# Some Livebooks to learn some Elixir

## [Elixir initiation Livebook](#elixir-initiation-livebook)
  ### [ Run it locally](#run-it-locally)
  ### [Run it the cloud](#run-it-in-the-cloud)
  ### [Install Livebook webbapp](#install-livebook-webbapp)
   
## [First steps with Tasks Genservers and Supervisors](#first-steps-with-tasks-genservers-and-supervisors)

## [Finite State machines with Elixir Erlang](#finite-state-machines-with-elixir-erlang)


## Elixir initiation Livebook

You have 3 ways to enjoy this Livebook

#### Run it locally

- If you have `Livebook` already installed, this is the best experience as you will use a more powerful computer (yours 🥳). Just click on the button below (or fork and run it):

[![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https%3A%2F%2Fgithub.com%2Fdwyl%2Flearn-elixir-with-livebook%2Fblob%2Fmain%2Flearn-elixir-on-livebook.livemd)

- with Docker
 <img src="https://user-images.githubusercontent.com/6793008/216023769-d2693462-1864-4204-b7cf-67378fce6d49.png" with="30" height="40" alt="docker"/>


If you have `Docker` installed,  launch `Docker` and run the commands below:

```
docker run -p 8080:8080 -p 8081:8081 --pull always -e LIVEBOOK_PASSWORD="securesecret" livebook/livebook
```

and in another terminal you launch the browser (you will need to authenticate with "securesecret"):

```
open http://localhost:8080/import?url=https://github.com/dwyl/learn-elixir-with-livebook/blob/main/learn-elixir-on-livebook.livemd
```


#### Run it in the cloud

If you don't have `Elixir` nor `Livebook` installed, you can still run the Elixir initiation `Livebook`. You (**right**-)click on the grey button **"Run in Livebook"** below. 

👉 [![Run in Livebook](https://livebook.dev/badge/v1/gray.svg)](https://livebook.dev/run?url=https%3A%2F%2Fdwyl-learn-elixir.fly.dev%2F)

:heavy_exclamation_mark: You **right-click"** to keep this reminder page open 😉 because you will need to remember to do 2 things:
  -  firstly, look at the bottom for the link "see source" as showed below, 🤔, and click.

<img width="355" alt="Screenshot 2023-01-13 at 10 23 14" src="https://user-images.githubusercontent.com/6793008/212285838-96ff4672-e36a-4a89-8efa-dee53a32a405.png">

  -  and finally, select the file [dwyl-learn-elixir.livemd]. It should be printed in green, and "join session". 🤗
   

#### Install Livebook webbapp

Easy peasy. Just click below:

👉  [<img width="326" alt="Screenshot 2023-01-13 at 10 15 23" src="https://user-images.githubusercontent.com/6793008/212283403-116dbf5c-eea4-4c16-88df-b9aba86e209a.png">](https://livebook.dev/)


## First steps with Tasks Genservers and Supervisors

Run this Livebook:

[![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https%3A%2F%2Fgithub.com%2Fdwyl%2Flearn-elixir-with-livebook%2Fblob%2Fmain%2Fabout-genservers.livemd)

## Finite State machines with Elixir Erlang

Run this Livebok:

[![Run in Livebook](https://livebook.dev/badge/v1/gray.svg)](https://livebook.dev/run?url=https%3A%2F%2Fgithub.com%2Fdwyl%2Flearn-elixir-with-livebook%2Fblob%2Fmain%2Fabout-state-machines.livemd)
