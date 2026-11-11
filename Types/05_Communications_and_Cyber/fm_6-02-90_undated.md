# fm_6-02-90_undated  UHF
TACSAT
  /DAMA

MULTI-SERVICE TACTICS,
     TECHNIQUES, AND

PROCEDURES FOR ULTRA
      HIGH FREQUENCY

TACTICAL SATELLITE AND
    DEMAND ASSIGNED
     MULTIPLE ACCESS
         OPERATIONS

                 FM 6-02.90
              MCRP 3-40.3G

                NTTP 6-02.9
             AFTTP(I) 3-2.53

    AUGUST 2004

DISTRIBUTION RESTRICTION: Approved for public release;
distribution is unlimited.


---

                                     FOREWORD

    This publication has been prepared under our direction for use by our respective
commands and other commands as appropriate.

ROBERT W. MIXON, JR.            ROBERT E. SCHMIDLE
Major General, US Army          Brigadier General, USMC
Deputy Director/Chief of Staff  Director
                                Expeditionary Force
    Futures Center
US Army Training and Doctrine       Development Center

    Center

JOHN M. KELLY                   STEPHEN G. CULLEN
Rear Admiral, USN               Colonel, USAF
Commander                       Vice Commander
Navy Warfare Development        Headquarters Air Force

    Command                         Doctrine Center

This publication is available through the Army
           at the Army Knowledge Online

   (www.us.army.mil) and General Dennis J.
 Reimer Digital Library (www.adtdl.army.mil)

     Web sites, through the ALSA Web site
 (www.alsa.mil), and through the Air Force at

         the Air Force Publishing Web site
              (www.e-publishing.af.mil).


---

                                         PREFACE

1. Scope

    The intent of this publication is to assist planners and users at the joint task force,
Service component, and other functional components by providing an improved and
unified process for planning, managing, and using ultra high frequency (UHF) tactical
satellite (TACSAT) frequencies with special emphasis on maximizing the use of this
limited resource.

2. Purpose

    Lessons learned and collected by Joint Staff J-6 from numerous joint operations
identified significant problems with planning and utilizing the limited number of UHF
TACSAT frequencies. Current methods and procedures based on use, geography,
channel size, demand access, and time have proved difficult to integrate and require
extensive manual tracking and manipulation. These inefficiencies contribute to the
shortage of this critical command and control resource. This multi-Service tactics,
techniques, and procedures (MTTP) publication consolidates and standardizes Service
tactics, techniques, and procedures (TTP) for planning and executing UHF TACSAT
frequency management operations. It serves as a planning and execution guide and a
framework for coordination and synchronization consistent with current Joint doctrine.

3. Application

    a. This publication is applicable to unit level UHF TACSAT planners and users
throughout the joint force.

    b. The United States (U.S.) Army, Marine Corps, Navy, and Air Force approved
this multi-Service publication.

4. Implementation Plan

    Participating Service command offices of primary responsibility review this
publication, validate the information, and reference and incorporate it into Service
manuals, regulations, and curricula as follows:

    Army. Upon approval and authentication, this publication incorporates its

procedures in the U.S. Army Doctrinal and Training Literature Program as directed by
the Commander, U.S. Army Training and Doctrine Command (TRADOC). Distribution
is in accordance with applicable directives and the initial distribution number (IDN) on
the authentication page.

    Marine Corps. The Marine Corps incorporates the procedures in this publication

in U.S. Marine Corps doctrinal and training publications as directed by the
Commanding General, U.S. Marine Corps Combat Development Command (MCCDC).
Distribution is in accordance with the Marine Corps Publication Distribution System.

Marine Corps PCN: 144 000148 00

                                                                                                                                       i


---

    Navy. The Navy incorporates these procedures in U.S. Navy training and doctrine

publications as directed by the Commander, Navy Warfare Development Command
(NWDC [I5]). Distribution is in accordance with Military Standard Requisition and
Issue Procedure Desk Guide (MILSTRIP Desk Guide) Navy Supplement Publication-
409 (NAV SUP P-409) and NTTP 1-01, the Navy Warfare library.

    Air Force. The Air Force incorporates the procedures in this publication in

accordance with applicable governing directives. Distribution is in accordance with Air
Force Instruction (AFI) 33-360.

5. User Information

    a. TRADOC, MCCDC, NWDC, Headquarters Air Force Doctrine Center (AFDC),
and the Air Land Sea Application (ALSA) Center developed this publication with the
joint participation of the approving Service commands. ALSA reviews and updates this
publication as necessary.

    b. This publication reflects current joint and Service doctrine, command and control
organizations, facilities, personnel, responsibilities, and procedures. Changes in Service
protocol, appropriately reflected in joint and Service publications, will be incorporated
in revisions to this document.

     ii


---

    c. We encourage recommended changes for improving this publication. For each
recommendation, include the specific page and paragraph and provide a rationale. Send
comments and recommendations directly to—

                                                    Army

          Commander
          US Army Training and Doctrine Command
          ATTN: AFTC-RD
          Fort Monroe, VA 23651-5000
          DSN 680-3951 COMM (757) 788-3951
          E-mail: doctrine@monroe.army.mil

                                               Marine Corps

          Commanding General
          US Marine Corps Combat Development Command
          ATTN: C42
          3300 Russell Road, Suite 318A
          Quantico, VA 22134-5021
          DSN 278-6233/6234 COMM (703) 784-6234
          E-mail: deputydirectordoctrine@mccdc.usmc.mil

                                                     Navy

          Commander
          Navy Warfare Development Command
          ATTN: N5
          686 Cushing Road
          Newport, RI 02841-1207
          DSN 948-1164/4189 COMM (401) 841-1164/4189
          E-mail: alsapubs@nwdc.navy.mil

                                                  Air Force

          HQ AFDC/DJ
          155 North Twining Street
          Maxwell AFB AL 36112-6112
          DSN 493-7442 Comm: (334) 953-7442
          E-mail: afdc.dj@maxwell.af.mil

                                                    ALSA

          ALSA Center
          ATTN: Director
          114 Andrews Street
          Langley AFB, VA 23665-2785
          DSN 575-0902 COMM (757) 225-0902
          E-mail: alsa.director@langley.af.mil

                                                                                                                                     iii


---

                                                                                         FM 6-02.90
                                                                                    MCRP 3-40.3G

                                                                                       NTTP 6-02.9
                                                                                   AFTTP(I) 3-2.53

FM 6-02.90            U.S. Army Training and Doctrine Command
MCRP 3-40.3G                                           Fort Monroe, Virginia
NTTP 6-02.9
AFTTP(I) 3-2.53  Marine Corps Combat Development Command
                                                            Quantico, Virginia

                             Navy Warfare Development Command
                                                     Newport, Rhode Island

                          Headquarters, Air Force Doctrine Center
                                     Maxwell Air Force Base, Alabama

                                                               31 August 2004

                 (UHF TACSAT/DAMA)

MULTI-SERVICE TACTICS, TECHNIQUES, AND PROCEDURES
 FOR ULTRA HIGH FREQUENCY TACTICAL SATELLITE AND
    DEMAND ASSIGNED MULTIPLE ACCESS OPERATIONS

                 TABLE OF CONTENTS

                                                                                   Page

EXECUTIVE SUMMARY ........................................................................................................IX

CHAPTER I        OVERVIEW/TERMINOLOGY ............................................................. I-1
                 Introduction .......................................................................................I-1
                 Definition of Key Terms ....................................................................I-1
                 Organizations and Functions............................................................I-2
                 UHF TACSAT Usage Guidance........................................................I-6
                 Description of UHF TACSAT Capabilities..................................... I-12
                 Military-Standards (MIL-STD) for DAMA.....................................I-15
                 Waveforms .......................................................................................I-15
                 Slave Channels ................................................................................I-23

CHAPTER II       COMMUNICATIONS PLANNING CYCLE ........................................ II-1
                 Assess Force Structure Requirements ............................................II-1

Distribution Restriction: Approved for public release; distribution is unlimited.
iv


---

CHAPTER III  Acquire Resources ............................................................................ II-1
             Manage Resources............................................................................ II-4
APPENDIX A   Issue Resources To Users ................................................................ II-4
APPENDIX B
APPENDIX C   TACSAT RADIO EQUIPMENT AND OPERATIONS....................... III-1
             Terminal .......................................................................................... III-1
APPENDIX D   Terminal Set up and Operations .................................................... III-3
APPENDIX E   Terminal Base Address (TBA) Management ................................. III-6
             Orderwire (OW) Key Management ................................................ III-7
APPENDIX F   Samples of Checklists ..................................................................... III-8
             Accessing a Dedicated Channel ...................................................... III-9
             Accessing a DAMA Channel ......................................................... III-10
             COMSEC Equipment .................................................................... III-14

             SATELLITE CHANNEL AUTHORIZATION LIST .............................A-1

             INFORMATION REQUEST CODES .................................................B-1

             AN/PRC-117F RADIOS.....................................................................C-1
             AN/PRC-117F Dedicated UHF SATCOM Operation .....................C-1
             UHF Dedicated SATCOM Programming Checklist .......................C-3
             Dedicated UHF SATCOM Operational Steps.................................C-5
             SATCOM 181B Data Operation Using KG-84 COMSEC

                   and Continuous Phase Modulation ..........................................C-6
             AN/PSC-117F DAMA UHF SATCOM.............................................C-8

             AN/PSC-5 SERIES RADIOS .............................................................D-1
             Line of Sight (LOS) Operations .......................................................D-1
             SATCOM Operations .......................................................................D-2
             DAMA 5-kHz Operations .................................................................D-3

             LST-5D RADIOS ...............................................................................E-1
             LST-5D LOS Procedures (Updated: 02 APR 98).............................E-1
             LST-5D SATCOM Procedures .........................................................E-3
             Key Variable Zeroization .................................................................E-5
             LST-5D DAMA 25-kHz AC Procedures (For MOD-3 and

                   Below) ........................................................................................E-5
             Cold Start Initialization...................................................................E-6
             Loading LST-5D for DAMA Use ......................................................E-6
             Programming Operating Modes ......................................................E-6
             Fill Procedures Using A KYX-15 .....................................................E-9
             Key Variable Zeroization .................................................................E-9

             AN/ARC-231/SKYFIRE ..................................................................... F-1
             Skyfire Operator Training ............................................................... F-1
             Skyfire Characteristics and Capabilities ........................................ F-1
             Capabilities and Features................................................................ F-1
             Control/Fill Panel ............................................................................. F-2

                                                                                                                    v


---

APPENDIX G  Loading COMSEC ............................................................................F-2
APPENDIX H  Download Presets .............................................................................F-4
APPENDIX J  Save Presets Manually.....................................................................F-5
APPENDIX K  Brightness Adjustment ....................................................................F-6
REFERENCES  LOS Operations ................................................................................F-7
GLOSSARY    LOS Guard Operations.....................................................................F-8
INDEX       SATCOM Operations........................................................................F-9
FIGURES
            AN/WSC-3 ........................................................................................ G-1
vi          Setting Up for DAMA ...................................................................... G-1

            EMI CHARACTERIZATION CHECKLIST ........................................ H-1

            CUT SHEETS .................................................................................... J-1

            PRIORITIZATION SCHEME............................................................. K-1

            ..........................................................................................References-1

            ..............................................................................................Glossary-1

            ....................................................................................................Index-1

            Figure I-1. UHF SATCOM Functional Organization Chart ......... I-3
            Figure I-2. Short-Range (1 to 20 kilometers) System/Mode

                  Decision Matrix ........................................................................ I-9
            Figure I-3. Medium-Range (20 to 50 kilometers)

                  System/Mode Decision Matrix ............................................... I-10
            Figure I-4. Long-Range (50 to 150 kilometers)

                  System/Mode Decision Matrix ............................................... I-11
            Figure I-5. Over-the-Horizon (150 to 10,000 kilometers)

                  System/Mode Decision Matrix ............................................... I-12
            Figure I-6. Military UHF Satellite Constellation and

                  Coverage Areas....................................................................... I-13
            Figure I-7. Waveform Breakout for 5-kHz DAMA....................... I-16
            Figure I-8. Waveform Communications for 5-kHz....................... I-17
            Figure I-9. Waveform Communications for 25-kHz DAMA ........ I-18
            Figure I-10. A Segment Slots ........................................................ I-19
            Figure I-11. B Segment Slots ........................................................ I-20
            Figure I-12. C Segment Slots ........................................................ I-21
            Figure I-13. Typical Navy 25-kHz DAMA Assignments.............. I-22
            Figure I-14. Example of 25-kHz TDMA DAMA

                  Assignments ........................................................................... I-23
            Figure I-15. Slave Channels for 25-kHz DAMA .......................... I-23
            Figure I-16. Communications on 25-kHz DAMA Slave

                  Channels ................................................................................. I-25
            Figure II-1. Communications Planning Cycle............................... II-1
            Figure III-1. AN/PRC-117F........................................................... III-3
            Figure III-2. AN/PSC-5 Series ...................................................... III-3
            Figure III-3. LST-5 ........................................................................ III-3
            Figure III-4. AN/ARC-231 ............................................................. III-4


---

TABLES  Figure III-5. AN/WSC-3 .................................................................III-4
        Figure III-6. TD-1271B/U ..............................................................III-4
        Figure III-7. MD-1324....................................................................III-5
        Figure III-8. DMR ..........................................................................III-5
        Figure III-9. USC-42(V)1, 2, 3 .......................................................III-6
        Figure III-10. AN/ARC-210............................................................III-6
        Figure C-1. UHF SATCOM Programming Sub Menu.................. C-4
        Figure C-2. SATCOM Programming Menu .................................. C-5
        Figure C-3. Dedicated UHF SATCOM Displays........................... C-7
        Figure C-4. Overall DAMA Programming Menu Tree ................. C-9
        Figure C-5. DAMA Net Preset Programming Menu Tree.......... C-11
        Figure C-6. DAMA Port Configuration Preset

              Programming Menu Tree ..................................................... C-14
        Figure C-7. DAMA Destination Preset Programming Menu

              Tree ........................................................................................ C-16
        Figure C-8. DAMA Defaults Programming Menu Tree ............. C-17
        Figure C-9. DAMA 25-kHz AC Call Menu .................................. C-23
        Figure C-10. Twenty-five-kHz AC Paging and Link Test .......... C-25
        Figure C-11. Call Menu 5-kHz DAMA ........................................ C-29
        Figure C-12. MSG Service Call Menu, 5-kHz DAMA................. C-32
        Figure C-13. DAMA Network State Displays, 5-kHz and

              25-kHz ................................................................................... C-33
        Figure C-14. DAMA Service State Displays, 25-kHz ................. C-34
        Figure C-15. DAMA Service State Displays, 5-kHz ................... C-35
        Figure F-1. Control/Fill Panel ........................................................F-2
        Figure J-1. Sample of LOS Cut Sheet ............................................J-1
        Figure J-2. Sample of SATCOM Cut Sheet ...................................J-2
        Figure J-3. Sample of DAMA Cut Sheet page 1 ............................J-3
        Figure J-4. Sample of DAMA Cut Sheet page 2 ............................J-4

        Table I-1. Voice/Data Planning Matrix ...........................................I-8
        Table III-1a. Radio Equipment......................................................III-1
        Table III-1b. Radio Equipment......................................................III-1
        Table III-1c. Radio Equipment ......................................................III-2
        Table III-2. OW Key Positions.......................................................III-8
        Table III-3. Checklist for 5-kHz DAMA ........................................III-8
        Table III-4. Checklist for 25-kHz DAMA ......................................III-9
        Table III-5. DAMA Points of Contact ..........................................III-12
        Table A-1. Satellite Channel (Home Channel)

              Authorization List................................................................... A-1
        Table B-1. Information Request Codes ......................................... B-1
        Table B-2. Configuration Codes..................................................... B-7
        Table C-1. Dedicated UHF SATCOM Capabilities....................... C-1
        Table C-2. MIL-STD 188-181B Data Rate Options, 5-kHz .......... C-2
        Table C-3. MIL-STD 188-181B Data Rate Options, 25-kHz ........ C-2
        Table C-4. UHF SATCOM Programming Parameters ................. C-3
        Table C-5. UHF Satellite Positions ............................................... C-6
        Table C-6. AN/PRC-117F DAMA SATCOM Capabilities............. C-8

                                                                                                             vii


---

                             Table C-7. DAMA Programming Checklist ................................. C-10
                             Table C-8. DAMA Net Preset Parameters .................................. C-12
                             Table C-9. DAMA Port Configuration Preset Parameters ......... C-13
                             Table C-10. DAMA Destination Preset Programming

                                    Checklist ................................................................................C-15
                             Table C-11. DAMA Defaults Programming Checklist................ C-16
                             Table C-12. DAMA Ranging Methods ......................................... C-18
                             Table C-13. Link Test Data Rates, 25-kHz DAMA..................... C-26
                             Table D-1. Lind of Sight (LOS) Operations................................... D-1
                             Table D-2. I/O Data Rates for 5-kHz DAMA................................. D-3
                             Table D-3. SYN/ASYN Settings .....................................................D-6
                             Table D-4. Messages, 5-kHz DAMA .............................................. D-9
                             Table D-5. Service Assigned Errors and Warnings .................... D-12
                             Table D-6. Message Queue Errors ...............................................D-12
                             Table D-7. Hot Keys, 5-kHz DAMA .............................................D-12
                             Table D-8. 5-kHz DAMA Operations (Same

                                    Footprint/MHOP) Guide .......................................................D-22
                             Table H-1. EMI Characterization Checklist ................................. H-1
                             Table K-1. SATCOM Priority Table .............................................. K-1

viii


---

                              EXECUTIVE SUMMARY

                       UHF TACSAT/DAMA

              Multi-Service Tactics, Techniques, and Procedures
                      for UHF TACSAT and DAMA Operations

    Chapter I identifies key players in the management of tactical satellite (TACSAT)
resources and offers critical guidance for the user to optimize this scarce resource. The
usage guidance centers on the need to consider other communications capabilities before
requesting access to TACSAT resources. The chapter concludes with sections on
TACSAT capabilities, military standards, waveforms, and slave channels. These
sections include discussions of narrowband and wideband channels, the utilization of
dedicated and demand assigned multiple access (DAMA) services, and descriptions of 5-
kHz and 25-kHz waveforms.

    Chapter II provides a detailed look at the communications planning cycle of assessing
force structure, acquiring resources, managing resources, and issuing resources to users.
It discusses DAMA emission control, terminal base address (TBA) management and
precedence, common, and private networks, and disadvantaged users.

    Chapter III provides techniques and procedures for UHF TACSAT equipment and
operations, TBA management, orderwire (OW) key management, and communications
security equipment. It also provides samples of 5- and 25-kHz DAMA checklists,
accessing dedicated and DAMA channels. The equipment list provides the planner with
the capability to assess communications interoperability of various elements in a Joint
Task Force (JTF). The point of contact list provides TACSAT users a means of
troubleshooting a variety of common problems with UHF TACSAT operations.

    The appendices provide samples of checklists, troubleshooting guides, and other
planning resources.

                                                                                                                                      ix


---

                             PROGRAM PARTICIPANTS

    The following commands and agencies participated in the development of this
publication:

                                                        Joint

    U.S. Joint Forces Command, Norfolk, Virginia
    U.S. Central Command, MacDill Air Force Base, Florida
    U.S. Strategic Command, Offutt Air Force Base, Nebraska
    U.S. Special Operations Command, MacDill Air Force Base, Florida
    Joint Spectrum Center, Annapolis, Maryland

                                                       Army

    Headquarters, U.S. Army, Washington, DC
    U.S. Army Training and Doctrine Command, Fort Monroe, Virginia
    U.S. Army Space Command, Colorado Springs, Colorado
    U.S. Army Forces Command, Fort McPherson, Georgia
    U.S. Army Special Operations Command (USASOC), Fort Bragg, North Carolina
    TRADOC System Manager for Satellite Communications, Fort Gordon, Georgia
    Headquarters, United States Army Network Enterprise Technology Command/
    9th Army Signal Command, Fort Huachuca, Arizona
    87th Training Support Division, 2d Brigade, Birmingham, Alabama

                                                 Marine Corps

    Headquarters, U.S. Marine Corps, Washington, DC
    Marine Corps Combat Development Command, Quantico, Virginia
    II Marine Expeditionary Force, Camp Lejeune, North Carolina
    Marine Forces Atlantic, Norfolk, Virginia

                                                        Navy

    Space and Naval Warfare Center, San Diego, California

                                                    Air Force

    Air Force Doctrine Center, Detachment 1, Langley Air Force Base, Virginia
    Air Combat Command/SCCF, Langley Air Force Base, Virginia
    Air Force Frequency Management Agency, Alexandria, Virginia

x


---

                                                  Chapter I

                              Overview/Terminology

1. Introduction

    This multi-Service tactics, techniques, and procedures (MTTP) publication serves as
a preparation and execution guide for the communications planner and the terminal
operators. It explores solutions to the following problems:

    a. Proper preparation and utilization for the limited number of ultra high frequency
(UHF) tactical satellite (TACSAT) resources.

    b. Greater efficiency in the utilization of this critical command and control
resource.

    c. Proper consolidation and standardization of Service tactics, techniques, and
procedures for planning an execution of UHF TACSAT management.

2. Definition of Key Terms

    a. Communications planner. For purposes of this publication, the term
“communications planner” refers to individuals responsible for developing UHF satellite
communications (SATCOM) requirements in support of the unified combatant
commander operations plan (OPLAN), exercise plan (EXPLAN), or emerging operations
(EMOP), including unit through component level. Communications planners may be
referred to in varying Service elements as frequency managers, signal noncommissioned
officer, signal officer, S6, J-6, spectrum manager, communication chief, or other similar
term.

    b. Terminal operator. For purposes of this publication, the term “terminal
operator” refers to any individual who interacts (directly or indirectly) with a UHF
TACSAT terminal.

    c. Frequency management. The term “frequency management” refers to the
process of requesting, issuing, and managing frequency resources in accordance with
joint policy, United States (US) and international law, and Service procedures. A
SATCOM channel consists of two frequencies managed as individual frequencies.

    d. Demand assigned multiple access (DAMA). DAMA is a technique used to
increase the number of users a limited “pool” of satellite transponder space can support.
The ability to share bandwidth is based on the assumption that not all users require
simultaneous access to communication channels. DAMA systems, quickly and
transparently, assign communication links or circuits to a network control system based
on requests received from user terminals. Once a circuit is not in use, the channels are
immediately returned to the central pool for reuse. Using DAMA allows many
subscribers to be served using a fraction of the satellite resources required by dedicated,
point-to-point signal-channel-carrier networks, thus reducing the costs of satellite
networking.

                                                                                                                                    I-1


---

    e. Naval Computer and Telecommunications Area Master Station
(NCTAMS)/Satellite Management Center (SMC). The NCTAMS is a station tasked to
install, operate, man, and maintain satellite ground stations. The SMC is the DAMA
controller office responsible for configuring, monitoring, and troubleshooting DAMA
network assignments.

    f. Joint UHF Military Satellite Communications (MILSATCOM) Network
Integrated (JMINI) controller. The JMINI is the hardware and software suite used by
the NCTAMS-SMC to manage 5-kilohertz (kHz) and 25-kHz DAMA networks. It is a
multiplexer controlling the technical configuration of the DAMA satellite channels to
provide functionality of the system.

    g. Satellite access request (SAR). The SAR is a formal request, submitted in
preformatted message form, to the UCC communications planning office by a using unit
through the chain of command. The SAR requests satellite resources to support valid
mission requirements.

    h. Satellite access assignment (SAA). The formal SAA assignment message
assigning specific resources to a unit for a specific period of time. The SAA is issued by
the regional SATCOM support center (RSSC). It is sent to the requesting unit and the
NCTAMS for controller configuring and system monitoring .

    i. Net control station (NCS). The NCS is an individual, office, communications
control center, or command responsible for facilitating shared access between terminal
operators for a particular UHF SATCOM network.

    j. Satellite database (SDB). The SDB is the base document listing validated
requirements as a result of UCC mission analysis. The document is reviewed annually
to ensure current resource requirements are included.

3. Organizations and Functions

    The Joint Chiefs of Staff (JCS), United States Strategic Command (USSTRATCOM),
UCC, joint frequency management office (JFMO), global SATCOM support center
(GSSC)/RSSC, joint task force (JTF), NCTAMS, combatant commands (COCOM),
communications planners, and terminal operators play key roles in planning and
managing UHF SATCOM requirements and resources. The responsibilities of each
organization are summarized below. The functional relationships between these
organizations are depicted in Figure I-1.

I-2


---

                         Figure I-1. UHF SATCOM Functional Organization Chart

    a. Joint Staff/J-6.
         (1) Provide and maintain a staffing capability to perform the following:
                (a) Monitor, coordinate, and formulate actions – approved by the Chairman

of the Joint Chiefs of Staff (CJCS) – for strategic, tactical, and contingency SATCOM
operational access.

                (b) Develop a coordinated Joint Staff position on SATCOM issues having
operational implications.

                (c) Implement CJCS adjudication directives for SATCOM resources.
                (d) Monitor the health and operational status of SATCOM systems.
         (2) Assist non-Department of Defense (DOD) users in accessing SATCOM
capabilities.
         (3) Ensure near-real-time visibility of all SATCOM capabilities and users.

                                                                                                                                    I-3


---

         (4) Assist in resolving international SATCOM interference issues that cannot be
resolved by COCOM.

         (5) Manage the SATCOM requirements process, including the necessary
requirements for commercial SATCOM assets for contingency and war situations.

         (6) Co-chair the monthly Joint SATCOM panel with USSTRATCOM.

         (7) Co-chair the annual joint revalidation and approval for planning purposes of
all SATCOM access requirements contained in the SDB with USSTRATCOM.

         (8) Review and assess the results of the UCC annual review of SATCOM access
requirements. Provide recommendations and corrective actions to the CJCS.

         (9) Chair joint working groups addressing SATCOM issues in support of CJCS
responsibilities.

         (10) Coordinate on USSTRATCOM’s recommendations for initial positioning of
satellites.

         (11) Coordinate the communications message processor (CMP) within the Joint
Staff. Oversee the coordination of CMP actions between the Services.

    b. USSTRATCOM.

         (1) Manage and dynamically assign SATCOM resources commensurate with its
role as the single point of contact in military space operational matters.

         (2) Monitor resource contention among users and facilitate resolution. Arbitrate
conflicts resulting from apportionment decisions, allocation, and spacecraft positioning.
Forward unresolved issues to the Joint Staff for adjudication by the CJCS.

         (3) Serve as SATCOM operational manager for the day-to-day management of
operational SATCOM resources. (See Appendix B for definitions of functions and
responsibilities.)

         (4) Serve as the advocate for, and develop annual assessment of, SATCOM
systems and capability requirements for SATCOM systems supporting operational
requirements, as described at Appendix E.

         (5) Maintain a direct liaison with the Services, Joint Staff, Defense Information
Systems Agency (DISA), Office of the Secretary of Defense, and users of SATCOM
systems to identify system provisioning requirements, support DOD SATCOM
architecture development, and integrate SATCOM into the Global Information
Grid/Defense Information Systems Network.

         (6) Coordinate the CMP schedules and issues with the COCOM annually.
Prioritize requirements, indicate shortfalls and operational impacts, and provide
accurate information to the Services and DISA.

    c. Unified Combatant Command (UCC).

         (1) Support relationship. Per JP 0-2, "Unified Action Armed Forces
(UNAFF)," the Secretary of defense establishes support command relationships between
combatant commanders for the planning and exeecution of joint operations. Operations
Allied Force and Iraqi Freedom highlighted the need to properly manage SATCOM
bandwidth, a challenge that may be exacerbated if the supported / supporting

I-4


---

relationship is not clearly defined. With regard to SATCOM support from
USSTRATCOM, the UCC typically will be the supported commander and, unless
limited by the establishing directive, will "have the authority to exercise general
direction of the supporting effort." When designated as the supporting commander,
Commander USSTRATCOM will determine the "methods, procedures, and
communications to be employed in providing this support" and "provide the
requested capabilities, as available, to assist the supported commander to
accomplish missions requiring additional resources."

         (2) Conduct annual reviews of SATCOM requirements for each validated
OPLAN, concept of operation plan, or operational architecture in accordance with the
joint strategic capabilities plan and CJCSM 3122.01.

         (3) Identify shortfalls from apportioned SATCOM capacity and Joint Strategic
Capabilities Plan guidelines. Ensure SATCOM requirements are consistent with
current plans and have a validated SDB number.

         (4) Consolidate and prioritize all SATCOM requirements needed to execute the
referenced plan or mission, including requirements of components and supporting
COCOM, Services, Defense agencies, and exercise and training requirements.

         (5) Forward a list of prioritized requirements, including requirements that could
not be filled using apportioned assets, to USSTRATCOM. Provide an information copy
to Joint Staff/J-6 with the annual SDB revalidation. DISA assists by providing a mix of
media assessments and modeling support.

         (6) Provide operational control of subnetworks for apportioned SATCOM
resources including—

                (a) Manage apportioned SATCOM capabilities.

                (b) Develop allocation plans and allocate apportioned SATCOM assets.

                (c) Establish access priorities for subordinate units according to appropriate
OPLAN, concept of operation plan, or mission requirements.

         (7) Adjudicate SATCOM access conflicts within the respective commands.

         (8) Ensure component communications staffs are trained to manage apportioned
SATCOM resources.

         (9) Prepare an annual report to DISA on commercial SATCOM operational use
and associated costs. Provide an information copy to the Joint Staff/J-6 and the
Assistant Secretary of Defense (NII). Submit the reports in the first quarter of each
fiscal year to DISA. DISA consolidates the reports into one comprehensive report and
submits it (annually) to the Joint Staff/J-6 and the Assistant Secretary of Defense.

         (10) Ensure proper coordination is routinely employed to obtain, defend, and
renew host nation approval for the various SATCOM systems employed by DOD.
Determine required coordination based on area of responsibility with the SATCOM
operational manager and its SATCOM system experts, the Services, and DISA.

         (11) Provide an applicable satellite, terminal, control, and network management
segment information for CMP development and updates.

                                                                                                                                    I-5


---

    d. GSSC/RSSC.
         (1) Perform 24-hour operations functions.
         (2) Plan and manage communications for the UCC.
         (3) Process SARs and issue SAAs.
         (4) Provide apportionment oversight for the UCCs.

    e. JTF.
         (1) Exercise control over joint communications systems and establish and

maintain joint circuits, per unified command J-6 guidance.
         (2) Submit frequency requirements to the theater JFMO.
         (3) Validate, consolidate, prioritize, and forward UHF TACSAT requirements to

the COCOM for channel allocation.
    f. JFMO.
         (1) Provide frequency clearance for apportioned TACSAT channels.
         (2) Assist users in resolving electromagnetic interference (EMI).
    g. NCTAMS.
         (1) Configure communications plans for the GSSC/RSSC.
         (2) Execute communications security (COMSEC) rollovers.
         (3) Provide EMI characterization.
         (4) Monitor DAMA control system performance.
         (5) Maintain DAMA control system equipment.
    h. Component Command.
         (1) Develop communications plans supporting UCC OPLAN/EXPLAN/EMOP.
         (2) Validate and rank component SARs.
    i. Communications Planners.
         (1) Identify resource requirements.
         (2) Submit SARs.
         (3) Perform local frequency deconfliction.

4. UHF TACSAT Usage Guidance

    a. UHF TACSAT bandwidth is an extremely scarce resource. Other means of
communications are considered prior to requesting a UHF TACSAT resource. UHF
TACSAT resources include dedicated channels and DAMA networks. Table I-1 presents
criteria communications planners use to determine when a UHF TACSAT resource is
necessary. A signals intelligence (SIGINT) risk assessment is performed to determine
the system and mode best suited to mitigate the SIGINT risk while accomplishing the
mission.

I-6


---

    b. Use a logical process for communications planning. The process should include
determining the distance and evaluating the terrain between terminating points; the
type of information to be moved (voice, data, imagery, video); the systems and modes
available to move the information; and the ability of the unit to furnish, install, operate,
and maintain the systems and modes. Compare the communications requirements to
the systems and modes available to communicate.

    c. Do not consider TACSAT as the default solution to any communications
requirement. Specific planning considerations drive communications planning and the
process of defining the resources required to move information. As the process of system
and mode analysis consideration proceeds, eliminate non-TACSAT systems through
accurate and defensible mission analysis before determining that TACSAT is required.

    d. The planning matrix in Table I-1 represents the logical process used to analyze
the systems and modes available to a unit for its communications mission.

                                                                                                                                    I-7


---

             Table I-1. Voice/Data Planning Matrix

  Distance            Mode                  System Example                         Remarks

1 to 20       LOS (line of sight)                VRC-8x/9x      National Security Agency (NSA) Type I
kilometers        FM Secure                         MBITR                   Encryption Required
(km)              Voice/Data
                                             AN/PSC-5/A/C/D             Plan 1 watt/km; RETRANS
20 to 50 km  LOS HF Voice/Data                 AN/PRC-117F                   Terrain-Dependent
                                                   LST-5D
50 to 150            Secure                     AN/TRC-176          NSA Type I Encryption Required
km              Phone/Satellite                 AN/GRC-206              1 x RETRANS per 40 km;
              LOS HI PWR FM                     AN/URC-119                   Terrain-Dependent
150 to                                            PRC-104
10,000 km         Voice/Data                                      Connected to a Tactical Local Area
(over-the-                                 AN/GRC-206 Pallet                    Network (LAN)
horizon)     LOS HF Voice/Data                  AN/PRC-150
                                                                    NSA Type I Encryption Required
                     Secure             STU/STE, Iridium, GSM,
                Phone/Satellite                  INMARSAT
              LOS HI PWR FM
                                                 VRC-8x/9x
                  Voice/Data,
                 w/RETRANS                      AN/URC-119
               EHF (Extremely                     PRC-104
               High Frequency)
                                           AN/GRC-206 Pallet
             LOS HF Voice/Data                  AN/PRC-150

                    TACSAT              STU/STE, Iridium, GSM,
                                                 INMARSAT
                   SIPRNET
                                   AN/VRC-8x/9x w/RETRANS Site
                        HF
                                           AN/PSC-11/SCAMP
                       EHF                      AN/TSC-154/
                     Secure                       SMART-T
                Phone/Satellite                 AN/URC-119
                    TACSAT                        PRC-104

                                           AN/GRC-206 Pallet
                                                AN/PRC-150

                                             AN/PSC-5/A/C/D
                                               AN/PRC-117F
                                                   LST-5D

                                                      SHF

                                                AN/URC-119
                                                  PRC-104

                                           AN/GRC-206 Pallet
                                                AN/PRC-150

                                           AN/PSC-11/SCAMP
                                        AN/TSC-154/ SMART-T
                                        STU/STE, Iridium, GSM,

                                                 INMARSAT
                                             AN/PSC-5/A/C/D

                                               AN/PRC-117F
                                                   LST-5D

    e. Figures I-2, I-3, I-4, and I-5 are decision matrices providing a methodical process
for assessing which systems and modes to use for the communications mission. Use this
methodical process during all phases of communications planning to ensure the
appropriate system and mode are used. Using the following matrices, the

I-8


---

communications planner determines which system and mode meets the requirement.
Use the first system and mode identified.

            Figure I-2. Short-Range (1 to 20 kilometers) System/Mode Decision Matrix

                                                                                                                                    I-9


---

         Figure I-3. Medium-Range (20 to 50 kilometers) System/Mode Decision Matrix
I-10


---

Figure I-4. Long-Range (50 to 150 kilometers) System/Mode Decision Matrix
                                                                                                                       I-11


---

    Figure I-5. Over-the-Horizon (150 to 10,000 kilometers) System/Mode Decision Matrix

5. Description of UHF TACSAT Capabilities

    The following are commonly used definitions.
    a. Bandwidth.

         (1) Narrowband. Narrowband describes a low-capacity voicedata
communications circuit, path, or channel. This usually implies that the channel is
capable of carrying a signal bearing data at a rate of 2.4 kilobits per second (kbps) or
less.

         (2) Wideband. Wideband describes a medium-capacity voice/data
communications circuit, path, or channel. This usually implies that the channel is
capable of carrying a signal bearing data at a rate greater than 2.4 kbps and up to 64
kbps.

    b. When speaking within the context of communications through 5-kHz and 25-kHz
channels of the UHF satellites (per the terminology of MIL-STD 188-181B for single-
channel non-DAMA UHF SATCOM), communications up to 9.6-kbps in 5-kHz channels
are called narrowband channels; communications up to 64-kbps in 25-kHz channels are
called wideband channels.

I-12


---

I-13

      Figure I-6. Military UHF Satellite Constellation and Coverage Areas


---

         (1) The UHF follow-on satellite provides twenty-one 5-kHz channels and
seventeen 25-kHz channels. In addition to the tactical channels, the Navy uses super
high frequency (SHF)-uplink/UHF-downlink broadcast channels to disseminate data to
ships. Each footprint has two primary satellites. USSTRATCOM provides a current
reference for satellite channel availability at http://uhfweb2.usspace.spacecom.smil.mil.

         (2) UHF TACSAT channels provide two types of satellite access, dedicated and
DAMA. Each type of access can support both voice and data communications.

         (3) A combination of fleet satellite communications (FLTSATCOM) and UHF
follow-on satellites provides coverage. Each satellite coverage area terminates in at
least two adjacent NCTAMS/Naval computing and telecommunications station (NCTS).
This redundant coverage ensures global connectivity when using DAMA capabilities.

    c. Dedicated TACSAT. All terminals in a net operate on one uplink radio frequency
paired with one downlink frequency and assigned exclusively to the net. A net’s
associated uplink frequency paired with its downlink frequency constitutes a single
channel dedicated for the net’s operational use during an assigned span of hours or
days. All stations in the net monitor its channel for calls. Each station has a unique
station identifier (or call sign) that is used to identify it to other station operators in the
net. Usually, one station in the net is designated as NCS to supervise and authenticate
the entry and exit of authorized stations.

    d. DAMA. DAMA is a channel access scheme; a TACSAT channel can
accommodate multiple concurrent communications. Uuser terminals access is allocated
in accordance with demand. DAMA multiplexing channels allow dedicated access to
portions of the channel without interference and, through time division multiple access
(TDMA), enables more networks to access the channel. TDMA is accomplished when a
network controller station transmits control signals that establish precisely recurring
intervals of time (frames). A frame is typically one or more seconds in duration. Each
frame is subdivided (time-division) into precise time-slots. Certain slots in each frame
are reserved for the controller station to receive user station service requests, or to
transmit control signals via the satellite. These kinds of signals are called orderwires
(OW). Other time-slots are available for user stations to transmit signal bursts to each
other via the satellite. User nets are assigned slots within the frames on a given
channel. This allows multiple nets to access the same channel simultaneously.

    e. Five-kHz DAMA. A 5-kHz DAMA channel supports one 2.4-kbps voice time-slot
(with current MIL-STD 188-182 terminals) and provides a dedicated point-to-point (or
point-to-network) connection between two outstations.

         (1) Point-to-point or point-to-network private circuit is used primarily for data.
The time delays in the waveform cause extensive latency for voice and, therefore, limit
voice circuits.

         (2) The users manually disconnect (teardown) from the time-slot on completion
of send/receive to make the time-slot available for other users.

    f. Twenty-five-kHz DAMA voice/data. When a dedicated 25-kHz channel is
converted to DAMA, it supports up to five 2.4-kbps time-slots that support voice and
data communications. A 25-kHz DAMA channel can provide two types of service.

         (1) TDMA DAMA (preassigned time-slots).

I-14


---

                (a) A shared time-slot dedicated to one network. In this type of service, one
set of users with a common or private (guard) network address has exclusive access to
this time-slot.

                (b) Delay is in proportion to the number of simultaneous users connected to
the network address.

                (c) A user can be connected, monitoring traffic without interfering with
other users, much like a dedicated channel.

         (2) Ad hoc DAMA (real DAMA).

                (a) Point-to-point/terminal base address (TBA)-to-TBA/TBA-to-common or
private (guard) network connection, a private connection between two or more
outstations in one time-slot.

                (b) No delay or interference due to the point-to-point connection capability.

                (c) Users manually disconnect (teardown) from the time-slot on completion
of send/receive to make the time-slot available for other users.

    g. Five-kHz DAMA multiple-hop (MHOP).

         (1) A circuit can be established between two radios that are physically located in
two different satellite footprints.

         (2) MHOP provides for data transmission over long distances, but has a system
delay due to data hopping across multiple satellite footprints that impairs voice
communication.

6. Military-Standards (MIL-STD) for DAMA

    a. MIL-STD-188-181 (Interoperability Standard for Single Access 5-kHz and
25-kHz UHF Satellite Channels) provides guidance on the use of UHF TACSAT
channels in the dedicated mode. Revision B, the most current version, provides the
information on home channel numbers and their respective frequencies. It also includes
information on higher throughput capabilities for both 5-kHz and 25-kHz DAMA
channels.

    b. MIL-STD-188-182 (Interoperability Standard for 5-kHz UHF DAMA Terminal
Waveform) provides guidance on using 5-kHz DAMA channels. Descriptions of
capabilities and OW transmissions are included. Revision A includes a shortened turn-
around time for voice communications and allows two simultaneous time-slots for voice
communications.

    c. MIL-STD-188-183 (Interoperability Standard for 25-kHz UHF DAMA Terminal
Waveform) provides guidance on using 25-kHz DAMA channels. Descriptions of
capabilities, frame formats, and OW transmissions are included; revision A to this
standard allows for both 5-kHz and 25-kHz channels to be utilized as slave channels;
other changes included in the document allow the DAMA semi-automatic controller
(SAC) to be utilized by terminals conforming to this standard.

7. Waveforms

    a. Five-kHz DAMA allows for the multiplexing of widely dispersed terminals over
single or multiple non-processed satellite channels. The DAMA waveform is divided

                                                                                                                                  I-15


---

into frames of 8.96 seconds. Each frame is subdivided into 1024 building blocks with a
length of 8.75 milliseconds (ms) each. These building blocks are grouped into three
segments in each frame, two for OW transmissions and one for communications. The
OWs sent from the primary channel controller (PCC) to the terminals are forward
orderwires (FOW) and the OWs from the terminal back to the PCC are return
orderwires (ROW). The breakout of a frame is depicted in Figure I-7.

                               Figure I-7. Waveform Breakout for 5-kHz DAMA
    b. In 5-kHz DAMA, the waveform is divided using a flexible frame format. In
flexible frame format, each frame can be different, based on the missions supported.
However, each frame has the same basic set up with the three segments. See Figure I-
8.

         (1) The FOW is the first segment of all frames. It provides essential control
information to all users via one time-slot, which consists of a variable number of
building blocks. The number varies in each frame, based on the amount of information
I-16


---

sent at that time and the number of users requiring replies from the PCC. In every
frame, the FOW contains information on the next frame.

         (2) The ROW is the second segment. It consists of several time-slots, based on
the number of users sending information to the PCC. Again, the number of time-slots
and number of building blocks changes in each frame based on the number of ROWs
sent and how many terminals require ranging in that frame. To ensure there is
sufficient room for communications, the ROW slot is limited to a maximum of four user
requests in each frame.

         (3) The user communications segment is the third segment. It is made up of the
remaining building blocks. The building blocks are grouped into time-slots for baseband
communications between terminals. The data rate and size of message determine how
many building blocks are required in the time-slot for a given transmission. An
additional consideration in the length of the time-slot is whether the user has a full-
duplex or half-duplex terminal. Based on the continual adjustment of frames, the
flexible frame format can technically support an infinite combination of formats. It is
also important to note that, with this waveform, the user time-slots are sequential. No
other user can begin a transmission until the current user finishes.

                              Figure I-8. Waveform Communications for 5-kHz
    c. In 25-kHz DAMA, the frames are broken down differently than in 5-kHz DAMA.
Each frame has a fixed frame format, predetermined by the controller. The format is
based on the number of users supported and the data rates utilized by each one. Unlike
5-kHz DAMA, where each frame is continually adjusted by the changing requests of the
users, the frame format normally stays constant on a 25-kHz DAMA channel. The
frame is divided into more defined segments, as seen in figure I-9.

                                                                                                                                  I-17


---

                        Figure I-9. Waveform Communications for 25-kHz DAMA
    d. The OWs transmitted by the PCC are the channel control orderwire (CCOW) and
always start the frame. Every eighth frame is a master frame in which the information
on the frame format is provided to the terminals along with COMSEC information. In
the 25-kHz DAMA frame, the OWs sent from the terminals return channel control
orderwire (RCCOW) are divided into link test, range, and RCCOW slots. The remaining
frame is divided into three user segments, as seen in Figures I-10, I-11, and I-12. Each
segment—A, B, and C—is divided into time-slots for the users based primarily on the
data rate being utilized for communications. The row selected in each user segment
provides the controller the information required to select the frame format for the
channel, normally stated in three-digit format.

I-18


---

Figure I-10. A Segment Slots
                                                                                    I-19


---

                                            Figure I-11. B Segment Slots
I-20


---

                                            Figure I-12. C Segment Slots

    e. The segments shown in Figures I-10 through I-14 are complete selections. They
facilitate understading how the controller determines the number of users that may
simultaneously use a channel without causing interference. The first item considered is
the data rate of the baseband device. This is indicated by the first number in each
block. The second item considered is the burst rate, which can be one of three
selections. On good channels, the burst rate can be as high as 32-kilosymbol(s) per
second; on noisier channels (or channels with disadvantaged users), the burst rate is
lowered to 19.2- or 9.6-kilosymbol(s) per second to increase the likelihood of successful
communication. The encoding rate also plays a major role, especially with the
disadvantaged users on the DAMA channels.

                                                                                                                                  I-21


---

    f. While there are selections that can accommodate up to 22 time-slots and
selections that can accommodate 16-kbps data/voice users, the most common Navy
selections are the 257 and 259 formats (shown in Figure I-13). These formats allow five
narrowband voice users at a 2.4-kbps data rate on the channel along with several lower
data rate users. The benefit to the user is that five voice nets can be placed on one
channel instead of five separate channels. These formats require ideal conditions in
which burst rates can be at their highest speed.

    g. Adjustments to the frame format are made for different data rates and different
requirements of the users. The UCC, RSSC, or JMINI control station operator always
determines the frame format. Users only supply the requests for access to the channels
and information (such as data rates, type of communications, length of transmissions,
and disadvantaged terminals within the network) supporting the use of the time-slots.
This allows the control operators to adjust the channels to support the greatest number
of users with the highest quality communications slots available.

                          Figure I-13. Typical Navy 25-kHz DAMA Assignments
    h. While these may be the most common frame formats used, they are not the only
formats available. Frame formats can, and should, be based on the communications
requirements submitted, then updated based on the quality of communications
provided. When a unit has disadvantaged users (such as manpack, 20w radio with a
low-look angle to the satellite) within the network, the frame format should be adjusted
to provide a more robust time-slot. This may include reducing the number of time-slots
available to allow for lower burst rates. The lower burst rates (19.2 and 9.6) allow for
communications to be established when the burst rate of 32 does not support the
majority of users.

I-22


---

    i. For TDMA DAMA, the time-slots within the frame format for communications
are assigned to a network address. This guarantees assured access to the units. The
slot is used only by those terminals contacting the network address. TDMA DAMA does
not allow point-to-point or conference calls since all time-slots are dedicated to network
addresses as indicated in Figure I-14. In addition, use of TDMA DAMA does not allow
changing frame formats based on communications problems. The time-slots are
assigned and cannot be changed.

                       Figure I-14. Example of 25-kHz TDMA DAMA Assignments

8. Slave Channels

    a. Slave channels capitalize on a frequency switching concept to assign services on
5-kHz and 25-kHz channels that are time-slaved to a 25-kHz DAMA control channel
(Figure I-15).

         (1) DAMA control channel used for OW communications, ranging, and link tests.
         (2) DAMA slave channels used for baseband communications.
         (3) DAMA slave channels do not require channel control modems/radios.

                                Figure I-15. Slave Channels for 25-kHz DAMA
    b. Only DAMA SAC supports slave channels; JMINI at full operational capability
supports—

                                                                                                                                  I-23


---

         (1) Both -183 (baseline) and -183A terminals can use 25-kHz slave channels.
         (2) Only -183A terminals can use 5-kHz slave channels. New burst rates and
forward are correction rates.
         (3) Set up and push-to-talk delays on 5-kHz slave channels are the same as on
any 25-kHz DAMA channel.
    c. Consider slave channels a hybrid of DAMA with demand assigned single access
(DASA) capability. DASA requires—
         (1) User tunes to DAMA home channel, requests timed DASA access.
         (2) Radio frequency switches to DASA channel for dedicated channel use.
         (3) Radio uses frequency switching technology.
    d. In each frame cycle—
         (1) Users tune to home channel for overhead.

                (a) CCOW.
                (b) RCCOW.
                (c) Link test.
                (d) Ranging.
                (e) No OW, ranging, or link data on slave channel.
         (2) Users frequency switch to slave channel for baseband communications on
appropriate data slot(s).

I-24


---

Figure I-16. Communications on 25-kHz DAMA Slave Channels
                                                                                                             I-25


---



---

                                                 Chapter II

                       Communications Planning Cycle

1. Assess Force Structure Requirements

    a. What is the mission requirement? Who, what, where, when, why
(OPLAN/EXPLAN/EMOP)?

    b. Validate mission requirements against established SDB (per
OPLANS/EXPLANS/EMOP/fragmentary order/Annex-K), and CJCSI 6250.01A priority
code.

                                 Figure II-1. Communications Planning Cycle

2. Acquire Resources

    a. Define unit specific resources. TACSAT resources are extremely constrained due
to proliferation of TACSAT capable radio systems. Based on system constraints a unit
may receive an assignment that provides for lower data rates than originally requested.
Communications planners validate all resource requirements based on mission criteria
and ensure that realistic resource requests are submitted based on mission analysis.

         (1) Do not use TACSAT networks for routine traffic when other systems and
modes of communication are available.

         (2) Do not request resources at a higher priority than required.

                                                                                                                                   II-1


---

    b. Voice.
         (1) Bandwidth (25-kHz or 5-kHz).
         (2) Mode (DAMA or dedicated).
         (3) Data rate (2.4-kbps or 16-kbps).
         (4) Criteria.
                (a) Per the JCS, narrowband voice mandate, compatibility with advanced

narrowband digital voice terminal (ANDVT) application 3 using voice digitization at 2.4-
kbps is the joint standard for secure voice operations via UHF satellites.

                (b) For a number of high priority networks, the COCOM can designate that
a network operate at 16-kbps for technical or voice recognition requirements.

    c. Data.
         (1) Bandwidth (25-kHz or 5-kHz).
         (2) Mode (DAMA or dedicated).
         (3) Data Rate (75-bps to 64-kbps).
                (a) The major factors that determine data rate selection are the file size

required to be transmitted, the volume of traffic, and tolerance for delay in access to the
circuit.

                (b) Larger file sizes require greater throughput speed (for example, a file
size of 50-bytes may be transmitted over a 300-baud link, but a 1.2-megabyte file may
require a nine.6-kbps link).

    d. Duty cycle. (For what percentage of a 24-hour day is access to the circuit
required?)

         (1) Low—1 to 2 hours access per 24-hour period.
         (2) Medium—2 to 8 hours access per 24-hour period.
         (3) High—8 hours or more access per 24-hour period.
    e. Access period. Coordinated universal time date-time group of start access date
and stop access date with specific periods of use per day (for example, 0700Z to 1700z
daily). Request 24-hour access if mission analysis identifies the requirement.
    f. Traffic priority. CJCSI 6250.01A identifies a prioritization scheme to determine
access to both the core warfighting and enterprise-wide SATCOM resource
apportionment. See Appendix J for the prioritization scheme used to determine access.
    g. Mission rationale (for specific/special resource request).
         (1) Equipment, platforms, or mission capabilities/limitations (such as not
capable of operating in all modes or bandwidths).
         (2) Support relationships (special users, coalition users).
         (3) Geographic or physical location (DAMA MHOP), footprint, look angle
constraints.

II-2


---

         (4) DAMA emission control (EMCON) While using 25-kHz DAMA channels,
especially TDMA DAMA, periodic slot connect OWs are transmittable to the terminals.
Stating EMCON is required, ensures the DAMA controllers are ready to transmit this
OW every 2 to 7 minutes. This “pulls in” any terminal logged into the DAMA channel
with the net guard address programmed into the guard list. This eliminates some
operator errors in accessing the net guard.

         (5) TBA management in TDMA DAMA networks. Access to the 25-kHz DAMA
channels is preassigned to the networks. Preassigning the channels removes the
capability to make point-to-point or conference calls and prevents preemption of time-
slots based on TBA precedence. Usually, the networks are assigned as common
networks, eliminating the need to identify which TBAs will participate in the net guard
address. Therefore, listing TBAs and requesting precedence for the TBA is not required.

         (6) TBA precedence. A unit assigns each TBA a precedence for establishing
services/calls via the SAR. For 5-kHz DAMA, the precedences are routine, priority,
immediate, flash, and flash override. The precedence determines how fast the terminal
accesses the satellite channel. All accesses on 5-kHz DAMA are precedence based.
Higher precedence services preempt lower precedence services, even if already
established. The precedences for 25-kHz DAMA and 5-kHz DAMA are the same, except
emergency action is the highest precedence in 25-kHz DAMA. For ad hoc DAMA
channels, TBA precedence works much the same as on 5-kHz DAMA. Precedence is not
the only basis for preemption. Ranked networks preempt slots on the channel first,
followed by precedence. Preassigned time-slots (TDMA DAMA) cannot be preempted by
any precedence.

         (7) Common network. A common network is a net guard address without a
designated list of access permitted terminals. Any terminal may participate if the net
guard address is on the guard list and it uses the configuration code assigned to the
address. The size of the network is limited to 512 addresses, because only 512 terminals
may use one 25-kHz DAMA channel (ranging limitation). The size on the 5-kHz DAMA
channel is limited to 64 terminals, based on the military standard.

         (8) Private network. A private network. is a net guard address with a
designated access list of terminals. This is the standard network for 5-kHz DAMA. A
maximum of 64 TBAs are assigned to the network and designated in the SAR as
participants. Any terminal can initiate the network for a call or service and any service
is available to the network. A 25-kHz DAMA private network. is also limited to 64
TBAs and they must be stated in the SAR as participants. In addition, designate one
terminal as the NCS of the network. This is the only terminal that initiates the
network. Usually, these networks are not given preassigned time-slots. A private
network on 25-kHz DAMA may request access to a DASA channel while a common
network cannot.

         (9) Disadvantaged users. Disadvantaged users are terminals with problems
accessing the satellite channels. These include, but are not limited to, manpack
terminals, aircraft, on-the-move vehicles, and terminals situated in areas with low-look
angles to the satellite (especially 20 degrees or less). Five-kHz DAMA has built in
capabilities to compensate disadvantaged users. Twenty-five-kHz DAMA must assign
frame formats to the channel to compensate these users. The assigned time-slots must
have the same data rate but lower burst rates (19.2 or 9.6) to ensure communications.

                                                                                                                                   II-3


---

This reduces the number of time-slots on a channel, but provides better access for the
user.

    h. Submit SAR. Submit the SAR to higher headquarters (to be published). A
common SAR is found at [Web site to be determined]. If unavailable, UCC guidance is
used.

3. Manage Resources

    a. Monitor the mission planning process for changes and submit updates as
required.

    b. Receive SAA [Web site to be determined] (to be published).
         (1) Verify that frequencies are correct.
         (2) For terminals using channel number, verify that the home channel number is

provided (see Appendix A).
    c. Provide a copy of the SAA to the frequency management office. Based on theater

guidance, the frequency management office—
         (1) Verifies that frequencies are clear in the intended area of operation.
         (2) Verifies that frequency records (uplink/downlink) are included in the

electromagnetic battlespace database (such as Spectrum XXI).
         (3) Tags TACSAT frequency assignments for inclusion in the joint restricted

frequency lists at the appropriate level.
         (4) Assists user with resolving EMI per Chairman Joint Chiefs of Staff Manual

(CJCSM) 3320.02.

4. Issue Resources To Users

    a. Incorporate appropriate information from the SAA into cut sheets, operations
orders, Annex-K, and so forth. Distribute as required. (See Appendix I for samples of
cut sheets.)

    b. Monitor mission for emerging requirements or changes.
    c. Coordinate extensions, preemptions, and terminations of SAAs as they occur.

II-4


---

                                          Chapter III

             TACSAT Radio Equipment and Operations

1. Terminal

                            Table III-1a. Radio Equipment

    Radio Item   AN/PSC-5 SPITFIRE         AN/PSC-5C               AN/PSC-5D Multiband
    Frequency                            SHADOWFIRE                  Multimission Radio

       Range     30 to 400               30 to 420                30 to 512
Megahertz (MHz)
                 LOS, SATCOM, 5-kHz      LOS, SATCOM, 5-kHz       LOS, SATCOM, 5-kHz
     Modes of    DAMA, 25-kHz DAMA       DAMA, 25-kHz DAMA        DAMA, 25-kHz DAMA
    Operations   MIL-STD 188-181         MIL-STD 188-181B         MIL-STD 188-181B
                 MIL-STD 188-182         MIL-STD 188-182A         MIL-STD 188-182A
       DAMA      MIL-STD 188-183         MIL-STD 188-183          MIL-STD 188-183A
   Compliance                            VINSON
                 VINSON                  MELP                     VINSON
    Embedded     ANDVT                   ANDVT                    ANDVT
     COMSEC      KG-84A (Modes 3 and 4)  KG-84A (Modes 1, 2, 3,   KG-84A (Modes 1, 2, 3,
                 FASCINATOR              and 4)                   and 4)
     Platform                            FASCINATOR               FASCINATOR
        Ports    Manpack/Vehicular       Manpack/Vehicular
                 One                     One                      Manpack/Vehicular
  Programming                                                     One
   Frequencies   Home Channel Numbers    Home Channel Numbers
                                                                  Home Channel Numbers

                            Table III-1b. Radio Equipment

Radio Item       AN/PRC-117F             AN/WSC-3 w/        MD-1324            LST-5D
                                            TD-1271   w/RT-1771 or AN/
 Frequency                                                              225 to 400
Range(MHz)                                                   WSC-3
                                                                        LOS, SATCOM,
  Modes of   30 to 512               225 to 400       225 to 400        5-kHz DAMA,
Operations                                                              25-kHz DAMA
             LOS, SATCOM, 5-kHz      SATCOM,          SATCOM, 5-kHz     MIL-STD 188-181
    DAMA     DAMA, 25-kHz DAMA       25-kHz DAMA      DAMA, 25-kHz      MIL-STD 188-182
Compliance                           FSCS for 25-     DAMA              MIL-STD 188-183
             MIL-STD 188-181B MIL-   kHz DAMA         MIL-STD 188-181   VINSON
Embedded     STD 188-182                              MIL-STD 188-182   ANDVT
  COMSEC     MIL-STD 188-183 and A   External Crypto  MIL-STD 188-183   KG-84
             VINSON                                                     External Crypto for
             ANDVT                                    External Crypto   Second Port
             KG-84A (Modes 1, 2, 3,
             and 4)
             FASCINATOR

                                                                        III-1


---

                     Table III-1b. Radio Equipment

  Radio Item  AN/PRC-117F           AN/WSC-3 w/            MD-1324            LST-5D
                                       TD-1271       w/RT-1771 or AN/
   Platform                                                            Manpack/Vehicula
     Ports                                                  WSC-3      r
                                                                       Two
Programming   Manpack/Vehicular     Mounted/Ship Mounted/Ship          Uplink and
Frequencies                                                            Downlink
              One                   Four             Two               Frequencies and
              Home Channel Numbers                                     Offsets
                                    Uplink and       Uplink and
                                    Downlink         Downlink
                                    Frequencies and  Frequencies and
                                    Offsets          Offsets

                     Table III-1c. Radio Equipment

       Radio Item          AN/ARC-231                   DMR     Mini-DAMA AN/USC-
  Frequency Range            SKYFIRE                                    42(V)1,2,3
                                          2 to 2000
          (MHz)      30 to 512            LOS, SATCOM, 5-kHz   225 to 400
Modes of Operations                       DAMA, 25-kHz DAMA
                     LOS, SATCOM, 5-kHz   MIL-STD 188-181B     LOS, SATCOM,
 DAMA Compliance     DAMA, 25-kHz DAMA    MIL-STD 188-182A     MIL-STD 188-181B
                     MIL-STD 188-181B     MIL-STD 188-183A     MIL-STD 188-182
Embedded COMSEC      MIL-STD 188-182A                          MIL-STD 188-183
                     MIL-STD 188-183A     VINSON
        Platform     VINSON               ANDVT                VINSON
           Ports     ANDVT                KG-84A               ANDVT
                     KG-84A (Modes 1, 2,                       KG-84
     Programming     3, and 4)            Mounted/Ship
      Frequencies    FASCINATOR           Four                 Mounted/Ship/Airborne
                                                               Eight
                     Airborne             Unknown
                                                               Unknown
                     One

                     Home Channel
                     Numbers

       Note: Information on all DAMA certified equipment is available on the Joint
                Interoperability Test Command (JITC) Web site:
                http://jitc.fhu.disa.mil/reg/uhfdama.htm.

III-2


---

2. Terminal Set up and Operations

    a. AN/PRC-117F. (See Appendix C.)

                                              Figure III-1. AN/PRC-117F
    b. AN/PSC-5A/C/D. (See Appendix D.)

                                            Figure III-2. AN/PSC-5 Series
    c. Lightweight satellite terminal (LST)-5D. (See Appendix E.)

                                                    Figure III-3. LST-5
                                                                                                                                  III-3


---

    d. AN/ARC-231. (See Appendix F.)

                                               Figure III-4. AN/ARC-231
    e. AN/WSC-3. (See Appendix G.)

                                                Figure III-5. AN/WSC-3
    f. TD-1271B/U. (See Appendix G.)

                                               Figure III-6. TD-1271B/U
III-4


---

g. MD-1324 W/AN/WSC-3 or RT-1771. (Not available)

                                             Figure III-7. MD-1324
h. Digital modular radio (DMR) (not available).

                                               Figure III-8. DMR

                                                                                                                             III-5


---

    i. USC-42(V)1, 2, 3 (mini-DAMA) (not available).

                                            Figure III-9. USC-42(V)1, 2, 3
    j. AN/ARC-210 (not available).

                                              Figure III-10. AN/ARC-210

3. Terminal Base Address (TBA) Management

    a. All DAMA capable terminals must have a valid, unique TBA to operate in a
DAMA network. A TBA identifies the radio on the DAMA network and in the DAMA
controllers at the SMC. TBAs cannot be shared by terminals in a DAMA network. A
TBA functions in a DAMA network much like an IP address functions in a computer
network. For those radios with more than one port, additional addresses are required
and known as port addresses. Space and Naval Warfare Systems Command (SPAWAR)
Charleston, South Carolina assigns these port addresses based on the type of terminal
for which the unit requests an address. Joint UHF MILSATCOM DAMA maintains a
list of all TBAs in the call directory, fleet satellite communications system (FSCS)-211-
80-29-2. This directory may be downloaded periodically from SPAWAR’s Charleston,
South Carolina Web site, http://sscc.spawar.navy.mil/ or contact SPAWAR’s
Charleston, South Carolina TBA administrator at commerical phone number (COMM)
(843) 218-6620 or defense switched network (DSN) 588-6620.

III-6


---

    b. Units request TBA from their higher headquarters to preclude proliferation of
unnecessary TBA. The headquarters coordinate with SPAWAR to acquire the required
TBAs. This ensures major commands have oversight of the procured TBAs available to
their units. Units should not interact with SPAWAR on a regular basis.
FSCS-217-98-00-1 provides guidance for requesting. (Point of contact at SPAWAR is
COMM (843) 218-6620.) Requests for TBAs should allow a 30 day turn around time for
the addresses to ensure the TBA is properly entered in the worldwide JMINI and SAC
databases and the TBA is recognized when it logs onto the network to access DAMA
network resources. Most units receiving the terminals must submit SARs in a timely
manner, therefore address requests should take place 60 to 90 days before receipt of
radios.

4. Orderwire (OW) Key Management

    a. Unit COMSEC custodians maintain the OW keys used in DAMA. For a unit that
does not have keys available, the COMSEC custodian orders the keys from—

         (1) Joint Chiefs of Staff ICP Manager, 7115 South Boundary Blvd, MacDill AFB,
FL 33608-2461.

         (2) COMM (813) 828-2461 or DSN 968-2461.
    Note: Only the requesting unit's COMSEC custodian with valid COMSEC

              account is authorized to order these keys. The DAMA system consists of
              four satellite coverage areas. Each satellite coverage area has a unique
              OW key. The requesting activity must specify the satellite coverage area,
              for example, continental United States (CONUS), Atlantic (LANT), Indian
              Ocean (IO), or Pacific (PAC) for the OW key requested. The COMSEC
              custodian receives a message stating which key segment is used for the
              WEEKLY key.

    b. The DAMA SAC and JMINI initial operational capability use keys in positions 0
to 7 while, the AN/PSC-5A (Spitfire) uses keys in positions 1 to 8. Careful coordination
is performed before executing any DAMA operations. Additionally, the key location
must be coordinated in each footprint that operations occur to ensure compatibility with
the DAMA controller in all areas of operation. A good technique is placing the same key
in the first four fill positions. The other four positions are reserved for future
over-the-air rekeying capabilities. The NCTAMS places the keys in the positions
indicated in Table III-2. Coordination is required to determine the key position for the
current week.

                                                                                                                                  III-7


---

                             Table III-2. OW Key Positions

DAMA Controller (PCC)          Footprint                            NCTAMS Key Position
      NCTAMS LANT               CONUS                                         0 and 1
                             LANT (MED)                                       2 and 3
  NCTAMS EURCENT                                                               2 and 3
      NCTAMS PAC                  PAC                                          0 and 1
     NCTAMS Guam                    IO

5. Samples of Checklists

    a. Sample checklist, 5-kHz DAMA.

                             Table III-3. Checklist for 5-kHz DAMA

                 ITEM                               OPTIONS
             Modulation
              Encryption                             PSK

                 Mode         ANDVT             3KG-84             4KG-84   External
              Data Rate
          Transmit Power               V                            D
         Channel Number
        Configuration Code    75  300  600  1200  2400  9600
       Orderwire Encryption
          Operation Mode                            23 to 43 dBm
               Ranging
             Satellite ID             ________ (129 to 191and 194 to 239)

        Satellite Ephemeris           _______ (000 to 511 (use 060 for 2400bps))

         Terminal Position             PT                           CT

           Terminal Time               Normal       Silent         EMCON
         Terminal Address
                                       Passive      Active         (Maint)
               Platform
         Message Release     1 2 3 4 5 6 7 8

                                       Longitude: ___° (0° to 180°)
                                      Ascension Time: ___:__ Zulu
                                      Inclination: ______° (0° to 10°)

                                      Latitude: N/S _____° (0° to 90°)

                                      Longitude: E/W _____° (0° to 180°)

                                                    __:__ Zulu

                                                _______ (00000 to 49999)

                                       Stationary                   Mobile

                                       Manual                       Auto

III-8


---

b. Sample Checklist, 25-kHz DAMA.

                      Table III-4. Checklist for 25-kHz DAMA

          ITEM                                  OPTIONS
     Service Type
      Modulation                       AC                     DC

       Encryption                                PSK
          Mode
                       ANDVT  3KG-84  4KG-84  VINSON  External
       Data Rate
                                       Voice                  Data
   Transmit Power
  Channel Number       75          300  600  1200  2400                4800
 Configuration Code                 16000  32000  56000  64000
Orderwire Encryption
   Operation Mode                              23 to 43 dBm

        Ranging                    009 to 128, 192, 193 _________________
      Satellite ID
                                   01 to 99 (Use code assigned in SAA)
 Satellite Ephemeris
                                       PT                     CT
  Terminal Position
                                       Normal                 EMCON
    Terminal Time
  Terminal Address           Active            Passive           (Maint)

       Guard List                               1 to 8
    COMSEC Key
    Orderwire Key                     Longitude: ___° (0° to 180°)
   Call Precedence
                                      Ascension time: ___:__ Zulu
      Destination
                                      Inclination: ______° (0° to 10°)
    Circuit Number
                                      Latitude: N/S _____° (0° to 90°)

                                   Longitude: E/W _____° (0° to 180°)

                                                ___:__ Zulu

                                      ________ (00000 to 65535)

                                      Up to 15 five-digit addresses

                                                1 to 6

                       EA             FO         1 to 4         P R
                                                F I

                                            Five-digit addresses

                                      __________ __________

                                   __________ __________ __________

                                      000 to 999 (DC mode only)

6. Accessing a Dedicated Channel

    a. A dedicated channel is a 5-kHz or 25-kHz satellite channel (uplink and downlink
frequency pair on a transponder) supporting a single communications network for a
designated period of time.

                                                                             III-9


---

    b. User requirements—
         (1) Azimuth and elevation to satellite.
         (2) Home channel/frequency pair/uplink and offset. (See Appendix A to verify

home channel number based on frequency pair.)
         (3) COMSEC type, mode of operations, and data rate.

7. Accessing a DAMA Channel

    a. Description—DAMA (called “demand assignment multiple access in the MIL-
STDs- is also correct) is a method of automated channel-sharing (multiplexing). User
terminals automatically interact with a control station, which allocates a portion of a
satellite channel for that terminal’s communications. Channel allocation is based on
current needs and priorities. Any unused DAMA resource is available on a precedence
basis and is shared by all users. The ad hoc nature of DAMA limits the waste caused by
long-term preassigned satellite resources. Channel-sharing is transparent to the
TACSAT user. Since there are two types of UHF satellite channels, 5-kHz and 25-kHz,
there are two types of DAMA.

    b. User requirements—
         (1) Azimuth and elevation to satellite.
         (2) Home channel/frequency pair/uplink and offset. (See Appendix A to verify

home channel number based on frequency pair.)
         (3) COMSEC type, mode of operations, and data rate.
         (4) OW key and position.
         (5) Type of channel—5-kHz or 25-kHz.
         (6) Configuration code.
         (7) Type of communications—normal, silent, EMCON.
         (8) TBAs with assigned maximum precedence and net guard addresses.
         (9) Demarcation number for 5-kHz DAMA.
         (10) Type of ranging.
         (11) Types of services
                (a) 5-kHz—message, circuit, or DASA.
                (b) 25-kHz—two-party or conference calls.

    c. Fundamentals of DAMA operations—
         (1) Acquiring the satellite. All terminals must be able to receive and decrypt

OWs transmitted by the DAMA controllers. Unless this is accomplished by the
individual terminal, access to the satellite channel is not obtained. The OWs include
the information required to decrypt messages. Common problems are using the wrong
OW key and placing the OW key in the wrong position.

         (2) Ranging. For terminals to transmit in the proper time-slot, the radios must
have range reaching the satellite. Active ranging may be performed by the terminal. It

III-10


---

automatically determines the range and provides the information required for
transmissions. Passive ranging is an option where a terminal computes the range to
the satellite based on the terminal position, zulu time (z), and satellite ephemeris data
to obtain the information required for transmissions.

         (3) Logging in. While terminology is different between the two types of DAMA,
each terminal must inform the controller the terminal is accessing the channel.

                (a) In 5-kHz DAMA, the radio sends a log in message providing the
terminal information to the controller.

                (b) In 25-kHz DAMA, the radio sends a status B message providing the
terminal information to the controller.

         (4) Establishing communications. When the terminal completes the previous
steps, it must still request permission to access the channel.

                (a) To communicate on 5-kHz DAMA, the type of service or call must be
decided before establishing communications with other terminals. The service or call is
limited to one address, so either a point-to-point or a net guard call is made. The types
of calls are circuit service, DASA service, and message service. Once communication is
complete, the call or service is automatically terminated or the operator terminates the
call or service manually. This releases the time-slot to be used by other terminals. The
system permits the controller to terminate the call or service, in case an operator
forgets, so the time-slot is available to other terminals.

                (b) To communicate on 25-kHz DAMA, a call or service must be established
with the other terminals. The call or service is made to a net guard address, another
terminal address, or a conference call (up to six terminal addresses or a mixture of one
net guard address and terminal addresses). Once the call or service is established, the
individual terminal notifies the operator that communication is possible. In a true
DAMA environment, the operators use the time-slot assigned for transmissions and
then return the resource by tearing down/completing the call so others may use the
time-slot.

         (5) Completing communications.

                (a) In 5-kHz DAMA, completion of the call or service is based on the type of
service established. With a message service, the call or service automatically
terminates once the data is sent and received by the terminals. With a DASA service,
the operator must request a time limit (5 to 5115 minutes or indefinite, which is 5115
minutes). The call or service automatically terminates when the time expires. For a
circuit service, the individual operator terminates the call or service. In addition, the
controller monitors the service for communications and if none are detected, the
controller terminates the call or service.

                (b) In 25-kHz DAMA, completion of the call or service is based on channel
set up. The operators may establish the communications with a time limit (01 to 59
seconds, minutes, hours, or days). Once the time limit is reached, the call or service
automatically terminates, releasing the time-slot. If a time limit is not set, the
operators must initiate the completion of the call or service. If the channel is set up so
time-slots are preassigned (also known as TDMA DAMA), the time-slot is not released
and completion of the call or service is not performed by the operator.

                                                                                                                                 III-11


---

         (6) Logging out.

                (a) For 5-kHz DAMA, a log out message must be transmitted to notify the
controller the terminal is leaving the channel. Failure to send the log out OW effects
terminals when they reaccess the DAMA channels. Terminals on a 5-kHz DAMA
channel are monitored continuously and can be logged out by the control station when
they do not respond to periodic polling. This time limit is normally set at 30 minutes.

                (b) For 25-kHz DAMA, an out of order service OW is transmitted to the
controller. This OW notifies the controller to take the terminal off line. The OW
requires use of a reason code. To date, 99 is the only code identified. Failure to send
the OW does not effect the terminal’s ability to reaccess the channel.

    d. Common DAMA challenges.

         (1) Wrong OW key loaded, OW key loaded in the wrong position or control
station has wrong OW key.

         (2) Radio programmed improperly.

         (3) Radio not programmed or contained incorrect TBA.

         (4) Guard list loaded improperly in the radio.

         (5) Radio loaded with the wrong home channel number/frequencies.

         (6) JMINI or SAC improperly programmed at the NCTAMS.

         (7) NCTAMS problems.

    e. EMI resolution checklist sample. (See Appendix H.)

    f. DAMA operations assistance.

             Table III-5. DAMA Points of Contact

       NAME       POSITION    AGENCY/POSITIO                        PHONE
                                          N
UHF POC      UHF Ops Support                      COMM (719) 554-4151
ICP POC      Office           ARSTRAT             DSN 692-4151
             Orderwire Key                        (813) 828-2461 DSN 968-2461
     SPAWAR  Ordering         ICP Manager
                                                                  SPAWAR
SPAWAR POC        SPAWAR            SPAWAR
                                                  COMM (843) 218-5698
SPAWAR POC   DAMA/JMINI/DAMA  SPAWAR Systems      DSN 588-5698
             SAC              Center Charleston,
SPAWAR POC                    South Carolina      COMM (843) 218-4546
SPAWAR POC   DAMA/JMINI/DAMA  SPAWAR Systems      DSN 588-4546
(TBAs)       SAC              Center Charleston,
                              South Carolina      COMM (843) 218-4937
             DAMA/JMINI/DAMA  SPAWAR Systems      DSN 588-4937
             SAC              Center Charleston,
                              South Carolina      COMM (843) 218-6620
             TBAs             SPAWAR Systems      DSN 588-6620
                              Center Charleston,
                              South Carolina

III-12


---

                      Table III-5. DAMA Points of Contact

SPAWAR Systems        ALL DAMA HELP          24 hours, 7 days a  1-877-4SPAWAR
Command                                      week                COMM (843) 974-5550
Consolidated Call     ALL DAMA HELP          0600-1700 EST       DSN 588-5550
Center (Level 1)                             Monday through
SPAWARSYSCEN                 CONUS           Friday              COMM (843) 974-4546/4939
Charleston UHF                                                   DSN 588-4546/4939
DAMA Help Desk        JMINI                         CONUS
(Level 2)                                                                          CONUS
                      DAMA SAC               Tech Control/Watch
      CONUS           SARs; DAMA             Officer             COMM (757) 445-5461/5279
                      Assistance; Satellite                      DSN 565-5461/5279
NCTAMS LANT           Issues                 POC 24/7 number     COMM (757) 445-7111/7112
                                             UHF CELL            COMM (757) 445-5625/5626
NCTAMS LANT           SARs; DAMA             JFCOM               DSN 565
                      Assistance; Satellite  USSOUTHCOM
Global SATCOM         Issues                                     COMM (719) 554-4096
Support Center        UHF SATCOM                                 DSN 312-692-4096
(USSTRATCOM)          Manager
                      Frequency Manager                          COMM (719) 554-6000
GSSC                                                             DSN 312-692-6000

RSSC CONUS                                                       Comm (813) 828-6840
                                                                 DSN 968-6840
UHF SATCOM
Manager                                                          DSN 836-7683

USSOUTHCOM                                                       COMM (305) 437-166
POC                                                              DSN 567-1661
                                                                 Fax 305-437-1951
USAF (CONUS)                                 JFMO LANT           COMM (757) 836-8006
                                                                 DSN 836-8006
      CONUS                  CONUS                  CONUS        Fax (757) 836-8022

SOCCENT               Spectrum Manager       JFMO LANT                             CONUS
SOCSOUTH              Spectrum Manager
Frequency                                         FORSCOM        DSN 968-4079
Manager               Frequency Manager                          DSN 865-3970
                                             FORSCOM
    FORSCOM               FORSCOM            FORSCOM             COMM (757) 836-8014
                                             FORSCOM
FORSCOM POC           FORSCOM                14th WPS/DOSCX                     FORSCOM
                      Spectrum Mgr           Hurlbert Field, FL
FORSCOM POC           Frequency Manager                          COMM (404) 464-5572
                                                   USASOC        DSN 367-5572
FORSCOM POC           Frequency Manager                          COMM (404) 464-5807
                                             USASOC              DSN 367-5807
Additional source of  AN/URC-133 Users       USSOCOM, SOIO-      COMM (404) 464-6016
reference.            Guide                  CR                  DSN 367-6016

     USASOC                 USASOC            MARINE CORPS       DSN 641-8830

USASFC G6             USASFC G6                                                   USASOC
Operations/Plans      Operations/Plans
NCO                   NCO                                        COMM (910) 432-7427
                                                                 DSN 239-7427
Spectrum Manager      Spectrum Manager
                                                                 DSN 299-4855
MARINE CORPS          MARINE CORPS
                                                                            MARINE CORPS

                                                                                           III-13


---

                  Table III-5. DAMA Points of Contact

Spectrum Manager        EUROPE        Spectrum Manager      COMM (757) 444-5960
MARFORLANT;                           Marine Forces         DSN 564-5960
MARFORSOUTH       JMINI               Atlantic; Marine      Fax (757) 444- 6136
MARFORNORTH                           Forces South; Marine
MARFORRES         DAMA SAC            Corps North           DSN 678-6777
MARFORPAC                             MARFORRES             DSN 315 477-8481
MARFOREUR         SARs; DAMA Assist;  MARFORPAC             DSN 314 431-2343
                  Satellite Issues    MARFOREUR
     EUROPE                                                                  EUROPE
                                             EUROPE
NCTAMS                                                      DSN 314-626-6140
EURCENT                               Tech Control/Watch
NCTAMS                                Officer               COMM 011-39081-568-3350
EURCENT                                                     DSN 314-626-3350
                                      RSSC EUR
RSSC EUR                                                    49-711-686-39-5843/5711
                  Spectrum Manager                          DSN 314-434-5843/5711
RSSC EUR
                                      USEUCOM               Cell (49) 160-969-10238
SOCEUR                                                      DSN 314-434-5843/5711
                        PACIFIC       MARFOREUR             DSN 314 430-4589
USEUCOM                                                     49-711-680-8853
                  JMINI                      PACIFIC        DSN 430-8853
MARFOREUR         DAMA SAC                                  Fax 430-5006
                                      Tech Control/Watch    DSN 314 431-2343
     PACIFIC      SARs; DAMA Assist;  Officer
                  Satellite Issues                                           PACIFIC
NCTAMS PAC                            TECH CONTROL
                                      (DAMA SAC)            DSN 315-453-0760
NCTAMS PAC                                                  COMM (808) 653-0084/0090
                                      UHF SATCOM CELL       DSN 315-453-0084/0321/0322/5544
NCTS GUAM                             RSSC PAC              COMM 671-355-5104
                                                            COMM (671) 355-5326
RSSC PAC          Frequency Manager USARPAC                 DSN 315-355COMM
                                                            COMM (808) 656-0582/4700
USARPAC POC       Spectrum Manager    MARFORPAC             DSN 315 456-0582/4700
                  Spectrum Manager
SOCPAC            Spectrum Manager                          COMM (808) 438-8219
SOCKOR                                                      DSN (315) 438-8219
MARFORPAC
                                                            DSN 477-8481

8. COMSEC Equipment

    a. VINSON. VINSON encryption is provided at 16 kbps only for voice and data
communications. It is used with 25-kHz channels, either dedicated or DAMA (with a 16
kbps time-slot).

    b. ANDVT. ANDVT encryption is provided at 1.2 kbps or 2.4 kbps for voice and
data communications. It is used with 5-kHz and 25-kHz channels, either dedicated or
DAMA.

    c. Mixed excitation linear predicative (MELP) voice encoder. MELP encryption is
provided for 2.4 kbps voice only, providing increased voice recognition, reliability, and
quality. It is used with 5-kHz and 25-kHz channels, either dedicated or DAMA.

III-14


---

    d. KG-84. KG-84 encryption is primarily used for data communications and is used
with data rates from 75 bits per second (bps) up to 56 kbps. It is used with 5-kHz and
25-kHz channels, either dedicated or DAMA, depending on the data rate. It is the
encryption device used with the MIL-STD 188-181B data rates, providing up to 9.6 kbps
on 5-kHz dedicated and DASA channels and up to 56 kbps on 25-kHz dedicated and
DASA channels.

    e. KGV-11. KGV-11 is used to provide OW encryption/decryption, either embedded
or external.

                                                                                                                                 III-15


---



---

                               Appendix A

SATELLITE CHANNEL AUTHORIZATION LIST

Table A-1. Satellite Channel (Home Channel) Authorization List

Channel  Uplink Frequency  Downlink Frequency  Channel Bandwidth
Number           (MHz)               (MHz)
                  SHF               250.350               N/A
     1            SHF               250.400               N/A
     2            SHF               250.450               N/A
     3            SHF               250.500               N/A
     4            SHF               250.550               N/A
     5            SHF               250.600               N/A
     6            SHF               250.650               N/A
     7            SHF               250.700               N/A
     8          292.850             251.850             25-kHz
     9          292.950             251.950             25-kHz
    10          293.050             252.050             25-kHz
    11          293.150             252.150             25-kHz
    12          294.550             253.550             25-kHz
    13          294.650             253.650             25-kHz
    14          294.750             253.750             25-kHz
    15          294.850             253.850             25-kHz
    16          296.250             255.250             25-kHz
    17          296.350             255.350             25-kHz
    18          296.450             255.450             25-kHz
    19          296.550             255.550             25-kHz
    20          297.850             256.850             25-kHz
    21          297.950             256.950             25-kHz
    22          298.050             257.050             25-kHz
    23          298.150             257.150             25-kHz
    24          299.350             258.350             25-kHz
    25          299.450             258.450             25-kHz
    26          299.550             258.550             25-kHz
    27          299.650             258.650             25-kHz
    28          306.250             265.250             25-kHz
    29          306.350             265.350             25-kHz
    30          306.450             265.450             25-kHz
    31          306.550             265.550             25-kHz
    32          307.750             266.750             25-kHz
    33          307.850             266.850             25-kHz
    34          307.950             266.950             25-kHz
    35          308.050             267.050             25-kHz
    36          309.150             268.150             25-kHz
    37          309.250             268.250             25-kHz
    38          309.350             268.350             25-kHz
    39          309.450             268.450             25-kHz
    40

                                                                  A-1


---

     Table A-1. Satellite Channel (Home Channel) Authorization List

     Channel  Uplink Frequency  Downlink Frequency  Channel Bandwidth
     Number           (MHz)               (MHz)
                     310.650             269.650             25-kHz
         41          310.750             269.750             25-kHz
         42          310.850             269.850             25-kHz
         43          310.950             269.950             25-kHz
         44          293.950             260.350             25-kHz
         45          293.975             260.375             25-kHz
         46          294.000             260.400             25-kHz
         47          294.025             260.425             25-kHz
         48          294.050             260.450             25-kHz
         49          294.075             260.475             25-kHz
         50          294.100             260.500             25-kHz
         51          294.125             260.525             25-kHz
         52          294.150             260.550             25-kHz
         53          294.175             260.575             25-kHz
         54          294.200             260.600             25-kHz
         55          294.225             260.625             25-kHz
         56          294.250             260.650             25-kHz
         57          294.275             260.675             25-kHz
         58          294.300             260.700             25-kHz
         59          294.325             260.725             25-kHz
         60          294.350             260.750             25-kHz
         61          294.375             260.775             25-kHz
         62          294.400             260.800             25-kHz
         63          294.425             260.825             25-kHz
         64          294.450             260.850             25-kHz
         65          295.050             261.450             25-kHz
         66          295.075             261.475             25-kHz
         67          295.100             261.500             25-kHz
         68          295.125             261.525             25-kHz
         69          295.150             261.550             25-kHz
         70          295.175             261.575             25-kHz
         71          295.200             261.600             25-kHz
         72          295.225             261.625             25-kHz
         73          295.250             261.650             25-kHz
         74          295.275             261.675             25-kHz
         75          295.300             261.700             25-kHz
         76          295.325             261.725             25-kHz
         77          295.350             261.750             25-kHz
         78          295.375             261.775             25-kHz
         79          295.400             261.800             25-kHz
         80          295.425             261.825             25-kHz
         81          295.450             261.850             25-kHz
         82          295.475             261.875             25-kHz
         83          295.500             261.900             25-kHz
         84          295.525             261.925             25-kHz
         85

A-2


---

Table A-1. Satellite Channel (Home Channel) Authorization List

Channel  Uplink Frequency  Downlink Frequency  Channel Bandwidth
Number           (MHz)               (MHz)
                295.550             261.950             25-kHz
    86          295.650             262.050             25-kHz
    87          295.675             262.075             25-kHz
    88          295.700             262.100             25-kHz
    89          295.725             262.125             25-kHz
    90          295.750             262.150             25-kHz
    91          295.775             262.175             25-kHz
    92          295.800             262.200             25-kHz
    93          295.825             262.225             25-kHz
    94          295.850             262.250             25-kHz
    95          295.875             262.275             25-kHz
    96          295.900             262.300             25-kHz
    97          295.925             262.325             25-kHz
    98          295.950             262.350             25-kHz
    99          295.975             262.375             25-kHz
   100          296.000             262.400             25-kHz
   101          296.025             262.425             25-kHz
   102          296.050             262.450             25-kHz
   103          296.075             262.475             25-kHz
   104          296.100             262.500             25-kHz
   105          296.125             262.525             25-kHz
   106          296.150             262.550             25-kHz
   107          297.150             263.550             25-kHz
   108          297.175             263.575             25-kHz
   109          297.200             263.600             25-kHz
   110          297.225             263.625             25-kHz
   111          297.250             263.650             25-kHz
   112          297.275             263.675             25-kHz
   113          297.300             263.700             25-kHz
   114          297.325             263.725             25-kHz
   115          297.350             263.750             25-kHz
   116          297.375             263.775             25-kHz
   117          297.400             263.800             25-kHz
   118          297.425             263.825             25-kHz
   119          297.450             263.850             25-kHz
   120          297.475             263.875             25-kHz
   121          297.500             263.900             25-kHz
   122          297.525             263.925             25-kHz
   123          297.550             263.950             25-kHz
   124          297.575             263.975             25-kHz
   125          297.600             264.000             25-kHz
   126          297.625             264.025             25-kHz
   127          297.650             264.050             25-kHz
   128          302.445             248.845              5-kHz
   129          302.450             248.850              5-kHz
   130

                                                                  A-3


---

     Table A-1. Satellite Channel (Home Channel) Authorization List

     Channel  Uplink Frequency  Downlink Frequency  Channel Bandwidth
     Number           (MHz)               (MHz)
                     302.455             248.855              5-kHz
        131          302.465             248.865              5-kHz
        132          302.475             248.875              5-kHz
        133          302.485             248.885              5-kHz
        134          302.495             248.895              5-kHz
        135          302.500             248.900              5-kHz
        136          302.505             248.905              5-kHz
        137          302.515             248.915              5-kHz
        138          302.525             248.925              5-kHz
        139          302.535             248.935              5-kHz
        140          302.545             248.945              5-kHz
        141          302.550             248.950              5-kHz
        142          302.555             248.955              5-kHz
        143          302.565             248.965              5-kHz
        144          302.575             248.975              5-kHz
        145          302.585             248.985              5-kHz
        146          302.595             248.995              5-kHz
        147          302.600             249.000              5-kHz
        148          302.605             249.005              5-kHz
        149          302.615             249.015              5-kHz
        150          302.625             249.025              5-kHz
        151          302.635             249.035              5-kHz
        152          302.645             249.045              5-kHz
        153          302.650             249.050              5-kHz
        154          302.655             249.055              5-kHz
        155          302.665             249.065              5-kHz
        156          302.675             249.075              5-kHz
        157          302.685             249.085              5-kHz
        158          302.695             249.095              5-kHz
        159          302.700             249.100              5-kHz
        160          302.705             249.105              5-kHz
        161          302.715             249.115              5-kHz
        162          302.725             249.125              5-kHz
        163          302.735             249.135              5-kHz
        164          302.745             249.145              5-kHz
        165          302.750             249.150              5-kHz
        166          302.755             249.155              5-kHz
        167          302.765             249.165              5-kHz
        168          302.775             249.175              5-kHz
        169          302.785             249.185              5-kHz
        170          302.795             249.195              5-kHz
        171          302.800             249.200              5-kHz
        172          302.805             249.205              5-kHz
        173          302.815             249.215              5-kHz
        174          302.825             249.225              5-kHz
        175

A-4


---

Table A-1. Satellite Channel (Home Channel) Authorization List

Channel  Uplink Frequency  Downlink Frequency  Channel Bandwidth
Number           (MHz)               (MHz)
                302.835             249.235              5-kHz
   176          302.845             249.245              5-kHz
   177          302.850             249.250              5-kHz
   178          302.855             249.255              5-kHz
   179          302.865             249.265              5-kHz
   180          302.875             249.275              5-kHz
   181          302.885             249.285              5-kHz
   182          302.895             249.295              5-kHz
   183          302.900             249.300              5-kHz
   184          302.905             249.305              5-kHz
   185          302.915             249.315              5-kHz
   186          302.925             249.325              5-kHz
   187          302.935             249.335              5-kHz
   188          302.945             249.345              5-kHz
   189          302.950             249.350              5-kHz
   190          302.955             249.355              5-kHz
   191          307.750             254.150             25-kHz
   192          311.150             257.550             25-kHz
   193          316.955             243.855              5-kHz
   194          316.960             243.860              5-kHz
   195          316.975             243.875              5-kHz
   196          317.000             243.900              5-kHz
   197          317.010             243.910              5-kHz
   198          317.015             243.915              5-kHz
   199          317.025             243.925              5-kHz
   200          317.035             243.935              5-kHz
   201          317.045             243.945              5-kHz
   202          317.055             243.955              5-kHz
   203          317.065             243.965              5-kHz
   204          317.075             243.975              5-kHz
   205          317.085             243.985              5-kHz
   206          317.090             243.990              5-kHz
   207          317.095             243.995              5-kHz
   208          317.100             244.000              5-kHz
   209          317.105             244.005              5-kHz
   210          317.110             244.010              5-kHz
   211          317.115             244.015              5-kHz
   212          317.125             244.025              5-kHz
   213          317.135             244.035              5-kHz
   214          317.145             244.045              5-kHz
   215          317.155             244.055              5-kHz
   216          317.165             244.065              5-kHz
   217          317.175             244.075              5-kHz
   218          317.185             244.085              5-kHz
   219          317.190             244.090              5-kHz
   220

                                                                  A-5


---

     Table A-1. Satellite Channel (Home Channel) Authorization List

     Channel  Uplink Frequency    Downlink Frequency    Channel Bandwidth
     Number           (MHz)                 (MHz)
                     317.195               244.095                5-kHz
        221          317.200               244.100                5-kHz
        222          317.205               244.105                5-kHz
        223          317.210               244.110                5-kHz
        224          317.215               244.115                5-kHz
        225          317.225               244.125                5-kHz
        226          317.235               244.135                5-kHz
        227          317.245               244.145                5-kHz
        228          317.255               244.155                5-kHz
        229          317.265               244.165                5-kHz
        230          317.275               244.175                5-kHz
        231          317.285               244.185                5-kHz
        232          317.290               244.190                5-kHz
        233          317.295               244.195                5-kHz
        234          317.300               244.200                5-kHz
        235          317.305               244.205                5-kHz
        236          317.310               244.210                5-kHz
        237          317.315               244.215                5-kHz
        238          317.325               244.225                5-kHz
        239          307.550               253.950     25-kHz (& 25-kHz UK)
        240          307.700               254.100               25-kHz
        241          311.050               257.450     25-kHz (& 25-kHz UK)
        242          311.200               257.600               25-kHz
        243          307.750               254.150             25-kHz UK
        244          311.250               257.650             25-kHz UK
        245          307.650               254.050             25-kHz UK
        246          311.150               257.550             25-kHz UK
        247                                                    25-kHz UK
        248   294.800 to 314.800   253.650 to 254.350          25-kHz UK
        249   298.300 to 313.300   257.150 to 257.850

A-6


---

                                  Appendix B

                   Information Request Codes

                   Table B-1. Information Request Codes

Note: If action states contact NCTAMS – the RSSCs may be contacted for assistance.

Code               Condition                                     Action

1 to 3 Not used.                                None.

4     Disconnect constant key offender.         Terminal has been transmitting for 17
                                                minutes—waveform does not allow for
      The controller determined a constant key  constant transmission. AN/PSC-5 terminal
                                                does not provide a means to bypass this rule,
      offender should be disconnected.          so all transmissions must be less than 17
                                                consecutive minutes.
5 to 65 Not used.
                                                None.

66 Terminal type cannot be connected to the Information request code 66 is sent when a

      requested guard number.                   user requests to join/start a network service

      The requested guard number is             using the wrong network address.

      associated with terminals built to a      MIL-STD 188-183(-) uses the odd numbered

      different version of the MIL-STD. Check (primary) address; this is the AN/PSC-5,

      the guard number and try connecting       AN/PRC-117F, and so forth.

      again.                                    FSCS and MIL-STD 188-183(A) use the even

      FSCS or 183A terminal requested to        numbered (alternate = primary + 1); for now

      connect to a guard number associated      this is the TD-1271, since there are not any

      with 183 (baseline) terminals.            certified 188-183(A) terminals yet.

      183 (baseline) terminal requested to      Note: 117F and AN/PSC-5D are pending

      connect to a guard number associated      upgrade to 183B capability.)

      with FSCS and 183A terminals              The new DAMA SAC channel controller

                                                software links the even/odd network address

                                                pair to maintain interoperability between all

                                                terminal types.

                                                Example VOICE CMD NET:

                                                Primary network address: 56001 for MIL-STD

                                                188-183 (-).

                                                Alternate network address: 56002 for TD-1271

                                                and MIL-STD 188-183A terminals. The

                                                DAMA SAC links 56001 and 56002 in its

                                                software to the same data slot. Use of 56001

                                                is required in the AN/PSC-5. Any TD-1271

                                                and MIL-STD 188-183A terminals would use

                                                56002.

                                                                                               B-1


---

                         Table B-1. Information Request Codes

Note: If action states contact NCTAMS – the RSSCs may be contacted for assistance.

Code              Condition                                         Action

67 Terminal cannot communicate on the                AN/PSC-5 terminals receive this code if

      assigned channel.                              mistakenly assigned a 5-kHz slave channel.

      The requested service is assigned on a AN/PSC-5 terminals cannot use these
      channel a MIL-STD 188-183 (baseline), to channels. Contact NCTAMS.

      which the terminal cannot connect.

      The channel is identified by an 8-bit

      channel code and this terminal uses

      channels identified by a 6-bit channel

      code.

      The channel is a 5-kHz slave channel.

68 Log out report has been ignored—                  Should not receive this code—contact

      terminal log out is performed only from        NCTAMS. AN/PSC-5 is a single port terminal

      port 1.                                        and only uses port 1. In addition, start using

      The log out information report was not         code 99 when sending the out of service
      sent from port 1. Change to port 1 and         message. This performs log out on the DAMA
      retry.                                         SAC.

69 Terminal identification (ID) duplicates an Terminal address is the same as a PCC's.

      existing operational address.                  Check the terminal address.

      The requesting terminal’s ID duplicates

      the address of an operational controller.

70 Requesting party’s guard list does not            Enter the correct net guard address in the

      contain guard address.                         guard list.

      The requesting user’s port guard list does

      not contain the guard address of the

      guard it is activating.

71 Service request access restriction                Send a status B message. Lower the

      violation.                                     precedence and set up the service again.

      The service requested either has a higher

      precedence than allowed by the source’s

      terminal access restriction level or it has a

      lower precedence than the channel

      access restriction level.

72 Requesting party already has an                   Three things may have occurred—

      outstanding queued request.                    1. Already sent a service set up to the queue.

      A user can have only one request in the Only permitted one service on 25-kHz DAMA.

      queue. This user already has a request The operator must teardown and then set up

      queued. Therefore, the current request is the new service. 2. The control station

      canceled.                                      believes a service is pending for the terminal.

                                                     Teardown and retry. If this does not work,

                                                     teardown, out-of-service, send status B, and

                                                     set up the service again. 3. Received a busy

                                                     signal from the distant end—try later or page

                                                     the terminal.

B-2


---

                           Table B-1. Information Request Codes

Note: If action states contact NCTAMS – the RSSCs may be contacted for assistance.

Code             Condition                                       Action

73 Requesting party is not authorized to          This code applies only if the service

      activate All-Call.                          addressed is—16383 or 65535. Check the

      The current request is canceled because     service set up and ensure the correct address
      only the controller operator activates a    was entered. If not, resend request with
      service to the All-Call address.            correct address. If still receiving code 73—
                                                  JMINI identified address incorrectly—contact

                                                  NCTAMS.

74 Requested terminal is already connected The terminal called is unavailable. Teardown

      to a DASA service.                          (if required) and try later.

      The requested user is on a terminal

      connected to a DASA service already;

      therefore, it is unavailable.

75 Request canceled by user.                      Received if teardown of the service is sent

      The source of the service request           before the service is provided (after
      canceled the request while it was queued    requesting a service setup; usually it is
      and waiting for a resource.                 queued). No action is required.

76 Queued call canceled; service queue            JMINI canceled service. Set up the service

      time-out timer expired.                     again.

      The previously queued request from the

      requesting user has been canceled due to

      the controller imposed time-out limit on

      queued service requests.

77 Terminal does not exist in the controller Terminal address is missing from the

      database.                                   database—check TBA for accuracy. If

      The controller has no record of the         correct, contact NCTAMS.

      requesting terminal’s address being

      assigned.

78 Currently the request queue is full.           Should not receive this code. However,

      The controller has too many requests in received a busy signal again— try later.

      the queue and cannot accept more at this

      time.

79 Call in the queue canceled; connection is Attempt the service set up again. If the

      no longer possible.                         terminal(s) called sent an out of service or

      The controller deleted a request from the   radio is the only one active on the network, a
      queue, either at the request of the         different code may be received providing
      controller operator or because it was no    updated information. .

      longer a valid request.

80 Enter a configuration code and retry.          Check for a configuration code, ensure it is

      The terminal operator has not entered a correct on the current menu, and set up the
      configuration code into the port originating service again.

      the request since the terminal was

      powered up or since an RCCOW, out-of-

      service message was sent from this port.

81 Required data rate cannot be supported. Requested a data rate different from the

      The data rate required for this connection  original SAR submission. The channel cannot
      is not supported by any channels            support changing to a different data rate. Set
      operating on this satellite.                up service for original data rate and
                                                  configuration code (via current mode screen).

                                                                                                B-3


---

                            Table B-1. Information Request Codes

Note: If action states contact NCTAMS – the RSSCs may be contacted for assistance.

Code                  Condition                                        Action

82 Requested party unknown. Check call             Check the terminal or network address in the

      directory and retry.                         service setup and retry. If the network

      The requested user or guard does not         address is correct and terminals are active on
      exist in the controller database.            the network, the controller may not have
                                                   activated the network address. Contact

                                                   NCTAMS. (If unable to contact NCTAMS, try

                                                   making a conference call.)

83 Cannot add users to this guard.                 Terminal is not at SVC idle. Teardown and

      The requesting party is connected to a       retry the call. (Even if it says SVC idle, try this
      guard and attempted to add user port(s)      procedure first.)

      to the guard connection.

84 Cannot add a guard to an existing call.         Terminal is not at SVC idle. Teardown and

      The requesting user is participating in a    retry the call. (Even if it says SVC idle, try this
      call and attempting to add a guard.          procedure first.)

85 Requesting party is not authorized to           The JMINI database marked the net guard

      activate this guard.                         address wrong. Contact NCTAMS to correct

      The requesting user attempted to activate error.

      a guard, but this user is not authorized to OR

      activate the guard for one of the following  The unit requested a private guard and the
      reason:                                      NCS has not or is not setting up the service to

      • The requesting party attempted to          the network first.

      activate a private guard, but is not a net

      controller for this guard (All).

      • This is a common guard and common

      guards cannot be activated by a user

      (SAC only).

      • This common or private guard is

      specified in the communications plan but

      is not active at this time (SAC only).

86 Requesting party is not a member of this Terminal not listed as part of the private

      private guard.                               network.

      The requesting user attempted to join a OR

      private guard, but the user is not an        Called the wrong net guard address (check
      authorized member of this private guard.     service set up). Contact NCTAMS.

87 JMINI controller sends this code.               Ensure terminal called the correct address. If

      Requested user’s terminal is unauthorized yes, contact NCTAMS about the address to

      or zeroized.                                 determine why it is marked this way.

      The user‘s terminal is marked in the

      controller database as unauthorized or

      zeroized.

B-4


---

                        Table B-1. Information Request Codes

Note: If action states contact NCTAMS – the RSSCs may be contacted for assistance.

Code                    Condition                                 Action

87 DAMA SAC sends.                            Requested a service with a terminal and/or

      Requested service requires a 5-kHz or   network address assigned to a different home

      25-kHz slave channel, but the required  channel. Currently, no capability to assign

      slave channel is not accessible from the terminal to either a different home channel or

      requestor’s home channel.               a slave channel associated with a different

                                              home channel. If authorized to talk within this

                                              network, check current mode screen to ensure

                                              it is set up for the correct home channel. If

                                              not, send an out of service message, make

                                              changes, or select correct preset, reenter the

                                              DAMA mode on the correct channel and set

                                              up service again.

88 Requesting party’s device is incompatible Configuration code does not match the JMINI

      with this guard.                        database for the net guard address. Check

      The requesting port’s baseband device is the code. If correct per the SAA, retry. If

      incompatible with the baseband device   continued receipt of code—contact NCTAMS.

      specified for this guard.

89 Requested party does not have a            Configuration code does not match the JMINI

      compatible baseband device.             database for the terminal being called. Check

      No port on the requested terminal is    the code. If correct, the distant end may have

      configured for a baseband device        entered the wrong code. First, try again, then

      compatible with the baseband port from need to work with distant end.

      originating the request.

90 None of the users requested are            Set up the service for a later time. If making a

      available.                              conference call, page the other terminals. If

      Not enough requested users are capable making a network call, there may not be any

      and available (for various reasons) to  other active users on the network.

      activate the service request.

91 Connection would cause contention.         Teardown and out of service then send status

      The requested connection would cause B and attempt to set up the service again. If

      contention with an ongoing              this does not work—contact NCTAMS.

      communication.                          Mistakenly, the JMINI has the terminal in

                                              service.

92 Not all requested parties could be         Set up a conference call but not all

      connected.                              participants received the service assigned

      At least one, but not all, of the requested message. Call all the stations and find out

      parties could be connected. (This request who is not connected. Before making a

      is honored, connecting any available    conference call, page all users to ensure they

      parties.)                               are available for the call. This ensures the

                                              terminal does not receive this message.

                                              However, if a message is received, send a

                                              status B message. The only way to add a

                                              missed terminal into the service is for all to

                                              teardown, and then have one terminal set up

                                              the service again.

93 Other link test in progress.               Wait 2 to 5 minutes then rerun link test. Run it

      Only one link test can be conducted on a at 32-kbps first.

      channel and currently another user

      terminal is conducting a test.

                                                                                               B-5


---

                         Table B-1. Information Request Codes

Note: If action states contact NCTAMS – the RSSCs may be contacted for assistance.

Code               Condition                                   Action

94 Unable to connect parties from different Requested a service with a terminal and/or

      channels (JMINI sends).                      network address assigned to a different home

      OR                                           channel. Currently, there is no capability to
                                                   assign the terminal a different home channelIf
      Unable to perform frequency switch           authorized to talk within this network, check
      required for this connection (DAMA SAC       current mode screen to ensure it is set up for
      sends).                                      the correct home channel. If not, send an out
                                                   of service, make changes or select correct
      Frequency switching is required to           preset, reenter the DAMA mode on the correct
      connect the requested service, but           channel and set up service again.
      frequency switching cannot be
      accomplished for any of the following

      reasons:

      • Terminal or terminals that must switch

      • Communications and orderwire

      channels are not on the same satellite.

      • Required frame segment on the

      communications and orderwire channels

      match.

      • Frame timing for the channels may not

      be aligned

95 JMINI sends.                                    The JMINI database marked the net guard

      Demand assigned activation disabled for      address wrong. Contact NCTAMS to correct
      this guard.                                  the error.

      This network is activated on a

      preassigned basis only. In order for a

      user to activate this network, the national

      military strategy network management

      system operator must check the "Allow

      User to Activate" box in the network

      definition.

95 DAMA SAC sends.                                 Should not receive this code—contact

      DASA requests are reserved for guards NCTAMS.

      only.

      The requesting user’s configuration code

      indicates a DASA service and the user

      have requested connection to another

      user or users. Configuration codes 98

      and 99 are reserved for DASA services

      and only private guards can be assigned

      to DASA channels.

96 No DASA channel available.                      Should not receive this code—contact

                                                   NCTAMS.

B-6


---

                Table B-1. Information Request Codes

Note: If action states contact NCTAMS – the RSSCs may be contacted for assistance.

Code            Condition                                      Action

97 Party is connected to a DAMA time-slot Should not receive this code—contact

      already.                                  NCTAMS.

      Cannot assign a DASA connection if

      another user port on the

      requested/requesting user’s terminal is

      participating in a DAMA service of equal

      or higher precedence. If it has a lower

      precedence, the user could be preempted

      out of the DAMA service.

98 Too many guards specified in this            Request can state only one network address.

      request.                                  Use terminal addresses for the other four

      More than one guard was specified in      addresses.

      conference request.

99 Reserved for TD-1271 home channel            Should not receive this code—contact

      change notification.                      NCTAMS.

                               Table B-2. Configuration Codes

Configuration   Equipment       Data Rate       Protocol               Crypto
      Code
         0        Reserved            0         N/A                    N/A
         1         Network            75
                (Prearranged)         75        IAW Network/Prearranged IAW Network/Prearranged
         2         Teletype           75
         3        Computer            75        ASCII 8N2              KG-84A/C
         4         PSC-2A             75        ASCII 8N2              KG-84A/C
         5        KL-43C/F                                             KG-84A/C
6-14 Not Used                                    PSC-2A                KL-43C/F
        15                                      ASCII 8N2

        16         Network      300             IAW Network/Prearranged IAW Network/Prearranged
        17      (Prearranged)
        18                      300             ASCII 8N2              KG-84A/C
        19         Teletype
        20        Computer      300             ASCII 8N2              KG-84A/C
        21
        22            Fax       300             Fax                    KG-84A/C
        23            Fax
                   PSC-2A       300             Fax            KYV-5, KY-99A/100
                   PSC-2A
                  KL-43C/F      300             PSC-2A                 KG-84A/C
                  Computer
                                300             PSC-2A         KYV-5, KY-99A/100

                                300             ASCII 8N2              KL-43C/F

                                300             ASCII 8N2      KYV-5, KY-99A/100

                                                                                           B-7


---

                               Table B-2. Configuration Codes

 Configuration  Equipment        Data Rate    Protocol         Crypto
       Code
                                      600
24-29 Not Used                        600
                                      600
         30        Network            600     IAW Network/Prearranged IAW Network/Prearranged
                (Prearranged)         600
         31                           600     ASCII 8N2              KG-84A/C
         32        Teletype           600     ASCII 8N2        KYV-5, KY-99A/100
         33        Teletype           600
         34                           600         Fax                KG-84A/C
         35           Fax             600      PSC-2A                KG-84A/C
         36        PSC-2A                      PSC-2A          KYV-5, KY-99A/100
         37        PSC-2A             1200    ASCII 8N2
         38       KL-43C/F            1200    ASCII 8N2                 None
         39       Computer            1200    ASCII 8N2              KG-84A/C
40-44 Not Used    Computer            1200                     KYV-5, KY-99A/100
                                      1200        FAX          KYV-5, KY-99A/100
                      Fax             1200
                                      1200
         45        Network            1200    IAW Network/Prearranged IAW Network/Prearranged
                (Prearranged)         1200
         46                           1200    ASCII 8N2              KG-84A/C
         47       Computer                        FAX          KYV-5, KY-99A/100
         48           Fax        Prearranged      FAX
         49           Fax                                            KG-84A/C
         50                           2400     PSC-2A                KG-84A/C
         51        PSC-2A             2400     PSC-2A          KYV-5, KY-99A/100
         52        PSC-2A             2400      DMDG                 KG-84A/C
         53         DMDG              2400      DMDG           KYV-5, KY-99A/100
         54         DMDG              2400    ASCII 8N2              KL-43C/F
55-56 Not Used    KL-43C/F                    ASCII 8N2        KYV-5, KY-99A/100
                  Computer

         57     TEST2                         Prearranged      Prearranged
58-59 Not Used

       60             Network                 IAW Network/Prearranged IAW Network/Prearranged
                  (Prearranged)
       61                                          Fax         KYV-5, KY-99A/100
       62                Fax                       Fax               KG-84A/C
       63                                         Voice
       64                Fax                  Prearranged      KYV-5, KY-99A/100
65 Not Used                                                        Prearranged
                Hand Set/ANDVT

                   Data/ANDVT

B-8


---

                               Table B-2. Configuration Codes

Configuration      Equipment         Data Rate       Protocol               Crypto
      Code
        66             PSC-2A             2400         PSC-2A              KG-84A/C
        67             PSC-2A             2400         PSC-2A        KYV-5, KY-99A/100
        68            KL-43C/F            2400       ASCII 8N2
        69            Computer            2400       ASCII 8N2             KL-43C/F
        70            Computer            2400       ASCII 8N2             KG-84A/C
        71        Tactical Internet       2400    Tactical Internet  KYV-5, KY-99A/100
        72      Personal Computer         2400      Prearranged            KG-84A/C
        73              TEST1        Prearranged    Prearranged            KG-84A/C
                                                                         Prearranged
 74 Not Used                              4800
                                          4800
         75          Network              4800    IAW Network/Prearranged IAW Network/Prearranged
                 (Prearranged)            4800
         76                               4800            Fax        KYV-5, KY-99A/100
         77             Fax               4800            Fax              KG-84A/C
         78             Fax               4800       ASCII 8N2             KL-43C/F
         79         KL-43C/F                      Tactical Internet        KG-84A/C
         80     Tactical Internet        16000       ASCII 8N2             KG-84A/C
         81         Computer             16000       ASCII 8N2
82-88 Not Used      Computer             16000                       KYV-5, KY-99A/100
                                         16000
89              Fax                      16000    Fax                KG-84A/C
                                         16000
90              Network                  16000    IAW Network/Prearranged IAW Network/Prearranged
                                         16000
                (Prearranged)            16000
                                     Prearranged
91              Fax                  Prearranged          Fax               KY-57/58
                                                         Voice              KY-57/58
92              Hand Set/ANDVT                         PSC-2A        KYV-5, KY-99A/100
                                                       PSC-2A              KG-84A/C
93              PSC-2A                            Tactical Internet        KG-84A/C
                                                    Prearranged            KG-84A/C
94              PSC-2A                               ASCII 8N2             KG-84A/C
                                                    Prearranged          Prearranged
95              Tactical Internet                   Prearranged          Prearranged

96              Computer

97              Computer

98              DASA 5-kHz

99              DASA 25-kHz

                                                                               B-9


---



---

                                    Appendix C

                          AN/PRC-117F Radios

1. AN/PRC-117F Dedicated UHF SATCOM Operation

    The AN/PRC-117F operates in UHF SATCOM mode using MIL-STD 188-181B
modulation and HPW data operation. It supports encrypted voice and data
communications in wideband 25-kHz and narrowband 5-kHz channels. The AN/PRC-
117F in SATCOM mode is compatible with VINSON KY-57 (wideband 25-kHz), ANDVT
KY-99/99A, and KG-84C cryptographic equipment. Refer to tables C-1 through C-3 for
capabilities.

                              Table C-1. Dedicated UHF SATCOM Capabilities

   Band of           MOD   COMSEC    DATA VOC                  Data Rates
  Operation      MS181                                     SYNC or ASYNC
                 MS181    PT-None  DATA only    1200, 2400
  Dedicated      MS181    ANDVT    VOICE        2400
  SATCOM         MS181    ANDVT    DATA         300, 600, 1200, 2400
                 MS181    KG-84C   DATA only    1200, 2400 using SBPSK
     5-kHz                KG-84C   DATA only    4800, 6000, 7200, 8000, 9600
Narrowband       HPW                            using Continuous Phase
                 MS181                          Modulation (CPM)
   Channel                                      4 to 8.5 kbps – ARQ
20 Watts Max
                                                1200, 2400, 9600
     Dedicated   MS181    KG-84C   DATA only    2 kbps, 16 kbps
     SATCOM      MS181    PT-None  DATA only    16 kbps
                 MS181                          16 kbps
25-kHz Wideband  MS181    VINSON   VOICE        1.2 k, 2.4 k, 9600, 16 k
      Channel             VINSON   DATA         19.2, 28.8, 32, 38.4, 48, 56 kbps
                 MS181    KG-84C   DATA only    using CPM
  20 Watts Max   MS181    KG-84C   DATA only    300, 600, 1200, 2400
                 HPW                            Special RETRANS Systems
                          ANDVT    DATA         18 to 56 kbps – ARQ
                          FASC     VOICE
                          KG-84C   DATA only

                                                C-1


---

             Table C-2. MIL-STD 188-181B Data Rate Options, 5-kHz

     Option  I/O Data  Modulation  Applicable    Voice or     Remarks
               Rate        Type     COMSEC         Data
       008     1200                               DATA           181A
       010     2400       SBPSK       KG-84       DATA     181A NB Voice
       010     2400       SBPSK       KG-84         D/V
       A10     1200       SBPSK      ANDVT        DATA
       B10      600       SBPSK      ANDVT        DATA
       C10      300       SBPSK      ANDVT        DATA
       013     4800       SBPSK      ANDVT        DATA
       016     6000                   KG-84       DATA
       018     7200        CPM        KG-84       DATA
       020     8000        CPM        KG-84       DATA
       021     9600        CPM        KG-84       DATA
                           CPM        KG-84
                           CPM

             Table C-3. MIL-STD 188-181B Data Rate Options, 25-kHz

     Option  I/O Data  Modulation    Applicable  Voice or      Remarks
               Rate        Type       COMSEC       Data    181A WB Voice
       130     9600       SBPSK                   DATA
       131     9600        CPM          KG-84     DATA
       132     16 k         FSK         KG-84       D/V
       F12     12 k         FSK       VINSON      VOICE
       137    19.2 k       CPM     FASCINATOR     DATA
       139    28.8 k       CPM          KG-84     DATA
       141     32 k        CPM          KG-84     DATA
       143    38.4 k       CPM          KG-84     DATA
       144     48 k        CPM          KG-84     DATA
       145     56 k        CPM          KG-84     DATA
                                        KG-84

C-2


---

2. UHF Dedicated SATCOM Programming Checklist

    Table C-4 outlines programming parameters necessary for dedicated UHF SATCOM
net presets. See Figures C-1 and C-2 for the sub menu and programming tree.

Table C-4. UHF SATCOM Programming Parameters

       Menu Item           Options                       Remarks
Frequency Code
Receive Frequency                    FREQUENCY
Transmit Frequency
Receive Only        Channel Number     Refer to Appendix A for list of FREQ codes.
                    001-249, or 999
Crypto Mode                            Use 999 to manually enter non-standard uplink
                    999                and downlink frequencies.
Encryption Key                         225.00000 to 511.99999 mHz
Analog Data         NO
                    YES                YES for EMCON, no transmit.
KG-84
Synchronization                       COMSEC
HPW Transec Key ID
Training Frames     None               Function switch in PT, mode defaults to DATA
                                       only.
Data/Voice
Modulation          VINSON             Not available on NB channels.
Sync/Async Select
                    ANDVT              2400 max data rate.

                    KG-84              Data only in NB or WB.

                    FASCINATOR         Not available on NB channels. Available for
                                       SATCOM to LOS BLACK RETRANS.

                    TEK 01 to 25       Load TEKs first.

                    YES                External devices with own modem, eliminates

                    NO                 crypto resyncs that interfere (KL-43C/F).

                    Redundant Mode 1   Match mode used in net.
                    Redundant Mode 2   HPW operation requires Mode 1.
                                       TSK loaded in SATELLITE storage position.
                    Non-Redundant
                    Mode 3
                    Non-Redundant
                    Mode 4

                    TSK 01 to 25

                    6, 9, 12, 15, 30, or 60 Sets length of training frames sequence, 9 is
                                                    default.

                                     DATA/VOICE

                    DATA               Only option w/KG-84 selected.

                    AUTO on ADF Port   With VINSON, select port to receive DATA.
                    AUTO on DATA Port

                    DATA or VOICE      With ANDVT COMSEC.
                    MS181              Regular SATCOM
                    HPW                Requires using KG-84 encryption in mode 1.
                    ASYNC              ASYNC requires port programming.

                                                                                           C-3


---

                  Table C-4. UHF SATCOM Programming Parameters

       Menu Item       Options                            Remarks
Baud Rate
Option            SYNC                   Synchronous data systems
                  (HPW) UFO (25-kHz)     Select type of satellite used, NB only on NB
Digital Squelch                          channel when using FREQ code 999. Refer to
Digital Squelch             WB (25-kHz)  Appendix A
                            NB (5-kHz)
TX Power Level    Data Option Codes      Available options dependent on FREQ code and
Change Net Name                          COMSEC previously selected.

                                 SQUELCH

                  ON                     Digital squelch ON prevents PT override.
                  OFF                    Digital squelch ON prevents PT override.
                  ON
                  OFF

                                 POWER

                  2 to 20 watts          Steps in one-dBm increments.

                                 NAME

                  NET 00 to 99           12 characters alphanumeric, no spaces.

                  FREQ CODE COMSEC DATA/VOC

                  SQUELCH                POWER NAME

                                 USE ← → TO SELECT ITEMS

                  Figure C-1. UHF SATCOM Programming Sub Menu

C-4


---

                                   Figure C-2. SATCOM Programming Menu

3. Dedicated UHF SATCOM Operational Steps

    a. To operate in dedicated UHF SATCOM mode, connect a medium or high gain
SATCOM antenna to VHF-HI/UHF J8 antenna connector with a coax cable. Analyze
terrain in planned areas of operation for satellite look-angle access. Verify the
SATCOM antenna is correctly oriented using a magnetic compass to point the antenna
on the proper horizontal azimuth to the satellite. Make an approximate antenna vertical
elevation adjustment. Pointing graphs and look-angle calculation software may assist
in this task. Azimuths from these graphs are not adjusted for local magnetic
declination. Table C-5 contains UHF satellite positions. To check SATCOM antenna

                                                                                                                                   C-5


---

pointing using the SATCOM receive signal strength indicator (RSSI) test, complete the
following procedures:

     Table C-5. UHF Satellite Positions

     Footprint Name  Satellite Position
     CONUS           100 and 105 dog W longitude
     LANT            15 and 23 dog W longitude
     IO              72 and 72. dog E longitude
     PAC             172 and 177 dog E longitude

     Note: The SATCOM RSSI test can be conducted only by using data operating
              parameters of 1200 or 2400 bps. Preselect data operation using KG-84 or
              ANDVT at one of these rates before initiating the test.

         (1) After placing the AN/PRC-117F into normal mode dedicated SATCOM
operation, press the CALL button on the KDU.

         (2) Press ENT to initiate the SATCOM RSSI test.

         (3) Watch display for test completion. A relative signal strength score is
displayed with a value from 000 to 100. Repeat test and adjust pointing of the
SATCOM antenna to obtain a better than 80 score.

         (4) Press CLR to exit SATCOM RSSI test.

    b. Perform the following procedure for dedicated UHF SATCOM operation:

         (1) Rotate function switch to cipher text (CT) or TD. The AN/PRC-117F does not
allow plain text (PT) non-secure voice operation in SATCOM to operate in a non-secure
SATCOM mode. The radio defaults to DATA only operation when PT is selected.

         (2) After the radio initializes, press MODE.

         (3) At the OPERATIONAL MODE prompt, select NORMAL; press ENT.

         (4) Select the desired SATCOM net preset by pressing the PRE + or – switch.

         (5) Begin radio operation. See Figure C-3 for SATCOM operational displays.

4. SATCOM 181B Data Operation Using KG-84 COMSEC and Continuous
Phase Modulation

    a. When using a SATCOM net preset using KG-84 COMSEC and Continuous Phase
Modulation (CPM) modulation, the sender transmitting station decides in which CPM
data option to conduct the transmission. The receiving end must also use a CPM data
code of the same channel type. To change the data option code for the currently selected
SATCOM net preset—

         (1) Press the circular arrow key to view the data option page of the SATCOM net
preset. See Figure C-3 for SATCOM displays.

         (2) Use left/right arrow key to scroll over to data option field. With the up/down
arrow key, select the required code. Only the data option codes relating to the presently
selected COMSEC mode and/or satellite channel type can be selected.

C-6


---

         (3) Refer to Table C-6 AN/PRC-117F DAMA SATCOM capabilities. If COMSEC
mode needs to be changed to achieve required data option, use the COMSEC menu
under OPT key.

                                Figure C-3. Dedicated UHF SATCOM Displays
    b. To send SATCOM DATA with CPM data option—

         (1) Ensure net communications plan is for all outstations to use a CPM data
option from Table C-7 for the same channel type (5-kHz or 25-kHz). A synchronous data
transmission application is best.

         (2) Sending station selects the desired CPM data option with which to transmit
the data message. On transmitting the message, the receiving radio automatically
matches speed of the sending station.

         (3) If transmission is unsuccessful, (the receiving end does not acknowledge good
reception), it may be necessary to reduce the CPM data rate and re-attempt the data
transmission. If transmissions continue to be unsuccessful, troubleshoot the
communications software set up to determine the communications failure.

                                                                                                                                   C-7


---

5. AN/PSC-117F DAMA UHF SATCOM

    a. UHF DAMA SATCOM is a separate mode of operation in the AN/PRC-117F.
DAMA operation is available on 5-kHz and 25-kHz UHF SATCOM channels that have
been converted to DAMA control. THE 25-kHz DAMA is operated in either automatic
control (AC) or distributed control (DC). Refer to Table C-6 AN/PRC-117F DAMA
SATCOM for capabilites.

     Table C-6. AN/PRC-117F DAMA SATCOM Capabilities

     Channel Type     MOD        COMSEC     Data Voice  Data Rates

     DAMA UHF           5K CKT     ANDVT        VOICE                  2400
     SATCOM (AC)        5K CKT     ANDVT        DATA           600, 1200, 2400
                        5K CKT     KG-84C       DATA     75, 300, 600, 1200, 2400
     DAMA UHF           5K MSG     KG-84 C      DATA     75, 300, 600, 1200, 2400
     SATCOM 25-kHz      25K AC     ANDVT        VOICE
     (DC)               25K AC     ANDVT        DATA                   2400
                        25K AC     KG-84 C      DATA           600, 1200, 2400
     DAMA UHF           25K DC     ANDVT        VOICE    75, 300, 600, 1200, 2400
     SATCOM             25K DC     ANDVT        DATA
     Dedicated Calls    25K DC      KG-84       DATA                   2400
     (DASA)             25K DC     VINSON       VOICE          600, 1200, 2400
                        25K DC     VINSON       DATA     75, 300, 600, 1200, 2400
                         25-kHz    VINSON       VOICE
                         25-kHz    VINSON       DATA                 16 kbps
                         25-kHz    KG-84C       DATA                 16 kbps
                                                                     16 kbps
                         5-kHz     ANDVT        VOICE                16 kbps
                         5-kHz     ANDVT        DATA     75, 300, 600, 1200, 2400,
                         5-kHz     KG-84C       DATA             4800, 16 kbps

                                                                       2400
                                                               600, 1200, 2400
                                                         75, 300, 600, 1200, 2400

    b. Figure C-4 depicts the overall DAMA UHF SATCOM programming menu tree.
Entry into DAMA programming takes the radio offline (not communicating).

C-8


---

                            Figure C-4. Overall DAMA Programming Menu Tree
    c. Table C-7 is the overall DAMA programming checklist. Figure C-5 is DAMA net
preset programming menu tree.

                                                                                                                                   C-9


---

                    Table C-7. DAMA Programming Checklist

    Menu Item       Options                   Remarks

Nets (10) 00 to 09           PRESETS
Port_Config (10)
                                              Sets up the parameters required to access a
      00 to 09                                                   DAMA channel.
Destinations (50)
                                              Matches the DAMA channel with the desired
      00 to 49                                       COMSEC and mode of operation.

      Defaults                                Sets all the call parameters to use a TBA on
                                                         any type of DAMA channel.
Select Info Code
AC # # (01 to 99)            DEFAULTS
Select Info Code
DC # # (01 to 99)                             Sets defaults in CALL operating menu.

    Satellite ID             CODES

      EPOCH         Report Response Code      Allows programming of expected response
                        AC # # # # # # #                        to report codes.
   Longitude of
      ASCEN         Report Response Code          Allows for programming of expected
                           AC # # # # #                  response to report codes.
     Inclination
   Argument of               EPHEM

      Perigee                   0 to 9        A storage location linking programmed data
    Eccentricity                              to the corresponding number in the DAMA
   Mean Motion            DD/MM/YYYY
  Mean Anomaly      000.00000 to 359.99999            net preset, not a UFO number.
                    000.00000 to 179.00000
    Menu Item       000.00000 to 359.99999     The data for the TLE data set being used,
Location Method                                   not the current date unless the same.

     Longitude                                Calculated from the TLE for the UFO being
      Latitude                                                        ranged.
       Altitude
                    0.00000000 to 0.99999999
                    0.00000000 to 0.99999999

                     000.00000 to 359.99999

                             LOCATION

                             Options                                Remarks
                                GPS                 Requires PLGR to radio interface.

                              Manual          Decimal minutes format in WGS-84 datum.
                    DDD MM.MMMM E/W

                      DD MM.MMM N/S
                    +/- 00000.0 to 99999.9

                              meters

C-10


---

                    Figure C-5. DAMA Net Preset Programming Menu Tree
d. Table C-8 is the DAMA net preset programming parameters checklist.

                                                                                                                            C-11


---

                  Table C-8. DAMA Net Preset Parameters

     Menu Item    Options                    Remarks

     Orderwire                  TRANSEC
     Encryption
  Key Location 0       OFF                                  PT EOW operation.
  Key Location 1                             ON by present doctrine. Requires TSKs to
  Key Location 2        ON
  Key Location 3                                      be assigned to key locations.
  Key Location 4       None
  Key Location 5  TSK 01 to 25                DAMA EOW TSKs loaded to SATELLITE
  Key Location 6                                              storage positions.
  Key Location 7       None
                  TSK 01 to 25               Assign proper key where channel controller
  Base_Address                                                expects to find it.
     Guard_List        None
                  TSK 01 to 25              IF not known, assign key to all key locations.
 Transmit Power
Change Net Name        None       ADDR
                  TSK 01 to 25

                       None
                  TSK 01 to 25

                       None
                  TSK 01 to 25

                       None
                  TSK 01 to 25

                       None
                  TSK 01 to 25

                  00001 to 65535             Add up to 15 TBA and/or network
                  Address to add:                          addresses.
                  00001 to 65535
                                               View programmed addresses.
                       Review                       Removes an address.
                        Delete

                                      POWER

                  1 to 20 watts              Steps in one-dBm increments.
                                     NAME

                  DAMANET 0 to 9             12 characters alphanumeric, no spaces.

    e. Table C-9 is the DAMA port configuration preset parameters. Figure C-6 is the
DAMA port configuration preset menu tree.

C-12


---

Table C-9. DAMA Port Configuration Preset Parameters

     Menu Item      Options                    Remarks

    Crypto Mode                 COMSEC

  Encryption Key                None                         Function switch in PT.
    Analog Data               VINSON                   Not available on NB channels.
   KG-84 SYNC                  ANDVT
        Mode                   KG-84                          2400 max data rate.
                                                                     Data only.
 Training Frames           TEK 01 to 25
                                                 Load TEKs first. Do not program empty
     Data/Voice                  YES                                  position.
  SYNC/ASYNC                     NO
                       Redundant Mode 1        External devices with own modem, such as
        Select         Redundant Mode 2                              KL-43C/F.
     Baud Rate      Non-Redundant Mode 3
                    Non-Redundant Mode 4          Match mode used in net. PSC-5 only
25-kHz Port Config                                         compatible with Mode 4.
         Code        6, 9, 12, 15, 30, or 60
                                               Sets length of training frames sequence for
5-kHz Port Config                                KY-99 compatibility, 9 is default setting.
         Code
                             DATA/VOICE
   Change Name
                      AUTO ON ADF PORT             With VINSON, select port on which to
                     AUTO ON DATA PORT                            receive DATA.

                          DATA or VOICE                     With ANDVT COMSEC.
                                 DATA                        With KG-84 COMSEC.
                                ASYNC               ASYNC requires port programming.
                                 SYNC
                                               COMSEC mode and CHAN type dependent.
                    WB to 75, 300, 600, 1200,
                       2400, 4800, 16 kbps

                    NB to 75, 300, 600, 1200,
                                  2400

                    CONFIG_CODE

                     01 to 99                       Use configuration code that matches
                    001 to 511                 COMSEC type, data rate, and data device.

                                                       Refer to Appendix B, Table B-2.

                                               Add leading zero, same codes as in 25-kHz
                                                    DAMA. Use configuration code that

                                               matches COMSEC type, data rate, and data
                                                  device. Refer to Appendix B, table B-2.

                                    NAME

                    DAMACFG 0 to 9             12 characters alphanumeric, no spaces.

                                                        C-13


---

              Figure C-6. DAMA Port Configuration Preset Programming Menu Tree
    f. AN/PRC-117F DAMA destination presets may be used on any type of DAMA
channel. All necessary elements for each type of channel are included in the preset.
Table C-10 is the preset checklist and Figure C-7 is the preset programming tree.

C-14


---

Table C-10. DAMA Destination Preset Programming Checklist

     Menu Item       Options                    Remarks

     Destination                         5-kHz

          Add        TBA 00000 to 65535         5-kHz channels allow calls only to one
Destination to Add:                                                address.

        Review                25-kHz AC
        Delete
   Circuit Number    1: 00001 to 65535              25-kHz AC operation allows up to five
Search Area (5-kHz   2: 00001 to 65535                    addresses to be designated.
         Only)       3: 00001 to 65535                     Conference call capability.
   Change Name       4: 00001 to 65535
                     5: 00001 to 65535          Allows checking of programmed addresses.
   Are You Sure?     Destination X of X                        Remove an address.

                      00000 to 65535

                              25-kHz DC

                     10000 to 10999             Enter authorized 25-kHz DC circuit number.

                              SEARCH

                     Local                              Local footprint only.
                     Global                     Sets up 5-kHz MHOP operation.

                                     NAME

                     DAMADEST0 0 to 49          12-digit alphanumeric name.

                                     CLEAR

                     YES                        Used to clear all parameters in the preset

                     NO                         being programmed.

                                                                               C-15


---

      Figure C-7. DAMA Destination Preset Programming Menu Tree

    g. DAMA defaults set which items appear as default values throughout the
AN/PRC-117F DAMA CALL menus. This speeds up operation by reducing the amount
of scrolling needed to reach the proper CALL parameters. All options for making calls
are still available in the CALL menus, regardless of DAMA defaults initially
programmed. Refer to Table C-11 for the checklist and Figure C-8 for the defaults
programming tree.

              Table C-11. DAMA Defaults Programming Checklist

 Menu Item    Options                  Remarks

 Precedence            OUT OF SERVICE
Reason Code
                  Routine, Priority,        Use only authorized precedence.
   Duration   Immediate, Flash, Flash
                                                   User developed codes.
Addresses to   Override, Emergency     Requires setting the amount and the units
     Page                Action
                        00 to 99                    before pressing ENT.
                                                   Use 0000 for indefinite.
                 # # # # - Seconds,
               Minutes, Hours, Days

                            PAGE

              1: # # # # #             00000 to 65535
              2: # # # # #
              3: # # # # #

C-16


---

                Table C-11. DAMA Defaults Programming Checklist

  Menu Item     Options                                      Remarks
Link Test Rate
                  9.6k   LINK _TEST
                  19.2k
                   32k                     Sets default link test data rate when
                                     conducting link tests. Refer to Table C-13 for

                                           times required to complete link tests.

                             CALL

   Duration       # # # # - Seconds,  Requires setting the amount and the units
                Minutes, Hours, Days               before pressing ENT.
  Dedicated                                       Use 0000 for indefinite.
   Duration
Channel Type             5-kHz CIRCUIT

                           YES        Set YES to make call default to dedicated
                            NO                         DASA operation.

                  # # # # - Seconds,  Requires setting the amount and the units
                Minutes, Hours, Days                before pressing ENT.
                                                  Use 0000 for indefinite.
                         25-kHz
                          5-kHz       Sets the default type of channel requested
                                          when making dedicated DASA calls.

                Figure C-8. DAMA Defaults Programming Menu Tree

                                                                 C-17


---

    h. Passive ranging and ephemeris data is used when the tactical situation dictates
the need to control emissions from the radio. Refer to Table C-12 to determine the
necessary elements required for passive ranging programming and operation.

                   Table C-12. DAMA Ranging Methods

         Ranging    Transmit        Time    Location  EPHEM      5-kHz Log in
      Method Used  Capability    (Options)              Data
                                               Not       Not    Over-the-Air or
           Active   Full Silent      Not    Required             Preassigned
                                 Required             required
          Passive   Full Silent                Yes              Over-the-Air or
                   (5-kHz) Yes       Yes                Yes      Preassigned

                                              WARNING

      Contact with the antenna or exposure directly in front of the antenna during
      DAMA SATCOM transmissions may cause injury to personnel. In DAMA
      SATCOM operation, the AN/PRC-117F interacts automatically with the channel
      controller, transmitting and receiving as needed. This automatic transmission
      may not be apparent to the operator; therefore, all personnel should avoid
      contact with the antenna or exposure directly in front of the antenna.

    i. The 25-kHz DAMA UHF SATCOM is operated in either AC or DC. The
AN/PRC-117F uses the following types of DAMA presets to manage operating
parameters. These presets allow for quick configuration changes to any type of
operation.

         (1) DAMA net presets, 10 each—0 to 9.

         (2) DAMA port configuration presets, 10 each—0 to 9.

         (3) DAMA destination presets, 50 each—00 to 49.

    j. Verify that the SATCOM antenna is oriented correctly using a magnetic compass
to point it on the proper azimuth, as determined from pointing slide rule graphs or
software applications. Make an approximate adjustment in the elevation angle as
needed. SATCOM RSSI test cannot be used in DAMA operation.

    k. Initial operation calls may be either normal DAMA circuit service calls or DASA
dedicated calls. See Table C-9. Perform the following procedure for initial operation:

         (1) Rotate function switch to CT.

         (2) At the OPERATIONAL MODE prompt, select DAMA; press ENT.

         (3) Select the desired DAMA net preset by pressing the left/right arrow keys on
the KDU to scroll to the NET preset number and use the KDU numeral keys to enter
the desired net preset number.

    Note: In DAMA mode, the PRE + / – key on the KDU is disabled to prevent
              inadvertently changing the net preset while in a net connected state.

C-18


---

         (4) Press the circular change key to see that the proper DAMA port configuration
preset is selected for the intended DAMA service request. If a different DAMA port
configuration preset is desired, use the left/right arrow keys on the KDU to scroll to the
preset number. Enter the required preset number and press ENT.

         (5) Begin radio operation. View main screen for network status changes in the
order listed:

                (a) ACQUIRING.

                (b) RANGING (active ranging method only).

                (c) LOGGING IN (5-kHz only).

                (d) CONNECTED.

         (6) Network status of CONNECTED indicates the terminal is ready to request or
receive services in the DAMA network. If terminal does not become connected, check
antenna pointing, loading, and programming assignment of the proper EOW TSK and
TBA. ERROR network status indicates that no DAMA EOW TSK is loaded.

    l. The 25-kHz DAMA has two modes of operation: AC or DC. The channel
controller determines the frame format of the channel and the radio operates
accordingly.

    m. Calls in 25-kHz AC DAMA may be made from one to five terminal or network
addresses. A network address is a predetermined group of terminals operated together
as a network. Determine the following before making a call request:

         (1) Type of Service. Before placing the call, use the proper DAMA port
configuration preset for the service needed from the service state display screen. On
changing the port configuration preset with a connected terminal, the radio sends a
status report B RCCOW to the channel controller for notification of the new
configuration. For DASA dedicated calls in 25-kHz AC DAMA, a port configuration
preset with a configuration code to signify DASA must be used. Refer to current
configuration codes.

         (2) Station(s) to be Called. DAMA destination presets are used in call menus to
select station(s) to be called. TBAs associated with this destination preset are shown on
the line below the DAMA destination preset name.

         (3) Precedence of the Call. Use the proper precedence for the importance of the
required service. If a higher precedence than authorized is used, the call is denied. Not
all terminals have access to every precedence level. Check with organization DAMA
planners and authorization documents. At certain times, the channel controller can
place precedence restrictions. The AN/PRC-117F does not allow calls below this
precedence during these times.

         (4) Duration of the Call. Request enough time to complete the required
communications; service is terminated automatically at the end of this time. See Figure
C-9. Perform the following procedure to place a call using 25-kHz AC DAMA:

                (a) Press CALL key to bring up SELECT REQUEST TYPE.

                (b) Select PLACE A CALL and press ENT.

                                                                                                                                 C-19


---

                (c) Select the destination to be called. Use the left/right arrow keys to select
the DAMA destination preset number field, then enter the preset number needed. As
an alternative, select the destination name field or scroll through the DAMA destination
presets names with the up/down arrow keys. Press ENT when proper destination
preset number or name is in view. The TBAs associated with this destination preset are
shown at the bottom of the display.

      (d) At the next display screen, choose the precedence of the CALL and press

ENT.

Note: When the channel controller places system restrictions, it sets the
         minimum precedence required to place a call on the DAMA channel.
         When this happens, the call precedence not authorized is no longer
         showm on AN/PRC-117F call menus.

                (e) Enter the required call duration in number of seconds, minutes, hours or
days (or input 0000 for indefinite). Use the left/right arrow keys to select between
either the unit digits field or the units. Press ENT when correct time and units are
selected.

                (f) The display returns to the main operational display. Service state
changes to PENDING. Wait for the radio to send the request to the channel controller.

                (g) Observe the following service states:

                 • PENDING—Radio terminal is negotiating the sending of the call
request and action on it from the channel controller. Wait until it becomes active or a
system message is received concerning the request.

                 • ACTIVE—Service request has been granted, the normal indication to
commence operation with the requested service.

                 • QUEUED—Service request is being held and is granted when channel
resources are free. Wait until the service is granted or terminate the call and try again
later.

                 • DEDICATED—Indicates that DASA operation has been granted.
Operation in DASA is ruled by MIL-STD 188-181A covering 5-kHz and 25-kHz
dedicated UHF SATCOM.

                 • IDLE—The radio is not active or is setting up a service.

    n. Terminate a 25-kHz AC DAMA call on completion. The user should terminate
the timed or indefinite call so the channel controller can reassign that channel to
another terminal user in the network.

    o. The 25-kHz DAMA has two modes of operation: AC or DC. The channel
controller determines the frame format of the channel and the radio operates
accordingly.

    p. Calls in 25-kHz AC DAMA can be made from one to five terminal or network
addresses. A network address is a predetermined group of terminals operated together
as a network. Determine the following before making a call request:

C-20


---

         (1) Type of Service. Before placing the call, use the proper DAMA port
configuration preset (from the service state display screen) for the service needed. On
changing the port configuration preset with a connected terminal, the radio sends a
status report B RCCOW to the notify channel controller of the new configuration. For
DASA dedicated calls in 25-kHz AC DAMA, use a port configuration preset with a
configuration code to signify DASA. Refer to current configuration codes.

         (2) Station(s) to be Called. DAMA destination presets are used in call menus to
select station(s) to be called. TBAs associated with this destination preset are shown on
the line below the DAMA destination preset name.

         (3) Precedence of the Call. Use the proper precedence for the importance of the
required service. If a higher precedence than authorized is used, the call is denied. Not
all terminals have access to every precedence level. Check with organization DAMA
planners and authorization documents. At certain times, the channel controller can
place precedence restrictions. The AN/PRC-117F does not allow calls below this
precedence during restricted times.

         (4) Duration of the Call. Request enough time to complete the required
communications; service is terminated automatically at the end of this time. See Figure
C-9. Perform the following procedure to place a call using 25-kHz AC DAMA:

       (a) Press CALL key to bring up SELECT REQUEST TYPE.

       (b) Select PLACE A CALL and press ENT.

                (c) Select the destination to be called. Use the left/right arrow keys to
select the DAMA destination preset number field, then enter the preset number needed.
As an alternative, select the destination name field or scroll through the DAMA
destination presets names with the up/down arrow keys. Press ENT when proper
destination preset number or name is in view. The TBAs associated with this
destination preset are shown at the bottom of the display.

       (d) At the next display screen, choose the precedence of the call and press

ENT.

Note:  When the channel controller places system restrictions, it sets the
       minimum precedence required to place a call on the DAMA channel. The
       call precedence not authorized is no longer shown on AN/PRC-117F call
       menus.

                (e) Enter the required call duration in number of seconds, minutes, hours,
or days (or input 0000 for indefinite). Use the left/right arrow keys to select either the
unit digits field or the units field. Press ENT when correct time and units are selected.

                (f) The display returns to the main operational display. Service state
changes to PENDING. Wait for the radio to send the request to the channel controller.

                (g) Observe the following service states:

                 • PENDING—Radio terminal is negotiating the sending of the call
request and action on it from the channel controller. Wait until it becomes active or a
system message is received concerning the request.

                                                                              C-21


---

                 • ACTIVE—Service request has been granted, the normal indication to
commence operation with the requested service.

                 • QUEUED—Service request is being held and is granted when channel
resources are free. Wait until the service is granted or terminate the call and try again
later.

                 • DEDICATED—Indicates that DASA operation has been granted.
Operation in DASA is ruled by MIL-STD 188-181A covering 5-kHz and 25-kHz
dedicated UHF SATCOM.

                 • IDLE—The radio is not active or is setting up a service.

C-22


---

Figure C-9. DAMA 25-kHz AC Call Menu

                                      C-23


---

    q. Terminate 25-kHz AC DAMA calls on completion. The user should terminate a
timed or indefinite call so the channel controller can reassign that channel to another
terminal in the network. Perform the following procedures to terminate a call:

         (1) From a service state display indicating ACTIVE and time remaining, press
CALL.

         (2) From SELECT REQUEST TYPE display, select TERMINATE CALL with the
up/down arrow keys; press ENT.

         (3) The TERMINATE CALL request is sent to the channel controller. The
channel controller tearsdown the service and the service state of the terminal returns to
one of the service states (IDLE, PENDING, or QUEUED), depending on other ongoing
requests.

    r. Send a 25-kHz AC DAMA out-of-service request to the channel controller instead
of logging out as in 5-kHz DAMA. In these requests, the duration for being out of
service, precedence, and reason code is transmitted. If another station attempts to call
the terminal during the out-of-service period, the channel controller can report the
reason code and time to be out of service to that user. Perform the following procedures
to send an out-of-service request:

         (1) Press CALL key to bring up SELECT REQUEST TYPE display.

         (2) Select OUT OF SERVICE and press ENT.

         (3) Select precedence for out-of-service request and press ENT.

         (4) Enter two-digit numerical out-of-service code.

         (5) Enter duration for the out of service period; use 0000 if it is to be indefinite.
Press ENT.

         (6) The out-of-service request is sent to the channel controller. Watch the
display for acknowledgement from the channel controller.

    s. To return to service in 25-kHz AC DAMA operation, send a status report B
RCCOW (menu item RETURN TO SERVICE) to the channel controller. This informs
the channel controller that the operator has returned. When an operational radio is
unmanned, it is not necessary to use this menu item when turning on after a power off.
The RCCOW sent to the channel controller when connected notifies the channel
controller of return to service. Perform the following procedure to return to service:

         (1) Press CALL key to bring up SELECT REQUEST TYPE display.

         (2) Select RETURN TO SERVICE and press ENT.

         (3) A Status report B RCCOW is sent to the channel controller.

    t. In 25-kHz UHF AC DAMA, an AN/PRC-117F terminal user can page up to three
other terminals. Paging is available only in 25-kHz AC DAMA. Using organization
network planners, determine the procedures on responding to pages. See Figure C-10.
Perform the following procedure to page:

         (1) Press CALL key to bring up service request screen of SELECT REQUEST
TYPE.

         (2) Select PAGE and press ENT.

C-24


---

         (3) Use KDU number keys to type in the first address to page; press ENT to
accept number.

         (4) Repeat step 3above for the second and third addresses. (If no more addresses
need to be paged, type 0000 and press ENT.)

         (5) The radio sends the page request to the channel controller. The paged
station should respond as unit procedure dictates.

                         Figure C-10. Twenty-five-kHz AC Paging and Link Test
    u. To alleviate problems in 25-kHz AC DAMA operation, the channel controller can
send an information request code to request information (INFO Report, see Figure C-
10). from the terminal operator. The terminal operator must respond to the request
with an information report code to continue operation in DAMA. Perform the following
procedure to send an information report code at any other time:

         (1) Press CALL to bring up SELECT REQUEST TYPE display.
         (2) Select INFO REPORT from menu and press ENT.
         (3) Enter the desired information report response code to send to the channel
controller and press ENT. The radio sends the code to the channel controller.
    v. The 25-kHz DAMA has start-link test built into its frame format. Link testing
determines suitability for data operations using more robust frame formats that support
higher burst data rates. It does not reduce channel overhead allotted to supporting

                                                                                                                                 C-25


---

communications. Slower data rate link tests require more time to complete. Refer to
Table C-13. Perform the following procedure to conduct a link test:

      (1) Press CALL key to bring up SELECT REQUEST TYPE display.

      (2) Select START LINK TEST and press ENT.

Note:  This sends a link test request to the channel controller. When the link
       test slot becomes available, the channel controller commands the radio to
       begin the link test. On completion of the link test, the radio displays the
       results in number of bit errors and missed acquisitions during the test.
       Results are recorded automatically by the channel controller and used to
       determine data burst rates. Terminals that show good results in link
       tests are assigned frame formats supporting more robust burst data rates,
       thereby increasing overall data throughput.

       Table C-13. Link Test Data Rates, 25-kHz DAMA

       Link Test Data Rate  Time Required to
                                 Complete
               9.6-kbps
              19.2-kbps       6 to 7 minutes
               32-kbps           2 minutes
                                  1 minute

    w. Abort link test (25-kHz AC or DC DAMA ) and use the radio for another purpose,
perform the following procedure:

         (1) Press the CALL key to bring up the SELECT REQUEST TYPE display.

         (2) Select ABORT LINK TEST and press ENT. The radio aborts the link test
process and terminates the link test.

    x. View network status messages (all DAMA modes). The AN/PRC-117F displays
operational status messages that pop up on the display and are then placed into a
message database while DAMA operation continues. To determine the steps in an
operation while using DAMA, refer to the technical manual for a list of the messages
and their explanation. There are two methods that may be used to view messages while
operating in UHF DAMA SATCOM: message indicator method and options menu
method.

    y. Perform the following procedure for the message indicator method:

         (1) Press the left/right keys to scroll over to the envelope icon on the operational
display and press ENT.

         (2) Use the up/down arrow keys to scroll through the message database.

         (3) Press CLR to return to operational screens.

    Note: When operations on a current DAMA net terminate, all the DAMA status
              messages erase. Some pop-up messages require operator intervention to
              continue.

C-26


---

    z. In 5-kHz DAMA, calls can be made to a single terminal address for a point-to-
point capability or to a sub-net address giving network capability. The nine-second
frame format creates long delays for voice users. The 5-kHz DAMA network operation
was designed and, therefore, more suited for DATA operations. DASA dedicated service
requests are used to handle service requests greater than the DAMA channel can
handle. On entry into DAMA mode using a properly configured DAMA net preset, the
AN/PRC-117F automatically acquires, ranges, and logs in with the channel controller.
Network status shows CONNECTED, if successful. DASA call requests are placed with
precedence of the call and the desired duration. Service request can be granted, placed
in queue, or denied. Calls made with a precedence higher than authorized are denied.
The 5-kHz DAMA has two basic modes of operation of circuit or message service. The
AN/PRC-117F is placed in each mode by changing it on the display. The mode of
operation is selected prior to operation in that mode. If a service message is received
while in circuit mode, the radio is switched to message mode to download the message.

         (1) Circuit service provides half-duplex encrypted voice or data service to a single
destination or to a network, or terminals grouped under a sub-network address.

         (2) Message service is a specialized data mode that provides packet transmission
and reception of data messages up to 14 kilobytes. This requires an external data device
to input the message to the AN/PRC-117F.

    aa. Place a call (5-kHz circuit service or dedicated call). (See Figure C-11.) Requests
for circuit service and dedicated calls are essentially the same. Dedicated service gives
a channel unhindered by the delay the long 5-kHz DAMA frame format. Not all users
have authorized use of dedicated service. Dedicated service is used to support data
rates and message lengths not adequately supported by circuit service. Consider the
following items before placing a call:

         (1) Type of service. Use the proper DAMA port configuration preset for the
service needed. Select this preset from the service state display screen before placing
the call.

         (2) Station(s) to be called. DAMA destination presets are used in call menus to
select station(s) to be called. TBAs associated with this destination preset are displayed
on the line below the DAMA destination preset name.

         (3) Precedence of the call. Use the proper precedence for the importance of the
required service. If a higher precedence than authorized is used, the call is denied. Not
all terminals have access to every precedence level. Check with organization DAMA
planners and authorization documents.

         (4) Duration of the call (DASA only). Request enough time to complete the
required communications. Service is terminated automatically at the end of this time.
Additionally, when making DASA calls, select either 5-kHz NB or 25-kHz WB channels.
Perform the following procedure to place a call using 5-kHz DAMA:

                (a) Rotate function switch to CT.

                (b) After the radio initializes, press MODE.

                (c) At the OPERATIONAL MODE prompt, select DAMA; press ENT.

                                                                                                                                 C-27


---

                (d) Select the desired DAMA net by pressing the left/right arrow keys on the
KDU to scroll to the NET preset number. Use the KDU number keys to enter the
desired net preset number.

                (e) Press the circular change key to view that the proper DAMA port
configuration preset is selected for the intended DAMA service request. If a different
DAMA port configuration preset is desired, use the left/right arrow keys on the KDU to
scroll to the preset number. Enter the required preset number and press ENT.

                (f) Begin radio operation. View main screen for network status of
CONNECTED.

                (g) Use the circular arrow key to check service state screen for 5-kHz CKT
mode. If in MSG mode, use the left/right arrow keys to scroll to mode and change to
CKT mode.

                (h) Press CALL key to bring up SELECT REQUEST TYPE.
                (i) Select PLACE A CALL and press ENT.
                (j) To select the destination to be called, use either—
                 • The left/right arrow keys to select DAMA destination preset number for
numeric entry of the destination
                 • The up/down arrow keys to select the destination preset name for the
desired destination.

    Note: The five-digit terminal addresses associated with this destination preset
              show on the bottom line of the display.

                (k) At next display screen, choose the precedence of the call and press ENT.
                (l) At DASA REQUEST? prompt, select YES for dedicated service and NO
for regular DAMA circuit service.
                (m) Enter the required DASA call duration in numerical units of seconds,
minutes, hours, or days (or use 0000 for indefinite). Press ENT when proper time and
units are selected. Time is not entered for normal DAMA calls.
                (n) For DASA dedicated calls, channel type (5-kHz or 25-kHz) is also
requested in the call request. This menu option is not shown when making a normal
DAMA circuit service call.
                (o) The display returns to the main operational display. Service state
changes to PENDING. Wait for the radio to send the request to the channel controller.
                (p) Observe the service state display for the following indications:
                 • PENDING—Radio terminal is negotiating the sending of the call
request and action on it from the channel controller. Wait until it becomes active or a
system message appears concerning the request.
                 • ACTIVE—Service request is granted. This is the normal indication to
commence operation with the requested service.

C-28


---

                 • PREEMPTED—An active service is preempted by a higher priority
service. Wait for the service to become active again.

                 • DEDICATED—Indicates that DASA operation is granted. Operation in
DASA is ruled by MIL-STD 188-181B covering 5-kHz and 25-kHz dedicated UHF
SATCOM. Use the appropriate DAMA port configuration preset needed for the DASA
service.

                 • IDLE—The radio is inactive or setting up a service.

                                       Figure C-11. Call Menu 5-kHz DAMA
    bb. Perform teardown service (5-kHz). If time is still remaining or if indefinite time
period (0000) is selected, circuit service and dedicated service are torn down on

                                                                                                                                 C-29


---

completion of the communications. Perform the following procedure for service
teardown:

         (1) At end of using a DAMA service, press CALL key on KDU.

         (2) Use up/down arrow keys to scroll to TEARDOWN. Press ENT to begin
teardown.

         (3) Use the up/down arrow keys to select the desired service to teardown. Press
the circular arrow keys to view the second screen of the service state.

         (4) Press ENT to teardown this service.

    cc. Terminate call (5-kHz dedicated call only). If time is remaining, dedicated calls
should be terminated. Perform the following procedure to terminate a dedicated call:

         (1) At the end of using DASA dedicated service, press CALL button on KDU.

         (2) Use up/down arrow keys to scroll to TERMINATE CALL.

         (3) Press ENT to terminate call.

         (4) Service state goes to IDLE after reacquiring the network home channel.

    dd. Send a message using 5-kHz DAMA message service. DATA messages of less
than 14 kilobytes are uploaded to radio and the packet is sent to the destination
address. The terminal prompts a message upload to the radio. Perform the following
procedure to send a message:

         (1) Ensure the DATA device is connected to the J1 ADF connector or J3 data
connector and is ready for operation with a message to be transmitted.

         (2) Select a DAMA port configuration preset that properly interfaces the data
device to the radio using KG-84C encryption.

         (3) Press the circular arrow keys to move display screens to service state screen
to place radio in MSG mode. If radio is in CKT mode, use the left/right arrow keys to
scroll to MODE and change to MSG mode with the up/down arrow keys, then press
ENT.

         (4) Press CALL key to bring up display for SELECT REQUEST TYPE. See
Figure C-12.

         (5) Select SEND A MESSAGE and press ENT.

         (6) Select DAMA destination preset to which the message is sent and press ENT.
TBAs associated with this preset are shown across the bottom line of the display.

         (7) The next display is SELECT PRECEDENCE. The display shows the
precedence last used to call the selected destination. Press ENT to keep that precedence,
or scroll and select an alternate message precedence.

         (8) After a brief configuring screen, the terminal prompts the user to ENTER
MESSAGE to the radio. Send the message on the data device to upload it into the
radio. Press CLR to abort.

         (9) When uploading is complete, the service state indicates IDLE with a message
status of one (1) for outgoing. After the message is transmitted, the outgoing message
indicator number decreases.

C-30


---

    ee. Receive a data message using 5-kHz DAMA message service. Depending on
operation of the particular data device, the radio is programmed to either automatically
download a received message from the radio buffer to the data device, or manually
download a received message after the data device is ready to accept it from the radio.
When using manual message release, remember to download messages so additional
messages are received without losing important data. When using 5-kHz message
service, the AN/PRC-117F is operated with a network state of CONNECTED and a
service state of IDLE. When a sender initiates sending a data message to the terminal,
the channel controller looks for the presence of the destination terminal and sets up a
service between the two terminals. On successful transmission, the AN/PRC-117F
indicates (in its message buffer) that it is holding a message for downloading. If the 5-
kHz MSG mode is set to AUTO instead of MANUAL, it sends the message immediately
to the interfaced output data device. Perform the following procedure to download a
message using 5-kHz message service with manual message mode:

         (1) Verify there is a buffered message in the radio and the radio is in MSG mode.
         (2) Connect the data device to either the J1 ADF connector or J3 data port, as
applicable, and ensure it (connector or port) is ready to receive the message.
         (3) Press the CALL key and bring up SELECT REQUEST TYPE display.
         (4) Select DOWNLOAD MESSAGE and press ENT.
         (5) The service state changes to DOWNLOAD and the message is sent to the
data device. When complete, the service state changes back to IDLE.
         (6) Check the data device for proper reception of the message. The incoming
message number is decremented.

                                                                                                                                 C-31


---

       Figure C-12. MSG Service Call Menu, 5-kHz DAMA

    ff. Log out of 5-kHz DAMA. To leave the 5-kHz DAMA channel, the terminal must
log out with the channel controller. Also, this is required if shutting the radio off for
any reason (such as changing the batteries or adjusting the antenna). Perform the
following procedure to log out of a 5-kHz DAMA net:

Note:  If the radio goes off the net without logging out, the channel controller
       automatically logs it out after it missed 200 ROWs (approximately 30
       minutes). Until it logs out, the channel controller considers the terminal
       logged in. If the terminal attempts to log in a second time, the channel
       controller may reject the second log in attempt. If a log in is rejected, go
       into net preset programming (Figure C-6) and change log in type to
       preassigned. The terminal is connected again. Return setting to over-
       the-air after the net connects again.

         (1) Press the CALL key to bring up the SELECT REQUEST TYPE display
screen.

C-32


---

(2) Use the up/down arrow keys to select LOG OUT; press ENT to log out.

Note:  The service state and network state switch to DISABLED after the
       channel controller acknowledges the log out request. The radio is
       switched to another DAMA net preset, or turned off. Figure C-13, Figure
       C-14, and Figure C-15 provide screen displays and descriptions for the
       radio.

       Figure C-13. DAMA Network State Displays, 5-kHz and 25-kHz
                                                                                                                  C-33


---

                            Figure C-14. DAMA Service State Displays, 25-kHz
C-34


---

Figure C-15. DAMA Service State Displays, 5-kHz
                                                                                                  C-35


---



---

            Appendix D

AN/PSC-5 Series Radios

1. Line of Sight (LOS) Operations

    a. Press ESC until the main menu is displayed.
    b. Press 3 (set presets).
    c. Press 1 (set mode presets).
    d. Select LOS.
    e. Enter the preset number (1 to 6).

                                                        SET PRESET
                                                        LOS -P#
                                                        TEK#
                                                        Normal
                                                        R###.###

    f. Enter the COMSEC key number (1 to 5).
    g. Select modulation (amplitude modulation [AM], frequency modulation [FM] or
frequency-shift keying [FSK]).
    h. Select encryption type (VINSN, FASCN, 3KG-84, 4KG-84).
    i. Select mode (V or D).
    j. Select data rate.
    k. In orderwire encryption PT only, select normal.
    l. Select transmit power level (see Table D-1).
    m. Enter receive frequency (030.000 to 399.975).

Table D-1. Lind of Sight (LOS) Operations

       FREQs        Modulation        Power
 30.000 to 87.975     FM/FSK      23 to 43 dbm
108.000 to 129.975       AM
                                  23 to 38 dbm
130.000 to 148.975  AM/FM/FSK      23 to 38 AM
156.000 to 173.975    FM/FSK    23 to 39 FM/FSK
225.000 to 399.975
                                  23 to 39 dbm

                                                                                   D-1


---

    n. If the transmit frequency is the same as the receive frequency, press ENT.
Otherwise enter a new transmit frequency.

    o. To load additional presets, repeat steps e through n.

    p. Perform the following procedure for LOS operation.

         (1) In the current mode screen, select LOS.

         (2) Enter the preset number (1 to 6).

         (3) Check all fields to ensure they are correct.
                                                    CURRENT MODE
                                                    LOS -P# Sq- -054
                                                    TEK# FM VINSN D16K
                                                    Normal Tpwr 37 dbm

    q. Proceed with communications.

2. SATCOM Operations

    a. Press ESC until the main menu is displayed.
    b. Enter 3 (set presets).
    c. Enter 1 (set mode presets).
    d. Select SATCOM.
    e. Enter the preset number (1 to 6).
    Note: Modulation is not selectable. Satellite loopback is not performed in FSK.

                                       SET PRESET

                               SATCOM -P#

                               TEK# FSK VINSN V16K

                               Normal            Tpwr 43 dbm

     f. Enter COMSEC key (1 to 5).

     g. Select encryption type (ANDVT, VINSN, 3KG-84, 4KG-84).

     h. Select mode (V or D).

     i. Select data rate (1200, 2400, 9600, 16 kbps).

     j. Enter/select power level (23 to 43dbm).

     Note: It may be necessary to re-enter the encryption type and data rate after
              entering the channel number.

D-2


---

k. Enter channel number (009 to 239) or 999 to enter frequency pairs manually. Using

the home channel number is recommended. SATCOM loopback cannot be utilized if 999 is

the channel number.

                     Channel Number: ###

                     R###.###          T###.###

                     DIFF

    l. If 999 was entered in previous step, enter the receive and transmit frequencies
(225.000 to 399.995).

    m. Select encoding type (DIFF or NDIFF). Radios must have the same encoding type to
communicate.

n. To load additional presets, repeat steps d through m.

o. Perform the following procedures for SATCOM operation.

(1) In the current mode screen, select SATCOM.

(2) Enter the preset number (1 to 6).

(3) Check all fields to ensure they are correct.

                                                          CURRENT MODE
                                                  SATCOM -P# Sq-__-030
                                                  TEK# FSK VINSN V16K
                                                  Normal Tpwr 43 dbm

3. DAMA 5-kHz Operations

    a. Perform the following to select 5-kHz input/output (I/O) rates. (See Table D-2 for I/O
data rates.)

                     Table D-2. I/O Data Rates for 5-kHz DAMA

 Baud                KG-84 Data        ANDVT Data         ANDVT Voice
 75                         X                 X                   X
300                         X                 X
600                         X                 X
1200                        X                 X
2400                        X                 X
9600                        X
16 k                        X

(1) Press ESC until the main menu is displayed.
(2) Press 2 (database options).
(3) Press 4 (5-kHz I/O rates).
(4) Use NEXT/PREV to select a field.

                                                                                        D-3


---

         (5) Use arrow keys to select (or deselect) each option, then press ENT.  If voice is
used, 2400 is checked by default.

                                                   DAMA 5KHz I/O RATES
                                                   __75 __300 __600
                                                   __1200_ 2400 __9600
                                                   __16k

     (6) Repeat steps 4 and 5, as required.

     (7) When completed, press ESC to return to the database menu.

    b. To ensure the terminal receives communications from a terminal, place that
network address (common guard, private guard, or subnet) in the guard list (do not enter
the terminal address). To add to (or change) the guard list, follow the procedure below.

     Note:  The guard list is a set of addresses for which a terminal receives services.
            The guard number is the address of a single terminal or network. Terminal
            addresses from which communications need to be received by a specific
            terminal are placed in the guard list. When a terminal address is placed in
            the guard list, the control station logs that address into the network.

            The guard list procedure is not recommended for 5-kHz DAMA. If a guard
            list is used for a 5-kHz terminal, ensure the terminal addresses placed in the
            guard list are not used by another active terminal.

            The demarcation point divides addresses between single terminals and
            networks. Addresses below the demarcation point (single terminals) should
            usually be left off the guard list.

     (1) Press ESC until the main menu is displayed.

     (2) Press 2 (database options).

     (3) Press 2 (guard list).

     (4) Select desired action (add, delete, modify, or view).

     (5) Perform the following, as required:

            (a) Add/enter address.

            (b) Delete—use NEXT/PREV to move to the desired address; press ENT.

            (c) Modify—use NEXT/PREV to move to the desired address; enter the new

address.

            (d) View—use NEXT/PREV to scroll through the list.

            (e) When completed, press ESC to return to the database menu.

D-4


---

GUARD LIST                             Note: 64000 is an
VIEW                                        example only. Do
1 64000 ------ -----                        not enter it as a
4 ----- ------ -----                        default setting.
7 ----- ------ -----
10 ----- ------ -----
13 ----- ------ -----

c. Perform the following procedure to enter a DAMA preset.

(1) Press ESC until the main menu is displayed.

(2) Press 3 (set presets).

(3) Press 1 (set mode presets).

(4) Select DAMA..

(5) Enter preset number (1 to 6).

                                     SET PRESET

                             DAMA -P#

                             TEK# PSK ANDVT V2400

                             5 KHz     Tpwr 35 dbm

Note: Modulation is not selectable.

(6) Enter the COMSEC key number (1 to 5).

(7) Select encryption type (ANDVT, 3KG-84, 4KG-84).

(8) Select mode (V or D).

(9) Select data rate (75 to 2400).

(10) Select DAMA type (5-kHz).

(11) Enter/select power level (23 to 43 dBm).

(12) Enter channel number (129 to 191, 194 to 239).  Corresponding frequencies are

displayed on the next line.

                             Channel Number: ###

                             R###.###  T###.###

                             Code:##   OW:CT

                             Normal Range: Active

(13) Enter configuration code.

(14) Select orderwire encryption (PT or CT).

(15) Select mode of operation (normal, EMCON, silent).

(16) Select ranging (passive, active, maintenance).

(17) If passive ranging, enter satellite number (1 to 8).

(18) For 5-kHz DAMA, select log in (preassigned, over-the-air).

(19) If preassigned, select precedence (FO, F, I, P, R).

                                                                 D-5


---

     (20) If preassigned, enter demarcation number 49999.   If demarcation number is not

entered in preset, the radio defaults to 16384.

                                 Channel Number: ###

                                 R###.###         T###.###

                                 Code:##          OW:CT

                                 Normal Range: Passive

                                 Satellite ID: 4

                                 Login: Preassigned

                                 Prec:R Dmark:49999#

     d. Perform the following procedure to enter a 5-kHz service preset.

     (1) Press ESC until the main menu is displayed.

     (2) Press 3 (set presets).

     (3) Press 2 (5-kHz service).

     (4) Enter preset number (01 to 20).

                                 SET PRESET 5K P01

                                 CIR EN SYN V2400

                                 Prec:R           D:#####

                                 Code:###

     (5) Select type of service (CIR or DASA).

     (6) Select encryption (EN or UN).

         (7) Select data communications (SYN or ASYN, see Table D-3). Use synchronous
unless sending asynchronous data in PT.

     Table D-3. SYN/ASYN Settings

     Data Device Type                      Mode Switch      Selection
     Synchronous                              PT or CT         SYN
     Asynchronous                                 PT          ASYN
     Asynchronous                                 CT           SYN

     (8) Select mode (V or D).
     (9) Select data rate (75 to 16k). Data rate is selected in the 5-kHz I/O rates menu.
     (10) Select precedence (FO, F, I, P, R).
     (11) Enter destination address.
     (12) Enter configuration code.

D-6


---

(13) For DASA only, enter time requested in hours and minutes, or select

INDEFINITE. Maximum time is 85 hours 15 minutes, in five-minute increments.

Indefinite is 85 hours 15 minutes.

                            SET PRESET 5K P01

                            DSA EN SYN V2400

                            Prec: R      D:#####

                            Code:###

                            INDEFINITE

(14) To load additional presets, repeat steps 4 through 13 above.

e. Perform the following to enter a 5-kHz message preset.

(1) Press ESC until the main menu is displayed.

(2) Press 3 (set presets).

(3) Press 4 (5-kHz message).

(4) Enter preset number (01 to 20).
                                         SET PRESET 5K MESG
                                         XMIT P01
                                         TEK1 3KG84
                                         PREC: R EN D:#####

(5) Enter the COMSEC key number (1 to 5).

(6) Select encryption type (3KG-84, 4KG-84, ANDVT).

(7) Select precedence (FO, F, I, P, R).

(8) Select encryption (EN or UN).

(9) Enter destination address.

(10) To load additional presets, repeat steps 4 through 9 above.

f. To start a 5-kHz DAMA network service quickly, perform the following.

(1) In the current mode screen, select DAMA.

(2) Enter preset (even if displayed already).

(3) Enter the service preset number (01 to 20).

Note: Verify terminal DAMA address is correct before continuing.

(4) Press ENT on start DAMA..

                                                                             D-7


---

     (5) Observe display. See Table D-4 if LOGIN is rejected by controller.

           CURRENT MODE

     DAMA -P1                               - -060

     TEK1 PSK ANDVT V2400

     5KHz                           Tpwr 35 dbm

     Channel Number: 136

     R248.900                          T302.500

     Code: 060                         OW:CT

     Normal Range: Active

     Login: Over The Air

     Service Preset: 01
          Start DAMA for 01000

     DAMA                              SQ - - 045

     5K        Acquiring N

     SRV-Idle

     1-Service Setup

     (a) Acquiring—Acquisition in process.

     (b) Range—Wait while ranging in process.

     (c) Log in—Manual log in required.

     (d) Log in-Pnd—Login pending.

     (e) Connected—Log in successful.

         (6) At SRVC ASGND popup message, enter on ACCEPT. To reject the service, use
the arrow keys to select REJECT and press ENT key.

     Note: When a warning or error message is displayed, refer to tables D-5 and D-6 for
              proper corrective action.

                                                  Srvc Asgnd
                                                  CIR TEK ANDVT V2400
                                                  Prec:R EN D:01000
                                                  SYN S:02000 {ACCEPT}

     Note: When SRV-RX/TX appears on the display, the terminal is ready for normal
              communications. See Table D-7 for hot keys to access additional tasks.

D-8


---

                       Table D-4. Messages, 5-kHz DAMA

Message                Action
   A
                       Terminal is not receiving OW. Check azimuth, power out, and reposition
Acquisition Failed     antenna.

C        Circuit       Check previous status messages. If logged out, log in over-the-air. Other
                       messages include circuit not available (especially DASA) and the reason.
   Aborted             Attempt to re-establish or establish a different type of service.
                       Circuit service request is denied for the stated reason. If condition is
Denied (Reason)        correctable, take appropriate action or try again later.
                       An incoming service is established but a mismatch is detected between the
Mismatch Detected      service and the current mode settings. Check setting of PT/CT mode and
                       type of attached data device.
  Preempted            The channel controller preempted the circuit. Wait for it to resume before
                       transmitting.
Receive Buffer
    Overflow                Or
                       Contact was temporarily lost with the controller; wait for it to resume.
Set up Queued          Check data device for incomplete message or errors in message. If needed,
    (Reason)           request source to retransmit message.
                       Service is queued for the reason supplied.
    Set up Rejected    Local—terminal called is logged in but time-slot is unavailable.
        (Reason)       MHOP—terminal called is not logged in with controller. If it is in another
                       footprint, wait. If it is supposed to be in the current footprint, teardown and
Terminated (Reason)    try again later.
       COMMAND         Service request is denied for the stated reason. Try again later unless one
         Rejected      of the following reasons is displayed.
                       Data Rate—Requested a DASA service at higher than 2400 bps—no 25-kHz
Rejected Port is busy  DASA channel available.
    (Check Current     Not Assignable—The LQ from terminal or the destination terminal is poor.
          Mode)        Check LQ in network state menu. If LQ is low, check antenna or raise
                       power.
                       Prec. Violation—The precedence entered is not allowed. Check network
                       state menu for assigned values. Ensure previous messages do not state
                       logged out. If previous message stated logged out, log in over-the-air and
                       re-attempt service set up at lower precedence.
                       Service Restrict—Request for a 2400 bps circuit denied due to network
                       traffic. Reduce data rate or wait until LIO no longer displayed in network
                       state.
                       An existing service is terminated for the stated reason. Try again later.

                       Check parameters and network; try again.

                       Request is rejected because of an existing active service. Ensure terminal is
                       idle before setting up a service.

                                                        D-9


---

                       Table D-4. Messages, 5-kHz DAMA

Message                Action
        CTIC
                       Invalid OW key. Reload OW key in correct position.
   Alarm Invalid Key
 Alarm Invalid Time-   Invalid time-slot number detected. Reload OW key in correct position.

      slot Number      Reload OW key in correct position.
    Alarm Unknown
                       Message from another terminal aborted.
           Cause
   I                   The controller logged the terminal off the network for the reason supplied.
  Incoming Message     Correct the error and perform an over-the-air log in.
From: xxxxx Aborted    Invalid Address on Guard—Check the addresses in the guard list.
  L                    Not Authorized—Terminal address is not in the database—contact the
                       controller if correcting it fails.
       Logged Out      200 Missing FOWs—Once the terminal accumulates 200 FOWs the terminal
         (Reason)      automatically logs itself off. Check antenna and radio. To clear count,
                       change current mode to LOS then return to DAMA. Start DAMA and
        LOG IN         perform a preassigned log in.
 Command Rejected      Invalid Service Request—The terminal is not logged in the network. Log in
                       and resend the service request.
     Failed No PCC
        Response       More than one log in has been attempted; wait for the controller to respond.
                       Try again. If no response, the control station is down. Contact control
Rejected, Invalid Log  station.
       in Address      Terminal address must be in the range of one to the demarcation address
                       (49999). Other possibilities:
      Rejected, No
         Capacity           Log in already accomplished.
                            Logged in on a 25-kHz channel and now attempting to log in on a 5-kHz
      Rejected, Not         channel.
       Authorized           Another operator has the terminal address in their guard list.
        LOG OUT             Trying to log in over-the-air in silent/EMCON mode.
                       To resume, log in preassigned.
 Command Rejected      The current channel has no capacity. Call the controller.
     Failed No PCC
        Response       Terminal is not authorized to participate in the network. Call the controller.
        MESSAGE
                       Attempted to log out more than once—wait the 18 seconds for response.
                       The controller has not responded to the log out request. Shut down the
                       system.

D-10


---

                          Table D-4. Messages, 5-kHz DAMA

Message               Action

   Aborted To:xxxx    Message is aborted for the stated reason. Try again.
        (Reason)

From: xxxx Encrypt    Mode switch (PT/CT) setting is different from the transmitting terminal.
Mismatch Detected     Contact distant end to correct.

                      Transmission rejected. Another operator is transmitting—try again later.

   Input Rejected     Or

                      Radio is in idle—set up a service.

                      Transmission rejected. Another operator is transmitting—try again later.

   Output Rejected    Or

                      Radio is in idle—set up a service.

   Set up Rejected,   Message set up is rejected for the stated reason.
        (Reason)

Terminated Frm: xxxx Message is terminated for the stated reason. Try again later.
   to:yyyy (Reason)

   Mode Command       Terminal address is entered as zero. This is reserved for the controller.
   Rejected, Node     Enter a valid terminal address.
   Address is Zero

Msg Set up Rejected Precedence entered is not allowed. Check network state menu for allowed
Precedence Violation values and re-enter.

  No Resources for Terminal is busy and cannot receive a message from the other terminal.
Message From: xxxx

R  RANGING

   Failed             Check current mode entries and antenna. Run BIT to verify terminal
                      operation.

   Overdue Transmit   A successful ranging attempt is not completed as scheduled. Transmission
         Inhibited    is denied. Check antenna. Transmit a ranging burst using the contention
                      ranging menu.

S  SERVICE SET UP

Command Rejected Verify connected and logged in and try again.

Rejected, Invalid Data Ensure a valid data rate is selected.
            Rate

T

Teardown Command The terminal has rejected the teardown request. Verify Idle.
        Rejected

     Transmission     Transmission rejected. Another operator is transmitting—try again later.
Rejected Re-Transmit     Or

                      Radio is in idle—set up a service.

Tx Rejected, Check    Transmission rejected. Another operator is transmitting—try again later.
Mode & Status Msgs       Or

      Retransmit      Radio is in idle —set up a service.

                                                                                                 D-11


---

                     Table D-5. Service Assigned Errors and Warnings

Message                   Action
       Verify I/O Device  a. ERROR. Attach asynchronous data device and accept service.
                          b. WARNING. Attach synchronous data device and accept service.
    I/O Device Present?   Attach data device and accept service.
    Check PT/CT Switch
                          Set mode switch to other setting (PT or CT) and accept service.
          Illegal Mode
  Assuming Ext Encrypt    Reject service.

        I/O Rate Invalid  If using external encryption, accept service. Otherwise, reject service.

                          Check for proper rate selection on the 5-K DAMA I/O rates menu.

        Message              Table D-6. Message Queue Errors
      No Ext Dev?
      Ext Encrypt?   Action
                     Attach data device.
          PT/CT?     If using external encryption, continue. Otherwise, set mode switch to CT
       Sync Dev?     and send encrypted data.
      Inv I/O Rate?  If message is not encrypted, set mode switch to PT.
                     Attach synchronous device or set mode switch to PT.
                     Check for proper data rate selection on 5-kHz DAMA I/O rates menu.

                          Table D-7. Hot Keys, 5-kHz DAMA

Key Function                                               Screen

       Service Set up. Information on type of service      SERVICE SETUP  SYN       P##
1 requested so controller can set up communication         CIR EN                   V2400
                                                           PREC: R             D: #####
       with another party. Requests time on satellite for  CODE: ###
       communication services (dials the phone).                                    {SEND}

                                                           TEARDOWN               1/3
      Teardown. Ends current service; terminal remains DESTIN ADD 02000 CIR
2 logged in to network (hangs up the phone) (hot key 1 in DASA). D PT PREC: R
                                                           LOCAL ACTIVE           {SEND}

                                                           SERVICE STATE          1/3

3 Service State. Indicates status of up to three           DESTIN   ADD 02000 CIR
       services.                                           D       PT PREC: R

                                                           LOCAL ACTIVE

      Network State. Indicates status of current network.          NETWORK STATE

4 LQ should be greater than 36.0.                          PCC: #####     MHOP LIO

                                                           FOW MISS ### LQ: ##.#

D-12


---

                      Table D-7. Hot Keys, 5-kHz DAMA

Key Function                                           Screen

                                                       PREC MIN/MAX: R/FO

                                                       MSG ##:##Z       01 of 10

5 Status Messages. Displays last 10 stored             NETWORK

messages (hot key 2), when using dedicated service. ACQUIRED

                                                                           02

                                                                   LOGOUT

6 Log out. Removes terminal from network.              OVER-THE-AIR

                                                                                  {SEND}

Contention Ranging. Ranges satellite when                CONTENTION RANGING

7 operating in silent mode. Contention ranging should

be performed initially, then once every 4.5 hours.                                {SEND}

                                                       MESSAGE QUEUE

8 Message Queue. Accesses queue to send or             XMIT       P##   1 IN QUE
       receive data messages.                          TEK #    ANDVT   D2400
                                                       Prec: R          D: #####
                                                                    EN

                                                                                  {SEND}

g. Perform the following to set up a 5-kHz DAMA network manually.

(1) In the current mode screen, select DAMA.

(2) Enter preset (even if already displayed).

                              CURRENT MODE

                      DAMA -P1 Sq- -045

                      TEK1 PSK ANDVT V2400

                      5KHz                  Tpwr 35 dbm

Note: For manual service set up, ensure service preset is set to 00.

(3) Press ENT on start DAMA.

                      Channel Number: 136

                      R248.900              T302.500

                      Code: 060 OW:CT

                      Normal Range: Active

                      Login: Over The Air

                      Service Preset: 00

                      Start DAMA for 01000

(4) Observe display.

                      DAMA                  Sq- -045

                      5K        Acquiring N

                      SRV-Idle

                      1−Service Setup

(a) Acquiring—Acquisition in process.

(b) Range—Wait while ranging in process.

                                                                                  D-13


---

                               DAMA             Sq-  -045
                              5K        LOGIN
                              SRV-Idle
                              LOGIN

      (5) Select log in type (over-the-air or preassigned).
                                                             LOGIN

                                             Over The Air
                                                                        {SEND}

         (6) For preassigned, select maximum assigned precedence (FO, F, I, P, R) and enter
demarcation address (49999).

      (7) Press ENT on send.

                                             LOGIN
                              Preassigned
                              Prec: R Dmark:#####

                                                                           {SEND}

Note: “Connected” appears on display and the terminal is ready for service set up.
         To set up a service, proceed to manual service set up by pressing Hot Key #1.
         See Table D-7 for hot keys to access additional tasks.

                              DAMA             Sq- -045

                              5K        Connected N

                              SRV-Idle

                              1-Service Setup

Note: Ensure current service state is idle (SRV-IDLE).

h. Circuit/DASA service set up (hot key #1).

         (1) Enter on preset number 00 for manual service set up, or enter the service preset
number and proceed to step k.

      (2) Select type of service CIR or DSA.

                                  SERVICE SETUP P##

                              DSA EN SYN V2400

                              Prec: R ANDVT D: #####

                              Code:###        ##hr ##min

                                                                        {SEND}
      (3) Select encryption (EN or UN).
      (4) If using data service, select data type (SYN or ASYN).
      (5) Select mode (V or D).
      (6) Select data rate, if applicable.
      (7) Select precedence (FO, F, I, P, R).
      (8) Enter destination address.

D-14


---

(9) Enter configuration code, if required.

(10) If using DASA, specify length of service.

         (11) For indefinite, press ENT on indefinite, then press ENT on send (indefinite for
DASA is 85 hours 15 minutes).

         (12) For timed service, with indefinite highlighted, press right or left arrow key.
With hour highlighted press ENT. Move cursor to ## field and input number of hours, if
applicable, and press ENT. Move cursor to ## field and input number of minutes and press
ENT.

(13) Press ENT on send.

(14) At SRVC ASGND popup message, enter on ACCEPT.    To reject the service, use

the arrow keys to select REJECT and press ENT key.

                   Srvc Asgnd

                   DSA TEK1 KG-84 D2400

                   Prec: R UN               D: 01320

                   SYN S:02000 {ACCEPT}

Note: When a warning or error message is displayed, refer to Table D-5 for proper
         corrective action.
         “SRV-Rx/Tx” appears on display, when terminal is ready for communications.

i. Send a message (hot key #8).

(1) Ensure service is idle; select XMIT. The display indicates how many messages

are in the queue.

                                 MESSAGE QUEUE

                   XMIT            P## 0 IN QUE

                   TEK 1 4KG-84 D2400

                   Prec: R EN               D:#####

                                            {SEND}

         (2) Enter 00 if not using a service preset, or enter the preset number and proceed to
step 8.

(3) Enter the COMSEC key (1 to 5).

         (4) Select encryption type (4KG-84, 3KG-84, VINSN, ANDVT) same as current
mode.

(5) Select precedence (FO, F, I, P, R).

(6) Select encryption (EN or UN).

(7) Enter address of the message recipient.

         (8) Press ENT on SEND and observe display. See Table C-6 if an error message is
displayed.

         (9) After “Enter Message Now” is displayed, key data device. (Message input from
the data device is confirmed by the message prompt “Msg Input Done” briefly displayed on
line 5 of the Msg Queue Display.)

                                                                                    D-15


---

Note:  When sending a message to a terminal address with manual or automatic
       release selected and the receiving operator downloads the message to their
       data device within 60 seconds, two popup acknowledgement messages are
       displayed. No acknowledgement is displayed if the message is sent to a
       network address or if the message was not downloaded to the data device
       within 60 seconds. If using AUTO message release, messages are
       automatically sent to the data device and the following procedure is not
       applicable.

j. Receive a message (hot key #8).

         (1) Ensure service is idle; select RCV. The display indicates how many messages are
in the queue.

      (2) Enter the COMSEC key number (1 to 5).

                              MESSAGE QUEUE

       RCV                                     1 IN QUE

       TEK 1                        4KG-84 D2400

       Prec: R                                 EN D:#####

                                               {RELEASE}

         (3) Select encryption type (3KG-84, 4KG-84, ANDVT) same as current mode. See
Table D-5 if an error message is displayed.

         (4) Select RELEASE to send the message to the data device, or DELETE to erase
the current message.

k. Teardown (hot key #2, hot key #1 for DASA).

      (1) Select service (# / #) to teardown.

      (2) View DESTIN or SOURCE address, and enter.

      (3) Press ENT on SEND.

       TEARDOWN                                        1/1

       DESTIN ADD 02000 CIR

       D PT                                    PREC:R

       LOCAL ACTIVE

                                                       {SEND}

         (4) Press ENT to verify teardown. The display changes to the network menu. A
status message confirms the result of the teardown.

                                                             TEARDOWN
                                                          Verify Teardown

                                                                           {SEND}

l. Log out (hot key #6).

Note: When logging out then back in, use the following as a rule of thumb: Log out
         over-the-air—log back in over-the-air. Log out forced locally—log back in
         preassigned.

D-16


---

         (1) Select over-the-air, if the terminal is off for 30 minutes or longer. Select force
locally, if less than 30 minutes.

                                                                LOGOUT
                                                   Over The Air

                                                                             {SEND}

       (2) Press ENT on SEND.

   Note: A status message confirms the result of the log out. If no log out was sent, or
            if the terminal was off for more than 30 minutes after a force locally log out,
            the JMINI logs the terminal out of the network.

   MESSAGE

   Input Rejected   Transmission rejected. Another operator is transmitting - try again later. Or, radio is in idle – set up a service.

   Output Rejected  Transmission rejected. Another operator is transmitting - try again later. Or, radio is in idle – set up a service.

   Setup Rejected,  Message setup is rejected for the stated reason.
       (Reason)

   Terminated       Message is terminated for the stated reason. Try again later.
Frm:xxxx to:yyyy

    (Reason)

Mode Command        Terminal address is entered as zero. This is reserved for the controller. Enter a valid terminal address.
Rejected, Node
Address is Zero

Msg Setup Rejected  Precedence entered is not allowed. Check network state menu for allowed values and re-enter.
     Precedence
       Violation

 No Resources for   Terminal is busy and cannot receive a message from the other terminal.
Message From:xxxx

R RANGING

   Failed           Check current mode entries and antenna. Run BIT to verify terminal operation.

Overdue Transmit    A successful ranging attempt has not been completed as scheduled. Transmission is denied. Check antenna.
      Inhibited     Transmit a ranging burst using the contention ranging menu.

S SERVICE SETUP

Command Rejected Verify connected and logged in and try again.

Rejected, Invalid   Ensure a valid data rate is selected.
    Data Rate

T

Teardown Command    The terminal has rejected the teardown request. Verify Idle.
        Rejected

   Transmission     Transmission rejected. Another operator is transmitting - try again later. Or, radio is in idle – set up a service.
   Rejected Re-

      Transmit

Tx Rejected, Check  Transmission rejected. Another operator is transmitting - try again later. Or, radio is in idle – set up a service.
Mode & Status Msgs

      Retransmit

                                                                                                                                         D-17


---

   AN/PSC-5 25-kHz AD                         37. C5594 (positions 3-4), IO = C5596                     ERROR CODE = DO THIS
                                                    (positions 1-2) (Must input the                Load Orderwire Keys, LANT =
    HOC DAMA SETUP                                  same key set in positions). Do not
                                                    connect the cable until the ANCD                (PREVENTIVE MEASURE)
             GUIDE                                  says “connect to radio”. Cycle the
                                                    radio to CT and return to F2 if it            77 = Talk to net NCS. NCS needs
1. The following are required before                continually fails to load. Be patient.  to check with the SMC/NCTAMS to
setup:                                                                                      ensure the network is on line.
                                              38. Go to Current Mode (1) and hit
      a. AN/PSC-5                                   enter.                                        82 = Check the TBA entered into
      b. Satellite Antenna                                                                  the radio to ensure it is correct.
      c. Proper Crypto (ANDVT)                39. Change mode back to DAMA; hit             (PMCS).
      d. Proper Orderwire set                       enter.
      e. Good batteries                                                                           90 = This is a busy signal. Call
2. Turn radio on to PT, Let the BIT           40. Press Preset #1, hit the 1 key on         back later.
      finish, then ESC.                             the keypad; hit enter.
3. Go to Set Presets (3), enter.                                                                  92 = Indicates a conference call
4. Choose Set Mode Presets (1).               41. Enter correct TEK#; hit enter.            was made or more than one terminal
5. > to DAMA; hit enter.                      42. Hit enter to confirm the remainder        was called. At least one terminal is
6. Choose Preset number 1; hit enter.                                                       not on the air but others are.
7. Choose COMSEC fill slot—                         of the settings until SEND STATUS
   • Use TEK1 as the default fill slot for          B YES/NO.                               Troubleshooting DAMA problems—
      ANDVT.                                  43. Verify connection to an antenna at
8. Choose type of Crypto: ANDVT; hit                this time, with antenna on azimuth      Problem: Fail to get past 25-kHz –
      enter.                                        to satellite.                           Acquiring – Idle when attempting first
9. Choose Data transfer rate—                 44. At SEND STATUS B, select YES,             connection after initial setup. No up and
   • 2400; hit enter.                               hit enter.                              down arrows displayed on the right side
10. Choose 25-kHz, enter.                     45. Select the desired service preset         of the screen.
11. TPWR select 43 dbm; enter.                      (P01, P02, etc), hit enter twice.
12. Channel number; enter.                    46. Radio screen will blink, an arrow in      Solution: Ensure the current Orderwire
13. Code 60; enter.                                 the right side of the screen will go    key segment is loaded in fill slots 1 – 4 in
14. OW: CT; enter.                                  up and then down once or twice,         F2. Lack of the current orderwire
15. Normal; enter.                                  then see acquiring, then range,         COMSEC loaded and/or not in 1 – 4 will
16. Range: Active, enter.                           then 25kHz AC connected-SRV-            cause a connection stop at the 25-kHz
17. Send Status B, YES.                             idle.                                   AC – Acquiring – Idle window during
18. Hit ESC.                                  47. NOTE: AD HOC DAMA ALLOWS                  initial connection.
19. Select Current Mode; enter.                     TBA-TO-TBA, TBA-TO-
20. Change mode to LOS; enter.                      NETWORK, OR TBA TO                      Problem: Cannot get the Orderwire
21. Hit ESC.                                        MULTIPLE TBA CONNECTIONS.               COMSEC to load.
22. Go to Database Options (2), enter.        48. Hit next to Service Setup (1),
23. Go to Guard List (2), enter.                    select R (Routine), then enter the      Solution: Do not connect the ANCD
24. > ADD, enter ##### (the Guard                   TBA or NETWORK ADDRESS,                 cable to the radio until the ANCD
      list/NETWORK ID number from the               then enter desired connection           displays Connect ANCD to Radio. Press
      SOI/SAA), enter. (DO NOT PUT                  time, hit enter and then Send,          the down arrow after connecting the
      THE TBA HERE!)                                enter.                                  cable, follow on screen instructions.
25. Hit ESC once.                             49. Radio screen will show arrows on
26. Go to Terminal Data (3), enter.                 the right going up and down and         Problem: COMSEC Alarm continues to
27. Enter ADDRESS ##### (the TBA,                   then the screen will display 25-kHz     popup.
      from the SOI) hit enter. (DO NOT              AC SRV-RX/TX (the station called
      PUT THE NETWORK ADDRESS                       will change at the same time).          Solution: Refill ANDVT key in F1.
      HERE!)                                  50. Ready to talk as normal (be
28. Backlight Timer, (user pref), enter.            patient).                               Problem: CTIC alarm.
29. Msg Release: Manual. Enter.               51. To terminate setup, select
30. ENTER N                                         Teardown (2) THE CONNECTION             Solution: Refill the orderwire key in the
                                                    MUST BE TORN DOWN AFTER                 correct positions.
                    E                               COMPLETING TRAFFIC TO
                    TIME = ZULU TIME                AVOID LOCKING UP THE OTHER              Problem: Data communications not
                    (not required)                  STATION AND BLOCKING                    getting through but voice
31. Platform: Stationary, hit enter.                OTHER TRAFFIC TO THAT                   communications are.
32. Press ESC twice.                                STATION. Terminal will be in 25-
33. Change radio on/off switch to F1.               kHz AC Connected SVC-idle               Solution: Run Link Test. It is item 7 in
34. Input ANDVT in fill slot 1.                     mode.                                   DAMA menu, needs to be run at 32
35. Follow the on screen instructions                                                       kbps, and the Symbol Errors need to be
      for filling the key. Watch for the Key        NOTE: To send data: (for                less than 100 when transmitting data.
      Filled message on the screen. Be        example, KL-43 or V-Mail) change the          Takes about a minute to run and lets the
      patient.                                V2400 to D2400.                               operator know a better signal is needed.
36. Change radio on/off switch to F2.                                                       Info Code 93 appears, send back
                                              NOTE: If the radio is not working             information report and wait since
                                              properly cycle the radio off/on, then         someone else is running the test.
                                              filter tune the radio and run a second
                                              BIT.

D-18


---

  25-kHz AD HOC DAMA                      40. Change radio on/off switch to F2.          ERROR CODES = DO THIS
SETUP GUIDE – AN/PSC-                     41. Load Orderwire Keys, LANT =
                                                                                         (PREVENTIVE MEASURE)
        5C/D RADIOS                             C5594 (positions 3-4), IO = C5596
                                                (positions 1-2) (Input the same key            77 = Talk to net NCS. NCS needs
1. The following are required before            set in positions). Do not connect the    to check with Naples to insure the
                                                cable until the ANCD says “connect       TBA is on line.
setup:                                          to radio”. Cycle the radio to CT and
                                                return to F2 if it continually fails to        82 = Check the TBA entered into
a.            AN/PSC-5C/D                       load. Be patient.                        the radio to ensure it is correct.
                                          42. Return on/off switch back to CT.           (pmcs)
b.            Satellite Antenna           43. Go to Current Mode (1) and hit
                                                enter.                                         90 = This is a busy signal. Call
c.            Proper Crypto (ANDVT)       44. Change mode back to DAMA; hit              back later.
                                                enter.
d.            Proper Orderwire set        45. Press Preset #1, hit the 1 key on                92 = Indicates conference call to
                                                the keypad; hit enter.                   more than one terminal was made. At
e.            Good batteries              46. Enter correct TK##; hit enter.             least one terminal is not on the air but
                                          47. Hit enter to confirm the remainder         others are.
2. Turn radio on to PT, let the BIT             of the settings until SEND STATUS
                                                B YES/NO appears.                          Troubleshooting DAMA problems
finish, then ESC.                         48. Ensure antenna is connected at this
                                                time, with antenna on azimuth to               Problem: Fail to get past 25-kHz
3. Go to Set Presets (3), enter.                satellite                                AC – Acquiring M – Idle when attempting
                                          49. At SEND STATUS B, select YES,              first connection after initial setup. No up
4. Choose Set Mode Presets (1).                 hit enter.                               and down arrows displayed on the right
                                          50. Select the service preset desired          side of the screen.
5. > to DAMA; hit enter.                        (P01, P02, etc), hit enter twice.
                                          51. Radio screen will blink, an arrow in             Solution: Ensure the current
6. Choose Preset number 1; hit enter.           the right side of the screen will go     Orderwire key segment is loaded in fill
                                                up and then down once or twice,          slots 1–4 in F2. Lack of the current
• Choose COMSEC fill slot: Use TEK              then see acquiring, then range,          orderwire COMSEC loaded and/or not in
                                                then 25-kHz AC connected-SRV-            1 – 4 will cause a connection stop at the
01 as the default fill slot for ANDVT.          idle                                     25-kHz AC – Acquiring – Idle window
                                          52. NOTE: AD HOC DAMA WILL                     during initial connection.
7. Choose type of Crypto: ANDVT;                ALLOW TBA-TO-TBA, TBA TO
                                                MULTIPLE TBA, AND TBA TO                       Problem: Cannot get the Orderwire
enter.                                          NETWORK CONNECTIONS.                     COMSEC to load.
                                          53. Hit next to Service Setup (1),
8. Choose Data transfer rate—                   select R (Routine), then enter the             Solution: Do not connect the
                                                TBA, MULTIPLE TBA’S, OR TO A             ANCD cable to the radio until the ANCD
• 2400; enter.                                  NETWORK ADDRESS enter time               displays Connect ANCD to Radio. Press
                                                required, hit enter and then Send,       the down arrow after connecting the
9. Choose 25-kHz, enter.                        enter.                                   cable, follow on screen instructions.
                                          54. Radio screen will show arrows on
10. Channel number; enter.                      the right going up and down and                Problem: COMSEC Alarm
                                                then the screen will display 25-kHz      continues to popup.
11. > Normal; enter                             AC SRV-RX/TX (the station or
                                                network called will change at the              Solution: Refill keys in F1.
12. TPWR select 43dbm; enter.                   same time).
                                          55. Ready to talk as normal (be                      Problem: CTIC alarm.
13. Code 60; enter.                             patient).
                                          56. To terminate setup, select                       Solution: Refill the orderwire key in
14. OW: CT; enter.                              Teardown (2) THE CONNECTION              the correct positions – F2.
                                                MUST BE TORN DOWN AFTER
15. Range: Active, enter.                       COMPLETING TRAFFIC TO                          Problem: Data communications not
                                                AVOID INTERFERING WITH                   getting through but voice
16. Send Status B, YES                          OTHER STATIONS’ TRAFFIC.                 communications are.
                                          57. Terminal will be in idle mode.
17. Hit ESC X 2.                                                                               Solution: Run Link Test. It is item 7
                                                NOTE: To send data: (for                 in DAMA menu, needs to be run at 32
18. Select Current Mode; enter.           example, KL-43 or V-Mail) change the           kbps, and the Symbol Errors need to be
                                          V2400 to D2400.                                less than 100 when transmitting data.
19. Change mode to LOS; enter.                                                           Takes about a minute to run and lets the
                                                NOTE: If the radio is not working        operator know a better signal is needed.
20. Hit ESC.                              properly cycle the radio off/on several        Info Code 93 appears, send back
                                          times. Filter Tune does not correct all        information report and wait since
21. Go to Database Options (2), enter.    as it did with older versions of radios!       someone else is running the test.

22. Go to Guard List (2), enter.

23. > ADD, enter ##### (the network

ID number from the SOI) enter.

(DO NOT PUT THE TBA HERE!)

24. Hit ESC twice.

25. Go to Configuration (4), enter.

26. Go to Terminal Data (1), enter.

27. Enter ADDRESS ##### (the TBA,

from the SOI) hit enter. (DO NOT

PUT A NETWORK ADDRESS

HERE!)

28. DS-101 ADD, ignore.

29. Backlight Timer, (user pref), enter.

30. Msg Release: Manual. Enter.

31. ENTER LAT N

              LON E

              TIME = ZULU TIME

              (not required)

32. Platform: Stationary, hit enter.

33. Freq Bands: Unlimited.

34. Ext PA Opt: Normal.

35. Remote Opt: PRCD.

36. Press ESC twice.

37. Change radio on/off switch to F1.

38. Input ANDVT in fill slot 1.

39. Follow the on screen instructions

for filling the key. Watch for the Key

Filled message on the screen. Be

patient.

25-kHz TDMA DAMA                          38. Do not connect the cable until the         ERROR CODES = DO THIS
                                                ANCD says “connect to radio”.

                                                                                                                D-19


---

SETUP GUIDE AN/PSC-5                                Cycle the radio to CT and return to     (PREVENTIVE MEASURE)
                                                    F2 if it continually fails to load. Be
1. The following are required before setu           patient. Return on/off switch back to         77 = Talk to the NCS. NCS needs
      a. AN/PSC-5                                   CT.                                     to check with Naples to ensure the
      b. Satellite Antenna                    39. Go to Current Mode (1) and hit            network is on line.
      c. Proper Crypto (ANDVT)                      enter.
      d. Proper Orderwire set                 40. Change mode back to DAMA; hit                   82 = Check the TBA entered into
      e. Good batteries                             enter.                                  the radio to ensure it is correct.
                                              41. Press Preset #1, hit the 1 key on         (PMCS)
2. Turn radio on to PT; let the BIT                 the keypad; hit enter.
      finish, then ESC.                       42. Enter correct TEK# for the mode (V              90 = This is a busy signal. should
                                                    or D); hit enter.                       not be seen with TDMA.
3. Go to Set Presets (3), enter.              43. Hit enter to confirm the remainder
4. Choose Set Mode Presets (1).                     of the settings until SEND STATUS             92 = Indicates more than one
5. > to DAMA; hit enter.                            B YES/NO appears.                       party was called. At least one party is
6. Choose Preset number 1; hit enter.         44. Verify connection to an antenna at        not on the air but others are.
7. Choose COMSEC fill slot: Use TEK                 this time, with antenna on azimuth
                                                    to satellite                               Troubleshooting DAMA problems
      01 as the default fill slot for ANDVT.  45. When SEND STATUS B appears,
8. Choose type of Crypto: ANDVT; hit                select YES, hit enter.                        Problem: Fail to get past 25-kHz
                                              46. Select the desired service preset         AC – Acquiring – SVC - Idle when
      enter.                                        (P01, P02, etc), hit enter twice.       attempting first connection after initial
9. Choose Data transfer rate—                 47. Radio screen will blink, an arrow in      setup. No up and down arrows displayed
                                                    the right side of the screen will go    on the right side of the screen.
   • 2400; hit enter.                               up and then down once or twice,
10. Choose 25-kHz, enter.                           then see acquiring, then range,               Solution: Ensure the current
11. TPWR select 43dbm; enter.                       then 25-kHz AC connected-SRV-           Orderwire key segment are loaded in fill
12. Channel number; enter.                          idle.                                   slots 1 – 4 in F2. Lack of the current
13. Code 60; enter.                           48. NOTE: TDMA DAMA WILL NOT                  orderwire COMSEC loaded and/or not in
14. OW: CT; enter.                                  ALLOW TBA-TO-TBA                        1 – 4 will cause a connection stop at the
15. Normal; enter.                                  CONNECTIONS. SERVICE MUST               25-kHz AC – Acquiring –SVC - Idle
16. Range: Active, enter.                           BE SET UP SERVICE TO THE                window during initial connection.
17. Send Status B, YES.                             NETWORK ADDRESS.
18. Hit ESC.                                        MULTIPLE STATIONS CAN BE                      Problem: COMSEC Alarm
19. Select Current Mode; enter.                     CONNECTED AT ONE TIME BUT               continues to popup.
20. Change mode to LOS; enter.                      THEY SHARE THE “CHANNEL”.
21. Hit ESC.                                  49. Hit next to Service Setup (1),                  Solution: Refill ANDVT key in F1.
22. Go to Database Options (2), enter.              select R (Routine), then enter the
23. Go to Guard List (2), enter.                    NETWORK ADDRESS (6???? Or                     Problem: CTIC alarm.
24. > ADD, enter ##### (the Guard                   5????) enter 00 ind (required for
                                                    TDMA) hit enter and then Send,                Solution: Refill the orderwire key in
      list/NETWORK ID number from the               enter. DO NOT SET UP A                  the correct positions (F2).
      SOI) enter. (DO NOT PUT THE                   SERVICE TO A TBA! THIS WILL
      TBA HERE!)                                    LOCK UP THE NETWORK.                          Problem: Data communications not
25. Hit ESC once.                             50. Radio screen will show arrows on          getting through but voice
26. Go to Terminal Data (3), enter                  the right going up and down and         communications are.
27. Enter ADDRESS ##### (TBA, from                  then the screen will display 25-kHz
      the SOI) hit enter. ( DO NOT PUT              AC SRV-RX/TX (the called station              Solution: Run Link Test. It is item 7
      THE NETWORK ADDRESS                           will change at the same time).          in DAMA menu, needs to be run at 32
      HERE!)                                  51. Ready to talk as normal (be               kbps, and the Symbol Errors need to be
28. Backlight Timer, (user pref), enter.            patient).                               less than 100 when transmitting data.
29. Msg Release: Manual. Enter.               52. To terminate setup, select                Takes about a minute to run and lets
30. ENTER LAT N                                     Teardown (2) Terminal will be in        operator know a better signal is needed.
                                                    idle mode.                              Info Code 93 appears, send back
                    LON E                     53. TEARDOWN IS NOT REQUIRED                  information report and wait since
                    TIME = ZULU TIME                IN TDMA. Terminal can remain            someone else is running the test.
                    (not required)                  connected and monitor traffic
31. Platform: Stationary, hit enter.                without interfering with other
32. Press ESC twice.                                stations if desired.
33. Change radio on/off switch to F1.              NOTE: To send data: (for
34. Input ANDVT in fill slot 1.               example, KL-43 or V-Mail) change the
35. Follow the on screen instructions         V2400 to D2400. If the radio is not
      for filling the key. Watch for the Key  working properly cycle the radio
      Filled message on the screen. Be        off/on, then filter tune the radio and
      patient.                                run a second BIT.
36. Change radio on/off switch to F2.
37. Load Orderwire Keys, LANT =
      C5594 (positions 3-4), IO = C5596
      (positions 1-2) (Input the same key
      set in positions).

   25-kHz TDMA DAMA                           39. Input ANDVT in fill slot 1.               NOTE 1: To send data: (for example,
SETUP GUIDE - AN/PSC-                         40. Follow the on screen instructions for     KL-43 or V-Mail) change the V2400 to
                                                                                            D2400.
                                                    filling the key. Watch for the Key
                                                    Filled message on the screen. Be

D-20


---

         5C/D RADIOS                                patient.                                       NOTE: If the radio is not working
                                              41. Change radio on/off switch to F2.          properly cycle the radio off/on several
1. The following are required before          42. Load Orderwire Keys, LANT =                times. Filter Tune does not correct all
      starting setup:                                                                        as it did with older versions of radios!
      a. AN/PSC-5C/D                                C5594 (positions 3-4), IO = C5596
      b. Satellite Antenna                          (positions 1-2) (Input the same key            ERROR CODES = DO THIS
      c. Proper Crypto (ANDVT)                      set in positions). Do not connect the          (PREVENTIVE MEASURE)
      d. Proper Orderwire set                       cable until the ANCD says “connect
      e. Good batteries                             to radio”. Cycle the radio to CT and     77 = Talk to the NCS. NCS needs to
                                                    return to F2 if it continually fails to  check with NAPLES to ensure the TBA
2. Turn radio on to PT, let the BIT                 load. Be patient.                        is on line.
      finish, then ESC.                       43. Return on/off switch back to CT.
                                              44. Go to Current Mode (1) and hit             82 = Check the TBA entered into the
3. Go to Set Presets (3), enter.                    enter.                                   radio to ensure it is correct. (PMCS)
4. Choose Set Mode Presets (1).               45. Change mode back to DAMA; hit
5. > to DAMA; hit enter.                            enter.                                   90 = This is a busy signal -- should not
6. Choose Preset number 1; hit enter.         46. Press Preset #1, hit the 1 key on the      be seen with TDMA.
7. Choose COMSEC fill slot—                         keypad; hit enter.
                                              47. Enter correct TK##; hit enter.             92 = Indicates more than one party
   • Use TEK 01 as the default fill slot for  48. Hit enter to confirm the remainder of      was called. At least one party is not on
      ANDVT.                                        the settings until SEND STATUS B         the air but others are. Check service
                                                    YES/NO appears.                          state (3) for who is connected.
8. Choose type of Crypto: ANDVT; hit          49. Verify connection to an antenna at
      enter.                                        this time, with antenna on azimuth to        Troubleshooting DAMA problems
                                                    satellite.
9. Choose Data transfer rate—                 50. When SEND STATUS B appears,                Problem: Fail to get past 25-kHz AC –
   • 2400; hit enter.                               select YES, hit enter.                   Acquiring M – Idle when attempting first
                                              51. Select the service desired preset          connection after initial setup. No up and
10. 2400 for voice; hit enter. Choose               (P01, P02, etc), hit enter twice.        down arrows displayed on the right side
      25-kHz, enter.                          52. Radio screen will blink, an arrow in       of the screen.
                                                    the right side of the screen will go up  Solution: Ensure the current Orderwire
11. Channel number; enter.                          and then down once or twice, then        key segment is loaded in fill slots 1–4 in
12. > Normal; enter.                                see acquiring, then range, then          F2. Lack of the current orderwire
13. TPWR select 43 dbm; enter.                      25-kHz AC connected-SRV-idle             COMSEC loaded and/or not in 1 – 4 will
14. Code 60; enter.                           53. NOTE: TDMA DAMA WILL NOT                   cause a connection stop at the 25-kHz
15. OW: CT; enter.                                  ALLOW TBA-TO-TBA                         AC – Acquiring – Idle window during
16. Range: Active, enter.                           CONNECTIONS. SET UP SERVICE              initial connection.
17. Send Status B, YES.                             TO THE NETWORK ADDRESS.
18. Hit ESC X 2.                                    MULTIPLE STATIONS CAN BE                 Problem: Cannot get the Orderwire
19. Select Current Mode; enter.                     CONNECTED AT ONE TIME BUT                COMSEC to load.
20. Change mode to LOS; enter.                      THEY SHARE THE “CHANNEL”.
21. Hit ESC.                                  54. Hit next to Service Setup (1), select      Solution: Do not connect the ANCD
22. Go to Database Options (2), enter.              R (Routine), then enter the              cable to the radio until the ANCD displays
23. Go to Guard List (2), enter.                    NETWORK ADDRESS (6???? Or                Connect ANCD to Radio. Press the down
24. > ADD, enter ##### (the network ID              5????) enter 00 ind (required for        arrow after connecting the cable, follow
                                                    TDMA) hit enter and then Send,           on screen instructions.
      number from the SOI) enter. (DO               enter. DO NOT SET UP SERVICE
      NOT PUT THE TBA HERE!)                        TO A TBA, IT WILL LOCK UP THE            Problem: COMSEC Alarm continues to
25. Hit ESC twice.                                  NETWORK.                                 popup.
26. Go to Configuration (4), enter.           55. Radio screen will show arrows on           Solution: Refill ANDVT key in F1.
27. Go to Terminal Data (1), enter.                 the right going up and down and
28. Enter ADDRESS ##### (the TBA,                   then the screen will display 25-kHz      Problem: CTIC alarm
      from the SOI) hit enter. (DO NOT              AC SRV-RX/TX (the station or             Solution: Refill the orderwire key in the
      PUT A NETWORK ADDRESS                         network called will change at the        correct positions (F2).
      HERE!)                                        same time).
29. DS-101 ADD, ignore.                       56. Ready to talk as normal (be patient).      Problem: Data communications not
30. Backlight Timer, (user pref), enter.      57. To terminate setup, select Teardown        getting through but voice communications
31. Msg Release: Manual. Enter.                     (2) Terminal will be in idle mode.       are.
32. ENTER LAT N                               58. TEARDOWN IS NOT REQUIRED IN
                                                    TDMA. It is possible to remain           Solution: Run Link Test. It is item 7 in
                    LON E                           connected and monitor traffic            DAMA menu, needs to be run at 32 kbps,
                    TIME = ZULU TIME                without interfering with other           and the Symbol Errors need to be less
                    (not required)                  stations if desired.                     than 100 when transmitting data. Takes
33. Platform: Stationary, hit enter.                                                         about a minute to run and lets them know
34. Freq Bands: Unlimited.                                                                   they need a better signal. Info Code 93
35. Ext PA Opt: Normal.                                                                      appears, send back information report
36. Remote Opt: PRCD.                                                                        and wait since someone else is running
37. Press ESC twice.                                                                         the test.
38. Change radio on/off switch to F1.

                                                                                             D-21


---

                  Table D-8. 5-kHz DAMA Operations (Same Footprint/MHOP) Guide

     Procedure                                                     Steps/Notes
Load presets for
5-kHz DAMA           1. Turn on the radio; go to PT.
                     2. Escape to main menu.
Enter 5-kHz DAMA     3. Scroll to set presets; press enter or 3.
channel              4. Select mode DAMA (press ⇒ to get to DAMA).
                     1. Enter preset number 2.
                     2. Enter encryption device: ANDVT.
                     3. Enter D.
                     4. Enter data rate 2400.
                     5. Enter 5-kHz (for type of DAMA).
                     6. Enter channel number.
                     7. Enter configuration code N/A.
                     8. Enter OW: CT.
                     9. Enter mode of operations: normal.
                     10. Enter range: active

Load database        From current menu, scroll to database options and enter (or press 2).

Enter guard list     1. From database menu, press enter (or 1).
addresses            2. Use arrow keys to scroll through options—VIEW, ADD, DELETE, MODIFY.
                     3. Enter on ADD.
                     4. Enter guard list addresses
                     Notes. Guard list includes addresses for which operator wishes to receive

                               services; it does not impact who is called.
                               Each address must be 5 digits long.
                               Up to 15 different addresses may be entered.
                               Always enter network address in the guard list. Terminal addresses may
                               be entered if the operator wishes to listen to calls made to that address.

Enter terminal data            In 5-kHz DAMA, if a terminal address is entered in the guard list, the
LAT, LON, TIME                 controller also logs in that TBA. When the terminal attempts to log in, it is
                               denied. Be careful.
Enter terminal       1. Enter LAT—N or S and four-digit number N.
address              2. Enter LON—E or W and four-digit number E.
                     3. Enter time—Must be Zulu time (if no time was entered, the time reflected is how
Enter platform       long the terminal is turned on).
Enter type of MSG    Note. This needs to be entered only if terminal is set up for silent, passive mode
release                        in 5-kHz DAMA. This is NOT the preferred method.
5-kHz message        TBA from the SOI.
queue only.          Note: Every terminal must have its own terminal address; no two terminals can
Enter 5-KHZ I/O                come up on a DAMA channel with the same address.
data rates           Enter stationary.
5-kHz DAMA only
                     Enter MANUAL if the radio is to hold the message, AUTO if the message is to go
                     straight into the data device (rule of thumb, KL-43, DMDG, PSC-2A, use MANUAL;
                     VDC-400/computer, use AUTO).
                     Note: If voice is used, this field always reverts to manual.

                     Check only the ones used. If voice is used, 2400 bps must be checked.

D-22


---

Table D-8. 5-kHz DAMA Operations (Same Footprint/MHOP) Guide

     Procedure    Steps/Notes

Enter satellite   Not required
ephemeris data
                  Note: This information is obtained from the unit frequency manager (who gets it
Check COMSEC                from the SMC). It is required only if terminal is set up for silent, passive
keys                        mode.
                            There are eight positions to input satellite ephemeris data.
Load orderwire              This information changes. Information used for one exercise may differ for
keys                        the next exercise.
Check orderwire
keys              1. Change mode selector switch to CT.                      Update column should
                  2. Scroll to database options and enter (press 2).
                  3. Scroll to COMSEC key states and enter (press 7).
                  4. Scroll through key positions to ensure key was filled.
                  state 0, unless some of the keys were updated.

                  1. Change mode selector switch to F2 position. Before loading orderwire keys, it
                  is best to have the COMSEC keys already loaded. Key positions 1 through 8 are
                  available. Orderwire keys need to be put in positions 1 to 4 only.

                  2. Positions 5 to 8 are reserved for over-the-air rekeying in the future.

                  The only way to check to see if keys were loaded is to go to F2 and see if the
                  numbers are on the line.

Change to DAMA    1. Go to current mode screen.
preset and enter  2. Change mode to DAMA.
DAMA network      3. Press preset number for channel and enter (press 2).
                  4. Ensure all information is correct from preset by pressing enter through all fields.
                  (The TEK is not part of the presets so special attention should be given to this field
                  to ensure it is correct.)
                  5. Press enter on start DAMA (radio does not change to DAMA mode until enter
                  on network is done).
                  Notes Watch screen for 5-kHz ACQUIRING; 5-kHz RANGE; 5-kHz LOGIN PND.

                            If the radio does not go to 5-kHz LOGIN PND or an M is on the net
                            acquiring line, check the following:

                                Adjust antenna.
                                Adjust output power.
                                Refill keys.
                                Ensure the proper key is loaded and in correct position.
                  Radio automatically log in—check for status messages.
                  Respond and view as necessary to all status messages received.

                                                                                                  D-23


---

      Table D-8. 5-kHz DAMA Operations (Same Footprint/MHOP) Guide

     Procedure                                                   Steps/Notes

Log in manual—     1. Ensure the radio is at the 5-kHz —LOG IN screen.
over-the-air       2. Press enter.
                   3. Screen states LOGIN; Over-the-air; SEND—press enter to send.
Log in, manual,    Notes: Do not perform this step until the first line states 5-kHz —LOGIN and last
preassigned
                             line states LOGIN.
Set up circuit               When accepted by the controller, screen changes to 5-kHz —
service—                     CONNECTED.
data/terminal for            Many other OWs may be sent and received by the terminal; one to
MHOP                         especially watch for is the guard list being changed.
Communicate                   Only one over-the-air log in is transmitted without sending an over-the-air
                             log out. If more than one is attempted, the terminal receives an error
                             message from the controller.

                                 Log in rejected.
                                 Not authorized.
                                 Log in rejected, invalid log in address.
                             These messages let the operator know that log in was attempted too many
                             times.
                             It is also possible to receive the above messages because the controller
                             did not activate the terminal address in the database. In this case, the unit
                             frequency manager intervenes.
                             Now, the terminal is ready to communicate with other radios. The terminal
                             is able to respond to service requests from other radios or send service
                             requests to other radios.

                   1. Ensure the radio is at 5-kHz LOGIN.
                   2. Press enter.
                   3. Screen states LOGIN; over-the-air—change to preassigned
                   4. New screen appears; ensure the maximum precedence is correct and the
                   demarcation point (DMARK) is at 49999 (unless told otherwise by the frequency
                   manager).
                   5. Press enter on send.
                   Notes: OWs are not received from the controller; this is only a means for telling

                             the terminal that it needs to be logged in.
                             If the terminal was not previously logged in (except when a SILENT
                             terminal), an attempt to set up a service is denied and the reason given is
                             the terminal is not logged in. In this case, send the over-the-air log in.
                             This is used when an over-the-air log in was already sent and the terminal
                             needs to come back up in the DAMA network—OR—when a service
                             connection has been torn down and re-access is required but the terminal
                             has not logged off the net.
                             The controller has the maximum precedence already stored in its
                             database. If that precedence is exceeded when attempting to set up a
                             service, the controller may log the terminal out of the system. The
                             operator needs to go back and send an over-the-air log in.

                   1. Ensure current mode screen reflects D.
                   2. Ensure screen states 5-kHz CONNECTED—SVC IDLE.
                   3. Scroll to service set up and enter (or press) 1.
                   4. Information displayed is the same information as in current mode (what was put
                   in the preset). Change anything that does not reflect data, 2400 bps, ANDVT.
                   5. In Destination, enter TBA (NOT network address) that is in the other footprint.
                   Enter on Send

                   When SRVCASGND message is received, press enter to ACCEPT. Pass traffic

D-24


---

Table D-8. 5-kHz DAMA Operations (Same Footprint/MHOP) Guide

     Procedure                                   Steps/Notes
Check service state
                     with VDC-400 CARD. Traffic takes longer over multiple footprints in the MHOP
Check network        service.
state
                     1. Check to ensure 5-kHz connected; may check service state whether in a
Log out              service, pending a service, or preempted from a service (also when idle).

                     2. Scroll to check service state and enter (or press 3).

                     Note: Information only screen displays how many services there are (up to 3)—
                               change the first number by pressing 2/3 to see other services and their
                               status.

                            Who set up the service/who was the destination address.

                            CIR or MSG service.

                            V or D; PT/CT; and precedence sent.

                            LOCAL (in the same footprint) or MHOP.

                            ACTIVE, PENDING, or QUEUED.

                     1. Ensure 5-kHz connected.

                     2. Scroll to check network state and enter (or press 4).

                     3. Displays information about the DAMA network:

                     PCC address—address assigned to the DAMA control station (not to be
                     confused with 00000).

                     4. MHOP indicates the controller is capable of sending messages across
                     footprints.

                     Note:  LIO (limited input/output)—if displayed, controller does not accept services
                            of 2400 bps or higher. If using data, use a lower data rate if possible when
                            setting up a service. If using voice (which is highly discouraged on 5-kHz
                            DAMA), terminal is denied if a service set up is sent for voice
                            communications.

                            FOW Miss—number of OWs missed from the controller. This is a running
                            total (which means misses could be intermittent). However, if the terminal
                            misses 200 consecutive OWs, the terminal is supposed to be logged out of
                            the network by the controller and goes to acquiring on its own.

                            Link Quality—values are from 26.0 to 57.5. The terminal requires a
                            minimum of 36 to access DAMA communications, 45 or better for data
                            communications.

                            Precedence/Precedence—indicates minimum precedence for network
                            access (if the net is a routine net and this displays priority, the entire
                            network is unable to gain access to the DAMA channel). Second
                            precedence indicates the maximum precedence for the terminal; the
                            frequency manager should provide this information. This is a way to check
                            what is in the controller's database.

                     1. Ensure the terminal is at 5-kHz CONNECTED and SVC IDLE; if there are any
                     services active, teardown.

                     2. Scroll to log out and enter (or press 6).

                     3. Select over-the-air log out and send.

                     4. Radio is now ready to be shut down. Terminal should receive a log out
                     acknowledgement message.

                     5. Turn off the radio or go to another preset channel for other modes of operation.

                                                                                                D-25


---



---

                                                Appendix E

                                    LST-5D Radios

1. LST-5D LOS Procedures (Updated: 02 APR 98)

    a. Reminder.
         (1) HD SET—Use a 6-pin audio connector plain text handset connector only.
         (2) LOS—Refers to line of sight. The radio is configured in the AM mode. This

may be used for ground-to-air and air-to-ground communications. If FM is required in a
LOS environment, the radio is configured in the SATCOM mode.

         (3) Audio/Data/Fill Connector—Connects to handset in secure voice modes, data
devices in secure data modes, or fill devices in fill modes.

    b. Prior to COLD START, press 0 and right arrow together. Then turn on the
radio. This will MASTER CLEAR all settings and crypto in the radio, if needed.

    c. Cold start initialization.
    Note: The down arrow button works as the “enter” button.

         (1) When unit is powered up in an un-initialized state, the unit performs system
tests and then displays a blinking ALARM message. (If the alarm blinks without going
to self-test, press ESC twice and then self-test begins.) The speaker shaped icon in the
lower left corner of the display is an ALARM annunciator. As long as the internal
COMSEC KG is not initialized, the radio set remains in the ALARM condition and
displays the ALARM message.

         (2) Rotate the key management (KGMT)switch to the LD KG position, then
depress and release the ESC on the front panel keypad twice. The SELF TESTING
message is displayed after the internal COMSEC KG successfully performs its power up
tests.

         (3) Once the radio completes and passes all power up tests (approximately 60 to
70 seconds) the radio displays a prompt to connect a fill device.

         (4) The radio is not used in a secure mode, move the KGMT switch to operate
(OP) position.

         (5) The three-digit alarm code in the lower right corner of the display should
read 050.

         (6) The three digit error code 255 is a catchall error code. Reinitiate the radio.

                                                                                                                                   E-1


---

    d. Programming operating modes.
    Note: The left and right arrow buttons move to the menu option needed.

         (1) Turn the mode select to OP position.
         (2) At the function screen, usethe right arrow button to select PROG and then
depress the down arrow button.
         (3) The program menu displays MODES and FREQS.
         (4) Select FREQS depress the right arrow button followed by the down arrow
button to enter.
         (5) The Program Freqs Menu displays CH1 with the RX—TX
(DOWNLINK/UPLINK) UHF frequencies. Insert the appropriate frequencies in the
channels (there are nine channels to use).
         (6) Depress the up arrow until STORE FREQ menu is displayed. Select YES and
depress the down arrow button to enter and save.
         (7) At the program screen, select MODES using the left arrow button followed by
the down arrow button to enter.
         (8) Select the preset to store the configuration into (enter a number) and depress
the down arrow button.
         (9) Scroll through the terminal selections and select LOS, depress the down
arrow button.
         (10) Display/SOURCE KG, select PT, depress the down arrow button.
         (11) Display/RADIO SCAN, select OFF, depress the down arrow button.
         (12) Display/CHANNEL SELECT, select the preset channel, depress the down
arrow button.
         (13) Display/POWER ADJ, select LOW or HIGH, depress the down arrow
button.
         (14) Select SAVE, depress the down arrow button to store.
         (15) Display/STORE INTO PRESET (what ever the circuit preset is 1 to 6)
         (16) Press ESC until the OP screen is displayed and select OP.
         (17) Recall the PRESET.

E-2


---

(18) After recalling the preset, the display shows a monetary alarm condition.

Radio initializes for a minute or so. Then the radio automatically accesses the

frequencies and the display reads as—

PRESET # 1

LOS PLAIN TEXT

I I I I I I I I I I I (power bars)

SIG

CH#1 FREQ                              RX

    e. Upon completion of the circuit, depress the ESC button or the up arrow button to
the FUNCTION menu.

f. Remember, communications are only as good as antennas.

2. LST-5D SATCOM Procedures

    a. SATCOM. SATCOM refers to satellite communications. When using plain text
voice communication, this is FM modulation. Using secure communication is frequency-
shift keying (FSK) or phase-shift keying (PSK) depending on the data rate.

    b. Cold start initialization.

         (1) When unit is powered up in an un-initialized state, the unit performs system
tests and then displays a blinking ALARM message. (If the alarm blinks without going
to self test, press ESC twice and then self test begins.) The speaker shaped icon in the
lower left corner of the display is an ALARM annunciator. As long as the internal
COMSEC KG is not initialized, the radio set remains in the ALARM condition and
displays the ALARM message.

         (2) Rotate the key management (KGMT) switch to the LD KG position, then
depress and release the ESC on the front panel keypad twice. The SELF TESTING
message is displayed after the internal COMSEC KG successfully performs its power up
tests.

         (3) Once the radio completes and passes all the power up tests (approximately 60
to 70 seconds) the radio displays a prompt to connect a fill device.

         (4) If the radio is not used in a secure mode, move the KGMT switch to OP.

         (5) If the radio is used in a secure mode, the internal COMSEC KG is initialized
and the KGMT switch is placed in the LD KG position.

         (6) The three-digit alarm code in the lower right corner of the display should
read “050".

         (7) The three digit error code 255 is a catchall error code. Reinitiate the radio.

         (8) The COMSEC KG within the radio has six key variable storage locations.
Locations 1 to 4 are user selectable traffic variable locations, 5 and 6 are used for Saville
advanced remote keying (SARK).

         (9) Switch the KGMT to LD KG.

         (10) CONNECT FILL DEVIC” blinks, connect KYK-13 to the ADF connector.

         (11) Turn on KYK-13 and screen displays KG VARIABLE FILL (put fill in any of
the variable, KG1 to KG4) depress the down arrow button.

                                                                                 E-3


---

         (12) After pushing the variable position to fill location, depress the STO/RCL
button.

         (13) The fill device light flashes. Display reads KG FILL IN PROGRESS.
         (14) Turn off KYK-13 and disconnect, the display reads KG FILL
SUCCESSFUL. (This verifies the correct transfer of the variable).
    c. Programming operating modes.

    Note: The left and right arrow buttons move to the menu option needed.

         (1) Turn the mode select to OP position.
         (2) At the function screen, select PROG use the right arrow button then depress
the down arrow button.
         (3) The program menu displays MODES and FREQS.
         (4) Select FREQS use the right arrow button followed by the down arrow button
to enter.
         (5) The Program Freqs Menu displays CH1 with the RX - TX
(DOWNLINK/UPLINK) satellite frequencies. Insert the appropriate frequencies in the
channels (there are nine channels to use).
         (6) Depress the up arrow button until STORE FREQ menu is displayed. Select
YES and depress the down arrow button to enter to save.
         (7) At the program screen select MODES use the left arrow button, then the
down arrow button to enter.
         (8) Select a preset channel to store the configuration (a number must be entered)
and depress the down arrow button.
         (9) Scroll through the terminal selections and select SATCOM, depress the down
arrow button.
         (10) Display/SOURCE KG, select INT KG, depress the down arrow button.
         (11) Display/CRYPTO MODE, select ANDVT, depress the down arrow button.
         (12) Display/ KG VARIABLE, select VARIABLE POSITION THAT IS LOADED
(1 to 6), depress the down arrow button.
         (13) Display/PHASING, select NORMAL, depress the down arrow button.
         (14) Display/TX MODE, select NORMAL, depress the down arrow button.
         (15) Display/DATA INVERT, select DISABLE, (for SATCOM), depress the down
arrow button.
         (16) Display/RADIO SCAN, select OFF, depress the down arrow button.
         (17) Display/CHANNEL SELECT, select the channel previously entered, depress
the down arrow button.
         (18) Display/POWER ADJ, select desired level (for example, 12) up to 18,
depress the down arrow button.

E-4


---

         (19) Select SAVE, the down arrow button to store in desired preset (a number
must be entered ).

(20) Press ESC until the OP screen is displayed and select OP.

(21) Recall the PRESET.

(22) After recalling the preset, the display shows a monetary alarm condition.

Radio initializes for a minute or so. Then the radio automatically accesses the satellite

and the display reads as—

                           PRESET # 1

                           SATCOM ANDVT V2.4V1

                           I I I I I I I I (power bars)

                           SIG

                           CH#1 FREQ                     RX

    d. Upon completion of the circuit, depress the ESC of the up arrow button to the
FUNCTION menu.

3. Key Variable Zeroization

    a. The radio has six fill positions. To zeroize all six key variables, pull and rotate
the KMGT switch to the extreme counter clockwise position. This is labeled ZALL. If
the radio set is in a mode that has the COMSEC hardware turned on, the display
immediately shows the ALARM message signifying a successful ZEROIZATION. The
preset operating modes are not affected by ZEROIZATION. If the radio is in a mode
with COMSEC hardware off, the display may not immediately display the ALARM
message after a ZALL. However, if a mode is entered that causes the COMSEC
hardware to turn on, the ALARM message l appears and a KG initialization is required.

    b. The radio can be zeroized by two other means. Removing the standby battery
when the radio set is turned off zeroizes all key variables. Also, unauthorized attempts
to access the COMSEC compartment zeroizes the key variables.

    c. To zeroize a specific key variable location, rotate the KMGT switch to the ZSEL.
Select (use the left or right arrow keys on the keypad) the key variable storage location
number (KG1 –to KG6) desired to zeroize.

    d. Once the proper location for the key variable is entered and verified on the
display, press and release the STO/RCL button on the keypad. If a KG variable is
selected, the message ZSEL IN PROGRESS is displayed briefly. The message ZSEL
SUCCESSFUL is displayed when the operation is completed successfully. The ZSEL IN
PROGRESS display should be brief and may not be identifiable.

4. LST-5D DAMA 25-kHz AC Procedures (For MOD-3 and Below)

    a. Under AC, 25-kHZ AC is 25-kHz DAMA. This terminal is used for satellite
communication in either voice or data mode. The channel width is 25-kHz.

    b. DAMA is a channel access scheme in which access of a channel from
geographically distributed communications terminals is allocated based on demand.

    c. AC is an operating mode that allows communications slots within the waveform
to be dynamically assigned to terminals requiring access to the slots.

                                                                                       E-5


---

    d. Prior to COLD START, press 0 and right arrow together and then turn on the
radio.

    e. This will MASTER CLEAR all settings and crypto in the radio, if needed.

5. Cold Start Initialization

    a. When unit is powered up in an un-initialized state, the unit performs system
tests and then displays a blinking ALARM message. (If the alarm blinks without going
to self-test, press ESC twice and then self-test begins.) The speaker shaped icon in the
lower left corner of the display is an ALARM annunciator. As long as the internal
COMSEC KG is not initialized, the radio set remains in the ALARM condition and
displays the ALARM message. Do not power up the unit in the OP position and then
toggle the KGMT switch to the LDOW position.

    b. The three-digit alarm code in the lower right corner of the display should read
050.

    c. The three digit error code 255 is a catchall error code. Reinitiate the radio.

6. Loading LST-5D for DAMA Use

    a. To initiate the internal fill, the KMGT switch must be placed in the LDOW
position for the internal modem to initialize. The fill device cannot be connected before
the internal modem initializes. During the initialization process, the message LOAD
CTIC ORDERWIRE INITIALIZING is displayed. If the initialization is longer than
5 minutes, toggle the switch to OP and then back to LDOW. The menu should change
within a few minutes. If the fill device connects before the modem completes
initializing, the message LOAD CTIC ORDERWIRE DISCNCT FILL DEVICE is
displayed and the fill device must be disconnected. After the modem completes
initialization, the message CONNECT FILL DEVICE blinks until a device is connected
and/or turned on or the KMGT switch is moved to another position.

    b. After the fill device is connected, the message LOAD CTIC ORDERWIRE KEY 1
is displayed. Load the appropriate keymat in all variable positions by pressing and
releasing the STO/RCL button. Do this for all variables. The lamp on the KYK-13
flashes when the button is pressed and the message OW FILL IN PROGRESS is
displayed. If the fill is completed successfully , the message OW FILL SUCCESSFUL is
displayed. In addition, when the KYK-13 is turned off, the CONNECT FILL DEVICE
message is displayed. Toggle the KGMT switch to the LDKG position and load the
ANDVT) keymat in load variable 1 of the LST-5D by pressing and releasing the
STO/RCL button. When the KGMT switch is toggled to the LDKG and the ALARM 255
flashes in the lower right corner, press the ESC button. The radio goes into an ALARM
050 and then to self-testing. Wait for the CONNECT FILL DEVICE to flash and then
load the ANDVT keymat.

7. Programming Operating Modes

    a. Turn the mode select to the OP position.

    b. At the function screen, use the right arrow button to select PROG and then
depress the down arrow button.

    c. The program menu displays MODES and FREQS.

E-6


---

    d. Select FREQS using the right arrow button followed by the down arrow button to
enter.

    e. The Program Freqs Menu displays CH1 with the RX - TX (Downlink/Uplink)
satellite frequencies. Insert the appropriate frequencies in the channels (there are nine
channels to use).

    f. To save the frequencies depress the up arrow button until STORE FREQ menu
displays. Select YES and depress the down arrow to enter.

    g. At the program screen, select MODES using the left arrow button and then the
down arrow button to enter.

    h. Select a preset channel in which to store the configuration (a number must be
entered) and depress the down arrow button.

    i. Scroll thru the terminal selections and select 25-kHz AC and depress the down
arrow button to enter.

    j. Select the frequency channel the satellite frequencies are stored in and then
depress the down arrow button to enter.

    k. Adjust the power up to 18 watts. Depress the down arrow button.
    l. Select ranging NORMAL. Depress the down arrow button.
    m. TX INHIBIT: select NO. Depress the down arrow button.
    n. XMODE ADDR: insert the TBA for that radio. The communication plan should
have this information.
    o. INTKG ADDR: automatically changes to the next higher number. Depress the
down arrow button.
    p. INTKG is displayed with 25-kHZ AC.
    q. ORDERWIRE: select ENABLE. Depress the down arrow button.
    r. CRYPTO MODE: select ANDVT. Depress the down arrow button.
    s. KG VARIABLE: insert 1. ANDVT keymat should have been inserted in
variable 1. Depress the down arrow button.
    t. DATA INVERT: can select DISABLE or ENABLE. (Does not matter with voice).
Depress the down arrow button.
    u. DEST ADDR: insert the NET # from the COMM STATUS REPORT. Depress
the down arrow button.
    v. CONFIG CODE: insert the number from the COMM STATUS REPORT.
Depress the down arrow button.
    w. ALLOW CONSTANT KEY: select NO. Depress the down arrow button.
    x. XMODE now displayed with 25-kHZ AC.
    y. Throughout XMODE menus, depress the down arrow button. Do not change any
of the menus. Used only with external crypto.
    z. GUARD ADDR 01: insert the NET #. Depress the down arrow button.

                                                                                                                                   E-7


---

    aa. INTKG should flash. Leave as is. Depress the down arrow button.

    bb. GUARD ADDR 02: Leave as is. (all XMODE menus are leave as is). Depress the
down arrow button.

    cc. Arrow over to SAVE. Depress the down arrow button.

    dd. STORE INTO PRESET: insert desired preset which is to be stored. (Enter
number).

    ee. Hit ESC or UP ARROW until the FUNCTION MENU is displayed. Arrow over
to OP and depress the down arrow button.

    ff. RECALL PRESET: enter the number where the preset is stored.The display
shows a monetary alarm condition. The menu reads as—

                                         PRESET 1 SU
                                         25KAC ANDVT V2.41
                                         INITIALIZING

    gg. Once the radio completes initializing, source dual port reads as—
                                         DAMA DL/IL OK
                                         SOURCE: DUAL PORT

    hh. The menu reads as—
                                         STAT REPROT B (either) NACKED or
                                         ACKED
                                         *DOWN ARROW TO NEXT

    ii. Depress the down arrow button. The menu reads as—
                                         XMODE NOT CONNECTED
                                         INTKG NOT CONNECTED

    jj. Depress the down arrow button. The menu reads as—
                                         REQUEST CALL
                                         TERMINATE CALL
                                         SEND STAT REPORT B
                                         *RESERVED

    kk. Depress the down arrow button. The menu reads as—
                                         INHIBIT TX
                                         PAGE USER(S)
                                         SEND INFO REPORT

    ll. Depress the down arrow button. The menu reads as—
                                         OUT OF SERVICE
                                         PERFORM LINK TEST
                                         *RESERVED*
                                         EXIT PRESET

    mm. Depress the down arrow button, returns to DAMA DL/UL OK menu.

    nn. To make calls on air.

         (1) Go to the REQUEST CALL menu

         (2) Press number 1.

E-8


---

         (3) DAMA CALL REQUEST
         (4) CH PREC = ROUTINE
         (5) PORT INTKG OR XMODE appears
         (6) Use INTKG, press the down arrow button
         (7) CALL PREC: ROUTINE appears (This is the call precedence. Press the
down arrow button.)
         (8) CONFERENCE CALL? Yes or No
         (9) USER 1
         (10) Enter the NET number. Press the down arrow button.
         (11) Radio emits RCCOW and displays if it is or is not connected.
         (12) If the menu states the RCCOW NACKED, go back to the REQUEST CALL
menu and reinitiate.
         (13) After completing the use of the circuit, press the ESC or the up arrow
button and scroll until the EXIT PRESET is displayed and press number 4.

8. Fill Procedures Using A KYX-15

    a. On the KYX-15, select the desired key to be loaded (1 to 16), then set the switch
to the LD position. On the radio, enter and verify on the display the proper storage
location for the variable. Press and release the STO/RCL button on the radio set’s
keypad and the lamp on the KYX-15 flashes when the button is pressed. The message
KG FILL IN PROGRESS is displayed. To verify correct transfer of the variable,
disconnect the KYX-15. If the fill completed successfully, the message KG FILL
SUCCESSFUL is displayed.

    b. Continue with the operating procedures.

9. Key Variable Zeroization

    See section 3 above.

                                                                                                                                   E-9


---



---

                                                Appendix F

                               AN/ARC-231/SKYFIRE

1. Skyfire Operator Training

    a. Obtain basic operational knowledge of the AN/ARC-231(V3).
    b. Radio (Skyfire) system characteristics and capabilities.
    c. Understand basic operations of the Skyfire radio.
    d. Load COMSEC variables.
    e. Load presets manually and through software/PCMCIA.
    f. Place Skyfire radio into various modes of operation, to include plain and Cipher
text modes.
    g. Change from preset to manual operations and back to preset.

2. Skyfire Characteristics and Capabilities

    Multi-band receiver/transmitter that provide the following modes of communication:
    a. LOS 30- to 400-MHz.
    b. Maritime voice communications 156- to 162.025-MHz.
    c. HAVE QUICK (HQ) voice communications 225- to 400-MHz.
    d. Single channel ground and airborne radio system voice and data 30- to
87.975-MHz.
    e. SATCOM DAMA 5-kHz and 25-kHz channel spacing voice and data 225- to
400-MHz.
    f. Non-DAMA SATCOM voice and data 225- to 400-MHz.
    g. ADF 30- to 400-MHz.
    h. Beacon transmission 30 to 400 MHz.
    i. Scan mode up to ten preset frequencies and transmit on one stored frequency,

3. Capabilities and Features

    a. Menu driven operations displayed on a 5 line by 20 character control interface
    b. Internal diagnostics that continuously run built in test routines.
    c. Embedded COMSEC functions provide VINSON, ANDVT), KG-84 modes 1 to 4,
and FASCINATOR.
    d. Preset mode allows storage of 20 sets of parameters for the following modes:
LOS, Maritime, HQ, single channel ground and airborne radio system, and non-DAMA
SATCOM.

                                                                                                                                   F-1


---

    e. DAMA SATCOM mode allows storage of 30 presets.

    f. The radio stores the last operating mode and all presets in non-volatile memory.
In addition, COMSEC keys are retained up to 20 minutes when internal battery is fully
charged, or indefinitely using an external hold up power source.

4. Control/Fill Panel                         Figure F-1. Control/Fill Panel

    a. Data display 5 line 20 characters.
    b. Preset card slot
    c. Selector control
    d. Enter encryption key switch
    e. Fill connector
    f. Mode select switch
    g. Toggle switches

5. Loading COMSEC

    Note: Unless stated otherwise, all switches and controls called out in this
              procedure are on the control indicator (CI).
              Until directed, do not connect fill device.
              Always load key position number 1 first, for proper key recall.

    STEP 1. Set mode switch on fill panel from PT to CT position.

    The following message appears–

                               COMSEC RANDOMIZE
                               PROCEED TO F1 AND
                               PRESS ENT TWICE

                                 (0)
                               S/G M/Z D/D P/N X/E

The following message appears–

                         INITIALIZING
                         TERMINAL FOR
                         KEY FILL
                         S/G M/Z D/D P/N X/E

    STEP 2. Press the X/E ↓Control Enter switch down, the (0) field changes to (1).
    STEP 3. Press the X/E ↓ Control Enter switch down again, the (1) field changes to
(2).
    STEP 4. Press the ENTER switch twice on the fill panel to ensure COMSEC is
randomized

F-2


---

    The following message appears–
                               F1: COMSEC
                               CONNECT DEVICE
                               S/G M/Z D/D P/N X/E

    STEP 5. Connect desired fill device such as, KYK-13, KYX-15, or CYZ-10
(configured for DS-102) to the fill panel connector; the display shows the COMSEC fill
menu when the fill device is turned on.

                               F1: COMSEC
                               DS-102
                               COMSEC Key: _ _
                               KEY TYPE: VINSN
                               S/G M/Z D/D P/N X/E

    STEP 6. Rotate the selector control knob clockwise, as required, to select COMSEC
key storage position (01 to 19). Next press ENTER (X/E) ↓

    STEP 7. Rotate selector control knob to select desired key type (ANDVT, FASCN,
VINSN, or #KG84, where #=1, 2, 3, or 4). (Field defaults to over-the-air rekeying if
position 20 was selected.)

                               F1: COMSEC
                               DS-102
                               COMSEC Key: 01
                               KEY TYPE: VINSN
                               S/G M/Z D/D P/N X/E

    STEP 8. Set address select (fill) switch on KYK-13 to the desired position.
    STEP 9. Press (X/E) ↓ Enter switch on the control indicator and observe that LED
on KYK-13 flashes.
    STEP 10. The CI display shows the message Key Filled or Key Fill Failure.

                               F1: COMSEC
                               KEY FILLED
                               COMSEC Key: _ _
                               KEY TYPE: VINSN
                               S/G M/Z D/D P/N X/E

    STEP 11. If key fill failed message appears, repeat steps 6 through 9 and try to fill
radio again.

                                                                                                                                   F-3


---

    STEP 12. If additional keys need to be filled, select desired key on fill device (if
applicable) and repeat steps 6 through 9. If key fill operation is complete, turn off and
disconnect COMSEC fill device from fill panel. Rotate mode select from F1 to CT or PT
position.

    Note: If at any time, the radio displays an alarm condition; follow the instruction
              given by the radio to clear the alarm properly.
              If an alarm condition does not clear using the instructions given, press
              the ↑ X/E switch to escape the menu and reset the radio.
              If an alarm condition persists, turn off radio for 15 to 30 seconds and then
              turn the radio on in PT mode. Allow the radio to go through BIT to
              ensure fault is not a system failure. Once BIT is complete and the radio
              goes into the current operations mode, continue previous operation.

6. Download Presets

    Note: Unless stated otherwise, all switches and controls called out in this
              procedure are on the control indicator (CI).

    STEP 1. Set mode switch on fill panel to PT. After BIT is complete, the display
shows the last active operational CURRENT MODE.

                               LOS-P01 Rx-PT-120
                               AM V16K
                               R378.050 T378.050
                               GUARD: OFF
                               S/G M/Z D/D P/N X/E

    STEP 2. Press MODE (M/Z)↑. The display shows the CI mode menu.
    STEP 3. Insert the pre-loaded PCMCIA card into PCMCIA port on the CI.
    STEP 4. Rotate selector control knob to select LOAD PRESETS and press ENTER
(ENT) ↓.

                               CI MENU
                               CMD: SAVE PRESETS
                               ENT

    STEP 5. The display shows the LOAD PRESETS submenu. Notice toggle switches
on CI change function and are re-identified.

    STEP 6. Press LOAD switch up or down to activate loading process.

F-4


---

CI MENU
LOAD PRESETS
LOADING PRESETS
LOAD EXIT

    STEP 7. When message PRESET LOAD COMPLETE is displayed, the PCMCIA
card may be removed from PCMCIA port on the CI.

CI MENU

LOAD PRESETS

PRESET LOAD COMPLETE

LOAD          EXIT

STEP 8. Press EXIT switch up or down to deactivate LOAD PRESET function.

STEP 9. The display returns to the main CI mode menu.

                         CI MENU
                         CMD: SAVE PRESETS
                         ENT

    STEP 10. To return to radio operating menus, rotate selector control knob to select
CONTROL RT and press ENTER (ENT).↓

                               CI MENU
                               CMD: CONTROL RT
                               ENT

    STEP 11. The radio returns to the main menu with cursor flashing over number 1.
Press the ENTER (X/E)↓ switch to return to the current operating mode.

                               MAIN MENU
                               1 - CURRENT MO
                               2 - DATABASE OPTIONS
                               3 - SET PRESETS
                               S/G M/Z D/D P/N X/E

7. Save Presets Manually

    STEP 1. From the current operating mode, press the ESCAPE/ENTER ↑(X/E)
switch to proceed to the main menu.

                                                                          F-5


---

     MAIN MENU
     1 - CURRENT MODE
     2 - DATABASE OPTIONS
     3 - SET PRESETS
     S/G M/Z D/D P/N X/E

    STEP 2. Press the (P/N) ↓ switch until cursor is flashing over number 3, then press
the ENTER (X/E)↓ switch to activate the preset submenu. With cursor flashing over the
number 1, press the ENTER (X/E)↓ switch to activate the preset submenu.

MAIN MENU                  SET PRESETS
1 - CURRENT MODE           1 – SET MODE PRESETS
2 - DATABASE OPTIONS       2 – 5-K SERVICE
3 -SET PRESETS             3 – 25K SERVICE
S/G M/Z D/D P/N X/E        S/G M/Z D/D P/N X/E

    STEP 3. Rotate the selector control knob to move through available selections, or
select numeric value using the (D/D) ↑ number switch to change the numeric value and
the (X/E) ↓ to accept the number. Press the ENTER (X/E)↓ switch to save choice in the
non-volatile memory.

                               SET MODE PRESET
                               LOS-P01 Sq- -39
                               TK 01 AM VINSN V16K
                               R378.050 T378.050
                               GUARD: OFF
                               NORMAL Tpwr 43 dbm

    STEP 4. After setting all desired presets; press the ESCAPE/ENTER ↑(X/E) switch
twice to proceed to the main menu.

                               MAIN MENU
                               1 - CURRENT MODE
                               2 - DATABASE OPTIONS
                               3 - SET PRESETS
                               S/G M/Z D/D P/N X/E

    STEP 5. Press the ENTER (X/E)↓ switch to return to the current operating mode.

8. Brightness Adjustment

    STEP 1. Press MODE (M/G)↑. The display shows the CI mode menu.

F-6


---

    STEP 2. Rotate selector control knob to select BRIGHTNESS and press ENTER
(ENT) ↓

                               CI MENU
                               CMD: BRIGHTNESS
                               ENT

    STEP 3. Rotate the selector knob to brighten or dim the display. Press the EXIT
switch up or down to save the brightness setting and return to the CI mode menu.
Press the NVG or NORM switch up or down to apply or remove the NVG brightness
delta respectively.

CI MENU     EXIT
BRIGHTNESS
NVG NORM

STEP 4. Press the EXIT switch up or down to deactivate brightness menu.

STEP 5. The display returns to the main CI mode menu.

                         CI MENU
                         CMD: SAVE PRESETS
                         ENT

    STEP 6. To return to radio operating menu, rotate selector control knob to select
CONTROL RT and press ENTER. (ENT) ↓.

                               CI MENU
                               CMD: CONTROL RT
                               ENT

    STEP 7. The radio returns to the main menu with cursor flashing over number 1.
Press the ENTER (X/E)↓ switch to return to the current operating mode.

                               MAIN MENU
                               1 - CURRENT MODE
                               2 - DATABASE OPTIONS
                               3 - SET PRESETS
                               S/G M/Z D/D P/N X/E

9. LOS Operations

    a. Preset operation.

                                                                                       F-7


---

    Note: Unless, stated otherwise, all switches and controls called out in this
              procedure are on the Control Indicator (CI). Do not proceed to CT
              operations until radio initialized in PT.

    STEP 1. Set mode switch on fill panel to PT. Initialization BIT runs for
approximately 30 seconds when PT is selected.

    STEP 2. With cursor flashing in the display mode field, rotate selector control knob
left or right until LOS appears then press ENTER (X/E) ↓. The cursor moves to preset
the field.

    STEP 3. Rotate selector control knob for desired preset (01 to 20) and press ENTER
(X/E) ↓.

                               LOS-P01 Sq- -030
                               AM V16K
                               R378.050 T378.050
                               GUARD: OFF/ NONE
                               S/G M/Z D/D P/N X/E

    STEP 4. For CT operations change mode switch to CT, ensure prior to LOS
operations, proper key is loaded according to COMSEC loading procedures. If required,
rotate selector control knob to select desired key (01 to 19) then press (X/E) ↓. to
configure radio.

                               LOS-P01 Tx-CT-38 TK 01
                               AM VINSN V16K
                               R378.050 T378.050
                               GUARD: OFF
                               S/G M/Z D/D P/N X/E

    STEP 5. Begin communications.
    b. Manual LOS operation
    For manual operation, make desired changes to CURRENT MODE menu (for
example, transmit power, operating frequency, and so forth). After making changes, the
“—P” field changes to “—M” to indicate manual operation.

                               LOS-M01 Sq- -30

    STEP 1. Press PREVIOUS/NEXT (P/N) ↓↑ to move to desired field(s) for changes.
    STEP 2. Rotate selector control knob to move through available selections, or select
numeric value using the (D/D) ↑ switch to change the numeric value
    STEP 3. Press ENTER (X/E) ↓. Switch to accept change and configure radio.
    STEP 4. Begin communications

10. LOS Guard Operations

    a. Perform the following steps to control guard operation:

F-8


---

         (1) On = Activates guard receiver.
         (2) Off = Deactivates guard receiver.
         (3) Emergency = Disables guard receiver and tunes main receiver to guard
channel.
    STEP 1. Press NEXT (P/N) ↓ to scroll down menu to guard field.
    STEP 2. Rotate selector control knob to select On, Off, or Emergency.

LOS-P01 Sq- -30    V16K
TK 01 AM VINSN      X/E
R378.050 T378.050
GUARD: ON
S/G M/Z D/D P/N

    STEP 3. Press ENTER (X/E) ↓.
    STEP 4. Begin communications.

11. SATCOM Operations

    a. Preset operation.
    Note: Unless stated otherwise, all switches and controls called out in this

              procedure are on the control indicator (CI). It is assumed proper
              COMSEC key material is loaded and system is initialized in PT mode.

    STEP 1. Set mode switch on fill panel to CT.
    STEP 2. With cursor in the display mode field, rotate selector control knob to
SATCOM and press ENTER (X/E) ↓.
    STEP 3. Rotate selector control knob for desired preset (01 to 20) and press ENTER
(X/E) ↓. Radio reconfigures.

                               SATCOM-P01 Rx-CT-120
                               TK 01 FSK VINSN V16K
                               CHANNEL NUMBER: 100
                               R295.975 T262.375
                               S/G M/Z D/D P/N X/E

    STEP 4. Begin communications.
    b. Manual operation.
    Note: For manual operation, simply make desired changes to CURRENT MODE

              menu (for example, transmit power, channel number, and so forth.). After
              making changes, the preset “—P” field changes to “—M” to indicate
              manual operation.

    STEP 1. Press PREVIOUS/NEXT (P/N) ↓↑ to move to desired field(s) for changes.

                                                                                                                                   F-9


---

    STEP 2. Rotate selector control knob to move through available selections, or select
numeric value using the (D/D) ↑ number switch to change the numeric value.

    STEP 3. Press ENTER (X/E) ↓ press the Enter switch to configure to radio.
                               SATCOM-M01 Rx-CT-120
                               TK 01 FSK VINSN V16K
                               CHANNEL NUMBER: 100
                               R295.975 T262.375
                               S/G M/Z D/D P/N X/E

    STEP 4. Begin communications.

F-10


---

                                                Appendix G

                                       AN/WSC-3

1. Setting Up for DAMA

    At antenna controller, dial in the elevation and azimuth of satellite (such as, UHF
follow-on 6) that the assigned channel is located. This setting depends on a ship’s
location and it changes as the ship travels the ocean. There is an azimuth/elevation
computation aid used to determine these values; each ship has one or more.

    a. Verify all power to the SA-2000 is on and all switches are turned on.
    b. On WSC-3 turn on or set as follows:

         (1) Turn power on.
         (2) Place standby/operate switch to operate.
         (3) Place control switch to local.
         (4) Place SATCOM/LOS switch to SATCOM.
         (5) Place modulation switch to EXT Modem.
         (6) For frequency select switches, dial the uplink frequency from Daily Comm
Status message for the operational channel (for example, CONUS DAMA 1).
         (7) Completely turn power control knob clockwise, then turn back approximately
one-quarter turn.
         (8) Partially extend radio from chassis.

                (a) Set SATCOM offset switch to offset 4. (This is the normal setting if the
difference between uplink and downlink frequency is 41-MHz. Sometimes offset 3 is
used if the difference is 33.6-MHz.)

                (b) This switch sets the downlink frequency in the radio.
                (c) Set TDMA/non-TDMA switch to TDMA position.
                (d) Return radio into chassis.
    c. At SB-4125 or SB-4126 IF patch panel, patch the TD-1271 Xmt to the
transmitting radio. Patch the TD-1271 Rcv to the receiving radio. (Usually it is the
same radio.)
    d. On the SB-4124 PATCH panel on the OK-454 or OK-455 equipment rack, ensure
the TD-1271 XMT position is either normal thru’d or patched to the radio used to
transmit. This TD-1271 XMT position is the top left position on the panel (A1J1).
    e. At the TD-1271.
         (1) Turn on the TD-1271.
         (2) Ensure the transmit inhibit switch is off.

                                                                                                                                   G-1


---

         (3) Load proper current keymat variable into the KGV-11 memory position called
for in the Daily Comm Status message for the operational channel and according to the
ship’s CMS procedures.

         (4) Normally, loading is performed with a KYK-13 or KOI-18.

         (5) Set KGV mode switch to Fill.

         (6) Attach fill device to front of KGV-11, set the KYK-13 to the proper position in
which the key variable is located and turned on.

         (7) Depress bite alarm reset pushbutton. Any bite alarm should clear.

         (8) Use the numeric keypad to depress the memory position number specified in
the Daily Comm Status message (for example, 0 or 1 CONUS, 2 or 3 LANT). Then press
Fill pushbutton. The KG alarm light should go out.

         (9) If using a KOI-18 pull tape through tape reader. KG alarm light should go
out.

         (10) Shut off and remove fill device

         (11) Set KGV mode switch to operate.

         (12) If everything above is lined up and loaded correctly, the TD-1271 acquires
and logs on the channel within approximately 5 to 10 seconds. An indication this
happened is a 6 (randomly a D) displayed in the front window of the multiplexer. If a B
displayed, check the crypto load for currency or proper memory location. If a C
displayed, check the IF patching on the SB-4125/4126, TD-1271 XMT control patching
on the SB-4124 patch panel, and satellite antenna azimuth/elevation alignment.

         (13) If the 6 (randomly a D) display is observed, the terminal is operating in
DAMA.

         (14) Press number 1 followed by the ENTER key to transmit the status report.
Acceptance and completion of this is observed by the ACCPT, XMT, and ACK lamps on
the front panel of the TD-1271. Upon receipt of the status report, the channel controller
automatically issues a channel change command, the TD-1271 alarms, automatically
enter port 1 and display an information code of AAA99. Enter number 600000 and
depress the ENTER key to clear the alarm. (This clear sequence has to be repeated in
the other ports as they were entered.)

         (15) Use the command *6 to exit port1. (The ENTER key is not required.)

         (16) Connect to the proper circuit(s). From the Daily Comm Status message for
the operational channel, record the guard number and configuration code of the circuit
where communications are established. For example—

                               CIRCUIT GUARD CC
                               SATHICOM 15014 60

    f. On the SB-4124 patch panel, find the baseband device (such as, ANDVT) and
either normal-through or patch the device to one of the four TD-1271 I/O ports.
Assuming port 2.

    g. On the TD-1271, use the following keystroke to enter port 2:

G-2


---

         (1) Enter *92 then depress the Enter key. (Port 1 is *91, port 3 is *93, and port 4
is *94.)

         (2) Enter number 600000 then depress the Enter key to clear any AAA99 IR
codes.

         (3) Enter the configuration code *5 60 then depress the Enter key. The TD-1271
transmits the configuration of the port to the channel controller. This is observed by the
ACCPT, XMT, and ACK lamps on the front panel of the TD-1271.

         (4) Enter the guard number into the port—*1 15014—then depress the Enter
key. A momentary 01 is displayed if that is the only guard in the multiplexer port. If
more than one guard is in the port a 02 or higher number is displayed. The preference is
to have only one guard in each port and that the same guard number is not put into any
other port. To read what guards are entered in the port, depress number 2 and watch
the display. A number is displayed for two seconds, which is the TBA of the port (for
example, 02157). Each guard number in the port is displayed for two seconds. To
remove unwanted guard numbers use the command number 4 followed by the guard
number then depress the Enter key (for example, number 4 15008 ENTER).

         (5) Use the keystrokes—#76 15014 ENTER—to request a connection to the
appropriate guard. The ACCPT, XMT, and ACK lamps on the front panel of the TD-
1271 cycle. If the guard number is a valid guard for the channel, the proper
configuration code was entered, and the terminal is an authorized user on the channel.
The channel controller responds with a guard connect command. (If one of the previous
actions is not valid, an information code is returned.) There is a laminated sheet with
the codes and their meanings). If everything is correct, the port connects to the correct
time-slot (guard) and beeps five times to indicate a connection. The CALL CONN lamp
should illuminate.

(6) Enter *7 to display the guard number the terminal connected to.

(7) Enter *6 to exit the port.

(8) Repeat above steps for other circuits/baseband equipment configurations.

h. When a connection is no longer required or desired—

(1) Enter the appropriate port with a *91, *92, *93, or *94 command.

         (2) Enter—*4 ##### Enter–to remove the guard number (for example, *4 15014
ENTER).

(3) Enter number 4 to disconnect from the circuit.

(4) Enter *6 to exit the port.

Notes:  Be observant of KGV-11 keymat rollover dates and memory locations.
        They are listed in the Daily Comm Status messages. If mux front panel
        PREC display goes to a B, it is an indication of improper key or memory
        location.
        Do not put the same guard number in two or more ports.
        If the TD-1271 beeps entering a guard connect request (for example,
        number 76 #####) and refuses to take the guard, it indicates the port is
        keyed already. The source of the key must be removed before the TD-

                                                                                   G-3


---

              1271 accepts entry of the guard connect request.
              Call COMM (843) 218-4937/4939 or DSN 588-4937/4939, SPAWAR
              Charleston if problems are experienced.

G-4


---

                                 Appendix H

        EMI CHARACTERIZATION CHECKLIST

    Extract from CJCSM 3320.02, Joint Spectrum Interference Resolution (JSIR)
Procedures.

                                   Table H-1. EMI Characterization Checklist

STEP    ACTION                                                                              COMPLETE
                                                                                                 Y/N

001     Start a log and collect as much information as possible.
002     Record what interference sounds like. If appropriate measurement equipment is
        available, an attempt should be made to quantify the characteristics of the
003     interference signal. These characteristics include the interfering source’s center
003-01  frequency, bandwidth, relative amplitude, modulation, direction of interference,
003-02  time of occurrence, and any other characteristics that can be obtained.
004     Geographical Information.
005     Check with other units in the geographical area to determine the area affected.
005-01  Verify exact location of receiver using global positioning system, if available.
005-02  Determine interference start and stop times.
005-03  Ensure affected system is operating correctly.

006     Ensure all connectors are tight.
007     Ensure antenna cables are in good condition.
007-01  Have maintenance personnel ensure equipment is operating IAW technical
        manual specifications and frequency assignment parameters.
007-02  Verify antenna is on the correct azimuth and elevation.
        Environment Information
007-03
007-04  Contact all nearby units to determine if they have recently installed any new
        equipment.
008     Check with equipment maintenance personnel to determine if the interference is
008-01  the result of maintenance actions or an equipment malfunction. This should
        include non-RF equipment that can cause spark-type interference used to
        support the operation of RF equipment (e.g., thermostat-controlled devices,
        electric motors, welders, etc.)
        Check to see if construction is being conducted in the immediate area.
        Determine whether the natural environment is the cause of the problem; see
        Enclosure F.
        Frequency Assignment Information
        Verify through service Component or JTF spectrum manager that a valid
        frequency assignment and/or satellite authorization exists.

008-02  If no assignment exists, cease transmission and request new frequency.
008-03
        If valid assignment exists, change to alternate frequency and determine if
        interference is present. If interference is to a satellite communications system,
        skip to step 9.

008-04 If a valid assignment exists and the interference goes away after changing to an

                                                                                            H-1


---

STEP    ACTION                                                                              COMPLETE
                                                                                                 Y/N

008-05  alternate frequency, submit an interference report through next higher
        headquarters and info JSC.
009
009-01  Where co-channel or adjacent channel interference is suspected (i.e., the
        interfering signal overlaps the operating bandwidth of the victim receiver), check
009-02  with local and area frequency management personnel to determine if other
009-03  locally operated equipment has been recently assigned a co-channel or adjacent
009-04  channel frequency.
009-05
        Satellite Communications Interference for MILSATCOM
009-06
009-07  Net Control Station should contact the supporting SSC and determine if they can
009-08  identify interference on the satellite. A determination shall be made at this time
010     as to whether the interference is on the uplink or downlink of the satellite
011     channel. If two or more users separated by 300 miles are observing the same
012     interference, the interference is likely on the uplink.

        If no interference is present on the satellite uplink frequency, request to be
        switched to an alternate channel in a different part of the frequency band.

        If SSC reports a steady receive key (SRK) on the channel, have all users vacate
        the net.

        Once all users are off the net, contact SSC and ask if the SRK is present.

        If SRK is gone, have users re-access the net one at a time while SSC monitors;
        once the user that was causing the interference moves back onto the net the
        SRK will re-appear.

        If SRK is present, request another channel for testing. Have users move to the
        new channel, one at a time, while monitoring the channel.

        Once all users have moved to new channel, determine if SRK is present on the
        original channel.

        If SRK is present on original channel, initiate a harmful interference report.

        Combatant command or JTF will request JSC support to help resolve
        interference to terrestrial systems.

        Combatant command or JTF will request resources to support interference
        resolution to space systems.

        Provide feedback through the chain of command to the affected unit of actions
        taken and the resolution.

H-2


---

                                                Appendix J

                                     CUT SHEETS

    The following figures are examples of cut sheets. Each unit may have developed cut
sheets specific to their unit or mission.

      LOS Cut Sheet                                        Presets

Mode  Parameter       Value        1  2                    3  4     5  6

LOS      Modulation          AM
                             FM
          Encryption        FSK
                         VINSON
      Communications  FASCINATOR
          Data Rate       4-KG84
                          3-KG84
         Scan Mode        ANDVT
      TX Power (dBm)       KYV5
                           VOICE
       RX Frequency        DATA
       TX Frequency          12k
        Mode Switch          16k
                             32k
                             56k
                             64k
                         NORMAL
                           SCAN

                         PT or CT

                      Figure J-1. Sample of LOS Cut Sheet

                                                                       J-1


---

        SATCOM Cut Sheet                         Presets

Mode    Parameter         Value            1  2  3                4  5  6

SATCOM      Encryption    ANDVT/MELP
                             VINSON
        Communications        4-KG84
                              3-KG84
            Data Rate         VOICE
                               DATA
        TX Power (dBm)          1200
         Home Channel           2400
                                9600
             Number              16k
          (no SATCOM           19.2k
        loopback if 999)       28.8k
         RX Frequency            32k
         TX Frequency          38.4k
                                 48k
            Encoding             56k
          Mode Switch
                              9 to 239
                               or 999

                          required if 999
                          required if 999

                                DIFF
                             Non-DIFF
                             PT or CT

                          Figure J-2. Sample of SATCOM Cut Sheet

J-2


---

DAMA Database Set up                                       Presets

Mode Parameter Values 1                     2        3     4             5              6

               Backlight     2 to 60
                 Timer      seconds

                                      1        2        3     4               5            6

               Guard List             7        8        9  10                 11        12

                                      13    14       15

                Terminal              LAT   LON      Zulu Address Platform Msg. Rel.
                   Data
DAMA Database                         2400                            Stationary Manual
               5-kHz I/O              ID #
               Data Rate                    LON Ascen. Inc.

                Satellite
               Ephemeris

                                      AC/DC Request        Meaning                      Response
                                                                                            N/A
                                      AC 70 Network address not in guard list               N/A
                                                                                            N/A
                                      AC    71       Violated Maximum Precedence
                                                                                            N/A
                                      AC    72       Already have a pending service
                                                                                            N/A
                                      AC    75          Requester sent teardown
                                                                  message                   N/A
                                                                                            N/A
                                      AC    77             Terminal address not in
                                                                    database                N/A

               Information            AC    81          Data rate incorrect - check         N/A
                  Codes                                      configuration code
                 (25-kHz                                                                    N/A
                  Only)               AC    82             Address called incorrect
                                                                                            N/A
                                                     Configuration code incorrect for       N/A

                                      AC    88             network                          N/A

                                                     Configuration code does not

                                      AC    89             match distant end

                                      AC    90          All addresses called are not
                                                                    available

                                                     Some addresses called are not

                                      AC    92             available

                                      AC    93       Someone else is running link test

                                      AC    98          Two or more addresses are
                                                             network addresses

                            Figure J-3. Sample of DAMA Cut Sheet page 1

                                                                                                  J-3


---

      DAMA Cut Sheet                                 Presets

Mode    Parameter           Value              1  2  3        4  5  6

          Encryption       ANDVT
      Communications       VINSON
                            KG-84
      Data Rate             VOICE

DAMA  Channel Variant       DATA
      TX Power (dbm)           75
                              300
                              600

                             1200
                             2400
                             4800
                             9600
                              16k
                            5-kHz
                            25-kHz

                           23 to 43

      Channel Number       9 to 239

      RX Frequency         For Reference Only

         TX Frequency      For Reference Only
      Configuration Code
                                    5-kHz
        OW Encryption              25-kHz
      Mode of Operation           PT or CT
                                   Normal
             Ranging              EMCON
      Satellite ID Number           Silent
                                    Active
                                   Passive
                             Passive Ranging
                                Only (1 to 8)

                 Figure J-4. Sample of DAMA Cut Sheet page 2

J-4


---

                         Appendix K

               Prioritization Scheme

               Table K-1. SATCOM Priority Table

               SATCOM PRIORITY TABLE

Note: CINCs and other users rank order within a category when multiple accesses are
assigned the same priority

Priority User  Category

Priority 1     Strategic Order (Essential to National Survival)
1A             System Control/Orderwire
1B             National Command Authorities
1B1            Presidential Support
1B2            Secretary of Defense Support
1B3            Envoy and Emissary Support
1C             Strategic and Threat Warning/Intelligence
1D             SIOP/Force Direction Requirements
Priority 2     Warfighting Requirements
2A             Department of State Diplomatic Negotiations
2B             CJCS Support
2C             COCOM Operations
2D             JTF or CTF Operations
2E             Component Operations (Theater Forces)
2F             Tactical Warning and Intelligence
2G             CJCS-Sponsored Select Exercises
2H             Counternarcotics Operations
Priority 3     Essential Nonwarfighting Operational Support
3A             Humanitarian Support
3B             Intelligence and Weather
3C             Logistics
3D             Radio Frequency Interference Resolution
3E             Diplomatic Post Support
3F             Space Vehicle Support
3G             Other Service Support

                                                                                     K-1


---

                 Table K-1. SATCOM Priority Table

                 SATCOM PRIORITY TABLE

Note: CINCs and other users rank order within a category when multiple accesses are
assigned the same priority

Priority User    Category

     Priority 4  Training
     4A          CJCS Sponsored
     4B          COCOM Sponsored
     4C          MAJCOM, major command, Echelon 2 Sponsored
     4D          Unit Sponsored
     Priority 5  VIP Support
     5A          Service Secretaries
     5B          Service Chiefs
     5C          COCOM Travel
     5D          Other Travel
     Priority 6  RDT&E and General
     6A          DOD-Sponsored Testing
     6B          DOD-Sponsored Demonstrations
     6C          DOD Administrative Support
     6D          DOD Quality of Life Initiatives
     Priority 7  Miscellaneous
     7A          DOD Support to Law Enforcement
     7B          Other Non-DOD Support
     7C          Non-U.S. Support as approved by the authorized organization
     7D          Other

K-2


---

                                      References

                                                     Joint

CJCSM 3122.01, Joint Operating Planning and Execution System (JOPES) Volume I
     (Planning Policies and Procedures) 14 July 2000

CJCSM 3320.02, Joint Spectrum Interference Resolution Procedures (JSIR) 8 November
     2002

CJCSI 6250.01A, Satellite Communications 10 December 2001

                                           Military Standards

MIL-STD 188-181, Interoperability Standard for Single-Access 5-kHz and 25-kHz UHF
     Satellite Communications Channels, 18 September 1992

MIL-STD 188-181A, Interoperability Standard for Single-Access 5-kHz and 25-kHz UHF
     Satellite Communications Channels, 31 March 1997

MIL-STD 188-181B, Interoperability Standard for Dedicated 5-kHz and 25-kHz UHF
     Satellite Communications Channels, 20 March 1999

MIL-STD 188-182, Interoperability Standard for 5 kHz UHF DAMA Terminal Waveform,
     18 September 1992

MIL-STD 188-182A, Interoperability Standard for 5 kHz UHF DAMA Terminal Waveform,
     31 March 1997

MIL-STD 188-183, Interoperability Standard for 25-kHz TDMA/DAMA Terminal
     Waveform, 18 September 1992

MIL-STD 188-183A, Interoperability Standard for 25-kHz TDMA/DAMA Terminal
     Waveform, 20 March 1998

                                                     Navy

NAV SUP P-409, MILSTRIP/MILSTRAP Desk Guide, 9 June 1998
NTTP 1-01, The Navy Warfare Library

                                                  Air Force

AFI 33-360, Publications Management Program, 29 December 2000

                                                                                                                     References-1


---



---

          Glossary

µs        PART 1 -- ACRONYMS AND ABBREVIATIONS

A               microsecond

A               signal amplitude
AC              automatic control
ADF             audio/data/fill connector for the LST-5D
AFDC            Air Force Doctrine Center
AFI             Air Force instruction
AFTTP(I)        Air Force technical training publication (inter-Service)
ALSA            Air Land Sea Application
AM              amplitude modulation
ANDVT           advanced narrowband digital voice terminal
ARSPACE         Army Space Command
ASCEN           ascension
ASYNC           asynchronous
ATM             asynchronous transfer mode
ATTN            attention

B               bits per second
                binary phase-shift keying
bps
BPSK            total received carrier power
                channel controller
C               channel control orderwire
C               channel
                channels
CC              control indicator
CCOW            commander-in-chief
CHAN            Chairman of the Joint Chiefs of Staff
CHLS            Chairman of the Joint Chiefs of Staff instruction
CI              Chairman of the Joint Chiefs of Staff manual
CINC            carrier-to-noise power density
CJCS            clear
CJCSI           communications message processor
CJCSM           carrier to noise ration
C/kT
CLR
CMP
C/N

                                                                          Glossary-1


---

COCOM       combatant command
COMM        commercial
COMSEC      communications security
CONPLAN     concept plan
CONUS       continental United States
            continuous phase modulation
CPM         cyclic redundancy check
            cipher text
CRC         combined task force
CT          communications security/transmission security integrated
CTF         circuit
CTIC
            demand assigned multiple access
D           demand assigned multiple access configuration
            demand assigned multiple access network
DAMA        demand assigned multiple access semi-automatic controller
DAMACFG     demand assigned single access
DAMANET     decibel
DAMA SAC    decibel (referenced to milliwatts)
DASA        distributed control
dB          degree
dBm         differentially encoded quadrature phase-shift keying
DC          Defense Information Systems Agency
deg         digital modular radio
DEQPSK      Department of Defense
DISA        Defense Satellite Communications System
DMR         defense switched network
DOD         data/voice
DSCS
            east
DSN         energy per bit
D/V         extremely high frequency
E           effective isotropic radiated power
            emission control
E           electromagnetic interference
Eb          emerging operations
EHF         encrypted
eirp        enter
EMCON       engineering orderwire
EMI
EMOP
EN
ENT
EOW

Glossary-2


---

EPHEM     ephemeris
ESC       escape
EST       Eastern
EURCENT   Europe Central
EXPLAN    exercise plan

F         fascinator
          facsimile
FASC      figure
FAX       fleet satellite communications
FIG       field manual, frequency modulation
FLTSAT    Forces Command
FM        forward orderwire
FORSCOM   frequency
FOW       Fleet Satellite Communications System
FREQ      frequency-shift keying
FSCS
          global broadcast service
FSK       gigahertz
G         global positioning
GBS       global system for mobile communications
          Global SATCOM Support Center
GHz
GPS       handset
GSM       high frequency
GSSC      high
          high performance waveform
H         HAVE QUICK, headquarters
          hour
HD SET    hertz
HF
HI        in phase
HPW       in accordance with
          inter-theater COMSEC package
HQ        identification
HR        initial distribution number
Hz        indefinite
          international maritime satellite
I         input/output

I
IAW
ICP
ID
IDN
ind
INMARSAT
I/O

                                                   Glossary-3


---

IO           Indian Ocean
IP           internet protocol

J            command, control, communications, and computer systems
             directorate of a joint staff
J-6          Joint Chiefs of Staff
             Joint Forces Command
JCS          Joint Frequency Management Office
JFCOM        Joint Interoperability Test Command
JFMO         Joint UHF Military Satellite Communications Network
JITC         Integrated
JMINI        Joint Spectrum Center
             joint spectrum interference resolution
JSC          joint task force
JSIR
JTF          kilobits per second
             keyboard display unit
K            key generator
             key management
kbps         kilohertz
KDU          kilometer
KG
KGMT         local area network
kHz          Atlantic
km           latitude
             low data rate
L            limited input/output
             longitude
LAN          line of sight
LANT         link quality
LAT          lightweight satellite terminal
LDR
LIO          major command
LON          United States Marine Corps Forces, Europe
LOS          United States Marine Corps Forces, Atlantic
LQ           United States Marine Corps Forces, North
LST
             United States Marine Corps Forces, Pacific
M            Marine Forces Reserve
             United States Marine Corps Forces, South
MAJCOM
MARFOREUR
MARFORLANT
MARFORNORT
H
MARFORPAC
MARFORRES
MARFORSOUTH

Glossary-4


---

MB          megabyte
Mbps        megabytes per second
MCCDC       United States Marine Corps Combat Development Command
MCRP        Marine Corps reference publication
MELP        mixed excitation linear prediction
MHOP        multiple-hop
MHz         megahertz
MILSATCOM   military satellite communications
MIL-STD     military standard
MILSTRIP    military standard requisition and procedure
MIN         minute
ms          milliseconds
MSG         message
            multi-Service tactics, techniques, and procedures
MTTP
N           integer number; north
            not applicable
N           Navy supplement publication
N/A         narrowband
NAVSUP P    noncommissioned officer
NB          network control station
NCO         Naval Computer and Telecommunications Area Master Station
NCS         Naval Computer and Telecommunications Area Master Station
NCTAMS      Europe Central
NCTAMS      Naval Computer and Telecommunications Area Master Station
EURCENT     Pacific
NCTAMS PAC  Naval Computer and Telecommunications Area Master Station
            Satellite Management Center
NCTAMS SMC  Naval Computing and Telecommunications Station
            Naval Computing and Telecommunications Station, Guam
NCTS        national information infrastructure
NCTS GUAM   nautical miles
NII         noise power spectral density
nmi         National Security Agency
No=kT       Navy tactics, techniques, and procedures
NSA         Navy Warfare Development Command
NTTP
NWDC        operate
            operations plan
O           orderwire

OP
OPLAN
OW

            Glossary-5


---

P           Pacific
            primary channel controller
PAC         program
PCC         precise lightweight global positioning receiver
PGM
PLGR        preventive maintenance checks and services

PMCS        point of contact

POC         phase-shift keying
            plain text
PSK         power
PT
PWR         quadrature phase shift keying

Q           return channel control orderwire
            research, development, test and evaluation
QPSK        radio frequency
            return orderwire
R           Regional SATCOM Support Center
            Regional Space Support Center Europe
RCCOW       Regional Space Support Center Pacific
RDT&E       receive signal strength indicator
rf          receiver
ROW
RSSC        south
RSSC EUR    satellite access assignment
RSSC PAC    semi-automatic controller
RSSI        satellite access request
RX          Saville advanced remote keying
            satellite communications
S           shaped binary phase-shift keying
            single channel anti-jam man portable terminal
S           spectrum management
SAA         satellite database
SAC         second
SAR         super high frequency
SARK        signal intelligence
SATCOM      single integrated operational plan
SBPSK       secret internet protocol router network
SCAMP
SCCF
SDB
SEC
SHF
SIGINT
SIOP
SIPRNET

Glossary-6


---

SMC            Satellite Management Center
S/N            signal to noise
SOCCENT        Special Operations Command, Central
SOCEUR         Special Operations Command, Europe
SOCKOR         Special Operations Command, Korea
SOCPAC         Special Operations Command, Pacific
SOCSOUTH       Special Operations Command, South
SPAWAR         Space and Naval Warfare
               Space and Naval Warfare Systems Center
SPAWARSYSC
EN             space command operations center
SPOC           steady receive key
               space support center
SRK            secure telephone equipment
SSC            secure telephone unit
STE            service
STU            synchronous
SVC
SYNC           tactical satellite
               terminal base address
T
               time division multiple access
TACSAT         traffic encryption key
TBA            telemetry
TD             Training and Doctrine Command
TDMA           transmission security
TEK            task
TLE            tactics, techniques, and procedures
TRADOC         transmitter
TRANSEC
TSK            unified combatant command
TTP            ultra high frequency follow-on
TX             ultra high frequency
               ultra high frequency satellite communications cell Regional
U              Space Support Center Pacific
               United Kingdom
UCC            unencrypted
UFO            United States of America
UHF            United States Air Force
UHF SATCOM
CELL RSSC PAC
UK
UN
USA
USAF

               Glossary-7


---

USARPAC            United States Army, Pacific
USASFC             United States Army Special Forces Command
USASOC             United States Army Special Operations Command
USEUCOM            United States European Command
USMC               United States Marine Corps
USN                United States Navy
USSOCOM            United States Special Operations Command
USSOUTHCOM         United States Southern Command
USSTRATCOM         United States Strategic Command

V                  very high frequency
                   encrypted ultrahigh frequency communications system
VHF                very important person
VINSON
VIP                watts; west; with
                   wide area network
W                  wideband

W                  Zulu

WAN
WB
Z

Z

access             PART II -- TERMS AND DEFINITIONS
acknowledgment
acquisition          The ability, permission, or liberty to communicate with, or
                     make use of, any system resource.
acquisition back-
off number           A message from the addressee indicating that information
active ranging       has been received without error.
active service
                     A necessary preliminary condition of a receiver, by which
address              frequency and phase ambiguities of an incoming radio
                     frequency (rf) carrier are sufficiently resolved to allow
                     information modulated onto the carrier to be properly
                     demodulated.

                     A number used by the terminal in the algorithm to reduce
                     the possibility of conflicting transmissions during the initial
                     ranging of terminals.

                     The transmission and subsequent reception of a burst signal
                     used for estimating the range to a satellite.

                     A service that has been assigned communications resources
                     and has not been torn down. Active services are either
                     assigned or preempted.

                     A 16- or 14-bit code that uniquely identifies a terminal I/O
                     port or network.

Glossary-8


---

algorithm             A procedure or formula for solving a mathematical problem.
                      Extremely complex algorithms or sets of algorithms are used
allocation            to simplify, modify or predict data in the digital
alternate channel     manipulation of information. Often, algorithms developed
controller            for digital applications are proprietary and are an important
angle of inclination  aspect of defining significant differences among the various
                      digital compression and codec (coding/decoding) standards.
antenna
                      TDMA frame time apportioned by the PCC for a particular
apogee                function.
assigned service
assigned-return       The control station function that monitors the channel and
orderwire time-slot   can assume control, either manually by operator action or
                      automatically when it detects that the PCC has failed.
asymmetric
warfare               The angle at which a satellite’s orbit is tilted in relation to
                      the Earth’s equator. A 90-degree angle of inclination is a
asynchronous          polar orbit. A zero degree angle of inclination is an
transfer node         equatorial orbit.
atmosphere
                      A device for transmitting and receiving radio waves.
attenuation           Depending on their use and operating frequency, antennas
attitude              can take the form of a single piece of wire, a dipole, a grid
                      such as a yagi array, a horn, a helix, a sophisticated
                      parabolic-shaped dish, or a phased array of active electronic
                      elements of virtually any flat or convoluted surface.

                      The point in orbit where an object, such as a satellite, is
                      farthest from Earth.

                      A service being assigned communications resources.

                      A ROW segment time-slot that a PCC assigns to a specific
                      terminal for the terminal's sole use. The assignment is made
                      by the PCC when the terminal is required to respond to a
                      FOW, such as when the PCC transmits a FOW requesting a
                      network status message be transmitted by the terminal.

                      Unanticipated or non-traditional approaches to circumvent
                      or undermine an adversary’s strengths while exploiting his
                      vulnerabilities through unexpected technologies or
                      innovative means. Simply put, dirty fighting that gives the
                      weak the best chance to defeat the strong.

                      A switching architecture that uses cell relay technology to
                      carry vast quantities of data at extremely high speeds.

                      The layer of gas surrounding the earth or other planets. The
                      upper atmosphere is the region of Earth’s atmosphere above
                      the troposphere (which extends to about 20-km). Regions of
                      the upper atmosphere are the stratosphere, mesosphere and
                      thermosphere.

                      The loss of power of electromagnetic signals between the
                      transmission and reception point. It can be caused by
                      distance or weather.

                      The position in space of a spacecraft or aircraft. A satellite’s

                      Glossary-9


---

aurora              attitude can be measured by the angle the satellite makes
automatic control   with the object it is orbiting, usually the Earth. Attitude
automatic           determines the direction a satellite’s instruments face. The
frequency change    attitude of a satellite must be constantly maintained; this is
                    known as attitude control.
bandwidth
                    Light radiated by ions and atoms in the Earth’s upper
baseband            atmosphere, mostly in polar regions.
binary phase-shift
keying              An operating mode that allows communications slots within
bit                 the waveform to be dynamically assigned to terminals
                    requiring access to the slots.
bit error rate
bit rate            A terminal capability to automatically switch to and operate
                    on another 5- or 25-kHz DASA or DAMA channel upon
                    receipt of a FOW directing such a change. This capability
                    requires the change to be accomplished within 8.96...seconds
                    for switching to a DASA channel, 90 seconds for switching to
                    another DAMA channel (5- or 25-kHz), and 90 seconds for
                    switching from a DASA channel to a DAMA channel. The
                    90-second switching time from a DASA to a DAMA channel
                    applies when assigned time on DASA channel expires.

                    A measure of spectrum (frequency) use or capacity. For
                    instance, a voice transmission by telephone requires a
                    bandwidth of about 3000 cycles per second (3-kHz). A TV
                    channel occupies a bandwidth of 6 million cycles per second
                    (6-MHz) in terrestrial systems. In satellite-based systems, a
                    larger bandwidth of 17.5- to 72-MHz is used to spread or
                    “dither” the television signal in order to prevent
                    interference.

                    The original band of frequencies produced by a signal-
                    initiating device such as a microphone or data key prior to
                    the initial modulation of the carrier.

                    A form of PSK in which the instantaneous phase of the
                    carrier can be either unchanged or shifted 180 degrees. The
                    information content of an uncoded BPSK signal is 1 binary
                    digit (bit) per symbol; therefore, the symbol rate and the
                    information rate are identical.

                    A single digital unit of information The smallest increment
                    of digital information. Often referred to as a 1 or 0 in the
                    binary system. Also referred to as an ‘on’ or ‘off’ when
                    referring to the mechanical operation of bits in the
                    computer.

                    The fraction of a sequence of message bits that are in error.
                    A bit error rate of 10Î6 means that there is an average of
                    one error per million bits.

                    The amount of data being transported, measured relative to
                    quantity over time in bps; the speed of a digital
                    transmission, measured in bps.

Glossary-10


---

bit                  The condition achieved when significant transitions of the
synchronization      recovered data rate clock are phase-stable to within 25
(clock lock)         percent of the bit period.
blocked service
                     A queued service held from scheduling, awaiting (1) the
building block       availability of participating terminals busy with other
burst                services, or (2) the completion of setting up the path for a
burst code           multiple-hop service.
burst rate
bus                  A fundamental unit of channel time used in determining
                     time within a frame. Used in the assignment of channel
carrier              resources.

carrier acquisition  A time-limited transmission composed of a synchronization
carrier frequency    preamble and a finite-length data stream that are formatted
                     into interleaver block pairs.
carrier to noise
ratio                A combination of modulation rate, coding rate, and (for
                     message services) maximum burst size.
cassegrain
channel              The over-the-air transmission rate (modulation rate) in
                     symbols per second.

                     The body of a satellite. The bus holds all of the scientific
                     equipment and other necessary components of the satellite.
                     The bus of a satellite is made of a variety of materials that
                     are selected to protect the satellite from things like
                     collisions, a build-up of electric charge, extreme
                     temperatures, and radiation.

                     The basic radio, television, or telephony center of frequency
                     transmit signal. The carrier in an analog signal is
                     modulated by manipulating its amplitude (making it louder
                     or softer) or its frequency (shifting it up or down) in relation
                     to the incoming signal. Satellite carriers operating in the
                     analog mode are usually frequency modulated.

                     The condition achieved when a receiver carrier reference is
                     coherent in frequency and phase with the receive signal.

                     The main frequency on which a voice, data, or video signal is
                     sent. Microwave and SATCOM transmitters operate in the
                     band from 1- to 14-gigahertz (GHz) (a GHz is one billion
                     cycles per second).

                     The ratio of the received carrier power and the noise power
                     in a given bandwidth, expressed in dB. This figure is
                     directly related to G/T (antenna gain-to-noise temperature
                     in dB/K) and signal/noise (S/N); and in a video signal the
                     higher the C/N, the better the received picture.

                     The antenna principle that utilizes a sub-reflector at the
                     focal point that reflects energy to or from a feed located at
                     the apex of the main reflector.

                     A frequency band in which a specific broadcast signal is
                     transmitted. The Federal Communications Commission
                     specifies channel frequencies in the United States.

                     Glossary-11


---

channel control      The transmissions from a controller that control the
orderwire            waveform and its usage, such as frame number, encryption
                     synchronization counts, user time-slot assignments, and
channel control      frame format in current use.
orderwire
acquisition          The terminal’s status when it has successfully achieved
channel control      error free reception of a CCOW: Master Frame (checked by
orderwire time-slot  CRC).
channel controller
channel resources    The time-slot through which a terminal receives CCOW
circuit burst kind   transmissions.
circuit number
circuit service      A generic term that relates to either a primary or alternate
                     controller.
C/kT
                     The available time, bandwidth, and power of a channel.
coherent
demodulation         A field that identifies the type of burst being transmitted
connected            during a circuit service.

connectivity         A 5-digit decimal number that identifies a time-slot when
contention-return    operating in the DC mode.
orderwire time-slot
                     Channel resource assignments in each frame that are
continuous phase     dedicated for use by participating members for duration of
modulation           the assignment.

control channel      The ratio of the rf carrier power (C) relative to noise power
                     density. Carrier power is measured into the receiving
                     system. k = Boltzman's constant and T = the effective noise
                     temperature at the terminal antenna in kelvins.

                     A demodulation process characterized by a synchronized,
                     phase-matched condition between a receiver's reference and
                     the received signal.

                     The configuration of a channel controller in which
                     connectivity to adjacent satellite footprints by relay is
                     available.

                     The physical infrastructure required to allow access and
                     exchange of electronic information.

                     A ROW segment time-slot available for use by any terminal
                     that has achieved downlink acquisition. The possibility
                     exists that transmissions from multiple terminals occurs in
                     the same time-slot.

                     A phase-only modulation technique in which the signal
                     phase changes are continuous. Phase changes for each
                     symbol are odd integer multiples of the modulation indices
                     hi. For multi-h CPM, the indices cyclically change from
                     symbol to symbol in order to provide coding gain to the
                     waveform.

                     A 25-kHz DAMA channel on which a channel controller (CC)
                     transmits CCOW messages and the frame is segmented for
                     terminals to transmit RCCOW, link test, ranging, and user
                     communications signals.

Glossary-12


---

control station    The equipment and software that performs resource
                   management, channel control, and external interface
controller         functions in two adjacent satellite coverage areas.

coronal mass       An entity that establishes frame format and system timing.
ejection           In the AC mode a controller also assigns waveform access to
cyclic redundancy  users.
check
data block         A vast region of hot, dense, and high speed solar wind
delay              propagating away from the Sun.

Demand assigned    A type of error detection scheme that uses parity bits
multiple access    generated by polynomial encoding and decoding algorithms
demand assigned    to detect transit-generated errors.
single access
destination        A quantity of user data (224 bits) used in integer multiples
terminal           within message-service packets.
differential
encoding           The time it takes for a signal to go from the sending station
                   through the satellite to the receiving station. This
differentially     transmission delay for a single hop satellite connection is
encoded            very close to one-quarter of a second.
quadrature phase-
shift keying       A highly efficient means of instantaneously assigning a
digital            channel in a transponder according to immediate traffic
                   demands.
digitization
                   An access scheme in which a SATCOM channel is assigned
distance learning  for single access through the DAMA control system in
                   accordance with demand.

                   The terminal addressee of a communication.

                   A process by which baseband digital data before modulation
                   is used to resolve the phase ambiguity of digital data
                   recovered from demodulation. It is not used for error
                   detection or correction. A process such that if the prior code
                   bit and the message bit are the same, the encoder output is
                   zero. If they are different, the encoder output is a one.

                   Quadrature phase-shift keying (QPSK) that has been
                   differentially encoded. DEQPSK is used to resolve the
                   phase ambiguity of digital data recovered from
                   demodulation. It is not used for error detection or
                   correction.

                   Conversion of information into bits of data for transmission
                   through wire, fiber optic cable, satellite, or over the-air
                   techniques. Method allows simultaneous transmission of
                   voice, data or video.

                   Digitization comprises the nuts and bolts solution for
                   synchronizing the vast amount of communications and
                   sensor equipment on the battlefield. Digitization allows a
                   plane to talk to a ship to talk to a soldier, etc.

                   Using video technology to allow students in one location to

                   Glossary-13


---

distributed control   participate in a class broadcast from another location.
Doppler shift
                      An operating mode in which a terminal's access to a
downlink              communications slot is preassigned (both time-slot and
downlink              frame format).
acquisition
dual spin             An apparent shift in the frequency of a wave. For example,
                      when someone is listening to the sound of an ambulance
eccentricity          siren, and that person is staying still but the ambulance is
                      driving by, the person hears a change in pitch of the
effective isotropic   ambulance siren. That change in pitch is caused by the
radiated power        “Doppler effect”. The frequency of a sound wave determines
                      the pitch, so the distance of the source of the sound from the
encryption            observer of that sound determines the amount that the
                      frequency seems to have shifted, known as the Doppler shift.
energy per bit
even link test time-  The satellite-to-earth half of a 2-way telecommunications
slot                  satellite link. Often used to describe the receive dish end of
field                 the link.
fill bits
                      Condition during initial acquisition of the waveform, when
                      the terminal or a non-controlling CC receives a correct FOW
                      burst.

                      Spacecraft design whereby the main body of the satellite is
                      spun to provide altitude stabilization, and the antenna
                      assembly is despun by means of a motor and bearing system
                      in order to continually direct the antenna earthward. This
                      dual-spin configuration thus serves to create a spin-
                      stabilized satellite.

                      The measure of how circular a satellite’s orbit is. For a
                      perfectly circular orbit the eccentricity is zero; elliptical
                      orbits have eccentricities between zero and one. The higher
                      the eccentricity, the more “squashed” the orbit is.

                      This term describes the strength of the signal leaving the
                      satellite antenna or the transmitting earth station antenna,
                      and is used in determining the carrier/noise (C/N) and
                      signal/noise (S/N). The transmit power value in units of
                      decibels relative to 1 watt is expressed by the product of the
                      transponder output power and the gain of the satellite
                      transmit antenna.

                      To encode data so as to render a document unreadable by all
                      except those who are authorized to have access to it.
                      Encryption is accomplished by scrambling the bits,
                      characters, words, or phrases in the original message.

                      The average signal energy contained in a binary digit.

                      A link test time-slot used to perform dedicated ranging
                      measurements when the receive frame count is even.

                      A specific portion of a burst or message.

                      Fill bits are used to complete the last interleaver block and
                      must be zero.

Glossary-14


---

flush bits         All-zero bits added to a data field prior to encoding to
footprint          provide proper convolutional encoder operation.

format             The area with which a satellite in geostationary orbit can
format number 1    communicate. A footprint can be as large as an entire
                   country; for example, many Canadian satellites have
format number 2    footprints almost the entire size of Canada, from coast to
forward error      coast.
correction
forward orderwire  The structuring of a frame into time-slots for the
frame              transmission and reception of CCOW, RCCOW, ranging,
                   link test, and user communications bursts.
frame count
frame format       The frame structure in effect when subformat B-1 is
                   selected. Used to reduce contention for half-duplex
frame lock         terminals [at radio frequency (rf)] that require
                   communications on two 2400-bps circuits.
frame lock loss
frame subformat    The frame structure in effect when subformats B-00 or B-2
frame time delay   through B-F are selected.

                   Adds unique codes to the digital signal at the source so
                   errors can be detected and corrected at the receiver.

                   The OW used for transmitting control and status
                   information from a PCC to terminals or alternate channel
                   controller.

                   A unit of time on the channel. (5-kHz DAMA) A frame is
                   8.96 seconds long and consists of 1024 building blocks,
                   which are grouped into segments for waveform overhead
                   and user-to-user communications. (25-kHz DAMA). A unit
                   of time on a channel. A frame is 1.3866 seconds long and is
                   subdivided into waveform overhead slots and user time
                   segments.

                   The sequence in which a particular frame occurs. The frame
                   count is defined by a 21-bit field transmitted by the
                   controller in each master frame.

                   The frame time-slot configuration defined by the
                   combination of frame subformats in use for user segments A,
                   B, and C. Also refers to the 3-digit hexadecimal code used to
                   specify this configuration.

                   The status a terminal achieves when it has received and
                   detected the precise location of two consecutive CCOWs. A
                   terminal that achieves this status is considered to have
                   properly established receive frame timing.

                   The condition of a terminal that has not decoded any CCOW
                   for 5 minutes for DC mode and 2 minutes for AC mode.

                   The time-slot configuration of user communications
                   segments A, B, or C. Also refers to the 1-digit hexadecimal
                   code used to specify this configuration.

                   Time delays introduced due to conversion of a continuous

                   Glossary-15


---

frequency code   data stream into burst-formatted data blocks.
frequency-shift
keying           An 8-bit code that defines the uplink and downlink
                 frequency pair of a satellite transponder.
frequency
switched         A form of frequency modulation. In FSK modulation, the
connection       frequency of the carrier is discretely controlled by the
frequency        transmitted information bits. In binary FSK, the
switching        instantaneous frequency of a signal is shifted between two
frequency        discrete values called the mark and space frequencies.
uncertainty
                 A time-slot connection on a channel other than the one
full-duplex      where the terminal receives CCOW.

gain             The ability of a terminal to transmit and receive in multiple
                 channels within the same frame.
geosynchronous
                 The difference between a received signal's expected
global           frequency and its actual frequency. Frequency uncertainty
ground segment   results when (1) a difference in frequency between reference
                 oscillators exists, (2) Doppler effects cause frequency shifts,
guard group      or (3) frequency-setting inaccuracies occur.
guard list
guard time       (1) Communications that occur in both directions (transmit
                 and receive) within one frame. (2) A terminal characteristic
Glossary-16      that signifies the capability to simultaneously receive and
                 transmit rf signals.

                 A measure of amplification. It is the ratio of output,
                 current, voltage or power to input current, voltage or power,
                 respectively. Gain is usually expressed in decibels. If the
                 ratio is less than unity, the gain expressed in dB, is
                 negative, in which case there is a loss between input and
                 output.

                 Refers to an orbit with a period equal to one day. A satellite
                 in geosynchronous orbit above Earth’s equator stays over
                 the same point on Earth at all times. Communications
                 satellites are often put in geosynchronous orbits so that
                 satellite dishes on earth can remain pointed at the same
                 point in the sky at all times.

                 A network configuration in which relays are present and
                 data may be routed to a network on another satellite
                 channel.

                 A term that describes that portion of the total
                 communications satellite system that is situated on the
                 Earth such as the transmitting and receiving antennas,
                 signal generating facilities, repeaters, RF receivers and
                 digital encoding equipment and decoders.

                 A group of terminals that have a common guard address.

                 A set of addresses for which a terminal receives services.

                 Unused time interval within a frame that prevents overlap
                 of transmissions that could occur due to timing differences


---

half-duplex          between transmitting terminals.
high power
satellite            A terminal characteristic that allows receipt and
home channel         transmission of signals, but not both at the same time.

hyperspectral        A satellite with greater than 100 watts of transponder radio
                     frequency transmitting power.
inclination angle
indicator            The control channel that a terminal uses to receive its
input/output data    CCOW messages and transmit its RCCOW and other system
rate                 support messages.
Internet
                     An instrument capability using many very narrow spectral
interoperability     frequency bands (300 or more), enabling a satellite-based
key generator        passive sensor to discriminate specific features or
identification       phenomena on the body being observed (e.g., Earth).
number
key generator        The angle between a satellite's orbital plane and the earth's
memory               equatorial plane.
key generator net
number               A symbol, flag, or signal that serves to identify a specific
local area network   state or item.

link test time-slot  The rate, in units of bps, at which bits are sent to or received
                     from an I/O device.
local
                     Interconnection of thousands of networks linked by a
local footprint      common set of technical protocols which make it possible for
                     users to communicate and use services.

                     The ability to have applications and computers from
                     different vendors work together on a network.

                     A unique 16-bit ID number associated with the OW
                     encryption/decryption device. The KG ID number is the
                     same as the terminal base address.

                     A 3-bit code that defines one of eight memory locations in
                     which the KG keys used for OW encryption and decryption
                     are stored.

                     A 5-bit code used to prepare the KG, which encrypts the
                     CCOW and RCCOW.

                     A group of computers and related equipment connected
                     locally, usually within a single building, by a
                     communications channel capable of sharing information
                     among several users.

                     A shared time-slot used by a terminal to evaluate its link
                     conditions or measure two-way range to the satellite. A link
                     test is performed only in odd-numbered frames; range
                     measurements are performed only in even-numbered
                     frames.

                     (1) Operations within a channel or group of channels in a
                     single footprint controlled by one PCC. (2) Initiations by an
                     equipment operator.

                     The satellite coverage area of a PCC and the terminals
                     operating under its control.

                     Glossary-17


---

low power satellite  A satellite with less than 30 watts of transponder radio
master frame         frequency transmitting power.

master frame         A frame occurring once in every eight frames that identifies
epoch                the current waveform format and other configuration
medium power         parameters.
satellite
message service      A set of eight contiguous frames, beginning with a master
modem                frame.

modernization        A satellite with greater than 30 watts but less than 100
                     watts of transponder radio frequency transmitting power.
modulation rate
modulo               A service that provides resources for transmitting messages,
multicast            using a packet-oriented protocol.

multi-h              A telecommunications device that converts between analog
                     and digital signals, allowing communication over voice
multiple-channel     circuits.

multiple-hop         The replacement of equipment, weapons systems, and
multiplexing         facilities in order to maintain or improve combat capability,
narrowband           upgrade facilities, or reduce operating costs.
operation
net guard address    The rate at which information is transferred across a
                     satellite channel, in units of symbols per second.
node
noise power          A mathematical function that yields the remainder of a
spectral density     division.
noncoherent
                     Multicast is a subset of broadcast that extends the broadcast
                     concept of one to many by allowing “the sending of one
                     transmission to many users in a defined group, but not
                     necessarily to all users in that group.”

                     A scheme that employs multiple modulation indices, or h
                     values, that are cyclically changed for successive symbol
                     intervals.

                     The network capability of automatically switching from
                     channel to channel within a single satellite footprint for
                     transmit and receive services when commanded by the PCC.

                     Operations that relay information between two or more
                     satellite channels.

                     Techniques that allow a number of simultaneous
                     transmissions over a single circuit.

                     A communications mode whose essential spectral content is
                     limited to a channel of nominal 5-kHz bandwidth.

                     Address above the demarcation number that allows multiple
                     terminals to communicate. Also called network address,
                     guard address, subnet address, or guard list address.

                     A terminal or channel controller in a network.

                     The noise power per hertz (Hz) of bandwidth (No = kT)

                     A demodulation process in which there is no synchronized

Glossary-18


---

demodulation        phase-matched condition between a receiver's reference and
nonprocessed        the desired signal.
channel
nonregenerative     A channel capable only of receiving, amplifying, filtering,
transponder         limiting, frequency translating, and retransmitting a
Northern Lights     received signal. (There is no signal processing.)
offset quadrature
phase-shift keying  A transponder (e.g., a satellite repeater) in which digital
                    signals are not reconstituted.
operator
orbit               A name for the aurora occurring over the North Pole.
orderwire
                    A form of offset quadrature phase-shift keying in which the
originator          in-phase (I) and quadrature bit streams are offset in time by
packet              one-half a symbol period, equal to the reciprocal of the data
pad bits            rate.

passive ranging     The person who controls and operates a communications
                    terminal or controller.
pending service
perigee             The path of an object that is moving around a second object
polarization        or point.
polar orbit
                    The portion of the DAMA (or TDMA) frame used for
                    transmission of management, control, and status
                    information among the channel controllers and terminal
                    users.

                    A person or terminal that initiates a communication.

                    For message service, the information transmitted in one
                    burst.

                    Pad bits are used both before and following user data when
                    insufficient user data is present to fill the data portion of a
                    burst.

                    A process by which a terminal determines signal
                    propagation time to a satellite by means other than
                    transmitting a ranging signal.

                    A queued service that is not blocked but is awaiting
                    availability of communications resources on the channel.

                    Low point of an orbit.

                    The property that describes the orientation of an
                    electromagnetic wave.

                    A satellite orbit passing over both poles of the Earth.
                    During a 12-hour day, a satellite in such an orbit can
                    observe all points on Earth.

                    Glossary-19


---

preamble           Consists of a carrier segment modulated by a predetermined
                   signal used for acquisition. The preamble may also include
preassigned        an unmodulated segment, immediately preceding the
service            modulated carrier segment, which is used by the receiver
preempted service  during carrier acquisition. The carrier segment modulated
primary channel    by a predetermined bit pattern is used by the demodulator
controller         for bit synchronization. The preamble bit pattern
quadrature phase-  immediately precedes, and is phase-locked to, transmitted
shift keying       baseband data

queued service     A type of service whose channel or time-slot allocation is
range              scheduled and set up well in advance of being used.

range lock         A service that has been interrupted to allow for higher-
                   precedence network activities.
range time-slot
ranging            The control station function that actively controls the DAMA
ranging epoch      channel.
interval
relay              A form of PSK in which the instantaneous phase of the
requested party    carrier can be either unchanged, shifted ±90 degrees, or
                   shifted 180 degrees. QPSK may be represented as two
                   independent binary bit streams modulated onto the in phase
                   (I) and quadrature phase components of the carrier. The
                   information content of a QPSK signal is 2 binary digits (bits)
                   per symbol; therefore, the symbol rate is one-half the
                   information rate.

                   A service in the request queue at the PCC waiting to be
                   assigned communications resources. Queued services are
                   either blocked or pending.

                   The round-trip distance between a satellite and a terminal
                   within the satellite footprint. (Because signal propagation
                   velocity is constant, terminals measure range in units of
                   time.)

                   The status a terminal achieves when it has determined its
                   range time delay with an uncertainty of less than or equal to
                   875-microseconds (Fs). [Terminal transmissions are
                   inhibited (except for active ranging transmissions) until the
                   terminal achieves this status.]

                   A shared slot used to measure two-way range to the
                   satellite.

                   A process by which a terminal determines signal
                   propagation time to a satellite to establish uplink timing.

                   The interval between scheduled dedicated ranging attempts
                   by a terminal.

                   A method of communications in which data is passed from
                   one DAMA channel to another to achieve greater
                   connectivity than that which is provided by the one channel.

                   The address to which a call is placed.

Glossary-20


---

requesting party     The address of the I/O port initiating a call.
return channel
control orderwire    A TDMA slot used by the terminals to (1) request, from the
                     channel controller, access to the waveform; (2) respond to
return orderwire     channel controller requests with information such as status
                     and configuration; and (3) transfer computer data to other
satellite            terminals.
satellite footprint
segment              The OW used to transmit control and status information
                     from network terminals to the channel controller and
service              perform system support functions, including ranging.
shaped binary
phase-shift keying   A body that revolves around a larger body.

shaped offset        The area of the earth's surface from which terminals are
quadrature phase-    able to access a particular satellite.
shift keying
                     A portion of a frame allocated to users for communicating.
slant range          The segment is further divided into time periods called time-
                     slots.
slave channel
                     A specified set of information-transfer capabilities provided
slot connect         to a group of users by the DAMA system.
slot number
solar flare          A form of BPSK modified to produce the phase-shift over a
                     period of time. For example, in 50 percent shaped binary
solar wind           phase-shift keying, the phase-shift occurs over a period of
                     time equal to one-half a bit period.

                     A form of offset quadrature phase-shift keying modified to
                     produce phase-shift over a period of time. For example, in
                     50-percent shaped offset quadrature phase-shift keying, the
                     phase-shift occurs over a period of time equal to one-half a
                     bit period.

                     The one-way distance between a satellite and a terminal
                     within the satellite's footprint. (Because signal propagation
                     velocity is constant, terminals measure range in units of
                     time.)

                     A DAMA channel (5- or 25-kHz) used only for user
                     communications and not for reception or transmission of OW
                     or system support messages. Channel timing is derived
                     from synchronization with the CCOW on the control
                     channel.

                     A connection between a terminal's I/O port(s) and a
                     communications slot in a TDMA frame.

                     A 5-bit code that identifies a time-slot when operating in the
                     AC mode.

                     An explosive release, marked by a sudden brightening near
                     a sunspot or prominence, of electromagnetic radiation and
                     huge quantities of charged particles from a small area of the
                     solar surface.

                     A stream of particles accelerated by the heat of the solar
                     corona (outer region of the sun) to velocities great enough to

                     Glossary-21


---

source terminal     permit them to escape from the Sun’s gravitational field.
space weather
                    The terminal from which information is considered to
special frame       originate.
format
spectrum            The conditions and processes occurring in space that have
spot beam           the potential to affect the near Earth environment. Space
                    Weather processes can include changes in the
spread spectrum     interplanetary magnetic field, coronal mass ejections from
                    the sun, and disturbances in the Earth’s magnetic field. The
subformat           effects can range from damage to satellites to disruption of
subnet              power grids on Earth.
symbols per second
                    A frame format in which one or more of a terminal's
synchronization     subformats may differ from the frame format indicated in
                    the master frame.
system support
slots               The range of electromagnetic radio frequencies used in
teardown            transmission of voice, data and television.
telemetry
telemetry,          A focused antenna pattern sent to a limited geographical
tracking, and       area. Spot beams are used by domestic satellites to deliver
                    certain transponder signals to geographically well-defined
                    areas such as Hawaii, Alaska, and Puerto Rico.

                    The transmission of a signal using a much wider bandwidth
                    and power than would normally be required. Spread
                    spectrum also involves the use of narrower signals that are
                    frequency-hopped through various parts of the transponder.
                    Both techniques produce low levels of interference between
                    the users. They also provide security in that the signals
                    appear as though they were random noise to unauthorized
                    earth stations.

                    See frame subformat.

                    A group of terminals with a need for common
                    communications that share a common address.

                    The unit of measure of the modulation rate. The modulation
                    rate in symbols per second is calculated by dividing the bit
                    rate, after forward error correction, by the number of bits
                    per symbol.

                    A deliberate attempt to determine what aspects of unit
                    processes are hindering the flow of information and order;
                    figuring out the bottlenecks and then coming up with better
                    ways.

                    Those portions of a control channel allocated for terminals to
                    perform link test and ranging operations.

                    Termination of an established communication.

                    Radio signals from a spacecraft used to encode and transmit
                    data to a ground station.

                    Telemetry, Tracking, and Control refers to the brain of a
                    satellite and its operating system. Telemetry, Tracking, and

Glossary-22


---

control             Control is the satellite’s method for storing and analyzing
                    the data it collects, and controlling its various systems. It
terminal            also logs every activity of the satellite, receives information
                    from the ground station, and takes care of any general
terminal base       upkeep, or “housekeeping”, the satellite needs to do.
address
time chip           Equipment designed to receive and transmit voice or data
time-slot           information using the frequencies, modulations, data rates,
transformation      access protocols, eirp, and sensitivity needed to establish
transmission mode   and sustain voice or data communications over a satellite
transmitter turn-   channel. A terminal may include internal or external voice
on time             or data encryption devices, or both.
transponder
uplink              The address of the lowest numbered I/O port attached to a
uplink acquisition  terminal.

user time-slot      One cycle of a 19,200-Hz oscillator (approximately
Van Allen           52-microseconds).
radiation belts
                    A fraction of a TDMA frame allocated for a specific control
                    function (FOW and ROW) (CCOW, RCCOW, Range, and
                    Link Test) or user communications.

                    (Regarding Army future change) The evolution and
                    deployment of combat capabilities that provide
                    revolutionary or asymmetric advantages to our forces.

                    A terminal configuration (such as modulation rate or I/O
                    rate) specified by the channel controller for a specific
                    transmission.

                    The time interval between baseband equipment key down
                    and the time at which the transmitter has stabilized to
                    within 90 percent of steady-state transmit power and 20-Hz
                    of the steady-state transmit center frequency

                    An instrument used on communications satellites that
                    receives a signal from a station on Earth at one frequency,
                    amplifies it, and shifts it to a new frequency.

                    The earth station used to transmit signals to a satellite

                    The status attained by a terminal or an alternate channel
                    control (1) after downlink acquisition is successful, and (2)
                    upon correct reception of a ranging burst or determination of
                    round-trip propagation time to the satellite by some other
                    means. Uplink acquisition is lost if round-trip propagation
                    time to the satellite is not known to within 12.604-
                    millisecond.

                    A fraction of the waveform frame that carries user-to-user
                    communications (such as encryption preambles,
                    independent network protocols, and encrypted data).

                    Bands of radiation trapped in Earth’s magnetic field. These
                    bands absorb ambient deep-space radiation and provide
                    protection for Earth’s surface. They are hazardous for
                    satellites and humans operating within them.

                    Glossary-23


---

waveform           The combination of baseband signal structure, rf signal
                   structure, and communications protocols that provides a
wide area network  framework within which coordinated communications can be
                   effected.
wideband
operation          A long distance computer network that enables users to
x-band             share information across large geographical distances; a
                   WAN may connect a number of LANs at different sites.
zulu
                   A communications mode whose essential spectral content is
                   limited to a nominal 25-kHz channel bandwidth.

                   A portion of the RF spectrum located between 7.25-GHz and
                   8.4-GHz that is dedicated to the United States Military for
                   SATCOM.

                   Time zone indicator for Universal Time.

Glossary-24


---

                                           Index

   A

advanced narrowband digital voice terminal (ANDVT), II-2, III-15, C-1, C-6, E-6, F-1
AN/PRC-117F, C-28, C-33
Annex-K, II-1, II-5
antenna

   SATCOM, C-5
azimuth, III-10, C-5, G-1, G-2

   B

bandwidth, I-1, I-13, II-3
   25-kHz, II-2
   5-kHz, II-2
   narrowband, I-13
   UHF TACSAT, I-7
   wideband, I-13

burst rate, I-23, I-24, I-26, II-4, C-27

   C

channel
   25-kHz, I-13, I-15, I-25
   25-kHz DAMA, I-16, I-17, I-20, I-26, II-3, II-4
   5-kHz, I-13, I-15, I-25
   5-kHz DAMA, I-15, I-17, II-4, III-12, C-34
   ad hoc DAMA, II-3
   DAMA, I-23, II-3, C-14, C-21, C-22
   DAMA multiplexing, I-15
   DASA, I-26
   narrowband, I-13, C-29
   SATCOM, I-1
   single, I-17
   TACSAT, I-6, I-15
   tactical, I-15
   UHF TACSAT, I-15, I-16
   wideband, I-13, C-29

channel allocation, III-10
channel control orderwire (CCOW), I-20, I-26
combatant commands (COCOM), I-4, I-5
combatant commands (COCOM), I-3, I-5, I-6, I-7, II-2
communication

   baseband, I-19, I-25, I-27
   data, I-13, I-15
   voice, I-13, I-15, I-17, F-1
communications message processor (CMP), I-4, I-5, I-6
communications planner, I-1, I-3, I-7, I-10, II-1
communications security (COMSEC), I-7, I-20, F-2

                                                                                                                             Index-1


---

COMSEC custodians, III-7
connection

   point-to-point, I-16
   private, I-16
   TBA-to-private (guard) network, I-16
   TBA-to-TBA, I-16

D

DAMA                                                                                          III-7,
   25-kHz, I-19, III-12, C-20

data rate, I-19, I-23, I-24, II-2, E-3
data rate, II-1
demand assigned multiple access (DAMA), III-7

   Joint UHF MILSATCOM, III-6
Dedicated TACSAT, I-15
Defense Information Systems Agency (DISA), I-5, I-6
demand assigned multiple access (DAMA), I-1, I-2, I-7, I-15, I-25, I-26, II-2, III-6,

   III-10, III-11, III-15, C-8, C-12, C-19, C-22, C-27, C-28, C-29, C-35, G-1
   25-kHz, I-16, II-3, II-4, III-11, III-12, C-8, C-19, C-21, C-27
   25-kHz AC, C-20, C-21, C-22, C-25, C-26, C-27
   25-kHz DC, C-27
   25-kHz UHF AC, C-25
   5-kHz, I-15, I-18, I-19, II-3, II-4, III-10, III-11, III-12, C-25, C-28, C-29, C-32, C-34
   challenges, III-12
   defaults, C-16
   EMCON, II-3
   home channel, I-26
   MHOP, II-3
   mini, III-6
   presets, C-19
   SAC, I-26, III-7
demand assigned single access (DASA), I-26, C-28, C-29, C-30, C-32

   E

electromagnetic interference (EMI, I-6, I-7, II-5, III-13
elevation, III-10, C-5, C-19, G-1, G-2
emerging operations (EMOP), I-1, I-7, II-1
exercise plan (EXPLAN), I-1, I-7, II-1

   F

fixed frame format, I-19
fleet satellite communications (FLTSATCOM), I-15
flexible frame format, I-18, I-19
footprint, I-15, I-16, II-3
forward orderwire (FOW), I-17, I-18
fragmentary order, II-1
frame

   25-kHz DAMA, I-20
frame cycle, I-26

Index-2


---

frame format, I-17, I-20, I-24, I-25, II-4, C-20, C-28
frequency management, I-1
frequency-shift keying (FSK), E-3

   G

Global Information Grid/Defense Information Systems Network, I-5
global SATCOM support center (GSSC), I-3, I-6, I-7
guard list, II-3, II-4, III-12, D-4

   H

home channel numbers, I-16

   J

Joint Chiefs of Staff (JCS), I-3, II-2
joint frequency management office (JFMO), I-3, I-6
Joint Staff J-6, I-4
Joint Strategic Capabilities Plan, I-5
joint task force (JTF), I-3, I-6
Joint UHF Military Satellite Communications (MILSATCOM) Network Integrated

   (JMINI), I-2, III-7

   K

key variable zeroization, E-5
KG-84, III-15

   L

link data, I-26
link test, I-25, I-26, C-27

   M

Mixed excitation linear predicative (MELP) voice encoder, III-15
multiple-hop (MHOP), I-16
multiplexing, I-17

   N

narrowband, I-24
Naval Computer and Telecommunications Area Master Station (NCTAMS), I-2, I-3, I-7,

   I-15, III-8
Naval computing and telecommunications station (NCTS), I-15
net control station (NCS), I-2, I-15, II-4
net guard address, II-3
network

   25-kHz DAMA, I-2
   5-kHz DAMA, I-2, C-28, D-7, D-13
   common, II-3, II-4
   computer, III-6

                                                                                                                             Index-3


---

   DAMA, I-7, III-6, C-20
   point-to-point signal-channel-carrier, I-2
   private, II-4
   TACSAT, II-2
   TMDA DAMA, II-3
   UHF SATCOM, I-2
network address, I-25

   O

operational access
   tactical, I-4

operations
   5-kHz DAMA, D-3
   line of sight (LOS), D-1, F-7
   SATCOM, D-2, F-8

operations
   LOS Guard, F-8

operations plan (OPLAN), I-1, I-5, I-7, II-1
orderwire (OW), I-15, I-20, III-11, III-12

   communication, I-25
   data, I-26
   encryption/decryption, III-15
   key, III-7, III-10, III-11, III-12
   out-of-service, III-12
   position, III-10
   transmissions, I-17

   P

phase-shift keying (PSK), E-3
precedence level, C-20
precedence levels, II-3
primary channel controller (PCC), I-17, I-18, I-19, I-20
procedures

   LST-5D 25-kHz DAMA, E-5
   LST-5D LOS, E-1
   LST-5D SATCOM, E-3
   using KYX-15, E-9

   R

ranging, I-25, I-26
   data, I-26

receive signal strength indicator (RSSI) test, C-6, C-19
regional SATCOM support center (RSSC), I-2, I-3, I-6, I-7
return channel control orderwire (RCCOW), I-20, I-26, C-22, C-25, E-9
return orderwire (ROW), I-17, I-19

   S

SATCOM, I-5
satellite access assignment (SAA), I-2, I-6, II-5

Index-4


---

satellite access request (SAR), I-2, I-6, I-7, II-3,  II-4,  III-7
satellite channel, I-15, II-3, II-4

   25-kHz, III-10
   5-kHz, III-10
   DAMA, I-2
satellite coverage area, I-15, III-7
satellite database (SDB), I-2, I-4, II-1
Satellite Management Center (SMC), I-2, III-6
Saville advanced remote keying (SARK), E-3
segment
   A, I-20
   B, I-20
   C, I-20
   control, I-6
   network management, I-6
   satellite, I-6
   terminal, I-6
   user, I-20
   user communications, I-19
semi-automatic controller (SAC), I-17
signal bursts, I-15
signals intelligence (SIGINT), I-7
Skyfire, F-1
slave channel, I-17, I-25, I-26, I-27
   5-kHz, I-26
   DAMA, I-25
start access date, II-2
stop access date, II-2
super high frequency (SHF), I-15

T

TACSAT, I-7, I-8, I-13, II-1                    III-6
TDMA DAMA, I-16, I-25, II-3, II-4, III-12
teardown, I-16, C-31, C-32, D-16
terminal base address (TBA), I-16, II-3, II-4,

   management, II-3
   precedence, II-3
terminal operator, I-1, I-3, C-26
time division multiple access (TDMA), I-15
traffic priority, II-3
type of information, I-7

   U

UHF satellite communications (SATCOM), I-1, I-3, I-4, II-3
ultra high frequency (UHF) tactical satellite (TACSAT), I-1, I-6
unified combatant command (UCC), I-2, I-3, I-4, I-5, I-6, I-7, II-4
United States Strategic Command (USSTRATCOM), I-3, I-4, I-5, I-15
users, I-4

   coalition, II-3

                                                                     Index-5


---

   data, I-24
   data rate, I-24
   disadvantaged, I-23, I-24, II-4
   non-Department of Defense (DOD), I-4
   special, II-3
   voice, I-24

   V

VINSON, III-15
voice, II-2

   W

waveform, I-16, I-17, I-18, I-19

Index-6


---

By Order of the Secretary of the Army:                               FM 6-02.90
                                                                MCRP 3-40.3G
Official:
       SANDRA R. RILEY                                              NTTP 6-02.9
                                                               AFTTP(I) 3-2.53
Administrative Assistant to the                             31 AUGUST 2004
     Secretary of the Army
                        0433404         PETER J. SCHOOMAKER
                                        General, United States Army

                                                   Chief of Staff

DISTRIBUTION:
Active Army, Army National Guard, and U.S. Army Reserve: Distribute in
accordance with the initial distribution number 115937, requirements
for FM 6-02.90.

By Order of the Secretary of the Air Force:

DAVID F. MacGHEE, JR.
Major General, USAF
Commander
Headquarters Air Force Doctrine Center

Air Force Distribution: F


---



---



---

MARINE CORPS: PCN 144 000148 00  PIN: 082040-000


--- 