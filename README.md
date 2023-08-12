# xwax OSC Timecode Edition

This is a customized version of the open-source digital DJ software, xwax, enhanced to transmit timecode information via Open Sound Control (OSC).

## Features

- Retains all features of xwax with the added capability to send timecode information via OSC.
- Enables integration with other software and hardware during DJ performances or live sessions.

## Prerequisites

- Basic system requirements for [xwax](http://xwax.org/)
- Tools or software that support OSC

## Compatibility

This customization has been tested and confirmed to work with xwax version 1.6 on Ubuntu 18.04. Other versions or operating systems might work but are not guaranteed.

## Installation

1. Clone the source code:
   ```bash
   git clone https://github.com/mattun/xwax-OSC-Timecode-Edition

2. Follow the installation instructions to build and install:
   ```bash
   cd xwax-osc-timecode
   ./configure && make && sudo make install  # Replace with your specific installation steps if different

## Usage

1. Start xwax as you normally would.
2. Enable the OSC transmission feature and set the target IP address and port number.
3. The timecode information will be sent as OSC messages.

## License

This project is licensed under the GNU General Public License version 2. Please see the `LICENSE` file for more details.

## Acknowledgments

This project builds upon the codebase of xwax, and we're grateful to its developers.
