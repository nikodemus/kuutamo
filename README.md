# Kuutamo

Kuutamo means *"moon appearing in the sky"* in Finnish. It is a small
project to explore modifications to the Pure Data software for the
Critter & Guitari 5 Moons looper.

## Goals

- [ ] Isolate the HW interfaces so that same code can be run on the
      device and a computer, for ease of development. (Ideally with no
      modifications.)
      - [x] Isolate HW interfaces behind a single message abstraction
      - [x] Have the original HW interface code us the same abstraction:
            it just won't do anything if running on computer.
      - [ ] Provide a facsimile of the HW user interface in PD

## Non-Goals

Releasing anything. Retaining original features: if new features
require hijacking a button function, so be it.

## Possible Features

The feasibility of _any_ of these is open. This is not a roadmap, just a
list of things that would be interesting.

- [ ] A way load an alternate version of SW on boot.
- [ ] Quantized loops.
- [ ] X-faded loop tails.
- [ ] Per track panning.
- [ ] Global panning.
- [ ] Loop position indicator using the LEDs.
- [ ] External clock. (Using one channel of the stereo input.)
- [ ] Dedicated monitor output. (Using one channel of the stereo output.)
- [ ] Metronome on the monitor.
