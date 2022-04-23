# Discuss

To start your Phoenix server:

  * Install dependencies with `mix deps.get`
  * Create and migrate your database with `mix ecto.setup`
  * Start Phoenix endpoint with `mix phx.server` or inside IEx with `iex -S mix phx.server`

Now you can visit [`localhost:4000`](http://localhost:4000) from your browser.

Ready to run in production? Please [check our deployment guides](https://hexdocs.pm/phoenix/deployment.html).

## Learn more

  * Official website: https://www.phoenixframework.org/
  * Guides: https://hexdocs.pm/phoenix/overview.html
  * Docs: https://hexdocs.pm/phoenix
  * Forum: https://elixirforum.com/c/phoenix-forum
  * Source: https://github.com/phoenixframework/phoenix

# phoenix-discuss-tutorial

MIX_ENV=dev mix ecto.create
MIX_ENV=dev iex -S mix phx.server
recompile

## Folder to add Dependencies is located at: mix.exs 
  * mix deps.get
  * Generates documentation {:ex_doc, "~> 0.27", only: :dev, runtime: false}
  * Add comments to the Modules and functions
  * @moduledoc
  * Run inside the doc folder: mix docs

## Testing 
Folder to write the test is located at: test
  * Run mix test


## Create a migration 
  * MIX_ENV=dev mix ecto.gen.migration add_topics
  * MIX_ENV=dev mix ecto.migrate

## Create Model and Migration 
  mix phoenix.gen.model Topic topics title:string

## Testing
  * IO.inspect
