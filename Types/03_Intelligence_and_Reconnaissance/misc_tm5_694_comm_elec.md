# misc_tm5_694_comm_elec  TM 5-694

TECHNICAL MANUAL

         COMMISSIONING OF
   ELECTRICAL SYSTEMS FOR

       COMMAND, CONTROL,
COMMUNICATIONS, COMPUTER,
INTELLIGENCE, SURVEILLANCE,
AND RECONNAISSANCE (C41SR)

                FACILITIES

APPROVED FOR PUBLIC RELEASE : DISTRIBUTION IS UNLIMITED

     HEADQUARTERS, DEPARTMENT OF THE ARMY

                                                                                        23 AUGUST 2002


---

   REPRODUCTION AUTHORIZATION/RESTRICTIONS

This manual has been prepared by or for the Government and, except to
the extent indicated below, is public property and not subject to
copyright.

Reprint or republication of this manual should include a credit
substantially as follows: "Department of the Army, TM 5-694,
Commissioning of Electrical Systems for Command, Control,
Communications, Computer, Intelligence, Surveillance, and
Reconnaissance (C4ISR) Facilities, 23 August 2002 ."

Table 2-1, Recommended minimum resistance values at 40°C (all values
in MO) and Table 2-2, Recommended minimum values ofpolarization
indexfor all machine components insulation classes reprinted with
permission from IEEE Std. 43-2000 "IEEE Recommended Practicefor
Testing Insulation Resistance ofRotating Machinery", copyright ® 2000
by IEEE. The IEEE disclaims any responsibility or liability resulting
from the placement and use in the described matter .

Table 3-1, Medium-voltage cables maximumfield acceptance test
voltages (W, dc) reprinted from NETA's Acceptance Testing
Specifications, copyright ®1999. Courtesy of the International
Electrical Testing Association. All rights reserved.


---

Technical Manual                                                             TM 5-694
No. 5-694
                                                        HEADQUARTERS
                                                DEPARTMENT OF THE ARMY

                                                     Washington, DC, 23 August 2002

           APPROVED FOR PUBLIC RELEASE; DISTRIBUTION IS UNLIMITED

COMMISSIONING OF ELECTRICAL SYSTEMS FOR COMMAND,
CONTROL, COMMUNICATIONS, COMPUTER, INTELLIGENCE,
SURVEILLANCE, AND RECONNAISSANCE (C4ISR) FACILITIES

                                                Paragraph Page

CHAPTER 1  INTRODUCTION                         1-1                1-1
CHAPTER 2  Purpose
CHAPTER 3  Scope                                1-2                1-1
           Reference
           General system testing requirements  1-3                1-1
           Component testing
           System commissioning testing         1-4                1-1
           Cost of commissioning
                                                1-5                1-2
           GENERAL SYSTEM TESTING REQUIREMENTS
           Introduction                         1-6                1-2
           General test plan
           Types oftesting methods              1-7                1-2
           Insulation testing
           Switch/circuit breaker testing       2-1                2-1
           Transformer testing
           Rotating machine testing             2-2                2-1
           Protective relays
           Ground system testing                2-3                2-8

           COMPONENT TESTING                    2-4                2-8
           Introduction to component testing
           Circuit switchers                    2-5                2-13
           Transformers
           Switchgear - medium voltage          2-6                2-14
           Switchgear - low voltage
           Transfer switch                      2-7                2-14
           AC/DC drives
           Motors                               2-8                2-16
           Generators
           Batteries                            2-9                2-17
           Battery chargers
           UPS systems                          3-1                3-1
           Cables
                                                3-2                3-1

                                                3-3                3-2

                                                3-4                3-3

                                                3-5                3-3

                                                3-6                3-4

                                                3-7                3-4

                                                3-8                3-4

                                                3-9                3-5

                                                3-10               3-7

                                                3-11               3-8

                                                3-12               3-8

                                                3-13               3-9


---

TM 5-694

CHAPTER 4   MAIN POWER SYSTEM                                                      Paragraph Page
CHAPTER     Description ofmain power system
CHAPTER 6   Operation of main power system                                         4-1  4-1
APPENDIX A  Commissioning plan for main power system                               4-2
            Installation inspections and component testing of main power system         4-2
            Energizing and test ofthe main power system
            Possible failures and corrective actions of the main power system      4-3  4-2

            STANDBY POWER SYSTEM                                                   4-4  4-2
            Description of standby power system
            Operation ofstandby power system                                       4-5  4-3
            Commissioning plan for standby power system
            Installation inspections and component testing of standby power        4-6  4-5
            system
            Energizing and test ofthe standby power system                         5-1  5-1
            Possible failures and corrective actions ofthe standby power system :  5-2
                                                                                        5-1
            UNINTERRUPTIBLE POWER SUPPLY SYSTEMS
            Description of uninterruptible power supply (UPS) system               5-3  5-2
            Operation ofuninterruptible power supply system
            Commissioning plan for the UPS system                                  5-4  5-2
            Installation inspections and component testing ofthe UPS system
            Energizing and test of the UPS system                                  5-5  5-3
            Possible failures and corrective actions
                                                                                   5-6  5-4
            REFERENCES
                                                                                   6-1  6-1

                                                                                   6-2  6-2

                                                                                   6-3  6-2

                                                                                   6-4  6-2

                                                                                   6-5  6-3

                                                                                   6-6  6-6

                                                                                        A-1

                   LIST OF TABLES

Table       Title                                                                       Page
1-1
2-1         Costs of commissioning, new construction                                    1-3

2-2         Recommended minimum insulation resistance values at 40°C (all values in     2-10

3-1         MP
4-1
4-2         Recommended minimum values ofpolarization index for all machine             2-16
5-1         components insulation classes
6-1
            Medium-voltage cables maximum field acceptance test voltages (kV, dc)       3-10
            Circuit switcher functional checklist
                                                                                        4-3

            Possible failures and corrective actions of the main power system           4-5
            Possible failures and corrective actions of the standby power system
                                                                                        5-4

            Possible failures and corrective actions of the UPS system                  6-6


---

                                                                                      TM 5-694

                                    LIST OF FIGURES

Figure       Title                                                                    Page

Figure 2-1   Sample of a commissioning plan                                           2-8
Figure 2-2
Figure 2-3   Step-voltage vs. time                                                    2-12
Figure'2-4
             Step-voltage high-potential test current                                 2-12
Figure 3-1
Figure 4-1   Power transformer diagram (Reprinted from Department of the Army TM 5- 2-15
Figure 4-2   686. Power Transformer Maintenance and Acceptance Testing 16 November
Figure 4-3   1998)
Figure 4-4
Figure 4-5   Static UPS system 150 to 750 kVA (courtesy of Liebert).                  3-9

Figure 4-6   Main power system single line diagram                                    4-7
Figure 4-7
Figure 4-8   Main power system control cable block diagram                            4-8
Figure 4-9
Figure 4-10  Main power system functional diagram - circuit switcher (typical for 2)  4-9
Figure 4-11
Figure 4-12  Main power system functional diagram - switchgear load breaker (typical for 8) 4-10
Figure 5-1   Main power system functional diagram - switchgear incoming breaker (typical 4-11
Figure 5-2   for 3)
Figure 5-3
Figure 5-4   Main power system circuit switcher wiring diagram (typical for 2)        4-12
Figure 5-5   Main power system incoming breaker wiring diagram
Figure 5-6                                                                            4-13
Figure 5-7   Sample of completed DA Form 7463-R
Figure 6-1                                                                            4-14
Figure 6-2   Sample of completed DA Form 7464-R
Figure 6-3                                                                            4-15
Figure 6-4   Sample of completed DA Form 7465-R
Figure 6-5                                                                            4-16
Figure 6-6
Figure 6-7   Sample of completed DA Form 7466-R                                       4-17
Figure 6-8
             Sample of completed DA Form 7467-R                                       4-18

             Standby power system single line diagram                                 5-6

             Standby power system block diagram                                       5-7

             Standby power system wiring diagram                                      5-8

             Engine fault tree                                                        5-9

             Sample of completed DA Form 7468-R                                       5-10

             Sample of completed DA Form 7469-R                                       5-12

             Sample of completed DA Form 7470-R                                       5-13

             Uninterruptible power supply system single line diagram                  6-9

             Uninterruptible power supply system block diagram                        6-10

             Uninterruptible power supply system wiring diagram                       6-11

             Sample of completed DA Form 7471-R                                       6-12

             Sample of completed DA Form 7472-R                                       6-13

             Sample of completed DA Form 7473-R                                       6-14

             Sample of completed DA Form 7474-R                                       6-15

             Sample of completed DA Form 7475-R                                       6-16


---

              TM 5-694

   CHAPTER I
INTRODUCTION

1-1. Purpose

The purpose of this publication is to provide guidance to engineering managers/planners for the
commissioning of electrical systems at command, control, communications, computer, intelligence,
surveillance, and reconnaissance (C4ISR) facilities. It specifically addresses different types of electrical
power systems, the preparation ofcommissioning statements ofwork (SOW), specifications, and
examples ofcommissioning tests that should be included during start-up. Electrical systems
commissioning (sometimes referred to as "acceptance testing") on new projects is critical to ascertain that
a system is installed correctly and that it will remain in service for its projected life cycle.

1-2. Scope

Guidance for commissioning of electric power systems on new projects is discussed in this manual . The
systems addressed include the main power substation, standby generator, and uninterruptible power
. supply. The following areas are addressed: general commissioning criteria, commissioning plan,
documentation requirements, verification procedures, system functional performance tests, deferred
performance tests, corrective measures, acceptance documentation, post commissioning follow up
procedures and examples of commissioning.

 1-3 References

Appendix A contains a list of references used in this manual . Other pertinent literature may be substituted
or used as supplements. Prescribed forms are also listed in appendix A.

 1-4 General system testing requirements

The purpose of electric systems commissioning is to increase the reliability of electrical power systems
after installation by identifying problems and providing a set ofbaseline values for comparison with
subsequent routine tests. A procedure should be developed to include a planned approach (road map) of
what should be done in order to verify the proper system installation. This procedure is the
commissioning plan . Specific areas addressed in a commissioning plan include the verification ofthe
installation of all equipment/components, interface connections between equipment and individual
 systems, and interconnection drawings . The development ofthis test plan specific to each system and/or
 component is key to the usefulness ofany maintenance program. The plan consists of the schedule of
when acceptance and routine tests should be performed, test forms to be used to record the outcome ofthe
tests which are retained for comparison with previous and subsequent tests, and a listing of the required
test devices. Since the results of the commissioning tests become baseline test values to compare with
 later tests and the results ofthe routine maintenance tests are compiled to identify any downward trend in
 performance, it is vital to the maintenance program to have accurate and complete records. To perform
 the testing, the plan lists all required tests in order ofperformance and gives a schedule for each test. The
 work items and schedule depend on many items including the importance and cost of the equipment,
 consequences of failure, age of equipment, past and future frequency ofservice, hours ofoperation, future
 maintenance availability, environmental conditions, and safety requirements .


---

TM 5-694

1-5 Component testing

The reliability of any system is dependent on the interconnection of the equipment and the equipment
itself. This manual's purpose is predominately for testing of electric systems themselves. It is assumed
that the detailed and comprehensive individual testing of equipment has been completed before the
commencing of commissioning of the system . However, general testing procedures for the components
ofthe systems described in this manual are addressed in chapter 3 . Commissioning requirements for the
system components are typically provided with the original proposal for the procurement of the
equipment. The requirements provided by the equipment manufacturer should be adhered to in addition
to the recommended testing herein . Although there are many of different components to any electrical
system, there are some tests that are common among the equipment. Examples of the common testing
procedures include the assembly check, alignment check, grounding verification, insulation resistance
tests and polarization index to name a few. These common tests are described in detail in chapter 2.
Sufficient time should be allocated to define the inspections required, perform the check, and document
the results. A review ofthe system drawings will show major pieces of equipment. Specific procedures
should be developed for each test referencing the equipment to be used, drawings to be followed, and step
by step procedures with readings to be recorded and forms for the results.

1-6 System commissioning testing

Electrical systems commissioning on new projects is critical to ascertain that a system is installed
properly and that it will remain in service for its projected life cycle. The commissioning of a system
encompasses the individual testing of the related components, the verification of the component
interconnection against the drawings, and the functional testing of the system as a whole. An
understanding ofthe equipment involved and the modes ofoperation for a system are essential to the
development of the system commissioning plan. A survey of the equipment of the system and listing the
equipment in order of importance and startup is the first step in developing the commissioning plan. The
schedule of the tests and inspections is dependent on many aspects ofthe equipment such as its
importance and cost, the frequency of service, hours of operation, environmental conditions, accessibility,
and safety requirements . The inspection, testing, and startup plan is then developed in conjunction with
this schedule with instructions and procedures for the test plan. Examples of systems testing are
discussed in chapters 4, 5 and 6. DA Forms 7463-R through 7475-R are checklists designed to assist in
these inspections and tests. They are found as reproducible forms at the end ofthis manual . Problems
may arise during the testing ofthe equipment and systems. In order to identify and correct these
problems, troubleshooting techniques should be developed. Checking of equipment such as fuses, lights,
and breakers for continuity, equipment calibration and settings, and investigating for faulty equipment or
connections should be the first troubleshooting steps. For all problems, the equipment and component
manuals are consulted for troubleshooting directions. Examples ofthe possible causes to common
problems are shown for each system in the chapters that follow.

1-7 Cost of commissioning

 The cost of commissioning for an electrical system is dependent upon many factors including the system
size, complexity and the level of reliability desired. New building construction, renovation of an existing
building, or the modernization also will effect the cost of commissioning. Experience has shown that the
initial commissioning cost is more than offset by increased system reliability and reduced operating costs.
The cost for commissioning a new building can range from 0.5 to 1 .5 percent of the total construction cost
as shown in the table below. For an existing building the commissioning costs can range from three to
five percent ofthe total operating costs .


---

                                                                                       TM 5-694

                     Table 1-1. Costs of commissioning, new construction

Commissioning Scope                              Cost

Entire building(HVAC, Controls, Electrical,      0.5-1 .5% of total construction cost
Mechanical) Commissioning .
HVAC and Automated Control System Commissioning  1 .5-2 .5% of mechanical system cost
Electrical Systems Commissioning                 1 .0-1 .5% ofelectrical system cost

Energy Efficiency Measures Commissioning          $0.23-0.28 per square foot

Source : Portland Energy Conservation Incorporated/Building Commissioning Guide, US Department of
Energy, 30 July 1998


---

                                      TM 5-694

                           CHAPTER 2
GENERAL SYSTEM TESTING REQUIREMENTS

2-1. Introduction

The purpose of electrical testing on systems and their components is two-fold . The first is to check the
installation ofthe equipment and perform component and systems tests to ensure that, when energized,
the system will function properly . The second is to develop a set of baseline test results for comparison in
future testing to identify equipment deterioration. Commissioning tests are usually performed by
independent contractors, the installation contractor, or the manufacturer. Each commissioning test should
be witnessed by a person not associated professionally with the person performing the test. The
individuals who perform the acceptance tests should be certified and/or licensed for the equipment under
test. The system should be initially checked for damage, deterioration, and component failures using
specific component checks, inspections, and tests defined by the equipment manufacturer. Then the
interconnection of the system components should be checked, using de-energized and energized methods,
to verify the proper interconnection and operation of the components, including on/off control, system
process interlocks, and protective relaying functions. Once the above tests are complete, the system can
be energized and operational tests and measurements should be performed. All steps and results of the
testing should be carefully documented for review and for use in the future for comparison with the
results of future tests. Many of the same component tests initially run will be performed at regular
intervals as part of a maintenance program. The new results will be compared to the initial results, where
variations may be indicative ofproblems like deterioration of insulation or dirty equipment. The steps
involved are to review the system and equipment, develop a general system and specific equipment test
plan, provide inspection and checks, perform component testing, verify and check the continuity of
wiring, check control functions, calibrate instruments and relays, energize portions ofthe circuits and
check for proper operation in a specific order, and, once complete, perform specific checks and control
tests on the complete system during initial period of operation.

2-2. General test plan

 There are management, economic, and technical requirements associated with every test plan. The
 development and use of a comprehensive test plan is like an insurance policy . While it has specific costs,
 it does not usually show any direct paybacks as the systems will usually startup without significant
 problems such as equipment failure or lost time. The cost of the tests will rise with the complexity ofthe
 test program. Many inspections and tests are redundant, but are used as checks and balances before
 system energization to ensure successful startup and operation. Many times, ifthe equipment is in the
 same operating condition as when it left the factory and the system design and installation are adequate,
 the system startup and testing will find no problems and the de-energized checks and energized testing
 may seem like a waste of time and money. There are occasions when a test will show bad insulation like
 a faulted transformer winding or a missing interlock in a control scheme that would have resulted in
 catastrophic failure ifthe system had been energized. The complexity of the system and equipment,
 experience ofthe designers/installers/operators, the possible results ofa failure, and the costs of the
 testing are all considered when determining the amount oftesting required . The component and system
 inspections and checks are the key to the success of the program. Sufficient time should be allocated to
 define the inspections required, perform the check, and document the results. A review ofthe system
 drawings will show major pieces of equipment. Specific procedures should be developed for each
 commissioning test referencing the equipment to be used, systems operation documents (SODs), systems


---

TM. 5-694

operation and maintenance manuals (SOMMs), drawings to be followed, and step by step procedures with
readings to be recorded and forms for the results. Once the equipment is identified, the manufacturer's
manuals should be used to identify the required receipt inspections, handling and installation procedures,
energized and de-energized component tests, drawing and wiring verification, minimum report
requirements for on-going maintenance and testing baseline, and requirements for repair and retesting if
certain checks and tests produce unsatisfactory results. To perform the testing, a definite plan listing all
required tests in order of performance and giving a schedule for each test should be developed. The work
items and schedule will depend on many items including the importance and cost of the equipment,
consequences offailure, age ofequipment, past and future frequency of service, hours of operation, future
maintenance availability, environmental conditions, and safety requirements . (For remote unattended
systems, additional items will be required in the initial test plan, to help assure all possible operating
sequences, malfunctions, and corrections have been verified . The plan should be revised as the inspection
and testing proceeds depending on the acceptability of the results.) Certain failures may require retesting
of component and system operation. When wiring problems are found and repaired, all affected wiring
terminations should be re-verified for their proper connections. The success of a test program and its use
to support an on-going maintenance program also greatly depends on the attention given to development
and review of the test records and reports by the testing and operations personnel and system
management . To have an effective program it is imperative that test data be complete, organized, and
readily available. Forms should be developed with the test procedures which list the required test
procedure, test sequence, test instrument, test data and, most importantly, acceptable test values for each
result . (Examples of test forms are found in each applicable chapter. These forms should only be used as
samples.) A remarks area should be included to list any pass or fail, comments, recommendations for
repair and retest, additional follow-up testing required during the next steps of the system operation, and
helpful information for future testing. Note that the data collected and recorded will be used over the
years to analyze trends for equipment deterioration or help determine causes for system malfunctions, so
 ifthe records are not complete and correct a large part ofthe usefulness of a good test program is lost .
The technical requirements for a test program can be stated as follows.

   a. Survey ofsystem equipment. An accurate and complete description of a power system and its
 equipment is required to develop a test program. This will include written system description, one-line
 diagrams, short circuit and coordination studies, three line diagrams, control logic diagrams, schematic
 logic diagrams, cable block and interconnecting diagrams, equipment physical and wiring drawings,
 equipment manuals, and auxiliary system manuals and drawings for support systems such as lighting, fire
 protection, backup power, building and building services, etc.. These documents serve to depict the
 design and operation ofthe system for use during installation, testing, startup, operation, and
 maintenance. Various standards groups such as the Institute of Electrical and Electronics Engineers
 (IEEE) and National Electrical Manufacturers Association (NEMA) have developed standards for these
 materials. Typical drawings and their definitions are as follows:

         (1) One-line (single-line) diagram. Shows, by means of single lines and graphic symbols, the flow
 ofelectrical power or the course of electrical circuit symbols, and how they are connected. In this
 diagram, physical relationships are usually disregarded.

         (2) Block diagram. Shows a group of interconnected blocks, each of which represent a device or
 subsystem .

         (3) Schematic (elementary) diagram. Shows all circuits and device elements of the equipment.
 This diagram emphasizes the device elements and their functions, and it is always drawn with all devices
 shown in deenergized mode .


---

                                                                                                                    TM 5-694

       (4) Control sequence (truth-table) diagram. Shows a description of the contact positions,
connections, that are made for each position of control action or device .

       (S) Wiring diagram (connection diagram) . Locates and identifies electrical devices, terminals, and
interconnecting wires in an assembly . This diagram may show interconnecting wiring by lines or
terminal designations .

       (6) Interconnection diagram. Shows only the external connection between controllers and
associated equipment or between various housing units of an assembly of switchgear apparatus.

       (7) Circuitlayout and routing diagram. Shows the physical layout of the facility and equipment
and how the circuit to the various equipment is run.

       (8) Short-circuit coordination study. Electrical power system data, diagrams, and drawings are
needed during maintenance and testing ofelectrical equipment. This may involve information and data
relating to protective devices and relays. Such data are usually found in a short-circuit coordination study
and usually encompass all the short-circuit values available in the power system, relays, and trip device
settings. Normally, this study is performed during the construction phase ofthe facility . It would be
much more desirable to perform this engineering study as part of the initial facility design, and then
validate it during the construction phase to assure that equipment and values specified have been met.
When accepting the facility, this study data should be used as a benchmark, and any changes that may
have been made during construction in the system should be incorporated to update the study for future
references.

   b. Listing ofcritical system equipment. The major equipment of a system is vital to its operation and
failure ofthis equipment could be a threat to personnel and system operation, i.e., potential single point
failures. From a review ofthe system documentation, especially the single line diagram, a list of critical
equipment and the order in which the items should be inspected, tested, and energized should be
developed. From this list, the plan and schedule for the test program can be developed. Normally the
 listing in order of criticality of the equipment is from the normal power source into the system with onsite
 sources failing after the main power source and distribution equipment. The listing may be difficult to
 prepare as it will vary for each system, and therefore a team from system engineering, operations, and
 maintenance may be required. This will also serve to provide the operations and maintenance personnel
 an opportunity to review the system during the early stages ofa project, which helps them in the
 performance of their work.

   c. Stepsfor the test program. A test program will commence after completion of installation and will
 usually include field inspection and installation checks, de-energized component testing, verify
 instrument and relay operation and calibration, visual check ofall wiring, continuity checking of control
 circuits, energized functional testing of control circuits, megger testing of power circuits, test of power
 circuits phasing, energizing of equipment, and service testing. Ifproblems are found during the testing;
 an analysis should be performed, and a repair and retest should be performed that is approved by the
 commissioning authority, manufacturer, engineer, and system operator . Many of these initial tests will be
 repeated periodically as part ofthe system maintenance program depending on the load conditions, duty
 cycle, environmental conditions, and the critical nature of the equipment. Because of this, the
 completeness and clarity of the test reports is important as they supply baseline data for comparison with
 the results ofthe maintenance tests.

    d. General definition oftest steps. Prior to testing, overall completion of installation should be
 verified including setting, wiring, grounding ofthe equipment, and conditioning of the overall area, i.e .,
 clean complete site to work in. This is considered a pretest. Note: all of the items below should be

                                                                                                                         2-3


---

TM. 5-694

performed in strict accordance with the drawings, systems operations documents, systems operation and
maintenance manuals (provided by contractor), and the engineer's and manufacturer's instructions for
each piece of equipment. The manufacturer typically provides the instructions in the form of diagrams
indicating how to connect the test instruments as well as charts indicating acceptable and unacceptable
values. The engineer's instructions will be found in the system specifications and drawings, and the
manufacturer's instructions are found in the equipment manuals and drawings. IEEE, NEMA, National
Fire Protection Association (NFPA), and other standards also include acceptable procedures for the
performance of the tests. As the acceptance tests and energization is performed; failures and repairs,
availability ofequipment and personnel, schedules, weather, and other items may cause the delay or non-
performance of a test. In any of these cases, the missing, failed, newly required, or postponed test should
be noted in the test documentation along with the reason for missing the test and the technical
consequences . An evaluation should be made as to whether the system can be energized without this test
noting the possible effect on safety, personnel, and equipment operation; and noting when or even ifthe
test should be performed in the future. If the test yet to be performed or needs to be performed to prove
the adequacy of a repair, the test should be scheduled with the system operations personnel as part ofan
on-going maintenance program.

        (1) Field inspection and installation checks . Include inspection of impact recorders, verification of
removal of shipping braces, inspection of installation against drawings and nameplates, inspecting of
components for damage and cleanliness, inspection ofinsulators for cracking, inspection of anchorage
and grounding, sizing check of fuses and breakers, alignment and adjustment checks, mechanical
operation and interlock checks, lubrication application, verification of insulating liquid or gas level or
pressure, and verification that local safety equipment is in place.

        (2) De-energized component testing. Include pressure and level checks, megger and insulation
resistance testing of equipment and connections including grounds, turns ratio measurements, polarity
tests, insulating liquid dielectric and moisture testing, power factor or dissipation factor tests,
 overpotential tests, contact resistance measurements, operation time travel analysis, battery and cell
 voltage measurements, charger/UPS (uninterruptible power supply)/generator current and voltage
 measurements, and equipment/systems impedance or resistance tests.

        (3) Verification ofinstrument and relay operation and calibration. Include verification of
 auxiliary device operation, calibration of instruments and relays, functional testing of individual
 instruments/gauges/alarms/relays/limit switches/etc .

         (4) Visual check ofall wiring. Include visual inspection of all wiring against the schematic and
 wiring, both internal and external, diagrams .

         (S) Continuity checking ofcontrol circuits . Include continuity and voltage testing of all control
 circuits against schematic diagrams.

         (6) Energizedfunctional testing ofcontrol circuits . Include energizing of control circuits and
 checking all remote and local close/trip operations, protective relay operations, safety and interlock
 operations, and all process and communication operations .

         (7) Megger testing ofpower circuits. Include megger testing of power, current transformer, and
 potential transformer buses and cables after connection .

         (8) Phase out testing ofpower circuits. Include primary and/or secondary injection testing for
  circuit impedance and polarity checks .

  2-4


---

                                                                                                                    TM 5-694

       (9) Energizing ofequipment. Include energizing of equipment in specific order after all above
testing is complete and evaluated.

       (10) Service testing. Include measurement of value and relationship of power, potential, and
current on sources, buses, feeders, and neutrals in the power system .

       (11) Post acceptance tests. Include on-going maintenance and operation tests, corrective action
tests, and deferred testing.

   e. Reports,forms, and records. Accurate and complete reports, forms, and records should be
developed and kept updated after the testing for the equipment and the system for initial evaluation of the
results before energization and on-going evaluation by operations and maintenance. Analysis ofthe data
and results should provide a decision to startup and a guide for future maintenance requirements and its
cost . Figures should be kept for the time, cost, and equipment used for each test for input to the
development of the maintenance program. Care should be taken to ensure that extraneous information
does not become part of the record, because record keeping might hamper future use. Test reports giving
test description and basic procedure, components, drawing and other document references, test circuit
diagrams, test equipment model and age and calibration date, special tools required, test forms with
results filled in, time to run the test, acceptance criteria, failure or unusual event information,
recommended repair, and when the test should be performed again for equipment maintenance should be
 developed for the tests. Summary logs developed from the information can be used for developing and
 scheduling an on-going maintenance program. Forms should be used to document the results oftesting
 procedures . They should be detailed and direct, but simple and durable enough to be used in the field.
 The forms should be used as input to the development of the test reports. A well designed form will
 contain checklist information for inspections, test procedures, safety and special precautions, required
 equipment and tools, reference drawings and manuals, acceptance criteria, estimated time to perform the
 test, and remarks/event recording area . Sample forms for basic equipment and tests are attached .

  f. Special precautions and safety . Many tests on electrical equipment involve the use ofhigh voltages

 and currents that are dangerous, both from the standpoint of being life hazards to personnel and because
 they are capable of damaging or destroying the equipment under test. Adequate safety rules should be
 instituted and practiced to prevent injury to personnel, both personnel who are performing the tests and
 others who might be exposed to the hazard . Also, the test procedures used should be designed to ensure
 that no intentional damage to equipment will result from the testing process. It should be recognized, as
 the name implies, that over-potential or high-potential testing is intended to stress the insulation structure
 above that of normal system voltage. The purpose ofthe test is to establish the integrity of the insulation
 to withstand voltage transients associated with switching and lightning surges and hence reduce the
 probability of in-service equipment failures. Direct voltage over-potential testing is generally considered
 a controlled, nondestructive test in that an experienced operator, utilizing a suitable test set, can often
 detect marginal insulation from the behavior ofmeasured current. It is therefore possible, in many cases
 to detect questionable insulation and plan for replacement without actually breaking it down under test .
 Unfortunately, some insulations might break down with no warning. Plans for coping with this
 possibility should be included in the test schedule. Low-voltage insulation testing can generally be done
 at the beginning ofthe planned maintenance shutdown . In the event ofan insulation failure under test,
 maximum time would be available for repair prior to the scheduled system startup. Equipment found in
 wet or dirty condition should be cleaned and dried before high-potential testing is done or a breakdown
 can damage the equipment. Low-voltage circuit breakers, which require very high interrupting ratings,
 are available with integral current-limiting fuses. Although the fuse size is selected to override without
 damage to the time-current operating characteristics of the series trip device, it is desirable to bypass or
 remove the fuse prior to applying simulated overload and fault current. Ifa testing program is to provide
  meaningful information relative to the condition ofthe equipment under test, then the person evaluating

                                                                                                                         2-5


---

TM 5-694

the test data must be ensured that the test was conducted in a proper manner and that all ofthe conditions
that could affect the evaluation of the tests were considered and any pertinent factors reported. The test
operator, therefore, must be thoroughly familiar with the test equipment used in the type of test to be
performed and also sufficiently experienced to be able to detect any equipment abnormalities or
questionable data during the performance ofthe tests .

  g. Test equipment. It is important that in any test program the proper equipment is used. The
equipment should be calibrated, in good condition, and used by qualified operators. Any test equipment
used for calibration shall have twice the accuracy of the equipment to be tested. Care should be taken to
use a quality or regulated power source for the equipment as voltage, frequency, and waveform variation
can produce invalid results . All equipment should be operated in accordance with its instruction manual .

  h. Sample Commissioning (Cx) Plan: The primary intent ofthis technical manual is to propose
different procedures that should be considered when commissioning a new electrical system and
/or component. The figures, forms, and tests in this manual are only examples ofthe concepts
that should be implemented when developing a commissioning plan. The following paragraphs
discuss an example of commissioning program planning stages that can be used to commission a
new system as shown in figure 2.1 (Commissioning Plan Example) . The time period in which a
commissioning process begins determines what steps in the planning stages are considered :

      (1) Initial commissioning (kick-off) meeting. The first commissioning meeting may start as
early as before a contract is awarded or as late as after the system has been installed (before it is
turned over to the customer). The participants in the meeting should include customer,
government contractor personnel, participating engineers, commissioning personnel (may be an
independent commissioning contractor or government engineer), general contractor, and
electrical and mechanical sub-contractors. Topics of meeting should include areas of
responsibility, expectations, overall presentation of system, methodology, potential problem
areas, etc. The participants should be all considered "part of a team".

       (2) Review initial statement ofwork (SOW). All participants should review the SOW that
describes the requirements of the commissioning process. The customer (or designated authority)
should have the ultimate control where decisions are required.

       (3) Review drawing submittals. After the systems are installed, drawings should be
submitted for review and comment. Sometimes the review may be before systems are installed .
Care must be taken to verify that the drawings submitted reflect the actual installed system.

       (4) Approval meeting. After the SOW and drawing submittals have been submitted,
reviewed, comments made, and comments incorporated, approval of documents should be
provided.

        (S) Systems operation document (SOD)/systems operation and maintenance manual
 (SOMM document. Prime contractor should provide a SOD or SOMM. These documents are
required in order to develop specific commissioning tests.

        (6) Submitfunctional performance tests (Ms). System/component tests or FPTs should
 be developed from submitted drawings, SODs and SOMMs. The tests should include large

 2-6


---

                                                                                                                     TM 5-694

component testing (i.e. transformers, cable, generators, UPS), and how components operate as
part of the total system . The test should be developed by the commissioning authority. The
commissioning authority should not be the installation contractor (or sub-contractor).

      (7) Quality assurance . As the equipment/components/systems are installed quality
assurance procedures should be administered to verify components are installed in-accordance
with minimum manufacturers recommendations, safety codes, and acceptable installation
practices. Quality assurance discrepancies should be identified and added to a "commissioning
action list" that must be rectified as past of the commissioning program. These items would
usually be discussed during commissioning meetings. Discrepancies are usually identified
initially by visual inspection .

      (8) Review FPTs. The tests should be reviewed by the customer, electrical contractors,
quality assurance personnel, maintenance personnel, etc (the commissioning team). Areas of
concern should be 1) are all functions of the system being tested, 2) are all major components
included, 3) do the tests reflect the system operating documents, 4) do the tests make sense, etc.

       (9) Make changes to FPTs. This is where corrections, questions answered, and additions
made will be implemented. This will be done by the commissioning authority.

       (10) FPT approval. After the changes are made to the FPTs they will again be submitted to
 the commissioning team. When it is acceptable the customer or his/her designated approval
 authority should approve the FPTs . It should be noted that even though the FPT is approved,
 problems that arise during the test (or areas not covered) should be addressed.

        (11) Systems operate . The FPTs can be implemented as various systems become operative
 (i.e. test the generator system) or when the entire system is installed. However the final "pull the
 plug" test will be performed after all systems are completely installed. If the FPTs are
 implemented by the electrical contractor (or sub-contractor) then a witness should initial each
 step of the test . The witness should not be employed directly or indirectly by the electrical
 contractor .

        (12) Customer receives system. After all tests are completed (including the "pull the plug"
 test) the system should be turned over to the customer.


---

TM. 5-694

                       Commissioning (Cx) Planning Stages

           Initial Cx  Review           Approval
           Meeting     Initial           Meeting
                       SOW

           Development OF Functional Performance Tests (FPT's)

                                Review  Make                FPT's
                                FPT's   Changes            Approved'"-
                                        to FPT's

                                Testing Implementation

                                                                        Customer
                                                                        Receives
                                                                        System

                                    Figure 2-1. Sample ofa commissioningplan

2-3. Types of testing methods

Types oftesting methods include the four categories of tests as well as the tests themselves.

  a. Categories oftests. There are four categories oftests for electrical equipment; factory, acceptance,
routine maintenance, and special maintenance. Factory tests are performed at the factory to prove the
equipment was manufactured properly and meets specific design parameters . Commissioning tests, the
main subject of this document, are also prooftests performed on new equipment and systems usually after
installation and before energization. They are run to determine whether the equipment is in compliance
with specifications, to establish benchmarks for future tests, to determine the equipment was installed
correctly and without damage, and to verify whether the equipment meets its intended design operation
and limits . Routine and special maintenance tests are run after the equipment has been in service for a
certain amount oftime to determine the degree of deterioration of certain equipment physical parameters
as operating time increases. Routine tests are performed on a periodic basis and special tests are
performed on defective equipment to help determine the cause of a failure and/or the extent of the
damage. The same type oftests and measurements are performed for all ofthe categories using different
voltage values. The acceptance tests are usually run at 80% and the maintenance tests are usually run at
60% of the factory test voltage values to help indicate deterioration without being destructive.

   b. Types oftesting methods. The testing of electrical power system equipment involves checking the
 insulation adequacy, electrical properties, protection and control, operation, and other items as they relate
to the overall system . Some of these checks are accomplished using de-energized component tests,
 instrumentation and relay operation and calibration tests, energized functional testing of control circuits,
 megger testing ofpower circuits, phase out testing of power circuits, and service testing.

 2-4. Insulation testing

 Insulation can either be solid, liquid, or gaseous dielectric materials that prevent the flow of electricity
 between points ofdifferent potential. Insulation testing is performed to determine the integrity of the

 2- 8


---

                                                                                                                                TM 5-694

insulation. This usually consists of applying a high potential voltage to the item and measuring the
leakage current that may flow to ground. Excessive leakage current is an indication of dielectric
breakdown and/or impending failure. Insulation may weaken over time at a rate tightly related to the
operating time and temperature of operation. Therefore, these tests are run periodically to track the
insulation deterioration. Insulation testing, the most common electrical testing performed, can be
performed by applying a direct current (dc) or alternating current (ac) voltage. The type and value ofthe
voltage determines whether the test is considered non-destructive or destructive. The higher the voltage,
the more destructive the test. Usually destructive tests are only run one time in the factory to verify the
initialstrength ofthe insulation, and non-destructive tests are run as acceptance and maintenance tests to
measure deterioration from the original value. Both the do and ac tests are "go no-go" tests. In addition,
the do test can indicate the amount of deterioration and forecast the remaining time for safe operation by
comparing the leakage current and test voltage to values from previous tests.

   a. Advantage ofdirect-current testing . Direct-current test is preferred on equipment whose charging
capacitance is very high, such as cables . Direct-current voltage stress is considered much less damaging
to insulation than ac voltages . The time of voltage application is not as critical with do voltage as with ac
voltage. The test can be stopped before equipment failure. Measurements can be taken concurrently . It
is not necessary to make a separate insulation resistance test prior to making a do over potential test.

   b. Disadvantage ofdirect-current testing. The stress distribution for transformers, motors, and
generator winding is different for do voltage than for ac voltage. The residual charge after a do voltage
test must be carefully discharged . The time required to conduct a do high-potential test is longer than for
an ac high-potential test.

   c. Direct-current (dc) testing. When a do potential is applied across an insulation, the resultant
 current flow is composed of several components as follows:

        (1) Capacitance-charging current. Capacitance-charging current is the current resulting from
 charge absorbed by the capacitor formed by the capacitance of the bushing. This current is a function of
 time which also depends on applied do voltage, insulation resistance and the time constant of the circuit.

        (2) Dielectric-absorption current. Dielectric-absorption current is the current that is absorbed and trapped
 in the dielectric during the charging ofthe piece ofequipment and released after the equipment is discharged.
 This current can be calculated from test voltage, capacitance, and time . In air-cooled and hydrogen-cooled ac
 rotating machines, dielectric absorption varies with temperature.

         (3) Surface leakage current. The passage of current over the surface ofan insulation rather than
 through its volume is surface leakage current. In measuring insulation resistance of armature and field
 windings in rotating machines (rated 1 hp, 750 W or greater), a high surface leakage current is usually
 caused by moisture or another type of partly conductive contamination present in the rotating machine.

         (4) Partial discharge (corona current) . This is a type of localized discharge resulting from
 transient gaseous ionization in an insulation system when the voltage stress exceeds a critical value.
 Partial discharge is not desirable and should be eliminated . It is caused by overstressing of air at sharp
 corners of the conductor due to high test voltage. In shielded power cable systems (rated > 5 kV),
 humidity or wind can increase the corona current.

         (5) Volumetric leakage current. The current that flows through the volume insulation itself is volumetric
 leakage current. It is the current that is of primary interest in the evaluation of the condition of the insulation . In
 shielded powercable systems (rated > 5 kV), humidity, condensation, and precipitation on the surface of a
 termination can increase surface leakage current and volumetric leakage current. Surface leakage current and

                                                                                                                         2- 9


---

TM 5-694

volumetric current added together is the quotient of the applied do voltage and insulation resistance . In large ac
rotating machines rated 10,000 kVA or greater and rated 6000 V or higher, moisture, on the end windings,
increases surface leakage current and volumetric leakage current especially when dirt is also on the winding.
Since the insulation may weaken over time, age may cause an increase in the various currents during testing.

  d. Insulation-resistance (megger) testing. For equipment containing electronic components, megger
testing must not be performed. However, this equipment should be tested according to manufacturer
specifications . In an insulation-resistance test, an applied voltage, from 600 to 5000 volts, supplied from
a source of constant potential, is applied across the insulation. The usual potential source is a
megohmeter, also known as a megger, either hand or power operated that indicates the insulation
resistance directly on a scale calibrated in megohms. A megohmeter that is a hand cranked, a rectifier-
type, or battery-operated instrument is suitable for testing equipment rated up to 600 volts. For
equipment rated over 600 volts, use ofa 1000-volt or 2500-volt motor-driven or rectifier-type
megohmeter is recommended for optimum test results. The quality of the insulation is evaluated based on
the level ofthe insulation resistance . The insulation resistance of many types of insulation is variable
with temperature, so the data obtained should be corrected to the standard temperature for the class of
equipment under test. Published charts similar to table 2-1 are available for this purpose. The megohm
value of insulation resistance obtained will be inversely proportional to the volume of insulation being
tested . For example, a cable 1000-ft (304.8 m) long would be expected to have one-tenth the insulation
resistance ofa cable 100-ft (30.48 m) long if all other conditions were identical. The insulation-resistance
test is relatively easy to perform and is a useful test used on all types and classes of electrical equipment.
Its main value lies in the charting of data from periodic tests, corrected for temperature, over the life of
the equipment so that deteriorative trends might be detected .

        Table 2-1. Recommended minimum insulation resistance values at 40°C (all values in Ma .

Minimum Insulation Resistance after 1 minute  Test specimen

(MCI )    kV + 1                              For most windings made before about 1970, all
                                              field windings, and others not described below
(Example : 15 kV machine is 1S + 1= 16 MS2)

          100 For most do armature and ac windings built after about 1970 (form-wound coils)

          5                                   For most machines with random-wound stator

                                              coils and form-wound coils rated below 1 kV

Notes: kV is the rated machine terminal to terminal voltage, in rms (root mean square) kV.
Recommended minimum insulation resistance values above, in megohms, at 40°C of the entire machine

winding for overvoltage testing or operation of ac and do machine stator windings and rotor windings .
                    From IEEE Std. 43-2000. Copyright C 2000 IEEE. All rights reserved.

  e. Dielectric absorption testing. In a dielectric-absorption test, a voltage supplied from a source of constant
potential is applied across the insulation . The test voltage used may have to be significantlyhigher than the
insulation-resistance test in orderto obtain measurable current readings . The potential source can be either a
meg-ohmmeter, as described above or a high-voltage power supply with an ammeter indicating the current being
drawn by the specimen under test. The voltage is applied foran extended period oftime, from 5 to 15 minutes,
and periodic readings are taken of the insulation resistance or leakage current. The test data is evaluated on the
basis that ifan insulation is in good condition, its apparent insulation resistance will increase as the test
progresses. Unlike the insulation-resistance test, the dielectric-absorption test results are independent of the
volume and the temperature of the insulation under test . Forthe dielectric absorption test, the values recorded at
each one minute interval are plotted on log-log paper with coordinates for resistance versus time . The slope of
the resulting curve gives a good indication ofthe insulation condition. A good insulation system will have a

2- 1 0


---

                                               TM 5-694

slope that is a straight line increasing in respect to time. The characteristic slope of a poor insulation system will
be a curve that flattens out with respect to time.

 f Polarization index testing. The polarization index is a specialized application ofthe dielectric

absorption test. The index is the ratio of insulation resistance at two different times after voltage
application, usually the insulation resistance at 10 minutes to the insulation resistance at 1 minute . The
use ofpolarization-index testing is usually confined to rotating machines, cables, and transformers . A
polarization index less than 1 .0 indicates that the equipment needs maintenance before being placed in
service. References are available for polarization indexes for various types ofequipment as well as in
table 2-2. Acceptance testing specifications for Electrical Power and Distribution Equipment and
Systems NETA 1999 and Recommended Practice for Testing Insulation Resistance ofRotating
Machinery (IEEE Std. 43-2000) are references available for polarization indexes for various types of
equipment. The polarization index test lasts for 10 minutes. The insulation resistance is recorded after 1
minute, then again after 10 minutes. The polarization index is the quotient of the 10-minute and 1 minute
readings as shown in the following equation:

Where:  PI = RIO/R, (dimensionless)

        PI = polarization index
        R = resistance.

For polarization indexes in transformers an acceptable value would be 2 or higher, values between 2 and 1
indicate marginal condition, and values below 1 indicate poor condition. After insulation resistance
readings have been made, the test voltage is returned to zero and the insulation is discharged .

  g. Highpotential testing. A high-potential test (hi-pot) consists of applying voltage across an
insulation at or above the do equivalent of the 60-Hz operating crest voltage. The do equivalent of the 60-
Hz operating crest voltage is calculated using the following equation:

Where:  Vac = Vdc/42-

        Vdc is the equivalent do voltage
        Vac is the operating crest ac voltage

The hi-pot test can be applied either as a dielectric-absorption test or a step-voltage test. DC high potential tests
are "go no-go" tests. The cable is required to withstand the specified voltage for the specified time duration .
These tests will normally reveal major problems due to improper field handling, improperly installed accessories
or mechanical damage. Recommended test voltages are given in standard tables for do and ac. To perform the do
Hi-pot test the inputvoltage to the testset should be regulated. The currentsensing circuits in test equipment
shall measure onlythe leakage current associated with the cable under test and shall not include internal leakage
ofthe test equipment. Record wetbulb and dry-bulb temperatures orrelative humidity and temperature. The wet
bulb temperature is defined as the temperature given by athermometer bulb which is covered with an absorbent
material (linen wetwith distilled water) and exposedto theatmosphere so that evaporation will cool the water
and the thermometer bulb. The dry-bulb temperature is defined as the temperature of the atmosphere given by an
ordinary thermometer. Test each section of cable individually with all other conductors grounded. All shields
must also be grounded . Terminations shall be adequately coronasuppressed by guard ring, field reduction
sphere, or other suitable methods as necessary. Precaution should be taken to insure that the maximum test
voltage does not exceed the limits for terminations specified in IEEE Standard 48 or manufacturers specifications.
When applied as a dielectric-absorption test, the maximum voltage is applied gradually over a period of from 60
to 90 seconds. The maximum voltage is then held for 5 minutes with leakage-current readings being taken each

                                               2- 1 1


---

TM 5-694
minute. In cables, high ambient temperature or humidity at the ends of improperly prepared cables can raise the
do leakage current to many times its normal value. When applied as a step-voltage test, the maximum voltage is
applied in a number of equal increments, usually not less than eight, with each voltage step being held for an
equal interval of time. A typical voltage versus time graph as shown in figure 2-2. The time interval between
steps should be long enough to allow the leakage current to reach stability, approximately 1 or 2 minutes. A
leakage-current reading is taken at the end of each interval before the voltage is raised to the next level.

            4 8 12 time (min)

                                          Figure 2-2. Step-voltage versus time

A plot oftest voltage versus leakage current or insulation resistance is drawn as the test progresses . A
nonlinear increase in leakage current can indicate imminent failure, and the test should be discontinued .
See figure 2-3.

        c   No breakdowns in

            insulation system I

         m

        Y ~-~-" Breakdown of
        Jm                       insulation system

                                                            Voltage (kV)

                                Figure 2-3. Step-voltage highpotential test current
After the maximum test voltage is reached, a dielectric absorption test can be performed at that voltage,
usually for a 5-minute period.

  h. AC highpotential testing. Alternating-current high-potential tests are made at voltages above the
normal system voltage for a short time, such a 1 minute . The test voltages to be used vary depending on
whether the device or circuit is low or high voltage, a primary or control circuit, and whether it was tested

2- 1 2


---

                                                                                                                    TM 5-694

at the factory or in the field. Manufacturers' instructions and the applicable standards should be consulted
for the proper values .

  i. Insulation powerfactor testing. The power factor of an insulation is a measure ofthe energy component
ofthe charging current. Power-factor testing is used to determine the power factor of an insulation system .
Power-factor testing is a useful tool in evaluating the quality of insulation in power, distribution, and instrument
transformers; circuit breakers ; rotating machines, cables ; regulators ; and insulating liquids. The equipment to be
tested should be isolated from the rest ofthe system, if practical, and all bushings or terminations should be
cleaned and dried. The test should be conducted when the relative humidity is below 70 percent and when the
insulation system is at a temperature above 32°F (0°C). The test equipment used should be such that the power
factor or dissipation factor can be read directly or such that the charging volt-amperes and the dielectric losses can
be read separately so that a ratio might be computed. The test equipment should also have sufficient
electromagnetic interference cancellation devices or shielding to give meaningful test results even when used in
an area ofstrong interference, such as an energized substation . Electromagnetic interference distorts the readings,
yielding incorrect values. The desired measurements should be performed following the operating instructions
supplied with the test equipment. The lead connections may have to be changed several times, depending on the
complexity ofthe apparatus and test equipment. A meaningful evaluation will include comparison to
manufacturer's results taken at the factory and/or nameplate data. Ontransformer tests, obtain the power factor
ofeach winding with respect to ground and each winding with respect to each other winding. In addition, tests
should be made of each bushing with a rated voltage above 600 volts, either using the power factor or capacitance
tap ifthe bushing is so equipped or by use of a "hot-collar" test using a test electrode around the outside shell of
the bushing. On higher voltage circuit breakers, the power factor of each line-side and load-side bushing
assembly complete with stationary contact and interrupters, with the circuit breaker open, and each pole of the
circuit breaker with the breakerclosed should be obtained. On ac rotating machines, the neutral connection on
the stator should be removed and a test of each winding with respect to the other two windings and ground should
be obtained. For cables, the power factor of each conductorwith respectto ground should be obtained and a hot-
 collar test should be made of each pothead ortermination. Power-factor testing of insulating oil should be
 performed in accordance with American Society for Testing and Materials (ASTM) D 924, Standard Test
 Method forDissipation Factor (orPower Factor) and Relative Permittivity (Dielectric Constant) of Electrical
 Insulating Liquids.

 2-5. Switch/circuit breaker testing

 In addition to the insulation testing mentioned above, for large switches and circuit breakers the following tests
 can be applied.

   a. Circuit breaker time-travel analysis . This test, used on medium and high-voltage circuit breakers
 provides information as to whether the operating mechanism of the circuit breaker is operating properly.
 This test can be used to determine the opening and closing speeds of the breaker, the interval time for
 closing and tripping, and the contact bounce . The test provides information that can be used to detect
 problems such as weak accelerating springs, defective shock absorbers, dashpots, buffers, and closing
 mechanisms . The test is performed by a mechanical device that is attached to the breaker. One device, a
 rotating drum with a chart attached, is temporarily connected to the chassis or tank of the breaker. A
 movable rod with a marking device attached is installed on the lift rod portion ofthe breaker. As the
 breaker is opened or closed, the marking device indicates the amount of contact travel on the chart as the
 drum rotates at a known speed. With another available device, a transducer is attached to the movable
 rod, and the breaker operation is recorded on an oscillograph .

    b. Contact-resistance testing. This test is used to test the quality of the contacts on switches and
 circuit breakers. A test set designed for this purpose is available with direct-scale calibration in
 microhms, capable of reading contact resistances of 10 microhms or less. An alternate method is to pass a

                                                                                                                       2- 1 3


---

TM 5-694

known level ofdirect current through the contact structures and to measure the do millivolt drop across
the contacts . The data obtained can then be converted to resistance by applying Ohm's Law. The
alternate method requires a source ofat least 100 amperes with a millivolt meter of approximately 0-20
mV range.

2-6. Transformer testing

Transformers are subject to the following tests in addition to the insulation testing mentioned above in
paragraph 2-4. However, dry-type transformers would not be subject to fault-gas analysis and insulating
liquid analysis due to the fact that these types of transformers usually feature a gaseous or dry compound
insulating medium. Cast coil transformers, which are defined as a transformer with high-voltage coils
cast in an epoxy resin, would also not be subject to fault-gas analysis and insulating liquid analysis due to
the fact that the core and coils of these types of transformers are not immersed in an insulating liquid .
Cast coil transformers are considered to be dry-type transformers .

   a Rcmsformer turns-ratio andpolarity tests. The turns-ratio test is used to determine the number ofturns in
one winding ofa transformer in relation to the number of turns in the other windings ofthe same phase ofthe
transformer. The polarity test determines the vectorai relationship of the various transformer windings . The tests
are applicable to all power and distribution transformers . See figure 2-4 for a diagram of a typical fluid filled
power transformers . Castcoil transformers are also subject to thesetests. The turns-ratio test and the polarity test
can be done on transformers of all sizes. The turns-ratio test is also commonly performed on instrument
transformers. The test equipment used will ordinarily be a turns-ratio test set designed for the purpose, although,
ifnot available, twovoltmeters or two ammeters (for current transformers only) can be used. When two ac
voltmeters are used, one is connected to the high-voltage winding and the other is connected to the low voltage
winding. The high voltage winding is excited to a voltage not exceeding the rating of the voltmeter. Both
voltmeters are read simultaneously. A second set of readings should be taken with the metering instruments
interchanged. The values indicated should be averaged to calculatethe ratio. A meaningful ratio measurement
may be made using only a few volts of excitation. The transformer should be excited from the highest voltage
winding in order to avoid possibly unsafe high voltages. Care should be taken during the application ofvoltage
 and during the measurement. It is important that simultaneous readings forboth voltmeters be made. The
 voltmeters used should have accuracy's matching with the requirements ofa 0.5 % ratio calculation. When a
 turns-ratio test is performed, the ratio should be determined forall no-loadtaps. Ifthe transformer is equipped
 with a load-tap changer, the ratio should be determined for each load-tap changer position.

   b. Fault-gas analysis . The analysis of the percentage of combustible gases present in the nitrogen cap
 of sealed, pressurized oil-filled transformers can provide information as to the likelihood of incipient
 faults in the transformer. Fault-gas analysis can be performed on mineral-oil-immersed transformers of
 all sizes. When arcing or excessive heating occurs below the top surface of the oil, some oil decomposes .
 Some ofthe products of the decomposition are combustible gases that rise to the top of the oil and mix
 with the nitrogen above the oil. The test set for this test is designed for the purpose. A small sample of
 nitrogen is removed from the transformer and analyzed .

    c. Insulating-liquid analysis. Insulating-liquid analysis can be performed in the field on oil-immersed
 power transformers of all sizes. Regular tests, on a semiannual basis, should be made on insulating oils
 and askarels . Samples should be taken from the equipment and tested in accordance with the
 manufacturer's instructions .

 2-7. Rotating machine testing

  The tests described below are for rotating machines such as motors and generators . These tests are
  applied based on the horsepower and WA rating of the machine.

  2- 1 4


---

                                                                                                                                TM 5-694

  a. Insulation-resistance (megger) testing. The insulation resistance test as described in paragraph 2-
4d is also applicable to rotating machines. This testing procedure applies to armature and rotating or
stationary field windings. If the insulation resistance is below the established minimum, circuit
components should be tested separately until the low insulation reading is located. Insulation-resistance
history based on tests conducted on new motors or after rewinding, cleaning, or from recorded data made
under uniform conditions form a very useful basis for interpretation of a machine winding condition.
When comparing records of periodic tests any persistent downward trend is an indication of insulation
trouble even though the values might be higher than the recommended minimum safe values.

                    PRESSURE RELIEF                       PRIMARY BUSHINGS
                    DEVICE
                                               SECONDARY
LIQUID LEVEL GUAGE                             BUSHINGS

PRESSURE/VACUUM                                                                       ARRESTER
GUAGE                                                                                 MOUNTING
                                                                                      PROVISION
    TANK LIFTING
    LUGS

LIQUID TEMPERATURE
GUAGE

CORE AND COIL                                                      COOLING RADIATORS
BRACING                                        BASE

               COILS

                        DRAIN/FILTERING VALVE

                                     Figure 2-4. Power transformer diagram
(Reprinted from Department of the Army TM 5-686. Power Transformer Maintenance and Acceptance

                                             Testing 16 November 1998).

b. Dielectric-absorption testing. A dielectric absorption test for a rotating machine is performed as
described in paragraph 2-4e. A more complete and preferred test than the insulation resistance test, the
dielectric absorption test applies the voltage for 10 minutes or more to develop the dielectric-absorption
characteristic. The curve obtained by plotting insulation resistance against time gives a good indication
of moist or dirty windings. A steady rising curve is indicative of a clean, dry winding. A quickly
flattening curve is the result of leakage current through or over the surface of the winding and is
indicative of moist or dirty winding. If facilities are not available for a 10-minute test, a polarization
index test can be performed by taking readings at 30 and 60 seconds. The ratio of the 60-to-30-second

                                                                                                                                2-15


---

TM 5-694

or the 10-to-l-minute ratio will serve as an indication of the winding condition. Table 2-2 lists
recommended acceptable values .

Table 2-2. Recommended minimum values ofpolarization indexfor all machine components insulation
              classes .

                        Thermal Class Rating  Minimum P.I.
                                                     1 .5
                        Class 105                   2.0
                                                    2.0
                        Class 130                   2.0

                        Class 155

          f             Class 180

The Polarization Index test is not applicable to noninsulated field windings (See IEEE Std. 43-2000
Section 12.2.1).
Note: The numbers in the thermal class rating are the hot-spot temperatures in degrees centigrade ofthe
rotating machine. Ifthe 1 min insulation resistance is above 5000 MS2, the calculated P.I. may or may not
be an indication of insulation condition and is therefore not recommended as an assessment tool.

                    From IEEE Std. 43-2000. Copyright ® 2000 IEEE. All rights reserved.

  c. Overpotential testing. Overvoltage tests are performed during normal maintenance operations or
after servicing or repair of important machines or during commissioning. Such tests, made on all or parts
ofthe circuit to group, ensure that the insulation level is sufficiently high for continued safe operation.
Both ac and do test equipment are available. The test overvoltages that should be applied will depend on
the type of machine involved and level of reliability required from the machines. However, it should be
of sufficient magnitude to search out weaknesses in the insulation that might cause failure. Standard ac
over-potential test voltage when new is twice rated voltage plus 1000 volts ac. The do over potential test
is performed by applying a voltage and measuring the leakage current. The voltage applied during the
acceptance test is a function of the equipment voltage rating as shown by the following equation :

        do acceptance test voltage in kV =1 .6[.8(2E + 1,000)] where E is the rated voltage in kV.
        do maintenance test voltage in kV =1 .6[.6(2E + 1,000)] where E is the rated voltage in kV.

These values for test voltages are given in A Stitch in Time, Manual on Electrical Insulation Testingfor
the Practical Man, Biddle Instruments, 1981 . The standard duration of the test is between 1 to 5 minutes.
The do acceptance test voltage is applied to each winding separately with the other windings grounded.
The voltage is applied in steps. First one third of the do acceptance test voltage is applied. Leakage
current readings are taken at one minute intervals up to a maximum of ten minutes. Then the voltage is
increased in 1 kV intervals recording the leakage current and applied voltage at each step. Sufficient time
shall be allowed between steps for the leakage current to stabilize. The data shall be plotted leakage
current versus applied test voltage. The plot will yield a smooth curve with a rising slope for a good
insulation system . Any sudden changes in the curve characteristics are an indication of impending
failure. A high-potential test made to determine the condition ofthe insulation up to a predetermined
voltage level is difficult to interpret. It is common practice to compare known good results against test
specimens to determine what is acceptable and what fails the test.

2-8. Protective relays

Protective relays are used to sense abnormalities and cause the trouble to be isolated with minimum
disturbance to the electrical system and the least damage to the equipment at fault. Protective relays
should be set and acceptance tested prior to being placed in service and tested periodically thereafter to
ensure reliable performance. In a normal industrial application, periodic testing should be done at least

2- 1 6


---

                                                                                                                    TM 5-694

every 2 years. The person performing the test should be given the settings to be applied to each particular
relay by the engineer. There are two types of protective relays addressed in this manual . The first types
are solid state relays. These are electronic "black box" devices. As all electronic devices, solid state
relays should never be subject to hi-pot or megger testing. They typically come equipped with internal
testing capabilities . Any diagnostic tests shall be performed as indicated in the manufacturer's manual .
The second type is induction disk relays . They are subject to the following tests.

   a. Inspection. Ifrecommended or desirable, each relay should be removed from its case (if relay
design permits) for a thorough inspection and cleaning. If the circuit is in service, one relay at a time
should be removed so as not to totally disable the protection. The areas of inspection are detailed in the
manufacturer's instruction manual . These generally consist ofinspection for loose screws, friction in
moving parts, iron filings between the induction disk and permanent magnet, and any evidence ofdistress
with the relay. The fine silver contacts should be cleaned only with a burnishing tool.

   b. Settings. Prescribed setting should be applied or it should be ascertained that they have been
applied to the relay.

   c. Pickup test. In the case ofa time-over-current relay, its contacts should eventually creep to a closed
position with a magnitude of current introduced in its induction coil equal to the tap setting. The pickup
is adjusted by means ofthe restraining spiral-spring adjusting ring. A pickup test on a voltage relay is
made in much the same manner .

   d. Timing test. A timing test should be made on most types of relays . In the case of a time-over-
current relay, one or more timing tests are made at anywhere from two to ten times the tap setting to
verify the time-current characteristic ofthe relay. One timing point should be specified in the prescribed
 settings. Tests should be made with the relay in its panel and case, and the time test run at the calibration
 setting.

   e. Instantaneous test. Some protective relays are instantaneous in operation, or might have a separate
 instantaneous element. In this context, the term instantaneous means "having no intentional time delay."
 If used, the specified pickup on the instantaneous element should be set by test. Again referring to the
 relay used in the example above, at two times pickup, its instantaneous element should have an operating
 time ofbetween 0.016 and 0.030 seconds.

  f. Test oftarget and seal-in unit. Most types of protective relays have a combination target and seal-

 in unit. The target indicates that the relay has operated. The seal-in unit is adjustable to pickup at either
 0.2 or 2.0 amperes. The pickup setting is established by the relay coordination study. The setting for the
 seal-in unit should be specified with the relay settings . It should be verified by test that the contacts will
 seal in with the minimum specified direct current applied in the seal-in unit.

    g. Test oftripping circuit. A test should be made, preferably at time of testing the relays, to verify that
 operation ofthe relay contacts will cause the breaker to trip .

 2-9. Ground system testing
 In addition to the general component tests stated in the preceding paragraphs, there are tests to be
 performed on the system as a whole after the components are installed. They are as follows:

    a. Equipment ground-impedance testing. This test is used to determine the integrity of the grounding
 path from the point of test back to the source panel or supply transformer. A low-impedance grounding
 path is necessary to facilitate operation ofthe overcurrent device under ground-fault conditions as well as

                                                                                                                        2-17


---

TM 5-694

provide a zero voltage reference for reliable operation of computers and other microprocessor-based
electronic equipment. Instruments are available to measure the impedance ofthe grounding path . When
using these instruments, the user should remember that, although a high-impedance value is an indication
of a problem, for example a loose connection or excessive conductor length, a low-impedance readout
does not necessarily indicate the adequacy of the grounding path . A grounding path that is found to have
a low impedance by the use of relatively low test currents might not have sufficient capacity to handle
large ground faults . Ground loop or grounding conductor impedance cannot be measured reliably in
situations where metallic conduits are used or where metallic boxes or equipment are attached to metal
building frames or interconnected structures. Such situations create parallel paths for test currents that
make it impossible to measure the impedance of the grounding conductors; or even to detect an open or
missing grounding conductor. Visual examinations and actual checking for tightness ofconnections are
still necessary to determine the adequacy of the grounding path .

   b. Grounded conductor (neutral) impedance testing. On solidly grounded low-voltage system (600
volts or less) supplying microprocessor-based electronic equipment with switching power supplies, this
test is used to determine the quality ofthe grounded conductor (neutral) from the point of test back to the
source panel or supply transformer. The same instruments used to perform the equipment ground-
impedance tests can be used to perform grounded conductor (neutral) impedance tests.

   c. Grounding-electrode resistance testing. Grounding-electrode resistance testing is used to
determine the effectiveness and integrity of the grounding system . Periodic testing is necessary because
changes in soil temperature, soil moisture, conductive salts in the soil, and corrosion of the ground
connectors cause variations in soil resistivity. The test set used will ordinarily be a ground-resistance test
 set, designed for the purpose, using the principle of the fall of potential of ac-circulated current from a test
 spot to the ground connection under test.

   d. Neutral-current testing. Situations exist where it is possible for the neutral current ofthree-phase
 systems to exceed the ampacity of the neutral conductor in normal operation. This is usually due to
 unbalanced phase loading, nonsinusoidal load currents (harmonics), or a combination of the two. Also
 nonlinear loads, such as rectifiers, computers, variable speed drives, electrical discharge lighting fixtures,
 and switching mode power supplies, cause phase currents that are not sinusoidal . The problem can be
 detected using a true root mean square (RMS) ammeter to measure the current flowing in the neutral
 conductor. The use of an average responding ammeter calibrated to read the RMS value of a sine wave
 should not be used as it will not yield valid results when used on nonsinusoidal waveforms . Ifthe neutral
 current is found to be excessive, the current in each phase should be measured to determine ifan
 abnormal condition exists. Ifexcessive neutral current exists and the phase currents are not excessive,
 harmonic content is the most likely cause. A means of analyzing neutral current containing harmonic
 components is through the use of a wave or spectrum analyzer.


---

                   TM 5-694

        CHAPTER 3
COMPONENT TESTING

3-1. Introduction to component testing

The component inspection and checks are the key to the success ofany commissioning program. Each
component ofthe system should be initially checked for damage, deterioration, and failures by a
procedure using inspections and tests as defined by the specific equipment manufacturer . The equipment
manuals from the manufacturer identify the minimum required receipt inspections, handling and
installation procedures, drawing and wiring verification, de-energized and energized component tests,
minimum testing baseline and report requirements for on-going maintenance, and requirements for repair
and retesting if certain checks and tests produce unsatisfactory results. After the systems components are
interconnected, the system should be checked, using de-energized and energized methods, to verify the
proper interconnection and operation of the components including on/off control, system process
interlocks, and protective relaying functions. Once these tests are complete, the system can be energized,
and operational tests and measurements are performed. This chapter of the manual gives a typical listing
ofthe commissioning test and testing procedures that are recommended (manufacturers'
recommendations should always be incorporated into component testing) for each of the following system
components before the interconnection and operation of the components as a system is verified and tested .
The components/systems to be verified and tested are circuit switchers, transformers, switchgear - low
voltage, switchgear - medium voltage, transfer switch, motors, ac/dc drives, generators, batteries, battery
chargers, UPS systems, and cables . For equipment containing electronic components, megger testing
must not be performed. However, this equipment should be tested according to manufacturer's
 specifications .

3-2. Circuit switchers

 A circuit switcher is a device that consists of a disconnect switch and a circuit-breaking interrupter. They
 are used for switching and protecting equipment such as transformers, lines, cables, capacitor banks, and
 shunt reactors from small short circuit currents . The first step towards acceptance of any device is
 verification of nameplate data and equipment conditions . All the equipment shall be checked against
 nameplate, one-line, schematic, and wiring diagrams . All equipment shall be carefully examined upon
 receipt to ensure that no damage has occurred during shipment. Upon receipt a visual inspection ofthe
 circuit switcher and associated hardware shall be made including nameplate, parts, drawings, and
 condition. Any discrepancies should be sent to the manufacturer for a resolution. After installation, the
 circuit switcher shall be checked to ensure that it has been bolted to its permanent foundation, all shipping
 braces have been removed, and that it has been properly grounded. The alignment of the disconnect
 should be checked to ensure that the blade tongue contact enters the jaw contact on center, rotates fully
 and comes to rest within 1/8" of the stop . The interrupter action should be checked for proper operation
 as described in the operation manual . The circuit switcher shall be manually operated to check that the
 mechanism works smoothly and correctly. The contact surfaces should be checked for proper lubrication.
 The control wiring installation shall be checked per the drawings . The low pressure indicator should be
 checked by measuring the pressure in psig and recorded along with the ambient temperature at the time
 the measurement was taken and then comparing this value with the manufacturers data . Checks shall be
 made to insure that the grounding connections have been installed. Simulate a fault by activating the
 protective relay circuit and check electrical operation. Check key interlocks both mechanically and
 electrically. Testing shall include timing, contact resistance, contact part time, and charging motor


---

TM 5-694

operation. Descriptions of these tests are found in paragraph 2-5. The timing test shall be performed at
the normal operating voltage for both trip command and close command.

3-3. Transformers

There are two basic types ofpower transformers, oil-filled and dry-type. Both are subject to many ofthe
same tests. Therefore, the following test procedures apply to both types unless otherwise noted. Since
cast coil transformers are considered dry-type, the following tests also apply unless the test is noted to
only apply to oil-filled transformers.

  a. Inspection on receipt. A thorough inspection for the transformer shall be completed upon arrival
and before unloading. This inspection shall include a detailed visual inspection of the external of the
transformer. Since the largest transformer we are concerned with in this manual is 10 MVA, the
transformers do not require impact recorder. The minimum size of transformer for impact recording is
approximately 20 MVA. Oil-filled type transformers are typically shipped filled with either dry air or
nitrogen . The pressure condition, nitrogen content, and dew point shall be measured before unloading of
the transformer. A positive pressure should be maintained on nitrogen-blanketed transformers. The
oxygen content should be less than one percent. The seals ofthe transformer shall be inspected to ensure
that they are properly seated . For an acceptable transformer installation it is imperative that the
foundation is level. This should be checked well in advance of receipt of the transformer. Upon
completion ofthe equipment inspections, the transformer shall be unloaded and set into its final
installation position. The shipping bracing shall be removed and it shall then be anchored to its
foundation . The bolts (ifused) securing the transformer to its foundation shall be checked to ensure that
they are installed at the proper torque . For large transformers (above 20 MVA approximately), a visual
inspection ofthe transformer internals shall be performed on air and oil-filled transformers filled with
nitrogen. Transformers shipped filled with oil will not need internal inspections unless the electrical
testing described below indicates a problem. Then the oil must be drained, inspection performed, and
repair completed. After the repair is inspected, the transformer shall be filled with clean dielectric fluid in
strict accordance,with the manufacturer's instructions . The purpose of this internal inspection is to
determine that no displacement has occurred in transit or during unloading. Items to be verified include
the tap-changer, end braces and current transformers. This inspection must be performed with dry air in
the main tank . If the transformer has been delivered filled with nitrogen, it must be evacuated from the
 tank replaced with dry air. Personnel performing the inspection must wear clean cotton clothing, mouth
 covers and oil-resistant, clean, rubber soled shoes that contain no metallic parts. All transformer
 nameplates, wiring, and accessories shall be visually inspected and compared against the drawings.
 These accessories include but are not limited to radiators, fans, bushings, and instrument controls .

   b. Installation checks . After the preceding inspections have been completed, the transformer shall be
 assembled. Transformer assembly includes but is not limited to, mounting of radiators, fans, bushings,
 thermometers, oil level indicators, relays and expansion tank. Transformer assembly must be in
 accordance with manufacturer's instructions and design drawings . After all of the accessories have been
 installed, protection circuits shall be wired and checked. A pressure test can now be performed and the
 transformer filled with oil. The alarm, control, and trip settings on temperature indicators shall be
 inspected to verify that they are set as specified. The cooling pumps shall operate correctly, and the fan
 and pump motors shall have correct overcurrent protection. Operation of all alarm, control, and trip
 circuits from temperature and level indicators, pressure relief device, and fault pressure relays shall be
 checked. Liquid level in all tanks and bushings shall be verified. Grounding shall be verified. Once the
 above is complete the following tests shall be performed on insulation resistance, dielectric absorption,
 polarization index, transformer turns ratio test, and power factor test. Descriptions of these tests are
 found in paragraphs 2-4 and 2-6. Once completed and passed, the transformer is ready for energization .

  3-2


---

                                                                                                                    TM 5-694

3-4. Switchgear - medium voltage

The first step towards acceptance of any device is verification of nameplate data. The nameplate on all
equipment shall be checked against one-lines and schematics. The Switchgear shall be checked for
completeness of assembly. All equipment shall be carefully examined upon receipt to ensure that no
damage has occurred during shipment. A visual inspection of the area where the switchgear is installed
should be performed to confirm that there is adequate aisle space at the front and rear ofthe equipment
for proper ventilation, service and maintenance of the equipment. The Switchgear should be checked to
insurd it is properly anchored to its foundation. Visually inspect that the high voltage connections are
properly insulated. Electrically disconnecting contacts, machined parts, shutter, etc., should be checked
for lubrication and operation. The breaker alignment and manual operation shall be checked. All
blocking, supports and other temporary ties should be removed from breakers, instruments, relays, etc .
Verify proper fuses are correctly placed . Verify proper voltage and phase connections. Verify correct
component and installation of potential and current transformers (PTs and CTs) and control fuse size and
check continuity. Also check PT and CT polarity and transformer turns ratio. Temporary wiring jumpers
should be removed. Verify ground connections properly made . Verify incoming primary and secondary
connections properly made and checked for shorts or undesired grounds. Verify all equipment that has
been removed during assembly has been replaced . Verify relays are coordinated with other relays and
protective devices on the system . Refer to relay instructions before making any adjustments. Consult
local utility before making any connections to the power supply . Verify storage battery fully charged and
provided with charger. Interlocks performing properly. Circuit breakers should be checked and prepared
per instruction book . All filters in vent areas are clean and free of shipping or construction material .
Once complete, the insulation resistance and do hi pot test should be performed. Descriptions of these
test are found in paragraph 2-4. Before performing insulation tests precautions should be made to
 eliminate damage to electronic controls/sensitive equipment attached to the bus. The insulation resistance
 test should be made on the high voltage circuit to be sure that all connections made in the field are
 properly insulated. A dielectric test should then be made on the high voltage circuit for one minute at the
 maximum test voltage. Once completed and passed, the switchgear is ready for energization.

 3-5. Switchgear - low voltage

 The first step towards acceptance of any device is verification of nameplate data. The nameplate on all
 equipment shall be checked against one-lines and schematics. All equipment shall be carefully examined
 upon receipt to ensure that no damage has occurred during shipment. A visual inspection of the area
 where the switchgear is installed should be performed to confirm that there is adequate aisle space at the
 front and rear of the equipment for proper ventilation, service and maintenance of the equipment. The
 Switchgear should be checked to insure it is properly anchored to its foundation. All switches, circuit
 breakers, and other operating mechanisms should be manually exercised to make certain they are properly
 aligned and operate freely . An insulation resistance test should be performed to make sure the Switchgear
 is free from short circuits and grounds. This should be done both phase-to-ground and phase-to-phase
 and with the switches or circuit breakers both opened and closed. Any electrical relays, meters, or
 instrumentation should be checked to determine that connections are made properly and the devices
 function properly. Electrically exercise all electrically operated circuit breakers, and other mechanisms
 (but not under load), to determine that the devices operate properly . An auxiliary source of control power
 may be necessary to provide power to the electrical operators. Test the ground fault protection system (if
 furnished) in accordance with the manufacturer's instructions . Check the settings of the adjustable
 current and voltage trip mechanisms to confirm that they are at the proper values . Make certain that field
 wiring is clear oflive bus and, where necessary, physically secured to withstand the effects of fault
 currents . Check to determine that all grounding connections are made properly. Remove all debris, scrap
 wire, etc., from the Switchgear interior before closing the enclosure. Install covers, close doors, and make
  certain that no wires are pinched and that all enclosure parts are properly aligned to be tightened. Once

                                                                                                                         3-3


---

TM 5-694

the above is complete perform an insulation resistance test. Before performing insulation tests
precautions should be made to eliminate damage to electronic controls/sensitive equipment attached to the
bus. The Insulation Resistance test is described in paragraph 2-4. Once completed and passed, the
switchgear is ready for energization.

3-6. Transfer switch

The first step towards acceptance of any device is verification of nameplate data. The nameplate on all
equipment shall be checked against one-lines and schematics . The transfer switch shall be checked for
completeness of assembly. All equipment shall be carefully examined upon receipt to ensure that no
damage has occurred during shipment such as loose parts and insulation damage. The Switch shall be
checked for proper alignment and manual operation. The switch insulation resistance (phase-to-phase and
phase-to-ground) shall be measured in normal and emergency positions. The wiring ofthe potential
transformer to the control device should be checked for continuity and the control fuse should be checked
to confirm size . The potential transformer should be tested as described in paragraph 3-3. The transfer
switch should be checked for proper grounding. The timer settings should be checked against design
parameters .

3-7. AC/DC drives

The first step towards acceptance ofany device is verification ofnameplate data. The nameplate on all
equipment shall be checked against one-lines and schematics. All equipment shall be carefully examined
upon receipt to ensure that no damage has occurred during shipment. Drives are controllers used to vary
the speed of a motor. Controllers are electronic devices that should never be megger tested . They
typically come equipped with internal testing capabilities . Any diagnostic tests shall be performed as
indicated in the manufacturer's manual . A visual inspection of the controller, enclosure, nameplates,
connections, and drawings shall be performed. After removal of the controller enclosure cover, the
controller shall be checked for physical damage and any debris from installation such as wire strands shall
 be removed using clean, dry, low-pressure air. All terminal connections shall be checked for tightness.
 The drive should be energized with no connection to the load and diagnostic test should be run. Motors
 should be tested separately as indicated in the motor paragraph.

 3-8. Motors

 The first step towards acceptance of any device is verification ofnameplate data . The nameplate on all
 equipment shall be checked against one-lines and schematics . All equipment shall be carefully examined
 upon receipt to ensure that no damage has occurred during shipment. A visual test ofthe motor shall be
 performed to ensure that the motor was not damaged in transit from the factory. Check that no loose
 items such as shaft keys, couplings, etc., are present. Check all connections for tightness and proper
 insulation . Amechanical test of the motor shall be performed to check that the motor is free from
 interference . This is accomplished by first uncoupling the motor from the driven machinery. The motor
 shaft is then manually rotated. The shaft should rotate freely . Once the above is complete, insulation
 resistance, power factor, do hi-pot test, and polarization index tests shall be performed. The Insulation
 Resistance test (Megger) shall be performed for motors less than or equal to 200 hp and 480V . For
 motors greater than or equal to 200 hp and 2400V the Insulation Resistance and Polarization index are
 required . The Insulation Resistance, Polarization index, and do Hi Pot tests are required for motors
 exceeding 200 hp and 2400V. On ac rotating machines, the neutral connection on the stator should be
 removed and a test of each winding with respect to the other two windings and ground should be
 obtained. After insulation resistance readings have been made, the test voltage is returned to zero and the
  insulation is discharged. High pot each phase separately with the other two phases and the winding temp
 detectors grounded . Capacitors and surge arrestors should be disconnected during this test. Once

  3-4


---

                                                                                                                                TM 5-694

completed and passed, the motor is ready for energized checks. A phase check should first be performed
by momentarily energizing or "bumping" the motor to confirm the proper direction of rotation. This will
confirm that the correct phase connections have been made. Once the correct phasing is confirmed, the
motor is ready for energization .

3-9. Generators

The first step towards acceptance of any device is verification of nameplate data . The nameplate on all
equipment shall be checked against one-lines and schematics . All equipment shall be carefully examined
upon receipt to ensure that no damage has occurred during shipment . A visual inspection shall be made
to check for any loose parts, connections, or foreign materials, nameplates/parts drawings . The clearance
in the generator and exciter air gap shall be checked. Be sure the generator set turns over freely. Rotate
the generator rotor by hand at least two revolutions to be sure there is no interference and it turns freely.
Do not apply any mechanical force to generator fan when rotating generator rotor. The insulation on all
wires shall be inspected. Insulation that is loose or frayed is unacceptable and should be repaired . All
wiring should be checked against the equipment drawings and all connections should be secure . Loose or
dirty connections are unacceptable and should be repaired . All leads should be supported or tied to keep
them from being damaged by rotating parts or sharp corners. After installation, the generator shall be
checked for proper mounting and grounding. Verify that the generator is connected for the required
voltage. The equipment should be inspected for any foreign objects such as remaining packing materials,
loose debris including, building materials, tools, hardware, rags, paper, leaves, etc., that could be drawn
into the generator and removed. All bolts and fasteners should be checked for tightness. All covers and
guards should be in place and secure . Always make a thorough visual inspection to check for any
obvious problems before attempting to test and run the generator. Ifthe generator is part ofa motor
generator (MG), uncouple the motor. Manually rotate the motor shaft to check that the motor is free from
 any interference and reconnect. Check that no loose items such as shaft keys, couplings, etc., are present.
 Check all connections for tightness and proper insulation. Insulation resistance, polarization index and do
 overpotential tests shall be performed before the generator is energized.

   a. Winding resistance test. The main stator winding resistance is very low. A meter capable of
 readings in the milli-ohm range would be required . A standard VOM can be used to check for continuity,
 shorts or grounds. The winding resistance is measured with a do bridge and compared with the calculated
 design values . This value, corrected to operating temperature is also used to calculated stator 12R loss for
 efficiency determination.

   b. DC overpotential test. Perform a do overpotential test to assess the dielectric strength of the insulation of a
 generator. The ac voltage used in this test is the factorytest value. For stator windings this value is typically
 calculated to be twice the rated voltage plus 1,000. High pot each phase separately with the other two phases and
 the winding temperature detectors grounded. Capacitors and surge arrestors should be disconnected during this
 test. Measure the voltages . Now the generator can be runwith no load and tested by performing the constant
 excitation test and the current measurements .

    c. No-load test. This test will determine whether a problem exists in the generator or regulator
 system . The theory behind this test is as follows. The output voltage of a generator is dependent on its
 speed, design, load, and exciter input current. Ifthe speed and exciter input are known, the output voltage
 at no load can be measured and compared to the design value. With the generator shut down, connect
 voltmeter to the generator output . Disconnect the leads at the regulator and connect a 12-volt battery
 capable of supplying one amp to the leads. Check to make sure that the battery is connected to the leads
 with the correct polarity . With no load on the generator, (main breakers open) run the generator at rated
 speed . Measure generator output voltage. Shut the generator down. Compare the voltage reading with

                                                                                                                         3-5


---

TM 5-694

design value, ifthey match the regulator is functioning properly (implement this procedure in accordance
with manufacturers' recommendations).

  d. Load test. This test will determine whether a problem with the sequence ofthe loading ofthe
generator exists . With no load on the generator, (main breaker open) run the generator at rated speed.
Gradually add load as sequenced. Standard procedures for commercial, routine and acceptance tests for
determination of speed- governing performance characteristics of internal combustion engine-generator
units can be found in ASME Power Test Codes (PTC) 26 .

  e. Operation ofmultiple generators in parallel. When operating multiple generators in parallel the
operators must be aware oftheir operating sequence. For a system with three generators in parallel the
operating sequence could be generator one then two then three or, two then one or three or, either one or
two or three. A way to identify the scheme ofa system is to functionally test the system by removing one
generator from the system and verifying that the system operates. For example, when operating three
generators in parallel, where two are normally operating and one is considered the backup generator the
circuitry could be such that the first generator always acts as the starting generator and when it is up to
speed, the second generator will synchronize to the first and following this, the third generator will
synchronize to the second (one then two then three) . In this arrangement ifthe first generator does not
come up to speed (or is taken out of service), the second generator will not go on-line and subsequently
neither will the third or, ifthe first generator does come up to speed but the second generator is down for
service, the third will not go on-line since it is dependent on the third. A scheme where the first generator
is the staring generator and either generator two or three synchronize to it is preferable over the first
scheme since the probability of a second generator coming on-line is greater however you still stand the
risk ofthe staring generator failing and thus halting the system . A preferred scheme is one where any of
the three generators will perform as a starting generator and either of the remaining generators will
synchronize to the generator on-line (one or two or three) .

   f. Speed control checks . When the alternating current generator sets are in parallel, load division
between units is entirely controlled by the speed setting of the engine governors. Increasing the speed
 setting ofone engine will cause it to absorb more load, and other generator sets in the system will be
 relieved of some load. Conversely, decreasing the speed setting ofone engine will cause it to decrease
 load. Other generator sets will absorb that load. All load can be remove from a generator by slowly
 decreasing the speed setting. Ifthe speed setting is moved lower than the no load point, that generator set
 will absorb power from other units which will continue to drive it at synchronous speed. It is impossible
 to have stable parallel operation ifmore than one unit in the system is set for zero speed droop
 (isochronous) operation unless the governors are the electronic load sharing type. When two or more
 units are operation in parallel, the regulator must control the excitation ofthe alternators so they share the
 reactive load . Two ways are: reactive droop compensation and reactive differential (cross current)
 compensation . Reactive droop compensation does not require wiring interconnection between regulators .
 During parallel droop compensation operation, the bus voltage droops (decreases) as the reactive lagging
 power factor load is increased. Reactive differential (cross current) compensation requires the addition of
 interconnecting leads between the current transformer secondaries and allows operation in parallel
 without voltage droop with reactive load . Cross current compensation can only be used when all the
 paralleling current transformers on all the generators delivering power to the bus are in the CT secondary
 interconnection loop. Because of this requirement, cross current compensation operation cannot be used
 when a generating system is operating in parallel with the utility power grid. Utility voltage can vary
 enough to cause high circulating current in a paralleled generator. KVAR controllers must be used to
 adjust generator voltage to match utility and minimize circulating current.


---

3-10 . Batteries

Although battery type varies (e.g., NiCd, Lead Acid), the acceptance criterion remains generally the same. The
fast step towards acceptance of anydevice is verification ofnameplate data. The nameplate on all equipment
shall be checked against one-lines and schematics. All equipment shall be carefully examined upon receipt to
ensure that no damage has occurred during shipment. Any apparent physical damage shall be recorded . Ifthe
battery is delivered filled, it shall be inspected to verify that no electrolyte has leaked during transit Ifthe battery
cells are not delivered filled, it is recommended that they be filled according to manufacturers recommendations
before installation on racks. The individual cell condition check shall include visual inspection of cell integrity
investigating evidence ofcorrosion at terminals, connections, racks, or cabinet The general appearance and
cleanliness ofthe battery, the battery rack or cabinet and battery area including accessibility shall be observed.
The cells shall be checked for cracks in cell or leakage of electrolyte as well as the integrity of the cover.
Electrolyte should be added to any cell in which the electrolyte level is below the top of the plates. Before
installation, the voltage ofeach cell shall be measured. The voltage measured should be equal to or less than 0.05
V below the manufacturers open circuit voltage. Ifit is not, the manufacturer shall be contacted to determine the
next course ofaction. The cell polarity for positive to negative connections shall be checked. The battery shall be
assembled as shown on drawings. Each battery cell is then checkedto ensure the electrolyte level is at the
maximum level. The interconnection ofthe battery cells shall be checked for polarity. The connector bolts shall
be checked to ensure that they have been tightened to the manufacturers recommended torque values. The cell
internal ohmic values and the intercell connection resistances shall be then measured . This is accomplished by
applying a load across the battery and measuringthe step change in voltage and current for each cell taken
between the positive and negative terminal posts of adjacent cells as well as the battery as a whole. The ohmic
value is the change in voltage divided by the change in current The resistance values for each cell shall then be
averaged and any interconnection that varies more than 10% or 5 AQ over the average shall be remade and then
rechecked for its resistance value. These values shall become baseline values for comparison in future tests. The
presence offlame arresters, adequacy of battery support racks, mounting, anchorage, grounding, and clearances,
 ventilation ofbattery room enclosure, and existence of suitable eyewash equipment shall be verified. After
 completion ofthe above inspections the battery is ready to be connectedto the charger. After charging, the
 following should be measured: each cell voltage and total battery voltage with charger in float mode of operation;
 ripple current; specific gravity; electrolyte temperature; electrolyte fill level; overall float voltage measured atthe
 battery terminals; chargeroutput current and voltage, ambienttemperature, condition of ventilation and
 monitoring equipment; and temperature of the negative terminal of each cell ofthe battery. When the battery is
 charged, use a voltmeter to check the polarity of the series connections. The total voltage shall be measured both
 across the battery and between adjacent cells and then shall be compared to the specified voltage. The total
 voltage should approximately be the resultant ofthe quantity of cells multiplied by the typical cell voltage. A
 variation is an indication that the battery maybe improperly assembled.

   a. Discharge test. The values for discharge time and end point voltage should be selected from the
 battery manufacturer's published ratings and the values used for the acceptance test should be
 approximately the same as that of the intended application. The discharge rate should be at a constant
 current or constant power load equal to the selected manufacturer's rating ofthe battery. The charging
 method used as the basis for the published data is an important factor. For a stationary float application,
 data based on prolonged constant potential charging should be used . If constant current charging has
 been used to establish the published data, appropriate float charging correction factors should be obtained
 from the manufacturer. Note that the test discharge current is equal to the rated discharge current divided
 by the temperature correction factor for the initial electrolyte temperature. Set up a load and the
 necessary instrumentation to maintain the test discharge rate determined in above. Disconnect the
 charging source, connectthe load to the battery, start the timing, and continue to maintain the selected
 discharge rate. If the charging source cannot be disconnected, the current being drawn by the load has to

                                                                                                                         3-7


---

      TM 5-694

      be increased to compensate for the current being supplied by the charging source to the battery. Read and
      record the individual cell voltages and the battery terminal voltage. The readings should be taken while
      the load is applied at the beginning and at the completion of the test and at specified intervals. There
       should be a minimum of three sets of readings. Individual cell voltage readings should be taken between
      respective posts of like polarity of adjacent cells so as to include the voltage drop of the intercell
       connectors. Maintain the discharge rate and record the elapsed time at the point when the battery terminal
       voltage decreases to a value equal to the minimum average voltage per cell as specified by the design of
       the installation times the number of cells.

         b. Capacity check. The capacity ofthe battery is checked using the following equation :

                   Percent Capacity at the test rate at 25°C (77°F) = (ta / ts) x 100
       Where:
is t4 the actual time of the test to specified terminal voltage as corrected for temperatures

                   is is the rated time to specified terminal voltage

       3-11. Battery chargers

       The first step towards acceptance of any device is verification ofnameplate data . The nameplate on all
       equipment shall be checked against one-lines and schematics . All equipment shall be carefully examined
       upon receipt to ensure that no damage has occurred during shipment . A visual inspection should be
       performed to verify the completeness of the equipment, correctness of installations, supports, grounding,
       and wiring. The rating plate shall be checked to ensure that both the ac supply to the charger and the
       battery to be connected corresponds to the charger's parameters . Confirm that all shipping and other
       debris in and around the charger cabinet have been removed. Check settings ofthe charger and calibrate
       per manufacturer's manual to match the battery (float and equalizing levels). Ifthe battery charger has
       been factory set, check the charger float and equalizing voltage levels against drawings and specifications .
       If not, set the charger float and equalizing voltage levels to those listed on drawings and specifications .
       Before connecting to the battery, measure the output voltage provided by the charger and record . Verify
       that all charger functions and alarms operate correctly. Verification that the battery is connected to the
       battery charger properly is extremely important. The negative wire from the negative terminal of the
       battery must be connected to the negative terminal ofthe charger. Similarly, the positive wire from the
       negative terminal of the battery must be connected to the positive terminal of the charger. A battery
       charger is an electronic device that converts ac power to do power. The charger supplies this do power to
       the battery. As with all electronic devices, this device should not be megger tested.

        3-12. UPS systems

        The first step towards acceptance ofany device is verification of nameplate data. The nameplate on all
        equipment shall be checked against one-lines and schematics . All equipment shall be carefully examined
        upon receipt to ensure that no damage has occurred during shipment. The Static UPS System consists of
        the battery charger, inverter, battery, transfer switch, circuit breakers, and cables. A picture of a typical
        UPS systems is seen in figure 3-1 . Of the UPS system, the component testing for the battery charger,
        battery, transfer switch, circuit breakers, and cables are described individually in this manual . The
        inverter is similar in construction to the charger. It converts do power to ac power using solid state
        electronics. Therefore, this device should not be megger tested . The completeness of the assembly shall
        be confirmed. A visual inspection should be performed to verify the correctness of installations, supports,
        grounding, and wiring . Verify that the air inlets are not obstructed. The interconnections shall be
        checked against the wiring schematic to ensure the proper phasing and voltage connections. For example,
        both the battery charger connections to the battery and the battery to the inverter should be checked to insure that

        3-8


---

                                                                                                                                TM 5-694
they have the correct polarity. Measure the input voltage provided by the battery and record . Measure the output
voltage and current from the inverter and record. Verify that these values correspond to the design values .
3-13 . Cables
For commissioning ofcables, the receipt inspection and testing is performedwhile the cable is still on the reel.
The exposed sections of the cables are visually inspected for signs of physical damage, the end caps are checked
for tightness. The cable types and configuration are checked for correctness against drawings and purchasing
documents. Continuity tests are performed on each conductor and the shield . For power cables, insulation
resistance tests are performed between each conductor and each conductor and the shield . The cable installation
shall be checked against one-lines and schematics. After installation, the cables are inspected fordamage, proper
trained bending radius, adequate spacing for ampacity, proper installation of fireproofing, proper size,
termination, and identification . Next, conductors are checked for continuity . The following tests shall be
performed before the cables are energized. They are the insulation resistance (Megger) test and the do hi pot test .
For medium and high voltage shielded cables the acceptance is dependent on the do hi pottest . A satisfactory test
is the exponential decrease of current with time with a fixed do voltage applied. Non-shielded cables are not

                           Figure 3-1 . Static UPS system 150 to 750 WA (courtesy ofLiebert)
 subject to the hi-pot test because only the sections of cable in contact with ground (such as cable tray rungs) are
 actually tested and therefore the test is notmeaningful. Test duration should not exceed 5 minutes for non-
 shielded cable or 15 minutes forshielded cable. When performing a do Highpotential test on cables, all
 precautions and limits as specified in the applicable NEMA/ICEA (Insulated Cable Engineers Association)
 standard for the specific cable should be followed. Tests should be performed in accordance with ANSMEEE
 Standard 400. Test voltages shall not exceed 80 percent of cable manufacturer's factorytest value or the
 maximum test voltage in table 3.1 below. The testprocedure should be as follows and the results for each cable
 test shall be recorded . Test each section of cable individually with all other conductors grounded . All shields
 must also be grounded . Terminations shall be adequately corona-suppressed by guard ring, field reduction
  sphere, or other suitable methods as necessary. Precaution should be taken to insure that the maximum test
  voltage does not exceed the limits forterminations specified in IEEE Standard 48 or manufacturers specifications .

                                                                                                                         3-9


---

TM 5-694

Reduce the conductor test potential to zero and measure residual voltage at discrete intervals. Upon the
completion of the test, apply grounds for a time period adequate to drain all insulation-stored charge. When new
cables are spliced to existing cables, the do high-potential test shall be performed on the new cable prior to
splicing . After test results are approved for the new cable and the splice is completed, an insulation resistance test
and a shielding continuity test should be performed on the length ofthe new and existing cable including the
splice. After a satisfactory insulation resistance test, a do high potential test shall be performed on the cable
utilizing atest voltage acceptable to owner and not exceeding 60 percent of factory test value.

          Table 3-1. Medium-voltage cables maximumfield acceptance test voltages (kV, dc)

       Insulation Type     Rated Cable Voltage Insulation Level Test          Voltage kV (dc)
       Elastomeric:                                                                25
       Butyl and Oil Base  5 kV                100%                                25
                                                                                   55
       Elastomeric: EPR    5 kV                133%                                65
                                                                                    80
       Polyethylene        15 kV               100% _                              25
Derived from ANSI/IEEE                                                             25
                           15 kV               133%                                 35
                                                                                    45
                           25 kV               100%                                 55
                                                                                    65
                           5 kV                100%                                 80
                                                                                   100
                           5 kV                133%                                 85
                                                                                   100
                           8 kV                100%                                 25
                                                                                    25
                           8 kV                133%                                 35
                                                                                    45
                           15 kV               100%                                 55
                                                                                    65
                           15 kV               133%                                 80
                                                                                    100
                           25 kV               100%                                100

                           25 kV               133%                           applicable ICEA/NEMA

                           28 kV               100%

                           35 kV               100%

                           5 kV                100%

                           5 kV                133%

                           8 kV                100%

                           8 kV                133%

                           15 kV               100%

                           15 kV               133%

                           25 kV               100%

                           25 kV               133%

                           35 kV               100% -~

                                  NEMA Table 10.6

                           Standard 141-1993 Table 12-9 and by factoring the

                                  Standards .

NOTE: AEIC CS5 and CS6, and ANSI/IEEE Standard 400 do not differentiate cables based upon

insulation thickness and, consequently, list differing test voltages .

Insure that the maximum test voltage does not exceed the voltage limits for potheads and terminators
specified in IEEE Std. 48 (IEEE Standard Test Procedures and Requirements for High-Voltage AC Cable
Terminations) or for molded rubber terminations specified in IEEE Std. 386 (IEEE Standard for
Separable Insulated Connector Systems for Power Distribution systems Above 600 V), or manufacturer's
published data.

Reprinted from NETA's Acceptance Testing Specifications, copyright 1999 . Courtesy of the
International Electrical Testing Association. All rights reserved .

3-10


---

                   TM 5-694

        CHAPTER 4
MAIN POWER SYSTEM

4-1 . Description of main power system

The following is a sample main power system with associated one-line and wiring diagrams for use as a
guide for implementing the test procedures described in the preceding chapters of this manual. The major
equipment in this main power system includes 34 .5 kV circuit switchers, 15,000 kVA oil filled
transformers, and 13 .8 kV metal clad switchgear including relays and controls . The equipment,
accessories, interconnections, ratings, and cabling are shown in figures 4-1 through 4-7. Figure 4-1
diagrams the main power system single line on page 4-7. Figure 4-2 diagrams the main power system
control cable block on page 4-8. Figure 4-3 diagrams the main power system circuit switcher on page 4-
9. Figure 4-4 diagrams the main power system switchgear load breaker on page 4-10. Figure 4-5
diagrams the main power system switchgear incoming breaker on page 4-11 . Figure 4-6 diagrams the
main power system circuit switcher wiring diagram on page 4-12 . Figure 4-7 diagrams the main power
system incoming breaker wiring on page 4-13 .

  a. Switches . The 34.5 kV Circuit Switches are outdoor vertical break, shunt trip with full momentary

current capability and limited fault current interrupting for applications feeding power transformers . Each
switch contains a high speed high torque power operator, interrupting units, disconnects, and post
insulators. The operator receives a trip or open signal from relays or a control switch, trips the
interrupter, and then opens the disconnect. If too much shunt current is available the relaying scheme will
block the switch from opening until the current decreases to an acceptable level. Each circuit switcher
has a 125 Vdc control circuit for control, relaying, and operator power. The circuit switcher is intended to
operate on transformer overload, transformer secondary faults, transformer through faults not cleared by
down stream switchgear breakers, and low value high resistance transformer faults. The 12/15 JAVA
power transformers are outdoor oil filled with radiators and fans for cooling, temperature and fault
 indicating relays, bushing mounted current transformers, no load secondary tap changer, and a control and
 alarm panel. The control and alarm panel requires a 120/208V, three phase power source for the controls,
 cabinet heater, and alarms . The 13 .8 kV switchgear is indoor, metal clad with individual spring operated
 vacuum circuit breakers and controls.

   b. Breakers . The switchgear line-up contains two incoming, one tie, and eight load breakers . Each breaker
 has a relay/control compartmentcontaining a control switch, indicating lights, relays, control wiring, and terminal
 blocks . The breakers have electrical and mechanical interlocks to prevent inadvertent operation, open/close
 springs, spring charging motors, position switches, and close and test positions. An auxiliary compartment in the
 switchgear is used to house the circuit switchers' control, indication, relays, and remote alarms; and the
 transformer remote alarms . Forcontrol, each circuit switcher and switchgear breaker has a control switch,
 indicating lights and relays. Each circuit switcher trip circuit contains overcurrent, differential current,
 transformer overload lockout, and transformer sudden pressure relays . The switchgear and load breakers have
 overcurrent relays . The tie breakerhas no relaying, and is intended to be closed to the switchgear bus together
 when Atransformer is out of service. It is interlocked to open or block closure ifboth of the incoming breakers
 are closed. There are potential transformers (FTs) on both sides ofthe switchgear and load circuit breakers. They
 are connected to undervoltage relays and sync check relays. The switchgear requires a 125 Vdc control and relay
 feed and 120 V single phase feed for space heaters.


---

TM 5-694

4-2. Operation of main power system

The operating modes for the main power system are as follows. These are some of the steps that would be
included in a systems operation document (SOD).

  a. Normal condition. Both circuit switchers closed, both transformers energized, both switchgear

breakers closed, tie breaker open, and load breakers closed .

  b. Transformerproblem. Associated circuit switcher and switchgear breaker open automatically, other

circuit breaker and switchgear breaker remain closed, and tie breaker closes automatically into dead bus.

  c. Transformer maintenance. Transformerto be maintained selected, tie breaker closed into live bus and

incoming breaker opened for transformer to be maintained, and circuit switcher for transformerto be maintained
opened

  d. Return to normal. Circuit switcher for deenergized transformer closed and switchgear breaker closed to

live bus and tie breaker opened .

NOTE: Automatic closing of the tie breaker during protective relay functions is a dead bus transfer. Manually
closing oftie breaker or closing of incoming breaker with tie breaker closed will parallel both transformers and
sync check relays will not permit breaker closing ifthe busses are not synchronized .

4-3. Commissioning test plan for main power system

A system verification and functional performance test should be performed on the main power system .
These tests will include installation inspections, individual component testing, verification and continuity
testing on wiring, control and interlock function checks, equipment energization, system operating
measurements, and functional tests.

44. Installation inspections and component testing of main power system

 As indicated in more detail in chapter 3, the installation ofthe main components (i.e. circuit switchers,
 transformers, and 13.8 kV switchgear) will be inspected for the following. These checks can be considered part
 of the pre-checks or the functional performance tests (FPTs).

   a Circuit switcher. Verification ofnameplate, sizing, and settings against drawings, completeness of

 assembly, loose parts and insulation damage, alignment and operation including limit switches and interlocks,
 insulation resistance test on each pole, interrupter time travel analysis and proper grounding. Figure 4-8 on page
 4-14 shows a sample of a completed DA Form 7463-R for a circuit switcher.

   b. Oil-filled transformer. Verification ofnameplate, size and settings against drawings, completeness of

 assembly, loose parts and insulator damage, seals and oil levels, auxiliary device operation and settings for
 radiators, fans, cooling, alarms, gauges, tap changer, etc., proper grounding, insulating liquid dielectric, acid
 neutralization, specific gravity, quality, color, etc., insulation resistance phase-to-phase, phase-to-ground, current
 transformers, turns ratio -highto-low windings at all taps, current transformers at all taps and impedance and
 polarity on current transformers. Figure 4-9 shows a sample ofa completed DA Form 7464-R for a transformer.

    c. Metal cladswitchgear: Verification of nameplate, sizing, and settings against drawings, completeness of
 assembly, loose parts and insulation damage, breakeralignment and operation (leave open) including limit
  switches and interlocks, bus insulation resistance (ifnot previously energized), relay calibration and settings
  including current transformer primary injection, insulator damage, proper grounding and current/potential

  4-2


---

                                                                TM 5-694

transformer insulation resistance, turns ratio, and polarity. Figure 410 on page 416 shows a sample ofa
completed DA Form 7565-R for the switchgear.

  d. Cabling. Proper use, voltage, labeling, and connections using drawings, tightness and neatness of
terminations, and power cable insulation resistance (phase-to-phase and phase-to-ground) . Figure 411 on page
417 shows a sample ofa completed DA Form 7466-R for power cables .

  e. Visual andelectrical wiring inspections. The termination of each cable, shown on the cable block and
wiring diagrams, should be checked to ensure each conductor matches the wiring and schematic diagrams. This
is performed by yellowing each connection from the schematic to the wiring diagram; visually inspecting each
connection for cable number, wire number/color, and terminal; and checking point-to-point continuity or "ringing
out" each wire from end-to-end including grounds. For example, Cable CIS from Circuit Switcher I to the
Switchgear Control Panel should be checked to verify schematic diagrams (figure 46).

Equipment                                         Terminal No.
Circuit Switcher                                          2
Switchgear Control Panel                                  1

As this is done, the wire on each drawing should be colored orhighlighted to show its termination has been
checked. This process should be completed for all field wiring as a minimum and internal wiring ifnot
previously performed at the factory.

45. Energizing and test of the main power system

The following are the steps to energize and test the main power system . These are some of the steps that
would be included in a functional performance test (FPT).

  a Initial energkation. The control circuits for each component shall be sequentially energized from the
circuit switcher down to the switchgear load breakers with the utility fuses removed. The control and interlock
functions for each circuit shall be verified by opening or closing the control switches, protective and lockoutrelay
contacts, temperature switches, etc. with both circuit switches closed, all switchgear circuit breakers closed, and
the switchgear tie breakers open. For example, on a circuit Switcher the functions as shown on table 41 should
be performed and checked. Verify operation oftransformercircuits as in (1) and (2) below.

Table 4-1. Circuit Switcherfunctional checklist

Function                        Action to Check
1) Energize Close/Trip Circuit  Green Light On
                                Red Light Off
2) Close Control Switch         Switcher Open
3) Trip Control Switch          Verify 86C/86I Normal
4) Reclose Circuit Switcher     Red Light On
                                Green Light Off
                                Switcher Closed
                                Green Light On
                                Red Light Off
                                Switcher Closed
                                Red Light On
                                Green Light Off
                                Switcher Closed

                                                                                                            4-3


---

TM 5-694

          Table 4-1 . Circuit switches functional checklist (continued)

          5) Trip 86C                 Green Light On

          6) Reset 86C                Red Light Off
          7) Close Control Switch     Switches Open
          8) Trip 861
                                      86C Tripped
          9) Reset 861                Switches Won't Reclose using Control Switch
          10) Close Circuit Switches  Green Light On

                                      Red Light Off

                                      Switches Open
                                      Red Light On
                                      Green Light Off
                                      Switches Closed

                                      Green Light On

                                      Red Light Off
                                      Switches Open

                                      86C Tripped
                                      Switches Won't Reclose using Control Switch
                                      Green Light On
                                      Red Light Off
                                      Switches Open

                                      Red Light On

                                      Green Light Off

                                      Switches Closed

       (1) Transformer trip. Verify circuit switchers and incoming breakers closed and tie breaker open .
Simulate transformer trip by operating Transformer 87 relay. Verify 86's trip; and then associated circuit
switches and incoming breaker opens, and tie breaker closes transfer. Verify tie breaker transfer is "dead"
bus by measuring continuity from high side of incoming breaker to unaffected bus. Reclose 86, circuit
switches, and incoming breaker. Open tie breaker. Repeat above process for other transformer.

       (2) Transformer maintenance. Verify circuit switchers and incoming breakers closed and tie
breaker open. Choose transformer to be removed from service. Close tie breaker. Open circuit switches
and incoming breaker for transformer to be maintained. Verify tie breaker transfer is "live" bus by
measuring. Reclose circuit switches and incoming breaker. Open tie breaker. Verify tie breaker transfer
is "live" bus. Repeat above process for other transformer.

   b. Energkation ofmainpowersystem . Individual components of the system shall be sequentially energized
from the circuit switches through the switchgear load breaker with the utility fuses installed as follows:

        (1) Circuit Switches 1 & 2. Verify main switchgear breaker open . Verify incoming voltage and
phasing. Close circuit switches. Measure voltage on secondary oftransformer. Compare voltage and
phasing on both transformer secondaries.

        (2) 13.8 kYswitchgear . Verify tie breaker and load breakers open . Close incoming breakers .
 Measure voltage on switchgear bus. Compare voltage and phasing across tie breaker, close and open tie
 breaker. Close load breakers one at a time. Measure voltage and current after closing each load breaker.

4-4


---

                                                                           TM 5-694

       (3) Transformer trip test. Verify system energized with both circuit switchers closed, switchgear
incoming and load breakers closed, and tie breaker open. Notify plant of impending transfer. Simulate
transformer trip by operating 50/51 relay. Verify 86C trips and then associated circuit switcher and
incoming breaker open and tie breaker closes . Measure voltage and current on switchgear buses and
verify "dead" bus transfer oftie breaker. Reclose 86C circuit switcher, and incoming breaker. Open tie
breaker. Verify tie breaker transfer is "live" bus by measuring bus voltages and current. Repeat above
process for other transformer.

      '(4) Transformer maintenance test. Verify system energized with both circuit switchers closed,
switchgear incoming and load breakers closed, and tie breaker opened . Notify plant of impending
transfer. Choose transformer to be removed from service. Close tie breaker. Open circuit switcher and
incoming breaker for transformer to be maintained . Verify tie breaker transfer is "live" bus by measuring
voltage and current on switchgear buses. Reclose circuit switcher and incoming breaker. Open tie
breaker. Verify tie breaker transfer is "live" bus. Repeat above process for other transformer.

       (S) Checklists. The acceptance testing is complete when all test are performed satisfactorily and
checklists for system components are complete . Figure 4-12 shows a sample of a completed DA Form
7467-R.

4-6. Possible failures and corrective actions of the main power system

Table 4-2 lists general problems that may arise during the testing ofthe equipment and systems along
with possible troubleshooting techniques . For all problems, consult the equipment and component
manuals for troubleshooting directions, check fuses/lights/breakers/etc . for continuity, check equipment
calibration and settings, and look for faulty equipment or connections.

Table 4-2. Possiblefailures and corrective actions ofthe mainpower system

Circuit Switcher  Areas to Check
Deviceswill not
close/trip        Mechanical alignment/Limit Switches
                  Interlocks
Devices trip      Relay and protective device settings and operation
inadvertently     Check for mis-wired circuits
                  Control circuit
                  Relay and protective device settings and operation
                  Check for mis-wired circuits

                  Control circuit
                  System overload or short
                  Ground on cable system


---

TM 5-694

Table 4-2. Possiblefailures and corrective actions of the main power system (continued)

Breaker                 Areas to Check
Devices will not        Mechanical alignmentIL mit Switches
close/trip              Interlocks
                        Relay and protective device settings and operation
Devices trip            Check for mis-wired circuits
inadvertently           Control circuit
                        Relay and protective device settings and operation
                        Check for mis-wired circuits
                        Control circuit
                        System overload or short
                        Ground on cable system

Transformer             Areas to Check
Transformer trips
                        System overload
Transformer overheats   Cooling system
                        Transformer internal short or bushing failure
                        Transformer relay settings and operation

                        Check for mis-wired circuits

                        Transformer oil

                        System overload
                        Cooling system

Main Power System       Areas to Check
Devices will not close  Mechanical alignment/Limit Switches
                        Interlocks
Inadvertent trips       Check for mis-wired circuits
                        Control circuit
                        System overload
                        Cable shorts or grounds
                        Equipment shorts or grounds
                        Transformer cooling
                        Check for mis-wired circuits
                        Relay and protective device settings


---

' .. .. .. . ......

                     m              . . . . . . . . . . . . .-

                     1200A
                     --- . . . . .
                     wc

                                                                ~~~) = Synch . Check ROW  lnstamWeous overcurrent Relay
                                                                Q= mdonwMVe Relay         owcurnioRetay
                                                                                          Sudden Pressure Relay
                                                                                          Lockout Relay
                                                                                          mmxnndmnvllay/

                                                                                                  nMUREw
                                                                                          MAIN POWER SYSTEM


---

120 VDC Distribution    CABLE   120 VDC Distribution
                        DP1C 1           Panel
      Panel
                                               CABLE
 Circuit Switcher                             DP1 CS2
   'No.:1 {C1}
                                           Circuit S.w2itcher
                 CABLE
                 DP2T1                           No

                        CABLE
                        DP2T2

    Stepdown            CABLE      Stepdown
Transformer No. 1        TIS2
                                TransformerNo. 2
  vCABLE
                 1S1    CABLE   CABLE
CABLE'                  T2S2     T2S1
 CS1S
                        13.8 kV SWtchgear         CABLE
      UABLE                                        CS2S
       DP2S              and RelayPanel
                               (S)         CABLE
                                           DP1S

                                                                          FIGURE 4-2
                                                                  MAIN POWER SYSTEM

                                                                      CONTROL CABLE
                                                                      BLOCK DIAGRAM
Figure 4-2. Main power system control cable blockdiagram


---

    O  rc
       Tn
aH  C
         o
       . ~'
~g~y3

Figure 4-3. Main power system functional diagram circuit switcher (typicalfor 2)


---

TM 5-694

                  w

          TaaSl=p~~'m
                     `o

           ly4~ v

          2Off. ~ It

        Figure 4-4. Main power system functional diagram switchgear load breaker (typicalfor 8)

4-10


---

                                                                                                                               w

                                                                                                                                                                                            ge ~ LL
                                                                                                                                                                                        ~pC

                                                                                                                        1e9y}oA~ZM

                                                                                                                                                                                                0

                                                                                                                        ~u.oLoF~ G
                                                                                                                           zv

                                                                        v

Figure 4-S. Mainpower system functional diagram switchgear incoming breaker (typicalfor 3)


---

    7V
.. . . . . . . .. . . . ... .1. . . . . . . . . . . . . . . . . . . . . .

                                HN
                                U
                             Va

                                       W                                            . Q~.

~ .O .V                                                                    r N M t(f m

 a

                Figure 4-6. Main power system circuit switcher wiring diagram (typicalfor 2)
4-12


---

                                         --- . . . . . . . . . . . . .. . . . . . . . . . . . . . . . .

125 VAC ^-r-~- - " -~^ ~-^ - ^^ ~        ~
                                         ,  umake,
Panel CircLdt

                                   TIS2     . ..... .. - .... ... .. .. .... .... .

                                                                                                                           FIGURE 4-7
                                                                                                                  MAIN POWER SYSTEM
                                                                                                     INCOMING BREAKER WIRING DIAGRAM


---

      TM 5-694

                                                        CIRCUIT SWITCHER INSPECTION CHECKLIST

                                                       Foruse of this form see TM 5694 ; the proponent agency is COE.

1 . PLANTIBUILDING                                                            SECTION A -CUSTOMER DATA                      3.JO8 NUMBER

Bldg 19291                                             2. LOCATION                                                          02-117

4. EQUIPMENT                                           Fort Tank                                                            6.0 ATE /YYYYMMDDl
                                                                                                                                                     20020823
Switcher                                               5. CIRCUIT DESIGNATION
                                                                                                                            8. TESTED BY
7. TEST ED UIPMENT TY PEIBRANO ANO CALIBRA TION 0A,TE  P1
                                                                                                                            John Smith
Sparls test set

9. MANUFACTURER                                10. STYLESIS .O .       SECTION B -EDUIPMENT DATA                                           12 . CURRENT RATING

S&C                                            air/5673                                            11 . VOLTAGERATING                      2000A

13 . INTERRUPTING RATING                                                                35kV

500M V A                                                                                           14. BUS BRACING

                                                                                        500M V A

                                               SECTION C -VISUAL AND ELECTRICALIMECHANICALINSPECTION

15 .                                                   COND'           NOTES                                           CHECKPOINT          COND'                  NOTES
                                   CHECKPOINT

EX TERIO R OF EQ UIPMENT                               A                      EQUIPMENT ID ENTIFICA TIO N                                  A

COMPLETENESS OFASSEMBLY                                     A                 BRACING A

ELECTRIC ALIMECHANICALINTERLOCKS                            A                 PROPER PHASE CONNECTION AND COLORCODE                        A

PROPER GROUNDING                                            A                 HAZARDOUSLOCATION                                            A

ALIGNMENT AND ROTATION LIMITS                               A                 CONTACT RESISTANCE                                           A

TIGHTNESS OF BOLTED CONNECTIONS                             A                 ANCHORAGE                                                    A

PROPER LUBRICATION                                          A                 REFERENCEDRAWINGS                                            A

INTERRUPTER TIME TRAVEL                                     A                 CO NTRO L CIRCU IT OPERATION                                 A

MANUALOPERATION                                             A                 ENERGIZED OPERATION                                                        A

                                                                       SECTION 0-ELECTRICAL TESTS                                                     B-C

16 .  INSULATION RESISTANCE                            A-GRO                  B-GRD       C-GRO                                    A-B     85 me ohm                       C-A

                  @5k v                        50 me ohm               75 me ohm     60 me ohm 80 me ohm                                      CURRENT"          80 me ohm
                                                                                                                                                       C
17 .                                                                                 VOLTAGEANDCURRENTMEASUREMENTS
                                                                                                                                                       C
                     MEASUREMENT DESCRIPTION
                                                                                                                                                        C
                                                                       VOLTAGE"'

                    NA                                 A-N        B-N  C-N    A-B    B-C                               C-A  A           B                      N  G

                    NA                                 A-N        B-N  C-N    A-B    B-C                               C-A  A           B                      N  G

                    NA                                 A-N        B-N  C-N    A-B    B-C                               C-A  A           B                      N  'G

1B . NOTES:

1 . Insulation resistance test performed on de-energized bus .
2 . Bolts not torqued properly . Situation corrected .

'CON01TIO N : A-ACCEPTABLE; R -NEEDS REPAIR, REPLACEMENT OR ADJUSTMENT; C-CORRECTED ; NA-NOT A PPLICABLE                                                          USAPA V 1 .00
''NOTEVALUEAND PHASING

DA FORM 74B3-R,

                                               Figure 4-8. Sample ofcompleted DA Form 7463-R

      4- 14


---

                                                                                                       TM 5-694

                                      TRANSFORMER INSPECTION CHECKLIST
                             For use of this form see TM 5-694; the proponent agency is CIE .

                                        SECTION A - CUSTOMER DATA

1 . PLANTIBUILDING               2 . LOCATION                                      3 . JOB NUMBER

Bldg 354                         Fort Tank                                         02-118

4 . EQUIPMENT                    5 . CIRCUIT DESIGNATION                           6 . DATE trryrmmDDj
                                                                                                         20020823
XFMR-T1                          CKT-A

7 . TEST EQUIPMENT TYPEIBRAND AND CALIBRATION DATE                                 B . TESTED BY

AEMC Megger, DTR, Biddle DLRO, Power Factor Test Set                               John Smith

                                        SECTION B - EQUIPMENT DATA

9 . MANUFACTURER             10 . STYLESIS .O .               11 . VOLTAGE RATING                 12 . CURRENT RATING

Cooper                       Oil-filled                       34500: 12470Yt72OO                  25MVA

13 . WET BULB TEMPERATURE    14 . DRY BULB TEMPERATURE        15 . ENCLOSURE TYPE                 16 . FREQUENCY

65 F                         85 F                                                                 60hz

                             SECTION C - VISUAL AND ELECTRICALIMECHANICAL INSPECTION

17 . CHECK POINT                 C0NO'           NOTES                   CHECK POINT              COND'            NOTES

EXTERIOR OF EQUIPMENT            A                            PROPER PHASE CONNECTION AND COLOR        A

                                                              CODE

COMPLETENESS OF ASSEMBLY         A                            HAZARDOUS LOCATION                       A

PROPER GROUNDING                 A                            WORKING CLEARANCE                        A

CONDITION OF INSULATION          A                            ANCHORAGE                                A

TIGHTNESS OF BOLTED CONNECTIONS  A                            REFERENCE DRAWINGS                       A
SEALS AND OIL LEVELS                                                                                   A
WINDING CONFIGURATION            R               3.           TURNS RATIO MEASUREMENTS                 A

                                 A                            AUXILIARY DEVICE OPERATION

                                        SECTION D -ELECTRICAL TESTS

18 .  INSULATION RESISTANCE      A-GRD               B-GRD          C-GRD          A-B            B-C              C-A

      0 5kV                      70 megohm 70 megohm 85 megohm

      POLARIZATION INDEX         2 .5                   2 .7        2 .7

      TURNS RATIO TEST

      POW ER FACTOR              0.5                    0 .5        0 .45

                   PROPER VOLTAGE
19 . NOTES :

1 . PERFORM GROUND RESISTANCE TESTS PRIOR TO ENERGIZING EQUIPMENT.
2 . GROUND RESISTANCE TESTS MUST BE PERFORMED IN DRY CONDITIONS AND SHALL BE PERFORMED
48 HOURS AFTER RAINFALL .
3 . REPLACE GASKET .

'CONDITION : A- ACCEPTABLE ; R- NEEDS REPAIR, REPLACEMENT OR ADJUSTMENT ; C-CORRECTED ; NA- NOT APPLICABLE         USA PA V1 .00
DA FORM 7464-R,

                                 Figure 4-9. Sample ofcompleted DA Form 7464-R
                                                                                                                                 4-15


---

                                           SWITCHGEAR INSPECTION CHECKLIST
                                 For use of this form see TM 5694 ; the proponent agency is C O E .

                                              SECTION A - CUSTOMER DATA

1 . PLANT/BUILDING                 2 . LOCATION                                   3 . JOB NUMBER                                     I
Bldg 314                           Fort Tank
                                                                                  02-119

4 . CIRCUIT DESIGNATION     5 . CIRCUIT FED FROM             6 . CIRCUIT FED TO                         7 . DATE lrrrrmmDD/
F5                          Main bus                         F2                                                       20020823

8 . TEST EQUIPMENT TYPEIBRAND AND CALIBRATION DATE           9 . ENCLOSURE TYPE                      10 . TESTED BY
AVO 414/ 5 Aug 2002                                          Air                                     John Smith

                                              SECTION B - EQUIPMENT DATA

11 . MANUFACTURER                 12 . STYLESIS .O .         13 . VOLTAGE RATING                        14 . CURRENT RATING
Siemens                                                                                                 2000A
                                                             600V
15 . INTERRUPTING RATING
50 kA                                                        16 . BUS BRACING
                                                             50 MVA

                                 SECTION C - VISUAL AND ELECTRICALIMECHANICAL INSPECTION

          CHECK POINT              C0 N0              NOTES             CHECK POINT                        C0ND'                NOTES

EXTERIOR OF EQUIPMENT              A                         EQUIPMENT IDENTIFICATION                                A

REFERENCE DRAWINGS                 A                         BRACING                                                 A

ELEC TRICALI ANOH INTfflIO CDKRSAW OUT A                     COOS R PHASE CONNECTION AND COLOR A

BUS AND SUPPORT INSULATORS         A                         HAZARDOUS LOCATION                                      A

PROPER LUBRICATION                 A                         W ORKING CLEARANCE                                      A

CLEAN SWITCHGEAR                   A                         ANCHORAGE                                               A

CHECK MANUAL OPERATION OF CIRCUIT  A                         ALL FILTERS AND VENTS CLEAR                             A
BREAKERS AND RELAYS

TEST RELAYS (ACCORDING TO ELEC .                             CHECK PROPER EQUIPMENT GROUNDING
STUDY RECOMMENDATIONS)             A                         TO GROUNDING BUS                                        A

CHECK INSTRUMENT AND RELAY         A                         SWITCHES FOR FREEDOM OF MOVEMENT                        A
COVERS

CHECK CIRCUIT BREAKER INSULATING   A                         CHECK INCOMING LINE CONNECTIONS TO                      A
PARTS                                                        MAIN BUS

CHECK CIRCUIT BREAKER CONTACT      A                         VERIFY PROPER SIZE BflEAKERSIFUSES                      A
SURFACES

18 . VERIFY LIFT OR BUILT WINCH FOR HANDLING  HEAVY   PARTS  19 . VERIFY CORRECT OPERATION OF INDICATING LIGHTS, METERS,
                                                             GAUGES, ETC .

20 . VERIFY BOLTED BUS CONNECTIONS TO MANUFACTURER           21 . VERIFY SPACE HEATER IS PROVIDED AND OPERATIONAL
RECOMMENDATIONS

                                              SECTION D -ELECTRICAL TESTS

22 . INSULATION RESISTANCE         A-GRD              B-GRD            C-GRD         A-B                B-C                     C-A
                       0 1000 V
                                                             VOLTAGE AND CURRENT MEASUREMENTS
23 . MEASUREMENT DESCRIPTION
                                                      VOLTAGE"                                          CURRENT"
Main Secondary
M1                                 A-N B-N C-N A-B B-C C-A                        A                  B  C               N            G

                                   277 277 278 482 479 480 250 240 230                                                  15           1 .5

                                   A-N B-N C-N A-B B-C C-A                        A                  B  C               N            G

                                   A-N B-N C-N A-B B-C C-A                        A                  8  C               N            G

24 . NOTES
1 . VOLTAGE MEASUREMENTS TO BE MADE AFTER UTILITY SOURCE IS CONNECTED TO INCOMING BREAKER
WITH THE UTILITY BREAKER OPEN .
2. INSULATION RESISTANCE TESTS MUST BE PERFORMED PRIOR TO ENERGIZING EQUIPMENT.

'CONDITION : A-ACCEPTABLE ; R- NEEDS REPAIR, REPLACEMENT OR ADJUSTMENT ; C-CORRECTED : NA- NOT APPLICABLE                       U$APA V1 .00
"NOTE VALUE AND PHASING
D A FORM 7465-R,

                                              Figure 4-10. Sample ofcompleted DA Form 7465-R

        4- 1 6


---

                                                                                                    TM 5-694

                                        POWER CABLE INSPECTION CHECKLIST
                              For use of this form see TM 5-694; the proponent agency is COE.

1 . PLANT/BUILDING                           SECTION A - CUSTOMER DATA         3 . JOB NUMBER
Bldg M-u                                                                       02-120
                                    2 . LOCATION
                                    Fort Tank                                  6. DATE (YYYYMMDD)
                                                                                                     20020823
4 . EQUIPMENT                       5. CIRCUIT DESIGNATION
Cable                               F1                                         8. TESTED BY
                                                                               John Smith
7. TEST EQUIPMENT TYPE/BRAND AND CALIBRATION DATE
AVO

                                           SECTION B - EQUIPMENT DATA

9. MANUFACTURER               10 . STYLES/S .O .         11 . VOLTAGE RATING                   12 . CURRENT RATING
Rome                          XLP                        15 kV                                 500 MCM
13 . WET BULB TEMPERATURE                                                                      16 . FREQUENCY
65 F                        114. DRY BULB TEMPERATURE    115 . ENCLOSURE TYPE                  60 hz
                             85 F
17 . CHECK POINT
                              SECTION C - VISUAL AND ELECTRICAL/MECHANICAL INSPECTION

                                    COND'         NOTES             CHECK POINT                COND'           NOTES

EXTERIOR OF CABLE RUN               A                    BRACING AND SUPPORTS                       A

PROPER GROUNDING AT TERMINAL        A                    CHECK PROPER SIZE OF CABLE                 A

LUGS TO BUS

REFERENCE EXISTING 1-LINE DIAGRAMS  A                    TIGHTNESS AND NEATNESS OF                  A

                                                         TERMINATIONS

PROPER LUBRICATION                  A                    ANCHORAGE                                  A

CHECK GROUNDING AT SPLICE JOINTS    A                    CHECK PROPER SIZE TERMINAL LUGS AND        A

                                                         MATERIAL

CHECK CABLE PHASE COLOR CODE        A                    CHECK CABLE PHASE COORDINATION             A

SHIELD CONTINUITY                   R              2.    CABLE IDENTIFICATION

                                           SECTION D - ELECTRICAL TESTS

18 . INSULATION RESISTANCE          A-GRD              B-GRD  C-GRD            A-B             B-C             C-A

APPLIED VOLTAGE 15 Kv               20 megohm 30 megohm 35 megohm

19 . NOTES

1 . PERFORM HIGH POTENTIAL TESTS IN ACCORDANCE WITH SPECIFIED REQUIREMENTS OR
MANUFACTURER(S) RECOMMENDATIONS .
2 . GROUND SHIELDS WERE NOT TERMINATED PROPERLY .

`CONDITION : A= ACCEPTABLE ; R-NEEDS REPAIR . REPLACEMENT OR ADJUSTMENT; C -CORRECTED ; NA-NOT APPLICABLE      USAPA V1 .00
DA FORM 7466-R,

                                    Figure 4-11. Sample ofcompleted DA Form 7466-R
                                                                                                                                    4-17


---

TM 5-694

                                      MAIN POWER ENERGIZATION CHECKLIST
                               For use of this form see TM 5-694; the proponent agency is COE.

1 . PLANT/BUILDING                        SECTION A - CUSTOMER DATA           3. JOB NUMBER
Bldg 2584                         2. LOCATION                                 02-121
                                  Fort Tank
                                                                                               7 . DATE (YYYYMMDDj
4 . CIRCUIT DESIGNATION       5. CIRCUIT FED FROM   6. CIRCUIT FED TO                                        20020823
Main                          Utility               Output CB
                                                                              9. TESTED BY
8 . TEST EQUIPMENT TYPE/BRAND AND CALIBRATION DATE                            John Smith
Fluke 45/ 7 Aug 2002

10 . CHECK POINT              SECTION B - VISUAL AND ELECTRICAL/MECHANICAL INSPECTION

                                  COND'  NOTES                  CHECK POINT                           COND"            NOTES

COMPONENT INSPECTION/TESTING      A                 VERIFY SWITCHGEAR CONTROL FUNCTIONS               A
COMPLETED

WIRING VISUAL VERIFICATION        A                 CHECK FOR WORKING CLEARANCE                       A

VERIFY WIRING DIAGRAMS            A                 ENERGIZE AND TEST SYSTEM                          A

VERIFY CIRCUIT SWITCHER CONTROL   A                 TRANSFORMER TRANSFER CONTROL                      A
FUNCTIONS                                           FUNCTIONS

ENERGIZE AND TEST SYSTEM FOR ALL  A                 CHECK FOR UNUSUAL SOUNDS AFTER                    A
CONDITIONS
                                                    ENERGIZING

CHECK BUSHING OR TERMINALS        A                 CHECK ANCHORING OF TRANSFORMER                    A
CHECK FOR REMOVAL OF PAINT OR                       SWITCHGEAR AND SWITCHES ENCLOSURE
HEAVY DENTS
11 . MEASUREMENT DESCRIPTION                        CHECK FOR NORMAL/ABNORMAL                         A
Main Feed                         A                 SWITCHING OPERATION
F1
F2                                       SECTION C - ELECTRICAL TESTS

                                                    VOLTAGE AND CURRENT MEASUREMENTS

                                                    VOLTAGE"                                       CURRENT"

                                  A-N B-N C-N A-B B-C C-A                     A                 B  C         N         G

                                  7630 7630 7630 13kV 13kV 13kV 1200 1150 1200                               125       _5

                                  A-N B-N C-N A-B B-C C-A                     A                 B  C         N         G

                                                                                                                       0

                                  A-N B-N C-N A-B B-C C-A                     A                 B  C         N

F3 A-N B-N C-N A-B B-C C-A A B C N G

                                  A-N B-N C-N A-B B-C C-A                     A                 B  C         N         G

12 . NOTES

1 . Main circuit breaker did not open manually .
2 . Voltage/current measurements should be compared with switchgear meters .

'CONDITION : A-ACCEPTABLE ; R=NEEDS REPAIR, REPLACEMENT OR ADJUSTMENT; C=CORRECTED; NA=NOT APPLICABLE
"NOTE VALUE AND PHASING

DA FORM 7467-R,                                                                                                        USAPA V1 .00

                                  Figure 4-12. Sample of completed DA Form 7467-R

418


---

                                                                                                                    TM 5-694

                                                CHAPTER 5

                                   STANDBY POWER SYSTEM

5-1. Description of standby power system

The following is a sample standby power system with associated one-line and wiring diagrams for use as
a guide for implementing the test procedures described in the preceding chapters of this manual . A
system functional performance test shall be performed on the system . The system shall be operated
through all modes of systems operation including every interlock and conditional control logic, full load
and part load conditions, and simulation of all abnormal conditions where there is a specific condition
response . The system consists of the following equipment: 480V switchgear with utility, generator
switchgear, and 500 KW, 480V generators with control panel, and synchronizing/paralleling panel. The
equipment, accessories, interconnections, ratings, cabling, etc. are shown on figures 5-1 through 5-3 .
Figure 5-1 is the standby power system single line diagram on page 5-6. Figure 5-2 is the standby power
system block diagram on page 5-7. Figure 5-3 is a diagram of the standby power system wiring on page
5-8. The system provides normal and standby 480V power to the Facility . Under normal conditions
power is supplied from the utility through the Utility Power Center to the Facility Plant Load Center
which feeds the facility loads. When utility power is lost, the diesel generators will supply power through
the utility load center until normal power is restored . The 480V switchgear is metal enclosed and free
standing with drawout air power circuit breakers. The main utility, generator breakers, and the facility
load breaker are electrically/manually operated. The breakers have instantaneous short time and long
time settings. Breaker controls and indication are located on the door of each breaker compartment. The
main bus and incoming line have potential transformers connected to a synchronizing check (25) relay,
and an undervoltage (27) relay. The 25 relay will not allow the utility breaker to be closed unless the
switchgear bus and utility line are synchronized . The 27 relay opens the utility line breaker upon a loss of
power (i.e. undervoltage). The 500 kW, 480 V Generator sets include air cooled individual four cycle
diesel engines, three phase, four wire generators, and paralleling/synchronizing control systems. The
control system allows starting, stopping, loading, paralleling, and synchronizing of the generator to the
 system in the auto or manual mode while monitoring for equipment and system problems .

 5-2. Operation of standby power system

 The operating modes for the systems are as follows. These steps would be included in the systems
 operating document (SOD).

   a. Normal condition. Under normal conditions, the utility power supply is energized, the utility
 breaker is closed, the load center circuit breaker is closed and the circuit breakers for the individual
 generators are open. The generators are not operating.

   b. Loss ofpower. In the event of the loss ofutility power, the utility power center 27 relay sends an
 open signal to the utility breaker, the load center circuit breaker, and a start signal to the generators . The
 generators operate either automatically or manually depending on mode selected . The generators will
 follow each other for load sharing and phasing. In the automatic mode, when the first generator is at the
 proper operating voltage and frequency, the controls system sends a close signal to that generator's
 breaker. This generator becomes the lead machine. As the next generator picks up speed, the controls
 system compares the outputs from that generator's potential transformers and the bus potential
 transformer and when the voltage and frequency are synchronized, a close signal is sent from the
 synchronizer to the second generator breaker. This process is again repeated for the third generator.
 When all available generators are operating in parallel, a signal is sent to close the load center circuit


---

TM 5-694

breaker. In manual operation, the operator controls the diesel generator voltage and speed until the diesel
generator is synchronized with other generators and then manually closes the diesel generator breaker.
The operator repeats this process for each diesel generator set and then manually closes the load center
circuit breaker.

  c. Paralleling with utility. In the event that it is desired to parallel with the utility, the system will
operate in either the automatic or manual mode. In the auto mode, the generators will automatically
synchronize with the utility bus and their breakers will close. In auto/manual mode, the generators will
automatically synchronize with the utility bus but the breakers will be manually closed . In manual
operation, the operator controls the generator voltage and speed until the diesel generator is synchronized
with the bus voltage and then manually closes the diesel generator breaker. The operator repeats this
process for each diesel generator set.

  d. Restoration of utility. In the event of a loss of utility power the generators are running and
supplying the load . The utility breaker is open and all of the generator breakers are closed . When the
utility power is restored, the operator manually adjusts the generator speed and voltage very slowly until
the sync check relay on the utility load center is energized and illuminates the sync check light. The
operator manually closes the utility breaker and then manually trips the generator breakers at the
generators control panels . For systems that employ automatic synchronizing devices, it is possible for the
system to synchronize to the utility and transfer power from the generator sets to the utility without
operator intervention. The automatic synchronizing devices adjust the generator speed and voltage until
the generator is in sync with the utility. Then the utility breaker is automatically closed and the generator
breaker is automatically tripped.
5-3. Commissioning plan for standby power system
A system verification and functional performance test should be performed on the standby power system .
These tests will include installation inspections and individual component testing verification and ring out
of wiring, control and interlock function checks, equipment energization, and system operating
measurements and functional tests.
5-4. Installation inspections and component testing of standby power system
As indicated in chapter 3, the installation of main components (i.e. generator, switchgear, cabling) each
will be inspected or tested for the following. These checks can be considered part ofthe pre-checks or
functional performance tests (FPTs) .

   a. Generator. Completeness of assembly, proper nameplate data, loose parts and insulation damage,
generator air gap and free rotation, generator insulation resistance (phase-to-phase and phase-to-ground),
generator polarization index, grounding and proper voltage and phase connections. Figure 5-5 on page 5-
 10 and 11 shows a sample of a completed DA Form 7468-R for the generator inspection.

   b. Engine . Completeness of assembly, proper nameplate data, loose parts, and proper lubrication.
   c. Switchgear . Completeness of assembly, proper nameplate data, loose parts and insulation damage,
 breaker alignment and manual operation, proper relay settings, bus insulation resistance (phase-to-phase
 and phase-to-ground), grounding, proper voltage and phase connections and potential transformer and
 control fuse size and continuity. See Figure 4-10 on page 4-16 for sample checklist (DA Form 7465-R).


---

                                                                    TM 5-694

  d. Cabling. Proper use ofvoltage connections, tightness and neatness of terminations, power cable
insulation resistance (phase-to-phase and phase-to-ground) . See figure 4-11 (DA Form 7466-R) for
sample checklist.

  e. Visual and electrical wiring inspections . The termination of each cable, shown on the cable block
diagram, shall be checked to ensure each conductor matches the wiring and schematic diagram. This is
performed by yellowing each connection from the schematic to the wiring diagram; visually inspecting
each connection ; and checking the continuity or "ringing out" each wire end to end including grounds.
For example Cable PWRI from Diesel Generator 1 to the 480V Load Center should be checked to verify
that the "black" wire is terminated as follows which is shown on figure 5-3 :

      Equipment                                       Terminal No.

Diesel Generator 1                                          L1
480V Load Center                                            T1

As this is done, the wire on each drawing should be colored or highlighted to show its termination has
been checked. This process should be completed for all field wiring as a minimum and internal wiring if
not previously performed at the factory.

 f. Check controlfunctions. Individual circuits of each component shall be energized and checked for

proper function .

       (1) Generator . Energize control circuit with outgoing circuit breaker open and verify correct
operation of indicating lights, alarms, analog outputs and status outputs (list) . Locally start the generator
following the manufacturer's instructions for energizing and starting . Verify machine comes up to speed
and correct operation of indicating lights, alarms, analog outputs and status outputs. Measure output
voltage and frequency. Check remote stop and then remote start functions, external load set function,
wattNAR/voltage outputs, trip and circuit breaker interlocks and other no-load functions specifically
required by the generator instruction manual, if any. Energize and verify the operation of any accessory
circuits (i.e. generator heaters, fuel heaters, battery chargers).

       (2) 480V switchgear. Verify manual operation and local position indication ofthe main and
generator breakers with feeder cables disconnected or breakers racked out. Check the calibration of
undervoltage and sync relays in the main breaker control circuit per the manufacturer's instructions.
Energize the main breaker control circuit and close the breaker electronically using the control switch .
Verify proper operation of lights. Trip the main circuit breaker using the control switch and the
undervoltage relay. Verify the 27 relay is not engaged when the switchgear bus is deenergized.

5-5. Energizing and test of the standby power system

In order to energize and test the standby power systems the following procedures must be completed.

a. Initial set-up. Verify that generator circuit breakers are open and the generators are ready to start

  b. Bus test. Close 480V switchgear main and feeder breakers, check voltage on bus, and verify 27
relay is energized. Read voltage and current on bus.

  c. Manual sync/paralleling test. While 480 V switchgear bus is energized, place each generator in the
manual sync mode. Start the first generator and verify it comes up to speed and is ready to take load (a
load bank should be used). Manually adjust the speed and voltage of the first generator to be in sync with
the 480V switchgear, verify with phase meters that both are in sync and close the first generator's circuit

                                                                                                           5-3


---

TM 5-694

breaker. Verify that the generator picks up load . Measure voltage, current and frequency. Repeat this
process for the other two generators . As each generator is connected, verify load is shared equally
between the generators . Measure the voltage, current and frequency for each generator as it is connected.
Repeat the entire process starting with the second generator and then again starting with the third
generator to ensure that any one of the three generators can act as the starting generator.

  d. Auto sync/paralleling test. Repeat the previous step with each generator in the auto sync mode.
Each generator should automatically synchronize and close into the 480V switchgear bus.

  e. Utility trip load test. Verify that the 480V main breaker is closed and the switchgear is energized.
Measure voltage and current on the bus. Verify that the generator breakers are open and the
synchronizers are in the auto mode. Trip the 480V main breaker (remove normal power supply). This
causes the load center circuit breaker to open . Verify that all three generators start, synchronize, and pick
up load (load center circuit breaker closes). Add load until each generator is fully loaded. Run the
system for at least 4 hours powered only by the generators . Reconnect utility power and note if sync
check relay in the 480V utility breaker is picked up. If not, slowly adjust the speed and voltage ofthe
first generator until the relay is picked up indicating the generators are in sync with the utility. The speed
and voltage ofthe second and third generators should follow the first generator as it is adjusted. Verify
that the 480V switchgear bus voltage is in sync with the utility with a phase/voltage meter and close the
480V main breaker.

 f. Checklists . In addition to the component test forms discussed above, checklists for utility and

   generator circuit breaker inspection (see figure 5-6 for completed sample ofDA Form 7469-R) and
   back-up power system inspection (see figure 5-7 for completed sample DA Form 7570-R) must be
   satisfactorily completed.

   g. Modifiedsequence of operations . The standbypower system should be operated in commissioning
for all possible sequences of operations that a system will encounter.

5-6. Possible failures and corrective actions of standby power system

Table 5-1 lists general problems that may arise during the testing ofthe equipment and systems along
with possible troubleshooting techniques . For all problems, consult the equipment and component
manuals for troubleshooting directions, check fuses/lights/breakers/etc . for continuity, check equipment
calibration and settings, and look for faulty equipment or connections. Engine manufacturers typically
provide a fault tree for troubleshooting problems . Figure 5-4 is a typical fault tree . The fault tree tracks
the symptoms of the problems to identify the most probable cause. For example, if the engine will not
run and the starter turns the engine slowly then there is a problem with the battery. The causes ofthe
problem are either loose or dirty connections or a discharged battery.

          Table S-1. Possiblefailures and corrective actions ofstandbypower system

Engine Problem        Areas to Check
Will not start        Starter, battery, and connections; fuel system, level, pump, injectors, internal
                      engine (valves, tappets, pistons), ignition system (gas engines) control system
Poor                  interlocks/permissives, mis-wired circuits
Performance/Will not  Fuel system and cleanliness, injectors or carburetor, internal engine, control and
handle load           ignition system, system kW requirements


---

                        TM 5-694

Table S-1. Possiblefailures and corrective actions ofstandby power system (continued)

Generator Problem       Areas to Check
No Output               Check stator and rotor continuity, battery fluid level, diode pack, voltage regulator,
Voltage/Current         control system and interlocks, miss-wired circuits
Failure to synchronize  Mis-wired circuits, blown PT fuses, governor/regulator not calibrated properly
Failure to share load   Mis-wired circuits, governor/regulator not calibrated properly

480V'Switchgear         Areas to Check
Problem
Breakers won't close    Mechanical alignment/ interlocks, control circuit operation, relay and protective
                        device settings and operation, close coil and mechanism, mis-wired circuits .
Breakers won't trip     Check control voltage.
Breakers trip           Trip coil and mechanism, control circuitry operation, mis-wired circuits
inadvertently           Ground on bus or outgoing cable, relay and protective device settings and
                        operation, control circuitry operation, mis-wired circuits . Check control voltage.

Back-Up Power            Areas to Check
System Problem
                         Control circuitry operation, auto/manual sync system, generator control system,
Generator Breakers       mis-wired circuits. Check control voltage.
                        Engine fuel and control system, generator voltage regulator, generator control
will not close           system, auto/manual sync system, protective device settings, mis-wired circuits

Generator will not       Parallelingcontrol system, mis-wired circuits, interconnecting unit control wiring
pick up load or          governor control systems, voltage regulating systems
                         Generator sync system, breaker sync check relay, breaker control circuitry, mis-
stalls/trips             wired circuits . Verify "as builts" reflect actual circuit conditions .
Generators don't share
 load

Main switchgear

breaker won't re-close
 on diesel generator

 powered system


---

II  q 11  II                                         -J ~

                                                     B OO

                                                             In

Figure S-1. Standbypower system single line diagram


---

                                                                            FIGURE 5-2
                                                                STANDBY POWER SYSTEM

                                                                       BLOCK DIAGRAM

Figure S-2. Standbypower system block diagram

                                                                                          5-7


---

    UTL  PT   DGi       OG2       DG3

    T1
    T2

    T3   ABG  Tt T2 T3  Ti T2 T3  71 T2 T3  PWR3

N
w

a

a

b
0

m

 m

 i
oc

>z

                                                            FIGURE 63
                                                  STANDBY POWER SYSTEM

                                                       WIRING DIAGRAM


---

         WILL NOT RUN-                                      POOR PERFORMANCE                       OTHER FAULTS

                    L                                                                                                                                    -1

         STARTER TURNS                              UNEVEN BLACK BLUE OR WHITE EXCESSIVE OIL                     ENGINE               KNOCK OIL LEVEL LOW OIL
         ENGINE SLOWLY                             RUNNING EXHAUST EXHAUST SMOKE CONSUMPTION OVERHEATING                                    IN SUMP PRESSURE
                                                                    SCE                                                                       RISING             ,

                             I RUN AFTER STARTING
STARTER WILL - I ENGINE TURNS BUT WILL                                                                      GOVERNOR         HIGH
NOT TURN ENGINE           NOT START OR FAILS TO     FUEL                 CHECK AIR  TURBO                   I
                                                    INJECTION             CLEANER CHARGER                   SEE MANUAL PITCH HALF
                                                    EQUIPMENT ELEMENT                                                     ENGINE
                       r                                                                                                     SPEED          WATER
FAULTY              LOW FUELLEVER FUEL                                                                                       I,             IN OIL
STARTER  COMPRESSION NOT FULLY SHORTAGE                     CONTAIN- WATER IN BURNING OIL                   T;C           ROCKER
                                  OPEM                              MATED  CYLINDER OIL LEAKS SEALS                       CLEARANCE
                                                                    OR LOW (WHITE)
         O VALVES TAPS RING                                         GRADE           U,             INCORRECT                             i    OIL'
                                                                                    ~~ OIL                                            HEAVY APPEARS
                                                                    FUEL                                                                    EMULSI-
                                        CLEARANCE
                                                                                           011. PASSING                               I     FIED

         FUEL                  AIR IN     FAULTY                                           LIP CYLINDER               SEIZED BROKEN
         TAW                      FUEL    LIFT                                                  BORES OR              INJECTOR DELIVERY
         EkWTY                            PUMP                                                  DOWN VALVE            NEEDLE VALVE
                                                                                                   GUIDES                          SPRING
                    FUEL COCK FUEL FILTER           INJECTION MISFIRING                            I
                       CLOSED           ELEMENT     COMMENCING ON ONE                              LIGHT                  WORN SMALL
                                                                                                                          OR BIG END
                          I             BLOCKED     LATE                  CYLINDER                 LOAD                      BEARINGS
                     FUEL DuTtET                                           (BLUE)               OPERATION
      BATTERY RESTRICTED
                                                            1 11                                                                    -I -1
         INJECTOR LINKAGE STIFF FUEL INJECTOR OUT OF                      DIRTY OR EXHAUST OIL WATER                      I
                                                                                                                      CRACK IN LEAKING LEAKING
         OR INCORRECTLY SET PHASE OR CALIBRATION FAULTY INJECTOR                                                      CYLINDER INJECTOR             OIL
                                                                                                                      BLOCK TUBE              TEMP.
                                                                                                                      OR HEAD               STABILIZER
                 FUEL        AIR CLEANER           LOSS OF HIGH BACK PRESSURE
         INJECTION                CHOKED         COMPRESSION CHOKED SILENCER                                                 RUN CRACKED
                                                                                                                             ENGINE CYLINDER
                                                                                                                             WITH LINER
         INCORRECT FUEL INJECTOR                                                                                             ROCKER
         INJECT )            OUT OF PHASE FAULTY ] BLOWING CYLINDER                                                          COVERS
         TIMING              OR CALIBRATION VALVES          HEAD GASKET                                                      REMOVED
                                                                                                                             TO CHECK                    FUEL
                                                                                                                                                         IN OIL
         FAULTY INJECTOR                           FAULTY BORES                                                           FOR LEAKS

                                                                 (                              I           INSUFFICIENT    FAULTY          FAULTY       ONE
                                                            FAULTY 0.0 BYPASSING MSUFFICIENT                     WATER    LIFT PUMP
                                                    TEMPERATURETEM PERATURE AIR PASSING                                                  INJECTION CYLINDER
                                                            GAUGE STABILIZER        THROUGH                                   SEAL       EQUIPMENT NOT
                           LOOSE                                                    RADIATOR                                                             FIRING
        BATTERY          OR DIRTY
      DISCHARG D       CONNECTIONS
:INITIATION SWITCH
                                                                                             D          CK  HEAT~~T_ORER
MAIN     24V                                                                        CORE           SLAFAN      THERMOSTAT
                                                                                                   BELTS        NOT OPEN
CHARGER ALTERNATOR

                                        FAULTY WORN MAIN CHOKED RELIEF LEAKING PRESSURE DEFECTIVE LEAK FROM INSUFFICIENT CHOKED
                                        OIL PUMP R BIG END          OIL    VALVE JOINTS GAUGE PIPE PRESSURE MAIN OIL OIL IN SUMP OIL
                                                   BEARINGS FILTER STICKING                        PINCHED       GAUGE GALLERY                           STRAINER
                                                                           OR WORN              OR BENT                      G-RINGS                                NA

                                                                                                                                                                    A


---

TM 5-694

                                                   ENGINE GENERATOR SET INSPECTION CHECKLIST
                                                     For we of this form see TM 5.694; the proponent agency is COE.

1. PLANTIBUILOING                                                   SECTION A -CUSTOMER DATA                 3.JOB NUMBER

Bldg 1924                                          2. LOCATION                                               02-122

                                                   Fort Tank

4. EQU IPMENT                                      5. CIRCUIT DESIGNATION                                    6. DATE /YYYYMMooj    20020823
                                                                                                             B. TESTED BY
Genset                                             G1
                                                                                                             John Smith
7. TEST EQUIPMENT TYPEIBRAND AND CALIBRATION DATE

Biddle Insulation Tester/ 5 July 2002

                                                                  SECTIONS -EQUIPMENT DATA

9. MANUFACTURER                                10 . STYIESIS.O .                11 . VOLTAGERATING                              12. kW RATING

CAT                                            Diesel 3416                      4160                                           500kW

13 . CIRCUIT BREAKER SIZEIINTERRUPTING RATING                                   14 . WET BULB TEMPERATURE                 15 . DRY BULB TEMPERATURE

300A/ 50kA                                                                      65 F                                      85 F

                                               SECTION C "VISUALAND ELECTRICALIMECHANICALINSPECTION

16. CHECK POINT                                    CONO'          NOTES                             CHECK POINT                         cow          NOTES

EXTERIO R OF EQ UIPMENT                            A                            EQUIPMENT ID ENTIFICATION                               A

COMPLETENESS OFASSEMBLY                            A                            BRACING                                                 A

EQUIPMENT ROTATION                                 A                            PROPER PHASECONNECTIONS                                 A

CHECK OIL LEVEL                                    A                            REFERENCE DRAWINGS                                      A
CHECK FU EL LEVEL
                                                   A                            WORKING CLEARANCE

PROPER EQUIPMENT GROUNDING A ANCHORAGE A

CHECK METERSIGAUGES                                A                            ALL FILTERS AND VENTS CLEAR                             A

TIGHTNESS OF BOLTED CONNECTIONS                    A                            CHECK EQUIPMENTENVIRONMENTALCLASSIFICATION              A

VERIFY GOVERNOR AND REGULATOR                      A                            CHECK FOR PROVISIONS OF SPILL CONTAINER                 A

CHECK VIBRATION                                    A                            CONTROL SYSTEM                                          A

CHECK BATTERIES                                    A                            CHECK FUEL FILTER                                       A
CHECK RA 0IATO RFLUID
PROPER SYSTEM GROUND                               A                            CHECK ALA RM 111101CA TORS: PROPER COLOR FOR EACH       A
                                                                                FUNCTION

                                                   A

                                                                  SECTION D-ELECTRICALTESTS

17 . INSULATION RESISTANCE                         A-GRO                 B-GRD            CGGRD                      A-B           B-C               C-A

         @ 2500 v                                  10 megohm 12 megohm 14 megohm

                 POLARIZATION INDEX                2 .1                  2 .2                 2 .3
            RATIO - 10 MINUTEII MINUTE

               DC OVERPOTENTIAL TEST               notes 1 & 2
                      0V

18 . NOTES

1 . PERFORM 5 MEASUREMENTS AT ONE MINUTE INTERVALS .
2 . DC HIPOT MEASUREMENTS SHOULD BEGIN AT 20% OF MAXIMUM TEST VOLTAGE AND INCREASE IN
EQUAL INTERVALS.

           MAX DC TEST VOLTAGE = R (2 x NAMEPLATE RATING) x 1 .6
                                                                        WHERE R = .8 FOR DC TEST ON INSTALLATION
                                                                        WHERE R = .6 FOR DC TEST AFTER SERVICE

(TEST MEASUREMENTS SHOULD NOT EXCEED MANUFACTURER'S RECOMMENDATION)

DA FORM 7466-R, AUG 2002                                                                                                                             PAGE 1 OF 2

                                   Figure S-S. Sample of completedDA Form 7468-R (side])                                                                 USAPAY1.00

               5-10


---

                                                                                                              TM 5-694

                                                       SECTION D -ELECTRICAL TESTS fCendanedl

19 .                                                                    VOLTAGE AND CURRENT MEASUREMENTS
                     MEASU REMENT DESCRIPTION

                                                              VOLTAGE"                                     CURRENT"
                                                       II-ET A-N
                                                       B-N    C.N  A-B         C-A             A        B  C                      N  G

20 . LOAD TESTS AS A PERCENTAGEOFGENERATOR RATING

      NO LOAD                                  25 %    75 %             100%                            110% (PRIME ENGINE ONLY)

A-N   2400                                     2400    2395             2389

B-N'  -2400                                    2400    2395             2395

C-N   2400                                     2400    2392             2390

A-B   4160                                     4160    4158             4155

B-C   4160                                     4160    4157             4150

C-A   4160                                     4160    4158             4160

A     0                                        17 .5A  52A              70A

B     0                                        17A     49A              69A

C     0                                        17A     50A              68A

N     0                                        0 .5A   1 .4A            1 .5A

G     0                                        0 .3A   0 .4A            0 .5A

21 . NOTES

1 . VOLTAGE MEASUREMENT TO BE MADE AFTER GENERATOR IS STARTED AND CONNECTED TO LOAD (CAN
USE LOAD BANK).

2 . DURING COMMISSIONING OF GENERATOR SETS OR ANY EQUIPMENT, A REPRESENTATIVE OF THE
MANUFACTURING COMPANY OR SUPPLIER MUST BE PRESENT TO WITNESS AND/OR PERFORM THE TESTS.

3 . ENGINE GENERATOR TESTING IS A VERY INTENSIVE PROCESS AND REQUIRES A 10 TO 14 HOUR DAY
DEPENDING ON THE EQUIPMENT BEING COMMISSIONED . SUPPLIERIMANUFACTURER NORMALLY SUPPLY
GENERATOR TESTING LOAD REQUIREMENTS .

4 . VERIFY ALL SYSTEM CHECK POINTS DURING LOAD CHANGES AND RECORD PER SPECIFIED
REQUIREMENTS AND/OR EQUIPMENT MANUFACTURER .

5 . PERFORM AND RECORD ENGINE MANUFACTURER'S RECOMMENDED CHECKS AND INSPECTIONS .

 'CONDITIO N:A-ACCEPTABLE; R -NEEDS REPAIR, REPLACEMENT OR ADJUSTMENT; C- CORRECTED; NA-NOT APPLICABLE                                         PAGE20F2
 "NOTEVALUEAND PHASING                                                                                                                              USAPAY1 .00
DA FORM 71664, RII6 2001
                                                                                                                                     5-1 1
                                          Sample of completed DA Form 7468-R (side 2)


---

      TM 5-694

                                        UTILITY AND GENERATOR CIRCUIT BREAKER INSPECTION CHECKLIST
                                                         For use of this form see TM 5-694; the proponent agency is CO E.

1. PLANTIBUILDING                                                SECTION A -CUSTOMER DATA  3.J08 NUMBER                    20020823

Bldg 358                                         2. LOCATION                               02-123
                                                                                           6.DATElYYYYMMDl
4. EQUIPMENT                                     Fort Tank
CB1                                                                                        8. TESTED BY
                                                 5. CIRCUIT DESIGNATION
7. TEST EQUIPMENT AND CALIBRATION DATE                                                     John Smith
                                                 Feeder 1
AVO Tester/ 7 Mar 2002

9. MANUFACTURER                         10 . STYLESIS .O .  SECTION B -EQUIPMENT DATA                                      12. CURRENT RATING
                                                                                11 . VOLTAGE RATING
AVO                                                                                                                        2000A
                                                                           600V
13 . CIRCUITBREAKER SIZEAND INTERRUPTING RATING                                                                                              15 . FREQUENCY
                                                                                14 . EOUIPMENTCLASSIFICATION
200A/ 50kA                                                                                                                             160hz
                                                                           Air

                                                 SECTION C-VISUALAND ELECTRICALIMECHANICALINSPECTION

16 .                                             COND'      NOTES                          CHECKPOINT                           CONO'  NOTES
                         CHECKPOINT

EXTERIOR O FEQ UIPMENT                           A                 BRACING                                                      A

CO MPLETENESS0FASSEMBLY                          A                 PROPER PHASECONNECTIONS AND COLOR CODE                       A

EX ECTRICALIMECHA NICALIN TERLOCKS               A                 HAZARDOUSLOCATION                                            A

PROPER GROUNDING                                 A                 WORKING CLEARNACE                                            A

CONTACT RESISTANCE                               A                 ANCHORAGE                                                    A

AUXILIARY WIRING                                 A                 REFERENCE DRAWINGS                                           A

PROPERLUBERICA TION                              A                 RELAYS CHECK MANUAL OPERATION OFCIRCUIT BREAKER AND A

TIGHTNESS OF BOLTED CONNECTIONS                  A                 RELAYS TESTED (ACCORDING TO ELECTRICAL STUDY 'A
                                                                   RECOMMENDATIONS)

EQUIPMENT ID ENTIFICATION                        A

                                                            SECTION D -ELECTRICALTESTS

17 .        INSULATION RESISTANCE                A-GRD      B-GRD             C-GRD                           A-B          B-C         C-A

                  @ 1000 V                       10 megohm 12 megohm F12 megohm

18 . NOTES

1 . MANUFACTURER'S INSTALLATION TESTS/CHECKS SHOULD BE IMPLEMENTED .

*CONDITION :A-ACCEPTABLE;R-NEEDS REPAIR, REPLACEMENT OR ADJUSTMENT C- CORRECTED; NA-NOT APPLICABLE                                                           USAPA V 1 .00
"NOTEVALUEAND PHASING
DA FORM 7469-R, AUG 2002

                                              Figure S-6. Sample ofcompleted DA Form 7469-R

               5-12


---

                                                                                                                                    TM 5-694

                                         BACK-UP POWER SYSTEM INSPECTION CHECKLIST
                                            For use of this form see TM 5694;t he proponent agency is COE.

i . PLANTIBUILDING                                       SECTION A -CUSTOMER DATA                             3.J08 NUMBER

Bldg 311                                 2. LOCATION                                                          02-131

4. EQU IPMENT                            Fort Tank

Switchgear/ controls                     5. CIRCUIT DESIGNATION                                               6. DATE /YYYYMMDD/

7. TEST EQUIPMENT A NO CALIBRATION DATE  Main                                                                                       20020823

Fluke 45/ 7 Aug 2002                                                                                          8. TESTED BY

9. MANUFACTURER'                                                                                              John Smith

Siemens                                  10 . STYLESIS .O .      SECTION B- EQUIPMENT DATA                              12. CURRENTRATING
                                                                                     11 .VOLTAGE RATING
13 . EQUIPMENT CLASSIFICATION                                                                                           2000A
                                                                                5 kV
Outdoor
                                         14. FREQUENCY                  15 . WET BULB TEMPERATURE                       16. DRY BULB TEMPERATURE
17 . CHECKPOINT
                                         60hz                           65 F                                            85 F

                                         SECTION C -VISUALAND ELECTRICALIMECHANICALINSPECTION

                                         COND'                   NOTES                                   CHECKPOINT               COND'             NOTES

COMPONENTINSP ECTIONITESTING             A                              WIRING VISUAL VERIFICATION                                  A

ENERGIZEAND TEST SYSTEM                  A                              UTILITY TRIPIGENERATORBUILDING LOAD TEST                    A
INSTALLATION IISPECTIONITESTING
                                         A                              TIGHTNESS OF BOLTED CONNECTIONS                             A

GENERATOR CONTROLS AND FUNCTIONS         A                              CHECK FOR PROPER SIZE BREAKER                               A

WIRING CONTINUITY TESTING                A                              REFERENCE DRAWINGS                                          A

WORKING CLEARANCE                        A                              PROPERPHASINGCONNECTIONS ANDCOLOR CODE                      A

SWITCHGEAR CONTROL FUNCTIONS             A

PERFORM AUTOMATIC TRANSFER SYSTEM (ITS) FUNCTIONS UNDER THE ADJACENT CONDITIONS . A. OPERATENORMAL POWER A

                                         B. ALL GENERATORS OPERATE                                                                  A

                                         C. GENERATORS 1 AND 2 OPERATE                                                              A

                                         0. GENERATORS 2 AND 3 OPERATE                                                              A

                                         E. GENERATORS 1 AND 3 OPERATE                                                              R                                                            2.

                                         F. RETURN TO NORMAL POWER A FTER EA CH OF THEABOVETESTS

                                         G. PARALLEL WITH U TAITY UP ON RETURN TO NORMA LPOWER(ITEMS B THROUGH E)

                                                                 SECTION D- ELECTRICAL TESTS

18 .                                                                         VOLTAGE AND CURRENTMEASUREMENTS
               MEASUREMENTDESCRIPTION
                                         A-N B-N C.NVOLTA_GEA".B -g-C CA A B . N G CURRCENT"
                  _
Total at Output                          277 277 275 480 480 478 600 600                                                       600            1 .5                                               0 .5

                                         A-N                 BA  C-N    A-8  B-C                         C-A         A      B  C              N                                                      G

19 . NOTES                                                                                                                                                                                       USAPA V 1 .00

1 . CHECK FOR PROPER GROUNDING CONNECTIONS PRIOR TO ENERGIZING .
2 . DOES NOT OPERATE WITH THIS SEQUENCE .

'CONDITION :A -ACCEPTABLE, R -NEEDS REPAIR, REPLACEMENT OR ADJUSTMENT; C- CORRECTED; NA-NOT APPLICABLE
"NOTEVALUEAND PHASING
CA FORM 7470-R, AUG 2002

                                         Figure S-7. Sample ofcompleted DA Form 7470-R

                                                                                                                                                                                          5- 13


---

                                                                                                                   TM 5-694

                                         CHAPTER 6

                UNINTERRUPTIBLE POWER SUPPLY SYSTEMS

6-1 . Description of uninterruptible power supply (UPS) system

The following is a sample uninterruptible power supply (UPS) system with associated one-line and wiring
diagrams for use as a guide for implementing the test procedures described in the preceding chapters of
this manual .

  a. Figure description. The uninterruptible power supply system consists ofthe following equipment:
480V utility feeder breaker, 480V generator feeder breaker, 480V transfer switch, 200 kVA redundant
UPS, 125 Vdc NiCad battery and a 208/120V UPS switchboard panel. The 200 kVA UPS consists ofthe
following equipment: 480V incoming breaker, 125 Vdc rectifier, redundant 120/208 VAC inverters, static
switches, bypass switches and miscellaneous breakers . The equipment, accessories, interconnection,
ratings, cabling, etc. are shown on figures 6-1 through 6-3. Figure 6-1 is the uninterruptible power system
single line diagram on page 6-9. Figure 6-2 shown on page 6-10 is the uninterruptible power system
block diagram and figure 6-3 shown on page 6-11 is the uninterruptible power system wiring diagram.

   b. Switching. The utility and generator breakers are metal enclosed free standing, manually operated,
air power circuit breakers. The breakers have instantaneous, short time, and long time trip settings with
manual control and position indication on the door ofthe breaker compartment. The 480V transfer switch
is metal enclosed, break before make, dead bus transfer, automatic on loss of voltage, solenoid operated,
and mechanically held complete with microprocessor controls and indication, four pole switch . Transfer
time and time delay settings are adjustable . The transfer switch will supply start and stop signals to the
back-up diesel generator upon loss of and restoration ofutility power. These controls are timed and must
be coordinated with the diesel generator manufacturer for start-up, loading, and cool down times. Remote
 indication, control, alarm, etc. functions are also available.

   c. UPS operation. The UPS is a static solid state system with a battery for back-up power. The
 rectifiers convert ac to do power for supply to the redundant inverters and for charging the battery. The
 inverters receive power from either the rectifier or battery, and convert it from do to ac. The inverters
 also include power conditioning equipment and circuits to remove harmonics developed in the system .
 Because the input power is converted from ac to do to ac, power system disturbances are also removed
 from the UPS output. This makes UPSs ideal for use with sensitive electronic equipment and computers.
 The rectifiers and inverters are constructed with power diodes or silicon control rectifiers along with
 controls and filtering circuitry. The UPS also contains thermal magnetic molded case circuit breakers and
 two bumpless static switches. The switches will transfer the output of the UPS from one redundant
 inverter to the other upon failure ofthe lead inverter . The transfer between the inverters is accomplished
 with absolutely no loss of continuity of power to the load. In the sample system, as shown in figure 6-1,
 the two UPS modules are both sized to supply the entire load independent of one another. The 208/120 V
 switchboard is a metal enclosed, wall-mounted distribution panel with incoming and feeder unadjustable
 thermal magnetic molded case circuit breakers . The switchboard also receives a backup power supply
 from the utility power center for use during the maintenance ofthe UPS through two bypass switches.

    d. Battery description. The nickel cadmium (NiCad) batteries are individual 1 .2 volt cells in plastic or
 steel cases with nickel and cadmium plates in a potassium hydroxide solution . The cells are sealed,
 maintenance free and connected together in series on racks to supply 125 Vdc. The 120/208V UPS
 switchboard panel contains two main and numerous molded case thermal magnetic circuit breakers to
 distribute the power. The breakers have instantaneous and overcurrent elements trip characteristics . The


---

TM 5-694

UPS systems provide normal and uninterruptible regulated power to sensitive emergency plant loads, like
computers, communications, radar, security systems, lighting, etc.
6-2. Operation of uninterruptible power supply system
The operating modes for the UPS system are as follows:

  a. Normal condition. Utility breaker closed, diesel generator not running but in auto mode, diesel
generator breaker closed, transfer switch connected to utility, inverter A connected through UPS static
switch to UPS bus and UPS switchboard connected to the UPS.

  b. Loss ofrectifierlbattery charger A. UPS incoming breaker feeding rectifier/battery charger A
opens, circuit breaker connecting rectifier/battery charger A to battery bus opens and battery fed by
rectifier/battery charger B

  c. Loss ofinverter A. UPS static switch A switches UPS bus to inverter B and Inverter A circuit
breaker opens.

  d. Loss ofutilitypower. Battery supplies power to UPS bus through inverter A or B, transfer switch
supplies start signal to diesel generator, diesel generator starts and ramps up to speed and transfer switch
connects to diesel generator.

   e. Restoration ofutility. Utility power restored, transfer switch switches to utility bus and diesel
generator shut down by transfer switch .
6-3. Commissioning test plan for the UPS system
A system verification and functional performance test should be performed on the UPS system . These
tests will include installation inspections, individual component testing, testing on wiring, control and
interlock functional checks, equipment energization and system operating measurements and functional
checks .
6-4. Installation inspections and component testing of the UPS system
As indicated in more detail in chapter 3, the installation of the main components (i.e. utility and generator
circuit breakers, transfer switch, UPS, battery, battery charger, and UPS switchboard) will be inspected as
follows:

   a. Utility and generator circuit breakers. Completeness of assembly, verification of nameplate, sizes
and settings against drawings, loose parts and insulation damage, breaker alignment and manual operation
(leave circuit breaker open) and bus insulation resistance (if not previously energized) . Figure 5-6 (DA
Form 7469-R) shows a completed checklist for circuit breakers .

   b. Transfer switch . Completeness of assembly, verification of nameplate, sizes and settings against
 drawings, loose parts and insulation damage, switch alignment and manual operation (leave open), switch
 insulation resistance (phase-to-phase and phase-to-ground), PT and control fuse size and continuity,
 ground connection and check timer settings. Figure 6-4 on page 6-12 shows a completed DA Form 7970-
 R for a transfer switch inspection.

   c. UPS. Completeness of assembly, verification of nameplate, sizes and settings against drawings,
 loose parts and insulation damage, proper settings, control fuse size and continuity, ground connection,

 6-2


---

                                                                         TM 5-694

proper neutral connection, proper phase and voltage connections (incoming, battery, inverter A, and
inverter B) and manual operation of circuit breakers (leave open). Figure 6-5 shows a completed DA
Form 7972-R for the UPS inspection.

  d. NiCad battery. Completeness of assembly, verification of nameplate, sizes and connection against
drawings, loose parts, leaks, or damage, electrolyte level, vents sealed and plugs installed, grounding and
measure voltage. Figure 6-6 on page 6-14 shows a completed DA Form 7973-R for a battery inspection.

  e. -UPS switchboard. Completeness of assembly, verification ofnameplate, sizes and settings against
drawings, loose parts and insulation damage, ground connection, proper phase and voltage connections
and manual operation of circuit breakers (leave open). Figure 6-7 shows a completed DA Form 7974-R
for the switchboard inspection.

 f Cabling. Proper use, voltage, labeling, and connection using drawings, tightness and neatness of

termination and power cable insulation resistance (phase-to-phase and phase-to-ground). See figure 4-11 (DA
Form 7466-R) for sample of completed checklist.

  g. Visual and electrical wiring inspections . The termination ofeach cable, shown on the cable block
and wiring diagrams, should be checked to insure each conductor matches the wiring and schematic
diagrams . This is performed by yellowing each connection from the schematic to the wiring diagram;
visually inspecting each connection for cable number, wire number/color, and terminal; and checking
point-to-point continuity or "ringing out" each wire from end to end including grounds. For example
(figure 6-3) Cable BGATS 1 from Automatic Transfer Switch to the Backup Generator should be checked
to verify that the "black" wire is terminated as follows as shown on the schematic and wiring diagrams :

          Equipment                         Terminal No.
Automatic Transfer Switch
Backup Generator                                   B1
                                                   TI

As this is done, the wire on each drawing should be colored or highlighted to show its termination has
been checked. This process should be completed for all field wiring as a minimum and internal wiring if
not previously performed at the factory.

6-5. Energizing and test of the UPS system

The following steps are performed to energize and test the UPS system .

  a. Initial energization. Individual components of the UPS system shall be sequentially energized from
the source through the loads. As each item is energized, control functions, interlocks, and alarms should
be checked for proper operation. Voltage, phasing, and current measurements should be made at each
step .

  b. Utility breaker. Verify diesel generator breaker open, verify incoming voltage, manually close the
utility breaker, measure outgoing voltage and phasing of breaker, measure incoming voltage oftransfer
switch and note position of transfer switch and manually open breaker.

  c. Diesel generator breaker. Verify utility breaker open, start diesel generator, verify diesel generator
voltage, verify diesel generator and utility voltage have same magnitude and phasing, manually close
diesel breaker, measure outgoing voltage and phasing, measure voltage at transfer switch and note
position of transfer switch, manually open breaker and stop diesel generator and place in auto .

                                                                                                             6-3


---

TM 5-694

  d. Transfer switch. Verify diesel generator stopped and in auto, verify utility bus energized, manually
close utility breaker. Verify position of transfer switch and indication light status, measure input and
output voltage of transfer switch, check phasing of utility bus to output of transfer switch . Manually open
utility breaker. Diesel generator should start and switch should transfer to diesel generator. Note timing
of diesel generator start and transfer from opening of utility breaker. Manually close utility breaker.
Switch should transfer to utility and diesel generator should stop . Note timing of transfer and diesel
generator stop from closing of utility breaker. Push test switch to simulate normal source failure. Verify
diesel generator starts and transfer switch switches to diesel generator, return switch to utility feed and
verify diesel generator stops.

  e. UPS (rectifier/ battery charger/battery) . Verify UPS incoming breaker open. Verify utility feed
closed through to input of UPS and measure voltage and phasing. Verify rectifier/battery charger output
A breaker open . Verify rectifier/battery charger output B breaker open . Verify battery breaker A open
and measure battery voltage and polarity. Verify battery breaker B open and measure battery voltage and
polarity. Verify inverter A and inverter B incoming breakers open. Close UPS incoming breaker A and
measure rectifier/battery charger A output voltage, check do output meter. Press battery "pre charge"
button, if available, and close rectifier/battery charger A output breaker and close battery breaker A.
Measure battery charger voltage. Allow unit to run until battery fully charged or for a minimum of 24
hours. Record time. Measure rectifier/battery charger A output current and read meter every 4 hours.
Open UPS incoming breaker A. Operate UPS from battery until minimum voltage recorded (1 to 4
hours). Open battery breaker A. Close UPS incoming breaker B and measure rectifier/battery charger B
output voltage, check do output meter. Press battery "pre charge" button, if available, and close
rectifier/battery charger B output breaker and close battery breaker B. Measure battery charger voltage.
Allow unit to run until battery fully charged or for a minimum of 24 hours. Record time. Measure
rectifier/battery charger B output current and read meter every 4 hours.

        UPS (inverter/static switch). Verify UPS operational through rectifier/battery charger and battery.
        (1) Verify UPS normal condition operation.

          (a) Verify battery charged and on float.
          (b) Measure float voltage
          (c) Verify inverter A and inverter B breakers open.
          (d) Verify static switch switched to inverter A.
          (e) Close inverter A and B input breakers .
          (fi Measure inverter A and inverter B output voltage and read meters .
           (g) Verify inverter A and inverter B outputs in phase.
           (h) Verify static switch in inverter A position.
       (2) Verify proper operation of static switches.
           (a) Open inverter A incoming breaker.
           (b) Verify static switch switches to inverter B.

 6- 4


---

                                                                                                                              TM 5-694

        (c) Measure voltage and ensure bumpless .
        (d) Close inverter A incoming breaker and verify static switch switches to A.
        (e) Measure voltage and ensure bumpless .

             Open inverter B incoming breaker and verify static switch stays connected to inverter A.
         (g) Measure voltage and ensure bumpless .
     (3) Verify low voltage trip .
         (a) Open rectifier/battery charger output breakers .
         (b) Open battery breakers.
         (c) Verify inverter A and B trip on low voltage.
         (d) Close rectifier battery charger B output breaker and battery breakers.
         (e) Close inverter A and B input breakers .

              Open UPS incoming breakers.
         (g) verify inverter A and B output (feed from battery).
         (h) Measure voltage and current.
         (i) Close rectifier battery charger A output breaker and battery breakers.
         (/) Open UPS incoming breaker.
         (k) Verify inverter A and B output present (feed from battery) .
         (I) Measure voltage and current.
  g. Loading UPS. Close incoming breaker to UPS bus. Verify UPS is energized through static switch .
Verify all UPS loads connected properly and ready to start Close load breaker on UPS bus sequentially .
Measure voltage and read UPS meters at each step. Add load until UPS loads equal normal design load.
Run for 4 hours and check for overheating.
  h. Utility trip test. Verify UPS loaded and connected to utility. Manually open utility breaker. Verify
battery picks up load. Read current. Verify diesel generator starts, transfer switch transfers to diesel
generator, diesel generator picks up load, and battery returns to float mode. Measure voltage and current
at UPS and ensure bumpless transfer. Close utility breaker. Verify transfer switch transfers to utility,
battery picks up load during transfer, diesel generator stops, and battery returns to float after utility picks
up load. Measure voltage and current at UPS bus and ensure bumpless transfer.
   i. Inverter A to inverter B loadedtransfer test. Verify UPS loaded and connected to utility. Open
inverter A incoming breaker. Verify static switch switches to inverter B. Measure voltage and current at

                                                                                                                            6-5


---

TM 5-694

UPS bus and ensure bumpless transfer . Close inverter A incoming breaker. Verify that static switch
switches to inverter A. Measure voltage and current at UPS bus and ensure bumpless transfer .

  j. Battery discharge test. Verify UPS loaded and connected to utility. Notify plant of pending UPS
trip. Open diesel generator breaker and block auto and manual start. Open utility breaker. Verify battery
picks up load. Measure battery voltage and current. Measure UPS voltage and current and ensure
bumpless transfer. Operate UPS from battery until battery minimum voltage reached (1 to 4 hours) .
Record voltage. Verify inverter A and B trip when batteries reach minimum voltage. Notify plant of
pending UPS re-energization. Reclose utility breaker. Close diesel generator breaker and return to auto
start mode. Verify battery on float and charging, measure current. Verify when battery fully charged and
record time to charge .

  k Checklists. The inspection is considered complete when the UPS System Inspection and Test (see
figure 6-8 on page 6-16 for completed sample ofDA Form 7475-R) is satisfactorily completed.

6-6. Possible failures and corrective actions

Table 6-1 lists general problems that may arise during the testing of the equipment and systems along
with possible troubleshooting techniques . For all problems, consult the equipment and component
manuals for troubleshooting directions, check fuses/lights/breakers/etc . for continuity, check equipment
calibration and settings, and look for faulty equipment or connections.

          Table 6-1 . Possiblefailures and corrective actions ofthe UPS system

Utility and Generator Circuit Breaker          Areas to Check
Problem
Breakers will not close/trip                   Mechanicalalignment/ interlocks
                                                Relay and protective device settings and operation
Breaker trips inadvertently                     Mis-wired circuits
                                               Groundoncable or system
                                                Relay and protective device settings and operation
                                                System overload
                                                Mis-wired circuits

Transfer Switch                                Areas to Check
Switch will not transfer
                                               -Solenoidoperating mechanism
UPS-Rectifier/ Battery Charger
No output voltage/ current                     Time delay settings

Low output voltage                             Control panel

                                               Mis-wired circuits

                                               Areas to Check          _

                                               Input voltage/ breaker

                                               Rectifier (SCR) and rectifier fuse

                                               Input transformer

                                               Control board

                                               Dead input phase

                                               Rectifier (SCR) and rectifier fuse

                                               Voltage control settings or potential

                                               Control board

6-6


---

                                                                                   TM 5-694

Table 6-1. Possiblefailures and corrective actions ofthe UPSsystem (continued)

High output voltage                        Input voltage high           potential
Output voltage not adjustable              Voltage control settings or
High output current                        Control board
Low output current                         Voltage control potential
                                           Control board
                                           System overload/ short
                                           Current limit setting
                                           Control board
                                           Current limit setting
                                           Control board

UPS- Battery                               Areas to Check
Low battery voltage/ current/ capacity
                                           Battery and cell connections
Breaker trip                               Electrolyte level

                                           Cell voltage
                                           Cell condition, cleanliness, and age
                                           Float voltage/ current
                                           Battery room temperature

                                           Battery design versus actual load
                                           Battery/ system ground
                                           Battery / system short
                                           System overload

UPS- Inverters/ Static Switch              Areas to Check
No output voltage/ current                 Input voltage/ breaker
                                           SCR or diode
Low output voltage                         static switch
                                           constant voltage transformer
                                           control boards
                                           Input voltage
                                           System overload
                                           System frequency
                                           Control board

UPS- Inverters/ Static Switch              Areas to Check
High/Low output frequency                  Input voltage
                                           Alternate source
No transfer from Inverter A to Inverter B  Frequency control setting
                                           Control board
                                           Primary/alternate source
                                           Static switch
                                           Synchronizing circuit
                                           Control board

UPS System                                 Areas to Check
No output voltage/ current
                                           Incoming voltage
                                           Circuit breakers
                                           System components

                                                                                   6- 7


---

TM 5-694

          Table 6-1 . Possiblefailures and corrective actions (continued)

No transfer to Diesel generator   Diesel generator equipment/  breaker
Low/high output voltage/ current
                                  Transfer switch
Transfers not bumpless
Inadequate UPS capacity           Incoming voltage
                                  System components

                                  Battery sizing/ capacity
                                  System sizing/ capacity
                                  Battery connection

                                  Static switch
                                  Control board

                                  UPS sizing/ capacity
                                  Battery sizing/ capacity


---

200 MN 480V '~Ptfase Backup                                                     300A
Generator arid CUCUit Breaker
                                                                                  OWA
                                          ol . . ONO 1 . .                                        FIGURE 64

200, WA UPS                                          Breaker A      266 WA UPS      QW7ERRUPTISLE POWSRINSTEM
                                              ChBfgefA                                     SINGLE LINE DIAGRAM

4
ft

                                   121YDC
                                   Bettery .

                                              UPS Distribud Panels


---

 Utility Power Center                  CABLE     Backup Generator
          (UPC)                       ~GATS2             (BIG)

               CABLE         Automatic                          CABLE
                  P LES1  Transfer Switch                       BGATS1

CABLE                           (ATS)
UPCIT1
                                       CABLE
                                        ATSUPSI

Transformer           d Uniterruptable Power     CABLE   Battery
      (IT)                          Supply       UPSBT1   (BA)
                                    '(UPS)
              CABLE
              ITUPP1

                                                                                                 FIGURE 6-2
                                                                                     UNINTERRUPTIBLE POWER

                                                                                                   SYSTEM
                                                                                             BLOCK DIAGRAM

                        Figure 6-2. Uninterruptible power supply system block diagram

6- 1 0


---

w

w
0o-
b
 0
A
y
b
b

A
3

oc
00

a

3

                                                                                                                                                                                                                                                                           FIGURE 63
                                                                                                                                                                                                                                                        UNINTERRUPTIBLE POWER SYSTEM

                                                                                                                                                                                                                                                                      WIRING DIAGRAM


---

TM 5-694

                                          TRANSFER SWITCH INSPECTION CHECKLIST
                                        Foruse of this form seeTM 5-694; the proponent agency is COE.

1 . PLANTIBUILOING                                         SECTION A -CUSTOMER DATA
Bldg 1924
                                        2. LOCATION                                                    3.JOB NUMBER                         \,
4. EQUIPMENT                            Fort Tank
                                                                                                       02-125
7. TEST EQUIPMENT ANO CALIBRATION DATE
Biddle/ 14 May 2002                     5. CIRCUIT DESIGNATION                                         6.0 ATE /YYYYMMOD)
                                        F1                                                                                   20020823
9. MANUFACTURER
Russell Electric                                                                                       8. TESTED BY
13 . SWITCH RATING                                                                                     John Smith
4 Pole
16 .                                                       SECTION B- EQUIPMENTDATA

                         CHECKPOINT     10 . STYLESIS.O .         11 . VOLTAGE RATING                          12 . CURRENT RATING
                                                                  600V                                         1200A
EX TERIO R OF ED U IPMENT
                                                                  14 . ENCLOSURETYPE                                      15 . FREQUENCY
                                                                                                                          60hz

                                        SECTION C -VISUALAND ELECTRICALIMECHANICAL INSPECTION

                                        COND'              NOTES                        CHECKPOINT                        COND'        NOTES

                                        A                         EQUIPMENT ID ENTIFICATIO N                              A

COMPLETENESS OFASSEMBLY                 A                         BRACING

INDICATING LIGHTS                       A                         PROPER PHASE CONNECTIONS AND COLOR CODE                 A

SWITCH FOR FREEDOM OF MOVEMENT          A                         ENVIRONMENTAL CLASSIFICATION                            A

ELECTRIC ALIMEC HANICA L IN TERLOCKS    A                         WORKING CLEARANCE                                       A

A0JUSTTIMING SETTINGS                   A                         ANCHORAGE                                               A

PROPER EQUIPMENT GROUNDING              A                         REFERENCE DRAWINGS                                      A

CONTACT RESISTANCE                      A                         PROPER LUBRICATION                                      A

TIGHTNESS OF BOLTED CONNECTIONS         A                         PT AND CONTROL FUSE SIZE                                A

                                                           SECTION D -ELECTRICAL TESTS

17 .        INSULATION RESISTANCE       A-GRD              B-GRD             C-GRD                     A-B           B-C               C-A
18 . NOTES
                   @        V

1 . SWITCH TRANSFERS ON LOSS OF NORMAL POWER AT SPECIFIED TIME DELAY .
2 . SWITCH TRANSFER BACK TO NORMAL POWER ON RETURN OF NORMAL POWER SERVICE AT SPECIFIED
TIME DELAY .

3 . AUXILIARY CONTACTS OPERATE CORRECTLY DURING NORMAL AND ABNORMAL POWER CONDITIONS .

'CONDITION :A-ACCEPTABLE;R -NEEDS REPAIR, REPLACEMENT OR ADJUSTMENT; C- CORRECTED; NA-NOT APPLICABLE                                        USAPAV1 .00
DA FORM 7471 -R, AUG 2002

                                         Figure 6-4. Sample ofcompleted DA Form 7471-R
         6- 1 2


---

                                                                                                                       TM 5-694

                                       UNINTERRUPTIBLE POWER SUPPLY (UPS) INSPECTION CHECKLIST
                                                      For use of this form see TM 5-694; the proponent agency is COE.

(. PLANTIBUR.DING                                           SECTION A -CUSTOMER DATA                                   3.JOB NUMBER
                                                                                                                       02-126
Bldg 354                                    2. LOCATION                                                                7.DATE /YYYYMMaal

4. EQUIPMENT                                Fort Tank                                                                                       20020823
UPS                                                                                                                    9. TESTED BY
S. TEST EDUIPMENTANO CALIBRATION DATE       5. CIRCUIT DESIG NATION FED TO  S. CIRCU IT DESIGNATION FED
                                                                                                                       John Smith
Fluke 45/ 7 Aug 2002                          Main                          FROM Main
                                                                                                                                13 . kVA RATING
10 . MANUFACTURER                      11 . ST YLESIS.O .  SECTION B "EDUIPMENT DATA
                                                                                                                              130 kVA
Liebert                                                                        12. VOLTAGE RATING
                                                                             1600V                                                             COND'
14 . CHECKPOINT
                                            SECTION C " VISUALAND ELECTRICALINIECHANICALINSPECTION

                                            COND'          NOTES                                   CHECKPOINT                                         NOTES
                                                                                                                                                      C-A
EXTERIOR OFEQ UIPMENT                       A                            EQUIPMENT ID ENTIFICATION                     A

COMPLETENESS OFASSEMBLY                     A                            BRACING                                       A

INDICATING LIGHTS                           A                            PROPER PHASE CONNECTIONS AND COLOR CODE       A

SWITCH FOR FREEDOM OF MOVEMENT              A                            ENVIRONMENTAL CLASSIFICATION                  A

MANUALOPERATION0FCIRCUITBREAKERS            A                            WORKING CLEARANCE                             A

TIMING SETTINGS                             A                            ANCHORAGE                                     A

PROPER GROUNDING                            A                            REFERENCE DRAWINGS                            A

PROPER VOLTAGE CONNECTIONS                  A                            CONTROL FUSE SIZE AND CONTINUITY              A

LIGHTNESS OF BOLTED CONNECTIONS             A                            VERIFY ALL TRANSFER SWITCH OPERATIONS               A
TEST CIRCUIT BREAKERSWITHCURRENT INJECTION
TESTER                                      A              SECTION D -ELECTRICAL TESTS                                 B-C

15                                          A-ORD                 B-GRD               C-GRD                    A-B
                         VAC(OUTPUT)

16 . NOTES

1 . VERIFY SYSTEM GROUND (AT ONE POINT ONLY).

'CONDITION :A- ACCEPTABLE- R -NEEDS REPAIR, REPLACEMENT OR ADJUSTMENT, C- CORRECTED; NA -NOT APPLICABLE                                                             USAFAVI .oa
DA FORM 7472 -R, AUG 2002
                                                                                                                                                      6- 1 3
                                          Figure 6-S. Sample of completedDA Form 7472-R


---

TM 5-694

                                                          BATTERY INSPECTION CHECKLIST
                                                For use ofthis form see TM 5-694;theproponent agency is COE.

1. PLANTIBUILDING                                                SECTION A-CUSTOMER  DATA
                                                2. LOCATION
Bldg 358                                                                                                      3.JOB NUMBER
                                                Fort Tank
4. EQUIPMENT                                                                                                  02-133
                                                5. CIRCUIT DESIGNATION
BAT-1                                                                                                         6.0 ATE IYYYYMmDoj  20020823
                                                CKT-2                                                         B. TESTED BY
7. TEST EQUIPMENT ANO CALIBRA TION DATE   Load
                                                bank                                                          John Smith
Fluke 87, Hydrometer, Thermometer,

9. MANUFACTURER                       10 . STYLESIS .O .  SECTION B -EQUIPMENT DATA                                     12 . CURRENTRATING
                                                                              11 . VOLTAGERATING
FIAMM                                 SD 5
                                                                         3 Volts per cell

13. ENCLOSURETYPE                     14. FREQUENCY                 15 . WET BULB TEMPERATURE                           16 . DRY BULB TEMPERATURE

Wet Cell                              60 hz                         65 F                                                85 F

                                          SECTION C -VISUALAND ELECTRICALIMECHANICALINSPECTION

17.                                             COND'        NOTES                                CHECK POINT                     COND'            NOTES
                         CHECK POINT

EXTERIO R OF ED UIPMENT A EQUIPMENT ID ENTIFICATION A

COMPLETENESS OFASSEMBLY                         A                   BRACING                                                       A

ELECTROLYTE LEVEL                               A                   ENVIRONMENTAL CLASSIFICATION                                  A

VENTS SEALED AND PLUGS INSTALLED                A                   WORKING CLEARANCE                                             A

PROPER POLARITY CONNECTIONS                     A                   ANCHORAGE                                                               A
TIGHTNESS OF BOLTED CONNECTIONS
PROPER GROUNDING                                A                   CHECK FOR EXHAUST FAN IF IN ENCLOSED                                       A
CHECK FORSHOWERANDEYEWASH STATION
TESTCIRCUITBREAKERSWITHCURRENT INJECTION                            ENVIRONMENT                                                             A
TESTER
TEST CIRCUIT BREAKERS                           A                   REFERENCE DRAWINGS                                                         A

18 .                                            A                   CHECKFORACCESSTOBATTERIESFOR                                            A
               MEASUREMENT DESCRIPTION                                                                                                      A
                                                                    0&M
              BATTERY VOLTAGE & CURRENT                                                                                           CURRENT"
                                                A                   CHECKUPS CONTROL PANELALARMS                                   NEGATIVE

                                                A                   TEST TRANSFER SWITCH

                                                          SECTION D -ELECTRICAL TESTS
                                                                                       VOLTAGEAND CURRENTMEASUREMENTS

                                                                  VOLTAGE"

                                                   POSITIVE              NEGATIVE                             POSITIVE                             GROUND

19. NOTES

1 . MEASURE RESISTANCE BETWEEN CELL CONNECTIONS .
2 . MEASURE VOLTAGE ACROSS EACH CELL .
3 . CHECK SPECIFIC GRAVITY OF EACH CELL .
4 . TEST AND MAINTAIN BATTERY (CELLS) IN ACCORDANCE WITH MANUFACTURERS RECOMMENDATIONS .

*CONDITION :A-ACCEPTABLE;R-NEEDS REPAIR, REPLACEMENT OR ADJUSTMENT;C-CORRECTED; NA-NOT A PPLICABLE                                                 USAPAV1 .00
"NOTEVALUE AND PHASING
DA FORM 7473-R, AUG 2002

                                              Figure 6-6 Sample ofcompleted DA Form 7473-R

              6- 14


---

                                                                                                                               TM 5-694

                             UNINTERRUPTIBLE POWER SUPPLY IUPS) SWITCHBOARD INSPECTION CHECKLIST
                                                         Foruse of this form see TM 5-894; the proponent agency is CO E.

1. PLANTIBUILDING                                                   SECTION A-CUSTOMER DATA         3.JOB NUMBER
                                                    2. LOCATION                                     02-128
Bldg 1934
                                                    Fort Tank

4. EQUIPMENT                                        5. CIRCUIT DESIGNATION                          6.0 ATE frrrNMDD/
                                                                                                                                 20020823
Switchboard                                         Main

7. TEST EG UIPMENT TYPEIBRAND AND CALIBRATION DATE                                                  8. TESTED BY

Biddle                                                                                              John Smith

9. MANUFACTURER,                         10 . STYtESIS.O .  SECTION B -EQUIPMENT DATA                                12. CURRENTRATING
                                                                                11 . VOLTAGERATING
Siemens                                                                        600V                                  2000A

13 . BUS RA TINGICB INTERRUPTING RATING

2000A/ 50kA

                                         SECTION C-VISUALAND ELECTRICALIMECHANICALINSPECTION

14 . CHECKPOINT                                     COND'   NOTES                                   CHECKPOINT                 CONO'       NOTES
                                                                                                                                           C-A
EX TERIO R OF EQUIPMENT                             A                       BRACING                                            A

COMPLETENESS OFASSEMBLY                             A                       PROPER PHASECONNECTION AND COLOR CODE              A

INDICATING LIGHTS                                   A                       ENVIRONMENTAL CLASSIFICATION                       A

MANUAL OPERATION 0FCIRCUIT BREAKERS                 A                       WORKING CLEARANCE                                  A

PROPER GROUNDING                                    A                       ANCHORAGE                                          A

CONDITION OF INSULATION                             A                       REFERENCE DRAWINGS                                 A

PROPER VOLTAGE CONNECTIONS                          A                       VERIFY PROPER SIZES 0FBREAKERSANDFUSES             A

TIGHTNESS OF BOLTED CONNECTIONS A CHECK PROPER EQUIPMENT GROUNDING TO GROUNDING A

                                                                                                                  BUS

EQUIPMENT KI ENTIFICATION                           A

                                                            SECTION D -ELECTRICAL TESTS

15.         BUSINSULATIONRESISTANCE                 A-GRO          B-GRO                     C-GRD              A-B       B-C

                   D 1000 V                         10 megohm 12 megohm 12 megohm

16 . NOTES

1 . TEST ALL CIRCUIT BREAKERS ACCORDING TO MANUFACTURER'S RECOMMENDATIONS.

'CON DITIO N: A-ACCEPTABLE - R -NEEDS REPAIR, REP LA CEMENT OR ADJUSTMENT;C- CORRECTED; NA-NOT APPLICABLE                                                    U8APA V 1 .00
DA FORM 7474-R, AUG 2002
                                                                                                                                           6- 15
                                          Figure 6-7. sample of completedDA Form 7474-R


---

                                      UNINTERRUPTIBLE POWER SUPPLY (UPS) SYSTEM INSPECTION CHECKLIST
                                                            For use of this form seeTM 5-694; the proponent agency is CO E.

1. PLANTIBUILDING                                              SECTION A -CUSTOMER DATA       3. JOB NUMBER                                                                   -
Bldg 31~                                                                                      02-129                                                                      ~/
4. EQUIPMENT                                   2. LOCATION
UPS System                                     Fort Tank                                      B .DATEIYYYYMMDol                                                   NOTES
1. TEST EOU IPMENT
NA                                             5. CIRCUIT DESIGNATION                                                                             20020824
                                               Critical
9.
                          CHECKPOINT                                                                                             8. TESTED BY
                                                                                                                       John Smith
COMPONENT INSPECTIONITESTING
                                               SECTION B " VISUALANO ELECTRICALIMECHANICALINSPECTION

                                               COND'         NOTES                       CHECKPOINT                                                    COND'

                                               A                    ENERGIZE AND TEST SYSTEM                                                           A

INSTALLATION INSPECTIONITESTING                      A              UTILITY TRIP TEST                                                                  A
WIRINGVISUALVERIFICATION
GENERATOR CONTROL FUNCTIONS                          A RETURN) LOADED TRANSFERTEST(NORMAL,EMERGENCY & A

                                                     A              TIGHTNESS OF BOLTED CONNECTIONS                                                    A

LOADING UPS TEST                                     A              BATTERY DIS CHARGETEST                                                             A

DISCONNECT RECTIFIERS& INVERTERS SEPARATELY .        A              TESTALLUPSDIAGNOSTIC FAULT INDICATORS                                              A

DOES SYSTEM OPERATECORRECTLY?

                                                             SECTION 0-ELECTRICAL TESTS

10. UPS INPUT                                  A-N      B-N  C-N    A-B  B-C             GA   A                                                B  C           N   G
                         UPS OUTPUT
                                               277 277 277 465 465 465 100                            150                                         100             4
          UPS SWITCHBOARD HARMONIC (THO)
11 . NOTES                                     A'fi     B-N  GN     A43  B-C             C-A  A                                                B  C           N   G

                                               277 277 277 480 465 465                        100 .   150                                         100         20  4

                                               A4       B-N  CGN    A-B  B-C             C"A  A                                                8  C           N   G

                                               3% 3% 4%                                       38%     42%                                         40%

*CONDITION :A-ACCEPTABLE :R-NEEDS REPAIR, REPLACEMENT OR ADJUSTMENT: C-CORRECTED ; NA-NOT APPLICABLE                                                              USAPAV1 .00
"NOTEVALUE AND PHASING
DA FORM 7475 A. AllG 2002

                                          Figure 6-8. Sample ofcompletedDA Form 7475-R

              6-16


---

            TM 5-694

APPENDIX A
REFERENCES

REQUIRED PUBLICATIONS

Government Publications

Department ofthe Army.

  TM 5-686
  Power Transformer Maintenance and Commissioning, Department ofthe Army, Washington, DC,
  November, 1998 (Cited in figure 2-3).

Department ofEnergy

  Building Commissioning Guide, version 2.2, Department of Energy, Washington, D.C ., July 1998
(Cited in table 1-1).

Non-Government Publications

American Society ofMechanical Engineers (SAME)
Three Park Avenue, New York, NY 10016-5990

  ASME Power Test Codes (PTC) 26 (cited in paragraph 3-9d)

American Societyfor Testing and Materials (AST4
100 Barr Harbor Drive, West Conshohocken, PA 19428-2959

  ASTM D-924
   "Standard Test Method for Dissipation Factor (or Power Factor) and Relative Permittivity (Dielectric
  Constant) of Electrical Insulating Liquids," ASTM, PA, 1999 (cited in paragraph 2-4i).

Biddle Instruments
510 Township Line Rd., Blue Bell, PA 19422

  "A Stitch in Time . . .", Manual on Electrical Insulation Testing for the Practical Man, 1981 (cited in
  paragraph 2-7c)

Institute ofElectrical and Electronic Engineers (IEEE)
445 Hoes Lane, P.O. Box 1331, Piscataway, NJ 08855-1331

   ANSI/IEEE-Std 57.104-1995
   "IEEE Guide for the Interpretation of Gases Generated in Oil-Immersed Transformers," IEEE, Inc.,
  New York, 1995 . (cited in paragraph 3-3e).

   ANSI/IEEE-Std 141-1993
   Red Book, "Electrical Power Distribution for Industrial Plants," IEEE, Inc., New York, NY, 1993 (cited
   in table 3-2)


---

TM 5-694

   IEEE 400
   "IEEE Guide for Making High-Direct-Current-Voltage Tests on Power Cable Systems in the Field", 1991
   (cited in paragraph 3-13 and table 3-2)

   IEEE-Std 43-2000
   "IEEE Recommended Practice for Testing Insulation Resistance ofRotating Machinery," IEEE, Inc.,
   New York, 2000 (cited in paragraph 2-7).
   IEEE Std. 48-1996
   "IEEE Standard Test Procedures and Requirements for Alternating Current Cable Terminations 2.5 KV
   through 765 KV", IEEE, Inc., New York, 1996 (cited in paragraph 2-4g and 3-13).
   IEEE-Std 62-1995
   "Guide for Diagnostic Field Testing ofElectric Power Apparatus - Part 1: Oil Filled Power
   Transformers, Regulators, and Reactors," IEEE, Inc., New York, NY, 1995. (cited in table 3-1)
   IEEE-Std 100-1996
   PTC 26-1962
   "Speed-Governing Systems for Internal Combustion Engine-Generator Units," ASME, New York,
   1962 (cited in paragraph 3-9d).

  IEEE-Std 386-1995
   "IEEE Standard for Separable Insulated Connector Systems for Power Distribution Systems Above 600
  V", IEEE, Inc., New York, 1995 (cited in paragraph 3-13).
InterNational Electrical Testing Association (NETA)
P.O. Box 687, Morrison, CO 80645
www.netaworld .ore

  IETA 2
   "Acceptance Testing Specifications for Electric Power Distribution Equipment and Systems," NETA,
  CO, 1991 (cited in paragraph 3-13).

  NETA-STDATS 1999
  "Commissioning Specifications for Electrical Power Distribution Equipment and Systems," National
  Electrical Testing Association (cited in paragraph 2-4f and table 3-2)

Mechanical Engineering Handbook, T. Baumeister (ed.) and E. Avallone (ed.), McGraw-Hill Book
Company, Inc, New York, 1978 . (cited in paragraph 3-9d).

RELATED PUBLICATIONS

Non-Government Publications

American Society ofHeating, Refrigerating and Air-Conditioning Engineers (ASHRAE)
1791 Tullie Circle NE, Atlanta, GA 30329

   ASHREA Guideline 1-1989
   "Commissioning of HVAC Systems,

A-2


---

                                                                                                                                  TM 5-694

Institute ofElectrical andElectronics Engineers (IEEE)
445 Hoes Lane, P.O. Box 1331, Piscataway, NJ 08855-1331 .

   ANSMEEE 944-1986
   "Recommended Practice for the Application and Testing ofUninterruptible Power Supplies for Power
   Generating Stations", IEEE, Inc . New York, NY, 1986.

   IEEE 450-1995
   "Recommended Practice for Maintenance, Testing, and Replacement of Vented Lead-Acid Batteries for
   Stationary Applications", IEEE, Inc., New York, N.Y., 1995.

   IEEE 484-1996
   "Recommended Practice for Installation Design and Installation ofVented Lead-Acid Batteries for
   Stationary Applications", IEEE, Inc., 1996.

   IEEE-Std 57.12 .80-1995
   "Standard Terminology for Power and Distribution Transformer," IEEE, New York, 1995 .

   IEEE-Std 95-1977
   "Insulation Testing ofLarge AC Rotating Machinery with High Direct Voltage," IEEE, Inc ., New
   York, 1977.

   IEEE Std 242-1991
   BuffBook, Protection and Coordination ofIndustrial and Commercial Power Systems," IEEE, Inc ., New
   York, NY, 1991 .

   IEEE-Std 446-1995
   Orange Book, "Emergency and Standby Power Systems for Industrial and Commercial Applications,"
   IEEE, Inc ., New York, NY, 1996.

   IEEE Std. 1106-1995
   "Recommended Practice for Installation, Maintenance, Testing, and Replacement ofVented Nickel-
   Cadmium Batteries for Stationary Applications", IEEE, Inc., New York, NY 1995 .

   IEEE Std. 1115-1992
   "Recommended Practice for Sizing Nickel-Cadmium Batteries for Stationary Applications", IEEE, Inc., New
   York, NY 1992.

   IEEE-Std. 1187-1996
   "Recommended Practice for Installation Design and Installation ofValve-Regulated Lead-Acid
   (VRLA) Batteries for Stationary Applications", IEEE, Inc ., New York, N.Y., 1996.

   IEEE-Std . 1188-1996
   "Recommended Practice for Maintenance, Testing, and Replacement ofValve-Regulated Lead-Acid
   (VRLA) Batteries for Stationary Applications", IEEE, Inc., New York, N.Y., 1996.

   "IEEE Standard Dictionary ofElectrical and Electronic Terms," IEEE., New York, 1996.
   Department Guide Book No. EE-31 Vol . C, "Electrical Engineering Guides and Data," Ebasco Services
   Inc ., New York, 1993 .

                                                                                                                                           A-3


---

TM 5-694

  IEEE Transactions on Industry Applications, Vol.24, No. 6, November/December 1988
  "Commissioning ofElectric Motors and Generators", Paul S. Hamer.

National Fire Protection Association (NFPA):
One Batterymarch Park, P.O . Box 9101, Quincy, MA 02269-9101

  NFPA 70B
  "Electrical Equipment Maintenance", National Fire Protection Association, Quincy, MA, 1998 .

  NFPA 110
  "Emergency and Standby Power Systems," National Fire Protection Association, Quincy, MA, 1996.

  NFPA 111
  "Standard on Stored Electrical Energy Emergency and Standby Power Systems," National Fire
  Protection Association, Quincy, MA, 2001 .

Standard Handbook for Electrical Engineers, D. G. Fink (ed.). and J. M. Carroll (ed.), McGraw-Hill Book
Company, New York, 1968 .

The J&P Transformer Book, S. Austen Stigant and A.C . Franklin, John Wiley & Sons, New York, 1973 .

PRESCRIBED FORMS
The following forms are printed in the back ofthis manual and are also available on the Army Electronic
Library (AEL) CD-ROM (EM 0001) and the USAPA web site (http://www.usapa.army.mil)

   DA Form 7463-R
   Circuit Switcher Inspection Checklist (Prescribed in paragraph 1-5 and 4-4a)

  DA Form 7464-R
   Transformer Inspection Checklist (Prescribed in paragraph 1-5 and 4-4b)

   DA Form 7465-R
   Switchgear Inspection Checklist (Prescribed in paragraph 1-5, 4-4c, and 5-4c)

   DA Form 7466-R
   Power Cable Inspection Checklist (Prescribed in paragraph 1-5, 4-4d, 5-4d, and 6-4f)

   DA Form 7467-R
   Main Power System Energization Checklist (Prescribed in paragraph 1-5 and 4-5b(5)]

   DA Form 7468-R
   Engine Generator Set Inspection Checklist (Prescribed in paragraph 1-5 and 5-4a)

   DA Form 7469-R
   Backup Power System Inspection Checklist (Prescribed in paragraph 1-5 and 5-5f)

   DA Form 7470-R
   Utility and Generator Circuit Breaker Inspection Checklist (Prescribed in paragraph 1-5, 5-5f, and 6-4a)


---

                                                                                                                      TM 5-694

  DA Form 7471-R
  Transfer Switch Inspection Checklist (Prescribed in paragraph 1-5 and 6-4b)

  DA Form 7472-R
  Uninterruptible Power Supply (UPS) Inspection Checklist (Prescribed in paragraph 1-5 and 6-4c)

  DA Form 7473-R
  Battery Inspection Checklist (Prescribed in paragraph 1-5 and 6-4d)

  DA Form 7474-R
  Uninterruptible Power Supply (UPS) Switchboard Inspection Checklist (Prescribed in paragraph 1-5
and 6-4e)

  DA Form 7475-R
  Uninterruptible Power Supply (UPS) System Inspection Checklist (Prescribed in paragraph 1-5 and 6-
5k)


---

                                                                                                                          TM 5-694

The proponent agency of this publication is the Chief of Engineers, United States Army.
Users are invited to send comments and suggested improvements on DA Form 2028
(Recommended Changes to Publications and Blank Forms) directly to HQUSACE, (ATTN:
CEMP-SP), Washington, DC 20314-1000.

By Order of the Secretary of the Army:       ERIC K. SHINSEKI

Official :                              General, United States Army
                                                  Chief of Staff
  ;VJ644")
      JOEL B. HUDSON

Administrative Assistant to the
      Secretary of the Army

Distribution :

         To be distributed in accordance with Initial Distribution Number QDN) 344745,
requirements for non-equipment TM 5-694.


---

                                      CIRCUIT SWITCHER INSPECTION CHECKLIST
                                      For use of this form see TM 5-694; the proponent agency is COE .

PLANT/BUILDING                                  SECTION A - CUSTOMER DATA            3 . JOB NUMBER
                                      2. LOCATION

4. EQUIPMENT                          5. CIRCUIT DESIGNATION                         6 . DATE (YYYYMMDD)

7. TEST EQUIPMENT TYPEBRAND AND CALIBRATION DATE                                     8. TESTED BY

                                             SECTION B - EQUIPMENT DATA

9. MANUFACTURER                       10. STYLES/S .O .         11 . VOLTAGE RATING                           12 . CURRENT RATING

13 . INTERRUPTING RATING                                        14. BUS BRACING

                                 SECTION C - VISUAL AND ELECTRICAL/MECHANICAL INSPECTION

15 .                                  COND*              NOTES             CHECK POINT                        COND*         NOTES
                    CHECK POINT

EXTERIOR OF EQUIPMENT                                           EQUIPMENT IDENTIFICATION

COMPLETENESS OF ASSEMBLY                                        BRACING
ELECTRICAL/MECHANICAL INTERLOCKS
PROPER GROUNDING                                                PROPER PHASE CONNECTION AND
                                                                COLOR CODE

                                                                HAZARDOUS LOCATION

ALIGNMENT AND ROTATION LIMITS                                   CONTACT RESISTANCE

TIGHTNESS OF BOLTED CONNECTIONS                                 ANCHORAGE

PROPER LUBRICATION                                              REFERENCE DRAWINGS

INTERRUPTER TIME TRAVEL                                         CONTROL CIRCUIT OPERATION

MANUAL OPERATION                                                ENERGIZED OPERATION

16. INSULATION RESISTANCE                    SEijCTION D - EL-1E-CTRICA L TESTS                         _
                                   V
                                      A-GRD              B-GRD      C-GRD               A-B                   B-C           CA
17.
       MEASUREMENT DESCRIPTION                                  VOLTAGE AND CURRENT MEASUREMENTS

                                                         VOLTAGE**                                            CURRENT**

                                      A-N B-N C-N A-B B-C C-A                        A                     B  C          N         G

                                      A-N B-N C-N A-B B-C C-A                        A                     B  C          N         G

                                      A-N B-N C-N A-B B-C C-A                        A                     B  C          N         G

18. NOTES :

*CONDITION : A=ACCEPTABLE ; R=NEEDS REPAIR, REPLACEMENT OR ADJUSTMENT; C--CORRECTED ; NA=NOT APPLICABLE                     USAPA V1 .00
**NOTE VALUE AND PHASING

DA FORM 7463-R, AUG 2002


---

                                   TRANSFORMER INSPECTION CHECKLIST

                                For use of this form see TM 5-694; the proponent agency is COE .

PLANTBUILDING                              SECTION A - CUSTOMER DATA           3. JOB NUMBER
                                 2 . LOCATION

4 . EQUIPMENT                    5 . CIRCUIT DESIGNATION                       6. DATE (YYYYMMOD)

7 . TEST EQUIPMENT TYPE/BRAND AND CALIBRATION DATE                             8. TESTED BY

                                        SECTION B - EQUIPMENT DATA

9. MANUFACTURER                 10. STYLES/S .O.          11 . VOLTAGE RATING                     12 . CURRENT RATING
13. WET BULB TEMPERATURE                                                                          16. FREQUENCY
                                14. DRY BULB TEMPERATURE   15. ENCLOSURE TYPE

                                SECTION C - VISUAL AND ELECTRICALJMECHANICAL INSPECTION

17 .                             COND*            NOTES              CHECK POINT                   COND*  NOTES
                   CHECK POINT
                                                          PROPER PHASE CONNECTION AND
EXTERIOR OF EQUIPMENT                                     COLOR CODE
COMPLETENESS OF ASSEMBLY
                                                          HAZARDOUS LOCATION

PROPER GROUNDING                                          WORKING CLEARANCE

CONDITION OF INSULATION                                   ANCHORAGE

TIGHTNESS OF BOLTED CONNECTIONS                           REFERENCE DRAWINGS

SEALS AND OIL LEVELS                                      TURNS RATIO MEASUREMENTS

JVINDING CONFIGURATION                                    AUXILIARY DEVICE OPERATION

                                        SECTION D - ELECTRICAL TESTS

18 . INSULATION RESISTANCE       A-GRD              B-GRD  C-GRD               A-B                B-C     C-A

                      V

POLARIZATION INDEX

TURNS RATIO TEST

POWER FACTOR

                PROPER VOLTAGE
19 . NOTES:

1. PERFORM GROUND RESISTANCE TESTS PRIOR TO ENERGIZING EQUIPMENT.
2. GROUND RESISTANCE TESTS MUST BE PERFORMED IN DRY CONDITIONS AND SHALL BE PERFORMED
48 HOURS AFTER RAINFALL .

*CONDITION: A=ACCEPTABLE ; R=NEEDS REPAIR, REPLACEMENT OR ADJUSTMENT ; C=CORRECTED; NA-- NOT APPLICABLE   USAPA V1 .00

DA FORM 7464-R, AUG 2002


---

                                      SWITCHGEAR INSPECTION CHECKLIST

                                  For use of this form see TM 5-694; the proponent agency is COE.

PLANT/BUILDING                             SECTION A - CUSTOMER DATA             3. JOB NUMBER
                                  2. LOCATION

4. CIRCUIT DESIGNATION      5 . CIRCUIT FED FROM             6. CIRCUIT FED TO                        7. DATE (YYYYMMDD)

8. TEST EQUIPMENT TYPE/BRAND AND CALIBRATION DATE            9 . ENCLOSURE TYPE                    10. TESTED BY
                                                                                                          14. CURRENT RATING
                                         SECTION B - EQUIPMENT DATA

11 . MANUFACTURER                 12 . STYLES/3 .0 .         13. VOLTAGE RATING

15 . INTERRUPTING RATING                                     16. BUS BRACING

                            SECTION C -VISUAL AND ELECTRICALIMECHANICAL INSPECTION

17. CHECK POINT                   COND"               NOTES             CHECK POINT                      COND"            NOTES

EXTERIOR OF EQUIPMENT                                        EQUIPMENT IDENTIFICATION

REFERENCE DRAWINGS                                           BRACING
ELECTRICAL/MECHANICAL DRAWOUT                                PROPER PHASE CONNECTION AND
MECHANISM AND INTERLOCKS                                     COLOR CODE
BUS AND SUPPORT INSULATORS                                   HAZARDOUS LOCATION

PROPER LUBRICATION                                           WORKING CLEARANCE

CLEAN SWITCHGEAR                                             ANCHORAGE

CHECK MANUAL OPERATION OF                                    ALL FILTERS AND VENTS CLEAR
CIRCUIT BREAKERS AND RELAYS                                  CHECK PROPER EQUIPMENT GROUNDING
 -EST RELAYS (ACCORDING TO ELEC.                             TO GROUNDING BUS
ffUDY RECOMMENDATIONS)

CHECK INSTRUMENT AND RELAY                                   SWITCHES FOR FREEDOM OF MOVEMENT
COVERS                                                       CHECK INCOMING LINE CONNECTIONS TO
CHECK CIRCUIT BREAKER INSULATING                             MAIN BUS
PARTS

CHECK CIRCUIT BREAKER CONTACT                                VERIFY PROPER SIZE BREAKERS/FUSES
SURFACES

18. VERIFY LIFT OR BUILT WINCH FOR HANDLING HEAVY PARTS      19. VERIFY CORRECT OPERATION OF INDICATING LIGHTS, METERS,
                                                             GAUGES, ETC .

20. VERIFY BOLTED BUS CONNECTIONS TO MANUFACTURER            21 . VERIFY SPACE HEATER IS PROVIDED AND OPERATIONAL
RECOMMENDATIONS

                                         SECTION D - ELECTRICAL TESTS

22 . INSULATION RESISTANCE        A-GRD               B-GRD     C-GRD               A-B               B-C                 C-A

in_,                V

23 .                                                         VOLTAGE AND CURRENT MEASUREMENTS
       MEASUREMENT DESCRIPTION
                                                      VOLTAGE"                                        CURRENT*"

                                  A-N B-N C-N A-B B-C CA                         A                 B  C          N             G

                                  A-N B-N C-N A-B B-C C-A                        A                 B  C          N             G

                                  A-N B-N C-N A-B B-C C-A                        A                 B  C          N             G

24 . NOTES

1 . VOLTAGE MEASUREMENTS TO BE MADE AFTER UTILITY SOURCE IS CONNECTED TO INCOMING BREAKER
WITH THE UTILITY BREAKER OPEN.
2. INSULATION RESISTANCE TESTS MUST BE PERFORMED PRIOR TO ENERGIZING EQUIPMENT .

"CONDITION : A=ACCEPTABLE; R=NEEDS REPAIR, REPLACEMENT OR ADJUSTMENT ; C --CORRECTED ; NA=NOT APPLICABLE                  USAPA V1 .00
**NOTE VALUE AND PHASING

DA FORM 7465-R, AUG 2002


---

                               POWER CABLE INSPECTION CHECKLIST
                            For use of this form see TM 5-694; the proponent agency is COE.

. PLANT/BUILDING                             SECTION A - CUSTOMER DATA      3. JOB NUMBER
                                    2. LOCATION

4. EQUIPMENT                        5. CIRCUIT DESIGNATION                  6. DATE (YYYYMMDD)

7. TEST EQUIPMENT TYPE/BRAND AND CALIBRATION DATE                           8. TESTED BY

                                           SECTION B - EQUIPMENT DATA

9. MANUFACTURER             10. STYLES/S .O .         11 . VOLTAGE RATING                    12. CURRENT RATING
13. WET BULB TEMPERATURE                                                                     16. FREQUENCY
                            14. DRY BULB TEMPERATURE 115. ENCLOSURE TYPE

                            SECTION C -VISUAL AND ELECTRICAL/MECHANICAL INSPECTION

17 . CHECK POINT                    COND"      NOTES        CHECK POINT                         COND'   NOTES

EXTERIOR OF CABLE RUN                                 BRACING AND SUPPORTS
PROPER GROUNDING AT TERMINAL
LUGS TO BUS                                           CHECK PROPER SIZE OF CABLE
REFERENCE EXISTING 1-LINE DIAGRAMS                    TIGHTNESS AND NEATNESS OF
PROPER LUBRICATION                                    TERMINATIONS
CHECK GROUNDING AT SPLICE JOINTS
CHECK CABLE PHASE COLOR CODE                          ANCHORAGE

                                                      CHECK PROPER SIZE TERMINAL LUGS
                                                      AND MATERIAL
                                                      CHECK CABLE PHASE COORDINATION

SHIELD CONTINUITY                                     CABLE IDENTIFICATION

18 . INSULATION RESISTANCE                 SECTION D - ELECTRICAL TESTS
APPLIED VOLTAGE
19 . NOTES                          A-GRD          B-GRD    C-GRD           A-B              B-C        C-A

1. PERFORM HIGH POTENTIAL TESTS IN ACCORDANCE WITH SPECIFIED REQUIREMENTS OR
MANUFACTURER(S) RECOMMENDATIONS .

'CONDITION : A=ACCEPTABLE ; R=NEEDS REPAIR, REPLACEMENT OR ADJUSTMENT; C--CORRECTED; NA=NOT APPLICABLE  USAPA V1 .00
DA FORM 7466-R, AUG 2002


---

                                    MAIN POWER ENERGIZATION CHECKLIST

                                  For use of this form see TM 5-694; the proponent agency is COE .

' . PLANT/BUILDING                         SECTION A - CUSTOMER DATA        3 . JOB NUMBER
                                  2. LOCATION

4. CIRCUIT DESIGNATION         5. CIRCUIT FED FROM          CIRCUIT FED TO                    7. DATE (YYYYMMDD)
                                                    T.                      9. TESTED BY

8. TEST EQUIPMENT TYPE/BRAND AND CALIBRATION DATE

                               SECTION B - VISUAL AND ELECTRICALIMECHANICAL INSPECTION

10 .                              COND'  NOTES                 CHECK POINT                                COND"     NOTES
                  CHECK POINT

COMPONENT INSPECTION/TESTING                        VERIFY SWITCHGEAR CONTROL
COMPLETED                                           FUNCTIONS

WIRING VISUAL VERIFICATION                          CHECK FOR WORKING CLEARANCE

VERIFY WIRING DIAGRAMS                              ENERGIZE AND TEST SYSTEM

VERIFY CIRCUIT SWITCHER CONTROL                     TRANSFORMER TRANSFER CONTROL
FUNCTIONS                                           FUNCTIONS

ENERGIZE AND TEST SYSTEM FOR ALL                    CHECK FOR UNUSUAL SOUNDS AFTER
CONDITIONS                                          ENERGIZING

CHECK BUSHING OR TERMINALS                          CHECK ANCHORING OF TRANSFORMER
                                                    SWITCHGEAR AND SWITCHES ENCLOSURE

CHECK FOR REMOVAL OF PAINT OR                       CHECK FOR NORMALIABNORMAL
HEAVY DENTS                                         SWITCHING OPERATION

                                         SECTION C - ELECTRICAL TESTS

11 .                                                VOLTAGE AND CURRENT MEASUREMENTS
       MEASUREMENT DESCRIPTION
                                                    VOLTAGE'"                                          CURRENT"

                                  A-N B-N C-N A-B B-C C-A                   A                       B  C         N  G

A-N B-N C-N A-B B-C _ - C-A -A . B- C N G

                                  A-N B-N C-N A-B B-C C-A                   A                       B  C         N  G

                                  A-N B-N C-N AB B-C C-A                    A                       B  C         N  G

                                  A-N B-N C-N A-B B-C C-A                   A                       B  C         N  G

12. NOTES

*CONDITION: A=ACCEPTABLE ; R=NEEDS REPAIR, REPLACEMENT OR ADJUSTMENT; C=CORRECTED ; NA=NOT APPLICABLE               USAPA V1 .00
"*NOTE VALUE AND PHASING

DA FORM 7467-R, AUG 2002


---

                          ENGINE GENERATOR SET INSPECTION CHECKLIST
                               For use of this form see TM 5-694; the proponent agency is COE.

. PLANT/BUILDING                         SECTION A - CUSTOMER DATA         3. JOB NUMBER
                                 2. LOCATION

4. EQUIPMENT                     5. CIRCUIT DESIGNATION                    6. DATE (YYYYMMDD)

7. TEST EQUIPMENT TYPE/BRAND AND CALIBRATION DATE                          8. TESTED BY

                                             SECTION B - EQUIPMENT DATA

9. MANUFACTUhER           10 . STYLES/S.O .         11 . VOLTAGE RATING                         12. kW RATING

13. CIRCUIT BREAKER SIZEANTERRUPTING RATING         14. WET BULB TEMPERATURE 15 . DRY BULB TEMPERATURE

                          SECTION C - VISUAL AND ELECTRICAL/MECHANICAL INSPECTION

16. CHECK POINT                  COND*       NOTES        CHECK POINT                              COND*       NOTES
                                                                                                B-C            C,A
EXTERIOR OF EQUIPMENT                               EQUIPMENT IDENTIFICATION
COMPLETENESS OF ASSEMBLY                            BRACING
EQUIPMENT ROTATION                                  PROPER PHASE CONNECTIONS
CHECK OIL LEVEL                                     REFERENCE DRAWINGS
CHECK FUEL LEVEL                                    WORKING CLEARANCE
PROPER EQUIPMENT GROUNDING                          ANCHORAGE
CHECK METERSIGAUGES                                 ALL FILTERS AND VENTS CLEAR
TIGHTNESS OF BOLTED CONNECTIONS                     CHECK EQUIPMENT ENVIRONMENTAL
VERIFY GOVERNOR AND REGULATOR                       CLASSIFICATION
CHECK VIBRATION                                     CHECK FOR PROVISIONS OF SPILL
CHECK BATTERIES                                     CONTAINER
CHECK RADIATOR FLUID                                CONTROL SYSTEM
PROPER SYSTEM GROUND                                CHECK FUEL FILTER
                                                    CHECK ALARM INDICATORS : PROPER
17 . INSULATION RESISTANCE                          COLOR FOR EACH FUNCTION
                        V
                                             SECTION D - ELECTRICAL TESTS

                                 A-GRD             B-GRD  C-GRD            A-B

            POLARIZATION INDEX
       RATIO =10 MINUTE/1 MINUTE

         DC OVERPOTENTIAL TEST
                               V

18 . NOTES

1 . PERFORM 5 MEASUREMENTS AT ONE MINUTE INTERVALS .
2. DC HIPOT MEASUREMENTS SHOULD BEGIN AT 20% OF MAXIMUM TEST VOLTAGE AND INCREASE IN EQUAL
INTERVALS.

          MAX DC TEST VOLTAGE = R (2 x NAMEPLATE RATING) x 1 .6
                                                                 WHERE R = .8 FOR DC TEST ON INSTALLATION
                                                                 WHERE R = .6 FOR DC TEST AFTER SERVICE

(TEST MEASUREMENTS SHOULD NOT EXCEED MANUFACTURER'S RECOMMENDATION)

DA FORM 7468-R, AUG 2002                                                                                       PAGE 1 OF 2


---

                                SECTION D - ELECTRICAL TESTS (Continued7

19 .                                                 VOLTAGE AND CURRENT MEASUREMENTS
       MEASUREMENT DESCRIPTION
                                                       VOLTAGE**          CURRENT-
                                A-N I B-N , C-N I A-B I B-C -~ C-A

/0 . LOAD TESTS AS A PERCENTAGE OF GENERATOR RATING

     NO LOAD  25%               75%                  100%                 110% (PRIME ENGINE ONLY)

A-N

B-N

C-N

A-B

B-C
C-A

A

B
C

N

    G

21 . NOTES
' . VOLTAGE MEASUREMENT TO BE MADE AFTER GENERATOR IS STARTED AND CONNECTED TO LOAD (CAN
JSE LOAD BANK).

2. DURING COMMISSIONING OF GENERATOR SETS OR ANY EQUIPMENT, A REPRESENTATIVE OF THE
MANUFACTURING COMPANY OR SUPPLIER MUST BE PRESENT TO WITNESS AND/OR PERFORM THE TESTS.

3. ENGINE GENERATOR TESTING IS A VERY INTENSIVE PROCESS AND REQUIRES A 10 TO 14 HOUR DAY
DEPENDING ON THE EQUIPMENT BEING COMMISSIONED. SUPPLIER/MANUFACTURER NORMALLY SUPPLY
GENERATOR TESTING LOAD REQUIREMENTS.

4. VERIFY ALL SYSTEM CHECK POINTS DURING LOAD CHANGES AND RECORD PER SPECIFIED REQUIREMENTS
AND/OR EQUIPMENT MANUFACTURER

5. PERFORM AND RECORD ENGINE MANUFACTURER'S RECOMMENDED CHECKS AND INSPECTIONS.

*CONDITION : A=ACCEPTABLE; R=NEEDS REPAIR, REPLACEMENT OR ADJUSTMENT; CORRECTED ; NA--NOT APPLICABLE  PAGE 2 OF 2
**NOTE VALUE AND PHASING

DA FORM 7468-R, AUG 2002


---

                  UTILITY AND GENERATOR CIRCUIT BREAKER INSPECTION CHECKLIST

                                         For use of this form see TM 5-694 ; the proponent agency is COE .

PLANT/BUILDING                                     SECTION A - CUSTOMER DATA   3. JOB NUMBER
                                         2. LOCATION

4 . EQUIPMENT                            5. CIRCUIT DESIGNATION                6. DATE (YYYYMMDD)

7 . TEST EQUIPMENT AND CALIBRATION DATE                                        8. TESTED BY

                                         SECTION B - EQUIPMENT DATA

9. MANUFACTURER            10 . STYLES/S .O.              11 . VOLTAGE RATING                12. CURRENT RATING

13 . CIRCUIT BREAKER SIZE AND INTERRUPTING RATING         14 . EQUIPMENT CLASSIFICATION                     15 . FREQUENCY

                           SECTION C - VISUAL AND ELECTRICAL/MECHANICAL INSPECTION

16 . CHECK POINT                 COND*             NOTES             CHECK POINT                            COND*  NOTES

EXTERIOR OF EQUIPMENT                                     BRACING
COMPLETENESS OF ASSEMBLY
EXECTRICAUMECHANICAL INTERLOCKS                           PROPER PHASE CONNECTIONS AND
                                                          COLOR CODE

                                                          HAZARDOUS LOCATION

PROPER GROUNDING                                          WORKING CLEARNACE

CONTACT RESISTANCE                                        ANCHORAGE

AUXILIARY WIRING                                          REFERENCE DRAWINGS

PROPER LUBERICATION                                       CHECK MANUAL OPERATION OF CIRCUIT
TIGHTNESS OF BOLTED CONNECTIONS                           BREAKER AND RELAYS

                                                          RELAYS TESTED (ACCORDING TO
                                                          ELECTRICAL STUDY RECOMMENDATIONS)

EQUIPMENT IDENTIFICATION

                                         SECTION D - ELECTRICAL TESTS

17. INSULATION RESISTANCE                A-GRD     B-GRD         C-GRD         A-B            B-C                  C-A

               @    V

18 . NOTES

1 . MANUFACTURER'S INSTALLATION TESTS/CHECKS SHOULD BE IMPLEMENTED.

*CONDITION : A=ACCEPTABLE; R=NEEDS REPAIR, REPLACEMENT OR ADJUSTMENT ; C=CORRECTED; NA=NOT APPLICABLE              USAPA V1 .00
**NOTE VALUE AND PHASING

DA FORM 7469-R, AUG 2002


---

                              BACK-UP POWER SYSTEM INSPECTION CHECKLIST

                                    For use of this form see TM 5-694 ; the proponent agency is COE .

PLANT/BUILDING                                    SECTION A - CUSTOMER DATA     3. JOB NUMBER
                                        2. LOCATION

4. EQUIPMENT                            5. CIRCUIT DESIGNATION                  6. DATE (YYYYMMDD)

7. TEST EQUIPMENT AND CALIBRATION DATE                                          8. TESTED BY

                                         SECTION B - EQUIPMENT DATA

9. MANUFACTURER                  10. STYLES/S .O .         11 . VOLTAGE RATING                         12 . CURRENT RATING

13. EQUIPMENT CLASSIFICATION     14 . FREQUENCY            15 . WET BULB TEMPERATURE 16 . DRY BULB TEMPERATURE

                              SECTION C - VISUAL AND ELECTRICALIMECHANICAL INSPECTION

17 . CHECK POINT                  COND'             NOTES         CHECK POINT                             COND'             NOTES

COMPONENT INSPECTION/TESTING                               WIRING VISUAL VERIFICATION

ENERGIZE AND TEST SYSTEM                                   UTILITY TRIP/GENERATOR BUILDING LOAD
INSTALLATION INSPECTION/TESTING                            TEST

                                                           TIGHTNESS OF BOLTED CONNECTIONS

GENERATOR CONTROLS AND                                     CHECK FOR PROPER SIZE BREAKER
FUNCTIONS

WIRING CONTINUITY TESTING                                  REFERENCE DRAWINGS

WORKING CLEARANCE                                          PROPER PHASING CONNECTIONS AND
                                                           COLOR CODE

SWITCHGEAR CONTROL FUNCTIONS

PERFORM AUTOMATIC TRANSFER        A. OPERATE NORMAL POWER
SYSTEM (ATS) FUNCTIONS UNDER THE  B. ALL GENERATORS OPERATE
ADJACENT CONDITIONS .

                                  C . GENERATORS 1 AND 2 OPERATE

                                  D . GENERATORS 2 AND 3 OPERATE

                                  E. GENERATORS 1 AND 3 OPERATE

                                  F. RETURN TO NORMAL POWER AFTER EACH OF THE ABOVE
                                  TESTS

                                  G . PARALLEL WITH UTILITY UPON RETURN TO NORMAL POWER
                                  (ITEMS B THROUGH E)

                                         SECTION D - ELECTRICAL TESTS

18.                                                        VOLTAGE AND CURRENT MEASUREMENTS
       MEASUREMENT DESCRIPTION
                                                    VOLTAGE*"                                             CURRENT"

                                  A-N B-N C-N A-B B-C C-A                       A                      B  C         N       G

                                  A-N B-N C-N A-B B-C C-A                       A                      B  C         N       G

19 . NOTES

1. CHECK FOR PROPER GROUNDING CONNECTIONS PRIOR TO ENERGIZING.

*CONDITION : A=ACCEPTABLE; R=NEEDS REPAIR, REPLACEMENT OR ADJUSTMENT; C=CORRECTED ; NA=NOT APPLICABLE                       USAPA V1 .00
'*NOTE VALUE AND PHASING

DA FORM 7470-R, AUG 2002


---

                            TRANSFER SWITCH INSPECTION CHECKLIST
                            For useof this form seeTM 5-694; the proponent agency is COE.

PLANT/BUILDING                                   SECTION A - CUSTOMER DATA  3. JOB NUMBER
                                        2. LOCATION

4. EQUIPMENT                            5. CIRCUIT DESIGNATION              6. DATE (YYYYMMDD)

7. TEST EQUIPMENT AND CALIBRATION DATE                                      8. TESTED BY

                                         SECTION B - EQUIPMENT DATA

9. MANUFACTURER             10 . STYLES/S .O.         11 . VOLTAGE RATING                  12 . CURRENT RATING

13. SWITCH RATING                                     14 . ENCLOSURE TYPE                       15. FREQUENCY

16.                         SECTION C - VISUAL AND ELECTRICALIMECHANICAL INSPECTION

            CHECK POINT           COND*        NOTES             CHECK POINT               COND*       NOTES

EXTERIOR OF EQUIPMENT                                 EQUIPMENT IDENTIFICATION

COMPLETENESS OF ASSEMBLY                              BRACING
INDICATING LIGHTS
SWITCH FOR FREEDOM OF MOVEMENT                        PROPER PHASE CONNECTIONS AND
                                                      COLOR CODE

                                                      ENVIRONMENTAL CLASSIFICATION

ELECTRICAL/MECHANICAL INTERLOCKS                      WORKING CLEARANCE

ADJUST TIMING SETTINGS                                ANCHORAGE

PROPER EQUIPMENT GROUNDING                            REFERENCE DRAWINGS

CONTACT RESISTANCE                                    PROPER LUBRICATION

TIGHTNESS OF BOLTED CONNECTIONS                       PT AND CONTROL FUSE SIZE

                                         SECTION D- ELECTRICAL TESTS

17 . INSULATION RESISTANCE        - A-GRD      B-GRD            C-GRD       A-B            B-C         C-A

              @     V

18 . NOTES

1 . SWITCH TRANSFERS ON LOSS OF NORMAL POWER AT SPECIFIED TIME DELAY.
2. SWITCH TRANSFER BACK TO NORMAL POWER ON RETURN OF NORMAL POWER SERVICE AT SPECIFIED TIME
DELAY.

3. AUXILIARY CONTACTS OPERATE CORRECTLY DURING NORMAL AND ABNORMAL POWER CONDITIONS.

*CONDITION : A=ACCEPTABLE ; R=NEEDS REPAIR, REPLACEMENT OR ADJUSTMENT; C=CORRECTED; NA=NOT APPLICABLE  USAPA V1 .00
DA FORM 7471-R, AUG 2002


---

                   UNINTERRUPTIBLE POWER SUPPLY (UPS) INSPECTION CHECKLIST

                                       For use of this form see TM 5694; the proponent agency is COE .

PLANT/BUILDING                                    SECTION A - CUSTOMER DATA              3. JOB NUMBER
                                        2. LOCATION

4. EQUIPMENT                            5. CIRCUIT DESIGNATION 16 . CIRCUIT DESIGNATION  7. DATE (YYYYMMDD)
                                                                                         9. TESTED BY
                                        FED TO         FED FROM

8. TEST EQUIPMENT AND CALIBRATION DATE

                                        SECTION B - EQUIPMENT DATA

10 . MANUFACTURER      11 . STYLES/S .O.               12. VOLTAGE RATING                13. kVA RATING

                       SECTION C - VISUAL AND ELECTRICALIMECHANICAL INSPECTION

14 . CHECK POINT                 COND'          NOTES  CHECK POINT                                      COND'  NOTES
                                                                                                               C-A
EXTERIOR OF EQUIPMENT                                  EQUIPMENT IDENTIFICATION

COMPLETENESS OF ASSEMBLY                               BRACING
                                                       PROPER PHASE CONNECTIONS AND
INDICATING LIGHTS                                      COLOR CODE
                                                       ENVIRONMENTAL CLASSIFICATION
SWITCH FOR FREEDOM OF MOVEMENT
MANUAL OPERATION OF CIRCUIT                            WORKING CLEARANCE
BREAKERS
TIMING SETTINGS                                        ANCHORAGE

PROPER GROUNDING                                       REFERENCE DRAWINGS

PROPER VOLTAGE CONNECTIONS                             CONTROL FUSE SIZE AND CONTINUITY

TIGHTNESS OF BOLTED CONNECTIONS                        VERIFY ALL TRANSFER SWITCH
TEST CIRCUIT BREAKERS WITH                             OPERATIONS
CURRENT INJECTION TESTER
                                        SECTION D - ELECTRICAL TESTS
15.
                   VAC (OUTPUT)         A-GRD   B-GRD  C-GRD                 A-B                        B-C

16 . NOTES

'CONDITION : A=ACCEPTABLE ; R=NEEDS REPAIR, REPLACEMENT OR ADJUSTMENT ; C=CORRECTED ; NA=NOT APPLICABLE        USAPA V1 .00

DA FORM 7472-R, AUG 2002


---

                                         BATTERY INSPECTION CHECKLIST

                                  For use of this form see TM 5-694 ; the proponent agency is COE .

1 . PLANT/BUILDING                               SECTION A - CUSTOMER DATA  3. JOB NUMBER
                                        2 . LOCATION

4. EQUIPMENT                            5. CIRCUIT DESIGNATION              6. DATE (YYYYMMDD)

7. TEST EQUIPMENT AND CALIBRATION DATE                                      8. TESTED BY

                                        SECTION B - EQUIPMENT DATA

9. MANUFACTURER           10. STYLES/S .O .       11 . VOLTAGE RATING                                12. CURRENT RATING

13. ENCLOSURE TYPE        14. FREQUENCY           15 . WET BULB TEMPERATURE 16. DRY BULB TEMPERATURE

                          SECTION C - VISUAL AND ELECTRICALIMECHANICAL INSPECTION

17. CHECK POINT                   COND* . NOTES                 CHECK POINT                          COND*               NOTES

EXTERIOR OF EQUIPMENT                             EQUIPMENT IDENTIFICATION

COMPLETENESS OF ASSEMBLY                          BRACING

ELECTROLYTE LEVEL                                 ENVIRONMENTAL CLASSIFICATION

VENTS SEALED AND PLUGS INSTALLED                  WORKING CLEARANCE

PROPER POLARITY CONNECTIONS                       ANCHORAGE

TIGHTNESS OF BOLTED CONNECTIONS                   CHECK FOR EXHAUST FAN IF IN
                                                  ENCLOSED ENVIRONMENT
PROPER GROUNDING
CHECK FOR SHOWER AND EYEWASH                      REFERENCE DRAWINGS
STATION
TEST CIRCUIT BREAKERS WITH                        CHECK FOR ACCESS TO BATTERIES FOR
CURRENT INJECTION TESTER                          O&M
TEST CIRCUIT BREAKERS
                                                  CHECK UPS CONTROL PANEL ALARMS
18 .
       MEASUREMENT DESCRIPTION                    TEST TRANSFER SWITCH

      BATTERY VOLTAGE & CURRENT         SECTION D - ELECTRICAL TESTS

                                                  VOLTAGE AND CURRENT MEASUREMENTS

                                                  VOLTAGE**                                          CURRENT'*

                                        POSITIVE                NEGATIVE    POSITIVE                 NEGATIVE            GROUND

19. NOTES

1. MEASURE RESISTANCE BETWEEN CELL CONNECTIONS .
2. MEASURE VOLTAGE ACROSS EACH CELL.
3. CHECK SPECIFIC GRAVITY OF EACH CELL.
4. TEST AND MAINTAIN BATTERY (CELLS) IN ACCORDANCE WITH MANUFACTURERS RECOMMENDATIONS .

" *CONDITION : A=ACCEPTABLE ; R=NEEDS REPAIR, REPLACEMENT OR ADJUSTMENT ; C=CORRECTED ; NA=NOT APPLICABLE                USAPA V1 .00

     NOTE VALUE AND PHASING

  DA FORM 7473-R, AUG 2002


---

              UNINTERRUPTIBLE POWER SUPPLY (UPS) SWITCHBOARD INSPECTION CHECKLIST

                                                 For use of this form see TM 5-694; the proponent agency is COE.

PLANT/BUILDING                                   SECTION A - CUSTOMER DATA    3 . JOB NUMBER
                                       2 . LOCATION

4. EQUIPMENT                           5 . CIRCUIT DESIGNATION                6 . DATE (YYYYMMDD)

7. TEST EQUIPMENT TYPE/BRAND AND CALIBRATION DATE                             8. TESTED BY

                                              SECTION B - EQUIPMENT DATA

9 . MANUFACTURER               10 . STYLES/S .O.         11 . VOLTAGE RATING                12. CURRENT RATING

13. BUS RATING/CB INTERRUPTING RATING

                             SECTION C -VISUAL AND ELECTRICALIMECHANICAL INSPECTION

14 . CHECK POINT                       COND"      NOTES         CHECK POINT                        COND`          NOTES

EXTERIOR OF EQUIPMENT                                    BRACING
                                                         PROPER PHASE CONNECTION AND
COMPLETENESS OF ASSEMBLY                                 COLOR CODE
                                                         ENVIRONMENTAL CLASSIFICATION
INDICATING LIGHTS
MANUAL OPERATION OF CIRCUIT                              WORKING CLEARANCE
BREAKERS
PROPER GROUNDING                                         ANCHORAGE

CONDITION OF INSULATION                                  REFERENCE DRAWINGS

PROPER VOLTAGE CONNECTIONS                               VERIFY PROPER SIZES OF BREAKERS AND
TIGHTNESS OF BOLTED CONNECTIONS                          FUSES

                                                         CHECK PROPER EQUIPMENT GROUNDING
                                                         TO GROUNDING BUS

EQUIPMENT IDENTIFICATION

                                              SECTION D - ELECTRICAL TESTS

15. BUS INSULATION RESISTANCE          A-GRD       B-GRD        C-GRD         A-B             B-C                 C-A

                  V

16 . NOTES

1. TEST ALL CIRCUIT BREAKERS ACCORDING TO MANUFACTURER'S RECOMMENDATIONS .

'CONDITION : A=ACCEPTABLE ; R=NEEDS REPAIR, REPLACEMENT OR ADJUSTMENT ; C=CORRECTED; NA=NOT APPLICABLE            USAPA V1 .00

DA FORM 7474-R, AUG 2002


---

                UNINTERRUPTIBLE POWER SUPPLY (UPS) SYSTEM INSPECTION CHECKLIST

                                             For use of this form see TM 5-694; the proponent agency is COE .

PLANT/BUILDING                              SECTION A - CUSTOMER DATA   3. JOB NUMBER
                                   2 . LOCATION

4. EQUIPMENT                       5 . CIRCUIT DESIGNATION              6. DATE (YYYYMMDD)

7. TEST EQUIPMENT                                                       8. TESTED BY

                                SECTION B - VISUAL AND ELECTRICALlMECHANICAL INSPECTION

9. CHECK POINT                     COND*  NOTES             CHECK POINT                        COND*              NOTES

COMPONENT INSPECTIOWTESTING                      ENERGIZE AND TEST SYSTEM

INSTALLATION INSPECTION/TESTING                  UTILITY TRIP TEST
WIRING VISUAL VERIFICATION
GENERATOR CONTROL FUNCTIONS                      LOADED TRANSFER TEST (NORMAL,
                                                 EMERGENCY & RETURN)

                                                 TIGHTNESS OF BOLTED CONNECTIONS

LOADING UPS TEST                                 BATTERY DISCHARGE TEST

DISCONNECT RECTIFIERS & INVERTERS                TEST ALL UPS DIAGNOSTIC FAULT
:EPARATELY. DOES SYSTEM OPERATE                  INDICATORS

  ORRECTLY?

                                          SECTION D - ELECTRICAL TESTS

10.                                A-N B-N C-N A-B B-C C-A              A                B  C                  N  G
                     UPS INPUT

            UPS OUTPUT             A-N B-N C-N A-B B-C C -A             A                B  C                  N  G

UPS SWITCHBOARD HARMONIC (THD) A-N B-N C-N A-B B-C CA A B C N G

11 . NOTES

*CONDITION : A=ACCEPTABLE ; R=NEEDS REPAIR, REPLACEMENT OR ADJUSTMENT ; C=CORRECTED; NA=NOT APPLICABLE            USAPA V1 .00
**NOTE VALUE AND PHASING

DA FORM 7475-R, AUG 2002


---

PIN : 080195-000


--- 