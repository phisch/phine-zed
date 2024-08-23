# Phine zed theme
Work in progress zed theme.

## Variables support
I wrote a small helper application to substitute variables in the theme file.
You can check it out in the [phisch/variable-substitutor](https://github.com/phisch/variable-substitutor) repository.

Here is a quick guide on how to use it:

```sh
git clone git@github.com:phisch/variable-substitutor.git
cargo build --release --manifest-path variable-substitutor/Cargo.toml
./variable-substitutor/target/release/substitutor -o ~/.config/zed/themes/phine.json themes/phine.json -w
```
