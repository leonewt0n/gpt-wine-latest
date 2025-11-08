# gpt-wine-latest
Gcenx's Wine with latest Wine and DXMT

Install Gcenx's cask (contains old 7.7 wine)
```
brew install --cask --no-quarantine gcenx/wine/game-porting-toolkit
```

Extract release zip and replace the game-porting-toolkit.app in /Applications/

May have to:

```
sudo xattr -d com.apple.quarantine /Applications/Game Porting Toolkit.app
```

# Installing Steam
```
wine64 ~/Downloads/steamsetup.exe
```

# Running Steam
```
 wine64 .wine/drive_c/Program\ Files\ \(x86\)/Steam/steam.exe
```
