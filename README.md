# Dulox

[Lox](https://github.com/munificent/craftinginterpreters) implementation written in [Dictu.](https://github.com/dictu-lang/Dictu)

## Running

To run Dulox you must first have Dictu installed on your system. At the time of writing Dulox uses features within Dictu that have not fully been released, so when building Dictu make sure it's done from the `develop` branch.

```
$ git clone -b develop https://github.com/dictu-lang/Dictu.git
$ cd Dictu
$ cmake -DCMAKE_BUILD_TYPE=Release -B ./build 
$ cmake --build ./build
```

Dulox can either be executed on a file or opened as a REPL

```bash
# Open as REPL
dictu lox.du

# Interpet file
dictu lox.du file.lox
```

### Note

Dulox implements the Java section of the [craftinginterpreters book](https://craftinginterpreters.com/) and is at section 8.1

## License

This project is licensed under the MIT license.