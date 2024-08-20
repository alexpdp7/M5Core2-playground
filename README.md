# Playing with the M5Core2

## Getting started

The M5Burner tool is a GUI application that can download and flash M5Core2 firmwares, including going back to the `Core2FactoryTest` preloaded firmware.

### Interesting images

* `UIFlow2.0` is the newest web-based tool to do easy M5Core2 development.
  However, it requires registration.
* `UIFlow_Core2` is an older version, but it does not require registration.
  When flashing, you configure wireless networking details.
  Then, you get an API key that you can use on https://flow.m5stack.com/ to do browser-based development (graphical Blockly or Python).

## Rust

The instructions in [The Rust on ESP Book](https://docs.esp-rs.org/book/) seem to apply to the M5Core2.
If you follow the instructions for the `esp-template`, you can flash a sample program that prints hello world in a loop.

Afterwards, you can use M5Burner to go back to the preloaded factory test firmware.
