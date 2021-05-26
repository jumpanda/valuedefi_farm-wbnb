# Valuedefi FARM-wBNB

## Requirements

- Elixir 1.12.0 (Erlang/OTP 22+)
- Livebook
  - Install (after Elixir)
  `mix escript.install hex livebook`

## How to use
- start Livebook server
```bash
# Start the Livebook server
livebook server
```
- go to link given in shell i.e. http://localhost:8080/?token=ttegxuvdibrssiu3i5zcso7onxaycz4r
- navigate to this repository and open `notebook.livemd`
- evaluate all sections

## Notes
- Ignores transfers and only considers minting/destroying LP-tokens
- Uses last known "good" liquidity change as LP-token -> $FARM rate
- Only takes tx pre exploit into account
