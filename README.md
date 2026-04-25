<img width="1135" height="702" alt="Screenshot 2026-04-12 121722" src="https://github.com/user-attachments/assets/7b7fec5e-64f9-482e-9220-cc6866fbb59c" />

# OpenLightingController
<img width="1229" height="711" alt="Screenshot 2026-04-12 121633" src="https://github.com/user-attachments/assets/e6171241-c9a3-421b-8512-987c8161afb5" />
Welcome to the OpenLightingController(OLC) project!
OLC is a custom lighting board which is designed to interface via MIDI connectivity to industry standard lighting control software. This software is used to control stage lighting such as moving heads, static LEDS + Par Cans and hazer/"Smoke" machines. These softwares are used by the majority of concerts and theatrical production, though different softwares are used depending on the application.
This board is designed to interface with QLC+, my preffered software, but it could be used with any software that supports MIDI input.

I made this project due to my interest in these technologies and their applications with timecodes to create visually immersive lightshows that contribute to the overall stage presence of a performer. I look forward to testing out this board on my school's lighting rig and potentially using it for smaller 'temporary stage' productions.

## Links and Resources:

| Name | Link |
| :--- | :--- |
| **Onshape CAD Model** | [View Design](https://cad.onshape.com/documents/8c624d398e81bdfc355cd38e/w/3366eaf354e27a5f53315e7f/e/8bca373dc61369696e409729) |
| **QLC+ Project** | [View Project](https://www.qlcplus.org/) |
## PCB Screenshots:

The keyswitch matrix used in the project.
<img width="868" height="572" alt="image" src="https://github.com/user-attachments/assets/14ff0cf9-003d-4d29-a7e8-5ca38b7310b5" />

Schematic for the faders.
<img width="905" height="329" alt="image" src="https://github.com/user-attachments/assets/834ea741-36be-4410-874a-218f609c5a74" />


The overall view of the 2 Layer PCB with routing.
<img width="1392" height="673" alt="image" src="https://github.com/user-attachments/assets/d6f0cbf9-6070-4b67-9972-42430c40773f" />

## CAD Screenshots:

The overall view of the top layer CAD.
<img width="982" height="542" alt="image" src="https://github.com/user-attachments/assets/33a828cf-6dfe-45f4-a08d-358a574b8b92" />

The side pieces used to put the top of the board on an angle to optimize the operators view of the stage.
<img width="984" height="784" alt="image" src="https://github.com/user-attachments/assets/6f69b47e-2ad6-4967-a7d9-81e28034232f" />

An assemby with a singular fader (slide pot), its custom knob and spacer.
<img width="758" height="784" alt="image" src="https://github.com/user-attachments/assets/a4941f13-9b66-4772-a38e-a3dc9ad7a369" />

## Bill of Matrials (BOM):
| Name | Purpose | Quantity | Total Cost (USD) | Distributor |
| :--- | :--- | :---: | :--- | :--- |
| [50pcs M3x6mm screws](https://www.aliexpress.com/item/32810852732.html) | Screws to put stuff together | 1 | $1.66 | Aliexpress |
| [Teensy 4.1 Microcontroller](https://core-electronics.com.au/teensy-4-1-headers.html) | The main MC for the board. | 1 | $40.38 | Core Electronics |
| PCB | PCB for the main project board. | 5 | $23.60 | JLCPCB |
| [MCRR25104X7RK0050](https://www.lcsc.com/product-detail/C2832506.html) | Multilayer ceramic capacitor | 10 | $1.00 | LCSC |
| [1N4148 (DO-35)](https://www.lcsc.com/product-detail/C18195411.html) | Switching Diode for Keyswitches | 50 | $0.60 | LCSC |
| [Mechanical Keyboard Switches (70pck)](https://www.aliexpress.com/item/1005007039675427.html) | The buttons on the board. | 1 | $10.82 | Aliexpress |
| [Linear Slide Potentiometers (60mm throw)](https://www.lcsc.com/product-detail/C17555413.html) | The main faders on the board to control intensity + speed. | 10 | $19.60 | LCSC |
