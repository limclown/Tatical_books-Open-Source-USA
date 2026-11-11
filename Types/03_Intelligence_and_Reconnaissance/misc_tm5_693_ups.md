# misc_tm5_693_ups  TM 5-693

TECHNICAL MANUAL

    UNINTERRUPTIBLE POWER
  SUPPLY SYSTEM SELECTION,

         INSTALLATION, AND
MAINTENANCE FOR COMMAND,
 CONTROL, COMMUNICATIONS,

   COMPUTER, INTELLIGENCE,
         SURVEILLANCE, AND

    RECONNAISSANCE (C4ISR)
                 FACILITIES

                APPROVED FOR PUBLIC RELEASE: DISTRIBUTION IS UNLIMITED

               HEADQUARTERS, DEPARTMENT OF THE ARMY
                                                                            31 MAY 2002


---

TM 5-693

                     REPRODUCTION AUTHORIZATION/RESTRICTIONS

                   This manual has been prepared by or for the Government and, except to
                   the extent indicated below, is public property and not subject to
                   copyright.
                   Reprint or republication of this manual should include a credit
                   substantially: “Department of the Army, TM 5-693, Uninterruptible
                   Power Supply System Selection, Installation, and Maintenance for
                   Command, Control, Communications, Computer, Intelligence,
                   Surveillance, and Reconnaissance (C4ISR) Facilities, 31 May 2002.”
                   Table 2-2. Harmonic currents present in input current to a typical
                   rectifier in per-unit of the fundamental current reprinted with permission
                   from IEEE Std. 519-1981 “IEEE Guide for Harmonic Control and
                   Reactive Compensation of Static Power Converters”, copyright © 1981
                   by IEEE. The IEEE disclaims any responsibility of liability resulting
                   from the placement and use in the described manner.
                   Table 3-1. IEEE table 3-2 reprinted with permission from IEEE Orange
                   Book, “Emergency and Standby Power Systems for Industrial and
                   Commercial Applications” Copyright © 1996, by IEEE. The IEEE
                   disclaims any responsibility of liability resulting from the placement and
                   use in the described manner.


---

                                                                          TM 5-693

Technical Manual                                                                 HEADQUARTERS
No. 5-693                                                       DEPARTMENT OF THE ARMY

                                                                             Washington, DC, 31 May 2002

           APPROVED FOR PUBLIC RELEASE; DISTRIBUTION IS UNLIMITED

 Uninterruptible Power Supply System Selection, Installation, and
Maintenance for Command, Control, Communications, Computer,
 Intelligence, Surveillance, and Reconnaissance (C4ISR) Facilities

                                                                     Paragraph                            Page

CHAPTER 1  INTRODUCTION
           Purpose
           Scope                                                     1-1                                  1-1
           References
           Principles and configurations                             1-2                                  1-1
           Design criteria and selection
           Installation and testing                                  1-3                                  1-1
           Maintenance
                                                                     1-4                                  1-1

                                                                     1-5                                  1-3

                                                                     1-6                                  1-3

                                                                     1-7                                  1-4

CHAPTER 2 PRINCIPLES AND CONFIGURATIONS OF UNINTERRUPTIBLE

           POWER SUPPLY (UPS) SYSTEMS

           Principles of static UPS systems                          2-1                                  2-1

           Principles of rotary UPS systems                          2-2                                  2-29

           Common static UPS system configurations                   2-3                                  2-33

           Rotary UPS system configurations                          2-4                                  2-36

CHAPTER 3 DESIGN AND SELECTION OF UNINTERRUPTIBLE POWER

           SUPPLY (UPS)

           Selecting an UPS                                          3-1                                  3-1

           Static UPS system ratings and size selection              3-2                                  3-13

           Rotary UPS system ratings and size selection              3-3                                  3-18

CHAPTER 4 INSTALLATION AND TESTING OF UNINTERRUPTIBLE

           POWER SUPPLY (UPS)

           Construction and installation of static UPS systems       4-1                                  4-1

           Construction and installation of rotary UPS systems       4-2                                  4-6

           Power distribution and equipment grounding and shielding  4-3                                  4-7

           requirements

           Testing and start-up                                      4-4                                  4-11

           Test equipment                                            4-5                                  4-19

CHAPTER 5 UNINTERRUPTIBLE POWER SUPPLY (UPS) SYSTEMS

           MAINTENANCE PROCEDURES

           Maintenance for UPS systems                               5-1                                  5-1

           UPS battery maintenance                                   5-2                                  5-5

APPENDIX A REFERENCES                                                                                     A-1

                                                                          i


---

TM 5-693

APPENDIX B SELECTING AN UNINTERRUPTIBLE POWER SUPPLY (UPS):                   B-1

             AN EXAMPLE

GLOSSARY                                                                      G-1

INDEX                                                                         I-1

                         LIST OF TABLES

 Table       Title                                                            Page

 Table 2-1   Characteristics of UPS battery types                             2-23
 Table 2-2
             Harmonic currents present in input current to a typical rectifier in per-unit of 2-26
 Table 3-1
 Table 3-2   the fundamental current
 Table 3-3
 Table 3-4   General criteria for determining the purposes of an UPS          3-3
 Table 3-5
 Table 3-6   Comparison of reliability of parallel redundant and parallel configurations 3-9
 Table 3-7
 Table 3-8   Criteria for evaluating UPS battery                              3-11
 Table 3-9
 Table 4-1   Typical rectifier/charger ratings                                3-14
 Table 4-2
 Table 4-3   Typical inverter ratings                                         3-14
 Table 4-4
 Table 4-5   Typical static switch ratings                                    3-14
 Table 4-6
 Table 4-7   Typical environmental ratings                                    3-14
 Table 4-8
 Table 4-9   Typical load power factors and inrush requirements               3-15
 Table 5-1
 Table 5-2   Updated typical rotary UPS ratings                               3-18
 Table 5-3
 Table 5-4   Circuit breaker corrective action                                4-19
 Table 5-5
             Rectifier/battery charger corrective action                      4-20
  Figure
             Battery corrective action                                        4-20
 Figure 1-1
 Figure 1-2  Inverter/static switch corrective action                         4-21
 Figure 2-1
 Figure 2-2  UPS system corrective action                                     4-21
 Figure 2-3
             Motor/engine corrective action                                   4-22
ii
             Generator corrective action                                      4-22

             Suggested test accessory list for battery maintenance            4-22

             Suggested test equipment list for troubleshooting an UPS module  4-23

             Major system inspection general                                  5-3

             Weekly battery inspection                                        5-6

             Monthly battery inspection                                       5-6

             Quarterly battery inspection                                     5-7

             Annual battery inspection                                        5-8

                         LIST OF FIGURES

             Title                                                            Page

             Simple version of a static UPS                                   1-2

             Rotary UPS (shown with primary power on)                         1-2

             Basic static UPS system                                          2-1

             SCR static switching transfer                                    2-3

             SCR switching transfer with UPS isolation                        2-4


---

                                                                              TM 5-693

                             LIST OF FIGURES (continued)

Figure       Title                                                                       Page

Figure 2-4   Static switching transfer with circuit breaker                              2-5
Figure 2-5
Figure 2-6   UPS maintenance bypass switching                                            2-6
Figure 2-7
Figure 2-8   Half-wave diode rectifier with resistive load                               2-7
Figure 2-9
Figure 2-10  Half-wave SCR rectifier with resistive load                                 2-7
Figure 2-11
Figure 2-12  Center-tap full-wave uncontrolled rectifier                                 2-9
Figure 2-13
Figure 2-14  Full-wave bridge uncontrolled rectifier                                     2-10
Figure 2-15
Figure 2-16  Three-phase uncontrolled single way rectifier                               2-11
Figure 2-17
Figure 2-18  Three-phase uncontrolled bridge rectifier                                   2-12
Figure 2-19
Figure 2-20  Single-phase controlled bridge rectifier                                    2-13
Figure 2-21
Figure 2-22  Three-phase controlled bridge rectifier                                     2-14
Figure 2-23
Figure 2-24  Simple single-phase inverter                                                2-15

Figure 2-25  Voltage control using pulse width control                                   2-16
Figure 2-26
Figure 2-27  Pulse width modulation (PWM)                                                2-17
Figure 2-28
Figure 2-29  Ferroresonant transformer                                                   2-18

Figure 2-30  Three-phase inverter                                                        2-19
Figure 2-31
Figure 3-1   Single-phase static transfer switch                                         2-20
Figure 3-2
Figure 3-3   Inertia-driven ride-through system                                          2-29
Figure 3-4
Figure 3-5   Battery supported motor generator (M-G) set                                 2-30
Figure 3-6
Figure 4-1   Nonredundant static UPS system                                              2-33
Figure 4-2
Figure 4-3   Static UPS system with static transfer switch                               2-34
Figure 4-4
             Static UPS system with static transfer switch and an alternate source       2-34
Figure 4-5
             regulating transformer
Figure 4-6
             Redundant static UPS system                                                 2-35
Figure 4-7
             Cold standby redundant static UPS system                                    2-36

             Dual redundant static UPS system with static transfer switches              2-37

             Inertia-driven ride-through system with a synchronous motor                 2-38

             Inertia-driven ride-through system with an induction motor and an eddy      2-38

             current clutch

             Battery supported inertia system                                            2-39

             Battery supported M-G set                                                   2-39

             Determine the general need for an UPS                                       3-1

             Determine the facility need for an UPS                                      3-2

             Determine the required power is a key step in the UPS selection process     3-7

             Redundancy improves system reliability                                      3-9

             Basic redundant UPS designs                                                 3-10

             Determining affordability requires that all costs be considered             3-12

             Static UPS system 150 to 750 kVA (courtesy of Liebert)                      4-2

             Various battery rack configurations (courtesy of Excide Electronics)        4-3

             Double-ended substation connected in secondary selective configuration      4-5

             Rotary UPS system 200 kVA to 10,000 kVA (courtesy of HITEC Power            4-6

             Protection)

             Single-point grounding example [reproduced from Federal Information         4-10

             Processing Standards Publications (FIPS pub) 94]

             Multi-point grounding example [reproduced from Federal Information          4-11

             Processing Standards Publications (FIPS pub) 94]

             UPS distribution panels                                                     4-18

                                                                                    iii


---

              TM 5-693

   CHAPTER 1
INTRODUCTION

1-1. Purpose

The purpose of this publication is to provide guidance for facilities engineers in selecting,
installing, and maintaining an uninterruptible power supply (UPS) system after the decision has
been made to install it. This technical manual (TM) TM 5-693 has been prepared to provide
generic guidance to agencies responsible for the selection, installation, and maintenance of UPS
systems at Command, Control, Communications, Computer, Intelligence, Surveillance, and
Reconnaissance (C4ISR) facilities. Although it is written mainly for C4ISR facilities, which
require a higher level of reliability, it could also be utilized as a reference in similar applications.

1-2. Scope

The process for identifying the need for an UPS system, selecting, installing, and maintaining the
UPS system are covered. Covered are: theory and principles of static and rotary UPS systems,
design and selection of UPS, installation and testing of UPS, maintenance and operation of UPS
systems, principles of static and rotary UPS, UPS system rating and sizing selection,
operations/maintenance, batteries, troubleshooting, harmonic distortions, grounding, checklists,
and acceptance testing.

1-3. References

A complete list of references is contained in appendix A. The design, installation, and
maintenance of UPS systems should follow the latest industry and commercial codes and
standards as detailed in the references.

1-4. Principles and configurations

An UPS system is an alternate or backup source of power with the electric utility company being
the primary source. The UPS provides protection of load against line frequency variations,
elimination of power line noise and voltage transients, voltage regulation, and uninterruptible
power for critical loads during failures of normal utility source. An UPS can be considered a
source of standby power or emergency power depending on the nature of the critical loads. The
amount of power that the UPS must supply also depends on these specific needs. These needs
can include emergency lighting for evacuation, emergency perimeter lighting for security, orderly
shut down of manufacturing or computer operations, continued operation of life support or
critical medical equipment, safe operation of equipment during sags and brownouts, and a
combination of the preceding needs.

  a. Static UPS. A static UPS is a solid-state system relying solely on battery power as an
emergency source. A static UPS consists of a rectifier, inverter, and an energy storage device,
i.e., one or more batteries. The inverter in the static UPS also includes components for power
conditioning. Modern static UPS systems are constructed with ratings ranging from about 220
VA to over 1 MVA. Static UPSs ranging from 220 VA to 1 MVA are constructed without
paralleling internal components. UPS with output higher than 1 MVA are built with some
parallel internal components, which result in decreasing reliability. Figure 1-1 shows a simple

              1-1


---

TM 5-693

static UPS. Design, installation, and maintenance requirements should follow the latest version
of applicable codes and standards from recognized industry and commercial groups.

                     UPS UNIT

NORMAL    RECTIFIER            INVERTER   STATIC                                     MANUAL      LOAD
    AC                                    SWITCH                                     BYPASS
                                                                                     SWITCH
SOURCE

                     BAT TERY

                               ALTERNATE
                               AC SOURCE

                                          Figure 1-1. Simple version of a static UPS

  b. Rotary UPS. A rotary UPS is a system that uses a motor-generator (M-G) set in its design.
Figure 1-2 illustrates a simple rotary UPS. Unlike static units, the basic parts may vary between
manufacturers for rotary units. Rotary units are mainly designed for large applications, 125 kVA
or higher. Some reasons for selecting a rotary UPS over a static UPS are to provide higher
efficiency, superior fault clearing capability, capability of supplying currents for high inrush
loads, and isolation from harmonic distortion generated by non-linear loads in the line. Rotary
UPS bearings must be replaced periodically. Although this might make reliability between the
two types debatable, bearing failure is highly predictable with stringent routine testing. Rotary
units produce more heat than do static units due to their M-G sets. They are more costly for small
capacities but become competitive with static units around 300 kVA. Rotary units provide
complete electrical isolation where the static UPS is limited by the static switch. Extremely high
voltages or rapidly rising voltages can pass through the static switch and damage critical loads.

                               Figure 1-2. Rotary UPS (shown with primary power on)
1-2


---

                                                                                                                     TM 5-693

1-5. Design criteria and selection

The UPS selection process involves several steps as discussed briefly here. These steps are
discussed in further detail in chapter 3.

  a. Determine need. Prior to selecting the UPS it is necessary to determine the need. The
types of loads may determine whether local, state, or federal laws mandate the incorporation of an
UPS. An UPS may be needed for a variety of purposes such as lighting, startup power,
transportation, mechanical utility systems, heating, refrigeration, production, fire protection,
space conditioning, data processing, communication, life support, or signal circuits. Some
facilities need an UPS for more than one purpose. It is important to determine the acceptable
delay between loss of primary power and availability of UPS power, the length of time that
emergency or backup power is required, and the criticality of the load that the UPS must bear.
All of these factors play into the sizing of the UPS and the selection of the type of the UPS.

  b. Determine safety. It must be determined if the safety of the selected UPS is acceptable.
The UPS may have safety issues such as hydrogen accumulation from batteries, or noise pollution
from solid-state equipment or rotating equipment. These issues may be addressed through proper
precautions or may require a selection of a different UPS.

  c. Determine availability. The availability of the selected UPS must be acceptable. The
criticality of the loads will determine the necessary availability of the UPS. The availability of an
UPS may be improved by using different configurations to provide redundancy. It should be
noted that the C4ISR facilities require a reliability level of 99.9999 percent.

  d. Determine maintainability. The selected UPS must be maintainable. Maintenance of the
unit is important in assuring the unit’s availability. If the unit is not properly cared for, the unit
will be more likely to fail. Therefore, it is necessary that the maintenance be performed as
required. If the skills and resources required for the maintenance of the unit are not available, it
may be necessary to select a unit requiring less maintenance.

  e. Determine if affordable. The selected UPS must be affordable. While this is the most
limiting factor in the selection process, cost cannot be identified without knowing the other
parameters. The pricing of the unit consists of the equipment cost as well as the operating and
maintenance costs. Disposal costs of the unit should also be considered for when the unit reaches
the end of its life.

  f. Re-evaluate steps. If these criteria are not met, another UPS system must be selected and
these steps re-evaluated.

1-6. Installation and testing

The installation and testing of the UPS is critical to its proper operation. These items are
discussed in greater detail in chapter 4.

  a. Features. The UPS shall be installed with all necessary features. Features such as alarms,
indicators, control devices, and protective devices are installed to assist in the safe operation of
the unit. Power and control components such as meters, indicating lights, control switches, push
buttons, and potentiometers are typically located in a nearby cabinet. Batteries are typically
installed on battery racks. The design of the racks varies based on the available space and
number of batteries.

                                                                                                                              1-3


---

TM 5-693

  b. Location. The UPS shall be installed on a level surface with sufficient clearance to allow
for ventilation and access to maintenance panels. Static UPSs require environments with a
controlled atmosphere where the temperature, humidity, and dust levels are carefully maintained.
The batteries of the UPS require ventilation of the room to prevent hydrogen buildup. Rotary
UPSs are suitable for placement in industrial environments.

  c. Protection. The UPS power distribution system shall be designed to provide short circuit
protection, isolate branch faults, and isolate critical loads from sources of harmonics, surges, and
spikes. This is achieved using panelboards, circuit breakers, and fuses. The UPS system is
grounded to ensure the safety of the operating personnel. Shielding of the control cables shall be
achieved by running power cables in bonded metal enclosures separately from the control cable’s
enclosures.

  d. Testing and startup. Testing and startup shall be performed to ensure the component’s
operation once energized. Acceptance testing should be performed on all equipment. Testing
records on test forms should be kept for comparison to later routine maintenance tests. The
possible failures of the equipment drawn out from the test results should be discussed and
corrective action implemented. Test equipment used should be in accordance with the
manufacturer’s recommendation.
1-7. Maintenance
Maintenance of the UPS consists of preventive and corrective maintenance. Preventive
maintenance consists of a scheduled list of activities. Performing these activities keeps the UPS
in good working order and helps to prevent failures. Corrective maintenance is performed as a
result of a failure. Corrective maintenance fixes the problem and gets the unit working again.
Maintenance is covered in chapter 5.

1-4


---

                                                                                                                  TM 5-693

                                    CHAPTER 2
PRINCIPLES AND CONFIGURATIONS OF UNINTERRUPTIBLE

                    POWER SUPPLY (UPS) SYSTEMS

2-1. Principles of static UPS systems

The basic static UPS system consists of a rectifier-charger, inverter, static switch, and battery as
shown in figure 2-1. The rectifier receives the normal alternating current (ac) power supply,
provides direct current (dc) power to the inverter, and charges the battery. The inverter converts
the dc power to ac power to supply the intended loads. The dc power will normally be provided
from the rectifier, and from the battery upon failure of the primary ac power source or the
rectifier. The inverter will supply the loads under normal conditions. In the event of the failure
of the inverter, the static switch transfers the load to an alternate ac source.

                                                     UPS UNIT

NORMAL  RECTIFIER            INVERTER   STATIC   MANUAL   LOAD
    AC                                  SW ITCH  BYPASS
                                                 SW ITCH
SOURCE

                   BAT TERY

                             ALTERNATE
                             AC SOURCE

                                           Figure 2-1. Basic static UPS system

  a. Normal operation. During normal operation, the rectifier converts the ac input power to dc
power with regulated voltage. The rectifier output is normally set at the battery float voltage to
charge the battery while supplying dc power to the inverter. The rectifier output voltage is
periodically set at the battery equalize voltage to maintain the battery capacity. The dc filter
(inductor) is provided for smoothing out the rectifier output current to reduce the current ripple
content. The battery acts as a capacitor and in conjunction with the filter, smoothes out the output
voltage and reduces the dc voltage ripple content. The inverter converts the dc power to ac power
with regulated voltage and frequency. An internal oscillator maintains the inverter frequency by
controlling the timing of the silicon controlled rectifier (SCR) firing signals and matches the ac
input frequency. The filters at the output transformer secondary are provided to filter out the
harmonics in the inverter output. Tuned L-C filters are used - when required - to filter out the 5th
and 7th harmonics while a capacitor is adequate for filtering out the higher order harmonics.

       (1) Loss of normal power. Upon loss of ac power supply or upon failure of the rectifier,
the battery maintains the dc supply to the inverter. The battery can maintain the dc supply to the
inverter until the ac supply is restored or to the end of the battery duty cycle. Under this
condition, the inverter continues to supply the connected loads without interruption. This mode
of operation continues until the system is shut down if the battery reaches the discharged state
before the charger output is restored. A system shutdown may be initiated manually or
automatically by a dc undervoltage sensing device.

                                                          2-1


---

TM 5-693

       (2) Restoration of power. Upon restoration of the ac supply after extended outage while
the battery has been discharged, the rectifier output voltage is set at the equalizing voltage to
recharge the battery. This can be done manually or automatically. The charger will also supply
the inverter while recharging the battery. At the end of the battery recharging time, the battery
charger returns to the floating mode and the system returns to normal operation.

       (3) Momentary loss of power. During momentary ac power interruptions or when the ac
supply voltage sags below acceptable limits, the battery maintains the dc supply to the inverter.
Under this condition, the inverter continues to supply the connected loads with regulated power
without interruption.

  b. Bypass mode. The static UPS systems may have three bypass switching arrangements: the
UPS static switch (SS), the UPS static switch circuit breaker (SS-CB), and the maintenance
circuit breaker.

       (1) UPS static switch. When an UPS equipment problem occurs, the load is automatically
transferred by the static switch bypass to an alternate power source to prevent power interruption
to the loads. The static switch is also useful in clearing load faults downstream of the UPS. The
static switch will transfer to the alternate power source on a setting of 110 to 125 percent of rated
load. Without this feature, the inverter would be driven to current limit on a fault. The inverter
would not supply sufficient current to trip the breaker and would continue to feed the fault
causing a potential hazard. The transfer of the fault to the alternate power source by the static
switch allows full short circuit current to pass through, thus tripping the circuit breaker. The
static switch will then transfer back to the UPS for normal operation. Because the circuit cannot
differentiate between an inrush and a fault current, it is common for the initial energization of a
load to cause a temporary transfer to the alternate source power. When the inverter logic drops
below a predetermined value, the bypass SCRs are gated-on by the static switch logic board and
the UPS bypass line will supply the load. Retransfer to the UPS module can occur automatically
when the logic senses that the UPS output problem has been eliminated. The logic system
circuitry maintains the inverter output in synchronization with the UPS bypass power. The
configuration of figure 2-2 does not provide the isolation capability of the figure 2-3 system.
Reverse parallel SCRs can also be used as UPS power interrupters, that is, as an on-off switch to
isolate a failed inverter occurring in a redundant UPS configuration.

       (2) UPS static switch with circuit breaker (SS-CB). A hybrid UPS system uses an
electromechanical switch in the inverter output with the reverse parallel SCRs provided only in
the UPS bypass line. With an UPS output malfunction, the UPS bypass static switch will be
turned on before the inverter output circuit breaker automatically opens. This type of hybrid
switching will need only a short-term static switch current carrying (heat) rating and provides a
normally reliable configuration if there are no problems with the circuit breaker closing in the
static switch's 300 milliseconds (ms) rating. Figure 2-4 shows a SS-CB configuration where
circuit breaker SS-CB closes after the UPS bypass static switch closes. The circuit breaker SS-
CB provides a bypass for the static switch and therefore allows for the use of a short-term static
switch current carrying (heat) rating. To prevent any damage to the static switch the circuit
breaker must be able to close within the static switch's short time rating. There have been
problems even though manufacturers quote a 450,000-hour mean-time-before-failure, so this
system cannot be considered as reliable as a fully rated UPS bypass static switch. Hybrid
switching is used as a method of combining the merits of both a static switch and a circuit
breaker, that is, both speed and economy.

2-2


---

                                                                                                                     TM 5-693

                                       Figure 2-2. SCR static switching transfer
       (3) Maintenance bypass circuit breaker. A bypass circuit breaker is provided to bypass the
complete UPS system when maintenance of the UPS system is required. The UPS bypass line
provides power continuity during UPS module malfunction periods. If the malfunction is such as
to require UPS maintenance, then the load must be shifted to a maintenance bypass line, as shown
on figure 2-5. An explanation as to why such a transfer is needed and the how such a transfer is
configured is basic to comprehending UPS maintenance procedures.

            (a) Purpose of maintenance bypass switch. It is unsafe to work on an energized UPS
system. The complete system must be isolated from ac inputs, ac outputs, and the dc link
whenever maintenance requires that the cabinet doors be opened and/or protective panels be
removed. There are lethal voltages present in UPS cabinetry, resulting from the ac power applied
to the converter or the dc power available from the battery. When energized, these circuits
provide high voltage. Any portions of the system providing a redundant path, such as more than
one UPS module or the static bypass, are tied together by the system logic so partial system
shutdown for maintenance is not acceptable. Shutting off the battery for maintenance and
running the UPS portion as a power conditioner should not be attempted since this also impacts
on the system logic. After shutdown, all UPS systems should be load tested off-line.
Approximately 85 percent of system failures occur after maintenance shutdowns which were not

                                                                                                                         2-3


---

TM 5-693

                               Figure 2-3. SCR switching transfer with UPS isolation
off-line load tested to assure proper operation. In order to shut down the complete UPS system,
the load must be transferred to a line which is isolated electrically from the power and logic
circuitry of the entire UPS installation.

            (b) Operation of maintenance bypass switch. Close the UPS static bypass, which
automatically opens the UPS module output circuit breaker (UPS-CB), allowing closing of the
maintenance bypass circuit breaker (MBP-CB) before opening the UPS output circuit breaker
(OUTPUT-CB). A closed transition has been made to an alternate supply for input to the critical
load with no interruption. Now the UPS system as a whole can be de-energized for maintenance
and off-line load testing. This is the basis for the interlocking requirements shown on figure 2-5.

  c. Test mode. Off-line load testing of UPS systems after installation and scheduled
maintenance is always necessary. A permanent load test tap or a circuit breaker and interlocking
circuitry may be provided as part of the installation. Otherwise a temporary connection must be
provided.

  d. Characteristics and limitations. To avoid drawing heavy inrush currents from the power
source upon initial energization, the battery charger is designed to assume the load gradually.
Normally, the start-up current is limited to a maximum of 25 percent of the full load current. The

2-4


---

                                                                                                                     TM 5-693

                              Figure 2-4. Static switching transfer with circuit breaker
current is then automatically increased gradually to the full load value in 15 to 30 seconds; this
time is termed the "walk-in" time. For this reason all loads cannot be switched simultaneously if
the battery has been fully discharged. Upon sudden application or removal of a load, the
inverter's output voltage will drop or rise beyond the steady-state level. The voltage then returns
to the steady-state condition after some short time which depends on the inverter's voltage control
circuit design. These voltage variations are termed "transient voltage response" and the time
required to return to steady-state conditions is termed the "recovery time.” Generally, due to the
absence of feedback regulating circuits in inverters with a ferroresonant transformer, the transient
response is slower than that of inverters with pulse width or pulse width modulation (PWM)
control techniques. SCRs have a limited overload capability. Also, heavy load currents may
cause commutation failures. Therefore, the rectifier and inverter are designed to be self protected
from overloads. The self protection circuit reduces the output voltage at currents exceeding the
full load current. Normally, the inverter is designed to reduce the output voltage to zero at
overloads of 115 to 135 percent rated load. The value of overcurrent at which the voltage is
reduced to zero is termed "current limit.” The inverter may reach the current limit condition
when energizing a load with a high inrush current or during a load branch circuit fault.

  e. Basic static UPS system without a dedicated battery. The basic system discussed above
utilizes a dedicated battery as a backup source. The UPS system is provided with a controlled
rectifier to supply the inverter and float/equalize charge the battery. In other applications, a large

                                                                                                                         2-5


---

TM 5-693

battery bank may be available for supplying the UPS system as well as other loads. In such
applications, a separate battery charger is provided to supply the connected load and
float/equalize the battery. In this case, the UPS system is provided with a rectifier that only
supplies the inverter and is isolated from the battery and other loads by a blocking diode. The
blocking diode allows current to flow from the battery to the inverter while blocking the flow of
current from the rectifier to the battery. Upon failure of the ac input power, the battery supplies
the inverter as discussed above.

                                    Figure 2-5. UPS maintenance bypass switching
  f. Principles of rectifiers and inverters. UPS systems use power semiconductors in the
construction of the rectifiers, inverters, and static switches. These solid-state devices control the
direction of power flow and switch on and off very rapidly allowing for the conversion of power
from ac to dc and dc to ac.

       (1) Power semiconductor characteristics. A power semiconductor is an electronic device
consisting of two layers of silicon wafer with different impurities forming a junction made by
diffusion. The joining of these two wafers provides control of the current flow. Referring to
figure 2-6, the power semiconductor permits the current to flow in one direction from the anode
A to the cathode K, whenever the anode voltage is positive relative to the cathode. When the
anode voltage is negative relative to the cathode, the power diode blocks the flow of current from
the cathode to the anode. The power semiconductors may be either SCR or transistors. The types
of transistors are bipolar transistors, field effect transistors (FET), and insulated gate bipolar
transistors (IGBT). The devices most commonly used are the SCRs and the IGBTs. The IGBTs
are relatively new and have been gaining in popularity. The IGBTs are significantly more
efficient and easier to control than the other power semiconductors. The use of IGBTs has
allowed for static UPS as large as 750 kVA without paralleling units.

       (2) Single-phase SCR characteristics. An SCR allows for forward flow of current through
the device similar to a diode. The SCR differs from a diode in that the SCR will not conduct until
a current pulse is received at the gate. Once the SCR is conducting, it will only turn off with the

2-6


---

                                                                                                                     TM 5-693

                               Figure 2-6. Half-wave diode rectifier with resistive load
current falling to zero or through a reverse current being applied. Referring to figure 2-7, the
anode voltage is positive relative to the cathode between wt = o and wt = α; the SCR begins
conducting when a firing pulse is applied at wt = α. Here, α is called the firing angle. Also, the
SCR blocks at wt > π when the anode voltage becomes negative relative to the cathode. The SCR
does not conduct again until a firing pulse is reapplied at wt = 2π + α. While turning on the SCR
is very efficient, the SCRs require a commutation circuit to turn it off. It is necessary to be able
to turn off the device for use in the inverter to generate the ac wave. The turn-off time is slow in
comparison to the transistors which are not latching devices. The other drawbacks to the
commutation circuit are that it adds more equipment to the circuit, adds audible noise to the unit,
and consumes power.

                               Figure 2-7. Half-wave SCR rectifier with resistive load
       (3) Bipolar transistors. Bipolar transistors permit current to flow through the circuit when
current is applied to the base. The flow of the power through the device is proportional to the
current applied to the base. Unlike SCRs, transistors are not latching. Upon removing the current
from the base, the circuit will be turned off. This allows for much quicker switching time than
the SCRs. However, bipolar transistors experience high saturation losses during power
conduction which requires drive circuits to minimize switching losses.
       (4) FET. FETs are turned on and off by applying voltage to the gate. This is more
efficient than applying current to the base as done with the bipolar transistors. The FETs
experience saturation losses and require drive circuits to minimize the switching losses.

                                                                                                                         2-7


---

TM 5-693

Moreover, the high resistance characteristics of the power conducting portion make this device
inefficient and undesirable for large applications.

       (5) IGBT. The IGBT combines the desirable characteristics of the bipolar transistor and
the FET. Voltage is applied to the base to turn the device on and off and the collector/emitter has
low resistance. IGBTs have a greater tolerance to temperature fluctuations than the FETs. The
IGBTs have the drawback of saturation losses and switching losses like all of the other
transistors. These must be taken into consideration in the designing of the UPS. Overall, the
IGBT is more efficient and easier to control than the other power semiconductors.

  g. Rectification. Rectification is the conversion of ac power to dc power. Rectification is
accomplished by using unidirectional devices such as SCRs or IGBTs. Rectifiers can be built to
convert single-phase or three-phase ac power to controlled or uncontrolled dc power. In a
controlled rectifier, the output dc voltage can be continuously maintained at any desired level
whereas in an uncontrolled rectifier the output dc voltage (at no load) is a fixed ratio of the input
ac voltage. Moreover, the output dc voltage of an uncontrolled rectifier varies with the load level
due to voltage drops in the various circuit elements. Generally, single-phase rectifiers may be
used in ratings up to 5 kilowatt (kW) whereas three-phase rectifiers are used in higher ratings.
When controlled dc voltage is required, SCRs are normally used.

       (1) Single-phase uncontrolled rectifiers. The two most common configurations of single-
phase uncontrolled rectifiers are the center-tap full wave rectifier shown in figure 2-8 and the
single-phase bridge rectifier shown in figure 2-9. In the center-tap configuration, each diode
conducts every half cycle when the anode voltage is positive relative to the cathode. In the bridge
configuration a pair of diodes conducts every half cycle when their anode voltage is positive
relative to the cathode. Comparison of the output voltage (Ed) and current wave shapes of the
two configurations indicates that they are identical. However, a major difference between the two
configurations is that for the same kW output, the center-tap configuration requires a transformer
with a higher kVA than the bridge configuration and is more costly. For this and other reasons,
the center-tap configuration is used mainly in ratings of less than one kW. Examining the output
voltage wave shape for the two configurations indicates that it contains two pulses every cycle.
This causes the output voltage, which is the average of these two pulses, to have a high ripple
content. Also, comparison of the output current (Id) wave shape for resistive and inductive loads
indicates that with an inductive load, the output current is essentially constant throughout the
cycle. Therefore, connecting a large inductor in series with the rectifier output smoothes the
output current and minimizes the current ripples.

       (2) Three-phase uncontrolled rectifiers. There are numerous possible configurations of
three-phase rectifiers. However, the basic building blocks of these configurations are the three-
phase single-way and the three-phase bridge rectifier configurations shown in figures 2-10 and 2-
11 respectively. Comparison of the output voltage and output current wave shapes indicates that
the bridge rectifier output wave shape contains six pulses while the wave shape for the single-way
rectifier contains three pulses. This makes the ripple content of the bridge rectifier output less
than that of the single-way rectifier. Another important difference is that the required transformer
kVA in the single-way configuration is approximately 1.5 times that in the bridge configuration
for the same kW output due to the low power factor of the single-way configuration. Normally
three-phase rectifiers are used in ratings higher than 5 kW although it may also be used in lower ratings.
The bridge rectifier configuration is commonly used in high power applications while the single-way
configuration is mostly used in lower ratings. Generally, the selection of one configuration or another is
up to the equipment designer and is based on cost considerations.

2-8


---

                                                                                                                     TM 5-693

                               Figure 2-8. Center-tap full-wave uncontrolled rectifier
       (3) Controlled rectifiers. In applications where a continuously adjustable dc voltage is
desired, controlled rectifiers are used. Controlled rectifiers like the uncontrolled rectifiers can be
single-phase or three-phase. The controlled rectifier configurations are identical to the
uncontrolled rectifiers, however, in order to control the output dc voltage, SCRs are used in place
of the power diodes. The output dc voltage can be controlled at any desired level by changing the
firing angle α as discussed in paragraph 2-1f(2). Control by changing the firing angle α is termed
“phase control." The voltage is controlled by a feedback loop which senses the output voltage
and adjusts the SCRs firing angles to maintain the output at the desired level. The configurations
of single-phase and three-phase controlled bridge rectifiers and their wave forms are shown in
figures 2-12 and 2-13 respectively. The output dc voltage of rectifiers with resistive-inductive or
non-linear loads and the effect of the firing angle α can be determined by circuit analysis
techniques for each specific load. The effect of the firing angle α on the magnitude of the output
dc voltage is as follows.

            (a) Single-phase bridge rectifier with a resistive load. The following equation models
the voltage output of the single-phase bridge rectifier with a resistive load.

                                     Edo (α ) = Edo (1 + cosα )
                                                             2

                                                                                                                         2-9


---

TM 5-693                                                         ID3
                                  ID1                                                 E I d d R L

ES  ID2                                                          ID4

                                       ID1, ID4                                     ID1, ID4
                                                       ID2, ID3  ID2, ID3

                                  Figure 2-9. Full-wave bridge uncontrolled rectifier
            (b) Single-phase bridge rectifier with an inductive load. The following equation
models the voltage output of the single-phase bridge rectifier with an inductive load.

                          Edo (α ) = Edo cosα

2-10


---

                                                                                                                     TM 5-693

                             Figure 2-10. Three-phase uncontrolled single-way rectifier
            (c) Three-phase bridge rectifier with a resistive load. The following equation models
the voltage output of the three-phase bridge rectifier with a resistive load.

                           Edo (α ) = Edo 1 − sin (α − Π )
                                                            6

                                                                                                                       2-11


---

TM 5-693

                               Figure 2-11. Three-phase uncontrolled bridge rectifier
            (d) Three-phase bridge rectifier with an inductive load. The following equation
models the voltage output of the three-phase bridge rectifier with an inductive load.

                          Edo (α ) = Edo cosα

2-12


---

                  TM 5-693

where:  Edo =     average dc voltage at no load without phase control (neglecting the
        Edo(α) =  voltage drop in the circuit elements)
                  average dc voltage at no load with phase control at firing angle α
                  (neglecting the voltage drop in the circuit elements).

                  Figure 2-12. Single-phase controlled bridge rectifier
                                                                                                        2-13


---

TM 5-693

                                 Figure 2-13. Three-phase controlled bridge rectifier
  h. Inversion. Inversion is the conversion of dc power to ac power. Inversion can be
accomplished using SCRs or IGBTs. In high power applications, IGBTs have been used.
Inverters for static UPS systems can be single-phase or three-phase. Single-phase inverters are
used in ratings up to approximately 75 kVA; at higher ratings three-phase inverters are used.

       (1) Inverter principles. The basic elements of a single-phase inverter are shown in figure
2-14. When SCRs 1 and 4 are turned on while SCRs 2 and 3 are off, a dc voltage appears across
the load with the polarity shown in figure 2-14a. After some time interval, if SCRs 1 and 4 are
turned off and SCRs 2 and 3 are turned on, a dc voltage appears across the load with opposite
polarity as shown in figure 2-14b. If SCRs 2 and 3 are allowed to conduct for the same time
interval as SCRs 1 and 4 and then turned off while SCRs 1 and 4 are turned on and the process is

2-14


---

                                                                                                                     TM 5-693

                                              Figure 2-14. Simple single-phase inverter
repeated, an alternating voltage will appear across the load. The wave form of this alternating
voltage is as shown in figure 2-14c. Two points must be taken into consideration to make the
simple circuit in figure 2-14 of practical importance. As discussed before, once a SCR is turned
on it remains conducting until the current drops to nearly zero. In the circuit shown in figure 2-
14, once the SCR is turned on, load current flows with magnitude larger than zero. Therefore,
some external means are required to cause the current to drop to near zero in order to turn off the
SCR. Such means is called a commutating circuit. Generally, all inverters with SCRs require
commutation means and normally charged capacitors are used to effect the commutation process.
However, when gate turn off (GTO) SCRs or power transistors are used, no commutation circuits
are required. GTO SCRs and power transistors can be turned off by gate pulses supplied by low
power gating circuits. Commutation circuits are relatively complex and their principles of
operation are beyond the scope of this manual. The second point is that in the circuit shown, the
load is directly connected to the dc source through the SCRs. This subjects the load to transients
generated within the dc system. For this reason, the load is normally isolated from the dc source
through the use of an output transformer. Also, the inverter output wave shape is a square wave.
This wave shape is not suitable for supplying power sensitive equipment. Therefore, some means
are required to condition the inverter output to a sinusoidal waveform.

       (2) Inverter voltage control. The common methods of inverter output voltage control are
pulse width control, PWM, and use of a ferroresonant transformer. Any of these methods may be
used for output voltage control. In some designs a combination of pulse width control and
modulation is used. However, a ferroresonant transformer is never used in combination with
either of the other two methods. The pulse width control technique has become less common

                                                                                                                       2-15


---

TM 5-693
than the PWM technique and the use of ferroresonant transformers. Also, some manufacturers
advocate the use of PWM while others favor the use of ferroresonant transformers. Although
each method may have some advantages over the others, the voltage control method is normally
not specified when specifying UPS systems. Either type may be used provided it meets the
performance requirements.

            (a) Pulse width control. To illustrate this technique, the circuit in figure 2-14 is
redrawn in figure 2-15. Referring to this figure, when each of the two SCR pairs (1, 4 and 2, 3) is
gated for a time interval equal to a half cycle without the two pairs conducting simultaneously,
the output voltage waveform is as in figure 2-15b. If the gating of SCR pair 2, 3 is retarded by a

                               Figure 2-15. Voltage control using pulse width control
quarter of a cycle, the output voltage waveform is as in figure 2-15c. Therefore, the inverter
output voltage can be continuously adjusted by retarding the firing signal of one pair of SCRs
with respect to the other. The magnitude of the fundamental component of the output voltage
depends on the pulse width and is higher for a wider pulse. The maximum output voltage is
2-16


---

                                                                                                                     TM 5-693

obtained with no retard; zero voltage is obtained when the firing signal is retarded by a half cycle.
The voltage control is accomplished by a feedback control loop which senses the output voltage
and adjusts the SCRs' firing angles to increase or reduce the output voltage level. With the pulse
width control technique, the output voltage harmonic content is high and a harmonic filtering
means is required.

            (b) PWM. In this technique, the inverter SCR pairs are switched on and off many
times every half cycle to provide a train of pulses of constant amplitude and different widths. The
output voltage is synthesized from this train of pulses as shown in figure 2-16. The output
voltage level can be controlled by varying the width of the pulses. By this technique the output
voltage wave shape can be made to closely approximate a sine wave. Also, it is feasible to
eliminate all harmonics by the use of this technique. This eliminates the use of output filters.
Inverters using this technique have lower impedance and faster transient response. The control is
accomplished by feedback control as in the pulse width control technique.

                                     Figure 2-16. Pulse width modulation (PWM)
            (c) Use of a ferroresonant transformer. A ferroresonant transformer connected across
the inverter's output can be used to regulate the output voltage and reduce its harmonic content.
The ferroresonant transformer is basically a two-winding transformer with an additional small
secondary compensating winding and a series low pass filter connected across part of the main
secondary winding as shown in figure 2-17. The filter presents a low impedance to the lower
order harmonics and reduces their amplitude in the output to a low acceptable value. The
compensating winding voltage is added to the secondary output voltage 180° out-of-phase thus
maintaining the output voltage within a narrow regulation band. However, with the use of a
ferroresonant transformer, the output voltage is not continuously adjustable as in the previous
techniques.
       (3) Three-phase inverters. Three-phase inverters are commonly made up of three single-
phase inverters connected to the same dc supply, as shown in figure 2-18. The secondaries of the
three single-phase inverter output transformers are connected in wye configuration. To generate a
three-phase output, the firing signals for phase B inverter SCRs are delayed 120° from those of
phase A inverter. Similarly the firing signals for phase C inverter SCRs are delayed 120° from

                                                                                                                       2-17


---

TM 5-693

                                        Figure 2 -17. Ferroresonant transformer
those of phase B inverter. The resulting phase-to-neutral voltages for 180° pulses and the line-to-
line secondary voltages are shown in figure 2-18, where:

            EA-B = EA-N - EB-N
            EB-C = EB-N - EC-N
            EC-A = EC-N - EA-N
In this case as with the single-phase inverter, the output wave shape is a square wave and means
for conditioning the output to a sinusoidal waveform is required. The three-phase inverter output
voltage control can be accomplished by the same techniques used for single-phase inverters. However,
the use of ferroresonant transformers is not feasible in many three-phase applications. This is due to the
fact that a slight load current unbalance can cause substantial phase shifts in the ferroresonant
transformers output voltages. With substantial voltage phase shift, the three line to neutral voltages may
have the same magnitude but the line-to-line voltages may be extremely unbalanced. However, PWM
technique can also be used as in the case of single-phase inverters.
  i. Static transfer switch. A static transfer switch, like an electromechanical transfer switch, is
used to transfer loads from one power source to another, manually or automatically. However,
unlike an electromechanical transfer switch, the static transfer switch total transfer time is in the
order of one fourth of a cycle which will provide power to the loads without interruption.
       (1) Design. As shown in figure 2-19, a single-phase static transfer switch consists of two
pairs of SCRs. Each pair is connected in antiparallel arrangement, i.e., the anode of one SCR is
connected to the cathode of the other. By this arrangement, each SCR in the pair can be made to
conduct every other half cycle. One pair of SCRs is connected between the load and each of the
two sources. The logic circuit applies firing signals to either pair of SCRs.
            (a) Operation. Applying a firing signal to source No. 1 SCRs causes them to conduct
and power flows from source No. 1 through the SCRs to the load. To transfer the load to source

2-18


---

                                                                                                                     TM 5-693

                                            Figure 2-18. Three-phase inverter
No. 2, the firing signals are transferred from source No. 1 SCRs to source No. 2 SCRs. This
causes source No. 2 SCRs to conduct and source No. 1 SCRs to block when the SCR anode
voltage reaches zero. By causing source No. 2 SCRs to conduct and source No. 1 SCRs to block,
power flows from source No. 2 through the SCRs to the load during the transfer, the two sources
are paralleled momentarily until source No. 1 SCRs reach the blocking state and the transfer is in
a "make-before-break" mode.

            (b) Initiation. The transfer process can be initiated manually or automatically through
the sensing and logic circuit. This circuit senses the voltage and frequency of both sources and
checks their synchronism. When the connected source voltage and/or frequency deviate from the
required level, the sensing and logic circuit initiates transfer to the other source provided its
voltage and frequency are within allowable tolerances. The transfer is normally initiated after a
short time delay to avoid unnecessary transfers during transients.

                                                                                                                       2-19


---

TM 5-693

                                    Figure 2-19. Single-phase static transfer switch
            (c) Three-phase static switch. A three-phase static transfer switch consists of three
single-phase switches. However, only one common sensing and logic circuit is used to monitor
the frequency and voltages of the three phases. A voltage deviation in any phase initiates the
transfer. Otherwise, operation is the same as the single-phase switch operation.
       (2) Static transfer switches with short time rating. The static transfer switch discussed in
paragraph 2-1i. above is capable of transferring and carrying the full load current continuously.
In some designs, particularly larger ratings, a static transfer switch with short time rating is used
in conjunction with a circuit breaker connected in parallel at the bypass source. In this
arrangement the static transfer switch is not rated to carry the load current continuously; it can
carry the full load current for a duration of less than one second. The static switch is used to affect
fast transfer and to carry the load current for the duration required to close the motor operated
circuit breaker which is in the order of several cycles. Once the circuit breaker closes, it carries
the load current and relieves the static transfer switch. This configuration is comparable to the
fully rated static transfer switch. However, it has a lower reliability due to the higher failure rate
of motor operated circuit breakers. It is used mainly for economic reasons in lower cost systems.
  j. Batteries. A battery is used in a static UPS system to provide reliable emergency dc power
instantaneously to the inverter when the normal power fails or degrades. Of the many available
battery types, the following two basic types are generally used in static UPS systems, namely, the
lead-acid and the nickel-cadmium (ni-cad) batteries.
       (1) Lead-acid batteries. A lead-acid battery cell consists basically of a sponge lead
negative electrode, a lead dioxide positive electrode, and a sulfuric acid solution as an electrolyte.
As the cell discharges, the active materials of both positive and negative electrodes are converted
to lead sulphate and the electrolyte produces water. On charge, the reverse action takes place. At
the end of the charging process, water electrolysis occurs producing hydrogen at the negative
electrode and oxygen at the positive electrode.

2-20


---

                                                                                                                     TM 5-693

            (a) Lead-acid design. The most common design of lead-acid batteries is the lead-
calcium cell construction where the active material for each electrode is prepared as a paste
spread onto a lead-calcium alloy grid. The grid provides the electrical conductivity and structure
to hold the active materials. The resultant plates are soldered to connecting straps to form
positive and negative groups which are interleaved. Separators are placed between the plates and
the assembly is placed in a container or jar. These batteries can survive more short duration,
shallow cycles than long duration, deep discharge cycles.

            (b) Voltage. The nominal voltage of a lead-acid cell is 2 volts while the open circuit
voltage is approximately 2.05 volts. A commonly used end or discharged voltage is 1.75 volts.
However, lower end voltages are also possible. The electrolyte specific gravity with the cell fully
charged can range from a nominal 1.210 to 1.300 at a temperature of 25°C (77°F).

            (c) Rate design. The batteries may be of the high rate, medium rate, or low rate
design. The high rate batteries are designed to deliver a large amount of current over a short
amount of time of approximately 15 minutes. This is achieved by designing the batteries with
thin plates. This design is most common for UPS applications. The medium rate batteries are
designed for general use. They deliver a medium amount of current over a medium amount of
time of approximately 1 to 3 hours. The design consists of medium width plates. This design is
most common with switchgear and control applications. The low rate batteries are designed for
delivery of power over a long amount of time of approximately 8 hours. The battery design
consists of thicker plates. This design is most common for applications such as emergency
lighting and telecommunications.

            (d) Vented (flooded) lead-acid battery. Vented (flooded) lead-acid cells are
constructed with the liquid electrolyte completely covering the closely spaced plates. The
electrolyte maintains uniform contact with the plates. These batteries require regular
maintenance of checking the specific gravity of the electrolyte and adding water. These batteries
are well suited for industrial applications due to the long lifetime (20 years) and high reliability
with the proper maintenance. Without the proper maintenance, the lifetime of the battery could
be greatly reduced. These batteries are approximately half the cost of ni-cad batteries. These are
the most commonly used batteries for industrial application UPSs.

            (e) Valve regulated lead-acid (VRLA) batteries. The VRLA batteries are sealed with a
valve allowing venting on excessive internal pressure. These cells provide a means for
recombination of the internally generated oxygen and suppression of hydrogen gas evolution to
reduce the need for adding water. This design does not require the maintenance of checking the
specific gravity and adding electrolyte as does the flooded lead-acid batteries. These batteries
have a lifetime of approximately 5 to 6 years. This is substantially shorter than the 20 year
lifetime of the flooded lead-acid and the ni-cad designs. These batteries would need to replaced 3
to 4 times to provide the same service of the flooded lead-acid and ni-cad designs. These units
sometimes experience failures called “sudden death failures” where deposits form on the plates
causing a short. This type of failure is difficult to detect and makes this battery less reliable than
the flooded lead-acid design and the ni-cad design. The VRLA batteries cost approximately half
of the price of the flooded lead-acid batteries and one fourth of the price of the ni-cad batteries.
These units are well suited for UPS systems providing back up to computer systems because of
their low maintenance, low cost, and low emissions. For industrial applications requiring greater
reliability and longer life the flooded lead-acid and ni-cad designs are preferred.

       (2) Ni-cad batteries. Stationary ni-cad batteries designed for emergency power
applications are being used in static UPS systems. These batteries have a long lifetime of 25

                                                                                                                       2-21


---

TM 5-693

years. However, because of their initial cost their use is not as common as the flooded lead-acid
type.

            (a) Ni-cad design. The ni-cad battery cell consists basically of a nickel hydroxide
positive electrode, a cadmium hydroxide negative electrode, and a potassium hydroxide solution
as an electrolyte. As the cell discharges, the nickel oxide of the negative electrode is changed to a
different form of oxide and the nickel of the positive electrode is oxidized. On charge the reverse
action takes place. Also, hydrogen and oxygen are evolved by the positive and negative
electrodes, respectively, as the cell reaches full charge. However there is little or no change in the
electrolyte's specific gravity.

            (b) Ni-cad voltage. The nominal voltage of a ni-cad cell is 1.2 volts while the open
circuit voltage is 1.4 volts. The electrolyte specific gravity is approximately 1.180 at a
temperature of 25°C (77°F).

            (c) Ni-cad rate design. Ni-cad batteries are also available in one of three designs of
high, medium, or low rate power delivery. The high rate batteries are the most commonly used in
the application of UPS systems.

            (d) Advantages. These batteries are resistant to mechanical and electrical abuse. They
operate well over a wide temperature range of –20°C to 50°C. Also, they can tolerate a complete
discharge with little damage to the capacity of the battery.

       (3) Lead-acid vs. ni-cad batteries. Lead-acid batteries are about 50 percent less expensive
than an equivalent ni-cad battery; the ni-cad batteries exhibit a longer life and a more rugged
construction. Also the ni-cad battery requires less maintenance than a lead-calcium battery.
However, a ni-cad battery requires approximately 53 percent more cells than a lead-acid battery
at the same voltage. Lead-acid batteries are more susceptible to high temperature than ni-cad
batteries. The life of a lead-acid battery is reduced by 50 percent for every 15°F increase in
electrolyte temperature while a ni-cad battery loses approximately 15 percent of its life. It should
also be noted that lead-acid batteries release more hydrogen during recharging than ni-cad
batteries.

  k. Battery charging. During initial operation, the battery requires charging. During normal
operation, local chemical reactions within the cell plates cause losses that reduce the battery
capacity if not replenished. Also, these local chemical reactions within the different cells occur at
varying rates. In lead-acid batteries these local reactions over long periods of time cause unequal
state-of-charge at the different cells. In addition, it is required to recharge the battery following a
discharge. Therefore, the battery charger should provide the initial charge, replenish the local
losses to maintain the battery capacity, equalize the individual (lead-acid) cells state-of-charge,
and recharge the battery following discharge. In stationary applications such as static UPS
systems, the battery is continually connected to the charger and the load and the battery is float
charged. During float charging the battery charger maintains a constant dc voltage that feeds
enough current through the battery cells (while supplying the continuous load) to replenish local
losses and to replace discharge losses taken by load pulses exceeding the charger's current rating.
Periodically the charger voltage is set at a level 10 percent higher than the floating voltage to
restore equal state-of-charge at the individual (lead-acid) cells. This mode of charging is called
“equalizing charge” and the charger voltage level during this mode is the equalizing voltage.
Following the battery discharge, the charger is set at the equalizing voltage to recharge the
battery. The charger is set at this higher voltage to drive a higher charging current to recharge the
battery in a reasonably short time and to restore it to the fully charged state. Although a periodic

2-22


---

                                                                                             TM 5-693

equalizing charge is not required for equalizing ni-cad cells, a charger with float/equalize mode is
required. At the floating voltage level, the ni-cad cell cannot be charged over 85 percent of its
full capacity. Therefore, the equalizing voltage level is required to fully recharge the cell after
successive discharges.

  l. Service life influences. Service life as reported by battery manufacturers is greatly
influenced by temperature considerations. Battery manufacturers are finding that the type and
number of discharge cycles can reduce life expectancy when installed for the high-current, short
period, full discharges of UPS applications. Characteristics of expected life and full discharge
capabilities of various types of UPS batteries are given in table 2-1. An explanation of the
relationship of battery life to battery capacity, of the basis for battery sizing, and of the effects of
battery cycling is considered necessary to impress on maintenance personnel why continual
maintenance, data reporting is so important in fulfilling warranty policy requirements. Operating
characteristics of the overall system such as charging/discharging considerations, ripple current
contribution, and memory effect also can lead to a diminishment in expected battery performance.

Table 2-1. Characteristics of UPS battery types

                             Battery Type                          Typical       Typical     Approximate
Lead-acid antimony, flooded electrolyte                          Warranty       Expected       Number of
Lead-acid calcium, flooded electrolyte                                                             Full
Lead-acid/calcium gelled electrolyte, valve-regulated               Period          Life      Discharges
Lead-acid/calcium suspended electrolyte, valve-regulated        15 years       15 years
Lead-acid special alloy suspended electrolyte, valve-regulated  20 years       20 years      1,000-12,000
Lead-acid/pure starved electrolyte, valve-regulated             2 years        5 years       100
Ni-cad, flooded electrolyte                                     1 - 10 years   5 - 12 years  100
                                                                14 years       14 years      100-200
                                                                1 year         5 - 20 years  200-300
                                                                20 - 25 years  25 years      150
                                                                                             1,000-1,200

       (1) Voltage tapping. Sometimes the UPS system will require one dc voltage level while
electrical operation of circuit breakers will require another dc voltage level. Tapping off of the
higher-voltage battery is not permitted. Unequal loads on the battery will reduce the battery's life
since it causes one portion of the battery to be undercharged while the other portion is
overcharged. Battery and UPS manufacturers both often indicate that such practices invalidate
their warranties.

       (2) Cycling effects. A cycle service is defined as a battery discharge followed by a
complete recharge. A deep or full cycle discharge/recharge consists of the removal and
replacement of 80 percent or more of the cell's design capacity. Cycling itself is the repeated
charge/discharge actions of the battery. A momentary loss of power can transfer the UPS to the
battery system and impose a discharge on the battery for the time period needed by the UPS to
determine whether the ac power input has returned to acceptability. As we see an increase in
non-linear loads, we may expect to see more frequent cycling. As indicated in table 2-1, the
ability of flooded lead-acid batteries utilizing a lead-antimony alloy to provide the greatest
number of full discharges. Ni-cad batteries have a good cycle life, but their increased cost does
not encourage their use in large installations. Valve-regulated batteries have low-cycle
capabilities because each recharge means a possibility of some gassing, resulting in the ultimate
failure of the cell when it eventually dries out.

                                                                                             2-23


---

TM 5-693

       (3) Charging/discharging considerations. A battery cannot function without a charger to
provide its original and replacement energy. A well designed charger will act to charge a
discharged battery by maintaining the correct balance between overcharging and undercharging
so as not to damage the battery. Additionally, the charger must assure that battery discharging is
limited to the point where the cells approach exhaustion or where the voltage falls below a useful
level (usually about 80 percent of the battery's rated capacity). Overcharging results in increased
water use, and over discharging tends to raise the temperature, which may cause permanent
damage if done frequently.

            (a) Current flow. Batteries are connected to the charger so that the two voltages
oppose each other, positive of battery to positive of charger and negative to negative. Battery
current flow is the result of the difference between the battery and the charger voltages and the
battery's extremely low opposing resistance. The voltage of the battery rises during charging,
further opposing current flow. Chargers are designed to limit starting charging currents to values
that keep equipment within a reasonable size and cost. They must also maintain a sufficiently
high current throughout charging so that at least 95 percent of the complete storage capacity is
replaced within an acceptable time period. This recharge time may range from 5 to 24 times the
reserve period (for a 15 minute reserve period with a 10 times recharge capability the recharge
period would be 2.5 hours).

            (b) Voltage action. Providing the precise amount of charge on each and every cell for
each and every recharge is impracticable for a continuously floating battery operation. The float-
voltage point should just overcome the battery's self-discharge rate and cause the least amount of
corrosion and gassing. Ambient temperature differences will affect the charging ability of the
selected float-voltage level. Overcharge, undercharge, and float voltage levels differ, depending
upon the type of cell used.

            (c) Lead-acid cells. The usual recommended float voltage for UPS applications is 2.20
to 2.30 volts per cell depending upon the electrolyte's specific gravity. The excess energy of
higher float voltages results in loss of water, cell gassing, accelerated corrosion, and shorter cell
life. To eliminate such actions, the charge is stopped slightly short of a fully-charged condition
on daily or frequent discharges. However, permissible cell manufacturing tolerances and ambient
temperature effects will cause individual cell-charge variations. Sulphation will take place and
not be reconverted upon recharge, since the charge is insufficient to draw all the acid from the
plates. The sulphate may start to crystallize and be shed from the plate. To prevent this, an
"equalizing" charge is given for a selected time period to provide a complete recharge on all cells.
However, excessive equalizing charges will have an adverse effect on battery life. Automatic
equalizing after a discharge may require less maintenance time but may affect battery life.
Equalizing charges on a periodic basis are not recommended but should follow the manufacturer's
guidelines. Equalizing charging should be considered a corrective action rather than routine
maintenance. Periodic equalizing charges can be considered as treating a possible problem before
determining that there is a problem.

            (d) Ni-cad cells. The usual recommended float voltage for UPS applications is 1.38 to
1.47 volts per cell depending upon the manufacturer's recommendation. Overcharge, as such,
may cause no harm to the battery although there will be water loss. The current rate used for
charging, though, could produce a damaging heating effect during any appreciable overcharge.
Equalizing is not as important for this type of battery, but may be recommended to assist in
electrolyte mixing after addition of water.

2-24


---

                                                                                                                     TM 5-693

       (4) Ripple currents. UPS applications can place unusual load conditions on a battery, and
one condition that increases the rate of battery breakdown is ripple current. Ripple current is
caused by the ripple voltage of the battery charger output and by the pulsating current
requirements of the inverter. The UPS battery design strives for excellent short-term, high-rate,
current characteristics and this demands the lowest possible internal cell resistance. This low
resistance can serve as a better short circuit path for the ripple voltages coming out of the rectifier
stage of the UPS than can the filter capacitors in the output rectifier. Also, the inverter stage of
the UPS demands large instantaneous dc currents as it builds ac power from the parallel
rectifier/battery combination. If the UPS is located some distance from the commercial ac power
source, the short-term instantaneous currents must then come from the battery. These factors can
result in a relatively high ac component in the UPS battery. The relative detrimental effects of
ripple current on the battery are mainly a function of the design of the UPS, the comparative size
of the battery as compared to the UPS rating, and the battery type. Ripple current tends to heat
the batteries and is equivalent to constantly discharging and recharging the battery a tiny amount.
Ni-cad cells can be adversely affected by ripple currents although they provide a very good
filtering capability. Lead, being much softer than nickel, requires different plate construction
techniques which make lead-acid batteries even more susceptible to harmful effects from ripple
currents. Usually ripple currents of less than 5 percent over the allowable continuous input range
of the battery will not be harmful to lead-acid batteries. A lead-acid battery operated on a high-
ripple current input at an elevated temperature can have its operating life reduced to one quarter
of what would normally be expected.

       (5) Memory effect. Ni-cad cells charged at very low rates are subject to a condition known
as a "memory effect." Shallow cycling repeated to approximately the same depth of discharge
leads to continual low-rate charging. The result is a battery action which has reduced the
effective reserve time of the UPS system. An affected cell can have the memory effect erased by
providing a complete discharge followed by a full charge with constant current which breaks up
the crystalline growth on the plates.

  m. Effects of loads on static UPS systems. Linear loads present a constant load impedance to
the power source. This type of load results in a constant voltage drop. However, non-linear loads
draw non-sinusoidal current resulting in a non-sinusoidal voltage drop. Non-linear loads and
loads with high inrush current demand could adversely affect the static UPS system performance.

       (1) Non-linear loads. Non-linear loads are loads whose current is not proportional to the
supply voltage such as loads with ferroresonant transformers or regulating transformers and solid-
state power supplies. Non-linear loads distort the inverter output voltage wave shape and cause
the output voltage to contain high harmonic content. This effect can be more pronounced in
inverters with high impedance such as inverters with pulse width control technique and inverters
with a ferroresonant output transformer.

       (2) Loads with high inrush current. Loads such as motors, transformers, incandescent
lamps, etc., draw a high initial current when energized. The high initial current for such loads
could be as high as 10 times the normal full load current. Therefore, loads with high inrush
current requirements should not be energized simultaneously otherwise the inverter may reach the
current limit point.

  n. Effect of static UPS system on power supply system. The battery charger within the static
UPS is a controlled rectifier which draws non-sinusoidal currents from the power source. The ac
line current drawn is basically a square wave or a stepped wave depending on the charger design.
This square or stepped wave can be analyzed into an equivalent sinusoidal wave of the power

                                                                                                                       2-25


---

TM 5-693

frequency (i.e., the fundamental component) plus other sinusoidal waves of higher frequencies or
harmonics. These harmonic currents cause harmonic voltage drops in the power source
impedance. This results in power source voltage distortion and the flow of harmonic currents in
the power system components and loads. The degree of power source voltage distortion increases
with the static UPS system capacity as well as the power source equivalent impedance. The flow
of harmonic currents in the power system can cause resonance and additional losses and heating
in the power source's components and loads. Normally, a static UPS system does not have
detrimental effects on the power supply system. However, when the static UPS system capacity
is close to 20 percent of the supply system capacity, the harmonic effects should be analyzed.
The effect of the UPS generated harmonics on the power source and other supplied equipment
can be minimized when necessary. The use of a 12- (or more) pulse rectifier reduces the
harmonic currents generated. The harmonic currents present in input current to a typical rectifier
in per-unit of the fundamental current are as shown in table 2-2. However, the rectifier number of
pulses is an equipment specific design parameter that is not normally specified by the user.
Should the UPS generated harmonics become a problem and affect other loads supplied from the
same bus as the UPS, harmonic filters at the UPS input may be used. Harmonic filters filter out
the harmonic currents and minimize the voltage distortion and its effects on harmonic susceptible
equipment.

Table 2-2. Harmonic currents present in input current to a typical rectifier in per-unit of the fundamental
current

Converter                        Harmonic Order
Pulses
6              5      7      11  13     17           19      23                     25
12         0.175  0.11   0.045                   0.010   0.009                  0.008
18         0.026  0.016  0.045   0.029  0.015    0.001   0.009                  0.008
24         0.026  0.016  0.007                   0.010   0.001                  0.001
           0.026  0.016  0.007   0.029  0.002    0.001   0.009                  0.008

                                 0.004  0.015

                                 0.004  0.002

           From IEEE Std 519-1981. Copyright © 1981 IEEE. All rights reserved.

       (1) Magnitude of harmonic effects. Systems with low impedances such as a large power
system will be less sensitive to the harmonic distortion from the non-linear UPS load than an
engine-generator source whose rating is close to that of the UPS. Sources with a high impedance
in relation to the load are known as "soft" power sources when they are unable to absorb the
generated distortion of their critical load; that is, the source voltage waveform can be greatly
deformed by the critical load waveform. It is difficult for the UPS to attenuate load produced
noise. A very noisy or extremely non-linear load may reflect current distortions via the UPS
input onto the source. Any interposed soft source may interact with this load to increase rather
than reduce critical load power disturbances. So non-linear loads on the UPS can actually distort
the "clean" power the UPS is designed to provide by their load-induced current harmonics. Most
UPSs provide an input current distortion which meets or is less than the Information Technology
Industry Council (ITIC) [formerly called Computer Business Equipment Manufacturers
Association (CBEMA)] recommendations. To maintain required power quality to other loads
served by the UPS source, ITIC advocates an input having a total reflected current harmonic
distortion (THD) of 5 percent or less of line-to-line distortion with a maximum of 3 percent for
any one harmonic order. Total distortion is the vector sum of individual harmonic frequency
distortions. UPS manufacturers typically guarantee that this distortion holds when the UPS
supplies linear loads. A UPS sized for the addition of future loads may be in trouble if the future
loads have high harmonic contents. All manufacturers of electronic equipment install line filters

2-26


---

                                                                                                                     TM 5-693

to meet the Federal Communications Commission's (FCC) requirements for radio frequency
limits. They do not necessarily provide them for reducing power-line harmonics since this adds
to equipment costs. Electronic load-induced distortion beyond the UPS limitations can be
deduced if adverse effects occur under maximum loads but not under lesser loads. As the UPS
impedance increases in relation to the lower loads, this may reduce the distortion to limits which
can be handled by the UPS. Experience has shown that while distortion in excess of the UPS
manufacturer's specified limits may not operate protective circuitry, such excess distortion will
probably result in increased heating and possible reduction in equipment life.

       (2) Problems from harmonics. Harmonic voltages and currents resulting from non-linear
loads have caused operating problems, equipment failures, and fires. Harmonics cause increased
heating, lower the power factor, change crest factors, increase zero crossing points, provide noise
feedback, and influence inductive and capacitive reactance. An understanding of harmonic
behavior helps to recognize actions which adversely influence the overall electrical systems.

       (3) Neutral harmonic behavior. Harmonics are integral multiples of the fundamental
power [60 hertz (Hz)] frequency. Odd-order harmonics are additive in the common neutral of a
three-phase system. For pulsed loads, even-order harmonics may be additive if the pulses occur
in each phase at a different time so that they do not cancel in the neutral. This results in
overloaded neutrals and becomes a fire safety concern. ITIC recommends providing double-
capacity neutrals. Section 310-4 of the National Electrical Code (NEC) suggests installing
parallel conductors to alleviate overheating of the neutral in existing installations where there is
high harmonic content. Balanced neutral current buildup due to harmonics can be as high as 1.73
times the phase current. Under unbalanced conditions, neutral current can be as much as three
times the phase current for worst case, pulsed loads. Oversized (that is per normal linear-load
applications) neutrals should be a requirement wherever solid-state equipment is installed.

       (4) Harmonics and equipment ratings. Transformers, motors, and generators are rated on
the heating effects of an undistorted 60-Hz sine wave. At higher frequencies, hysteresis and eddy
current losses are increased, and the conductor's skin effect decreases its ampacity. Substantial
harmonic currents therefore will result in substantial heating effects, which means that the
equipment loads must be decreased to prevent overheating. Equipment loaded to less than 70
percent of its nameplate rating has been shut down because of harmonic overheating.
Unfortunately, there is only one standard on how to derate equipment. American National
Standards Institute (ANSI) C57.110 covers transformers, but a measured harmonic distribution of
the load current is probably not available to most users. Equipment capability must be checked
then by observation based on the temperature rise of the affected equipment.

       (5) Lower power factor. Many non-linear loads have an uncorrected low power factor
because expensive power factor and harmonic line distortion correction has not been provided.
Any decrease in system power factor may indicate a load change has been made, which has
increased harmonic distortion.

       (6) Crest value changes. Measurements for currents and voltages are based on average or
peak values, which are calibrated to read root-mean-square () or effective values. For a sine
wave, the crest factor or ratio of the peak to the root mean square (RMS) value is 1.414. Crest
values of non-sinusoidal waveforms can be greater than this value, so that normal measuring
instruments do not provide correct readings. It is the effective value which is a measure of the
true amount of heat from a resistance. Inaccurate measurements (low for average-sensing and
high for peak-sensing instruments) can lead to protective device actions such as premature
tripping or failure to trip. Induction-disc watt-hour meters, when used for billing, may result in

                                                                                                                       2-27


---

TM 5-693

bills which are usually too high rather than too low. True RMS sensing is practical but requires
microprocessor based technology. The use of other than true RMS sensing meters, relays, and
circuit breaker trip units may contribute to system operating problems.

       (7) Zero crossing increases. Controls such as generator voltage regulators which use the
zero crossing point of a voltage or current wave can start hunting where harmonic contents result
in more zero crossings than there are naturally in a 60-Hz system. Instability in speed and
frequency can result, causing generator paralleling problems. An inaccurate measurement of
RMS values can prevent proper load sharing of paralleled units. These are important
considerations when generating-capacity requirements are changed. Generator manufacturers
should be contacted when existing units are used to supply non-linear loads in order to ensure
compatible interfacing.

       (8) Noise feedback. Power-line harmonics at audio and even radio frequencies can be
interposed on telephone, communication, and data systems by inductive or capacitive coupling
and by radiation. FCC has set maximum power line conduction and radiation standards for many
types of electric equipment. Unfortunately, not all harmonic-generating non-linear loads come
under FCC standards, and improperly shielded and filtered equipment can conduct or radiate
noise, which may cause problems even many miles from their source.

       (9) Inductive and capacitive influences. High harmonic content can cause resonant circuits
at one or more of the harmonic frequencies, resulting in voltages and currents that are higher than
equipment ratings. Insulation breakdown, overheated equipment, and eventually equipment
failure will result. Additionally, capacitors added for surge suppression or power factor
correction may have such a low reactance at higher harmonic frequencies as to cause a short
circuit and failure of the capacitor.

       (10) Harmonic correction techniques. The measurements of harmonic currents and
voltages require special techniques. The inductive and capacitive impedance is variable because
of harmonic variations; therefore, its effects are usually unpredictable. More and more the power
system is becoming susceptible to the operation of the sensitive electronic equipment, as much as
or more than the sensitive electronic device is susceptible to the power source. If harmonic
problems have been identified as causing problems, certain procedures are recommended. The
following are some of the procedures. Provide oversized neutral conductors. Derate
transformers, generators, motors, and UPS if necessary. Insure all controls, especially those
involving generator speed and paralleling, are properly shielded and filtered and are designed to
respond as quickly as is necessary. Use of unfiltered voltage regulators and non-electronic
governors will probably cause problems, especially for generators supplying more than a 25-
percent non-linear load. Provide line filters to suppress the harmonics emanating from the power
source. Increase power source capacities so as to lower output impedance and minimize voltage
distortion. Use UPS outputs which have no neutrals. Where neutral voltages are required,
provide isolation transformers as close to their loads as possible to shorten oversized neutral
installations. Use true RMS sensing for circuit breaker trip units, relays, meters, and instruments.

  o. Advantages and disadvantages of static UPS systems. Static UPS systems have several
advantages. They provide disturbance free uninterrupted power, operate at low sound levels, have
high reliability and short repair times, require minimal maintenance, simple installation, and lend
themselves to future expansion and reconfiguration. However, they also have some
disadvantages. Some of the disadvantages are that they introduce harmonics into the power
supply system, have a high initial cost to purchase, require large space, require regulated

2-28


---

                                                                                                                     TM 5-693

environment, require skilled technicians for trouble shooting and repairs, and have a somewhat
low efficiency.
2-2. Principles of rotary UPS systems
The most basic UPS system is the inertia-driven ride-through system. This system consists of a
synchronous motor driving a synchronous generator with a large flywheel as shown in figure 2-
20. During normal operation the motor drives the flywheel and the synchronous generator at
constant speed proportional to the power supply frequency. The generator output voltage is
regulated by the voltage regulator and the frequency is constant and proportional to the motor
power supply frequency. When input power is momentarily lost or degrades, the flywheel
supplies its stored energy to the generator and the frequency is maintained within the required
tolerance for a duration depending on the flywheel inertia. The time interval for which the
frequency can be maintained within tolerance is proportional to the ratio of flywheel inertia to the

                                   Figure 2-20. Inertia-driven ride-through system
load for a given speed. To keep the system weight low, high speed is required. However, to keep
the noise level low, low speed is desirable. Therefore, the system is commonly operated at a
speed of 1800 revolutions per minute (rpm) as a trade-off. In this system, a synchronous motor is
used to maintain a constant speed independent of the load level. However, an induction motor
with very low slip may also be used as discussed in paragraph 2-2a(1). In newer designs an
asynchronous motor is coupled with a synchronous generator. This technology uses induction
coupling rather than a flywheel for the ride-through inertia. Other designs use a battery. The
battery-supported inertia rotary UPS system consists of a synchronous motor driving a
synchronous generator, with a rectifier, inverter, and storage battery added. The system
configuration is shown in figure 2-21. During normal operation, the synchronous motor drives
the synchronous generator and provides filtered power. Upon loss of the ac input power to the
motor, the battery supplies power to the motor through the inverter which drives the generator.
The batteries provide energy to the system during the transition from normal to emergency
operation. This system may also use a kinetic battery in place of the standard lead-acid and ni-
cad batteries [see paragraph 2-2b(6)].

                                                                                                                       2-29


---

TM 5-693

                             Figure 2-21. Battery supported motor-generator (M-G) set

  a. Motor types and characteristics. In a rotary UPS system an ac motor is used to convert
electrical energy to mechanical energy for driving an ac generator and a flywheel. Both
synchronous and induction motor types may be used. DC motors are also used in rotary systems
with a storage battery for back-up power. In the following paragraphs, only the motor
characteristics relevant to rotary UPS applications are addressed.

       (1) Induction motors. Induction motors are of the squirrel cage or the wound rotor type. It
is the three-phase cage motor type that is used in rotary UPS applications. The relevant
characteristics of a cage motor are as follows. The motor speed is essentially proportional to the
power supply frequency. The motor speed is dependent on the load level. For a motor with 5
percent slip, the speed may increase by up to 5 percent of the rated speed from rated load to no
load. The speed variations are lower for low slip motors. When energized, the motor draws a
starting current as high as 6.5 times the rated current for a duration of 2 to 10 seconds or longer
depending on the load inertia. The induction motor power factor is approximately 0.8 lagging.

       (2) Synchronous motors. The relevant characteristics of a three-phase synchronous motor
are as follows. The motor speed is independent of the load and is directly proportional to the
power supply frequency. The starting current and starting duration of a synchronous motor are
slightly less than those of a comparable induction motor. A synchronous motor can be either self-
excited or externally excited (see paragraph 2-2b(3) for exciter types). The synchronous motor
power factor can be changed from lagging to unity to leading by adjusting the field or exciting
current.

       (3) DC motors. DC motors are classified according to the method of excitation used as
shunt excited, series excited, and compound excited. The shunt excited dc motor is the most
suitable in rotary UPS applications and has the following characteristics. The motor speed is
dependent on the load level. The speed may decrease by up to 5 percent of the rated speed from
no load to rated load. The motor speed can be easily adjusted by varying the shunt field current
through the use of a rheostat. The motor can be operated as a generator by applying mechanical
input to the shaft.

  b. Generator types and characteristics. In a rotary UPS system a synchronous generator is
used to convert the motor mechanical energy or the mechanical energy stored in a flywheel to ac
electrical energy with regulated voltage. In rotary systems with a storage battery a dc motor or
inverter is provided for driving the generator during a loss of ac power. When ac power is
available, the dc motor is operated as a dc generator to charge the battery. Newer rotary system

2-30


---

                                                                                                                     TM 5-693

designs may also utilize a back-up inverter and a dc battery to supply the driving motor upon loss
of the normal ac power. In the following paragraphs, only the generator characteristics relevant
to rotary UPS applications will be discussed.

       (1) Synchronous generators. The relevant characteristics of a three-phase synchronous
generator are as follows. The generator frequency is directly proportional to the prime mover
speed. Controlling the output frequency is accomplished by controlling the prime mover speed.
The output voltage can be regulated by varying the field current, i.e., excitation level. The
generator rated power factor is normally 0.8 lagging. The generator has a limited load unbalance
capability; severe unbalance can result in overheating. The generator can supply a maximum
current of 6 to 7 times rated RMS current for a few cycles and 3 to 4 times rated RMS current for
a few seconds. The output voltage harmonic content is typically less than 5 percent.

       (2) DC generators. Similar to dc motors, dc generators are classified as shunt excited,
series excited, and compound excited. The relevant characteristics of dc generators are as
follows. The generator output is essentially ripple free power. The output voltage can be
precisely held at any desired value from zero to rated by controlling the excitation level. The
generator can be operated as a motor by applying dc power to its armature.

       (3) Exciters. Exciters are used to create the magnetic field on the generator. They can be
broadly classified as static and rotary. In a static exciter all components are stationary and are
mounted outside of the machine frame. The synchronous machine field coils are connected to
commutator rings, and brushes are used to connect the field coils to the excitation power source.
In a rotary exciter, some of the components are rotating and are mounted either on the
synchronous machine shaft or externally. Also, in a rotary exciter a commutator ring and brushes
may be required or the system may be brushless. Brushless type exciters are more commonly
used now due to their lower maintenance requirements. However, selection of the exciter type is
largely up to the manufacturer to meet the performance requirements.

       (4) Flywheel. A flywheel is used in a rotary UPS system as an energy storage device. The
flywheel is coupled to the M-G shaft and supplies stored energy to drive the generator upon
momentary loss of the motor output. In addition, it acts to stabilize the generator frequency by
maintaining the rotational speed following transient frequency variations at the motor power
supply or sudden load changes. The flywheel may be considered an analog to a storage battery
(with a very short protection time) in static UPS systems.

       (5) Induction coupling. Induction coupling occurs when using an asynchronous motor and
a synchronous generator. The induction coupling provides kinetic energy lasting approximately 2
seconds after loss of normal ac power to allow transfer to backup power. During this time a
backup diesel generator may be brought on-line to provide power. This kinetic energy is supplied
from the rotor. Energy storage is achieved when the rotor of a three-phase, two-pole
asynchronous machine is accelerated to 3600 rpm. The stator of the same machine is
mechanically connected with the rotor of the synchronous machine, running at 1800 rpm. The
squirrel cage rotor of the asynchronous machine will run at 5400 rpm (1800 plus 3600 rpm). To
retrieve energy from the squirrel cage, at the moment of power interruption, a controlled dc field
is provided through an additional dc stator winding in the asynchronous machine. The magnetic
field created in this way brakes the speed of the free running inner rotor, so that energy is
released. This energy is used to keep the rotor running at 1800 rpm, while the generator comes
on line.

                                                                                                                       2-31


---

TM 5-693

       (6) Kinetic battery. The kinetic battery may be used in place of regular flooded lead-acid
or ni-cad batteries in the battery backed M-G configuration as shown in figure 2-21. The energy
for the kinetic battery comes from a flywheel coupled with a M-G set. The energy from the
flywheel is driven by a small pony motor using normal ac power. Upon loss of normal power, the
flywheel continues to put out energy through the generator which provides input ac power to the
rectifier. The rectifier and inverter filters the ac power and provides ac power to the primary M-G
set. The ac power must be filtered to prevent the load from seeing the degradation of the
frequency as received from the flywheel-generator source. This system allows for approximately
15 to 30 seconds of ride-through while waiting for the diesel generator to start.

  c. Affect of loads on rotary UPS systems. Various types of loads may affect the UPSs ability
to perform. Some of these load types are non-linear loads, loads with high inrush current, and
unbalanced loads.

       (1) Non-linear loads. Non-linear loads as discussed in paragraph 2-1m(1) will distort the
synchronous generator output voltage wave shape and cause the output voltage to contain high
harmonic content. The harmonic currents generated can also cause additional losses and heating
in the generator. This may require derating the generator if the harmonic content of the load
current is excessive. The generator manufacturer should provide the derating recommendations
which are based on the nature as well as the level of the non-linear loads.

       (2) Loads with high inrush current. Unlike a static UPS system, a rotary UPS system is
capable of supplying high inrush currents at reduced voltages. The level of voltage reduction is
more gradual than for the static inverter and depends on the generator transient reactance.

       (3) Unbalanced loads. The unbalanced load capability of a rotary system is less than that
of a comparable static UPS system. A synchronous generator has a very limited negative
sequence current capability. Highly unbalanced loads produce high negative sequence currents
which cause severe overheating.

  d. Affect of the rotary UPS system on the power supply system. Due to the high starting
current required by ac motors, a rotary UPS system may cause the reduction of the power supply
system voltage during startup. The duration of the voltage reduction is dependent on the motor
type and the system inertia. It could be as long as 10 or 15 seconds. The power factor of a
system with a synchronous motor can be made leading by adjusting the motor excitation level.
This means that the motor can be made to supply reactive power to the power supply system and
improve its overall power factor. Improving the overall power factor can improve the supply
system voltage regulation. On the other hand, systems with an induction motor have a power
factor of approximately 0.8 lagging. Such a system requires reactive kVA from the power supply
system which may cause a voltage reduction on the supply system. AC motors contribute
currents during system faults. A large rotary UPS system may appreciably increase the system
short circuit capability.

  e. Advantages and disadvantages of rotary UPS systems. The rotary UPS system has both
advantages and disadvantages that should be considered at the time of selection.

       (1) Rotary advantages. There are many advantages to a rotary UPS system. The rotary
system low output impedance makes it able to supply higher fault currents to operate a circuit
breaker during fault conditions. They provide total isolation of sensitive loads from power supply
system transients. They provide disturbance free uninterrupted power. Systems without storage
batteries have a low initial cost. Efficiency is higher than comparable static UPS systems. The

2-32


---

                                                                                                                     TM 5-693

rotary UPS systems have higher tolerance to adverse environments. Some require small space,
especially systems without a storage battery. They do not cause power supply system voltage
distortion. High ratings, e.g., above 1000 kVA can be built in the rotary UPS design. A rotary
system has a lower number of components than a comparable static system and hence has a lower
failure rate. It has a low output impedance which makes its output voltage less susceptible to
harmonic distortion as may be caused by non-linear loads.

       (2) Disadvantages. While there are several advantages to the rotary UPS, it does have
some short comings. Some of them are that they operate at high sound levels unless equipped
with special silencing enclosures. They require more maintenance and long repair times. Also,
they require special foundations. Their installation is more complex. They do not easily lend
themselves to future expansion, paralleling, or reconfiguration. Their performance requirements
and configurations are not commonly standardized. Fewer manufacturers produce rotary UPS
systems as compared to static UPS systems. The rotary UPS has a short backup time and requires
either a battery or backup diesel generator for longer backup power.

2-3. Common static UPS system configurations

The building blocks of a static UPS system are rectifier/charger, inverter, battery, and static switch.
These building blocks can be assembled in many configurations as required to meet reliability and/or
economic considerations. However, some specific configurations have been in common use and are
standardized in Institute of Electrical and Electronic Engineers (IEEE) 446. The most common of these
configurations in ascending order of reliability are a non-redundant system, a system with static bypass
switch, a redundant system, a cold standby redundant system, and a dual redundant system with static
transfer switches.

  a. Non-redundant system. The non-redundant static UPS system shown in figure 2-22 is the
basic system described in paragraph 2-1. One major limitation in this configuration is that failure
of the inverter leads to the loss of power to the supplied loads. This limitation makes this
configuration undesirable except for supplying redundant loads where the loss of one load group
does not impact operation. Another limitation is that due to the limited overload capability of the
inverter elements, it is not suitable for supplying loads with high inrush current requirements.

                                    Figure 2-22. Non-redundant static UPS system

  b. System with static bypass switch. The static UPS system with a static transfer switch is
shown in figure 2-23. It is made up of the basic system with the addition of a static transfer
switch to transfer to an alternate ac source. Normal operation of this system is basically the same
as the basic system as described in paragraph 2-1. In addition, the static transfer switch sensing
and logic circuit continuously monitors the inverter output voltage and initiates a load transfer to

                                                                                                                       2-33


---

TM 5-693

                             Figure 2-23. Static UPS system with static transfer switch
the alternate source during a loss of inverter output or a deviation of the inverter output voltage
beyond the allowable tolerance due to malfunctions, high inrush demand, or a load branch circuit
fault. In order to minimize disturbances to the connected loads during transfers, the inverter is
synchronized to the alternate ac source. During normal operation the inverter frequency is
controlled by the alternate source's frequency. In this mode, the inverter's internal oscillator
provided for controlling the inverter frequency is bypassed. However, should the alternate source
frequency deviate beyond the allowable tolerance, the inverter automatically reverts to its internal
oscillator for frequency control and maintains the frequency within tolerance. The static transfer
switch is commonly designed to automatically retransfer the loads back to the inverter when its
output voltage recovers to within tolerance. However, the automatic retransfer feature can be
inhibited if desired to allow for manual retransfer only. The addition of the static transfer switch
to the basic system configuration increases the system reliability by connecting the loads to an
alternate source upon loss of the inverter output. In addition, this configuration facilitates
supplying loads with high inrush demands. One common improvement to this system is the
addition of a regulating transformer as shown in figure 2-24. A regulating transformer is a
specially designed transformer which can maintain its output voltage with limited deviations in
input voltage. In addition, it can attenuate voltage surges and spikes originating in the power
supply source.

Figure 2-24. Static UPS system with static transfer switch and an alternate source regulating transformer
2-34


---

                                                                                                                     TM 5-693

  c. Redundant system. The redundant static UPS system configuration is shown in figure 2-25.
This configuration is made up of two or more normally energized basic systems connected in
parallel and synchronized with one another. The static interrupters used in this configuration are
solid-state devices which serve to isolate a faulty inverter from the connected loads and to prevent
the other inverters from supplying high fault currents to the faulted inverter. In this
configuration, although the rectifier/inverter combinations are duplicated for higher reliability,
only one common battery is used. This is due to the extremely high reliability of batteries. The
rating of each of the parallel basic systems should be such that if one system fails, the remaining
systems are capable of supplying the connected load. Therefore, for a two-parallel system, each
system should be rated for 100 percent capacity and for a three-parallel system, each system
should be rated for 50 percent capacity, etc. In this configuration, all the parallel systems are
normally energized and share the load equally. It is also used where very high reliability is
required. Should one system fail, the remaining systems supply the load without interruption.
installations (400 kVA and larger) where the load exceeds the rating of available systems. This
configuration is also commonly used in very large configuration is more costly than other
configurations to purchase and install. In addition, it has a lower overall efficiency since all the
parallel systems have to be operated continuously at part load where the efficiency is lower than
at full load. However, this configuration is desirable where very high reliability is essential and
the reliability of the ac power supply is questionable. It should be noted that C4ISR facilities
require a system reliability level of 99.9999 percent.

                                       Figure 2-25. Redundant static UPS system
  d. Cold standby redundant system. The cold standby redundant static UPS system
configuration is shown in figure 2-26. It is made up of two basic systems with one common
battery. Each of the two basic systems is rated at 100 percent capacity. During normal operation
one system is de-energized and the other system is energized to supply the load through a
manually operated circuit breaker. Upon loss of the inverter output, the static switch
automatically connects the load to the alternate source without interruption. The second system's
static switch is then closed manually, also connecting the load to the alternate source. To transfer
the load to the second system, the static switch of the failed system is manually opened. Next the
second system's breaker is manually closed, its static switch is opened, and the load is supplied
from the system's inverter. During the transfer operations, the load is continuously supplied from

                                                                                                                       2-35


---

TM 5-693

the alternate source without interruption until it is switched to the second system. In this
configuration the two inverters are not intended for operation in parallel and their output circuit
breakers are interlocked to prevent this condition. One disadvantage of this configuration, when
compared to the redundant system, is that the load is supplied from the unregulated alternate
source for a short duration before the transfer is completed. Also, the transfer from one system to
the other is manually accomplished and requires an operator's action. This makes the use of this
configuration undesirable in locations where the alternate power source has a low reliability.
However, this configuration has a higher efficiency than a comparable two-parallel redundant
configuration. The higher efficiency is due to operating the energized system at 100 percent
capacity as compared to operating each of the systems of a two-parallel redundant configuration
at 50 percent capacity. Another advantage of this configuration over the redundant system is that
the two basic systems are not susceptible to a single failure.

                               Figure 2-26. Cold standby redundant static UPS system
  e. Dual redundant system with static transfer switches. The configuration of the dual
redundant static UPS system with static transfer switches is shown in figure 2-27. Like the
redundant system configuration, it is made up of two normally energized 100 percent capacity
basic systems connected in parallel with one common battery. Each of the two basic systems is
synchronized to the alternate source. The static switch provided at the output of each system
serves the functions of a static interrupter as in the redundant system configuration, and a switch.
Operation of this configuration is similar to the redundant system. In addition, upon loss of both
systems or deviation of the output voltage beyond acceptable limits, the static switches disconnect
the load from the inverters and connect it to the alternate source in a make-before-break transfer.
The addition of the alternate source increases the reliability of this configuration over the
comparable redundant system. In addition, the static switches make this configuration capable of
supplying high in-rush currents by transferring to the alternate source. As with all systems with a
static transfer switch to an alternate ac source, a regulating transformer connected to the alternate
ac source is commonly used.
2-4. Rotary UPS system configurations

The main building blocks of rotary UPS systems are the synchronous motor, ac generator, and
flywheel. In addition to the main building blocks, induction motors, eddy current clutches,
batteries, dc M-Gs, and static rectifier/inverters are also used in rotary UPS systems. The
building blocks can be assembled in numerous configurations to meet reliability and/or economic

2-36


---

                                                                                                                     TM 5-693

considerations. The most common rotary UPS configurations are the inertia-driven ride-through
system with a synchronous motor, the inertia-driven ride- through system with an induction
motor, inertia-driven ride-through system with an induction motor and an eddy current clutch,
battery supported inertia system with a dc motor, and battery supported inertia system with a
backup inverter.

                  Figure 2-27. Dual redundant static UPS system with static transfer switches
  a. Inertia-driven ride-through system with a synchronous motor. The inertia-driven ride-
through system with a synchronous motor shown in figure 2-28 is the basic inertia-driven ride-
through system described in paragraph 2-2. The main limitation in this configuration is that the
ride-through time is normally limited to 0.5 seconds. This makes this configuration suitable only
at locations where the power supply has a high reliability and long term interruptions are unlikely
as in large metropolitan areas. This configuration is also widely used in frequency changer
applications to convert the power supply frequency to another frequency such as 420 Hz. In this
application the synchronous motor drives the generator at a constant speed proportional to the
power supply frequency. The ratio of the generator number of poles to the motor number of poles
should be the same as the ratio of the desired frequency to the power supply frequency. This
configuration is becoming less common and it is not available from many manufacturers.
However, newer technologies provide an induction coupling system for the inertia ride-through
rather than the flywheel as discussed in paragraph 2-2b(5). This system is used with an
asynchronous motor and a synchronous diesel generator. The induction coupling allows for
approximately 2 seconds of ride-through while the diesel generator comes on line.
  b. Inertia-driven ride-through system with an induction motor. The inertia-driven ride-
through system with an induction motor is the same as shown in figure 2-28 except for replacing
the synchronous motor with an induction motor. In this configuration, the induction motor must
be with low-slip characteristics - typically less than 0.5 percent slip. With 0.5 percent slip
characteristic, the generator output frequency (for a 60 Hz system) can vary from 59.7 Hz at rated
load to near 60 Hz at no load. This configuration has the same limitation as the configuration
with a synchronous motor. In addition, it is mostly suitable for supplying loads with higher
tolerance to frequency variations. However, due to the lower cost of an induction motor as
compared to a comparable synchronous motor, this configuration is less costly.

                                                                                                                       2-37


---

TM 5-693

                   Figure 2-28. Inertia-driven ride-through system with a synchronous motor
  c. Inertia-driven ride-through system with an induction motor and an eddy current clutch.
This configuration shown in figure 2-29 consists of an induction motor which drives a flywheel
and an eddy current clutch at a speed essentially proportional to the supply frequency. The
generator rotates at a constant speed lower than the motor speed by controlling the slip of the
eddy current clutch. The generator output frequency can be maintained at 60 hertz ±0.25 hertz.
On loss of the ac input power, the generator receives energy stored in the flywheel. As the
flywheel slows down, the slip of the eddy current clutch is reduced so as to maintain the generator
frequency at 60 Hz. The generator frequency can be maintained above 59.5 Hz for up to 15
seconds after loss of ac input power. This configuration is most suitable where a backup power
source such as a diesel generator or gas turbine is available. The rotary system can supply the
loads until the backup source is started and operated to supply the motor. However, the use of
this configuration is becoming less common and it is not available from many manufacturers.

    Figure 2-29. Inertia-driven ride-through system with an induction motor and an eddy current clutch
  d. Battery supported inertia system with a dc motor. The battery supported inertia system
with a dc motor is shown in figure 2-30. The ac motor may be a synchronous or a low slip
induction motor. The frequency regulation of systems using an induction motor is the same as
the inertia-driven ride-through system described in paragraph 2-2. This configuration is required
at installations where the power supply is of low reliability and long term interruptions are
common. This type is no longer manufactured, however, there may be some still in use.

2-38


---

                                                                                                                     TM 5-693

                                     Figure 2-30. Battery supported inertia system
  e. Battery supported M-G set. The battery supported M-G system with a backup inverter is
shown in figure 2-31. It is made up of a synchronous M-G set with the addition of a
rectifier/inverter, batteries, and a static switch. During normal operation, the static switch is
conducting and 95 percent of the required power is supplied to the motor from the ac source. The
remaining 5 percent power is supplied through the rectifier/inverter while the battery is float
charged. The inverter is kept operational at this low power level to ensure that it remains
operational and can supply full power in the event of degradation or loss of the ac source. Upon
loss of the ac source or deviation of its frequency and/or voltage from acceptable limits required
to maintain the generator output, the static switch is automatically blocked and power is supplied
from the battery to the motor through the inverter. Upon restoration of the ac source, the static
switch automatically conducts and the system reverts to normal operation. This configuration
provides conditioned, isolated, and uninterrupted power. In addition, it has a higher reliability
and requires less maintenance than a comparable rotary system with a dc motor. DC machines in
general require more frequent maintenance due to wear in brushes and wear and pitting in the
commutator ring.

                                        Figure 2-31. Battery supported M-G set
  f. Rotary systems with a transfer switch to a bypass source. Like static UPS systems, rotary
systems can be provided with a transfer switch to transfer the load to an alternate source upon
loss of the generator output. However, unlike the static UPS inverter, it is not practical or
economical to synchronize the generator to the alternate source. Therefore, the transfer may

                                                                                                                       2-39


---

TM 5-693
occur in "out-of-synch" mode and may subject the connected loads to undesirable transient
overvoltages. Therefore, although the addition of a transfer switch can increase the availability of
power supply, live transfer is not recommended in rotary systems. Also, less costly
electromechanical switches may be adequate for this purpose.

  g. Paralleling of redundant rotary systems. Redundant rotary systems may be connected in
parallel to provide higher capacity and/or to increase the reliability as was discussed in paragraph
2-3c for static UPS systems. However, due to the difficulty of synchronizing the generators to
one another, switching the individual generators for parallel operation should be performed
without the loads being connected to avoid subjecting sensitive equipment to high voltage
transients during switching.

2-40


---

                                                                                                                      TM 5-693

                                      CHAPTER 3

          DESIGN AND SELECTION OF UNINTERRUPTIBLE
                              POWER SUPPLY (UPS)

_____________________________________________________________

3-1. Selecting an UPS
The process for selecting an UPS consists of eight steps. These steps are: determining the need
for an UPS, determining the purpose(s) of the UPS, determining the power requirements,
selecting the type of UPS, determining if the safety of the selected UPS is acceptable,
determining if the availability of the selected UPS is acceptable, determining if the selected UPS
is maintainable, and determining if the selected UPS is affordable. The last four steps may
require repeating if the UPS does not meet all of the requirements. This process does not and
cannot provide a “cookbook solution.” Each facility has unique requirements for emergency and
standby power. These requirements include the reliability of the prime power source, the nature
of the work done, local and state regulations governing emergency power, etc. The process does
not give a single solution that is applicable to all cases. It is hoped, however, that it provides the
framework for selecting an UPS for any facility. Figure 3-1 illustrates this process. To help
illustrate how the selection procedure can be used, an example is provided in appendix B. This
example is completely fictitious and should not be considered as “the” model for how the
selection process would be used in every case. It does, however, illustrate the many factors that
go into the decision process and the need for a good staff to assist the facility manager in making
the UPS selection.

                                 Figure 3-1. Determine the general need for an UPS

  a. Determine the general need for an UPS. The assessment process for determining the need
for a facility UPS is shown in figure 3-2. Determining the need for an UPS is mainly a matter of
evaluating the way in which a facility is used, as well as knowing whether local, state, or federal
laws mandate the incorporation of an UPS. The number of regulations mandating an alternate
power source to ensure safety of personnel and to prevent pollution of the environment continues
to increase. Consequently, enforcement agencies should be consulted to determine if an UPS is
mandated. They should also be consulted during design and installation to make sure that the
UPS is designed and installed in accordance with current applicable regulations.

                                                                                                                         3-1


---

TM 5-693

                                  Figure 3-2. Determine the facility need for an UPS

  b. Determine the purpose of the UPS. An UPS may be needed for a variety of purposes.
These include emergency lighting for evacuation, emergency perimeter lighting for security, shut
down or continued operation of manufacturing equipment or computer operations, continued
operation of life support or critical medical equipment, continued operation of communications,
and safe operation of equipment during sags and brownouts. Some facilities need an UPS for
more than one purpose. In any case, the purpose(s) must be known before proceeding because it
determines many factors that will drive the amount of power required and the type of UPS that
will be needed. These factors are the acceptable delay between loss of primary power and
availability of UPS power, the length of time that emergency or backup power is required, and the
criticality of the load that the UPS must bear. Applications such as hospital life support and
safety, aircraft tracking and landing, and certain production process controls and data processing
cannot tolerate any loss of power, no matter how short the period of time, without loss of life or
revenue. Other applications like refrigeration, heating, and cooling may tolerate loss of power for
several minutes (or longer) without any adverse effects. For data processing equipment, it may
be necessary to maintain power until the equipment can be shut down in an orderly manner. This
process may take only a few minutes. Alternatively, life support, safety, communications and
security equipment, and other applications may require continuous power until primary power is
restored. Restoration of primary power could take hours or even days. A survey of commercial
power outages may be necessary to determine this information. If commercial power outages are
historically infrequent and last only a few minutes or hours, it may not make economical sense to
install an UPS capable of supplying power for several days. Table 3-1 lists some general criteria

3-2


---

     Power Needed           Purpose         Maximum Tolerable Power         Recommended Minimum         Type of Auxiliary Power                                             Justification for UPS
            For      Evacuate Personnel            Failure Duration          Auxiliary Supply Time      Emergency Standby        Prevent panic, injury, loss of life. Comply with building codes and local, state, and
                                                                                          2h                                     federal laws. Lower insurance rates. Prevent property damage. Lessen losses due to
        Lighting                             Up to 10s, preferably not                                        X                  legal suits.
                                                     more than 3s                                                                Lower losses from theft and property damage. Lower insurance rates. Prevent injury.

                         Illuminate                       10 s              10-12 h during all dark     X  X                     Prevent or reduce property loss. Comply with building codes and local, state, and
                     perimeter & for        From 10 s up to 2 or 3 min                                                           federal laws. Prevent injury and loss of life.
                                                                            hours                                                Reduce risk of extended power and light outage due to a longer repair time.
                          security
                     Provide warning                                        Until prime power restored  X                        Prevent loss of sales. Reduce production losses Lower risk of theft. Lower insurance
                                                                                                                                 rates.
                       Restore normal       1 s to indefinite depending on  Until repairs completed     X  X                     Facilitate continuous patient care by surgeons, medical doctors, nurses, and aids.         Table 3-1. General criteria for determining the purposes of an UPS
                        power system                 available light                                                             Comply with all codes, standards, and laws. Prevent injury or loss of life. Lessen losses
                       Provide general                                      and power restored                                   due to legal suits.
                                                Indefinite; depends on
                            lighting            analysis and evaluation     Indefinite; depends on         X                     Prevent injury, loss of life, and property loss by a more orderly and rapid shutdown of
                      Provide power to       Up to 10s (NFPA 99-1996,                                                            critical systems. Lower risk of theft. Lower insurance rates.
                                               ANSI/NFPA 101-1994);         analysis and evaluation                              Restore production. Prevent property damage due to freezing. Provide required electric
                         hospitals and      allow 10s for alternate power                                                        power .
                        medical areas         source to start and transfer  Until prime power restored  X  X                     Restore production. Power instrumentation.

                      Facilitate orderly                  power.            10 min to several hours     X                        Safeguard personnel. Evacuate building. Continue normal activity.
                          shut-down                     0.1 s to 1 h
     Startup Power                                                          Until prime power restored  X  X                     Complete production run. Permit orderly shutdown. Continue normal activity.
                      Startup power for                      3s
     Startup Power           boilers                                        Until prime power restored     X                     Evacuate building. Continue normal activity.
       (continued)                                         1 min
                      Startup power for                                     1 h (Until prime power         X                     Prevent loss from theft, arson, or riot. Maintain security systems. Comply with codes,
     Transportation            air                    15s to 1 min                                                               standards, and laws. Lower insurance rates. Alert operators to critical out-of-tolerance
                                                                                                                                 temperature, pressure, water level, and other hazardous or dangerous conditions.
                         compressors                                                                                             Comply with local, state, and federal codes, standards, and laws. Prevent personnel
                     Power for elevators                                                                                         injury. Prevent property and economic loss.

                                                                            restored)                                            Continue production. Prevent damage to equipment. Provide fire protection.

                      Power for material            15s to 1 min            1 h (Until prime power         X                     Provide customer service. Maintain personnel performance.
                            handling
                                            15s to no requirement for       restored)                                            Prevent loss of electric generation and steam. Maintain production. Prevent damage to
                      Power for escalators              power                                                                    equipment.
                                                        1-10s               Zero to until prime power      X                     Prevent flooding. Maintain cooling facilities. Provide sanitation.. Continue production.
                     Power for alarms and                                                                                        Maintain boiler operation.
                          annunciators                                      restored

     Signal                                                                 Until prime power restored  X  X
     Circuits

                     Land-based aircraft,           1s to 1 min             Until prime power restored  X  X
                      railroad, and ship
     Mechanical        warning systems                   15s                ½h (Until prime power          X
        Utility       Water (cooling and
       Systems            general use)      1 min to no requirement         restored)
                                                        0.1s
                         Provide water                                      Indefinite until evaluated     X                                                                                                                                                                                    TM 5-693
                     (drinking & sanitary)   10s to no requirement
3-3                                                                         1 h (Until prime power      X  X
                         Provide boiler
                              power                                         restored)

                       Power pumps for                                      Indefinite until evaluated     X
                       water, sanitation,
                        and production

                              fluids


---

Power Needed                                                                                                                                                                                                          TM 5-693Maximum Tolerable PowerRecommended MinimumType of Auxiliary Power
       For                                                                                                                                                                                                  Table 3-1. General criteria for determining the purpose of an UPS (continued)Failure DurationAuxiliary Supply Time
                        Purpose                                     Indefinite until evaluated   Emergency Standby                                                  Justification for UPS
  Mechanical3-4Power fans & blowers      0.1s to until prime power                                                        Maintain boiler operation. Provide venting and purging of gas-fired units. . Maintain
     Utility                                        restored                                     X  X                     cooling and heating functions for buildings and production.
    Systems       for ventilation &
                        heating                      5 min          Until prime power restored      X                     Prevent loss of sales and profit. Prevent spoilage of in-process preparation.
  (continued)                                        5 min          Indefinite until evaluated;
    Heating          Prepare food
                   Sustain process                                     normally for time for
                                                                    orderly shutdown, or until      X                     Prevent in-process production damage. Prevent property damage. Continue production.

                                                                       prime power restored                               Prevent payment to workers during no production. Lower insurance rates
                                                                    Until prime power restored
Refrigeration    Power special                      5 min                                           X                     Prevent equipment or product damage.
 Production       equipment or
                 devices having         5 min (10s per NFPA 99-     Until prime power restored      X                     Prevent loss of stored material.
                critical warm-up                    1996)
                  (cryogenics)                        2h            Indefinite until evaluated      X                     Prevent loss of stored material . Lower insurance rates.
                 Power critical
               depositories (e.g.,                  1 min           Until prime power restored      X                     Prevent product and equipment damage. Continue normal production. Reduce payment
                   blood bank)                                       or until orderly shutdown
               Power non-critical               Up to 1 min                                                               to workers on guaranteed wages during nonproductive period. Lower insurance rates.
               depositories (e.g.,                    10s
                 meat, produce)                     1 min
                   Power critical                   1 min

                       process                   10s or less
                                                   30 min
                                                                                                                          Prevent prolonged shutdown due to non-orderly shutdown
                                                      15s
                   Process control                    10s           Until prime power restored   X  X                     Prevent loss of machine and process computer control program. Maintain production.
                        power
                                                    1 min                                                                 Prevent safety hazards from developing. Prevent out-of-tolerance products.
                   Control critical                   15s
    Space           temperatures                                    1 min or until prime power   X  X                     Prevent personnel hazards, product or property damage. Lower insurance rates.
Conditioning       Control critical
                                                                    restored                                              Continue normal activities. Prevent loss of computer function.
                      pressures
                    Control critical                                1 min or until prime power   X  X                     Prevent personnel hazards, product or property damage. Continue normal activities.

                        humidity                                    restored                                              Lower insurance rates. Comply with local, state, and federal codes, standards, and laws.
                    Control static
                                                                    Until prime power restored      X                     Prevent loss of computer functions. Maintain normal operations and tests. Prevent
                        charge
                  Control building                                                                                        hazards.

                     heating and                                    Until prime power restored   X  X                     Prevent static electric charge and associated hazards. Continue normal production.
                        cooling
                                                                    Until prime power restored      X                     Prevent loss due to freezing Maintenance of personnel efficiency. Continue normal
                 Ventilate for toxic
                         fumes                                                                                            activities.

                    Ventilate for                                   Until prime power restored   X  X                     Reduce health hazards. Comply with local, state, and federal codes, standards, and
               explosive atmosphere
                                                                    or orderly shut-down                                  laws. Reduce pollution

                                                                    Until prime power restored   X  X                     Reduce explosion hazard. Prevent property damage. Lower insurance rates. Comply

                                                                    or orderly shutdown                                   with local, state, and federal codes, standards, and laws. Lower hazard of fire. Reduce

                                                                                                                          hazards to personnel

                General ventilation                                 Until prime power restored      X                     Maintain personnel efficiency. Provide make-up air in building.
               Ventilation for special
                                                                    Until prime power restored   X  X                     Provide purging operation to allow safe shutdown or startup. Reduce hazards to
                      equipment
                                                                    or orderly shutdown                                   personnel and property. Meet requirements of insurance company. Comply with local,

                                                                                                                          state, and federal codes, standards, and laws.


---

     Power Needed      Purpose              Maximum Tolerable Power        Recommended Minimum          Type of Auxiliary Power                                               Justification for UPS
            For      Non-critical                  Failure Duration         Auxiliary Supply Time       Emergency Standby           Maintain comfort. Prevent loss of tests
          Space      ventilation                         1 min                        Optional
                                                                                                                                 X
      Conditioning   Control air                         1 min
       (continued)    pollution

                                                                           Indefinite until evaluated;  X  X                        Continue normal operation. Comply with local, state, and federal codes, standards and          Table 3-1. General criteria for determining the purposes of an UPS (continued)

                                                                           compliance or shutdowns                                  laws                                                                                         IEEE Orange Book Copyright © 1996 IEEE. All rights reserved.

                                                                           are options

        Data         Power CPU memory                   ½ cycle            Until prime power restored      X                        Maintain conditions to prevent malfunctions in data processing system. Prevent damage
     Processing        tape/disk storage,
                           peripherals      5-15 min (1 min for water-     or orderly shutdown                                      to equipment and storage media. Continue normal activity.
         Fire                                    cooled equipment
     Protection      Control humidity and                  1s              Until prime power restored      X                        Prevent malfunctions in data processing system and damage to equipment Continue
                           temperature                    10s
                          Annunciator                                      or orderly shutdown                                      normal activity.
                              alarms
                           Fire Pumps                                      Until prime power restored   X                           Comply with local, state, and federal codes, standards, and laws. Lower insurance rates.

                                                                                                                                    Minimize damage to life and property.

                                                                           Until prime power restored      X                        Comply local, state, and federal codes, standards, and laws. Lower insurance rates.

                                                                                                                                    Minimize damage to life and property.

                     Auxiliary lighting     10s                            5 min or until prime power   X  X                        Service fire pump engine should it fail to start. Provide visual guidance for fire-fighting

                                                                           restored                                                 personnel.

     Life Support    X-ray                  Milliseconds to several hours  From no requirement to       X  X                        Maintain exposure quality. Ensure availability in emergencies.
        and life
         safety                                                            until prime power restored,
        systems
       (Medical                                                            as evaluated
        offices,
                     Light                  Milliseconds to several hours  Until prime power restored   X  X                        Comply with local, state, and federal codes, standards, and laws. Prevent interruption to
      Hospitals,
     clinics, etc.)                                                                                                                 operation and operating needs

                          Critical-to-life  ½ cycle to 10s                 Until prime power restored   X  X                        Maintain life. Prevent interruption of treatment or surgery. Continue normal activity.
                     machines and services       5 min
                                                                                                                                    Comply with local, state, and federal codes, standards, and laws.
                          Refrigeration
                                                                           Until prime power restored      X                        Maintain blood, plasma, and related stored material at recommended temperature and in

                                                                                                                                    prime condition.

     Communication       Teletypewriter     5 min                          Until prime power restored      X                        Maintain customer services. Maintain production control and warehousing. Continue
         Systems
                         Inner building      10s                                                                                    normal communication to prevent economic loss
                     Television (CCTV &      10s
                                                                           Until prime power restored   X                           Continue normal activity and control
                          commercial)        10s
                         Radio systems       10s                           Until prime power restored      X                        Continue sales. Meet contractual obligations.. Maintain security. Continue production.
                       Intercom systems
                                                                           Until prime power restored   X  X                        Continue sales. Meet contractual obligations.. Maintain security. Continue production.

                                                                           Until prime power restored   X  X                        Provide evacuation instructions. Direct activities during emergency. Continue normal                                                                                           TM 5-693

3-5                                                                                                                                 activities. Maintain security.

                     Paging systems         10s                            1/2h                         X  X                        Locate responsible persons concerned with power outage. Provide evacuation

                                                                                                                                    instructions. Prevent panic.


---

TM 5-693

to assist in determining the purposes of a backup power system, diesel generator, UPS, or
combination of diesel may vary. Note that the terms emergency power and standby power are used in
the table. An emergency power system can be defined as an independent reserve source of electric
energy that, upon failure of the primary source, automatically provides reliable electric power within a
specified time to critical devices and equipment which, if they fail to operate satisfactorily, would
jeopardize the health and safety of personnel, result in property damage, or cause loss of revenue. A
standby power system is an independent reserve source of electric energy that, upon failure or outage of
the prime source, provides electric power of acceptable quality so that the user’s facility(ies) may
continue operation in a satisfactory manner.

  c. Determine the power requirements. After determining the specific purpose(s) for an UPS,
the next step is to determine the facility power requirements. This task is often laborious but is
essential because it sets the stage for the remainder of the selection process. Undefined power
requirements, or oversight of any initial conditions, could result in the selection of a system that is
not capable of meeting the needs of the facility, costly budget overruns, and delays in completing
the project. In addition, there is usually significant growth in the number of UPS loads as a
manufacturing plant is developed. This must be accounted for in the sizing of the UPS. Figure 3-
3 outlines the process of determining the required power capacity. The first question to answer is
how much power is needed. Power requirements can be divided into two categories, critical and
non-critical. Critical power can be thought of as power for items such as emergency lighting for
evacuation of personnel, security systems, central computing systems, signaling systems, medical
equipment, and other functions that could cause loss of productivity, or result in injury or a life
threatening situation. Non-critical power is used for functions such as general lighting,
escalators, coffee makers, etc. Once the power requirements are defined, the next step is to
determine how much (if any) to oversize the unit. Oversizing serves two purposes. First, it
provides the capability to efficiently and effectively handle surges in power requirements due to
peak demands caused by starting machinery, switching power supplies, etc. Secondly, it provides
for growth. Over time, power demands may rise due to the addition of equipment or personnel,
increases in productivity, and other reasons. Oversizing the UPS ensures it will have the capacity
to handle the increased load without the expense of retrofitting the system, which is more costly
in the long run. A general rule of thumb in oversizing is to increase the initial power requirement
by 30 percent. If oversizing cannot be justified, the UPS should be selected and the installation
designed such that future expansion can be accommodated at the least possible cost.

  d. Select the Type of UPS. Selecting a particular type and configuration of an UPS depends
on many factors that must be considered and weighted according to a facility’s particular
requirements. These factors include the purpose of the UPS, the required power, cost, safety,
environmental, availability, and maintenance. Note that the selection process (see figure 3-1) is
iterative. The type and configuration of the UPS initially selected is based on the purpose and
power required. If the selected UPS is not acceptable based on one or more of the remaining
factors, another type or configuration must be selected and the evaluation repeated.

  e. Determine if the safety of the selected UPS is acceptable. Safety is an overriding concern
of any UPS design and installation. Safety is basically governed by the electrical codes and
standards as adopted by government and commercial agencies, and good judgment on the part of
the design and installation team. In cases where more than one performance or safety design
alternative exists, preference should be given to those that have been approved by the
governmental authority having jurisdiction. Batteries pose special safety concerns for the facility
manager. Safety problems associated with lead-acid batteries include spills of sulfuric acid,
potential explosions from the generation of hydrogen and oxygen, and the generation of toxic

3-6


---

                                                                                                                      TM 5-693

gasses such as arsine (AsH3) and stibine (SbH3). All of these problems can be satisfactorily
handled with the proper safety precautions. National Fire Protection Association (NFPA) 70,
National Electrical Code (NEC), provides guidance on battery room ventilation. Wearing face
shields and plastic/rubber aprons and gloves when handling acid is recommended to avoid
chemical burns from sulfuric acid. Precautions must be routinely practiced to prevent explosions
from ignition of the flammable gas mixture of hydrogen and oxygen formed during overcharge of
lead-acid cells. The gas mixture is explosive when hydrogen in air exceeds 4 percent by volume.
A standard practice is to set warning devices to alarm at 20 to 25 percent of this lower explosive
level. Hydrogen accumulation is usually not a problem if good air circulation around a battery is
present. If relatively large batteries are confined in a small room, an exhaust fan(s) should be
used to constantly vent the room or should start automatically when hydrogen accumulation
exceeds 20 percent of the lower explosive limit. Finally, the materials used in the battery
container should be fire retardant.

             Figure 3-3. Determine the required power is a key step in the UPS selection process

  f. Determine if the availability of the selected UPS is acceptable. In managing a facility, the
availability of equipment and systems is of the utmost concern. Simply stated, availability is the
amount of time a piece of equipment is available to perform its function divided by the total time
the equipment is needed. It is also defined as “uptime” divided by “total time.” Thus, if an air
conditioner is required 12 hours each day, the availability would be 90 percent if it is out of
commission an average of 1.2 hours each day. Normally, the required availability for UPS is 98
percent. Availability is a function of reliability and maintainability. The inherent or designed-in
availability is usually expressed as follows.

                                          Ai = MTBF
                                                 MTBF + MTTR

                                                                                                                         3-7


---

TM 5-693

where:    Ai is inherent availability
          MTBF is mean time between failure (a measure of reliability)
          MTTR is mean time to repair (a measure of maintainability)

Reliability is the probability that the item will perform as intended for a specified period of time,
under a stated set of conditions. It can be expressed in terms of the number of failures in a given
time (the failure rate), or as the time between failures (for repairable items), or time to failure (for
“one-shot” or non-repairable items. Maintainability is defined as the relative ease and economy
of time and resources with which an item can be retained in, or restored to, a specific condition.
This assumes maintenance is performed by personnel having the specified skill levels, using
prescribed procedures and resources, at each prescribed level of maintenance and repair. It can
be expressed as the probability that an item can be restored to operational condition in a stated
time, the number of repairs that can be made in a specific time (repair rate), or the MTTR. From
the equation for Ai, it is obvious that availability can be increased by increasing MTBF or
reducing MTTR. For example, assume the MTBF and the MTTR of a single UPS unit are 500
hours and 20 hours, respectively. The inherent availability of a single unit configuration would
be:

          Ai =  500       = 0.962

                500 + 20

The inherent availability of a two-unit configuration where only one unit is required would be:

                                        Ai = A1 + A2 –(A1 x A2)=0.999
The inherent availability of a two-unit configuration where both units are required would be:

                                              Ai = A1 x A2 = 0.925

The availability could be increased by increasing the reliability or reducing the MTTR. The reliability
could be increased by selecting a more reliable unit, derating the unit (i.e., use a unit capable of providing
more power than needed - when used, it will be operating below its capacity thereby reducing stresses),
or use redundancy (see 3-1f). MTTR could be decreased by selecting an inherently more maintainable
system or perhaps by improving diagnostics, training, or procedures.

       (1) UPS reliability. Reliability is a function of the design of the UPS, the configuration
selected, and the parts used. The environment that the UPS is installed in also plays a role in the
reliability of the UPS. Environmental factors such as excessive heat, cold, humidity, and/or dust
can all have a significant effect on the UPS reliability. Another significant factor in UPS reliability
is the configuration. The different UPS configurations were discussed in paragraphs 2-3 and 2-4.
Redundancy reduces the overall failure rate of the UPS because one failure does not cause the UPS to
fail. The example in figure 3-4 illustrates why this so.

As discussed in paragraph 2-3c, two units may be placed in parallel where each is capable of
supplying 100 percent of the load or three units may be placed in parallel where each is capable
of carrying 50 percent of the load. The earlier case where one of two units is required is the most
reliable. This is shown through the following equations. The reliability where two of three units
are required to supply 100 percent of the needed power, is given by the following equation.

3-8


---

                                                                             TM 5-693

           Figure 3-4. Redundancy improves system reliability

Reliability = R(t) = 3e-2λt-2e-3λt

where:  λ is the failure rate of each unit and the units fail exponentially
        t is the time over which the system must operate

The reliability where one of two units is needed to supply 100 percent of the power, the reliability is
given by the following equation.

Reliability = R(t) = 2e-λt-e-2λt

Table 3-2 shows the reliability for various values of t and λ.
Where f/h is failures per hour and h is hours.

        Table 3-2. Comparison of reliability of parallel redundant and parallel configurations

        λ  t                        CONFIGURATION

        (f/h) (h)                   Parallel Redundant          Parallel
                                            (1 of 2)            (2 of 3)

        .01 1                       0.999901                    0.999705
        .02 1
        .03 1                       0.999608                    0.998839
        .01 2
        .02 2                       0.999127                    0.997431
        .03 2
        .01 3                       0.999608                    0.998839
        .02 3
        .03 3                       0.998463                    0.995508
        .01 4
        .02 4                       0.996609                    0.990221
        .03 4
        .01 5                       0.999127                    0.997431
        .02 5
        .03 5                       0.996609                    0.990221

                                    0.992592                    0.979052

                                    0.998463                    0.995508

                                    0.994089                    0.983176

                                    0.987213                    0.964531

                                    0.997621                    0.993096

                                    0.990944                    0.974556

                                    0.980598                    0.947198

                                                                                                3-9


---

TM 5-693

Redundancy is the duplication of elements in a system or installation for the purpose of
enhancing the reliability of the system or installation. The two most common redundant designs
are the isolated parallel and parallel redundant systems. See figure 3-5.

              UPS Switch ac Output                             ac Output

      UPS #1                                           UPS #1

      UPS #1                                           UPS #1

              UPS Switch

              UPS Switch

      UPS #1                                           UPS #1

Isolated Parallel Redundant System                     Parallel Redundant System

              Figure 3-5. Basic redundant UPS designs

Isolated and parallel redundant systems involve paralleling multiple power-conversion modules.
The designs are termed redundant because they contain at least one more unit than is required to
support the load. The basis for this arrangement is that if one of the power–conversion modules
fails or must be taken off line for service, the remaining unit(s) is able to support the load. This
approach can provide significant improvement to the systems reliability, but must be designed
and installed properly in order to achieve its full potential. Parallel redundant systems can
actually be less reliable if the power conversion units are not tolerant of disturbances and
overloads on their outputs. Although redundancy improves the system-level reliability, it actually
increases the total number of failures that will occur. The reason the number of failures increases
is that the number of operating modules, subsystems, or components has increased and nothing
has been done to reduce their basic failure rate. The reliability of the UPS is certainly affected by
the battery selected. In choosing an UPS, criteria that the buyer might use in evaluating the
batteries are shown in table 3-3. Reliability and availability data on UPS components can be
obtained by contacting the manufacturer or, if the information is not available, by referencing the
Institute of Electrical and Electronics Engineers (IEEE) 500. Due to the nature of their critical
loads, C4ISR systems are desired to maintain a reliability level of 99.9999 (commonly known as
the six-nine rule). This should be taken into account as one attempts to design or select an UPS
system. The selected UPS system, in combination with the overall system, should maintain
reliability level of 99.9999 or higher. Therefore, it might be necessary to design and select a
system with greater redundancy, in order to achieve the "six-nine" goal.

       (2) Maintainability. As already shown by the availability equation, reducing the time to
restore a system after it has failed is another way to increase availability. Major factors
determining the ease and economy with which maintenance can be performed are means for
identifying the component(s) that caused the system to fail (i.e., diagnostics), accessibility of
components, and skills and resources needed to repair the system (through in-place repair of the
failed component(s) or by removing and replacing them).

3-10


---

                                                TM 5-693

Table 3-3. Criteria for evaluating UPS battery

                  CRITERION                  FOR RELIABLE PERFORMANCE & LONGER LIFE
The thickness of the positive plate          Thicker is better for durability.
The material used for the battery posts      Copper inserted posts operate more efficiently and cooler,
                                             and require less frequent retorquing than do lead posts
How the batteries are tested at the plant    Cells should be tested together
Capacity at which the batteries are shipped  Anything less than 100% makes it debatable whether 100%
from the factory                             can ever be achieved
Tolerance to temperatures above 77°F         The higher, the better
Frequency at which a boost charge is         Less frequent is better
needed
Frequency at which testing is required       Less often for short times is better

            (a) Diagnostics. Identifying what has caused a system failure requires a diagnostics
capability. This capability can consist of built-in test, manual troubleshooting procedures, or
troubleshooting using external test equipment.

            (b) Accessibility. Once the component(s) that caused the system to fail are identified
through the diagnostic capability available for the system, maintenance personnel must gain
access to those components. (Access may also be an issue in performing the troubleshooting of
the system failure.) To some extent, the accessibility is determined by the installation as well as
the system design. Access to certain areas of an UPS installed in a very limited space may make
repair very difficult even though the UPS design is very maintainable.

            (c) Skills and resources. Even a system that has the most reliable and thorough
diagnostics and is designed for total accessibility will not be economical to maintain if highly
skilled personnel and extensive and expensive equipment are required. When highly skilled
personnel are required, the cost of maintenance increases, obviously. However, the consequences
go beyond the cost of actual repairs. Training costs also increase. Ideally, personnel will need
only low to moderate skills and a minimum of training (initial and recurring). Special
qualifications for UPS maintenance personnel can include fundamentals of electrical and
electronic design of UPSs, UPS testing and maintenance practices, specific maintenance training
on identical or similar equipment, UPS safety precautions, and facility-specific procedures for
operation, surveillance, and maintenance. Economical support is also difficult to achieve if many
different pieces of expensive test equipment and tools are needed to support the UPS. Ideally, the
only tools required will be common hand tools normally found in a facility maintenance shop and
the number and cost of test equipment will be minimal.

  g. Determine if the selected UPS is maintainable. Maintenance determines much of the
operating cost of an UPS. Done correctly, maintenance can ensure that the UPS stays reliable.
Poorly done, maintenance can compromise reliability and safety. A system may be inherently
maintainable (i.e., good access, good diagnostics, etc.), but other factors can determine whether or
not the system can be maintained. These factors include availability of trained personnel,
availability of spares and parts, and location of repair facilities for removed components.
Availability of personnel is a function of the total number of maintenance personnel, the hours of
facility operation (dictates the number of shifts during which maintenance personnel may be
required), and training schedules. Availability of spares (to replace removed components) and
parts (to repair in-place or removed components) depends on the total number initially procured.
Replacement and repair then depends on the rate spares and parts are purchased and the rate at
which the spares and parts become obsolete. Location of repair facilities is important because if

                                                3-11


---

TM 5-693

they are located a significant distance from the UPS, transportation may increase the time (and
the cost) to restore the UPS to operation. In many cases, the facility manager may choose to do
only that maintenance performed directly on the UPS (i.e., in-place repair and removal and
replacement) with internal resources. All other maintenance (i.e., repair of removed components)
would be done by the UPS manufacturer or a third party. Alternatively, the manager may
contract out all of the maintenance. This decision should be made primarily on the basis of cost
and availability. The cost of hiring and training personnel should be compared to that of
contracting out all or some of the maintenance. The expected number of repairs should be
considered. A study of high failure rate components and the stock levels needed to minimize
down time is also important. Another party might be able to maintain the required stock levels at
a lower cost and might be able to make repairs in a shorter time. On the other hand, many
contractors require time (typically 24 hours) to respond to a problem. This additional time may
result in large losses of revenue. Even if internal repair is more expensive, the added cost may be
more than offset by the savings in revenue.

  h. Determine if the selected UPS is affordable. Although discussed as the last step in the
selection process, affordability is often a limiting factor in the selection of an UPS. It is placed
last because the pricing of the UPS can only be done when the type, configuration, and sizing are
known. These parameters cannot be known until the steps in paragraph 3-1 have been completed.
When considering the cost of an UPS (or any product, for that matter), it is best to consider the
total cost, or life cycle cost, that will be incurred. (See figure 3-6 that describes the process for
determining affordability.) For an UPS, the total cost includes the purchase price, installation
cost, operating and support costs, and disposal costs. The acquisition and installation of the

                   Figure 3-6. Determining affordability requires that all costs be considered

3-12


---

                                                                                                                      TM 5-693

UPS typically constitute the greatest portion of the life cycle cost. A static UPS will cost between
$100 and $250,000 while the cost of a rotary ranges between $5000 and $1,000,000 for single
units. The cost of any needed auxiliary equipment must also be considered. At a minimum, a
manual bypass switch is required to disengage the UPS from the input power and load during
maintenance or repair. These switches are typically integrated into a static UPS but are stand-
alone items with rotaries. In the latter case, the switches require additional cabling and support
hardware. More sophisticated systems having automatic monitoring, switching, and control
functions requiring additional components, adding to the complexity and cost of the system(s).
As part of the installation costs, the costs associated with needed facility modifications should
also be considered. If the UPS is operated under adverse conditions, availability will suffer.
Specific precautions must be taken for dirty, hot, cold, corrosive, explosive, tropical and other
adverse conditions. Additional air conditioning might be required for the UPS (or for the facility
due to heat loads from the UPS). Rotary units may require additional or special ventilation
equipment to purge toxic fumes from working areas. Floor units (usually static UPS for computer
system backup) may require strengthening of the floor to support their weight. Large UPSs may
require the construction of a separate building to house the unit. A rotary UPS or engine
generator used in a cold climate will probably require thermostatically controlled lubricating oil,
coolant heaters, and radiator louvers. All equipment manufacturers specify the temperature
extremes, humidity, and other conditions for which the UPS was designed. Operating and
support costs of the UPS are usually secondary to the costs of purchasing and installation.
However, they can be substantial and should be included as a factor in the final selection.
Operating and support costs include cost of fuel, maintenance, replacement parts, and taxes.
Finally, when an UPS reaches the end of its life, disposal costs will be incurred. Disposal may
simply consist of dismantling the UPS and selling the parts to a recycling company or dumping it
at an approved refuse site. For UPSs containing dangerous or environmentally unsafe chemicals
or materials, disposal is much more complicated and expensive. For example, disposal of lead-
acid batteries must be performed according to all federal, state, and local regulations. Lead-acid
batteries should be reclaimed to avoid the regulatory requirements for hazardous waste treatment
and disposal facilities. Reclamation may be included as part of a procurement contract for
replacement batteries or contracts may be placed with a permitted reclaiming facility. In
disposing of spent batteries, the facility manager must ensure that batteries meet all radioactive
contamination requirements for uncontrolled release. A variety of UPS types and configurations
can be selected. The costs can vary widely depending on the specific type and configuration
selected. It is impractical to provide an all-inclusive cost comparison of all possible combinations
of types and configurations.

3-2. Static UPS system ratings and size selection

Presently, there are no standard ratings and performance characteristics for static UPS systems.
However, the typical performance specifications from various manufacturers are indicated in
tables 3-4, 3-5, and 3-6. The performance specifications are normally based on operating the
static UPS system under typical environmental conditions as shown in table 3-7. These ratings
only provide a general listing of typical ratings. The manufacturer's ratings shall be used to
determine if the UPS will perform in the specified environment. It may be necessary to derate the
equipment where the manufacturer's performance specifications are exceeded.

  a. Determining static UPS system rating. In order to properly size and select a static UPS
system, the load kVA, load power factor, inrush kVA or current, load voltage, number of phases
and frequency, and required battery protection time should be determined for the load to be
served.

                                                                                                                        3-13


---

TM 5-693

       (1) Determining load kVA. In existing installations, the load kVA should be determined by
measuring the current with all equipment operating. In three-phase installations, the load current
should be measured at each phase. The load kVA can then be estimated as follows.

                              Table 3-4. Typical rectifier/charger ratings

a.       Input

Voltage                       208, 220, 240, 380, 415, or 480 V, ± 10%, 3 phase /
                              120/220 V, ± 10%, 1phase
Frequency                     50 or 60 Hz. ± 0.5%
                              0.8
Power Factor (typical)
                              110 VDC, 220 VDC nominal
b.       Output               130VDC, 260 VDC nominal
                              ±5% adjustment
Nominal Voltage               140 VDC, 280 VDC
                              ±5% adjustment
Equalize Voltage              <2% RMS with batteries
                              1-100 hours, manual start, auto-reset
Ripple Voltage                Sized to recharge the battery in 8 to 10 hours
Equalize Timer
Capacity

                              Table 3-5. Typical inverter ratings

a.       Input

         Voltage (range)      120, 220 V ± 20%

b.       Output               120 V, single phase 280 V or 480 V, 3 phase,
                              3 or 4 wire
         Voltage              ± 2% for balanced load
                              ± 3% for 100% unbalanced loads (3 phase only)
         Voltage Regulation   ±0.5 Hz
                              0.8 to 1.0
         Sync range           ± 3% within 10 milliseconds
         Load Power factor    ± 1% within 30 milliseconds
         Transient Recovery   3% maximum single harmonic
                              5% THD maximum up to crest factor 2
         Harmonic Distortion  3% THD maximum for linear loads
                              50 or 60 Hz ±0.1%
         Frequency            500% for 1 cycle, 120% continuous
         Overload Capacity    3:1 at full load
         Crest factor

                              Table 3-6. Typical static switch ratings

Transfer Time                 0 s (Make-before-break)
Overcurrent Transfer          120% of rated full load current
Overload Capacity             1000% for 1 cycle

                              Table 3-7. Typical environmental ratings

ambient temperature range     0° to 40°C
relative humidity range       0 to 95% non-condensing
operating Altitude            0 to 1200 meters
audible noise                 <67 dB(A) at 1.5 meters

3-14


---

                                                                                   TM 5-693

Single-phase loads

kVA= VI
       1000

where: V is the system voltage in volts

I is the measured current in amperes

Three-phase loads
       kVA=1.73 VI
                   1000

where: V is the phase-to-phase voltage in volts

I is the highest measured phase current in amperes

In cases where the load current cannot be measured or when the installation is in the planning
stage, the load kVA should be calculated. Calculating the kVA requires obtaining the individual
load kVAs from equipment manufacturers' data. The total load kVA is then obtained by
vectorially adding the individual load kVAs. However, when an individual load power factor is
not available, it can be estimated from the data in table 3-8. Also, an approximate but
conservative estimate of the load kVA may be obtained by arithmetically adding the individual
load kVAs.

                    Table 3-8. Typical load power factors and inrush requirements

Type of Load                                     Power Factor  Inrush %            Duration
Induction motor or MG set                        0.75          500-800             1-30 sec.
Computer central processor unit                  0.9-0.85      600-1000            2-6 cycles
Computer peripherals                             0.8           500-800             1-30 sec.
Process instruments & controls                   0.85          300-500             2-6 cycles
Fluorescent lights (corrected type)              0.95          300-600             1 cycle
Incandescent lights                              1.0           600-1500            2-6 cycles
Regulated DC power supply (or battery charger)   0.6-0.8       600-1000            2-6 cycles
Unregulated DC power supply                      0.9           600-1000            2-6 cycles
Transformer                                      Same as load  1000                1 cycle
Magnetic line regulators (auto-transformer)      0.6-0.8       200-300             1 cycle
Ferroresonant type line                          0.5 lead
regulators (CVT)                                 to 0.5 lag    600-1000            1-3 cycles
Solenoids. Relays and Contactors                 0.5           1000                2-3 cycles

       (2) Determining load power factor. In existing installations, the load power factor should
be determined by actual measurements using a power factor meter. In cases where actual
measurements cannot be taken or when the installation is in the planning stage, the load power
factors should be calculated. To calculate the load power factor, the kVA and power factor of the
individual loads should be obtained from the equipment manufacturers' data. When a load power
factor is not available, it can be estimated from the data in table 3-8. The total load power factor
can then be calculated. Estimating the load power factor is necessary since the kVA rating and
performance parameters of most static UPS system designs are guaranteed only at a power factor

                                                                                   3-15


---

TM 5-693

range of 0.8 lagging to unity. The static UPS system kVA capacity and performance parameters
are affected at other power factors.

       (3) Determining load inrush kVA. Determination of the load inrush kVA is particularly
important for static UPS configurations without a static transfer switch and bypass capability. In
these configurations, if the load inrush kVA requirements exceed the inverter capability, the
inverter will reach the “current limit” mode causing the output voltage to drop. In configurations
with a static transfer switch and bypass capability, determining the load inrush current
requirements is required for proper selection of overcurrent protective devices for the transfer
switch and coordination with other overcurrent protective devices. The load inrush kVA or
current in existing installations should be determined by actual measurement using a high speed
storage oscilloscope or oscillograph. Since all loads are not normally started simultaneously, the
inrush kVA or current requirements should be determined by energizing the load with the highest
inrush kVA while all other loads are connected. In cases where measurements cannot be taken or
when the installation is in the planning stage, the load inrush requirements should be calculated.
Data on individual load inrush kVA and duration should be obtained from equipment
manufacturers or estimated from the data in table 3-8. The maximum inrush current and effective
inrush current can be calculated.

       (4) Load voltage, number of phases, and frequency. The load voltage and frequency
requirements determine the UPS system output voltage and frequency. Three-phase loads require
a system with three-phase output regardless of the kVA rating required. However, when all loads
are single-phase, a system with single-phase output is preferable up to a rating of 75 kVA. When
the single-phase loads are higher than 75 kVA, a system with three-phase output is normally
used. In such a case, the loads should be distributed among the three phases to minimize the
phase unbalance effects on the inverter.

       (5) Battery protection time. Battery protection time depends on the load type and
functions. Generally, a battery with a minimum protection time of one minute is necessary for
the initial operation of the inverter without support from the power supply source, i.e., during the
walk-in time. There is no upper limit for the protection time. However, other considerations may
limit the length of battery protection time. Examples are the loss of the environmental control
support, which could limit the length of a computer operation time with power loss to 5, 10, or 15
minutes. In such a case, there is no need to select a battery protection time which can extend
computer operating time beyond the time for which a computer system can operate before it must
shutdown due to overheating.

  b. Battery sizing. In order to properly size the battery, required discharge rate in kilowatt
(kW)/cell, required protection time, end of discharge voltage, and ambient temperature should be
determined.

       (1) Discharge rate. For an UPS system battery, the discharge rate should correspond to the
highest inverter input power required to produce rated output at minimum input dc voltage. The
end of discharge voltage should be equal to or higher than the minimum dc input voltage required
by the inverter to maintain rated performance. The minimum dc voltage required by the inverter
is normally published by the manufacturer. The maximum dc power required by the inverter can
be obtained from the manufacturer or can be calculated. In addition, it is recommended to
include a margin of 30 percent for the required capacity to account for load growth and battery
aging.

3-16


---

                                                                                                                      TM 5-693

       (2) Lifetime. The expected lifetime of batteries on UPS duty is usually stated in terms of
years of service on continuous charge to an end of life defined as the failure to be able to deliver a
certain percentage of rated capacity. Initial capacity (unless specified as 100 percent capacity) is
usually in the range of 90 to 95 percent of rated capacity. This will rise to 100 percent capacity in
normal service after several charge-discharge cycles. IEEE 450 recommends that a battery be
replaced when its actual capacity drops to 80 percent of rated capacity; however, some
manufacturers rate "end-of-life" at 50 percent of rated capacity. Obviously, the user needs to
check the initial capacity rating, the service life period, and the aging characteristics given in the
battery guarantee so as not to be unpleasantly surprised.

       (3) End of discharge voltage. UPS batteries are not sized on so many ampere-hours of
capacity for an 8-hour period. Battery voltage is not constant, so if the load requires a constant
power output, which most UPS applications do, the current must increase as the voltage
decreases. Consequently, the battery is sized to supply a specific kW rate (usually the maximum
inverter kW requirement without recharging) for a specific period of time (usually 5 to 15
minutes) to a minimum specific end voltage and, for lead-acid types, at a maximum specific
gravity (measured at 77°F).

            (a) Lead-acid cells. A nominal system design may utilize minimum end voltage of
1.67 to 1.75 volts per cell and a maximum specific gravity of 1.215 at 77°F. The actual end
voltage should be the voltage which the UPS manufacturer, battery manufacturer, or the system
design requires, whichever is higher. In some cases, designs provide higher end voltages to meet
design concerns. A higher specific gravity may result in a battery installation needing less space,
but results in shorter life spans and higher cell losses and float voltages. The lower end voltage
that manufacturers recommend may cause the UPS to go to static bypass or, by overstressing
battery plates, shorten the life of the battery.

            (b) Nickel-cadmium (ni-cad) cells. A nominal system design for ni-cad units will be to
a minimum end voltage of 1.14 volts at 77°F with the actual end voltage to meet both
manufacturers' and system design requirements. The specific gravity of a new cell will vary
between 1.160 and 1.190 at 77°F, depending upon the manufacturer. Lower specific gravities are
generally used in cells with larger electrolyte reserves. Higher specific gravities are typically
used for low-temperature applications. The specific gravity will decrease slowly over the years
because of evaporation and other effects, even though the surface of the electrolyte is probably
covered with a protective layer of oil. Renewal will be necessary if the specific gravity decreases
to 1.130 to 1.160, depending upon the manufacturer's instructions.

            (c) Temperature correction. Ratings are at 77°F (25°C). Therefore, to determine
specific gravity, which is temperature sensitive, a temperature correction factor must be applied.
For both lead-acid and ni-cad batteries, add one point (.001) to the hydrometer reading for every
3°F above 77°F and subtract one point for every 3°F below 77°F.

       (4) Ambient temperature. The usual controlled environment provided for batteries should
eliminate temperature correction while a 100 percent UPS inverter capacity normally allows an
adequate kW design margin. The life of a battery in comparison with an UPS system (which may
be outdated and replaced in much less time) may mean that the aging factor is not of such great
importance.

  c. Computation sheets. The typical computation sheet in appendix B is intended for
calculating the kVA rating and inrush capability of a single-phase static UPS system with static
bypass switch. The methodology used in this computation sheet can be used to develop

                                                                                                                        3-17


---

TM 5-693

computation sheets for other system configurations. For example, for a three-phase system, the
step-by-step procedure should be followed for each phase. The system kVA rating should be
three times the largest single-phase kVA obtained. For systems without a static transfer switch,
the maximum inrush current obtained should be below the value at which the system reaches the
current limit mode.

  d. Static UPS system selection criteria. Selection of a static UPS system should be in
accordance with certain criteria. The system output voltage and frequency shall be as required by
the loads. The output shall be three-phase when any of the loads is a three-phase load, otherwise
a single-phase system should be used for ratings up to 75 kVA. The system output voltage and
frequency regulation and transient response shall meet the requirements of the most power-
sensitive load(s). The system rated kVA at the specific site shall be equal to the load kVA plus a
25 to 30 percent margin. The system shall be capable of supplying the load inrush demand
without reaching the current limit mode. The battery protection time shall not be less than one
minute and shall not exceed the maximum time the load can be operated with the loss of the
environmental support equipment as specified by the equipment manufacturer (normally in the
range of 1 to 15 minutes).

3-3. Rotary UPS system ratings and size selection

Similar to static UPS systems, there are no standard ratings and performance characteristics for
rotary UPS systems. Also, since the use of rotary UPS systems is much less common, the
number of manufacturers offering rotary UPS systems is limited. Each rotary UPS system
configuration may have unique performance characteristics. Performance characteristics of
typical configurations are shown in table 3-9.

          Table 3-9. Updated typical rotary UPS ratings

Protection Time                               Induction Motor            Asynchronous motor
Voltage Regulation                      Generator/ Kinetic Battery  generator/ induction coupling
Voltage Drop or Rise for 50% Load Step
Change from Full Load                                12 s                           2 s
                                                     ±1%                           ±1%
Voltage Transient Recovery Time                ±3% @ 1.0 pf                        ±6%
Frequency Regulation                           ±4% @ 0.8 pf
Frequency Transient Recovery Time             150 ms to ±2%                      250 ms
Phase Angles, Unbalanced Loads up to               ±0.5 Hz                      ±0.5 Hz
20 Percent                                           0.5 s
Harmonic Voltage                                  120° ± 1°                        0.5 s
                                                                                120° ± 1°
                                           1.5 % THD (Ph-Ph)
                                            2.5 % THD (Ph-Ph)                   4% max.

  a. Determining rotary UPS system rating. In order to properly size and select a rotary UPS
system, the load kVA, load power factor, inrush kVA or current, load voltage, number of phases
and frequency, required battery protection time (if battery supported UPS), maximum permissible
frequency deviation (if inertia-driven UPS), and required ride-through time (if inertia ride-
through UPS) should be determined. This information can be determined in the same manner as
described in paragraph 3-2 for determining a static UPS system rating. The maximum permissible
frequency deviation and required ride-through time is required for sizing the flywheel inertia as will
be described in the following paragraph. The maximum permissible frequency deviation should
be the maximum deviation tolerated by the most sensitive load. The required ride-through time depends

3-18


---

                                                       TM 5-693

largely on the nature of the power supply source. It should be longer than the longest momentary
interruption experienced or expected at the particular installation. The longest momentary interruption
time is usually the duration of reclosing operations on the power supply distribution feeders. In
addition, the nature and percentage of non-linear loads should be determined. This is necessary
to insure that the system's level of voltage distortion when supplying such loads is acceptable.

  b. Motor and generator ratings. Motor and generator ratings and performance characteristics
are standardized by the National Electrical Manufacturers Association (NEMA) in ANSI/NEMA
Publication MG-1, 1978.

       (1) Synchronous motors. The NEMA rating structure of continuous duty synchronous
motors is based on horsepower output, maximum ambient temperature for which motor is
designed, speed at full load, frequency, number of phases, voltage, full load current, field current,
excitation voltage, power factor, and locked rotor (starting) kVA.

       (2) Induction motors. The NEMA rating structure of continuous duty induction motors is
based on horsepower output, maximum ambient temperature for which motor is designed, speed
at full load, frequency, number of phases, voltage, full load current, and lock rotor (starting) kVA.

       (3) DC motors. The NEMA rating structure of continuous duty dc motors is based on
horsepower output at base speed, maximum ambient temperature for which the motor is designed,
base speed at rated load, armature voltage, field voltage, armature load current at base speed, and
winding type - shunt, series, or compound.

       (4) Synchronous generators. The NEMA rating structure at synchronous generators is
based on kVA output, output power (kW), power factor, maximum ambient temperature for
which the generator is designed, speed, voltage, full load current, number of phases, frequency,
excitation current, and excitation voltage.

  c. Flywheel sizing. The flywheel inertia is selected such that the stored energy is sufficient to
supply the generator while operating at rated power for a duration not exceeding 0.5 second while
keeping the speed from falling to maintain the frequency drop to a maximum of 0.5 Hz. The
flywheel inertia plus the inertia of the coupled motor(s) and generator make up the total inertia of
a rotary UPS system. The flywheel inertia is usually more than 95 percent of the total inertia and
the motor's and generator's inertias can be neglected. The required flywheel inertia (WK2) can be
calculated as follows.

WK 2 = H kW x106 (0.231)(n) (lb − ft2 )

where: kW = generator rated power (kW)
         n = generator rated rotational speed (r/min)

The inertia constant (H) is determined based on the required ride-through time and minimum
frequency as follows.

       F 2
H=t  1 −  min  
          fr  
              

                                                       3-19


---

TM 5-693

where: t = required ride-through time (s)
         Fmin = minimum frequency required at the end of the ride-through time (Hz)
         fr = generator rated frequency (Hz)

Theoretically, a flywheel can be selected to provide any ride-through time. However, practical
and economical considerations limit the ride-through time to around 0.5 second. High flywheel
inertia causes a long motor starting time. During the starting time, the motor's high starting
current can cause unacceptable or excessive motor heating. Also, due to the flywheel's heavy
weight and the long starting time, special bearings and lubrication methods may be required.

  d. Rotary UPS system selection criteria. Selection of a rotary UPS system should be in
accordance with certain criteria. The system output voltage and frequency shall be as required by
the loads. The output should preferably be three-phase except for small systems (5 kVA and
smaller) where single-phase systems may be used. The system output voltage and frequency
regulation and transient response shall meet the requirements of the most power sensitive load(s).
The system rated kVA at the specific site shall be equal to the load kVA plus a 10 to 15 percent
margin. The system shall be capable of supplying the load inrush demand without voltage and
frequency deviations beyond the required tolerances. The inertia-driven ride-through
configuration should be considered at sites where the power distribution system has a high
reliability and long duration interruptions are not frequently experienced. The battery supported
inertia configuration should be considered at sites with frequent long duration power
interruptions. The battery protection time shall not be less than one minute and shall not exceed
the maximum time the load can be operated with the loss of the environmental support
equipment.

3-20


---

                                                                                                                     TM 5-693

                                     CHAPTER 4

INSTALLATION AND TESTING OF UNINTERRUPTIBLE POWER
                             SUPPLY (UPS) SYSTEMS

4-1. Construction and installation of static UPS systems

The construction and installation of the UPS are critical to its proper operation.

  a. Construction features of static systems. There are several construction features about the
UPS that contribute to the system as a whole.

       (1) Charger/inverter. In addition to the basic components of the charger/inverter, an input
transformer is normally connected at the charger for isolating the charger components from the
power source. Also, surge suppression devices are used at the input to protect the charger
components from high transient voltages. Various protective and control devices may be used on
static UPS systems including a thermal magnetic circuit breaker at the system alternating current
(ac) inputs (with indicating lights to indicate the breaker open/close position), devices to detect
and alarm loss of ac input, and devices to detect and alarm low/high charger output direct current
(dc) voltage. The power and control components are normally mounted in one or more free
standing, sheet metal cabinets. One cabinet may be adequate for smaller systems. The cabinets
are normally designed for front access. All components can be inspected or removed from the
front of the cabinet by opening a hinged door. Meters, indicating lights, control switches or
pushbuttons, and adjustment potentiometers may be located inside the cabinet or mounted on the
hinged door. A static UPS with a power range of 150 to 750 kVA is shown in figure 4-1.
Electronic control components are normally assembled in a modular construction with drawout
removable modules. The cabinet doors are provided with screened filtered openings for cooling.
Cooling may be either by natural convection or by fans. Fans are typically used in larger
systems. The cabinets are normally designed to allow power and control cables to enter from
either the top or bottom.

       (2) Batteries and racks for smaller systems. Batteries for smaller systems (50 kVA and
smaller) may be mounted in cabinets or on open racks. Batteries used in cabinets are normally
the valve regulated (VRLA) type sometimes referred to as "maintenance free” type. Also, the
individual units normally have a voltage rating of 12 volts. Battery cabinets are supplied
prewired with all inter-connections factory made. The use of battery cabinets is common for
lead-acid batteries in smaller systems and for nickel-cadmium (ni-cad) batteries. Lead-acid
batteries for larger installations are normally mounted on open racks. In open rack installations,
the individual battery cells are mounted on a rack or group of racks specially constructed for this
purpose. The racks are constructed of steel rails, frames, and braces. The battery cells rest on
plastic channels. The rack is factory painted with acid resistant paints. The racks may be of a
variety of configurations as shown in figure 4-2. The battery rack configuration is usually
determined by the cell dimensions, the number of cells, and the space available. Lead-acid cells
are connected by specially designed inter-cell connectors made of lead-plated flat copper. Ni-cad
cells can be connected by specially designed inter-cell connectors made of flat steel. Inter-tier,
inter-rack, and inter-row connectors are also specially fabricated for the cell and rack type used.

  b. Installation requirements. The static UPS system should be located indoors in a clean, dust
free, low humidity location. The charger/inverter cabinets may be located in the same room with

                                                                                                                              4-1


---

TM 5-693
the battery. However, for larger systems, it is preferable to locate the battery in a separate room
for additional safety. The charger/inverter cabinets should be located as close as practical to the
battery to minimize the voltage drop in the battery leads. Personnel access should be limited to
the battery and charger/inverter. The manufacturer’s instructions and National Electrical Code
(NEC) instructions shall be consulted for access and arrangements. The UPS cabinets should not
be located directly adjacent to office space and work areas unless provided with acoustically
treated enclosures. Although the noise level of static UPS systems is low, the humming caused
by the electromagnetic components (transformers and reactors) may be irritating. Finally, since
the static UPS system causes power supply source voltage distortion, the effect of distortion on
other equipment supplied from the same bus as the UPS system should be taken into
consideration. To eliminate the effect of voltage distortion on other equipment, it is advisable to
supply larger UPS systems by a dedicated distribution transformer whenever possible. When the
use of a dedicated transformer is not feasible and a double-ended substation is available, the loads
should be distributed between the two buses as shown in figure 4-3 to minimize the effect of
voltage distortion. By this arrangement, when the UPS goes to bypass, the loads are supplied
from a distortion free source through the transfer switch.

                        Figure 4-1. Static UPS system 150 to 750 kVA (courtesy of Liebert)
       (1) Charger/inverter cabinets. The charger and inverter cabinet assemblies shall be
installed on a level surface. The assemblies may be bolted to the floor if required by the
manufacturer. The cabinets should be in a convenient location for periodic inspection with
sufficient front clearance for front door opening and access to the cabinet internals. Sufficient

4-2


---

                                                                                                                     TM 5-693
rear and overhead clearances should also be maintained for removing rear panels when necessary
and for ventilation. The minimum clearances should be as recommended by the manufacturer.
The charger/inverter cabinets are normally factory wired. The field wiring consists of connecting the ac
input to the rectifier/charger, the alternate ac source to the bypass equipment when used, the battery
leads, and the connections to the output distribution panel. The positive and negative battery leads
should preferably be run in separate non-metallic conduits. The cables from the normal and the
alternate ac sources should also be run in separate conduits to avoid common failures. The room
temperature should be maintained below 104°F for maximum equipment life. However, when
batteries are installed in the same room as the rectifier/inverter cabinets, a lower room
temperature (approximately 77°F) is desirable. A ventilation system may be required

              Figure 4-2. Various battery rack configurations (courtesy of Excide Technologies)
                                                                                                                              4-3


---

TM 5-693

to remove the heat load generated by the UPS system and maintain the required room
temperature. The approximate heat load generated by the UPS in BTU/hr is:

     1500 x UPS kVA for systems rated up to 20 kVA
     1000 x UPS kVA for systems rated above 20 kVA

The need for a ventilation system should be determined on a case-by-case basis. Consideration
should be given to the load carrying capacity of the floor where the charger/inverter cabinets are
to be installed. Also, the availability of freight elevators with adequate capacity for moving large
systems in office buildings should be ensured.

       (2) Batteries and racks for larger systems. The battery racks should be located to allow access to
the cells for periodic maintenance. It is recommended that the battery be installed in a clean, cool, dry
location. Cells should not be exposed to heating units, strip heaters, radiators, steam pipes, or sunlight.
Any of these conditions can cause a serious electrolyte temperature variation among cells within a
battery. In large battery installations, whenever possible, a floor drain with acid or alkaline proof piping
to a collection tank (depending on the cell type used) should be located near the rack to permit draining
any electrolyte that may spill accidentally. However, it may be desirable to use a pan directly underneath
the batteries. Due to the excessive weight of lead-acid batteries, it should be ascertained that the battery
room floor has a weight carrying capacity that exceeds the load of the batteries and racks. The battery
room should be provided with sufficient ventilation to prevent hydrogen gas accumulation in the room
air. The ventilation equipment should be such that the battery room air is changed 2.5 times each hour.
The objective of the room ventilation is to keep the hydrogen concentration in the room air to less than 1
percent by volume. If it is required to establish that the ventilation of the battery room is adequate, then
it is necessary to calculate the rate of evolution of hydrogen gas in the room. The following method is
used.

             C = FC × AH × K × N
                  1000 100
                      A= C
                            0.01

Where: C     = Cubic feet of hydrogen per hour

          FC = Float current, in milliamperes per 100 AH (temperature compensated)

          AH = Ampere hours

          K  = Constant – 1 AH = 0.016 cubic feet of hydrogen

          N  = Number of cells

          A  = New air required

          0.01 = 1 percent maximum concentration of hydrogen

It is also important to maintain the average ambient room temperature at around 77°F. Higher
average ambient temperatures substantially shorten the life expectancy of lead-calcium batteries.
An average ambient temperature of 95°F shortens the life expectancy by about 50 percent. The
NEC insulation restrictions require that battery strings rated over 250 volts be installed in groups having
a total nominal voltage of not over 250 volts on any one rack. Sectionalizing protection for each 250
volt group is highly recommended. For battery strings rated under 250 volts, batteries having rubber jars
must be sectionalized into groups rated at 150 volts or less. Vented alkaline-type batteries in conductive
material jars cannot be installed with more than 20 cells (24 volts) in any one tray. For safety, an
eyewash and quick drench facilities shall be located nearby.

4-4


---

                                                                                                        TM 5-693

Figure 4-3. Double-ended substation connected in secondary selective configuration
                                                                                                                4-5


---

TM 5-693

4-2. Construction and installation of rotary UPS systems
The construction and installation of the UPS are critical to its proper operation.

  a. Construction features of rotary systems. There are several construction features about the
UPS that contribute to the system as a whole.

       (1) Motor-generators (M-G) and controls for rotary systems. The M-Gs used in rotary
UPS systems are normally of the horizontal type. The M-Gs can be built into a single frame or in
separate frames coupled together and mounted on a common base. The M-G can be mounted
without enclosures or enclosed in a sheet metal cabinet. In constructions without an enclosure,
the control and monitoring devices are installed in one or more small cabinets mounted on the
M-G frame(s). In constructions with an enclosure, the control and monitoring devices are
normally mounted in a free-standing cabinet attached to the M-G enclosure. An inertia-driven
ride-through system with a synchronous motor rotary UPS with a power range of 200 to 10,000
kVA is shown in figure 4-4. In addition to the M-G, various protective and control devices may
be used on rotary systems including a thermal magnetic circuit breaker at the ac motor input

          Figure 4-4. Rotary UPS system 200 to 10,000 kVA (courtesy of HITEC Power Protection)
(with indicating lights to indicate the breaker open/close position), an ac contactor used along
with the input circuit breaker, a thermal magnetic circuit breaker with ac contactor and indicating
lights at the generator output, and a dc contactor at the dc motor input in systems with a dc motor
and a backup battery. Relays to detect and alarm loss of ac input/output and loss of dc input in
systems with a backup battery may also be provided. The control cabinets are normally designed
for front access. All components can be operated, inspected, or removed from the front of the
cabinet by opening a hinged door. Meters, indicating lights, control switches or pushbuttons, and
adjustment potentiometers may be located inside the cabinet or mounted on the hinged door. The
cabinet doors are provided with screened filtered openings for cooling. Cooling is normally by
natural convection. Enclosure-mounted cabinets are normally designed to allow power and
control cables to enter from the top. Free-standing cabinets are designed to allow the power and
control cables to enter from either the top or the bottom. In some designs the motor and generator

4-6


---

                                                                                                                     TM 5-693

are vertically mounted on a common vertical shaft to reduce the required floor space. Reducing
the floor space may also be accomplished by stacking the motor and generator and coupling their
horizontal shafts using pulleys and belts. Some designs are also available with a common motor
and generator in one rotor to optimize the machine size.

       (2) Batteries and racks for rotary systems. Construction of rotary UPS system batteries
and racks is the same as the static UPS system batteries discussed in paragraph 4-1a(2).

  b. Installation requirements for rotary systems. The rotary UPS system can tolerate a larger
range of environmental conditions than the static UPS. The room may range from temperatures
of 5° to 40° C while operating, -20° to 80° C while not operating. The humidity may range from
0 to 95 percent non-condensing for all temperatures mentioned. The UPS is suitable for
installation in industrial electrical environments. Where applicable, the charger/inverter cabinets
should be located as close as practical to the battery to minimize the voltage drop in the battery
leads. Also, the UPS shall be close to the protected load if possible. The UPS cabinets should
not be located directly adjacent to office space and work areas unless provided with acoustically
treated enclosures.

       (1) M-G and controls installation. The M-G and cabinet assemblies shall be installed on a
level surface. The assemblies may be bolted to the floor if required by the manufacturer. The
cabinets should be in a convenient location for periodic inspection with sufficient front clearance
for front door opening and access to the cabinet internals. Sufficient rear and overhead clearances
should also be maintained for removing rear panels when necessary and for ventilation. The
minimum clearances should be as recommended by the manufacturer. The rotary UPS can
tolerate a range of temperatures of 5° to 40° C while operating, and -20° to 80° C while not
operating. However, when batteries are installed in the same room, a lower room temperature
(approximately 77°F) is desirable. The need for a ventilation system should be determined on a
case-by-case basis. Consideration should be given to the load carrying capacity of the floor
where the rotary UPS is to be installed. Also, the availability of freight elevators with adequate
capacity for moving large systems in office buildings should be ensured.

       (2) Battery and rack installation for rotary systems. Installation of rotary UPS system
batteries and racks is the same as the static UPS system batteries discussed in paragraph 4-1b(2).

4-3. Power distribution and equipment grounding and shielding requirements

An UPS system, whether static or rotary, single-phase or three-phase, has a single output. The
UPS system, however, usually supplies a variety of loads, each of which should be independently
protected so that a fault on one circuit will not cause loss of all others.

  a. Power distribution equipment. There are three critical functions of a well designed UPS ac
distribution system. First, short circuit protection of all underground conductors; second,
isolation of panel pull-down during a branch fault; and third, isolation of the critical loads from
electrical noise coupled through the static bypass. The power distribution system will usually
consist of a panelboard, with circuit-breakers or fuses to protect the individual branch circuit
conductors which will usually be run in conduits dedicated to these uninterruptible circuits.

       (1) Panelboards. A panelboard consists of a sheet steel housing containing a set of bus
bars, enclosed in a molded insulated housing, which also provides mounting for the branch circuit
protective devices. A single-phase UPS will require two bus bars while a three-phase UPS will
require three. A neutral bar, insulated from the enclosure but otherwise bare, will be provided in

                                                                                                                              4-7


---

TM 5-693

both single-phase and three-phase boards. A front panel, usually screwed to the enclosure,
contains a door for access to the protective devices while completely enclosing the wiring and
terminals.

       (2) Circuit breakers. Molded-case circuit breakers are either plugged into or bolted onto
auxiliary bus bars attached at right angles to the main bus bars. Circuit breakers may be single-
pole or two-pole in single-phase boards; three-phase boards may in addition contain three-pole
breakers. Manual switching as well as automatic overcurrent tripping of the various branch
circuits is provided by the circuit breaker, which disconnects all ungrounded circuit conductors
simultaneously.

       (3) Fused switches. As an alternative to circuit breakers, fused switches may be used. The
switch provides for manual control and the fuse provides automatic overcurrent protection.
Switches may have one, two, or three poles as with circuit breakers.

       (4) Neutral bus. An UPS system will usually supply at least some line-to-neutral loads,
and a neutral bus will be provided. This bus contains provision for both a main neutral conductor
and a grounding conductor, as well as terminations for the branch circuit neutral conductors. The
neutral bus must not be grounded to the enclosure, either accidentally or intentionally, in spite of
the provision of a grounding terminal. The neutral ground is applied at the UPS and at the bypass
source and must not be duplicated at the panelboard. Also, in a three-phase UPS system with a
transfer switch, the neutral conductor should not be opened with the transfer switch.

       (5) Coordination of protection. When a fault (or short circuit) occurs on a branch circuit,
the branch circuit breaker or fuse must isolate the fault before the UPS protective devices operate
and trip the entire system. When this condition is fulfilled, the protection system is said to be
coordinated. Fuses of different ratings can be coordinated, so a main panelboard may supply a
downstream panel if necessary, however, it rarely is necessary and should be avoided. Molded-
case circuit breakers are instantaneous in action at currents above 8 to 10 times their continuous
current rating. Since the UPS has limited output current, additional power for clearing fault
currents rapidly may be provided from an alternate high power source by the use of a static
switch. When a fault occurs on any branch circuit, the inverter reaches the current limit condition
and the bus voltage falls almost to zero, thus depriving all branch circuit loads of power. The
permissible duration of this loss of power must be longer than the clearing time of the breaker
plus the transfer switching time in the UPS if the coordination is to be obtained.

            (a) Branch circuit breakers. Branch circuit breakers are selected based upon the
voltage rating, the normal full load current of each branch circuit load (continuous and
intermittent loads), the inrush current and its duration for each branch circuit load, the maximum
time each connected load can tolerate a loss of voltage without failure (time for failure), and the
available short circuit current at the uninterruptible ac main bus through the inverter or the by-
pass circuit when a static transfer switch is used (to be obtained from the UPS system vendor or
calculated).

            (b) Fuses. Like circuit breakers fuses must have adequate voltage rating. Select the
fuse ampere rating for each branch circuit to be as close as possible to the full load current of the
connected load. Check from the fuse melting curve that the fuse melting time at a current equal
to the connected load inrush current is longer than the duration of the load inrush current. If this
condition is not satisfied, increase the fuse size as required. The branch circuit fuse with the
largest rating shall have a clearing time which when added to the static transfer switch total

4-8


---

                                                                                                                     TM 5-693

transfer time (normally 4 milliseconds (msec) or less) shall be less than the time the most critical
load can tolerate a loss of power.

  b. Grounding. The usual electrical power system utilizes two grounding methods; their
purposes are quite different. System grounding is the intentional grounding of the neutral point of
devices to provide equipment protection by suppressing transient and sustained overvoltages
caused by fault conditions. Equipment grounding is provided as protection against accidental
grounds by interconnecting a low-impedance path from all noncurrent-carrying metallic parts,
thus minimizing potential gradients while ensuring sufficient fault current to trip protective
devices.

       (1) System grounding. The neutral of a single-phase, three-wire system and of a three-
phase four-wire system should always be grounded. As explained in paragraph 4-3a(4), the
neutrals of the UPS and of the bypass source should be grounded and not the neutral bar in the
distribution panel board.

       (2) Equipment grounding. For safety reasons, all electrical equipment enclosures,
including metallic conduits, must be effectively grounded per the NEC. Although all raceways
and enclosures are bonded together to form a continuous ground path, grounding of enclosures to
the nearest ground point is recommended. The ground point may be a structural member which is
part of a bonded and grounded network of steel beams and columns, a ground conductor, or to a
ground rod driven into earth. The connection between the equipment enclosure and the ground
point should be as short as possible to achieve the maximum in noise reduction, particularly at the
higher frequencies.

       (3) Single point grounding. In addition to grounding the system neutral to facilitate ground
fault isolation and grounding the equipment enclosures to avoid the hazard of electrical shocks,
the grounding system should minimize the generation of unwanted noise. The generation of
unwanted noise can be minimized by equalizing the voltage to ground of all the system
components. This is done by establishing single-point grounding. The single-point grounding is
established by connecting the grounding conductors of all the system component enclosures to
the power source neutral grounding point as shown in figure 4-5. For the single-point grounding
system to be effective, the equipment grounding conductors should be as short as possible. This
requires that the UPS system be located adjacent to or in the same room with the supplied
equipment. In installations where this cannot be accomplished and the UPS system is located
away from the loads, an isolation transformer should be used. The isolation transformer is
interposed between the UPS output and the loads and should be located in the same room with the
supplied loads. The isolation transformer grounded secondary neutral is used as the grounding
point to connect all the equipment grounding conductors.

       (4) Ground loops and multipoint grounding. The single-point grounding system should be
used whenever feasible. However, within very large systems the use of a single-point grounding
may not be practical. The system may be made of subsystems each supplied from different
power sources with separate central grounding points. This situation is often in installations
where data terminals and remotely located printers are located outside the computer room. In
such installations the different central ground points may have different potential to ground and
ground loops are established as shown in figure 4-6. Such ground loops can create a path for

                                                                                                                              4-9


---

TM 5-693

                                      Figure 4-5. Single-point grounding example
          [Reproduced from Federal Information Processing Standards Publications (FIPS pub) 94]
unwanted noise through the data links between the different components. Ground conductors of
low resistance interconnecting the separate central grounding points shunts some of the noise
current away from the data cable as shown in figure 4-6.
  c. Computer power centers. A computer power center is a self-contained unit which can be
located in a computer room to distribute the power from the UPS system to the loads. It contains
an isolation stepdown transformer, output circuit breakers, and terminations for main input power
cable and output cables. A computer power center may also contain a power monitoring panel
which monitors the input/output power and system faults and records power disturbances. The
contained isolation transformer in a computer power center isolates noise that may be produced in
the power cable from the UPS output and allows establishing an effective single-point grounding
system. Additionally, the output cables have specially fabricated grounding wires which tie the
equipment enclosures to the single-point ground through plug-in connectors. There should be no
other grounds on the neutral conductors which must be insulated for their entire length, including
the wiring in the equipment supplied by the branch circuits.
  d. Shielding. Low-level signal cables to instruments should never be run in the same raceway
as power cables. While signal (or instrumentation) cables are usually shielded and/or twisted to
reduce noise pickup, it is practically impossible to provide shielding of power cables to eliminate
transmission of low frequency energy. Using grounded metal enclosures, such as conduit or solid
tray, for all the distribution circuits will eliminate most of the higher frequency energy radiated by
the power cables.
  e. Radio frequency interference (RFI). Shielding as described in paragraph 4-3d. above
effectively eliminates the RFI that may be caused by harmonics in the UPS output. The RFI
effects that may be caused by radiated noise from the UPS components can be minimized by
maintaining adequate space between the UPS and susceptible equipment. A spacing at

4-10


---

                                                                                                                     TM 5-693

                                      Figure 4-6.. Multipoint grounding example
          [Reproduced from Federal Information Processing Standards Publications (FIPS pub) 94]

25 feet is considered adequate in most applications. Also, a suppression plate attached to the
junction box located in the computer room for connecting the incoming power cable to the local
distribution panel can be used to attenuate the radio frequency (RF) noise which may propagate
along the incoming power cable.

  f. Noise and noise reduction methods. Noise is unwanted current and/or potential induced in
the signal cables by adjacent sources. Noise can be induced in the signal cable in the following
two modes. Differential mode, where the induced noise causes the potential of one side of the
signal path to change relative to the other side. Common mode, where the induced noise appears
between both signal leads and the common signal reference ground and causes the potential of
both sides of the signal path to change simultaneously and by the same amount relative to the
common reference ground. Noise is generally induced by electromagnetic coupling, electrostatic
coupling, and ground potential differences. Noise reduction methods are highly specialized and
are specific to the application. They also depend on the installation configuration, the proximity
and nature of sources of interference, frequency of the interference signals, etc. However, noise
can generally be reduced by providing proper grounding, avoiding ground loops, providing
electrostatic and electromagnetic shielding of signal circuits, and providing separation of circuits.
4-4. Testing and start-up
The purpose of electrical testing on systems and their components is two-fold. The first is to
check the installation of the equipment and perform component and systems tests to ensure that,
when energized, the system will function properly. The second is to develop a set of baseline test
results for comparison in future testing to identify equipment deterioration. The system should be
initially checked for damage, deterioration, and component failures using specific component

                                                                                                                             4-11


---

TM 5-693

checks, inspections, and tests defined by the equipment manufacturer. Then the interconnection
of the system components should be checked, using de-energized and energized methods, to
verify the proper interconnection and operation of the components, including on/off control,
system process interlocks, and protective relaying functions. Once the above tests are complete,
the system can be energized and operational tests and measurements should be performed. All
steps and results of the testing should be carefully documented for review and for use in the
future for comparison with the results of future tests. Many of the same component tests initially
run will be performed at regular intervals as part of a maintenance program. The new results will
be compared to the initial results, where variations may be indicative of problems like
deterioration of insulation or dirty equipment. A test program will commence after completion of
installation and will usually include field inspection and installation checks, de-energized
component testing, verify instrument and relay operation and calibration, visual check of all
wiring, continuity checking of control circuits, energized functional testing of control circuits,
megger testing of power circuits, test of power circuit phasing, energizing of equipment, and
service testing. If problems are found during the testing, an analysis should be performed, and a
repair and retest should be performed that is approved by the manufacturer, engineer, and system
operator. Many of these initial tests will be repeated periodically as part of the system
maintenance program depending on the load conditions, duty cycle, environmental conditions,
and the critical nature of the equipment. Because of this, the completeness and clarity of the test
reports is important as they supply baseline data for comparison with the results of the
maintenance tests. Many tests on electrical equipment involve the use of high voltages and
currents that are dangerous, both from the standpoint of being life hazards to personnel and
because they are capable of damaging or destroying the equipment under test. Adequate safety
rules should be instituted and practiced to prevent injury to personnel, both personnel who are
performing the tests and others who might be exposed to the hazard. Also, the test procedures
used should be designed to ensure that no intentional damage to equipment will result from the
testing process. There are four categories of tests for electrical equipment: factory, acceptance,
routine maintenance, and special maintenance. Factory tests are performed at the factory to prove
the equipment was manufactured properly and meets specific design parameters. Acceptance
tests are also proof tests performed on new equipment and systems usually after installation and
before energization. They are run to determine whether the equipment is in compliance with
specifications, to establish benchmarks for future tests, to determine the equipment was installed
without damage, and to verify whether the equipment meets its intended design operation and
limits. Routine and special maintenance tests are run after the equipment has been in service for a
certain amount of time to determine the degree of deterioration of certain equipment physical
parameters as operating time increases. Routine tests are performed on a periodic basis and
special tests are performed on defective equipment to help determine the cause of a failure and/or
the extent of the damage. The same type of tests and measurements are performed for all of the
categories using different voltage values. The acceptance tests are usually run at 80 percent and
the maintenance tests are usually run at 60 percent of the factory test voltage values to help
indicate deterioration without being destructive. The following paragraph discusses the
acceptance testing. The routine and special maintenance testing is discussed in chapter 5.
Acceptance testing is a system verification and functional performance test which should be
performed on the UPS system. These tests will include installation inspections, individual
component testing, testing on wiring, control and interlock functional checks, equipment
energization and system operating measurements, and functional checks.

  a. Installation inspection. Field inspection and installation checks include the inspection of
the component nameplates, inspection of components for damage and cleanliness, inspection of
insulators for cracking, inspection of anchorage and grounding, sizing check of fuses and
breakers, alignment and adjustment checks, mechanical operation and interlock checks,

4-12


---

                                                                                                                     TM 5-693

lubrication application, verification of insulating liquid or gas level or pressure, and verification
that local safety equipment is in place.

       (1) UPS. The UPS system shall be inspected for completeness of assembly, verification of
nameplate, sizes and settings against drawings, loose parts and insulation damage, and proper
settings.

       (2) Battery. The battery should be inspected for completeness of assembly, verification of
nameplate, sizes and connection against drawings, loose parts, leaks or damage, electrolyte level
(flooded batteries), and vents sealed and plugs installed (if applicable).

       (3) UPS switchboard. The UPS switchboard should be inspected for completeness of
assembly, verification of nameplate, sizes and settings against drawings, and loose parts and
insulation damage.

       (4) Motor inspection. The motors should be inspected for completeness of assembly,
verification of nameplate, sizes and connection against drawings, loose parts, foreign materials or
damage, check insulation type, and alignment of motor with generator.

       (5) Generator inspection. The generators should be inspected for completeness of
assembly, verification of nameplate, sizes and connection against drawings, loose parts, foreign
materials or damage, proper mounting and grounding, and alignment of motor with generator.

  b. Individual component testing. De-energized component testing typically includes megger
and insulation resistance testing of equipment and connections including grounds, turns ratio
measurements, polarity tests, power factor or dissipation factor tests, overpotential tests, contact
resistance measurements, operation time travel analysis, battery and cell voltage measurements,
charger/UPS/generator current and voltage measurements, and equipment/systems impedance or
resistance tests. The following components of the UPS system will be tested as follows.

       (1) UPS systems. The static UPS system consists of the battery charger, inverter, battery,
and static switch. In addition to these items the rotary UPS consists of a motor and a generator.
These items are individually listed.

       (2) Battery chargers. A battery charger is an electronic device that converts ac power to dc
power. The charger supplies this dc power to the battery. As with all electronic devices, this
device should not be megger tested. A visual inspection should be performed to verify the
correctness of installations, supports, grounding, and wiring. The rating nameplate should be
checked to ensure that both the ac supply to the charger and the battery to be connected
corresponds to the charger’s parameters. Check to ensure all shipping and other debris in and
around the charger cabinet are removed. Check settings of the charger and calibrate per
manufacturer’s manual to match the battery (float and equalizing levels). If the battery charger
has been factory set, check the charger float and equalizing voltage levels against drawings and
specifications. If not, set the charger float and equalizing voltage levels to those listed on
drawings and specifications. Before connecting to the battery, measure the output voltage
provided by the charger and record. Verify that all charger functions and alarms operate
correctly. Verification that the battery is connected to the battery charger properly is extremely
important. The negative wire from the negative terminal of the battery must be connected to the
negative terminal of the charger. Similarly, the positive wire from the positive terminal of the
battery must be connected to the positive terminal of the charger. As with the interconnections

                                                                                                                             4-13


---

TM 5-693

for all other equipment, the cables used should be megger tested as described in the paragraph 4-
4.a.

       (3) Inverter. The inverter is similar in construction to the charger. It converts dc power to
ac power using solid-state electronics and should generally be tested using the same methods.
Therefore, this device also should not be megger tested.

       (4) Static switch. The inverter is similar in construction to the charger and inverter. It is
constructed of solid-state electronics and should generally be tested using the same methods.
Therefore, this device also should not be megger tested.

       (5) Battery testing. The individual cell condition check includes visual inspection of cell
integrity investigating evidence of corrosion at terminals, connections, racks, or cabinet. The
general appearance and cleanliness of the battery, the battery rack or cabinet, and battery area
including accessibility should be observed. The cells should be checked for cracks in cell or
leakage of electrolyte as well as the integrity of the cover. Electrolyte should be added to any cell
in which the electrolyte level is below the top of the plates. If the battery cells are not delivered
filled, it is recommended that they be filled according to manufacturer’s recommendations before
installation on racks. Before installation, the voltage of each cell should be measured. The
voltage measured should be equal to or less than 0.05 volts below the manufacturer’s open circuit
voltage. If it is not, the manufacturer should be contacted to determine the next course of action.
The cell polarity for positive to negative connections should be checked. The battery should be
assembled as shown on drawings. Each battery cell is then checked to ensure the electrolyte level
is at the maximum level. The interconnection of the battery cells should be checked for polarity.
The connector bolts should be checked to ensure that they have been tightened to the
manufacturer’s recommended torque values. The cell internal ohmic values and the inter-cell
connection resistances are then measured. This is accomplished by applying a load across the
battery and measuring the step change in voltage and current for each cell taken between the
positive and negative terminal posts of adjacent cells as well as the battery as a whole. The
ohmic value is the change in voltage divided by the change in current. The resistance values for
each cell should be averaged and any interconnection that varies more than 10 percent or 5 µΩ
over the average should be remade and then rechecked for its resistance value. These values shall
become baseline values for comparison in future tests. The presence of flame arrestors, adequacy
of battery support racks, mounting, anchorage, grounding, and clearances, ventilation of battery
room enclosure, and existence of suitable eyewash equipment should be verified. After
completion of the above inspections the battery is ready for charging. After charging, measure
each cell voltage and total battery voltage (with charger in float mode of operation), ac ripple
current, specific gravity, electrolyte temperature (visually check fill level), overall float voltage at
the battery terminals, charger output current and voltage, and ambient temperature. Also check
the condition of ventilation and monitoring equipment and the temperature of the negative
terminal of each cell of the battery. When the battery is charged, use a voltmeter to check the
polarity of the series connections. The total voltage should be measured both across the battery
and between adjacent cells and should be compared to the specified voltage. The total voltage
should approximately be the resultant of the quantity of cells multiplied by the typical cell
voltage. A variation is an indication that the battery may be improperly assembled.

            (a) Discharge test. For the acceptance test the discharge rate should be at a constant
current or constant power load equal to the manufacturer’s rating of the battery. The charging
method used as a basis for published data is an important factor. For a stationary float
application, data based on prolonged constant potential charging should be used. If constant
current charging has been used to establish the published data, appropriate float charging

4-14


---

                                                                                                                     TM 5-693

correction factors should be obtained from the manufacturer. Note that the test discharge current
is equal to the rated discharge current divided by the temperature correction factor for the initial
electrolyte temperature. Set up a load and the necessary instrumentation to maintain the test
discharge rate determined above. Disconnect the charging source, connect the load to the battery,
start the timing, and continue to maintain the selected discharge rate. If the charging source
cannot be disconnected, the current being drawn by the load has to be increased to compensate
for the current being supplied by the charging source to the battery. Read and record the
individual cell voltages and the battery terminal voltage. The readings should be taken while the
load is applied at the beginning and at the completion of the test and at specified intervals. There
should be a minimum of three sets of readings. Individual cell voltage readings should be taken
between respective posts of like polarity of adjacent cells so as to include the voltage drop of the
inter-cell connectors. Maintain the discharge rate and record the elapsed time at the point when
the battery terminal voltage decreases to a value equal to the minimum average voltage per cell as
specified by the design of the installation times the number of cells.

            (b) Capacity check. The capacity of the battery is checked using the following
equation.

Percent capacity at the test rate at 25 ºC (77 ºF) = (ta / ts) x 100

Where: ta is the actual time of the test to specified terminal voltage as corrected for
            temperatures

            ts is the rated time to specified terminal voltage

       (6) Motor testing. Testing of motors will vary based on the size of the motor. Small size
motors, less than 200 HP require mechanical testing and insulation resistance testing (megger).
Medium size motors, between 200 and 5000 HP require mechanical testing, insulation resistance
testing (megger), and polarization index testing. Large size motors, greater than 5000 HP require
mechanical testing, insulation resistance testing (megger), polarization index testing, and
overpotential testing (Hi Pot).

            (a) Motor mechanical test. A mechanical test of the motor should be performed to
check that the motor is free from interference. This is accomplished by first uncoupling the
motor from the driven machinery. The motor shaft is then manually rotated. The shaft should
rotate freely.

            (b) Motor insulation resistance test (megger). This test is performed to ensure the
insulation has no weaknesses. The test is performed utilizing a megohmmeter, either hand or
power operated, with a voltage output of at least 1000 volts. The test should be conducted phase-
to-phase and phase-to-ground. Test duration should be one minute. The insulation resistance is
variable with temperature, thus the measured value should be corrected to the standard
temperature as required. The recommended minimum values of insulation resistance are rated
kilovolts (kV) plus 1 megohm for the stator winding (for example, 5.16 megohms for 4.16 kV
winding) and 1 megohm for the rotor winding. While this is a guideline, the manufacturer's test
manual shall include acceptance criteria for the test. Megger test are “go/no-go” tests.

            (c) Motor polarization index test. The polarization index test is an insulation
resistance test that lasts for 10 minutes. The insulation resistance is recorded after 1 minute, then
again after 10 minutes. The polarization index is the quotient of the 10-minute and 1 minute

                                                                                                                             4-15


---

TM 5-693

readings. After insulation resistance readings have been made, the test voltage is returned to zero
and the insulation is discharged.

            (d) Motor overpotential testing (Hi Pot). This test assesses the dielectric strength of
the insulation of a generator. The dc over potential test is performed by applying a voltage and
measuring the leakage current. The voltage applied during the acceptance test is a function of the
equipment voltage rating as shown by the following equation.

    dc acceptance test voltage = (2 x E + 1) x 1.7 x 0.75 kV, where E is the rated voltage in kV

The standard duration of the test is between 1 to 5 minutes. The dc acceptance test voltage is
applied to each winding separately with the other windings grounded. The voltage is applied in
steps. First, one third of the dc acceptance test voltage is applied. Leakage current readings are
taken at 1 minute intervals for a maximum of 10 minutes. Then the voltage is increased in 1 kV
intervals recording the leakage current at each step. Sufficient time shall be allowed between
steps for the leakage current to stabilize. The data shall be plotted. Any sudden changes in the
curve characteristics are an indication of impending winding failure.

       (7) Generator testing. Testing of generators will vary based on the size of the generator.
Small size generators, less than 200 HP, require mechanical testing, insulation resistance testing
(megger), no load testing, and load testing. Medium size generators, between 200 and 5000 HP,
require mechanical testing, insulation resistance testing (megger), polarization index testing, no
load testing, and load testing. Large size generators, greater than 5000 HP, require mechanical
testing, insulation resistance testing (megger), polarization index testing, overpotential testing (Hi
Pot), no load testing, and load testing.

            (a) Generator mechanical test. The clearance in the generator and exciter air gap
should be checked. Uncouple the motor from the generator. Make sure the generator set turns
over freely. Rotate the generator rotor by hand at least two revolutions to be sure there is no
interference and it turns freely. Do not apply any mechanical force to generator fan when rotating
generator rotor.

            (b) Generator polarization index test. The polarization index test is an insulation
resistance test that lasts for 10 minutes. The insulation resistance is recorded after 1 minute, then
again after 10 minutes. The polarization index is the quotient of the 10-minute and 1 minute
readings. After insulation resistance readings have been made, the test voltage is returned to zero
and the insulation is discharged.

            (c) Generator insulation resistance test (megger). This test is performed to ensure the
insulation has no weaknesses. The test is performed utilizing a megohmmeter, either hand or
power operated, with a voltage output of at least 1000 volts. The test should be conducted phase-
to-phase and phase-to-ground. Test duration should be 1 minute. The insulation resistance is
variable with temperature, thus the measured value shall be corrected to the standard temperature
as required. The recommended minimum values of insulation resistance are rated kV plus 1
megohm for the stator winding (for example, 5.16 megohms for 4.16 kV winding) and 1 megohm
for the rotor winding. While this is a guideline, the manufacturer's test manual shall include
acceptance criteria for the test. Megger test are “go/no-go” tests.

            (d) Generator over-potential test (Hi Pot). This test assesses the dielectric strength of
the insulation of a generator. The dc over potential test is performed by applying a voltage and

4-16


---

                                                                                                                     TM 5-693

measuring the leakage current. The voltage applied during the acceptance test is a function of the
equipment voltage rating as shown by the following equation.

    dc acceptance test voltage = (2 x E + 1) x 1.7 x 0.75 kV, where E is the rated voltage in kV

The standard duration of the test is between 1 to 5 minutes. The dc acceptance test voltage is
applied to each winding separately with the other windings grounded. The voltage is applied in
steps. First, one third of the dc acceptance test voltage is applied. Leakage current readings are
taken at 1 minute intervals for a maximum of 10 minutes. Then the voltage is increased in 1 kV
intervals recording the leakage current at each step. Sufficient time shall be allowed between
steps for the leakage current to stabilize. The data shall be plotted. Any sudden changes in the
curve characteristics are an indication of impending winding failure.

            (e) No load test. This test will determine whether a problem exists in the generator or
regulator system. The theory behind this test is as follows. The output voltage of a generator is
dependent on its speed, design, load, and exciter input current. If the speed and exciter input are
known, the output voltage at no load can be measured and compared to the design value. To
conduct the test, verify that the generator is shut down and connect a voltmeter to the generator
output. With no load on the generator (main breakers open) run the generator at rated speed and
measure the generator output voltage. Shut the generator down and compare the voltage reading
with the design value; if they match, the regulator is functioning properly.

            (f) Load test. Following the no load test, perform a load test turning the generator off
and attaching an ammeter to the output. Turn on the generator and add load until generator rated
power is reached. Run the generator at full load for four hours, and check the temperature to
ensure the unit is not overheating.

  c. Visual and electrical wiring inspections. The termination of each cable, shown on the
cable block and wiring diagrams, should be checked to insure each conductor matches the wiring
and schematic diagrams. This is performed by yellow lining each connection from the schematic
to the wiring diagram, visually inspecting each connection for cable number, wire number/color,
and terminal, and checking point-to-point continuity or “ringing out” each wire from end to end
including grounds.

  d. Energizing and test of the UPS system. After installation and component testing, individual
components of the UPS system should be sequentially energized from the source through the
loads. As each item is energized, control functions, interlocks, and alarms should be checked for
proper operation. Voltage, phasing, and current measurements should be made at each step. See
figure 4-7.

       (1) UPS (inverter/static switch). Verify the UPS is operational through the rectifier/battery
charger and battery, and verify the battery is charged and on float. Measure the float voltage.
Verify the UPS bus incoming breaker is open, inverters A and B breakers are open, and the static
switch is switched to inverter A. Close inverters A and B input breakers, measure inverters A and
B output voltage and read meters, and verify inverters A and B outputs are in phase. Verify static
switch is in inverter A position, open inverter A incoming breaker and verify static switch
switches to inverter B. Measure voltage and ensure a bumpless transfer is made. Close inverter
A incoming breaker and verify static switch switches to inverter A. Measure voltage and ensure a
bumpless transfer is made. Open rectifier/battery charger output breakers and battery breaker and
verify that inverts A and B trip on low voltage.

                                                                                                                             4-17


---

TM 5-693

                                                  Figure 4-7. UPS distribution panels

       (2) Loading UPS. Verify UPS is energized through static switch and all UPS loads are
connected properly and ready to start. Close the incoming breaker to the UPS bus. Close the
load breakers on the UPS bus sequentially. Measure voltage and read UPS meters at each step,
and add load until the UPS reaches normal design load.

       (3) Utility trip test. Verify the UPS is loaded and connected to the utility. Manually open
the feeder breaker and verify the battery picks up load. Measure the current. Verify the transfer
4-18


---

                                                                            TM 5-693

switch transfers to diesel generator, the diesel generator starts and picks up load, and the battery
returns to float mode. Measure voltage and current at UPS and ensure a bumpless transfer is
made. Close the utility breaker. Verify the transfer switch transfers to the utility, the battery
picks up load during transfer, the diesel generator stops, and the battery returns to float after the
utility picks up load. Measure voltage and current at UPS bus and ensure a bumpless transfer is
made.

       (4) Inverter A to inverter B loaded transfer test. Verify the UPS is loaded and connected
to the utility. Open inverter A incoming breaker and verify the static switch switches to inverter
B. Measure voltage and current at UPS bus and ensure a bumpless transfer is made. Close
inverter A incoming breaker and verify that the static switch switches to inverter A. Measure
voltage and current at the UPS bus and ensure a bumpless transfer is made.

       (5) Battery discharge test. Verify the UPS is loaded and connected to the utility, and
notify the plant of pending UPS trip. Open the diesel generator breaker and block auto and
manual start. Open the utility breaker. Verify the battery picks up load and measure battery
voltage and current. Measure the UPS voltage and current and ensure a bumpless transfer is
made. Operate the UPS from the battery until the battery minimum voltage is recorded (1 to 4
hours). Verify inverters A and B trip when the batteries reach minimum voltage. Notify the plant
of pending UPS re-energization, reclose the utility breaker, close the diesel generator breaker, and
return to auto start mode. Verify the battery is on float and charging, and measure the current.
Verify when the battery is fully charged and record time to charge.

  e. Test forms. Component and system test forms for the UPS, battery, UPS switchboard,
motor, generator, UPS loading, utility trip, inverter transfer, and battery discharge test should be
completed for each component and the system.

  f. Possible failures and corrective actions. For general assistance in resolving equipment
failures of the UPS, tables 4-1 to 4-7 may be referenced. Specific troubleshooting guides of
equipment are provided by the manufacturer.

                              Table 4-1. Circuit breaker corrective action

Circuit Breaker Problem       Areas to Check
Breakers will not close/trip  Mechanical alignment/ Interlocks
                              Relay and protective device settings and operation
Breaker trips inadvertently   Ground on cable or system
                              Relay and protective device settings and operation
                              System overload

4-5. Test equipment

The amount of test equipment available should be appropriate to the amount of local use and
should meet safety requirements. The user in some cases may have had some control over the
amount of diagnostic and monitoring equipment, plus the special tools specified for UPS systems.
In other cases, off-the-shelf equipment might have been installed. The maintenance personnel
may be primarily electrically oriented. Such personnel may have had some training on UPS
systems maintenance at one time. In some cases, highly qualified electronically oriented
technicians may be available because of the need to service computer equipment. Because of the
variations in UPS equipment and maintenance capability, a hard and fast list of recommended

                                                                                              4-19


---

TM 5-693

tools and test equipment cannot be given. Some general guidance is provided covering use of
diagnostics, maintenance personnel, and ownership of equipment. Suggested checklists on
maintenance test equipment are advisory only.

          Table 4-2. Rectifier/battery charger corrective action

Rectifier/ Battery Charger              Areas to Check
No output voltage/ current              Input voltage/ breaker
                                        Rectifier (SCR) and rectifier fuse
Low output voltage                      Input transformer
                                        Control board
High output voltage                     Dead input phase
Output voltage not adjustable           Rectifier (SCR) and rectifier fuse
High output current                     Voltage control settings or potential
Low output current                      Control board
                                        Input voltage high
                                        Voltage control settings or potential
                                        Control board
                                        Voltage control potential
                                        Control board
                                        System overload/ short
                                        Current limit setting
                                        Control board
                                        Current limit setting
                                        Control board

                               Table 4-3. Battery corrective action

Battery                                 Areas to Check
Low battery voltage/ current/ capacity  Battery and cell connections
                                        Electrolyte level
Breaker trip                            Cell voltage
                                        Cell condition, cleanliness, and age
                                        Float voltage/ current
                                        Battery room temperature
                                        Battery design versus actual load
                                        Battery/ system ground
                                        Battery / system short
                                        System overload

  a. Use of maintenance personnel. Maintenance personnel should be able to recognize that a
failure condition exists from observation of the display, alarm, diagnostics aids, and
manufacturer's support. Simple failures such as blown fuses, defective fans, normal electrical-
mechanical deficiencies, and electronic failures (i.e., printed circuit boards [PCB]) should not be
beyond the repair or replacement capability of on-site maintenance personnel. Repair of the
PCBs should be performed by the manufacturer.

  b. Use of diagnostics. Display, alarm, and diagnostic equipment are generally provided in
proportion to the cost and complexity of the UPS system. Whether personnel can repair
equipment based on the diagnostics will depend on their training. All operating and maintenance
personnel should be familiar with their display, alarm, and diagnostics aids to the extent that they

4-20


---

                                                                                TM 5-693

indicate proper operation, the need for local repair, the need for manufacturer-provided repair or
consultation, and the requirement to observe and record trends indicating a need for preventive
maintenance.

Table 4-4. Inverter/static switch corrective action

Inverters/ Static Switch                   Areas to Check
No output voltage/ current                 Input voltage/ breaker
                                           SCR or diode
Low output voltage                         Static switch
High/Low output frequency                  Constant voltage transformer
No transfer from Inverter A to Inverter B  Control boards
                                           Input voltage
                                           System overload
                                           System frequency
                                           Control board
                                           Input voltage
                                           Alternate source
                                           Frequency control setting
                                           Control board
                                           Primary/Alternate source
                                           Static switch
                                           Synchronizing circuit
                                           Control board

                                  Table 4-5. UPS system corrective action

System                                     Areas to Check
No output voltage/ current                 Incoming voltage
No transfer to Diesel generator            Circuit breakers
Low/high output voltage/ current           System components
                                           Diesel generator equipment/ breaker
Transfers not bumpless                     Transfer switch
Inadequate UPS capacity                    Incoming voltage
                                           System components
                                           Battery sizing/ capacity
                                           System sizing/ capacity
                                           Battery connection
                                           Static switch
                                           Control board
                                           UPS sizing/ capacity
                                           Battery sizing/ capacity

  c. Suggested lists of test equipment and accessories. A list of test accessories for an UPS
battery is given in table 4-8, and a list of UPS module or power converter test equipment for a
500 kVA module is given in table 4-9. Special equipment may be available or may be rented,
dependent upon the site's maintenance capabilities. Normal and safety equipment should already
be available as a part of the electrical maintenance equipment. Manufacturer's equipment should
be provided with the UPS equipment by the UPS manufacturer.

                                                                                4-21


---

TM 5-693

          Table 4-6. Motor/engine corrective action

Engine Problem                             Areas to Check
Will not start                             Starter, Battery, and connections; Fuel system, level, pump, injectors,
                                           internal engine (valves, tappets, pistons), Ignition system (gas engines)
Poor Performance / Will not handle load    Control system interlocks/permissives
                                           Fuel System and cleanliness, injectors or carburetor, internal engine,
                                           control and ignition system, System kW requirements

          Table 4-7. Generator corrective action

Generator Problem                          Areas to Check
No Output Voltage / Current                Check Stator and Rotor Continuity, Fluid diode pack, voltage regulator,
                                           Control System and interlocks
Generator Breakers will not close          Control Circuitry operation, Auto/manual sync system, generator
                                           control system
Generator will not pick up load or         Engine fuel and control system, generator voltage regulator, generator
stalls/trips                               control system, auto/manual sync system, protective device settings
Generators don’t share load                Paralleling control system
Main switchgear breaker won’t re-close on  Generator sync system, breaker sync check relay, breaker control
diesel generator powered system            circuitry.

          Table 4-8. Suggested test accessory list for battery maintenance

                                   Item                                     Disposition
Battery capacity test set                                                     Special
Battery conductance/impedance tester                                          Special
Battery lifter                                                                Special
Metering of dc (located on the rectifier charger)                             Normal
Hydrometer set                                                                Normal
Microohmmeter                                                                 Normal
Portable infrared temperature measuring device                                Normal
Terminal protective grease                                                    Normal
Thermometer set                                                               Normal
Torque wrench                                                                 Normal
Chemical-resistant gloves                                                      Safety
Goggles and face shield                                                        Safety
Protective aprons or suits and shoes                                           Safety
Rubber matting                                                                 Safety

4-22


---

                                                                            TM 5-693

Table 4-9. Suggested test equipment list for troubleshooting an UPS module

Item                                                          Disposition
Analog multimeter                                                Normal
Digital multimeter                                               Normal
Dual trace oscilloscope                                          Normal
Load bank                                                        Normal
Phase rotation meter                                             Normal
Portable ammeter                                                 Normal
Portable clamp-on current transformer                            Normal
Portable infrared temperature measuring device                   Normal
Built-in test equipment board
Diagnostic printed-circuit board (PCB) and all related parts  Manufacturer
Extender cable kit                                            Manufacturer
Capacitor shorting device                                     Manufacturer
Rubber matting
                                                                  Safety
                                                                  Safety

                                                                            4-23


---

                                                                                                                     TM 5-693

                                      CHAPTER 5

       UNINTERRUPTIBLE POWER SUPPLY (UPS) SYSTEMS
                        MAINTENANCE PROCEDURES

_____________________________________________________________

5-1. Maintenance for UPS systems

A general guide for the maintenance requirements of the UPS systems modules, static switches,
and controls is provided. Although electronic components are not subject to wear in the same
degree as electromagnetic (EM) components, they do require systematic maintenance. A
standard maintenance procedure cannot be developed for all types and sizes of UPS units. The
manufacturer's user's manual should always be consulted as to specific maintenance requirements
and troubleshooting diagnostics guidelines.

  a. Safety. Do not rely on memory. Follow the user's manual guidelines. Such guidelines
should provide safety precautions. If your user's manual limits the maintenance that can be
provided by the user, follow the manual's instructions unless general instructions are
supplemented with additional guidance. Physical maintenance or troubleshooting should only be
performed by personnel trained on the system. Operating personnel not instructed in UPS
maintenance must limit their efforts to identifying the symptoms of a fault. Always be aware of
the DANGER, as voltages within the UPS modules and associated switchgear are lethal. Lethal
voltages are present even when the output circuit breaker in the UPS is open. It is necessary to
open the circuit breaker in the distribution panel feeding the UPS and the UPS bypass circuit
breaker, plus opening the direct current (dc) link connection to the battery, before all dangerous
voltages within the UPS are eliminated. Capacitors may need to be discharged of their stored
energy. Use CAUTION when operating UPS equipment to prevent serious injury or death.

  b. Preventive maintenance. Periodic maintenance is required to maintain the integrity and
lifetime of the battery. Power electronic equipment also requires scheduled maintenance even
though solid-state devices are used. Preventive maintenance may require that the UPS system be
shut down. A transfer of the critical load which may not provide the power enhancement
capabilities of an UPS system is something that the user must tolerate in order to obtain
maximum reliability and minimize downtime and repair costs.

       (1) Records. Preventive maintenance is systematic maintenance. The objective is to
minimize equipment operating problems and prevent failures by making minor or necessary
repairs before major operating difficulties occur. The general condition of the equipment needs
to be evaluated periodically, and records need to be maintained for comparison at subsequent
inspections. Recorded information is more reliable than a maintenance technician's memory.
Records should be concise but completely describe equipment conditions. Inspection records
should provide complete information on the following topics, preferably on separate record
sheets.

            (a) Equipment record. This record should list the basic information on the equipment
itself, e.g., manufacturer's identification, style, serial, size, location, etc., and incorporate
inventory-control data for spare parts. Warranty requirements covering uninterruptible operating
conditions should be abstracted from the user's manual.

                                                                                                                              5-1


---

TM 5-693

            (b) Repair cost record. This record should provide a history of repair and associated
costs of maintenance for the UPS system. It is an essential diagnostic record for avoiding future
difficulties, especially for systems determined to be of poor quality, misapplied, or marginal for
the application.

            (c) Inspection check list. This list should provide necessary and pertinent information
on points to be checked and establish the recommended recurring dates when these checks should
be made. Since shutdown may require a sliding window period, the amount of time for which
this request must precede the shutdown window should also be stated.

            (d) Periodic maintenance schedule. This schedule provides a complete listing of the
day-to-day, weekly, monthly, and annual duties which should be reviewed on the same periodic
time basis so that potential trouble situations can be investigated and corrected as soon as
possible.

            (e) Maintenance inspection and repair records. These necessary and vital documents
should be completed in detail by the inspector or an assigned individual in the maintenance
department. Maintenance personnel usually report their findings and corrective action on
assignment sheets or job cards. Permanent records are a useful guide to each UPS system's
general condition and reliability. It is important to know the frequency and type of repair and
how often there is a need for a complete overhaul.

       (2) Use of records. These records provide for a workable preventive maintenance
program. The information obtained from the necessary periodic inspections can be quickly lost.
This is particularly true when test results are required. Unless records and data on the test and
performance of equipment are retained, the maintenance program will be defeated. Unless
records are updated at each succeeding test period, valuable information is lost. Comparative test
data materially assists an UPS specialist in defining problems, especially when test results differ
from manufacturers' recommended settings or actual factory test data. Significant changes in
comparative test data can, in general, be related to the equipment's condition.

       (3) Scheduling. Scheduling of UPS and battery maintenance is normally based on the
manufacturers' recommendations. Since an UPS system is vital to the operation of critical loads,
it may be considered advisable to provide more inspections than those the manufacturer
recommends. Certain items on the UPS should be inspected daily or weekly. This inspection can
be done by operating personnel, but data should be recorded and sent to the appropriate
maintenance point not more than 5 days after being recorded. Battery maintenance should be
done by maintenance personnel. Visual monitoring data should be recorded daily for the UPS,
and if recorded for the battery, the recorded data should be handled and sent on to the
maintenance department on a weekly basis.

       (4) Periodic system status checks. The continued monitoring of the operating status of any
electronic equipment greatly enhances the probability that failure of that equipment will be
prevented. Daily observation is advised but do not provide less than weekly checks. Personnel
involved in status monitoring should be those most concerned with the equipment's proper
functioning.

            (a) UPS systems in computer rooms. Computer room operating personnel should
become familiar with the equipment and its various operating indications. They should maintain
records on all findings or occurrences during preventive maintenance. The operating personnel
shall check all lamps on mimic bus and alarm status indicators. They shall have maintenance

5-2


---

                                                                                                                     TM 5-693

personnel replace inoperative bulbs. Also, they shall check input, output, and bypass voltages
and currents and all other system status readings and compare them to the required specifications.
A copy of the requirements which must be met, exceeded, or not exceeded should be included as
a part of the inspection checklist. Maintenance personnel shall be called to apply troubleshooting
procedures if abnormal values are indicated. Operating personnel may also ensure adequate
ventilation and cooling by checking that all fans are operational; ensure all doors, drawers, and
covers are secured; and check for unusual noises and odors.

            (b) UPS system in dedicated UPS rooms. These systems will normally have remote
displays and alarms. Display panels usually indicate problems only to the extent that they affect
computer operations. Summary alarms keep the information simple and easy to understand. A
usual system would include "on battery," "battery near discharge," "overload," and "UPS
operating abnormality." In a location where the UPS is in a dedicated room, the periodic
monitoring records of the UPS system would be provided by maintenance personnel. Computer
room operating personnel would only record battery cycling, time, discharge, overload, and
abnormality and advise maintenance personnel at the time of an alarm indication of the problem
displayed.

       (5) Major system inspections. These should be performed at least annually on small to
medium systems and semiannually on large to very large systems. By performing this type of
maintenance on a scheduled basis, it is possible to find and remedy potential problems before the
system's operation is affected. Table 5-1 provides general guidance for the major system
inspection, however, the manufacturer's recommendations should be strictly followed.

       (6) Minor system inspections. Minor system inspections should be provided either after 5
months from an annual major inspection or after 3 months from a semiannual major inspection
unless a more frequent requirement is recommended by the manufacturer. Minor system
inspections should include at least the first four items listed under major inspections. Off-line
load testing is required if major component replacements are required.

                                      Table 5-1. Major system inspection general

Perform visual checks and operational tests of all UPS equipment and associated switchgear.
Review maintenance logs and log all alarm operations and output
Complete a functional checkout and test of the UPS diagnostic systems.
Check environment, temperature, dust, moisture, room vents, etc.
Clean and tighten all power connections at the input and output terminals, at all circuit breakers, and at the terminal
posts and fuses on the rectifier and inverter legs. During the inspection, check all power cabling for abrasions and burn
spots. Visually check components for signs of overheating, swelling, leaking, etc.. Visually check printed circuit board
alignments.
Replace air filters at regular intervals. Site conditions will determine how often the filters should be replaced, but
generally, they will need to be replaced at least every 6 months in clean environments. If more frequent replacement is
required, the cleanliness of the environment should be upgraded.
Check and calibrate each system, to include switchgear and circuit breakers, meters, and alarm levels for frequency,
voltage, current, transfer, trip, alarm, etc.
Perform system and component functional tests on all UPS equipment to insure proper functioning within specified parameters.
Run all UPS system diagnostics, and correct all diagnosed problems.
Resolve any previous outstanding problems, review operation with user personnel, and report any power enhancement
or equipment operation recommended changes.
Replace control batteries at least every 2 years. If the control batteries have been used without inverter or bypass AC
power, they may need replacement sooner.

                                                                                                                              5-3


---

TM 5-693

                                      Table 5-1. Major system inspection general (Continued).
Open all doors, drawers, and covers. Perform a thorough inspection of all cabinets for foreign objects. Perform a thorough
dusting and vacuuming of all cabinet interiors. Use only rubber or plastic vacuum attachments to clean drawers and cabinets.
Except for vacuuming, never attempt to clean the UPS subassemblies. Accumulated dust or grime should only be cleaned by the
manufacturer's service representative. The exterior panels can be cleaned with a mild cleaning solution. Transparent panels
should be cleaned with a mild soap and water solution only. Restore all doors and covers to their secured condition.
Off-line load test the UPS system to ensure that the system is completely functional.
Return the UPS to service following the manufacturer's recommended start-up procedures. Make sure that no damage
to the UPS equipment or shutdown will occur because of inrush currents.

  c. Corrective maintenance. All UPSs have some degree of diagnostic capability which
usually includes some degree of battery monitoring. This diagnostic ability, along with a
systematic tracking of preventive maintenance data, will aid in locating possible internal faults
and may even help in tracking external faults. A good preventive maintenance program should
minimize the need for corrective maintenance.

  d. Recognizing impending problems. Operating personnel as well as maintenance personnel
should be made aware of the conditions which lead to problems and the clues which may point to
the beginning of troubles. Any time the environmental requirements are compromised there will
be a potential for damage. Maintenance personnel should be called to check equipment that has
not been kept clean, dry, tight, and friction free.

  e. Troubleshooting. Troubleshooting procedures covered by the user's manual address the
most common alarm conditions and assume that spare parts are available for replacement of
defective components. If following the procedure does not lead to the correction of an alarm
condition, contact the manufacturer's local service representative or field service office. Each
manufacturer has a particular system to guide the troubleshooter in the definition of a fault or the
action necessary to remove a fault condition. Fault-free recognition systems or fault charts all list
"yes" or "no" steps leading to some recommended action. Troubleshooting procedures may be
provided for problems such as overvoltage trip, undervoltage trip, battery discharge, battery
ground, battery undervoltage, clock failed, frequency failed, fuse cleared, inverter leg fuse blown,
inverter overload, inverter/rectifier overtemperature, logic failed, power supply failed, or rectifier
fuse blown. This guide is reproduced to illustrate the type and depth of information that must be
on hand prior to any attempt at troubleshooting by qualified personnel. Obtain the manufacturer's
troubleshooting guide that applies to the specific system needing repair.

  f. Spare parts availability. A spare parts inventory for the UPS equipment should have been
provided at the time of installation. Normally, the inventory level should satisfy maintenance
requirements for at least a one-year period based on the level of servicing capability of
maintenance personnel.

       (1) Spare parts levels. The basic level includes typical user-replacement items such as
fuses, capacitors, power semiconductors, and other items that may be useful at the time of
installation. Another level may include the basic level plus essential electronic control modules
and printed circuit boards. Additional items which are less frequently replaced or not as essential
to the uninterrupted operation of the UPS may also be included. The baking soda or boric acid
neutralizing agents and distilled water required for the battery electrolyte should also be available.
Spare batteries having a short shelf life (6 months) should be ordered on need.

       (2) Training levels. There are two training levels: basic, that is preventive and
troubleshooting, and advanced, that is corrective or remedial. Every user's manual will be

5-4


---

                                                                                                                     TM 5-693

structured differently. An understanding of what user personnel are permitted to do and what
requires a service representative will be different. Always refer to the user's manual for specific
directions.

            (a) Qualifications. Maintenance electricians should be specifically qualified for their
assignments. Responsible supervisors should know the capabilities and limitations of their
personnel and the equipment to be maintained and should not attempt maintenance or repair
activities for which they are not completely staffed or adequately equipped. It is important that
personnel who are to be responsible for the operation and maintenance of the complex UPS
system equipment be trained to a level at which they are comfortable with the equipment.
Without this training there is a tendency for personnel to become very apprehensive about
operating controls or opening cabinet doors if necessary.

            (b) Basic training. Personnel should be able to perform preventive maintenance
checks and first-level troubleshooting, order spare parts, and have a knowledge of the UPS
system operation, after having completed the UPS manufacturer's basic training course. Training
topics include start-up procedures, theory of operation (block diagram level), system description,
demonstration of the UPS in operation, operational characteristics, calibration and alignment
procedures, preventive maintenance, basic troubleshooting procedures, safety, and battery
maintenance.

            (c) Advanced training. This training may not be available from all manufacturers.
Personnel should be able to perform their own remedial maintenance and be fully equipped with
spare parts and testing and repair equipment to do it independently, except for occasional
telephone consultations with the manufacturer's service group. They should have a complete
knowledge of the UPS system's operation, be able to order and install replacement components,
and have completed the UPS manufacturer's advanced training course. Topics will expand on
those of the basic course and include corrective maintenance, testing and repair equipment,
schematics analysis, flowcharts, troubleshooting charts, and printed-circuit assembly repair.

5-2. UPS battery maintenance

The basic component that differentiates an UPS system from a power conditioner is the battery.
If the batteries fail before the backup generators come on line, the critical power goes down.
Improperly installed, poorly maintained, and inadequately tested batteries are common
happenings. Only the fact that the backup generators are highly reliable and come on line in a
few seconds prevents many UPS battery banks from failing long before their rated design life.
Maintenance costs and maintenance access generally are the greatest contributing factors to
poorly maintained battery systems.

  a. Maintenance costs. An UPS equipment installation cost will run $750 to $2500 per kVA.
Annual maintenance cost will run 3 to 8 percent of the installed cost for a static UPS and 1 to 2
percent of the installed cost for a rotary UPS. An UPS battery-per-cell installed cost is about $10
with an annual maintenance cost of 120 to 180 percent of the installed battery-per-cell cost.
These battery maintenance costs may appear high; but, compared to the cost of an unplanned
critical load outage, they are relatively small.

  b. Maintenance access. Redundant UPS systems having a separate but inter-tied battery per
UPS module can be maintained without taking the entire UPS system off line. A single system
battery requires an UPS system shutdown on not less than a quarterly basis. Shutdown should be
done in conjunction with the maintenance shutdown for the UPS equipment. While some battery

                                                                                                                              5-5


---

TM 5-693

maintenance service companies indicate that battery maintenance which does not require testing
can be performed without UPS shutdown, they also indicate that the battery disconnect switch
should be open. It is recommended that site maintenance personnel not provide quarterly
maintenance to the battery without an UPS shutdown.

  c. Preventive maintenance. Institute of Electrical and Electronics Engineers (IEEE) 450 and
IEEE 1106 recommend monthly, quarterly, and yearly inspections. Some manufacturers
recommend weekly inspections. The National Electrical Code (NEC) requires periodic testing on
a schedule acceptable to the authority having jurisdiction. Periodic maintenance is required and
written records of tests and maintenance must be kept. A typical lead-acid battery inspection
procedure shown in table 5-2.

       (1) Testing. Do not overtest. Frequent testing will shorten the service life. IEEE 450 and
IEEE 1106 require a performance test (a current capacity test which discharges a battery to a
designated terminal voltage to detect any change in the capacity determined by the initial test)
within the first 2 years of service and then recommends performance tests at 5-year intervals until
the battery shows signs of degradation or has reached 85 percent of the service life expected.
Degradation of lead-acid batteries is indicated when the battery capacity drops more than 10
percent of rated capacity from its capacity on a previous performance test or is below 90 percent
of the manufacturer's rating. Degradation of nickel-cadmium (ni-cad) batteries or extensive
capacity loss is indicated when the battery capacity drops more than an average of 1.5 percent per
year of rated capacity from its previous performance test capacity. Then annual performance
tests must be provided. Perform tests in accordance with IEEE 450 or IEEE 1106 requirements.

       (2) Inspections. Inspections should be made under normal conditions and performed on a
regularly scheduled basis. Tables 5-2 through 5-5 provide general checklists to be performed on
a weekly, monthly, quarterly, and annual basis. Refer to the appendices of IEEE 450 and IEEE
1106 for more information. The inspections recommended in this manual are in excess of IEEE
requirements.

                                                  Table 5-2. Weekly battery inspection

Check and record the overall float voltage at the battery terminals (not at the rectifier charger)
Measure the pilot cell voltage
Make a visual cell and rack check as to general appearance, cleanliness, cracks in cells, electrolyte leakage, or evidence of corrosion.

                                                 Table 5-3. Monthly battery inspection

Check and record the overall float voltage at the battery terminals (not at the rectifier charger)
Measure the pilot cell voltage
Make a visual cell and rack check as to general appearance, cleanliness, cracks in cells, electrolyte leakage, or evidence of corrosion.
Check rectifier
Check rectifier charger output current and voltage
Check electrolyte levels
Check ambient temperature and condition of ventilating equipment
Check pilot cell voltage, specific gravity of flooded lead-acid pilot cells, electrolyte temperature of flooded pilot cells r and terminal
temperatures of valve-regulated pilot cells
Check for evidence of voltage leaks to ground

5-6


---

                                                                                                                     TM 5-693

                                         Table 5-4. Quarterly battery inspection

Check and record the overall float voltage at the battery terminals (not at the rectifier charger)
Measure the pilot cell voltage
Make a visual cell and rack check as to general appearance, cleanliness, cracks in cell, electrolyte leakage, or evidence
of corrosion.
Check rectifier
Check rectifier charger output current and voltage
Check electrolyte levels
Check ambient temperature and condition of ventilating equipment
Check pilot cell voltage, specific gravity of flooded lead-acid pilot cells, electrolyte temperature of flooded pilot cells r
and terminal temperatures of valve-regulated pilot cells
Check for evidence of voltage leaks to ground
Check rectifier charger output current and voltage
Check electrolyte levels
Check ambient temperature and condition of ventilating equipment
Check pilot cell voltage, specific gravity of flooded lead-acid pilot cells, electrolyte temperature of flooded pilot cells r
and terminal temperatures of valve-regulated pilot cells
Check for evidence of voltage leaks to ground
Check all cell voltages, specific gravities of all flooded lead-acid cells and all terminal temperatures of valve-regulated
batteries
Check total battery voltage
Check 10 percent of inter-cell connection resistances chosen at random
Clean and provide corrosion protection of cells terminals, and racks, and add water to adjust electrolyte levels as
necessary
Provide an equalizing charge if cells are unbalanced
Analyze records and report any recommendations

       (3) Special inspections. A special inspection should be made whenever a battery
experiences an abnormal condition (such as a severe discharge or overcharge) to assure that the
battery has not been damaged. This inspection should include all the quarterly tests.

  d. Maintenance procedures. Always follow the battery manufacturer's procedures and check
warranty requirements. Manufacturers will normally provide assistance in developing a
maintenance program for their batteries. All have maintenance instructions for their cells and
some will conduct maintenance seminars or presentations. Be familiar with IEEE 450 and IEEE
1106 covering maintenance, testing, and replacement of storage batteries for lead-acid and ni-cad
types, respectively. Battery record, figure F-11 in National Fire Protection Association (NFPA)
70B is an example form to use.

       (1) Maintenance program. The maintenance program selected should address the specific
needs of the battery installed and should be both consistent and regular. Recommended
maintenance intervals should never be longer than those required by the manufacturer to satisfy
the requirements of their warranty. In addition, critical load requirements may dictate more
frequent maintenance based upon the importance of the installation and the consequences of a
failure of the battery when it is required to serve its load. Proper maintenance will ensure
optimum battery life assuming the battery has been properly sized and installed. Wherever
practicable, tests should be carried out in a manner that accomplishes one or more objectives at
once; a capacity test also can check for high connection resistance.

       (2) Battery specifics. A maintenance program must address the specific battery installed.
Although the tests and frequency of maintenance may be the same, there are subtle differences
between batteries. For example, the nominal float voltage will vary between lead-antimony and
lead-calcium cells. In addition, the total float voltage (terminal voltage) will be different for a

                                                                                                                              5-7


---

TM 5-693

188-cell UPS battery than for a 192-cell UPS battery, since the number of cells varies even
though the voltage per cell may be the same. Another consideration is that the float voltage used
will vary with the nominal specific gravity of the cell.

                                                  Table 5-5. Annual battery inspection

Check and record the overall float voltage at the battery terminals (not at the rectifier charger)
Measure the pilot cell voltage
Make a visual cell and rack check as to general appearance, cleanliness, cracks in cells, electrolyte leakage, or evidence of corrosion.
Check rectifier
Check rectifier charger output current and voltage
Check electrolyte levels
Check ambient temperature and condition of ventilating equipment
Check pilot cell voltage, specific gravity of flooded lead-acid pilot cells, electrolyte temperature of flooded pilot cells r and terminal
temperatures of valve-regulated pilot cells
Check all cell voltages, specific gravities of all flooded lead-acid cells and all terminal temperatures of valve-regulated batteries.
Check total battery voltage.
Check 10 percent of inter-cell connection resistances chosen at random.
Clean and provide corrosion protection of cells terminals, and racks, and add water to adjust electrolyte levels as necessary.
Provide an equalizing charge if cells are unbalanced.
Analyze records and report any recommendations.
Provide a detailed visual inspection of each cell
Check all bolt connections per IEEE 450 or IEEE 1106 to see if retorquing is required and retorque to the manufacturer's
specifications as required.
Check inter-cell, inter-tier, and battery terminal connection resistances.
Check integrity of the battery racks.
Record the AC ripple voltage going to the battery and ensure that the rectifier-charger filtering circuits are maintaining a ripple
output that meets the battery manufacturers' requirements on both a continuous and intermittent (spikes, transients) basis.

            (a) Battery system replacement. When a battery is replaced, the new battery often
continues to be maintained in the same manner as the old ones. However, the new battery may be
of a different alloy or nominal specific gravity or may contain a different number of cells.
Maintenance personnel may not recognize the differences, which can lead to irreversible damage.

            (b) Battery condition. Battery condition can be assessed based upon comparisons of
current data with past data. Data collected during maintenance must always be corrected to the
standard temperature reference so that meaningful comparisons between data can be made.

       (3) Remote battery monitoring systems. Battery monitoring may be performed remotely
with the installation of a battery monitoring system. These systems are able to monitor overall
string voltage, cell voltages, ambient temperature, internal cell resistance, inter-cell resistance,
and load cycles. With the installation of one of these systems, system reliability will increase due
to the constant monitoring of the system. Also, maintenance cost will be reduced, by minimizing
the required maintenance man-hours.

  e. Maintaining flooded lead-acid cells. Visual checks, various measurements, and certain
tests are used to optimize the life and performance of battery systems. Visual checks will indicate
when cleaning is necessary or when there are other problems that need to be corrected.
Measurements of voltage and specific gravity identify the condition of each cell. Battery capacity
tests and measurements are made of inter-cell connection and terminal connection resistances are
made to determine the battery system's condition. Measurements and tests are often performed
on pilot cells instead of the entire battery.

  f. Maintenance considerations. Specifics of maintenance requirements will vary because of
the battery type, the construction, and the manufacturer's requirements. However, general

5-8


---

                                                                                                                     TM 5-693

maintenance considerations are the same, except that electrolyte levels and specific gravity
requirements do not apply to valve-regulated batteries and specific gravity variations do not affect
the performance of ni-cad cells. Maintenance of a battery begins at the time of the battery
installation. The tests and data taken at that time form the base set of values for the battery to
which all future data must be referenced for later inspections.

       (1) Visual inspections. Visual inspections afford the opportunity to check cells for damage
or evidence of improper charging or other mishandling. A flashlight or other localized
unsparking light source is essential in inspecting cell components and connections and checking
for evidence of excessive gassing, mossing, sediment, and low electrolyte levels. Vibration may
be a problem. Although hydration and frozen electrolytes should not be problems, under
abnormal operating conditions such unlikely events can cause irreparable damage.

            (a) Cell inspections. The jars, plates, and connections should be closely inspected on
each cell. Jars, covers, and cover-to-jar and cover-to-post seals should be checked for cracks or
other structural damage. Failure of any seal will cause the electrolyte to seep out. A light source
can be directed through clear jars as an aid in locating cracks or structural damage to the jar or
cover and their seals; such defects should be noted, and the manufacturer should be consulted as
to remedial action. Unwrapped plates in a clear jar should be examined, as they show the
battery's condition. The color of the positive plate of a lead-acid cell will vary from light to deep
chocolate brown, and the darker the color the more likely the battery has been overcharged. The
negative plate will be gray in color, with a tendency to darken with age. Check and note any
buckling, warping, scaling, swelling, or cracking of plates. Shining a light source on the plates
may detect sulphation by reflections from any sulphate crystals on the plate edges. If visible,
inspect the connections between the plates, straps (i.e., bus bar connecting the plates to the post),
and posts for obvious abnormalities. In areas of high seismic activity, this connection sometimes
fails if acceptance seismic testing was not properly performed. Check for electrolyte spillage,
evidence of corrosion, and vent cap damage, and correct any problems. Examine cables
connecting the battery to the rectifier charger and those cables used as inter-cell or inter-tier
connectors to be sure they are putting no strain on the cell posts.

            (b) Excessive gassing. Although gassing on recharge is normal, excessive gassing can
indicate overcharging, so gassing should always be noted. Lead-acid batteries begin to gas when
cell voltage reaches approximately 2.30 volts. Outgassing, when a cell is on open circuit or on
float charge, may be an indication of high local action and undercharging. The gas coming from
the negative plate is not generated but is squeezed out of the expanding active plate material by
the sulphate formed as the cell discharges. Most local action takes place at the negative plates,
and the positive plates may remain well charged. The specific-gravity drop will not be as great as
for uniformly discharged positive and negative plates, and so using specific-gravity readings may
not detect this action. Cells which do not gas during charge may indicate problems such as
undercharge, short circuits in the cell, or impurities in the electrolyte.

            (c) Mossing. Mossing of lead-acid cells is caused by overcharging or charging at
excessively high rates. Moss shield protection may be provided by the manufacturer on the top of
the plates for some cell constructions. Mossing results from the accumulation of a sponge-like
material on top of the negative plates or straps. The material is shed predominantly from the
positive plates and is carried off by gassing, where, if deposited on the positive plates, gassing
simply washes it off again; however, if the material is deposited on the negative plates it will
adhere to these plates. Over time, the negative plates build up a deposit sufficient to bridge and
make contact with positive plates, causing partial shorts. If mossing is found during an
inspection, expect to find excessive sediment as well.

                                                                                                                              5-9


---

TM 5-693

            (d) Sediment. Observing quantity and color of sediment in clear lead-acid battery jars
also indicate the battery's condition. Excessive sediment usually indicates overcharge or charge
at excessively high rates. The sediment from a well maintained cell may look like a layer of dust
on the bottom of the jar. The sediment from a poorly maintained cell may completely fill the
space provided under the plates and will be in the form of hills under the plates. Partial short
circuits will occur when the sediment hills reach the plate bottoms. Dark or chocolate brown
sediment hills beneath the positive plates indicate continuous overcharge. A gray deposit in hills
beneath the negative plates indicates continuous undercharge. Excessive but somewhat mixed
sediment hills showing both positive and negative materials indicate the battery has probably
undergone random periods of undercharge and overcharge. Examine cells for mossing where
excessive sediment is noted. Cells should be watered when inspection reveals electrolyte levels
below the high level line. The manufacturer should be consulted immediately about cells where
the electrolyte level is below the plate tops. Water should not be added to these cells until the
manufacturer has agreed that this is the proper action or has inspected the cells and recommended
filling. Electrolyte levels below the plate tops can cause permanent cell damage, and the cell may
need to be replaced. A record of the amount of water added to each cell should be kept and
checked with the battery manufacturer's normal cell water consumption requirement. Lead-
antimony batteries normally experience an increase in water consumption with age. Water
consumption in excess of the manufacturer's requirement is an indication of overcharging. A cell
that has been recently moved or transported should not have water added until it has been placed
back on charge for a period of time as recommended by the manufacturer. If the plates were
exposed while moving cells, consult the manufacturer for recommended action. Vibration
occurring as a cell is moved will tend to free hydrogen bubbles attached to the plates and the loss
of these bubbles will cause a decrease in the electrolyte level. Once the cell is installed, the
bubbles will reappear, and the electrolyte level will increase. Never add acid (or alkali) to a cell,
nor add any additive which claims to rejuvenate cells.

            (e) Vibration. Check the surface of the electrolyte for indication of any battery
vibration. Battery life will be reduced in proportion to the length of time and action of any severe
systematic vibration. Excess sediment when there is no apparent reason for that sediment (such
as the battery has not experienced overcharging or undercharging) can indicate recurrent
vibration. Where signs indicate vibration, reexamine the battery supporting/restraining system
and eliminate this source of damaging activity.

            (f) Hydration. Overdischarge of a lead-acid battery without immediate recharge can
cause hydration. This could happen if the rectifier charger is shut down or if a lead-acid battery is
kept in storage for an extended period without recharging. The cell must be replaced if
irreversible damage is indicated, for example, by a whitish "bathtub ring" visible approximately
halfway up a clear jar. The lead and lead compounds in the cell dissolve in the water released on
overdischarge and form lead hydrate which is deposited on the separators. Thousands of short
circuits between the positive and negative plates will occur when the battery is recharged after
hydration. Hydration can also occur when a dry-charged battery is mistakenly filled with water
instead of the electrolyte solution.

            (g) Frozen electrolyte. In the required environment, it is very unlikely that the
electrolyte will freeze since nominal 1.200 specific-gravity lead-acid electrolyte only starts
forming slush at approximately -20°F. But, during discharge, a lead-acid cell's specific gravity
decreases, and there is a resultant increase in the temperature at which slush could form; freezing
would then begin at 16°F if the specific gravity decreased to 1.100. Irreparable damage occurs
when ice crystals form within the battery, even though damage may not be visible. In essence,

5-10


---

                                                                                                                     TM 5-693

the frozen electrolyte will cause the active materials to expand and lose contact with the grid.
The frozen electrolyte can also cause structural damage to the jar.

       (2) Cleaning. It is recommended that batteries be kept clean at all times. The battery cells,
battery connections, and battery vent caps shall be kept clean and free of corrosion to maximize
the battery lifetime.

            (a) Battery cells. Jars or covers should be wiped with a clean lint-free cloth or wiper
moistened with clean water. The cloth should be moistened to clean any electrolyte spilled on the
cover or jar with a suitable neutralizing agent. Wipe with a clean dry cloth or wiper once
cleaning is finished. Never use solvents, detergents, oils, waxes, polishes, or ammonia to clean
the jars, as this may cause permanent damage to the jar. Use an acid-neutralizing agent consisting
of soda solution (one pound of bicarbonate of soda to one gallon of water). Other neutralizing
agents may damage the jar.

            (b) Battery connections. Terminal posts and connections should be cleaned with a
clean lint-free cloth or wiper moistened with a suitable neutralizing agent, followed by a clean
cloth moistened with water, and finally by a dry cloth. Cleaning charged batteries could present a
safety hazard in the case of heavy corrosion. Corroded connections should be unbolted and
cleaned. Suitable means to continue service (e.g., installing jumper cells) should be arranged for
batteries which must remain in service. Normally, loss of the voltage jumpered out by removal of
the cells will not degrade the ability of the battery to supply the UPS if the number jumpered out
is in accordance with the UPS manufacturer's recommendations. Cleaning of heavily corroded
posts and connectors should follow the manufacturer's directions. Do not clean the surfaces so
rigorously that the plating is removed. A plastic bristle brush can be used. Once the connection
is clean, a thin coating of an approved corrosion inhibitor such as No-Ox-Id should be applied.
Never use anti-corrosion sprays in aerosol containers. Observe the manufacturer's recommended
torque values when remaking the connection.

            (c) Battery vent caps. Flame arrestor vent caps should be cleaned periodically by
thoroughly rinsing in clean, clear water. No solvents or detergents should be used.

       (3) Pilot cells for voltage and specific gravity measurements. One or more pilot cells may
be chosen to reduce the time necessary to perform inspections and tests while still affording the
user some degree of confidence in the battery's condition. One cell per rack section should be
chosen so that all levels are represented; otherwise, the selection is arbitrary. Some users select
pilot cells after complete sets of quarterly voltages and specific gravities are taken. Criteria for
selection include cells with the lowest specific gravity, lowest voltage, highest specific gravity,
highest voltage, or combinations of both. Pilot cells should be rotated periodically, usually on a
quarterly basis. One reason for this is to limit electrolyte loss. Whenever a cell's specific gravity
is read, some small amount of electrolyte will remain in the hydrometer after the electrolyte
which was removed from the cell for the specific-gravity reading is again returned to the cell. For
the more frequently read pilot cell, this loss of electrolyte, although very small, could ultimately
affect the cell over a long period of time, which is the reason for pilot cell rotation.

       (4) Temperature readings. Electrolyte temperatures should be read and be recorded any
time specific-gravity or voltage readings are taken. Normally, only a representative sample of
cells is checked for electrolyte temperature. IEEE 450 recommends checking every sixth cell,
even when each cell's voltage and specific gravity are read. These readings are used to correct
specific gravity, along with the electrolyte level correction, and voltage to a standard reference
temperature in accordance with instructions in IEEE 450. The standard reference temperature

                                                                                                                             5-11


---

TM 5-693

and correction for batteries not manufactured in the United States should follow the
manufacturer's recommendations. Operation of a battery on a higher or lower reference
electrolyte temperature will affect that battery's performance and life.

            (a) Differential temperature. Differential temperatures between cells can be a
problem, if the electrolyte temperature differential between any two cells is greater than 5°F.
This problem normally occurs when one portion of a battery is located near a localized heat
source such as a window that allows the sun to shine on a portion of the battery, or when a battery
rack with more than two steps or tiers is used. A battery temperature differential will cause some
cells to be overcharged and some cells to be undercharged.

            (b) Ambient temperature. Ambient temperature of the battery area should be read and
recorded periodically even where the room or area is environmentally conditioned. Battery
performance is based upon the cell electrolyte temperature, which can differ from the room
ambient. Optimum battery performance is obtained when electrolyte temperature is maintained at
77°F.

       (5) Specific-gravity readings. Specific gravity is a good indication of state-of-charge of
lead-acid cells. Corrections for electrolyte temperature and level must be applied to adjust the
specific-gravity readings to a standard reference temperature. Level corrections can vary for each
cell type and should be obtained from the manufacturer. Note that specific-gravity readings
should not be taken within 72 hours of the termination of an equalizing charge or a water
addition. Specific-gravity readings can be inaccurate where the water addition has not been
properly mixed with the existing electrolyte solution and stratification occurs.

            (a) Differences in specific gravity. Lead-antimony or lead-calcium batteries do not
always have the same nominal specific gravities even if the plate alloy is the same. Maintenance
personnel should be alerted when a battery replacement provides a different specific-gravity
requirement. New high performance stationary cells for UPS service may have nominal specific
gravities as high as 1.300. In similar cells, higher specific gravities mean higher float voltage
requirements, increased local action, and higher water consumption. Some application
considerations may also cause a manufacturer to vary the nominal 1.215 specific gravity for
stationary cells. High or low ambient temperatures are not usually found for UPS systems, but
the user should be aware of their effects on specific-gravity requirements. A higher specific
gravity electrolyte is provided when ambient temperatures are extremely low. This increases cell
performance as well as serving to lower the freezing point of the electrolyte. Similarly, in high
ambients (normally above 90°F), a lower specific gravity electrolyte is provided to reduce losses
and maintain expected life.

            (b) Comparisons. The measured specific gravity should be corrected to the reference
temperature and compared to previous data. Readings should be uniform, with a minimum
difference between the high and low readings. Where specific gravities vary considerably over
the battery, they are termed "ragged" and corrective action is required as covered in IEEE 450 and
IEEE 1106.

       (6) Voltage readings. The open-circuit voltage of a lead-acid cell is a direct function of
specific gravity and can be approximated by equation 6.1. This relationship holds for cells that
are truly open-circuited (i.e., no current flowing through the cell) and have been off charge for
more than 16 hours with a well-mixed electrolyte. A problem may be indicated if a voltage check
indicates a voltage below that expected by the following equation.

5-12


---

                                                                                                                     TM 5-693

                               Open-circuit voltage = specific gravity + 0.84

            (a) Float and equalize voltages. Float voltages are directly related to cell type and
plate alloy as well as to the specific gravity of the cell, so that the higher the specific gravity, the
higher the minimum float voltage must be. This ensures sufficient charging current is available to
overcome the increased local action. Too high a float voltage will result in overcharging and
therefore reduce battery life. A slightly higher float voltage is sometimes selected to reduce or
even eliminate the need for periodic equalizing charges for maintenance purposes. Equalizing
voltages are normally limited by system design considerations when batteries are selected and
sized.

            (b) Voltage records. Correction should be made for the electrolyte temperature and no
voltage readings should be taken within 72 hours of an equalizing charge. Voltages should also
be uniform rather than ragged, with minimum spread between the high and low readings.
Measure the terminal voltage of a battery, at the battery terminals. Measurements at the rectifier
charger are not acceptable, since the voltage drop in the cables to the battery may result in low
voltage at the battery terminals, with resultant undercharging of the battery.

       (7) Capacity tests. The only true indication of battery condition and capacity is a discharge
test. Stationary cells designed for float operation should have no more than two deep discharges
per year, and the duration of these tests, test setup, personnel requirements, etc., make frequent
testing impractical. One must also consider that the battery is not available to serve its load
during a capacity test, and so an UPS shutdown must occur or a redundant/replacement battery
will need to be provided. For these reasons, voltage and specific gravity are used to periodically
monitor the battery condition. Recognize that these readings indicate state-of-charge, but do not
indicate the capacity of the battery.

            (a) Use of capacity tests. The results of a capacity test can be used to determine the
need for a replacement battery. Currently, battery test sets are available from a number of
manufacturers, or the user can fabricate a load bank (sometimes actual loads can be used). Three
types of battery capacity tests are described in the standards, namely, acceptance, performance,
and service tests. Of these, the last two are required for normal maintenance testing.

            (b) Comparison of results. The key again is to compare the results to prior test data to
establish a trend. Battery capacity may be less than 100 percent of nameplate rating during the
first few years of operation, unless 100 percent capacity at delivery was required by the purchase
specification. The capacity (normally 90 to 95 percent of nameplate) of a new battery will rise to
its rated value after several charge-discharge cycles or after several years of float operation.

       (8) Connection resistance. This check is very important but is often neglected, even
though it can be conducted with the battery in service. The instruments normally used are those
which are used to measure a power circuit breaker's contact resistance by passing a moderate to
high current through the connection under test and measuring the voltage drop which is converted
at the meter output to microohms. These measurements are difficult to perform, especially when
the cells have multiple posts per cell and multiple inter-cell connectors per post. In these cases,
multiple measurements per cell must be made or there will be significant errors in the
measurement. The test, performed at the initial installation, should be repeated periodically and
the results compared. High connection resistance, if not detected, can cause severe damage in a
stationary cell required to discharge at a high current rate for a period of time, as in an UPS
application. High connection resistance can actually melt battery posts.

                                                                                                                             5-13


---

TM 5-693

       (9) Battery rack. Battery racks should be checked during visual inspections. Included are
checks for structural integrity, corrosion, and proper grounding.

            (a) Corrosion. The check should include an inspection of the corrosion resistant
covers (e.g., plastic channels) normally installed on the rack materials where the jars rest. Clean
any corrosion found and recoat the rack using a chemical-resistant coating, in accordance with the
manufacturer's instructions. Replace cracked or broken corrosion-resistant covers.

            (b) Seismic. Additional checks of the rails and spacers must be made, if the battery
rack is a seismic type that is designed for use in installations requiring earthquake protection.
Seismic racks use rails and spacers to prevent movement of cells during an earthquake and the
spacers function to prevent adjacent cells from knocking together. The side rails are covered by a
corrosion-resistant cover (such as a plastic channel) where they touch the jars. Check to ensure
all side rails, end rails, and spacers are in place, and bolts are properly torqued. Occasionally,
portions of the seismic equipment for the rack may be disassembled to allow maintenance to be
performed on the battery or for cell replacement. The ability of the rack to protect the battery
during an earthquake will be impaired if rack reassembly is not properly done. Consult the
manufacturer if replacement spacers are required. Spacers must be corrosion resistant and non-
swelling, such as using a styrofoam-like material. Swelling of spacers can damage the battery
jars. Recheck and retorque all rack bolts and anchoring bolts, steel plates, and welds. Note any
deficiencies and correct in accordance with the manufacturer's recommendations/drawings.

       (10) Water quality. Use of distilled or deionized water is recommended so as to eliminate
the addition of foreign contaminants which reduce cell life and performance. Otherwise, a water
quality test is necessary. This can be performed by the user or by the battery manufacturer who
will provide information on the maximum allowable impurities in the water to be used for
maintaining electrolyte levels. Water should be stored in chemically inert, nonmetallic
containers.

       (11) Test equipment. Test equipment used in battery maintenance is covered in paragraph
4-5. Periodically, recalibrate all devices as necessary. A number of new instruments are
available which can continuously monitor a battery. These are often provided for systems serving
very critical loads. One final caution is that instruments which are inserted into the electrolyte
should not be used for different battery types. For example, a hydrometer used on a lead-
antimony battery should never be used on a lead-calcium or a ni-cad battery. Such use of
equipment will cause cell contamination.

  g. Maintaining valve-regulated lead-acid cells. All the requirements given for flooded lead-
acid cells apply except the requirements for electrolyte level and specific gravity.

       (1) Differences. The valve-regulated sealed lead-acid cells differ from traditional cells in
that they are not in transparent jars; thus, plates cannot be seen, and the cell's electrolyte is not
accessible. Do not expect to install these cells and forget about them for their expected life.
Maintenance inspections are still required. Gelled electrolyte cells are normally operated in a
vertical orientation; however, some manufacturers can produce a cell which can be operated
horizontally. A seal leak may require cell replacement.

       (2) Charging. Charging considerations for valve-regulated sealed lead-acid cells are
similar to those for flooded cells, but charging voltage must be monitored more closely.
Normally, the cells operate on float charge without need for periodic equalizing charges.
Recharge times are relatively short when recharges are required. Temperature compensation of

5-14


---

                                                                                                                     TM 5-693

float voltage is more critical than for flooded cells, and a temperature-compensated rectifier
charger should be utilized.

       (3) Temperature. Failure to temperature-compensate float voltage can cause premature
cell failure. A recommended float voltage of 2.25 volts per cell at 77°F must be increased to 2.33
volts per cell if the ambient temperature is 55°F and must be decreased to 2.18 volts per cell if the
ambient temperature is 95°F (consult manufacturers for specific values for their cells). Ripple
content of the rectifier charger output must also be considered. Ripple voltage limits are specified
by some battery manufacturers on their cell data sheets. Excess ripple may reduce the expected
life of the battery, particularly when the battery has a low internal resistance.

  h. Ni-cad cells. In general, all of the procedures and tests described for flooded lead-acid cells
are valid for ni-cad batteries, except for specific gravity. The ni-cad electrolyte is a solution of
potassium hydroxide in water with a specific gravity between 1.180 and 1.200, depending upon
the manufacturer. The electrolyte does not enter into the reaction of the ni-cad cell and is
therefore not an indication of state-of-charge; thus, specific-gravity readings are not part of
normal routine maintenance. The electrolyte in a ni-cad cell will start to freeze (slush) at
approximately -40°F. Occasionally, grayish-white deposits of potassium carbonate may be seen
on the cell tops; these deposits form the electrolyte entrained in the escaping gas reacts with the
carbon dioxide in the air. This deposit is not corrosive but is a conductor when damp, and needs
to be removed from the battery.

       (1) Parameters. The flooded lead-acid material data discussed previously can be used for
maintaining ni-cad cells by changing parameters appropriate for alkaline cells. Float voltages for
ni-cad cells are significantly different from those for lead-acid cell. Although the battery terminal
voltage may be the same, the number of cells will be different since a lead-acid cell is a nominal
2-volts per cell with a ni-cad battery is a nominal 1.2-volts per cell.

       (2) Neutralizing agent. Use a boric acid solution of 7 ounces of boric acid to one gallon of
water.

  i. Safety. Every UPS battery installation presents safety hazards and safety precautions
cannot be ignored. The three major hazards are from the electrolyte in the battery, the gases
emitted by the battery, and the potential electrical hazard available from the stored energy of the
battery. Most persons trained in an electrical environment are aware that batteries are dangerous,
but need to be warned and advised again as to the extent of the hazards posed by UPS battery
systems both large and small, flooded, and valve-regulated.

       (1) Warnings. All batteries contain an acid or alkaline solution. While the gases from a ni-
cad electrolyte are not toxic, the ni-cad electrolyte is corrosive as is the dilute sulfuric-acid
electrolyte of lead-acid batteries. All batteries are capable of out-gassing.

       (2) Electrolyte hazard. Battery rooms are required by OSHA to provide quick drenching
facilities for the eyes and body within 25 feet of the work area for emergency use. Where
emergency eyewash and showers are not provided, there are many portable devices which can be
brought into a computer room. Squeeze bottles can substitute for eyewash fountains and canisters
that look much like fire extinguishers can be fitted to provide eyewash or quick drench. When
using these devices, be sure to change the water as recommended. This prevents the growth of
bacteria. Squeeze bottles are date coded and should be replaced before the expiration date. The
canister units should be exercised periodically to prevent clogging of the head so that a good flow
of water is available when it's really needed.

                                                                                                                             5-15


---

TM 5-693

       (3) Explosive gas hazard. All batteries present a potentially deadly shock hazard and
produce hydrogen gas, which is explosive in the right concentration. Therefore, there is a need
for removal of possible explosive gas buildup.

       (4) Electrical hazard. An UPS battery is operated ungrounded, so touching a live part will
not result in a shock. The real hazard exists when an accidental ground is already present and a
person touches a live part. In this case, the person completes the circuit to ground and current
will flow through the person. Sometimes personnel may recognize that the hazard exists but do
not seem concerned because the cell voltage is only 1.2 to 2 volts per cell nominal. Another
hazard is when an accidental connection between positive and negative points is such as to cause
a dangerous potential gradient.

            (a) Possible effects. Batteries used for large UPS systems often contain 188 or 192
individual cells connected in series (to form a string) representing approximately 500 volts. In
addition, multiple strings may be connected in parallel to serve an UPS system. Another fact to
consider is the short-circuit current a battery can deliver. The short-circuit capability of any
battery can be obtained from the manufacturer. For example, a battery of one manufacturer that
provides backup for a 500 kVA UPS for 15 minutes is capable of delivering approximately
23,000 amperes into a zero-resistance short circuit.

            (b) Accidental grounds. It is not uncommon to find that a ground does exist on a
battery. One way in which this occurs is that electrolyte on top of a cell will track across the
cover, down the plastic jar, and contact a metallic part of the rack. The electrolyte, being
conductive, establishes the ground path.

            (c) Normal safety procedures. When working around batteries, all normal safety
procedures should be followed, including the use of protective equipment and tools with insulated
handles. Generally, a ground detector is provided as part of the dc system, most often in the
rectifier-charger. Be certain to check the ground detector before starting work. If an
unintentional ground exists, it should be cleared before work begins.

  j. Troubleshooting. Questionable battery system performance means that all the service
checks required under annual inspections will need to be made. Generally, any cell which
demonstrates conditions beyond the manufacturer's recommended parameters should be replaced
and the system rechecked to ensure all suspect cells have been removed. Where widespread
premature battery failures are encountered, the battery manufacturer's service department should
be contacted for further instructions. If low or high float voltages, temperature variations, visual
deviations or bulges, low open-circuit voltages, and low 10 second full-load voltages all exceed
the manufacturer's parameters, the cells are probably irreparably damaged.

5-16


---

            TM 5-693

APPENDIX A
REFERENCES

Required Publications

Government Publications

Department of Commerce

  Federal Information Processing Standards (FIPS) pub 94
  Guideline of Electrical Power for ADP Installations (cited in figures 4-5, 4-6).

Non-Government Publications

American National Standards Institute (ANSI)
1430 Broadway, New York, NY 10018

  ANSI C57.110
  Recommended Practice for Establishing Transformer Capability when Supplying Non-
  sinusoidal Load Currents (1998) [cited in paragraph 2-1n(4)]

  ANSI/IEEE 519
  Recommended Practices and Requirements for Harmonic Control in Electrical Power Systems,
  (1992) (cited in table 2-2)

  ANSI/NEMA MG-1
  Motors and Generators, (1978) (cited in paragraph 3-3b)

Institute of Electrical and Electronic Engineers (IEEE)
445 Hoes Lane, P. O. Box 1331, Piscataway, NJ 08855-1331

  IEEE 446
  Orange Book, Emergency and Standby Power Systems for Industrial and Commercial
  Applications, (1996) (cited in paragraph 2-3, Table 3-1)

  IEEE 450
  Recommended Practice for Maintenance, Testing, and Replacement of Vented Lead-Acid
  Batteries for Stationary Applications, (1995) [cited in paragraphs 3-2b(2), 5-2c, 5-2c(1), 5-
  2c(2)(k), 5-2f(4), 5-2f(5)(6)]

  IEEE 500
  IEEE Guide to the Collection and Presentation of Electrical, Electronic, Sensing Component,
  and Mechanical Equipment Data for Nuclear-Power Generating Stations, (1984) [cited in
  paragraph 3-1f(1)]

            A-1


---

TM 5-693

  IEEE 1106
  Recommended Practice for Installation, Maintenance, Testing, and Replacement of Vented
  Nickel-Cadmium Batteries for Stationary Applications, (1995) [cited in paragraphs 5-2c(1), 5-
  2c, 5-2c(2), 5-2d, 5-2f(5)(b)]

National Fire Protection Association (NFPA)
One Batterymarch Park, P. O. Box 9101, Quincy, MA 02269-9101

  NFPA 70
  National Electrical Code, (1999) [cited in paragraphs 2-1n(3), 3-1e, 5-2d]

RELATED PUBLICATIONS

Government Publications

Department of the Army

  TM 5-682
  Facilities Engineering Electrical Facilities Safety, November 1983

  TM 5-683
  NAVFAC MO-116/AFJMAN 32-1083, Facilities Engineering Electrical Interior Facilities,
November 1995

  TM 5-684
  NAVFAC MO-200/AFJMAN 32-1082, Facilities Engineering Electrical Exterior Facilities,
  November 1996

  TM 5-685/NAVFAC MO-912
  Operation, Maintenance and Repair of Auxiliary Generators, August 1996

  TM 5-686
  Power Transformer Maintenance and Acceptance Testing, November 1998

  TM 5-811-2/AFM 88-9 Chap. 2
  Electrical Design Interior Electrical System, September 1983

Non-Government Publications

Institute of Electrical and Electronic Engineers (IEEE)
445 Hoes Lane, P. O. Box 1331, Piscataway, NJ 08855-1331

  IEEE 241
  Gray Book, Recommended Practice for Electric Power Systems in Commercial Buildings,
  (1990)

  IEEE 484
  Recommended Practice for Installation Design and Installation of Vented Lead-Acid Batteries
  for Stationary Applications, (1996)

A-2


---

                                                                                                                     TM 5-693

  ANSI/IEEE 944
  Recommended Practice for the Application and Testing of Uninterruptible Power Supplies for
  Power Generating Stations, (1986)

  IEEE 1100
  Recommended Practice for Powering and Grounding Sensitive Electronic Equipment, (1992)

  IEEE 1115
  Recommended Practice for Sizing Nickel-Cadmium Batteries for Stationary Applications,
  (1992)

  IEEE 1159
  Recommended Practice for Monitoring Electric Power Quality, (1995)

  IEEE 1184
  Guide for the Selection and Sizing of Batteries for Uninterruptible Power Systems, (1995)

  IEEE 1187
  Recommended Practice for Installation Design and Installation of Valve-Regulated Lead-Acid
  (VRLA) Batteries for Stationary Applications, (1996)

  IEEE 1188
  Recommended Practice for Maintenance, Testing, and Replacement of Valve-Regulated Lead-
  Acid (VRLA) Batteries for Stationary Applications, (1996)

  IEEE 1189
  Guide for the Selection of Valve-Regulated Lead-Acid (VRLA) Batteries for Stationary
  Applications, (1996)

National Electrical Manufacturer’s Association (NEMA)
2101 L Street, NW, Suite 300, Washington, DC 20037

  NEMA PE-1
  Uninterruptible Power Systems, (1993)

  NEMA PE-5
  Utility Type Battery Chargers, (1986)

National Fire Protection Association (NFPA)
One Batterymarch Park, P. O. Box 9101, Quincy, MA 02269-9101

  NFPA 70B
  Recommended Practice for Electrical Equipment Maintenance, (1996)

  NFPA 110
  Emergency and Standby Power Systems, (1996)

                                                                                                                        A-3


---

TM 5-693

Other Publications

  Baliga, B.J., M.S. Adler, R.P. Love, P.V. Gray, and N.D. Zommer
  “The Insulated Gate Transistor: A New Three-Terminal MOS-Controlled Bipolar Power
  Device,” IEEE Transactions on Electronic Devices, Vol. ED-31, pp. 821-828, 1984

  Blaabjerg, Fred, John K. Pedersen, and Ulrik Jaeger
  “Evaluation of Modern IGBT-Modules for Hard-Switched AC/DC/AC Converters,” IEEE,
  October 1995, pp. 997-1005

  Brecht, William B.
  “Life Expectancy of VRLA Batteries,” Batteries International, July 1994, pp. 40-41

  Bulik, Vince
  “Sizing a UPS System for Non-Linear Loads,” 1993 Power Distribution Conference, Solid
  State Controls, October 26, 1993

  DOE-HDBK-1084-95
  “Primer on Lead-acid Storage Batteries,” U.S. Department of Energy, Washington, D.C., 1995

  Feder, Dr. David O.
  “VRLA Cell Failures - The 60’s Revisited,” Batteries International, July 1994, pp. 44-48

  Harville, A.
  “Choosing a Secondary Battery Technology,” Powertechnics, March 1991, pp. 31-35

  Herritty, Robert
  “A Primer on Batteries”, EC&M, February 1991, pp. 20-21

  Hussain, A. J., and John Sears
  “UPS Semiconductor Technologies,” Power Quality, March/April 1997

  Ittner, David, D.
  “Selecting and Maintaining UPS Battery Systems,” Power Quality Assurance,
  January/February 1994, pp. 19-26

  Kamran, Farrukh
  “A Novel On-Line UPS with Universal Filtering Capabilities,” IEEE Transactions on Power
  Electronics, Vol. 13, No. 3, May 1998, pp. 410-418

  Key, Thomas, Lai, Jih-Sheng
  “Costs and Benefits of Harmonic Current Reduction for Switch-Mode Power Supplies in a
  Commercial Office Building,” IEEE, Inc., New York, NY, 1995

  Li, H.H., M. Trivedi, and K. Shenai
  “Dynamics of IGBT Performance in Hard- and Soft-Switching Converts,” IEEE, October 1995,
  pp. 1006-1009

  McLatcher
  “Specifying Nickel-Cadmium Batteries,” Powertechnics, February 1990, pp. 37-40

A-4


---

                                                                                                                   TM 5-693

Migliaro, Marco
“Considerations for Selecting and Sizing Batteries,” IEEE Transactions on Industry
Applications, Vol. IA-23, No. 1, January/February 1987, pp. 134-143
Migliaro, Marco
“Maintaining Station Batteries,” IEEE Transactions on Industry Applications, Vol. IA-23, No.
4 July/August 1987, pp. 765-772
Motto, Eric R., John F. Donlon, Stashi Mori, and Takhiko Iida
“New Process Technologies Improve IGBT Efficiency,” IEEE, October 1995, pp. 991-996
Reeves, Mark
“IGBTs,” Power Technics, August 1990, pp. 12-16
Sammuli, Lynn
“Harmonics Can Affect a UPS,” Electrical Design and Installation, June 1991, pp. 18-23
Santini, John
“Specifying Power Supplies,” Powertechnics, January 1991, pp. 25-
Smith, K.M.
“Intelligent Magnetic-Amplifier-Controlled Soft-Switching Method for Amplifiers and
Inverters,” IEEE Transactions on Power Electronics, Vol. 13, No. 1, January 1998, pp. 84-92
VanDee, Dawn
“Rounding Up Rotary UPS Features,” EC&M, March 1999, pp. 54-55
VanDee, Dawn
“Understanding UPS Techno-Babble,” EC&M, November 1998, pp. 80-87
Windhorn, Allen
“A Hybrid Static/Rotary UPS System,” IEEE Transactions on Industry Applications, Vol. 28,
No. 3, May/June 1992, pp. 541-545
Yarpezeshkan, Hassan
“Selecting the Battery for UPS Applications,” Powertechnics, October 1989, pp38-42

                                                                                                                     A-5


---

                                                                                                                     TM 5-693

                                     APPENDIX B

SELECTING AN UNINTERRUPTIBLE POWER SUPPLY (UPS): AN
                                       EXAMPLE

The following example illustrates the use of the selection process described in this handbook.
Please note that no one example can serve as the model or template for every possible case. Each
case in which an UPS is being selected for a specific facility is unique and the specifics of the
process will vary. All figures are for purposes of the example and should not be considered
indicative of actual costs.

John Public, who will be the facility manager for the new Eastville plant, now in planning, of ABC,
Inc., is selecting the UPS to be installed in the plant. With the aid of his engineering staff, Mr.
Public has gone through each of the steps of the process. Following is a summary of how each
step was accomplished.

  1. Determine the need for UPS. Mr. Public knows that many of the electrical loads are critical
and even a lapse in power of 5 seconds could result in damage to very expensive processing
equipment and could lead to injuries to operators. He is also aware of governmental regulations
that require that lighting for evacuations and for other functions must be available in the event of
a loss of power. Clearly, an UPS is needed.

  2. Determine the purpose of UPS. Based on discussions with his engineers and production
personnel, the following purposes were identified for the UPS.

         • Power lighting for evacuation, security, and facilitate orderly shutdown.
         • Continue heating, ventilation, and air-conditioning (HVAC) functions for selected

              equipment to facilitate orderly shutdown. Shutdown of the entire plant could take as
              much as 2-3 hours.
         • Provide power to critical processing functions and controls until orderly shutdown
              can be completed.
         • Continue fire protection in the event of a loss of power.
         • Provide communications (paging within plant).

  3. Determine the power requirements. Mr. Public’s engineers have calculated the total power
requirements for the UPS to be 1000 kVA. But Mr. Public is concerned about growth. He
decides to add a 12.5 percent “cushion” to allow for growth. The engineers endorse this approach
to cover overvoltages and other anomalies. So the total power required is 1250 kVA. At a power
factor of .80, this is equivalent to 1000 kilowatt (kW).

  4. Select the type of UPS. A diesel generator is selected for the UPS. Diesels start quickly,
are reliable, can provide the needed power for as long as necessary, and are easy to maintain. The
UPS should be on-line. Based on discussions with his staff, Mr. Public knows that an on-line
system is the best choice for providing the maximum possible protection for critical loads. The
efficiency of the diesel generator is about 93 percent. Mr. Public was advised by his staff that a
high efficiency means less heat will be generated by the UPS. The result will be increased battery
life, higher reliability, and decreased cooling requirements.

                                                                                                                        B-1


---

TM 5-693

  5. Is safety of selected UPS acceptable? The diesel generator will be located outside of the
main plant. Personnel will be isolated from the noise of the diesel. Separate HVAC will ensure
that exhaust and battery fumes (the battery is vented) are properly vented and that the battery will
not be operated at temperatures above 25°C. The engine is a proven-design, used for many years
in similar applications, and has a good safety record.

  6. Is selected UPS availability acceptable? The UPS can start, come up to speed, and take up
the load within 3 seconds. The reliability of the UPS in previous applications is equivalent to
about a 200-hour mean time between maintenance (MTBM). Preventive maintenance procedures
were developed using a reliability-centered maintenance (RCM) approach and allows
maintenance personnel to keep the unit in “like-new” condition with a minimum of expense. The
average time to repair a failure is less than 5 hours, so the availability is .9756.

  7. Is selected UPS maintainable? As already stated, the diesel generator has a proven record
of low maintenance and has excellent preventive maintenance procedures. Since ABC, Inc.,
operates and maintains its own fleet of diesel-powered trucks, and will operate and maintain
many alternating current (AC) motors in the plant, Mr. Public feels that maintenance can be done
internally. Major repairs, such as overhauls, will be outsourced.

  8. Is cost of UPS acceptable? The price of the diesel generator is $60,000 and construction of
a separate building will cost $250,000. So the total acquisition cost is $310,000. Operating and
maintenance costs are estimated by Mr. Public’s staff to be $30,000 over 15 years. This estimate
is based on an MTBM of 200 hours, fuel consumption of 70 gallons per hour, labor costs of $25
per hour, and a conservative forecast of 20 operating hours per year. All figures are in constant
calendar year 1998 dollars. Of the total budget for constructing and outfitting the new plant,
$350,000 was allocated for the UPS, therefore, the total acquisition cost is acceptable. Mr. Public
knows that similar plants within ABC, Inc., spent about $25,000 last year on all maintenance. He
estimates that maintenance for the new plant, excluding the UPS, will take about $22,500 per
year. That would mean the total cost per year with the UPS operating and maintenance costs
included would be about $24,500. Disposal costs are considered negligible, since some of the
costs can be recouped through sale of the UPS for parts and scrap. Mr. Public is concerned about
the estimate because it only has $500 of “wiggle room.” He decides to a look at an alternate
UPS. Back to step 4.

B-2


---

          TM 5-693

GLOSSARY

Section I
Abbreviations

ac
Alternating Current

AGM
Absorbed (or Absorptive) glass mat

ANSI
American National Standards Institute

C4ISR
Uninterruptible Power Supply System Selection, Installation, and Maintenance for Command,
Control, Communications, Computer, Intelligence, Surveillance, and Reconnaissance (C4ISR)
Facilities

CBEMA
Computer Business Equipment Manufacturers Association

dc
Direct Current

EM
Electromagnetic

FCC
Federal Communications Commission

FET
Field Effect Transistors

GTO
Gate Turn Off

HVAC
Heating, Ventilation, and Air Conditioning

IEC
International Electrotechnical Commission

IEEE
Institute of Electrical and Electronic Engineers

IGBT
Insulated Gate Bipolar Transistors

          G-1


---

TM 5-693

IITRI
IIT Research Institute

ITIC
Information Technology Industry Council

kW
Kilowatt

MDT
Mean Downtime

M-G
Motor-Generator

MOSFET
Metal Oxide Field Effect Transistor

ms
Millisecond

MTBD
Mean Time Between Demand

MTBF
Mean Time Between Failure

MTTF
Mean Time To Failure

MTTR
Mean Time To Repair

MVA
Mega Volt Amperes

NEC
National Electrical Code

NEMA
National Electrical Manufacturer’s Association

NFPA
National Fire Protection Association

Ni-Cad
Nickel-Cadmium

PCB
Printed Circuit Board

G-2


---

                                                                                                                     TM 5-693

PWM
Pulse Width Modulation

RF
Radio Frequency

RFI
Radio Frequency Interference

RMS
Root Mean Square

rpm
Revolutions Per Minute

SCR
Silicon Controlled Rectifier

SLA
Sealed Lead-Acid (also see VRLA)

THD
Total Harmonic Distortion

TM
Technical Manual

UL
Underwriters Laboratories

UPS
Uninterruptible Power Supply

VRLA
Valve Regulated Lead-Acid

Section II
Terms

Absorbed (or Absorptive) Glass Mat (AGM)
In an AGM cell, the electrolyte is absorbed and held in place with a microfibrous silica glass mat
sandwiched between the plates. The electrolyte is and remains liquid for the entire battery life.
The glass mat is only about 90 percent saturated with electrolyte, therefore, oxygen produced
during charge can readily migrate to the negative plate and recombine into water. This
recombination mechanism, along with charge voltage control, substantially eliminates water loss,
making the AGM batteries as non-spillable and maintenance-free as possible. Properly
supported, AGM batteries with absorbed electrolyte can be installed and operated on their side.

                                                                                                                        G-3


---

TM 5-693

Active Redundancy
[see Redundancy (active)]

Alternate Power Source
[see Power Source (alternate)]

Availability
In its simplest definition, availability is uptime divided by downtime. In terms of reliability
(MTBF or MTBD) and maintainability (MTTR or MDT), inherent and operational availability
are defined as:

                                         Inherent availability = Ai = MTBF
                                                                          MTBF + MTTR
                                                                               MTBD

                                   Operational availability = Ao =
                                                                          MTBD + MDT

Backup Time
Time during which the UPS can supply the rated load with nominal-quality power while the
mains are down. This time depends on the battery and the efficiency of the UPS. Typical backup
ranges from five minutes to several hours.

Battery
A device that converts chemical energy into electrical energy by means of an electrochemical
reaction. Usually defined as consisting of two or more cells, but commonly used to refer to one
cell.

Battery (flooded cell)
An electrolyte filled vented cell.

Battery (recombination)
Battery with a gas recombination rate at least equal to 95 percent, i.e., no water need be added
over battery life. Usually called “maintenance free.”

Battery (tier-mounted)
Battery cell installation system whereby the cells are placed on tiers made of insulating material.

Battery (vented cell)
The battery cells are equipped with a filling port for distilled, demineralized water used to top up
the free electrolyte.

Battery Cells
The interconnected battery elements that supply electrical power created by electrolytic reaction.

Battery Circuit Breaker
[see Circuit Breaker (battery)]

Battery Monitor
Battery monitoring and protection system developed and patented by MGE UPS SYSTEMS for
UPS systems. It incorporates software to calculate the real available backup time, predicts when
batteries need replacement, and is a protection system against excessive discharges.

G-4


---

                                                                                                                     TM 5-693

Battery on Shelves
Battery cell installation system whereby the cells are placed on several vertically stacked shelves
or racks made of insulating material.

BEM (Building and Energy Management) System
System used for control/monitoring of all building utilities and systems. It is generally composed
of sensors, actuators, and programmable controllers connected to a central computer or several
computers, equipped with specific software.

Brownout
Conditions under which power is available but not sufficient to fully meet the needs (voltage,
current) of the load.

BS (British Standard)
Label used to indicate compliance with British standards.

Bypass
The use of parallel units in an UPS to increase capacity or for redundancy.

Bypass (automatic)
In the event of an overload or an unlikely UPS problem, your application is still powered thanks
to the automatic bypass module.

Bypass (manual)
Manually operated switch used to supply the load via direct connection to utility power during
servicing of the UPS system.

Capacity (battery)
The number of ampere-hours (Ah) a fully charged cell or battery can deliver under specified
conditions of discharge.

Cell
The basic electrochemical element of a battery.

Charge (equalizing)
An extended charge to a measured end point that is given to a storage battery to insure the
complete restoration of the active materials in all the plates of the cells.

Charger
Device associated with the rectifier and used to supply the battery with the electrical power
[direct current (dc)] required to recharge and/or float charge the battery, thus ensuring the rated
backup time.

Circuit Breaker (battery)
DC circuit breaker that protects the battery of an UPS.

Cos phi
A measure of the phase shift between the current wave and the voltage wave observed at the
terminals of a load supplied with ac power at a given frequency.

                                                                                                                        G-5


---

TM 5-693

Cos phi1
A measure of the phase shift between the fundamental current wave and the fundamental voltage
wave observed at the terminals of a non-linear load .

Crest Factor (Fc)
Ratio between the peak current value to the root mean square (RMS) current value.

Cubicle (parallel UPS unit)
Cubicle containing a rectifier/charger and an inverter. It is connected to one or several other
identical cubicles and a bypass cubicle to make up a parallel UPS.

Cubicle (single UPS unit)
Cubicle containing a rectifier/charger, an inverter, and a bypass. Connected to a battery, it
operates alone, forming a single UPS. Compare with cubicle (parallel UPS unit).

Current (float)
DC current that maintains the battery at nominal charge, corresponding the float voltage. This
current compensates open circuit losses.

Current (inrush)
Temporary current observed in a network when electrical devices are energized, generally due to
the magnetic circuits of the devices. The effect is measured by the current’s maximum peak
value and the RMS current value it generates.

Current Harmonics
[see Harmonics (current and voltage)]

Current Loop (20 mA)
Transmission system used on certain devices and offering better performance than the RS232C.
It provides a high degree of immunity to interference and is easy to implement, but has not been
standardized.

Cycle
A battery discharge followed by a complete recharge. A deep (or full) cycle is described as the
removal and replacement of 80 percent or more of the cell’s design capacity.

Cycling
The repeated charge/discharge cycle of a storage battery. Some batteries are rated by their ability
to withstand repeated, deep discharge cycles.

Diagnostics
Manual, automated, and semi-automatic methods and procedures for identifying and isolating a
failure in an item.

Discharge Rate
The rate at which a cell or battery delivers current (e.g., 200 amperes over 10 hours is a rate of 20
amperes per hour).

Distortion (individual)
Ratio between the RMS value of an nth order harmonic and the RMS value of the fundamental.

G-6


---

                                                                                                                     TM 5-693

Distortion (total)
Ratio between the RMS value of all harmonics of a non-sinusoidal alternating periodic value and
that of the fundamental. This value may also be expressed as a function of the individual
distortion of each harmonic
Hn = Yn /Y1.

Earthing System
System for the interconnection and earthing of exposed conductive parts and neutral. There are
three types of neutral systems: IT, TN, TT.

Earthing System IT
Earthing system in which the neutral is isolated from the earth or connected to the earth via a high
impedance and the various exposed conductive parts are connected to the earth via individual
earthing circuits. An alarm must signal the appearance of a first insulation fault. The installation
must be de-energized immediately in the event of a second insulation fault.

Earthing System TN
Earthing system in which the exposed conductive parts are interconnected and connected to the
neutral. The neutral is connected to the earth. The installation must be de-energized immediately
in the event of an insulation fault.

Earthing System TT
Earthing system in which the neutral and the exposed conductive parts are directly earthed. The
installation must be de-energized immediately in the event of an insulation fault.

Electrode
The electrical connector and the associated active materials at which an electrochemical reaction
occurs. Also referred to as the positive and negative plates in a secondary cell.

Electrolyte
The medium that provides the ion transport function between the positive and negative electrodes
of a cell. In lead-acid batteries, the electrolyte is a mixture of water and sulfuric acid. A nickel-
cadmium (ni-cad) cell uses a dilute alkaline mixture of potassium hydroxide in water.

Electromagnetic (EM) Compatibility
Possibility of a device to operate normally when installed near other devices, given the
disturbances emitted by each device and their mutual sensitivities.

Emergency Power
An independent reserve source of electric energy that, upon failure or loss of the primary source,
provides reliable power within a specified time to critical devices and equipment which, if they
fail to operate satisfactorily, would jeopardize the health and safety of personnel, result in
property damage, or cause loss of revenue.

Ferroresonant
An interactive UPS configuration in which a ferroresonant transformer is used to magnetically
couple the ac input to the load.

Field Effect Transistor (FET)
A solid-state device in which current is controlled between source and drain terminals by voltage
applied to a non-conducting gate terminal.

                                                                                                                        G-7


---

TM 5-693

Filter (phase-shift)
Filter used to reduce, if necessary, the overall distortion due to the current harmonics injected into
the mains upstream of an UPS by its rectifier-charger. Filtering is superior to that of a traditional
filter of the L or C type.

Float Charge
Commonly used for applications in which the battery is only infrequently discharged, charging
conducted with the charger, battery, and load in parallel. The charger operates off the normal
power supply.

Float Current
[see Current (float)]

Floating Voltage
[see Voltage (float)]

Fourier Theorem
Theorem stating that any non-sinusoidal periodic function (frequency f) may be represented as a
sum of terms (series) made up of a sinusoidal term with frequency f, called the fundamental
frequency, n sinusoidal terms with frequencies that are whole multiples of the fundamental
frequency, (harmonics), and a possible dc component. Where n is a whole number. n = 1
corresponds to the fundamental, n > 1 to the harmonic of the nth order.

Gell-Cell
Refers to a battery in which the electrolyte consists of a mixture of finely divided silica or sand
mixed with a sulfuric acid solution. The gelled electrolyte is highly viscous and during charge
and discharge can develop voids or cracks that impede acid flow and result in loss of battery
capacity.

Harmonic
Sinusoidal term of the Fourier series expansion of a periodic function. The harmonic (or
harmonic component) of the nth order is characterized by: Yn is the root mean square (RMS)
value of the given harmonic component, w is the angular frequency of the fundamental, related to
frequency by: w = 2¹f; phin is the phase angle of the given harmonic component at t = 0.

Harmonics
Distortions of the sine-wave that characterizes normal ac current. Harmonics are transmitted into
an ac line by non-linear loads (i.e., loads that do not draw power in regular sine waves), such as
computers, copiers, FAX machines, and variable-speed motors. Harmonics can cause
communication errors and equipment damage. In three-phase systems, they can cause
transformers and neutral conductors to overheat creating a possible fire hazard.

Harmonics (current and voltage)
All ac which is not absolutely sinusoidal is made up of a fundamental and a certain number of
current harmonics which are the cause of its deformation (distortion) when compared to the
theoretical sine-wave. For each current harmonic of order n and an RMS value In, there is a
voltage harmonic with a RMS value Un. If Zsn is the voltage source output impedance for the
harmonic of the nth order, then: Un = Zsn x In.

High-Frequency Interference
[see Interference (high frequency)]

G-8


---

                                                                                                                     TM 5-693

Hybrid UPS
(see UPS, Hybrid)

Individual Distortion
[see Distortion (individual)]

Inrush Current
[See Current (inrush)]

Insulated Gate Bipolar Transistor (IGBT)
The IGBT is a minority carrier device and is fundamentally different in operation than a
MOSFET, although they are similar in cross section.

Interference (high-frequency)
High-frequency parasitic current that is either conducted (electrostatic origin) or radiated (EM
origin) by a device.

International Electrotechnical Commission (IEC)
Advisory organization that draws up international standards in the electrotechnical field.

Inverter
A device for converting dc to ac current.

Inverter
UPS subassembly that recomposes a sine-wave output (regulated and without breaks) using the
dc current supplied by the rectifier-charger or the battery. The primary elements of the inverter
are the dc/ac converter, a regulation system, and an output filter.

Inverter (off-line or stand-by)
UPS configuration in which the inverter is parallel-mounted to the load supply line and backs up
the mains. This configuration offers a substantial cost reduction but is applicable only to low
outputs, under 3 kVA, because it results in an interruption lasting up to 10 milliseconds (ms)
during transfer and does not filter inrush currents.

Inverter (on-line)
UPS configuration in which the inverter is in series mounted between the mains and the load. All
power drawn by the load passes via the inverter. This is the only configuration used for high
outputs.

IP (protection index)
[see Protection index (IP)]

ISO 9000
Standard defining procedures and systems used to attain an internationally recognized level of
production quality. ISO 9000 certification is proof that the quality system effectively complies
with the standard. Certification is carried out by an official organization (AFAQ), unaffiliated
with either clients or suppliers or the company itself, and is valid for a three-year period with
yearly audits and checks.

                                                                                                                        G-9


---

TM 5-693

Kilo Volt Amperes (kVA)
The product of the voltage and the amperes expressed in units of thousands. The resultant is total
system power.

Kilowatt (kW)
The product of the voltage and the amperes and the power factor expressed in units of thousands.
The resultant is “real” system power.

Life Cycle Cost (LCC)
The total costs incurred in the acquisition, operation and maintenance, and disposal of an item.
For an UPS, from a customer perspective, life cycle cost includes the purchase price, installation
costs, operating and support costs, and disposal costs.

Line-Interactive
An UPS configuration in which line power is fed directly into the load through a series inductor
or transformer.

Load (linear)
Load for which voltage form and current form are similar. Voltage and current are related by
Ohm’s law U(t) = Z x I(t).

Load (non-linear)
Load (generally with a switched-mode power supply) generating major harmonic currents.
Current wave form is different from voltage wave form. Ohm’s law is not applicable. It can be
used only with each harmonic.

Load Power
Apparent power Pu that the UPS inverter supplies under given load conditions. It is less than or
equal to the rated output Pn. The ratio Pu/Pn defines the percent load of the inverter.

Load Shedding
The process of deliberately removing pre-selected loads from a power system in response to an
abnormal condition to maintain the system’s integrity.

Maintainability
Relative ease and economy of time and resources with which an item is retained in, or restored to,
a specific condition when maintenance is performed by personnel having specified skill levels,
using prescribed procedures and resources, at each prescribed level of maintenance and repair.
Measures include probability to repair within a given time, repair rate, and mean time to repair.

Manual Bypass
[see Bypass (manual)]

Mean Downtime (MDT)
The mean time during which an item is not available for operation for any reason, including
active maintenance, lack of parts, lack of maintenance personnel, etc.

Mean Time Between Demand (MTBD)
A measure of reliability that addresses all reasons for support. Demands can result from inherent
failures of the item, failures caused by operators or maintenance personnel (induced failures),
preventive maintenance requirements, etc.

G-10


---

                                                                                                                     TM 5-693

Mean Time Between Failure (MTBF)
A measure of reliability. Usually denotes the time between inherent failures (i.e., failures caused
by a physical or chemical phenomena within the item.)

Mean Time To Failure (MTTF)
Mathematical calculation of the duration of normal operation of a non-reparable device, i.e., for
which a MTBF is not possible. The product, expressed in hours, is an indication on the reliability
of the device.

Mean Time To Repair (MTTR)
A measure of maintainability. Mathematical calculation (or statistical average if available) of the
time required to repair a device.

Mega Volt Amperes (MVA)
The product of the voltage and the amperes expressed in units of millions. The resultant is total
system power.

Micro-Outage
Total loss in the supply of power for 10 ms.

Monitor (system interface)
User interface on the Galaxy range of UPS systems. This interface includes an LCD
alphanumeric display with two lines of 20 characters each and is used in conjunction with the
Signal 4 interface.

Motor-Generator (M-G)
Power systems that use a rotating ac generator to generate the needed output power. A motor-
generator that is powered by a battery or a diesel or gas-powered engine when utility power is
lost, constitutes a rotary or hybrid UPS.

Noise level
Acoustical decibel level of a source of noise, measured according to the applicable ISO standard.

Non-Linear Load
(see Load)

No-Ox-Id
No-ox-id is a soft, wax based rust preventive lubricant. It contains a small amount of solvent for
ease of application with a brush. It is non-drying and retains its properties indefinitely.

Off-Line Inverter
(see Inverter)

Off-Line or Standby
An off-line, or standby, UPS is switched on to power the load only when the primary power
source is lost or fails. The interval of time from when the utility power is lost and the UPS picks
up the load can range from 2 to 20 ms.

On-Line
An UPS that continuously powers the load from the inverter.

                                                                                                                      G-11


---

TM 5-693

On-Line Inverter
(see Inverter)

Output (rated)
Apparent power Pn that the UPS can deliver under given load conditions (power factor = 0.8).

Overall Distortion
[see Distortion (overall)]

Oversizing
Increasing the capacity of an UPS beyond that required to exactly meet the needed power
requirements. Oversizing allows an UPS to efficiently and effectively handle surges and provides
for growth in the power requirements.

Overvoltage
Sudden increases in voltage on one or more phases of ac power caused by large changes in the
electrical load or from utility power switching.

Parallel UPS Cubicle
[see Cubicle (parallel UPS unit)]

Parallel UPS with Redundancy
[see UPS (parallel with redundancy)]

Parallel UPS without Redundancy
[see UPS (parallel without redundancy)]

Percent Load
Ratio between the power Pu drawn by the load and the rated output Pn of an UPS system (Pu/Pn).
Sometimes referred to as the load factor. Phase-shift filter [see Filter (phase-shift)].

Power Factor
The power factor is the mathematical relationship between apparent or effective power, measured
in kVA, and real or average power, measured in kW. When the current and voltage are in phase,
purely resistive load, the power factor is 1. In a purely reactive load in which voltage and current
are 90° out of phase, the power factor is 0.

Power factor (l)
Ratio between the active power P supplied to a load and the apparent power S supplied to said
load by an ac power supply.

Power Source (alternate)
Backup source used in the event of a mains failure. The connection time and the duration of the
source depend on the type of source used.

Power Source (safety)
Power source for loads defined as critical by applicable safety regulations. This supply must not
be affected by a mains failure and is generally separate from other supplies.

Primary Cell or Battery
A cell or battery that is not intended to be recharged and is discarded at the end of its useful life.

G-12


---

                                                                                                                     TM 5-693

Prime Power
The normal source of power used continuously day and night. Usually supplied by an electric
power utility but can be supplied by base-loaded user-generation.

Protection Index (IP)
Index indicating the capacity of an electrical device to resist environment conditions. It is made
up of three digits (e.g., IP 205), each corresponding to a type of environmental risk. The higher
the number, the greater the capacity to resist. First digit (0 to 6): capacity to resist penetration by
solid objects. Second digit (0 to 7): capacity to resist penetration by liquids. Third digit (0, 1, 2,
3, 5, 7, 9): mechanical strength.

Pulse Width Modulation (PWM)
Inverter high-frequency chopping technique using a means of regulation enabling rapid
modification of pulse widths over a single period. This makes it possible to maintain the inverter
output within tolerances even for non-linear loads.

Radio Frequency Interference (RFI)
An unwanted electromagnetic signal that degrades the performance of the electronic device.

Rated Output
[see Output (rated)]

Reactance
Relative measurement (percent) of the internal impedance of an ac generator during harmonic
phenomena. This reactance, also called the longitudinal subtransient reactance of the generator, is
sometimes identified as X”d. For most common generators, the value ranges between 15 and 20
percent. It can drop to 12 percent for optimized systems and to 6 percent for special devices.

Recombinant Battery
A battery in which the cells are sealed with pressure relief valves that confine any gases produced
during cell operation. These gases are then recombined back into water, substantially eliminating
the loss of water from the cells and the need for water replenishment.

Recombination Battery
[see Battery (recombination)]

Rectifier
A device for converting ac to dc.

Rectifier/charger
UPS component that draws on the mains the power required to supply the inverter and to float
charge or recharge the battery. The alternating input current is rectified and then distributed to
the inverter and the battery.

Redundancy (active)
Parallel UPS configuration in which several UPS units with equal outputs are parallel connected
and share the load. In the event one UPS unit fails, the other units pick up its share without any
interruption in the supply of power to the load.

                                                                                                                      G-13


---

TM 5-693

Redundancy (standby)
UPS configuration in which one or several UPS units operate on standby, with no load or only a
partial load, and can immediately back up a faulty UPS unit by no-break transfer of the load,
carried out by a static switch.

Reliability
The probability that an item will perform as intended for a specified period of time under a stated
set of conditions. Usually measured as a probability, a failure rate, or a mean time between
failures.

Reliability
Probability that a device will accomplish a required function under given conditions over a given
period of time. RMS value of ac with harmonics. The RMS value Yrms of a non-sinusoidal ac
may be determined on the basis of the individual harmonic currents: where Y is the RMS value of
the fundamental.

Reliability Centered Maintenance (RCM)
A maintenance program established to maximize the equipment reliability.

Rotary UPS
(see UPS, Rotary)

RS232C (recommended standard RS232C)
Standard defining the communication circuits between devices for synchronous and asynchronous
transmissions on the following types of lines: two-wire, four-wire, point-to-point, telephone lines,
and local links with short cables. Though the standard covers only transmissions over distances
up to 15 meters, it is often possible to ensure correct transmission over greater distances using
high-quality shielded cable in a reasonably satisfactory electrical environment. Most terminals
and devices on the market can implement this transmission standard.

RS422A (Recommended standard RS422A)
Standard RS232C is sufficient for transmissions in a normal environment. For transmissions in a
disturbed environment or over long distances, standard RS422A offers a differential operation
option, with a balanced voltage, ensuring far superior performance. What is more, it can be used
for multipoint links, with generally up to ten connection points (one sender and up to ten
receivers).

RS485 (recommended standard RS485)
This standard is similar to RS422A except that the number of possible links is greater and up to
32 senders may be interconnected to as many receivers. This system is particularly designed for
local-area networks.

Safety Installation
Installation supplying electrical equipment which may have a direct effect on the safety of users
and must therefore remain energized even in the event of a main failure. In general,
characteristics concerning the power supply and conditions for transfer to the safety source for
such electrical equipment are covered by applicable regulations.

Safety Power Source
[see Power Source (safety)]

G-14


---

                                                                                                                     TM 5-693

Sag
A low-voltage condition in which the voltage on one or more phases of ac power falls below 80
to 85 percent of the nominal value for more than one cycle (1/60th of a second for 60-cycle ac).
Can be caused by ground faults, starting large loads, inadequate power supply, utility switching,
utility equipment failure, and lightning. Can cause computer crashes and damage equipment.

Secondary Battery
A battery that may be restored to its charged state after discharge by passing an electrical current
through the cell in the opposite direction to that of discharge. Also called a storage or
rechargeable battery.

Single UPS
[see UPS (single)]

Single UPS Cubicle (see Cubicle)
[single UPS (unit)

Standby Power
An independent reserve source of electric energy that, upon failure or loss of the prime source,
provides electric power of acceptable quality so that the facility may continue operation in a
satisfactory manner (which could include an orderly shutdown).

Standby Redundancy
[see Redundancy (standby)]

Static Bypass Switch
Power-electronics device that can be used to switch from one source to another without
interruption in the supply of power. In an UPS, transfer is from Mains 1 to Mains 2 and back.
Transfer without interruption is possible due to the fact that there are no mechanical parts and the
ultra-fast switching capabilities of the electronic components.

Static UPS
[see UPS (static)]

Subtransient Reactance of Generator
(see Reactance )

Surge
A high voltage condition in which the voltage on one or more phases of ac power exceeds 100
percent of the nominal value for more than one cycle (1/60th of a second for 60-cycle ac). Can be
caused by a rapid load reduction or switching, and can damage equipment.

Thermal Runaway
A condition that is caused by a battery charging current that produces more internal heat than the
battery can dissipate. This condition ultimately causes cell venting and premature failure.

Thevenin Generator
For a given load, it is possible to consider the power supply as a voltage generator, referred to as
a Thevenin generator, made up of a perfect voltage Uo generator, in series with an internal
impedance Zs: n Uo is the voltage measured across the load terminals, given that the load is to be
disconnected (load terminals forming an open circuit), n Zs is the equivalent impedance as seen

                                                                                                                      G-15


---

TM 5-693

from the load terminals (again considered an open circuit), obtained by short-circuiting the
upstream voltage generator(s).

Tolerance in Percent
Limit for allowable variations for a given quantity, expressed as a percent of the rated value.

Transformer Short-Circuit Voltage
Relative measurement (percent) of the internal impedance of a transformer. This short-circuit
impedance is commonly called the short-circuit voltage because it is measured during a short-
circuit test (shorted secondary winding subjected to a current set to In). For most common three-
phase transformers, this value ranges between 3 and 6 percent.

Transients
Disturbances to electrical power lasting less than one cycle (1/60th of a second for 60-cycle ac).
Also referred to as voltage spikes. Can be caused by lightning strikes, sudden load-shedding on
the primary power system, shutdown of equipment that was drawing an extremely large amount
of power, or a general rise in voltage on the primary power system after use by a large number of
consumers. Voltage spikes can blow fuses or trigger circuit breakers, destroy electronic circuitry,
and corrupt stored data.

Underwriters Laboratories (UL)
UL is a non-governmental, non-profit certification organization in the United States in which not
only government authorities are represented, but also consumer groups, “export” services,
research, etc. Following certification, a product may bear the UL label.

Uninterruptible Power Supply (UPS)
An electrical device providing an interface between the mains power supply and sensitive loads
(computer systems, instrumentation, etc.). The UPS supplies sinusoidal ac power free of
disturbances and within strict amplitude and frequency tolerances. It is generally made up of a
rectifier/charger and an inverter together with a battery for backup power in the event of a mains
failure.

Uninterruptible Power System (UPS)
Also used as the abbreviation for uninterruptible power supply. The latter is most often used for
static (battery) backup power supplies for personal computers and other equipment with similar
power requirements. UPSs include uninterruptible power supplies as well as more complex
systems (e.g., rotary, hybrid, etc.).

UPS (parallel with redundancy)
An UPS made up of several parallel-connected UPS units with equal output ratings (P) and each
equipped with its battery. If one unit fails, one or several of the others pick up the resulting
excess load. If an UPS has a rated output n x P and is made up of n + k units, k is the level of
redundancy for the entire set of n + k units.

UPS (parallel without redundancy)
An UPS made up of several (n) parallel-connected UPS units with equal output ratings (P) and
each equipped with its battery, for large loads. The total output is equal to the number of units
multiplied by their individual output (n x P). In this configuration, no UPS unit is redundant.

UPS (single)
An UPS made up of one single UPS unit (rectifier/charger, inverter, and bypass) and a battery.

G-16


---

                                                                                                                     TM 5-693

UPS, Hybrid
An UPS that combines the features of both a static and rotary UPS.

UPS, Multiple-Unit
An UPS in which two or more units share the load but neither can carry 100 percent of the load.

UPS, Parallel-Redundant
An UPS in which two or more units are arranged in parallel and each can carry 100 percent of the
load.

UPS, Parallel-Unit
An UPS in which two or more units are arranged in parallel and not all units are required to carry
100 percent of the load.

UPS, Rotary
An UPS in which a M-G set is used.

UPS, Single Unit
An UPS in which one unit carries 100 percent of the load.

UPS, Static
A solid-state UPS relying solely on battery power.

Useful Life (battery)
The time over which a battery can deliver a useful (normally defined as 80 percent or more of the
battery’s capacity) amount of power.

UTE (Union Technique de l’Electricité)
French electrotechnical standards organization.

VDE
German electrotechnical standards organization.

Vented Battery
[see Battery (vented)]

Voltage (equalize)
The voltage applied during an equalizing charge. This voltage is sufficiently high to ensure that
the local action of all cells is overcome.

Voltage (float)
DC voltage applied to the battery to maintain its charge level. This voltage depends on the type
of battery, the number of cells, and the manufacturer’s recommendations.

Volt Amperes (VA)
The product of the voltage and the amperes. The resultant is total system power.

Voltage Harmonics
[see Harmonics (current and voltage)]

                                                                                                                      G-17


---

TM 5-693
Valve-Regulated Lead-Acid (VRLA)
A “sealed” battery in which the electrolyte is immobilized, a relief valve opens when the internal
pressure (caused by oxygen and hydrogen generation) exceeds a predetermined value. VRLA
provide a means of recombination of internally generated oxygen and suppression of hydrogen
gas evolution to limit water consumption. The electrolyte is immobilized by using an absorbent
separator (e.g., AGM) or a gelling agent.
Walk-In
The slow transfer of power from the battery back to the utility over a 10-20 second interval.

G-18


---

       TM 5-693

INDEX

                                                 A

acceptance test, 4-12
acceptance testing, 1-1
asynchronous motor, 2-29
availability, 1-3, 2-40, 3-1, 3-2, 3-6, 3-7, 3-8, 3-10, 3-12, 3-13, 4-4, 4-7

                                                 B

batteries, 1-1, 1-3, 2-20, 2-22, 2-24, 3-6, 4-1, 4-4, 4-7, 4-14, 5-16
battery, 1-1, 1-3, 2-1, 2-2, 2-3, 2-4, 2-5, 2-20, 2-21, 2-22, 2-23, 2-24, 2-25, 2-29, 2-30, 2-31, 2-32,

  2-33, 2-35, 2-36, 2-38, 2-39, 3-7, 3-10, 3-11, 3-13, 3-14, 3-15, 3-16, 3-17, 3-18, 3-20, 4-1, 4-2,
  4-3, 4-4, 4-6, 4-7, 4-13, 4-14, 4-15, 4-17, 4-18, 4-19, 4-20, 4-21, 5-1, 5-2, 5-3, 5-4, 5-5, 5-6, 5-
  7, 5-8, 5-9, 5-10, 5-11, 5-12, 5-13, 5-14, 5-15, 5-16
battery charging, 2-22
battery sizing, 3-16
bipolar transistors, 2-6, 2-7
blocking diode, 2-6

                                                 C

checklists, 1-1
controlled rectifiers, 2-9
corrective maintenance, 1-4, 5-4
crest value changes, 2-27
current limit, 2-5, 2-25, 3-16, 3-18, 4-8
cycling effects, 2-23

                                                 D

DC generators, 2-31
DC motors, 2-30, 2-31, 3-19

                                                 E

emergency power, 1-1, 2-22, 3-1, 3-6
exciters, 2-31

                                                 F

ferroresonant transformer, 2-5, 2-15, 2-17
field effect transistors (FET), 2-6, 2-7, 2-8
filtered power, 2-29
flywheel, 2-29, 2-30, 2-31, 2-32, 2-36, 2-37, 2-38, 3-18, 3-19, 3-20

       I-1


---

TM 5-693

                                                 G

generator, 1-2, 2-26, 2-28, 2-29, 2-30, 2-31, 2-32, 2-33, 2-36, 2-37, 2-38, 2-39, 3-6, 3-13, 3-18, 3-
  19, 3-20, 4-6, 4-13, 4-16, 4-17, 4-19, 4-21, 4-22

grounding, 1-1, 4-7, 4-9

                                                 H

harmonic correction techniques, 2-28
harmonic distortion, 1-1, 2-25, 3-14
harmonics, 2-1, 2-17, 2-26, 2-27, 2-28, 4-10

                                                 I

induction coupling, 2-31
induction motors, 2-30, 3-19
inrush current, 2-4, 2-5, 2-25, 2-33, 3-16, 3-18, 4-8
installation, 1-1, 2-4, 2-28, 2-33, 3-1, 3-6, 3-10, 3-11, 3-12, 3-13, 3-15, 3-16, 3-17, 3-19, 4-7, 4-

  11, 4-12, 4-14, 4-15, 4-17, 5-4, 5-5, 5-7, 5-8, 5-9, 5-13, 5-15
insulated gate bipolar transistor (IGBT), 2-6, 2-8, 2-14
inversion, 2-14
inverter, 1-1, 2-1, 2-2, 2-5, 2-6, 2-7, 2-14, 2-15, 2-16, 2-17, 2-18, 2-20, 2-25, 2-29, 2-30, 2-32, 2-

  33, 2-34, 2-35, 2-37, 2-39, 3-16, 3-17, 4-1, 4-2, 4-3, 4-4, 4-7, 4-8, 4-14, 5-3

                                                 K

kinetic battery, 2-29

                                                 L

latching devices, 2-7
lead-acid batteries, 2-20
lower power factor, 2-27

                                                M

maintenance, 1-1, 1-3, 1-4, 2-3, 2-4, 3-11, 4-1, 4-20, 4-22, 5-1, 5-2, 5-4, 5-5, 5-7, 5-8, 5-9, 5-12,
  5-14

maintenance bypass switch, 2-3
memory effect, 2-25
motor, 1-2, 2-20, 2-29, 2-30, 2-31, 2-32, 2-36, 2-37, 2-38, 2-39, 3-15, 3-18, 3-19, 3-20, 4-6, 4-13,

  4-15, 4-16, 4-19

                                                 N

neutral harmonic behavior, 2-27
nickel-cadmium batteries, 2-20, 2-22, 5-6, 5-15
noise feedback, 2-28
nonlinear loads, 2-25, 2-32

                                                 O

operations, 1-1

I-2


---

                                                                                                                     TM 5-693

                                                 P

power, 1-1, 1-2, 1-3, 1-4, 2-1, 2-2, 2-3, 2-4, 2-6, 2-7, 2-8, 2-9, 2-14, 2-15, 2-18, 2-20, 2-21, 2-22,
  2-23, 2-25, 2-26, 2-27, 2-28, 2-29, 2-30, 2-31, 2-32, 2-33, 2-34, 2-35, 2-36, 2-37, 2-38, 2-39, 2-
  40, 3-1, 3-2, 3-6, 3-7, 3-8, 3-9, 3-10, 3-13, 3-15, 3-16, 3-17, 3-18, 3-19, 3-20, 4-1, 4-2, 4-6, 4-7,
  4-8, 4-9, 4-10, 4-11, 4-12, 4-13, 4-14, 4-15, 4-16, 4-17, 4-21, 5-1, 5-3, 5-4, 5-5, 5-13

power diodes, 2-9
power requirements, 3-6
preventive maintenance, 1-4, 5-1, 5-5
probability, 3-8, 5-2
protective devices, 1-3, 3-16, 4-7, 4-8, 4-9
pulse width modulation (PWM), 2-5, 2-15, 2-16, 2-17

                                                 R

rectification, 2-8
rectifier, 1-1, 2-1, 2-2, 2-5, 2-6, 2-8, 2-9, 2-10, 2-11, 2-12, 2-25, 2-26, 2-29, 2-32, 2-33, 2-35, 2-

  36, 2-39, 4-3, 4-17, 4-20, 4-22, 5-3, 5-4, 5-6, 5-8, 5-9, 5-10, 5-13, 5-15, 5-16
reliability, 2-20, 2-21, 2-28, 2-33, 2-34, 2-35, 2-36, 2-37, 2-38, 2-39, 2-40, 3-1, 3-7, 3-8, 3-9, 3-

  10, 3-11, 3-20, 5-1, 5-2, 5-8
ripple currents, 2-25
rotary UPS, 1-1, 1-2, 1-4, 2-29, 2-30, 2-31, 2-32, 2-33, 2-36, 2-37, 3-13, 3-18, 3-20, 4-6, 4-7, 4-

  13, 5-5

                                                 S

safety, 3-6, 4-22, 4-23, 5-1, 5-5, 5-15, 5-16
SCR, 2-1, 2-3, 2-4, 2-6, 2-7, 2-14, 2-15, 2-16, 2-17, 2-18, 2-19, 4-20, 4-21
shielding, 1-4, 4-7, 4-10
single-phase uncontrolled rectifiers, 2-8
sizing selection, 1-1
standby power, 1-1, 3-1, 3-6
static switch, 1-2, 2-1, 2-2, 2-20, 2-33, 2-35, 2-36, 2-39, 4-8, 4-17, 4-19
static transfer switch, 2-18, 2-20, 2-33, 2-34, 2-36, 3-16, 3-18, 4-8
static UPS, 1-1, 1-2, 2-1, 2-6, 2-14, 2-20, 2-22, 2-25, 2-26, 2-31, 2-32, 2-33, 2-35, 2-36, 2-39, 2-

  40, 3-13, 3-15, 3-16, 3-17, 3-18, 4-1, 4-2, 4-7, 5-5
synchronous motor, 2-29, 2-37, 4-6
system rating, 1-1, 3-18

                                                 T

testing, 1-3, 1-4, 4-1, 4-11, 4-13, 4-15, 4-16, 5-5, 5-6
three-phase uncontrolled rectifiers, 2-8
transistors, 2-6, 2-7, 2-8, 2-15
troubleshooting, 1-1, 3-11, 4-23, 5-4, 5-5, 5-16

                                                 U

unbalanced load, 2-32

                                                                                                                              I-3


---

TM 5-693

                                                 V

valve regulated lead acid batteries (VRLA), 2-21
voltage tapping, 2-23

                                                W

walk-in time, 2-5

                                                 Z

zero crossing increases, 2-28

I-4


---



---



--- 