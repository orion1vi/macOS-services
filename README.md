# generaterandomname
macOS service to generate random file names using OpenSSL       
# Install
Service uses OpenSSL to generate random values, make sure openssl package is installed.

Homebrew:
```bash
brew install openssl
```
To add service:
```bash
bash add_service.sh
```
Or open "Generate Random File Name.workflow" and press Install.

Installation directory: ~/Library/Services/
# Usage
Select one or more files in Finder, right click to open context menu, move down to Services and press on "Generate Random File Name"
