<h1 align="center">hsu</h1>

<div align="center">
  <!-- Badges -->
    <img src="https://img.shields.io/badge/Version-PRERELEASE-blue.svg?longCache=true&style=popout-square"
      alt="Version" />
    <img src="https://img.shields.io/badge/License-GPLv2.0-red.svg?longCache=true&style=popout-square"
      alt="License" />
</div>

<div align="center">
  <strong>hsu is a Magisk module for hiding Magisk and root by entirely disabling and hiding them</strong>
</div>

  <h3>
    <a href="https://github.com/rmnscnce/hsu">
      Source Code
    </a>
    <span> | </span>
    <a href="https://example.org/">
      XDA Link (placeholder)
    </a>
  </h3>
</div>

Have you ever tried to use the [McDonald's app (proprietary, non-free software)](https://play.google.com/store/apps/details?id=com.mcdonalds.app&hl=en) while rooted on Magisk? I have, and it still doesn't work even if I added it into the MagiskHide blocklist. This Magisk module will help you circumvent those detection methods by completely disabling and hiding Magisk and root. Not even Magisk can detect itself being installed.

### Installation steps
To install `hsu`, you will use the very same installation steps as any other Magisk modules out there.
- Download the latest release from [here](https://github.com/rmnscnce/hsu/releases)
- Install the module using Magisk Manager
- Reboot your device

### Usage
To use hsu is a very easy thing to do. The interactive shell is made to make `hsu` really easy to use. You can start `hsu` by using this command on your terminal emulator app:
> `hsu [argument]`

And here is the available arguments to use:
Argument | Function
------------ | -------------
(*anything but listed below*) | Run interactive `hsu`
`help` | Show the help menu
`hide` | Hide root and Magisk (given the environment has been set up before)
