# Building
### Dependencies
We use rust bindings for bluez, a bluethooth library for linux.
- Fedora(-based)
```
  sudo dnf in bluez-libs-devel
```

- Debian(-based)
```
  sudo apt install libbluethooth-dev
```

### Building

```
   cargo b -r
```
The Binary will be in `target/release/we_golf_server`

you can also just run it with

```
   cargo r -r
```

For development omit the `-r` or `--release` flag for fast builds
