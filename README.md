# Kharcha Note config

The signed settings file of Kharcha Note: bank message formats, an update notice and switches. It holds patterns and words only, never code, and the app only accepts it when the signature matches the key built into the app.

Live address: https://aman-sidd.github.io/kharcha-note-config/config.signed.json

To publish a change: edit `config.json`, raise `version`, then from the app repository run `node scripts/config-tool.mjs check`, then `sign`, and push `config.signed.json`.
