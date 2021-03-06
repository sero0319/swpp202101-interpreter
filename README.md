# SWPP Interpreter

This interpreter executes SWPP assembly programs.

## Authors

Sung-Hwan Lee, Seunghyeon Nam

## Build

- Requirement: cmake >= 3.10

```bash
# e.g. install cmake in ubuntu
sudo apt update
sudo apt install cmake
```

- Build

```bash
# creates "sf-interpreter"
./build.sh
```

## Run

```bash
# executes a given assembly program and prints status to "sf-interpreter.log"
# detailed information on the cost of an execution is emitted to "sf-interpreter-cost.log"
# note that it gets a standard input on call to "read"
./sf-interpreter <input assembly file>
```
