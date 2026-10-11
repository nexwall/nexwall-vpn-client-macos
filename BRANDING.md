# Nexwall VPN for macOS (branded fork of Tunnelblick)

Public fork of [Tunnelblick](https://github.com/Tunnelblick/Tunnelblick) (GPLv2, see `COPYING`) for the SSL VPN
(OpenVPN) of the Nexwall firewall. The source of every released build is this repository.

## Status
Phase 1 (current): the upstream code builds unmodified on a GitHub-hosted macOS runner (`.github/workflows/macos-build.yml`).
Phase 2 (needs a real Mac for testing): rename the product. Tunnelblick's name is wired into the bundle identifier,
the privileged helper, launch daemons, the kernel-extension and `/Library/Application Support/Tunnelblick` paths,
so it must be renamed as one coordinated, tested change, not with a search-and-replace.
Phase 3: sign with an Apple Developer ID and notarize (needs the Apple Developer Program membership).

## Rules for this fork
Keep all upstream copyright and license files; keep the source public; do not use the "Tunnelblick" or "OpenVPN"
names/logos for the product once phase 2 is done. Branding assets: `branding/`.
