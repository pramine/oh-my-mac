# setting my mac

## display hidden files

```bash
cd /Applications/Utilities
defaults write com.apple.finder AppleShowAllFiles TRUE;killall Finder
```

restore

```bash
cd /Applications/Utilities
defaults write com.apple.finder AppleShowAllFiles FALSE;killall Finder
```