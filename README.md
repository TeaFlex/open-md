# open-md.sh

Small utility command to open markdown file in the browser.
It works by rendering markdown to html with `pandoc` and storing the result in a temporary file.

## Installation
You must intall `pandoc` in the first place. For Debian based distros:
```sh
sudo apt update && sudo apt install pandoc -y
```

The copy/paste the script anywhere you like on your system in order to use it.
Don't forget to make it executable.

## Usage
```sh
open-md.sh ./some-markdown-file.md
```

