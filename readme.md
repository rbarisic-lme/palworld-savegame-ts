# Palworld Savegame TS

## Savegame Parser
Because Palworld files are subject to change, this provides a clean implementation where you can pop in Parsers for files by demand and still utilize the same utilize to retrieve certain information.

This is a very early release and was decoupled from my Palworld Server Control Dashboard Application.

## Types
Utilizes Typescript to build intellisense previews for interacting with the save files.

## Support
- Currently only supports v3 Savefiles (Palworld v0.1.4.0, v0.1.3.0)
- Doesn't support Level.sav yet. feel free to contribute and add types for Level.sav