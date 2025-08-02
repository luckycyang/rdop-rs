# Remote Debuger over Probe-rs

now just polyfill

in `probe-rs` for add a probe to debug arm chip, we just impl `DebugProbe` and `RawDapAccess`, should we just impl swd protocol, jtag less, but jtag also should impl

i think tcp connect can as control esp32 io action, and websocket use as serial communication for swo, or any i can run `probe-rs` in web browser in [`Support webusb as a backend`](https://github.com/kevinmehall/nusb/pull/99), because as `SerialPort` and `WebUSB`
