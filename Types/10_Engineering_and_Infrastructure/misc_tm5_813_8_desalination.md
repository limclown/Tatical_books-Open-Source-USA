# misc_tm5_813_8_desalination  TM 5-813-8

               TECHNICAL MANUAL

               WATER DESALINATION

HEADQUARTERS,  DEPARTMENT          OF  THE ARMY
                                                 SEPTEMBER 1986


---

                                                                                                                                       TM 5-813-8

                                 REPRODUCTION AUTHORIZATION/RESTRICTIONS

This manual has been prepared by or for the Government and, except to the extent indicated
below, is public property and not subject to copyright.

Copyrighted material included in the manual has been used with the knowledge and permission
of the proprietors and is acknowledged as such at point of use. Anyone wishing to make further
use of any copyrighted material, by itself and apart from this text, should seek necessary
permission directly from the proprietors.

Reprints or republications of this manual should include a credit substantially as follows:
"Department of the Army, USA, Technical Manual TM 5-813-8, Water Desalination.

If the reprint or republication includes copyrighted material, the credit should also state:
"Anyone wishing to make further use of copyrighted material, by itself and apart from this text,
should seek necessary permission directly from the proprietors."


---

                                                                                                                               TM 5-813-8

TECHNICAL MANUAL                                              HEADQUARTERS
No. 5--813-8                                       DEPARTMENT OF THE ARMY
                                      WASHINGTON, D.C. 15 September 1986

                  WATER DESALINATION

CHAPTER 1.                                                                                        Paragraph             Page
CHAPTER 2.  GENERAL
CHAPTER 3.  Purpose ............................................................................................ 1-1     1-1
CHAPTER 4.  General design considerations .......................................................... 1-2                 1-1
            Special design considerations ........................................................... 1-3                1-1
CHAPTER 5.  Economic considerations ................................................................. 1-4                1-1
CHAPTER 6   Appendices ...................................................................................... 1-5        1-1
            SITE SELECTION
CHAPTER 7.  Site technical requirements .............................................................. 2-1               2-1
CHAPTER 8.  Water storage and system modularization ........................................ 2-2                         2-1
            WATER SOURCE SELECTION
            General............................................................................................. 3-1     3-1
            Quality .............................................................................................. 3-2   3-1
            Selection versus rejection of potential raw water sources .................. 3-3                             3-1
            PROCESS SELECTION
            General process selection................................................................. 4-1               4-1
            Process limitations............................................................................ 4-2          4-2
            Distillation/condensation energy........................................................ 4-3                 4-3
            Membrane energy............................................................................. 4-4             4-5
            Waste disposal ................................................................................. 4-5         4-5
            Preliminary process selection............................................................ 4-6                4-5
            Process selection.............................................................................. 4-7          4-5
            PRETREATMENT CONSIDERATIONS
            General............................................................................................. 5-1     5-1
            Chemical treatment........................................................................... 5-2            5-1
            Degasification and deaeration........................................................... 5-3                 5-5
            Filtration with granular media ............................................................ 5-4              5-5
            Secondary filtration .......................................................................... 5-5          5-5
            Disinfection....................................................................................... 5-6      5-6
            DISTILLATION/CONDENSATION TECHNIQUES
            General............................................................................................. 6-1     6-1
            High-temperature distillation ............................................................. 6-2              6-1
            Low-temperature distillation .............................................................. 6-3              6-1
            Mechanical distillation....................................................................... 6-4           6-1
            Thermal discharge ............................................................................ 6-5           6-7
            Design analysis................................................................................. 6-6         6-7
            Materials of construction ................................................................... 6-7            6-7
            Distillation/condensation system design ............................................ 6-8                     6-7
            MEMBRANE TECHNIQUES
            Electrodialysis................................................................................... 7-1       7-1
            Electrodialysis-reversal design.......................................................... 7-2                7-1
            Reverse osmosis .............................................................................. 7-3           7-3
            Reverse osmosis membrane staging configurations.......................... 7-4                                7-7
            Reverse osmosis system design ....................................................... 7-5                    7-11
            Materials of construction ................................................................... 7-6            7-13
            ION EXCHANGE
            General............................................................................................. 8-1     8-1
            Pretreatment..................................................................................... 8-2        8-1
            Desalination...................................................................................... 8-3       8-2
            Demineralization............................................................................... 8-4          8-5

                  i


---

                                                                                                                                   TM 5-813-8

CHAPTER 9.    POST-TREATMENT                                                                                                  9-1
              General............................................................................................. 9-1        9-1
CHAPTER 10.   Remineralization and aeration .......................................................... 9-2                    9-1
              Post-treatment of distilled water ....................................................... 9-3                   9-1
APPENDIX A.   Post-treatment of reverse osmosis product water ............................. 9-4                               9-3
APPENDIX B.   Post-treatment of electrodialysis-reversal product water.................... 9-5
APPENDIX C.   WASTE DISPOSAL                                                                                                 10-1
BIBLIOGRAPHY  General............................................................................................. 10-1      10-2
              Pretreatment wastes ........................................................................ 10-2              10-3
              Distillation/condensation system wastes ........................................... 10-3                       10-5
              Membrame system wastes ............................................................... 10-4                    10-6
              Ion-exchange system wastes ........................................................... 10-5                    10-6
              Ultimate disposal ............................................................................. 10-6            A-1
              SAMPLE PROBLEMS ......................................................................                          B-1
              WATER TESTING REQUIRED FOR DESALINATION TREATMENT                                                               C-1
              REFERENCES .................................................................................               Biblio-1
              .........................................................................................................

                                                                   ii


---

                                                                                              TM 5-813-8

FIGURE    2-1                                     LIST OF FIGURES
          2-2
          4-1  Typical Desalination Flowsheet
          5-1  Typical Reverse Osmosis Desalination System
          5-2  Energy Consumption
          5-3  Pretreatment Techniques
          6-1  Approximate Concentration Factor Limits for Calcium Sulfate in Sea Water
          6-2  Disinfection Alternatives
          6-3  Three Methods of Vaporization
          6-4  Multiple-Effect Vertical-Tube Evaporation Process
          6-5  Multistage Flash Distillation Facility
          7-1  Waste Heat Recovery Evaporation Process
          7-2  Vapor-Compression Vertical-Tube Distillation System
          7-3  Principles of Electrodialysis Desalination
          7-4  Reverse Osmosis Principles
          7-5  Reverse Osmosis Desalination System
          7-6  Flow-Work Exchanger Principles
          7-7  Construction of a Tubular Reverse Osmosis Membrane
          7-8  Internal Construction of a Spiral-Wound Membrane
          7-9  Internal Construction of a Hollow Fine-Fiber Reverse Osmosis Membrane Module
          8-1  Reverse Osmosis Product Staging
          8-2  Reverse Osmosis Membrane Reject Staging
          8-3  Principles of Ion-Exchange Processes
          8-4  RDI Process
          8-5  Three-Unit Variation Desal Process
          9-1  Two-Unit Variation Desal Process
        10-1   Demineralization Two-Bed Flowsheet
        10-2   Break-Point Chlorination Curve
        10-3   Waste Disposal Overview
        10-4   Pretreatment Sludge Disposal
         A-1   Deep-Well Disposal Unit
         A-2   Brine Waste Disposal
         A-3   Sample Use of Table 4-1
         A-4   Sample Use of Table 4-2
         A-5   Water Analysis (Sample Problem A-1a)
         A-6   Sample Use of Table 4-3
         A-7   Water Analysis (Sample Problem A-1b)
         A-8   Water Analysis (Sample Problem A-1c)
         A-9   Low-Pressure Reverse Osmosis System
        A-10   Sample Use of Table 4-1
        A-11   Water Analysis (Sample Problem A-2)
        A-12   Sample Use of Table 4-2
        A-13   Sample Use of Table 4-3
        A-14   Plan View of Vapor Compression System
        A-15   Water Analysis (Sample Problem A-4)
               Amberlite IR-120 Plus Leakage Data Regeneration-5 lbs. H2S04 (66° Be)/cu. ft.
        A-16   Amberlite IR-120 Plus Iso-Capacity Data Regeneration-5 lbs. H2S04
        A-17
                    (66° Be)/cu. ft.
        A-18   Amberlite IR-120 Plus Capacity Correction for Alkalinity
               Amberlite IR-120 Plus Leakage Data Regeneration-3 lbs. H2S04
        A-19
        A-20        (66° Be)/cu. ft.
        A-21   Amberlite IR-120 Plus Iso-Capacity Data Regeneration-3 lbs. H2S04

                    (66° Be)/cu. ft.
               Amberlite IR-120 Plus Capacity Correction for Alkalinity
               Cation Exchangers Plan
               Degasifier and Clearwell Plan

                                                              iii


---

                                                                                                    TM 5-813-8

FIGURE A-22          Three Projections of the Water Blends That Satisfy TB MED 576 Requirements
               A-23  Plan View of a Two-Pass Reverse Osmosis System

Table  4-1                                               LIST OF TABLES
                     Preliminary Desalination Process Selection
       4-2           Selecting Desalination Processes after Water Quality Data are Obtained
                     Final Selection of a Desalination Technique from Treatability Data
       4-3           The Maximum Allowable Contaminants in the Feed Water Used

       5-1                by Various Desalination Processes
                     Water Constituents at Treatment Stages with 5 Pounds/Cubic Foot Acid
       A-1
                          Regeneration
       A-2           Water Constituents at Treatment Stages with 3 Pounds/Cubic Foot Sulfuric Acid

       A-3                Regeneration
                     Cost Projections for Possible Optimum Blends

                                                                    iv


---

                                                                   TM 5-813-8

                                     CHAPTER 1
                                      GENERAL

1-1. Purpose. This manual describes the guidelines                 1-4. Economic considerations. The selection of
to be followed in selecting a process capable of                   one particular type of design for a water desalination
producing potable water supplies from brackish and sea             system/subsystem, when two or more types of design
water sources. Potable water is defined in TB MED 576.             are known to be feasible, must be based on the results
Army potable water quality requirements can be found in            of an economic study, in accordance with the
TB MED 576. Information on required pre- and post-                 requirements of DOD 4270.1-M and PL 95-619, 9 Nov
treatment design, water distribution, and storage can be           78. The results of these economic studies are to be
found in the TM 5-813 series.                                      included in the design/analysis documentation for the
                                                                   project. All such studies are to be conducted in
1-2. General design considerations.  All                           accordance with HQDA's economic-studies criteria for
                                                                   Military Construction Program (MCP) designs.
desalination facilities will be designed as simply as              Clarification of HQDA criteria for a particular application
                                                                   or supplementary criteria and guidelines that may be
possible and will produce a final product water in                 required for special cases may be obtained by request
                                                                   through normal channels to HQDA (DAENECE-G),
keeping with operational needs. Desalination process               Wash. DC 20314-1000.

selection will be site-specific and will include evaluations       1-5. Appendices. Appendix A contains sample
                                                                   problems illustrating use of information presented in this
of product quality and quantity, raw feed water sources,           document. Various tests and analyses required or used
                                                                   in desalination treatment of water are listed in Appendix
and available energy sources. Potable water will                   B. Appendix C contains a list of references used in this
                                                                   document.
contain less than 500 milligrams per liter of total

dissolved solids (TDS). (One milligram per liter is equal

to one part per million.) Technological processes not

covered in this TM that are proposed for selection must

be approved by DAENECE-G.

1-3. Special design considerations. When
facilities require improved water quality, such as boiler
feed water or medical facility waters, additional water
treatment systems will be installed.

                                                              1-1


---

                                                                 TM 5-813-8

    CHAPTER 2
SITE SELECTION

2-1. Site technical requirements. Site technical                      a. Equipment downtime. In all distillation/
requirements are specific to each particular process.            condensation and many membrane desalination plants,
Generalized recommendations can be made regarding                storage will be determined by equipment downtime
location, space, and access requirements. A typical              when equipment downtime is more than 1 day. To
desalination system flowsheet is shown in figure 2-1. A          determine the necessary storage, establish the longest
typical desalination system layout, using reverse                period of time that could be required for planned or
osmosis as a sample process, is shown in figure 2-2.             unplanned maintenance. Calculate the storage by
                                                                 multiplying this time period by the water demand rate.
     a. Location. Desalination facilities will be located
as close to the raw water source as possible in order to              b. Peak daily demands. When maximum
avoid excessive pipeline or pumping costs and to                 equipment downtime is less than 1 day, the peak daily
minimize operation and maintenance costs for pumping             demands may set a larger storage demand. When
raw water (high saline content). The placement of                these peak demands set the storage requirements, refer
desalination facilities within the perimeter of a military       to water storage in the TM 5-813 series.
reservation will provide facility security. Topography
should be considered in the siting of a desalination                  c. Fire water storage. On a facility served by a
facility, and gravity flow should be used where possible.        desalination system, fire water may be saline water or
                                                                 potable water depending on economic analysis. Dual
     b. Space requirements. The space required for               water distribution system will be required if saline water
desalination facilities is determined by the process.            is used. Hence, part of the fire protection water can be
Membrane desalination equipment needs less space                 either saline or potable water due to piping and pumping
than distillation/condensation desalination equipment.           cost. Economic evaluation of various design
In general, space requirements are less for the                  alternatives is usually needed to assure the optimal
desalination equipment than for a conventional surface           design to be adopted.
water treatment plant of the same capacity. An
exception is solar desalination systems. These systems                d. System redundancy and modularization. One
employ solar collectors that require an area several             complete and functional desalination module in excess
times greater than other types of desalination equipment         of that required to supply the design flow will be
in order to achieve equal capacity.                              provided as redundant capacity, and all desalination
                                                                 systems will have a minimum of three independently
     c. Access. Access to systems must be provided to            functioning desalination modules where practicable.
permit routine maintenance, sludge and brine removal,
and delivery of desalination equipment and supplies.
The access requirements for desalination facilities are
similar to those for conventional water treatment
facilities.
2-2. Water storage and system modularization.

                                                            2-1


---

                                                                                                                                                         TM 5-813-8

Figure 2-1. Typical desalination flowsheet.
                          2-2


---

                                                                                                       TM 5-813-8

Figure 2-2. Typical reverse osmosis desalination system.
                                    2-3


---

                                                                                              TM 5-813-8

                                            CHAPTER 3
                                WATER SOURCE SELECTION

3-1. General. The selection of a water supply will be                         (3) Turbidity and silt density index. These two
based on available quantity, quality, and cost of
development. Investigate usable fresh surface water                characteristics provide two different measures of the
and groundwater thoroughly, prior to consideration of
sources requiring desalination. When fresh water                   amount of fine particulate matter in the water. Turbidity
sources do not exist, consider saline water sources. The
most commonly used parameter to differentiate between              is measured in nephelometric turbidity units (a measure
saline water qualities is total dissolved solids (TDS).
The total dissolved solids is defined as the sum of the            of the amount of light scattered by a known water
dissolved organic materials and the inorganic salts.
Fresh waters contain less than 1,000 milligrams per liter          sample thickness). Silt density index is a measure of
of total dissolved solids. Brackish water contain 1,000-
20,000 milligrams per liter of total dissolved solids. Sea         the amount of 0.45-micron filter plugging caused by
water usually contains at least 20,000 milligrams per
liter of total dissolved solids. Quantities of potable water       passing a sample of water through the filter for 15
needed will be determined by an analysis of the site in
accordance with TM 5-813-1. The quantity of saline                 minutes. Turbidity must be determined for all
feed water necessary to produce the required quantity of
product water is addressed in Chapter 4.                           desalination processes. Also, the silt density index must

                                                                   be determined for water being considered for reverse

                                                                   osmosis treatment.

                                                                   b. Chemical constituents.  The chemical

                                                                   constituents of the raw water must be determined to

                                                                   provide information for treatment selection. Appendix B

                                                                   shows the water testing analyses required for

                                                                   desalination treatment.

                                                                   c. Bacteriological quality. The bacteriological

                                                                   testing of the raw water must include a type of a

                                                                   coliform indicator organism count. Procedures for filter

3-2. Quality. The quality will be determined by the                membrane, most probable number fermentation tube,

planned use. Physical, chemical, and bacteriological               and standard plate count, coliform organism

testing of source waters are required to determine the             bacteriological testing techniques can be found in

level of treatment to supply the necessary water quality.          Standard Methods for the Examination of Water and

When the quantity withdrawn exceeds the recharge rate,             Wastewater and TB Med 576. Manufacturers'

quality inherently decreases; therefore, this must be              recommendations as to the media and procedures used

considered during design.                                          to identify microbiological activity detrimental to the

a. Physical characteristics.    The physical                       operation of a particular desalination system shall be

characteristics of the raw water source that must be               followed.

evaluated are total suspended solids (TSS) and                     3-3. Selection versus rejection of potential raw

temperature. Turbidity and silt density index (SDI).               water sources. After the completion of physical,

(1) Total suspended solids. The total                              chemical, and bacteriological testing, a final water

suspended solids level of raw water sources must be                source may be selected. Extreme care must be taken in

evaluated to determine the level of pretreatment                   the selection of a source where the usage rate is greater

processes required. Raw water having low total                     than the recharge rate. In most cases, selection will

suspended solids levels generally requires less                    involve choosing the brackish water with the lowest level

pretreatment. The source with the lowest total                     of total dissolved solids. When brackish water is not

suspended solids is preferred.                                     available, use sea water or water as saline as sea water

(2) Temperature. The temperature of the raw                        as the feed water source. When the coliform indicator

water source must be matched to the specific                       organism count of a water is greater than 10,000 most

desalination process. In extreme cases, the water                  probable number (MPN), then the water source should

temperature may control the desalination process                   be rejected for sanitary reasons and a more saline water

selection. A climatological survey must be made prior              chosen (per Standard Methods for the Examination of

to finalization of process selection to determine the              Water and Wastewater and TB MED 576). If other

seasonal maximum and minimum water temperatures of                 water is available, a water containing more than 1,000

the proposed water sources.                                        nephelometric turbidity units should be rejected on the

                                                                   basis of the high cost and difficulty of

                                                              3-1


---

clarification, even if the alternative water is more saline.                                                                   TM 5-813-8
When the total delivery pumping pressure of a less
saline water is greater than the operating pressure of a           desalination of the less saline source. The final
reverse osmosis system, then the desalination of the               selection of a raw water source will be based on
more saline water by reverse osmosis may be more                   economic studies. In some cases, the decision cannot
economical than the combined cost of delivery and                  be made until all systems are fully designed and life
                                                                   cycle costed.

                                                              3-2


---

                                                                                                               TM 5-813-8

        CHAPTER 4
PROCESS SELECTION

4-1. General process selection. In selecting a                                     100%
potable water production system, it is important to               % recovery of product water
estimate costs of various options. The conventional unit
of comparison is cost in dollars per 1,000 gallons of                 x water demand = saline feed water flow
product water. Water quality and energy sources will be
estimated from simple site reconnaissance. For                    In some cases, the limited quantity of an available
example, a sea coast site where the water source                  saline water may require a decision to adopt a more
temperature exceeds 95 degrees Fahrenheit indicates a             expensive desalination process with a higher water
high-salinity high-temperature combination favoring               recovery rate. However, it may require choosing a
distillation/condensation processes. Reverse osmosis              different and more saline feed water with a greater
requires a feed water temperature below 95 degrees                availability.
Fahrenheit. If local well testing indicates salinity
between 500 and 3,000 milligrams per liter and                         c. Blending of waters. Blending a high
electricity is inexpensive, electrodialysis reversal or           concentration stream with a low concentration stream
highflux reverse osmosis is indicated.                            wastes the osmotic pressure energy between the two
                                                                  streams. Therefore, it is best to match the design of the
     a. Desalination requirements. The design of a                desalination system to the product quality desired.
desalination system requires a clear understanding of             When a desalination process cannot be economically
the following: the quantity of product water desired; the         matched to the desired product quality, then a process
quality of the desired product; and the quality of the feed       that yields water with a very low dissolved material
water source. This manual addresses the production of             content must be used. To conserve capital and
potable water containing less than 500 milligrams per             equipment costs and meet the desired water demand,
liter of total dissolved solids. Laundries, boilers, mess         the high purity product water can be blended with the
halls, and hospitals may require water purer than 500             pretreated saline feed water to produce the required
milligrams per liter of total dissolved solids. Potable           product quantity and quality. The following equation can
water from the desalination system may be further                 be used to calculate the concentration of a blended
treated to meet these requirements in accordance with             water stream:
AR 420-46.
                                                                  ( ) i =n
     b. Saline feed water quantity. The production of                Σ concentration i x flow i /total flow =
potable water from saline water usually requires a                i=1
significantly larger quantity of saline feed water than the                                       blended concentration
quantity of potable water produced. When desalination
is necessary to produce potable water, the process splits         When only two streams are blended, the equation can
the feed water into two streams. One stream is the
product water; the other stream is the brine that contains        be rearranged to show the flow of concentrated water
most of the salts originally in the feed water. In waters
that need very little desalination, high-rate reverse             that when blended with a dilute flow will result in the
osmosis may only reject 5 percent of the feed stream as
brine. In reverse osmosis of sea water, more than 70              desired product concentration. This rearranged
percent of the intake water may be rejected as brine.
Multiply the required product quantity by the reciprocal          equation is as follows:
of the product water recovery fraction to find the
quantity of saline water that must be processed to yield                          (P - H)(D) =F
the desired quantity of product water. In equation, form,
it can be expressed as follows:                                                            C-P

                                                                  Where:

                                                                       P = Desired product water

                                                                          concentration

                                                                       H = High purity water concentration

                                                                       D = Flow of the high purity water

                                                                       C = Concentration in the impure

                                                                          concentrated stream

                                                                       F = Flow rate of the concentrated

                                                                          stream

                                                                  Reblending for remineralization is discussed in Chapter

                                                                  9. The same blend equations will apply to blending

                                                             4-1


---

                                                                  TM 5-813-8

for remineralization, which is a more common                      extremely complex. When the molybdenum reactive
procedure. See Appendix A for sample problems.                    silica concentration exceeds 30 milligrams per liter as
4-2. Process limitations. The various desalination                SiO2 or the pH exceeds 8.3 in the brine stream, an
processes presently available have limitations that must          environmental chemist or engineer should be consulted.
be considered prior to selecting a desalination process           Reverse osmosis is also limited to the treatment of
for a particular site. These limitations apply only to the        waters with less than 1 milligram per liter of oil and
desalination processes themselves; pretreatment can be            grease.
and is often used to bring a saline feed water within
limits so that a desalination process can be used. The                        (1) Cellulose acetate membranes. Cellulose
raw feed water chemistry for all desalination systems             acetate membranes are usually limited to pH levels
must be evaluated thoroughly for constituents that may            between 4.0 and 7.5. Cellulose acetate membranes
precipitate in the desalination system.                           require some form of continuous disinfection with the
                                                                  feed water to prevent microbial degradation of the
     a. High-temperature distillation. High-temperature           membranes and can tolerate up to 1 milligram per liter
distillation is limited by the saturation of alkaline earth       of free chlorine. Therefore, cellulose acetate
metal salts, such as CaSO4, BaSO4, SrSO4, CaCO3,                  membranes are usually disinfected by maintaining 0.2 to
BaCO3, and SrCO3. Carbonate salt scaling can be                   0.9 milligrams per liter of free chlorine in the feed water.
controlled by acid addition. The recovery of water from           Cellulose acetate membranes cannot be used on waters
a hightemperature distillation plant is usually limited by        where the temperature exceeds 88 degrees Fahrenheit.
calcium sulfate solubility. When the concentration of             Cellulose acetate membranes should not be used at
the sulfate and the limiting alkaline earth metal is one-         pressures greater than the manufacturer's
third of the saturated condition at ambient temperature,          recommended pressure, since they are prone to
distillation design must include pretreatment to reduce           membrane degradation by pressure compaction.
or inhibit the scaling ions. High-temperature distillation
is also limited to oil and grease levels below 1 milligram                    (2) Polyaromatic amide membranes.
per liter. All other limitations on the high-temperature          Brackish water polyaromatic amide membranes are
distillation process are equipment specific and require           generally limited to operation in feed waters between pH
individual evaluation.                                            4 and pH 11. Polyaromatic amide membranes are less
                                                                  pH tolerant and should not be used outside of the range
     b. Low-temperature and mechanical distillation.              pH 5 to pH 9. All polyaromatic amide membranes are
Low-temperature and mechanical distillation systems               limited to use on feed streams that are free of residual
are limited to operation below saturation of alkaline             chlorine. If chlorination is necessary or desirable as a
earth sulfates and carbonates. The lower operating                pretreatment option, complete dechlorination must be
temperature permits economical operation on waters                effected. Polyaromatic amide membranes are tolerant
that are at or below half saturation at ambient                   of water temperatures up to 95 degrees Fahrenheit.
temperature. Oil and grease are limited to less than 1            While polyaromatic amide membranes are not as
milligram per liter. Any other limitations are equipment          quickly or completely compacted as are cellulose
specific.                                                         acetate membranes, manufacturer's recommended
                                                                  pressures must be followed to prevent mechanical
     c. Reverse osmosis. The most severe limitation               damage to membrane modules.
on reverse osmosis is the maximum limit of 50,000
milligrams per liter of total dissolved solids in the feed             d. Electrodialysis reversal. While electrodialysis
water. Another limitation is that there must be no iron in        reversal has been used to treat water as saline as sea
the feed water. This limitation is so rigid that only             water, 4,000 milligrams per liter of total dissolved solids
stainless steel and nonferric materials will be used              is considered to be an upper limit for economical
downstream of the iron removal. The solubility of                 operation. Some electrodialysis membranes can
alkaline earth sulfates and carbonates limits reverse             tolerate strong oxidants, like chlorine, but most cannot.
osmosis treatment. Any water containing less than                 The reversal of polarity used in electrodialysis reversal
4,000 milligrams per liter of total dissolved solids that         for removal of scale allows operation on water that is
would be saturated with an alkaline earth sulfate when            saturated with alkaline earth carbonates. Saturation
the concentration is multiplied by 1.5 should not be
considered for reverse osmosis desalination. Reverse
osmosis is limited to waters that do not have silica
saturation in the reject brine. Silica chemistry is

                                                             4-2


---

with an alkaline sulfate with low carbonate alkalinity                                                               TM 5-813-8

should be avoided.                                       tricity. Steam is used to heat the saline water to
                                                         increase its vapor pressure. Normally, electricity is used
4-3. Distillation/condensation energy.  In               to run the compressor in vaporcompression distillation.
                                                         If excess steam is available, its use as a power source
distillation/condensation plants, energy is used in the  should be

form of steam and elec

                        Figure 4-1. Energy consumption.
                                            4-3


---

                                                                      TM 5-813-8
                                                        Appendix B

                                                        Appendix B

Table 4-1. Preliminary desalination process selection.
                                  4-4


---

                                                                                              TM 5-813-8

investigated. The amount of electricity or mechanical          4-6.  Preliminary process selection. Use
work that steam will yield depends on its temperature as
well as the temperature to which it can be condensed.          preliminary site information to eliminate certain
The energy consumption of both vapor compression and
thermal distillation, as related to the total dissolved        desalination processes. A decision logic table for use
solids of feed water, is shown in figure 4-1.
                                                               with preliminary information is shown in table 4-1.
4-4. Membrane energy. Historically, membrane
desalination systems use less energy than other                Decisions based upon table 4-1 are to be considered
systems. Brackish water disalination should be
accomplished by membrane separation processes                  preliminary only. Necessary water quality tests to
because of the reduced energy requirement. The
energy consumption of electrodialysis reversal can be          further support the recommedations made in Column E
made to follow reduced or variable salinity, while the
energy consumption of reverse osmosis is set principally       of table 4-1 are in Column F.
by membrane water flux. Again, the energy
consumption of electrodialysis reversal and reverse            4-7. Process selection. When initial site and raw
osmosis as a function of the total dissolved solids            water source selections have been made, use
content of the feed water is shown in figure 4-1. As           preliminary water quality information with table 4-1 to
membrane materials are developed, energy                       assist in a preliminary process selection. As more
consumption may be reduced.                                    specific information is obtained from laboratory analyses
                                                               of water quality, make an initial process selection using
4-5. Waste disposal. Waste disposal may influence              the second decision logic table, table 4-2. After a
process selection. Since brine disposal costs can be an        treatability investigation has been completed, select the
important part of process economics, brine disposal            final desalination process. A final decision logic table,
alternatives must be explored while water quality              table 4-3, assists in the final process selection. The use
analyses are being performed. For further information,         of the decision logic table sequence will only provide
refer to Chapter 10 on waste disposal.                         generalized assistance in process selection; additional
                                                               economic, engineering, and environmental studies may
                                                               indicate that methods or combinations of methods must
                                                               be used.

                                                          4-5


---

                                                                                                                                                   TM 5-813-8

Table 4-2. Selecting desalination processes after water quality data are obtained.
                                                    4-6


---

                                                                                                                                              TM 5-813-8

Table 4-3. Final selection of a desalination technique from treatability data.
                                               4-7


---

                                                                                                                   TM 5-813-8

                                       CHAPTER 5
                     PRETREATMENT CONSIDERATIONS

5-1. General. Before raw water is desalinated, the                 systems through the formation of scale. Materials that

undesirable materials will be removed or reduced to                precipitate easily to form scale are double-charged

acceptable levels. Such materials to be removed                    positive ions, such as calcium and magnesium salts. As

include solids, immiscible liquids, and sparingly soluble          water volume is reduced, the concentration of all ions

salts. Accumulations of these materials on desalination            and materials is increased. When the concentration

process surfaces greatly reduce efficiencies. Without              reaches saturation, scale is formed. With alkaline earth

adequate pretreatment, desalination facilities are                 sulfates and carbonates, the saturation concentration is

destined for reduced lifetimes, shortened periods of               reduced by increasing temperature. Ion exchange (see

operation, and high maintenance. The feedwater                     Chap. 8) as well as chemical treatment followed by

limitations for various desalination processes are                 filtration can reduce the levels of sparingly soluble salts

summarized in table 5-1. An overview of typical                    before desalination processes. However, such a

pretreatment options is shown in figure 5-1.                       treatment system may not be cost effective, economic

a. Solids. Physical and chemical treatment                         evaluation is needed before proceeding with detailed

processes will be used to remove solid materials. The              design. The concentration factor limits for calcium

level of solids removal will depend on the desalination            sulfates in sea water are shown in figure 5-2.

process to be used.                                                5-2. Chemical treatment. Many materials, e.g.,

             (1) Settleable solids. Settleable solids are          calcium salts, magnesium salts, oil and grease, total

easily removed from water by gravity settling or                   suspended solids and some organic contaminates, that

filtration.                                                        are harmful to desalination processes can be reduced to

                                                                   acceptable levels by chemical treatment. Chemical

             (2) Non-settleable solids. Non-settleable             treatment may involve any of the following: coagulation,

solids are removed by chemical treatment. Chemical                 either with or without clarification; pH adjustment, which

treatment may be designed to remove not only non-                  may influence fluoride removal; or scale inhibition.

settleable solids but to precipitate and remove scale-             When required, degasification and secondary filtration

forming solids.                                                    follow chemical treatment.

             b. Immiscible liquids. Emulsified oil and             a. Coagulation. Non-settleable solids and some

grease are the principle sources of immiscible liquid              suspended materials do not precipitate because of

fouling in desalination facilities. Use gravity settling and       electrical charges on the surface of the particles. If the

chemical treatment processes followed by a filtration              charges on the particles can be reduced, the particles

system to maintain immiscible liquid concentrations                may precipitate. Chemicals that lower surface charges

within acceptable levels. To measure low levels of oil             are lime, alum, ferric salts, and polyelectrolytes.

and grease, a sophisticated concentration procedure                Evaluate each chemical used in pretreatment to

must be performed.                                                 determine its effect on the successive steps in the

c. Dissolved organic contaminants. The most                        desalination process. For example, calcium present in

common organic materials, tannins and humic acids,                 lime can cause an increase in scale formation in

can be removed from water by chemcial treatment.                   distillation/condensation processes; the iron present in

Some organic materials will carry across a                         ferric salts can cause excessive fouling in membrane

distillation/condensation process with the water.                  desalination systems; alum is usually the best coagulant

Pesticides and industrial organic chemicals may be                 for desalination systems. Do not use pretreatment

difficult to remove by distillation/condensation. Reverse          chemicals without prior operational experience and an

osmosis will usually remove the majority of the large              exhaustive actual application review. The non-

pesticide molecules. If during pretreatment tests a non-           settleable solids and the suspended solids in conjunction

ionized organic contaminate is not reduced to                      with any added coagulants will be removed by either

acceptable levels, then a full treatability investigation          standard clarification techniques or direct filtration.

will be performed to ensure that potable water standards           Lime softening

are met.

d. Sparingly soluble salts. As physical and

chemical conditions change during desalination, some

soluble materials become insoluble (precipitate). This

precipitation of solid materials can foul desalination

                                                              5-1


---

                                                                                                                                                                                                        TM 5-813-8

NOTES *Based upon manufacturer's guarantee
                                    Table 5-1. The maximum allowable contaminants in the feed water used by various desalination processes
                                                                                                          5-2


---

without adequate downstream filtration and pH                                                                         TM 5-813-8
adjustment will lead to suspended lime particles in the
feed water. Lime softening will usually remove a          conducted to assure the optimal coagulation process
significant amount of fluoride and may adjust the pH to   design.
the higher levels, above 7.0, where fluoride removal is
optimized. Laboratory analysis or pilot studies shall be       b. pH adjustment. The pH adjustment step of
                                                          pretreatment must result in the optimal pH level for the
                                                          individual desalination system. After coagulants have

Figure 5-1. Pretreatment techniques.
                      5-3


---

been added, the pH is often changed significantly. In                                                               TM 5-813-8
most cases, the pH must be returned to a neutral or a
slightly acid level. Adjustment chemicals to lower the  with lime pretreatment. Sulfuric acid should not be used
pH include carbon dioxide, sulfuric acid, and           for pH adjustment of systems where the resulting
hydrochloric acid. Carbon dioxide should not be used    increase in sulfate salts can cause scaling in the
for pH adjustment of lime addition systems because of   desalination system. Fluoride removal will be hindered,
the previously mentioned scaling problem associated     if the pH is reduced below 7.0.

                                                             c. Scale inhibition. The formation of scale

Source. American Institute of Chemical Engineers
                         Figure 5-2. Approximate concentration factor limits for calcium sulfate in sea water.
                                                                               5-4


---

                                                                                                               TM 5-813-8

limits the efficiency of product water recovery during               systems are generally used. In some cases, mixed-
                                                                     media filtration may be necessary. Filters may use
plant operation. The precipitation of calcium carbonate,             either pressure or gravity flow methods.

magnesium hydroxide, and calcium sulfate can be                           a. Single-media filtration. Single-media filtration
                                                                     consists of one media. This media is often small-
prevented through the addition of scale-inhibiting                   grained silica sand; however, anthracite may be used
                                                                     after lime and lime-soda softening. Some desalination
chemicals. Two scale-inhibiting chemical types are                   pretreatment systems use an alternate media such as
                                                                     greensand to remove iron compounds. Diatomaceous
commonly used: polyphosphates and polyelectrolytes.                  earth media is not recommended for primary filtration
                                                                     because of its characteristic high head loss and short
The most commonly used scale inhibitors are                          fun times.

polyphosphate chemicals. Polyphosphates lose their                        b. Dual-media filtration. Dual-media filtration
                                                                     consists of two media with different specific gravities.
effectiveness above 190 degrees Fahrenheit, which                    The difference creates a two-layer separation effect.
                                                                     Use silica sand or greensand for one layer; use
limits upper operating temperatures. To prevent the                  anthracite for the other layer. The use of dual media will
                                                                     allow larger quantities of material to be filtered and will
formation of scale within desalination systems,                      reduce head loss during operation. The use of two
                                                                     media types will provide a good coarse-of-fine filtration
polyphosphate-based chemicals are the best general                   process for desalination facilities.

purpose additive. The most commonly used                                  c. Mixed-media filtration. When three media are
                                                                     used in filters, a better coarse-to-fine filtration pattern
polyphosphate  compound         is                 sodium            can be constructed. High-density silica sand, garnet,
                                                                     and anthracite are commonly used to provide the filter
hexametaphosphate. Polyelectrolytes or organic                       bed. The different media do not stratify completely.
                                                                     Instead, there is a small amount of intermixing among
polymers are relatively new scale inhibitors. The use of             the different layers. This gradual change in media size
                                                                     provides a gradient from coarse to fine and creates a
polyelectrolytes in potable water shall be in accordance             media flow pattern necessary to achieve a very low silt
                                                                     density index.
with paragraph 7 of AR 420-46.

5-3. Degasification and deaeration. The removal

of dissolved gases from a feed water can be

accomplished in one of two ways. The dissolved gas

may be stripped out with another gas, or the dissolved

gas may be stripped out with water vapor. A forced

draft degasification tower will remove nonatmospheric

gases. This is done by blowing air up through a tower of

packing. The water to be degasified is then sprinkled

over the packing. When full deaeration is required to

prevent the interference of oxygen and nitrogen with

water vaporizaton or flashing, steam or water vapor

must be used as the stripping gas. On high-temperature

distillation systems, a steam deaerator may be used.

On most distillation desalination systems, the only

economical method of deaeration the water is to lower                5-5. Secondary filtration. Secondary filtration is

the pressure with a vacuum pump or venturi eductor or                necessary to ensure that particulate material does not

ejector to produce enough water vapor to strip away all              pass from the pretreatment systems into a membrane

dissolved gases. There are two basic designs for water               desalination process. Secondary filtration is used

distribution in deaerators. A design that sprays the                 normally as a precautionary measure. Cartridge filters

water in the deaerator vessel will usually create the                are commonly used. Ultrafiltration systems can be used

most complete deaeration. The other commonly used                    as a process and precautionary measure.

design involves cascading the water over trays. While                a. Cartridge units. The necessary protection is

the internal design of this deaerator is prone to short              most easily accomplished with cartridge filters. The

circuiting and incomplete deaeration, it is more compact             cartridges are replaced easily, and the filter mesh can

and requires no pressure to operate the sprayers.                    be sized to remove from 20-micron to 0.05-micron

                                                                     particles. Although some cartridge filters can be

5-4 Filtration with granular media. Before the                       backwashed, most are replaced when head loss reaches
filtration is designed, the possibility of use of
wells/infiltration galleries shall be evaluated. Filtration is       excessive levels.
necessary when the desalination process requires a low
level of particulate material. Primary filtration with               b. Ultrafiltration units. The newer process for
granular media removes particulate materials left after
lime, coagulates, or other chemicals have been added                 secondary filtration is ultrafiltration.  New
to the feed waters. Single-or dual-media filtration

                                                                5-5


---

                                                                TM 5-813-8

Figure 5-3. Disinfection alternatives.

materials provide 0.005-micron filtration in a stable,          5-6. Disinfection. Biological growth can seriously
backwash operational unit. Some ultrafiltration units           interfere with desalination surfaces and equipment.
possess a salt-rejection capability, which reduces both         Cellulose acetate reverse osmosis membranes can be
the ultrafine particulate material and salt loading on          attacked by bacteria and require continuous disinfection
membrane desalination processes. The ability to ensure          application at the membrane surface. Disinfection of
particulate removal at 0.005-micron levels, as well as          potable waters is required by TB MED 576 for sanitary
backwash capabilities, makes ultrafiltration an excellent       reasons. Marine intake structures are particularly prone
secondary filtration technique.

                                                           5-6


---

                                                                                                      TM 5-813-8

to biogrowths. A strong biocide is usually needed to              time, which will increase the number of organisms
prevent extensive marine growths from fouling intakes,
piping and storage facilities. An overview of disinfection        destroyed, it will also increase trihalomethane formation.
alternatives can be found in figure 5-3. Chlorination is
not advisable in the pretreatment process when organic            When an open intake requires optional disinfection as
contents are high.
                                                                  shown in figure 5-1 and chlorination is shown by
     a. Ultraviolet irradiation. One effective disinfection
technique is ultraviolet irradiation.                             pretreatment investigation to bring the trihalomethane
Raw wafers flow through a chamber where they are
exposed to ultraviolet lamps. The resulting disinfection          content above 0.1 milligrams per liter, then no form of
prevents bacterial destruction of cellulose acetate-based
membrane systems and eliminates biofouling of                     chlorine shall be used as a raw water disinfectant. The
polyaromatic-based membrane systems. Because
polyaromatic fiber membranes are very susceptible to              legal limit (per National Interim Drinking Water
chemical oxidant attack, ultraviolet disinfection is the
best disinfection technique for these systems.                    Regulations) for trihalomethanes in potable water

     b. Oxidants. The addition of chemical oxidants,              effluents for communities and installations with an
such as chlorine, bromine, iodine, or ozone, can provide
biological disinfection before membrane processes. The            effective population of 10,000 or more is 0.1 milligrams
use of oxidants must be monitored carefully to keep the
chlorine below 1.0 milligrams per liter of free chlorine          per liter.
residual that would even damage cellulose acetate
membrane systems. For cellulose acetate membrane                  c. Dechlorination. When chlorine is used as a
systems, a carefully monitored oxidant addition is the
best technique for disinfection of biologically active feed       disinfectant, complete dechlorination of pretreated
waters. When biological and other organic materials are
chlorinated, the resulting chlorine oxidation generates           waters must occur before desalination in polyaromatic
halogenated carbon compounds, such as the
trihalomethane class of compounds. While the                      membrane systems.  Dechlorination can be
placement of chlorine disinfection upstream of
coagulation of filtration will increase chlorine contact          accomplished chemically through sulfite compound

                                                                  addition or passage through granular-activated carbon.

                                                                  Complete dechlorination and destruction of the chlorine

                                                                  residual by reducing compounds will ensure that

                                                                  chemicals do not attack these sensitive membrane

                                                                  systems. When a chlorinated water source must be

                                                                  used and complete dechlorination below 1.0 milligrams

                                                                  per liter as free chlorine is not possible, use

                                                                  distillation/condensation. When dechlorination is only

                                                                  economically practical to between 0.2 and 1.0

                                                                  milligrams per liter as free chlorine, a cellulose acetate-

                                                                  based membrane system may be used.

                                                             5-7


---

                                                                                                         TM 5-813-8

                                          CHAPTER 6
                 DISTILLATION/CONDENSATION TECHNIQUES

6-1. General. Distillation/condensation is the most               problem, corrosion of flash-evaporation units is of
                                                                  concern.
common desalination process. More than 70 percent of

all desalination facilities in use today employ some

variation of the distillation/condensation process.               6-3. Low-temperature distillation. Distillation/
                                                                  condensation facilities that operate at temperatures less
6-2. High-temperature distillation.                  High-        than 205 degrees Fahrenheit are low-temperature units.
                                                                  In situations where waste heat is plentiful, low-
temperature distillation faciilties that operate at               temperature waste-heat-recovery evaporation units are
                                                                  used. A waste-heat-recovery unit is shown in figure 6-4.
temperatures greater than 205 degrees Fahrenheit are              For onshore application, low-pressure waste steam from
                                                                  power generation facilities can provide the necessary
the most prevalent desalination facilities in the world           thermal energy for desalination systems. The most
                                                                  recent developments in distillation/condensation
today. There are three methods of vaporizaiton:                   technology involve the use of waste heat or lowpressure
                                                                  steam with evaporation units and a mechanical vapor
submerged tube vaporization; flash vaporization; and              compression system. Multiple stages then derive the
                                                                  maximum vapor and product water production from the
thin-film vaporization. These methods are illustrated in          system.

figure 6-1. Submerged tube vaporization is the least

efficient vaporization technique, but it allows for easy

maintenance. This type of vaporization system is most

often used in exhaust gas waste heat recovery

distillation systems. The flash vaporization technique is

presently the most common technique in existing

distillation units. The impact of sprayed hot brine within

the evaporator unit causes both erosion and corrosion of

most metals. Using a thin-film sprayvaporization                  6-4. Mechanical distillation.          The use of

process, the raw water is introduced at slightly less than        mechanical methods for vapor production and heat

atmospheric pressure through an orifice onto heat                 transfer can result in a highly efficient desalination

exchanger tubes for immediate vaporization. The                   system. These systems operate at temperatures less

corrosive environment is reduced from the flash                   than atmospheric boiling point and use a variety of

vaporization system, but scaling can occur on the heat            methods to vaporize raw waters. These mechanical

transfer surfaces. These vaporization techniques are              processes commonly use multiple effects to maximize

used in the two major high-temperature distillation               the efficiency of the applied mechanical energy.

processes, multiple-effect (ME) evaporation, and                  a. Vapor compression. The technique of vapor

multistage flash (MSF) evaporation.                               compression uses a mechanical energy source, such as

a. Multiple-effect evaporation units. To maximize                 an engine of electric motor, to power a compression

thermal  energy  efficiency          within               a       turbine. This turbine draws vapor from the distillation

distillation/condensation system, several units or effects        vessel and compresses it, which raises the temperature

are used. The heat from the condensation step of one              of the exhaust vapor. The vapor is then passed over a

effect is used to supply vaporization heat for the                heat exchanging condenser, where it returns to the

following effect. The next effect is a slightly lowered           liquid state as product water. The heat removed during

pressure and temperature. This gradual reduction by               condensation is returned to the raw water to assist in the

heat transfer results in a much greater yield of product          production of more vapor. The more recent vapor-

water from a given quantity of thermal energy. A typical          compression multiple-effect units produce a

multiple-effect evaporation unit is shown in figure 6-2.          concentrated brine byproduct that has had its excess

b. Multistage flash-evaporation units. Distillation               heat reduced by the multiple effects.

technology was advanced through the development of                b. Waste heat. Adding waste heat to vapor

multistage flash evaporation units. Stages of flash               compression systems results in a highly efficient

evaporation are operated using heat from an external

source. Pressure is reduced gradually in each

successive stage to continue flash operation at

successively lower temperatures and pressures.

Because scaling is not a serious problem, this design

has become the most prevalent distillation process. A

typical multistage flash-evaporation unit is shown in

figure 6-3. Although internal scaling is not a great

                                                             6-1


---

                                                                                              TM 5-813-8

Figure 6-1. Three methods of vaporization.
                          6-2


---

                                                                                                          TM 5-813-8

Figure 6-2. Multiple-effect vertical-tube evaporation process.
                                      6-3


---

                                                                                                TM 5-813-8

Figure 6-3. Multistage flash distillation facility.
                            6-4


---

distillation/condensation process. These systems are                                                                TM 5-813-8
designed to maximize the production of product water
with minimal energy input. A typical vapor-compression  The advantages of this type of system include a lower
multiple-effect system is shown in figure 6-5.          energy demand than high-temperature distillation, less
                                                        corrosion due to possible use of thermoplastic materials,
                                                        and lower operational temperatures.

Figure 6-4. Waste heat recovery evaporation process.
                                  6-5


---

                                                                                                            TM 5-813-8

Figure 6-5. Vapor-compression vertical-tube distillation system.
                                        6-6


---

                                                                                                    TM 5-813-8

6-5. Thermal discharge. A problem resulting from                b. Existing or planned facilities. Distillation/
all distillation/condensation facilities is thermal
discharge of liquids. Older high temperature facilities         condensation systems design must include availability
produce brine at very high temperatures. Cooling
towers, heat exchangers, or similar equipment must be           of energy information. See sample problem A-8.
designed into the process to handle the thermal
discharge from distillation/condensation facilities. More       Alternative steam sources considered in the design must
sophisticated desalination units employ a system of heat
exchange devices that use the raw feed water to cool            include steam temperature, steam pressure, and
the brine and reclaim this waste heat to help provide
thermal energy for system operation.                            available quantity of steam. The design must show

6-6. Design analysis. When it is necessary to                   available electrical power including voltage, amperage,
review several water distillation/condensation designs,
standard dimensionless analysis will be used for design         phase of the available electricity, and frequency of the
comparison. If dimensionless correlations for particular
aspects of design do not exist, a bench- or pilot-scale         available electrical power.
study should be done.
                                                                c. Raw water information.           One of two
6-7. Materials of construction . The corrosive
nature of high-temperature brines, acid pretreatments,          circumstances will limit the quantity of raw water
and chemical scaling can cause plant failure. Presently,
the only acceptable construction materials for wetted           consumed. Both of these limitations must be
surfaces in high-temperature systems are an austenitic
stainless steel, such as AISI Type 316L of titanium.            considered in the design:
Anodized aluminum and many thermoplastic materials
are acceptable for use in low-temperature systems.                      -The availability of raw water may place a

6-8. Distillation/condensation system design .                          limitation on the raw water used in the
Pursuant to finalized site and process selection, one
distillation/condensation system will usually be chosen.                process.
When the process selection does not yield a single
process, then designs must be prepared for more than                    -The maximum amount of waste brine that
one process.
                                                                        can be economically disposed of may
     a. Identification of work. When the base site has
been selected and a schedule for construction has been                  limit the raw water used in the process.
prepared, this information will be made available to the
water treatment engineer. The identification of the             The principle requirement in a desalination design is an
location and the time schedule will be considered in the
design; this includes the date the system must be online.       accurate projection of the chemical makeup of the worst
The minimum number and minimum size of the
modules will be determined. Any restrictions that               quality water that will be used as raw feed water at the
storage will place on maximum allowable downtime will
also be determined. With distillation/ condensation             site being investigated. The design must include
systems, the design must address the maximum
allowable total dissolved solids and, where applicable,         consideration of the maximum total dissolved solids,
the minimum allowable rejection of distillable material.
Distillable material is defined as nonaqueous, volatile         individual ions (see App. B), maximum amount of total
water contaminants.
                                                                suspended soiled present in the feed water, maximum

                                                                organic contaminant loading, and any gas or potential

                                                                corrosive agent that may be in the feed water. All

                                                                known or anticipated future qualities of the feed water

                                                                shall be considered in the design.

                                                                d. Process        design.           When          a

                                                                distillation/condensation process has been identified as

                                                                the most economical, then the design will be limited to

                                                                the single process. The process design for any

                                                                distillation/condensation process will include a minimum

                                                                required input temperature and some maximum

                                                                required heat sink temperature. Between these two

                                                                temperature criteria, the process must be capable of

                                                                producing the required product water quality and

                                                                quantity. When a particular metallurgy is required for

                                                                strategic, corrosion design, or economic reasons, this

                                                                metallurgy shall be designated for all applicable parts,

                                                                as well as spare parts. All required instrumentation

                                                                must be included in the design. The design must show

                                                                the required output water quality based on the worst raw

                                                                water input chemistry and quality. The system design

                                                                must be based on equipment with a history of successful

                                                                water treatment system experience. The required

                                                                experience history should include a minimum of 2 years

                                                                of operating experience meeting water quality and

                                                                system                                    design

                                                           6-7


---

goals, treatment capacity, maximum allowable repair                                                                     TM 5-813-8
frequency and duration, and a maximum allowable ratio
of experienced capital cost to repair cost.                 The requirement for successful experience will limit the
                                                            amount of untested innovation used at a facility.

                                                       6-8


---

                                                                                                              TM 5-813-8

CHAPTER 7

MEMBRANE TECHNIQUES

7-1. Electrodialysis. The ions in a water solution                c. Electrodialysis reversal.  One important
can be made to migrate by applying an electric field to
the solution. By arranging various barriers to the flow of        improvement now used in electrodialysis installations is
ions, it is possible to directly desalinate water with
electricity. Such barriers are called ion-exchange                to reverse the polarity periodically and move the ions in
membranes. Membranes that allow a reasonable flow
of cations, but block or reduce the flow of anions, are           the opposite direction. This returns anions across the
called cationic-exchange membranes. Membranes that
allow a reasonable flow of anions, but block or reduce            anionic membranes and helps break up scale formed on
the flow of cations, are called anion-exchange
membranes. Membranes that pass both anions and                    the concentrating face of the membranes. Water will
cations are called neutral membranes.
                                                                  flow osmotically across both membranes from the dilute
     a. Theory. In solutions containing dissolved ions,
electric currents are carried by movement of the ions.            product stream to the concentrated brine stream in an
Positive ions migrate in the direction of the current flow,
and negative ions migrate against the current direction.          electrodialysis-reversal stack. This osmotic product
When the anions are blocked by a cationic-exchange
membrane, they stop and form a localized charge at the            water loss concentrates uncharged material, such as
membrane face. This accumulated negative charge is
neutralized by the flow of cations across the cationic            turbidity and bacteria. This concentration effect must be
membrane. This generates a concentrated solution on
the side of a cationic-exchange membrane that faces               considered during the design to ensure meeting water
the negative electrode. It also generates a dilute
solution on the side of the cationic membrane that faces          turbidity and product water bacterial count requirements.
the positive electrode as shown in figure 7-1.
                                                                  Most electrodialysis membranes are not tolerant of
     b. Electrodialysis stack. If both a cationic and
anionic membrane are placed across a current flow in              chlorine. When possible, water desalinated by
an electrolyte solution, the side of the cationic
membrane facing the positive electrode and the side of            electrodialysis reversal should be disinfected after
the anionic membrane facing the negative electrode will
become less saline. If the cationic membrane is closer            desalination is completed. The membranes should be
to the negative electrode and the anionic membrane is
closer to the positive electrode, the solution between the        protected by a 10-micron cartridge filter.
membranes will become less saline as the ions migrate
in their respective directions. Any number of pairs of            7-2. Electrodialysis-reversal design.       When
cationic and anionic membranes can be placed across a
current-carrying solution, such that the cationic                 electrodialysis reversal can be shown to be the most
membrane is closest to the negative electrode, and the
solution between will be diluted (fig. 7-1). A battery of         economical process for desalination, then only an
several such membrane pairs is called an electrodialysis
stack. Several variations of the standard electrodialysis         electrodialysis-reversal system will be designed. When
stack have been developed, but none have been proven
superior to this standard stack of alternating cationic-          the process selection does not yield a specific process,
and anionic-exchange membranes to desalinate natural
brackish water.                                                   then designs must be prepared for more than one

                                                                  process.

                                                                  a. Identification of work. The design engineer will

                                                                  be made aware of the base site and construction

                                                                  schedule. The location and time schedule will be

                                                                  considered in the design; this includes the date the

                                                                  system must be online. The minimum number and

                                                                  minimum capacity of the modules will be determined.

                                                                  Any restrictions that storage will place on maximum

                                                                  allowable downtime will also be considered. A

                                                                  maximum allowable output conductivity in the product

                                                                  water will be determined, based on the worst possible

                                                                  feed water.

                                                                  b. Existing on planned facilities.          When

                                                                  electrodialysis reversal is being designed, it is essential

                                                                  to determine the types of available electrical power.

                                                                  The voltage, phase, frequency, and available amperage

                                                                  of all electrical power sources, planned or existing, must

                                                                  be considered in the design.

                                                                  c. Raw water information.                   One of two

                                                                  circumstances will limit the quantity of raw water

                                                                  consumed. Both of these limitations must be

                                                                  considered in the design:

                                                             7-1


---

-The availability of raw water may place a                                                                     TM 5-813-8
 limitation on the raw water used in the process.
-The maximum amount of waste brine that can        The principle requirement in a desalination design is an
 be economically disposed of may limit the raw     accurate projection of the chemical makeup of the worst
 water used in the process.                        quality water that will ever be used as a raw feed water
                                                   at the site being investigated. The design
                                                   documentation must include maximum total dissolved
                                                   solids, the individual ions (see App. B), the maximum
                                                   amount of total suspended solids present in the feed
                                                   water, and any gas or potential corrosive agent that may
                                                   be in the feed water.

Figure 7-1. Principles of electrodialysis desalination
                                7-2


---

     d. Process specifications. When an electro-                                                                            TM 5-813-8
dialysis-reversal process has been identified as most
economical, the design will be limited to the single            solution, provided that the pressure differential exceeds
process. The process design for any electrodialysis-            the osmotic pressure. A typical reverse osmosis flow
reversal process will include a minimum/maximum                 sheet is shown in figure 7-3.
allowed product water conductivity. The design must
show the required product conductivity that must be                  b. Energy recovery. Reverse osmosis produces a
obtainable at the required product flow, based on the           concentrated, high-pressure brine. With reverse
worst conductivity raw water. A 10-micron cartridge             osmosis, the energy lost in depressurizing the brine can
filter to be placed before the membranes must be                be returned efficiently to the feed water by mechanical
included in the design. When a particular metallurgy or         methods. In small systems, consider a flow-work
material is required for strategic, corrosion design, or        exchanger; in large systems, consider an energy
process economic reasons, this metallurgy or material           recovery turbine.
will be designated for all applicable parts and spare
parts and equipment. All required instrumentation,                        (1) Flow-work exchanger. A flow-work
including a voltmeter and an ammeter, for each                  exchanger, figure 7-4, is a simple piston driven by
electrodialysis-reversal stack must be designed. The            pressurized brine to compress the saline feed. When
system design must be based on equipment with a                 the piston has traveled a full stroke, the valving is
history of water treatment system experience. The               changed, and the saline feed is used to expel
required experience history should include a minimum            depressurized brine. Flow-work exchangers have been
of 2 years of operating experience meeting water quality        under development since 1980.
and system design goals, current operating capacity,
maximum allowable repair frequency and duration, and                      (2) Energy recovery turbines. Several large
maximum allowable ratio of experienced capital cost to          reverse osmosis systems have been built with energy
repair cost. The requirement for successful experience          recovery turbines. These turbines can be installed to
will limit the amount of untested innovation used at a          assist directly in pumping or to drive synchronous
facility.                                                       motors and generate electricity. While reverse osmosis
                                                                is an energy efficient desalination process for highly
7-3. Reverse osmosis. Diffusion through materials               saline waters, energy recovery can reduce the amount
is influenced by the nature of the diffusing material. A        of energy used by as much as one-third.
number of materials allow water to pass through with
relative ease. Some of these materials allow only a                  c. Mechanical strength and packing of membranes.
minute passage of ionized material compared to the              For containment of high pressures with thin membranes
passage of water through them. These semipermeable              in reverse osmosis, three alternative arrangements have
materials are used for desalination. If a thin barrier or       been developed.
membrane is used, water can be forced through the
membrane while ions are stopped by the membrane. In                       (1) Porous tubes. Porous tubes lined with
general, nonionized materials, such as some gases and           semipermeable membrane material have been
many organics, will not be removed by these                     developed for concentration of valuable products in
membranes. Some larger organic molecules may not                industry. Such systems are no longer used for water
pass through the membranes.                                     desalination. A packing density of less than 110 square
                                                                feet of surface area per cubic foot of volume makes this
     a. Osmotic pressure. When a semipermeable                  configuration too expensive for water production. See
membrane that will pass solvent is placed between two           figure 7-5.
solutions of different concentrations containing the same
solvent at identical temperatures, the solvent must pass                  (2) Spiral-wound membranes. By using
from the less concentrated to the more concentrated             spacers it is possible to roll a membrane envelope onto
solution as shown in figure 7-2. This flow of solvent           a slotted product water tube as shown in figure 7-6. This
produces a pressure head difference. The equilibrium            reverse osmosis membrane configuration is known as
liquid pressure head difference is called the osmotic           the spiral-wound configuration. This arrangement allows
pressure difference of the solutions (see App A for the         for surface densities of greater than 250 square feet of
calculation). If these pressures are reversed, pure water       surface area per cubic foot of volume. With the
will be forced from the more concentrated solution              development of this spiral-wound configuration, water
through the membrane into the less concentrated                 production from brackish water sources by reverse
                                                                osmosis became economical in many applications. See
                                                                figure 7-6.

                                                           7-3


---

                                                              TM 5-813-8

Figure 7-2. Revere osmosis principles.

          (3) Hollow fine fibers. A large research and        If product water is not supplied, then the osmotic
development effort made it possible to coat minute            suction, if the feed water side of the membrane is
hollow fibers, smaller in diameter than a human hair,         depressurized, will draw air back into the membranes
with semipermeable membrane material. This reverse            and dehydrate them. Usually, the required volume of
osmosis membrane configuration is known as the hollow         product water is supplied by a suck-back tank, which
fine-fiber configuration. Packing densities with hollow       maintains a minimum volume and back pressure on the
fine fibers have exceeded 4,900 square feet of surface        reverse osmosis membranes.
area per cubic foot of volume. See figure 7-7.
                                                                        (1) Cellulose acetates. This material suffers
     d. Membrane materials. There area number of              from slow chemical decomposition through a process
successful reverse osmosis membrane materials.                called hydrolysis. The use of acids to prevent scaling
Currently, two principal types of membrane materials          increases the rate of this form of membrane decay.
are being used: cellulose acetate and polyaromatic            Cellulose acetates are also biodegradable and must be
amide. Both materials are destroyed by dehydration of         protected from bacterial attack. One of the important
the membranes. To avoid dehydration, product water            advantages of cellulose acetate is its resistance to
must be supplied to allow osmotic water to flow back          attack by chlorine.
through the membranes in order to dilute the feed water
to approximate product water concentrations.

                                                         7-4


---

                                                                TM 5-813-8

Figure 7-3. Reverse osmosis desalination system.

Most cellulose acetate membranes can be used with               chemical stability, these membranes cannot tolerate any
feed waters containing less than 1 milligram per liter of       residual oxidant. If chlorination is required to reduce the
residual chlorine, which will protect the membranes from        amount of biological suspended solids, then
biological attack.                                              dechlorination must be complete if polyaromatic amide
                                                                membranes are used.
          (2) Polyaromatic amides. These membranes
are stable, biologically and chemically. Despite this

                                                           7-5


---

                                                                                                                          TM 5-813-8

Figure 7-4. Flow-work exchanger principles.
                           7-6


---

                                                                  TM 5-813-8

Figure 7-5. Construction of a tubular reverse osmosis membrane.

7-4. Reverse osmosis membrane staging                             waters, whose product water salinity cannot be reduced
configurations. Two kinds of membrane staging are                 to the required concentration by a single pass through
commonly used in reverse osmosis desalination plants:             the membrane under consideration. Banking is the term
product staging and reject staging. Reject staging is             usually used for parallel arrangement of a number of
used to treat waters with low salinity, so that most of the       membrane modules operating from the discharge of a
raw feed water will eventually be recovered as product            single pump.
water. Product staging is used to treat highly saline

                                                             7-7


---

                                                                                                           TM 5-813-8

Figure 7-6. Internal construction of a spiral-wound membrane.
                                       7-8


---

                                                                                                                                                        TM 5-813-8

Figure 7-7. Internal construction of a hollow fine-fiber reverse osmosis membrane module.
                                                          7-9


---

                                                                 TM 5-813-8

Figure 7-8. Reverse osmosis product staging.

Banking of membranes usually require a flow restraint            membrane modules. While higher flow rates will tend to
on the brine reject of each module in the bank. A pigtail        clean membranes, excessive flow can fatigue or fray
of nylon tubing is often used for this flow equalization         both spiral and hollow fine-fiber membranes. Low flow
headloss. This pressure drop maintains a balanced flow           rates allow the concentrated brine to stagnate, which
of brine out of each membrane module in the bank.                leads to scaling and fouling of membrane surfaces.
Unbalanced flow can shorten the useful life of

                                                           7-10


---

     a. Product staging. Product staging is true series                                                                       TM 5-813-8
operation of two or more reverse osmosis membrane
systems, as shown in figure 7-8. Product staging is               The design of reject staging, in order to balance the
used when a single pass through one reverse osmosis               utilization of the membrane modules for optimum
membrane does not bring a constituent concentration               economical life cycle cost, is a complex activity to be
down to specification. The second stage always                    performed by the membrane manufacturer or
requires its own pressurizing pump, taking suction from           Operations Engineering Manufacturer.
the suck-back or storage tank of the first stage reverse
osmosis system. When the water produced from the                       c. Combined product and reject staging. In the
second stage is significantly lower in dissolved                  desalination of highly saline waters such as seawater,
constituents than required, the product water from the            product and reject staging can be effectively combined.
first stage may be blended with the second stage                  The second stage of a product staged system can be
product to produce the desired water quality. When                designed as a reject staged subsystem. Any of three
potable water and other waters with lower dissolved               factors may limit reverse osmosis water recovery:
solids content are required, a product staging system             osmotic pressure; sparingly soluble salts; or turbidity.
can be used to supply the desired quality or qualities            Water from a primary reverse osmosis treatment system
between that of the first and second stage product. Life          will have three properties pertaining to these limitations:
cycle costing should be used to evaluate dual- and
triple-distribution systems where product staging is                               -A lower osmotic pressure than the raw
required.                                                                           feed water.
                                                                                   -A disaproportionately reduced concentra-
     b. Reject staging. Reject staging, figure 7-9, is                              tion of divalent ions.
used when the low salinity of the raw water permits a                              -No turbidity.
high water-recovery ratio. Most membrane module                   These qualities of primary reverse osmosis product
manufacturers have a minimum allowable brine reject               water can allow for greater water recovery from a
flow for any given membrane of their manufacture. The             secondary product staged reverse osmosis subsystem
manufacturer's recommended maximum feed water flow                than is allowed by the manufacturer's maximum
rate and minimum recommended brine reject flow can                recommended recovery rate. When the water recovery
be used to calculate a maximum recommended single                 of the second stage of a product staged system can be
stage recovery fraction by use of the following equation:         increased by reject staging, the secondary stage shall
                                                                  be reject staged. When the brine from the secondary
                     F - B =R                                     stage of a product staged system is less concentrated
                       F                                          than the primary stage feed water by more than 1,000
                                                                  milligrams of total dissolved solids per liter, the use of
Where:                                                            dedicated desalination of this lower concentration water
          F = Maximum recommended feed flow per                   shall be life cycle costed. This life cycle cost for
                module                                            dedicated secondary stage brine desalination shall be
          B = Minimum recommended brine reject flow               compared with the life cycle cost of blending the
                per module                                        secondary stage brine into the primary stage feed water.
          R = Maximum recommended recovery rate
                                                                  7-5. Reverse osmosis system design. When
This maximum single stage water recovery is one                   process selection does not yield a specific membrane or
means of evaluating a membrane module being                       even a particular process, then designs must be
considered for low salinity reverse osmosis desalination.         prepared for more than one process.
When the reject stream is still diluted enough for further
concentration after the maximum recommended                            a. Identification of work. When a schedule and a
recovery ratio is reached, the brine can be piped directly        base site have been selected, this information will be
into another membrane module for further water                    made available to the design engineer. The
recovery. This is accomplished by combining the brine             identification of the location and the time schedule will
flow from a number of first stage modules onto a fewer            be considered in the design; this includes the date the
number of secondary membrane modules. It is                       system must be online. The minimum number of
occasionally possible to further concentrate the brine on         independently operable membrane banks and the
a third reject stage as shown in figure 7-9.                      minimum capacity of the banks must be determined.
                                                                  Any restrictions that storage will place on maximum
                                                                  allowable downtime will also be determined.

                                                            7-11


---

                                                                 TM 5-813-8

Figure 7-9. Reverse osmosis membrane reject staging.

All reverse osmosis designs will consider a minimum              The phase, voltage, frequency, and amperage of all
membrane rejection for all objectionable materials in the        available or planned electrical power will be determined.
pretreated saline water.                                         The process design, particularly with respect to pumping
                                                                 and pretreatment, must be detailed clearly.
     b. Existing or planned facilities. Reverse osmosis
design must include information on the available                      c. Raw water information. As with other
sources of mechanical energy. Electrical power is the            desalination systems, one of two limitations exist on the
most common energy source for conversion to                      quantity of raw water to be desalinated.
mechanical pumping energy.                                       Both of these limitations must be considered in the
                                                                 design:

                                                           7-12


---

                 -The maximum amount of waste brine that                                                                         TM 5-813-8
                  can be economically disposed of may
                  place a limitation on the raw water used in        A suitable tank to meet suck-back requirements will be
                  the process.                                       designed for all membranes that could be damaged by
                 -Availability of the raw water may limit the        dehydration. The system design must be based on
                  raw water used in the process.                     equipment with a history of successful water treatment
The principle requirement in a reverse osmosis design is             experience. The required experience should include a
an accurate projection of the chemical, biological, and              minimum of 2 years of experience, treatment capacity,
physical makeup of the poorest quality water that will               repair frequency and duration, and a ratio of repair cost
ever be used as raw feed water at the site being                     to capital cost. The requirement for successful
investigated. The design documentation must include                  experience will limit the amount of untested innovation
the following:                                                       used at a facility. When a particular metallurgy or
                 -Maximum total dissolved solids.                    material is required for strategic, corrosion design, or
                 -Maximum concentration of every ion that            process economic reasons, this metallurgy will be
                  could precipitate or influence the activity        included for all applicable parts and spare parts and
                  coefficient of a precipitation reaction.           equipment.
                  (See App. B.)
                 -Maximum concentration of each ion that             7-6. Materials of construction.
                  must be controlled in the product water.           Ferric ions will cause severe problems in membrane
                 -Concentration of both molybdate reactive           systems. For this reason, never permit carbon steel to
                  and molybdate nonreactive silica.                  be in contact with the feed water being supplied to a
                 -Maximum allowable concentration of                 membrane desalination plant. Use nylon or other
                  nonionizable material.                             plastics capable of maintaining the desired pressures
                 -An oil and grease analysis to levels below         whenever possible. Use 316L stainless steel for pump
                  10 milligrams per liter.                           impellers and other feed-water-contact metal surfaces if
                 -Any gas or potential corrosive agent that          hexametaphosphate is used for scale control. If no
                  may be in the feed water.                          scale inhibition is necessary, use bronze for pump
     d. Process design. When a particular membrane                   impellers.
has been identified as the most economic, the design
will be limited to the one membrane type. The process
design for any reverse osmosis process will consider
raw water quality and the required final product water
quality.

                                                               7-13


---

                                                                                                              TM 5-813-8

                                                       CHAPTER 8
                                                    ION EXCHANGE

8-1. General. Some naturally occurring and                        Although not desalination, the exchange of sodium ions

synthetic materials can exchange one type of ion for              for divalent cations produces a change in the type of

another dissolved ion of like charge, e.g., one positive          salinity. This change in the salinity reduces the levels of

ion for another positive ion. The number of charges on            the calcium and magnesium ions, such that the

the ions removed from solution must equal the number              concentration of other ions in the reject or blowdown

of charges on the ions exchanged from the material.               stream can be increased in the desalination process with

The major types of synthetic ion-exchange resins that             a resultant increase in water recovery. Saturation of

have been developed are as follows: strong acid cation            scale-forming materials, such as calcium carbonate,

resins, weak acid cation resins, strong base anion                calcium sulfate, and magnesium hydroxide, is still

resins, and weak base anion resins. Strong acid and               reached, but the total concentration of salts in the reject

weak acid cation resins exchange hydrogen ions (H+)               attains a higher overall level than would be possible

for other cations. Strong acid cation resins may also             without softening.

exchange monovalent sodium ions (Na+) for such                    b. Dealkalization-softening.                Desalination

divalent cations as calcium (Ca+ +) and magnesium                 processes can best utilize dealkalization-softening as a

(Mg+ +). Strong base anion resins exchange hydroxyl               pretreatment method when the raw water contains high

(OH-) or bicarbonate (HCO3) ions for other anions.                levels of alkalinity, bicarbonate and carbonate ions, and

Weak base anion resins adsorb acidic ionic materials,             high levels of hardness, calcium and magnesium ions.

such as hydrochloric acid, sulfuric acid, and carbonic            A properly operated pretreatment that utilizes a weak

acid from solutions. Once adsorbed on the weak base               acid cation resin will produce water with an alkalinity

anion resin, the anion part of the acid may be                    level of no more than 10 parts per million (as CaCO3)

exchanged for other anions. These exchanges occur                 and a residual hardness approximately equal to the

during the service cycle when treated water is produced.          original raw water non-carbonate hardness.

When the capacities of resins have been used up or                (1) Treatment process. The major benefit of

exhausted, they are regenerated with acid or base or              dealkalization-softening using carboxylic (weak acid

salt to restore the resin to the original ionic state.            cation) resins lies in the actual reduction of the

Illustrations of the strong acid cation resin hydrogen ion-       dissolved solids content of the water. Hydrogen (H+)

cation exchange and the strong base anion hydroxyl ion-           ions from the resin exchange with the divalent calcium

anion exchange that occur in the complete                         and magnesium ions in the water. This exchange

demineralization of water are shown in figure 8-1.                occurs only if the anions of weak acid salts, such as

8-2. Pretreatment. Ion exchange can be used as a                  bicarbonate or carbonate ions, are present. Carbonic

pretreatment method in the desalination process to                acid is formed when the hydrogen and bicarbonate ions

reduce the levels of sparingly soluble salts. A strong            react. The carbonic acid is weakly ionized and reverts

acid cation resin in the sodium form and a weak acid              to its basic constituents of carbon dioxide and water.

cation resin in the hydrogen form can be used. In both            The dissolved carbon dioxide can be removed by using

processes the levels of alkaline earth metal cations,             degasification methods, as discussed in paragraph 5-3.

such as calcium (Ca+ +) and magnesium (MG+ + ), are               The combination of the weak acid cation exchange with

reduced. The use of the strong acid cation resin in the           degasification reduces both the calcium and magnesium

sodium form is called water softening, and the use of             levels as well as the alkalinity level in the raw water.

the weak acid cation resin in the hydrogen form in                (2) Dealkalization-softening uses.                        This

conjunction with a carbon dioxide degasifier is called            pretreatment should be investigated when pH

dealkalization-softening.                                         adjustment of the raw water by an acid addition is

a. Softening. Water softening by sodium ion                       indicated for the desalination process. Weak acid resins

exchange can be used as a pretreatment method in a                use about 10-percent more acid than that required for

desalination process.      During water softening,                pH adjustment alone and will reduce the calcium and

monovalent sodium ions on the strong acid cation resin            magnesium concentration as an additional advantage.

are exchanged for the divalent calcium and magnesium

in the water.

                                                             8-1


---

                                                                TM 5-813-8

Figure 8-1. Principles of ion-exchange processes.

In brackish waters containing essentially only calcium,         8-3. Desalination. Ion exchange can be used as a
magnesium, and alkalinity, the use of weak acid cation          desalination process in the production of potable water.
resins with degasification could be considered as a
possible desalination process. Since some types of                   a. Requirements. There are several basic
weak acid cation resins also permit the efficient removal       requirements for the ion-exchange process to be used
of sodium bicarbonate, the process becomes applicable           economically for the desalination of brackish waters.
as a desalination process when the raw water contains
mainly sodium and alkalinity.

                                                           8-2


---

                 -The ion-exchange resins should operate at                                                                   TM 5-813-8
                  high capacities.
                 -The ion-exchange resins should be               Then, the water travels through a weak base anion
                  regenerated close to the stoichiometric         resin, where the free mineral acidity is adsorbed but the
                  equivalence capacity.                           carbonic acid passes through unaffected. The water is
                 -The acid and base regerants should be           then degasified, which removes the dissolved carbon
                  low cost.                                       dioxide. The weak acid cation and strong acid cation
                 -The waste regenerants should be rinsed          resins are regenerated with either sulfuric or
                  from the ion-exchange resins with a             hydrochloric acid, first through the strong acid cation
                  minimum of water, so that the capacity of       resin and then through the weak acid cation resin. The
                  the resin is not exhausted significantly.       strong base anion and weak base anion resins are
                 -Regenerant waste volumes should be              regenerated in series with sodium bicarbonate, first
                  minimized, and unused regenerants               through the strong base anion resin and then through
                  should be recovered and reused to reduce        the weak base anion resin. The RDI Process is shown
                  the waste disposal volume.                      in figure 8-2.
     b. Limitations. The use of ion exchange in the
desalination of brackish water has several limitations.                d. Three-unit variation. In the three-unit variation,
The volume of water treated is inversely proportional to          the strong acid anions in the water, such as chloride,
the ionic concentration in the water. Regenerant                  sulfate, and nitrate, are replaced with the bicarbonate
consumption per unit volume of treated water is high              ion from a weak base anion resin in the bicarbonate
and becomes higher as the salinity of the brackish water          form. The process then employs a weak acid cation
increases. The size of the ion-exchange equipment                 resin that replaces the calcium, magnesium, and sodium
follows the same rationale-the more saline the water,             in water with the hydrogen ion from the resin. The
the larger the ion-exchange equipment.                            carbonic acid that is formed is adsorbed by a second
A low salinity water, usually product water, is required          weak base anion resin in the free-base form. When the
for regeneration of the ion-exchange resins.                      system has exhausted its treating capability, the lead
     c. Treatment processes. The treatment processes              weak base anion resin is regenerated with ammonia,
employed have either been on a pilot plant scale or               caustic, or lime, the weak acid cation resin is
have been used in a limited number of full-size                   regenerated with sulfuric, hydrochloric, nitric, or
installations. The processes have generally utilized              sulfurous acid, and the tail-end weak base anion is not
weak acid cation and weak base anion resins. These                regenerated. The lead weak base anion resin is now in
resins have higher capacities and require less acid and           the free-base form and the weak acid cation resin in the
base regenerants than strong acid cation and strong               hydrogen form. After its adsorption of carbonic acid in
base anion resins. Two ion-exchange desalination                  the previous service cycle, the tail-end weak base anion
treatments that have been developed are the Desal                 is in the bicarbonate form. The service flow direction is
Process and the RDI Process.                                      reversed for the next service cycle, with the former tail-
          (1) Desal process. The Desal Process has                end weak base anion in the lead position and the former
several variations, but the main thrust of the process is         lead weak base anion in the tail-end position. The
the use of the weak base anion resins in the bicarbonate          direction of service flow is reversed on each succeeding
form.                                                             service cycle after regenerating only the weak acid
          (2) RDI Process. The RDI Process is a three-            cation and the former lead weak base anion. This three-
unit system using four different resins. The water first          unit variation of the Desal Process is shown in figure 8-
passes through a strong base anion resin where the                3, with the following sequence of operation: Service-A
strong acid anions, such as chloride, sulfate, and nitrate,       followed by Regeneration-B, Regeneration-B followed
are replaced with the bicarbonate ion from the resin.             by Service-C, Service-C followed by Regeneration-D,
The water then moves through a layered ion exchange               Regeneration-D followed by Service-A, Service-A
unit of weak acid cation and strong acid cation resins,           followed by Regeneration-B, etc., in a repeating
where the calcium, magnesium, and sodium are                      sequence.
removed, the bicarbonates are converted into carbonic
acid, and the neutral salt leakage from the previous                   e. Two-unit variation. In the two-unit variation,
anion unit is converted into free mineral acidity, i.e.,          carbon dioxide is fed to the raw water. The carbon
sulfuric, hydrochloric, and nitric acids.                         dioxide in the water (carbonic acid) converts the weak
                                                                  base anion resin in the lead unit to the bicarbonate form
                                                                  and the strong acid anions in the water, such as
                                                                  chloride, sulfate, and nitrate, are replaced with the
                                                                  bicarbonate ion from the resin.

                                                             8-3


---

                                                            TM 5-813-8

Figure 8-2. RDI Process.

The process then employs a weak acid cation resin, in       water with the hydrogen ion from the resin. The
the same manner as the three-unit variation, which          carbonic acid or dissolved carbon dioxide that is formed
replaces the calcium, magnesium, and sodium in the          is now removed by a degasifier.

                                                       8-4


---

Ammonia, caustic, or lime can be used to regenerate                                                                  TM 5-813-8
the weak base anion resin and sulfuric, hydrochloric,
nitric, or sulfurous acid can be used to regenerate the  water as pure as does ion exchange. In the production
weak acid cation resin. The two unit variation of the    of steam, it is sometimes necessary to use water with a
Desal Process is shown in figure 8-4.                    lower level of total dissolved solids. Ion exchange
                                                         should be considered if water with less than
8-4. Demineralization. No other demineralization or      approximately 300 milligrams per liter of total dissolved
desalination technique can, in a single pass, produce    solids must be purified further.

Figure 8-3. Three-unit variation Desal Process.
                             8-5


---

                                                               TM 5-813-8

Figure 8-4. Two-unit variation Desal Process.

A typical cation-anion two-bed demineralization flow           removed. For many small users, such as laboratories,
sheet is shown in figure 8-5. The cost of ion-exchange         replaceable mixed-bed ion-exchange cartridges are the
regeneration, including regeneration waste disposal, is        most economical method used to obtain ultrapure water.
directly related to the amount of dissolved solids to be

                                                          8-6


---

                                                                                                                            TM 5-813-8

Figure 8-5. Demineralization two-bed flowsheet.
                              8-7


---

                                                                 TM 5-813-8

     CHAPTER 9
POST-TREATMENT

9-1. General. Desalination can and most often does               The Langelier Corrosion Index can be adjusted to a
produce water so free of dissolved material that                 slightly positive value by pH adjustment. The
corrosion and potential health problems are possible.            adjustment of the distilled water pH should occur
Electrodialysis reversal is an exception to this general         immediately after reaeration, prior to distribution, as
rule. Electrodialysis reversal does not remove                   airborne carbon dioxide may influence the pH.
microorganisms.
9-2. Remineralization and aeration. Pure water is                     d. Residual disinfection. Residual disinfection
a relatively reactive chemical. When air is dissolved in         should be present in the active parts of the distribution
extremely pure water, the resulting solution is extremely        system. A break-point chlorination curve is shown in
corrosive. Water without dissolved air tastes flat and           figure 9-1. Chlorine disinfection of very pure water
objectionable. Water that contains very little hardness          leads to a chlorine residual that is free of combined
appears to be unhealthy for drinking purposes.                   chlorine or chloramines. Chlorination of distilled water
Therefore, the designer of a desalination system must            systems should occur immediately prior to the
consider some posttreatment options, such as                     distribution system. Where it is convenient or
remineralization and aeration, in order to produce a             economical, calcium hypochlorite should be used to
healthful, noncorrosive, pleasant-tasting water.                 control pH to aid in recalcification and to disinfect the
9-3. Post-treatment of distilled water. The mineral              distribution system. Disinfection of Army potable water
content of distilled water is much lower than is                 supplies is discussed in TB MED 229 and TB MED 576.
considered healthy for drinking purposes. Distilled
potable water should be aerated and remineralized for                 e. Reblending for remineralization. One of the
health, taste, and to prevent corrosion. Some                    most cost-effective ways to remineralize distilled water
radionuclides may not be removed by                              is to blend a small stream of pretreated saline feed
distillation/condensation, which may require post-               water back into the distilled product water. When
treatment by ion exchange, prior to all other post-              bacterial contamination is sufficiently low and hardness
treatment methods.                                               is sufficiently high, then reblending is an acceptable
                                                                 means of distilled water remineralization. When
     a. Reaeration. Distilled potable waters will be             reblending is practiced, boiler feed water should be
reaerated before use. Cascade, eductor, or sprayed               removed from the system upstream of the reblend point.
aeration are acceptable but must be followed by                  Saline water used for reblending must have a 30-minute
disinfection to prevent bacterial contamination.                 chlorine contact time. This chlorinated reblend stream
                                                                 is an excellent method of providing the total chlorination
     b. Mineralization. Recent studies have indicated            for the distribution system. As further discussed in
that the hardness of drinking water is important for             Chapter 10, brine can be used to electrolytically produce
human health. The Langelier Corrosion Index was                  hypochlorite ion for disinfection.
developed to predict the tendency of water to deposit or         9-4. Post-treatment of reverse osmosis product
dissolve calcium carbonate. Recalcification of distilled         water. Unlike distilled water, reverse osmosis product
water will be performed in order to reach a positive             water is not necessarily free of dissolved gases. If
Langelier Corrosion Index by adding lime. Fluoridation           degasification is not used as a pretreatment step, the
of Army potable water supplies is discussed in TB MED            dissolved gas content of the reverse osmosis product
576.                                                             stream will be roughly that of the feed stream.
                                                                 Since divalent and trivalent ions are better eliminated by
     c. Corrosion control. Distilled water has a greater         reverse osmosis than are monovalent ions, reverse
corrosion potential once it is aerated.                          osmosis product water is usually very soft and has a
Any boiler feed water should bypass reaeration where             hardness level that is unhealthy when used as drinking
possible. Corrosion should be controlled by the addition         water.
of sodium hexametaphosphate or sodium silicate, in
conjunction with remineralization, prior to entry into the            a. Corrosion control. As a consequence of the
distribution system.                                             dissolved gas content of the reverse osmosis product
                                                                 water, corrosion control should occur as close as is
                                                                 convenient to the suck-back tank.

                                                            9-1


---

                                                            TM 5-813-8

Figure 9-1. Break-point chlorination curve.

A high carbon dioxide content in reverse osmosis            A degasification tower is used to obtain equilibrium with
product water contributes to corrosion. This is true,       atmospheric carbon dioxide. Degasification should
particularly where acid is fed for scale control.           occur after remineralization. Boiler feed water or wash
                                                            water should be drawn off prior to corrosion control.

                                                       9-2


---

                                                                                                         TM 5-813-8

To control corrosion of reverse osmosis product water,         control. If this is feasible, suspended solids control will

add sodium silicate or sodium hexametaphosphate.               be a post-treatment process at the electrodialysis-

Corrosion control is affected by recalcification and           reversal facility. When it is impossible to centralize all

Langelier Corrosion Index adjustment.                          turbidity control, and electrodialysis reversal is still

b. Reverse         osmosis             remineralization.       shown to be economical, both pretreatment and post-

Occasionally, remineralization of reverse osmosis              treatment suspended solids control shall be designed.

product water is not necessary. Since reverse osmosis          At high-current densities, electrodialysis reversal will

increases the monovalent-to-divalent ion ratio,                soften water by the selective removal of multivalent

remineralization is usually advisable.         This            ions. At low-current densities, electrodialysis reversal

remineralization, will contribute to the production of a       can be used to selectively remove monovalent ions.

pleasant tasting and healthful product water.                  This selective removal of monovalent ions at low-

c. Residual disinfection. The use of calcium                   current densities can be economical for fluoride or other

hypochlorite for disinfection will assist in                   exotic ion removal or control where total dissolved

remineralization.                                              solids and other ions are not a problem.

d. Reblending. Reblending of pretreated saline                 b. Remineralization.  Remineralization of

water is an acceptable remineralization procedure for          electrodialysis-reversal product water is seldom

reverse osmosis product water as long as the hardness          necessary. When recalcification is deemed desirable, it

of the reblend can be shown to be healthful. All               is generally best to make provisions for adding calcium

reblended water must receive a full 30-minute chlorine         carbonate.

contact time.                                                  c. Residual disinfection. Disinfection chlorination

9-5. Post-treatment of electrodialysis-reversal                of electrodialysis-reversal product water should occur as

product water. Electrodialysis reversal does not               soon as possible after electrodialysis-reversal

remove small suspended material. The pretreatment for          desalination. Electrodialysis reversal will remove most

electrodialysis reversal should remove any material that       of the free available chlorine used in any pretreatment

will plug a 10-micron filter. Loosened scale and               chlorination. Electrodialysis reversal can lead to a

particulate matter may require postdesalination removal.       greater concentration of bacteria in the product water

Micro-organisms are not removed by electrodialysis             than was present in the feed stream due to osmotic loss

reversal.                                                      of water to the waste brine stream. Chlorination of all

a. Suspended solids removal. Suspended solids                  electrodialysis reversal waters will include a 30-minute

removal during pretreatment is the preferred design for        chlorine contact time after treatment. Pretreatment

electrodialysis-reversal facilities. Pretreatment of           chlorination will not be included as part of the 30-minute

suspended solids removes particulates, including micro-        contact time. The operation and design of electrolytic

organisms, which are prone to blind electrodialysis-           hypochlorite production equipment, as listed in Chapter

reversal membranes. This removal reduces the time              10, is similar to the electrodialysis process. This can

between cleanings. When electrodialysis-reversal               make electrolytic production an operational and strategic

product water turbidity cannot be controlled                   advantage for electrodialysis-reversal desalination

economically by pretreatment, then an attempt will be          facilities.

made to eliminate all pretreatment suspended solids

                                                          9-3


---

                                                        TM 5-813-8

    CHAPTER 10
WASTE DISPOSAL

10-1. General. Wastes from desalination systems         A waste disposal overview is shown in figure 10-1. The
include solids, liquids, and gases. Evaluate each       designer shall also refer to TM's 5-813-3 and 5-813-7 for
desalination system to determine its particular waste   additional guidance.
products, then use the appropriate systems to treat or
contain these wastes.

Figure 10-1. Waste disposal overview.
                       10-1


---

10-2. Pretreatment wastes. Systems that require                                                                      TM 5-813-8
pretreatment processes produce pretreatment wastes.
Solid materials, and the chemicals added to precipitate  or press operations, or evaporative, which are solar
them, form floc that will be removed from raw water by   beds or lagoon operations. The alternatives for
clarification. The sludges formed must undergo           pretreatment sludge disposal are shown in figure 10-2.
dewatering and are sent to a landfill. Dewatering        In addition to solid wastes, pretreatment processes can
processes can be mechanical, which are centrifugation    produce liquid wastes from filter backwash operations.
                                                         These liquid wastes often can be reclaimed or treated
                                                         along with other liquid wastes from desalination process.

Figure 10-2. Pretreatment sludge disposal.
                         10-2


---

10-3. Distillation / condensation system wastes .                                                                              TM 5-813-8

The waste stream volume produced by                                The area must be checked for geologic faults and any
                                                                   manmade penetrations of the aquiclude. The brine
distillation/condensation systems is usually less than             must contain less than 15 milligrams per liter of
                                                                   suspended solids, with a maximum size of 20 microns.
that produced by other desalination processes. The                 Figure 10-3 shows a typical injection well. High
                                                                   construction and operating costs and the potential for
vaporization process yields concentrated brine with a              serious operational problems usually cause deep-well
                                                                   injection to be the last process selected. If deep-well
reduced liquid waste loading. The use of less extensive            injection, evaporation, or return-to-source liquid-disposal
                                                                   options are not possible, review the entire facility
pretreatment requirements for these systems generally              location.

results in a reduction of solid wastes. The cooling water               d. Dried salts. When evaporation processes have
                                                                   reduced the brines to dry salts, make evaluations to
discharge produced by many distillation processes does             determine a market value for these salts, as some salts
                                                                   have a value when dried. A landfill operation must be
present a separate thermal discharge problem.                      maintained when no market value can be assigned to
                                                                   the dried salts. An overview of brine wastes disposal is
a. Brine return to source. The brines from                         shown in figure 10-4.

distillation/condensation processes are highly                          e. Use of brine. Desalination evaporation ponds
                                                                   make excellent solar stratification ponds. These ponds
concentrated. For this reason, brines will be discharged           can be used to produce a stored thermal energy
                                                                   gradient, which can be harvested with a Rankin cycle
where contamination of the intake water will not occur.            engine. Electricity from such a system can be used to
                                                                   electrolytically produce chlorine. The total disposal of
The liquid brines will be returned to the raw water source         brine by chlorine production is not expected to ever be
                                                                   economical for the military. The internal production of
if impact studies show there will be no significant                chlorine for water disinfection is strategic. Presently, the
                                                                   smallest systems available produce over 22 pounds of
environmental impact. Wetlands and estuarian areas                 chlorine per day. The brine concentration must be
                                                                   greater than above 35,000 milligrams of total dissolved
that are often used for discharge are usually productive           solids to be practical. Any hardness in the brine limits
                                                                   efficiency and causes scaling.
growth sites for many valuable food species. These
                                                                        f. Cleaning wastes. At regular intervals,
areas are easily damaged by thermal discharges and                 distillation systems must be cleaned. This usually
                                                                   involves strong acid cleaning solutions. These solutions
require study to ensure that they are acceptable disposal          must be neutralized and may require lime precipitation
                                                                   of heavy metals before they can be discharged. These
areas for concentrated desalination waste liquids.                 wastes can be dried in evaporation ponds or disposed of
                                                                   in injection wells. The volume of cleaning waste is small
b. Brine evaporation. If it is not feasible to return              enough that transportation of the cleaning wastes to
                                                                   commercial hazardous waste disposal facilities is a third
the brines to the raw water source, then consider the use          alternative. The operation of pretreatment scale control
                                                                   can reduce the frequency of cleaning.
of evaporation ponds to dry the liquid wastes. The
                                                                        g. Gases. Gas wastes from desalination
thermal nature of the brine from most                              processes are removed from the system during
                                                                   deaeration or distillation. These gases include
distillation/condensation systems can aid evaporation of

the wastes to dry salts. In areas where the net

evaporation rate is low, but thermal energy sources are

available, use thermal evaporation.            Thermal

evaporation has high energy requirements and usually is

not cost-effective.

c. Brine deep-well injection. If discharging the

brine to a surface water or evaporation is impractical or

uneconomical, deep-well injection of brines is possible.

The injection of liquid wastes to deep underground

formations can provide a disposal alternative where

none was previously available. To properly design and

install a deep-well injection facility, a complete geologic

and geochemical analysis of the reservoir formation is

required. Volumes of less than 53 gallons per minute

can be disposed of practically in injection wells, while

volumes in excess of 264 gallons per minute will be

much more difficult to dispose of by use of this method.

Compatibility tests must be run between the proposed

waste and a sample of the formation water. This test

should ensure that the two waters do not react to form

precipitates that may clog the receiving formation. The

receiving formation must be separated from any fresh

water or the desalination source water by an aquiclude

that will ensure that the brine will not contaminate them.

                                                             10-3


---

                                                                                          TM 5-813-8

Figure 10-3. Deep-well disposal unit.
                     10-4


---

                                                                          TM 5-813-8

Source U. S. Army Corps of Engineers

                                      Figure 10-4. Brine waste disposal.

carbon dioxide, nitrogen, and oxygen and require no             10-4. Membrane system wastes.
special disposal or monitoring facilities. When hydrogen        Membrane desalination systems are the most efficient
sulfide gas is removed from raw feed water or toxic and         potable water procedures. However, they produce the
explosive gasses such as methane are generated in               most pretreatment wastes, a less concentrated brine
waste treatment process, special precautions must be            waste, and spent membrane modules.
taken for its safe discharge.
                                                                      a. Brines. Brines produced from membrane

                                                          10-5


---

                                                                   TM 5-813-8

desalination are usually less concentrated and are at a            10-5. Ion-exchange system wastes.
lower temperature than distillation/ condensation system           Neutralize the acid and caustic solutions from ion-
brines. The concentration and temperature of these                 exchange regeneration. Then dispose of wastes as
membrane brines make them ideal for disposal by                    concentrated brines. The only other major waste product
return-to-source technology if it is approved by regulatory        from ion-exchange systems is the ion-exchange bed
authorities. Other methods, such as evaporation or                 itself. Resins that are spent and not to be regenerated
injection, can be used.                                            can be placed in a landfill.

      b. Membrane modules. Membranes can become                    10-6. Ultimate disposal. All waste streams from
fouled, compacted, or destroyed during the normal                  desalination processes must reach a point of ultimate or
course of membrane desalination operation. None of the             final disposal. Without adequate waste disposal
membrane systems in current use present health or                  facilities, site development cannot continue.
environmental hazards when disposed in a landfill. It is
customary for the membrane manufacturers to dispose
of defective membranes and their modules when
replacement is necessary.

                                                             10-6


---

      APPENDIX A
SAMPLE PROBLEMS


---

                  TM 5-813-8

      APPENDIX A
SAMPLE PROBLEMS

A-1. Sample source and process selection. A facility has been proposed near El Paso, Texas. The final facility population
is set at 100 full-time resident personnel. Use TM 5813-1 to obtain water consumption per day. The calculation is as
follows:

                                                      100 Persons X 150 gallons X (Capacity)
                                                                             day Person (Factor)

The nearest flowing river is the Rio Grande, which is 100 miles from the proposed site. Surface water in shallow lakes is
also available. Investigations at one location indicate that the lake is much saltier than seawater. A groundwater literature
review indicates that several brackish water aquifiers exist in the area.
The assumed site data are summarized below:

      1-Surface lake water is more saline than sea water.
      2-River water is more than 100 miles away.
      3-Available brackish water is only slightly saline.
      4-Solar energy is available.
      5-Pond evaporation of brine would be about 0.7 multiplied by net pan evaporation (86 inches per year) = 60 inches

         per year.
      6-Power lines are remote. A natural gas supply is available at the proposed site. Electricity for the facility could be

         produced by natural gas engines.
Saline Lake Water
The use of table 4-1 indicates that Rule 1 will apply to this water source (see fig. A-1, Sample use of table 4-1).
Rule 1 states that water saltier than sea water is probably not economical for desalination. A total dissolved solids

      determination should be run on the lake water to verify excessive salinity.
Assume that the laboratory analyses recommended in table 4-1 were performed and the following was obtained:

                                                                      Saline lake water
                                                 Total dissolved solids 70,000 milligrams per liter

Now use table 4-2 where Rule 1 is applicable. Rule 1 states that if this water must be used, thermal distillation is the only
possible process. (See fig. A-2, Sample use of table 4-2). Since alternate brackish water sources are available, this
water source is rejected.
Brackish Groundwater

      The use of table 4-1 indicates that Rule 6 or Rule 7 will apply to this water source (see fig. A-1).
      Rule 6 states that the most economical method to obtain drinking water from brackish water is through reverse
osmosis, regardless of how electricity is to be generated. Analyses of total dissolved solids, calcium, sulfate, carbonate,
pH, bacterial count, silt density index, turbidity, and low-level oil and grease (less than 1 milligram per liter), as well as the
other tests called for in Appendix B, should be performed on test-well water sample.
      Rule 7 states that electrodialysis reversal should be investigated for slightly saline water, regardless of electric or
steam costs. A total dissolved solids determination, full ionic breakdown, bacterial count, turbidity, and the other tests
listed in Appendix B should be done on these test-well samples.
      In one area of the site assume that a 230-foot-deep test well is drilled and that the laboratory analyses recommended
in table 4-1, Rule 6, were performed and the following data shown in figure A-3 were obtained:
      The following data were extracted from the laboratory analysis and bacterial plate count:

             230-foot-deep well
             total dissolved solids 5,000 milligrams per liter
             Ca+ + 150 milligrams per liter
             SO 4 = 300 milligrams per liter
             CO 3 = milligrams per liter
             HCO 3 172 milligrams per liter

                                                                               A-1


---

                                                   TM 5-813-8
                                     Appendix B

                                           Appendix B
                                           Appendix B

Figure A-1. Sample use of table 4-1
                     A-2


---

                                                                                                                      TM 5-813-8

Figure A-2. Sample use of table 4-2.
                      A-3


---

                                                                                                    TM 5-813-8

Figure A-3. Water analysis (sample problem A-1a).
                                A-4


---

                                                                                                                      TM 5-813-8

Figure A-4. Sample use of table 4-3.
                      A-5


---

                                                                                            TM 5-813-8

pH 8.5
Bacterial count 0/100 milliter (membrane filter technique)
Silt density index 1
Turbidity less than 0.01 nephelometric turbidity unit
Oil and grease less than 1 milligrams per liter

      In table 4-2, Rule 7 is applicable (see fig. A-2). Rule 7 states that reverse osmosis processes should be investigated.
The low level of silt density index precludes the necessity of an alum jar test.

      Use table 4-3 showing that Rule 8 applies (see fig. A-4). Rule 8 states that hollow fine-fiber reverse osmosis
specifications should be prepared. No specific pretreatment process is necessary.

      In another area of the site a 500-foot test well was drilled. The driller’s report indicated that this water had a slight
saline taste. Table 4-1, Rule 7 applies (see fig. A-1).

      Rule 7 states that electrodialysis reversal should be investigated for slightly saline water, regard- less of electric or
steam costs. The recommended laboratory analyses are: total dissolved solids, a full ionic breakdown, bacterial count,
turbidity, and the other tests for electrodialysis-reversal feed waters listed in Appendix B.

      Assume that the laboratory analyses of this water sample give the following data shown in figure A-5.

The following data were extracted from the laboratory analysis and bacterial plate counts:
      500-foot-deep well
      total dissolved solids 1,000 milligrams per liter
      Ca+ + 100 milligrams per liter as CaCO3
      Mg + + 7 milligrams per liter
      SO 4 = 240 milligrams per liter
      CO 3 = 0 milligrams per liter
      HCO 3- 21 milligrams per liter
      Cl- 389 milligrams per liter
      Na+ 326 milligrams per liter
      Bacterial count 0/100 milliliter (membrane filter technique)
      Turbidity less than 0.01 nephelometric turbidity unit

      Table 4-2, Rule 8 applies (see fig. A-2). Rule 8 states that electrodialysis reversal should be investigated. The low
level of turbidity precludes the use of an alum jar test. The low salinity of this sample indicates this to be a superior quality
brackish water source.

      Application of the preliminary process selection information with table 4-3 results in two possible final process
selections. Both Rule 9 and Rule 10 are applicable to this water source. (See fig. A-4)

      Rule 9 states that low-pressure high-rate reverse osmosis specifications should be prepared, with antiscalants to be
recommended.

      Rule 10 states that electrodialysis-reversal specifications should be prepared.
      A final decision should be based on the probability of the total dissolved solids fluctuating by more than approximately
15 percent.
      Assume a fourth water source was also investigated at this same site. A shallow 32-foot test well was drilled. A
preliminary inspection indicated this water was slightly saline and foul tasting with a strong rotten egg smell.
      Use of table 4-1 indicates that Rule 6 and Rule 7 may apply (see fig. A-1). Rule 6 states that the most economical
method to obtain drinking water from brackish water is through reverse osmosis, regardless of how electricity is to be
generated. Analyses of total dissolved solids, calcium, sulfate, carbonate, pH, bacterial count, silt density index, turbidity,
low-level oil and grease (below 1 milligram per liter), and any other tests called for in Appendix B should be performed on
test-well water samples.
      Rule 7 states that for slightly saline water electrodialysis reversal is the most economical method to obtain potable
water from brackish water. Analysis of total dissolved solids, a full ionic breakdown, bacterial count, turbidity, and any
other tests called for in Appendix B should be performed.
      The laboratory analyses of this water sample give the following data shown in figure A-6:

A-6


---

                                                   TM 5-813-8

PHYSICAL AND CHEMICAL ANALYSIS OF WATER

Figure A-5. Water analysis (sample problem A-1b).
                                A-7


---

                                                   TM 5-813-8

PHYSICAL AND CHEMICAL ANALYSIS OF WATER

Figure A-6. Water analysis (sample problem A-1c).
                                A-8


---

                                                                                                                                                    TM 5-813-8

                                                         Figure A-7. Low Pressure Reverse Osmosis System.
                          Source: The Permuttit Co., Inc.
The following data were extracted from laboratory analysis and bacterial plate counts:
      32-foot-deep well
      total dissolved solids 4,000 milligrams per liter
      Ca+ + 50 milligrams per liter as CaCO3
      Mg+ + 64 milligrams per liter
      SO 4 = 1,000’nilligrams per liter

                                                                               A-9


---

CO 3 = absent due to pH                                                                                   TM 5-813-8

pH 3.5

Bacterial count 50,000/100 milliliters (sulfide media, not a coliform test)

Silt density index 6.67 (Complete plugging in 2 minutes)

Turbidity 115 nephelometric turbidity unit (Total Suspended Solids 250 milligrams per liter)

Oil and grease 100 milligrams per liter

Use of these laboratory analyses with table 4-2 indicates that Rule 8 applies (see table A-2). Rule 8 states that

electrodialysis reversal should be investigated. The elevated bacterial count indicates the possible contamination of the

source with sewage effluent. This possible contamination should be investigated.

Assume that a bacteriological examination of a water sample indicated that the bacteria present are sulfur oxidizing

bacteria, responsible for the low pH of the sample. The bacterial count may not reflect the true level of bacteria in the

source, since aeration of the sample stimulates bacterial growth in the presence of the sulfide. Although no sewage

effluent contamination is detected, potential taste and odor problems with this water source are severe.

Use of table 4-3 results in three possible final process selections. Rule 7, Rule 8, and Rule 9 are all applicable for this

water source (see fig. A-4).

Rule 7 states that if water is below 1 nephelometric turbidity unit and has a silt density index above 4, specifications

for spiral-wound reverse osmosis processes should be prepared.

Rule 8 states that if water is clear and has a silt density index of less than 4, specifications for hollow fine-fiber

reverse osmosis processes should be prepared.

Rule 9 states that electrodialysis reversal specifications should be prepared. While no individual rule fits completely,

Rule 9 appears to be the most applicable. As this last example demonstrates, these tables are not intended to supplant

sound engineering judgment. They do not include all possible waters or conditions found in the continental United States.

Of the four water sources considered in this sample problem, the low salinity and turbidity of the 500-foot-deep well

would indicate that it would be the most economical water source for development. The other three sources should be

rejected. A drawing of a reverse osmosis system similar to that which would be used in treating such a well water is

shown in Figure A-7.

A-2. Sample source and process selection. A facility is planned for the California coast in an area not currently served

by an electric utility. Fresh surface water and groundwater do not exist or are unavailable in the area. The only water

source is sea water. The facility will have 3,000 permanent personnel. Natural gas is available. Use TM 5-813-1 to

determine daily water consumption. The calculation follows:

                              3,000 Persons x 150 gallons x 1.5 (Capacity)

                                               day person       (Factor)

Daily water consumption = 675,000 gallons per day

      The area is reasonably arid with a mean summer temperature greater than 59 degrees Fahrenheit and a mean winter
temperature greater than about 48 degrees Fahrenheit (see TM 5-813-1, figs. 2-5 and 2-7). Brine disposal at sea is
feasible. It is estimated that electricity would cost more than $.50/kilowatt hour if the facility could install a power
transmission line. A natural gas-powered internal combustion engine could produce power for approximately $.60/kilowatt
hour.
Summarize this data as shown below:

             1-No fresh surface water or fresh ground water are available in the area.
             2-The site is on the Pacific Ocean and sea water is available.
             3-Solar energy is available.
             4-Brine disposal at sea is feasible.
             5-Power lines are remote. A natural gas supply is available for electricity generation by internal combustion

                engine.
      Use of table 4-1 with the above data indicates that Rule 4 will apply to a sea water source (see fig. A-8).

                                                   A-10


---

                                                    TM 5-813-8
                                      Appendix B

                                            Appendix B
                                            Appendix B

Figure A-8. Sample use of table 4-1.
                     A-11


---

                                                                                                                                                    TM 5-813-8

      Rule 4 states that when sea water is used and internal combustion engines are being considered for power
production, vapor-compression distillation should be considered. Laboratory analyses of the sea water should include total
dissolved solids, bacterial count, and turbidity. An evaluation of possible waste heat recovery from the power generation
system should also be undertaken.

      Assume the results from the laboratory analyses recommended in table 4-1, shown in figure A-9, are as follows (the
format for the Physical and Chemical Analysis of Water used in this manual is for illustration purposes only and users are
advised to develop their own format): The following data were extracted from the laboratory analysis and bacterial plate
counts:

             Seawater
             TDS 35,000 milligrams per liter
             Ca + + 350 milligrams per liter as Ca+ +
             SO 4 = 2,650 milligrams per liter
             pH 7.2
             Bacterial count 10/100 milliliters (membrane filter technique)
             Turbidity 15 nephelometric turbidity units
      Assume that the following was obtained from analysis of the design of the internal combusion engine to be used for
power production.
      Waste heat: Approximately 1.0 x 109 British thermal units per day between 264 degrees Fahrenheit and 68 degrees
Fahrenheit.
      Calculating the cost of electricity from the power utility $.50/kilowatt hour versus the cost of waste heat steam which
can be produced at less than $0.03/1.0 x 106 British thermal units gives the following:
             $0.50/kilowatt hour/$0.03/1.0 x 106 British thermal unit = 16.67 x 106 British thermal unit per kilowatt hour
      Use of this information and table 4-2 indicates that Rule 3 is applicable for this facility (see fig. A-10). Steam and
electricity costs are compared as a ratio to eliminate dollar value changes, but technology could easily change the 10.0 x
106 British thermal unit per kilowatt hour guideline. Rule 3 states that a comparison between reverse osmosis and
distillation/condensation systems should be made. Additional testing should include an alum jar test and 10-micron filter
plugging, as well as evaluation of the effects of ultraviolet (UV) sterilizations.
      Assume that the results from the recommended testing indicate that the turbidity can be reduced by alum addition to
below 1 nephelometric turbidity unit, and a 10-micron filter will not plug rapidly on this treated water. Assume that a
computer analysis in addition to figure 3-2, TM 5-813-1, shows scaling is not a problem until the total dissolved solids is
concentrated about 1.5 times at temperatures below 212 degrees Fahrenheit.
Use of table 4-3 indicates that Rule 3 applies for this facility (see fig. A-11).
Rule 5 states that if temperature over 212 degrees Fahrenheit are economical for distillation at
this site, acid feed may be necessary to prevent scaling.
A distillation/condensation system with an associated vapor-compression system should be evaluated. Specifications
should be prepared. A drawing of a sea water distillation system capable of recompressing low-grade steam is shown in
figure A-12.

A-3. Calcium sulfate solubility product (Ca S04 · XH2O) scale. As can be seen below, the calculation of a solubility limit
is moderately complex for a simple, pure solute at low concentration. Hand calculation is not practical in solutions
containing a few percent of several cationic and/or several anionic species. Most manufacturers have computer programs
that include the concentration polarization factors and any other surface-related factors that set the scaling limits for their
products. The following is a sample calculation of calcium ion sulfate ion, acid-base solubility for 64 degrees Fahrenheit.
To estimate solubilities for distillation condensation or other temperatures different from 64 degrees Fahrenheit, the
solubility product for calcium sulfate at temperatures up to 392 degrees Fahrenheit can be found in reference (4).

      These calculations are suitable for initial design and process selection (see tables 4-2 and 4-3). The principle
purpose of these calculations is to indicate waters that are well below saturation and therefore do not present scaling
problems. A full computer evaluation of scaling potential should be performed by the manufacturer as part of the final bid.

                                                                              A-12


---

                                                  TM 5-813-8

PHYSICAL AND CHEMICAL ANALYSIS OF WATER

Figure A-9. Water analysis (sample problem A-2).
                              A-13


---

                                                                                                                       TM 5-813-8

Figure A-10. Sample use of table 4-2.
                      A-14


---

                                                                                                                       TM 5-813-8

Figure A-11. Sample use of table 4-3.
                      A-15


---

                   TM 5-813-8

Symbols:                            Figure A-12. Plan view of a vapor compression system.
      [Ca + +] =
      [SO 4 = =    Double-ionized calcium concentration in moles/liter (molar)
      [HSO 4- ] =  Double-ionized sulfate concentration in moles/liter (molar)
      [H+] =       Undissociated bisulfate ion concentration in moles/liter (molar)
                   The dissociated hydrogen ion concentration in moles/liter (molar)
pKsp  =            The negative base 10 logarithm of the solubility product
                   The product of the concentration of the ions in a saturated solution that is beginning to form crystals
Ksp   =            The negative base 10 logarithm of the hydrogen ion concentration
                   The negative base 10 logarithm of the hydroxyl ion concentration
pH    =            The negative base 10 logarithm of the acid dissociation constant
                   The ratio of the concentration of dissociated acid and hydrogen ion concentration to the undissociated
pOH =               acid concentration at equilibrium

pKa   =                                                                A-16

Ka =


---

                                                                                       TM 5-813-8

Assume that:                                                    =

The water contains 1,000 parts per million as CaCO3, 2,650 parts per million SO4 as total sulfate and is at pOH =

11. Assume that the temperature is close to 64 degrees Fahrenheit and that there is no ion pairing of SO4 other

than hydrogen ion as HSO4.

The pKsp of calcium sulfate is given as 3.6.

The pKa of sulfuric acid second dissociation is given as 1.92.

The density of the saline water sample is 1,025 grams/liter at 64 degrees Fahrenheit.

    To convert calcium and sulfate concentrations in the expected brine (density = 1025 grams/liter) to molarity use the
following calculations:

∴ Unless other ions complex Ca++ or SO4, scaling will be a problem at 64 degrees Fahrenheit. (See figure 5-2.)

A-4. Ion- exchange desalination. Apermanent installation is proposed near Haftrak,
Arizona. The potable weater treatment system will serve a resident population of 2,000. Use TM 5-813-1 to obtain water
consumption per day. The calculation is as follows:

                                           150 gallons
                     2,000 persons x day Person x 1.5 capacity factor = 450,000 gallons per day

    The area is hot and dry, with annual average maximum daily air temperature of 55 degrees Fahrenheit and a net pan
evaporation of approximately 87 inches. Ground water is available, as well as an average chemical analysis.

                                                                              A-17


---

                                                   TM 5-813-8

PHYSICAL AND CHEMICAL ANALYSIS OF WATER

Figure A-13. Water analysis (sample problem A-4).
                               A-18


---

                                                                                                                                                    TM 5-813-8
The assumed site data are summarized below:

             1-Available ground water is a consideration.
             2-Ion exchange will be considered for the potable water treatment.
             3-Pond evaporation of regenerate wastes would be approximately 0.7, multiplied by net pan evaporation (87

                inches per year), which equals 508 inches per year.

Ground Water

Laboratory analyses are available, and the following water quality data are shown in figure A-13.

Ion-Exchange Resin Selection

On the physical and chemical analysis of water report (fig. A-13), the following data were extracted:

Total dissolved solids 800 milligrams per liter

      Sulfate         77 milligrams per liter

      Chloride        107 milligrams per liter

      Nitrate         9 milligrams per liter

      Iron            0.01 milligrams per liter

      Manganese       0.01 milligrams per liter

      Fluoride        2.0 milligrams per liter

In comparing the extracted data with the potable water maximum contaminant levels found in Army Medical Corps

documents, total dissolved solids is the only limit exceeded.

The choice of the proper ion-exchange method depends on the composition of the raw water and its intended use. A

strongly acidic cation exchange resin replaces the cations in the raw water with hydrogen, and the effluent from the

exchanger unit is both softened and acidic. Since sodium is the most predominant cationic ion in the well water, a

reduction of sodium and associated alkalinity will reduce the total dissolved solids to within the potable water limits.

Therefore, a strongly acidic cation exchange resin system is indicated. No specific pretreatment process is necessary.

Neutralization

A strongly acidic cation exchange system converts carbonate and bicarbonate alkalinity to carbonic acid, which breaks

down to carbon dioxide and water. Then, the carbon dioxide may be removed by air stripping in a degasification tower.

After degasification, a percentage of the raw well water containing alkalinity may be blended to obtain the desired 500

milligrams per liter of total dissolved solids.

Ion-Exchange Engineering Data

Since total dissolved solids only need to be reduced approximately 40 percent, consider low acid regeneration levels.

Regeneration levels of 5 and 3 pounds per cubic foot will be considered. Leakage can be estimated from vendor data

such as figure A-14.

With a 5-pound H2S04 (66 degrees Be)/cubic foot regeneration level, the average sodium leakage equals 60.5 parts

per million as CaCO3. The capacity of the ion-exchange resin can be found in figure A-15.

With a 5-pound H2S04 (66 degrees Be)/cubic foot regeneration level, the book capacity = 15.1 kilograins/cubic foot.

The alkalinity correction factor can be found in figure A-16.

      At 56 percent, the alkalinity correction factor is 1.125

      The corrected capacity = 17.0 kilograins/cubic foot.

Then

      Use equipment factor = 0.8
      ... Design Capacity = 13.6 kilograins/cubic foot.

      With a 3-pound H2SO4 (66 degrees Be)/cubic foot regeneration level, the average sodium leakage = 104.5 parts

per million as CaCO3. Leakage can be estimated from vendor data such as figure A-17.

      With a 3-pound H2S04 (66 degrees Be)/cubic foot regeneration level, the book capacity = 11.0 kilograins/cubic

foot. The capacity of the ion-exchange resin can be found in figure A-18.

                                                               A-19


---

                                                                                                                                TM 5-813-8

Figure A-14. Amberlite IR-120 plus leakage data regeneration-5 Ibs. H2SO4 (66° Be)/cu. ft.
                                                          A-20


---

                                                                                                                                                    TM 5-813-8
                                                                                                                      BOOK CAPACITY = 15.1 KGR/Ft3

Source Rohm and Haas Co
                  Figure A-15. Amberlite IR-120 plus iso-capacity data regeneration-5 Ibs. H2S04 (66° Be)/cu. ft.

      With a 5-pound H2SO4 (66 degrees Be)/cubic foot regeneration level, the book capacity = 15.1 kilograins/cubic foot.
The alkalinity correction factor can be found in figure A-19.
Then

      The corrected capacity = 12.4 kilograins/cubic foot.
Then

      Use equipment factor = 0.8.
      ... Design Capacity = 9.9 kilograins/cubic foot.
Water Analyses Summary
Table A-1 is a summary of the average water constituents at different stages in the ion-exchange treatment process.

                                                                              A-21


---

                                                                                                                                                    TM 5-813-8
                                                                                       @ 56% ALK = 15.1 X 1.125 = 17.0 KGR/Ft 3
                                                                                       USE 0.8 EQUIPMENT FACTOR
                                                                                       17.0 x 0.8 = 13.6 KGR/Ft 3
                                                                                       DESIGN CAPACITY

                                   Figure A-16. Amberlite IR-120 plus capacity correction for alkalinity.
      When using 5-pound H2S04 (66 degrees Be) per cubic foot regeneration, the cation exchanger effluent will have
approximately zero calcium and magnesium, with a sodium leakage of 61 parts per million as indicated on Figure A-14.
The remaining cations are hydrogen as indicated.
      The anions are not affected, with the exception of alkalinity, which is converted to carbon dioxide and water.
      The next step in the treatment is blending sufficient raw water to neutralize the hydrogen ions in the cation effluent.

                                                                              A-22


---

                                                                                                                               TM 5-813-8

Figure A-17. Amberlite IR-120 plus leakage data regeneration-3 lbs. H2SO4 (66° Be)/cu. ft.
                                                         A-23


---

                                                                                              TM 5-813-8
                                                                BOOK CAPACITY = 11.0 KGR/Ft3

         Figure A-18. Amberlite IR-120 plus iso-capacity data regeneration-3 lbs. H2S04 (66° Be)/cu. ft.

Neutralized Blend (N.B.)
      181 parts per million hydrogen as CaCO3
                                                                = 0.59 Volume Ratio
      308 parts per million alkalinity as CaCO3

Or
      Per unit volume of cation effluent, 0.59 volume of raw water is required to neutralize the hydrogen ions.

0.59 =.37 x 100 = 37 percent of neutralized blend is raw water

1.59

Raw Water = R.W.

Neutral Blend = N.B.

Potable  = P

                      A-24


---

                                                                       TM 5-813-8
                             @ 56% ALK = 11.0 x 1.125 = 12.4 KGR/Ft3

                  Figure A-19. Amberlite IR-120 plus capacity correction for alkalinity.

100x = percent of R.W. in P
    P - N.B.

x=
    R.W. - N.B.

   500 - 303 197

=  = =0.396

   800 - 303 497

100x = 0.396
     x = 39.6 percent R.W. in P.

100x(1 - .396) = 60.4 percent N.B. in P.
      The blended potable water has a Langelier Index of + 0.65, which produces a slight scaling tendency for distribution

system corrosion protection.
                                                                              A-25


---

                                                                                                                                    TM 5-813-8

Table A-1. Water Constituents at Treatment Stages with 5 Pounds/Cubic Foot Acid Regeneration.
                                                              A-26


---

                                                                                                                                                    TM 5-813-8

               Table A-2. Water Constitutes at Treatment Stages with 3 Pounds/Cubic Foot Sulfuric Acid Regeneration
Source U S Army Corps of Engineers

      Table A-2 is a summary of the average constituents at different stages in the ion-exchange treatment process.
      When using 3-pounds H2S04 (66 degrees Be) per cubic foot regeneration, the cation exchange effluent will have
approximately zero calcium and magnesium, with a sodium leakage of 104.5 parts

                                                                              A-27


---

                                                                                               TM 5-813-8

per million as indicated on figure A-17. The remaining cations are hydrogen as indicated.
      After degasification of the neutral blend, the carbon dioxide is 10 parts per million based on the degasifier design.

Raw water is again blended after degasification to achieve a 500 milligram per liter of total dissolved solids product.
Neutralized Blend (N.B.)

      137.5 parts per million hydrogen as CaCO3 0.45 volume ratio
      308 parts per million alkalinity as CaCO3
Or
      0.45 Volume
      1.45 Volume = 0.32 x 100 = 32 percent of neutralized blend is raw water

      Two-step blending is considered to take advantage of the carbonate in the raw water, which will neutralize the
remaining carbon dioxide and reduce potential corrosion in the distribution system.

Blend of Well Water and Neutral Degased Water

R.W. = 800 milligrams per liter of Total Dissolved Solids
N.B. = 302 milligrams per liter of Total Dissolved Solids
P = 500 milligrams per liter of Total Dissolved Solids
100x = Percent of R.W. in P

      P - N.B.
= R.W. - N.B.

      500 - 302
x= 800 - 302 = 0.398
100x = 0.398
x = 39.8 R.W. in P
100x (1 - .398) = 60.2 percent of N.B. in P

      The blended potable water has a Langelier Index of +0.54, which indicates a slight scaling tendency for the
distribution system corrosion protection.
Chemical Requirements

      3 pounds/cubic foot regeneration level
      ... In 1,000 gallons of potable water

                   398 gallons of raw water to 500 total milligrams per liter of dissolved solids
             + (1,000 - 398) x .32 = 193 gallons to neutralize
Or
      398 + 193 = 591 gallons of raw water and 409 gallons of cation effluent
So
      40.9 percent of potable water is treated with the cation exchanger.
Acid Usage
Cation Regeneration Efficiency

50 grains CaCO3 x (3 pounds/cubic feet) (.93 pounds acid/pounds) (7 kilograins/pounds) = 2.01

49 grains H2S04  9.9 kilograins/cubic feet

                 or 200-percent stoichiometric

                                               A-28


---

                                                                                            TM 5-813-8

Cations Removed Per Gallons of Potable Water

(409 gallons) x  488 parts per million - 104.5 parts per million x 1 pound
 kilogallon            17.1 parts per million/grains/gallon        7000 grains

               = 1.31 pounds as CaCO3
                 1000 gallons potable water

At 200-percent regeneration efficiency:

Acid Required = 2.0 x   1.31 pounds as CaCO3                   49 equivalent weight acid
                       kilogallons potable water             50 equivalent weight CaCO3

               x 1 pound H2S04
                  .995 percent H2S04

               = 2.58 pounds 99.5 percent H2SO4 per 1000 gallons potable water

Waste Acid

(2.0 - 1.0)1.29        pounds acid                x 1.29 pounds 99.5 percent H2S04

                       kilogallons potable water             1000 gallons potable water

Chemical Costs

Acid Cost = 3 cents/pound 99.5 percent H2S04
NaOH Cost = 10 cents/pound 100 percent NaOH
Regeneration Acid = 1.29 pounds 99.5 percent H2SO4
If neutralization of the waste acid is required prior to disposal:
Waste Acid = 1.29 pounds 99.5 percent H2S04

                       1000 gallons potable water
If we use 100 percent NaOH

                                                                 40 equivalent weight NaOH
NaOH = 1.32 pounds of 100% acid as CaCO3 x 50 equivalent weight CaCO3

            =    1.05 pounds of 100 percent NaOH

                       1000 gallons potable water

Summary of Cost Per 1000 Gallons of Potable Water
      Cation exchange acid usage = 1.29 pounds x 3.0 cents = 3.87 cents
      Waste acid = 1.29 pounds x 3.0 cents = 3.87 cents
      Neutralization NaOH = 1.05 pounds x 10 cents = 10.5 cents

5 Pounds/Cubic Foot Regeneration Level
∴In 1000 gallons potable water

    396 gallons raw water to 500 milligrams per liter of total dissolved
    solids + (1000 - 396) x .37 = 223.5 gallons to neutralization
Or

         396 + 223.5 = 619.5 gallons of raw water
And

         380.5 gallons of cation effluent
So:

         38 percent of potable water is treated with the cation exchanger
Acid Usage

  Cation Regeneration Efficiency

                                                             A-29


---

                                                                                                          TM 5813-8

                                  (5 pounds/cubic feet) (.93 pounds acid/

50 Equivalent Weight CaCO3 x            pound) (7 kilograins/pound)               = 2.44

49 Equivalent Weight H2S04               13.6 kilograins/cubic feet

                                        or 250 percent stoichiometric

Cations Removed

380.5 gallons             x       488 parts per million - 61 parts per million x 1 pound

kilogallon potable water                17.1 parts per million/grains/gallon                 7000 grains

                          =       1.36 pounds as CaCO3

                                  1000 gallons potable water

At 250 Percent Regeneration Efficiency:

Acid Required

= 2.5        1.36 pounds as CaCo 3 x 49 equivalent weight acid x 1pound H2SO4
            1 kilogallon potable water 50 euqivalent weight CaCO3 .995 percent H2SO4

= 3.35 pounds 99.5 percent H2SO4
            1000 gallons potable water

Waste Acid

(2.5-1.0) x 1.34 = 2.01 pounds acid/1000 gallons potable water

Chemical Costs

Acid Cost = 3 cents/pound               99.5 percent H2SO4
NaOH Cost = 10 cents/pound              100 percent NaOH

Regeneration Acid= 1.34 pounds 99.5 percent H2SO4
                                1000 gallons potable water

If neutralization of the waste acid is required prior to disposal:

       Waste acid = 2.01pounds 99.5 percent H2SO4
                             1000 gallons potable water

If we use 100 percent NaOH

NaOH = 2.04 pounds of 100% acid as CaCO3 x 40 equivalent weight NaOH
                                                                 50 equivalent weight CaCO3

               = 1.63 pounds of 100 percent NaOH
                          1000 gallons potable water

Summary of Cost per 1000 Gallons of Potable Water

Cation exchange acid usage = 1.34 pounds x 3.0 cents = 4.02 cents

Waste acid                        = 2.01 pounds x 3.0 cents = 6.0 cents

Neutralization NaOH               = 1.63 pounds x 10 cents = 16.3 cents

These chemical costs and water quantities can now be used for life cycle costing of the system.

The ion-exchange equipment size and cost will vary with the cation-exchange flow rate and loading.

The traded water quantities are:

Potable water requirement 450,000 gallons per day

With 5 pounds/cubic foot regeneration, 38 percent of the potable water is treated by ion exchange

= 171,000 gallons per day.

With 3 pounds/cubic foot regeneration, 40.9 percent of the potable water is treated by ion exchange

= 184,050 gallons per day.

Figures A-20 and A-21 show the plan view of two cation exchangers and a degasifier, respectively,

similar to the equipment that will be necessary for such an ion-exchange system.

                                                            A-30


---

                                                                                                                      TM 5-813-8

Figure A-20. Cation exchangers plan
                     A-31


---

                                                                                               TM 5-813-8

                           .
Figure A-21. Degasifier and clearwell plan.

                         A-32


---

                                                                                                                                                    TM 5-813-8
A-5. Sample of multiple component water blend optimization. A base on a volcanic island in the Pacific is to be
expanded. While inadequate disinfection has often been blamed for the maladies of newcomers, the analysis requested
before pumping and drilling tests are continued indicate a hard, high total dissolved solids, sulfate-rich fresh water lens on
the island. For these reasons you have been assigned to direct a study to evaluate the various desalination options. You
have good reason to believe that both water quantity and brine disposal will prevent the simple desalination of island well
water to supply the projected 500 gallons per minute of potable water. A product-staged or double-pass reverse osmosis
sea water desalination facility will apparently be required.

Symbols:  x = The flow rate of fully treated relatively pure second-stage reverse osmosis product water used in
               the blend.

          y = The flow rate of the first-stage reverse osmosis product water used to blend.
          z = The flow rate of island well water used to blend.
          Cx = The unit cost of second-stage reverse osmosis water (water x).
          Cy = The unit cost of first-stage reverse osmosis product water (water y).
          Cz = The unit cost of island well water (water z).
          C = The unit cost of final blended water.

          SAMPLE PROBLEM ON BLENDING

Given:  The high quality two-pass water (water x) contains:
             50.0 mg Cl-/liter
             1.2 mg SO4=/liter

        and 95.5 mg TDS/liter

        The single-pass water (water y) contains:
             500 mg Cl-/liter
             30 mg SO4=/liter
             85 mg TDS/liter

        The well water presently being used (water z) contains:
             30 mg Cl-/liter
             400 mg SO4=/liter
             729 mg TDS/liter

        The final blend must meet TB MED 576 standards or
             Cl- Û 250 mg Cl-/liter
             SO4= Û 250 mg SO4=/liter
             TDS Û500 mg TDS/liter

        i=n
        Σ Flowi Concentrationi ÷ Flow Total = Final Concentration
        i=l

                1=n Flowi Costi/Gallon ÷ Flow Total = Final Unit Water Cost = C
                  Σ

Step 1: List Equations
          a. Water Balance
                x + y + z = 500
          b. Blend Concentration Constraints
                Chloride 50x + 500y + 30z Û 500(250)
                Sulfate 1.2x + 30y + 400z Û 500(250)
                Total Dissolved Solids
                     95.5 + 851y + 729z Û 500(500)

                                                                              A-33


---

                                                                    TM 5-813-8

c. Two-Way Blends

     for Chloride
          500y + 50x Û 250(500)
          x = 500 - y

     ∴500y + 50(500) - 50y Û 250(500
     or y Û 500(250 - 50)/(500 - 50)
     for Total Dissolved Solids

          851y + 95.5x Û 500(500)
          x = 500 - y
     ∴851y + 95.5(500) - 95.5y Û 500(500)
     or y Û 500(500 - 95.5)/(851 - 95.5)
     For sulfate, neither water y nor x are limited.

     for Sulfate
     400z + 1.2x Û 250(500)

          x = 500 - z
     ∴400z + 1.2(500) - 1.2z Û 250(500)
     or z Û 500(250 - 1.2)/400 - 1.2)
     for Total Dissolved Solids
     792z + 95.5x Û 500(500)

          x = 500 - z
     ∴792z + 95.5(500) - 95.5z Û 500(500)
     or z Û 500(500 - 95.5)/(729 - 95.5)
     For Chlorides, neither water x nor z are limited.
d. Cost
     Cxx + Cyy + Czz = C

Step 2: Project constraints onto water balance equation to eliminate one variable (preferably the most expensive water).

     a. Chloride 50x + 500y + 30z Û 125,000
                     - 50x - 50y - 50z = - 25,000
                              450y - 20z Û 100,000

b. Sulfate  1.2x + 30y + 400z 125,000
             -1.2x - 1.2y - 1.2z = - 600
             28.8y + 398.8z Û 124,400

c. Total Dissolved Solids   95.5x + 851y + 729z Û 250,000
                           -95.5x - 95.5y - 95.5z = - 47,750

                                 755.5y + 633.5z Û 202,250

Step 3: Graph resulting constraint questions, two dimensions at a time in the M dimensional space required (i.e., for
            blending 10 waters, all combinations of 9 things taken two at a time; for this example of 3 waters all combinations
            of 2 things taken two at a time). See figure A-22.

Step 4: Solve all constraints simultaneously to identify corners and edges. The most economical blend will almost always
            occur at a corner, but it is possible that an entire range of blend values along a constraint edge will be equally
            economical.

a. Chloride - Sulfate Pair
                     SO4= = 28.8y + 398.8z Û 124,400

          (398.8/20)Cl- = 8973.0y-398.8z Û 1,994,000
                                           9001.8y Û 118,400

                                                              A-34


---

                                                                                                                                                          TM 5-813-8

Figure A-22. Three projections of the water blends that satisfy TB MED 576 Requirements.
                                                         A-35


---

                                                                                             TM 5-813-8

 y Û 235.3                                                See figure A-22 point F.
 z Û [124,400 - 28.8(235.3)]/398.8
 z Û 295
 x Û 500 - 235.3 - 295 = -30.3
but the Total Dissolved Solids in this corner is:
 -30.3(95.5) + 235.3(851) + 295(729) ?Û 250,000

            412,401.65 Û 250,000
Therefore, this corner is outside of the TDS constraint.

b. Total Dissolved Solids - Chloride Pair

    Total Dissolved Solids 755.5y + 633.5z Û 202,250
    (633.5/20)Cl- = 14,253.75y - 633.5z Û 3,167,500

                           15,009.25y Û 3,369,750

          y Û 224.5
          z Û [202,250 - 755.5(224.5)]/633.5
          z Û 51.5
          x Û 500 - 224.5 - 51.5 = 224
    and for Sulfate SO4=;
          224(1.2) + 224.5(30) + 51.5(400) ?Û 125,000
          27,603.8 Û 125,000
    Therefore, this blend will have less than the maximum allowable sulfate concentration.

c. Total Dissolved Solids - Sulfate Pair

Total Dissolved Solids  755.5y Û 202,250 - 633.5z
(755.5/28.8) SO4= =     -755.5y Û 3,263,340.3 - 10461.6z

∴solving for the equal condition only

202,250 - 633.5z = 3,263,340.3 - 10,461.6z

      z = 311.5
      y Û [202,250 - 633.5(311.5)]/755.5
      y Û 6.5
using the equal condition makes z Û 311.5
      x Ú 500 - 311.5 - 6.5 = 182
and for chloride Cl-
182(50.0) + 6.5(500) + 311.5(30) Û 125,000
      21,695 Û 125,000

Therefore, this blend will have less than the maximum allowable chloride C1- concentration.

Blends containing only high quality second-stage product water and one of the remaining waters x or y could be

most economical.

d. Well Water z and Water x
    1. Sulfate limited
          z Û 500 (250 - 1.2)/(400 - 1.2)
          z Û 311.9 so x Ú 188.1
    2. TDS limited
          z Û 500(500 - 95.5)/729 - 95.5)
          z Û 319.25 so x Ú 180.75
    3. Chloride cannot limit since both have chlorides below 250.

e. Single-Pass Reverse Osmosis Water y and Water x.

                                            A-36


---

                                                                                                   TM 5-813-8

1. Chloride limited

y < 500 (250 - 50.0)/(500 - 50.0)
y < 222.2 so x Ú 277.8

2. TDS limited

y < 500(500 - 95.5)/(851 - 95.5)

y < 267.7 so x > 232.3

3. Sulfate cannot limit since both waters have sulfates below 250. (The intercept at 4319.4 would require a

removal flow of -3819.4 of second-stage product water x to concentrate the split stream to 250 mg SO4/liter.)

f. Locate Inside Intercepts

1. Since 311.9 < 319.25,

Sulfate limits use of water

z to z < 311.9 with

x > 188.1

2. Since 222.2 < 267.7,

Chloride limits use of water

y to y < 222.2 with

x > 277.8

Step 5: Identify the coordinates of the corners of the convex polyhedron of acceptable blends.

In this case, the polyhedron is a pentagon with 5 corners.

The coordinates of the corners of acceptability are:

                     x          y    z

1-                   500        0    0

2-                   577.8 222.2 0

3-                   188.1 0         311.9

4-                   182        6.5  311.5

5-                   224        224.5 51.5

Step 6: Use Cost Equation to make each corner and edge a minimum cost solution (use the graph to identify adjacent
                corners).

     a. All Second-Stage Product (No Blending)
                Cx 500 < 188.1 Cx + 311.9 Cz

         and Cx 500 < 277.8 Cx + 222.2 Cy
         Therefore, don’t blend at all if Cx < Cz and Cx < Cy
     b. Blend of x and y Waters Only
         500Cx > 222.2 Cx + 277.8 Cy and 222.2 Cx + 277.8C y < 224 Cx + 224.5 Cy + 51.5 Cz

or Cx > Cy
and 53.8 Cx < 2.3 Cy + 51.5 Cz
or Cx < 0.0427 Cy + 0.95725 Cz
Therefore, if the cost of water x was greater than the cost of water y, and less than 0.0427 Cy + 0.957 Cz then the
blend of single- and double-pass sea water reverse osmosis products would be more economical than any blend
containing well water.

c. Blend of x and z Water Only

500 Cx > 188.1 Cx + 311.9 Cz and 188.1 Cx + 311.9 Cz < 182 Cx + 6.5 Cy + 311.5 Cz

or Cx > Cz
and 6.1 Cx + .4 C2 < 6.5 Cy
or Cx < 1.066 Cy - 0.066 Cz

Therefore, if the cost of water x was greater than the cost of water z, but less than 1.066 Cy - 0.066 Cz, then the
blend of well water and double-pass sea water reverse osmosis product would be more economical than any blend
containing any single-pass waters.

d. Blend at Point A Figure A-22 containing a small amount of single-pass reverse osmosis water y.

                                            A-37


---

                                                                                                                                                    TM 5-813-8
         182 Cx + 6.5 Cy + 311.5 Cz < 224 Cx + 224.5 Cy + 51.5 Cz and 182 Cx + 6.5 Cy + 311.5 Cz
         < 188.1 CX + 311.9 Cz
         or

                260 Cz < 42 CX + 218 Cy
         and 0.4 Cz > 6.5 Cy - 6.1 Cx
         or
         16.25 Cy - 15.25 Cx < Cz c 0.1615 Cx + 0.838 Cy
         Therefore, if the cost of well water is less than 0.1615 Cx + 0.838 Cy and greater than 16.25 Cy - 15.25 Cx, then
         the use of 6.5 gallons/minute of first-stage reverse osmosis product water in a blend to reduce the amount of
         second-stage product needed, to dilute well water, from 188.1 gallons/minute to 182 gallons/minute will be
         economical.
     e. Blending at Point B Figure A-22
         using 224 gallons/minute of water x

                224.5 gallons/minute of water y
         and 51.5 gallons/minute of water x
         224 Cx + 224.5 Cy + 51.5 C, < 182 Cx + 6.5 Cy + 311.5 Cz, and 224 Cx + 224.5 Cy + 51.5 Cz
         < 277.8 Cx + 222.2 Cy
         or
         42 CX + 218 Cy < 260 Cz
         and 51.5 Cz < 53.8 Cx - 23 Cy
         or
         0.1615 Cx + 0.838 Cy < Cz
         and Cz < 1.0447 Cx - 0.0447 Cy
         Therefore, if the cost of well water is greater than 0.1615 Cx + 0.838 Cy and less than 1.0447 Cx - 0.0447 Cy, then
          the use of a blend of 51.5 gallons/minute of product-staged double-pass reverse osmosis water, with 224.5
          gallons/minute of first-pass reverse osmosis product water and 224 gallons/minute of well water, would be the
          most economical blend.

Step 7: Make Reasonable Assumptions and Worst Case Scenarios
     a. The cost of second-stage reverse osmosis product water must be greater than the cost of first-stage reverse
          osmosis product water, because second-stage water is made from first-stage water.
     b. The maximum recovery available with most triple-reject-staged reverse osmosis membrane module assemblies is
          85%.
     c. The second-stage low-pressure desalination of first-stage product water is almost always less expensive than the
          initial first-stage desalination of sea water.
     d. The expansion of a drain field collection or a well field system is almost always cheaper than the desalination of
          even brackish water.

Step 8: Put Assumptions and Scenarios into Mathematical Form
     a. Using 2 from step 7
         Cx > Cy
     b. Using a and b from step 7
         CX > 1/.85 Cy = 1.176 Cy
     c. Using c and a from step 7
         Cx < 2 Cy usually
     d. Using d from step 7
         C2 < Cy usually
     e. Using a and d above
         Cx > Cy > Cz usually
     f. Using c and d above
         1/2 Cx < Cy > Cy usually
     g. Using b and d above
         .85 Cx > Cy > Cz usually

                                                                              A-38


---

                                                                                                                                                    TM 5-813-8
Step 9: Analyze the Minimum Corner and Edge Constraints Solutions from Step 6 with respect to the assumptions and

          scenarios in Step 8.
     a. Since Cx > Cy and for the minimum cost solution to be all double-pass water such as Case a, Step 6, Cx > Cy,

          blending should be done for economy.
     b. When water x and y are the only components of a blend Case B, Step 6 shows

         Cx < 0.0427 Cy + .957 Cz
         and Step 8, Case g shows
         .85 Cx > Cy > Cz
         Therefore, 1.176 Cy 0.0427 Cy + .957 Cz
         or 1.134 Cy < Cz,
         which violates the second half of Step 8, Case g, unless the cost of well water really is greater than 1.13 times the
         cost of first-stage reverse osmosis sea water desalination.
     c. When water x and z are the only components of a blend
         Case C, Step 6 shows
         Cx < 1.066 Cy - 0.066 Cz
         and Step 8, Case b shows
         Cx > 1.176 Cy
         Therefore, 1.176 Cy < 1.066 Cy - 0.066 Cz
         or 0.11 Cy < - 0.066z,
         so this cannot be an optimum solution unless someone is paying you to dispose of well water z.
     d. When 6.5 gallons/minute of first-stage reverse osmosis product water is used in a triple blend Step 6, Case d
         shows
         16.25 Cy - 15.25 Cx < Cz < 0.1615 Cx

                + 0.838 Cy
         and Step 8, Case f shows
         .5 Cx < Cy > Cz usually
         Therefore,
         16.25 Cy - 15.25(2 Cy) < Cz < 0.1615(2Cy)

                + 0.838 Cy
         or - 14.25 Cy < Cz < 1.161 Cy,
         so for any cost from being paid 14.25 times the cost of water y to dispose of well water z to having water z cost
         1.161 times water y the optimum cost solution will be this triple blend.
     e. When the acceptable triple blend of

                224 gallons/minute of water x
                224.5 gallons/minute of water y
         and 51.5 gallons/minute of water z
         is most economical, Step 6, Case e shows
         0.1615 Cx + 0.838 Cy < Cz < 1.0447 Cx
                - 0.0447 Cy
         and Step 8, Case f, shows
         .5 Cx < Cy > Cz usually
         and Step 8, Case g shows
         .85 Cx > Cy > Cz usually
         Therefore,
         (0.1615)(1.176 Cy) + 0.838 Cy < Cz 1.0447 (2 Cy)
                - 0.0447 Cy
                1.0279 Cy < Cz < 2.0447 Cy
         so this blend will be economical only if the cost of well water is greater than the cost of single-pass desalinated sea
         water by more than 1.03 times and less than 2.04 times as expensive as single-pass desalinated sea water. These
         conditions violate the second part of Step 8, Cases f and g.

Step 10: Draw Conclusions

     a. The most economical blending strategy on the island will almost certainly be: 182 gallons/minute of high quality
          second-stage, product-staged reverse osmosis desalinated sea water

                                                                              A-39


---

                                                                                                                                                    TM 5-813-8

          6.5 gallons/minute of high chloride high total dissolved solids single-or first-stage reverse osmosis desalinated sea
                 water. 311.5 gallons/minute of high sulfate island well water

          This blend will be most economical when:
             1. The cost of island well water is between 14.25 times single-or first-stage product water and 1.161 times the
                   cost of this first-stage product water.
             2. The removal of 311.5 gallons/minute of well water does not degrade the water quality in the wells.

     b. The availability of up to 312 gallons/minute of island well water and the quality of island well water should be
          investigated extensively.

     c. If over roughly (500) + 85 = 600 gallons/minute of island well water can easily be withdrawn without degrading the
          quality or quantity of island well water in the future, then the facility should be reviewed again for the installation of
          electrodialysis-reversal treatment at 85% recovery and disposal of the resulting high sulfate brine.

     d. The use of a mere 6.5 gallons/minute of first-stage desalinated sea water will save at least (188.1 182)
          gallons/minute = 6.1 gallons/minute of second-stage reverse osmosis water plus (6.1) + 0.85 6.5 gallons/minute =
          0.68 gallons/minute first-stage reverse osmosis water. This savings is definitely worth the engineering,
          construction, and operation costs.

     e. A table showing the final cost of blended waters consisting of the five possible minimum cost blends of $.10 well
          water, $4.00 single-pass reverse osmosis water, and $5.75 double-pass reverse osmosis water has been
          prepared and is shown in table A-3. Figure A-23 shows a plan view of the desalination system of a two pass
          reverse osmosis system.

A-6. Sample problem for simple blend. A base in the desert has a water with a total dissolved solids content of 907
mg TDS/liter. If reverse osmosis is to be used as a desalination technique in this application, then the final product water
will have far less than the required 500 mg TDS/liter. If 250,000 gallons/day of finished water will be required, how much
of the raw water can be reblended in meeting TB-MED 576 requirements?

    Symbols:
          x = Amount of water that must be treated

    Given:
          Daily flow is 250,000 gallons/day
          Finished blend concentration is 500 mg TDS/liter.
          Initial feed concentration is 907 mg TDS/liter.

Flow Concentrated = (Desired Concentration - Dilute Concentration) Flow Dilute
                                       (High Concentration - Desired Concentration)

                                                    SAMPLE PROBLEM FOR SIMPLE BLEND
Assumptions: a. The total dissolved solids rejection of a low-pressure membrane is about 90%, leaving .1 x TDS in the

                        dilute water stream.
                    b. Total dissolved solids are the limiting factors in the reblending.
Therefore: The flow of raw undesalinated water used = 250,000 gallons/day - x
And:

                    (250,000 gallons/day - x) = [500 - .1(907)]x
                                                              (907 - 500)

250,000 gallons/day = x + (409.3/407)x
250,000 gallons/day = 2.00565x
·'. x = 124,000 gallons/day

A-7. Silt density index (SDI). This fouling index mentioned in Chapter 3, tables 4-2 and 4-3, and Chapter 5 is
measured on a 47-millimeter-diameter 0.45-micron pore size membrane filter. The data used by the manufacturers to
calculate the index are the time (T1) necessary initially to force 500 milliliters of solution through a clean 0.45-micron filter
with a 30-pound-per-square-inch pressure differential across the filter, followed by the time (T2) required to force an
additional 500

                                                                              A-40


---

                                                                                                                                   TM 5-813-8

Table A-3. Cost projections for possible optimum blends.
                                  A-41


---

                                                                                                                                                    TM 5-813-8

                                      Figure A-23. Plan review of a two-pass reverse osmosis system.
Source Neptune MiroFIoc Inc
milliliters of solution through the same filter (operating at the constant pressure 30 pounds per square inch gauge) 15
minutes later. Between these two time periods (TB = 15 minutes) the solution must be continuously fed to the membrane
filter under a constant 30-pound-per-square-inch gauge pressure differential. The silt density index is then calculated in
the following manner:

    Symbols:
          T1 =Time for first 0.132 gallons to pass filter
          TB = Time between two measured 500-milliliter samples, usually 15 minutes
          T2 = Time for second 500-milliliter sample to pass filter
          SDI = Silt Density Index
                                                                              A-42


---

                                                                      TM 5-813-8

Given:                         = SDI
      T = 1 minute
      TB = 15 minutes
      T2 = 4.083 minutes

             (1- T1/T2) x 100
                      TB

The formula for the SDI is as follows:
SDI = (1 - 1 minute/4.083 minutes) 100/15 minutes = 5.03 silt density index

A-8. Concentration factor. If the percentage of the feed stream that is removed as product water (i.e., percent recovery)
is known, the concentration of the brine can be calculated for the purpose of estimating scaling concentrations as follows:

      Symbols:
             Percent Rec. = 100 x the fraction of the feed water that becomes product water

      Given:
             30 percent of the feed water becomes product
             At 30 percent recovery, 70 percent of water contains all the original salt, ∴
             1/0.7 x original concentration = final concentration
                                1
                   1-Percent Rec. = Concentration factor
                          100
                     1
                   1-30 = 1.429
                     100

A-9. Reverse osmosis membrane requirement (manufacturers will supply the necessary number of permeators).
The following equations can be used with membrane manufacturer’s water flux constants to calculate a water flux or, by
rearrangement of the equation, a membrane area requirement can be calculated.

      Symbols:
             Qw = Water flow
             Kw = Water flux constant for the membrane
             A = Area of membrane
             ∆P = The pressure drop across the membrane (not including head losses to or from the membrane)
             Aπ = The osmotic pressure difference across the membrane

Usually about:  10 pounds per square inch

                1,000 milligrams per liter of total dissolved solids

Given:
      Kw = 2.53 x 10-7 gallons/pound-hour
      The membrane area, A = 1,000 square feet
      The applied pressure, P = 900 pounds/square inch
      The osmotic-pressure difference, ∆π = 350 pounds/square inch.
             Qw = KwA (∆P - ∆π)
             Qw = 2.53 x 10-7 gallons/pound-hour x 1,000 square feet x 144 square feet x (900 pounds/square inch - 350
                      pounds/square inch)
             Qw = 20 gallons/hour

                                                                        A-43


---

                                                                                                      TM 5-813-8

A-10. Reverse osmosis membrane salt flux (manufacturers will meet desired water quality). The following

calculations can be used with membrane manufacturer’s specific ion flux constants to estimate the concentrations of

particular ions in the product water.

      Symbols:

      Qs                               = The salt flow

      Ks                               = The salt flux constant for the ion under consideration across the membrane

used

      A                                = The area of membrane

      Cion feed/brine average          = One half the sum of the feed concentration and the reject brine concentration of

                                       the ion under consideration (Mg+ + in this example)

      Cion product                     = The concentration in the product of the ion under consideration (Mg+ + in this

                                       example)

      Given:
            The salt flux constant for this membrane Ks = 2.8 x 10-4 gallons per square foot-hour

      The membrane area A, = 1,000 square feet

      The feed water contains 204.4 grains per gallon of magnesium Mg ++.

      The product water contains 0.3 grains per gallon of magnesium Mg+ +.

      Qs = KsA (Cion feed/brine average Cion product)
      Qs = (2.8 x 10-4 gallons per square foot-hour)

                (1,000 square feet)

                (204.4 grains per gallon Mg+ + -0.3 grains per gallon Mg++)

                = 57 grains Mg+ + per hour

A-11. Second-law limiting thermal efficiency. A perfect conversion of heat into work is not possible. There is,
however, a limiting efficiency of conversion of heat energy to mechanical or electrical energy. No heat machine can
operate at this best efficiency, but it does allow a rough estimate of the value of lower grades of steam.

      Symbols:    Temperature in degrees Rankine of steam source. Higher temperature in degrees
            TH =  Rankine (degrees Rankine equal degrees Fahrenheit plus 460 degrees)

      TL =        Temperature in degrees Rankine of the cooling sink. Lower or discharge
                  temperature in degrees Fahrenheit

      emax =      Maximum possible second law efficiency (maximum percent of the heat available
                  that can be converted theoretically into work)

      emax = (TH - TL)/TH X 100

      Given:
            The steam temperature drop available is 264 degrees Fahrenheit to 68 degrees Fahrenheit.
            (See problem A-2.)

      emax = (724 degrees Rankine - 528 degrees Rankine)/724 degrees Rankine x 100

      emax = 27 percent

                                                        A-44


---

                                                  APPENDIX B                              TM 513-8

      WATER TESTING REQUIRED FOR DESALINATION TREATMENT                     Distillation

TEST                                                               PROCESS  D-P
                                                                            D
TDS                                               Electrodialysis  Reverse  D-P
Temperature                                       Reversal         Osmosis  P
Turbidity                                                                   D-P
Suspended Solids                                  D-P              D-P      D
Color                                             D                D        P
Corrosivity                                       D-P              D-P      D-P
Odor                                              P                P        D-P
pH                                                D-P              D-P      D-P
Alkalinity                                        D                D        D-P
Total Hardness                                    P                P        D-P
Noncarbonate Hardness                             D-P              D-P      D
Carbonate Hardness                                D-P              D-P      D
H2S                                               D-P              D-P      D-P
Chlorine Demand                                   D-P              D-P      D
Bacterial Contamination                           D-P              D-P      D
Plankton                                          D                D        D-P
Oil and Grease                                    D                D        D-P
Endrin                                            D-P              D-P      D-P
Lindane                                           D                D        D-P
Methoxychlor                                      D                D        D-P
Toxaphene                                         D-P              D-P      D-P
2, 4-D                                            D-P              D-P      P
2, 4, 5-TP Silvex                                 D-P              D-P      D-P
Trihalomethanes                                   D-P              D-P      D-P
Ammonia                                           D-P              D-P      D-P
Arsenic                                           D-P              D-P      D-P
Barium                                            P                P        D-P
Cadmium                                           D-P              D-P      D-P
Chromium                                          D-P              D-P      D-P
Lead                                              D-P              D-P      D-P
Mercury                                           D-P              D-P      D-P
Nitrate                                           D-P              D-P      D-P
Selenium                                          D-P              D-P      D-P
Silver                                            D-P              D-P      D-P
Fluoride                                          D-P              D-P      D-P
Zinc                                              D-P              D-P      D-P
Copper                                            D-P              D-P      D-P
Boron                                             D-P              D-P      D
Calcium                                           D-P              D-P      D
Magnesium                                         D-P              D-P      D
Strontium                                         D-P              D-P      D
Sodium                                            D-P              D-P      D
Potassium                                         D                D        D
Bicarbonate                                       D                D        D-P
Carbonate                                         D                D
Sulfate                                           D                D
                                                  D                D
Legend:                                           D                D
    D = Required for desalination process design  D-P              D-P
    P = Required for potable water design
                                                     B-1


---

                 TEST                             Electrodialysis  PROCESS             TM 5-813-8
                                                  Reversal
Chloride                                                           Reverse  Distillation
Iron                                              D-P              Osmosis  D-P
Manganese                                         D-P                       D-P
Molybdenum Reactive                               DP               D-P      D-P
Silica                                                             D-P
Molybdenum Nonreactive                                             D-P
Silica
Silt Density Index                                                 D

Legend:                                                            D
    D = Required for desalination process design                   D
    P = Required for potable water design


---

                                                                             TM 5-813-8

                              APPENDIX C
                             REFERENCES

Government Publications.     Construction Criteria Manual
    Department of Defense.
    DOD 4270.1-M             Water and Sewage
    Department of the Army.  Sanitary Control and Surveillance of Water
    AR 420-46
    TB MED 229                    Supplies at Fixed and Field Installations
                             Sanitary Control and Surveillance of Water
    TB MED 576
                                  Supplies at Fixed Installations
    TM 5-813-1               Water Supply Sources and General

    TM 5-813-3                    Considerations
    TM 5-813-4               Water Treatment
    TM 5-813-7               Water Supply and Water Storage
                             Water Supply Special Projects

                                                                C-1


---

                                                                                                                                                    TM 5-813-8

                                                                      BIBLIOGRAPHY

A. Books:

American Chemical Society, Journal of Chemical and Engineering Data, XIII, Aqueous Systems at High Temperature,
    American Chemical Society, 1155 16th St. N.W., Washington, DC (January 1968).

American Public Health Association, American Water Works Association, and Water Pollution Control Federation,
    Standard Methods for the Examination of Water and Wastewater (15th Edition). American Public Health Association,
    Washington, DC (1981).

Spiegler, K. S., and A. D. K. Laird, Principles of Desalination (2nd Edition). Parts A and B. Academic Press, New York
    (1980).

B. Manuals:

Desalting Handbook for Planner OWRT-8701 (1) NTIS PB80-202518. Office of Water Research and Technology and
    Catalytic, Inc. (1979).

Electrical Design Corrosion Control TM 5-811-4. Department of the Army (1962).
Installation Master Planning Principles and Procedures TM5-803-1. Department of the Army (1970).
The Decision Logic Table Technique PAM 310-11. Department of the Army (1967).
U.S. A.I.D. Desalination Manual. United States International Development Cooperation Agency, Office of Engineering,

    and CH2M Hill International Corp (1980).

                                                                            Biblio-1


---

The proponent agency of this publication is the Office of the Chief of Engineers, United States
Army. Users are invited to send comments and suggested improvements on DA Form 2028
(recommended Changes to Publications and Blank Forms) direct to HQDA (DAEN-ECE-G), WASH
DC 20314-1000.

By Order of the Secretary of the Army:  JOHN A. WICKHAM, JR.
                                        General, United States Army
Official:
                 R. L. DILWORTH              Chief of Staff

Brigadier General, United States Army
                 The Adjutant General

DISTRIBUTION:
To be distributed in accordance with DA Form 12-34B requirements for Water Supply-Special Projects.

                                        *U.S. GOVERNMENT PRINTING OFFICE 1995-388-421/40468


---



---

PIN: 060240-000


--- 