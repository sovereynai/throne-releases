# Sovereyn Throne Releases

**Public repository for Sovereyn throne daemon binary releases.**

This repository contains only pre-compiled binaries for the Sovereyn throne daemon. The source code remains proprietary and is hosted in a private repository.

## Downloads

Download the latest release for your platform from the [Releases page](https://github.com/sovereynai/throne-releases/releases).

### Available Platforms

- **macOS** (Intel): `throne_darwin_amd64.tar.gz`
- **macOS** (Apple Silicon): `throne_darwin_arm64.tar.gz`
- **Linux** (x86_64): `throne_linux_amd64.tar.gz`
- **Linux** (ARM64): `throne_linux_arm64.tar.gz`
- **Windows** (x86_64): `throne_windows_amd64.zip`
- **Windows** (ARM64): `throne_windows_arm64.zip`

## Installation

### Via Package Manager (Recommended)

**macOS/Linux (Homebrew):**
```bash
brew tap sovereynai/tap
brew install reign
```

**Windows (Scoop):**
```powershell
scoop bucket add sovereyn https://github.com/sovereynai/scoop-bucket
scoop install reign
```

### Manual Installation

1. Download the appropriate binary for your platform from [Releases](https://github.com/sovereynai/throne-releases/releases)
2. Extract the archive:
   ```bash
   # macOS/Linux
   tar -xzf throne_*.tar.gz
   
   # Windows
   unzip throne_windows_*.zip
   ```
3. Move the binary to your PATH:
   ```bash
   # macOS/Linux
   sudo mv throne /usr/local/bin/
   
   # Windows
   # Move throne.exe to a directory in your PATH
   ```
4. Run the daemon:
   ```bash
   throne serve
   ```

## Companion CLI

For the best experience, install the **reign** CLI (open source):
- Repository: https://github.com/sovereynai/reign
- License: MIT

## Links

- **Documentation**: https://github.com/sovereynai/throne#readme
- **Homebrew Tap**: https://github.com/sovereynai/homebrew-tap
- **Scoop Bucket**: https://github.com/sovereynai/scoop-bucket
- **Reign CLI**: https://github.com/sovereynai/reign

## Security

All binaries are:
- ✅ Built via GitHub Actions with reproducible builds
- ✅ Obfuscated with Garble
- ✅ Compressed with UPX (except macOS)
- ✅ SHA256 checksums provided

## License

The throne daemon is proprietary software.

Copyright (c) 2025 Sovereyn AI. All rights reserved.

---

**Made with ❤️ by the Sovereyn team**

👑 Rule Your AI Destiny!
