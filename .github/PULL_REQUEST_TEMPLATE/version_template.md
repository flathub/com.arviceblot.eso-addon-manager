# [VERSION]

Change summary.

## Release checklist

- [ ] Bump version in `Cargo.toml`
- [ ] Add release notes to `com.arviceblot.eso-addon-manager.metainfo.xml`
- [ ] Take new screenshots if applicable
- [ ] Update `cargo-sources.json`:

  ```shell
  python3 flatpak-cargo-generator.py Cargo.lock -o cargo-sources.json
  ```

- [ ] `cargo-sources.json`
- [ ] git commit hash in `com.arviceblot.eso-addon-manager.json`
