# mcrp_3-40-3c_undated  MCRP 3-40.3C
                                     (Formerly MCRP 6-22D)

Antenna Handbook

           U.S. Marine Corps

                                                                         PCN 144 000062 00


---

                              To Our Readers

 Changes: Readers of this publication are encouraged to submit
 suggestions and changes that will improve it. Recommendations
 may be sent directly to Commanding General, Marine Corps
 Combat Development Command, Doctrine Division (C 42),
 3300 Russell Road, Suite 318A, Quantico, VA 22134-5021 or by
 fax to 703-784-2917 (DSN 278-2917) or by E-mail to
 smb@doctrine div@mccdc. Recommendations should include
 the following information:

      • Location of change
             Publication number and title
             Current page number
             Paragraph number (if applicable)
             Line number
             Figure or table number (if applicable)

      • Nature of change
             Add, delete
             Proposed new text, preferably double-
               spaced and typewritten

      • Justification and/or source of change

 Additional copies: A printed copy of this publication may be
 obtained from Marine Corps Logistics Base, Albany, GA 31704-
 5001, by following the instructions in MCBul 5600, Marine
 Corps Doctrinal Publications Status. An electronic copy may
 be obtained from the Doctrine Division, MCCDC, world wide
 web home page which is found at the following universal refer-
 ence locator: http://www.doctrine.quantico.usmc.mil.

Unless otherwise stated, whenever the masculine or feminine gender
                is used, both men and women are included.


---



---

                   DEPARTMENT OF THE NAVY
              Headquarters United States Marine Corps

                    Washington, D.C. 20380-1775

                                                                 1 June 1999

                               FOREWORD

Communications and information systems (CIS) support collect-
ing, processing, and exchanging information. CIS automate
routine functions, freeing commanders and staffs to focus on the
aspects of command and control that require experience, judg-
ment, and intuition. Personnel who install, operate, and maintain
CIS play a key role in the command and control of the Marine air-
ground task force (MAGTF). It is an understatement to say that
the success of the MAGTF in the modern battlespace depends on
the effective employment of CIS.

One of the most important networks of the MAGTF CIS architec-
ture is single-channel radio (SCR). SCR is the principal means of
communications support for maneuver units. SCR communica-
tions equipment is easy to operate, and networks are easily
established, rapidly reconfigured, and, most importantly, easily
maintained on the move. SCR provides secure voice communica-
tion and supports limited data information exchange. MAGTF
SCR equipment is fielded in many configurations and includes
hand-held, manpack, vehicle-mounted, bench-mounted, and shel-
tered radios. These radios operate in simplex and half-duplex
modes. The most widely employed tactical radios provide inte-
grated communications security (COMSEC) and jam resistance
through frequency hopping.


---

Tactical SCRs operate in the three military radio frequency bands
(high frequency [HF], very high frequency [VHF], and ultrahigh
frequency [UHF]). In the HF band, SCR can support long-range
communications, albeit at the expense of mobility. SCR in the
VHF and UHF bands is normally limited to line of sight. SCR
satellite communications (SATCOM) provide mobility, flexibili-
ty, and ease of operation with unlimited range. Limitations of
SCR include susceptibility to enemy electronic warfare; cosite,
footprint, terrain, and atmospheric interference; the requirement
for close coordination and detailed planning; a need for common
timing, frequency, and equipment; and limited spectrum avail-
ability. The latter is particularly critical for SATCOM.

Of all the variables affecting single-channel radio communica-
tions, the one factor that an operator has the most control over is
the antenna. With the right antenna, an operator can change a
marginal net into a reliable net. Marine Corps Reference Publica-
tion (MCRP) 6-22D, Antenna Handbook, gives operators the
knowledge to properly select and employ antennas to provide the
strongest possible signal at the receiving station of the circuit.

MCRP 6-22D builds on the doctrinal foundation established in
Marine Corps Warfighting Publication (MCWP) 6-22, Communi-
cations and Information Systems. This handbook is intended not
only for CIS officers and radio operators, but for all personnel de-
siring information about antenna fundamentals.

MCRP 6-22D supersedes Fleet Marine Force Reference Publica-
tion (FMFRP) 3-34, Field Antenna Handbook, dated 5 March
1991.


---

Reviewed and approved this date.

BY DIRECTION OF THE COMMANDANT OF THE MARINE CORPS

                              J. E. RHODES
               Lieutenant General, U.S. Marine Corps

                          Commanding General
          Marine Corps Combat Development Command

DISTRIBUTION: 144 000062 00


---

            Antenna Handbook                        Page

                   Table of Contents                  1-1
                                                      1-2
Chapter 1. Radio Principles                           1-2
                                                      1-3
Electromagnetic Radiation                             1-3
Radio Waves                                           1-5
                                                      1-8
   Frequency                                          1-8
   Frequency Calculation                              1-8
   Frequency Bands                                  1-18
Radio Communication Circuit                         1-19
Propagation Fundamentals                            1-19
   Earth’s Atmosphere                               1-21
   Radio Wave Propagation                           1-22
   Other Factors Affecting Propagation              1-23
   Path Loss                                        1-24
   Reflected Waves                                  1-24
   Diffraction
   Tropospheric Refraction, Ducting and Scattering
Noise
   Natural Noise
   Manmade Noise

v


---

_________________________________________ MCRP 6-22D

Chapter 2. Antenna Fundamentals

Section I. Concepts and Terms                      2-2

Forming a Radio Wave                               2-2

Radiation                                          2-2

Radiation Fields                                   2-3

Radiation Patterns                                 2-4

Polarization                                       2-6

Polarization Requirements for Various Frequencies  2-8

Advantages of Vertical Polarization                2-9

Advantages of Horizontal Polarization              2-10

Directionality                                     2-10

Resonance                                          2-11

Reception                                          2-12

Reciprocity                                        2-13

Impedance                                          2-14

Bandwidth                                          2-15

Gain                                               2-16

Take-Off Angle                                     2-18

Section II. Ground Effects                         2-19

Grounded Antenna Theory                            2-19

Types of Grounds                                   2-20

Counterpoise                                       2-22

Ground Screen                                      2-23

Section III. Calculating Antenna Length            2-24

Section IV. Antenna Orientation                    2-26

                            vi


---

Antenna Handbook _________________________________

Azimuth                                              2-26

Improvement of Marginal Communications               2-27

Transmission and Reception of Strong Signals         2-29

Chapter 3. Transmission Lines

Properties                                           3-1

Transmission Line Types                              3-1

Minimizing Energy Loss                               3-3

Impedance                                            3-3

Optimizing Line Length                               3-5

Attenuation                                          3-6

Making the Best Use of Available Transmission Lines  3-7

Twin-Lead Limitations                                3-8

Directly Connecting the Transceiver and Antenna      3-9

Baluns                                               3-10

Cable Connectors                                     3-11

Balanced Antenna                                     3-11

Chapter 4. HF Antenna Selection

Antenna Selection Procedure                          4-2

Determining Antenna Gain                             4-6

Antenna Types                                        4-8

AS-2259/GR                                           4-9

Vertical Whip                                        4-10

Half-Wave Dipole                                     4-14

Inverted Vee                                         4-19

                             vii


---

_________________________________________ MCRP 6-22D

Long Wire                                 4-21

Inverted L                                4-24

Sloping Vee                               4-28

Sloping Wire                              4-33

Vertical Half-Rhombic                     4-37

HF NVIS Communications                    4-40

Chapter 5. VHF and UHF Antenna Selection

Frequencies                               5-1

Polarization                              5-2

Gain and Directivity                      5-2

Gain                                      5-3

Directivity                               5-3

Transmission Lines                        5-4

Radiators                                 5-5

Vertical Radiator                         5-5

Cross Section Radiator                    5-5

Insulation                                5-5

Interference                              5-6

Noise                                     5-6

Multipath Interference                    5-6

Vegetated Areas                           5-8

Antenna Types                             5-9

Vertical Whip                             5-9

OE-254                                    5-10

Antenna Within Vehicle Interior           5-12

HF Antenna Types Usable at VHF and UHF    5-12

Dual-Function Antennas                    5-12

                        viii


---

Antenna Handbook _________________________________

Chapter 6. Field Repair and Expedients

Repair Techniques                             6-1

Whip Antennas                                 6-1

Wire Antennas                                 6-2

Guys                                          6-4

Masts                                         6-4

Tips on Construction and Adjustment           6-4

Constructing the Antenna                      6-4

Adjusting the Antenna                         6-6

Field Expedient Antennas                      6-7

VHF Considerations                            6-7

HF Considerations                             6-7

End-Fed Half-Wave Antenna                     6-8

Center-Fed Doublet Antenna                    6-9

Field Expedient Directional Antennas          6-14

Vertical Half-Rhombic and Long-Wire Antennas  6-14

Yagi Antenna                                  6-14

Vee Antenna                                   6-16

Sloping Vee Antenna                           6-16

Chapter 7. Satellite Communications Antennas

Siting SATCOM Antennas                        7-4

Considerations                                7-4

Determining Horizon Angles                    7-4

                            ix


---

_________________________________________ MCRP 6-22D

Chapter 8. Antenna Farms

Command Post                           8-1

Tactical                               8-1

Main                                   8-2

Rear                                   8-2

Location Selection Considerations      8-2

Doctrinal Considerations               8-2

Tactical Considerations                8-3

Technical Considerations               8-5

Siting VHF Antennas                    8-6

Transmitting Antenna Site              8-9

Receiving Antenna Sites                8-11

Antenna Farm Internal Arrangement      8-12

Frequency Band                         8-12

Antenna Selection and Placement        8-12

Requirements                           8-14

Polarization                           8-15

Power and Signal Lines                 8-16

Antenna Farm Layout Principles         8-16

Appendices

A Glossary                             A-1

B References and Related Publications  B-1

                                x


---

               Chapter 1

       Radio Principles

ELECTROMAGNETIC RADIATION

Electromagnetic radiation includes radio waves, microwaves, infra-
red radiation, visible light, ultraviolet waves, X-rays, and gamma
rays. Together they make up the electromagnetic spectrum. They all
move at the speed of light (186,000 miles/300 million meters per
second). The only difference between them is their wavelength (the
distance a wave travels during one complete cycle [vibration]),
which is directly related to the amount of energy the waves carry.
The shorter the wavelength, the higher the energy. Figure 1-1 lists
the electromagnetic spectrum components according to wavelength
and frequency (the number of complete cycles [vibrations] per sec-
ond). A portion of the spectrum which is used for HF, VHF, and
UHF radio communication has been expanded to show more detail.

RADIO

                               VISIBLEIR UV X-RAY GAMMA- COSMIC-

               UHF                      RAY  RAY
       VHF
HF

                       3 GHz
               300 MHz

       30 MHz
3 MHz

Figure 1-1. Electromagnetic Spectrum.


---

1-2 _____________________________________ MCRP 6-22D

                          RADIO WAVES

Radio waves propagate (travel) much like surface water waves.
They travel near the Earth’s surface and also radiate skyward at var-
ious angles to the Earth’s surface. As the radio waves travel, their
energy spreads over an ever-increasing surface area. A typical radio
wave has two components, a crest (top portion) and a trough (bottom
portion). These components travel outward from the transmitter, one
after the other, at a consistent velocity (speed). The distance between
successive wave crests is called a wavelength and is commonly rep-
resented by the Greek lowercase lambda (λ) (see fig. 1-2).

                                           ONE CYCLE
                                         WAVELENGTH

STRENGTH 0  PEAK

                  PEAK

                                      TIME OR DISTANCE

                        Figure 1-2. Radio Wave.

Frequency

Radio waves transmit radio and television (TV) signals. They have
wavelengths that range from less than a centimeter to tens or even
hundreds of meters. Frequency modulated (FM) radio waves are
shorter than amplitude modulated (AM) radio waves. A radio
wave’s frequency equals the number of complete cycles that occur
in 1 second. The longer the cycle time, the longer the wavelength


---

Antenna Handbook ______________________________ 1-3

and the lower the frequency. The shorter the cycle time, the shorter
the wavelength and the higher the frequency.

Frequency is measured and stated in hertz (Hz). A radio wave fre-
quency is very high. It is generally measured and stated in thousands
of hertz (kilohertz [kHz]), in millions of hertz (megahertz [MHz]),
or sometimes in billions of hertz (gigahertz [GHz]).

1 Hz   = 1 cycle per second
1 kHz  = 1 thousand cycles per second
1 MHz  = 1 million cycles per seconds
1 GHz  = 1 billion cycles per second

Frequency Calculation

For practical purposes, the velocity of a radio wave is considered to
be constant, regardless of the frequency or the amplitude of the
transmitted wave. To find the frequency when the wavelength is
known, divide the velocity by the wavelength.

Frequency (hertz)  = 300,000,000 (meters per second)
                                 Wavelength (meters)

To find the wavelength when the frequency is known, divide the
velocity by the frequency.

Wavelength (meters) = 300,000,000 (meters per second)
                                                 Frequency (hertz)

Frequency Bands

Frequency spectrum designations are—

     HF                  VHF                  UHF
3 to 30 MHz        30 to 300 MHz  300 to 3,000 MHz/3GHz


---

1-4 _____________________________________ MCRP 6-22D

HF is used primarily for long-range communications. An HF signal
is reflected by the outermost portion of the atmosphere, the iono-
sphere. VHF is used for short-range communications. To use VHF,
it is necessary to be able to visualize a direct line of sight (LOS)
between the transmitter and receiver. This limits UHF to distances
that are not much greater than the distance to the horizon, assuming
that there are no massive obstructions in the LOS. When the LOS
path exists and VHF transmission is possible, VHF is always pre-
ferred to HF because a VHF signal can be made to follow a much
narrower and more direct path to the receiver. UHF is a third type of
transmission. UHF transmission is like VHF in that both follow the
direct or LOS path. But with the proper antenna, UHF transmission
can be made to follow an even narrower path to the receiver than
VHF.

Each frequency band has unique characteristics. The ranges and
power requirements shown in table 1-1 are for normal operating
conditions (i.e., proper siting and antenna orientation and correct
operating procedures). Ranges will change according to the condi-
tion of the propagation medium and the transmitter output power.

     Table 1-1. Frequency Range Characteristics.

Band  Ground Wave  Sky Wave        Power
           Range     Range       Required

HF    0–50 miles   100–8000 miles .5–5 kW

VHF   0–30 miles   50–150 miles  .5 or less kW

UHF   0–50 miles   N/A           .5 or less kW

Tactical SCRs operate in the three military radio frequency bands
shown in table 1-2.


---

Antenna Handbook ______________________________ 1-5

           Table 1-2. Ground SCRs.

Frequency    MAGTF SCR        Operating          Typical
   Band    Equipment Used     Frequency       Application
     HF                                    Radio LOS and
     VHF    AN/PRC-104           Range     beyond/long range
            AN/GRC-193        2–29.999
     UHF    AN/MRC-138        MHz          Radio LOS and
                              30–88 MHz    relay/retransmis-
            AN/PRC-68                      sion
            AN/PRC-119        116–150 MHz
            AN/VRC-88 (A, D)  225–400 MHz  Critical LOS
            AN/VRC-89 (A, D)               (ground to air)
            AN/VRC-90 (A, D)               Critical LOS
            AN/VRC-91 (A, D)               (ground to air)
            AN/VRC-92 (A, D)
            AN/GRC-213                     SATCOM footprint
            AN/MRC-145

            AN/PRC-113
            AN/VRC-83

            AN/PRC-113
            AN/VRC-83
            AN/GRC-171

            AN/PSC-3
            AN/PSC-5

            RADIO COMMUNICATION CIRCUIT

The radio equipment for communicating between two stations,
including the path the radio signal follows through the air, is a radio
link. A radio link consists of seven components: transmitter, power
supply, transmission lines, transmitting antenna, propagation path,
receiving antenna, and receiver.


---

1-6 _____________________________________ MCRP 6-22D

The transmitter generates a radio signal. The power supply provides
power for the operating voltage of the radio (battery or generator).
The transmission line delivers the signal from the transmitter to the
transmitting antenna. The transmitting antenna sends the radio
signal into space toward the receiving antenna. The path in space
that the radio signal follows as it goes to the receiving antenna is the
propagation path. The receiving antenna intercepts or receives the
signal and sends it through a transmission line to the receiver. The
receiver processes the radio signal so it can be heard (fig 1-3).

The radio operator’s objective is to provide the strongest possible
signal to the receiving station. The best possible signal is one that
provides the greatest signal-to-noise (S/N) ratio at the receiving
antenna.

To implement a radio communications circuit it is necessary to—

• Generate and radiate an electromagnetic wave modulated with
    information (e.g., voice, Morse code).

• Make the wave propagate efficiently from the transmitting
    antenna to the receiving antenna.

• Intercept the wave by using a receiving antenna.
• Demodulate the energy so that the information originally trans-

    mitted becomes available in a useful form.

Choosing the right antenna and matching its characteristics to the
best propagation path are the two most important factors in setting
up a communications circuit. The weakest link in the communica-
tions circuit is the wrong propagation path. The best transmitter,
antenna, and receiver are of little use if the frequency is wrong or
the propagation path is improper.


---

Antenna Handbook ______________________________ 1-7

                                       PROPAGATION
                                              PATH

TRANSMITTING                                   RECEIVING
    ANTENNA                                    ANTENNA

              TRANSMISSION
                     LINES

              POWER
              SUPPLY

TRANSMITTER                                    RECEIVER

              Figure 1-3. Typical Radio Link.


---

1-8 _____________________________________ MCRP 6-22D

             PROPAGATION FUNDAMENTALS

Earth’s Atmosphere

Propagation usually takes place within the Earth’s atmosphere. The
atmosphere surrounding the Earth is divided into several layers,
each possessing unique characteristics. The first layer, starting at
the Earth’s surface and extending to a height of about 10 kilometers
(km), is the troposphere. In this layer, the air temperature decreases
with altitude at the rate of about 2.5°C every 300 meters.

The second layer of the atmosphere is the stratosphere, which occu-
pies an altitude range extending from about 10 km to 50 km. This
layer of air remains at a nearly constant temperature of about -65°C.

Beginning at about 50 km and extending upward to more than 500
km is the ionosphere. The ionosphere gets its name because the
molecules of its atmosphere are ionized, i.e., electrons have been
stripped away from atoms by the constant bombardment of the
Sun’s rays and other high energy particles released by the Sun.
Because of the large quantities of free electrons, the ionosphere is
capable of interacting strongly on radio waves traveling through it.

Radio Wave Propagation

There are two principal ways radio waves travel from the transmit-
ter to the receiver. One is by ground wave, directly from the trans-
mitter to the receiver. The other is by sky wave, up to the
ionosphere and refracted (bent downward) back to the Earth. Short-
distance, all UHF, and upper VHF transmissions are by ground
waves. Long-distance transmissions are principally by sky waves.
SCR sets can use either ground wave or sky wave propagation for
communications.


---

Antenna Handbook ______________________________ 1-9

Ground Wave Propagation. Radio communications using ground
wave propagation do not use or depend on waves refracted from the
ionosphere (sky waves). Ground wave propagation is affected by
the Earth’s electrical characteristics and by the amount of diffrac-
tion (bending) of the waves along the Earth’s curvature. The ground
wave’s strength at the receiver depends on the transmitter’s power
output and frequency, the Earth’s shape and conductivity along the
transmission path, and the local weather conditions. The ground
wave includes three components: the direct wave, the ground
reflected wave, and the surface wave (fig. 1-4).

                                         DIRECT WAVE

                                   GROUND REFLECTED
                                               WAVE

    SURFACE
      WAVE

                          Figure 1-4. Ground Wave.

Direct Wave. The direct wave travels directly from the transmitting
antenna to the receiving antenna. The direct wave is limited to the
LOS distance between the transmitting antenna and the receiving
antenna plus the short distance added by atmospheric refraction and
diffraction of the wave around the Earth’s curvature. This distance
can be extended by increasing the transmitting or the receiving
antenna height, or both.


---

1-10 ____________________________________ MCRP 6-22D

Ground Reflected Wave. The ground reflected wave reaches the
receiving antenna after being reflected from the Earth’s surface.
Cancellation of the radio signal can occur when the ground
reflected component and the direct wave component arrive at the
receiving antenna at the same time and are 180° out of phase with
each other.

Surface Wave. The surface wave follows the Earth’s curvature. It
is affected by the Earth’s conductivity and dielectric constant.

Frequency Characteristics Of Ground Waves. Various frequen-
cies determine which wave component will prevail along any given
signal path. For example, when the Earth’s conductivity is high and
the frequency of a radiated signal is low, the surface wave is the
predominant component. For frequencies below 10 MHz, the sur-
face wave is sometimes the predominant component. However,
above 10 MHz, the losses that are sustained by the surface wave
component are so great that the other components (direct wave and
sky wave) become predominant.

At frequencies of 30 to 300 kHz, ground losses are very small, so
the surface wave component follows the Earth’s curvature. It can be
used for long-distance communications provided the radio operator
has enough power from the transmitter. The frequencies 300 kHz to
3 MHz are used for long-distance communications over sea water
and for medium-distance communications over land.

At high frequencies, 3 to 30 MHz, the ground’s conductivity is
extremely important, especially above 10 MHz where the dielectric
constant or conductivity of the Earth’s surface determines how
much signal absorption occurs. In general, the signal is strongest at
the lower frequencies when the surface over which it travels has a
high dielectric constant and conductivity.


---

Antenna Handbook ____________________________ 1-11

Earth’s Surface Conductivity. The dielectric constant or Earth’s
surface conductivity determines how much of the surface wave
signal energy will be absorbed or lost. Although the Earth’s surface
conductivity as a whole is generally poor, the conductivity of vary-
ing surface conditions, when compared one with an other, would be
as stated in table 1-3.

Table 1-3. Surface Conductivity.

      Surface Type        Relative Conductivity
Large body fresh water              Very good
Ocean or sea water                  Good
Flat or hilly loamy soil            Fair
Rocky terrain                       Poor
Desert                              Poor
Jungle                              Very poor

Sky Wave Propagation. Radio communications that use sky wave
propagation depend on the ionosphere to provide the signal path
between the transmitting and receiving antennas.

Ionospheric Structure. The ionosphere has four distinct layers. In
the order of increasing heights and decreasing molecular densities,
these layers are D, E, F1, and F2. During the day, when the rays of
the Sun are directed toward that portion of the atmosphere, all four
layers may be present. At night, the F1 and F2 layers seem to merge
into a single F layer, and the D and E layers fade out. The actual
number of layers, their height above the Earth, and their relative
intensity of ionization vary constantly.


---

1-12 ____________________________________ MCRP 6-22D

The D layer exists only during the day and has little effect in bend-
ing the paths of HF radio waves. The main effect of the D layer is to
attenuate HF waves when the transmission path is in sunlit regions.

The E layer is used during the day for HF radio transmission over
intermediate distances (less than 2,400 km/1,500 miles [mi]). At
night the intensity of the E layer decreases, and it becomes useless
for radio transmission.

The F layer exists at heights up to 380 km/240 mi above the Earth
and is ionized all the time. It has two well-defined layers (F1 and
F2) during the day, and one layer (F) at night. At night the F layer
remains at a height of about 260 km/170 mi and is useful for long-
range radio communications (over 2,400 km/1,500 mi). The F2
layer is the most useful for long-range radio communications, even
though its degree of ionization varies appreciably from day to day
(fig. 1-5).

The Earth’s rotation around the Sun and changes in the Sun’s activ-
ity contribute to ionospheric variations. There are two main classes
of these variations: regular (predictable) and irregular, occuring
from abnormal behavior of the Sun.

Regular Ionospheric Variations. The four regular variations are—

• Daily: caused by the rotation of the Earth.
• Seasonal: caused by the north and south progression of the Sun.
• 27-day: caused by the rotation of the Sun on its axis.
• 1-year: caused by the sunspot activity cycle going from maxi-

    mum through minimum back to maximum levels of intensity.


---

Antenna Handbook ____________________________ 1-13

F1 & F2

COMBINE   F2                                    SUN

AT NIGHT

          F1

          E

          D

  DAYLIGHT POSITIONS
                                       F2

                                       F1

                                        E

                                       D

F2 250-500 km (250-420 km at night)
F1 200-250 km
E 90-130 km
D 75-90 km

            Figure 1-5. Ionospheric Structure.


---

1-14 ____________________________________ MCRP 6-22D

Irregular Ionospheric Variations. In planning a communications
system, the current status of the four regular variations must be
anticipated. There are also unpredictable irregular variations that
must be considered. They have a degrading effect (at times blank-
ing out communications) which cannot be controlled or compen-
sated for at the present time. Some irregular variations are—

• Sporadic E. When excessively ionized, the E layer often blanks
    out the reflections from the higher layers. It can also cause
    unexpected propagation of signals hundreds of miles beyond
    the normal range. This effect can occur at any time.

• Sudden ionospheric disturbance (SID). A sudden ionospheric
    disturbance coincides with a bright solar eruption and causes
    abnormal ionization of the D layer. This effect causes total
    absorption of all frequencies above approximately 1 MHz. It
    can occur without warning during daylight hours and can last
    from a few minutes to several hours. When it occurs, receivers
    seem to go dead.

• Ionospheric storms. During these storms, sky wave reception
    above approximately 1.5 MHz shows low intensity and is
    subject to a type of rapid blasting and fading called flutter fad-
    ing. These storms may last from several hours to days and usu-
    ally extend over the entire Earth.

Sunspots. Sunspots generate bursts of radiation that cause high
levels of ionization. The more sunspots, the greater the ionization.
During periods of low sunspot activity, frequencies above 20 MHz
tend to be unusable because the E and F layers are too weakly ion-
ized to reflect signals back to Earth. At the peak of the sunspot
cycle, however, it is not unusual to have worldwide propagation on
frequencies above 30 MHz.


---

Antenna Handbook ____________________________ 1-15

Frequency Characteristics in the Ionosphere. The range of long-
distance radio transmission is determined primarily by the ioniza-
tion density of each layer. The higher the frequency, the greater the
ionization density required to reflect radio waves back to Earth. The
upper (E and F) layers reflect the higher frequencies because they
are the most highly ionized. The D layer, which is the least ionized,
does not reflect frequencies above approximately 500 kHz. Thus, at
any given time and for each ionized layer, there is an upper fre-
quency limit at which radio waves sent vertically upward are
reflected back to Earth. This limit is called the critical frequency.

Radio waves directed vertically at frequencies higher than the criti-
cal frequency pass through the ionized layer out into space. All radio
waves directed vertically into the ionosphere at frequencies lower
than the critical frequency are reflected back to Earth. Radio waves
used in communications are generally directed towards the iono-
sphere at some oblique angle, called the angle of incidence. Radio
waves at frequencies above the critical frequency will be reflected
back to Earth if transmitted at angles of incidence smaller than a cer-
tain angle, called the critical angle. At the critical angle, and at all
angles larger than the critical angle, the radio waves pass through the
ionosphere if the frequency is higher than the critical frequency. As
the angle of transmission decreases, an angle is reached at which the
radio waves are reflected back to Earth.

Transmission Paths. Sky wave propagation refers to those types
of radio transmissions that depend on the ionosphere to provide sig-
nal paths between transmitters and receivers.

The distance from the transmitting antenna to the place where the
sky waves first return to Earth is the skip distance. The skip distance
depends on the angle of incidence, the operating frequency, and the


---

1-16 ____________________________________ MCRP 6-22D

ionosphere’s height and density. The antenna’s height, in relation to
the operating frequency, affects the angle that transmitted radio
waves strike and penetrate the ionosphere and then return to Earth.
This angle of incidence can be controlled to obtain the desired cov-
erage area. Lowering the antenna height increases the angle of trans-
mission and provides broad and even signal patterns in a large area.

Using near-vertical transmission paths is known as near-vertical
incidence sky wave (NVIS). Raising the antenna height lowers the
angle of incidence. Lowering the angle of incidence produces a skip
zone in which no usable signal is received. This area is bounded by
the outer edge of usable ground wave propagation and the point
nearest the antenna at which the sky wave returns to Earth. In short-
range communications situations, the skip zone is an undesirable
condition. However, low angles of incidence make long-distance
communications possible.

When a transmitted wave is reflected back to the Earth’s surface, the
Earth absorbs part of the energy. The remaining energy is reflected
back into the ionosphere to be reflected back again. This means of
transmission—alternately reflecting the radio wave between the
ionosphere and the Earth—is called hops. Hops enable radio waves
to be received at great distances from the point of origin.

Fading. Fading is the periodic increase and decrease of received
signal strength. Fading occurs when a radio signal is received over a
long-distance path in the high frequency range. The precise origin
of this fading is seldom understood. There is little common knowl-
edge of what precautions to take to reduce or eliminate fading’s
troublesome effects. Fading associated with sky wave paths is the
greatest detriment to reliable communications. Too often, those
responsible for communication circuits rely on raising the transmit-
ter power or increasing antenna gain to overcome fading. Unfortu-
nately, such actions often do not work and seldom improve


---

Antenna Handbook ____________________________ 1-17

reliability. Only when the signal level fades down below the back-
ground noise level for an appreciable fraction of time will increased
transmitter power or antenna gain yield an overall circuit improve-
ment. Choosing the correct frequency and using transmitting and
receiving equipment intelligently ensure a strong and reliable
receiving signal, even when low power is used.

Maximum Usable and Lowest Usable Frequencies. Using a
given ionized layer and a transmitting antenna with a fixed angle of
radiation, there is a maximum frequency at which a radio wave will
return to Earth at a given distance. This frequency is called the max-
imum usable frequency (MUF). It is the monthly median of the
daily highest frequency that is predicted for sky wave transmission
over a particular path at a particular hour of the day. The MUF is
always higher than the critical frequency because the angle of inci-
dence is less than 90°. If the distance between the transmitter and
the receiver is increased, the MUF will also increase. Radio waves
lose some of their energy through absorption by the D layer and a
portion of the E layer at certain transmission frequencies.

The total absorption is less and communications more satisfactory
as higher frequencies are used—up to the level of the MUF. The
absorption rate is greatest for frequencies ranging from approxi-
mately 500 kHz to 2 MHz during the day. At night the absorption
rate decreases for all frequencies. As the frequency of transmission
over any sky wave path decreases from high to low frequencies, a
frequency will be reached at which the received signal overrides the
level of atmospheric and other radio noise interference. This is
called the lowest useful frequency (LUF) because frequencies
lower than the LUF are too weak for useful communications. The
LUF depends on the transmitter power output as well as the trans-
mission distance. When the LUF is greater than the MUF, no sky
wave transmission is possible.


---

1-18 ____________________________________ MCRP 6-22D

Propagation Prediction. Although a detailed discussion of propa-
gation prediction methods is beyond the scope of this publication, it
should be noted that propagation predictions can be obtained from a
system planning, engineering, and evaluation device (SPEED).

Other Factors Affecting Propagation

In the VHF and UHF ranges, extending from 30 to 300 MHz and
beyond, the presence of objects (e.g., buildings or towers) may pro-
duce strong reflections that arrive at the receiving antenna in such a
way that they cancel the signal from the desired propagation path
and render communications impossible. Most Marines are familiar
with distant TV station reception interference caused by high-flying
aircraft. The signal bouncing off of the aircraft alternately cancels
and reinforces the direct signal from the TV station as the aircraft
changes position relative to the transmitting and receiving antennas.

This same interference can adversely affect the ordinary voice com-
munications circuit at VHF and UHF, rendering the received signal
unintelligible for brief periods of time. Receiver locations that
avoid the proximity of an airfield should be chosen if possible.
Avoid locating transmitters and receivers where an airfield is at or
near midpoint of the propagation path of frequencies above 20
MHz.

Many other things may affect the propagation of a radio wave.
Hills, mountains, buildings, water towers, tall fences, aircraft, and
even other antennas can have a marked affect on the condition and
reliability of a given propagation path. Conductivity of the local
ground or body of water can greatly alter the strength of the trans-
mitted or received signal. Energy radiation from the Sun’s surface
also greatly affects conditions within the ionosphere and alters the
characteristics of long-distance propagation at 2 to 30 MHz.


---

Antenna Handbook ____________________________ 1-19

Path Loss

Radio waves become weaker as they spread from the transmitter.
The ratio of received power to transmitted power is called path loss.
LOS paths at VHF and UHF require relatively little power since the
total path loss at the radio horizon is only about 25 decibels (dB)
greater than the path loss over the same distance in free space
(absence of ground). This additional loss results from some energy
being reflected from the ground, canceling part of the direct wave
energy. This is unavoidable in almost every practical case. The total
path loss for an LOS path above average terrain varies with the fol-
lowing factors: total path loss between transmitting and receiving
antenna terminals, frequency, distance, transmitting antenna gain,
and receiving antenna gain.

Reflected Waves

Often, it is possible to communicate beyond the normal LOS dis-
tance by exploiting the reflection from a tall building, nearby moun-
tain, or water tower (fig. 1-6 on page 1-20). If the top portion of a
structure or hill can be seen readily by both transmitting and receiv-
ing antennas, it may be possible to achieve practical communica-
tions by directing both antennas toward the point of maximum
reflection. If the reflecting object is very large in terms of a wave-
length, the path loss, including the reflection, can be very low.

If a structure or hill exists adjacent to an LOS path, reflected energy
may either add to or subtract from the energy arriving from the
direct path. If the reflected energy arrives at the receiving antenna
with the same amplitude (strength) as the direct signal but has the
opposite phase, both signals will cancel and communication will be
impossible. However, if the same condition exists but both signals
arrive in phase, they will add and double the signal strength. These


---

1-20 ____________________________________ MCRP 6-22D

                      RECEIVER

                                TRANSMITTER

                        Figure 1-6. Reflected Waves.
two conditions represent destructive and constructive combinations
of the reflected and direct waves.
Reflection from the ground at the common midpoint between the
receiving and transmitting antennas may also arrive in a construc-
tive or destructive manner. Generally, in the VHF and UHF range,
the reflected wave is out of phase (destructive) with respect to the
direct wave at vertical angles less than a few degrees above the
horizon. However, since the ground is not a perfect conductor, the
amplitude of the reflected wave seldom approaches that of the
direct wave. Thus, even though the two arrive out of phase, com-
plete cancellation does not occur. Some improvement may result
from using vertical polarization rather than horizontal polarization


---

Antenna Handbook ____________________________ 1-21

over LOS paths because there tends to be less phase difference
between direct and reflected waves. The difference is usually less
than 10 dB, however, in favor of vertical polarization.

Diffraction

Unlike the ship passing beyond the visual horizon, a radio wave
does not fade out completely when it reaches the radio horizon. A
small amount of radio energy travels beyond the radio horizon by a
process called diffraction. Diffraction also occurs when a light
source is held near an opaque object, casting a shadow on a surface
behind it. Near the edge of the shadow a narrow band can be seen
which is neither completely light nor dark. The transition from total
light to total darkness does not occur abruptly, but changes
smoothly as the light is diffracted.
A radio wave passing over either the curved surface of the Earth or
a mountain ridge behaves in much the same fashion as a light wave.
For example, people living in a valley below a high, sharp, moun-
tain ridge can often receive a TV station located many miles below
on the other side. Figure 1-7 illustrates how radio waves from the

                         Figure 1-7. Diffracted Wave.


---

1-22 ____________________________________ MCRP 6-22D

TV station are diffracted by the mountain ridge and bent downward
in the direction of the village. It is emphasized, however, that the
energy decays very rapidly as the angle of propagation departs from
the straight LOS path. Typically, a diffracted signal may undergo a
reduction of 30 to 40 dB by being bent only 5 feet by a mountain
ridge. The actual amount of diffracted signal depends on the shape
of the surface, the frequency, the diffraction angle, and many other
factors. It is sufficient to say that there are times when the use of
diffraction becomes practical as a means for communicating in the
VHF and UHF over long distances.

Tropospheric Refraction, Ducting, and Scattering

Refraction is the bending of a wave as it passes through air layers of
different density (refractive index). In semitropical regions, a layer
of air 5 to 100 meters thick with distinctive characteristics may
form close to the ground, usually the result of a temperature inver-
sion. For example, on an unusually warm day after a rainy spell, the
Sun may heat up the ground and create a layer of warm, moist air.
After sunset, the air a few meters above the ground will cool very
rapidly while the moisture in the air close to the ground serves as a
blanket for the remaining heat. After a few hours, a sizable differ-
ence in temperature may exist between the air near the ground and
the air at a height of 10 to 20 meters, resulting in a marked differ-
ence in air pressure. Thus, the air near the ground is considerably
denser than the air higher up. This condition may exist over an area
of several hundred square kilometers or over a long area of land
near a seacoast. When such an air mass forms, it usually remains
stable until dawn, when the ground begins to cool and the tempera-
ture inversion ends.

When a VHF or UHF radio wave is launched within such air mass,
it may bend or become trapped (forced to follow the inversion
layer). This layer then acts as a duct between the transmitting


---

Antenna Handbook ____________________________ 1-23

antenna and a distant receiving site. The effects of such ducting can
be seen frequently during the year in certain locations where TV or
VHF FM stations are received over paths of several hundred kilo-
meters. The total path loss within such a duct is usually very low
and may exceed the free space loss by only a few dBs.

It is also possible to communicate over long distances by means of
tropospheric scatter. At altitudes of a few kilometers, the air mass
has varying temperature, pressure, and moisture content. Small
fluctuations in tropospheric characteristics at high altitude create
blobs. Within a blob, the temperature, pressure, and humidity are
different from the surrounding air. If the difference is large enough,
it may modify the refractive index at VHF and UHF. A random dis-
tribution of these blobs exists at various altitudes at all times. If a
high-power transmitter (greater than 1 kW) and high gain antenna
(10 dB or more) are used, sufficient energy may be scattered from
these blobs down to the receiver to make reliable communication
possible over several hundred kilometers. Communication circuits
employing this mode of propagation must use very sensitive receiv-
ers and some form of diversity to reduce the effects of the rapid and
deep fading. Scatter propagation is usually limited to path distances
of less than about 500 km.

                                NOISE

Noise consists of all undesired radio signals, manmade or natural.
Noise masks and degrades useful information reception. The radio
signal’s strength is of little importance if the signal power is greater
than the received noise power. This is why S/N ratio is the most
important quantity in a receiving system. Increasing receiver ampli-
fication cannot improve the S/N ratio since both signal and noise
will be amplified equally and S/N ratio will remain unchanged.
Normally, receivers have more than enough amplification.


---

1-24 ____________________________________ MCRP 6-22D

Natural Noise

Natural noise has two principle sources: thunderstorms (atmo-
spheric noise) and stars (galactic noise). Both sources generate
sharp pulses of electromagnetic energy over all frequencies. The
pulses propagate according to the same laws as manmade signals,
and receiving systems must accept them along with the desired sig-
nal. Atmospheric noise is dominant from 0 to 5 MHz, and galactic
noise is most important at all higher frequencies. Low frequency
transmitters must generate very strong signals to overcome noise.
Strong signals and strong noise mean that the receiving antenna
does not have to be large to collect a usable signal (a few hundred
microvolts). A 1.5 meter tuned whip will deliver adequately all of
the signals that can be received at frequencies below 1 MHz.

Manmade Noise

Manmade noise is a product of urban civilization that appears wher-
ever electric power is used. It is generated almost anywhere that
there is an electric arc (e.g., automobile ignition systems, power
lines, motors, arc welders, fluorescent lights). Each source is small,
but there are so many that together they can completely hide a weak
signal that would be above the natural noise in rural areas. Man-
made noise is troublesome when the receiving antenna is near the
source, but being near the source gives the noise waves characteris-
tics that can be exploited. Waves near a source tend to be vertically
polarized. A horizontally polarized receiving antenna will generally
receive less noise than a vertically polarized antenna.

Manmade noise currents are induced by any conductors near the
source, including the antenna, transmission line, and equipment
cases. If the antenna and transmission line are balanced with respect
to the ground, then the noise voltages will be balanced and cancel


---

Antenna Handbook ____________________________ 1-25

with respect to the receiver input terminals (zero voltage across ter-
minals), and this noise will not be received. Near-perfect balance is
difficult to achieve, but any balance helps.
Other ways to avoid manmade noise are to locate the most trouble-
some sources and turn them off, or move the receiving system away
from them. Moving a kilometer away from a busy street or highway
will significantly reduce noise. Although broadband receiving
antennas are convenient because they do not have to be tuned to
each working frequency, sometimes a narrowband antenna can
make the difference between communicating and not communicat-
ing. The HF band is now so crowded with users that interference
and noise, not signal strength, are the main reasons for poor com-
munications. A narrowband antenna will reject strong interfering
signals near the desired frequency and help maintain good commu-
nications.

                                                                    (reverse blank)


---

                         Chapter 2

         Antenna Fundamentals

All radios, whether transmitting or receiving, require some sort of
antenna. The antenna accepts power from the transmitter and
launches it into space as an electromagnetic or radio wave. At the
receiving end of the circuit, a similar antenna collects energy from
the passing electromagnetic wave and converts it into an alternating
electric current or signal that the receiver can detect.

How well antennas launch and collect electromagnetic waves
directly influences communications reliability and quality. The
function of an antenna depends on whether it is transmitting or
receiving.

A transmitting antenna transforms the output radio frequency (RF)
energy produced by a radio transmitter (RF output power) into an
electromagnetic field that is radiated through space. The transmit-
ting antenna converts energy from one form to another form. The
receiving antenna reverses this process. It transforms the electro-
magnetic field into RF energy that is delivered to a radio receiver.


---

2-2 _____________________________________ MCRP 6-22D

               Section I. Concepts and Terms

To select the right antennas for a radio circuit, certain concepts and
terms must be understood. This section defines several basic terms
and relationships which will help the reader understand antenna
fundamentals. These include: forming a radio wave, radiation fields
and patterns, polarization, directionality, resonance, reception, reci-
procity, impedance, bandwidth, gain, and take-off angle.

                  FORMING A RADIO WAVE

When an alternating electric current flows through a conductor
(wire), electric and magnetic fields are created around the conduc-
tor. If the length of the conductor is very short compared to a wave-
length, the electric and magnetic fields will generally die out within
a distance of one or two wavelengths. However, as the conductor is
lengthened, the intensity of the fields enlarge. Thus, an ever-
increasing amount of energy escapes into space. When the length of
the wire approaches one-half of a wavelength at the frequency of
the applied alternating current, most of the energy will escape in the
form of electromagnetic radiation. For effective communications to
occur, the following must exist: alternating electric energy in the
form of a transmitter, a conductor or a wire, an electric current
flowing through the wire, and the generation of both electric and
magnetic fields in the space surrounding the wire.

                             RADIATION

Once a wire is connected to a transmitter and properly grounded, it
begins to oscillate electrically, causing the wave to convert nearly
all of the transmitter power into an electromagnetic radio wave. The
electromagnetic energy is created by the alternating flow of elec-
trons impressed on the bottom end of the wire. The electrons travel


---

Antenna Handbook ______________________________ 2-3

upward on the wire to the top, where they have no place to go and
are bounced back toward the lower end. As the electrons reach the
lower end in phase, i.e., in step with the radio energy then being
applied by the transmitter, the energy of their motion is strongly
reinforced as they bounce back upward along the wire. This regen-
erative process sustains the oscillation. The wire is resonant at the
frequency at which the source of energy is alternating.

The radio power supplied to a simple wire antenna appears nearly
equally distributed throughout its length. The energy stored at any
location along the wire is equal to the product of the voltage and the
current at that point. If the voltage is high at a given point, the cur-
rent must be low. If the current is high, the voltage must be low. The
electric current is maximum near the bottom end of the wire.

Radiation Fields

When RF power is delivered to an antenna, two fields evolve. One
is an induction field, which is associated with the stored energy; the
other is a radiation field. At the antenna, the intensities of these
fields are large and are proportional to the amount of RF power
delivered to the antenna. At a short distance from the antenna and
beyond, only the radiation field remains. This field is composed of
an electric component and a magnetic component (see fig. 2-1 on
page 2-4).

The electric and magnetic fields (components) radiated from an
antenna form the electromagnetic field. The electromagnetic field
transmits and receives electromagnetic energy through free space.
A radio wave is a moving electromagnetic field that has velocity in
the direction of travel and components of electric intensity and
magnetic intensity arranged at right angles to each other.


---

2-4 _____________________________________ MCRP 6-22D

TRANSMITTING                                RECEIVING
   ANTENNA                                   ANTENNA

              ELECTRIC FIELD

SIGNAL VOLTAGE
 DIRECTION OF TRAVEL

                                              MAGNETIC FIELD

                        Figure 2-1. Radiation Fields.

Radiation Patterns

The radio signals radiated by an antenna form an electromagnetic
field with a definite pattern, depending on the type of antenna used.
This radiation pattern shows the antenna’s directional characteris-
tics. A vertical antenna radiates energy equally in all directions
(omnidirectional), a horizontal antenna is mainly bidirectional, and
a unidirectional antenna radiates energy in one direction. However,
the patterns are usually distorted by nearby obstructions or terrain
features. The full- or solid-radiation pattern is represented as a
three-dimensional figure that looks somewhat like a doughnut with
a transmitting antenna in the center (fig 2-2).


---

Antenna Handbook ______________________________ 2-5

.

                               OMNIDIRECTIONAL

                                 BIDIRECTIONAL

                                UNIDIRECTIONAL
                       Figure 2-2. Radiation Patterns.


---

2-6 _____________________________________ MCRP 6-22D
                          POLARIZATION

A radiated wave’s polarization is determined by the direction of the
lines of force making up the electric field. If the lines of electric
force are at right angles to the Earth’s surface, the wave is vertically
polarized (fig. 2-3). If the lines of electric force are parallel to the
Earth’s surface, the wave is horizontally polarized (fig. 2-4). When
a single-wire antenna extracts (receives) energy from a passing

                            DIRECTION OF TRAVEL

                                   SIGNAL VOLTAGE

                                   ELECTRIC FIELD

                                          EARTH

                      Figure 2-3. Vertical Polarization.


---

Antenna Handbook ______________________________ 2-7

radio wave, maximum pickup results if the antenna is oriented in
the same direction as the electric field component. A vertical
antenna receives vertically polarized waves, and a horizontal
antenna receives horizontally polarized waves. If the field rotates as
the waves travel through space, both horizontal and vertical com-
ponents of the field exist, and the wave is elliptically polarized.

                             DIRECTION OF TRAVEL

                                    ELECTRIC FIELD

                                   SIGNAL VOLTAGE

                                           EARTH

.

                    Figure 2-4. Horizontal Polarization.


---

2-8 _____________________________________ MCRP 6-22D

Polarization Requirements for Various Frequencies

At medium and low frequencies, ground wave transmission is used
extensively, and it is necessary to use vertical polarization. Vertical
lines of force are perpendicular to the ground, and the radio wave
can travel a considerable distance along the ground surface with a
minimum amount of loss. Because the Earth acts as a relatively
good conductor at low frequencies, horizontal lines of electric force
are shorted out, and the useful range with the horizontal polariza-
tion is limited.

At high frequencies, with sky wave transmission, it makes little dif-
ference whether horizontal or vertical polarization is used. The sky
wave, after being reflected by the ionosphere, arrives at the receiv-
ing antenna elliptically polarized. Therefore, the transmitting and
receiving antennas can be mounted either horizontally or vertically.
Horizontal antennas are preferred, since they can be made to radiate
effectively at high angles and have inherent directional properties.

For frequencies in the VHF or UHF range, either horizontal or ver-
tical polarization is satisfactory. Since the radio wave travels
directly from the transmitting antenna to the receiving antenna, the
original polarization produced at the transmitting antenna is main-
tained as the wave travels to the receiving antenna. If a horizontal
antenna is used for transmitting, a horizontal antenna must be used
for receiving.

Satellites and satellite terminals use circular polarization. Circular
polarization describes a wave whose plane of polarization rotates
through 360° as it progresses forward. The rotation can be clock-
wise or counterclockwise (see fig. 2-5). Circular polarization occurs
when equal magnitudes of vertically and horizontally polarized
waves are combined with a phase difference of 90°. Rotation in one
direction or the other depends on the phase relationship.


---

Antenna Handbook ______________________________ 2-9

Advantages of Vertical Polarization

Simple vertical half-wave and quarter-wave antennas provide
omnidirectional communications. This is desirable in communicat-
ing with a moving vehicle. The disadvantage is that it radiates
equally to the enemy and friendly forces.

When antenna heights are limited to 3.05 meters (10 feet) or less
over land, as in a vehicular installation, vertical polarization pro-
vides a stronger received signal at frequencies up to about 50 MHz.
From about 50 to 100 MHz, there is only a slight improvement over
horizontal polarization with antennas at the same height. Above 100
MHz, the difference in signal strength between vertical and hori-
zontal polarization is small. However, when antennas are located
near dense forests, horizontally polarized waves suffer lower losses
than vertically polarized waves.

Vertically polarized radiation is somewhat less affected by reflec-
tions from aircraft flying over the transmission path. With horizon-
tal polarization, such reflections cause variations in received signal

                                                                                  DIRECTION
                                                                                  OF TRAVEL

                               DIRECTION OF ROTATION,
                                         RIGHT-HAND

                     Figure 2-5. Circular Polarization.


---

2-10 ____________________________________ MCRP 6-22D

strength. An example is the picture flutter in a television set when
an aircraft interferes with the transmission path. This factor is
important in areas where aircraft traffic is heavy.

When vertical polarization is used, less interference is produced or
picked up from strong VHF and UHF transmissions (TV and FM
broadcasts) because they use horizontal polarization. This factor is
important when an antenna must be located in an urban area that
has TV or FM broadcast stations.

Advantages of Horizontal Polarization

A simple horizontal half-wave antenna is bidirectional. This charac-
teristic is useful in minimizing interference from certain directions.

Horizontal antennas are less likely to pick up manmade interfer-
ence, which is ordinarily vertically polarized. When antennas are
located near dense forests, horizontally polarized waves suffer
lower losses than vertically polarized waves, especially above 100
MHz. Small changes in antenna location do not cause large varia-
tions in the field intensity of horizontally polarized waves when an
antenna is located among trees or buildings. When vertical polariza-
tion is used, a change of only a few feet in the antenna location may
have a significant effect on the received signal strength.

                        DIRECTIONALITY

Vertical receiving antennas accept radio signals equally from all
horizontal directions, just as vertical transmitting antennas radiate
equally in all horizontal directions. Because of this characteristic,
other stations operating on the same or nearby frequencies may
interfere with the desired signal and make reception difficult or


---

Antenna Handbook ____________________________ 2-11

impossible. However, reception of a desired signal can be improved
by using directional antennas.

Horizontal half-wave antennas accept radio signals from all direc-
tions. The strongest reception is received in a line perpendicular to
the antenna (i.e., broadside, and the weakest reception is received
from the direction of the ends of the antenna). Interfering signals
can be eliminated or reduced by changing the antenna installation
so that either end of the antenna points directly at the interfering
station.

Communications over a radio circuit is satisfactory when the
received signal is strong enough to override undesired signals and
noise. The receiver must be within range of the transmitter. Increas-
ing the transmitting power between two radio stations increases
communications effectiveness. Also, changing the types of trans-
mission, changing to a frequency that is not readily absorbed, or
using a directional antenna aids in communications effectiveness.

Directional transmitting antennas concentrate radiation in a given
direction and minimize radiation in other directions. A directional
antenna may also be used to lessen interception by the enemy and
interference with friendly stations.

                           RESONANCE

Antennas can be classified as either resonant or nonresonant,
depending on their design. In a resonant antenna, almost all of the
radio signal fed to the antenna is radiated. If the antenna is fed with
a frequency other than the one for which it is resonant, much of the
fed signal will be lost and will not be radiated. A resonant antenna
will effectively radiate a radio signal for frequencies close to its
design frequency (usually only 2 percent above or below the design


---

2-12 ____________________________________ MCRP 6-22D

frequency). If a resonant antenna is used for a radio circuit, a sepa-
rate antenna must be built for each frequency to be used on the
radio circuit. A nonresonant antenna, on the other hand, will effec-
tively radiate a broad range of frequencies with less efficiency. Res-
onant and nonresonant antennas are commonly used on tactical
circuits. Resonance can be achieved in two ways: physically match-
ing the length of the antenna to the wave and electronically match-
ing the length of the antenna to the wave.

                            RECEPTION

The radio waves that leave the transmitting antenna will have an
influence on and will be influenced by any electrons in their path.
For example, as an HF wave enters the ionosphere, it is reflected or
refracted back to earth by the action of free electrons in this region
of the atmosphere. When the radio wave encounters the wire or
metallic conductors of the receiving antenna, the radio wave’s elec-
tric field will cause the electrons in the antenna to oscillate back and
forth in step with the wave as it passes. The movement of these
electrons within the antenna is the small alternating electrical cur-
rent which is detected by the radio receiver.

When radio waves encounter electrons which are free to move
under the influence of the wave’s electric field, the free electrons
oscillate in sympathy with the wave. This generates electric cur-
rents which then create waves of their own. These new waves are
reflected or scattered waves. This process is electromagnetic scat-
tering. All materials that are good electrical conductors reflect or
scatter RF energy. Since a receiving antenna is a good conductor, it
too acts as a scatterer. Only a portion of the energy which comes in
contact with the antenna is converted into received electrical power;
a sizable portion of the total power is re-radiated by the wire.


---

Antenna Handbook ____________________________ 2-13

If an antenna is located within a congested urban environment or
within a building, there are many objects which will scatter or re-
raditate the energy in a manner that can be detrimental to reception.
For example, the electric wiring inside a building can strongly re-
radiate RF energy. If a receiving antenna is in close proximity to
wires, it is possible for the reflected energy to cancel the energy
received directly from the desired signal path. When this condition
exists, the receiving antenna should be moved to another location
within the room where the reflected and direct signals may rein-
force rather than cancel each other.

                           RECIPROCITY

The various properties of an antenna apply equally, regardless of
whether the antenna is used for transmitting or receiving. This is
what is meant by reciprocity of antennas. For example, the more
efficient a certain antenna is for transmitting, the more efficient it
will be for receiving the same frequency. The directive properties
of a given antenna will be the same whether it is used for transmis-
sion or reception.

For example, figure 2-6 on page 2-14 shows a particular antenna
used with a transmitter radiating a maximum amount of energy at
right angles to the antenna wire. There is a minimum amount of
radiation along the axis of the antenna. If this same antenna is used
as a receiving antenna, it receives best in the same directions in
which it produced maximum radiation (i.e., at right angles to the
axis of the antenna). There is a minimum amount of signal received
from transmitters located in line with the antenna wire.


---

2-14 ____________________________________ MCRP 6-22D

MAXIMUM RADIATION  MAXIMUM RECEPTION

TRANSMITTING       RECEIVING
    ANTENNA         ANTENNA

Figure 2-6. Reciprocity.

                            IMPEDANCE

Impedance is the relationship between voltage and current at any
point in an alternating current circuit. The impedance of an antenna
is equal to the ratio of the voltage to the current at the point on the
antenna where the feed is connected (feed point). If the feed point is
located at a point of maximum current, the antenna impedance is 20
to 100 ohms. If the feed point is moved to a maximum voltage
point, the impedance is as much as 500 to 10,000 ohms.

The input impedance of an antenna depends on the conductivity or
impedance of the ground. For example, if the ground is a simple
stake driven about a meter into earth of average conductivity, the
impedance of the monopole may be double or even triple the quoted
values. Because this additional resistance occurs at a point on the
antenna circuit where the current is high, a large amount of


---

Antenna Handbook ____________________________ 2-15

transmitter power will dissipate as heat into the ground rather than
radiated as intended. Therefore, it is essential to provide as good a
ground or artificial ground (counterpoise) connection as possible
when using a vertical whip or monopole.

The amount of power an antenna radiates depends on the amount of
current which flows in it. Maximum power is radiated when there is
maximum current flowing. Maximum current flows when the
impedance is minimized—when the antenna is resonated so that its
impedance is pure resistance. (When capacitive reactance is made
equal to inductive reactance, they cancel each other, and impedance
equals pure resistance.)

                            BANDWIDTH

The bandwidth of an antenna is that frequency range over which it
will perform within certain specified limits. These limits are with
respect to impedance match, gain, and/or radiation pattern charac-
teristics. Typical specification limits are—

• An impedance mismatch of less than 2:1 relative to some stan-
    dard impedance such as 50 ohms.

• A loss in gain or efficiency of no more than 3 dB.
• A directivity pattern whose main beam is 13 dB greater than

    any of the side lobes, and a back lobe at least 15 dB below the
    main beam.
• Bandwidth is measured by changing the frequency of a con-
    stant-strength test signal above and below center frequency and
    measuring power output. The high and low frequencies, where
    power is one-half (-3 dB) of what it was at center, define the
    bandwidth. It is expressed as frequency (high minus low) or in
    percentage (high-low/center x 100%).


---

2-16 ____________________________________ MCRP 6-22D

In the radio communication process, intelligence changes from
speech or writing into a low frequency signal that is used to modu-
late, or cause change, in a much higher frequency radio signal.
When transmitted by an antenna, these radio signals carry the intel-
ligence to the receiving antenna, where it is picked up and recon-
verted into the original speech or writing. There are natural laws
which limit the amount of intelligence or signal that can be trans-
mitted and received at a given time. The more words per minute,
the higher the rate and the modulation frequency, so a wider or
greater bandwidth is needed. To transmit and receive all the intelli-
gence necessary, the antenna bandwidth must be as wide or wider
than the signal bandwidth, otherwise it will limit the signal frequen-
cies, causing voices and writing to be unintelligible. Too wide a
bandwidth is also bad, since it accepts extra voices and will degrade
the S/N ratio. Figure 2-7 shows how signal bandwidth is defined
and gives some examples of bandwidth required to transmit ordi-
nary types of intelligence.

                                 GAIN

The antenna’s gain depends on its design. Transmitting antennas are
designed for high efficiency in radiating energy, and receiving
antennas are designed for high efficiency in picking up (gaining)
energy. On many radio circuits, transmission is required between a
transmitter and only one receiving station. Energy is radiated in one
direction because it is useful only in that direction. Directional
receiving antennas increase the energy gain in the favored direction
and reduce the reception of unwanted noise and signals from other
directions. Transmitting and receiving antennas should have small
energy losses and should be efficient as radiators and receptors.


---

Antenna Handbook ____________________________ 2-17

POWER OUTPUT    TUNED CENTER FREQUENCY
   PERCENT OF POWER AT 3.0 MHz
100                                                0
                                                                                           DECIBELS
50                                                 -3

                                                                        -6
                                                                        -9
0 -15
 2.0 2.2 2.4 2.6 2.8 3.0 3.2 3.4 3.6 3.8 4.0

                     BANDWIDTH=1.34 MHz

                   FREQUENCY, MHz

     INTELLIGENCE            BANDWIDTH

     Voice, AM               6.0 KHz

     Voice, FM               46.0 KHz

     One microsecond pulses  10,000.0 KHz

     Bandwidths necessary to transmit and receive
     some ordinary kinds of intelligence

                Figure 2-7. Bandwidth.


---

2-18 ____________________________________ MCRP 6-22D

                        TAKE-OFF ANGLE

The antenna’s take-off angle is the angle above the horizon that an
antenna radiates the largest amount of energy (see fig. 2-8). VHF
communications antennas are designed so that the energy is radi-
ated parallel to the Earth (do not confuse take-off angle and polar-
ization). The take-off angle of an HF communications antenna can
determine whether a circuit is successful or not. HF sky wave
antennas are designed for specific take-off angles, depending on the
circuit distance. High take-off angles are used for short-range com-
munications, and low take-off angles are used for long-range com-
munications.

ANTENNA

         MAIN ENERGY
         FROM ANTENNA

            TAKE-OFF
            ANGLE

Figure 2-8. Take-Off Angle.


---

Antenna Handbook ____________________________ 2-19

                   Section II. Ground Effects

Since most tactical antennas are erected over the Earth and not out
in free space, except for those on satellites, the ground will alter the
free space radiation patterns of antennas. The ground will also
affect some of the electrical characteristics of an antenna. It has the
greatest effect on those antennas that must be mounted relatively
close to the ground in terms of wavelength. For example, medium-
and high-frequency antennas, elevated above the ground by only a
fraction of a wavelength, will have radiation patterns that are quite
different from the free-space patterns.

              GROUNDED ANTENNA THEORY

The ground is a good conductor for medium and low frequencies
and acts as a large mirror for the radiated energy. The ground
reflects a large amount of energy that is radiated downward from an
antenna mounted over it. Using this characteristic of the ground, an
antenna only a quarter-wavelength long can be made into the equiv-
alent of a half-wave antenna. A quarter-wave antenna erected verti-
cally, with its lower end connected electrically to the ground (fig.
2-9 on page 2-20), behaves like a half-wave antenna. The ground
takes the place of the missing quarter-wavelength, and the reflec-
tions supply that part of the radiated energy that normally would be
supplied by the lower half of an ungrounded half-wave antenna.


---

2-20 ____________________________________ MCRP 6-22D

                                          QUARTER-WAVE
                                          VERTICAL ANTENNA

                                                                             1/4
                              EARTH

                                          IMAGE ANTENNA

                    Figure 2-9. Quarter-Wave Antenna
                             Connected to Ground.

                      TYPES OF GROUNDS

When grounded antennas are used, it is especially important that the
ground has as high a conductivity as possible. This reduces ground
losses and provides the best possible reflecting surface for the
down-going radiated energy from the antenna. At low and medium
frequencies, the ground acts as a good conductor. The ground con-
nection must be made in such a way as to introduce the least possi-
ble amount of resistance to ground. At higher frequencies, artificial
grounds constructed of large metal surfaces are common.


---

Antenna Handbook ____________________________ 2-21

The ground connections take many forms, depending on the type of
installation and the loss that can be tolerated. In many simple field
installations, the ground connection is made by one or more metal
rods driven into the soil. Where more satisfactory arrangements
cannot be made, ground leads can be connected to existing devices
which are grounded. Metal structures or underground pipe systems
are commonly used as ground connections. In an emergency, a
ground connection can be made by forcing one or more bayonets
into the soil.

When an antenna must be erected over soil with low conductivity,
treat the soil to reduce resistance. Treat the soil with substances that
are highly conductive when in solution. Some of these substances,
listed in order of preference, are sodium chloride (common salt),
calcium chloride, copper sulfate (blue vitriol), magnesium sulfate
(Epsom salt), and potassium nitrate (saltpeter). The amount
required depends on the type of soil and its moisture content.

                                   WARNING
WHEN THESE SUBSTANCES ARE USED, IT IS IMPORTANT
THAT THEY DO NOT GET INTO NEARBY DRINKING WATER
SUPPLIES.

For simple installations in the field, a single ground rod can be fab-
ricated from pipe or conduit. It is important that a low resistance
connection be made between the ground wire and the ground rod.
The rod should be cleaned thoroughly by scraping and sandpaper-
ing at the point where the connection is to be made, and a clean
ground clamp should be installed. A ground wire can then be sol-
dered or joined to the clamp. This joint should be covered with tape
to prevent an increase in resistance because of oxidation.


---

2-22 ____________________________________ MCRP 6-22D

Counterpoise

When an actual ground connection cannot be used because of the
high resistance of the soil or because a large buried ground system
is not practical, a counterpoise may be used to replace the usual
direct ground connection. The counterpoise (fig. 2-10) consists of a
device made of wire, which is erected a short distance above the
ground and insulated from it. The size of the counterpoise should be
at least equal to or larger than the size of the antenna.
When the antenna is mounted vertically, the counterpoise should be
made into a simple geometric pattern. Perfect symmetry is not
required. The counterpoise appears to the antenna as an artificial
ground that helps to produce the required radiation pattern.

                      COUNTERPOISE

                                        ANTENNA

                                         SUPPORT

                      Figure 2-10. Wire Counterpoise.


---

Antenna Handbook ____________________________ 2-23

In some VHF antenna installations on vehicles, the metal roof of the
vehicle (or shelter) is used as a counterpoise for the antenna. Small
counterpoises of metal mesh are sometimes used with special VHF
antennas that must be located a considerable distance above the
ground.

Ground Screen

A ground screen consists of a fairly large area of metal mesh or
screen that is laid on the surface of the ground under the antenna.
There are two specific advantages to using ground screens. First,
the ground screen reduces ground absorption losses that occur when
an antenna is erected over ground with poor conductivity. Second,
the height of the antenna can be set accurately, and the radiation
resistance of the antenna can be determined more accurately.


---

2-24 ____________________________________ MCRP 6-22D

Section III. Calculating Antenna Length

An antenna’s length must be considered in two ways: physical and
electrical. The two are never the same. The reduced velocity of the
wave on the antenna and a capacitive effect (end effect) make the
antenna seem longer electrically than physically. The contributing
factors are the ratio of the diameter of the antenna to its length and
the capacitive effect of terminal equipment (e.g., insulators or
clamps) used to support the antenna.

To calculate the antenna’s physical length, use a correction of 0.95
for frequencies between 3 and 50 MHz. The figures given are for a
half-wave antenna.

Length (meters)  = 150 x 0.95 =  142.50

                 Frequency in MHz Frequency in MHz

Length (feet)    = 492 x 0.95 =        468

                 Frequency in MHz Frequency in MHz

The length of a long-wire antenna (one wavelength or longer) for
harmonic operation is calculated by using the following formula,
where N = number of half-wavelengths in the total length of the
antenna.

Length (meters)  = 150 (N - 0.05)
                     Frequency in MHz

Length (feet)    = 492 (N - 0.05)
                     Frequency in MHz


---

Antenna Handbook ____________________________ 2-25

Example: 3 half-wavelengths at 7 MHz is—

Length (meters)  = 150 (N - 0.05)
                     Frequency in MHz

                 = 150 (3 - .05)
                                7

                 =  150 x 2.95

                                          7

                 =  442.50

                                          7

                 =  63.2 meters


---

2-26 ____________________________________ MCRP 6-22D

              Section IV. Antenna Orientation

The orientation of an antenna is extremely important. Determining
the position of an antenna in relation to the points of the compass
can make the difference between a marginal and good radio circuit.

                              AZIMUTH

If the azimuth of the radio’s path is not provided, determine it by the
best available means. The accuracy required depends on the radia-
tion pattern of the directional antenna. If the antenna beamwidth is
very wide (e.g., 90° angle between half-power points) an error of

                      HALF-POWER

      90°             POINTS      90°

270°                  0°  270°              0°

               180°                  180°

           RELATIVE               RELATIVE
      FIELD STRENGTH               POWER

Figure 2-11. Beamwidth Measured on Relative Field Strength
                      and Relative Power Patterns.


---

Antenna Handbook ____________________________ 2-27

10° is of little consequence. In transportable operation, the rhombic
and vee antennas may have such a narrow beam that great accuracy
is required to determine azimuth. The antenna should be erected for
the correct azimuth. Great accuracy is not required to erect broad-
beam antennas.

Unless a line of known azimuth is available at the site, the direction
of the path is best determined by a magnetic compass. Figure 2-12
on page 2-28 is a map of magnetic declination, showing the varia-
tion of the compass needle from the true north. When the compass
is held so that the needle points to the direction indicated for the
location on the map, all directions indicated by the compass will be
true.

Improvement of Marginal Communications

It may not always be feasible to orient directional antennas to the
correct azimuth of the desired radio path, and marginal communica-
tions may suffer. To improve marginal communications—

• Check, tighten, and tape cable couplings and connections.
• Retune all transmitters and receivers in the circuit.
• Check that the antennas are adjusted for proper operating fre-

    quency.
• Change the heights of antennas.
• Move the antenna a short distance away and in different loca-

    tions from its original location.
• Separate transmitters from receiving equipment, if feasible.


---

                                                                                                                2-28 ____________________________________ MCRP 6-22D

Figure 2-12. Magnetic Declination Over the World.
180 160 140 120 100 80 60 40 20 0 20 40 60 80 100 120 140 160 180

80 50E 60W 60E          35E 40E 80
                 55W    25E 30E 70
70  40E     NMP  50W

    35E          45W

60  30E          40W    20E  5W                  60
                 35W
50 25E 25W 30W
    20E                 10E                      50

40               20W    5E   10W                 40

30 15E             15W            5W             30
                 10W

20 5E 0 5W              0E        0              20

10 10E                               5E          10

0                       5W 10W 10E 0

10  10E                 15W                      10

20                      20W                      20
30 15E
                        25W

                        30W              15E 30

                        35W

    20E                 40W

40  25E                 50W 45W 20E 40

50 35E 30E              55W              25E30E 50

60 50E 40E              60W              35E40E
                                         50E 60
                                         60E
70 60E                                           70
                             SMP

80                                               80

180 160 140 120 100 80 60 40 20 0 20 40 60 80 100 120 140 160 180


---

Antenna Handbook ____________________________ 2-29

Transmission and Reception of Strong Signals

After an adequate site has been selected and the proper antenna ori-
entation obtained, the signal level at the receiver will be propor-
tional to the strength of the transmitted signal.

                                   WARNING
EXCESSIVE SIGNAL STRENGTH MAY RESULT IN ENEMY IN-
TERCEPT AND INTERFERENCE OR IN YOUR INTERFERENCE
WITH ADJACENT FREQUENCIES.

If a high-gain antenna is used, a stronger signal can be obtained.
Losses between the antenna and the equipment can be reduced by
using a high quality transmission line, as short as possible, and
properly matched at both ends.

                                   WARNING
BE EXTREMELY CAREFUL WHEN PUTTING UP, TAKING
DOWN, OR MOVING ANTENNAS LOCATED NEAR HIGH VOLT-
AGE OR COMMECIAL POWER LINES. ANTENNA CONTACT
WITH THESE CAN AND MAY RESULT IN ELECTROCUTION
OR SEVERE INJURY TO PERSONNEL HOLDING THE ANTEN-
NA OR THE CONNECTING GUY WIRES AND CABLES.

                                                                    (reverse blank)


---

                         Chapter 3

            Transmission Lines

Transmission lines (antenna feed lines) conduct or guide electrical
energy from the transmitter to the receiver. This chapter is oriented
primarily toward transmission lines with field expedient antennas.
For standard issue radios and antennas, use the issued coaxial cable.
As long as radios, cables, and antennas are maintained in working
order, they will operate as designed and won’t require any adjust-
ments or changes based on the information in this chapter.

                           PROPERTIES

Transmission Line Types

Transmission lines are classified according to construction and
length, and fall into two main categories: balanced line and unbal-
anced line. The terms balanced and unbalanced describe the rela-
tionship between transmission line conductors and the Earth.
Transmission lines may be classified as resonant or nonresonant
lines, each of which may have advantages over the other under a
given set of circumstances.

Balanced Line. A balanced line is composed of two identical con-
ductors, usually circular wires, separated by air or an insulating
material (dielectric). The voltages between each conductor and
ground produced by an RF wave as it moves down a balanced line,


---

3-2 _____________________________________ MCRP 6-22D

are equal and opposite (i.e. at the moment one of the conductors
supports a positive voltage with respect to ground, the other sup-
ports a negative voltage of equal magnitude). Some balanced lines
carry a third conductor in the form of a braided shield, which acts as
ground. Conductor spacings up to several centimeters are com-
monly used. Figure 3-1 shows balanced and unbalanced lines.

PLASTIC COVERING         BRAIDED WIRE SHIELD

                               PLASTIC
                               COVERING

OPEN TWIN LINES INSULATORS SHIELDED LINE

BALANCED TRANSMISSION LINES

                         PLASTIC COVERING

CONDUCTING GROUND PLANE

                         BRAID

OPEN SINGLE WIRE LINE    SHIELDED LINE(COAX)

UNBALANCED TRANSMISSION LINES

Figure 3-1. Balanced and Unbalanced Transmission Lines.


---

Antenna Handbook ______________________________ 3-3

Unbalanced Line. The unbalanced line is usually open single-wire
line or coaxial cable. It is one-half of a balanced line.

Nonresonant Line. A nonresonant line is a line that has no stand-
ing waves of current and voltage. It is either infinitely long or is ter-
minated in its characteristic impedance. Because there are no
reflections, all of the energy passed along the line is absorbed by the
load (except for the small amount of energy dissipated by the line).

Resonant Line. A resonant transmission line has standing waves of
current and voltage. The line is of finite length and is not terminated
in its characteristic impedance. Reflections are present. A resonant
line, like a tuned circuit, is resonant at some particular frequency.
The resonant line will present to its source of energy a high or a low
resistive impedance at multiples of a quarter-wavelength. Whether
the impedance is high or low at these points depends on whether the
line is short- or open-circuited at the output end. At points that are
not exact multiples of a quarter-wavelength, the line acts as a capac-
itor or an inductor.

                 MINIMIZING ENERGY LOSS

To communicate with minimal energy loss, elements such as imped-
ance matching and attenuation (line losses) must be considered.

Impedance

Currents and waves cannot move from place to place without some
dissipation; their flow is impeded. Impedance describes the nature
and size of whatever impedes their flow. Impedance is an important
consideration in selecting the proper transmission line.


---

3-4 _____________________________________ MCRP 6-22D

A radio wave consists of electric and magnetic fields arranged per-
pendicularly to each other and to the direction the wave travels. The
impedance associated with this wave is the ratio of the potential dif-
ference (voltage) to the current (amperage) at a given point along a
transmission line. The following formula illustrates this.

                           Voltage = Impedance
                           Current

In transmission lines, because of the length-frequency relationship,
the characteristic impedance is more often discussed in terms of
capacitance and inductance. In conventional circuits that contain
inductors and capacitors, the inductance and capacitance are present
in definite lumps. In an RF transmission line, however, these quan-
tities are distributed throughout the entire line and cannot be sepa-
rated from each other.

If a transmitter is connected to a transmission line that is terminated
in a load whose impedance is different from that of the line, only a
portion of the available energy will be accepted by the load antenna,
and the remainder will be reflected back down the line in the direc-
tion of the transmitter. The energy is actually traveling in both
directions along the line.

If a transmitter is connected to a transmission line terminated in a
load whose impedance exactly equals the impedance of the line, the
line will absorb all of the energy except for that lost in the resistive
and dielectric losses of the line. Current flowing through the line
will be uniformly distributed along its length, and the voltage
between the conductors on the line will be equal at all points. When
this condition exists, the line is said to be perfectly matched and
carries only a forward or incident wave. If the impedance of the
transmission line and the load also equal the internal impedance
(output impedance) of the transmitter, a maximum transfer of


---

Antenna Handbook ______________________________ 3-5

energy (lowest system loss) is achieved (i.e., the transmitter or
receiver, transmission line, and antenna are all the same imped-
ance), and the best possible transfer of signal energy will occur.

Optimizing Line Length

When it is necessary to use a transmission line whose impedance is
significantly different from that of the load, it is possible to make
good use of standing waves and the repetitive impedance variations
along the line to match the antenna to the transmitter or the receiver
to the antenna by cutting the line to a specific length. An example
is when the only available equipment consists of a 300-ohm twin-
lead transmission line; a 50-ohm half-wave dipole antenna; and a
50-ohm internal impedance transceiver. (Note: The internal imped-
ance of most USMC radios is 50 ohms). Ordinarily, this impedance
combination would result in lost energy that could affect the qual-
ity of communications. However, if a single frequency is used to
communicate, the length between the antenna and the receiver can
be matched. This occurs because the impedance of the receiver is
repeated at intervals of a half-wavelength along the line.

For end-fed, long-wire antennas, a similar impedance match can be
made by feeding the long wire with a quarter-wavelength piece of
wire that is connected to the transmitter on one end and to the end
of the long wire on the other. The quarter-wavelength section
doesn’t need to be a separate piece of wire. For a 2-wavelength,
long-wire antenna, for example, the wire can be cut to 2 1/4 wave-
lengths. The entire quarter-wavelength section then becomes the
transmission line between the radio and the antenna.


---

3-6 _____________________________________ MCRP 6-22D

Attenuation

Transmission lines do not transfer all of the energy applied at one
end of the line to the opposite end. Attenuation is energy that is lost
when converted into heart, partially due to conductor (wire) resis-
tance. More energy is lost due to the insulation material used to
space the conductors (dielectric loss). Some insulating materials
(e.g., Teflon) have extremely low loss while others (e.g., rubber or
wood) have relatively high loss, especially at frequencies above
about 30 MHz. Old, dry wood (especially redwood) may be boiled
in paraffin or bee’s wax to make a fairly good insulator at frequen-
cies up to about 200 MHz. Polyethylene, a common insulation
material used in coaxial cables, has an average loss of about twice
that of Teflon in the 100-MHz range for cables having a diameter of
less than about one centimeter. Dry air is a better insulator than
most solid, liquid, or flexible materials. Some inert gases (e.g.,
nitrogen, helium, and argon) are superior to air and are often used
under pressure to fill coaxial cables used with high-powered trans-
mitters.

Since attenuation results from conductor resistance and dielectric
loss, transmission lines using large diameter conductors lose less
energy than cables having small diameter conductors. Also, trans-
mission lines having a large spacing between conductors (high
impedance) will lose less energy than those with a smaller spacing
(lower impedance) since they carry smaller currents and there is
less energy lost in conductor resistance. Thus, 300-ohm twin-lead
has less loss than coaxial cable at most frequencies. Among coaxial
cables, the larger the diameter, the lower the loss, assuming the
same insulator is used. It is also true that coaxial cable, which has
an impedance of 75 ohm, has slightly lower loss than 50-ohm cable,
when both cables have about the same diameter. When there is a
choice, it is best to use the largest available transmission line which
matches the impedance of both the antenna and transmitter.


---

Antenna Handbook ______________________________ 3-7

        MAKING THE BEST USE OF AVAILABLE
                     TRANSMISSION LINES

It is often necessary to feed a balanced antenna (e.g., horizontal
dipole) with coaxial cable. While this is not considered good prac-
tice, it will perform satisfactorily under most conditions. When
coaxial cable is used for this purpose, it should run perpendicular to
the dipole wires for a distance greater than one-half of the length of
the dipole. This will help to prevent unwanted RF power from being
induced on the outside shield of the cable. It is also advisable to
make sure that the total length of the coaxial cable and one side of
the antenna is not equal to a half-wavelength or any multiple
thereof. This will prevent the outside conductor from becoming res-
onant and acting as a radiating part of the antenna. The same pre-
caution should be taken with twin-lead transmission line.

Occasionally, it may also be necessary to feed an unbalanced
antenna (e.g., a whip with twin-lead or balanced line). Again this is
not considered good practice, but the bad effects can be minimized
if care is taken. If the transmitter has a balanced output circuit, little
difficulty will be experienced. However if the output is unbalanced,
the hot terminal or coaxial center at the transmitter output must be
connected to the same wire of the twin-lead as is the vertical whip
at the other end of the twin-lead. This ensures that the ground side
of the transmitter output is connected to the side of the twin-lead
that goes to the ground side of the unbalanced antenna.

If the twin-lead is reversed and the antenna ground terminal is con-
nected to the hot terminal of the transmitter, a large portion of the
transmitter output may be wasted, making communications either
difficult or impossible. Twin-lead of the type commonly used with
television sets usually has one tinned and one bare copper conduc-
tor. This color coding readily permits correct connection of the
transmitter to the antenna. It is also advisable to make the length of


---

3-8 _____________________________________ MCRP 6-22D

the twin-lead equal to a half-wavelength or any multiple of a half-
wavelength. When possible, the twin-lead should be twisted so that
it forms a long helix with about one twist every thirty centimeters,
or so. Twisting helps to prevent transmission line radiation and
reduces noise pickup when receiving.

Twin-Lead Limitations

It is generally best not to use twin-lead or balanced line at frequen-
cies higher than about 200 MHz for three reasons.

First, the spacing between the two wires becomes sufficiently large
in terms of a wavelength that radiation from the line occurs. When
lengths over 30 meters are employed, this radiation may represent a
significant loss of energy.

Second, if the twin-lead or balanced lines must come in close con-
tact (less than 2 or 3 cm) with metal, masonry, or wood surfaces,
additional losses will be encountered due to the substantial imped-
ance change which takes place along the section of the line next to
the surface. This mismatch loss becomes apparent at frequencies
above 200 MHz because the length of the section affected becomes
a substantial portion of a wavelength long. At lower frequencies,
the section of line involved is too short to be seriously affected.

Third, twin-lead picks up more locally generated interference than
coaxial cable since the outer conductor of the coaxial cable acts as a
shield for the center conductor. Radiation and noise pickup by twin-
lead can be partially prevented by twisting it once every 20 or 30
centimeters.

When using common, TV twin-lead (300 ohm), preference should
be given to the deep brown rather than the light, colorless variety.
The darker colored twin-lead withstands the effects of sunlight and


---

Antenna Handbook ______________________________ 3-9

moisture after prolonged outdoor exposure much better than the
clear type. The clear, colorless, twin-lead tends to crack after a few
months exposure to the Sun. It also begins to absorb moisture which
greatly increases energy loss.

Directly Connecting the Transceiver and Antenna

In many instances the transmitter or receiver may be connected
directly to the antenna wire without using a transmission line. This
is particularly true with indoor antennas in the HF range and with
many VHF whip antennas designed for use with manpack trans-
ceivers.

When a direct connection is made between a transmitter and the
antenna at frequencies below 30 MHz or where the length of the
antenna wire is much shorter than 0.25 λ, the output circuit of the
transmitter usually contains a matching device which may be used
to tune the antenna efficiently to resonance. This tuning actually
matches the impedance of the antenna to the output impedance of
the transmitter.

When a VHF transceiver is designed to connect directly to a short
whip or self-contained, collapsible rod, the output circuit is usually
designed to accommodate the range of impedances likely to be
encountered at the base of the whip or rod.

The efficiency of these devices is usually low since the ground
return circuit for the antenna may range from nothing more than the
case of the transmitter to the hand and body of an individual hold-
ing the device. The impedance of the antenna may vary with fre-
quency over a range of 5 to 1 or greater. Thus, antenna efficiencies
of from 25 to 50 percent are not uncommon with such devices.


---

3-10 ____________________________________ MCRP 6-22D

                               BALUNS

There are times when a balanced antenna must be used with a trans-
mitter or receiver which has an unbalanced output or input circuit.
While it is possible to make a direct connection between balanced
and unbalanced devices, it is certainly not good practice. A balun
can be used to transform energy from balanced to unbalanced
devices and vice versa.

The word balun comes from balanced to unbalanced transformer.
Many balun types are easily constructed in the field. Using them
can often make the difference between marginal communications
and completely solid contact. This may be especially true in the
receiving case where a balun can result in a substantial reduction in
the amount of manmade noise and interference received by a poorly
balanced antenna system. The balun is usually placed at the antenna
terminals so that a coaxial transmission line can be used. However,
it is possible to feed a balanced antenna with twin-lead or any kind
of balanced line, and the balun is placed near the transmitter or
receiver terminals (see figs. 3-2 and 3-3).

                                                           BALANCED ANTENNA

                                                                      BALUN

                      TRANSMITTER OR
                                 RECEIVER

                                       COAX

              Figure 3-2. A Balun Placed at the Antenna.


---

Antenna Handbook ____________________________ 3-11

                                                                  ANTENNA

                               TRANSMITTER OR
                                          RECEIVER

COAX  BALUN

             TWIN LEAD

     Figure 3-3. Balun Placed at the Transmitter or Receiver.

Cable Connectors

Cable connector fittings are available for all standard transmission
lines. Although it takes some time to prepare the cable ends and sol-
der the fittings on, it may be well worth it later if rapid assembly or
disassembly of a communications system is necessary.

Balanced Antenna

It is highly desirable to use a receiving antenna which is balanced
with respect to ground. This insures the antenna’s insensitivity to
locally generated noise. Balancing only the receiving antenna is not
enough. The entire receiving system must be balanced to success-
fully reject noise. The antenna should be connected to its receiver
so as not to disrupt the antenna’s balance. Receivers are supplied
with either balanced or unbalanced antenna terminals, and some-
times both.

                        (reverse blank)


---

                         Chapter 4

         HF Antenna Selection

The HF portion of the radio spectrum is very important to commu-
nications. Radio waves in the 3 to 30 MHz frequency range are the
only ones that are capable of being reflected or returned to Earth by
the ionosphere with predictable regularity. To optimize the proba-
bility of a successful sky wave communications link, select the fre-
quency and take-off angle that is most appropriate for the time of
day transmission is to take place.

Merely selecting an antenna that radiates at a high elevation angle is
not enough to ensure optimum communications. Various large con-
ducting objects, in particular the Earth’s surface, will modify an
antenna’s radiation pattern. Sometimes, nearby scattering objects
may modify the antenna’s pattern favorably by concentrating more
power toward the receiving antenna. Often, the pattern alteration
results in less signal transmitted toward the receiver.

When selecting an antenna site, the operator should avoid as many
scattering objects as possible. How the Earth’s surface affects the
radiation pattern depends on the antenna’s height. The optimum
height above electrical ground is about 0.4 λ at the transmission fre-
quency. However, the exact height is not critical.

Although NVIS is the chief mode of short-haul HF propagation, the
ground wave and direction (LOS) modes are also useful over short
paths. How far a ground wave is useful depends on the electrical
conductivity of the terrain or body of water over which it travels.
The direct wave is useful only to the radio horizon, which extends
slightly beyond the visual horizon.


---

4-2 _____________________________________ MCRP 6-22D

          ANTENNA SELECTION PROCEDURE

Selecting the right antenna for an HF radio circuit is very important.
When selecting an HF antenna, first consider the type of propaga-
tion. Ground wave propagation requires low take-off angle and ver-
tically polarized antennas. The whip antenna included with all radio
sets provides good omnidirectional ground wave radiation.

If a directional antenna is needed, select one with good, low-angle
vertical radiation. An example is an AN/MRC-138 with its compo-
nent 32-foot whip set up on a 200-mile circuit. With the radiation
characteristics of the whip antenna, the radiated power of the trans-
mitter or whip could be 300 watts for the take-off angle required for
a 200-mile circuit.

If a 35-foot half-wave horizontal dipole is used instead of the whip,
the radiated power would be 5,000 watts. By using the dipole
instead of the whip, the radiated power is increased more than 16
times. A circuit with 5,000 watts of radiated power produces a bet-
ter signal than a 300-watt circuit using the same frequency.

Selecting an antenna for sky wave propagation is more complex.
First, find the circuit (range) distance so that the required take-off
angle can be determined. Table 4-1 gives approximate take-off
angles for daytime and nighttime sky wave propagation. A circuit
distance of 966 kilometers (600 miles) requires a take-off angle of
approximately 25° during the day and 40° at night. Select a high-
gain antenna (25° to 40°). If propagation predictions are available,
skip this step, since the predictions will probably give the take-off
angles required.

Next, determine the required coverage. A radio circuit with mobile
(vehicular) stations or several stations at different directions from the
transmitter requires an omnidirectional antenna. A point-to-point


---

Antenna Handbook ______________________________ 4-3

circuit uses either a bidirectional or a directional antenna. Normally,
the receiving station locations dictate this choice (see table 4-1).

Table 4-1. Take-Off Angle vs. Distance.

Take-off Angle        Distance
   (Degrees)
                F2 Region Daytime F2 Region Nighttime
           0
           5    kilometers miles kilometers miles
         10
         15     3220  2000  4508         2800
         20
         25     2415  1500  3703         2300
         30
         35     1932  1200  2898         1800
         40
         45     1450  900   2254         1400
         50
         60     1127  700   1771         1100
         70
         80     966   600   1610         1000
         90
                725   450   1328         825

                644   400   1127         700

                564   350       966      600

                443   275       805      500

                403   250       685      425

                258   160       443      275

                153   95        290      180

                80    50        145      90

                0     0         0        0

Before selecting a specific antenna, examine the available construc-
tion materials. At least two supports are needed to erect a horizontal
dipole, with a third support in the middle for frequencies of 5 MHz
or less. If these supports or other items to use as supports are
unavailable, the dipole cannot be constructed, and another antenna
should be selected. Examine the proposed antenna site to determine
if the antenna will fit. If not, select a different antenna.


---

4-4 _____________________________________ MCRP 6-22D

The site is another consideration. Usually, the tactical situation
determines the position of the communications antennas. The ideal
setting would be a clear, flat area (i.e., no trees, buildings, fences,
power lines, or mountains). Unfortunately, an ideal location is sel-
dom available. Choose the clearest, flatest area possible. If the pro-
posed site is obstructed, try to maintain the horizontal distance
listed in table 4-2. Often, an antenna must be constructed on irregu-
lar sites. This does not mean that the antenna will not work. It
means that the site will affect the antenna’s pattern and function.

Table 4-2. Assuming a 30-Foot Antenna and
                     75-Foot Trees

Take-Off Angle  Required Horizontal Distance
   (Degrees)                 from Trees
             0
             5  18    kilometers
           10
           15   1932  meters
           20
           25   966   meters
           30
           35   644   meters
           40
           45   483   meters
           50
           60   370   meters
           70
           80   298   meters
           90
                241   meters

                201   meters

                169   meters

                145   meters

                105   meters

                64    meters

                32    meters

                0     meters


---

Antenna Handbook ______________________________ 4-5

After selecting the antenna, determine how to feed the power from
the radio to the antenna (fig. 4-1). Most tactical antennas are fed
with coaxial cable (RG-213). Coaxial cable is a reasonable compro-
mise of efficiency, convenience, and durability. Issued antennas
include the necessary connectors for coaxial cable or for direct con-
nection to the radio.

                   INSULATING SPACERS

PLASTIC SHIELDING

BRAID                   WIRE
                   CENTER CONDUCTOR

                               INSULATION

                      Figure 4-1. Antenna Feed Lines.

Problems may arise in connecting field expedient antennas. The
horizontal half-wave dipole uses a balanced transmission line
(open-wire). Coaxial cable can be used, but it may cause unwanted
RF current.

A balun prevents unwanted RF current flow, which causes a radio
to be hot and shock the operator. Install the balun at the dipole feed
point (center) to prevent unwanted RF current flow on the coaxial
cable. If a balun is unavailable, use the coaxial cable that feeds the


---

4-6 _____________________________________ MCRP 6-22D

antenna as a choke (see fig. 4-2). Connect the cable’s center wire to
one leg of the dipole and the cable braid to the other antenna leg.
Form the coaxial cable into a 6-inch coil (consisting of ten turns),
and tape it to the antenna under the insulator for support.

                         6” COIL TAPED TO INSULATOR

COAX

      TO TRANSMITTER

Figure 4-2. Coax RF Current Choke.

               DETERMINING ANTENNA GAIN

Determine antenna gain at a specific take-off angle from the vertical
radiation pattern. Figure 4-3 shows the vertical antenna pattern for
the 32-foot vertical whip. The numbers along the outer ring (90°,
80°, 70°) represent the angle above the Earth; 90° would be straight
up, and 0° would be along the ground. Along the bottom of the pat-
tern are numbers from -10 (at the center) to +15 (at the edges).
These numbers represent the gain in decibels over an isotropic radi-
ator (dBi).

To find the antenna gain at a particular frequency and take-off
angle, locate the desired take-off angle on the plot. Follow that line
toward the center of the plot to the pattern of the desired frequency.
Drop down and read the gain from the bottom scale. If the gain of a
32-foot vertical whip at 9 MHz and 20° take-off angle is desired,
locate 20° along the outer scale. Follow this line to the 9-MHz


---

Antenna Handbook ______________________________ 4-7

                                 TAKE-OFF ANGLE

                            70°  80° 90° 80°     70°

                       60°                            60°
                                                              50°
               50°                                                    40°

          40°

     30°                                                                   30°

20°                                                                        20°

10°                                                                             10°

     15   10        5       0    -5  -10  -5          10 15

                                     dBi

               3 MHz                 9 MHz

         Figure 4-3. 32-Foot Vertical Whip, Vertical Pattern.

pattern line. Move down to the bottom scale. The gain is a little less
than 2.5 dBi (the line between 0 and 5 dBi). The gain of the 32-foot
vertical whip at 9 MHz and 20° is 2 dBi.

Once the antenna’s overall characteristics are determined, use the
antenna selection matrix (table 4-3 on page 4-8) to find the specific
antenna for a circuit. If the proposed circuit requires a short-range,
omnidirectional, wideband antenna, the selection matrix shows that
the only antenna that meets all the criteria is the AS-2259/GR.

If the circuit requires a medium-range directional antenna, several
antennas could be used (e.g., long wire, sloping vee, or vertical half-
rhombic). The antenna choice depends on available installation
space, available components, and required highest gain take-off
angle. For a required take-off angle of 25° at a frequency of 9 MHz,


---

4-8 _____________________________________ MCRP 6-22D

the 100-foot vertical half-rhombic antenna is the best choice because
it provides the highest gain at the required take-off angle.

             Table 4-3. Antenna Selection Matrix.

                           Use                       Polar- Band-
                                   Directivity ization width
                         Sky Wave

                  Ground Wave
                        Short (500 Miles)
                               Medium (500 to 1200 Miles)
                                      Long (1200 Miles)
                                             Omnidirectional
                                                    Bidirectional
                                                           Directional
                                                                  Horizontal
                                                                         Vertical
                                                                               Wide
                                                                                      Narrow

AS-2259/GR               X         X               X

Vertical Whip     X                X               XX

Half-Wave Dipole         XX           X     X          X

Inverted Vee      XXX                 X     XX         X

Long Wire         X         XX        XX           XX

Inverted L        XXX              XX       XX         X

Sloping Vee       X         XX           XX        X

Sloping Wire      X         XX        XX           XX

Vertical Half-Rhombic X     XX           X         XX

                        ANTENNA TYPES

The AS-2259/GR, vertical whip, half-wave dipole, inverted vee,
long wire, inverted L, sloping vee, sloping wire, and vertical half-
rhombic antennas are described and illustrated.


---

Antenna Handbook ______________________________ 4-9

AS-2259/GR

The AS-2259/GR antenna (fig. 4-4) provides NVIS propagation for
short-range radio circuits. It consists of two crossed sloping dipoles
positioned at right angles to each other and is supported at the center
by a 15-foot mast. In use, the dipole’s components provide guying
support for the mast. Characteristics are—

Frequency range:            2 to 30 MHz
Polarization:               Horizontal and vertical simultaneously
Power capability:           1,000 watts
Radiation pattern
Azimuthal (bearing):        Omnidirectional
Vertical (take-off angle):  See figure 4-5 on page 4-10

Figure 4-4. AS-2259/GR.


---

4-10 ____________________________________ MCRP 6-22D

                                 TAKE-OFF ANGLE

                            70°  80° 90° 80°     70°

                       60°                            60°
                                                              50°
               50°                                                    40°

          40°

     30°                                                                   30°

20°                                                                        20°

10°                                                                             10°

     15   10        5       0    -5 -10  -5           10 15

                                 dBi

               3 MHz             9 MHz

          Figure 4-5. AS-2259 Vertical Radiation Pattern.

Vertical Whip

The vertical whip is a component of all Marine Corps radio sets
(see fig. 4-6). It is available and easy to use on almost all radio cir-
cuits; however, it is probably the worst antenna to use on sky wave
circuits. Unless the radio circuit involves omnidirectional ground
wave propagation, any other antenna would provide better commu-
nications. For example, vertical whips are often used for long-range
point-to-point circuits with marginal success. Since the circuit is
point-to-point, there is no need to radiate energy in all directions.
Radiation in directions other than at the distant station is wasted and
serves no useful purpose. Concentrating the omnidirectional radia-
tion at the distant station produces a better received signal and
reduces interference around the transmitting antenna. Concentrate
radiation in a single direction with a directional antenna. Figures


---

Antenna Handbook ____________________________ 4-11

4-7 on page 4-12, 4-8 on page 4-13, and 4-3 on page 4-7 illustrate
various vertical whip antenna patterns.

Characteristics are—

Frequency range:            2 to 30 MHz
Polarization:               Vertical
Power capability:           Matched to specific radio
Radiation pattern
Azimuthal (bearing):        Omnidirectional
Vertical (take-off angle):  See figures 4-7 on page 4-12, 4-8 on
                            page 4-13, and 4-3 on page 4-7

                Figure 4-6. Vertical Whip with Reflector.

If a vertical whip must be used, there are several techniques to
improve the antenna radiation. If the antenna is mounted directly to
the radio, ground the radio. If the antenna is remoted from the radio
ground the antenna base plate. A 6-foot ground rod is preferable for
both. Ground radials (wires spread out like wheel spokes with the
antenna at the center) may improve the antenna radiation. Connect
these radials to the ground rod directly beneath the antenna.


---

4-12 ____________________________________ MCRP 6-22D

                                 TAKE-OFF ANGLE

                            70°    80° 90° 80°   70°

                       60°                            60°
                                                              50°
               50°                                                    40°

          40°

     30°                                                                   30°

20°                                                                        20°

10°                                                                             10°

     15   10        5       0      -5 -10  -5         10 15

                                   dBi

                            9 MHz

        Figure 4-7. 10-Foot Vertical Whip (Vertical Pattern).

A ground radial system can be constructed easily from field tele-
phone wire (WDl/TT) and can be kept with the radio. Cut the field
wire into twenty 45-foot lengths, and remove 6 inches of insulation
from one end. Using twine or a clamp, bundle together the uninsu-
lated (bare) ends. Attach a 2-foot length of thick wire to the bare
ends so that the thick wire extends about one foot beyond the wire
bundle. Solder the wire bundle to ensure good electrical contact. In
use, the thick wire extending from the bundle connects the radials to
a ground rod. The radials are then spread out like wheel spokes with
the vertical whip at the center. Radio operators should experiment
with different radial systems to determine which one provides the
best connectivity.

A reflector placed approximately one-quarter wavelength behind a
vertical whip may also improve the whip’s performance. A reflector


---

Antenna Handbook ____________________________ 4-13

is a vertical wire, metallic pole, or another whip that is insulated
from the ground. It is placed so that the reflector, the whip, and the
distant station are on a straight line. The reflector will reflect radio
energy striking it and cause the energy to travel toward the distant
station, increasing the total energy radiated in the desired direction.
To work properly, the reflector must be longer than the whip. If the
reflector is shorter, it will act as a director, directing the radio signal
away from the distant station. A reflector is longer and is placed
behind the whip; a director is shorter and is placed between the
whip and the distant station. Adjust the position of the reflector
while listening to the distant station until the strongest signal is
received.

                                 TAKE-OFF ANGLE

                            70°    80° 90° 80°   70°

                       60°                            60°
                                                              50°
               50°                                                    40°

          40°

     30°                                                                   30°

20°                                                                        20°

10°                                                                             10°

     15   10        5       0      -5 -10  -5         10 15

                                   dBi

                            9 MHz

         Figure 4-8. 15-Foot Vertical Whip (Vertical Pattern).


---

4-14 ____________________________________ MCRP 6-22D

The length of a vertical whip antenna is calculated from the follow-
ing formula:

               Length in feet = Frequency in MHz 234

For WD-l/TT

                                                  225.50
               Length in feet = Frequency in MHz

Half-Wave Dipole

The horizontal half-wave dipole (doublet) antenna is used on short-
and medium-length sky wave paths (up to approximately 1,200
miles). Since it is relatively easy to design and construct, the dou-
blet is the most commonly used field expedient wire antenna. It is a
very versatile antenna; by adjusting the antenna’s height above
ground, the maximum gain can vary from medium take-off angles
(for medium path-length circuits) to high take-off angles (for short
path-length circuits). When the antenna is constructed for medium
take-off angle gain (a height of approximately one-half wave-
length), the doublet is a bidirectional antenna (i.e., the maximum
gain is at right angles to the wire). This is the broadside pattern nor-
mally associated with a half-wave dipole antenna. Format A in fig-
ure 4-9 shows this pattern in polar plot format.

Format B shows the radiation off the ends of the wire. It is easily
seen by comparing with format A that for maximum gain, a doublet
one-half wavelength above ground should be constructed so that the
side of the antenna points in the direction of the distant station. If
the antenna is lowered to only one-quarter wavelength above
ground, format C results. This lower antenna height produces


---

Antenna Handbook ____________________________ 4-15

maximum gain at high take-off angles. In format D, the radiation
off the ends of the doublet also has maximum gain at high take-off
angles. This means that for short path-length circuits, which require
high take-off angles, a doublet antenna one-quarter wavelength
above ground produces almost omnidirectional coverage.

   H= λ             H= λ

        2                2

A                B

       H= λ               H= λ

              4                    4

C                D

Figure 4-9. Illustrative Doublet Antenna Patterns.

The vertical plots included for half-wave dipole antennas are given
for heights from 8 to 12 meters. The plot for 8 meters shows that for
3 and 9 MHz the antenna has high-angle radiation. At those fre-
quencies the antenna is close to ground (compared to a half-wave-
length). The pattern for 18 MHz shows the characteristic
bidirectional pattern since 8 meters is a half-wave at 18 MHz.

The half-wave dipole is a balanced resonant antenna (see fig. 4-10
on page 4-16). It produces its maximum gain for a very narrow


---

4-16 ____________________________________ MCRP 6-22D

range of frequencies, normally 2 percent above or below the design
frequency. Since frequency assignments are usually several mega-
hertz apart, it is necessary to construct a separate dipole for each fre-
quency assigned (see figs. 4-11 and 4-12 on page 4-17, and 4-13 on
page 4-19). If space and other resources are unavailable to erect sep-
arate dipoles, three or four dipoles can be combined to occupy the
space normally required for one.
Each wire is a half-wavelength for an assigned frequency. The sepa-
rate dipoles are connected to the same center insulator, or preferably
a balun, and are fed by a single coaxial cable. When the antenna is

                Figure 4-10. Half-Wave Dipole Antenna.


---

Antenna Handbook ____________________________ 4-17

                                 TAKE-OFF ANGLE

                            70°  80° 90° 80°     70°

                       60°                            60°
                                                              50°
               50°                                                    40°

          40°                                                               30°

     30°

20°                                                                             20°

10°                                                                              10°

     15   10        5       0    -5  -10  -5          10 15

                                     dBi

                    3 MHz                 9 MHz

     Figure 4-11. 8-Meter Half-Wave Dipole (Vertical Pattern).

                                 TAKE-OFF ANGLE

                            70°  80° 90° 80°     70°

                       60°                            60°
                                                              50°
               50°                                                    40°

          40°

     30°                                                                   30°

20°                                                                        20°

10°                                                                              10°

     15   10        5       0    -5  -10  -5          10 15

                                     dBi

               3 MHz                 9 MHz

Figure 4-12. 10-Meter Half-Wave Dipole (Vertical Pattern).


---

4-18 ____________________________________ MCRP 6-22D

fed with an assigned frequency, the doublet cut for that frequency
will radiate the energy. Up to four separate dipoles can be combined
in this manner. When constructing this antenna, examine the indi-
vidual frequency assignments to determine if one frequency is three
times as large as another. If this relationship exists between two fre-
quencies, one dipole cut in length for the lower of the two frequen-
cies will work well for both frequencies.

The length of a half-wave dipole is calculated from the following
relationship:

Dipole length = 142 meters or                       468 feet

Frequency in MHz               Frequency in MHz

The height of a half-wave dipole is figured using—

Height X/4 = 75 meters or                           246 feet

Frequency in MHz               Frequency in MHz

Height X/2 = 150 meters or                          492 feet

Frequency in MHz               Frequency in MHz

Use the right relationship for the right purpose. If the height rela-
tionship is used for the dipole length, the antenna will be too long
and will not work properly. Characteristics are—

Frequency range:           ± 2% of design frequency
Polarization:              Horizontal
Power capability:          1,000 watts
Radiation Pattern
Azimuthal (bearing):       Bidirectional λ/2 high
                           basically omnidirectional at λ/4 high
Vertical (takeoff angle):  See figures 4-11 and 4-12 on page
                           4-17, and 4-13 on page 4-19


---

Antenna Handbook ____________________________ 4-19

                                 TAKE-OFF ANGLE

                            70°  80° 90° 80°     70°

                       60°                            60°
                                                              50°
               50°                                                    40°

          40°

     30°                                                                   30°

20°                                                                        20°

10°                                                                             10°

     15   10        5       0    -5  -10  -5          10 15

                                     dBi

               3 MHz                 9 MHz

    Figure 4-13. 12-Meter Half-Wave Dipole (Vertical Pattern).

Inverted Vee

The inverted vee, or drooping dipole, is similar to a dipole but uses
only a single center support (see fig. 4-14 on page 4-20). Like a
dipole, it is designed and cut for a specific frequency and has a
bandwidth of 2 percent above or below the design frequency.
Because of the inclined sides, the inverted vee antenna produces a
combination of horizontal and vertical radiation—vertical off the
ends and horizontal broadside to the antenna. All the construction
factors for a dipole also apply for the inverted vee. The inverted vee
has less gain than a dipole, but using only a single support could
make this antenna the preferred antenna in some tactical situations
(see fig. 4-15 on page 4-21).


---

4-20 ____________________________________ MCRP 6-22D

Characteristics are—

.                           ± 2% of design frequency
                            Horizontal
Frequency range:            1,000 watts
Polarization:
Power capability:           Basically omnidirectional with combi-
Radiation pattern           nation polarization
Azimuthal (bearing):        See figure 4-15

Vertical (take-off angle):

Figure 4-14. Inverted Vee Antenna.


---

Antenna Handbook ____________________________ 4-21

                                 TAKE-OFF ANGLE

                            70°  80° 90° 80°     70°

                       60°                            60°
                                                              50°
               50°                                                    40°

          40°                                                               30°

     30°

20°                                                           20°

10°                                                                              10°

     15   10        5       0    -5  -10  -5          10 15

                                     dBi

               3 MHz                 9 MHz

               Figure 4-15. Inverted Vee (Vertical Pattern).

Long Wire

A long wire antenna is one that is long compared to a wavelength
(see fig. 4-16 on page 4-22). A minimum length is one-half wave-
length. However, antennas that are at least several wavelengths long
are needed to obtain good gain and directional characteristics. Con-
structing long wire antennas is simple, and there are no critical
dimensions or adjustments. A long wire antenna will accept power


---

4-22 ____________________________________ MCRP 6-22D

                     Figure 4-16. Long Wire Antenna.
and radiate it well on any frequency for which its overall length is
not less than one-half wavelength.
The gain and take-off angle of a long wire antenna depend on the
antenna’s length. The longer the antenna, the more gain, and the
lower the take-off angle. Gain has a simple relationship to length;
however, take-off angle is a bit more complicated. A long wire
antenna radiates a cone of energy around the tie wire, much like a
funnel with the antenna wire passing through the funnel opening.
The narrow part of the funnel would be the feed point, and the open
part would be toward the distant station. If the funnel were cut in
half, the resulting half cone would represent the pattern of the
antenna. As the antenna is lengthened, the cone of radiation (fun-
nel) moves closer and closer to the wire. Figure 4-17 shows pattern


---

Antenna Handbook ____________________________ 4-23

1X  2X                          3X

    Figure 4-17. Long Wire Radiation Patterns.

changes as the wire is lengthened. The patterns represent a view
from directly below the antenna.

In the three-wavelength pattern, for very low-angle radiation, posi-
tion the wire somewhat away from the direction of the distant sta-
tion so that the main lobe of radiation points at the receiving station.
If a higher take-off angle is required, point the wire directly at the
distant station. For take-off angles from 5 to 25 feet, the following
general off-axis angles will provide satisfactory radiation on toward
the distant station (see table 4-4).

    Table 4-4. Off-Axis Angle.

    Wire Length (Feet)  23456

Off-Axis Angle (Degrees) 30 20 13 10 10

To make a long wire antenna directional, place a terminating device
at the distant station end of the antenna. The terminating device
should be a 600-ohm, noninductive resistor capable of absorbing at


---

4-24 ____________________________________ MCRP 6-22D

least one-half of the transmitter power. Terminating resistors are
components of some radio sets but can also be fabricated locally
using supply system components (100-watt, 106-ohm resistor).

Constructing a long wire antenna requires only wire, support poles,
insulators, and a terminating resistor (if directionality is desired).
The only requirement is that the antenna be strung in as straight a
line as the situation permits. The antenna is only 15 to 20 feet above
ground, so tall support structures are not required. The antenna is
normally fed through a coupler that can match the antenna’s 600-
ohm impedance. Coaxial cable can be used if a 12 to 1 balun is
available to convert the coaxial cable 50-ohm impedance to the
required 600 ohms. Vertical radiation plots of this antenna are not
presented because of the great variation in the pattern as the length
changes. For take-off angles between 5 and 25 feet, use the off-axis
graph (table 4-4 on page 4-23) and the gain versus length graph
(table 4-5) to determine the proper antenna length. Characteristics
are—

Frequency range:            2 to 30 MHz
Polarization:               Vertical
Power capability:           1,000 watts
Radiation pattern
Azimuthal (bearing):        Bidirectional with terminating resistor
Vertical (take-off angle):  Depends on length

Inverted L

The inverted L is a combination antenna made up of a vertical sec-
tion and a horizontal section (see fig. 4-18). It provides omnidirec-
tional radiation for ground wave propagation from the vertical
element and high-angle radiation from the horizontal element for
short-range sky wave propagation. The classic inverted L has a
quarter-wave vertical section and a half-wave horizontal section


---

Antenna Handbook ____________________________ 4-25

                                       INSULATORS

                                      λ_

                                                  2
                                       ANTENNA WIRE

                              λ_

                                        4

RADIO

                          GROUND

Figure 4-18. Inverted L Antenna.

and is used for a very narrow range of frequencies. By using the
antenna couplers that are part of many radio sets, the dimensions of
the inverted L can be modified to allow ground wave and short-
range sky wave propagation over a range of frequencies. Using a
vertical height of 35 to 40 feet, the following horizontal lengths will
give reasonable performance for short-range sky wave circuits.

Table 4-5. Gain Versus Length.

Frequency Range (MHz) 2.5 to 4.0 3.5 to 6.0 5.0 to 7.0

Horizontal Length (Feet)  150     100  80


---

4-26 ____________________________________ MCRP 6-22D

                                 TAKE-OFF ANGLE

                            70°    80° 90° 80°   70°

                       60°                            60°
                                                              50°
               50°                                                    40°

          40°                                                               30°

     30°

20°                                                   20°

10°                                                                              10°

     15   10        5       0    -5  -10  -5          10 15

                                     dBi

                            3 MHz

          Figure 4-19. 40-Foot Inverted L (Vertical Pattern),
                                  150 Feet Long.

Orient the antenna like a dipole (i.e., the broad side of the antenna
should be toward the distant station). These lengths should not be
used outside the frequency ranges specified because the antenna
radiation pattern changes, and for frequencies much removed from
the range, the antenna will become directional off the wire end. (See
the sloping wire paragraphs on page 4-34 for using this directional
characteristic.) The inverted L antenna can be used as a substitute
for the dipole; however, it has less gain than a dipole, and its radia-
tion pattern varies with frequency (unlike a dipole). Figures 4-19,


---

Antenna Handbook ____________________________ 4-27

                                 TAKE-OFF ANGLE

                            70°    80° 90° 80°   70°

                       60°                            60°
                                                              50°
               50°                                                    40°

          40°                                                               30°

     30°

20°                                                   20°

10°                                                                              10°

     15   10        5       0    -5  -10  -5          10 15

                                     dBi

                            5 MHz

Figure 4-20. 40-Foot Inverted L Antenna (Vertical Pattern),
                               80 Feet Long.

4-20, and 4-21 on page 4-28 illustrate vertical patterns of various
inverted L antennas. Characteristics are—

Frequency range:                     Less than 2:1 over design frequency
Polarization:                        Vertical from vertical section
                                     Horizontal from horizontal section
Power capability:                    1,000 watts
Radiation pattern
Azimuthal (bearing):                 Omnidirectional
Vertical (take-off angle):           See figures 4-19, 4-20, and 4-21 on
                                     page 4-28


---

4-28 ____________________________________ MCRP 6-22D

                                 TAKE-OFF ANGLE

                            70°    80° 90° 80°   70°

                       60°                            60°
                                                              50°
               50°                                                    40°

          40°                                                               30°

     30°

20°                                                            20°

10°                                                                              10°

     15   10        5       0    -5  -10  -5          10 15

                                     dBi

                            4 MHz

          Figure 4-21. 40-Foot Inverted L (Vertical Pattern),
                                  100 Feet Long.

Sloping Vee

The sloping vee is a medium- to long-range sky wave antenna that
is simple to construct in the field. Antenna gain and directivity
depend on the leg length. For reasonable performance, the antenna


---

Antenna Handbook ____________________________ 4-29

should be at least one wavelength long, but preferably several
wavelengths long (see fig. 4-22).

                                            INSULATORS

                 ANTENNA WIRE

POLE

      LEAD WIRE                          POLE

                RADIO
                         GROUND

      Figure 4-22. Sloping Vee Antenna.


---

4-30 ____________________________________ MCRP 6-22D

A compromise tactical sloping vee can be constructed using 500-
foot legs and a 40-foot support mast. The angle between the two
legs is adjusted to provide maximum radiation at the desired take-
off angle. Table 4-6 shows the angles between legs (apex angle) that
will give poor results for the distances indicated.

Table 4-6. Angle Between Antenna Legs
                for Poor Results.

Path Length  700 to 1000  1000 to 1500  over 1500
    (Miles)

Apex Angle

(Degrees)    60           45            30

To make the antenna directional, use terminating resistors on each
leg on the open part of the vee. The terminating resistors should be
300 ohms and be capable of handling one-half of the transmitter’s
power output. These terminations are either procured or fabricated
locally using supply system parts (100-watt, 106-ohm resistor).
Using the terminating resistors, the antenna is aimed so that the line
cutting the vee in half is pointed at the distant station.


---

Antenna Handbook ____________________________ 4-31

                                 TAKE-OFF ANGLE

                            70°    80° 90° 80°   70°

                       60°                            60°
                                                              50°
               50°                                                    40°

          40°

     30°                                                                   30°

20°                                                                        20°

10°                                                                             10°

     15   10        5       0    -5  -10  -5          10 15

                                     dBi

                            9 MHz

         Figure 4-23. 40-Foot Sloping Vee (Vertical Pattern),
                      500 Feet Long, 30° Apex Angle.

The sloping vee is normally fed with a 600-ohm, open-wire feed
line. One side of the feed line is connected to one leg with the other
side connected to the other leg. The open-wire feed line can be con-
nected to a 12 to 1 balun, which is then connected to standard coax-
ial cable. Figures 4-23, 4-24 on page 4-32, and 4-25 on page 4-33
illustrate the vertical patterns for various sloping vee antennas.


---

4-32 ____________________________________ MCRP 6-22D

                                 TAKE-OFF ANGLE

                            70°  80° 90° 80°     70°

                       60°                            60°
                                                              50°
               50°                                                    40°

          40°                                                               30°

     30°

20°                                                   20°

10°                                                                              10°

     15   10        5       0    -5  -10  -5          10 15

                                     dBi

               3 MHz                 9 MHz

Figure 4-24. 40-Foot Sloping Vee Antenna (Vertical Pattern),
                    500 Feet Long, 45° Apex Angle.

Characteristics are—                 3 to 30 MHz
                                     Horizontal
Frequency range:                     Depends on terminating resistors
Polarization:
Power capability:                    Directional (20° either side of
Radiation pattern                    direction of radiation)
Azimuthal (bearing):                 See Figures 4-23, 4-24 on page
                                     4-32, and 4-25 on page 4-33
Vertical (takeoff angle):


---

Antenna Handbook ____________________________ 4-33

                                 TAKE-OFF ANGLE

                            70°  80° 90° 80°     70°

                       60°                            60°
                                                              50°
               50°                                                    40°

          40°                                                               30°

     30°

20°                                                   20°

10°                                                                              10°

     15   10        5       0    -5  -10  -5          10 15

                                     dBi

               3 MHz                 9 MHz

Figure 4-25. 40-Foot Sloping Vee Antenna (Vertical Pattern),
                    500 Feet Long, 60° Apex Angle.

Sloping Wire

The sloping wire antenna is simple and easy to construct. It requires
only one support (see fig. 4-26 on page 4-34). A version of the long
wire antenna, the sloping wire produces best results when it is long
compared to a wavelength. Tactical sloping wires vary in length
from 45 to over 500 feet. The shorter lengths perform rather poorly
and should be used only when no other antenna can be erected. The


---

4-34 ____________________________________ MCRP 6-22D

longer lengths (e.g., 250 feet, 500 feet) can produce good radiation
for medium to long sky wave paths.

                              MAXIMUM RADIATION
                      INSULATOR

ANTENNA WIRE
                             RADIO

                                    GROUND

                          Figure 4-26. Sloping Wire.

A sloping wire can be either terminated or unterminated. If avail-
able, use 600-ohm termination because this makes the antenna
impedance fairly constant, and a balun can be used to match the
antenna to a transmitter. If the antenna is unterminated, use a cou-
pler to match the transmitter to the antenna.

The low end of the wire should be oriened toward the receiving sta-
tion. If the wire is unterminated, feed the antenna at the low end. If
a terminating resistor is used, feed the antenna low end. Figure 4-27
and figures 4-28 and 4-29 on page 4-36 illustrate the vertical pat-
terns for various sloping wire antennas.


---

Antenna Handbook ____________________________ 4-35

Characteristics are—                 Depends on wire length/configura-
                                     tion
Frequency range:                     Vertical
                                     Determined by terminating resistor
Polarization:
Power capability:                    Bidirectional for unterminated
Radiation pattern                    Directional for terminated
Azimuthal (bearing):                 See figure 4-27 and figures 4-28 and
                                     4-29 on page 4-36
Vertical (take-off angle):

                                 TAKE-OFF ANGLE

                            70°  80° 90° 80°     70°

                       60°                            60°
                                                              50°
               50°                                                    40°

          40°                                                               30°

     30°

20°                                                          20°

10°                                                                              10°

     15   10        5       0    -5  -10  -5          10 15

                                     dBi

               3 MHz                 9 MHz

     Figure 4-27. 100-Foot Sloping Wire (Vertical Pattern).


---

4-36 ____________________________________ MCRP 6-22D

                                     TAKE-OFF ANGLE

                                70°  80° 90° 80°     70°

                           60°                            60°
                                                                  50°
                   50°                                                    40°

              40°                                                               30°

         30°

20°                                                                                  20°

10°                                                                                  10°

     15       10        5       0    -5  -10  -5          10 15

                                         dBi

                        3 MHz                 9 MHz

         Figure 4-28. 250-Foot Sloping Wire (Vertical Pattern).

                                     TAKE-OFF ANGLE

                                70°  80° 90° 80°     70°

                           60°                            60°
                                                                  50°
                   50°                                                    40°

              40°                                                               30°

     30°

20°                                                              20°

10°                                                                                  10°

     15       10        5       0    -5  -10  -5          10 15

                                         dBi

                   3 MHz                 9 MHz

         Figure 4-29. 234-Foot Sloping Wire (Vertical Pattern).


---

Antenna Handbook ____________________________ 4-37

Vertical Half-Rhombic

The vertical half-rhombic antenna is a version of the long wire
antenna that uses a single center support (see fig. 4-30). Easily con-
structed, this antenna has a narrow width (as wide as the center sup-
port guys), which allows several to be installed in a relatively
narrow area. The vertical half-rhombic antenna radiates a medium-
to low-angle signal, making it a good choice for medium- to long-
range sky wave circuits. Normally, the 500-foot version is the max-
imum length of antenna that most tactical situations will allow;
however, the vertical radiation pattern for a 1,000-foot version is
included, so that if the opportunity exists, the antenna can be used
for excellent results.

             Figure 4-30. Vertical Half-Rhombic Antenna.


---

4-38 ____________________________________ MCRP 6-22D

The vertical half-rhombic uses a single wire feed either through a
coupler or a balun (12 to 1). One of the two terminals of the coupler
or balun is attached to the antenna, while the other terminal is
grounded. Like other terminated antennas, the terminating resistor
(600 ohms) should be able to handle one-half of the transmitter’s
power output. Terminators can be procured or fabricated locally
(100-watt, 106-ohm resistor).

The orientation of this antenna depends on the frequency bands
being worked. Below 12 MHz, point the terminated end of the
antenna at the distant station; above 12 MHz, aim the antenna 10
feet to either side of the distant station. Figures 4-31 and 4-32 illus-
trate the vertical patterns for various vertical half-rhombic antennas.
Characteristics are—

Frequency range:            2 to 30 MHz
Polarization:               Vertical
Power capability:           Determined by terminating resis-
                            tor
Radiation pattern
Azimuthal (bearing):        Directional
Vertical (take-off angle):  See Figures 4-31 and 4-32


---

Antenna Handbook ____________________________ 4-39

                                 TAKE-OFF ANGLE

                            70°  80° 90° 80°     70°

                       60°                            60°
                                                              50°
               50°                                                    40°

          40°                                                               30°

     30°

20°                                                   20°

10°                                                                              10°

     15   10        5       0    -5  -10  -5          10 15

                                     dBi

               3 MHz                 9 MHz

Figure 4-31. 50-Foot Vertical Half-Rhombic (Vertical Pattern),
                                500 Feet Long.

                                 TAKE-OFF ANGLE

                            70°  80° 90° 80°     70°

                       60°                            60°
                                                              50°
               50°                                                    40°

          40°                                                               30°

     30°

20°                                                                              20°

10°                                                                              10°

     15   10        5       0    -5  -10  -5          10 15

                                     dBi

               3 MHz                      9 MHz

Figure 4-32. 50-Foot Vertical Half-Rhombic (Vertical Pattern),
                               1,000 Feet Long.


---

4-40 ____________________________________ MCRP 6-22D

                 HF NVIS COMMUNICATIONS

NVIS propagation is simply sky wave propagation that uses anten-
nas with high-angle radiation and low operating frequencies. Just as
the proper selection of antennas can increase the reliability of a
long- range circuit, short-range communications also require proper
antenna selection. NVIS propagation is one more weapon in the
communicator’s arsenal.

To communicate over the horizon to an amphibious ship on the
move, or to a station 100 to 300 kilometers away, the operators
should use NVIS propagation. The ship’s low take-off angle
antenna is designed for medium and long-range communications.
When the ship’s antenna is used, a skip zone is formed. This skip
zone is the area between the maximum ground wave distance and
the shortest sky wave distance where no communications are possi-
ble. Depending on operating frequencies, antennas, and propagation
conditions, this skip zone can start at roughly 20 to 30 kilometers
and extend out to several hundred kilometers, preventing communi-
cations with the desired station.

NVIS propagation uses high take-off angle (60° to 90°) antennas to
radiate the signal almost straight up. The signal is then reflected
from the ionosphere and returns to Earth in a circular pattern all
around the transmitter. Because of the near-vertical radiation angle,
there is no skip zone. Communications are continuous out to several
hundred kilometers from the transmitter. The nearly vertical angle
of radiation also means that lower frequencies must be used. Gener-
ally, NVIS propagation uses frequencies up to 8 MHz.

The steep up and down propagation of the signal gives the operator
the ability to communicate over nearby ridge lines, mountains, and
dense vegetation. A valley location may give the operator terrain
shielding from hostile intercept and also protect the circuit from


---

Antenna Handbook ____________________________ 4-41

ground wave and long-range sky wave interference. Antennas used
for NVIS propagation need good high take-off angle radiation with
very little ground wave radiation (see fig. 4-33).
Using the HF antenna selection matrix (table 4-4 on page 4-8), the
AS-2259/GR and half-wave dipole are the only antennas listed that
meet the requirements of NVIS propagation. While the inverted vee
and inverted L antennas have high-angle radiation, they also can
have strong ground wave radiation that could interfere with the
close-in NVIS communications. These antennas could be used if
terrain shielding prevented the ground wave signal from propagat-
ing to the distant station.

                      Figure 4-33. NVIS Propagation.


---

4-42 ____________________________________ MCRP 6-22D

The dipole antenna pattern is illustrated in figures 4-11 and 4-12 on
page 4-17 and figure 4-13 on page 4-19. The patterns for 3 and 9
MHz show that large amounts of energy are directed up in the 60°
to 90° range. Also, the pattern is the same on both sides of the 90°
line. This means that a low dipole would be a good antenna for
NVIS propagation. The pattern at 18 MHz is not important because
NVIS propagation normally does not use frequencies much above 8
MHz. Set up dipoles on whatever supports are available. Ensure
that the height is below a quarter-wavelength, which at 8 MHz is
about 30 feet.

Mobile CPs do not always have time to set up a dipole antenna or
an AS-2259/GR. Several options are possible. If a Marine is in an
MRC-138 vehicle, then use a tilt whip adapter and the 16-foot whip
antenna to try to obtain high-angle radiation (fig. 4-34). Tilt the
antenna at least 30°. Another option is disconnecting the whip
antenna and connecting a 32-foot wire to the antenna base. Run the
wire parallel to the ground, and stake it at the distant end the same
height above the ground as the radio end. Insulate the staked end
from the ground to prevent radio damage (fig 4-35).

             Figure 4-34. AN/MRC-138 with NVIS Antenna.


---

Antenna Handbook ____________________________ 4-43

    Figure 4-35. AN/MRC-138 with Stationary NVIS Antenna.

                                   WARNING
THE WIRE MUST BE PROTECTED SO THAT MARINES DO
NOT WALK INTO IT. IT CARRIES ENOUGH RF ENERGY DUR-
ING TRANSMISSION TO CAUSE SEVERE INJURIES.

When using a manpack radio like the AN\PRC-104, the whole radio
can be rotated so that the 8-foot antenna is tilted at least 30°.
Because of the antenna’s flexibility, it will need support on the far
end. This support must be a good insulator. Ensure that Marines
keep clear of the antenna. Characteristics are—

Frequency range:            2 to 30 MHz
Polarization:               Vertical or horizontal
Power capability:           100 to 400 Watts
Radiation pattern
Azimuthal (bearing):        Basically omnidirectional
Vertical (take-off angle):  Minimizes skip zone using 90°,
                            40°, and 20° take-off angle

                            (reverse blank)


---

                         Chapter 5

   VHF and UHF Antenna Selection

                          FREQUENCIES

The VHF portion of the radio spectrum extends from 30 to 300
MHz. The UHF range reaches from 300 to 3,000 MHz (3 GHz).
Both frequency ranges are extremely useful for short-range (less
than 50 km) communications. This includes point-to-point, mobile,
air-to-ground, and general purpose communications. A wavelength
at these frequency ranges is considerably shorter than those in the
HF range, and simple antennas are much smaller.

Because the VHF and UHF antennas are small, it is possible to use
multiple radiating elements to form arrays, which provide a consid-
erable gain in a given direction or directions. An array is an
arrangement of antenna elements, usually dipoles, used to control
the direction in which most of the antenna’s power is radiated.

Generally, many more types of antennas are available and useful in
the VHF and UHF range than at HF. Several of these types will be
discussed in this chapter since they are useful for various field
applications.

Within the VHF and UHF portion of the spectrum, there are several
subfrequency bands for specific uses. The 118 to 136 MHz range is
generally reserved on a worldwide basis for air-to-ground commu-
nications and is known as the VHF aircraft band. The 225 to 400
MHz range is also allocated for air-to-ground use and is known as
the UHF aircraft band. The 148 to 174 MHz and 450 to 470 MHz


---

5-2 _____________________________________ MCRP 6-22D

ranges are assigned to many activities, including citizens (public)
communications (e.g., mobile, police, weather, taxis, and general
purpose).

                          POLARIZATION

In many countries, FM and TV broadcasting in the VHF range use
horizontal polarization. One reason is because it reduces ignition
interference, which is mainly vertically polarized. Mobile commu-
nications often use vertical polarization for two reasons. First, the
vehicle antenna installation has physical limitations, and second, so
that reception or transmission will not be interrupted as the vehicle
changes its heading to achieve omnidirectionality.

Using directional antennas and horizontal polarization (when possi-
ble) will reduce manmade noise interference in urban locations.
Horizontal polarization, however, should be chosen only where an
antenna height of many wavelengths is possible. Ground reflections
tend to cancel horizontally polarized waves at low angles. Use only
vertically polarized antennas when the antenna must be located at a
height of less than about 10 meters above ground, or where omnidi-
rectional radiation or reception is desired.

                    GAIN AND DIRECTIVITY

VHF and UHF (above 30 MHz) antenna gain and directivity are
extremely important for several reasons. Assuming the same
antenna gain and propagation path, the received signal strength
drops as frequency is increased. At VHF and UHF, more of the
received signal is lost in the transmission line than is lost at HF. A
10 to 20 dB loss is not uncommon in a 30 meter length of coaxial
line at 450 MHz.


---

Antenna Handbook ______________________________ 5-3

At frequencies below 30 MHz, system sensitivity is almost always
limited by receiver noise rather than by noise external to the
antenna (e.g., atmospheric and manmade interference). Generally,
wider modulation or signal bandwidths are employed in VHF and
UHF transmissions than at HF. Since system noise power is directly
proportional to bandwidth, additional antenna gain is necessary to
preserve a usable S/N ratio.

VHF and UHF antenna directivity (gain) aids security by restricting
the amount of power radiated in unwanted directions. Receiver sen-
sitivity is generally poorer at VHF and UHF (with the exception of
high quality state-of-the-art receivers). Obstructions (e.g., build-
ings, trees, hills) may seriously decrease the signal strength avail-
able to the receiving antenna because VHF and UHF signals travel
a straight LOS path.

Gain

Obtaining communications reliability over difficult VHF and UHF
propagation paths requires considerable attention to the design of
high-gain, directive antenna arrays at least at one end of the com-
munications link. Unlike HF communications, the shorter VHF and
UHF wavelengths support walkie-talkie transceivers and simple
mobile transmission units. Communicating or receiving with such
devices over distances beyond 1 or 2 km requires maximum
antenna gain at the base station site or fixed end of the link.

Directivity

Because VHF and UHF wavelengths are so short, reliable predic-
tion of diffraction, refraction, and reflection effects are not practi-
cal. One must depend entirely on LOS paths. For best results,
attempt to establish VHF and UHF communications paths that are
as free of obstacles as possible. The VHF and UHF wavelengths are


---

5-4 _____________________________________ MCRP 6-22D

short enough that it is possible to construct resonant antenna arrays.
An array provides directivity (the ability to concentrate radiated
energy into a beam that can be aimed at the intended receiver).
Arrays of resonant elements, (e.g., half-wave dipoles), can be con-
structed of rigid metal rods or tubing or of aluminum or copper foil
laid out or pasted on a flat nonconducting surface. Directing power
helps to increase the range of the communications path and tends to
decrease the likelihood of interception or jamming from hostile
radio stations. However, such highly directive antennas place an
added burden on the operator to ensure that the antenna is pointed
properly.

                     TRANSMISSION LINES

Choosing transmission lines at VHF and UHF depends on many
factors. Generally, twin-lead has much lower loss than small diame-
ter coaxial cable. Twin-lead is preferred over coaxial when trans-
mission line lengths exceed 10 meters. Twin-lead is much more
susceptible to picking up objectionable manmade noise than is well
shielded coaxial cable. Also, most modern VHF and UHF equip-
ment employs unbalanced input and output circuitry with a 50-ohm
impedance. Such equipment requires either using coaxial cable or a
balun to feed a twin-lead or two-wire balanced transmission line.
Noise pickup by twin-lead transmission lines may be considerably
reduced by twisting the line along its length.

When using twin-lead, the spacing between the wires of the line
should not exceed 0.05 λ. If the spacing is an appreciable part of a
wavelength, the line will radiate and receive energy like the
antenna. This effect will alter the intended antenna radiation pat-
tern. To further reduce local noise pickup, keeping twin-lead clear
of metal objects (e.g., gutters and window frames). Twice the wire
spacing in the twin-lead is sufficient clearance.


---

Antenna Handbook ______________________________ 5-5

                            RADIATORS

A radiator is the antenna component that transmits RF energy.

Vertical Radiator

A vertical radiator for general coverage use at UHF should be one-
quarter wavelength long. Longer vertical antennas do not have their
maximum radiation at right angles to the line of the radiator. They
are not practical for use where the greatest possible radiation paral-
lel to the Earth is desired. It is important that the antenna be decou-
pled from the coaxial transmission line. This will prevent unwanted
radiation currents from flowing along the outside of the cable,
which will distort the antenna pattern. Use a sleeve, ground plane,
or counterpoise to perform decoupling.

Cross Section Radiator

Aluminum tubing is commonly used for dipoles and radiation ele-
ments. They are so short that the expense of larger diameter con-
ductors is relatively low. With such conductors, the antenna will
tune much more broadly. This is very desirable, particularly when
an antenna or array is used over an entire frequency band.

Large cross section radiators have a shorter resonant length than a
radiator or mode of small diameter wire. A tubing radiator mode is
seldom longer than 90 percent of a half-wavelength for a dipole at
frequencies above 100 MHz.

                            INSULATION

Insulation or dielectric material quality is more important at VHF
and UHF than at frequencies below 30 MHz. Many insulators that
perform well in the HF range are poor or unusable for fabricating


---

5-6 _____________________________________ MCRP 6-22D

antennas operating at frequencies above 100 MHz. Ordinary wood
is a good example. In minimal rainfall climates, using very dry red-
wood, maple, or fir boiled in paraffin wax for several hours is fairly
successful up to frequencies as high as 560 MHz. The neck of a
glass soft drink bottle or other similar items work reasonably well
up to frequencies as high as 1 GHz. Several modern plastics, used
throughout the world, also make excellent insulators (e.g., fiber-
glass, polystyrine, polyethylene, and Styrofoam). Pieces of these
plastics in usable shapes can be found almost everywhere, and, with
a little ingenuity, can be used as insulation in the design of many
VHF and UHF antennas. Avoiding insulation entirely is possible by
choosing an antenna design with elements supported at lower volt-
age (high current) points (e.g., the Yagi antenna).

                         INTERFERENCE

Obtaining optimum coupling between the antenna and transmission
line and between the transmission line and the receiver or transmit-
ter circuits is a major concern.

Noise

While atmospheric and manmade noise usually limit the ultimate
sensitivity of an HF receiving system, a VHF or UHF receiving sys-
tem is almost always limited by receiver noise. External (atmo-
spheric) noise is virtually nonexistent at frequencies higher than
100 MHz. Automobile ignition and other forms of manmade static
affect frequencies well into the UHF band.

Multipath Interference

VHF and UHF radio waves are highly attenuated when they travel
through most materials. Select a location which is as free as possi-
ble of obstacles in the direction of desired propagation. It is possible


---

Antenna Handbook ______________________________ 5-7

to use relay stations or carefully placed reflectors when obstacles
interfere with the direct path.

When operating from areas where the transmission path is bounded
rather closely by reflective objects (e.g., buildings or metal towers)
the possibility of multipath exists. Whenever conditions are such
that radio signals travel two or more separate paths from the trans-
mitting to the receiving antenna, a phenomenon known as an inter-
ference pattern is created around the receiving antenna. There will
be zones where the incoming signal is received very strongly (con-
structive interference) with areas of weak signal between (destruc-
tive interference). If each of the two signal has the same strength,
complete cancellation will occur in the destructive interference
zones, and no signal will be received. At VHF and UHF the created
interference patterns are small enough to permit moving out of a
destructive zone and into a constructive zone within the space of
only a meter or so.

It is difficult to predict the location of an interference pattern. Opti-
mizing antenna location is a must for good results. Sometimes a
secondary path is created as the result of reflection from a moving
object (e.g., an automobile or airplane). The resulting interference
pattern will not be stationary, but will move past the antenna so that
the received signal appears to flutter between good and poor recep-
tion. Multipath problems can be particularly severe when either the
transmitting or receiving antenna is moving. Diversity techniques
such as two separated antennas or circular polarization should help
to alleviate the effects of multipath interference. High gain (highly
directive) antennas, both on the transmitter and the receiver, can
reduce signal loss from multipath interference.


---

5-8 _____________________________________ MCRP 6-22D

Vegetated Areas

VHF and UHF communications through a dense forest over dis-
tances of more than a few kilometers can often be very difficult. In
many tropical regions, trees and underbrush absorb VHF and UHF
radio energy. In addition to the ordinary free space loss between
transmitting and receiving antennas, a radio wave passing through a
forest undergoes an additional loss that is measured in dBs per km.
This extra loss increases rapidly as the transmission frequency
increases.

Near the ground (i.e., antenna heights of less than 3 meters) vertical
polarization is preferred. However, if it is possible to elevate both
receiving and transmitting antennas as much as 10 to 20 meters,
horizontal polarization is preferable to vertical polarization. Con-
siderable reduction in total path loss results if either or both the
transmitting and receiving antennas can be placed above the tree
level through which communications must be made.

Increasing antenna gain may provide an improved signal strength
that exceeds the added antenna gain by reducing the number of
multipath reflections from trees along the propagation path. The
higher gain antenna exhibits a much narrower radiation pattern
which includes fewer trees in its beam. Generally, this effect is most
noticeable with antenna gains higher than 15 dB or azimuthal half-
power beam of less than 35°.

Communications through heavily forested areas over distances
greater than 10 kms may require a transmitter power of at least 10
watts and antenna gains of 10 dB or more, depending on antenna
height, terrain features, type of trees, moisture content, and numer-
ous other factors. If communication is required over distances


---

Antenna Handbook ______________________________ 5-9

exceeding 30 kms, it may be necessary to use high-angle iono-
spheric propagation in the 3 to 10 MHz frequency range (i.e., HF)
to obtain a reliable circuit.

                        ANTENNA TYPES

The vertical whip is the most commonly used antenna. The OE-254
is a broadband, omnidirectional, biconical antenna. Antennas
located in places which are enclosed mostly in a metal shell or con-
tainer (e.g., an automobile) cannot be expected to perform as well
as if located outside the enclosure. Most of the antenna types usable
in the HF range are also usable in the VHF and UHF bands. In the
VHF and UHF ranges, use the same antenna for transmitting and
receiving.

Vertical Whip

It is easy to use and part of every radio set. In mobile situations, it is
the only antenna that can be used. In stationary operations, the ver-
tical whip is not a good choice. It cannot be elevated for good omni-
directional VHF LOS communications, and it radiates in useless
directions if communications are point-to-point.

If the tactical situation prevents using an antenna other than the ver-
tical whip, steps can be taken to improve its performance. Ensure
that the antenna is vertical. This can be a problem when using the
manpack short whip or tape in the prone position. Use the flexible
base on the tape to ensure that the antenna is in a vertical position.

Place a reflector behind the whip to direct radiation in a general
direction. A reflector is a vertical wire or another whip placed one-
quarter wavelength behind the radiating whip. Place the reflector at
the same height as the whip, and insulate it from the ground. The


---

5-10 ____________________________________ MCRP 6-22D

reflector reflects some of the radio energy back towards the whip
and provides a broad beam of energy towards the distant station.
Characteristics are—

Frequency range:            30 to 88 MHz
Polarization:               Vertical
Power capability:           Matched to specific radio
Radiation pattern
Azimuthal (bearing):
Vertical (take-off angle):

OE-254

The OE-254 (fig. 5-1) is scheduled to replace the RC-292. Unlike
the RC-292, the OE-254 does not require tuning for specific bands
and can cover the 30 to 87.975 MHz VHF band without adjust-
ments. Three upward and three downward radial elements simulate
two cones which provide omnidirectional VHF LOS radiation. The
antenna is usually mounted on a 33-foot 8-inch mast for an overall
height of 41 feet 9 inches. The antenna may be installed at lower
heights; however, care should be taken to ensure that the lower and
upper mast adapter assemblies are always used. An 80-foot coaxial
cable comes with the antenna for direct connection to a radio.

Frequency range:            30 to 88 MHz
Polarization:               Vertical
Power capability:           350 watts
Radiation pattern
Azimuthal (bearing):        Omnidirectional
Vertical (take-off angle):


---

Antenna Handbook ____________________________ 5-11

                  Figure 5-1. Installed OE-254 Antenna.


---

5-12 ____________________________________ MCRP 6-22D

Antenna Within Vehicle Interior

Antennas located inside vehicles will lose some radiation through
the window openings. It is difficult to predict how much radiation
will escape or how much the original antenna radiation pattern will
be affected by the enclosure. The pattern modification depends on
the vehicle size and its openings and on the location of the antenna
inside. Select antennas which operate above the cutoff frequency of
the window openings. An opening in a metal container which is less
than 0.5 λ in the dimension perpendicular to the plane of polariza-
tion will be severely attenuated or cutoff as it traverses the opening.
Lower frequency waves will suffer even greater attenuation.

HF Antenna Types Usable at VHF and UHF

Simple vertical half-wave dipole and quarter-wave monopole
antennas are very popular for omnidirectional transmission and
reception over short-range distances. For longer distances, rhombic
antennas made of wire and somewhat similar in design to HF ver-
sions may be used to good advantage at frequencies as high as 1
GHz. Another HF antenna, the Yagi, is equally popular in the VHF
and UHF ranges. However, while Yagis with more than three or
four elements are seldom used at HF, Yagi designs with as many as
15 elements, or more, are quite common at VHF and UHF.

Dual-Function Antennas

Because there is no sure method of accurately pointing a transmit-
ting antenna, accomplish this task by first using the antenna in
reception and orienting it for the best received signal. Positioning
the antenna in this manner assures that, according to the reciprocity
theorem, the antenna is optimally oriented for transmitting. If two-
way communications are desired (i.e., transmitting and receiving
alternately) a switch to toggle quickly back and forth between trans-
mitter and receiver is required. Design the switch so that it will not


---

Antenna Handbook ____________________________ 5-13

upset the impedance on the transmission line, causing unwanted
received or transmitted power loss. When using coaxial cable as
transmission line, use suitable, commercially available, low-loss
coaxial antenna switching relays if possible.
In the 225 to 400 MHz and 450 to 470 MHz frequency ranges, most
antennas are quite small. Mount two identical antennas, using one
for transmitting and one for receiving. Separate transmission lines
may then be used, eliminating the need for an antenna relay.

                                                                     (reverse blank)


---

Antenna Handbook ______________________________ 6-1

                         Chapter 6

      Field Repair and Expedients

Antennas sometimes break or sustain damage, causing poor com-
munications or communications failure. If a spare is available, use
it to replace the damaged antenna. When there is no spare, construct
an expedient antenna. The following paragraphs discuss antenna
and support repair and constructing and adjusting expedient anten-
nas.

                     REPAIR TECHNIQUES

Whip Antennas

A broken antenna (whip) can be repaired temporarily. If the whip is
broken into two sections, rejoin the sections. Remove the paint and
clean the sections where they will rejoin to ensure a good electrical
connection. Place the sections together, secure them with a pole or
branch, and lash them with bare wire or tape above and below the
break (see fig. 6-1 (A) on page 6-2).

If the whip is badly damaged, use a length of field wire (WD1/TT)
the same length as the original antenna. Remove the insulation from
the lower end of the field wire antenna, twist the conductors to-
gether, stick them in the antenna base connector, and secure with a
wooden block. Use either a pole or a tree to support the antenna
wire (see fig. 6-1 (B) on page 6-2).


---

6-2 _____________________________________ MCRP 6-22D

           Figure 6-1. Emergency Repair of Broken Whip.

Wire Antennas

Expedient wire antenna repair may involve repairing or replacing
the antenna or transmission line wire or repairing or replacing the
assembly that supports the antenna. When one or more antenna
wires are broken, repair the antenna by reconnecting the broken
wires. Lower the antenna to the ground, clean the ends of the wires,
and twist the wires together. Solder the connection if possible. If the
antenna is damaged beyond repair, construct a new one. Make sure
that the substitute wire is the same length as the original.
Antenna supports may also require repair or replacement. Use a
substitute item in place of a damaged support. If properly insulated,
any material of adequate strength can be used. If the radiating ele-
ment is not properly insulated, field antennas may be shorted to
ground and rendered ineffective. Many commonly found items can


---

Antenna Handbook ______________________________ 6-3

be used as field expedient insulators (fig. 6-2). The best are plastic
or glass, including plastic spoons, buttons, bottle necks, and plastic
bags. Less effective than plastic or glass, but better than no insula-
tors at all, are wood and rope, or both, in that order. The radiating
element—the actual antenna wire—should touch only the antenna
terminal and be physically separated from all other objects, other
than the supporting insulator.

                                                   BEST

                                             PLASTIC BAG

BOTTLE NECK                           BUTTON
                       PLASTIC SPOON
                             GOOD

WOOD(DRY)
     FAIR

NYLON ROPE

RUBBER OR CLOTH STRIP(DRY)            NYLON ROPE

Figure 6-2. Improvised Insulators.


---

6-4 _____________________________________ MCRP 6-22D

Guys

Lines used to stabilize antenna supports are called guys. These lines
are usually wire, manila rope, or nylon rope. If a rope breaks, repair
it by tying the two broken ends together. If the rope is too short after
tying, lengthen it by adding another piece of rope or a piece of dry
wood or cloth. If a guy wire breaks, replace it with another piece of
wire. Figure 6-3 shows how to repair a guy line with a spoon.

Masts

Some antennas are supported by masts. If a mast breaks, replace it
with another mast the same length. If long poles are not available,
overlap short poles and lash them with rope or wire to provide a
pole of the required length. Figure 6-3 shows how to make an expe-
dient mast repair.

    TIPS ON CONSTRUCTION AND ADJUSTMENT

Constructing the Antenna

The best kinds of wire for antennas are copper and aluminum. In an
emergency, use any type that is available. The exact length of most
antennas is critical. An expedient antenna should be the same length
as the antenna it replaces.

Antennas supported by trees can usually survive heavy wind storms
if the trunk of a tree or a strong branch is used as a support. To keep
the antenna taut and to prevent it from breaking or stretching as the
trees sway, attach a spring or old inner tube to one end of the
antenna. Another technique is to pass a rope through a pulley or
eyehook, attach the rope to the end of the antenna, and load the rope
with a heavy weight to keep the antenna tightly drawn.


---

Antenna Handbook ______________________________ 6-5

                Figure 6-3. Repaired Guy Line and Mast.
Guys used to hold antenna supports are made of rope or wire. To
ensure that wire guys will not affect antenna operation, cut the wire
into several short lengths and connect the pieces with insulators.


---

6-6 _____________________________________ MCRP 6-22D

Adjusting the Antenna

An improvised antenna may change a radio set’s performance. Use
the following methods to determine if the antenna is operating prop-
erly.

Use a distant station to test the antenna. If the signal received from
this station is strong, the antenna is operating satisfactorily. If the
signal is weak, adjust the antenna and transmission line height and
length to receive the strongest signal at a given receiver volume
control setting. This is the best method of tuning an antenna when
transmission is dangerous or forbidden.

Most Marine Corps cadets use the transmitter to adjust the antenna.
Set the transmitter controls in position for normal operation. Then,
tune the system by adjusting the antenna height and length and the
transmission line length to obtain the best transmission output.

                                   WARNING
SERIOUS INJURY OR DEATH CAN RESULT FROM CONTACT
WITH THE RADIATING ANTENNA OR MEDIUM- OR HIGH-
POWER TRANSMITTER. TURN THE TRANSMITTER OFF
WHILE MAKING ADJUSTMENTS TO THE ANTENNA.

Impedance-matching a load to its source is an important consider-
ation in transmissions’ systems. If the load and source are mis-
matched, part of the power is reflected back along the transmission
line towards the source. This reflection prevents maximum power
transfer, causes erroneous measurements of other parameters, or
causes circuit damage in high-power applications.


---

Antenna Handbook ______________________________ 6-7

The power reflected from the load interferes with the incident (for-
ward) power, creating standing waves of voltages and current along
the line. The ratio of standing-wave maximal to minimal is directly
related to the impedance mismatch of the load. The standing-wave
ratio (SWR) provides the means to determine impedance and mis-
match.

               FIELD EXPEDIENT ANTENNAS

VHF Considerations

SINCGARS VHF radios provide the primary means of communica-
tions means for Marine Corps forces around the world. SINCGARS
radios operate in both single-channel and frequency hopping modes.
It is important for CIS personnel to remember that when using SIN-
CGARS radios in the frequency hopping mode, field expedient VHF
antennas should not be used. CIS personnel should only use the
whip antenna or the OE-254 antenna when operating in the fre-
quency hopping mode.

HF Considerations

Vertical antennas are omnidirectional. They transmit and receive
equally well in all directions. Most manpack portable radios use a
vertical whip antenna. Improvise a by using a metal pipe or rod of
the correct length, held erect by guys. Insulate the lower end of the
antenna from the ground by placing it on a large block of wood or
other insulating material. Support a vertical wire antenna with a tree
or a wooden pole (fig. 6-4 on page 6-8). For short, vertical anten-
nas, use the pole without guys (if properly supported at the base). If
the vertical mast is too short to support the wire upright, modify the
connection at the top of the antenna.


---

6-8 _____________________________________ MCRP 6-22D

              Figure 6-4. Field Substitutes for Support of
                             Vertical Wire Atennas.

End-Fed Half-Wave Antenna

Construct an expedient, end-fed half-wave antenna from available
materials (e.g., field wire, rope, and wooden insulators). This
antenna’s electrical length is measured from the antenna terminal
on the radio set to the far end of the antenna (fig. 6-5).


---

Antenna Handbook ______________________________ 6-9

For best performance, construct the antenna longer than necessary,
then shorten it, as required, until best results are obtained. Connect
the radio set’s ground terminal to a good Earth ground for func-
tional efficiency.

   INSULATORS  WOODEN
               MAST
ANTENNA
WIRE                  GROUND
                         STAKE

                Figure 6-5. End-Fed Half-Wave Antenna.

Center-Fed Doublet Antenna

The center-fed doublet is a half-wave antenna consisting of two
quarter-wavelength sections on each side of the center. See figure
6-6 on page 6-10 for constructing an improvised doublet antenna
for use with FM radios.


---

6-10 ____________________________________ MCRP 6-22D

           INSULATORS

WOODEN     QUARTER-  QUARTER-
     MAST     WAVE      WAVE

                                                                          GROUND STAKE

                Figure 6-6. Center-Fed Doublet Antenna.

Doublet antennas are directional broadside to their length, which
makes the vertical doublet antenna essentially omnidirectional. The
radiation pattern is doughnut shaped. The horizontal doublet
antenna is bidirectional.

Compute the length of a half-wave antenna by using the formula in
chapter 4. Cut the wires as closely as possible to the correct length
because the antenna wires’ lengths are important.

A transmission line conducts electrical energy from one point to
another and transfers the output of a transmitter to an antenna.
Although it is possible to connect an antenna directly to a transmit-
ter, the antenna generally is located some distance away. In a vehic-
ular installation, for example, the antenna is mounted outside, and


---

Antenna Handbook ____________________________ 6-11

the transmitter is inside the vehicle. A transmission line, therefore,
is necessary as a connecting link.

Center-fed half-wave FM antennas can be supported entirely by
pieces of wood. See figure 6-7 (A) for a horizontal antenna of this
type. See figure 6-7 (B) for a vertical antenna. These antennas can
be rotated to any position to obtain the best performance. If the
antenna is erected vertically, the transmission line should be
brought out horizontally from the antenna for a distance equal to at
least one-half of the antenna’s length before it is dropped down to
the radio set.

  INSULATORS

                 QUARTER-
                 WAVE

                 TRANSMISSION
                 LINE

A
   HORIZONTALLY
     POLARIZED

                 B
                   VERTICALLY
                    POLARIZED

Figure 6-7. Center-Fed Half-Wave Antenna.


---

6-12 ____________________________________ MCRP 6-22D

A short, center-fed half-wave antenna is shown in figure 6-8. The
antenna ends are connected to a piece of dry wood (e.g., a bamboo
pole). The bend in the pole holds the antenna wire straight. Another
pole, or bundle of poles, serves as the mast.

                                 1 TURN LOOP

BAMBOO POLES

              QUARTER-
              WAVE

              QUARTER-
              WAVE

WIRE          LASHING
              1 TURN LOOP

                    Figure 6-8. Bent Bamboo Antenna.

Figure 6-9 shows an improvised vertical half-wave antenna. This
technique is used primarily with FM radios. In heavily wooded
areas it is effective for increasing the range of portable radios. The


---

Antenna Handbook ____________________________ 6-13

top guy wire can be connected to a limb or passed over the limb and
connected to the tree trunk or a stake.

  ANTENNA          INSULATOR
   WIRE                       INSULATOR

GROUND
   STAKE

INSULATOR

     ANTENNA WIRE  GROUND
INSULATOR          STAKE

Figure 6-9. Improvised Vertical Half-Wave Antenna.


---

6-14 ____________________________________ MCRP 6-22D

    FIELD EXPEDIENT DIRECTIONAL ANTENNAS

The vertical half-rhombic, the long wire, and the yagi are field
expedient directional antennas.

Vertical Half-Rhombic and Long-Wire Antennas

The vertical half-rhombic antenna (fig. 6-10) and the long-wire
antenna (fig. 6-11) radiate a directional pattern and primarily trans-
mit or receive HF signals. They consist of a single wire, preferably
two or more wavelengths, supported on poles at a height of 3 to 7
meters (10 to 20 feet) above the ground. The antennas also operate
satisfactorily as low as 1 meter (approximately 3 feet) above the
ground. Connect the far end of the wire to a ground through a non-
inductive 500- to 600-ohm resistor. To ensure the transmitter’s out-
put power does not burn out the resistor, use a resistor that is rated
at least one-half the wattage output of the transmitter. Use a reason-
ably good ground (e.g,. a number of ground rods or a counterpoise)
at both antenna ends.

Yagi Antenna

The Yagi antenna (fig. 6-12) is a dipole with an additional wire
behind it (reflector) and an additional wire in front of it (director).

                      RESISTOR

       Figure 6-10. Vertical Half-Rhombic Antenna.


---

Antenna Handbook ____________________________ 6-15

These additional wires increase the power to the front of the
antenna while decreasing the power to the rear.

                   RESISTOR

         Figure 6-11. Long Wire Antenna.

         SPLIT CABLE BOARD                ROPE

         QUARTER-  QUARTER-
            WAVE      WAVE

ANTENNA                                           1/8
MAST                                            WAVE

            10’
                      ONE-HALF WAVE

                        WD1/TT WIRE

         Figure 6-12. Yagi Antenna.


---

6-16 ____________________________________ MCRP 6-22D
Vee Antenna

The vee antenna is another field expedient, directional antenna. It
consists of two wires forming a vee with the open area of the vee
pointing in the desired direction of transmission or reception (see
fig. 6-13). The antenna must be fed by a balanced transmission line.

                                                                 INSULATORS

                                                                 10’
                                                                                               10’

                            10’

                          Figure 6-13. Vee Antenna.

Sloping Vee Antenna

To simplify construction, the legs may slope downward from the
apex of the vee (this is called a sloping vee antenna [see fig. 6-14]).


---

Antenna Handbook ____________________________ 6-17

The angle between the legs varies with the length of the legs in
order to achieve maximum performance.

                                                  RESISTORS
                                                                   INSULATORS

                                                                 RESISTOR
                                                                                 INSULATOR

                    Figure 6-14. Sloping Vee Antenna.


---

6-18 ____________________________________ MCRP 6-22D

Use table 6-1 to determine the angle and length of the legs..

Table 6-1. Leg Length and Angle
          for Vee Antennas.

   Antenna    Optimum Apex
    Length          Angle
(Wavelength)
                 (Degrees)
          1
          2             90
          3             70
          4             58
          6             50
          8             40
         10             35
                        33

When the antenna is used with more than one frequency or one
wavelength, use an apex angle that is midway between the extreme
angles determined by the chart.

To make the antenna radiate in only one direction, add noninductive
terminating resistors from the end of each leg (not at the apex) to
ground. The resistors should be approximately 500 ohms and have a
power rating at least one-half of the transmitter’s output. Without
the resistors, the antenna radiates bidirectionally, both front and
back.


---

                        Chapter 7

Satellite Communications Antennas

The Marine Corps’ primary LOS and SATCOM radio set, the AN/
PSC-5 enhanced manpack UHF terminal, operates at 5 to 25 kHz
and provides data and voice communications. It replaces all man-
packable and vehicular-mounted UHF SATCOM radios. The AN/
PSC-5 provides LOS communications with the AS-3566 and long-
range SATCOM with the AS-3567 and AS-3568 antennas.

Characteristics of the AS-3566 (fig. 7-1) are—

Frequency range (LOS):   30 to 400 MHz
Demand assignment
multiple access (DAMA):  225 to 400 MHz
Non-DAMA:                225 to 400 MHz
Polarization:            Directional
Power capability:        Determined by terminating resistor
Radiation pattern
Azimuthal (bearing):     Directional

Figure 7-1. AS-3566 Low-Gain Antenna.


---

7-2 _____________________________________ MCRP 6-22D

Characteristics of the AS-3567 (fig. 7-2) are—

Frequency range:  225 to 399.995 MHz
Beamwidth:        85°
Orientation:      Directional
                  Elevation (0 to 90°)
Input impedance:  50 ohms
VSWR:             1.5:1
Gain:             6 dB (225 to 318 MHz)
                  5 dB (318 to 399.995 MHz)

Figure 7-2. AS-3567 Medium-Gain Antenna.


---

Antenna Handbook ______________________________ 7-3

Characteristics of the AS-3568 (fig. 7-3) are—

Frequency range:  240 to 400 MHz
Beamwidth:        77°
Orientation:      Directional
                  Elevation ( 0 to 90°)
Imput impedance:  Azimuth: ± 180°
VSWR:             50 ohms
Gain:             1.5:1 maximum
                  8 dB (240 to 318 MHz)
Power             6 dB (318 to 400 MHz)
                  Up to 150 watts continuous

Figure 7-3. AS-3568 High-Gain Antenna.


---

7-4 _____________________________________ MCRP 6-22D

                 SITING SATCOM ANTENNAS

The most important consideration in siting LOS SATCOM equip-
ment is the antenna elevation with respect to the path terrain.
Choose sites that exploit natural elevations.

Considerations

The most important consideration in siting over-the-horizon sys-
tems is the antenna horizon angles (screening angles) at the termi-
nals. As the horizon angle increases, the transmission loss
increases, resulting in a weaker received signal.

The effect of the horizon angle on transmission loss is very signifi-
cant. Except where the consideration of one or more other factors
outweighs the effect of horizon angles, the site with the most nega-
tive angle should be first choice. If no sites with negative angles
exist, the site with the smallest positive angle should be the first
choice.

Determining Horizon Angles

The horizon angle can be determined by using a transit at each site
and sighting along the circuit path. Strictly speaking, the on-site
survey will determine the visual horizon angle. The radio horizon
angle is slightly different from the visual horizon angle; however,
the difference is generally insignificant.

The horizon angle is measured between the tangent at the exact
location of the antenna and a direct LOS to the horizon. The tangent
line is at a right angle (90°) to a plumb line at the antenna site. If the
LOS to the horizon is below the tangent line, the horizon angle is
negative.


---

Antenna Handbook ______________________________ 7-5

Trees, buildings, hills, or the Earth can block a portion of the UHF
signal, causing an obstruction loss. To avoid signal loss due to
obstruction and shielding, clearance is required between the direct
LOS and the terrain. Path profile plots are used to determine if there
is adequate clearance in LOS systems.
Weak or distorted signals may result if the SATCOM set is operated
near steel bridges, water towers, power lines, or power units. The
presence of congested air-traffic conditions in the proximity of
microwave equipment can result in significant signal fading, partic-
ularly when a nondiversity mode is employed.

                                                                    (reverse blank)


---

                         Chapter 8

               Antenna Farms

The antenna farm (also referred to as the radio hill or the antenna
hill) is a component of a command echelon. It is the location of the
bulk of the unit’s antennas and radio and cryptographic equipment.
It is also the portion of the command echelon that produces the
majority of the electromagnetic radiation. Antenna farms can be
located in several different areas: inside the command echelon, out-
side the command echelon but near it, or outside the command ech-
elon but far from it.

                        COMMAND POST

The commander exercises command and control through establish-
ing a command post (CP). CPs provide the headquarters facilities
from which the commander and staff operate. Battalions and larger
units may divide the headquarters into three echelons—tactical,
main, and rear. The CP then becomes the echelon at which the com-
mander is physically located.

Tactical

The tactical echelon (main group) is a mobile unit that contains a
minimal personnel and equipment. Its main focus is tactical control
of current operations. The antenna farm will generally be located
within the CP.


---

8-2 _____________________________________ MCRP 6-22D

Main

The main echelon is where the commander is normally located
together with those elements of the staff required to plan and direct
operations and control forces. The antenna farm will generally be
located outside of and far from the CP.

Rear

The rear echelon, located to the rear of the main echelon, focuses on
administrative and logistics functions. It is normally established by
regiments and larger units. It may be located in or near the rear ech-
elon of the senior headquarters or remain aboard ship. The antenna
farm will generally be located outside of and far from the CP.

      LOCATION SELECTION CONSIDERATIONS

There are doctrinal, tactical, and technical considerations involved
in deciding of how far the antenna farm should be from the CP. The
CIS officer and CIS chief need to list considerations relevant to the
situation before determining the best location for the antenna farm.

Doctrinal Considerations

MCWP 6-2 (under development), MAGTF Command and Control,
FMFM 6 (MCWP 3-1 under development), Ground Combat Opera-
tions, and MCWP 6-22, Communications and Information Systems,
contain Marine Corps doctrinal guidance on command echelon
organization and location.

Some areas to consider when deciding on the antenna farm location
are communications, electronic warfare (EW), tactical situation,
and accessibility.


---

Antenna Handbook ______________________________ 8-3

Communications
• Take a radio along on reconnaissance to ensure that communi-

    cation from the proposed site is possible.
• Choose another site if communication is not possible.

Electronic Warfare
• Enemy capability.
• Projected electronic signature of the command.

Tactical Situation
• Cover and concealment.
• Offense/defense.
• Moving/static.
• Intended length of stay.
• Future operational plans.
• Speed of displacement.

Accessibility
• Terrain.
• Climate.
• Personnel and equipment available.

Tactical Considerations

Once the doctrinal issues have been addressed, locating the antenna
farm must be reviewed in the light of tactical considerations. Since
the antenna farm contains the majority of the unit’s radios, crypto-
graphic equipment, antennas, and a fair portion of the radio opera-
tors, the physical safety of the site is an important aspect of the


---

8-4 _____________________________________ MCRP 6-22D

antenna farm location decision. At the division/force service sup-
port group/wing levels, the antenna farm should be remoted 1,000
meters away from the CP, if possible.

Security. The antenna’s physical security depends on the ability to
protect it. The requirement to provide protection depends on the
considerations listed above. Protection considerations also depend,
in part, on the proximity of the antenna farm to the CP. For an
antenna within the CP, no additional protective measures are
required beyond those employed to protect the CP. Additional con-
siderations for the antenna farms located at remote sites follow.

Far Remote Sites

• Security forces available.
• Natural obstacles.
• Perimeter defense, avenues of approach.
• Barbed wire, automatic weapons, deployment.
• Mines and sensors.
• Supporting coverage.

Near Remote Sites

• Same factors as above apply.
• Take increased EW measures.
• Enforce strict circuit discipline.
• Use messengers.

Cover and Concealment. Whether the antenna farm is located
inside the unit perimeter or at a remote location, using cover and
concealment is imperative. Security assets make it possible to select
a site that has the best available cover and concealment. Cover and
concealment is a trade-off with the ability to communicate with and


---

Antenna Handbook ______________________________ 8-5

from the site. A thoroughly covered and concealed site that prevents
communications is worthless.

Obstacles. As with any other defensive position, use natural or
manmade obstacles to enhance the antenna farm’s security.

Terrain. Studying the terrain in the vicinity of remote antenna farms
is essential to developing an adequate plan for defense. Studying
the terrain is also of paramount importance to ensuring that a unit
can communicate from the site.

Technical Considerations

Siting VHF antennas greatly effects communications reliability. In
an ideal setting, the antenna would be as high as possible above a
flat, clear area. In tactical situations, the antenna location must be a
compromise of propagation consideration, EW considerations, and
cover and concealment.

When it is possible to see the distant station but not communicate
with it, the receiving station is experiencing destructive multipath
interference. This combining of direct and reflected rays out of
phase, results in complete signal cancellation. This interference can
also result in a very weak signal or one that flutters. To improve
communications, either raise or lower the antenna or move the
antenna to several different sites. Usually, one or both of these
actions will result in good communications.

Another cause of weak communications is antenna cross-polariza-
tion. This means that the transmitting and receiving antennas have a
different polarization. For best communications, both antennas
should be vertically or horizontally polarized.


---

8-6 _____________________________________ MCRP 6-22D

Another problem could be misaligned directional antennas. If direc-
tional antennas are not correctly pointed at each other, communica-
tion is degraded. The directional antennas’ electrical characteristics
can change over several field deployments, especially if the antenna
is subjected to harsh use. These electrical characteristic changes can
cause the radiation pattern to change. Then, when the antenna is
physically pointed at the distant station, the main radiation may be
aimed in another direction.

To correct these electrical characteristic changes, have the distant
station transmit. Slowly turn the receiving antenna while listening
to the received signal. When the received signal is strongest, the
antenna is properly aligned for the circuit. Secure the antenna in this
position and have the distant station align its antenna in the same
way. When both antennas are properly adjusted, the maximum radi-
ation from each antenna is directed at the other antenna.

                    SITING VHF ANTENNAS

Antenna sites should be as high as possible and clear of obstruc-
tions such as hills, dense woods, and buildings. If it is necessary to
site the antennas on or around hills, choose a site that allows LOS to
the distant station or stations. If possible, place the antenna on the
military crest of a hill, not on the ridge line. Antennas located on the
ridge line provide an aiming stake for enemy observation and fire
(fig. 8-1).

Place high ground between the antenna and the enemy to block the
enemy’s observation and the antenna’s radiation, reducing the
enemy’s intercept capability (fig. 8-2).


---

Antenna Handbook ______________________________ 8-7

Figure 8-1. Ridge Line Antenna Farm.

DESIRED         ENEMY
COMMUNICATIONS

            Figure 8-2. Antenna Sited on a Military Crest.

In a dense forest, get the antenna tip above the treetops. This height
allows the radio signal to propagate in the clear space above the
trees. If it is impossible to raise the antenna above the trees, a hori-
zontally polarized antenna provides better communications through


---

8-8 _____________________________________ MCRP 6-22D

trees than a vertically polarized antenna. Figure 8-3 shows good,
fair, and poor antenna siting in dense trees.

A clearing in a forest improves propagation if the antenna is placed
so that the clearing is between the antenna and the distant station
(for a directional antenna). Place an omnidirectional antenna in the
center of a clearing, with the antenna as high as possible (fig. 8-4).

A communicator may have little choice in selecting a transmitter or
receiver site location. Often the site is determined by the opera-
tional requirements of a superior command. However, when a
choice is available, determine the HF antenna site by wave-path
geometry.

GOOD

            DISTANT STATION
      FAIR

                                      POOR

Figure 8-3. Antennas Sited in Dense Trees.


---

Antenna Handbook ______________________________ 8-9

      DISTANT STATION

GOOD  FAIR             POOR

       Figure 8-4. Directional Antennas Sited in a Clearing.

Transmitting Antenna Site

Any site that has a horizon whose obstructions subtend vertical
angles of less than 2° from level in any of the directions of trans-
mission can be considered immediately as a satisfactory site from
the standpoint of radiation. As a simple rule, a satisfactory horizon
clearance exists when any obstruction subtends a vertical angle that
does not exceed one-half of the desired beam angle in the vertical
plane in that direction. If the vertical beam angle for a given circuit
is low for the lowest order hop, then the horizon in that direction
can be as much as 5° above level as seen from the antenna location.

In hilly or mountainous country, choosing a site for long-distance
transmission, requiring very low beam angles, can be difficult.
When the only possible site presents horizon obstructions in the pre-
ferred wave path, it may be necessary to design an antenna that uses
a higher order of hop, and to direct the beam at a corresponding
higher angle to obtain the desired 2-to-1 horizon clearance angle.


---

8-10 ____________________________________ MCRP 6-22D

For example, if the computed vertical beam angle for a one-hop cir-
cuit is 6° at an azimuth of 332°, and the horizon in this direction is a
range of mountains with a height of 8° as seen from the antenna
site, the performance of the circuit would be greatly compromised
by the obstruction of the mountains. It might be better to work this
circuit with two hops—a vertical beam of 20° could be used
instead, with adequate horizon clearance for the wave path. If the
circuit required 6° for a two-hop circuit 5,400 kilometers long with
the same obstruction sited, the circuit could be changed to three
hops, which, for the same layer heights, would permit using a beam
at 14°. The latter solution lacks the full 2-to-1 horizon-clearance
angle, but it may be an acceptable compromise and perhaps prefera-
ble to using four hops.

Short-range, sky wave circuits using one-hop high-angle radiation
give a great latitude in the choice of sites. For F layer transmission
to distances of 500 miles and less, the vertical beam or angles are
always greater than 30°. Satisfactory sites for such transmission can
often be located in rather deep valleys without any compromise on
the circuit performance.

Forests on or near the site require some consideration. Because the
theoretical radiation pattern is calculated on perfect reflectivity
from ground, some precautions are necessary to obtain actual per-
formance that substantially agrees with theoretical performance.
Choose a site that provides conditions as nearly perfect as possible
with respect to wave-reflecting surfaces around the antenna. There
should be few or no trees and buildings out to the necessary dis-
tance from the antenna. The point of wave reflection should be flat
and cleared. An excellent choice is a site that borders the sea or a
lake. Water is a wave-reflecting surface.


---

Antenna Handbook ____________________________ 8-11

Receiving Antenna Sites

Choosing a receiving antenna site is similar to choosing a transmit-
ting antenna site. The dominant angles of arrival of the incoming
waves at the site are determined mainly by the characteristics of the
transmitting antenna. Best results are obtained with complementary
transmitting and receiving antennas. If a horizon obstruction exists
at the optimum angle of wave arrival, a compromise, noncomple-
mentary antenna may be necessary. When possible, move the trans-
mitting antenna to align with the receiving antenna.

The receiving site must be as free as possible from electrical noise.
The tolerable amount of manmade noise at a particular receiving
station site depends on the prevailing natural atmospheric noise lev-
els. At a well selected site, reception should always be limited only
by natural atmospheric noise. Any manmade noise at the site should
always be substantially less than the atmospheric noise received
during the low-noise periods.

Aside from broadcast systems, most communications systems re-
quire that antennas be positioned so that their main lobes of radia-
tion are aligned with each other. This requires knowledge of the
great circle bearing to the other antenna and the local magnetic vari-
ation from true north.

The great circle bearing between two locations is calculated by
methods that are beyond the scope of this publication. A way to find
the great circle bearings is to request a frequencies of optimum
transmission chart from the Electromagnetic Compatibility Analy-
sis Center.


---

8-12 ____________________________________ MCRP 6-22D

     ANTENNA FARM INTERNAL ARRANGEMENT

Frequency Band

The higher the frequency, the shorter the wavelength. The shorter
the wavelength, the more nearly LOS. The more nearly LOS, the
more critical is a clear LOS path for the signal.

Antenna Selection and Placement

Selection. The key to antenna selection rests with the answers to
the following three questions:

• To whom will you be transmitting? Where will they be?
• What is the path between you and them?
• What kind of net? Point-to-point or multistation?

Placement. Antenna placement within the antenna farm should
take into account the following three factors:

Cosite Interference. Evaluating interference can be difficult be-
cause of the nature of the systems involved and the complexity of
the signals. The mechanisms are varied. In the simpler cases they
may be direct interference into the radio receiver. In other cases,
they may be spurious products or combinations of products which
arrive at the receiver input and produce a net resultant interference
into the receiver intermediate frequency section. The latter may be
frequency translations resulting from sum and difference products
within the same system. In still other cases, the receiver may see an
identical signal to the regular signal.

Interference produces beats or noise in a radio receiver which have
detrimental effects depending on the frequency, deviation, channel
separation and linearity of the transmission medium, as well as the


---

Antenna Handbook ____________________________ 8-13

nature of the interfering signal. Sometimes the interfering signals
combine with other frequencies in the system, including carrier-
sum and difference frequencies, to produce interference in a third
radio channel. The products may hold up automatic gain control
during critical fading periods, with serious effect on system noise.
Usually, noise in the base band channels is an end product.

Radio system interference may be introduced through antennas,
wave guides, cabling, or by spurious products produced in the radio
equipment itself. Interference introduced into the cabling or in the
equipment can be prevented by good installation practices, includ-
ing proper separation of high- and low-level cabling, proper ground-
ing practices, shielding where necessary, and good equipment
design and assembly. Interference introduced by coupling between
wave guides in the same station is usually produced by radiation
from wave guide and filter flanges which are not properly tightened,
or which are damaged and cannot be mated properly.

Antenna Coupling. Antenna coupling is a frequency-independent
problem that may occur whenever other antennas (whether trans-
mitting or not) or metallic objects are located within one wave of the
transmitting antenna. Antenna coupling may be either beneficial or
detrimental. Yagis, log periodic arrays, and half-square antennas,
for example, derive their gain and directivity from antenna cou-
pling. Unintended antenna coupling, on the other hand, may signifi-
cantly reduce the signal strength in the desired direction and either
degrade or stop communications.

Coupling is based on two principles. One, that current flowing
through a wire creates a magnetic field around it; and, two, that sig-
nals in phase reinforce each other whereas signals out of phase can-
cel each other. Receiving antennas have current flowing in them
(the received signal). Because there is a flowing current that creates
a magnetic field, a receiving antenna will simultaneously receive
and reradiate the same signal. Receiving antennas, in fact, tend to


---

8-14 ____________________________________ MCRP 6-22D

reradiate about one-half of the power they receive. If the receiving
antenna is within one wavelength of a transmitting antenna (it
makes absolutely no difference whether or not the receiving
antenna’s radio is tuned to the same frequency as the transmitting
radio), the receiving antenna will reradiate a portion of the signal
which may be out of phase with the original signal, altering the
transmitting antenna’s radiation pattern.

Direction of Desired Transmission. Separate antennas according
to the direction of desired transmission. For example: If antenna A
is used to communicate to the east, and antenna B is used to com-
municate to the north, then locate antenna A south and east of
antenna B. Do not make the signal from one antenna pass through,
or around, another antenna on the way to its intended receiver.
Accomplish this by the physical location of the antennas, by mask-
ing the antennas, or by placing the antennas at different elevations.

Requirements

Separate antennas based on the frequencies at which they will oper-
ate and the power they will transmit to avoid cosite interference.

For a 10 percent separation—

               Power          Distance (Meters)
                 1 kilowatt           500
              400 watts               315
              150 watts               200
              100 watts               150
               40 watts               100
               20 watts                 70
               10 watts                 50
                 2 watts                22
                 1 watt                 15


---

Antenna Handbook ____________________________ 8-15

Multiply separations by 10 for each halving of frequency separation
(i.e., 10 for 5 percent; 100 for 2.5 percent).

For a 5 percent separation—

      Power (Watts)               Distance (Meters)
             10                           500
              2                           220
              1                           150

For a 2.5 percent separation—     Distance (Meters)
                                         5000
                   Power (Watts)         2200
                          10             1500
                            2
                            1

Separate antennas by a minimum of wavelength at the lowest fre-
quency at which they will operate to alleviate antenna coupling.

Band  Lowest Frequency            Minimum Separation
             (MHz)                         (Feet)
 HF              2                          492
VHF             30                            32.8
UHF           225                              4.37

Separate antennas according to the desired direction of transmission
(i.e., don’t send the propagated wave through other antennas).

Polarization

The preferable polarization with respect to vegetation depends on
the forest and the amount of foliage. Use a polarization with an
inherent advantage when heavy vegetation cannot be avoided. Any


---

8-16 ____________________________________ MCRP 6-22D

advantage based on polarization will be determined by the polariza-
tion of possible sources of interference. In deciduous forests the
sources are evenly divided between vertical and horizontal. In
mature coniferous forests the sources are predominately vertical, so
horizontal polarization has an advantage.

Power and Signal Lines

Distribute power and signal lines to eliminate and avoid crossovers.
If power and signal lines must cross, arrange them so that they cross
at right angles, and separate them by 4 feet of elevation. Do not run
power and signal lines parallel to each other.

         ANTENNA FARM LAYOUT PRINCIPLES

• Segregate HF, VHF, and UHF channels.
• Maintain separation between antennas.
• Separate power and signal lines. Keep them out of the main

    ground phase of antennas.
• Keep transmitters close to the feed point of their antennas (i.e.,

    keep them short).
• Establish good RF and safety grounds for each antenna.
• Use ground radials for each antenna.
• Site LOS antennas on the highest ground.
• Site antennas to avoid the main lobes and significant side lobes

    of directional antennas.
• Remote antenna farms 1 kilometer from the CP if practical.


---

                       Appendix A

                  GLOSSARY

                               Section I
                Acronyms and Abbreviations

AM .............................................................. amplitude modulationn

C .......................................................................................centigrade
CIS..................................communications and information systems
cm.................................................................................... centimeter
COMSEC ................................................. communications security
CP..............................................................................command post

dB ..........................................................................................decibel
dBi ..............................................decibels over an isotropic radiator

e.g. ................................................................................. for example
EW....................................................................... electronic warfare

FM ................................................................. frequency modulation
FMFM ...................................................Fleet Marine Force manual
FMFRP............................Fleet Marine Force reference publication

GHz ................................................................................... gigahertz

HF............................................................................. high frequency

i.e.............................................................................................that is


---

A-2 _____________________________________ MCRP 6-22D

kHz..................................................................................... kilohertz
km ..................................................................................... kilometer
kW........................................................................................kilowatt

LOS................................................................................line of sight
LUF............................................................ lowest usable frequency

MAGTF ..............................................Marine air-ground task force
MCDP ...................................... Marine Corps doctrinal publication
MCRP ......................................Marine Corps reference publication
MCWP ................................. Marine Corps warfighting publication
MHz ................................................................................. megahertz
mi .....................................................................................mile/miles
MUF..................................................... maximum usable frequency

NVIS ............................................ near-vertical incidence sky wave

RF ........................................................................... radio frequency

SATCOM ..................................................satellite communications
SCR.................................................................. single-channel radio
SID ................................................. sudden ionospheric disturbance
SINCGARS.........single-channel ground and airborne radio system
S/N ............................................................................signal-to-noise
SPEED ..........system planning, engineering, and evaluation device
SWR.................................................................. standing wave ratio

TV ..................................................................................... television

UHF .................................................................. ultrahigh frequency


---

Antenna Handbook _____________________________ A-3

VHF.................................................................. very high frequency
VHF-LOS ..................................... very high frequency line of sight
VSWR ..................................................voltage standing-wave ratio
W ............................................................................................... watt


---

A-4 _____________________________________ MCRP 6-22D

                              Section II
                             Definitions

                                    A

alternating current—Current that is continually changing in mag-
nitude and periodically in direction from a zero reference level.
Also called AC.

amplification—The process of increasing the strength (current,
voltage, or power) of a signal.

amplitude—The level of an audio or other signal in voltage or cur-
rent. The magnitude of variation in a changing quantity from its
zero value.

amplitude modulation—Modulation in which the amplitude of the
carrier wave is varied above and below its normal value in accor-
dance with the intelligence of the signal being transmitted. Also
called AM.

angle of incidence—The acute angle (smaller angle) at which a
wave of energy strikes an object or penetrates a layer of the atmo-
sphere or ionosphere.

antenna—A device used to radiate or receive electromagnetic
energy (generally RF).

antenna bandwidth—The frequency range over which a given
antenna will accept signals.

antenna feed—Means by which power is transferred to and from
the antenna and the connecting transmission line.


---

Antenna Handbook _____________________________ A-5

antenna gain—The effectiveness of a directional antenna as com-
pared to a standard nondirection antenna. It is usually expressed as
the ratio in decibels of standard antenna input power to directional
antenna input power that will produce the same field strength in the
desired direction. For a receiving antenna, the ratio of signal power
values produced at the receiver input terminals is used. The more
directional an antenna is, the higher is its gain.

array—Several simple antennas, usually dipoles, used together to
control the direction in which most of the antenna’s power is radi-
ated.

attenuation—Power loss resulting from conductor resistance and
dielectric loss within the insulating material used to separate the
conductors.

azimuth—An angle measured in a horizontal plane from a known
reference point.

                                    B

balanced antenna—An antenna is balanced with respect to ground
when both its arms have the same electrical relationship to ground.

balanced transmission line—A transmission line whose conduc-
tors have voltages of opposite polarity and equal magnitude with
respect to the Earth.

balun—A device for feeding a balanced load with an unbalanced
line, or vice versa.

bandwidth—The width of a band of frequencies used for a particu-
lar purpose.


---

A-6 _____________________________________ MCRP 6-22D

baud—The number of times per second the carrier signal changes
value.

bidirectional—In two directions, usually opposite.

blob—Small areas of the atmosphere where temperatures and pres-
sure differences produce conditions suitable for the refraction of
radio waves.

broadband antenna—An antenna capable of operation over a
wide band of frequencies

                                    C

cable connectors—Fittings for cable ends which permit rapid con-
nection and disconnection with equipment or other cables.

capacitance—A natural property of an electrical circuit which
opposes the rate of change of voltage.

capacitor—A device for storing electrical charge.

center-fed—Transmission line connection at the electrical center of
an antenna radiator.

coaxial cable—A transmission line consisting of two conductors,
one inside the other, and separated by insulating material. The inner
conductor may be a small copper tube or wire; the outer conductor
may be metallic tubing or braid. Radiation loss from this type of
line is very little.

command post—The headquarters of a unit or subunit where the
commander and staff perform their functions.


---

Antenna Handbook _____________________________ A-7

communications circuit—The means by which information is
transferred between two or more places.

conductor—A material (usually metal) that has low resistance to
the flow of electrical current. A wire, cable, or other object capable
of carrying electric current. Good conductors are made of metals
such as silver, copper, and aluminum.

connections—Points at which two or more conductors are brought
into contact.

counterpoise—A conductor or system of conductors used as a sub-
stitute for ground in an antenna system; a wire or group of wires
mounted close to the ground, but insulated from ground, to form a
low-impedance, high-capacitance path to ground.

critical frequency—The highest frequency at which a signal may
be transmitted directly overhead and be reflected back to Earth
from the ionosphere.

cross-polarized—The polarization of a received signal is 90
degrees to the polarization of the receiving antenna.

current—The flow of electrons along any path.

                                    D

decibel—The standard unit used to express transmission gain or
loss and relative power levels. Also called dB.

deflection—The displacement of an electron beam from its line of
sight path.

demodulate—To recover the information originally impressed on
the radio wave.


---

A-8 _____________________________________ MCRP 6-22D

dielectric—A material that does not conduct electricity, such as
rubber or glass, i.e. an insulator.

diffraction—The process by which electromagnetic waves are bent
so that they appear behind an obstruction.

dipole antenna—A center-fed wire antenna whose conductors are
in a straight line.

directional antenna—An antenna designed to transmit and receive
RF energy in a specific direction(s).

direct waves—Waves which propagate in a straight line from the
transmitting to the receiving antennas.

directivity—The property of radiating more energy in some direc-
tions than in others.

director—A conductor placed in front of a driven element to cause
directivity.

ducting—The propagation of VHF/UHF wave by bouncing
between the Earth’s surface and the interface between layers of air
having different dielectric constants.

                                    E

efficiency—The ratio of power output to power input.

electromagnetic field—The field of force that an electrical current
produces around the conductor through which it flows.

electromagnetic waves—A wave propagating as a periodic distur-
bance of the electric and magnetic fields and having a frequency in


---

Antenna Handbook _____________________________ A-9

the electromagnetic spectrum; the means by which energy is trans-
mitted from one place to another.

end-fed—An antenna whose power is applied to one end rather
than at some point between the ends.

                                    F

fading— A periodic decrease in received signal strength.

feedpoint impedance—Impedance that is measured at the input
terminals of an electrical device such as an antenna.

fields—Regions in which each point has a value of a physical quan-
tity (voltage, magnetic force, velocity, mass, etc.).

free space—The absence of ground.

frequency—The rate at which a process repeats itself. In radio
communications, frequency is expressed in cycles per second.

frequency hopping—A method of jumping from frequency to fre-
quency in synchronization with one another in a random order at a
rate of up to 100 times per second. Frequency hopping is the pre-
ferred method of communication with SINCGARS radios.

frequency modulation—The process of varying the frequency of a
carrier wave, usually with an audio frequency, in order to convey
intelligence. Also called FM.

frequency of optimum transmission—85 percent of the maximum
usable frequency (MUF). A practical frequency selection which
allows for MUF variations.


---

A-10 ____________________________________ MCRP 6-22D

                                    G

gain—The increase in signal strength that is produced by an ampli-
firer.

generator—A device that changes mechanical energy into electri-
cal energy.

ground—A very large semiconductive surface (the Earth) or a
smaller highly conductive surface.

ground radials—Wires on or in the earth to improve its conductiv-
ity near the antenna.

ground screen—A wire mesh ground plane.

ground wave—A radio wave that travels along the Earth’s surface
rather than through the upper atmosphere.

                                    H

half-wave dipole antenna—A center-fed antenna whose electrical
length is half the wavelength of the transmitter or received signal.

half-wave vertical dipole antenna—A half-wave dipole con-
structed vertical to the Earth’s surface.

hertz—One cycle per second.

high frequency—frequencies between 3 and 30 MHz.

hop—A single reflection of the wave back to Earth at a point
beyond the horizon.


---

Antenna Handbook ____________________________ A-11

horizontal dipole—A dipole constructed parallel to the Earth’s sur-
face.

horizontal pattern—The horizontal cross-section of an antenna’s
three-dimensional radiation pattern.

horizontal polarization—Transmission of radio waves in such a
way that the electric lines of force are horizontal (parallel to the
Earth’s surface).

                                     I

impedance—The total opposition offered by a circuit or compo-
nent to the flow of alternating current.

impedance match—The condition where the load impedance
equals the characteristic impedance of a transmission line.

inductance—The natural property of an electrical circuit which
opposes the rate of change or current, i.e., electrical “intertia.”

in phase—Two or more signals of the same frequency passing
through their maximum and minimum values of like polarity at the
same instant.

insulator—A device or material that has a high electrical resis-
tance; a nonconductor of electricity.

interference—A degradation of a received signal caused by
another transmitter, a noise source, or the desired signal propaga-
tion over two or more different routes.

inverted L antenna—A half-wave dipole fed by a one-quarter
wavelength long vertical section.


---

A-12 ____________________________________ MCRP 6-22D

inverted vee antenna—A half-wave dipole erected in the form of
an upside-down vee, with the feed point at the apex. It is essentially
omnidirectional, and is sometimes called a “dropping doublet.”

ionization—The process where radiation and particles from the
Sun make some of the Earth’s atmosphere partially conductive.

ionosphere—A partially conducting region of the Earth’s atmo-
sphere between 50 kms and 400 kms high.

                                    L

lambda—Greek lower case letter (λ) used to represent a wave-
length with reference to electrical dimensions in antenna work.

linearly polarized antennas—Antennas that produce only one
polarization.

line of sight—The transmission path of a wave that travels directly
from the transmitting antenna to the receiving antenna. Also called
LOS.

load—A device that consumes electrical power.

loading—Providing or connecting an electrical device capable of
accepting power to match the impedance of an antenna to a trans-
mitter so that maximum power is radiated from a generating device,
such as a transmitter.

lobe—A bulge on an antenna radiation pattern which indicates the
direction in which radiated power is concentrated.

long-wire antenna—An end-fed single wire antenna usually one
wavelength or longer.


---

Antenna Handbook ____________________________ A-13

lowest usable frequency—The lowest frequency that will not be
absorbed by the ionosphere or smothered by atmospheric noise.
Also called LUF.

                                    M

maximum usable frequency—The highest frequency for a given
elevation angle that will reflect from an ionospheric layer. Also
called MUF.

megahertz—One million cycles per second. Also called MHz.

modulate—To change the output of a transmitter in amplitude
phase, or frequency in accordance with the information to be trans-
mitted.

monopole antenna—An antenna with a single radiating element; a
whip antenna.

                                    N

noise—Random pulses of electromagnetic energy generated by
lightning or electrical equipment.

                                    O

offset angle—The angle at which a long wire antenna must be
aimed on either side of the direction to the base station.

omnidirectional antenna—An antenna whose radiation pattern
shows equal radiation in all horizontal directions.

oscillation—A periodic, repetitive motion or set of values (voltage,
current, velocity).


---

A-14 ____________________________________ MCRP 6-22D

out of phase—Two alternating quantities not passing through cor-
responding values at the same time (e.g., if the current in a circuit
reaches its maximum value before or after the applied voltage does,
the current is out of phase with the voltage).

                                    P

path loss—The ratio of received power to transmitted power.

polarization—The direction of the electric field of a radiated wave
relative to the surface of the Earth (vertical, horizontal, linear, and
circular).

polarization fading—Fading due to polarization rotation of a
received signal. The received signal decreases when the incoming
wave does not have the same polarization as the receiving antenna.

power gain—The directive gain of an antenna multiplied by its
efficiency

propagation—A phenomenon by which any wave moves from one
point to another; the travel of electromagnetic waves through space
of along a transmission line.

propagation path—The path or route over which power flows
from the transmitter to the receiver.

                                    Q

quarter-wave antenna—An antenna with an electrical length that
is equal to one-quarter wavelength of the signal being transmitter or
received.


---

Antenna Handbook ____________________________ A-15

                                    R

radiate—To transmit RF energy.

radiation—Energy that moves through space as electromagnetic
waves.

radiation patterns—A chart of relative radiation intensity (or
power) versus direction.

radio frequency—Any frequency of electrical energy capable of
propagation into space (usually above 20 kHz). Also called RF.

radio horizon—The greatest distance on the Earth at which a trans-
mitted wave can be received by the direct path from a transmitter
located on the Earth.

radio waves—Electromagnetic waves at a frequency lower than
3,000 GHz and propagated through space without and artificial
guide.

receiver—Amplifying and selecting equipment that receives radio
frequencies and delivers a duplicate of the information impressed
on the transmitter.

reception—The process of recovering transmitted information; the
process of converting electromagnetic fields to current in wires.

reciprocity—The various properties of an anntenna apply equally
whether the antenna is transmitting or receiving.

reflected waves—Waves that change their direction of propagation
after striking a surface that is either a conductor or an insulator.


---

A-16 ____________________________________ MCRP 6-22D

reflection—The turning back of a radio wave from an object or the
surface of the Earth.

reflector type antenna—An antenna placed in front of a conduct-
ing surface (reflector) for the purpose of increasing radiation in one
direction, at the expense of radiation in other directions.

refraction—The bending, or changing direction, of a radio wave
passing into or through layers of the atmosphere or the ionosphere
that have different density (dielectric constant).

refractive index—A measure of the degree by which the speed of
an electromagnetic wave is slowed as it propagates through a given
material.

resistance—The property of a material or substance to oppose the
passage of current through it, thus causing electrical energy to be
converted into heat energy.

resonance—The state or frequency of vibration, electrical or
mechanical, in which forces that impede the motion are minimum.

resonant length—The proper length of an antenna to render it reso-
nant

rhombic antenna—An antenna made of four wires of equal length
connected together in the shape of a rhombus.

                                    S

scattering—The spreading or breaking up of electromagnetic
waves when they encounter objects of different electrical properties
than those in which the wave is traveling.


---

Antenna Handbook ____________________________ A-17

shortened dipole—A dipole antenna made to resonate at a lower
frequency by use of a coil.

signal—A radio wave that contains the transmitted message.

signal loss—The amount of signal power lost between the transmit-
ter and receiver.

signal-to-noise ratio—The power intensity of the signal compared
to that of the noise.

skip distance—The distances on the Earth’s surface between the
points where a radio wave sky wave leaves the antenna and is suc-
cessfully reflected and/or refracted back to Earth from the iono-
sphere.

skip zone—The space or region within the transmission range
where signals from a transmitter are not received, i.e., between the
ground wave and the point where the refracted wave returns.

sky wave—A radio wave that is reflected from the ionosphere.

sloping long-wire antenna—A wire antenna of length greater than
one wave-length and supported in an inclined orientation with
respect to the ground.

standing-wave ratio—The ratio of the maximum to minimum
amplitudes of voltage, or current, along a transmission line.

standing waves—Waves that appear not to be moving as the result
of power traveling in both directions along a transmission line.

stratosphere—The second layer of the Earth’s atmosphere, extend-
ing from 10 to 50 km.


---

A-18 ____________________________________ MCRP 6-22D

sunspots—Activity on the Sun’s surface which is seen as a series of
blemishes that vary in size, number, and location.

                                    T

take-off angle—The angle measured from the Earth’s surface or
horizontal up to the direction of propagation towards the iono-
sphere.

transistor—A minute electronic device that permits a small current
to control the flow of a larger current.

transmission line—A conductor that transfers radio frequency RF
energy from the transmitter to the antenna or from the antenna to
the receiver.

transmitter—A piece of equipment that generates and amplifies a
radio frequency, adds intelligence to this signal, and then sends it
out into the air as a radio frequency wave.

troposphere—The region of the Earth’s atmosphere from the sur-
face to a height of about 10 km.

tuning—The process of adjusting a radio circuit so that it resonates
at the desired frequency.

twin-lead transmission line—A balanced transmission line gener-
ally used with balanced antennas.

two element array—An antenna composed of two element anten-
nas.


---

Antenna Handbook ____________________________ A-19

                                    U

ultrahigh frequency—Frequencies between 300 and 3,000 MHz.

unbalanced transmission line—A transmission line one of whose
conductors is grounded.

unidirectional—In one direction only.

                                    V

vee antenna—Two long-wire antennas connected to form a vee.

velocity—The speed of a radio wave through the dielectric medium
it is in.

vertical dipole—A balanced or dipole antenna oriented vertically.

vertical polarization—Transmission of radio waves in such a way
that the electric lines of force are vertical (perpendicular to the
Earth’s surface).

vertical quarter-wave antenna—A monopole (whip) antenna that
is oriented vertically.

very high frequency— Frequencies between 30 and 300 MHz;
transmissions that follow the line of sight path.

voltage—Electrical pressure, expressed in volts, which is the result
of squeezing electrons together.

voltage standing-wave ratio—The ratio of the amplitude of the
electric field or voltage at a voltage maximum to that at an adjacent
voltage minimum. Also called VSWR.


---

A-20 ____________________________________ MCRP 6-22D

                                    W

wavelength—The distance a wave travels during one complete
cycle. It is equal to the velocity divided by the frequency.
wave propagation—The transmission of RF energy through space.
whip antenna—A vertical monopole.
wire—Conductors in one of many different sizes with different
kinds of insulation.

                                    Y

yagi antenna—A combination of dipoles to increase the gain.


---

              Appendix B

          References and
       Related Publications

Marine Corps

Warfigthing Publication (MCWP)

6-22   Communications and Information Systems

Reference Publications (MCRPs)

6-22A  TALK-II SINCGARS: Mutiservice Communica-
6-22C     tions Procedures for the Single-Channel Ground
          and Airborne Radio System

       Radio Operator’s Handbook (under development)

Technical Manual (TM)

2000-15/2B Principal Technical Characteristics of U.S. Marine
                     Corps Communications-Electronic Equipment

Army

Field Manuals (FMs)

11-32  Combat Net Radio Operations
11-43  Signal Leader’s Guide
11-65  High Frequency Radio Communications
24-2   Spectrum Management
24-18  Tactical Single-Channel Radio Communications

24-19     Techniques
       Radio Operator’s Handbook

                                                        (reverse blank)


--- 