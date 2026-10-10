# lux-demo-face
A [Second Movement](https://github.com/joeycastillo/second-movement) watch face that receives text over light, using [lux-rx](https://github.com/eiriksm/lux-rx).

## Description

Samples the OPT3001 light sensor and decodes text sent as blinking light. Received text can set the time, be echoed back over FESK, or be written to files on the watch. See `src/lux_rx_demo_face.h` for the commands and buttons.

## Installation

Install with composer, alongside `eiriksm/lux-rx`:

```
composer require eiriksm/lux-demo-face:dev-main
```

The face depends on the Second Movement firmware headers (`movement.h`, `fesk_session.h`, `base32.h` and friends), so it only builds as part of the firmware.
