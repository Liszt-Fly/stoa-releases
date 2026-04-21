# stoa Releases

This repository hosts public release artifacts for `stoa`.

## Install

### macOS and Linux

Install with Homebrew:

```sh
brew install Liszt-Fly/tap/stoa
```

Or add the tap first:

```sh
brew tap Liszt-Fly/tap
brew install stoa
```

### Windows

Install with Scoop:

```powershell
scoop bucket add stoa https://github.com/Liszt-Fly/scoop-bucket
scoop install stoa
```

### Manual Download

Download archives from the latest release:

https://github.com/Liszt-Fly/stoa-releases/releases/latest

Available packages include:

- `stoa_Darwin_arm64.tar.gz`
- `stoa_Darwin_x86_64.tar.gz`
- `stoa_Linux_arm64.tar.gz`
- `stoa_Linux_x86_64.tar.gz`
- `stoa_Windows_x86_64.zip`
- `checksums.txt`

## Verify

After installing:

```sh
stoa --version
```

For manual downloads, compare the downloaded file's SHA-256 checksum with
`checksums.txt` from the release.

## Package Repositories

- Homebrew tap: https://github.com/Liszt-Fly/homebrew-tap
- Scoop bucket: https://github.com/Liszt-Fly/scoop-bucket
