Blynclight
==========

Open-source control software for the [Embrava
Blynclight Standard](https://www.embrava.com/products/blynclight-standard) IM
status indicator.

Device identified by :

    USB VID:0x2C0D 
        PID:0x000C

Getting Started
---------------
Install dependencies:
    
    $ sudo apt-get install libusb-dev

Clone the repo:

    $ git clone https://github.com/mborgerson/blynclight.git
    $ cd blynclight

Create a virtual environment:

    $ mkdir env
    $ virtualenv -p python3 env
    $ source env/bin/activate

Install requirements:

    $ pip install -r requirements.txt

Run:

    $ python src/blynclight.py cycle

Commands
--------
* `cycle`: Cycle through red, blue, green colors
* `color`: Set a specific color
* `pulse`: Pulse a specific color

Run with `--help` for more details.


USB Protocol 
------------
More details on USB protocol command in [USB_COMMANDS.txt](USB_COMMANDS.txt)
