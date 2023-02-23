# pokedex-cli

A Pokedex in a command-line REPL.

## Example usage

```bash
Pokedex > catch pidgey
Throwing a Pokeball at pidgey...
pidgey was caught!
You may now inspect it with the inspect command.
Pokedex > catch caterpie
Throwing a Pokeball at caterpie...
caterpie was caught!
You may now inspect it with the inspect command.
Pokedex > pokedex
Your Pokedex:
 - pidgey
 - caterpie
```

## How to play with it

1. install go from https://go.dev/doc/install
2. download the repo
3. Open your terminal and cd to the root of this project
4. check go version (if not successful, then go is not properly installed)
5. run "go run main.go" in the terminal and play with it.

## Ideas for extending the project

1. Update the CLI to support the "up" arrow to cycle through previous commands
2. Simulate battles between pokemon
3. Add more unit tests
4. Refactor your code to organize it better and make it more testable
5. Keep pokemon in a "party" and allow them to level up
6. Allow for pokemon that are caught to evolve after a set amount of time
7. Persist a user's Pokedex to disk so they can save progress between sessions
8. Use the PokeAPI to make exploration more interesting. For example, rather than typing the names of areas, maybe you are given choices of areas and just type "left" or "right"
9. Random encounters with wild pokemon
10. Adding support for different types of balls (Pokeballs, Great Balls, Ultra Balls, etc), which have different chances of catching pokemon
