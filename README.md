#  Unity Device Simulator Definitions For All iPhone 14 & 15 Models
A simple .device (Device Info Asset) JSON file with settings for the iPhone 14 Pro and a device border adjusted to the standard style of Unity devices. 

Hardware specifications taken from the Apple website:
* [iPhone 14 - Technical Specifications](https://support.apple.com/en-gb/111850)
* [iPhone 14 Plus - Technical Specifications](https://support.apple.com/en-gb/111854)
* [iPhone 14 Pro - Technical Specifications](https://support.apple.com/en-gb/111849)
* [iPhone 14 Pro Max - Technical Specifications](https://support.apple.com/en-gb/111846)
* [iPhone 15 - Technical Specifications](https://support.apple.com/en-gb/111831)
* [iPhone 15 Plus - Technical Specifications](https://support.apple.com/en-gb/111830)
* [iPhone 15 Pro & Pro Max - Technical Specifications](https://www.apple.com/uk/iphone-15-pro/specs/)

Safe Area specifications taken from [Use Your Loaf](https://useyourloaf.com/):
* [iPhone 14 Models ](https://useyourloaf.com/blog/iphone-14-screen-sizes/)
* [iPhone 15 Models ](https://useyourloaf.com/blog/iphone-15-screen-sizes/)

# Installation Instructions

## Manual Installation
* In an existing Unity project, create a new folder called `Devices` in any directory e.g. `<project directory>/Assets/Configs/Devices`.
* Copy the contents of this repository to the chosen folder.

## Git UPM Installation
* Open unity package manager window
* Click the `+` button
* Choose `Add package from git URL`
* Paste the following link
```
https://github.com/henryprescott/com.unity.device-simulator-Apple-iPhone-14-and-15-models.git
```

Or simply
* Open `Packages/manifest.json` in your project
* Add the following to the dependencies section:
```json
"henryprescott.device-simulator.devices": "https://github.com/henryprescott/com.unity.device-simulator-Apple-iPhone-14-and-15-models.git"
```

### Known Issues
* Some images may not be pixel perfect, but are close enough.
* 'systemInfo' parameters are not accurate, just roughly populated with data.
