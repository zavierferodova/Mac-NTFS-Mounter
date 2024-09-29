# MAC NTFS Mounter
This script used for mount NTFS disk on Mac OS and give read-and write access.

## Installation
1. Install latest version of MacFuse using Homebrew
```bash
brew install --cask macfuse
```
2. Add homebrew-fuse repository and install ntfs-3g-mac
```bash
brew tap gromgit/homebrew-fuse
brew install ntfs-3g-mac
```

## Usage
1. Plug your NTFS disk and make sure the disk volume is already mounted
2. Add execute permission on `ntfsmounter` script
```bash
chmod +x ntfsmounter
```
3. Run it with `sudo`
```bash
sudo ./ntfsmounter
```

## Screenshot
![Terminal screenshot](https://github.com/zavierferodova/Mac-NTFS-Mounter/blob/main/screenshots/image.png?raw=true)