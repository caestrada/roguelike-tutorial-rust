# Roguelike Tutorial Rust (1)

Tutorial [LINK](https://tomassedovic.github.io/roguelike-tutorial/index.html)

## Notes

Created a new project. We’re passing `--bin` because we’re making a binary program: if we were making a library, we’d pass `--lib`.
```shell
$ cargo new --bin roguelike
```

## >_ Commands

```shell
# Create a new project
$ cargo new <project_name>
```

```shell
# Build the project
$ cargo build

# This command creates an executable file in 'target/debug/<project_name>
```

```shell
# Running the executable
$ cargo run

# Build artifacts in release mode, with optimizations
cargo run --release
```

```shell
# Checks your code to make sure it compiles but doesn’t produce an executable.
$ cargo check
```