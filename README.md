# Nordic nRF51: development platform for [PlatformIO](https://platformio.org)

[![Build Status](https://github.com/platformio/platform-nordicnrf51/workflows/Examples/badge.svg)](https://github.com/platformio/platform-nordicnrf51/actions)

The Nordic nRF51 Series is a family of highly flexible, multi-protocol, system-on-chip (SoC) devices for ultra-low power wireless applications. nRF51 Series devices support a range of protocol stacks including Bluetooth Smart (previously called Bluetooth low energy), ANT and proprietary 2.4GHz protocols such as Gazell.

* [Home](https://registry.platformio.org/platforms/platformio/nordicnrf51) (home page in the PlatformIO Registry)
* [Documentation](https://docs.platformio.org/page/platforms/nordicnrf51.html) (advanced usage, packages, boards, frameworks, etc.)

# Usage

1. [Install PlatformIO](https://platformio.org)
2. Create PlatformIO project and configure a platform option in [platformio.ini](https://docs.platformio.org/page/projectconf.html) file:

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

Please navigate to [documentation](https://docs.platformio.org/page/platforms/nordicnrf51.html).
