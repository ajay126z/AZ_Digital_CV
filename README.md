# Ajay Zapadiya

_| Tech Lead @ KPIT | ADAS | EMS | ePT | Automotive Software Development C/C++ | Complex Device Driver | AUTOSAR | CAN-FD/Eth | Automation Tool Development | ASPICE | ISO26262 |_

_A tech savvy and love challenging work style, envision to contribute toward ePT, Autonomous Driving, Electric Vehicle Technologies, Conventional/Hybrid Power Train, Functional Safety, Cyber security, and Secure Software Development._


## Enginerring Experience Summary

7.5+ Years of Experience in Software Development with a demonstrated history of working in the Automotive industry. 

Skilled in Embedded Software Design, Architecture Design, Low Level Driver Development, Automation Techniques, and AUTOSAR Framework. 

Below description shows my brief experience in the Automotive Software Development Industry.

<< ADAS >>
  - Developed Complex Device Driver for one of the Intel based Image processing system DSP (MobileEye). 
 Worked on Camera core Software.
  - Integration testing of the ADAS Camera based features like Lane Departure Warning, Forward Collision Warning, Traffic Sign Recognition, Lane Keep Assistant, Pedestrian Detection.
  - Worked on creating a Generic Test Automation framework to simulate all the ADAS features from Signals at run time from the External GUI/Script window based tool. 

<< EMS and Power Train >>
  - Worked as a Software Developer and Technical team leader for Complex Device Driver Development for Conventional Powertrain domain.
  - Developed Device Driver for Fast Solenoid Valve controller from Bosch. 
  - Worked on Direct Fuel Injection Software and High Pressure Fuel Pump Software Design and Implementation.
  - Developed Software to output StepCAM, Replicated Cank Out, Heater Controller from proprietery ASIC.
  - Worked on the Wide Range Air Flow Sensor Software Design and Implementation of CJ138 ASIC from Bosch.
   - Created an Automation Tool to Generate C code from Excel based configuration of Generic Timer Module for RH850 (Thousands of registers were configured using this tool). 
  - Experience in performing Software Release Audit before Customer Delivery.
  - Experience in facing the ASPICE process audit.
  - Experience in working, supporting and leading team in complete V Cycle work packages.
  - Hands on experience on ADC, DFE, DMA, SPI, MSB, GTM, CANFD, LIN, Flexray.
  - Experience in AUTOSAR based software development.

Continuously learning and Interested in below technologies/process
  - Electric Power Train
  - Multi Sensor Fusion
  - Functional Safety (ISO26262)
  - Autonomous Driving Technology
  - Functional Safety
  - Cyber Security
  - Secure Software Development
  - Data Mining and Machine Learning Concepts

## Education
    - Bachelor of Engineering in Electronics and Communication from Gujarat Technological University (Jun 2014) | CGPA 8.11
    - Higher Secondary School Examination from GSHSEB Board (Mar-2010) | 81.40 %
    - Secondary School Examination from GSHSEB Board (Mar-2008) | 89.54 %


## Technical Skills and Interests
		
###	Languages	: Embedded C | C++ | Python | C# | Lua | Linker Script | Make file | CAPL Scripting | CMM Scripting 

### Automotive Communication Protocols : CAN, CANFD, LIN, UDS, SPI, UART, MSC, I2C

### Software & Tools: 
	
	Vector Tools		: Vector CANoe and CANape 
	Flashing and Debugging	: Lauterbach-Trace32 (RH850) Debugger, Green Hills Debugger, SerialLoader, Dediprog, Keil uvision 4 & 5, AVR studio 4/6.2, ARDUINO IDE
	Static Code Analysis	: Polyspace
	ALM Tools		: PTCIntegrity, TeamForge, JIRA, Unipro, Microsoft Planner
	Version Control		: SVN 
	Requirement Management	: IBM DOORs	
	Protocol Analyzer	: Cheetah (Cheetah GUI Software -SPI Simulator), Beagle (Data Center Software - SPI Analyzer TotalPhase), Termite(UART), CANoe (CAN)
				
	Hardware Tools		: neoRADI/O - Simple Low Cost CANI/O,  Oscilloscope
	Microcontrollers	: 8051, AVR Atmega Series(8,16,32,128,640,2560), ARMLPC2148, NXPMPC5643L, AurixTC297T, RH850GUH				
	
	Design Tools		: Enterprise Architect (EA), IBM Raphosody, MATLAB
	Autosar Configuration	: EB TresOS, DaVinci Configurator, KSAR
		

								

## Achievements and Recognition and Certification
 
  - Received Individual award “Delighted customer” at KPIT (Apr 2019)
  - Recognized in the KPIT Engineering Productivity Newsletter for building GTM AutocodeGen Tool (Nov-2019)
  - Received prestigious award of “Hitachi Automotive Systems Software Business Division Award Certificate of Commendation” (Sept 2019).
  - Received Individual award “THE COMRADES” twice at KPIT (Nov- 2021, Jun-2022)
  - Received Individual award “THE HIGH FLYERS” at KPIT (Aug -2021)
  - Received Team award “Practice Excellence Award” at KPIT (Oct- 2021)
  - Certified in Agile Planning: Project Initiation and Requirement Gathering by Skillsoft (Mar-2018).
  - Certified in “Test Driven Development for Embedded C/C++” by Wingman Software. (Aug-2019)
  - Certified by International Software Testing Qualifications Board (ISTQB) in Foundation level Exam (Mar-2015)
  - Certified in “MATLAB OnRamp” by Mathworks Software. (Jun-2022)
  - ‘On the SPOT Award’ for the prompt and timely delivery of the Software at TCS (Oct-2017).
  - Participated in the MIT ROBOCON, Pune - 2013 (Asia-Pacific Robot Contest (ABU Robocon) is an Asian-Oceanian college robot competition).

## Projects
    
   ### Project I - HWIO CDD Development for PCM - T&M / PES				
    
      Organization  : KPIT Technologies Ltd.			
      Role          : Tech Lead
      Duration      : Oct 2019 - Till date	
      Client        :	Hitachi Astemo Ltd, USA
      
      Description:  The scope of this project was to contribute into following for Hitachi P02 powertrain control module:
                     1.	Development of the HWIO
                     2.	Development of the Low Level Driver
  
      Different modules involved in this Project:

        - FSVCp ASIC Driver 
          FSVCp Driver is responsible for fast solenoid valve controller. It is used to switch inductive load fast with precise current control using microcode which is loaded into the ASIC at power up.
                              
        - Direct Injection Fuel Output
          Direct Injection Fuel Output is used in injecting fuel in the cylinder and monitoring the voltages in the fuel injectors. This module involves diagnostics of the Injector output driver.

        - High Pressure Fuel Pump 
          High pressure fuel pump is integral part of the Engine System. It is used to fill the fuel in fuel rail with adequate pressure for the next injection cycle.

        -	D30 ASIC Driver:
          D30 is proprietary ASIC of Hitachi Astemo. D30 driver module provides the APIs to setup the D30 devices as well as periodically communicate to exchange the control, status and diagnostic information from the Renesas high speed microsecond bus.

        -	StepCAM Outputs and Diagnostics
          StepCAM is essential component of the Engine Power train  ECU. StepCAM diagnostics was implemented for power short, ground short, load short and open fault. 

        -	NAC10p ASIC Driver
          NAC10p is responsible for the ADC Test and differential ADC data drivers. 

        -	AADCT
          AADCT driver is responsible for ADC testing of the NAC10p ASIC.

        -	ADRI
          ADRI component is responsible the differential ADC voltage calculation.

        -	Oxygen Sensor Input
          Oxygen Sensor Input driver is responsible for the Oxygen Sensor voltage measurement ADC Data from the Oxygen Sensor ADC. 

        -	CJ138/WRAF ASIC Driver
          CJ138 is critical ASIC for the after-treatment system. CJ138 driver was developed to calculate various parameters from the raw data.

        -	GTM 
          Generic Timer module is the most important part of the power train module. It involves ATOM, TOM, TIM and MCS modules. 

        -	MSB Driver
          MSB driver module acts as a high speed data transfer medium between critical ASICs responsible for the STEPCAM, RCCO and Spark Control. 


      Processes and Tools used by KPIT:
        - In depth knowledge of SDLC process defined by Hitachi Astemo and KPIT.
        - AutoCodeGen tool designed for GTM configuration.
        - Knowledge of Engine Complex Device driver application and its components. 

      Contribution: As a Technical Leader, I was responsible for the following tasks:
        - Play key role in analysis of customer requirements analysis,  architecture design specification, component design specification, Implementation, Testing which involves new feature introduction, as well as current feature support.
        - Review deliverables (ADS, CDS, Code, UTS/R, ITS/R) created by team member.
        - Design and Developement on full end to end process of Engine and Power Train device driver development.
        - Identification of functional and non-functional requirement and based on the identification creation of technical document like impact analysis document, query understanding document etc.
        - Working on Problem Requests and Change Requests. Study the System Design Documents (CTRS) and implementing the changes in the current software, involves analysis & modifications in current software and design document (ADS/CDS). 
        -	Creation of task breakup and estimation.
        -	Modifications to existing functions initiated by Problem Report/Change Request (PCEs) and maintaining product compatibility.
        -	Creation of Release Integration Test cases and perform the same on before release.
        -	Performing release audit before SW delivery to OEM.
        -	Working with System Architect and supporting OEM for field issues.
        -	Manage the day-to-day technical activities & tech project plan of the tech team.
        -	Serve as a single point of contact/responsibility for building and executing the technical implementation plan.

      Environment:	Lauterbach, RDC-linux, Windriver compiler, SVN, Team-forge.


   ### Project II - HWIO CDD Development for PCM - T&M / PES
      
      Organization  : KPIT Technologies Ltd		
      Role          : Senior Software Engineer	
      Duration      : Jun 2018 – Sept 2019		
      Client        :	Hitachi Astemo Ltd, USA

      Description: As a Senior Software Engineer, I was responsible for gathering and analyzing requirements, Low Level Design of the RH850 Peripherals like PWM Output, PWM Input, ICU Driver, and GTM,  and implementation and testing of the driver Interfaces:

      Different Modules Involved in the Project:
            - PWM Driver (Autosar compatible) for RH850
            - ICU Driver (Autosar compatible) for RH850
            - GTM Configuration 

       Processes and Tools used by KPIT:
            - In depth knowledge of SDLC process defined by KPIT and Hitachi.

       Contribution: As a Senior Software Engineer, I was responsible for the following tasks:
            - Technical discussion with client about requirement and providing implementation solution.
            - Low Level Design of the PWM and ICU modules for configurable number of channels as per AUTOSAR Software Specification
            - Implementation of the PWM and ICU modules as per AUTOSAR specification
            - Testing of the PWM and ICU module 
            - Discussing with application user for explaining use-cases and possible solution using the LLD driver.


        Environment: Lauterbach, RDC-Linux, Wind River compiler, SVN.

   ### Project III - Development of the ADAS Camera Core Software (AUTOSAR Based)

      Organization  : Tata Consultancy Services, Ltd		
      Role          : IT. Analyst
      Duration      : Oct 2017 – May 2018		
      Client        : ZF, USA
      
      Description:  Development of core software components which includes Complex Device drivers and software modules dedicated to interacting with Image Processing System On Chip (SoC EyeQ).

      Contribution:	As an I.T. Analyst, I was responsible for the following:
        - Implementation of EyeQ mode change, Camera Calibration Services, Datagram Services and IPC, Emulating ADC, etc through Software Hooks using Embedded C.
        - Performing Requirement Analysis and preparation of High level design documents.
        - Performing Requirement Review with V&V Team Lead.
        - Performing code review, unit testing and possible root-cause of the failures.
        - Fixing the Open points reported by testing team.

      Environment:  Lauterbach, Eclipse, PTC Integrity, DOORs, Source Insight, ASAP2 Editor, CANoe, CANape, TRACE32 Debugger, EB TRESOS, Cheetah (SPI Host Adapter), Beagle (SPI Analyzer), Oscilloscope, neoRADI/O - Simple Low Cost CAN I/O.

   ### Project IV - Design and Development of Generic Test Automation Framework 
     
      Organization  : Tata Consultancy Services, Ltd		
      Role          : Systems Engineer
      Duration      : Oct 2015 – Sept 2017		
      Client        : In-house Tool, TCS
      
      Description:  The software tester needs to focus on the quality test procedure instead of creating test-cases and scenario manually. Generic Test Automation Framework takes Excel sheets as input, generates test scripts and triggers execution of test scripts for MxVDev, EyeQ SPI Messages and CANoe.

      Contribution: As a Systems Engineer, I was responsible for the following:
        -	Conceptualizing System requirement for GTAF tool.
        - Creating Functional to software low level requirements for the GTAF tool. 
        - Designing the Data Structures and Algorithms for Input Data, Intermediate processed data and Output Data.
        - Implementing the modules in C#. 
        - Creating GUI and implementing functionality for automatic scripts generation and auto script execution. 
        - Validation of the Tool by executing sample use cases. 
        - Debugging and adding new APIs in the tool as per tester or client’s needs.

      Environment:  Visual Studio, ASAP2 Editor, MxVDev/CANoe, CANape, TRACE32 Debugger, Cheetah (SPI Host Adapter), Beagle (SPI Analyzer), Oscilloscope, Python, neoRADI/O - Simple, Low Cost CAN I/O.



   ### Project V - Design and Development of Image Processing Sub-system Simulation 
      
      Organization  : CMC, Ltd (Formerly known as a Subsidiary of TCS, In Oct, 2015 CMC merged with TCS)
      Role          : Trainee IT Engineer
      Duration      : Aug 2014 – Sept 2015		
      Client        : TRW, USA
      
      Description:  In order to test the ADAS features, the various videos for different feature needs to be played In front of the Camera. When some scenarios cannot be created or it’s costly to create, then the EyeQ signals are simulated in order to test all the features (LDW, TSR, PCW, FCW, AEB, ACC, etc) for the ADAS system.

      Contribution: As an Trainee I.T. Engineer, I was responsible for the following:
        - Preparing System Requirement Specification and Software Design Document for Simulation System. 
        - Implementation of Software components to send image processing signals over Inter Process Communication Channel to ECU. 
        - Preparing the software build.
        - Executing functional tests for MDT Fault Insertion Testing.

      Environment: Visual Studio, GNU Make, CANApe, MxVDev/CANoe, GHS Compiler and Debugger.
