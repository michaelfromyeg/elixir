# elixir

Hello, world in Elixir. For CPSC 418.

## Setup

Install dependencies.

```plaintext
sudo apt-get update
sudo apt-get install inotify-tools
```


```plaintext
brew install erlang elixir

mix local.hex
mix archive.install hex phx_new
```

Initialize a new project; install packages.

```plaintext
mix phx.new hello_world
cd hello_world
mix deps.get
```

Run the server.

```plaintext
mix phx.server
```

