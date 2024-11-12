# PDF Cracker using RUST

This project is copied from: https://github.com/mufeedvh/pdfrip

Create a new project:

```bash
cargo new pdfrip
```

update dependencies in `Cargo.toml`:

```python
pdf = "0.7.2"
rayon = "1.5.1"
snmalloc-rs = "0.2.28"
indicatif = "0.16.2"
clap = "3.0.14"
colored = "2.0.0"
once_cell = "1.9.0"
```

Run Cargo build:

```shell
cargo build
```

if error:
```
failed to execute command: No such file or directory (os error 2)
  is `cmake` not installed?
```

install cmake: `sudo apt install cmake`


to run:
```
./target/debug/pdfrip --help
```
