# Sensors

## Do it first
Before you read: cover your phone's top edge with your hand and watch the screen dim. The phone sensed the light fall and answered by dimming itself — sensing, deciding, acting, in a second. The middle step gets the glory, but the first step — turning light into an electrical signal — is this lesson's device: the sensor.

## Sub lesson 1 — What a sensor is — the circuit's senses

Without a sensor, a circuit is deaf: the op-amps and output devices of the following lessons have nothing to amplify or switch. With one, a circuit can watch a greenhouse, guard a door, or dose a headlight — the whole of automatic control starts at this translation step.

[Picture 36737]

## Sub lesson 2 — The working members — and how each speaks

The thermistor also shows the family trait of **non-linearity**: its resistance plunges steeply as it warms (NTC) — a known curve, usable precisely because it is known and repeatable, and a warning that 'sensor' does not mean 'perfectly proportional'.

## Sub lesson 3 — Judging a sensor — sensitivity, range, response

Three characteristics decide whether a sensor fits a job. **Sensitivity**: the size of the signal change per unit change of the quantity — a gauge that moves 1 mV per degree against one that moves 10 mV per degree. **Range**: the span of the quantity it can follow before saturating or breaking. **Response time and repeatability**: how fast it follows a change, and whether the same quantity always earns the same signal (drift and hysteresis are the enemies). Vietnam's lesson names these as the sensor's characteristics (đặc tính) — the vocabulary with which the sensor circuits of Bài 8–9 are then designed: sensor chosen, divider set, op-amp switched output — a complete sensing system assembled from the topic's three lessons.

## The key ideas

- A sensor converts a physical quantity into an electrical signal: thermistor (temperature), LDR (light), strain gauge (strain), piezoelectric crystal (pressure), Hall sensor (magnetic field)
- Resistive sensors are read in a potential divider; generating sensors (thermocouple, piezoelectric, photovoltaic) make their own small voltage
- Sensor signals are often non-linear — usable because the curve is known and repeatable, like the NTC thermistor's plunging resistance
- A sensor is judged by sensitivity (signal per unit change), range, response time and repeatability

## Say it to your companion
Tell your companion: A sensor is a device that turns a physical quantity — light, temperature, strain, pressure, magnetism — into an electrical signal a circuit can use: its resistance, voltage or current changes in a known way as the quantity changes, and a useful sensor is judged by its sensitivity (how much signal per unit change), its range, and how fast and repeatably it responds. If your companion can work the Do It Yourself tasks without looking back, the lesson has landed.

## Do It Yourself
1. An LDR's resistance rises from 1 kΩ in daylight to 100 kΩ in darkness. In a divider with a fixed 10 kΩ resistor, describe qualitatively how the output voltage moves as darkness falls (sensor in the lower arm).
2. A job needs to detect a 0.1 °C change. Sensor A gives 2 mV/°C, sensor B gives 0.05 mV/°C. Which is the starting choice, and what else must be checked before deciding?
3. Name the sensor and the electrical change you would use to (a) switch street lights at dusk, (b) weigh a lorry, (c) detect a door's magnet.
