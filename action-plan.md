# Forest Sensor Action Plan
Gatlin Newhouse, Tim Pupkiewicz, Bart Massey 2026-03-18

0a. ~~Find actual funded proposal and review~~ No funding on this specific
project, probably funded through a more generalized grant via Josh (Gatlin)
0b. Purchase initial HW (Gatlin, Tim)
   0.1. Solar panel (2×?)
   0.2. STM 32L4 and 32WLE5 eval boards (2×?)
   0.3. NiMH LSD D batteries (9×)
   0.4. Buck converter components for breadboarding and/or COTS
        converter (ASAP)
   0.5. I2C Lora radio card for L4
   0.6. Flexible patch antennas for 70cm
1. Select desired sensors (Josh, Gatlin)
2. Find target deployment (Josh)
3. Gather site and weather information (Tim)
4. Talk to site folks and other experts for advice
   4.1. Physical packaging requirements?
   4.2. Solar panel requirements?
   4.3. CO2 importance and drift?
5. Select Lora story
   5.1. Find out what Lora hardware will work at 70cm
   5.2. Find out whether patch antenna will work
   5.3. Pick a Lora Mesh stack
6. Architect Software
   6.1. Language: C, C++ or Rust
   6.2. Overall arch: RTOS vs Rust RTIC vs Rust Embedded (Embassy?)
   6.3. Identify Lora stack and get it demoed locally
   6.4. Breadboard buck converter and solar panel: demo on
        some micro board
   6.5. Demo MPPT with solar panel
