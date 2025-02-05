# Toggle Pinned Tab

Extension to Toggle Pinned Tabs in firefox via a keybind

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

### Installation

In Zen Browser or Firefox, go to `about:addons`. Click the settings gear next to `Manage Your Extensions`, and select `Install Add-on from File`.

Choose the built zip file. And allow unsigned addons

### Usage

Used in Zen browser. Another item that is useful in Zen, is to disable the default command for Bookmarking a tab. Once this is done, and the addon is installed, this will mimic Arc browsers Pin Tab command

### Modifying Keybind

In `manifest.json` update the keybind to whatever you would like. Then run `pnpx web-ext build --overwrite-dest` to build out a new extension package to be installed.

### Contributing

Do as you please.
