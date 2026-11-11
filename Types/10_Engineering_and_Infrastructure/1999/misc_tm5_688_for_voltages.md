# misc_tm5_688_for_voltages  TM 5-688

FOREIGN VOLTAGES
        AND

FREQUENCIES GUIDE

APPROVED FOR PUBLIC RELEASE DISTRIBUTION IS UNLIMITED

HEADQUARTERS, DEPARTMENT  OF THE ARMY
                               12 NOVEMBER 1999


---

           REPRODUCTION AUTHORIZATION/RESTRICTIONS

This manual has been prepared by or for the Government and, except to the extent
indicated below, is public property and not subject to copyright.

Reprint or republication of this manual should include a credit substantially as fol-
lows: “Department of the Army, TM 5-688, Foreign Voltages and Frequencies
Guide, 12 November 1999.”


---

TECHNICAL MANUAL                I                                                                                                                TM 5-688
No. 5-688
                                Approved for public release; distribution                                                      HEADQUARTERS
                                                                                                                     DEPARTMENT OF THE ARMY

                                                                                                              Washington, DC, 12 November 1999

                                                                                                             is unlimited.

                                     FOREIGNVOLTAGESAND FREQUENCIESGUIDE

                                                                                                                              ParaaraDh &

Chapter 1.     INTRODUCTION                                                                                  ...........      l-l          1-l
Chapter 2.     Purpose ..........................
               scope ...........................                                                              ...........     l-2          1-l
               References .........................                                                          ...........
                                                                                                                           .  l-3          l-l
                                                                                                             ..........
               EQUIPMENT SENSITIVE TO FREQUENCY AND VOLTAGE LEVELS                                           ..........
                                                                                                             ..........
               Theoretical overview                 .....................                                                     2-l          2-l
                                                                                                             ..........
               Heating, ventilating, and air conditioning (HVAC) ...........                                 ..........       2-2          2-3
                                                                                                             ..........
               Electrical distribution and protection ................                                       ..........       2-3          2-3

               Medium voltage distribution equipment: 50 Hz 60 Hz ..........                                                  2-4          24

               Safety and security equipment ..................                                                               2-5          25

               Communication equipment ...................                                                                    2-6          2-5

               Lighting ..........................                                                                            2-7          2-5

               Other electrical equipment            ...................                                                      2-8          2-5

Chapter 3.     EQUIPMENT DERATING
Appendix A.
               Derating under 50 Hz conditions .................                                             ...........      3-l          3-l

               Heating, ventilating, and air conditioning (HVAC) for derating .......                        ...........      3-2          3-l
                                                                                                             ...........
               Electrical distribution and protection ................                                       ...........      3-3          3-l
                                                                                                             ...........
               Safety and security equipment for derating ..............                                     ...........      3-4          3-2
                                                                                                             ...........
               Communication    equipment for derating                     ...............                   ...........      3-5          3-2
                                                                                                             ...........
               Lighting for derating ......................                                                  ...........      3-6          3-2

               Other electrical equipment for derating ...............                                                        3-7          3-2

               Derating under alternate voltage conditions.                .............                                      3-8          3-2

               Recommendations       ......................                                                                   3-9          3-3

               Summary .........................                                                                              3-10         3-3

               REFERENCES . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .A-1

Appendix B. FREQUENCY AND SINGLE- AND THREE-PHASE VOLTAGE LEVELS BY COUNTRY .                                                              &l

Appendix C. DERATING FACTORS.                        . . . . . . . . . . . . _ . _ _ . . . . . . . . . . . . . . . . . . . C-l

                                                                                            IJST OF FlGulEs

Number                                                                                                                              &gg

2-l. Simplified twowinding transformer.              . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2-l

2-2. Magnetization  curve for the transformer’s iron core . . . . . . _ . . . . . . . _ . _ . . . . . . . . . . . . 2-2

                                                                                            LIST OF TABLE

Number              and single and threephase        voltage levels by country                                                                                                                   f&g
El. Frequency                                                                               . . . . . _ . . . . . . . . . . . . . . . . . . B-l


---

                                                        TM 5-688

  CHAPTER 1
INTRODUCTION

1-1. Purpose.                                           1-2. Scope.

This manual provides guidance required to identify      This manual identifies the classes of electrical equip-
the voltage and frequency standards of various for-     ment that are sensitive to frequency and voltage varia-
eign countries for both medium and low voltage sys-     tions. Appendix B covers identification of various low
tems. It also identifies the classes of equipment that  and medium voltage levels, along with the system fre-
are sensitive to voltage and frequency differences.     quencies, used by countries around the world. Derating
Foreign countries around the world use different        factors are discussed and developed for the six gener-
electrical standards for voltage and frequency than     ic types of equipment in chapter 3. Appendix C sum-
those of the United States. Some electrical equip-      marizes the derating factors presented in chapter 3 for
ment will operate properly at an electrical frequency   different voltage and frequency environments.
of either 50 or 60 Hz. Equipment designed for 60
Hz that will not operate properly at 50 Hz is termed    1-3. References.
“50 Hz sensitive,” and equipment designed for 50
Hz that will not operate properly at 60 Hz is termed    Appendix A contains a list of publications referenced in
“60 Hz sensitive.”                                      this manual.

                                                        1-1


---

                                                                                                    TM s-688

                               CHAPTER2
EQUIPMENTSENSITIVETO FREQUENCYAND VOLTAGELEVELS

2- 1. Theoretical overview.                                  transformer depends on several natural laws including
                                                             the following-
 Equipment sensitive to frequency and or voltage is
 designed to operate within certain tolerances. Most             (1) A sinusoidal, time-varying flux, 0, linking a
 equipment is sensitive to large changes in the supply       conducting circuit produces a voltage, e, in the circuit
 voltage level because more current will flow through a      proportional to d @/dt (i.e., Faraday’s law of induc-
 device when the voltage level of the supply is              tion).
 increased (the current through the device is equal to
 the voltage across the device divided by the                    (2) The algebraic sum of the Voltages around any
 impedance of the device). When a larger current             closed path in a circuit is zero (i.e., Kirchhoff’s voltage
-flows, the heat dissipated in the device increases (the     law).
 heat dissipated by the device is proportional to the
 square of the current). Thus, doubling the voltage will         (3) The voltage, v, in a circuit induced by a chang-
 typically double the current, resulting in the device dis-  ing flux is always in the direction in which current
 sipating four times the heat. Most devices cannot toI-      would have to flow to oppose the changing flux (i.e.,
 erate this amount of heat and cannot operate reliably       Lenz’s law).
 with a supply voltage level more than 10 percent or so
 higher than their rated voltage.                              c. When the sinusoidal voltage, v, is impressed onto
                                                             the primary electrical winding of Nt turns, it is expect-
   a. An additional complication arises in the case of       ed that a sinusoidal current, I, will begin to flow in the
 devices that use magnetic coupling. Since most electri-     circuit, which in turn will produce a sinusoidally vary-
 cal equipment depends on a magnetic field as the            ing flux, @. For simplicity, it is assumed that all of the
 medium for transferring and converting energy, the fol-     flux set up by the primary circuit lies within the trans-
 lowing paragraphs discuss a basic transformer to            former’s iron core and it therefore links with all the turns
 explain how the magnetic circuit depends on the fre-        of both windings. If the flux at any instant is represent-
 quency and amplitude of the applied voltage.                ed by the equation:

   b. A transformer enables electrical energy to be trans-           @= 0m sin 2xft

 ferred with high efficiency from one voltage level to       where:
 another at the same frequency. Consider a simplified
 view of a transformer with a sinusoidal voltage source,     @,,, = the maximum  value of the flux
 v, applied to the primary circuit and the seconday cir-     f = the frequency
 cuit open, as shown in figure 2-1. The operation of the     t = time,

Figure 2- 1 Simplified twowinding transformer
                                                                                             2-l


---

TM s-688                                                   ondary circuit. If the core flux is in the direction indi-
                                                           cated (with the flux increasing), then by Lenz’s law,
it follows from Faraday’s law (i.e., e = N d 0/dt) that
                                                           the polarity of E2 will be such that current It will flow
the instantaneous voltage el induced in the primary
winding is:                                                in the secondary winding in attempt to decrease the
                                                           core flux. The amount of secondary current that will
el = 27t f NI 0m cos 2x f f                                flow will depend on the value of /?tood (that is, /Z =
                                                           E2/Rtood), and the power delivered to the load will
The polarity of el will be according to Lenz’s law, and
hence will be in opposition to the impressed voltage, v    equal E&. It is important to understand the mecha-
(figure 2-l). The root mean square (rms) value of el is
                                                           nism by which the power is transferred from the pri-
        El = (2n AZ/ f N] 0m = 4.44f N, 0m                 mary circuit to the load. Consider a situation when
                                                           current is suddenly allowed to flow in the secondary
 d. Remembering Kirchhoff’s voltage law, and assum-        winding by closing the switch. As mentioned previ-
                                                           ously, the action of this current will be to decrease the
ing that the winding resistance is relatively small, E,    core flux. Decreasing the core flux would lower the

must be approximately equal to V, where V represents       value of El, which would be in violation otKirchhoff’s

the rms value of the applied voltage. One important        voltage law (KVL). Since KVL must be satisfied, more
result from this equation is that the value of the maxi-   current must flow in the primary winding. The steady-
mum flux, @,.,,, is determined by the applied voltage. In  state result is that the primary current will increase to
other words, for a given transformer, the maximum          the value sufficient to neutralize the demagnetizing
value of the flux is determined by the amplitude and fre   action of the secondary current. It is important to real-
quency of the voltage applied to the primary winding.      ize that the resultant flux in the core remains the some
The same flux that caused Et in the primary winding        regardless of the loading on the transformer. If the
will also induce a voltage across the terminals of the
secondary winding. Thus, the only difference in the rms    level of core flux were to vary with load, then El and
values of the two voltages will come from the difference   E2 would also vary, which is contrary to what is
in the number of turns. if the secondary winding has N2
turns, the seconday voltage can be written as:             observed in practice.

                   E2=4.44fN2@,,                             f. An iron core is used in transformers because it pro
                                                           vides a good path for magnetic flux and directs the flux
Dividing Equation  3 by Equation  4 gives the familiar     so it predominantly links all of the turns in each winding.
relationship:                                              However, the core has its limitations and can carry only
                                                           so much flux before it becomes saturated. Core saturo-
  e. Consider next when the transformer is loaded          tion occurs when all of the magnetic domains of the iron
with a resister /&d by closing the switch in the sec-      align, resulting in a condition in which no further
                                                           increase in flux density over that of air can be obtained.
                                                           Consider the magnetizing curve in figure 2-2, showing
                                                           flux versus magnetizing current, where the magnetizing
                                                           current i, is the steady-state component of current

                                                              Magnetizing Cumnt
                                                                        fv

                                       Figure 2-2. Magnetization curve for the transformer’s iron core

2-2


---

required to establish the resultant flux level in the iron                                                           Th4 s-688
core for the transformer. It is typical for 0 transformer, or
any other magnetic circuit, to be designed for operation       its rating in the 50 Hz environment. For the motor to
close to the “knee” of this curve (i.e., @,,,) to use as       deliver the some mechanical power at Q lower speed, it
much of the iron core as possible. Beyond @r,,ax, the          must deliver more torque since output power equals
iron saturates and it becomes extremely difficult to fur-      torque times the shaft speed. If the motor delivers more
ther increase the flux level. The curve implies that forc-     torque, more current will flow in the motor and on over-
ing the iron core into saturation con result in a signifi-     loaded condition may result. Hence, a 60 Hz motor
cant increase in the value of the magnetizing current,         may hove to be derated to handle the extra current flow.
and hence, con cause the windings to become over-
loaded and the transformer to overheat.                          c. Another concern with operating a 60 Hz motor
                                                               with a 50 Hz voltage source is with saturating the iron
g. This study is concerned primarily with equipment            core of the motor. Like the transformer, the maximum
                                                               value of flux in the core depends directly on the ampli-
sensitive to 50 Hz and voltage levels since the equip          tude of the applied voltage and inversely on the fre
                                                               quency. Assuming that the some voltage level is
ment will be used overseas where voltage frequencies           applied to the 60 Hz motor in the 50 Hz environment,
                                                               the reduction in frequency to 50 Hz would require on
and levels typically ore different from those in the United    increase in core flux of 20 percent (that is, 6/5 of its
                                                               60 Hz level). If the iron core of the motor is unable to
States. This equipment could be listed by item, but a          provide the extra flux, the core will saturate, and a sig-
                                                               nificant increase in the stotor currents con result, caus-
more useful format results when it is divided into classes     ing the motor to overheat.

and subclasses of equipment from which manufacturers            d. Step-down transformers typically ore needed to

for specific pieces of equipment can be easily selected.       transform local voltage levels to the levels the equipment
                                                               is designed for. In most cases, the equipment contains
Following this format, listed below ore the brood class-       some sort of step-down transformer that typically has to
                                                               be changed to convert the higher input voltage to the
es of equipment sensitive to 50 Hz and building voltage        some output voltage. In cases where no step-down trans-
                                                               former is in the equipment, one must be added to ovoid
levels. Each section contains specific classes and sub         burning out components by subjecting them to a higher
                                                               supply voltage. Determining the need for a stepdown
classes of equipment. Additionally,  each section              transformer and adding it to the equipment is easily
                                                               accomplished, and is discussed further in chapter 3.
describes why the equipment is sensitive to voltage fre        Equipment that cannot be purchased with the precise
                                                               specifications needed must be purchased in U.S. speci-
quency and or level. Equipment that does not readily fit       fications and then denoted as described in chapter 3.

into any other category is listed in paragraph 2-8.            2-3. Electrical distribution and protection.

M&ating,   ventilation, and air-conditioning                   Electrical distribution equipment includes transformers,
        .                                                      panelboards and switchboards, generators, transfer
                                                               switches, capacitors, and related equipment. Electrical
HVAC equipment includes boilers, furnaces, water               protection devices include fuses, circuit breakers,
chillers, humidifiers, fans, compressors, evaporators,         relays, reclosers, and contoctors. The devices hove dif-
and related equipment. Certain issues must be consid-          ferent sensitivities to supply voltage and frequency, and
ered when using HVAC equipment in 50 Hz and alter-             ore discussed below.
note voltage environments, including the motor speed
and step-down transformers for power supplies.                   a. Electrical distribution. As mentioned earlier, trans-
                                                               formers ore sensitive to the frequency and amplitude of
  a. The objective of on HVAC system is to provide the         the supply voltage. Using a 60 Hz transformer in a 50
necessary heating and cooling to a building according          Hz electrical environment con cause the core of the
to the design specifications. Typically, alternating cur-      transformer to saturate, overheating the transformer.
rent (AC) motors ore used in HVAC systems to drive             Other than the potential problem with saturation, the
fans, pumps, and compressors. When 60 Hz motor is              transformer should be fully capable of supplying the
run off a 50 Hz supply, the shaft speed of the motor is        nameplate rated load. Most transformers ore available
reduced by 5/6 since the motor speed is directly relat-        in 50 Hz or 50/60 Hz configurations, so saturation
ed to the frequency of the applied voltage. This speed         should not be a problem.
will affect all directdrive applications. For example, a
pump that is directly coupled to the motor shaft will                                                                                     2-3
transfer less fluid over time if the shaft speed is reduced.
Consequently, directdrive HVAC applications must be
derated to account for the reduced motor speed.
However, for driven equipment that is tied to the motor
through adiustoble pulleys, the speed of the driven
device con be increased to the necessary level.

  b. Regardless of how the driven equipment is coupled
to the motor, the 60 Hz motor must still operate within


---

TM s-688

    (1) Panelboards, switchboards, and load centers ore        b. Electrical protection. Electrical protection devices
generolly not sensitive to supply frequency, except
when protective devices such as circuit breakers ore          vary in their sensitivity to supply frequency. All protec-
included in them. These items con be acquired readily         tion devices ore available in Q wide range of voltage
in a wide variety of voltage ratings; therefore, supply       ratings so the level of the supply voltage is not a con-
voltage does not pose a problem.                              cern. The main concern with protection devices is the
                                                              change in response time from 60 Hz to 50 Hz. These
(2) General output voltage con be increased or                devices are coordinated to protect the distribution sys-
                                                              tem from faults (shorts or spikes) but ore connected so
decreased by using on appropriate  transformer.               they do not trip when anticipated voltage spikes (that
                                                              is, motor starting) occur. The power system design engi-
However, since generators ore typically used to supply        neer must be sure to use the proper trip curves for the
                                                              environment when coordinating protective devices. Trip
backup power when the utility power source foils, and         curves for 50 Hz ore readily available from vendors
                                                              contacted in this study. The only device designed dif-
or ore used in addition to the utility power source, it is    ferently for 50 Hz and 60 Hz is the circuit ebreaker.

necessary for the generator to provide o 50 Hz volt-          2-4. Medium voltage distribution equipment:

age source to match the utility supply. Therefore the         50 Hz + 60Hz.

user must purchase a generator configured for 50 Hz           In this section medium voltage transformers, switchgear
                                                              and associated auxiliary devices will be examined with
operation.                                                    respect to frequency and voltage changes.

    (3) Automatic source transfer switches ore sensitive      o. Medium voltage distribution  transformers.
to supply voltage frequency and amplitude because
they ore electronically controlled and hove power             Distribution transformers ore key components in any
supplies that expect to operate on 60 Hz and rated
voltage. Once again, supply voltage level is not a            electric power distribution system. It is important that
problem since transformers ore available to adapt
voltage levels. Supply frequency, however, may be Q           they ore properly matched to their environment. Issues
problem depending on the type of power supply the
electronics use.

                                                              related to operating Q 60 Hz transformer from a 50 Hz

    (4) Related equipment includes meter centers, and         power source were discussed earlier in this manual. The
sockets or receptacles. Meter centers ore sensitive to volt-
age level and frequency. Consequentiy, using a 60 Hz          emphasis here will be on discussing issues concerning
meter center in o 50 Hz environment may result in inac-
curate readings. However, meters ore readily available        operating 50 Hz transformers in a 60 Hz environment.
in Q variety of voltage levels and 50 Hz configurations.
                                                                  (1) An important parameter to consider when oper-
    (5) Sockets or receptacles ore needed when foreign        ating a transformer, or other iron corebased devices, is
consumer products ore to be used with the power sys-          the ratio of amplitude to frequency of the applied volt-
tem. Receptacles ore configured for different voltage         age. The ratio obtained using the nameplate rated volt-
levels, and these configurations vary in different coun-
tries. It is important that the standard receptacle style     age and frequency should be compared with the ratio
for a given voltage be used to ovoid confusing the user
and creating Q potential safety hazard.                       available at the proposed site. If the ratio is less than or
                                                              equal to that obtained using the nameplate quantities,
    (6) Capacitors ore used in on electrical distribution     magnetic saturation will not be a problem at the new
system to odjust the power factor or phase angle              site. Any time the ratio is higher than nameplate, the
between the voltage and current waveforms. It is desir-       manufacturer should be contacted to ensure that the
able to hove Q phase angle close to zero, or a power          transformer has enough reserve available to accommo
factor close to one so that most of the power transferred     date the increase in operating magnetic flux density.
to the load is real power. Real power is the only part of
the total kilovolt-amperes transferred that con do work.          (2) For example, consider o transformer that is
The balance is called reactive power and cannot do            brought over from Germany where it was used on a 10
any useful work. Th e operation of Q capacitor depends        kV, 50 Hz distribution system. It WQS determined that
on the supply frequency, since a capacitor’s                  the electrical insulation system of the transformer WQS
impedance, Xc, is related to the capacitance and fre          rated for 15 kV. It is desired to use the transformer on
quency of the current passing through it by the equation      a 13.8 kV, 60 Hz system. Considering the magnetic cir-
                                                              cuit, the volts-per-hertz ratio of the 50 Hz transformer is
xc = 1 (j27tf C), where C is the capacitance in farads        200 (i.e., 10 kV/50 Hz). On the new supply the ration
                                                              would be increased to 230 (that is, 13.8 kV/60 Hz),
and j equals the square root of -1.                           requiring a higher magnetic flux density in the iron
                                                              core. This increase could potentially saturate the iron
                                                              core and overheat the transformer. Alternatively, this

2-4


---

                                                                                                          TM s-688

transformer could be used on Q 7.2 kV/60        Hz system      b. Medium voltage switchgeor. Switchgear is Q gen-
(120 volts-per-hertz ratio), where saturation   would not
be a problem.                                                 eral term covering switching and interrupting devices
                                                              alone, or their combination with other associated con-
    (3) A few words should be mentioned concerning            trol, metering, protective, and regulating equipment.
iron core loss in transformers. The two primary compo         Common switchgear components include the power
nents of core loss ore eddy-current loss and hysteresis       bus, power circuit breaker, instrument transformers,
loss. Eddycurrent loss is the term used to describe the       control power transformer, meters, control switches,
power loss associated with circulating currents that are      protective relays and ventilation equipment. The ratings
found to exist in closed paths within the body of Q iron      of switchgear assemblies ore designations of the oper-
material and cause undesirable heat production.               ational limits under specific conditions of ambient tem-
Hysteresis loss represents the power loss associated          perature, altitude, frequency, duty cycle, etc. For exam-
with aligning and realigning the magnetic domains of          ple, the performance of some 50 Hz magnetic type cir-
iron in accordance with the changing magnetic flux.           cuit breakers may be altered slightly when operated on
Both components ore dependent on the frequency, OS            a 60 Hz power system. Switchgear manufacturers
shown in the following equations:                             should always be consulted to identify the frequency
                                                              response of circuit breakers andbll auxiliary devices.

        peddy - current = Ke f 2 B2rnT2v                      2-5. Safety and security equipment.

                                                              Safety and security equipment includes fire detection

        physteresis = Khf ev                                  systems, burglar alarm systems, doorbells, and

                                                              surveillance systems. This equipment typically oper-

where,                                                        ates on low voltage, either alternating current (AC)

                                                              or direct current (DC), generated initially by a

K = constant value dependent upon     material                power supply. Acquiring the proper power supply to

f = frequency of variation of flux                            convert from the supply voltage to the low voltage

B = maximum flux density                                      that these systems expect (typically 6 to 12 VAC or
v = total volume of the material
                                                              VDC) is the key to proper operation of these systems
Z= lamination thickness.
                                                              in foreign environments.  Power supplies of 50

                                                              Hz/120 VAC usually ore available from vendors of

(4) It should be noted that, even though frequency            these systems, and a transformer con be used to step

increases when using 50 Hz transformers on a 60 Hz-           o 240 VAC supply down to Q 120 VAC foreign envi-

based system, the voltagetofrequency  ratio will typical-     ronment. Therefore, derating is not necessary for

ly be lower, and hence, the maximum flux densities B          these items, although Q transformer may be needed

will be lower. The result is that core-losses will generally  to step high voltage supply levels down to 120 VAC

not increase OS a result of the higher frequency used.        for the power supplied to these systems. Most ven-

                                                              dors of safety and security equipment con configure

    (5) Other key parameters ore voltage and current. To      their equipment to 50 Hz and a variety of voltage
maintain insulation system integrity, rated voltage
and/or current for the transformer should not be              levels.
exceeded. A transformer con be operated on lower
than rated voltage; however, its current rating must not      2-6. Communication equipment.
be violated. Also, the secondary voltage must be
matched to the proper voltage levels.                         Communication  equipment  encompasses       public

                                                              address systems and sound systems, both of which

                                                              operate on o low-voltage DC supply generated by o

                                                              power supply. Power supplies ore available to operate

    (6) In addition to having on iron core, windings, and     on 50 Hz and 240 V supply voltages. In cases where
insulation system, distribution transformers may include
top changers and auxiliory devices. Auxiliary devices         only 120/50 Hz supplies ore available, a step-down
might include fans, current transformers, pressure relief
devices, and lighting arresters. Once again, attention        transformer con be used to step o 240 V supply down
should be focused on devices that use a magnetic field
for transferring or converting energy, such as instrument     to 120 V. The vendors contacted in this study hove stat-
transformers and small motor drives. Even if the volt-
age-to-frequency ratio is found to be lower, manufoc-         ed that they provide 50 Hz power supplies.
turers should be contacted to make sure that all linear
and rotating drive mechanisms will develop adequate           2-7. Lighting.
force and torque to function properly.
                                                              Lighting con be divided into incandescent, fluores-
                                                              cent, and high intensity discharge (HID) categories.
                                                              Incandescent lighting is not frequency-sensitive,
                                                              whereas fluorescent and HID lights ore started by a
                                                              ballast that is sensitive to voltage level and frequency.

                                                                                                          2-5


---

TM 5-688                                                     motor starters consisters of a coil, thermal overloads,
                                                             and a set of contactors (contacts). The thermal over-
All types of lighting are sensitive to the supply voltage    loads, which are essentially circuit breakers, and the
level and cannot be derated for voltage. For example,        contactors are rated to handle a certain amount of cur-
subjecting a 120 V incandescent lamp to a 240 V              rent. Since at 50 Hz, a motor of a given horsepower
source will result in the lamp burning twice as hot,         rating will draw more current than an identically-rated
causing rapid lamp failure. Subjecting the iron core         motor would draw at 60 Hz, the thermal overloads and
ballast use in many HID and fluorescent fixtures to          the contactors must be sized accordingly.
twice its rated voltage will saturate the ballast and will
subject the fixture to much more than its rated current.       b. Computer power supplies include voltage regula-
As with transformers and motors, 60 Hz iron-core bal-        tors, isolation transformers, transient voltage suppressor
lasts can also be saturated when operated at 50 Hz.          transformers, computer regulator transformers, and
At first thought, frequency dependence may not be OS         power conditioning transformers. Computer power sup
much of a problem with electronic ballasts since, in         plies are sensitive to both frequency and voltage level.
most cases, the AC voltage source is first converted
back to a high frequency AC source, and therefore,             c. Clocks are sensitive to supply frequency and volt-
the voltage source that is actually impressed across         age. Clocks rely on the frequency of the supply voltage
the lamp is decoupled from the 60 Hz AC source.              to keep correct time, so a clock designed for 60 Hz
However, the power supply used to power the elec-            will not keep correct time at 50 Hz. The motor that runs
tronics in these ballasts must be capable of 50 Hz           the clock is also sensitive to supply voltage level.
operation.                                                   Therefore, a clock must either be purchased config-
                                                             ured for the supply voltage level, or a transformer must
2-8. Other electrical equipment.                             be used to convert the supply voltage level to the
                                                             clock’s rated voltage level. Clocks cannot be derated
Other electrical equipment includes motors, motor            for frequency, and therefore clocks designed for 50 Hz
starters, computer power supplies, and clocks.               must be purchased.

  a. Typically, motor starters are sensitive to both supply
voltage level and frequency. The most commonly used

2-6


---

                                                             TM 5-688

       CHAPTER 3
EQUIPMENT DERATING

3-1. Derating under 50 Hz conditions.                        operated safely while overloaded continuously by 20
                                                             percent. The same motor can be operated safely with a
Derating factors for 50 Hz operation are developed           rated mechanical load and a 50 Hz power supply with
differently for different types of equipment. Derating       no horsepower derating, assuming saturation is not an
factors for HVAC, electrical distribution and protec-        issue, the thermal limit of the motor is not exceeded, and
tion, safety and security equipment, communication           the same voltage amplitude is applied. However, a 60
equipment, lighting, and other electrical equipment          Hz motor, with a 1.0 service factor, driving a rated
are discussed below.                                         mechanical load would have to be derated for horse
                                                             power by 20 percent, since it is not capable of handling
3-2. Heating, ventilating, and air conditioning              greater than the rated current. In summary, the user
                                                             should find out the service factor and thermal limit of the
(HVAC) for derating.                                         motor to determine the amount of horsepower derating
                                                             required, and to ensure that the 20 percent increase in
The frequency of the supply voltage affects two types of     current level in the motor does not exceed the motor’s
components in HVAC systems: motors and controls. From        rating (again, assuming saturation is not a concern].
the discussion in paragraph 2-2, for the same mechani-
cal load and voltage level, a 60 Hz motor will draw 20         b. Another issue to be considered when purchasing
percent more current when supplied from a 50 Hz volt-        HVAC equipment for a 50 Hz environment is that the
age source. This assumes the iron core of the motor does     motor’s shaft will spin 5/6 as fast as it would with a 60
not saturate. Therefore, a 60 Hz motor would have to be      Hz supply. For a 4-pole motor, the shaft will rotate at
capable of handling the increase in current level.           roughly 1500 RPM when run off a 50 Hz supply, where
However, as was also mentioned in the previous chapter,      as with a 60 Hz voltage source it will rotate at about
saturation can be a serious problem when running a 60        18OO RPM. Consequently, equipment that is directly
Hz motor off a supply frequency of 50 Hz. Developing a       coupled to the shaft of the motor will rotate at 5/6 the
derating factor to account for saturation is not possible,   speed it would in a 60 Hz environment. Hence, direct-
since the motor designs vary from vendor to vendor, and      drive equipment must be derated to account for the
hence, the degree of saturation that would occur, if any,    change in speed. In cases where the equipment is indi-
would be impossible to predict. Consequently, it is rec-     rectly coupled to the motor shaft, through the use of
ommended that no horsepower derating be performed,           adiustable pulleys for example, the reduction in shaft
and a 50 Hz motor be purchased.                              speed is not as much of a problem since the required
                                                             speed of rotation can be obtained through the proper
  a. However, if the vendor can guarantee the user that      adjustment or selection of the pulleys.
a given 60 Hz motor would not saturate at 50 Hz, then
the motor would need only to be derated to handle the          c. Additionally, electronic HVAC controls that contain
20 percent increase in current level. The amount of          their own power supply may be 50 Hz sensitive. Most
horsepower derating required would depend on the             of the vendors contacted stated that this typically is not
motor’s mechanical load, service factor, and thermal         a problem because most controls are frequency-sensi-
limit. The service factor is a measure of how much the       tive. If the control are 50 Hz sensitive, they must be pur-
motor can be overloaded continuously without exceed-         chased in a 50 Hz configuration. The HVAC vendor
ing safe temperature limits. The thermal limit is the mini-  must be consulted on a case-bycase basis to determine
mum speed at which an AC motor can be operated with          if the controls can be used in 50 Hz environments.
rated amperes, without exceeding safe temperature rise.
The thermal limit is important because the motor’s abili-    3-3. Electrical distribution and protection.
ty to cool itself will be reduced at lower speeds unless,
of course, some sort of auxiliary cooling is used. In most   In general, a 60 Hz transformer should not be used
cases, however, the minimum shaft speed necessary to         with a 50 Hz voltage source because of the potential
exceed the thermal limit is much lower than 1500 revo-       saturation problem. As with motors, a derating factor
lutions per minute (RPM, for example, for a 4-pole           cannot be developed to account for saturation because
motor), so 50 Hz operation should not be a problem,          of the many different transformer designs on the mar-
although the vendor should be contacted for verifica-        ket. It is recommended that a 50 Hz transformer be pur-
tion. A 60 Hz motor with a 1.20 service factor can be
                                                                                                                            3-1


---

TM 5-688                                                    not be derated, and power supplies insensitive to fre
                                                            quency do not need to be derated. In cases where the
chased for use with a 50 Hz voltage source. However,        power supplies are sensitive to 50 Hz, vendors are
if a 60 Hz transformer vendor can ensure that a trans-      able to ship the equipment with a 50 Hzcompatible
former will not saturate when operated at 50 Hz, the        power supply.
transformer should be fully capable of safely supplying
its nameplate rated load (that is, no horsepower derat-     3-5. Communication equipment for derating.
ing is required). In terms of the transformer’s equivalent
impedance, sometimes used for power system studies          Communication equipment operates on a low-voltage
(for example, shortcircuit and load-flow analysis), the     DC supply and does not need to be derated for fre-
60 Hz value should be derated by 5/6 to account for         quency. Vendors will either ship the units with frequen-
the reduction in system frequency.                          cy-insensitive power supplies, or they will configure the
                                                            units for 50 Hz operation before shipping.
  a. Power factor capacitors rated at 60 Hz must also
be derated to 50 Hz. Capacitors do not consume any          3-6. Lighting for derating.
real power, but they do consume reactive power. The
rating given to power factor capacitors is given in units   Incandescent lighting is not frequency-sensitive since
of kilovolt-amperes reactive (KVAR), which indicates the    this type of lighting consists of a resistive element (the
amount of reactive power the capacitor will consume at      filament), which is not frequency-sensitive. Fluorescent
the rated frequency. As mentioned in chapter 2, the         and high intensity discharge (HID) lighting, on the other
capacitor’s impedance, X,, is inversely related to fre-     hand, use a ballast to generate the proper lamp volt-
quency. If the frequency drops from 60 to 50 Hz, the        age and to limit the current flowing through the lamp.
impedance will increase to 6/5 of its 50 Hz value.          These ballasts are sensitive to frequency. Because of the
                                                            numerous ballast designs and styles on the market, and
Since the KVAR rating equals V2/Xc, if X, at 50 Hz          the potential saturation problem, a simple derating fac-
                                                            tor cannot be developed and it is recommended that a
increases to 6/5 of its 60 Hz rating, the KVAR rating       vendor supplying 50 Hz-rated ballasts be located.
will decrease to 5/6 of its 60 Hz rating when the
capacitor is used in a 50 Hz environment. Therefore, a      3-7. Other electrical equipment fbr derating.
60 Hz-rated capacitor must have the KVAR rating mul-
tiplied by 5/6 to yield its 50 Hz KVAR rating.              Other electrical equipment consists of motors, motor
                                                            starters, computer power supplies, and clocks. Motor
  b. Other electrical protection and distribution equip     derating was mentioned earlier in the HVAC section of
ment either cannot or should not be derated. Electrical     this chapter. Motor starters are sensitive to frequency as
protection devices are generally able to be used at         well, but indirectly so. Since a 60 Hz motor will draw
either 50 Hz or 60 Hz, but a different trip curve needs     20 percent more current when operated off a 50 Hz
to be used by the power system designer for 50 Hz.          voltage source, assuming the same voltage amplitude is
These 50 Hz trip curves are readily available from ven-     applied and there is no saturation problem, the motor
dors of this equipment, so no derating is necessary. The    starter current rating must be derated by 20 percent to
only exception is that some circuit breakers are            account for the increase in current. Clocks and com-
designed differently at 50 Hz and 60 Hz.                    puter supply equipment are sensitive to frequency and
                                                            cannot be derated. Clocks rely on the frequency of the
  c. Voltage, current, and power meters can be derat-       supply to keep correct time, so a 60 Hz clock will not
ed, but this practice is not recommended. A meter           keep correct time at 50 Hz. Although derating factors
should display the true value it is supposed to measure     could be developed for clocks, they would be mean-
to ensure that the readings are interpreted correctly and   ingless. Computer power supply equipment cannot be
that no dangerous situations result. Meters, therefore,     derated due to the way the equipment is constructed.
should not be derated. Automatic transfer switches use
power supplies that may or may not be frequency-sen-        3-8. Demtirg under ahernate &age conditions.
sitive. Vendors must be contacted regarding 50 Hz con-
figuration of these devices. Electrical generators must     As appendix B shows, standard onephase voltages
be purchased already configured to provide a 50 Hz          around the world are either in the range of 100-l 27
voltage source.                                             VAC or 220-240 VAC. Voltage variations within about
                                                             10 percent of an equipment’s rated voltage are
3-4. Safety and security equipment for derating.            acceptable, so derating for voltage will only be neces-
                                                            sary when a piece of equipment rated for U.S. voltage
Safety and security equipment operate on a low-volt-        (approximately 120 VAC) needs to be operated in an
age AC or DC source that is generated by a power            environment using 220-240 VAC. This would be a dou-
supply. Some power supplies are sensitive to frequen-       bling of rated voltage. None of the equipment sensitive
cy; others are not. In either case, derating is not nec-    to voltage level is capable of surviving this increase
essary since power supplies sensitive to frequency can-

3-2


---

without rapid failure. Thus, no derating factors for volt-                                                                     TM 5-688
age level are offered. Instead, it is recommended that
transformers be used to step the higher voltage level       vendor be contacted to discuss the derating. It is
down to a voltage level in the range of 100-127 VAC,        always preferable to locate a vendor that will supply
which U.S. equipment can tolerate. It has been found,       the equipment with the desired ratings before derating
however, that most vendors of voltage-sensitive equip-      is attempted. The majority of vendors contacted are
ment are able to configure the equipment for 220-240        able to supply equipment rated at 50 Hz and a variety
VAC and corresponding threephase voltage levels.            of voltage levels, so derating should be necessary in
                                                            only a few cases.
3-9. Recommendations.
                                                            3-10. Summary.
Derating factors were discussed and developed for the
six generic types of equipment. Appendix C, which           Appendix B can be used to rapidly identify the stan-
summarizes the discussion of derating factors present-      dard frequency and voltage levels in other countries. In
ed in this chapter, is useful in identifying derating fac-  cases where cities within a country differ in their elec-
tors quickly and easily. Although this chapter presents     trical standards, the cities are listed separately. For
derating factors for equipment, it is recommended that,     countries in which all cities have the same electrical
whenever a piece of equipment is to be derated, the         standards, typically only the capital city is listed. In
                                                            these cases, assume that all cities in the country have
                                                            the same electrical standards.

                                                            3-3


---

                                                                                                                                 TM 5-688

                                           APPENDIX A
                                            References

Electrical Current Abroad-1998 Edition (U.S. Department of Commerce, Bureau of Industrial Economics,
    Superintendent of Documents, PO. Box 371954, Pittsburgh, PA 15250-7954, Stock Number 003-009-00673-2).

International Directory of Electric Utilities, 9th ed. (Utility Data Institute [Division of McGraw-Hill], 1200 G St., NW,
    Suite 250, Washington, DC 20005, January 1996).

World Electricity Supplies (British Standards Institution, 389 Chiswick High Rd., London W4 4AL, England, 1975).
DelToro, Vincent, Basic Electric Machines (Prentice Hall, One Lake St., Upper Saddle River, NJ 07458, 1990)
Elgerd, Olle I., Electrical Energy Systems Theory: An Introduction (McGraw-Hill Companies, Two Penn Plaza, 9th

    Floor, New York, NY 10121-2298, 1971)
Fitzgerald, A. E., Charles Kingsley, and Stephen Umans, Electric Machinery-Fifth Edition (McGraw-Hill Companies,

    Two Penn Plaza, 9th Floor, New York, NY 10121-2298, 1990)
Information Handling Services (IHS Engineering Products, 15 Inverness Way East, Englewood, CO 80112)
Lawrence, Ralph, and Henry Richards, Principles of Alternating Current Machinery-Fourth Edition (McGraw-Hill

    Companies, Two Penn Plaza, 9th Floor, New York, NY 10121-2298, 1953)
Means Electrical Cost Data-14th Annual Edition (R. S. Means Company, Inc., Construction Plaza, 63 Smiths Lane,

    Kingston, MA 02364-0800, 1990)
Means Mechanical Cost Data-9th Annual Edition (R. S. Means Company, Inc., Construction Plaza, 63 Smiths Lane,

    Kingston, MA 02364-0800, 1990)

                                                                                                                                        A-1


---

                                                                                                                                           TM 5-688

                                               APPENDIX B
              Frequency and Single- and Three-PhaseVoltage levels by Country

This appendix covers identification of various           low and medium voltage       levels, along with the system frequencies,
used by countries around the world.

                                         Table 5 I. Frequency and Sing/e and Three-Phase Voltage levels by Country

Country/City                             Frequency (Hz)  Number of Phases  Low Voltage (V)                   Medium Voltage (kV)

Afghanistan                              50              1.3               220/380                           3.2, 6, 10, 15, 20
Algeria
                                         50              1,3               127/220                           5.5, 6.6, 10, io

                                                                           220/380

American Samoa                           60              1,3               120/240                           NA

                                                                           240/480

Angola                                   50              1,3               220/380                           NA

Antigua                                  60              1,3               230/400                           NA

Argentina                                50              1,3               220/380                           6.6, 13.2, 33

Australia                                50              1,3               240/4 15                          6.6, 7.6, 11, 12 7. 19. 22, 33, 66
Austria
                                         50              1,3               220/380                           3, 5, 6, 10, 20, 25, 28, 30

Azores                                                                                                       NA
        Ponto Delgada
                                         50              133               110/190
       All Others
                                                                           220/380
Bahamas
                                         50              1,3               220/380

                                         60              1,3               120/240                           7.2, 11

                                                                           120/208

Bahrain                                                                                                      11
       Awali
       All Others                        60              1,3               230/400

                                         50              183               230/400

Bangladesh                               50              1,3               220/380                           1 1, 33 (various seasanally)
Barbados
                                         50              1,3               115/230                           11.24

                                                                           115/200

  Belgium                                50              1,3                     220                         6.6, 10, 15, 36, 70’
          Anderlecht                                                                                         cities listed.
          Antwerpen                      50              1,3               127/220

          Brugge                                                           220/380
          Brussels
                                         50              1,3               220/380
          Charlerio
          Gentbrugge                     50              1,3               127/220
          Hasselt
                                                                           220/380
          Hoboken
                                         50              1,3               230/400
          “UY
*Voltages listed are country-inclusive,  50              1,3               220/380

                                         50              1,3               130/220

                                                                           220/380

                                         50              1,3               127/220

                                                                           220/380

                                         50              1,3                     220

                                         all voltages listed for the country may not be found in individual

                                                                                                                                                 B-l


---

TM s-688                   Table 5 I. Frequency and Single and ThreePhose Voltage levels by Country-Continued

  Country/City             Frequency [Hz)  Number of Phases  Low Voltage (V)  Medium Voltage (kV)

   Belgium (continued)     50              183               127/220
          Jette
          Leige            50              1,3               220/380
          LiegeMonsinport
                           50              1,3               11 o/220
          Lokeren
          Leuven                                             220/380
          Mechelen
          Mons             50              1,3               220/380
          Namur
          Oostende         50              1,3               220/380

          Ronse            50              1,3               220/380
          Seraing
          Turnhout         50              1,3               220/380
          Uccle
          Vilvoorde        50              1,3               220/380

  Belize                   50              1,3               127/220
          Belize City
                                                             220/380
          Balmopan
                           50              1,3               220/380
          Corozal Town
                           50              1,3               220/280                                           .
          Orange Walk
          San lgnacio      50              1,3               220
          Stann Creek
          Punta Gorda      50              1,3               220/380

          San Pedro        50              1,3               120/220

  Benin                                                      220/380

  Bermuda (Island-wide)                                                       6.6, 22’

  Bolivia                  60              1,3               11 o/220
          Calamarca
          Chollapata                                         220/440
          Cobija
          Cochabamba       60              1,3               11 o/220
          Guayaramerin
          La Paz                                             220/240
          Potosi
          Oruro            60              1,3               11 o/220
          Riberalta
          Santa Cruz                                         220/440
          Sucre
          Trinidad         60              1                 11 o/220
          Tupiza
          Viacha           60              1                 11 o/220
          Villazon
                           60              1                 11 o/220
   Bosnia/Herzogovino
                           60              1,3               11 o/220
   Botswana
                                                             220/440
   Brazil
           Barbacena       60              1                 11 o/220
           Blumenau
           Braganca        50              1,3               220/380          15,20

B-2                        60              f,3               120/240          NA

                                                             120/208

                                                                              6.6, 24.9*

                           50              1,3               230/400

                           50              113               220/380

                           50              1,3               230/400

                           50              1,3               220/380

                           50              1,3               230/400

                           50              1,3               9??/230

                           50              1,3               220/380

                           50              I,3               11 o/220

                           50              183               230/400

                           50              1,3               220/380

                           50              1,3               220/380

                           50              1,3               230/400

                           50              1,3               220/380

                           50              1,3               11 o/220

                           50              113               220/380

                           NA              NA                NA               6.6, 10

                           50              1,3               220/380          1 1, 33, 66

                                                                              6, 11.4, 13.8, 22, 25, 34.5*

                           60              1,3               11 o/220

                           60              1,3               220

                           60              1,3               11 o/220


---

Country/City                    Frequency (Hz)  Number of Phases  Low Voltage (V)  Medium Voltoge (kV)  TM s-688
                                                                                                               B-3
Brazil (continued)              60              1,3               220/380
       Brasilia
       Caxias do Sul            60              183               220/380
       Cel Fabriciano
       Corumba                  60              1,3               11 o/220
       Florianopolis
       Fortalezo                60              1,3               11 o/220
       Goiania
       Goias                    60              1,3               220/380
       ltajai
       Jooo Pessoa              60              I,3               230/400
       Joinville
       Jundiai                  60              1,3               220/380
       Livromento
       Londrino                 60              1,3               220/380

                                60              1,3               220

                                60              113               220

                                60              1,3               220/380

                                60              183               110

                                60              183               220/380

                                60              1,3               127/220

        Macapa                  60              113               11 o/220 .
        Moceio                                                    11 o/220
        Manaus
        Mossoro                 60              1,3               220/380
        Notal
        Novo Friburgo           60              1,3               120/240
        Olindo
                                60              1,3               220/380

                                60              133               220/380

                                60              1,3               220

                                60              1,3               127/220

                                                                  220/380

        Paranaguo               60              1,3               11 o/220
        Parnaibo
        Pelotas                 60              1,3               11 o/220
        Petropolis
                                60              1,3               220/380

                                60              1,3               127/220

                                                                  115/220

        Ponto Grossa            60              1,3               220
        Port0 Velho
        Sonto Andre             60              1,3               11 o/220
        Sao Bernaroo do
        Sao Coetano do          60              1,3               115/230
        Sul
        So0 Luis         Campo  60              1,3               115/230
        So0 Paul0
        Teresina                60              1,3               11 o/220
        Volta Rendonda
        All Others              60              1.3               11 o/220

                                60              1,3               115/230

                                60              1,3               11 o/220

                                60              1,3               125/216

                                60              1,3               127/220

Brunai                          NA              NA                NA               11,68

Bulgaria                        50              1,3               220/380          NA

Burma/Myanmar                   50              1,3               230/400          3.3, 6.6, 11, 33

Burundi                         50              1,3               220/380          6.6, 15

Cambodia                                                                           4.4, 6.3, 15’
       Phnom-Penh
       Sihonoukville            50              1,3               220/380
       All Others
                                50              1,3               220/380

                                50              1,3               120/208

Cameroon                                                                           10, 15, 30, 33, 55*
        Buea
        Eseko                   50              1,3               230/400
       Maroua
       Mbalmayo                 50              1,3               1271220

                                50              1,3               127/220

                                50              1,3               127/220

                                                                  220/380

        Nkongsambo              50              1,3               127/220

                                                                  220/380

        Sangmelima              50              1,3               127/220

                                                                  220/380


---

TM s-688                    Table B I. frequency and Single and Three-Phase Voltage Levels by Country-Continued

  Country/City              Frequency (Hz)  Number of Phases  Low Voltage (Vj  Medium Voltage (kV)
  Cameroon (continued)
                            50              1,3               230/400
          Victoria
          Yaounde           50              1,3               127/220
          All Others
                                                              220/380
   Canada
                            50              1,3               220/380
  Canary Islands
                            60              1,3               120/240          2.4, 4.16, 7.2, 8, 12.47, 13.8, 14.4,
  Cape Verde (Praia)
  Coyman blonds                                                                20, 25, 34.5, 44, 49
  Central African Republic
  Chad                      50              113               127/220          NA
   Channel blonds
                                                              220/380
          Alderney
          Guernsey          50              1,3               220/380          6, 6.3, 13, 15, 20
          Jersey
   Chile                    60              1,3               120/240          NA                                .
  China
  Colombia                  50              1,3               220/380          NA
          Bogota
          Duitama           50              1,3               220/380          15
          Honda
          Sogomosa                                                             11
          All Others
   Congo                    50              1,3               240/4 15
   Costa Rica
   Croatia                  50              183               230/400

   Cyprus                   50              113               240/4 15
   Czech Republic
                            50              1,3               220/380          12, 13.2, 13.8, 15, 23
   Denmark
   Djibouti                 50              113               220/380          10, 20, 35
   Dominican Republic
   Ecuador                                                                     4.16, 7.6, 13.2, 13.8, 33, 34.5, 44*

           Cuenco           60              1.3               150/240
           Esmeraldas
           Guaranda         60              1,3               120/208
           lbarra
           Latacunga        60              1,3               120/208
           Loja
           Machala          60              113               120/240

B-4                         60              113               11 o/220

                            50              1,3               220/380          5.5, 6.6, 10, 20

                            50              1,3               120/240          4.2, 13.2, 24.9, 34.5

                            50              113               220/380          10,35

                            50              1,3               240/4 15         11

                            50              183               220/380          6, 10 (urban)

                                                                               22, 35 (rural)

                            50              1,3               220/380          6, 10, 20, 30

                            50              1,3               220/380          NA

                            60              1,3               11 o/220         2.5, 4.16, 12.5

                                                                               13.8, 34.5, 46, 69*

                            60              1,3               120/208

                            60              1,3               120/208

                                                              120/240

                            60              f,3               120/208

                                                              120/240

                            60              f,3               127/220

                            60              f,3               120/208

                            60              183               127/220

                            60              1,3               127/220


---

                                                                                                          TM s-688

Country/City                  Frequency (Hz)  Number of Phases  Low Voltage M  Medium Voltage (kV)
Ecuodor [continued]
                                       60                1.3        120/208    3, 6.6, 11, 20, 33, 66
       Morona                          60                1,3        127/220    4.16, 4.4, 13.2, 23, 34.5
        Portoviejo                     60                1,3        127/220
        Puyo                           60                1,3        120/208
       Quito                           60                1,3        127/220
        Riobamba                       60                1,3        11 o/220
       Tulcan                          60                113        121/210
       Zamora                                                       127/220
       All Others                      50                1,3        121/210
                                       60                1,3        127/220
Egypt                                                               120/208
El Solvador                                                         127/220
England (see United Kingdom)
Equatorial Guinea                                                   220/380
Ethiopia
Faroe Islands                                                       115/230
Fiji
Finland                       50              1                 220            NA
France
                              50              113               220/380        15
        I’Alpe d’Huez
       Alencon                50              1,3               220/380        NA
       Amiens
       Angers                 50              113               240/4 15       11
       Angouleme
       hnecy                  50              1,3               220/380        10, 20, 30, 45
       Arcachon
        Argenteuil                                                             3.3, 5.5, 10, 15, 20, 30’
        Asnieres
        Lobule                50              1,3               127/220
        Besoncon
        Beziers                                                 220/380
        Biarritz
        BoulognesurMer        50              1.3               127/220
        lo Bourboule
        Bourges                                                 220/380
        Bourg-EwBresse
                              50              1,3               115/220

                                                                220/380

                              50              1,3               127/220

                                                                220/380

                              50              1,3               127/220

                                                                220/380

                              50              1,3               127/220

                                                                220/380

                              50              1,3               127/220

                                                                220/380

                              50              l-3               127/220

                                                                220/380

                              50              1,3               115/200

                                                                220/380

                              50              1,3               127/220

                                                                220/380

                              50              183               127/220

                                                                220/380

                              50              113               127/220

                                                                220/380

                              50              1,3               127/220

                                                                220/380

                              50              1,3               127/220

                                                                220/380

                              50              1,3               127/220

                                                                220/380

                              50              f,3               127/220

                                                                220/380

                              50              1,3               127/220

                                                                220/380

                                                                                                          B-5


---

TM s-688                    Table 5 I frequency and Single and Three-Phase Voltage Levels by Country-Continued

  Country/City              Frequency [Hz)  Number of Phases  Low Voltage (v)  Medium Voltage (kV)
  France (continuedj
                            50              I,3               127/220
          Brest
          Brioncon                                            220/380
          Cabourg
          Caen              50              I,3               115/200
          Calais
          Cauterets         50              1,3               127/220
          Cholons
          Chateauroux                                         220/380
          Choumont
          Cherbourg         50              1,3               127/220
          Chinon
          Clermont-Ferrond  50              1,3               115/220
          Collioure
          Courbevoie                                          220/380
          Deauville
          Dieppe            50              1,3               127/220
          Dijon
          Dinan             50              1,3               127/220
          Douai
          Dreux                                               220/380
          Etain
          Evreux            50              113               120/208
          Fontainbleau
          Frejus                                              220/380
          Grenoble
          LeHavre           50 1,3 120/208 .

          Jounge                                                                          220/380
          Juan-ies-Pins
          Lens              50              1,3               127/220
          Lille
          Luchon                                              220/308
          LuxeuiCBoins
          Lyon              50              1,3               127/220

          LeAtans                                             220/308
          Marly-feRoi
                            50              1,3               127/220
B-6
                                                              220/308

                            50              1,3               127/220

                                                              220/380

                            50              1,3               115/230

                            50              1.3               127/220

                                                              220/380

                            50              1,3               127/220

                                                              220/380

                            50              1,3               127/220

                                                              220/380

                            50              1,3               127/220

                                                              220/380

                            50              1,3               127/220

                                                              220/380

                            50              1,3               127/220

                                                              220/380

                            50              1,3               115/200

                                                              220/380

                            50              1,3               127/220

                            50              1,3               127/220

                                                              220/380

                            50              1,3               127/220

                                                              220/380

                            50              1,3               127/220

                            50              1,3               110/190

                                                              127/220

                                                              220/380

                            50              1,3               127/220

                                                              220/380

                            50              1,3               127/220

                            50              1,3               127/220

                                                              220/380

                            50              1,3               11 o/220

                                                              220/380

                            50              1,3               127/220

                                                              220/380

                            50              1,3               127/220

                                                              220/380

                            50              1,3               11 o/220

                                                              127/220

                                                              220/380

                            50              1,3               127/220

                                                              220/380

                            50              1,3               127/220

                                                              220/380


---

Country/City                   Frequency (Hz)  Number of Phoses  Low Voltoge (V)  Medium Voltage (kV)  TM s-688
France (continued)                                                                                             B-7
                                        50                1,3    115/200
       Marseille                        50                1,3
       Megev                            50                1,3    220/380
       Metz                             50                113
       Lemont-Dore                      50                1.3    127/220
       Motlucon                         50                1,3
       Morzine                          50                1,3    110/190
       Mulhouse                         50                1.3
       Nancy                            50                1,3    220/380
       Nantes                           50                1,3
       Neuilly                                                   127/220
                                        50                1,3
       Nice                             50                1,3    220/380
       Nimes                                              1,3
       Orleans                          2:                1,3    127/220
       Paris                            50                1,3
       Perpignan                        50                113    220/380
       Roanne                           50                1,3
       LaRochelle                                                127/220
                                        50                1,3
       Roubaix                          50                1.3    220/380
       Royan                            50                183
       Saint-Etienne                                             230
                                        50                1.3
       SaintGervois-les-Bains           50                1,3    220/380
        Saint-JeandeLux                 50                1,3
        Saint Lo                        50                1.3    127/220
       Saint Quentin                                      1,3
        Sallanches                      z:                1,3    220/380
        Strasbourg                      50                1,3
       Tabes                            50                113    110/190          .
        Toulon                          50                133
        Tourcoing                       50                1,3    115/230
        Tours                           50                1,3
        Val d’ lsere                    50                1,3    127/220
        Valenciennes                    50                 1,3
        Valloire                        50                 1,3   220/380
        Verdun                           50                1,3
        Versailles                      50                 1,3   127/220
        Vichy                           50                 1.3
        Vincennes                       50                 1,3   220
        All Others
                                                                 220/380

                                                                 127/220

                                                                 115/230

                                                                 127/220

                                                                 220/380

                                                                 127/220

                                                                 220/380

                                                                 115/200

                                                                 127/220

                                                                 220/380

                                                                 220/380

                                                                 127;220

                                                                 220/380

                                                                 115/230

                                                                 127/220

                                                                 220/380

                                                                 127/220

                                                                 220/380

                                                                 380

                                                                 127/220

                                                                 220/380

                                                                 127/220

                                                                 220/380

                                                                 127/220

                                                                 125/220

                                                                 220/380

                                                                 115/200

                                                                 220/380

                                                                 127/220

                                                                 220/380

                                                                 11 o/220

                                                                 220/380

                                                                 127/220

                                                                 127/220

                                                                 220/380

                                                                 127/220

                                                                 220/380

                                                                 127/220

                                                                 127/220

                                                                 220/380

                                                                 127/220

                                                                 220/380

                                                                 127/220

                                                                 220/380

                                                                 127/220

                                                                 220/380

                                                                 220/380


---

TM s-688                Table 5 I. frequency and Single and ThreePhase Voltage Levels by Country-Continued

  Country/City          Frequency (Hz)  Number of Phases  Low Voltage (V)  Medium Voltoge (kV)
   French Guiana
  Gabon                 50              1,3               220/380          NA
  Gambia
  Germany               50              1,3               220/380          5.5, 20
  Ghana
  Gibraltar             50              1,3               220/380          11,33
  Greece
  Greenland             50              1,3               220/380          3, 6, 10, 20, 30, 45, 60

  Grenada -             50              1,3               220/400          1 1, 33, 34.5
  Guadeloupe
  Guam                  50              1.3               240/4 15         NA

  Guatemala             50              1,3               220/380          6.6, 15, 20, 22
  Guinea
  GuineoBissau          50              1.3               220/380          NA                               .
  Guyana
   Hoiti                50              1,3               230/400          NA

          Cap Hoitien   50              1,3               220/380          20
          Gonaives
          All Others    60              1,3               11 o/220         4, 13.8
   Honduros
   Hong Kong                                              120/208
   Hungary
   Iceland              60              1,3               120/240          22, 34.5, 50
   India
           Bombay City  50              133               220/380          5.5, 6.3, 15, 20, 30
           Madras
           Mussoorie    50              113               220/380          6, 10, 20, 30
           Naini Tal
           New Delhi    50              1,3               11 o/220         2.3, 4, 11, 13.8
           Patna
           Simla                                                           2.4, 4.2, 7.2, 12.5*
           All Others
   Indonesia            60              1,3               120/208
           Jakarta
           All Others   60              1,3               120/208
   Iran
   Iraq                 50              1,3               11 o/220

B-8                     60              1,3               11 o/220         2.4, 4.2, 13.8, 34.5, 69

                        50              183               200/346          11,33

                        50              1,3               220/380          6, 10, 20, 22, 30, 35

                        50              1,3               220/380          6, 11, 22, 33

                                                                           2.2, 3.3, 6.6, 11, 15, 11 l

                        50              1,3               230/400

                                                          230/460

                        50              1,3               230/400

                                                          250/440

                        50              1,3               220/380

                        zi              1,3               220/380          11

                                        1,3               230/400

                                                          230/4 15

                        50              1,3               220/380

                        50              1,3               220/380

                        50              1,3               230/400

                                                                           3-20’

                        50              1,3               220/380

                        50              1,3               127/200

                        50              1,3               220/380          11, 20, 33, 63, 66

                        50              183               220/380          6.6, 11


---

                                                                                                      TM s-688

Country/City        Frequency (Hz)     Number of Phases  Low Voltage (V)  Medium Voltoge (kV)
                             50                   1,3                     5, 10, 20, 38
Ireland                      50                   1,3        220/380      NA
                             50                   1,3                     6.3, 12.6, 22, 33’
Isle of Man                  50                   1,3        240/4 15
                             50                   1,3                     3.6, 10, 15, 20, 30, 45, 66
Israel                                                       230/400
        Jerusalem   50                 1,3                   220/380      NA
                                                                          6.9, 13.8, 24
Italy               50                 1,3                   127/220      3, 6, 6.6, 11, 20, 22, 60*
                                                             220/380
Ivory Coast                         I                                                           M
                                                             220/380
Jamaica             50                 1,3
                                                             11 o/220
Japan               50                 1,3
        Chiba                                                100/200
        Hakodote    50                 I,3                   100/200
        Kowosaki                                             100/200
        Muroron     50                 1,3                   100/200
        Niigata                                              100/200
        Otoru       50                 1,3                   100/200
        Sapporo                                              100/200
        Sendai      50                 1,3                   100/200
        Tokyo                                                100/200
        Yokohomo    50                 1,3                   100/200
        Yokosuka                                             100/200
        All Others  50                 1,3                   100/200

Jordan              50                 I,3                   220/380

Kenya               50                 I,3                   240/4 15

Korea               50                 1,3                   11 o/220
                                                             120/208
Kuwait              60                 1,3                   220/380
                                                             120/240
Laos                50                 113                                6.6, 11, 33
                                                             240/4 15     11, 33, 40, 66
Lebanon             50                 1,3                                22.9
        Tripoli                                              220/380
                    60                 1,3                                NA
        Zahleh                                               110/190      6.6, 22
        All Other   60                 1,3                   220/380      11,15,33*
                                                             220/380
Lesotho             60                 1,3                   110/190      11,33
                                                                          7.2, 12.5
Liberia             60                 1                     120/240      NA
                                                             120/208
Libya               50                 1,3                                5, 15, 20, 65
        Barce                                                120/240
        Benghazi    50                 1,3                   120/208
        Darnah
        Al Boyda    50                 1,3                   230/400
        Sebha                                                230/400
        Tubruq      50                 1,3                   230/400
        All Other
                    50                 113                       230
Luxembourg                                                       230
                    50                 113                   230/400
                                                             127/220
                    60                 1,3
                                                             120/208
                    50                 1,3                   220/380

                    50                 1,3

                    50                 1,3

                    50                 183

                    50                 1

                    50                 1,3

                    50                 1,3

                    50                 1,3


---

TM s-688                    Table B I. Frequency and Single and ThreePhose Voltage Levels by Country-Continued

  Country/City              Frequency (Hz)  Number of Phases  Low Voltage (V)  Medium Voltage (kV)

Macau                       50              1,3               220/380          11

Macedonia                   NA              NA                NA               6.6, 10

Madagascar                                                                     5, 20, 35’
       Ambatolampy
       Ambatondrazaka       50              1,3               220/380
       Tulear
       All Others           50              183               220/380

                            50              1,3               220/380

                            50              1,3               127/220

                                                              220/380

Majorca Island              50              1,3               127/220          NA

                                                              220/380

Malawi                      50              1,3               230/400          3.3, 11, 33, 66                  -

Molaysia                    50              1,3               240/4 15         6.6, 11, 22, 33

Maldives                    50              1,3               230/400          11

Mali, Republic of           50              113               220/380          15,30

Molto                       50              1,3               240/4 15         6, 11

Martinique                  50              1,3               220              NA

Mauritius                   50              1,3               230/400          6.5, 22

Mexico                      60              1,3               127/220          6.6, 13.2, 13.8, 23, 34.5, 44, 69

Monaco                      50              1,3               127/220          10,20

                                                              220/380

Montserrot                  60              1,3               230/400          NA

Morocco                                                                        5.5, 20, 22*

        Agadir              50              1,3               127/220

                                                              220/380

        Beni-Mellal         50              133               127/220

                                                              220/380

        El-Haceima          50              1,3               220/380

        Khemisset           50              1,3               220/380

        Kheniha             50              1,3               220/380

        Oued-Zem            50              1,3               127/220

                                                              220/380

        Sidi Kacem          50              1,3               127/220

                                                              220/380

        Sidi Slimane        50              1,3               127/220

                                                              220/380

        Souk-El-Arba Gharb  50              1,3               127/220

                                                              220/380

        All Others          50              1,3               127/220

Mozambique                  50              1,3               220/380          6.6, 11, 22, 33

Myanmar/Burma               50              1,3               230/400          3.3, 6.6, 11, 33

Nepal                       50              1,3               220/440          11,33

Netherlands                                                                    5.3, 6, 10, 12.5, 20, 25’

        Amsterdam           50              1,3               220/380

                                                              220

        Delft               50              1,3               220/380

                                                              220

        All Others          50              1,3               220/380

B-10


---

                                                                                                    TM s-688

Country/City                Frequency (Hz)  Number of Phases  Low Voltage (VJ  Medium Voltage (kV)
                                                                               NA
Netherlands Antilles                 60                 1         115/230
Aruba:                               60                183        127/220      NA
                                     60                113        127/220
        Logo Colony                 50                 1,3        127/220      11             .
        Oranjestad                  50                 I,3        223/380
        San Nicolas                 50                 1.3        127/220      13.8, 24.9
Bonaire:                            60                 183        120/208      5.5, 15,20
        Kralendijk                  50                 1,3        220/380      11,33
Curococo:                           50                 1,3        230/400      NA
        Emmostad                    60                 1,3
       Willemstod                   50                 1.3        120/240      NA
St. Martin:                         50                 1,3        220/380
        Philipsburg                 50                 1,3        230/415      11,33
                                                                               11,33
New Coledonio                       60                  1             230
                                    60                  1                      11, 12, 34.5*
New Zealand                         50                 1,3        120/240
                                                                  100/200      11,22
Nicaragua                           50                 1,3        240/4 15     23
                                    50                 1,3                     5, 10, 20, 30*
Niger                               50                 183        220/380
                                                                  220/380      2.4, 4.8, 6.24, 7.62, 13.2, 13.8, 34.5*
Nigerio                             60                 1,3        230/400
                                    60                 1,3                     6, 15, 20, 30, 40, 60
Norway                              60                 1,3        115/230      6, 10, 15, 30, 40, 60
                                    60                 1,3        115/230      4.16, 13.2
Okinawa                             50                 113        126/208      11
       Military Facilities          50                 1,3        120/240
       All Cities                                                 11 o/220
                                    50                 1,3        240/4 15
Oman                                60                 183        220/380
                                    60                 113
Pakistan                                                              220
        Hyderobad                   60                 I,3        11 o/220
        Karachi                      60                1,3
       All Others                    50                1,3            220
                                     50                1,3
Panamo                               60                183        115/230
       Colon                        50                 183        11 o/220
        Panoma City                                               11 o/220
                                                                  220/380
        Puerto Armuelles                                          220/380
       All Others                                                 120/240
                                                                  240/4 15
Papua New Guinea

Paraguay

Peru
       Arequipa
       Talara
       All Others

Philippines
        Manila

        All Others

Poland

Portugal

Puerto Rico

Qatar

                                                                                                    B-11


---

TM s-688                   Table B I. Frequency and Single and Three-Phose Voltage Levels by Country-Continued

  Country/City             Frequency (Hz)  Number of Phases  Low Voltage (V)  Medium Voltage (kV)

   Romania                 50              1,3               220/380          6, 10, 20

   Russia                  50              183               220/380          NA

   Rwanda                  50              183               220/380          6.6, 15, 30

   St. Kitts and Nevis     60              1,3               230/400          NA

   St. Lucia               50              1,3               240/4 16         11

   Son Marino              NA              NA                NA               15

   St. Vincent             50              1,3               230/400          6.3, 11, 33

   Saudi Arabia                                                               13.8, 33, 34.5, 69’               .
          Al Khobar
          Buraydah         60              I,3               127/220
          Dammam
          Hufuf            50              1,3               220/380
          Jiddah
          Mecca            60              1,3               127/220
          Medina
          Riyadh           50              1,3               230/400
          Taif
                           60              I,3               127/220
   Senegal
                           50              1,3               230/400
   Serbio
                           60              1,3               127/220
   Seychelles
                           60              1,3               127/220
   Sierra Leone
                           50              1*,3              230/400
   Singopore
                           50              1,3               127/20           5.5, 16.6, 30
   Slova Republic
                           50              1,3               220/380          10, 20, 35
   Slavenia
                           50              1,3               240              11
   Somalia
          Berbera          50              1,3               230/400          11
          Bravo
          Chisimaio        50              1,3               230/400          6.6, 22
           Hargeysa
          Marka            NA              NA                NA               6, 10, 22, 35
          Mogadishu
                           NA              NA                NA               6.6, 10
   South Africa/Namibia
           Beaufort west                                                      3,15*
           Benoni
           Boksburg        50              1,3               230
           Cradock
           Germiston       50              1,3               220/440
           Grahaamstad
           Keetmanshoop    50              1,3               220
           King Williams
                           50              1,3               220
           Klerksdorp
           Kraanstad       50              1,3               120/220
           Paarl
           Port Elizabeth  50              1,3               220/380
           Pretoria
           Roodepoort                                                         6.6, 11, 22, 33*

B-12                       50              1,3               230/400

                           50              1,3               230/400

                           50              1,3               230/400

                           50              1,3               230/400

                           50              1,3               230/400

                           50              1,3               250/430

                           50              1,3               230/400

                           50              1,3               220/380

                                                             250/433

                           50              1,3               230/400

                           50              1,3               230/400

                           50              1,3               230/400

                           50              183               250/433

                           50              1,3               240/4 15

                           50              1,3               230/400


---

                                                                                                             TM5688

Country/City                    Frequency (Hz)  Number of Phoses  Low Voltage (V)  Medium Voltage (kV)

South Africa/Namibia   {cont.]
        Somerset West
        Springs                 50              1,3               230/400

        Stellenbosch            50              1,3               220/380
        Umtata
        Upington                                                  230/400
       Virginia
       Vryheid                  50              3                 220/380
       Walvis Bay
       Wellington               50              1,3               230/400
       Worcester
       All Others               50              1,3               230/400

Spain                           50              1,3               230/400

                                50              1,3               230/400

                                50              1,3               230/400

                                50              1,3               230/400

                                50              1,3               230/400

                                50              1,3               220/380

                                50              1,3               127/220          3, 6.6, 10, 11.6, 15, 20, 33

                                                                  220/380                         .

Sri Lanka                       50              1,3               230/400          11,33
Sudan
Suriname                        50              l?                240/4 15         11,33
Swaziland
Sweden                          60              113               115/230          33
Switzerland
Syria                           50              1,3               230/400          11,33
Tahiti
Taiwan                          50              1,3               220/380          3, 6, 7, 10, 20. 30
Tanzania
Thailand                        50              1,3               220/380          1, 16, 50
Togo
                                50              1,3               220/380          20
        Lome
        All Others              60              1,3               127/220          4.8, 14.4, 20
Tonga
Trinidad and Tobago             60              1,3               11 o/220         2.3, 3.3, 5.9, 11 4 22 8

                                50              1,3               230/400          11,33

                                50              1,3               220/380          3.5, 11, 12, 22. 24. 33

                                                                                   5.5, 20, 33’

                                50              1,3               127/220

                                                                  220/380

                                50              183               220/380

                                50              183               240/4 15         11

                                60              1,3               115/230          6.6, 12

                                                                  230/400

Tunisia                                                                            10, 15,30’
       Ariana
                                50              1,3               127/220
        Bardo
                                                                  220/380
        Bejo
        Bizerte                 50              183               127/220
        Carthage
        Gafsa                                                     220/380

        Hammam-Lif              z:              183               127/220
        Kairouan
        La Goulette                             113               127/220
        La Mono&a
        La Marsa                50              1,3               127/220
        Mateur
                                50              1,3               127/220

                                                                  220/380

                                50              1,3               127/220

                                50              1,3               127/220

                                50              1,3               127/220

                                2:              1,3               127/220

                                                1,3               127/220

                                50              1,3               127/220

                                                                                                                 B-13


---

TM S-688

                          Table 5 I. Frequency and Single and Three-Phase Vohoge levels by Country-Continued

Country/City              Frequency (Hz)  Number of Phases  Low Voltage M  Medium Voltage (kVJ

Tunisia [continuedj       50              1,3               127/220
        Menzel Bourguiba
        sfax              50              1,3               127/220

                                                            220/380

       Sousse        ^    50              1,3               127/220

       Tunis              50              1,3               127/220

                                                            220/380

       All Others         50              1,3               220/380

Turkey                                                                     6.3, 10.5, 15, 34.5*
        Istanbul
                          50              1,3               11 o/220
       All Others
Uganda                                                      220/380

                          50              1,3               220/380

                          50              1,3               240/4 15       11,33                              .

United Arab Emirates                                                       6.6, 11, 33’

       Abu Dhabi          50              1,3               240/4 15

       Ajman              50              113               230/400

       Dubai              50              1,3               220/380

United Kingdom:

       England            50              153               240/480        3.5, 6.6, 11, 22, 33,66

                                                            240/4 15

       Scotland           50              1,3               240/4 15       6.6, 11, 22, 33

       Northern Ireland   50              183               220/380        6.6, 11, 33

                                                            230/400

United States of America  60              1,3               120/240        2.4, 4.16, 4.8, 6.9, 8.32, 12, 12.47,

                                                            120/208        13.2, 13.8, 14.4, 19.9, 20.8, 22.86,

                                                                           23, 24.94, 34.5, 46, 69

Upper Volta               50              1,3               220/380        NA

Uruguoy                   50              1,3               220            6, 15, 30, 60

Venezuela                 60              1,3               120/240        2.4, 4.16, 4.8, 12.47, 13.8

Vietnam                                                                    6.6 (south)

       Ban Me Thout       50              1,3               220/380        10 (north)

       Can Tho            50              113               127/220        15 (middle)

                                                            220/380        35 (entire)

       Dalat              50              1,3               120/208

                                                            220/380

       Da Nang            50              183               127/220        Note: State has plans to change to

       Hue                50              1,3               127/220        22 kV for whole country.

       Khanh Hung         50              1,3               220/380

       Saigon             50              1,3               120/208

                                                            220/380

Virgin Islands            60              1,3               120/240        NA

Western Samoa             50              1,3               230/400        6.6, 22

Yemen                     50              1,3               250/440        NA

Zaire                     50              1,3               220/380        6.6, 15, 20, 30

Zombia                    50              1,3               220/380        11, 33, 66

Zimbabwe                                                                   11, 22, 33, 66*

       Bulawayo           50              1,3               230/400

       All Others         50              1,3               220/380

B-14


---

                                                                                                                                             TM 5-688

                                           APPENDIX C
                                         Derating Factors

C-1. Heating, ventilation, and air conditioning (HVAC).

  a. 50 Hz. The output of directlycoupled, motordriven equipment must be derated to account for the reduction in
shaft speed to 5/6 the 60 Hz value. Otherwise, the mechanical coupling used between the motor and driven equip-
ment should be purchased to give the required rotating speed. HVAC controls that are frequency dependent must be
purchased in 50 Hz configurations.

  b. Voltage. Derating for voltage is not an option.

C-2. Electrical distribution and protection for transformers.
  a. 50 Hz. In general, derating for frequency is not recommended. See chapter 3 for details.

  b. Voltage. Derating for voltage is not recommended. Vendors can provide almost any needed input voltage rat-
ing. Consult vendor regarding derating possibility if derating is absolutely necessary.

C-3. Electrical distribution and protection for power factor capacitors.
  a. 50 Hz. Derate kilovolt-amperes reactive (KVAR) rating by multiplying 60 Hz KVAR rating by 5/6 to yield 50 Hz

WAR rating.

  b. Voltage. Derating for voltage is not recommended. Vendors can provide almost any needed voltage rating.
Consult vendor regarding derating possibility if derating is absolutely necessary.

C-4. Electrical distribution and protection for protection equipment.
  a. 50 Hz. Different trip curves may be needed. Consult vendor for these curves.

  b. Voltage. Derating for voltage should not be needed. Verify with vendor since special protection equipment may
need derating.

C-5. Other electrical distribution and protection.
Derating either cannot or should not be performed. Contact vendors to purchase appropriately rated equipment.

C-6. Safety and security equipment.
  a. 50 Hz. Depends on type of power supply. Derating is either not necessary or not possible. Contract vendor to

purchase appropriately configured power supply.

  b. Voltage. Derating far voltage is not recommended. Contact vendor to purchase appropriately configured power
supply, or use transformer to convert supply voltage level to power supply input level.

C-7. Communication equipment.
  a. 50 Hz. Depends on type of power supply. Derating is either not necessary or not possible. Contact vendor to

purchase appropriately configured power supply.

  b. Voltage. Derating for voltage is not recommended. Contact vendor to purchase appropriately configured power
supply, or use transformer to convert supply voltage level to power supply input level.

C-8. Incandescent lighting.
  a. 50 Hz. No derating necessary. lncandescents are frequency insensitive.

  b. Voltage. Not possible. Bulb life will suffer drastically. Contact vendor to purchase high voltage bulbs, or use trans-
former to convert supply voltage to lamp voltage.

                                                                                                                                         C-1


---

TM 5-688
C-9. Fluorescent and high intensity discharge (HID) lighting.
50 Hz. Derating is not recommended. Fixtures configured for 50 Hz should be purchased.
C-10. Motors.

  a. 50 Hz. In general, derating a 60 Hz motor is not recommended. See chapter 3 for exceptions
 b. Voltage. Derating for voltage is not recommended. Contact vendor to purchase appropriately configured equip-
ment, or use transformer to convert supply voltage to motor’s rated voltage level.
C-11. Motor Starters.
  a. 50 Hz. Derate by multiplying 60 Hz horsepower rating by 4/5 to yield the 50 Hz horsepower rating.
  b. Voltage. Derating for voltage is not possible. Contact vendor to purchase appropriately configured equipment,
or use transformer to convert supply voltage to motor starter’s rated voltage level.
C-12. Clocks.
  a. 50 Hz. Derating is possible but meaningless since 60 Hz clock will not keep correct time in 50 Hz environment
  b. Voltage. Derating for voltage is not recommended. Contact vendor to purchase appropriately configured clocks,
or use transformer to convert supply voltage to clock’s rated voltage level.
C-13. Computer power supplies.
  a. 50 Hz. Derating is not possible due to equipment construction. Contact vendor to purchase 50 Hz rated equip-
ment.
  b. Voltage. Derating for voltage is not possible. Contact vendor to purchase appropriately configured equipment,
or use transformer to convert supply voltage to equipment’s rated voltage level.

C-2


---

I                                                                                                           I

   The proponent agency of this publication is the Chief of Engineers, United States Army.
   Users are invited to send comments and suggested improvements on DA Form 2028
   (Recommended Changes to Publications and Blank Forms) directly to HQUSACE, (ATTN:
   CEMP-SP), Washington, DC 20314-1000.

   By Order of the Secretary of the Army:         ERIC K. SHINSEKI
   Official                                General, United States Army

                                                      Chief of Staff

        JOEL B. HUDSON
Administrative Assistant to the

      Secretary of the Army

Distribution:
To be distributed in accordance with initial Distribution Number (IDN), 344698, requirements for TM 5-688.


--- 