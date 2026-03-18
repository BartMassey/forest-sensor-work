# Forest Sensor Spec and Design Ideas
Gatlin Newhouse, Tim Pupkiewicz, Bart Massey 2026-03-18

* Constraints
  * Final deployment 10-15 units (?) — cost
  * Site (?), Mackenzie River Valley — reliability
  * Topology (linear ?)
  * Weather and insolation (?) — power, reliability
  * Sensors (?) — bandwidth, reliability
  * Unattended deployment time target (one year?) — reliability
  * No moving parts (?) — reliability

* Needs
  * Physical package design
  * Sensor suite specification
  * Board design
  * Software specification and design
  * Collection node design
  * Power budget

* Tentative design sketches
  * Physical package design
    * Strap to a tree about 8' up with extension ladder (?) — tamper resistant
    * Flexible patch antenna (?)
    * Solar panel (mounting for weather, effect on insolation?)
    * Enclosure for board and sensors (?, CO2 airflow vs debris?)
  * Sensor suite specification
    * CO2 (the pain)
    * Temperature
    * Humidity
    * Soil moisture
    * Light (for free)
    * Lightning
    * Other air sensors?
    * Rain gauge?
    * Tree motion?
    * Forest motion?
  * Board design
    * 3 LDR NiMH D batteries
    * COTS 50W solar
    * Soft buck converter
    * STM32L4 or WLE5
    * LDR for digital
    * Sensors (onboard or modular)
    * Lora at 70cm
    * Antenna (flexible patch?)
  * Software design
    * Charger operation
    * Lora meshing
    * Sensors and measurement
    * OTA update (?)
    * Logging and reporting
    * Power and sleep management
  * Collection node — TBD

