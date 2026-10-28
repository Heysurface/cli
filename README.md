# Obi CLI

Obi, the AI Search Employee by Heysurface, Inc., works in your own AI assistant. This repository distributes the installable CLI and bundled Skill for invited Alpha accounts. The product source repository is private.

## Install the Alpha

Node.js 22 or later is required.

```bash
npm install --global https://github.com/Heysurface/cli/releases/download/v0.1.5-alpha/heysurface-cli-0.1.5.tgz
obi --version
obi skill install
```

Version `0.1.5` provides both `obi` and the compatible `heysurface` command. They share the same account connection. The existing `/heysurface` Skill remains available.

Open a new assistant chat:

- Claude Code or Cursor: type `/obi`.
- Codex CLI: type `$obi` or select Obi through `/skills`.
- Codex desktop: select Obi from the skills picker.

Obi asks which business to work on in the conversation. Account access remains invitation-only; downloading the public package does not enable public signup or grant paid capabilities.

## Verify the download

The [v0.1.5-alpha release](https://github.com/Heysurface/cli/releases/tag/v0.1.5-alpha) includes the package and `heysurface-cli-0.1.5.tgz.sha256`. On macOS or Linux, download both files into the same directory, then run:

```bash
shasum -a 256 -c heysurface-cli-0.1.5.tgz.sha256
npm install --global ./heysurface-cli-0.1.5.tgz
```

Archive SHA-256: `e679718a910e8867b6795113d18f058a22ff87bc42b9cb5d7ca397f000d4da19`.

## Work with Obi

The Skill guides sourced business research, Business review and buyer-question corrections, measured scan review, strategies, and saved content revisions. Draft history and export retain the selected revision. Authorized operators can evaluate a public company in a separate case without claiming ownership of that company's website.

Public research and reasoning use the capabilities available in your assistant. Version 0.1.5 imports complete native browser observations, discovers JavaScript-rendered links and resumes the existing research inventory. The bundled capture guide uses actual navigation metadata; the CLI does not install a browser or buy hosted research automatically. Engine scans run on Heysurface servers after the reviewed question version and authorized coverage are approved. Purchase preparation requires explicit confirmation and returns a browser checkpoint. Saved paid scope can resume within verified capacity without creating another checkout; a scan already admitted retains its saved questions and budget.

Public package availability does not authorize publishing content or starting paid work. Assistant search/browser availability and subscription limits still apply.

## Previous releases

[v0.1.4-alpha](https://github.com/Heysurface/cli/releases/tag/v0.1.4-alpha), [v0.1.3-alpha](https://github.com/Heysurface/cli/releases/tag/v0.1.3-alpha) and [v0.1.2-alpha](https://github.com/Heysurface/cli/releases/tag/v0.1.2-alpha) remain available with their original assets.

## License

The CLI and Skill are distributed under the [Heysurface CLI License](LICENSE). Public download does not grant a right to redistribute the package or access the Heysurface service. Third-party notices remain included in the package.
