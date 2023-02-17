# Some Livebooks to learn some Elixir

1. [Elixir initiation Livebook](#elixir-initiation-livebook)
  
2. [First steps with Tasks Genservers and Supervisors](#first-steps-with-tasks-genservers-and-supervisors)

3. [Finite State machines with Elixir Erlang](#finite-state-machines-with-elixir-erlang)

4. [Streaming files](#stream-with-files)


## Elixir initiation Livebook

You have 3 ways to enjoy this Livebook

- If you have `Livebook` already installed, this is the best experience as you will use a more powerful computer (yours 🥳). Just click on the button below (or fork and run it):

[![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https%3A%2F%2Fgithub.com%2Fdwyl%2Flearn-elixir-with-livebook%2Fblob%2Fmain%2Flearn-elixir-on-livebook.livemd)

- with Docker
 <img src="https://user-images.githubusercontent.com/6793008/216023769-d2693462-1864-4204-b7cf-67378fce6d49.png" with="30" height="40" alt="docker"/>. 
Launch `Docker` and run the commands below:

```
docker run -p 8080:8080 -p 8081:8081 --pull always -e LIVEBOOK_PASSWORD="securesecret" livebook/livebook
```

and in another terminal you launch the browser (you will need to authenticate with "securesecret"):

```
open http://localhost:8080/import?url=https://github.com/dwyl/learn-elixir-with-livebook/blob/main/learn-elixir-on-livebook.livemd
```


## Tasks Genservers and Supervisors

Run this Livebook:

[![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https%3A%2F%2Fgithub.com%2Fdwyl%2Flearn-elixir-with-livebook%2Fblob%2Fmain%2Ftasks-genservers.livemd)

<hr />

## Finite State machines with Elixir Erlang

Run this Livebok:

[![Run in Livebook](https://livebook.dev/badge/v1/gray.svg)](https://livebook.dev/run?url=https%3A%2F%2Fgithub.com%2Fdwyl%2Flearn-elixir-with-livebook%2Fblob%2Fmain%2Fstate-machines.livemd)


## Stream with files:

[![Run in Livebook](https://livebook.dev/badge/v1/gray.svg)](https://livebook.dev/run?url=https%3A%2F%2Fgithub.com%2Fdwyl%2Flearn-elixir-with-livebook%2Fblob%2Fmain%2Fstream-files.livemd)
