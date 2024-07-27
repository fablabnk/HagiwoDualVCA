# ToDo

- Add branding/info
- Double check schematic one more time
- DONE: Drill out holes under jacks and don't route traces through them
- power stripe check
- pass DRC fully
- Double check VCA chip pinout is correct
- Does it matter than the sleeve in pin 2 not 3?
- Chose to simplify decoupling cap choices to one set of 1uF caps - if I don't have specified caps then go with verified caps below

- 100pF = 101 disc cap - have it
- 1uF = 105 disc cap - have it
- 470pF = 471 disc cap - have it

# Key points

- Both designs are 8HP
- V2164 can be replaced with SSI2164, SSM2164, or AS2164. (I think, unverified)
- Needs calibration

# Decoupling caps

using decoupling caps specified in this verified build: https://github.com/Testbild-synth/HAGIWO_055_dual_vca
Hagiwo uses 47uF and 1uF decoupling caps plus extra 1uF on TL074 rails
Verified build uses 10uF and 100n
