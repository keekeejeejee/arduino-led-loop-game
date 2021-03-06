# Arduino/node.js LED Loop Game

A little game built with an Arduino and node.js. The light bounces back and forth faster and faster--try to hit the button and stop it on the center light!

## Prerequisites

- Get [node.js](https://nodejs.org)
- Set up your Arduino with Firmata per the [instructions](https://github.com/rwaldron/johnny-five/#setup-and-assemble-arduino) at the Johnny-Five repo
- Get the [Johnny-Five](https://github.com/rwaldron/johnny-five) module so you can run JavaScript/node on your Arduino:
```bash
npm install johnny-five
```

## Bits and Pieces
- Arduino Uno (or whatever)
- A lil' breadboard
- A million wires
- Piezo buzzer/speaker
- Push button
- 2 1K Ohm resistors
- 7 LEDs, one of which is a unique color

## Circuit Diagram

(I'm super new to this, so let me know if this diagram is total nonsense)

![LED loop game circuit diagram](led_loop_bb.jpg)
