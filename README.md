# Blockle Pre-built Binaries

These are the latest **Blockle** command-line tools and GUI wallet—ready to run, no build required.

---

## Why use `curl` instead of `git clone`?

Cloning the full Blockle source pulls down hundreds of megabytes of code, history, and build-tool dependencies that you don’t need if all you want is the ready-to-run executables. Downloading just the compressed tarball of binaries is:

- **Faster** – only ~XX MB to download instead of the entire repo.  
- **Simpler** – zero build steps; just extract and run.  
- **Cleaner** – keeps your workspace uncluttered by avoiding dozens of subdirectories.

---

## Download & Extract

1. **Download**  
   ```bash
   curl -L https://github.com/blocklechain/binaries/blockle-binaries.tar.gz \
     -o blockle-binaries.tar.gz
