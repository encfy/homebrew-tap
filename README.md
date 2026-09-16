# encfy/homebrew-tap

Homebrew tap for the [encfy](https://github.com/encfy/platform) CLI — developer text tools with a Brazilian twist.

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

## Usage

```bash
encfy base64 encode "Olá"
encfy hash sha256 "abc"
encfy cpf 529.982.247-25
encfy slug "Gerador de URL amigável"
encfy config set-key encfy_live_...   # needed for API-backed commands
encfy cep 01001-000
```
