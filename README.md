# Installation

To install requried version open [releases](https://github.com/tonfactory/tons-releases/releases) page. Scroll down if you want to find older versions. We highly recommend to install the latest one.


# Versions

Currently, only MacOS versions are compiled.

### MacOS

You can see different assets:
- tons-macos-installer-intel-*.pkg
- tons-macos-installer-m1-*.pkg
- beta-tons-macos-installer-intel-*.dmg

Choose the right version according to your Mac's processor model. You can find it under Apple > About This Mac > Processor.

#### .pkg

This installation type will unpack all required files on your system and move them to the right places.

To run application after the installation, run Terminal application and type the following command.
```bash
$ tons
```

*Note: first startup takes longer than usual*

To delete application, type the following command in your Terminal.
```bash
$ sudo bash /opt/tons/uninstall.sh
```

#### .dmg

This installation type will create .app aplication in your Applications folder.

To run application just double click on it in the Applications folder or find it in the Launchpad by typing 'tons-interactive'.

*Note: first startup takes longer than usual*

To delete application just drop tons-interactive to the bin.
