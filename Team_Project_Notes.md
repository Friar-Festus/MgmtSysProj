# Team Project Notes

## Deliverables

### Concept of Operations (CONOPS)

- Loading into Operations Van
- Transport to/from support vessel
- Loading/Unloading Operations Van on/off support vessel
- Mission planning
- Mission execution
  - Load mission parameters into AUV
  - Launch AUV from support vessel
  - Perform mission, e.g. mine detection, ISR, target recovery
  - Recover AUV
  - Transfer mission data from AUV
  - Post process and/or transmit mission data
- Post-mission maintenance
  - Freshwater washdown
  - Recharge AUV

### Work Breakdown Structure (WBS)

1 Autonomous Underwater Vehicle (AUV)

    1.1. Program Management
       1.1.1. Technical Reports, Briefing Materials/Meeting Minutes - Miscellaneous
       1.1.2. Progress, Status and Management Reports
       1.1.3. Quarterly Program Management Reviews (PMR)
       1.1.4. Periodic Cost and Technical Progress Reports for Prime and Subcontracts
       1.1.5. Statement of Work (SOW), Including Labor, Material and Other Direct Costs Breakdown
       1.1.6. Integrated Master Schedule (IMS)
       1.1.7. Risk Analysis and Management Plan
       1.1.8. Periodic and Final Invoices
    1.2. Systems Engineering
       1.2.1. Systems Engineering Management Plan (SEMP)
       1.2.2. Test and Evaluation Management Plan (TEMP)
       1.2.3. Requirement Specifications
            1.2.3.1. Autonomous Underwater Vehicle (AUV) Specification
                1.2.3.1.1. Propulsion System Specification
                1.2.3.1.2. Sensor Module Specification
                1.2.3.1.3. Housing Specification
                1.2.3.1.4. Power and Distribution Specification
                1.2.3.1.5. Manipulator Module Specification
                1.2.3.1.6. Communication Module Specification
                1.2.3.1.7. Support Equipment Specification
                     1.2.3.1.7.1. Operations Van Specification
                     1.2.3.1.7.2. Support Vessel Integration Interface Specification
                     1.2.3.1.7.3. Launch and Recovery System Specification
                1.2.3.1.8. AUV Software Specification
                1.2.3.1.9. Mission Planning Software Specification
                1.2.3.1.10. Data Analysis Software Specification
       1.2.4. Systems Engineering Technical Reviews
            1.2.4.1. System Requirements Review (SRR)
            1.2.4.2. Preliminary Design Review (PDR)
            1.2.4.3. Critical Design Review (CDR)
            1.2.4.4. Test Readiness Reviews (TRR)
                1.2.4.4.1. Acceptance Testing TRR
                1.2.4.4.2. Qualification Testing TRR
            1.2.4.5. Manufacturing Readiness Review
    1.3. Hardware Engineering
       1.3.1. Propulsion & Steering
            1.3.1.1. Motor
                1.3.1.1.1. Motor Trade Study
                1.3.1.1.2. Motor Selection
                1.3.1.1.3. Motor Integration
            1.3.1.2. Battery and Power Distribution
                1.3.1.2.1. Rechargeable Battery Trade Study
                1.3.1.2.2. Battery Selection
                1.3.1.2.3. Battery Integration
                1.3.1.2.4. Cable Harness
                1.3.1.2.5. Charging Interface
            1.3.1.3. Steering/Depth Control Subsystem
                1.3.1.3.1. Servomotor Selection
                1.3.1.3.2. Servomotor Integration
                1.3.1.3.3. Depth Control
       1.3.2. Sensor Payload (Sonar, IR, etc.)
            1.3.2.1. Sonar Sensor
                1.3.2.1.1. Sonar Sensor Trade Study
                1.3.2.1.2. Sonar Sensor Selection
                1.3.2.1.3. Sonar Sensor Integration
            1.3.2.2. Infrared (IR) Sensor
                1.3.2.2.1. IR Sensor Trade Study
                1.3.2.2.2. IR Sensor Selection
                1.3.2.2.3. IR Sensor Integration
            1.3.2.3. Optical Sensor
                1.3.2.3.1. Optical Sensor Trade Study
                1.3.2.3.2. Optical Sensor Selection
                1.3.2.3.3. Optical Sensor Integration
            1.3.2.4. Inertial Navigation Sensor
                1.3.2.4.1. Inertial Navigation Sensor Trade Study
                1.3.2.4.2. Inertial Navigation Sensor Selection
                1.3.2.4.3. Inertial Navigation Sensor Integration
            1.3.2.5. Payload Integration Package
                1.3.2.5.1. Payload Integration Design
                1.3.2.5.2. Payload Integration Package (PIP) Prototype
                1.3.2.5.3. PIP Prototype Test w/ Integrated Sensors
                1.3.2.5.4. Updated PIP Design
       1.3.3. Manipulator
            1.3.3.1. Manipulator Design
            1.3.3.2. Manipulator Integration
       1.3.4. Communication Module
            1.3.4.1. Low Frequency (LF) Radio
                1.3.4.1.1. LF Radio Trade Study
                1.3.4.1.2. LF Radio Selection
                1.3.4.1.3. LF Radio Integration
            1.3.4.2. Ultra High Frequency (UHF) Radio
                1.3.4.2.1. UHF Radio Trade Study
                1.3.4.2.2. UHF Radio Selection
                1.3.4.2.3. UHF Radio Integration
            1.3.4.3. Modulator/Demodulator Integration
            1.3.4.4. Full Communication Module Integration
       1.3.5. Controller
            1.3.5.1. Controller Trade Study
            1.3.5.2. Controller Selection
            1.3.5.3. Controller Integration 
                1.3.5.3.1. Propulsion, Steering, Depth Control Integration
                1.3.5.3.2. Navigation (INS) Integration
                1.3.5.3.3. Manipulator Control Integration
                1.3.5.3.4. Communication Integration
       1.3.6. Structural Housing
            1.3.6.1. Structural Housing Design Drawings
            1.3.6.2. Structural Housing Fabricated
            1.3.6.3. AUV Integration
       1.3.7. Operations Van
            1.3.7.1. Launch and Recovery System (Sub MAPC?)
                1.3.7.1.1. Transport Rails
                1.3.7.1.2. Winch
                1.3.7.1.3. AUV Launch/Recovery Attachment
            1.3.7.2. Storage Rack
            1.3.7.3. Maintenance Area
            1.3.7.4. Mission Planning/Operations Area
       1.3.8. Support Vessel Integration
            1.3.8.1. Installation/Removal Procedures
            1.3.8.2. Operational Procedures
    1.4. Software (SW) Engineering
       1.4.1. AUV Software
            1.4.1.1. Navigation
            1.3.1.2. Propulsion and Steering Control
            1.4.1.2. Sensor Operation and Data Collection
            1.4.1.3. Communication
            1.4.1.4. "Target" Acquisition & Positioning
            1.4.1.5. Manipulator Operation
            1.4.1.6. Manual Override
       1.4.2. Mission Planning SW
            1.4.2.1. Geographical Information System (GIS) Maps
            1.4.2.2. Mission Parameters
       1.4.3. Data Analysis SW
            1.4.3.1. Imagery Analysis
            1.4.3.3. Navigation Model Update
    1.5. Support and Training
       1.5.1. Technical Manuals - Drafts
       1.5.2. Training Manuals - Drafts
    1.6. Integration and Test
       1.6.1. Sensor Integration Testing
       1.6.2. Propulsion and Navigation Testing
       1.6.3. Manipulator Testing
       1.6.4. Integrated Manipulator Testing
       1.6.5. Communication Testing
       1.6.6. Integrated System Testing
    1.7. Operational Demonstration
       1.7.1. Demonstration Test Plan
       1.7.2. Demonstration Dry Run
       1.7.3. Dry Run Review
       1.7.4. Test Plan Update
       1.7.5. Operational Demonstration
       1.7.6. Operational Demonstration Report

### Statement of Work (SOW)

[SOW](Statement%20of%20Work,%20AUV%20Rev%20(-).docx)

- [ ] Include material compatibility analysis

### (Schedule)/Critical Path Network (This seems silly)

### Work Breakdown Structure (WBS) - Phase II Outline

1 Autonomous Underwater Vehicle (AUV)

    1.1. Program Management
       1.1.1. Technical Reports, Briefing Materials/Meeting Minutes - Miscellaneous
       1.1.2. Progress, Status and Management Reports
       1.1.3. Quarterly Program Management Reviews (PMR)
       1.1.4. Periodic Cost and Technical Progress Reports for Prime and Subcontracts
       1.1.5. Statement of Work (SOW), Including Labor, Material and Other Direct Costs Breakdown
       1.1.6. Integrated Master Schedule (IMS)
       1.1.7. Risk Analysis and Management Plan
       1.1.8. Periodic and Final Invoices
    1.2. Systems Engineering
       1.2.1. Systems Engineering Management Plan (SEMP)
       1.2.2. Test and Evaluation Management Plan (TEMP)
       1.2.3. Requirement Specifications
            1.2.3.1. Autonomous Underwater Vehicle (AUV) Specification
                1.2.3.1.1. Propulsion System Specification
                1.2.3.1.2. Sensor Module Specification
                1.2.3.1.3. Housing Specification
                1.2.3.1.4. Power and Distribution Specification
                1.2.3.1.5. Manipulator Module Specification
                1.2.3.1.6. Communication Module Specification
                1.2.3.1.7. Support Equipment Specification
                     1.2.3.1.7.1. Operations Van Specification
                     1.2.3.1.7.2. Support Vessel Integration Interface Specification
                     1.2.3.1.7.3. Launch and Recovery System Specification
       1.2.4. Systems Engineering Technical Reviews
            1.2.4.1. System Requirements Review (SRR)
            1.2.4.2. Preliminary Design Review (PDR)
            1.2.4.3. Critical Design Review (CDR)
            1.2.4.4. Test Readiness Reviews (TRR)
                1.2.4.4.1. Acceptance Testing TRR
                1.2.4.4.2. Qualification Testing TRR
            1.2.4.5. Manufacturing Readiness Review
    1.3. Hardware Engineering - Finalize Design
       1.3.1. Identify Updates Based on Prototype Demonstration
       1.3.2. Implement Design Updates
       1.3.3. Generate Production Plans, Drawings, etc.
            1.3.3.1. Propulsion & Steering
            1.3.3.2. Sensor Payload (Sonar, IR, Optical, Intertial Nav)
            1.3.3.3. Manipulator
            1.3.3.4. Communication Module
                1.3.3.4.1. Encryption Unit
                1.3.3.4.2. Full Communication Module Integration
            1.3.3.5. Controller - Integrate Sensor Front Ends
            1.3.3.6. Structural Housing
            1.3.3.7. Operations (Transport, Launch & Recovery, Support Vessel Integration)
    1.4. Software (SW) Engineering - Finalize Design
       1.4.1. AUV Software Updated Based on Prototype Demonstration
       1.4.2. Mission Planning SW Updated Based on Prototype Demonstration
       1.4.3. Data Analysis SW Updated Based on Prototype Demonstration
    1.5. Support and Training
       1.5.1. Technical Manuals
       1.5.2. Training Manuals
    1.6. Integration and Test
       1.6.1. Subsystem Integration Tests 
       1.6.2. Integrated System Testing
    1.7. Manufacturing
       1.7.1. Purchasing of Materials
       1.7.2. Facility Setup
       1.7.3. Low-Rate Initial Production
       1.7.4. Full-Rate Production
    1.8. Production Testing (Acceptance, Verification)
       1.8.1. Acceptance/Verification Test Plans
       1.8.2. Test Dry Runs
       1.8.3. Dry Run Reviews
       1.8.4. Test Plan Updates
       1.8.5. Verification Testing
       1.8.6. Verification Test Report
       1.8.7. Acceptance Testing of Each Production AUV

### Links

[Hydroid'S LBS UAV](https://www.naval-technology.com/news/newshydroids-lbs-auv-enters-full-rate-production-us-navy/?cf-view)

[MAPC Launch & Recovery](https://www.mapcorp.com/technologies-main/#launch)

[REACH Robotics Manipulators](https://reachrobotics.com/products/manipulators/reach-x/)