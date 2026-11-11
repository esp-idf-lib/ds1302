# Example for `ds1302` driver

## What it does

It initializes the date and the time to 2018-03-11 00:52:10.

It shows current date and time in a loop.

## Wiring

Connect `CE`, `I/O` and `SCLK` pins to the following GPIO with appropriate pull-up
resistors.

| Name | Description | Defaults |
|------|-------------|----------|
| `CONFIG_EXAMPLE_CE_GPIO` | GPIO number for `CE` | "5" for `esp32c3`, "16" for `esp32`, `esp32s2`, and `esp32s3` |
| `CONFIG_EXAMPLE_IO_GPIO` | GPIO number for `I/O` | "4" for `esp32c3`, "17" for `esp32`, `esp32s2`, and `esp32s3` |
| `CONFIG_EXAMPLE_SCLK_GPIO` | GPIO number for `SCLK` | "18" for `esp32`, `esp32s2`, and `esp32s3`, "6" for `esp32c2`, `esp32c3`, `esp32c5`, `esp32c6`, `esp32c61`, `esp32h2`, and `esp32p4` |
