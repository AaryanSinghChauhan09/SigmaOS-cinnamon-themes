# SigmaOS Cinnamon themes

This crate is currently a `no_std` identity scaffold. Its only public type
constructs a `Component` with the fixed name `SigmaOS Component`. It does not
provide theme assets, load styles, or change desktop appearance.

The inline unit test checks only the fixed scaffold name; it does not validate
theme selection or rendering.

## Build

```sh
cargo check --lib
```

## License

Apache-2.0. See [`Cargo.toml`](Cargo.toml).
