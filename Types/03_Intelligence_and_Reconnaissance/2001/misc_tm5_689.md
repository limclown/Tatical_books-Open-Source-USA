# misc_tm5_689  TM 5-689

TECHNICAL MANUAL

  ADP/COMPUTER ELECTRICAL
INSTALLATION AND INSPECTION

    FOR COMMAND, CONTROL,
 COMMUNICATIONS, COMPUTER,
 INTELLIGENCE, SURVEILLANCE,
 AND RECONNAISSANCE (C4ISR)

                 FACILITIES

APPROVED FOR PUBLIC RELEASE: DISTRIBUTION IS UNLIMITED

 HEADQUARTERS, DEPARTMENT OF THE ARMY

                                                                               10 SEPTEMBER 2001


---

   REPRODUCTION AUTHORIZATION/RESTRICTIONS

This manual has been prepared by or for the Government and, except to
the extent indicated below, is public property and not subject to
copyright.

Reprint or republication of this manual should include a credit
substantially as follows: “Department of the Army TM 5-689,
ADP/Computer Electrical Installation and Inspection for Command,
Control, Communications, Computer, Intelligence, Surveillance, and
Reconnaissance (C4ISR) Facilities, 10 September 2001.”

Appendix B reprinted with permission from Information Technology
Industry Council (ITI) “ITI (CBEMA) Curve”, copyright © 1999 by ITI.
ITI disclaims any responsibility of liability resulting from the placement
and use in the described manner.


---

                                                                                  TM 5-689

Technical Manual                                                 HEADQUARTERS
No. 5-689                                                 DEPARTMENT OF THE ARMY

                                                          Washington, DC, 10 September 2001

              APPROVED FOR PUBLIC RELEASE; DISTRIBUTION IS UNLIMITED

ADP/Computer Electrical Installation and Inspection for Command, Control,
Communications, Computer, Intelligence, Surveillance, and Reconnaissance

                                     (C4ISR) Facilities

                                                                       Paragraph  Page

CHAPTER 1.  INTRODUCTION
            Purpose
            Scope                                                      1-1        1-1
            References
                                                                       1-2        1-1

                                                                       1-3        1-1

CHAPTER 2.  FACILITY POWER SYSTEM
            Dependable power system requirements
            Commercial (utility) power                                 2-1        2-1
            Power line phenomena
            Power quality requirements                                 2-2        2-3
            Power quality parameters
            Detection of power line anomalies                          2-3        2-4

                                                                       2-4        2-6

                                                                       2-5        2-7

                                                                       2-6        2-8

CHAPTER 3.  POWER CONDITIONING
            Automated data processing power requirements
            Power line disturbances                                    3-1        3-1
            Acceptable limits for ac power
            ADP protective equipment                                   3-2        3-2
            Power distribution systems
                                                                       3-3        3-4

                                                                       3-4        3-5

                                                                       3-5        3-15

CHAPTER 4.  GROUNDING

            Purpose of grounding                                       4-1        4-1

            National electrical code (NEC) requirements for grounding  4-2        4-1

            System configurations                                      4-3        4-4

            Ground configurations                                      4-4        4-9

            Grounding for fault protection                             4-5        4-10

            ADP grounding                                              4-6        4-16

CHAPTER 5.  HARMONICS
            Harmonics defined
            Harmonic sources                                           5-1        5-1
            Harmonic technical history
                                                                       5-2        5-1

                                                                       5-3        5-2

                                                                                             i


---

TM 5-689

            Resonance                                                Paragraph    Page
            Electrical loads
            Neutral currents                                         5-4        5-3
            Derating power equipment                                 5-5        5-4
            Generator control problems                               5-6        5-5
            UPS output harmonic distortion                           5-7        5-6
            AC system response to harmonics                          5-8        5-7
            Solution of harmonic problems                            5-9        5-8
            Measurement of non-sinusoidal currents and voltages      5-10       5-8
            Conclusions                                              5-11       5-11
                                                                     5-12       5-16
                                                                     5-13       5-17

CHAPTER 6.  STANDBY POWER                                            6-1        6-1
CHAPTER 7.  Introduction
CHAPTER 8.  Codes and standards                                      6-2        6-3
            Off-line/on-line ADP systems standby power requirements
CHAPTER 9.  Diesel generator standby systems                         6-3        6-3
            Battery standby systems
            Transfer switches for standby systems                    6-4        6-5
            Grounding standby power systems
                                                                     6-5        6-8
            LIGHTNING
            Lightning effects on power systems                       6-6        6-20
            Principals of protection
            Lightning protection systems                             6-7        6-30

                                                                     7-1        7-1

                                                                     7-2        7-4

                                                                     7-3        7-5

            INSTALLATION                                     system  8-1        8-1
            Objective of an automated data processing (ADP)
            Contract bidding                                         8-2        8-1
            Inspection requirements
            Ground system installation inspections                   8-3        8-2
            Neutral junction installation inspections
            Safety ground installation inspections                   8-4        8-3
            Inspecting for unbalanced loads
            Utility power system installation inspections            8-5        8-4
            RFI inspections
            ESD inspection                                           8-6        8-4
            ADP system environment inspections
            Pre-site inspection                                      8-7        8-6
            Pre-inspection for electrical systems
            ADP room inspection                                      8-8        8-6
            Air-conditioning system inspection
            Lighting system inspection                               8-9        8-7
            Fire safety inspection
            Total evaluation                                         8-10       8-9

                                                                     8-11       8-10

                                                                     8-12       8-12

                                                                     8-13       8-12

                                                                     8-14       8-13

                                                                     8-15       8-13

                                                                     8-16       8-14

                                                                     8-17       8-14

                                                                     8-18       8-14

            MAINTENANCE                                              9-1        9-1
            Objective
            Maintenance program                                      9-2        9-2
            Maintenance data file
            Personnel qualif ications                                9-3        9-4

                                                                     9-4        9-5

ii


---

                                                                               TM 5-689

             Dedicated maintenance equipment                    Paragraph        Page
             Renewal parts
             Continuous inspection program                      9-5            9-6
             Maintenance schedule                               9-6            9-7
             Maintenance tests                                  9-7            9-8
             Safety                                             9-8            9-8
             Electrical equipment fires                         9-9            9-9
             Equipment diagrams                                 9-10           9-10
             Test forms                                         9-11           9-12
                                                                9-12           9-12
                                                                9-13           9-13

APPENDIX A.  REFERENCES                                                        A-1

APPENDIX B.  ITI (CBEMA) CURVE APPLICATION NOTE                                B-1

GLOSSARY                                                                       G-1

Figure                         LIST OF FIGURES

Figure 4-1   Title                                                             Page
Figure 4-2
Figure 4-3   Minimum grounding requirements for ac powered isolated system     4-5
Figure 4-4
Figure 4-5   Minimum grounding requirements for battery powered isolation system 4-6
Figure 4-6
Figure 4-7   Clustered system                                                  4-6
Figure 4-8
Figure 4-9   Basic grounding of a clustered system                             4-7
Figure 5-1
Figure 5-2   Central-with-extensions system                                    4-9
Figure 5-3
Figure 5-4   Single phase 115/230 Vac power system ground connections          4-13
Figure 5-5
Figure 5-6   Three phase 120/208 Vac power system ground connections           4-13
Figure 5-7
Figure 5-8   Properly wired ac distribution circuits for minimum ground noise  4-14
Figure 5-9
Figure 5-10  Noise problems resulting from improper wiring                     4-15

             Series RLC circuit                                                5-10

             Poles and zeros on the s-plane                                    5-11

             Surface view of H(s) for all complex frequency in s-plane         5-12

             Response vs frequency for steady state input                      5-12

             Phase angle and power factor vs frequency                         5-13

             Impedance vs frequency                                            5-13

             Tuned passive filter                                              5-14

             Impedance poles and zeros of tuned passive filter                 5-15

             Tuned passive filter with static Var control                      5-15

             Active load current compensation                                  5-16

                                                                                       iii


---

TM 5-689          LIST OF TABLES

Table      Title                                                              Page

Table 4-1  Summary of the effects of shock                                    4-11
Table 5-1
Table 6-1  Voltage distortion limits for medium and high voltage power systems 5-2
Table 6-2
           Typical range of input power quality and load parameters of major  6-2

           computer manufacturers

           Comparison of cells required for NICAD and lead acid batteries     6-19

iv


---

                                                                                                         TM 5-691

   The proponent agency of this publication is the Chief of Engineers, United States Army. Users are
   invited to send comments and suggested improvements on DA Form 2028 (Recommended
   Changes to Publications and Blank Forms) directly to HQUSACE, (ATTN: CEMP-SP),
   Washington, DC 20314-1000.

By Order of the Secretary of the Army:

                                          General, United States Army
                                                   Chief of Staff

Official:

         Acting Administrative Assistant
         to the Secretary of the Army

Distribution:

         To be distributed in accordance with Initial Distribution Number (IDN) 344736, requirements
for non-equipment TM 5-689.


---

              TM 5-689

   CHAPTER 1
INTRODUCTION

1-1. Purpose

The purpose of this manual is to familiarize qualified personnel with problem areas of supplying electrical
power to automated data processing (ADP) systems. Special emphasis is placed on areas most often
overlooked or misunderstood by experienced designers and personnel responsible for maintaining an
outflow of quality data from an ADP installation. ADP systems are highly reliable, but will on occasion
malfunction and because of their complexity will require the services of highly skilled personnel to
correct and maintain the systems. This manual covers many inter-related aspects of an ADP installation
in regard to the electrical and life-safety systems. This manual will review the systems found in the
typical data center, and is not intended to provide the detailed level of understanding where arithmetic and
other more advanced mathematics are required to describe or explain a given function.

1-2. Scope

This manual is limited in scope in that it in no way is intended to be a course in the design of ADP
systems or related components. The engineering skills needed to design ADP systems are abilities
acquired through the process of formal education and actual field experience. The area of field
experience will be stressed in this manual and the subjects focused upon will be those areas that are
frequently the least understood. This manual will be useful to the power-oriented engineer with limited
commercial building experience and personnel responsible for the electrical design, inspection,
installation, and maintenance supervision of electrical power distribution systems supplying ADP
systems. This manual is not intended as a replacement for the engineering text furnished as part of ADP
system components, but rather, should be used to supplement and better evaluate established design
practices. While the fundamental objective of any ADP system is the processing of input data, the output
data can be greatly altered and influenced by the quality of power supplying the ADP system. In spite of
the wide variation of systems in use, all ADP systems respond adversely in some degree to the quality of
the basic power sources available. The manual addresses the following primary elements required for a
safe and reliable ADP system.

  a. Quality of the electrical power system for both efficiency and reliability

  b. Safe electrical installations

  c. Proper electrical grounding

  d. Standardization of ADP systems at various sites

1-3. References

Design, installation, and maintenance requirements should follow the latest version of applicable codes
and standards from recognized industry and commercial groups and committees. Appendix A contains a
complete listing of references used in this manual.

              1-1


---

                       TM 5-689

           CHAPTER 2
FACILITY POWER SYSTEM

2-1. Dependable power system requirements

Commercial power companies attempt to provide continuous, trouble -free, dependable service. The
computer and other sophisticated electronic devices have become of great concern throughout industry as
users become more dependent on continuous up-time and trouble -free operation of their systems. Better
knowledge of ac power and the problems that introduce faulty conditions would prevent unnecessary
downtime and costly repairs. Initial site preparation, proper installation procedures, and the use of proper
power line conditioning devices can prevent many of these related problems.

  a. Environmental conditions play a major part in insuring that computer systems operate at maximum
efficiency. Proper temperature control becomes very important. Variations in temperature lead to
component thermal shock, resulting in excessive downtime. High particulate counts in the atmosphere
contaminate and cause problems. Corrosives have short- and long-term adverse effects. Vibration in
heavy industrial areas must be observed and considered. Radio frequency interference (RFI) must be
detected and prevented and so must electrostatic discharge (ESD).

  b. Conductive contamination of computer room equipment by zinc whiskers can cause voltage or
signal perturbations leading to machine errors or equipment shutdown. Zinc whiskers can grow on metal
stringers or on the bottom or sides of floor tiles that have a zinc electroplated-passivation coating on the
tile’s sheet metal pan. As floor tiles are moved or disturbed, the zinc whiskers break off , become
airborne , and make their way inside computer systems’ equipment. The zinc whiskers lodge themselves
in electronic components of logic cards and power supplies causing either a voltage or signal perturbation.
At this point the machine posts an error or shuts down. Inspection, cleaning, and floor tile replacement
can prevent or correct this problem. However, computer room floor tile manufacturers have identified
this problem as no zinc electroplated floor tiles have been manufactured for several years.

  c. The five most prevalent causes of computer and electronic problems are: (1) poor or improper
grounding of equipment, (2) loose wiring connections, (3) improper computer room temperature and
humidity control, (4) degraded power, and (5) systems mismatching.

  d. Power line noise, poor regulation, and impulse transients can cause a host of problems when
coupled into sensitive electrical and electronic circuits. Steps can be taken to reduce these problems by
proper conditioning, grounding, and shielding. Yet, the weakest link in such circuitry may well be the
power supply, since these impulse transients and the line noise may be coupled through it and super-
imposed on the signals. Low-level analog circuits are not unique in this respect. Digital instrumentation,
computers, data processing equipment, recorders, etc., are all vulnerable.

  e. The commercial utility specifications define limits for amplitude variations, frequency variations,
and harmonic distortion for the power they furnish, but make no official mention of the fluctuations
lasting from 1 microsecond to 30 milliseconds that occur during load switching, transformer tap
switching, or phase compensation. Some utilities have, however, admitted that voltage variations to 300
percent, lasting up to 1 minute, may occur. Their position is understandable, considering that many of the
fluctuations, impulse transients, and interruptions are not caused by their own equipment.

                       2-1


---

TM 5-689

  f. When the electric lights flicker, it means that a power line voltage fluctuation has occurred. It also
means that the fluctuation lasted about half a second since the human eye cannot detect light intensity
changes that occur at much faster rates. However, many of the fluctuations that appear on power lines
last for only a few milliseconds or microseconds. Critical electronic circuits respond to these high-speed
fluctuations, causing erratic and erroneous operation. In addition, subjecting circuit components to the
cumulative stresses exerted by these impulse transients can cause intermittent changes or component
breakdowns that may occur even at a time when line transients are not present. Therefore, it is vital to
determine whether the power source is clean.

  g. The power line is exposed to all the noise voltages generated by the appliances, tools, and machines
that receive power from it, and these noise voltages are superimposed on the line voltage and coupled
through the power step-down transformer. When these noise voltages pass through the transformer, they
appear in the power supply. The noise voltages may cause the power supply to break into oscillation, or
may simply pass through it to appear in the electronic logic, control, or amplifier circuits. In either case,
the noise voltages may cause a computer to make errors, may induce non-programmed jumps, or may
actually cause equipment damage.

  h. Power line conductors also act as antennas and pick up radiated voltage from automobile ignition
systems, high-power transmitters, fluorescent lamps, diathermy machines, and lightning. These voltages
appear equally on each conductor of a pair, and consequently cannot be measured between them. The
voltages do, however, appear between either lead and ground. While this voltage cannot be detected
between the input leads, it is coupled through the distribution capacitances between the individual turns of
the primary and secondary transformer winding and appears as normal mode noise across the secondary
winding. Suppressing these line surges, dips, transients, and power fluctuations at their radiated voltage
sources would be an impossible task. The only realistic approach to eliminating their effects is to isolate
each critical equipment installation from these disturbances.

  i. There are only six basic categories of power line problems - total loss of line power for extended
periods, insufficient or excessive power line voltage, harmonic distortion, high frequency noise, impulse
transients, and combinations of these.

       (1) With a total loss of power, the equipment receives no power and does not operate.

       (2) During insufficie nt or excessive voltage, many types of equipment malfunctions and even
equipment damage can occur, but the condition can be detected by monitoring the power and voltage with
an ac voltmeter.

       (3) Harmonic distortion is detected using either an oscilloscope or a harmonic distortion analyzer.

       (4) The remaining types of problems, noise and impulse transients, cannot be detected by either the
human eye or an ordinary voltmeter, because neither the eye nor the meter can respond to the rates of
changes that occur when these phenomena are present. Studies have concluded that these types of
transient overvoltages cause almost 90 percent of soft and hard failure to computer systems through the
power line. The ideal device for detecting either noise or impulse transients is a power line monitor,
provided it has the proper characteristics and is correctly connected to the power circuit. However, even
many expensive monitors do not give total true peak amplitudes, rendering it impossible to correlate the
amplitude of an impulse and its relationship to the sinewave. The best power line monitors will record
transients with amplitudes varying from a few hundred voltage to several hundreds or thousands of volts
which last for as little as 30 nanoseconds. Some record amplitude, frequency, and time. Some monitor
only single -phase power lines and others accept and monitor three-phase inputs. Proper connections of
the monitoring equipment are a must. An improperly connected monitor may totally ignore line voltage

2-2


---

                                                                                                      TM 5-689

abnormalities, and the power line may be erroneously eliminated as the culprit when critical measuring or
data processing equipment malfunctions. Measurement limits must also be set properly or much of the
valuable data may be misinterpreted and ignored.

2-2. Commercial (utility) power

Electrical power generating plants are generally located in remote areas near some natural source of
power such as water, oil, or coal. The electrical power must be delivered to where it is consumed via a
transmission line. To minimize losses, power is transmitted at high voltage and low current. The
generator outputs three-phase, ac power normally at 18,000 to 22,000 volts. The voltage is then increased
through step-up transformers to 69,000 to 500,000 volts. These high voltage transmission lines are then
tapped off at substations, which step the voltage down and deliver three-phase ac power to the local lines
at some intermediate voltage such as 13,800 volts. The final reduction to a nominal 480 volts or 208/120
volts usually occurs at a transformer located near or in the user’s facility. This may also be derived from
the incoming 480 volt power line with an additional step-down transformer.

  a. Power is generated and transmitted in three-phase form for several reasons. Three-phase current
produces a rotating field , which is useful in motor applications. Poly-phase motors are simpler to
construct, are more efficient, and operate more smoothly , especially at larger horsepower ratings; i.e., 100
horsepower and above. Three-phase power also has less ripple when rectified, thus requiring less
filtering. The three-phase, three-wire transmission system delivers 1.73 (square root of 3) times as much
power as a two-wire, single -phase system. This results in a savings of 25 percent in the amount of copper
required to transmit a given amount of power a fixed distance with a given line loss and fixed voltages
between conductors.

  b. North American utility companies attempt to maintain electrical power within the following
tolerances.

       (1) The nominalfrequency of 60 hertz is maintained within ±0.5 hertz. The frequency is generally
within ±0.2 hertz in the United States and Canada because of the grid integrity between the two countries
and between areas within each country.

     (2) Utilities attempt to provide voltage with no harmonic distortion; i.e., no frequency component

other than the 60 hertz fundamental frequency.  There  will,  however,  inevitably  be  evidence  of  the  3rd,    th

                                                                                                                 5,

and    th  harmonics.

     7

       (3) Utilities also strive to limit noise spikes - generated either within or outside the service drop
(from transformer to main service panel). Spikes (impulse transients) from lightning and switching
operations will be present, however.

     (4) “Normal” voltage root mean square (RMS) amplitudes are as follows.

            (a) The 120 volts normal is permitted to drop to 111 volts at the utility feed (distribution
transformer).

            (b) From the utility an additional 3 percent voltage drop is allowed to the service entrance
(meter).

           (c) A 2 percent drop is considered acceptable from the service entrance to the equipment.

                                                                                                                 2-3


---

TM 5-689

            (d) The lowest allowable RMS value at the equipment is, therefore, 105 volts without
brownouts.

2-3. Power line phenomena

There are six basic power line disturbances or anomalies.

  a. A loss of voltage or a complete power outage can range from downed power lines to failed
transformers, to tripped circuit breakers, etc. These power outages may last for a short one-half cycle of
the 60 hertz sinewave (8.3 milliseconds) or for several hours. Most are no longer than a few seconds.

  b. High or low voltages/amplitude changes can be detected with a voltmeter or a voltage recorder.
Causes may be power lines, distribution panels , and/or the wiring being too heavily loaded. In addition,
being too close to the source of the power or too far from the source of power can cause large voltage
fluctuations, as well as starting or stopping heavy motor loads, non-uniform loading of poly-phase
transformers, or poor regulation. If an undervoltage condition continues for more than 0.5 cycle (8.3
milliseconds), but less than 1 minute, this is referred to as a sag . If an overvoltage condition continues for
more than 0.5 cycles (8.3 milliseconds), but less than 1 minute, this is referred to as a swell. Longer than
1 minute they are referred to as an undervoltage or overvoltage.

  c. Harmonic distortion occurs when the normal sinewave is mis-shaped caused by harmonics
(multiples of the primary frequency). When 60 hertz power is generated, multiple harmonic frequencies
are generated but normally only the odd harmonics have sufficient amplitude to be of concern. Generally,
these harmonics can only be detected by specially designed equipment. Flat-topping of the sinewave, as
seen on an oscilloscope, is the first indication of harmonic distortion. Under severe conditions, the
sinewave can look extremely distorted. Causes may include overloading or improper loading of
transformers, faulty regulation transformers, fluorescent or other electric -discharge lighting, and/or data
processing equipment.

  d. Noise is normally detected as bad or faulty data and then investigated with an oscilloscope.
Oscilloscopes are used to detect and analyze high frequency events or even to analyze the 60 hertz power
sinewave. Noise is a low voltage, low current, high frequency signal riding on the 60 hertz sinewave and
is characterized by having a repeatable frequency pattern, one that can be determined and analyzed.
Generally it is electromagnetic interference (EMI) and is caused by having the power or data lines or the
equipment too close to a source of EMI; a large motor or transformer for instance. Improper grounds or
grounding can also be a cause. Noise can also be RFI if a radio tower or transmitter is located nearby.

  e. Transients or impulses are high voltage, high-current, fast bursts of energy riding on the 60 hertz
sinewave. They also exhibit a non-repeatable frequency pattern even when resulting from the same
repeated event. They exhibit extremely fast rise times (1 microsecond to peak) and last for less than 8.3
milliseconds, usually decaying to 50 percent of peak value in 1 millisecond or less. Because they have no
repeatable frequency pattern and are random in occurrence, they are extremely difficult to detect. Power
line analyzers must be used to detect the presence of transients although the first indication of their
existence is usually data errors, computer crashes, and damaged circuitry. Microprocessor based
equipment is very susceptible to damage from these anomalies. Transients occur whenever the current
through any inductive load (motors, transformers, coils of any kind) is changed at a rapid rate. This rapid
change in current is the result of switching actions, sudden power outages, and applications of power.
Transients are also induced on power and data lines by nearby lightning strikes or having data lines too
close to power lines that are being switched.

2-4


---

                                                                                                                                    TM 5-689

  f. The most common anomaly is any combination of the above. While any of these problems can and
do occur by themselves, the more general rule is for them to occur in combinations. Transients always
accompany voltage outages. High or low voltages may result in noise when power supplies are put under
the strain of having to work at input voltage levels outside their design limits.

  g. Different anomalies have different affects on various types of equipment. Take, for example, the
length of a power interruption. A wall clock or scanner may be unaffected for up to four cycles without
power. Other equipment like card readers, symbol generators, and many computers cannot stand to be
without power for even one-half cycle (8.3 milliseconds). The equipment that is the most susceptible to
short interruptions will also be the most adversely affected by the short duration impulses and vice versa.

  h. Manufacturers attempt to build some protection into their equipment but competition limits what
they can do economically. The Information Technology Industry Council (ITI) sets guidelines for such
protection by suggesting an ac input power profile envelope shown in appendix B. They suggest that
information technology equipment should be designed to meet these guidelines. However, even if the
equipment were designed to this power profile guide, the envelope does not cover the power profile of the
utilities supplying the power.

  i. Power companies attempt to provide the cleanest and most stable power (input voltage)to the ir
customers. There is very little attempt to constrain anomalies shorter than one half cycle (8.3
milliseconds); i.e., impulses, EMI, RFI. The input power line may carry short duration variations (less
than 8.3 milliseconds duration) whose voltage amplitudes can be hundreds of times greater than nominal.
These “Type I disturbances” are often damaging to electronic equipment. Between 8.3 milliseconds and
0.5 second the power line may still vary as much as +30 percent to –40 percent of nominal. These “Type
II disturbances” (sags and swells) may also adversely affect the equipment as will the ‘Type III
disturbances,” voltage dropouts, and overvoltages.”

       (1) To counteract these conditions and protect computerized equipment from these anomalies, the
ITI recommends that all computerized equipment be designed to operate within the set guidelines.
Equipment designed and manufactured to meet this recommendation should then withstand any variations
within the guidelines. Therefore, an impulse with voltage amplitude less than 200 percent of nominal
rated RMS and shorter than 100 microseconds duration should not adversely affect the equipment.
Neither should those less than 100 percent and shorter than 1 millisecond or less than 30 percent and
shorter than 8.33 milliseconds.

       (2) Engineers from IBM conducted a study from which they were able to determine the incidence
rate of harmful power line disturbances. They studied a large number of installations over an extended
period of time and in 1974 published their findings in a document [1] “Monitoring of Computer
Installation for Power Line Disturbances,” G. W. Allen and D. Segal, Institute of Electrical and Electronic
(IEEE) Winter Power Meeting Conference Paper C74-199-6. The results showed that 88.5 percent of
power line disturbances were Type I disturbances, 11 percent were Type II disturbances, and 0.5 percent
were Type III disturbances. Type I, II, and III disturbances were defined as having durations of less than
0.5 cycles, 0.5 to 120 cycles, and greater than 120 cycles, respectively.

            (a) While Type I disturbances are the most damaging to equipment and data, even Types II and
III can be of great importance for customers who cannot tolerate the inconvenience and high cost of
downtime or erroneous data, loss of data, etc. There will be many cases where a customer may need and
be willing to go to great expense to eliminate even the least frequent of these occurrences.

                                                                                                                                             2-5


---

TM 5-689

            (b) Electronic chips have become denser – more than one million components on a small chip
– and are thus even more susceptible to Type I disturbances. Utilities are attempting to hold closer
tolerances on the voltage, and yet, sags and swells (Type II) and outages (Type III) are on the increase.

       (3) Several recent power quality surveys have been conducted and published in an effort to define
the electrical environment. These studies are [2] “Diagnosing Power Quality-Related Computer
Problems,” T. S. Key, IEEE Transactions on Industry Applications (1979); [3] “The Quality of U.S.
Commercial AC Power,” M. Goldstein and P.D. Speranza, INTELLEC (IEEE International
Telecommunications Energy Conference, 1982); [4] “Canadian National Power Quality Survey Results,”
M. B. Hughes and J. S. Chan, Proceedings of EPRI’s PQA ’95; [5] “Point of Utilization Power Quality
Study Results,” D. S. Dorr, IEEE Transactions on Industry Applications (1995); [6] “Preliminary Results
of Monitoring from the EPRI Distribution Power Quality Project,” D. D. Sabin and T.E. Grehe,
Proceedings of EPRI’s PQA ’95; [7] “Power Quality Site Surveys: Facts, Fiction, and Fallacies,” F. D.
Martzloff and T.S. Gruzs, IEEE Transactions on Industry Applications (1988); and [8] “Matching
Appliances to their Electrical Environments,” T. S. Key, D.S. Door, M.B. Hughes and J.J. Stanislawski,,
Proceedings of EPRI’s PQA ’95. Studies [1], [2] and [3] are compared in study [7] and in the appendix of
IEEE Std. P1100-1992. Studies [4], [5] and [6] are compared in study [8].

       (4) Recent studies have redefined Type I, II, and III disturbances as transient, momentary, and
steady-state disturbances respectively. Transient disturbances include unipolar transients, oscillatory
transients (such as capacitor switching), localized faults, and other events typically lasting less than 10
milliseconds. Momentary disturbances are voltage sags, swells, and interruptions lasting more than 10
milliseconds but less than 3 seconds. Steady-state disturbances are undervoltages, overvoltages, and
interruptions that last 3 seconds or longer.

2-4. Power quality require ments

Prior to design and installation of a sophisticated automated data processing (ADP), the end user should
request from the electric utility a report on the quality of distribution supplied power at the location.
Quality of supplied power is intended to include not only the annual expected outage rate at the specified
feeder location, which is now available from feeder outage records, but also a voltage sag history using
the following methods.

  a. Install one power analyzer per selected substation to record on paper or magnetic tape the
magnitude of voltage sags and their duration in cycles together with date and time of occurrence.
Installations would be made at one major distribution substation per 25-mile radius with the monitored
voltage being the distribution supply voltage as stepped down by metering or station service transformers.
Only voltage sags of 10 percent or greater would be monitored.

  b. The voltage sag histories would be collected monthly and the cause of the recorded sags identif ied
from fault records to establish location and type of system fault causing the voltage sag.

  c. Short circuit computer runs would be performed duplicating the fault conditions to establish the
magnitude and duration of the monitored sags, which occurred at the non-monitored substation busses.
The duration assigned would be the same as that recorded at the monitored station.

  d. Annual voltage sag histories would then be developed for all distribution substations.

  e. The above steps establish voltage sag histories for all major substation busses on the electric supply
system. One remaining step remains and that is to establish the expected voltage sag history at the
customer’s computer location on the feeder. If the computer is to be supplied from a feeder originating

2-6


---

                                                                                                                                    TM 5-689

from the same distribution substation bus for which the substation voltage sag history was developed, no
further corrections are necessary. If on the other hand, the feeder in question originates from another
distribution substation bus which is not directly connected to the bus for which the substation voltage sag
history was developed, it will be necessary to adjust the counts of voltage sags due to feeder faults in
proportion to the total number of feeder faults occurring on the two busses. If the number of faults
occurring on feeders supplied from each bus of a two separate bus substation is about the same, the
correction will not be necessary.

2-5. Power quality parameters

Since over 88 percent of the harmful power line disturbances recorded in the IBM study were Type I
disturbances (transients), additional investigation of the specific disruptions is warranted. The majority of
these disturbances (49 percent of the overall total) were “oscillatory, decaying transients.” These would
be the result of lightning or some other sharp electrical “hit” that would excite the natural frequency of the
subject electrical system (much like a tuning fork is excited). The electrical system will then ring at its
natural frequency, fn (different electrical systems have different natural frequencies just as different
mechanical systems have different natural frequencies), defined as:

                                                                                                                    1/2

                                                     fn = 1/2π(LC)

The amplitude of the natural frequency (voltage in this case) will then decay at an exponential rate
dependent upon the stiffness of the electrical system, amount of wiring, wire sizes, layout, etc. Due to the
fact that induced lightning can be one of the initiators of this oscillatory action, the initial amplitude
(voltage) of the resultant sinewave can be very high (thousands of volts) and may contain a lot of energy
(thousands of joules).

  a. The remaining Type I disturbances were “voltage spikes (impulse transients)” characterized by very
fast rise times and slow decay times. These single uni-directional events contain a wide range of
frequencies as indicated by the 1 microsecond rise time to full amplitude indicating the presence of
several extremely high frequency components in excess of 1 megahertz (MHz) and the relatively slow
decay time to 50 percent of full amplitude of 1 millisecond (1000 microseconds). This slow decay time
indicates low frequency components of 1 kilohertz (kHz) or less.

  b. For years, transient suppression devices have been tested for “impulse transient” suppression
capability using transient wave forms given in American National Standards Institute (ANSI)/IEEE Guide
C62.41-1991, IEEE Recommended Practice for Surge Voltages in Low Voltage AC Power Circuits.
These wave forms were 1.2 microseconds x 50 microseconds for the voltage and 8 microseconds x 20
microseconds for the current. A study of wave forms actually recorded in the field was published as an
IEEE paper (85 WM 243-1). This study, conducted in nine cities across the United States, over a 2-year
period shows a much different real wave shape. Both voltage and current were recorded and correlated.
To be accepted as valid data, the voltage and current events had to both occur within a 50 microsecond
window.

       (1) A total of 277,612 correlated events were recorded measuring the peak value and the time to
reach peak along with the 50 percent decay point value and the time to reach that value. The computer
rendition of the resultant wave form is a 1 microsecond x 1000 microseconds voltage wave form and a 60
microseconds by 1000 microseconds current wave form. A total of 89.4 percent of the calculated wave
forms fall within +10 percent of these wave forms.

       (2) From the data it was concluded that the equipment in the field and associated transient
suppressors are subjected to far greater amounts of transient energy than in the lab. The frequency

                                                                                                                                             2-7


---

TM 5-689

content of these wave forms is also much wider than the laboratory wave forms, ranging from below 1
kHz to over 1 MHz. Many suppressors that give good to excellent results in the lab cannot handle the
field experienced transients with their high energy and broad frequency range.

  c. Data lines and instrumentation lines, while not directly affected by power line problems, can be
adversely affected if located in close proximity to power lines or if located where they can be affected by
induced lightning transients. Power lines or power wiring and control wiring can induce noise into data
and instrumentation wiring when it is run parallel to them. Transients on the power lines paralleling data
lines can also be induced onto these low voltage lines and damage data or instrumentation equipment. As
little as 10 volts applied to a transistor-transistor logic (TTL) circuit for only 30 nanoseconds will cause
the destruction of the TTL junction. Data line instrumentation should never be run in close parallel
proximity to power and control voltage lines.

  d. The affect of lightning transients may be reduced by using shielded cable for data transmission, and
instrumentation care must be taken to ground the shield on these cables only at one end of the cable run to
prevent induced circulating currents.

  e. Data and instrumentation cable, run underground, should be buried at least 4 feet down to protect
from lightning. Lightning striking the ground can raise the ground potential and induce transients into
underground wiring not encased in steel pipe. Most buried cable is now encased in either polyvinyl
chloride (PVC) or fiberglass if not directly buried and, therefore, is subject to lightning inducted
transients if buried too close to the surface. Data and instrumentation cable inside buildings should never
be run closer than 5 feet to an outside wall in a high lightning area for the same reason, induced transients
from nearby or direct lightning strikes.

2-6. Detection of power line anomalies

Instrumentation has been developed to record and better understand the power line disturbance
phenomena. Iron vane meters were developed to read voltage, current, frequency, and then power to
enable operators to maintain constant voltage and frequencies and read current values. Then came
recorders to supply a constant record of these events. As long as the major interest was only in the areas
of no voltage, high and low voltage, sags, and surges, these instruments were sufficient.

  a. Electronics brought in a new dimension; higher data frequencies meant that things happened faster
and new instrumentation was developed to read and record these events, recording oscillographs and
oscilloscopes. The higher frequency, faster electronics were also more susceptible to the higher
frequency anomalies on the power supply line. Power line noise (EMI) and impulses were mistaken as
data by the electronics and processed as such. Solid-state electronics and the microprocessor chip brought
us high density – thousands and millions of solid-state components on a small 1/4” by 3/8” chip. The low
voltage requirement of these circuits and the high density made them extremely susceptible to even minor
overvoltages. A TTL junction will be destroyed at only 10 volts.

  b. Due to the randomness of the power line anomalies, it became necessary to develop high-speed
event recorders to detect the presence of the high-speed anomalies: noise and impulses. Such an
instrument will measure and record only the event itself. The occurrences of events can be recorded for
later analysis without the requirement of the constant presence of the operator or the accumulation of
meaningless recorded data. A general discussion is presented below of two different power line monitors,
which can record and analyze power disturbances.

       (1) The first monitor, called the “universal disturbance analyzer” is extremely versatile and because
of this feature requires greater skill to set up and operate. If limits are not properly chosen and

2-8


---

                                                                                                                                    TM 5-689

programmed in, and depending upon the “print-out mode” chosen, the user can either end up with
insufficient data upon which to base corrections decisions or with large amounts of superfluous data to
wade through to determine what problem needs to be corrected. Such data to the untrained individual
may lead them to believe that one problem exists when the problem is really something else. For
instance: one might be misled to believe that sag-surge problems existed because of reams of sag-surge
data when in reality the limits had been set so low that what was actually recorded was a lot of normal
voltage fluctuations well within the permissible limits set by equipment manufacturers and governing
bodies; i.e., fluctuations not harmful to equipment. However, when properly set up, this type of
instrument can produce much valuable data for the experienced user.

       (2) The second monitor, called the “power line consultant” does not have the versatility of the first.
However, this lack of versatility results in ease of set up and eliminates questions regarding the validity of
the final data. This instrument can produce all the data required to make an intelligent decision about a
problem, and therefore the proper correction device, without the skill needed with the first instrument.

                                                                                                                                             2-9


---

                    TM 5-689

         CHAPTER 3
POWER CONDITIONING

3-1. Automated data processing (ADP) power requirements

Typical applications of electronic equipment are in mainframe and distributed data processing
computers and their peripherals, customer-owned telephone switching systems, and increasingly
complex electronic industrial control equipment. Faulty performance of these units can cause
inconvenient, expensive, and even dangerous situations. These electronic circuits in this
equipment operate on dc power. The source of this power is an internal dc power supply which
converts (rectifies) the ac power furnished by an electric utility to the various dc voltage levels
required by the electronic equipment. Internal dc power supplies are designed to isolate the
electronic equipment from moderate disturbances on the ac power lines. But the fact is that
frequently types and levels of power line disturbances are encountered which pass, little altered,
through internal power supplies. This causes aberrations in the dc voltage levels , which can
result in everything from faulty operation to complete shutdown or failure of the electronic
equipment. One of the major problems when electronic equipment performs incorrectly or shuts
down unexpectedly is locating the source of the trouble. Scrambled data in a recirculating
memory can, for example, look like a hardware or software failure on the surface whereas it
might actually have been caused by an intermittent blip on the power line. It is, therefore,
important that a user know something about the kinds of disturbances that appear on his power
line and how often they occur. This does away with much of the finger pointing by the user and
various service personnel when a problem does arise, and at the same time permits steps to be
taken to prevent these disturbances from reaching the dc power supplies. The proper choice of
equipment designed to isolate the power supply from line disturbances is wholly contingent on
the precise types of power line disturbances expected, the estimated frequency of occurrence, and
the importance to the user of keeping the electronic equipment on line.

  a. Electronic equipment used in computers operates on dc power equivalent to that obtained
from an ordinary battery. It is a single-polarity (either plus or minus) and is derived by
converting or rectifying the ac power supplied by a utility. Typical dc levels required by solid-
state electronic equipment are plus or minus 5, 12, 15, and 24 volts. Power line disturbances,
which pass through a power supply , can cause dc voltage levels to rise or fall slowly or rapidly,
exhibit positive or negative spikes, or even drop to zero. Any of these occurrences can cause
faulty equipment performance, system shutdown, or even damage to sensitive electronic
components.

  b. The ac power generated by electrical utilities is characterized by alternating back and forth
between equal positive and negative voltage levels along a pure sinewave wave form. Because of
the sinewave characteristics there are various ways of describing ac power. The nominal 120
volts from an outlet is actually the effective or root mean square (RMS) voltage of the ac wave. It
is equivalent to 120 volts dc when supplying a pure resistance load such as an incandescent light
bulb – thus the name effective. The negative and positive peak voltages are equal to 1.414 times
the RMS voltage, while the average one-cycle voltage is equal to 0.637 times the positive or
negative peak voltage. Thus for our 120-volt outlets, the peak voltages are equal to 120 times
1.414 or 170 volts, while the average voltage equals 170 times 0.637 or 108 volts. In turn, of
course, the RMS voltage is equal to 0.707 times the peak voltage. In the United States, ac power

                    3-1


---

TM 5-689

is generated at a frequency of 60 hertz or cycles per second (in other countries 50 hertz power is
common). This means there are 60 full sinewaves per second so that a cycle is 16.7 milliseconds
long.

       (1) Utilities supply residential structures and commercial and industrial offices with single -
phase ac power. Usually there are three-wire systems with two “hot” conductors and a neutral.
The neutral is grounded at the service entrance (normally to a water pipe) and this ground lead or
a ground connection is carried throughout the system. One hot lead, the neutral, and the ground
connection are carried to the standard 120 volt outlets. Under proper operating conditions only
the hot and neutral leads carry current; the ground connection is for safety purposes. If there
should be an insulation breakdown in the energized equipment, the ground connection will drain
the current back to ground, thus preventing personnel exposure to 120 volts.

       (2) For higher powered equipment, such as ranges, air conditioners, electric heating,
clothes dryers, and some office equipment, the two hot conductors and ground are wired to
special outlets. This yields 240 volts and halves the current that would be required if the same
equipment was designed to operate on 120 volts.

       (3) For large electric power users, utilities generate and transmit three-phase ac power in
which the three phases are time phased by one-third cycle, effectively producing three ac wave
forms. Three-phase power is less expensive to transmit, simpler to rectify into low-ripple ac
voltage, and three-phase ac motors are simpler and operate more smoothly than single -phase
motors. The single -phase residential power mentioned above is obtained by tapping off one
phase of a three-phase transmission line.

       (4) Every industrial facility and most large computer installations are supplied with three-
phase power. The most popular configurations for supplying this three-phase power are the four-
wire “wye” with ground and the ungrounded and grounded “delta.” Wye circuits can usually
handle either 480 volt or 208 volt three-phase loads and 277 volt or 120 volt single -phase loads.
The 120 volt level is, of course, that obtained from the standard ac outlet, whereas 277 volts is a
popular level for fluorescent lamp fixtures. Both types of delta circuits normally supply either
480 volt or 240 volt three-phase loads.

3-2. Power line disturbances

All of these types of ac circuits are susceptible to line disturbances which may either be
introduced via the utility’s transmission lines or generated internally within the user’s own
facility. Breaker tripping and reclosure for fault clearance, random switching of heavy loads,
lightning strikes, noise, motor controllers, and an endless number of similar occurrences can and
will introduce ac line disturbances about which the utility can do little. With the exception of
frequency variations, all power line disturbances are voltage phenomena, with the type of
disturbance and the means of compensating for it depending on the magnitude and time period of
the voltage excursion beyond a nominal voltage band. Fluctuations of the RMS voltage value
over an appreciable time interval are known as undervoltages or overvoltages, shorter term
variations are called sags or swells, and spikes or transients of very short duration and
considerable peak magnitude are known as impulses. Dropouts or line interruptions are where
the line voltage goes to zero, a situation that can exist for any time period.

  a. Any RMS voltage fluctuation which exceeds allowable limits for more than 1 minute is
classed as an undervoltage or overvoltage.

3-2


---

                                                                                                                         TM 5-689

       (1) Undervoltage situations are normally caused by purposeful utility “brownouts” and/or
line overloading either within the same facility or by neighboring facilities on the same
transmission line. Utilities cause brownouts by deliberately dropping the voltage by 3, 5, or even
8 percent to extend system capability, particularly on hot days with heavy air-conditioning loads
and limited reserve.

       (2) Overvoltage is caused by poor line regulation by a utility or by lighter than expected
loads on the line. If, for example, an emergency forced several neighboring plants to shut down
during the normal working day, transmission line voltage would undoubtedly rise until the utility
could bring it back under control.

       (3) Overvoltage causes electronic equipment to run hot, stressing components and possibly
prompting immediate or incipient failures. Equipment shutdown may also occur if the heat
dissipation forces the enclosure to reach unsafe high temperatures and a thermal limit trips.
Normal utility voltage variations, plus internal facility feeder line voltage drops and the ever
present possibility of brownouts in certain sections of the country, make undervoltage situations
fairly common. If the voltage drops sufficiently, all kinds of erratic performance can be expected
as electronic equipment nears the point where it will stop operating completely. Also, motor
loads draw more current and run hotter and less efficiently under low voltage conditions.

  b. Sags and swells are short-term special cases of undervoltage and overvoltage conditions
where the voltage fluctuation exceeds the allowable limit for at least some significant portion of
one cycle (say 10 milliseconds) and reenters the limit band within 1 minute. Because sags and
swells are transitory conditions caused by momentary occurrences, they usually exhib it larger
voltage excursions than longer term undervoltages and overvoltages.

       (1) Swells look the same as sags except that the voltage exceeds the upper limits that are
usually established at 10 percent. Sags are most commonly caused by switching on to the line
heavy loads such as large motors, electric furnaces, substantial air-conditioning capacity, etc.
Such loads draw heavy inrush currents, which drop the voltage for short periods and line voltage
regulation typically takes a definite period to recover from such heavy loads. Swells are
frequently caused by the reverse – the disconnecting of heavy loads from the line with the
accompanying voltage increases.

       (2) If sags or swells have sufficient magnitude to be reflected through the internal dc
power supplies, they can play havoc with the performance of sensitive electronic equipment. For
example, equipment designed to initialize upon startup may re-initialize after a severe sag – it
confuses the sag with the turn off and turn on of power. And much electronic equipment shuts
down and stays shut down if the voltage drops below a limit for more than a few milliseconds.
Particularly disruptive situations can occur if part of the equipment in an integrated system starts
up after recovery from a sag and the balance of the equipment does not.

  c. Impulses are deviations from the ideal ac sinewave having very short duration compared
with one cycle – typically from a fraction of a microsecond to a very few milliseconds. Their
forms range from single pulses with extremely short rise time and gradual decay to oscillatory
disturbances persisting for five to ten oscillations within a gradually decaying envelope. They
may either increase or decrease the instantaneous amplitude of the sinewave described as a
“spike” or “notch,” respectively.

       (1) Impulses can range in magnitude from a fraction of peak voltage up to hundreds or
thousands of volts and by far cause the largest voltage swings of any types of line disturbances.

                                                                                                                                  3-3


---

TM 5-689

The proper way to examine an impulse disturbance is to filter out the sinewave. If any impulse
spike with a magnitude of 500 volts occurred at the top of a nominal 120 volt sinewave, then the
actual voltage impressed on the load would be 500 volts plus the peak instantaneous voltage of
170 volts or 670 volts.

       (2) Two other measures of an impulse disturbance are impulse duration and impulse
strength. Impulse strength is defined as the volt-second area under the impulse curve. It is clear
that impulse strength and impulse duration are related and either adds a significant measure to the
knowledge of the problems a transient can cause beyond the straightforward measurement of
impulse magnitude by itself.

       (3) It is also important to know the direction or source of an impulse. Did it occur at the
source of power via the utility power feeder or was it generated in the electronic equipment?
Either is possible, and of course, the solutions to the two problems are radically different.

       (4) There are two types of impulses: common-mode transients where the voltages to
ground of the ac power line phases rise and fall together, and normal-mode transients where the
phase-to-ground voltages vary from phase to phase. Common-mode impulses are caused by such
things as lightning and utility breaker tripping and reclosure, usually resulting in single spikes or
notches on the sinewave. In contrast, normal-mode impulses are typically the result of
connecting or disconnecting heavy loads or power factor compensating capacitors. These
impulses exhibit decaying oscillatory characteristics with frequencies up to and above 5 kilohertz
(kHz). It is important to know the type of impulse since the means of suppressing them are
different.

       (5) Impulses are the most insidious type of power line disturbance. They occur without
any indication at all to operating personnel, and if not suppressed can cause scrambled data
transmission or memory data resulting from bit changes, over-stressed components, or even
component failure.

  d. Loss of total power to zero voltage can occur for any time period from a portion of a cycle
on up to hours or even days. Very short-term dropouts are frequently caused by utility breakers
tripping to clear a fault and then reclosing automatically, while long-term line interruptions can
result from any serious utility problem – power lines felled by a storm or fires in substations are
typical. Most computers and sensitive electronic equipment, which depend on digital data
manipulation, will shut down automatically if a power dropout exceeds a very few milliseconds.

  e. Frequency deviation is seldom a problem with utility-supplied power in the United States.
Frequency rarely varies more than 0.5 hertz from 60 hertz (a common computer specification)
and is always averaged out over a 24-hour period because of the number of clocks and other time-
based devices, which depend on constant frequency for accuracy. However, if power is generated
locally by a private power plant or by motor-generator (M-G) sets or diesel or gas turbine
engines, frequency can wander over a 10 hertz band from 55 to 65 hertz. Frequency shifts of this
magnitude can cause problems with time-based equipment or frequency-sensitive circuits.

3-3. Acceptable limits for ac power

Although there are no industry standards to define “acceptable” ac power, the Information
Technology Industry Council (ITI) has issued a guideline (shown in appendix B) that describes
the ac input voltage envelope which typically can be tolerated by information technology
equipment (ITE) . The various sags, swells, undervoltages, overvoltages, and impulses exhibited

3-4


---

                                                                                                                         TM 5-689

by a power line can be classified as acceptable or unacceptable based on whether they fall within
or without the dashed-line boundaries. In these guidelines, long-term overvoltages or
undervoltages which deviate from the nominal voltage by more than +10 percent or -20 percent
for longer than 500 milliseconds (30 cycles) can be expected to cause problems. Any swell or
sag, which exceeds +20 percent or –30 percent of the nominal voltage for more than 20
milliseconds (1.2 cycles), is apt to cause faulty operation of ITE. The impulse band is more
difficult to define because of the frequent high magnitude of the transients, but, generally
speaking, impulses greater than the nominal peak sinewave voltage can degrade a system’s
operation. If monitored power line disturbances fall outside these boundaries, particularly during
pre-installation site inspection, a careful analysis may avoid future problems.

3-4. ADP protective equipment

Although it is difficult to make any generalizations concerning the benefits that accrue from the
use of line protective equipment, it has been estimated that clean power versus that taken directly
from the “average” power line reduces load equipment outages by 40 percent and maintenance
costs by 25 percent. The choice to use protective equipment is both an economic and technical
consideration. The wide range of power line conditioning and isolating equipment varies greatly
in price and in the types of disturbances it will protect against. Less expensive protective
equipment may not provide much improvement and costly equipment for every conceivable
power line problem may not be economically justifiable.

  a. Once the profile and estimated frequency of occurrence of line disturbances via power line
monitoring is determined, an economic analysis should be performed. This analysis should
include a complete life cycle cost analysis associated with purchasing and operating the
protective equipment, the costs incurred as a result of load equipment outages, faulty
performance, hardware damage, and any other anomaly that may occur for various degrees of
power line protection.

       (1) Costs to consider are the initial purchase price of line conditioning or isolating
equipment, installation costs, and operating costs. Within these, consideration should be made
for site preparation, equipment operating efficiency, and maintenance requirements.

       (2) Site selection and preparation may be a major contributor since some line condit ioning
equipment may require special space and site preparation. In new building construction, space
limitations may not be a problem, but space may be a major factor when a large computer
installation in an existing facility requires retrofitting.

  b. Special factors requiring consideration prior to selection of protective equipment are as
follows.

       (1) Transformer hum or rotating equipment noise may require a sound baffled enclosure or
location away from occupied areas.

       (2) Large battery banks in some uninterruptible power supply (UPS) systems are heavy
and require substantial surrounding space to permit proper maintenance. Certain battery types
also generate explosive fumes that an isolated space with forced ventilation and extra reinforcing
because of heavy floor loading.

                                                                                                                                  3-5


---

TM 5-689

       (3) Environmental conditions must also be considered if the load protective equipment is
located in the same space as the computer or other electronic load devices. The line conditioning
and isolation equipment generates heat, which may require additional air-conditioning capacity.

       (4) Equipment efficiencies must also be considered in the cost. No load protective
equipment is 100 percent efficient, and efficiencies may range from as low as 50 percent to a high
96 percent. This electrical energy incurs a cost with the efficiency of some types of protective
equipment decreasing with time so this continuing cost may increase as the equipment ages.
Obtain efficiency rates from the equipment supplier for the actual conditions under which the
equipment will be operating.

       (5) Equipment maintenance is a continuing expense, which must also be considered. All
electronic systems require periodic inspection and will fail from time to time. Modular plug-in
construction and diagnostic aids speed troubleshooting and repair, but parts and labor still cost
money. Batteries require periodic monitoring of electrolyte and terminal cleaning, and all
rotating equipment needs, at minimum, regular bearing inspection and occasional bearing
replacement. Backup engine-driven alternator sets have particularly high maintenance costs.

  c. Isolation transformers used for protective devices are primarily intended to attenuate
common-mode impulses. Some types also provide limited attenuation of normal mode impulses.
Isolation transformers perform no voltage regulating function. Sags, swells, undervoltages, or
overvoltages will be reproduced faithfully on the transformer secondary. If the power line
voltage is consistently stable and high frequency impulses or noise is the only problem, then a
suitable isolation transformer may eliminate your power line disturbance difficulties.

       (1) While a standard transformer has no dc connection between primary and secondary, the
windings are ac coupled through an infinite number of coupling capacitances. At high noise
frequencies, these capacitances have relatively low impedance and transfer the noise directly
from primary to secondary. Thus a standard transformer has practically no ability to attenuate
impulse noise but instead passes it right through.

       (2) The basic isolation transformer helps this somewhat by inserting an aluminum foil
electrostatic Faraday shield between the primary and secondary windings. While this shield does
not completely eliminate this coupling capacitance, it shunts a lot of it to ground and thus
minimizes the transformer’s ability to transfer common mode impulses. Power line noise on the
primary is considerably attenuated by the time it reaches the secondary.

       (3) The ultimate isolation transformer (variously called high, super, ultra, etc., by different
suppliers) further reduces this coupling capacitance with box electrostatic shields around the
primary and secondary windings. Capacitances between the windings and the frame and
windings are broken up into smaller series capacitances and shunted to ground, thus minimizing
input-to-output capacitance of 0.001 pico-farads, and the better ones are as low as 0.0005 pico-
farads. This very low level of coupling capacitance effectively prevents common mode impulses
on the power line from reaching the load.

       (4) Attenuation capability for a top quality isolation transformer is expressed in decibels
(dB), a shorthand way of indicating attenuation ratios. The higher the dB rating the isolation
transformer has the better the noise attenuation. Well designed dc power supplies exhibit
considerable normal-mode noise attenuating capability.

3-6


---

                                                                                                                         TM 5-689

       (5) High quality isolation transformers are available in sizes ranging from 125 VA single-
phase to 130 kVA three-phase. Isolation transformers with somewhat lower levels of impulse
attenuation are also available . There are many different suppliers with various quality level
transformers so almost any specific performance requirement can be satisfied.

  d. Line voltage regulators do exactly what the name implies – their purpose is to maintain
reasonably constant output voltage to the load in the face of variations in power line voltage.
There are many different ways of accomplishing this and among the basic types there are
innumerable variations, all with their own advantages and limitations. The following covers one
or two popular or generic versions of five basic types of voltage regulators.

       (1) Most line regulators will correct utility voltage sags and swells of 15 percent to output
voltages to the load ranging from ±3 to ±7 percent of nominal. Many will bring extreme utility
sags in the area of 20 to 30 percent, back to ±7 to ±10 percent of the nominal output voltage.
Some things to consider when picking a line voltage regulator are cost, speed of response, output
impedance, audible noise, efficiency at part and full load, sensitivity to load power factor and
unbalanced three-phase loads, and harmonic distortion.

       (2) A few types of line regulators can attenuate impulses to a modest degree, but most
perform the regulation function only and pass impulses right through. In fact, some types may
create additional impulse noise by internal switching.

       (3) There are two types of motor-actuated regulators, the motor-driven brush type and the
induction regulator type. The motor-driven brush type moves across many taps on an
autotransformer, causing the series transformer to buck or boost the voltage to the load. The
same function is performed by an induction regulator where rotating the regulator one direction or
the other varies the magnetic coupling and raises or lowers the output voltage.

       (4) Motor-actuated voltage regulators are generally inexpensive and can handle heavy
loads, but they are slow in response and can only correct for gradual voltage changes. In
addition, their electro-mechanical parts require substantial maintenance and output impedance is
high. They are not often used with critical and sensitive electronic equipment.

       (5) The saturable reactor regulator controls output voltage by varying the impedance of the
saturable reactor winding in series with a step-up autotransformer. These regulators are relatively
inexpensive, and have a wide load range, low maintenance requirements, and yield fair normal-
mode impulse protection. However, the disadvantages often outweigh these plus factors.
Sag/swell response is sluggish (in the range of 5 to 10 cycles), output impedance is high (as much
as 30 percent of the load impedance), and they are sensitive to lagging load power factor.

       (6) The ferro-resonant transformer voltage regulator is one of the more popular regulators,
especially in the lower size ranges of 0.5 to 2 kVA. The ferro-resonant transformer core structure
is designed so that the secondary operates in flux saturation and the secondary winding resonates
with the capacitor in a tuned circuit. As a result of this saturated operating mode, changing the
primary or line voltage may change the current but will not vary the flux or the secondary
induced voltage. Thus the unit performs a voltage regulating action. A unique characteristic of
the ferro-resonant regulator is its ability to reduce normal-mode impulses. Since its regulating
capability is based on driving the secondary winding into saturation, transients and noise bursts
are clipped.

                                                                                                                                  3-7


---

TM 5-689

            (a) The basic ferro-resonant transformer puts out a high harmonic content squarewave,
not suitable for supplying sensitive electronic loads. A properly selected neutralizing winding
cancels out most of the harmonic content of the output voltage and yields a satisfactory low-
distortion sinewave.

            (b) The ferro-resonant regulator has a response time of about 25 milliseconds or 1.5
cycles, good reliability, minimal maintenance requirements, reasonable cost, good normal-mode
impulse attenuation, and good regulation. Because of the tuned circuit on the output, it is
sensitive to frequency variations (1 percent frequency change causes 1.5 percent output voltage
change), but this is not much of a problem with tight utility network frequency control. More
important are its high output impedance (again up to 30 percent of load impedance), sensitivity to
both leading and lagging load power factors, and low efficiency at partial loads. Efficiency is
about 90 percent at rated load, but since the unit wastes about 10 percent of rated load regardless
of what load level it is operating at, efficiency drops with load. This, in turn, results in heat
dissipation and the generation of audible noise.

            (c) In addition, ferro-resonant regulators have poor capacity for handling momentary
overloads such as might be caused by high motor starting current, and output voltage collapses at
somewhere about 150 percent of full load. Oversizing is not the whole answer to this problem,
since this causes reduced efficiency and increased heat dissipation. In summary, the ferro-
resonant regulator is useful in small systems that do not contain large motors.

       (7) The last type of line voltage regulator to be looked at here is the electronic tap-
switching autotransformer. With this unit the proper triac (or back-to-back silicon controlled
rectifier [SCR]) is energized depending on whether the power line voltage must be increased or
decreased. Voltage correction occurs in discrete steps rather than continuously. Resolution
depends on the closeness of the taps, and switching impulses are minimized by changing taps
when the line voltage is near a zero crossing.

            (a) The electronic tap-switching transformer has many good features. Response time
is fast at about 0.5 cycles or 10 milliseconds, regulation is good, output impedance is in the range
of 5 percent of load impedance, efficiency is high at about 95 percent, and the units are
insensitive to load power factor and load unbalance.

            (b) The disadvantages are a somewhat high cost and slightly poorer reliability when
compared to the more rugged units.

            (c) This type of regulator is popular and widely used in the medium sizes of 3 kVA
and up.

  e. Line conditioners combine the functions of isolation transformers and line voltage
regulators and thus both attenuate impulses and regulate output voltage. For this reason, a line
conditioner can protect against the principal types of power line disturbances except for voltage
dropouts and line interruptions. It is possible to create a line conditioner by placing separate
voltage regulators and isolation transformers in series. Properly matching the two can be tricky,
and the package is bulkier and generally more expensive than using a single unit designed to
perform the total line conditioner function.

       (1) There are basically two types of packaged line conditioners on the market, regulating
line conditioners and enhanced isolation transformer line conditioners. The first uses an

3-8


---

                                                                                                                         TM 5-689

improved ferro-resonant transformer voltage regulator, while the second includes an electronic
tap-switching voltage regulator in conjunction with a high quality isolation transformer.

       (2) The ferro-resonant transformer line conditioner is more popular, being lower priced
and highly reliable. The box and Faraday shields around the primary and compensating windings
give it essentially the characteristics of a high quality isolation transformer in series with a ferro-
resonant voltage regulator. The expected normal-mode impulse attenuation from the saturated
operation of the ferro-resonant transformer, plus the electrostatic shields, make this line
conditioner a good attenuator of both common-mode and normal-mode impulses.

       (3) A typical high quality line conditioner should regulate output voltage to within ±4
percent of nominal for ac input power line voltage changes from –20 percent to +10 percent.
Total harmonic distortion (THD) will be less than 5 percent, and both types of impulses should be
attenuated up to 120 dB. Other features may include electromagnetic interference/radio
frequency interference (EMI/RFI) noise filtering and quality transient voltage surge suppression
on the output of the line conditioner as almost all line conditioners are intended to serve multiple
loads.

  f. M-G sets consist of a motor driving an ac generator or alternator so that the load is
completely electrically isolated from the power line. In the past, in some cases dc or induction
drive motors were used requiring close speed control to maintain stable frequency to the load.
The tendency nowadays is to use synduction or synchronous motors. The synduction motor
resembles an induction motor but runs at synchronous speed. With either of these unit types,
alternator speed and thus frequency to the load is as stable as power line frequency. M-G sets
have been widely used to supply 415 hertz power to the mainframe computers which require this
frequency, but recently there has been a substantial shift to the use of solid-state inverters.

       (1) M-G sets shield the load from impulses and from voltage sags and swells. For
substantial power line voltage changes of ±20 percent or more, voltage to the load is still
maintained at ±1 percent of nominal. The unique feature of the M-G is its ability to bridge severe
short-term sags or voltage dropouts. The rotational momentum of the rotating elements permits
the M-G to span dropouts of up to about 300 milliseconds or 0.3 seconds, the type that cause
lights to flicker and plays havoc with digital circuitry. This period can be extended by adding
inertia via a flywheel.

       (2) The problems with M-G sets are mostly on the output or load side. Very high
alternator output impedance can cause substantial voltage dips in response to sudden load
changes such as result from large inrush motor starting current, and response to load changes is
sluggish in the range of 0.25 to 0.5 seconds. Also, the drive motor may overheat under long-term
brownout or low line voltage conditions.

       (3) The cost of a M-G set is somewhat more than for a functionally equivalent line
conditioner. Also, M-G efficiency is relatively low at about 80 percent, so that electrical energy
costs over its lifetime may be substantial. Heat dissipation, weight and bulk, and the potential for
annoying audible noise are factors which must be considered in M-G installation. The use of
rotating field exciters has eliminated the need for slip rings, with the consequent brush inspection
and replacement, but as with any rotating equipment, bearings must be inspected and periodically
replaced.

  g. If continuous operation is necessary during a line voltage interruption lasting more than a
half second or so, then an UPS is required. The basic UPS consists of a rectifier/battery charger,

                                                                                                                                  3-9


---

TM 5-689

battery bank, and inverter. The rectifier/battery charger takes ac line power of the proper voltage
and frequency and generates dc power. The battery bank takes the place of the rectified dc power
source if line power fails. The inverter with suitable filtering converts the dc power back into a
sinusoidal wave form. UPS systems are complex, expensive, have high output impedance, and
frequently require special installation facilities and increased air-conditioning capacity to
dissipate the heat. The proper UPS will protect the load equipment from all types of power line
disturbances.

       (1) The size of the battery bank determines the length of time the inverter will supply
normal power to the load. For a large computer installation this time is usually about 15 to 20
minutes, since this is the length of time the computer will operate without air conditioning before
the high-temperature trip causes shutdown. An alarm is activated when 5 minutes of battery time
remains to permit orderly shutdown. If the load equipment does not require special air
conditioning (most process control systems and medical electronics, for example) then it is
practical to size the battery bank to cover more extended outages. In this situation, up to an hour
of running time is not uncommon and much longer periods are possible .

       (2) There are various ways of employing a UPS. The specific configuration to be used is
largely dependent upon the reliability of power required by the load.

            (a) Continuous mode describes the configuration whereby the load power is always
obtained from the UPS except during UPS failure or periods of required maintenance. In this
case, the load is manually switched to the raw power line via the maintenance bypass line,
causing substantial discontinuity in load operation.

            (b) In the forward-transfer mode, the load is normally supplied from the utility power
line and the UPS idles. When power fails, the load is automatically transferred to the UPS. In
normal operation with this configuration there is no load protection from power line disturbances,
except for severe sags and voltage outages, unless other load protection is installed in the utility
power line. This tends to defeat the major objective of the UPS.

            (c) More popular is the reverse-transfer mode configuration. Here, the load is
normally supplied by the UPS and is automatically switched to the utility power line only when
the UPS malfunctions. This mode provides maximum benefit from the UPS.

            (d) If more extended protection is required, further backup via an engine-driven
generator must be added. Here, battery time is usually only about 5 minutes – long enough to get
the engine-driven generator up and synchronized with inverter output. Of course, such an
installation is very expensive and requires special facilities and substantial maintenance. It
should only be considered if extended power outages are frequent and continuity is critical.

            (e) For very critical situations there are other configurations that can be considered,
including double - and triple -redundant UPS systems backed up by multiple engine-drive
generators.

       (3) An especially sensitive element, in terms of continuity of service, is the type of
automatic transfer switch, which is used. The electro-mechanical transfer switch is actuated
when the sensed output voltage to the load drops below 94 percent of nominal. However, sense
and switch time ranges from 20 to 50 milliseconds. This time delay will cause most sensitive
load equipment to severely malfunction or even shut down. The static transfer switch is much
faster. It switches upon sensing a failure in inverter input circuitry, a drop in load voltage to 94

3-10


---

                                                                                                                         TM 5-689

percent of nominal, or overload on the inverter exceeding 130 percent of full load. The sense and
switch time is only about 4 milliseconds, so there is a good chance the load’s dc power supply
will ride right through this short delay and the load will see no discontinuity. Of course, in all
transfer situations inverter output must be phased with the power line.

       (4) Several different types of inverters used in the UPS system are available. The type that
is included in a UPS depends to some extent on the power level requirements for the UPS and on
the particular tendencies of the supplier.

            (a) The pulse-width-modulation inverter incorporates two inverters, which regulate by
varying the pulse width and yield an output, which closely resembles a sinewave. This reduces
filter requirements and provides good voltage regulation and response times in the range of 100
milliseconds. However, the extra inverter and feedback networks make this inverter complex and
expensive, and it is usually used only at power levels over 50 kVA.

            (b) The most popular inverter type in the smaller size ranges is the ferro-resonant unit.
It consists of an oscillator, which controls the SCR switches, a ferro-resonant transformer, and a
harmonic filter. Its saturated operation produces a regulated output voltage and current limiting,
so complex voltage and current feedback networks are not required. Efficiency varies from 50 to
88 percent depending on load level, and response time is about 20 milliseconds. The simplicity
of this inverter leads to relatively low cost.

            (c) SCRs are used in the inverter section of most large UPS products. A SCR is a
semiconductor device with unique properties. It can serve as a rectifier and as a static latching
switch. It can handle more power (both voltage and current) than typical transistors, under both
continuous and surge conditions. It is the most rugged semiconductor available , and in most
cases, can handle more watts per dollar than other types of semiconductors. The SCR serves as
an on-off switch. The SCR can be turned on by a momentary application of control current to the
gate, while transistors require a continuous on signal. The SCR can be turned on in about 1
microsecond, and static switch sections turned off in 10 to 40 microseconds. The SCR is ideal for
rectifier UPS products, but has disadvantages when applied to inverter sections.

            (d) In recent years manufacturers have been changing over to transistorized inverters in
their UPS products. A transistor permits current to flow through a circuit when the base drive of
the transistor receives an electrical signal. Transistors are not latching devices, so they can be
turned off by simply removing the base drive signal. To minimize switching losses, however,
special drive circuits are required to turn the devices off quickly. Transistors also experience
saturation losses during the conduction stage of the cycle. A transistor is considered efficient if it
has high “gain” – when relatively small amounts of drive current applied to the base permit a
comparatively large current to flow in the collector emitter circuit.

            (e) Bipolar transistors produce gain by current conduction. A current applied to the
base causes a proportional current to flow in the collector/emitter. A special type of bipolar
transistor is called a Darlington, which consists of two transistors linked together. The
collector/emitter of the first transistor is used to activate the base drive of the second. Darlingtons
have a higher gain than a single bipolar and are easier to control. The disadvantage is that they
have higher saturation losses and require special drive circuits to minimize switching losses.

            (f) Field-effect transistors (FETs) work differently than bipolars. They do not inject
current into the base. Instead, they conduct when they sense a voltage on the gate. This means
that relatively little power is consumed in the gate drive. However, the power-conducting portion

                                                                                                                                3-11


---

TM 5-689

has a relatively high resistance. This creates excessive losses and lower efficiency, making it
unsuitable for use in large UPS products.

            (g) Insulated gate bipolar transistors (IGBTs) combine the best of conventional bipolar
transistors and FETs. Like FETs, they only require a voltage across the base in order to conduct.
However, like conventional bipolars, they are efficient conductors of current through their
collector/emitters. IGBTs are the preferred transistors for UPS applications. They are
significantly more efficient and are easier to control than any other power semiconductors.
IGBTs are commonly available for UPS applications up to 750 kVA without paralleling devices.
Larger devices are available, but have not achieved as much market penetration.

       (5) The battery charger/rectifier system operates in a constant-current mode during the
initial charge period, automatically switching to a constant-voltage mode towards the end of the
charge cycle. This gives maximum battery life consistent with fast recharge, and prevents
excessive battery outgassing and water consumption. The charger provides a float voltage level
for maintaining the normal battery charge, and sometimes, a periodic higher voltage to equalize
certain types of batteries. There are seve ral different types of batteries generally selected for UPS
applications. The most common types break down into two technologies: lead acid and nickel
cadmium (NICAD). Lead-acid batteries are further broken down into two types: lead-
acid/calcium and lead-acid/antimony. Lead-acid calcium batteries can be divided into two
categories, wet cell (or flooded) and valve-regulated lead acid (VRLA) sometimes mistakenly
referred to as maintenance-free.

            (a) The sealed VRLA lead-calcium battery uses either a gelled electrolyte design
(GELL), or an absorbent glass mat (AGM) design, does not require the addition of water, and has
no problems with outgassing or corrosion. This type is used when the batteries are integral to
small UPS systems, and where the batteries must be placed in occupied areas. Their big
disadvantage is a limited life span of about five years under optimum conditions. Conventional
wet cell lead-calcium batteries are the preferred type in most UPS systems. Watering and
terminal cleaning are required only about every six months and manufacturer’s warranties are for
up to 20 years. They do outgas hydrogen under charge conditions and must be placed in a secure,
ventilated area.

                (1) The AGM design uses a very fine glass filament matted together and wrapped
around the battery plates. This glass mat serves two purposes. Through capillary action, the acid
electrolyte is drawn up between the plates with the mat acting as the immobilizing agent. The
glass mat is not 100 percent saturated; thus there are small openings between the glass filaments.
These openings allow oxygen, which is generated on the positive plate during the final stages of
charging to migrate to the negative plate and through chemical reaction, convert back to water,
conserving the electrolyte.

                (2) The GELL uses a different approach by adding silica to the electrolyte. This
mixture will form a gell compound once the battery has formed. After set-up, the gell will have
many cracks in it. These cracks are essential to allow for the oxygen exchange between the
negative and positive plates. Once in contact, the same chemical reaction occurs as in the AGM
design.

            (b) Lead-antimony batteries are the traditional lead-acid units. Their performance is
equivalent to that of the lead-calcium batteries, but they require maintenance every three months
and life is only about one half that of the lead-calcium units. To retain their capacity, lead-
antimony batteries require monthly equalize charging.

3-12


---

                                                                                                                         TM 5-689

            (c) NICAD batteries are the most expensive of the various types. Their advantages lie
in small size and weight for a given capacity and excellent high and low temperature properties.
Life is long, nearly that of a conventional lead-calcium battery, and a six-month maintenance
period is adequate. They do require monthly equalize charging, as well as periodic discharge
cycles, to retain their capacity.

            (d) All of these batteries, except for the NICAD type, are surprisingly temperature
sensitive and should be maintained between 72°F to 82°F for optimum performance and long life.
Low temperatures reduce battery capacity and high temperatures shorten life. If batteries are to
be exposed to severe temperature swings, the NICAD type should be seriously considered.

  h. The magnetic synthesizer is a static electromagnetic (EM) three-phase ac power
regenerator. The device, powered from the ac utility line, uses no mechanically moving parts in
the generation process, and utilizes no semi-conductor elements in the power path. The output
wave form of the device is electromagnetically generated, and is complete ly isolated and
independent of the input in all parameters except two, the phase rotation and the frequency. The
output phase rotation of the device is governed by the direction of the input phase rotation, while
the output frequency is precisely keyed to the input line frequency. There is no electrical
connection between the input and the output of the device. The only power line disturbances not
correctable by a magnetic synthesizer are frequency deviations and loss of power, both of which
require a UPS to correct. An ideal application for a magnetic synthesizer is in a major urban area
where utility networks or loops are fed from multiple substations providing very reliable but
otherwise “dirty” power. The improved quality of power results from the synthesis of three-
phase 60 hertz voltage wave forms which remain essentially constant in magnitude and shape
over a large range of input voltage excursions in both the positive direction (surges) and the
negative direction (sags). The device consists solely of saturable iron core reactors and
transformers, together with capacitors, and employs the principles of ferro-resonance for its
operation.

       (1) As long as the core of an inductor is not magnetically saturated, the inductor will
support a voltage across the windings. However, as the inductor core approaches saturation, the
current through the winding will begin to increase. When the core becomes completely saturated
and can absorb no more magnetic flux, tremendous currents will flow through the winding, and
the voltage across the winding will approach zero. In essence, the device will go from an open-
circuit to a short-circuit.

       (2) If the voltage across the saturated reactor is now reversed, the core will begin
magnetizing in the other direction and will again act as an open-circuit. The inductor will support
this reversed voltage until the core becomes saturated in the opposite direction. At this point, the
reversed current increases to a maximum and the voltage decreases to a minimum. In standard 60
hertz non-saturating devices, the core flux is oriented in one direction for 1/120 second; but
before it can reach the point where the core cannot absorb any more flux, the voltage is reversed,
which begins to orient the core flux in the other direction for the next 1/120 second.

       (3) The amount of time for the saturation of a reactor core to take place is measured in
volt-seconds. The volt-seconds rating for an inductive reactor depends upon the frequency and
the voltage desired to be present across the reactor winding before saturation.

       (4) A saturating transformer is inherently a non-linear device. It is this non-linearity which
makes it valuable in regulating circuits. In a saturating transformer, as in conventional

                                                                                                                                3-13


---

TM 5-689

transformers, production of an output voltage depends upon the changing magnetic flux in the
transformer core. But unlike conventional transformers, the saturating transformer is designed for
the core to reach saturation after a given number of volt-seconds. Because the flux no longer
changes when the core is saturated, there is no voltage output at this time.

       (5) The primary waveshape and output power level determining elements of the magnetic
synthesizing power conditioner are saturating transformers. In order to obtain the desired outputs
from these transformers, energy must be injected into the devices. In the magnetic synthesizer
power conditioner, energy is introduced through line chokes into the primary windings of the
saturating transformer elements. The line chokes are designed to pass the electrical energy from
the input lines, while blocking the waveshape and voltage level information. The chokes act as
current sources and buffers for the saturating transformer elements. The primary windings are
duplicates of the regulated windings of the secondary. Because the primary windings are wound
on top of the secondaries and are isolated from them, there is introduced the ability to reject
common-mode noise. The primary-over-secondary arrangement also provides a fail-safe feature.
A broken connection at any point will not cause the voltage to rise toward infinity at the load.
There is no high-voltage failure mode in this device.

            (a) Six interconnected saturating transformers are utilized for power wave form
synthesis in the power conditioner. At any particular time during operation, one of these cores is
unsaturated while the other five are saturated in directions specified by the interconnection
configuration. When the one core finally becomes saturated, the voltage across it collapses and it
becomes a conductor. That process causes reversal of the voltage across one of the remaining
five cores, which then goes out of its present saturated state and begins building toward saturation
in the other direction. When the core reaches saturation in the other direction, it will then reverse
the voltage across yet another core.

            (b) The sequence of saturation and voltage reversals among the transformers is
determined by the transformer interconnection configuration and by the phase sequence of the
driving circuit. The process continues as long as the power conditioning device is in operation.
During the time that a transformer core is unsaturated, there is voltage present in the transformer
interconnecting circuit of the power conditioning device. Therefore, sequencing of the
transformers will produce a constant series of voltage pulses on the interconnecting circuit. The
parameters of each pulse are determined by the volt-seconds design of the corresponding core.

            (c) The three-phase sine waveforms which are produced by the design and
interconnection of the transformers in the power synthesizing device contain less than 3 percent
THD. Because each of the wave forms is produced by a saturated element, both the shape and
amplitude are stable. Thus, the transformer configuration becomes a source which dictates the
voltage level and waveshape of the resulting output. Close voltage regulation is maintained and
clean waveshape is assured, each independently of the input line conditions.

  i. High quality transient voltage surge suppressors (TVSSs) are available to protect ac
systems at all distribution voltage levels. The TVSSs have let-through voltages much lower than
basic lightning arresters and are designed for facility and sensitive equipment protection. TVSSs
are designed to handle much higher speed transients than lightning arresters.

       (1) Underwriter’s Laboratory (UL) Standard 1449, Standard for Transient Voltage Surge
Suppressors, categorizes TVSS into three types: (1) Direct plug-in TVSS devices incorporate
integral blades for connection directly to electrical outlets by consumers wherever point-of-use
surge protection is desired. (2) Cord connected TVSS devices have a power supply cord

3-14


---

                                                                                                                         TM 5-689

terminating in an attachment plug for connection to nearby electrical outlets by consumers,
wherever area of use is desired by the end user. (3) Permanently connected TVSS devices are
equipped with terminals or leads that are hard wired by qualified personnel into the building’s
electrical service entrance and distribution system.

       (2) UL recently revised UL Standard 1449, Second Edition, August 15, 1996, for
permanently connected TVSS devices to increase the test duty cycle a TVSS must pass. The
measured limiting voltage test was previously known as the “transient voltage surge test.” This
test assigns a suppression voltage rating, or let-through voltage, to a product under test. The first
and last test surge current magnitude used to benchmark and measure the TVSS capability has
been reduced from 3000 A to 500 A. While the duty cycle part of the test has been reduced in
number of impulses from 24 to 20, the current magnitude has been increased from 750 A to 3000
A. The benefit of this change is that the TVSS under test is now subjected to a more strenuous
duty cycle test than with the previous version of the test. A wide variety of additional tests have
been included in the revised UL 1449, including testing of components (capacitor endurance test),
enclosure integrity tests (enclosure impact test, crushing test, mold stress-relief distortion test,
mounting hole barrier test, and adequacy of mounting test), as well as manufacturing and
production line testing.
3-5. Power distribution systems
Power distribution systems, otherwise called movable power systems or computer power centers,
are sometimes confused with load protective equipment. The purpose of a power distribution
system is to provide convenience in distributing power to computer system elements, to avoid
some electrical contractor expenses, and possibly to obain a better job, particularly if the
contractor is not experienced in computer system installation. Power distribution systems are
made by some computer suppliers and independents, but they do not provide any protection
against power line disturbances unless specially equipped to do so. However, such a UL listed
system should certainly be considered for complex computer installations since it can provide
proper wiring and grounding, monitoring of key power system variables, and other features which
will assure that good installation practices have been followed.

                                                                                                                                3-15


---

            TM 5-689

 CHAPTER 4
GROUNDING

4-1. Purpose of grounding

The primary purposes of grounding for circuits, cables, equipment, and systems are to prevent
shock hazard, protection of circuits and equipment, and reduction of electromagnetic interference
(EMI) due to electromagnetic (EM) field, common ground impedance, or other forms of
interference coupling. The various grounding systems used (lightning, power, and/or signal) are
integral parts of a facility or system whether they involve vehicles such as automobile s, ships,
missiles, or aircraft; buildings; or building complexes. Like other facility components, grounding
networks are exposed to the ambient EM environment. This environment includes many sources
ranging from incident radio frequency (RF) signals to lightning, and from atmospheric noise to
internally generated stray currents.

  a. The objective and plan of the facility ground network design should consider all aspects to
the degree required for the particular mission of the facility in its environment and in the context
of cost-effectiveness. The use of the term facility ground network is intended to be in the
collective sense; it includes the power fault protection network, lightning protection network,
building or structure (or frame, hull, fuselage skin, etc.) ground, equipment ground, signal
ground, instrument ground, data ground, etc. Attempts should be made to integrate the three
features of lightning protection, electrical safety, and EMI control.

  b. The integration of these features in the design may be difficult because they usually do not
fall under the responsibility of the same individual, group, or perhaps company, and they may not
even be considered in the same time frame. In the case of a building, lightning protection and
power grounding are often decided by an architectural and engineering firm during the structural
design phase, and EMI control aspects are left to the electronic equipment engineers for
resolution long after the building is finished. When this happens, tradeoffs become difficult.
However, the various grounding networks must interface and they all must operate in a common
EM environment. To alleviate this situation in future facilities, equipment designers and EMI
engineers must be allowed to participate early in the facility design process. For existing
structures, those persons responsible for electronic equipment grounding should become
thoroughly familiar with the power and lightning-protection ground networks through reviews of
drawings, performance of current and voltage measurements, and physical inspections before
deciding upon the final signal/equipment grounding networks.

4-2. National electrical code (NEC) requirements for grounding

Requirements for the safe installation of electric conductors and equipment within or on various
facilities are contained in National Fire Protection Association (NFPA) 70-1999 and the NEC.
The purpose of the NEC is “the practical safeguarding of persons and property from hazards
arising from the use of electricity.” The NEC is the most widely used code having been adopted
by the majority of the states, counties, municipalities, cities, etc. The federal government,
through the Occupation Safety & Health Administration (OSHA) adopted the NEC in 1971.
Since this code is universally adopted, it serves as a basis for computers and computer systems’
equipment complying with the minimum requirements found in the Code.

            4-1


---

TM 5-689

  a. The NEC contains the intent for grounding. The requirements for grounding the process
control computers and distributed control systems are contained in several sections of the NEC.
These sections specifically address equipment (enclosures), above 50 volts, below 50 volts, and
grounding electrode.

  b. The grounding of the electrical system and connection of the electrical system neutral to
earth must be connected at only one point to the equipment grounding conductor. Reasons for the
electrical system to be grounded are stabilization of the voltage (that is, to keep it from floating
above a set reference point), facilitation of clearing phase to enclosures/ground faults, and
limitation of lightning and line surges. The NEC calls for bonding the electrical system to the
enclosures of (1) conductors and wireways such as conduit, and (2) equipment.

  c. Article 250, Part F, of the NEC addresses the requirements for equipment grounding.

       (1) The word “enclosure” is defined in Article 100 as “The case or housing of apparatus, or
the fence or walls surrounding an installation to prevent personnel from accidentally contacting
energized parts, or to protect the equipment from physical damage.” In Article 250, Part D,
“Enclosure Grounding” could be confused with the word enclosure as being similar to a raceway,
which may be rigid or flexible conduit, wireways, busways, etc. All equipment enclosures will,
therefore, be referred to simply as “equipment” as is done in Part F of Article 250. Although
computers and distributed control systems are not mentioned in name, Section 645-15 states that
“All exposed noncurrent-carrying metal parts of an information technology system shall be
grounded in accordance with Article 250 or shall be double insulated.”

       (2) If the equipment is fastened in place or connected by permanent fixed wiring methods,
which is not the usual case, then the exposed noncurrent-carrying parts likely to become
energized shall be grounded, if within 8 feet vertically or 5 feet horizontally of ground or
grounded metal objects and subjected to contact by persons (refer to Section 250-110). It can be
inferred from Section 110-26 that concrete, brick, or tile floors are considered as grounded. Since
the walls are assumed to be grounded, the floor could also be assumed to be grounded since it
touches/attaches to the wall. However, to assure adequate ground protection the floor must be
bonded to a known ground. Most computer systems are connected by cord and plug. Although
these systems are not mentioned by name, it is accepted practice that the noncurrent-carrying
equipment parts be grounded.

  d. NEC 250-20(b) addresses the grounding requirements of electrical systems above 50 volts
to 1000 volts. The article addresses systems supplying premises wiring and premises wiring
systems. It does not address the electrical supply system powering the computers and distributed
control systems. The building electrical system can be a grounded, ungrounded, or high
impedance (resistance) grounded system. The definition of premises wiring from Article 100-A
of the NEC is: “That interior and exterior wiring, including power, lighting, control, and signal
circuit wiring together with all of their associated hardware, fittings, and wiring devices, both
permanently and temporarily installed, that extends from the service point of utility conductors,
or source of power such as a battery, a solar photovoltaic system, or a generator, transformer or
converter windings to the outlet(s). Such wiring does not include wiring internal to appliances,
fixtures, motors, controllers, motor control centers, and similar equipment.” It is, therefore,
prudent to assume that this section does not apply then to anything other than premises and
excludes equipment connected by cord and plug.

4-2


---

                                                                                                                         TM 5-689

  e. Grounding requirements for electrical systems below 50 volts are addressed in Article 250-
20(a). Thus, if computers and distributed control systems were to use electrical systems less than
50 volts ac, and if the conditions covered below apply, the ac system must be grounded.

       (1) If the transformer supply system exceeds 150 volts to ground

       (2) If the transformer’s primary system is ungrounded

       (3) When installed as overhead conductors outside of buildings

  f. Section 250-30 of the NEC addresses the grounding of separately derived systems. Large
automated data processing (ADP) systems can have a separately derived system through a delta-
wye grounded transformer. This article of the NEC shall apply when an ADP is powered by such
a network.

       (1) The grounding electrode shall be as near as practicable to and preferable in the same
area as the grounding conductor connection to the system. The grounding electrode shall be: (1)
the nearest available effectively grounded structural metal member of the structure; or (2) the
nearest available effectively grounded metal water pipe; or (3) other electrodes.

       (2) There is an exception dealing with transformers rated not more than 1000 VA. A 1000
VA transformer can use the frame, and, therefore, a grounding electrode is not necessary. This
exception is stated in Section 250-30(a)(2).

  g. The key to one of the problems with computers and distributed control systems is found in
Part H, “Grounding Electrode System,” Section 250-50. This part of the NEC states: “If
available on the premises at each building or structure served, each item (a) through (d), metal
underground water pipe, metal frame of the building, concrete-encased electrode, and ground ring
shall be bonded together to form the grounding electrode system.” This is normally interpreted as
meaning that all metallic systems within the structure shall be bonded such that they have a
common ground plane. Where none of these electrodes are available, “Made and Other
Electrodes” may be used as specified in Section 250-52. These electrodes consist of metal
underground gas piping system, other local metal underground systems or structures, and
plate electrodes.

       (1) Many control system instruction manuals show rods as the only method of connecting
to earth for the electrical system and the computer system. This is probably a carryover from the
residential wiring practice, where the items listed as “grounding electrode system” are not
available and “made and other electrodes” (rods) must be used.

       (2) Section 250-60, “Use of Air Terminals” states that “Air terminal conductors and . . .
rods . . . used for grounding air terminals shall not be used in lieu of the made grounding
electrodes required by Section 250-52 for grounding wiring systems and equipment.”

       (3) Section 250-52 of the NEC states that “Where more than one electrode is used, each
electrode of one grounding system (including that used for air terminals), shall not be less than 6
feet (1.83m) from any other electrode of another grounding system.” The isolation between
electrical systems, which was sought through separate ground rods, was usually non-existent.
The electrical systems were actually tied together through the “sphere of influence.” The radius
of the sphere of influence of a driven rod is equal to the rod’s depth. If a 10-foot rod is driven
into the earth, everything within a radius of 10 feet will be under the influence of the 10-foot deep

                                                                                                                                  4-3


---

TM 5-689

rod. The average resistance between a second rod driven within a sphere whose radius is 10 feet
and which is centered at the top of the first rod will be negligible. They would be considered as
being connected together, assuming average earth conditions.

  h. The authority having jurisdic tion of enforcement of the NEC will have the responsibility
for making interpretations of the rules, for deciding upon the approval of equipment and
materials, and for granting special permission contemplated in a number of the rules (Section 90-
4). If the installation complies with and exceeds the NEC requirements, both stated and inferred,
no problems should be encountered in receiving approval for the installation. This will be true if
all the electrical systems, grounding systems, equipment enclosures, etc., are all connected and
bonded together.

4-3. System configurations

Electrical systems can encompass one item or several. A system may represent a small self-
contained electronic circuit totally within the confines of a case, cabinet, rack, or it may be an
extended collection of equipment racks or consoles distributed over a wide geographical area.
The grounding requirements and procedures will be markedly different for these different types
of systems. One way of distinguishing between different types of systems is to examine the
manner by which power is obtained and how the equipment elements are interconnected with
each other and with other systems. Based on these two considerations, systems may be identified
as isolated, clustered, distributed, multiple -distributed, or central with extensions.

  a. An isolated system is one in which all functions are accomplished with one equipment
enclosure. An isolated system should not be confused with a floating system, which has no
external ground. Some isolated systems may be floating while others must be grounded.

       (1) Only a single power source is associated with an isolated system. (Single power source
means one battery pack, one branch circuit supply, etc.). In addition, only one ground connection
(to structure, to earth, to hull, etc.) for the entire system is needed for personnel protection or
lightning protection, or no facility ground connection at all is required. No conductors except the
power cord and the appropriate ground exists because no interfaces (power or signal) with other
equipment or devices, which are grounded, are present or needed. Common examples of isolated
systems are hand-held calculators, desktop computers (off line), home-type radios, televis ion
receivers, etc.

       (2) Grounding requirements for isolated systems are illustrated by figures 4-1 and 4-2.
They typically include a third wire ground if powered with single -phase ac or a ground-cable run
with the power conductors if multiphase ac is involved. Double insulated systems as defined in
NEC Article 250-114 are not required to have a third ground wire. Battery driven systems
usually do not require any grounding, but the system should be isolated. It is important that
isolated systems are not located near lightning down conductors, or near other grounded metal
objects, and in areas where very high RF voltages may appear on equipment cases. The internal
signal grounding requirements of the isolated system are those determined by the designer as
necessary for proper self operation.

  b. A clustered system as shown in figure 4-3 is characterized as having multiple elements,
equipment racks, or consoles located in a central area. Typical clustered systems include
minicomputers, component stereo systems, medium scale data processors, and multi-element
word processors.

4-4


---

                     TM 5-689

                     ISOLATED
                     SYSTEM,
                     AC POWER

        TO CIRCUITS

INPUT
POWER

SAFETY
GROUND

                  Figure 4-1. Minimum grounding requirements for ac powered isolated system

       (1) A distinguishing feature of a clustered system is that it utilizes one common power
source, e.g., a battery or a single ac power connection. There are likely to be multiple
interconnecting cables (signal, control, and power) between the members of the system but not
with any other system. A clustered system only needs one facility structure ground tie to realize
personnel safety and lightning protection requirements.

       (2) Grounding for a clustered system requires that one connection be made to structural
ground as illustrated by figure 4-4. If the power supplied is single -phase ac, the third wire
ground provides this connection. If the power supply is three-phase ac, (according to Paragraph
250-122 in the NEC) a supplemental ground conductor shall be installed. It shall be sized in
accordance with Section 250-122 and Table s 250-66 and 250-122 of the NEC. Battery powered
systems should have one ground connection to the structure. The signal ground referencing
scheme used between the elements of the system should reflect the particular signal
characteristics (frequency, amplitude, etc.) of the various pieces of equipment. This scheme may
be single -phase or multiple -point.

            (a) If a multiple -point scheme is used, the signal ground may be realized with cable
shields, auxiliary conductors, or a wire grid or metal sheet under or above the array of equipment.
In a benign (quiet) EM environment, signal grounding with cable shields or auxiliary conductors
between the interconnected pieces is acceptable. In high level, multi-signal environments, this
type of grounding scheme should be avoided because of the antenna pickup effects of the
multiple conductors. Signals coupling to the ground conductors produce common-mode voltages
between various source-load pairs and raise the threat of interference. A better method of

                     4-5


---

TM 5-689

                                     TO CIRCUITS

          +           -

                                                                 STRUCTURAL GROUND NOT NEEDED
                                                                 WITH BATTERY POWERED SYSTEMS
                                                                 EXCEPT FOR LIGHTNING ARC
                                                                 PREVENTION

          Figure 4-2. Minimum grounding requirements for battery powered isolated system

          Mainframe            Host                                           PBX

          Disk array  Printer        Communications
                                          Processor

                                                Figure 4-3. Clustered system
4-6


---

                                                                                                                         TM 5-689

     SINGLE
     AC
     CIRCUIT

                                                             STRUCTURAL GROUND
                                                             (i.e. SAFETY GROUND)

                                   Figure 4-4. Basic grounding of a clustered system

grounding should provide broad metal paths between the pieces of equipment of the system.
Overhead or underfloor ductwork, cable trays, and wire channels can frequently provide the
necessary signal grounding and fault protection network for a clustered system. The best
approach, and the one recommended for use in high level RF environments, will use a close-mesh
wire grid or a solid metal sheet for mounting the various pieces of equipment of the system.

            (b) In extremely severe environments as in the vicinity of a transmitter, the solid sheet
is preferred over the grid. Each cabinet is carefully bonded to this grid or sheet. All
interconnecting signal leads, power buses, etc., should be routed inside enclosures and beneath
the ground plane, preferably in conduit or in raceways. Note that the evolution from the poorest
to the best approach is aimed at rendering the system and its cables successively less effective as
a pick-up antenna for radiated RF energy, particularly in the broadcast, high frequency, very high
frequency, and ultra high frequency bands.

  c. A distributed system is one in which major elements are physically separated in a way that
requires equipment to be variously fed from different power outlets, branch circuits, different
phases of the line, or perhaps even different transformer banks.

       (1) In a distributed system, separate safety and lightning protection grounds to the facility
(vehicle) structure (frame) are required. Another common characteristic of a distributed system is
that multiple conductor lengths are likely to be greater than 1/10 of a wavelength at frequencies
where an interference threat exists. Examples of distributed systems include industrial process
control, environmental monitoring and control, communications switching, and large main frame
computer nets.

                                                                                                                                  4-7


---

TM 5-689

       (2) Effective grounding of distributed systems to achieve the required safety and lightning
protection for equipment and personnel, while minimizing noise and EMI, requires careful
application. To describe a stereotyped network or to list a set of rules is not considered prudent.
General guidelines follow.

            (a) If the system is ac powered, consider each major element (consisting of one or
more types of equipment essentially located at a particular location) as either an isolated or
clustered system, as appropriate. Proceed to ground each major element. Each and every signal
port on these isolated or clustered subsystems that must interface with other portions of the total
system, i.e., other subsystems, should be viewed as interfacing with a noisy world. As such, the
techniques for controlling unwanted coupling of radiated and conducted interference into the
signal paths must be fully employed. Obviously, discretion will be necessary. There will be
situations, depending upon the properties of the signal being transmitted from terminal to
terminal, the characteristics of the signal path, and the nature of the EM environment, in which no
additional protective measures are required. In general, adequate isolation must be provided
between the external (to the system) conducted and radiated noise environment and the signal
path.

            (b) Common battery distributed systems present a particular challenge. Such systems
are commonly found on aircraft where the fuselage is used for dc power return. The use of the
equipment rack, structure, hull, or fuselage for the power return path means that the structure
becomes the circuit reference. Therefore, voltage differentials between various points in the
structure appear in series with any single ended, unbalanced signal paths. Again, adequate
rejection against such conducted interference must be obtained.

       (3) Multiple distributed systems are similar to that of a distributed system except that there
are usually several systems contained and operating in the same general area. Typically, the
multiple systems share the primary power sources. A distinguishing feature of multiple
distributed systems is that they typically run a high risk of interfering with each other and are
susceptible to interference from facility noise and the external environment. Thus, in addition to
having grounding requirements like those discussed for distributed systems, additional shielding
and filtering requirements are necessary to minimize intersystem interference.

  d. A central system with extensions is illustrated in figure 4-5. It is distinguished from an
isolated or clustered system in that integral elements of the systems extend out from the central
portion at long physical and electrical distances. This system is distinguished from a distributed
system in that the extended elements obtain their power from the central element. Connections to
a power source are not made anywhere except at the main element. An example of this type of
system is an industrial process controller with sensors and actuators located remotely from the
data logger or controller.

       (1) The central or primary element of this type of system should be founded as though it
were a clustered or isolated system. Depending upon the operating frequency ranges and signal
levels of the extension elements and the characteristics of the EM environment, a single -point tree
or star grounding scheme may be used or a multiple -point scheme may be used.

       (2) It is likely that most systems of the central-with-extensions configuration will involve
relatively low frequency (audio or below) with operating bandwidths encompassing the power
frequencies. If this is the situation, a single -point tree is recommended. The ground mode would
be at the central element with one connection (the safety ground) made to the structure. Extended
elements should be floated or balanced. Twisted pair or balanced signal transmission-line

4-8


---

                   TM 5-689

Remote
Sensors/Actuators
(Typical)

                                                                                                    Controller

                                       Figure 4-5. Central-with-extensions system

conductors should be used between the central element and the extended elements. If radiated
coupling proves to be a problem, the extended elements should be configured, if at all possible, so
that the shields (as on coax, for example) from the central element can be continued to enclosure
the extended elements.

4-4. Ground configurations

  a. Single-point grounding means connecting one point (either the source or load end) of the
signal return side of the energy transfer loop to ground. There are many applications, which
require single -point grounding. Although definitely advantageous in many situations, in a multi-
equipment system or facility a single -point ground system can be very difficult to implement and
maintain as a true single -point ground system.

  b. Multiple -point ground attempts to realize an adequately low ground plane impedance, i.e.,
minimize ground reference voltage differentials, is the basis of multiple -point grounding. In
multiple-point grounding, the source and load end of every energy (signal) transfer pair is
connected to a ground plane (chassis, equipment cabinet, structural frame, printed circuit board,
etc.) by the shortest electrical path. The ground plane is also interconnected by the largest
feasible number of parallel paths. Ideally, the ground plane would consist of a solid metal mass
of lowest possible resistance.

  c. A signal ground is necessary for RF equipment and circuits which frequently utilize the
chassis, cabinet, or large unetched areas on printed circuit boards as ground planes for the signals
of primary interest. Large, common areas are effective RF signal grounds because wide metal
paths exhibit lower inductance, and thus lower impedance, than do round wires or narrow rods.
To retain the ground plane effectiveness, paths serving as individual component, device, or
network grounds must be short to minimize the circuit-relative impedance; thus, the overall
ground must be brought to the component, device, or network. RF interfaces (input and output
signal ports) are typically unbalanced and thus cable references, or signal grounds, must be the
same as the chassis or cabinet ground.

                                                                                                                                  4-9


---

TM 5-689

  d. The control of ground plane impedance is important in ensuring a noise-free system.
Interference between circuits and systems always exists between ground conductors.

       (1) Grounding conductors and paths exhibit inductive, capacitive, and resistive properties.
Having such properties means that grounding conductors and paths rarely provide the zero
impedance, or equipotential, reference plane which is sought for the grounding of signals. Any
unwanted signals, whether they are power or microwaves, pose a threat of interference to desired
signals whose circuits are referenced to the network.

       (2) If both source and load ends of a circuit are connected to a noisy ground reference, a
possibility exists for interference. Obviously, if the voltage differential between the source and
the load is reduced, the interference threat is reduced.

       (3) Reduction of interference can be done through lowering the impedance of the path
through which the interference currents (and, frequently, the desired signal currents) are flowing.

       (4) Ground noise problems can frequently be solved by providing more ground paths
through the bonding of all metallic members of an equipment cabinet, or of a structure, together
with low impedance interconnections. The technique, if thoroughly applied throughout a facility,
can be very effective in reducing ground system (plane) impedance. The use of massive ground-
return conductors, grounding sheets, or large area plates are frequently helpful.

  e. In situations where single -point grounding is required at RF frequencies, capacitive
grounding can be used. This is referred to as frequency-selective grounding. The inverse
situation can also be employed where an inductance is used to achieve a dc and low frequency
ground (e.g., for safety) and approximate an open circuit at RF. Parasitic effects can render
capacitive and inductive grounding highly unpredictable and should be used only under unusual
conditions and with a great deal of care to assure that the overall interference problem is not
aggravated.

4-5. Grounding for fault protection

Fault protection is an integral part of ground network design. Frequently, signal grounds are
common with fault protection paths, particularly where structural elements of a building are
involved. Because traditional practices and personnel and structural protection requirements
strongly favor that priority be placed on fault protection needs over EMI needs, it is likely that
signal ground networks must be designed to be compatible with these networks. Occasionally,
requirements of fault protection will force compromises in the signal ground design and
implementation. The following discussion presents an overview of the principles of design
behind fault protection systems.

  a. One primary reason for grounding is to prevent electric shock in the event of a circuit fault.
Electric shock occurs when the human body becomes a part of an electric circuit. It most
commonly occurs when people come in contact with energized devices or circuits while touching
a grounded object or while standing on a damp floor. The effects of an electric current on the
body are principally determined by the magnitude of current and duration of the shock. Current
is determined by the open circuit voltage of the source and total path resistance including internal
source resistance and human body resistance.

       (1) In power circuits, internal source resistance is usually negligible in comparison with
that of the body. In such cases, the voltage level, V, is the important factor in determining if a

4-10


---

                                                                                                                         TM 5-689

shock hazard exists. At commercial frequencies of 50 to 60 hertz and voltages of 120 to 140
volts, the contact resistance of the body primarily determines the current through the body. This
resistance may decrease by as much as a factor of 100 between a completely dry condition and a
wet condition. For estimation purposes, the resistance of the skin is usually somewhere between
500 and 1500 ohms.

       (2) An electric current through the body can produce varying effects including death,
depending upon the magnitude of current. For example, the perception current is the smallest
current that might cause an unexpected involuntary reaction and produce an accident as a
secondary effect. Shock currents greater than the reaction current produce an increasingly severe
muscular reaction. Above a certain level, the shock victim becomes unable to release the
conductor. The maximum current at which a person can still release the conductor by using the
muscles directly stimulated by that current is called the let-go current. Shock currents above the
let-go level can begin to cause check muscles to contract and breathing to stop. If the current is
interrupted quickly enough breathing will resume. At a still higher level, electric shock currents
can cause an effect on the heart called ventricular fibrillation. Under this condition, usually there
is a stoppage of heart action. Various current levels for 60 hertz and dc are summarized in table
4-1. At frequencies above 300 hertz, the current levels required to produce the above effects
begin to increase due to skin effort. For example, the perception current is approximately 100
milliamperes at 70 kilohertz (kHz). Above 100-200 kHz, the sensation of shock changes from
tingling to heat. It is believed that heat or burns are the only effects of shock above these
frequencies.

  b. To protect people from inadvertent exposure to hazardous voltages, all exposed metallic
elements should be connected to ground. In this sense ground usually means other exposed
equipment, metal members of the building, plumbing fixtures, and any other metallic structures
likely to be at a different (hazardous) potential in the event of a fault.

       (1) If accidental contact occurs between energized conductors and chassis, frame, or
cabinet through human error, insulation failure or component failure, a direct low resistance path

                                Table 4-1. Summary of the effects of shock

Alternating Current (60 Hertz)  Direct Current            Effects
            (milliamperes)      (milliamperes)         (milliamperes)
                 0.5-1                           Perception
                 1-3                  0-4        Surprise (reactor current)
                 3-21                  4-15      Reflex action (let-go current)
                21-40                 15-80      Muscular inhibition
                40-100                 80-160    Respiratory block
                Over 100              160-300    Usually fatal
                                       Over 300

                                                 4-11


---

TM 5-689

exists between the fault and the energy source (usually a transformer) which causes fuses to blow
or breakers to trip and thus quickly remove the hazard.

       (2) The dependence of shock effects upon frequency suggests that the relative danger from
electric shock is related to the duration of exposure so that one objective of the fault protection
system (network) is to reduce the time of exposure to a minimum. Another reason for achieving
rapid clearance is to limit temperature rise in the faulted conductor and thus minimize a potentia l
fire hazard.

  c. Fault protection design is normally governed by the NEC and other established industry
standards. The NEC is issued by the NFPA as NFPA 70 and is updated every three years. This
code has been adopted by the American National Standards Institute (ANSI) as ANSI/NFPA 70
and it is rapidly becoming universally accepted. It has become, in effect, a Federal Standard with
its incorporation into the OSHA requirements.

       (1) When viewed from the perspective of EMI and noise control, it should be remembered
that the primary objectives of the NEC are fire and shock hazard protection and not the
achievement of EM compatibility. However, this does not mean that practices of the NEC are
necessarily in opposition to good EMI practices. It does mean that the NEC standards must be
met in any equipment or system design and installation and, therefore, its requirements must be
thoroughly understood while implementing any EMI grounding system. Another thing to realize
is that simply conforming to the NEC does not assure a noise-free system; generally other
measures also must be employed to achieve the desired level of total system (equipment, facility,
and environment) compatibility.

       (2) Article 250 of the NEC sets forth the general grounding requirements for electrical
wiring in a structure. Present requirements of the NEC specify that the ground lead (green wire),
in a single -phase ac power distribution system, must be one of three leads. The other two leads
comprise the hot lead (black wire) and the neutral lead (white wire). The ground lead is a safety
conductor designed to carry current only in the event of a fault. The hot lead is connected to the
high side of the secondary of the distribution transformer. For fault protection, the NEC specifies
that the neutral be grounded at the service disconnecting means (main breaker). The safety
ground (green wire) is grounded at that point as shown in figure 4-6. All exposed metallic
elements of electrical and electronic equipment are connected to this ground with the green wire.

       (3) Grounding of a three-phase wye power distribution system is done similarly to the
single-phase system. The connections for a typical system are shown in figure 4-7. The neutral
lead, as in single -phase systems, is grounded for fault protection at the service disconnecting
means. The NEC specifies that the neutral should never be grounded at any point on the load side
of the service entrance on either single -phase or three-phase systems.

       (4) Figure 4-8 illustrates two correctly wired branch circuits. In the separate branch
circuit, two pieces of equipment are energized from separate branch circuits. Minimum power-
related voltages exist between the equipment cabinets A and B. Thus, potential interference
currents in the interconnecting ground path (provided, for example, by a ground bus, cable shield,
etc.) are small. The common branch circuit in figure 4-8 shows both pieces of equipment sharing
a common-branch circuit, as in the same room, for example.

4-12


---

                                                                             TM 5-689

DISTRIBUTION                           SERVICE
 TRANSFORMER                   DISCONNECTING

                                          MEANS

                                                            115V

                                                                   NEUTRAL        230V
                                                                       LEAD
                                                 115V

                                                                   SAFETY GROUND

NEUTRAL                                          NEUTRAL GROUNDED
GROUNDED                                         AT SERVICE
AT                                               DISCONNECTING
TRANSFORMER                                      MEANS

              Figure 4-6. Single phase 115/230 Vac power ground connections

WYE                            PHASE 1           THREE PHASE 4-WIRE
CONNECTED                      PHASE 2           120/208V SYSTEM
TRANSFORMER                    NEUTRAL
SECONDARY                                                          SERVICE
WINDING                        PHASE 3                             DISCONNECTING
                                                                   MEANS

                    NEUTRAL                                                         EARTH
                  GROUNDED                                                          ELECTRODE
                                                                                    SYSTEM
                           AT
              TRANSFORMER                                          SAFETY GROUND

                                        TO FACILITY WIRING

                     Figure 4-7. Three phase 120/208 Vac power system ground connections

       (5) Figure 4-9 shows the effects of improper wiring.

            (a) The hot neutral reversed condition is that of reversal of the hot (black) and neutral
(white) conductors. Although a violation of the NEC, it does not automatically produce stray or
return currents in the safety wire (or equipment cabinet/conduit system).

                                                                                  4-13


---

TM 5-689

                                                          EQUIPMENT

                                                  OUTLET  A

                                           HOT            EQUIPMENT     LITTLE
                                                                     B  NOISE
                                      NEUTRAL                           CURRENT
                                       SAFETY
                                                          EQUIPMENT
                                           HOT                       A

                                      NEUTRAL
                                       SAFETY
          A) SEPARATE BRANCH CIRCUIT

                                             HOT

                                       NEUTRAL
                                         SAFETY

                                                          EQUIPMENT     LITTLE
                                                                     B  NOISE
                                                                        CURRENT

                                                                                       B) COMMON BRANCH CIRCUIT

                  Figure 4-8. Properly wired ac distribution circuits for minimum ground noise

            (b) The other conditions of figure 4-9 represent the most likely problems and are the
most troublesome from the standpoint of stray noise. Interchange of the neutral and ground
conductors frequently exists because no short circuit is produced and the condition may go
undetected. The full load current of terminating equipment, however, returns through the safety
wire/conduit/cabinet ground system. The resultant common-mode voltages and currents pose a
severe threat to interconnecting circuits between equipment A and B. The condition of neutral
safety interchanged, separate branch circuit is the most troublesome from the standpoint of power
frequency common-mode noise because of the higher voltage drop developed by the return
current traveling through the longer path.

            (c) These conditions are the sources of many facility ground noise problems.
Improperly grounded neutrals can occur in a piece of terminating equipment or can be the result
of improper wiring at an outlet, junction box, or switch panel. (The most common cause is
improper wiring.) If the neutral is grounded at any point except at the service disconnect, part (if
not most) of the load current returns from the load back through conduit, raceways, equipment
cables (including coax and other cable shields), and structural support members. Voltage drops
associated with this return load current appear as common-mode noise sources between

4-14


---

                                                                                   TM 5-689

                                                                     EQUIPMENT

                                                             OUTLET  A

      HOT                                                            EQUIPMENT     LITTLE
NEUTRAL                                                                         B  NOISE
                                                                                   CURRENT
 SAFETY

      HOT

A) HOT-NEUTRAL REVERSED, COMMON OR SEPARATE BRANCH CIRCUITS          EQUIPMENT
                                                                                A
                                                      HOT

                                                NEUTRAL
                                                 SAFETY

                                                                     EQUIPMENT     MUCH
                                                                                B  NOISE
                                                                                   CURRENT

B) NEUTRAL-SAFETY INTERCHANGED, COMMON BRANCH CIRCUIT                EQUIPMENT
                                                                                A
                                              HOT
                                                                     EQUIPMENT     NOISE
                                        NEUTRAL                                 B  CURRENT
                                         SAFETY

                                        V = I Z
                                              HOT

                                        NEUTRAL
                                         SAFETY

C) NEUTRAL-SAFETY INTERCHANGED, SEPARATE BRANCH CIRCUIT

                             Figure 4-9. Noise problems resulting from improper wiring

separately located equipment, as illustrated. If this equipment must be interconnected with signal
paths, appropriate common-mode rejection measures must be employed in the signal paths.

                                                                                   4-15


---

TM 5-689

4-6. ADP grounding

The primary objective of grounding for computers and data processing equipment is to minimize
electronic noise that would adversely affect the output signals of the equipment. The power-
distribution system for computer rooms is usually designed by an electrical consultant and
installed by an electrical contractor to insure maximum reliability. Grounding provisions provide
personnel safety equal to or exceeding the requirements of the NEC. The computers and data-
processing equipment are usually designed and installed by computer manufacturing companies
or their contractors, in cooperation with the user-purchaser. The computer-room installation often
includes a raised floor, with power to computers, peripheral equipment, interconnections,
computer cooling-air distribution, and a fire-extinguishing system all located under the floor.
This is where the usual interfaces are accomplished and where problems frequently occur
between the computer installation and the electrical distribution system powering the computers.
Grounding methods have been developed to minimize noise, sometimes isolating the computer
equipment grounding system from the rest of the building grounding system. However, some of
these methods are violations of the NEC grounding requirements and may be unsafe.

  a. To prevent electrical noise from affecting computers, two entirely different and separate
grounding systems are required.

       (1) First, the power distribution system must be grounded in accordance with NEC
requirements for safety, and in addition the 60 hertz power system grounding must be so designed
that it will minimize noise pickup that can affect the computer operation.

       (2) Second, the computer equipment and enclosures must be connected to a reference
grounding system for high-frequency noise. This high-frequency protection is in no way related
to system grounding. In fact, the high-frequency reference will work whether or not it is
grounded to the system ground. However, since it consists of exposed, metallic noncurrent-
carrying parts that could accidentally become energized, it must be grounded, as required by NEC
Section 250-42.

       (3) Once it is recognized that proper computer grounding requires both a 60 hertz and a
high-frequency grounding system, that electrical safety requires that the two systems be bonded
together, and that each system can be examined separately, then it can be determined how to bond
them so they are compatible.

  b. The grounding of computer equipment is done in accordance with NEC Article 645,
Information Technology Equipment (ITE).

       (1) Computer equipment grounding, like all other electrical equipment grounding, has only
one purpose -–safety. The grounding performs two functions. First, it ties all equipment together
with low-impedance conductors so all equipment is at the same potential. It also bonds that
system to the grounding-electrode system so that the potential is that of the earth. If the
grounding is done in accordance with the NEC, there should not be an unsafe difference in
potential between any two pieces of exposed noncurrent-carrying metal or from any noncurrent-
carrying metal to ground, even under fault conditions. Second, the equipment grounding provides
a safe, low-impedance return path for ground-fault currents to permit overcurrent devices to clear
the fault quickly and thus minimize damage.

4-16


---

                                                                                                                         TM 5-689

       (2) Where the power system supplying the computer has a grounded conductor (which is
usually the case, since most computers utilize a 208Y/120V power supply with a grounded
neutral), that conductor must be grounded in accordance with Article 250. This is frequently a
source of confusion and conflict when the computer is supplied from a separately derived source
such as a dedicated transformer or an uninterruptible power supply (UPS) or motor-generator (M-
G) set. The NEC requirements are intended to ensure a safe installation and are not concerned
with whether or not the system works properly so long as it is safe. It is important to keep this in
mind. It is necessary to conform to the code and at the same time design and install a computer
grounding system that will permit the computers to operate with a minimum of noise problems
and data-handling errors.

       (3) In a mistaken effort to isolate the computer system from the rest of the building power
system, many systems have been grounded to a ground rod or buried ring around the building but
not connected to the building grounding system and grounding electrode. This isolation has often
been achieved by using many makeshift devices to keep the computer equipment insulated from
the metallic parts of the distribution system.

       (4) Power-supply conduits have been insulated from computer cabinets with polyvinyl
chloride (PVC) conduit fittings or even plumbing fittings. Conduit runs have been ended before
reaching the computer cabinet and the conductors run the remaining distance exposed. Green-
insulated grounding conductors have been run separately from the circuit conductors and to a
separate ground point. Ground pins have been cut off plugs and the green wire left floating.
Flexible cords, without grounds, have been used to supply the computer units, and so on.

       (5) All these schemes are unsafe, because there is no low-impedance return path for fault
current and no assurance of equal potential between the equipment and other grounded metal.
They violate many sections and every intent of the NEC. Finally, they often result in more
computer noise than proper grounding would produce, because the multiple ground points can
have differences in potential between them, causing circulating ground currents and false data
inputs or processing.

       (6) Computer grounding must be done in accordance with NEC Article 250 and consist of
computer-equipment grounding and computer power-system grounding. All equipment
grounding essentially requires that exposed noncurrent-carrying metal parts be connected by
equipment grounding conductors to the grounding electrode at the electric service equipment, or
at the power source if power is obtained from a separately derived system. The equipment
grounding conductors must run with or enclose the circuit conductors and may be one or more of
a combination of the types listed in NEC Section 250-91. These include a bare or insulated
conductor, rigid or intermediate metal conduit or electrical metallic tubing, flexible metal conduit
approved for the purpose; the armor of Type AC armored cable; cable trays; and other raceways
specifically approved for grounding. An insulated grounding conductor must have an outer finish
that is green or green with a yellow stripe. The grounding path must be permanent and
continuous, and conductors must be sized and installed in full compliance with the many other
applicable code requirements.

       (7) Computer equipment grounding will comply with the code and will be safe if it meets
these requirements. However, several additional provisions are necessary if the computer
installation is to operate with minimum noise problems from the ground system. If computer
equipment is installed in the same way as most other electrical equipment, the grounding may
create many multiple grounding paths. The grounding conductors are run with the power
conductors from the source to each piece of equipment, but there are also many pieces of

                                                                                                                                4-17


---

TM 5-689

equipment fed from other equipment, and many other metallic interconnections between the
grounded metal enclosures of various units. This can be perfectly safe, and in accordance with
the code for equipment grounding, but the multiple points of grounding can have slight
differences in potential, causing small ground currents to flow, especially under transient
conditions. These ground currents appear as noise to the data -processing equipment and can
cause errors in computation or component failures. This arrangement produces “ground loops” –
multiple paths for the circulation of ground currents.

       (8) By modifying the grounding these ground loops can be eliminated. Each piece of
equipment is fed separately and radially from the source and is grounded (by means of the
metallic raceway, green-wire ground, and any other grounding conductors) to a single computer
ground point (G) at the source or distribution point. This radial grounding eliminates any ground
loops. In addition, each piece of equipment is connected by the shortest possible connection to
the reference grid. While these connections seem to create multiple ground loops, as explained
earlier, all points on this reference grid are at the same potential, not only at the power frequency
of 60 hertz, but also at much higher frequencies, so no currents will circulate. One point on the
reference grid must also be tied to the computer ground point to put it at the same ground
potential as all other equipment.

       (9) A radial installation made as shown to a single ground point can comply in all ways
with the NEC, can be entirely safe, and at the same time can be as free as possible from computer
noise problems originating from the grounding system.

       (10) Another point of confusion in computer grounding is the selection of the proper
grounding electrode to which the computer grounding system must be connected. A frequent
error of computer manufacturers is to request a grounding electrode separate from and not
connected to the power system electrode – a separate ground rod or ground ring. This is not only
unsafe and a code violation; because of differing ground potentials, it can also be a source of,
rather than a cure for, computer noise problems.

            (a) The proper grounding electrode is clearly spelled out in Article 250 of the code.
Where the building service is the source of supply, the grounding electrode must be one or more
of those types listed in Section 250-81, to which the grounded circuit conductor (neutral) must
also be connected. There is little confusion on this point. However, large computer installations
are frequently supplied from a separately derived system rather than direct from the building
service. This is done to isolate the computer supply from the other building power systems, and
often to condition the computer power to make it more reliable and compatible with computer
requirements.

            (b) The separately derived system may be a transformer, a computer power center, a
M-G set, a synthesizer, or a UPS inverter. In all such cases, the required grounding electrode
must be as near as possible to the source of power, the separately derived system (Section 250-
26). The grounded conductor, or neutral, of the separately derived system and all equipment
grounding conductors must be connected to this grounding electrode, not the one at the building
service. A connection may also be made back to the service grounding electrode through the
metallic raceway system; but this is neither required by code nor necessary for safety. The reason
for this is that any fault currents that flow in the separately derived system must have a low-
impedance path back to their source - the separate system source, not the building service.

            (c) For separately derived systems, the preferred grounding electrode is the nearest
effectively grounded metal structural building steel, or the nearest effectively grounded metal

4-18


---

                                                                                                                         TM 5-689

water pipe. If neither of these is available, other electrodes as listed in Section 250-81 or 250-83
may be used. We have seen installations with grounding connections run several hundred feet
back to the service ground from a computer transformer secondary, when the connection could
have been and should have been made to the steel building column only a few feet away.

            (d) Ground the computer equipment radially to a single ground point, tie it to a high-
frequency reference grid, and ground this grid to the same computer ground point. Ground the
computer ground point to the proper grounding electrode, and a computer grounding system that
is electrically safe and meets all code requirements, will be essentially free of ground-caused
computer noise and problems.

  c. Computers input, process, and output data at tremendous rates which are constantly
increasing. Typical computer clocks that control the data transfer into, within, and out of the
computer operate at very high frequencies [upwards of 1 gigahertz (GHz)]. These are radio
frequencies, and computers are sensitive to these frequencies. The wiring can act as a receiving
antenna and can respond to external RF signals that may cause false data to be processed by the
computer. The RF signals that can radiate from or get into computers are known as EMI.

       (1) Computer microprocessors operate at very low voltages – usually 5 to 12 volts.
Therefore, it is critical that unintentional voltage differences between various units of data-
processing equipment in a computer room be extremely small. At 60 hertz this is relatively
simple – just tie them together with a low resistance, low-impedance grounding conductor so the
enclosures and grounded metal are all at the same (ground) reference potential.

       (2) At radio frequencies the solution is not so simple. Low-impedance grounds are not
easy to obtain, since the inductive reactance of a conductor is proportional to the frequency. At
30 megahertz (MHz), a length of conductor has an inductive reactance 500,000 times the
reactance at 60 hertz. In addition, there is stray inductance and capacitance from conductor to
conductor or conductor to grounded metal and resonance effects at high frequencies, making it
very difficult to get a conductor of any appreciable length to have the same voltage at both its
ends. If there is a difference in potential between the ends of a grounding conductor connecting
two pieces of data processing equipment, it is possible for data errors to occur.

       (3) A high-frequency impulse applied to a conductor travels along the conductor at a finite
speed, about 85 percent of the speed of light, until it reaches the end of the conductor. It is
reflected back along the conductor, becoming a traveling wave. At some frequencies, the
reflected waves meet and reinforce oncoming new waves, creating resonances and standing
waves. At or near these resonant frequencies the conductor appears to have an extremely high
impedance and does not provide an effective voltage equalizing means between two pieces of
equipment. In addition, the conductor can act as an antenna at or near these resonant frequencies,
radiating energy that can interfere with other equipment or receiving stray signals from other
sources and presenting a false voltage signal to the computer equipment.

       (4) These effects are completely unpredictable because the interfering signals are not
steady and because data processing equipment sensitivity varies. Digital computers on binary
signals, on or off, or 0 to 1. The circuits are most sensitive at the moment they are switching
from one state to the other, and if an impulse occurs at that moment, a false “bit” of data may
occur in the system. At other times, the same impulse may not affect the processing. These
errors can be extremely difficult to identify.

                                                                                                                                4-19


---

TM 5-689

       (5) This points out the need to interconnect all cabinets of the system in such a way that
they are at the same potential for all frequencies, from 60 hertz or less to very high radio
frequencies. One of the best ways of accomplishing this is the signal reference grid.
Transmission-line testing has shown that standing waves will not cause a significant voltage
difference between the two ends of a conductor that is not longer than about 1/10 to 1/20 of a
wavelength. The wavelength at 10 MHz is about 100 feet and 1/20 wavelength is 5 feet. The
wavelength at 30 MHz is about 32 feet and 1/20 wavelength is a little under 2 feet.

                                                      λ = c/ƒ
                                       where λ = wavelength (meters)
                        c = velocity of light in free space = 3 x 108 meters/second
                                   ƒ = frequency in hertz (cycles/second)

       (6) If conductors are connected in a mesh or grid to form a multitude of low-impedance
loops in parallel, there will be little voltage difference between any two points in the grid at all
frequencies from 60 hertz up to a frequency where the length of one side of one square represents
about 1/10 wavelength. A grid made up of 2 foot squares will at any point provide an effective
equipotential ground reference point for signals up to more than 30 MHz. If such a grid is
installed in the computer room and the enclosure or frame of each piece of data -processing
equipment is connected to it by a short conductor, there should be no computer noise problems
resulting from differences in ground potential between the frames of any two pieces of
equipment.

       (7) A raised floor in the computer room can be used as the reference grid if of the proper
type and design. Most raised floors consist of vertical stanchions or corner supports 2 feet apart
that hold up the 2-foot square floor tiles. If the floor is the type that has stringers between the
stanchions and the stringers are positively mechanically bolted to them to make a good electrical
connection, the stringers will form an excellent 2-foot square mesh. If the floor tiles or panels are
metal-clad, they will further reduce the impedance between loops. This is probably the best and
least-costly way to obtain the high-frequency reference ground grid. Floor tiles should be used
that do not have a zinc electroplated-passivation coating on the tile’s sheet metal pan, thereby
avoiding potential problems with zinc whiskers. Computer room floor tile manufacturers have
identified this problem, and no zinc electroplated floor tiles have been manufactured for several
years.

       (8) The frames of the data-processing equipment should be connected to the grid by the
shortest possible leads with braided copper the preferred material, followed by copper strap, with
round conductor least desirable, because braid provides the most effective and round conductor
the least-effective results with high-frequency signals. Connections from the equipment frames
to the raised-floor grid can easily be kept to 8 inches.

       (9) If the bolted-stringer type of floor is not installed, a grid can be created by laying a
mesh on the true floor, under the raised floor. This mesh also can be of copper wire, (least
desirable) flat copper strap, or braided copper strap (most desirable), electrically connected every
2 feet to make a grid of 2-foot squares. Since this grid is on the true floor, it is about 2 feet
farther from the equipment enclosures and requires a longer connecting strap from enclosure to
grid, reducing its effectiveness a little.

       (10) Additional protection against false signals is obtained by using shielded cables to
interconnect equipment or using filters and traps to keep unwanted signals out of the system. If
shielded cables are used, only one end of the shielding may be grounded. Grounding both ends of

4-20


---

                                                                                                                         TM 5-689

the shield would provide a closed current loop that could create an induced current in the shield
and damage the shield through overheating.

       (11) A higher frequency network reference signal subsystem may be required for
frequencies of concern higher than 30 MHz. The optimum interconnecting cable and/or mesh
spacing of the equipotential plane should be one-tenth to one-twentie th of the wavelength of
concern. For a 500 MHz signal, one-tenth of a wavelength is about 1.2 inches. This small mesh
spacing may not be feasible ; therefore, the mesh spacing should be as small as practical. As a
design objective, the mesh grid openings should be no larger than 4 inches. A ground reference
plane made up of a copper mesh with four-inch openings may be embedded in the concrete floor
of new facilities. Another option for existing or new facilities is to install a metal sheet or roll of
aluminum, copper, or phosphor bronze under floor tiles or carpet. When it is impractical to
install an equipotential plane under the floor surrounding the ADP equipment, thin metal sheets
can be installed in or on the ceiling of the equipment room. Additional details can be found in
MIL-HDBK-419A, Section 1.5.1, Higher Frequency Network.

                                                                                                                                4-21


---

                                                                                                                 TM 5-689

                                                    CHAPTER 5
                                                   HARMONICS

5-1. Harmonics defined

Harmonic is defined as a sinusoidal component of a periodic wave having a frequency that is an integral

multiple of the fundamental frequency. For example, a component, the frequency of which is five times

the  fundamental  frequency,  is  called  a    th  harmonic.  The theoretical maximum amplitude of each

                                             5

harmonic current produced by a converter is equal to that of the fundamental component divided by

harmonic order.   For  example,   the    th  harmonic  is  equal  to  20  percent  of  the  load  current;  and  the    th

                                       5                                                                              7

harmonic is equal to 14.3 percent; and so on. These values are for an idealized squarewave and, in

practice, will be less because of system impedance. The harmonic components are assumed to be in

phase with the fundamental. The resulting waveshape will depend on the magnitude and the phase

relation of each of the harmonic components.

  a. Harmonic distortion factor (HDF) standards are needed to ensure that users are provided with a
suitable voltage supply wave form; limit distortions to levels that system components can tolerate; and
prevent the power system from interfering with the operation of other systems. In order to compare levels
of harmonic distortion in a power system, the HDF is used, and is defined in the Institute of Electrical and
Electronic Engineers (IEEE) Standard 519-1992 as:

HDF = (sum of squares of amplitudes of all harmonics) ½
         ( square of amplitude of fundamental ) x 100%

  b. The amount of voltage distortion that can be tolerated on a power system is dependent upon the
equipment connected to it and this equipment’s susceptibility to nonsinusoidal waveshapes. Power utility
companies may be more stringent or relaxed in their specifications for the HDF, and may use different
formulas than those given in IEEE Standards. In Canada, for example, the requirements for HDF vary
from utility to utility, but in general they range from 1 to 5 percent depending on the system voltage level.
The higher the voltage level, the more stringent the harmonic limitations requirements. It is, therefore,
necessary to check with the power company as to their requirements in limiting harmonic voltages and
currents as this may have substantial impact on the drive and filter design. IEEE Standard 519-1992
specifies guidelines with regard to limiting the harmonic voltage and current distortion factor. A
summary of these guidelines is given in table 5-1.

5-2. Harmonic sources

The common sources of harmonics in utility or industrial electrical systems are: rectifiers, dc motor
drives, adjustable frequency ac drives, uninterruptible power supplies (UPS), arc furnaces, static volt
amperes reactive (VAR) generators, cyclo converters, and static motor starters.

a. A static power converter generates harmonic currents the order of which is given by:

     n = kp ±1

where: n = order of the harmonic
         k = an integer 1, 2, 3 . . .
         p = number of pulses of the converter system

                                                                                                                            5-1


---

TM 5-689

               Table 5-1. Voltage distortion limits for medium and high voltage power systems

Power System                         Dedicated System                                      General Power
Voltage Level                            Converter*                                             System

Medium Voltage                                  8%                                         5%

2.4 – 69 kV

High Voltage                                    1.5%                                       1.5%
115 kV and Above

*A dedicated system is one servicing only converters or loads not affected by voltage distortion.

                                                                                                                                        th th th th th th rd th

A 6-pulse converter would generate harmonic currents of the order 5 , 7 , 11 , 13 , 17 , 19 , 23 , 25 ,
etc. For a 12-pulse converter configuration, the harmonics generated are 11th, 13th, 23rd, 25th, etc.

Therefore, a 12-pulse converter system provides a significant reduction in the voltage distortion and,

equally  important,  it  eliminates  (assuming  balanced  conditions)  the  lowest  order  harmonics  of    th  and    th

                                                                                                          5          7

that are typical of most concern.

  b. The presence of these harmonic producing devices in a system does not necessarily constitute a
problem. The harmonics may be of sufficiently low magnitude and, therefore, harmless at one extreme,
or they may be a magnitude high enough to cause damage to equipment in the system. If in an existing
system there is no history of harmonic related problems such as motor failures, telephone interference,
etc., then there is likely to be no harmonic problem, and a harmonic analysis study is probably not
warranted. However, a good guideline is that if 20 percent or more of the plant load consists of harmonic
producing sources, a harmonic study should be considered. This will determine the magnitude of
harmonic currents and voltages, and will aid in designing special filters to reduce these distortions.

  c. In addition there are other non-linear devices such as arc discharge devices used in arc furnaces and
fluorescent lamps. Power supplies for electronic equipment such as UPS, numerical controlled machine
and computers, and any load that requires other than a sinusoidal current will be a source of harmonic
currents.

5-3. Harmonic technical history

From approximately 1910 to the 1960s, the main non-linear loads came from those few larger users in the
electro-chemical and electro-metallurgical industries. They developed means of limiting the harmonic
currents that their processes developed and thus minimized the effect on power systems and other users.

  a. Small and medium sized adjustable speed drives used motor-generator (M-G) sets to feed dc
motors and a few adjustable speed ac drives used wound rotor motors. Still other variable speed drives
were steam driven. For the M-G sets, the mechanical linkage between the two systems transmitted power
between them and at the same time electrically isolated each system from the other. However, these M-G
sets were bulky and tended to be high maintenance pieces of equipment.

  b. The first attempt at electrical rectification was accomplished through mechanical means. A motor
driven cam physically opened and closed switches at precisely the right instant on the voltage wave form

5-2


---

                                                                                                                                    TM 5-689

to supply dc voltage and current to load. At best, this approach was cumbersome since timing the
switches and keeping them timed was extremely difficult. In addition, contact arcing plus mechanical
wear also made this equipment a high maintenance item. Mechanical rectifiers were soon replaced by
static equipment including mercury, selenium, and silicon diodes, thyristors and finally insulated gate
bipolar transistors (IGBTs). With the invention and development of the thyristor, cost effective
equipment became available to allow standard squirrel cage induction motors to drive pumps, fans, and
machines with the ability to control the speed of these drives. The technology grew rapidly and the
applications of these drives covered all aspects of process drives in all industries. These non-linear type
loads increased dramatically in just the decade of the 1970s. This growth has continued and will
continue.

  c. Although solid-state rectification appeared to be the panacea to the problems of the older methods,
other system problems soon became noticeable , especially as the total converter load became a substantial
section of the total system power requirements.

       (1) The most noticeable initial problem was the inherent poor power factor associated with static
power converters. Economics (utility demand billing) as well as system voltage regulation requirements
made it desirable to improve the overall system power factor which normally was accomplished using
shunt power factor correction capacitors. However, when these capacitor banks were applied, other
problems involving harmonic voltages and currents affecting these capacitors and other related equipment
became prevalent.

       (2) Another initial problem was the excessive amount of interference induced into telephone
circuits due to mutual coupling between the electrical system and the communication system at these
harmonic frequencies.

       (3) More recent problems involve the performance of computers, numerical controlled machines,
and other sophisticated electronic equipment which are very sensitive to power line pollution. These
devices can respond incorrectly to normal inputs, give false signals, or possibly not respond at all. More
recently, neutrals of four-wire systems (480/277V; 120/208V) have been the latest power system element
being affected by harmonics.

5-4. Resonance

The application of capacitors in a harmonic environment necessitates the consideration of the potential
problem of an excited harmonic resonance condition. Inductive reactance increases directly with
frequency and capacitive reactance decreases directly with frequency. At the resonant frequency of any
inductive-capacitive (L-C) circuit, the inductive reactance equals the capacitive reactance.

  a. Two forms of resonance which must be considered: series resonance and parallel resonance.

       (1) For the series circuit , the total impedance at the resonant frequency reduces to the resistance
component only. For the case where this component is small, high current magnitudes at the exciting
frequency will flow. From a practical viewpoint, series resonance conditions are source limited. As long
as the harmonic source is not excessively large compared to the power factor capacitor bank, the
harmonic current is typically within limits.

       (2) Parallel resonance is similar to series resonance where the capacitance reactance equals the
inductive reactance. However, the parallel impedance is significantly different. At the resonant
frequency the impedance is very high and when excited from a source at this frequency, a high circulating
current will flow in the capacitance-inductance loop – although the source current is small in comparison.

                                                                                                                                             5-3


---

TM 5-689

The most common situation, which leads to parallel resonance in industry, is where the source inductance
resonates with the power factor capacitor bank at a frequency excited by the facilities’ harmonic sources.
In this situation, the harmonics are amplifie d by the resonant condition and are not source limited.

  b. In actual electrical systems utilizing power factor correction capacitors, either type of resonance or
a combination of both may occur if the resonant point happens to be close to one of the frequencies
generated by harmonic sources in the system. The result may be the flow of excessive amounts of
harmonic current and/or the appearance of excessive harmonic overvoltages. Possible consequences of
such an occurrence are excessive capacitor fuse operation, capacitor failures, unexplained protective relay
tripping, telephone interference, or overheating of other electrical equipment.

5-5. Electrical loads

  a. Until recently, almost all loads were linear, and those that were not were a small portion of the total
as to have little effect on system design and operation. Then came the electronic revolution and electronic
loads, such as computers, UPS equipment, and variable speed motor drives, have proliferated. These
electronic loads are mostly non-linear, and have become a large enough factor to have serious
consequences in distribution systems. Overheated neutral conductors, failed transformers, malfunctioning
generators, and motor burnouts have been experienced, even though loads were apparently well within
equipment ratings. Motor, incandescent lighting, and heating loads are linear in nature. That is, the load
impedance is essentially constant regardless of the applied voltage. For ac, the current increases
proportionately as the voltage increases and decreases proportionately as the voltage decreases. This
current is in phase with the voltage for a resistive circuit with a power factor of unity. It lags the voltage
by some phase angle for the more typical partially inductive circuit with a power factor commonly
between 0.80 and 0.95, and leads the voltage by some phase angle for the occasional capacitative circuit,
but is always proportional to the voltage. For a sinusoidal voltage, the current is also sinusoidal and at the
same frequency.

  b. A non-linear load is one in which the load current is not proportional to the voltage. Often, the load
current is not continuous. It can be switched on for only part of the cycle, as in a thyristor-controlled
circuit; or pulsed, as in a controlled rectifier circuit, a computer, or power to a UPS.

       (1) Non-linear loads can often create considerable harmonic distortion on the system. Harmonic
currents cause excessive heating in magnetic steel cores of transformers and motors. Odd-order
harmonics are additive in the neutral conductors of the system, and some of the pulsed currents do not
cancel out in the neutral, even when the three phases of the system are carefully balanced. The result is
overloaded neutral conductors. Also, many of these non-linear loads have a low power factor, increasing
the cost of utility power where power factor penalty clauses apply.

       (2) Non-linear load currents are nonsinusoidal and even when the source voltage is a clean
sinewave, the non-linear loads can distort that voltage wave, making it nonsinusoidal. It is essential that
special characteristics of non-linear loads are understood so that failures on critical systems are avoided.

       (3) In rectifiers for dc loads and dc motor speed controls, the incoming ac is rectified and in many
cases filtered to remove the ripple voltage.

       (4) In ac speed controls, the incoming ac is rectified to dc, which is then inverted by pulsing
circuits back to adjustable -frequency ac. The same steps are used in UPS systems to obtain constant-
frequency 60 or 415 hertz ac power.

5-4


---

                                                                                                                                    TM 5-689

       (5) In power supplies for computers, office machines, programmable controllers, and similar
electronic equipment, the ac is converted to low-voltage dc, with high-speed switching circuits for
controlling the voltage. The dc is used directly by the microprocessors or central processing unit (CPU).

       (6) In the past, most motor-driven computer peripherals, such as tape drives and cooling fans, had
ac motors. However, in the latest equipment these peripherals use dc motors, increasing the dc load of the
computer system.

       (7) Conventional rectifier-type power supplies consist of a transformer to raise or lower the
voltage, a rectifier, and filtering to remove the voltage variations or ripple from the dc output. Where
voltage change is not necessary, the transformer may be eliminated. Voltage control can be obtained by
replacing the diodes in the rectifier with thyristors [silicon-controlled rectifiers (SCRs)]. These are gated
on (conducting) at any point in the cycle, turn off automatically as the current passes through zero, and
are gated on again at the same point in each subsequent half-cycle.

       (8) Rectifiers use three-phase power for a 6-pulse circuit , or use transformers to increase the
number of phases to create a 12- or 24- pulse circuit. The greater the number of pulses, the less filtering
is needed to provide a smooth, ripple -free dc output. There are many variations of these basic rectifier
circuits.

       (9) A characteristic of all rectifier circuits is that they are non-linear and draw currents of high
harmonic content from the source. Diode full-wave rectifiers are least non-linear, conducting as soon as
the forward voltage overcomes the small (about 0.7 V) forward bias required. Phase-controlled rectifiers
using thyristors do not begin to conduct until gated on and are, therefore, more non-linear.

       (10) The standard power supply, with a transformer and an iron-core choke in the filter, is large,
heavy, inefficient, and costly. Manufacturers of computers and other microprocessor-based electronic
equipment have almost completely changed over to the switching-mode type of power supply, which
eliminates the heavy iron-core input transformer and filter choke.

       (11) The switcher controls the voltage, switching at a frequency of from 20 to 100 kilohertz (kHz).
A newer switcher operates in the megahertz (MHz) range. A transformer on the switcher output provides
some voltage control and isolation of the load from the source. The high switching frequency means that
the transformer can be small and light. It requires only a ferrite core instead of a steel core. Voltage
sensors and control circuits vary the switcher duty cycle (on time) to produce the required output voltage
under varying load conditions.

       (12) Switching mode power supplies (SMSP) are highly non-linear and a major source of harmonic
distortion and noise. The high-frequency harmonics extend into the radio-frequency (RF) range,
requiring most manufacturers to include filters in the incoming line to meet FCC requirements on limiting
conducted and radiated interference. Modern computers, from the individual PC to the largest
mainframe, and most other microprocessor-based electronic equipment use SMPS and are a major source
of non-linear load problems.

5-6. Neutral currents

Multiples of the 3rd harmonic current are additive in the common neutral of a three-phase system, but the
mechanism that causes this is little understood.

  a. In a three-phase, four-wire system, single -phase line-to-neutral load currents flow in each phase
conductor and return in the common neutral conductor. The three 60 hertz phase currents are separated

                                                                                                                                             5-5


---

TM 5-689

by 120°; and for balanced three-phase loads, they are equal. When they return in the neutral, they cancel
each other out, adding up to zero at all points. Therefore, for balanced three-phase, 60 hertz loads, neutral
current is zero.

b.   For    nd  harmonic      currents    separated       by  120°,  cancellation  in   the   neutral  would   also   be  complete

          2

with zero neutral current. This is true in the same way for all even harmonics.

c.   For    rd  harmonic      currents,   the  return     currents   from  each  of  the  three  phases  are   in  phase     in  the

          3

neutral  and  so  the  total    rd  harmonic   neutral    current    is  the  arithmetic  sum  of  the  three  individual      rd

                              3                                                                                              3

harmonic phase currents.            This  is  also  true  for  odd  multiples  of  the    rd  harmonic     th  15th,  21st,  etc.).

                                                                                        3               (9 ,

  d. The theoretical neutral current with harmonics is at least 1.73 and perhaps as much as 3.0 times the
phase current. For pulsed loads, the pulses can occur in each phase at a different time. They will return
in the common neutral, but they will be separated by time; therefore, there will be no cancellation. If
none of the pulses overlap, the neutral current can be three times the phase current.

  e. The effects of additive harmonics in the neutral were first recognized in the National Electrical
Code (NEC) many years ago, when Section 220-22 prohibited reduced neutral conductor size for that
portion of the load consisting of discharge lighting. The effects of electronic equipment were recognized
in the 1987 NEC when the prohibition in Section 220-22 against reducing the neutral was expanded to
include non-linear loads.

  f. There are several solutions to minimize this problem. Not only must neutral conductor sizes not be
reduced for these loads, but they must often be increased. Many engineers are designing with neutral
conductors sized for at least 150 percent of the true root mean square (RMS) phase current, including the
harmonic content.

  g. The harmonic content of the loads may be reduced by means of line filters. Since the
manufacturers of the electronic equipment seldom install line filters beyond the minimum necessary to
meet FCC requirements, the power-line filters must usually be separate units installed between the source
and the loads.

  h. For large computers, UPS, or other non-linear loads, the final isolation transformer should be
located as close as possible to the load. The neutral conductors from the wye secondary must be
oversized as noted, but the conductor lengths would be relatively short. Nothing upstream from the
transformer will be affected. However, the transformer may have to be derated.

5-7. Derating power equipment

The ratings of transformers and generators are based on the heating created by load currents of an
undistorted 60 hertz sinewave. When the load currents are non-linear and have a substantial harmonic
content, they cause considerably more heating than the same number of amperes of pure sinewave. There
are two major reasons for this.

  a. When steel is magnetized, the minute particles known as magnetic domains reverse direction as the
current alternates, and the magnetic polarity also reverses. The magnetizing of the steel is not 100 percent
efficient, since energy is required to overcome the friction of the magnetic domains. This creates
hysteresis losses which are greater for a given RMS current at the higher-frequency harmonics, where the
magnetic reversals are more rapid than at the fundamental 60 hertz.

5-6


---

                                                                                                                                    TM 5-689

  b. Also, alternating magnetic fields induce currents into the steel laminations when the changing
magnetic flux cuts through a conductor. These “eddy currents” flow through the resistance of the steel,
generating eddy-current heating losses. Because of the higher frequencies, eddy-current losses are
considerably greater for harmonic currents than they are for the same RMS value of 60 hertz current. A
lesser, but still considerable, heating effect at higher frequencies is caused by the “skin effect” in the
conductors. Currents at higher frequencies are not distributed evenly through the cross-section of the
conductor. The magnetic fields tend to force the current flow toward the outside or skin of the conductor.
This effect increases as the frequency increases, and also as the magnitude of current increases. At higher
frequencies, the center of the conductor carries little or no current. Therefore, the effective cross-section
of the conductor is decreased, and its resistance is increased. It behaves as a smaller conductor of lower
capacity. As a result, a given current at harmonic frequencies causes more conductor heating than the
same current at 60 hertz.

  c. The result of hysteresis, eddy current, and skin effect is that the transformer or generator carrying
no more than its full-rated RMS current, but supplying non-linear loads with a high harmonic content,
will overheat, sometimes to the point of failure. Transformers and generators loaded to less than 70
percent of their rating have been shut down because of over-temperature. Rectifier transformers
specifically designed for non-linear industrial rectifier loads have been manufactured to reduce these
effects. At this time, transformers specially designed for other electronic loads are not available, and
standard transformers must be derated.

  d. As the harmonic currents are drawn by the loads, they act on the impedance of the source, causing
harmonic distortion of the source voltage. Motors are normally linear loads, but when the supply voltage
has harmonic distortion, the motors draw harmonic currents. These harmonic currents cause excessive
motor heating from higher hysteresis and eddy-current losses in the motor laminations and skin effect in
the windings. Thus, motors supplied from sources with voltage distorted by other non-linear loads will
also overheat unless they are derated.

  e. The solutions to overheating of transformers, generators, and motors as a result of non-linear loads
are the same as those for neutral overheating. The equipment must be derated or the harmonic content
must be reduced by line filters, or both. There are no standards for the required derating, although
considerable research is being done to determine these requirements. Derating can be done by
observation, based on the temperature rises of the affected equipment. In initial design, equipment must
be oversized by an amount determined by judgement and experience to permit the necessary derating.

5-8. Generator control problems

  a. Harmonic currents can cause serious problems for generator installations in addition to excessive
heating. Modern generators use electronic means to regulate the output voltage of the generator, to
control the speed of the engine or prime mover (thus the output frequency of the generator), to parallel
generators, and to share the load proportionately among the paralleled units.

  b. Many of these control devices use circuits that measure the zero crossing point of the voltage or
current wave. At 60 hertz this is acceptable; but with a high harmonic content, there may be many more
zero crossings than the normal ones for 60 hertz. This can cause hunting and instability in speed and
frequency control, and can make the paralleling of generators difficult or impossible.

  c. Load sharing depends on measurement of the load on each unit. The RMS value of the current is
simple to determine for a pure 60 hertz sinewave, but using controls based on 60 hertz RMS where
harmonics are present will give false readings, sometimes too high and at other times too low. Only more
complex true RMS measurements will provide proper operation.

                                                                                                                                             5-7


---

TM 5-689

  d. Therefore, it is urgent that the generator and control manufacturers are informed of the load
characteristics if a generator is to be used alone or in parallel with non-linear loads. If this is not done, the
installation may not perform properly and it may be costly to obtain correct operation.

5-9. UPS output harmonic distortion

UPSs are used to supply clean power to computers under all conditions, including total utility power
failure. They range from large systems of thousands of kVA for major computer installations to small
units of a few hundred VA for PCs. If the loads distort the power supplied by the UPS, then the power
fed to the loads will not be truly “clean.”

  a. When harmonic currents are drawn by the load, they cause voltage distortion of the source. Since
the voltage drop across the source for a given current is proportional to the impedance of the source (E = I
x Z), the distortion caused by a given harmonic current is lower for a low-impedance source and higher
for a high-impedance source.

  b. The total harmonic distortion (THD) of the UPS for a given load depends on the UPS design and
output impedance. This is true whether the UPS is the static type or the rotary M-G type. Most UPS
manufacturers specify the output distortion of their equipment; <5 percent total harmonic distortion (as a
percentage of the fundamental) is typical. However, many manufacturers add a disclaimer, such as
“based on linear loads” or “for reactive and inductive loads.” Such a disclaimer means that the THD
figure only applies under linear load conditions. Before purchasing any UPS, make certain that it is
capable of supplying the actual types of non-linear loads to be connected to it. Discuss the prospective
loads with the manufacturer because correcting problems may be costly.

  c. UPS equipment utilizing IGBT rectifier technology, working at a 6 kHz frequency avoids harmonic
contamination of the source. Input current wave forms have been measured at less than 3 percent THD at
100 percent load and a maximum of 5 percent at 50 percent load. These low levels of harmonics are
achieved without the use of any passive harmonic resonant filtering. The input power factor of IGBT
rectifiers is 0.98 lagging, so there is no need for power factor correcting capacitors.

5-10. AC system response to harmonics

  a. An ac system’s response to harmonic currents can be very complex. If only one steady-state
sinusoidal voltage or current were applied, ohm’s law (E = IZ) could be applied. The results of Fourier
analysis of complex current wave forms indicate that such a simple relationship is not enough to describe
the networks involved. Any number of inputs can be imposed upon a network so a more complete
analytical tool is needed. Such a tool is that of complex functions.

       (1) Using the complex function H(s), with s as the complex frequency, its value (real or complex
numbers) can indicate constants, linear changes, exponentials, sinusoids or any frequency, or any
conceivable input in any combination. If a network with only one pair of input terminals is present, the
response is H(s) = E(s)/I(s) = Z(s), the input impedance. Likewise, H(s) = I(s)/E(s) = Y(s), which is the
input admittance.

       (2) In both cases, the network function H(s) relates the voltage and current (complex or real
quantities) at the same pair of terminals. It is also called a driving-point or input function. The units of
the driving-point function may be either ohms or mhos.

5-8


---

                                                                             TM 5-689

  b. The forced response and the form of the free response or transient behavior can be found from the
appropriate driving-point function. For a current input, the nature of the free response, which is the only
response when the input is opened, is determined by the poles of Z(s). For a voltage source, the free
response, which is the only response when the source is shorted out depends upon the poles of Y(s).

       (1) Poles are not the only points of importance. Another phenomenon called a zero is also of
interest. To understand exactly what the poles and zeros mean, we must first realize that all circuits and
networks contain capacitors (C), inductors (L), and resistors (R); either placed there intentionally or
simply there as a consequence of distributed parameters. The R, L, and C components combine in various
ways to form factors of H(s). Suppose that H(s) = Z(s) for a particular R-L-C network. If Z(s) has poles
at particular points of s, it means that the impedance of the network is infinite or at least extremely high
for most practical circuits. This means if any current at all can be forced into the network, its voltage
response will tend toward infinity. On the other hand, if H(s) has zeros at some points of s, this means
that the impedance of the network has gone to zero ohms at those points. Hence, H(s) looks like a short
circuit. Consequently, extremely high or infinite current can be injected; but the network will produce no
voltage response. This phenomenon also has both useful and detrimental effects.

       (2) The impedance of the network will not stay constant for all frequencies. Small harmonic
currents entering the network may coincide with high impedances at that harmonic frequency; giving rise
to abnormally high harmonic voltages. Other inputs may encounter zeros which give rise to uncontrolled
currents. In practical circuits, components may be damaged by unwanted high voltages or currents. Less
drastic, though equally undesirable, the original forcing voltage may end up badly distorted by the
network’s response to input currents contributed by harmonics.

  c. A simple R-L-C circuit is shown in figure 5-1. The poles and zeros of the network are important;
so the network function must be expressed in a form that permits their mathematical evaluations. To do
this, the quantities 1/sL, sC, and 1/R become the expressions for the circuit conductances. These are
manipulated, following the rules of basic algebra, to obtain the following function.

                          (1/L) s
H(s) = Y(s) = s2 + (R/L) s + 1/(LC)

       (1) Evaluation of the poles and zeros must be performed. The zero is straightforward. H(s) =
E(s)/I(s) is zero when the numerator of H(s) is zero. Since s is the only term, H(s) is zero when s = 0 and
is the representation of a constant dc source.

       (2) The capacitor will act as an open circuit to a constant dc voltage; therefore, the circuit has zero
current response to pure constant dc.

       (3) To find the poles, the roots of the second order polynomial in s must be extracted. By utilizing
the standard quadratic form, the roots, which are the poles P1 and P2, are found by the formula

                           2   2 1/2
P1, P2 = -X ± (X – ω )

Some algebraic manipulation shows:

X = R/2L, ω0 = 1/ (LC)1/2

Finally:

ωd  =      2  –     2 1/2  so  the  exact  pole  locations  are:  -X ± jωd.

       (ω        X)

                                                                             5-9


---

TM 5-689                                            L  R

                                         E SIN(wt)                                                 C
                                          VOLTS        I (t) AMPS

                                                     Figure 5-1. Series RLC circuit

The location of the poles and zeros is plotted on the complex frequency or s plane as shown in figure 5-2.

       (4) The extreme resolving power of H(s) can be visualized in figure 5-3. H(s) describes a complex
surface consisting of peaks, which are the poles and depressions, which are the zeros. The value of –X,
which is represented on the –b axis, describes how the circuit responds to transient inputs. If the capacitor
and the inductor remain constant and the resistor value varies, several things can happen. If R is infinite,
then –X is infinite and all responses of the circuit are damped to zero. If R is very large compared to L
and C, the circuit will be overdamped or heavily damped. When X is small, meaning R is small, the
circuit becomes underdamped.

       (5) Finally, if all resistance could be removed from the circuit (R = 0-ohms), the poles would move
to the jω-axis. In this theoretical case, the circuit would become an oscillator whose frequency would be
ωo. The oscillation would start as soon as any energy was introduced. In practice there is always some
resistance in the circuit so the circuit response would eventually die out.

       (6) The damping factor describes how the energy in the circuit is redistributed or dissipated when
the input is changed or removed. This distribution and/or dissipation of energy has to occur because the
inductors and capacitors act as energy storage devices. Consequently, the network’s response cannot stop
when the input is removed if energy has been stored in the network.

            (a) From figure 5-3, the cutaway view made along the +jw axis shows the network response to
the steady-state source. That is b = 0, so s = ±jω only. Figure 5-4 shows the magnitude of H(jω) for any
positive frequency, ω. This is the same curve traced out by the right-hand edge of the complex surface in
figure 5-3. Finally, figure 5-6 shows the impedance Z(jω) which is the inverse of figure 5-4.

5-10


---

                              TM 5-689

                     +jω

-X + jωo = P1
               x

(-σ = -X)            Z
 -b
                  0       +b

                                                       x
                                       -X - jωo = P2

                                                                               -jω

                                       Figure 5-2. Poles and zeros on the s-plane

            (b) The most important point for either Y(jω) or Z (jω) occurs at the resonant-frequency, ωo.
Here, the effects of the inductor and capacitor exactly cancel each other; leaving only the conductance
1/R or the resistance R, respectively. Only at this point is the power factor unity, figure 5-5. For
frequencies lower than ωo, the network looks capacitive (generates VARS); and for frequencies higher
than ωo, the network looks inductive (absorbs VARS).

  d. Summarizing transient behavior:

       (1) The impedance of the network is not constant with respect to frequency.

       (2) The impedance Z(s) or admittance Y(s) functions develop drastic changes at various critical,
complex frequencies, which are the roots of the poles and zeros.

       (3) The values of R, L, and C will change the network function if any one value is changed.

       (4) The damping, or energy storage manifesting itself as transient behavior , changes with R/L or
RC depending on the network.

       (5) The network function H(s) becomes more complex with each addition of an inductor , resistor,
or capacitor; consequently, the source and/or load impedance will affect the network as well.

5-11. Solution of harmonic problems

  a. The use of phase multiplication should be considered in the design stages of a particular power
supply. The phase multiplication technique requires special transformer configurations. Retrofits to
existing power supplies, i.e., user loads would entail a cost far outweighing the benefits of the scheme.

                              5-11


---

TM 5-689

                                     H(s)

                     Pole at -X -jω        Pole at -X +jω
          -b                                        S-plane
                                                                                  +jω

                                                            0
                                                                                +b

                 -jω
          Figure 5-3. Surface view of H(s) for all complex frequency in s-plane

          H(jω)
             1/R

                  0 ω0                     ω

                                     Figure 5-4. Response vs frequency for steady state input

       (1) Phase multiplication theoretically will cancel normal harmonics. However, in practice, both
current sharing distributions and phase angles deviate enough to allow only incomplete cancellation.
Most references on the subject indicate that 10 to 25 percent of the maximum harmonic magnitudes will
remain.

5-12


---

         θ & PF                                                                  TM 5-689
          H(jω)                                                              ω
90o / 100% Lead
 45o / 70% Lead
          0% Unity
  -45o / 70% Lag
-90o / 100% Lag

                                                                 ω0
                   Figure 5-5. Phase angle and power factor vs frequency

          Z(jω)

R

   0  ω0                                                                  ω

                                                 Figure 5-6. Impedance vs frequency

    (2) Once systems without higher order phases are in place, there is little the power system engineer
can do but resort to external filtering or real-time cancellation methods.

                                                                             5-13


---

TM 5-689

  b. Tuned passive filters contain several branches of series R-L-C elements. These are connected in
parallel and externally to the non-linear load with the objective of filtering the major harmonics generated
by the load.

       (1) The harmonic currents do not “magically” disappear; rather they flow through the branches
whose impedances have been set to result in a minimum voltage distortion response.

      (2)  An  example    of  a  tuned  passive    filter  containing     elements   for  the    th  and    th  harmonics  and  a

                                                                                               5          7

high pass filter for all the higher harmonics is shown in figure 5-7. The filters represent a constant net

capacitive VAR generation at the fundamental frequency. The inductor Lp is added to re-establish an

overall unity power factor.

                          Ls            Rs

                  SOURCE IMPEDANCE

                                                                                  L       R          Lp

                                                                     L5   L7

           AC                                                        C5   C7         C               Rp         LOAD
           INPUT

                                                                     R5   R7

                                                               TUNED PASSIVE ELEMENTS                     POWER FACTOR
                                                                                                          COMPENSATOR

                                             Figure 5-7. Tuned passive filter

       (3) An examination of figures 5-7 and 5-8 together will show the complexity of this arrangement.
Experience shows there will be eight poles and at least four zeros within the range of harmonic
frequencies normally encountered. The filter is located, selected, and tuned with both the load
characteristics and source impedance (Ls and Rs) in mind. Changing the load, the source, or the filter’s
location can result in degraded or unpredictable performance. The units can be costly to design and set,
bulky, frequency and component variation sensitive, and intolerant of major system design changes.

c.    A  passive  filter  configured    for    rd    th    th    th  and  higher  harmonics  is  shown    in    figure  5-9.  The

                                             3,    5,    7,    9,

phase control of the current through the inductor Lp can continuously adjust filter/load power factor.

With careful design, placement, and tuning, it will effectively handle higher kVA loads of 6-pulse

rectifiers exhibiting incomplete harmonic cancellation. However, the drawbacks discussed in the

previous sections should not be underestimated.

5-14


---

                                                                                TM 5-689

Z(jω)

                                                                             ω

       0         5th         7th

          Figure 5-8. Impedance poles and zeros of tuned passive filter

         L s Rs           L       R                                      Lp
GEN.
                 L5   L7

                 C5   C7     C                                           Rp  LOAD

                 R5   R7

                                     Figure 5-9. Tuned passive filter with static VAR control

  d. The active load current compensator is shown in figure 5-10. It performs every function of the
tuned passive devices with VAR compensation shown in figure 5-9. The active technique requires an
efficient, high speed, switching amplifier. This technique is superior to passive filtering in the following
areas.

       (1) It will power-up/power-down without transients.
       (2) Will go into a self-protection mode should a load short-circuit (crowbar) appear.
       (3) Can tolerate some variation in frequency without compromising performance.

                                                                                                                                           5-15


---

TM 5-689

                   L s Rs I r                                                                        IR + I Q+ I HF        I HF
                                                                                                              P2
                                                                                P1                                         CHFP  LOAD
                                            VLINE                                           I DC
          GEN.
                                                                                                                       P1
                                                                                        P2
           PARALLEL CONNECTED ACTIVE FILTER

                                          Figure 5-10. Active load current compensation

       (4) Will respond to voltage step variation or load current step variation without unwanted
transients.

       (5) Effectively cancels the harmonic currents at its output node by “real-time” addition and
subtraction. In effect, it “linearizes” the load’s non-linear current.

5-12. Measurement of non-sinusoidal currents and voltages

Measuring nonsinusoidal currents and voltages requires radically different techniques than used for
sinusoidal wave forms. Conventional meters (analog and digital) measure either the average value or the
peak value of the wave form, and then are calibrated to read the equivalent RMS value. The RMS value
of a periodic wave is called its effective value; the RMS value of current or voltage is a measure of its
true heating value in a resistance. For a sinewave, the RMS value is 0.707 times the peak value, or 111
times the average value. A meter sensing peak or average values and calibrated using these multipliers to
read RMS values will agree with a true RMS meter.

  a. This only applies if the wave form being measured is a true sinewave. As soon as the wave form
contains harmonics, the ratio of true RMS to average or peak value can change drastically.

       (1) On a squarewave, the average-calibrated meter will read RMS values about 11 percent high,
and the peak-calibrated unit about 30 percent low.

       (2) For pulses, the errors can be tremendous, depending on the height of the peak and on the off-
time between pulses. The average-sensing meter will read very low, as much as 50 percent, and the peak-
sensing meter will read very high sometimes more than 100 percent.

  b. Crest factor is the ratio of the peak or maximum value of a wave form to the RMS value. For a
pure sinewave, the crest factor is 1/0.707 or 1.414. However, for a pulsed wave of the same peak value,
but with considerable “off” time and a low RMS value, the crest factor will be much higher.

5-16


---

                                                                                                                                    TM 5-689

  c. Only a meter or relay that measures true RMS values will give correct readings for a nonsinusoidal
wave form. Some thermal meters apply an input to a resistive load and measure the heat generated. This
gives a true RMS reading, but is very slow in reaction time and, therefore, not practical for most power
system measurements. Some analog meters can be made to measure true RMS, but are complex, slow,
and limited in scope.

  d. Accurate electronic measurement of RMS values has been made practical by micro-processors.
RMS measuring circuits sample the input signal at a high rate of speed, typically about 100 times the
highest harmonic frequency. To measure the 25th harmonic of a power system, a frequency of 1500 hertz,
the sampling rate would be about 150,000 times per second. The microprocessor circuits digitize and
square each sample, add it to previous samples squared, and take the square root of the total. This will be
an accurate RMS value, regardless of the wave form being measured. This cannot be done continuously,
but is done to brief samples and is only possible using the high speed of digital electronic circuitry.

  e. Current transformers must be of high quality (with a very wide bandwidth) to sense high and low
frequencies accurately, if the RMS reading is to be accurate for high-order harmonics and pulsed currents.
This is not a problem for pure 60 hertz sinewaves.

  f. The best designs of modern solid-state circuit breaker trips and of other electronic relays use this
digital sampling technique and true RMS measurement, combined with high-quality sensors, to obtain
accurate tripping on non-linear loads. Older solid-state relays, even though electronic, used average-
sensing with RMS calibration. When applied on non-linear loads, these relays can fail to trip on
overcurrents or can trip unnecessarily.

  g. When induction-disk watthour meters are applied on non-linear loads, the harmonics may cause the
disk to rotate faster or slower than the same RMS current at 60 hertz, depending on the specific harmonic
content. If the watthour meter is used for billing, this can result in utility bills that are too high or low,
and in most cases, too high.

  h. Power factor is the ratio between the true power consumed and the product of the voltage and the
current (power factor = ω/EI, which can be transposed to ω = EI (power factor). For a sinewave, the
power factor is often expressed as the cosine of the phase angle (è) between the voltage and current, and
this equation becomes ω = EI cosine è. This is true only for a sinewave, and cosine è is not the power
factor for non-linear loads. The only accurate way to measure non-linear power factor is to measure the
average instantaneous power and divide that by the product of the true RMS voltage and the true RMS
current. This can be done by digital microprocessor circuits.

  i. When it is necessary to know the actual harmonic content of a wave form, a spectrum analysis can
be performed. This breaks the wave form down into its separate harmonics and measures the percentage
and the phase angle of each with respect to the fundamental frequency. This analysis has been made
practical by digital microprocessor processing. Spectrum analyzers have recently become available that
can print out the results in both graphic and tabular form.

5-13. Conclusions

The problems of non-linear loads and the harmonics they generate will continue to cause problems that
must be corrected. The techniques recommended to minimize the effects of these loads are:

  a. Oversize neutral conductors to 200 percent of phase conductor ratings.

                                                                                                                                           5-17


---

TM 5-689

  b. Locate isolation transformers close to the load.
  c. Derate transformers, generators, and motors.
  d. Use true RMS sensing meters, relays, and circuit breaker trip units.
  e. Make certain that all controls, especially for generator speed and paralleling will operate properly
with non-linear loads.
  f. Select power sources with low output impedances to minimize voltage distortion.
  g. Provide line filters to remove the harmonic loads from the source.

5-18


---

                TM 5-689

     CHAPTER 6
STANDBY POWER

6-1. Introduction

The purpose of this chapter is to provide guidance and understanding of standby power systems that may
be required depending on the reliability of the primary power supply and the desire to maintain the
automated data processing (ADP) system operable and uninterrupted.

  a. There are many electrical power applications which require a continuous and high quality power
source. An uninterruptible power supply (UPS) is an assembly of equipment dedicated to providing
power free of voltage and frequency variation, transient pulses, line noise, and interruption. Techniques
to accomplish these purposes are varied. Combining the characteristics of a UPS system, particularly the
static systems, and a standby generator set presents special considerations to ensure compatibility.

  b. The major problem associated with reliable power for computer systems is how to reconcile
commercial short-duration power interruptions with relatively short time domains in electronic circuits.
The goal of most manufacturers in today’s technology is to build 4 milliseconds to 1 cycle of carryover,
or ride-through time, into their equipment.

  c. Table 6-1 identifies computer input power quality parameters for several manufacturers. This table
should be used only as a source of some examples since computer designs vary with size of computers,
their processing power, and the technology available when the design was created. They are continually
changing and the parameters of power needs are changing rapidly with the designs. Although there is a
degree of variance between computer manufacturers, the following represents the principal power
parameters which are considered important by most major companies. While several of these parameters,
such as frequency variation, can be relatively insignificant when power is derived from a commercial
power source which embodies vast tie networks, they can become an important design consideration
when supplemental or independent power sources are applied as a means of power quality improvement.

  d. Two common sources of standby power are ac generators and dc batteries.

       (1) A standby generator can be on line in a matter of seconds and continue operating as long as the
utility outage lasts. A standby generator set is defined as a unit which supplies continuous electrical
service during interruption of normal power.

       (2) Battery power is a group of electro-chemical cells interconnected to supply a nominal voltage
of dc power to a suitable connected electrical load. The number of cells connected in series determines
the nominal voltage rating of the battery. The number of positive and negative plates in a battery cell is
the basic factor that determines the discharge capacity rating of the entire battery.

            (a) “Primary” type cells are capable of being discharged a single time and cannot be recharged
effectively, e.g., zinc-carbon flashlight cells. “Secondary” type cells, however, can be discharged and
subsequently recharged many times.

                6-1


---

TM 5-689

 Table 6-1. Typical range of input power quality and load parameters of major computer manufacturers

     Parameters*                                             Range or maximum

1) Voltage regulation, steady-state             +5, -10 to +10 percent, -15 percent (American
                                                National Standards Institute (ANSI) C84.1
                                                1970) is +6, -13 percent

2) Voltage disturbances/momentary undervoltage  -25 to –30 percent for less than 0.5s with –100
                                                percent acceptable for 4 to 20 milliseconds

     Transient overvoltage                      +150 to 200 percent for less than 0.2
                                                milliseconds

3) Voltage harmonic distortion**                3-5 percent (with linear load)

4) Noise                                        No standard

5) Frequency variation                          60 hertz ±0.5 to ±1 hertz

6) Frequency rate of change                     1 hertz/s (slew rate)

7) Three-phase voltage unbalance***             2.5 to 5 percent

8) Three-phase load unbalance****               5 to 20 percent maximum for any one phase

9) Power factor                                 0.8 to 0.9

10) Load demand                                 0.75 to 0.85 (of connected load)

  *Parameters 1), 2), 5), and 6) depend on the power source while parameters 3), 4), and 7) are the
product of an interaction of source and load and parameters 8), 9), and 10) depend on the computer load
alone.

**Computed as the sum of all harmonic voltages added vectorially.

***Computed as follows.

     percent phase voltage unbalance =          3 (V max – V min) x 100
                                                  Va + Vb + Vc

****Computed as difference from average single -phase load.

6-2


---

                                                                                                                                    TM 5-689

            (b) Lead-acid cells are by far the most popular type of secondary cell. Properly sized,
installed, and maintained, a stationary battery using lead-acid wet cells can have a life expectancy of up to
25 years in stationary applications, depending upon plate design, relationship between cell capacity and
load demand, cycling, care during installation, maintenance, control of discharges and recharges, and site
environmental conditions. Sealed valve regulated lead-acid (VRLA) batteries offer reduced maintenance
and can be placed in rooms without special ventilation since there is no hydrogen off-gas. VRLAs also
offer higher power densities than equivalent lead-acid wet cells.

            (c) Nickel-cadmium (NICAD) batteries are increasingly applied to emergency lighting and
other standby service. The active materials are nickel hydroxide in the positive plate and cadmium oxide
in the negative. No gases are generated during discharge, and the gases given off during charging are not
corrosive. Initial cost of NICAD batteries is higher than lead-acid on an ampere-hour (Ah) basis.
However, at short rates of discharge, from 90 minutes down to 30 minutes the NICAD battery discharges
a greater percentage of its capacity than does the lead-acid. This high discharge feature is even more
important at extreme rates of discharge. In some applications the Ah capacity of a lead-acid battery must
be twice the Ah capacity of a NICAD battery to do the same job.

6-2. Codes and standards

  a. “Emergency systems” are those classified as essential for human life. The National Electrical Code
(NEC), Articles 700, 701, and 702 in the 1999 edition address the electrical safety of the installation,
operation, and maintenance of emergency, legally required, and optional standby systems respectively.
“Legally Required Standby Systems” which are those systems required and so classed as legally required
standby by municipal, state, federal, or other codes or by any governmental agency having jurisdiction.
The systems are intended to automatically supply power to selected loads (other than those classed as
emergency systems) in the event of failure of the normal source. Article 702 covers “Optional Standby
Systems” which are intended to protect private business or property where life safety does not depend on
the performance of the system. Optional standby systems are intended to supply on-site generated power
to selected loads either automatically or manually. The sources of power discussed are storage batteries,
generators, UPS, separate service, and unit equipment.

  b. Institute of Electrical and Electronic Engineers (IEEE) 446-1995 entitled “Recommended Practice
for Emergency and Standby Power Systems for Industrial and Commercial Applications” addresses the
uses, power sources, design, and maintenance of emergency and standby power syste ms. It includes a
general discussion of needs for and the configuration of emergency and standby systems, the power needs
for specific industries, the selection of power sources, recommendations for protecting both power
sources and switching equipment during fault conditions, recommendations for design of system
grounding, recommendations for designing to reliability objectives, and recommended maintenance
practices.

6-3. Off-line/on-line ADP systems standby power requirements

Most ADP installations can be grouped into two general classes of operation in accordance with their
usage. These classifications are off line and on line. These categories will be helpful in identifying a data
processing system’s vulnerability to electrical power disturbances, since an off-line process will rarely
require power buffering or backup sources of equipment. Conversely, it is common for an on-line system
to warrant the additional expense of buffering or backup equipment.

  a. Off-line ADP systems are generally set up to perform one or more programs at a time in a
sequential or batch type. Often, 24-hour operation for a heavily loaded system may be necessary.

                                                                                                                                             6-3


---

TM 5-689

       (1) In the off-line category, for the most part, are business, scientific, and computer center
applications. Systems of this type are particularly vulnerable when the programs are lengthy (several
hours in duration). Thus the insertion of several natural breaks or checkpoints in the program for
segmentation of long programs is highly desirable.

       (2) Programming can be designed to save intermediate results at a checkpoint and to have the
option of restarting at the last checkpoint which preceded the power interruption. Such a practic e in
program interruption can be valuable in protecting against peripheral equipment failure. Many current
programs are being designed without checkpoint techniques even though the practice has been found to
be feasible. Data dependent programs have running times which vary in duration of the magnitude of
input data, and accordingly it is difficult to limit the run to much less than a 20-minute period.

  b. On-line ADP systems, or as they are often called, “real time” systems, are systems which are time
and event oriented. They must respond to events which occur randomly in time, often coincidentally. An
awareness by the system of events which occur that are external to the computer and beyond its influence
is a requirement.

       (1) In this category are such applications as industrial process monitoring and control systems,
airline passenger reservations systems, vehicular traffic control, certain specialized scheduling
applications, international credit/transaction systems, plus many more. With these systems the computer
outage problem due to power interruption is usually more critical than in off-line applications. Further,
there is generally no merit in segmenting programs. In most cases any outage or power interruption will
result in the loss of some data which was available only during the time period of the usage. The form of
the input data is not conveniently available for a rerun, but may come from sensors such as thermocouples
or pressure transducers which are scanned by a computer.

       (2) When a computer controls a process, potential problems resulting from a power disturbance are
generally serious enough in terms of product damage or equipment malfunctioning to warrant the use of a
reserve or backup power source. Further, any solution, to be adequate, must accomplish the necessary
switching to the backup source without power interruption to the computer. It is obvious that the
potential losses to several hundred users, or input stations, to a time-shared computer system would
warrant the providing of a backup source which can practically guarantee uninterruptible power.

       (3) In cases where equipment or process monitoring must be made, as through data logging,
protection from destruction of only the core memory content during a power interruption may be
adequate. Automatic restart upon return of power is possible to minimize time that the equipment is
down and can often be utilized with the additional provision for a manual means of updating the system
data or information not gathered or scanned during an interruption.

  c. Further differentiation of the single-phase versus the three-phase systems can be made by the
magnitude of load. As with most power utilization equipment, smaller power consuming devices can
generally be supplied from a single -phase source. The differentiation between single -phase versus three-
phase power consuming systems is often necessary since the methods of protection against input power
disturbances and outages can be quite different for each system. Some of the data processing systems
which use single -phase power will employ micro-processors or minicomputers. Others may consist of
multiple single -phase load units distributed in their connection to three-phase power so as to achieve a
reasonable load balance when all units are operating. This may result in load unbalance when some of the
units are turned off. In general, computers and peripheral units which draw less than 1.5 kVA will often
be single -phase. Those which draw more than 10 kVA often require three-phase power. In most cases
single-phase loads can be connected to three-phase sources provided load unbalance at maximum load is
not excessive, generally taken as 25 percent or less.

6-4


---

                                                                                                                                    TM 5-689

6-4. Diesel generator standby systems

The use of a diesel generator for the UPS source can provide extended power for an indefinite power
outage and also supply air-conditioning and lighting loads. Data processing equipment rooms will
typically overheat within a 15- to 30-minute period if the ventilation system is not working, making the
generator set a near necessity for outages in excess of this time. Analysis of battery cost will often justify
a generator set at lower cost than choosing a long battery support time with an accompanying restriction
of eventually implementing an orderly critical load shutdown. A battery support time of as little as a few
minutes may be specified with generator set backup; however, longer support times in the range of 15
minutes are more typical. This minimizes unnecessary starting of the generator set during short power
interruptions of a few minutes, which occurs more frequently than extended outages.

  a. When a power failure occurs, the generator set is automatically started after a short delayed
command. When stabilized at normal frequency and voltage, a transfer switch connects the generator set
to the UPS. The rectifier/charger frequently is equipped with “power walk-in” that gradually applies load
over approximately a 15-second interval when making the transition from battery power to ac source.
This minimizes any large block loading disturbances on the source.

  b. During normal operation from utility source, the UPS inverter frequency stability is assured by a
synchronizing signal that maintains the inverter output phase and frequency in synchronism with the
incoming line. While operating from the battery, the inverter operates from a precise internal oscillator to
maintain frequency. During generator set operation, the UPS inverter must maintain frequency control or
be equipped with over/under frequency disconnect to maintain the inverter frequency within acceptable
critical load tolerance despite frequency deviations of the generator set caused by such things as large air-
conditioning motor starts. An isochronous governor on the generator set is not usually required with a
UPS system if the inverter maintains frequency control during generator set operation. Depending upon
UPS system load, it may be desirable or necessary to bypass the UPS in the event of failure within the
system, momentary overloads, or system maintenance. When using nonbreak “make-before-break”
transfer, both sources are momentarily connected to the critical load. Therefore, the UPS must have
synchronizing circuitry to assure the inverter output and bypass source are in synchronism. The bypass
source must be within acceptable voltage and frequency parameters for the load. Whenever a standby
generator set serves as UPS bypass source, an isochronous governor is recommended to provide minimal
frequency deviation to the critical load.

  c. The following is a procedure suggested by a generator set manufacturer to use in sizing generator
sets that have static UPS systems as part or all of their load. This procedure has four parts.

       (1) Establish UPS input kW using supplier data. If not available from supplier, the following
procedure and guidelines are recommended to approximate or estimate UPS input kW.

                             UPS input kW = UPS output kW + battery recharge kW
                                                           UPS efficiency

            (a) UPS output for computer loads is stated in terms of kVA. For approximating, if UPS
output kVA is given and kW is unknown, use 0.9 power factor (typical for computer systems).

            (b) Battery recharge kW generally ranges from 0 to 25 percent of input kW (15 percent is
typical). If unknown, use 25 percent of output kW for an approximation.

                                                                                                                                             6-5


---

TM 5-689

          (c) If UPS efficiency is unknown, the following guidelines are recommended.

          0.85 if UPS   <100 kW
          0.875 if UPS  >100 kW but <500 kW
          0.90 if UPS   >500 kW

NOTE: Maximum input with redundant systems is less than total rating of individual systems.

       (2) Establish the minimum size generator to contain wave form distortion, i.e., quality of electric
power.

          (a) For 6-pulse rectifier/charger: minimum standby rated generator set = UPS input kW x 1.6

          (b) For 12-pulse rectifier/charger: minimum standby rated generator set = UPS input kW x 1.4

       (3) Size the generator to accommodate other loads. Minimum standby generator rating with other
loads = (UPS input kW x K) + kW of other loads. Where:

          K = 1.15 for 6-pulse rectifier/charger
          K = 1.10 for 12-pulse rectifier/charger

       (4) Combine “(2)” and “(3)” for final selection. Select larger of value and round to nearest larger
size standby generator set.

  d. For example, select a standby generator set for powering a UPS rated 200 kVA/180kW. Other
loads connected to the generator set total 100 kW.

     (1) From supplier data, the UPS input is 255 kW, including battery recharge.

       (2) The rectifier/charger is a 6-pulse circuit. Minimum standby rated generator set = 255 kW x 1.6
= 408 kW.

       (3) Size for other loads. Minimum standby generator set rating with other loads = (255 kW x 1.15)
+ 100 kW = 393 kW.

       (4) 408 kW is larger than 393 kW; therefore, a standby generator set of at least 408 kW is
recommended. A 450 kW standby generator set will satisfy this application. Loads on the generator set
frequently include large motors for air conditioning; and other support functions. Following selection of
the generator set, a check should be made to determine if the generator set has adequate motor starting
kVA capability.

  e. Most system incompatibility problems involving generator sets and UPS systems arise because the
equipment selection and system design did not consider any power source other than a stiff utility system
or “unlimited bus.” When problems do arise, particularly if the system performs satisfactorily on utility,
it is very easy to erroneously conclude that it must be the generator set because it works fine on utility. It
is important to note that loads drawing harmonic currents cause distortion from the source, the source
does not produce distortion.

  f. A standby generator is characteristically of higher impedance than a transformer. Also contributing
to the impedance difference is a significant difference in kVA rating between the two sources. Where a
unit transformer is sized to carry the total facility load, the standby generator set is often only sized to

6-6


---

                                                                                                                                    TM 5-689

carry the emergency or critical loads. A generator may have 5 to 100 times greater sub-transient
reactance than the normal source transformer. Consequently, non-linear loads which work fine on utility
supplied power may react entirely different when powered by a generator set.

  g. Using an oversize generator to reduce reactance may be of some benefit, but a significant reduction
in reactance is not usually economically feasible. A doubling of generator rating is required to reduce
reactance by one-half.

  h. Generators are usually rated for 0.8 power factor. The rectifier/charger may have a lower power
factor. Displacement of current with respect to voltage occurs with rectifier phase control. Line power
factor can vary depending upon silicon controlled rectifier (SCR) conduction angle. Compounding this
are the high frequency harmonic currents which result in added kVARs.

  i. Harmonic currents produce high frequency flux changes and cause heating in stator cores.
Generator rotor losses also occur because harmonic currents in the stator will induce currents in the pole
faces and amortisseur windings. Higher magnetic core temperatures will produce higher winding
temperature. Generator stator heating is also a function of I2R loss, and the winding heating is
proportional to the effective or root mean square (RMS) current squared (RMS current being 1.11 times
the average value). The RMS value of the distorted SCR circuit input current wave form is typically
greater than 1.11 times average current. Derating or using a low temperature rise generator is a means of
compensating for increased heat losses.

  j. Three-phase sensing minimizes effects of wave form distortion by providing an average of all three
phases at any given instant. Since the SCRs in three-phase rectifier loads do not all “gate on” at the same
instant, a minimized distortion, average signal of the three phases is processed. In comparison, a single -
phase sensing regulator will sense severe distortion occurring at a given instant during the cycle in one
phase. Generators having a three-phase sensing network with a floating neutral are common so that wave
form notching is effectively blocked from the regulator. Regulator circuits must include features to
isolate field power control from effects of distortion. If SCRs are used within the regulator, circuits must
be used to prevent the distortion from loaded SCRs interfering with triggering of regulator SCRs.

  k. Generator field power must be filtered to minimize interaction with distortion from the load. A
well filtered regulator combined with the inherent inductive filtering of a brushless design generator
virtually eliminates this problem. Self-excited generators have a well filtered regulator and excitation
system which provides voltage control and stability equivalent to that obtainable with a permanent
magnet pilot exciter. It is also fully capable of sustaining excitation during the short circuit periods
occurring during the commutation of load SCRs without the benefit of excitation sustaining options. A
permanent magnet exciter while capable of sustaining excitation during a sustained fault condition, has no
advantage in providing excitation during the short duration of load SCR commutation.

  l. Common instrumentation used in electric power generation is characterized by wave form
distortion error. Measurement of ac current and voltage is standardized on the basis of RMS value, but
departure from a sinewave may introduce significant error in many instruments. Accuracy of moving
iron-type voltmeters and ammeters, commonly used on generator set panels and switchboards, is
generally limited to commercial power frequencies. These are RMS responding meters; however, high
frequency harmonics may produce eddy current, hysterisis, and inductive reactance effects which can
cause indication errors of as much as 40 percent. True RMS ammeters and voltmeters employing non-
linear converting circuits are available in switchboard cases at a premium cost. These should be capable
of at least 5:1 peak to RMS ratio to ensure accuracy.

                                                                                                                                             6-7


---

TM 5-689

  m. Most electrical devices and equipment will operate relatively unaffected when powered by
generator sets with UPS loads. However, knowledge of potentially sensitive devices may be of value in
system planning. Many electronic devices containing internal ac to dc power supplies with filtering
electronic or control devices that depend upon source voltage “zero crossings” for timing may perform
erratically. If these devices are of low power, a simple and low cost filter will usually eliminate any
problem.

  n. Caution must be exercised where power factor correction capacitors are used. A resonant condition
at one of the harmonic frequencies with some part of the line inductance such as a transformer, on-line
motor, or the generator is possible. Excessive and possibly damaging currents at the harmonic frequency
can flow through the equipment.

       (1) Power factor correction capacitors are used primarily for economic reasons; however, they can
also be effective in reducing wave form distortion. It may be advisable to keep them off the line until the
effects of operating on an emergency generator set with non-linear loads can be observed.

       (2) Three-phase motors connected to the same supply lines as an SCR-controlled load have a
damping effect on harmonics. Some harmonic energy is absorbed by the motors as heat and may be
observed as higher than normal motor temperature rise. A filter or power factor correction capacitor to
attenuate harmonic current may be required if temperature rise is excessive.

  o. Regulating devices, such as battery chargers, voltage regulators, automatic speed controls, and
engine governors with closed loop controls which typically have a reference, error detector, and error
correction elements may be susceptible to instability or self-oscillation. This problem is not frequent but
may occur where response times coincide and create oscillatory response between equipment. Altering
time constants of one of the control systems will usually correct the problem.

  p. Another effect of harmonic wave forms is electromagnetic interference (EMI) /radio frequency
interference (RFI) noise induced into low level signal circuits such as carrier current, telephone, and
electronic engine governors. Basic practices of using shielded wire, good grounding techniques, physical
separation, and/or avoiding parallel runs between power leads and signal leads will minimize these
problems.

  q. A review of the entire generator set distribution system should be made to determine if loads exist
which require a source with low distortion wave form. Unless the generator set system is large, it is quite
common for other loads to share a common bus with the UPS and distortion may occur.

6-5. Battery standby systems

This section reviews the factors to be considered when specifying a stationary battery and the accessories
serving the battery system.

  a. A stationary battery system consists of three interconnected subsystems, normally specified in the
following sequence – (1) the electrical dc load; (2) the battery; and (3) the battery charger. Each
subsystem is described.

  b. The combination of the charger and the battery becomes a system when it is connected to an
electrical load. The load is the equipment that draws dc power from the charger and/or battery. The
charger-battery load combination is most efficient only when all of the components are properly matched
to each other. The charger converts ac power into dc power that is compatible with the battery’s voltage

6-8


---

                                                                                                                                    TM 5-689

and current characteristics. The charger is the converter section of the UPS which charges the batteries
and supplies dc to the inverter.

  c. When the charger and battery are connected permanently to each other and to the load, and the
charger regulates the voltage supplied to the load and the battery, the system is known as a floating
battery system. The battery in such systems is mounted normally on a rack or racks housed inside a
building or enclosure. The load in this case is the inverter.

  d. Major users of stationary battery systems are telephone companies and electric power generating
and transmission systems. Stationary battery systems also are used widely by industrial manufacturing
plants, communications systems, pipe line companies, airports, airline reservations systems, hospitals,
police and fire-fighting headquarters, computer backup systems, sewage treatment plants, and many other
facilities that place critical reliance on power continuity. Some applications include:

       (1) Voltage dips in the primary power supply can be corrected to specified levels with battery
power.

       (2) Voltage spikes can be absorbed by the battery system before they reach critical equipment.

       (3) Electrical ‘noise” produced by other power sources can be filtered from power circuits by the
battery.

       (4) Current demands that temporarily exceed the capacity rating of power input lines and/or the
charger can be met with battery power.

       (5) During the interruption of primary power (converter or rectifier) supply, the battery system is
used as an emergency power source to supply selected loads for a specified time period.

       (6) When operations require uninterrupted dc power supply for lengthy periods after an outage of
primary power occurs, the battery system can serve as a power “bridge” during the time required to
switch from the primary power input lines to the alternate power input sources, such as a standby utility
power circuit from another substation or an on-site standby generator set.

  e. A storage battery uses chemical interactions to produce desired voltage; therefore, it is affected by
changes in temperature. Performance ratings of stationary batteries are based on a standard temperature
of 77°F (25°C). Any deviation from that temperature will affect battery performance and life expectancy.

  f. The storage battery is constructed of a group of identically sized cells connected in series. The
number of cells connected in series determines the voltage rating of the battery. The discharge capacity
of the battery is basically its ability to supply a given current for a given period of time at a given initial
cell temperature while maintaining voltage above a given minimum value. This capacity is stated in
amperes (A) at a given discharge rate. Most stationary battery cells are rated for 8-hour, 3-hour, 1-hour,
15-minute discharge rates to 1.75 volts per cell.

       (1) The rated capacity of the individual cell is the rated capacity for the whole battery. Connecting
the cells in series does not increase the capacity rating.

       (2) The ability of a fully charged cell to deliver a certain number of Ah at a given discharge rate is
determined primarily by the size and/or number of positive and negative plates in the cell. Another
important factor is the type of construction used.

                                                                                                                                             6-9


---

TM 5-689

       (3) There are three basic types of lead-acid positive plates, available in a wide range of plate sizes
for various capacity ratings. The following choices are available for modern stationary lead-acid
batteries.

            (a) Pasted plates use either antimony or calcium alloy grids. The design uses the pasted or
“flat” plate for both positive and negative plates. A lattice grid in each plate is cast of either antimony or
calcium alloy, needed to strengthen the basic lead content of the grid. Antimony alloy contains
ingredients that reduce positive plate wear, local action, and charging current requirements. Cadmium
alloy grids drastically reduce the frequency of watering when the battery is float charged and seldom
cycled. However, frequent cycling will cause the calcium grid in the positive plate to “grow” or
physically enlarge, shortening the cells’ life expectancy. For this reason, calcium cells are best suited for
applications where deep discharges are infrequent. The life expectancy of a pasted plate battery is usually
shorter than either a tubular type or a Plante type.

            (b)Multi-tubular positive plates use antimony alloy grids only. Multi-tubular positive plates
enclose the active material exposed to electrolyte. The antimony alloy grid consists of spines extending
downward from a top bar. Each spine forms the center of a tube filled with powdered active material.
Tubular cells provide the greatest power density of any lead-acid stationary battery design. This means
that more Ah of capacity are provided per cubic foot of battery volume (at moderate rates of discharge).
This feature can be especially important when battery room space is limited. Tubular cells have a
relatively long life expectancy when used at moderate rates of discharge.

            (c) Plante plates use either pure heavy lead or “Manchex” rosettes in heavy antimony alloy
frames. Basic construction of this grid is a heavy antimony alloy configuration in which circular holes
have been cast with specially formed walls. Heavily corrugated strips of high purity lead are rolled into
spiral buttons or “rosettes” that are forced into the holes. The walls of each hole are convex, having a
slightly smaller inside diameter at mid-point in the wall thickness. This “pinches” the button firmly into
place. Each lead button exposes five times more active material surface area to the electrolyte than a
comparable area on a pasted plate. The buttons also help prolong cell life expectancy by providing a
reserve supply of unformed lead for gradual conversion. Manchex cells have recorded performance lives
of 25 years or more in many heavy-duty applications. This battery cell combines long life with
exceptional reliability. Its precise construction requires the highest investment per Ah capacity, but this
cost is substantially reduced when prorated on an annual basis. Manchex cells are an excellent hedge
against inflationary trends that could greatly increase the costs of a replacement battery if shorter-lived,
low-priced cells are used in an installation.

  g. Basic components of a lead-acid cell design for stationary battery applications are listed in their
sequence of assembly at the factory:

       (1) An element is an assembly of positive and negative plates insulated from each other by
separators and “burned” to metal straps. The element is the key assembly of the cell. Its inter-reaction
with the electrolyte determines the cell’s performance characteristics.

            (a) Each plate consists of a rigid lead alloy grid that provides physical support for relatively
porous active materials. The active materials in the positive plates are different from those in the negative
plates.

            (b) Reaction of the electrolyte and active materials creates a current flow when a load is
imposed on the cell. The grids and straps are electrical conductors that carry the current to and from the
posts.

6-10


---

                                                                                                                                    TM 5-689

            (c) The size and number of plates in the element control the discharge characteristics of the
cell. The positive and negative plates are sandwiched together in an alternating pattern (neg-pos-neg-pos-
neg) with a negative plate at each end of the assembly.

            (d) Each positive plate must be separated from its neighboring negative plate by an insulating
material, usually a thin sheet of microporous material, ribbed on the side facing the positive plate.

       (2) A cell cover is usually a molded plastic cover through which protrude the positive and negative
posts to which the element is attached; also includes a vent well with flame arrester.

            (a) The cell cover normally is opaque. The element is connected to the posts that usually
protrude through the cell cover.

            (b) Positive posts are marked either with a plus sign (+) or the letters “POS;” negative posts
carry a minus sign (-) or the letters “NEG.” Cells with four or six posts are designed for the highest
current discharge rates.

            (c) The flame arrester vents protect the cells against ignition of internal gases by external flame
or sparks.

       (3) A cell jar is usually a transparent plastic container which houses the element and electrolyte; a
multi-cell jar has a separate compartment for each cell. The cell jar is usually made of a transparent
impact-resistant plastic material.

            (a) The jars must be large enough to enclose the element while providing reservoir space above
and below the element. The upper space accommodates gradual lowering of the electrolyte level, caused
by water loss during charging.

            (b) The bottom space serves as a collection basin for sediment shed by the plates during many
years of service. This sediment must be kept away from the element; otherwise the cell would be short-
circuited when the sediment contacts both positive and negative plates simultaneously.

            (c) The cell cover is sealed in the cell jar during or after assembly in which the element has
been lowered into the empty jar.

       (4) Electrolyte is a liquid solution of dilute sulfuric acid in which the element is immersed for the
lifetime of the cell.

            (a) Electrolyte in lead-acid battery cells is a dilute solution of sulfuric acid and water. The
ratio of acid weight to water is measured as specific gravity. Pure water has a specific gravity of 1,000.
The quantity of electrolyte in a cell is specified in pounds, kilograms, gallons, or liters.

            (b) Acid electrolyte recommended for most stationary batteries has a nominal specific gravity
of 1.215 at 77°F, when the cell is fully charged. The specific gravity of acid electrolyte gradually drops
as the cell is discharged. When the charger resumes operation after a discharge period, the charging
process gradually raises and restores the specific gravity of the electrolyte.

            (c) A tropical (low) specific gravity of electrolyte can be considered for longer battery life of
cells where the battery room ambient averages above 85°F more than 30 days per year.

                                                                                                                                           6-11


---

TM 5-689

            (d) A medium or high specific gravity electrolyte is available for special applications such as
UPS which in some cases will reduce the battery size. For such types the float and equalize voltages will
have to be increased for normal life.

  h. Specification of the charger and the lead-acid battery depends on the dc load. Each single item of
electrical equipment that will be powered by the stationary battery system must be analyzed. Pertinent
data required for each item of the load includes: voltage range (window); current or kW draw; duration of
operation (time); number of cycles; frequency of use; depth of discharge; and operating temperature
range. After this data has been compiled, the battery and charger can be sized and specified.

       (1) A stationary lead-acid battery system can be designed to meet practically any desired voltage
rating. Most dc-powered equipment systems are within one of the following major dc voltage groups.

            (a) 6-12 volts (emergency lighting units)

            (b) 24 volts (audible and visual alarm systems, engine cranking, communication systems)

            (c) 32 volts (emergency lighting systems, engine cranking, electric clock systems)

            (d) 48 volts (switchgear systems, telephone systems, microwave systems, engine cranking)

            (e) 120 volts (switchgear systems; boiler flame control; emergency lighting systems;
communication systems; telemetering; supervisory control systems; teletype systems, fire alarm systems,
uninterruptible ac power supply systems, large engine cranking, test bench power)

            (f) 240 volts (switchgear systems; uninterruptible ac power supply systems, large engine
cranking)

            (g) Higher voltages (uninterruptible ac power supply systems)

       (2) Stationary battery systems are maintained at voltages higher than the nominal system voltage.
For example, a nominal 120-volt system is operated usually at 130/135 volts. This is due to a tendency of
a battery cell to gradua lly lose some of its electrical charge due to minor electrochemical reactions that
are taking place constantly on the plate surfaces. These losses are made up by constant “float” charging
during normal system operations. Float charging voltage is maintained at a precise pre-set level, virtually
always higher than the nominal system voltage but lower than the recharge or equalizing charge voltage.

       (3) The equipment powered by dc is usually designed to operate within a fairly broad range of
voltage supply. This is necessary for two reasons:

            (a) to accommodate the gradual decline of battery voltage during discharge, and

            (b) to accept voltage increases when required by recharging or equalizing charge operations.

       (4) The minimum and maximum permissible voltages accepted by the dc equipment are vitally
important to the battery and charger selection. This information is used in selecting the size and number
of plates per cell as well as specifying the number of cells in the battery. Voltage ranges for various
operating mechanisms are based normally on the Standards of the ANSI, the National Electrical
Manufacturers Association (NEMA), and the IEEE.

6-12


---

                                                                                                                                    TM 5-689

            (a) One common electrical load in stationary battery systems is switchgear. Operating voltage
ranges for various types of dc switchgear are listed in the “C37 Series” of standards available from the
organizations listed above. These standards include: IEEE C37.13-1990, Standard for Low-Voltage ac
Power Circuit Breakers Used in Enclosures; IEEE C37.14-1992, Standard for Low-Voltage dc Power
Circuit Breakers Used in Enclosures; IEEE C37.20-1-1993, Standard for Metal-Enclosed Low-Voltage
Power Circuit Breaker Switchgear; ANSI C37.16-1997, Low-Voltage Power Circuit Breakers and ac
Power Circuit Protectors Preferred Ratings, Related Requirements, and Application Recommendations;
ANSI C37.17-1997, Trip Devices for ac and General Purpose dc Low Voltage Power Circuit Breakers.

            (b) A typical example of approved voltage ranges, based on a nominal 120-volt system, lists dc
voltages between 105 and 140 volts for tripping mechanisms of low-voltage air circuit breakers. If this
system is served by a conventional antimony alloy lead-acid battery, it would have 60 cells float charged
at 2.20 volts per cell equivalent to a system voltage of 132 volts. During recharging operations following
a battery discharge, the system voltage would be raised to 140 volts by temporarily increasing the
charger’s output to 2.33 volts per cell. At the end of a pre-set recharging period, the system voltage
would return to the float voltage level.

            (c) When electronic components in communications and control circuits require a narrow
range of permissible dc voltages, the battery engineer must be advised of the fact. The
minimum/maximum voltages of such critical hardware should be grouped separately in the equipment
description.

            (d) One method of lowering maximum battery system voltage is to use fewer cells in the
battery. This design can allow recharging at 2.33 volts per cell without exceeding the maximum
permissible voltage accepted by the dc equipment. However, the battery must be equipped with cells that
are higher in rated discharge capacity, in order to meet the minimum voltage limits.

            (e) Another method of reducing maximum battery system voltage is to eliminate the charger’s
recharge and equalizing charge voltage. The float charge level in such systems is raised to a voltage
which will maintain the battery system under all conditions. This higher float voltage (at 1.215 specific
gravity) must never exceed 2.20 volts per cell, except when a special float voltage is recommended.
However, such systems require a substantially longer recharge time following a power outage, since the
recharge current is limited.

            (f) When the dc electrical load inventory includes loads rated for different voltages (i.e., a 120-
volt pump motor and a 48-volt circuit breaker), battery engineers recommend that each voltage class be
served by a separate battery and charger. It is technically possible to modify the main battery by
connecting supplementary cells to provide a higher voltage level for selected loads, but two chargers are
essential – one to recharge the 48-volt battery and a second to charge the 120-volt battery.

       (5) Another critical factor that must be considered by the system engineer is the voltage drop
caused by resistance in conductor runs. Any equipment powered by a battery should be located as
physically close to the battery as possible. If the distance between the battery and the load is substantial,
the voltage drop can be minimized by using a larger conductor. If this is not feasible, the calculated
voltage loss should be added to the voltage requirement of the load. This will allow the battery engineer
to compensate by specifying larger cells for the battery. Voltage drop is especially severe in high ampere
applications, where special attention to the problem is recommended.

            (a) Each item of electrical equipment is assigned a nominal current or kW rating by its
manufacturer. This rating is used by the electrical engineer as a guide when sizing the circuits that feed
power to that equipment and any other equipment connected to that circuit.

                                                                                                                                           6-13


---

TM 5-689

            (b) The battery engineer must know the current ratings, which are a vital part of the load
specification. If the load is a given constant wattage, the current output of the battery will increase as the
battery voltage declines during discharge.

            (c) In addition to the normal A rating, some electrical equipment has another current factor that
is seldom rated by the equipment manufacturer, but which is highly important to the battery engineer.
This is the temporary high ampere demand, called inrush current, imposed on the power supply when
electric motors, etc., are activated. Inrush demands must be determined – or estimated on the high side –
so that battery supply voltage will not drop below critical specified minimum limits during the inrush.

            (d) Individual equipment operations are normally classified in one of the following categories -
continuous load for indicating lights, relays, alarm systems, and other items; time-limited loads, such as
motors, emergency lighting, communications systems, etc., which are longer than a minute but shorter
than the battery’s duty cycle; and momentary current demands, particularly the power needed to close or
trip switchgear, which may be imposed at intervals during the duty cycle.

       (6) The operational cycle of required equipment is an important factor for consideration in
specifying the battery requirements. The duration of operation of each equipment item should be
specified in hours, minutes, or seconds, whichever is pertinent. The battery engineer collates this time
data with the equipment’s ampere or kW rating to determine its effect on the total duty cycle.

            (a) When an equipment item is used more than once during the duty cycle, the anticipated
frequency of such usage must be specified.

            (b) If this frequency is considered variable, depending on such circumstances as equipment
positions or status at the time the duty cycle began, the maximum number of possible operations should
be specified in the duty cycle. This is necessary to ensure sufficient battery capacity to handle a worst-
case situation.

       (7) Environmental conditions and location must also be considered when specifying the battery.
Normally , storage batteries are sized to perform at 77°F but allowance must be made in the calculations
for lower temperatures which require more capacity to meet the load criteria. Freezing of the electrolyte
results in water crystals forming but a solid mass is seldom formed. Such crystals damage the plates
resulting in reduced life.

            (a) Charger and UPS performance are adversely affected by altitudes higher than 3,300 feet
(approximately 1,000 meters) above sea level or ambient temperatures above 105°F (40°C).
Compensations for these factors can be designed into the lead-acid battery system.

            (b) Battery capacity is reduced when battery room temperature is normally lower than 77°F.
Battery life expectancy is shortened when the battery room temperature is consistently higher than 85°F.

       (8) After an equipment inventory has been compiled, describing all of the electrical loads intended
for operation using battery power, the sequence of operation must be scheduled. This listing of dc loads
in sequence during the battery discharge is called the duty cycle schedule.

            (a) Selection of the proper size of battery depends not only on the current or kW draw and
duration of each load, but also the sequence in which they occur. Careful scheduling of the load sequence
in the duty cycle can be of considerable help in keeping battery cell size to a minimum, which lowers
costs.

6-14


---

                                                                                                                                    TM 5-689

            (b) A simple stationary battery system with only one continuous load throughout the duty cycle
is easy to size. A typical example would be an emergency lighting system in which 50 A are demanded
for three hours. Cell selection tables are provided in catalog sheets.

            (c) Many stationary battery systems are multi-load rather than single -load systems. When a
variety of loads are connected to the battery, sudden increases and decreases in current demands are
imposed on the battery system. If the high-current loads can be scheduled for the beginning of the duty
cycle, the battery can be sized smaller than if the high-current loads are activated at the end of the
discharge cycle. However, if a load is random in nature and could occur at any time during the duty
cycle, it is normally good practice to indicate the random load on the schedule as occurring at the end of
the duty cycle, when its effect would be most severe. In some cases, it may be advisable to show the
random load occurring simultaneously with the highest ampere load in the discharge schedule. The
battery engineer must plan for the worst-case situation to ensure meeting the specified protection time
requirements. A company representative should be consulted if there is any question regarding placement
of the random load in the sequence of the duty cycle.

  i. Short-circuits affecting stationary battery systems usually involve the total system voltage and
occur chiefly in the dc switchgear or other electrical load circuits. Instantaneous high currents, as high as
9 to 12 times the 1-minute discharge rate to 1.75 volts per cell of the battery, can occur. Therefore, the
stationary battery system should be equipped with fault current protective interrupting devices
strategically located throughout the power distribution system. This assumes that the power distribution
system is capable of carrying the high current rating of the interruption devices.

       (1) The individual tripping and closing circuits of each power circuit breaker should have separate
fault protective devices. This is necessary to prevent any fault in the closing circuit of a breaker from
jeopardizing tripping. A fault in the control circuit of any one device or breaker should not be allowed to
interrupt the control power supply to all the breakers and other electrical loads served by the stationary
battery system.

       (2) Some stationary battery systems are operated without a main protective device because failure
of such a device could accidentally shut down the entire system. The designing engineer must review the
applicable codes and pertinent factors of the installation before deciding whether or not to install
protective devices on the battery’s distribution. However, if the battery is installed before the electrical
loads are ready to be connected, and if construction work is underway in the general area, engineers
recommend protective devices until such time as the loads are ready for connection.

       (3) Either one-time fuses or molded-case breakers may be used as short-circuit protective devices.
The fuses operate much faster than the breakers when an over-current occurs. A one-time fuse, with 10
times rated current passing through it, will interrupt the circuit in about 0.1 second, compared to
approximately 0.7 to 2 seconds for magnetic breakers. Switchgear manufacturers generally recommend
and furnish fuses in battery control power circuits.

       (4) When sizing these fuses or breakers, engineers generally assume a zero resistance at the
location in the circuit for which the short-circuit calculations are to be made. This theoretically represents
a worst-case example. In actual practice, the current delivered through a fault will depend on resistance
of the short-circuit path; battery’s state of charge; battery’s electrolyte temperature; and voltage existing
at the battery terminals at the time the short-circuit occurs.

  j. During the charging and discharging process of battery operation, hydrogen gas is formed.
Hydrogen gas is very explosive when exposed to open flames, sparks, and cigarettes.

                                                                                                                                           6-15


---

TM 5-689

       (1) The room in which the battery is located should be provided with ventilation, so as to prevent
the buildup of liberated hydrogen gas. In the USA, Occupational Safety & Health Administration
(OSHA) specifies that the concentration of hydrogen gas should not exceed 1 percent. Other countries
may permit other levels of hydrogen concentration. Room ventilation must be adequate to assure that
pockets of trapped hydrogen gas do not occur, particularly at the ceiling.

       (2) Significant amounts of hydrogen are evolved only as the battery approaches full charge. When
the cell is fully charged, each charging ampere produces 0.016 cubic feet of hydrogen per hour from each
cell. This volume applies at sea level when the ambient temperature is 77°F.

  k. Battery chargers used in stationary battery systems are normally constant voltage chargers. Voltage
adjustments can be made with precision to 1/100th of a volts per cell. This is necessary because floating
voltage and equalizing; voltage levels critically affect battery performance and life expectancy. Voltage
level specifications are normally expressed to two decimal positions; i.e., 2.25 volts or 2.33 volts.

       (1) Proper specifications and adjustments of the battery charger are the most important factors
affecting the satisfactory performance and life of the battery cells in a stationary battery system. Voltage
levels from the charger also usually serve the electrical load, so changes in charger voltage output affect
the load.

       (2) Battery chargers for stationary battery systems normally are specified after determining:
system voltage, current, filtered or unfiltered dc output voltage, wall-hung or floor-mounted housing, ac
voltage, single - or three-phase ac input power, and frequency of ac input power. The current of ac input
power can be specified by the manufacturer after the above factors have been determined.

  l. Valve regulated lead acid (VRLA) batteries are sealed except for a valve that opens to the
atmosphere when the internal buildup of gas pressure exceeds atmospheric pressure by a predetermined
amount. The electrolyte within a VRLA is immobilized either by adding a gelling agent or by using
absorbent separators. VRLA cells provide a means for recombination of internally generated oxygen and
the suppression of hydrogen gas evolution to limit water consumption. VRLA batteries can be used for
the same applications as conventional vented wet cell batteries; however, they are susceptible to two
failure modes that are not normally associated with vented cells, dry-out and thermal runaway.

       (1) Dry-out can result from excessive water loss as a result of electrolysis or diffusion through the
jar and cover walls. Both mechanisms of water loss result from operating at elevated temperatures. The
high temperatures can be caused by operation at higher than normal float voltages or higher positive grid
corrosion rates.

       (2) Thermal runaway can occur if the rate of heat evolution due to the recombination reaction is
greater than the rate of heat dissipation. The hotter the battery, the higher the current needed to maintain
the float voltage. The increased current then results in still more recombination and heat generation,
which further raises battery temperature. The net effect can be the accelerated dry-out or melting of the
battery. The potential for thermal runaway can be minimized by appropriate ventilation around each cell
and by limiting the charger output current and voltage by using temperature compensated chargers.

       (3) Maintenance and surveillance requirements for VRLA batteries are similar to those required for
vented cells except that specific gravity readings and water additions are not possible. Instead, internal
impedance or conductance tests can be used to provide information for comparison of individual cell
measurements with either initial baseline values or with present values obtained from similar cells.

6-16


---

                                                                                                                                    TM 5-689

  m. NICAD batteries with high-rate discharge performance are used for applications demanding a
heavy surge of current for short periods, such as engine/turbine starting, switchgear control, or inverter
supply. This type of cell is characterized by a great number of very thin plates, closely spaced, creating
an extremely low-resistance electrical path. Intra-cell members, such as collector bars and posts, as well
as inter-cell connectors, are of large cross-section to ensure low resistance. This design takes advantage
of the fact that high-rate, short-duration discharge efficiency is more a function of plate surface area and
the conductivity of current-carrying structures than of the amount of active material (which establishes the
battery’s Ah rating). High rate units are available in cell sizes from 85 to 570 Ah capacity and in plastic
or steel containers.

       (1) For long-rate discharge performance when plate surface area and current-carrying structures
have little effect on the efficiency of discharge, it is more economical to use a cell construction with fewer
plates, each with relatively more active material. Long rate discharge units are available in cell sizes from
10 to 1245 Ah capacity.

       (2) For intermediate-rate discharge performance, plate thickness and plate separation are greater
than the high rate discharge type and less than long rate discharge. Intermediate rate discharge units are
available in cell sizes from 13 to 1180 Ah capacity.

       (3) Proper battery and system performance can be optimized if insta llation aspects are properly
considered during the design. The battery and its charger should be located close to one another for
convenience in checkout and servicing. It is particularly important that the battery also be installed as
close as possible to its load to minimize cable length and subsequent voltage drop. Cables of sufficient
size must be used, particularly in high-rate applications such as engine-cranking and switchgear. The
ordinary rules of wire sizing pertaining to 120-volt ac circuitry cannot be used when figuring wire sizes
for high-rate discharges. Calculate wire size based on current, voltage, and cable length.

       (4) Normal ventilation is entirely adequate for the room in which a NICAD battery is installed. A
hood or exhaust fan is not necessary unless the room has no ventilation. During the last portion of high-
rate charging, all batteries give off gas (a mixture of hydrogen and oxygen).

       (5) If it is necessary to install the battery in a closed compartment, ensure that there is adequate
ventilation by arranging for large vents in the bottom, sides, and top. Small holes in each corner must be
drilled to allow for drainage of water that might be spilled during battery servicing operations.

       (6) If the battery is to be serviced through a cover or hinged door on top of the compartment, allow
a minimum clearance of 3 inches between the top of the vent plugs or caps and the battery box cover.

       (7) If the battery is to be serviced from the side, allow additional cle arance between vent plug or
cap tops and cover.

       (8) The battery charger is vital to the proper performance, long life, and reliability of the battery it
is connected to.

       (9) The charger must meet two requirements: its nominal voltage must be the same as the battery
and its capacity must be adequate to handle the load – both for the charging of the battery and for any
external load, intermittent or continuous.

       (10) Battery chargers are usually described in terms relating to their dc voltage and ampere output:

                                                                                                                                           6-17


---

TM 5-689

            (a) Constant current has a rating and characteristics which permit a constant-current charge to
the battery by manual or automatic adjustment over the full charge voltage range of the battery.

            (b) Constant potential has a regulated dc voltage output and theoretically has a sufficiently
high current output to furnish the maximum current the battery will accept at the regulated voltage.

            (c) Modified constant potential has a regulated output voltage with current limiting. Chargers
used with NICAD batteries are generally of this type – either float chargers or with the capability of two-
rate charging, either manually or automatically switched to high-rate as required by the battery. This type
is considered the most satisfactory for standby service.

       (11) Like all vented storage batteries, the gas given off by NICAD batteries during high-rate
charging is a mixture of hydrogen and oxygen, which is a result of the decomposition of water by the
passage of current through the electrolyte.

       (12) The gas is completely non-corrosive – cut, under certain conditions, can be potentially
explosive. However, even slight movement of air around the battery such as normal room ventilation will
dissipate the concentration of the gas.

       (13) The NICAD battery uses an alkaline electrolyte – potassium hydroxide (KOH) instead of
sulfuric acid.

       (14) The specific gravity of the electrolyte of the NICAD battery remains essentially constant
(1.180 + 0.020) in both charged and discharged conditions, unlike the electrolyte of the lead-acid battery
whose specific gravity changes.

            (a) The nominal individual cell voltage is 1.2 volts.

            (b) The float charging voltage is 1.40 – 1.42 volts per cell.

            (c) High-rate charging voltage is 1.50 – 1.65 volts per cell.

       (15) Stationary batteries of the lead-acid or NICAD type have a standard Ah rating based on either
the eight- or the ten-hour rate to a specific end voltage, such as 1.14 volts per cell in the case of a NICAD
battery which is similar to 2.22 volts per cell in a lead acid system. The number of cells in series will
determine the system voltage where for a NICAD battery, 1.2 volts per cell is normally used. Table 6-2
compares the cells required for certain voltages for NICAD and lead-acid batteries. These are typical
voltage ratings which represent series connections of cells. The Ah capacity rating is a fixed basis for a
constant current discharge for a specific time where the battery is guaranteed to stay above that minimum
voltage per cell at that temperature where the base temperature rating is given as 77°F. It must be
emphasized that the Ah rating of the battery as a basis for calculation is only good at the particular time
given such as eight hours. If a battery is discharged at higher rates, i.e., shorter times than eight hours, it
will not perform as efficiently and less total Ah will be obtained. Similarly, a battery discharged for
longer than eight hours will operate somewhat more efficiently and extra capacity can be obtained on
discharges of 24, 48, or 72 hours. The factory should be consulted in such load profiles in order to gain
the most competitive battery sizing for the application.

6-18


---

                                                                                                                TM 5-689

Table 6-2. Comparison of cells required for NICAD and lead-acid batteries

Voltage  NICAD Cells  NICAD Cells (nom)  Lead-Acid Cells

     12         10           9 – 11              6
     24         20          18 – 22             12
     48         37          36 – 40             24
    125         92          90 – 96             60
    240        184         180 – 192           120

       (16) NICAD batteries have an advantage when it comes to sizing because of low, medium, and high
rate battery types to choose from. Often, a high rate NICAD battery will give substantially higher
currents than a competitive type of unit of the same total Ah rating. On this basis, it may offer a much
better economic picture.

            (a) As an example, three different simple load situations and assuming 25°C and 1.14 end
voltage in all three cases, the first case would be the eight-hour discharge rate. The most economical
choice here may be the low-rate battery. A comparison of the data and cost for the medium rate and high
rate cells must be performed to substantiate this choice.

            (b) The next check is the 1-hour discharge rate. Similar comparisons must be performed.

            (c) The last check would be to compare the 1-minute rate. After examining the data, it can be
determined if the low-rate battery is the most economical choice. Tripping in the switchgear may be a
concern where a small medium-rate cell will adequately do the job versus a high-rate battery. Also
certain control loads, while they have short durations, have very low currents, therefore, the smallest low-
rate battery is quite sufficient for the load application. However, as a general statement, short duration
high-rate discharges will be best served by high-rate batteries.

  n. Continuous battery monitoring equipment is available which is used in conjunction with a battery
charging system. These systems can monitor float charge rate, voltage levels of individual cells or the
complete bank, monitor liquid level, and adjust charge cycle and rate of charge.

       (1) A well-designed monitoring system can add significantly to the reliability of a system, but it is
not designed to replace monitoring and maintenance by qualified personnel.

       (2) To insure satisfactory operation of batteries in all types of systems, the batteries must be
maintained on a regular schedule. Special safety precautions must be observed to protect maintenance
personnel and the equipment when working around batteries.

       (3) The area where the battery is installed must be ventilated. Maintaining a proper, well-
ventilated environment is the most important maintenance technique that can be performed for batteries
since hydrogen, an explosive gas, is emitted from batteries during charging.

       (4) During charging, some of the water molecules in the battery electrolyte break down and are
separated into the elemental components, hydrogen, and oxygen. The hydrogen and oxygen escape from

                                                                                                                                           6-19


---

TM 5-689

the battery through the vent plugs, which lowers the level of the water. Therefore, the water should be
replaced periodically.

       (5) The battery jar is marked with high and low level marks. The level of electrolyte should
always be between these marks. A cell or battery could suffer permanent damage if the electrolyte were
left to drop below the top of the metal plates. The procedure for adding water depends on whether the
cells are equipped with explosion-proof vent plugs or regular plugs. Specific instructions are given by the
battery manufacturer. Water is poured through the center of the plug or hole, and eye guards should be
worn for safety. Unless there is a specific recommendation from a qualified chemical engineer, acid or
electrolyte should never be added to the cells. Water from the plant drinkable water supply can be used in
batteries, as long as periodic analyses for impurities are made. When the normal water supply is not
suitable, distilled water should be used. No special powders, booster chemicals, or jellies should be added
to station batteries.

       (6) One sign that the float level charging current is too high is that water must be added more
frequently than the normal, once a year addition. Float charge voltage is critical and should only deviate
from the recommended level by 1 percent. A very accurate voltmeter should be used in setting float
specific to the type of battery and manufacturer and should be checked against the battery supplier’s
recommendation. A typical voltage for lead acid batteries is 2.22 volts per cell.

       (7) A short-duration charge at higher than the float voltage is made periodically to insure that all
cells in a battery have an equal charge. Battery chargers are equipped with an equalize/float switch or
with a timer switch which automatically limits the duration of an equalize charge.

       (8) Specific gravity is read at least once a year. An on-going record is kept both in the battery
room and in other plant maintenance records. Specific gravity is read with a hydrometer syringe. The
instructions which accompany a battery indicate the safe range of reading for a particular type of battery.
To obtain an accurate reading, the battery must have been charging at the specified float rate for at least a
few days. The hydrometer reading may be misleading if the battery has been charging at an incorrect
rate. Before making a hydrometer reading, hydrometer indication must be corrected for temperature to
obtain a reading comparable with past readings. The base temperature for correction is 77°F.

       (9) The following safety precautions should be performed during periodic inspections and
maintenance on the batteries.

            (a) Replace explosion-proof fixtures such as globes for explosion-proof room lights with exact
replacement parts.

            (b) Do not smoke around batteries or in the battery room.

            (c) Turn the room vent fan on for a few minutes before entering.

            (d) Wear safety eyeshields or approved goggles while checking or handling the batteries.

6-6. Transfer switches for standby systems

The purpose of the automatic transfer switch in the electrical system along with its related controls, is to
switch power from either the normal or the emergency source to the electrical loads. For maximum
protection, the automatic transfer switch should always be located as close as possible to the electrical
loads it serves.

6-20


---

                                                                                                                                    TM 5-689

  a. The controls have the intelligence to monitor the normal source. If there’s a power outage - a
supply transformer burns out, a power line is knocked down, lightning strikes, or any other cause for
power to fail – the controls signal the standby engine generator to start. When the generator reaches
proper voltage and frequency, the controls cause the switch to transfer the connected loads to the
generator. When the normal source is restored, the loads are transferred back to the normal source, and
the engine is shut down after a cool-down period. It is all handled automatically by the automatic transfer
switch.

  b. The transfer switch should include all of the features that are necessary to fulfill its requirements.
Such features are voltage and frequency sensing, various time delays, engine control contacts, manual
controls, and indicators.

  c. When selecting a transfer switch, certain considerations should be made. Some of the basic things
that should be considered when selecting a transfer switch are given below.

       (1) The two sources (normal and emergency) should never be connected to the load at the same
time unless the system is designed for this type of operation. Doing so could create a short circuit from
one source to the other with damaging results.

       (2) The switch contacts should always be closed on one source or the other – never in-between. In-
between (not closed on either source) is undesirable because it would mean that the load would not be
getting power from either source. The only type of switch that will satisfy proper operation is a true
double-throw, inherently interlocked switch; that is, closed on normal and open on emergency, or closed
on emergency and open on normal.

  d. Power to the load is always going through the transfer switch. It is important that the switch be
designed for continuous duty from either source and be able to transfer to and operate from one or the
other source at any time. While the switch is connected to one source, the contacts on the other source
can become coated from exposure to the atmosphere and thus cause poor contact when the switch
transfers to them. The arc that is formed at the contacts when the switch transfers can also cause the
current-carrying contacts to deteriorate. To keep them clean and operable, the current-carrying contacts
should have high contact pressure and be able to clean themselves with a wiping action when they
operate.

  e. Emergency systems must respond quickly to assure minimum outage time in accordance with the
NEC. Fast operating transfer time is also important when protecting motors with in-phase transfer.
Therefore, the operating time for transfer switches through 4000 A should not exceed 1/6th of a second in
either direction – normal to emergency and emergency to normal.

       (1) A solenoid operator will provide the inherent double -throw operation that is needed. With the
single solenoid operator, there are only two possible positions that the switch contacts can be closed on
normal, open on emergency; or open on normal, closed on emergency. Obviously, if both contacts were
closed, there would be a short circuit from one source to another. If both were open, the load would be
disconnected from both sources.

       (2) The single solenoid operator power drives the contacts from one source to the other, then
mechanically locks them in place with high contact pressure. This simple mechanism eliminates any need
for hooks, latches, or motor drives.

       (3) Because of the erosive and destructive action of arcs, the main current-carrying surfaces must
be protected. Construction should be such that the arc is pulled away from the main contacts. Switches

                                                                                                                                           6-21


---

TM 5-689

over 400 A should utilize separate arcing contacts to properly protect main contacts. Switches 400 A and
under, where arc energy is lower, should utilize arc runners and contact tips.

       (4) To prevent the arc from short circuiting one source to another, the arc must be extinguished
rapidly regardless of current level or power factor. A wide arc gap is necessary to accomplish this.

       (5) To reduce heat and lengthen insulation life, switches over 400 A should have segmented
contacts to provide multiple paths for current flow.

       (6) Conventional contacts can separate due to the electromagnetic (EM) forces that occur during
fault currents. The consequence at this time, if contacts open, is violent arcing with severe erosion and
deterioration of dielectric. Blow-out contact construction on switches over 400 A uses EM forces to keep
contacts closed until the over-current device clears the fault.

  f. Transfer switches are generally located in the main or secondary distribution bus which feeds the
branch circuits. The switch must be designed to close against high inrush currents, to interrupt current,
to carry full rated current continuously, and to withstand fault currents.

       (1) When the contacts on a transfer switch close, they may be required to pass a substantial inrush,
or surge, of current; the amount will depend upon the load.

            (a) For tungsten lamp load, the cold resistance is approximately 1/15th to 1/17th of the hot
resistance. This means that theoretically the initial lamp current will be 15 to 17 times normal operating
current. Such inrush currents may take as long as 14 cycles (.23 second) to return to a normal or steady-
state condition. These characteristics vary depending upon lamp wattage.

            (b) Motor loads are also a source of high inrush currents. If a stalled rotor motor is connected
to a source of power, the inrush currents will be in the neighborhood of six times normal running current.
A ratio of ten times running current is generally used in designing motor controllers. This may not be a
realistic inrush ratio for transfer switches. Transfer switches must be capable of transferring a running
motor from one source to another. These two sources are not necessarily synchronized and, therefore, the
residual voltage of the motor may be 180° out of phase with the voltage to which the motor is to be
transferred. This means that the motor may momentarily draw as much as 15 times normal running
current. The transfer switch must be capable of closing on such loads. In-phase monitors are designed to
minimize the condition when large motor loads are transferred.

            (c) There must be no tendency for the contacts of a transfer switch to weld when closing on
loads having high inrush currents. This means that the physical construction of the switch must provide a
minimum of contact bounce and have ample thermal capacity. Good engineering practice demands a
transfer switch capable of withstanding inrush currents of 20 times full load rating.

            (d) Transfer switches should be rated for all classes of load including any combination of
motors, electric discharge lamps, electric heating (resistive) loads, and tungsten lamp loads.

       (2) Upon retransfer to normal, the switch is normally required to interrupt rated current at full
voltage. Ordinarily on transfer to emergency the current interrupted will be zero or relatively small. The
transfer switch can also be called upon to interrupt full load currents at full voltage under test conditions.
Accordingly, the automatic transfer switch ratings must apply to both normal and emergency contacts.

            (a) Wide arc breaking distances combined with magnetic blowout insure rapid arc interruption
during transfer from one source to the other. Magnetic blowout coils are less effective at lower current

6-22


---

                                                                                                                                    TM 5-689

levels and, therefore, the use of wide arc breaking gaps is also required. It is often more difficult to
interrupt currents at the 20 percent level than at higher levels.

            (b) Installations often require transfer switches to be capable of interrupting at any current
level from 20 to 600 percent of the continuous duty rating at a power factor less than 50 percent.

       (3) A transfer switch differs from other emergency equipment in that it must continuously carry
current to critical loads. The engine generator set is generally required to provide power only during the
emergency period, whereas current flows through the transfer switch continuously during both normal
and emergency conditions, with an expected minimum life of 20 to 40 years. During this period, fault
currents, repetitive switching of all types of loads, and adverse conditions should not cause excessive
temperature rise nor detract from reliable operation. Continuous duty operation should be achieved with
minimum maintenance.

            (a) To meet the requirements for continuous duty, the contact temperature rise of a transfer
switch must be well below that established for an eight-hour rated device, and the quality of contact must
be sustained through proper contact design, including separate arcing contacts on larger switches rated
above 400 A. Arcing contacts prevent or minimize arcing at the main contacts, which would cause
contact erosion and affect the ability of the switch to carry current continuously.

            (b) When selecting a transfer switch, determine the maximum continuous load current which
the transfer switch must carry. Momentary inrushes, such as occur when lighting or motor loads are
energized, can be ignored. Select a transfer switch that is either equal to or greater than the calculated
continuous current.

            (c) Sometimes the transfer switch size is selected to be the same as the over-current device
ahead of it on the normal side. Although this may not be necessary, it is a convenience which permits the
addition of future loads while remaining within the system’s capacity. Sometimes, to obtain a higher
withstand current rating, a higher continuous duty rating, a higher continuous duty rated transfer switch
may be used.

       (4) Transfer switches are designed to withstand the magnetic stresses and dissipate the heat energy
resulting from high fault currents. Withstand current ratings vary depending on the switch size and type.
For most applications, transfer switches have adequate withstand current rating when used with current
limiting fuses or breakers.

            (a) To properly evaluate application and coordination of transfer switches with protective
devices, a system short-circuit calculation should be made to determine the symmetrical fault current
magnitude and the X/R ratio at each point of application. The X/R ratio is the ratio of the reactance to the
resistance of the circuit. As the X/R ratio increases, both the fault withstandability of a transfer switch
and the fault interrupting capacity of an over-current protective device become more critical.

            (b) A transfer switch should be capable of withstanding the available fault current at its
location in the system until the over-current protective device clears the fault. The system designer
should determine the available RMS symmetrical fault current at the transfer switch location, the X/R
ratio, voltage, and types of protective devices (current limiting fuse, molded case breaker, power breaker)
before a properly rated transfer switch with adequate withstand current can be selected.

            (c) Transfer switches are rated in terms of the available RMS symmetrical current with a
specific X/R ratio and specific types or classes of over-current protective devices. For example, a 600 A
transfer switch is rated for use with Class L fuses in a system having an available fault current of 200,000

                                                                                                                                           6-23


---

TM 5-689

symmetrical RMS A. This is based on a maximum size fuse rating of 1200 A, and an X/R ratio not
exceeding 6.6. Most installations normally do not exceed an X/R ratio of 6.6 (i.e., power factor of 0.15).

            (d) The factors that account for the high withstand current ratings of transfer switches, include
blow-on contact structure, thermal capacity, and operational time delay.

            (e) In many switching devices, the EM fields which encompass the current-carrying conductor
act to force the contacts to separate. Since these EM forces increase exponentially with current, it can be
anticipated that the contacts will separate during short-circuit currents because of magnetic effects. The
consequence is substantial arcing accompanied by severe erosion, deterioration of dielectric , and possible
flashover.

            (f) The amount of heat generated at the transfer switch is proportional to the resistance of the
parts that carry the current through the switch, multiplied by the square of the current. To provide the
thermal capacity needed to cope with this heat, the cross section of the current-carrying parts must be of
substantial magnitude to keep the resistance down to a reasonable value. It is also necessary to provide
adequate radiating surfaces, along with high contact pressures, to keep heating to a minimum. Most
importantly, the contacts on larger switches should provide multiple current paths.

            (g) On large transfer switches segmented contacts are utilized to provide multiple paths for
current flow through to main contacts. This reduces the heat generated and thereby provides longer life
without replacement of contacts.

            (h) A voltage drop normally accompanies large fault currents. It is important that the voltage
drop does not cause an automatically operated switch to transfer while the switch is carrying the fault
current.

            (i) Two safeguards are provided: the mechanically held mechanism and a time delay to
override momentary dips in voltage. The mechanically held mechanism assures that the switch will not
transfer until control voltage is applied to the transfer switch solenoid coil. To prevent energizing the
solenoid coil until the over-current protective device clears the fault, a standard nominal time delay,
adjustable up to six seconds, is incorporated into the control circuit.

  g. Facilities in which relatively large motors are used have been exposed to the sometimes destructive
consequences of switching motors off and then back on again (even to the same bus), before the motor
residual voltage has decayed. The consequences of reconnecting a motor to a power source while motor
residual voltage is high – i.e., the motor rotating the substantial speed at the instant of reconnection – can
be extremely high inrush currents which lead to possible breaker tripping, motor damage, and/or coupling
damage. The damage is the result of the abnormal mechanical forces which can develop. The problem is
growing as more and more motors are being added to emergency and standby systems. The need to
understand the cause of high inrush currents and how to avoid them becomes apparent.

  h. Two types of loads, which may be termed passive and active, must be considered.

       (1) Passive loads include incandescent lamps, heaters, or any load that is predominately resistive.
These loads do not store electrical energy. When they are disconnected from a voltage source, the voltage
across the load drops to zero almost immediately.

       (2) Active loads include rotating electric motors. They store energy in their rotating mass and
magnetic fields. The instant the motor is disconnected, it acts as a self-excited generator that can deliver
substantial amounts of current because the magnetic flux within the air gap does not collapse

6-24


---

                                                                                                                                    TM 5-689

immediately. The resulting residual voltage decreases in amplitude exponentially. The length of time it
takes is determined by what is called the motor’s open circuit time constant. (One time constant is that
length of time it takes the residual voltage to fall to 37 percent of its initial amplitude.) Large motors can
have time constants of four to five seconds. Thus, when such a motor is disconnected, it will take four to
five seconds for its residual voltage to drop to 37 percent of its original value. It will take 20 to 25
seconds, or five time constants, for the residual voltage to go to zero.

       (3) In addition to the motors’ residual voltage decreasing, the relative phase angle between the
motor voltage and supply voltage changes. After the motor is disconnected, its mechanical speed starts to
decrease. This, plus the effect of slip (peculiar to induction type motors), causes an ever-increasing
change in relative phase between the motor’s residual voltage and the supply to which it is being
transferred. The motor is now acting as a self-excited generator of decreasing frequency that is coasting
in and out of synchronism at an ever-increasing rate until its residual voltage ultimately goes to zero.

  i. Out-of-phase transfer (or even reconnection to the same source) presents a problem. The electric
utilities have always been concerned with this problem of large motor load transfer and for obvious
reasons. But the problem of motor load transfer is not exclusive to utilities. The same situation is
becoming more apparent in general applications as electrical loads get larger. Mechanical loads like air
conditioners, ventilating fans, elevators, pumps, grinders, crushers, radar antennas, etc., are requiring
motors of higher and higher speeds and horsepower. This compounds the problem of motor transfer.
Electrical design engineers must be concerned with the design solutions to avoid the abnormal inrush
currents which the motor could develop upon reconnection.

  j. There are three basic solutions recommended for transferring motor loads without incurring
excessively high inrush currents.

       (1) One solution is to let the residual voltage across the motor be allowed to drop to zero value
where reconnection currents are similar to normal startup currents. This solution creates some problems.
For example, the motor must be disconnected until its residual voltage drops to where it can be safely
reconnected. The time that the motor must be disconnected is unacceptable in many applications.
Furthermore, the motor’s residual voltage versus time profile must be known so enough time is allowed
for the motor’s residual voltage to drop to a safe value. A reconnection voltage of 25 percent is generally
accepted as the maximum. However, if the motor were 180° out of phase with the reconnected source,
the maximum reapplied voltage would still be 125 percent. The maximum inrush current could be from
25 to 35 percent higher than normal, and the resulting stresses placed on the motor would be from 156 to
183 percent above normal. The manufacturer should be checked to see if the motor could take the 25
percent overvoltage when 180° out of phase.

       (2) A second method, overlap (closed transition) transfer with momentary paralleling of the two
power sources appears to be an ideal solution at first glance. An uninterrupted load transfer should
provide the least amount of system and process disturbance. However, overlap can only be achieved
when both power sources are present and properly synchronized by voltage, frequency, and phase angle.
In the case of a failing source, overlap transfer may be extremely difficult, if not impossible, to achieve.
Overlap transfer can only be used during test transfers and retransfer back from the generator to the utility
when both sources are at full voltage. While the overlap arrangement is technically feasible, it is not
always practical because of the reluctance of the utility companies to permit paralleling of extraneous
power sources to their lines.

       (3) In most applications a more practical solution is to use a conventional automatic transfer switch
with an in-phase monitor. This combination is the most popular with system designers and allows the
motor loads to be reconnected almost immediately without excessive inrush current. The in-phase

                                                                                                                                           6-25


---

TM 5-689

monitor, prior to transfer, samples the relative phase angle that exists between the source being
transferred to. Once the two voltages are within the required phase angle and approaching zero phase-
angle difference, the in-phase monitor signals the transfer switch to operate and reconnection takes place
close to synchronism.

            (a) With this arrangement, the asset of rapid transfer becomes evident. Also, it is not necessary
to know the residual voltage profile of the motors. In most cases, it will probably be high, but it will also
be almost in phase. The result is minimal or even non-existent electrical and mechanical shock; thus
avoiding unwanted breaker trip and mechanical damage. Furthermore, this result is accomplished without
altering the speed of the generator.

            (b) In addition to voltage and current ratings, it is also important to consider the operating
transfer time of automatic transfer switches used with in-phase monitors.

            (c) The operating transfer time of an automatic transfer switch is a primary factor in the proper
utilization of an in-phase monitor. For example, the advance angle adjustment of the in-phase monitor is
a direct function of the operating transfer time and the frequency difference between the two sources.
(For a given advance angle, the faster an automatic transfer switch can transfer, the wider the allowable
frequency difference.)

            (d) Consider a typical motor load in terms of its mechanical characteristics. Loads are either
high inertia or low inertia. High inertia loads include cooling tower fans, chiller motors, centrifugal
pumps and fans, centrifuges, rolling mill machinery, motor-generator (M-G) sets, etc. Low inertia loads
include rock crushers, conveyor belts, reciprocating pumps, compressors, etc.

            (e) The mechanical energy stored in the driven load is a contributing factor to the residual
voltage open-circuit time constant. Therefore, high inertia loads are more likely to have longer open-
circuit time constants than low inertia loads.

            (f) There is a need for in-phase transfer in many existing and proposed systems. For example,
there may be a need in an existing installation that has a history of trips on over-current, and/or damage to
motors and couplings.

            (g) The need for in-phase monitoring is usually determined by the size of the motor and the
inertia of the load. As a guideline, difficulties can be expected with motors of 50 horsepower or more,
especially if they constitute the only load on the transfer switch. High inertia loads tend to lengthen
residual voltage time constants. Still another consideration concerns the nature of the miscellaneous load,
other than the motor, connected to the transfer switch.

            (h) Dissipative loads reduce residual voltage times. However, capacitive loads used for power
factor correction have a tendency to increase open-circuit time constants since they provide additional
excitation to the motor’s stator windings.

            (i) Motor manufacturers will usually provide data regarding their motors’ residual voltage
time constants under varying degrees of load. However, several motors connected in parallel present
problems since it is somewhat difficult, if not impossible, to theoretically determine the resultant time
constant of the motor combination. This is so because the larger motors, upon disconnect, tend to drive
the smaller motors. Also, the indiv idual loads inertia interact upon one another. Here it is best to
empirically find the resultant time constant through the use of recording instruments in order to determine
the need for in-phase monitoring. The determination is a function of not only motor size, but also driven

6-26


---

                                                                                                                                    TM 5-689

load inertia and location of the motor in the distribution system with respect to the automatic transfer
switch.

  k. Another design accommodation to meet today’s needs is provision for proper ground-fault sensing.
Ground-fault sensing requires special consideration. This necessitates proper interfacing between various
Articles of the NEC.

       (1) Article 230-95 of the 1999 NEC states: “Ground-fault protection of equipment shall be
provided for solidly grounded wye electrical services of more than 150 volts to ground, but not exceeding
600 volts phase-to-phase for each service disconnecting means rated 1000 A or more.”

       (2) Article 445-1 of the 1999 NEC states: “Generators and their associated wiring and equipment
shall comply with applicable provisions of Articles 695, 700, 701, 702, and 705.”

       (3) Article 250-30 of the 1999 NEC defines the grounding requirements for a “separately derived
system.” A “separately derived system” is defined in Article 100 as follows. “A premises wiring system
whose power is derived from a battery, a solar photovoltaic system, or from a generator, transformer, or
converter windings , and that has no direct electrical connection, including a solidly grounded circuit
conductor, to supply conductors originating in another system.”

       (4) Article 250-24(a)(5) of the 1999 NEC states: “. . . A grounding connection shall not be made to
any grounded circuit conductor on the load side of the service disconnecting means except as otherwise
permitted in this article.”

       (5) Article 250-2 of the 1999NEC, defines the general requirements for grounding and bonding.

  l. These code requirements have a number of bearings on “Emergency Systems,” “Legally Required
Standby Systems,” and “Optional Standby Systems” as covered by Articles 700, 701, and 702 of the
NEC. Consider a 480Y/277 volt system with a three-pole transfer switch and zero sequence ground-fault
sensing. A preferred method for isolating the normal and emergency source neutrals is for the automatic
transfer switch to provide overlapping neutral transfer contacts. This arrangement also conforms to
Section 250-24(a) and provides continuity of the grounded neutral conductor, in accordance with Section
250-2, through utilization of overlapping neutral transfer contacts. This feature provides the necessary
isolation between neutrals, and, at the same time, minimizes abnormal voltages. By means of overlapping
contacts, the only time the neutrals of the normal and emergency power sources are connected together is
during transfer and retransfer. With a solenoid-operated, conventional double -throw transfer switch, this
duration can be less than the actuating time of the ground-fault sensor, thus avoiding false tripping due to
unbalance current that might result when using a solid neutral.

       (1) In addition to meeting code requirements, features of this arrangement include:

            (a) No flow of ground-fault current through neutral conductor that would detract from or
effectively reduce ground-fault detection.

            (b) No flow of unbalanced current through the generator neutral which would alter pickup of
ground-fault sensor and possibly cause nuisance breaker tripping.

            (c) The load neutral is always permanently connected to either source of power. There is no
momentary opening of the neutral conductor when the transfer switch operates.

                                                                                                                                           6-27


---

TM 5-689

            (d) Abnormal voltages and transient voltages are kept to a minimum, in that the neutral-to-
ground is not broken.

            (e) There is no erosion of the overlapping contacts due to arcing, thus maintaining the integrity
to carry current with minimum maintenance. The impedance of the neutral circuit does not change.

            (f) Conventional ground-fault detectors may be used on both normal and emergency sides.

            (g) Permits ground-fault sensing and alarm on the emergency side.

       (2) Four pole switches have also been satisfactorily applied where the loads are passive and
relatively balanced, providing complete isolation of service and generator neutral conductors. As with the
overlapping neutral contacts described above, this approach eliminates possible erroneous ground-fault
sensing and nuisance tripping caused by multiple neutral-to-ground connections and satisfies the NEC
definition of a separately derived system. However, unbalanced loads may cause abnormal voltages for
as long as 10 to 15 milliseconds when the neutral conductor is momentarily opened during load transfer.
Transfer switches are frequently called upon to operate during the total load imbalance caused by a
single-phasing condition. Inductive loads may cause additional high-transient voltages in the
microsecond range. Consequently, the contact of the fourth switch pole may interrupt neutral currents
causing arcing and contact erosion. The contact erosion can be minimized if the fourth pole is designed
to open last (after three other poles interrupt the load current) and make first without contact bounce. A
good maintenance program must reaffirm at intervals the integrity of the fourth pole as a current carrying
member with sufficiently low impedance. Both the NEC and Underwriters’ Laboratories (UL) recognize
the use of four-pole switches for three-phase, four-wire systems. In some countries, including Germany
and France, it is mandatory to use four-pole switching devices.

       (3) Automatic transfer switches that include full-phase protection have voltage sensor connected
across the line on single -phase, two-wire systems, and across the outside conductors on a single -phase,
three-wire system. On a three-phase, three- or four-wire system, each phase is monitored; therefore, three
voltage sensors are required.

       (4) There are cases where only two voltage sensors, connected between the three-phase
conductors, have been used to monitor the three phases. However, should one phase conductor open,
feedback through the load from the other two phase lines will maintain near full voltage on both voltage
sensors and neither will drop out.

       (5) Voltage sensors must be the voltage sensitive type since the release voltage of ordinary sensors
is generally less than 50 percent of normal voltage. Consider the single -phase, three-wire system under a
condition where a fuse has blown in one line. Any relay connected across the outside conductors will
have impressed across it one-half of the normal voltage due to feedback through the load. If the relay is
not the voltage sensitive type set to drop out above 50 percent voltage, transfer will not be affected.

       (6) Where the possibility exists that under open phase conditions (and this applies to both single -
phase and three-phase applications) terminal voltage will be sustained at a relatively high value due to
generator action of connected motors, voltage sensors having close differential between pickup and
dropout are required to detect this condition.

       (7) This possibility, as well as the characteristics of present-day lighting, computer
instrumentation, and other voltage sensitive loads, has been a contributing factor to the selection of
voltage sensors.

6-28


---

                                                                                                                                    TM 5-689

  m. Static transfer switches use SCRs to conduct current from source to load. These devices turn on
when gated, and turn off at the first current zero crossing following removal of the gate signal. The major
advantage of static transfer switches is fast transfer without source interconnection. The response to an
outage is, in the worst case, less than 8 milliseconds, provided the second source is available. Static
transfer SCR technology should be considered when an 8-millisecond outage is the maximum that can be
tolerated. It should be noted that most modern computer equipment can withstand a 20-millisecond
outage as described in the Information Technology Industry Council (ITI) Curve and Application Notes
(appendix B).

       (1) The SCRs require the semiconductor junctions to be forward biased. This results in a voltage
drop of approximately 1.5 volts per line (or 225 watts per phase in a 150 A switch). This power loss
generates considerable heat, which must be dissipated by fans. The fans run continuously, and over-
temperature sensors are usually required to set an alarm if there is a cooling malfunction. The switch may
not be able to support the load under an overtemperature condition and automatic bypassing may be
required to protect the SCRs.

       (2) Detection circuits are employed to prevent transfer if an SCR shorts (which would result in a
source-to-source connection). If a shorted SCR on the connected source is detected, the opposite source
breaker is shunt tripped as protection against a source-to-source connection and transfer to the alternate
source is inhibited. Similarly, if circuitry detects an open-phase SCR, the load is transferred to the
opposite source to restore power, providing the opposite source is available. Transfer back to the original
source is then inhibited.

       (3) Unlike the mechanical switch, the controller must be functioning, and providing continuous
gate pulses to the SCRs to keep them on or the static switch itself will cause the load to lose power.

  n. The hybrid solid-state transfer switch takes advantage of both static and mechanicalswitching
elements. It utilizes the best of each technology and virtually eliminates their shortcomings. A standard
electro-mechanical switch provides power to the load through mechanical contacts. The switch is
electrically operated and mechanically held. The reliability and cool operation of mechanically locked
contacts are maintained. SCRs are added to transfer to the opposite source with fast and precise timing.
The result is a transfer switch that meets all requirements of the ITI Curve (appendix B). Planned
transfers result in less than a 3-millisecond disruption to the load. An unanticipated loss of source
supplying the load will result in an unplanned transfer in less than 20 milliseconds without source-to-
source interconnection. The SCR conduction is limited to approximately 15 milliseconds during transfer,
and the mechanically locked contacts support load at all other times. This results in low voltage drop
across the contacts, and cool operation without requirement for fans or over-temperature alarms.

  o. Many users, local governing authorities, Federal agencies, electrical inspectors, etc., frequently
require that the transfer switch meet some form of minimum performance criteria before it is considered
acceptable. The performance criteria may vary depending on the degree of reliability and quality level
desired. Factors which involve the life of the equipment, such as ease of maintenance, fire safety, shock
hazards, overload, endurance, temperature rise, and ability to withstand available fault currents,
frequently receive consideration as measures of performance.

  p. Other organizations also have recognized the need and developed standards to satisfy specific
requirements. Such standards include IEEE Recommended Practice for Emergency and Standby Power
Systems, Standard 446-1995; IEEE Recommended Practice for Electric Power Systems in Commercial
Buildings, Standard 241-1990; NEMA Standard ICS 10-1993 Industrial Control and Systems: AC
Transfer Switch Equipment; CSA Standard C22.2 No. 107.1-95, General Use Power Supplies; and EGSA
100S-1996, Performance Standard for Transfer Switches for Use with Engine Generator Sets.

                                                                                                                                           6-29


---

TM 5-689

  q. Federal agencies, such as the Veterans Administration, General Services Administration, Federal
Aviation Administration, and Corps of Engineers have written stringent performance criteria requiring
certified tests which must be met before a transfer switch can be accepted. Other approving authorities
may simply require that the transfer switch be UL listed and labeled. UL has written a safety standard for
transfer switches. The standard is identified as UL 1008 and contains the criteria by which UL evaluates
a transfer switch for fire and shock hazards to determine if it meets the basic safety standards for a UL
listing. This standard has been written to embrace many manufacturers of transfer switches and,
therefore, defines only safety criteria. Each application should be carefully evaluated to determine the
acceptable quality and reliability levels in addition to UL’s safety requests. It may be necessary to specify
performance requirements above and beyond UL 1008 in order to obtain proper performance. For
example, UL’s test to withstand short circuit current requires an X/R ratio which may be exceeded in the
actual application.

  r. Special consideration should be given to systems that utilize adjustable frequency drives (AFDs) to
control motor operation. These electronic devices often consist of SCR assemblies to change the voltage
and frequency applied to the motor to vary its torque and speed.

       (1) With some AFDs, interruption of the input, be it caused by transfer switch operation or other
momentary power outages, causes the device to see a low voltage input. To maintain motor speed, some
control sensors immediately change the conduction angle of the controlling SCRs to compensate for the
low line condition. The result is that upon immediate reapplication of power, the controlling SCRs are
turned fully on causing a severe current inrush. This current inrush is of such a magnitude that protective
devices such as fuses can blow or worse yet, the SCRs themselves can be irreparably damaged.

       (2) This problem is only partly solved by conventional in-phase transfer or other load disconnect
arrangements because other extraneous interruptions of power (such as disturbances on the high lines)
will also confuse the AFD voltage sensing circuitry.

       (3) Some manufacturers of AFDs have recognized this problem and have included in their systems
special high-speed voltage sensing circuitry that detects momentary power outages and shuts down the
AFD entirely. Upon reapplication of voltage, the SCRs go from an off condition to a soft start current
limiting startup that automatically protects the solid-state switching devices.

       (4) When other provisions are lacking, the motor load disconnect control circuit previously
described (i.e., disconnect before transfer) can be considered for transfer of SCR controlled loads for AFD
motors and other loads such as used by communications companies. The contact, which must be
integrated by the AFD system manufacturer, simply signals the SCR control to “power down” before
transfer and permits a soft restart after transfer. As indicated above, such controls may protect the SCRs
during a power interruption when the transfer switch is operating, but offer no protection when the power
interruption is extraneous to the transfer switch.

6-7. Grounding standby power systems

Since the primary consideration in the installation of emergency and standby power systems is to satisfy
the need for continuity of electrical service, the type of system grounding that is employed, and the
arrangement of system and equipment grounding conductors, will affect the service continuity.
Grounding conductors and connections must be arranged so that objectionable stray neutral currents will
not exist and ground fault currents will flow in low impedance, predictable paths which will protect
personnel from electrical shock and assure proper operation of the circuit protective equipment.

6-30


---

                                                                                                                                    TM 5-689

  a. Where phase-to-neutral loads must be served, systems are required to be solidly grounded.
However, 600 volt and 480 volt systems may be high resistance grounded or ungrounded where a
grounded circuit conductor is not used to supply phase-to-neutral loads. High resistance grounded or
ungrounded systems may provide a higher degree of service continuity than solidly grounded systems.

  b. Where grounded (neutral) conductors are used as circuit conductors in systems that have emergency
or standby power supplies, the grounding arrangement must be carefully planned to avoid objectionable
stray currents. For example, stray neutral currents and ground-fault currents in unplanned, undefined
conducting paths may cause serious sensing errors by ground-fault protection equipment.

  c. A grounded (neutral) circuit conductor is permitted to be solidly connected (not switched) in the
transfer equipment. Therefore, a neutral conductor is permitted to be solidly interconnected between a
service-supplied normal source and an on-site generator which serves as an emergency or standby source.
Grounding connections to the grounded (neutral) conductor on the load side of the service disconnecting
means is not recommended, so the grounding connection to the generator neutral should not be made.

       (1) Such multiple grounding of the neutral circuit conductor may cause stray currents that are
likely to be objectionable and will cause ground-fault current to flow in paths that may adversely affect
the operation of ground-fault protection equipment. Grounding connection to the neutral conductor at the
on-site generator on the load side of the service disconnecting means is not recommended and may not
satisfy code requirements. Where the grounded (neutral) conductor is solidly connected (not switched) in
the transfer equipment, the system supplied by the on-site generator should not be considered as a
separately derived system.

       (2) The grounding connection to the neutral conductor at the on-site generator completes a
conducting path for stray neutral current. The magnitude of the stray current will be a function of the
relative impedances of the neutral current paths. Where ground fault protection is provided at the service
disconnecting means, the stray neutral current may adversely affect the operation of the ground fault
protection equipment.

       (3) The multiple grounding connections to the solidly interconnected neutral permit a portion of the
ground fault current returning to the normal source to flow through the neutral grounding bond at the on-
site generator and bypass the sensor for the ground fault protection at the service equipment. The main
service disconnecting means is not supposed to trip for a ground fault on a feeder or branch circuit, so this
is not a serious problem provided the feeder to the transfer switch does not have ground fault protection
equipment that is actuated by a ground fault current sensor. However, ground fault protection for feeders
may be required if the service disconnecting means is equipped with ground fault protection.

  d. Where ground fault protection is applied to a feeder from the service equipment to the transfer
equipment, the ground fault current may not be accurately detected by a zero sequence ground fault
current sensor.

       (1) The multiple grounding connections to the solidly interconnected neutral permit a portion of the
ground fault current returning to the on-site generator to pass through the sensor for the ground fault
protection at the service equipment. This arrangement could result in tripping the service disconnecting
means by ground fault current supplies from the on-site generator.

       (2) The transfer switch may have an additional pole for switching the neutral conductor, or the
neutral may be transferred by make-before-break overlapping neutral contacts in the transfer switch.
Where the neutral circuit conductor is transferred by the transfer equipment, an emergency or standby
system supplied by an on-site generator is a separately derived system. A separately derived system with

                                                                                                                                           6-31


---

TM 5-689

a neutral circuit conductor should be solidly grounded at or ahead of the system disconnecting means.
The neutral conductor between the service equipment and the on-site generator is completely isolated by
the transfer switch and is solidly grounded at the service equipment and at the on-site generator. Where
the neutral circuit conductor is switched by the transfer equipment, the stray neutral current paths and the
undesirable ground fault current paths are eliminated.

       (3) The normal supply and the alternate supply are equivalent to two separate radial systems
because all of the circuit conductors from both supplies are switched by the transfer switch. Since both
systems are completely isolated from each other and are solidly grounded, ground fault sensing and
protection can be applied to the circuits of the normal source and the emergency or standby source as it is
applied in a single radial system.

  e. Unintentional neutral grounds will cause stray neutral currents that may be objectionable.
Therefore, in addition to carefully planning the intentional grounding connections, systems should be kept
free of unintentional grounds on the neutral circuit conductors.

       (1) Where there are two on-site generators connected for parallel operation, the neutral conductor
is grounded at the generator switchgear instead of at the generator. Where the generator switchgear is
adjacent to the generators, the grounding connections may be made in the generator switchgear.

       (2) Switching of the neutral conductor permits grounding of the neutral at the generator location.
This may be desirable for the following reasons.

            (a) An engine-generator set is often remotely located from the grounded utility service
entrance, and the ground potentials of the two locations may not be the same.

            (b) Good engineering practice requires the automatic transfer switch to be located as close to
the load as possible to provide maximum protection against cable or equipment failures within the
facility. The distance of cable between incoming service and the transfer switch and then to the engine-
generator set may be substantial. Should complete cable failure occur with the neutral conductor not
grounded at the generator location, the load would be transferred to an ungrounded emergency power
system. This could jeopardize emergency service continuity and possibly lead to additional failures.
Concurrent failure of equipment (breakdown between line and equipment ground) after transfer to
emergency power may not be detected. Thus the generator frame may approach line potential, causing a
substantial voltage difference between the generator frame and the neutral conductor.

            (c) Some local codes require ground fault protection while the engine-generator is operating.
This may present a sensing problem if the neutral conductor of the generator is not connected to a
grounding electrode at the generator site and proper isolation of neutrals is not provided.

            (d) When the transfer switch is in the emergency position, other problems may occur if the
engine-generator set is not properly grounded. A ground fault condition could cause nuisance tripping of
the normal source circuit breaker even though load current is not flowing through the breaker.
Furthermore, both the normal neutral conductor and the emergency neutral conductor would be
simultaneously vulnerable to the same ground fault current. Thus a single fault could jeopardize power to
critical loads even though both utility and emergency power are available. Such a condition may be in
violation of codes requiring independent wiring and separate emergency feeders.

  f. Where a transferable load is supplied by a system that is derived from an on-site isolating
transformer and the transfer equipment is ahead of the transformer, a grounded (neutral) circuit conductor
is not required from either the normal or alternate supply to the transformer primary.

6-32


---

                                                                                                                                    TM 5-689

       (1) The isolating transformer permits phase-to-neutral transferable loads to be supplied without a
grounded (neutral) circuit conductor in the feeders to the transfer switch.

       (2) The system supplied by the isolating transformer is a separately derived system, and if it is
required to be solidly grounded, it should be grounded in accordance with code requirements. The neutral
circuit conductor for the transferable load is supplied from the secondary of the isolating transformer.

  g. If the on-site generator is rated 480Y/277V or 600Y/347V, its neutral may not need to be solidly
grounded because the neutral is not used as a circuit conductor. Therefore, the type of system grounding
for such a generator is optional. However, the generator frame should be solidly grounded whether its
neutral is ungrounded, high resistance grounded, or solidly grounded.

  h. In ground fault current return paths where the grounded (neutral) circuit conductor of a transferable
load is isolated by a transformer, any stray neutral current or ground fault current on the secondary of the
isolating transformer will have no effect on ground fault protection equipment at the service equipment or
at the generator.

  i. Where the grounded (neutral) circuit conductor is solidly connected (not switched) in the transfer
equipment, an emergency or standby system supplied by an on-site generator should not be considered a
separately derived system. The solidly interconnected grounded (neutral) conductor need only to be
grounded at the service equipment.

       (1) The solidly interconnected neutral conductor is grounded at the service equipment only and
there are no conducting paths for stray neutral currents. If the generator is not adjacent to the service
equipment, the generator frame should be connected to a grounding electrode such as effectively
grounded building steel.

       (2) Where the solidly interconnected neutral conductor is grounded at the service equipment only ,
the ground fault current return path from the transferable load to the on-site generator is through the
equipment grounding conductor from the transfer switch to the service equipment, thence through the
main bonding jumper in the service equipment and the neutral conductor from the service equipment to
the generator.

  j. The ground fault current might trip the service disconnecting means even though the ground fault is
on a circuit supplied by the generator. A signal could be derived from a ground fault sensor on the
generator neutral conductor to block the ground fault protection equipment at the service in case of
ground faults while the system is transferred to the generator. Such blocking signals require careful
analysis to ensure proper functioning of the ground fault protection equipment.

  k. If the neutral conductor between the service equipment and the transfer switch is intentionally or
accidentally disconnected, the generator will be ungrounded. Therefore, the integrity of the neutral
conductor must be maintained from the service equipment to the transfer switch while the load is
transferred to the generator. The equipment grounding conductor must also be maintained from the
servic e equipment to the transfer equipment in order to provide a ground fault current return path from the
transferable load to the generator.

  l. For increased reliability, multiple transfer switches, located close to the loads, are often used rather
than one transfer switch for the entire load. Therefore, consideration should be given to the possibility of
cable or equipment failure between the service equipment and the transfer switches, thus possibly causing
an ungrounded emergency or standby power system.

                                                                                                                                           6-33


---

TM 5-689

  m. Three-phase, three-wire, 480 volt and 600 volt systems, which are used prevalently, do not require
the use of grounded conductors as circuit conductors. There are more system grounding options where
emergency and standby power systems do not require a grounded circuit conductor to supply phase-to-
neutral loads.

  n. In many installations the service to the premises will be solidly grounded, three-phase, four-wire
where a grounded (neutral) circuit conductor is not required for loads that are provided with an on-site
emergency or standby supply. An on-site emergency or standby supply is not always required to have the
same type of system grounding as the normal supply to the premises.

  o. The generator supplies a three-phase, three-wire system. If the generator is rated 480Y/277V or
600Y/347V, it need not be solidly grounded because its neutral is not used as a circuit conductor.
An on-site generator that is not required to be solidly grounded may be high resistance grounded or
ungrounded. A high resistance grounded or ungrounded emergency or standby power supply provides a
high degree of service continuity because the circuit protective equipment will not be tripped by the first
ground fault on the system. If the generator is solidly grounded, it must be grounded at or ahead of the
generator disconnecting means.

  p. Interlocked circuit breakers are used as the transfer means. Where a grounded (neutral) circuit
conductor is not required, the type of transfer equipment that is employed is not a consideration in
selecting the type of system grounding for the emergency or standby supply.

  q. Interlocked circuit breakers should not be selected as a transfer means without considering
additional means to isolate the normal and alternate circuit conductors and equipment for maintenance
work. The overall reliability of a system may be reduced due to additional exposure where the circuit
conductors from the normal supply are solidly connected to the circuit conductors from the emergency or
standby supply. The circuit wiring for an emergency system should be kept entirely independent of all
other wiring or equipment except in transfer switches or in junction boxes and in fixtures for exit and
emergency lighting.

  r. A 480 volt or 600 volt, three-phase, three-wire, on-site generator that is high resistance grounded
may serve as an emergency or standby power supply for a three-phase, three-wire system that is normally
supplied by a solidly grounded service.

  s. Where the three-phase, three-wire critical load is relatively large compared with loads that require a
grounded (neutral) circuit conductor, a high resistance grounded emergency or standby power supply is
sometimes considered. This arrangement requires an on-site transformer for loads that require a neutral
circuit conductor. If an on-site transformer is provided for emergency lighting, it must be supplied from
the normal service and the emergency supply through automatic transfer equipment.

  t. The supply transformer for the normal service and the on-site generator are both high resistance
grounded. There are no provisions to supply phase-to-neutral loads.

  u. The ground fault current return path to the on-site generator is completed through the grounding
resistor. The grounding resistor limits the line-to-ground fault current to a magnitude that can be tolerated
for a time, allowing the ground fault to be located and removed from the system.

  v. High resistance grounded systems should not be used unless they are equipped with ground fault
indicators or alarms, or both, and qualified persons are available to quickly locate and remove ground
faults. If ground faults are not promptly removed, the service reliability will be reduced.

6-34


---

           TM 5-689

CHAPTER 7
LIGHTNING

7-1. Lightning effects on power systems

The frequency of thunderstorms is important in the protection of power systems. The frequency of
occurrence of strokes to transmission lines and open country is an indication of the exposure to lightning
that an electric power system experiences.

  a. An isokeraunic map published by the National Weather Service, which indicates the annual number
of thunderstorm days; that is, the number of days on which the weather observer hears thunder or either
cloud-to-cloud or cloud-to-ground lightning is useful in planning lightning protection. Using an
isokeraunic level of 30 as a reference, an analysis of several thousand measurements made of lightning
strokes to transmission lines indicates that a line with a single, 100-foot high ground wire collects 100
strokes per 100 miles per year. A similar line with two overhead ground wires receives more strokes
since it collects strokes in a wider swath. The total number of strokes to a line tends to increase with
increasing height and decrease with decreasing height.

       (1) Knowing the number of strokes to the above transmission lines, we can calculate the number of
strokes per unit area (density) by first determining the swath in which a line collects strokes. Again,
based on an isokeraunic of 30, the density is 13.7 strokes per square mile per year.

       (2) The number of strokes to transmission lines or open ground is assumed to vary directly with
isokeraunic . The isokeraunic or storm days do not necessarily reflect the actual number of strokes to
earth, however, since a single clap of thunder or a series of thunderstorms lasting several hours would
both be counted as one storm day. Thus, the number of strokes to earth can vary widely for a given
isokeraunic .

  b. In designing lightning protection for power systems, how lightning enters the system, both by direct
strokes and by induced surges from nearby strokes; the propagation of surges within the system; and the
effects of these surge voltages and currents on the circuits and apparatus within the system must be
considered.

       (1) Lightning surges entering a power system through direct strokes are the primary concern in
planning surge protection. These strokes may hit phase conductors directly , or they may strike the
overhead ground wires or masts that shield the conductors. In either case, it is necessary to understand
the associated surge currents and voltages produced before a protection system can be designed.

       (2) A lightning stroke terminating directly on phase conductors or equipment terminals develops a
very high voltage, which, with no surge protection, will flash over the insulation in the majority of cases.
If the flashover occurs through air or across porcelain insulation, it rarely causes permanent damage. If,
on the other hand, the flashover occurs through solid insulation such as in a transformer or cable,
permanent damage results.

  c. The magnitude of surge voltages applied to equipment and line insulation systems can be limited by
providing grounding masts or ground wires to intercept direct strokes. Even with a shielding network,

           7-1


---

TM 5-689

though, there is some chance of flashover, depending on stroke current magnitude, impedance of the
shielding system, and the amount of insulation between the network and the energized circuits.

  d. A lightning stroke terminating near a transmission line can induce a voltage in the circuit which
seldom exceeds 500 kV. Lines, shielded with overhead ground wires and operating at 69 kV and above,
generally have sufficient insulation to prevent flashover by voltages in this range. The same applies to
some well insulated 34.5 kV lines. Lower voltage lines, however, with insulation levels appreciably
below 500 kV, may be flashed over by induced surges. In most cases, these circuits do not have ground
wires, and are, therefore, subject to flashover each time they are contacted by a direct stroke. In general,
flashovers by induced surges do not create a significant problem since the number of flashovers from
direct strokes far exceeds those from induced strokes.

  e. A lightning stroke terminating on a power system initiates traveling waves which propagate within
the system. To determine the resulting surge voltages and currents in various parts of the system, a
traveling wave analysis is required. Simple networks with linear impedances can be analyzed manually;
more complicated networks, characteristic of practical power systems, require analog or digital computer
analysis.

       (1) First, consider a stroke terminating on the phase conductor of a transmission line. The stroke
initiates voltage and current waves traveling at the speed of light in each direction from the terminating
point. With a linear impedance, voltage and current have the same waveshape.

       (2) The traveling waves are represented by the equation:

  e = iZ

  e and i are the voltage and current, respectively, of the traveling wave. Z is the conductor surge
impedance.

       (3) Surge impedance is circuit impedance as seen by a transient such as lightning. For an open-
wire conductor:

  Z = L/C
  L = inductance/unit length
  C = shunt capacitance to ground/unit length

       (4) A typical surge impedance for a line conductor is 400 ohms. Corresponding values for L and C
would be 0.4 H/feet and 2.5 pF/feet, respectively.

       (5) Assuming that the stroke current, I, is equal to 2i (that is, the stroke current divides equally at
the terminating point), the conductor voltage for a 10,000 A stroke is:

  e = IZ
            2

       = 10,000 A x 400 ohms
                2

       = 2,000 kV

Thus, a traveling wave current of 5,000 A (I/2) generates 2,000 kV on the transmission line.

7-2


---

                                                                                                                                    TM 5-689

       (6) The traveling waves initiated by the stroke continue to propagate along the line until a
discontinuity is encountered. At this point, voltage and current waves are reflected back along the line,
and at the same time, traveling waves are transmitted beyond the point of discontinuity. Points of
discontinuity may be an open circuit breaker, a transformer, another connected line, or a flashover on the
line.

            (a) To a lightning surge, a transformer appears as a capacitance of 2,000 to 3,0000 power
factor, and behaves essentially as an open circuit. As the traveling voltage wave encounters an open
circuit, a voltage wave of the same magnitude and polarity as the incoming surge is reflected. The
incoming and reflected waves combine, resulting in double the traveling wave voltage (2e) at the open
circuit or transformer termination. This is the well known phenomenon of voltage doubling at the end of
a line.

            (b) For an open circuit termination, the reflected current wave has the same magnitude as, but
opposite polarity to, the incoming wave, resulting in zero current at the open end of a line.

            (c) Now consider a line terminated in a perfect short circuit. The incoming and reflected
voltage waves have the same magnitude and opposite polarity resulting in zero voltage at the terminal.
The current waves have equal magnitude and the same polarity, resulting in double the traveling wave
current (2I). This is the well known phenomenon of traveling wave current doubling when it encounters a
short circuit.

            (d) An arrester discharging a current at the end of a line is a close approximation to the short
circuit case, since the arrester resistance is very low compared with the line surge impedance. The current
which the arrester must discharge, therefore, is nearly double the line traveling wave current. This is an
important concept in considering arrester discharge duty from lightning surges.

       (7) Another useful concept which can be calculated simply is the determination of the surge
voltage in a substation with any number of connected lines.

            (a) The substation voltage can be written:

  E = 2e
           n

  e = incoming traveling wave voltage
  n = total number of connected lines including that on which the surge originated

  Assuming an incoming voltage of one per unit (p.u.),

  E = 2, 1, 0.67, and 0.5 p.u. for one, two, three, and four connected lines, respectively

            (b) This simple calculation illustrates the advantages of multiple lines in reducing surge
voltage in a substation.

            (c) As noted previously, typical surge impedance for a phase conductor is 400 ohms. Some
other typical values are:

  Overhead ground wire – 450 to 500 ohms
  Two overhead ground wires (in parallel) – 350 ohms

                                                                                                                                             7-3


---

TM 5-689

  Steel transmission tower – 200 ohms
  Cables – 15 to 40 ohms

            (d) The propagation velocity in each of these elements is essentially that of light, with the
exception of cables in which propagation velocity is about 50 percent of that of light, depending on the
dielectric constant of the insulating material. These values are useful in representing power systems in
detailed traveling wave analysis using analog or digital computer methods.

  f. In protecting power systems against lightning, surge voltages and currents must be considered. In
general, lightning protection is primarily concerned with surge voltages; surge currents cause less
concern. A lightning stroke to a power system develops very high surge voltages across equipment and
line insulation systems. If these voltages exceed the insulation strength, a flashover occurs. A flashover
through air or over porcelain insulation (commonly used for transmission line insulation) does not usually
produce permanent damage. In generators, transformers, or motors, however, where solid insulating
materials are used, a flashover results in permanent damage.

  g. Once lightning enters a power system, the surge current is unlikely to cause any damage. Although
the current may be extremely high, it is very short lived and can easily be handled by a small conductor.
The largest recorded conductor to be fused or vaporized by a direct stroke was a No. 10 AWG . The size
of conductors, installed expressly for conducting lightning currents, is usually determined by mechanical
strength considerations, rather than by current-carrying capacity. On some rare occasions overhead
ground wires have been severed by lightning at the point of contact. This is probably due to the stroke
channel heating the conductor at the point of impingement, rather than from simply conducting the
lightning current.

7-2. Principles of protection

It has been shown that a modest lightning stroke of 10,000 A develops a 2,000 kV voltage when it
terminates on the phase conductor of a transmission line. Obviously, lines and equipment cannot be
insulated to withstand voltages in this range. A more practical alternative is to limit voltages to a much
lower level. This involves two basic principles: the use of masts and overhead ground wires to shield
equipment and circuits from direct strokes; and the application of arresters to limit surge voltages to levels
well below practical equipment insulation levels.

  a. Shielding masts are commonly used in substations and overhead ground wires are used in both
substations and on transmission lines. Both use the lightning rod princ iple. The following calculation
illustrates how a well-grounded mast limits the surge voltage magnitude.

       (1) Consider a mast grounded through a 5 ohm resistance and receiving a 10,000 A stroke.

  Voltage developed = 10,000 A x 5ohms
                             = 50 kV

       (2) The voltage at the top of the mast may be somewhat higher since our calculation ignores
inductive drop. However, this voltage is significantly less than the 2,000 kV that would be developed for
the same stroke on a conductor. Grounded masts and grounded wires, then, offer an important reduction
in the magnitude of surge voltages.

  b. Even with an effective shielding system, the surge voltages to allow for voltages developed by
strokes to the shielding network must be limited to magnitudes consistent with practical and economical
equipment insulation levels. On rare occasions strokes may also bypass the shielding system and

7-4


---

                                                                                                                                    TM 5-689

terminate directly on the energized circuits. For these situations, an arrester is used to control and limit
surge voltages to a safe level. The arrester, applied on or near the terminals of the protected equipment, is
connected from phase to ground. Under normal operating conditions, the arrester has no effect on the
power system. Under surge conditions, the arrester will spark over and conduct the surge current to
ground, limiting the voltage applied to the equipment insulation to a safe level. After conducting the
surge current to ground, the arrester will interrupt the power-follow current and restore itself to its normal
operating conditions.

7-3. Lightning protection systems

Modern offices and other facilities furnished with computer equipment and other sensitive electronic
devices demand effective lightning protection to assure reliable operation. Surges in the power system
induced by a lightning stroke can cause equipment malfunction or the introduction of false data or
commands. Also, lightning-generated electrical energy levels are extremely high and can cause
significant damage to electronic components. Such damage can occur when the equipment is turned off,
and in some instances, even when it is disconnected from the power receptacle.

  a. When lightning strikes a power line, there is a zone extending to each side of the actual stroke
where the lightning voltage may greatly exceed the insulation level of the line, and flashover to ground
will occur instantaneously. Simultaneously, traveling waves are generated in the conductors on either
side of the strike point. These traveling waves have two components: voltage and current. The voltage
magnitude is equal to the current magnitude multiplied by the surge impedance of the line and less than
the flashover voltage of the system insulation. These surges travel along the overhead line at about 1000
feet per microsecond (the speed of light). Research shows that a lightning stroke produces more energy
than has previously been considered possible. A typical lightning stroke carries nearly 3000 million kW
at approximately 125 million volts and an average current of over 20,000 A.

       (1) A typical lightning surge has an extremely steep wave front, which means that its voltage is
rising at the rate of millions of volts per microsecond. The steep wave front is followed by a short wave
tall, which means that after crest voltage is reached, surge voltage diminishes to half crest value in about
50 microseconds and completely dissipates in 100 to 200 microseconds.

       (2) The development, testing, and correlation of insulation with lightning protective devices has
been facilitated by adoption of a standard 1.2 x 50 voltage wave as representative of impulse surges. In
the 1.2 x 50 microseconds wave, crest is reached in 1.2 microseconds, and the wave decays to half crest in
50 microseconds.

       (3) High-voltage testing laboratories have developed surge generators that can simulate lightning
strokes. Not only have the 1.2 x 50 microseconds waves been produced, but the generators can also
produce the steeper-front waves with which arresters are tested for front-of-wave sparkover (as specified
by standards).

       (4) While lightning is usually considered synonymous with extremely high voltage, it is the current
component in the lightning stroke that is the measure of its effect on a stricken object. The instant a
voltage-sensitive device such as a surge arrester sparks over, it becomes a current-carrying path or
relatively low impedance for the duration of the surge discharge. Major segments of the arrester’s
protective characteristics are determined by its performance in discharging the surge current.

       (5) Elaborate scientific investigations have been made to measure and record lightning stroke
currents. A wide range has been reported, varying from lows of 1000 A to highs of more than 200,000 A,
emphasizing the unpredictability of lightning.

                                                                                                                                             7-5


---

TM 5-689

       (6) Overvoltage surge protection for power lines and equipment can be devised by using arresters
or by a combination of shielding and arresters. Because of the unpredictable nature of the lightning
phenomena, engineering analyses are based on statistical data, and reasonable service continuity can
usually be assured through correlation of scientific investigations, available weather records, such as
isokeraunic maps, and appropriate protective equipment.

  b. To provide the most effective safeguard, a lightning-protection system must be appropriate for the
type of structure and its construction characteristics. Three protection systems are available and each
should be considered:

       (1) A conduction system has been in use for many years.

       (2) An attraction technique has recently been gaining popularity.

       (3) A dissipation system is another new method available.

       (4) Other factors that must be considered in providing lightning protection for sensitive equipment
include making sure that all parts that carry a lightning electrical discharge are located far away from
items being protected. Extensive design data and installation guidelines for lightning-protection systems
are provided in National Fire Protection Association (NFPA) 780-1997, “Standard for the Installation of
Lightning Protection Systems;” the Underwriters’ Laboratories (UL) 96A “Master Label Code;” and the
Lightning Protection Institute’s (LPI) LPI-175 “Installation Code.” Isokeraunic maps also provide
essential information on lightning frequencies.

  c. The oldest and most commonly used protection method is the conduction system, sometimes
termed as the Franklin Rod or Faraday Cage system.

       (1) Air terminals (lightning rods) on the structure roof are connected to a grid of interconnecting
(coursing) conductors, which connect to down conductors that extend down to earth and connect to
appropriate grounding electrodes. The grounding electrodes can be individual ground rods or a
conductive ring buried around the building perimeter or both.

       (2) All system components are made of copper, anodized aluminum, or stainless steel.

       (3) To complete the conventional lightning-protection system installation, all metallic elements
(roof fans, vents, etc.), grounded or isolated, which are located on the roof or in the exterior walls near the
down conductors, must be bonded to the down conductors because the possibility of a sideflash exists. A
sideflash is an arc caused by a difference in potential between a down conductor and a metallic element.
The bonding eliminates potential difference and prevents high current flow from damaging these
components.

       (4) Recent changes in standard guidelines have redefined the outline of the zone protected by any
one standard air terminal. Originally, the accepted standard indicated that the area protected was defined
by a 60° cone starting at the tip of the air terminal, surrounding the terminal, and extending to earth,
without regarding the terminal height. Now, however, research and better data define the protected zone
as an area under an arc that has a maximum radius of 150 feet and is tangent to the earth while touching
the tip of an air terminal.

       (5) This is important for structures exceeding 150 feet in height because additional air terminals
must be installed at an appropriate intermediate level, as well as at roof level.

7-6


---

                                                                                                                                    TM 5-689

       (6) Other protection requirements for high-rise buildings include the electrical interconnection of
the steel column components or installation of conductive loops around the building at vertical intervals
not exceeding 60 feet. A bonding conductive loop must also be made at ground level and at roof level.
Furthermore, all grounded building elements (roof fans, vents, etc.) within 12 feet of the main roof must
be connected to the protection system. Also, buildings over 75 feet high must use larger system
components per the requirements of the Lightning Protection Code, NFPA 780-1997.

  d. The lightning attraction system pulls a lightning stroke to a grounding point located away from the
building or the sensitive equipment area. This system uses a spherical/saucer-shaped air terminal (in
place of a Franklin lightning rod) and a low-impedance grounding path using components similar to those
used with a standard conduction system.

       (1) When a storm is in the area, the spherical/saucer terminal generates an ion streamer that attracts
and creates a path for a lightning discharge to follow. The strength of the ionized path produced by the
attraction device increases as a charged cloud moves closer. The lightning discharge then occurs at the
attraction device location rather than at the structure housing sensitive equipment. It is important that the
path to ground have the lowest impedance possible so that the high currents involved can be handled
safely.

       (2) Two terminal designs are in use: one uses radioactive isotopes to initiate the ion streamer; the
other has a patented ion-initiator design that does not require the radioactive isotope. Both systems have
successful track records proven by hundreds of installations.

       (3) This system using the ion-type terminal has been successfully tested in U. S. labs where 95
percent of discharges tested were attracted away from conventional rods by these terminals.

  e. The third lightning-protection method used is a dissipation system. These installations rely on
many small metallic points to create a massive ionized field that continually discharges the electrical field
created by the storm. In the area around the dissipater, the field never reaches the lightning flashover
point. Dissipation devices come in a variety of configurations, yet the operating principle is the same.
Each point discharges a small amount of the potential difference between the cloud and earth. This action
creates a continuous low level current flow, and as a result prevents a lightning strike from occurring.
Thousands of these installations have proven to be successful. The committee for NFPA 780 is
considering a wording change that will allow dissipation systems to be installed under their standards.

  f. To provide effective protection, it is of utmost importance that these three systems have a low-
impedance path to ground. This applies to all components and connections from the air terminals to the
grounding electrodes. Low impedance is essential so that the huge currents involved will follow the
design path in preference to alternative paths offered by building materials such as wood, brick, tile,
stone, or concrete. When lightning follows these higher impedance paths, extensive damage may be
caused by the heat and mechanical forces generated during the passage of the lightning discharge.

       (1) A low-impedance path reduces the potential difference between the storm system, the earth,
and the protection to the point where a stroke does not occur or at least is somewhat controlled. Even
with installations built on solid rock, an extensive low-impedance ground electrode/system is required, as
well as solid connections between components and earth. Standards do not call out a specific ohmic
ground value; however, every effort must be made to obtain the lowest value possible.

       (2) A number of techniques can be used to lower earth resistance or provide an effective grounding
network, as described in NFPA 780. Two additional effective methods for reducing earth resistance are
achieved using chemical soil conditioning.

                                                                                                                                             7-7


---

TM 5-689

       (3) Where the soil is of a high-resistance composition, calcium or sodium chloride has historic ally
been buried with the grounding electrodes to increase conductivity. However, with this technique, the
conductor and the salt usually require replacement every few years. To reduce the labor and expense
required to make this replacement, a chemically filled rod has been developed.

       (4) A second ground conductivity enhancer is a plastic -like material that is poured over the
grounding electrode system before it is buried. This enhancement technique reduces the potential
difference between the electrical system grounding path, the building structure, and the earth.

  g. Interconnecting conductors are as important as other components. Tests in high-voltage
laboratories demonstrate that a steep voltage wave front, such as created by lightning, causes the surge
impedance in conventional conductors to increase to the point that side-flashes occur. Installation of
multiple grounding conductors for buildings and a roof grid system creating a Faraday Cage reduces the
magnitude of current flow in any one conductor. However, sideflashes can still occur.

       (1) Standard down conductors are usually large bare copper or aluminum stranded conductors that
are constructed particularly for the lightning-protection industry. A recent advancement is a coaxial cable
that reduces the surge impedance as well as flashover. However, this cable is more costly than other
conventional conductors.

       (2) The most effective lightning-protection system can be selected after a study of the isokeraunic
(lightning frequency for the area), and an evaluation of the structure/site characteristics. Isokeeraunic
maps and related data are available from NFPA 780.

       (3) A computerized program has been developed that predicts site vulnerability, building area
susceptibility, and the magnitude of the possible stroke. Typical inputs to the program are structure
height, site height above sea level, storm probability from area records, and the building configuration.
From this data, the probability, location, and magnitude of a strike on the building can be determined.
The program’s accuracy has been as statistically accurate as the input data. Using this approach, the best-
suited protection system can be installed, and sensitive equipment can be located away from strike-prone
areas.

  h. Other methods are used to protect equipment from lightning damage. For example, over
transmission lines, substations, or high towers, a protective shielding cable sometimes called a “skywire”
is installed. It is a well-grounded bare conductor, usually mounted several feet above the conductors or
equipment to be protected. When lightning strikes in the vicinity, induced voltage surges tend to be
carried by the shielding skywire instead of the protected conductors or equipment. Lightning arresters
and surge protectors are also used to provide protection. These devices, which should be UL listed,
prevent lightning induced currents and switching surges from entering the electrical and
distribution/voice/data system. These protective devices are connected between the protected system
conductor and ground. Normally, they see an abnormally high voltage, such as would be caused by a
lightning stroke, their resistance breaks down, carrying any high currents to ground. After the danger is
over, normal high resistance is restored.

7-8


---

              TM 5-689

   CHAPTER 8
INSTALLATION

8-1. Objectives of an automated data processing (ADP) system

The objective of an ADP system is to provide accurate, reliable, and continuous data. This objective can
only be achieved through the careful and intelligent design of all aspects of the complete ADP system.
The purpose of this chapter is to ensure that the installation of the system is performed in such a manner
that a continuous trouble -free service is achieved. Initial site preparation and proper installation
procedures can prevent many of these related problems. Other power related problems can only be
remedied through the proper use of the proper power line conditioning devices.

  a. Environmental conditions play a major part in insuring that computer systems operate at maximum
efficiency. Proper temperature control becomes very important. Variations in temperature lead to
component thermal shock, resulting in excessive downtime. High particulate counts in the atmosphere
contaminate and cause problems. Corrosives have short- and long-term adverse effects. Vibration in
heavy industrial areas and 40-story plus buildings must be observed and considered. Radio frequency
interference (RFI) must be detected and prevented, as is the case with electrostatic discharge (ESD).

  b. The personnel responsible for the design, installation, startup, maintenance, and operation of an
ADP system must possess a high degree of knowledge in many seemingly unrelated fields. They not only
must have a wide ranging technical ability but must also have a background in bid documents and
interpreting specifications.

8-2. Contract bidding

The general philosophy of the contract bidding process is one of competition. Originally the idea was to
give everyone a fair chance to compete for contracts but with competitive bidding to keep the vendors
honest and provide the lowest price possible. The procurement methodologies grew around this
conception and were designed to produce open and honest competition for all purchases.

  a. It soon became apparent that finding the lowest bidder was neither appropriate nor practical for all
procurements. There are many cases where it was absolutely necessary for an executive decision to
determine which bidder was truly capable of providing the required product or services that would fulfill
the client specifications in an acceptable manner. Experience demonstrates that in many cases the product
or services of the low bidder may be simply unacceptable.

  b. The specifications that are furnished to the bidders are the technical requirements of the end
product and also as important, these specifications become the legal framework of a contract between
vendor and client. The bidders are provided a detailed description of what must be supplied and are
cautioned to bid realistically because their product must pass the scrutiny of inspectors that are
knowledgeable and expert in their fields. The bidder must be aware that failure to fulfill the terms of the
specifications may result in rejection of the product. Under these circumstances the contractor offering
the lowest bid to produce that which has been clearly specified is awarded the contract.

              8-1


---

TM 5-689

  c. Throughout the installation of an ADP system it is absolutely mandatory that the inspectors and
engineers assigned to the project become familiar, proficient, and expert in understanding the bid
specifications and the construction specifications.

  d. The ADP manufacturer must submit in its proposal an item-by-item detailed compliance statement
to all requirements of these specifications as well as complete floor plans, one-line diagrams, bill of
materials, and all the data requested in the various parts of these specifications. The requested data
should be presented on the specification compliance forms in the proposal. One-line diagrams must
specify type, frame, and trip ratings of all circuit breakers. Floor plans shall identify all proposed
equipment with weights, dimensions, access, and cooling requirements. Presentation of equipment not in
full compliance to this specification must not relieve the successful bidder from meeting all requirements
of this specification at no extra cost to the owner after the award of contract.

  e. In the event of discrepancies between the drawings/attachments and the technical specifications, the
technical specifications shall take precedence.

  f. Off loading, setting in place, installation, interconnection cables, hardware, lugs, and testing of all
equipment specified are to be the responsibility of the contractor including any and all associated labor,
parts, tools, and equipment.

  g. The final acceptance is to be made after the equipment has been adjusted and has demonstrated (site
acceptance test) that it fulfills the requirements of the specifications and the supplier has furnished all
required test documents in accordance with the specified testing procedures.

8-3. Inspection requirements

Installation inspection may be listed under the very broad heading of construction management. The
inspector has the responsibility of being the eyes and ears on site throughout installation and should
possess skills in many disciplines of engineering and construction. It is strictly the responsibility of the
installation inspection individual or team to make certain that he receives the opportunity to evaluate all
factors throughout an installation. The inspector must carefully determine the requirements and present
appropriate and valid information to the other members of the construction management team.

  a. The ultimate and final responsibility for a completed, one-line installation will rest upon a single
agency or with an individual within that agency. The responsibility of the personnel performing startup
inspections and verifying the compliance of the completed system with the specifications cannot be
overemphasized.

  b. Although there is considerable similarity in the design of all electrical apparatus associated with an
ADP installation, there can be extreme variations in design tolerances, mechanical and electrical settings,
and other physical characteristics.

  c. Many quality features are now built into equipment, some of which add to the apparatus cost,
principally because the manufacturer must protect his product from abuse and failure in normal use. Even
though a system has been properly engineered and quality apparatus of the specified rating has been
purchased, the equipment will ultimately experience premature failure if the proper installation and
startup procedures are not adhered to. Reliability can be built into a system but proper installation is the
key factor in initiating a proper equipment life cycle.

8-2


---

                                                                                                                                    TM 5-689

  d. Many unknown and sometimes hazardous conditions are discovered through installation
inspections. At times a simple and apparently minor adjustment can be made during installation which if
found in time may benefit both client and vendor.

  e. From the viewpoint of economics, the inspection process cannot and must not be allowed to
degenerate into complacency. Assumptions cannot and must not be tolerated, and one must not assume
the vendor or contractor possesses all of the necessary experience to complete a successful installation. It
is the responsibility and duty of the purchaser and user to ensure that all equipment is installed so as to
fulfill the concept of the design and to produce a reliable finished product.

  f. The inspector or inspection team must make certain to continue to develop his expertise to enable
him to carry out the responsibilities assigned to him. Inspection personnel must be able to work closely
with both vendor and with those in authority within his own organization. The need for attention to detail
cannot be over emphasized. In summary, it is the inspection staff that will carry the responsibility for
maintaining a high standard of construction and start up of any project.

8-4. Ground system installation inspections

The earth ground system is a direct conducting connection to the earth or a body of water serving as a low
impedance path to earth for the purpose of establishing an earth reference for the X0 terminal on the
secondary of a transformer and for the purpose of providing a low impedance path for the discharge of
lightning. The National Electrical Code (NEC) requires that the resistance to ground (earthing
impedance) be less than 25 ohms (NEC Article 250-56). The grounding electrode conductor must be
minimum No. 8 AWG copper or as shown in Table 250-66 of the NEC. The earthing impedance for a
computer quality installation should be le ss than 5 ohms, and the earthing conductors should be the same
AWG size as the supply conductors connected to the transformer secondary. The earthing electrode
should penetrate the earth to a depth of 8 feet below the frost line and the earthing conductor must be
connected to the earthing electrode with either cad-weld, silver solder, or a terminal block clamp located
below ground level. Use of a saddle clamp is unacceptable as it will loosen with age, freezing, thawing,
etc.

  a. Doubling the diameter of an earthing electrode will decrease earth impedance by 10 percent, while
doubling the length of a ground rod will decrease earth impedance by up to 40 percent. The most cost-
effective and common method, however, is generally multiple electrodes. A technique of multiple
electrodes spaced a minimum of 6 feet apart is the most effective. When the existing service entrance
electrode cannot be measured (not able to shut building down), a second electrode should be driven 6 feet
from the service entrance electrode. If earth impedance of the new electrode is less than standard, the
service entrance electrode and the new electrode should be tied together with the same size conductor as
used to connect the original electrode to the service entrance. If the second electrode impedance is above
standard, drive a third electrode. Tie these two electrodes together with the same AWG wire used to the
service entrance (No. 8 AWG minimum). Measure the impedance to earth. Continue this process,
encircling the original electrode, until the standard is achieved. Then tie earthing electrodes to the
original electrode as above. New electrical grounding test equipment is now available that can measure
the ground resistance without disconnection of the earthing electrode and shutting the building down.

  b. There is a difference between a neutral (grounded conductor) and ground (grounding conductor).
The neutral carries current back to the source (transformer). A separate non-current carrying grounding
conductor is also required to meet the NEC requirements for safety. This equipment grounding conductor
is required to bond equipment frames to ground and to carry any fault currents to insure circuit breaker
trips under fault conditions. On delta connected systems always insure that a separate ground wire is run
to bond equipment frames to ground. Additionally, a separate, full-sized, non-current carrying, insulated

                                                                                                                                             8-3


---

TM 5-689

conductor (back to the transformer earthing electrode) may be required to provide a zero volt system
reference point for ADP equipment (see paragraph 4-6). This single point grounding conductor is used to
connect the ADP equipment signal ground to the electrical service entrance point and is required by the
NEC.

8-5. Neutral junction installation inspections

Neutral is the junction point on a wye circuit or the center tap on a split-phase circuit. The neutral
conductor provides the return path for current from the load to the supplying transformer. The neutral
conductor is connected to the grounding electrode system by a grounding electrode conductor. This
connection may be made at any location between the source terminals (typically a transformer or
generator) and the first disconnecting means or overcurrent device. The neutral is then bonded to the
equipment grounding conductors at this same point.

  a. The neutral wire cannot be used for safety grounding. In the NEC, the neutral is referred to as the
grounded conductor, while the safety ground is referred to as the grounding conductor. The grounding
conductor (green wire) is the non-current carrying conductor (Section 250-26 of the NEC) and should
carry zero current, except for any ground fault currents and for the discharge of static electricity.
Underwriters’ Laboratories (UL) approved or listed equipment does not cause current to flow in the
ground conductor. The neutral conductor may never be connected to the grounding conductor in any
circuit breaker panel except the main entrance panel (Section 250-24). The neutral conductor should
never contact conduit or circuit panel cases. Connecting the neutral to ground in breaker panels causes
the ground to operate as another neutral. This violates the code and is a safety hazard and can be a
primary contributor to ground potential differences in a building.

  b. The only place ground and neutral can deliberately be tied together is at the building entrance
distribution panel and on the secondary of any distribution transformer, including isolation transformers.

8-6. Safety ground installation inspections

Grounding accomplishes several purposes and safety considerations must take precedent whenever there
is a conflict of interest. The task to be accomplished is to make the installation as safe as possible and at
the same time satisfy all practical requirements for noise emission and susceptibility. The three basic
purposes of grounding are safety, logic reference, and shielding. Safety falls into the categories of
limiting “touch” voltage and providing a return path for fault current to ground. Logic reference provides
a zero volt system reference for power supplies and shielding protects the electronics from high frequency
noise.

  a. Safety ground is an alternate path for the return of fault current for the purpose of interrupting
(tripping) the branch circuit breaker and for establishing a point of reference to X0 terminal of the
transformer. This conductor should be sized with the ability to handle the appropriate current to permit
tripping the branch circuit breaker in the event of a fault. The impedance from any outlet to the
transformer X0 terminal shall not exceed 2 ohms at 120 volts ac, 1 ohm for 240 volts ac, 0.5 ohm for 480
volts ac, etc. A clamp-on ammeter on the ground conductor should read near zero. Any reading in excess
of 0.2 A should be cause for concern and the reason for this excess current should be found and
eliminated. Earth ground and safety ground should touch only at the X0 terminal.

  b. Any fault or leakage between an ungrounded conductor and a grounded enclosure will produce
fault current. Leakage current may be harmlessly drained away, but a short circuit current must be
promptly terminated by protective fuses or circuit breakers. The same devices which protect against line-
to-line or line-to-neutral faults also protect against line-to-ground faults. Therefore, the ground return

8-4


---

                                                                                                                                    TM 5-689

path must have a low enough impedance so as not to limit the fault current to a value that will prevent
prompt tripping of the protective device. The electrically continuous conduit and equipment ground
conductor must be connected directly to the neutral of the power source at the building entrance neutral-
ground bond. This is at a secondary of a transformer, output of a motor-generator (M-G), or at the
building entrance service equipment if no isolating transformer is interposed.

  c. The connection between the conduit or enclosure safety ground and neutral must not permit fault
current to flow through a separate connection between the enclosure and a driven earth or other qualified
ground connection. If fault currents have to pass through two driven earth stakes or rods, the resistance of
these earth grounds would prevent many circuit breakers from tripping. A very low ground resistance for
a driven earth ground might be 5 ohms (25 ohms is often acceptable). Two such earth grounds in series
would be 10 ohms and when in series with a 120 volt ground fault would allow only 12 A of current to
flow. This is not enough current to trip the lowest circuit breaker rating in common use, a 15 A breaker.

  d. To ensure prompt operation, a circuit breaker must see from five to ten times its rated current.
Ground path impedance between the fault point and the connection to neutral, plus all other circuit
impedances, should not exceed 0.8 ohm for a 15 A circuit breaker (to meet a times ten criteria). For a 150
A circuit, this would be 0.08 ohms maximum. It is clear that driven earthing rods cannot meet this
requirement, but direct wiring connections can.

  e. Connecting some equipment to one ground rod and other equipment to a separate ground rod is a
violation of the NEC and will create noise currents and voltages between the two rods. These ground
loop currents result in noise on computers and other electronic systems and their interconnecting data
cables.

  f. The predominant type of grounding in Europe and the United Kingdom is the “TN” system. Like
the method used predominantly in the United States and Canada, this scheme uses a grounded power
source with the frame of the load grounded directly through a separate safety ground conductor to the
neutral at the power source.

  g. The ground conductors connect equipment frames to safety ground and to each other to limit the
voltage that can be present on the frame of a product to a safe level to protect personnel. The voltage
difference between the ends of a safety ground conductor should never exceed a fraction of a volt at
power frequencies (50 or 60 hertz) except during a fault to ground condition and then only until a
protective circuit element (circuit breaker or fuse) can interrupt the power from the source. Such a ground
fault might be the result of either an insulation or component failure in the equipment or a failure in the
conductors supplying power. The conduit and grounding conductors are not intended to carry any portion
of the load current. They are to carry only fault currents, leakage currents, and noise currents.

  h. At power frequencies, 30 volts root mean square (RMS) is commonly specified as an upper limit
for “safe” voltages. A momentary excursion above this dur ing the time it takes for a fuse or circuit
breaker to clear a fault is not considered a significant hazard.

  i. At higher frequencies and with short duration impulses, the human body can tolerate much higher
voltages and currents than at power frequencie s. This is fortunate because as frequency content increases,
the voltage drop for a given leakage or noise current also increases. High frequency and impulse voltage
signals of 150 to 200 volts appear regularly on ground conductors associated with 120 volt circuits. Their
duration, however, is usually measured in microseconds and they cannot normally be detected by touch.

  j. The most important consideration for computer reliability and operation, as well as other electronic
systems is a simple point ground reference within its environment. The computer system’s reliability will

                                                                                                                                             8-5


---

TM 5-689

be enhanced by using this technique. The building service entrance should be the initial reference for the
single point ground system or even more desirable is the reference for the computer system’s treatment
device.

8-7. Inspecting for unbalanced loads

High or “noisy” neutral-to-ground readings can indicate a poor power balance between loads. Improperly
balanced loads will cause excessive neutral current to flow, resulting in a voltage drop across the neutral
conductor. Balancing the loads should reduce this current/voltage and if it does not, the neutral-to-ground
bond should be checked, and the grounding conductor size and insulation verified. Where the major
portion of the load consists of electric discharge lighting, data processing, or similar equipment, there will
be harmonic currents present in the neutral.

8-8. Utility power systems installation inspections

American utility companies attempt to maintain electrical power within certain tolerances. See Section 2-
2.b. for a discussion of typical values.

  a. In addition to the voltage and frequency tolerances allowed by the utility supplying the ADP
system, there are six basic power line problems to be considered when inspecting an ADP installation.

       (1) No voltage (loss of power) is very easy to detect. No instrumentation is required, only
attempting to turn on the lights or some piece of equipment. Causes can range from downed power lines
to failed transformers, to tripped circuit breakers, etc. These power outages may last for a short one-half
cycle of the 60 hertz sinewave (8.3 milliseconds) or for several hours. Most are no longer than a few
seconds.

       (2) High or low voltages/amplitude changes in the sinewave can be detected with a voltmeter or a
voltage recorder. Causes may be power lines, distribution panels, and/or the wiring being too heavily
loaded. In addition, being too close to the source of the power or too far from the source of power can
cause large voltage fluctuations, as well as starting or stopping heavy motor loads, non-uniform loading
of poly-phase transformers, or poor regulation. If these conditions continue for more than 8.3
milliseconds, but less than 2 seconds they are high or low voltage line conditions, often referred to as
high-average or low-average line voltage.

        (3) Harmonic distortion refers to sinewave misshaping caused by harmonics (multiples) of the

primary frequency. When 60 hertz power is generated, inherently all the odd harmonic frequencies (180

hertz,  300  hertz,  420  hertz,  etc.)  are  generated  but  only  the    rd    th  and    th  normally  have  sufficient

                                                                         3,    5,         7

amplitude to be of concern. Generally, these are so small as to go undetected except with very

sophisticated equipment. Flat-topping of the sinewave, as seen on an oscilloscope, is the first indication

of harmonic distortion. Causes may range from overloading or improper loading of transformers, faulty

regulation transformers, fluorescent or other electric -discharge lighting, to data processing equipment.

       (4) Noise is normally detected as bad or faulty data and is investigated with an oscilloscope.
Oscilloscopes are used to detect and analyze high frequency events or even to analyze the 60 hertz power
sinewave. Noise is a low voltage, low current, high frequency signal riding on the 60 hertz sinewave and
is characterized by having a repeatable frequency pattern, one that can be determined and analyzed.
Generally it is electromagnetic interference (EMI) and is caused by having the power or data lines or the
equipment too close to a source of EMI; a large motor or transformer for instance. Improper grounds or
grounding can also be a cause. Noise can also be RFI if a radio tower or transmitter is located nearby.

8-6


---

                                                                                                                                    TM 5-689

       (5) Transients or impulses are high voltage, high-current, fast bursts of energy riding on the 60
hertz sinewave. They also exhibit a non-repeatable frequency pattern even when resulting from the same
repeated event. They exhibit extremely fast rise times (1 microsecond to peak) and last for less than 8.3
milliseconds, usually decaying to 50 percent of peak value in 1 millisecond or less. Because they have no
repeatable frequency pattern and are random in occurrence, they are extremely difficult to detect. Power
line analyzers must be used to detect the presence of transients although the first indication of their
existence is usually data errors, computer crashes, and damaged circuitry. Microprocessor based
equipment is very susceptible to damage from these anomalies. Transients occur whenever the current
through any inductive load (motors, transformers, coils of any kind) is changed at a rapid rate. The result
is a voltage impulse that follows the equation, -E = L di/dt. This rapid change in current is the result of
switching actions, sudden power outages, and applications of power. Transients are also induced on
power and data lines by nearby lightning strikes or have data lines too close to power lines that are being
switched.

       (6) Finally, the sixth of these anomalies and the most common one is any combination of the
above. While any of these problems can and do occur by themselves, the more general rule is for them to
occur in combinations. Transients always accompany voltage outages. High or low voltages may result in
noise when power supplies are put under the strain of having to work at input voltage levels outside their
design limits.

8-9. RFI inspections

RFI is any emission of electromagnetic (EM) energy having an undesirable effect on other electronic
equipment. As electronic data processing equipment has become more sophisticated and dependence on
the continued on-line operation of this equipment has grown, the effects of RFI have become more
prevalent.

  a. Although RFI of sufficient levels can adversely affect most electronic circuitry, among the most
susceptible are disc drive positioning circuits and plotter mechanisms. As little as 1.0 volt/meter can be
harmful to this equipment. The necessary sensitivity of these circuits make them susceptible to extremely
low level interference unless they are adequately shielded. Due to the necessity for special
instrumentation to detect EM radiation and its possible presence in practically any location or
environment, it is imperative that RFI susceptibility specifications for all ADP equipment be published by
the manufacturer and that an RFI survey be included in all site preparation surveys for proposed systems
locations.

  b. Regardless of location, urban or rural, industrial or residentia l, sources of RFI abound. Some of the
more prevalent sources of RFI are:

       (1) Radio transmitters

       (2) Radar transmitters

       (3) Aircraft navigational equipment

       (4) Microwave ovens

       (5) Automobile ignition systems

       (6) Induction ovens

                                                                                                                                             8-7


---

TM 5-689

       (7) Diathermy equipment

       (8) Relay operated equipment

       (9) Electric motors

       (10) Radio receivers

       (11) Television receivers

       (12) Furnaces

       (13) Home appliances

       (14) Switching contacts

       (15) Other electronic equipment

  c. These devices can appear at any time before or after the installation of ADP systems, without any
noticeable change to the environment, adding to the subtlety of failures induced by the effects of
undersized EM radiation. A survey for RFI presence may save considerable time and duress when
troubleshooting recurring intermittents and failures without apparent cause.

  d. A survey of the vicinity will reveal a transmitting tower, or a check with occupants in nearby
facilities will indicate other interference problems. In any case, a survey utilizing appropriate
instrumentation is recommended when interference is suspected.

  e. Many commercially available instruments can be utilized in performing the survey. Field strength
meters, electronic field sensors, spectrum analyzers, and the electronic oscilloscope are most common.
The spectrum analyzer is the most sensitive and accurate device to locate the presence and identify the
source of RFI. Tuning the spectrum analyzer over the band will indicate the relative levels of radiation as
well as its frequency. A portable electronic field sensor should be used to check for areas of increased or
decreased field strengths once the source has been identified.

  f. To begin a survey, first make a plan drawing of the location indicating all windows, doors,
furniture, and equipment. Near the affected equipment, set up a spectrum analyzer and record all
frequencies indicated with their respective power levels. Using the portable electronic field sensor,
observe the field strength present at the affected equipment and record the reading in volts per meter on
the respective location of your plan drawing. Now record several readings within the location using the
portable sensor.

       (1) Record the field strength outside the building on each side and try to identify the source of any
interference by noting the direction of strongest readings.

       (2) Compare all recorded field strengths to the published equipment specifications and note any
readings that are excessive.

       (3) Should you not have the necessary instrumentation, and the interference is from a radio or
television broadcast station, the following method may be used to determine field strength.

            (a) Obtain the station’s radiated power from the station engineer.

8-8


---

                                                                                                                                    TM 5-689

            (b) To determine the approximate field strength use the formula:

                                                                                                     1/2

                                                E = (30Pt) volts/meter
                                                          d

       Where: E = field strength in RMS volts/meter
                Pt = transmitted power in watts
                d = distance from isotropic antenna in meters

This calculation does not account for any insertion loss resulting from walls, buildings, etc.

       (4) If it is suspected that interference is occurring sporadically or only at various times, a strip
recorder can be connected to the E field sensor and left to record field strength over several days.

  g. The methods chosen to eliminate RFI problems will depend on the physical characteristics of the
site as well as the field strength present. Some interference problems may be corrected by simply
providing a separate grounding connection to the frame or case of the affected equipment or moving
equipment to another room. More serious cases may require the purchase or construction of a completely
shielded enclosure incorporating filtered power and shielded ventilation.

  h. In some cases, it is recommended that all walls, ceiling, floor, doors, and windows be shielded.
The shielding material should be bonded at all seams to ensure maximum effectiveness of the shielding.
The shielding material should then be connected to a good earth ground. This treatment can provide as
much as 80 decibels (dB) attenuation at 100 megahertz (MHz), when door sealing and ventilation duct
shielding have been provided. Attenuation by 80 dB will reduce field strengths to one ten-thousandth of
their former levels.

  i. RFI problems are primarily solved with Faraday Shielding and special window glass like that used
in microwave ovens. When shielding of the entire room is required, run a No. 12 AWG bare copper wire
around the bottom of the shield, solder it to the shield, solder the shield together and reference the shield
to the transformer ground (X0). An RFI detector reading of one-half (1/2) volt per square meter to 1 volt
per square meter is the maximum allowable.

  j. Never place electronic equipment closer than 3 feet to fluorescent lighting due to the RFI radiation
from the lamps.

8-10. ESD inspection

ESD is a transfer of charge between bodies of differing electrostatic potentials. The term ESD event also
includes both EM fields and corona effects before and during a discharge. The ESD event may include
significant electric (E) and magnetic (H) field phenomena due to current flow. ESD phenomena thus
includes EM field generation over a broad range of frequencies, from dc to the low gigahertz region.

  a. One of the subjects may be fabricated electronic equipment or subassemblies. This subject is
generally at local electrostatic ground potential. The second body, usually in the role of an intruder, is
often a human; but it may be any mobile object such as a wheeled chair, an equipment cart, a vacuum
cleaner, etc. The victim may also be affected by the EM fields generated by a discharge between an
intruder and a third mass which is not itself the subject.

                                                                                                                                             8-9


---

TM 5-689

  b. Static electrification refers to all processes which produce segregation of positive and negative
electrical charges by mechanical action. These processes operate by contact between two surfaces with
subsequent separation.

  c. The most common charging mechanism is frictional or tribo-electrification. This mechanism
involves electron or even ion transfer upon contact due to the frictional localized heating of microscopic
contact between solid surfaces. The localized microscopic zones are fluidized, leading to increased
charge mobility. Accumulation of charges can occur if the relaxation time or charge decay is long due to
low conductivity values.

  d. The distinction between a conducting and a non-conducting object is based on its surface resistance
in ohms-per-square centimeter. A non-conductive object cannot be discharged by grounding points on its
surface. The electrostatic charge that can be developed between two materials is a function of their
relative position in the tribo-electric series. The term tribo-electric derives from the Greek “tribos”
meaning to rub. Hence, tribo-electric is the generation of static charge by rubbing.

  e. Everyday actions can develop large electrostatic potentials due to static charging. As a typical
example, walking across a synthetic fiber carpet on a relatively dry day (30 percent relative humidity) can
easily develop an electrostatic potential of 20 kV or more. The floor need not be carpeted. Walking
across many present day floor coverings can also produce an electrostatic charge. Waxing the floor may
worsen the situation, adding to the electrostatic charge that may be developed. Simple movement of the
body within clothing can also develop large static potentials. At 15 percent relative humidity, walking 20
feet on a vinyl floor, the human is charged to 12 kV, whereas at 80 percent relative humidity, the human
is only charged to 1.5 kV. Walking on a carpet at 15 percent relative humidity, the human can charge to
35 kV.

  f. The minimum voltage necessary for a person to detect an electrostatic discharge is approximately
300 volts. However, sufficient energy may be contained in electrostatic discharges that are below the
threshold of human perception to cause damage to electronic equipment. The maximum potentials that
may be routinely developed via electrostatic charging ranges from 1 to 10 kV. Given the proper
conditions, potentials may reach 20 to 25 kV. Corona effects, which bleed off charge, limit maximum
electrostatic potentials to 35 to 40 kV. The electrostatic potential difference that exists between two
charged objects, or between a charged and uncharged object, may be viewed or modeled as existing
between two plates of a charged capacitor. In the extreme case, human body electrostatic discharges may
contain energy levels as great at 400 millijoules for voltages of 40 kV and a capacitance of 300 picofarads
(pF).

  g. Damage to equipment caused by electrostatic discharge can be minimized by placing grounded
static discharge mats in areas where movable furniture (chairs, file racks, etc.) or pedestrian traffic can
discharge into a sensitive component. Personnel working on sensitive equipment may need to be
continuously grounded through a wrist strap. Equipment used in the maintenance of sensitive
components should be grounded and special manufacturer maintenance procedures must be followed.

8-11. ADP system environment inspections

Computers and other ADP devices along with their peripheral equipment have very precise environmental
tolerance limits. Therefore, the precise control of temperature, humidity, and particulate contamination is
critical to their proper operation.

  a. The ideal computer room environment is critical.

8-10


---

                                                                                                                                    TM 5-689

       (1) Temperature should be adjustable from 65°F to 80°F but shall optimally be set at 72°F and not
vary more than ±1°F from that setting. The temperature should not vary by more than 10°F anywhere in
the room. Variations of the component temperatures, with time, causes flexing of the components,
component leads, printed circuit boards, connectors, etc. Every time a junction or connection is flexed it
is stressed and every time it is stressed it deteriorates.

       (2) Humidity is also critical and shall be controlled within ±2.5 percent R.H. over an operating
range adjustable from 45 to 55 percent R. H. The ideal setting is 55 percent (±5 percent) as there are
minimum static problems at 55 percent relative humidity. Humidification is the only way to control
static.

       (3) The only acceptable form of humidification is with pure steam humidifie rs designed for
computer room environmental control. These offer the highest efficiency and lowest maintenance and the
steam is distilled. Never use cold mist humidifiers that release water-born contaminates into the computer
room atmosphere. Wet bulb humidifiers with heating elements require continual cleaning of sludge tanks
to keep them efficient. Evaporative and infrared methods can release corrosive salts, excessive humidity,
and mineral contaminates directly into the computer room environment, eventually leading to computer
system failures.

  b. To help execute these parameters, the computer room should be constructed with wall insulation
rated R-19 or better; floors and ceilings should also be insulated. All windows should be thermopane.
All outside windows should have sunscreens and all glass above the 12th floor should be Faraday
shielded. Airflow from the air conditioner should be designed to provide the maximum amount of mixing
possible from the discharge to the return. Discharge should not be directly into the equipment to prevent
thermal shock to components when air conditioner operates on and off. Equipment should be laid out to
avoid creating any air dams; i.e., equipment in a line should have a minimum open spacing between
individual products of 8 inches, and particulate producing equipment such as printers should be placed
closest to the cold air return in the product lineup.

  c. The computer room air conditioner should run almost all of the time to eliminate temperature
cycling. Ethylene glycol coolant is best suited for meeting this requirement because it uses a smooth
running turbine compressor, it can be easily regulated, and has a heat transfer 1 to 1.6 times that of water,
depending upon the ratio of water to ethylene glycol. However, to use ethylene glycol, a 243-hour chilled
water loop is required. If ethylene glycol cannot be used, then use freon. However, freon cannot be
throttled and will result in more frequent temperature cycling.

       (1) The advanced A-frame air-conditioner arrangement with cross-circuited cooling coils
connected to two separate refrigeration systems under electronic sequencing control provides greater
sensitivity in cooling and dehumidification. Greater surface area and lower velocity air offers quiet,
efficient cooling with less turbulence. This system enables 60 percent cooling to continue during
servicing of one of the refrigeration systems.

       (2) The air-conditioning unit should have an electric resistance heater sized to offset the sensible
cooling capacity in the dehumidification mode. The reheat element should be of low-watt density, tubular
construction with a no-corrosive metal sheath. The electric reheat should be three-phase system identical,
to prevent the possibility of uneven phase balance. The reheat element should be electrically and
thermally protected in accordance with UL requirements. Both heating and cooling functions should have
automatic step starting with time delay to minimize power line requirements. Temperature and humidity
sensors should be solid-state devices to ensure accurate system control and high reliability.

                                                                                                                                           8-11


---

TM 5-689

       (3) When evaluating the air-conditioning system it is desirable to have a high coolant pressure
differential across the compressor, but, a high delta P across the evaporator causes freezing and is an
indication that either the dryer is dirty or the airflow over the evaporator is insufficient. A check of feeder
line amperage gives a good indication of the continuing health of the air conditioner. A drop in current
from previous readings indicates a loss of freon.

  d. Computer room air must be filtered to 15 microns or less. The newer disc drives require 10 micron
filtration. Electronic filters must be equipped with Faraday shielding, have internal water jets for wash-
down cleaning and address smoke, hydrocarbons, and particulates. Air supply shafts must have Faraday
shielding because spark gap precipitators generate frequencies in the gigahertz range. Particulate count
must be less than 150 parts per liter, chlorine count less than 10 parts per billion, and sulfur count below
10 parts per billion.

8-12. Pre-site inspection

Computers and other electronic systems are often adversely affected by the environment in which they are
located and expected to function. Variations in temperature will stress solder joints and contact points
due to the variations in the expansion and contraction characteristics of the different materials involved;
i.e., fiberglass, plastic, metals, etc. If the humidity is too low, static becomes a problem; too high, and
things begin to grow. Chemicals in the air can corrode and airborne particulates can be conductive or
abrasive and affect circuit boards and the operation of electronics, as do externally generated voltage
impulse transients and noise.

  a. To optimize operation, all of the above areas must be considered and dealt with and the problems
eliminated. Ideally, this should be done prior to the installation of the computer or electronic system.
Practically, however, these areas are very often not properly addressed until after installation and the
equipment operation begins to suffer, thus causing attention. Whether addressed prior to or after
installation, the physical steps taken to insure the best possible site preparation should be nearly the same.

  b. Begin a pre-site inspection several miles from the site and always involve as many of the following
personnel as possible – the salesman who sold the equipment, the data processing manager, maintenance
manager, building contractor, air-conditioning contractor, and electrical contractor. Within a five-mile
radius of the site, note the general terrain, other industries in the area and their types, antennas,
transmission lines, etc. Determine whether the power is brought into the facility underground or
overhead. Note everything, even the prevailing winds. When arriving at the site, view the building from
all sides and especially from the roof.

8-13. Pre -inspection for electrical systems

Perform the electrical inspections with the electrical contractor or the electrician. Start at the building’s
main service entrance.

  a. Find and verify the earthing electrode installation.

  b. At the transformer, check for any contamination, corrosion, or leakage; check the transformer
temperature and insulation and the cooling fans, if any.

  c. Follow the power to the ADP or electronics room. Check all transformers as above. Observe all
aluminum terminals for correct connections and connection integrity (listen and smell).

  d. Measure and record currents and voltages at each transformer and in the distribution panels.

8-12


---

                                                                                                                                    TM 5-689

  e. Check and record voltage across each circuit breaker and the current on each breaker.

  f. Check all neutral and ground wires for current.

  g. Verify the neutral and ground busses to be insulated and isolated. Verify that the voltage between
the neutral and ground is no more than 0.2 volt RMS (1-2 volts peak to peak as measured on an
oscilloscope).

  h. Check primary and secondary bus voltages and check for any ground to neutral voltages. Verify
voltages and current and that the system is balanced. Check that wire sizes and breaker sizes are
compatible.

  i. Verify that there is a neutral wire for each circuit breaker in the distribution panel; i.e., the same
number of neutrals as there are circuit breakers.

  j. If the ADP equipment is not yet in place, verify that it can be unloaded at the dock and moved to
the final destination with a minimal risk of damage. Verify that equipment can be properly stored to
protect it from the elements prior to installation. Verify proper clearances, stairways, elevators, door
widths, heights, etc., so the equipment can be transported to its final location without fear of damage.

8-14. ADP room inspection

Inspect the computer or electronics room where the equipment is, or will be, located. The ac power for
this equipment should be supplied from a transformer dedicated for this purpose and located as close as
possible to this room. This transformer, and any isolation transformer, must have the secondary neutral
solidly grounded. If the ac specifications for the equipment cannot be met, a line treatment device will
also be required. All receptacles in this room should be the isolated ground type.

  a. The computer (electronics) room should not be a passage area; i.e., no convenient pathway from
one area to another area. It should have a raised floor, minimum height 6 inches, with ramps rather than
stairs into the room and be vinyl covered. Wash the computer room floors with Ivory soap and wet mop
only. Use no ammonia (chlorine) and the floor should be one piece vinyl. Seal all masonry and have no
glass or carpets on the walls.

  b. Raised floor posts must be painted, galvanized, or cad-plated to prevent rust. Permit no roller
chairs in the room to prevent electrostatic discharge problems. All floor supports should also be
grounded. This ground should be a “dirty ground” back to the isolation transformer X0. It is not to be
connected to neutral or computer ground except at the transformer X0. This ground can be used for
grounding of non-electrical items such as static mats, etc.

8-15. Air-conditioning system inspection

The room should have its own air-conditioning system. The air conditioner should be dust free.
Electronic filtering is the optimum. The air conditioner should provide positive air pressure in the room
to help keep out outside contaminants. There should be no corrosives in the room. Possible corrosives
include ammonia, hydrocarbons, hydrogen sulfide, nitrates, oxides or nitrogen, oxidants, and sulfur
dioxide. Room temperature should not vary more than 10°F from hottest to coldest spot anywhere in the
room and the overall temperature should not vary more than 10°F per hour. This can best be attained by
using a chilled water coolant system rather than freon, as chilled water systems are easier to throttle,
meaning less “on and off” operations. Humidity should be between 50 and 60 percent at all times.

                                                                                                                                           8-13


---

TM 5-689

Equipment should not be positioned in a manner to create air dams. Provide a minimum of 8 inches
clearance between any side-by-side devices. Note the intake and exhaust vents; they should be located to
allow maximum air mixing in the room. If there are outside windows exposed to sunlight, some type of
correction will be required to shade the windows.

8-16. Lighting system inspection

Lighting should be from 55 to 72 candlepower throughout the room, with the backs of all equipment

receiving equal or greater lighting from the fronts. Place no equipment closer than 3 feet to any

fluorescent lighting to prevent RFI radiation problems. It is more than likely that the fluorescent fixtures

in a large business complex will be powered from a three-phase, four-wire system. Fluorescent lighting

systems  are  non-linear  loads     and,  therefore,  are  generators  of    rd  harmonic  currents.  The recently

                                                                           3

developed electronic ballast consumes less power but has the decided disadvantage of injecting even

higher  levels  of    rd  harmonic  current  into  a  power  distribution  system.  It is essential that the special

                    3

characteristics of these non-linear loads be understood to prevent the failure or disturbance to critical

systems. Every part of the room must have telephone access through additional telephone jacks or long

telephone cords.

8-17. Fire safety inspection

If fire safety is provided through a sprinkler system, a means should be provided to automatically
disconnect the computer or electronics power when the sprinkler is activated. Due to restrictions on the
emission of chloro-fluorinated hydrocarbons (CFC) to the atmosphere, Halon systems are being phased
out. The next generation of clean agent fire suppression systems uses environmentally friendly products
such as FM-200, a compound of carbon, fluorine, and hydrogen, that is odorless, colorless, electrically
non-conductive, non-corrosive and leaves no residue when discharged. Since FM-200 is discharged as a
gaseous vapor, it is able to penetrate enclosures and reach areas that water or dry chemical agents cannot.
A fast response, automatic fire detection system is commonly installed to activate the suppression system
and limit both fire and smoke damage. In most cases, photoelectric smoke detectors will be used due to
the high airflow conditions found in ADP facilities. Careful attention must be paid to airflow rate and
how it impacts detector spacing. Aspirating (air sampling) smoke detection systems may also be installed
in some facilities to allow detection during the fire's incipient stages.

8-18. Total evaluation

During the first site preparation walk-through, all the above information should be recorded, as taken, and
stored. Every six months to a year, all information should be recorded again and compared to the
previous and original data. In this way, the affects of added equipment can be evaluated and any addition
of equipment that is not readily apparent or should not be on the dedicated system can be found.

  a. Proper environmental instrumentation will help in collecting much of the required data.
Instruments are available for monitoring: light levels (light meter), humidity (sling psychrometer or
hydrometer), temperature (chart recorder), RFI (field strength meter), static (Anderson Effect Meter),
vibration, and microbial contamination. If, however, these instruments are not readily available, a fairly
thorough evaluation of environmental conditions can be made with an amprobe, a sling psychrometer, and
the human eye. Green door hinges indicate the presence of chlorine; black or greasy door hinges result
from hydrocarbons. Check air-conditioning vents for signs of corrosion and hydrocarbons. A white
powder on the printer is caused by chlorine and blackening of the leads of the dual-in-line packs (DIPS)
and chips are caused by the presence of sulfur. A glass ashtray can be used to detect vibration. Place it
on a smooth surface and clearly mark its location. Return in a few days and if it has moved, vibration is
indicated.

8-14


---

                                                                                                                                    TM 5-689

  b. Hydrocarbons and sulfur can be removed with an electronic air cleaner. Chlorine or a high
concentration of sulfur will require a scrubber. Vibration difficulties can be handled by placing the
equipment on four-inch thick cork mats. High noise levels may require special noise abatement
procedures such as special acoustic wall covering, ceiling tiles, etc.

                                                                                                                                           8-15


---

              TM 5-689

   CHAPTER 9
MAINTENANCE

9-1. Objective

In most common electrical systems, two types of maintenance are normally recommended, routine and
preventive. Routine maintenance is that which is required to ensure continued operation of the system
and is usually that which is recommended by the equipment manufacturer. Preventive maintenance
carries the routine maintenance one step further by performing actions, such as replacing components that
may be nearing their end of life, that prevent failures of systems that would cause unwanted outages.
Breakdown maintenance is the minimum level performed by all organizations and consists of those
actions conducted after a failure to restore equipment or systems to an operational condition. The main
objective of a preventive maintenance program is to reduce the number of avoidable breakdowns. A
well-planned and efficient preventive maintenance program is expensive; it requires shop facilities,
skilled labor, keeping records, and stocking of replacement parts. However, the cost of downtime may
amount to ten or more times the actual cost of repair, and possibly compromised security and the problem
cascading into related systems. Therefore, maintenance must be scheduled into the operation of any
automated data processing (ADP) system that will be processing hard to replace or sensitive information.

  a. When preparing maintenance schedules, it must be recognized that too frequent inspections are a
waste of money and that insufficient inspections place vital equipment in jeopardy. The frequency of
inspection should depend on the equipment’s contribution to profitable production, its duty cycle, age,
overload, and other pertinent factors. The manufacturer of electrical equipment will recommend an
inspection cycle that may be modified later by experience. A good maintenance program provides for
scheduling equipment out of service for routine overhauls during periods of least usage, rather than risk a
breakdown at an inopportune time. Thus maintenance can be done at a time convenient to the production
or operating schedule. Some companies find it convenient to close down completely during the vacation
periods to provide time for planned overhauls.

  b. All equipment should be classified as to its role in the manufacturing or operating process.
Machinery and control equipment that could halt operations if a breakdown occurred should be classified
as vital equipment and should be provided with a very comprehensive preventive maintenance program.
Other equipment, such as room air conditioners, electric fans, drinking-water coolers, etc., should be
classified as non-vital equipment. A breakdown of non-vital equipment will have little or no adverse
affect on the processing of information or safety, etc., and a simplified maintenance program may be
used. The decision to provide the same degree of maintenance for non-vital and vital equipment must be
made with as much consideration as was given to the selection of the equipment itself. The cost of such
programs should be considered as part of the unit cost of operation or production. The essentials of an
effective preventive maintenance program include record taking and interpretation, acquisition of
adequate replacement parts, skilled labor to carry out the program, and cooperative management.

  c. It must be recognized that the deterioration of electrical equipment is normal, and this process
begins as soon as the equipment is installed. If deterioration is not checked, it can cause electrical failures
and malfunctions. Load changes or circuit alterations may be made without overall design coordination,
which can result in improper settings of protective devices or wrong trip units installed in the circuits.
With an electrical preventive maintenance and testing program, potential hazards that can cause failure of
equipment or interruption of electrical service can be discovered and corrected. Also, the program will

              9-1


---

TM 5-689

minimize the hazards to life and equipment that can result from failure of equipment when it is not
properly maintained.

  d. The systems within an ADP facility may interface with one another, such as main electrical power;
emergency power; dedicated “clean” power; utility power; fire and security systems hydraulic ;
pneumatic ; heating, ventilation, and air-conditioning (HVAC); and other mechanical systems. Therefore,
it is important to know how these interfaces work and how they can be coordinated in the maintenance
program. Related systems within a facility cannot be overlooked. The air-conditioning and heating
system that maintains temperature and humidity levels in an ADP center can result in ADP equipment
failures if this equipment fails. HVAC systems produce a quality work atmosphere for ADP personnel
but more importantly the HVAC systems produce controlled conditions that are essential to reliable ADP
operation.

9-2. Maintenance program

The main objective of planning preventive maintenance in an ADP system is to provide quality power at a
reasonable and acceptable cost.

  a. This objective can only be reached by implementing a well-planned maintenance program that will:

       (1) Improve overall plant and equipment productivity through continuous operation and production
by reducing downtime.

       (2) Minimize maintenance expenditures through budgeting for planned versus replacement cost by
collecting data on equipment and production downtime.

       (3) Establish maintenance priorities by analyzing equipment and production priorities.

       (4) Stock replacement parts for high prior ity apparatus.

       (5) Implement the best maintenance techniques and test equipment.

  b. The era of growing old with equipment is over. Today, it is impossible for untrained maintenance
personnel to keep pace with the continuous changes in electrical equipment being produced through
advanced technology. Service and maintenance requirements for electronic and solid-state circuitry
require a high level of specialized training and skill. The individual who is not given the opportunity, or
is unwilling to update the educational requirements necessary for the maintenance of modern equipment,
is faced with the possibility of being phased out along with the obsolete equipment being replaced. This
is a reality facing anyone who is expected to service and maintain sophisticated and more complex
apparatus.

  c. Plans for a maintenance program should be one of the first considerations when a new plant is
constructed, additions made, or more modern equipment purchases are installed. At this time, conditions
are ideal for one or more of the maintenance personnel to inspect the normally inaccessible parts of
equipment and to ask questions of the installing contractor or the manufacturer’s representative in order to
learn as much as possible about the maintenance requirements for new equipment coming under their
jurisdiction.

  d. Total familiarity with the electrical equipment is a necessary prerequisite for any maintenance
program to be successful, and an extremely valuable asset to rely on if it becomes necessary to correct or
repair any operating problems within the electrical equipment.

9-2


---

                                                                                                                                    TM 5-689

  e. The main parts of the maintenance program can be classified into maintenance management
considerations, technical requirements, and those items that should be included in the electrical
maintenance and test program.

       (1) The design of any maintenance program must meet the ultimate goals of management.
Maintenance is like an insurance policy: it has no direct payback, yet it is a cost that adds to the cost of
the final product. However, one must hasten to say that it has inherent payback. It is generally observed
that management resists the investment in a maintenance program even though they realize the need for
good maintenance. In view of this, it is up to electrical personnel to show management how a properly
planned electrical maintenance and testing program is justifiable.

       (2) The planning of the programs should then include the advantages of well-planned maintenance
along with cost data for lost production due to equipment failure versus cost of budgeted preventive
maintenance. Any maintenance program should prove that it is cost effective and minimizes equipment
failure. The planning of the program should include considerations for proper test equipment, tools, and
trained personnel to carry out maintenance routines. Also, consideration should be given to record-
keeping systems, which can range from fully computerized to manual file systems. To set up an electrical
preventive maintenance and test program, the following steps may be undertaken.

            (a) Determine the factors that will form the basis of the maintenance program, such as the
necessity for continuous production, and management policy on budgeting for planned maintenance
versus replacement of equipment.

            (b) Survey and consolidate data on equipment breakdowns and cost of lost production. Make
an analysis of the cost data to convince management of the benefits of planned maintenance.

            (c) Establish electrical maintenance priorities. These consist of on-line production sequence,
determining the most important to least important equipment, weighing the reliability of the equipment,
and other factors.

            (d) Establish the best maintenance techniques. This involves selecting the best maintenance
method and personnel for the various types of equipment and systems.

            (e) Schedule and implement the program. Monitor its benefits and costs. Analyze program
functions periodically for improvement of the program.

  f. After the program has been set up, it is essential that it consist of five elements that will prove it to
be a success: responsibilities, inspection, scheduling, work orders, and record-keeping.

       (1) The responsibilities of the maintenance organization should be clearly defined by organization
charts with functional work statements for each unit. The functional work statements must be established
by management as a matter of policy. Every other department must be informed of the responsibilities
assigned to maintenance organizations. The effectiveness of the maintenance departments will depend
upon how well they are organized and how well personnel are utilized.

       (2) Inspection is the key to the success of any maintenance program. Sufficient time should be
allocated for inspection to verify the condition of new and installed equipment. The purpose of inspection
is to provide advance warning as to the condition of the equipment under investigation. When inspection
is performed on definite cycles by qualified people, impending deterioration can be detected in advance
so that repair or replacement can be made before failure of the equipment occurs.

                                                                                                                                             9-3


---

TM 5-689

       (3) To perform maintenance, a definite schedule of work to be performed must be established.
Maintenance schedules must be based upon minimum downtime for the various operating segments. The
schedule for inspection, routine maintenance, and other work may vary for different equipment and will
depend upon many factors. These factors can be age of equipment, frequency of service, hours of
operation, environmental conditions, damage due to abuse, and safety requirements. Frequency of
scheduling of the tasks should be adjusted as data on various equipment are recorded and analyzed to
provide a balance between cost of maintenance and replacement cost of the equipment.

       (4) Work orders are job requests that need action for completion. Work orders can be established
for all inspection service and other work on equipment in terms of routines. Any of these routines should
include information on when such work is to be performed, where it is to be performed, and exactly what
has to be done. These routines can be generated by a computer-based maintenance system. The routines
should include all the pertinent information concerning the equipment.

       (5) The success of a planned maintenance program depends upon the impetus given by top
management and the interest of the maintenance personnel in the program. To have an effective program,
it is imperative that maintenance and test inventory data on all equipment should be complete and readily
available throughout the service life of the equipment. To that end, record-keeping is very important. All
forms and reports should be organized to provide ready accessibility to data when needed and to flag
down problem areas. Such data may also be used over the years to analyze trends for equipment
deterioration. If data is not recorded and maintained properly, the whole purpose of planned maintenance
is lost.

9-3. Maintenance data file

The maintenance data file of the ADP system will include the information relating to the hardware within
a defined system, a list of maintenance personnel qualified to support the equipment, training records with
the level of skills achieved, current data on manufacturers representatives, renewal parts vendors,
consultants with a special field of expertise that is not available in house, and the service organizations on
contract to maintain equipment.

  a. The most important phase of a preventive maintenance program is the recording and interpretation
of data pertinent to each piece of equipment. One method of data file record-keeping will use two or
more file cards for each piece of equipment. The equipment record card should include the motor
nameplate data, location in the plant, purchase price and installation cost, application, and the
manufacturer’s replacement part number for each replaceable part. The history card should include the
date of each periodic test, the test data, the type of repairs, the manhours, the cost of each repair, and the
initials of the workman in charge of the job. This data can be transferred to a computer database for
which there are many software packages available.

  b. The data file is the only way to preserve the integrity of data accumulated over the life of the
equipment. It indicates when maintenance costs are beginning to exceed the normally anticipated
expense so plans can be initiated to purchase new or higher rated apparatus.

  c. Since maintenance is a continuous activity, it is extremely important that historical records be kept
and updated on all apparatus. The place for this type of information is in the maintenance department file,
not in a hip pocket, notebook, or central engineering office where it cannot be reviewed regularly.

  d. The record card should indicate the maintenance task performed, why it was necessary, and
whether it was a routine breakdown or an emergency repair resulting from some extraneous cause.

9-4


---

                                                                                                                                    TM 5-689

Additional information should include how long it takes to perform the maintenance work on the
equipment, and what particular maintenance tasks must be performed regularly. An immediate update of
the record card should follow each maintenance period, and the report should be comprehensive enough
to assist anyone in determining whether all required maintenance was performed. This also holds true for
any type of maintenance periods, such as emergency repairs.

  e. When adding circuits to existing equipment or making any changes in wiring different from the
original drawings, it is essential that these changes be noted on the record cards. If wiring changes are not
recorded when they have been made, they are sure to be forgotten and more time will be required to
correct an otherwise routine maintenance task. More importantly, however, new circuits may be added
and connected to points of greater power, causing them to remain energized when the circuit breaker is
opened. Someone may be seriously injured because it is assumed that all connected circuits have been
de-energized when power has been turned off at the source. Never add a circuit without first establishing
its effect on the performance capabilities of the system or without immediately changing circuit drawings
to show the source of power and the added load requirements. Such action can result in feeder circuits
that are dangerously overloaded or a system imbalance. This can cause other connected loads to fluctuate
or even be interrupted due to voltage drop when some high current equipment load is started or stopped in
another area of the plant.

  f. Each time a piece of equipment is serviced, a record should be made indicating the date, work
performed, changes made, and probable cause of any problems other than routine servicing. A “fat file”
may indicate a misapplication or misuse. It may also indicate that load conditions may have changed,
requiring replacement with equipment of greater capacity and longer life.

9-4. Personnel qualifications

Maintenance personnel should be selected on the basis of qualifications for the job. Assignments should
not be made on a hit-or-miss basis to those who happen to be idle at the moment. Equipment may be
ruined by overzealous, inexperienced personnel. The maintenance department must not be a catchall for
personnel who could not adjust elsewhere. The complexity of control systems in automatic and semi-
automatic facilities requires well-educated and skilled personnel in the maintenance department. Very
often, because of the newness and complexity of the maintenance requirements, special training may be
required. A skilled maintenance force must be kept abreast of the latest techniques and developments in
the field. This may be done by visiting plant maintenance shows, subscribing to appropriate periodicals,
and attending specialized classes, panel discussions, and lectures.

  a. A file of equipment manufacturers’ bulletins and instructions should be available to all maintenance
personnel. Only modern testing equipment, good tools, and the latest methods should be used. Whenever
possible, maintenance standards and testing procedures recommended by the Institute of Electrical and
Electronics Engineers (IEEE), American National Standards Institute (ANSI), National Electrical
Manufacturers Association (NEMA), InterNational Electrical Testing Association (NETA) and the
National Fire Protection Association (NFPA) should be used. A good preventive maintenance program
represents insurance against avoidable outages that can completely de-stabilize an ADP facility.

  b. Additional personnel who possess a greater degree of technical training and specialized skills
should be added to the work force if necessary. However, when the plant inventory has only one or two
pieces of specialized equipment, the maintenance department should call in a manufacturer’s field service
representative when a problem develops, which is usually less costly in the long run.

  c. Inexperienced personnel attempting to repair or service any type of apparatus can spend hours
trying to locate trouble, and the repair could possibly cost more than the replacement of the equipment. In

                                                                                                                                             9-5


---

TM 5-689

the process the employee may disturb or alter adjustments which only a factory-trained service
representative can restore, and his actions may affect the reliability of the equipment or even the entire
system. There is also the possibility of further damaging the apparatus and incurring additional expense
because of experimenting or attempting to keep equipment operating when it should be repaired. By
using a manufacturer’s representative, maintenance personnel can acquire a considerable amount of
knowledge if they are present when the representative is working on the equipment. After a few service
calls, the maintenance man may know enough about the equipment to repair and maintain it himself in the
future.

  d. Certain guidelines should be adhered to when selecting outside assistance to contribute to a
maintenance program. It is of course possible to contract out all and every level of responsibility
associated with maintenance and testing.

       (1) There are certain advantages when utilizing contractor help.

            (a) The testing and maintenance firm can be a corporately independent testing organization
which can function as an unbiased testing authority, professionally independent of the manufacturers’
suppliers, and installe rs of equipment or systems evaluated by the testing firm.

            (b) The testing and maintenance firm is regularly engaged in the testing of electrical equipment
devices, installations, and systems, and will, therefore, maintain a degree of expertise that may be difficult
for in-house personnel to achieve and maintain on a cost effective basis.

            (c) The testing and maintenance firm can be required to utilize only full-time technicians who
are regularly employed by the firm. Electrically unskilled employees are not permitted to perform testing
or assistance of any kind. Electricians and/or linemen may assist, but may not perform testing and/or
inspection services.

            (d) The testing and maintenance firm can supply all test equipment that may be required for
any level maintenance.

            (e) Test equipment furnished by an outside firm can be required to be inspected and calibrated
within established industry standards.

       (2) Disadvantages to using contractor help include the following.

            (a) There can be many disadvantages associated with the maintenance program of any
sensitive electrical system or for that matter, any system. There is, however, one disadvantage that may
far outweigh any advantage.

            (b) The testing and maintenance firm is not sensitive to, neither can it be motivated to be
sensitive to, the critical intrinsic needs of the client.

9-5. Dedicated maintenance equipment

The maintenance equipment that is necessary to support, maintain, troubleshoot, and service the ADP
system is sensitive and sophisticated. A well organized maintenance department will own and maintain,
or have ready access to all of the test equipment that shall be needed to support their mission.

9-6


---

                                                                                                                                    TM 5-689

  a. The test equipment may be purchased and kept on site or it may be leased through an outside
vendor. Test equipment may be furnished by a contracted maintenance agency. The manufacturers of the
ADP system equipment being maintained should be consulted when selecting test equipment.

  b. Maintenance and test equipment that is used to maintain other equipment must also be maintained
and serviced on a regular basis to insure its reliability and accuracy. Test equipment should be
maintained by a qualified firm and a calibration program should be established which maintains all
applicable test instrumentation within rated accuracy. The accuracy shall be traceable to the National
Bureau of Standards in an unbroken chain.

       (1) Instruments shall be calibrated in accordance with the following frequency schedule.

            (a) Field instruments – 6 months maximum

            (b) Laboratory instruments – 12 months

            (c) Leased specialty equipment – 12 months

            (d) Dated calibration labels shall be visible on all test equipment

       (2) Records must be kept up-to-date which show date and results of all instruments calibrated or
tested.

       (3) An up-to-date instrument calibration instruction and procedure will be maintained for each test
instrument.

  c. Personnel assigned to the use of this equipment must be thoroughly trained in its efficient and safe
use.

9-6. Renewal parts

Renewal parts have always been and probably always will be a very temperamental subject with
accountants and budget planners. Renewal parts contribute nothing to a system until they are needed.
The maintenance manager should place the stocking and continuous maintenance of renewal parts high on
the priority list to maintaining a reliable ADP system.

  a. A carefully selected assortment of spare parts is essential to a good maintenance program and
represents insurance against prolonged shutdowns. Even though repairs may not be made on the
premises, keeping an adequate stock of spare parts will avoid delay in placing the machine back in
service. Overstocking and understocking should be avoided. Overstocking results in excessive carrying
costs as well as losses due to obsolescence when equipment is replaced. Understocking places the system
in jeopardy if an outage occurs. Very often replacement parts for one machine may be used on many
other units in the same area. In such instances it is unwise to stock spares for each unit alone, but to
follow the manufacturer’s recommendations concerning the minimum that is permissible for a group of
equipment.

  b. When making the decision to stock renewal parts, keep in mind the objectives of the maintenance
program. If there is any uncertainty as to type and a variety of renewal parts to be stocked, the original
equipment manufacturer should be consulted. The manufacturers should be provided with the critical
nature of the system and the level of expertise of the personnel maintaining the system.

                                                                                                                                             9-7


---

TM 5-689

9-7. Continuous inspection program

The equipment within an electrical system is prone to failure for a myriad of reasons. These failures may
occur for no apparent reason or the cause of failure may be poignantly apparent.

  a. The failure of electrical equipment should be analyzed to assess reasons for its breakdown. Unless
the cause is obvious, the equipment quality may be questioned. Reliability can be built into the
equipment, but it requires upkeep to retain it. The tendency to ignore regular maintenance and testing
generally prevails over regularly scheduled maintenance because regular maintenance may be considered
unnecessary and too expensive. Therefore, the best designed and built equipment may break down
through lack of attention. Every failure should be analyzed for its cause so that corrective measures can
be implemented to prevent similar breakdowns.

  b. A well-managed maintenance program will include an on-going and continuous inspection program
to monitor equipment. The main objective of continuous inspection will be to avoid unscheduled outages
and downtime. All equipment failures should also be reviewed and included in a continuous inspection
program. The cause of equipment failure may be readily determined if analyzed soon after the failure
occurs and other factors are available which may become lost if the analyzation process is delayed.

  c. The importance of a continuous inspection program will be determined by the critical nature of the
product of the ADP system. The inspection program may be limited to taking daily load readings or it
may include sophisticated computer monitoring of load, heat, and vibration sensors to list only a few.

9-8. Maintenance schedule

The purpose of the maintenance schedule is to establish the condition of the equipment and determine
what work will be required before its next scheduled maintenance. Usually, manufacturers’ service
manuals specify recommended frequency of maintenance and/or inspection. These time intervals are
based upon standard operating conditions and environments. If these standard conditions change for the
equipment, then the frequency should be modified accordingly. However, once the frequency of
scheduled maintenance is established, this schedule should be adhered to for at least several maintenance
cycles.

  a. The schedule should be adjusted if the equipment begins to experience unexpected failures. The
frequency can be reduced by as much as 50 percent. On the other hand, if the equipment does not require
maintenance for more than two inspections, the period of frequency for that equipment can be increased
by as much as 50 percent. Adjustment should be continued until the optimum interval is found.
Generally, the test frequency can vary from 6 months to 3 years.

  b. An efficient maintenance department will schedule in advance jobs that cannot be performed while
a plant is operating. Time must be allotted to do a good job, or the quality of the maintenance program
and the equipment will eventually be affected. However, sufficient time must be allowed to perform
proper maintenance. If more work is scheduled than can be completed during a shutdown, the equipment
will be returned to service with certain maintenance tasks not completed. The net result is that the job
card will indicate that servicing was performed, but in actuality certain operations will be missed and not
reported. This means that these operations will not be performed until the apparatus is scheduled for
maintenance at another time.

  c. If components appear to be wearing out faster or repairs are required more frequently than in the
past, it could be that the equipment is now required to carry additional loads for prolonged periods of
time, or a single shift is now operating around the clock. This will accelerate maintenance requirements

9-8


---

                                                                                                                                    TM 5-689

and alter the maintenance schedule. For instance, a reduction in the life expectancy of expendable items
such as contacts can only come about due to a greater number of operations or under additional load
requirements.

  d. The following guidelines provide a means by which an effective maintenance program can be
scheduled.

       (1) Establish objectives for the maintenance department.

       (2) Plan the maintenance program in advance.

       (3) Train the employees in the necessary technical areas.

       (4) Initiate a data file on each piece of equipment, and keep it updated.

       (5) Perform all indicated maintenance according to the original schedule.

       (6) Call in a manufacturer’s representative when necessary and provide necessary lead time so that
the representative can be on hand for the maintenance.

9-9. Maintenance tests

Preventive maintenance and testing will allow the prediction of impending failure of a particular piece of
equipment so that plans can be made to replace it without catastrophic results. The information on testing
can be obtained from several different standards, such as the Insulated Cable Engineering Association
(ICEA), NFPA, IEEE, ANSI, NEMA, NETA, Insurance Company Manuals (ICM), and others depending
on the equipment to be tested.

  a. Field tests are conducted to see whether newly installed equipment has been damaged, to indicate
whether any corrective maintenance or replacement is necessary on existing equipment, to indicate if the
equipment can continue to perform its design functions safely and adequately, to chart the gradual
deterioration of the equipment over its service life, and to check new equipment before energization. The
types of tests are acceptance tests, routine maintenance tests, and special maintenance tests that are
conducted for specific purposes.

       (1) Acceptance tests are known as proof tests and are performed on new equipment, usually after
installation and prior to energization. They are run to determine the following.

            (a) Whether the equipment is in compliance with the specification.

            (b) To establish a bench mark for future tests.

            (c) To determine that the equipment has been installed without damage.

            (d) To verify whether the equipment meets its design intent and limits.

       (2) Maintenance tests are performed at regular intervals over the service life of the equipment.
They are made concurrently with preventive maintenance. In the course of routine maintenance tests, it is
very helpful to record the information as it is found on the equipment and to also record the condition in
which the equipment is left. Therefore, these tests can be further subdivided into the following.

                                                                                                                                             9-9


---

TM 5-689

            (a) As-found tests are performed on equipment on receipt or after it has been taken out of
service for maintenance, but before any maintenance work is done.

            (b) As-left tests are performed after maintenance has been performed and just before re-
energization. They can indicate the degree of improvement in the equipment and serve as a bench mark
for comparison for future tests.

       (3) Special maintenance tests are performed on equipment that is known to be defective or has
been subjected to adverse conditions that may affect its operating characteristics. An example might be
the fault interruption by a circuit breaker, which requires inspection, maintenance, and tests before it can
be put back into service.

  b. The final technical function in developing a maintenance and test program involves establishment
of instructions, procedures, and methods to ensure that the equipment and system components operate
without failure. The maintenance department should have fully developed procedures and instructions for
thoroughly servicing all equipment and components. In addition, the maintenance department should
develop shutdown procedures, safeguards, interlocking of equipment, alarms, and methods of recording
data and reporting unusual conditions to the proper authority. The maintenance records should be further
utilized to evaluate results and as an indicator of possible modifications or changes in the maintenance
program. In other words, the recorded information should be used as historical data and for feedback to
modify the maintenance program.

9-10. Safety

Safe performance of maintenance is of prime importance when planning a preventive maintenance
program.

  a. All electrical wiring should conform to the recommendations of the National Board of Fire
Underwriters as presented in the National Electrical Code (NEC). Machinery and other equipment should
be installed with a view toward easy accessibility for maintenance. Joints and valves for water, steam,
waste, and other liquid-carrying lines should not be located over electrical apparatus unless such
equipment is drip-proof or splash-proof as required. Only approved safety solvents should be used for
cleaning insulation, bearings, and other parts.

  b. Switches and circuit breakers should always be closed completely and with a swift firm action.
This will enable the quick operation of a fuse or breaker if a fault exists. Partially closing the switch or
tickling the contacts “to see if everything is alright” is dangerous. The high-resistance path of a partially
closed switch will cause severe burning and arcing at the contacts.

  c. Before attempting repair work on electrical equipment, it must be disconnected from the power
supply. The incoming lines to the apparatus must be tested with a voltmeter or voltage tester of the
correct range for positive proof that the circuit is dead. All capacitors, connected to the apparatus must be
discharged.

  d. The following rules and guidelines should be adhered to when performing any maintenance or
testing.

       (1) All circuits and equipment are to be considered as energized until proven de-energized by
testing with voltage detectors, and grounding cables are connected. The voltage detectors selected should
be for the class of voltage supplied to the circuits and equipment to be serviced.

9-10


---

                                                                                                                                    TM 5-689

       (2) Personnel assigned to on-site electrical service work should be supplied with at least two
electrical voltage detectors. The voltage detectors provided shall be capable of safely detecting the
voltage present in the circuits and/or equipment to be serviced. The assigned personnel shall be instructed
in the correct operation of each detector before each on-site electrical job.

       (3) Each electrical circuit and/or piece of equipment to be serviced should be tested by an assigned
person with two detectors and then tested by one other person who has been trained in the correct
operation of the voltage detectors. This testing shall be performed in the assigned person’s presence to
insure that the electrical circuit and/or equipment is de-energized.

       (4) The voltage detectors should be checked for proper operation immediately prior to and
immediately after testing the electrical circuits and/or equipment to be serviced. These checks should be
made on a known source of energized voltage, or with a specifically designed tester supplied by the
detector vendor.

       (5) While testing circuits and/or equipment, the person performing the tests shall wear lineman’s
safety rubber gloves designed for the class of voltage in the circuits and/or equipment to be serviced and
other protective equipment for this work.

  e. Capacitors of any size and voltage class must be treated with special caution at all times. The
ability of a capacitor to hold a potentially lethal charge for extremely long periods of time after it is de-
energized makes it necessary to remove the capacitor from service in the following sequence.

       (1) Isolate the capacitors by opening the breakers or isolation devices connecting them to the
electrical system.

       (2) Permit the capacitors to drain off the accumulated charge for five to ten minutes. (There is
generally a built-in device which accomplishes this drain).

       (3) Discharge and ground the capacitors. While performing these procedures, be very careful that
sufficient distance is maintained from the capacitors with a “hot stick” in the event the drain-off device is
not properly functioning.

       (4) Vacuum circuit interrupters such as the types used in circuit breakers and load tap changers can
generate lethal amounts of x-ray radiation.

  f. Although the procedure for hipotting a vacuum circuit interrupter is similar to that used for any
other electrical device, there are two areas that require the exercise of extra caution.

       (1) During any hipotting operation, the main shield inside the interrupter can acquire an electrical
charge that usually will be retained after the hipot voltage is removed. This shield is attached to the
midband ring of the insulating envelope. A grounding stick should always be used to discharge the ring
as well as the other metal parts of the assembly before touching the interrupter, connections, or breaker
studs.

       (2) High voltage applied across open gaps in a vacuum can produce hazardous x-radiation if the
voltage across the contacts exceeds a certain level for a given contact gap. Therefore, do not make hipot
tests on an open breaker at voltages higher than recommended by the manufacturer. During the hipot test,
the steel front panel and partial side panels should be assembled to the breaker. Personnel should stand in
front of the breaker to take advantage of the shielding afforded by the panels. If this position is not
practical, equivalent protection can be provided by limiting personnel exposure to testing four three-phase

                                                                                                                                           9-11


---

TM 5-689

breakers per hour with the personnel not closer than 9 feet 10 inches to the interrupters. During
equipment operation in the normal current carrying mode, there is no x-radiation because there are no
open contacts.

       (3) Refer to the equipment manufacturers’ instruction manuals for proper testing methods and
safety procedures.

  g. Electrostatic coupling can be present in de-energized circuits at levels that may be fatal or cause
involuntary reactions that may jeopardize personnel safety. When personnel are working on de-energized
circuits that are adjacent to energized circuits, a flux linkage between circuits may occur if circuits are not
properly grounded. Solid ground must be attached to the de-energized circuits at all times. De-energized
equipment must always be grounded with an appropriate resistor grounding device before installing
grounds and attempting to work on the equipment.

9-11. Electrical equipment fires

The standard procedure for fighting electrical fires is to open the circuit and then apply an approved
extinguishing agent.

  a. A carbon dioxide (CO2) extinguisher offers the advantage of extinguishing the fire, cooling the
apparatus, leaving no residue, and having no adverse affect on the insulation and metal parts, and it may
be used on live circuits. Hence it is the preferred extinguishing agent for most electrical fires. However,
when applied in confined spaces, such as in the engine room of a ship, the CO2 should be purged with air
before workmen are allowed to enter.

  b. The dry-chemical extinguisher is satisfactory and may be used on live circuits. However, it leaves
a residue and does not cool the apparatus so effectively as does the CO2 extinguisher. A carbon
tetrachloride extinguisher will put out the fire and cool the apparatus, but excessive use of this agent will
be detrimental to the insulation and metal parts. Carbon tetrachloride is also very noxious and should be
used only in well-ventilated places.

  c. Water sprinklers and steam smothering apparatus may be used only after the circuit is de-energized.
Such systems have been built into large machines and are very effective. The serious drawback to their
extended usage is the time required to clean and dry the apparatus before it can be placed back in service.

  d. Regardless of the type of extinguishing agent used, the apparatus should be thoroughly inspected
and tested after the fire is out. The cause of the fire should be determined, and corrective action should be
taken before the apparatus is put back in service. If no damage is apparent and an insulation-resistance
test indicates normal, the apparatus may be started at reduced load and carefully observed as load is
applied.

9-12. Equipment diagrams

To perform an effective maintenance program, it is necessary to have accurate data about the electrical
power system. This may include one-line diagrams, short-circuit coordination studies, wiring and control
diagrams, and other data that can be used as a reference point for future maintenance and testing. The
purpose of these diagrams is to document and serve as an official record of equipment and circuit
installation. NEMA has established standards for diagram symbols, device designations, and electrical
symbols. The types of diagrams and drawings in common use are the following.

9-12


---

                                                                                                                                    TM 5-689

  a. A process or flow diagram is a conceptual diagram of the functional inter-relationship of
subsystems in pictorial form.

  b. A one-line (single -line) diagram shows, by means of single lines and graphic symbols, the flow of
electrical power or the course of electrical circuits and how they are connected. In this diagram, physical
relationships are usually disregarded.

  c. Schematic (elementary) diagrams show all circuits and device elements of the equipment. This
diagram emphasizes the device elements and their functions, and it is always drawn with all devices
shown in de-energized mode.

  d. A control sequence (truth-table) diagram is a description of the contact positions or connections that
are made for each position of control action or device.

  e. A wiring diagram (connection diagram) locates and identifies electrical devices, terminals, and
interconnecting wires in an assembly. This diagram may show interconnecting wiring by lines or
terminal designations.

  f. Interconnection diagrams show only the external connections between controllers and associated
equipment or between various housing units of an assembly of switchgear apparatus.

  g. Circuit layout and routing diagrams show the physical layout of the facility and equipment and how
the circuit to the various equipment is run.

  h. Electrical power system data, diagrams, and drawings are needed during maintenance and testing of
electrical equipment. This may involve information and data relating to protective devices and relays.
Such data are usually found in a short-circuit coordination study and usually encompass all the short-
circuit values available in the power system, relays, and trip device settings. Normally, this study is
performed as part of the initial facility design, and then validated during the construction phase to assure
that equipment and values specified have been met. When accepting the facility, this study data should be
used as a bench mark, and any changes that may have been made during construction in the system
should be incorporated to update the study for future references.

  i. System diagrams will generally be needed for large systems. Such diagrams may consist of control
and monitoring system, lighting system, ventilation system, heating and air-conditioning system,
emergency system, and other systems. All the system diagrams may interface with one another, such as
electrical diagrams, fire and security diagrams, emergency power, and hydraulic pneumatic or mechanical
systems. Each system may depend upon the integr ity of each associated system within a facility. It is,
therefore, important to understand how these systems interface and how they can be coordinated into a
maintenance and test program.

9-13. Test forms

A key factor in an efficient maintenance and testing program is the preparation and filing of all inspection
and test records. This enables mathematical trends to be established, and to a great extent future
performance and maintenance measures can be predicted. Forms permit the orderly recording of data and
are a reminder to record all pertinent factors, for example, temperature and relative humidity. A variety
of forms are available in the industry or they can be tailored to fit requirements as needed.

  a. One method of filing is by apparatus with the original inspection or test, and all successive tests for
that apparatus would be filed in chronological order with the latest test on top. The important fact is that

                                                                                                                                           9-13


---

TM 5-689

records should be maintained (in whatever order or format that may be suitable) for comparison and
evaluation.

  b. Any efficient maintenance department should have forms available for their staff. A data file
composed of consistent documentation is an integral part of any maintenance department. Test forms and
procedures for specialty equipment are available from equipment manufacturers. It should be noted that
forms can be generated to cover any set of unique circumstances that a qualified maintenance crew may
encounter and that the attached forms are included only as samples and must not be regarded as the only
specimen available.

9-14


---

            TM 5-689

APPENDIX A
REFERENCES

Required Publications

Government Publications

MIL-HDBK-419A
Grounding, Bonding, and Shielding for Electronic Equipment and Facilities (cited in 4-6c(11))

Non-Government Publications

Electric Power Research Institute (EPRI)
3412 Hillview Avenue, Palo Alto, CA 94304

  Proceedings of EPRI’s PQA ‘95
  New York, NY, May 9-11, 1995

       Hughes, M. B. and J. S. Chan, “Canadian National Power Quality Survey Results” (cited in
       paragraph 2-3i(3))

       Sabin, D. D. and T. E. Grehe, “Preliminary Results of Monitoring from the EPRI
       Distribution Power Quality Project” (cited in paragraph 2-3i(3))

       Key, T. S., D. S. Dorr, M. B. Hughes, and J. J. Stanislawski, “Matching Appliances to their
       Electrical Environments” (cited in paragraph 2-3i(3))

Information Technology Industry Council (ITI)
1250 Eye Street NW, Suite 200, Washington, D. C. 20005
(cited in paragraphs 2-3h., 2-3i(1), 3-3, 6-6m, 6-6n, and appendix B)

Institute of Electrical and Electronics Engineers (IEEE)
445 Hoes Lane, P. O. Box 1331 Piscataway, NJ 08855-1331

  IEEE Std C37.13-1990
  Standard for Low-Voltage ac Power Circuit Breakers Used in Enclosures (cited in paragraph 6-
  5h(4)(a))

  IEEE Std C37.14-1992
  Standard for Low-Voltage dc Power Circuit Breakers Used in Enclosures (cited in paragraph
  6-5h(4)(a))

  IEEE Std C37.20-1-1993
  Standard for Metal-Enclosed Low-Voltage Power Circuit Breaker Switchgear (cited in
  paragraph 6-5h(4)(a))

            A-1


---

TM 5-689

  ANSI/IEEE Guide C62.41-1991
  IEEE Recommended Practice for Surge Voltages in Low Voltage AC Power Circuits (cited in
  paragraph 2-5b, appendix B 3.4)

  IEEE Paper C74-199-6
  Allen, G. W. and D. Segal, “Monitoring of Computer Installation for Power line Disturbances”,
  (cited in paragraph 2-3i(2))

  IEEE Transactions on Industry Applications

       Key, T. S., “Diagnosing Power Quality-Related Computer Problems”, Vol. 1A-15, No. 4,
       July/August 1979 (cited in paragraph 2-3i(3))

       Martzloff, F. D. and T. S. Gruzs, “Power Quality Site Surveys: Facts, Fiction, and
       Fallacies”, Vol. 24, No. 6, Nov/Dec 1988 (cited in paragraph 2-3i(3))

       Dorr, D. S., “Point of Utilization Power Quality Study Results”, Vol. 1A-31, No. 4,
       July/August 1995 (cited in paragraph 2-3i(3))

  IEEE International Telecommunications Energy Conference
  Goldstein, M. and P. D. Speranza, “The Quality of U.S. Commercial AC Power”, 1982, pp. 28-
  33, CH1818-4 (cited in paragraph 2-3i(3))

  IEEE Paper 85 WM 243-1 (cited in paragraph 2-5b)

  IEEE Std 241-1990
  Recommended Practice for Electric Power Systems in Commercial Buildings (cited in
  paragraphs 6-2b, 6-6p)

  IEEE Std 446-1995
  Recommended Practice for Emergency and Standby Power Systems (IEEE Orange Book)
  (cited in paragraphs 6-2b and 6-6p)

  IEEE Std 519-1992
  Recommended Practices and Requirements for Harmonic Control in Electrical Power Systems
  (cited in paragraphs 5-1a, 5-1b)

National Electrical Manufacturers Association (NEMA)
2101 L Street, NW, Suite 300, Washington, DC 20037

  NEMA ICS 10-1993
  Industrial Control and Systems: AC Transfer Switch Equipment (cited in paragraph 6-6p)

Canadian Standards Association
178 Rexdale Blvd, Etobicoke ON M9W 1R3, Canada

  C22.2 No. 107.1-95
  General Use Power Supplies (cited in paragraph 6-6p)

A-2


---

                                                                                                                         TM 5-689

The Electrical Generating Systems Association
1650 S. Dixie Highway, 5th Floor, Boca Raton, Florida 33432

  EGSA 100S-1996
  Performance Standard for Transfer Switches for Use with Engine Generator Sets (cited in
  paragraph 6-6p)

American National Standards Institute (ANSI)
1430 Broadway, New York, New York 10018

  ANSI C37.16-1997
  Low-Voltage Power Circuit Breakers and ac Power Circuit Protectors Preferred Ratings,
  Related Requirements, and Application Recommendations (cited in paragraph 6-5h(4)(a))

  ANSI C37.17-1997
  Trip Devices for ac and General Purpose dc Low Voltage Power Circuit Breakers (cited in
  paragraph 6-5h(4)(a))

National Fire Protection Association (NFPA)
One Batterymarch Park, P. O. Box 9101, Quincy, MA 02269-9101

  NFPA 70-1999
  National Electrical Code (cited in paragraphs 4-2, 4-2c, 4-2c(1), (2), 4-2d., 4-2e, 4-2f, 4-2f.(2),
  4-2g, 4-2g(2), (3), 4-2h, 4-3a(2), 4-3b(2), 4-5c(2), 4-6a(2), 4-6b, 4-6b(2), 4-6b(6), 4-6b(10)(a),
  4-6b(10)(b), 4-6b(10)(c), 5-6e, 6-2a, 6-6k(1 through 5), 6-6l, 8-4, 8-5a)

  NFPA 780-1997
  Standard for the Installation of Lightning Protection Systems (cited in paragraphs 7-3b(4), 7-
  3c(6), 7-3e, 7-3f(2), and 7-3g(2))

Underwriter’s Laboratories, Inc. (UL)
333 Pfingsten Road, Northbrook, IL 60062-2096

  96A
  Master Label Code (cited in paragraph 7-3b(4))

  1008
  Transfer Switch Equipment (cited in paragraph 6-6q)

  1449
  Standard for Transient Voltage Surge Suppressors (cited in paragraphs 3-4i(1))

Lightning Protection Institute
3335 N. Arlington Hts. Rd., Suite E, Arlington Hts., IL 60004

  Standard LPI-175
  Installation Code (cited in paragraph 7-3b(4))

                                                                                                                                 A-3


---

TM 5-689

InterNational Electrical Testing Association (NETA)
P.O. Box 687, Morrison, CO 80645
www.netaworld.org

  IETA 1 - 1997
  Maintenance Testing Specifications for Electric Power Distribution Equipment and Systems

Related Publications

Government Publications
  National Bureau of Standards; Washington, D.C.20234
  Copies available from National Technical Information Service, U.S. Department of Commerce,
  Springfield, VA 22161
  FIPS PUB 94-1983
  Federal Information Processing Standards Publication 94, Guideline on Electrical Power for
  ADP Installations

Non-Government Publications
  IEEE Std 142-1991
  Recommended Practice for Grounding of Industrial and Commercial Power Systems (IEEE
  Green Book)
  IEEE Std 1100-1999
  Recommended Practice for Powering and Grounding Electronic Equipment (IEEE Emerald
  Book)
  IEEE Std 1159-1995
  Recommended Practice for Monitoring Electric Power Quality
  NFPA 75-1999
  Standard for the Protection of Electronic Computer/Data Processing Equipment

A-4


---

                                                                                                                           TM 5-689

                                     APPENDIX B

                ITI (CBEMA) CURVE APPLICATION NOTE

_______________________________________________________________________________

The ITI (CBEMA) Curve, included within this Application Note, is published by Technical
Committee 3 (TC3) of the Information Technology Industry Council (ITI, formerly known as the
Computer & Business Equipment Manufacturer Association). It is available at
http://www.itic.org/technical/iticurv.pdf.

1. SCOPE

    The ITI (CBEMA) Curve (figure B-2) and this Application Note describe an ac input voltage
envelope which typically can be tolerated (no interruption in function) by most Information
Technology Equipment (ITE). The Curve and this Application Note comprise a single document
and are not to be considered separately from each other. They are not intended to serve as a design
specification for products or ac distribution systems. The Curve and this Application Note describe
both steady-state and transitory conditions.

2. APPLICABILITY

The Curve (figure B-2) and this Application Note are applicable to 120V nominal voltages
obtained from 120V, 208Y/120V,and 120/240V 60 hertz systems. Other nominal voltages and
frequencies are not specifically considered and it is the responsibility of the user to determine the
applicability of these documents for such conditions.

3. DISCUSSION

This section provides a brief description of the individual conditions which are considered in the
Curve. For all conditions, the term " voltage" implies an ideal condition of 120V root mean square
(RMS), 60 hertz. Seven types of events are described in this composite envelope. Each event is
briefly described in the following sections, with two similar line voltage sags being described under
a single heading. Two regions outside the envelope are also noted. All conditions are assumed to
be mutually exclusive at any point in time, and with the exception of steady-state tolerances, are
assumed to commence from the nominal voltage. The timing between transients is assumed to be
such that the Information Technical Equipment (ITE) returns to equilibrium (electrical, mechanical,
and thermal) prior to commencement of the next transient.

3.1 Steady-state tolerances. The steady-state range describes an RMS voltage which is either
very slowly varying or is constant. The subject range is +/-10 percent from the nominal voltage.
Any voltages in this range may be present for an indefinite period, and are a function of normal
loadings and losses in the distribution system.

3.2 Line voltage swell. This region describes a voltage swell having an RMS amplitude of up to
120 percent of the RMS nominal voltage, with a duration of up to 0.5 seconds. This transient may
occur when large loads are removed from the system or when voltage is supplied from sources
other than the electric utility.

3.3 Low-frequency decaying ring wave. This region describes a decaying ring wave transient
which typically results from the connection of power-factor-correction capacitors to an ac

                                                                                                                                    B-1


---

TM 5-689

distribution system. The frequency of this transient may range from 200 hertz to 5 kilohertz,
depending upon the resonant frequency of the ac distribution system. The magnitude of the
transient is expressed as a percentage of the peak 60 hertz nominal voltage (not the RMS value).
The transient is assumed to be completely decayed by the end of the half-cycle in which it occurs.
The transient is assumed to occur near the peak of the nominal voltage wave form. The amplitude
of the transient varies from 140 percent for 200 hertz ring waves to 200 percent for 5 kilohertz ring
waves, with a linear increase in amplitude with increasing frequency. Refer to figure B-1 for an
example of a typical wave form.

                          Figure B-1. Typical low frequency decaying ring wave
3.4 High-frequency impulse and ring wave. This region describes the transients which typically
occur as a result of lightning strikes. Wave shapes applicable to this transient and general test
conditions are described in American National Standards Institute (ANSI)/Institute of Electrical
and Electronics Engineers (IEEE) C62.41-1991. This region of the curve deals with both
amplitude and duration (energy), rather than RMS amplitude. The intent is to provide an 80 joule
minimum transient immunity.
3.5 Voltage sags. Two different RMS voltage sags are described. Generally,these transients
result from application of heavy loads, as well as fault conditions, at various points in the ac
distribution system. Sags to 80 percent of nominal (maximum deviation of 20 percent) are
assumed to have a typical duration of up to 10 seconds, and sags to 70 percent of nominal
(maximum deviation of 30 percent) are assumed to have a duration of up to 0.5 seconds.

B-2


---

                                                                                                                           TM 5-689

3.6 Dropout. A voltage dropout includes both severe RMS voltage sags and complete
interruptions of the applied voltage, followed by immediate re-application of the nominal voltage.
The interruption may last up to 20 milliseconds. This transient typically results from the occurrence
and subsequent clearing of faults in the ac distribution system.
3.7 No damage region. Events in this region include sags and dropouts which are more severe
than those specified in the preceding paragraphs, and continuously applied voltages which are less
than the lower limit of the steady-state tolerance range. The normal functional state of the ITE is
not typically expected during these conditions, but no damage to the ITE should result.
3.8 Prohibited region. This region includes any surge or swell which exceeds the upper limit of
the envelope. If ITE is subjected to such conditions, damage to the ITE may result.

                                                                                                                                    B-3


---

TM 5-689

                                     Figure B -2. ITI (CBEMA) Curve
                                                 (Revised 2000)

Published by:
Information Technology Industry Council (ITI)
1250 Eye Street NW Suite 200 Washington DC 20005
202-737-8888
http://www.itic.org
May be reprinted with permission.

B-4


---

                                         GLOSSARY  TM 5-689
                                                           G-1
Section I
Abbreviations

A
Ampere

ac
Alternating Current

ADP
Automated Data Processing

AFD
Adjustable Frequency Drives

AGM
Absorbent Glass Mat

Ah
Ampere-Hour

ANSI
American National Standards Institute

AWG
American Wire Gauge

CFC
Chlorofluorinated Hydrocarbons

CO2
Carbon Dioxide

CPU
Central Processing Unit

dB
Decibels

dc
Direct Current

DIPS
Dual-in-line Packs

EM
Electromagnetic


---

TM 5-689

EMI
Electromagnetic Interference

ESD
Electrostatic Discharge

FET
Field-Effect Transistors

GELL
Gelled Electrolyte Design

GHz
Gigahertz

HDF
Harmonic Distortion Factor

HVAC
Heating, Ventilating, and Air Conditioning

ICEA
Insulated Cable Engineering Association

ICM
Insurance Company Manuals

IEEE
Institute of Electrical and Electronics Engineers, Inc.

IGBT
Insulated Gate Bipolar Transistors

ITE
Information Technology Equipment

ITI
Information Technology Industry Council

kHz
Kilohertz

KOH
Potassium Hydroxide

kVA
Kilovolt Amperes

kVAR
Kilovolt Amperes Reactive

G-2


---

kW                                             TM 5-689
Kilowatts                                              G-3

LC
Inductive-Capacitive

LPI
Lightning Protection Institute

M-G
Motor-generator

MHz
megahertz

NEC
National Electrical Code

NEMA
National Electrical Manufacturers Association

NETA
International Electrical Testing Association

NFPA
National Fire Protection Association

NICAD
Nickel Cadmium

OSHA
Occupation Safety & Health Administration

pF
Picofarads

PVC
Polyvinyl Chloride

RF
Radio Frequency

RFI
Radio Frequency Interference

RMS
Root Mean Square


---

TM 5-689

SCR
Silicon Controlled Rectifier

SMPS
Switching Mode Power Supplies

THD
Total Harmonic Distortion

TTL
Transistor-Transistor Logic

TVSS
Transient Voltage Surge Suppressors

UL
Underwriters’ Laboratories

UPS
Uninterruptible Power Supplies

VA
Volt Ampere

VAR
Volt Amperes Reactive

VRLA
Valve Regulated Lead-Acid

Section II
Terms

ALARM
A condition which is annunciated but does not cause shutdown.

ALTERNATE POWER SOURCE
One or more generator sets, or battery systems where permitted, intended to provide power during the
interruption of the normal electrical service; or the public utility electrical service intended to provide
power during interruption of service normally provided by the generating facilities on the premises.

AMBIENT TEMPERATURE
The temperature of the environment immediately surrounding the systems into which heat is dissipated.
For forced air-cooled units, the ambient temperature is measured at the air intake.

AMERICAN WIRE GAUGE (AWG)
A standard for sizing cross-sectional areas of wire and for measuring sheet-metal thickness

AMPERE (A)
Electron or current flow representing the flow of one coulomb per second past a given point in a circuit.

G-4


---

                                                                                                                                    TM 5-689

ANTIMONY
An element sometimes used to harden the plate material used in lead acid cells.

APPLIANCE
Electrical equipment, generally other than industrial, normally built in standardized sizes or types, which
is installed or connected as a unit to perform one or more functions.

ARC
Sparking that results when undesired current flows between two points of differing potential. It may be
due to leakage through a contaminated leakage path.

ARRESTER
A device placed across the conductors of a power transmission line or data line to suppress high-
amplitude transients.

AUTOMATIC TRANSFER
A transfer between electrical power sources without operator/user involvement and is usually based upon
the status or condition of the input/output ac power.

BATTERY
A group of cells connected to deliver more voltage and/or more current than a single cell.

BRANCH CIRCUIT
One division of a load circuit. Its current drain is limited by a fuse or circuit breaker.

BROWNOUT
A commercial line voltage reduction necessitated by inadequate generator capacity at a particular time.
Nominal reductions are 3%, 5%, or 8%.

BYPASS SOURCE
An alternate source for the critical bus which can be connected to the load in the event of a UPS failure or
for routine maintenance.

CALCIUM
An element sometimes used to harden the plate material used in lead acid cells.

CAPACITOR
Two plates or conductors separated by a dielectric material. Applying a voltage across the plates causes
current to flow and stores a charge.

CELL
A unit containing a combination of metal plates and an electrolytic solution. When connected to an
external circuit, a charged cell reacts chemically and delivers an electrical output.

CHARGE VOLTAGE
The voltage level maintained in a cell or battery in its maximum charge condition.

CIRCUIT BREAKER
A device, usually electro-mechanical, which detects excessive power demands in a circuit and self-
interrupts when they occur.

                                                                                                                                            G-5


---

TM 5-689

CLAMP
To limit the voltage to a specified level by limiting the voltage source.

COAX
A cable consisting of two concentric conductors separated by a dielectric material. Usually flexible, but
maintains constant conductor spacing under stress.

COMMON-MODE VOLTAGE
One common to both signal input (or power input) terminals of a circuit. An undesired common-mode
voltage is usually developed between the zero signal reference ground and some other ground point.

COMMUTATION
A term used to mean “turning off a SCR.” For this to be accomplished, the gate signal must be removed
and the current through the SCR must be reduced to zero.

CONDUCTIVE
Adjective describing not only those materials, such as metals, which are commonly considered as
electrically conductive, but also that class of materials which, when tested have a resistance not exceeding
1,000,000 ohms. Such materials are required where electrostatic interconnection is necessary.

CONNECTION
One which indicates the location and describes the types of connectors to be used at every junction in the
distribution system.

CORE
The iron form or frame on which a choke or transformer is wound.

CRITICAL EQUIPMENT
That equipment essential to the safety of the occupants of the facility.

CRITICAL LOAD
Equipment that must have an uninterrupted power input to prevent damage to a facility or to itself, or to
prevent damage or injury to operating personnel.

CROWBAR
The characteristic of a protective device (i.e., gas tubes, SCR, thyristor) causing a momentary short circuit
between two protected points in a circuit when an over-voltage occurs.

DIRECT CURRENT (dc)
An electric current flowing in one direction.

DELTA
A method of connecting a three-phase source or load in a closed series loop with the output or input
connections made to each of the three junctions.

DISK
A memory device used to store data for future computer use.

DUTY CYCLE
The ratio of operating time to non-operating time.

G-6


---

                                                                                                                                    TM 5-689

ELECTROLYTE
The acid or alkaline solution surrounding the plates of a battery cell.

EMERGENCY SYSTEM
A system of feeders and branch circuits used in meeting the requirements of Article 700 of NFPA 70,
National Electrical Code, and intended to supply alternate power to a limited number of prescribed
functions vital to the protection of life and safety, with automatic restoration of electrical power within
ten seconds of power interruption.

ENGINE GENERATOR
Combination of an internal combustion engine and a generator.

EQUALIZE
A brief charge with an elevated voltage (about 2.33 volts/cell) to equalize the specific gravity of the cells
in a battery string.

FARADAY SHIELD
A metallic housing, screen, or sheath that substantially reduces the effect of electric fields or for providing
a means for reducing electrostatic coupling between conductors.

FAILURE
An incident which increases the hazard to personnel or patients or affects the safe functioning of electric
appliance or devices. It includes failure of a component, loss of normal protection paths such as
grounding, and short circuits or faults between ene rgized conductors and the chassis.

FAULT CURRENT
A current in an accidental connection between an energized and a grounded or other conductive element
resulting from a failure of insulation, spacing, or containment of conductors.

FEEDBACK
Energy coupled from the output of a circuit to its input.

FEEDER
All circuit conductors between the service equipment, or the generator switchboard of an isolated plant,
and the final branch circuit over-current device.

FERRO-RESONANCE
Resonance resulting when the iron core of an inductor that’s part of an LC circuit is saturated, increasing
the inductive reactance to the value of the capacitive reactance.

FLASHOVER
Flashing due to high current flowing between two points of different potential. Usually due to the
insulation breakdown caused by arcing.

FLOOR LOADING
A statement of the force, usually in lbs/ft2, exerted on a floor when equipment is installed.

FLUCTUATION
A sag or swell in voltage amplitude, often caused by load switchin g or fault clearing.

                                                                                                                                            G-7


---

TM 5-689

FLYWHEEL
A large, heavy wheel used as a governor to maintain constant generator speed by inertial force.

FOLLOW CURRENT
The current from the connected power source that flows through an arrester (typically gas tube) during or
following the passage of discharge current.

FREQUENCY DEVIATION
A swing away from nominal frequency.

GATE
A logic element but usually refers to the signal lead of an SCR. By applying a gate signal to this lead, the
SCR can be commanded to the conducting state if it is forward biased.

GATE SIGNAL
The signal applied to the gate lead of a SCR by the GFM.

GROUND
A connection from a circuit or object to the earth.

GROUND FAULT
Any undesired current path from a point of differing potential to ground.

GROUNDING
A system of conductors which provides a low-impedance return path for leakage and fault currents. It
coordinates with, but may be locally more extensive than, the grounding system described in Article 250,
NFPA 70, National Electrical Code.

HARMONICS
A periodic waveform can be expressed as a sum of sinewaves which are integral multiples of the
repetitive frequency of the waveform. The first harmonic is often referred to as the fundamental and is
one times the frequency. The second harmonic is 2X, the third 3X, etc. Harmonics present in a
waveform will cause its shape to deviate from a sinewave, so in UPS systems, it is desirable to have low
harmonic distortion.

HARMONIC DISTORTION
The presence of harmonics that change an ac voltage waveform from sinusoidal to complex.

IMPEDANCE
Impedance is the ratio of the voltage drop across a circuit element to the current flowing through the same
circuit element. The circuit element may consist of any combination of resistance, capacitance or
inductance. The unit of impedance is the ohm.

INDUCTOR
A conductor, usually coiled, which tends to oppose any change in the flow of current through itself.

INRUSH CURRENT
The initial surge current demand before a load resistance or impedance increases to its normal operating
value.

G-8


---

                                                                                                                                    TM 5-689

INVERTER
The subsystem of the UPS which converts dc power to ac power for the critical load.

ION
An electrically charged atom.

ISOLATION TRANSFORMER
Any transformer not having a dc current path connecting the primary and secondary windings.

JOULE
A unit of energy that is a function of voltage, current, and time. One joule is equal to one watt-second.

LINE CONDITIONER
A circuit or device designed to improve the quality of an ac line.

LOAD
The driven device that uses the power supplied by the source.

LOAD SWITCHING
Transferring the load from one source to another.

MAGNETIC FIELD
Flux, O. The pattern of magnetic force lines surrounding a magnet or energized electromagnet or
inductor.

MIL-SPEC OR MIL-STD
Document issued by one of the military or government departments, stipulating specifications and
outlining tests to determine that an item conforms to specifications.

MOTOR-GENERATOR
Combination of an ac motor and an ac generator. The motor is driven from the ac source and the
generator becomes the new source for the load. Provides very good isolation from ac power line
fluctuations and short-term anomalies.

NEUTRAL
The junction point of the legs in a wye circuit.

NEUTRALIZIING WINDING
An extra winding that cancels the harmonics developed in the saturable secondary, resulting in a
sinusoidal output from a ferroresonant transformer.

NOISE
Continuous or intermittent low energy disturbances superimposed on a useful waveform which may
obscure its information content. Typically low voltage, low current, and repeatable frequency.

NON-PROGRAMMED JUMP
A skip of one or more of the ordered instructions in a computer program due to the presence of a spurious
pulse or transient.

                                                                                                                                            G-9


---

TM 5-689

ORDERLY SHUTDOWN
Sequentia l shutdown of the units comprising a computer to prevent garbling or loss of data, or damage to
the system.

OSCILLATION
Flywheel action in an LC circuit caused by the current generated by the alternate charge and discharge of
the capacitor and the expansion and contraction of the magnetic field around the inductor.

PERIPHERAL
Any device used to process data for entry into or extraction from a computer.

PHASE COMPENSATION
Switching capacitors into or out of the power distribution network to compensate for load power factor
variations.

PHASE CONTROL
A form of regulation which controls the output of a SCR circuit by varying the conduction time of the
SCR.

PLANTE PLATE
A positive cell plate made from a cast lead antimony grid with lead buttons embedded in its surfaces.
Named for its inventor.

POWER FACTOR
W/VA. The ratio of real power to apparent power. It will be “leading” or “lagging,” depending upon
which way the load shifts the circuit current phase with respect to the voltage phase. Inductive loads
cause the current to lag; capacitive loads cause the current to lead. Most loads are inductive.

POWER LINE MONITOR
A device to detect and indicate changes in power line frequency and/or voltage amplitude.

POWER OUTAGE
An interruption of commercial power.

POWER PROFILE
A graph of the power requirements for a composite load during the start-up period, from turn-on until
steady-state operations commences.

PROTECTOR
A device that detects a fault and protects against it.

REACTANCE
The component of impedance contributed by inductance or capacitance. The unit of reaction is the ohm.

REFLECTION
The return wave generated when a traveling wave reaches the load, the source, or a junction point where
there is a change in line impedance.

RELIABILITY
The likelihood of trouble -free performance from a component or an assembly. Principally, a function of
MTBF and MTTR.

G-10


---

                                                                                                                                    TM 5-689

RESISTOR
A device or material that develops a voltage drop when current passes through it.

RESPONSE TIME
The time interval for a protective device to respond to a transient over-voltage condition and begin
clamping.

ROTATING FIELD
The electrical field developed in a multi-phase generator. The varying currents through the pairs of stator
windings cause the magnetic field to vary as if it were a single rotating field.

SATURABLE REACTOR
A transformer-like device. One winding has a core that saturates when a small amount of current is
passed through it. This saturation causes a large change in the inductance of the main winding, thus
controlling the current through it.

SENSOR
Any device used to detect electrical variations, temperature variations, etc., within a system.

SHUNT
A device used to convert a large dc current to a low dc voltage for metering purposes.

SHUNT TRIP
An electromagnetic trip used in circuit breakers to allow control circuits to open the breaker.

SOLENOID
A coil used to actuate a relay armature.

SPIKE
An unusually high and sharply defined transient.

STATIC SWITCH
A solid-state switch noted for its high speed. The static switch connects the bypass source to the critical
bus in the event of a UPS failure. It is designed only for momentary use until the bypass breaker has time
to close.

STRESS
External force or action applied to a component or assembly that tends to damage or destroy it.

SUBSTATION
A facility where power at lower levels is taken from the high voltage transmission line. Houses step-
down transformers and switchgear required for local distribution.

SUPPRESSOR
A device that is used to arrest (keep down) excessive force, such as voltage transients. Will suppress
unwanted voltage above a specified level.

SURGE
A sudden rise of current or voltage.

                                                                                                                                          G-11


---

TM 5-689

SURGE CURRENT
The current flowing in a circuit associated with a transient over-voltage condition.

SWITCHGEAR
Any switches, relays, or protective devices used to control power distribution.

SYNCHRONOUS MOTOR
An ac motor whose speed is exactly proportional to the power input frequency.

THREE-PHASE POWER
Three separate outputs from a single source. There is a phase difference of 120 degrees between any two
of the three voltages.

TRANSDUCER
Any device that senses one form of energy and converts it to another, as sound, force, temperature, or
humidity to electrical energy, or vice versa.

TRANSFER
Refers to the act of switching the critical load from the UPS to the bypass source or from the bypass
source to the UPS.

TRANSFER SWITCH
One used to transfer the load from one source of power to a different source of power.

TRANSIENT
A high-amplitude, short-duration pulse superimposed on the normal voltage.

TRANSMISSION LINE
The conductors used to carry electrical energy from one location to another.

TRAVELING WAVE
One that moves along a transmission line in both directions from any point where a step voltage change
occurs.

TRIP/TRIP CONDITION
If a major alarm condition is detected, the UPS will automatically remove itself from the sync bus and
shut itself down. This is known as a “trip.” Any condition that results in a trip is a trip condition.

UNINTERRUPTIBLE POWER SUPPLY (UPS)
A power source consisting of a rectifier, inverter, and batteries, continuously supplying power to a load
from the inverter.

VOLT
Unit of measurement of electromotive force or potential difference. Symbol E, in electricity; symbol V in
semiconductor circuits.

VOLTAGE
A derivative electrical quantity, E, measured in the unit volts and defined in terms of the independently
obtained ampere, 1, and the unit of resistance, ohm (R) by ohms law E = IR.

G-12


---

                                                                                                                                    TM 5-689

VOLTAGE CONTROL
A mode of regulation for the rectifier/charger or the inverter in which the output voltage is regulated to a
constant value.
VOLTAGE DROP
Difference in potential between two points in a passive component or circuit.
VOLAGE REGULATOR
A circuit that develops a constant output voltage regardless of input voltage variation.
VOLTAGE REGULATION
1) The process of holding voltage constant between selected parameters, the extent of which is expressed
as a percent. 2) The relative percent change of voltage during (cell/battery) discharge.
WYE
A three-phase source or load connection, with a single common junction and three-phase lines out or in.

                                                                                                                                          G-13


---

                                                                                                                                          TM 5-689

The proponent agency of this publication is the Chief of Engineers, United States Army.
Users are invited to send comments and suggested improvements on DA Form 2028
(Recommended Changes to Publications and Blank Forms) directly to HQUSACE, (ATTN:
CEMP-SP), Washington, DC 203 14-1000.

By Order of the Secretary of the Army:        ERIC K. SHINSEKI
                                        Genera/, United States Army
Officib ~ ~
    B JOEL B. HUDSON                              Chief of Staff

Administrative Assistant to the
      Secretary of the Army

Distribution:

         To be distributed in accordance with Initial Distribution Number (IDN) 344736,
requirements for non-equipment TM 5-689.


---

PIN: 079244-000


--- 