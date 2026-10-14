# Five-Input 7-Segment Display Simulation

An interactive logic-circuit simulation of a seven-segment display controlled by five binary inputs. It evaluates minimized AND–OR Boolean expressions for the segments, so you can see both the displayed character and which product terms activate each output.

## Run the simulation

Download the RAW file of [`seven-segment-simulator-ZAPE.html`](TP%20midterms/seven-segment-simulator-ZAPE.html) in a modern web browser. The simulation is a standalone HTML file; an internet connection is only needed to load its optional web fonts.

## How to use it

- Toggle inputs **a–e** to select a binary input combination. **a** is the most significant bit and **e** is the least significant bit.
- Use **Previous row** and **Next row** to step through the 32 input combinations.
- Select a row in the truth-table grid to jump directly to that combination.
- Press **Spell the name** to play the first 16 rows in sequence; adjust the speed slider to change the interval.
- Review each segment's Boolean product terms and output to see how the circuit produces the display.
- Use the built-in self-test to check that the circuit outputs match the truth table for all 32 rows and seven segments.
- Toggle the theme for light or dark display.

## Project files

- [`TP midterms/seven-segment-simulator-ZAPE.html`](TP%20midterms/seven-segment-simulator-ZAPE.html) — interactive simulation, circuit logic, and truth-table interface.
- [`TP midterms/documentation_EduardoJoseZape.pdf`](TP%20midterms/documentation_EduardoJoseZape.pdf) — project documentation.
- [`TP midterms/7 Segment Display.png`](TP%20midterms/7%20Segment%20Display.png) — seven-segment display image.
