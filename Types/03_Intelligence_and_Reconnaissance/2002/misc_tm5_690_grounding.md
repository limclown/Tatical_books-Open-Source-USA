# misc_tm5_690_grounding  TM 5-690

TECHNICAL MANUAL

   GROUNDING AND BONDING
     IN COMMAND, CONTROL,

COMMUNICATIONS, COMPUTER,
INTELLIGENCE, SURVEILLANCE,
AND RECONNAISSANCE (C4ISR)

               FACILITIES

APPROVED FOR PUBLIC RELEASE: DISTRIBUTION IS UNLIMITED

 HEADQUARTERS, DEPARTMENT OF THE ARMY

                                                                               15 FEBRUARY 2002


---

TM 5-690

                     REPRODUCTION AUTHORIZATION/RESTRICTIONS

                        This manual has been prepared by or for the Government and,
                        except to the extent indicated below, is public property and not
                        subject to copyright.
                        Copyrighted material included in the manual has been used with
                        the knowledge and permission of the proprietors and is
                        acknowledged as such at point of use. Anyone wishing to make
                        further use of any copyrighted material, by itself and apart from
                        this text, should seek necessary permission directly from the
                        proprietors.
                        Reprint or republication of this manual should include a credit
                        substantially as follows: “Department of the Army, TM 5-690,
                        Grounding and Bonding in Command, Control, Communications,
                        Computer, Intelligence, Surveillance, and Reconnaissance
                        (C4ISR) Facilities, 15 February 2002.”
                        If the reprint or republication includes copyrighted material, the
                        credit should also state: “Anyone wishing to make further use of
                        copyrighted material, by itself and apart from this text, should
                        seek necessary permission directly from the proprietor.”


---

                                                                               TM 5-690

Technical Manual                                                              HEADQUARTERS
No. 5-690                                                           DEPARTMENT OF THE ARMY

                                                                         Washington, DC, 15 February 2002

            APPROVED FOR PUBLIC RELEASE; DISTRIBUTION IS UNLIMITED

Grounding and Bonding in Command, Control, Communications, Computer,
        Intelligence, Surveillance, and Reconnaissance (C4ISR) Facilities

                                                                    Paragraph  Page

CHAPTER 1.  INTRODUCTION
            Purpose
            Scope                                                   1-1        1-1
            Objectives
            References                                              1-2        1-2
            Overview of the inspection program
                                                                    1-3        1-2

                                                                    1-4        1-2

                                                                    1-5        1-2

CHAPTER 2.  FACILITY ELEMENTS AND PROTECTION REQUIREMENTS

            Generic C4ISR facility elements                         2-1        2-1

            Element descriptions                                    2-2        2-1

            C4ISR facility protection requirements                  2-3        2-17

            Role of grounding                                       2-4        2-26

            Role of bonding                                         2-5        2-27

            Role of shielding                                       2-6        2-28

CHAPTER 3.  FACILITY GROUND SYSTEM FOR NEW C4ISR FACILITIES

            Ground systems                                          3-1        3-1

            Earth electrode subsystem                               3-2        3-2

            Fault protection subsystem                              3-3        3-17

            Lightning protection subsystem                          3-4        3-30

            Signal reference subsystem.                             3-5        3-58

CHAPTER 4.  ELECTROMAGNETIC INTERFERENCE (EMI) PROTECTION

            Purpose of EMI protection                               4-1        4-1

            Typical configuration                                   4-2        4-1

            Design considerations                                   4-3        4-2

            Typical components and installation details             4-4        4-7

            Interfaces with other grounding and bonding subsystems  4-5        4-18

            Inspections and testing                                 4-6        4-18

            Baseline configuration documentation                    4-7        4-20

CHAPTER 5.  ELECTROMAGNETTC PULSE (EMP) PROTECTION

            Purpose of EMP protection                               5-1        5-1

            Types of EMP                                            5-2        5-1

                                                                                                           i


---

TM 5-690

                                                                            Paragraph  Page

            Effects of EMP on facility systems                              5-3        5-2

            Grounding protection against EMP                                5-4        5-3

            Typical components and installation details                     5-5        5-4

            Interfaces with other grounding and bonding subsystems          5-6        5-5

            Inspections and testing                                         5-7        5-5

            Baseline configuration documentation                            5-8        5-7

CHAPTER 6.  EVALUATING, MODIFYING, AND MAINTAINING

            EXISTING C4ISR FACILITIES

            Purpose of evaluating, modifying and maintaining                6-1        6-1

            C4ISR facilities

            Facility survey                                                 6-2        6-1

            Performance evaluation program                                  6-3        6-12

            Upgrades                                                        6-4        6-12

            Expansions                                                      6-5        6-14

CHAPTER 7.  MAINTENANCE OF GROUNDING AND BONDING SYSTEMS

            Purpose of maintenance of grounding and bonding systems 7-1                7-1

            Configuration control                                           7-2        7-1

            Maintenance and repair records                                  7-3        7-1

            Earth electrode subsystem                                       7-4        7-2

            Fault protection subsystem                                      7-5        7-3

            Lightning protection subsystem                                  7-6        7-3

            Signal reference subsystem                                      7-7        7-4

            Facility shielding                                              7-8        7-5

            Performance evaluation program                                  7-9        7-5

APPENDIX A  REFERENCES                                                                 A-1

GLOSSARY                                                                               G-1

                                       LIST OF TABLES

Table       Title                                                                      Page

2-1         Grounding and bonding principles for structures                            2-3

2-2         Grounding and bonding principles for power distribution                    2-7

2-3         Grounding and bonding principles for non-electrical utilities              2-8

2-4         Grounding and bonding principles for heating, ventilation,                 2-9

            and air-conditioning

2-5         Grounding and bonding principles for earth electrode subsystem             2-10

2-6         Grounding and bonding principles for lightning protection                  2-11

2-7         Grounding and bonding principles for communications                        2-13

2-8         Grounding and bonding principles for computers and data processing         2-15

2-9         Grounding and bonding principles for controls                              2-16

2-10        Grounding and bonding principles for personnel support equipment           2-17

3-1         Approximate soil resistivity                                               3-3

3-2         Relative advantages and disadvantages of the principal types               3-6

            of earth electrodes

ii


---

                                                                                    TM 5-690

             LIST OF TABLES (Continued)

3-3          Minimum requirements for roof and down conductors on                   3-41

             structures not greater than 75 feet (23 meters) in height              3-42

3-4          Minimum requirements for roof and down conductors on                   3-49
                                                                                    3-51
             structures greater than 75 feet (23 meters) in height                  3-65

3-5          Generalized characteristics for surge arresters by type                Page

3-6          Typical withstand level limits for electrical devices                  2-4
                                                                                    2-6
3-7          Size of equipment ground cables                                        2-20
                                                                                    2-21
Figure                                      LIST OF FIGURES                         2-25
                                                                                    2-26
Figure 2-1             Title
Figure 2-2                                                                          3-8
Figure 2-3   One-line diagram of a generic ac power subsystem                       3-10
Figure 2-4   Typical ac power subsystem configuration                               3-11
Figure 2-5   Required grounding for separately derived systems                      3-12
Figure 2-6   Required grounding for non-separately derived systems                  3-16
Figure 3-1   Recommended TEMPEST signal reference subsystem                         3-18
             Recommended power grounding for secure facilities                      3-20
Figure 3-2   Earth electrode subsystem configuration for                            3-21
Figure 3-3                                                                          3-22
Figure 3-4            rectangular shaped facility                                   3-23
Figure 3-5   Earth electrode subsystem configuration for irregular shaped facility  3-24
Figure 3-6   Electrode configuration for closely adjacent structures                3-27
Figure 3-7   Typical grounding well installation                                    3-31
Figure 3-8   Sample of completed DA Form 7452-R
Figure 3-9   Grounding for fault protection                                         3-32
Figure 3-10  Typical equipment fault protection subsystem                           3-34
Figure 3-11  Single-phase 120/240 volt ac power ground connection                   3-35
Figure 3-12  Three-phase 120/208 volt ac power system ground connections            3-36
Figure 3-13  Single service entrance with common equipment grounding conductor      3-37
Figure 3-14  Single service entrance without common equipment grounding conductor   3-38
             Sample of completed DA Form 7452-1-R                                   3-39
Figure 3-15  150-foot radius of protection                                          3-40
Figure 3-16  Mean annual number of thunderstorm days based on the                   3-40
Figure 3-17
Figure 3-18           period 1948 to 1972                                           3-43
Figure 3-19  Location of air terminals on gently sloping roofs                      3-44
Figure 3-20  Location of air terminals for common roof types                        3-47
Figure 3-21  Air terminal placement on flat-roofed structures
Figure 3-22  Lower roof protection for flat roof 25-feet or less high                      iii
Figure 3-23  Lower roof protection provided by pitched roof 25-feet or less high
             Lower roof protection for flat roof 50-feet or less high
Figure 3-24  Lower roof protection for pitched roof 50-feet or less high
Figure 3-25  Criteria for dead end coverage
             Recommended construction practices for integral lightning

                      protection systems
             Overhead ground wire lightning protection system
             Secondary ac surge arrester installation, grounded service


---

TM 5-690

                 LIST OF FIGURES (Continued)

Figure    Title                                                             Page

Figure 3-26 Secondary ac surge arrester installation, ungrounded service    3-48

Figure 3-27 Lightning protection for underground cables                     3-52

Figure 3-28 Communication cable entry installation                          3-54

Figure 3-29 Grounding details for elliptical waveguide                      3-55

Figure 3-30 Ground strap fabrication details for elliptical waveguide       3-56

Figure 3-31 Sample of completed DA Form 7452-2-R                            3-57

Figure 3-32 Floating signal ground                                          3-59

Figure 3-33 Single-point signal ground                                      3-60

Figure 3-34 Single-point ground bus system using separate risers            3-61

Figure 3-35 Single-point ground bus system using a common bus               3-62

Figure 3-36 Use of single-point ground configuration to minimize effect of

          facility ground currents                                          3-62

Figure 3-37 Signal coupling for lower frequency equipment                   3-66

Figure 3-38 Sample of completed DA Form 7452-3-R                            3-70

Figure 4-1 Connection of bonding jumpers to flat surface                    4-12

Figure 4-2 Examples of bonding                                              4-13

Figure 6-1 Sample of completed DA Form 7452-4-R                             6-2

Figure 6-2 Sample of completed DA Form 7452-5-R                             6-3

Figure 6-3 Sample of completed DA Form 7452-6-R                             6-4

Figure 6-4 Sample of completed DA Form 7452-7-R                             6-5

Figure 6-5 Sample of completed DA Form 7452-8-R                             6-6

Figure 6-6 Sample of completed DA Form 7452-9-R                             6-7

iv


---

              TM 5-690

   CHAPTER 1
INTRODUCTION

1-1. Purpose

The purpose of this manual is to present an integrated set of design and installation requirements for
grounding and bonding practices in new and existing Command, Control, Communications, Computer,
Intelligence, Surveillance, and Reconnaissance (C4ISR) facilities. Grounding and bonding alone will not
and cannot guarantee absolute protection against electromagnetic (EM) environmental threats. Improper
grounding and bonding practices, however, can negate the effectiveness of other protective measures,
such as EM protection, TEMPEST protection, shielding, and surge suppression.

  a. EM protection. EM protection requirements are intended to limit the spurious emissions given off

by electronic equipment and to ensure that electronic equipment is not adversely affected by such
emissions. Typical EM requirements are contained in CFR 47 or in documents promulgated by Technical
Committee 77 (Electromagnetic Compatibility) of the International Electrotechnical Commission (IEC).

  b. TEMPEST protection. Transient electromagnetic pulse emanation standard (TEMPEST) protection
is a government standard with the purpose of protecting the compromising emanations from any
information processing equipment from the possibility of interception and extraction of classified
information by unauthorized parties.

  c. EM and TEMPEST grounding and bonding practices. A Faraday cage that provides an
electromagnetic and radio frequency shield enveloping the electronic equipment to be protected best
describes the basic requirements of EM and TEMPEST protection. This shield isolates the protected
circuits from spurious external signals and also attenuates TEMPEST emanations to levels that are too
small to be intercepted or analyzed. To be usable this shield must have penetrations for personnel and
equipment access, power lines, control cables, and ventilation. The number of shield penetrations must
be held to a minimum since each penetration is a potential leakage source unless properly grounded and
bonded. Shielding hardware and a power distribution system designed to meet the objectives of EM and
TEMPEST protection guidelines must always meet the requirements of the National Electrical Code®,
NFPA 70-1999 (NEC®). In particular, the grounding and bonding of shields and associated components
must comply with Article 250 of the NEC®. (National Electrical Code® and NEC® are registered
trademarks of the National Fire Protection Association Inc., Quincy, MA 02269.)

  d. Recommended grounding and bonding practices. The recommended grounding and bonding
practices are designed to: (1) accomplish adequate fault and lightning protection, (2) allow effective
TEMPEST protection to be implemented, (3) support reliable signal and data transmission without
introducing noise coupling via safety grounds, and (4) maintain the integrity of electromagnetic
interference (EMI) control and electromagnetic pulse (EMP) hardness measures. C4ISR facilities and the
interconnections between the various system elements are very complex. Existing documentation of the
as-installed grounding and bonding networks is typically not kept current. Therefore, this manual will
provide a unified set of grounding and bonding practices specifically formulated for standard C4ISR
facilities.

              1-1


---

TM 5-690

1-2. Scope

The scope of this manual is to provide general guidance for design, construction, modification, inspection,
and acceptance testing of the grounding and bonding subsystems for building protection, electrical power
ground fault protection, lightning protection, and signal ground protection for both new and existing
C4ISR facilities. The procedures presented in this manual are basic. Detailed information and specific
instructions for each particular project should be observed.

1-3. Objectives

The objective to this manual is to define the state of the art and most commonly accepted practices for an
integrated set of grounding and bonding practices for design and installation that is applicable to both new
and existing C4ISR facilities.

1-4. References

Appendix A contains a complete listing of references used in this manual. Prescribed forms are also listed
in appendix A, page A-4.

1-5. Overview of the inspection program

The inspection program is divided into two groups of forms. The first group contains Department of the
Army (DA) forms for guidance to the electrical inspector in the inspection of new C4ISR facilities and is
found in chapter 3. The second group pertains to existing C4ISR facilities and is found in chapter 6.

  a. New facilities. Figure 3-5 illustrates how the information for DA Form 7452-R (Earth Ground
Electrode Subsystem Checklist for New Facilities) is recorded by electrical inspectors checking the earth
ground electrode subsystem. Figure 3-12 illustrates a sample of DA Form 7452-1-R (Ground Fault
Protection Subsystem Checklist for New Facilities) as does figure 3-31 for DA Form 7452-1-R
(Lightening Protection Grounding Subsystem Checklist for New facilities) and figure 3-38 for DA Form
7452-2-R (Signal Ground Reference Subsystem Checklist for New Facilities). These four may be found
at the end of the manual as reproducible forms.

  b. Existing facilities. Typically, existing C4ISR facilities have been built to a variety of building codes
that either directly dictated specific grounding and bonding practices or indirectly restricted what could be
done. Consequently, the practices may vary or be incomplete with respect to other environmental
grounding and bonding practices. Major modifications to the grounding system may need to be done in
phases or may need to wait until a major equipment upgrade is being performed so that the new
grounding measures can be implemented as a part of the equipment changeover. Figure 6-1 illustrates a
sample filled-out form for use by electrical inspectors in completing the DA Form 7452-4-R (Earth
Electrode Subsystem Checklist for Existing Facilities). Figure 6-2 illustrates a sample of DA Form
7452-5-R (Grounding and Bonding Connection Checklist for Existing Facilities) as does figure 6-3 for
DA Form 7452-6-R (Lightning Protection Grounding Subsystem Checklist for Existing Facilities) and
figure 6-4 for DA Form 7452-7-R (Ground Fault Protection Subsystem Checklist for Existing Facilities).
Figure 6-5 illustrates a sample DA Form 7452-8-R (Signal Ground Reference Subsystem Checklist for
Existing Facilities) and figure 6-6 is an illustration for DA Form 7452-9-R (Shielding Subsystem
Checklist for Existing Facilities). These six may be found at the end of the manual as reproducible forms.

1-2


---

                          TM 5-690

              CHAPTER 2

   FACILITY ELEMENTS AND
PROTECTION REQUIREMENTS

2-1. Generic C4ISR facility elements

To support its mission of gathering, processing, and transmitting information, the Command, Control,
Communications, Computer, Intelligence, Surveillance, and Reconnaissance (C4ISR) facility contains as
a minimum ten distinguishable elements. These are the structure or housing; electrical power generation
and distribution [both alternating current (ac) and direct current (dc)]; non-electrical utilities; heating,
ventilation, and air-conditioning (HVAC); an earth electrode; lightning protection; communications
systems; computer and data processing systems; control and security systems; and personnel support
systems.

  a. Requirements. In general, C4ISR facility elements must conform to the requirements commonly
encountered in commercial construction. However, because of their unique mission, the C4ISR facility
elements must also accommodate several specialized requirements not found in commercial buildings or
in military administration and support buildings. These specialized requirements impose restrictions on
the configuration and installation of grounding networks and on bonding practices that are not common in
routine construction. Fixed land-based C4ISR facilities range from small structures performing dedicated
missions with few pieces of equipment to large complexes performing varied jobs involving many
different kinds of signal and data processing equipment.

  b. Facility characteristics. Regardless of the specific mission, land-based C4ISR facilities have certain
characteristics that make them unique relative to administrative and support facilities. For example, in
addition to commercial power, they commonly contain extensive on-site power generation capabilities for
both emergency backup and power conditioning. Effective protection against electrical faults within this
combined power system must be established. Also, because much of the information processed by the
facilities is classified, TEMPEST measures must be taken to protect against unauthorized interception. In
many locations, lightning presents a serious threat of damage to the sensitive equipment and protection
must be provided. Hardness against disruption and damage from electromagnetic pulses (EMP) produced
by nuclear blasts is also required in many facilities. Further, because of the amount of electronic data
processing, transmission, and reception equipment in the facilities, there are many opportunities for
electromagnetic interference (EMI) to occur. Integral to reliable operation of the C4ISR facility in this
electromagnetic (EM) "environment" is the establishment of electrical fault protection networks and
lightning discharge paths, the installation of interference control and surge suppression devices, and the
implementation of EM shields between sensitive receptors and troublesome EM sources. Grounding and
bonding are essential elements of these protective measures.

2-2. Element descriptions

Following are the descriptions of some common elements found in commercial and administrative
facilities as well as in C4ISR facilities. For example, all facilities have structural, utility, HVAC, and
personnel support elements. Other facilities may contain a number of the remaining elements.

  a. Structure. The structure provides physical support, security, and weather protection for equipment
and personnel. The structure is an element common to all facilities, yet it is the most varied. The size,
configuration, material, and construction are rarely the same in any two C4ISR facilities.

                          2-1


---

TM 5-690

     (1) Wood, stone, glass, or concrete, which are essentially transparent to EM energy, provide little
shielding to EMI and EMP threats.

     (2) Structures containing steel reinforcing bars or steel superstructures offer some degree of EM
protection. Other structures that have walls containing wire mesh, corrugated metal panels, aluminum
siding, or solid metal foils or sheets offer still more protection against the transmission of EM energy into
or out of the facility. Generally, as the metal content of the structure increases, so does the available EM
protection. However, this protection depends heavily upon the electrical continuity (bonding) and
topology of the structure. For example, structures which are completely enclosed by well-bonded steel
sheets or plates with adequately treated apertures may provide over 100 decibels (dB) of protection from a
few kilohertz to several gigahertz. On the other hand, open metallic construction may actually enhance
coupling at frequencies where the members exhibit resonant lengths.

     (3) Where TEMPEST or EMP protection is required, the structure of the C4ISR facility typically
incorporates continuously bonded metal sheets in exterior walls or around rooms or clusters of rooms to
provide a zonal barrier to prevent disruptive or compromising coupling of EM energy between internal
equipment and the external environment. To maintain the shielding integrity of these EM barriers, all
seams must be made electrically tight and all penetrations must be constructed and maintained to prevent
unintended coupling of energy through the barrier. These penetrations include those required for
personnel access, HVAC support, and signal and power transmission.

     (4) For underground facilities, the housing typically consists of large interconnected metal rooms.
The rock and earth overburden provides some degree of attenuation to EM energy; however, for complete
EMP and TEMPEST protection, the added metal enclosures are necessary.

     (5) The C4ISR facilities associated with the generation and transmission of high power radio
frequency (RF) signals (e.g., long range radar installations or those providing high satellite linkages)
commonly incorporate continuous RF shielding to control EMI to internal equipment. Similar
requirements also exist in those facilities near commercial broadcast facilities or other RF-generating
sources.

     (6) Steel structural members offer many parallel conducting paths between various points within the
facility and between these points and earth. These structural support members are frequently in direct
contact with soil and can provide a low impedance path to earth. Because of the large cross-sectional
areas of steel superstructural members, the net impedance between points is frequently less than that
provided by lightning down conductors and electrical grounding conductors. For this reason,
crossbonding between lightning down conductors and structural members is required to control flashover.

     (7) Throughout the typical existing C4ISR facility, structural members are in frequent electrical
contact with other facility elements either through intentional grounding or inadvertent grounding as a
result of normal construction and installation practices. In general, structural members do not provide
either adequate EM shielding or reliable power safety grounding. On the other hand, with proper bonding
of structural members and with proper control of stray power return currents, the structure can be used to
effectively augment grounding networks within the facility.

     (8) The particular grounding and bonding requirements and constraints imposed on C4ISR
structures are summarized in table 2-1.

  b. Electric power generation and distribution. The power system is a network of electrical equipment,
conductors, and distribution panels located throughout the C4ISR facility. The purposes of this network
are to:

2-2


---

                                                                                                  TM 5-690

                        Table 2-1. Grounding and bonding principles for structures

Electrical Safety       Lightning                EMC                       EMP                    Signal Security

The structure cannot    All exterior metal       To provide the lowest     All structural joints  No untreated
be substituted for the  walls must be bonded     impedance facility        should be              grounding conductors
required equipment      to lightning down        ground system, all        electrically well      may penetrate or cross
grounding conductor,    conductors.              structural joints should  bonded.                the structural
i.e., “green wire.”                              be electrically well                             boundary. External
                        No lightning             bonded.                   No untreated           grounding conductors
Wherever possible and   protection subsystem                               grounding              must be bonded to the
convenient, the         conductors need                                    conductors may         outside of the
structure should be     penetrate the                                      penetrate or cross     structure. Internal
frequently              structural boundary                                the structural         grounding conductors
interconnected with     of the facility. Bonds                             boundary. External     must be bonded to the
the fault protection    for the protection                                 grounding              interior surface of the
subsystem.              against lightning                                  conductors must be     structure or enclosure.
                        flashover must be                                  bonded to the
The structure should    connected to opposite                              outside of the
be frequently           sides of the structural                            structure. Internal
interconnected with     boundary.                                          grounding
the earth electrode                                                        conductors must be
subsystem.              Large exterior metal                               bonded to the
                        objects that are                                   interior surface of
                        within 2 meters of                                 the structure or
                        down conductors                                    enclosure.
                        must be cross-bonded
                        to the nearest down
                        conductor.

                        Large interior metal
                        objects and shielded
                        rooms positioned
                        within 2 meters of
                        exterior steel
                        structural members
                        must be bonded to
                        these members.

                        Resistance of bonds
                        should not exceed
                        one milliohm.

       (1) Transform, as necessary, and route commercially supplied power into the facility.
       (2) Generate appropriate on-line electrical power as required, especially during the absence of
commercial power.
       (3) Switch between these two sources of electrical power.
       (4) Condition the electrical power for the critical loads being served.
       (5) Provide uninterrupted electrical power for critical equipment in all situations.
       (6) Distribute appropriate electrical power to the various equipment loads throughout the facility.
       (7) The overall facility power system includes both ac and dc subsystems. A one-line diagram of a
generic ac system is illustrated by figure 2-1. It consists of a substation/transformer bank, a number of

                                                                                                                                         2-3


---

TM 5-690

engine/generators (E/Gs), various switchgear, intermediate transformers, an uninterruptible power supply
(UPS), transfer switches, and a network of conductors, disconnects, and distribution panels.

COMMERCIAL                                                                                                                    COMMERCIAL
POWER #1                                                                                                                      POWER #2

                                                                                                               SPARE FEEDERS

                                 #1  #2                    #3  #4       #5      #6

                                                                                         BUS #1

                                                                                         BUS #2

                                                           TYPICAL METAL OXIDE
                                                           SURGE ARRESTER

                                  TYPICAL TECHNICAL LOADS

PCE                                                    NO          PCE              PCE                         NO  TYPICAL
                          PCE                                                                                       NONESSENTIAL LOADS
                                                                                                 ESSENTIAL STATION
                                                                                                 SERVICE LOAD

                          UPS #1                               UPS #2                            GENERAL NOTE

                                                                                                 LOADS ARE TO BE SUPPLIED FROM UPS MODULES
                                                                                                 WITH POWER CAPACITY AND VOLTAGE RATINGS
                                                                                                 EQUAL TO THOSE OF THE CRITICAL EQUIPMENT.
                                                                                                 THE INPUT AND OUPUT FREQUENCIES OF THE UPS
                                                                                                 MODULES MUST BE THE SAME.

              NO                     BUS TIE                                             NO
                                     CONTROL                                                               NO
NO
                     MBB                                                            MBB

                          MCB-1                  NO                MCB-2

                                        TYPICAL
                                     CRITICAL LOADS

                         Figure 2-1. One-line diagram of a generic ac power subsystem

     (8) The substation/transformer bank, which can range in size from a single pad-mounted transformer
to a complete power substation, converts the incoming commercial power to the proper voltages for use at
the facility. Commercial power is a primary ac power source for C4ISR installations wherever such
sources are available and where operational and economic considerations permit. Independent, redundant
sources are desirable. Thus, on-site electrical generators driven by diesel engines are commonly used to
produce ac power as needed. The main facility switchgear is used to select one of the commercial power
feeds or the generators as the primary source of facility power, to synchronize these sources, and to
switch between them. In addition to having redundant feeds, this switchgear is configured with multiple
buses so as to provide redundant paths to technical operational loads.

2-4


---

                                                                                                                                TM 5-690

      (9) C4ISR facilities contain four types of electrical/electronic equipment to which power must be
supplied: critical technical, essential technical, non-essential loads, and emergency loads. Critical
technical loads are those which must remain operational (100 percent continuity) in order for the facility
to carry out its assigned mission. Essential technical loads are those which are supportive of the assigned
mission but are not required to have 100 percent continuity. Non-essential loads indirectly support the
C4ISR mission. Emergency loads consist of life-safety equipment such as emergency lights, exit lights,
and fire alarm and suppression systems.

      (10) The configuration of the ac power system following the main switchgear depends on the type
of facility load being served. The critical and essential technical equipment loads are supplied through
multiple bus switchgear and double feeds to provide redundant distribution paths. The non-essential
loads are supplied through a single feed and single bus switchgear either from one bus in the main facility
switchgear or directly from commercial power. In addition to the redundant distribution paths, the critical
technical equipment loads are supplied through a UPS. The UPS provides continuous, high quality,
uninterruptible power in all operational situations to the critical technical equipment within the facility. It
consists of a rectifier bank driving a group of inverters, which generate the required ac power.
Uninterruptible ac power results from paralleling the dc output of the rectifiers with a battery bank
capable of carrying the critical facility load until the engine/generators are started, brought up to speed,
and switched on-line. In addition, all incoming commercial and engine/generator power to critical loads
is conditioned by the rectifier/battery/inverter process in normal operational situations.

      (11) The output of the UPS is routed via multiple buses and redundant feeds through breakers in the
critical bus switchgear to branch distribution panels. These branch panels are located throughout the
facility at critical equipment locations. The critical power is then routed through circuit breakers in each
of these panels to specific pieces of equipment.

      (12) At appropriate locations in the power distribution paths, transformers and intermediate
switchgear (indoor unit substations) and transfer switches may be employed. The transformers convert
the ac power to the appropriate voltages and configuration (i.e., three-phase, delta or wye, or single-
phase) for the loads being served. The transfer switches, which are typically automatic, switch between
two sources of power to provide continuous operation in the event of failure of one of the sources.

      (13) A typical configuration for the ac power system showing the neutral and grounding conductor
is illustrated in figure 2-2. (To simplify this figure, the redundant buses in the switchgear and the
redundant feeds are not shown.) Typically, every transformer between the ac power source and the load
is a delta-primary/wye-secondary configuration, thus establishing a separately derived source at each
transformer. Furthermore, the neutral is usually not run between intermediate switchgear. For example,
although the neutral is usually present in the intermediate switchgear, it is usually not continued to the
next successive transformer/switchgear assembly. It commonly begins at the last transformer prior to a
single-phase load and is then routed with the phase conductors through the remaining switchgear and
distribution panels to the loads.

      (14) The dc power system usually consists of multiple battery racks located at various places in the
facility and includes dc switchgear, battery chargers, and distribution conductors. In some C4ISR
facilities, individual battery racks are located near the dc loads they serve; in others, a large battery rack
called the station battery serves the function of, and replaces, several individual battery racks. The dc
power system supplies appropriate power for switchgear circuit breaker controls, protective and auxiliary
relays, and pilot lights; for other instrumentation and control signaling and switching; and for the UPS
equipment. Since the major functions of the dc loads are associated with generation, monitoring, and
control of the ac power, a significant portion of the dc power system is located near the ac power
switchgear.

                                                                                                                                         2-5


---

TM 5-690

COMMERCIAL  SUBSTATION                              MAIN                    ELECTRICAL SWITCHGEAR                                                      DISTRIBUTION                                     TO NONCRITICAL LOADS
  POWER                                 3 PH  SWITCHGEAR                                                                     3 PH                             PANEL
                                           G                                                                                  G                                                   PH
                                                                      3 PH                                                                                                         N
                                        3 PH                                                                                 3 PH                                                  G
                                           G                             G                                                    G
                                                                                                                                                                                  PH
                                                                      3 PH                                                                                                         N
                                                                         G                                                                                                         G

E/G'S                                                                                                                                          LEGEND:
                                                                                                                                                           DIRECT CONNECTION TO EARTH
                   UPS
            SWITCHGEAR                                                                                                                                     CONNECTION TO FACILITY
                                                                                                                                                           GROUND SYSTEM
                        3 PH             E    CRITICAL BUS                                                                                     NOTE: THE MULTIPLE BUSES IN THE       TO CRITICAL LOADS
                          G   UPS               SWITCHGEAR                                                                                     SWITCHGEAR AND THE REDUNDANT
                                                                          3 PH                                                                 FEEDS, UPS'S, AND DISTRIBUTION
                        3 PH                                                                                                                   PATHS ARE NOT SHOWN FOR
                          G                                                  G                                                                 SIMPLICITY.

                                                                          3 PH                                                     DISTRIBUTION
                                                                             G                                                            PANEL
                                                                                                                                                             PH
                                                                                                                                                              N
                                                                                                                                                              G

                                                                                                                                                             PH
                                                                                                                                                              N
                                                                                                                                                              G

                               Figure 2-2. Typical ac power subsystem configuration

      (15) In many facilities, there will be power conditioning centers dedicated to supplying highly
filtered and protected power to data processing and other equipment demonstrated to be highly
susceptible to power line transients and ground system noise. These centers commonly contain filters,
terminal protection devices (TPDs), isolation transformers, voltage regulators, and overload protection.
Depending upon the criticality of the equipment being served, a secondary UPS may also be provided by
the power-conditioning center.

       (16) The particular grounding and bonding requirements and constraints imposed on C4ISR
electric power generation and distribution are summarized in table 2-2.

  c. Non-electric utilities. Non-electric utilities are the non-electrical piping used for gas, sewer, and
water (both for fire fighting and normal use). In addition to these normal services, the facility will likely
contain other non-electric utilities such as fire suppression, chilled water, compressed air, etc. The utility
pipes providing these services are typically constructed of steel, cast iron, copper, or plastic. Some buried
sewer lines may be fired clay. In older facilities, the lines enter the facility at different points and then
branch out to form an interwoven tree network of pipes. Metal pipes of different non-electric utility
systems are frequently mechanically bonded together to become electrically continuous along their path.
For example, gas and water pipes become interconnected at hot water heaters; water and sewer pipes
interconnect at sinks and appliances; all may interconnect with structural elements via mounting brackets.
Through chilled water and other coolant systems, the utility piping network can become electrically
interconnected with electronic equipment. The internal piping is commonly joined electrically to the
external system of pipes. This electrically joined network may provide coupling paths for unwanted

2-6


---

                                                                                                        TM 5-690

        Table 2-2. Grounding and bonding principles for power distribution

Safety                   Lightning                EMC                       EMP                         Signal Security

Ground the neutral of    Lightning ground must    The neutral should not    All power conductors        All power
three-phase wye and      be interconnected with   be grounded at any        entering or leaving         conductors
single-phase supply      power ground.            point on the load side    protected regions of the    (including neutrals)
lines at the service                              of the disconnect,        facility must be            entering or leaving
disconnect for the       Surge suppressors        other than as required    equipped with EMP           Controlled Access
facility and/or          installed on             on the secondaries of     power line filters and      Areas (CAA) must
individual buildings.    transformers shall be    delta-wye stepdown        TIDs. Grounding             be equipped with
                         grounded to the          transformers or           conductors must be          EMI power line
Electrical supporting    transformer housings     isolation transformers.   bonded to the structure,    filters. Grounding
structures should be     and their earth          (See exception for        EM shield, or EMP           conductors, i.e.,
interconnected and       electrode connections    certain personnel         zonal boundary at the       green wires, must be
connected with facility  with minimum length      support appliances.       point of penetration of     bonded to outside
ground.                  conductors               For this exception,       the power conductors.       and the inside
                         Suppressors installed    however, it is essential                              surfaces of EM
Neutrals of engine       on service entrance      that the frames or        No untreated grounding      shields surrounding
generators should be     panels shall be          cabinets NOT be           conductors may              the CAA. A common
grounded through a       grounded to the          interconnected with       penetrate or cross the      grounding stud may
current limiting         common neutral-          the structure or fault    structural boundary.        be used to terminate
resistance or with a     grounding conductor      protection subsystem.)    External grounding          the external and
grounding transformer    connection with                                    conductors must be          internal grounding
to the facility ground.  minimum length           All fuse and breaker      bonded to the outside of    conductors. External
                         connections.             panels, switch boxes,     the structure. Internal     grounding
The equipment                                     junction boxes, power     grounding conductors        conductors must
grounding conductors,    TPDs installed on        outlets, electronic       must be bonded to the       terminate to the
i.e., "green wire        power and control        equipment enclosures,     interior surface of the     exterior part of
grounds," must be run    cables interfacing with  etc., MUST have no        structure or enclosure.     shielded volume.
with power conductors    HVAC elements must       inadvertent
and connected to         be grounded to the       neutral/grounding wire    Multiple entry panels
equipment frames and     enclosure of the         (white/green) reversal.   may be used; however,
housings.                protected equipment                                the aggregation of all
                         with minimum length      All power conductors,     penetrating conductors -
Resistance of bonds      conductors.              including neutrals,       power, signal, data,
should not exceed one                             entering or leaving       control lines, and utility
milliohm.                Resistance of bonds      protected regions         conductors - to a single
                         should not exceed one    should be equipped        entrance panel or vault
                         milliohm.                with EMI power line       should be a goal during
                                                  filters.                  upgrades and
                                                                            continuing
                                                                            modifications of the
                                                                            facility.

energy both between equipment internal to the facility and between internal equipment and the external
environment, if adequate measures are not taken to disrupt the coupling path. The particular grounding
and bonding requirements and constraints imposed on non-electric utilities are summarized in table 2-3.

  d. Heating, ventilating and air conditioning (HVAC). HVAC is the network of equipment that
regulates the internal physical environment of the facility. This system consists of the furnaces, air-
conditioners, heat pumps, and humidifiers that condition the air, ducts, vents, and fans that distribute the
conditioned air throughout the facility.

      (1) The HVAC ducts are routed throughout the facility and are likely to make frequent contact with
structural elements. The duct system may or may not be electrically continuous.

                                                                                                        2-7


---

TM 5-690

              Table 2-3. Grounding and bonding principles for non-electrical utilities

Power Safety               Lightning                   EMC            EMP                        Signal Security

Except for gas lines,      Buried metal pipes   All utility pipe      Utility pipes must be      All utility pipes
exterior pipes are to be   must be bonded       penetrations into     bonded to the structure    entering CAA must
bonded to the earth        together and to the  protected areas must  at the point of            be peripherally
electrode subsystem        earth electrode      be properly treated.  penetration. If possible,  bonded to the CAA
and to the structure.      subsystem.                                 peripheral bonding to a    shield or utilize
                                                                      penetration panel or       waveguide - below
Exterior gas supply                                                   through a shielded         cutoff penetrations.
lines shall be isolated                                               entrance vault is
from conductors inside                                                preferred.
the facility, if required
by local codes.                                                       All utility pipes should
                                                                      be bonded to the earth
Metallic piping                                                       electrode subsystem at
including gas lines                                                   the point of crossing the
inside the structure                                                  subsystem. Utility pipes
should be frequently                                                  should have an
interconnected with the                                               insulating section
facility ground.                                                      inserted immediately
                                                                      outside the earth
                                                                      electrode subsystem.

                                                                      All utility pipes outside
                                                                      the zone oil boundary
                                                                      should be below grade.

      (2) Some components of the HVAC system, such as cooling towers and oil tanks, are usually
outside the structure. These components can act as pickup conductors for lightning and EMP energy;
thus, penetrating conductors such as fuel, water and coolant lines, and the protective conduit of electrical
supply lines associated with external elements of the HVAC subsystem must be peripherally bonded.
Electrical conductors must have appropriate transient suppressors and filters installed.

       (3) The particular grounding and bonding requirements and constraints imposed onC4ISR HVAC
systems are summarized in table 2-4.

  e. Earth electrode. The earth electrode subsystem is a network of conductors buried in soil to establish
an electrical connection between the facility and the body of the earth. This connection provides the
primary path to ground for the facility and its contents:

       (1) The network provides a preferential path to the earth for lightning discharge currents in a
manner that protects the structure, its occupants, and the equipment inside.

       (2) The network ensures that any faults in the facility substation or transformer-breaker system
have a sufficiently low impedance return path between the fault and the generating source to reliably
cause breakers (in the substation or in generators) to trip and clear the fault and to minimize voltage
hazards until the fault is cleared.

       (3) The network restricts the step-and-touch potential in areas accessible to personnel to levels
below the lethal threshold even under lightning discharge and power fault conditions.

2-8


---

                                                                                                 TM 5-690

Table 2-4. Grounding and bonding principles for heating, ventilation, and air-conditioning

Power Safety        Lightning                    EMC                       EMP                   Signal Security

Green wire grounds  Any external HVAC            Isolation Sections must   Filters and TPDs      Isolation sections
must be run with    elements exposed to direct   be inserted in air ducts  installed for noise   must be inserted in
power conductors    lightning strokes must have  immediately prior to      suppression and       air ducts
and connected to    air terminals mounted        shield penetrations.      transient protection  immediately prior to
equipment frames    thereon and be                                         must be grounded to   shield penetrations.
and housings        interconnected with roof     Filters and TPDs          their mounting
                    and down conductors.         installed for noise       enclosures (which
                                                 suppression and           presumably is
                    Any other external HVAC      transient protection      mounted directly on
                    equipment located within 2   must be grounded to       the housing of the
                    m of roof and down           their mounting            HVAC equipment)
                    conductors should be         enclosures (which         with direct
                    interconnected with the      presumably is mounted     Connections or with
                    nearest down conductor.      directly on the housing   minimum length
                                                 of the HVAC               conductors.
                    TPDs installed on power      equipment) with direct
                    and control cables           connections or with
                    interfacing with HVAC        minimum length
                    elements must be grounded    conductors.
                    to the enclosure of the
                    protected equipment with
                    minimum length
                    conductors.

       (4) The earth electrode subsystem commonly consists of both intentional and incidental metal
conductors. Intentional conductors include ground rods (plus an interconnecting cable), grids, horizontal
radials, or some combination of these. These conductors are generally placed around the perimeter of the
structure, underneath the equipment as in the case of generators and high voltage transformers, or at
penetration points of long external conductors. Since the C4ISR facility includes auxiliary generators
and, typically, a commercial substation as integral elements of the power system, substation ground mats
are likely to be a part of the facility earth electrode subsystem either through integral design or by
extension through normal interconnections. Further, where auxiliary towers are a part of the complex,
their grounds are also part of the earth electrode subsystem of the facility.

       (5) Incidental earth electrode conductors are those buried objects that are directly or indirectly
interconnected with the intentional earth electrode subsystem. Examples of incidental members of the
earth electrode subsystem are underground storage tanks connecting to the facility via metal pipes,
structural steel pilings, buried metal utility pipes (usually the cold water main), well casings, and, for
underground facilities, conduit for power conductors and signal cables which penetrate the overburden.

       (6) The particular grounding and bonding requirements and constraints imposed on the C4ISR
earth electrode subsystem are summarized in table 2-5.

  f. Lightning protection. A lightning protection subsystem is frequently installed to protect the structure,
personnel, and equipment of the C4ISR facility from damage due to lightning discharges.

       (1) The subsystem is a network of bonded air terminals and down conductors distributed over the
exterior of the structure and connected to the earth electrode subsystem. The lightning protection
subsystem also includes properly bonded support towers, to include their interconnections with the earth

                                                                                                 2-9


---

TM 5-690

          Table 2-5. Grounding and bonding principles for earth electrode subsystem

Power Safety               Lightning                       EMC                  EMP                    Signal Security

A low resistance           The earth electrode             No untreated         All metal conductors   No untreated
connection to earth is     subsystem shall be              conductors may       shall be peripherally  conductors may
required, i.e., 10 ohms    configured as a ground rod      penetrate protected  bonded to the earth    penetrate protected
or less.                   and counterpoise ring           areas.               electrode subsystem    areas.
                           around the facility.                                 at the point of
Ground mats or grids                                                            crossing or shall
shall be installed as      Ground connections must be                           have insulating
required to limit step-    0.6 m outside the facility                           sections installed.
and-touch potentials in    wall and must extend a
generating plants,         minimum of 3 m into soil.                            No untreated
substations, switching                                                          conductors may
stations, and power        Multiple paths between air                           penetrate protected
conditioning centers.      terminals and the earth                              areas.
                           electrode subsystem must be
Except for gas lines, all  installed. Except for gas
nearby buried metal        lines, all nearby buried
objects shall be           metal objects shall be
interconnected to the      interconnected to the earth
earth electrode            electrode subsystem. Gas
subsystem. Local codes     lines shall have a minimum
may dictate that exterior  1 m insulating section
gas supply lines be        installed outside at the point
isolated from              of penetration inside the
conductors inside the      facility and before crossing
facility.                  the earth electrode
                           subsystem conductors.

electrode subsystem. Primary and secondary surge arresters on power lines, along with terminal
protection devices on power and signal conductors located at penetration points into EM-protected areas,
also are integral parts of the lightning protection subsystem.

     (2) Air terminals are vertically mounted conductors placed on roof edges, ridges, corners, and any
structural projection likely to receive a lightning stroke. Their purpose is to divert to themselves the
lightning energy, which would otherwise enter the structure. Air terminals are interconnected with roof
conductors routed along the roof edges and ridges.

      (3) Lightning down conductors provide preferential paths for the lightning energy to follow from
the air terminals and roof conductors to earth. Since analytical tools and measurement methods are not
available for determining in advance the path of least resistance for a lightning discharge, down
conductors are routed to follow the straightest and shortest path from the air terminals to earth. The down
conductors must terminate to the lowest available impedance contact with earth, which should be the
earth electrode subsystem for the facility.

      (4) Lightning surge arresters are placed on the primary and secondary terminals of transformers
supplying commercial power to the facility. These surge arresters are typically the robust spark gap
variety used by the power utilities to protect against lightning strokes to the transmission network.
Additional arresters are placed at penetration points into the facility and at subsequent step-down
transformers, switchgear, the UPS, and other vulnerable equipment locations. These added arresters
include both lightning surge suppressors and the fast-acting semi-conductor TPDs necessary for EMI and
EMP transient suppression. Complete lightning and EMP protection also require that TPDs be placed on
all exposed signal and control conductors at penetration points into EM-protected volumes.

2-10


---

                                                                                                                                TM 5-690

     (5) The particular grounding and bonding requirements and constraints imposed on the C4ISR
lightning protection subsystem are summarized in Table 2-6.

                    Table 2-6. Grounding and bonding principles for lightning protection

Power Safety        Lightning                        EMC                  EMP                        Signal Security

Any exterior metal  For above ground facilities, an  No untreated         No untreated               No untreated
objects within 2 m  air terminal, roof conductor,    conductors may       conductors may             conductors penetrate
of lightning down   and down conductor net- work     penetrate protected  penetrate protected        protected areas.
conductors must be  is required.                     areas.               areas.
bonded to the
down conductors.    At least two paths from each                          No lightning protection
                    air terminal to earth must                            subsystem conductors
The lightning       exist.                                                may penetrate the zonal
protection sub-                                                           boundary of the facility.
system's earth      Locate air terminals and down                         Bonds for the protection
connection must be  conductors so as to assure that                       against lightning
common with the     all building extensions are                           flashover must be
facility's earth    effectively protected.                                connected to opposite
electrode sub-                                                            sides of the zonal
system.             Each down conductor shall                             boundary.
                    terminate to a ground rod of
                    the earth electrode subsystem.                        The ground lugs of
                                                                          terminal protection
                    Lightning down conductors                             devices shall be bonded
                    should be bonded to structural                        to the distribution
                    steel members at the top of the                       frame, junction box,
                    structure and near ground                             penetration panel, or
                    level.                                                filter box where
                                                                          mounted. The frame,
                    On towers, lightning down                             box, or panel must be
                    conductors should be                                  grounded directly to the
                    periodically bonded to the                            nearest point on the
                    tower structure along their                           structure or on the
                    downward paths.                                       EMP/EMI shield and,
                                                                          by extension, to the
                    Resistance of bonds should                            lightning down
                    not exceed one milliohm.                              conductor and earth
                                                                          electrode subsystem.

  g. Communications systems. The communications subsystem is the network of electronic equipment,
interfaces, and antennas whose elements are located both in, and around, the C4ISR facility. The purpose
of the communications subsystem is to transfer information from one point to another. The information
transfer may take place between points located within the facility or between different facilities.

      (1) The electronic equipment making up the communications subsystem frequently include RF
receivers and transmitters; audio, baseband, and RF amplifiers, data terminals and displays; telephones;
modems; multiplexers; frequency converters; encryption devices; and other communication-electronic (C-
E) equipment. Within the facility, the interfaces between equipment are generally hard-wired signal lines
or waveguides. Signal penetrations into the facility include coaxial and waveguide for RF signals and,
shielded, multiconductor cables for telephone, data, and control signals. Fiber optic penetrations are
being increasingly used for EMP-protected facilities. Between facilities, the information transfer is
usually via land lines or RF transmission. The RF antennas are generally located on or near the facility.

                                                                                                                                       2-11


---

TM 5-690

      (2) The various communication sub-elements include telephone, radio, local area data transfer, and
high-speed data. The telephone sub-element provides internal communications via hard-wired interfaces
and intersite communications via land lines or microwave links. As a minimum, the telephone subsystem
consists of the telephone instrument sets, cabling, and distribution frames. Larger facilities generally also
have a private branch exchange (PBX), Centrex, and/or automatic switching racks, intercom apparatus,
and a telephone power plant.

      (3) The radio subsystem converts audio and baseband signals to a RF signal, radiates the RF signal
to the receiving point, and then converts the RF signal back to the appropriate audio or baseband signal.
Since it has both low frequency and RF equipment interconnected within the same network, the operating
frequencies of the radio subsystem cover an extremely wide range.

      (4) The low frequency signal interfaces to and from the RF equipment may be either single-ended or
balanced, twisted-pair lines. Depending on the frequency of operation, the RF signal interfaces may be
either coaxial lines or waveguides. These various types of interfaces are included within the radio
subsystem.

      (5) Another subsystem is equipment and cables associated with high-speed data transmission. This
subsystem is used to transfer high-speed data signals between data processing equipment. The
transmission paths employ both shielded twisted pair and coaxial cables.

      (6) The equipment of the various communication elements is likely to be distributed throughout the
facility and grounded at multiple points. The equipment cases, racks, and frames are grounded to the ac
power ground, to raceways and conduit, and to structural members at numerous locations within the
facility. In many facilities, a single point configuration for the signal reference ground is said to be
implemented for telephone circuits and for data processing circuits. Actually, however, a single point
ground configuration does not exist because of internal grounding of signal references to cabinets and
enclosures with subsequent interconnections to power conduits and raceways and because of the use of
unbalanced interfaces between the various pieces of equipment. Consequently, the effective signal
reference ground for the communication subsystem in the typical C4ISR facility is a multi-point grounded
system with numerous interconnections between signal references, equipment enclosures, raceways,
conduit, and structural members.

       (7) The particular grounding and bonding requirements and constraints imposed on C4ISR
communications systems are summarized in table 2-7.

  h. Computer and data processing systems. A distinguishing feature of the C4ISR facility is the
presence of many digital processors ranging from microcomputers performing dedicated equipment and
instrument control to large interconnected mainframes providing complex analyses, signal processing,
and image displays. These processors typically interface with numerous input/output (I/O) devices
including keyboards, monitors, disk drives, tape drives, remote terminals, data acquisition and control
equipment, and other processors.

      (1) The data processing subsystems are configured in various ways. These various configurations
result in different grounding connections being established. For example, stand-alone desktop computers
obtain power from single ac outlets and thus establish only one electrical safety ground connection. Other
small computing systems may be configured so that the processor and I/O devices share the same outlet,
or perhaps the same branch circuit. In this configuration, the ground connection is effectively a single
connection although more than one physical tie is made. Where I/O and other peripherals are separated
by large distances from the processor, multiple connections to the facility ground network result.

2-12


---

                                                                                                                                TM 5-690

      (2) Larger computing subsystems are generally characterized by having the processor in one place
and the peripherals distributed throughout the facility. In this configuration, the peripherals are supplied
from different ac outlets, off different branch circuits, or perhaps from different phases of the line. In

                       Table 2-7. Grounding and bonding principles for communications

Power Safety           Lightning                EMC                            EMP                            Signal Security

Green wire grounding   The ground terminal of   A signal reference             A signal reference             A signal reference
conductor must be run  surge arresters and      subsystem shall be             subsystem shall be             subsystem shall be
with power conductors  TPDs shall be bonded     established. This ground       established. This ground       established inside the
and connected to       to the mounting          reference subsystem will       reference subsystem will       Controlled Access
equipment cabinets.    enclosure with           consist of multiple            consist of multiple            Area (CAA). This
                       minimum length           interconnections between       interconnections between       ground reference
                       conductors. The          equipment cabinets, frames,    equipment cabinets, frames,    subsystem will
                       enclosure shall be       and racks; between conduit,    and racks; between conduit,    consist of multiple
                       mounted directly to the  raceway, and wireway;          raceway and wireway;           interconnections
                       tower structure or will  between these                  between these                  between equipment
                       be bonded with a         communication subsystem        communication subsystem        cabinets, frames and
                       minimum length, flat     members and structures; and    members and structure; and     racks; between
                       conductor.               shall incorporate raised       shall incorporate raised       conduit, raceway and
                                                floors into the reference      floors into the reference      wireway; between
                                                subsystem.                     subsystem.                     these communication
                                                                                                              subsystem members
                                                Where space and                Where space and                and structure; and
                                                accessibility exist, a wire    accessibility exist, a wire    shall incorporate
                                                mesh grid may be installed     mesh grid may be installed     raised floors into the
                                                at floor level or overhead to  at floor level or overhead to  reference subsystem.
                                                supplement the above           supplement the above
                                                cabling network. Equipment     cabling network. Equipment     Terminate shields of
                                                enclosures and racks should    enclosures and racks should    all cables in the CAA
                                                be bonded to this wire mesh.   be bonded to this wire mesh.   to the signal
                                                The mesh should be bonded      The mesh should be bonded      reference subsystem
                                                to structure at each point     to structure at each point     within the CAAs.
                                                where structural members       where structural are
                                                are accessible.                accessible.

                                                Both ends of shielded cable    Filters and TPDs installed
                                                shall be terminated to case    for noise suppression and
                                                or enclosure. Continuous       transient protection must be
                                                peripheral bonding of the      directly grounded to the
                                                shield is best.                enclosures of the protected
                                                                               equipment. TPDs installed
                                                Filters and TPDs installed     in distribution frames and
                                                for noise suppression and      junction boxes must be
                                                transient protection must be   terminated directly to the
                                                directly grounded to the       ground bus or to the
                                                enclosures of the protected    mounting enclosure. The
                                                equipment. TPDs installed      ground bus and the
                                                in distribution frames and     mounting enclosure must be
                                                junction boxes must be         bonded to the fault
                                                terminated directly to the     protection subsystem with
                                                ground bus or to the           minimum length conductors.
                                                mounting enclosure. The
                                                ground bus and the             Both ends of shielded cable
                                                mounting enclosure must be     shall be terminated to case
                                                bonded to the fault            or enclosure. Continuous
                                                protection subsystem with      peripheral bonding of the
                                                minimum length                 shield shall be used.
                                                conductors.

                                                                                                              2-13


---

TM 5-690

some installations, remote terminals may even be in separate buildings and supplied from different
transformer banks. Each remote device must have a safety ground at its location. Noise in
interconnecting paths can be encountered from stray currents in the ground reference network. The most
practical approach to solving these noise problems is not to strive to implement a "single point" ground
connection for the main processor but rather to minimize the stray current in the ground reference system
and use effective common mode suppression techniques and devices in data paths.

       (3) The particular grounding and bonding requirements and constraints imposed on C4ISR
computer and data processing systems are summarized in table 2-8.

  i. Control and security systems. Typical C4ISR facilities have many control and security devices
which gather information and then automatically respond to a given situation by alerting personnel or
engaging equipment to correct it. These subsystems range in nature from pneumatic and mechanical to
electrical, electronic analog or digital, or a combination of these. Numerous current sensors, intrusion
detectors, trip relays, sound detectors, remote control locks, remote control doors, and alarms are typically
included in the systems.

       (1) Many of the control subsystems are self-contained and independent, as, for example, intrusion
detectors that sound alarms. Often, however, they interact with other facility elements. For example, the
HVAC subsystem contains an integral network of temperature and humidity sensors along with actuators
that control the interior air. For fire protection, smoke detectors, sound alarms, and temperature sensors
start purging of the affected area. The power subsystem incorporates electronically operated circuit
breakers to close or open circuits and to keep particular breaker combinations from being opened or
closed simultaneously.

       (2) Control subsystems range from being entirely automated to completely manual. One example
of automated controls is that which switches over from commercial power to engine/generator power
upon loss of commercial power. The control elements can automatically start the engine/generators, bring
them up to proper speed and voltage, and switch the appropriate breakers. On the other hand, the operator
has the option of performing each of these functions separately using selected devices of the control
system to monitor the progress.

       (3) In terms of grounding, the large diversity of the control subsystem results in various grounding
paths being established. Small control devices are typically grounded through the ac safety ground
provided via the power outlet. The more automated and complex subsystems, however, resemble a
computer net or a communication subsystem. For example, sensors communicate information from their
locations (which may be very remote) to a central location. In many cases, processors monitor the
sensors, determine if an abnormal situation exists, and provide appropriate commands to control the
necessary equipment. The processor may be the main facility computer. In such cases, the grounding
network resembles that of both data processing and communications.

       (4) Many control sensors and actuators are outside EM-protected portions of the facility.
Particularly with automated control subsystems, these exposed portions are extremely susceptible to upset
or damage from high level EM transients such as produced by lightning and EMP. Clearly, appropriate
incorporation of shielding, terminal protection, grounding, and bonding are necessary. Specific attention
must be paid to the filtering and terminal protection of control cables penetrating the boundary of the EM-
protected volume, to effectively establishing adequate grounding paths for transient energy, and to
accomplishing electrically tight bonds around the penetrations into control devices.

2-14


---

                                                                                                  TM 5-690

Table 2-8. Grounding and bonding principles for computers and data processing

Power Safety Lightning              EMC                            EMP                            Signal Security

Green wire      The ground lugs     A signal reference             A signal reference             A signal reference
grounding       of terminal         subsystem must be              subsystem must be              subsystem must be
conductor must  protection          established. This ground       established. This ground       established. This
be run with     devices shall be    reference subsystem will       reference subsystem will       ground reference
power           bonded to the       consist of multiple            consist of multiple            subsystem will
conductors and  distribution frame  interconnections between       interconnections between       consist of multiple
connected to    or junction box     equipment cabinets, frames,    equipment cabinets, frames,    interconnections
equipment       where mounted.      and racks; between conduit,    and racks; between conduit,    between equipment
cabinets.       The distribution    raceway, and wireway;          raceway, and wireway;          cabinets, frames,
                frame or junction   between these                  between these                  and racks; between
                box must be         communication subsystem        communication subsystem        conduit, raceway,
                grounded to the     members and structure; and     members and structure; and     and wireway;
                nearest structural  shall incorporate raised       shall incorporate raised       between these
                frame member        floors into the reference      floors into the reference      communication
                and, by extension,  subsystem.                     subsystem.                     subsystem members
                to the lightning                                                                  and structure; and
                down conductor.     Where space and                Where space and                shall incorporate
                                    accessibility exist, a wire    accessibility exist, a wire    raised floors into the
                The shields of      mesh grid may be installed     mesh grid may be installed     reference
                penetrating data    at floor level or overhead to  at floor level or overhead to  subsystem.
                lines shall be      supplement the above           supplement the above
                bonded to the       cabling network.               cabling network.               Both ends of
                entrance panel, or  Equipment enclosures and       Equipment enclosures and       shielded cable shall
                to the facility     racks should be bonded to      racks should be bonded to      be terminated to
                ground with a       this wire mesh. The mesh       this wire mesh. The mesh       case or enclosure.
                minimum length      should be bonded to            should be bonded to            Continuous
                conductor.          structure at each point        structure at each point        peripheral bonding
                                    where structural members       where structural members       of the shield is best.
                Data cable shields  are accessible.                are accessible.
                shall be bonded
                to antenna tower    Both ends of shielded cable    Both ends of shielded cable
                structural          shall be terminated to case    shall be terminated to case
                members at the      or enclosure. Continuous       or enclosure. Continuous
                point of departure  peripheral bonding of the      peripheral bonding of the
                from the tower.     shield is best.                shield is best.

                                    Filters and TPDs installed     Filters and TPDs installed
                                    for noise suppression and      for noise suppression and
                                    transient protection must be   transient protection must be
                                    directly grounded to the       directly grounded to the
                                    enclosures of the protected    enclosures of the protected
                                    equipment. TPDs installed      equipment. TPDs installed
                                    in distribution frames and     in distribution frames and
                                    junction boxes must be         junction boxes must be
                                    terminated directly to the     terminated directly to the
                                    ground bus or to the           ground bus or to the
                                    mounting enclosure. The        mounting enclosure. The
                                    ground bus and the             ground bus and the
                                    mounting enclosure must        mounting enclosure must
                                    be bonded to the fault         be bonded to the fault
                                    protection subsystem with      protection subsystem with
                                    minimum length                 minimum length
                                    conductors.                    conductors.

                                                                                                                          2-15


---

TM 5-690

       (5) The particular grounding and bonding requirements and constraints imposed on C4ISR control
and security systems are summarized in table 2-9.

  j. Personnel support systems. Typically, C4ISR facilities are manned 24 hours per day. This means
that in addition to routine office equipment, food, lodging, and recreational facilities are normally
required for operating personnel on duty. This personnel support equipment includes those electrical
devices that connect directly to the power system and do not interconnect with the communication,
computer, or control system under normal operation. Devices such as office typewriters, lighting fixtures,
kitchen equipment, cleaning apparatus, and electric tools are examples of personnel support equipment.
Even non-electrical objects like carpeting, which can contribute to static charge build-up, need to be
considered.

                            Table 2-9. Grounding and bonding principles for controls

Power Safety         Lightning               EMC                     EMP                      Signal Security

Green wire           The ground lugs of      Both ends of shielded   Both ends of shielded    Control circuits
grounding conductor  terminal protection     cable shall be          cable shall be           penetrating the CCA
must be run with     devices shall be        terminated to case or   terminated to case or    must be treated as
power conductors     bonded to the           enclosure.              enclosure. Continuous    BLACK1 conductors.
and connected to     distribution frame or   Continuous              peripheral bonding of    They must be enclosed
equipment cabinets.  junction box where      peripheral bonding of   the shield is best.      in continuous conduit,
                     mounted. The            the shield is best.                              which are peripherally
                     distribution frame or                           Filters and TPDs         bonded at each end
                     junction box must be    Filters and TPDs        installed for noise      They must be powered
                     grounded to the         installed for noise     suppression and          from BLACK power.
                     nearest structural      suppression and         transient protection     All penetrations through
                     frame member and, by    transient protection    must be directly         the CAA barrier must
                     extension, to the       must be directly        grounded to the          be thoroughly filtered.
                     lightning down          grounded to the         enclosures of the
                     conductor.              enclosures of the       protected equipment.     Both ends of shielded
                                             protected equipment.    TPDs installed in        cable shall be
                     The shields of          TPDs installed in       distribution frames and  terminated to case or
                     penetrating data lines  distribution frames     junction boxes must be   enclosure. Continuous
                     shall be bonded to the  and junction boxes      terminated directly to   peripheral bonding of
                     entrance panel, or to   must be terminated      the ground bus or to     the shield is best.
                     the facility ground     directly to the ground  the mounting
                     with a minimum          bus or to the           enclosure. The ground    Filters and TPDs
                     length conductor.       mounting enclosure.     bus and the mounting     installed for noise
                                             The ground bus and      enclosure must be        suppression and
                     Control cable shields   the mounting            bonded to the fault      transient protection
                     shall be bonded to      enclosure must be       protection subsystem     must be directly
                     antenna tower           bonded to the fault     with minimum length      grounded to the
                     structural members at   protection subsystem    conductors.              enclosures of the
                     the point of departure  with minimum length                              protected equipment.
                     from the tower.         conductors.                                      TPDs installed in
                                                                                              distribution frames and
                                                                                              junction boxes must be
                                                                                              terminated directly to
                                                                                              the ground bus or to the
                                                                                              mounting enclosure.
                                                                                              The ground bus and the
                                                                                              mounting enclosure
                                                                                              must be bonded to the
                                                                                              fault protection
                                                                                              subsystem with
                                                                                              minimum length
                                                                                              conductors.

1 See paragraph 2-3a for definition of BLACK protection areas.
2-16


---

                                                                                                                                TM 5-690

       (1) Support equipment is usually electrically self-contained and has its own internal safety
grounds. The connection to the power ground is via the three-pronged electrical plug, which connects to
the "green" wire safety ground or otherwise provides an electrical safety grounding connection.

       (2) Certain kinds of furniture and carpet may be responsible for the build-up of static charges.
When personnel walking across carpet or in contact with furniture touch a piece of electronic equipment,
a discharge can occur causing serious damage to solid-state devices. Computer and communication
equipment is especially susceptible to damage of this type, particularly if they contain metal oxide
semiconductor (MOS) integrated circuits. However, static build-up can be eliminated by proper choice of
materials and by proper grounding of the offending objects and the affected equipment. Properly
designed raised floors in data processing areas can largely fulfill this grounding requirement.

       (3) The particular grounding and bonding requirements and constraints imposed on C4ISR
personnel support systems are summarized in table 2-10.

Table 2-10. Grounding and bonding principles for personnel support equipment

Power Safety                      Lightning  EMC  EMP                  Signal Security

All exposed elements of                           Waveguide-below-
electrical equipment and                          cutoff personnel
appliances should be                              entryways must be
grounded via the green wire                       peripherally bonded
ground to the fault protection                    to the supporting
subsystem, with the                               structure/shields.
following exceptions:
Certain types of high current,
220-volt appliances such as
ranges, ovens, and dryers
commonly are designed such
that the neutral is grounded
to the frame. These
appliances shall not be
grounded to the fault
protection subsystem, to
structure, nor to utility pipes.

Doubly insulated, portable
equipment does not need to
be grounded, as per the
National Electrical Code.

2-3. C4ISR facility protection requirements

The C4ISR facility requires different levels of protection dependent on the importance to national security
for the area.

  a. Protection areas. In the areas of protection two generic terms are used to depict the importance to
national security. These terms are RED and BLACK. RED is applied to wire lines, components,
equipment, and systems that handle national security signals, and to areas in which national security
signals occur. BLACK is applied to wire lines, components, equipment, and systems that do not handle
national security signals, and to areas in which no national security signals occur. The facility itself

                                                                                                                                       2-17


---

TM 5-690

generally contains three areas requiring protection; these are the controlled access area (CAA), the
Limited Exclusion Area (LEA), and the Controlled BLACK Equipment Area (CBEA).

       (1) A controlled access area (CAA) is the complete building or facility area under direct physical
control, which can include one or more LEA, CBEA, or any combination thereof.

       (2) A limited exclusion area (LEA) is a room or enclosed area to which security controls have
been applied to provide protection to a RED information processing systems' equipment and wire lines
equivalent to that required for the information transmitted through the system. A LEA must include a
RED equipment area.

       (3) A controlled black equipment area (CBEA) is a BLACK equipment area that is not located in a
LEA but is afforded the same physical entry control which would be required if it were within a LEA.

  b. Practices. The grounding and bonding practices for the C4ISR facility must conform to the
requirements for electrical safety and for lightning protection, must not compromise signal security, and
must not degrade EMI control and EMP hardness. The ten identified elements of the generic C4ISR
facility may therefore be logically divided into three categories.

       (1) The first category includes those that must establish contact with earth in order to function
correctly. In this category are the earth electrode subsystem and the lightning protection subsystem.

       (2) The second category includes those elements which do not require grounding in order to
perform their primary function, but which must be grounded for safety, for overvoltage protection, or
because they tend to become part of the facility grounding system through convenience or accessibility.
In this category are the structure, electrical power generation and distribution subsystem, utilities, HVAC,
and personnel support.

       (3) In the third category are those facility elements which must be grounded for fault protection
and whose functioning may be severely impacted by improper grounding and bonding practices. This
category includes the communications, data processing, and security and control systems. For these
systems, in particular, the necessary protection against EMI, control of unwanted emissions, and EMP
may be compromised unless proper grounding and bonding practices are followed.

  c. Electrical safety (fault protection). The two primary goals of the fault protection subsystem are
protection of personnel from exposure to electrical shock hazards in the event that short circuits or
leakage paths occur between electrical conductors and exposed metal surfaces or objects and rapid
clearance of fault conditions to minimize potential fire hazards. The electrical safety (fault protection)
system falls in the second or third categories of protection.

       (1) Effective electrical fault protection is achieved through the establishment of a low resistance
contact with earth; the installation of ground mats or grids underneath high voltage transformers, circuit
breakers and switchgear; and the installation of dedicated grounding conductors ("green wire") to
equipment surfaces likely to become energized in the event of a fault.

       (2) A low resistance connection to earth at substations and transformer locations simultaneously
aids in clearing primary sideline faults while minimizing hazardous potentials. Since commercial power
lines are highly exposed to lightning, the lightning surge arresters protecting the transformers, breakers,
and switches are likely to be activated regularly. These lightning surge currents must be safely conducted
to earth at the transformer/breaker location rather than through other, uncontrolled paths. This
requirement can best be met with a low resistance, earth electrode subsystem at the power
transformer/breaker/switchgear site.

2-18


---

                                                                                                                                TM 5-690

       (3) The purpose of the mats or grids under high voltage apparatus is to limit to safe values the
step-and-touch voltages that are produced during high current fault conditions and during lightning surge
arrester firings. In this way, if a fault occurs while personnel are in the substation or switchgear room, the
voltages to which they are exposed remain within non-lethal ranges. Mats and grids are also effective in
establishing a low resistance contact with earth. This low resistance is helpful in minimizing the voltage
differential between objects in contact with the mat and personnel or objects not in contact with the mat.

       (4) As a further protective measure against hazardous step-and-touch potentials during faults and
lightning discharges, all metal objects, such as gates, fences, towers and barriers, which are in the
immediate vicinity of the transformer/breaker site must be electrically interconnected with the grounding
system for the site.

       (5) A dedicated fault current return path must be installed between all potential fault locations and
the source at E/Gs, transformer secondaries, and service disconnects. Thus all electrically powered
equipment and the conduit, raceway, breaker panels, and junction boxes associated with the electrical
distribution system must be electrically interconnected with the "green wire," or the "equipment
grounding conductor” specified by the National Electrical Code®. This equipment grounding conductor
is connected to the source neutral at all engine/generators, transformer secondaries and service entrance
disconnects. (Reprinted with permission from NFPA 70-2002, the National Electrical Code® Copyright©
2002, National Fire Protection Association, Quincy, MA 02269. This reprinted material is not the
referenced subject which is represented only by the standard in its entirety.)

       (6) In order to prevent ac return current from flowing in the power grounding network, the neutral
must not be grounded at any point following the first disconnecting means of a separately derived system
or the building (i.e., "main") disconnecting means of an ac supply originating outside the building served.

       (7) The generators, transformers, power converters, and power conditioners within the C4ISR
facilities constitute "separately derived systems." Figure 2-3 shows the required grounding for separately
derived systems.

          (a) Article 250-20(d) of the National Electrical Code® defines separately derived systems as "a
premise wiring system whose power is derived from generator, transformer, or converter windings and
has no direct electrical connection, including a solidly connected grounded circuit conductor, to supply
conductors originating in another system.” An alternate power source cannot be considered as a
separately derived system if its neutral is solidly interconnected to a normal utility service supplied
system neutral. Figure 2-4 shows the required grounding for non-separately derived systems.

          (b) Separately derived systems are grounded for fault protection and personnel safety in the
same way as normal ac supply systems. The neutrals from the wye windings of generators and the wye
secondaries of transformers are bonded to the fault protection subsystem. Article 250-28 of the National
Electrical Code® specifies that a bonding jumper sized in accordance with table 250-66 be used to
interconnect the equipment grounding conductors of the separately derived system to the grounded
conductor of the separately derived system. Further, this connection may be made at any point between
the source and the first disconnecting means for that separately derived source. Confusion can arise
between "the first disconnecting means for a separately derived system" and "the building disconnecting
means" for normal commercial service.

          (c) The intent for either separately derived sources or normal commercial ac service is to have
the grounded conductor (as defined in Article 250-24) made common with the grounding conductor so as
to complete the fault return path and to prevent the grounded conductor from contacting the grounding
conductor at any point beyond the service disconnect for that particular ac service. Thus, the
interconnection of the neutrals of transformer or generator wye windings to building steel and the

                                                                                                                                       2-19


---

TM 5-690
interconnection of the neutral conductor to the grounding conductor at the first disconnect following the
transformer or generator fulfills the requirements of the Code. This requirement for the interconnection
of neutral to the grounding conductor applies to both normal ac service and separately derived systems.
The neutral is not grounded for non-separated derived systems, which have a bonded neutral conductor, to
avoid incorrect operation of overcurrent devices during ground faults. Beyond this disconnect, no
connections may be made between the grounded conductor (the neutral) and the safety grounding
conductor.

            (d) Except where single-phase loads are involved, the neutrals are not continued beyond the
disconnect of separately derived systems or the disconnect for the building, as appropriate. Where single-
phase loads are served, both the neutral and the grounding conductor are continued to the loads. The
grounding conductor must be run with the phase conductors, which include the neutral.

                         Figure 2-3. Required grounding for separately derived systems
2-20


---

                                                                                                                                TM 5-690

                       Figure 2-4. Required grounding for non-separately derived systems
        (e) A major category of equipment that is exempted from this prohibition of grounding of the
neutral includes ranges and clothes dryers. These personnel support equipment typically have their
neutrals connected to the frames. Consequently, these appliances should not have their frames
interconnected with the remaining elements of the facility grounding system, including utility pipes.
      (8) At engine/generator locations, low resistance contacts with earth are typically installed. In
indoor locations where operating personnel may be reasonably isolated from intimate contact with earth,
the necessary fault protection reference for multiple engine/generators can be achieved through the
installation of a copper bus bar of adequate cross section around or throughout the engine/generator area.
This bus in turn is connected to the fault protection subsystem or to the earth electrode subsystem at the

                                                                                                                                       2-21


---

TM 5-690

motor/generator if the engine/generator is a separately derived system, i.e. its neutral is not solidly
connected to the neutral of the normal ac supply. If the engine/generator neutral were solidly tied to the
normal ac supply the engine/generator would not be considered a separately derived system and the
generator neutral would not be grounded. A four-pole transfer switch, which transfers the neutral
conductor or a transfer switch with overlapping neutral make-before-break contacts, is normally used for
transferring between separately derived power sources, i.e. the normal ac supply and the
engine/generators instead of a three-pole transfer switch. For additional reference material on grounding
of engine/generators see IEEE 446-1995, Recommended Practice for Emergency and Standby Power
Systems for Industrial and Commercial Applications.

           (a) Where phase-to-neutral loads must be served, engine/generators are required to be solidly
grounded. However, 600 volt and 480 volt systems may be high resistance grounded or ungrounded
where a grounded circuit conductor is not used to supply phase-to-neutral loads.

           (b) High resistance grounded or ungrounded engine/generators may provide a higher degree of
service continuity than solidly grounded engine/generators. High resistance grounding combines some of
the advantages of solidly grounded systems and ungrounded systems. System overvoltages are held to
acceptable levels during ground faults, and the potentially destructive effects of high magnitude ground
currents are eliminated. With high resistance grounding, ground fault currents are normally limited to 10
amperes or less to allow continued operation of a system until the fault is located and cleared. However,
if a ground fault is not located and cleared before another ground fault occurs, the high magnitude ground
currents will flow through the equipment grounding conductors and operate the circuit protective devices.

           (c) Where phase-to-neutral loads are not served, low resistance grounding of engine/generators
may be used where limiting the ground-fault current is important. Such grounding may be used to limit
damage to large engine/generators. There is also an additional element of protection for personnel who
may be working on or near the engine/generator. The size of the resistor can be set to limit the current to
100 amperes; however, the 200-1000 ampere range is more typical. This provides sufficient current to
operate the motor protective devices for a line-to-ground fault. The neutrals of the engine/generators are
typically connected to ground through low resistance grounding resistors.

  d. Lightning protection. The lightning protection requirements seek to protect personnel, buildings,
and equipment from the high voltage and current transients produced by lightning discharges. A major
element of this protection is achieved by providing a means by which a lightning stroke can bypass the
facility and enter the earth without causing damage. The stroke current must first be intercepted before it
penetrates the structure. Air terminals are provided for this purpose. Preferential paths must then be
offered which the stroke current will follow instead of any others. To provide these preferred paths, down
conductors are designed to have large diameters and are routed to be as straight and short as possible.
Finally, a low impulse impedance connection with the earth must be made.

       (1) "Side flashes" between the down conductors and internal conducting objects within the facility
can occur because of the inherent inductance of the down conducting path. The internal conducting
objects must be interconnected with the down conductors to prevent this flashover. However, EMP and
TEMPEST protection practices prohibit unprotected conductors from penetrating the EM boundary,
which in many facilities is the exterior wall of the structure. Fortunately, the connection for preventing
flashover can be made without violating the EMP restrictions by bonding the cross conductors to the
outside and the inside, respectively, of the exterior wall (with no direct penetration).

       (2) An essential addition to the air terminals, down conductors, and earth connection for the
protection of electrical and electronic equipment is the installation of lightning arresters and terminal
protection devices (TPDs) on all external power, communications, data, and control lines that penetrate
the facility boundary. TPDs are fast-response protection devices installed for the purpose of shunting

2-22


---

                                                                                                                                TM 5-690

extraneous pulses to ground. Examples of commonly used terminal protection devices are carbon blocks,
gas-filled spark gaps, zener diodes, and EMI power and signal line filters. These devices must respond in
a sufficiently short time to limit the surge voltages produced by the lightning discharge to levels, which
can be tolerated by the equipment inside the facility. To obtain least response time and to limit the
overshoot voltage of the arresters and TPDs, these devices must be properly grounded. They must be
installed such that their leads are kept to minimum lengths and kept very near to facility ground
conductors.

  e. Electromagnetic (EM) interference. Each of the electronic subsystems found in C4ISR facilities
contain several pieces of equipment that must work together as an integrated unit. Communication and
data transfer between the equipment consists of analog, digital, RF, or audio signals. Extraneous energy
from other equipment within the facility or from sources outside the facility can degrade performance or
damage components.

       (1) To prevent such interference or damage from occurring it is necessary that the level of the
interfering signal at the susceptible component be reduced by relocating the sensitive equipment inside a
shielded volume and by shielding and filtering the power and signal conductors. Grounding, in and of
itself, is not part of the interference control process. Yet the method of grounding filters and equipment
cases and the bonding of cable shields can influence the performance of shields and filters and other EMI
protective measures.

       (2) Grounding is required for lightning protection and for electrical safety. In most installations,
signal references will not remain isolated from the safety and lightning protection grounds. For example,
signal paths between equipment often use unbalanced transmission lines in which the low, signal return
side is electrically interconnected with the case. Since the case must be grounded for electrical safety, the
signal reference ground and the power safety become common. This interconnection between the signal
reference and the power safety ground gives rise to the frequently mentioned "ground loops." The stray
current flowing in the common "ground" produces the common-mode voltage between interconnected
equipment. Such voltages can produce a differential noise voltage in the terminating loads of the
equipment, which can disrupt the intended operation of the system or damage circuit components. The
degree of interference or upset experienced in a given situation is dependent upon the impedance of the
common path, the amplitude of the stray current in the path, the common-mode rejection of the cabling
between the equipment and the internal circuitry of the equipment, and the relative susceptibility of the
circuits to the coupled noise currents. Typically, the most serious contributors to "ground loop
interference" are the very high stray power currents present in the fault protection subsystem of C4ISR
facilities. These currents commonly arise from electrical wiring errors, which interchange the neutral
(white) and grounding (green) conductors. Other contributors to troublesome grounding network noise
currents are filter capacitors in shunt across power lines and improperly wired electronic equipment.
Particular attention needs to be paid to locating and correcting excessive stray power currents wherever
they exist.

       (3) A frequently encountered recommendation for eliminating "ground loop noise" in signal and
data circuits is to install a single point ground. The single point ground seeks to isolate the entire signal
processing circuitry in the interconnected equipment from the fault protection subsystem except for one
connection. To achieve a truly single point grounded complex of equipment requires extraordinary
attention to assuring that all pieces of equipment except one are completely isolated from the fault
protection subsystem. Not only must the complex be laid out to be fed from a single ac power source, but
also no hardwired signal, control, or other type of lines may interconnect with other equipment outside the
complex. Not only are these constraints difficult to achieve at initial installation but they are also
impractical to maintain over any extended period of use. Consequently, single point grounded systems
are being replaced with multiple point grounded systems. A multiple point grounding system is a
grounding system with multiple connections to earth. In addition, as noted in the previous section, even

                                                                                                                                       2-23


---

TM 5-690

in those locations where single point ground networks are said to be installed, normal installation
practices typically produce a multiple point, interconnected grounding system.

       (4) The merits of the multiple point ground are that it is straightforward to install since it does not
demand special training or procedures, and it is simple to maintain during normal operation and through
successive upgrades or retrofits.

  f. Electromagnetic pulse (EMP). The EMP generated by a nuclear explosion presents a harsh EM
environmental threat with lightning being the closest comparable threat. Exo-atmospheric nuclear bursts
can develop pulses of EM energy whose amplitudes can approach 50,000 volts/meter over geographical
regions nearly the size of the continental United States. Such high amplitude, short duration EM fields
can induce currents into long unprotected conductors sufficient to cause operational upset and component
burnout in C4ISR equipment.

       (1) Since the EMP threat is significantly different from any other man-made or natural EM threat,
the measures that are routinely incorporated for protection from non-EMP environments are not adequate.
For example, the structures that are intended to house equipment in non-EMP environments are typically
not designed nor constructed with an aim toward providing the extensive EM shielding needed for EMP
protection.

       (2) Effective EMP protection requires the construction of a closed EM barrier surrounding the
susceptible equipment. The realization of an EM barrier involves the construction of an effective shield,
the treatment of shield penetrations and apertures, and correct grounding and bonding.

          (a) Shielding involves the use of metallic barriers to prevent the direct radiation of incident
energy into the system and internal enclosures and to minimize the coupling of energy to cables and other
collectors which may penetrate these barriers. Shielding is the basic element of any barrier design, and
little EMP protection is possible without its proper use. A completely solid shield is not possible since
mechanical and electrical penetrations and apertures are necessary. These openings must be properly
treated, or "closed," to prevent unacceptable degradation in the effectiveness of the shield. Grounding
and bonding, by themselves, do not directly provide protection against EMP. However, they form an
integral part of, and are inseparable from, enclosure shield designs and penetration and aperture
treatments. Proper grounding and bonding techniques and practices must be followed if violations in the
integrity of EMP shields and of penetration and aperture treatments are to be avoided.

           (b) In some existing C4ISR facilities, it may be possible to enclose the entire building
containing critical equipment, including power, inside a well-bonded metal shell. In most situations,
however, surrounding the total building with a metal shell will be extremely difficult and extraordinarily
expensive. For the majority of cases, shielding of only part of the volume of the building will be realistic.
In perhaps a small number of facilities, the necessary amount of EMP protection can be achieved by only
shielding individual equipment enclosures.

           (c) Inside a volume, shielded with solid metal, the primary purpose of grounding is to achieve
electrical safety. A facility not totally shielded may be conveniently divided into EM zones. Outside the
structural walls of the facility is defined as Zone 0. Inside the facility outer walls, but outside equipment
enclosures or internal shielded rooms, is then Zone 1. Thus, the facility outer structural walls become the
Zone 0/1 boundary. (For underground facilities, the rock-earth overburden may be considered to be the
Zone 0/1 boundary.) Zone 2 is then inside the electronic enclosure or inside the shielded room, if present.
Higher ordered zones may also be defined, according to the level of compartmentalization employed.

           (d) In the absence of a solid metal, well-bonded shield for the Zone 0/1 boundary, certain steps
can be taken to minimize the coupling of EMP energy into the facility. Minimal steps include

2-24


---

                                                                                                                                TM 5-690

implementing low resistance bonds across structural joints and assuring that utility pipes are effectively
bonded to the earth electrode subsystem where they cross, or to the facility ground subsystem at the point
where the pipes enter the facility. Fast acting surge suppressors should be installed across entering power
and signal lines.

           (e) More substantial steps include augmenting the shielding properties of the structure by
installing wire mesh or sheet metal. The added metal must be continuously joined at the seams and joined
to the existing structural steel members with soldered or welded connections.

           (f) More comprehensive EMP treatment involves rerouting utility, electrical, and signal
conductors into the facility through a well-shielded entry vault or through an entry plate positioned at or
below grade level with a short interconnection with the earth electrode subsystem. Surge arresters and
TPDs should be returned to the entry vault walls or to the entry plate with minimum length conductors.

  g. Signal security. Equipment that processes classified information may produce signals capable of
unauthorized detection. To prevent such security compromises, measures must be taken to reduce
sensitive data signals to levels low enough to make detection impossible in areas accessible to
unauthorized personnel. These measures include controlled grounding practices.

       (1) The recommended approach to TEMPEST grounding is illustrated in figure 2-5. All
equipment cabinet grounds, RED signal grounds, and BLACK signal grounds are made to the ground
reference established inside the CAA. Both RED and BLACK cable shields are peripherally bonded to
equipment cabinets at both ends. The low sides of BLACK data lines are connected to cable shields in
the BLACK intermediate distribution frame (IDF) and both are grounded to the ground reference plane.
Notice that BLACK cables should exit the controlled area via filtered couplings through the CAA
boundary.

  RED   RED            BLACK            CAA
EQUIP.  IDF              IDF
                              BLACK
             CRYPTO           EQUIP.

              CONDUIT                        FILTERED
                                             PENETRATION
        RED SIGNAL
        REFERENCE      BLACK
        SUB-SYSTEM     SIGNAL
                       REFERENCE
                       SUB-SYSTEM

                                                    EQUIPOTENTIAL PLANE
NOTE: GREEN WIRES NOT SHOWN

               Figure 2-5. Recommended TEMPEST signal reference subsystem
                                                                                                                             2-25


---

TM 5-690

      (2) Figure 2-6 depicts the grounding approach recommended for ac power distribution in secure
facilities. Note that both the neutral and phase conductors are filtered. As discussed earlier, the neutral is
grounded only at the service disconnect. The cases of all subsequent distribution panels, filter enclosures,
technical power panels, and equipment are all interconnected with the deliberately installed grounding
conductor. Note that the equipment cases are connected to the BLACK signal reference system, which is
grounded to the reference plane.

                                                  FROM THE FILTER BACK, THE GREEN     LEGEND:
                                                  WIRE CONDUCTOR SHOULD BE THE
                                                  SAME AWG AS THE NEUTRAL.                     NEUTRAL
                                                                                               HOT
                                                                                               GREEN SAFETY GROUND

                                                                                           N   NEUTRAL BUS UNGROUNDED

                             EARTH                                                         N   NEUTRAL BUS GROUNDED
                             ELECTRODE
                             SYSTEM

                                                  MOUNT ALL FILTERS REGARDLESS OF
                                                  PHASE IN A SINGLE BOX THROUGH
                                                  STUD. BRAZE BOTH SIDES.

               N             N                             N                       N

                                                           MOUNTING PLATE IN A
                                                           STANDARD FILTER(S)
                                                           CONTAINER

               MAIN SERVICE  DISTRIBUTION         FILTERS  TECHNICAL            EQUIPMENT
                 DISCONNECT         PANEL                      POWER
                                                               PANEL

          UAA                                CAA  LEA         FACILITY GROUND SYSTEM

               EARTH ELECTRODE SUBSYSTEM

          NOTE: WHEN USE OF NEUTRAL FILTERS
          INTRODUCES OPERATIONAL PROBLEMS,
          THE NEED FOR THE FILTER SHOULD BE
          VERIFIED BY A TEMPEST TEST.

                         Figure 2-6. Recommended power grounding for secure facilities

2-4. Role of grounding

The C4ISR grounding system consists of four subsystems, (1) the earth electrode subsystem, (2) the fault
protection subsystem, (3) the lightning protection subsystem, and (4) the signal reference subsystem. The
purpose of the earth electrode subsystem is to provide a path to earth for the discharge of lightning
strokes, prevent shock hazard to personnel, and assist in the control of noise. The primary purpose of the
fault protection subsystem is the protection of circuits and equipment by ensuring prompt operation of
overcurrent devices and protection of personnel from electric shock hazards. The primary purpose of the
lightning protection subsystem is the reduction of overvoltages due to lightning and power system surges.
The primary purpose of the signal reference subsystem is the reduction of EMI due to EM field, common
ground impedance, or other forms of interference coupling. The various grounding systems used are
integral parts of a facility or system.

  a. Facility ground network design. The facility ground network design should consider all aspects to
the degree required for the particular mission of the facility in its environment and in the context of cost-

2-26


---

                                                                                                                                TM 5-690

effectiveness. The use of the term facility ground network is intended to be in the collective sense; it
includes the power fault protection network, lightning protection network, building or structure ground,
equipment ground, signal ground, instrument ground, data ground, etc.

  b. Installation requirements. Requirements for the safe installation of electric conductors and
equipment within or on various facilities are contained in the National Electrical Code® NFPA 70-2002.

  c. Separation of equipment grounding. The grounding of the electrical system and connection of the
electrical system neutral to earth must be separated from the equipment grounding. Reasons for the
electrical system to be grounded are stabilization of the voltage (that is, to keep it from floating above a
set reference point), facilitation of clearing phase to enclosures/ground faults, and limitation of lightning
and line surges.

2-5. Role of bonding

Bonding refers to the process by which a low impedance path for the flow of an electric current is
established between two metallic objects. In any realistic electronic system, whether it be only one piece
of equipment or an entire facility, numerous interconnections between metallic objects must be made in
order to minimize electric shock hazards, provide lightning protection, establish references for electronic
signals, etc. Ideally, each of these interconnections should be made so that the mechanical and electrical
properties of the path are determined by the connected members and not by the interconnection junction.
Further, the joint must maintain its properties over an extended period of time in order to prevent
progressive degradation of the degree of performance initially established by the interconnection.
Bonding is concerned with those techniques and procedures necessary to achieve a mechanically strong,
low impedance interconnection between metal objects and to prevent the path thus established from
subsequent deterioration through corrosion or mechanical looseness.

  a. Bonding objectives. In terms of the results to be achieved, bonding is necessary for the:

     (1) Protection of equipment and personnel from the hazards of lightning discharges;

     (2) Establishment of fault current return paths;

     (3) Establishment of homogeneous and stable paths for signal currents;

     (4) Minimization of RF potentials on enclosures and housings;

     (5) Protection of personnel from shock hazards arising from accidental power ground; and

     (6) Prevention of static charge accumulation.

  b. Effects of poor bonds. With proper design and implementation, bonds minimize differences in
potential between points within the fault protection, signal reference, shielding, and lightning protection
networks of an electronic system. Poor bonds, however, lead to a variety of hazardous and interference-
producing situations.

     (1) For example, loose connections in ac power lines can produce unacceptable voltage drops at the
load, and the heat generated by the load current through the increased resistance of the poor joint can be
sufficient to damage the insulation of the wires which may produce a power line fault or develop a fire
hazard or both. Loose or high impedance joints in signal lines are particularly annoying because of
intermittent signal behavior such as decreases in signal amplitude, increases in noise level, or both. Poor
joints in lightning protection networks can be particularly dangerous. The high current of a lightning
discharge may generate several thousand volts across a poor joint.

                                                                                                                                       2-27


---

TM 5-690

       (2) Degradation in system performance from high noise levels is frequently traceable to poorly
bonded joints in circuit returns and signal referencing networks. As noted previously, the reference
network provides low impedance paths for potentially incompatible signals. Poor connections between
elements of the reference network increase the resistance of the current paths. The voltages developed by
the currents flowing through these resistances prevent circuit and equipment signal references from being
at the same reference potential.

       (3) Poor bonds in the presence of high-level RF fields, such as those in the immediate vicinity of
high powered transmitters, can produce a particularly troublesome type of interference. Poorly bonded
joints have been shown to generate cross modulation and other mix products when irradiated by two or
more high level signals. Some metal oxides are semiconductors and behave as nonlinear devices to
provide the mixing action between the incident signals. Interference thus generated can couple into
nearby susceptible equipment.

  c. Importance of Bonding. Bonding is also important to the performance of other interference control
measures. For example, adequate bonding of connector shells to equipment enclosures is essential to the
maintenance of the integrity of cable shields and to the retention of the low loss transmission properties of
the cables. The careful bonding of seams and joints in EM shields is essential to the achievement of a
high degree of shielding effectiveness. Interference reduction components and devices also must be well
bonded for optimum performance.
2-6. Role of shielding
Shielding involves the use of metallic barriers to prevent the direct radiation of incident energy into the
system and internal enclosures and to minimize the coupling of energy to cables and other collectors that
may penetrate these barriers. Shielding is the basic element of any barrier design, and little EMP
protection is possible without its proper use. A completely solid shield is not possible since mechanical
and electrical penetrations and apertures are necessary. These openings must be properly treated, or
"closed," to prevent unacceptable degradation in the effectiveness of the shield. Grounding and bonding,
by themselves, do not directly provide protection against EMP. However, they form an integral part of,
and are inseparable from, enclosure shield designs and penetration and aperture treatments. Proper
grounding and bonding techniques and practices must be followed if violations in the integrity of EMP
shields and of penetration and aperture treatments are to be avoided.

2-28


---

                          TM 5-690

            CHAPTER 3

FACILITY GROUND SYSTEM
FOR NEW C4ISR FACILITIES

3-1. Ground system

A facility ground system is typically comprised of four major subsystems. These are the earth electrode
subsystem, the fault protection subsystem, the lightning protection subsystem, and the signal reference
subsystems.

  a. Earth electrode subsystem. Earth grounding is defined as the process by which an electrical
connection is made to the earth. The earth electrode subsystem is that network of interconnected rods,
wires, pipes, or other configuration of metals, which establishes electrical contact between the elements of
the facility and the earth. The extensions into the building are used as the principal ground point for
connection to equipment ground subsystems serving the facility. Ground reference is established by
electrodes in the earth at the site or installation. This system should achieve the following objectives.

       (1) Provide a path to earth for the discharge of lightning strokes in a manner that protects the
structure, its occupants, and the equipment inside.

       (2) Restrict the step-and-touch potential gradient in areas accessible to persons to a level below the
hazardous threshold even under lightning discharge or power fault conditions.

       (3) Assist in the control of noise in signal and control circuits by minimizing voltage differentials
between the signal reference subsystems of separate facilities.

  b. Fault protection subsystem. The fault protection subsystem ensures that personnel are protected
from shock hazard and equipment is protected from damage or destruction resulting from faults that may
develop in the electrical system. It includes deliberately engineered grounding conductors (green wires),
which are provided throughout the power distribution system to afford electrical paths of sufficient
capacity, so that protective devices such as fuses and circuit breakers installed in the phase or hot leads
can operate promptly. If at all possible the equipment fault protection conductors should be physically
separate from signal reference grounds except at the earth electrode subsystem. The equipment fault
protection subsystem provides grounding of conduits for signal conductors and all other structural
metallic elements as well as the cabinets or racks of equipment. In the event of transformer failure (e.g.,
disconnect between neutral and ground or line to ground faults) or any failure between the service
conductor(s) and grounded objects in the facility, the earth electrode subsystem becomes a part of the
return path for the fault current. A low resistance assists in fault clearance; however, it does not guarantee
complete personnel protection against hazardous voltage gradients, which are developed in the soil during
high current faults. Adequate protection generally requires the use of ground grids or meshes designed to
distribute the flow of current over an area large enough to reduce the voltage gradients to safe levels. The
neutral conductor at the distribution transformer must therefore be connected to the earth electrode
subsystem to ensure that a low resistance is attained for the return path.

  c. Lightning protection subsystem. The lightning protection subsystem provides a non-destructive path
to ground for lightning energy contacting or induced in facility structures. To effectively protect a
building, mast, tower, or similar self-supporting objects from lightning damage, an air terminal (lightning
rod) of adequate mechanical strength and electrical conductivity to withstand the stroke impingement

                                                                                                                                         3-1


---

TM 5-690

must he provided. An air terminal will intercept the discharge to keep it from penetrating the non-
conductive outer coverings of the structure, and prevent it from passing through devices likely to be
damaged or destroyed. A low-impedance path from the air terminal to earth must also be provided.
These requirements are met by either an integral system of air terminals, roof conductors, and down
conductors securely interconnected to provide the shortest practicable path to earth; or a separately
mounted shielding system, such as a metal mast or wires (which act as air terminals) and down
conductors to the earth electrode subsystem.

  d. Signal reference subsystem. The signal reference subsystem establishes a common reference for
communications equipment, thereby also minimizing voltage differences between equipment. This in
turn reduces the current flow between equipment and also minimizes or eliminates noise voltages on
signal paths or circuits. Within a piece of equipment, the signal reference subsystem may be a bus bar or
conductor that serves as a reference for some or all of the signal circuits in the equipment. Between
equipment, the signal reference subsystem will be a network consisting of a number of interconnected
conductors. Whether serving a collection of circuits within a single piece of equipment or serving several
pieces of equipment within a facility, the signal reference network will in the vast majority of cases be a
multiple point/equipotential plane. However, in some cases, the signal reference subsystem can be a
single point depending on the equipment design, the facility, and the frequencies involved.

  e. Interfaces among the subsystems. The earth electrode subsystem provides the main grounding
connection to the earth for the facility, the associated equipment, and the personnel protection
requirements. This system interfaces with all the other grounding systems in that it provides the ultimate
earth ground, ensuring the other systems provide the protection they were designed for.

3-2. Earth electrode subsystem

The earth electrode subsystem establishes the electrical connection between the facility and earth. This
connection is necessary for lightning protection, useful in power fault protection, and in the minimization
of noise. The system should be tailored to reflect the characteristics of the site and the requirements of
the facility. It must be properly installed and steps must be taken to assure that it continues to provide a
low resistance connection throughout the life of the structure.

  a. Typical configurations. Typical configurations of an earth electrode subsystem may consist of the
following.

       (1) A system of buried, driven rods interconnected with bare wire that normally form a ring around
the building; or

       (2) Metallic pipe systems, i.e., water, gas, fuel, etc., that have no insulation joints (metallic pipe
systems shall not be used as the sole earth electrode subsystem); or

       (3) A ground plane of horizontal buried wires.

  b. Design. To achieve the desired objectives of the earth ground system, design of the system to be
installed is of utmost importance. For an acceptable system the following steps must be followed.

       (1) Perform a site survey to determine the electrical and physical properties of the site,

       (2) Design an earth electrode subsystem appropriate for the site,

       (3) Install the subsystem in accordance with the recommended procedures, and

3-2


---

                                                                    TM 5-690

       (4) Measure the earth resistance of the subsystem to verify that it meets the recommended goals or
design specifications.

  c. Soil resistivity. As the first step of the site survey, measure the resistivity of the soil at several points
over the area of the planned facility. For even the smallest facility, the effective facility area in so far as
the electrode subsystem is concerned is assumed to be at least 15 meters by 15 meters (50 feet by 50 feet).
For larger facilities, the facility areas are assumed to extend at least 6 meters (20 feet) beyond the basic
building or structural outline, i.e., the ground floor plan, substation grid, tower footing, transformer
housing, etc. It is necessary that the soil resistivity be known over the area encircled or covered by the
earth electrode subsystem. It is not always possible to ascertain with a high degree of certainty the exact
type of soil present at a given site. Soil is typically rather non-homogeneous; many types will be
encountered at most locations. Even with the aid of borings and test samples the resistivity estimate can
easily be off by two or three orders of magnitude. When temperature and moisture variations are added to
the soil type variations, it is evident that estimates based on standard values are not sufficiently accurate
for design purposes. The only way to accurately determine the resistivity of the soil at a specific location
is to measure it. The most commonly used field methods for determining soil resistivity employ the
technique of injecting a known current into a given volume of soil, measuring the voltage drop produced
by the current passing through the soil, and then determining the resistivity using standard equations.

       (1) The one electrode method involves driving a round electrode in the earth and then inducing a
current into it. In uniform earth, injected current flows radially from the hemispherical electrode.
Equipotential surfaces are established concentric with the electrode and perpendicular to the radial
directions of current flow. As the current flows from the hemisphere, the current density decreases with
distance from the electrode because the areas of successive shells become larger and larger. The current
density within the earth, at given distances from the center of the electrode, is then calculated. The
electric field strength is then calculated, which allows the resistance and subsequently the resistivity of the
earth to be calculated. Approximate values of earth resistivity are given in table 3-1.

                   Table 3-1. Approximate soil resistivity

     Type of Soil  Ohm-m        Resistivity                 Ohm-ft
                   10     Ohm-cm                            33
Wet Organic        102    103                               330
Moist              103    104                               3300
Dry                104    105                               33000
Bed Rock                  106

       (2) In the four-terminal method developed by the U.S. Bureau of Standards, four electrodes are
inserted into the soil in a straight line with equal spacings. A known current is injected into the soil
through the end electrodes and the voltage drop between the two inside electrodes is measured.
Connection is made to the electrodes by insulated conductors. The current is introduced into one of the
outermost spheres and flows out of the earth through the other outermost sphere. The voltage from the
left hand to the right hand inner sphere can be viewed as resulting from a current flowing to infinity and

                                                                    3-3


---

TM 5-690

another returning from infinity. The resistance and subsequently the earth resistivity can then be
calculated.

  d. Geological considerations. Identify the significant geological features of the site. Specifically,
attempt to establish:

       (1) The distribution of major soil types to include the locations of sand and gravel deposits

       (2) Major rock formations

       (3) The presence of water sources to include underground streams

       (4) The depth of the water table

       (5) Utilize test borings, on site inspections, studies of local maps, and interviews with local
 construction companies, well drillers, and other local personnel to obtain the desired information.

       (6) Evaluate the information provided by these sources for indications of particularly troublesome
 (or particularly helpful) characteristics that may influence the design or installation of the earth electrode
 subsystem of the facility.

  e. Physical features. Locate and identify those other physical features that will influence the general
placement of the earth electrode subsystem, the location of test and access points, physical protection
requirements, and the cost of materials and installation. For example, indicate on the general site plan the
planned physical layout of the building or structure, locations of paved roads and parking lots, drainage
(both natural and man-made), and the location of buried metal objects such as pipes and tanks.

  f. Local climate. Review local climatic conditions and determine the annual amount and seasonal
distribution of rainfall, the relative incidence of lightning, and the depth of freezing (frost line) typical of
the area. Obtain the rainfall and frost line information from the local weather service and project the
relative lightning incidence from isokeraunic maps. Record the data and make it a part of the facility files
for the site. Immediately, however, use this information to aid in the design of the earth electrode
subsystem for the facility to be constructed at the site.

  g. Design procedure. The detailed design process involves discrete steps that ensure the system will
perform the intended function.

     (1) Determine what type of earth electrode subsystem is most appropriate for the facility. The
directed configuration is a ring ground. If this configuration cannot be employed, alternate configurations
meeting the requirements must be considered.

     (2) Establish the primary functional requirements to be met by the earth electrode subsystem.

          (a) For a facility located in an area of high lightning incidence or a high degree of exposure to
lightning, or both, the earth electrode subsystem must safely dissipate the lightning energy without
melting conductors or overheating the soil. Also, the subsystem must minimize step voltages in areas
where personnel are present.

          (b) If the antenna counterpoise must serve as an earth electrode subsystem, it must have low RF
impedance properties.

3-4


---

                                                                                                                                TM 5-690

         (c) At fixed facilities, the earth electrode subsystem should exhibit a resistance to earth of 10
ohms or less. If 10 ohms is not economically feasible by the ring ground, alternate methods should be
considered

    (3) The conditions of the site and its location must be considered in the design process.

        (a) Determine if the soil resistivity is low (< 5000 ohm-cm), average (5000 to 20,000 ohm-cm), or
high (> 20,000 ohm-cm). The higher the soil resistivity, the more complex (and expensive) will be the
electrode subsystem necessary to achieve 10 ohms resistance.

        (b) Consideration must be given to the water table at the site. Factors to consider include its
location in relation to the surface and whether or not it is subject to large seasonal variations. Design the
earth electrode subsystem so that it makes and maintains contact with soil that stays damp or moist year
round if at all possible. Penetration of the permanent water table is highly desirable.

        (c) The depth of the frost line even in the coldest periods must be determined. The resistivity of
soil rises greatly as the soil temperature drops below 32° F. Thus for maximum stability of electrode
resistance, the subsystem should penetrate far enough into the soil so that contact is always maintained
with unfrozen soil. In permafrost, fault protection must be provided through the use of metallic returns
accompanying the power conductors to insure the existence of a return path to the transformer or
generator. Personnel protection in permafrost requires an even greater emphasis on the bonding of all
metal objects subject to human contact and to the power system neutral. Because of the high resistance of
permafrost, stray earth currents can be expected to be minimal with consequently reduced concern with
inter-facility power frequency noise problems.

        (d) Major rock formations near the surface large enough to influence the design and layout of the
earth electrode subsystem must be considered. In regions of shallow bedrock, vertical ground rods may
not be usable and horizontal grids, wires, or plates must be used. Large rock outcropping or subsurface
boulders may force the alternate routing of conductors or the placement of rods. There is no need to incur
the expense of drilling holes in rock to insert rods or lay wires because the resistivity of rock is so high
that generally the rods or wires would be ineffective.

     (4) The design of the earth electrode subsystem must be such that it will not be materially
influenced by the weather shielding effects of parapets and overhangs. Lightning down conductor
placement and routing will frequently be influenced by architectural considerations. Design the earth
electrode subsystem to accommodate such considerations by providing convenient connection points near
the down conductors. Route the interconnecting cable of the earth electrode subsystem near down
conductors to avoid long extensions between the down conductor and the effective grounding point.
Configure the earth electrode subsystem such that convenient connections are possible between the earth
electrode subsystem and grounding conductors of the power and signal ground systems inside the facility.

    (5) Preferably locate ground subsystem conductors under sodded areas or those otherwise covered
with vegetation. Locate conductors to take maximum advantage of the wetting effects of runoff or
drainage water from the roof, parking lots, etc. Try to avoid placing major portions of this earth electrode
subsystem under extensive paved areas such as roads and parking lots.

    (6) Considering the relative advantages and disadvantages given in table 3-2, choose a basic type of
electrode most appropriate for meeting the functional requirements of the facility at the site under
construction.

                                                                                                                                         3-5


---

TM 5-690

     Table 3-2. Relative advantages and disadvantages of the principal types of earth electrodes

     Type                            Advantages                        Disadvantages
     Ring Ground
                                     Straightforward design. Easy      Not useful where large rock
     Horizontal Bare Wires           to install (particularly around   formations are near surface.
     (Radials)                       an existing facility). Hardware
                                     readily available. Can be
     Horizontal Grid (Bare Wire)     extended to reach water table.

     Vertical Rods                   Can achieve low resistance        Subject to resistance
                                     where rock formations prevent     fluctuations with soil drying.
     Plates                          use of vertical rods. Low
     Incidental Electrodes (utility  impulse impedance. Good RF
     pipes, building foundations,    counterpoise when laid in star
     buried tanks)                   pattern.

                                     Minimum surface potential         Subject to resistance
                                     gradient. Straightforward         fluctuations with soil drying if
                                     installation if done before       vertical rods not used.
                                     construction. Can achieve low
                                     resistance contact in areas
                                     where rock formations prevent
                                     use of vertical rods. Can be
                                     combined with vertical rods to
                                     stabilize resistance
                                     fluctuations.

                                     Straightforward design.           High impulse impedance. Not
                                     Easiest to install (particularly  useful where large rock
                                     around an existing facility).     formations are near surface.
                                     Hardware readily available.       Step voltage on earth surface
                                     Can be extended to reach          can be excessive under high
                                     water table.                      fault currents or during direct
                                                                       lightning strike.

                                     Can achieve low resistance        Most difficult to install.
                                     contact in limited area.

                                     Can exhibit very low              Little or no control over future
                                     resistance.                       alterations. Must be employed
                                                                       with other made electrodes.

      (7) Estimate the relative costs to meet the objectives with the different types of configurations.
Include the cost of materials, installation costs, and relative maintenance and upgrading costs.

3-6


---

                                                                                                                                TM 5-690

     (8) Once the most appropriate configuration is chosen for the facility, calculate the resistance to
earth for the configuration. If the calculated resistance meets the design goal (or requirement), complete
the design to include all necessary interconnections.

     (9) Non-ideal sites will frequently be encountered and will require an alternate configuration from
the standard ring ground system. For example, large rock formations may be present which prevent the
uniform placement of ground rods around the site; bed rock may be relatively near the surface; the water
level may drop to several feet below grade; the soil resistivity may be very high; or architectural and
landscape requirements may preclude locating ground rods at particular points. In such cases, modify the
electrode configuration to conform to the constraints while achieving the desired resistance. Typical
suggested alternatives are:

          (a) Change number of ground rods.

         (b) Use longer ground rods. Rods longer than 10 feet may be used in high resistivity soil in place
of a larger number of 10-foot rods. Where the ground water table is greater than 10 feet below the surface
at any season of the year or where the frost line is greater than 10 feet, use the longer rods to maintain
contact with the permanently moist, unfrozen soil.

         (c) Use horizontal wires or grids instead of vertical rods. Where bedrock or other obstacles
prevent the effective use of vertical rods, horizontal wires, grids, or radials should be used.

         (d) Lower the soil resistivity through chemical enhancement (salting). Where the above
alternatives are not possible or are not cost effective, chemical enhancement is frequently the only choice
left.

  h. Minimum design requirements. The design of each ground system is unique to the particular facility
and the conditions present. However, a minimum set of requirements shall be considered for each
facility.

     (1) At each facility supplied by electric power, at least one ground rod should be installed near the
service disconnecting means and bonded to the earth electrode subsystem. If the transformer is located on
the site, a bare 1/0 AWG wire or cable should interconnect the ground rod at the transformer with the
earth electrode subsystem at the first service disconnect for lightning protection purposes.

     (2) For lightning protection purposes, all facilities large or small or located in areas of low or high
lightning incidence will require an earth electrode subsystem. Facilities having structural extensions or
equipment protrusions (such as antenna elements or towers) extending above the surrounding terrain
should have a continuous earth electrode subsystem enclosing each facility or should have individual
earth electrode subsystems connected together.

     (3) Most installations will require many interconnected ground rods. The configuration shown in
figure 3-1 is adequate for most facilities. (The number of ground rods actually required at a given
location will be determined by the resistivity of the soil and the configuration of the installation.) Three-
meter (10-foot) ground rods installed at 20-foot intervals around the perimeter of the structure provide
good utilization of the effective radius of the rod while providing several points of contact with the earth.
If longer rods are required to reach the water level, to make contact with lower resistivity soils, or to
penetrate below the frost line, greater spacings may be employed. The nominal spacing between rods
should be between one and two times the length of the rod; however, it is necessary for each lightning
down conductor to be connected to its own dedicated ground rod, so spacing should be limited to not
more than 50 feet in order to conform to lightning protection requirements.

                                                                                                                                         3-7


---

TM 5-690

             Figure 3-1. Earth electrode subsystem configuration for rectangular shaped facility
3-8


---

                                                                                                                                TM 5-690

      (4) The rods and interconnecting cable comprising the earth electrode subsystem should be
positioned 0.6 to 1.8 meters (2 to 6 feet) outside the drip line of the building or structure to insure that
rain, snow, and other precipitation wets the earth around the rods.

     (5) For facilities that do not conform to a rectangular or square configuration, lay out the rod field to
generally follow the perimeter of the structure. See figure 3-2 for an example.

     (6) When two or more structures or facilities are located in the same general area (less than 200 feet)
and are electrically interconnected with signal, control, and monitor circuits, either provide a common
earth electrode subsystem, or interconnect the separate earth electrode subsystems with two buried bare
cables. See figure 3-3 for an example. A common example of an installation where two separate
structures are involved is a radar or communications site where the equipment shelter is adjacent to the
antenna tower. Signal cables (both coaxial and waveguide), control cables, and power lines typically run
between the tower and the shelter. The tower, being taller than the shelter, is more susceptible to
lightning strikes. To minimize voltage differentials between the two structures, the facilities should
effectively share a common earth electrode subsystem. Separate structures spaced closer than 6 meters
(20 feet) should have a common earth electrode subsystem installed that encircles both facilities.
Structures or facilities having no interconnecting cables and separated by a distance greater than 60
meters (200 feet) generally do not require their earth electrode subsystems be interconnected.

     (7) There may be a number of incidental, buried, metallic structures in the vicinity of the earth
electrode subsystem. These structures should be connected to the subsystem to reduce the danger of
potential differences during lightning or fault protection; their connection will also reduce the resistance
to the earth of the electrode subsystem. Such additions to the earth electrode subsystem should include
the rebar in concrete footings, buried tanks and pipes.

     (8) To minimize resistance variations caused by surface drying of the soil and by the freezing of the
soil during winter and to minimize the possibility of mechanical damage to ground rods, connections, and
interconnecting cables, the tops of ground rods should be at least 0.3 meters (1.0 foot) below grade level.
Bury the bare 1/0 AWG interconnecting cable at least 0.45 meters (1.5 feet) below grade level.

     (9) If the subsystem is installed after foundations are poured, cables are installed, utility pipes
installed, etc., make proper provisions for performing the needed interconnections between the water
system, lightning down conductors, structural steel, buried lines and cables, and the electrodes.

     (10) Access to the earth electrode subsystem should be provided through the installation of one or
more grounding wells at each site. Two acceptable types of grounding wells are illustrated in figure 3-4.
Either clay pipe or poured concrete may be used. Removable access covers must be provided. In very
large structures, particularly those in which grounding grids are installed underneath, the grounding well
or wells may be located inside the building in an accessible location. More than one grounding well may
be necessary depending upon the size of the facility, the extent of the electrode subsystem, and the degree
of accessibility to the electrodes deemed desirable. Locate at least one of the ground wells in an area with
access to open soil so that resistance checks of the earth electrode subsystem can be made once the
building is in use.

  i. Typical components. Earth electrode subsystems can be divided into two general types, the most
preferable being a ring ground with 10-foot (3-meter) minimum length ground rods every 15 feet (4.5
meters). A second and less preferable type consists of a system of radials or grounds used when soil is
rocky or has extremely high resistivity. At sites where soil resistivity varies from high to very high and
frequent electrical storms are common, a combination of the two is recommended, i.e., a ring ground

                                                                                                                                         3-9


---

TM 5-690

              Figure 3-2. Earth electrode subsystem configuration for irregular shaped facility
3-10


---

                                                                                                       TM 5-690

Figure 3-3. Electrode configuration for closely adjacent structures
                                                                                                              3-11


---

TM 5-690

                                   Figure 3-4. Typical grounding well installation
around the building (worst case-grid under building) extending 2 to 6 feet (0.6 to 1.8 meters) outside the
drip line with radials or horizontal conductors extending to 125 feet (37.5 meters). With either system,
resistance to earth and danger of arc over can be greatly reduced by bonding any large metal objects in the
immediate area to the earth electrode subsystem. These include metal pipes, fuel tanks, grounded metal
3-12


---

                                                                                                                                TM 5-690

fences, and well casings. The advantages and disadvantages of each type of system are shown in table 3-
2.

      (1) Vertically driven ground rods or pipes are the most common type of made electrode. Rods or
pipes are generally used where bedrock is beyond a depth of 3 meters (10 feet). Ground rods are
commercially manufactured in 1.27, 1.59, 1.90 and 2.54 cm (1/2, 5/8, 3/4 and 1 inch) diameters and in
lengths from 1.5 to 12 meters (5 to 40 feet). For most applications, ground rods of 1.90 cm (3/4 inch)
diameter, and length of 3.0 meters (10 feet), are used. Copper-clad steel ground rods are required because
the steel core provides the strength to withstand the driving force and the copper provides corrosion
protection and is compatible with copper or copper-clad interconnecting cables.

     (2) Where bedrock is near the surface of the earth, the use of driven rods is unpractical. In such
cases, horizontal strips of metal, solid wires, or stranded cables buried 0.48 to 0.86 meters (18 to 36
inches) deep may be used effectively. With long strips, reactance increases as a factor of the length with
a consequent increase in impedance. Low impedance is desirable for minimizing lightning surge
voltages. Therefore, several wires, strips, or cables arranged in a star pattern, with the facility at the
center, is preferable to one long length of conductor.

     (3) Grid systems, consisting of copper cables buried about 15.24 cm (6 inches) in the ground and
forming a network of squares, are used to provide equipotential areas throughout the facility area. Such a
system usually extends over the entire area. The spacing of the conductors, subject to variation according
to requirements of the installation, may normally be 0.6 to 1.2 meters (2 to 4 feet) between cables. The
cables must be bonded together at each crossover. Grids are generally required only in antenna farms or
substation yards and other areas where very high fault currents are likely to flow into the earth and
hazardous step potentials may exist or soil conditions prohibit installation of other ground systems.
Antenna counterpoise systems shall be installed in accordance with guidance requirements of the
manufacturer.

     (4) Rectangular or circular plate electrodes should present a minimum of 0.09 square meters (2
square feet) of surface contact with the soil. Iron or steel plates should be at least 0.64 cm (1/4 inch) thick
and non-ferrous metals should be at least 0.15 cm (0.06 inches) thick. A burial depth of 1.5 to 2.4 meters
(5 to 8 feet) below grade should be maintained. This system is considered very expensive for the value
produced and is generally not recommended.

     (5) The metal frameworks of buildings may exhibit less than 10 ohms, depending upon the size of
the building, the type of footing, and particular location. Buildings that rest on steel pilings in particular
may exhibit a low impedance connection to earth. For this low resistance to be used advantageously, it is
necessary that framework be bonded together.

     (6) Metal underground pipes have traditionally been relied upon for grounding electrodes. The
resistance to earth provided by piping systems is usually quite low because of the extensive contact made
with soil. Municipal water systems in particular establish contact with the soil over wide areas. For water
pipes to be effective, any possible discontinuities must be bridged with bonding jumpers. The National
Electrical Code (NEC) requires that any water metering equipment and service unions be bypassed with a
jumper not less than that required for the grounding connector. However, stray or fault currents flowing
through the piping network into the earth can present a hazard to workmen making repairs or
modifications to the water system. For example, if the pipes supplying a building are disconnected from
the utility system for any reason, that portion connected to the building can rise to a hazardous voltage
level relative to the rest of the piping system and possibly with respect to the earth. In particular, if the
resistance that is in contact with the soil near the building happens to be high, a break in the pipe at even
some distance from the building may pose a hazardous condition to unsuspecting workmen. Some water

                                                                                                                                       3-13


---

TM 5-690

utilities are inserting non-conductive couplings in the water mains at the point of entrance to buildings to
prevent such possibilities. For these reasons, the water system should not be relied upon as a safe and
dependable earth electrode for a facility and should be supplemented with at least one other ground
system.

     (7) There may be a number of incidental, buried, metallic objects in the vicinity of the earth
electrode subsystem. These objects should be connected to the system to reduce the danger of potential
differences during lightning or power fault conditions: their connection will also reduce the resistance to
earth of the earth electrode subsystem. Such additions to the earth electrode subsystem should include the
rebar in concrete footings, buried tanks, and piping.

     (8) Well casing can offer a low resistance contact with the earth. In some areas, steel pipe used for
casing in wells can be used as a ground electrode. Where wells are located on or near a site, the
resistance to earth of the casing should be measured and, if below 10 ohms, the well casing can be
considered for use as a ground electrode.

  j. Installation practices. The installation of the system must be performed in conjunction with other
construction activities for the facility.

     (1) The schedule for installation must be such that any needed excavation, such as hole and trench
digging, can be performed while other excavating, clearing, and earth moving operations associated with
construction of the facility are in progress. If the subsystem is installed prior to completion of other earth
moving operations, take the precautions necessary to assure that the components are not damaged or
broken.

     (2) All metallic lines, such as water lines, sewer lines (if metal), armored cable, etc., must be bonded
to the earth electrode subsystem. Bonding jumpers of 1/0 AWG, or larger, bare copper wire are to be
used for this purpose.

     (3) Before covering the earth electrode subsystem with backfill dirt or otherwise rendering it
inaccessible, make visual checks of all joints and connections to check mechanical integrity, to verify the
absence of voids or other indications of poor bonding, and to see that all required interconnections are
made.

     (4) All bonds in concealed locations must be brazed or welded. Any bonds between dissimilar
metals, such as between a copper wire and cast iron or steel pipe, must be thoroughly sealed against
moisture to minimize corrosion. Bolted clamp connections are to be made only in manholes or in
grounding wells and are to be readily accessible for verification of integrity.

     (5) Drive rods only into undisturbed earth or into thoroughly tamped or compacted filled areas. Rods
and cables should be placed in the backfill around foundations only after the soil has been compacted or
has had adequate time to settle. Do not drive or lay rods in gravel beds which have been installed for
drainage purposes unless the rods extend through such beds far enough to provide at least 1.8 to 2.4
meters (6 to 8 feet) of contact with the undisturbed earth underneath. Do not lay horizontal cables in such
beds under any circumstances.

     (6) Rods may be driven either by sledgehammer or with the use of power drivers. Use driving nuts
to prevent damage to the driven end, particularly if two or more sections are to be joined. Deep driven
rods or those driven into hard or rocky soil generally require the use of power drivers with special driving
collars to prevent damage to the rod.

3-14


---

                                                                                                                                TM 5-690

     (7) Attach the interconnecting cable to the rods by brazing, welding, or clamping. Use bolted,
clamped-type connections only if the tops of the rods are accessible through grounding wells and a
periodic maintenance program is established to verify the integrity of the connection on a regular basis.

     (8) As rods are installed, make a one-time resistance check of each rod once it reaches its intended
depth. This subsystem should be visually inspected every 2 months, mechanically inspected every 12
months, and electrically tested every 24 months, per InterNational Electrical Testing Association’s
(NETA) guidelines. See text for specific recommendations. Use the fall of potential method outlined in
MIL-HDBK-419A, Grounding, Bonding, and Shielding for Electronic Equipment and Facilities. In this
way a continuous check is made of the electrode design. If the measured resistance of the rods is less
than the calculated resistance, the use of fewer rods may be acceptable as long as the minimum number
required for terminating lightning down conductors is installed. On the other hand, if the measured
resistance of the rods is greater than calculated, additional rods or longer rods should be installed during
the construction stage rather than waiting until the facility is completed to add additional rods.

  k. Inspections and testing. Inspection and testing of the system should be implemented as integral
elements of the facility during the construction of the building or structure. To ensure that the
implementation is accomplished in a timely manner, the construction efforts should be carefully
monitored from the onset of excavation through completion of the facility. Prior to acceptance of the
facility, the installation should be validated as acceptable using DA Form 7452-R shown in figure 3-5.
The following guidelines are provided to aid in the inspection and checkout of the facility.

     (1) Observe installation procedures. Specifically see that the requirements and recommendations
outlined above are observed. Verify that ground rods conform to specified sizes. If the ground rods are
driven in place, see that driving collars or nuts are used to prevent damage to the rods. Watch for bent
and broken or bulged couplings between sections. Seriously weakened or damaged couplings should be
replaced before driven below grade.

     (2) Spot-check the resistance of rods as they are driven. Use the fall-of-potential method to
determine the resistance of a rod when it reaches the design or specified depth. Project the net resistance
of the total number of ground rods. This projection should indicate if the planned electrode subsystem
will achieve 10 ohms (or less) resistance. As additional rods are driven, continue to spot check the
resistance of individual rods by measuring the resistance at each successive fourth or fifth rod. This
procedure will permit a decision to be made on the necessity for adjusting the electrode configuration
(either adding to or subtracting from) to achieve the required resistance.

     (3) See that cable interconnecting the rods is of a correct size (1/0 AWG). Inspect all connections
between cable sections and all interconnections between cable and ground rods. All connections to be
buried and subsequently made inaccessible must be welded or brazed. Restrict the use of clamps or
bolted connections to locations which will remain accessible.

     (4) Verify that provisions are made for interconnecting the earth electrode subsystem with metal
utility lines, buried tanks, and other underground metals.

     (5) Verify that risers or cables of appropriate size are installed for lightning down conductor, signal
ground, and power system ground connections. Ensure that risers used for lightning down conductors are
not used as part of the signal reference or fault protection subsystems.

                                                                                                                                       3-15


---

TM 5-690

1. FACILITY                       EARTH GROUN D ELECTRODE SUB SYST EM CHECKLI ST FOR N EW FACI LI TI ES

                                                            For use of this f orm, see TM 5-69 0; t he proponent agency is COE.

                                                                                                                              2. DATE (YYYYMMDD)

F ort Tank                                                                                                                                  2 00 202 28

3. LOCATION                                                                                                    4. INSPECTOR

B u ild in g 3 5 8                                                                                             Jo e Spa rks

5. SOIL RESISTIVITY (ohm-cm) (Obtain f rom site sur vey or f rom the meas ured res istance of a rod  6. RESISTANCE OF COMPLETED EART H ELECTRODE SUB SYSTEM (ohms)
or gr oup of r ods)
                                                                                                                                           5
                                     100

7. SKETCH OF FINAL EART H ELECTRODE SUB SYSTEM (Show dimensi ons, locations of ot her buri ed metal obj ects , ri sers for lightni ng, power, or si gnal ground connecti ons, and any ground well s.)
(Corrected engi neer ing draw ings may be attached in lieu of sket ch.)

                    S ee a tta ch ed d ra win g 00 1 -5 0-6 , 30 N o vem b er 2 0 0 1

COMPONENT IDENTIFICATION

8. GROUN D RODS                                        8b. SIZE                                                                         8c. NUMB ER OF ADDITIONAL RODS
8a. TYPE

                          co pp er stran d                                  1 " X 10 feet                                                                        2

8d. P OSIT IONED AN D IN STALLED AS SPECIFIED                                                        8e. PHYSICAL CONDITION

             YES              NO                                                                                                              n o d am ag e

9. GROUN D CONDUCT ORS                                 9b. SIZE                                                                         9c. MATERIAL
9a. TYPE

                         stra n d ed , b a re                                                        1 /0                                                        copper

9d. DISTANCE B ETWEEN TWO SUCCESSIVE GROUN D CONDUCT ORS                                                              9e. BURIED DEPTH

                                               6 feet                                                                                                    3 feet

10. IN TERCONNECTIN G CONDUCTORS                       10b. SIZE                                                                        10c. MATERIAL
10a. TYPE

                         stra n d ed , b a re                                                        1 /0                                                        copper

11. CON NECT ORS/FITT INGS                                        11b. MEASUREMENT OF RESISTAN CE B ETWEEN T WO CONNECTION POINTS
11a. PROPER TYP E/SIZE/MATERIAL AS SPECIFIED

             YES              NO                                                                                                        0 .1 o h m s

12. RISERS                                             12b. PROPERLY SIZED                                                              12c. LOCAT ED AS SPECIFIED
12a. PROPER LY INS TALLED

             YES              NO                                  YES                                      NO                                     YES                    NO

13. FUTURE INACCESSIBLE JOINTS AND CON NECT IONS                                                     13b. PR OPER LY CONNECTED
13a. PROPER LY INS TALLED

             YES              NO                                                                               YES                      NO

14. GROUND WELLS                                                                                     14b. MEASURED RESISTAN CE-TO-EARTH (ohms)
14a. IN STALLED AS SPECIFIED

             YES              NO                                                                                                            5

DA FORM 7452-R, FEB 2002                                                                                                                                                     USAPA V1.00

                                 Figure 3-5. Sample of completed DA Form 7452-R

       (6) Once the complete minimum system is installed, measure the resistance to earth for the system
using the fall-of-potential method. If the resistance is greater than 10 ohms, alternate methods as
described above for reducing the resistance-to-earth shall be considered.

       (7) Ensure that all changes or modifications are properly indicated on the facility drawings.

3-16


---

                                                                                                                                TM 5-690

     (8) Maintain a copy of all drawings, initial site surveys, checklists, and test data collected during
construction in the facility records department.

  l. Baseline configuration documentation. Documentation collected during the site surveys that provide
the basis for the site conditions should be maintained in the facility records for future reference.

3-3. Fault protection subsystem

An electrical system ground is the connection of the electrical system to earth in such a manner that will
limit the voltage imposed by lightning, line surges and unintentional contact with higher voltage lines;
and stabilize the voltage to earth during normal operation. An equipment ground is the connection of
conductive materials enclosing electrical conductors or equipment to limit the voltage to ground on these
materials. A grounded conductor is a system or circuit conductor, which is intentionally grounded. A
grounding conductor is a conductor used to connect equipment or the grounded circuit of a wiring system
to a grounding electrode or electrodes. The purpose of the equipment fault protection subsystem is to
ensure that personnel are protected from shock hazard and equipment is protected from damage or
destruction resulting from faults that may develop in the electrical system. To accomplish this, ground
connections must be adequate for both normal and fault currents and have sufficiently low impedance to
facilitate operation of overcurrent devices under fault conditions. The fault protection subsystem includes
the green wire and all exposed non-current-carrying metal parts of fixed equipment such as raceways and
other enclosures which are likely to be energized under power fault conditions. Any conductor used for
grounding purposes shall not penetrate any designated RF barrier, screen room, shielded enclosure etc.,
but shall rather be bonded to a welded stud on the barrier.

  a. Typical configuration. The equipment fault protection subsystem consists primarily of the
grounding conductors of the interior ac power distribution system. One of the major shortcomings in
grounding systems is the interconnection and reversal of ac neutral and equipment grounding conductors
of the ac power distribution at various power distribution panels and at equipment throughout a facility.
These installation errors result in additional electrical noise and ac currents in the ground system. The
equipment fault protection subsystem should generally follow a configuration from a central or main
ground point which ideally should be at the primary power station transformer ground point. If an
equipment grounding conductor is not available to the main ground point, the equipment grounding
conductor should be bonded directly to the earth electrode subsystem at the communications building.
The configuration consists of a central main or trunk lead from the power source with equipment
grounding conductors to the various intermediate power panels and equipment. The equipment grounding
conductor is carried along with the phase and neutral wires from the main ground point to the main circuit
breaker panel, from there to intermediate circuit breaker panels to the equipment panels, and finally to the
equipment.

  b. Design considerations. A power system fault is either a direct short or an arc (continuous or
intermittent) in a power distribution system or its associated electrical equipment. Figure 3-6 illustrates
how personnel hazards are developed by improper wiring and fault conditions. The grounding system for
transformers, switchgear, motors, etc. shall comply with the requirements of NEC® Article 250. These
faults are hazardous to personnel for several reasons:

     (1) Fault currents flowing in the ground system may cause the chassis of grounded equipment to be
at a hazardous potential above ground if not properly grounded.

     (2) The energy in a fault arc can be sufficient to vaporize copper, aluminum, or steel. The heat can
present a severe burn hazard to personnel.

                                                                                                                                       3-17


---

TM 5-690
     (3) There could be a fire hazard associated with any short circuit or arc.
     (4) Burning insulation can be particularly hazardous because of the extremely toxic vapors and

smoke which may be produced.
     (5) Common causes of electrical system faults are:
        (a) Rodents getting between ground and phase conductors

                                           Figure 3-6. Grounding for fault protection
        (b) Water infiltration
        (c) Moisture in combination with dirt on insulator surfaces
        (d) Breakdown of insulation caused by thermal cycling produced by overloads
        (e) Environmental contaminants
        (f) Damage during installation
        (g) System age deterioration

3-18


---

                                                                                                                                TM 5-690

     (6) For a motor supply if one phase of the 230-volt line accidentally contacts the motor frame, and
the motor is not grounded, its frame will rise to the circuit maximum phase-to-ground potential of 133
volts, and anyone coming in contact with it would be subject to a lethal shock if simultaneous contact is
made with a grounded object. To prevent this situation from arising, the motor frame must be grounded
via the equipment grounding conductor (green wire). The resistance of the fault path must be low enough
to permit the fault current to trip the overload protector and interrupt the fault. If the resistance of the
fault path is too large, the fault current will not be enough to trip the overload protectors. Thus to
minimize both shock and fire hazards, the resistance of the fault path must be as low as possible.
However, the fault protection subsystem normally does not depend on the earth electrode subsystem to
trip overcurrent devices. The fault current normally flows through the green wire (grounding conductor)
to the source side of the first service disconnect where the green wire and the neutral are tied together.
The fault current then flows through the neutral to the transformer to complete the circuit. This path
functions completely independent of the connection to the earth electrode subsystem. The earth electrode
subsystem functions to limit the voltage difference between personnel and equipment, and prevent system
voltage from rising above normal levels during fault conditions. The earth electrode subsystem is
connected to the ac power system at the supply transformer neutral and the service entrance disconnect.

     (7) Fault clearance in power distribution systems is normally provided by circuit breakers, fuses, or
overload relays in each phase. These devices provide protection only if the fault current is sufficient to
trip the over-current device. However, these protective devices may not act fast enough to protect
personnel during accidental direct contact with energized circuits.

     (8) Article 250-118 of the NEC® describes the types and materials used for equipment grounding
conductors. Types include solid and stranded (insulated or bare) wire or other shapes, such as metallic
tubes, pipes, and conduit. The grounding conductor types permitted by the NEC® also include various
metal ducts, cable trays, and raceways; however, these types shall not be used in lieu of the equipment
grounding conductors. The NEC® also permits/allows certain types of armored cable sheath be used as
grounding conductors.

  c. Typical components and installation details. The equipment fault protection subsystem consists
primarily of the grounding conductors of the interior ac power distribution system. The grounding
conductors are green insulated or bare wires running in the same conduit or duct with the neutral and
phase conductors. Dedicated grounding conductors are preferred to reduce electromagnetic interference
(EMI). Figures 3-7, 3-8, and 3-9 provide examples of equipment fault protection subsystems.

     (1) To protect personnel from exposure to hazardous voltages, all exposed non-current carrying
metallic elements located near the energized circuits shall be connected to ground. In the event of
inadvertent contact between the "hot" lead and chassis, frame, or cabinet through human error, insulation
failure, or component failure, a good, direct, known fault current path will be established to quickly
remove the hazard. Also, according to NEC®, Article 250-24, the neutral conductor should be grounded
at the service entrance disconnecting mean. If the transformer supplying the service entrance is located
outside the building, an additional grounding electrode should be installed at the transformer and the
grounded conductor of the transformer should be grounded to the newly added grounding electrode.
Buildings having two or more service entrances are bonded to the building’s common earth electrode
subsystem.

     (2) Metal boxes, fittings, and non-current-carrying metal parts of other fixed equipment do not
require additional protection if mechanically connected to the grounded cable armor or bonded to the
grounded members of the building. MIL-STD-188-124B, Grounding, Bonding and Shielding for
Common Long Haul/Tactical Communication Systems Including Ground Based Communications-
Electronics Facilities and Equipment, provides that the path to ground for circuits, equipment, and

                                                                                                                                       3-19


---

TM 5-690

                             Figure 3-7. Typical equipment fault protection subsystem
3-20


---

                                                                                                                                TM 5-690

                            Figure 3-8. Single-phase 120/240 volt ac power ground connection

conductor enclosures be permanent and continuous. The path must have (1) the capacity to conduct
safely any fault current likely to be imposed upon it, and (2) sufficiently low impedance to limit voltage
to ground and to aid the operation of circuit protective devices.

        (3) Experience with military communications equipment (CE) facilities has proven that a low-
noise, low-impedance equipment fault protection subsystem can be maintained over a prolonged period of
time if separately designed and installed with ground conductors. Therefore, a separate equipment fault
protection conductor shall be included with the ac power distribution if not provided in the power cable.
A grounding (green) wire should be used and installed in the same conduit as the other ac wires. When
ferrous ducts or conduits are used to shield the neutral and phase conductors, the lowest impedance will
result when this grounding conductor is installed in the same conduit. The impedance can be further
decreased if the grounding conductor is wrapped around the other conductors and bonded to the duct or
conduit at both ends. In a correctly installed power distribution system, there should be no power current
on the grounding conductor, except during an abnormal condition. It should be noted that there are two
types of abnormal conditions causing overcurrent devices to operate. The first is an overload condition in
equipment. In this case, the high current is on the neutral and phase leads. The second abnormal
condition is where a phase or hot lead is inadvertently grounded. The high current in this case is on the
hot lead and the grounding conductor. In both cases, the overcurrent protective device, usually a circuit
breaker, is opened in the phase or hot lead. Due to the high currents that can flow either on the phase
leads, neutral, or grounding conductor, it is recommended that a 2-inch separation be maintained between
power runs and signal runs when neither is in conduit.

     (4) Electrical supporting structures such as conduit, cable trays or raceways, wiring system
enclosures, and metallic power cable sheaths should be electrically continuous and are to be bonded to the
facility ground system at multiple points. In the event of a fault, this continuity will prevent these
structures from rising to a hazardous potential.

     (5) For service entrances, the ac neutral lead can be grounded at the first service disconnect means.
In this case, the ac neutral also serves as a grounded conductor back to the source. For best results, the ac
neutral (grounded) and green (grounding) wire should be grounded at the service transformer and the first

                                                                                                                                       3-21


---

TM 5-690

                  Figure 3-9. Three-phase 120/208 volt ac power system ground connections
service disconnect means through the five-wire distribution system. All distribution neutrals are to be
isolated from equipment and structural elements except for the connection at the first service disconnect.
If a single common service supplies two or more separate buildings, the connection to the grounding
electrode and grounding or bonding of equipment, structures or frames required to be grounded or bonded
must be accomplished in different ways, depending on whether the equipment grounding conductor is
installed with the supply or is not installed with the supply. If a single service is installed with an
equipment grounding conductor to a second building, the grounded conductor (neutral) is not permitted to
be connected to the equipment grounding conductor or the grounding electrode system as shown in figure
3-10. If a single service is not installed with an equipment grounding conductor to a second building, the
grounded conductor (neutral) is permitted to be connected to the equipment grounding conductor or the
grounding electrode system as shown in figure 3-11.

     (6) Connect the ground terminals of convenience outlets to the facility ground system with the green
wire specified by the NEC®. Do not use “wiremold” or “plugmold” distribution strips, which depend
upon serrated or toothed fingers for grounding. “Wiremold” or “plugmold” is commonly used to supply
high-density 120V receptacles for laboratories and work areas. Wiremold Company catalog number V20-
C2 illustrates this product. Effectively ground the ground terminals on such strips with an auxiliary
grounding conductor equivalent to the green wire requirements of Article 250 of the NEC®.

     (7) For a direct current (dc) power system, ground one leg with a single connection to the earth
electrode subsystem. The NEC® requires all two-wire dc systems operating between 50 to 300 volts be
grounded, and requires all three-wire dc systems to be grounded. The size of the grounding conductor

3-22


---

                                                                                                                                TM 5-690

             Figure 3-10. Single service entrance with common equipment grounding conductor

shall not be smaller than the largest conductor for two-wire dc systems, and shall not be smaller than the
neutral conductor for all three-wire dc systems. Whether grounded at the source, the first system
disconnection means or overcurrent device, or by other means that accomplish equivalent system
protection, provide a dedicated current return conductor from the load to the source to assure that the dc
load current in the facility ground system or the lower frequency signal ground network is minimized.

     (8) On-site power generation requires grounding. The frames and housing of ac standby generators
should be grounded as prescribed by the NEC®. Ground the neutral to the facility main ground plate or
to the earth electrode subsystem, whichever is closest. When generators are connected in parallel,
interconnect the neutrals and ground them to the facility’s earth electrode subsystem with a common
grounding conductor.

     (9) For metal poles supporting outdoor lighting fixtures, ground pole to a grounding electrode in
addition to separate equipment grounding conductor run with supply branch circuit.

     (10) Bond grounding conductors, including grounding-conductor conduits, to lightning protection
down conductors or lightning protection grounding conductors in compliance with National Fire
Protection Association (NFPA) 780, Standard for the Installation of Lightning Protection Systems (1997).
Bond electric power system ground directly to lightning protection system grounding conductor at closest
point to electric service grounding electrode. Use bonding conductor sized same as system grounding
conductor and install in conduit.

     (11) Electrical raceways require grounding to ensure the complete low impedance path to ground is
maintained. The conduit is grounded to the power panel at each end, but it is not used in lieu of a
grounding conductor, which continues through the conduit to the equipment ground bus bar.

                                                                                                                                       3-23


---

TM 5-690

           Figure 3-11. Single service entrance without common equipment grounding conductor
        (a) All metal conduit is to be grounded, regardless of whether it is used for enclosing power
cables or for signal and control cables.
        (b) All joints between sections of conduit and between conduit, fittings, and boxes should be
made electrically continuous when they are installed.
        (c) All pipe and locknut threads should be thoroughly cleaned before they are engaged and then
tightened firmly.
        (d) Gouging locknuts must positively penetrate all paint or other non-conductive finishes.
        (e) Any joints not inherently continuous should be bonded with jumpers of No. 12 AWG or larger
copper wire. These jumpers should be welded or brazed in place or attached with clamps, split bolts,
grounding bushings, or screws and lockwashers.
        (f) Protect the bonds against weather, corrosion, and mechanical damage.
        (g) Firmly tighten the screws on the cover plates of pull boxes, junction boxes, and outlet boxes.

3-24


---

                                                                                                                                TM 5-690

        (h) All conduit brackets and hangers should be securely bonded to both the conduit and to the
structural member to which they are attached. Bond conduit runs, to include the individual sections,
couplings, line fittings, pull boxes, junction boxes, outlet boxes, etc., to the facility ground system should
be at intervals not exceeding 15 meters (50 feet). The resistance to each connection should not exceed 5
milliohms.

         (i) All cable tray systems shall be electrically continuous by bonding together each individual
section. Bond each support bracket or hanger to the cable trays which they support. Connect the cable
tray assemblies to the facility ground system with copper cables or equivalent conforming to the 2000
cmil per foot criterion. Make the connections within two feet of each end and at intervals not exceeding
15 meters (50 feet) along the run. Where metal covers are used, they should be securely bolted in place.

     (12) All metallic pipes and tubes (including conduit) and their supports should be electrically
continuous and are to be bonded to the facility ground system at least at one point. If any run of metal
pipes or tubes exceeds 3 meters (10 feet) in length, it should be bonded to the facility ground system at
each end. Also, longer runs should be bonded to the facility ground system at intervals of approximately
45 meters (150 feet).

         (a) At indoor locations, these bonds may be made with clamps which provide continuous
pressure. Pipes installed out of doors should be bonded to the facility ground system at entry point or
wherever feasible by welding or brazing. Compatible stainless steel straps may be used with stainless
steel pipe. In the event that a direct bond cannot be made, zinc-plated hose clamps or stranded, bare
copper, untinned bond straps may be used. All bonds should be adequately protected against corrosion in
humid or corrosive environments.

         (b) Joints in metal pipes and tubes should have a dc resistance no greater than 5 milliohms. In
the case of threaded joints, the threads should be cleaned and firmly tightened (200 ft-lbs for rigid wall
conduit) and protected against corrosion. Leaded or caulked joints, flared and other compression fittings,
and 0-ring fittings should all be measured to verify that the joints have a dc resistance no greater than 5
milliohms.

     (13) Other equipment/installations requiring grounding and bonding include the following.

         (a) The frames of motors, generators, and other types of electrical rotating machinery are to be
connected to the facility ground system in accordance with the NEC requirements.

         (b) Ground all enclosures of electrical and electronic wiring and distribution equipment in
accordance with NEC® Article 250.

         (c) The armor on electrical power cables should be bonded to the facility ground system at each
end if the cables are 3 meters (10 feet) or longer. Provide supplemental connections at intervals not
exceeding 15 meters (50 feet). The resistance of each connection should not exceed 5 milliohms.

         (d) To protect personnel from exposure to hazardous voltages, all exposed metal elements of
equipment and supporting structures shall be interconnected by an equipment grounding conductor (green
wire) from the ac power distribution system and referenced back to the power source. The grounding
requirements of a transportable facility installed in the field and operating from transportable engine
generators is relatively simple. The primary requirement is to ensure that all vans, vehicles, trailers, and
engine generator units are interconnected through an equipment grounding conductor (green wire)
network, and the power neutral is grounded from a common bus that is connected to an earth electrode at
the generator. Where parts are moveable or subject to vibration, metal straps may be used in lieu of the
green wire. When transportable equipment is powered from a commercial base ac source or is integrated

                                                                                                                                       3-25


---

TM 5-690

into a permanent installation with non-transportable equipment, personnel protection requirements
become more complex. When part of a fixed installation, the transportable equipment shall be integrated
into the facility ground system by extending the earth electrode subsystem to provide connections for the
transportable equipment. All metallic components of the transportable equipment shall be interconnected
through the equipment fault protection subsystem and bonded to the earth electrode subsystem at the main
power panel, or back to the primary power source through the ground conductor of the power distribution
cable.

  d. Inspections. Inspections of the fault protection subsystem should be implemented as integral
elements of the facility during the construction of the building or structure. To ensure that the
implementation is accomplished in a timely manner, the construction efforts should be carefully
monitored. Prior to acceptance of the facility, the installation should be validated as acceptable using DA
Form 7452-1-R shown in figure 3-12. The following guidelines are provided to aid in the inspection and
checkout of the facility.

     (1) Specifically see that the requirements and recommendations outlined in paragraph 3.3.c. (1)
through 3.3.c. (13) are observed. Verify that grounding conductors conform to the sizes specified.

     (2) Verify that the grounding conductors are routed along the shortest and straightest paths possible,
except as otherwise indicated. Avoid obstructing access or placing conductors where they may be
subjected to strain, impact, or damage.

     (3) Verify that any underground ground conductors are bare copper wire sized as specified and are at
least 24 inches (600 mm) below grade.

     (4) Verify bonds to metal water pipes.

     (5) Verify that bonds have been made to pipes of each interior metal piping system present and to
metal air ducts. These bonds shall be located between equipment grounding conductors of associated
pumps, fans, blowers, electric heaters, and air cleaners. Bonds shall be made by using braided-type
bonding straps.

     (6) Verify that connections are made with galvanically compatible materials.

     (7) Verify exothermic-welded connections comply with manufacturer's written instructions. Welds
that are puffed up or that show convex surfaces indicating improper cleaning are not acceptable.

     (8) Verify proper lugs are used for the appropriate cable size.

     (9) Verify conduits are properly terminated and bonded to the metal housings. Verify the conduit to
be electrically non-continuous and that both entrances and exits are properly bonded with grounding
bushings and bare grounding conductors, except as otherwise indicated.

     (10) Verify that screws and bolts for grounding and bonding connectors and terminals are installed
in accordance with manufacturer's published torque-tightening values. Where these requirements are not
available, use those specified in Underwriters Laboratories (UL) UL 486A, Wire Connectors and
Soldering Lugs for Use with Copper Conductors, Ninth Edition (1998), and UL 486B, Wire Connectors
for Use with Aluminum Conductors, Fourth Edition (1997).

3-26


---

                                                                                                                                                      TM 5-690

1. FACILITY                             GROUND FAULT PROTECTI ON SUBSYSTEM CHECKLI ST FOR NEW FACI LI TI ES

                                                                 For use of this form, see TM 5-690; the proponent agency is COE.

                                                                                                                               2. DATE (YYYYMMDD)

F ort Tank                                                                                                    2 00 202 28

3. LOCATION                                                                                  4. INSPECTOR

Buildin g 19 29                                                                              Lou Sw ire

5. SKETCHTHE LAYOUT OF THE ACTUAL ELECTRICAL GROUNDFAULT PROTECTION SUBSYSTEM. IF AN ENGINEERING DRAWING EXISTS, UPDATE IT WITHTHE ACTUAL DATA. THIS
SHOULD INCLUDE ALL GROUNDED (Neutral) ANDGROUNDING (Gr een) CIRCUITS FROM THE MAIN INPUTS (Feeding the facility) TO THE LOAD CIRCUITS.

                          S ee a tta ch ed d ra win g 00 1 -5 0-6 , 30 N o vem b er 2 0 0 1

6. CHECK ALL GROUNDEDCIRCUITS FOR PROPER INSTALLATION, CONTINUITY, AND CORRECT TYPES, SIZES, AND MATERIAL AS SPECIFIED. RECORD ALL DEFICIENCIES.

               LOCATI ON                                                                     DEFI CI ENCI ES

P a n el A -3                           G r o u n d e d c o n d u ct o r i s s i ze # 2 i n st e a d of 2 /0 a s sp ec i f i e d i n D W G E E -1

P a n el B -5                           G ro u n d in g c o n du c to r d o e s n o t ru n in sa m e c o nd u it a s p ha se s c o n d uc to r

P a n el C -7                           N o g ro u n d b u s e x i s t s. A l l g re e n c o n d uc t o r s w e r e co n n e c te d t o n e u t ral b u s .

7. CHECK ALL ELECTRICAL GROUNDFAULT PROTECTION COMPONENTS/DEVICES FOR SIGNS OF OVERHEATING, BURNING, RODENT, WATER INFILTRATION, ENVIRONMENTAL
CONTAMINANTS, AND INSULATION DAMAGE. RECORD ALL UNDESIRABLE SITUATIONS.

               LOCATI ON                                                                     DAMAGE

P a n el E -1                           G rou nd b us has sig ns o f burnin g
P a n el E -3                           N eutral bu s corro ded

8. DETERMINE ANDRECORD CONNECTION TOEARTHELECTRODE SUBSYSTEM

                             LOCATI ON                                 CONNECTI ONS                                                    CONDUCTOR SIZES

M a in sw itc h g e a r                 G rou nd b us of SW G                                              (3 ) 5 0 0 M C M
G en switchgea r                        G rou nd b us of SW G                                              (3 ) 5 0 0 M C M

9. MEASURE ANDRECORD THE NEUTRAL AND GROUNDCURRENTS AT ALL PANEL BOARDS

                 LOCATI ON                                          CURRENT READING                                                            NOTES

P a n el A -2                           I(N ) = 3 0 A , I(G ) = 0 .5 A                                     S u p p ly Wa reh o use B -1
P a n el B -4                           I(N ) = 5 0 A , I(G ) = 1 0 A                                      S u p p ly A D P R oo m B -5
P a n el C -6                           I(N ) = 4 2 A , I(G ) = 0 .7 A                                     S u p ply BO Q 3

DA FORM 7452-1-R, FEB 2002                                                                                                                                         USAPA V1.00

                                     Figure 3-12. Sample of completed DA Form 7452-1-R

       (11) For compression-type connections verify that the proper hydraulic compression tools provide
correct circumferential pressure for the connectors. Verify the tools and dies are as recommended by the

                                                                                                                                                             3-27


---

TM 5-690

manufacturer of the connectors. Provide embossing die code or other standard method to make a visible
indication that a connector has been adequately compressed on grounding conductor.

       (12) Insure that all changes or modifications are properly indicated on the facility drawings.

  e. Tests. Testing shall be performed by qualified and trained personnel.

       (1) The following safety precautions should be followed when testing the ground system.

          (a) When testing earth resistance, remember that during fault conditions, dangerous voltages
may exist between a system ground and a remote point being tested. Care should be taken when
connecting leads and test equipment. Avoid as much contact with the leads and probes as possible.

          (b) Most of the earth resistance is located close to the grounding system due to the “hemisphere
effect.” Around a grounding hemispherical electrode, the resistance of the soil is the sum of the series
resistances of virtual shells of earth, located progressively outward from the electrode. The shell nearest
the electrode has the smallest circumferential area or cross section, so it has the highest resistance.
Successive shells outside this one have progressively larger areas, and thus progressively lower
resistances. As the radius from the electrode increases, the incremental resistance per unit of radius
decreases effectively to nearly zero. When a ground fault occurs, the majority of the voltage drop is close
to the system. Caution should be used when approaching a live ground.

          (c) At stations where the fence is not connected to the station ground, a dangerous voltage can
develop under fault conditions between the fence and station ground. Do not touch both at the same time.

          (d) Surge and switching effects in transmission lines may induce dangerous spikes in the test
leads strung under the line. Care should be exercised in handling these test leads.

          (e) Tests should not be performed during a thunderstorm.

          (f) Rubber gloves, boats, an insulated platform, etc., capable of protecting the operator against
full-line voltage, are recommended for protection.

     (2) The completed grounding system shall be megger tested at each location where a maximum
ground-resistance level is specified by the installation design documents, at service disconnect enclosure
grounding terminal, and at ground test wells. Measure ground resistance not less than 2 full days after the
last trace of precipitation, and without the soil being moistened by any means other than natural drainage
or seepage and without chemical treatment or other artificial means of reducing natural ground resistance.
Perform tests by the two-point method according to IEEE 81, Guide for Measuring Earth Resistivity
Grounding Impedance and Earth Surface Potentials of Ground Systems (1983). The two-point method
provides a pass/fail indication of ground resistance and is easier to perform than the three-point method.
Maximum grounding to resistance values are as follows.

             (a) Equipment rated 500 kVA and less: 10 ohms

             (b) Equipment rated 500 to 1000 kVA: 5 ohms

             (c) Equipment rated more than 1000 kVA: 3 ohms

             (d) Unfenced substations and pad-mounted equipment: 5 ohms

3-28


---

                                                                                                                                TM 5-690

             (e) Manhole grounds: 10 ohms

       (3) Measure the ground path resistance of all branches of the grounding system from the point of
connection, on the structure, equipment enclosure, or neutral conductor, to the earthing connection. The
earthing connection may be the top of a single ground rod, a water pipe, a counterpoise, or a ground grid.

       (4) Measure the resistance of the earthing connection whether it is a ground rod, a water pipe, a
counterpoise, or a ground grid to the earth itself.

       (5) Wherever the total resistance of the total ground circuit is in excess of the values established,
measure resistance of individual portions of the circuit to determine the point or points where resistance is
excessive and corrective action can be taken.

       (6) Measure resistance between gates and gateposts to ensure that flexible ground connections are
adequate. Resistance higher than one-half ohm indicates a deficiency.

       (7) Measure resistance between operating rods and handles of group-operated switches and the
supporting structure to determine that the flexible connections are adequate. Resistance higher than one-
half ohm indicates a deficiency.

       (8) Measure resistance of all bonds between metallic-cable sheathing and its ground path.
Resistance higher than one-half ohm indicates a deficiency.

       (9) All methods of measuring ground resistance are similar in that a suitable source of current is
necessary. Auxiliary reference grounds and test instruments are necessary for American National
Standards Institute (ANSI)/Institute of Electrical and Electronics Engineers (IEEE) ANSI/IEEE 80, IEEE
Guide for Safety in AC Substation Grounding, methods. The following methods are suitable for
measuring the resistance of isolated ground rods or small grounding installations. Precision in
measurements is difficult to obtain. Normally an accuracy of 25 percent is sufficient, since the
surrounding soil will not have consistent values of temperature, moisture, and depth.

         (a) A usual way to measure the ground resistance is with a low-range, self-contained, portable
earth-tester instrument such as the “Megger” ground tester. The manufacturer’s instructions should be
followed in the use of this instrument.

         (b) The resistances of the ground circuits are determined from the meter readings and these
values are then used in calculating resistance (R). Stray alternating currents (ac) of the same frequency as
the test current, if present, will introduce some error in measurements.

         (c) Where accurate measurements of extensive low-resistance grounding systems are required,
more elaborate test methods and equipment are needed using considerably larger separation distances
between test electrodes. Normally large facility substations are tested with the fall-of-potential method.

         (d) To allow for seasonal variations it is recommended that tests be made at the same time each
year or for each season of the year to allow for accurate comparison.

          (e) Tests should be performed in accordance with written procedures. Provide adequate safety
precautions as all electrical conducting paths for overvoltage and fault currents are connected to the
substation grid.

                                                                                                                                       3-29


---

TM 5-690

      (11) Maintain a copy of all drawings, initial site surveys, checklists, and test data collected during
construction in the facility records department. Prepare test reports, certified by the testing organization,
of ground resistance at each test location. Include observations of weather and other phenomena that may
affect test results. Describe measures taken to improve test results.

3-4. Lightning protection subsystem

A lightning protection subsystem is frequently installed to protect the structure, personnel, and equipment
of the C4ISR facility from damage due to lightning discharges. A major element of this protection is
achieved by providing a means by which a lightning stroke can bypass the facility and enter the earth
without causing damage. The stroke current must first be intercepted before it penetrates the structure.
Air terminals are provided for this purpose. Preferential paths must then be offered which the stroke
current will follow instead of any others. To provide these preferred paths, down conductors are designed
to have large diameters and are routed to be as straight and short as possible. Finally, a low impulse
impedance connection with the earth must be made.

  a. Typical configuration. To provide the most effective safeguard, a lightning-protection system must
be appropriate for the type of structure and its construction characteristics. It has been shown that a
modest lightning stroke of 10,000 amperes (A) develops a 2,000 kV voltage when it terminates on the
phase conductor of a transmission line. Obviously, lines and equipment cannot be insulated to withstand
voltages in this range. A more practical alternative is to limit voltages to a much lower level. This
involves two basic principles - the use of masts and overhead ground wires to shield equipment and
circuits from direct strokes; and the application of arresters to limit surge voltages to levels well below
practical equipment insulation levels.

     (1) The oldest and most commonly used protection method is the conduction system, sometimes
termed as the Franklin Rod or Faraday Cage system.

        (a) Air terminals (lightning rods) on the structure roof are connected to a grid of interconnecting
(coursing) conductors, which connect to down conductors that extend down to earth and connect to
appropriate grounding electrodes. The grounding electrodes can be individual ground rods or a
conductive ring buried around the building perimeter or both.

        (b) All system components are made of copper, anodized aluminum, or stainless steel.

        (c) To complete the conventional lightning-protection system installation, all metallic elements
(roof fans, vents, etc.), grounded or isolated, which are located on the roof or in the exterior walls near the
down conductors, must be bonded to the down conductors because the possibility of a sideflash exists. A
sideflash is an arc caused by a difference in potential between a down conductor and a metallic element.
The bonding eliminates potential difference and prevents high current flow from damaging these
components.

     (2) Recent changes in standard guidelines have redefined the outline of the zone protected by any
one standard air terminal. Originally, the accepted standard indicated that the area protected was defined
by a 60° cone starting at the tip of the air terminal, surrounding the terminal, and extending to earth,
without regarding the terminal height. Now, however, research and better data define the protected zone
as an area under an arc that has a maximum radius of 150 feet and is tangent to the earth while touching
the tip of an air terminal. This is important for structures exceeding 150 feet in height because additional
air terminals must be installed at an appropriate intermediate level, as well as at roof level. Figure 3-13
illustrates the 150-foot radius of protection.

3-30


---

                                                                                                                                TM 5-690

                                      Figure 3-13. 150-foot radius of protection

     (3) Other protection requirements for high-rise buildings include the electrical interconnection of the
steel column components or installation of conductive loops around the building at vertical intervals not
exceeding 60 feet. A bonding conductive loop must also be made at ground level and at roof level.
Furthermore, all grounded building elements (roof fans, vents, etc.) on building exterior walls within 12
feet of the main roof must be connected to the protection system. Also, buildings over 75 feet high must
use larger system components per the requirements of the Standard for the Installation of Lightning
Protection Systems, NFPA 780.

  b. Design considerations. The degree to which lightning protection is required, is a subjective decision
requiring an examination of the relative criticality of the structure location and its contents to the overall
mission of the facility. Those structures containing elements vital to the operational mission such as air
traffic control towers, radar installations, navigational aids, and communications centers are examples of
facilities, which obviously must be protected. However, every building or structure does not require that
a lightning protection system be installed. For example, buildings primarily used for the storage of non-
flammable materials do not have a critical need for protection. Three of the factors to consider in
ascertaining whether a given structure should have a lightning protection system installed or in
determining the relative comprehensiveness of the system are the relative threat of being struck by
lightning, the type of construction, and the nature of the facility.

     (1) The relative likelihood of a particular structure being struck by lightning is a function of the
isokeraunic level, i.e., the thunderstorm activity of the locality and the effective height of the structure.
Average thunderstorm activity can be determined from isokeraunic maps. Figure 3-14 shows the mean
annual number of days with thunderstorms based on the period 1948-1972. The frequency of strikes can
then be estimated. Use this estimation as one of the inputs to the decision process.

     (2) A structure, for lightning protection purposes, is defined as a building mast, tower, or similar
self-supporting object other than power lines, power stations, and substations. To provide minimum

                                                                                                                                       3-31


---

TM 5-690

       Figure 3-14. Mean annual number of days with thunderstorms based on the period 1948-1972
3-32


---

                                                                                                                                TM 5-690

protection for structures against direct lightning strikes, four requirements must be fulfilled - an air
terminal must be provided to intentionally attract the leader stroke, a path must be established that
connects this terminal to earth with such a low impedance that the discharge follows it in preference to
any other, a low resistance connection must be made with the earth electrode subsystem, and a low
impedance interface must be established between the earth electrode subsystem and earth. Steel frame
buildings with metal outer coverings offer the greatest inherent protection against lightning damage.
Steel towers also exhibit a high immunity to structural damage. Additional protection for these type
buildings will probably be required only for very critical facilities in highly exposed locations. Steel
frame buildings with non-conductive, but non-flammable, outer coverings (like brick or other masonry)
also offer a high degree of protection against lightning damage. The greatest hazard is posed by pieces of
masonry being dislodged by stroke currents passing through the outer coverings to reach the structural
steel underneath. Minimal protection consisting of interconnected air terminals to down conductors and
steel support columns will be sufficient to prevent this type of structural damage. Buildings constructed
of non-conductive materials such as wood, concrete blocks, or synthetic materials are the most susceptible
to destructive damage. A complete auxiliary protection system will be required to prevent lightning
damage to buildings utilizing this type of construction.

       (3) Methods used to protect outdoor equipment vary depending on the location of the equipment.
If the equipment were located in close proximity to a structure, which is being protected, it would be
prudent to include the equipment protection within the zone of influence of the structure. Otherwise this
equipment may be protected in the same way as overhead lines, transmission lines, substations, or high
towers. In these cases a protective shielding cable sometimes called a “skywire” is usually installed. It is
a well-grounded bare conductor, usually mounted several feet above the conductors or equipment to be
protected. When lightning strikes in the vicinity, induced voltage surges tend to be carried by the
shielding skywire instead of the protected conductors or equipment.

  c. Protection components and installation details. Lightning protection systems are typically
comprised of the following major components.

       (1) Air terminals (lightning rods) must intercept, or divert to themselves, any lightning stroke that
might otherwise strike the building or structure being protected. Antennas and their associated
transmission lines/supporting structures shall be protected by air terminals rather than be dependent upon
transient protection/suppression devices.

         (a) Erect air terminals on the points of highest elevation and on other exposed areas to intercept
the stroke before it has an opportunity to damage the structure, equipment, or components mounted
thereon. The terminal points must be placed high enough above the structure to eliminate the danger of
fire from the arc.

         (b) To keep from exploding, igniting, or otherwise being destroyed, air terminals should be made
of copper, aluminum, brass, or bronze. The minimum sizes are 1.27 cm (1/2 inch) in diameter for solid
copper, brass, or bronze rods and 1.6 cm (5/8 inch) in diameter for solid aluminum rods.

         (c) Air terminals must extend at least 25.4 cm (10 inches) directly above the object being
protected and be of sufficient height so as to provide a 1:1 zone of protection for adjacent objects
(antennas and associated support/control towers, etc). Rather than choosing the shortest terminal, which
will provide this minimum height, all parts of the structure must be checked graphically or analytically to
determine if the zone of protection provided by the terminal is adequate. Where taller terminals are
required to provide complete protection, adequate support and bracing must be provided.

                                                                                                                                       3-33


---

TM 5-690
         (d) Where air terminals are mounted on or very near [less than 1.5 meters (5 feet)] to vents or

stacks that emit potentially explosive or ignitable dusts, vapors, or gases, provide additional clearance.
Over hooded vents emitting explosive substances under natural draft, the air terminals should extend at
least 1.5 meters (5 feet) above the opening. Above open stacks emitting explosive substances under
forced drafts, air terminals should extend at least 4.5 meters (15 feet) above the opening.

         (e) Locate air terminals along the ridges of gable, gambrel, and hip roofs as shown in figures 3-
15 and 3-16. Place them on the corners and along the edges of gently sloping roofs having a span of 40
feet or less with a rise-to-run ratio, i.e., pitch, of one-eighth or less or having a span greater than 40 feet
and a rise-to-run ratio of one-quarter or less.

         (f) On flat roofs position the air terminals around the perimeter as shown in figure 3-17. Provide
additional air terminals placed at 50-foot intervals over the interior of flat and gently sloping roofs which
exceed 50 feet in width.

         (g) Terminals are to be provided within 2 feet of corners, the end of ridges, or edges of main
roofs.

         (h) Terminals less than 24 inches in height are to be spaced 20 feet or less. Terminals 24 inches
or taller may be placed at intervals not exceeding 25 feet.

                          Figure 3-15. Location of air terminals on gently sloping roofs

3-34


---

                                                                                                   TM 5-690

Figure 3-16. Location of air terminals for common roof types
                                                                                                          3-35


---

TM 5-690

                          Figure 3-17. Air terminal placement on flat-roofed structures
3-36


---

                                                                                                                                TM 5-690

         (i) Ensure that no part of the structure extends outside the zone of protection established by the
air terminals. For structures with multiple-level roofs no more than 50 feet (15 meters) in height, the zone
of protection shall form a cone having an apex at the highest point of the strike termination device, with
walls forming approximately a 45-degree (1:1 slope) or 63-degree (1:2 slope) from the vertical.
Structures that do not exceed 25-feet (7.6 meters) are considered to protect lower portions of a structure
located in a one-to-two (1:2) zone of protection as shown in figures 3-18 and 3-19. Structures that do not
exceed 50-feet (15.24 meters) are considered to protect lower portions of a structure located in a one-to-
one (1:1) zone of protection as shown in figures 3-20 and 3-21.

                       Figure 3-18. Lower roof protection for flat roof 25-feet or less high

         (j) Structures that do not exceed 150-feet shall determine the zone of protection by the space not
intruded by a rolling sphere having a radius of 150-feet (46 meters). When the sphere is tangent to earth
and resting against an air terminal, all space in the vertical plane between the two points of contact and
under the sphere are in the zone of protection. A zone of protection is also formed when such
a sphere is resting on two or more air terminals. This zone shall also include the vertical plane under the
sphere and between those devices, as shown in figure 3-13. All possible placements of the sphere must be
considered when determining the zone of protection using the rolling sphere model.

         (k) Structures greater than 150-feet (46 meters) above earth or above a lower air terminal shall
determine the zone of protection to be the space in the vertical plane between points of contact and under
the sphere when the sphere is resting against a vertical surface of the structure and the lower air terminal
or earth. The zone of protection shall be limited to the space above the horizontal plane of the lowest air
terminal unless it can be extended by further analysis, such as in rolling the sphere to be tangent to earth.

     (2) To provide effective protection, it is of utmost importance that a low-impedance path to ground
exists. This applies to all components and connections from the air terminals to the grounding electrodes.

                                                                                                                                       3-37


---

TM 5-690

            Figure 3-19. Lower roof protection provided by pitched roof 25-feet or less high
Low impedance is essential so that the huge currents involved will follow the design path in preference to
alternative paths offered by building materials such as wood, brick, tile, stone, or concrete. When
lightning follows these higher impedance paths, extensive damage may be caused by the heat and
mechanical forces generated during the passage of the lightning discharge. A low-impedance path
reduces the potential difference between the storm system, the earth, and the protection to the point where
a stroke does not occur or at least is somewhat controlled. Even with installations built on solid rock, an
extensive low-impedance ground electrode/system is required, as well as solid connections between
components and earth. Standards do not call out a specific ohmic ground value; however, every effort
must be made to obtain the lowest value possible. The down conductors from the air terminals to the
earth connections provide this low impedance path.

         (a) Install roof and down conductors so that they offer the least possible impedance to the
passage of stroke currents between the air terminals and the earth. The most direct path is the best. The
radius of conductor bends shall not be less than 8 inches nor shall the angle of such bends be less than 90
degrees.

         (b) Course down conductors over the extreme outer portions of the structure and separate them as
far apart as possible. Preferred locations are at diagonally opposite corners on square or rectangular
structures and symmetrically distributed around cylindrical structures.

         (c) Locate down conductors as close as practical to air terminals and to the most convenient
places for attaching the conductors to the earth electrode subsystem of the structure. The down
conductors should be equally and symmetrically spaced about the perimeter of the structure.

3-38


---

                                                                                                                                TM 5-690

                       Figure 3-20. Lower roof protection for flat roof 50-feet or less high
         (d) At least two down conductors are required on all structures except on slender objects like
flagpoles, antenna masts (not substantial towers), light poles, and the like.
         (e) Provide one additional down conductor for each additional 30 meters (100 feet) or fraction
thereof on structures having a perimeter exceeding 75 meters (250 feet). On structures having flat or
gently sloping roofs and on irregular-shaped structures, the number of down conductors should be such
that the length of the average roof conductor joining them does not exceed 30 meters (100 feet). The
spacing between down conductors need not be less than 15 meters (50 feet).
         (f) Down conductors are to be provided or located appropriately to avoid dead ends in excess of
4.8 meters (16 feet) in length. See figure 3-22, note 1.
         (g) Maintain down conductors in a downward course with routing around or through any
obstruction which may lie in the path. Sharp bends or turns are to be avoided with necessary turns limited
to not less than 90 degrees and not less than 20 cm (8 inches) in radius.

                                                                                                                                       3-39


---

TM 5-690

                     Figure 3-21. Lower roof protection for pitched roof 50-feet or less high

                                     Figure 3-22. Criteria for dead end coverage
3-40


---

                                                                                                                                  TM 5-690

           (h) Where large re-entrant loops (i.e., those with greater than 90-degree turns) cannot be avoided,
 e.g., around cornices or over parapets, the conductor should be routed to ensure that the open side of the
 loop is greater than one-eighth the length of the remaining sides of the loop. It is advised, however, to
 course the conductor through holes or troughs through the obstacles and avoid the loop completely
 whenever possible.

          (i) On structures with overhangs such as antenna towers with extended platforms or buildings
 utilizing cantilevered construction, run the down conductors vertically through the interior of the
 structure. Internally routed conductors must be enclosed in non-metallic, non-combustible ducts.

          (j) Substantial metal structural elements of buildings may be substituted for regular lightning
conductors where, inherently or by suitable electrical bonding, they are electrically continuous from the air
terminal to the earth electrode connection. The structural elements must have a conducting cross-sectional
area, including that in joints, at least twice that of the lightning conductor that would otherwise be used.
There need be no difference whether such conductors are on the interior or exterior of the structure when
used for down conductors. Steel frame buildings encased in bricks or other masonry products must have
external air terminals and roof conductors installed and bonded directly to the structural members to keep
the lightning discharge from having to penetrate the masonry shell to reach the frame members.

     (3) Provide each air terminal with a two-way path to earth through the installation of roof and down
conductors conforming to table 3-3 for structures not greater than 75 feet in height and conforming to table
3-4 for structures greater than 75 feet in height. An exception is that air terminals located on prominent
dormers extending less than 16 feet from the main structure need have only one connecting path from the
terminal to the main down conductor.

Table 3-3. Minimum requirements for roof and down conductors on
       structures not greater than 75 feet (23 meters) in height

              Conductor               Material
                                                   Aluminum
                              Copper

    Cable       Strand Size        14 AWG              12 AWG
                Wt/1000 ft.        187 ½ lbs             95 lbs
 Solid Strip                   59,500 Cir Roils
 Solid Rod          Area      .176 ohms/1000 ft.   98,500 Cir Roils
Tubular Rod    dc Resistance       14 AWG         .176 ohms/1000 ft.

                 Thickness            1 in.            12 AWG
                   Width      .176 ohms/1000 ft.          1 in.

               dc Resistance       186 ½ lbs      .176 ohms/1000 ft.
                Wt/1000 ft.   .176 ohms/1000 ft.         95 lbs
               dc Resistance
                Wt/1000 ft.        187 ½ lbs      .176 ohms/1000 ft.
              Wall Thickness        .032 in.             95 lbs
               dc Resistance  .176 ohms/1000 ft.        .064 in.

                                                  .176 ohms/1000 ft.

                                                                      3-41


---

TM 5-690

                Table 3-4. Minimum requirements for roof and down conductors on
                               structures greater than 75 feet (23 meters) in height

      Material  Strand Size  Weight/ft.  Weight/1000 ft.  dc Resistance/1000 ft.
        Copper   14 AWG         6 oz          375 lbs            .088 ohms
      Aluminum   12 AWG         3 oz          190 lbs            .088 ohms

         (a) Roof conductors should be routed along ridges of gable, gambrel, and hip roofs, and around
the perimeter of flat and gently sloping roofs.

         (b) Roof grounding conductors routed throughout decks, flat surfaces, and flat roofs should be
interconnected to form closed loops to insure that all air terminals have at least two paths to earth.

         (c) Ridge conductors may drop from a higher to a lower roof level without installing an extra
down lead at the point of intersection of the two roof levels if there are not more than two air terminals on
the lower roof level.

         (d) On roofs that exceed 50 feet in width, additional conductors are to be provided to
interconnect the air terminals required to protect large flat areas. One additional conductor for each 50
feet in width is necessary. For example, on roofs 50 to 100 feet wide, add one additional run; on roofs
100 to 150 feet wide, add two additional runs; etc. These additional runs must be interconnected together
and to the perimeter conductor at 150-foot intervals with cross conductors as illustrated in figure 3-17.

         (e) Maintain a horizontal or downward course with roof conductors. Provide "U" or "V" (up and
down) pockets with a down conductor from the base of the pocket to ground or to a convenient lead of the
main down conductor.

         (f) Route conductors through or around obstructions which lie in a horizontal plane with the
conductor [figure 3-23(b) and (c)]. Bends in the conductor should not include an angle of less than 90
degrees and should maintain a radius of 8 inches or greater [figure 3-23(d)]. In particular, re-entrant
loops should be avoided. When routing around obstructions, wide gradual bends are preferred. Other
recommended practices are illustrated in figure 3-23(e) through (h).

         (g) Securely attach the conductors directly to the ridge roll or roof with UL-approved fasteners
every 3 feet.

         (h) Conductors may be coursed through air up to 0.9 meters (3 feet) without support. With an
acceptable support such as a 1.9 cm (3/4-inch) copper-clad ground rod or its equivalent, securely fastened
at each end, a conductor may be coursed up to 1.8 meters (6 feet) through air.

      (4) To complete the conventional lightning-protection system installation, all metallic elements
(roof fans, vents, etc.), grounded or isolated, which are located on the roof or in the exterior
walls near the down conductors, must be bonded to the down conductors because the possibility of a
sideflash exists. A sideflash is an arc caused by a difference in potential between a down conductor and a
metallic element. The bonding eliminates potential difference and prevents high current flow from
damaging these components.

3-42


---

                                                                                                                                TM 5-690
     (5) Continuous conductor runs shall be used if at all possible. Connections and splices shall be of
high quality and performed using approved manufacturer’s recommended methods and tools. Figure 3-23
shows several examples of splices and connections.

        Figure 3-23. Recommended construction practices for integral lightning protection systems
                                                                                                                                       3-43


---

TM 5-690

       (6) Securely attach air terminals and roof and down conductors to the building or other object upon
which they are placed. Fasteners (including nails, screws, or other means by which they are attached)
should be substantial in construction, not subject to breakage, and should be of the same material as the
conductor or of a material that will preclude serious tendency towards electrolytic corrosion in the
presence of moisture because of contact between the different metals. Keep all hardware, component
parts, and joints that are not welded or brazed and that require inspection for maintenance and repair
readily accessible. Any special fixtures required for access should be permanently attached to prevent
loss. However, appropriate locks or other devices essential to safety, security, and physical protection of
the hardware or of the area in which it is located may be used.

       (7) No part of the structure being protected should extend outside the protected zone. Where it is
impractical to provide a common mast to provide protection for an entire structure, additional masts
should be provided. If the pole is made of a non-conducting material, provide an air terminal extending
not less than 0.6 meters (2 feet) nor more than 0.9 meters (3 feet) above the top of the pole.
Connect the base of the mast (if metal) or the down conductors to the earth electrode subsystem of the
protected structure with at least a No. 6 AWG copper conductor or equivalent.

       (8) If the poles are of a non-conducting material, an air terminal shall be securely mounted on the
top of each pole, extending not less than 0.45 meters (1.5 feet) above the top of the pole. Down
conductors are run down the side of the pole or the guy wire may be employed as the conductor as shown
in figure 3-24. If the guy wire is used, it shall be properly grounded and bonded and both this wire and
the overhead ground wire are dead-ended at the pole. The overhead ground wire and the guy wire shall
be interconnected with a separate cable. Down conductors and guy wires used as down conductors are to

                         Figure 3-24. Overhead ground wire lightning protection system

3-44


---

                                                                                                                                TM 5-690

be connected to the earth electrode subsystem of the structure being protected. Guy wires not located
near existing earth electrode subsystems shall be grounded either to their respective ground anchor (by
use of an interconnecting cable) or to a separate ground rod.

         (a) The height of the poles should be sufficient to provide a clearance of not less than 1.8 meters
(6 feet) between the overhead ground wire and the highest projection on the building. When the overhead
ground wire system is used to protect stacks or vents which emit explosive dusts, vapors, or gases under
forced draft, the cable is installed so that it has a clearance of at least 4.5 meters (15 feet) above the object
receiving protection.

         (b) With either the mast type or the overhead ground wire type of system, the pole is placed at a
distance from the structure that is at least one-third the height of the structure, but in no instance less than
1.8 meters (6 feet).

  d. Transient protection. An essential addition to the air terminals, down conductors, and earth
connection for the protection of electrical and electronic equipment is the installation of lightning
arresters and terminal protection devices (TPDs) on all external power, communications, data, and control
lines that penetrate the facility boundary. TPDs are fast-response protection devices installed for the
purpose of shunting extraneous pulses to ground. Examples of commonly used terminal protection
devices are carbon blocks, gas-filled spark gaps, zener diodes, and EMI power and signal line filters.
These surge arresters and TPDs must respond in a sufficiently short time to limit the surge voltages
produced by the lightning discharge to levels which can be tolerated by the equipment inside the facility.
To obtain least response time and to limit the overshoot voltage of the arresters and TPDs, these devices
must be properly grounded. They must be installed such that their leads are kept to minimum lengths and
kept very near to facility ground conductors.

     (1) Installation of a properly selected secondary ac surge arrester at the facility main service
disconnect provides the best method for ensuring that high energy transients are not coupled to equipment
by ac distribution lines within the facility. The surge arrester installed must have certain characteristics to
ensure adequate protection.

          (a) The arrester must be capable of safely dissipating transients of amplitudes and waveforms
expected at the facility for a predetermined period of time. Selection of an arrester that will provide
protection for a period of ten years is recommended.

          (b) Have a turn-on time fast enough to ensure that transient energy will not cause damage before
the surge arrester turns on and clamps. (50-5000 nanoseconds)

          (c) Maintain a low enough discharge (clamp) voltage while dissipating transient current to
prevent damage to protected equipment. (1.5 times system normal voltage)

          (d) Have a reverse standoff voltage high enough to ensure non-conduction during normal
operation. (1.75 time normal system voltage)

          (e) Be capable of complete extinguishing after firing on an energized line.

          (f) The surge arrester must be properly installed to ensure optimum operation. The input to each
phase arrester contained in the surge arrester should be fused to provide protection against overload of, or
damage to, the ac supply in the event an arrester should short. Also, indicator lights and an audible alarm
that go off when a fuse opens should be provided on the front of the surge arrester enclosure as a
maintenance aid.

                                                                                                                                       3-45


---

TM 5-690

          (g) Proper installation of the surge arrester is of vital importance for optimum operation. A
surge arrester with excellent operating characteristics cannot function properly if correct installation
procedures are not used. All surge arresters should be installed in accordance with the manufacturer's
recommendations.

          (h) If possible, install arresters inside the first service disconnect box to keep interconnecting
lead lengths as short as feasible. Use interconnecting wire of sufficient size to limit resistance and
inductance in the transient path to ground through the surge arrester. Interconnecting wiring should be
routed as straight and direct as possible with no sharp bends and the least number of bends possible. Do
not include loops in the wiring. The arrester must be grounded by the shortest low impedance path
available.

          (i) Installation of surge arresters is shown for grounded and ungrounded service in figures 3-25
and 3-26 respectively. For best possible protection, the line supply side of the main service disconnect
means should be connected to the phase input(s) of the surge arrester. However, when necessary to
facilitate removal of ac power for surge arrester maintenance, it is permissible to connect the surge
arrester to the load side of the main service disconnect means. In order to prevent introducing excessive
inductance and resistance in the transient path to the surge arrester, No. 4 AWG (minimum) insulated
stranded copper wire of the minimum feasible length must be used to make the interconnection(s) unless
otherwise recommended and guaranteed by the manufacturer. Also, the interconnecting wiring must not
contain loops or sharp bends. Otherwise, the response time of the surge arrester will be delayed and a
higher clamp voltage than that of the surge arrester will be impressed across the protected equipment, thus
increasing the possibility of damage. In the event a very fast transient should occur, it is quite likely that
the surge arrester would never turn on, and all of the transient energy would be dissipated by supposedly
protected equipment.

          (j) When the surge arrester is not properly grounded, its response time will be delayed and a
higher clamp voltage than that of the surge arrester will be impressed across the equipment being
protected. This can also be expected if the earth ground connection for the surge arrester contains loops
or sharp bends or is not properly bonded to the earth electrode subsystem. To overcome this problem,
stranded copper wire specified in accordance with Article 280 of the NEC® must be used to make the
ground connection unless other specifications are provided by the manufacturer of the surge arresters.
Figures 3-25 and 3-26 show the surge arresters installed to ensure the best direct route to ground thereby
minimizing the lead inductance(s) and ensure the firing of the surge arresters. For best results exothermic
welds should be used for bonding to the earth electrode subsystem. UL–approved pressure connectors are
suitable for aboveground bonds.

          (k) Selection of a surge arrester that will provide adequate protection against worst case
transients is recommended.

          (l) Several surge arrester application guide standards are available from the IEEE to aid in the
selection of surge arresters for specific applications. These standards are IEEE C62.2, Guide for the
Application of Gapped Silicon-Carbide Surge Arresters for AC Systems; IEEE C62.22, Guide for the
Application of Metal-Oxide Surge Arresters for AC Systems; IEEE C62.22.1, Guide for the Connection
of Surge Arresters to Protect Insulated, Shielded Electric Power Cable Systems; IEEE C62.37.1, Guide
for the Application of Thyristor Surge Protective Devices; IEEE C62.42 Guide for the Application of Gas
Tube and Air Gap Arrester Low-Voltage (Equal to or Less Than 1000 Vrms or 1200Vdc) Surge
Protective Devices; and IEEE C62.43, Guide for the Application of Surge Protectors Used in Low-
Voltage (Equal to or Less Than 1000 Vrms or 1200Vdc) Data, Communications, and Signaling Circuits.

3-46


---

                                                                                                          TM 5-690

Figure 3-25. Secondary ac surge arrester installation, grounded service
                                                                                                                 3-47


---

TM 5-690

                   Figure 3-26. Secondary ac surge arrester installation, ungrounded service
3-48


---

                                                                                      TM 5-690

         (m) The turn-on time (response time) is the time required for an arrester to turn on and clamp a
transient after turn-on voltage is impressed across device terminals. All basic suppressor devices used in
the manufacture of surge arresters are voltage dependent for ionization, breakdown, and other phenomena
associated with breakdown. Therefore, a low turn-on voltage enhances a faster turn-on time. Turn-on
time requirements for a surge arrester must be directly related to the withstand level for equipment and
components being protected. For instance, if only heavy duty electrical equipment, such as motors,
contactors, and switches are being protected, relatively slow turn-on of 1 to 5 microseconds can be
tolerated. However, if solid-state electronic equipment, or a combination of electrical and electronic
solid-state equipment is being protected, turn-on time becomes much more critical. In general, the most
rapid response time available is desirable. However, cost and current dissipation capability normally
place constraints on such selection criteria. Four types of arresters are currently manufactured. Their
general characteristics are listed in table 3-5.

         (n) Turn-on time of 50 nanoseconds is sufficiently fast to protect all except very critical
components that would directly receive transient energy prior to turn-on and clamp of the surge arrester.
Solid-state units may be used for protection of very critical equipment components, and the gas-filled
spark gap type will provide adequate protection for heavy duty electrical equipment such as motors,
contactors, and switches. However, arresters with slow turn-on time and high turn-on voltage should not
be used to protect electronic equipment that has low-voltage, fast turn-on transient suppression devices, or
circuits included as an integral part of the equipment. Otherwise, the transient suppression in the
equipment will turn on and attempt to dissipate transient energy before the surge arrester installed at the
main service disconnect means turns on. In most cases, this will rapidly destroy equipment-level transient
suppression. The resistance and inductance of power distribution panels and power distribution wiring
within the facility will tend to slow down transient rise time and also dissipate some transient energy both
before and after the surge arrester turns on. The resistance and inductance works in conjunction with the
surge arrester at the main service disconnect means to provide additional protection. However, the true
degree of protection thus provided varies widely due to varying transient waveforms, and size and length
of distribution wiring within the facility.

                  Table 3-5. Generalized characteristics for surge arresters by type

      Type          Turn-on           Current       Firing/Clamp   Reverse                Cost
Gas-filled spark      Time           Capacity          Voltage    Standoff            $25 - $750
                                                                   Voltage
       gap           5 – 250      Up to 150,000       350 – 5500  200-300%            $50 - $1000
                  nanoseconds         amperes            volts                           $100 –
 MOV or ZNR                                                       175±25%               $25,000
                      for 10        Life = 2500       300 – 3000
  Solid-State     kV/micro sec    surges @ 10,00         volts    175±25%

                    rise time         amperes         275 – 750
                        50             Varies            volts

                  nanoseconds,   Varies usually 50
                  any rise time   – 100 amperes

                        10
                  nanoseconds,
                  any rise time

         (o) Design of effective lightning transient protection requires that the surge arrester turn on very
rapidly at the lowest voltage possible when a transient occurs. In addition, it is desirable that a low clamp
voltage be maintained across the surge arrester while conducting surge current to ground. Turn-on

                                                                                      3-49


---

TM 5-690

voltage and associated turn-on time as well as clamp voltage are proportional to reverse standoff voltage.
That is, an arrester with a low reverse standoff voltage has a lower turn-on voltage (and thus a faster turn-
on time) and a lower clamp voltage than an arrester with a higher reverse standoff voltage. Therefore, it
is important that the surge arrester has the lowest possible reverse standoff voltage.

          (p) For effective protection, the reverse standoff voltage should be between 200 to 300 percent
of nominal line-to-ground voltage of the appropriate ac service lines for a spark gap type surge arrester
that is to be installed line to ground. The reverse standoff voltage should also be between 200 to 300
percent of nominal line-to-line voltage of appropriate ac service lines for a spark gap type surge arrester
that is to be installed line to line. The reverse standoff voltage for metal oxide varistor (MOV) and zinc
oxide non-linear resistor (ZNR) type arresters should be 175 ± 25 percent of the nominal line-to-ground
or line-to-line voltages of the appropriate ac service lines.

     (2) Electrical and electronic equipment at various facilities has been severely damaged by lightning-
generated transients. The transients occur on externally exposed lines that directly interface equipment.
Externally exposed lines are outside lines, buried, overhead, etc., that are exposed to weather elements.
The lines include incoming ac service conductors, equipment signal, status, control, grounding
conductors, and intrafacility ac and dc power lines. This section identifies transient source and damage,
waveforms and amplitudes of projected transients on different types of lines, frequency of transient
occurrence, and effective methods to implement to preclude equipment damage and operational upset
when transients occur.

           (a) Electrical and electronic equipment comprising an operating system is susceptible to
damage from lightning-generated transient surges via two primary sources - transient surges coupled to
equipment from incoming commercial ac power conductors and transient surges coupled to equipment by
connected facility control, status, power, ground, and data and signal lines that originate or terminate at
equipment located externally to the building or structure housing the equipment of interest.

           (b) Damage resulting from lightning-generated transients occurs in many forms. Entire
equipment chassis have been exploded and burned, and wall-mounted equipment has been blown off the
wall by large-magnitude transient energy. Damage usually consists of catastrophic component failure or
shortened operating lifetime of components resulting from over-stress.

           (c) Damage can be minimized, and in most instances eliminated, by properly using the
generally field-proven protection methods. In order to be cost effective and to provide effective
protection, allocation of protection must be divided into three general categories: (1) transient
suppression (metal conduit and guard wires) for outside lines that interface equipment to be protected; (2)
installation of transient suppression devices on both ends of exterior lines immediately after equipment
building penetration or at exterior equipment termination, and on incoming ac service entrance lines at the
facility main service disconnect means (on shielded facilities, transient suppression devices (TSDs)
should be installed in an entry vault or inside the main service disconnect box); and (3) including transient
suppression as an integral part of protected equipment at the exterior line-equipment interfaces.

       (3) If realistic transient protection is to be designed, frequency of transient occurrence, amplitudes
and waveforms of transients, and the basic insulation level (BIL) of equipment to be protected must be
defined. The BIL is the short-duration voltage and current surge levels that equipment can withstand
without overstressing or immediate destruction of components occurring, and without equipment
operational upset occurring.

         (a) Integrated circuits, discrete transistors and diodes, capacitors, miniature relays, transformers,
and switches used in the design of solid-state equipment are very susceptible to damage from lightning-

3-50


---

                                                                                                                                TM 5-690

generated transient surges. Other components are not immune to damage but are susceptible to a much
lesser degree. Standards do not exist for specifying the withstand level against lightning-transients for
most equipment and components. Therefore, accurate information must be obtained from manufacturers,
laboratory testing performed, or conservative engineering estimates made. Typical withstand level limits
for common devices are shown in table 3-6.

Table 3-6. Typical withstand level limits for electrical devices

                           Device                                 Withstand Level Limit
Integrated circuits                               1.5 times normal rated junction and Vcc voltage
Discrete transistors                              2 times normal rated junction voltage
Diodes                                            1.5 times peak inverse voltage
Miniature relays, transformers, and switches      3 times rated voltage
                                                  1.5 times dc working voltage unless transient
Capacitors                                        dielectric punch-through voltage known
                                                  1.5 times diode peak inverse voltage (PIV) rating
DC power supplies with step-down transformer and  times the transformer secondary to primary voltage
diode bridge                                      ratio
Small motors, small transformer, and light
machinery                                         10 times normal operating voltage
Large motors, large transformers, and heavy
machinery                                         20 times normal operating voltage

  e. Protection of conductors and other systems. Protection of outside distribution circuits and
components from lightning strikes is described below. Because of the large physical size of incoming ac
service conductors, less impedance (resistance and inductance) is presented to transient surge current
flow. As a result, amplitude and waveforms of transients appearing at ac inputs are quite different from
those appearing at control, status, data, signal, and in-system power-line inputs. Therefore, protection for
incoming ac power service conductors is discussed separately from that for other externally exposed lines.

       (1) An overhead guard wire has been proven to provide an effective level of protection for
overhead service conductors against direct lightning strikes. This guard wire also provides a low level of
protection against transients induced on lines by close proximity strikes as well as nearby cloud-to-cloud
discharges. The guard wire must be located above and parallel to the service conductors. To be effective,
the height of the guard wire must not allow a circle with the radius of 100-feet tangent to the guard wire
and earth to touch the service conductors to be protected per NFPA 780. The guard wire must extend
from the secondary of the service transformer for the facility to the facility service entrance fitting. Also,
at each end the guard wire must extend to, and be bonded to, an effective earth ground or to the earth
electrode subsystem of the facility. When the distance between the service transformer and the facility
service entrance exceeds 250 feet, the guard wire shall also be bonded to a ground rod. Since the guard
wire and the earth electrode subsystem are usually comprised of different metals, exothermic welding is
recommended.

       (2) Transient protection on ac service conductors is accomplished by use of the following.

                                                                  3-51


---

TM 5-690

        (a) Installation of an ac surge arrester at the facility main service disconnect means.
        (b) Including surge suppressors as an integral part of equipment at ac power inputs of each critical
sub-panel of a facility.
        (c) Installation of suitable lightning or surge arresters on the primary and secondary of the main
station service transformer.
     (3) Protection against direct lightning strikes for underground cables may be accomplished by use of
the following.
        (a) Completely enclose buried lines in ferrous metal, electrically continuous, watertight conduit.
Protect against direct lightning strikes to buried cable by installing a guard wire above the cables or cable
duct. A 1/0 AWG bare copper cable laid directly over the protected cables is recommended. At least
25.4 cm (10 inches) should be maintained between the protected cables and the guard wire. For a
relatively narrow spread of the cables, 0.9 meters (3 feet) or less, or for a duct less than 0.9 meters (3 feet)
wide, only one guard wire cable is necessary. For wider cable spreads or wider ducts, at least two 1/0
AWG cables should be provided as illustrated in figure 3-27. The guard wires should be spaced at least
30 cm (12 inches) apart and be not less than 30 cm (12 inches) nor more than 45 cm (18 inches) inside the
outermost wires or the edges of the duct. To be effective, the guard wires must be bonded to the earth
electrode subsystem at each terminating facility. Exothermic welds provide the most effective bonding.
Since the guard wire and protected cables are embedded in the earth, the applicable zone of protection is
not known.

                            Figure 3-27. Lightning protection for underground cables

3-52


---

                                                                                                                                TM 5-690

         (b) Experimental use of a buried guard wire embedded in soil above and parallel to buried cable
runs not enclosed in metal conduit has provided effective attenuation of lightning-induced transients. Use
of the guard wire is recommended for protection of buried equipment lines not enclosed in metal conduit.
Bare 1/0 AWG copper wire has provided the most effective protection during experimental use. The
guard wire should be installed using the same guidelines given for underground cable runs encased in
metal conduit.

       (4) Waveguides between antennas and their associated transmit/receive equipment should be
grounded in the following manner.

         (a) Each waveguide shall be bonded to the down conductor of the air terminal at the top near the
antenna and also at the bottom near the vertical to horizontal transition point. The waveguide shall also
be bonded to the antenna tower at the same points as well as at an intermediate point if the tower exceeds
60 meters (200 feet).

         (b) All waveguide support structures shall be bonded to the tower. The waveguide and
supporting structure shall be bonded together at the waveguide entry plate and connected to the earth
electrode subsystem.

         (c) All waveguides, conduit, or piping entering a building shall be bonded to the waveguide entry
plate, then to the earth electrode subsystem, as shown in figures 3-28 through 3-30.

         (d) Rigid waveguides within 1.8 meters (6 feet) of each other should be bonded together through
the entry plate or by means of a crimp type lug fastened under the waveguide flange bolts and No. 6
AWG wire. The bond shall be extended to the bus at the waveguide entry point and connected to the
earth electrode system.

         (e) Determine location of ground strap position and remove waveguide jacket. The ground strap
is made from a piece of waveguide. Clean mating surfaces (waveguide and strap) with solvent or
cleaning fluid.

         (f) Wrap the strap with No. 14 AWG copper wire (for 8 GHz waveguide). For 4 GHz
waveguide, use No. 10 AWG solid copper wire. Use adjustable stainless steel clamps as required to
secure the strap. Tighten screw until the clamp grips firmly. Excessive tightening could damage the
waveguide and impair the electrical characteristics. Weatherproof with Scotch Guard or equivalent and
tape.

         (g) An alternate method of securing the strap to the waveguide is to use wrap-around heat shrink
to cover the bond and to maintain weatherproofing. Solder one end of a solid copper wire (#10 for 4 GHz
and #14 for 8 GHz waveguide) to one end of corrugated portion of the ground strap. Align the corrugated
section of the ground strap with the exposed section of the waveguide. Tightly wrap the wire
around the ground strap and waveguide and solder the end of the wire to the ground strap for securing
purposes. Apply the wrap-around heat shrink around the waveguide and heat according to the
manufacturer’s instructions.

         (h) Remove all sharp and rough edges on ground strap.

                                                                                                                                       3-53


---

TM 5-690

                               Figure 3-28. Communication cable entry installation
3-54


---

                                                                                                                                TM 5-690

                              Figure 3-29. Grounding details for elliptical waveguide
  f. Inspections. Inspections of the final installation shall be performed to confirm the system is installed
in accordance with the engineering drawings and specifications. Inspections of the system should be
implemented as integral elements of the facility during the construction of the building or structure. To
ensure that the implementation is accomplished in a timely manner, the construction efforts should be
carefully monitored. Prior to acceptance of the facility, the installation should be validated as

                                                                                                                                       3-55


---

TM 5-690
acceptable using DA Form 7452-2-R shown in figure 3-31. The following guidelines are provided to aid
in the inspection and checkout of the facility.

    (1) The zone of protection established by the air terminals (or by the mast or overhead ground wire, if
a separately installed system is provided) shall be determined. Locate air terminals on a scaled drawing
of the structure (be sure to include all views). Verify all parts of the facility are adequately included
within the zones of protection established by the air terminals. In deficient areas, determine what
additional measures, if any, need to be taken.

                     Figure 3-30. Ground strap fabrication details for elliptical waveguide
       (2) Verify that the air terminals are the proper type, correct height, and in the proper locations.
       (3) Verify roof conductors are the proper size and correct choice of materials.
       (4) Verify the route of the roof conductors is acceptable and that all fasteners are acceptable.
       (5) Verify down conductors are the proper size and correct material.

3-56


---

                                                                                                                                           TM 5-690

1. FACILITY                       LIGHTNING PROTECTION GROUNDING SUBSYSTEM CHECKLIST FOR NEW FACILITIES

                                                               For useof this form, see TM 5-690;theproponent agency is COE.

                                                                                                                       2. DATE (YYYYMMDD)

Fort Tank                                                                                                          2 0 0 20 2 2 8

3. LOCATION                                                                                    4. INSPECTOR

Bu ild in g 3 1 6                                                                              Al Volta

5. SKETCHTHELAYOUT OF THE ACTUALLIGHTNINGPROTECTION SUBSYSTEM (Or attachanup-to-date engineering drawing)

                  See attach ed draw ing 0 0 1-5 0 -7, 3 0 N o v emb er 20 0 1 fo r d etails

6. ALLLIGHTNINGPROTECTION EQUIPMENTUL LABELED                                   7. ULMASTERLABEL ISSUEDAND PROPERLY ATTACHED TOTHE BUILDING

                  YES                 NO                                                                      YES       NO

8. AIRTERMINALS                           8b. HEIGHT                            8c. MATERIAL                       8d. SIZE (Diameter)

8a. CLASS                                                    2 ft                               c o pp e r                             5 /8"

                     I

8e. PROPERBASES/FITTINGS                  8f. PHYSICAL CONDITION          8g. PROPERLYINSTALLED                 8h. LOCATED ANDSPACED AS SPECIFIED
                                                                                         YES
             YES                  NO                     good                                             NO       YES                      NO

8i. DOESTHEHEIGHT OF AIRTERMINALS PROVIDEPROPER CONEOFPROTECTION                                          8j. DEFICIENCIES

             YES                  NO                                                                      N eed to rein stall p rop erly

9. ROOF CONDUCTORS

9a. CLASS                                 9b. TYPE                              9c. SIZE                           9d. MATERIAL

                     I                                stranded bare                             1 /2"                                c o pp e r

9e. BENDRADIOUS                           9f. SECURELY ANCHORED           9g. PROPER FITTINGS                   9h. LOCATED ANDSPACED AS SPECIFIED
                                                                                         YES
                   10"                               YES           NO                                     NO       YES                      NO

9i. PROPERLYBONDED TOAIR TERMINALSAND OTHER METAL OBJECTSON ROOF

             YES                  NO

9j. PROPERLY INTERCONNECTED TOOTHER CROSS ROOFCONDUCTORS                                      9k. DEFICIENCIES

             YES                  NO                                                          none

10. DOWN CONDUCTORS

10a. CLASS                                10b. TYPE                             10c. SIZE                          10d. MATERIAL

                     I                                stranded bare                             1 /2"                                c o pp e r

10e. BEND RADIOUS                         10f. SECURELY ANCHORED          10g. PROPER FITTINGS                  10h. LOCATED ANDSPACED AS SPECIFIED

                   10"                               YES           NO           YES                       NO       YES                      NO

10i. PROPERLYBONDED TOROOFCONDUCTORS/AIRTERMINALS AND GROUNDINGELECTRODES

                        YES               NO

10j. DEFICIENCIES

       nonee

11. GUARDS

11a. TYPE                                                 11b. PROPER FITTINGS                                11c. SOLIDLY ANCHORED

                             PVC                                     YES        NO                                 YES                     NO

12. GROUNDINGELECTRODES

12a. TYPE                                 12b. SIZE                             12c. LENGTH (Each)                 12d. FORMCOUNTERPOISE LOOP
                                                                                                                                     YES
             co p p er clad                               5/8 "                                    20 ft                                             NO
                                                                                                                                                     NO
12e. DISTANCEBELOWGRADELEVEL                         12f. DISTANCE FROMOUTERWALL                                   12g. PROPERLY INSTALLED
                                                                                                                                     YES                  USAPA V1.00
                           2 ft                                                        6 ft

12h.PROPERLY CONNECTEDTOOTHERGROUNDINGSYSTEMS OF THE BUILDING

                   YES                NO

12i. PROPERLY CONNECTEDTODOWN CONDUCTORS                                        12j. GROUNDRESISTANCE MEASUREMENT

                   YES                NO                                                                               10 ohms

DA FORM 7452-2-R, FEB 2002

                                              Figure 3-31. Sample of completed DA Form 7452-2-R
                                                                                                                                                3-57


---

TM 5-690

      (6) Verify that the down conductors are routed properly. Verify fasteners and hardware are
accessible and are the proper type and material.

      (7) Verify that adequate guards are provided where necessary.

      (8) Maintain a copy of all drawings, initial site surveys, checklists, and data collected during
construction in the facility records department. Prepare test reports, certified by the testing organization,
of ground resistance at each test location. Include observations of weather and other phenomena that may
affect test results. Describe measures taken to improve test results.

3-5. Signal reference subsystem

Signal circuits are grounded and referenced to ground to establish signal return paths between a source
and a load, control static charge, or provide fault protection. The desired goal is to accomplish each of
these three grounding functions in a manner that minimizes interference and noise. If a truly zero
impedance ground reference plane or bus could be realized, it could be utilized as the return path for all
currents -- power, control, audio and RF -- present within a system or complex. This ground reference
would simultaneously provide the necessary fault protection, static discharge, and signal returns. The
closest approximation to this ideal ground would be an extremely large sheet of a good conductor such as
copper, aluminum, or silver underlying the entire facility with large risers extending up to individual
equipment. The impedance of this network at the frequency of the signal being referenced is a function of
conductor length, resistance, inductance, and capacitance. When designing a ground system in which RF
must be considered, transmission line theory must be utilized.

  a. Isolation from fault protection subsystem. Because of the interference threat that stray power
currents present to audio, digital, and control circuits (or others whose operating band extends down to 60
Hz or below), steps must be taken to isolate these large currents from signal return paths. Obviously, one
way of lessening the effects of large power currents is to configure the signal ground system so that the
signal return path does not share a path common with a power return.

       (1) The first step in the development of an interference-free signal reference subsystem for an
equipment or a facility is to assure that the ac primary power neutral or grounded conductor are
interconnected with the safety grounding network at only one point. Isolation of ac power returns from
the signal reference subsystem is a major factor toward reducing many noise problems. Additional steps
should also be taken to minimize other stray ac currents such as those resulting from power line filters.
One way of reducing these currents is to limit the number of filter capacitors in an installation by using
common filtered ac lines wherever possible or by locating the filters as near as possible to the power
service entry of the facility.

       (2) To meet the safety requirements while minimizing the effects of power currents flowing with
signal currents through a common impedance, a single connection between the power distribution neutral
and the earth electrode subsystem is necessary. This single connection eliminates conductive loops in
which circulating (power) currents can flow to produce interference between elements of the signal
reference network. This connection to the earth electrode subsystem should be made from the first
service disconnect. Care should be taken to ensure that the signal reference, fault protection, and
lightning protection subsystems are bonded to the earth electrode subsystem at separate ground rod
locations.

  b. Typical configuration. Within a piece of equipment the signal reference subsystem may be a sheet
of metal which serves as a signal reference plane for some or all of the circuits in that equipment.
Between equipment, where units are distributed throughout the facility, the signal ground network usually

3-58


---

FAULT PROTECTION                                                                                                                TM 5-690
                                                                                                                                                              FAULT PROTECTION
consists of a number of interconnected wires, bars, or a grid that serves an equipotential plane. Whether
serving a collection of circuits within equipment or serving several pieces of equipment within a facility,
the signal reference subsystem will be a floating ground, a single-point ground, a multiple-point ground,
or an equipotential plane. Of the aforementioned signal reference subsystems, the equipotential plane is
the optimum ground for communications-electronics facilities.

     (1) A floating ground is illustrated in figure 3-32. In a facility, this type of signal ground system is
electrically isolated from the building ground and other conductive objects. Hence, noise currents present
in the building's ground system will not be conductively coupled to the signal circuits. The floating
ground system concept is also employed in equipment design to isolate the signal returns from the

                                                                                                                                EQUIPMENT

                                                                                                               SIGNAL REFERENCE SUBSYSTEM

                                                                 EARTH ELECTRODE SUBSYSTEM

                                          Figure 3-32. Floating signal ground

equipment cabinets and thus prevent noise currents in the cabinets from coupling directly to the signal
circuits. The effectiveness of floating ground systems depends on their true isolation from other nearby
conductors, i.e., to be effective, floating ground systems must really float. In large facilities, it is often
difficult to achieve a completely floating system, and even if complete isolation is achieved it is difficult
to maintain such a system. In addition, a floating ground system suffers from other limitations. For
example, static charge buildup on the isolated signal circuits is likely and may present a shock and a spark
hazard. In particular, if the floated system is located near high voltage power lines, static buildup is very
likely. Further, in most modern electronic facilities, all external sources of energy such as commercial
power sources are referenced to earth grounds. Thus, a danger with the floating system is that power
faults to the signal system would cause the entire system to rise to hazardous voltage levels relative to
other conductive objects in the facility. Another danger is the threat of flashover between the structure or
cabinet and the signal system in the event of a lightning stroke to the facility. Not being conductively
coupled together, the structure could be elevated to a voltage high enough relative to the signal ground to
cause insulation breakdown and arcing. This system generally is not recommended for C-E facilities.

                                                                                                                                       3-59


---

FAULT PROTECTION SUBSYSTEMTM 5-690
                                                                                                                                                                FAULT PROTECTION SUBSYSTEM
       (2) A second configuration for the signal ground network (for lower frequencies, 0-30 kHz up to
300 kHz) is the single-point approach illustrated in figure 3-33. With this configuration, the signal
circuits are referenced to a single point, and this single point is then connected to the facility ground. The
ideal single-point signal ground network is one in which separate ground conductors extend from one
point on the facility ground to the return side of each of the numerous circuits located throughout a
facility. This type of ground network requires an extremely large number of conductors and is not
generally economically feasible. In lieu of the ideal, various degrees of approximation to single-point
grounding are employed.

                                                                                                                                  EQUIPMENT

                                                                                SIGNAL REFERENCE SUBSYSTEM

                                                                 EARTH ELECTRODE SUBSYSTEM

                                        Figure 3-33. Single-point signal ground

          (a) The configuration illustrated by figure 3-34 closely approximates an ideal single-point
ground. It uses individual ground buses extending from an earth electrode subsystem to each separate
electronic system. In each system, the various electronic subsystems are individually connected at only
one point to this ground bus.

         (b) Another frequently used approximation to the ideal is illustrated in figure 3-35. Here the
ground bus network assumes the form of a tree. Within each system, each subsystem is single-point
grounded. Each of the system ground points is then connected to a tree ground bus with a single insulated
conductor (usually yellow).

         (c) The single-point establishes a signal reference plane in each unit or piece of equipment, and
these individual reference planes are connected together and to the earth electrode subsystem. An
important advantage of the single-point configuration is that it helps control conductively-coupled
interference. As illustrated in figure 3-36, closed paths for noise currents in the signal ground network are
avoided by the single point signal reference subsystem. The interference voltage, VN in figure 3-36, in
the facility ground system is not conductively coupled into the signal circuits via the signal reference

3-60


---

                                                TM 5-690

                            SUBSYSTEM
                                     A

                SYSTEM A

                SUBSYSTEM   SUBSYSTEM
                         C           B

BUILDING STEEL

                            SYSTEM
                                 B

                                        SYSTEM
                                             C

                                                                                                                                            MAIN GROUND PLATE
                                                                                                                                            (ISOLATE FROM BUILDING)

                                                                                                                           EARTH ELECTRODE
                                                                                                                           SUBSYSTEM

                       Figure 3-34. Single-point ground bus system using separate risers

subsystem. Therefore, the single-point signal reference subsystem minimizes the effects of lower
frequency noise currents, which may be flowing in the facility ground.

         (d) Single-point grounds, however, also become transmission lines at higher frequencies with
earth being the other side of the line. In addition, every piece of equipment bonded to this transmission
line will act as a tuned stub. In the presence of digital signals (square waves) the tuned circuits will ring
at the specific frequencies to which they are resonant. Since single-point grounds behave as transmission
lines at RF frequencies, they will have different impedances as a function of frequency, i.e., they may
appear as inductors, capacitors, tuned circuits, insulators, or pure resistance, and therefore become
extremely poor grounds. In a large installation, another major disadvantage of the single-point ground
configuration is the requirement for long conductors. The long conductors prevent the realization of a
satisfactory reference for higher frequencies because of large self-impedances. Further, because of stray
capacitance between conductors, single-point grounding essentially ceases to exist as the signal frequency
is increased.

          (e) Because of the above conditions, single-point grounds are not recommended for use in
communications electronics facilities.

                                                3-61


---

TM 5-690

          SYSTEM                                                   SYSTEM B
               C                                                 SUBSYSTEM

                                                  SYSTEM                  A
                                                       A
                                                                            SUBSYSTEM
                      GROUNDING                                                      B
                      BUS
                                                                 SUBSYSTEM
                                          EARTH                            C
                                          ELECTRODE
                                          SUBSYSTEM

          Figure 3-35. Single point ground bus system using a common bus

                           EQUIPMENT

          FAULT PROTECTION SUBSYSTEM
                                                                                                                                                                         FAULT PROTECTION SUBSYSTEM
          SIGNAL REFERENCE SUBSYSTEM

                                                          ZG     IN

          FACILITY GROUND                                 -V N+

   Figure 3-36. Use of single-point ground configuration to minimize effect of facility ground currents
3-62


---

                                                                                                                                TM 5-690

       (3) The multipoint ground (for higher frequencies, 30-300 kHz and above) utilizes many
conductive paths from the earth electrode subsystem to various electronic systems or subsystems in the
facility. Within each subsystem, circuits and networks are connected to this ground network. Thus in a
facility numerous parallel paths exist between any two points in the ground network.

         (a) Multipoint grounding frequently simplifies circuit construction inside complex equipment. It
is the only realistic method for the grounding of higher frequency signal circuits. This method of
grounding permits equipment employing coaxial cables to be more easily interfaced since the outer
conductor of the coaxial cable does not have to float relative to the equipment cabinet or enclosure.

         (b) The multipoint grounding has the disadvantage of exhibiting transmission line characteristics
at radio frequencies. Care must also be taken to ensure 60 hertz power currents and other high amplitude
lower frequency currents flowing through the facility ground system do not conductively couple into
signal circuits and create intolerable interference in susceptible lower frequency circuits.

       (4) An equipotential ground plane implies a mass, or masses of conducting material which, when
bonded together, offers a negligible impedance to current flow. Connections between conducting
materials which offer a significant impedance to current flow can place an equipotential plane at a high
potential with respect to earth. The importance of equipotential ground planes cannot be overemphasized
for proper equipment operation, as well as for EMI and noise/static suppression. High impedance
interconnections between metallic members subject to large amounts of current due to power system
faults can be extremely hazardous to personnel and equipment.

          (a) The radio frequency interference (RFI) effect of an equipotential plane or system must
however be carefully considered, and it is important to understand that grounding may not, in and of
itself, reduce all types of RFI. On the contrary, grounding a system may in some instances increase
interference by providing conductive coupling paths or radiative or inductive loops. Many of the
deficiencies of the wire distribution system can be overcome by embedding a large conducting medium,
in the floor under the equipment to be grounded. A large conducting surface presents a much lower
characteristic impedance than that of wire because the characteristic impedance is a function of L/C,
hence as capacitance to earth increases, impedance decreases. The capacitance of a metallic sheet or grid
to earth is much higher than that of wire. If the size of the sheet is increased and allowed to encompass
more area, the capacitance increases. Also, the unit length inductance decreases with width, which
further decreases impedance. If the dimensions of a metallic sheet increase extensively (as in the case of
conducting floor), the characteristic impedance approaches a very low value. In this case, the
characteristic impedance would be quite low throughout a large portion of the spectrum. This, in turn,
would establish an equipotential reference plane for all equipment bonded to it.

          (b) Grounding buses in a communication facility where higher frequencies are present act as
lossy transmission lines and therefore must be treated as such. Due to this phenomena, single-point
grounds and multipoint grounds employing ground buses are high impedance grounds at higher
frequencies. To be effective at the higher frequencies, the multipoint ground system requires the
existence of an equipotential ground plane. Equipotential planes are sometimes considered to exist in a
building with a metal floor or ceiling grid electrically bonded together, or in a building with the ground
grid embedded in a concrete floor connected to the structural steel and the facility ground system.
Equipment cabinets are then connected to the equipotential plane. Chassis are connected to the
equipment cabinets and all components, signal return leads, etc., are connected to the chassis. The
equipotential plane is then terminated to the earth electrode subsystem and to the main structural steel via
multiple connections, to assure personnel safety and a low impedance path for all frequencies and signals.

                                                                                                                                       3-63


---

TM 5-690

It is again emphasized, however, that care must be taken not to create loops that can couple signals from
one system to another.

  c. Design considerations. The design of an effective signal reference subsystem depends upon
properly identifying the range of signal frequencies likely to be encountered.

       (1) A higher frequency grounding network is defined as one that is > 300 kHz, and in some cases
down to 30 kHz. The higher frequency (equipotential) grounding network provides an equal potential
plane with the minimum impedance between the associated electronic components, racks, frames, etc.
This plane shall be used at facilities or areas within facilities where interface frequencies are over 300
kHz and may be used at sites where interface frequencies are as low as 30 kHz. In higher frequency
systems, equipment chassis are frequently used as the signal reference. The chassis in turn is usually
connected to the equipment case at a large number of points to achieve a low impedance path at the
frequencies of interest.

          (a) The higher frequency grounding network is a conductive sheet, grid, or cable network mesh
providing multiple low resistance paths between any two points within the structure and between any
point in the structure and the earth electrode subsystem. It consists of three primary components -
equipotential plane, equipment ground conductors, and structural steel elements and electrical supporting
structures, connected to the earth electrode subsystem. The equipment grounding conductor (green wire)
sha1l not be considered a substitute for this subsystem. The optimum interconnecting cable and mesh
spacing of the equipotential plane should be 1/8 of a wavelength with regard to the highest frequency of
concern. In practice this may not be feasible and the interconnecting cable and mesh spacing should
therefore be as short and small as practical.

                                                            λ = c/ƒ
                         where c = velocity of light in free space = 3 x 108 meters/second

                                         ƒ = frequency in hertz (cycles/second)

          (b) The NEC requires that equipment cases and housings be grounded to protect personnel from
hazardous voltages in the event of an electrical fault. Stray currents in the fault protection network can
present an interference threat to any signal system whose operating range extends down into the lower
frequency range and should be eliminated. Where such problems exist, it is advisable to attempt to
reduce the impedance of the reference plane as much as possible. A practical approach is to interconnect
equipment enclosures with the equipotential plane, via building structural steel, cable trays, conduit,
heating ducts, piping, etc., into the earth electrode subsystem to form as many parallel paths as possible.
It should be recognized that because of the inductance and capacitance of the network conductors, such
multipoint ground systems offer a low impedance only to the lower frequency noise currents; however,
these currents can be the most troublesome in many facilities. Higher frequencies find a much lower
impedance to ground through the distributed capacity of the equipotential plane.

          (c) In steel frame buildings, make all structural members of the building (e.g., building
columns, wall frames, roof trusses, etc.) electrically continuous by bonding each joint and interconnection
with a welded, brazed, soldered, or high–compression bolted connection. Where direct bonds of these
types are not possible, bridge the joint with a l/0 AWG stranded copper cable both ends of which are
brazed, welded, or bolted in place. This does not include rebars.

          (d) Connect the bonded structural steel network to the earth electrode subsystem with 1/0 AWG
copper cables. The distance between adjacent connections from the building structure to the earth
electrode subsystem should not exceed 15 meters (50 feet).

3-64


---

                                                        TM 5-690

         (e) Where steel frame construction is not used, install a supplemental network consisting of large
copper cables conforming to table 3-7.

         (f) Equipment cabinets, electrical supporting structures, and utility pipes are to be connected to
this structural steel or copper cable grid (equipotential plane) with #6 AWG copper wire. This
interconnecting wire should be as short as feasible, preferably not over 24 inches to minimize high
frequency reactance. (Electrical supporting structures include all the conduit, raceways, switch and
breaker panels, and other hardware (not energized) commonly associated with the communication
electronic facility.)

       Table 3-7. Size of equipment ground cables

Cable Size  Maximum Path Length

  (AWG)                 (FT)

750 kcmil1              375
600 kcmil               300
500 kcmil               250
350 kcmil               175
300 kcmil               150
250 kcmil               125
                        105
    4/0                  84
    3/0                  66
    2/0                  53
    1/0                  41
      1                  33
      2                  21
      4                  13
      6
      8                   8

Busbar

4 x ¼                                              636

4 x 1/8                                            318

3 x ¼                                              476

3 x 1/8                                            238

2 x ¼                                              318

2 x 1/8                                            159

2 x 1/16                                           79

1 x ¼                                              159

1 x 1/8                                            79

1 x 1/16                                           39

1 kcmil – One thousand circular mils. A circular mill is a unit of area equal to the area of a circle whose diameter is
one mil (1 mil = 0.001-6 inch).

                                                                                                                                       3-65


---

TM 5-690

        (g) The dividing line between the lower and higher frequency should be high enough to include
all audio communications signals. Since digital systems employ frequencies, which extend from dc up to
several hundred MHz, a decision based on pulsed-signal considerations is more appropriate. To minimize
the possibility that the ground bus conductors will form antennas; the lengths should not exceed 0.02
wavelength which is approximately 21 meters (70 feet) at 300 kHz. Since the grounding buses in medium
to large sized facilities may extend 21 meters (70 feet), 300 kHz appears to be the maximum frequency
for which a single-point grounding system should be used. At frequencies up to 30 kHz, conductor
lengths up to 210 meters (700 feet) can be approached without exceeding the 0.02 wavelength criteria.
MIL-STD-188-124B establishes the lower frequency network range from dc to 30 kHz and in some cases
(depending on the interface frequency) up to 300 kHz. The higher frequency network range extends
above 300 kHz and may in some cases be used at sites where the interface frequencies are as low as 30
kHz. The frequency range from 30 kHz to 300 kHz is a mutual area and may be considered as either
higher or lower depending upon the interface frequency.

      (2) The lower frequency grounding network is defined as the range from 0-30 kHz, and in some
cases up to 300 kHz. The lower frequency grounding network for the facility should conform to the
following principles:

          (a) It should be isolated from other ground networks including structural, safety, lightning and
power grounds, etc. The purpose of this isolation is to prevent stray currents (primarily 50/60 Hz power)
from developing voltage differentials between points on the ground network.

          (b) The inter-equipment or facility ground system should not be expected to provide the primary
return path for signal currents from the load to the source. Figure 3-37 illustrates a way of discriminating
against those extraneous signals which may inductively or capacitively induce currents into the grounding
network and develop differential voltages between the source and the load.

                           Figure 3-37. Signal coupling for lower frequency equipment

3-66


---

                                                                                                                                TM 5-690

          (c) The lower frequency grounding network must be connected to the earth electrode subsystem
at only one point.

          (d) The network must be configured to minimize conductor path lengths. In facilities where the
equipment to be connected to the ground network are widely separated, more than one network should be
installed.

          (e) Finally, the conductors of the network are to be routed in a manner that avoids long runs
parallel to primary power conductors, lightning down conductors, or any other conductor likely to be
carrying high amplitude currents.

          (f) Lower frequency signal reference subsystems are not recommended as the sole system in
communications-electronics facilities.

  d. Typical components and installation details. Typical components and installation details for signal
reference subsystems are described below.

       (1) Conducting media that can be utilized for the equipotential plane generally consists of a copper
grid embedded in the concrete floor or raised metal floor such as computer floor. Since a large solid
conducting surface is not economically feasible for some installations, a ground reference plane, made up
of a copper grid, or copperclad construction mesh with 4-inch openings may be embedded in the concrete
with ground risers installed to the surface of the concrete. The mesh is commercially available in AWG
wire sizes Nos. 6, 8, 10, and 12. It is normally furnished in 3.7m (12 foot) rolls, but can be obtained in
various widths up to 5.5m (18 feet). Where sections of mesh are joined together, there should be a one-
foot overlap and bonded together every two feet by welding, brazing, or manufactured connectors that are
connected to the grid and give grounding access at the floor surface. Normally, if the grid is embedded in
a concrete floor, the latter method provides the easiest grounding source. The equipotential plane shall be
welded to the main structural steel of the building at multiple locations. Where frame buildings are
utilized, the plane is connected to the earth electrode subsystem at multiple locations using 1/0 AWG
copper conductors. If metal floor systems are used (metal floors with concrete poured over the floor) then
the floor system itself can be used as the equipotential plane. In fact, this would be the preferred method
of establishing the plane.

       (2) Where it is not practicable to install a plane on the floor around the equipment, it is possible to
install an overhead equipotential plane in or on the ceiling of the equipment room. This can be
accomplished by installing either thin metal sheets or screen either above or on the ceiling. Care must be
taken to keep bonding straps from the equipment to the plane as short as possible. Generally phosphor
bronze screen is used in this application because it is light, durable, and easy to work. The plane must be
connected to the building steel, which in turn is bonded to the earth electrode subsystem. Alternately, a
ceiling grid arrangement may be used. The grid openings should not be larger than 1/20 wavelength of
the highest frequency of concern up to 4 inches. As a design objective (DO), the grid openings should not
be larger than 4 inches.

       (3) A surface equipotential plane is one usually installed under floor tile or carpet. An
equipotential plane can be realized by installing a metal sheet or roll of aluminum, copper, or phosphor
bronze under the floor tile or carpet. This sheet may be either thin gauge solid metal or window screen
type material bonded to the floor with mastic and tile or carpet installed on top of it. In existing facilities
where equipment is already installed, the plane need not be installed under tile equipment cabinets, but
must be bonded to the cabinets on all four sides. The plane shall be bonded to the main structural steel
members of the building at multiple locations. The structural steel shall in turn be bonded to the earth

                                                                                                                                       3-67


---

TM 5-690

electrode subsystem. Alternatively, a ceiling grid arrangement may be used. The grid openings should
not be larger than 1/20 wavelength at the highest frequency of concern up to 4 inches. As a DO, the grid
openings should not be larger than four inches.

     (4) Raised floors are used to structurally support equipment cabinets and provide a space between
the original facility floor and raised floor plates for cabling, air plenum or air conditioning ducting,
piping, drains, etc. Raised floors provide an esthetic room appearance. Three general types of floor
systems manufactured are the drop-in grid, the freestanding (stringerless or pedestal-only) type, and the
bolted-grid (stinger) system. Only the bolted-grid or the rigid grid system is acceptable as an
equipotential plane.

          (a) On a drop-in or removable grid system, the grids or stringers are retained by engaging pins or
depressions in the pedestal head. The stringers supply support and when newly installed provide
comparatively low resistance contact to the pedestal head. Equipment cabinets resting on the floor panels
provide increased contact pressure in certain areas. Severe corrosion and unreliable electrical contact
have resulted due to dirt, moisture, and floor cleaning/waxing compounds filtering through crevices. This
floor system is also considered unsuitable for a reference plane. Floor panels resting on the pedestals and
grids are commonly 24” x 24” although they may be purchased in 30” x 30” dimension.

          (b) On a freestanding (pedestal-only or stringerless) system, the pedestal base is glued or “shot”
in place to form the basic understructure. The pedestal heads are leveled and the floor panel is installed.
The conductivity between distant pedestals is variable and unreliable, making it unsuitable for a ground
reference.

          (c) Bolted-grid (stringer) or rigid grid system raised floors are similar to the drop-in grid except
the grids, when properly installed, are securely bolted or clamped in place. The drop-in panels must be
metal or wood with metal plate on both sides with a selected floor covering. They should be no larger
than 24" x 24." Although the panels may not make a good low resistance contact with the stringers, the
high distributed capacitance makes the floor appear to be an electrically continuous sheet at RF
frequencies. The equipment cabinets shall be connected to the floor stringers by bonding straps which
must be kept as short as possible. This will provide a low impedance path to earth at the lower
frequencies. Materials used for stringers and pedestal heads are steel and aluminum. In general, the
grounding aspects of raised flooring have been excellent.

         (d) Problem areas that designers and installers should be aware of are inadequate bonded joints
between pedestal heads due to oxidized dirty pedestal heads when installed, use of poor bolting hardware
(speed nuts, sheet metal screws), or bolting hardware not installed or not properly tightened. Composite
bonds between cabinet chassis and the raised floor shall not exceed a specified resistance value, usually 1
milliohm. Typically, a pedestal head to stringer resistance will read about 40 micro-ohms and should not
exceed 100 micro-ohms.

          (e) Connections from the equipment racks and the earth electrode subsystem to the floor are
important. Clamps, if used, should be installed on the upper pedestal assembly to avoid the relatively
high resistance between the lower assembly (that has the base) and the upper column. The stringer to
pedestal fastener hardware can often be changed to allow bolting a bonding cable terminal directly to the
pedestal head. It is feasible to obtain additional grid locking hardware and use it to bolt the bonding cable
terminal to the floor grid. Another means of terminating a bonding cable is to drill a hole and bolt it to a
non-heavyweight bearing stringer.

          (f) In extremely humid environments where corrosion is common, the use of corrosion
prevention compounds is recommended. Bolted joints can be covered with a non-corrosive silicone-

3-68


---

                                                                                                                                TM 5-690

rubber compound that will protect the joint for the life of the installation. An ice cube rubbed on the
silicone-rubber will smooth it.

          (g) Carpeting selected as a floor-covering, should be of a low static or static-free type to prevent
possible static discharge or component failure.

          (h) To determine degradation of the floor, resistance measurements and method should be
documented and available so that repeat measurements can be made if ground reference subsystem
problems are suspected or periodic checks for degradation made.

       (5) The type of ground riser to be used depends on the type of equipotential plane to be installed
and whether the subject building will be new construction, a major modification to an existing building in
which new equipment will be installed, or an existing building in which only the ground system will be
upgraded while the equipment remains in place.

       (6) Each individual unit or piece of equipment should either be bonded to its rack or cabinet, or
have its case or chassis bonded to the nearest point on the equipotential plane. Racks and cabinets should
also be bonded to the nearest point of the plane.

  e. Shielding for EDP protection and signal security. Grounding of equipment, conduit, and frames for
safety protection in areas processing national security related information (RED data) is no different than
any other facility. Typically a RED and a BLACK signal ground is established by a direct connection
totally within a controlled space to an equipotential ground plane and earth electrode subsystem. Cable
shields from the RED equipment to the RED side of the crypto are grounded at least at both ends. Cable
shields from the BLACK side of the crypto equipment through the BLACK intermediate distribution
frame (IDF) to the BLACK equipment are normally grounded at both ends. For unbalanced signaling,
signal ground is usually established by a direct connection from an isolated signal ground bus in the RED
distribution frame to an equipotential ground plane and in turn to the earth electrode subsystem.

  f. Inspections and tests. Inspection and testing of the system should be implemented as integral
elements of the facility during the construction of the building or structure. To ensure that the
implementation is accomplished in a timely manner, the construction efforts should be carefully
monitored from the onset of excavation through completion of the facility. Prior to acceptance of the
facility, the installation should be validated as acceptable using DA Form 7452-3-R shown in figure 3-38.
The following guidelines are provided to aid in the inspection and checkout of the facility.

     (1) Examine the drawings and schematics and visually inspect to see if an isolated single-point
signal ground is provided. Provide a brief description of the signal ground network or attach copies of the
schematics or drawings.

     (2) Verify that the internal signal ground network is terminated to an insulated signal ground
terminal as required. If a wire is used, verify that the size conforms to the 500 cmil per foot criteria (or as
specified) times the length of the wire connecting the single-point signal ground network to the earth
electrode subsystem. Enter the information requested on the inspection form.

     (3) Verify that the signal ground is correctly identified with a yellow label or color code.

     (4) Inspection requirements for the equipotential plane include the following.

        (a) Verify that equipotential planes exist in conformance to paragraph 3-5.d.

                                                                                                                                       3-69


---

TM 5-690

1. FACILITY                      SIGNAL GROUND REFERENCE SUBSYSTEM CHECKLIST FOR NEW FACILITIES

                                                       For useof this form, see TM 5-690;theproponent agency is COE.

                                                                                                                2. DATE (YYYYMMDD)

Fort Tank                                                                                                             2 0 0 20 2 2 8

3. LOCATION                                                                                4. INSPECTOR

Bu ild in g 3 5 8                                                                          G eorg O hm

5.SKETCHTHE LAYOUT OF THEACTUAL SIGNAL GROUNDREFERENCE SUBSYSTEM(Or attach the up-to-date engineering drawings)

             S ee a tta ch ed d ra win g 00 1 -5 0-4 , 30 N o vem b er 2 0 0 1

6. CHECKALLSIGNALGROUND COMPONENTSFOR PROPER SIZES,TYPESAND MATERIAL AS SPECIFIED. RECORD ALLDEFICIENCIES.

                       LOCATION                                                                         DEFICIENCIES

C o m p u ter ro o m (# 1 2 )    Th e g ro u n d in g pla te is 2 ft x 1 ft in stea d o f 2 ft x 3 ft a s sp ecified
Telep ho ne ro om (#1 5)         Th e b a ttery g rou n d con d u ctor is #6 AW G in stead o f 50 0 M C M

7. CHECK ALL SIGNAL GROUNDCOMPONENTSFORPROPER CONNECTION, BONDING,ANDCONTINUITY. RECORDALLDISCREPANCIES.

                       LOCATION                                                                         DEFICIENCIES

C o m p u ter ro o m (# 1 2 )    Th e g ro un d in g p la te is n o t bo n d ed to th e raised flo o r
Telep ho ne ro om (#1 5)         Th e p h on e sw itch rack is n o t g ro u n d ed
Tower antenna #6                 Th e to w er meta l stru ctu re is n ot g rou n d ed

8. GROUND RESISTANCE MEASUREMENTS (Use double balanced dc bridgefor all joint connectors)                                  RESISTANCE MEASUREMENT

                                                                     TEST POINTS                                      .0 2 m illio h m s
                                                                                                                      .0 3 m illio h m s
Bo n d b etw een g ro u nd in g p la te a n d ra ised floo r fra m e in ro om # 1 1
Bo n d b etw een ra ised flo o r fra m e a n d co m p u ter server fra m e

DA FORM 7452-3-R, FEB 2002                                                                                                                         USAPA V1.00

          3-70                   Figure 3-38. Sample of completed DA Form 7452-3-R


---

                                                                                                                                TM 5-690

        (b) In steel frame buildings, verify that the equipotential plane is bonded to the main structural
steel elements. In wooden or masonry buildings inspect to assure that multiple downleads are bonded to
the plane. Insure the red and black signal grounds are bonded to the equipotential plane.

         (c) Verify that the structural steel elements are bonded at the joints to produce a low resistance
(< 1 milliohm) joint. Welded joints conforming are preferred. Mechanically fastened joints should be
carefully cleaned, bolts adequately torqued, and proper bond protection supplied. Visually inspect
cleaning procedures, perform spot checks torque measurements, and visually verify that paints and
sealants are applied as needed. Perform spot check measurements of bond resistance at structural joints
using the double balanced bridge technique. Where bond resistances greater than 1 milliohm are
encountered, require that bond surfaces be recleaned, bolts retorqued, or supplemental jumpers provided
as needed to achieve 1 milliohm.

          (d) In non-steel frame or masonry buildings, inspect the installation of the supplemental
grounding network. In particular, verify that the grounding cables provide the required 2,000 circular
mils per running foot of conductors times the length of the wire connecting the higher frequency
equipotential signal ground plan to the earth electrode subsystem.

          (e) Verify that the ground risers are bonded to the equipotential plane and that the bond
resistance does not exceed 1 milliohm. Inspect to assure that the ground risers are located to provide the
shortest possible lengths to the equipotential plane.

          (f) Verify that at least two electrical paths exist between the equipotential plane and the earth
electrode subsystem. Preferably the plane should be bonded to the building main structural steel (or
downleads in wooden buildings) at least every 3 meters (10 feet). Measure the resistance between
selected points on the plane and the earth electrode subsystem to verify that the total resistance does not
exceed 5 milliohms. If the resistance does exceed 5 milliohms, check all joints for proper bonding and
down hauls for proper sizes. See that all deficient conductors are replaced and that all poor bonds are
redone.

      (5) Inspect all conduit metallic pipes and tubes for continuity and bonding.

      (6) Verify that all electrical supporting structures and cable ways are interconnected and bonded.

      (7) Inspect the grounding of the electrical distribution system.

      (8) With all cables (signal cables, control lines, power cables, etc.) disconnected, measure the
resistance between the signal ground terminal and the equipment case with an ohmmeter. The resistance
should be greater than one megaohm. Also, measure the resistance between each ac input terminal
(ground wire excluded) and the case. A resistance of one megaohm or greater should be measured.
Record both readings on the inspection form. If the measured resistance is less than one megaohm,
proceed as follows.

         (a) First check to see that all cables, lines, cords, etc., are disconnected from the equipment or
that the far ends of any such cables are insulated from other equipment and the structure. Disconnect all
cables found still connected.

          (b) If no connected cables are found or the low resistance reading still exists after disconnecting
all cables, visually inspect the mounting of the signal ground terminal to see that it is properly insulated
from tile case or cabinet (disassemble, if necessary). Alternately, disconnect the signal ground connection

                                                                                                                                       3-71


---

TM 5-690

inside the equipment and then measure the resistance between just the terminal and the case. If the
terminal is not insulated from the case or cabinet, it must be redone.

          (c) If the preceding two steps fail to identify the reason for the lack of isolation, the equipment
schematics and mechanical layout should be analyzed and inspected to locate the compromise in the
signal ground isolation. Be particularly alert for sneak paths through components (transformers, switches,
relays, etc.), readout devices (meters, lights), physical contact between the case or cabinet and the signal
ground, and wiring errors.

          (d) Measure the resistance between the green safety wire and the case; the resistance reading
should be 0.1 ohm or less. If a higher resistance reading is obtained, inspect the equipment to see if the
green wire in the power cord has been connected to the case or cabinet. If the connection is there
physically, was the paint removed from the area of attachment? Are screws or nuts fastened securely? If
any of these deficiencies exist, they must be corrected before installing or energizing the equipment.

          (e) Inspect all cabling and connectors to see that balanced signal lines are used for lower
frequency interfacing lines and that cable shields are grounded only at one end. The shields of individual
cable pairs must be isolated from each other except at the common ground points. Check overall shields
for grounding. Record any specifically noted deficiencies on the inspection form.

          (f) If the equipment is already installed, verify that the signal ground terminal is connected to the
nearest feeder ground plate of the lower frequency signal ground network for the facility. Check the size
of the cable to see that it conforms to the 500 cmil per foot or as otherwise specified.

     (9) Inspection requirements for higher frequency equipment include the following.

          (a) Verify that higher frequency reference points and planes are directly grounded to the chassis
and the equipment case to the extent permitted by circuit design requirements (and unless specified
otherwise).

          (b) Check to see that properly matched constant impedance cables are used for interfacing
purposes. Verify that all connectors are of a type and design that provides a low impedance path from the
signal line shield to the equipment case. Do not permit the use of pigtails for the termination of higher
frequency line shields outside the equipment case.

          (c) Check connectors for tightness, cleanliness, and for proper mounting. Measure the resistance
between the connector shell or body and its mounting surface with a double balanced dc bridge. The
resistance should not exceed one milliohm. If the resistance exceeds one milliohm, the mounting surfaces
should be recleaned to remove all paint, non-conductive coatings, or dirt and all screws or fasteners
should be retightened to achieve a close mechanical fit.

          (d) Measure the point-to-point resistance between selected points on the case or cabinet with the
double balanced bridge. The maximum resistance between any two points on the case or cabinet should
be one milliohm or as specified. If the resistance is greater than one milliohm, check to see that all
bonding surfaces are properly cleaned and that all connections are securely fastened. (Larger sized
grounding cables may have to be added to reduce the resistance to one milliohm or less.)

          (e) Record the results of the inspection on the inspection form.

      (10) If the lower and higher frequency signal networks are separate, inspect each in accordance with
the preceding respective instructions. If the networks involve both lower and higher frequency signals,

3-72


---

                                                                                                                                TM 5-690
inspect for conformance with the higher frequency requirements. Record the results of the inspection on
the inspection form.

     (11) Check to see that installed equipment, in addition, have their cases or cabinets grounded to the
facility ground system of the facility with a cable providing at least 2000 cmil per running foot or as
specified. Record results on the inspection form.

     (12) Maintain a copy of all drawings, initial site surveys, checklists, and test data collected during
construction in the facility records department.

                                                                                                                                       3-73


---

                               TM 5-690

                   CHAPTER 4

ELECTROMAGNETIC INTERFERENCE
             (EMI) PROTECTION

4-1. Purpose of EMI protection

Interference is any extraneous electrical or electromagnetic (EM) disturbance that tends to interfere with
the reception of desired signals or that produces undesirable responses in electronic systems. Interference
can be produced by both natural and man-made sources either external or internal to the electronic
system. The major objective of interference reduction in modern electronic equipment and facilities is to
minimize and, if possible, prevent degradation in the performance of the various electronic systems by the
interactions of undesired signals, both internal and external. In systems operating with high level signals,
undesired signals with amplitudes on the order of volts may be tolerable, while in low level systems a few
microvolts may produce intolerable errors in the response of the system. An important element in the
control of unwanted interactions between signals is the proper grounding of the system.

4-2. Typical configuration

An ideal signal system is a simple signal generator-load pair. With no extraneous voltages present within
the loop, the simple pair is free of interference. However, when the current return path is non-ideal and
sources of noise are present, a voltage difference will exist between the return or low side of the generator
and the return or low side of the load. This voltage difference effectively appears in the signal transfer
loop in series with the signal generator and produces noise currents in the load.

  a. Noise current reduction. Four ways of combating this noise problem are as follows.

       (1) Isolate the source-load pair from the noise sources; i.e., float the system and provide the
necessary shielding and filtering to prevent coupling by other means.

       (2) Connect the return or low side of the generator-load loop to one of the reference planes, but not
at both.

       (3) Reduce the impedance of the path connecting the two noise sources (the generator and the
load).

       (4) Reduce the magnitudes of noise voltages through the control of the currents producing them by
lowering the impedance through which these currents flow.

  b. Common reference plane. Practical electronics circuits typically are a collection of several source-
load combinations. These various source-load combinations may be functionally dependent on each
other. Hence each individual source-load pair cannot operate in isolation; there must be coupling between
pairs. For example, one source may be driving several loads; one load may be receiving signals from
several sources; or the load for one signal source may serve as the source for another load. At the circuit
level, numerous sources and loads are connected in an interrelated fashion and the use of individual return
paths for each source-load pair becomes impractical. It is more realistic to establish a common ground or
reference plane that serves as the return path for several signals. The control of undesired network
responses, particularly in high gain and/or higher frequency circuits, often requires the establishment of a

                               4-1


---

TM 5-690

common signal reference to which functional grouping of components, circuits, and networks can be
connected. Ideally, this common reference connection offers zero impedance paths to all signals for
which it serves as a reference. The several signal currents within the network can then return to their
sources without creating unwanted conductive coupling between circuits.

  c. Large common reference planes. At the equipment level, the individual signal reference planes for
the various networks must be connected together to prevent personnel shock hazards and to provide as
near as possible, the same signal reference for all networks. Thus, the signal reference plane may extend
over large distances within a facility. The assumption that this large reference plane provides zero
impedance paths is not valid; the series inductance and resistance of the conductors forming the signal
reference plane and the shunt capacitance to nearby conductive objects must be considered. Currents
flowing in the signal reference plane will develop voltages across this impedance and will produce
electric and magnetic fields around the conductors.

4-3. Design considerations

Adherence to the following design considerations should mitigate the effects of any extraneous EM
interference in Command, Control, Communications, Computer, Intelligence, Surveillance, and
Reconnaissance (C4ISR) facilities.

  a. Equipotential plane. The equipotential plane (described in chapter 3) shall be bonded to the earth
electrode subsystem at multiple points. Such an equipotential plane exists in a building with a metal or
raised floor or ceiling grid electrically bonded together, or, in a building with a concrete floor with a
ground grid imbedded in it, connected to the facility ground. Equipment cabinets are then connected to
the equipotential plane. Chassis are connected to the equipment cabinets and all components, signal
return leads, etc., are connected to the chassis. The equipotential plane is then terminated to the earth
electrode subsystem to assure personnel safety and a low impedance path to ground. Planes are not
required in areas of the facility where no communications equipment (CE) equipment is or will be
installed.

       (1) At high frequencies, the large conducting surface embedded in or on the floor under the
equipment to be grounded, presents a much lower characteristic impedance than a single wire, even if
both were improperly terminated because the characteristic impedance is a function of L/C. As the
capacitance to earth increases, the impedance decreases.

       (2) Normally, the capacitance of a metallic sheet to earth is higher than that of wire. If the size of
the sheet is increased and allowed to encompass more area, the capacitance increases. Also, the unit
length inductance decreases with width, which further decreases Zo.

       (3) If the dimensions of a metallic sheet increase extensively (as in the case of a conducting sub-
floor), the characteristic impedance approaches a very low value. In this case, even if the signal
equipotential plane were improperly terminated to the earth electrode subsystem, the impedance would be
quite low throughout a large portion of the spectrum. This, in turn, would establish an equipotential
reference plane for all equipment bonded to it. With this reference plane bonded to earth, the following
advantages are obtained.

          (a) Any "noisy" cable or conductor connected to the receptor through or along such a ground
plane will have its electric field contained between the conductor and the ground plane. The noise field
can be "shorted out" by filters and bond straps because the distance between these “transmission line”
conductors is very small. Shorting out the noise field has the desirable effect of keeping noise current
from flowing over the receptor case and along any antenna input cables.

4-2


---

                                                                                                                                TM 5-690

          (b) Filters at the interface terminals of equipment can operate more effectively when both
terminals of their equivalent “transmission line” are available. Access to both terminals allows short
connections to the equipotential plane from both terminals for filtering of noise generated from either
source or load. A large conducting surface makes it possible to contain the field carried by the offending
conductor in such a way that it can be more easily prevented from traveling further, and will also tend to
shield any rooftop antennas from cable runs below it.

       (4) The equipotential plane may be a solid sheet or may consist of a wire mesh. A mesh will
appear electrically as a solid sheet as long as the mesh openings or spacing of conductors are less than 1/8
wavelength at the highest frequencies of concern. When it is not feasible to include a fine mesh (either
overhead or under the equipment) a larger grid may be installed, but even then the mesh size should be
made as small as practicable. In all cases, the “design objective” (DO) is to keep the mesh size to less
than 1/8 wavelength at the highest frequencies of concern.

                                                            λ = c/ƒ

                         where c = velocity of light in free space = 3 x 108 meters/second

                                         ƒ = frequency in hertz (cycles/second)

       (5) Conducting media that can be utilized for ground distribution networks are Q-cell floor (if
available) or subfloor of aluminum, copper, or sheet metal laid underneath the floor tile. Since a large
solid conducting surface may not be economically feasible for some installations, a ground reference
plane, made up of a copper grid, should be considered. Copper-clad steel wire meshes with all crossovers
brazed are commercially available. They are obtainable in mesh spacings of from 5 to 61cm (2 to 24 in)
squares, in AWG wire sizes Nos. 6, 8, 10, and 12. It is normally furnished in 3.7m (12 foot) rolls, but can
be obtained in various widths up to 5.5m (18 feet). Electrically continuous stringers of raised floors may
also be used to serve as an equipotential plane. Ground connections can be made to either the grid or
stringer by direct bonding or manufactured ground “buses” and give grounding access at the floor surface.
Normally, if the grid is embedded in a concrete floor, the latter method provides the easiest grounding
source. Equipotential planes for existing facilities may be installed at or near the ceiling above the CE
equipment.

  b. Grounding and bonding. Intersite or inter-building common-mode noise voltages in the earth
contribute to the need for a low resistance of 10 ohms to earth at each facility. Even a resistance to earth
of as low as 10 ohms may not, however, alleviate all common mode noise on a data cable connecting two
separate locations or buildings.

       (1) While a low resistance may help, there will always be potential differences between any two
rods in the ground. The use of shielded, balanced twisted pair for all lower frequency equipment
interfaces is intended to provide additional common-mode rejection to those unavoidable noise voltages
which exist in any facility. This is not to say that the sources of noise in a facility cannot be controlled.
In fact, much can be done by equalizing the load between the phases of the alternating current (ac)
distribution system; by insuring that the neutral is grounded only at the service disconnecting means; by
limiting the quantity of leakage current from power line filter capacitors by using the smallest acceptable
value of capacitance; or by sharing common filtered lines with several pieces of equipment.

       (2) Bonding provides an electrical union between two metallic surfaces used to provide a low-
impedance path between them. Bonding is the procedure by which the conductive surface of a
subassembly or component is electrically connected to another. This prevents development of electrical
potentials between individual metal surfaces for all frequencies capable of causing interference.

                                                                                                                                         4-3


---

TM 5-690

  c. Shielding. Groups of equipment or subsystems may be made EM compatible by any combination of
three fundamental approaches: the interfering signal level may be reduced, the receptor susceptibility may
be reduced, or the attenuation of the path or paths over which interference is transmitted from source to
receptor may be increased. Radiated interference signals generated by EM fields may be effectively
attenuated by EM shielding, either at the source or at the receptor. Shielding, when properly designed and
implemented, offers significant wideband protection against EM radiation, where source and receptor are
not sufficiently separated for adequate free space radiation attenuation.

       (1) It is relatively easy to obtain 40 decibels (dB) of shielding effectiveness in a frequency range
above 100 kHz with a single shield, and values as high as 70 dB can be obtained with careful single-
shield construction. Where this is inadequate, double shields are normally used, providing shielding
values as high as 120 dB. Radiated energy may still be coupled into a susceptible device through a shield
of inadequate thickness, through holes penetrated for ventilation and other purposes, and through
imperfectly jointed shielded sections.

       (2) Precise calculation of shielding effectiveness, even for perfectly joined solid shields, depends
on the form of the shield and the type of field for which the shielding is to be used. Both electric and
magnetic coupling can occur. Normally, it is relatively easy to provide electric shielding. Magnetic
shielding, however, is more difficult to provide, particularly at frequencies below 100 kHz.

       (3) Shielding shall be integrated with other basic interference control measures such as filtering,
wire routing, cable and circuit layout, signal processing, spectrum control, and frequency assignment to
achieve operational compatibility of the equipment. The degree of shielding shall be determined by the
systems engineering process.

       (4) Shields shall be constructed from material that provides the required degree of signal
suppression without incurring unnecessary expense and weight. The selection of materials shall be based
upon: the amplitude and frequency of the signals to be attenuated, the characteristics of the EM field of
the signal (i.e., is the signal being coupled via inductive, capacitive, or free space means), configuration,
the installation constraints, and the corrosion properties.

       (5) Filters on power, control, and signal lines shall be installed in a manner that maintains the
integrity of the shield. Power line filters shall be completely shielded with the filter case grounded.
Filters on power control and signal lines shall be placed as close as possible to the point of penetration of
the case in order to avoid long, unprotected paths inside the equipment.

       (6) Several steps can be taken during the design and construction stages of a facility to minimize
subsequent common-mode noise problems in instrumentation, equipment, and systems. The
recommended steps should be recognized as being appropriate for interference control in general and not
limited strictly to common-mode noise.

         (a) Sensitive data and instrumentation facilities should be located as far as possible from high
voltage (66 kV and above) transmission lines.

         (b) The routing of data and signal lines should be perpendicular to main power lines wherever
possible. Where parallel runs cannot be avoided, maximum separation must be maintained. In many
instances, routing of the data and signal cables in ferrous conduit may be necessary.

         (c) Distribution feeders to the facility should be routed perpendicularly to high voltage power
lines, if possible. In any event, long parallel runs between distribution feeders and the main power line
should be avoided.

4-4


---

                                                                                                                                TM 5-690

         (d) Where overhead distribution lines are necessary, pre-assembled aerial cable should be used in
preference to open wires. Magnetic field is greatly reduced.

         (e) All internal distribution power conductors near sensitive test and measurement facilities and
carrying more than 5 amperes should be twisted. A suggested rate of twist is one complete twist for each
length equal to approximately 25 times the diameter of the insulated power conductor when physically
possible.

       (7) Metallic enclosures should be used for power conductors wherever possible to take advantage
of the shielding they offer. In order of preference, the types of enclosures recommended are:

          (a) Rigid steel conduit is the most effective enclosure for power conductors from the standpoint
of noise reduction and should be used wherever practical. Electrical metallic tubing (EMT) and rigid
aluminum or copper conduit provide effective electrostatic shielding, but their magnetic shielding
properties are at least an order-of-magnitude poorer than rigid steel conduit.

           (b) Armored cable is sometimes used in lieu of conduit and individual insulated conductors.
The armor provides an effective electrostatic shield but is not as effective as rigid steel conduit for
magnetic shielding. Steel armor is preferable to aluminum or bronze.

           (c) Standard construction grade flexible conduit is a poorer electrostatic shield than either of the
above because of its construction and provides considerably less magnetic shielding than rigid steel
conduit. It is recommended that the use of flexible conduit be restricted to short lengths and only where
required to absorb vibration or to permit position adjustment of the equipment or device served.

           (d) Wireways, which are rectangular sheet metal duct-like enclosures and cable trays, are not
nearly as effective for electrostatic or magnetic shields as rigid steel conduit. Unless the wireway or cable
tray is made of a ferrous metal and all discontinuities are carefully bonded, its use for the shielding of
power conductors should be limited.

       (8) The effect of RF radiation on living tissue is thought to be primarily thermal in nature. The
most vulnerable parts of the human body are nerves, skin, and muscles. However, other parts that can be
affected are the brain, the eyes and the testes. The thermal effects can range from mild heating of the skin
or organs to fatal damage. To minimize possible hazards from RF radiation, Dept of Defense Instruction
6055.11 (9-4) provides recommendations to prevent possible harmful effects in human beings exposed to
radio frequency radiation.

          (a) Below 1000 MHz, RF energy penetrates deeply into the body. These frequencies are
extremely hazardous since the radiation is not detected by the nerve endings located in the skin. The
power absorbed in the body tissues can be as high as 40% of the incident power. The urinary bladder,
gall bladder, and parts of the gastro-intestinal tract are particularly vulnerable since they are not cooled by
an abundant flow of blood. Also, stainless steel and platinum bone implants and fillings in teeth can
increase in temperature when subjected to RF radiation, resulting in burning of tissues.

          (b) In the 2-5 GHz region of the RF spectrum, the eyes and the testes are the most vulnerable
organs to RF radiation damage. Damage to the eyes is generally irreversible and can result in blindness
from cataracts or loss of lens transparency. Animal experiments have shown that damage to the testes
from low levels of exposure does not differ from that caused by common forms of heat applied to the
testes, and that the reduction in testicular function due to heating appears to be temporary. It is not known
if RF radiation produces any genetic damage.

                                                                                                                                         4-5


---

TM 5-690

       (9) Various organizations and countries have developed exposure standards and guidelines over
the past several decades. In North America and most of Europe exposure standards and guidelines have
generally been based on exposure levels where effects considered harmful to humans occur. Safety
factors are then incorporated to arrive at specific levels of exposure to provide sufficient protection for
various segments of the population. The Federal Communications Commission (FCC) Office of
Engineering and Technology Bulletin 56 (OET-56) discusses in great detail the recommended human
exposure limits to RF radiation for the general public and occupational exposures. The ANSI/IEEE
document (ANSI/IEEE C95.3-1992) entitled, "Recommended Practice for the Measurement of Potentially
Hazardous Electromagnetic Fields - RF and Microwave," contains practical guidelines, required
instrumentation and information for performing RF field measurements.

  d. Aperture control. Unnecessary apertures shall be avoided. Only those shield openings needed to
achieve proper functioning and operation of the equipment shall be provided.

       (1) Controls, switches, and fuse holders shall be mounted such that close metal-to-metal contact is
maintained between the cover or housing of the devices and the case.

       (2) Where non-conductive control shafts are necessary, a waveguide-below-cutoff metal sleeve
(for the highest frequency of concern) shall be peripherally bonded to the case for the shaft.

       (3) The cutoff frequency for the waveguide shall be considerably higher than the equipment
operating frequency. The length of the sleeve shall be no less than three times its diameter.

       (4) Pilot lights shall be filtered or shielded as needed to maintain the required degree of shielding
effectiveness.

       (5) If possible, ventilation and drainage holes shall not penetrate radio frequency (RF)
compartments. If necessary, such holes shall utilize waveguide-below-cutoff honeycomb or other
appropriate screening. Care shall be taken to assure the honeycomb and screens are well bonded to the
shield completely around the opening.

  e. RED/BLACK equipment. Specific requirements concerning the installation of RED/BLACK
equipment is contained in MIL-HDBK-232A, Red/Black Engineering-Installation Guidelines. This
manual will provide the general requirements expected to provide interference protection for signals
generated from these installations.

       (1) Physical barriers should be provided at the perimeter of the facility to ensure that the earth
electrodes are not degraded or tapped, or that pickup devices are not introduced into the system.

       (2) Each RED/BLACK facility should use a facility entrance plate with all conductors entering the
facility passing through this plate. The entrance plate should extend approximately one foot from the
nearest conduit or cable penetrations. All signal cables entering the facility should be shielded, with the
shield circumferentially bonded to the plate. These cables should be either filtered or isolated and
protected by surge arresters or other protective devices. The entrance plate should be bonded to the earth
electrode subsystem using two #1/0 AWG cables.

       (3) Internally the interference barrier between RED and BLACK equipment consists of physical
separation, shielding of cables, and encrypting or filtering signal lines which connect the RED/BLACK
equipment. All equipment shields should be grounded to the equipotential plane at every convenient
point.

4-6


---

                                                                                                                                TM 5-690

4-4. Typical components and installation details

Typical components and installation details for electromagnetic interference (EMI) protection systems are
described below.

  a. Shielding. Coupling is defined as the means by which a magnetic or electric field produced by one
circuit induces a voltage or current in another circuit. Interference coupling is the stray or unintentional
coupling between circuits, which produces an error in the response of one of the circuits. An effective
means for the reduction of coupling is the use of shields around the circuits and around interconnecting
lines.

       (1) To determine the shielding required at a facility, the EM environment at the planned location
should first be surveyed. The threat should be compared with the response properties or susceptibilities
of the equipment to be located in that environment. If a need for shielding is indicated, then it should be
provided either as a part of the facility or the equipment shielding should be upgraded.

       (2) Conduct an EM survey at the facility location using the proper equipment and experienced
personnel, examine the history of performance of the similar equipment at other sites with comparable
environments, and consider the measured EMI characteristics of the equipment.

       (3) Determine the amount of shielding necessary. If the measured signal strength is greater than
the susceptible level, arrange to provide the extra shielding necessary either as part of the structure or
building or require that the equipment’s shielding be upgraded. If susceptibility data is not available,
make a best estimate of the amount of required shielding from the historical performance of the
equipment (or similar types) at other sites.

       (4) Before deciding what type or how much supplemental shielding material is necessary, estimate
the amount of shielding inherently provided by conventional building materials and techniques. Estimate
the shielding provided by normal construction techniques (steel skeleton with brick or concrete block
exterior with standard wood, gypsum board, or concrete block interior walls). Reinforced concrete offers
additional shielding because of the presence of the rebar. Estimate the shielding effectiveness of single
course rebar to low frequency magnetic fields.

       (5) Design the shielding to conform to the needs of the system. Consider the relative ease of
shielding individual equipment rather than shielding a room or the entire structure.

       (6) Assure that the shielding provided is sufficient to meet system needs (both known and
predicted) but do not excessively over design.

       (7) Use the inherent shielding properties of the structure to maximum advantage. Employ the
small amount of shielding (typically 10-20 dB) offered by reinforced concrete. However, do not expect
common building materials such as brick, concrete, wood, fiberglass, or plastic to provide any significant
shielding to EM signals.

       (8) Locate most sensitive and most critical equipment as close to the core of the structure as
operational requirements will permit.

       (9) To minimize the attenuation requirements on shields, predetermine the location of likely
sources of interference such as power substations, engine-generators, and RF transmitters; maximize the
separation between such sources and potentially susceptible equipment or systems.

                                                                                                                                         4-7


---

TM 5-690

       (10) Where a choice exists as to exterior skin materials for the shelter or structure (e.g., fiberglass
versus sheet steel or aluminum) choose metals to take advantage of their improved shielding properties.
(In order to utilize metal sidings as effective shields, seams must be electrically continuous.)

       (11) Insure that shield continuity is maintained at points of entry of signal cables, power
conductors, utility lines, and ground conductors.

       (12) Make sure that windows, doors, and ventilation ports are shielded along with the walls. Use
well bonded screen wire for windows, use metal doors, and apply honeycomb ducts or appropriate
screening over ventilation ports.

       (13) Equip all power lines supplying shielded areas with power line filters.

       (14) Use steel conduit in preference to aluminum conduit to take advantage of the improved
magnetic shielding properties of steel.

       (15) Use enclosed metal wiring ducts or raceways in preference to open mesh or unenclosed types.

       (16) If the only purpose of the shield is to establish a personnel barrier to prevent inadvertent
contact with direct current (dc) and power frequency hazardous voltages, consider the use of non-
conductive shields which may be less expensive. (If metal shields are used to provide shock protection,
they must be well grounded to the power safety ground - the green wire network.)

       (17) The selection of a shielding material can be done either by choosing a possible metal of a
given thickness and then determining if the shielding effectiveness is equal to or greater than the field
attenuation desired, or starting with desired attenuation, determining what thickness of metal sheet or
what type of screen is required. Either approach is acceptable.

          (a) The first step in the selection of a shield type and material is to determine the nature of the
field by determining whether it is an electric field, magnetic field, or a plane wave.

          (b) Compute the wavelength, or the incident signal or signals and measure the location of the
sources. From this a determination is made of the incident field and the absorption and reflection loss of
the material selected for a plane wave.

          (c) The total shielding effectiveness is the sum of the absorption loss and the reflection loss.
Consider the use of thin metal foils for shielding high frequency (broadcast frequencies and above) plane
and electric fields.

       (18) Employ the following installation guidelines when constructing shielded facilities.

          (a) Securely ground all metal shields.

          (b) All seams and joints must be well bonded. Welded seams are highly desirable in enclosures,
which must provide a high degree 80 dB of RF shielding or are intended for EMP protection. Where
welding is impractical, solder or knitted wire gaskets should be used to supplement the mechanical
fasteners.

          (c) Limit openings (windows, doors, ventilation ports) and penetrations (signal lines, power lines,
utilities) to the lowest possible number and restrict their dimensions to a minimum.

4-8


---

                                                                                                                                TM 5-690

         (d) If holes through the shield are necessary, determine the optimum size and spacing.

         (e) Use honeycomb for the shielding of ventilation ports wherever possible.

         (f) Peripherally bond metallic utility lines to the shield at the point of entrance. Non-metallic
lines entering through waveguide-below-cutoff ducts or tubes may also be used for water, gas,
compressed air, etc.

         (g) Cover all openings required for visual access with wire screen or conductive glass. Ensure
that the screen or glass is carefully bonded to the enclosure around the perimeter of the opening.

         (h) Doors should be metal with solid, uniform contact around the edges. Wire mesh gaskets or
finger stock should be provided.

         (i) For large shielded enclosures where high traffic volume is expected, consider the use of
waveguide-below-cutoff hallways.

  b. Bonding. Bonding is the process by which a low impedance path for the flow of an electric current
is established between two metallic objects. Bonding is concerned with the techniques and procedures
necessary to achieve a mechanically strong, low impedance interconnection between metal objects and to
prevent the path thus established from subsequent deterioration through corrosion or mechanical
looseness. With proper design and implementation, bonds minimize differences in potential between
points within the fault protection, signal reference, shielding, and lightning protection networks of an
electronic system. Poor bonds, however, lead to a variety of hazardous and interference-producing
situations. Loose or high impedance joints in signal lines are particularly annoying because of
intermittent signal behavior such as decreases in signal amplitude, increases in noise level, or both.

       (1) A degradation in system performance from high noise levels is frequently traceable to poorly
bonded joints in circuit returns and signal referencing networks. The reference network provides low
impedance paths for potentially incompatible signals. Poor connections between elements of the
reference network increase the resistance of the current paths. The voltages developed by the currents
flowing through these resistances prevent circuit and equipment signal references from being at the same
reference potential. When such circuits and equipment are interconnected, the voltage differential
represents an unwanted signal within the system.

       (2) Bonding is also important to the performance of other interference control measures. For
example, adequate bonding of connector shells to equipment enclosures is essential to the maintenance of
the integrity of cable shields and to the retention of the low loss transmission properties of the cables.
The careful bonding of seams and joints in EM shields is essential to the achievement of a high degree of
shielding effectiveness.

       (3) Interference reduction components and devices also must be well bonded for optimum
performance. If a joint in a current path is not securely made or works loose through vibration, it can
behave like a set of intermittent contacts. Even if the current through the joint is at dc or at the ac power
frequency, the sparking which occurs may generate interference signals with frequency components up to
several hundred megahertz. Poor bonds in the presence of high level RF fields, such as those in the
immediate vicinity of high-powered transmitters, can produce a particularly troublesome type of
interference. Poorly bonded joints have been shown to generate cross modulation and other mix products
when irradiated by two or more high level signals. Some metal oxides are semiconductors and behave as
non-linear devices to provide the mixing action between the incident signals. Interference thus generated
can couple into nearby susceptible equipment.

                                                                                                                                         4-9


---

TM 5-690

       (4) A primary requirement for effective bonding is that a low resistance path be established
between the two joined objects. The resistance of this path must remain low with use and with time. The
limiting value of resistance at a particular junction is a function of the current (actual or anticipated)
through the path. Noise minimization requires that path resistances of less than 50 milliohms be
achieved. However, noise control rarely ever requires resistances as low as those necessary for fault and
lightning currents.

          (a) A bonding resistance of 1 milliohm is considered to indicate that a high quality junction has
been achieved. Experience shows that 1 milliohm can be reasonably achieved if surfaces are properly
cleaned and adequate pressure is maintained between the mating surfaces.

          (b) A much lower resistance could provide greater protection against very high currents, but
could be more difficult to achieve at many common types of bonds such as at connector shells, between
pipe sections, etc. However, there is little need to strive for a junction resistance that is appreciably less
than the intrinsic resistance of the conductors being joined.

       (5) Direct bonding is the establishment of the desired electrical path between the interconnected
members without the use of an auxiliary conductor. Specific portions of the surface areas of the members
are placed in direct contact. Electrical continuity is obtained by establishing a fused metal bridge across
the junction by welding, brazing, or soldering or by maintaining a high pressure contact between the
mating surfaces with bolts, rivets, or clamps. Examples of direct bonds are the splices between bus bar
sections, the connections between lightning down conductors and the earth electrode subsystem, the
mating of equipment front panels to equipment racks, and the mounting of connector shells to equipment
panels.

          (a) Properly constructed direct bonds exhibit a low dc resistance and provide RF impedance as
low as the configuration of the bond members will permit. Direct bonding is always preferred; however,
it can be used only when the two members can be connected together and can remain so without relative
movement. The establishment of electrical continuity across joints, seams, hinges, or fixed objects that
must be spatially separated requires indirect bonding with straps, jumpers, or other auxiliary conductors.

          (b) The objective in bonding is to reduce the bond resistance to a value negligible in comparison
to the conductor resistance so that the resistance of the conductors primarily determines the total path
resistance.

          (c) Metal flow processes such as welding, brazing, and silver soldering provide the lowest values
of bond resistance. With such processes, the resistance of the joint is determined by the resistivity of the
weld or filler metal, which can approach that of the metals being joined. The bond members are raised to
temperatures sufficient to form a continuous metal bridge across the junction.

          (d) For reasons of economy, future accessibility, or functional requirements, metal flow
processes are not always the most appropriate bonding techniques. It may then be more appropriate to
bring the mating surfaces together under high pressure. Auxiliary fasteners such as bolts, screws, rivets,
or clamps are employed to apply and maintain the pressure on the surfaces. The resistance of these bonds
is determined by the kinds of metals involved, the surface conditions within the bond area, the contact
pressure at the surfaces, and the cross-sectional area of the mating surfaces.

       (6) In terms of electrical performance, welding is the ideal method of bonding. An effective
welding technique for many bonding applications is the exothermic mixture of aluminum, copper oxide,
and other powders. The mixture is held in place around the junction by a joint with a graphite mold. The
mixture is ignited and the heat generated (in excess of 4000°F) reduces the copper oxide to provide a

4-10


---

                                                                                                                                TM 5-690

homogeneous copper blanket around the junction. Because of the high temperatures involved, copper
materials can be bonded to steel or iron as well as to other copper materials.

          (a) The intense heat involved is sufficient to boil away contaminating films and foreign
substances. A continuous metallic bridge is formed across the joint, and the conductivity of this bridge
typically approximates that of the bond members. The net resistance of the bond is essentially zero
because the bridge is very short relative to the length of the bond members. The mechanical strength of
the bond is high; the strength of a welded bond can approach or exceed the strength of the bond members
themselves. Since no moisture or contaminants can penetrate the weld, bond corrosion is minimized.
The erosion rate of the metallic bridge should be comparable to that of the base members; therefore, the
lifetime of the bond should be as great as that of the bond members.

          (b) Welds should be utilized whenever practical for permanently joined bonds. Although
welding may be a more expensive method of bonding, the reliability of the joint makes it very attractive
for bonds that will be inaccessible once construction is completed. Most metals that will be encountered
in normal construction can be welded with one of the standard welding techniques

       (7) Brazing to include silver soldering is another metal flow process for permanent bonding. In
brazing, the bond surfaces are heated to a temperature above 800°F but below the melting point of the
bond members. A filler metal with an appropriate flux is applied to the heated members which wets the
bond surfaces to provide intimate contact between the brazing solder and the bond surfaces.

       (8) Soft soldering is an attractive metal flow bonding process because of the ease with which it can
be applied. Relatively low temperatures are involved and it can be readily employed with several of the
high conductivity metals such as copper, tin, and cadmium. With appropriate fluxes, aluminum and other
metals can be soldered. Properly applied to compatible materials, the bond provided by solder is nearly
as low in resistance as one formed by welding or brazing. Because of its low melting point, however, soft
solder should not be used as the primary bonding material where high currents may be present.

          (a) In addition to its temperature limitation, soft solder exhibits low mechanical strength and
tends to crystallize if the bond members move while the solder is cooling. Therefore, soft solder should
not be used if the joint must withstand mechanical loading. The tendency toward crystallization must also
be recognized and proper precautions observed when applying soft solder. Soft solder can be used
effectively in a number of ways. For example, it can be used to tin surfaces prior to assembly to assist in
corrosion control.

          (b) Soft solder can be used effectively for the bonding of seams in shields and for the joining of
circuit components together and to the signal reference subsystem associated with the circuit. Soft solder
is often combined with mechanical fasteners in sweated joints. By heating the joint hot enough to melt
the solder, a low resistance filler metal is provided which augments the path established by the other
fasteners; in addition, the solder provides a barrier to keep moisture and contaminants from reaching the
mating surfaces.

       (9) In many applications, permanent bonds are not desired. For example, equipment must be
removed from enclosures or moved to other locations that require ground leads and other connections
must be broken. The most common semi-permanent bond is the bolted connection (or one held in place
with machine screws, lag bolts, or other threaded fasteners) because this type bond provides the flexibility
and accessibility that is frequently required. The bolt (or screw) should serve only as a fastener to provide
the necessary force to maintain the 1200-1500 psi pressure required between the contact surfaces for
satisfactory bonding. Examples are shown in figure 4-1.

                                                                                                                                       4-11


---

TM 5-690

                            Figure 4-1. Connection of bonding jumpers to flat surface
4-12


---

                                                                                                                                TM 5-690
       (10) Riveted bonds are less desirable than bolted connections or joints bridged by metal flow
processes. Rivets lack the flexibility of bolts without offering the degree of protection against corrosion
of the bond surface that is achieved by welding, brazing, or soldering. The chief advantage of rivets is
that they can be rapidly and uniformly installed with automatic tools. Examples of riveted bonds are
shown in figure 4-2.

                                            Figure 4-2. Examples of bonding
                                                                                                                                       4-13


---

TM 5-690

           (a) The current path through a rivet is theorized to be through the interface between the bond
members and the rivet body. This theory is justified by experience, which shows that the fit between the
rivet and the bond members is more important than the state of the mating surfaces between the bond
members. Therefore, the hole for the rivet must be a size that provides a close fit to the rivet after
installation. The sides of the hole through the bond members must be free of paint, corrosion products, or
other non-conducting material.

           (b) For riveted joints in shields, the maximum spacing between rivets is recommended to be
approximately 2 cm (3/4 inch) or less. In relatively thin sheet metal, rivets can cause bowing of the stock
between the rivets. In the bowed or warped regions, metal-to-metal contact may be slight or non-existent.

           (c) These open regions allow RF energy to leak through and can be a major cause of poor RF
shield performance. By spacing the rivets close together, warping and bowing are minimized. For
maximum RF shielding, the seam should be gasketed with some form of wire mesh or conductive epoxy
to supplement the bond path of the rivets.

       (11) Conductive adhesive is a silver-filled, two-component, thermosetting epoxy resin, which when
cured produces an electrically conductive material. It can be used between mating surfaces to provide
low resistance bonds. It offers the advantage of providing a direct bond without the application of heat as
is required by metal flow processes. In many locations, the heat necessary for metal flow bonding may
pose a fire or explosion threat. When used in conjunction with bolts, conductive adhesive provides an
effective metal-like bridge with high corrosion resistance along with high mechanical strength. In its
cured state, the resistance of the adhesive may increase through time. It also tends to adhere tightly to the
mating surfaces and thus an epoxy-bolt bond is less convenient to disassemble than a simple bolted bond.
In some applications, the advantages of conductive adhesive may outweigh this inconvenience.

       (12) The preferred method of bonding is to connect the objects together with no intervening
conductor. Unfortunately, operational requirements or equipment locations often preclude direct bonding.
When physical separation is necessary between the elements of an equipment complex or between the
complex and its reference plane, auxiliary conductors must be incorporated as bonding straps or jumpers.
Such straps are commonly used for the bonding of shock mounted equipment to the structural ground
reference.

           (a) Bond straps or cables are also used for bypassing structural elements, such as the hinges on
distribution box covers or on equipment covers, to eliminate the wideband noise generated by these
elements when illuminated by intense radiated fields or when carrying high level currents. They may also
be used to prevent static charge buildup and to connect metal objects to lightning down conductors to
prevent flashover.

           (b) The resistance of an indirect bond is equal to the sum of the intrinsic resistance of the
bonding conductor and the resistances of the metal-to-metal contacts at each end. The resistance of the
strap is determined by the resistivity of the material used and the dimensions of the strap. With typical
straps, the dc bond resistance is small. With aluminum, copper, or brass straps, these resistances should
be less than 0.1 milliohm with properly made connections. If long straps are required, however, the
resistance of the conductor can be significant.

           (c) Because high conductivity materials attenuate RF rapidly, high frequency currents do not
penetrate into conductors very far, i.e., they tend to stay near the surface. At frequencies where this “skin
effect” becomes significant, the ac resistance of the bond strap can differ significantly from its dc value.

4-14


---

                                                                                                                                TM 5-690

           (d) The geometrical configuration of the bonding conductor and the physical relationship
between objects being bonded introduce reactive components into the impedance of the bond. The strap
itself exhibits an inductance that is related to its dimensions. Even at relatively low frequencies, the
reactance of the inductive component of the bond impedance becomes much larger than the resistance.
Thus, in the application of bonding straps, the inductive properties as well as the resistance of the strap
must be considered. The physical size of the bonding strap is important because of its effect on the RF
impedance. As the length of the strap is increased, its impedance increases non-linearly for a given
width; however, as the width increases, there is a non-linear decrease in strap impedance. In many
applications, braided straps are preferred over solid straps because they offer greater flexibility. There is
no significant difference between the impedance of the braided or solid strap for frequencies up to 10
MHz. Because the strands are exposed they are more susceptible to corrosion; braided straps may be
undesirable for use in some locations for these reasons. Fine braided straps also are generally not
recommended because of higher impedances at the higher frequencies as well as lower current carrying
capacities.

           (e) A certain amount of stray capacitance is inherently present between the bonding jumper and
the objects being bonded as well as between the bonded objects themselves. At low frequencies where
the reactance of the strap is low, bonding straps will provide effective bonding. At frequencies where
parallel resonance exists in the bonding network, straps may severely enhance the pickup of unwanted
signal. Above the parallel resonant frequency, bonding straps do not contribute to the pickup of radiated
signals either positively or negatively. In conclusion, bonding straps should be designed and used with
care with special note taken to ensure that unexpected interference conditions are not generated by the use
of such straps.

       (13) To achieve an effective and reliable bond, the mating surfaces must be free of any foreign
materials, e.g., dirt, filings, preservatives, etc., and non-conducting films such as paint, anodizing, and
oxides and other metallic films. Various mechanical and chemical means can be used to remove the
different substances, which may be present on the bond surfaces. After cleaning, the bond should be
assembled or joined as soon as possible to minimize recontamination of the surfaces. After completion of
the joining process the bond region should be sealed with appropriate protective agents to prevent bond
deterioration through corrosion of the mating surfaces.

           (a) Solid material such as dust, dirt, filings, lint, sawdust, and packing materials impede metallic
contact by providing mechanical stops between the surfaces. They can affect the reliability of the
connection by fostering corrosion. Dust, dirt, and lint will absorb moisture and will tend to retain it on
the surface. They may even promote the growth of molds, fungi, and bacteriological organisms that give
off corrosive products. Filings of foreign metals can establish tiny electrolytic cells that will greatly
accelerate the deterioration of the surfaces.

           (b) The bond surface should be cleaned of all such solid materials. Mechanical means such as
brushing or wiping are generally sufficient. Care should be exercised to see that all materials in grooves
or crevices are removed. If a source of compressed air is available, air blasting is an effective technique
for removing solid particles if they are dry enough to be dislodged.

           (c) Paints, varnishes, lacquers, and other protective compounds along with oils, greases, and
other lubricants are non-conductive and in general, should be removed. Commercial paint removers can
be used effectively.

           (d) Lacquer thinner works well with oil-based paints, varnish, and lacquer. If chemical solvents
cannot be used effectively, mechanical removal with scrapers, wire brushes, power sanders, sandpaper, or
blasters should be employed. When using mechanical techniques, care should be exercised to avoid

                                                                                                                                       4-15


---

TM 5-690

removing excess material from the surfaces. Final cleaning should be done with a fine, such as 400-grit,
sandpaper or steel wool. After all of the organic material is removed, abrasive grit or steel wool filaments
should be brushed or blown away. A final wipe down with denatured alcohol, dry cleaning fluid, or
lacquer thinner should be accomplished to remove any remaining oil or moisture films.

          (e) Many metals are plated or coated with other metals or are treated to produce surface films to
achieve improved wearability or provide corrosion resistance. Metal plating such as gold, silver, nickel,
cadmium, tin, and rhodium should have all foreign solid materials removed by brushing or scraping and
all organic materials removed with an appropriate solvent. Since such platings are usually very thin, acids
and other strong etchants should not be used. Once the foreign substances are removed, the bond surfaces
should be burnished to a bright shiny condition with fine steel wool or fine grit sandpaper. Care must be
exercised to see that excessive metal is not removed. Finally, the surfaces should be wiped with a cloth
dampened in a denatured alcohol or dry cleaning solvent and allowed to dry before completing the bond.

          (f) Chromate coatings such as iridite-14, iridite-18P, oadkite-36, and alodine-1000 offer low
resistance as well as provide corrosion resistance. These coatings should not be removed.

          (g) Many aluminum products are anodized for appearance and corrosion resistance. Since these
anodic films are excellent insulators, they must be removed prior to bonding. Those aluminum parts to be
electrically bonded either should not be anodized or the anodic coating must be removed from the bond
area.

          (h) Corrosion by-products such as oxides, sulfides, and sulfates must be removed because they
restrict or prevent metallic contact. Soft products such as iron oxide and copper sulfate can be removed
with a stiff wire brush, steel wool, or other abrasives. Removal down to a bright metal finish is generally
adequate. When pitting has occurred, refinishing of the surface by grinding or milling may be necessary
to achieve a smooth, even contact surface. Some sulfides are difficult to remove mechanically and
chemical cleaning and polishing may be necessary. Oxides of aluminum are clear and thus the
appearance of the surface cannot be relied upon as an indication of the need for cleaning. Although the
oxides are hard, they are brittle and roughening of the surface with a file or coarse abrasive is an effective
way to prepare aluminum surfaces for bonding.

       (14) After cleaning of the mating surfaces, the bond members should be assembled or attached as
soon as possible. Assembly should be completed within 30 minutes if at all possible. If more than 2
hours is required between cleaning and assembly, a temporary protective coating must be applied. Of
course, this coating must also be removed before completing the bond.

          (a) The bond surfaces must be kept free of moisture before assembly, and the completed bond
must be sealed against the entrance of moisture into the mating region. Acceptable sealants are paint,
silicone rubber, grease, and polysulfates. Where paint has been removed prior to bonding, the completed
bond should be repainted to match the original finish. Excessively thinned paint should be avoided;
otherwise, the paint may seep under the edges of the bonded components and impair the quality of the
connection. Compression bonds between copper conductors or between compatible aluminum alloys
located in readily accessible areas not subject to weather exposure, corrosive fumes, or excessive dust do
not require sealing.

          (b) Corrosion is the deterioration of a substance (usually a metal) because of a reaction to its
environment. Most environments are corrosive to some degree. Those containing salt sprays and
industrial contaminants are particularly destructive. Bonds exposed to these and other environments must
be protected to prevent deterioration of the bonding surfaces to the point where the required low
resistance connection is destroyed.

4-16


---

                                                                                                                                TM 5-690

          (c) Paint or metallic platings used for the purpose of excluding moisture or to provide a third
metal compatible with both bond members should be applied with caution. When they are used, both
members must be covered. Covering the anode alone must be avoided. If only the anode is covered, then
at imperfections and breaks in the coating corrosion will be severe because of the relatively small anode
area. All such coatings must be maintained in good condition.

  c. Entry plates. All metallic penetrations of the facility shielding should enter at a common location,
and all shielded cables, conduits, and pipes should be bonded to an entry plate. This plate should be large
enough so that no penetrations will occur within 1 foot of the nearest edge. The entrance plate should be
continuously welded around its perimeter to the building shield. The entry plate should be connected to
the earth electrode subsystem with a 1/0 AWG (minimum) insulated copper cable. The cable should be
bonded to the entry plate and the earth electrode subsystem with exothermic welds. The conduit should
be of steel with threaded or welded couplings. Conduit runs should be as short as practical with joints
held to a minimum.

       (1) Effective transient protection can be provided by peripherally bonding each RF coaxial cable
to a metal bulkhead connector that in turn is peripherally bonded to the building entry plate and grounded
to the earth electrode subsystem. This scheme will route transient currents from cable shields to earth
ground instead of through terminating equipment to ground. Also, transient surge currents will be
shunted to ground before transient energy is cross-coupled to other equipment lines in the facility. The
entry plate must contain the required number of appropriate coaxial feed through connectors to terminate
all applicable incoming lines. The connectors must also provide a path to ground for connected cable
shields. If external and internal coaxial cables are of a different physical size, the changeover in
connector size should be accomplished by the feed through connectors of the entry plate.

       (2) The shields of all telephone cables entering a CE facility must be bonded to each other and to
the earth electrode subsystem through the steel entry plate. This measure eliminates harmful differences
of potential between the various telephone cables entering the facility. It is important that electrical
continuity of all cable shields is maintained. Care must be taken to ensure that shields of aerial telephone
cables are bonded to any connecting buried or underground cable shields. This provides a path to ground
for lightning and power currents and provides an effective noise shield.

       (3) Configuration control must be considered during the design phase. Conducting penetrations
must be bonded carefully around the penetration perimeter (360 degrees) to the shield entry plate to
prevent aperture coupling to the facility interior or to inner conductors of shielded cables. Non-
conducting penetrations must be treated as apertures in the shield.

  d. Filters. The majority of interfering signals, even if they are free-space coupled to the signal and
power lines, are conductively coupled into the susceptible circuit. The proper application of filters to both
the signal and power lines can reduce this coupling.

       (1) It is essential to avoid signal penetration via power and signal wiring. This demands that filters
achieving adequate insertion loss be installed in all incoming cables; it is fairly normal to have three-
phase power circuits and several hundred signal lines going into a large enclosure. It is essential that the
filters provide the specified attenuation under full-load conditions at all frequencies. Unless the filter
attenuation is maintained at all frequencies and load currents, the overall shield attenuation will be
degraded by the signal penetration via the filters. Shield penetrations may also be provided for air, gas,
and water lines; these can be achieved either by the use of waveguide-below-cutoff tubes carrying
insulating piping or by welding metal pipe to the shield. It is essential that all input circuits and
penetrations occur in a localized area.

                                                                                                                                       4-17


---

TM 5-690

       (2) All power line filter cases shall be directly bonded to the equipment case or enclosure. Filters
shall be bonded to any subassembly enclosure used to maintain shield effectiveness.

       (3) Filters on power, control, and signal lines shall be installed in a manner that maintains the
integrity of the shield. Power line filters shall be completely shielded with the filter case. Filters on
power control and signal lines shall be placed as close as possible to the point of penetration of the case in
order to avoid long, unprotected paths inside the equipment. Mount filters for power and control cables
inside the shield and extend the filter input terminals through the shield.

       (4) DC power equipment has been found to be a significant electrical noise source that can be
minimized through proper configuration of the facility, the physical and electrical isolation of the dc
power equipment from communications equipment, and filtering of the output. Certain communications
equipment with inverter or switching type power supplies also cause electrical noise on the dc supply
leads and the ac input power leads. This noise can be minimized by the use of decentralizing filters at or
in the equipment. The location, number, and termination of the dc reference ground leads are also
important elements in providing adequate protection for dc systems and, at the same time, minimizing
electrical noise and dc currents in the ground system.

       (5) AC line filters can cause ac currents in the ground system when distributed in various areas of
the facility. This is due to ac current passing through capacitors in the ac line filters when the lines are
filtered to ground. Power line filters should not induce more than 30 milliamperes of current to the fault
protection subsystem.

       (6) Linear filters may also be used as barrier elements on penetrating wires, but at the outer
(facility-level) barrier, filters are always used in combination with surge arresters. On power lines, for
example, the line filter usually cannot tolerate the peak voltages, so a spark-gap surge arrester is used to
limit the voltage, and the filter isolates the interior circuits from the negative dynamic resistance and
shock excitation of the spark-gap discharge. The shunt input capacitance of the filter may also be used to
reduce the rate-of-rise of the voltage, so that the firing voltage of the surge arrester will be lower. A
variety of low-pass, bandpass, and high-pass filters are available for power and signal line protection.

4-5. Interfaces with other grounding and bonding subsystems

The grounding required for EMI protection is a part of the total facility grounding network. The ultimate
path to ground is the earth electrode subsystem. Protection against EMI is imperative for sensitive
electronic equipment to ensure a workable and secure system. Grounding for this protection interfaces
with each of the major subsystems. The main interface is the earth electrode subsystem which in turn ties
in with the fault protection subsystem, the lightning protection subsystem, and the signal reference
subsystem.

4-6. Inspections and testing

Thorough inspection and testing programs are imperative to assess the effectiveness of the EMI protection
measures utilized.

  a. Inspections. Inspect the facility for the following.

       (1) Verify that the EM survey at the facility has been properly performed and documented.

       (2) Verify that shielding provided is sufficient to meet system needs (both known and predicted).

4-18


---

                                                                                                                                TM 5-690

       (3) Verify that shield continuity is maintained at points of entry of signal cables, power
conductors, utility lines, and ground conductors.

       (4) Verify that windows, doors, and ventilation ports are shielded along with the walls.
       (5) Verify that all power lines supplying the shielded areas are protected with power line filters.
       (6) Verify that all electrical conduit is steel inside the shielded areas.
       (7) Verify that any wiring ducts are totally enclosed.
       (8) Verify that all metal shields are grounded.
       (9) Verify that all seams and joints are well bonded by welding, solder, or knitted wire gaskets.
       (10) Verify that all metallic utility lines are bonded to the shield at the point of entrance.
       (11) Verify that all openings required for visual access are covered with wire screen or conductive
glass and that the screen or glass is carefully bonded to the enclosure around the perimeter of the opening.
       (12) Verify that all doors are metal with solid, uniform contact around the edges.
       (13) Verify that all bonds are of the type that will provide the least resistance possible for the
application, preferably direct bonding with no intervening conductor.
       (14) Verify that the bonding surfaces are cleaned of all such solid materials and moisture.
       (15) After bonding, verify that the completed bond is sealed against the entrance of moisture into
the mating region.
       (16) Verify that all metallic penetrations and shielded cables through the facility shield are bonded
to the entry plate.
       (17) Verify that each RF coaxial cable is bonded to the entry plate with a metal bulkhead
connector, which is bonded to the building entry plate and grounded to the earth electrode subsystem.
       (18) Verify that the shields of all telephone cables entering the facility are bonded to each other
and to the earth electrode subsystem through the steel entry plate.
       (19) Verify filters specified in the design are installed as shown on the engineering drawings.
       (20) Verify all power line filter cases are directly bonded to the equipment case or enclosure.
       (21) Verify filters are bonded to any subassembly enclosure used to maintain shield effectiveness.
       (22) Verify filters on power, control, and signal lines are installed in a manner that maintains the
integrity of the shield.
       (23) Verify that the power line filters are completely shielded with the filter case.
       (24) Verify that filters on power control and signal lines are placed as close as possible to the point
of penetration of the case.

                                                                                                                                       4-19


---

TM 5-690
  b. Testing. Measure the bonding resistance of each bond. One milliohm or less should be the

acceptable value of the resistance measured.
  c. Inspection and test records. Inspection and test records shall be maintained for the facility with the

periodic maintenance records and shall be used as the baseline for determining any corrective actions that
be necessary as a result of unacceptable conditions found during normal routine maintenance activities.
4-7. Baseline configuration documentation
Baseline documentation shall be maintained as part of the facility records for the life of the facility.
Changes to the baseline configuration shall be documented and approved by the responsible engineer.
Modifications and additions to the facility shall have the same requirements for maintaining an acceptable
EMI grounding configuration as the original installation.

4-20


---

                        TM 5-690

            CHAPTER 5

ELECTROMAGNETIC PULSE
      (EMP) PROTECTION

5-1. Purpose of EMP protection

The purpose of the electromagnetic pulse (EMP) protection system is to protect critical electrical systems
from the effect of intense electromagnetic (EM) effects caused as a result of an explosion. The frequency
spectrum may extend from below 1 Hz to above 300 MHz. The high-altitude EMP produced by an
exoatmospheric nuclear explosion is the form of EMP commonly of most interest because of the large
area covered by a single bomb. This high-intensity EMP can disrupt or damage critical electronic
facilities over an area as large as the continental United States, unless protective measures are taken in the
facilities. The development of such protective measures involves grounding, bonding, and shielding.

5-2. Types of EMP

An EMP event can be subdivided into three time-based periods, each of which has distinct characteristics.

  a. Early time EMP. During the early time portion of the EMP the amplitude, duration, and polarization
of the wave depend on the positions of the burst and the observer, relative to the Earth’s magnetic field
lines. Peak electric field strengths of over 50 kV/m with risetimes of a few nanoseconds and decay times
of less than 1 µs are typical.

  b. Late time EMP. During the late time portion of the EMP, currents are induced in the ground by the
effects of the expanding and rising fireball constituents. These effects are called the
magnetohydrodynamic EMP. As a result the currents produced induce image currents in the ground over
a period of 10 to 100 seconds. Although the field strengths produced at the surface by the
magnetohydrodynamic EMP are small (tens of volts per kilometer), they occur over long times. Thus, the
magnetohydrodynamic EMP is a consideration for long power and communications lines and, because of
its duration, for the energy it can deliver to protective devices.

  c. Intermediate time EMP. Between the early-time EMP and the magnetohydrodynamic EMP,
transitory phenomena produce what is called intermediate-time EMP. This EMP lasts from about 1 µs to
about 0.1 s. The intermediate-time EMP observed at the Earth’s surface has a peak electric field strength
of a few hundred volts per meter and is predominantly vertically polarized.

  d. Surface burst EMP. When a nuclear weapon is detonated at or near the surface of the Earth, neutrons
and gamma rays are ejected radially outward from the burst center. The surface-burst EMP is a more
localized source than the EMP and the event may cause large currents to be induced on long conductors,
such as power lines and communication cables. These currents may be propagated along the conductors
for great distances from their source. Therefore, this source-region EMP may be important to systems far
outside the source region if they are connected to the source region through wires, cables, or other
conductors.

  e. High altitude EMP. The high-altitude EMP is the most important form of EMP for communication
facilities because of its large area of coverage. However, in addition to the EMP and the surface-burst
EMP, a few other electrical effects could occur. System-generated EMP is produced when the high-

                                                                                                                                         5-1


---

TM 5-690

energy particles (mostly gamma- and X-ray photons) produced by the bomb interact directly with the
system structure. These interactions knock electrons out of the structure, which causes current on the
structure and potential gradients between the structure and the removed electrons. The structure of
interest may be system wiring or cable shielding; the current and potential differences are then on system
circuits.

5-3. Effects of EMP on facility systems

EMP interaction with systems may be separated into long-line effects and local effects. Long-line effects
are the currents and voltages induced on long power lines, communication cable links, or even other
conductors, such as pipelines. Some of these EMP effects may be induced far away and guided to the
facility along the conductor. Local effects are the currents and voltages induced directly on the facility
shield, building structure, wiring, equipment cabinets, etc. These local effects are very difficult to
evaluate analytically because of the complexity of the facility structure, the lack of information on the
broadband electrical properties of many of the structural materials, and the extremely large number of
interaction paths, facility states, and other complicating factors. On the other hand, the local interactions
can be evaluated experimentally with simulated EMP fields that envelop the facility.

  a. EMP induced currents. The currents induced on long straight overhead lines parallel to the Earth’s
surface by EMP-like events have been analyzed thoroughly. If the line is over a perfectly conducting
ground plane, the current has a waveform similar to the EMP early-time waveform, except for a slightly
longer risetime for lines more than a few feet high. For imperfectly conducting ground, such as soil, the
imperfect reflection of the wave from the ground allows the line to be driven more strongly and for a
longer time than if the ground were a good conductor.

  b. Effects on long buried lines. In long buried lines imperfectly conducting soil does not completely
reflect the incident field; some of the incident wave is transmitted into the soil. This field in the soil can
induce current in underground cables, pipes, and other conductors. However, because the velocity of
propagation of a wave is much less in soil than in air, the bow-wave effect is almost negligible on buried
conductors. Furthermore, the attenuation on buried conductors is greater than on overhead lines because
of the proximity of the soil to the buried conductor.

  c. Effects on conductors in contact with the soil. For conductors in contact with the soil (i. e., buried
bare conductor), the current at any observation point is determined primarily by coupling within one skin-
depth of the observation point. Current induced at points farther away is so strongly attenuated by the soil
that it adds little to the total current at the observation point.

  d. Effects on vertical structures. The EMP interacts with vertical structures, such as radio towers,
waveguides, and cables to overhead antennas, and downleads from power and communication lines in
much the same manner as it interacts with horizontal lines, except that it is the vertical component of the
electric field that drives the vertical structures.

  e. Effects on closed shields. The EMP fields incident on a closed shield induces surface currents and
charge displacements on the outer surfaces of the shield. If the shield is continuous metal (i. e., it has no
opening or discontinuities in its surface) and about 1 mm thick, voltage is induced in circuits inside the
shield by these surface currents.

  f. Effects on insulated penetrating conductors. Conductors, such as power and signal wires, that pass
through the shield may allow very large currents and voltages to be delivered to internal circuits. The
current on the wire just inside the shield is about equal to the current just outside the shield; the wire is a
hole in the shield or, in other words, a 0 decibel (dB) compromise of the shield. A major concern for

5-2


---

                                                                                                                                TM 5-690

EMP interaction is the penetrating conductor that can guide EMP-induced waves through shield walls.
The shield is effective in excluding the incident EM waves, but it has little effect on the waves guided
through it on insulated penetrating conductors.

  g. Effects on apertures in shield surfaces. Apertures in the shield surface allow the external EMP-
induced fields to penetrate through the shield and interact with internal wiring or other conductors. The
external electric field associated with the surface charge density can induce charge on internal cables.
The external magnetic, field which has the same magnitude as the surface current density can penetrate
through the aperture to link internal circuits.

  h. Transient radiation effects on electronics (TREE). Another important electrical effect is known as
transient radiation effects on electronics (TREE). The radiation emitted by the nuclear explosion can
interact with components of electronic circuits to produce ionization or atomic displacements in the
semiconductor and insulating materials. The effects range from momentary changes in conductivity to
permanent changes in crystal lattices. Semi-permanent effects, such as trapped charges in insulating
materials, may also occur. TREE may upset memories, produce spurious circuit responses (logic errors),
drive circuits into abnormal states, or cause permanent damage. As with most other EMP forms, damage
caused by TREE can also occur through secondary effects. Self-inflicted damage may be triggered by
abnormal conductivity in a junction that allows stored energy to be released. In addition, one circuit may
be caused to instruct another circuit or another part of the system to perform some forbidden act that
destroys the circuit or even the system.

  i. Effects on large networks. Protecting large networks from the EMP usually involves conservative
protection of individual parts of the network in the hope that network hardness will follow from
component hardness.

5-4. Grounding protection against EMP

Some form of grounding is required in any electrical or electronic system for protecting personnel from
electrical shock, controlling interference, proper shunting of transient currents around sensitive
electronics, and other reasons. (Grounding does not directly provide protection against EMP, but must be
done properly to prevent creation of more serious EMP vulnerabilities.) Ideally, grounding would keep
all system components at a common potential. In practice, because of possible inductive loops, capacitive
coupling, line and bonding impedances, antenna ringing effects, and other phenomena, large potentials
may exist on grounding circuits. The choice of grounding concept is therefore important in the EMP
protection philosophy.

  a. EMP grounding protection considerations. There are important considerations in the EMP
grounding protection that affect the value that can be placed on EMP protection. The EMP protection
adds cost to the facility, and the value received for the added cost is confidence that the facility will
survive EMP. Since EMP would not ordinarily occur during peacetime, degradation of the protection is
not evident from peacetime operation of the facility. Protecting communication facilities against the EMP
typically consists of developing a closed EMP barrier about the facility. The barrier consists of a shield to
exclude the incident space waves and various barrier elements on the essential penetrating conductors and
in the apertures required for personnel and equipment.

  b. EMP barrier. The EMP barrier is usually a facility-level shield fabricated from welded sheet steel.
The thickness is usually selected for ease of fabrication, but in areas where exceptional mechanical abuse
is likely, mechanical strength, as well as workability, may be a consideration. Shield assembly is
typically accomplished by continuous welding, brazing, hard soldering, or other fused-metal process to
minimize the number of discontinuities in the shield (a weld or other fused-metal pint is considered

                                                                                                                                         5-3


---

TM 5-690

continuous metal). This shield should be bonded to the earth electrode system in a number of places,
typically in a grid configuration with a cable equal in size to the largest earth electrode grounding
conductor. This bond should be a continuous weld to preclude any potential high resistance bonds that
may develop with aging of the facility.

  c. Coupling of EM energy to penetrating conductors. Many factors affect the coupling of EM energy
to penetrating conductors. The EMP waveform characteristics, such as magnitude, rate of rise, duration,
and frequency, are each important. Further, the observer’s position with respect to the burst is a factor.
Because the interaction between fields and conductors is a vector process, the direction of arrival and
polarization is also important. Conductor characteristics also affect EMP coupling. These include
conductor geometry (length, path, terminations, distance above or below the earth’s surface), physical and
electrical properties that determine series impedance per unit length (including diameter, resistivity, and
configuration), and the presence and effectiveness of shielding. For overhead or buried conductors, the
electrical properties of soil affect coupling. Many elements of a facility can act as efficient collectors and
provide propagation paths for EMP energy. EMP can couple to structures such as power and telephone
lines, antenna towers, buried conduits, and the facility grounding system. Actual antennas, non-electrical
penetrators such as waterpipes, and any other conductive penetration can couple EMP energy into a
structure. In addition, if the structure is not shielded or is not shielded well enough, EMP can couple to
the cables between equipment inside. Penetrating conductors (plumbing, waveguides, grounding cables,
electrical conduit, and cable shields) must be grounded by bonding to the shield wall at their entry point.
The preferred method of bonding is by peripherally welding them to the wall. However, it is permissible
to use clamps, collets, etc., that peripherally bond the penetrating conductor to the shield with little or no
discontinuity.

  d. Treatment of penetrating conductors. Signal and power wires that need not penetrate the shield
should not penetrate the shield. Wires that must penetrate the shield must be treated with a barrier
element, such as a filter or surge arrester, that closes the barrier above a voltage threshold or outside the
passband required for signal or power transmission.

  e. Openings in EMP barriers. Unnecessary openings or discontinuities in the shield are not typically
allowed. Those openings necessary for personnel and equipment loading and for ventilation must be
properly grounded to ensure continuity and a continuous path to the ground system.

5-5. Typical components and installation details

Typical components and installation details for EMP protection systems are described below.

  a. Shielding. An EMP-induced event can cause a magnetic or electric field to be induced in an
electrical circuit that can cause an error in the response of the circuit. As in electromagnetic interference
(EMI) protection described in chapter 4, an effective means for the reduction of this interfering coupling
is the use of shields around the circuits and around interconnecting lines penetrating the EMP barrier and
internally within the barrier.

       (1) To determine the shielding required at a facility, the equipment susceptible to such events
should be surveyed. The sensitive equipment will typically be located within the shielded barrier
provided for EMP protection. Shielding should be provided for the cabling servicing this equipment by
installing it in rigid metal conduit that is bonded to the entry plate of the shield. Instrumentation and
coaxial cable should be of shielded construction with connectors providing additional protection as the
cable passes through the entry plate into the protected area.

5-4


---

                                                                                                                                TM 5-690

       (2) Insure that shield continuity is maintained at points of entry of signal cables, power
conductors, utility lines, and ground conductors.

       (3) Make sure that windows, doors, and ventilation ports are shielded along with the walls. Use
well-bonded screen wire for windows, use metal doors, and apply honeycomb ducts or appropriate
screening over ventilation ports.

       (4) Equip all power lines supplying shielded areas with power line filters.

       (5) Securely ground all metal shields.

  b. Bonding. The bonding requirements for EMP protection necessary to ensure a mechanically strong,
low impedance interconnection between metal objects and to prevent the path thus established from
subsequent deterioration through corrosion or mechanical looseness are the same as those for EMI
protection as established in chapter 4.

  c. Entry plates. All metallic penetrations entering the protected area should enter at a common
location, and all shielded cables, conduits, and pipes should be bonded to an entry plate. This plate
should be designed and installed as described for EMI protection in chapter 4.

  d. Filters. The majority of the interfering signals will be conductively coupled into the susceptible
circuit. The proper application of filters to both the signal and power lines to reduce this coupling is the
same for EMP protection as it is for EMI protection discussed in chapter 4.

5-6. Interfaces with other grounding and bonding subsystems

The grounding required for EMP protection is a part of the total facility grounding network. The ultimate
path to ground is the earth electrode subsystem. Protection against EMP is imperative for sensitive
electronic equipment to ensure a workable and secure system. Grounding for this protection interfaces
with each of the major subsystems. Since the influence of EMP-induced interference is similar to that
seen by lightning discharges, the lightning subsystem and the earth electrode subsystem are the main
interfaces with the EMP protection system. It is, therefore, imperative that these systems be properly
designed and constructed to ensure the most direct and lowest possible impedance to the earth ground.

5-7. Inspections and testing

Thorough inspection and testing programs are imperative to assess the effectiveness of the EMP
protection measures utilized.

  a. Inspections. Inspect the facility for the following.

       (1) Verify that the EMP survey at the facility has been properly performed and documented.

       (2) Verify that shielding provided is sufficient to meet system needs (both known and predicted).

       (3) Verify that shield continuity is maintained at points of entry of signal cables, power
conductors, utility lines, and ground conductors.

       (4) Verify that windows, doors, and ventilation ports are shielded along with the walls.

       (5) Verify that all power lines supplying the shielded areas are protected with power line filters.

       (6) Verify that all electrical conduit is steel inside the shielded areas.

                                                                                                                                         5-5


---

TM 5-690

       (7) Verify that any wiring ducts are totally enclosed.

       (8) Verify that all metal shields are grounded.

       (9) Verify that all seams and joints are well bonded by welding, solder, or knitted wire gaskets.

       (10) Verify that all metallic utility lines are bonded to the shield at the point of entrance.

       (11) Verify that all openings required for visual access are covered with wire screen or conductive
glass and that the screen or glass is carefully bonded to the enclosure around the perimeter of the opening.

       (12) Verify that all doors are metal with solid, uniform contact around the edges.

       (13) Verify that all bonds are of the type that will provide the least resistance possible for the
application, preferably direct bonding with no intervening conductor.

       (14) Verify that the bonding surfaces are cleaned of all such solid materials and moisture.

       (15) After bonding, verify that the completed bond is sealed against the entrance of moisture into
the mating region.

       (16) Verify that all metallic penetrations and shielded cables through the facility shield are bonded
to the entry plate.

       (17) Verify that each RF coaxial cable is bonded to the entry plate with a metal bulkhead
connector, which is bonded to the building entry plate and grounded to the earth electrode subsystem.

       (18) Verify that the shields of all telephone cables entering the shielded facility must be bonded to
each other and to the earth electrode subsystem through the steel entry plate.

       (19) Verify that filters specified in the design are installed as shown on the engineering drawings.

       (20) Verify that all power line filter cases are directly bonded to the equipment case or enclosure.

       (21) Verify that filters are bonded to any subassembly enclosure used to maintain shield
effectiveness.

       (22) Verify that filters on power, control, and signal lines are installed in a manner that maintains
the integrity of the shield.

       (23) Verify that the power line filters are completely shielded with the filter case.

       (24) Verify that filters on power control and signal lines are placed as close as possible to the point
of penetration of the case.

  b. Testing. Measure the bonding resistance of each bond. One milliohm or less should be the
acceptable value of the resistance measured.

  c. Inspection and test records. Inspection and test records shall be maintained for the facility with the
periodic maintenance records and shall be used as the baseline for determining any corrective actions that
be necessary as a result of unacceptable conditions found during normal routine maintenance activities.

5-6


---

                                                                                                                                TM 5-690
5-8. Baseline configuration documentation
Baseline documentation shall be maintained as part of the facility records for the life of the facility.
Changes to the baseline configuration shall be documented and approved by the responsible engineer.
Modifications and additions to the facility shall have the same requirements for maintaining an acceptable
EMP grounding configuration as the original design configuration.

                                                                                                                                         5-7


---

                                                                                                                                TM 5-690

                                          CHAPTER 6

               EVALUATING, MODIFYING, AND MAINTAINING
                             EXISTING C4ISR FACILITIES

6-1. Purpose of evaluating, modifying and maintaining existing C4ISR facilities

The purpose of this chapter is to provide guidance, steps, and procedures for verifying, upgrading, and
evaluating the grounding, bonding, and shielding networks in an existing facility. The specific items to
consider and inspection procedures used during the evaluation of the facility will be addressed. The
procedures are directed toward verifying that the grounding, bonding, and shielding networks have not
been compromised, that the basic resistance goals continue to be met, and that corrosion is effectively
controlled.

6-2. Facility survey

For an existing facility with electrical wiring already installed, with an earth electrode subsystem
(frequently only a connection to the water system) present, and with electrical/electronic equipment in
place, the installation of the grounding, bonding, and shielding networks described in previous chapters
may not be straightforward. In recognition that major retrofitting, with the attendant costs and operational
disruption, may be required in order for the facility to conform to the recommended practices and
procedures, it is necessary that a comprehensive grounding, bonding, shielding, and lightning protection
survey be made of the entire facility. The findings of the survey should be documented on a survey form.
Survey forms are DA Forms 7452-4-R through 7452-9-R as shown in figures 6-1 through 6-6.
Reproducible forms can be found at the end of the manual. The results should be critically analyzed to
determine the extent to which the existing system fails to conform to the recommendations set forth in the
previous chapters. In areas of non-conformance, the performance history of equipment and subsystems in
the facility should be examined to establish, if possible, any relationships which exist between noted
deficiencies and operational problems. Then the decision to retrofit and the extent of any such retrofitting
can be made based on the relative need to improve and on the overall cost of the retrofit.

  a. Baseline configuration. Before upgrading, altering, or expanding the grounding, bonding, or the
shielding of a facility, it is necessary to define and analyze the existing system. This definition and
analysis should include drawings depicting the ground system layout of the facility; determination of the
condition, integrity, and effectiveness of the existing grounding, bonding, and shielding systems;
documentation of existing conditions; and a comparison of the findings with the facility requirements to
determine if improvements are needed.

     (1) Engineering drawings for the facility should include all structures, the configuration of the earth
electrode subsystem, location of utility piping and cable systems, general landscape features, and building
profiles. Drawings should also show methods of connecting to the earth electrode subsystem, methods
used for structural steel assembly, locations and methods for the installation of reinforcing steel as well as
metal screens or sheets. Electrical drawings should show wire sizes, breaker sizes, as well as cable type,
routing and enclosures utilized, the lightning protection subsystem, with heights and locations of air
terminals, down conductor sizes and routing, fasteners, guards, and connections to the earth electrode
subsystem.

                                                                                                                                         6-1


---

TM 5-690

       (2) Compare the drawings with the existing configuration. If the drawings do not match the
configuration, review available maintenance and change records to confirm the changes made where
acceptable. Update the drawings as needed to reflect additions or modifications that have been made but
not entered on the drawings. If new drawings must be prepared, be sure they include all elements of the
structure. It is very important that an accurate representation of the existing configuration be used in
determining what changes are required to the grounding system.

                                              E AR T H E L E C T R OD E S U B S Y S T E M C H E CK L I S T F OR E X I S T I N G F AC I L I T I E S
                                                                        For use o f th is f orm, see T M 5 -6 9 0 ; t he p ropo nent age ncy is C OE.

1. FA CILITY                                                                                                           2 . D AT E (YYYYM M DD)         2 0 0 20 2 2 8
F o rt Ta n k                                                                                                          4 . IN S P ECT OR
3 . LOCA T ION

B u ildin g 1 9 2 9                                                                                                    A n d re A m p ere

5 . S KET CH T H E L AYO UT OF T HE EA R T H EL ECT R OD E S UB S YST EM (Or attac h a n u p-t o-d ate en gin eer ing dr aw i ng)

                     S e e a t t a c h e d d r a w i n g 0 0 1 -5 1 -7 , 3 0 A p r il 2 0 0 1

6 . S OIL C ON DIT ION S (T y pe)                                                                                                  7 . EART H ELE CT R ODE SU B SY S T E M R ES I S T A N CE M E ASU R EM EN T
                                                                                                                                                                              1 .5 o h m s
LOAM OR H UM US                               CLAY                            S AN D           GRA VEL

8 . LAST R ESI ST A N CE M E AS U REM EN T                                                            9 . M ON T HS S IN CE LAS T R E S IST AN CE M EA S UR E M EN T
                                                        1 .4 o h m s                                                                                                   14

COM P ON EN T ID EN T I FICA T ION

1 0 . GRO UN D RODS                           1 0 b. S IZ E (Diam eter)                               1 0 c. LEN GT H                                      1 0 d. P HYSIC AL CON DIT ION
10a. TYPE                                                                                                                                                   g o o d : n o co rrosio n , n o da m a g e

                          co p p er                                       1"                                                       2 0 ft                  1 1 d. P HYSIC AL CON DIT ION
                                              11b. SIZ E                                                                                                                 g o o d : n o c o rr o s i o n
1 1 . GR OUN D C ON D UCT OR S                                                                        1 1c. M ATE RIAL
11a. TYPE                                                                                                                     co p p er                    1 2 d. P HYSIC AL CON DIT ION
                                                                                                                                                                         g o o d : n o c o rr o s i o n
                  stra n d e d /b a re                                     1 /0
                                                                                                                                                   1 .5 o h m s
1 2 . IN T ERC ON N E CT IN G CO N DUC T ORS  12b. SIZ E                                              1 2c. M ATE RIAL
12a. TYPE                                                                                                                     co p p er            1 .0 o h m s

                       stra m d ed                                         1 /0

13. R ISERS                                                                                           1 3b. M EAS URE D R ESI ST A N CE
1 3 a. P HYSIC AL CON DIT ION

                                              good

1 3 . GROU N D W ELLS                                                                                 1 3b. M EAS URE D R ESI ST A N CE
1 3 a. P HYSIC AL CON DIT ION

                                                            good
1 4 . WEA T HER CON DIT I ON S (At tim e of ins pect ion)

                     WET                                              DRY                      SN OW                                       R AIN                           M IST

  1 5 . M E AS U RED T E M P E RAT UR E                                                               1 6 . DAYS SIN C E LAS T P RE CIP IT AT ION
D A F OR M 74 52-4-R , F E B 2002
                                              80 F                                                                                                 10 days

                                                                                                                                                                                  USAP A V1 .0 0

                                              (2) Figure 6-1. Sample of completed DA Form 7452-4-R

6-2


---

                                                                                                                                                            TM 5-690

                               GROUNDING AND BONDINGCONNECTION CHECKLIST FOR EXISTING FACILITIES

                                                          For use of this form, see TM 5-690; the proponent agency is COE.

1. FACILITY                                                                         2. DATE (YYYYMMDD)                                      2 0 0 20 3 2 8
                                                                                    4. INSPECTOR
Fort Tank
                                                                                    Lou Swire
3. LOCATION
                                                    GOOD              POOR          UNACCEPTABLE
B u ild in g 3 1 6

5. GENERAL CONDITION

                  EXCELLENT

6. SPECIFIC DEFICIENCIES

LOCATION                                                                            DEFICIENCIES

1 . S ervice en tra nce racew a y                   Th e m e ta llic ra c e w ay is n o t bo n d e d
2 . S e rv ice e n tra n c e pa n e l (2 0 0 0 A )  B o n d in g ju m p e r is u n d e rsize d (# 2 A W G C u )
3 . D istrib u tio n p a ne l D -1                  N eu tra l b us is b o n d ed to g ro u nd b u s
4. Racew ay between panel D 4&D 5                   C o n n e c to r (fittin g ) is n o n -m e ta llic
5 . Pa n el D P-7                                   N o g ro u nd b u s. N e u tra l b us is use d for b o th n e u tra l a n d g ro u nd c o n du c to rs

7. RESISTANCE (Use double balanced dc bridge or approvedbondresistance meter and identify those bonds whose resistance is greater than1.0 milli-ohm)

                        LOCATION                                                                                              DEFICIENCIES

1 . R a c e w ay b e tw e e n p a n e ls D -3       H ig h re sista n c e is d ue to n o n -m e ta llic fittin g
a n d D -7                                          M e ta llic ra c e wa y is n o t c o n tin u o u s
2 . B etw een p a n els D -7 & D -9

8. INEFFECTIVE BONDINGJUMPERS

                        LOCATION                            MATERIAL        LENGTH      SIZE                                                                      DEFICIENCIES

1 . S e rv ice e n tra n c e pa n e l (2 0 0 0 A )  copper                   10"    #2 AWG                                                  u n d e rsize d
2 . D istrib u tio n p a n e l D -6 (3 0 0 A )      copper                    7"    #6 AWG                                                  u n d e rsize d
3 . D istrib u tio n p a n e l D -9 (1 5 0 A )      copper                   24"    #2 AWG                                                  too long

DA FORM 7452-5-R, FEB 2002                                                                                                                                                                 USAPA V1.00

                                         Figure 6-2. Sample of completed DA Form 7452-5-R                                                                                       6-3


---

           TM 5-690

                                 LIGHTNING PROTECTION GROUNDING SUBSYSTEM CHECKLIST FOR EXISTING FACILITIES

                                                                    For use of this form, see TM 5-690; the proponent agency is COE.

1. FACILITY                                                                                             2. DATE (YYYYMMDD)      2 0 0 20 3 3 0
                                                                                                        4. INSPECTOR
Fort Tank

3. LOCATION

B u ild in g 3 5 8                                                                                      Joe Sparks

5. SKETCHTHELAYOUT OF THE ACTUAL LIGHTNING PROTECTION SUBSYSTEM (Or attach an up-to-date engineeringdrawingif it exists)

                    S e e a ttac h e d d ra w in g 0 01 -5 0 -0 9 , 12 D e ce m b e r 2 0 0 1

6. ALL LIGHTNING PROTECTION EQUIPMENT UL LABELED                                          7. UL MASTER LABEL ISSUEDAND PROPERLY ATTACHED TO THE BUILDING

                YES                      NO                                                                      YES                     NO

8. AIR TERMINALS                                                  8b. MATERIAL                                      8c. SIZE (Diameter)

8a. HEIGHT                                                                              copper                                                       5 /8 "

                               2 ft

8d. PROPER BASES/FITTINGS                                         8e. PROPERLY INSTALLED                            8f. LOCATED ANDSPACED AS SPECIFIED

           YES                       NO                                    YES                      NO                          YES                          NO

8g. DOES THE HEIGHT OF AIR TERMINALS PROVIDEPROPER CONEOF PROTECTION                                             8h. PHYSICAL CONDITION

           YES                       NO                                                                                                       w e ll m a in ta in e d

9. ROOF CONDUCTORS

9a. TYPE                                                          9b. SIZE                                          9c. MATERIAL

                         stra n d e d                                                         2 /0                                                   copper

9d. BEND RADIUS ACCEPTABLE                                        9e. SECURELY FASTENED                             9f. PROPER FITTINGS

           YES                       NO                                    YES                      NO                          YES                          NO

9g. PROPERLYBONDED TO AIR TERMINALS AND OTHER METAL OBJECTS ON ROOF

           YES                       NO

9h. PROPERLY INTERCONNECTED TO OTHER CROSS ROOF CONDUCTORS                                              9i. PHYSICAL CONDITION

           YES                       NO                                                                                         good

10. DOWN CONDUCTORS

10a. TYPE                                10b. SIZE                                   10c. MATERIAL                              10d. BEND RADIUS ACCEPTABLE            NO
                                                                                                                                                   YES
               stra n d e d                                 2 /0                                         copper                                                        NO
                                                                                                                                                                       NO
10e. SECURELY ANCHORED                                            10f. PROPER FITTINGS                           10g. LOCATED ANDSPACED AS SPECIFIED
                                                                                                                                                                            USAPA V1.00
           YES                       NO                                         YES                 NO                          YES                          NO

10h. PROPERLYBONDED TO ROOF CONDUCTORS/AIR TERMINALS AND GROUNDINGELECTRODES

                            YES                 NO
10i. PHYSICAL CONDITION
                                 good

11. GUARDS

11a. TYPE                                           11b. SOLIDLY ANCHORED                                        10c. PHYSICAL CONDITION

                    PVC                                           YES                NO                                                        good

12. GROUNDINGELECTRODES

12a. TYPE                                    12b. SIZE                               12c. LENGTH (Each)                         12d. FORMCOUNTERPOISE LOOP
                                                                                                                                                   YES
              copper clad                               5 /8 "                                            20 ft

12e. DISTANCEBELOW GRADELEVEL                           12f. DISTANCE FROMOUTER WALL                                            12g. PROPERLY INSTALLED
                                                                                                                                                   YES
                            2 ft                                                            6 ft

12h. PROPERLY CONNECTEDTO OTHER GROUNDING SYSTEMS OF THE BUILDING

                    YES                  NO

12i. PROPERLY CONNECTEDTO DOWN CONDUCTORS                                                      12j. GROUNDRESISTANCE MEASUREMENT

                    YES                  NO                                                                                              10 ohm s

DA FORM 7452-6-R, FEB 2002

                                          Figure 6-3. Sample of completed DA Form 7452-6-R
           6-4


---

                                                                                                                                            TM 5-690

                             GROUND FAULT PROTECTION SUBSYSTEM CHECKLIST FOR EXISTING FACILITIES

                                                        For useof this form, see TM 5-690;theproponent agency is COE.

1. FACILITY                                                                     2. DATE (YYYYMMDD)                      2 0 0 20 3 0 1
                                                                                4. INSPECTOR
Fort Tank

3. LOCATION

Building 1929                                                                   Max D rain

5. CHECKTHEGROUNDED(Neutral)ANDGROUNDINGCIRCUITS FORPROPER INSTALLATION,CONNECTION,AND BONDINGFROM THESERVICE ENTRANCE PANELSTOTHE DISTRIBUTION
PANELS. VERIFYTHAT THE GROUNDED AND GROUNDINGCONDUCTORS ARELOCATED IN THESAME CONDUIT AS THE LINE (Hot) CONDUCTORS. RECORDTHE DATAAND ALL
DEFICIENCIES.

                LOCATION       MAIN         GROUNDED                        GROUNDING           PROPER                  PROPER              LOCATED IN SAME
                             BREAKER          CIRCUIT                          CIRCUIT      INSTALLATION                BONDING                  CONDUIT
M a in p anel M P-1          RATING
                                      SIZE MATERIAL                    SIZE MATERIAL        YES           NO            YES             NO         YES   NO
                             1000A
                                      (2 ) 5 0 0 co p p er             4 /0 cop per

D istributio n pa nel D P-1  225A     4/0 co pp er # 2 cop per

6. MEASURETHELINE-TO-NEUTRALVOLTAGES, LINE-TO-GROUND VOLTAGES,AND NEUTRAL-TO-GROUND VOLTAGES AT ALL PANELSAND DISCONNECTED SWITCHES

                             LINE-TO-NEUTRAL VOLTAGES                         LINE-TO-GROUND VOLTAGES                   NEUTRAL-TO-GROUND VOLTAGES
                                                                                                                                           V (N-G)
LOCATION                     V (A-N)  V (B-N)         V (C-N)          V (A-G)  V (B-G)          V (C-G)

M a in p anel M P-1          418V     480V            481V             480V     480V             481V                                       0.2 V

D istributio n pa nel D P-1  480V     480V            481V             479V     480V             481V                                       0.5 V

7. MEASURETHELINE (Hot) CURRENTS,NEUTRAL CURRENTS,AND GROUND CURRENTS

                                      LINE CURRENTS                                         NEUTRAL CURRENT                             NEUTRAL CURRENT
                                                                                                      I (N)                                       I (G)
LOCATION                     I (A)             I (B)                   I (C)
                                                                                                  150A                                        1 .5A
M a in p anel M P-1          650A              630A                    595A                        52A                                        2 .0A

D istributio n pa nel D P-1  110A              100A                    115A

8. RECORDALLNATIONAL ELECTRIC CODE (NEC) AND NATIONAL ELECTRIC SAFETYCODE (NESC)VIOLATIONS

                LOCATION                                                                                    VIOLATIONS

D istributio n pa nel D P-2  N eu tra l b us is b o n d ed to g ro u nd b u s
D istributio n pa nel D P-5  N o g ro u n d bu s. All gro u n d co n du cto rs a re co n nected to neu tral b u s

DA FORM 7452-7-R, FEB 2002                                                                                                                                    USAPA V1.00

                                      Figure 6-4. Sample of completed DA Form 7452-7-R                                                             6-5


---

TM 5-690

                                  SIGNAL GROUND REFERENCE SUBSYSTEM CHECKLIST FOR EXISTING FACILITIES

                                                            For useof this form, see TM 5-690;theproponent agency is COE.

1. FACILITY                                                                                  2. DATE (YYYYMMDD)  2 0 0 20 3 0 4
                                                                                             4. INSPECTOR
Fort Tank

3. LOCATION

Bu ild in g 3 5 8                                                                            Al Volta

5.SKETCHTHELAYOUTOF THE EXISTINGSIGNALGROUND REFERENCE SUBSYSTEMORATTACH AN UP-TO-DATEENGINEERINGDRAWING

             S ee a ttach ed d ra w in g 0 01 -5 0 -4 , 20 D ecem b er 2 0 0 1

6. VISUALLYINSPECT THEEXISTINGSIGNAL GROUND REFERENCESUBSYSTEM FOR SIGNS OF DETERIORATION, BURNING, CORROSION, OR DAMAGE. RECORD ALLDEFICIENCIES.

                   LOCATION                    GROUND COMPONENTS                                                 DEFICIENCIES

Tower antenna #3                  G round conductor                             c o rro sio n

Ba ttery set # 3 (Ro o m 1 2 )    G round bus                                   c o rro sio n

7. CHECKTHECONTINUITYOFTHEGROUNDINGCIRCUITS. CHECK ALL CONNECTORS, JOINTS, BONDS, ANDFITTINGSFOR PROPER INSTALLATION, CRACKS,AND TIGHTNESS. RECORD
ALL DEFICIENCIES.

                   LOCATION                                                                  DEFICIENCIES

C o m p u ter ro o m (Ro o m 2 )  Bo n d betw een th e server # 2 fram e a n d ra ised flo or fra me w a s b ro ken

Telep h o n e ro o m (Ro o m 3 )  Battery rack is not grounded

8. MEASURETHERESISTANCEBETWEEN CONNECTORS, JOINTS, BONDS, ANDFITTINGSUSINGDOUBLE BALANCED DC BRIDGE. RECORD ALLMEASUREMENTS.

                   LOCATION                                                     CONNECTIONS                                      RESISTANCE

C o m p u ter ro o m (Ro o m 2 )  Bo n d b etw een g ro un d p la te an d raised flo o r                                   0 .2 m illio h m s
DCO                               Bo n d b etw een gro u nd b us a nd p ho n e ra ck                                         .0 3 m illio h m s

9. MEASURETHEEARTH TOGROUNDRESISTANCE OF THESIGNAL GROUND REFERENCESUBSYSTEM USINGTHE FALL OF POTENTIAL METHOD. RECORDTHE MEASUREMENT.

             RESISTANCE           1 .5 o hm s

DA FORM 7452-8-R, FEB 2002                                                                                                                         USAPA V1.00

                               Figure 6-5. Sample of completed DA Form 7452-8-R
6-6


---

                                                                                                                                                 TM 5-690

1. FACILITY                         SHIELDING SUBSYSTEM CHECKLIST FOR EXISTING FACILITIES                                   2 0 0 20 2 2 7

Fort Tank                                       For useof this form, see TM 5-690;theproponent agency is COE.
                                                                                                        2. DATE (YYYYMMDD)
3. LOCATION
                                                                                                        4. INSPECTOR
Bu ild in g 3 5 8
                                                                                             Lou Scable

5. VISUALLYINSPECT THEEXISTINGSHIELD NETWORK FOR PROPERGROUNDINGAND SIGNS OF DAMAGE, CORROSION,AND LOOSENESS

                       LOCATION                                                                            DEFICIENCIES

S ervice en tra n ce p o in t       C o rro sion a t p o in t o f bo n d ing to th e sh ield

6. CHECKSHIELDINGON ALLDOORS,WINDOWS,VENTILATION PORTS,VISUAL ACCESS OPEININGS,ANDWALLS FOR PROPER INSTALLATION AND BONDING

                       LOCATION                                                       DEFICIENCIES

Ven tila tio n p o rt               N o b on d in g screen w ire a pp lied

7. CHECKALLUTILITY LINES, ELECTRICAL CONDUCTORS, AND DATACABLES FORPROPER BONDINGAND SHIELDING                                              YES            NO
 a. UTILITYLINES,ELECTRICAL CONDUCTORS, ANDDATACABLESARE PROPERLY BONDED TOTHESHIELD AT THE POINT OF ENTRANCE
 b. ALLELECTRICAL GROUNDED ANDGROUNDINGCONDUCTORSARE IN THE SAME CONDUIT ASPHASECONDUCTORS
 c. ALLELECTRICALFILTERS AND CONDUCTORS ARE PROPERLY ENCLOSED INSIDEMETAL(STEEL) CASES/CONDUITS

d. ALLMETALOBJECTS/CASES/CONDUITS AREPROPERLYBONDED TOGROUND

e. DATACABLES ARE PROPERLY BONDEDTOTHE SIGNAL GROUNDFEFERENCE SYSTEM

8. MEASURESTRAYCURRENTSON THE GROUND CIRCUITS

                          LOCATION                                   GROUND CIRCUITS                                         CURRENT MEASUREMENTS

S ervice en tra n ce                Electrica l gro u n d co n du cto r                                                     0 .5 a m ps
                                    D a ta ca b le shield                                                                   0 .1 a m ps

9.MEASURE THEBOND RESISTANCES                                          BOND CIRCUIT                                                 RESISTANCES
                          LOCATION
                                    D a ta ca b le to sh ield                                                               0 .1 o hm s
S ervice en tra n ce

DA FORM 7452-9-R, FEB 2002                                                                                                                                  USAPA V1.00

                                    Figure 6-6. Sample of completed form 7452-9-R                                                                6-7


---

TM 5-690

  b. Field inspections. After the drawings are obtained or prepared, conduct a comprehensive survey of
the grounding, bonding, shielding, and lightning protection practices throughout the facility. This survey
should cover all the major elements of the fault protection subsystem, signal reference subsystem,
bonding (both in current paths and between structural elements), lightning protection for the structure, and
shielding for both electromagnetic interference (EMI) [and electromagnetic pulse (EMP), if required] and
personnel protection.

     (1) Visual observations should be concisely documented and related to the engineering drawings for
the facility. Measurements performed and data collected should be accurately documented on the survey
form. The steps of the inspections are as follows.

         (a) Analyze the earth electrode subsystem and measure its resistance to earth (figure 6-1).

         (b) Inspect a representative number (5 to 10 percent) of the bonds throughout the facility (figure
6-2).

         (c) Inspect and evaluate the lightning protection subsystem (figure 6-3).

         (d) Inspect fault protection subsystem; make spot checks of stray current levels (figure 6-4).

         (e) Wisp out and describe the signal grounding networks (or systems) present in the facility
(figure 6-5).

         (f) Perform a ground system shielding survey (figure 6-6).

         (g) Evaluate (if applicable) the electromagnetic (EM) shielding of (or in) the facility (figure 6-6).

         (h) Before leaving the facility, review the survey forms for accuracy and completeness.

     (2) A comprehensive survey of the earth electrode subsystem should include the following items.

         (a) Determine the configuration of the earth electrode subsystem for the facility. Sketch the
conductor layout on the survey form or on an attached sheet. Engineering drawings may be attached in
lieu of the sketch. Corrections or additions should be made to the drawings as appropriate (figure 6-1 #5).
Identify the type of earth electrode subsystem present, i.e., rods, ring ground, grid, grid with rods, plates,
horizontal radials, utility pipes, etc. (figure 6-1 #10 through #13). Note all interconnections between the
earth electrode subsystem and other conductors such as water pipes, buried tanks, structural columns,
underground guard cables, antenna counterpoises, and power grounds (figure 6-2).

         (b) To the extent that information is available, determine the composition (copper, copperclad
steel, steel, solid, hollow, etc.), diameter, and length of ground rods, as well as the size, depth, and
composition of the ring ground. If horizontal rods or ribbons are used, record the dimensions; likewise,
record the physical dimensions and composition of plates, cylinders, or other types of electrodes (figure
6-1 #10 through #13).

         (c) Examine the conductor or conductors used to ground the power system neutral in the first
service disconnecting means (i.e., main power switch or breaker for the facility), the power transformers,
or other elements of the power distribution system to the earth electrode subsystem. Record the size or
sizes on the survey form. Using a clamp-on ammeter, measure the ac current in each of these conductors
and record the value on the survey form (figure 6-4).

6-8


---

                                                                                                                                TM 5-690

         (d) Inspect those bonds associated with the earth electrode subsystem carefully for evidence of
looseness, corrosion, electrolysis, and lightning or mechanical damage (figure 6-2).

         (e) Make a general classification of the type of soil at the site. If the site possesses unique
properties (i.e., located on a mountaintop, in a swamp, on a coral reef), appropriately indicate the unusual
features (figure 6-1). Also generally describe the weather conditions existing at the time of the survey,
particularly if the earth resistance measurement described in the next step is performed. If known,
indicate how recently rainfall totaling at least 0.01 inch has occurred. State if any soil treatment or
enhancement procedures have been utilized (figure 6-1).

          (f) Measure the resistance to earth of the earth electrode subsystem using the fall-of-potential
method (figure 6-1).

      (3) A comprehensive survey of the lightning protection subsystem should include the following
items (figure 6-3).

          (a) Make a sketch of the lightning protection network for the facility or compare the system as
installed with the engineering drawings. Indicate the location of air terminals (lightning rods), the routing
of roof and down conductors, connections to the earth electrode subsystem, and the location and size of
bonding jumpers.

          (b) Document the Underwriters Laboratories (UL) listing of the system if available.

          (c) Record the height (above the roof) and material of the air terminals. Inspect for evidence of
burning, pitting, or melting of a degree that seriously weakens (physically) the air terminals. Identify
other metallic extensions (railings, antenna masts, etc.) extending above the air terminals or outside the
150-foot radius of protection.

          (d) Record the cable sizes and materials used for roof and down conductors. Examine both
types of conductors for unnecessary length, sharp or unnecessary turns [radii less than 20 cm (8 inches)],
corrosion, and mechanical damage.

          (e) Check fasteners and mounting hardware for secure mounting, looseness, corrosion, and
mechanical damage. Verify that fasteners for connecting dissimilar metals (e.g., copper to aluminum) are
of UL approved bimetallic construction.

          (f) Ensure that interconnections between the lightning protection subsystem and the earth
electrode subsystem, structural metals, utility lines, etc., are recorded.

          (g) Inspect the guards that provide mechanical protection for down conductors. Note any down
conductors in areas with public access or subject to contact by equipment or machinery. All such down
conductors must be guarded with metallic or non-metallic (preferably) guards to a height of at least 2.7
meters (9 feet) from grade or floor level. Such guards must be securely fastened in place and not show
appreciable physical degradation. Metal guards to include electrical metallic tubing (EMT) and conduit
must be bonded to the down conductor at the top and bottom.

     (4) A comprehensive survey of the fault protection subsystem should include the following items
(figure 6-4).

                 (a) Inspect the fault protection subsystem for conformance with the requirements of
          MIL-STD-188-124B and the National Electrical Code (NEC). Specifically, all equipment

                                                                                                                                         6-9


---

TM 5-690

          supplied with electric power and other electrical apparatus falling within the jurisdiction of the
          standard or the NEC, must be grounded in accordance with the standard or the code. Inspect the
          facility and the equipment associated with the facility to see that grounding (green) conductors
          are present and record the sizes of the conductors. See that all connections are tight and well
          made.

         (b) Verify that color continuity is maintained from the breaker panels to the equipment. In
particular, be alert for white wire/green wire reversals.

         (c) Verify that the neutral white wire (or other designated conductor) is not grounded at
intermediate distribution panels, at switch boxes, or inside equipment. The grounded conductor (neutral
white wire) shall be bonded to the earth electrode subsystem only at the first service disconnecting means.
Facilities which can be temporarily removed from service should be de-energized and the main power
switch locked or otherwise secured open. With electrical power removed, disconnect the neutral from
ground at the first service disconnecting means and check for continuity between the neutral and the
grounding conductor. A low resistance reading (<10 ohms) indicates that the neutral is connected to
ground somewhere other than at the first service disconnect. This ground connection must be located and
removed. Under normal operation, a one megohm resistance should easily be attained.

         (d) Measure for stray currents using a clamp-on ammeter in the safety ground network at selected
points throughout the facility. Choose a sufficient number of points to give an indication of the relative
stray current level in the facility. In facilities containing electronic equipment, record and take action to
correct all levels greater than 0.1 ampere.

      (5) A comprehensive survey of the signal reference subsystem should include the following items
(figure 6-5).

        (a) Prepare a general description of the methods, techniques, and practices of signal grounding
in the facility. Determine if an identifiable, dedicated signal grounding network is present. Note the
equipment served by the network. Include the description of this network and record the location and size
of wires or buses used as signal conductors. Also determine the existence of an equipotential plane.

         (b) Using a double balanced bridge or a four-terminal milliohmmeter, measure the resistance
between selected points of the signal ground network. Where lower frequency ground networks exist,
measure the resistance between those points on the network where equipment interconnections are made.
Measurements between equipment cabinets should not exceed 20 milliohms. Measurements between the
cabinet and ground or the cabinet and the structure should be no more than five milliohms.

     (6) A comprehensive survey of the bonding subsystem should include the following items (figure
6-2).

         (a) Visually check a representative number (5 to 10 percent) of the various types of bonds in use
throughout the facility. Welded, brazed, or silver soldered connections should be examined for broken or
cracked seams, presence of voids, size of filler deposit length and number of deposits (if discontinuous),
and evidence of corrosion. Soft soldered bonds should be inspected for broken connections, evidence of
cold solder joints (crystalline, grainy appearance), and signs of overheating. Soft solder should only be
used to improve conductivity at load bearing joints; it should not be required to provide mechanical
restraint. There shall be no solder joints in either the fault protection subsystem (this includes the green
wire network) or in the lightning protection subsystem. Bolted joints should be checked for looseness,
inadequately sized fasteners, corrosion of either the fastener or main member, improper use of washers
and locknuts, absence of or inadequate coverage with protective coatings, damaged or missing hardware,

6-10


---

                                                                                                                                TM 5-690

and improperly cleaned mating surfaces. Be particularly thorough in the inspection of bolted connections
in areas open or exposed to the weather. Joints using rivets, clamps, and other type fasteners should
generally be examined for looseness and corrosion.

          (b) Record the location and nature of specific bond deficiencies.

          (c) Concurrently with or following the visual inspection of the bonds, perform bond resistance
measurements. Select five to ten bonds that visually appear tight, well made, and corrosion free and
measure their resistances. The sampling should include structural bonds, equipment-to–structure bonds,
connections between safety ground wires, conduit-to-conduit or conduit-to-cabinet joints, bonds in
lightning down conductors (to include structural columns if used for lightning discharge paths), and
others as appropriate. Measure all bonds exhibiting visible defects. These measurements indicate the
actual resistance between the two measurement points and also include the effects of any paths in parallel
with the bond under test.

          (d) For every bond exhibiting a resistance greater than one milliohm, check for looseness; if the
connection is loose, tighten the fastener. Measure the resistance again after tightening. If the resistance is
still greater than one milliohm and the joint can be readily disassembled, disassemble the joint and check
for corrosion, debris, paint, or other non-conductive materials. Remove the material, reassemble the
bond, and re-measure the resistance. If the resistance is still greater than one milliohm, note on the survey
form the location of the bond and indicate the type of corrective action needed.

          (e) Bonding jumpers using wires, cables, or wide metal straps are frequently used for fault
grounding, signal grounding, and lightning grounding. Fault protection jumpers should conform to
Article 250 of the NEC®. If they do not conform to Article 250, the jumpers should be replaced with
cables or straps of the sizes specified by the NEC®. Signal grounding straps should be only as long as
needed to bridge the physical distance and should exhibit a length to width ratio of not greater than 5 to 1.
Lightning bonds should be restricted to not more than 1.8 meters (6 feet) and should only be used to
interconnect lightning down conductors to nearby metallic objects. In addition to these requirements,
examine the end connections at the end of the straps or jumpers for looseness, corrosion, and mechanical
damage as described above. Any bond jumper not conforming to these requirements should be
documented in the survey form. Note the specific location and indicate the type of corrective action
needed.

     (7) A comprehensive survey of the shielding subsystem should include the following items (figure 6-
6).

         (a) Identify the presence and nature (or type) of shields at the facility. (Recognize that shielding
may be incidentally provided by a wall, screen, or other type of barrier that is primarily intended for a
different purpose.) Record the description of the type of shields on the survey form.

          (b) Inspect screens, shielded cabinets, doors, covers, etc., of all designated RF barriers for wear,
damage, corrosion, broken bond straps, broken or damaged bonds, and loose gaskets. Observe equipment
operation for evidence of interference, noise, or malfunctions. Record deficiencies on the survey form.
Ensure that grounding conductors passing through a designated RF barrier are bonded.

          (c) Be sure that the bonds and bonding inspection include the shields.

          (d) Examine cables and connectors for broken or frayed shields, improper mounting, and
evidence of corrosion. Check to see if the termination of cable shields is properly performed.

                                                                                                                                       6-11


---

TM 5-690

6-3. Performance evaluation program

Use the information available from the corrected drawings and the facility survey to determine if
modification or upgrading of the facility is necessary. Compare the grounding, bonding, shielding, and
lightning protection networks and practices with the recommendations contained in the previous chapters
of this manual. While making these comparisons, be particularly alert for indications of operational,
installation, or maintenance problems (either with a system or with a piece of equipment) which may be
directly or indirectly related to a noted deficiency. Where a need for upgrading is indicated, determine
what retrofit steps would be necessary and estimate the costs. If the operational mission of the facility
justifies the cost, proceed with the implementation.

6-4. Upgrades

The following guidelines may be used to help evaluate the survey findings and to help define the retrofit
steps which should be taken. This set of guidelines is not to be considered as all inclusive. Specific
situations can be expected to arise that will not be adequately covered by the guidelines. These situations
must be recognized and dealt with on an individual basis.

  a. Earth electrode subsystem. If the measured resistance of the earth electrode subsystem is greater
than 10 ohms, identify the reason for the high resistance. Review the past record (if available) of earth
resistance measurements for signs of gradual increases in resistance as well as sudden resistance changes.
(Discard from consideration "zero" resistance reading and other similarly unobtainable values.) Examine
the resistance readings for possible correlation with site changes.

       (1) Once the reason for the high resistance and local climatic conditions is established, determine
the most appropriate method in terms of cost and ease of implementation for reducing the resistance.
Typical alternatives include the use of more or longer ground rods, the installation of horizontal grids or
wires, chemical salting, or the drilling of wells down to the permanent water table.

       (2) Carefully review the building drawings to insure that proper connections to the earth electrode
subsystem are provided for all elements of the facility.

       (3) All specific earth electrode subsystem installation deficiencies such as grounding conductor
sizes not in conformance with MIL-STD-188-124B requirements or maintenance deficiencies such as
loose or corroded bonds and fasteners should be corrected as soon as possible.

  b. Lightning protection subsystem If no lightning protection subsystem exists for the structure,
determine if one is needed.

       (1) Where a structural lightning protection subsystem exists, all deficiencies noted during the
survey should be corrected.

         (a) All seriously degraded damaged air terminals should be replaced.

         (b) Air terminals should be relocated as needed so that they are the objects of highest elevation
on the structure and where they provide a 1:1 cone of protection for the antennas without affecting their
operation.

         (c) Down conductors should be rerouted or additional down conductors added where more direct
paths to the earth are needed.

6-12


---

                                                                                                                                TM 5-690

         (d) If not already provided, the lightning protection network should be interconnected with the
earth electrode subsystem, electrical ground, utility pipes, equipment grounds, and with the building
ground to provide common grounding for all.

         (e) All corroded and mechanically damaged connectors and fasteners should be replaced with
UL-approved devices.

         (f) Missing and severely damaged guards should be replaced.

         (g) If the structure is used as a lightning down conductor or as an electrical safety grounding
conductor, see that all joints are effectively bonded.

         (h) If more than 25 percent of the bonds measured exhibit a resistance greater than one milliohm
then all bonds throughout the facility should be inspected carefully, and the resistance measured. Each
one found deficient should be redone.

      (2) The lightning protection subsystem should be expanded as needed to provide protection for
those parts of the facility extending outside the established cones of protection.

      (3) At those facilities where the lightning outage history indicates a need for surge protection on
either signal or power lines, appropriate lightning and surge protectors should be installed. Insure that the
protectors are adequate for protecting the type of equipment on which installed.

  c. Coupling path analysis. Review electrical wiring diagrams and the electrical equipment distribution
within the facility to determine possible direct or indirect coupling paths between noisy equipment and
susceptible electronic apparatus. Apply corrective measures such as relocating equipment, redistributing
the electrical load so that potentially interfering equipment are served by separate feeders, installing
electrical feeders in steel conduit or raceway to reduce magnetic fields, and relocating signal lines to
sensitive equipment at the maximum possible distance from power conductors feeding noisy equipment.

  d. Equipment malfunction analysis. Correlate, if possible, any evidence of equipment malfunctions due
to electrical noise on signal or control cables with the measured values of stray currents or voltages on
grounding conductors and on cable shields. If such correlation exists, determine as best as possible the
probable cause of such noise voltages. Perform corrective actions as necessary to bring the noise levels to
acceptable values.

  e. Signal grounding analysis. Carefully review the drawings of the facility to identify the type of signal
grounding employed throughout the facility. If operational experience as indicated by maintenance logs
or outage reports and operator comments reveal problems with system noise and interference attributable
to grounding deficiencies, determine the severity of the problems and remedy them if necessary.

  f. Shielding analysis. Where shielding deficiencies exist, determine if the need is for additional
shielding or for improved maintenance of the existing shields. If no shielding is present, design and
install shields as needed. If the existing shields have simply degraded through poor aperture control and
poor bond or seam maintenance, implement corrective measures immediately.

  g. Facility “as-built” documentation. Indicate all changes made during the upgrading process on the
facility drawings.

                                                                                                                                       6-13


---

TM 5-690
6-5. Expansions
As operational requirements change, expansions of the grounding and shielding networks in a facility will
be necessary. The added elements must maintain the philosophy and integrity of the existing networks.
When making additions or modifications to shielded areas, the original level of shielding integrity must
be maintained. Particular attention must be directed to the careful bonding of connector shells, the
installation of filters, and other practices which may drastically degrade tile shielding effectiveness of a
housing or other enclosure if not controlled. Following major additions to the facility, the facility should
be resurveyed. Any deficiencies in the installation or compromises to the original networks should be
corrected. File a copy of all survey results in the maintenance file for the facility to provide the initial
starting point for the maintenance history. Finally review all drawings to verify that they are complete
and accurately reflect the actual installation.

6-14


---

                          TM 5-690

               CHAPTER 7

MAINTENANCE OF GROUNDING
     AND BONDING SYSTEMS

7-1. Purpose of maintenance of grounding and bonding systems

Well designed and properly installed grounding, bonding, shielding, and lightning protection networks in
a new facility or in an existing facility can rapidly deteriorate unless adequate and thorough maintenance
is performed at regular intervals throughout the life of the facility.

7-2. Configuration control

Baseline records are of utmost importance when performing maintenance activities. The initial
installation records should be maintained in such a fashion that they could be easily obtained for future
reference.

  a. New installations. In a new facility, consider the initial checkout as the first maintenance inspection
for the facility. Utilize the results or information provided by the initial facility inspection as a base or
starting point of comparison of the results of subsequent inspections. Subsequent inspections should be
performed at least annually. In addition, a thorough inspection should be performed on affected parts or
elements of the networks following major changes or additions to the facility either of the structure itself
or of the equipment or systems located in the structure.

  b. Existing facilities. In an older facility, consider the initial survey evaluation as the initial
maintenance inspection. If a survey has not been made, an initial inspection of the facility should be
made to determine the general condition of grounding networks, bonds, shields, and lightning protection
subsystems. Subsequent to the survey or initial inspection, a maintenance inspection should be conducted
annually and after major changes or additions to the facility as discussed above.

  c. System modifications. Modifications of the facility system and the impact to the grounding system
as a result of these modifications should be documented on the engineering drawings so that future
maintenance activities can include the additions.

7-3. Maintenance and repair records

Chronological records of all tests and observations should be maintained. When a significant departure
from the record is noted, an investigation should be performed to determine the cause and the necessary
corrective action taken. Any measurement (i.e., earth electrode subsystem resistance, bond resistance,
point-to-point ground network resistance, etc.) not meeting the specified or recommended value should be
immediately investigated to see if rework is desired.

  a. Facility maintenance report. Maintenance procedures for the earth electrode subsystem, lightning
protection subsystem, signal reference subsystem, fault protection subsystem, facility ground system,
bonding, and shielding should be prepared. Upon completion of any or all of these procedures, the
facility maintenance report should be prepared and then placed in the permanent maintenance file or
record along with other supporting evidence such as test results, photographs, and drawings. The facility

                          7-1


---

TM 5-690

maintenance report should be reviewed and updated annually along with any supporting maintenance
inspection or testing results.

  b. Major deficiency report. Where deficiencies are noted that are immediately correctable (e.g., broken
or misplaced bond wires or jumpers, loose bolts or screws, or other minor defects), they should be
corrected with appropriate notation made on the facility maintenance report. A major discrepancy report
should be made on major deficiencies (e.g., earth electrode resistance too high, parts of structure outside
the cone of protection, excessive current levels on signal ground conductors, etc.) to identify those areas
needing significant rework or upgrading.

7-4. Earth electrode subsystem

Proper maintenance of the earth electrode subsystem requires the following inspection and testing
activities be performed at regular intervals.

  a. Visual and mechanical inspection. The earth electrode subsystem should be visually inspected every
2 months and mechanically inspected every 12 months per InterNational Electrical Testing Association’s
(NETA) guidelines.

       (1) Inspect all accessible portions of the system. Particularly look for loose connections, corrosion,
and physical damage.

       (2) Check the general overall condition of bonds as excellent, good, or poor. Perform resistance
measurements and record the location of those that measure greater than one milliohm. (Take
photographs as necessary to show nature of problems for before and after comparisons and for historical
documentation purposes.)

       (3) Note any undocumented changes or modifications to system. Update drawings as needed and
correct minor deficiencies (e.g., clean surfaces, retighten or replace connectors and fasteners, reapply
protective coatings, etc.).

       (4) Generally inspect facility site for changes (in vegetation, roads, parking areas, excavation,
drainage, etc.) that could cause future earth resistance variations and note such changes.

       (5) Major deficiencies should be the subject of a major discrepancy report. After major
deficiencies are corrected, the facility should be re-inspected. File the inspection report.

  b. Electrical testing. Electrical testing of the earth electrode subsystem should be conducted every 24
months per NETA guidelines.

       (1) Measure the resistance to earth of the earth electrode subsystem using the fall of potential
method. Test directly in a ground well if available. If not, connect to a signal ground cable, the power
system grounding conductor, a lightning down conductor, or a structural grounding connection.

       (2) Measure stray current in grounding conductor between service disconnecting means and earth
electrode subsystem (current reading).

       (3) Concurrently with or following the visual inspection of the bonds, perform bond resistance
measurements. Select five to ten bonds that visually appear tight, well made, and corrosion free and
measure their resistances. The sampling should include structural bonds, equipment-to–structure bonds,
connections between safety ground wires, conduit-to-conduit or conduit-to-cabinet joints, bonds in

7-2


---

                                                                                                                                TM 5-690

lightning down conductors (to include structural columns if used for lightning discharge paths), and
others as appropriate. Measure all bonds exhibiting visible defects. These measurements indicate the
actual resistance between the two measurement points and also include the effects of any paths in parallel
with the bond under test. For every bond exhibiting a resistance greater than one milliohm, check for
looseness; if the connection is loose, tighten the fastener. Measure the resistance again after tightening.
If the resistance is still greater than one milliohm and the joint can be readily disassembled, disassemble
the joint and check for corrosion, debris, paint, or other non-conductive materials. Remove the material,
reassemble the bond, and re-measure the resistance. If the resistance is still greater than one milliohm,
note on the survey form the location of the bond and indicate the type of corrective action needed.

7-5. Fault protection subsystem

Proper maintenance of the fault protection subsystem requires the following inspection and testing
activities be performed at regular intervals.

  a. Visual and mechanical inspection. The fault protection subsystem should be visually inspected every
2 months and mechanically inspected every 12 months per NETA guidelines.

       (1) Inspect all electrical/electronic equipment for safety grounding conductors (green wire). Check
to see that sizes conform to all designated requirements.

       (2) Spot check all green wire connections to see that they are tight and free of corrosion.

       (3) Check inside equipment, switch boxes, and distribution panels to see that the white wire
(neutral) is not grounded at these locations.

       (4) Check the grounding connection at the first service disconnect to make sure it is tight and free
of corrosion.

       (5) Generally check the electrical supporting structures for looseness in joints or bonds and
evidence of corrosion.

  b. Electrical testing. Electrical testing of the fault protection subsystem should be conducted every 24
months per NETA guidelines.

       (1) With neutral disconnected at first service disconnect, the resistance to ground should be at least
one megohm. (New ground resistance testers on the market today do not require that the neutral
conductor be disconnected.)

       (2) Perform spot check resistance measurements on power receptacles and stray current
measurements on safety ground to insure that the ground terminals on the receptacles are properly
grounded to the facility ground system and no currents are flowing on grounding conductor.

       (3) Measure for stray currents at obvious locations.

       (4) Perform resistance tests of a sample of bonds as described earlier in this chapter

7-6. Lightning protection subsystem

Proper maintenance of the lightning protection subsystem requires the following inspection and testing
activities be performed at regular intervals.

                                                                                                                                         7-3


---

TM 5-690

  a. Visual and mechanical inspection. The lightning protection subsystem should be visually inspected
every 2 months and mechanically inspected every 12 months per NETA guidelines.

       (1) Verify that all facility components and antennas are within the cone of protection.
       (2) Check for evidence of burning and/or pitting, as well as melting of air terminals.
       (3) Check for burned fasteners.
       (4) Check for broken or melted down conductors or severely damaged as well as distorted roof
conductors, down conductors, and bonding jumpers.
       (5) Look for signs of arcing or flashover indicating a need for bonding jumpers or spark gaps.
       (6) Check for corroded or loose connectors and fasteners.
       (7) Verify that copper-to-aluminum contact does not occur except through Underwriters
Laboratories (UL) approved bimetallic connectors.
       (8) Verify that all guards for down conductors are in place and without severe mechanical damage.
       (9) Verify that all guards are bonded to down conductors (at both ends of guard).
  b. Electrical testing. Bond resistance tests of a sample of bonds as described earlier in this chapter
should be conducted every 24 months per NETA guidelines.

7-7. Signal reference subsystems

Proper maintenance of the signal reference subsystems requires the following inspection and testing
activities be performed at regular intervals.

  a. Visual and mechanical inspection. The signal reference subsystem should be visually inspected
every 2 months and mechanically inspected every 12 months per NETA guidelines.

       (1) Inspect connections to equipment signal ground terminals and equipotential plane for looseness
and corrosion. Apply corrective measures.

       (2) Check to see if any new equipment has been added or relocated since the last inspection. If so,
check interconnecting cables for conformance with the requirements.

       (3) Ensure that labels and protective covers are in place and free of serious damage.
       (4) Inspect equipment grounding cables for correct sizes, physical damage, and properly bonded
end connections.
  b. Electrical testing. Electrical testing of the fault protection subsystem should be conducted every 24
months per NETA guidelines.
       (1) Perform resistance tests of a sample of bonds as described earlier in this chapter.
       (2) Perform point-to-point resistance measurements at select locations comprising approximately
25 percent of available locations.

7-4


---

                                                                                                                                TM 5-690

       (3) Perform stray current measurements and differential noise voltage measurements.

7-8. Facility shielding

Proper maintenance of the facility shielding requires the following inspection and testing activities be
performed at regular intervals.

  a. Visual and mechanical inspection. The signal reference subsystem should be visually inspected
every 2 months and mechanically inspected every 12 months per NETA guidelines.

       (1) Check personnel barriers for mechanical strength, signs of damage, and proper grounding (if
metallic).

       (2) Insure that all shields around high voltage apparatus are properly labeled. Labels should be
provided in accordance with the individual facility standards, practices and requirements.

       (3) Check electromagnetic (EM) shields for adequate bonding.
       (4) Inspect all EM shields for holes or openings added since last inspection. Check to see that
such openings are properly covered with screening or covers.
       (5) Inspect power line and signal line filters on wires entering shielded areas for proper peripheral
grounding.
       (6) Inspect cable shield pigtails for excessive length.
       (7) Inspect connectors for tightness, evidence of corrosion, or physical damage.
       (8) Ensure that all grounding conductors penetrating a designated radio frequency (RF) barrier are
peripherally bonded to barrier.
  b. Electrical testing. Bond resistance tests of a sample of bonds as described earlier in this chapter
should be conducted every 24 months per NETA guidelines.

7-9. Performance evaluation program

The purpose of the performance evaluation program is to provide checklists and procedures for the
evaluation of compliance to overall grounding, bonding, and shielding practices. Individuals qualified in
the proper methods of obtaining an acceptable grounding system accomplish the evaluation mainly
through visual inspection. Checklists should be prepared to include the following attributes for
inspection.

  a. Resistance to earth of the earth electrode subsystem should be less than 10 ohms.
  b. The lightning down conductors should be continuous and welded or brazed to the earth electrode
subsystem.
  c. Underground metal pipes entering the facility should be bonded to the earth electrode subsystem.
  d. The fall-of-potential method should be used to measure the earth electrode subsystem.

                                                                                                                                         7-5


---

TM 5-690

  e. A separate grounding conductor (green wire) should exist for the power system and be installed with
the phase and neutral conductors.

  f. Document if conduit is used in lieu of the separate grounding conductor.
  g. All non-current carrying metal objects should be grounded. All main metallic structural members,
electrical supporting structures, metallic piping, tubing, and supports should be electrically continuous
and grounded.
  h. The alternating current (ac) grounded conductor (neutral) should be grounded only at the source
distribution transformer and at the service entrance to the earth electrode subsystem.
  i. All generators and their frames should be grounded. Generator neutrals should be tied together and
grounded by a single lead to the earth electrode subsystem.
  j. The ground terminals of all ac outlets should be connected to the facility ground system through the
grounding (green) conductor.
  k. One leg of each direct current (dc) power system should be grounded.
  l. The facility should be protected against lightning.

       (1) All antennas should be inside a 1:1 cone of protection.
       (2) Bends in down conductors of the lightning protection subsystem should have a radius of at
least 20 cm (8 inches) and not less than 90°.
       (3) Metal objects should not be within 1.8 meters (6 feet) of the lightning down lead.
       (4) All bonds between elements of the lightning protection subsystem should be welded, brazed, or
secured by UL approved clamps.
  m. If the facility has a metal tower, it should have a direct tie to the earth electrode subsystem with the
down conductors bonded to the tower at the base. If in conduit, the conduit should be bonded at each end.
  n. The waveguide should be grounded near the antenna, at the vertical to horizontal transition, and at
the waveguide entry port.
  o. All metal hand rails, ladders, stairways, antenna pedestals, and other objects subject to human
contact should be grounded.
  p. Power lines at the point-of-entry to the facility should be protected with approved lightning arresters.
  q. Overall cable shields should be grounded at each end.
  r. Bonds should show no signs of corrosion, should be adequately torqued, and be low in resistance.
  s. The routing and layout of power lines and high level signal lines must be kept separate from low
level signal lines.
  t. The equipotential plane should be bonded to the facility ground earth electrode subsystem.

7-6


---

                                                                                                                                TM 5-690
  u. Resistance measurements should be conducted on the equipotential plane.
  v. Ground-fault-circuit-interrupters (GFCI) should be installed on 15 and 20 ampere convenience
outlets.

                                                                                                                                         7-7


---

            TM 5-690

APPENDIX A
REFERENCES

Required Publications

Government Publications

Department of Defense
       DOD Instruction 6055.11
       Protection of DoD Personnel from Exposure to Radiofrequency Radiation
       [Cited in paragraph 4-3c(8)]

       MIL-STD-188-124B
       Grounding, Bonding and Shielding for Common Long Haul/Tactical Communication Systems
       Including Ground Based Communications-Electronics Facilities and Equipment
       [Cited in paragraph 3-3c(2), 3-5c(1)(g), 6-2b(4)(a), 6-4a(3)]

       MIL-HDBK-232A
       Red/Black Engineering-Installation Guidelines
       [Cited in paragraph 4-3e]

       MIL-HDBK-419A
       Grounding, Bonding, and Shielding for Electronic Equipment and Facilities
       [Cited in paragraph 3-2j(8)]

Federal Communications Commission
       Office of Engineering and Technology Bulletin 56 (OET-56)
       Questions and Answers about Biological Effects and Potential Hazards of Radiofrequency
       Electromagnetic Fields
       [Cited in paragraph 4-3c(9)]

Non-Government Publications

Institute of Electrical and Electronic Engineers (IEEE):
445 Hoes Lane, P. O. Box 1331, Piscataway, NJ 08855-1331

       IEEE 80-1986
       IEEE Guide for Safety in AC Substation Grounding
       [Cited in paragraph 3-3e(9)]

       IEEE 81-1983
       IEEE Guide for Measuring Earth Resistivity Grounding
       Impedance and Earth Surface Potentials of Ground Systems (1983)
       [Cited in paragraph 3-3e(2)]

                                                                                               A-1


---

TM 5-690

       IEEE 446-1995
       IEEE Recommended Practice for Emergency and Standby Power
       Systems for Industrial and Commercial Applications (1995)
       [Cited in paragraph 2-3c(8)]

       IEEE C62.2-1987
       Guide for the Application of Gapped Silicon-Carbide Surge Arresters for AC Systems
       [Cited in paragraph 3-4d(1)(l)]

       IEEE C62.22-1997
       Guide for the Application of Metal-Oxide Surge Arresters for AC Systems
       [Cited in paragraph 3-4d(1)(l)]

       IEEE C62.22.1-1996
       Guide for the Connection of Surge Arresters to Protect Insulated, Shielded Electric Power Cable
       Systems
       [Cited in paragraph 3-4d(1)(l)]

       IEEE C62.37.1-2000
       Guide for the Application of Thyristor Surge Protective Devices
       [Cited in paragraph 3-4d(1)(l)]

       IEEE C62.42-1992
       Guide for the Application of Gas Tube and Air Gap Arrester Low-Voltage (Equal to or Less Than
       1000 Vrms or 1200Vdc) Surge Protective Devices
       [Cited in paragraph 3-4d(1)(l)]

       IEEE C62.43-1999
       Guide for the Application of Surge Protectors Used in Low-Voltage (Equal to or Less Than 1000
       Vrms or 1200Vdc) Data, Communications, and Signaling Circuits
       [Cited in paragraph 3-4d(1)(l)]

       IEEE C95.3-1992
       Recommended Practice for the Measurement of Potentially Hazardous Electromagnetic Fields –
       RF and Microwave
       [Cited in paragraph 4-3c(9)]

InterNational Electrical Testing Association (NETA)
P.O. Box 687, Morrison, CO 80645
www.netaworld.org

       IETA 1 - 1997
       Maintenance Testing Specifications for Electric Power Distribution Equipment and Systems
       [Cited in paragraphs 3-2j(8), 7-4a, 7-4b, 7-5a, 7-5b, 7-6a, 7-6b, 7-7a, 7-7b, 7-8a, and 7-8b]

National Fire Protection Association (NFPA):
One Batterymarch Park, P. O. Box 9101, Quincy, MA 02269-9101

       NFPA 70
       National Electrical Code (1999)
       [Cited in paragraph 1-1c, 1-2b, 2-3c(7)(a) through (c), 2-4b, 3-3b, 3-3b(8), 3-3c(1), 3-3c(6-8),

A-2


---

                                                                                                                                TM 5-690

       3-3c(13)(b), 3-4d(1)(j), 6-2b(6)(e)]

       NFPA 780
       Standard for the Installation of Lightning Protection Systems (1997)
       [Cited in paragraph 1-2b, 3-3c(10), 3-4a(3)]

Underwriters’ Laboratories, Inc. (UL):
333 Pfingsten Road, Northbrook, IL 60062-2096

       UL 486A
       Wire Connectors and Soldering Lugs for Use with Copper Conductors, Ninth Edition (1998)
       [Cited in paragraph 3-3d(10)]

       UL 486B
       Wire Connectors for Use with Aluminum Conductors, Fourth Edition (1997)
       [Cited in paragraph 3-3d(10)]

Related Publications

Institute of Electrical and Electronic Engineers (IEEE):
445 Hoes Lane, P. O. Box 1331, Piscataway, NJ 08855-1331

       IEEE 142-1991
       IEEE Recommended Practice for Grounding of Industrial and
       Commercial Power Systems (1983)

       IEEE 1100-1999
       IEEE Recommended Practice for Powering and Grounding
       Electronic Equipment (1999)

       IEEE 1159-1995
       IEEE Recommended Practice for Monitoring
       Power Quality (1995)

       IEEE C2-1997
       National Electrical Safety Code (1997)

Lightning Protection Institute:
3335 N. Arlington Hts. Road, Suite E, Arlington Hts., IL 60004

       LPI-175
       Installation Code

Underwriters’ Laboratories, Inc. (UL):
333 Pfingsten Road, Northbrook, IL 60062-2096

       UL 96
       Lightning Protection Components, Fourth Edition (2000)

       UL 96A
       Installation Requirements for Lightning Protection Systems, Tenth Edition (1998)

                                                                                                                            A-3


---

TM 5-690

Prescribed Forms
The following forms are printed in the back of this manual and are also available on the Army Electronic
Library (AEL) CD-ROM (EM 0001) and the USAPA web site (www.usapa.army.mil).

         DA Form 7452-R
         Earth ground electrode subsystem checklist for new facilities
         [Cited in paragraph 1-5a and 3-2a]

         DA Form 7452-1-R
         Ground fault protection subsystem checklist for new facilities
         [Cited in paragraph 1-5a and 3-3d]

         DA Form 7452-2-R
         Lightning protection grounding subsystem checklist for new facilities
         [Cited in paragraph 1-5a and 3-4f[

         DA Form 7452-3-R
         Signal ground reference subsystem checklist for new facilities
         [Cited in paragraph 1-5a and 3-5f]

         DA Form 7452-4-R
         Earth electrode subsystem checklist for existing facilities
         [Cited in paragraph 1-5b and 6-1]

         DA Form 7452-5-R
         Grounding and bonding connection checklist for existing facilities
         [Cited in paragraph 1-5b and 6-1]

         DA Form 7452-6-R
         Lightning protection grounding subsystem checklist for existing facilities
         [Cited in paragraph 1-5b and 6-1]

         DA Form 7452-7-R
         Ground fault protection subsystem checklist for existing facilities
         [Cited in paragraph 1-5b and 6-1]

         DA Form 7452-8-R
         Signal ground reference subsystem checklist for existing facilities
         [Cited in paragraph 1-5b and 6-1]

         DA Form 7452-9-R
         Shielding subsystem checklist for existing facilities
         [Cited in paragraph 1-5b and 6-1]

A-4


---

          TM 5-690

GLOSSARY

Section I
Abbreviations

A
Amperes

ac
Alternating current

AWG
American Wire Gage

C4ISR
Command, Control, Communications, Computer, Intelligence, Surveillance, and Reconnaissance

C
Centigrade

CAA
Controlled Access Area

CBEA
Controlled BLACK Equipment Area

C-E
Communications Equipment

cm
Centimeter

cmil
Circular mils

dB
Decibel

dc
Direct current

DO
Design objective

EG
Engine generator

                                                                                            G-1


---

TM 5-690

EM
Electromagnetic

EMC
Electromagnetic Compatibility

EMI
Electromagnetic Interference

EMP
Electromagnetic Pulse

EMT
Electrical metallic tubing

F
Fahrenheit

ft
Feet

GFCI
Ground Fault Circuit Interrupter

GHz
Gigahertz

HVAC
Heating, Ventilating, and Air Conditioning

Hz
Hertz

IDF
Intermediate Distribution Frame

IEEE
Institute of Electrical and Electronics Engineers

in
Inch

I/O
Input/Output

kcmil
One-thousand circular mils

kg
Kilogram

G-2


---

kHz                                   TM 5-690
Kilohertz                                    G-3

kV
Kilo Volt

kVA
Kilo Volt Amperes

kW
Kilo Watts

LEA
Limited Exclusion Area

m
Meter

MHz
Megahertz

mm
Millimeter

MOV
Metal Oxide Varistor

MOS
Metal oxide semiconductor

MVA
Mega Volt Amperes

NEC
National Electrical Code

NFPA
National Fire Protection Association

PA
Public Address

PBX
Private Branch Exchange

PIV
Peak Inverse Voltage

psi
Pounds per square inch


---

TM 5-690

R
Resistance
RF
Radio Frequency
RFI
Radio Frequency Interference
S
Second
TM
Technical Manuals
TPD
Terminal Protection Devices
TSD
Transient Suppression Devices
TREE
Transient radiation effects on electronics
UL
Underwriters’ Laboratories
UPS
Uninterruptible Power Supply
VRMS
Volts root-mean-square
ZNR
Zinc Oxide Non-Linear Resistor

G-4


---

                                                                                                                                TM 5-690

Section II

Terms
Absorption Loss
The attenuation of an electromagnetic wave as it passes through a shield. This loss is primarily due to
induced currents and the associated I2R loss.

Air Terminal
The lightning rod or conductor placed on or above a building, structure, tower, or external conductors for
the purpose of intercepting lightning.

Aperture
An opening in a shield through which electromagnetic energy passes.

Balanced Line
A line or circuit using two conductors instead of one conductor and ground (common conductor). The
two sides of the line are symmetrical with respect to ground. Line potentials to ground and line currents
are equal but have opposite phase at corresponding points along the line.

Bond
The electrical connection between two metallic surfaces established to provide a low resistance path
between them.

Bond, Direct
An electrical connection utilizing continuous metal-to-metal contact between the members being joined.

Bond, Indirect
An electrical connection employing an intermediate electrical conductor or jumper between the bonded
members.

Bond, Permanent
A bond not expected to require disassembly for operational or maintenance purposes.

Bond, Semi-permanent
Bonds expected to require periodic disassembly for maintenance, or system modification, and that can be
reassembled to continue to provide a low resistance interconnection.

Bonding
The process of establishing the required degree of electrical continuity between the conductive surfaces of
members to be joined.

Building
The fixed or transportable structure that houses personnel and equipment and provides the degree of
environmental protection required for reliable performance of the equipment housed within.

Cabinet
A protection housing or covering for two or more units or pieces of equipment. A cabinet may consist of
an enclosed rack with hinged doors.

                                                                                                                                        G-5


---

TM 5-690

Case
A protective housing for a unit or piece of electrical or electronic equipment.

Chassis
The metal structure that supports the electrical components which make up the unit or system.

Circular Mil
A unit of area equal to the area of a circle whose diameter is one mil (1 mil = 0.001-6 inch). A circular
mil is equal to or 78.54 percent of a square mil (1 square mil = 10 square inch). The area of a circle in
circular mils is equal to the square of its diameter in mils.

Circuit
An electronic closed-loop path between two or more points used for signal transfer.

Common-Mode Voltage
That amount of voltage common to both input terminals of a device.

Common-Mode Rejection
The ability of a device to reject a signal which is common to both its input terminals.

Conducted Interference
Undesired signals that enter or leave equipment along a conductive path.

Copper Clad Steel
Steel with a coating of copper bonded on it.

Coupling
Energy transfer between circuits, equipment, or systems.

Coupling, Conducted
Energy transfer through a conductor.

Coupling, Free-Space
Energy transfer via electromagnetic fields not in a conductor.

Cutoff Frequency
The frequency below which electromagnetic energy will not propagate in a waveguide.

Degradation
A decrease in the quality of a desired signal (i.e., decrease in the signal-to-noise ratio or an increase in
distortion), or an undesired change in the operational performance of equipment as the result of
interference.

Down Conductor, Lightning
The conductor connecting the air terminal or overhead ground wire to the earth electrode subsystem.

Earth Electrode Subsystem
A network of electrically interconnected rods, plates, mats, or grids installed for the purpose of
establishing a low resistance contact with earth.

G-6


---

                                                                                                                                TM 5-690

Electric Field
A vector field about a charged body. Its strength at any point is the force that would be exerted on a unit
positive charge at that point.

Electromagnetic Compatibility (EMC)
The capability of equipment or systems to be operated at their intended operational environment, within
designed levels of efficiency, without causing or receiving degradation due to unintentional EMI. EMC is
the result of an engineering planning process applied during the life cycle of equipment. The process
involves careful consideration of frequency allocation, design, procurement, production, site selection,
installation, operation, and maintenance.

Electromagnetic Interference (EMI)
Any electrical or electromagnetic phenomenon, manmade or natural, either radiated or conducted, that
results in unintentional and undesirable responses from, or performance degradation or malfunction of,
electronic equipment.

Electromagnetic Pulse (EMP)
A large impulsive type electromagnetic wave generated by nuclear or chemical explosions.

Equipment, Unit or Piece Of
An item having a complete function apart from being a component of a system.

Equipment Grounding
Attained by the grounding conductor of the fault protection subsystem, and/or bonding to the signal
reference subsystem or the structural steel elements of the building.

Equipotential Plane
A grid, sheet, mass, or masses of conducting material which, when bonded together, offers a negligible
impedance to current flow (serves as signal reference subsystem for new facilities).

Facility
A building or other structure, either fixed or transportable in nature, with its utilities, ground networks,
and electrical supporting structures. All wiring, cabling as well as electrical and electronic equipment are
also part of the facility.

Facility Ground System
The electrically interconnected system of conductors and conductive elements that provides multiple
current paths to earth. The facility ground system includes the earth electrode subsystem, lightning
protection subsystem, signal reference subsystem, fault protection subsystem, as well as the building
structure, equipment racks, cabinets, conduit, junction boxes, raceways, duct work, pipes, and other
normally noncurrent-carrying metal elements.

Far Field
The region of the field of an antenna where the radiation field predominates and where the angular field
distribution is essentially independent of the distance from the antenna.

Fault
An unintentional short-circuit, or partial short-circuit, (usually of a power circuit) between energized
conductors or between an energized conductor and ground.

                                                                                                                                        G-7


---

TM 5-690

First Service Disconnect
The necessary equipment (circuit breakers, switches, fuses, etc.) located at the point of entrance of power
conductors to a building or other structure.

Ground
The electrical connection to earth primarily through an earth electrode subsystem. This connection is
extended throughout the facility via the facility ground system consisting of the signal reference
subsystem, the fault protection subsystem, the lightning protection subsystem, and the earth electrode
subsystem.

Grounded Conductor
(Neutral) The circuit conductor that is intentionally grounded (at first service disconnect or power
source).

Grounding Conductor
(Green Wire) A conductor used to connect equipment or the grounded circuit of a power system to the
earth electrode subsystem.

Higher Frequency Ground
The interconnected metallic network (equipotential plane) intended to serve as a common reference for
currents and voltages at frequencies above 30 kHz and in some cases above 300 kHz. Pulse and digital
signals with rise and fall times of less than 1 microsecond are classified as higher frequency signals.

Interface
Any electrical connection (encompassing power transfer, signaling, or control functions) between two or
more equipments or systems.

Isokeraunic (or isoceraunic)
Showing equal frequency of thunderstorms.

Isolation
Physical and electrical arrangement of the parts of an equipment, system, or facility to prevent
uncontrolled electrical contact within or between the parts.

Lightning Protection Subsystem
A complete subsystem consisting of air terminals, interconnecting conductors, ground terminals, arresters,
and other connectors or fittings required to assure a lightning discharge will be safely conducted to earth.

Lower Frequency Ground
A dedicated, single-point network intended to serve as a reference for voltages and currents, whether
signal, control, or power from dc to 30 kHz and in some cases to 300 kHz. Pulse and digital signals with
rise and fall times greater than 1 microsecond are considered to be lower frequency signals.

Magnetic Field
A vector field produced by a continuous flow of charge.

Multipoint Ground
More than one path to ground.

G-8


---

                                                                                                                                TM 5-690

National Electrical Code (NEC)
A standard governing the use of electrical wire, cable, and fixtures installed in buildings. It is sponsored
by the National Fire Protection Association (NFPA-70) under the auspices of the American National
Standards Institute (ANSI-CI).

Near Field
The region of the field immediately surrounding an antenna where the inductive and capacitive fields
predominate. In this region the angular distribution of the field varies with distance from the antenna.

Neutral
The ac power system conductor that is intentionally grounded on the supply side of the first service
disconnecting means. It is the low potential (white) side of a single-phase ac circuit or the low potential
fourth wire of a three-phase wye distribution system. The neutral (grounded conductor) provides a
current return path for ac power currents whereas the grounding (or green) conductor does not, except
during fault conditions.

Penetration
The passage through a partition or wall of an equipment or enclosure by a wire, cable, or other conductive
object.

Plane Wave
An electromagnetic wave that predominates in the far field region of an antenna, and with a wavefront
which is essentially in a flat plane. In free space, the characteristic impedance of a plane wave is 377
ohms.

Rack
A vertical frame on which one or more units of equipment are mounted.

Radiation
The emission and propagation of electromagnetic energy through space.

Radiation Resistance
The resistance which, if inserted in place of an antenna, would consume the same amount of power that is
radiated by the antenna.

Radio Frequency Interference (RFI)
RFI is manmade or natural, intentional or unintentional electromagnetic propagation that results in
unintentional and undesirable responses from or perform ante degradation or malfunction of, electronic
equipment.

Reflecting Loss
The portion of the transition loss, expressed in dB, that is due to the reflection of power at a barrier or
shield. Reflection loss is determined by the magnitude of the wave impedance inside the barrier relative
to the wave impedance in the propagation medium outside the barrier.

RF-Tight
Offering a high degree of electromagnetic shielding effectiveness.

                                                                                                                                        G-9


---

TM 5-690

Shield
A housing, screen, or cover which substantially reduces the coupling of electric and magnetic fields into
or out of circuits or prevents the accidental contact of objects or persons with parts or components
operating at hazardous voltage levels.

Shielding Effectiveness
A measure of the reduction or attenuation in the electromagnetic field strength at a point in space caused
by the insertion of a shield between the source and that point.

Signal Reference Subsystem
A conductive sheet or cable network/mesh providing an equipotential reference for C-E equipment to
minimize interference and noise.

Signal Return
A current-carrying path between a load and the signal source. It is the low side of the closed loop energy
transfer circuit between a source-load pair.

Structure
Any fixed or transportable building, shelter, tower, or mast that is intended to house electrical or
electronic equipment or otherwise support or function as an integral element of an electronics complex.

Supporting Structures, Electrical
Normally non-electrified conductive structural elements near to energized electrical conductors such that
a reasonable possibility exists of accidental contact with the energized conductor. Examples are conduit
and associated fittings, junction and switch boxes, cable trays, electrical/electronic equipment racks,
electrical wiring cabinets, and metallic cable sheaths.

Transducer
A device which converts the energy of one transmission system into the energy of another transmission
system.

Thunderstorm Day
A local calendar day on which thunder is heard.

Undesired Signal
Any signal which tends to produce degradation in the operation of equipment or systems.

Wave Impedance
The ratio of the electric field strength to the magnetic field strength at the point of observation.

Zone Of Protection
That space that is below and adjacent to a lightning protection subsystem that is substantially immune to
direct lightning discharges.

G-10


---



---



---



---



---



---



---



---



---



---



---



---



--- 