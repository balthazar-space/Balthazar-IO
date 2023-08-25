# Balthazar
open-hardware laptop computer modules
These are electronic schematic modules as presented at https://balthazar.space/wiki/Balthazar with the main aim for team access

KiCad 5.1.5 files are uploaded here as well as the drawings and pictures.

# BalthazarIO

BalthazarIO module is a simple USB2.0 four-port hub for the internal devices: keyboard and touchpad, webcam and optional audiocard. Additional simplification and pcb size reduction was done recently.

IO-board (here) means connectivity with peripheral devices. These can be seen as on-board and out-board. On-board Balthazar devices include: combined usb1.1 keyboard + trackpad, usb2.0 webcam and optional audio-card. 

Since we are targeting the mini-computer family of systems (Raspberry PI. Banana PI, Orange PI, ...) - USB is the usual solution for this. 

A simple usb 2.0 hub is enough, so a very ubiquitous usb hub chip was chosen. Main mini-computer board usually provides a much better hub for 4 downstream usb devices. At this point this is still mainly USB 2.x - slowly moving to usb3.x.

Mass storage / system disk - microSD – and especially versions of SSD (sata or pcie) – should be plugged to usb3.x directly (via usb adapter).


## Funding

This project is funded through the [NGI Zero Entrust Fund](https://nlnet.nl/entrust), a fund
established by [NLnet](https://nlnet.nl) with financial support from the European Commission's
[Next Generation Internet](https://ngi.eu) program. Learn more on the [NLnet project page](https://nlnet.nl/project/Balthazar-Casing/).

[<img src="https://nlnet.nl/logo/banner.png" alt="NLNet foundation logo" width="300" />](https://nlnet.nl)
[<img src="https://nlnet.nl/image/logos/NGI0Entrust_tag.svg" alt="NGI0 Entrust Logo" width="300" />](https://nlnet.nl/entrust)
