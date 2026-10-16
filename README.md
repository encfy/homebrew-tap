# encfy/homebrew-tap

Homebrew tap and public binary releases for the [Encfy](https://www.encfy.com) CLI — developer text tools with a Brazilian twist.

```bash
brew tap encfy/tap
brew install encfy
encfy --version
```

Or in one line:

```bash
brew install encfy/tap/encfy
```

The formula in `Formula/encfy.rb` is generated and updated automatically by GoReleaser
when a `cli/vX.Y.Z` tag is pushed to `encfy/platform`. Do not edit it by hand.

Binary archives for macOS, Linux and Windows (AMD64 and ARM64), together with
SHA-256 checksums, are available in [Releases](https://github.com/encfy/homebrew-tap/releases).
The CLI is proprietary (all rights reserved); the MIT license of the separate
`@encfy/core` package does not apply to these binaries.

## Usage

```bash
encfy base64 encode "Olá"
encfy hash sha256 "abc"
encfy cpf 529.982.247-25
encfy slug "Gerador de URL amigável"
encfy config set-key encfy_live_...   # needed for API-backed commands
encfy cep 01001-000
```
