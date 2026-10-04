# Switchboard releases

Signed builds of Switchboard for macOS (Apple silicon). This repository holds release
downloads only, no source.

- **Install:** download `Switchboard-<version>-arm64.dmg` from the latest release, open it, and
  drag Switchboard to Applications. The first launch needs System Settings → Privacy &
  Security → Open Anyway (the app is not notarised yet).
- **Updates:** an installed Switchboard checks this repository itself and offers an update in
  its Inbox. Every download is checked against a signing key built into the app before it is
  installed; nothing installs without your click.
- Each `.zip` and `.dmg` has a `.minisig` beside it: a [minisign](https://jedisct1.github.io/minisign/)
  signature you can check by hand with the public key shipped in the app.
