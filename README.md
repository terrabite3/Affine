# Affine

Affine is a 4HP utility module for amplifying, attenuating, inverting, and offsetting a CV signal. Think of it like `f(x) = ±a*x + b`, where `0 < a < 2` and `-12 < b < 12`. The scale knob controls the level of the input from 0 to 2x. The invert switch inverts the input. The offset knob adds an offset from -12V to +12V. That's about it.

The cool part is the LED display that shows the output level. As the voltage rises above 0, the LEDs in the top half gradually turn on. Same for the bottom half. It isn't calibrated or anything, but it can give you an idea of what is being output.

## BOM

| Qty | Designator | Part | Notes |
| --- | --- | ---- | ----- |
|   1 | S1 | SPDT full size toggle (1/2" bushing) | I use a short lever, but long would work too.
|   1 | U2 | TL074 |
|   1 | U1 | TL072 |
|   1 |  | 8-pin DIP socket | optional
|   1 |  | 14-pin DIP socket | optional
|   1 | R25 | 22R resistor 1/4W |
|   1 | R21 | 1k resistor 1/4W |
|  12 | R9, R10, R11, R12, R13, R14, R15, R16, R17, R18, R19, R20 | 3k3 resistor 1/4W |
|   2 | R23, R24, R28 | 10k resistor 1/4W |
|   1 | R3 | 51k resistor 1/4W | 47k is also fine -- sets gain
|   5 | R5, R6, R8, R26, R27 | 100k resistor 1/4W |
|   3 | R2, R7, R22 | 1M resistor 1/4W |
|   2 | R1, R4 | B100k alpha potentiometer |
|   4 | C1, C2, C5, C6 | 100n capacitor | 0.1" pitch
|   2 | C3, C4 | 10uF electrolytic capacitor |
|  10 | D1, D2, D3, D4, D5, D6, D7, D8, D9, D10 | 1N4148 diode | or similar
|  12 | LED1, LED2, LED3, LED4, LED5, LED6, LED7, LED8, LED9, LED10, LED11, LED12 | Blue 2x5mm rectangular LED |
|   1 | J3 | 9-pin male breakaway header |
|   1 | H1 | 9-pin female header | 10-pin works if you remove a pin
|   2 | J1, J2 | Thonkiconn jacks |
|   1 | J4 | 10-pin shrouded header | Use nonpolarized header at your own risk
|   2 |  | 7/16" 4-40 female standoffs | McMaster part [91780A431](https://www.mcmaster.com/91780A431/)
|   4 |  | 1/4" 4-40 screws | McMaster part [92949A106](https://www.mcmaster.com/92949A106/)
|   2 |  | Knobs | McMaster part [6332K42](https://www.mcmaster.com/6332K42/)

## License

* You are free to build this design, modify it, and use parts of it in other designs.
* Most PCB fabs have a minimum order of 5 units. You may sell excess PCBs as bare PCBs, kits, or fully assembled modules. Just don't order extras with the intent of selling them.
* If you make substantial changes to the design, then you may treat the design as your own. For example, adding features, removing features, or changing the form factor. Changing the font on the panel and other superficial changes would not count.
* I urge you to release any derivative works under similar terms, but you don't have to.
