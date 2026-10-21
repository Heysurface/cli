# Heysurface CLI

The Heysurface CLI and bundled Skill connect your AI harness to an authorized Heysurface account. This repository distributes the installable alpha package; the product source repository is private.

## Install the alpha

Install Node.js 22 or later, then run:

```bash
npm install --global https://github.com/Heysurface/cli/releases/download/v0.1.2-alpha/heysurface-cli-0.1.2.tgz
heysurface --version
heysurface skill install
```

Open a new Claude Code or Cursor chat and invoke `/heysurface`. The Skill will guide account connection or let an authorized operator evaluate a public company. Account access remains invitation-only during the private alpha.

The [v0.1.2-alpha release](https://github.com/Heysurface/cli/releases/tag/v0.1.2-alpha) includes the package archive and its SHA-256 checksum. Verify the archive before installing when transferring it outside GitHub.

## License

The CLI and Skill are distributed under the [Heysurface CLI License](LICENSE). Public download does not grant a right to redistribute the package or access the Heysurface service.
