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
