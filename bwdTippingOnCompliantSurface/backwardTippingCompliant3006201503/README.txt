BRIEF: Data collection with external IMU attached to right foot ankle (outer side) and 2-layer mat under the skin.

- Skin under the feet. Both skins properly working.
- Mat unfolded under the feet.
- Torso joint 2 moving from 20 to -18 from yarpmotorgui in 2.0 seconds.
- Data collected in ./dumper/icub
  - inertial: IMU readings.
  - left_foot/analog:o  Left foot FT analog sensor
  - right_foot/analog:o Right foot FT analog sensor
  - right_leg: right foot state (joint config)
  - left_leg: left foot state (joint config)
  - skin/left_foot: Left foot skin
  - skin/right_foot: Right foot skin
  - torso: Torso joint configuration
- Directory 'sequence' contains the whole body joint sequence to be played back with the yarpmotorgui
