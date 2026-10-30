# Abdurakhmon Kuchkorov

Final-year Electrical Engineering BSc student at the University of Debrecen, Hungary,
specialising in Industrial Process Control. I'm heading for industrial automation and
control: PLCs, SCADA, instrumentation and energy systems.

## Now: my BSc thesis

**[tcs](https://github.com/justkuchkorov/tcs)** — traction control for an electric car.
A Python model of the car (with the values of a VW ID.3) and a PI controller in Structured
Text on a CODESYS SoftPLC, linked over Modbus TCP. I wrote the car model and the controller
and tuned the controller myself. When the road suddenly turns from dry to ice, the controller
brings the wheel slip back under control in 1.38 s; without it, the wheel spins to the end.

## Lab work

**[onewire-long-cable](https://github.com/justkuchkorov/onewire-long-cable)**: how large can a
1-Wire pull-up resistor be on a 5 m cable? A DS18B20 sensor read by an ESP32, with the data line
measured on an oscilloscope. Every reading worked up to 13.99 kΩ, and every one failed at
14.94 kΩ. An RC model predicted the rise times well, but its failure point was too low by about
1.8×. The report says what I think the reason is and what I did not test.

## Earlier projects

- [HIL-Drive-By-Wire-Sim](https://github.com/justkuchkorov/HIL-Drive-By-Wire-Sim) — drive-by-wire simulation, Python + CODESYS
- [active-suspension-hil](https://github.com/justkuchkorov/active-suspension-hil) — active suspension simulation
- [transformer_digital_twin](https://github.com/justkuchkorov/transformer_digital_twin) — transformer thermal model
- [bms](https://github.com/justkuchkorov/bms) — battery management system
- [sensor-timestamp-sync](https://github.com/justkuchkorov/sensor-timestamp-sync) — aligning sensor streams that arrive at different rates

## Tools

`Python` (serial, CSV logging, matplotlib) · `CODESYS / Structured Text` · `Modbus TCP` · `ESP32 / Arduino` · `oscilloscope` · `Git`

## Languages

Uzbek, English, Russian, Kyrgyz. Learning German.

## Contact

- Telegram: [@justkuchkorov](https://t.me/justkuchkorov)
- LinkedIn: [justkuchkorov](https://www.linkedin.com/in/justkuchkorov)
- Debrecen, Hungary
