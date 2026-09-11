Battery-Powered Subwoofer Audio Amplifier

This project is a compact analog audio system that accepts a stereo input, combines the left and right channels, filters the signal to isolate low-frequency content, and amplifies the resulting bass signal to drive a speaker. The circuit was designed in KiCad and implemented as a four-layer PCB within a 2 × 2 inch footprint.

Technical Overview

Designed the complete analog signal chain from stereo input to speaker output, including channel summing, low-pass filtering, voltage gain, and power amplification stages.

Used an LM358 dual operational amplifier to condition the input signal and isolate the low-frequency content needed for subwoofer playback.

Integrated an LM1875 audio power amplifier to provide the output power required to drive the connected speaker.

Selected resistor and capacitor values for the summing, filtering, feedback, coupling, and power-decoupling networks based on the required behavior of each stage.

Captured and reviewed the full schematic in KiCad, checking component connections, power rails, grounding, and signal flow before beginning the PCB layout.

Converted the schematic into a four-layer PCB while meeting a 2 × 2 inch size constraint, requiring careful component floorplanning and trace routing.

Separated sensitive audio signals from higher-current output and power paths to reduce interference and preserve signal integrity within the compact layout.

Prepared the design for fabrication, assembled the board using SMD soldering techniques, and inspected component orientation and solder joints during bring-up.

Tested the completed signal path with an oscilloscope, multimeter, and function generator to verify filtering, amplification, power delivery, and speaker output.

Technologies and Components

KiCad · Analog Circuit Design · PCB Layout · LM358 · LM1875 · SMD Soldering · Oscilloscope · Function Generator · Multimeter

Signal Flow

A stereo audio source enters through the left and right input channels.

The channels are summed into a single mono signal.

The filter stage removes higher-frequency content and retains the bass frequencies.

The conditioned signal is amplified by the LM1875 output stage.

The amplified low-frequency signal drives the connected speaker.

