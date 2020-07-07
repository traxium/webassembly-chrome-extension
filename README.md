## WebAssembly Chrome Extension (in C# and Blazor)

### Installation instructions:

1. Download the latest release (.zip) from https://github.com/traxium/webassembly-chrome-extension/releases
1. Unpack (e.g. to `~/webassembly-chrome-extension-v0.1.0`)
1. In Chrome go to `chrome://extensions/`
1. Enable [Developer mode] (if not enabled)
1. Click [Load unpacked]
1. Go inside the unpacked folder (e.g. inside `~/webassembly-chrome-extension-v0.1.0`)
1. Click [Select Folder]/[Open] button

### Build instructions:

1. Open this repo in Visual Studio 2019 (or newer)
   1. Click [Build] -> [Build Solution] (or press Ctrl + Shift + B)
2. In Chrome go to `chrome://extensions/`
   1. Enable [Developer mode] (if not enabled)
   1. Click [Load unpacked]
   1. Point to `...\WebAssemblyBlazorChromeExtension\bin\Release\netstandard2.1\wwwroot\` or `...\WebAssemblyBlazorChromeExtension\bin\Debug\netstandard2.1\wwwroot\`
   1. Click [Select Folder]/[Open] button
