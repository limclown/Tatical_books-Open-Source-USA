# mcwp_6-22_undated  MCWP 6-22

  Communications
           and

Information Systems

    U.S. Marine Corps
                    PCN: 143 00042 00


---

                                        To Our Readers

   Changes: Readers of this publication are encouraged to submit suggestions and
   changes that will improve it. Recommendations may be sent directly to Commanding
   General, Marine Corps Combat Development Command, Doctrine Division (C 42),
   3300 Russell Road, Suite 318A, Quantico, VA 22134-5021 or by fax to 703-784-2917
   (DSN 278-2917) or by E-mail to smb@doctrine div@mccdc. Recommendations
   should include the following information:

         • Location of change
                Publication number and title
                Current page number
                Paragraph number (if applicable)
                Line number
                Figure or table number (if applicable)

         • Nature of change
                Add, delete
                Proposed new text, preferably double-spaced and typewritten

         • Justification and/or source of change

Additional copies: A printed copy of this publication may be obtained from Marine
Corps Logistics Base, Albany, GA 31704-5001, by following the instructions in MCBul
5600, Marine Corps Doctrinal Publications Status. An electronic copy may be obtained
from the Doctrine Division, MCCDC, world wide web home page which is found at the fol-
lowing universal reference locator: http://www.doctrine.quantico.usmc.mil.

      Unless otherwise stated, whenever the masculine or feminine gender is used,
                                both men and women are included.


---

                              DEPARTMENT OF THE NAVY
                        Headquarters United States Marine Corps

                                Washington, DC 20380-1775

                                                                            16 November 1998

                                         FOREWORD

Marine Corps Warfighting Publication (MCWP) 6-22, Communications and Infor-
mation Systems, presents doctrine, tactics, techniques, and procedures (TTP) for the
employment of communications and information systems to support Marine air-
ground task force (MAGTF) command and control. It builds on the underlying
approach to command and control described in Marine Corps Doctrinal Publica-
tion (MCDP) 6, Command and Control, and supports the basic warfighting philoso-
phy of the Marine Corps as presented in MCDP 1, Warfighting. MCWP 6-22
emphasizes the relationship between effective employment of communications and
information systems and effective command and control, which leads ultimately to
success on the modern battlefield.

MCWP 6-22 provides guidance to communications and information systems (CIS)
personnel (officer and enlisted) in planning, installing, operating, and maintaining
communications networks and interfacing information systems to those networks.
It also provides guidance for commanders and their staffs, who are the users of
MAGTF communications and information systems. MCWP 6-22 does not provide
detailed instructions on the use of any single item of equipment or system, but
rather provides a broad understanding of how communications and information
systems are used to support command and control.

MCWP 6-22 addresses the planning and employment of information systems as
well as communications systems. This publication describes the integration of the
previously separate functional areas of communications and data processing and
emphasizes the rapidly changing nature of information technology and the com-
mand and control environment. In this regard, it addresses the impact on the Marine
Corps of both the Global Command and Control System (GCCS) and the Defense
Information Systems Network (DISN). MCWP 6-22 is intended to be read by all
Marines involved in the command and control process, whether as users of infor-
mation or as operators of communications and information systems.

Substantial developmental efforts are underway throughout the Marine Corps com-
mand and control doctrinal hierarchy. The target date for completion of all new and
revised command and control series doctrinal publications is the summer of 1999.
Pending completion of this task, in the event of terminology, conceptual, opera-
tional, or other conflicts between MCWP 6-22 and other FMFM’s, MCWP 6-22
takes precedence.


---

This publication supersedes Fleet Marine Force Manual (FMFM) 3-30, Communi-
cations, dated 3 April 1989.
Reviewed and approved this date.
BY DIRECTION OF THE COMMANDANT OF THE MARINE CORPS

                                                             J. E. RHODES
                                              Lieutenant General, U.S. Marine Corps

                                                         Commanding General
                                          Marine Corps Combat Development Command

DISTRIBUTION: 143 000042 00


---

             Communications and Information Systems

                           Table of Contents

Chapter 1    Command and Control and                                 Page
             Communications and Information Systems
1001                                                                    1-1
1002         Command and Control Environment                            1-2
1003         Information Management                                     1-6
1004         CIS Characteristics                                        1-7
             CIS Responsibilities
Chapter 2                                                               2-1
             Organizations                                              2-1
Section I                                                               2-2
             USMC Organizations                                         2-4
2101                                                                    2-4
2102         Operating Forces
2103         Marine Corps Forces                                        2-5
2104         Marine Air-Ground Task Forces                              2-7
2105         Marine Corps Forces Reserves                               2-8
             The Supporting Establishment                               2-8
Section II                                                              2-9
             CIS Organizations                                          2-9
2201                                                                  2-10
2202         Communication Battalion
2203         Marine Wing Communication Squadron                       2-11
2204         Communications Company, HQ Battalion, Marine Division    2-12
2205         Communications Company, HQ and Service Battalion, FSSG   2-13
2206         Communications Platoons, Branches, and Sections          2-15
2207         Special Security Communications Elements and Teams       2-16
             Amphibious Squadron Deployment Teams                     2-17
Section III                                                           2-17
             C2 Organizations                                         2-18
2301                                                                  2-20
2302         MEF CE                                                   2-21
2303         Ground Combat Element
2304         Aviation Combat Element
2305         CSSE
2306         Intelligence Command and Control
2307         Fire Support Centers
2308         Rear Area Operations Centers
2309         CIS Control
2310         Amphibious C2 Facilities
             Mobile CPs

                                                       iii


---

____________________________________________________________________________________________________ MCWP 6-22

Chapter 3    Information Systems and Services

Section I    Defense Information Infrastructure Common Operating Environment

3101         Mission Applications                                             3-1
3102
             Services                                                         3-1
Section II
             Global Command and Control System
3201
3202         Background                                                       3-3
3203
3204         Description                                                      3-4
3205
3206         Joint Operation Planning and Execution System                    3-4
3207
3208         Global Reconnaissance Information System                         3-4
3209
3210         Evacuation System                                                3-5
3211
             Fuel Resources Analysis System                                   3-5
Section III
             Global Status of Resources and Training System                   3-5
3301
3302         Theater Analysis and Replanning Graphical Execution Toolkit      3-5
3303
3304         Joint Deployable Intelligence Support System (JDISS)             3-5
3305
3306         ATO                                                              3-6
3307
3308         JMCIS                                                            3-6
3309
             MAGTF C4I
Section IV
             Migration Strategy                                               3-7
3401
3402         MAGTF C4I Software Baseline Capabilities                         3-7

Section V    Hardware/Operating System Requirements                           3-7

3501         Maneuver                                                     3-10
3502
3503         Intelligence                                                 3-10
3504
3505         Air Operations                                               3-12
3506
3507         Fire Support                                                 3-13

             Logistics                                                    3-14

             Force Deployment Planning                                    3-15

             The Defense Message System

             AUTODIN                                                      3-17

             Upgrades                                                     3-17

             Information Services

             Directory Services                                           3-18

             Terminal Emulation Services                                  3-18

             Message Handling Services                                    3-18

             Network Management Services                                  3-18

             Security Services                                            3-19

             Facsimile Services                                           3-20

             Communications Services                                      3-20

                                          iv


---

Communications and Information Systems __________________________________________________________________

Section VI   Shipboard Information Systems

3601         Key Resources                                3-21

3602         JMCIS-Afloat                                 3-21

Chapter 4 Defense Information Systems Network

4001         Tactical Entry Points                        4-1

4002         DISN STEP Services                           4-2

4003         STEP Access                                  4-3

4004         Changes to DISN STEP Sites                   4-4

4005         USMC Network Operations Center               4-4

Chapter 5 MAGTF Tactical Communications Network

Section I    Overview

5101         Architecture                                 5-1

5102         Challenges                                   5-1

Section II   Single Channel Radio

5201         HF Radio                                     5-4

5202         VHF Radio                                    5-4

5203         UHF Radio                                    5-5

5204         EPLRS                                        5-6

5205         UHF-TACSAT                                   5-6

5206         Commercial International Maritime Satellite  5-8

5207         Data Communications                          5-8

Section III  Local Area Networks

5301         LAN Media                                    5-10

5302         LAN Topologies                               5-11

5303         Access Methods                               5-14

Section IV   Switched Backbone

5401         Tri-Services Tactical System                 5-16

5402         Switches                                     5-17

5403         Global Block Numbering Plan                  5-21

5404         IP Routers                                   5-21

5405         Multichannel Radios                          5-24

Section V    Special Purpose Systems

5501         PLRS                                         5-35

5502         Precision Lightweight GPS Receiver (PLGR)    5-35

5503         JTIDS                                        5-35

5504         Integrated Broadcast Services                5-36

5505         Commander’s Tactical Terminal                5-36

                                            v


---

____________________________________________________________________________________________________ MCWP 6-22

5506         The Joint Tactical Terminal                    5-36

5507         TROJAN SPIRIT II                               5-36

5508         Global Broadcast System                        5-37

5509         JTF Enabler Module                             5-37

Chapter 6 Planning and Execution

Section I    Overview

6101         Planning Information                           6-2

6102         Coordination                                   6-2

6103         Security                                       6-2

6104         Estimates                                      6-3

6105         Recommendations                                6-3

6106         Preparing Plans                                6-3

6107         Implementing Plans                             6-3

Section II   CIS Requirements

6201         Mission                                        6-4

6202         Courses of Action                              6-4

6203         Concept of Operations                          6-4

6204         Task Organization                              6-4

6205         Available Resources                            6-5

6206         Enemy Situation                                6-5

6207         Environment                                    6-6

6208         Information Management Plan                    6-6

Section III  Pre-Deployment Preparation

6301         Review Existing Plans and Orders               6-8

6302         Prepare Troop and Equipment Lists              6-8

6303         Request Augmentation                           6-8

6304         Coordinate Frequencies                         6-8

6305         Request Satellite Access                       6-8

6306         Compile a Publications Library                 6-8

6307         Initiate Telecommunications Service Requests   6-9

6308         Conduct Communications/Command Post Exercises  6-9

6309         Provide CIS Support for Embarkation            6-9

6310         Submit Communications Guard Shifts             6-9

6311         Request COMSEC Material                        6-9

6312         Coordinate Logistics                           6-9

6313         Effect Liaison/Coordination                    6-10

Section IV   CIS Plans, Orders, and Directives

6401         Standing Operating Procedure                   6-11

6402         CEOI                                           6-13

6403         CIS Plan                                       6-14

6404         CIS Estimate                                   6-14

6405         CIS Concept                                    6-14

                                             vi


---

Communications and Information Systems __________________________________________________________________

6406          Paragraph 5 of the OPLAN/OPORD            6-15

6407          Annex K (CIS Annex)                       6-16

Section V     Communications Control

6501          Phases                                    6-17

6502          Responsibilities                          6-18

6503          Functional Areas                          6-18

Section VI    System Planning and Engineering

6601          Functions                                 6-20

6602          Responsibilities                          6-20

6603          Automated Tools                           6-26

Section VII   SYSCON

6701          Functions                                 6-29

6702          Staff Responsibilities                    6-29

6703          OSCC Responsibilities                     6-31

Section VIII  TECHCON

6801          Functions                                 6-32

6802          Responsibilities                          6-32

Chapter 7 Information Systems Security

Section I     Communications Security

7101          Responsibilities                          7-2

7102          Cryptosecurity                            7-3

7103          Transmission Security                     7-3

7104          Emission Security                         7-4

7105          Physical Security                         7-4

Section II    Computer Security

7201          The Threat                                7-6

7202          Protection                                7-7

Section III   Incident Response

7301          The Fleet Information Warfare Center      7-9

7302          Naval INFOSEC Help Desk                   7-9

7303          The Air Force Information Warfare Center  7-10

7304          Points of Contact                         7-10

                                       vii


---

____________________________________________________________________________________________________ MCWP 6-22

Chapter 8 Future Directions

8001         Operational Maneuver From the Sea                                8-1

8002         CIS Requirements                                                 8-2

Appendices:

A     Defense Information Infrastructure Common Operating Environment Compliance A-1

B     Common Hardware and Standard Commercial Software Applications           B-1

C     Ship Visit Checklist                                                    C-1

D     MAGTF Radio Nets                                                        D-1

E     Information Systems Directory                                           E-1

F     CIS Planning Checklist                                                  F-1

G     Unit Planning Checklist                                                 G-1

H     Data Communications Network and Information Systems Planning Checklist  H-1

I     Communications and Information Systems Estimate                         I-1

J     Sample CIS Annex (Annex K)                                              J-1

K     CIS Threat Assessment Planning Checklist                                K-1

L     Emission Classification and Designation                                 L-1

M     Sample Guard Charts                                                     M-1

N     Points of Contact                                                       N-1

O     Glossary                                                                O-1

P     References and Related Publications                                     P-1

                                     viii


---

                                Chapter 1

              Command and Control
                            and

Communications and Information Systems

MCWP 6-22 outlines the responsibilities of CIS      on speed and tempo, demands compressed plan-
personnel and CIS users to ensure that those sys-   ning, decision, execution and assessment cycles.
tems provide effective command and control (C2)     At the same time, the volume of information that
support. MCWP 6-22 is written, to the extent pos-   needs to be processed and analyzed to support de-
sible, in nontechnical language. However,           cisionmaking is exploding, and this information
chapters 3, 4, and 5 contain many computer net-     overload threatens to overwhelm the commander
working and communications terms that may be        and his staff. The MAGTF must employ limited
unfamiliar to most Marines. These terms are de-     CIS resources to meet these challenges. To help
fined in appendix O.                                satisfy the operational requirement, the Marine
                                                    Corps is changing its manpower structure and its
MCWP 6-22 focuses on the CIS used to support        education and training processes as well as its
the MAGTF in the operational environment. It ad-    doctrine through the combat development pro-
dresses CIS employment in support of the Marine     cess. Changes are based on integrating the
Corps component headquarters and how the            previously separate functional areas of communi-
Marine Corps organizes to provide CIS support to    cations and data processing into a single
the MAGTF. It describes the information systems     functional area with responsibilities for both in-
and services that support MAGTF C2 and the em-      formation processing and information exchange.
ployment of communications systems and              This merger will position the Marine Corps to
networks to link these information systems.         take full advantage of advances in information
                                                    technology to meet C2 requirements.
This publication emphasizes the impact of the
rapidly evolving joint C2 environment on Marine     Developments in the joint C2 arena are another
Corps CIS. Key planning considerations, guide-      significant factor in the C2 environment. The De-
lines, and procedures are presented. CIS operation  partment of Defense (DOD) is significantly
is then discussed in terms of system planning and   enhancing the C2 capabilities of the armed forces
engineering, operational systems control (SY-       by rapid exploitation of advanced information
SCON), and technical control (TECHCON)              technologies and significant improvements in in-
followed by information security (INFOSEC) and      teroperability. These accomplishments are largely
communications security (COMSEC). MCWP 6-           the result of the implementation of the Defense In-
22 concludes with a discussion of future CIS        formation Systems Network (DISN) and the
concepts.                                           GCCS and the associated Joint Technical Archi-
                                                    tecture standards. The DISN is an integration of
1001. Command and Control                           DOD communications systems and networks un-
Environment                                         der the management control of the Defense
                                                    Information Systems Agency (DISA). The ulti-
The C2 environment is characterized by rapid        mate goal of DISN is to provide a single,
change and continuous challenge. Implementation     integrated, common-user, global communications
of maneuver warfare doctrine, with its emphasis     network that supports all echelons, strategic
                                                    through tactical. Similarly, the GCCS is designed
                                                    to replace incompatible Service-unique C2


---

1-2 ________________________________________________________________________________________________ MCWP 6-22

systems with a single, integrated C2 system. Im-      true in a battle of wills between opposing forces
plementation of GCCS will ensure interoperability     in military or political conflicts in which each side
among forces and provide a common operational         seeks to deceive the other with false information.
picture and a common set of decision support tools    The commander cannot, therefore, be certain that
for all components of the joint task force (JTF).     the information obtained depicts the situation
Through communications connectivity provided          with absolute certainty, only that it provides an
by the DISN, GCCS will support the planning, de-      approximation of reality. Generally, the com-
ployment, employment, sustainment, and                mander’s approximation of reality can be
redeployment of joint forces worldwide. It will be    increased with more time to collect and analyze
some years before the DISN and GCCS are fully         additional information. However, reality also
implemented. However, GCCS and DISN, as dis-          changes with time because of enemy and friendly
cussed in chapters 3 and 4, are already having a      actions and the environment. These changes then
major impact on the employment of Marine Corps        introduce additional information that requires pro-
CIS.                                                  cessing and analysis. At some point, the
                                                      commander must make decisions based on the
One of the most difficult C2 issues currently fac-    best information available. Although CIS provide
ing the Marine Corps is the requirement to            useful tools, the application of sound information
support a deployable Marine component HQ with         management principles is required to satisfy the
CIS personnel and equipment. The primary              commander’s information requirements.
source of support is the communications battal-
ion. The requirement to provide support to a          a. Information Quality
deployed Marine component HQ can have a sig-
nificant effect on the availability of CIS resources  Information quality and availability have a direct
to support the MAGTF. Resources required to           effect on the commander’s capability to effective-
support a component HQ is the subject of ongoing      ly C2 forces. Good information reduces confusion
study and will be addressed by the next Force         and contributes to situational awareness. Good in-
Structure Planning Group.                             formation is essential for effectively planning,
                                                      monitoring, and influencing operations. Informa-
CIS must be able to satisfy the C2 requirements of    tion quality cannot be taken for granted and must
the expeditionary battlefield. CIS must provide       be assessed with care.
MAGTF commanders and their staffs with the
tools necessary to rapidly collect, process, ana-     The following criteria are by no means all-inclu-
lyze, and exchange information in support of          sive, nor are they independent or all of equal
operations planning and execution. These systems      importance. It is counterproductive to seek com-
must make available the information needed,           plete information if the search for completeness
when it is needed, wherever it is needed on the       makes the information untimely. Irrelevant infor-
battlefield. Employment of these systems must         mation is worse than no information, and false
not adversely affect the freedom of action and        information can be disastrous, especially if it is
mobility of the MAGTF. They must be reliable,         part of an enemy deception.
flexible, and responsive. The success of the
MAGTF on the modern battlefield depends on de-        (1) Relevance. Information must apply to the
signing, planning, and employing CIS that satisfy     mission, task, or situation. Exhaustive informa-
the information needs of the MAGTF C2 process.        tion provided without filtering often detracts from
                                                      rather than enhances the commander’s ability to
1002. Information Management                          make timely, effective decisions. Furthermore the
                                                      transmission and processing of exhaustive infor-
Much of the information obtained for any endeav-      mation ties up CIS.
or or purpose is contradictory. This is especially


---

Communications and Information Systems _______________________________________________________________ 1-3

(2) Timeliness. Information must be available at     vides two definitions for information: (1) facts,
the appropriate place and time to be useful. Infor-  data, or instructions in any medium or form, and
mation management procedures and techniques          (2) the meaning that a human assigns to data by
must ensure the timely, unimpeded flow of rele-      means of the known conventions used in their
vant information. Well-planned and implemented       representation. It is important to understand that
CIS; clearly identified information requirements;    the term information, in its broadest sense, in-
effective collection, reporting, and dissemination;  cludes everything from raw data, perhaps a radar
and decisiveness by commanders and staff all         signal or a suspected enemy sighting by an obser-
contribute to timely information.                    vation post, to data that has been extensively
                                                     processed into useful information for a decision
(3) Accuracy. Information must be as accurate        maker. Ultimately, study and analysis of informa-
as possible. Although information systems can        tion leads to an understanding of the situation,
collect, transport, process, disseminate, and dis-   that is, situational awareness. Navy doctrinal pub-
play information, Marines must still evaluate the    lication (NDP) 6, Naval Command and Control,
information and make decisions as to its accuracy,   and MCDP 6, Command and Control, describe a
timeliness, and relevance.                           four-step cognitive process by which the transfor-
                                                     mation from raw data to situational awareness
(4) Completeness. Information may be useful          takes place. (See fig. 1-1 on page 1-4.) These four
only when it is complete. However, by the time       steps may be viewed as defining an information
complete information is obtained, it may no long-    hierarchy.
er be timely. If subordinates are aware of the
commander’s intent and critical information re-      (1) Data. The first step in the cognitive process is
quirements, they can provide only those              to collect raw data. The raw data can take many
information fragments needed for situational         forms: radar signals, intercepted radio signals,
awareness.                                           meteorological data from a weather balloon, or
                                                     even bar-coded logistic data scanned from the
(5) Objectivity. Information must be provided in     side of a container. This data may be transmitted
the most undistorted, factual, and unbiased way      in either analog or digital formats by telephone,
possible. Any interpretation should be highlighted.  radio, or facsimile; transferred between comput-
                                                     ers over local area networks (LANs); or sent by
(6) Usability. The display or presentation of in-    messenger as rolls of undeveloped film or perhaps
formation to the user must be understandable and     computer diskettes. In any event, to be useful, this
useful. Standard, clearly understandable informa-    raw data must be processed into a form that can
tion formats, symbols, and terms should be used      be understood by the ultimate user.
to exchange information and present it to users.
Information exchanged and presented in non-          (2) Processed Data. Processing data involves a
standard form causes delays in interpretation and    wide range of functionsCfrom decoding and
is more easily misunderstood, thereby leading to     translating intercepted communications to filter-
longer decision and execution cycles and, ulti-      ing and correlating sensor returns to developing
mately, to less reliable decisions.                  film. Processing includes placing information into
                                                     a form, such as a graphical display or a formatted
b. Information Defined                               message, that can be readily interpreted. Some
                                                     information will come to the MAGTF in pro-
In this publication, the term information refers to  cessed form and will not require further
all information that is needed to support the deci-  processing. Once data has been processed, it is re-
sionmaking process on the battlefieldCthat           ferred to as information in the cognitive process.
information required to execute the planning, de-    At this point some information may have immedi-
cision, and execution cycle in combat. Joint Pub     ate value for Marines in close contact with the
0-2, Unified Action Armed Forces (UNAAF), pro-       enemy. Such information is known as combat


---

1-4 ________________________________________________________________________________________________ MCWP 6-22

Figure 1-1. Information Hierarchy.

information. It is usually extremely perishable         awareness with limited and uncertain information
and should be disseminated to using units as rap-       under severe time constraints is the fundamental
idly as possible.                                       C2 challenge.

(3) Knowledge. In the next step, information is         c. Types of Information and
analyzed and evaluated. Through this process of         Commander’s Critical Information
analysis and evaluation comes knowledge. For            Requirements (CCIRs)
example, the analysis of intelligence information
helps build a picture of the enemy situation.           The information required for situational aware-
                                                        ness falls into three general categories:
(4) Understanding. The last step in the process is      information about the enemy, information about
the development of an understanding of the situa-       the environment, and information about friendly
tion based on the information available.                forces. The identification of CCIRs is a means to
Understanding is the result of applying human           focus and direct the collection and processing of
judgment based on individual experience, exper-         information in those categories. CCIRs are the
tise, and intuition to gain a full appreciation of the  information regarding the enemy and friendly ac-
battlefield. This understanding is situational          tivities and the environment identified by the
awareness and provides a sound basis for opera-         commander as critical to maintaining situational
tional decisions. It allows the commander to            awareness, planning future activities, and facili-
anticipate events and to uncover critical vulnera-      tating timely decisionmaking. Designation of
bilities for exploitation. As we strive to gain an      CCIRs reduces the volume of information to a
understanding of the situation, however, we must        manageable level and helps to ensure the accura-
recognize that time is working against us. We           cy, relevance, and timeliness of that information.
may not be able to gain complete situational            CCIRs comprise priority intelligence require-
awareness before acting. Developing situational         ments (PIRs), friendly force information


---

Communications and Information Systems _______________________________________________________________ 1-5

requirements (FFIRs), and essential elements of        what information is needed to support the plan-
friendly information (EEFIs). Clearly defining         ning, decision, execution and assessment cycle.
these information requirements is one of the most
difficult and important tasks of command. CCIRs        (3) EEFIs. EEFIs are specific facts about friendly
will not only govern the quantity and quality of       intentions, capabilities, and activities needed by
the information available to support decisionmak-      adversaries to plan and execute effective opera-
ing, but also have a direct effect on the workload     tions against our forces. These EEFIs may be
of the staff and subordinate units.                    viewed as representing the opposing command-
                                                       er’s PIRs. Identification of the EEFIs is key to
(1) PIRs. PIRs are intelligence requirements as-       planning effective INFOSEC, operations security,
sociated with a decision that will affect the overall  and other force protection operations.
success of the command’s mission. PIRs include
both information about the enemy and informa-          d. Flow of Information
tion about the environment. Information about
both enemy capabilities and intentions is critical     The goal of information management is to facili-
to allow commanders to anticipate and analyze          tate a rapid, unconstrained flow of information
possible enemy courses of action (COAs). Infor-        throughout an organization from its source
mation on the environment includes information         through intermediate collection and processing
on the weather, the terrain, the local population,     nodes to its delivery to the ultimate user. CCIRs
the local communications and transportation in-        serve as a necessary filter to ensure that only rele-
frastructures, and a host of other factors that may    vant information is delivered, thereby preventing
affect the conduct of military operations. Through     information overload. Information must flow in
identification of PIRs, commanders ensure that         all directions to support a common picture of the
limited intelligence resources are directed to ob-     battlefield among all unitsCsenior, subordinate,
taining intelligence information that is essential     adjacent, supporting, and supported alike. A flexi-
for decisionmaking.                                    ble, responsive MAGTF C2 architecture is
                                                       required that pushes relevant, time-sensitive in-
(2) FFIRs. To complete the picture of the situa-       formation to the user while allowing the user to
tion, the commander requires information on            pull additional detail as required. This C2 archi-
friendly forces. FFIRs are the information the         tecture consists of the C2 facilities, information
commander needs about friendly forces to be able       systems, and communications networks that are
to develop plans and make effective decisions.         described in chapters 2, 3, 4, and 5.
Depending on the circumstances, information on
unit location, composition, readiness, personnel       A number of networking techniques are widely
status, and logistic status could become an FFIR.      used to improve the flow of information both with-
Just as it is essential for the commander to use       in and between Marine Corps organizations. These
PIRs to identify the most important requirements       techniques support improved situational aware-
for information on the enemy, it is also essential     ness and collaborative planning. Networking also
for the commander to specify what critical friend-     offers tremendous opportunities for “electronic
ly information is required to support planning and     reachback.” The concept of electronic reachback
execution. The commander must have real-time           may reduce the size of deployed staffs through the
or near real-time information on the location, sta-    use of specialistsCmilitary, government civilian,
tus, and capabilities of friendly forces. However,     or consultantCwho never deploy. The Marine
FFIRs must be prioritized to limit and focus the       Corps Chemical/Biological Incident Response
collection and processing effort. It is easy to over-  Force (CBIRF) provides an excellent example of
burden subordinate units, as well as to overload       this approach.
communications networks, with requests for non-
essential information. FFIRs help commanders,          The most widely used networking technique is e-
staffs, and subordinate units understand precisely     mail. E-mail provides a convenient means for


---

1-6 ________________________________________________________________________________________________ MCWP 6-22

exchanging information between both organiza-        secure, timely, flexible, interoperable, and
tions and individuals and is a highly effective      survivable.
means of communication. E-mail supports rapid
dissemination of time-critical information be-       a. Reliability
tween a HQ and subordinate organizations and
across staff sections. Organizational e-mail has     CIS should be available when needed and per-
replaced much of the information traffic that was    form as intended, with low failure rates and few
previously sent over the Automatic Digital Net-      errors. Reliability is also attained by standardizing
work (AUTODIN). E-mail permits a single user         equipment and procedures, building necessary re-
to disseminate information to one or several users   dundancy, establishing effective logistic support,
simultaneously. However, in a deployed environ-      and protecting against computer viruses, electron-
ment, the potential to overload the                  ic jamming, and deception. Systems should
communications system requires a disciplined ap-     perform reliably aboard ships and aircraft, in gar-
proach to the establishment and use of e-mail        rison, and in austere field environments.
accounts.
                                                     b. Security
Other networking techniques support the concept
of information pull and have the potential to re-    CIS should provide security commensurate with
duce the load on the communications network and      the user’s requirements and with the vulnerability
thereby improve the information flow. These          of the transmission media to interception and ex-
techniques include using home pages and news-        ploitation. Security is achieved by using
groups as well as shared network drives on a         appropriate protection and cryptographic systems,
LAN. However, posting information to a news-         using transmission security techniques, and edu-
group or a home page, or updating a file on a        cating and training personnel in security
LAN server, is no guarantee of receipt by the in-    procedures.
tended audience.
                                                     c. Timeliness
Pull techniques are generally unacceptable for the
promulgation of time-sensitive critical informa-     CIS should process and transfer information be-
tion such as fragmentary orders or warning           tween decision makers rapidly enough to
orders. Although brief messages could be sent in-    maintain a high tempo of operations and ensure
dicating that the order had been posted and          that our decision and execution cycle remains
requiring addressees to acknowledge and comply,      ahead of any potential adversary’s.
the order itself normally would not have been
lengthy enough to make this an efficient ap-         d. Flexibility
proach. On the other hand, when selective access
to information in large databases is required to     CIS should be capable of being reconfigured
support an analysis, pull techniques are more effi-  quickly to respond to a rapidly changing environ-
cient than push techniques.                          ment. Flexibility can be obtained through system
                                                     design or by using commercial facilities, mobile
1003. CIS Characteristics                            or transportable systems, or prepositioned
                                                     facilities.
It would be impossible to provide adequate C2
support on the modern battlefield without CIS.       e. Interoperability
This publication defines CIS as any system whose
primary functions are to collect, process, or ex-    CIS should enable information to be exchanged
change information. CIS should be reliable,          among all of the commanders and forces involved


---

Communications and Information Systems _______________________________________________________________ 1-7

in an operation. MAGTF CIS also should possess          However, overall information management policy
the interoperability required to ensure information     and procedures will be under the staff cognizance
exchange in joint and multinational operations          of the chief of staff (C/S) or the executive officer
and in operations with other Government                 (XO).
agencies.
                                                        a. Commander
f. Survivability
                                                        The commander is responsible for the employ-
Survivability is all measures taken to prevent dis-     ment of CIS within the command. Although the
ruption of CIS by enemy interference or natural         authority to plan and employ communications and
disaster. Survivability can be enhanced by the dis-     information systems may be delegated, ultimate
persal and protection of key nodes, physical and        responsibility for CIS planning and employment
electromagnetic hardening, and redundancy of            remains with the commander. The commander
communications paths and information process-           must provide adequate guidance, including neces-
ing nodes.                                              sary assumptions and constraints, to support the
                                                        development of CIS estimates, plans, and orders.
1004. CIS Responsibilities                              The commander is also responsible for providing
                                                        the focus for information management throughout
The officer military occupational specialties of        the organization and participates directly in the
2502, communications officer, and 4002, data pro-       information management process by establishing
cessing officer, have been merged into a single         the CCIRs discussed in paragraph 1002c.
military occupational specialty, 0602, CIS officer
(CISO). Responsibility for this functional area has     b. Communications and Information
been assigned to the G-6/S-6. To reflect this as-       Systems Officer
signment of responsibility, this publication refers
to the G-6/S-6 as the CISO, rather than communi-        The CISO is responsible to the commander for all
cations officer or communications-electronics           matters concerning the planning and employment
officer. Since the technology associated with such      of CIS within the command. As a general or exec-
systems and networks continue to evolve, specific       utive staff officer, the CISO serves as an advisor,
responsibilities continue to evolve as well. Al-        planner, supervisor, and coordinator. Specific re-
ready it is clear that responsibilities for installing  sponsibilities include—
and operating information systems will be shared
between CIS specialists and functional area users.      (1) Providing the commander and other staff of-
For example, the tactical combat operations             ficers with—
(TCO) system will be operated by personnel from
the G-3/S-3. However, they will be assisted in in-      q Advice on information management policies
stalling the system and interfacing the system to          and procedures.
LANs and wide area networks (WANs) by CIS
personnel.                                              q Estimates of the supportability of courses of ac-
                                                           tion (COAs).
Just as important as the responsibility for install-
ing, operating, and maintaining CIS is the              q Estimates of requirements for CIS re-
responsibility for the management of the informa-          sourcesCpersonnel, equipment, supplies, and
tion processed and exchanged by those systems.             facilities.
Each staff section will be responsible for the qual-
ity of the information in the databases of the          q Recommendations for the allocation and use of
systems that support that particular staff section.        CIS resources.

                                                        q Recommendations for CIS training for the
                                                           command.


---

1-8 ________________________________________________________________________________________________ MCWP 6-22

q Recommendations on the location, echelon-            c. Unit Information Management
   ment, and displacement of the command post          Officer
   (CP) and C2 facilities.
                                                       The unit information management officer is a spe-
q Advice on operational aspects of information         cial staff officer operating under the staff
   systems security (INFOSEC). See chap. 7 for         cognizance of the C/S or XO. If an information
   detailed G-6/S-6 responsibilities.                  management officer is not designated, then this
                                                       duty is the responsibility of the C/S or XO. The
(2) Preparing CIS plans, orders, and standing          information management officer is responsible for
operating procedures (SOPs) to implement the           establishing the policy and procedures for infor-
commander’s policies and decisions on CIS              mation management within the command.
employment.                                            Responsibilities include:

(3) Assisting the staff in the area of CIS for the     (1) Coordination, with the assistance of the in-
preparation of studies, estimates, plans, orders, in-  formation management officers of each staff
structions, and reports.                               section and subordinate units, of information
                                                       management efforts throughout the organization.
(4) Ensuring compliance with the commander’s
orders and instructions by supervising—                (2) Development and publication of the infor-
                                                       mation management plan. The information
q Employment of CIS personnel.                         management plan establishes policies and proce-
                                                       dures for ensuring the quality and flow of
q Installation, operation, and maintenance of          information within the organization.
   communications networks.
                                                       (3) Coordination of the CCIR process: the nomi-
q LAN and WAN management, including Inter-             nation of CCIRs; approval of CCIRs by the
   net Protocol (IP) address and routing manage-       commander and collection and reporting of
   ment.                                               CCIRs by the staff; dissemination of CCIRs to
                                                       higher, adjacent and subordinate commands; and
q Technical support for functional users in the in-    maintenance of CCIRs.
   stallation, operation, and maintenance of infor-
   mation systems hardware and common user             (4) Development and implementation, in close
   software.                                           coordination with the CISO and other staff princi-
                                                       pals and subordinate units’ information
q Communications systems training and, in coor-        management officers, of effective information
   dination with functional users, information sys-    dissemination techniques.
   tems training.
                                                       (5) Development of training programs on infor-
q Supply and maintenance of CIS.                       mation management procedures.

q Compliance with SOPs and interoperability            (6) Coordination with the unit security manager
   standards.                                          in the development and implementation of infor-
                                                       mation security procedures.
q CIS security in coordination with the other staff
   sections.                                           (7) Coordination with the CISO on LAN man-
                                                       agement and networking issues, communications
(5) Coordinating CIS matters with cognizant            channels prioritization, and traffic management.
staff sections and with staffs of other units, as
required.

(6) Establishing CIS liaison with senior, subor-
dinate, adjacent, supported, and supporting units.


---

Communications and Information Systems _______________________________________________________________ 1-9

d. Staff Section Information                           (2) Serving as the configuration manager for in-
Management Officer                                     formation systems supporting the functional area.

Each staff section should appoint an information       (3) Conducting routine information system ad-
management officer. The staff section informa-         ministration (assigning user identification,
tion management officer is responsible for—            passwords, and privileges; performing data/file
                                                       storage and management; conducting system
(1) Coordinating the internal and external infor-      backups).
mation flow for the staff section and its
integration with the information flow of other         (4) Coordinating with the G-6/S-6 to ensure that
staff sections, including identifying and prioritiz-   adequate hardware, software, trained personnel,
ing information management requirements.               and procedures are in place before implementing
                                                       a new system or system modification.
(2) Providing the unit information management
officer with input to the information management       (5) Coordinating with the G-6/S-6 to develop
plan.                                                  and maintain user training programs for CIS.

(3) Coordinating information management train-         (6) Identifying to the G-6/S-6 information sys-
ing for section personnel with the unit                tem support requirements.
information officer.
                                                       (7) Identifying to the G-6/S-6 specific commu-
(4) Coordinating the identification and process-       nications requirements, including requirements to
ing of all CCIRs within the staff section’s area of    interface with other information systems and po-
responsibility (AOR).                                  tential interface problems.

e. Functional User Responsibilities                    (8) Complying with applicable CIS security
                                                       measures.
On the modern battlefield, it is essential that func-
tional users of information be able to configure       (9) Reporting malfunctions and outages and co-
and operate the information systems supporting         ordinating with the G-6/S-6 to restore service.
their functional area. Such an ability facilitates
increased speed and operator knowledge in estab-       (10) Designating an information management of-
lishing a distributed network. It also ensures that    ficer for the staff section.
functional area users are able to best exploit and
control the capabilities of systems that support       f. Communications Between
their needs. Functional users include every staff      Commands
section that is supported by CIS. Consequently,
all staff principals have functional user responsi-    The responsibility for establishing communica-
bilities for the functional areas over which they      tions between units must be clearly delineated.
have staff cognizance. For example, the G-3/S-3        These responsibilities are a cornerstone of com-
has functional user responsibilities for TCO.          munications doctrine. However, when supporting
Functional user responsibilities include—              combat operations, unit communications capabili-
                                                       ties may be destroyed, and responsibility may
(1) Serving as the primary point of contact, both      become unclear or irrelevant. Flexibility, common
internal and external to the command, for issues       sense, initiative, cooperation, and mutual assis-
affecting information systems supporting the           tance must prevail in these instances.
functional area.


---

1-10 _______________________________________________________________________________________________ MCWP 6-22

Communications between a senior and subordi-           Communications between a unit and an attached
nate unit are the responsibility of the senior         unit are the responsibility of the commander of the
commander.                                             unit to which the attachment is made.

Communications between adjacent units are the          g. G-6/S-6 Staff Cognizance
responsibility of the first common senior
commander.                                             Communications units and detachments operate
                                                       under the staff cognizance of the supported unit’s
Communications between a supporting and sup-           G-6/S-6. The Marines assigned to these units, in
ported unit are the responsibility of the supporting   concert with personnel assigned to G-6/S-6 sec-
unit commander.                                        tions and functional area users, are responsible for
                                                       employing CIS to support C2. Communications
Communications between a reinforcing and rein-         units and the detachments they deploy are the key
forced unit are the responsibility of the reinforcing  elements in planning, installing, operating, and
unit commander.                                        maintaining an effective CIS network. See chap-
                                                       ter 2 for responsibilities.


---

      Chapter 2

Organizations

Section I

USMC Organizations

Marine Corps CIS are employed to support the         operational plans. MARFORLANT, headquar-
command and control of Marine forces. To under-      tered in Norfolk, VA, is assigned as the Marine
stand the requirements for CIS support, it is nec-   Service component for the U.S. Atlantic Com-
essary to understand the organization and mission    mand, the U.S. Southern Command, and the U.S.
of those forces. Marine forces are organized,        European Command. MARFORPAC, headquar-
trained, and equipped under a total force concept    tered at Camp Smith, HI is assigned as the Marine
to conduct a wide range of expeditionary opera-      Service component for the U.S. Pacific Command
tions. The Marine Corps total force consists of      and the CINC United Nations Command/Com-
three components—the operating forces, the Re-       bined Forces Command.
serves, and the supporting establishment. The
operating forces are an expeditionary “force-in-     2102. Marine Corps Forces
readiness,” providing forward presence, crisis re-
sponse, and rapid power projection capabilities to   Marine Corps forces (MARFOR) is the designa-
warfighting commanders in chief (CINCs). The         tion given all Marine component commands. A
Marine Corps Reserve is an integral part of the to-  Marine component command is a command con-
tal force team, is continuously training and oper-   sisting of all MARFOR assigned to a joint force.
ating with the active forces, and is fully prepared  There are two levels of Marine components. A
to augment or reinforce in times of crisis. The      Marine Service component is assigned to a com-
supporting establishment is responsible for re-      batant commander or a subordinate unified com-
cruiting, training, equipping, and sustaining the    mander. (The two standing Marine Service
force—Active and Reserve.                            components are described in paragraph 2101.)
                                                     The other level of componency is the Marine
2101. Operating Forces                               component assigned to a JTF. A Marine Service
                                                     component may consist of one or more MAGTFs,
The two major components of the operating forc-      as well as other required theater-level organiza-
es are the Marine Corps Forces, Atlantic (MAR-       tions such as a Marine logistic command. Nor-
FORLANT), and Marine Corps Forces, Pacific           mally, a JTF Marine component will include only
(MARFORPAC). These two forces constitute the         one MAGTF and no additional Marine organiza-
expeditionary combat power of the Marine Corps.      tions. A MAGTF commander may be dual-desig-
The other two elements of the operating forces are   nated as the Marine Service or JTF Marine
the Marine Corps Security Forces at naval instal-    component commander. Unless higher authority
lations and the Marine Security Guard Battalion      establishes otherwise, the Marine component
with detachments at embassies and consulates.        commander commands all assigned MARFOR
Consistent with the Goldwater-Nichols Defense        and exercises operational or tactical control
Reorganization Act and Joint Pub 0-2, each com-      (TACON) of other assigned or attached forces.
batant CINC is assigned a Marine Service compo-      The Marine component commander deals directly
nent for planning and execution of various           with the joint force commander (JFC) in matters


---

2-2 ________________________________________________________________________________________________ MCWP 6-22

affecting assigned MARFOR. The Marine com-            2103. Marine Air-Ground Task
ponent commander commands, trains, equips, and        Forces
sustains all Marine forces. Combat operations are
executed by assigned MAGTFs. When designated          Marine operating forces are further organized into
by the joint commander, a Marine component            MAGTFs. MAGTFs are organized, equipped, and
commander (at either the Service or JTF level)        trained to conduct forward-presence and crisis-re-
may also serve as a functional component com-         sponse missions anywhere in the littoral areas of
mander. A functional component command is a           the world. The MAGTF is capable of conducting
command that is normally composed of forces of        expeditionary operations across the full spectrum
two or more Military Departments and that may         of conflict, including forcible entry by amphibi-
be established to perform particular operational      ous assault. The MAGTF is also capable of a
missions. Functional component commanders are         broad range of noncombat operations ranging
normally selected from Service component com-         from noncombatant evacuations to disaster relief.
manders. Normally the Service component com-          Because MAGTFs are task-organized, they differ
mander providing the preponderance of the             in organization. However, all MAGTFs share the
functional capability in question is designated the   same basic structure.
functional component commander. A Service
component commander designated as a functional        a. Core Elements
component commander retains Service compo-
nent responsibilities. A Marine component com-        Each MAGTF has four core elements: a com-
mander is more likely to be designated a              mand element (CE), a ground combat element
functional component commander in smaller             (GCE), an aviation combat element (ACE), and a
scale contingencies where MARFOR constitute a         combat service support element (CSSE). This
large portion of the joint force. The Marine com-     structure is carefully designed to provide opera-
ponent commander could be designated as the           tional flexibility and coordinated execution, thus
joint force maritime component commander, joint       maximizing the contribution of each element to
force land component commander, or joint force        the overall mission.
air component commander.
                                                      (1) CE. The CE is the MAGTF HQ. It is task-or-
MCWP 0-1.1, Componency, describes three pos-          ganized to provide the command and control ca-
sible staff organizations for the component HQ:       pability necessary for effective planning and
                                                      execution of operations. In addition to the HQ
q One commander and one staff—A single com-           staff, it includes units and detachments that pro-
   mander is designated as both the Marine com-       vide communications, information systems, and
   ponent and MAGTF commander. Likewise a             intelligence support for the MAGTF.
   single staff executes both component and
   MAGTF functions.                                   (2) GCE. The GCE is task-organized to conduct
                                                      ground operations to support the MAGTF mis-
q One commander and two staffs—Again a sin-           sion. It is formed around an infantry organization
   gle commander serves as both component and         reinforced with artillery, reconnaissance, armor,
   MAGTF commander; however, the command-             engineer, and other forces as needed. The GCE
   er is supported by two separate staffs.            can vary in size and composition from a rein-
                                                      forced infantry battalion to one or more Marine
q Two commanders and two staffs—This organi-          divisions. During amphibious operations, it
   zation provides for two separate commanders,       projects ground combat power ashore by using
   each with a dedicated staff. Although this is the  transport helicopters from the ACE, organic as-
   most effective arrangement, it is also the most    sault amphibious vehicles, and Navy landing
   costly in terms of personnel, equipment, and fa-   craft.
   cilities.


---

Communications and Information Systems _______________________________________________________________ 2-3

(3) ACE. The ACE is task-organized to perform        the full spectrum of conflict, including amphibi-
all or part of the six functions of Marine aviation  ous assault and sustained combat operations
in support of MAGTF operations. During am-           ashore. A MEF can range in size from less than
phibious operations, it can vary in size and com-    one to multiple divisions and aircraft wings, to-
position, from a reinforced aviation squadron or     gether with one or more FSSGs. As described
detachment, with appropriate air command and         above, there are three standing MEFs. Each of
control and combat service support (CSS), to one     these MEFs consists of a permanent CE and one
or more Marine aircraft wings (MAWs).                Marine division, MAW, and FSSG. Each forward
                                                     deploys MEUs on a continuous basis.
(4) CSSE. The CSSE is task-organized to provide
the full range of CSS capabilities necessary to      The size and composition of a deployed MEF can
support and sustain MAGTF operations. During         vary greatly depending on the mission, from ele-
amphibious operations, it may vary in size and       ments consisting of less than a full division, wing,
composition from a task-organized CSS detach-        or service support group to elements consisting of
ment to one or more force service support groups     more than one. A MEF can deploy with forces at-
(FSSGs).                                             tached from the other standing MEFs as well as
                                                     from the Reserves. With accompanying supplies
b. Types of MAGTFs                                   for 60 days, MEFs are capable of both amphibi-
                                                     ous operations and sustained operations ashore.
All MAGTFs are expeditionary forces that are         With appropriate augmentation, especially in the
task-organized for a specific mission. MAGTFs        area of C2 capability, the CE is capable of per-
vary greatly in size and composition according to    forming the mission of a JTF HQ, and the MEF
the assigned mission. To provide a frame of refer-   can serve as the nucleus of the JTF. The CIS re-
ence, Marine Corps doctrine categorizes              quirements associated with such taskings are sig-
MAGTFs into Marine expeditionary forces              nificant.
(MEFs), Marine expeditionary units (MEUs), and
special purpose MAGTFs (SPMAGTF).                    A MEF normally deploys in echelon and desig-
                                                     nates its lead element as the MEF (forward) (MEF
(1) MEFs. Most of the Marine Corps operating         [Fwd]). The deployment of the MEF (Fwd) does
forces are assigned to the three standing MEFs:      not automatically trigger the deployment of the
                                                     entire force. This would occur only if the crisis is
MARFORPAC               MARFORLANT                   large enough to require the entire MEF.

I MEF       III MEF          II MEF                  (2) MEUs. The MEU is normally composed of a
                        Based in North and           reinforced infantry battalion, a reinforced helicop-
Based in    Forward     South Carolina               ter squadron (which may include vertical/short
California  based in                                 takeoff and landing (V/STOL) attack aircraft), a
            Okinawa,                                 MEU service support group, and a CE. The MEU
            mainland                                 is commanded by a colonel and deploys with 15
            Japan, and                               days’ worth of accompanying supplies. MAR-
            Hawaii                                   FORLANT and MARFORPAC routinely forward
                                                     deploy MEUs aboard amphibious shipping in the
These standing MEFs can deploy as a MEF (nor-        Mediterranean Sea, Indian Ocean, Persian Gulf,
mally in echelon) or can deploy subordinate units    and Western Pacific. Deployed as part of an am-
(task-organized for assigned missions). All three    phibious ready group, the MEU provides a com-
MEFs provide MEUs for service afloat.                batant or operational commander with a seabased
                                                     rapid-reaction force for a wide variety of
The MEF is the principal Marine Corps warfight-      missions. The MEU has a limited forcible entry
ing organization, particularly for larger crises or  capability and can facilitate the employment of
contingencies. Normally commanded by a lieu-
tenant general, it is capable of operations across


---

2-4 ________________________________________________________________________________________________ MCWP 6-22

follow-on forces, including joint and combined       Marine Corps Recruiting Command, the Marine
forces as well as a MEF. Before deployment, the      Corps Combat Development Command, the
MEU undergoes a 6-month training program fo-         Marine Corps Systems Command, and Headquar-
cusing on selected maritime special operations       ters, U.S. Marine Corps. The supporting estab-
and culminating in the designation of the unit as    lishment’s contributions are vital to the overall
“special operations capable” (MEU[SOC]).             combat readiness of the Marine Corps. Further-
                                                     more, because of the interconnected nature of the
(3) SPMAGTFs. A SPMAGTF may be formed to             CIS support infrastructure, the supporting estab-
conduct a specific mission that is limited in scope  lishment plays a direct role in supporting the com-
and focus and often in duration. A special purpose   mand and control of all MAGTFs. This support is
MAGTF may be any size, but normally it is a rel-     necessary to effectively deploy and implement
atively small force—the size of a Marine expedi-     modern information technology in support of the
tionary unit or smaller—with narrowly focused        MAGTF both in garrison and when deployed. In
capabilities chosen to accomplish a limited mis-     particular, the Marine Corps Network Operations
sion. Common missions of a special purpose           Center and the Marine Corps Tactical Systems
MAGTF include raids, peacekeeping, noncombat-        Support Activity (MCTSSA) provide essential
ant evacuation, disaster relief, and humanitarian    support to the operating forces in the employment
assistance.                                          and operation of CIS.

2104. Marine Corps Forces                            The Marine Corps Network Operations Center,
Reserves                                             located in Quantico, VA, acts as the focal point
                                                     for technical support of Marine Corps data com-
Rapid force expansion is possible through the ac-    munications networks. This activity provides as-
tivation of the Marine Corps Forces Reserve          sistance in planning for and maintaining data
(MARFORRES). The Reserve, like the active            communications networks for the MAGTF by co-
forces, consists of a balanced combined-arms         ordinating with external agencies such as DISA;
team with ground, aviation, and CSS units. Orga-     advising operational planners; providing software
nized under the Commander, Marine Corps Forc-        support, including contact teams; and providing
es Reserve, units are located at 191 training        Marine Corps-wide network operations manage-
centers in 46 states, Puerto Rico, and the District  ment.
of Columbia. The Marine Corps Forces Reserve is
closely integrated with the active component un-     MCTSSA, located at Camp Pendleton, CA, pro-
der the Marine Corps total force concept. The Re-    vides support to the operating forces for the oper-
serves provide individuals and specific units to     ation and maintenance of fielded CIS. As the
augment and reinforce active capabilities.           designated post-deployment software support ac-
                                                     tivity for most Marine Corps CIS, MCTSSA re-
2105. The Supporting                                 ceives trouble reports, analyzes problems, and
Establishment                                        takes corrective action. The Fleet Marine Force
                                                     (FMF) Support Division of MCTSSA provides
The supporting establishment consists of 16 ma-      direct continuous liaison with the operating forces
jor bases, training activities, formal schools, the  to identify and resolve problems and provides
                                                     training and operational support for exercises and
                                                     actual contingencies.


---

Communications and Information Systems _______________________________________________________________ 2-5

        Section II

CIS Organizations

Marines dedicated to using CIS are organized by     C2 functions are exercised through the battalion
table of organization (T/O) into the units de-      commander and the executive staff. The comm
scribed in the following subparagraphs. The T/O     battalion consists of the HQ company, a service
units may deploy and be employed as a complete      company, three direct support comm companies,
unit or they may provide task-organized detach-     and a general support company. Elements of the
ments to support elements of a MAGTF. These         comm battalion may be employed separately as
units and detachments operate under the staff cog-  task-organized detachments to support organiza-
nizance of the G-6/S-6 of the supported unit. Sep-  tions smaller than a MEF CE, or the entire battal-
arate units and detachments will be found only at   ion may be employed to support larger MAGTF
higher echelons. At regiments and below, the        CEs. The HQ company includes the structure nec-
communications unit will be an integral part of     essary to provide detachments to support two
the HQ, and the communications unit commander       MEU CEs.
may also serve as the S-6. The Marines assigned
to these units, in concert with personnel assigned  The comm battalion will normally deploy as a
to G-6/S-6 sections and functional area users, en-  task-organized unit or will deploy task-organized
sure that an effective CIS network is planned, in-  detachments in support of MAGTF CEs. Upon
stalled, operated, and maintained.                  notification, and before deployment of a MEF
Communications units and the detachments they       CE, the battalion will task organize to support the
deploy are the key element in providing CIS capa-   deployment. Upon notification, and before de-
bility for the MAGTF elements that they support.    ployment of a MEF(Fwd) CE or a component
Missions, tasks, and concepts of organization and   HQ, a direct support comm company will be task
employment of these units are identified in their   organized to support the deployment. The
T/Os and synopsized in this section.                MAGTF CE G-6/S-6 exercises staff cognizance
                                                    over MAGTF communications; to facilitate sys-
2201. Communication Battalion                       tem planning and engineering, the battalion con-
                                                    ducts concurrent planning with the Component
The mission of the comm battalion is to provide     MAGTF G-6/S-6.
communications support to a MARFOR compo-
nent HQ; a MEF CE or a MEF(Fwd) CE; a com-          a. HQ Company
ponent HQ deployed simultaneously with a MEF
CE and a MEF(Fwd) CE; or two MEF(Fwd) CEs.          The mission of the HQ company is to provide or-
A further mission is to provide support to three    ganic command, administration, logistic, and oth-
MEU CEs. The battalion provides—                    er required support for a comm battalion as well
                                                    as to support system planning and engineering for
q CE communications for the supported CE:           and operational control of MAGTF communica-
   MEU, MEF(Fwd), MEF, and component HQ.            tions networks as required. The company—

q Communications connectivity between the sup-      q Plans and engineers CIS for the MAGTF CEs,
   ported CE and senior, adjacent, and subordi-        as required.
   nate HQs.
                                                    q Installs, operates, and maintains network con-
q The supported CE with a Naval Telecommuni-           trol facilities and system control facilities for
   cations Systems entry and/or, as appropriate,       the component HQ and MAGTF CEs of
   entry into the Defense Communications Sys-          MEF(Fwd) size and larger.
   tem.


---

2-6 ________________________________________________________________________________________________ MCWP 6-22

q Installs, operates, and maintains field message     Defense Communications System as required.
   centers, radio links, and tactical switchboard/    The company—
   telephone systems for two MEU CEs.
                                                      q Installs, operates, and maintains the MEF digi-
The company is organized into functional group-          tal transmission backbone by using cable and
ings to provide for a battalion and company HQ           multichannel radio (MCR) equipment.
and support of the primary mission and tasks.
The company normally collocates with the battal-      q Installs, operates, and maintains digital switch-
ion HQ and operates in support of the battalion.         es to provide secure and nonsecure voice, fac-
As required, the various sections can be assigned        simile, message, and data service to the MEF
to task-organized comm battalion detachments in          CE CPs.
support of deployed MAGTFs.
                                                      q Interfaces the component and MEF CE CIS
b. Direct Support Company                                with national systems, the Naval Telecommu-
The mission of the direct support company is to          nications System, commercial telecommunica-
install, operate, and maintain the communications        tions systems, and senior (CINC/JTF),
system for a MEF CE, MEF(Fwd) CE, or compo-              adjacent, and subordinate systems and net-
nent HQ. The company—                                    works as required.

q Installs, operates, and maintains communica-        q Installs, operates, and maintains tactical wide
   tions center facilities for the supported CE/HQ.      area networks (WANs)/local area networks
                                                         (LANs) for MAGTF CEs of MEF(Fwd) size or
q Maintains radio stations on CIS, administra-           larger.
   tive, logistic, and other radio nets as required.
                                                      The company is organized into a company HQ, a
q Installs, operates, and maintains switchboard       switching platoon, a satellite comm platoon, and a
   and telephone services for the supported CE/       terrestrial comm platoon and operates under the
   HQ.                                                direct control of the comm battalion. When oper-
                                                      ating in support of the MEF CE, the company de-
The direct support comm company is organized          ploys and collocates with the comm battalion.
into a company HQ and three platoons organized        When in support of a MEF(Fwd) CE or compo-
along functional lines, tailored to support the pri-  nent HQ, detachments from the company will
mary mission and tasks listed above. The direct       augment a task-organized direct support comm
support comm company operates under the direct        company to provide a switched communications
control of the comm battalion. When operating in      hub for an area communications network. Simul-
support of a MEF CE, the company deploys and          taneously, ground mobile forces (GMF) satellite
collocates with the comm battalion. When in sup-      communications teams and terrestrial transmis-
port of a MEF(Fwd) CE or component HQ, the            sion teams, as required, deploy as attachments to
company, with reinforcements, is capable of de-       MSCs to connect the MEF CE with subordinate
ploying as a separate unit.                           commands.

c. General Support Communications                     d. Service Company
Company
The mission of the general support comm compa-        The mission of the service company is to provide
ny is to install, operate, and maintain the compo-    transportation, maintenance, communications-
nent HQ, MEF CE, and MEF(Fwd) CE message              electronics maintenance, materiel handling equip-
and voice switches and links to JTF HQ, major         ment, materiel handling equipment maintenance,
subordinate commands (MSCs), adjacent units,          and electrical power distribution services for a
the Naval Telecommunications System, and the          comm battalion. The company—

                                                      q Provides heavy transportation support to oper-
                                                         ating companies as required.


---

Communications and Information Systems _______________________________________________________________ 2-7

q Provides communications-electronics equip-         q Assists in the system planning and engineering
   ment maintenance support to operating compa-         of ACE communications and install, operate,
   nies as required.                                    and maintain expeditionary communications to
                                                        support the command and control of the MEF
q Provides primary electrical power distribution        ACE.
   and service for the battalion.
                                                     q Provides operational systems control centers,
q Provides materiel handling support to the bat-        as required, to coordinate communications
   talion.                                              functions internally and externally to the ACE.

q Executes combat trains in support of the battal-   q Provides maintenance support for ground-com-
   ion.                                                 mon communications equipment in the MAW.

The service company is organized into a company      q Provides the digital backbone communications
HQ and three platoons: a motor transport platoon        support for the ACE HQ, forward operating
to provide the operation and maintenance of             bases, and Marine air command and control
heavy motor transportation equipment organic to         system (MACCS) agencies for up to two air-
the battalion; a communications-electronics main-       fields per detachment. The MACCS agencies
tenance platoon capable of performing third-eche-       include the tactical air command center
lon maintenance on digital switches, telephones,        (TACC), tactical air operations center (TAOC),
cables, computers, cryptographic equipment, and         direct air support center (DASC), early warn-
radio equipment, including high frequency (HF),         ing/control (EW/C) sites, low altitude air de-
very high frequency (VHF), ultra high frequency         fense (LAAD) teams, and Marine air traffic
(UHF), super high frequency (SHF), and extreme-         control detachments (MATCD).
ly high frequency (EHF) single and multichannel
assets organic to the operating companies of the     q Provides tactical, automated switching and
comm battalion; and an engineer platoon that in-        telephone services for the ACE HQ and TACC.
stalls, operates, and maintains power distribution,
air conditioning, refrigeration systems, and mate-   q Provides electronic message distribution for the
riel handling equipment organic to the comm bat-        ACE HQ, primary MACCS agencies, and ten-
talion.                                                 ant units.

When the comm battalion is deployed as a unit,       q Provides external, single-channel radio (SCR),
the service company normally collocates with the        MCR, and radio retransmission communica-
battalion HQ and provides support. As required,         tions support for ACE operations as required.
personnel and equipment from the service compa-
ny can be assigned as part of task-organized         q Provides deployed WAN and deployed LAN
comm battalion detachments.                             server support for the ACE HQ and primary
                                                        MACCS agencies.
2202. Marine Wing
Communication Squadron                               q Provides the support cryptographic site for all
                                                        ground-common and MACCS-assigned com-
The mission of the Marine wing communication            munications security equipment within the
squadron (MWCS) is to provide expeditionary             ACE.
communications for the ACE of a MEF, including
communications support for the deployment of         The squadron consists of a HQ element and one
task-organized elements of a MAW. The squad-         or two detachments. The squadron provides com-
ron—                                                 munications support for the ACE HQ and TACC.
                                                     Each detachment may be independently deployed
                                                     to provide external communications for up to two
                                                     airfields and four forward bases.


---

2-8 ________________________________________________________________________________________________ MCWP 6-22

2203. Communications                                  local telephone and multichannel lines. Multi-
Company, HQ Battalion,                                channel communications service will be disrupted
Marine Division                                       during displacement of the division HQ.

The mission of the comm company is to install,        2204. Communications
operate, and maintain the communications system       Company, HQ and Service
for a Marine division HQ. The company—                Battalion, FSSG

q Installs, operates, and maintains communica-        The mission of the comm company is to provide
   tions center facilities for the division HQ.       communications support to the HQs of the FSSG,
                                                      subordinate battalions, and CSSEs. The compa-
q Maintains radio stations on CIS, administra-        ny—
   tive, logistic, and other radio nets as required.
                                                      q Provides communications support to the FSSG
q Installs, operates, and maintains switchboard          HQ/force CSS area and other CSSEs estab-
   and telephone services for the division HQ.           lished to support MAGTF operations.

q Installs, operates, and maintains MCR termi-        q Provides communications support for head-
   nals for support of internal division communi-        quarters and service (H&S), maintenance, sup-
   cations links as required.                            ply, and dental battalions and augmentation to
                                                         the organic capabilities of motor transport, en-
q Provides, in coordination with the artillery regi-     gineer support, and medical battalions.
   ment, communications support for the division
   naval gunfire officer, division air officer, and   q Installs, operates, and maintains communica-
   division fire support coordination center             tions control facilities.
   (FSCC).
                                                      q Installs, operates, and maintains tactical auto-
q Installs, operates, and maintains enhanced posi-       matic switching and wire communications for
   tion location reporting system (EPLRS) master         the FSSG HQ/force CSS area, CSS areas, and,
   stations and reference community in support of        when required, provides small-scale automated
   MAGTF operations. The division comm com-              switching within maintenance, supply, medical,
   pany is organized into a company HQ and six           and dental battalions; the explosive ordnance
   platoons organized by function to support the         disposal platoon and bulk fuel company; the
   mission and tasks listed above.                       engineer support battalion; and the FSSG.

The division comm company will furnish com-           The company is structured to provide communi-
munications for the division main, the division       cations support to the FSSG HQ in MEF opera-
rear, and the alternate CP.                           tions and task-organized detachments to the HQs
                                                      of CSSEs deployed with MAGTFs smaller than a
The division comm company will provide multi-         MEF. Augmentation from the MEF comm battal-
channel communications to the three infantry reg-     ion is required if a dedicated naval telecommuni-
iments, the artillery regiment (which may act as      cations system/defense communications system
the alternate division CP), and to the DASC.          entry is required.
MCR will be the primary means of communica-
tion with major subordinate units. Wire communi-      The company provides the primary communica-
cations will not normally be installed to major       tions support for the FSSG HQ and other CSSE
subordinate units, but may be installed to separate   HQs.
battalions if located within approximately one
mile of the division HQ. Otherwise, wire service
will be restricted to internal HQ installations for


---

Communications and Information Systems _______________________________________________________________ 2-9

2205. Communications Platoons,                      q H&S battery, LAAD battalion, MACG.
Branches, and Sections                              q Marine air control squadron (MACS), MACG.
                                                    q Airfield operations division, Marine wing sup-
Comm platoons, branches, and sections provide
communications support at the regimental/group,        port squadron (MWSS), Marine Wing
battalion/squadron, and, in some instances, com-       Support Group (MWSG).
pany/battery levels of the MAGTF. These com-
munications units are organized to support the CPs  e. MEU
and the communication networks of their parent
organization. The artillery unit comm platoons are  q MEU CE comm platoon.
further required to provide support for establish-
ing the communications links to the units receiv-   q H&S company, BLT.
ing their artillery support. The radio battalion    q Comm detachment, MSSG.
comm platoon provides SI communications sup-        q Comm section, MACG, ACE.
port for the MAGTF CE as described further in
paragraph 2206. Comm platoons, branches, and        2206. Special Security
sections are found in the following organizations:  Communications Elements and
                                                    Teams
a. MEF CE
q H&S company, radio battalion.                     The mission of the special security communica-
q HQ, force reconnaissance company.                 tions elements and teams is to provide SI commu-
                                                    nications support to the MAGTF. SI
b. Marine Division                                  communications support for the MAGTF CE is
q HQ company, infantry regiment.                    provided by the special security communications
q H&S company, infantry battalion.                  element of the radio battalion. SI communications
q HQ battery, artillery regiment.                   support for the division and MAW HQ is provid-
q HQ platoon, artillery battery.                    ed by special security communications teams (SS-
q HQ battery, artillery battalion.                  CT)—small force units organic to each division
q H&S company, tank battalion.                      and MAW. These teams operate under the staff
q H&S company, assault amphibian battalion.         cognizance of the assistant chief of staff (AC/S),
q H&S company, combat engineer battalion.           G-2/special security officer. The special security
q H&S company, light armored reconnaissance         element or team provides the personnel and
                                                    equipment to install, operate, and maintain SI
   (LAR) battalion.                                 communications terminals. The communications
                                                    circuits are provided by the communications unit
c. FSSG                                             supporting the HQ—the comm battalion for the
q H&S company, engineer support battalion.          MAGTF CE, the comm company for the division
q H&S company, landing support battalion.           HQ, and the comm squadron for the MAW HQ.
q H&S company, motor transport battalion.           Close coordination is maintained with the sup-
q H&S company, medical battalion.                   porting SYSCON and TECHCON to ensure ade-
                                                    quate support and circuit priority. The special
d. MAW                                              security elements/teams provide personnel aug-
q Marine air support squadron (MASS), Marine        mentation to man ship’s signals exploitation spac-
                                                    es (SSES) communications facilities as necessary
   air control group (MACG).                        to support landing force requirements.


---

2-10 _______________________________________________________________________________________________ MCWP 6-22

2207. Amphibious Squadron                            PHIBRON deployment teams provide the re-
Deployment Teams                                     quired expertise and leadership to maintain
                                                     Marine Corps current and future CIS networks.
In 1998, Marine communications detachments           The Marine staffing billets as part of the com-
(MARCOMMDET) and Marine tactical C2 sec-             mander amphibious group (COMPHIBGRU) and
tions (MTACCS) were reorganized into amphibi-        Fleet staffs will facilitate essential amphibious
ous squadron (PHIBRON) deployment teams to           CIS planning, coordination, installation, and
provide support for landing force CIS on board all   maintenance. In addition, the PHIBRON deploy-
amphibious ships. As both the Navy and CIS           ment teams provide appropriate manpower to ad-
architecture migrates towards a more standard-       dress critical deficiencies in amphibious CIS
ized, digital-based information network, it has be-  requirements determination and programming at
come necessary to look at all amphibious             Flag and staff levels, as well as necessary opera-
platforms as CIS recipients, and couple these CIS    tional support.
requirements with support personnel.


---

Communications and Information Systems _____________________________________________________________ 2-11

       Section III

C2 Organizations

To exercise command and control in combat, all        a. Future Plans
MAGTF units establish CPs, which serve as the
HQ from which the commander and his staff op-         The MEF G-5 establishes a future plans cell to
erate. Units of battalion size or larger may divide   conduct long-range planning. Future plans works
the HQ into echelons—main, rear, and tactical.        closely with the JTF HQ to ensure that the MEF is
The CP then becomes the echelon at which the          prepared for its next major mission. Products
commander is physically located. The main eche-       from future plans provide the basis on which fu-
lon (main) is where the commander is normally         ture operations will develop the operations order
located with those elements of the staff required     (OPORD).
to plan and direct operations and control forces. In
a large geographic area, a unit may establish a       b. Future Operations
rear echelon (rear) to serve principally as an ad-
ministrative and logistical support base. To be in    The MEF G-3 establishes a future operations cell
close proximity to subordinate units and more di-     that is responsible for planning operations in sup-
rectly influence tactical actions, the commander      port of the current mission. Future operations re-
may create a tactical echelon (tactical CP). The      ceives an initial plan and related material from
tactical echelon is mobile and contains a mini-       future plans and begins detailed planning. Future
mum number of personnel and equipment, includ-        operations consists of several full-time personnel
ing the commander, CIS operator(s), the G-2/S-2,      from the G-3 who form the core of an operational
the G-3/S-3, and the fire support coordinator.        planning team. When the operational planning
                                                      team is formed, it includes members of the G-1,
2301. MEF CE                                          G-2, G-4, G-5, and G-6 sections. Other appropri-
                                                      ate staff sections join the planning team as need-
The MEF staff and supporting CE units are task        ed. Representatives from subordinate units also
organized to exercise command and control and         join the team. Designated functional experts com-
to support the MEF’s assigned mission. The MEF        plete this group. The operational planning team
includes standard components as well as compo-        remains together through mission analysis and
nents that are used only for certain missions.        COA development, analysis, and comparison/de-
Standard components include the principal staff       cision. These personnel then return to their re-
sections and, within the operations section, a fu-    spective work sections, complete annexes and
ture operations cell and a current operations cell.   appendices to the OPORD as required, and re-
Additional components may be added, based on          sume normal duties.
the mission, to support functions needed in a par-
ticular operation. For example, in a humanitarian     c. Current Operations
operation, the MEF commander may organize an
agency or section to coordinate with other gov-       The MEF G-3 establishes a current operations cell
ernment (foreign or domestic), nongovernment,         that is responsible for executing operations. Cur-
and private voluntary agencies and organizations.     rent operations personnel receive the plan from
Another example, establish a consolidated mili-       future operations and execute it. Current opera-
tary engineering group to provide centralized         tions personnel man the MEF combat operations
planning and manage engineering assets of the         center (COC) from which they monitor MEF op-
Marine Corps, Army, and Navy that are assigned        erations and respond to situations as needed. The
to the MEF.                                           COC consists of a G-3 watch officer, a G-2 watch
                                                      officer, a senior watch officer, and a situation re-
                                                      port watch officer. A number of enlisted Marines
                                                      assist in operating tactical information systems


---

2-12 _______________________________________________________________________________________________ MCWP 6-22

and maintaining situation displays. The G-2 and          e. MEF Rear
G-3 watch officers receive information from col-
located MAGTF all-source fusion center (MAFC)            The MEF rear may perform several functions
personnel and force fires coordination center            within the MEF area of operations (AO). A MEF
(FFCC) representatives (ground and air), the sur-        rear may be established to coordinate administra-
veillance and reconnaissance center (SARC), as           tive and logistical activities while the MEF ma-
well as subordinate and adjacent units. The G-2          neuvers forward. The MEF rear may also be
and G-3 watch officers filter this information and       assigned responsibility for rear area operations.
forward important pieces to the senior watch of-         Rear area operations are extremely complex at the
ficer. The senior watch officer also receives infor-     MEF level. Joint doctrine currently defines eight
mation that affects current operations from other        rear area functions that must be coordinated: area
principal staff sections (G-1, G-4, and G-6). The        management, movements, infrastructure develop-
senior watch officer evaluates information in the        ment, host nation support, security, communica-
context of current operations and determines             tions, intelligence, and sustainment. The MEF
whether action is required. Depending on the situ-       commander may assign some or all of these func-
ation, the senior watch officer may be assisted in       tions to the MEF rear and others to the wing and
this process by other officers from current opera-       the FSSG. If assigned overall responsibility, the
tions. On the basis of authority delegated by the        MEF rear would require the capability to plan and
MEF commander, the senior watch officer acts by          conduct rear area operations. In this instance, the
either issuing orders or briefing the MEF com-           MEF rear would establish a rear area operations
mander and recommending action.                          center to facilitate command and control of opera-
                                                         tions within the rear area. In situations where the
d. C2 Facilities                                         main HQ does not move forward and the MEF re-
                                                         tains responsibility for rear area operations, the
Watch officers and supporting personnel from the         rear area operations center becomes another ele-
staff sections and supporting units establish and        ment of the MEF.
operate centers within the HQ from which the
day-to-day activities of the MEF are coordinated,        2302. Ground Combat Element
controlled, and supported. These C2 centers
sometimes, especially when dealing with air com-         a. Division Main
mand and control, are referred to as C2 agencies.
In this publication, these centers and agencies,         The division main serves as the division com-
both at the MEF level and at the subordinate unit        mander’s primary HQ. Both current and future
level, are referred to as C2 facilities. These facili-   operations planning are accomplished in the divi-
ties include the personnel, software, hardware,          sion main. Division personnel monitor current op-
shelters, and ancillary equipment needed to sup-         erations from the division main, and if the
port command and control. The key C2 facility in         commander is aboard, current operations are also
the MEF is the COC described above. In most              directed from the division main. Although smaller
cases, the COC is collocated with the FFCC and           than the MEF, the division main is organized for
the MAFC. These three C2 facilities work togeth-         command and control in a similar manner, includ-
er closely, focusing on current operations and re-       ing a future operations cell within the G-3 section.
sponding to the immediate needs of the MEF               Current operations are directed from the division
commander. In all cases, information system sup-         COC, which is typically manned with G-3 person-
port and LAN connectivity within and among               nel; G-2 personnel; the division engineer; the di-
these three facilities are essential for efficient exe-  vision air officer; and nuclear, biological, and
cution of MEF operations. The FFCC, the MAFC,            chemical (NBC) personnel. The FSCC is usually
and other MEF C2 facilities are discussed under          physically collocated with the COC, and the
the functional area they support.                        DASC is either physically or electronically collo-
                                                         cated with the FSCC.


---

Communications and Information Systems _____________________________________________________________ 2-13

b. Division Rear                                       spective commanders. Additionally, they may
                                                       serve within the FSCC to assist with planning and
If the division is spread over a large geographic      deconfliction functions related to air support for
area, the division commander may establish a di-       the assigned unit. Forward air controllers provide
vision rear. The division rear may serve principal-    terminal control of close air support aircraft that
ly as an administrative and logistical support base    are passed to them by the DASC. These officers
for the division. In this arrangement, the division    also advise GCE commanders on aviation capa-
main may consist of the COC and FSCC with the          bilities and limitations and prepare requests for air
collocated DASC. The division rear would then          support.
include principal staff elements not required to
plan and execute current operations (G-1, G-4,         2303. Aviation Combat Element
staff judge advocate, etc.). This arrangement al-
lows the division main to maneuver rapidly in          a. Wing Main
high-tempo operations.                                 The wing main serves as the principal HQ for the
                                                       wing commander. Like the MEF and division
c. Division Tactical Echelon                           main, most principal staff members are located in
                                                       the wing main, and future planning is done in the
The division commander may establish a small,          wing main. The wing rear area operations center
highly mobile tactical echelon to remain in close      is often collocated with the wing main. Unlike the
proximity to the battle, gain first-hand situational   MEF and division main, however, the wing main
awareness, and more directly influence tactical        may be located outside the MEF AO. The wing
operations at critical times. Depending on the sit-    commander often locates the wing main at a large
uation, either surface or air platforms, appropri-     airfield, especially if this airfield houses most of
ately configured, provide mobility and                 the wing’s fixed-wing aircraft. Wing future and
communications for the tactical echelon. The di-       current operations functions occur within the
vision commander prescribes which staff mem-           TACC, which may or may not be collocated with
bers constitute the tactical echelon. A nominal        the wing main.
tactical echelon would include the division com-
mander, CIS operator(s), G-2, G-3, and fire sup-       b. TACC
port coordinator.                                      The wing commander conducts future operations
                                                       planning and current operations monitoring from
d. Regiment/Battalion                                  the TACC. The TACC consists of three mutually
                                                       supporting cross-function operational cells sup-
Regiments and battalions also use the main, rear,      ported by a centralized intelligence center. The
and tactical echelon structure and establish a COC     organizations that comprise the TACC are—
to coordinate and direct operations. These opera-
tions centers and echelons are much smaller than       q Future plans
those at the division level because regiments and      q Future operations (future ops)
battalions have fewer subordinate units and fewer      q Current operations (current ops)
functions to support.                                  q Air combat intelligence (ACI)

e. Tactical Air Control Party                          Future plans conducts aviation and aviation sup-
                                                       port planning for the next MAGTF mission
Tactical air control parties (TACPs) provide coor-     change. Future ops develops future air tasking or-
dination between GCE units and supporting avia-        ders (ATOs), and prepares OPORDs/fragmentary
tion assets. TACPs exist at the infantry division,     orders for the next ACE mission change. Current
regiment, and battalion levels. Depending on the
command level, a TACP contains a combination
of air officers, forward air controllers, and enlist-
ed radio operators. Air officers serve at the divi-
sion, regiment, and battalion levels. These
officers serve as special staff officers to their re-


---

2-14 _______________________________________________________________________________________________ MCWP 6-22

ops executes the daily ATO and assesses its effec-      coordinate with Stinger teams to construct and
tiveness.                                               operate base defense zones.

ACI is imbedded within the TACC. Timely, tai-           e. LAAD Battery Command Center
lored, and fused intelligence is integral to the
functioning of future plans, future ops, and cur-       The LAAD battalion, usually collocated with the
rent ops. ACI is the focus of all aviation intelli-     TAOC, establishes a COC for the exercise of bat-
gence activities supporting the ACE. It produces        talion operations. The LAAD battalion command-
and disseminates aviation specific all-source in-       er exercises overall command and control of
telligence, including assessments of adversary ca-      LAAD battalion operations from the COC. The
pabilities and vulnerabilities, target analysis,        LAAD battalion commander obtains and relays
battle damage assessment (BDA), and the current         intelligence and combat information on friendly
status and priority of assigned targets to assist in    and enemy operations to the two subordinate
execution day changes. The TACC uses special-           LAAD battery COCs. The LAAD battery COCs
ized information systems and equipment to dis-          maintain situational awareness of MAGTF and
play a common picture of the aviation situation         other air operations and plan and control employ-
received from tactical digital information links.       ment of LAAD teams.
Each Marine aviation function (antiair warfare,
assault support, electronic warfare (EW), air re-       f. DASC
connaissance, offensive air support, and control
of aircraft and missiles) provides representation to    The DASC controls aircraft supporting the GCE.
the TACC.                                               Air support personnel control aircraft en route to
                                                        the forward air controllers serving with infantry
c. TAOC                                                 units. DASC controllers also monitor helicopter
                                                        missions within the MEF battlespace. These per-
The TAOC performs air surveillance and control          sonnel assist GCE units to obtain additional air
of aircraft and missiles for the wing commander.        support, either fixed-wing aircraft or helicopters,
Air control personnel assigned to this facility use     beyond those preplanned missions scheduled to
specialized information systems, sensors, and           fly. Because of their proximity to the senior
dedicated communications links to search the            FSCC, DASC personnel often help the wing com-
MEF’s airspace and provide air defense services         mander maintain awareness of the ground combat
for those areas designated as vital. The TAOC           situation. Several configurations exist for the
controls friendly aircraft in the intercept of hostile  DASC, with varying degrees of size, capability,
aircraft and assists Marine missile units in locat-     and mobility. One configuration may be em-
ing and destroying hostile aircraft. Information        ployed in a C-130 aircraft.
gained through radar assets and tactical digital in-
formation links is transmitted to the TACC and          g. Airborne Coordinators
provides situational awareness for the wing com-
mander. The TAOC is movable, but not mobile,            Marine pilots and aircrew often serve as airborne
and is located in the rear of the MEF AO. Often,        extensions of MACCS. The tactical air coordina-
the TAOC is collocated at a fixed-wing airfield.        tor (airborne) serves as an extension of the DASC
                                                        and coordinates aircraft en route to close air sup-
d. MATCDs                                               port missions. The tactical air coordinator (air-
                                                        borne) receives aircraft “hand-offs” from the
MATCDs provide air control services in and              DASC, briefs those aircrew, then turns these mis-
around airfields. Additionally, detachment radar        sions over to ground or airborne forward air con-
contributes to air surveillance efforts, and infor-     trollers for terminal control. The assault support
mation is forwarded to other agencies via tactical      coordinator (airborne) also serves as an extension
digital information links. Detachment personnel         of the DASC and coordinates complex helicopter
                                                        missions. The assault support coordinator decon-


---

Communications and Information Systems _____________________________________________________________ 2-15

flicts transport packages, escort packages, and fire   maintain status displays of friendly and enemy
support efforts throughout the mission.                situations. Additionally, CSSOC personnel han-
                                                       dle requests from subordinate units and keep the
Airborne strike coordination and reconnaissance        MEF informed of the CSS situation. FSSG com-
is a means to efficiently focus aviation fires in the  manders may choose either a centralized or de-
deep battlespace. This function, usually per-          centralized configuration for their CSSOCs.
formed by an F/A-18 aircrew, allows real-time re-
connaissance to locate the MEF commander’s             c. Combat Service Support
high-priority targets. Once located, the strike co-    Detachments
ordination and reconnaissance aircrew control at-
tack aircraft in much the same manner as a             Depending on the situation, the FSSG commander
tactical air coordinator, cycling and deconflicting    establishes forward detachments to provide direct
multiple strike packages as they ingress to the tar-   support to the GCE. Detachment commanders
get area. Using aircrew to extend the command          may establish small facilities to coordinate sup-
and control system offers several benefits. These      port and monitor logistics communications nets.
personnel can position themselves to effectively       A mobile CSS detachment possesses the least ca-
control multiple aircraft missions and maintain        pability to establish an operations center. In this
communications with both the aircraft they con-        instance, the CSSOC could resemble a mobile,
trol and ground-based C2 facilities.                   tactical echelon. Communications connectivity
                                                       would be predominantly through SCR.
2304. CSSE
                                                       d. Movement Control Center
a. FSSG Main
                                                       Movement control centers support the deploy-
The FSSG main is task organized by the FSSG            ment of the MEF from the home station, through
commander to enable him to control and coordi-         intermediate bases, to the destination. The com-
nate logistic support of the MEF. An FSSG main         mander, MARFOR (COMMARFOR) establishes
includes the principal staff sections, a future plans  a HQ movement control center, which provides
and deployment section, and the CSS operations         connectivity to United States Transportation
center (CSSOC). The future plans and deploy-           Command (USTRANSCOM) and keeps the MEF
ment section ensures that the FSSG is prepared to      force movement control center apprised of strate-
support the next major mission of the MEF. Of-         gic movement issues. The force movement con-
ten, this new mission involves a deployment or re-     trol center controls and coordinates all movement
deployment. The CSSOC monitors current                 support and conducts liaison with the Air Mobili-
operations and plans near-term future operations.      ty Command, the Military Sealift Command, and
The FSSG main will typically be located near sea       the Military Traffic Management Command. The
or aerial ports of debarkation in the MEF’s AO.        force movement control center supervises efforts
Subordinate battalions establish their own HQ in       of unit movement control centers of the division,
proximity to the FSSG main.                            wing, and FSSG. These latter units provide trans-
                                                       portation and communication assets in support of
b. CSSOC                                               deployment activities. Bases and air stations from
                                                       which Marine units deploy establish base or sta-
The CSSOC serves as the hub for future and cur-        tion operations support groups to coordinate their
rent operations planning within the FSSG main.         efforts with those of deploying units. These bases
Each CSS functional area (supply, maintenance,         also provide their transportation and communica-
transportation, engineering, health services, and      tion assets in support of deploying units. These
services) provides representation to the CSSOC.        units augment unit movement control centers to
Under the supervision of a G-3 watch officer,          ensure that all personnel and materiel arrive at sea
these personnel monitor current operations and         and aerial ports of embarkation.


---

2-16 _______________________________________________________________________________________________ MCWP 6-22

e. Marine Logistic Command                            b. SARC

The COMMARFOR may establish a Marine Lo-              The SARC is the primary intelligence C2 node
gistic Command (MLC) and assign it responsibil-       used to direct, coordinate, monitor, and supervise
ity for establishing the theater general support      MAGTF collection operations (including intelli-
structure to facilitate reception (arrival/assembly)  gence collection operations conducted by organic
and reception, staging, onward movement, and in-      attached and direct support assets). The SARC is
tegration operations, and, on order, for providing    located close to the MEF COC. The SARC coordi-
operational logistic support to Marine forces as      nates collection and operations tasks to various
the Marine component operational-level logistic       MEF assets, including force reconnaissance, the
agency in theater. MLC is a task organization op-     sensor control and management platoon, the un-
tion, not a standing organization. COMMARFOR          manned aerial vehicle squadron, the radio battal-
may choose to assign a specific FSSG responsi-        ion, counterintelligence detachments,
bility for MLC functions. Then, on the basis of       interrogator-translator teams, the force imagery
the operational situation, theater geography, oper-   interpretation unit, and the topographic platoon.
ations and logistic command and control, and in-      Collection results are forwarded to the MAFC to
frastructure requirements, COMMARFOR will             incorporate into current intelligence products, and,
assign Marine component resources to the FSSG         when appropriate, to the COC.
for detailed task organizing and conducting MLC
theater-support operations.                           c. Reconnaissance Operations Center

2305. Intelligence Command and                        The reconnaissance operations center serves as a
Control                                               focal point for monitoring and supervising force
                                                      reconnaissance operations. Located near the
The combat intelligence center (CIC) is estab-        SARC, this facility gathers information from dis-
lished under the G-2/S-2 within the MAGTF HQ          persed teams, decrypts reports, and forwards in-
to provide centralized direction for the overall      formation for fusion into the overall MEF
MAGTF intelligence effort. This organization          intelligence situation display. Personnel manning
serves the entire force by consolidating, validat-    the reconnaissance operations center assist recon-
ing, and prioritizing intelligence requirements       naissance teams with movement and other activi-
from all MAGTF elements. The CIC links the            ties as needed.
MAGTF to JTF, theater, national, and allied intel-
ligence assets. The CIC includes as key internal      d. OCAC
nodes the MAFC and the SARC. It also provides
small G-2/S-2 elements to support both the current    The OCAC provides centralized direction, man-
and future ops cells. The CIC is supported by the     agement, and control of signals intelligence (SIG-
reconnaissance operations center and the opera-       INT) and EW activities within the MEF and
tions control and analysis center (OCAC).             coordinates with external theater and national as-
                                                      sets. Assigned personnel process, analyze, and
a. MAFC                                               disseminate collected information. The OCAC is
                                                      located within the MEF HQ compound, near other
The MAFC provides intelligence analysis, pro-         intelligence C2 facilities.
duction, and targeting information to the MEF.
An integral part of the MAGTF main CP, the            e. Intelligence Centers
MAFC is usually collocated with the MEF COC.
All surveillance, reconnaissance, and intelligence    The G-2/S-2 will establish intelligence centers at
gathering results flow into the MAFC, where they      all echelons of the MAGTF down to the battalion
are fused with previous collections and intelli-      level. Personnel assigned to the intelligence cen-
gence products are updated and disseminated.          ter will collect, process, integrate, analyze, evalu-
                                                      ate, and interpret intelligence and continuously
                                                      update the enemy situation. This information will
                                                      be rapidly provided to current and future ops.


---

Communications and Information Systems _____________________________________________________________ 2-17

These centers will be collocated with the COC          talion levels, the FDC exercises tactical fire
whenever possible.                                     direction, and battalion FDC personnel supervise,
                                                       advise, and augment battery personnel as re-
2306. Fire Support Centers                             quired. Battalion personnel also assist by trouble-
                                                       shooting gunnery problems, which enables
C2 facilities are established to coordinate the        battery FDC personnel to focus on delivering ar-
overall fire support effort and to exercise tactical   tillery fires. The battery FDC provides technical
and technical fire support direction.                  fire direction by evaluating information received
                                                       by forward observers and determining firing data.
a. FFCC                                                This firing data is issued to artillery sections
The FFCC is established at the MEF level to as-        through fire commands. Battery FDCs are also ca-
sist the MEF commander in planning and coordi-         pable of tactical fire direction and would perform
nating deep fires. The FFCC performs three             this function in cases, such as MEU deployments,
primary functions for the MEF: planning, acquir-       when the battery operates independently.
ing, and maintaining target information; coordi-
nating and integrating MAGTF-level fires with          d. EW Coordination Center
future operations; and coordinating and integrat-
ing MAGTF-level fires into current ops. Located        The EW coordination center (EWCC) facilitates
within the MEF, this facility assists both future      coordination of EW operations with other fires
ops and current ops in their targeting functions.      and CIS. This center coordinates efforts by the G-
Additionally, the FFCC provides coordination be-       2, G-3, and G-6 to eliminate conflicts between
tween the MEF and JTF targeting boards and cen-        these overlapping battlespace functions. The
ters. Watch standers may be collocated with the        EWCC is under the staff G-3’s cognizance. As-
COC to facilitate rapid deep fires coordination.       signed personnel identify potential conflicts in
                                                       planned operations and work to resolve these is-
b. FSCC                                                sues. The EWCC includes an EW officer, a CIS
Each Marine ground combat organization from di-        representative, and other liaison officers as need-
vision to battalion employs a FSCC as an advisory      ed. Liaison could include radio battalion represen-
and coordination agency. The FSCC is collocated        tation, EA-6B electronic countermeasures
with the COC. The senior FSCC coordinates and          officers, a MACG radar officer, and other Service
deconflicts fire support efforts among subordinate     representatives.
units and centers. The FSCC includes the fire sup-
port coordinator, artillery liaison, TACP person-      2307. Rear Area Operations
nel, mortar unit liaison when appropriate, and a       Centers
naval surface fires liaison. At the division level,
the division artillery officer or artillery regiment   Responsibility for rear area operations may be
commanding officer serves as the fire support co-      tasked to the MEF rear. It may also be shared with
ordinator. At lower levels, each commander ap-         or assigned to the FSSG and the wing, especially
points a fire support coordinator from his staff       when the MSCs are widely dispersed geographi-
(usually the weapons company commander).               cally. In any case, a rear area operations center fa-
                                                       cilitates C2 operations within the rear area(s). The
c. Fire Direction Center                               rear area operations center contains personnel to
Fire direction centers (FDCs) exist at artillery reg-  monitor and coordinate the vast array of activities
iments, battalions, and batteries. These organiza-     occurring in the MEF rear area. For MSCs, the
tions permit respective commanders to plan and         size and scope of a rear area operations center
control fires. Fire direction activities may be cen-   would be driven by the unit’s mission and rear ar-
tralized or decentralized. At regimental and bat-      ea activities. At a minimum, the wing and FSSG
                                                       would use one or more rear area operations cen-
                                                       ters to coordinate security for the bases they occu-
                                                       py. Personnel serving in these facilities must be


---

2-18 _______________________________________________________________________________________________ MCWP 6-22

knowledgeable in all functions performed by the          SPE effort at the MAGTF level. The G-6/S-6 at
facility. To support the security function, a fire       lower echelons, with the assistance of their sup-
support coordinator must be assigned to plan and         porting communications unit/detachment, per-
coordinate fires in the rear area. All rear area op-     forms appropriate level SPE functions in
erations centers should be linked and should coor-       accordance with the overall MAGTF communica-
dinate activities across the entire MEF rear area.       tions plan.

2308. CIS Control                                        (2) Systems Control. The systems control (SY-
                                                         SCON) performs current operations functions for
At the MAGTF CE level, the CISO (G-6/S-6) ex-            communications operations. The SYSCON is es-
ercises overall operational systems control of           tablished by the operations officer of each com-
MAGTF communications networks and informa-               munications unit to maintain current information
tion systems. The G-6/S-6 also coordinates with          on availability and operational readiness of CIS,
the controlling authorities of external networks.        set priorities and resolve conflicts. SYSCON per-
The G-6/S-6 is assisted by personnel from the            sonnel perform their duties in an appropriate fa-
communications battalion to exercise operational         cility in the vicinity of the supported command
systems control. Operational systems control is          post. The SYSCON receives direction from the
exercised at levels lower than the MAGTF down            SPE. The SYSCON coordinates directly with se-
to the battalion/squadron level by the G-6/S-6 of        nior, subordinate, and adjacent SYSCONs as re-
that organization. The G-6/S-6 is supported by or-       quired. SYSCON personnel must have the
ganic communications units or detachments.               technical expertise and experience to coordinate
                                                         resolution of complex communications problems.
a. Operational Systems Control Center
                                                         (3) Technical Control. TECHCON provides cen-
The functions of an operational systems control          tralized technical supervision over the installa-
center (OSCC) exist at all levels of CIS control.        tion, operation and maintenance of single channel
At higher echelons (MSC and above), specific             radio, wire, multichannel and data communica-
agencies are established to conduct these func-          tions systems. TECHCON functions are per-
tions. At lower echelons (bn/sqdn), the functions        formed from specially designed TECHCON
are still performed, but at the S-6/comm unit lev-       facility(ies), the network operations center, main-
el. Figure 2-1 details a typical Joint operational       tenance facilities, and communications centers,
systems control model. The OSCC functions con-           when established. The TECHCON facility(ies)
sist of the following:                                   provides a means to conduct and coordinate cir-
                                                         cuit troubleshooting and restoration. The size and
(1) Systems Planning and Engineering. T h e              scope of the TECHCON facility(ies) are driven
systems planning and engineering (SPE) performs          by the size of the communications organization
future ops functions for communications opera-           and types of services being provided. TECHCON
tions. The SPE at any echelon consists of CIS net-       personnel must have the technical expertise and
work design. These networks are designed and             experience to resolve complex communications
subsequently engineered to meet the operational          problems.
requirements as determined by the CISO. Circuits
are determined by type and number to meet both           b. Joint Communications Control
internal and external command communications             Center
requirements. SPE personnel normally perform
their duties in a suitable facility as part of the G-6/  The joint communications control center (JCCC)
S-6 staff in the main CP. The MAGTF G-6/S-6 is           is the operational systems control agency of the
the senior Marine CISO who directs the overall           JTF or CINC J-6. Per Chairman, Joint Chiefs of


---

Communications and Information Systems _____________________________________________________________ 2-19

Figure 2-1. Joint Operational Systems Control Model.

Staff Manual (CJCSM) 6231.07A, Joint Network      MAGTF communications control center may also
Management and Control, the JCCC provides         be required to support to a Marine component HQ.
theater or JTF planning level and supervision of
component communications control centers. Nor-    d. Component Communications
mally, liaison officers from each service compo-  Control Centers
nent command are provided to the JCCC as
subject matter experts and participate in JCCC    Each component of the Joint Force or Theater
functions as watch members.                       Command (USA, USAF, USN, USMC) establish
                                                  somes form of an operational systems control
c. MAGTF Communications Control                   center to perform component level operational
Center                                            systems control functions. The components of the
                                                  designated army Theater Signal Command will
The MAGTF G-6 employs the MAGTF commu-            normally support the Army Component Com-
nications control center as the MAGTF operation-  mand and augment JTF/Theater-level operational
al systems control center. The subordinate        systems control agency. The MAGTF communi-
communications battalion(s)/company(ies) staff    cations control center will coordinate OSCC
augments the MAGTF communications control         functions with joint and service component com-
center. The MAGTF communications control cen-     munications control centers to maintain the joint
ter coordinates external communications control   network.
with the JTF or CINC J-6 through the JCCC. The


---

2-20 _______________________________________________________________________________________________ MCWP 6-22

2309. Amphibious C2 Facilities                        tains ATF special security communications
                                                      terminals and processing facilities.
When the MAGTF is embarked aboard amphibi-
ous shipping, the MAGTF commander serves              c. Supporting Arms Coordination
concurrently as the commander of the landing          Center
force. While embarked, the MAGTF commander
and his staff direct the actions of the MAGTF         The CATF exercises overall coordination of sup-
from C2 facilities aboard the amphibious ships.       porting fires within the amphibious objective area
Under the OMFTS concept, MAGTF command                through the supporting arms coordination center
and control may remain afloat throughout the am-      (SACC). This center, located aboard the amphibi-
phibious operation. Many of the shipboard C2 fa-      ous flagship, consists of a supporting arms coordi-
cilities also support the commander, amphibious       nator, naval gunfire, air support, and target
task force (CATF), who normally is located, with      information sections. ATF operations, intelli-
his staff, in the flag plot located aboard the flag-  gence and communications personnel, and land-
ship.                                                 ing force fire support personnel perform the
                                                      functions of the SACC. These functions are simi-
a. Landing Force Operations Center                    lar to those performed by the FFCC and FSCC
                                                      that may be subsequently established ashore. A
The landing force operations center (LFOC) is the     landing force liaison is established in the SACC if
shipboard space allocated to the commander,           the responsibility for coordination of supporting
landing force (CLF), and staff to plan and execute    arms is passed ashore.
landing force operations. The LFOC is normally
located on the amphibious task force (ATF) flag-      SACC provides the commanders of the ATF and
ship. The LFOC staff are the same personnel who       the landing force with information concerning the
man the MAGTF COC when and if it is phased            requirements and developments that affect coordi-
ashore in an amphibious operation. The functions      nation of fire delivery by naval gunfire units, sup-
of the LFOC mirror those of the COC. This center      port aircraft, and artillery units. Fire support
controls and monitors the activities of the landing   requests received from the landing force are coor-
force until the CLF establishes command ashore.       dinated from this center to ensure that all fires are
                                                      integrated to achieve the maximum effect against
b. Amphibious Task Force                              targets. Current fire support information is contin-
Intelligence Center                                   ually updated and displayed while direction for
                                                      the execution of restrictive fire plans and instruc-
The amphibious task force intelligence center         tions concerning troop safety are promulgated.
(ATFIC) is a single Naval intelligence facility       Naval gunfire plans are prepared and their execu-
formed during a preassault phase of amphibious        tion is supervised by the SACC staff. This center
operations. It supports the requirements of the       also coordinates air support operations with ap-
CATF and the CLF. The ATFIC is usually located        propriate ATF and landing force air control agen-
aboard the amphibious flagship and is manned by       cies. Records of targets in the objective area are
Navy and Marine intelligence personnel. Intelli-      maintained, and appropriate fire support activities
gence resources available to the ATFIC include        in the amphibious objective area are monitored
national, joint, combined, and internal naval force   when responsibility for the coordination of fires is
assets. Some of these assets may already be for-      passed to the CLF ashore.
ward deployed in advance or assault operations.
Landing force intelligence personnel and their or-    d. Tactical Air Control Center (Afloat)
ganic information systems such as the Intelli-
gence Analysis System (IAS) and the technical         The tactical air control center (afloat) (TACC[A])
control and analysis center (TCAC) workstations       is organized and located in the flagship of the
are integrated in the ATFIC operations while          CATF. The TACC(A) provides the means to di-
afloat. Additionally, the ship’s signals exploita-    rect and coordinate all tactical air operations in an
tion space (SSES) is within the AFTIC and con-        objective area, including antiair warfare, until this


---

Communications and Information Systems _____________________________________________________________ 2-21

responsibility is transferred to Marine air control    f. Tactical-Logistical Group
agencies ashore. The TACC(A) consists of a tacti-
cal air controller; air support controller; antiair    Tactical-logistical groups (TACLOGs) are tempo-
warfare coordinator; and appropriate operations,       rary agencies organized as required by ground
intelligence, and communications personnel and         combat organizations of a landing force to assist
equipment. These personnel and their equipment         the naval control organization in the ship-to-shore
are provided by the flagship, the staff of the         movement of troops, equipment, and supplies.
CATF, and a designated tactical air control squad-     They are normally established aboard control
ron.                                                   ships at each echelon of the MAGTF, along with
                                                       the naval control agency exercising control over
e. Helicopter Direction Center                         the ship-to-shore movement of that echelon dur-
                                                       ing a waterborne landing. They are also estab-
The helicopter direction center (HDC) is orga-         lished aboard each helicopter transport carrier
nized aboard the flagship of the helicopter trans-     during vertical assaults. A TACLOG consists of
port group to provide the means to direct and          operations, CSS, embarkation, and communica-
control helicopters during the ship-to-shore move-     tions personnel provided by the parent ground
ment. It consists of a helicopter director, who is     combat organization.
responsible to the tactical air commander for di-
rection of all helicopters and supporting aircraft; a  TACLOG assists the corresponding naval control
helicopter direction net officer; a helicopter air     agency in handling landing force requirements
controller; and other appropriate air operations       during the ship-to-shore movement. It is task-or-
and communications personnel and equipment.            ganized to advise the naval control agency as to
These personnel and their equipment are normally       the location of units, equipment, and supplies and
provided by the flagship on which the HDC is es-       to monitor their regulated movement ashore. The
tablished.                                             TACLOG maintains a detailed record of the un-
                                                       loading and landing status, provides information
To effect the direction and control of helicopter      to appropriate commanders concerning the
movement in an objective area, the HDC must op-        progress of the ship-to-shore movement, and re-
erate under the overall direction of the TACC(A)       sponds to routine requests received from units by
for coordinating air operations with other agen-       coordinating with the naval control agency. It fur-
cies and under the operational control (OPCON)         ther advises the naval control agency when the
of the helicopter transport group commander. The       tactical situation ashore dictates an adjustment to
HDC advises the TACC(A) on all matters pertain-        the prescribed landing sequence.
ing to helicopter movement that require coordina-
tion with supporting arms. The HDC provides            2310. Mobile CPs
information as directed by the TACC(A) and the
helicopter transport group commander and main-         Mobile CPs provide means for commanders at all
tains availability and location status of assigned     levels to keep pace with rapidly maneuvering ele-
helicopters. The HDC also receives requests for        ments. They are essential for the conducting ma-
helicopter support, designates units to provide the    neuver warfare. These mobile CPs are usually
helicopters for specific missions, and directs their   mounted in vehicles, but may be situationally air-
employment. The HDC further controls the move-         borne or footmobile. Various configurations exist
ment of helicopters, both transport and escort,        depending on the availability of C2 platforms. C2
from wave rendezvous to initial point and from         variants of the assault amphibious vehicle (AAV)
takeoff at the landing zone to breakup point. The      and light armored vehicle (LAV) are specifically
HDC also controls movement of helicopters be-          designed for this purpose, and it is also one of the
tween platforms and assists the DASC in control-       roles of the utility helicopter. Units also use or-
ling helicopters between ship and shore after the      ganic vehicles in various arrangements to form
control of helicopters has been passed ashore.         mobile CPs. Mobile CPs normally consist of the


---

2-22 _______________________________________________________________________________________________ MCWP 6-22

commander accompanied by a few key personnel        ple, when operating in terrain that precludes using
from the tactical echelon. At the small unit level  vehicles. However, given restrictions on the
(rifle company and rifle platoon), the CP is often  amount of equipment that can be carried, a foot-
footmobile. In some situations, the tactical eche-  mobile CP is usually impractical above battalion
lon of a larger unit may be footmobile; for exam-   level.


---

                        Chapter 3

Information Systems and Services

Information systems and services provide the        profound effect on Marine Corps CIS policy and
management and decision support tools that are      will ultimately have an impact on all MAGTF CIS
required to support command and control func-       doctrine, organization, training, and equipment.
tions, including operations planning and execu-     The Marine Corps is migrating its tactical infor-
tion. To improve interoperability, increase         mation systems to the DII COE beginning with
efficiency, and reduce costs, the DOD has mandat-   TCO and IAS. DII COE compliance will provide
ed that the Services move to a common set of in-    complete interoperability with GCCS and other
formation systems and services. This migration is   DII COE-compliant systems. To understand the
taking place rapidly with the fielding of the GCCS  information systems and services provided by the
and the implementation of the defense information   MAGTF CIS environment, it is necessary to de-
infrastructure (DII) common operating environ-      scribe that environment in the context of the
ment (COE). These developments are having a         GCCS and the DII COE.

                      Section I

Defense Information Infrastructure
Common Operating Environment

The DII COE provides a standard environment,        3102. Services
off-the-shelf software, and a set of programming
standards that describe in detail how mission ap-   As the user selects the mission applications need-
plications will operate in the standard environ-    ed to perform a set of tasks, the integration tool au-
ment. The COE contains common support               tomatically loads all the COE modules needed by
applications and platform services required by      those applications. These selected modules make
mission applications.                               up a subset of the DII COE superset: this subset is
                                                    called a COE-variant (COE-V). The original COE
3101. Mission Applications                          software components are used without modifica-
                                                    tion. System managers must ensure that COE-Vs
Each mission application that is migrated to the    do not include nonstandard software that dupli-
common environment must comply with guid-           cates services provided by software under the
ance published in the DII COE standards (see app.   COE. Figure 3-1 (on page 3-2) shows the services
A). Although there may be some need for             available under the DII COE. This figure depicts
“workarounds” as mission applications migrate to    mission applications (e.g., Joint Maritime Com-
the COE, these are necessary as mission applica-    mand Information System [JMCIS]) accessing the
tions. As the COE matures, workarounds will no      services in the DII COE through a standard appli-
longer be needed and will be stripped from the      cation interface. It also reflects both the mission
mission application.                                applications and the DII COE services hosted on
                                                    common computer platforms using COTS operat-
                                                    ing systems.


---

3-2 ________________________________________________________________________________________________ MCWP 6-22
                                                        Figure 3-1. DII COE Services.


---

Communications and Information Systems _______________________________________________________________ 3-3

                        Section II

Global Command and Control System

The GCCS implements the joint C4I for the war-       (C3I) established the GCCS as the principal mi-
rior concept. This concept calls for the capability  gration path for defense-wide C2 systems, direct-
to move a joint force anywhere on the globe at       ing that GCCS rapidly and efficiently deliver
any time and to provide that force with the infor-   mission-essential C2 capabilities to combatant
mation necessary to accomplish its mission. The      commanders through maximum use of commer-
GCCS is a revolutionary approach designed to re-     cial off-the-shelf (COTS) and government off-
solve joint C2 interoperability issues and evolve    the-shelf (GOTS) components. Further, he speci-
incompatible, Service-specific C2 programs into a    fied that the program evolve through a continuous
single integrated C2 system. Figure 3-2 depicts      requirements-refinement process to meet the goal
GCCS.                                                of providing responsive C2 support to combatant
                                                     commanders.
3201. Background
                                                     GCCS provides a fused and shared picture of the
The Assistant Secretary of Defense (C3I) and the     battlespace together with the essential planning
Joint Staff are exercising oversight of GCCS im-     and assessment tools required by combatant com-
plementation. The Assistant Secretary of Defense     manders and their subordinate commanders.

Figure 3-2. GCCS


---

3-4 ________________________________________________________________________________________________ MCWP 6-22

GCCS also supports readiness assessment and re-      The baseline GCCS architecture consists of a
porting by the Services. GCCS employs a modern       suite of relational database servers and applica-
client-server architecture using commercial, open    tion servers. At most GCCS sites, the relational
systems standards and will, through the ongoing      database server acts as a typical file server by
DOD migration strategy, reduce the large number      hosting user accounts, user-specific data, and site-
of information systems in use today.                 specific files that are not part of GCCS. The appli-
                                                     cation servers host the automated message han-
GCCS is evolving from a baseline of existing C2      dling system, applications not loaded on the
systems. This baseline has served as the corner-     database server, and other databases. At each
stone for the rapid implementation of an initial     GCCS site, one application server is configured as
system capable of fulfilling the most critical user  the executive manager. This server acts as the us-
requirements. As new GCCS versions are subse-        er interface and provides access to GCCS applica-
quently fielded, existing legacy systems will be     tion programs through user identification and
replaced. The common functional, physical, and       discrete passwords. GCCS software application
operational characteristics of GCCS are based on     programs are categorized into two groups: COE
a single COE described below. All future joint       applications and mission applications.
and Service/CINC-specific C2 systems must be
compatible with this COE. The goal is to achieve     Several key GCCS mission applications are de-
a fully integrated, single GCCS in which all C2      scribed in paragraphs 3203 through 3211. GCCS
functions are provided through GCCS application      is an evolutionary program with mission applica-
programs that have a common look and feel.           tions being added or improved in each new soft-
                                                     ware release. The GCCS configuration
3202. Description                                    management website (http://spider.osfl.disa.mil/
                                                     new_home/cnfgmgmt/cnfgmgmt.html) contains
GCCS is composed of several mission application      detailed information on the current status of
programs built within a single COE. GCCS also        GCCS mission applications.
includes the network that supports sharing, dis-
playing, and exchanging information. The GCCS        3203. Joint Operation Planning
infrastructure consists of a client-server environ-  and Execution System
ment incorporating UNIX-based servers and cli-
ent terminals as well as microcomputer               JOPES is the integrated C2 system used to plan
workstations operating on a standardized LAN.        and execute joint military operations. It is a com-
(Although GCCS currently employs a UNIX-cen-         bination of joint policies, procedures, personnel,
tric architecture there is movement toward an ar-    and training and a reporting structure supported
chitecture that exploits the capabilities of         by automated data processing on GCCS. The ca-
Windows NT. This is discussed in paragraph           pabilities of the JOPES mission applications sup-
3003.)                                               port translation of the National Command
                                                     Authorities’ policy decisions into planning and
The GCCS infrastructure supports data transfer       execution of joint military operations. These ap-
among workstations and servers. Connectivity be-     plications are used by MAGTF planners for de-
tween GCCS sites is provided by the secret inter-    ployment and employment planning.
net protocol router network (SIPRNET), the
secret layer of the DISN that is discussed in the    3204. Global Reconnaissance
next chapter. Remote user access is also support-    Information System
ed by using dial-in communications and the tele-
communication network (TELNET) protocol.             The Global Reconnaissance Information System
Ultimately, GCCS will be able to operate in a        supports the planning and scheduling of monthly
multilevel security mode. See chapter 7 for more
information on multilevel security initiatives.


---

Communications and Information Systems _______________________________________________________________ 3-5

sensitive reconnaissance operations (SRO) theater    tors File or with the Service-provided data
requests. The Joint Staff staffs these requests      system.
through the Office of the Secretary of Defense,
the Central Intelligence Agency, and the State De-   3207. Global Status of Resources
partment for National Security Council approval.     and Training System
Incoming reconnaissance 1/2/3/4 formatted mes-
sages are received by an automated message han-      The Global Status of Resources and Training Sys-
dling system, validated, and passed to the Global    tem provides information on the status of units
Reconnaissance Information System application        with respect to personnel, equipment, and train-
for automated processing and database update.        ing. Query and display capabilities include cate-
The Global Reconnaissance Information System         gories of units (ships, fighter aircraft, ground
generates all reconnaissance messages and also       forces, etc.), specific types of units (frigates, ar-
monitors the monthly execution of theater recon-     mor battalions, F-15 squadrons, etc.), and a spe-
naissance missions approved in the previous          cific unit (displays detailed status information).
month. The Global Reconnaissance Information
System is used by the Joint Staff and theater com-   3208. Theater Analysis and
mands exercising OPCON over airborne recon-          Replanning Graphical Execution
naissance assets.                                    Toolkit

3205. Evacuation System                              TARGET contains a set of planning tools de-
                                                     signed to support the operational planner during
The Evacuation System collects and displays in-      crisis action procedures. These tools allow plan-
formation about U.S. citizens located outside the    ners and operators to accomplish tasks through
United States as collected by U.S. State Depart-     rapid access to required documents; information
ment embassies and consulates. It accesses the da-   sources; and analysis, multimedia, and teleconfer-
tabase server via TELNET from a GCCS-                encing tools.
compatible client.
                                                     3209. Joint Deployable
3206. Fuel Resources Analysis                        Intelligence Support System
System                                               (JDISS)

The Fuel Resources Analysis System provides fu-      JDISS applications provide access to national,
el planners with an automated capability for de-     theater, and tactical intelligence sources through
termining supportability of a deliberate or crisis   the joint architecture for intelligence. It provides
action plan and for generating the time-phased       protocols for connectivity and interoperability
bulk petroleum, oil, and lubricants required to      with intelligence systems required to support
support an operation plan (OPLAN). The Fuel          forces during peacetime, crisis, and war.
Resources Analysis System facilitates review of
the fuel requirements of a proposed, new, or re-     JDISS includes the protocols to access intelli-
vised OPLAN and assesses adequacy of available       gence link (INTELINK) at the secret classification
resources to support crisis action planning. Re-     level (INTELINK-S). INTELINK-S is an intelli-
quirements can be generated and analysis per-        gence dissemination service that enhances the
formed either for the overall OPLAN, or by           sharing of intelligence information electronically
Service, or by region within the AO. Two or more     over the SIPRNET. INTELINK provides intelli-
OPLANs can be combined into a single OPLAN           gence dissemination by using networked informa-
for analysis. The requirements generated can be
varied through the use of intensity tables and con-
sumption data extracted from the Logistics Fac-


---

3-6 ________________________________________________________________________________________________ MCWP 6-22

tion discovery, retrieval, and browsing services.   coded ground tracks for selected portions of the
Its “point and click” technology makes intelli-     order. ATO interfaces with the contingency the-
gence products widely available to both users and   ater automated planning system (CTAPS) and its
producers of intelligence. JDISS applications are   follow-on theater battle management core systems
able to exchange sensitive compartmented infor-     (TBMCS).
mation (SCI)—video and data—using the Joint
Worldwide Intelligence Communications System        3211. JMCIS
(JWICS). The JWICS communications network is
discussed in chapter 4.                             JMCIS is the foundation for the GCCS fused op-
                                                    erational battlespace picture. It displays near real-
3210. ATO                                           time ground, sea, and air tracks. JMCIS uses a
                                                    core service known as unified build to provide
The ATO application provides the capability to      geographic display, contact correlation, and track
view and print selected portions of ATOs. A que-    database management. JMCIS Unified Build
ry function allows the user to tailor requests for  served as the basis for the original GCCS COE,
information in a specified order for viewing. The   which has evolved into the DII COE.
query function also supports the display of color-


---

Communications and Information Systems _______________________________________________________________ 3-7

 Section III

MAGTF C4I

MAGTF C4I is the concept for the integration of      q Pursuit of a naval architecture that integrates
Marine Corps tactical information systems and           USMC, Coast Guard, and Navy requirements.
the migration of selected systems to the DII COE.
The MAGTF C4I concept is consistent with DOD         q Focus on support of naval expeditionary forces
mandates for DII compliance and designation of          in a joint environment.
standard migration systems. MAGTF C4I pro-
vides commanders and their staffs at all levels of   q Pursuit of nondevelopmental items (NDI),
the MAGTF with the capability to send, receive,         COTS and GOTS solutions.
process, filter, and display data to aid them in
their decisionmaking process. MAGTF C4I also         q Exploitation of Windows NT® to avoid the
provides a shared situational awareness through a       technical complexity and high costs associated
common picture of the battlespace.                      with developing, integrating, operating, and
                                                        maintaining UNIX-based systems.
3301. Migration Strategy
                                                     3302. MAGTF C4I Software
The MAGTF C4I migration strategy focuses on          Baseline Capabilities
incorporating the software functionality of
MAGTF tactical information systems into a            Table 3-1 (on pages 3-8 and 3-9) describes the
MAGTF C4I Software Baseline. Standard soft-          current capabilities of the MAGTF C4I Software
ware mission applications and the capabilities to    Baseline. Capabilities are added as new segments
support MAGTF C2 functions are described and         are approved and incorporated into the MAGTF
developed under the MAGTF C4I Software Base-         C4I Software Baseline. As more capable seg-
line Program. The MAGTF C4I Software Base-           ments are added, many older segments will be
line relies on the DII COE to provide its common     eliminated. These upgrades will occur continually
software environment. The MAGTF C4I Soft-            as new releases of the MAGTF C4I Software
ware Baseline is developed using the DII COE         Baseline are fielded to the FMF.
software as its foundation. The MAGTF C4I Soft-
ware Baseline configuration is coordinated with      3303. Hardware/Operating
and controlled under the JMCIS Unified Build         System Requirements
and DII COE programs. This strategy is based on
the following:                                       MAGTF C4I Software Baseline uses Marine
                                                     common hardware suite (MCHS) equipment, in-
q Integration with the DOD GCCS. No function-        cluding the Hewlett-Packard TAC-4, CHS-2 Sun
   ality offered by GCCS will be duplicated by the   SPARC 20, and Intel PC platforms running the
   MAGTF C4I Software Baseline. All MAGTF            DII COE. The MAGTF C4I Software Baseline is
   C4I Software Baseline functionality that has      completely transportable across the GCCS hard-
   joint applicability will be nominated for use by  ware platforms. These systems are certified
   GCCS.                                             through the security accreditation process in ac-
                                                     cordance with current DISA requirements. Vari-
q Commitment to the DII COE and the evolution        ous SECNAVINSTs provide guidance on security
   to open systems, including Windows NT®,           certification and accreditation procedures within
   Windows 95®, and Java®.                           the Department of the Navy (DON).


---

3-8 ________________________________________________________________________________________________ MCWP 6-22

Table 3-1. MAGTF C4I Software Baseline Capabilities ..

                                               COE

           Segment                                                 Description/Purpose

Windows NT                                     Universal Applications

Plotter                             Application programming interfaces for mapping, communications, track database, and alerts
Symbols                             from command and control PC and UNIX DII COE code. It is the minimum set of application
Tactical Digital Information Link   program interfaces required for NT DII COE development.
(TADIL) A/B
Tactical Communications Interface   Ability to plot a tactical map overlay of a user-specified area on an acetate sheet.
Module (TCIM)
Command and Control PC              This COE improvement provides the capability to display MIL STD 2525 symbols and overlays
Netscape                            to the common operational picture/common tactical picture display.

MS Office                           This COE improvement provides the capability to receive, parse, and display TADIL A and B
WABI                                tracks.

Position Location Information Sys-  Capability to exchange over-the-horizon (OTH)-Gold tactical messages over SCR via the TCIM
tem (PLIS) and JPI                  modem using the Marine tactical systems protocol.
Routes
                                    MS Windows NT client program that provides the capability to participate in the common opera-
MIG                                 tional picture and common tactical picture using an Intel PC.

System Planning, Engineering, and   COTS World Wide Web (WWW) browser and e-mail. It will also provide Web page production
Evaluation Device (SPEED)           and shared whiteboard collaboration tools. May replace the functionality of Internet News, Intel-
                                    ligence Relay Chatter, and JDISS.
Air Field
TARGET                              COTS package that provides advanced word processing, graphics, spreadsheet, presentation
                                    graphics, and scheduling capabilities.

                                    Capability to run a subset of MS Windows 3.11 applications, including MS Office, on a UNIX
                                    workstation. It is also required to run MS Office.

                                                       Maneuver

                                    Capability to receive, parse, and inject tracks into the track database from global positioning sys-
                                    tem (GPS) and other position location information (PLI) systems.

                                    Graphical route planning tool with an overlay builder and trafficability analysis.

                                                      Intelligence

                                    Centralized database server for intelligence databases. Provides access to the National Informa-
                                    tion Database. Tactical data can be accessed, output, and updated by analysts at local and remote
                                    locations. Naval Intelligence Processing System (NIPS) applications are resident in MIG. NIPS
                                    also provides capabilities to process and store message traffic from various sources, generate and
                                    transmit messages, and create briefings with mapping and imagery tools.

                                                  Communications

                                    SPEED applications will be available in the MAGTF C4I Software Baseline when converted to
                                    operate in Windows NT.

                                            Strategic and Operational

                                    Worldwide database of airfield capabilities by individual location.

                                    Timeline-based, time-phased force deployment data (TPFDD) editing and analysis tool.


---

Communications and Information Systems _______________________________________________________________ 3-9

Table 3-1. MAGTF C4I Software Baseline Capabilities (continued).

                                                      COE

           Segment                                                 Description/Purpose

Evacuation System                   Database of potential evacuees at foreign service posts.
Force Augmentation Planning and     OPLAN mobilization planning, analysis, and execution tool.
Execution System (FAPES)
Fuel Resources Analysis System      OPLAN fuel capacity, requirement, and expenditure tool.
GCCS ATO Review (GARC)              ATO confirmation message browser. Data is parsed from messages sent by CTAPS. May dupli-
                                    cate the NIPS functionality for Sun SPARCs.
Global Status of Resources and      Tool to enter status of unit locations, deployment readiness, and training.
Training System
Global Transportation Network       Visibility into USTRANSCOM transportation data for the global transportation network.
(GTN)
Individual Manpower Requirements    Individual mobilization planning and execution tool.
and Availability System (IMRAS)
Imagery Product Archive (IPA)       Imagery files and products database.
Internet News                       SIPRNET bulletin board tool.
Intelligence Relay Chatter          SIPRNET chat tool.
JDISS                               Multimedia applications used to access intelligence information databases over INTELINK and
                                    other networks.
Joint Engineer Planning and Execu-  OPLAN civil engineering tool.
tion System (JEPES)
JOPES: Ad Hoc Query                 Ad hoc querying capability to the JOPES using data fields and Boolean operators from a pick list.
                                    May duplicate the NIPS ad hoc functionality.
JOPES: Information Resource Man-    Generic database manipulation tool for compositing OPLANs.
ager (IRM)
JOPES: JOPES Navigation (JNAV)      JOPES front-end tool.
JOPES: Predefined Reports (PDR)     JOPES OPLAN report tool.
JOPES: Requirement Development      JOPES TPFDD force module generator.
Analysis (RDA)
JOPES: Scheduling and Movement      JOPES TPFDD scheduling and movement tool.
(S&M)
Logistics Sustainment Analysis and  Logistics sustainment, feasibility, resupply requirements, contingency plans, and “black-bottom”
Feasibility Estimator (LOGSAFE)     cargo transportation tool.
Medical Planning and Execution      OPLAN medical requirements tool.
System (MEPES)
Oracle                              COTS relational database management system that provides access to the various databases
                                    within the system. It allows the users to access, query, and update information in the databases.
                                    May duplicate the NIPS Sybase functionality.


---

3-10 _______________________________________________________________________________________________ MCWP 6-22

Although the MAGTF C4I Software Baseline             field. TCO supports the development of COAs
maintains UNIX operating system segments, new        and the preparation and dissemination of
development is based on Windows NT. The              OPLANs and OPORDs, including overlays that
UNIX-based TAC-4 and CHS-2 platforms are in-         are geographically referenced to an electronic
terim application and data servers. However, both    map.
IAS and TCO workstations are transitioning to a
common PC-based Windows NT® environment.             TCO supports the operations sections of all FMF
                                                     units of battalion/squadron size and larger as well
All systems will be DII COE/MAGTF C4I com-           as planning sections at higher echelons. TCO con-
pliant. All systems will operate on the standard     sists of computer workstations operating at the se-
MCHS of equipment and will be distinguished          cret level on multiple LANs interconnected on the
only by the set of applications or functional seg-   SIPRNET through MAGTF communications net-
ments resident on the computer. The Marines that     works. TCO components include the MCHS ter-
use each of the functional area tactical data sys-   minals, the tactical communications interface
tems (TDS) in this section are responsible for set-  module (TCIM) for radio interface, and LAN
ting up, operating, and maintaining those systems    equipment. The functional manager for TCO is
(e.g., Marines from the G-3/S-3 will be responsi-    the G-3/S-3, and COC personnel are responsible
ble for setting up, operating and maintaining TCO    for setting up the TCO equipment in their opera-
and Marines from the G-2/S-2 will have those re-     tions centers. Communications and information
sponsibilities for IAS). CIS personnel will assist   systems personnel are responsible for connecting
these functional users in the operation and main-    TCO terminals to the SIPRNET, providing them
tenance of their systems and provide external net-   with IP network host addresses, and assisting op-
work connectivity and IP addresses. This division    erations COC personnel in installing and main-
of responsibilities requires close cooperation and   taining the TCO.
coordination between the functional system user
and CIS personnel and applies to all of the infor-   JMCIS-Afloat and TCO are both built around the
mation systems described in this section. System     JMCIS Unified Build core software. This permits
descriptions in paragraphs 3304–3309 are orga-       Marine forces embarked aboard Navy ships to
nized by the functional area that they support.      “plug in” to the JMCIS-Afloat. Furthermore, be-
                                                     cause the JMCIS Unified Build served as the
3304. Maneuver                                       baseline for the DII COE, migration of TCO to
                                                     the DII COE is occurring rapidly. DII COE com-
Maneuver systems support operations planning         pliance will provide complete interoperability
and execution by providing commanders and            with GCCS and other DII COE compliant sys-
staffs with shared situational awareness through     tems.
an integrated representation of the battlespace.
Maneuver systems pull and fuse information from      3305. Intelligence
all functional areas. These systems provide the
means for mission receipt and rapid development      Intelligence systems support the timely planning,
and dissemination of the commander’s intent and      collection, processing, production, and dissemina-
OPLANs and OPORDs.                                   tion of all-source intelligence. In addition, these
                                                     systems support the effective employment of re-
The tactical combat operations (TCO) system          connaissance, surveillance, and target acquisition
provides an automated capability to process bat-     resources.
tlefield information. TCO provides timely infor-
mation to help commanders and their staffs           a. IAS
conduct operations planning and make critical C2
decisions. TCO processes and fuses tactical infor-   Intelligence analysis system (IAS) provides
mation to form a common picture of the battle-       MAGTF intelligence personnel with intellopera-


---

Communications and Information Systems _____________________________________________________________ 3-11

tions planning and direction, all-source process-     workstations, two SUN servers, and five radios
ing and fusion, and dissemination capabilities.       (one HF, two VHF, one UHF, and one UHF satel-
IAS is the principal Marine Corps intelligence in-    lite communications [SATCOM]). Through its
formation system. The G-2/S-2 is the functional       automated processing, analysis, and reporting ca-
manager for IAS, and intelligence personnel are       pability, TCAC PIP enhances the overall control
responsible for setting up IAS equipment in their     and management of SIGINT assets as well as the
intelligence centers. MEF IAS is a sheltered, mo-     development and dissemination of SIGINT prod-
bile system with multiple (scalable) analyst work-    ucts. Timely, fused, and filtered SIGINT products
stations in a client-server LAN configuration. IAS    are provided to MAGTF commanders, usually
suites for intermediate commands are configured       through the MAFC.
in a four-workstation LAN. Single IAS worksta-
tions support battalions and squadrons. IAS uses      d. Joint Surveillance Target Attack
MCHS equipment and will transition to the DII         Radar System
COE. IAS hosts the secondary imagery dissemi-
nation system (SIDS), and links are planned with      The JSTARS aircraft is a U.S. Air Force asset that
other intelligence systems at the national (DOD       can provide the MAGTF commander with a near-
Intelligence Information Systems [DODIIS]), the-      real-time depiction of the surveillance area for in-
ater, and tactical (including TCAC, Tactical Elec-    telligence and battlespace situational awareness.
tronic Reconnaissance Processing and Evaluation       JSTARS detects and tracks moving and stationary
System (TERPES), and Joint Services Imagery           ground targets in the AO, including data on ene-
Processing System [JSIPS]) levels.                    my forces and position location of friendly forces.
                                                      Access to this theater asset also enhances target
b. MAGTF SIDS                                         acquisition and identification, postattack combat
                                                      assessment, indications and warning, cueing/
The manpack SIDS device provides the capability       cross-cueing among intelligence collectors, oper-
to electronically collect, transmit, and receive im-  ations planning and execution, and pattern analy-
agery products throughout the MAGTF, as well as       sis/intelligence fusion.
through adjacent, higher, and external commands.
MAGTF manpack SIDS uses MAGTF communi-                JSTARS consists of two major components: the
cations networks and complies fully with the na-      U.S. E-8C aircraft and the common ground sta-
tional imagery transmission format (NITF)             tion (CGS), which provides connectivity to the
Version 2.0 and the Tactical Communications           aircraft. The sensor suite provides target detection
Protocol (TACO II). MAGTF SIDS is fielded in          and tracking through moving target indicator,
two configurations. One configuration is hosted       fixed target indicator, and synthetic aperture radar
on the IAS; the other is a standalone manpacked       data. The aircraft transmits data sets to the CGS
configuration. Both configurations allow the user     via a surveillance control data link. The CGS ter-
to display, manipulate, annotate, print, transmit,    minates the surveillance control data link and pro-
and receive images on a multipurpose worksta-         cesses and manipulates the sensor data sets. Map
tion.                                                 data are registered and topographical features en-
                                                      tered on the two operator workstations and digi-
c. TCAC Product Improvement                           tized plotting boards within the CGS. The
Program                                               JSTARS picture will be fed simultaneously from
                                                      up to four CGS remote workstations, which may
Tactical control and analysis center product im-      be located in the MAFC, the current operations
provement program (TCAC PIP) provides the ra-         cell, the FFCC, the future operations cell, or other
dio battalions with a fully capable SIGINT            C2 nodes. The MAFC serves as the principal C2
processing, production, and dissemination sys-        node for correlating, analyzing, and interpreting
tem (and other C2 information systems) that is        JSTARS information and for its dissemination to
shelter-mounted on a heavy variant, high-mobili-      MAGTF subordinate units.
ty, multipurpose wheeled vehicle (heavy HM-
MWV). The TCAC PIP includes three SUN


---

3-12 _______________________________________________________________________________________________ MCWP 6-22

In the future, full JSTARS data sets (moving tar-     and dissemination of electronic reconnaissance
get indicator, fixed target indicator, and synthetic  information. Data is received from EA-6B aircraft
aperture radar imagery), fused intelligence, track    by data links, magnetic tape, and crew logs. TER-
database information, and contact and track data      PES also supports EA-6B mission planning, brief-
information will be available throughout the          ing, and debriefing and generates intelligence for
MAGTF down to regimental/MAG levels via               strike mission planning. TERPES fuses data from
IAS, TCO, and/or the Advanced Field Artillery         EA-6B missions with information from other na-
Tactical Data System (AFATDS) by using the            tional and theater sources to update the electronic
TDN backbone.                                         order of battle and passes intelligence to the IAS
                                                      for further processing and dissemination. TERP-
e. Mobile Electronic Warfare Support                  ES is housed in one 8-foot by 8-foot by 20-foot
System Product Improvement                            shelters dedicated to mission analysis, mission
Program                                               planning, and mission support.

The MEWSS, mounted in an LAV, provides SIG-           3306. Air Operations
INT/EW support to a wide variety of missions, in-
cluding LAR operations. The MEWSS PIP                 Air operations systems support the planning, co-
provides the radio battalions with an upgraded        ordination, and control of MAGTF air combat op-
SIGINT/EW suite. The MEWSS PIP is a wide-             erations and interface with Navy, joint, and
band intercept system that provides a complete        combined forces air operations systems. These
picture of the enemy electronic order of battle and   systems also interface directly with fire support
state of the art electronic warfare support mea-      systems.
sures (ESM). The system contains three primary
mission subsystems that are also part of the Ar-      The MACCS provides the tactical air commander
my’s Intelligence/EW Common Sensor program.           with the automated support required to exercise
                                                      control over MAGTF air operations. MACCS
The primary mission subsystems consist of a           supports tactical air command, tactical air opera-
communications intelligence (COMINT) system           tions, air defense, and direct air support. Person-
that provides intercept, collection, and geoloca-     nel dedicated to these systems provide support for
tion across a broad frequency range and a capabil-    their installation, operation, and maintenance. The
ity against a variety of modern threat                MWCS provides the multichannel communica-
communications emitters; an electronic intelli-       tions connectivity that links the airfields and for-
gence (ELINT) system that provides interception,      ward sites, as well as the long haul single channel
identification, and geolocation of noncommunica-      radio support between higher and adjacent com-
tions emitters, including counterbattery and bat-     mands and the wing headquarters and TACC.
tlefield radar; and a precision location system to
locate communications emitters to within target-      a. Tactical Air Command Systems
ing accuracy. The MEWSS PIP system includes
an electronic attack (EA) module that is capable      Tactical air command systems provide the tactical
of “smart” and conventional jamming. The              air commander with support for planning, control-
MEWSS PIP is completely interoperable with Ar-        ling, and coordinating overall MAGTF air opera-
my Intelligence/EW Common Sensor platforms,           tions. Functions supported include determination
thereby allowing cooperative engagement and da-       of operational requirements, allocation of aircraft,
ta sharing.                                           publication of ATOs, planning of air operations,
                                                      coordination and supervision of execution, and
f. TERPES                                             coordination with naval and joint agencies.
                                                      CTAPS, one of the mission applications support-
Tactical Electronic Reconnaissance Processing         ing tactical air command, is used to create and
and Evaluation System (TERPES) is a system that       disseminate the ATO. The Joint Chiefs of Staff
supports the reception, processing, evaluation,


---

Communications and Information Systems _____________________________________________________________ 3-13

have mandated the use of CTAPS for joint ATO           an integrated system that consists of five light-
dissemination. CTAPS runs at the secret level on       weight multipurpose shelter Type-1 systems
UNIX-based MCHS servers on the TACC LAN.               mounted on M-1097 heavy HMMWVs. Each
The MWCS provides each CTAPS workstation               operations shelter contains five operator worksta-
with an IP host address and connects the TACC          tions capable of conducting integrated aviation
LAN to remote airfields, DASC, TAOC, and oth-          C2 functions. Each high-mobility downsized
er Service command centers over SIPRNET by             DASC vehicle tows an M-116 trailer that carries a
using IP routers and organic transmission assets.      generator and external cables. The trailers associ-
Tactical air command systems are evolving to           ated with the operations suites also carry one
provide improvements in a number of areas, in-         quick-erect shelter. The system design allows for
cluding migration to common hardware and DII           maximum employment flexibility to support any
COE compliance, mobility, and Joint Tactical In-       level of MAGTF operations, providing the FMF
formation Distribution System (JTIDS) integra-         with a lightweight, highly mobile system that is
tion. Through such enhancements, tactical air          capable of responsive direct air support C2.
command systems will provide the automated
tools needed to effectively plan, coordinate, and      3307. Fire Support
direct all MAGTF tactical air operations.
                                                       Fire support systems support the planning, coordi-
b. Air Defense Systems                                 nation, and control of artillery, air, and naval gun-
                                                       fire.
The Tactical Air Operations Center (TAOC) is
the C2 agency that controls tactical air operations    a. Fire Support Command and Control
and coordinates the air defense of the MAGTF.          System (FSC2S)
The TAOC consists of the AN/TYQ-23(V)1 Tac-
tical Air Operations Module (TAOM) and associ-         The FSC2S is designed to meet the basic require-
ated sensors, the AN/TPS-59, AN/TPS-63, and its        ments for a fully automated fire support system. It
replacement, the AN/MPO-62 radars, and the sec-        provides initial semiautomated tactical fire sup-
tor antiair warfare facility. The TAOM provides        port and technical artillery fire control functions
automated support for surveillance, weapons con-       for MAGTF operations. The follow-on AFATDS
trol, air traffic control, and training. The operator  completes the transition to fully automated fire
console of the TAOM is being upgraded to pro-          support C2. There are two components to the
vide GCCS functionality and a Windows inter-           FSC2S: the fire control system and the battery
face. The Sector Antiair Warfare Facility provides     computer terminal.
the tactical air picture from the TAOM to the sec-
tor antiair warfare coordinator and enables an au-     The FSC2S is employed at FDCs down through
tomated interface between CTAPS and TAOM               the firing battery level, at FSCCs down through
for passing the ATO. JTIDS implementation is           the battalion level, at the SACC, and by the
ongoing and will provide greatly enhanced, se-         MAGTF CE to support fire planning and tactical
cure, high-capacity, jam-resistant information dis-    fire direction. The FSC2S is supported by digital
tribution capabilities as well as improved             fire support communications nets.
interoperability for the conduct of joint air de-
fense and theater missile defense operations.          b. Advanced Field Artillery Tactical
                                                       Data System (AFATDS)
c. Direct Air Support Systems
                                                       The AFATDS is a joint Army/Marine Corps sys-
The high-mobility downsized DASC provides au-          tem which will replace the initial fire support au-
tomated support to the DASC for the conduct of         tomated system (IFSAS). It is a multi-service,
air operations directly supporting ground forces.      integrated, battlefield management and decision
It provides support for the coordination of close      support system which incorporates automation in-
air strikes, assault support, and air reconnaissance   to the fire support warfighting function to assist
missions. The high-mobility downsized DASC is


---

3-14 _______________________________________________________________________________________________ MCWP 6-22

the commander in the planning, delivery, and co-      (2) MAGTF II/Logistics Automated Information
ordination of supporting arms. These terminals
will be located in FSCCs, DASC, TACC, and ar-         System (LOGAIS). This family of systems sup-
tillery battalion and regimental FDCs. AFATDS         ports Marine Corps ground logistic data require-
will provide the MAGTF commander with the ca-         ments. The MAGTF II system is the primary
pability to rapidly integrate ground, air, and naval  planning tool for selecting and tailoring a
surface fire support with the scheme of maneuver.     MAGTF and for providing updates to JOPES to
The AFATDS software architecture is interopera-       support FDP&E. It includes TC-AIMS and
ble with Marine Corps CIS, GCCS COE, and              MDSS II. TC-AIMS II, a joint system, will even-
MAGTF C4I baseline systems.                           tually replace TC-AIMS and MDSS II. TC-AIMS
                                                      and ATLASS will be the primary systems that
3308. Logistics                                       provide functional logistics management for sus-
                                                      tainment and distribution.
LOG systems support logistic planning and oper-
ations. These include all logistic functions sup-     (3) Transportation Coordinators’ Automated
porting deployment, employment, and                   Information for Movement System (TC-AIMS).
reconstitution of forces.
                                                      TC-AIMS provides automated support for motor
There are two basic uses for information: to pro-     transport control, planning of support, and coordi-
mote situational awareness as the basis for a deci-   nation of overland movement and convoys. It
sion and to direct and to coordinate actions in the   manages use and movement of day-to-day motor
execution of that decision. There are currently       transport and heavy equipment. Its resource-man-
over one hundred logistic information systems         agement module provides inventory, support re-
utilized within the Marine Corps to support Force     quests, and task and dispatch management. It
Deployment Planning and Execution, sustainment        supports convoy management with an embarka-
and distribution. Biannually, the Installations and   tion and marshaling module. It tracks critical
Logistics Department, Headquarters Marine             events, including user time statistics. TC-AIMS
Corps publishes a comprehensive listing of these      interfaces with the MAGTF Deployment Support
systems in a Logistics Information Resources          System II (MDSS II). This system, along with
Plan (Log IR Plan). The Log IR Plan provides a        TC-AIMS, assists in deployment planning and ex-
roadmap for how logistics information systems         ecution and unit movement at the MEF level and
will utilize information technology methods. It al-   below. The integrated MAGTF/LOGAIS soft-
so provides a migration strategy that tailors the     ware will enable an improved degree of integra-
number of systems by eliminating redundancies         tion between MDSS II and TC-AIMS.
and leveraging joint systems where appropriate.
While by no means a complete listing, the follow-     (4) Theater Medical Information Program
ing provides a top down view of the significant of
information systems currently in use to support       (TMIP). TMIP provides a global capability that
force structure, movement, sustainment, materiel      links medical information databases to integration
readiness, and fiscal management.                     centers; these integration centers are accessible to
                                                      Navy medical personnel while engaged in support
a. Systems in Support of Operations                   of Marine forces. The goal for TMIP is to provide
                                                      theater medical integrated automated information
(1) Standard Accounting, Budgeting, and Re-           using Global Command and Control System
                                                      (GCCS) and Global Combat Support System
porting System (SABRS). SABRS is a DOD                (GCSS) that links all echelons of medical care in
automated system used by Marine Corps fiscal          support of Marine forces.
planners to account for and report expenditures of
appropriated funds and for use in submissions to      (8) MDL. MAGTF Data Library is the data
the DOD budget cycle.                                 dictionary tool used to facilitate gathering of valid
                                                      source data for use by all of the MAGTF/LOG-
                                                      AIS family of systems.


---

Communications and Information Systems _____________________________________________________________ 3-15

(5) MDL. MAGTF Data Library is the data                cessing support for maintenance of all aviation
dictionary tool used to facilitate gathering of valid  equipment and spares to aviation units and select-
source data for use by all of the MAGTF/LOG-           ed base and garrison activities throughout the
AIS family of systems.                                 Marine Corps.

b. Systems in Support of Materiel                      (6) Shipboard Uniform Automated Data Pro-
Readiness
                                                       cessing System (SUADPS). This is the supply
(1) Global Status of Resources and Training            software application used by MALS to provide fi-
                                                       nancial, inventory, and logistic management of
System (GSORTS). GSORTS provides informa-              aviation supply support for Marine aircraft.
tion on the readiness status of units with respect to
personnel, equipment, and training.                    (7) Conventional Ammunition Integrated Man-

(2) Asset Tracking Logistics and Supply                agement System (CAIMS). CAIMS provides
                                                       on-line inventory management data such as am-
System (ATLASS). ATLASS provides automat-              munition location, quantity, material condition,
ed support for supply and maintenance. It replaces     purpose code, and requisition status.
two mainframe-based systems developed in the
early 1970s—the Marine Integrated Maintenance          3309. Force Deployment
Management System (MIMMS) and the Support-             Planning
ed Activities Supply System (SASSY)—with a
client-server system based on an open systems ar-      Force deployment planning systems support plan-
chitecture. ATLASS is being implemented                ning for the movement of forces and their sustain-
through phased development, with the current           ment from original locations to specified
phase focusing on integrating user-unit supply         operational areas. The MAGTF II system supports
and shop-level maintenance functions.                  deployment planning. It enables Marine deploy-
                                                       ment planners to conduct both deliberate and time-
(3) Naval Tactical Command Support System.             sensitive (crisis action) planning. By using
                                                       MAGTF II, planners can select and tailor
NTCSS is a fleet tactical command support sys-         MAGTFs and estimate sustainment and lift re-
tem used by the ACE. NTCSS replaces 1970s vin-         quirements. MAGTF II is a PC-based system that
tage fleet equipment with modern minicomputers,        supports TPFDD development and maintenance,
personal computers, and local area networks. It        with the results uploaded to JOPES. MAGTF II
provides status and ad hoc reports to the Battle       can operate on a LAN, although system users and
Group Logistics Coordinated Support System             administrators must be mindful of security con-
(BGLCSS). The system is formulated around              cerns. Because of its usability, versatility, and
SNAP III, which began the process of integrating       portability, MAGTF II has been nominated as a
shipboard computers by adopting the command            migration system that will, with specific modifica-
and control systems architecture for command           tions, serve all Services and the Joint Staff as an
support applications.                                  automated tool to support deployment planning
                                                       and execution. For detailed information on force
(4) Shipboard Nontactical ADP Program III              deployment planning, see Joint Pub 5-03.1, Joint
                                                       Operation Planning and Execution System, Vol-
(SNAP III). The Marine wing support group              ume I.
(MWSG) and MALS use SNAP III hardware to
provide automated information processing sup-          The MAGTF C4I systems described above nor-
port for supply, finance, and organizational main-     mally operate on LANs in various C2 facilities of
tenance management.                                    the MAGTF. A notional layout of the systems that
                                                       support COCs is in figure 3-3 (on page 3-16).
(5) Naval Aviation Logistics Command Man-
agement Information System (NALCOMIS).

MWSG and MALS use the NALCOMIS software
application to provide automated information pro-


---

3-16 _______________________________________________________________________________________________ MCWP 6-22
                                                     Figure 3-3. Supporting Systems.


---

Communications and Information Systems _____________________________________________________________ 3-17

                 Section IV

The Defense Message System

DMS is an evolving system that consists of all        systems will be phased out and DMS capabilities
hardware, software, procedures, standards, facili-    will be upgraded by the end of calendar year
ties, and personnel used to exchange messages         2008. Services and agencies have been tasked to
electronically between organizations and individ-     develop transition plans for implementation of the
uals in the DOD. The current subsystems of the        new system and have been asked to include sup-
DMS are the automated digital network (AUTO-          ported CINCs in their plans. DMS has been desig-
DIN) (which includes base-level support systems)      nated the single DOD message system and will be
and e-mail. DMS will have a store and forward         integrated with all applications that have embed-
capability. The DMS must support interfaces to        ded messaging functions, such as GCCS.
systems of other government agencies, allies, tac-
tical systems, and defense contractors. System us-    3402. Upgrades
ers may be deployed or in garrison, fixed or
mobile. The planned or objective system will re-      Joint requirements, policy, doctrine, and architec-
place the current subsystems, based on DOD            ture and a transition plan for interfacing and in-
standards, with a single system based on interna-     corporating tactical users into the DMS are still
tional standards established by the International     under development. At present, tactical message
Organization for Standardization (ISO). Security      traffic enters the long-haul network primarily
services, including authentication, integrity, con-   through AUTODIN switching centers and auto-
fidentiality, and registration, are provided through  matic message processing exchanges. The AU-
the Fortezza Personal Computer Memory Card            TODIN interface into the DMS is scheduled to be
International Association (PCMCIA) card, which        phased out by 31 December 1999; therefore, the
is discussed later in this chapter. The primary ob-   impact on tactical users, including the need to in-
jective of the DMS is to maintain existing service    teroperate with legacy tactical message switches,
and security while reducing cost and staffing.        will be felt over several years. The primary
                                                      MAGTF message handling system replaced by
3401. AUTODIN                                         DMS is the AN/MSC-63A message switch. DMS
                                                      also replaces VINES mail, a proprietary messag-
The transition to the objective system involves re-   ing system used throughout the Marine Corps.
placing AUTODIN delivery systems and existing         DMS will improve tactical messaging by provid-
e-mail capabilities based on the simple mail trans-   ing a seamless system across the strategic and de-
fer protocol (SMTP) with e-mail based on the ISO      ployed environments. It provides a secure, timely,
X.400 message handling protocol and the sup-          reliable writer-to-reader messaging service. The
porting X.500 ISO standard for directory services.    DMS program helps to integrate the tactical and
The transition also involves transitioning the se-    strategic environments and is a key component of
curity and service management infrastructure. Fi-     the DII. CJCSM 6231.03A, Joint Data Systems,
nal AUTODIN closeout is scheduled for 31              provides additional detailed information about the
December 1999. Remaining non-DMS message              DMS.


---

3-18 _______________________________________________________________________________________________ MCWP 6-22

                                 Section V

                        Information Services

Information management and exchange are sup-        chical fashion, much like a file system. The re-
ported not only by the information systems de-      mainder of the domain name is administered by
scribed previously, but also by common              the network administrator of the subnetwork, and
information services hosted on servers throughout   the subnetwork is often broken up into additional
the MAGTF. Many of these information services       zones to ease administration. The network admin-
have already been mentioned as part of the DII      istrator is responsible for setting up name servers
COE and the MAGTF C4I Software Baseline. Fig-       to handle requests for domain name-to-address
ure 3-4 shows these services, which are described   resolution for the network administrator’s zones.
in the following paragraphs. These services en-
able the flow of information over the communica-    3502. Terminal Emulation
tions networks supporting the MAGTF.                Services

Communications          Mission Application         Terminal emulation services provide the capabili-
Fax                     File                        ty for remote users to access logistic and person-
Message                 Database                    nel applications hosted at DISA megacenters.
Security/Firewall       Network Operating           Remote logins are supported through a synchro-
                        System                      nous terminal emulation using the TELNET pro-
Defense Message         Network Management          tocol.
System
World Wide Web          Directory                   3503. Message Handling Services
Print                   Domain Name
Network Administration  TELENET 3270                Message handling services provide message stor-
                                                    age, transfer, forwarding, routing, translation, and
             Figure 3-4. Information Services.      format conversion. Services include SMTP, mul-
                                                    tipurpose Internet mail extension (MIME), and
3501. Directory Services                            ACP 123 message handling capability.

Directory services consist of Marine Corps stand-   3504. Network Management
ard network directory service application, the do-  Services
main name system (DNS), and X.500. The Marine
Corps standard network directory service applica-   Network management services link a Network
tion is Banyan Street Talk Directory Assistance.    Management System and networked devices (e.g.,
As mentioned above, X.500 is the ISO standard       servers) being managed. Network management is
for directory services that supports X.400 messag-  provided through the simple network manage-
ing and will be part of DMS. DNS is a directory     ment protocol (SNMP) Through SNMP the sys-
service that links Internet domain names to the IP  tem administrator is alerted when traffic patterns
addresses specified by network administrators.      and conditions indicate that a networked device is
The DNS organizes the names of hosts in a hierar-   failing or has failed. A network manager can set
                                                    thresholds for devices and receive an alarm when
                                                    the threshold is reached.


---

Communications and Information Systems _____________________________________________________________ 3-19

a. Configuration Management                          a. Fortezza Cards
Configuration management includes resource ser-
vicing, testing, and reporting; software distribu-   The Fortezza card is a security component that
tion and licensing; planning; and management.        provides user privileges for sending and receiving
Configuration management also includes the plan-     DMS messages. The Fortezza cards include pri-
ning and use of directories. Configuration man-      vate security keys and user messaging privileges.
agement requires maintenance of complete             User messaging privileges include individual mes-
records of users, assignments, equipment, and oth-   saging and organizational message release, in-
er information needed to administer the network.     cluding organizational level, precedence, and
Planning support consists of development, dis-       classification authorized. Directory queries for
semination, and coordination of letters of instruc-  DMS directory services are authenticated by the
tion, Annex K for OPLANs\OPORDs, routing             digital signature function of the Fortezza PC card
tables, address assignments, and message han-        to allow access to the X.500 directory. The Fortez-
dling instructions.                                  za PC cards are programmed by using the certifi-
                                                     cation authority workstation.
b. Fault Management
Fault management consists of fault determination,    b. Certification Authority Workstation
correction, prevention, reporting, and archiving.
File server backup and recovery functions consist    The certification authority workstation is a PC-
of providing backup and recovery services locally    based application used to program and maintain
and from one server to another in the network.       Fortezza PCMCIA cards for users. These Fortez-
                                                     za cards (one per person) include not only private
c. Performance Management                            security keys, but also the user messaging privi-
Performance management consists of perfor-           leges. Local authorities use the DMS agent soft-
mance and traffic characterization, performance      ware applications resident in the certification
testing, performance timing and correction, con-     authority workstation to perform distributed di-
trol of performance management, reporting, and       rectory and security management tasks. This
archiving.                                           trusted workstation supports functions that in-
                                                     clude decentralized assignment of directory
d. Security Management                               names and creation of X.509 certificates. As part
Security management consists of configuration        of this process, the applications initialize each us-
management of security components, security          er’s Fortezza card with a personal identification
mechanism management (including identification       number (PIN), X.509 certificate(s), and selected
and authentication, discretionary access control,    DMS information.
object reuse, and the use of audit trails), system
vulnerability reduction, and other methods to pre-   c. In-line Network Encryptors
vent security breaches. Figure 3-5 (on page 3-20)
is an outline of the interactions and relationships  In-line network encryptors use the Secure Data
between the various MAGTF C4I services and           Network System standards from the National Se-
protocols.                                           curity Agency and interface to the National Elec-
                                                     tronic Key Management System. In-line network
3505. Security Services                              encryptors provide end-to-end security between
                                                     hosts and workstations running on secure LANs.
Information systems security is discussed in depth   In-line network encryptors allow secure commu-
in chapter 7.                                        nications over public, packet-switched, and un-
                                                     classified backbone networks. In-line network
                                                     encryptors incorporate an open architecture.


---

3-20 _______________________________________________________________________________________________ MCWP 6-22

Figure 3-5. MAGTF C4I Services and Protocols.

3506. Facsimile Services                             This server provides dynamic addressing and rout-
                                                     ing services that allow automated selection of the
Facsimile services allow the sending and receiv-     pooled communications resources at a central lo-
ing of electronic text, graphics, and images         cation. It interfaces with the message handler and
through the switched telephone network. The fac-     the TCIM to provide automated radio network
simile server provides storage, routing, and trans-  message addressing and routing. This server sup-
lation of data.                                      ports Marine tactical systems, Transmission Con-
                                                     trol Protocol (TCP)/IP, e-mail, file transfer,
3507. Communications Services                        SNMP, and SMTP.

Communications services provide communica-
tions management between LANs and WANs.


---

Communications and Information Systems _____________________________________________________________ 3-21

                  Section VI

Shipboard Information Systems

Naval amphibious ships provide CIS support to       complete all-source information management,
embarked Marine forces as well as spaces from       display, and dissemination capabilities. These in-
which to exercise command and control. Avail-       clude multisource data fusion and distribution of
able shipboard information system support will      command, surveillance, and intelligence data and
seldom fully satisfy the requirements of the em-    imagery to support warfare mission assessment,
barked Marine force and, consequently, will re-     planning, and execution. JMCIS-Afloat is DII
quire augmentation by organic MAGTF                 COE compliant and shares the JMCIS Unified
informations systems support resources.             Build software with TCO. This commonality per-
                                                    mits the MAGTF to operate TCO in the LFOC
3601. Key Resources                                 and the IAS in the JIC.

Appendix I is an overview of the various CIS re-    JMCIS-Afloat includes the NIPS database inter-
sources available on amphibious ships. However,     face and the national, regional, and organic sensor
the actual CIS support available on amphibious      intelligence and environmental databases. The
ships varies, even between ships of the same        JDISS and other services described in the GCCS
class, based on system installation and upgrade     section are also included in JMCIS-Afloat. Em-
schedules. Specific configurations, including       barked MAGTF commanders can access and use
identification of software release versions, must   the JMCIS-Afloat services by using MAGTF and/
be determined during pre-deployment and embar-      or shipboard computers (with prior coordination)
kation planning. Figure 3-6 (on page 3-22) depicts  on ships’ LANs. Flagships such as CV, CVN,
the information systems and equipment typically     LHA, LHD, and LCC have been upgraded to the
available on amphibious ships, focusing on com-     latest version of JMCIS, while most of the unit-
munications resources and LANs that are key to      level platforms such as CG, DD, DDG, LPD,
shipboard command and control.                      LPH, and LSD ships are using older software ver-
                                                    sions that have incompatibilities with the
3602. JMCIS-Afloat                                  MAGTF C4I Software Baseline. Upgrades are
                                                    continual; until the Navy can achieve a coordinat-
JMCIS-Afloat (formerly known as Navy Tactical       ed simultaneous software update with the Marine
Command System-Afloat [NTCS-A]) provides            Corps, this condition requires that MAGTF CIS
the tactical commander with timely, accurate, and   personnel adapt and find ways to make the net-
                                                    works provide the required services.


---

3-22 _______________________________________________________________________________________________ MCWP 6-22
                                        Figure 3-6. Amphibious Ship Information Systems.


---

                            Chapter 4

Defense Information Systems Network

The goal of DOD communications architects is a        provides the communications backbone for other
single, integrated, common-user, global commu-        DOD-wide systems including the Secure Voice
nications network. This network, the DISN, will       System, DMS, Defense Data Transport Network
provide support for exchange of voice, data, im-      nonsecure internet protocol router network (NIPR-
agery, and video from strategic to tactical levels,   NET) and SIPRNET, video teleconferencing, and
at all echelons, in garrison or when deployed.        JWICS, as well as separate systems and networks
DOD and the Services are implementing DISN in         serving the CINCs, Services, and agencies.
an evolutionary manner by interfacing and inte-
grating existing communications networks and          4001. Tactical Entry Points
maximizing commercial services and standards.
                                                      As a first step in DISN implementation, DISA es-
Just as GCCS and the DII COE are shaping the          tablished the Integrated Tactical-Strategic Data
future of MAGTF C4I systems, DISN implemen-           Network (ITSDN) to provide an IP router-based
tation is shaping the Marine Corps tactical com-      data network to support deployed forces. IP router
munications architecture. For the near term, the      networks are described later in this chapter. Ac-
communications networks supporting the                cess to ITSDN was provided through SIPRNET
MAGTF will include the current MAGTF tactical         and NIPRNET gateways consisting of IP routers
communications networks, the Tri-Services Tacti-      and appropriate encryption devices. ITSDN entry
cal Communications System (TRI-TAC) switched          points were established at the following locations:
backbone, SCR, LANs, and special-purpose net-
works with an interface to DISN for long-haul         q Ft. Belvoir, VA.
communications (see chap. 5). However, change         q Wahiawa, HI.
is occurring rapidly with the introduction of rout-   q Northwest, VA.
er-based data communications systems augment-         q Ft. Buckner, Japan.
ing the switched backbone and providing               q Ft. Meade, MD.
enhanced connectivity among tactical networks         q Riyadh, Saudi Arabia.
and between tactical networks and DISN.               q Ft. Detrick, MD.
                                                      q Landstuhl, Germany.
DISN is the information-transfer segment of the       q Camp Roberts, CA.
DII. The objective of DISN is the creation of a sin-  q Croughton, United Kingdom.
gle, integrated telecommunications infrastructure
that can provide end-to-end communications con-       These ten sites have been upgraded. The four sites
nectivity in support of military operations world-    listed below have been established to provide 14
wide. DISN is evolving toward that objective          DISA standard tactical entry points (STEPs).
through continuous upgrades to switching and
transmission centers around the world and through     q Ft. Bragg, NC.
consolidation and integration of satellite and ter-   q Bahrain.
restrial communications networks. DISN currently      q MacDill AFB, FL.
provides long-haul, common-user, dedicated, se-       q Lago Patria, Italy.
cure and nonsecure, voice, data, and video service
through a mix of both DOD-dedicated and stand-
ard commercial communications services. DISN


---

4-2 ________________________________________________________________________________________________ MCWP 6-22

Upgrades include installation of the Defense Sat-   trunks allow tactical users to place secure red
ellite Communications System (DSCS), the inte-      switch calls from the field.
grated digital network exchange (IDNX), and an
interface to the Navy Tactical Network. The         c. NIPRNET
STEP sites are also called Defense Communica-
tions System entry points, GMF gateways, or         NIPRNET is an information network that is based
DISN gateways. MAGTFs and forward-deployed          on IP routers and IDNX smart multiplexers. NI-
forces use these STEP sites to access DISN to       PRNET is designed for sensitive but unclassified
conduct training, exercises, and operations. When   information transfer. It supports unclassified net-
ashore, the MAGTF’s primary means to access         works such as the Marine Corps Data Network
the STEP sites is through GMF tactical satellite    and the Tactical Automated Weather Distribution
(TACSAT) communications over the DSCS.              System. Under the ITSDN program, 10 of the 14
Shipboard access is provided through the Navy       STEP sites were configured with NIPRNET rout-
Tactical Network. Five entry points with Navy-      ers. MAGTFs use the NIPRNET both aboard ship
unique configurations are located at naval com-     and ashore to transfer administrative data.
puter and telecommunications area master
stations (NCTAMS) to provide both ship-to-shore     d. SIPRNET
and ship-to-ship communications. Figure 4-1 de-
picts a JTF notional architecture with a STEP site  SIPRNET is an information network based on IP
and NCTAMS providing the DISN entry.                routers and IDNX smart multiplexers and de-
                                                    signed for exchanging classified information up
4002. DISN STEP Services                            to and including the secret level. It supports ex-
                                                    changing classified data among GCCS, DMS,
The services provided to the deployed MAGTF         CTAPS, TCO, IAS, and other tactical information
through the DISN STEP include voice, data, and      systems. SIPRNET routers are collocated with
video. Voice services consist of the Defense        NIPRNET routers at 10 STEP sites. MAGTFs use
Switched Network (DSN) and, for secure voice,       the SIPRNET both aboard ship and ashore to
the Defense Red Switch Network. Data and video      transfer operational data.
services are provided through NIPRNET, SIPR-
NET, JWICS, and video teleconferencing.             e. JWICS

a. DSN                                              JWICS is an information network based on both
                                                    IDNX smart multiplexers and IP routers. It is de-
STEP provides one T1 (1.544 Mbps) circuit           signed for exchange of SCI-level video and data
transcoded to support 48 interswitch trunks to a    information. It supports the MAGTF’s use of IN-
DSN multifunction switch. These 32 kbps inter-      TELINK and other services such as those access-
switch trunks allow tactical users to place either  ed by using JDISS and TCAC. MAGTFs access
nonsecure or secure telephone unit-type III (STU-   JWICS while aboard ship and in operations
III) calls to a DSN subscriber.                     ashore.

b. Defense Red Switch Network                       f. Video Teleconferencing

A single STEP accommodates up to four 56 kbps       Higher echelons use video teleconferencing with
circuits to the Defense Red Switch Network          increasing frequency. Within the operating forc-
switch. Each circuit provides two interswitch       es, it is used primarily for MAGTF-to-JTF/CINC
trunks between the tactical and Defense Red         coordination. Currently, video teleconferencing
Switch Network switches. These eight interswitch    supports only point-to-point conferencing. In the
                                                    future, multipoint conferencing will also be sup-
                                                    ported.


---

Communications and Information Systems _______________________________________________________________ 4-3

Figure 4-1. JTF Notional Architecture.

4003. STEP Access                                    must be contacted. A previously issued mission
                                                     directive (described below) references the DISA
The STEP access process is different for the         monitoring center supporting an operation or ex-
MAGTAF GMF/TRI-TAC terminals than it is for          ercise. The DISA analyst ensures that all routers
Navy shipboard terminals. The STEP access            are configured properly to support the operation/
equipment at the entry points is assigned to either  exercise. DISA has the capability to modify rout-
GMF/TRI-TAC or Navy. The GMF/TRI-TAC ac-             ing tables and configurations as required:
cess equipment is managed by DISA, and the Na-
vy-unique access equipment is managed by the         q Columbus, OH (NIPRNET Regional Control
Navy. DISA manages the satellite power and              Center).
bandwidth for DSCS. DISA also assigns MAGTF
(i.e., GMF/TRI-TAC) users particular STEP sites      q Washington, DC (SIPRNET Regional Control
according to priority and equipment/service capa-       Center).
bilities.
                                                     q Oahu, HI (Pacific).
The various DISA monitoring centers that control     q Vaihingen, Germany (Europe).
NIPRNET and SIPRNET router configurations
and programming are listed below. When a circuit     Procedures for GMF/TRI-TAC access to an entry
is activated and a router-to-router connection is    point and satellite are described in the CJCSM
made or attempted, the DISA monitoring center        6231 series. Theater-specific access procedures
                                                     are described in DISA contingency exercise plans.


---

4-4 ________________________________________________________________________________________________ MCWP 6-22

Theater access procedures for the western hemi-         network structure. For additional information, see
sphere (including the continental United States         CJCSM 6231.07A.
[CONUS]) are governed by Contingency Exer-
cise Plan 10-95, for the European theater by Con-       4005. USMC Network Operations
tingency Exercise Plan 1-96, and for the Pacific        Center
theater by Contingency Exercise Plan 203-92. Ac-
cess is initiated with the MAGTF G-6/S-6 request        Assistance from outside the MAGTF is available
to the theater DISA Contingency Operations              from the USMC Network Operations Center. The
Branch and a satellite access request to the Re-        USMC Network Operations Center provides tech-
gional Space Support Center, either directly or         nical support for MAGTF and supporting estab-
through the JTF J-6. The request specifies the ser-     lishment WAN managers and acts as the primary
vices required. DISA responds with an SHF/GMF           point of contact for all Marine Corps operational
mission directive and a satellite access authoriza-     issues in the area of communications networking.
tion. The mission directive is a message that iden-     The USMC Network Operations Center acts as
tifies entry points and points of contact to establish  the Marine Corps Service-level representative to
the access. The priority and purpose of the request,    DISA, other DOD agencies, and commercial ven-
based on the MAGTF mission, should determine            dors concerning network operational issues and
the speed at which entry point access is granted.       products.

The mission directive also provides IP addressing,      The USMC Network Operations Center operates
router information, port and channel assignment,        24 hours a day, 7 days a week supporting the
and coordination points of contact for each data        Marine Corps communications infrastructure as a
network. For additional information on ITSDN,           whole. It performs the following tasks:
see the IP Addressing Plan and the CJCSM 6231
series documents. The communication battalion’s         q Reports/resolves problems.
data network officer and system planning and en-        q Distributes networking software.
gineering officer maintain copies of these and          q Provides network infrastructure components in-
other DISA documents.
                                                           ventory.
4004. Changes to DISN STEP                              q Serves as the Marine Corps network registra-
Sites
                                                           tion authority as assigned by the DISA network
Change is continuous in the DISN evolution.                information center.
DISN sites and the tactical users must remain           q Provides centralized management and funding
adaptable to obtain the more robust and flexible           of Marine Corps telecommunications services
services provided by the upgraded IDNX back-               that traverse DISN, NIPRNET, SIPRNET,
bone. The joint communications support element             LAN-WAN exchange, and IBM Systems Net-
(JCSE) that provides CINC/JTF support commit-              work Architecture networks.
ted funding for IDNX upgrades to meet the goal          q Serves as Service representative to DISA.
communications architecture. IDNX provides link         q Coordinates Marine Corps and other Service/
bandwidth management that allocates circuits as            agency telecommunications requirements.
needed. It allows for a virtual network with auto-      q Provides technical assistance teams to request-
matic routing and rerouting. It also sets the stage        ing units.
for an evolutionary transition to the use of asyn-      q Maintains 16 permanently assigned NIPRNET
chronous transfer mode (ATM). As these changes             and 16 permanently assigned SIPRNET Class C
take place, MAGTFs will require similar equip-             addresses for deployed MEU(SOC)s.
ment to take advantage of the more robust global


---

                                Chapter 5

MAGTF Tactical Communications Network

The MAGTF tactical communications network              work interfaces to DISN. The MAGTF tactical
supports information exchange requirements—            communications network must also interface with
voice, data, video, and imagery—both internal and      the tactical communications networks of the other
external to the MAGTF. For external long-haul          Services.
communications, the tactical communications net-

 Section I

Overview

This overview is designed to give all Marines
who use tactical communications an understand-
ing of the capabilities and limitations of these net-
works. This understanding, in turn, will assist in
the effective employment of these networks to
conduct operations and accomplish assigned mis-
sions.

5101. Architecture                                                      Figure 5-1. MAGTF Tactical
                                                                        Communications Network.
The tactical communications network is com-
posed of numerous subnetworks that interface           5102. Challenges
with one another in varying degrees. These sub-
networks themselves are usually referred to as         The rapid pace of change provides the CIS com-
networks. Figure 5-1 depicts the four types of         munity with both challenges and opportunities.
subnetworks—SCR, local area networks, SBB,             Perhaps the most critical challenge is to provide
and special purpose systems. Each is described in      maneuver battalions with adequate data commu-
sections II–V.                                         nications capability. The ability to provide the

The Marine Corps tactical communications archi-
tecture is rapidly evolving to meet the information
transfer requirements of the MAGTF and to take
advantage of new technology. Changes in the ar-
chitecture are also driven by the requirement to
interface with DISN and to be interoperable with
the other Services.


---

5-2 ________________________________________________________________________________________________ MCWP 6-22

shared situational awareness so critical to the suc-  ing forces. In the early stages of an operation,
cessful execution of any operation depends on         SCR usually provides the principal means of
meeting this challenge and others. The fundamen-      communications. As the operation evolves, LANs
tal requirement remains unchanged—to provide          and SBB networks are established to meet the in-
the MAGTF with a reliable, secure, fast, and flex-    formation transfer requirements of command and
ible communications network.                          control at higher echelons. Maneuver battalions
                                                      continue to depend on SCR throughout the opera-
The design of the actual communications archi-        tion with limited radio interface extensions to the
tecture to support a MAGTF is based on the na-        SBB. Special-purpose systems provide dedicated
ture of the operation, the commander’s (JTF,          communications support for certain functions,
ATF, MAGTF) intent, the concept of operations,        such as position location and navigation and air
and the composition and task-organization of the      defense.
MAGTF as well as that of attached and support-


---

Communications and Information Systems _______________________________________________________________ 5-3

                      Section II

           Single Channel Radio

SCR is the principal means of communications          MAGTF SCR equipment is fielded in many con-
support for maneuver units. SCR communications        figurations and includes hand-held, manpack, ve-
equipment is easy to operate, and networks are        hicle-mounted, ground-mounted, and sheltered
easily established, rapidly reconfigured, and, most   radios. These radios operate in simplex and half-
importantly, easily maintained on the move. SCR       duplex modes. The most widely employed tactical
provides secure voice communication and sup-          radios provide integrated COMSEC and jam re-
ports limited data information exchange. SCR in       sistance through frequency hopping. Tactical
the VHF and UHF bands is normally limited to          SCRs operate in the three military radio frequen-
line of sight. In the HF band, SCR can support        cy bands shown in table 5-1. Characteristics of
long-range communications, albeit at the expense      each category are discussed in paragraphs 5201
of mobility. SCR SATCOM provide mobility,             through 5203.
flexibility, and ease of operation with unlimited
range. Limitations of SCR include susceptibility      SCR is used primarily for secure voice communi-
to enemy electronic warfare; cosite, footprint, ter-  cations. However, SCR can also transmit and re-
rain, and atmospheric interference; the require-      ceive data by using terminal devices such as the
ment for close coordination and detailed              Digital Message System (previously called and
planning; a need for common timing, frequency,        more commonly known as the Digital Communi-
and equipment; and limited spectrum availability.     cations Terminal [DCT]) and the TCIM. The
The latter is particularly critical in the case of    DCT and the TCIM are described in this section
SATCOM.                                               because of their critical role in enabling data com-
                                                      munications at the tactical level over SCRs. (See
                                                      app. A.)

                             Table 5-1. Ground SCRs.

Frequency    MAGTF SCR          Operating                        Typical Application
   Band    Equipment Used       Frequency             Radio line of sight and beyond/long range
      HF                                              Radio line of sight and relay/retransmission
     VHF    AN/PRC-104             Range
            AN/GRC-193         2–29.999 MHz           Critical line of sight (ground to air)
     UHF    AN/MRC-138                                Critical line of sight (ground to air)
                              30–88 MHz               SATCOM footprint
            AN/PRC-68
            AN/PRC-77        116–150 MHz
            VRC-12 family    225–400 MHz
            SINCGARS family

            AN/PRC-113
            AN/VRC-83

            AN/PRC-113
            AN/VRC-83
            AN/GRC-171

            AN/PSC-3
            AN/PSC-5


---

5-4 ________________________________________________________________________________________________ MCWP 6-22

5201. HF Radio                                        HF transmission paths must be constantly moni-
                                                      tored to achieve a dependable HF link. HF radio
HF radio equipment is capable of both long- and       data communications capabilities are limited by
short-range secure voice and data communica-          the bandwidth that is imposed by legal constraints
tions. Data communications capability is typically    and the physics of the spectrum. The bandwidth
limited to rates of 2.4 kbps. Data transmission re-   available in the HF spectrum limits the channel
quires modems specifically designed for opera-        bandwidth, which in turn limits data throughput.
tion in this band of the radio spectrum. MAGTF
HF radio equipment includes the AN/PRC-104            5202. VHF Radio
manpack, the vehicle-mounted AN/MRC-138, the
AN/GRC-193, and the AN/TSC-120 with auto-             The primary MAGTF VHF radio is the single
matic link establishment capability.                  channel ground and airborne radio system (SINC-
                                                      GARS). SINCGARS is a family of lightweight
The primary advantage of using HF radio is its ca-    combat radios that serves as the primary means of
pability to provide long-range, OTH communica-        communications for command and control and
tion. Successful data communication over the HF       fire support on the battlefield. SINCGARS is the
range depends on several factors: equipment sit-      standard VHF-frequency modulated (FM) tactical
ing, proper equipment grounding, types of anten-      radio for the Marine Corps, replacing the AN/
nas used, tactical employment of radio                PRC-77 and the AN/VRC-12 family. The system
equipment, path assessment and analysis, and fre-     provides high security against threat EW by using
quency planning and assignment. When commer-          frequency hopping with integrated COMSEC. It
cial data terminal equipment (DTE) is used, users     is capable of voice and data transmission (up to
employing HF radio equipment need to be aware         16 kbps under optimum conditions and over limit-
of radio interference and potential shock hazards     ed distances) over the VHF-FM frequency range
that can easily affect unprotected DTE. Whenever      of 30–87.975 MHz.
possible, HF radio equipment should be remoted
from DTE.                                             There are seven different SINCGARS configura-
                                                      tions available, depending on the requirements of
The primary limiting factors when using HF radi-      the user. These configurations include the man-
os are frequency allocation/management and            pack, typically used in infantry operations, and ve-
bandwidth availability. Frequency allocation/         hicle-mounted variants. The radio provides voice
management is concerned with frequency, time of       communications ranges of up to 8 km for the man-
day, time of year, and location. The ability to re-   pack and 35 km for vehicular configurations. SIN-
flect HF radio waves off the ionosphere to a dis-     CGARS is capable of remote operation by using
tant location is in a constant state of flux because  the analog AN/GRA-39B radio remote control,
of activity in the ionosphere.                        the digital HYX-57 wire-line adapter, or the digi-
                                                      tal C-11561(C)/U remote control unit (RCU).
The sun’s radiation causes disturbances in the
ionosphere, with most changes taking place in         a. Systems Improvement Program
what is known as the F-layer. Sunrise and sunset
can be the most difficult times for HF communi-       The SINCGARS radio has undergone a systems
cations. The F-layer splits into two separate layers  improvement program (SIP). This radio is re-
around sunrise and recombines into one layer          ferred to as the SINCGARS SIP. The primary im-
around sunset. These splits affect transmission       provements relate to the data transmission
distances as the area “skipped over” increases and    capabilities of the system. A forward error correc-
decreases. At times, solar storms can completely      tion appliqué‚ was implemented in the receiver/
eliminate all HF communications.                      transmitter and a new packet data mode was
                                                      created to better support packet networks. An im-
                                                      proved channel access protocol was added which


---

Communications and Information Systems _______________________________________________________________ 5-5

optimizes data throughput performance while             clock), antenna placement (cosite interference is
minimizing impact on voice communications on            more of a concern than in the single-channel oper-
the same SINCGARS channel.                              ating mode), and power setting. SINCGARS radi-
                                                        os configured for different hopsets that dial into
The SINCGARS SIP radio is also available in a           the same numbered net will not be able to com-
downsized version, the result of an advanced sys-       municate. MCRP 6-22A, TALK II-SINCGARS:
tems improvement program (ASIP). This radio is          MSCP for the Single Channel Ground and Air-
referred to as the SINCGARS ASIP. This radio            borne Radio System, provides detailed informa-
will retain all the functionality of the full size SIP  tion on the employment of SINCGARS.
radio in half the size at a total weight of 7.6
pounds (including the battery). The radio is inter-     VHF SCR is the primary communications system
changeable with previous SINCGARS versions,             for combat and combat support units while on the
including the capability to be mounted in older         move. The predominant mode of operation is se-
vehicular adapter assemblies. A new feature of          cure voice. However, use of VHF radio for data
the SINCGARS ASIP provides a retransmission             communication will increase with the fielding of
capability while operating in the packet data           tactical information systems at the battalion level
mode and will also employ a new fast channel ac-        and below.
cess protocol for improved operations in shared
voice/data nets.                                        Small, handheld VHF radios are used at the small-
                                                        unit level in the MAGTF. These radios are often
The AN/ARC-210 multipurpose radio supports              commercial items that lack compatibility with
single-channel air-to-air, air-to-ground, and           SINCGARS and do not have integrated COM-
ground-to-air communications in tactical Navy/          SEC. Their use should be governed accordingly.
Marine Corps fixed- and rotary-wing aircraft. It
has the capability to transmit and receive VHF-         c. Environmental Limitations
FM, VHF-amplitude modulation (AM), and UHF.
It is compatible with SINCGARS in the frequen-          The primary limiting factors when using VHF ra-
cy hopping mode, as well as with HAVE QUICK             dios are range and frequency availability. VHF ra-
and HAVE QUICK II frequency hopping UHF                 dios can provide reliable communication for
radios, and it can accept 25 preset single-channel      ranges of up to 10 miles, depending on the equip-
frequencies. The AN/ARC-210 requires a TSEC/            ment operating constraints and the operating envi-
KY-58 encryption device to encrypt transmissions        ronment. When employing radios that operate in
and decrypt received signals.                           the VHF spectrum, consideration must be given to
                                                        unit location. Most circuits are limited to radio
b. Employment Considerations                            line of sight, known as 4/3 earth curvature. VHF
                                                        radio signals essentially follow the curvature of
Attention to operator maintenance of the radio          the earth to a distance that is approximately 1/3
equipment, antennas, cable assemblies, and              greater than the distance to the horizon. Foliage
equipment grounding, as well as site planning and       interferes with VHF signals and may reduce nor-
selection, is essential to reliable communications.     mal operating ranges to significantly less than 10
Frequency separation, radio antenna separation,         miles.
remote keying when using COMSEC, and power
output are significant employment factors.              5203. UHF Radio

When operating with some Navy ships, SINC-              Military UHF radio equipment operates in the
GARS may be limited to the single-channel               116-150 MHz upper VHF frequency range and the
mode. When SINCGARS is employed in the fre-             225-400 MHz military UHF radio spectrum.
quency hopping mode, the following operating            MAGTF UHF radio sets (AN/PRC-113, AN/
factors need to be taken into account: hopset (fre-     VRC-83, and AN/GRC-171) are capable of data
quency segment allocation), time of day (system


---

5-6 ________________________________________________________________________________________________ MCWP 6-22

communication at 16 kbps under optimal condi-           ue to reduce its size. Ultimately a “laptop” com-
tions. MAGTF ground and airborne UHF radios             munications network initialization capability is
incorporate the HAVE QUICK electronic counter-          envisioned, concurrent with increased functional-
counter measures capability and operate in single-      ity within the radio set itself. (See fig. 5-2.)
channel and frequency hopping modes. The
HAVE QUICK UHF radio is capable of remote               5205. UHF-TACSAT
operation by using the AN/GRA-39B or HYX-57.
                                                        The AN/PSC-5 Enhanced Manpack UHF terminal
The UHF radios are used for forward air control         employs both narrowband (5 kHz) and wideband
ground-to-air communication. Line of sight be-          (25 kHz) channels supporting 2.4 and 16 kbps da-
tween radios is critical for reliable communica-        ta transfer rates, respectively. UHF-TACSAT ra-
tion. Significant range differences are encountered     dios are employed for long-range communication.
between UHF radios employed for ground-to-air           Multiple-access schemes can operate either with
and ground-to-ground communications. Greater            fixed channel assignments to the various users or
range is achieved when employed from ground to          with channels being assigned in varying fashion
air because of the increased line of sight. When        according to demand. The latter is called demand
employed in the frequency hopping mode, the fol-        assigned multiple access (DAMA). With demand
lowing operating factors must be understood for         assignment the user makes a channel request, and,
proper operation: hopset, time of day, antenna          after a brief time lag, a channel is allocated. The
placement, and power setting.                           DAMA scheme of operation is employed on
                                                        UHF-TACSAT to share available channels more
The primary limiting factor when using UHF radi-        efficiently. The radio systems are compatible with
os is range (critical line of sight). Critical line of  the KY-57 (wideband mode only), the KY-99 and
sight can be described as “what you see is what         ANDVT (narrowband mode only), and the KG-
you get.” As long as the radio’s antenna has opti-      84C (wideband or narrowband) COMSEC equip-
cal line of sight to another radio’s antenna, the two   ment. This radio equipment is also capable of
will be able to transmit and receive. For this rea-     remote operations by using the AN/GRA-39B
son, UHF radios are primarily used in air-to-           (narrowband mode) or HYX-57 (wideband
ground communications.                                  mode).

5204. EPLRS                                             a. Employment Considerations

EPLRS shares many characteristics with PLRS,            Because of its limited availability, the MAGTF
but provides a significant increase in data com-        employs TACSAT primarily to support critical,
munications capability over PLRS. Various data          long-range communications requirements (e.g.,
rates supporting a variety of broadcast and point-      communications support for deep reconnaissance
to-point modes are currently available. Thus,           operations or connectivity to the tactical echelon
EPLRS will provide a dedicated data communica-          of a MEU(SOC) when deployed ashore). The AN/
tions capability between regiment and battalion         PSC-5 is the primary DAMA-capable TACSAT
tactical data networks (TDNs) within the ground         radio available to the MAGTF.
combat element, when fielded in FY-00. This net-
work will also be extended to lower echelons            TACSAT limitations include the competition for
throughout the MAGTF. EPLRS can also serve as           available frequency resources and channel time
a source for automated friendly position location       on the satellite. If only narrowband channels are
information (PLI) and navigation information in a       available, channel data rates are limited to 2,400
hybrid community with PLRS, though data                 bps. Channel congestion, noise, and network satu-
throughput is reduced. A NCS-E(D) is currently          ration will affect the information flow on satellite
required to establish an EPLRS communications           channels and will require a significant reduction
network, however, efforts are underway to contin-       in the data transmission rates to sustain data com-
                                                        munication. Transmit power selection can be


---

Communications and Information Systems _______________________________________________________________ 5-7

Figure 5-2. EPLRS COE.

critical. Sometimes increasing the transmit power    tions. This delay can interfere with systems that
can decrease net effectiveness. Larger directional   automatically retransmit if an acknowledgment is
antennas provide increased signal gain, which in-    not received after a very short timeout period.
creases the transmitted signal power. Antennas
for these systems are lightweight and fragile and,   As unit location changes, the “look angle” (angle
therefore, require constant maintenance and in-      above the horizon) to the satellite can affect net
spection for proper operation.                       reliability. The orbit of a satellite allows it to cov-
                                                     er a certain footprint on the earth. Satellites in
b. Environmental Limitations                         equatorial orbit can cover large portions of the
                                                     earth both north and south of the equator, but as
The primary environmental limitations on TAC-        the user moves closer to the earth’s poles, the
SAT radios are signal propagation delay, location    TACSAT terminal may exceed the satellite foot-
on the earth, terrain masking, and weather effects.  print. This will cause intermittent or lost commu-
Timing between DTE can be a critical factor in       nications. Terrain can also have this effect by
SATCOM because the satellite, acting as a relay      interfering with the satellite and TACSAT termi-
between radios, is about 25,000 miles away.          nal line of sight. Thunderstorms, heavy snow-
There is approximately a one-fourth second prop-     storms, and hail also affect satellite transmissions
agation delay between sending and receiving sta-


---

5-8 ________________________________________________________________________________________________ MCWP 6-22

both by damage to antennas and effect on the          a. DCT (AN/PSC-2)
electromagnetic environment.
                                                      The DCT is a rugged, lightweight, microproces-
5206. Commercial International                        sor-controlled, handheld message processor. It
Maritime Satellite                                    provides Marine users at all echelons with point-
                                                      to-point and netted data communications and is
INMARSAT is a commercial L-band UHF sys-              compatible with most MAGTF radio, wire, and
tem originally designed to support merchant ves-      encryption equipment. It supports data transfer up
sels and cruise ships with telephonic                 to 2.4 kbps in the analog frequency shift keying
communications. It is used by the military on a       (FSK) mode and, depending on the transmission
surge basis to satisfy demands that military satel-   media, up to 16 kbps in the digital baseband
lites cannot meet. Significant restrictions on the    mode. The DCT allows the operator to enter and
use of INMARSAT are its cost and lack of securi-      read data in both free text and fixed or variable
ty. It is a pay-as-you-go service that costs $5–$8    message formats (VMFs). VMF is the tactical
per minute. Because of these high usage costs,        message standard adopted by DOD for ground
INMARSAT should be used only when other tac-          forces. All of the Services have agreed to use this
tical communications cannot support the opera-        standard.
tion effectively. The advantage to INMARSAT is
its availability with minimum advance coordina-       DCT communications protocols and modulation
tion, although it could potentially become saturat-   techniques are interoperable with those of the
ed during a major crisis. Planning for use of         TCIM used at MAGTF CPs. DCTs are used by
INMARSAT requires coordination and approval           the Army for both fire support and intelligence
from the MAGTF G-6/S-6 and arrangements for           applications, and a DCT interface is available on-
connection and payment of bills.                      board the LHD-1 class of amphibious ships.

To access the INMARSAT satellite constellation,       Forward air controllers, forward observers, Sting-
the Marine Corps can employ any one of a variety      er teams, and reconnaissance teams are the pri-
of manpack and mobile systems. These terminals        mary users of the DCT. Employment of this
communicate via satellite with a shore station that   device enables one-time entry of the data, incorpo-
provides the connection to the global terrestrial     rating burst transmission for reduced on-air time.
network. INMARSAT radio employment consid-            The DCT supports standard message formats for
erations and environmental limitations are much       accurate, consistent, and machine-readable infor-
the same as those for military TACSAT.                mation exchange. Effective DCT employment re-
                                                      quires training and a commander’s willingness to
5207. Data Communications                             take the time required to set up data communica-
                                                      tions nets rather than relying strictly on voice
Although data communications will never com-          communications. Proper DCT operation results in
pletely replace voice communications on the bat-      a key command and control capability—the abili-
tlefield, for certain functions it is essential.      ty to exchange data at the tactical level.
Examples are functions such as reconnaissance,
where transmit time must be minimized, and fire       b. Data Automated Communications
support, where rapid, accurate fire support request   Terminal
processing is critical. Furthermore, as tactical in-
formation systems such as TCO are fielded to          The DACT is a small, tactical computer and com-
lower echelons, the requirement for data commu-       munications terminal which gives users the capa-
nications will expand dramatically.                   bility to receive, process, and transmit various
                                                      messages, to include text and symbology, used by
                                                      tactical data systems. The DACT will effectively
                                                      replace the DCT when it achieves full operational
                                                      capability in FY 03, but will provide much greater
                                                      functionality below battalion levels. This will


---

Communications and Information Systems _______________________________________________________________ 5-9

include an embedded GPS receiver, the ability to      Three types of TCIMs are available with various
share a common picture of the battlespace, auto-      software versions that support a wide variety of
mated data exchange, and MAGTF C4I network            communications protocols. The three types in-
connectivity. The DACT will be transportable by       clude an internal PC card, an external set of cards
foot mobile Marines and mounted in tactical or ar-    mounted in a small metal box, and a PC card vari-
mored vehicles.                                       ant that requires a compatible PCMCIA card slot
                                                      in the computer. TCIM interfaces to the computer
c. TCIM                                               by using the open systems standard small comput-
                                                      er system interface (SCSI) and the serial RS-232C
TCIM provides interfaces between MAGTF in-            (7-wire) interface. Programmable wire-line, mul-
formation systems and communications systems.         tipurpose, and radio port interfaces are provided
It is used to connect standalone terminals with       on the network side of TCIM.
SCR nets and to pool radio resources at operation
centers for more efficient use of equipment and       Communications protocols supported include
frequencies. TCIM provides operations centers         TACFIRE, combat net radio, battery computer
with the ability to receive and transmit a set of     system, gun direction unit, Marine tactical sys-
standard tactical netted messages processed by        tems (MTS), MIL-STD-188-220A variable mes-
the DCT and other tactical information systems.       sage format (VMF), commercial, Army mobile
As an MCHS communications processor for               subscriber equipment (MSE) tactical packet
MAGTF information systems, TCIM provides the          switch network, and EPLRS X.25 packet switch
data network interface for MAGTF command,             protocols. This network interface device allows
control, communications, computers, and intelli-      data exchange with Marine and other Service ele-
gence information systems at various facilities,      ments using compatible protocols. The DCT can
agencies, centers, and individual locations. It sup-  exchange data with information systems that use
ports data exchange over radio, wire, and TRI-        TCIM.
TAC SBB networks.


---

5-10 _______________________________________________________________________________________________ MCWP 6-22

          Section III

Local Area Networks

MAGTF LANs are data communications net-              connecting multiple facilities in a large HQ com-
works designed to support information exchange,      plex. Fiber-optic backbone LANs are also used
collaboration, and resource sharing in a particular  aboard Navy ships in conjunction with copper-
agency, facility, center, cell, or geographic loca-  based coaxial and twisted-pair LANs within an
tion. Because of the limited distances involved,     operational workspace such as the LFOC.
network signal protocols can be designed to sup-
port high data throughput—up to 100 Mbps, al-        a. Unshielded Twisted-Pair Cable
though 10 Mbps is more common. These LANs
include terminal equipment connected to a trans-     Unshielded twisted-pair cable is increasingly the
mission medium such as wire or fiber-optic cable.    commercial LAN cable of choice. Unshielded
The terminal equipment exchanges data by using       twisted-pair cable is economically priced, widely
a protocol that is compatible with the medium.       available, and relatively easy to install, operate,
MAGTF LANs use both copper wire and fiber-           and maintain, making it particularly attractive for
optic cable of various types configured to meet      MAGTF employment. The MAGTF requires that
the tactical information exchange requirements of    LANs be easily and quickly set up and dismantled
the command. Specific LAN access methods,            to support rapid and frequent displacements on
technologies, protocols, and equipment are em-       the battlefield. Less specialized installation equip-
ployed in a topology that connects the commands’     ment and training are major considerations driv-
information systems and services. This section       ing Marine Corps use of unshielded twisted-pair
addresses the basic types of LAN media, topolo-      cable. Twisted-pair cable comes in several gauges
gies (physical and logical layout or design), and    (more commonly referred to as categories in LAN
access methods in use by the MAGTF.                  terminology), based on the number of twists per
                                                     foot, with categories 3, 4, and 5 being the most
This section describes the LAN environment and       desirable for LAN connectivity. Smaller gauges,
some of its many implementations. MAGTF LAN          used for subscriber telephone line installations,
implementations will change with time because of     should not be used for data transmission. Local
continuous change in the technology and resulting    networking using unshielded twisted-pair cables
commercial products. DOD acquisition directives      requires hubs or concentrators to provide retrans-
require the Services to implement COTS and           mission of signals and assist in maintenance. Un-
GOTS products where they are feasible and cost-      shielded twisted-pair LANs are not reliable in
effective. As these very products compete in the     environments with high electromagnetic interfer-
commercial marketplace, it is incumbent on CIS       ence (EMI). In these environments, wire cables
personnel to remain aware of these changes to be     must be shielded, routed around interference
able to employ the most effective LAN cables, to-    sources, or replaced with fiber-optic cable.
pologies, and access media in coordination with
Marine Corps- and DII-specified standards.           b. Shielded Cable

5301. LAN Media                                      Shielded LAN cable options include shielded
                                                     twisted-pair and coaxial cable. Shielded twisted-
LAN media include copper-based coaxial and           pair cable has many of the advantages of un-
twisted-pair cable used within local facilities,     shielded twisted-pair cable, but costs more in
such as a regimental-level COC and fiber-optic       return for supporting greater segment lengths and
cable used for higher-speed backbone connections     a relatively limited shielding capability. Coaxial
                                                     cable is available in both thick and thin diameters.
                                                     Thick coaxial cable allows greater noise immuni-
                                                     ty and longer cable runs than does thin coaxial


---

Communications and Information Systems _____________________________________________________________ 5-11

cable. Shielded LAN cables are used by MAGTFs         d. Shipboard Media
only when necessary to achieve greater distance
without repeaters and as a lower-cost alternative     In an effort to improve information access and re-
to fiber-optic cable.                                 source sharing, upgrades to shipboard LANs are
                                                      constantly underway. As ships are cycled through
c. Fiber-Optic Cable                                  service life extension, they receive the latest net-
                                                      working technology. However, it may be several
Fiber-optic cable provides high speed over long       years between overhauls, leaving much of the
distances with immunity to electromagnetic inter-     fleet with older, less responsive networking
ference. Greater levels of security are possible      equipment. Many older shipboard LANs were in-
with this cable because it is very difficult to tap.  stalled with thick coaxial cable, while newer ship-
Glass fiber-optic cable is many times more trans-     board LANs use both fiber-optic backbones and
parent than its plastic counterpart, and, therefore,  twisted-pair or thin-wire coaxial cable extensions
it is the primary type used for LAN applications.     from hubs to workstation terminals. Embarked
This cable is available in single- and multimode      MAGTFs do not use the older thick-cable LANs
fiber based on its light conducting or propagation    because they cannot adequately support multiple
characteristics. Single-mode fiber is much thinner    additional users. In these cases, embarked
than multimode fiber and provides higher trans-       MAGTFs are often authorized to install their own
mission throughput at distances much greater than     temporary, unshielded twisted-pair or thin-wire
a few miles.                                          coaxial LANs.

Single-mode fiber uses lasers as an intense light     e. Media Selection
source and is the most expensive to install. Multi-
mode fiber uses dispersed light signals; this re-     The higher cost and increased complexity of in-
duces its transmission throughput and its effective   stallation and maintenance of coaxial cable and fi-
cable length to distances of less than a mile. Mul-   ber-optic LANs is sometimes outweighed by their
timode fiber uses the much more cost-effective        capability to span greater distances without re-
and weaker light source provided by light-emit-       peaters and, in the case of fiber-optic cable, much
ting diodes. Therefore, if a MAGTF fiber-optic        greater throughput capacity. This is particularly
LAN backbone capability made of interconnect-         true in the choice of a backbone media to support
ing, 1-km or less segments is suitable, the cheaper   a larger HQ such as the MEF or an MSC. On the
multimode fiber capability would be acceptable.       other hand, at the cells and centers of the larger
The MAGTF Fiber-Optic Cable System currently          HQ and at tactical echelons, regiment and below,
in the supply inventory can be used for the tactical  media selection will be driven by ease of installa-
data network (TDN) backbone, with appropriate         tion and operation, and data throughput require-
connector modifications.                              ments will not be as great. In most cases, this will
                                                      lead to a choice of unshielded twisted-pair cable.
Fiber-optic cables require two fibers to allow two-
way (full duplex) communications. MAGTF               5302. LAN Topologies
fiber-optic cable is bundled with two fibers in a
single cable, but commercial fiber-optic cable is     LAN topologies are described by both their physi-
also available as single-fiber cable. The glass fi-   cal configuration (bus, star, or ring) and their log-
bers are surrounded by a reflecting wrap, a plastic   ical implementation. The most common physical
coating, a layer of tough material such as Kevlar,    topologies in use by the MAGTF are the bus and
and an outermost jacket for protection. Two disad-    star, with the star becoming more prevalent. Ship-
vantages of fiber-optic cable are its low tolerance   board physical topologies include bus, star, and
for bends in the cable and poorly constructed or      ring. The fiber-optic backbone on most ships is
maintained connectors. Light transmission toler-      arranged as a ring, with star-configured LANs
ances are critical for these cables to operate prop-  connected to the ring. Logical topologies describe
erly.                                                 the way the LAN is viewed by the media access


---

5-12 _______________________________________________________________________________________________ MCWP 6-22

method used. For example, Ethernet uses both the      es. Installation and reconfigurations tend to be
bus and star physical topologies while implement-     simpler with a single cable. Less equipment, wir-
ing a bus-type logical topology.                      ing, and infrastructure are required for the bus
                                                      compared to other topologies; therefore, installa-
a. Bus Topology                                       tion and operating costs are likely to be lower.
                                                      Multiport transceivers, bus attachment devices
The bus physical topology requires the least          that allow multiple terminal drops from one con-
amount of cable and is the simplest of the three.     nection to the bus, transform the bus topology to a
Terminal devices are attached using drop lines to     star. The flexibility of being able to reroute the
points along the cable where a tap is used to pene-   terminal drops without moving the bus is a further
trate the cable, or, alternatively, quick disconnect  advantage of this topology.
hardware is used at planned breaks in the cable.
Signals transmitted on the bus propagate to every     The shared nature of the bus topology is the cause
point on the bus in a broadcast fashion. Any de-      of its disadvantages. Any disconnected or broken
vice connected to the bus can communicate with        cable will disable the entire LAN. Minimum dis-
any and all other devices on the bus over this        tances between connected terminal devices are
broadcast medium. The ends of the bus require         imposed to reduce adjacent terminal signal reflec-
terminating devices with an impedance that            tions and to allow sufficient time for collision de-
matches that of the cable (typically 50 ohms for      tection schemes to operate properly. Bus cables
baseband coaxial cable). Without this matched         are restricted in length through imposed specifica-
termination, reflected signals would interfere with   tions to ensure that signal propagation delay never
intended transmissions. (See fig. 5-3.)               exceeds the time needed to send the shortest al-
                                                      lowable message over the LAN. The thin-wire
The bus topology is usually used with contention-     LAN cable specification 10Base2, for example,
based media access methods such as Ethernet.          indicates with the number “2” that the maximum
This topology is also frequently used as a back-      cable length is 200 meters. Actual cable lengths
bone transmission path for other topologies,          are somewhat less than the approximate numbers
which allows multiple specifications and access       used in the abbreviated specifications.
methods in a more complex network. Buses use
specifications that restrict overall cable length.    b. Star Topology
Length restrictions are necessary to ensure that
timing measurements associated with signal prop-      The star topology is characterized by multiple ter-
agation and collisions on the cable can be used to    minal devices homed or connected to a central
manage the network.                                   hub or server. Unlike the bus, the star topology
                                                      continues to operate for all other connected devic-
The bus topology may be desirable for smaller         es if one of its terminals or a cable to one of its
LANs at tactical echelons where its simplicity and    terminals malfunctions. This topology, although
ease of installation may outweigh its disadvantag-    more complex than the bus, can be more efficient

Figure 5-3. Bus Topology.


---

Communications and Information Systems _____________________________________________________________ 5-13

and is the most widely used LAN topology in           connected terminals. If the hub loses power or has
commercial and MAGTF applications. (See fig.          a failure in its circuitry, the entire LAN may be
5-4.)                                                 shut down. If the failed hub is attached to a back-
                                                      bone bus when it fails, the entire bus could also be
                 Figure 5-4. Star Topology.           disrupted. The additional wiring for terminal con-
                                                      nections and the hubs themselves adds to the cost
Advantages of the star topology include excellent     of this type of topology. Despite the higher cost,
diagnostic, control, and management capabilities.     the added flexibility and convenience of the star
Priority schemes can be employed as a way of          topology make it the topology most often used in
managing the various workstations and other ter-      the MAGTF.
minal devices on the LAN. Because all terminal
devices connect to the hub, all lines are easily      c. Ring Topology
monitored and controlled. Reconfiguration is also
much easier to manage at this centralized loca-       In the ring topology, all terminals are connected
tion. (See fig. 5-5.)                                 to one another to form a circular ring with com-
                                                      munications possible in either direction. Typical-
                                                      ly, one of the terminals acts as the manager or
                                                      monitor in the network. The monitor is responsi-
                                                      ble for generating and passing the token that con-
                                                      trols other terminal users’ access to the ring. Only
                                                      the holder of the token is allowed to transmit on
                                                      the LAN. Once completed, that user sends the to-
                                                      ken to the next user on the ring. The ring is gener-
                                                      ally associated with token-passing access methods
                                                      such as token ring or fiber distributed data inter-
                                                      face (FDDI). (See fig. 5-6.)

      Figure 5-5. Combined Bus/Star Topology.                          Figure 5-6. Ring Topology.

The star topology’s disadvantages center around       The implementation of this topology is most often
its centralized hub, also called a concentrator. The  combined with the star topology using hubs on
hub is a common point of failure for all of the       the ring as multiple access units for terminal con-
                                                      nections. This access method reduces failures and
                                                      interruptions that would occur if terminals were
                                                      connected in a series of point-to-point connec-
                                                      tions to form the ring. (See fig. 5-7 on page 5-14.)

                                                      The hubs are left in place, reducing the chance of
                                                      failure introduced by constant interruption caused


---

5-14 _______________________________________________________________________________________________ MCWP 6-22

by user connections and disconnections. One bad        access methods are specifically developed for 100
connection on any part of the ring, however, can       Mbps fiber-optic and copper LANs. Ethernet, a
bring the entire LAN down. The hubs are part of        specific implementation of the 802.3 access meth-
the ring, and their failure to maintain the ring con-  od, is the most widely used LAN standard in the
nection can cause the backbone LAN to fail. Dual       world. It is also, not surprisingly, the most widely
rings are used to overcome this single point of        used LAN access method in the MAGTF and
failure. Usually, one ring is the primary ring,        aboard ship. Ethernet is used with multiple media
while the other (secondary ring) is a backup that      types and topologies Ethernet standards are speci-
is used if the primary ring fails. As with the star    fied for twisted-pair, coaxial, and fiber-optic LAN
topology, the ring topology includes excellent di-     media. Table 5-2 shows approximate maximum
agnostic, control, and management capabilities.        data rates, cable types, approximate maximum ca-
This topology is prevalent aboard ship.                ble segment lengths, topologies, and the number
                                                       of segments and nodes per segment for each
5303. Access Methods                                   Ethernet specification.

LAN access methods define the processes, proce-        The FDDI access method specifies a 100 Mbps,
dures, and standards for the various types of me-      token-passing, dual-ring LAN that uses the fiber-
dia and topologies. The Institute of Electrical and    optic transmission medium. It defines the physical
Electronic Engineers (IEEE) 802 series specifies       layer and media-access portion of the link layer.
standards for LAN media access methods. The            FDDI access is similar in many ways to Token
IEEE 802 series includes Carrier Sense Multiple        Ring access. Both use the ring topology, token
Access with Collision Detection (CSMA/CD or            passing, and redundant features such as dual
802.3), token bus (802.4), and token ring (802.5)      rings.
access methods. These access methods, originally
used with copper wire at data rates of 1 - 16 Mbps     FDDI is defined by specifications for media ac-
are now also used with fiber-optic cable and can       cess control, physical layer protocols and medi-
be used at 100-Mbps data rates. The FDDI and           um, and station management. FDDI, however,
corresponding copper distributed data interface        uses the same upper sublayer of the datalink layer
                                                       that Ethernet uses, making it compatible with

Figure 5-7. Combined Ring/Star Topology.


---

Communications and Information Systems _____________________________________________________________ 5-15

.

                                         Table 5-2. Ethernet Standards and Specifications.

Specification  Maximum      Cable Type                Maximum    Bus Type                       Number of
    Name 1     Data Rate                              Length of  Topology                   Segments/Nodes
                                                      One Cable
                                                       Segment                                 per Segment
                                                       (meters)

10BaseT        10 Mbps      Twisted-pair              100        Star                       Depends on hub ports
                            Category: 3, 4, 5

10Base2        10 Mbps      Coaxial (thin)            200.00     Linear 2                   3/30

10Base5        10 Mbps      Coaxial (thick)           500        Linear 2                   5/250

10BaseFL       10 Mbps      Fiber-optic               4000.00    Star

100BaseFX/TX   10 Mbps 100  Twisted-pair              150        Star                       Depends on hub ports
               Mbps         (Category 5)

1Specifications are all baseband, with the first number indicating the maximum data rate in Mbps and the last letter/number indicat-
ing the cable type or the unrepeated cable length.
2 Impedance matching terminations at ends of cables required.

Ethernet at its higher throughput. Media access       FDDI employs two traffic types, synchronous and
control defines the medium access method, which       asynchronous, to provide real-time allocation of
includes frame format, token handling, address-       network bandwidth. A portion of the total 100
ing, the algorithm for calculating a cyclic redun-    Mbps bandwidth can be allocated solely for syn-
dancy check value for error detection, and error      chronous traffic, while asynchronous traffic uses
recovery mechanisms. The physical layer proto-        the remainder. Stations with the need for continu-
col defines data coding procedures, clocking,         ous transmission capability, such as simultaneous
framing, and other requirements. The physical         voice, data, and video information applications,
layer medium defines the transmission medium,         use synchronous traffic. The remaining band-
which includes the fiber-optic link, power levels,    width is used by asynchronous traffic users who
bit-error rates, optical components, and connec-      have much lower throughput requirements. Sta-
tors. Station management involves the FDDI sta-       tion management functions of FDDI include a
tion and ring configurations and ring control         distributed bidding scheme to allocate FDDI
features such as station insertion and removal, ini-  bandwidth based on an eight-level priority
tialization, fault isolation and recovery, schedul-   scheme. These capabilities for flexible bandwidth
ing, and statistics collection.                       allocation are useful in the larger MEF HQ to en-
                                                      sure effective use of limited bandwidth.


---

5-16 _______________________________________________________________________________________________ MCWP 6-22

        Section IV

Switched Backbone

The MAGTF switched backbone (SBB) compris-           communications. Wideband MCRs, both satellite
es the switching, routing, and wideband transmis-    and terrestrial, provide the internodal communica-
sion systems that provide the high-capacity          tions for the MAGTF communications network
communications backbone for the MAGTF tacti-         and the connectivity to the DISN entry points.
cal communications network as well as connec-        (See app. E.)
tivity with the DISN. It is the tactical equivalent
of commercial local and long-distance networks       5401. Tri-Services Tactical
and, in some situations, interfaces with and uses    System
those commercial networks. The SBB uses an
evolution of older and newer equipment and tech-     The TRI-TAC family of equipment, developed in
nology. The evolution drives changes in systems      the 1970s under a joint program of the Marine
and organizations, revisions in procedures, and      Corps, Air Force, and Army and fielded in the
requirements for additional training.                mid-1980s, provides the major components of the
                                                     MAGTF SBB. This equipment was developed to
The SBB, like the MAGTF itself, is tailored and      provide interoperable, secure, and deployable
has the flexibility to adapt to support the unfold-  voice and data digital switching and transmission
ing tactical situation and overall scheme of ma-     systems for tactical forces operating in a joint en-
neuver. The SBB is planned, designed, installed,     vironment. The design took into consideration the
operated, and maintained by CIS personnel under      realities of tactical communications in remote lo-
the cognizance of the G-6/S-6 and leadership of      cations. Tactical transmission links are con-
communications unit commanders. Planning, re-        strained by high bit-error rates and limited
design, and adaptation are continuous as SBB         bandwidth, and TRI-TAC systems are designed to
equipment and personnel arrive in theater and the    operate in this environment.
MAGTF transitions to operations ashore. Larger
HQ, rear areas, expeditionary airfields, and C2 fa-  TRI-TAC systems provide a high degree of secu-
cilities are the principal subscribers to the SBB.   rity but are complicated, expensive, difficult to
Maneuver battalions cannot afford the restrictions   operate, and use a very different set of communi-
on mobility imposed by the SBB and normally          cations standards than the commercial networks
link to it through an SCR interface.                 and the DSN. For voice digitization, TRI-TAC
                                                     systems employ continuously variable slope delta
The switches, IP routers, and wideband MCR sys-      (CVSD) modulation to conserve transmission
tems that form the MAGTF SBB are described in        bandwidth, while the DSN and commercial net-
this chapter. Computers play a key role in the op-   works use pulse-code modulation and adaptive
eration, maintenance, and control of this SBB.       differential pulse-code modulation. These differ-
Computer-controlled communication links and          ences require modulation conversions at interface
switching enable efficient, flexible use of limited  points between the TRI-TAC and DSN or com-
resources. Computerized switches and routers are     mercial networks. Multiple modulation signal
used to route voice, data, and video information at  conversions eventually lead to errors that disrupt
various points or nodes in the network. They in-     circuits.
clude devices such as circuit switches to route
telephone calls and data, message switches to        TRI-TAC systems use conditioned diphase sig-
route organizational message traffic, packet         naling, which allows longer wire-line transmis-
switches for efficient data transmission, and rout-  sion without repeaters than commercial baseband
ers to interface with IP router networks for data


---

Communications and Information Systems _____________________________________________________________ 5-17

signaling techniques and permits timing to be em-     Army and Air Force MOUs used to obtain GMF
bedded in every circuit. This type of signal also     SATCOM augmentation. TRI-TAC switches use
provides a much more efficient use of bandwidth       deterministic routing like the DSN and commer-
than commercial baseband signaling. Again, how-       cial networks, while the Army’s AN/TTC-39D
ever, the different signaling techniques drive a re-  and MSE switches use an incompatible flood-
quirement for conversion to interface with DSN        search routing scheme.
and commercial networks.
                                                      5402. Switches
The TRI-TAC family of TACSAT and terrestrial
microwave MCR communications and switching            Switches provide the means to route traffic
systems equipment is currently in use by three        through a network of transmission media support-
Services and the joint community—the Army at          ing many commands, units, and individual
echelons above corps level, the Marine Corps at       Marines. Switching may be manual (operator as-
regiment/group and higher echelons, the Air           sisted) or automatic, and it may connect local sub-
Force when deployed, and the JCSE to support          scribers, such as those in a MEF main COC, or
JTFs. The employment of TRI-TAC systems be-           perform WAN functions, such as sending traffic
gan before Desert Shield/Desert Storm and pro-        over satellite links. There are basically three types
vided, with some growing pains, an                    of switches: circuit, message, and packet.
unprecedented degree of communications interop-
erability between the Army, Marine Corps, and         Circuit switches generally support telephone traf-
Air Force.                                            fic; message switches process formatted messages
                                                      for storage and delivery; and packet switches pro-
GMF tactical SATCOM systems include DSCS              cess data into packets for transmission over multi-
satellites that provide the required relay and com-   ple links and then reassemble the packets at the
patible ground terminal systems. Terminal sys-        other end. Although the Marine Corps developed
tems include the AN/TSC-85 and AN/TSC-93,             a packet switch under the TRI-TAC program, it
which are fielded in the MAGTF in limited num-        was never fielded, and the Marine Corps achieves
bers. The Army also uses these terminals, while       a packet switching capability through the use of
the Air Force uses interoperable versions—the         IP routers as discussed below. The Army, in con-
AN/TSC-100 and AN/TSC-94 terminals. Marine            trast, employs an X.25 packet switching protocol
component and MEF HQ are routinely augmented          in conjunction with their MSE equipment to es-
with Air Force and Army GMF SATCOM termi-             tablish a tactical packet network. Exchanging data
nals for training and contingencies under memo-       between the MAGTF SBB and the Army tactical
randums of understanding (MOUs) with the              packet network will be a requirement in most
Army and Air Force.                                   joint operations and will be discussed later.

There are five different TRI-TAC circuit switches     a. Circuit Switches
and two versions of the TRI-TAC message
switch. Each switch has its own software that         Circuit switches provide an electrical circuit on
must be frequently tested and certified to ensure     demand between calling and called parties. The
that it will interoperate with the other switches in  circuit is reserved for exclusive use of the parties
the network. The Marine Corps and the Air Force       until the connection is terminated. The tactical
employ the TRI-TAC-developed AN/TTC-42 and            telephone system operates by means of circuit
SB-3865 unit-level circuit switches (ULCSs). The      switching. Circuit switches are used to switch
large, high-capacity AN/TTC-39 circuit switch         voice, data, and multimedia traffic. Traffic may
and AN/TYC-39 message switch are also TRI-            originate from either data capable terminal devic-
TAC switches but are not part of the Marine           es, secure telephones, nonsecure telephones, or IP
Corps inventory. However, these two switches are      routers used to route LAN traffic within the
available, with support personnel, under the same     MAGTF and over WANs.


---

5-18 _______________________________________________________________________________________________ MCWP 6-22

(1) AN/TTC-42 and SB-3865. The MAGTF uses             standard digital interfaces between NATO tactical
two ULCSs: the AN/TTC-42 and the SB-3865.             communications systems. The AN/TTC-42 and
AN/TTC-42 switches can provide service to 280         SB-3865 switches do not implement NATO inter-
combined digital/analog loops/trunks. An SB-          faces and rely on AN/TTC-39 family switches to
3865 switch can provide service to 64 combined        provide NATO access if it is required.
digital/analog loops/trunks in a single configura-
tion, and two or three SB-3865s may be stacked to     (6) Security. The TRI-TAC system employs
serve 90 combined digital/analog loops/trunks at a    digital subscriber voice terminals (DSVTs) to
single site. Because routing of calls is determinis-  provide end-to-end encryption for classified con-
tic, a tactical telephone directory must be main-     versations and uses link encryption of interswitch
tained.                                               digital transmission groups to conceal the number
                                                      of calls made over the link and the telephone
(2) Digital Transmission Groups. D T G s a r e        numbers called (i.e., traffic flow security). Al-
used to interconnect switches and are usually en-     though not designed as part of the TRI-TAC sys-
crypted to provide traffic flow security. DTGs        tem, STU-III terminals are used to provide secure
may be transported by using GMF SATCOM, line          access to subscribers in the DSN. DSVT, digital
of sight microwave radio, tropospheric-scatter        nonsecure voice terminal (DNVT), and analog
(troposcatter) microwave radio, coaxial cable, and    telephones cannot be used to place secure calls in-
fiber-optic cable.                                    to the DSN because they are cryptographically in-
                                                      compatible with the STU-III terminals. DSVT,
(3) Interface to the DSN. TRI-TAC switches in-        DNVT, and analog telephones can place nonse-
terface to the DSN through STEPs. STEPs are           cure calls to STU-III terminals connected to the
configured to provide the interface between the       DSN or commercial networks. A STU-III multi-
tactical and DSN systems. Because a direct digital    media terminal can be used for interfaces with
CVSD-to-pulse-code modulation conversion has          DNVT devices for interface to the TRI-TAC
not yet been implemented in the STEPs, the inter-     communications network.
face between the tactical communications system
and the DSN consists of converting tactical           (7) Access. Telephones (DSVT, DNVT, and
CVSD-modulated circuits to analog form, inter-        multimedia terminal), TCIMs, radio-wire integra-
facing the analog signal with the DSN, then digi-     tion devices, remote multiplexer combiners
tizing the signal into 64 kbps pulse-code             (RMCs), and electrical/optical converters are used
modulation or 32 kbps adaptive differential pulse-    to gain access to circuit switches (see table 5-3).
code modulation format for further transmission       Telephone lines may be multiplexed/combined by
within the DSN.                                       RMC devices before entering the circuit switch.
                                                      Many of the tactical telephones are both data and
(4) Interface to MSE. TRI-TAC switches inter-         voice capable. The TCIM provides a computer-to-
face to MSE switches via designated area codes        radio or computer-to-circuit switch interface ca-
known as “area code gateways.” These area codes       pability. Radio-wire integration devices provide
are used within MSE as the means of interfacing       manual, remote access to the SBB from SCR sys-
between the MSE flood-search network and exter-       tems. RMCs extend the service area of a local cir-
nal deterministic networks such as DSN and TRI-       cuit switch by providing wire-line access to a
TAC.                                                  limited number of subscribers who do not possess
                                                      or have direct access to a switch. Electrical/opti-
(5) North Atlantic Treaty Organization and            cal converters allow for connection of fiber-optic
                                                      cable between switches and other parts of the
Commercial Interfaces. TRI-TAC AN/TTC-39              communications network
family switches contain hardware and software
features that allow them to interface with NATO       (8) Analog Equipment. Some older analog cir-
members’ switches in accordance with Standard-        cuit switches and telephones remain in the inven-
ization Agreement (STANAG) 5040. STANAGs              tory. These devices can interface to the SBB, but
4206 through 4213 provide specifications for


---

Communications and Information Systems _____________________________________________________________ 5-19

not in a secure digital mode. Consequently, their    SCI. As mentioned earlier, the AN/TYC-39 mes-
primary utility lies in providing local telephone    sage switch is available from the Army to aug-
service within a single CP or HQ. These analog       ment the message switching capability of the
devices are described in TM-2000-15/2B, Princi-      MEF.
pal Technical Characteristics of U.S. Marine
Corps Communication-Electronic Equipment.            c. Packet Switches

Table 5-3. MAGTF Telephones.                         Transmission of complete messages is an ineffi-
                                                     cient use of data communications networks. Pack-
Analog         TA-312                                et switches break messages into data packets that
Digital        TA-838                                are individually addressed and entered into the
1Data capable  TA-938                                network. The packets are forwarded to the ad-
               STU-III1                              dressee over a number of different links or circuit
                                                     paths between packet switches based on circuit
               TA-954 DNVT                           availability. At the receiving end of the circuit,
               TA-1042 DNVT1                         the packets are reassembled into the original mes-
               TSEC/KY-68/78 DSVT1                   sage, which is then passed to the receiving termi-
               Multimedia terminal (STU-III)1        nal. The MAGTF does not use packet switches.
                                                     However, the MAGTF circuit switches may have
More information on circuit switching can be ob-     to interface with the Army’s MSE. MSE employs
tained from TRI-TAC manuals and in CJCSM             a tactical packet network overlay to accomplish
6231.02, Joint Voice Communications Systems          packet switching over its circuit switches. MSE
and CJCSM 6231.03A. The older tactical tele-         supports division units in the Army. Special inter-
phones are described in TM 2000-15/2B.               face equipment and protocols are required to ac-
                                                     complish this interface.
b. Message Switches
                                                     d. Switch Network
Message switches ensure delivery of complete
messages to a distant location or multiple loca-     MAGTF switches are used primarily at the regi-
tions when circuits to that location become avail-   ment level and higher echelons at the main and
able. If all circuits are busy, the originating      rear area operations centers. MAGTF switches
message center or intermediate message switches      and associated subscriber devices are listed in ta-
store the message and automatically transmit it to   ble 5-4 on page 5-20.
the proper addressee as soon as a circuit is free.
This form of switching is referred to as “store and  Switches are now available in increasingly small
forward.”                                            packages such as circuit cards. This enables the
                                                     use of these switches within or as embedded com-
Message switches are primarily used by the           ponents of other systems such as digital TECH-
MAGTF at the MEF CE and MSC levels. The              CON equipment and TDN servers and gateways.
AN/MSC-63A is used to support both general ser-      Routers, described next, are also migrating to en-
vice (GENSER) and SCI message switching. The         closures such as those described above and per-
designations for these two message switch uses       form similar functions to those of switches.
are the Tactical Communications Center (TCC)         Figure 5-8 (on page 5-20) shows circuit switch
for the GENSER message switch and the Special        connectivity for a MEF in a JTF. CJCSM 6231.02
Security Communications Central (SSCC) for           and CJCSM 6231.03A provide more detailed in-
                                                     formation about tactical circuit and message
                                                     switch descriptions and use.

                                                     .


---

5-20 _______________________________________________________________________________________________ MCWP 6-22

               Table 5-4. MAGTF Switches.

       Switch  Location Used                  Interface       Terminal       Type
AN-TTC-42                                     Devices          Devices  Circuit
SB-3865
               MEF/MSC                        TCIM        STU-III
AN/MSC-63A                                    IP routers
AN/TYC-39      MEF/MSC                                    DNVT
               Regiment/group                             DSVT
               Artillery regiment/ battalion

               MEF/ACE/division                           Message servers Message
               MEF/MARFOR

               Figure 5-8. Circuit Switch Network.


---

Communications and Information Systems _____________________________________________________________ 5-21

5403. Global Block Numbering                         q Recommend any policy requirements that facil-
Plan                                                    itate the management and assignment of PALs
                                                        To HQMC (C4I) on an as needed basis.
Effective 1 June 1995 the Global Block Number-
ing Plan (GBNP) was implemented by all tactical      q Coordinate with COMMARLOGBASES on
circuit switches and switchboards in the Depart-        equipment related issues.
ment of Defense. The GBNP does not violate the
deterministic use of 3/4 or 4/3 numbering plans.     q Coordinate with MCCDC to ensure that USMC
The plan was designed to be compatible with             PAL assignments are incorporated into the ap-
numbering plans previously used for joint opera-        propriate doctrinal publications.
tions and the Military Services. Incorporation of
the plan should be done during the normal cycle      5404. IP Routers
when contingency, exercise, and operations plans
are updated.                                         The modern battlefield demands that the SBB
                                                     provide efficient support for data communica-
The basis for the GBNP is fourfold: (1) to incor-    tions. Although circuit switches and message
porate all Services into a joint network, (2) to     switches can support data communications, pack-
identify a unique, Service-managed block of unit     et switching is far more efficient. The Marine
and subscriber numbers, (3) to simplify network      Corps initially planned to establish a packet
management (DISN/Commercial) routing into a          switching network using a packet switch devel-
global network, and (4) to identify data bases and   oped under the TRI-TAC program. However, the
subnetworks within the block of numbers. The         Army chose to implement an X.25-based packet
GBNP must be implemented with the circuit            switching network as an overlay on its MSE
switch routing - task execution plan (CSR-TEP)       network. This Army decision and other factors led
to preclude NNXX contention between flood            the Marine Corps to abandon the TRI-TAC
search and deterministic subscribers and to allow    packet switch, known as the unit-level message
deterministic switches to route into the flood       switch. Instead, the Marine Corps has developed a
search network.                                      packet switching capability through the use of
                                                     commercial IP routers. This placed the Marine
HQMC (C4I) is the policy and oversight authority     Corps in an excellent position in terms of connec-
for the USMC’s GBNP and Preafilliation List          tivity to DISN because DISA has transitioned the
(PAL) management. PAL management will be             strategic DISN Defense Data Network (DDN)
centralized at the USMC and major command lev-       from a network based on X.25 packet switching to
el (COMMARFORPAC, COMMARFORLANT,                     one based on IP routers.
and COMMARFORRES). As of June 1998,
MARCORSYSCOM is designated the USMC                  The Marine Corps uses commercially available IP
PAL Manager; MCTSSA will be the action orga-         routers to automatically route traffic to and from
nization. The USMC PAL Manager will—                 local or remote subscriber LANs, over the SBB,
                                                     and to and from the DISN. These IP routers form
q Coordinate, distribute and maintain the USMC       a data communications overlay on the SBB and
   PAL assignments as delineated by the Global       serve as gateways to the IP router networks of the
   PAL Manager (U.S. Army).                          other Services, the JTF, and DISN. MAGTF com-
                                                     puters are configured to operate by using their
q Serve as the Marine Corps’ primary Point of        unique IP address(es). These computers imple-
   Contact for the Global PAL Manager (U.S.          ment the TCP to handle end-to-end delivery of
   Army).                                            messages on IP router networks.

q Coordinate and assist the major commands in        IP routers route data packets containing data in
   establishing PAL and PAL sublists and main-       multiple formats throughout the DISN IP router
   tain this information in a centralized database.  networks: JWICS, SIPRNET and NIPRNET.


---

5-22 _______________________________________________________________________________________________ MCWP 6-22

Inline network encryptors and COMSEC encryp-        q NIPRNET, SIPRNET, and JWICS WAN ac-
tion equipment are used to provide packet-level        cess for one MSC.
and transmission security of the IP router net-
works. IP routers provide the gateways between      q NIPRNET, SIPRNET, and JWICS LAN access
the LAN and the SBB. IP routers use exterior pro-      for 35–50 end users.
tocols along with interior protocols to handle IP-
addressed packets, determine paths to destinations  q TDS network management.
or other routers, and manage the IP packet flow     q IP router network management.
through their nodes. CJCSM 6231.07A, chapter
VIII, provides information about router protocols   b. Notional MEF Data Communica-
and IP addressing used by the DISN.                 tions Package
                                                    A typical router-based data communications
a. Notional Air-Deployable Data                     package to support the MEF CE includes the
Communications Package                              equipment in table 5-6.

A typical air-deployable, router-based data com-    Table 5-6. MEF CE Data Communications Package.
munications package to support the MAGTF CE
includes the equipment in table 5-5.                          Nomenclature          Quantity
                                                    5-ton truck with shelter             1
Table 5-5. Notional Air-Deployable Data             Banyan server suite                  8
        Communications Package.                     Laptop (router)                      2
                                                    Desktop suite (net management)       5
           Nomenclature             Quantity        CISCO 7000 router                    3
Heavy HMMWV with shelter                 2          CSU/DSU modems                       4
Banyan server suite                      4          Asynchronous modems                  2
Laptop (router)                          2          LAN repeater                         8
Desktop suite (net management)           3          UPS                                  11
CISCO 4000 router                        3          KG-84C                               20
LAN repeater                             3          KYK-13/DTD                           2
Uninterruptible power supply (UPS)       7          KOI-18                               2
Channel service unit (CSU)/              4
data service unit (DSU) modems                      This equipment, with appropriate CIS personnel
Asynchronous modems                      2          and transmission equipment, provides the follow-
KG-84C                                   8          ing capabilities:
KYK-13/data transfer device (DTD)        2
KOI-18                                   2          q NIPRNET, SIPRNET, and JWICS WAN ac-
                                                       cess to a gateway/higher HQ.
This equipment, with appropriate CIS personnel
and transmission equipment, provides the follow-    q NIPRNET, SIPRNET, and JWICS WAN ac-
ing capabilities:                                      cess for seven MSCs/adjacent units.

q NIPRNET, SIPRNET, and JWICS WAN ac-               q NIPRNET, SIPRNET, and JWICS LAN access
   cess to a gateway/higher HQ.                        for 50–200 end users.

                                                    q TDS network management.
                                                    q IP router network management.


---

Communications and Information Systems _____________________________________________________________ 5-23

q JTF enabler module.                               and to interface with DISN. TDN will have an ini-
                                                    tial operational capability in FY 00.

c. Contingency Data Network Suites                  The TDN system augments the existing MAGTF
                                                    communications infrastructure. It provides the
MCTSSA has available, on request, contingency       commander with an integrated data network and
data network suites capable of supporting NIPR-     forms the data communications backbone for
NET and SIPRNET WAN access. The contingen-          MAGTF TDSs. It will replace the interim data
cy data network suite is a standard data network    communications package with an expeditionary,
package for MAGTF use until the TDN gateway         highly mobile suite of equipment that uses the lat-
is fielded. Each contingency data network suite     est router technology.
has been designed to support encrypted WAN
connectivity to distant CPs and a LAN of up to 48   The TDN system has two configurations: the
hosts operating at the same classification level.   TDN gateway and the TDN server. The TDN
The contingency data network suite is composed      gateway is deployed at the MEF and MSC levels
of two CE packages and six remote site packages     and provides access to the NIPRNET, the SIPR-
that differ in size and the number of serial data   NET, and other Services’ tactical packet switch
connections available. Table 5-7 lists the contin-  networks. The TDN gateway consists of an air-
gency data network suite equipment. The KIV-7       conditioned/heated, heavy HMMWV-mounted
is compatible with the KG-84A/C, but is capable     shelter equipped with the major components list-
of much higher data rates when interfaced with      ed in table 5-8.
another KIV-7. The UNIX workstation is capable
of supporting a DNS and network management          Table 5-8. TDN Gateway Components.
software. The contingency data network suite can
be requested from MCTSSA via the MEF G-6.

Table 5-7. Contingency Data Network Suite                          Item              Quantity
                      Equipment.                    MCHS processors                       4
                                                                                          2
Item                       Quantity                 Monitors                              1
CE Package (x 2)                                                                          2
CISCO 4500 router               1                   Smart multiplexer IDNX-20
KIV-7 encryption device         4                                                         6
LAN hubs                        2                   Router-multiprotocol                  4
2000VA UPS                      1                   Minimum: 8 serial ports               16
UNIX workstation                1                                                         16
Printer (LaserJet)              1                               2 802.3 ports             6
Remote Site Package (x 6)                                       1 asynchronous port       4
CISCO 2514 router               1                   Repeater (7-port)                     2
KIV-7 encryption device         2                                                         6
                                                    TCIM and TCIM power supply            4
d. TDN
                                                    KIV-7 encryption device               4
Although the TDN had not been fielded as of the                                           2
writing of this publication, the operating forces   Wire-line adapters                    1
are already using COTS hardware and software to
establish tactical data communications networks     UPS

                                                    SNMP adapter

                                                    Fiber-optic modems

                                                    KY-68 DSVT

                                                    MMT with DNVT appliqué

                                                    Patch panels
                                                    EIA 530
                                                    Loop

                                                    In-line network encryptor


---

5-24 _______________________________________________________________________________________________ MCWP 6-22

The TDN server is deployed at the MEF, MSCs,         CJCSM 6231.02 and 6231.03A provide more de-
and units down to the battalion/squadron level.      tailed information about switches, routers, and
The TDN server is transported in three transit cas-  joint communications networks.
es. It includes the equipment shown in figure 5-9.
TDN gateways and servers provide the capability      5405. Multichannel Radios
to share files, perform electronic message han-
dling, and provide transparent routing of messages   MCR provides the communications links for the
through the LAN, circuit switch, MCR, and SCR        SBB. It permits multiple users to access a single
subnetworks.                                         communications path. MCR equipment includes
                                                     terrestrial line of sight, troposcatter, TACSAT,
e. Future Direction                                  and HF radios, all with associated multiplexers,
                                                     modems, cabling, and antennas. MCR provides
For more efficient MAGTF interfaces to the           worldwide connectivity through links to the NI-
DISN, IP routers and smart multiplexers are in-      PRNET, SIPRNET, and JWICS networks of the
creasingly replacing the older and less expedition-  DISN as well as the links for long-distance com-
ary switching system equipment. For example,         munications within the theater and within the
IDNX smart multiplexers are being included at        MAGTF. MCR provides reliable, flexible, and
SIPRNET and NIPRNET (DISN) entry points,             high-capacity links for both voice and data com-
and the implementation of similar equipment by       munications. Its primary disadvantages are com-
the MAGTF will enable more efficient and flexi-      plexity and a lack of mobility. An MCR network
ble use of available bandwidth. Figure 5-10 shows    requires more time to set up and more expertise to
the many connectivity options available with         operate and maintain than an SCR network, and it
smart multiplexers.

Figure 5-9. TDN Server Components.


---

Communications and Information Systems _____________________________________________________________ 5-25

                 Figure 5-10. Smart Multiplexer Connectivity.

cannot operate on the move. Consequently, ma-      ations. Table 5-9 lists the MCRs employed by the
neuvering elements will rely on SCR in most situ-  MAGTF.

                 Table 5-9. MCRs

Category         MAGTF Radio                                  Type or Use
SHF terrestrial  AN/TRC-170(V)5                       Troposcatter radio terminal
SHF SATCOM
                   AN/TSC-85B                            GMF satellite terminals
UHF terrestrial    AN/TSC-93B
UHF SATCOM         AN/MRC-142                               Line of sight radio
HF multichannel  AN/TSC-96A(V)                     Satellite communications central
                   AN/TSC-120
                                                        Communications central


---

5-26 _______________________________________________________________________________________________ MCWP 6-22

a. SHF Terrestrial                                    Table 5-10. AN/TRC-170 Characteristics.

The AN/TRC-170 is a microwave radio terminal               Characteristic        AN/TRC-170 (V) 5
developed under the TRI-TAC program. The AN/          Frequency range      4.4 - 5.0 GHz (tunable in
TRC-170 provides secure digital trunking be-                               100-kHz increments)
tween major nodes of the MAGTF communica-             Bandwidth            3.5 or 7.0 MHz
tions network and limited dedicated circuits          Transmitter power    l kW
between individual subscribers. The AN/TRC-170        Diversity            Dual
includes antennas, radio transmitting and receiv-     Data rates           Up to 4,608 kbps
ing equipment, digital transmission group multi-      Channel capacity     Up to 144 (includes overhead)
plexing equipment, digital and analog voice and       (at 32 kbps)
data orderwires, and built-in test equipment for
fault isolation. Although longer links have been      (2) Modes of Operation. The AN/TRC-170 can
successfully installed, the AN/TRC-170 nominal-       be operated in one of three modes with various
ly supports a 100-mile communications link. Link      ranges achievable in each mode. The modes are
distance depends on the transmission technique        line of sight, troposcatter, and obstacle gain dif-
used (mode of operation), data rate, terrain and ho-  fraction. Each mode is useful under certain cir-
rizon angles, and atmospheric conditions. Com-        cumstances and in various environmental
munication battalions and Marine wing                 conditions. The extensive capabilities and flexi-
communication squadrons operate the AN/TRC-           bility of this system make it an invaluable trans-
170.                                                  mission system and workhorse that provides the
                                                      connectivity between the MSCs and the CE of the
(1) Low Data Rate Multiplexer (FCC-100). The          MEF.
most important feature of the FCC-100 is its capa-
bility to conserve the conditioned diphase band-      Line-of-sight mode requires minimal power out-
width and digital trunk group interfaces to the       put (down to 0.25 W) and requires straight-line
TRI-TAC system while providing a compatible           clearance between sites. Normally, line of sight is
interface to a commercial T1 multiplexer digital      used for links up to 10 miles. Figure 5-11 depicts
trunk group. Commercial and TRI-TAC interface         this mode of operation.
capabilities are available on both the loop and
trunk group sides of the FCC-100. It interfaces       Figure 5-11. Line-of-Sight Mode.
with a single group of the digital group modem
and provides up to 16 loop ports. These loop ports
can be a mix of synchronous, asynchronous, iso-
chronous, conditioned diphase data, and CVSD
and pulse-code modulation voice frequency (ana-
log-to-digital and digital- to-analog) signals. With
the appropriate interface card, two-wire foreign
exchange systems and four-wire voice compres-
sion coder-decoder (CODEC) modules, STU-III,
facsimile, and modem interfaces are supported.
Characteristics of the AN/TRC-170 are listed in
table 5-10.

   .


---

Communications and Information Systems _____________________________________________________________ 5-27

Troposcatter mode is used for link distances of 40    (4) Group Trunks. Up to four groups interface
to 100 miles. Ranges of up to 150 miles are possi-    with the AN/TRC-170 through CX-11230 or fi-
ble with troposcatter, and ranges of under 75         ber-optic cable.
miles, while possible, are difficult to achieve. A
small portion of the transmitted radio waves is re-   (5) Potential TRC-170 Configurations. The
fracted off the troposphere toward the distant-end    TRC-170 has a variety of potential configura-
AN/TRC-170. (See fig. 5-12.)                          tions, including:

             Figure 5-12. Troposcatter Mode.          Multitrunking Terminal. The multitrunking termi-
                                                      nal is used to provide connectivity between multi-
Obstacle gain diffraction mode is used for link       ple sites.
distances of 10 - 40 miles with an obstacle (e.g., a
mountain) located between the sites. Radio waves      Through Relay. The through relay is used to ex-
are diffracted off the obstacle toward the distant-   tend the distance of a link or provide connectivity
end AN/TRC-170. (See fig. 5-13.)                      when terrain prevents a single line of sight, obsta-
                                                      cle gain diffraction, or troposcatter link.
    Figure 5-13. Obstacle Gain Diffraction Mode.
                                                      Terminal Site. The terminal site is the terminated
(3) Subscriber Channels. By using two loop            end of a link.
group multiplexers (LGMs), up to 32 individual
channels (any combination of digital and analog,      Dedicated Subscriber. The dedicated subscriber is
depending on availability of circuit card assem-      used for point-to-point telephone and/or data cir-
blies) can be accommodated. These interface with      cuits.
the AN/TRC-170 through four-wire WF-16 or
CX-4566 cable.                                        LGM Used as an RMC. As an RMC, the LGM is
                                                      used to provide tactical telephone service to dis-
                                                      tant sites. The LGM is programmed the same as
                                                      two stacked RMCs off the switchboard (TTC-42
                                                      or SB-3865).

                                                      Figure 5-14 on page 5-28 shows how these con-
                                                      figurations could be used to form part of a
                                                      MAGTF network.

                                                      b. SHF SATCOM
                                                      SHF SATCOM is employed in the MAGTF by
                                                      using GMF TACSAT terminals and preplanned
                                                      DISN satellite and STEP access. These systems
                                                      are deployed by the communication battalion in
                                                      support of the MEF. The MEF uses two types of
                                                      GMF TACSAT systems: the AN/TSC-85B and
                                                      the AN/TSC-93B.

                                                      (1) AN/TSC-85B. The AN/TSC-85B is a full du-
                                                      plex nodal satellite communications terminal that
                                                      is capable of interfacing with a single satellite. It
                                                      transmits a single carrier and receives between
                                                      one and four carriers.


---

5-28 _______________________________________________________________________________________________ MCWP 6-22

Figure 5-14. Notional TRC-170 Network.

(2) AN/TSC-93B. The AN/TSC-93B is a full du-         available with MAGTF GMF assets are point-to-
plex satellite nonnodal communications terminal.     point, nodal, mesh, or hybrid mesh/nodal.
The TSC-93B simultaneously transmits and re-
ceives a single carrier.                             In the point-to-point configuration, each terminal
                                                     communicates with the other terminal only. All
(3) GMF TACSAT Capabilities. Table 5-11 lists        GMF terminals are capable of operating in this
the capabilities and characteristics of the SHF      configuration. Associated cut sheets and terminal
SATCOM terminal systems. Characteristics of          assignment sheets must be coordinated with
the AN/TSC-85B terminal are the same as those        detailed planning to ensure systems interoperabil-
of the AN/TSC-93B unless otherwise noted.            ity and minimize troubleshooting efforts. (See fig.
                                                     5-15.)
(4) Potential Configurations. A GMF network is
composed of nonnodal and nodal terminals con-        In the nodal configuration, the central or nodal
nected through a satellite to provide the user data  terminal is able to communicate directly with all
communications links. System configurations          of the peripheral or nonnodal terminals. The AN/
                                                     TSC-93B is a nonnodal terminal, and the AN/


---

Communications and Information Systems _____________________________________________________________ 5-29

Table 5-11. SHF SATCOM Terminal Systems Capabilities.

Transmit frequency range             7900 - 8400 MHz           AN/TSC-93B
Transmit bandwidth                   40 MHz
Power output                         500 W (nominal)
Receive frequency range              7,225 - 7,725 MHz
Receive bandwidth                    500 MHz

Group data rate                                  AN/TSC-85B

Balanced nonreturn to zero (NRZ)            8 - 1,152 kbps          8 - 1,152 kbps
Conditioned diphase                        72 - 1,152 kbps          8 - 1,152 kbps
Unbalanced NRZ                         288; 576; 1,152 kbps     288; 576; 1,152 kbps
Low-rate multiplexer: (12 channels/   8 low-rate multiplexers  3 low-rate multiplexers
low-rate multiplexer)
Maximum data rate                              256 kbps                   1 port
Minimum/maximum per channel                   1,256 kbps
TRI-TAC: (digital trunk group)       4 ports via group modem

      Figure 5-15. Point-to-Point Configuration.             Figure 5-16. Nodal Configuration.
                                                             Figure 5-17. Mesh Configuration.
TSC-85B is a nodal terminal. The nodal terminals
can communicate with up to four nonnodal termi-
nals. (See fig. 5-16.)

(5) Mesh Operations. In this configuration, the
nodal units communicate with each other. The
AN/TSC-85B can simultaneously communicate
with four other AN/TSC-100As or AN/TSC-85Bs
with all terminals operated in a nodal mode. For
communications to be possible, the baseband
equipment must be compatible. (See fig. 5-17.)


---

5-30 _______________________________________________________________________________________________ MCWP 6-22

(6) Hybrid Mesh/Nodal. In configuration, nodal      Table 5-12. AN/MRC-142 Characteristics.
units communicate with both nodal terminals and
nonnodal terminals simultaneously. The AN/          Frequency range      1,350 - 1,850 MHz
TSC-85B can communicate with any combination        Bandwidth            100 (125 optional) kHz
of up to four AN/TSC-100As, AN/TSC-85Bs,            Channel rate         144, 288, and 576 kbps
AN/TSC-94As, and/or AN/TSC-93Bs. The TSC-           Output power         Low: 300 mW (25 dBm)
100A and TSC-94A are GMF terminals that the                              High: 3 W (35 dBm)
Air Force operates and provides for MEF and/or      Frequency stability  10 ppm
Marine component support under a formal MOU.        Orderwire channel    Analog: 300 - 3,400 Hz
(See fig. 5-18.)                                                         Digital: 16 kbps

             Figure 5-18. Hybrid Mesh/Nodal         The AN/MRC-142 has four operational configu-
                          Configuration.            rations that provide the flexibility required of this
                                                    system in MEF operations. It is capable of being
c. UHF Terrestrial                                  configured as a single- or dual-link terminal, a
The AN/MRC-142 is the UHF terrestrial MCR           through repeater, or a drop-and-insert repeater.
terminal used by the MEF and its MSCs. A TRI-
TAC-developed transmission system, the AN/          One of the two line-of-sight radio subsystem ter-
MRC-142 is configured with two line-of-sight ra-    minals in each AN/MRC-142 is used to configure
dio subsystem terminals. The line-of-sight radio    a single UHF radio link. In this operational con-
subsystems can be set up to function as indepen-    figuration, the radio terminal equipment designat-
dent line-of-sight radio subsystem terminals or     ed “number 1" is used because it provides the best
can be configured together to function as a         equipment access and communicates with just
through repeater or drop-and-insert repeater. Each  one other AN/MRC-142.
line-of-sight radio subsystem terminal interfaces
with another AN/MRC-142 line-of-sight radio         Two line-of-sight radio subsystem terminals in
subsystem terminal over a UHF radio link using      each AN/MRC-142 are used when two separate
parabolic grid antennas mounted on telescoping      UHF radio links are required. In this configura-
50-foot masts. The characteristics of the AN/       tion, the two independent radio terminals
MRC-142 are provided in table 5-12.                 communicate with single line-of-sight radio sub-
                                                    system terminals in two other separate AN/MRC-
                                                    142s.

                                                    The through repeater configuration is used when a
                                                    particular radio path between two AN/MRC-142s
                                                    is longer than 20 - 30 miles or does not have a
                                                    line-of-sight path. The through repeater configu-
                                                    ration uses a third AN/MRC-142 to extend or
                                                    complete the radio link between two communicat-
                                                    ing AN/MRC-142s.

                                                    The drop-and-insert repeater configuration is used
                                                    when a particular mission requires access to traf-
                                                    fic at a repeater site. The drop-and-insert function
                                                    is accomplished by connecting a TD-1234 RMC
                                                    between the cable side interface of the two line-


---

Communications and Information Systems _____________________________________________________________ 5-31

of-sight radio subsystem terminals. In this mode,     mon channel is the primary channel for fleet
a digital transmission group from one end is put      broadcast traffic. The overload channel will
into the high group side of the RMC. The RMC          broadcast messages that could not be broadcast on
demultiplexes eight individual traffic channels       the common channel because of overload. It will
from the group and passes on a low group, which       also rerun messages transmitted on the common
is still combined. This combined low group is         channel.
connected from the RMC to the second line-of-
sight radio subsystem terminal and passed on to       SCI channels are automatically routed/forwarded
the distant end. The result is that eight channels    to the SCI facility, to the AN/MSC-63A, or di-
from the source are “dropped off” at the repeater     rectly to the user. Two weather channels can be
site and an additional eight channels (combined       transmitted over fleet broadcast and processed in
low group) are passed on to the distant-end termi-    the AN/TSC-96A(V). A tactical intelligence (TA-
nal.                                                  CINTEL) channel can be received in the AN/
                                                      TSC-96A(V) but not processed. United Press In-
d. UHF SATCOM                                         ternational and Associated Press International
                                                      news are sometimes transmitted and can be pro-
The AN/TSC-96A(V) is a UHF SATCOM central             cessed.
terminal that provides the capability to receive
and transmit GENSER message traffic. This sys-        The AN/TSC-96A(V) has several configurations
tem accesses AUTODIN through the Naval Com-           available to the supported unit. The subsystems
mon User Digital Information Exchange                 and capabilities/limitations listed above are avail-
Subsystem (CUDIXS) and provides access to se-         able in any configuration. The AN/TSC-96A(V)
cure voice communications and fleet broadcast         can be configured as—
via UHF satellites. It can be employed anywhere
in the world within the coverage of any fleet satel-  q A stand-alone communications message center
lite (FLTSAT), UHF follow-on satellites, leased       q Networked into an AN/MSC-63A message
satellite, or GAP FILLER satellites.
                                                         switch
The AN/TSC-96A(V) is a UNIX-based system              q Networked into the LAN.
hosted on two processors and workstations with
Naval Modular Automated Communications                The AN/TSC-96A(V) can be configured to sup-
Subsystem II (NAVMACS II) software. It inter-         port a unit with all of the capabilities of a commu-
faces with the AN/MSC-63A, Banyan VINES               nications center except the reproduction
servers, and PC-client software loaded on com-        capabilities. In this configuration, the AN/TSC-
puter terminals for message distribution. The sys-    96A(V) provides primary AUTODIN entry via
tem has the capability to receive four high-speed     the associated NCTAMS. In addition to the
fleet broadcast channels. It was designed with in-    GENSER message traffic capability, the AN/
ternal backup and the capability to remote DAMA       TSC-96A(V) can provide the using unit with a se-
secure voice up to 100 feet. The AN/TSC-96A(V)        cure voice capability.
can use four DAMA ports and monitor four fleet
broadcast channels. A daily communication status      The AN/TSC-96A(V) can be connected to the
report lists the available channels on the satellite  AN/MSC-63A message switch for increased ca-
for fleet DAMA and fleet broadcast.                   pabilities. In this configuration, the AN/TSC-
                                                      96A(V) can provide the primary or secondary
There are 16 total channels on the fleet broadcast    AUTODIN access for units connected to the AN/
network. One channel is used for timing and over-     MSC-63A.
head, leaving 15 operational channels. Eleven of
the fleet broadcast channels are secure and can be    The AN/TSC-96A(V) can be linked into the LAN
processed by the AN/TSC-96A(V). These are             through several options. If the network users are
called common and overload channels. The com-


---

5-32 _______________________________________________________________________________________________ MCWP 6-22

using PC-client software, the LAN can be admin-      tween ships and with wide-area voice networks
istered through the AN/TSC-96A(V). If the net-       ashore.
work is using Banyan VINES software, a third
computer terminal is needed between the servers.     TACINTEL. This subsystem is specifically de-
This terminal is the gateway between the Banyan      signed for special intelligence communications.
VINES server and the TAC-3 server. This termi-
nal requires Super TCP/IP and NAVMACS II             DAMA. This subsystem is designed to multiplex
software for the system to be compatible with        several subsystems, or users, on one satellite
Banyan VINES networks.                               channel. This multiplexing has the effect of al-
                                                     lowing more satellite circuits to use a single UHF
The AN/TSC-96A(V) uses the Navy UHF SAT-             satellite channel.
COM system, which consists of information ex-
change and quality monitoring subsystems.            Satellite Monitoring. This subsystem provides us-
Satellites relay communications and control infor-   ers of the UHF satellite communications system
mation as well as data to manage satellite resourc-  with means to analyze and resolve system and
es.                                                  equipment-related problems. The SATCOM sig-
                                                     nal analyzer is operational at NCTAMS.
The subsystems are designed to address specific
naval communications requirements. These sub-        e. Super High Frequency (SHF)
systems provide various communications net-          Tri-Band Advanced Range Extension
works with specific services and capabilities.       Terminal (STAR-T)

(1) Fleet Satellite Broadcast Subsystem. This        The STAR-T (AN/TSC-156) is a HMMWV-
is an expansion of the fleet broadcast, which his-   mounted, multichannel, tri-band SATCOM termi-
torically has been the central communications        nal that will be fielded in FY 99. The STAR-T
medium for operating naval units. Fleet broadcast    supports the equivalent of four 1.544 Mbps cir-
is a receive-only function that allows the sub-      cuits. It can communicate with the DSCS and
scriber the ability to monitor 4 channels at 75 bps  commercial satellite systems. It is capable of
per channel. In addition, fleet broadcast can be     wideband satellite transmission and reception
used as an alternate route for receiving message     over the DSCS. It is also capable of commercial
traffic if the CUDIXS link is not available. High-   satellite communications in the Ku and C bands
speed fleet broadcast is available from NCTAMS.      of the electromagnetic spectrum. The AN/TSC-
High-speed fleet broadcast gives the subscriber      156 will replace the current inventory of AN/
the ability to receive the four channels of fleet    TSC-93(B)’s and AN/TSC-85(B)’s in the FMF.
broadcast at 2,400 bps per channel.                  The STAR-T brings increased mobility, reduced
                                                     set-up/tear-down times, and commercial access
(2) CUDIXS/NAVMACS II. These two systems             capability to the Marine Corps. The STAR-T will
combine to form a communications network for         be organic to the Communication Battalion of the
transmitting GENSER message traffic between          Marine Expeditionary Force. In addition to sup-
ships and shore installations. CUDIXS is ashore,     porting the doctrinal MEF to Major Subordinate
and NAVMACS II is aboard ship and in the AN/         Command wideband links, STAR-T will provide
TSC-96A(V).                                          smaller MAGTF’s like MEU’s the bandwidth
                                                     they need to conduct a range of missions in the lit-
Secure Voice. This is a narrowband UHF sub-          torals. Maximum aggregate bandwidth on the
system that provides voice communications be-        downlink is equivalent to four 1.544 Mbps (T-1).
                                                     It will have an increased channel bandwidth and
                                                     greater operational capability.


---

Communications and Information Systems _____________________________________________________________ 5-33

f. Secure Mobile Anti-Jam Reliable                   making the AN/TSC-120 a highly interoperable
Tactical-Terminal (SMART-T)                          and flexible system. Each modem is limited to
                                                     emulating one modem-mode at a time, and only
The SMART-T, a HMMWV-mounted, tactical               one modem can be patched per sideband.
SATCOM terminal, Nomenclature: AN/TSC-
154. Scheduled for fielding in FY 99, this Ex-       AUTODIN interface is provided by using a laptop
tremely High Frequency (EHF) terminal is             computer that provides Modes I, II, and V AU-
mounted on a HMMWV. It is capable of Low Da-         TODIN access. It can transmit and receive Joint
ta Rate (LDR) and Medium Data Rate (MDR)             Army, Navy, and Air Force Publication (JAN-
transmission and reception over the Milstar satel-   AP)-128 messages at data rates of up to 2,400 bps
lite constellation. The SMART-T brings a new ca-     (Modes I and II) and 1,200 bps (Mode V). Allied
pability to the Fleet- protected, survivable         Communications Publication (ACP)-126 and
communications. It will be organic to the Com-       message text format editor messages stored on
munication Battalion of the Marine Expeditionary     3.5-inch floppy disks can be modified, stored, and
Force, and will also reside at the Communications    then transmitted.
Company of the Marine Division and the
Communications Platoon of the Marine Infantry        Automatic link establishment automatically se-
Regiment. SMART-T will also provide the means        lects an optimum HF communications channel
by which Marines participate in CINC and JTF         from an available list of approved, prepro-
mandated EHF communications circuits. Maxi-          grammed channels. It then executes a handshak-
mum aggregate bandwidth on the downlink is           ing protocol to connect two or more HF radio
1.544 Mbps.                                          systems in a half-duplex link with minimal opera-
                                                     tor involvement. Automatic link quality analysis
g. HF Communications Central                         calculates the quality of available channels and
                                                     displays the results in a numeric format. On the
The MAGTF uses the AN/TSC-120 for its HF in-         basis of the automatic link quality analysis results,
terface to AUTODIN. It is a self-contained, stand-   the operator can establish the link on the best
alone communications central used primarily for      overall channel or allow automatic link establish-
long-haul Defense Communications System entry        ment to establish the link on the first channel that
and point-to-point, beyond line of sight communi-    allows for communications. Once the link is es-
cations. It provides connectivity for the major      tablished, the operator must choose the best chan-
CEs of a MAGTF.                                      nels for transmitting and receiving in order to
                                                     establish the full-duplex link.
The AN/TSC-120 is shelter mounted on a heavy
HMMWV. It may also include one AN/PSC-5              h. MEF Use
DAMA-capable UHF TACSAT radio per system.
Each communication battalion maintains five          Through task-organization, the MCR equipment
AN/TSC-120s, which are operated in the 2–            can be used at any location and with any unit in
29.9999 MHz frequency range, with automatic          the MAGTF. However, the most common use of
tuning for 280,000 possible frequencies in 0.1-      this equipment within a MEF is as shown in fig-
kHz increments. The AN/TSC-120 is capable of         ure 5-19 on page 5-34. CJCSM 6231.04, Joint
either single or double sideband operation. Its in-  Transmission Systems, provides detailed informa-
ternal modems are capable of emulating several       tion about the operation of MCR equipment.
modems currently used in the DOD inventory,


---

5-34 _______________________________________________________________________________________________ MCWP 6-22
                                           Figure 5-19. MEF Notional MCR Connectivity.


---

Communications and Information Systems _____________________________________________________________ 5-35

             Section V

Special Purpose Systems

The MAGTF special-purpose system assets are           ness Data Link [SADL]) also have PLRS-related
systems designed to provide specific position lo-     requirements.
cation, navigation, information distribution, and
cooperative identification services. These systems    5502. Precision Lightweight GPS
serve all MAGTF elements, often through exter-        Receiver (PLGR)
nally managed satellite and aircraft relay systems.
These systems provide real-time information to        The AN/PSN-11 PLGR is a small, handheld, GPS
tactical users at the point of need.                  receiver that weighs approximately 3 lb. It pro-
                                                      vides precise positioning and timing solutions
5501. PLRS                                            based on signals received from the GPS satellite
                                                      constellation. Position can be displayed in virtual-
PLRS provides MAGTF commanders with near              ly any format, including latitude/longitude, mili-
real-time, accurate, three-dimensional position lo-   tary grid reference system, and Universal
cation and navigation information. It is a time-or-   Transverse Mercator. It contains 49 map datums,
dered, spread-spectrum radio system operating in      and users can program way-points for navigation
the Ultra-High Frequency (UHF) band between           with back azimuths and distances to the next way-
420 and 450 megahertz. Integral error detection       point available with the push of a button. The
and correction, cryptographic security, and fre-      PLGR is compatible with night vision goggles. It
quency hopping features provide resistance to         is important, however, to understand the differ-
electronic countermeasures.                           ence in capabilities between the PLGR and PLRS.
                                                      While the PLGR provides a dramatic improve-
The PLRS radio set can be employed in the fol-        ment in land navigation capability, it cannot pro-
lowing configurations: manpack, surface vehicle,      vide the location of another unit and has no
or aircraft. The five-ton truck configuration of the  communications capability beyond the passive re-
current PLRS Master Station is being replaced by      ceipt of location and time. It should be viewed as
the Net Control Station-EPLRS (Downsized)             a complement for, not a replacement of, PLRS.
(NCS-E[D]). The NCS-E(D) improves mobility,
flexibility, and reliability. It can accommodate up   5503. JTIDS
to 460 radio sets in a single PLRS “community.”
Key planning considerations are the number and        JTIDS is an advanced radio system that provides
location of “reference” radio sets and the location   information distribution, position location, and
of relays, as necessary. (Each radio set in the net-  cooperative identification capabilities in an inte-
work is capable of automatically relaying data to     grated form. The primary JTIDS mission is to co-
the NCS-E(D) without operator action.) Refer-         ordinate tactical resources for air defense of the
ence sites can be surveyed, in which case they are    MAGTF. JTIDS is a spread spectrum, fast fre-
fixed, or established by using a Global Position-     quency hopping, cryptographically secure, digital
ing System interface, which provides additional       (data and voice) communications system. The
mobility and versatility.                             system operates in the 960–1,215 MHz frequency
                                                      band and provides jam-resistant, line-of-sight
PLRS is employed by PLRS Platoon, Communi-            communications using a time division multiple
cations Company, Marine Division. The U.S. Ar-        access (TDMA) architecture. The system has a
my (Enhanced PLRS [EPLRS]), U.S. Navy (AN/            maximum range of 500 miles. The Marine Corps
KSQ-1), and U.S. Air Force (Situational Aware-


---

5-36 _______________________________________________________________________________________________ MCWP 6-22

will implement the JTIDS terminal in the TAOM          common capabilities. These terminals use multi-
to enhance coordination of antiair warfare. The        ple communications transmission paths and sound
other services are fielding JTIDS in aircraft as       information management to provide the ability for
well as in air defense command and control sys-        each user in the battlespace to view a common op-
tems. JTIDS is also an integral component of           erational picture/common tactical picture. The
NATO air defense systems.                              modular feature of these terminals allows produc-
                                                       ers and users in the MAGTF to incorporate IBS
5504. Integrated Broadcast                             into their existing CIS. Hardware and software
Services                                               existing in the MAGTF (IAS, TCO, ACE sys-
                                                       tems, etc.) can integrate the common IBS mod-
IBS is a worldwide, DOD standard network for           ules that add the required capability.
transmitting tactical and strategic intelligence in-   Alternatively, users may also obtain completely
formation and targeting data. IBS will integrate       configured tactical terminals. Employment of
intelligence broadcast using the DII for both          JTT/common IBS modules facilitates a seamless
broadcast and interactive dissemination. IBS will      transition from current dissemination systems to
migrate tactical terminals/receivers to a single, re-  the IBS without degrading the capabilities provid-
lated Joint Tactical Terminal (JTT) family. The        ed by the current systems.
JTT Common IBS modules will enable seamless
information displays on GCCS. The goal of IBS is       5507. TROJAN SPIRIT II
to resolve the proliferation of stovepipe intelli-
gence broadcast formats by providing the tactical      TROJAN SPIRIT II consists of two heavy HM-
commander with an integrated means of deliver-         MWVs with lightweight multipurpose shelters,
ing intelligence information to the warfighter.        trailer-mounted power generation units, and a
                                                       towed 2.4-meter (C, Ku band) or 6.1-meter tri-
5505. Commander’s Tactical                             band (C, Ku, and X band) antenna. The 6.1-meter
Terminal                                               antenna is not used by the Marine Corps. The sec-
                                                       ond heavy HMMWV is used as a maintenance
CTT (AN/USC-55) is a multi-service developed           shelter. TROJAN SPIRIT II is a mobile, SHF
special application UHF satellite communications       SATCOM system that is capable of receiving,
receiver that can be dedicated to receiving criti-     transmitting, and processing multimedia products,
cal, time-sensitive intelligence to commanders         including imagery and secure dial-up voice, data,
and intelligence centers at all echelons, in near-re-  facsimile, and video.
al-time, at GENSER or SCI levels. Its receiver
provides one full duplex and two receive-only          TROJAN SPIRIT II will be deployed to provide
channels. Planned concept of employment for            GENSER and SCI communications for intelli-
CTT is similar to that of the tactical receive         gence operations. TROJAN SPIRIT II provides
equipment (TRE); i.e., fielded widely within the       16 channels of digital voice or data when used ex-
MAGTF to allow access to intelligence broad-           clusively for SCI or collateral secret traffic. This
casts and intelligence collectors. Full operational    mode of operation allows a maximum T1 aggre-
capability for CTT is expected by the fourth quar-     gate data rate. If both SCI and collateral secret
ter of fiscal year 1998.                               traffic are handled, a 2-channel separation be-
                                                       tween SCI and collateral secret traffic results in a
5506. The Joint Tactical Terminal                      lower aggregate data rate. TROJAN SPIRIT II
                                                       provides LAN communications supported by two
JTT, with its common IBS modules, is capable of        separate Ethernet LANs (SCI and collateral se-
receiving diverse broadcasts into terminals with       cret) and entry to the SIPRNET and the JWICS.


---

Communications and Information Systems _____________________________________________________________ 5-37

5508. Global Broadcast System                       mander to support preparations for the introduc-
                                                    tion of follow-on forces. The Marine Corps
The GBS will augment and interface with other       currently augments MEU(SOC)s with this capa-
CIS and provide a continuous, high-speed, one-      bility. In coordination with the commander of the
way flow of high volume information to deployed     amphibious squadron, the organic CIS of the am-
or garrisoned Marine units. GBS will support rou-   phibious ready group and the embarked
tine operations, training and military exercises,   MEU(SOC), augmented with an enabler module,
crisis, situational awareness, weapons targeting,   can support initial command and control of fol-
intelligence, and the transition to and conduct of  low-on forces from either afloat or ashore.
opposed operations short of nuclear war. GBS
will provide the capability to quickly disseminate  The JTF enabler includes the GCCS deployment
large information products to various joint and     and operations modules, such as the JMCIS/TCO
small user platforms. GBS coverage will be          module; the CTAPS; the JDISS; and secure elec-
worldwide.                                          tronic messaging. Currently, an AN/TSC
                                                    93B(V)1 is used to provide high-capacity, long-
5509. JTF Enabler Module                            haul connectivity. The personnel and equipment
                                                    for the enabler are currently provided from the or-
The JTF enabler provides the JTF, Marine com-       ganic assets of the supporting comm battalion.
ponent, or MEF commander an initial, in-theater,
immediate, reliable command and control capa-       The JTF or follow-on forces enabler allows a JTF,
bility. Detailed guidance for the employment of     Marine component, or MEF commander to fall in
CIS in support of joint operations is found in JCS  on assets carried by a forward-deployed
Pub 6-0, Doctrine for Command, Control, Com-        MEU(SOC) and commence operations without
munications, and Computer Support to Joint Op-      delay. The MEU(SOC) can provide limited com-
erations; JCS Pub 6-02, Joint Doctrine for the      mand and control systems support ashore for a
Employment of Operational/Tactical Command,         short period of time. The responsibility for CIS
Control, Computer, and Communications Sys-          support for the JTF HQ shifts to the JCSE and the
tems; and the CJSM 6231 Series, Manual for Em-      JTF HQ organic information systems support up-
ploying Joint Tactical Communications.              on their arrival in theater. The JTF enabler mod-
                                                    ule will usually backload with the MEU(SOC)
The module includes the personnel and equip-        upon arrival of sufficient JTF HQ assets and capa-
ment needed to establish high-capacity, long-haul   bilities in order to be ready for employment as an
communications links and provide information        enabler for additional follow-on forces. The en-
systems services. This capability would be used     abler module, however, may also remain as part
by the JTF, Marine component, or MEF com-           of the MEF CE or Marine component HQ.

                                                    (reverse blank)


---

               Chapter 6

Planning and Execution

Effective C2 depends on the effective and efficient operation of CIS. These systems
provide the means to develop a common operational picture (COP); to prepare and
rapidly disseminate OPLANs and OPORDs; and to monitor, direct, and coordinate
maneuver, fires, and logistics. In turn, the effective, efficient operation of these CIS
depends on detailed planning that is thoroughly integrated with the operation plan-
ning process. Coordination and integration are key to ensuring development of
OPLANs that are supportable from a CIS perspective and CIS plans that are respon-
sive to the needs of the operation. Normally, the commander assigns the responsibili-
ty for detailed preparation of CIS plans and orders to the G-6/S-6, who is the CISO.

The CISO should be thoroughly familiar with the form, content, and techniques for
preparing these documents. This chapter describes the planning process as it pertains
to the CISO, establishes basic planning guidance, discusses planning considerations,
and describes CIS planning documents. This information is provided to assist the CIS
planner in participating in the overall operation planning process and in preparing
CIS plans that are complete and effective and that support the mission of the MAGTF
and the Marine component.

 Section I

Overview

Preliminary planning is conducted before the re-     q Mission analysis.
ceipt of a mission. It is based on the analysis of   q COA development.
facts and trends to predict probable commitments     q COA analysis.
and to anticipate what action will be required to    q COA comparison/decision.
accomplish future tasks. Preliminary planning        q Orders development.
makes use of available information and logical as-   q Transition to execution.
sumptions to prepare studies, estimates, and plans.
The depth of these studies, estimates, and plans is  MCWP 5-1 (draft) provides the details of the
based on the time available. They are refined as     Marine Corps planning process.
more information becomes available and are the
basis for subsequent planning. Other measures        All planning is time constrained. To maintain op-
that may be taken to reduce planning time include    erational tempo, an organization must employ
the use of existing SOPs, concept plans (CON-        techniques that reduce the overall time required to
PLANs) and OPLANs that can be tailored and re-       plan. Effective employment of information sys-
fined. Once a mission is received, operation         tems and information management procedures
planning involves six steps:


---

6-2 ________________________________________________________________________________________________ MCWP 6-22

permits concurrent, collaborative planning among       c. Other HQs
staff sections and between echelons. This speeds       The CISO must obtain information from other
up the planning process and, at the same time, re-     HQs during planning. Higher HQs may provide
sults in better coordinated plans.                     CIS support, impose special communications re-
                                                       quirements, or issue special communications in-
6101. Planning Information                             structions for the operation. Subordinate HQs
                                                       may require additional personnel, equipment, or
The CISO collects and analyzes all available in-       other assistance to accomplish their mission.
formation relative to the impending operation and
the resources available to support the operation to    6102. Coordination
provide the commander and other staff members
with sound advice for the employment of CIS.           Planning must be coordinated not only within the
The CISO uses this information as the basis for        local command, but with the HQs of senior, sub-
estimating the situation, making recommenda-           ordinate, adjacent, supported, and supporting
tions, and preparing CIS plans.                        units. The proper coordination of planning efforts
                                                       involves the prompt, continual exchange of infor-
a. Commander                                           mation, decisions, plans, orders, and instructions
                                                       among all interested parties. Coordination means
The commander briefs the staff and subordinate         include—
commanders on the mission as part of the mission
analysis. This briefing includes the action to be ac-  q Liaison with all personnel responsible for the
complished as well as the commander’s intent,             exchange of planning information and coordi-
which describes the desired end state. At the end         nation of planning activities.
of the mission analysis, the commander provides
initial planning guidance: the results of the mis-     q Interaction among G-6s/S-6s and communica-
sion analysis, necessary assumptions and con-             tions units and detachments.
straints, COAs to be considered, and any other
considerations that may influence planning. After      q Appropriate coordination and dissemination of
issuing this guidance, the commander keeps the            information by staff sections.
staff and subordinate commanders informed on a
continuing basis as mission-related information is     q Coordination of planning documents.
received and decisions are made.                       q Staff conferences for the exchange of informa-

b. Staff                                                  tion between HQs and development of mutual-
                                                          ly-agreed-upon COAs.
The CISO is the G-6/S-6 and, in this capacity, has     q Timely briefings to keep the commander and
staff cognizance for the overall CIS effort. The          staff informed of the current situation.
CISO must have continual interaction both with
other staff officers and with supporting and subor-    6103. Security
dinate CIS unit commanders. CISOs must obtain
essential information from other staff members to      Operational security, COMSEC and COMPUSEC
understand and support the developing situation.       are important considerations during the planning
Information that affects the employment of CIS         of any operation. To maintain surprise, it is neces-
must be aggressively pursued. Close coordination       sary to deny the enemy prior knowledge of details
is critical to the establishment of effective C2.      pertaining to an operation. Measures must also be
                                                       instituted to control access to information and
                                                       protect information systems and communications
                                                       networks.


---

Communications and Information Systems _______________________________________________________________ 6-3

6104. Estimates                                       available, and, when appropriate, are coordinated
                                                      with other staff sections. Recommendations are
The CIS officer prepares estimates to assist the      concise and presented in a form that requires only
commander in the analysis of alternative COAs.        the commander’s approval or disapproval.
On the basis of factors such as terrain, weather,
distance, scheme of maneuver, and availability of     6106. Preparing Plans
personnel and equipment, the CISO predicts the
supportability of COAs from a CIS perspective.        CIS planning is simplified when it is considered in
The CISO also provides the commander with rec-        reverse order (e.g., when developing a C3 Systems
ommendations on how the available means can           Annex for an amphibious operation, first address
best support the selected COA. Formal, detailed,      the assault phase and move in reverse order back
written estimates are usually prepared only during    to the planning and embarkation phases). A wide
preemployment. Once execution begins, written         range of planning considerations is covered in the
estimates are seldom used. Whenever the situa-        next paragraph. The maintenance and use of a
tion warrants, a revised estimate is briefed to the   standing CIS Annex, Annex K, which can be tai-
commander and/or other staff officers for their       lored for specific operations, greatly facilitates the
consideration in the planning process. In either      timely preparation of OPLANs. (See app. J.) The
case, the CISO’s estimate should derive from a        CIS procedures that remain constant, such as the
logical sequence of thought that considers all crit-  MAGTF internal telephone numbering scheme,
ical elements of CIS planning. A suitable form for    should not have to be re-planned regardless of the
a formal CIS estimate is included in appendix I.      time, location, or type of operation. The CIS plan-
                                                      ner may then concentrate on specific require-
6105. Recommendations                                 ments for a particular operation, with only a quick
                                                      review of the other items that may have changed
The CISO makes recommendations to the com-            over time.
mander, as required, to assist in establishing poli-
cies and making decisions. The CISO should also       6107. Implementing Plans
offer recommendations to other staff officers and
subordinate commanders on CIS matters. Al-            Once a CIS plan or annex is completed and ap-
though the CISO may follow formal or informal         proved, it must be implemented effectively. Close
procedures in arriving at and making recommen-        supervision and frequent examination of the status
dations, many of the recommendations are based        of information systems and communications net-
on observations or mental estimates. Recommen-        works by the CISO and staff are essential. Plans
dations based on other written studies or formal      will inevitably be modified as the operational situ-
estimates are usually submitted in writing. What-     ation develops. The CISO and staff must keep
ever the procedure, recommendations are the           abreast of developments and be prepared to adapt
product of careful analysis and comparison con-       the CIS plan to the changing situation to support
strained by the time available. They are candid       and maintain MAGTF operational tempo.
and objective, are based on the best information


---

6-4 ________________________________________________________________________________________________ MCWP 6-22

Section II

CIS Requirements

The CISO must determine the resources required      ing fires, and in an amphibious operation, the
to support the operation and request augmentation   landing plan. Analysis of the concept of opera-
if needed. To do this, the CISO must first deter-   tions gives the CISO an understanding of when
mine the information processing and information     events will occur, projected locations and move-
transfer requirements to be supported. This in-     ment of units and C2 facilities, and the distances
volves extensive coordination with CISOs of         the communications network must span.
higher, subordinate, adjacent, supporting, and
supported units. All aspects of the operation must  6204. Task Organization
be considered to accurately determine the require-
ments for information processing and information    The task organization lists all tactical, administra-
exchange.                                           tive, and service groupings with the commanders
                                                    of each. It depicts the organization for combat and
6201. Mission                                       indicates the command relationships of the as-
                                                    signed forces. Review of the task organization
The mission statement describes, in concise         helps the CISO determine the requirements for in-
terms, the location of the operation, the time it   ternal and external information flow to be sup-
will occur, and the tasks to be accomplished. The   ported by the communications network. Review
mission includes the commander’s intent—the         of the task organization also enables the CISO to
purpose of the action. Careful review of the mis-   identify the C2 facilities and their associated re-
sion gives the CISO a general idea of what overall  quirements for information systems support. A
CIS resources will be required to support the op-   major consideration is whether the component
eration. At the component level, the possible des-  and the MAGTF commanders are supported by
ignation of the Marine component commander as       separate staffs and, if by separate staffs, whether
a functional component commander or the possi-      or not those staffs are collocated. The requirement
ble requirement to provide the nucleus of a JTF     to support separate, geographically separated,
HQ would drive a significant increase in CIS re-    component and MAGTF CE HQs will severely
quirements.                                         stress the capabilities of a communication battal-
                                                    ion.
6202. Courses of Action
                                                    After the CISO has determined the requirements
A COA is an approach to accomplish the mission.     to be supported, the factors that may affect the
The CISO develops estimates of supportability       employmen of information systems and commu-
for each COA considered while at the same time      nications networks are analyzed. These include:
influencing COA development on the basis of
CIS capabilities and limitations.                   q Available resources.
                                                    q Enemy situation.
6203. Concept of Operations                         q Environment.
                                                    q Information management plan.
The concept of operations generally depicts the
scheme of maneuver, the employment of support-


---

Communications and Information Systems _______________________________________________________________ 6-5

6205. Available Resources                            Storm, newly fielded TRI-TAC equipment re-
                                                     quired extensive software modifications to
The CISO must consider all available resources to    achieve interoperability between Services and
determine the extent of support that can be pro-     with joint HQs. The CISO must ensure that users
vided and to determine shortfalls in the capability  of CIS are aware of the potential for incompatibil-
to support the mission. This includes resources      ity and take appropriate action to ensure that sys-
both organic and external to the MAGTF.              tems are interoperable and compatible. MCTSSA
                                                     is responsible for software support of fielded sys-
a. Personnel                                         tems, and MEF CISOs should coordinate with
                                                     MCTSSA to implement new releases of software
The number, military occupational specialties,       and to identify and resolve software problems.
state of training, and availability of replacements
are of primary concern. Individual mobilization      d. Supplies
augmentee billets must be filled, contractor sup-    The quantity and condition of available supplies
port requirements must be identified and, when       such as wire, batteries, and repair parts, and the
appropriate, agreements for other-Service aug-       availability of resupply in the objective area need
mentation must be exercised.                         to be coordinated.

b. Equipment and Services                            e. Maintenance
                                                     Maintenance requirements must be anticipated
The availability, condition, and operational char-   and support planned for each phase of the opera-
acteristics of equipment must be identified, as      tion. Particular attention to the availability of test
must the availability of external telecommunica-     equipment is necessary to support maintenance
tions services. This includes identifying equip-     efforts in the objective area. Planning must take
ment available through joint or other-Service        into consideration the availability of maintenance
augmentation and telecommunications services         support through inter-Service agreements and
available through commercial sources, and, in        host nations.
some cases, host nation support. Points of contact
for information concerning the employment and        6206. Enemy Situation
maintenance of equipment should be researched
in advance of operations. The Marine Corps Sys-      Enemy intelligence, reconnaissance, and EW ca-
tems Command, the Marine Corps Network Oper-         pabilities can significantly degrade and in some
ations Center (NOC), the Command and Control         cases exploit our CIS. The potential for disruption
Systems School, and the Marine Corps Communi-        of MAGTF command and control must be under-
cations-Electronics School are excellent sources     stood and countered. The CISO should always as-
of information, as are equipment manufacturers       sume that the enemy has the capabilities to
and suppliers. Information on interfaces to joint,   intercept, locate, exploit, deceive, and/or other-
other-Service, allied, commercial, and host nation   wise degrade MAGTF CIS. The enemy threats
equipment should be researched.                      can be countered through—

c. Software                                          q Threat awareness.
                                                     q Sound COMSEC and COMPUSEC proce-
The compatibility and interoperability of CIS are
major concerns. Even in a single information or         dures.
communications system, different versions or re-     q Restricted RF emissions.
leases of software may be incompatible. For ex-      q Employment of secure, jam-resistant, low-
ample, various versions of the GCCS (JMCIS
Unified Build and MAGTF C4I Software Base-              probability-of-intercept transmission equip-
line) are not compatible and can preclude infor-        ment.
mation sharing between the embarked MAGTF
and shipboard systems. In Operation Desert


---

6-6 ________________________________________________________________________________________________ MCWP 6-22

q Use of wire and messengers.                          terference, both natural and manmade, can
                                                       severely degrade the performance of communica-
Chapter 7, sections I and II, address COMSEC           tions systems. An effective training program for
and COMPUSEC.                                          operator and maintenance personnel is the key to
                                                       being able to communicate effectively in an ad-
The CISO must take into consideration the threat       verse electromagnetic environment. Information
capability to employ NBC weapons. Given the            on the electromagnetic environment may be ob-
continued proliferation of weapons of mass de-         tained from the Joint Spectrum Center and in
struction to both outlaw nations and non state ac-     MCRP 6-22B, MSP for Spectrum Management in
tors, even military operations on the lower end of     a Joint Environment.
the conflict spectrum may include their use. Con-
sequently, the CISO must plan for CIS support in       d. Facilities
a contaminated environment and be prepared to
provide rapid decontamination of CIS equipment         The CISO should take into account the infrastruc-
and facilities. (See app. K.)                          ture in the AO, especially telecommunications
                                                       and electric power generation and distribution fa-
6207. Environment                                      cilities, and its potential availability either
                                                       through host nation support or capture.
The CISO must consider those physical character-
istics such as terrain, weather, and the electro-      6208. Information Management
magnetic environment of the objective area that        Plan
may affect the employment of CIS.
                                                       The information management plan describes the
a. Terrain                                             processes by which information will be created,
The CISO should be aware of the topography,            processed, maintained, and disseminated within
vegetation, road networks, soil conditions, and        the organization. Normally, the information man-
other terrain features in the objective area. The      agement plan will consist of a set of SOPs that
terrain has a major bearing on the location of fa-     are updated as necessary to fit the circumstances
cilities, sitting of antennas and relays, effective    of a particular exercise or operation and promul-
range of line-of-sight transmission systems, in-       gated as an annex to the OPLAN or OPORD. The
stallation of wire lines, and effectiveness of mes-    unit information management officer, with the
senger service.                                        guidance of the C/S or XO, and in coordination
                                                       with the information management officers of each
b. Weather                                             staff section and subordinate units, develops the
The climatic conditions in the objective area de-      information management plan. The CISO must
termine the requirements for special equipment or      ensure that the employment of CIS support the in-
supplies such as heaters, air conditioners, shelters,  formation management plan. The information
or cold weather batteries. Many CIS do not oper-       management plan will include the following:
ate effectively under conditions of extreme heat
or cold, and heavy precipitation can adversely af-     q Procedures by which information requirements
fect radio transmissions. The CISO must plan to           are identified, developed and prioritized, in-
operate under all weather conditions that will be         cluding how CCIRs are nominated, approved,
encountered during the operation.                         collected, reported, maintained, and dissemi-
                                                          nated. The information management plan will
c. Electromagnetic Interference                           identify and assign responsibility for standing
The CISO must take into account the electromag-           CCIRs (key items of information that will be
netic environment in the AO. Electromagnetic in-          required in almost any situation). Standing
                                                          CCIRs must be reviewed for relevancy and
                                                          modified, expanded, or deleted as necessary.


---

Communications and Information Systems _______________________________________________________________ 6-7

   The CCIR procedures will include guidance on       • Policy governing the use of e-mail.
   filtering and fusing raw data before submission
   and dissemination.                                 • Supply-push and demand-pull approaches to
                                                         information dissemination, as well as eche-
q Procedures by which the COP is maintained              lon skipping where appropriate (e.g., re-sup-
   and shared. This will include guidance on the         ply requests bypassing intermediate
   level of detail (e.g., a division COP might dis-      echelons).
   play friendly units down to the battalion level,
   and a battalion COP might display friendly         • Manual as well as automated procedures for
   units down to the platoon level); assignment of       handling information dissemination. Tactical
   responsibility for the quality and integrity of       echelons must avoid overloading communi-
   the COP database, including the management            cation circuits. Particular attention should be
   of air, ground, and sea tracks/unit locations;        given to the best approach for transferring
   and assignment of responsibility for maintain-        high-volume data formats such as imagery,
   ing the status of friendly and enemy units. Each      video, maps, and overlays. Messengers and
   staff section will be assigned responsibility for     hard copy OPORDs remain a reliable means
   providing status information for the functional       of information dissemination.
   areas over which they have cognizance.
                                                      • Procedures for the design, maintenance, ac-
q Designation of data standards, including stand-        cess, use, synchronization, and integration of
   ards for symbology, report/message formats            databases supporting command and control.
   and data element standards.
                                                      • Procedures and schedules for daily briefings,
q Procedures supporting the effective flow of            meetings, and reporting. This daily opera-
   both routine and time-sensitive information:          tions cycle is developed in coordination with
                                                         all staff sections and subordinate units. Upon
   • Automated networking techniques such as             commencement of operations, the C/S or XO
      news groups, home pages, and other Inter-          may modify the operations cycle as neces-
      net-like methodologies.                            sary to maintain tempo or to adjust to the un-
                                                         folding situation.


---

6-8 ________________________________________________________________________________________________ MCWP 6-22

Section III

Pre-Deployment Preparation

Mission accomplishment often depends on pre-           memorandums of agreement for support from
deployment planning and preparation. Numerous          other Services and the procedures for exercising
actions must be accomplished by the G-6/S-6 be-        those agreements, as well as procedures for ob-
fore deployment. Appendices C, F, G, H, and K of       taining support from the Reserve. At the present
this publication and CJCSM 6231.07A (app. G),          time, both the Army and the Air National Guard
contain pre-deployment checklists that should be       have memorandums of agreement in effect with
considered for incorporation into unit SOPs.           the Marine Corps to provide a portion of the com-
                                                       munications equipment and personnel required to
6301. Review Existing Plans and                        support two Marine component HQs.
Orders
                                                       6304. Coordinate Frequencies
OPLAN and OPORD communications-electron-
ics/CIS annexes, time phased force deployment          The type and number of frequencies required
data (TPFDD) files, planning guidance, and any         should be identified in sufficient time and for-
other appropriate documentation, including after-      warded to the frequency manager who is found at,
action reports and CIS annexes from previous op-       but not limited to, the joint, CINC, Force, MEF,
erations of a similar nature and unit SOPs, should     and Base levels. Liaison should be made with the
be reviewed. Items not covered adequately in ex-       frequency coordinator so that required frequen-
isting OPLANs or OPORDs should be identified.          cies can be obtained, assigned, and distributed in
The CISO should prepare and submit updated in-         sufficient time. The frequency coordinator pro-
formation for the TPFDD file.                          vides guidance on frequencies used in garrison,
                                                       during embarkation, in transit, and in the AO.
6302. Prepare Troop and
Equipment Lists                                        6305. Request Satellite Access

Personnel requirements must be determined and          The CISO should identify requirements and coor-
the troop list prepared. The troop list should in-     dinate requests for UHF and SHF satellite access
clude rank, military occupational specialty, line      through the frequency manager.
number, and billet description. The CISO should
determine equipment requirements and prepare an        6306. Compile a Publications
equipment list summarizing all Class VII items to      Library
be deployed.
                                                       General and technical publications need to be em-
6303. Request Augmentation                             barked to ensure that deployed units have access
                                                       to the information they need. It may be advanta-
Augmentation of personnel and/or equipment             geous to maintain some publications on mass
should be requested if shortfalls exist in either ar-  storage media. However, essential publications
ea. The CISO must be familiar with any existing        should be available in hard copy.


---

Communications and Information Systems _______________________________________________________________ 6-9

6307. Initiate                                       6310. Submit Communications
Telecommunications Service                           Guard Shifts
Requests
                                                     Upon deployment, a unit must submit a communi-
To request U.S. or host nation commercial re-        cations guard shift message to ensure continued
sources, a telecommunications service request        receipt of its record traffic. Guard shift messages
must be submitted. The telecommunications ser-       are used to update the Common Source Route
vice request format is found in various DISA Cir-    File. Guard shift procedures are contained in na-
culars and should also be included in the unit CIS   val tactical publication (NTP) 4, Fleet Communi-
SOP. Telecommunications service requests are         cations. Deployed organizational and individual
normally submitted via the chain of command          e-mail systems must also be established and re-
well in advance of the operation.                    designated for the deployment period.

6308. Conduct Communications/                        6311. Request COMSEC Material
Command Post Exercises
                                                     Requests for appropriate cryptographic material
These exercises are designed to test personnel and   (equipment keys, etc.) must be expeditiously sub-
equipment readiness. In a communications exer-       mitted through the appropriate chain of command
cise, the viability of the communications network    to the controlling authority for each key required.
is tested. In a CP exercise, unit staff functioning  The controlling authority validates the request
and information systems support are exercised to     and forwards it to the director of the Communica-
prepare for an operation. The optimal way to test    tions Security Material System for processing.
both the staff and the adequacy of CIS support is    The requisitioning process can be lengthy.
by combining these two exercises. The staff be-
come familiar with the information systems they      6312. Coordinate Logistics
will employ in the operation, and the CISO is able
to test the adequacy of the communications net-      The G-6/S-6, in close coordination with the G-4/
work as well as the information systems support      S-4, must plan for logistic matters. The following
before operational employment.                       areas require special attention.

6309. Provide CIS Support for                        a. Equipment
Embarkation                                          To ensure equipment readiness, limited technical
                                                     inspections should be conducted on all equipment
Support is required throughout the embarkation       scheduled for embarkation. These inspections
phase. Movement to sea and aerial ports of em-       must be conducted as early as possible to allow
barkation requires communications nets for con-      time for correction of deficiencies before embar-
voy control and coordination, and the actual         kation. Waterproofing and weatherproofing of
embarkation of troops, equipment, and supplies is    equipment before deployment are essential to pro-
most efficient when supported with information       tect the equipment while in transit.
systems. The preferred means of providing this
support is through the use of equipment and per-     b. Power Requirements
sonnel who are not deploying with the MAGTF.         The G-6/S-6 officer must identify to the G-4/S-4
                                                     the electrical power requirements.


---

6-10 _______________________________________________________________________________________________ MCWP 6-22

c. Embarkation Material                                based on the equipment density list, must either
Units should maintain materials required for con-      accompany the deploying unit or be staged in the
struction of embarkation boxes to meet mission         AO. In addition to repair parts, appropriate test
requirements.                                          equipment and maintenance personnel must be
                                                       available. Regardless of the operational readiness
d. Technical Representative Support                    of equipment at embarkation, it will deteriorate if
Because of technical sophistication, contract tech-    not properly maintained during sustained opera-
nical representatives from the manufacturer are        tions. Required items are often held in a contin-
required to maintain some critical low-density         gency block that is identified by need and held
equipment. Technical representative support is         ready for issue on demand. It is the responsibility
available for exercises and operations but requires    of the CISO to request this block through the sup-
considerable lead time. Requests for such support      ply officer.
should be submitted in accordance with current
directives.                                            g. Supplies
                                                       In addition to repair parts, the G-6/S-6 must en-
e. Hazardous Cargo                                     sure that adequate provision is made for re-supply
Hazardous cargo is any material that is prone to       of other critical, high-volume consumables such
fire, explosion, or toxic seepage, thereby present-    as batteries and petroleum, oil, and lubricants.
ing an inherent danger to personnel and equip-
ment as well as to ships and aircraft. This type of    6313. Effect Liaison/
material must be identified, packaged according        Coordination
to existing transportation regulations, and certi-
fied by a competent authority. Many restrictions       For the CISO to accurately assess requirements
apply. It is critical that these matters be addressed  and plan the necessary CIS support, close liaison
before embarkation so that vital equipment and         and coordination with senior, adjacent, support-
supplies are not rejected by loadmasters or com-       ing, and subordinate CISOs as well as other staff
bat cargo officers during embarkation.                 officers are essential. Appendix P and CJCSM
                                                       6231.07A, appendix A, identify liaison/coordina-
f. Repair and Maintenance                              tion points of contact.
Sustained operations result in the need to main-
tain and repair equipment. Required repair parts,


---

Communications and Information Systems _____________________________________________________________ 6-11

                    Section IV

CIS Plans, Orders, and Directives

CIS plans and orders describe how CIS will be        loss of effectiveness. The procedures are applica-
employed to support the commander in the exer-       ble unless ordered otherwise. The SOP reflects
cise of C2. The G-6/S-6 is responsible to the com-   approved doctrine as published in current doctri-
mander for preparing the following plans, orders,    nal publications, directives, and regulations, mod-
and directives:                                      ified to satisfy local operating conditions and the
                                                     policies of the command. The SOP is normally
q CIS SOPs.                                          followed, but may be modified, tailored, or even
q Communications-electronics operating instruc-      completely discarded depending on the situation.
                                                     In no way should the SOP be allowed to reduce
   tions (CEOI).                                     flexibility and adaptability or to limit creativity
q CIS plan.                                          and initiative. The SOP is usually referred to in
q CIS estimate                                       the OPORD with exceptions identified. The
q CIS concept.                                       amount and type of information to be included in
q Paragraph 5 of the OPORD or OPLAN                  an SOP must be carefully determined. Procedures
q CIS Annex (Annex K).                               must be clear and concise. In the absence of spe-
                                                     cific orders to the contrary, the instructions con-
The G-6/S-6 is often required to provide CIS         tained in the SOP are guiding. The SOP—
guidance for inclusion in other annexes of an
OPLAN or OPORD. This may include the air an-         q Reduces the need for other types of orders and
nex and the naval gunfire annex. Planners must          simplifies the preparation and transmission of
ensure that all necessary CIS guidance and in-          orders.
structions are covered in Annex K, other designat-
ed annexes where certain CIS instructions are        q Simplifies training by establishing uniform
appropriate, or both. The practice of cross-refer-      practices for the unit.
encing annexes without adequate harmonization
can result in gross omissions of required CIS        q Promotes understanding and teamwork
guidance. Plans and orders follow standard for-         throughout the command.
mats. For a detailed discussion of standard for-
mats for OPLANs and OPORDs, see MCWP 5-1             q Facilitates and expedites execution of routine
(draft).                                                procedures.

6401. Standing Operating                             q Minimizes confusion and error.
Procedure
                                                     The scope of the SOP varies with the echelon of
The SOP is one of several types of orders that the   the preparing command. An SOP prepared by a
commander develops and uses to accomplish the        division is broad in scope and provides essential
mission. It is a set of instructions covering those  instructions for all major elements of the division.
features of operations that lend themselves to a     The SOP of a subordinate unit applies only to that
definite or standardized set of procedures without   individual unit and its subordinate elements. As
                                                     the scope of the SOP narrows, the amount of de-
                                                     tail increases. For example, an SOP for a section
                                                     is detailed, describing what each individual does
                                                     and in what sequence with respect to the actions
                                                     of other individuals in the section.


---

6-12 _______________________________________________________________________________________________ MCWP 6-22

a. Format                                               for transmittal, receipt, and processing of
                                                        record traffic.
Although there is no established format for an
SOP, one of the two following formats is general-    q Procedures covering the exchange of organiza-
ly used. An SOP may be formatted as an all-inclu-       tional and individual e-mail. The authorization
sive document containing in the main body               for use and the records to be maintained should
sections and paragraphs detailing the duties and        be prescribed.
responsibilities of subordinate units and, where
applicable, of personnel. This format does not       q Procedures for wire communications, including
have annexes or enclosures. The other approach is       wire and cable installation practices; priority of
to publish the main body of the SOP as a basic          installation; tagging procedures; general guid-
document containing instructions of a general na-       ance pertaining to locations of switching, rout-
ture with annexes for technical details and specif-     ing, and patching facilities; LANs and terminal
ic instructions for individual units and/or             equipment; and instructions governing the
personnel. For example, the basic document could        placement of calls. Also, inclusion of directory
contain information for the communications bat-         service information, guidance for obtaining ser-
talion as a whole with annexes for different func-      vice, and instructions for maintenance of equip-
tional areas such as TECHCON and systems                ment and lines should be considered.
planning and engineering. SOPs prepared by sub-
ordinate units must comply with and be coordi-       q Instructions pertaining to the planning, installa-
nated with pertinent parts of the SOP of the higher     tion, operation, and maintenance of SCR equip-
command. SOPs should not repeat practices or            ment and guidance for the composition and
procedures governed by other directives or docu-        operation of radio nets, including those re-
ments that are readily available to all elements of     quired for data communications. Information
the command unless such repetition is required to       about data interface modules used with the ra-
clarify local operating practices.                      dios and the advance planning required for fre-
                                                        quency hopping radios and TACSAT
b. Suggested Content                                    communications should be included. Actions to
                                                        be taken in the event of imitative communica-
q References such as MCWPs, field manuals,              tions deception or jamming should be defined.
   technical manuals, regulations, and the SOPs
   and CEOI of higher commands.                      q Instructions pertaining to the planning, installa-
                                                        tion, operation, and maintenance of the
q Planning checklists.                                  switched backbone that apply to all elements of
                                                        the command. Detailed instructions on opera-
q Training instructions outlining general training      tions should be published in the SOP of the unit
   standards. Detailed instructions are normally        that owns the equipment. Joint and other-Ser-
   contained in quarterly training schedules.           vice interfaces, means of entry into the DISN,
                                                        and planning for TACSAT communications
q Information systems security instructions that        should be addressed.
   address both COMSEC and COMPUSEC. In-
   structions should be limited to those that are    q Instructions pertaining to the planning, installa-
   applicable to all elements of the command and        tion, operation, and maintenance of LANs, in-
   are not contained in the command CEOI, as the        cluding switch, router, and/or server planning,
   purpose of this section should be to develop         installation, operation, and maintenance.
   and maintain CIS security awareness through-
   out the unit.                                     q General procedures to be employed by all users
                                                        for the planning, installation, operation, and
q Physical security instructions designed to de-        maintenance of radio-wire integration facilities.
   velop an awareness for physical security and to
   promulgate and standardize physical security      q Instructions pertaining to the general use and
   procedures throughout the unit.                      distribution of visual and sound signal devices
                                                        (flags, lights, pyrotechnics, panels, arm-and-
q Instructions for the operation of communica-          hand signals, whistles, sirens, bells, voice am-
   tions centers, including location and procedures     plifiers, explosive devices, etc.).


---

Communications and Information Systems _____________________________________________________________ 6-13

q Procedures to be followed to obtain frequen-         q Specific responsibilities of each major subordi-
   cies, restrictions on the use of frequencies, pro-     nate element.
   cedures for reporting interference, and
   conditions under which radio silence is re-         q Instructions on routine operations of such im-
   quired.                                                portance that continuing instructions are desir-
                                                          able.
q Instructions covering the identification of cir-
   cuits and systems for installation and control      q Instructions governing the execution of all re-
   purposes.                                              sponsibilities for CIS support.

q Special communications support procedures            q Instructions pertaining to routine administra-
   (e.g., R and Y routers) that may be required for       tive and logistic support, including personnel
   intelligence systems in the command.                   policies and procedures, supply and mainte-
                                                          nance procedures, inspection procedures, phys-
q Identification of the various command, control,         ical security, and other areas as directed by the
   and coordination agencies, centers, and cells          unit commander.
   (this manual refers to these entities generically
   as command and control facilities, for example,     Additional subjects to consider include specific
   COC, DASC, FSCC, TACC, and TAOC) with-              responsibilities for sections and/or individuals as
   in the command and their requirements for           well as for subordinate units, guidance for inclu-
   information systems support and communica-          sion in the SOPs of subordinate units, CIS poli-
   tions connectivity.                                 cies, key references, exercise guidelines, safety
                                                       instructions, and displacement procedures.
q General procedures to be employed by all users
   for the planning, installation, operation, and      6402. CEOI
   maintenance of general-purpose computers and
   general guidance for interfacing all tactical in-   The CEOI contains the technical guidance re-
   formation systems into the communications           quired to establish and maintain communications
   network. Detailed instructions on the operation     support of operations. The CEOI amplifies the
   of individual tactical information systems          CIS SOP by providing detailed guidance for the
   should be published separately.                     coordination and control of communications
                                                       means and functions. SPEED includes the Revised
q General instructions pertaining to communica-        Battlefield Electronic CEOI System (RBECS), a
   tions control not covered elsewhere in the SOP.     module to support generation of the CEOI. Input
   More detailed instructions on communications        is normally requested from subordinate com-
   control will be promulgated in the CIS SOPs of      mands by higher HQ. Sufficient copies of the
   communications units.                               CEOI should be maintained by the issuing HQ to
                                                       allow issue to other units that may be attached for
q Information pertaining to the location of the        an operation. The following information and in-
   CISO and C2 facilities, selection of CPs, in-       structions can usually be included in the CEOI:
   structions governing the preparation of the
   CEOI, subordinate unit SOPs, and instructions       q Call sign assignments.
   pertaining to CIS planning for future opera-        q Frequency assignments.
   tions.                                              q Radio guard charts (app. M).
                                                       q Radio net identifiers.
c. Communications Units                                q Telephone directory names and numbers.
                                                       q Identification and marking panel codes.
The CIS SOP for a communications unit is unique        q Signal panel message instructions.
in that it addresses the operation of the unit in the  q Pyrotechnic and smoke codes.
execution of its primary missions. Its scope is de-
termined by the type of unit, the amount of detail
the unit commander desires, and the echelon of
command to which the unit is assigned. As a min-
imum, the SOP should include—


---

6-14 _______________________________________________________________________________________________ MCWP 6-22

q Ground-to-air signals.                             q Compare the alternatives and select the best
q Sound warning signals.                                one.

6403. CIS Plan                                       q Translate the selected solution into a decision
                                                        (if the commander’s estimate) or recommenda-
A CIS plan is normally created by combining the         tion (if the G-6/S-6 estimate).
CIS SOP and the CEOI. This combined document
then becomes a basic CIS plan. The tactical and      6405. CIS Concept
administrative instructions of the SOP form the
body of this plan. The operating instructions of     After developing the CIS estimate and gaining the
the CEOI are normally issued as a supplement.        commander’s approval, the CISO prepares the
During the discussion of the tactical and adminis-   CIS concept. The concept outlines how CIS are to
trative instructions in the body, reference should   be employed to support command and control
be made as necessary to the supplement that con-     throughout the operation. The CIS concept in-
tains related technical operating instructions. The  cludes information such as—
preparation of the operating instructions as a sep-
arate supplement facilitates revision or extraction  q Numbers, types, classification levels, and loca-
as the need arises.                                     tions of C2 facilities.

6404. CIS Estimate                                   q Numbers, types, classification levels, locations,
                                                        and mode of operation of SCR nets.
As discussed earlier, the CIS estimate is a tool or
procedure the G-6/S-6 uses to assist the com-        q Numbers, types, classification levels, locations,
mander in determining the best COA to accom-            and channelization of MCR circuits, including
plish a mission. On the basis of CIS estimates, the     location of transmission equipment.
G-6/S-6 provides the commander with insights in-
to the supportability of alternative COAs and rec-   q Numbers, types, classification levels, and loca-
ommendations on how available means can best            tions of wire circuits, including location of ter-
support the selected COA. Appendix I provides a         minal equipment.
suggested format for the CIS estimate. The pro-
cess of developing a CIS estimate is analogous to    q Numbers, types, classification levels, and loca-
and completely integrated with the process of de-       tions of radio-wire integration facilities.
veloping a preferred COA for the operation. De-
pending on the time available, several iterations    q Numbers, types, classification levels, and loca-
may be performed as COAs are refined and modi-          tions of LANs.
fied, and the CIS estimate is updated accordingly.
The following five steps are useful for preparing    q Numbers, types, classification levels, and loca-
the estimate:                                           tions of switching centers, routers, and gate-
                                                        ways.
q Develop an understanding of the mission, the
   commander’s intent, and the situation.            q Numbers, types, classification levels, locations,
                                                        and channelization of satellite links, including
q Consider all factors that affect employing CIS,       location of terminal equipment.
   and develop alternative approaches to satisfy
   CIS requirements.                                 q Numbers, types, classification levels, and loca-
                                                        tions of terminal devices (computer, facsimile,
q Analyze each alternative to determine its ad-         etc.).
   vantages and disadvantages.
                                                     q Frequency requirements.
                                                     q Call sign requirements.
                                                     q Visual, sound, and messenger communications.
                                                     q Communications control procedures, including

                                                        number, types, and location of communications
                                                        control facilities.


---

Communications and Information Systems _____________________________________________________________ 6-15

The above list is not all-inclusive. It provides gen-  q Command Relationships. Control of RLT-7
eral guidance for preparing the CIS concept.              passes from 1st Marine Division to 2d Marine
Concept development should be closely coordi-             Division on order of CG, I MEF, on or about
nated with OPLAN/OPORD development. The                   D+2.
concept is modified and refined as necessary and
then promulgated as Annex K to the OPLAN/              q Command Relationships. Omitted.
OPORD.
                                                       b. Signal
6406. Paragraph 5 of the
OPLAN/OPORD                                            This subparagraph references Annex K, the CIS
                                                       Annex and other publications that are in effect,
The culmination of all operational planning is the     such as the CIS plan. It also includes instructions
preparation and issuance of an OPLAN or                or restrictions pertaining to radio, visual, or sound
OPORD. Information and instructions necessary          signals. For example—
to employ CIS and effect command and control
are detailed in paragraph 5, Command and Signal,       q Reference (b) (CIS plan) and Annex K (CIS
of the plan/order. As the member of the command-          Annex).
er’s general or executive staff with cognizance for
employment of CIS in support of command and            q Radio silence until lifted by this HQ.
control, the G-6/S-6 is responsible for preparing
paragraph 5. The G-6/S-6, with input from the G-       q Signal for “assault waves have landed” will be
3/S-3, will provide the draft paragraph 5 to the          green star cluster.
staff section with overall staff cognizance for the
plan (G-5 at MEF level and above and G-3/S-3 at        c. Command Posts
division/wing/FSSG level and below) or the order
(G-3/S-3). See MCWP 5-1 (draft) for discussion         This subparagraph states the locations of the issu-
on development of OPLANs/OPORD.                        ing unit’s CP, subordinate unit CPs, and CP of the
                                                       next higher unit. If an Annex K is not prepared, the
The command and signal paragraph covers sever-         CP locations of adjacent and supported units may
al subjects: CIS establishment and maintenance         also be shown to facilitate communication by mes-
instructions; CP location instructions; probable lo-   senger. In an amphibious operation, this subpara-
cations of future CPs; and command relationships.      graph may also show CPs both afloat and ashore.
CP locations and command relationships informa-        This subparagraph should be considerably short-
tion is provided by the G-3/S-3. Sections of para-     ened by referencing CP locations on the operation
graph 5 pertaining to the employment of CIS may        overlay or, if one is prepared, in Annex K. This
consist simply of the notation “no change” if the      subparagraph may also direct subordinate units to
existing CIS plan (CIS SOP and CEOI) is adequate       report the location and opening/closing times of
for the operation. It may contain only changes or      CPs. For example—
additions to an existing CIS plan/order if these are
few. In either case, the existing CIS plan must be     Command Posts
clearly referenced and available to all. Paragraph 5
will always include as subparagraphs command                    Afloat                     Ashore
relationships, signal, and CPs.                                                     (Grid Coordinates)
                                                       Unit     (Ship Designation)
a. Command Relationships                                                                10268381
                                                       RLT 4          LHA               10254387
This subparagraph shows changes in or unusual          BLT 1/4        LPD               To be reported
command relationships. If there are none, the          Co A           LSD               10264391
term “omitted” is used. For example—                   Co B           LPD               18466832
                                                       Co C           LHA

                                                       Report initial location ashore and changes in loca-
                                                       tion by priority message.


---

6-16 _______________________________________________________________________________________________ MCWP 6-22

Additional subparagraphs may or may not be in-         modify) existing CIS SOPs and CEOI and not
cluded. If used, they are lettered consecutively       promulgate redundant information. Finally, by
and may include the following information, as ap-      reference to the Annex K and/or the communica-
propriate:                                             tions plan of a senior HQ, a subordinate organiza-
                                                       tion may be able to place all necessary CIS
q Locations and times of opening/closing of C2         instructions in paragraph 5 of its OPLAN, obviat-
   facilities.                                         ing the need to prepare a separate Annex K. How-
                                                       ever, there are still instances when the plan or
q Use of CIS and equipment.                            order developed by a lower echelon should con-
q Code words and names.                                tain both paragraph 5 and a CIS Annex. For ex-
q Liaison procedures.                                  ample, when a unit is involved in a highly
q Brevity List.                                        complex operation requiring detailed CIS instruc-
                                                       tions to ensure that no salient points are omitted
6407. Annex K (CIS Annex)                              or misunderstood, such detailed instructions
                                                       should be contained in a CIS Annex.
Annex K is an amplification of the instructions
contained in paragraph 5 of the OPLAN or               Annexes to an OPLAN or OPORD are prepared
OPORD. It is a tool to coordinate the establish-       to—
ment, operation, and maintenance of CIS to sup-
port command and control. It delineates:               q Promote clarity, brevity, and simplicity within
                                                          the body of an order.
q The primary CIS missions to be accomplished
   by the organization.                                q Amplify parts of an order with data that is tech-
                                                          nical and/or limited in application to the com-
q The CIS missions to be accomplished at the or-          mand as a whole.
   ganizational HQ.
                                                       q Furnish guidance for development of a plan or
q The CIS missions assigned to subordinate units          order by a subordinate unit.
   and (internal unit staff) principle staff officers
                                                       Annex K serves all three purposes. It amplifies
q Detailed technical plans for employment of           paragraph 5 with data that is technical and, for the
   CIS.                                                most part, limited in applicability, and at the same
                                                       time eliminates the need for detailed CIS instruc-
q Administrative and logistics details related to      tions in the main body. The CIS Annex also pro-
   CIS.                                                vides guidance to communications units for the
                                                       development of their OPLANs and OPORDs. The
In formulating an OPLAN or OPORD, MEFs, di-            G-6/S-6 should begin preparation of Annex K on
visions, aircraft wings, FSSGs, and other major        the basis of the conclusions reached in the CIS es-
HQs normally find it necessary to issue a volumi-      timate developed in support of the preferred COA
nous and detailed CIS Annex. However, the an-          and in close coordination with the overall devel-
nexes developed by subordinate organizations are       opment of the OPLAN or OPORD. Detailed in-
usually less detailed. The maintenance of a stand-     structions on the preparation of Annex K and a
ing Annex K that can be tailored as necessary will     recommended format are contained in appendix J
greatly reduce the preparation time to develop a       of this manual.
comprehensive Annex K for a specific operation.
Furthermore, the Annex K should reference (or


---

Communications and Information Systems _____________________________________________________________ 6-17

Section V

Communications Control

Communications control is the method used by          Many of the communications control functions
the CISO to manage and provide positive control       supported by the communications battalions for
over the communications network and the em-           the MEF and the Marine component are per-
ployment of information systems. It involves or-      formed by the MWCS, the division and FSSG
ganizing CIS personnel to plan, direct, and           communications companies, and, at lower eche-
coordinate CIS support and controlling, engineer-     lons, communications platoons and detachments.
ing, installing, operating, and maintaining the       Likewise, many of these functions associated with
MAGTF communications network. Communica-              SCI communications are performed by the radio
tions control provides centralized control of limit-  battalions (for the MAGTF CE) or division and
ed CIS resources while allowing decentralized         wing special security communications teams.
execution for greater flexibility and responsive-
ness. Communications control is the responsibili-     6501. Phases
ty of the commander. The commander delegates
this responsibility to the CISO, the G-6/S-6. The     Communications control begins with planning for
overall MAGTF communications control effort is        an operation/exercise and continues throughout
the responsibility of the MAGTF G-6/S-6 officer.      the deployment, installation, maintenance, and re-
CISOs of subordinate organizations and units are      deployment phases.
responsible for providing communications control
of the CIS resources of their respective organiza-    a. Planning
tions and units in accordance with the overall
MAGTF communications control effort.                  This phase consists of both operational and tech-
                                                      nical planning. It culminates in the issue of a com-
At the MEF, the G-6 exercises communications          mand element OPORD and a supporting
control with the assistance of a staff that is aug-   communications unit OPORD. This phase is char-
mented by the supporting communications battal-       acterized by extensive coordination meetings be-
ion. An MCCC is organized under the direction of      tween the supporting communications unit(s) and
the G-6. The MCCC directs both internal and ex-       supported staff.
ternal communications control functions. External
communications control is coordinated with the        b. Deployment
JTF or CINC J-6 through the joint communica-
tions control center (JCCC). The functions and re-    During this phase, OPCON of the communica-
sponsibilities of the JCCC are described in           tions units and/or detachments is transferred to
CJCSM 6231.01A, Joint Tactical Systems Man-           the supported CE. The CIS plan is refined through
agement, and CJCSM 6231.07A. The MCCC also            coordination among the supporting communica-
provides communications control support to the        tions unit(s) and the supported G-6/S-6 staffs and
Marine component HQ.                                  key staff officers (e.g., the G-2/S-2 for intelli-
                                                      gence CIS requirements, the fire support coordi-
Although communications control responsibili-         nator for fires CIS requirements, etc.). Limited
ties, functions, and organization are more com-       execution is performed during this phase, includ-
plex at higher echelons of the MAGTF,                 ing tracking message traffic and operating in-tran-
communications control is exercised throughout        sit radio circuits, as required.
the MAGTF down to battalion/squadron level.


---

6-18 _______________________________________________________________________________________________ MCWP 6-22

c. Installation                                       q Planning, engineering, managing, coordinating,
                                                         and controlling the MAGTF communications
This phase begins with the ship-to-shore move-           networks, both GENSER and SCI, including
ment and reoccurs with subsequent CP and orga-           SCR, local area, and SBB networks, as well as
nizational displacements. Central coordination of        maintaining connectivity to external networks.
multiple tasks is characteristic of this phase. Par-
ticular attention is paid to maintaining communi-     q Identifying problems with the communications
cations links external to the command element.           networks and coordinating and controlling ef-
SCR links are of highest priority.                       forts to restore, reconstruct, or reroute circuits
                                                         to resolve problems.
d. Maintenance
                                                      q Frequency planning, allocation, management,
This phase occurs as terminal systems and net-           and deconfliction.
work circuits become operational. It is highlight-
ed by a shift from SCR to SBB-based systems,          q Managing COMSEC assets and monitoring
including installation and operation of LANs and         compliance with COMSEC procedures.
support of voice traffic and router and switch-
based message and data traffic over MCR links. It     q Managing, coordinating, and supervising tacti-
is important to keep the SCR installation, opera-        cal information systems employment in concert
tion, and maintenance efforts separate from ef-          with principal staff officers representing func-
forts to install backbone systems. Otherwise the         tional area users.
criticality of maintaining the SCR network can in-
terfere with efforts to install the SBB. During this  6503. Functional Areas
phase, communications planning is continual to
modify and adapt communications networks as           Communications control is divided into the func-
necessary to support maneuver and displacement.       tional areas of system planning and engineering,
                                                      SYSCON, and TECHCON.
e. Redeployment
                                                      System planning and engineering consists of de-
This phase is highlighted by coordinated efforts to   termining the CIS requirements of the organiza-
deactivate and pack up systems and equipment          tion; designing the communications networks to
and by a transition to a simpler, less capable com-   support those requirements; and promulgating
munications network while maintaining the re-         CIS plans, orders, and directives.
quired level of communications connectivity and
information transfer capability. Communications       SYSCON consists of supervising, coordinating,
support must remain effective and responsive          and controlling the overall, day-to-day operation
throughout this phase.                                of MAGTF communications networks.

6502. Responsibilities                                TECHCON consists of centralized technical su-
                                                      pervision of the installation, operation, and main-
Communications control is the method of orga-         tenance of MAGTF communications networks.
nizing communications personnel and facilities to     At the MEF and MSC level, a SYSCON staff and
provide positive control of communications. It in-    an OSCC support the SYSCON function, and a
cludes planning, organizing, directing, coordinat-    TECHCON operations staff and facility support
ing, controlling, and evaluating circuitry and        the TECHCON function. Figure 6-1 is an over-
equipment to ensure effective support of commu-       view of MEF communications control. Sections
nications requirements. As the level of command       VI through VIII discuss these three functional ar-
increases, so does the complexity of communica-       eas and the specific responsibilities and tasks as-
tions control. Communications control responsi-       sociated with performing them in support of
bilities include—                                     MAGTF tactical communications networks.


---

Communications and Information Systems _____________________________________________________________ 6-19
                                              Figure 6-1. MEF Communications Control.


---

6-20 _______________________________________________________________________________________________ MCWP 6-22

                    Section VI

System Planning and Engineering

System planning and engineering involves the           facilities, radio net structure, relay/retransmis-
technical aspects of designing the MAGTF tacti-        sion sites, frequency requirements/allocations,
cal communications networks. These networks            and alternate means of communications.
are planned, designed, and engineered to meet the   q Analyzing the need for system reconfiguration
operational requirements set by the CISO. The          and priority restructuring.
type and number of circuits required, circuit       q Prepare and issue directives on implementing
routes, frequency management, and other consid-        changes in network configuration, connectivi-
erations are evaluated to establish requirements       ty, or routing resulting from unit displacements,
for both internal and external communications.         modifications of missions, unsatisfactory sys-
System planning and engineering is performed by        tem performance, or other reasons.
each CISO in the MAGTF. The MEF G-6 is the
senior CISO and directs the overall system plan-    q Continual review of system status and perfor-
ning and engineering of CIS networks. The com-         mance of communications equipment and per-
munication battalion provides personnel to             sonnel.
support system planning and engineering at the
MEF level. The CISOs at lower echelons plan         q Planning system expansion, extension, com-
communications support for their respective orga-      pression, or reconfiguration.
nizations in accordance with the overall MEF
communications plan.                                q Prepare and update contingency plans.

6601. Functions                                     q Establishing network priorities.
                                                    q Monitoring progress of work implementation
System planning and engineering is conducted at
all echelons and includes the following functions:     and quality assurance testing.
                                                    q Coordinating frequency requests and develop-
q Prepare and disseminate general command pol-
   icies for the use of CIS within the command.        ing a frequency management plan that includes
                                                       frequency allocation for both communications
q Prepare and issue communications and infor-          and noncommunications emitters such as radar.
   mation orders, records, and reports for the use  q Maintenance of the system planning and engi-
   of CIS and equipment within the command             neering database.
   subordinate elements.                            q Prepare communications operations reports and
                                                       maintain historical data and files.
q Maintain continual contact with other staff ele-  q Inform the commander and staff of the commu-
   ments to ensure awareness of the operational        nications situation.
   environment and evolving CIS requirements        q Prepare and plan COMSEC requirements (keys,
   and coordination with the CIS staffs of other       codes, equipment, etc.) for the communications
   units in the AO.                                    networks.

q Specification of system interfaces to other-Ser-  q Coordinate the development of automated tools
   vice and joint networks and the DISN.               to enhance system planning and engineering ca-
                                                       pabilities.
q Planning and engineering of the overall config-
   uration of the command’s communications net-     6602. Responsibilities
   works, including the general locations of
   multichannel terminals, switches, gateways, ca-  The MAGTF CISO is responsible for planning the
   ble routes, and LANs and the use of host nation  SCR, local area, SBB, and special purpose system
                                                    networks. Subparagraphs a–c address specific


---

Communications and Information Systems _____________________________________________________________ 6-21

system planning and engineering responsibilities      est usable frequency, and the frequency of
with respect to each of the communications net-       optimum transmission for skywave propagation.
works. Responsibilities for LANs are included un-     The MAGTF frequency manager must then re-
der the SBB.                                          quest frequency assignments from the area fre-
                                                      quency coordinator. The power requirement and
a. SCR                                                range for groundwave propagation are also re-
                                                      sponsibilities of the frequency manager. Addi-
Planning SCR operations is the responsibility of      tionally, the MAGTF CISO is responsible for
CISOs at all MAGTF levels. Each level can em-         identifying required COMSEC keys.
ploy a specific radio differently; however, interop-
erability and interference require consideration of   b. Switched Backbone
factors such as frequency selection, cryptographic
equipment, communications protocols, and fre-         (1) Switching Systems. The MAGTF CISO is
quency separation. SCR nets used by the MAGTF         responsible for the detailed planning of the
are described in appendix D.                          MAGTF SBB on the basis of user requirements.
                                                      Each MSC CISO determines user requirements
(1) VHF and UHF Frequency Hopping Radio               from within the command and forwards this infor-
                                                      mation to the MAGTF CISO. On the basis of this
Networks. These networks include the SINC-            information, the MAGTF CISO designs the net-
GARS and HAVE QUICK radio systems. Both of            work by establishing the trunking requirements
these systems employ frequency hopping tech-          from the MAGTF CE to each MSC and between
niques. The set of frequencies, or hopset, to be      the MSCs. From this design, each MSC CISO
used is planned and allocated by the MAGTF fre-       completes the detailed planning for the MSC
quency manager. The MAGTF CISO assigns a              switching system, including trunking to subordi-
unique net identifier to each net within the          nate units, trunking between subordinate units,
MAGTF. Current policy is for the net identifier to    and loop termination assignments. The MAGTF
be permanently assigned in the MAGTF master           CISO prepares and distributes the network timing
net list. The MAGTF CISO identifies the               plan to the subordinate units, indicating the mas-
MAGTF COMSEC keys for each net.                       ter timing source for the network. From this over-
                                                      all plan, the unit CISO develops the internal site
(2) Satellite Systems. The AN/PSC-5 is a sin-         timing plans. The MAGTF CISO identifies the
gle-channel UHF satellite radio system used for       COMSEC keys for the MAGTF switched net-
communication both within and external to the         work and identifies the COMSEC and alternate
MAGTF. The area NCTAMS performs the link              COMSEC parent circuit switches.
performance calculations, plans the uplink and
downlink frequencies, and provides the satellite      (a) AN/TTC-42. The MEF employs AN/TTC-42
location information for antenna pointing calcula-    circuit switches at the MEF CE and at each MSC
tions. When the radio is employed within the          HQ. The MAGTF CISO, after consulting with the
MAGTF, the MAGTF CISO identifies the COM-             GBNP, determines the numbering scheme to be
SEC key to be used. If the radio is employed to       used and develops the circuit switch numbering
communicate outside the MAGTF (JTF, other             plan. The MAGTF CISO also assigns telephone
Services, and agencies), the higher HQ is respon-     numbers and publishes the information systems
sible for security planning.                          directory (app. E). The interswitch trunking as-
                                                      signments and interoffice and interarea routing
(3) HF Systems. Factors for HF communica-             schemes are also the responsibility of the
tions interface planning include terminal selec-      MAGTF CISO. Unit CISOs are responsible for
tion, data rate selection, and operational mode.      configuring their switches to meet network design
These are the responsibility of the MAGTF CISO.       requirements and for providing subscriber ser-
The MAGTF frequency manager is responsible            vice. Unit CISOs are also responsible for report-
for the propagation prediction. This includes cal-    ing their local plans and operational problems to
culating the maximum usable frequency, the low-


---

the MAGTF CISO. The MAGTF CISO deter-                 MSCs. Circuits that run from each MSC HQ to its
mines the priority for restoration of service.        subordinate units are the responsibility of the
                                                      MSC CISO. If the MAGTF uses external means
(b) SB-3865. The SB-3865 circuit switch is used       to communicate outside of the MAGTF (JTF, oth-
throughout the MAGTF, within each MSC, and at         er Services, and agencies), the planning require-
subordinate units. It has operating characteristics   ments are coordinated with the higher HQ. The
similar to the AN/TTC-42. Therefore, the plan-        following transmission systems employment con-
ning requirements, with minor exceptions, are the     siderations provide some understanding of the CI-
same as for the AN/TTC-42. The MAGTF CISO             SO’s responsibilities.
determines the priority for restoration of service.
No planning is involved in selecting the number       (a) CX-4566, 26-Pair Cable. CX-4566 is used to
format because the SB-3865 accepts only the tac-      extend the distance of subscriber terminal equip-
tical numbering format (4/3).                         ment from assemblages and switches and to per-
                                                      form the function of a link concentrator when used
(c) AN/MSC-63A. The AN/MSC-63A communica-             with a J-1077 junction box.
tions central is employed as a message switch at
the MAGTF’s CE and major subordinate ele-             (b) CX-11230, Coaxial Cable. The CX-11230 pro-
ments. Connectivity for the AN/MSC-63A is             vides the connectivity between switches, switches
planned at two levels: the MAGTF CE level and         and transmission systems, and data terminals.
the MSC level. When employing the AN/MSC-
63A, users must plan for communications connec-       (c) Fiber-Optic Cable System. The fiber-optic ca-
tivity because the AN/MSC-63A does not have           ble system provides the connectivity from the
organic communications equipment. If GENSER           switch equipment to the transmission equipment
and/or SCI communities are to be served, the us-      or between switches.
ers, inter-Service requirements, and security re-
quirements must be identified.                        (d) AN/MRC-142. The AN/MRC-142 is a UHF
                                                      transmission system employed by each MSC
(d) IP Routers. The Marine Corps employs IP           within the MAGTF. This system provides critical
routers to provide a data communications capabil-     line-of-sight communications from the MAGTF
ity over the SBB and to interface with the SIPR-      CE to the HQs of subordinate commands, between
NET, NIPRNET, and JWICS. The MAGTF CISO               MSC HQs, and within each MSC. The AN/MRC-
also has overall responsibility for network securi-   142 baseband configuration is planned by the
ty on the SIPRNET. The MAGTF CISO                     MAGTF CISO with input from the MSC CISO.
coordinates with MSC CISOs to ensure router           Profiling and frequency planning between the CE
connectivity throughout the MAGTF. Communi-           and MSCs and between MSCs are accomplished
cations and special communications units at the       by the MAGTF CISO. Systems internal to an
MAGTF CE and MSCs are responsible for the in-         MSC are profiled by the MSC CISO. Site selec-
stallation, operation, and maintenance of the         tion and antenna elevation are the responsibility of
MAGTF secure and nonsecure data networks. Af-         the CISO employing the equipment and are based
ter the networks are operational, the communica-      on the profile of the system.
tions unit monitors the network for activity,
reliability, and security. Any detected security vi-  (e) AN/TRC-170. The AN/TRC-170 radio terminal
olations are reported immediately to the unit CI-     set is used for line-of-sight or troposcatter com-
SO and the unit security manager. See appendix        munications by the MEF CE, each MSC within
M for an example of an IP network diagram.            the MEF, and between elements of the ACE. The
                                                      MAGTF CISO, with input from the MSC CISOs,
(2) Transmission Systems. The MAGTF CISO              coordinates baseband configuration and profiling
is responsible for planning the systems for trans-    of the AN/TRC-170s between the CE and MSCs
mission from the CE to the MSCs and between           and between MSCs. The MAGTF CISO is


---

Communications and Information Systems _____________________________________________________________ 6-23

responsible for the frequency planning for the        tions forces. The CISOs at each echelon plan for
AN/TRC-170 systems.                                   the employment of the AN/TSC-120 and are re-
                                                      sponsible for the proper employment of the sys-
(f) AN/TSC-85B and AN/TSC-93B. T h e s e t e r m i -  tem, including terminal equipment selection, data
nals provide entry into the GMF satellite system      rate selection, and mode of operation. The CISOs
and the DISN gateway. The MAGTF CISO plans            also submit communication guard shifts to ensure
for employing the AN/TSC-85B satellite terminal       system entry into the Naval Telecommunications
at the CE. At the MSC locations, the MSC CISO         System and DISN.
plans for employing the AN/TSC-93B. The base-
band configurations of the AN/TSC-85B and AN/         When employing this system, the MAGTF CISO
TSC-93B are planned by the MAGTF CISO in co-          and frequency manager must confirm the avail-
ordination with the MSC CISOs. The MAGTF CI-          ability and allocation of multiple frequencies nec-
SO submits a satellite access request to the          essary for effective operation and circuit
Regional Space Support Center in CONUS, Eu-           reliability. Calculation of skywave propagation
rope, or the Pacific for entry to the GMF satellite   parameters is also required. In addition, power re-
system. The Regional Space Support Center will        quirements and range for groundwave propagation
produce and provide a satellite engineering plan      employment must be considered. The area
that includes the path, link analysis, uplink and     NCTAMS performs the link performance calcula-
downlink frequencies, azimuth and elevation for       tions for the AN/PSC-5 employed with the TSC-
the antenna, and satellite assignments. The results   120, plans the uplink and downlink frequencies,
are sent to the MAGTF CISO and then to the            and provides the satellite location information for
MSCs for employment of the GMF equipment.             antenna pointing calculations. The MAGTF CISO
                                                      is responsible for planning power requirements,
(g) AN/TSC-96A. The AN/TSC-96A is a UHF sat-          range, and message throughput and wait times for
ellite communications system designed to work         VHF-AM meteor burst employment. When the
with the Fleet Satellite Communications (FLT-         AN/TSC-120 is employed within the MAGTF, the
SATCOM) network. It is employed down to the           MAGTF CISO identifies the COMSEC key to be
MSC level within the MEF. The baseband config-        used. If it is employed to communicate outside the
uration of the AN/TSC-96A is planned by CISOs         MAGTF (JTF, other Services, and agencies), the
of the MSC. Because this is a satellite system, the   higher HQ is responsible for security planning.
link performance calculations, uplink and down-
link frequencies, and the antenna pointing calcula-   (3) Special-Purpose Systems
tions are planned by the NCTAMS servicing the
AO. A communications information bulletin is          (a) PLRS. The PLRS is a ground-based radio-navi-
published by the area NCTAMS. The communica-          gation system. Employment of PLRS is the joint
tions information bulletin provides the satellite     responsibility of the GCE operations and CIS of-
coverage of the area, base frequencies for reestab-   ficers and the MAGTF CISO. The GCE opera-
lishment of links, and the types of information       tions officer is responsible for operational
transmitted over each satellite channel. There is a   planning, including basic user unit equipment dis-
communications information bulletin published         tribution, group access, message set access, and
for each operational area of the world. MEF and       navigational aids (zone, corridor, and line bound-
MSC CISOs should request copies of the commu-         aries and predetermined items). The MAGTF CI-
nications information bulletin before they deploy.    SO is responsible for planning the initial locations
The COMSEC keys to be used with this system           of the PLRS master station and alternate master
are planned by the parent agency of the system.       station. The GCE operations officer determines
                                                      the organizations that will provide the necessary
(h) AN/TSC-120. The AN/TSC-120 is employed at         6–10 reference units and coordinates with the CI-
the MEF and MSC HQs and provides internal and         SO for their initial locations. The MAGTF CISO
external communications. It can operate with both     is responsible for planning reference units and
U.S. and NATO conventional and special opera-         coordinates with the GCE CISO for their initial


---

6-24 _______________________________________________________________________________________________ MCWP 6-22

locations. The MAGTF CISO is responsible for          ating force. The tactical situation will determine
planning reference and relay unit locations to en-    its exact location. However, in making this deter-
sure complete PLRS coverage. The MAGTF fre-           mination, the commander should consider the
quency manager provides the net frequency             scheme of maneuver, security requirements, EPL-
allocation and a single-channel VHF frequency         RS network requirements, and electromagnetic in-
for the PLRS engineering net. In the event that       terference. The reference community can be based
more than one PLRS network is operated, the           on a mix of fixed reference sites and radio sets
MAGTF frequency manager plans for additional          with Global Positioning System Interface Units
frequency allocations for the additional networks.    (GPSIUs). The GPSIU allows the employment of
                                                      a mobile, more versatile reference community,
(b) EPLRS. EPLRS employment requires detailed         vice fixed reference units which must be surveyed,
planning so that it can support the operational       by connecting an organic AN/PSN-11 PLGR to ei-
scheme of maneuver. All predetermined EPLRS           ther an EPLRS radio set or PLRS BUU. A single
data communications needlines must be planned         EPLRS/PLRS community will be deployed with
and established prior to mission execution. Con-      one NCS-E(D) and up to 460 active radio sets.
tinuous coordination between the operations offi-
cer and communication-electronics officer of op-      During ship-to-shore movements, the Marine
erational headquarters throughout the MAGTF is        Corps EPLRS network can be integrated with the
necessary for effective employment of EPLRS.          U.S. Navy’s Amphibious Assault Direction Sys-
EPLRS network planning with consideration for         tem (AN/KSQ-1). (Net Control Stations are being
TDN, DACT, TCO, AFATDS, and SINCGARS,                 installed on all LHAs and LHDs as part of this sys-
and the cryptological key management plan are         tem.) The AN/KSQ-1 is designed to monitor and
key mission planning factors. Additionally, for       control naval surface landing craft—LCUs and
joint operations, coordination with Army EPLRS        LCACs—as well as “inject” PLI generated by
planners, Air Force Situation Awareness Data          these craft into the Joint Maritime Command In-
Link (SADL) planners, and Navy AN/KSQ-1               formation System (JMCIS) Track Database Man-
planners may be necessary.                            ager (TDBM) for building the common
                                                      operational picture. Airborne or terrestrial plat-
During operations ashore, EPLRS will serve as         forms equipped with EPLRS can provide “over-
the primary data radio set for TDN connectivity       the-horizon” communications, dependent upon
below the regimental level, as well as providing      the mission and platform availability. In order to
data communications requirements for task orga-       capitalize on EPLRS communication and PLI ca-
nizations below the battalion level. The network      pabilities, extensive coordination and planning
can be generated and established by an NCS-E(D)       must be done in order to establish and manage the
or a PC, dependent upon the particular mission.       data needlines for Marine and Navy use.
(The PC-based capability, currently under devel-
opment, will be used for rapid communications         (c) JTIDS. JTIDS is an airspace C2 support sys-
network initialization, and generation of initial-    tem. The TAOC and the TACC are the only
ization and cryptographic keys to support garrison    Marine Corps C2 facilities to be equipped with
and field exercises, EPLRS radio set training, and    JTIDS. The ACE CISO is responsible for plan-
host system training. This precludes deployment       ning implementation of the JTIDS terminals lo-
of an NCS-E(D) to support limited training envi-      cated within the ACE. The ACE CISO requests
ronments and small operational deployments            the required frequencies and time slots from the
which do not require an automated PLI capability,     MAGTF CISO, who forwards the request to the
but do require EPLRS data communications capa-        JTF J-6. The MAGTF CISO is also responsible
bilities.)                                            for identifying COMSEC key requirements. The
                                                      JTF J-6 assigns the frequencies to be included in
If EPLRS and PLRS are also employed for PLI,          the frequency allocation and the time slots for op-
the NCS-E(D) is required and will be located in       eration in the network. The ACE CISO coordi-
the vicinity of the senior headquarters of the oper-  nates with the ACE operations officer to


---

Communications and Information Systems _____________________________________________________________ 6-25

determine the locations of the JTIDS modules as-        tion with analysts from Radio Battalion, can re-
sociated with the TAOC and TACC.                        ceive live SIGINT information being collected in
                                                        the forward area. This capability enables analysts
(d) GPS. The GPS is a passive system, and there         to train and maintain their readiness in collection
are no communications networks for the MAGTF            management, technical control, and system super-
CISO to coordinate. However, the MAGTF CISO             vision, as well as SIGINT production and data
must ensure that satellite coverage is available in     base maintenance.
the AO. This information is found in the satellite
almanac published by the U.S. Air Force Space           The executive authority for Trojan Spirit is the
Command. The data in the almanac includes the           U.S. Army Intelligence and Security Command
number of satellites covering the AO, the actual        (INSCOM) at Fort Belvoir, VA; management is
number of satellites operating, and the times the       provided by the U.S. Army Technical Control and
satellites are overhead. The GPS satellite almanac      Analysis Element (TCAE) at Fort Meade, MD.
data is also transmitted automatically to GPS re-       Use and management of the Trojan Spirit system
ceivers from the GPS satellite constellation.           is exercised at Fort McPherson, GA. Trojan Spirit
                                                        services are extended to the I, II, and III MEFs.
(e) Trojan Spirit II. Each day, a portion of the radio
electronic spectrum is captured by selected SIG-        In addition to supporting the counter-drug mis-
INT collection facilities overseas and relayed via      sion, language training, an essential element of
the Trojan Spirit intelligence support system to        the intelligence training program, is a secondary
CONUS-based analysts for further exploitation.          purpose of the system. The command provides se-
Trojan Spirit (fig. 6-2) is a unique transmission ca-   cure facilities and communications with intelli-
pability designed to forward tactical SIGINT to         gence staff oversight and INSCOM technical
CONUS-based elements for analysis. Operating            control for the training of SIGINT skills, tasks,
at the SCI/TK level, the Trojan Spirit system is        and processing of assigned units under TCAE op-
fielded and operational in the MEFs. Operators at       erational control.
the Intelligence Company of the MEF, in conjunc-

Figure 6-2. Trojan Spirit.


---

6-26 _______________________________________________________________________________________________ MCWP 6-22

The Trojan Spirit system consists of four major el-       6603. Automated Tools
ements: the remote collection equipment in the
forward area, transmission systems that carry the         Several automated planning and engineering tools
actual transmission to CONUS, central switching           are available to support system planning and engi-
facilities at Fort Belvoir that route traffic to specif-  neering.
ic processing sites, and the garrison central operat-
ing facility.                                             a. SPEED

A basic Trojan Spirit system consists of four col-        SPEED is a team-transportable, fully integrated,
lection positions, four listening posts, a system su-     microcomputer-based system that supports
pervisor’s console, and system-associated                 MAGTF tactical communications planning to the
communications equipment. An upgraded capa-               regimental/group level. SPEED is used in con-
bility includes enhanced signal distribution inter-       junction with a random data generator and a data
connecting control and digital data switching. The        transfer device. SPEED should have other pro-
tactical field monitor sub-component of the Trojan        grams which provide the following capabilities:
Spirit system is designated the AN/TSQ-144(V)2.
This equipment can remotely control receivers at          q Point-to-point analysis.
unmanned collection sites. From the collection            q High-frequency analysis.
site, secure communications links are established         q Guard chart application.
using tactical military equipment such as SHF/            q Signal/noise and signal/interference analysis.
GMF terminals employing the DSCS, most often a            q Area coverage analysis.
combination of U.S. military-owned/-leased com-           q Topographic database.
mercial connectivity using satellite and terrestrial      q Database of basic equipment characteristics.
systems.                                                  q RBECS software programs for CEOI/signal

Although Trojan Spirit is oriented toward CONUS              operating instructions generation.
garrison operations, the system has tactical appli-       q Tactical Network Analysis and Planning Sys-
cations, as was proven during Operations Desert
Shield/Desert Storm. The Army realized that it               tem Plus (TNAPS+) software.
had a robust wide-band communications asset that          q Switched Network Automated Planner soft-
could be used to support tactical operations. Dur-
ing Operation Restore Hope, using Trojan Spirit to           ware.
support split-based operations reduced the number
of intelligence personnel required to deploy.             b. Revised Battlefield Electronic CEOI
                                                          System
Future TS IIs will provide MEFs with both C- and
Ku-band satellite communications; planned field-          RBECS application software was designed to pro-
ing will remain at two systems per MEF. The HM-           vide the user with an enhanced CEOI and frequen-
MWVs are currently configured with a primary              cy hopping data generation capability. RBECS is
Trojan shelter on one vehicle and a spare equip-          one of the applications resident on SPEED termi-
ment shelter on the other. Both vehicles have un-         nals. There are two application modules within
der-the-hood and tunnel-mounted electrical power          RBECS: Signal operating instructions/CEOI and
generating capabilities. The space between the            Revised SINCGARS Integrated Communications
HMMWV cab and the shelter contains the tunnel-            Security Module, Nonintegrated Communica-
mounted generator. The system also has a mobile           tions Security Module Support Software (RSI-
antenna platform trailer.                                 NISS). Signal operating instructions/CEOI
                                                          provide the user with the capability to build, gen-
                                                          erate, edit, and print CEOI locally for training or
                                                          operations. CEOI generation requires an AN/
                                                          CSZ-9 random data generator and is conducted at
                                                          the MEF, MSC, and MEU CE levels.


---

Communications and Information Systems _____________________________________________________________ 6-27

c. Revised SINCGARS Integrated                      Software has two application modules: signal op-
Communications Security Module,                     erating instructions and radio. Signal operating in-
Nonintegrated Communications                        structions can receive, store, find, display, and
Security Module Support Software                    transfer CEOI data. Radio can receive, store, edit,
                                                    and transfer frequency hopping data. Radio can
This application of the RBECS was designed to       also generate, receive, store, and transfer COM-
generate, store, edit, and transfer SINCGARS fre-   SEC keys.
quency hopping data. RSINISS can download fre-
quency hopping data from a PC into a DTD by         g. ARC-210 Fill Program
using RS-232 cable or to a floppy disk for dissem-
ination to subordinate, adjacent, or supporting     The ARC-210 Fill Program is a software applica-
units. RSINISS requires a random data generator     tion located on the SPEED platform. The ARC-
to generate unique transmission security keys.      210 Fill Program is used to enter and organize the
Transmission security keys are generated at the     various types of data required to fill an AN/ARC-
MEF, MSC, and MEU CE levels.                        210 radio: single-channel frequencies and related
                                                    data and HAVE QUICK and SINCGARS fre-
d. AN/CSZ-9 Random Data Generator                   quency hopping data. This data allows the radio to
                                                    operate in either single-frequency or frequency
The random data generator performs two basic        hopping modes with compatible radios.
functions. It randomizes the allocated frequencies
into daily changing frequencies and assigns daily   h. Consolidated SCR EP Package
changing call signs for the CEOI application. It
generates a unique pseudo random transmission       The Consolidated SCR EP Package is a software
security key for RSINISS use when creating load-    application that may be loaded into the DTD. The
sets.                                               Consolidated SCR EP Package allows the DTD to
                                                    receive frequency hopping data from RSINISS
e. AN/CYZ-10 DTD                                    and COMSEC keys from common fill devices.
                                                    The Consolidated SCR EP Package application
The DTD is a weather-resistant, electronic data     consists of two functions: detailed management
storage and transfer device procured by the Na-     and quick fill. The detailed management function
tional Security Agency loaded with RBECS DTD        offers transmit, receive, database, and setup func-
Software. The DTD is cargo-pocket size, weighs      tions. The quick fill function transfers frequency
1.5 pounds, and requires three 3-volt batteries or  hopping data from the DTD to a SINCGARS or
one 9-volt battery. DTD’s primary function is to    AN/ARC-210.
serve as a common fill device to load COMSEC
keys into any Marine Corps cryptographic equip-     i. TNAPS
ment. It is the planned replacement for the TSEC/
KYK-13 and the TSEC/KYX-15. The DTD can             TNAPS is a computer-based desktop system plan-
receive, store, and transfer frequency hopping da-  ning and SYSCON tool that assists the planner in
ta between DTDs or PCs. The DTD can also re-        building an exercise or operation database and in
ceive, store, display, and edit CEOI information    producing a series of output reports describing the
and transfer one time period of CEOI information    resulting networks and equipment configurations.
over the air by using a SINCGARS radio. The         The system controller can use this database with
DTD is also referred to as the Automated Net        program support to monitor and manage in-place
Control Device (ANCD) in many U.S. Army             communications. TNAPS allows tactical commu-
technical and operation manuals.                    nications planning and control at two levels: the
                                                    network level and nodal/equipment level. Net-
f. Revised Battlefield Electronic CEOI              work planners and controllers are responsible for
System DTD Software                                 planning and managing the overall network. Nod-
                                                    al planners and controllers plan and manage a
This is the software application used by the Army   complete database for equipment within the node
and Marine Corps in the DTD. RBECS DTD


---

6-28 _______________________________________________________________________________________________ MCWP 6-22

and generate all necessary worksheets and crew  q Subscriber database control.
assignment sheets. Some of the functions of     q SYSCON.
TNAPS are—
                                                j. Switched Network Automated
q Exercise of database control.                 Planner
q Site configuration and inventory control.
q Circuit/message switch graphics and network   The Switched Network Automated Planner is
                                                used to plan and engineer switched communica-
   development.                                 tions networks. Through a series of user selec-
q Transmission graphics and network develop-    tions and inputs and software routines, the
                                                Switched Network Automated Planner assists in
   ment.                                        planning and engineering a network and provides
q COMSEC database control.                      physical and database configuration data for
q Report generation.                            ULCS equipment.


---

Communications and Information Systems _____________________________________________________________ 6-29

Section VII

SYSCON

The primary purpose of SYSCON is to ensure op-       q Achieve speed and grade-of-service goals in the
timum use of all available circuits to meet the re-     network under normal and stress conditions.
quirements of the commander. SYSCON is the
responsibility of the supporting communications      q Determine satellite/transponder usage and mon-
unit. The SYSCON function includes two types of         itor the channels for occupancy to determine
activity: staff direction of MAGTF communica-           whether a reallocation of channels is necessary.
tions network configurations and day-to-day man-
agement of the operating communications              q Provide circuit switch, message switch, and
networks. These functions are accomplished by           router programming needed to establish and
the SYSCON staff and the OSCC watchstanders,            update subscribers and route traffic.
respectively. The SYSCON staff supervises OS-
CC activities and compiles statistics and reports    q Develop, monitor, and load key variables into
for use in long-range planning. The OSCC mean-          encryption devices.
while directs day-to-day operations of the commu-
nications networks within the MEF. The               q Collect and analyze traffic data, service com-
communications battalion provides the SYSCON            plaints, and outage reports to identify and correct
staff and mans the MEF OSCC. At the MSC level,          system inadequacies, procedural deficiencies,
the supporting communications unit(s) provide the       and other problems and provide the analyses to
same functions. At lower echelons, SYSCON               system planning and engineering. Make recom-
functions are less complex and are performed by         mendations to system planning and engineering
personnel of the communications unit without es-        for corrective actions when the resources avail-
tablishment of an OSCC.                                 able to SYSCON are insufficient to provide sat-
                                                        isfactory communications service.
6701. Functions
                                                     q Prepare and distribute information essential to
The SYSCON functions performed by the SY-               using and operating the system, such as tele-
SCON staff and the OSCC are—                            phone directories, network addresses, and call
                                                        signs.
q Prepare and issue detailed directives and in-
   structions to subordinate communications units    q Maintain system records and historical data and
   for implementaion of CIS plans and supervis-         submit reports as required.
   ing the execution of the plans.
                                                     q Direct and receive circuit information from the
q Monitor system performance and coordinate             local TECHCON operations center.
   actions required for restoration of system out-
   ages, including coordinatoin with senior, sub-    6702. Staff Responsibilities
   ordinate, and adjacent OSCCs.
                                                     Communications, as a function of the command,
q Generate and disseminate frequency assign-         are the ultimate responsibility of the commander.
   ments and monitor and control frequency usage.    The CISO and the supporting communications
                                                     unit operations officer act as agents of the com-
q Maintain the transmission quality on all trans-    mander. For example, the MEF communications
   mission links.                                    battalion operations officer may provide direction
                                                     to the division communications company opera-
q Adjust communications resources to compen-         tions officer. However, the division communica-
   sate for disruptions or destruction of the com-   tions company operations officer is ultimately
   munications system by the enemy.                  responsible to the division commander and serves
                                                     as the agent of the division commander to express


---

6-30 _______________________________________________________________________________________________ MCWP 6-22

the division communications requirements to the      ficers coordinate with adjacent units to resolve
MEF.                                                 problems. Subordinate communications unit oper-
                                                     ations officers are responsible for providing peri-
At each echelon, the communications unit opera-      odic status reports to the next higher echelon. The
tions officer has been delegated the management      MAGTF CISO is kept informed of the MAGTF
and control responsibility necessary to direct the   communications network status by the MAGTF
operation of the communications systems and net-     communications unit operations officer. Subordi-
works. At the MAGTF CE, the communications           nate communications unit operations officers are
unit operations officer is responsible for the com-  responsible for reporting problems that cannot be
munications links connecting the CE to the subor-    solved at their level to the next higher communi-
dinate HQ. Directives from the MAGTF CISO are        cations unit operations officer.
distributed down to each subordinate communica-
tions unit operations officer. The MAGTF com-        c. Special Purpose Systems
munications unit operations officer periodically
monitors the status of each link of the MAGTF        Direction, management, and control responsibili-
communications networks, including equipment         ties for special purpose systems consist primarily
status. Reports from subordinate communications      of reporting equipment status and outages. Status
unit operations officers are consolidated by the     reporting for these systems is the same as de-
MAGTF communications unit operations officer.        scribed above for the switched backbone. Outage
Each subordinate communications unit operations      reports are sent to the external supporting organi-
officer monitors the equipment and network status    zations for these networks through the MAGTF
within the command and reports the status to the     CISO. Planning to circumvent outages is coordi-
MAGTF communications unit operations officer.        nated with the communications unit operations
For systems between adjacent subordinate HQs         officer. The communications unit operations of-
(e.g., GCE to ACE), the MAGTF CISO designates        ficer coordinates with the appropriate network or-
one of the subordinate communications unit oper-     ganizations for access according to local SOP
ations officers to control the link.                 guidelines.

a. SCR                                               The MAGTF communications unit operations of-
                                                     ficer is responsible for directing, managing, and
Each subordinate communications unit operations      controling the PLRS (EPLRS). The MAGTF
officer or commander monitors the status of SCR      communications unit operations officer directs the
nets and provides periodic status reports to the     activities of the PLRS (EPLRS) master station op-
next higher command communications unit oper-        erators in implementing OPLANs and plan
ations officer. If an MSC communications unit        changes. The PLRS (EPLRS) master station oper-
operations officer is notified of a COMSEC or        ators are responsible for the PLRS TECHCON
TRANSEC compromise, the MAGTF CISO is in-            functions. The MAGTF communications unit op-
formed. Each subordinate communications unit         erations officer monitors the PLRS (EPLRS) net-
operations officer informs the next higher com-      work to check for full area coverage. If the area
munications unit operations officer of any inter-    coverage is insufficient, the MAGTF communica-
ference problems that require additional             tions unit operations officer notifies the MAGTF
frequency planning for HF, VHF, UHF, and             CISO. PLRS (EPLRS) employment must be inte-
UHF-SATCOM nets.                                     grated into the commander’s scheme of maneuver
                                                     and support execution. This means that the net-
b. Switched Backbone                                 work must be flexible and able to adapt to change
                                                     as it occurs during all phases of planning and op-
Each subordinate communications unit operations      erations.
officer is responsible for directing the implemen-
tation of the SBB network according to plans de-     The MWCS operations officer is responsible for
veloped or approved by the MAGTF CISO. The           the SYSCON of the JTIDS. The MWCS
subordinate communications unit operations of-


---

Communications and Information Systems _____________________________________________________________ 6-31

operations officer receives system status reports      control procedures. The OSCC reports problems
from the wing OSCC and reports system failures,        that cannot be resolved at that level to the respec-
frequency interference problems, and ground sta-       tive communications unit operations officer. The
tion movements to the wing CISO.                       OSCC is also responsible for directing the loading
                                                       of the proper COMSEC keys into the equipment
The MAGTF communications unit operations of-           and ensuring proper operation. The OSCC com-
ficer needs to ensure that the appropriate COM-        piles the statistics of the switched network and re-
SEC variables are distributed so that encrypted        ports them to the communications unit operations
positioning signals can be properly received. The      officer.
MAGTF CISO monitors almanac conditions, co-
ordinates appropriate adjustments, and forwards        c. Special Purpose Systems
information messages to GPS users. System out-
ages are reported to U.S. Air Force Space Com-         The primary functions of each OSCC are to direct
mand.                                                  the installation of the systems, maintain the equip-
                                                       ment status, and report equipment outages to the
6703. OSCC Responsibilities                            communications unit operations officer. Security
                                                       management is also the responsibility of the OS-
The OSCC directs the day-to-day operation of           CC. The OSCC provides COMSEC keys and en-
communications networks.                               sures proper operation.

a. SCR                                                 The majority of PLRS (EPLRS) OSCC duties,
                                                       such as monitoring reference units and coordinat-
The OSCC directs the implementation of the SCR         ing with multiple network PLRS (EPLRS) master
nets, including coordination with the unit opera-      station operators, must be done at the master sta-
tions section for the operation of the net control     tion location. The PLRS (EPLRS) master station
station. The OSCC also maintains the COMSEC            operator is responsible for fulfilling the duties of
and TRANSEC keys, the word of the day, and the         the OSCC. The master station operators are re-
net frequency allocation for each net. The TECH-       sponsible for reporting the status of the network
CON of the tactical radio nets, including trouble-     to the MAGTF communications unit operations
shooting, is directed by the OSCC. To combat           officer. They also provide the COMSEC keys to
interference or to limit the amount of traffic on a    the necessary personnel. The master station oper-
net, the OSCC and the operations officer may de-       ators continually monitor the units that are active
cide in favor of time sharing of nets or directed      users of the PLRS (EPLRS). Units moving out of
net operations. The OSCC periodically reports the      the area of coverage are reported to the communi-
tactical radio net status to the communications        cations unit operations officer for action. Master
unit operations officer.                               station operators are also responsible for verifying
                                                       the map, control, and coordination data that ap-
b. Switched Backbone                                   pears on the monitors.

The OSCC maintains the equipment status of each        The ACE OSCC directs the JTIDS installation,
system. The OSCC also monitors the circuit             operation, and maintenance; provides the COM-
switched network statistics to insure that system      SEC key to the JTIDS operators; and coordinates
availability, call blocking, and the switch traffic    the movement of the JTIDS ground stations. The
load are within acceptable tolerances. The OSCC        OSCC provides system status, frequency interfer-
directs the installation of the switch network to in-  ence, and ground station movement reports to the
clude fault isolation, restoration, and reconfigura-   communications unit operations officer.
tion, as necessary. The OSCC institutes
preauthorized changes in the switched network          The MEF OSCC distributes COMSEC keys and
such as routing table changes, zone restrictions, al-  information messages to GPS users.
ternate routing, database changes, or traffic load


---

6-32 _______________________________________________________________________________________________ MCWP 6-22

Section VIII

TECHCON

TECHCON is the means of exercising centralized        6802. Responsibilities
technical supervision over the installation, opera-
tion, and maintenance of the circuits and systems     The current generation of digital switching and
employed by the MAGTF. The installation of each       transmission equipment has been designed with
system is controlled by a TECHCON facility. This      inherent TECHCON capability. Because many of
includes both the systems that interface directly     the component systems that make up the commu-
with the facility and those that do not. The OSCC     nications networks are physically isolated from
watch officer directs the activities of the TECH-     one another, responsibility for the TECHCON of
CON operations staff. The TECHCON operations          the communications networks involves the com-
staff supervises the installation, operation, and     bined and coordinated effort of each operator, su-
maintenance activities of the direct support, gener-  pervisor, and maintainer in each part of the
al support, and service companies and/or their de-    system.
tachments. The capabilities of these units are
organized around platoons and sections into cen-      a. SCR
ters such as radio, wire, multichannel, and data
communications central; the TECHCON facility;         The responsibility for TECHCON of MAGTF
the communications center; and the maintenance        tactical radio nets lies with the net control station
facilities. TECHCON operations staff oversees         equipment operators and the local communica-
and directs the activities of all these centers.      tions organization. For frequency hopping radio
                                                      nets to operate properly, each radio in the net
6801. Functions                                       must maintain an accurate time-of-day clock. The
                                                      net control station maintains time of day and pro-
TECHCON functions are—                                vides it to the users of the net. The equipment op-
                                                      erators are responsible for maintaining
q Exercise technical coordination between ele-        synchronization within the network and correct-
   ments of the MAGTF tactical communications         ing as necessary. Troubleshooting tactical radio
   network.                                           nets is the responsibility of the local communica-
                                                      tions organization. The local communications or-
q Exercise technical supervision over subordinate     ganization also determines the separation and
   technical control facilities                       placement of antennas to minimize electromag-
                                                      netic interference. The OSCCs direct equipment
q Restore disrupted service.                          operators on the power setting that will allow
q Perform quality checks and exercise technical       them to operate in the net without using an excess
                                                      amount of power.
   direction, coordination, and supervision on sys-
   tem testing.                                       b. Switched Backbone
q Coordinate system activation, deactivation,
   and/or reconfiguration.                            The TECHCON for the SBB is accomplished by
q Report system and circuit status to the appro-      the operators and supervisors of the switch and
   priate control facility.                           transmission equipment, as well as by dedicated
                                                      TECHCON personnel. The switch and transmis-
q Record status of transmission links, trunks,        sion equipment operators are responsible for
   channels, and circuits as required by local SOP.   installing the individual circuits in the switched
                                                      network and for monitoring the equipment


---

Communications and Information Systems _____________________________________________________________ 6-33

alarms. It is also the responsibility of the equip-    to connected equipment; condition circuits; and
ment operators to monitor the synchronization of       perform analog/digital, 2-wire/4-wire, and signal-
the switched network. When circuit or system           ing conversions. It contains the monitoring, test-
outages occur, the operators are responsible for       ing, and patching equipment required by technical
notifying the OSCC and implementing proce-             controllers to troubleshoot and restore faulty cir-
dures for fault isolation and restoring the lost ser-  cuits and links. Equipment is contained in an S-
vice. If necessary, they reconfigure the circuits or   280 shelter and will be transported by a dedicated
systems under the direction of the OSCC. Equip-        5-ton truck. A total of 31 systems are planned for
ment and circuit outages are reported to OSCC by       fielding to the FMF.
the operators. Equipment operators are also re-
sponsible for monitoring and adjusting circuits        c. Special Purpose Systems
that require alignment, such as analog voice and
data circuits. The operators are also responsible      Because the special purpose systems are separate
for monitoring the status of each circuit and sys-     from the other systems within the MAGTF, the
tem and periodically reporting this status to the      TECHCON is accomplished by the equipment op-
OSCC. In addition, there may be dedicated cir-         erators. The operators monitor the status of the
cuits installed that use the transmission systems      transmission and subscriber equipment. Reports
but do not access the switched network. The            of system status and outages are sent to the OSCC.
TECHCON for these circuits may be accom-
plished by using portable TECHCON facilities           The PLRS (EPLRS) master station operators are
that do not interface with other systems.              responsible for the TECHCON duties. These re-
                                                       sponsibilities have been discussed in the day-to-
The current TECHCON facility is the AN/TSQ-            day OSCC responsibilities.
84, an analog facility with limited capabilities.
The digital technical control (DTC) is replacing       The JTIDS operators at the TAOC and TACC
the AN/TSQ-84. The DTC provides the FMF with           perform the TECHCON functions for the JTIDS
a deployable, digital technical control capability     system. The JTIDS operators install and restore
to replace the AN/TSQ-84. The DTC facilitates          the JTIDS system under the direction of the ACE
the installation, operation, restoration, and man-     OSCC and report equipment outages and periodic
agement of individual circuits and digital links       system status to the ACE OSCC.
consisting of many multiplexed circuits. It pro-
vides the primary interface between subscriber         The MAGTF G-6 staff monitors almanac condi-
systems/networks within a local area and long          tions and coordinates appropriate adjustments and
haul multi-channel transmission systems to trans-      information messages to GPS users. System out-
port voice, message, data, and imagery traffic. It     ages are reported to U.S. Air Force Space Com-
can add, drop, and insert digital circuits into mul-   mand.
tiplexed groups; provide a source of stable timing

                                                       (reverse blank)


---

                    Chapter 7

Information Systems Security

MAGTF command and control relies on the confi-        vice to unauthorized users, including those
dentiality, availability, and integrity of tactical   measures necessary to detect, document, and
communications networks and information sys-          counter such threats.
tems. Protecting these systems from exploitation,
disruption, or destruction is of highest priority.    As with other forms of security, the first step in
                                                      providing effective INFOSEC is understanding
The threat to MAGTF CIS comes from a variety          the threat. This includes identifying threat objec-
of sources and continues to evolve. This threat       tives, capabilities, and techniques as well as
ranges from conventional EW/SIGINT tech-              friendly vulnerabilities.
niques to newer forms such as computer intrusions
by hackers; drug traffickers; foreign intelligence    The threat’s overall capability to conduct C2 war-
agencies; disaffected, disgruntled, or disloyal per-  fare on the battlefield and information warfare in
sonnel; and, potentially, battlefield adversaries.    the strategic arena affects the way the MAGTF
Intruders have repeatedly demonstrated their abili-   must defend its information systems.
ty to penetrate military information systems. With
the increasing interconnection of information sys-    At the strategic level, DISA is responding to the
tems, such attacks threaten the entire DII as well    threat with a defensive information warfare strate-
as the tactical communications networks and in-       gy based on protecting the infrastructure and data,
formation systems that interface with and use that    detecting attacks, reacting promptly to attacks,
infrastructure.                                       and maintaining service. On the battlefield, the
                                                      MAGTF is responding to the threat through a
INFOSEC is the protection of information sys-         similar C2 protection strategy.
tems against unauthorized access to or modifica-
tion of information, whether in storage,              This chapter focuses on two key security disci-
processing, or transit, and against denial of ser-    plines: COMSEC and computer security (COM-
vice to authorized users or the provision of ser-     PUSEC).

Section I

Communications Security

COMSEC is the protection resulting from all           tions from enemy exploitation while ensuring un-
measures designed to deny unauthorized persons        impeded use of the electromagnetic spectrum.
information of value that might be derived from       The organization must be able to employ commu-
the possession and study of telecommunications        nications equipment effectively in the face of ene-
or to mislead unauthorized persons in their inter-    my efforts. COMSEC is an integral part of
pretation of the results of such possession and       electronic protection—the element of EW that fo-
study. COMSEC includes physical, cryptograph-         cuses on protection of our capabilities. COMSEC
ic, transmission, and emission security. The goal     requirements must be integrated into communica-
of COMSEC is to protect friendly communica-           tions systems planning and must focus on provid-


---

7-2 ________________________________________________________________________________________________ MCWP 6-22

ing secure communications without impairing         q Supervising the COMSEC Material System
reliability or responsiveness. Modern communi-         (CMS) custodian in the execution of his duties
cations equipment includes features such as inte-      and responsibilities for control and account-
grated encryption capability and frequency             ability over classified CMS material and equip-
hopping capability, which contribute to communi-       ment, including distribution and destruction of
cations protection. However, the security of our       COMSEC material in accordance with current
communications depends on the proper operation         directives.
of communications equipment and adherence to
proper procedures.                                  q Ordering COMSEC material and equipment for
                                                       operations and exercises.
7101. Responsibilities
                                                    q Developing, in coordination with the unit secu-
COMSEC is a command responsibility. It is also         rity manager, emergency destruction plans for
the responsibility of each individual user of com-     COMSEC materials and equipment.
munications. The G-6/S-6 is responsible to the
commander for the overall planning, supervision,    b. G-2/S-2
and coordination of COMSEC matters, including       q Advising and assisting the communications in-
the administrative, day-to-day management of
COMSEC material. Specific staff responsibilities       formation systems officer on electronic protec-
include:                                               tion techniques based on analysis of enemy
                                                       SIGINT and EW capabilities and other threats
a. G-6/S-6                                             to unit CIS and operations.

q Incorporating COMSEC requirements into the        c. G-3/S-3
   communications plan.                             q Integrating communications information sys-

q Supervising communications to ensure proper          tems protection, including COMSEC and elec-
   equipment operation and use of COMSEC pro-          tronic protection, into the concept of operation
   cedures.                                            in accordance with the commander’s guidance.
                                                    q Planning and supervising the physical protec-
q Training communications personnel in COM-            tion of essential communications nodes.
   SEC and electronic protection techniques.        q Planning and supervising the overall EW effort
                                                       in coordination with the G-2/S-2 and the G-6/
q Promoting awareness of the enemy EW threat           S-6.
   among all members of the command.
                                                    d. MEF COMSEC Management Office
q Advising and assisting the unit security manag-   q Providing and sourcing MEF units with mis-
   er, G-2/S-2, and G-3/S-3 in matters regarding
   CIS and electronic security and protection.         sion essential contingency COMSEC material.
                                                    q Establishing CMS policy within the MEF.
q Preparing an emission control (EMCON) plan        q Deploying as a MEF COMSEC Management
   to include employment of alternate communi-
   cations means.                                      Office (MCMO) in support of the MEF or de-
                                                       ploys and/or supports a Joint COMSEC Man-
q Advising and assisting the G-3/S-3 in matters        agement Office for a Joint Headquarters.
   regarding the command’s operations security
   and deception plan.                              e. Command Security Manager
                                                    q Serving as the commanding officer’s advisor
q Instructing all users on proper operation of
   communications systems and equipment and            and direct representative in matters pertaining
   proper communications procedures.                   to the security of classified information and
                                                       personnel security.
q Coordinating with the G-2/S-2 and G-3/S-3 for
   conducting COMSEC monitoring and analysis
   operations.


---

Communications and Information Systems _______________________________________________________________ 7-3

q Developing written command information and         be used, for example, to modify a bit stream to
   personnel security procedures, including an       send over a communications network. If the re-
   emergency plan which integrates emergency         ceiver of the bit stream has access to the seed used
   destruction bills where required.                 by the sender, the modified bit stream can be de-
                                                     coded. The bit stream may consist of data, or it
q Ensuring that threats to security, compromises     may be digitized voice. With this approach to en-
   and other security violations are reported, re-   cryption, it is not necessary for the equipment it-
   corded and, when necessary, investigated vig-     self to be highly classified as was the case with
   orously. Ensures incidents falling under the      World War II era encryption equipment. It is only
   investigative jurisdiction of the NCIS are im-    losing the seed number, or key, that will compro-
   mediately referred to the nearest NCIS office.    mise the encrypted information. Therefore, the
                                                     management and control of keying material is of
For a complete list of all Security Manager duties/  utmost concern. Commanders should limit the
requirements refer to OPNAVINST 5510.1H.             holdings of keying material to the minimum re-
                                                     quired for operations. This material must be trans-
7102. Cryptosecurity                                 ported, stored, safeguarded, destroyed, and
                                                     accounted for in strict accordance with existing
Cryptosecurity is the COMSEC component that          regulations.
results from the provision of technically sound
cryptosystems and their proper use. With the         7103. Transmission Security
built-in encryption feature of SINCGARS and the
widespread availability of encryption equipment      Transmission security (TRANSEC) is that com-
for other SCRs and the SBB, it should be possible    ponent of COMSEC that results from all mea-
to cover all tactical communications. Accom-         sures designed to protect transmissions from
plishing COMSEC requires detailed planning that      interception and exploitation by means other than
is conducted as an integral part of the overall      cryptoanalysis. The Marine Corps’ goal is to se-
communications planning effort. The require-         cure all tactical communications circuits and SCR
ments for encryption must be determined and the      nets. However, even encrypted communications
appropriate equipment and material must be ob-       may be targeted, exploited, and disrupted by an
tained to support those requirements. CJCSM          enemy’s intelligence and EW organizations via
6231.05 provides detailed COMSEC information         traffic analysis, direction finding, and jamming.
for TRI-TAC equipment and is a key reference in      TRANSEC is an important component of the unit
planning the SBB. Units must act immediately         electronic protection effort.
upon receipt of a COMSEC callout message to
obtain the required cryptographic material to be     a. SCR
employed in a particular exercise or operation to
include, when designated, the intertheater COM-      Strict radio discipline and adherence to authorized
SEC package. In the future, the joint key manage-    procedures are key to ensuring TRANSEC over
ment system, which is under development, will        SCR networks. Operating SINCGARS radios in a
enable the electronic distribution of keys through-  frequency hopping mode provides maximum pro-
out the JTF.                                         tection against enemy EW capabilities. Other
                                                     TRANSEC measures include:
Modern cryptographic systems use random num-
ber generators to accomplish encryption. By ini-     q Training operators thoroughly on proper com-
tializing the random number generator with a seed       munications procedures and equipment opera-
number, a deterministic sequence of pseudoran-          tion. (This includes all Marines that may
dom numbers is generated. Each time the same            operate SCR, not just CIS personnel.)
seed is used, the same sequence of numbers is
generated. The pseudorandom numbers may then         q Avoiding unauthorized transmission and test-
                                                        ing and maximizing use of data networks to


---

7-4 ________________________________________________________________________________________________ MCWP 6-22

   minimize transmission time and opportunity        that can reduce the vulnerability of MCR to ene-
   for enemy direction finding.                      my EW.

q Using transmitter, antenna, and power combi-       In addition to encryption and measures to reduce
   nations that produce minimum wave propaga-        the probability of interception, traffic flow securi-
   tion and emission intensity consistent with       ty is required. Traffic flow security conceals the
   reliable communications.                          presence of messages on communications cir-
                                                     cuits. Traffic flow security is normally achieved
q Strictly adhering strictly to authorized frequen-  on the SBB by using trunk encryption devices to
   cies.                                             generate a continuous stream of bits, making the
                                                     circuit appear busy at all times.
q Using authentication systems to protect against
   imitative deception on nonsecure nets.            7104. Emission Security

q Using changing call signs and frequencies on       Emission security (TEMPEST) is the component
   nonsecure nets.                                   of COMSEC that results from all measures taken
                                                     to deny unauthorized persons information of val-
q Promptly responding to and reporting enemy         ue that might be derived from interception and
   jamming. (Operators should continue to oper-      analysis of compromising emanations from
   ate on assigned frequencies in a secure mode,     crypto equipment and telecommunications sys-
   unless otherwise directed by a competent au-      tems. The operation of communications and infor-
   thority, and should attempt to work through the   mation systems may result in unintentional
   interference.)                                    electromagnetic emissions. Although tactical
                                                     equipment is designed to reduce the possibility of
q Strictly adhering to all EMCON restrictions        such emissions, COTS equipment is not. Uninten-
   and observance of radio silence.                  tional emissions are extremely susceptible to in-
                                                     terception and analysis and may disclose
q Using communications means that do not radi-       classified information. Commanders must follow
   ate in the electromagnetic spectrum such as       applicable regulations providing guidance on con-
   messengers, visual and sound signaling, and lo-   trol and suppression of such emissions.
   cal wire loops.
                                                     7105. Physical Security
q Using terrain masking to shield transmission
   systems from enemy EW systems.                    Physical security is the COMSEC component that
                                                     results from all physical measures necessary to
q Remoting transmitters and avoiding the cluster-    safeguard classified equipment, material, and doc-
   ing of antennas.                                  uments from access or observation by unautho-
                                                     rized persons. The access to classified
b. Multichannel Radio and Wire                       cryptographic information must be tightly con-
                                                     trolled. When a commander or designated repre-
Information is often compromised by the assump-      sentative has determined that an individual has a
tion that wire is secure. While wire is inherently   need to know and is eligible for access, then ac-
more secure than radio, the SBB normally uses        cess to classified cryptographic information will
MCR to move traffic beyond the local geographic      be formally authorized. The authorization process
area. Furthermore, when a wire infrastructure is     must include an introduction to the unique nature
used over an extended area, the line can be          of cryptographic information, its unusual sensitiv-
tapped. Sensitive traffic, voice or data, should be  ity, the special security regulations governing its
either sent over covered circuits or encrypted pri-
or to transmission over nonsecure circuits. MCR
operation in close proximity to the enemy is of
concern because the high power of transmission
equipment and continuous mode of operation are
easily detectable and could potentially reveal the
location of units and CPs. Use of terrain masking
and, where possible, limiting forward and back
lobe emission into enemy territory are measures


---

Communications and Information Systems _______________________________________________________________ 7-5

handling and protection, and the penalties pre-       casual viewing by uncleared personnel, whether
scribed for its disclosure. In the event of a viola-  by accident or as the result of operational necessi-
tion of physical security, a report is required.      ty, does not constitute a reportable violation.
Reportable violations include:
                                                      Personnel planning for and setting up the SBB
q Loss of material.                                   must be aware of the requirement for red/black
q Unauthorized viewing.                               isolation. This refers to the separation of circuits,
q Capture of individuals having access to COM-        systems, equipment, and areas that handle classi-
                                                      fied plain text (red) information in electronic sig-
   SEC information.                                   nal form from those that handle unclassified
                                                      (black) information in electronic signal form.
Currently fielded COMSEC equipment is unclas-         (Black signals include encrypted signals because
sified for external viewing when appropriate cov-     these signals would not divulge national security
ers are in place and no keying material is visible.   information if recovered and analyzed.)
Consequently, the exposure of such equipment to


---

7-6 ________________________________________________________________________________________________ MCWP 6-22

        Section II

Computer Security

Command and control on the modern battlefield        sensitive information. Access to this information
depends increasingly on information systems. The     provides the enemy insight into MAGTF, joint,
amount of data that is processed and the tempo of    and national capabilities; force and resource loca-
operations combine to make manual procedures         tions; plans and intentions; readiness status; and
inadequate except at the small unit level. Even at   knowledge of what is known about the enemy.
the small unit level, automated systems are prolif-  This type of information, when discovered and
erating, particularly in the fire support area. The  used to advantage, has often been the deciding fac-
increasing dependence on tactical information        tor in the outcome of battle. In today’s environ-
systems drives the requirement to protect these      ment, this type of information is surprisingly easy
systems from disruption or exploitation by hostile   to obtain. For example, careless e-mail exchanges
forces. In much the same way that COMSEC pro-        with family and friends can reveal planned
vides the security for information transferred       MAGTF movements and operations. E-mail is
through communications systems, COMPUSEC             easily and readily collected by enemy agents.
provides the security for information that is col-
lected, stored, processed, and displayed by com-     b. Information Modification
puters and peripheral equipment at user locations.
                                                     Another objective of attacks on our information
7201. The Threat                                     systems is information modification. Such infor-
                                                     mation corruption can be used to create an elec-
With the openess of the Internet, intruders can in-  tronic deception. Undetected, it can lead to
flict damage on information systems from virtual-    incorrect assumptions and subsequent faulty deci-
ly any location with little fear of detection.       sions. In other instances, the attack may be de-
Today’s information systems are connected into       signed to destroy information required to execute
worldwide communications networks that are           the MAGTF planning and decision cycles. In ei-
only as secure as the weakest link. The enemy can    ther case, detection of the attack can severely re-
easily gain access to much of the same informa-      duce confidence in the MAGTF’s information
tion infrastructure used by the MAGTF. Intruders     systems. The MAGTF’s ability to observe, orient,
do not require sophisticated technology. A non-      decide, and act more quickly than the enemy de-
technical means, such as a compromised pass-         pends greatly on the information provided by the
word, can bypass LAN security features. Once         information systems used. Reduced confidence,
access is gained, the attacker can employ mali-      induced time delays, and undetected, faulty infor-
cious logic to inflict tremendous damage on our      mation can all severely degrade the commander’s
information systems. (Malicious logic is comput-     ability to make sound and timely decisions.
er code designed to deny, destroy, modify, or im-
pede system configurations, programs, data files,    c. Denial of Service
or routines. Types of malicious logic include vi-
ruses, Trojan horses, logic or time bombs, and       Still another objective of enemy attacks on our in-
worms.) The enemy will have several objectives       formation systems is either total or partial restric-
in attacking MAGTF information systems.              tion of our ability to process, retrieve, and
                                                     disseminate information. Data corruption results
a. Information Compromise                            in lost confidence and service self-denial. Suc-
                                                     cessful enemy attacks on stored data, applica-
A major goal of threat attacks on MAGTF infor-       tions, or operating systems may render
mation systems is to gain access to classified or    information systems unusable. Damage or physi-
                                                     cal destruction to equipment, facilities, and per-


---

Communications and Information Systems _______________________________________________________________ 7-7

sonnel will be a high priority for the enemy          b. Management
because our communications information systems
capabilities are viewed as critical vulnerabilities   The CISO provides overall COMPUSEC manage-
and key targets. Such attacks may range from ter-     ment through policies, directives, plans, and train-
rorist truck bombings to more technologically ad-     ing. The CISO guides LAN managers,
vanced enemies using directed energy weapons.         information systems coordinators, and informa-
The environment is also a potential disruptive        tion systems users in implementing procedures
force. Information systems, particularly COTS         necessary to maintain reliable and secure informa-
systems, are very susceptible to power surges;        tion systems. Much of the security for informa-
temperature extremes; and dusty, dirty, and sandy     tion systems is provided at the individual
conditions encountered in the austere littoral areas  workstation through operating systems and appli-
in which the MAGTF operates.                          cation-specific access mechanisms. However, for
                                                      networked applications and services, a well-de-
7202. Protection                                      vised network security plan is necessary to man-
                                                      age the various accesses and privileges that
Protection of MAGTF information systems is es-        control read and write access to files and data.
sential. COMPUSEC is the means of providing           Monitoring the network is required to document
that protection. This includes knowledge of the       activity and detect intruders. COMPUSEC proce-
threat and employment of operating procedures,        dures must be integrated with and complement the
equipment, and personnel training to counter that     overall communications information systems plan
threat. COMPUSEC also includes putting into           to ensure responsive service to authorized users
place measures to detect intrusion early and plan-    while protecting against unauthorized access.
ning for immediate action to counter attacks, and,
if necessary restore lost data and service.           c. Implementation

a. Responsibilities                                   DOD Directive 5200.28 establishes mandatory,
                                                      minimum standards for automated information
COMPUSEC is a command responsibility and              systems. It promotes using computer-based secu-
must be understood and practiced by all MAGTF         rity features that emphasize the personal responsi-
informations systems users. However, overall net-     bility of system users. Current procedures rely on
work and information systems security responsi-       standalone workstations and system high net-
bility belongs to the CISO. This includes             works, which require dedicated routers and
establishing policy and procedures for LAN,           switches, making system security management
WAN, and information systems management.              difficult. There are many ongoing programs to
Procedures are required to manage user identifica-    provide improved security services for individual
tion and passwords assignment, to provide authen-     workstations, LANs, and the overall DII. Multi-
tication, and to maintain visibility and control of   level Information Systems Security Initiative
the operation and use of network services. The CI-    products and services are being fielded incremen-
SO coordinates network management functions,          tally as technology matures. They include—
including security, with the individual LAN man-
agers and information systems coordinators.           (1) Cryptographic Cards. PC-configured cryp-
Training and education in threat capabilities and     tographic cards are gradually being introduced to
COMPUSEC procedures are CISO’s responsibili-          provide different levels of personal security pro-
ty, supported by the unit security manager, G-2/S-    tection, including confidentiality, data integrity,
2, G-3/S-3, and in coordination with all LAN man-     identification/authentication, and nonrepudiation.
agers and functional information systems coordi-
nators.                                               (2) Firewalls. Firewalls protect MAGTF net-
                                                      works from outside networks such as the Internet.
                                                      Firewalls with Fortezza identification and authen-
                                                      tication allow Fortezza card-holders controlled ac-
                                                      cess to the NIPRNET from outside networks. This


---

7-8 ________________________________________________________________________________________________ MCWP 6-22

capability prevents unauthorized access to the sen-    information. This allows the transmission of clas-
sitive but unclassified information on the NIPR-       sified data on unclassified networks or SCI data on
NET while providing convenient access for              secret networks. In-line network encryptors,
authorized users.                                      through software configuration and appropriate
                                                       keying material, are used to link multiple sites.
(3) High Assurance Guards. H i g h a s s u r a n c e
guards, such as the secure network server with         (5) Security Management Services. S e c u r i t y
standard mail guard, are used to protect against       management services include security measures
unauthorized release of classified information         such as cryptographic keying, access control, au-
from a classified facility while allowing the re-      thentication, and the use of passwords. These ser-
lease of unclassified information. High assurance      vices are needed to implement effective
means that the guard has been verified by the Na-      information systems security programs within the
tional Security Agency to be highly resistant to       MAGTF. Key security management services in-
penetration based on the application of rigorous       clude—
security software engineering methods, extensive
penetration testing, and security analysis during      q Local authority workstations that reside on the
its development, production, and fielding. The            LAN and provide security capabilities such as
guard is required for information processing and          digital signatures, cryptographic keys, and ac-
exchange between facilities or systems operating          cess control permissions.
at different levels. The guard also ensures that ex-
ternal requests for access to the “guarded” higher     q Rekey managers that work in conjunction with
security level locations are approved before al-          electronic key management systems to provide
lowing that access.                                       cryptographic rekey support for Multilevel In-
                                                          formation Systems Security Initiative products.
(4) In-Line Network Encryptor. In-line network
encryptors provide data confidentiality and integ-     q Audit managers that provide support for the
rity across LANs and WANs. They employ en-                collection and analysis of security-relevant
cryption and access control through cryptographic         events that can be audited and are associated
key management. Some in-line network encryp-              with Multilevel Information Systems Security
tors can also provide traffic flow security services.     Initiative products. Repeated failed user login
In-line network encryptors operate with IP routers,       is an example of a security-relevant event that
packet switches, synchronous optical networks,            can be audited.
and asynchronous transfer mode networks. Some
of the in-line network encryptors offer combina-       q Directories that provide a repository for public
tions of these capabilities to allow for the future       security information essential for effective glo-
growth of networks based on synchronous optical           bal message addressing. The public part of a
network and asynchronous transfer mode technol-           user’s digital signature is an example of this
ogies. A key feature of in-line network encryptors        type of public security information.
is that they encrypt only the data, not the address
                                                       q Mail list agents that are used by messaging sys-
                                                          tems to add security for messages that are sent
                                                          to many recipients.


---

Communications and Information Systems _______________________________________________________________ 7-9

        Section III

Incident Response

Effective response to attacks on MAGTF infor-       tion systems security and computer security prob-
mation systems requires that all users and support  lems. This help desk receives calls 24 hours daily
personnel be aware of attack indicators and the     and is manned a minimum of 8 hours per day,
procedures to be followed in the event of an at-    Monday through Friday. Emergency calls are re-
tack. The Marine Corps Command Center (MC-          ceived via cellular phone when the help desk is
CC) and the Network Operations Center (NOC)         not manned. Services include—
will exchange information in the event of an IN-
FOSEC incident. The MCCC will act as the com-       q Security policy interpretation.
munications link between the NOC and                q Installation, configuration, support, and train-
Headquarters Marine Corps throughout the inci-
dent. The NOC has the overall responsibility of        ing for implementation of network security
managing any computer intrusion incidents in the       products:
Marine Corps.
                                                       • Internet firewalls.
7301. The Fleet Information                            • Standard mail guard.
Warfare Center                                         • Secure network server.
                                                       • Fortezza cards.
The Fleet Information Warfare Center is the Na-        • Packet filters and routers.
vy’s principal agent for development of informa-       • UNIX host security.
tion warfare and command and control warfare
tactics, procedures, and training. The center de-   q Additional guidance is provided on—
ploys personnel trained in command and control         • The Multilevel Information Systems Securi-
protection and is equipped with appropriate infor-        ty Initiative.
mation systems security equipment to support           • Protected distribution systems.
battle group and JTF operations. It is responsible     • Secure systems and Tempest certifications.
for providing computer incident response teams         • Cryptographic/COMSEC equipment.
and is the single point of contact for monitoring      • Secure voice systems.
the security of information systems. All computer      • The Navy Key Management System.
incidents (break-in attempts and malicious logic)      • Secure telemetry and communications.
are reported to the center. The center publishes       • Computer and network security tools.
advisories containing the latest information on        • Risk assessment and vulnerability surveys.
system vulnerabilities and effective countermea-       • Destruction, purging, or recovery of sensi-
sures. These advisories are received from the cen-        tive data.
ter’s computer incident response team by the           • Computer systems accreditation and certifi-
Marine Corps Network Operations Center and                cation.
disseminated to all Marine Corps commands.             • Controlled access.
                                                       • Distribution of naval computer security pub-
7302. Naval INFOSEC Help Desk                             lications.
                                                       • Training courses.
The information systems security help desk at Na-      • Other naval INFOSEC resources.
val In-Service Engineering Activity on the East
Coast provides expert assistance with all informa-


---

7-10 _______________________________________________________________________________________________ MCWP 6-22

7303. The Air Force Information                        vulnerabilities and effective countermeasures.
Warfare Center                                         These advisories are received by the Marine
                                                       Corps Network Operations Center and dissemi-
The Air Force Information Warfare Center devel-        nated to all Marine Corps commands.
ops, maintains, and deploys command and control
warfare capabilities in support of operations, cam-    7304. Points of Contact
paign planning, acquisition, and testing. The cen-
ter acts as the single focal point for command and     Appendix N provides points of contact, including
control warfare services and provides technical        telephone numbers, WWW uniform resource lo-
expertise for computer security and COMSEC.            cators (URLs), and e-mail addresses, for INFOS-
The Air Force computer emergency response              EC and other key organizations. Appendix P
team is part of the center and is responsible for re-  includes a list of reference documents. This infor-
porting and handling computer security incidents       mation should be verified and incorporated into
and vulnerabilities. The center publishes adviso-      command and control plans and SOPs.
ries containing the latest information on system


---

         Chapter 8

Future Directions

The Marine Corps implementation of command            In OMFTS, the MAGTF operates as part of a na-
and control is based on a maneuver warfare phi-       val expeditionary force in the conduct of a joint
losophy. Effective support of maneuver warfare        campaign.The primary focus of OMFTS is to al-
demands a flexible command and control system         low a sea-based MAGTF to decisively engage en-
that can support rapid decisionmaking and execu-      emy forces and accomplish naval and joint
tion to create and maintain a high tempo of opera-    objectives. New technologies and capabilities in
tions. CIS and equipment are the means through        amphibious operations will allow the MAGTF to
which effective command and control support is        engage the enemy from positions of advantage
provided. These systems must be as robust, flexi-     and to penetrate to the heart of an enemy system,
ble, and expeditionary as the MAGTF they sup-         destroying his ability and will to resist effectively.
port. They are employed across the full spectrum
of operations, from humanitarian assistance oper-     OMFTS may allow the MAGTF to act as an en-
ations to general war. They support the MAGTF         abling force, allowing the introduction of larger
whether forward deployed or in garrison.              land-based forces to commence sustained opera-
                                                      tions ashore; as a decisive force, where the
Most importantly, MAGTF CIS must be equally           MAGTF operates to achieve the decisive cam-
capable of supporting all expeditionary operations    paign objectives of a joint force commander; or as
conducted by the Marine Corps—operational ma-         an exploitation force that takes advantage of op-
neuver from the sea (OMFTS), sustained opera-         portunities created by other elements of the joint
tions ashore, and military operations other than      force. The transition to sustained operations
war (MOOTW). This chapter focuses on OMFTS,           ashore (SOA) or other expeditionary operations
the concept by which naval forces will project        (OEO), and the decision to base all or some of the
power ashore in the 21st century. As the com-         MAGTF ashore for long periods will depend on
mand and control doctrine and organizations           the situation and assigned missions. OMFTS is
evolve to meet the requirements of OMFTS,             based on two key implementing concepts—ship-
MAGTF CIS and equipment must evolve as well.          to-objective maneuver (STOM) and seabasing.
This chapter provides a framework for under-
standing the unique considerations in the employ-     a. Ship-to-Objective Maneuver
ment of CIS to support OMFTS.
                                                      The implementing concept of STOM combines
8001. Operational Maneuver from                       the ship-to-shore movement with subsequent op-
the Sea                                               erations ashore into a single, decisive maneuver
                                                      directly from the ship. STOM generates operating
The underlying operational concept for all            tempo by avoiding a pause to build up combat
MAGTF operations is OMFTS. This concept is            power ashore. Full exploitation of this concept
the application of the principles of maneuver war-    hinges on fielding the advanced amphibious as-
fare to naval forces at the operational level. While  sault vehicle (AAAV) and the MV-22 to transport
not every MAGTF operation is an OMFTS, the            the surface assault and the vertical assault, re-
maneuver warfare principles associated with it        spectively. However, through skillful use of
provide the basis for all Marine Corps operations.    available platforms, STOM is possible today, al-
                                                      though on a somewhat restricted scale. Figure 8-1
                                                      (on page 8-2) depicts the STOM concept.


---

8-2 ________________________________________________________________________________________________ MCWP 6-22

Figure 8-1. The STOM Concept.

b. Seabasing                                         8002. CIS Requirements

Seabasing is another important implementing          OMFTS provides a means of projecting naval ex-
concept for executing OMFTS. Seabasing envi-         peditionary power directly against an exposed en-
sions bringing ashore only those MAGTF ele-          emy center of gravity (COG) or critical
ments that must be ashore to accomplish their        vulnerability. However, the execution of OMFTS
mission. Most fire support, command and control,     poses a number of C2 challenges, particularly
and logistic functions remain at sea throughout      with respect to CIS support. Perhaps the most ob-
the operation. Most aviation support remains sea-    vious challenge is how to provide secure, reliable,
based. While some or all GCE C2 transitions          high-capacity communications links over extend-
ashore, the overall command and control of the       ed distances, perhaps as much as 200 miles, from
MAGTF, centralized in the MAGTF CE, normal-          the ships of the ATF to rapidly maneuvering sur-
ly stays afloat. Seabasing offers tremendous oper-   face and vertical assault elements ashore. For
ational freedom of action to the MAGTF.              longer distances, innovative solutions and new us-
Retaining command and control, aviation, fires,      es for existing equipment must be pursued. Satel-
and logistics afloat reduces the need to establish   lite communications (SATCOM) offers the best
and then protect shore-based facilities while si-    near term solution. Airborne/ground-based high
multaneously enhancing the MAGTF’s force pro-        capability, multichannel relay sites; long range,
tection posture. This translates into increased      high capacity single channel systems; and secure
operating tempo and reduced requirements for         global cellular and phone networks are just some
rear area security. The reduced infrastructure       of the intriguing possibilities to provide ship-to-
ashore also facilitates the rapid reembarkation and  objective communications.
redeployment of the landing force.


---

Communications and Information Systems __________________________________________________ 8-3

In the near-term, several interim fixes are being     face or airborne, may be required for effective
pursued, including the possible employment of         PLRS operation. Future systems will exploit PL-
the MRC-142 with appropriately modified anten-        RS, GPS and other navigation systems, linked to
nas to enable shipboard operation providing con-      communication and information systems, to pro-
nectivity at ranges of up to 40 miles. For longer     vide an accurate, real time COP throughout the
distances, SATCOM appears to be the only cur-         MAGTF and Navy force.
rently available option. Although the numbers of
SATCOM terminals currently available are rela-        To conduct OMFTS, the MAGTF must have the
tively limited, this situation is improving with the  ability to employ its information systems effec-
fielding of the AN/PSC 5. However, obtaining the      tively while at sea. This is an area in which signif-
SATCOM access required to provide the commu-          icant improvements are rapidly occurring. Both
nications connectivity needed for command and         tactical combat operations (TCO) and intelligence
control of a MEF is problematic because of com-       analysis system (IAS) are routinely deployed
petition with other elements of the ATF, the naval    aboard amphibious ships, and connectivity is be-
expeditionary force, and the JTF. Before and dur-     ing provided to the JMCIS LAN. However, pres-
ing the early phases of the ship-to-shore move-       ently these installations are occurring on an ad
ment, ultrahigh frequency (UHF) tactical              hoc basis, and the installation varies from ship to
satellites (TACSATs) with high frequency (HF)         ship even within the same class. It is therefore
single channel radios (SCR) as backup is the pre-     critical that the command and control officer be-
dominant means of long-haul communications.           gin planning early to ensure not only adequate
                                                      numbers of workstations, but also, just as impor-
Once established ashore, MAGTF forward ele-           tantly, adequate LAN connectivity. Workstations
ments may use ground mobile forces (GMF)              dedicated to MAGTF LAN connectivity are re-
TACSAT. As previously discussed, employment           quired in all landing force command and control
of high-capacity, multichannel transmission sys-      and administrative work spaces in all ships of the
tems and establishment of the switched backbone       amphibious ready group, not just in the LFOC
come at some expense in terms of maneuverabili-       aboard the flagship. Future seabased MAGTF fa-
ty. Tradeoffs will demand careful analysis. Future    cilities will require CIS connectivity that is as ef-
systems should seek to overcome these limita-         fective throughout the battle space as that for
tions.                                                shore based facilities. In other words, whether
                                                      seabased or shore-based, CIS capabilities and
Another key ingredient for successful OMFTS is        availability should be transparent to users in fu-
the provision of real-time COP throughout the         ture command naval control and administrative
ATF and the landing force. OMFTS depends on           facilities.
free maneuver of both the surface assault and the
vertical assault elements to exploit the developing   Full implementation of OMFTS will place strin-
situation and to avoid obstacles and strongpoints.    gent demands on the command and control capa-
The only way that we can maneuver freely while        bilities of the MAGTF. The MAGTF will exercise
simultaneously providing responsive supporting        command and control both ashore and afloat over
fires is through continuous, real-time knowledge      greatly extended distances. Furthermore, the
of friendly and enemy locations. Presently, this      MAGTF will depend on increasing amounts of in-
position location information (PLI) is available      formation to plan operations, deploy and sustain
through the PLRS system installed aboard the          its forces, and execute its missions. Effective in-
LHD class of amphibious ships and can be dis-         formation management will be critical for fo-
seminated throughout the ATF by JMCIS. Ship-          cused, efficient command and control.
board coverage of landing force maneuver              Information systems must provide a common pic-
elements must be maintained until the landing         ture of the battlefield and shared situational
force brings a master station ashore. Depending       awareness throughout the battlespace. Communi-
on the distances involved, relay units, either sur-   cations systems must provide a robust voice and


---

8-4 ________________________________________________________________________________________________ MCWP 6-22

data communications capability throughout the        and information systems support to a follow-on
battlespace and connectivity to information re-      forces commander.
sources throughout the world.
                                                     As a final note, MAGTF operational concepts are
The CIS discussed in chapters 3, 4, and 5 will pro-  undergoing rapid and dramatic change, not unlike
vide many of these capabilities in the near future.  the field of information technology. MAGTF
This includes the migration of tactical informa-     communications and information systems person-
tion systems to the GCCS and the fielding of in-     nel must adapt the command and control system
ternet protocol (IP) router and IDNX-based           to support these evolving concepts. This will be
gateways and servers. Continual improvements in      done through exploitation of information technol-
the packaging of tactical information systems will   ogy and the continued refinement of proven com-
result in smaller, more maneuverable operations      mand and control doctrine. The ultimate goal is to
centers and CPs. Another significant develop-        enhance the commander’s command and control
ment is the JTF enabler, which will allow a          capabilities—providing the necessary informa-
MEU(SOC) to provide initial communications           tion at the right place and time for effective plan-
                                                     ning, decisionmaking, and execution.


---

Communications and Information Systems __________________________________________________ 8-5


---

                                 Appendix A

       Defense Information Infrastructure
Common Operating Environment Compliance

The concept of a common operating environment       software will run when loaded on a COE platform
(COE) is the most significant part of the Global    and whether it will interfere with other segments.
Command and Control System (GCCS) develop-
ment effort. The DII COE encompasses the archi-     Category 2, Style Guide
tecture, standards, and reusable software modules   Category 2 measures how well the proposed soft-
that provide a cohesive framework for systems       ware operates from a look and feel perspective. It
development. Even more importantly, the DII         is an assessment of how consistent the overall
COE guarantees the interoperability of all sys-     system will appear to the end user. It is important
tems that achieve full COE compliance. This ap-     that the resulting COE-based system appear
pendix addresses what is meant by COE               seamless and consistent to minimize training and
compliance. As with any standard, compliance is     maintenance costs.
required to ensure interoperability. More detailed
information on the DII COE and COE compliance       Category 3, Architectural Compatibility
may be found on the Defense Information Sys-        Category 3 measures how well the proposed soft-
tems Agency (DISA) COE configuration manage-        ware fits within the COE architecture (client/serv-
ment web site—http://spider.osfl.disa.mil/cm/       er architecture, distributed computing
1097_cm_page.html. The information in this ap-      environment (DCE) infrastructure, CDE desktop,
pendix is extracted from DII COE Version 3.0 of     etc.). It is an assessment of the software's poten-
5 February 1997.                                    tial longevity as the COE evolves. It does not im-
                                                    ply that all software must be client/server and
Compliance Categories                               remote procedure call (RPC)-based. It simply
                                                    means that a reasonable design choice has been
The DII COE defines four areas of compliance        made given that the COE is client/server based
called compliance categories. Within a specific     and is built on top of a DCE infrastructure.
category, a segment is assigned a numerical val-
ue, called the compliance level, which is a mea-    Category 4, Software Quality
sure of the degree to which a segment is            Category 4 measures traditional software metrics
compliant within the category. This approach fa-    (lines of code, McCabe complexity metric, etc.).
cilitates the development of migration strategies   It is an assessment of program risk and software
for legacy systems as well as the evaluation of     maturity.
COE compliance by both legacy systems and new
developments.                                       Category 1 Levels

Category 1, Runtime Environment                     Version 3.0 of the COE defines compliance levels
Category 1 measures how well the proposed soft-     for category 1 only. The COE defines eight pro-
ware fits within the COE executing environment      gressively deeper levels of integration for this
and the degree to which the software reuses COE     category. Levels 1 through 3 are considered to be
components. It is an assessment of whether the


---

A-2 ________________________________________________________________________________________________ MCWP 6-22

interfacing with the COE and not integrated with      Level 2, Network Compliance
the COE. Integration begins at level 4.
                                                      Two capabilities coexist on the same LAN but on
Bootstrap compliance (level 4) is required before     different central processing units (CPUs). Limited
a segment may be submitted to DISA for evalua-        data sharing is possible. If common user interface
tion as a prototype. Such segments will not be        standards are used, applications on the LAN may
fielded or accepted into the online library. At       have a common appearance to the user.
DISA's discretion, segments that meet the criteria
for minimal COE compliance (level 5) may be ac-       Level 3, Workstation Compliance
cepted into the online library and installed at se-
lected sites as prototypes for user evaluation and    Environmental conflicts have been resolved so
feedback. However, such segments will not be ac-      that two applications may reside on the same
cepted as fieldable products. Acceptance as an of-    LAN, share data, and coexist on the same work-
ficial DISA fieldable product requires                station as COE based software. The kernel COE,
demonstration of interoperable compliance (level      or its equivalent, must reside on the workstation.
7) and a migration strategy to full COE compli-       Segmenting may not have been performed, but
ance (level 8), unless the proposed segment is an     some COE components may be reused. Applica-
interim product that is targeted to be phased out in  tions do not use the COE services and are not nec-
the near term.                                        essarily inter operable.

As previously noted, the compliance categories        Level 4, Bootstrap Compliance
and levels are designed to support the migration
of legacy systems into the COE. The first step of     At level 4, all applications are in segment format
category 1, covered by levels 1 through 4, is to      and share the bootstrap COE. Segment formatting
ensure that systems do not destructively interfere    allows automatic checking for certain types of ap-
with each other when located at the same opera-       plication conflicts. Use of COE services is not
tional site. Level 5 is sometimes called a federa-    achieved and users may require separate login ac-
tion of systems in that while systems are still       counts to switch between applications.
maintained as stovepipes, they can safely share
common hardware platform resources. Levels 6          Level 5, Minimal COE Compliance
through 8 complete the migration by reducing
functional duplication, promoting true data shar-     At this level, all segments share the same kernel
ing, and making the system appear to the user as if   COE, and functionality is available via the execu-
it were developed as a single system. The last        tive manager. Boot, background, and local pro-
three levels represent varying degrees of integra-    cesses are specified through the appropriate
tion from marginally acceptable (level 6) to a tru-   segment descriptor files. Segments are registered
ly integrated system (level 8).                       and available through the online library. Applica-
                                                      tions appear integrated to the user, but there may
Level 1, Standards Compliance                         be duplication of functionality and inter operabili-
                                                      ty is not guaranteed. Segments may be successful-
Level 1 is a superficial level in which the pro-      ly installed and removed through the COE
posed capabilities share only a common set of         installation tools.
COTS standards. Sharing of data is undisciplined,
and minimal software reuse exists beyond the          Level 6, Intermediate COE Compliance
COTS. Level 1 may allow simultaneous execu-
tion of the two systems.                              Segments use existing account groups and reuse
                                                      one or more COE component segments. Minor
                                                      documented differences may exist between the
                                                      style guide and the segment's graphical user inter-
                                                      face (GUI) implementation.


---

Communications and Information Systems ______________________________________________________________ A-3

Level 7, Interoperable Compliance                     Level 8, Full COE Compliance

Segments reuse COE component segments to en-          Proposed new functionality is completely integrat-
sure inter operability. These include COE provid-     ed into the system (e.g., makes maximum possible
ed communications interfaces, message parsers,        use of COE services) and is available via the exec-
database tables, track data elements, and logistic    utive manager. The segment is fully compliant
services. All access is through published applica-    with the style guide and uses only published public
tion program interfaces with documented use of        application program interfaces. The segment does
few, if any, private application program interfaces.  not duplicate any functionality contained else-
Segments do not duplicate any functionality con-      where in the system whether as part of the COE or
tained in COE component segments.                     as part of another mission application segment.

                                                      (reverse blank)


---

                                Appendix B

              Common Hardware and
Standard Commercial Software Applications

MAGTF units employ a wide and varied array of         grate to the DII COE, they are hosted on a stand-
computers and peripheral equipment. Although          ard suite of computersCthe Marine common
some of this computer hardware represents the lat-    hardware suite (MCHS).
est technology in the commercial market, in many
instances, constrained budgets force units to con-    The Marine Common Hardware
tinue to use some outdated, yet still functioning,    Suite
equipment. This situation is a fact of life in the
FMF and is manageable through proper training         The Common Computer Resources (CCR) Pro-
and effective maintenance practices. However,         gram Office, Marine Corps Systems Command,
such equipment will ultimately become more ex-        continuously evaluates computers and peripheral
pensive to maintain than to replace.                  equipment for inclusion in the MCHS and identi-
                                                      fies DOD contract vehicles (currently Navy- and
Standard commercial software is identified by Re-     Army-common hardware programs) to use for
quirements Division, Marine Corps Combat De-          procurement by the MCHS. This office maintains
velopment Command. These standards are                a Computer Buyer’s Guide that is updated on a
promulgated to improve interoperability and re-       quarterly basis and posted on the Marine Corps
duce training requirements.                           Systems Command web site (www.marcorsy-
                                                      scom.usmc.mil). Procurement of common com-
Computers are used throughout the MAGTF both          puter resources through the MCHS program will
as integral components of tactical information sys-   help ensure commonality, interoperability, sup-
tems and for administrative and logistic support      portability, and redundancy between the comput-
functions. Several fielded tactical information sys-  ers and peripherals that support the many
tems including TAOM and PLRS use embedded             functional users. Figure B-1 depicts the categories
Navy standard AYK and UYK computers, which            of MCHS equipment currently available through
will not be addressed here. As new MAGTF C4I          the CCR contracts.
systems are developed and fielded systems mi-

Figure B-1. The MCHS.


---

B-2 ________________________________________________________________________________________________ MCWP 6-22

MCHS High-Performance Server                          and machines, data storage devices, UPSs, and
                                                      various types of displays. Some of these devices
The high-performance server (HPS) is intended to      are purchased as standard equipment through the
function as a network server, database server, and    supply system, and others are obtained as COTS
communications server, or as a central facility       products. Additionally, many peripheral compo-
processor with rapid processing and display capa-     nents are provided as part of the MCHS equip-
bilities. It is intended for medium-to-large-sized    ment fielded for various command posts and
workgroups that use processor-intensive applica-      centers. Proper operation of this equipment in-
tions. HPS computers are available in both UNIX-      volves using quality cables and ensuring that
compatible, reduced instruction set computing         proper connections are maintained to computing
(RISC) and PC-compatible, complex instruction         and LAN equipment. Most peripherals also re-
set computing (CISC) architectures. The HPS           quire software drivers that must be installed with
RISC and CISC computers are also available in         the appropriate user preferences and settings. Ta-
both nonrugged (V1) and rugged (V2) variants.         ble B-1 lists some typical peripheral equipment
Variant 2 is configured to fit into a 19-inch rack.   used with MAGTF information systems.
Peripherals available for the HPS include CD-
ROM, erasable optical disks, digital audio tape       Data Storage
(DAT) drives, high-capacity internal storage
disks, an expansion chassis, enhanced graphics ca-    The MCHS provides a separate four-bay SCSI pe-
pability, and various video monitors.                 ripheral device enclosure, commonly referred to
                                                      as the TAC-4 Data Silo. This enclosure accom-
MCHS High-Performance Workstation/                    modates two 2.5 GB (4 GB optional) removable
Application Server                                    disks, a CD-ROM drive, and a 4-mm DAT drive.
                                                      The TAC-4 Data Silo is connected to the worksta-
The high-performance workstation (HPW) has the        tion via an SCSI port. This item is a part of the
capability to function as a server for smaller        MCHS suite of equipment.
workgroups and as a network or standalone work-
station. The HPW is available in the same com-        I/O
puting architectures and variants as the HPS.
Variant 1 is available in desktop/deskside and        The SCSI provides a commercial standard com-
portable configurations. Variant 2 is available in a  puter interface for peripheral devices. The SCSI
portable configuration.                               terminal server is a separate SCSI peripheral de-
                                                      vice that provides eight RS-232 serial ports and
MCHS Standard Application                             one parallel port as a means of connectivity to
Workstation                                           other devices. This item is a part of the MCHS
                                                      suite of equipment.
The MCHS standard application workstation
(SAW) provides network and standalone, high-          Printer
and low-end, desktop or laptop computers for use
at all echelons of the MAGTF. The SAW comput-         The MAGTF MCHS printers include both Paint-
ers are available in the same computing architec-     Jet and DeskJet printers. These printers are avail-
tures and variants as the HPS and HPW                 able in both color and black and white for hard-
computers. Peripherals available for the SAW in-      copy text and graphics output.
clude CD-ROM, a tape drive, a high-capacity re-
movable disk drive, external video monitors,          Plotter
Ethernet LAN interface cards, a ruggedized mag-
neto-optical drive, and others.                       The recommended MCHS plotter is a DesignJet
                                                      model.
Peripherals
                                                      Scanner
Peripheral equipment includes items purchased
separately, such as printers, facsimile modems        The recommended MCHS scanner is a ScanJet
                                                      model.


---

Communications and Information Systems ______________________________________________________________ B-3

Display                                              End-User Computing Equipment

The large group display is composed of a flat-       The End-User Computing Equipment (EUCE)
panel video display that rests on top of a high-in-  Program fields microcomputer systems through-
tensity overhead projector to project the worksta-   out the FMF for general-purpose administrative
tion screen displays. This item is a part of the     information processing and for information sys-
MCHS suite of equipment.                             tem workstations. The EUCE, AN/UYK-83, and
                                                     the downsized version, DEUCE, AN/UYK-85,
Power Supply/Protection                              are ruggedized, Tempest-certified 286, 386, and
                                                     486 IBM-compatible computers. These comput-
UPSs protect computers from the power surges of      ers are being replaced by more capable computers
field-generated power. The UPS also provides a       purchased through the MCHS program.
backup power source.

Table B-1. MCHS Peripheral Equipment.

     Category                    Peripheral Equipment
Storage
                    Z-Micro single, dual plus, three-bay, four-bay,
Input/Output (I/O)  and seven-across expansion chassis with
Printer             removable hard drives and media canisters
Plotter
Scanner             SCSI Terminal Server
Display
Power Supply        Hewlett-Packard DeskJet and LaserJet Models

                    Hewlett-Packard DesignJet Models

                    Hewlett-Packard ScanJet Models

                    Large Group Display Flat-Panel Video Display

                    UPS
                    Rugged
                    COTS

                                                                     (reverse blank)


---

B-4 ________________________________________________________________________________________________ MCWP 6-22


---

         Appendix C

Ship Visit Checklist

Action Items                                         q Discuss ship’s ability to meet landing force
                                                        needs.
Ship visits are conducted by the CIS officer be-
fore embarkation. CIS representatives embarked       q Discuss equipment type, operational condition,
aboard the same ship should coordinate a joint          and interoperability.
meeting. CIS requirements have to be completely
coordinated with the ship’s information officer so   q Identify shortfalls.
that an exchange of information, decisions, plans,
orders, and instructions may be properly execut-     q Discuss deck mounting policy (i.e., location,
ed. Every attempt should be made to get a written       type of equipment, security, and safeguarding
agreement by all concerned. Key considerations          of ship’s watertight integrity).
during ship visits follow.
                                                     q Provide guard list and summary of anticipated
In Preparation                                          arrivals and departures.
q Determine communications center require-
                                                     q Discuss communications center and other ship-
   ments (number of augmentees).                        board personnel augmentation requirements.
q Determine circuit requirements.
q Determine TECHCON capabilities.                    q Discuss message quantities and distribution
q Identify classified material and CMS storage          procedures for landing force message traffic.

   needs.                                            q Obtain copy of Ship’s Loading and Character-
q Identify HAZMAT storage needs.                        istics Pamphlet (SLCP).

During Ship Visit                                    q Review SLCP for accuracy.
q Determine space available for landing force:
                                                     q Review Marine tactical CIS systems and/or
   • Communications control                             communications detachment SOP(s).
   • Message reproduction and distribution
   • CIS officer and staff office                    q Identify shipboard CIS available for landing
   • Cryptographic material and equipment stor-         force use. (See list at end of this checklist.)

      age                                            q Coordinate EMCON notification-of-change
   • Battery storage                                    procedures.
   • CIS equipment repair benches
   • Radio central                                   q Discuss joint circuits and facilities to be used
   • Troop training spaces.                             during each phase of the operation.
q Locate joint spaces (joint intelligence center,
   SACC, etc.).                                      q Resolve location, quantity, and restoration pri-
q Provide prioritized list of landing force circuit     orities of landing force circuits. Get a copy of
   requirements (by type operation).                    the phone directory for the ship’s spaces to pre-
                                                        pare a phone directory for all landing force
                                                        spaces (including berthing and state rooms) and
                                                        other critical spaces aboard the ship.

                                                     Also Discuss:

                                                     q Antenna locations

                                                     q Frequency separation requirements

                                                     q Shipboard interference problems

                                                     q Joint intelligence center communications


---

C-2 __________________________________________________________________________________________________________________________________________________________ MCWP 6-22

q How to handle high-precedence and special-       q Plain old telephone system (POTS)
   category landing force message traffic          q KY-68 (connection to Pentagon red switch)
                                                   q EHF capabilities
q SCI communications
q Access lists                                     Shipboard CIS
q Remote locations
q Use of signal communications during EMCON        The following CIS represent the types of systems
q Supplies and communications center operating     found aboard amphibious ships in the fleet. This
                                                   list is not all inclusive; it is meant to stimulate
   stocks to be provided by landing force          thought and lead to a constructive dialog among
q Fleet secure voice communications (FLTSE-        embarking Marine and ship’s company CIS per-
                                                   sonnel. Systems will vary widely among ships of
   VOCOM) channelization                           the same type and among different types of ships.
q Competing requirements/potential problem ar-     This is because all ships are rotated periodically
                                                   through service life extension program overhauls
   eas                                             where they receive new systems and system up-
q Lost communications procedures                   grades that are planned through the combat devel-
q Window versus carrier frequencies                opment process.
q Telephone locations
q Multichannel channelization                      C2
q Clearance and message-release needs              q JMCIS Unified Build 1.X, 2.X, 3.X, etc.
q Use of brevity codes, authentication, and so on  q CTAPS host/remote
q Types of information systems available           q CTAPS 5.2 (TAC n)
q Availability of Navy and Marine Corps CIS op-    q Joint Maritime Tactical Communications

   erators, maintainers, and supply support per-      Switching System (JMTCSS) (formerly TRI-
   sonnel                                             TAC and smart multiplexing unit (SMU))
q Operational checkout of shipboard equipment      q Integrated Video System (23TV) closed-circuit
   designated for landing force use                   television video switch
q LAN connectivity to “green spaces”               q Radiant Mercury A rules-driven multilevel se-
q FCC-100 (SHF) channelization (satellite access      curity automatic sanitizer
   request coordination)                           q AN/USQ-119D, NTCS-A IV
q DSN trunks                                       q GCCS phase 2 or 3
q JDISS                                            q 9TV (SXQ-8)
q GCCS
q TCO, IAS, AFATDS, Logistic AIS (LOGAIS),         Satellite Communications
   etc.                                            q INMARSAT A/B
q IP addresses                                     q W-band commercial SATCOM
q Use of copiers/printers/scanners                 q EHF SATCOM USC-38
q INMARSAT                                         q Navy EHF communications controller (NECC)
q NIPRNET                                          q EHF medium data rate (MDR) MILSTAR
q SIPRNET                                          q High-speed fleet broadcast
q JWICS                                            q WSC-3 UHF SATCOM/line of sight
q Unique systems (PLRS/KSQ-1, situational
   awareness beacon with reply (SABER), en-
   hanced PLRS)


---

Communications and Information Systems ____________________________________________________________________________________________________ C-3

q WSC-6 SHF SATCOM/7’ antenna                      q Tactical Data Information Exchange System-
q Global Broadcast Service (GBS)/Joint Broad-         Subsystem A (TADIXS-A)

   cast Service (JBS)                              q TADIXS-B tactical receive equipment
q UHF DAMA                                         q JTT/commander’s tactical terminal (CTT)
q 5 kHz DAMA AN/USC-54                             q Battle Group Information Exchange System

Logistics                                             (BGIXS)

q Naval Tactical Command Support System            Tactical Communications
   (NTCSS) includes the following:                 q Mission Display System
                                                   q Battlegroup cellular telephone system
   • Shipboard Nontactical Automated Data Pro-     q Maritime Cellular Information Exchange Sys-
      cessing (ADP) Program (SNAP): includes
      automated supply, financial, organizational     tem (MCIXS)
      maintenance management, administration,      q High-frequency radio group (HFRG)
      and medical functions                        q R-2368A HF/low frequency-medium frequen-

   • Naval Aviation Logistics Command Man-            cy receiver
      agement Information System (NALCOMIS):       q SINCGARS (3 channel)
      includes intermediate and organizational-    q UHF Digital Wideband Transmission System
      level maintenance management
                                                      (DWTS)
q Maintenance Resource Management System           q UHF antijam HAVE QUICK
   (MRMS): automates shipboard intermediate        q Video Information Exchange System (VIXS)
   maintenance management.
                                                   Intelligence-IW Sensors
Communications                                     q JWICS
                                                   q JDISS
q Joint Maritime Communications Strategy (JM-      q Battle Group Passive Horizon Extension Sys-
   COMS) includes—
                                                      tem (BGPHES)
• Automated Digital Network System                 q Common high-bandwidth data link (CHBDL)
   (ADNS): network management, switching,          q Outboard/combat direction finding
   routing, and control                            q Ship’s signals exploitation equipment
                                                   q JSIPS-Navy (JSIPS-N)
• Digital Modular Radio (DMR) System: mul-         q DSSCS
   tifunction radio (2 kHz - 2 GHz)                q TACINTEL
                                                   q Tactical Remote Sensor System (TRSS)
• Integrated Terminal Program (ITP): military
   and commercial radio at frequencies above 2     Message Processing
   GHz.                                            q NAVMACS I/II
                                                   q AN/SSQ-33A Shipboard Automated Commu-
q Link 4A air intercept control and fighter-to-
   fighter data link                                  nications Control System
                                                   q UGC-143A(V) Navy standard terminal (NST)
q Link 11 AN/USQ-125 common shipboard data         q Navy orderwire
   terminal set (CSDTS)

q Link 16 (JTIDS)/command and control proces-
   sor rehost

q Officer in Tactical Command Information Ex-
   change System (OTCIXS)

q TACINTEL (UHF Fleet           SATCOM
   Subsystem)/TACINTEL II Plus


---

C-4 __________________________________________________________________________________________________________________________________________________________ MCWP 6-22

Miscellaneous CIS Equipment                       q IT-21 DNS-SCI
q Red analog switch                               q Red/black baseband switch
q Black analog switch                             q SSQ-88C Quality Monitoring System
q Battlegroup HF e-mail                           q Electronic Key Management System Phase 2
q Information transfer for the 21st century (IT-  q Navy Key Management System local manage-

   21)                                               ment device
q IT-21 DNS-GENSER


---

         Appendix D

MAGTF Radio Nets

This appendix provides the basic description and      Marine Expeditionary Force
participants for each radio net. It is a planning     Master Net Lists
guide for radio nets that may be established to sat-
isfy MAGTF CIS requirements. CIS officers must        The MEF Master Net List is a database that facili-
emphasize to users of this appendix that not all of   tates the MEF’s Revised Battlefield Electronic
the listed radio nets will be used in a given opera-  CEOI System CEOI generation. These files are
tion or exercise. As few as two or three nets may     unclassified and consist of every circuit within the
suffice to meet mission requirements.                 MEF and each circuit’s emission requirements, as
                                                      well as grouping, call sign, and call word infor-
The kinds of services (voice, video, facsimile,       mation. The list is important to SINCGARS net-
etc.) that are required should be determined and      work planners because it is the sole source for net
adjusted to conform to available resources (per-      assignments and net identifiers. Characteristics of
sonnel, equipment, and frequency/channel avail-       the Master Net List are presented in table D-1 (on
ability) and environmental characteristics. The       page D-2).
required service will be governed primarily by the
tactical situation, terrain features, and distances   The MEF Master Net List is controlled by the
between stations on the net (with due consider-       MEF G-6 and is managed by the MEF frequency
ation to equipment inventories and available per-     manager. The MEF Master Net List will be re-
sonnel). Multiple nets of the same type may be        viewed annually for proposed modifications on
established to handle excess traffic volume. These    the basis of input from operating force command-
nets would have a number suffix such as 1, 2, and     ers. Requests for modification of the Master Net
3 for the primary, secondary, and tertiary circuits   List will be submitted to higher HQ for consolida-
of the same type. The primary net descriptions are    tion and review. The Master Net List, and thereby
given in this appendix.                               CEOI net assignments, should not be modified
                                                      without the review and approval of the MEF G-6.
Within each net composition, units in italics nor-
mally participate in the specified net as required.   The need to maintain consistent, standard radio
There is no absolute requirement for each unit        network terminology demands that MEF radio
noted to participate in net composition. CIS offic-   circuit assignments be regulated. With the intro-
ers can use the net composition in this appendix      duction of the Revised Battlefield Electronic
for planning and compiling radio guard charts         CEOI System Master Net List, electronic CEOI
(which SPEED provides) for operations.                information can be matched to the task organiza-
                                                      tion, edited, generated, and printed for an entire
Where multiple frequency bands are listed in pa-      MEF within hours. Unit participation in Master
rentheses following radio net titles, the frequency   Net List revisions and compliance are essential to
band that is normally assigned is listed first.       maintaining the currency of this information.


---

D-2 ________________________________________________________________________________________________ MCWP 6-22

                     Table D-1. Special Characteristics of the Master Net List.

             Item              Purpose                                         Comment
Net number           Reference                      Used to provide task organization requirements to higher
                                                    HQ
Net name             Description                    Standard net description
Net ID               SINCGARS                       000 - 999
Call sign            Call-sign assignment           Yes or no, assigned randomly
Organizational code  Echelon separation             Allows for duplicate net IDs within separate units
Restrictions         Subband separation             Allows for restrictive frequency assignments (such as HF
                                                    day and night)
Frequency            Band assignment                N-None, H-HF, F=VHF, A=VHF-AM, U=UHF, S=SHF,
                                                    E=EHF
Power                Output power                   1-High through 4-Low
Reuse class          Geographic separation          Tactical
Call word            Call-word assignment           Fixed or random

Marine Air-Ground Task Force                        MAGTF Tactical 1 (UHF-SATCOM/
Command Element Nets                                VHF/HF)
                                                    Used to carry operational traffic between the
MAGTF CE nets are established to support the        commander and major CEs of the MAGTF.
exercise of command and control during combat
operations. The type operation, commander’s in-     q CE
tent, concept of operations, environment, enemy     q GCE(s)
capabilities, and MAGTF task organization will      q ACE(s)
influence which nets are required and established.  q Other OPCON units
During amphibious operations the term MAGTF         q Landing force TACLOG
is synonymous with the term landing force.
MAGTF CE nets follow:                               MAGTF Ground Reconnaissance
                                                    Command (UHF-SATCOM/HF)
MAGTF Command Net 1 (UHF-SAT-                       Used for C2 of landing force ground reconnais-
COM/HF)                                             sance operations and transmission of collected re-
Used to exercise command and coordinate admin-      connaissance directly to the MAGTF commander
istrative and logistic functions with the major     or the MAGTF CE combat intelligence center
components of the MAGTF.                            (CIC).

q CE                                                q CE
q GCE(s)                                            q OPCON reconnaissance units
q ACE(s)                                            q Unmanned aerial vehicle (UAV) squadron/de-
q CSSE
q Other OPCON units                                    tachment
                                                    q GCE(s)


---

Communications and Information Systems ______________________________________________________________ D-3

q Other units, as required (e.g., radio battalion     MAGTF NGF Support 1 (HF)
   radio reconnaissance team (RRT), Navy spe-         Used to request NGF support and coordinate the
   cial warfare teams, etc.)                          employment of NGF support ships in general sup-
                                                      port of the landing force.
MAGTF Alert/Broadcast (HF)
Used for alert warning traffic or general traffic     q SACC
pertaining to all (or the majority) of the units on   q GCE(s)
this net. Messages not of an alert warning type will  q Landing force general support ships
be consecutively numbered upon transmission.          q CE

q CE                                                  MAGTF Fire Support Coordination
q Designated units within the MAGTF ground el-        (UHF-SATCOM/VHF/HF)
                                                      Used to coordinate all MAGTF fires. Activated at
   ement(s)                                           the CE when a FFCC or FSCC is established.

MAGTF Intelligence (UHF-SATCOM/                       q SACC
HF/VHF).                                              q FFCC and senior FSCC(s)
Used for rapid reporting and dissemination of in-     q Senior artillery FDC
telligence, collaborative planning of future          q UAV squadron/detachment
MAGTF intelligence operations, and command            q SASS
and control of ongoing MAGTF intelligence and
reconnaissance operations.                            NGF Control (HF)
                                                      Used to request, assign, and relieve fire support
q CE                                                  ships. Also used to request general support mis-
q GCE(s)                                              sions and report reliefs, emergencies, and orders
q ACE(s)                                              pertinent to the execution of scheduled fires. The
q CSSE                                                CATF may establish an NGF control overload net
q OPCON intelligence and reconnaissance units         to handle excess traffic.
q UAV squadron/detachment
                                                      q CATF/SACC
MAGTF Air Observation (UHF/VHF)                       q Fire support group and unit commanders
Used to coordinate air observation and transmit       q Fire support ships
information from air observers to MAGTF ele-          q Screen commanders
ments. May be used to adjust artillery or naval       q GCE NGF officer
gunfire (NGF) on an emergency basis.
                                                      NGF Ground Spot 1 (HF)
q CE                                                  Used to control individual ship gunfire support.
q Aerial observer                                     Its primary use is to call and adjust fire, and its
q GCE                                                 secondary use is to exchange vital information be-
q FSCCs                                               tween stations on the network, such as frontline
q Artillery battery FDC                               positions. Activated at the MAGTF CE level
q Supporting arms special staff (SASS)                when a MAGTF FFCC or FSCC is established.


---

D-4 ________________________________________________________________________________________________ MCWP 6-22

q Battalion FSCC(s) (NGF liaison officer(s))           q Convoy commander
q NGF spot team(s)                                     q Designated convoy elements
q FFCC and/or FSCC(s)                                  q Artillery units and aerial observers
q Direct support ship(s)                               q HQ of unit conducting convoy
q General support ship(s)
q UAV squadron/detachment                              MAGTF Landing Zone (LZ) Control 1
                                                       (UHF/VHF)
Shore Fire Control Party Local 1 (VHF)                 Used to control and coordinate helicopters en
Used to coordinate shore fire control party activi-    route between the initial point and the LZ.
ties.
                                                       q MAGTF CE
q NGF spot team                                        q Support helicopters
q NGF liaison officer                                  q LZ control team
                                                       q MAGTF support party
MAGTF Artillery Command/Fire                           q Helicopter support teams
Direction (HF)
Used to direct the fires of artillery units when es-   Helicopter Support Team Control 1
tablished ashore. Established only when two or         (HF)
more independent artillery units are providing fire    Used to control and coordinate helicopter support
support for the MAGTF.                                 team activities.

q FFCC/FSCC/SASS                                       q MAGTF CE TACLOG group
q SACC (MAGTF artillery officer afloat)                q TACLOG support helicopters
q MAGTF artillery units                                q MAGTF support party
                                                       q Helicopter support teams
MAGTF Artillery Air Spot (UHF/VHF)
Used to conduct air spot for force artillery fires on  Helicopter LZ (HLZ) Local 1 (VHF)
deep and difficult targets. Activated at MAGTF         Used to coordinate helicopter support team activi-
level only when artillery units are under the direct   ties within an LZ.
control of the MAGTF commander.
                                                       q Helicopter support team
q Force artillery air spotters
q CE                                                   MAGTF CSS (UHF-SATCOM/HF/VHF)
q GCE artillery air spotters                           Used to coordinate CSS within the MAGTF.
q Artillery units
                                                       q CE
MAGTF Convoy Control 1 (VHF/HF)                        q GCE(s)
Used to control the various elements within a con-     q ACE(s)
voy. Artillery units and aerial observers may enter    q CSSE
to ensure security of motor march routes. Multiple     q TACLOG element
convoy control nets may be required depending
on the extent of motor march activity within the
force.


---

Communications and Information Systems ______________________________________________________________ D-5

MAGTF Damage Control (HF)                          q HQ commandant
Used to exchange damage assessment informa-        q Security elements as directed
tion subsequent to an enemy attack with mass de-
struction means. Also used to direct and           MAGTF Medical Regulating (HF)
coordinate evacuation and casualty assistance for  Used to coordinate casualty distribution among
a stricken unit.                                   medical treatment facilities.

q CE                                               q Landing force casualty evacuation agency
q All MAGTF units of battalion/squadron size       q Medical battalion/unit
                                                   q Hospital ships
   and larger                                      q Designated medical facilities
q Damage control parties/ monitor teams
q Mass evacuation units                            MAGTF Communications Information
q Designated medical units                         Systems Coordination 1 (UHF- SAT-
                                                   COM/HF/VHF)
MAGTF Damage Control Local 1 (VHF)                 Used to coordinate, install, and restore MAGTF
Used to coordinate damage control efforts within   communications-information systems operations.
a local area.
                                                   q CE (G-6/S-6)
q Damage control parties                           q GCE (G-6/S-6)
                                                   q ACE (G-6/S-6)
MAGTF Support Party Control (HF)                   q CSSE (G-6/S-6)
Used for combat units to request support from the  q Communications unit (S-3/detachments)
landing force support party (LFSP) and for the
LFSP to coordinate with TACLOGs for landing        MAGTF EW Coordination (HF)
of equipment and supplies.                         Used to coordinate electronic attack (EA) and
                                                   SIGINT activities.
q Landing force TACLOG
q GCE TACLOG                                       q CE (G-3/S-3 EWCC)
q MAGTF support party                              q OCAC
q LFSP liaison teams                               q GCE
q FSSG/brigade service support group/MEU ser-      q TACC
                                                   q TAOC
   vice support group
                                                   MAGTF Defense Special Security
Shore Party Net (VHF)                              Communications System Entry (UHF-
Used to coordinate shore party activities on a     SATCOM/HF/Multiplex (MUX))
landing beach or on multiple beaches.              Used to provide the MAGTF commander with an
                                                   SCI data communication capability with external
q Shore party                                      agencies. The communication path is provided by
q Beach party team                                 the supported commander, and the terminal
                                                   equipment and personnel are provided by the
MAGTF Local Security (VHF)                         radio battalion/special security communications
Used to coordinate CE security.                    team (SSCT).


---

D-6 ________________________________________________________________________________________________ MCWP 6-22

q MAGTF CE via the radio battalion/detachment     q MAW SSCT
   special security communication element
                                                  Radio Battalion/SSU Command and
MAGTF Special Intelligence Communi-               Control Net (HF/VHF)
cations Net External (HF)                         Used to provide the battalion commander/detach-
Used to provide the MAGTF commander with a        ment officer in charge with command and control
secure data communications channel for the ex-    of subordinate elements. The communications
change of SCI. The communications path is pro-    path, equipment, and personnel are provided by
vided by the supported commander, and the         the radio battalion.
terminal equipment and personnel are provided
by the radio battalion/SSCT.                      q Radio battalion
                                                  q Radio battalion direct support unit
q MAGTF CE via the radio battalion detachment
   special security communication element         Theater Cryptologic Support Net
                                                  (HF/UHF-SATCOM)
q CJTF                                            Used to provide rapid exchange of cryptologic in-
q CATF                                            formation with the cryptologic elements of other
                                                  organizations. The communications path is pro-
MAGTF Critical Communications                     vided by the supported commander, and the ter-
(CRITICOMM) Net (UHF-SATCOM/VHF)                  minal equipment is provided by the radio
Used to provide the supported commander with a    battalion direct support unit.
channel to adjacent Service cryptologic agencies
or cryptologic support group. The communica-      q MAGTF (radio battalion direct support unit)
tions path is provided by the supported command-  q Adjacent Service cryptologic elements
er, and the terminal equipment and personnel are  q National cryptologic agencies
provided by the radio battalion/SSCT.             q Joint/ATF cryptologic agencies

q MAGTF CE via the radio battalion/ SIGINT        Radio Battalion CRITICOMM Net
   support unit (SSU) special security communi-   (UHF-SATCOM/HF/VHF)
   cations element                                Used to provide CRITICOMM facilities to battal-
                                                  ion elements that are physically removed from the
q Higher HQ, adjacent HQ, and theater and na-     CP in support of MAGTF units. The communica-
   tional intelligence/SIGINT agencies            tions path is provided by the supported command-
                                                  er, and the equipment and personnel are provided
MAGTF Internal Special Intelligence               by the radio battalion.
Communications Handling System Net
(VHF/UHF/SHF)                                     q Radio battalion
Used to provide the MAGTF commander with a        q Radio battalion direct support unit (at least
secure SCI communications capability with sub-
ordinate division/wing commanders through their      two)
organic SSCT. The communications path is pro-
vided by the supported commander, and the ter-    Radio Battalion/SSU Collection and
minal equipment and personnel are provided by     Reporting Net (UHF-SATCOM/HF/VHF)
the radio battalion/SSCT.                         Used to provide command and control and SIG-
                                                  INT reporting capabilities for battalion/SSU col-
q MAGTF CE via radio battalion/SSU special se-    lection operations.
   curity communications element

q Division SSCT


---

Communications and Information Systems ______________________________________________________________ D-7

q Radio battalion/SSU (OCAC)                        Tactical Receive Equipment and
q Deployed collection/direction funding (DF)        Related Applications Program Data
                                                    Dissemination System
   teams                                            Used to provide global surveillance information
                                                    in time for sensor cueing and to provide indica-
Radio Battalion/SSU EA Control Net                  tions and warning. Data is forwarded from sensor
(VHF)                                               to communications gateways/relays for dissemi-
Used to provide the direction and control of radio  nation to worldwide military users via geosyn-
battalion electronic countermeasures assets. The    chronous UHF satellite links. TDDS data sources
communications path, equipment, and personnel       include national and tactical sensor systems.
are provided by the radio battalion.
                                                    q Intelligence agencies
q Radio battalion/SSU (OCAC)                        q CIC
q Deployed EA teams                                 q OCAC
                                                    q SSES
Radio Battalion/SSU DF Flash Net                    q ATFIC
(VHF)
Used to provide the DF control station with a       On-Board Processor/Direct Downlink
means of broadcasting DF flashes to the DF out-     Used to distribute nationally generated data to op-
stations. The communications path, equipment,       erational forces and commanders worldwide. The
and personnel are provided by the radio battalion.  information delivered directly to tactical users can
                                                    be used to support indications and warning, sur-
q Radio battalion/SSU (OCAC)                        veillance, targeting (including OTH targeting),
q Deployed DF teams                                 maneuver, execution, and battle damage assess-
                                                    ment.
Radio Battalion/SSU DF Report Net
(VHF)                                               q Intelligence agencies
Used for DF reporting from DF outstations to DF     q CIC
control. The communications path, equipment,        q OCAC
and personnel are provided by the radio battalion.  q SSES
                                                    q Joint intelligence center
q Radio battalion/SSU (OCAC)
q Deployed DF teams                                 TACINTEL Broadcast Service
                                                    Used to provide near-real-time intelligence from
DF Data Net (VHF)                                   an open network of interactive participants by us-
Used to exchange DF information between out-        ing multiple sensors and sources. The TIBS
stations and DF control. The communications         broadcast uses UHF SATCOM assets for network
path, equipment, and personnel are provided by      operation and for the relay of out-of-theater spe-
the radio battalion.                                cific information into the tactical users’ AOs.
                                                    TIBS participants include a wide variety of na-
q DF outstations                                    tional and Service airborne, surface, and subsur-
q DF control                                        face intelligence platforms.

                                                    q JTF, theater, and national intelligence organiza-
                                                       tions

                                                    q MAGTF CE (CIC)


---

D-8 ________________________________________________________________________________________________ MCWP 6-22

q ATFIC (SSES)                                       q MEWSS internal
                                                     q Army Guardrail Common Sensor
Tactical Reconnaissance Intelligence                 q Army Ground-Based Common Sensor
Exchange System                                      q Army Advanced Quickfix

Used to provide high-accuracy targeting data to      Radio Battalion/SSU DF Net (UHF)
multi-Service/joint Services command, control,       Used to control, coordinate, and report DF data.
and intelligence users. The TRIXS network sup-
ports full-duplex data and half-duplex voice con-    q MEWSS
nectivity between user terminals. It is designed to  q OCAC
provide in-time intelligence reports that are fo-    q Army Technical Control and Analysis Element
cused on high-payoff ground threat targets. It is
capable of providing maneuver, threat avoidance,     Radio Battalion/SSU Tasking and
targeting, mission planning, and sensor cueing       Reporting Net (VHF)
support to commanders at all echelons. The           Used to issue taskings/report results
TRIXS network can accept input from up to five
intelligence producers such as the Army Guardrail    q Team Portable Collection System
Common Sensor and Airborne Reconnaissance            q Analyst Subsystem
Low, the Air Force Contingency Airborne Recon-       q Collection outstations
naissance System, and the Navy Story Teller Sys-
tem.                                                 Radio Reconnaissance Command
                                                     (UHF-TACSAT)
q JTF, theater, and national intelligence organiza-  Used for command and control of deployed
   tions                                             RRTs; reporting of SIGINT collection and DF re-
                                                     ports.
q MAGTF CE (CIC)
q ATFIC (SSES)                                       q MAGTF CE (CIC)
                                                     q ATFIC (SSES)
TACINTEL Net
                                                     TROJAN SPIRIT II Net (C and Ku Band
Used for transmission and reception of sensitive     SATCOM)
information sensor data and voice among collec-      Used to receive, report, and disseminate intelli-
tion and reporting units and detachments of the      gence information over a special-purpose satellite
radio battalion, the MAGTF, and shipboard facili-    system.
ties, TACINTEL is an automated, high-speed data
link.                                                q MAGTF CE (CIC/OCAC)
                                                     q ATFIC (SSES)
q JTF, theater, and national intelligence organiza-  q External intelligence agencies and organiza-
   tions
                                                        tions
q MAGTF CE (CIC)
q ATFIC (SSES)                                       Maritime Prepositioning Ships (MPS)
                                                     Offload 1 (HF/VHF/UHF SATCOM)
Radio Battalion/SSU Mission                          Used to control and coordinate the MPS offload.
Equipment Control Data Link
Net (UHF)

Used to control, coordinate, and monitor the mis-
sion equipment of the MEWSS. This net is used
for internal MEWSS operations and for interface
and cooperative operation with the Army intelli-
gence and EW common sensor systems.


---

Communications and Information Systems ______________________________________________________________ D-9

q Surveillance, liaison, and reconnaissance party      q Others, as required
   (SLRP)
                                                       Sensor Reporting Net (VHF)
Force Reconnaissance Company                           Used as a means for rapid reporting of sensor data
Command (HF)                                           to supported units.
Used to exercise command and coordinate admin-
istrative and logistic requests of subordinate units.  q MAGTF CE CIC (SARC [net control])
                                                       q SCAMP monitoring sites
q Unit HQ                                              q Supported units
q Subordinate units                                    q Others, as required
q Liaison personnel
                                                       SCAMP Data Transmission (VHF)
Surveillance and Control Data Link                     Used for transmission of sensor data collected by
(UHF)                                                  remote sensor sites.
The surveillance and control data link is used to
transmit moving target indicator, synthetic aper-      q SCAMP liaison and control element monitor-
ture radar, and fixed target indicator data acquired      ing sites
by Joint STARS to the MAGTF CE to support
target acquisition, situation development, bat-        q MAGTF CE CIC (SARC)
tlespace management, and targeting functions.          q Remote sensor and sensor relay sites

q JSTARS                                               CI/HUMINT Team(s) Command
q MAGTF CE G-2 section's CGS                           (HF/VHF)
                                                       Used for command and control of CI teams and
Air/Naval Gunfire Liaison Company/                     subteams, interrogator-translator teams and sub-
Marine Liaison Group Command                           teams, and HUMINT exploitation teams opera-
(VHF/UHF)                                              tions and the coordination of CI/HUMINT
Used to exercise command and coordinate admin-         administrative and logistic support.
istrative and logistic requests of subordinate units.
                                                       q MAGTF CE CIC (SARC HUMINT liaison and
q ANGLICO HQ/MLG HQ                                       control element)
q Senior liaison team/Marine liaison companies
q Subordinate liaison teams                            q CI/HUMINT company/detachment HQ
                                                       q Deployed CI/HUMINT teams and subteams
Sensor Control and Management                          q Others, as required
Platoon (SCAMP) Command (VHF)
Used for command and control of SCAMP opera-           CI/HUMINT Reporting Net (VHF)
tions and for the coordination of SCAMP admin-         Used as a means for the rapid reporting of CI/HU-
istrative and logistic support.                        MINT data to supported units.

q MAGTF CE CIC (SARC/SCAMP liaison and                 q MAGTF CE CIC (SARC [net control])
   control element)                                    q Deployed CI/HUMINT teams and subteams
                                                       q Supported units
q SCAMP/detachment HQ                                  q Others, as required
q Monitoring sites/deployed sensor employment

   squad (SES)/sensor employment team liaison
   teams


---

D-10 _______________________________________________________________________________________________ MCWP 6-22

Ground Combat Element Nets                         q GCE HQ (G-2/S-2/SARC)
                                                   q Reconnaissance units
Division/GCE Command 1 (HF)                        q LAR units
Used by the division/RLT/BLT commander to ex-      q UAV squadron/detachment
ercise command and coordinate administrative
and logistic functions.                            Division/GCE Intelligence (HF/VHF)
                                                   Used to provide rapid reporting and dissemination
q GCE HQ (forward, main, and alternate CPs)        of intelligence, collaborative planning of future
q Artillery regiment/battalion/battery             intelligence operations, and command and control
q Infantry regiment/battalion/company              of ongoing intelligence and reconnaissance opera-
q Reconnaissance battalion/company/platoon         tions.
q LAR battalion/company
q Tank battalion/company/platoon                   q GCE HQ (G-2/S-2/MAFC)
q Assault amphibian battalion/company platoon      q Infantry units
q Combat engineer battalion/company/platoon        q Artillery units
q GCE TACLOG group                                 q Reconnaissance units
q Attached combat and CSS units                    q LAR units
                                                   q Tank units
Division/GCE Tactical 1                            q Assault amphibian units
(UHF-SATCOM/HF/VHF)                                q Combat engineer units
Used by commanders to exercise TACON of ma-        q Attached/direct support intelligence units
jor combat units of the GCE.
                                                      (RadBn SIGINT support unit [SSU], CI team)
q GCE HQ (forward, main, and alternate CPs)        q UAV squadron/detachment
q Infantry regiment/battalion/company              q Attached combat and combat support units
q Artillery regiment/battalion/battery
q Reconnaissance company/platoon                   Marine Division Defense Special
q LAR battalion/company                            Security Communications System
q Tank battalion/company/platoon                   Entry (UHF-SATCOM/HF/MUX)
q Assault amphibian battalion/company/platoon      Used to provide the division commander with an
q Combat engineer battalion/company/platoon        SCI data communication capability with external
q UAV squadron/detachment                          agencies. The communications path is provided
q Attached combat units                            by the communications company, and the termi-
q GCE TACLOG                                       nal equipment and personnel are provided by the
q MAGTF TACLOG                                     division SSCT.

Division/GCE Ground Reconnaissance                 q SSCT
Company Command (HF/VHF)
Used for command and control of ground recon-      Division/GCE Fire Support
naissance operations and for reporting reconnais-  Coordination (HF/VHF)
sance information for deployed reconnaissance      Used to provide division/GCE-level fire support
elements/teams to the GCE G-2/S-2 (SARC).          coordination.

                                                   q GCE FSCC


---

Communications and Information Systems _____________________________________________________________ D-11

q Artillery regiment                                q MP company HQ
q Subordinate regiment FSCC(s)                      q MP units
q UAV squadron/detachment                           q Traffic control/mobile units
q DASC
                                                    Combat Engineer Battalion Command
Division/GCE Communications                         (HF)
Information Systems Coordination 1                  Used for administrative control and OPCON of
(HF/VHF)                                            subordinate units.
Used to coordinate, install, maintain, and restore
GCE communications information systems opera-       q Combat engineer battalion HQ
tions.                                              q Engineer units
                                                    q Supporting and attached units
q GCE HQ (G-6/S-6)                                  q Liaison personnel at higher HQ
q Infantry S-6s and communications information
                                                    Engineer Company Command (VHF)
   systems units                                    Used for administrative control and OPCON of
q Artillery S-6s and communications information     subordinate units.

   systems units                                    q Engineer company HQ
q Separate battalions (S-6)                         q Engineer units
q Attached combat and combat support units          q Liaison personnel at higher HQ

Division/GCE Convoy Control 1 (VHF)                 Engineer Local (VHF)
Used to control elements within a convoy and to     Used to coordinate engineer efforts within a local
ensure security (threat and fratricide) of motor    area.
march routes.
                                                    q Engineer units/detachments
q Convoy commander
q Convoy elements                                   Tank Battalion/Company/Platoon
q Artillery units                                   Command 1 (VHF)
q Aerial observers                                  Used to exercise command and coordinate admin-
q Division HQ                                       istrative and logistic requests. Separate command
                                                    nets are set up for each echelon in the battalion.
Military Police (MP) Company                        Separate tube-launched, optically tracked, wire
Command (VHF)                                       command link guided missile (TOW) company,
Used to exercise command and to coordinate ad-      platoon, and section command nets are also in-
ministrative and logistic functions.                cluded.

q MP company HQ                                     q Tank battalion/company/platoon HQ
q MP units                                          q Tank companies/platoons/tanks
q GCE provost marshal                               q Tank recovery on tank company command
q Traffic control/mobile units                      q TOW companies, platoons, sections, squads
                                                    q Liaison personnel
MP Company Tactical 1 (VHF)                         q Supporting and attached units
Used by MP commander to tactically control and
coordinate MP activities.


---

D-12 _______________________________________________________________________________________________ MCWP 6-22

LAR Battalion/Company/Platoon                         Reconnaissance Company/Platoon
Tactical 1 (VHF/HF)                                   Command (HF/VHF)
Used to exercise TACON of subordinate units.          Used to exercise command and coordinate admin-
Each echelon has its own tactical command             istrative and logistic support.
(TAC) net.
                                                      q Unit HQ
q Unit HQ                                             q Subordinate units
q Subordinate units and vehicles                      q Patrols/support aircraft/vehicles
q Recovery vehicles (company net)                     q Supporting units
q Liaison personnel                                   q Liaison teams at supported units
q Attached units
                                                      Infantry Regiment Command (HF)
LAR Battalion Command (HF/VHF)                        Used to exercise command and coordinate admin-
Used to exercise command and coordinate admin-        istrative and logistic support.
istrative and logistic support.
                                                      q Infantry regiment HQ
q Battalion HQ                                        q Infantry battalions
q Companies                                           q CSS area HQ
q Liaison personnel                                   q Landing support company
q Supporting/attached units                           q Attached units

LAR Battalion Mortar (VHF)                            Infantry Regiment Tactical 1 (VHF)
Used to request and control the fires of the mortar   Used to exercise TACON of subordinate units.
platoon.
                                                      q Infantry regiment HQ
q Forward observer teams                              q Infantry battalions
q Mortar platoon FDC                                  q Regimental TACLOG
q Mortar representative at the battalion HQ           q Supporting and attached units

Assault Amphibian Battalion/                          Infantry Regiment Intelligence (VHF)
Company/ Platoon Command                              Used for rapid reporting and dissemination of in-
(VHF).                                                telligence, collaborative planning of future intelli-
Used to exercise command and coordinate admin-        gence operations, and command and control of
istrative and logistic support. Each echelon has its  ongoing intelligence and reconnaissance opera-
own command net.                                      tions.

q Unit HQ                                             q Infantry regiment HQ
q Subordinate units/vehicles                          q Infantry battalions
q Recovery vehicles (company net)                     q Intelligence units (radio battalion SSU, coun-
q Liaison personnel
                                                         terintelligence team)
                                                      q Supporting and attached units
                                                      q Regimental observation post


---

Communications and Information Systems _____________________________________________________________ D-13

Infantry Regiment Fire Support                        q Weapons company
Coordination (VHF)                                    q Battalion TACLOG group
Used for regimental-level fire support coordina-      q Landing support or helicopter support teams
tion.                                                 q Battalion liaison officer(s)
                                                      q Supporting and attached units
q Infantry regiment FSCC
q Infantry battalion FSCC(s)                          Infantry Battalion Mortar (VHF)
q Artillery battalion(s)                              Used to request and control the fires of the 81-mm
q Other supporting HQ                                 mortar platoon.

Infantry Regiment Communications                      q Forward observer teams
Information Systems Coordination                      q 81-mm mortar platoon FDC
(VHF)                                                 q 81-mm mortar representative at battalion HQ
Used to coordinate, install, maintain, and restore
regimental communications-information systems         Scout-Sniper Command (VHF)
operations.                                           Used to exercise command and control of battal-
                                                      ion scout-sniper operations and to report recon-
q Infantry regiment HQ                                naissance information collected by deployed
q Infantry battalions                                 scout-sniper teams.
q Supporting and attached units
                                                      q Battalion S-2 and S-3 (fires)
TACP Local (VHF)                                      q Scout-sniper teams
Used to coordinate activities of the air liaison of-
ficer and forward air controllers.                    Rifle Company/Platoon Tactical (VHF)
                                                      Used to exercise TACON of subordinate units.
q Air liaison officer
q Forward air controllers                             q Rifle company or platoon HQ
                                                      q Rifle platoons or squads/fire teams
Infantry Regiment Local Security                      q Weapons platoon or sections
(VHF)                                                 q Company or platoon observation posts
Used to coordinate HQ main area, rear area, and       q Supporting and attached units
CP security elements. Multiple security nets will
be required.                                          Artillery Regiment/Battalion/Battery
                                                      Command 1 (HF, Regiment; VHF,
q HQ commander                                        Battalion/Battery)
q Security elements                                   Used to exercise command and coordinate admin-
                                                      istrative and logistic requests. May be used as an
Infantry Battalion Tactical 1 (VHF)                   alternate fire direction net.
Used to exercise tactical control and fire direction
of subordinate units.                                 q Artillery unit HQ
                                                      q Subordinate artillery units
q Infantry battalion HQ                               q Attached/reinforcing artillery units
q Rifle companies                                     q Division HQ


---

D-14 _______________________________________________________________________________________________ MCWP 6-22

Artillery Regiment Tactical 1/2                         q Artillery battalions
(VHF/HF)
Used as a supplemental means for the commander          Artillery Regiment Radar Telling (VHF)
to exercise command and control of subordinate          Used to exchange radar intelligence information
units when the command and fire direction nets          and for requests for surveillance of enemy coun-
become overloaded. This net may also be used by         terfire weapons. May also be used for registration
the artillery battalion liaison officers for the rapid  and adjustment of artillery fire.
exchange of fire planning data, counterfire infor-
mation, and other artillery liaison activities.         q Artillery regiment HQ
                                                        q Countermortar radar sites
q Artillery regiment HQ                                 q Artillery battalions and batteries
q Division HQ (forward, main, alternate CP)
q Artillery battalions                                  Artillery Regiment Survey/Metro (VHF)
q Attached artillery units                              Used to exchange survey, meteorological, and
q Supporting artillery units                            ballistic information and data between survey
q Artillery battalion liaison officers                  teams and artillery units.

Artillery Regiment/Battalion/Fire                       q Artillery regiment HQ
Direction 1/2 (VHF/HF, Regiment;                        q Artillery battalions/batteries
VHF, Battalion)                                         q Survey officers and teams
Used to exercise tactical fire direction of subordi-    q Division HQ
nate units by the assignment of fire missions, des-
ignation of units of fire, and conduct of time-on-      Artillery Battalion/Battery Conduct of
target missions. Subordinate units may use this         Fire (VHF)
net to request additional fires from organic and at-    Used by forward observers to request and adjust
tached artillery units. This net may also be used       artillery fire. Established when fire direction is
for the exchange of infantry fire planning data and     centralized; when fire direction is decentralized,
fire support coordination information when no           each battery in the battalion has a separate con-
other means is available.                               duct-of-fire net that terminates at the battery HQ.
                                                        There may be as many as four conduct-of-fire
q Artillery unit HQ                                     nets in each direct-support artillery battalion.
q Division FSCC
q Subordinate artillery units                           q Artillery battalion or battery HQ
q Attached/reinforcing artillery units                  q Battery forward observers
q Supporting artillery units                            q Battery liaison officers
q Artillery liaison officers                            q UAV squadron/detachment
                                                        q Artillery battalion liaison officers
Artillery Regiment Communications                       q Attached/reinforcing artillery units
Information Systems Coordination
(VHF/HF)                                                Aviation Combat Element Nets
Used to coordinate installation and restoration of
communications-information systems capabilities.        Wing radio nets that are replaced by static MUX
                                                        circuits will remain available as backups.
q Artillery regiment HQ


---

Communications and Information Systems _____________________________________________________________ D-15

ACE Command Net 1 (HF)                                q EW/C
Used to exercise command and coordinate admin-        q LAAD Battery CP/ADCP
istrative and logistic support.
                                                      Air Operations Control (HF/MUX)
q ACE HQ                                              Used by TAOC to request interceptor aircraft and
q MAGs                                                report friendly air defense situation information to
q Marine wing support group/squadron                  the TACC/TADC. Used to exchange information
q Marine air control group/detachment                 pertaining to combat air patrol availability, sta-
q Independent squadrons/battalions                    tioning and assignment, assignment and disposi-
q Attached units                                      tion of targets, intercept progress, SAM unit
                                                      status and employment, and aircraft/missile weap-
Tactical Air Command 1                                ons coordination. Multiple air operations control
(UHF-SATCOM/HF)                                       nets are normally required; one or more for each
Used by the tactical air commander to task subor-     TAOC in operation.
dinate elements to provide aircraft for missions.
                                                      q TACC/TADC
q TACC/tactical air direction center (TADC)           q TAOCs
q TAOC(s)                                             q LAAD Battery CP/ADCP
q DASC                                                q Early warning/control activities
q Marine aircraft groups/squadrons (as required)
q MATCDs                                              Antiaircraft Intelligence (HF/MUX)
q Early warning/control (EW/C)                        Used by SAM batteries to report targets acquired
                                                      by the battery surveillance radar. TAOC passes
Command Action (HF/VHF/MUX)                           selected early warning contacts to missile firing
Used for command-level coordination of antiair        units. Combined with the antiaircraft control net
warfare (AAW) through the exchange of informa-        when MUX is not available.
tion pertaining to missile battery employment, as-
signment of air targets, and the interceptor/missile  q TAOC(s)
coordination. Net functions may be performed          q Air defense fire units
over the air operations control net when an MCR       q EW/C
circuit is not established.                           q LAAD Battery CP/ADCP

q TACC/TADC                                           Combat Information/Detection
q TAOC(s)                                             (HF/MUX)
q EW/C                                                Used to report unidentified or hostile aircraft, in-
                                                      cluding initial contact reports, tracking, amplify-
Antiaircraft Control (HF/VHF/MUX)                     ing, and final disposition. Multiple combat
Used to control surface-to-air missile (SAM) bat-     information/detection nets may be established for
teries. Types of information passed on this net in-   multiple TAOCs.
clude: target assignments, fire direction orders,
weapons status commands, battery status reports,      q TAOC(s)
and progress-of-engagement reports.                   q Early warning/control activities
                                                      q LAAD Battery CP/ADCP
q TAOC(s)                                             q Air defense fire units
                                                      q DASC (as required)


---

D-16 _______________________________________________________________________________________________ MCWP 6-22

q MATCD (as required)                                Interface Coordination (HF/UHF VHF/
q TACC/TADC                                          MUX)
q Other reporting agencies                           Provides a means for command level coordination
                                                     in the employment of certain tactical weapons and
Handover/Cross Tell (HF/MUX)                         for interface command, control, and coordination.
Used to transfer aircraft control between air con-
trol agencies. Multiple nets can be established for  q TACC
the TAOC-early warning/control handover or           q Other-Service agencies
ground control intercept-ground control approach     q TAOC
handover. Functions may be combined on one net
if traffic permits.                                  TADIL A (HF/UHF)
                                                     Used to exchange digital data between various
q TAOC                                               TDSs. Types of data passed include air and sur-
q Early warning/control                              face tracks, weapons status, and selected orders
q ATC Detachment, MACS                               and functions. TADIL A operates as a star-netted
q MATCD                                              data link.
q Other-Service control agencies
                                                     q TACC
LAAD Battalion Command (HF)                          q TAOC(s)
Used to exercise command and coordinate admin-       q EW/C
istrative and logistic support.                      q Other-Service air control agencies

q LAAD battalion HQ                                  TADIL B (MUX)
q LAAD battery                                       Used in a point-to-point mode by using a full-du-
q Command Posts/ADCP                                 plex wire/multichannel path (a functional equiva-
                                                     lent to TADIL A). NATO designation: Link 11 B.
LAAD Weapons Control (HF)
Used for air defense warnings, weapons control       q TACC
conditions, and pertinent information concerning     q TAOC(s)
friendly, enemy, or unknown aircraft.                q EW/C
                                                     q MATCD
q Command Posts/ADCP                                 q Other-Service air control agencies
q LAAD battery
q LAAD platoon commanders/section leaders            TADIL C (UHF)
                                                     Used as a one- or two-way unsecure digital data
LAAD Team Control (VHF)                              link between air control agencies and interceptor
Provides air defense warnings, weapons control       aircraft. NATO designation: Link 4A.
condition and pertinent information concerning
friendly, enemy, or unknown aircraft to LAAD         q TAOC
teams. Multiple LAAD team control nets are nor-      q EW/C
mally employed.                                      q Interceptor aircraft
                                                     q Other-Service air control agencies (E-3/E-2C
q LAAD section leaders
q LAAD teams                                            aircraft, ship AAW facilities)


---

Communications and Information Systems _____________________________________________________________ D-17

Army Tactical Data Link (ATDL)-1                   q TACC
(MUX)                                              q TAOC
Used for secure, point-to-point exchange of air    q Other-Service air control agencies
breathing track data. Data passed includes refer-
ence tracks, missile status, and missile engage-   Radar Remote Coordination (VHF/HF)
ments.                                             Used to exchange early warning/control track and
                                                   control data.
q TAOC
q Early warning/control                            q TAOC
q Army Air Defense units                           q TAOMs
                                                   q Early warning/control sites
Ground-Based Data Link (VHF)
Used for air defense CP downlink of surveillance   Voice Product Net (HF/UHF/MUX)
information to short-range firing units.           Used to report/forward hostile target SIGINT in-
                                                   formation that is not reportable in a standard data
q ADCP                                             format.
q Short-range air defense
q Remote sensors                                   q TACC
                                                   q TAOC
Point-to-Point Data Link (MUX)                     q Other interfacing agencies
Used for one-way transmission of TBM nonair
breathing track data.                              ACE Communications Information
                                                   Systems Coordination (HF/VHF)
q ADCP                                             Used to coordinate installation and restoration of
q TPS-59 radar                                     communication capabilities.

Track Supervision Net (TSN)                        q Wing HQ
(HF/UHF/MUX)                                       q Marine aircraft groups
Used by surveillance personnel to exchange infor-  q MACGs
mation in order to maintain a clear picture. May   q Marine wing support group/squadron
be combined with Data-Link Coordination Net        q Independent squadrons/battalions
(DCN) for SCR operations.                          q Attached units

q TACC/TADC                                        Direct Air Support (HF/MUX)
q TAOC(s)                                          Used by DASC to request direct air support air-
q Antiaircraft operations center                   craft from the TACC. Information pertaining to
q Early warning/control activities                 aircraft stationing, fuel and ordnance status, and
                                                   progress of direct air support missions may be
Data-Link Coordination Net                         passed over this net.
(HF/UHF/MUX)
Used for maint/coord of data-link operation. May   q TACC/TADC
be combined with TSN for SCR operations. Gen-      q DASC
erally one DCN per TADIL-B/ATDL-1.


---

D-18 _______________________________________________________________________________________________ MCWP 6-22

Tactical Air Request/Helicopter                         q TAOC
Request (TAR/HR) (UHF-SATCOM/HF/                        q Early warning/control
VHF)                                                    q Interceptor aircraft
Used by forward ground combat units to request          q Other-Service AAW agencies
immediate air support from the DASC. Intermedi-
ate ground combat echelons (FSCCs) monitor this         Tactical Air Direction (TAD) (UHF/VHF)
net and may modify or disapprove a specific re-         Used to direct aircraft in the conduct of offensive
quest. The DASC uses the net to brief the request-      air support missions and to brief support aircraft
ing unit on the details of the mission. Target          on target information or assignment. Multiple
damage assessments and HRs may be passed over           TAD nets are required and are assigned to major
this net. Multiple TAR/HR nets may be required,         air control agencies by the DASC. This net is pri-
depending on the scope of close air support opera-      marily UHF with a secondary VHF capability
tions.                                                  available in some cases.

q DASC                                                  q DASC
q TACPs                                                 q UAV GCS
q HDC                                                   q TACP
q TAOC                                                  q Forward air controller (airborne)
q Tactical air coordinator (airborne)                   q Offensive air support aircraft
q Forward air controller (airborne)
                                                        Helicopter Direction (HD)
Tactical Air Traffic Control (TATC)                     (UHF/VHF/HF)
(UHF/VHF)                                               (Navy: inbound and outbound; USMC: control of
Used by the TACC/TADC, TAOC, and DASC to                helicopters in the objective area) Used by the
exercise control of all tactical and itinerant air-     HDC for positive control of inbound and out-
craft in the objective area. Used to pass aircraft re-  bound helicopters in the amphibious objective ar-
ports of launches by mission number, to clear           ea. The radar controller in the HDC uses these
aircraft to their assigned control agencies, to di-     nets to direct flight course and altitude of helicop-
vert aircraft as necessary, and to report missions      ters and holdings, let-downs, and climbout when
completed before landing. Multiple TATC nets            required. Both UHF/VHF and HF HD nets are
are required for each control agency.                   employed. Multiple HD nets are required and are
                                                        allocated by the DASC.
q TACC/TADC
q TAOC(s)                                               q DASC
q DASC                                                  q HDC
q EW/C                                                  q UAV GCS
q Fixed-wing aircraft                                   q Assault support coordinator (airborne)
q Helicopters                                           q Helicopters
q UAV ground control station (GCS)                      q Helicopter LZ Control Team (LZCT)
                                                        q Tactical air controller (airborne)
Fighter Air Direction (FAD) (UHF/VHF)                   q TACP
Control aircraft in the conduct of intercepts. Mul-
tiple FAD nets are required and assigned to major
control agencies.


---

Communications and Information Systems _____________________________________________________________ D-19

Tanker (UHF)                                         Search and Rescue (SAR) (UHF/VHF)
Used by in-flight refueling aircraft to communi-     Used to control and coordinate air rescue mis-
cate with the tanker. Used by TAOC to exchange       sions. Multiple SAR nets may be required de-
information with the tanker.                         pending on the number of concurrent SAR
                                                     missions.
q Tanker
q In-flight refueling aircraft                       q All elements within the command and control
q EW/C                                                  system
q TAOC
                                                     q Aircraft involved in SAR missions
Squadron Common (UHF/VHF)
Used for in-flight group or squadron aircraft, and   ATC Common (HF/MUX)
group or squadron HQ, communications. Each           Used to coordinate airspace management between
aircraft squadron has its own common net.            airfields.

q Group or squadron HQ                               q Air traffic controller(s)
q In-flight group or squadron aircraft
                                                     Approach Control (UHF/VHF)
Guard (UHF/VHF/HF)                                   Used to control air traffic approaching the termi-
Used by aircraft to declare an emergency. Used       nal airspace.
by air control agencies to advise aircraft of emer-
gency conditions or serious hazards to aircraft      q Approach controller
safety.                                              q Approaching aircraft

q TACC/TADC                                          Departure Control (UHF/VHF)
q TAOC(s)                                            Used to control air traffic departing the terminal
q DASC                                               airspace.
q MATCD
q EW/C                                               q Air Traffic Control Facility
q Fixed-wing and helicopter aircraft                 q Departing aircraft

Crash, Fire, and Rescue (VHF)                        Ground Control Approach (GCA)
Used to coordinate crash recoveries on or around     (UHF/VHF)
an airfield.                                         Used to provide bearing and altitude to approach-
                                                     ing aircraft.
q Crash crew
q ATC facility                                       q TATC
q Airfield operations                                q Aircraft
q Explosive ordnance disposal
q Medical facility                                   Ground Control (UHF/VHF)
q MP                                                 Used to control ground movement of vehicles,
                                                     aircraft, and personnel on the taxiways and run-
                                                     ways.


---

D-20 _______________________________________________________________________________________________ MCWP 6-22

q Ground control                                        q Convoy elements
q Aircraft                                              q Aerial observers
q Vehicles                                              q ACE HQ
q Personnel
                                                        Defense Meteorological Satellite
LZ Control (VHF/UHF)                                    Program Satellite Imagery
Used to control aircraft en route between the ini-      (SATCOM)
tial point and the LZ.                                  Used as an encrypted receive-only circuit to pro-
                                                        vide a direct readout of real-time satellite imagery
q LZCT                                                  from polar orbiting satellites of the Defense Mete-
q Aircraft en route between the initial point and       orological Satellite Program.

   the LZ                                               q Deployed Marine wing support squadron
q DASC                                                     (MWSS)
q Aircraft coordinator (airborne)
                                                        Fire Support Safety (HF)
LZCT Local (VHF)                                        Used to exchange information concerning the em-
Used to direct the activities of aircraft control per-  ployment of artillery, NGF, surface-to-surface
sonnel in each of the landing sites.                    missiles, and close air support aircraft to ensure
                                                        safety of all aircraft in the objective area.
q LZCT commander
q Landing site controllers                              q Air control agencies and elements

Air Base Security (VHF)                                 Fleet Facsimile (HF)
Used to coordinate security operations of expedi-       Used as a broadcast receive-only circuit to pro-
tionary airfields (EAFs).                               vide weather graphics produced by Navy regional
                                                        centers.
q MPs at the EAFs
                                                        q Broadcast from NCTAMS
Air Defense Alert (UHF)                                 q Deployed MWSS
Used to direct coordination and exchange of criti-
cal threat information and verbal warning to air-       Fleet Multichannel Broadcast
craft transiting minimum risk routes and                (UHF SATCOM)
operating near missile engagement zones.                Used as a receive-only circuit on channels 8 or 15
                                                        (environmental channels) of the satellite to pro-
q Ground-based air defense units                        vide weather bulletins produced by Navy regional
q Combat air patrol aircraft                            centers.
q Transiting to friendly aircraft
                                                        q Broadcast from NCTAMS
Convoy Control (VHF)                                    q Deployed MWSS
Used to control the various elements within a con-
voy.                                                    Goldwing Communications (HF)
                                                        Used as a secure, in-theater, joint net that may be
q Convoy commander                                      used for voice traffic but is primarily for transmit-
                                                        ting and receiving alphanumeric weather data.


---

Communications and Information Systems _____________________________________________________________ D-21

q Other-Service meteorological and oceano-         q Assault support watch officer
   graphic agencies
                                                   Tactical Alert (HF)
q Deployed MWSS                                    Used for rapid dissemination of air-raid warnings.

Landing Signal Officer (UHF)                       q MAGTF HQ
Used to coordinate control of the landing pattern  q GCE/ACE/CSSE HQ
with the control tower and to control aircraft in  q Air control agencies
the landing pattern. A tower secondary frequency
is normally used for this requirement.             Television Infrared Observation
                                                   Satellites Imagery (SHF)
q ATC Facility                                     Used as an unencrypted receive-only circuit to
q Aircraft in pattern                              provide a direct readout of real-time satellite im-
q Landing signal officer                           agery from the National Oceanographic Atmo-
                                                   spheric Administration.
Medical Evacuation (MEDEVAC)
Coordination Net (VHF)                             q Deployed MWSS
Used to coordinate MEDEVACs.
                                                   Tower Hot (HF/VHF)
q Requesting unit                                  Used by ATC to inform the TACC of launched
q Evacuation helicopters                           aircraft.
q Medical facilities
                                                   Tower Primary (UHF/VHF)
Pilot to Metro (UHF)                               Used by controller to issue traffic advisories and
Used for exchange of meteorological information.   aircraft clearances within the EAF.

q Flying aircraft                                  Tower Secondary (UHF/VHF)
q Weather detachment at EAF                        Overflow traffic from the tower primary.

Rear Area Security (VHF)                           Weather Radar Net (AN/FPS-106)
Used to coordinate security operations of groups/  Used as a single-site radar that provides a visual
squadrons/attached units at EAFs and air control   depiction of precipitation and storm structure
agency locations.                                  within a 200-nautical-mile radius of its location.

q Security element task organized by the units at  q Deployed MWSS at the EAF
   the EAFs and air control agency locations
                                                   Wing Intelligence (HF)
Strip Alert (HF/VHF)                               Used for rapid reporting and dissemination of in-
Used to coordinate fixed-wing aircraft and heli-   telligence information.
copter operations at the EAF.
                                                   q ACE G-2
q Air boss                                         q Group S-2
q Tactical air watch officer                       q Squadron S-2


---

D-22 _______________________________________________________________________________________________ MCWP 6-22

MAW Defense Special Security Com-                    UAV Secondary Uplink Control
munications System Entry (UHF-SAT-                   (G-Band)
COM/HF/MUX)                                          Used to control air vehicle and payload if primary
Used to provides the wing commander with an          link control is lost.
SCI data communication capability with external
agencies. The communications path is provided        q Ground data terminal
by the communications company, and the termi-        q Launch and recovery
nal equipment and personnel are provided by the      q Air vehicle
MAW SSCT.
                                                     UAV Telemetry Downlink (G-Band)
q SSCT                                               Used to provide real-time video display of target
                                                     area and downlink flight control data.
Wing Logistic Net (HF)
Used to request logistic support.                    q GCS
                                                     q Launch and recovery site
q ACE G-4                                            q Remote video terminal teams
q Group S-4                                          q Air vehicle
q Squadron S-4
                                                     Combat Service Support Element
Link-1 (NATO) (MUX)                                  Nets
Used for point-to-point interface with NATO Air
Defense Ground Environment (NADGE) agen-             CSS Command 1/2 (UHF-SATCOM HF/
cies in a full-duplex data link to exchange air de-  VHF)
fense information.                                   Used to exercise command and coordinate admin-
                                                     istrative and logistic support.
q TACC/TADC
q TAOC                                               q Unit HQ
q NADGE agencies                                     q General support group
                                                     q Direct support group
UAV Command Net (HF/VHF/UHF)                         q CSS detachments
Used to coordinate UAV activities.
                                                     CSS Alert/Broadcast (HF)
q UAV squadron/detachment HQ                         Used for alert warning or general traffic pertain-
q GCS                                                ing to all (or a majority) of the units. Messages
q Launch and recovery site                           not of an alert warning type will be consecutively
q Remote video terminal teams                        numbered at the time of transmission.

UAV Primary Uplink Control (G-Band)                  q Unit HQ
Used to control air vehicle and payload.             q General support group
                                                     q Direct support group
q Ground data terminal                               q CSS detachments
q Launch and recovery
q Air vehicle


---

Communications and Information Systems _____________________________________________________________ D-23

CSS Damage Control (HF)                               q CSS detachments
Used for damage assessment information that is        q Supported unit(s)
exchanged subsequent to an enemy attack with
mass-destruction means. Evacuation and casualty       LFSP Command (HF/VHF
assistance for stricken units may also be directed    Used to exercise command and coordinate admin-
over this net.                                        istrative and logistic support of own units. This
                                                      net is also used to coordinate the movement of
q Unit HQ                                             supplies being landed over multiple colored
q General support group                               beaches.
q Direct support group
q CSS detachments                                     q LFSP HQ
                                                      q Shore party/helicopter support groups
CSS Communications Information                        q Shore party/helicopter support team
Systems Coordination (HF/VHF)
Used to coordinate, install, maintain, and restore    Shore Party Control (VHF/HF)
CSSE communications and information systems           Used to coordinate the flow of supplies and per-
operations.                                           sonnel. A separate net is established for each col-
                                                      or of beach.
q Unit HQ
q General support group                               q Shore party group (operating the beach)
q Direct support group                                q Shore party teams
q CSS detachments                                     q TACLOG group of supported units using indi-

CSS Local (VHF)                                          cated beach
Used to coordinate activities within CSS local area.  q Shore party liaison teams with supported units
                                                      q LFSP HQ
q Unit HQ                                             q MAGTF TACLOG
q General support group
q Direct support group                                Engineer Support Battalion
q CSS detachments                                     Subordinate Unit Command
                                                      (HF)
CSS Security (VHF)                                    Used to exercise command and coordinate admin-
Used to coordinate security elements in the CSS       istrative and logistic requests of subordinate units.
operating areas.
                                                      q Unit HQ
q CSS HQ commandant                                   q Subordinate units
q Security elements as directed by HQ comman-
                                                      Motor Transport Battalion Company
   dant                                               Command/Convoy Control (VHF/HF)
                                                      Used to exercise command and coordinate admin-
CSS Request (UHF-SATCOM/VHF)                          istrative and logistic requests of subordinate units.
Used to receive requests from supported units and     Used to control and coordinate convoys.
provide status.
                                                      q Unit HQ
q CSSOCs                                              q Convoy commander


---

D-24 _______________________________________________________________________________________________ MCWP 6-22

q Convoy front                                         q Medical unit HQ
q Convoy rear                                          q MEDEVAC ambulances/vehicles
                                                       q Evacuation/treatment facilities
Medical Battalion Command (VHF)                        q Requesting units
Used to exercise command and coordinate admin-
istrative and logistic requests of subordinate units.  Medical Battalion Evacuation
                                                       Coordination (Air) (VHF)
q Medical battalion HQ                                 Used to coordinate air MEDEVAC.
q Medical companies
q Hospital companies                                   q Medical unit HQ
                                                       q MEDEVAC aircraft
Medical Battalion Evacuation                           q DASC
Coordination (Ground) (VHF)                            q Evacuation/treatment facilities
Used to coordinate ground MEDEVAC.                     q Requesting units


---

                    Appendix E

Information Systems Directory

 Section I

Overview

An information systems directory is one of the        Emergency Numbers
most critical documents pertaining to
CIS planning. It shows a subscriber how to use        Emergency numbers provide the subscriber rapid
the system to the maximum extent possible with-       access to the numbers of certain critical agencies
out assistance from communications or data sys-       (e.g., aid station, combat operations center, force
tems personnel. The principal function of this        protection platoon). These numbers should also
directory is to provide guidelines from which CIS     be listed in the organizational listing.
officers and telephone systems officers may pro-
duce a directory for their commands/organiza-         Index
tions. Section II of this appendix is a sample
directory for II MEF. It supports the design char-    An index is an optional feature that serves as a ta-
acteristics of the MAGTF tactical communica-          ble of contents. The size of the directory deter-
tions network.                                        mine the need for an index.

Security of Information                               General Instructions

The information systems directory for a given or-     These instructions discuss the differences in the
ganization, even one as large as the MEF, need        types of telephone equipment that may be used by
not be classified if the directory contains informa-  a unit during an operation. The telephone equip-
tion derived from unclassified sources. For exam-     ment should include tactical equipment such as the
ple, a listing of organizations with subscriber       KY-68, TA-954, and TA-1042, STU-III’s, com-
numbers that are consistent with this appendix        mercial equipment, and cellular telephones. Each
and are unchanging from operation to operation        has its own special operating instructions.
need not be classified. However, an information
systems directory could be used as a source of in-    Operating Instructions
formation for enemy intelligence collection.
Therefore, an information systems directory           These instructions tell subscribers how to effec-
should be handled as For Official Use Only if it      tively use the tactical automated switching system
contains CIS architecture diagrams or if it will be   (TASS) and commercial systems. They should list
used in an operation outside of CONUS.                the unique operating characteristics of each tele-
                                                      phone system.
Cover
                                                      Dialing Instructions
A cover can specify which organization created
the directory, for what community of users the di-    These instructions will aid subscribers in using
rectory is intended, and the effective period for     the different telephone systems found in a MEF-
the directory.                                        level exercise. Instructions should give enough


---

E-2 ________________________________________________________________________________________________ MCWP 6-22

detail to allow unfamiliar subscribers to effective-  q Situations which gravely affect the internal se-
ly use the system. Instructions should not change        curity of the United States.
too much from unit-to-unit or from operation-to-
operation, as the equipment characteristics do not    q Civil Defense actions concerning direction of
change. Instructions do not describe every avail-        our population and their survival.
able subscriber feature of the switching system.
This technical information may be found in TMs        q Disasters or events of extensive seriousness
or the CJCSM 6231 series for the specific equip-         having an immediate and detrimental effect on
ment.                                                    the welfare of the population.

Precedence Subscribers                                q Vital information having an immediate effect
                                                         on aircraft, spacecraft, or missile operations.
Circuit switched calls within a network are pro-
cessed according to five levels of precedence. The    Flash (F)
precedence levels follow in ascending order.
                                                      Flash has precedence over and preempts immedi-
Routine (R)                                           ate, priority, and routine calls. Flash precedence
                                                      is reserved generally for telephone calls pertain-
Routine has no precedence over any other call and     ing to—
is handled sequentially as placed by the calling
party. There is no preemption of any lines. Rou-      q Command and control of military force essen-
tine precedence designation applies to normal of-        tial to defense and retaliation.
ficial government communications.
                                                      q Critical intelligence essential to national sur-
Priority (P)                                             vival.

Priority has precedence over any other telephonic     q Conduct of diplomatic negotiations critical to
call of lower precedence (routine calls). Priority       the arresting or limiting of hostilities.
precedence is reserved generally for telephone
calls by parties requiring expeditious action or      q Dissemination of critical civil alert information
requiring essential information for conducting           essential to national survival.
government operations.
                                                      q Continuity of Federal Government functions
Immediate (I)                                            essential to national survival.

Immediate has precedence over and will preempt        q Fulfillment of critical United States internal se-
routine and priority calls. Immediate precedence         curity functions essential to national survival.
is reserved generally for telephone calls pertain-
ing to—                                               q Catastrophic events of national or international
                                                         significance.
q Situations that gravely affect the security of na-
   tional and allied forces.                          Flash Override (FO)

q Reconstitution of forces in a post attack period.   Flash override has precedence and preempts all
                                                      other types of telephone calls. The application of
q Intelligence essential to national security.        the FO capability is available to—

q Diplomatic negotiations to reduce or limit the      q The President of the United States, Secretary of
   threat of war.                                        Defense, and Joint Chiefs of Staff.

q Implementation of Federal Government actions        q Commanders of unified and specified com-
   essential to national survival.                       mands when declaring either Defense Condi-
                                                         tion One or Defense Emergency.

                                                      q CINCNORAD when declaring either Defense
                                                         Condition One or Air Defense Emergency and
                                                         other national authorities as the President may
                                                         authorize.


---

Communications and Information Systems ______________________________________________________________ E-3

Dialing Precedence Calls                             Area Code (MYX)

The precedence indicator (P, I, F, or FO) is dialed  An area code is a number that identifies an area or
from the subscriber’s telephone terminal keypad,     region of switches. Area codes are only assigned
and is dialed first in any dialing sequence. If no   during very large military operations in which
precedence is dialed, the call is processed as rou-  several Services are working together in a joint
tine. The unit CIS officer (in accordance with       operation. DISA DSN area codes are assigned by
standard operating procedures) determines which      geographical areas as follows:
telephones will have precedence capability. The
precedence capability is programmed into the cir-          312 - CONUS
cuit switch memory. If a subscriber has a prece-           313 - Caribbean
dent capability, any precedence indicator can be           314 - Europe
chosen in a dialing sequence, up to the level that         315 - Pacific
has been authorized. A subscriber attempting to            317 - Alaska
use precedence levels higher than that authorized          318 - CENTCOM
will have the call processed at the maximum au-
thorized level. Both loops and trunks are preempt-   Unique Area Codes
able. A call cannot preempt a loop or trunk in the
switch that is handling a call of equal or higher    If a very large military operation is conducted, all
precedence.                                          of the forces in a theater might be assigned their
                                                     own unique area code (300 for example). Depend-
Numbering Plan                                       ing on which part of the world they are deployed
                                                     to, if a military operation becomes extremely
The tactical telephone numbering plan is based on    large, the MARFORs have several area codes re-
a 13-digit numbering scheme and is structured in-    served for their use.
to four parts:
                                                     MARFOR ACOM     204

                                                     MARFOR CENTCOM  304

                                                     MARFOR PACOM    804

                                                     MARFOR SOCOM    408

 9YX     MYX     PRSL        GXX                     Inter-Area Dialing

      |       |        |           |                 When calling a subscriber who is serviced by a
      |       |        |           |                 different area code (MYX), the full ten-digit num-
                                                     ber must be dialed (MYXPRSLGXX). As with di-
NATO     Area    Switch   Subscriber                 aling another PRSL, the same 9 or 91 escape code
Code     Code    Code      Number                    must be used. The number dialed will be either—

G = 1–8          PR = 32–39                                 9 MYX PRSL GXX
M = 2–8          SL = 00–99                                              or
X = 0–9
Y = 0–1                                                    91 MYX PRSL GXX

NATO Code (9YX)                                      Switch Code (PRSL)

NATO members have reached a standardization          A switch code is a unique number that identifies
agreement (STANAG) to use a unique three-digit       one particular circuit switch. It is composed of
national identification (NI) number. The NI code     two parts; the first two digits are the primary zone
for tactical U.S. forces is 914. Calls to NATO       (PR) and the last two digits are the switch locator
subscribers can only be made from the medium         (SL). The switch code is also called the “PRSL”.
unit level switch (AN/TTC-42) when it is con-        All circuit switches must be assigned a switch
nected to the AN/TTC-39 large circuit switch.        code, whether operating independently or as part


---

E-4 ________________________________________________________________________________________________ MCWP 6-22

of a circuit switched network. A four-digit PRSL      subscriber numbers are listed together in the in-
switch code within a network is also called a 4/3     formation systems directory, which is published
numbering plan, since the switch code is four dig-    by the unit CIS officer prior to an operation.
its and the subscriber number is three digits. The    When one subscriber wishes to call another sub-
4/3 numbering plan is preferred in military circuit   scriber who is on the same circuit switch, he only
switched systems since it allows for more circuit     needs to dial the subscriber number (GXX).
switches with fewer subscribers as compared to a
commercial switching system which uses a 3/4          Global Block Numbering Plan
numbering plan. A commercial switching system
has fewer switches with more subscribers, hence       The Marine Corps will begin using the GBNP in
the 3/4 code.                                         FY 99 to incorporate all of its switches into a joint
                                                      network. The GBNP will identify all of the ser-
Interswitch Dialing                                   vices with a unique, service-managed block of
                                                      numbers, simplify network management into a
When calling a subscriber who is serviced by a        global network, ensure nonduplication of num-
different circuit switch (PRSL), the full seven-      bers within an area of responsibility, and identify
digit number must be dialed (PRSL-GXX). But           databases and subnetworks within the assigned
first, the circuit switch must be told that the num-  block of numbers. After implementing the GBNP,
bers dialed are PRSL numbers and not subscriber       it is expected that a block of numbers (PRSL
numbers. This is done with a one or two digit spe-    numbers between 3200–3900) will be associated
cial “long-distance” or escape code. Some circuit     with each major subordinate command (MSC)
switches require a “9” or a “91” code prior to the    and switch type. MSCs should coordinate with
seven digit subscriber number. This is analogous      their respective preaffilation managers to deter-
to dialing a “1” for long distance on a telephone at  mine their subscriber numbers.
home or in the office. The number dialed will be
either—                                               LAN Instructions

       9 - PRSL - GXX                                 These instructions address how to use the secured
               or                                     (SIPRNET) and unsecured (NIPRNET) LAN. In-
                                                      structions should describe all LAN services avail-
      91 - PRSL - GXX                                 able, including electronic mail, Internet access,
                                                      message dissemination, and COMPUSEC.
PRs will be assigned by the higher headquarters
J6/G-6, according to the Global Block Numbering       Information Systems Listing
Plan (GBNP) matrix found in CJCSM 6231.02.
Some higher level switches in the military can use    This listing provides tactical, commercial, DSN,
a 3/4 numbering plan, which uses a three-digit        host nation, pager, and cellular telephone num-
switch code (NNX) called a local exchange code,       bers for subscribers at every organizational loca-
vice a PRSL code. The full subscriber number          tion. It also provides subscriber’s SIPRNET and
then takes on the form NNXGXXX.                       NIPRNET LAN addresses and any operational
                                                      webpage addresses. The listing should include ad-
Subscriber Number (GXX)                               jacent major organizations of other services in a
                                                      joint operation.
The subscriber number is a three-digit number be-
tween 100 and 899. Every telephone instrument
that is connected to a circuit switch, whether auto-
matic or manual, must be assigned a number. All


---

Communications and Information Systems ______________________________________________________________ E-5

                                                Section II

               Sample II MEF Information Systems Directory

   This section contains a representative information systems directory designed according to the prin-
   ciples outlined in section 1. This sample directory used II MEF as the notional unit. The directory,
   however, may not accurately reflect the actual composition of the present II MEF, nor does it list all
   of the potential subscribers to the system. CISOs should consult with the GBNP and their unit’s T/Os
   and SOPs before preparing a directory to ensure that subscriber numbers are accurate.

                                                    CLASSIFICATION

                                          II MEF EXERCISE
                           INFORMATION SYSTEMS DIRECTORY

                                      Effective Date 210800Z October XXXX

EMERGENCY NUMBERS

Operator                  000
Combat Operations Center  3420-300
Headquarters Commandant   3420-807
Force Protection Platoon  3420-160

Telephone  3421-613
Help Desk  3420-605

LAN
Help Desk

TELEPHONE SECURITY IS EVERYONE’S RESPONSIBILITY. DO NOT
DISCUSS CLASSIFIED INFORMATION ON NONSECURE TELEPHONES!
OFFICIAL DOD TELEPHONES ARE SUBJECT TO MONITORING AT ALL
TIMES FOR COMMUNICATION SECURITY PURPOSES.

                              CLASSIFICATION


---

E-6 ________________________________________________________________________________________________ MCWP 6-22

                                                      INDEX

   EMERGENCY NUMBERS ..................................................................................................................
   GENERAL INSTRUCTIONS ...............................................................................................................
   OPERATING INSTRUCTIONS ...........................................................................................................
   DIALING INSTRUCTIONS .................................................................................................................
   PRECEDENCE SUBSCRIBERS ..........................................................................................................
   NUMBERING PLAN............................................................................................................................
   LAN INSTRUCTIONS .........................................................................................................................
   INFORMATION SYSTEMS LISTING ................................................................................................

                                        GENERAL INSTRUCTIONS

   TASS allows most subscribers to place local and long distance telephone calls without operator as-
   sistance. By using the following instructions telephone service will be quicker and more responsive
   to your needs. Use the following telephones with digital switching equipment:

   TA-1042 Digital Non Secure Voice Terminal (DNVT). This is the ruggedized green push but-
   ton telephone. The LED will blink and a ring will be sounded when the phone receives a ring. A
   knob located on the phone will adjust ringer volume. Ensure that the ear-piece is properly reinserted
   into the body of the phone after the call is completed. DO NOT use the push-to-talk switch on the
   handset at anytime. This will disrupt your conversation.

   KY-68 Digital Secure Voice Terminal (DSVT). This is the ruggedized green push button tele-
   phone. Once filled, the KY-68 holds the highest classification because of the COMSEC key loaded
   inside and must be handled accordingly. After the phone has received its crypto fill it requires no us-
   er adjustments other than adjusting the ring volume. ANY OTHER ADJUSTMENTS TO THE RE-
   MAINING CONTROLS MAY ZEROIZE THE TELEPHONE RENDERING IT INOPERATIVE.
   If this occurs notify the TELEPHONE TROUBLE DESK at 411.

   SECTEL MMT 1500. This is the Motorola 1500 STU III in that it can be operated from a garrison
   telephone or the tactical phone system. The MMT can talk unsecured to any type of phone on the
   tactical system (the MMT can only be connected to the tactical switch digital line termination unit
   (DLTU) with the DNVT adapter). The MMT can only go secure with another STU-III. The dialing
   instructions for the MMT are the same as any tactical instrument on the network unless dialing
   through an IWF.

   INTER-WORKING FUNCTION (IWF). This device allows tactical SECTEL MMT 1500 STU-III
   subscribers to place secure calls to commercial STU-III subscribers. The IWF is programmed as a
   DNVT within the ULCS network and is direct access service (DAS) to the TTC-42 switch and con-
   nected to a single Dial Central Office (DCO) line. Access the IWF by dialing its tactical number from
   a SECTEL MMT 1500 STU-III within the tactical network, receiving a second dial tone (from DCO)
   and then dialing the commercial telephone number. Once this connection is made, both subscribers
   may go secure.

   The only way that commercial subscribers are able to go secure with tactical STU-III subscribers is
   by dialing through the IWF.


---

Communications and Information Systems ______________________________________________________________ E-7

                                      OPERATING INSTRUCTIONS

The KY-68 and the TA-1042 may receive and initiate calls with any telephone installed within the TASS.
The KY-68 has some unique operation characteristics that are as follows:
q Under the handset of the phone is a 3 position pole type plunger which automatically sets itself in the

   secure mode when the phone is hung up.
q All calls will be initiated in the secure mode; pick up the handset and dial the required number you de-

   sire.
q If the party you are calling does not have a secure voice telephone (KY-68), you will hear a continuous

   heartbeat sound in the receiver and the NSW (Nonsecure Warning) will flash. Simply pull up on the
   plunger and your phone will go to the unsecured mode. Note: The NSW light will remain until you
   terminate the call.
q The KY-68 will automatically reset itself to the secure mode when you hang up.

DSVT’s cannot talk secure with STU-III telephones. They are not compatible in the secure mode.

Access Through Defense Switched Network (DSN)

The II MEF TASS will have six DSN trunks available through the AN/TTC-42 switchboard. DSN use by
subscribers will be on “A FIRST COME, FIRST SERVED” basis. Precedence subscribers will have the
ability to preempt other subscribers when a precedence call is initiated.

                                        DIALING INSTRUCTIONS

q To dial a tactical telephone number from your tactical phone, dial the following:
   • AN/TTC-42 subscribers: Dial 9 and the seven digit extension (9-XXXX-XXX).

q To dial DSN telephone numbers aboard Camp Lejeune from your tactical phone, dial the following:
   • AN/TTC-42 subscribers: Dial 5C (wait for tone)-451-XXXX-C. (XXXX = the four digit DSN num-
      ber) or dial for the operator at 000.
   • SB-3865 subscribers: Dial 91 (wait for the tone)-5C (wait for the tone)-451-XXXX-C or dial the op-
      erator at 000.

q To dial a tactical telephone number from a DSN number or to dial a TASS Operator from a DSN num-
   ber, take the following steps:
   • Dial the tactical switch operator at one of the following numbers: 6131 or 6174.
   • Give the operator the seven digit number (PRSL-XXX) for the subscriber you wish to reach. Exam-
      ple: 3469-633.

Note: TASS subscribers with an assigned higher precedence may start the dialing sequence with the
appropriate level precedence.

   • If any problem occurs during the dialing process, call the operator by dialing 000 or for telephone
      trouble calls within your switching network, dial the unit’s corresponding telephone trouble desk
      number.


---

E-8 ________________________________________________________________________________________________ MCWP 6-22

                PRECEDENCE SUBSCRIBERS

The tactical circuit switch (AN/TTC-42) is capable of processing five levels of precedence. The prece-
dence levels in ascending order are—

ROUTINE    (R)

PRIORITY   (P)

IMMEDIATE  (I)

FLASH      (F)

FLASH OVERRIDE (FO)

The maximum precedence level authorized to a particular terminal is assigned by a classmark. The prece-
dence indicator (P,I,F,FO) is dialed first in any dialing sequence. If no precedence is dialed, the call is
processed as routine. Subscribers can initiate calls at a precedence level lower than the maximum autho-
rized. Once a call is established, the originator’s precedence level is maintained, regardless of the level
authorized to other participating parties. Preemption is employed to calls of higher priority are given pref-
erence over lower precedence calls. Initiate the call with the assigned precedence, and the call will be
completed on a priority basis. Example: P600, F300, etc.

Note: When a priority is used it will disconnect any subscriber who has lower precedence. PLEASE
USE THEM WITH DISCRETION.

                                                        WARNING

Remember that the telephone network is NOT SECURE. Do not discuss classified material on any
telephone UNLESS YOU ARE USING A KY-68 OR A STU-III TELEPHONE IN THE SECURE
MODE. Even calls made within the command post are susceptible to interception. Practice good
communications security!


---

Communications and Information Systems ______________________________________________________________ E-9

                  NUMBERING PLAN

The Primary Zone (PR) is the primary identification number that identifies subscribers in the geographic
area.

Switch Location (SL) assignments are listed for all commands and organizations within II MEF and east
coast units. Spare SL numbers are provided at different echelons and for task organization assignments.

The following PR and SL are assigned to II MEF units participating in the MEF Exercise:

                                  PR  SL

II MEF CE                         34  20

EIGHTH COMM BN                    34  21

2D FSSG                           35  77

MED BN                            35  80

8TH ESB                           35  82

2D LSB                            35  84

8TH MT BN                         35  86

2D MAW/MWCS-28 DET B (CHRY PT)    35  27

2D MAW/MWCS-28 DET A (BOGUE FLD)  35  30

2D MAW (NEW RIVER)                35  32

2D MAW/MWSS-274                   35  42

2D MAW/MWSG-27                    35  36

2D MAW/MWSS-271                   35  40

2D MAW/MASS-1                     35  33

2D MAW/MWSS-272                   35  41

2D MARDIV                         34  69

2D MAR REGT                       34  76

6TH MAR REGT                      34  77

8TH MAR REGT                      34  78

10 MAR REGT                       34  79

2D TANK BN                        34  88

2D AMPHIBIOUS ASSAULT BN          34  89

2D LAR BN                         34  90

2D COMBAT ENG BN                  34  91


---

E-10 _______________________________________________________________________________________________ MCWP 6-22

                                           LAN INSTRUCTIONS

Disclaimer. The United States Marine Corps, while recognizing certain commercial products in this di-
rectory, does not endorse any of the products listed here. Technology and the marketplace drive the prod-
ucts that are available. The USMC will use the best technology or tool for the job at any given time.

LAN Overview

II MEF personnel will have access to both the nonsecure internet protocol router network (NIRPNET) and
the secure internet protocol router network (SIPRNET) during this exercise. NIPRNET and SIPRNET ad-
dresses are located on the information systems listing at the end of this directory.

The overall LAN coordinator for the exercise will be the II MEF Assistant Chief of Staff G-6 Information
Systems Management Officer (ISMO), under the cognizance of the II MEF AC/S G-6. The ISMO will be
assisted by communications and information systems officers and personnel at each of the Major Subor-
dinate Commands (MSCs). LAN questions and problems should be addressed to the LAN help desk at
3420-605.

II MEF personnel will be using a variety of computers loaded with Microsoft WindowsNT® network
and Exchange® software applications during this exercise. WindowsNT® is a multipurpose operating
system that integrates a variety of network services. The network services it provides are designed to ad-
dress requirements in many categories. Windows NT® will be used to connect all of the units within the
MEF.

Software Applications

II MEF computers have been installed with several software application packages, which include
Microsoft Outlook® and Internet Explorer®, and Message Dissemination System (MDS).

Microsoft Outlook®. This application is used for all electronic mail applications, including calendar and
scheduling features, and is accessed via the desktop icon.

Microsoft Outlook® is a desktop information management program that helps the user organize and
share information on your desktop and communicate with others. Use Outlook® to manage your messag-
es, appointments, contacts, and tasks, as well as track activities, view and open files, and share informa-
tion with others.

In Outlook®, information is organized in folders. When the user first starts Outlook®, the Inbox folder
opens. Use the Inbox to read and send mail messages, meeting requests, and task requests.

To create a message, point to New on the file menu, and then click Mail Message. Enter recipient names
in the To and Cc boxes. Type the subject of the message in the subject box, and then type the message in
the text box. When you are ready to send the message, click Send.

To quickly go to another part of Outlook®, click a Shortcut on the Outlook® Bar to the left of the Inbox.
For example, click Calendar to open your Calendar folder. The Folder Banner (horizontal bar above the


---

Communications and Information Systems _____________________________________________________________ E-11

information viewer) shows the name of the folder you have open. To see a complete list of your folders,
click the folder name in the Folder Banner.

The user can use Outlook® as a substitute for Windows Explorer®. To view the files on the hard disk,
click Other on the Outlook® Bar, and then click My Computer, My Documents, or Favorites.

Outlook® uses views to sort and organize items in a folder. To switch to a different view, click a view in
the Current View box on the Standard toolbar.

If Microsoft Word® is installed on a computer, use Word® and Outlook® together to create powerful e-
mail messages. To turn Word® as your editor on or off, close this message and click Options on the
Tools menu. On the E-mail tab, select or clear Use Microsoft Word® as the e-mail editor. With Microsoft
Word® as your e-mail editor, you can use features such as autocorrect, spell it, bullets and numbering,
document map, and highlighter to create your e-mail messages.

The Internet (MS Internet Explorer®). This application is used for all Web access and is accessed via
the desktop icon.

The Internet is a collection of computer networks that connects millions of computers across the United
States and around the world. Explorer® enables the user to connect to the internet to gain access to vast
stores of information on these computers. Double click on the Explorer® icon to access the internet.
When a frequently used URL is typed into the Address bar, Explorer® will complete the address. In addi-
tion, Explorer® can search through incorrectly typed addresses in order to find a match.

Users can search for web sites using the Explorer® bar. Click on the search button on the toolbar: the Ex-
plorer® bar appears in the left side of the browser window. Then click on a link to view that page on the
right side of the screen while viewing the list of search documents on the left. It is also possible to
browse through favorite sites and history folders, channels, or documents.

Users can find information on the web in a variety of ways. When the search button is clicked on the
toolbar, the Explorer® bar appears to the left of the window. It provides access to a number of search ser-
vices that offer different kinds of searching capabilities. To find information quickly, type GO, Find, or
?, followed by a word or phrase right in the address bar. Explorer® immediately starts a search for the
topic. Then, after the user goes to a specific web page, the user can search for the specific text on that
page.

Message Dissemination System (MDS). MDS has been installed on II MEF computers for this exercise.
The primary function of MDS is the automatic dissemination of Organizational Automatic Digital Net-
work (AUTODIN) messages to various organizational users as MD Users or E-Mail Addressees. This au-
tomatic dissemination is based on the Office Code Distribution provided by the Originator of the message
in the form of Office Codes assigned to Plain Language Addresses (PLAs) in the heading of a message,
and/or Profiles. Messages are made available to MD for processing either electronically via a GateGuard
System or on diskette produced by a GateGuard, Personal Computer Message Terminal (PCMT), or other
systems using the standard message diskette format.


---

E-12 _______________________________________________________________________________________________ MCWP 6-22

LAN Security

The internet works by sending information from computer to computer until the information reaches its
destination. When information is sent from one point to another, every computer in between has an op-
portunity to look at what’s being sent. This can pose a security problem. Users must understand that clas-
sified information must not be sent on unsecured networks. Users should practice good computer security
(COMPUSEC) procedures while using the Internet.


---

Communications and Information Systems _____________________________________________________________ E-13

                 II MEF Information Systems Listing

                          Effective Date: 210800Z October XXXX
Note: The tactical PRSL numbers listed below are based on a draft GBNP switch block proposal
dated 26 Aug 98. CISOs are highly encouraged to check with their unit PAL managers before as-
signing tactical numbers.

                                                                E-MAIL ADDRESS

      Subscriber     Tactical         Commercial DSN            NIPRNET          SIPRNET
                                                                Domain:          Domain:

           II MEF                                               fwd.iimef.usmc.  fwd.iimef.usmc.
     CMD ELEMENT                                                mil              smil.mil
      3420 (TTC-42)

CG                   3420-106 (DSVT)                  751-9475  cg@domain        cg@domain

CELLULAR                              (910) 340-8230

C/S                  3420-103 (DSVT)

HQ CMDT              3420-807 (DNVT)

SJA                  3420-104 (DNVT)

PAO                  3420-105 (DSVT)

SGT MAJ              3420-109 (DNVT)

           G-1

AC/S G-1             3420-114 (DSVT)                            g1@domain        g1@domain

PERSONNEL OFFICER 3420-110 (DSVT)

ADJUTANT             3420-112 (DSVT)

           G-2

AC/S G-2             3420-203 (DSVT)                            g2@domain        g2@domain

G-2 CHIEF            3420-209 (DSVT)

CIC WATCH OFFICER    3420-225 (DSVT)

COLLECTIONS OFFICER 3420-211 (DSVT)

TARGET OFFICER       3420-245 (DSVT)

RAD BN               3420-201 (DSVT)

CI                   3420-211 (DSVT)

METOC                3420-240 (DSVT)

SARC                 3420-242 (DSVT)

RECON OPS CENTER     3420-244 (DSVT)

           G-3

AC/S G-3             3420-300 (DSVT)                            g3@domain        g3@domain

G-3 CHIEF            3420-303 (DSVT)

    COMBAT OPERATIONS CENTER (COC)

SENIOR WATCH OFFICER 3420-300 (DSVT)

FUTURE OPS OFFICER 3420-327 (DSVT)

AIR OPS OFFICER      3420-308 (DSVT)


---

E-14 _______________________________________________________________________________________________ MCWP 6-22

                                                        E-MAIL ADDRESS

       Subscriber     Tactical         Commercial  DSN  NIPRNET         SIPRNET
                                                        Domain:         Domain:

CSS OPS OFFICER       3420-405 (DSVT)

FFCC OFFICER          3420-340 (DSVT)

FIRES                 3420-340 (DSVT)

TARGETING             3420-319 (DSVT)

EW PLANS OFFICER      3420-225 (DSVT)

CIVIL AFFAIRS         3420-105 (DSVT)

           G-4

AC/S G-4              3420-402 (DSVT)                   g4@domain       g4@domain

G-4 CHIEF             3420-402 (DSVT)

G-4 OPERATIONS        3420-403 (DSVT)

EMBARK                3420-404 (DSVT)

ENGINEER OFFICER      3420-405 (DSVT)

MEF SURGEON           3420-430 (DSVT)

           G-5

AC/S G-5              3420-500 (DSVT)                   g5@domain       g5@domain

DEP G-5               3420-501 (DSVT)

G-5 CHIEF             3420-505 (DSVT)

           G-6

AC/S G-6              3420-600 (DSVT)                   g6@domain       g6@domain

G-6 OPS OFFICER       3420-601 (DSVT)

G-6 OPS CHIEF         3420-602 (DSVT)

G-6 DATA OFFICER      3420-603 (DSVT)

G-6 COMM CHIEF        3420-603 (DSVT)

LAN/WAN TROUBLE DESK 3420-605 (DNVT)

MISCELLANEOUS

AID STATION           3420-155 (DNVT)

FORCE PROTECTION      3420-160 (DNVT)

      8TH COMM BN     3421-806 (DSVT)                   syscon@domain   syscon@domain
      3421 (SB-3865)  3421-807 (DSVT)                   techcon@domain  techcon@domain
CO                    3421-808 (DNVT)                   datacom@domain  datacom@domain
XO                    3421-830 (DSVT)
SGT MAJ               3421-931 (DSVT)
OPS OFFICER           3421-801 (DNVT)
OPS CHIEF             3421-867 (DNVT)
PERSONNEL OFFICER     3421-802 (DNVT)
BAS                   3421-613 (DSVT)
BN OOD                3421-623 (DSVT)
SYSCON                3421-633 (DSVT)
TECHON
DATA COM


---

Communications and Information Systems _____________________________________________________________ E-15

                                                                                  E-MAIL ADDRESS

     Subscriber      Tactical         Commercial DSN                    NIPRNET     SIPRNET
                                                                        Domain:     Domain:
                                      (910) 340-8235
2D MARINE DIVISION                    (910) 340-1014                    fwd.2dmardiv.iimef. fwd.2dmardiv.iimef.
     3469 (TTC-42)
                                                              751-9265  usmc.mil    usmc.smil.mil
                                      (910) 451-9271
CG                   3469-106 (DSVT)  (910) 451-9272                    cg@domain   cg@domain
                                                                        g1@domain   g1@domain
G-1                  3469-114 (DSVT)                          751-9470  g2@domain   g2@domain
                                                                        g2@domain   g3@domain
G-2                  3469-200 (DSVT)                          751-1014  g-4@domain  g4@domain
                                                              751-5263
G-3                  3469-300 (DSVT)
                                                              751-3977
G-4                  3469-400 (DSVT)                          751-2822

CELLULAR

TCO DIAL-IN          3469-675 (DNVT)

G-6                  3469-600 (DSVT)                                    g6@domain   g6@domain

CELLULAR

     DIVISION COMM COMPANY

CO COMM CO           3469-610 (DSVT)

TECHCON              3469-113 (DSVT)

OPS OFFICER          3469-149 (DSVT)

SYSCON (STU-III)     3469-669 (DSVT)

SIPRNET to MEF       3469-330 (DSVT)

TSC-93 (GMF)

DASC (STU-III)

LONG LOCAL - MEF     3469-701 (DNVT)

LONG LOCAL - WING    3469-702 (DNVT)

TTC-42 (SWBD)

     2ND MAR REGT
     3476 (SB-3865)

CO                   3476-106 (DSVT)

S-1                  3476-114 (DNVT)

S-2                  3476-200 (DSVT)

S-3 (STU-III)        3476-300 (DSVT)

S-4                  3476-400 (DNVT)

S-6                  3476-600 (DSVT)

     6TH MAR REGT
     3477 (SB-3865)

CO                   3477-675 (DSVT)

S-1                  3477-200 (DNVT)

S-2                  3477-300 (DSVT)

S-3                  3477-662 (DSVT)

S-4 (FAX)            3477-400 (DNVT)

S-6 (STU-III)        3477-600 (DSVT)


---

E-16 _______________________________________________________________________________________________ MCWP 6-22

                                                                          E-MAIL ADDRESS

       Subscriber           Tactical     Commercial DSN                   NIPRNET            SIPRNET
                                                                          Domain:            Domain:
       8TH MAR REGT     3478-106 (DSVT)                         751-2551
        3478 (SB-3865)  3478-114 (DNVT)
CO                      3478-200 (DSVT)
S-1                     3478-300 (DSVT)
S-2                     3478-400 (DNVT)
S-3                     3478-600 (DSVT)
S-4
S-6 (STU-III)           3479-106 (DSVT)
      10TH MAR REGT     3479-200 (DNVT)
        3479 (SB-3865)  3479-300 (DSVT)
CO                      3479-400 (DNVT)
S-2                     3479-600 (DSVT)
S-3
S-4                     3488-106 (DSVT)
S-6                     3488-300 (DSVT)

         2D TANK BN     3489-106 (DSVT)
        3488 (SB-3865)  3489-300 (DSVT)
CO
S-3                     3490-106 (DSVT)
  2D AMPH ASSAULT BN    3490-300 (DSVT)
        3489 (SB-3865)
CO                      3491-106 (DSVT)
S-3                     3491-300 (DSVT)

          2D LAR BN
        3490 (SB-3865)
CO
S-3
   2D COMBAT ENG BN
        3491 (SB-3865)
CO
S-3

          2D FFSG       3577-106 (DSVT)                                   fwd.2dfssg.iimef.  fwd.2dfssg.iimef.
       3577 (TTC-42)    3577-114 (DSVT)                                   usmc.mil           usmc.smil.mil
CG (STU-III)            3577-200 (DSVT)
G-1                     3577-300 (DSVT)                                   cg@domain          cg@domain
G-2                     3577-440 (DSVT)                                   g1@domain          g1@domain
G-3                     3577-606 (DSVT)                                   g2@domain          g2@domain
G-4                                                                       g3@domain          g3@domain
G-6                                                                       g4@domain          g4@domain
                                                                          g6@domain          g6@domain


---

Communications and Information Systems _____________________________________________________________ E-17

                                                         E-MAIL ADDRESS

       Subscriber           Tactical Commercial DSN      NIPRNET  SIPRNET
                                                         Domain:  Domain:
             H&S BN     3577-706 (DSVT)
CO                      3577-703 (DSVT)
S-3                     3577-704 (DNVT)
S-4
                        3577-610 (DSVT)  (910) 451-9609
     FSSG COMM CO       3577-149 (DSVT)  (910) 451-9610
CO                      3577-633 (DSVT)
OPSO
SYSCON                  3577-669 (DSVT)
COMMERCIAL (STU-III)    3577-720 (DNVT)
TECHCON                 3577-779 (DNVT)
SUPPLY
MAINT                   3580-706 (DSVT)
COMMERCIAL (STU-III)    3580-703 (DSVT)
                        3580-704 (DNVT)
              MD BN     3580-600 (DSVT)
        3580 (SB-3865)  3580-604 (DNVT)
CO
S-3                     3582-706 (DSVT)
S-4                     3582-703 (DSVT)
S-6                     3582-704 (DNVT)
DENTAL BN               3582-600 (DSVT)

             ENG BN     3584-706 (DSVT)
        3582 (SB-3865)  3584-703 (DSVT)
CO                      3584-704 (DNVT)
S-3                     3584-600 (DSVT)
S-4
S-6                     3586-706 (DSVT)
                        3586-703 (DSVT)
               LSB      3586-704 (DNVT)
        3584 (SB-3865)  3586-600 (DSVT)
CO
S-3
S-4
S-6

              MT BN
        3586 (SB-3865)
CO
S-3
S-4
S-6


---

E-18 _______________________________________________________________________________________________ MCWP 6-22

                                                      E-MAIL ADDRESS

       Subscriber           Tactical Commercial  DSN  NIPRNET           SIPRNET
                                                      Domain:           Domain:
           2D MAW       3527-106 (DSVT)
     CHERRY POINT       3527-114 (DSVT)               fwd.2dmaw.iimef.  fwd.2dmaw.iimef.
       3527 (TTC-42)    3527-200 (DSVT)               usmc.mil          usmc.smil.mil
CG                      3527-300 (DSVT)
G-1                     3527-400 (DSVT)               cg@domain         cg@domain
G-2                     3527-675 (DSVT)               g1@domain         g1@domain
G-3                                                   g2@domain         g2@domain
G-4                     3527-113 (DSVT)               g3@domain         g3@domain
G-6                     3527-150 (DSVT)               g4@domain         g4@domain
                        3527-185 (DNVT)               g6@domain         g6@domain
        TACC “DET B”    3527-120 (DNVT)
       CHERRY POINT     3527-196 (DNVT)
SYSCON OFFICER          3527-170 (DNVT)
TECHCON                 3527-613 (DNVT)
TSC-85                  3527-106 (DSVT)
TSC-120                 3527-103 (DSVT)
TSC-96                  3527-104 (DSVT)
TRC-170 (MEF)           3527-115 (DNVT)
Long Local - MEF        3527-206 (DNVT)
MCWS 28 CO              3527-230 (DSVT)
MCWS 28 S-3             3527-111 (DSVT)
MCWS 28 S-4             3527-211 (DNVT)
MCWS 28 Maint
DET B OFFICE            3527-333 (DSVT)
DATA COMM               3527-380 (DNVT)
COMM CENTER             3527-334 (DNVT)
MSC-63                  3527-382 (DSVT)
                        3527-393 (DSVT)
           MTACS 28     3527-381 (DSVT)
SAC
CTAPS SYS ADMIN         3530-113 (DSVT)
SWO/SAC                 3530-555 (DNVT)
DCN                     3530-150 (DSVT)
ICO                     3530-106 (DSVT)
TACC                    3530-132 (DNVT)
                        3530-131 (DNVT)
            2D MAW
  BOGUE FIELD DET “A”

         3530 (TTC-42)
SYSCON
TTC-42 VAN
TECHON
CO
RADIO
WIRE


---

Communications and Information Systems _____________________________________________________________ E-19

                                                          E-MAIL ADDRESS

       Subscriber           Tactical     Commercial  DSN  NIPRNET  SIPRNET
                                                          Domain:  Domain:
DATA COMM               3530-129 (DSVT)
COMM CTR                3530-111 (DSVT)
MAINT                   3530-115 (DNVT)

     MACS-6 ATC SITE    3530-350 (DNVT)
ATC COMMON              3530-351 (DSVT)
FACILITY WATCH O        3530-352 (DNVT)
RADAR SUPERV
                        3527-330 (DSVT)
     MACS-6 EW/C SITE   3527-332 (DSVT)
SAD                     3527-313 (DSVT)
SID                     3527-310 (DSVT)
TECHCON
SYSCON                  3532-113 (DSVT)
                        3532-213 (DSVT)
          NEW RIVER     3532-150 (DNVT)
            DET “A”     3532-150 (DSVT)
                        3532-106 (DSVT)
        3532 (SB-3865)
SYSCON                  3533-101 (DSVT)
SYSCON (SWO)            3533-102 (DSVT)
TTC-42 VAN              3533-103 (DSVT)
TECHON                  3533-104 (DNVT)
CO
                        3535-106 (DSVT)
 MASS-1 SUBSCRIBERS     3535-114 (DSVT)
        3533 (SB-3865)  3535-300 (DSVT)
                        3535-400 (DSVT)
SAC                     3535-600 (DSVT)
SYSCON
SEC WAN                 3535-806 (DSVT)
COMM USER               3535-330 (DSVT)

             MAG-26     3536-806 (DSVT)
          NEW RIVER     3536-803 (DSVT)
        3535 (SB-3865)  3536-800 (DSVT)
CO
S-1
S-3
S-4
S-6
           HMLA-167
CO
S-3

            MWSG 27
        3536 (SB-3865)
CO
S-3
S-6


---

E-20 _______________________________________________________________________________________________ MCWP 6-22

                                                          E-MAIL ADDRESS

       Subscriber           Tactical     Commercial  DSN  NIPRNET  SIPRNET
                                                          Domain:  Domain:
S-6 CHIEF               3536-801 (DNVT)
SYSCON                  3536-802 (DSVT)
TECHCON                 3536-833 (DSVT)
DATA                    3536-804 (DSVT)
WXO                     3536-805 (DNVT)

           MWSS 271     3540-506 (DSVT)
        3540 (SB-3865)  3540-503 (DSVT)
CO                      3540-500 (DSVT)
S-3                     3540-501 (DNVT)
S-6                     3540-502 (DNVT)
SYSCON                  3540-505 (DNVT)
TECHON
WXO                     3541-506 (DSVT)
                        3541-503 (DSVT)
           MWSS 272     3541-500 (DSVT)
        3541 (SB-3865)  3541-501 (DNVT)
CO                      3541-502 (DNVT)
S-3                     3541-505 (DNVT)
S-6
SYSCON                  3542-306 (DSVT)
TECHON                  3542-303 (DSVT)
WXO                     3542-300 (DSVT)
                        3542-301 (DNVT)
           MWSS 274     3542-302 (DNVT)
        3542 (SB-3865)  3542-305 (DNVT)
CO
S-3
S-6
SYSCON
TECHON
WXO


---

             Appendix F

CIS Planning Checklist

The purpose of this checklist is to guide CIS plan-   q Joint Communications Support Element Plan-
ning for joint operations. This checklist is derived     ning Guide
from Joint Pub 6-02, Joint Doctrine for Employ-
ment of Operational/Tactical Command, Con-            q Lessons-learned databases from previous oper-
trol, Communications, and Computer Systems.              ations and exercises
This checklist is not all-inclusive. Questions
should be revisited as CIS planners adapt to the      q TPFDD and time-phased force deployment list
changing operational situation. The checklist pro-
vides a framework for supporting CIS planning         Planning Considerations
for each phase of an operation, focusing CIS plan-
ners on the mission and how the commander in-         General
tends to accomplish it. CIS planners should also      q What is the MAGTF or unit mission?
be familiar with relevant joint and naval TTP and     q What is the geographic operational area?
have access to pertinent publications and techni-     q What are the commander’s intent, concept of
cal manuals as well as CIS support organizations,
including those listed at appendix P.                    operations, planning guidance, and CCIRs?
                                                      q What are the commander’s communications
Reference Material
                                                         and information systems requirements?
q Existing OPLANs and OPORDs                          q What are the JTF, naval expeditionary force,

q Commander’s planning guidance, estimate, in-           MAGTF, and supporting elements’ task organi-
   tent, and concept of operations                       zations? What are the command relationships?
                                                      q How will the forces deploy (means of transpor-
q Area studies                                           tation), and what is the deployment timeline?
                                                      q Are there any transport and/or lift restrictions
q Unit SOPs                                              (availability of assets, departure and arrival lo-
                                                         cations)?
q Joint Pub 6-0, Doctrine for Command, Control,       q Are there any satellite landing rights?
   Communications, and Computer (C4) Systems          q When are the operations planning meetings
   Support for Joint Operations                          scheduled? How will CIS planning meetings fit
                                                         into this schedule? Has DISA been involved re-
q Joint Pub 6-02, Joint Doctrine for Employment          garding coordination of technical require-
   of Operational/Tactical Command, Control,             ments?
   and Computer Systems                               q Are there any planning constraints?
                                                      q Are there any special CIS requirements? Who
q Joint Pub 6-02.1, Joint Connectivity Handbook          has them?
                                                      q What national space-based assets are required
q CJCSM 6230.03, Communications-Electronics              and/or available to support the operation? Has a
   Operations Instructions—Signal Operations             U.S. Space Command Joint Space Support
   Instruction                                           Team been contacted?
                                                      q What communications capabilities are avail-
q CJCSM 6231.01–6231.07A series, Manual for              able to the MAGTF: SHF and/or UHF com-
   Employing Joint Tactical Communications               mercial satellite, DSCS, and FLTSATCOM;

q DISA Contingency Plan 10-95


---

F-2 ________________________________________________________________________________________________ MCWP 6-22

   military strategic and tactical relay system        q What information does the supported MAGTF
   (Milstar) satellite terminals; JWICS and Mil-          or unit need from the supporting units and/ or
   star; HF, VHF, and UHF radio; tropospheric             activities (intelligence, weather, imagery, map-
   and line-of-sight microwave systems; local ar-         ping, deployment), and how will it be access-
   ea, switched backbone, and router networks;            ed?
   DMS; DISN; and personal communications
   systems?                                            Nonorganic Support

q What frequencies are available for the MAGTF         DISA
   in the operations area?
                                                       q Does the operational area have a DISA Region-
q What are the general INFOSEC requirements?              al Control Center or field office?
   Who will draft the callout message?
                                                       q Who is the DISA point of contact?
q Who is the potential adversary? What are their       q What is the DISN infrastructure in the opera-
   capabilities to conduct offensive information
   warfare (IW)? Does a joint force plan exist to         tional area?
   counter the threat?                                 q Are sufficient gateways available? What are the

q What are the releasability requirements for             interface requirements to access the gateways?
   multinational operations?                              Is the equipment available?
                                                       q Is the Telecommunications Service Provision-
Subordinate Units                                         ing and/or National Security Emergency Pre-
                                                          paredness authority provided and current?
q Where will their C2 nodes be located?                q What are the anticipated DSCS and commer-
                                                          cial satellite requirements?
q What are their communications requirements           q Has modeling of space networks been initiated
   (identify by function, C2 node/agency, and             by DISA?
   overall unit priority)?
                                                       Commercial Networks
q What are their communications capabilities
   (identify by function, command and control          q Are commercial networks available for use?
   node/agency, and overall unit priority)?               Who can approve access to them? Are funds
                                                          available? Has DISA been contacted to ensure
q What type of communications systems do they             required lead times for normal allocations? (1)
   have (power, frequency bands, interoperable            Satellite (2) Data (3) Voice?
   and compatible with other subordinate compo-
   nents’ equipment, mobility)?                        q What special interfaces are required to access
                                                          the commercial network, and where are the ac-
q Who is the unit CIS officer (G-6 or S-6) staff          cess points?
   point of contact for planning and technical
   management and direction?                           q What are the locations and types of switches in
                                                          the commercial network? What are their tech-
q Are there any special CIS requirements result-          nical parameters?
   ing from the mission and the commander’s esti-
   mate, intent, and concept of operations?            q Where are the locations and types of systems
                                                          providing the backbone transmission network?
q Are subordinate and supporting CIS plans con-
   sistent with the supported commander’s CIS          q What type of power is used—voltage, current,
   plan?                                                  commercial grid, or generator?

Supporting Units                                       q Does the operational area have a cellular net-
                                                          work? What are the transmission media, fre-
q What is the mission of the supporting units and/        quency band, and interface requirements? What
   or activities (this includes other Services, agen-     are the system standards? Is the system avail-
   cies, allies, and coalitions)?                         able for use?

q What are their communications capabilities?


---

Communications and Information Systems ______________________________________________________________ F-3

Chairman of the Joint Chiefs of Staff (CJCS)-      q What are the call signs and/or words for each
Controlled Assets                                     node?

q What CJCS-controlled assets are available?       q What units will provide, install, operate, and
q What capabilities are available?                    maintain the equipment for each node?
q Will JCSE support be required in the operation-
                                                   q What lift assets are available to deploy these
   al area, or will other defense and commercial      units? When will the units deploy and activate
   assets be sufficient?                              the nodes or network?
q Will JCSE support be needed for en route com-
   munications?                                    q Is the deployment schedule of CIS assets con-
q Has a Chairman of the Joint Chiefs of Staff In-     sistent with the phases of the plan? Will it per-
   struction (CJCSI) 6110.01, CJCS-Controlled         mit the provision of CIS support when and
   Tactical Communications Assets, support re-        where needed?
   quest for CJCS-controlled C4 systems assets
   been submitted?                                 q What is the phased buildup of CIS in the opera-
q What are the JCSE’s logistics support and elec-     tional area?
   trical power requirements?
q What are the JCSE airlift considerations, allo-  q Has CIS scheduling information been added to
   cations, and/or priority?                          the TPFDD and/or time-phased force deploy-
                                                      ment list?
Other Support
                                                   q Have the commander and principal staff offic-
q Is support needed from specialized communi-         ers affected been informed of potential CIS
   cations units?                                     shortfalls and recommended solutions?

q Who are the points of contact, and what are the  q How will keying material be managed (order-
   request procedures?                                ing, generation, storing, distribution, transfer,
                                                      and destruction)? What are the procedures for
q What are the unit’s communications capabili-        handling compromises? Is a COMSEC logis-
   ties and limitations?                              tics management activity needed in the opera-
                                                      tions area? What access will allies have to U.S.
Planning Activities                                   COMSEC?

General Planning                                   q Are network and node diagrams available?
q What nodes will provide entry into the global
                                                   q Have special communications requirements
   C4 systems network, and where will they be lo-     been addressed (MPF, shipboard, SAR, en
   cated?                                             route communications, and embarkation and
q What transmission media will be used to con-        debarkation connectivity)?
   nect the nodes?
q What types of CIS equipment will be located at   q Have SCI communications requirements been
   each node (equipment strings, interoperability     identified and satisfied?
   of the equipment)?
q What are the frequency requirements for each     q How will the joint, component, supporting
   node? How will the frequencies be allotted         forces, and MAGTF networks interface with
   (joint, multinational, components, the MAGTF,      nonorganic networks (DISN, commercial, and
   and MSCs)? Are there potential frequency con-      JCSE)?
   flicts?
                                                   q When and where will the joint, Marine Forces,
                                                      or MAGTF communications control centers be
                                                      established?

                                                   q Are the subordinate elements/units and sup-
                                                      porting CIS plans consistent with the MAGTF
                                                      CIS plan?

                                                   Detailed Planning

                                                   Circuit Switches


---

F-4 ________________________________________________________________________________________________ MCWP 6-22

q Does a circuit switch network diagram exist        q What STEP sites will be used? Has a gateway
   that shows information about the switch and          access request been submitted in accordance
   circuit switch network connectivity (switch          with DISA contingency and/or exercise plans?
   type, area code, trunk groups, and capacity)?
                                                     q What is the addressing scheme?
q How does the switch route calls: flood, deter-     q Where do the IP addresses come from?
   ministic, or circuit switch routing task execu-   q Will the IP addresses have to be changed when
   tion plan?
                                                        elements of the MAGTF go ashore?
q Where do circuit switches need to be located?      q What is the scheme for sorting out router
   How will they be connected?
                                                        loops?
q What special features or restrictions will be im-
   posed on subscribers? Who will authorize and      Message Switches
   enforce these restrictions?
                                                     q Where are the message switches required?
q Where are the DSN interfaces? Are precedenc-       q What is the trunking plan?
   es authorized? By whom?                           q What is the network connectivity of all mes-

q How will subscriber assistance be handled?            sage switches?
                                                     q Have routing indicators been developed and
q Where is the greatest anticipated traffic load:
   for GENSER? for SCI? Does sufficient capaci-         routing tables established?
   ty exist to handle these?                         q Is this an R and/or Y network?
                                                     q Has a plain language address directory been
q What types of status reports are required, and
   when will they be submitted?                         created?
                                                     q How will special category traffic be handled?
q How will traffic metering and network loading
   be measured, modeled, and managed?                   Who will be authorized to have access?
                                                     q What are the intranodal and internodal termi-
q Who will publish telephone directories, and
   how will they be distributed?                        nals?
                                                     q What types of status reports are required, and
Data Networking
                                                        when will they be submitted?
q What are the anticipated MAGTF or unit data        q What AUTODIN switching centers are con-
   requirements?
                                                        nected to the message switch?
q Has automation been planned and/or engi-           q Who is the automated message processing sys-
   neered into the network (x.25, IEEE 802.3,
   TCP/IP)?                                             tem security officer?
                                                     q Who will act as the AUTODIN controller?
q What and/or where are the network identifica-
   tions and gateways?                               Transmission Systems

q Will data of various classifications “ride” a se-  q Are the circuit requirements, routing, channel-
   cure tactical backbone? How will traffic of var-     ization, and other parameters that were identi-
   ious classifications be controlled and managed?      fied in high-level planning valid? Have satellite
   Are multilevel information systems security          access requests been submitted? Have frequen-
   initiative devices needed, and are resources         cy requests been approved and published?
   available?
                                                     q What are the characteristics and connectivity of
q What is the data network architecture?                multiplexers in the network? Are they compati-
                                                        ble?
q Who are the data network managers?

q What are the NIPRNET, SIPRNET, and
   JWICS connectivity requirements?


---

Communications and Information Systems ______________________________________________________________ F-5

q What are the timing requirements for the net-     q Who will control frequency spares and autho-
   work components? How will timing be accom-          rize their use?
   plished?
                                                    q Who manages the allocated satellite bandwidth
q What types of status reports are required, and       used by the geographic joint forces?
   when will they be submitted?
                                                    JCSE
Technical Management and                            q Is JCSE support required?
Direction                                           q Who is the JCSE point of contact?
                                                    q How is support requested?
Joint, Marine Forces, and/or MAGTF                  q How will JCSE participate in the technical
Communications Control Centers
q What are the operational procedures for the          management process?
                                                    q Are there any special reporting requirements
   control centers?
q Where are the joint, Marine Forces, and/or           for systems provided by the JCSE?

   MAGTF control centers located?                   Spectrum Management
q How will the control centers be manned?
q What reports will be required, how often will     q What are the provisions and procedures for fre-
                                                       quency planning and use for opposed and/or
   they be required, and when will they be submit-     unopposed entry operations into an operational
   ted?                                                area?
q How will network reconfiguration be accom-
   plished?                                         q What frequency allotments and assignments are
q Who are the points of contact at the subordinate     available for the operational area?
   control centers?
q Who will submit the telecommunications ser-       q Can the allotted and assigned frequencies sup-
   vice request (TSR) and telecommunications           port the equipment deployed to the operational
   service order (TSO)? Have TSRs/TSOs for SCI         area (communications, LANs and/or WANs,
   communications requirements been incorporat-        sensors, surveillance radars, GPS, and airspace
   ed?                                                 control radars)?
q Who will coordinate changes to connectivity
   with the DISN? With the commercial net-          q Will the frequencies work (propagation and to-
   works?                                              pographic analyses)?
q What kind of statistics will be kept? Who will
   analyze them? What will be done with them?       q Does the allocation and assignment of frequen-
q How will changes caused by the evolving tacti-       cies to subordinate commands contribute to
   cal situation be handled?                           mission accomplishment?
q Can the JCCC direct changes within MAGTF
   networks to optimize C4 systems within the       q What are the enemy capabilities to intercept,
   joint operations area?                              radio direction find, jam, or otherwise exploit
q Where is the boundary between technical direc-       or degrade MAGTF allotted and assigned fre-
   tion and operational direction?                     quencies? Does a joint and MAGTF plan exist
q How will frequency deconfliction be managed?         to counter the threat?
   How can potential conflicts be anticipated?
                                                    q Will the JCCC resolve electromagnetic inter-
                                                       ference issues? Will Joint Spectrum Center
                                                       support be required to resolve interference is-
                                                       sues?

                                                    q Who will issue the Joint Restricted Frequency
                                                       List?


---

F-6 ________________________________________________________________________________________________ MCWP 6-22

q Are sufficient spare frequencies available?       q What is the logistics plan for the cryptographic
q What EMCON measures will be applied?                 equipment?
q Will the MAGTF implement an electronic de-
                                                    q Are equipment and keymat sufficient to sup-
   ception plan? Are sufficient frequencies avail-     port planned and unplanned operations?
   able to support this plan?
                                                    q Have key change times been established and
Security                                               promulgated?

q Will the cryptographic equipment interoperate?    q Have provisions been made for over-the-air re-
q What are the keying material requirements?           keying where applicable?
q Does a key management plan exist?
q How will cryptographic compromises be de-         q Is an intertheater communications plan avail-
                                                       able? Is it needed?
   tected and corrected?
q What INFOSEC measures will be employed on         q What will we transition to and when?

   the LANs and WANs in the operational area?       q What is the IW threat?
q How will access to the various networks be
                                                    q Are virus-detection software applications in-
   controlled (electronic and physical)?               stalled and operational? Are passwords issued
q Have COMSEC and INFOSEC emergency de-                and in use? Has a contingency plan been devel-
                                                       oped to guide recovery actions should data be
   struction procedures been established?              modified or destroyed by unauthorized intru-
                                                       sions?

                                                    q Do remotely accessed computer systems pos-
                                                       sess features to identify users and substantiate
                                                       their identification before allowing information
                                                       to be processed?


---

                                   Appendix G

                 Unit Planning Checklist

The following checklist is provided to assist CIS planners in conducting operational
planning. It is oriented toward detailed unit planning from a CIS perspective. This
checklist is based on the 6-Step Marine Corps Planning Process (MCPP) published in
MCWP 5-1 (draft). Rather than reiterate the specific subcomponents of the 6-Step
MCPP, the reader should refer to MCWP 5-1 and comparatively analyze thought pro-
cesses which may assist in the design of the overall CIS architecture(s) which support
one or more courses of action (COAs).

The recommendations which follow may not be complete, depending on the level of
planning, the time allocated for planning, and most importantly, the commander’s in-
tent. As with any collaborative planning, the MCPP may not always appear sequen-
tial (e.g., 1, 2...6) when actually being executed. With these thoughts in mind, the
considerations provided below apply to each step, but are not necessarily limited to
any specific step. This is because the operational planning team (OPT) must remain
focused on the commander’s intent—and supporting it—throughout all levels of
planning.

Step 1, Mission Analysis                                 s MUX, SCR, what is the operational
                                                            state—transitional (mobile) or consolidat-
During this step, it is essential that the CIS plan-        ed (more static), and how may we support
ner develop a thorough understanding of the mis-            this?
sion and the commander’s intent, as well as the
situation. Included in this step are—                    s Interoperability—like all CIS planning the
                                                            key planning considerations (flexibility,
q Commander’s initial orientation.                          survivability, etc.); the CISO should con-
                                                            sult the CJCSM 6231.07A to determine if
q Staff analysis—the CIS planner may begin to               equipages involved in the operation are in-
   consider some of the following:                          teroperable.

   • Connectivity.                                    • Coordination—as soon as feasible, plan and
                                                         conduct an initial planning conference for
      s JTF HQ? MARFOR HQ? What is the                   CIS personnel (to include adjacent and sub-
         MAGTF composition?                              ordinate unit G-6/S-6s) in order to begin ef-
                                                         fective, concurrent planning. Coordinate all
      s Links to MSCs; again, MAGTF composi-             issues as they can be developed. Determine
         tion?                                           mid-term planning conference as applicable
                                                         to update all personnel involved in the plan-
         s Strategic high-capacity links—are these       ning with the latest revisions and command-
            required?                                    er’s intent.

         s What special capabilities may be re-       • Intelligence preparation of the battlespace
            quired to support special circuits?          (IPB). As with all members of the staff, IPB
                                                         should be constant throughout the planning
         s Is bandwidth adequate?


---

G-2 ________________________________________________________________________________________________ MCWP 6-22

      process. Some initial considerations in-              • Synchronization of C2 with maneuver and
      clude—                                                   all warfighting functions mobility of the CIS
                                                               assets and personnel?
      s Location/distances with respect to the ene-
         my; what terrain studies are available?            • Provision for link or circuit activation—
                                                               speed of support vs. reliability of the link or
      s Begin analysis of the topography and en-               circuit must be weighed; priority ALWAYS
         vironment in which CIS systems must op-               rests with the commander.
         erate. Consider also time of year (TNAPS
         + databases can begin to be built, notional        • Force protection; how do CIS units and per-
         at this point, and/or SPEED can be used to            sonnel support force protection?
         assist in this initial analysis of the area of
         operation).                                        • Logistics considerations; provision of sup-
                                                               port must be matched by effective consider-
      s Electronic emissions, communications se-               ation of the logistics plan.
         curity (COMSEC), computer security
         (COMPUSEC) and physical security is-               • IPB results; IPB is continuous, and the ene-
         sues must be formulated from the initial              my situation as it develops must be in the
         planning. What are enemy and friendly                 CIS planner’s mind.
         electronic warfare (EW) capabilities?
                                                         q Develop measures of effectiveness (MOEs).
      s Ensure a thorough understanding of the           q Develop COAs to achieve end state.
         enemy’s location and situation. Possible        q Present COA brief.
         node and retransmission sites must be           q Obtain approval of COAs for further analysis.
         considered in light of the enemy situation.
                                                         Step 3, COA Analysis
q Warning order.
                                                         The CIS planner must analyze all alternatives to
Step 2, COA Development                                  determine advantages and limitations of each.

The CIS planner should consider all factors that         q Commander provides guidance.
affect the exercise of C2. These factors include         q Staff wargames each COA.
mission, allocated forces, supporting communica-         q Staff briefs each COA.
tions units and equipment employment sites, and
joint/MAGTF user requirements. Finally, develop             • Wargame results.
alternative approaches to satisfy C2 requirements.          • Staff estimates of supportability.

q Determine desired end state; some specific CIS               s Feasibility of all alternatives to support
   considerations may include—                                    the COA?

   • Asset availability; what units are available to           s Adequacy of all means to support the
      support the current COA?                                    COA?

   • Personnel availability; what personnel can                s Acceptability of mediums and capacities
      best provide mission support to the COA?                    (links, circuits, etc.) to the commander?

   • Tempo of the operation; in addition to mo-                s Supportability of the CIS plan for the
      bility factors, how do all of the battlespace               COA; does it best enable the commander to
      functions factor in which must be supported                 exercise C2? What are the commander’s
      by CIS systems?                                             critical information requirements (CCIRs),


---

Communications and Information Systems ______________________________________________________________ G-3

         and how may each link/circuit provide                phase, coordination of a final planning
         them?                                                conference and a technical control confer-
      s Assumptions with regard to availability of            ence will enable key coordination efforts
         assets and personnel; identify and recon-            to take place, and a more detailed plan for
         cile all of these with the commander.                support can be prepared by all supporting
                                                              units/agencies.
      s Limitations; the estimate of supportability
         should identify for the commander and       Step 5, Orders Development
         staff what these may be.
                                                     Prepare the Annex K, refine the plan continuous-
      s Constraints/restraints; how do they affect   ly, and continue liaison with the staff and the
         the design and implementation of the CIS    commander. In this step, the staff will refine the
         plan?                                       selected COA into an OPORD together with sup-
                                                     porting documentation. Much of the required in-
Step 4, COA Comparison and                           formation will have already been developed in the
Decision                                             previous steps of the planning process. The
                                                     checklists below identify specific areas to be ad-
Selecting the best COA relies heavily on the de-     dressed in the OPORD.
velopment of the COA by staff elements; it is at
this point that the CIS planner assists the com-     The first list should be checked as soon as you
mander and staff in COA comparison by recom-         know your mission, while the second contains
mending the best option.                             items to be addressed after receipt of a warning
                                                     order. Many of these areas will need to be ad-
q Commander evaluates and compares COAs.             dressed several times throughout the planning and
                                                     during execution. Bear in mind that planning for
q Commander decides on the COA to be used.           an operation/exercise is different from planning
                                                     for a contingency. The checklists on the following
q New warning order issued.                          pages are to help guide you.

   • Commander’s concept of operation.               Items to be Initiated Well in Advance
   • Updated commander’s intent.                     of Warning Order Receipt

   • Complete description of the chosen COA.         *These items require continuous action before
                                                     and during the operation.
      s Supporting concepts; the CIS planner
         must begin immediately to resolve any       Communications
         shortfalls anticipated. At this point, the
         limitations which have already been iden-   q Review senior HQ operation plan/letter of in-
         tified by the CIS planner must be reduced      struction.
         or overcome in order to support the com-
         mander’s ability to exercise C2.            q Identify command relationships and related
                                                        connectivity requirements (both GENSER and
      s Task organization.                              SCI).*
      s Refined CCIRs.
                                                     q Request maps of area of operation.
      s Staff estimates.
      s Coordination—the CIS planner should en-      q Determine equipment requirements.*

         sure that final coordination with all re-   q Conduct map, weather, terrain analysis.*
         spective G-6s/S-6s (or designated
         representatives) is completed prior to      q Conduct C2 threat assessment. (See app. K.)
         orders development. During the planning


---

G-4 ________________________________________________________________________________________________ MCWP 6-22

q Conduct site or map reconnaissance and ID         Maintenance
   possible CP locations.*
                                                    q Verify an equipment repair order matrix.
q Conduct SPEED/sight analysis tools/Joint          q Determine repair parts requirements (preex-
   Spectrum Center studies.
                                                       pended bin, class IX block, stocks).
q Request frequencies/net IDs/call signs.           q Review/establish maintenance procedures.
                                                    q Check force activity designator status.
q Submit UHF satellite request (CUDIXS).            q Determine technicians required.
                                                    q Update the equipment repair order priorities on
q Submit SHF/GMF satellite access request.
                                                       mission-essential equipment (Marine Corps
q Identify AUTODIN requirements.                       Bulletin 3000).
                                                    q Update priorities on modifications and calibra-
q Submit telecommunications service requests           tions.
   (both GENSER and SCI).                           q Determine availability/need for mobile mainte-
                                                       nance teams.
q Recommend/coordinate w/S-3 on CP layout.          q Prepare necessary publications for embarka-
                                                       tion.
q Identify retransmission/relay/remote locations.*  q Conduct liaison visits with support agencies.
                                                    q Update temporary loan paperwork.
q Determine security requirements for communi-      q Determine status of type I, II, and III items.
   cations assets (both GENSER and SCI).            q Determine MPF asset availability.
                                                    q Prepare tools/equipment (test, maintenance, and
q Coordinate messenger communications opera-           diagnostic equipment).
   tions and procedures with the unit G-1/S-1.      q Conduct limited technical inspections.
                                                    q Update preventive maintenance actions.
q Review SYSCON procedures.                         q Determine availability of maintenance facilities.

q Identify communications reporting procedures.     CMS/Classified Materials Control Center/
                                                    Security
q Prepare and distribute radio guard chart.
                                                    q Establish list of authorized users.
q Prepare and distribute IP address chart.          q Determine keying material requirements.
                                                    q Acknowledge satellite access authorization.
q Prepare circuit switch traffic diagram.           q Determine CMS start and changeover times.

q Provide senior HQ with CEOI/automated             q Determine requirement for safes.
   CEOI/telephone directory.                        q Determine requirement for cables.
                                                    q Issue security reminder to all users/staff (two-
q Conduct ship visit (see app. C) as soon as pos-
   sible.                                              person integrity).
                                                    q Prepare input for C2 protection and deception
q Present predeployment briefing to staff/subor-
   dinates.                                            plan.
                                                    q Establish message handling procedures.
q Publish communications-related safety remind-
   ers.

q Prepare for special operations if required.

q Conduct predeployment training.

q Assess environmental impact on communica-
   tions.

q Review appropriate publications.

q Ensure that subordinate units understand com-
   munications guard shift procedures.

q Prepare/submit communications guard shift in
   accordance with NTP 4, Naval Telecommuni-
   cations Procedures—Fleet Communications.


---

Communications and Information Systems ______________________________________________________________ G-5

q Determine hardware requirements.                   q Shelter half (with five pins, three poles, and
                                                        guy line).
Items to be Initiated After Receipt of a
Warning Order                                        q ISO mat.
                                                     q Waterproof bag.
Communications                                       q Sleeping bag.
                                                     q Poncho and poncho liner.
q Issue fragmentary/warning order to subordinate
   units and issue initial CIS guidance to support-  Uniform Requirements
   ed principal staff officers.
                                                     q Cammies.
q Assemble staff to begin detailed planning.         q Cammie cover.
q Submit equipment augmentation request.             q Physical training gear (green/green, gray/gray,
q Weatherproof equipment.
                                                        running shoes, white socks).
Maintenance                                          q Field jacket with liner.
                                                     q Watch cap.
q Conduct operational checks.                        q Gloves with inserts.
                                                     q Rank insignia.
CMS.                                                 q Combat boots.
                                                     q Boot bands.
q Issue CMS callout message.                         q Web belt with buckle.
q Ensure that CMS equipment is distributed.          q Cold-weather underwear (top and bottom).
                                                     q Wet-weather top.
Administration                                       q Wet-weather bottom.
Personnel Equipment Requirements                     q Skivvie bottoms.
                                                     q T-shirt.
q Helmet.                                            q Socks.
q Flak jacket.                                       q Civilian clothes.
q H-harness.                                         q Towel (green).
q Cartridge belt.                                    q Washcloth (green).
q Two canteens with covers.                          q Shaving kit.
q Two magazine pouches.                              q Foot powder.
q Six M-16 pouches.                                  q Boot polish and brush.
q Weapon (with cleaning gear).                       q Sewing kit.
q Chemical protective gear.
q Gas mask.                                          Personnel Administrative Requirements
q E-tool.
q ALICE pack (with frame).                           q Determine personnel requirements.
q Flashlight (red lens).                             q Ensure that security clearances are complete.
q Bayonet/K-bar.                                     q Identify advance, main, and rear parties.
q Ear plugs.                                         q Make advance party assignments.


---

G-6 ________________________________________________________________________________________________ MCWP 6-22

q Submit request for personnel augmentation.            • ID tags/cards.
q Determine billeting requirements.                     • Next of kin.
q Duplicate records (service record book, health,       • CPOG, gas mask size.
                                                        • Uniform, boot size.
   dental,).                                            • Updated record of emergency data (RED).
q Ensure that visas/passports/drivers licenses          • Messman requirements.
                                                        • Corpsman request.
   (Status-of-Forces Agreement) are current.            • Armory draw.
q Ensure that basic clothing is servicable/marked.      • Recall roster.
q Ensure that direct deposit is established.            • Security for personal effects (supply).
q Ensure that powers of attorney are completed.         • Banks/credit unions.
q Ensure that wills are completed/updated.              • Mortgage/deed of trust/financial obligations.
q Check dental (class I or II) status.                  • Leases.
q Check dependent care arrangements.                    • Outstanding bills (address of creditors).
q Obtain key volunteers phone list.                     • Insurance coverage.
q Ensure that mail (forwarding address) form is         • Safe deposit box.
                                                        • Automobile storage.
   complete/submitted.                                  • Storage of household goods.
q Ensure that Marines understand the following          • Right to vote.
                                                        • Memberships and subscriptions.
   procedures/programs:
   • Family assistance.                              Logistics
   • Red Cross.
   • Casualty assistance.                            Embarkation
   • Legal assistance.
   • The Soldiers and Sailors Relief Act.            q Determine equipment requirements.
q Ensure that TRICARE/DEERS information is           q Determine logistical support requirements.
   updated and correct.                              q Identify hazardous materials (HAZMAT) and
q Ensure that allotment to spouses/split pay is ar-
   ranged.                                              storage/disposal procedures.
q Ensure that dependent ID cards are current         q Prepare personnel and equipment for embarka-
   through date of return from deployment.
q Ensure that custody of children for single par-       tion.
   ents is legally established.                      q Obtain shipping lists.
q Establish personnel database:                      q Identify and label embarkation boxes.
   • Name, rank, SSN, MOS.                           q Submit equipment density list (broken down by
   • Security clearance.
   • Meal card.                                         ship or transport relay).
   • Weapon number.                                  q Determine transportation requirements (person-
   • Section.
   • Blood type.                                        nel).
                                                     q Waterproof materials.


---

Communications and Information Systems ______________________________________________________________ G-7

q Prepare embarkation list for each box.            Utilities
q Provide air and surface transport support equip-
                                                    q Determine power requirements.
   ment (height, length, weight, cube).             q Submit generator (and operator) requests.
q Determine material handling equipment re-         q Conduct generator operator license training.
                                                    q Provide light bulbs.
   quirements (forklift/crane).                     q Provide drip pans/fuel drums.
q Inspect vehicles, generators, HAZMAT.             q Determine mobile electric power distribution
q Prepare staging schedule (TPFDD).
q Prepare 463L pallet request/inventory (check         system cabling/harness requirements.

   for proper straps).                              Motor Transport
q Submit MilVan/ConEx/QuadCon requests.
q Determine requirement and understand proce-       q Conduct HMMWV/five-ton license training.
                                                    q Determine convoy route.
   dures for HAZMAT, packaging, handling, stor-     q Submit vehicle and driver assignments (consid-
   age, transportation, etc.
                                                       eration: command group drivers).
Supply                                              q Determine convoy composition.
                                                    q Establish convoy communications/control pro-
q Block of materials request.
q Camouflage netting requirements.                     cedures.
q Tentage.                                          q Determine requirement for vehicle placards.
q Cots.                                             q Determine fuel requirements (petroleum, oils,
q Field desks/tables/chairs.
q Meals, ready to eat (MREs).                          and lubricants).
q Training allowance pool gear.                     q Determine requirement for trip tickets.
q Batteries.
q Wire.                                             Step 6. Transition
q Sandbags.
q Plastic.                                          The last step in the MCPP is transition of the
q Flooring.                                         OPORD from the planners to the executors (at the
q Heaters.                                          MEF level, from future operations to current op-
q Schedule.                                         erations). The planning, decision, and execution
                                                    cycle continues with planners responding to the
                                                    developing situation and with new or revised mis-
                                                    sions.

                                                    (reverse blank)


---

G-8 ________________________________________________________________________________________________ MCWP 6-22


---

Communications and Information Systems ______________________________________________________________ G-9


---

                            Appendix H

      Data Communications Network
                          and

Information Systems Planning Checklist

Gateway Access Coordination                         q Identify transmission system links to be used in
                                                       support of data networks, in conjunction with
q Determine bandwidth requirements (over 32            communications battalion/squadron systems
   kbps will require special coordination).            planning and engineering staff and the G-6.

q Incorporate request for NIPRNET/SIPRNET/          q Identify data rates to subordinates.
   JWICS into satellite access request.             q Determine the interior routing and encapsula-

   • MEF IP networks to be used.                       tion protocol to be used with subordinates (i.e.,
   • Router type.                                      IGRP/OSPF and HDLC/PPP).
   • Encryption device.                             q Determine autoroute tables and related require-
   • Data rate.                                        ments for all JMCIS workstations.
   • Exterior routing and encapsulation protocol    q Determine CSU/DSU unit leased-line require-
                                                       ments.
      (i.e., BGP4/EGP and PPP/HDLC).                q Determine the number of hosts (MEF CE) that
                                                       require an IP address (UNIX TDS workstations
q Ensure standard gateway COMSEC (ICP                  and PCs configured as IP clients).
   USKAT: C5573).                                   q Determine the appropriate IP subnet mask to be
                                                       used.
q Coordinate/confirm KG-84A/C front-panel set-      q Design a detailed IP data network for NIPR-
   tings with gateway.                                 NET, SIPRNET, and JWICS (MEF CE will pro-
                                                       vide IP addresses for MEF/subordinate IP
q Contact DISA, per mission directive, 7–10 days       interface).
   before scheduled activation to confirm IP ad-    q Determine the COMSEC keymat to be used
   dressing and routing information.                   (generally will use same as gateway).
                                                    q Coordinate DNS access/use, if required.
q Coordinate with the local information office, in
   conjunction with MEF G-6, to establish a NI-     LAN Requirements
   PRNET server-to-server connection.
                                                    q Determine the number of PCs to be connected to
MEF WAN Requirements                                   each network.

q Determine the number of subordinate/adjacent      q Determine the number of services required.
   commands/units requiring serial port router ac-  q Determine the number of TDSs to be connected
   cess.
                                                       to SIPRNET (e.g., GCCS, IAS, TCO, CTAPS,
q Determine appropriate router type.                   etc.).
                                                    q Identify the geographical area that the MEF CE
   • CISCO 4000 (two serial/four Ethernet)             will use (tents, buildings, or trailers) and the
   • CISCO 7010 (eight serial/six Ethernet)            physical separation/distance between sections.


---

H-2 __________________________________________________________________________________________________________________________________________________________ MCWP 6-22

q Determine cabling and connector requirements       q Determine power requirements (generally, 15
   (RG-58, fiber optic, thick Ethernet, BNC con-        kW, 120 V, 60 Hz).
   nectors, terminators, T connectors).
                                                     q Determine the number of personnel required to
   • RG-58: maximum distance, 185 m.                    support the exercise/operation. Keep in mind:

   • Thick Ethernet: maximum distance, 500 m.           • WAN monitoring/maintenance will general-
                                                           ly require two Marines per shift.
   • Fiber optic: maximum distance, 2.5 miles
      multi-fiber, 10 miles single fiber.               • The help desk will generally require one Ma-
                                                           rine per shift.
q Determine the number of repeaters required.
   (The number depends on the physical layout of        • LAN troubleshooting will generally require
   the CE and number of PCs/laptops/TDSs.)                 1 Marine per 35 computers per shift.

q Determine the number of servers required. (The        • 24-hour operations require 12-hour shifts.
   number depends on applications: Plan for 1
   server per 35 users when message distribution        • Duration of exercise/operation will affect
   system (MDS) is being used.)                            personnel requirements.

q Design a detailed LAN diagram with appropri-       q Submit COMSEC request to CMS.
   ate cable segments, repeater, routers, servers,
   TDSs, and IP clients identified.                  q Coordinate priority DSN/INMARSAT access
                                                        for initial SIPRNET/NIPRNET/JWICS installa-
q Determine server application requirements             tion.
   (e.g., MDS, e-mail, etc.).
                                                     q Coordinate one AN/GRA-39 per shelter. (When
q Determine the number of LAN dial-ins required         using HMMWV-mounted shelters, arrange for
   and the type of interface (i.e., KY-68, STU-III,     two.)
   Hayes Modem).
                                                     q Coordinate separate J1077 (J-box)/26-pair ca-
q Determine the concept of operations for INFOS-        ble for data serial connections for each shelter
   EC monitoring and analysis, and initiate neces-      (reduces conflicts with wire/telephone connec-
   sary support requests.                               tions—recommended when supporting multi-
                                                        ple serial line connections).

Logistic and Personnel Planning                      Network Management

q Determine block of materials requirements on       q Coordinate IP address management in conjunc-
   the basis of requirements and preliminary plan-      tion with principal staff officers and higher/ ad-
   ning, and submit 45–60 days before deploy-           jacent/subordinate unit communications and
   ment.                                                information systems officers.

q Determine embarkation requirements, includ-        q Create appropriate user accounts in accordance
   ing shelters to be used (height, weight, width,      with Marine Corps and MEF standards, per G-6
   length), on the basis of equipment requirements      input.
   and geographical location.
                                                     q Implement a virus management plan in conjunc-
q Submit appropriate log requests for lifting and       tion with the G-6.
   transporting shelters or pallets (if required).
                                                     q Implement an automatic data processing securi-
q Determine power distribution and grounding re-        ty plan in conjunction with the G-6.
   quirements.
                                                     q Implement an internet access policy in conjunc-
                                                        tion with the G-6.


---

Communications and Information Systems_____________________________________________________________________________________________________ H-3

Preexercise Equipment                                q Preconfigure and bench test equipment string.
Preparation
                                                     q Coordinate a data communications pretest/con-
q Identify the equipment required to support the        figuration exercise with subordinate units, if
   exercise/operation.                                  feasible.

q Configure and test servers (see Server Checklist   q Ensure that all application, diagnostic, and serv-
   on page H-4).                                        er software is loaded on each server and on dis-
                                                        kette (two copies), tape, or compact disk (CD).
q Configure and test routers and repeaters (see
   Router/Repeater Checklist on page H-5).           q Ensure that all UPSs are tested.

q Confirm proper crypto strappings.                  q Ensure that all network and router management
q Inspect and test all KG-84 red and black side ca-     PCs/laptops are configured and tested properly.

   bles.                                             q Ensure that all equipment is embarked in a man-
q Configure and test all CSU/DSU modems and             ner that will minimize equipment damage.

   cables.                                           q Ensure that appropriate backup equipment is
                                                        tested and embarked.


---

H-4 __________________________________________________________________________________________________________________________________________________________ MCWP 6-22

                               SERVER CHECKLIST                                               Date______________

Server serial no._________________ Server key no._____________________ Server name____________________

Server console password________________ Sys admin account name: SysAdmin*___________________________

Password_______________ Processor (min. 486)_____________________ RAM (min. 16 Mb)________________

Hard disk size (min. 500 Mb): No. 1_____ No. 2_____ No. 3_____     Tape backup unit__________________________

             Network interface cards and                                         Services created:
       intelligence communication adapter:

Slot Type/Maker IRQ I/O Address RAM Address Init. Started Type Name

____ ___________ ____ ___________ ___________ ____ Started File SHARED FILES*

____ ___________ ____ ___________ ___________ ____ Started File DATACOMM SHARED FILES*

____ ___________ ____ ___________ ___________ ____ Started ISMTP ISMTP*

____ ___________ ____ ___________ ___________ ____ Stopped STDA SATELLITE STDA*

____ ___________ ____ ___________ ___________ ____ Stopped Print SHARED PRINTER*

              Server options:                          Software installation (each program loaded and tested):

Init.                          Version No.                         On SHARED FILES*

____ VINES operating system                     Init.                                 Version No. License No.

____ Server-to-server LAN                       ____ Lotus SmartSuite (LAN user)

____ Server-to-server WAN (HDLC)                ____ MTF Editor

____ PC print                                   ____ MDS

____ Asychronous dial-in                        ____ VDS

____ Asynchronous terminal emulation            ____ MCLLS

____ Mail service                               ____ JULLS

____ Network management                                          On DATACOMM SHARED FILES*

____ VINES assistant toolbox                    ____ MS-DOS

____ TCP/IP routing                             ____ Windows

____ TCP/IP server to server                    ____ ProComm Plus

____   Incognito simple mail transfer protocol  ____   3 Com Etherlink II Diag
       (ISMTP) (software only)                  ____   3 Com Etherlink III Diag

____   Incognito domain name server             ____   PCtools
       (software only)                          ____   SuperTCP for Windows

          Server accessories:                                    Hardware test verification:

Init.                                           Init.

____ Power cable (CPU, monitor, printer, router) ____ Each network interface card tested with a client PC

____ UPS                                        ____ Intelligence communication adapter tested (each port)

____ ICA cables                                 ____ Floppy drive tested

____ Surge protectors (2)                       ____ Tape backup tested and verified

____ Extension cord (15 ft. or more)            ____ Platform diagnostics run

____ Printer                                    ____ Last second echelon preventive maintenance ______________

____ Printer cable                              Next scheduled second echelon preventive maintenance_______________

____   Printer ribbons/toner cartridge          *@servername@servers
____   Blank option key

____ Server software/CD-ROM


---

Communications and Information Systems_____________________________________________________________________________________________________ H-5

                                     ROUTER/REPEATER CHECKLIST

Router CISCO 4000/7010

Serial no.__________________         Router name/no.____________________ Router password________________

Software version no._______________          Router configuration printed and attached___________________(initials)

       Router hardware verification                         Ethernet transceivers and AUI cables
        (each port must be tested)                                             (test each)

Init.                                        Init.                                        Serial no.

____ Serial 0     ____ Ethernet 0            ____ One transceiver per router/repeater port ____________

____ Serial 1     ____ Ethernet 1            ____ One AUI cable per router/repeater port  ____________

____ Serial 2     ____ Ethernet 2            ____ Five backup transceivers/AUI cables     ____________

____ Serial 3     ____ Ethernet 3

____ Serial 4     ____ Ethernet 4

____ Serial 5     ____ Ethernet 5

____ Serial 6     ____ Ethernet 6

____ Serial 7                 Ethernet 7

Repeater          Serial no.__________

Quantity          Init.

____ AUI ports    ____ All ports tested

____ Ethernet ports ____ One transceiver/AUI cable per AUI port, serial nos.:______________________________

       UPS (two)

Init.

___ Tested good

                        Additional items

Init. Quantity    Item

____ ____         Blank, option keys (five)

____ ____         Cable, AUI (five: one per router/repeater port)

____ ____         Cable, CISCO 4000 to RS-449

____ ____         Cable, CISCO 7010 to KG-84C

____ ____         Cable, power (CPU, monitor, router, repeater)

____ ____         Cable, RS-232 to KG-84 red (six per ICA)

____ ____         Cable, RS-449 to KG-84 red (four)

____ _____        ICA cable (one per ICA)

____ ____         Surge supresser (two)

____ ____         Transceiver, thinnet

                                                                                          (reverse blank)


---

                                  Appendix I

 Communications and Information Systems
                          Estimate

     COMMUNICATIONS AND INFORMATION SYSTEMS ESTIMATE
     (Local variations and modifications as necessary to meet requirements.)
------------------------------------------------------------------------------------------------

                                    CLASSIFICATION

                                                               Copy no. ___ of ___ copies
                                                               Issuing headquarters
                                                               PLACE OF ISSUE
                                                               Date/time of issue

COMMUNICATIONS AND INFORMATION SYSTEMS ESTIMATE

Ref:

1. ( ) MISSION. (This subparagraph contains a brief restatement of the basic
mission of the command as a whole as previously announced by the commander.
Deduced missions necessary for the accomplishment of the basic mission, along
with previous decisions of the commander regarding either deduced or basic
missions should be listed in appropriate subparagraphs.)

2. ( ) SITUATION AND CONSIDERATIONS.

     a. ( ) Intelligence Situation. (Information known or obtained from the
     G2. Where appropriate, reference may be made to the Intelligence Estimate
     or other intelligence documents.)

          (1) ( ) Characteristics of the Area. (Those affecting C2.)

                (a) ( ) Weather.

                (b) ( ) Terrain.

                (c) ( ) Transportation networks/communication routes.

                (d) ( ) Other area characteristics that affect C2.

                                       (Page number)
                                    CLASSIFICATION


---

I-2 _________________________________________________________________________________________________ MCWP 6-22

                                                  CLASSIFICATION

                     (2) ( ) Enemy Strengths and Disposition of Major Units
                          (a) ( ) Tactical units.
                          (b) ( ) Signals intelligence/electronics warfare.
                                  1. ( ) Jamming.
                                  2. ( ) Wire tapping.
                                  3. ( ) Imitative deception.

                b. ( ) Friendly Forces. (Information obtained from the commander’s planning
                guidance and from the G-3.)

                     (1) ( ) Present Disposition of Major Units
                          (a) ( ) Tactical units.
                          (b) ( ) CIS elements.

                     (2) ( ) Courses of Action to be Considered
                          (a) ( ) Course of action #1.
                          (b) ( ) Course of action #2, etc.

                     (3) ( ) Projected Operations. (If known, and which will affect the CIS situ-
                     ation.)

                          (a) ( ) Rates of advance.
                          (b) ( ) Command post location and displacement.
                          (c) ( ) Uncovering of major communication routes.
                          (d) ( ) Other projected operations that affect the CIS situation.
                c. ( ) Personnel Situation. (Information known or obtained from the G-1 re-
                garding personnel matters affecting the CIS situation. Where appropriate, make
                reference to the personnel estimate or other personnel documents.)
                     (1) ( ) Strengths.
                     (2) ( ) Replacements.

                                                     (Page number)
                                                  CLASSIFICATION


---

Communications and Information Systems _______________________________________________________________ I-3

                                                  CLASSIFICATION

                         (3) ( ) Command post organization and operation.

                         (4) ( ) Other personnel matters affecting the CIS situation.

                    d. ( ) Logistics Situation. (Information known or obtained from the G-4
                    regarding logistics matters affecting the CIS situation. Where appropriate,
                    reference may be made to the logistics estimate or other logistics docu-
                    ments.)

                        (1) ( ) Availability of equipment.

                        (2) ( ) Condition of equipment.

                        (3) ( ) Availability of repair parts and consumable items.

                        (4) ( ) Other logistic matters affecting the CIS situation.

                    e. ( ) Assumptions. (Any assumptions required as a basis for initiating
                    planning or for the preparation of the estimate.)

                    f. ( ) CIS Situation.

                         (1) ( ) General. (Information regarding current communication in-
                         stallations, the status of the overall communications system, and the lo-
                         cation and mission of communication and control agencies. Reference
                         may be made to the CIS SOP and COI or to the command, control and
                         communications systems annexes contained in current operation plans
                         or orders.)

                         (2) ( ) Special. (Items not covered elsewhere which affect the CIS
                         situation.)

                              (a) ( ) Availability and assignment of radio frequencies.

                              (b) ( ) Assignment of call signs.

                              (c) ( ) Availability of shipboard communication equipment for
                              troop use.

                              (d) ( ) Arrangements for communications guard.

                              (e) ( ) Anticipated traffic volumes.

                              (f) ( ) Cryptographic matters.

                              (g) ( ) Other special items affecting the CIS situation.

                                                      (Page number)
                                                  CLASSIFICATION


---

I-4 _________________________________________________________________________________________________ MCWP 6-22

                                                  CLASSIFICATION

          3. ( ) ANALYSIS. (Each course of action under consideration is analyzed in the
          light of significant factors to determine problems which will be encountered, measures
          required to solve such problems, and any limiting features which will exist.)

                a. ( ) Course of Action #1.

                     (1) ( ) Support Requirements,

                          (a) ( ) Terrain and Distance Factors. (A discussion of terrain and dis-
                          tance factors that may affect the location of command posts, installations,
                          and the employment of communications means.)

                          (b) ( ) Installations. (A discussion of known or deduced communica-
                          tions requirements for each communications and control agency and other
                          units. These requirements may be expressed as need lines or may be de-
                          tailed to include types of circuits and terminal service, or other forms of
                          communications, required by these activities.)

                     (2) ( ) Support Capability. (A discussion of the capability to employ all
                     available means of communications to satisfy the foregoing support require-
                     ments.)

                          (a) ( ) Radio and Wire. (Discussed in conjunction with the capability
                          to provide various types of circuits and attendant terminal service; e.g.,
                          telephone, facsimile, and data.)

                          (b) ( ) Network Systems.

                          (c) ( ) Messenger.

                          (d) ( ) Visual and Sound.

                b. ( ) Course of Action # 2. (Same for each COA #1.)

          4. ( ) EVALUATION. (Based on the foregoing analysis, the advantages and disad-
          vantages of each course of action are summarized and compared from a CIS view-
          point.)

                a. ( ) Course of Action #1.

                     (1) ( ) Advantages.

                     (2) ( ) Disadvantages.

                                                     (Page number)
                                                  CLASSIFICATION


---

Communications and Information Systems _______________________________________________________________ I-5

                                                  CLASSIFICATION
                         b. ( ) Course of Action #2.
                         (1) ( ) Advantages.
                         (2) ( ) Disadvantages.
                    c. ( ) Other Courses of Action.
              5. ( ) CONCLUSIONS.
                    a. ( ) COA Statement. (A statement as to which course of action under con-
                    sideration can best be supported from a CIS viewpoint.)
                    b. ( ) Salient Disadvantages Statement. (A statement of the salient disad-
                    vantages which render the other courses of action less desirable from a CIS
                    viewpoint.)
                    c. ( ) Significant Problems Statement. (A statement of significant CIS prob-
                    lems to be solved and limitations which may exist.)
                    d. ( ) Resolution Statement. (A statement of measures required to resolve
                    the foregoing CIS problems and offset any limitations which may exist.)

                                                                              /s/____________________
                                                                                _____________________

              Appendixes: (As appropriate)

   (Page number)  (reverse blank)
CLASSIFICATION


---

                  Appendix J

Sample CIS Annex (Annex K)

The CIS annex generally follows the basic           stand the annex. The caption Ref:____ is always
OPLAN or OPORD format. General instructions         included. When there are no references, the cap-
for preparation are provided below. A sample        tion will be followed by the word “none.” Each
Annex K appears on pages J-4 through J-14.          item cited as a reference is preceded by a letter in
                                                    parentheses and is in alphabetical sequence (e.g.,
Heading                                             (a), (b), etc.). Information regarding maps and
                                                    charts should include the country, scale, name and
The heading is the same as the heading of the       sheet number, and year of edition, or the appropri-
OPLAN or OPORD and gives the following in-          ate information required to locate them on com-
formation:                                          pact disc.

Issuing HQ                                          Time Zone
This consists of the official designation of the
command.                                            The time zone normally used in the plan or order
                                                    is that of the objective area. When the plan or or-
Place of Issue                                      der applies to units in different time zones, uni-
This shows the physical location of the issuing     versal coordinated time or the time specified by
HQ. All letters are capitalized.                    higher HQ is used.

Date-Time Group                                     Body
This indicates the date and time the plan or order
is signed and, unless otherwise specified in the    The body of the annex contains information con-
plan or order, the date and time the annex be-      sistent with that contained in the main body but
comes effective. It is expressed in standard mili-  focused on information relevant to CIS.
tary sequence: day, hour, minutes, time zone
suffix, month, and year (e.g., 151200Z Jan 2000).   General
The time zone used will be that of the operations
area or universal coordinated time.                 This subparagraph contains a brief, general state-
                                                    ment of the purpose of the annex with respect to
Designation and Title of the Annex                  the basic plan objectives. It provides guidance for
The title of an annex consists of a capital letter  CIS support of the operation.
followed by an indication of the subject matter in
parentheses and by the number of the OPLAN or       Situation
OPORD to which it is attached.
                                                    This paragraph provides an overview of the envi-
References                                          ronment in which the CIS support described in
Included in the heading and listed as references    the annex will be provided. This includes the rea-
are other sources of information (CIS SOPs,         son for the annex, the friendly and enemy situa-
CEOI, maps, charts, or overlays) needed to under-   tion, and assumptions that are necessary to
                                                    planning. This subparagraph summarizes the situ-
                                                    ation consistent with that of the main body, but
                                                    focusing on those factors that affect CIS.


---

J-2 ________________________________________________________________________________________________ MCWP 6-22

General. This subparagraph will make reference to      procedures that are contained in the references but
the concept of operations.                             that need emphasis are called out. New procedures
                                                       are included in a separate subparagraph.
Enemy Forces. This subparagraph contains enemy
forces information that will affect CIS employ-        Operational Concept
ment. This subparagraph usually references the in-
telligence annex or provides specific information      This subparagraph describes briefly how the en-
on the enemy’s intelligence, EW, or deception (or      tire operation is visualized from the CIS view-
other) capabilities; C2 facilities; CIS capabilities;  point. Particular emphasis is placed on aspects of
and the possible exploitation of enemy assets.         the basic plan that establish CIS support require-
                                                       ments, capabilities, and limitations.
Friendly Forces. This subparagraph contains infor-
mation on the higher, adjacent, supported, and/or      Tasks and Responsibilities
supporting units or facilities involved in the C2
support of the operation. This subparagraph identi-    This subparagraph assigns specific CIS support
fies communications elements attached or de-           missions or tasks for both issuing and subordinate
tached for the operation. Reference may also be        units. The tasks for each unit are addressed in sep-
made to the task organization annex.                   arate subparagraphs. In addition, instructions for
                                                       functional areas such as intelligence, fires, and lo-
Assumptions. This subparagraph establishes es-         gistics are in specific subparagraphs and often ex-
sential criteria for developing the CIS annex. If, as  panded on in appendices to Annex K. It should be
the planning phase progresses and the situation        noted that CIS support for functional areas is also
develops, the assumptions prove mistaken, then         routinely incorporated into CIS appendices, tabs,
the plan must be modified accordingly. Assump-         or enclosures that are a part of the OPLAN/
tions define the anticipated conditions that will      OPORD annexes covering those functional areas.
drive CIS requirements and affect CIS capabili-
ties; they are major considerations for planning       Coordinating Instructions
CIS support. The number of assumptions should
be held to a minimum and worded carefully to de-       This subparagraph provides instructions for CIS
scribe concisely and accurately the conditions on      support tasks that apply to two or more units.
which the plan is based. Assumptions are applica-
ble to plans only.                                     Special Measures. This paragraph is separated into
                                                       subparagraphs and provides information regard-
Mission                                                ing each special measure or procedure necessary to
                                                       support the mission that is not addressed above or
This paragraph is a concise statement of the mis-      in paragraph 4 of the OPLAN or OPORD. This
sion of the command. It should include the com-        paragraph includes specific information pertain-
mander’s intent and identify actions necessary to      ing to measures such as routing indicators, elec-
support this intent, the concept of operations, and    tronic identification procedures, and liaison teams.
the commander’s planning guidance. Normally,
this paragraph states the time that the C2 facilities  Information Management. This paragraph provides
will commence and terminate operations.                instructions for ensuring that the communications
                                                       and information management systems supports the
Execution                                              unit information management plan. Usually, this
                                                       paragraph references the annex that addresses CIS
Guiding Principles                                     support for information management.

This subparagraph outlines the principles neces-       Administration and Logistics
sary for the coordination and guidance of all com-
mands and units. Selected policies, doctrine, or       Administration

                                                       This paragraph contains administrative procedures
                                                       concerning CIS support in the areas of personnel,


---

Communications and Information Systems _______________________________________________________________ J-3

records, reports, and other administrative matters.  q Signature of either the commander or the com-
It will include identification of CPs ashore and        mander’s authorized representative. (Authenti-
afloat.                                                 cation by the authorized representative is also
                                                        acceptable.)
Logistics
                                                     q List of the appendices attached to the annex.
This paragraph contains logistics information re-
lating to CIS employment, and usually references     q Distribution.
the logistic/CSS annex.
                                                     Appendices
Command and Control
                                                     Appendices amplify information contained in the
Command Relationships                                basic CIS annex and are used to promote accura-
                                                     cy, brevity, and clarity. The material contained in
This paragraph contains information relating to      the appendices is usually technical, detailed, and
command relationships and usually refers to the      complex in nature. The information often lends it-
appropriate appendices in the OPORD.                 self to presentation in tabular, schematic, or over-
                                                     lay form. MCWP 5-1 (draft) provides amplifying
Communications and Information Systems               information. Typical appendices that may be pre-
Plans                                                pared to support the basic CIS annex include com-
                                                     munications security, call signs, visual and sound
This paragraph refers to the appropriate appendi-    communications, and frequency management, to
ces in the OPORD.                                    name but a few possibilities. The sample format
                                                     (pages J-4 through J-14) contains a more exten-
Ending                                               sive listing of possible appendices, but the listing
                                                     provided is not meant to be either exhaustive or
The ending of the CIS annex consists of the fol-     mandatory. The number and type of appendices
lowing:                                              required will vary with the situation and the needs
                                                     of the preparing organization.
q Acknowledgment instructions.


---

J-4 ________________________________________________________________________________________________ MCWP 6-22

                   CLASSIFICATION

                                            Copy no. _____ of _____ copies
                                            Issuing headquarters
                                            PLACE OF ISSUE
                                            Date/time of issue
                                            Message reference number

ANNEX K TO (UNIT) OPORD (NUMBER) (U)
COMMUNICATIONS AND INFORMATION SYSTEMS (U)

(U) Ref:  (a) MCWP 6-22 (Communications and Information Systems) (U)
          (b) CJCSM 6231 (Series) (Manual for Employing Tactical Communications) (U)
          (c) ACP 121 (Communications Instructions—General) (U)
          (d) ACP 122 (Series) (Communications Instructions—Security) (C)
          (e) ACP 167 (Series) (Glossary of Communications-Electronics Terms) (U)
          (f) NWP 4 (Series) (Basic Operational Communications Doctrine) (U)
          (g) NTP-3 (Series) (Telecommunications—Users Manual) (U)
          (h) NTP-4 (Series) (Naval Telecommunications Procedures—Fleet Communications) (C)
          (i) NTP-5 (Voice Communications) (U)
          (j) JANAP 128 (Series) (Automated Digital Network (AUTODIN) Operating Procedures) (U)
          (k) (Higher Headquarters) (Communication and Information Systems Plan) ( )
          (l) (Higher Headquarters) (OPORD) ( )
          (m) (Unit) Order (Communication and Information Systems SOP) ( )
          (n) (Unit) Order (Information Management SOP) ( )

(U) Time Zone: Z

1. ( ) GENERAL. This annex provides guidance for employing CIS architecture to support (unit) op-
erations.

2. ( ) SITUATION.

a. ( ) General. (See Concept of Operations, Annex C (Operations))
b. ( ) Enemy.

    (1) ( ) See Annex B (Intelligence)
    (2) ( ) The enemy has the capability to—

                                                (Page number)
                                             CLASSIFICATION


---

Communications and Information Systems _______________________________________________________________ J-5

                                                  CLASSIFICATION

                              (a) ( ) Conduct satellite-based EA, including imitative commu-
                              nications deception, jamming (both communications and radar), ra-
                              dar deception, and electromagnetic virus insertion operations.

                              (b) ( ) Intercept, analyze, and report timely intelligence informa-
                              tion derived from friendly emitters to appropriate enemy command-
                              ers.

                              (c) ( ) Accurately locate and target friendly forces communica-
                              tions and electronic emitters by DF.

                              (d) ( ) Conduct meaconing operations against both TACAN and
                              low-frequency automatic direction finding (ADF) navigation re-
                              ceivers.

                              (e) ( ) Access and gain temporary control of commercial digital
                              telecommunications switches and deny access to satellite communi-
                              cations switches in geosynchronous orbit.

                              (f). ( ) Employ malicious logic techniques against our information
                              systems.

                    c. ( ) Friendly. See Annex A (Task Organization).

                         (1) ( ) Higher headquarters or other specific organizations that will
                         provide CIS to (unit) in a specific operation.

                         (2) ( ) The command relationship between friendly forces is shown in
                         Annex J (Command Relationships) to this OPORD.

                         (3) ( ) Attachments and Detachments

                              (a) ( ) (See Annex A (Task Organization) to this OPORD.

                              (b) ( ) When OPCON is taken of MAGTF units as (unit) forms
                              during compositing, MARFOR CIS assets will be listed separately.

                    d. ( ) Assumptions. (State the assumptions that establish essential criteria
                    for development of the annex.)

              3. ( ) MISSION. Commencing and terminating on order, (unit) communica-
              tions organizations provide, install, operate, and maintain the internal and exter-
              nal communications and support the installation, operation, and maintenance of
              information systems for reliable C2.

                                                      (Page number)
                                                  CLASSIFICATION


---

J-6 ________________________________________________________________________________________________ MCWP 6-22

                                                  CLASSIFICATION

          4. ( ) EXECUTION

                a. ( ) Commander’s Intent. Synopsis of the commander’s intent that bears on
                employing CIS.

                b. ( ) Guiding Principles

                     (1) ( ) The procedures contained in references (a) through (n) will be used.

                     (2) ( ) (Unit) operations will be conducted in a hostile EW environment.
                     The following degradations are to be expected.

                          (a) ( ) Loss of DCS entry due to equipment damage or circuit path loss.

                          (b) ( ) Isolation of a headquarters due to loss of wideband systems.

                          (c) ( ) Hostile interference on all terrestrial/satellite MCR and SCR
                          systems (jamming).

                          (d) ( ) Loss of a switchboard due to component failure or hostile ac-
                          tion.

                          (e) ( ) Loss of a satellite asset due to EW or destruction of the satellite.

                          (f) ( ) Disruption or loss of information systems due to component
                          failure or hostile action.

                     (3) ( ) Frequency changes, radio transmission brevity, and, on occasion,
                     complete EMCON will be employed in order to facilitate control and reduce
                     anticipated interference with communications.

                     (4) ( ) Backup CIS equipment and alternate communications paths will be
                     planned and installed to enhance reliability, flexibility, and responsiveness of
                     CIS networks.

                     (5) ( ) Based on coordination with affected commanders and principal
                     staff officers, radio nets will be combined/pooled at the COCs and other C2
                     facilities to conserve the frequency spectrum and reduce communications re-
                     quirements.

                     (6) ( ) Information systems security and COMSEC measures will be em-
                     ployed to deny information of value to the enemy and to prevent loss or dis-
                     ruption of service through hostile action. Refer to Appendix 1
                     (Communications and Information Systems Security) to this annex for de-
                     tails.

                                                     (Page number)
                                                  CLASSIFICATION


---

Communications and Information Systems _______________________________________________________________ J-7

                                                 (CLASSIFICATION)

                         (7) ( ) The (unit) G-6/S-6 will be the single point of contact at this
                         headquarters for obtaining CIS services, support, or interface with high-
                         er headquarters, NTS, DISA, or other external agencies.

                    c. ( ) Operational Concept

                         (1) ( ) Every means available will be used to provide the commander
                         with the ability to exercise C2 and to accomplish the assigned mission.
                         It is the responsibility of the G-6/S-6 to make the commander fully
                         aware of the capabilities and limitations of available CIS.

                         (2) ( ) Subordinate unit CIS officers must advise the G-6 of situa-
                         tions, actual or potential, that could adversely affect MAGTF CIS sup-
                         port.

                         (3) ( ) The major limitation of the CIS network is the EW threat. The
                         enemy has the full capability to disrupt, intercept, and confuse friendly
                         forces CIS operations. Line-of-sight communications will be adversely
                         affected because of extremely rugged terrain throughout the AO.

                         (4) ( ) The critical vulnerability of CIS network is the degradation of
                         the common tactical picture during extended COC and CP displace-
                         ments.

                         (5) ( ) The COG of the CIS network is the capability to adapt and
                         scale the network through extensive retransmission and backup systems
                         configurations. This provides full support of maneuver, intelligence,
                         fires, CSS, and force protection throughout the AO.

                         (6) ( ) Appendix 1 (Communications and Information Systems Se-
                         curity) to this annex lists measures designed to deny information to un-
                         authorized persons.

                         (7) ( ) Appendix 2 (Command and Control Protection) to this annex
                         describes measures to ensure continuous availability of friendly CIS.

                    d. ( ) Tasks and Responsibilities. Appendix 3 (Communications and In-
                    formation Systems Planning) to this annex highlights CIS planning consider-
                    ations for effective execution of the assigned mission.

                         (1) ( ) (Communications Unit)

                              (a) ( ) Provide the net control station(s) for all (unit) controlled
                              radio circuits. See Appendix 4 (Radio Circuit Plan) to this annex.

                                                      (Page number)
                                                  CLASSIFICATION


---

J-8 ________________________________________________________________________________________________ MCWP 6-22

                                                  CLASSIFICATION

                          (b) ( ) Ensure that information on call signs and routing indicators is
                          promulgated to using staff sections/functional agencies. See Appendix 5
                          (Call Signs and Routing Indicators) to this annex.

                          c) ( ) Install, operate, and maintain wire and MCR communications
                          as described in Appendix 6 (Wire and Multichannel Radio Plan) to this
                          annex.

                          (d) ( ) Install, operate, and maintain the data communications network
                          as described in Appendix 7 (Data Communications Network Plan) to this
                          annex.

                          (e) ( ) Promulgate visual and sound signals for the operation. See Ap-
                          pendix 8 (Visual and Sound Communications) to this annex.

                          (f) ( ) Install, operate, and maintain a SYSCON and TECHCON fa-
                          cility in support of the (unit) communications networks. See Appendix 9
                          (Communications Control) to this annex.

                                  1. ( ) Ensure that a liaison representative is at higher and adja-
                                  cent headquarters to facilitate the direct handling of questions and/
                                  or problems relating to CIS.

                                  2. ( ) Ensure that the G-6/S-6 and appropriate watch officers
                                  are informed of the communications circuit status.

                                  3. ( ) Ensure strict compliance with G-6/S-6 assigned frequen-
                                  cies. See Appendix 10 (Frequency Management) to this annex.

                                  4. ( ) Ensure that the established power distribution system is
                                  properly grounded and that backup mobile power is available as
                                  necessary. See Appendix 11 (Power Requirements) to this annex.

                                  5. ( ) Ensure that CP displacements are hastily executed with
                                  the requisite communications network scaled to retain essential in-
                                  formation flow. See Appendix 12 (Command Post Displacement
                                  Communications) to this annex.

                                  6. ( ) Ensure that the TACSAT communications are installed,
                                  operated, and maintained as depicted in Appendix 13 (Tactical
                                  Satellite Communications) to this annex.

                                  7. ( ) Ensure that communications restoration is handled expe-
                                  ditiously. See Appendix 14 (Communications Restoration) to this
                                  annex.

                                                     (Page number)
                                                  CLASSIFICATION


---

Communications and Information Systems _______________________________________________________________ J-9

                                                  CLASSIFICATION

                                      8. ( ) Ensure that the G-6/S-6 and the command are kept
                                      informed about the status of the commercial (local civilian)
                                      telecommunications systems.

                              (g) ( ) Install, operate, and maintain a communications and elec-
                              tronics maintenance facility to inspect, repair, and/or replace faulty
                              communications and electronics equipment. See Appendix 15 (Spe-
                              cial Maintenance Procedures) to this annex.

                              (h) ( ) Establish and maintain messenger service, including
                              truck, helicopter, and motorcycle couriers, as directed in Appendix
                              16 (Messenger Service) to this annex.

                              (i) ( ) Install, operate, and maintain a communications center to
                              support (unit) with over-the-counter service for all Marine units/
                              agencies at the (unit) headquarters. See Appendix 17 (Communica-
                              tions Center) to this annex.

                              (j) ( ) Establish emergency action procedures for use in the
                              communications center and any other area containing classified
                              and/or cryptographic material. See Appendix 18 (Emergency Ac-
                              tion) to this annex.

                         (2) ( ) Radio battalion/SSU: Install, operate, and maintain MAGTF
                         CE special security communications terminal facilities.

                         (3) ( ) Ground Combat Element

                              (a) ( ) Install, operate, and maintain internal and external com-
                              munication circuits and information systems as directed in unit
                              SOPs and this annex.

                              (b) ( ) Be prepared to assume communications and crypto-guard
                              for (unit(s)) and to assume net control of (unit) circuits in the event
                              (unit) headquarters becomes a casualty.

                              (c) ( ) Install, operate, and maintain a SYSCON/TECHCON fa-
                              cility to ensure the rapid restoration/rerouting of communications
                              circuits.

                         (4) ( ) Aviation Combat Element

                              (a) ( ) Install, operate, and maintain internal and external com-
                              munications circuits and information systems as directed in unit
                              SOPs and this annex.

                                                      (Page number)
                                                  CLASSIFICATION


---

J-10 _______________________________________________________________________________________________ MCWP 6-22

                                                  CLASSIFICATION

                          (b) ( ) Install, operate, and maintain a SYSCON/TECHCON facility
                          to ensure the rapid restoration/rerouting of communications circuits.

                          (c) ( ) Be prepared to maintain TADIL A, TADIL B, TADIL J, AT-
                          DL-1, GBDL, and Link 1 connectivity with (fleet), (joint Service), and
                          NATO agencies.

                          (d) ( ) Ensure the necessary liaison to establish and maintain the nec-
                          essary MACCS interface with joint, other-Service, national, and interna-
                          tional agencies, as required.

                     (5) ( ) Combat Service Support Element. Install, operate, and maintain a
                     SYSCON/TECHCON facility to ensure the rapid restoration/rerouting of
                     communications circuits.

                e. ( ) Intelligence and Reconnaissance. State intelligence and reconnaissance
                support required even though they have been covered in Annexes B and C because
                Annex K may be distributed separately. If the information is very detailed, pre-
                pare an appendix to the CIS systems annex. If MILSATCOM is a requirement, en-
                sure it’s covered in Appendix 13.

                f. ( ) Coordinating Instructions

                     (1) ( ) Special Measures

                          (a) ( ) The G-6/S-6 will make special efforts to indoctrinate staff/
                          command personnel in alternate routes/means of communications to pre-
                          clude the confusion or delay of information due to outages in the high-
                          threat EW environment.

                          b) ( ) The communications support for linkup operations is found in
                          Appendix 19 (Communications for Linkup Operations) to this annex.

                          ((c) ( ) Specific communications procedures relative to air assets are
                          found in Appendix __ (Air Communications) to Annex __ (Air Opera-
                          tions) to this OPORD.

                          (d) ( ) Safety is paramount in working with CIS. Appendix 20 (Safe-
                          ty) to this annex identifies major safety measures and concerns.

                          e) ( ) Emergency evacuation operations require unique communica-
                          tions capabilities. See Appendix 21 (Noncombatant Evacuation Opera-
                          tions Communications) to this annex.

                                                     (Page number)
                                                  CLASSIFICATION


---

Communications and Information Systems _____________________________________________________________ J-11

                                                  CLASSIFICATION

                              (f) ( ) Detailed instructions for the ITSDN/DISN/DCS STEP
                              procedures are found in Appendix 22 (ITSDN/DISN/DCS) to this
                              annex.

                              (g) ( ) Detailed instruction designed to alleviate confusion in the
                              rapid task organization of (unit), with its necessary command com-
                              munications support shifts, is found in Appendix 23 (Task Organi-
                              zation/Communications Guard Shifts) to this annex.

                              (h) ( ) The description for handling emergency action communi-
                              cations is found in Appendix 24 (Emergency Action Communica-
                              tions) to this annex.

                              (i) ( ) To alleviate confusion and to aid in the organized assign-
                              ment of resources while embarked, Appendix 25 (Communications
                              and Information Systems Support for Embarked Units) to this annex
                              details assets available for (unit) use.

                              (j) ( ) Details for radio battalion/special security officer (SSO)
                              communications support are found in Appendix 26 (RadBn/SSO
                              Communications Support) to this annex.

                              (k) ( ) Procedures for effecting a reliable communications net-
                              work in geographic areas in which climatic conditions require spe-
                              cial consideration are found in Appendix 27 (Special Climatic/
                              Geographic Considerations) to this annex.

                              (l) ( ) Special considerations for establishing and coordinating
                              joint Service communications support are found in Appendix 28
                              (Joint Service Communications Coordination) to this annex.

                              (m) ( ) Instructions for establishing and coordinating communi-
                              cations connectivity with and in the host nation are found in Appen-
                              dix 29 (Host Nation Communications) to this annex.

                              (n) ( ) Special communications considerations necessary to sup-
                              port hardback (information pull) and connectivity to global infor-
                              mation systems are found in Appendix 30 (Global
                              Communications) to this Annex.

                              (o) ( ) Special instructions for establishing and coordinating
                              communications support for intelligence activities are found in Ap-
                              pendix 31 (Communications Support for Intelligence) to this annex.

                                                      (Page number)
                                                  CLASSIFICATION


---

J-12 _______________________________________________________________________________________________ MCWP 6-22

                                                  CLASSIFICATION

                          (p) ( ) Specific communications support relative to intelligence opera-
                          tions is addressed in Appendix 31 (Communications Support for Intelli-
                          gence) to this annex.

                          (q) ( ) Instructions for the establishment of Internet Protocol (IP) ad-
                          dresses are found in Appendix 34 (IP Address Assignments) to this annex.

                     (2) ( ) Information Management. This paragraph contains instructions to
                     ensure that employing CIS is coordinated with and supports the unit informa-
                     tion management plan. Detailed instructions will be addressed in Appendix
                     35 to this annex.

          5. ( ) ADMINISTRATION AND LOGISTICS.

                a. Administration.

                     (1) ( ) Required CIS status and other reports are listed in Appendix 32
                     (Reports) to this annex.

                     (2) ( ) Security violations will be reported in accordance with Appendix 1
                     (Communications and Information Systems Security) to this annex.

                     (3) ( ) Procedures to support the administrative formation of a unit at sea
                     are found in Appendix 33 (Compositing) to this annex.

                     (4) ( ) CPs

                                 MEF main: Vicinity (location). See reference (n) and Annex C (Op-
                                 erations).
                                 *List remaining MEF and other subordinate elements’ tactical,
                                 main, and rear echelons.

                b. ( ) Logistics

                     (1) ( ) See Annex D (Logistics/Combat Service Support).

                     (2) ( ) Units will deploy with the capability to perform basic organization-
                     al and field maintenance.

                     (3) ( ) The service support unit will provide intermediate maintenance (di-
                     rect support and general support) of all ground-common communications and
                     electronics equipment.

                                                     (Page number)
                                                  CLASSIFICATION


---

Communications and Information Systems _____________________________________________________________ J-13

                                                  CLASSIFICATION

                         (4) ( ) Water, billeting, messing, and generator fuel will be provided
                         by the unit that hosts multichannel teams.

                         (5) ( ) Communications units deploy with sufficient maintenance
                         equipment; repair parts (class IX); petroleum, oils, and lubricants (Class
                         III); batteries; and cable for ( ) days/weeks of sustained operations.

                         (6) ( ) Report maintenance problems for critical low-density items to
                         the G-6/S-6 immediately.

              6. ( ) COMMAND AND CONTROL

                    a. ( ) Command Relationships. Refer to Annex J for command relation-
                    ships.

                    b. ( ) CIS Plans. All subordinate commands down to battalion level sub-
                    mit unit CIS plans to this headquarters (Attn: AC/S G-6) NLT (date).

                                                                                                T.U. STARR
                                                                     Major General, U.S. Marine Corps

                                                                                               Commanding

              Appendices:
              1 Communications and Information Systems Security
              2 Command and Control Protection
              3 Communications and Information Systems Planning
              4 Radio Circuit Plan
              5 Call Signs and Routing Indicators
              6 Wire and Multichannel Radio Plan
              7 Data Communications Network Plan
              8 Visual and Sound Communications
              9 Communications Control
              10 Frequency Management
              11 Power Requirements
              12 Command Post Displacement Communications
              13 Tactical Satellite Communications
              14 Communications Restoration
              15 Special Maintenance Procedures
              16 Messenger Service
              17 Communications Center

                                                      (Page number)
                                                  CLASSIFICATION


---

J-14 _______________________________________________________________________________________________ MCWP 6-22

                                                  CLASSIFICATION

          18 Emergency Action
          19 Communications for Linkup Operations
          20 Safety
          21 Noncombatant Evacuation Operations Communications
          22 ITSDN/DISN/DCS
          23 Task Organization/Communications Guard Shifts
          24 Emergency Action Communications
          25 CIS Support for Embarked Units
          26 RadBn/SSO Communications Support
          27 Special Climatic/Geographic Considerations
          28 Joint Service Communications Coordination
          29 Host Nation Communications
          30 Global Communications
          31 Communications Support for Intelligence
          32 Reports
          33 Compositing
          34 IP Address Assignments
          35 CIS Support for Information Management

          OFFICIAL:

          O.N.E. EAGLE
          Colonel, USMC
          AC/S G-6

          DISTRIBUTION:


---

                               Appendix K

CIS Threat Assessment Planning Checklist

This checklist is designed to assist C2 planners in  q What means of collection are used?
evaluating any threat capability to exploit and/or      q Satellite? What is the footprint? When are
disrupt our CIS. Planners must understand the               we most vulnerable?
threat to develop a C2 architecture that performs       q Overflights? What platforms are used? What
effectively with minimum disruption.                        capability do they have?
                                                        q Ground collection units? Where? Capabil-
Physical Destruction                                        ity? Range of their equipment? What fre-
                                                            quencies? Is it a part of a worldwide
q What type of weapons of mass destruction does             collection and reporting network?
   the enemy have?
                                                     q How is information used and distributed?
q Do they have antiradiation munitions? How ac-         q Direct targeting?
   curate are they?                                     q Tracking?
                                                        q Intelligence analysis?
q What means of delivery of munitions are avail-
   able?                                             Jamming

q Do they have trained saboteurs? Infiltrators?      q What type of jamming do they use? Barrage?
q What other means of physical destruction do           Spot?

   they possess?                                     q What frequencies are vulnerable?
q Where are we most vulnerable to ground at-         q What geographic area is likely to be affected?
                                                     q What equipment do they use? How is it de-
   tack?
q Does the enemy possess and train to use chemi-        ployed?
                                                     q What techniques are most likely to be used?
   cal and biological agents? What are their         q What circuits are most vulnerable?
   means of delivery?
q Are lasers used against CIS targets?               Imitative Deception

Collection Systems                                   q Level of sophistication?
                                                     q Do they have trained imitative communications
q Is the threat capable of—
   q Visible light, infrared imagery?                   deception operators?
   q Electronic surveillance, direction finding?     q How do they deploy?
   q Interception of radio signals, wiretapping?     q What techniques have they used in the past?
   q Gathering HUMINT and placing agents in
       the area?

                                                     (reverse blank)


---

                             Appendix L

Emission Classification and Designation

The International Telecommunication Union             Between 1.00 and 999 kHz shall be expressed in
(ITU) at its World Administrative Radio Confer-       kHz (letter K). Examples:
ence in 1979 in Geneva, Switzerland, adopted an
international standard method of forming radio        2.4 kHz = 2K40   180.4 kHz = 180K
emission designators. Emissions shall be desig-       6.0 kHz = 6K00   180.5 kHz = 181K
nated according to their necessary bandwidth and      12.5 kHz = 12K5  180.7 kHz = 181K
their classification character as prescribed by the
ITU. Information about the character codes in this    Between 1.00 and 999 MHz shall be expressed in
appendix is derived from the Manual of Regula-        MHz (letter M). Examples:
tions and Procedures for Federal Radio Frequen-
cy Management (also referred to as the Redbook        1.25 MHz = 1M25  10.0 MHz = 10M0
or NTIA Manual), pages 9-16 through 9-18. The         2.0 MHz = 2M00   202 MHz = 202M
current version of this manual is available on the
National Telecommunications and Information           Between 1.00 and 999 GHz shall be expressed in
Administration (NTIA), Department of Com-             GHz (letter G). Example:
merce, Web page: www.ntia.doc.gov or with the
frequency manager.

Necessary Bandwidth                                   5.65 GHz = 5G65

For a given class of emission, the width of the fre-  Classification
quency band is just sufficient to ensure the trans-
mission of information at the rate and with the       Emissions shall be classified and symbolized ac-
quality required under specified conditions. The      cording to their basic characteristics. Optional
necessary bandwidth shall be added just before        characteristics may be used. Normally, only the
the classification symbols and shall be expressed     basic characteristics are required.
by three numerals and one letter. The letter occu-
pies the position of the decimal point and repre-     Basic Characteristics
sents the unit of bandwidth. The first character
shall be neither zero nor K, M, or G. Necessary       q First character—type of modulation of the
bandwidths are expressed as follows:                     main carrier.

Between 0.001 and 999 Hz shall be expressed in        q Second character—nature of signal(s) modulat-
Hz (letter H). Examples:                                 ing the main carrier.

0.002 Hz = H002  25.3 Hz = 25H3                       q Third character—type of information to be
0.1 Hz = H100    400.0Hz = 400H                          transmitted.


---

L-2 ________________________________________________________________________________________________ MCWP 6-22

Modulation that is used only for short periods and  Amplitude and Angle Modulated
for incidental purposes (such as, in many cases,
for identification or calling) may be ignored pro-  CE mission in which the main carrier is amplitude
vided the necessary bandwidth as indicated is not   and angle modulated, either simultaneously or in a
thereby eased.                                      preestablished sequence.

First Character                                     Character                 Description
                                                         D     Amplitude and angle modulation
Unmodulated

Emission of an unmodulated carrier

Character                 Description               Pulse
     N     Unmodulated carrier
                                                    Emission of pulses (emissions for which the main
Amplitude Modulated                                 carrier is directly modulated by a signal that has
                                                    been coded into quantized form (e.g., pulse-code
Emission in which the main carrier is AM (includ-   modulation)), should be designated using the
ing cases where subcarriers are angle modulated).   characters listed above in amplitude modulated, or
                                                    angle modulated.

Character               Description                 Character                 Description
     A     Double sideband                               P
     H     Single sideband, full carrier                 K     Sequence of unmodulated pulses
     R     Single sideband, reduced or vari-             L
           able-level carrier                            M     Modulated in amplitude
     J     Single sideband, suppressed car-              Q
           rier                                          V     Modulated in width/duration
     B     Independent sidebands                         W
     C     Vestigial sideband                                  Modulated in position/phase
                                                         X
Angle Modulated                                                In which the carrier is angle modu-
                                                               lated during the period of the pulse
Emission in which the main carrier is angle modu-
lated.                                                         That is a combination of the forego-
                                                               ing or is produced by other means
Character                 Description
     F     FM                                                  Of cases not covered above, in which
     G     Phase modulation                                    an emission consists of the main car-
                                                               rier modulated either simultaneously
                                                               or in a combination of two or more of
                                                               the following modes: amplitude,
                                                               angle, pulse

                                                               In cases not otherwise covered (A
                                                               fully explanation for this selection
                                                               must be provided in supplementary
                                                               details)


---

Communications and Information Systems ______________________________________________________________ L-3

Second Character                                       Character             Description

                                                       C          Facsimile

Character              Description                     D          Data transmission, telemetry, and

0          No modulating signal                                   telecommand (The character D indi-

1          A single channel* containing quan-                     cates that data, telemetry, or telecom-

           tized or digital signal information                    mand information* is being

           without the use of a modulating sub-                   transmitted individually or that any

           carrier (this excludes time-division                   combination of the three is being

           multiplex)                                             transmitted simultaneously. If any

2          A single channel* containing quan-                     combination is being transmitted

           tized or digital signals with the use of               simultaneously, one of the multichan-

           a modulating subcarrier (this                          nel symbols 7, 8, or 9 must be used

           excludes time-division multiplex)                      for the second character.)

3          A single channel* containing analog         E          Telephony (including sound broad-

           signals                                                casting)

7          Two or more channels* containing            F          Television (video)

           quantized or digital signals                W          Combination of the above (Use only

8          Two or more channels* containing                       for multichannel systems that have

           analog signals                                         the capability to transmit all informa-

                                                                  tion* simultaneously.)

9          Composite system with one or more           X          Cases not otherwise covered (A full

           channels containing quantized or                       explanation is required in supplemen-

           digital signals together with one or                   tary details.)

           more channels containing analog sig-        *In this context, the word “information” does not
                                                       include information of a constant, unvarying nature
           nals                                        such as is provided by standard frequency emissions,
                                                       continuous wave, and pulse radars
X          In cases not otherwise covered (a full

           explanation for this selection must be

           provided in supplementary details)

*In this context, the word “channel(s)” refers to the  Optional Characteristics
radio frequency channel.                               The optional additional characteristics not nor-
                                                       mally required are—
Third Character
                                                       q Fourth character—details of signal(s)
Character               Description                    q Fifth character—nature of multiplexing

      N    No information transmitted
      A    Telegraphy for aural reception
      B    Telegraphy for automatic reception


---

L-4 ________________________________________________________________________________________________ MCWP 6-22

Fourth Character                                  Character               Description

Character               Description                     K    Sound of commercial quality with
                                                             the use of frequency inversion or
      A    Two-condition code with elements of          L    band splitting
           differing numbers and/or durations                Sound of commercial quality with
     B                                                  N    separate FM signals to control the
           Two-condition code with elements of          O    level of demodulated signal
      C    the same number and duration with-           P    Monochrome
           out error correction                         Q
      D                                                      Color
           Two-condition code with elements of               Combination of the above
      E    the same number and duration with                 Cases not otherwise covered
           error correction
      F                                           Fifth Character
           Four-condition code in which each
      G    condition represents a signal element  Character               Description
      H    (of one or more bits)
      J                                                 N    None
           Multicondition code in which each            C    Code-division multiplex (this
           condition represents a signal element             includes bandwidth-expansion tech-
           (of one or more bits)                        F    nique
                                                        T    Frequency-division multiplex
           Multicondition code in which each           W     Time-division multiplex
           condition or combination of condi-
           tions represents a character                 X    Combination of frequency-division
                                                             multiplex and time-division multi-
           Sound of broadcasting quality                     plex
           (monophonic))
                                                             Other types of multiplexing
           Sound of broadcasting quality (ste-
           reophonic or quadraphonic)

           Sound of commercial quality
           (excluding categories of sound given
           under characters K and L, below)


---

                                       USA FDC             USAF AWACS  USAF AOC                         USN ATDS SHIPS                          USMC DASC  USMC TAOC  USMC TACC  CJTF/JFACC  2=VHF 4=UHFSATCOM  1=HF 3=UHF  TRANSMISSION TYPE:      SOP CIRCUIT                      LEGEND:
                                                USAF FACP                                      USN FIGHTER/                                                                                                                                     DESIGNATIONS                     X = GUARD
                                                                                           ATTACK SQDNS                               USMC VMFA                                                                                                                              W = WHEN DIRECTED
                                                                                                                                  SQUADRONS                                                                                                                              A = AS REQUIRED
                                                                                 USAF CRC                                                                                                                                                                            M = MONITOR
                                                                                                                        USN NTDS SHIPS                                                                                                                           C = NET CONTROL

                                                                                                                                                                      X          C                              4                                 AC-1 JOINT AIR COORDINATION NET
                                                                                                                                                                                                                                                 AC-1A JOINT AIR COORDINATION NET
                                                                                                                                                                      W          C                              1                                AC-4 TACTICAL AIR DIRECTION NET
                                                                                                                                                                                                                                                AC-10A JOINT AIR SUPPORT
Figure M-1. Sample Radio Guard Chart.                     X                                                                                    X                      X          C                              3                                                                                          Appendix M
                                                A                                                                       X                                                                                                                                   COORDINATION NET
                                                                                 X                                                                                    X          C C                            2                               AC-10B JOINT AIR SUPPORT                        Sample Guard Charts

                                                                                 X                                                                                    X                                         1 OR                                         COORDINATION NET
                                                                                                                                                                                                                                                 AC-11 TADIL A (LINK 11)
                                                                       X         X       X                                                                 X          X          X           3                              1                    AC-13 TADIL B (LINK 11B)

                                       ROUTED THROUGH THE MULTICHANNEL NETWORKX XXX X    X                              X                                  X          X XX       C C                            1                                AC-14 JOINT ICN
                                                                                                                                                                                                                                                 AC-15 JOINT TSN
                                       ROUTED THROUGH THE MULTICHANNEL NETWORK           X                              X X                                X X                                                  1                                AC-16 JOINT DCN
                                       ROUTED THROUGH THE MULTICHANNEL NETWORK                                                                                                                                                                  AC-17 JOINT VPN
                                                                       X         X       X                                                                                       X                              1                                AC-18 JOINT TACTICAL AIR REQUEST
                                                                                                                                                                                                                                                AC-22 AIR TRAFFIC CONTROL
                                                                                 X       X                              X                                  X          X          C                              3                               JTF-17 JOINT SAR NET

                                                X                                X                                              X                                     X          C                              1 OR 1                           NONE TADIL C (LINK 4A)
                                                                                                                                                                                                                                                 NONE JMS
                                                                                 X       X                              X M                                X          X M                    3                              2                    NONE ATDL-1
                                                                                                                                                                                                                                                 NONE NADGE (NATO LINK 1)
                                                                       M         M       M                                      M                                                C

                                                                                      X  X                              X    X                             X                                                    3

                                       X           X                             X


---

M-2 ________________________________________________________________________________________________ MCWP 6-22

LEGEND:             AS DIR NONE MARFOR CMD NET
X = GUARD                    AS DIR NONE MARFOR TAC NET
W = WHEN DIRECTED                     AS DIR NONE MARFOR INTEL NET
A = AS REQUIRED                                 AS DIR NONE MARFOR COMM COORD
M = MONITOR
C = NET CONTROL                                            712A MEF CMD NET 1
                                                                    712B MEF CMD NET 2
SOP CIRCUIT                                                                   713A MEF TAC 11
DESIGNATIONS                                                                           713B MEF TAC 2
                                                                                                 715 MEF ALERT BRDCAST2112112
TRANSMISSION TYPE:                                                                                         717A MEF INTEL 1
1=HF 3=UHF                                                                                                          717B MEF INTEL 2
2=VHF 4=UHFSATCOM                                                                                                            721 MEF CSS
                                                                                                                                        751A MEF COMM COORD 1
                                                                                                                                                 751B MEF COMM COORD 2
                                                                                                                                                           NONE TAR/HR 1
                                                                                                                                                                     NONE TAR/HR 2
                                OR 1                       1           1                                                                                                          2

                                4

MARFOR HQ           C  C  C  C

MEF HQ              X X X    X  C C C    C C C C     X  C C            X  X

MAW TACC                        XWX WX         XW X     X  A W W
MAR DIV HQ
FSSG HQ                         XWX WX         X W X    X A            X  X

                                XWX WX         XW C     X A            W W

DASC                                                                   C C

                    Figure M-1. Sample Radio Guard Chart (continued).


---

Communications and Information Systems ______________________________________________________________ M-3

                                               Figure M-2. Sample IP Network Diagram.
                                                                                                                    (reverse blank)


---



---

                                         Appendix N

                                  Points of Contact

Headquarters, United States Marine Corps (C4I)  Command and Control Systems School

http://www.usmc.mil                             Marine Corps University

DSN        327-5561                             http://www.ccss.quantico.usmc.mil

Commercial (703) 607-5538                       DSN        278-2438

                                                Commercial (703) 784-2438

Marine Corps Network Operations Center

Help Desk                                       Marine Corps Communications Electronics School

http://www.noc.usmc.mil                         MCAGCC

DSN        278-5300                             DSN        957-3707 (Ops)

Commercial (703) 784-5300

                                                Marine Corps Tactical Systems Support Activity

Architecture Branch                             http://www.mctssa.usmc.mil

Requirements Division                           DSN        365-2167

Marine Corps Combat Development Command         Commercial (760) 725-2167

http://www.archvision.quantico.usmc.mil

DSN        278-6049                             National Telecommunications and Information
                                                Administration
Commercial (703) 784-6049                       Department of Commerce

Marine Corps Systems Command                    (Frequency Management-Emission Designator
                                                Codes)
C4I Directorate, Code CCR, MCHS                 http://www.ntia.doc.gov

http://www.marcorsyscom.usmc.mil

DSN        278-5610

Commercial (703) 784-5610                       Naval In-Service Engineering Activity-East

(This WWW site has links to the following:      (INFOSEC)

Marine Corps Computer Buyer’s Guide             E-mail     Questions@infosec.nosc.mil

DII COE                                         http://infosec.nosc.mil

MARCORSYSCOM                                    DSN        563-8878/8879

DefenseLINK                                     Commercial 800-304-4636/800-974-5426

MarineLINK)

Doctrine Division, MCCDC                        Naval Computer Incident Response Team
                                                (NAVCIRT) Hotline
http://www.doctrine.quantico.usmc.mil           NAVCIRT NIPRNET
                                                E-mail NAVCIRT@fiwc.navy.mil
DSN        278-6229/33 (Unclassified)           Commercial 888-NAVCIRT/800-628-8893

fax        x-2917

Commercial (703) 784-xxxx

                                                                            (reverse blank)


---

                    Appendix O

               Glossary

Section I. Acronyms and Abbreviations

AAAV ........ advanced amphibious assault vehicle                     BDA ............................. battle damage assessment
AAV........................... assault amphibious vehicle             BGLCSS ...... Battle Group Logistics Coordinated
AAW .............................................. antiair warfare
ACE ............................... aviation combat element                                                    Support System
ACI....................................air combat intelligence        BGIXS ......... Battle Group Information Exchange
ACOM .................................... Atlantic Command
ACP.............. Allied Communications Publication                                                                      System
AC/S....................................assistant chief of staff      BGP.................................border gateway protocol
ADCP.........air defense communications platform                      BGPHES ................Battle Group Passive Horizon
ADF ........................... automatic direction finding
ADNS...........Automated Digital Network System                                                             Extension System
ADP ............................ automated data processing            BLT....................................battalion landing team
AFATDS ......... Advanced Field Artillery Tactical                    Bn.............................................................battalion
                                                                      bps..................................................bits per second
                                             Data System              BUU ............................................... basic user unit
AFFOR....................................... Air Force Forces
AIS ........................automated information system              C2........................................command and control
ALICE............. all-purpose lightweight individual                 C3........... command, control and communications
                                                                      C3I ....... command, control, communications, and
                                    carrying equipment
AM ..................................... amplitude modulation                                                       intelligence
ANCD ..................... automated net control device               C4......... command, control, communications, and
ANGLICO .......air/naval gunfire liaison company
AO.............................................area of operations                                                     computers
AOC ........................ air operations center (USAF)             C4I .............. command, control, communications,
AOI ................................................area of interest
AOR .....................................area of responsibility                                  computers and intelligence
ARFOR .............................................Army Forces        CAIMS...... Conventional Ammunition Integrated
ASIP.....advanced systems improvement program
ATC ........................................... air traffic control                                      Management System
ATDL................................Army tactical data link           CATF ............ commander, amphibious task force
ATF .................................... amphibious task force        CBIRF.................... Chemical/Biological Incident
ATFIC ..............................ATF intelligence center
ATLASS .... Asset Tracking Logistics and Supply                                                                Response Force
                                                                      CCIR ................commander’s critical information
                                                   System
ATM......................... asynchronous transfer mode                                                           requirements
ATO ............................................ air tasking order    CCR ........................ common computer resources
AUI ..............................autonomous unit interface           CDE ...................... common desktop environment
AUTODIN .................Automatic Digital Network                    CD.................................................... compact disk
AWACS ...... airborne warning and control system                      CD-ROM .......... compact disk–read only memory
                                                                      CE ............................................ command element
                                                                      CENTCOM.............................. Central Command
                                                                      CEOI ........ communications-electronics operating

                                                                                                                    instructions
                                                                      CFC..........................Combined Forces Command
                                                                      CG.......................................commanding general;


---

O-2 ________________________________________________________________________________________________ MCWP 6-22

                                  guided missile cruiser            ConEx ...................................... Container Express
CGS..................................common ground station          CONPLAN........................................ concept plan
CHBDL .......... common high-bandwidth data link                    CONUS......................... continental United States
CI ............................................counterintelligence  COP.......................... common operational picture
CIC.............................. combat intelligence center        COTS ............................. commercial off the shelf
CINC ......................................commander in chief       CP................................................... command post
CINCNORAD.......... Commander in Chief, North                       CPOG................ chemical protective overgarment
                                                                    CPU................................... central processing unit
           American Aerospace Defense Command                       CRC .......................... control and reporting center
CIS ......communications and information systems                    CRITICOMM ................. critical communications
CISC............... complex instruction set computing               C/S .................................................... chief of staff
CISCO.......Cisco Systems (a computer company)                      CSDTS ........ common shipboard data terminal set
CISO ..........communications information systems                   CSMA/CD .......carrier sense multiple access with

                                                    officer                                               collision detection
CJCS .......... Chairman of the Joint Chiefs of Staff               CSR-TEP .... circuit switch routing-task execution
CJCSI ......... Chairman of the Joint Chiefs of Staff
                                                                                                                           plan
                                               instruction          CSS .................................. combat service support
CJCSM....... Chairman of the Joint Chiefs of Staff                  CSSE...................combat service support element
                                                                    CSSOC............combat service support operations
                                                   manual
CJTF..........................commander, joint task force                                                                center
CLF ............................. commander, landing force          CSU........................................channel service unit
CMD ......................................................command   CTAPS ..................contingency theater automated
CMS .... communications security material system
COA ............................................. course of action                                          planning system
COC .............................. combat operations center         CTT....................... commander’s tactical terminal
CODEC ...........................................coder-decoder      CUDIXS............common user digital information
COE ................... common operating environment
COE-V ...common operating environment-variant                                                              exchange system
COG ............................................ center of gravity  CV...................................................aircraft carrier
COMINT................. communications intelligence                 CVN ..................................aircraft carrier, nuclear
comm .......................................... communications      CVSD................continuously variable slope delta
COMMARFOR ..........commander, Marine Corps
                                                                    DACT............................................ data automated
                                                     forces                                      communications terminal
COMMARFORLANT......... Commander, Marine
                                                                    DAMA ..............demand assigned multiple access
                                 Corps Forces, Atlantic             DARPA................... Defense Advanced Research
COMMARFORPAC............ Commander, Marine
                                                                                                            Projects Agency
                                  Corps Forces, Pacific             DAS ...................................... direct access service
COMMARFORRES ............ Commander, Marine                         DASC...............................direct air support center
                                                                    DASC(A) ........direct air support center (airborne)
                                  Corps Forces Reserve              DAT ...........................................digital audio tape
COMMARLOGBASES....... Commander, Marine                             DATACOMM..................... data communications
                                                                    dBm.........decibels referred to 1 milliwatt; decibel
                                 Corps Logistics Bases
COMM BN .................. communications battalion                                                                  millivolts
COMM COORD......communications coordinator                          DCE .............. distributed computing environment
COMNAVFOR ........... Commander, Navy Forces                        DCN ..........................Data Link Coordination Net
COMPHIBGRU...commander, amphibious group                            DCO .......................................... dial central office
COMPUSEC .............................computer security             DCS................. Defense Communications System
COMSEC ...................... communications security


---

Communications and Information Systems ______________________________________________________________ O-3

DCT ...................digital communications terminal                  ESM .............electronic warfare support measures
DD...........................................................destroyer  EUCE ..................... end user computer equipment
DDG ........................................................destroyer   EW ................... electronic warfare; early warning
DDN..................................Defense Data Network               EW/C .................................. early warning/control
DEERS................. Defense Eligibility Enrollment                   EWCC.......electronic warfare coordination center

                                      Reporting System                  F .....................................................................flash
DEUCE ..................................downsized end-user              FACP ...............................forward air control post
                                                                        FAD ....................................... fighter air direction
                                  computing equipment                   FAPES ............Force Augmentation Planning and
DF ...............................................direction finding
DII ...................defense information infrastructure                                                     Execution System
DISA .........Defense Information Systems Agency                        fax ........................................................... facsimile
DISN ....... Defense Information Systems Network                        FDC........................................ fire direction center
DLTU.........................digital line termination unit              FDDI ..................... fiber distributed data interface
DMR ....................................digital modular radio           FFCC..................... force fires coordination center
DMS..............................Defense Message System                 FFIR .........friendly force information requirement
DNS .................................. Domain Name System               FIWC ...............Fleet Information Warfare Center
DNVT ................ digital nonsecure voice terminal                  FLTSAT............................................ fleet satellite
DOD................................. Department of Defense              FLTSATCOM........fleet satellite communications
DODD ............................................DOD directive          FLTSEVOCOM.........................fleet secure voice
DODIIS .... DOD Intelligence Information System
DON ...............................Department of the Navy                                                       communications
DSCS ............. Defense Satellite Communications                     FM...................................... frequency modulation
                                                                        FMF ........................................ Fleet Marine Force
                                                   System               FMFM........................ Fleet Marine Force manual
DSN ...........................Defense Switched Network                 FO ..................................................Flash Override
DSSCS ........ Defense Special Security Communi-                        FSC2S ..........Fire Support Command and Control

                                          cations System                                                                   System
DSU ............................................ data service unit      FSCC................... fire support coordination center
DSVT .................digital subscriber voice terminal                 FSK .................................. frequency shiftkey(ing)
DTC .................................digital technical control          FSSG..........................force service support group
DTD ...................................... data transfer device         ft. ............................................................. foot; feet
DTE.................................data terminal equipment
DTG .............................digital transmission group             GARC .................................... GCCS ATO review
DWTS ....Digital Wideband Transmission System                           GB ............................................................. gigabite
                                                                        GBDL................................ ground-based data link
EA ............................................... electronic attack    GBNP....................Global Block Numbering Plan
EAF ..................................... expeditionary airfield        GBS............................... Global Broadcast System
EEFI ....essential elements of friendly information                     GCA ......................... ground controlled approach
e.g....................................................... for example  GCCS ...... Global Command and Control System
EGP .............................. exterior gateway protocol            GCE .................................ground combat element
EHF .............................. extremely high frequency             GCS.................................... ground control station
ELINT ................................ electronic intelligence          GCSS .................Global Combat Support System
EMCON ...................................... emission control           GENSER...................... general service (message)
EMI ..........................electromagnetic interference              GHz ......................................................... gigahertz
EP..........................................electronic protection       GMF.................................... ground mobile forces
EPLRS ........ enhanced position location reporting                     GOTS ............................. government off the shelf

                                                    system


---

O-4 ________________________________________________________________________________________________ MCWP 6-22

GPS .............................. global positioning system                  INFOSEC.............................. information security
GPSIU ........... global positioning system interface                         INMARSAT......... international maritime satellite
                                                                              INSCOM................... U.S. Army Intelligence and
                                                      units
GSORTS ............. Global Status of Resources and                                                                Security Command
                                                                              INTELINK...................................intelligence link
                                        Training System                       INTELINK-S ................... intelligence link-Secret
GTN .................... Global Transportation Network                        I/O ...................................................... input/output
GUI .................................. graphical user interface               IP ................................................. internet protocol
                                                                              IPA ..................................imagery product archive
H&S ............................... headquarters and service                  IPB ......intelligence preparation of the battlespace
HAVE QUICK................jam-resistant UHF radio                             IRM....................... information resource manager
HAZMAT ..............................hazardous materials                      ISC .....................information systems coordinator
HD.......................................... helicopter direction             ISMO ...............information systems management
HDC .............................helicopter direction center
HDLC......................... high-level data link control                                                                        officer
HF ................................................. high frequency           ISO .........................International Organization for
HFRG.........................high frequency radio group
HLZ.................................. helicopter landing zone                                                          Standardization
heavy HMMWV .....heavy variant, high-mobility,                                IT-21 .............information technology for the 21st

                        multipurpose wheeled vehicle                                                                             century
HMMWV... high mobility multipurpose wheeled                                   ITP ............................integrated terminal program
                                                                              ITSDN............. Integrated Tactical-Strategic Data
                                                   vehicle
HPS ................................ high-performance server                                                                    Network
HPW... high-performance workstation/application                               ITU.......International Telecommunications Union
                                                                              IW ..........................................information warfare
                                                     server                   IWF ................................... inter-working function
HQ..................................................... headquarters
HQMC ..................... Headquarters, Marine Corps                         JANAP .................... Joint Army, Navy, Air Force
HR ............................................. helicopter request                                                         publication
HUMINT ................................ human intelligence
Hz ...................................................................hertz   JBS ...................................Joint Broadcast Service
                                                                              JCCC............joint communications control center
I .............................................................immediate      JCSE......... joint communications support element
IAS ............................intelligence analysis system                  JDISS ........Joint Deployable Intelligence Support
IBS ............................integrated broadcast service
ICN............................................idle channel noise                                                                System
ID ..................................................... identification       JEPES...... Joint Engineer Planning and Execution
IDNX ........... integrated digital network exchange
i.e..................................................................that is                                                     System
IEEE.............................. Institute of Electrical and                JFACC ...... joint force air component commander
                                                                              JFC .................................... joint force commander
                                   Electronic Engineers                       JFLCC.....joint force land component commander
IFF............................. identification, friend or foe                JFMCC ...............joint force maritime component
IFSAS........interim fire support automated system
IGRP ...................................... interior routing and                                                            commander
                                                                              JIEO ................ Joint Interoperability Engineering
                                 encapsulation protocol
IMRAS.........Individual Manpower Requirements                                                                            Organization
                                                                              JMCIS ...... Joint Maritime Command Information
                               and Availability System
                                                                                                                                 System
                                                                              JMCOMS ....................................... Joint Maritime

                                                                                                            Communications System


---

Communications and Information Systems ______________________________________________________________ O-5

JMTCSS........................... Joint Maritime Tactical                LPD............................. amphibious transport dock
                 Communications Switching System                         LPH................................. amphibious assault ship
                                                                         LSB ......................................logistic support base;
JNAV ...................................... JOPES Navigation
JOPES .....................Joint Operation Planning and                                                landing support battalion
                                                                         LSD........................................... dock landing ship
                                      Execution System                   LZ...................................................... landing zone
JSIPS .................................Joint Services Imagery            LZCT ........................... landing zone control team

                                     Processing System                   m .................................................................. meter
JSIPS-N.............................................. JSIPS-Navy         MACCS ............ Marine air command and control
JSOTF ..............joint special operations task force
JSTARS ................ joint surveillance target attack                                                                     system
                                                                         MACG ........................... Marine air control group
                                             radar system                MACS .......................Marine air control squadron
JTF .................................................joint task force    MAFC ............... MAGTF all-source fusion center
JTIDS ...... Joint Tactical Information Distribution                     MAG ................................... Marine aircraft group
                                                                         MAGTF ...................Marine air-ground task force
                                                   System                MAGTF II............Marine air-ground task force II
JTT ...................................... joint tactical terminal       MALS ......... Marine Aviation Logistics Squadron
JULLES .......................... Joint Universal Lessons                MARCOMMDET...........Marine communications

                                         Learned System                                                               detachments
JWICS ..................... Joint Worldwide Intelligence                 MARCORMATCOM ....... Marine Corps Material

                              Communications System                                                                      Command
                                                                         MARCORSYSCOM......... Marine Corps Systems
kbps ......................................... kilobits per second
kHz.......................................................... kilohertz                                                  Command
km .......................................................... kilometer  MARDIV .................................... Marine Division
                                                                         MARFOR..............................Marine Corps forces
LAAD .............................. low altitude air defense             MARFORLANT... Marine Corps Forces, Atlantic
LAAM ............................ light antiaircraft missile             MARFORPAC........Marine Corps Forces, Pacific
LAN ......................................... local area network         MARFORRES ....... Marine Corps Forces Reserve
LAR .......................light armored reconnaissance                  MASS....................... Marine air support squadron
LAV .................................... light armored vehicle           MATCD ..... Marine air traffic control detachment
LCAC..............................landing craft air cushion              MAW ....................................Marine aircraft wing
LCC............................ amphibious command ship                  Mb........................................................... megabite
LCU .......................................landing craft, utility        Mbps ................................... megabites per second
LDR ..................................................low data rate      MCAGCC ....................Marine Corps Air-Ground
LFOC ...................landing force operations center
LFSP .......................... landing force support party                                                        Combat Center
LGM..................................loop group multiplexer              MCCC................ Marine Corps Command Center
LHA ..............general purpose amphibious assault                     MCCDC ...... Marine Corps Combat Development

                                                       ship                                                              Command
LHD ..............general purpose amphibious assault                     MCDP ........... Marine Corps doctrinal publication
                                                                         MCHS .................Marine common hardware suite
                              ship (with internal dock)                  MCIXS... maritime cellular information exchange
LOGAIS..............logistics automated information
                                                                                                                             system
                                                    system               MCMO........MEF COMSEC Management Office
LOG IR Plan ..... Logistics Information Resources                        MCO ...................................... Marine Corps order
                                                                         MCPP.................. Marine Corps Planning Process
                                                       Plan
LOGSAFE ............. logistics sustainment analysis

                               and feasibility estimator


---

O-6 ________________________________________________________________________________________________ MCWP 6-22

MCR........................................ multichannel radio          MS...............................message switch; Microsoft
MCRP ...........Marine Corps reference publication                      MSC .........................major subordinate command
MCTSSA ............ Marine Corps Tactical Systems                       MS-DOS ........... MicroSoft-disk operating system
                                                                        MSE ........................ mobile subscriber equipment
                                        Support Activity                MTACCS ............... Marine tactical command and
MCWP ......Marine Corps warfighting publication
MD ............................................................medical                                           control sections
MDL................................... MAGTF Data Library               MT Bn............................motor transport battalion
MDR ..........................................medium data rate          MTF ...................................... message text format
MDS....................Message Dissemination System                     MTS .................................Marine tactical systems
MDSS II ................ MAGTF Deployment Support                       MUX ...................................................... multiplex
                                                                        MWCS ... Marine wing communications squadron
                                                System II               MWSG .......................Marine wing support group
MECDL ....... mission equipment control data link                       MWSS.................. Marine wing support squadron
MED BN ....................................medical battalion
MEDEVAC.............................medical evacuation                  NADGE ......................NATO air defense ground
MEF ...........................Marine expeditionary force                                                            environment
MEF (Fwd) ................Marine expeditionary force
                                                                        NALCOMIS........ Naval Aviation Logistics Com-
                                                 (forward)                                    mand Management Information
MEPES.............. Medical Planning and Execution                                                                         System

                                                   System               NATO ........... North Atlantic Treaty Organization
METOC ......... meteorological and oceanographic                        NAVCIRT..................... Naval Computer Incident
MEU.............................Marine expeditionary unit
MEU(SOC) .... Marine expeditionary unit (special                                                                 Response Team
                                                                        NAVFOR .......................................... Navy Forces
                                    operations capable)                 NAVMACS II............ Naval Modular Automated
MEWSS ........Mobile Electronic Warfare Support
                                                                                               Communications Subsystem II
                                                   System               NBC ..................nuclear, biological, and chemical
mHz ....................................................... megahertz   NCIS .......... Naval Criminal Investigative Service
MILSATCOM ........................... Military Satellite                NCS-E(D) ................. Net Control Station-EPLRS

                                       Communications                                                               (Downsized)
Milstar ..................... military strategic and tactical           NCTAMS......... naval computer and telecommun-

                                             relay system                                          ications area master station
MilVan ..............................................Military Van       NDI .................................. nondevelopmental item
MIME..........multipurpose internet mail extension                      NDP .............................naval doctrine publication
MIMMS ............. Marine Integrated Maintenance                       NECC....... Navy EHF communications controller
                                                                        NGF ................................................. naval gunfire
                                   Management System                    NIPRNET........ nonsecure internet protocol router
MLC..........................Marine Logistics Command
MLG...................................Marine Liaison Group                                                                network
MOE............................. measures of effectiveness              NIPS.......... Naval Intelligence Processing System
MOU ................... memorandum of understanding                     NIST...............National Institute of Standards and
MOOTW ......... military operations other than war
MOS..................... military occupational specialty                                                              Technology
MP ................................................. military police    NITF...........national imagery transmission format
MPF .......................maritime prepositioning force                NLT.................................................. not later than
MPS .......................maritime prepositioning ships                NOC ............................. network operations center
MRE.......................................... meal, ready to eat        nos. ........................................................... numbers
MRMS ........ Maintenance Resource Management                           NRZ ........................................... nonreturn to zero
                                                                        NST.................................. Navy standard terminal
                                                   System


---

Communications and Information Systems ______________________________________________________________ O-7

NSTISSI............National Security Telecommuni-                            PLA................................... plain language address
                    cations and Information Systems                          PLAD .................plain language address directory
                                    Security Instruction                     PLGR ................precise lightweight GPS receiver
                                                                             PLI .......................... position location information
NSW........................................ nonsecure warning                PLIS ......... Position Location Information System
NTCS-A .......... Navy Tactical Command System-                              PLRS .......... Position Location Reporting System
                                                                             POTS...........................plain old telephone system
                                                    Afloat                   ppm .............................. pulse position modulation
NTCSS ............Naval Tactical Command Support                             PPP.................................... point-to-point protocol
                                                                             PR..................................................... primary zone
                                                   System
NT DII COE...................... nodal terminal defense                      QuadCon .............................. Quadruple Container

                             information infrastructure                      R................................................................. routine
                     common operating environment                            RadBn ............................................ radio battalion
NTIA .............. National Telecommunications and                          RAM ................................random access memory
                                                                             RBECS.................. Revised Battlefield Electronic
                           Information Administration
NTP ............................... naval tactical publication                                                          CEOI System
NTS ..................naval telecommunications system                        RCU ........................................ remote control unit
                                                                             RDA ............ Requirement Development Analysis
OCAC ....... operations control and analysis center                          RECON OPS................reconnaissance operations
OEO ......................other expeditionary operations                     RED ..............................record of emergency data
OMFTS .......... operational maneuver from the sea                           regt .......................................................... regiment
OPCON ................................... operational control                RF................................................. radio frequency
OPLAN ...........................................operation plan              RISC................ reduced instruction set computing
OPNAVINST.............. Chief of Naval Operations                            RLT.................................regimental landing team
                                                                             RMC........................ remote multiplexer combiner
                                               Instruction                   RPC.....................................remote procedure call
OPORD ........................................ operation order               RRT............................. radio reconnaissance team
ops .........................................................operations      RSINISS.............. Revised SINCGARS integrated
OPSEC ................................... operations security
OPT ..............................operational planning team                                      COMSEC module, nonintegrated
OSCC ..............operational systems control center                                         COMSEC module support software
OSPF ................................. open shortest path first
OTCIXS ................. Officer in Tactical Command                         SABER...situational awareness beacon with reply
                                                                             SABRS...... Standard Accounting, Budgeting, and
                       Information Exchange System
OTH ............................................ over the horizon                                                  Reporting System
                                                                             SACC ...........supporting arms coordination center
P .................................................................priority  SADL ................Situational Awareness Data Link
PACOM ....................................Pacific Command                    SAM.....................................surface-to-air missile
PAL .............................................preaffiliation list         SAR........................................... search and rescue
PAO ........................... public affairs officer/office                SARC .......surveillance and reconnaissance center
PC.............................................personal computer             SASS....................... supporting arms special staff
PCMCIA ......... Personal Computer Memory Card                               SASSY ........ Supported Activities Supply System
                                                                             SATCOM.......................satellite communications
                              International Association                      SAW.................. standard application workstation
PCMT.......... personal computer message terminal                            SBB......................................... switched backbone
PDR.......................................... predefined reports
PHIBRON ........................... amphibious squadron
PIN ....................... personal identification number
PIP........................ product improvement program
PIR .....................priority intelligence requirement


---

O-8 ________________________________________________________________________________________________ MCWP 6-22

SCAMP ...............sensor control and management                     SSU ...................................... SIGINT support unit
                                                   platoon             STANAG .....................standardization agreement
                                                                       STAR-T .............Super High Frequency Tri-Band
SCI .............sensitive compartmented information
SCR ....................................... single-channel radio                      Advanced Range Extension Terminal
SCSI ...................small computer system interface                STEP ......................... standard tactical entry point
SECNAVINST. Secretary of the Navy instruction                          STOM ........................ship-to-objective maneuver
SECTEL......................................secure telephone           STU-III................... secure telephone unit-type III
SES............................... sensor employment squad             SUADPS ..............Shipboard Uniform Automated
SGT MAJ .......................................sergeant major
SHF ......................................super high frequency                                        Data Processing System
SI .............................................special intelligence   SYSCON.......................................systems control
SIDS.....secondary imagery dissemination system
SIGINT ...................................signals intelligence         TAC ........................................................... tactical
SINCGARS................. single-channel ground and                    TACAN............................... tactical air navigation
                                                                       TACC........................ tactical air command center
                                  airborne radio system                TACC(A) .......... tactical air control center (afloat)
SIP........................ systems improvement program                TACFIRE............................................ tactical fire
SIPRNET ............... secret internet protocol router                TACINTEL............................ tactical intelligence
                                                                       TACLOG .........................tactical-logistical group
                                                  network              TACO II.........Tactical Communications Protocol
SJA........................................ staff judge advocate       TACON..........................................tactical control
SL.................................................... switch locator  TACP .............................. tactical air control party
SLCP ............. Ship’s Loading and Characteristics                  TACSAT.......................................tactical satellite
                                                                       TAD .......................................tactical air direction
                                                 Pamphlet              TADC..........................tactical air direction center
SLRP .... survey, liaison, and reconnaissance party                    TADIL .................tactical digital information link
S&M.............................scheduling and movement                TADIXS A/B .............. Tactical Data Information
SMART-T ........ Secure Mobile Anti-Jam Reliable
                                                                                          Exchange System-Subsystem A/B
                                       Tactical Terminal               TAOC....................... tactical air operations center
SMTP ...................... simple mail transfer protocol              TAOM.................... tactical air operations module
SMU................................. smart multiplexing unit           TAR ......................................... tactical air request
SNAP .........Shipboard Nontactical ADP Program                        TARGET.......... Theater Analysis and Replanning
SNAPIII ....................Shipboard Nontactical ADP
                                                                                                Graphical Execution Toolkit
                                              Program III              TASS............tactical automated switching system
SNMP........ simple network management protocol                        TATC .............................tactical air traffic control
SOA ...........................sustained operations ashore             TBM..................................theater ballistic missile
SOCOM ................................ Southern Command                TBMCS....................... theater battle management
SOP .........................standing operating procedure
SPE.................. systems planning and engineering                                                               core system
SPEED ............system planning, engineering, and                    TCAC.......... technical control and analysis center
                                                                       TCAC PIP ...... tactical control and analysis center
                                       evaluation device
SPMAGTF .....................special purpose MAGTF                                            product improvement program
Sqdn ........................................................squadron  TCAE ....... Army Technical Control and Analysis
SRO...............sensitive reconnaissance operations
SSCC..... special security communications central                                                                        Element
SSCT .........special security communications team                     TC-AIMS ................Transportation Coordinators’
SSES ..................ship’s signals exploitation space
SSN ................................... social security number                                    Automated Information for
SSO ................................... special security officer                                            Movement System

                                                                       TCC......................tactical communications center


---

Communications and Information Systems ______________________________________________________________ O-9

TCIM ...............tactical communications interface              TSN...................................... track supervision net
                                                   module          TSO..................telecommunications service order
                                                                   TSR ...............telecommunications service request
TCO .............................tactical combat operations        TTP ................ tactics, techniques, and procedures
TCP .........................transmission control protocol
TDBM ................. technical database management               UAV................................unmanned aerial vehicle
TDDS ................ Tactical Receive Equipment and               UHF ....................................... ultrahigh frequency
                                                                   ULCS ...............................unit-level circuit switch
                       Related Applications Program                UNC .............................United Nations Command
                                    Data Dissemination             UNIX ........an open-architecture operating system
                                                                   UPS ......................... uninterruptible power supply
TDMA..................... time division multiple access            URL ............................... uniform resource locator
TDN ..................................... tactical data network    USA .......................................United States Army
TDS ........................................ tactical data system  USAF ...............................United States Air Force
TECHCON..................................technical control         USMC ....................... United States Marine Corps
TELNET ................. telecommunications network                USN ....................................... United States Navy
TERPES ........Tactical Electronic Reconnaissance                  USTRANSCOM .................... U.S. Transportation

                  Processing and Evaluation System                                                                 Command
TIBS...........tactical intelligence broadcast service
TM ............................................. technical manual  VHF ...................................... very high frequency
TMIP ........ Theater Medical Information Program                  VIXS .......... Video Information Exchange System
TNAPS+...............Tactical Network Analysis and                 VMF................................variable message format
                                                                   VMFA.................. Marine fighter attack squadron
                                  Planning System Plus             VPN ...........................................voice product net
T/O ....................................... table of organization  V/STOL ........... vertical/short takeoff and landing
TOW ........tube-launched, optically tracked, wire-
                                                                   W................................................................... watts
                        command link guided missile                WAN........................................ wide area network
TPFDD... time-phased force and deployment data                     WWW ..........................................world wide web
TRANSEC ...........................transmission security
TRE ..............................tactical receive equipment       XO...............................................executive officer
TRI-TAC............................... Tri-Service Tactical

                              Communications System
TRIXS ........ Tactical Reconnaissance Intelligence

                                                Exchange
TRSS .......................tactical remote sensor system
TSCM...... technical surveillance countermeasures


---

O-10 _______________________________________________________________________________________________ MCWP 6-22

                                      Section II. Definitions

                             A                         backbone—The high traffic density connectivity
                                                       portion of any communications network.
Allied Communication Publication 123 (ACP
123)—ACP 123 defines a military messaging              bandwidth—The difference between the limiting
standard. Allied nations have agreed to adopt the      frequencies of a continuous frequency band ex-
ACP 123 Military messaging standard to replace         pressed in hertz (cycles per second). The term
the current human-interactive ACP 127 proce-           bandwidth is also loosely used to refer to the rate
dures. The ACP 123 standard is based on the open       at which data can be transmitted over a given
system X.400 message standard, which provides          communications circuit. In the latter usage, band-
not only the format of the message, but the proce-     width is usually expressed in either kilobits per
dures and services required in its delivery.           second (kbps) or megabites per second (Mbps).

Allied Communication Publication 126 (ACP              baseband—The original band of frequencies pro-
126)—ACP 126 defines a character-oriented mes-         duced by a transducer, such as a microphone, tele-
sage standard for use in operations with allied        graph key, or other signal-initiating device, before
forces.                                                initial modulation. Baseband describes the signal
                                                       state before modulation, before multiplexing, fol-
application—A system or problem to which a             lowing demultiplexing, and following demodula-
computer is applied.                                   tion.

asynchronous—Pertaining to an operation that           bit error rate—The number of erroneous bits di-
occurs without a regular or predictable time rela-     vided by the total number of bits transmitted, re-
tionship to a specified event.                         ceived, or processed over some specified period.

asynchronous transfer mode (ATM)—A meth-               bomb—A computer program, generally mali-
od of digitized data transmission based on fixed-      cious in nature, hidden within or emulating anoth-
length cells. ATM can carry multiple types of da-      er program and designed to execute at a specific
ta—text, voice, imagery, and video—at high             future time or on the occurrence of a specific
speeds.                                                event.

asynchronous transmission—Data transmission                                         C
in which the instant that each character, or block
of characters, begins to be transmitted is arbitrary.  client-server architecture—A computer net-
However, the time of occurrence of each signal         working architecture, client-server defines a soft-
representing a bit within the character or block is    ware architecture and not a hardware architecture.
predictable.                                           A client software entity (client) requests a service
                                                       from a server software entity (server), which in
                             B                         turn fulfills the request. To fulfill the request the
                                                       server may provide data, perform processing
back lobe—Pertaining to a directional antenna,         tasks, control a peripheral, or request the services
the radiation occurring in a direction 180 degrees     of another server. A client can request services
from that of the main axis of radiation.               from multiple servers and a server can service


---

Communications and Information Systems _____________________________________________________________ O-11

multiple clients. Because clients and servers are     thenticity of a paper document. A message is
software entities, they can reside on the same        encrypted with the sender’s digital private key
computer or be on different computers in a net-       and the recipient decrypts the signature with the
work. Servers are designated according to the ser-    sender’s digital public key.
vices provided. A server providing access to
communications services would be called a com-        digital switch—A switch that performs time-di-
munications server.                                   vision multiplexed switching of digitized signals.
                                                      When used with analog inputs analog-to-digital
collision detection—A method by which a colli-        and digital-to-analog conversions are necessary.
sion is detected on a LAN transmission medium.
A collision occurs when more than one simulta-        digital transmission—The transmission of a dig-
neous transmission is attempted on the LAN.           ital bit stream that may include digitized voice or
                                                      data or both. The transmission signal itself may be
combat information—Unevaluated data, gath-            either discrete or continuous (analog).
ered by or provided directly to the tactical com-
mander which, due to its highly perishable nature     digital transmission group—A group of digi-
or the criticality of the situation, cannot be pro-   tized voice and/or data channels that have been
cessed into tactical intelligence in time to satisfy  combined (multiplexed) into a single digital bit
the user’s tactical intelligence requirements.        stream for transmission over communications me-
                                                      dia.
communications—A method or means of con-
veying information of any kind from one person        DISA megacenter—One of several large data
or place to another. (Joint Pub 1-02).                processing centers maintained and operated by
                                                      DISA, such as the Cleveland Center, which sup-
conditioned diphase signaling—A robust form           ports the Defense Finance and Accounting Ser-
of digital baseband signaling employed by TRI-        vice.
TAC equipment in which bits are encoded in the
phase of the signal.                                  domain name—The symbolic name assigned to a
                                                      host on an IP network. Syntactically the domain
                             D                        name consists of a sequence of names separated
                                                      by periods. A domain is a logical grouping of IP
data terminal equipment—A networked device,           hosts.
such as a PC, that is capable of transmitting and
receiving digital data signals over a communica-      domain name system—The online distributed
tions circuit.                                        database system used to relate (map) readable, al-
                                                      phabetic domain names with numeric IP address-
digital backbone—A term loosely applied to the        es.
TRI-TAC-based circuit switched communications
network employed by the Marine Corps. Used            double sideband—The transmission of a modu-
synonymously with switched backbone.                  lated carrier wave accompanied by both sidebands
                                                      resulting from modulation. The upper sideband
digital signature function—A cryptographic            corresponds to the sum of the carrier and modula-
technique for authenticating electronic docu-         tion frequencies, whereas the lower sideband cor-
ments, much as a written signature verifies the au-   responds to the difference between the carrier and
                                                      the modulation frequencies.


---

O-12 _______________________________________________________________________________________________ MCWP 6-22

                             F                        information system—The organized collection,
                                                      processing, transmission, and dissemination of in-
forward lobe—Pertaining to a directional anten-       formation, in accordance with defined procedures,
na, the radiation occurring along the main axis of    whether automated or manual. In information
radiation.                                            warfare, this includes the entire infrastructure, or-
                                                      ganization, and components that collect, process,
full duplex—Refers to a mode of transmission in       store, transmit, display, disseminate, and act on
which communication between two terminals             information. (Joint Pub 1-02)
takes place in both directions simultaneously.
                                                      in-line network encryptor—A cryptographic de-
                             G                        vice that permits the transmission of classified da-
                                                      ta on unclassified networks or SCI data on secret
gateway—In a communications network, a net-           networks. A key feature of in-line network en-
work node that is equipped for interfacing with       cryptors is that they only encrypt the data, not the
another network that uses different protocols. The    address information. In-line network encryptors,
term is loosely applied to a computer or computer     through software configuration and appropriate
software configured to perform the tasks of a         keying material, may be used to link multiple
gateway.                                              LANs of one classification level by using a data
                                                      communications network operating at a lower
                             H                        classification level.

half-duplex—Refers to a mode of transmission in       internet—The worldwide interconnection of in-
which communication between two terminals oc-         dividual computer networks operated by govern-
curs in either direction, but in only one direction   ment, industry, academia, and private parties. The
at a time. This is the typical mode of operation for  internet was originally developed by the Defense
tactical single-channel radios.                       Advanced Research Projects Agency (DARPA) to
                                                      interconnect laboratories and academic institu-
host—In a computer network, a computer that           tions engaged in government-sponsored research.
provides services to end users. Those services are
considered to be hosted on that computer. The         internet protocol (IP)—A DOD standard proto-
term host also refers to the computer on a network    col designed for use in interconnected systems
that performs network control functions.              (internets) of packet-switched communications
                                                      networks. The IP provides for transmitting blocks
                             I                        of data called datagrams from sources to destina-
                                                      tions, where sources and destinations are identi-
IDNX—Integrated Digital Network Exchange, or          fied by fixed length addresses (IP addresses).
IDNX, devices provide automated link bandwidth
management that allocates available circuits as       IP address—A unique numerical address as-
needed. These devices are used at network nodes       signed to each host on an IP network based on a
to allow for a virtual network with automatic rout-   standard scheme and by a central agency. Used to
ing and rerouting. IDNX devices are easily up-        communicate between hosts on the network.
graded to asynchronous transfer mode (ATM)
capability.                                           isochronous—Pertaining to data transmissions in
                                                      which the time interval separating two corre-
                                                      sponding signal state transitions is equal to the


---

Communications and Information Systems _____________________________________________________________ O-13

unit interval of that signal state or a multiple of    multaneously. Multichannel transmission may be
the unit interval.                                     accomplished by time-, frequency-, code-, and
                                                       phase-division multiplexing, or space diversity.
                             J
                                                       multiplexer—A device that combines (multiplex-
Joint Army, Navy, Air Force Publication                es) multiple input signals (information channels)
(JANAP)-128 local area network—A joint stan-           into an aggregate signal (common channel) for
dard for AUTODIN message formats and proce-            transmission.
dures. A data communications system that lies
within a limited geographic area, has a specific       multipurpose internet mail extension
user group, and uses a specific topology. A LAN        (MIME)— MIME is the internet standard proto-
is not part of a public switched telecommunica-        col for sending multipart, multimedia, and binary
tions network although it may be connected to          data by using e-mail. Typical uses of MIME in-
such a network.                                        clude sending images, audio, word processing
                                                       documents, programs, or even plain text files
                             L                         when it is important that the mail system does not
                                                       modify any part of the file. MIME also allows for
loop—A communication channel from a switch-            labeling message parts so that a recipient (or mail
ing center or an individual message distribution       program) may determine what to do with them.
point to the user terminal. In a telephone system, a   The MIME internet standard is described in RFC-
pair of wires running from a central office to a       1521.
subscriber’s telephone.
                                                                                    O
                             M
                                                       open systems—A system with characteristics that
media access method—The method by which a              comply with specific, publicly maintained (rather
terminal on a LAN accesses the LAN transmis-           than proprietary), readily available standards.
sion medium.                                           Such a system, by virtue of adherence to the stan-
                                                       dard, may be connected to other systems that
modem—In computer communications, a device             comply with those same standards.
used for converting digital signals into, and recov-
ering them from, quasi-analog signals that are         order wire—An auxiliary circuit or channel for
suitable for transmission over analog communica-       use by operating and/or maintenance personnel
tions channels.                                        for communications incident to establishing, op-
                                                       erating, maintaining, and controlling communica-
modulation—The process of varying a character-         tions facilities, systems and equipment.
istic (e.g., frequency, phase, amplitude) of a carri-
er signal in accordance with an information                                         P
bearing signal.
                                                       packet switch—A switch that breaks messages
multichannel—Pertaining to communications,             into data packets for transmission over a network
usually full duplex, on more than one channel si-      and reassembles data packets into messages upon
                                                       receipt.


---

O-14 _______________________________________________________________________________________________ MCWP 6-22

protocol—A formal set of specifications govern-        establishes a link to a remote host and handles the
ing the format and control of interaction among        translation of different mail file formats between
terminals communicating over a network.                hosts. To arrange for mail delivery, e-mail appli-
                                                       cations running on a particular host must make a
                             R                         call to SMTP which then handles the delivery.
                                                       SMTP uses internet domain names to find a con-
radio-wire integration—The combining of wire           nection, relying on the DNS to make the transla-
circuits with radio functions.                         tions to IP numeric addresses.

relational database—A database that is based on        simple network management protocol (SN-
the relational model. The relational model relies      MP)—The internet standard protocol used to pro-
on the mathematics of set theory, thereby provid-      vide the network management capabilities needed
ing a solid theoretical base for the management of     to monitor and control a network.
data. Relational databases are typically easier to
use and maintain than nonrelational databases.         simplex—Refers to a mode of operation in which
The relational model provides for improved data        communication between two terminals can take
availability, data integrity, and data security be-    place in only one direction.
cause the model rigorously defines these features
as part of the database, not as part of the processes  single sideband—A mode of communications in
that maintain the database.                            which the carrier wave and one sideband are sup-
                                                       pressed. Single sideband operation requires less
repeater—A device that amplifies, reshapes, re-        power at the transmitter for the same effective
times or performs a combination of these func-         signal at the receiver, a narrower frequency band
tions on an input signal for retransmission. The       can be used, and the signal is less affected by se-
input signal may be either analog or digital. Re-      lective fading or interference.
peaters are used to extend the distance that net-
work signals can be transmitted.                       skywave—A radio wave that reaches the receiv-
                                                       ing location after refraction from the ionosphere.
request for comment (RFC)—A document used
by the Internet Activities Board (the governing        synchronous—Pertaining to an operation that oc-
body for internet protocols) to develop and to         curs with a regular or predictable time relation-
configuration manage internet protocols.               ship to a specified event.

router—A device used to interconnect two or            systems network architecture (SNA)—A pro-
more data communication networks. The router           prietary network architecture developed by IBM.
reads the network address of all data packets and
forwards to the addressee via the best available                                    T
communications path.
                                                       T1 circuit—A communications circuit providing
                             S                         1.544 Mbps capacity.

simple mail transfer protocol (SMTP)—The in-           TELNET—The internet standard virtual terminal
ternet standard protocol used to facilitate the ex-    protocol that is used for remote terminal connec-
change of e-mail across an internet. SMTP              tion service. TELNET allows a remote terminal to


---

Communications and Information Systems _____________________________________________________________ O-15

login to and access services from a host computer       trusted workstation—A workstation that meets
by using dial-in or other network connections.          strict security accreditation standards and is con-
                                                        sidered secure from exploitation.
timing—The synchronization of communica-
tions signals. Of critical importance for digital                                    V
communications networks and for secure commu-
nications.                                              virus—A self-replicating malici attaches itself to
                                                        an application program or other executable
token—A bit pattern used in the token ring and          system component.
token bus media access methods for controlling
access to the medium.                                                               W

topology—In the context of a communications             wide area network—A term loosely applied to
network, the term topology refers to the way in         any communications network extending over a
which the stations or terminals attached to the net-    large geographic area.
work are interconnected. The common topologies
for local area networks are the star, ring, and bus.

transponder—1. An automatic device that re-             worm—An independent computer program de-
ceives, amplifies, and retransmits a signal on a        signed to self-replicate from computer to comput-
different frequency. 2. An automatic device that        er across computer networks often clogging
transmits a predetermined message in response to        networks and monopolizing computer system re-
a predefined received signal. (Note: Examples of        sources as it spreads.
transponders are identification, friend or foe (IFF)
systems and air-traffic-control secondary radar                                      X
(beacon radar) systems.) 3. A receiver-transmitter
which will generate a reply signal upon proper in-      X.400—Open system standard for e-mail.
terrogation. (Joint Pub 1-02) 4. Device in a com-
munications satellite that receives a signal from a     X.500—Open system standard for network direc-
sending earth station and retransmits the signal to     tory service.
one or more receiving earth stations.
                                                        X.509 certificate—Open system standard for se-
Trojan horse—A computer program containing              curity. Many internet protocols and applications
an apparently or actually useful function that also     employ public-key technology for security pur-
contains hidden functions that allow unauthorized       poses and require a public-key infrastructure to
collection, falsification, or destruction of data.      securely manage public keys for widely-distribut-
                                                        ed users or systems. The X.509 standard provides
trunk—A trunk is a single circuit between two           basis for such an infrastructure, defining data for-
switching centers or individual message distribu-       mats and procedures related to distribution of
tion points. This is in contrast to a loop, which is a  public keys via certificates digitally signed by
single circuit between the switching center or          certification authorities.
message distribution point and the individual sub-
scriber terminal. A trunk group is formed by two                                                     (reverse blank)
or more trunks between the same two points.


---

                                  Appendix P

         References and Related Publications

Standardized Agreements (STANAGs)

4206     The NATO Multi-Channel Tactical Digital Gateway—System Standards

4207     The NATO Multi-Channel Tactical Digital Gateway—Multiplex Group Framing

         Standards

4208     The NATO Multi-Channel Tactical Digital Gateway—Signalling Standards

4209     The NATO Multi-Channel Tactical Digital Gateway—Standards for Analogue to Dig-

         ital Conversion of Speech Signals

4210     The NATO Multi-Channel Tactical Digital Gateway—Cable Link Standards

4211     The NATO Multi-Channel Tactical Digital Gateway—System Control Standards

4212     The NATO Multi-Channel Tactical Digital Gateway—Radio Relay Link Standards

4213     The NATO Multi-Channel Tactical Digital Gateway—Data Transmission Standards

5040     NATO Automatic and Semi-Automatic Interfaces Between the National Switched

         Telecommunications Systems of the Combat Zone and Between These Systems and

         the NATO Integrated Communications System (NCIS)—For the Period 1979 to the

         1990s

Allied Communications Publications (ACPs)

121      Communications Instructions—General

122      Series Communications Instructions—Security

123      Common Messaging Strategy and Procedures

126      Communications Instructions Teletypewriter Procedures

167      Series Glossary of Communications-Electronics Terms

Department of Defense Publications

Directives (DODDs)

5200.1   Information Security Program
5200.28  Security Requirements for Automated Information Systems (AISs)
8320.1   DOD Data Administration

Instruction (DODI)

4630.8   Procedures for Compatibility, Interoperability, and Integration of Command, Control,
         Communications and Intelligence (C3I) Systems


---

P-2 ___________________________________________________________________________________________ MCWP 6-22

Chairman, Joint Chiefs of Staff (CJCS) Publications

Joint Publications (Joint Pubs)

0-2       Unified Action Armed Forces (UNAAF)
1-0       DOD Dictionary of Military and Associated Terms
3-0       Doctrine for Joint Operations
5-0       Doctrine for Planning Joint Operations
5-03.1    Joint Operation Planning and Execution System—Volume 1
6-0       Doctrine for Command, Control, Communications, and Computer (C4) Systems
          Support to Joint Operations
6-02      Joint Doctrine for Employment of Operational/Tactical Command, Control,
          Communications, and Computer Systems
6-02.1    Joint Connectivity Handbook

Manuals (CJCSMs)

6231.01A  Manual for Employing Joint Tactical Communications—Joint Tactical Systems
6231.02   Management
6231.03A  Manual for Employing Joint Tactical Communications—Joint Voice Communi-
6231.04   cations Systems
6231.05   Manual for Employing Joint Tactical Communications—Joint Data Systems
6231.06   Manual for Employing Joint Tactical Communications—Joint Transmission Sys-
6231.07A  tems
          Manual for Employing Joint Tactical Communications—Joint Communications
          Security
          Manual for Employing Joint Tactical Communications—Joint Technical Control
          Procedures and Systems
          Manual for Employing Joint Tactical Communications—Joint Network Manage-
          ment and Control

Instructions (CJCSIs)

6110.01   CJCS-Controlled Tactical Communications Assets
6230.03   Communications-Electronics Operation Instructions/Signal Operation Instruc-
          tions

Joint Army, Navy, Air Force Publications (JANAPs)

128       Automatic Digital Network (AUTODIN) Operating Procedures

137       Automatic Voice Network (AUTOVON) Operating Procedures


---

Communications and Information Systems _________________________________________________________ P-3

Army Publications

Field Manuals (FMs)

11-24     Signal Tactical Satellite Company
11-25     Signal Troposcatter Company
11-30     MSE Communications in the Corps/Division
11-32     Combat Net Radio Operations
11-41     Signal Support: Echelons Corps and Below (ECB)
11-43     Signal Leader’s Guide
11-50     Combat Communications within the Division (Heavy and Light)
24-2      Spectrum Management
24-11     Tactical Satellite Communications
24-18     Tactical Single-Channel Radio Communications Techniques
24-19     Radio Operator’s Handbook
24-26     Tactical Automatic Switching
100-6     Information Operations

Technical Manuals (TMs)

11-5820-  Operator’s Manual for SINCGARS Ground Combat Net Radio, ICOM Manpack
890-10-1  Radio AN/PRC-119A (NSN 5820-01-267-9482) (EIC: L2Q) Short Range Ve-
          hicular Radio AN/VRC-87A (5820-01-267-9480) (EIC: L22) Short Range Ve-
          hicular Radio with Single Radio Mount AN/VRC-87C (5820-01-304-2045)
          (EIC: GDC) Short Range Vehicular Radio with Dismount AN/VRC-88A (5820-
          01-267-9481) (EIC:L23) Short Range Vehicular Radio with Dismount and Single
          Radio Mount AN/VRC-88C (5820-01-304-2044) (EIC: GDD) Short Range/Long
          Range Vehicular Radio AN/VRC-89A (5820-01-267-9479) (EIC: L24) Long
          Range Vehicular Radio AN/VRC-90A (5820-01-268-5105)(EIC:L25) Short
          Range/Long Range Vehicular Radio with Dismount AN/VRC-91A (5820-01-
          267-9478) (EIC: L26) Long Range/Long Range Vehicular Radio AN/VRC-92A
          (5820-01-267-9477) (EIC: L27)

11-5820-  SINCGARS ICOM Ground Radio Operator’s Pocket Guide for Manpack Radio
890-10-2  AN/PRC-119A (NSN 5820-01-267-9482) (EIC: L2Q) Short Range Vehicular
          Radio AN/VRC-87A (5820-01-267-9480) (EIC: L22) Short Range Vehicular Ra-
          dio with Single Radio Mount AN/VRC-87C (5820-01-304-2045) (EIC: GDC)
          Short Range Vehicular Radio with Dismount AN/VRC-88A (5820-01-267-9481)
          (EIC: L23) Short Range Vehicular Radio with Dismount and Single Radio Mount
          AN/VRC-88C (5820-01-304-2044) (EIC: GDD) Short Range/Low Range Vehic-
          ular Radio AN/VRC-89A (5820-01-267-9479) (EIC: L24) Long Range Vehicu-
          lar Radio AN/VRC-90A (5820-01-268-5105) (EIC: L25) Short Range/Long
          Range Vehicular Radio with Dismount AN/VRC-91A (5820-01-267-9478) (EIC:
          L26) Long Range/Long Range Vehicular Radio AN/ VRC-92A (5820-01-267-
          9477) (EIC: L27)

11-5820-  SINCGARS ICOM Ground Radios used with Automated Net Control Device
890-10-6  (ANCD) AN/CYZ-10 Operator’s Pocket Guide Radio Sets Manpack Radio AN/
          PRC-119A) (NSN: N/A) (EIC: N/A) Vehicular Radios (AN/VRC-87A-C thru
          AN/VRC-92A) (NSN: N/A) (EIC: N/A)


---

P-4 ___________________________________________________________________________________________ MCWP 6-22

11-5820-  Operator’s Manual for SINCGARS Ground Combat Net Radio, ICOM Manpack
890-10-8  Radio, AN/PRC-119A (NSN 5820-01-267-9482) (EIC: L2Q), Short Range Ve-
          hicular Radio AN/VRC-87A (5820-01-267-9480) (EIC: L22), Short Range Ve-
          hicular Radio with Single Radio Mount AN/VRC-87C (5820-01-304-2045)
          (EIC: GDC), Short Range Vehicular Radio with Dismount AN/VRC-88A (5820-
          01-267-9481) (EIC: L23), Short Range/Long Range Vehicular Radio AN/VRC-
          88C (5820-01-304-2044) (EIC: 6DD), Short Range/Long Range Vehicular Ra-
          dio AN/VRC-89A (5820-01-267-9479) (EIC: L24), Long Range Vehicular Ra-
          dio AN/VRC-90A (5820-01-268-5105) (EIC: L25), Short Range/Long Range
          Vehicular Radio with Dismount AN/VRC-91A (5820-01-267-9478) (EIC: L26),
          Short Range/Long Range Vehicular Radio AN/BRC-92A (5820-01-267-
          9477)(EIC: L27) used with Automated Net Control Device (ANCD) (AN/CYZ-
          10) Precision Lightweight GPS Receiver (PLGR) (AN/PSN-11) Secure Tele-
          phone Unit (STU) Frequency Hopping Multiplexer (FHMUX)

Navy Publications

Navy Doctrine Publications (NDPs)

5         Naval Planning

6         Naval Command and Control

Navy Warfare Publication (NWP)

4         Basic Operational Communication Doctrine

Navy Technical Publications (NTPs)

3         Telecommunications Users Manual

4         Naval Telecommunications Procedures—Fleet Communications

5         Naval Telecommunications Procedures—Voice Communications

6         Naval Telecommunications Procedures—Spectrum Management Manual

Office of the Chief of Naval Operations Instruction (OPNAVINST)

5510.1H   Messages Requiring Special Handling, Information Security Program

Marine Corps Publications

Doctrine Publications (MCDPs)

1         Warfighting

1-1       Strategy

1-2       Campaigning

1-3       Tactics

2         Intelligence

3         Expeditionary Operations

4         Logistics

5         Planning

6         Command and Control


---

Communications and Information Systems _________________________________________________________ P-5

Warfighting Publications (MCWPs)

0-1.1      Componency
2-1        Intelligence Operations
3-1        Ground Combat Operations (in development)
3-2        Aviation Operations (in development)
3-25.5     Direct Air Support Center Handbook
3-25.7     Tactical Air Operations Center Handbook
4-1        Logistics Planning and Operations (in development)
5-1        Marine Corps Planning Process (in development)

Reference Publications (MCRPs)

5-2A       Operational Terms and Graphics
6-22A      TALK II-SINCGARS: Multiservice Communications Procedures for the Single-
           Channel Ground and Airborne Radio System
6-22B      Multiservice Procedures for Spectrum Management in a Joint Environment
6-22C      Radio Operator’s Handbook (in development)
6-22D      Field Antenna Handbook (in development)
6-22E      TTP For The AN/TSQ-1

Orders (MCOs)

1510.83A   Individual Training Standards (ITS)
P3000.18   Marine Corps Planner’s Manual
5236.2     ADP Resources Delegation Program Order
5271.4     E-Mail Policy and Guidance
P5510.14   AIS Security Program

Bulletin (MCBul)

3000       Table of MARES Reportable Equipment

Technical Manuals (TMs)

8B552B-    Operator’s Manual for Multiplexers/Demultiplexers TD-1389(P)(V)1/G (NSN
10/1A      5895-01-188-8820) (EIC: L2R) TD-1389(P)(V)2/G (5895-01-186-3235) (EIC:
           L2N)

07748B-    Operational and Organizational Maintenance Instruction for the AN/PRC-
12/1       104B(V)1, (V)4 Radio Set

07749A/    Operator’s and Organizational Maintenance Instruction Amplifier-Converter AM

07743A-12/2 6879/URC

07508A-14  Instruction Manual Antenna, AS-2259/GR (FSN 5895-106-6130) and Adapter,
           Antenna to Antenna Base MX-9313/GR (FSN 5985-172-6518)

08347A-10/1 Operator’s Manual for Satellite Communications Terminals, AN/TSC-85B(V)1
                  (NSN 5895-01-284-8305) and AN/TSC-85B(V)2 (5895-01-248-8308)


---

P-6 ___________________________________________________________________________________________ MCWP 6-22

08347B-    Operator’s and Organizational Maintenance Manual for Satellite Communica-
12/1-1     tions Terminals AN/TSC-85B(V)1 (NSN 5895-01-284-8305) and AN/TSC-
           85B(V)2 (5895-01-284-8308) Operation and Operator Maintenance

08347B-    Operator’s and Organizational Maintenance Manual for Satellite Communica-
12/1-2     tions Terminal AN/TSC-85B(V)1 (NSN 5895-01-284-8305) (EIC: L3F) and AN/
           TSC-85B(V)2 (5895-01-284-8308) (EIC: N/A)

08348A-    Operator’s Manual for Satellite Communications Terminals AN/TSC-93B(V)1
10/1       (NSN 5895-01-284-8306) and AN/TSC-93B(V)2 (5895-01-284-8307)

08348B-    Operator’s and Organizational Maintenance Manual for Satellite Communica-
12/1-1     tions Terminals AN/TSC-93B(V)1 (NSN 5895-01-284-8305) (EIC: L3E) and
           AN/TSC-93B(V)2 (5895-01-284-8307) (EIC: N/A)

08439A-    Operator and Organizational Maintenance Switchboard, Telephone, Automatic,
12/2-1     SB-3865(P)/TCC

08440A-    Central Office Telephone, Automatic, AN/TTC-42(V)
12/2-1

08467A-    Operator’s Manual for Multiplexer, Digital, TD-1337(V)1/G, (NSN 7025-01-
10/1       112-6311), TD-1337(V)2/G (7025-01-112-6310), TD-1337(V)3/G (7025-01-
           112-6312), and TD-1337(V)4/G (7025-01-127-7020)

08658A-    Combined Operation and Maintenance Instructions Organizational and Interme-
14/1       diate Radio Terminal Set AN/TRC-170(V)3 Part Number 951100-5 (NSN 5820-
           01-148-3976)

08761A-    Operator’s and Unit Maintenance Manual for Digital Data Modem MD-1026(P)/
12/1       G (NSN 5820-01-145-4945)

09280A-    Microwave Antenna Group OE-468
14&P/1

09543A-14 Operator and Troubleshooting Checklist for the Radio Terminal Set AN/MRC-
                  142

09589A-    Communications Central, AN/TSC-120
14&P/1

2000-15/2B Principal Technical Characteristics of U.S. Marine Corps Communication-Elec-
                  tronic Equipment

4700-15/1 Ground Equipment Record Procedures

5805-12/1  Operator’s and Organizational Maintenance Manual for Multiplexer, TD-
           1235(P)/TTC (NSN 5820-01-145-2460)


---

Communications and Information Systems _________________________________________________________ P-7

5805-12/2  Operator’s and Unit Maintenance Manual for Multiplexer, TD-1236/G (NSN
           5820-01-145-2461)
10149A-
13&P/1-1   Tactical Combat Operations (TCO) Technical Manual (NSN 5895-01-392-0294)

Miscellaneous Publications

Joint Manual of Regulations and Procedures for Federal Radio Frequency Management
Manual for Regulations and Procedures for Federal Radio Frequency Management (also referred
to as the NTIA Manual or Redbook) (http://www.ntia.doc.gov/osmhome/redbook/redbook.html)
DISA Contingency Plan 10-95
Computer Buyer’s Guide (http://www.marcorsyscom.usmc.mil)
Ship’s Loading and Characteristics Pamphlet

           (reverse blank)


--- 