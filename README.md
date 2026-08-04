# touch

One small Rust CLI for creating and removing files (a multi-file touch / delete helper).

## Requirements

- Rust (cargo + rustc), edition 2021

No environment variables are required for the current CLI.

## Install

```bash
git clone https://github.com/DevChaudhary78/touch-rs.git
cd touch-rs
cargo build --release
```

Optional:

```bash
cargo install --path .
```

## Usage

```bash
# create files
touch file.txt
touch a.txt b.txt notes.md

# remove
touch -r obsolete.txt
touch --remove old1.txt old2.txt

# help
touch -h
touch --help
```

## License

See repository terms. Contributions welcome via PR.
