# Nordic nRF51: development platform for [PlatformIO](http://platformio.org)
[![Build Status](https://travis-ci.org/platformio/platform-nordicnrf51.svg?branch=develop)](https://travis-ci.org/platformio/platform-nordicnrf51)
[![Build status](https://ci.appveyor.com/api/projects/status/e6cno5podkuha0ox/branch/develop?svg=true)](https://ci.appveyor.com/project/ivankravets/platform-nordicnrf51/branch/develop)

The Nordic nRF51 Series is a family of highly flexible, multi-protocol, system-on-chip (SoC) devices for ultra-low power wireless applications. nRF51 Series devices support a range of protocol stacks including Bluetooth Smart (previously called Bluetooth low energy), ANT and proprietary 2.4GHz protocols such as Gazell.

* [Home](http://platformio.org/platforms/nordicnrf51) (home page in PlatformIO Platform Registry)
* [Documentation](http://docs.platformio.org/page/platforms/nordicnrf51.html) (advanced usage, packages, boards, frameworks, etc.)

# Usage

1. [Install PlatformIO](http://platformio.org)
2. Create PlatformIO project and configure a platform option in [platformio.ini](http://docs.platformio.org/page/projectconf.html) file:

## Stable version

```ini
[env:stable]
platform = nordicnrf51
board = ...
...
```

## Development version

```ini
[env:development]
platform = https://github.com/platformio/platform-nordicnrf51.git
board = ...
...
```

# Configuration

Please navigate to [documentation](http://docs.platformio.org/page/platforms/nordicnrf51.html).
