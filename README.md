# pngoptimizefolder
macOS folder action service that watches set folders and automatically optimizes PNG pictures using zopflipng     

![Screenshot](screenshot.png)
# Install
This service uses parallel and zopflipng utilities, make sure they are installed.

Homebrew:
```bash
brew install parallel
brew install zopfli
```

To add folder action service, open "PNG Optimize.workflow" and press Install.
After that go to "Folder Actions Setup..." and set folders that should be watched by this script.

Installation directory: ~/Library/Workflows/Applications/Folder Actions/

# Notice
Every *new* PNG file that gets dropped, downloaded or coppied into any of set folders gets optimized automatically, this service doesn't work recursively, e.g. new PNG files in ~/SetFolder/foobar/ won't get optimized.
