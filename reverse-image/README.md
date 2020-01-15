# reverseimageservice
macOS service that adds reverse image search to Finder

# Install
This service can optionally use parallel for faster performance.

Homebrew:

```bash
brew install parallel
```

To add service, open "Reverese Image Search.workflow" and press Install.

Installation directory: ~/Library/Services/

# Usage
Select one or more pictures in Finder, right click to open context menu, move down to Services and click on "Reverse Image Search", new tab should open on your default browser with image search results. If more than one image was selected, new tab will open one after another after each request has been handled.

Currently only Google image search service is being used.
