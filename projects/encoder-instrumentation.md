# Real-time encoder instrumentation

RWU collaborative electrified cargo trailer project, August 2026.

## My contribution
Encoder selection, quadrature signal processing, period-based velocity measurement and a stepper-driven proof-of-concept test setup.

- Selected a 12-inch wheel and 1024 PPR incremental encoder, with 2048 counts/revolution using 2x decoding.
- Implemented period-based signal processing in Simulink Real-Time on Speedgoat IO397, with 80 Hz output and zero-speed detection.
- Bench-tested position, direction, velocity and zero-velocity indication using a stepper motor, encoder and coupler.

## Visual evidence index
The source presentation, individual contribution section (slides 20–27), provides the following gallery assets prepared for upload:

| Asset | Source slide |
|---|---|
| Signal-processing architecture | 22 |
| Encoder and wheel selection | 23 |
| Prototype test rig | 24 |
| Quadrature position and turn count | 25 |
| Velocity and direction | 26 |
| Zero-velocity flag | 27 |

The other team members investigated EKF state estimation and odometry-wheel suspension. Full vehicle validation was future work. Gallery image files are pending upload and publication clearance.