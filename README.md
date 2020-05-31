# ADLINK DAQ USB driver (pyusb)

A fully open source python implementation to access ADLINK DAQ USB devices.

Supported devices:

* USB DAQ 7250

## USB DAQ 7250

The 7250 has:

* 8-CH relay output
* 8-CH digital inputs
* 2-CH counter

| features                           | supported | tested |
| ---------------------------------- | -------   | ----   |
| get device id                      | X         | X      |
| get/set relay state                | X         | X      |
| get/set relay initial state        | X         | X      |
| get digital input state            | X         | X      |
| set digital input min pulse width  | X         |        |
| enable digital input filter        | X         |        |
| digital input COS/IRQ              | X         |        |
| read COS changes                   |           |        |
| get counter frequency              | X         | X      |
| get counter edge                   | X         | X      |
| set counter min pulse width        | X         |        |
| enable counter filter              | X         |        |
| set counter polarity               | X         |        |
| reset counter frequency            | X         |        |
| reset counter counter              | X         |        |