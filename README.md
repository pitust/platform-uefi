# UEFI
UEFI is da hardware firmware lol.

# Usage

1. [Install PlatformIO](http://platformio.org)
2. Create PlatformIO project and configure a platform option in [platformio.ini](http://docs.platformio.org/page/projectconf.html) file:

## Stable version

```ini
[env:stable]
platform = windows_x86
board = ...
...
```

## Development version

```ini
[env:development]
platform = https://github.com/platformio/platform-windows_x86.git
board = ...
...
```

# Configuration

I don't know. 
