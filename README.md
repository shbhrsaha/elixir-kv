# KV

Implementation of KV from Getting Started tutorial at elixir-lang.org

https://elixir-lang.org/getting-started/mix-otp/introduction-to-mix.html

Interactive:

`iex -S mix` (use `recompile()` to recompile)

Test:

`mix test`

Overview:

KV.Supervisor (Supervisor) -> makes sure KV.Registry (GenServer) is always running -> makes sure KV.Bucket (Agent) is monitored and retrieved