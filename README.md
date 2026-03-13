# rust-template

Cargo-generate template for Rust projects with standardized CI.

## Usage

```bash
cargo generate natepiano/rust-template --name my-project
```

### Options

| Flag | Effect |
|------|--------|
| `--bin` (default) | Binary crate with `main.rs` |
| `--lib` | Library crate with `lib.rs` |
| `--define bevy=false` | Omit Bevy CI support |

## What you get

- GitHub Actions CI: formatting, taplo, clippy, build, nextest, cargo-mend
- Dual MIT/Apache-2.0 license
- Changelog
