# Material Captive Portal for Untangle

Custom Material designed captive portal for Untangle firewall installations. This custom web design not only features a Wifi login portal, but a customized download page for clients to easily find and install your root CA.

## Installation

Upload these files to your Untangle server! Make sure you replace [`RootCAInstaller.exe`](cert/RootCAInstaller.exe) and [`root_authority.crt`](cert/root_authority.crt) with your own files you can find in Untangle, for your clients to download.

**Note:** I don't have my Untangle firewall installed at the moment so this has not been tested, but it should work!

## Screenshots

### Wifi Portal login

![](https://i.imgur.com/z5zBNXR.png)

### Certificate download

![](https://i.imgur.com/bKOuIxp.png)

## Credit

This is a slimmed down version of Cryosim's [CaptivePortal](https://github.com/Cryosim/CaptivePortal), which used a Bootstrap design.
