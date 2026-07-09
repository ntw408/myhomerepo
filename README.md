# Basic C Main Program

This repository intentionally contains only a minimal C entrypoint and this short explanation file.

`MAIN.C` defines a standard `int main(void)` function, prints `Hello, world!`, and returns `0` to indicate successful execution.

## Build

```sh
cc -x c -Wall -Wextra -pedantic -std=c11 MAIN.C -o main
```

## Run

```sh
./main
```
