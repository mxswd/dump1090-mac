# dump1090-mac

A macOS dump1090 BEAST server.

Based on https://github.com/MalcolmRobb/dump1090 but customized to work better on macOS.

## Usage

Run `dump1090-mac` with no arguments and you will be tracking ADS-B right away.

With no arguments `dump1090-mac` runs launch a BEAST format server on port 30005.

No dependencies to install, no drivers. Just plug in any rtl-sdr compatible device and you are good to go.

## License

This software statically links libusb, rtl-sdr and is heavily based off dump1090.
Licenses are included inside the dump1090-mac/Licenses/ directory.
It is up to you and your lawyers to determine what they mean.

libusb version 1.0.22_0 built from commit 270bef4002e3a34e234bda12915c1da2b1e9af88 is included, the source code to this may be downloaded from https://github.com/libusb/libusb. rtl-sdr was built from commit f68bb2fa772ad94f58c59babd78353667570630b which may be downloaded from https://github.com/osmocom/rtl-sdr.
