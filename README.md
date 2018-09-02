# QuickNFO

macOS QuickLook plugin for previewing NFO files.

Forked from the original repository since it was last updated in 2014. This is mainly done to distribute a current binary for easy use and to update the installation instructions. All credits go to the author [@planbnet](https://github.com/planbnet), I just cleaned up the surroundings a bit.

Uses libiconv to convert the NFO text to UTF-8 and WebKit to render the output.

The current version supports preview and thumbnail generation. Rendering with HiDPI, like on retina displays, is also supported.

## Installation

Build the Xcode project or download the [compiled plugin](https://github.com/herrbischoff/QuickNFO/releases). Then copy the file `QuickNFO.qlgenerator` to `/Library/QuickLook`.

## Examples

### Thumbnails
<img src="examples/thumbnails.png" alt="QuickLook Thumbnails" width="722" height="171">

### Preview
<img src="examples/preview.png" alt="QuickLook Preview" width="606" height="817">
