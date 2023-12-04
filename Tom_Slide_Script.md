# CONOPS

- The concept of operations for the AUV is depicted here.
- We start with the AUV in storage and transport it to the area of operations, using as much of the existing dolphin program infrastructure as possible.
- Once set up at the AO, the AUV is loaded with mission parameters such as navigation profile, geo-fencing limits, target ID, and so forth. In production units the communication module would be loaded with encryption keys if necessary for the mission.
- The AUV is then launched to perform its mission. Some mission types are listed here:
  - Intelligence, surveillance and reconnaissance (ISR),
  - Mine (or other weapon) detection, and
  - Reusable target recovery.
- Use of an AUV over dolphins has the advantages of a more stable platform for ISR and real-time data transfer during a mission using low-frequency communications. In addition more dexterous physical tasks are possible through the use of interchangeable end effectors for the manipulator arm.
- After mission completion the AUV returns to the launch point, surfaces, and is recovered along with any retrieved objects.
- Sensor data is offloaded for analysis and as inputs for improving future autonomous performance.
- The AUV is washed down with freshwater and any required maintenance is performed prior to the next mission or returning the AUV to its home base.

# Work Breakdown Structure (WBS)

- The WBS lists the major tasks to be performed during this Phase I period of performance. The Phase I WBS is provided in both graphical format as shown here and in text format with some additional detail. The textual document also contains a high-level WBS for Phase II.
- The WBS has seven main headings, which will be discussed in more detail for the Statement of Work.
  - Program Management
  - Systems Engineering
  - Hardware Engineering
  - Software Engineering
  - Support & Training 
  - Integration & Test
  - Operational Demonstration

# Statement of Work (SOW)

## Overview Slide

- The SOW follows roughly the same outline of the WBS, though Specialty Engineering such as reliability and structural engineering is broken out of Hardware Engineering and the Demonstration Test activity is folded into Integration & Test.

## Program Management Slide

- Very briefly list... Standard PM activities.

## Systems Engineering Slide

- Very briefly list... Standard SE activities

## Hardware Engineering Slide

- Trade studies will be performed for the following components to select the final configuration. 
  - List items shown
  - Long lead items will be identified as soon as possible in the preliminary development phase in order to reduce risk going into Phase II by placing purchase orders early enough to meet the LRIP schedule.
- Integration testing with the AUV controller/emulator will be conducted as soon as each subsystem/module is developed to reduce final integration risk.

## Software Engineering Slide

- Software development comprises three main computer software configuration items (CSCIs):
  - AUV software to control the following:
    - Navigation
    - Propulsion, steering and depth control
    - Sensor operation & data collection
    - Communication (telemetry, data, external control)
    - Target acquisition & positioning
    - Manipulator operation
    - Manual override
  - Mission Planning SW
    - GIS map loading
    - Geo-fencing
    - Loading of mission parameters
  - Data Analysis SW (may not be a single CSCI)
    - Imagery analysis
    - Navigation model updates
    - Target acquisition model updates
    - Sensor analysis

## Integration & Test Slide

- As noted previously, each hardware module will be tested with the AUV controller or emulator as it is being developed.
- Fully integrated testing will be performed:
  - Dry - on land
  - Wet - non-operational hydrostatic testing
  - Wet - operational
  - Demonstration dry run
  - Operational demonstration 