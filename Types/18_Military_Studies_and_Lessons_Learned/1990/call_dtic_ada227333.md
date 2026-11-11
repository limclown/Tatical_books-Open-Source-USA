# call_dtic_ada227333  RULE-BASED EXPERT SYSTEMS  fTI F/ Lt COPy
           IN THE COMMAND ESTIMATE:
         AN OPERATIONAL PERSPECTIVE

         A thesis presented to the Faculty of the U.S. Army
              Command and General Staff College in partial
                    fulfillment of the requirements for the
                                                   degree

                        MASTER OF MILITARY ART AND SCIENCE

N

                                                        by

                              TIMOTHY R. PUCKETT, MAJ, USA
         B.S., East Central Oklahoma State University, 1977

         Fort Leavenworth, Kansas      DTIC

                    10               SB D ELECTE
                                          OCT 12190

                                     S B

                                      4

         Approved for public release; distribution is unlimited.

9004622


---

                                   ..... . . . ....  ..........                                  I           orm ,4ppio~ed                                     "
                   REPORT DOCUMENTATION PAGE
                                                                                                             OMB No 017040188

~a'cfe P.N.f( epcr1-- bt..e, for th,% c! cIr of *e'o,"at~n %e~it n-.ted tc. a.0-je
                                                                      o eCf4  , w ' kic 19 1 e I-e lof 'e-r  r nt '.0rns  w  g it,11q data~gC
                                                     ehleun,t, e-n ! teC led oedeof . oermaon '
.l'TeO  . 4,9 .netaj l t,hI data edCI . J OI , D                                                 dotee ?ef or n~ ft~r bi dentIt~er.tC Of *I ttg, '*r -r o C1,

'or, O' f o'       on{.e. hnlvd.g  22 fc'- aw (d, thbwde mO. !O V 'C flQere   gaSpe e e, j Oc ' e fto ro -ft.or oW ha toC.f peOCCCS 21 S 'et!'v o

0.W H Y'S i        N204.ArlingVoAn.221024302 d o the OfftC"e Ma ;ereee Ard Budgt. Pa0PeOrk RT.cfon Pioe<f (0704-018e). yYPjhNton. DC 20503

A. AGENCY USE ONLY (Leave blank)                     2. REPORT DATE           3. REPORT          AND DATES COVERED                Ju
4.TITLE AND SUBTITLE
                                                         1 June 1990           Master            s Thesis, Aug 1989 to Jun                  1990

                                                                                                             S. FUNDING NUMBERS

Rule-Based Expert Systems in the Command Estimate: An
Operational Perspective

6. AUTHOR(S;                       Puckett

Major Timothy R.

7. PERFORMING ORGANIZATION NAME(S) AND ADDRESS(ES)                                                           8. PERFORMING ORGANIZATION

U.S. Army Command and General Staff College                                                                      REPORT NUMBER
Attn: ATZL-SWD-GD
 Fort Leavenworth, KS 66027-6900

9. SPONSORING"/MONITORING AGENCY NAME(S) AND ADDRESS(ES)                                                     10. SPONSORING/MONITORING
                                                                                                                  AGENCY REPORT NUMBER

11. SUPPLEMENTARY NOTES

12a. DISTRIBUTION /AVAILABILITY STATEMENT                                                                    12b. DISTRIBUTION CODE

 Approved for public release; distribution is unlimited.                                                                         A

13. ABSTRACT (Maximum 200words)

This study is an analysis of how the branch of artificial intelligence known as rule-

based expert systems can be used to assist the performance of the command estimate as
prescribed in Command and General Staff College Student Text 100-9, The Command

Estimate. Current command and control systems are analyzed to determine why battle-
field information management is not successful. Trends in civilian decision aids for

corporate executives are introduced and contrasted with military requirements. The

capabilities of rule-based systems are discussed and a base line for their use in the

command estimate is introduced. Observations of the command estimate made by the

Center for Army Lessons Learned (CALL) and the Army Research Institute for the

Behavioral and Social Sciences (ARI) are analyzed to determine areas of the command
estimate that can benefit from assistance with rule-based systems. A detailed exam-

ination of the flow of information through the command estimate process is conducted

using techniques of systems analysis. Additionally, the Intelligence Preparation of

the Battlefield (IPB) is analyzed using the same methodology. This study of the

information flows and the types of information managed by each process indicates

areas that can be cnhanced with assistance by rule-based systems.

14. SUBJECT TERMS                                                                                            15. NUMBER OF PAGES

                      Artificial Intelligence, Rule-Based Expert Systems,                                                    221

Automated Command and Control, Command Estimate, Commander's

Intent, Decision Aids, Staff Support Aids, Battlefield Information

17. SECURITY CLASSIFICATION 18. SECURITY CLASSIFICATION 19. SECURITY CLASSIFICATION 20. LIMITATION OF ABSTRACT

        OF REPORT                                    OF THIS PAGE             OF ABSTRACT

        Unclassified                                 Unclassified             Unclassified                                   UL

NSN 7540-01-280-5500                                                                                         Standard Form 298 (Rev         2 89)
                                                                                                             Cee.,0d by ANSI Sfd ?39 8
                                                                                                             298-102


---

                        GENERAL INSTRUCTIONS FOR COMPLETING SF 298

The Report Documentation Page (RDP) is used in announcing and cataloging reports. It is important
that this information be consistent with the rest of the report, particularly the cover and title page.
Instructions for filling in each block of the form follow. It is important to stay within the lines to meet
optical scanning requirements.

Glock 1. Agency Use Only (Leave blank.                Block 12a. Distribution/Availability Statement.
                                                      Denotes public availability or limitations. Cite any
Block 2.. Report Date. Full publication date          availability to the public. Enter additional
including day, month, and year, if available (e g. 1  limitations or special markings in all capitals (e.g.
Jan 88). Must cite at least the year.                 NOFORN, REL, ITAR).

Block 3. Type of Report and Dates Covered.            DOD           See DoDD 5230.24, 'Distribution
                                                                    S ee o 53n 4,nitr ti
State whether report is interim, final, etc. If                     Statmentso c

applicable,  enter inclusive report dates (e.g.  1.08).Documents.'  See authorities.
                   Jun  7-30Jun                                     See Handbook NHB 2200.2.
                                                                    Leave blank.
Jun 87 -30 Jun 88).                                   DOE
                                                                     Distribution Code.
Block 4. Title and Subtitle. A title is taken from       NASA -
the part of the report that provides the most            NTIS -     Leave blank.
meaningful and complete information. When a                         Enter DOE distribution categories
report is prepared in more than one volume,           Block 12b.    from the Standard Distribution for
repeat the primary title, add volume number, and                    Unclassified Scientific and Technical
include subtitle for the specific volume. On             DOD        Reports.
classified documents enter the title classification      DOE -      Leave blank.
in parentheses.                                                     Leave blank.

Block 5. Funding Numbers. To include contract         NASA -
and grant numbers; may include program                NTIS -
element number(s), project number(s), task
number(s), and work unit number(s). Use the

following labels:

C - Contract            PR - Project                  Block13. Abstract. Include a brief (Maximum
G - Grant               TA - Task                     200 words) factual summary of the most
PE - Program            WU - Work Unit                significant information contained in the report.

          Element                  Accession No.

Block 6. Author(s). Name(s) of person(s)              Block 14. Subiect Terms. Keywords or phrases
respo ,iiblefor writing the report, performing        identifying major subjects it- the report.
the research, or credited with the content of the
report. If editor or compiler, this should follow     Block 15. Number of Pages. Enter the total
the name(s).                                          number of pages.
                                                      Block 16. Price Code. Enter appropriate price
Block 7. Performing Organization Name(s) and
Address(es). Self-explanatory.

Block 8. Performing Organization Report               code (NTIS only).
Number. Enter the unique alphanumeric report
number(s) assigned by the organization                Blocks 17. - 19. Security Classifications. Self-
performing the report.                                explanatory. Enter U.S. Security Classification in

Block 9. Sponsoring/Monitoring Agency Name(s)         accordance with U.S. Security Regulations (i.e.,
and Address(es). Self-explanatory.
                                                      UNCLASSIFIED). If form contains classified
Block 10. Sponsoring/Monitoring Agency
Report Number. (If known)                             information, stamp classification on the top and
                                                      bottom of the page.

Block 11. Supplementary Notes. Enter                  Block 20. Limitation of Abstract. This block must
information not included elsewhere such as:           be completed to assign a limitation to the
Prepared in cooperation with...; Trans. of...; To be  abstract. Enter either UL (unlimited) or SAR (same
published in.... When a report is revised, include    as report). An entry in this block is necessary if
a statement whether the new report supersedes         the abstract is to be limited. If blank, the abstract
or supplements the older report.                      is assumed to be unlimited.

                                                                    Standard Form 298 Back (Rev 2-89)


---

                                               RULE-BASED EXPERT SYSTEMS
                                               IN THE COMMAND ESTIMATE:
                                              AN OPERATIONAL PERSPECTIVE

                      A thesis presented to the Faculty of the U.S. Army
                            Command and General Staff College in partial
                                  fulfillment of the requirements for the
                                                                 degree
                                      MASTER OF MILITARY ART AND SCIENCE

                                                                     by
                                           TIMOTHY R. PUCKETT, MAJ, USA
                      B.S. , East Central Oklahoma State University, 1977

                                                 Fort Leavenworth, Kansas
                                                                    1990

                  Approved for public release; distribution is unlimited.

9004622


---

                            MASTER OF MILITARY ART AND SCIENCE
                                         THESIS APPROVAL PAGE

                 Name of candidate: Major Timothy R. Puckett

                 Title of thesis: Rule-based Expert Systems in the
Command Estimate: An Operational Perspective

Approved by:

                  -     n         Thesis Committee Chairman

Lieutenant        ,ltel Ronald D. Pfeiffer, M.S.

                                                               Member, Graduate Faculty
ieitenait Colonel John A. Strand III, M.B.A., M.S.

  !

              ..     /  '      , Member, Consulting Faulty

Coronel James L. Morrison, PE.D.

Accepted this 1st day of June 1990 by:

                               ,        .DirectoGrr,aduate Degree

Phili J. Brookes, Ph.D.                 Program

The opinions and conclusions expressed herein are those of
the student author and do not necessarily represent the views
of the U.S. Army Command and General Staff College or any
other governmental agency. (References to this study should
include the foregoing statement.)

                           ii


---

                ABSTRACT

RULE-BASED EXPERT SYSTEMS IN THE COMMAND ESTIMATE: AN
         OPERATIONAL PERSPECTIVE, by Major Timothy R. Puckett,
         USA, 221 pages.

This study is an anlaysis of how the branch of artificial
intelligence known as rule-based expert systems can be
used to assist in the performance of the command estimate
as prescribed in Command and General Staff College Student
Text 100-9, The Command Estimate.

Current command and control systems are analyzed to
determine why battlefield information management is not
successful. Trends in civilian decision aids for
corporate executives are introduced and contrasted with
military requirements. The capabilities of rule-based
systems are discussed and a base line for their use in the
command estimate is introduced.

Observations of the command estimate made by the Center

for Army Lessons Learned (CALL) and the Army Research
Institute for the Behavioral and Social Sciences (ARI) are
analyzed to determine areas of the command estimate that
can benefit from assistance with rule-based systems.

A detailed examination of the flow of information through

the command estimate process is conducted using techniques

of systems analysis. Additionally, the Intelligence

Preparation of the Battlefield (IPB) is analyzed using the

same methodology. This study of the information flows and

the types of information managed by each process indicates

areas that can be enhanced with assistance by rule-based

systems.     .

The study concludes that rule-based systems can be used

to automate the IPB process and significantly contribute

to portions of the command estimate. The role these

systems can play is best described as a staff aid.

Functions would include expression and dissemination of

the commander's intent, creation of planning time lines

and synchronization matrices, standardization of mission

statements, performance of the IPB, assistance and              Por

maintenance of task organizations, tracking of critical

events, and creation and dissemination of warning orders.

                                                                            Ed

                                                    Ju- _ I i it Oi

                                                    By
                                                    Dintributio/

                             iii  Diit(~L1 A':iTlablity Codassc •
                                             ;Avail and/or
_ _ _     _     _


---

I                          TABL 8 E OF

                           CO NT ENT S

   Title Page ..........             ......................        i
   Approval Page .........
   Abstract .........                .................... ii

                                 ......................        iii

   CHAPTER 1. INTRODUCTION

                                                               Page

   Introduction ...........             .....................      1

   Background ...........            ......................        5

   Purpose of the Thesis ........           ................       7

   Assumptions ...........              .....................      7

   Definition of Terms ........         .................          8

   Limitations ........              .....................     10

   Delimitations ........            ....................      10

   Significance of the Study .....      ..............         11

   Thesis Outline ........           ....................      11

   Chapter 1 End Notes ......        .................         14

   CHAPTER 2. REVIEW OF LITERATURE

   Review of Literature ......       .................         15

   Rule-based Expert Systems .....      ..............         16

   The Command Estimate ......       .................         21

   Battlefield Information Management ....       .......... 24

   Executive Information Systems: Civilian

   Information Management Success ....      ............       27

   Performance Enhancements ...      ............... 31

   Rule-based Expert System War Gaming ...       .........     32

   Conclusion ..........             ...................... 34

   Chapter 2 End Notes ........         ................. 35

   CHAPTER 3. RESEARCH METHODOLOGY

   Research Methodology ......       .................         39

   Information Sources ........         ................. 39

   Research Tools ................................ 39

   Selection of Subject Matter Experts ...       .........     42

   Systems Analysis of the Command Estimate ...  .......       43

   Chapter 3 End Notes ......        .................         48

                                 iv


---

CHAPTER 4. IS THERE A NEED FOR RULE BASED EXPERT SYSTEMS
                                   IN COMMAND AND CONTROL?

Is There a Need for Rule Based Expert Systems

in Command and Control ......       ................           49

Why Current Automated C2 Systems Do Not Perform

Battlefield Information Management ....    .......... 50

Automation in Soviet Troop Control ....    .......... 52

Battlefield 2000 +. ......      . . . ..   . ................  53

ATCCS: An Information Firehose ...        ........... 54

The Expert System Tool Box .....          ..............       56

Summary ..........................                             57

Chapter 4 End Notes ......          .................          59

CHAPTER 5. OBSERVATIONS OF THE COMMAND ESTIMATE

Observations of the Command Estimate ....      ......... 61

The Successful Command Estimate .....      ........... 62

Facts and Assumptions ......        ................           63

Mission Analysis .........          ................... 63

Commander's Guidance ......         .................          66

Develop Courses of Action .....           ..............       68

Analyze Courses of Action .....           ..............       72

OPORD/FRAGO Production ......       ................           73

Abbreviated Command Estimate .....        .............        74

Summary ..........              .......................        75

Chapter 5 End Notes ........              ................. 78

CHAPTER 8. ANALYTICAL DECOMPOSITION OF TEX
                           COMMAND ESTIMATE

Analytical Decomposition of the Command Estimate . .           . 80
                                                                  81
Mission ..........             .......................            87
                                                                  92
Facts and Assumptions ......        ................             9g

Mission Analysis ........           ...................        102
                                                                108
Commander's Guidance ........             .................     113
                                                                115
Develop Courses of Action ....      .............               118
                                                                118
COA Analysis ........          ....................             125

Decision ..........            ......................

OPORD/FRAGO Preparation .....       ..............

Commander and Staff Input ....      .............

Summary .........           ......................

Chapter 6 End Notes ......          ................

CHAPTER 7. CONCLUSIONS AND RECOWMENDATIONS

Conclusions and Recommendations .. ..........                  127

Conclusions ........           ....................            128

Recommendations .......         ..................             133

Priority of Rule-Based System Implementation ....              136

Commander's Intent ......       .................              136

Synchronization .......         ..................             137

Mission Statements ......       .................              138

                            v


---

G2/S2 IPB . . . . . . . . . . . . . . . . . . . . . 138
Task Organization...................139
Critical Events....................140
Warning Orders.....................140
ATCCS and Rule-Based Systems..............140
Chapter 7 End Notes..................142

A P P 1 N D I aC30

A. Analytical Decomposition of the Intelligence

Preparation of the Battlefield CIPB) ........     143

B. Synopsis of Interviews...............174

C. Glossary.........................196

D. Bibliography....................207

LaXS T OF IFPIC3URF ES0

1. The Command Estimate.................4

2. Data Flow Diagram..................45

3. The Command Estimate................82

4. Mission DFD.....................84

5. Facts and Assumptions DFD..............88

6. Mission Analysis DFD................93

7. Mission Analysis DFD (continued)...........97

8. Commander's Guidance DFD..............100

9. Develop Courses of Action DFD ............     104

10. Analyze COA DFD..................110

11. Decision DFD..................114

12. OPORD/FRAGO DFD..................116

13. The IPB Process....................145

14. IPB Battlefield Area Evaluation DFD ........  147

15. Terrain Analysis DFD...............151

16. Terrain Analysis DFD (continued).........154

17. Weather Analysis DFD...............158

18. Threat Evaluation DFD...............161

19. Threat Integration DFD..............165

]L.ISTrr aOF TA M 1.,0

1. Chapter 5 Summary..................77
2. DFD Summary....................121
3. Conclusion Summary.................135
4. IPB Summary....................169

vi


---

                                                 CHAPTER 1

                                             INTRODUCTION

               The estimate of the situation has been the bedrock
for military decision making in the United States Army
since the turn of the century.' When used to assist the
commander and staff as they plan and conduct combat
operations it is referred to as the command estimate.
This cyclic process has withstood the tests of time and
combat. It is a highly refined procedure. Until now, the
command estimate has been omitted from the technology
envelope of the automation revolution that has swept the
modern battlefield. However, the maturation of the branch
of computer science known as artificial intelligence (AI)
raises the question of whether the command estimate
process can be automated in future battlefield command and
control (C2) systems.

               Although the command estimate appears to be
rigidly structured, it is not a simple mechanical process
and is dependent upon continuous input of information.
For the process to be successful, it must rely on the
constant interplay of the commander's experience,


---

knowledge, and evaluation of the information continuously
provided by the staff. In effect, the command estimate is
as much military art as it is military science.

               The current generations of automated command and
control systems are complex in physical architecture but
do little more than simple processing of tabulated
information. The amount of information that these systems
can sort, sift, filter, merge, collate, or rank has
surpassed the human management threshold and may inundate
the commander with the sheer mass and volume of data
produced. Indeed, the tremendous amount of unprocessed
data these systems present to the commander may be a
hindrance to making smart battlefield decisions.

               The civilian sector is beginning to answer this
dilemma by the introduction of artificial intelligence
within the framework of control systems. 2 A specific area
of promise is that of rule-based expert systems. Based on
a structure of rules defined by human "experts", these
systems can process mundane and trivial information and
appear to make decisions. These decisions are nothing
more than the adherence to a set of human responses
predefined for specific situations. This frees the human-
decision maker from distraction and allows more effort to
be concentrated on the task at hand. These redefined

                                                      2


---

business-decision and control systems do not simply
process data; the., manage and leverage the information
into a tangible asset.

               The use of rule-based expert systems in
corresponding civilian decision-support systems indicates
their possible use in the military decision process.
However, due to the dynamics of combat operations and the
tenuous nature of much of the information involved, the
use of such AI techniques is still uncertain.

               The command estimate is the definitive example of
the military decision cycle. Figure 1 represents this
process as depicted in U.S. Army Command and General Staff
College Student Tixt 100-9. As shown, the command
estimate appears to be highly procedural with well
delineated steps, start points, and end points.3 However,
its use depends -n many human factors including a keen
knowledge of tactics and experience levels. Additionally,
the fluid and constantly changing reality that represents
the modern battlefield complicates the proposition of
artificial intelligence-based C2 systems.

               Due to the complexity and dynamics of military
decision-making, it is not feasible to simply adapt an
existing civilian rule-based expert system to fi tle
command estimate model. A significant problem is that
such a system designed to work in one well-defined
situation may be faced with considerably different

                                                      :3


---

     THE COMMAND ESTIMATE

IMission] Received from higher HO or deduced by CDR's feel for the battle

F acts and                                 1.Onhand data focused by miasion
Assumptions                                2.COR's initial Input

                                           3.Upate Ifo       frpann

CDRUvdfoerdrprleaentnirinng

missionAPreparspsynhsibeues of fondtioCaRfsoetchne      mso

OPORD~arin                                            OrRAdWanigOre

                                     Fiur                                  B1.

      5                                    ssedwih isin nayss4n


---

environments during combat operation. Additionally, no
two units in the Army operate in exactly the same way.
This results in the condition that a rule-based expert
system built on a single decision model may not be
applicable for every unit unless it can be tailored for
the particular unit based on the way it operates as
defined by resident experts (i.e., commanders and their
staffs). A third feature is that under the pressures of
combat, the command estimate process may assume an
entirely different shape than as taught in the classroom
environment. These factors indicate that there are
considerable challenges in the implementation of an AI-
based C2 system.

Background

The Maneuver Control System (MCS) is the Army's

first attempt to emplace a comprehensive automated C2

information processing system across the tactical

spectrum. Although it is an impressive effort, the

strength of MCS is found in its communications ability

rather than in the computer system.  MCS does little more
than simple data base manipulation.  This provides limited

utility until the information is further interpreted and

refined by the commander and staffs. Most importantly,

because of the data processing power automation has given

5


---

MCS, it is capable of overloading the commander and staff
with information. Due to the nature of military
operations, the occurrences of this overload will be at
the times when the most critical decisions have to be
made.

               Basic limitations in the sophistication of the
software constrain the way MCS can present information for
interpretation. The human process of filtering this
information for application in the decision cycle adds a
significant amount of time. By the time this data is
interpreted, it is either too old or has become overcome
by events and is of no use in the battlefield commander's
decision cycle. It is obvious this infusion of dated,
incomplete, and inaccurate information has the potential
for disastrous or catastrophic implications in regard to
battlefield decisions.

                In its present form, MCS does not provide the
commander with any decision-aids. MCS does have the
potential to provide an embryonic platform for efforts to
implement artificial intelligence aids within military
decision making and command and control. The focus for
any effort in this area will be provided by the Combined
Arms Center Future Battle Lab, Fort Leavenworth, Kansas.

               The key to success for any future C2 systems is
high fidelity irplementation of the command estimate. A
concentrated effort is currently focused on the use of AI

                                                      6


---

in the development of the future generation of automated
C2 systems. This effort includes the possible use of AI
in the command estimate process. However, a preliminary
review of literature indicates that this research is being
driven by computer scientists without apparent regard to
the operational needs of Army commanders and their staffs.
This may be attributed to the confusion of where military
science ends and military art begins.

                                     Purpose of the Thesis
               The purpose of this thesis is to establish a
militarily operational viewpoint of using rule-based
expert systems in an automated command estimate.

                                                    Assumptions
               1. Due to the relative recent emergence of
artificial intelligence from the academic environment to
solve real world problems, proposals for AI-based
implementation of the command estimate will have
originated from other than an Army source.
               2. There exists a need to evaluate the
implementation of rule-based expert systems in the command
estimate from a purely military perspective.
               3. There are qualified experts to serve as the
subject matter experts who can quantify the necessary

                                                      7


---

knowledge base to implement rule-based expert systems in
portions of the command estimate.

               4. Software techniques and capabilities for the
development of Al-based C2 systems exist and are available
within present technology.

                5. The most current literature will be found in
periodicals. The focus of this information will not be
restricted to military applications and a degree of
inference will be taken to equate the civilian sector
experience with military requirements.

                                       Definition of Terms
                Artificial Intelligence: A branch of computer
science in which computer-based solutions to complex
problems are derived through the application of processes
that are analogous to human reasoning. 4
                ATCCS: Army Tactical Command and Control
System. The command and control system utilized by all
tactical echelons up through corps. ATCCS includes the
organization, facilities, and procedures through which the
commander plans, directs, controls, and coordinates
operations.'
                Command and control (C2): The process through
which the activities of military forces are directed,
coordinated, and controlled to accomplish the mission.
This process encompasses the personnel, equipment,

                                                       8


---

communications, facilities, and procedures necessary to
gather and analyze information, to plan tasks, to issue
instructions, and to supervise the execution of
operations.6

               Command and control system: The totality of
automation, communications, and procedures used to gather
information, process the information, develop operational
plans, generate military orders, and convey these orders
to subordinate elements to execute a mission.

               Command estimate: The process used by military
commanders and their staff that focuses on essential
facts and necessary assumptions to make decisions that
will lead to success on the battlefield.'

               Estimate of the situation: In the military decision
making process, the collection and analysis of relevant
information for developing, within the time limits and
available information, the most effective solution to a
problem.0

               Expert Systems: A sub-field of artificial
intelligence in which the computer programs follow rules
established by a human expert in a specific problem
domain.'

                Maneuver control system (MCS) : A command and
control system that focuses on the tactical execution of

                                                      9


---

war. Currently, MCS is in the form of an automated system
based on a collection of data bases and attendant
communications facilities to disseminate information.

               Rule-based: A technique of AI in which a decision
is predicated on satisfying an established set of rules
governing any problem solution.

               Subject Matter Expert (SME) : A human expert in a
particular field or problem domain from which the
procedures for solving a particular problem are taken.

                                               Limitations
                1. The scope of this thesis will not allow a
detailed history or explanation of artificial intelligence
or expert systems.
                2. The use of the term artificial intelligence
within this thesis is used interchangeably with the term,
rule-based expert systems. I recognize that artificial
intelligence is a broad and ever expanding domain.
Furthermore, expert systems is a growing subset of
artificial intelligence with many variations and nuances
in addition to rule-based systems.

                                              Delimitations
                1. This study will not produce computer language
code or any rule-based expert system models.
                2. Classified subjects will not be addressed.

                                                      10


---

               3. The rule-based expert systems recommended
within this thesis are meant to be aids to the commander's
staff officers. These systems will not replace the
function of any soldiers but will serve as staff-aids to
improve the information flow through the staff to provide
the commander with the best information upon which to make
decisions.

               4. Unless otherwise stated, whenever the
masculine gender is used, both men and women are included.

                                 Significance of the Study
               This thesis will provide an Army perspective of
the operational needs of rule-based expert systems within
the command estimate. It will provide scope and direction
of future Army automated command and control systems that
incorporate artificial intelligence in the military
decision process.

                                           Thesis Outline
               Chapter 2: Review of Literature. The branch of
artificial intelligence known as rule-based expert systems
is described in respect to military applications. The
concept of battlefield information management is then
examined and explained to support the need of managing and

                                                     11


---

controlling information in a tactical environment.
Finally, the methods used in the civilian business
community to control important information is introduced.

               Chapter 3: Research Methodology. The use of
hypertext, electronic mail, personal and telephonic
interviews with subject matter experts and a literature
review served as the primary research vehicles for this
thesis. The techniques used to implement these methods
are analyzed and discussed in this chapter.

              Chapter 4: The Need for Rule-Based Expert Systems
in Command and Control. This chapter establishes a
baseline argument for the need of automation in modern
command and control. In addition, this chapter addresses
the advantages of applying rule-based expert systems to
portions of the command estimate.

               Chapter 5: Observations of the Command Estimate.
This chapter analyzes formal obs4.vations made into the
performance of the command estimate by the Center for Army
Lessons Learned and the Army Research Institute for the
Behavioral and Social Sciences. Additionally, it
discusses the command estimate as viewed from several
functional area experts within the Center for Army
Tactics. In conjunction with the examination of these
discussions, recommendations are made to incorporate rule-
based systems to assist the implementation of the command
estimate.

                                                      12


---

               Chapter 6: Analytical Decomposition of the
Command Estimate. This chapter examines the command
estimate process from a systems analysis point of view.
It discusses operational Army requirements combined with
an analysis of those portions of the process that can best
be performed by an AI-based system and those that are best
done with the current manual technology.

               Chapter 7: Conclusion and Recommendations. This
chapter focuses on the parts of the command estimate that
could best be assisted by the use of rule-based expert
systems.

               Appendix A: Functional Decomposition of the
Intelligence Preparation of the Battlefield (IPB). This
annex examines the IPB from a systems analysis point of
view in the same manner the command estimate was analyzed
in Chapter 6. It discusses operational Army requirements
combined with an analysis of those portions of the process
that can best be performed by an AI-based system and those
that are best done with the current manual technology.

              Appendix B: Interview and E-Mail Summary.
Interviews with subject matter experts conducted via
electronic mail, personal sessions and telephone calls are
summarized in this section.

                Appendix C: Glossary. Technical and domain-
specific vocabulary used within this study are defined in
this chapter.

                                                      13


---

                                       CHAPTER 1 END NOTES
          'U.S. Army, Command and General Staff College,
Student Text 100-9, The Command Estimate (1989): 1-2.
          'Bob Brown, "Future of Network Management Lies in
Expert Systems, Network World 37 (September 18, 1989): 11.
          3ST 100-9 (1989): 1-3.
          4 David W. Rolston, Principles of Artificial
Intelligence and Expert Systems Development (1988): 15.
          OUS Army, FM 100-15, CORPS OPERATIONS (APPROVED
FINAL DRAFT): 4-10.
          'U.S. Army, FM 101-5-1, Operational Terms and Symbols
(1985): 1-16.
          7ST 100-9, (1989): 1-2.
          IFM 101-5, (1984): 5-2.
          *Paul E. Lehner, Artificial Intelligence and
National Defense (1989): 15.

                                                      14


---

                                                   CHAPTER 2

                                           LITERATURE REVIEW

               The use of artificial intelligence, and more
specifically, rule-based expert systems, in military
command and control systems is not a novel idea. The
computer hardware and software that could make such a
system become reality are available with present
technology. However, there are no deployable or
successful implementations of rule-based expert systems
within any existing or near-term command and control
systems.

               The command estimate is the essence of military
command and control. Determining if rule-based expert
systems can be successfully used within the command
estimate will set the stage for the future development of
military command and control systems.

               The purpose of this chapter is to describe the
current state of militarily significant rule-based expert
systems, define the requirements for battlefield
information management, introduce the command estimate,
compare civilian executive information systems with

                                                     15


---

military requirements, and examine some areas of the
command estimate and staff operations that have been
identified for possible enhancement.

                                 RULE-BASED EXPERT SYSTEMS
               The military application of computer systems that
aid in decision making is not a new development. Many
conventional systems such as TACFIRE and TACCS have
proled effective for solving mathematical, statistical,
or routine data processing problems. However, the
challenges associated with assisting the commander in the
process of command and control in combat do not fit into
these categories. The solution to such problems are
still critically dependent on skill in identifying and
relating trends, weighing evidence, developing courses
of action, evaluating alternatives, predicting outcomes,
and making complex decisions. This can be summed up as
the human ability to bring a wealth of diverse knowledge
and years of experience to bear on the problem at hand.
A computer system to perform in such a manner is called
an expert system.'
                Expert systems are computer programs that
duplicate, to some degree, the kind of results achieved
by human experts. These systems are able to solve some
types of problems, to predict situation outcomes, and to
give advice within narrow areas of consideration. One
theory defines expertise, or the skill shown by experts.

                                                      16


---

as the result of the accumulation of a set of rules for

interpreting facts to reach a conclusion. The general

idea of rule-based expert systems is that if these rules

could be collected and put into a computer, then some of

the skill of the expert could be shown by that computer.-

A detailed examinatior. of specialized aspects of

artificial intelligence and rule-based systems can be

found in Encyclopedia of Computer Science and

Engineering. 3 This work is a tremendous vehicle for

generzl background information but lacks a scope into

military applications. Several other books provide a

point of departure for the understanding of rule-based

systems applicable to the direction of this thesis.    They
include Fundamentals of Human-Computer Interaction 4

which details expert system structure and knowledge

engineering, Winston's Artificial Intelligence,' and

Principles of Artificial Intelligence and Expert Systems

Development.' These works excel at the explanation of

problem solving concepts and knowledge engineering.

However, none of these books provides insight into how

rule-based expert systems can assist in military command

and control.

A general source of information for rule-based

expert systems within the narrow band of military command

and control applications is Lehner's Artificial

Intelligence and National Defense.' It provides a

concise source for the explanation of AI as a science and

              17


---

a crosswalk of several current efforts within the
Department of Defense. While it contains an overview of
rule-based expert systems in several command and control
initiatives, it does not examine their role in the
command estimate.

                It would be prudent to question why there are no
major expert systems currently augmenting military
command and control systems. The answer is not simple.

                Although expert systems have been around since
the 1950s, it has only been recently that they could be
operated without reliance on large mainframe computers.
Due to this mainframe dependency, they have been
restricted to a very narrow scope in application.
Additionally, they have required constant programmer
maintenance to build and maintain knowledge bases.* The
interval since 1984 has seen a tremendous downsizing of
the expert systems to more transportable hardware, an
exponential growth in software capabilities, and an
emergence of applications in the civilian sector that
promote adaptability towards military uses.'

                While rule-based expert systems show significant
promise in military applications, there are several
considerations that limit the scope of their use:

                 1. There are finite limits to what these systems
can currently do. The optimum size for a rule base is
between ten and 10,000 rules. 10

                                                      18


---

               2. Th+ y Ltridr Lo be idiot savants, capable of
doing some limited things rather well while not being
capable of operations near the fringes of their knowledge
bases."

               3. Basic rule-based systems do not learn. While
the capability of some systems to learn has been
demonstrated, this process is not yet at a level of
sophistication that would justify a military
application. 12

               4. They do not know how and when to break their
own rules. 1 3

                5. They lack the ability of visual or pattern
recognition to a militarily significant level. Visual
recognition is a primary method used by military
commanders and staffs to distill information. 1"

               6. Rule maintenance is expensive and time
consuming."

               7. These systems contain no common sense and can
give absurd results." There is no reality checking
mechanism other than human interpretation of the results.

               8. Human knowledge is often deficient in some
areas for even the best or most successful experts. 17

               9. Special and perishable skills rapidly
deteriorate as the reliance on and use of the expert
system increases. This results in the organization
becoming critically dependent on machines."1

                                                     19


---

               Once the limitations are understood, the
advantages of expert systems can be exploited. Areas in
which they can excel and have practicality in military
applications include:

                1. They can allow soldiers of varying skill
levels to approximate an expert in performing a task
within the problem domain of the system."

               2. They are not subject to fatigue, stress,
fear, exhaustion, or emotions. Hence, they can reduce
personnel requirements for continuous operations. 2 0

               3. An important role an expert system can
perform is that of a consultant. 2 1 It could not have a
hidden agenda and, therefore, could be relied on for
providing information and detail solely based on logic.

               4. An expert system can be an advanced checklist
mechanism to query the human commander to make sure
doctrinal tenets are satisfied.

               5. Over a period of time, an expert system can
accumulate input from a variety of experts, thus refining
its internal expertise and providing system users with an
increase in capability. 22

               8. As experience is gained through use of a
system, it can provide a corporate memory and historical
summaries of past performance on which to measure current
operations.

               7. Due to the portability of automation
equipment, a rule-based expert system can serve as a

                                                     20


---

transportable equivalent to the Center for Army Lessons
Learned (CALL). This would facilitate the dissemination
and standardization of newly developed doctrine.

               8. In a distributed network, rule-based expert
systems can dramatically expand integration of
information from a wide variety of sources.23

                                         THE COMMAND ESTIMATE
               FM 101-5 explains how army staffs are organized
and operate to execute the military decision making
process.2 4 Army staff organizations and functions are
based on methods which have evolved over the last
century. The process taught to commanders and staffs in
arriving at military decisions is termed the command
estimate. The methodology for this process is formalized
and explained in ST 100-9.20 The command estimate is a
proven manual process. It is a logical and orderly
examination of all factors affecting the accomplishment
of the mission in order to reach a sound decision. In
reality, the command estimate is a continuing mental
process for the commander or staff officer who must
observe, evaluate, revise, decide, and observe again
throughout the duration of a tactical operation. The
command estimate is as thorough or as brief as time and
circumstances permit.20
               The command estimate is not a simple mechanical
process. Although it is depicted as a flow chart in ST
100-9 (Figure 1, page 4), there are no distinct starting

                                                     21


---

or stopping points. The components of it are not

independent. Many of the elements can occur or be in

progress at the same time.27
                 The command estimate is a continuous process.

Unless the current mission is changed, or until a new

mission is received, commanders and staff officers

continuously update and refine information in their

respective areas of responsibility. A change in the

current mission, the receipt of a new mission, or a

change of information provides new direction to this

process for that particular operation."
                 Formal scientific analysis of the command estimate

has been conducted by the Fort Leavenworth field office

of the Army Research Institute (ARI). The following are

ARI's areas of issue and concern in the execution of the
command estimate: 2'

1. Time constraints. There is not enough

available time to do the prescribed procedures of the

command estimate. Consequently, some of the steps are

omitted, conducted out of sequence, or performed

incorrectly.                           Human adopted strategies
                 2. Cognitive biases.

can be suboptimal due to the effects of group thinking

and consensus confirmation.

3. Information use. The commander and staff

fail to actively seek or disseminate information. This

                             22


---

is attributed to the threat of overload for incoming
information and the responsibilities associated with the
ownership of outgoing information.

                 4. Information uncertainty. Inherent in any
tactical situation is the large degree of uncertainty in
information.

                 5. Overconfidence of the commander and staff.
This leads to a misleading implementation of plans and
results in the lack of development of contingencies.

                 6. Lack of experience. With many commanders
and staffs, the possibility of an inadequate experiential
base to make sound tactical judgments exists.

                7. Management of the process. The overall group
decision-making process is poor. A fairly common
occurrence is that issues are resolved using the last
option discussed.

                8. Definition of insufficient options. When
multiple options are created, they are often simple
variations of a main theme. When there is variance, it
is normally the practice to generate something to 'throw
away' to give the appearance that more than one option
was considered.

               9. Limited scope of the command estimate. The
command estimate is often used for other kinds of
operations that don't lend themselves to resolution via
the military decision model.

                                                     23


---

               10. Decision analysis. The applicability of
the command estimate and its components are highly
situational dependent.

                11. Inappropriateness of the decision making
model. The continuous and cyclic nature of the command
estimate is not always the optimum method to
simultaneously generate and evaluate courses of action.

               This thesis will conduct an indepth analysis of
the command estimate and examine the adaptation of rule-
based expert systems as a means to assist commanders and
staffs in its execution.

                       BATTLEFIELD INFORMATION MANAGEMENT
               The commander and staff have unique and specific
information requirements for battlefield command and
control. Although information is not fully recognized as
a combat multiplier, if processed correctly and timely,
it can contribute to combat power. A method for managing
this information is to divide it into three major
functional areas of planning, directing, and executing. 30
               These three areas have seven tasks that the
command and control system must do:

                                                     PLAN
                1. See both friendly and enemy situations.
                2. Evaluate the mission.
               3. Develop the plan.

                                                     24


---

                                                   DIRECT
               4. Allocate resources.
               5. Coordinate the allocation, assignment, and
reallocation of resources.

                                                 EXECUTE
               6. Fight the battle.
               7. Sustain the forces.
               Although manual methods are used in performing
these tasks, they are rapidly losing their status as
the primary means of managing information. 3 1 Computers
are more accurate and faster than manual processes.
Automated command and control information systems have
been used to assist in planning, directing, and
executing military operations in various forms since the
1960s. Their utility and need are widely recognized as
being essential for military operations. There are three
primary conditions that justify the expense and effort
for implementing automated command and control systems to
regulate information handling: 3 2
                1. The commander's performance ability is
saturated under normal conditions because of information
overflow.
               2. The commander's performance is limited under
prolonged periods of stress conditions.
               3. Higher accuracies and better reliability of
data are needed to make better informed decisions.

                                                     25


---

               The positive effect of introducing a command and
control information system is that it can prevent or
reduce the burden imposed on commanders, freeing them
from routine tasks and allowing them to concentrate on
important information and making timely decisions. The
problem is that while automated systems do a credible job
of getting information to commanders and their staffs,
they do little to help sort, sift, filter, merge,
collate, or rank the information to assist the commander
to make informed decisions. While the raw speed and
power of automation is intoxicating, commanders can
readily become so immersed in details that they do not
have sufficient time to devote to the prosecution of the
battle. To fight and win in three separate and distinct
battles (close, deep, and rear), information must be
properly organized so that the commander is neither
flooded with detail or suffers from a lack of critical
information.

               Too little information makes the command estimate
completely ineffective. Too much information slows the
process down. Automated rule-based expert systems can be
used to intelligently process data and, therefore,
optimize the available time within the command estimate.

                                                     28


---

                           EXECUTIVE INFORMATION SYSTEMS:
                 CIVILIAN INFORMATION MANAGEMENT SUCCESS
               The civilian sector has turned to a class of
computer products called executive information systems
(EIS) to manage and leverage information in an attempt to
increase profits. Simply stated, an EIS is a computer-
based means by which information can be accessed,
created, packaged, and delivered for use on demand by
high-level, nontechnical executives. An EIS is a hands-
on tool that focuses, filters, and organizes an
executive's information, so that he or she can make more
effective use of it. By using information more
effectively and more strategically, a corporation can
ultimately increase profits.13 EIS applications are
designed for the non-computer-oriented executives who
have neither the time nor the inclination to be trained
in computer methods. This definition dovetails with
battlefield information management needs of commanders
and staffs.
               The goals of an EIS are also in line with those
needed in a commander's battlefield information system.34
In the following list of goals for an EIS, the words
 commander and staff* can be interchanged for *executive*
or *management team.*
                1. To reduce the amount of data bombarding the
executive.

                                                     27


---

               2. To increase the relevance, timeliness, and
usability of the information that does reach the executive.

               3. To focus a management team on critical
success factors.

               4. To facilitate information comprehension and
communication with others.

               5. To enhance executive follow-through.
                 To meet these goals, a commercial EIS product

Commander has the following modules:
                1. Status reporting via an electronic 'briefing

book.' By using this application, each executive can
receive a focused selection of reports and charts, which
reduces the amount of irrelevant information. Specific
tolerances can be designated that result in rapid
exception reporting. The information feeding these
status reports is constantly updated. 36

               2. E-Mail management. In this module,
information can be rapidly disseminated to specific
agencies or individuals within the organization.3

               3. Free-form data base queries. This feature
allows the executive to seek detailed informa*.ion if
required. Multiple levels of investigation are possible
that cannot be done using paper reports. Dynamic
relationships between data elements can be designated and
investigated through corporate data bases. It also gives
the ability to play 'what ifs" with current data sets. 2 7

                                                     28


---

               4. Reminder capabilities for tracking and
follow-through. This is an electronic suspense and
calendar system that can assist in complex
synchronization of scheduled events. Project management
is also a facet of this feature. Critical dates and
events can be managed with this system.3 0

               5. Delivery of current news of the world
outside. Information that is critical to the decision
maker can be accessed as it comes 'on line* via news or
stock market reporting services. 3 0

               The spread of EIS is growing within civilian
industry. IBM has introduced a line of products which
target corporate chief executive officers, managers, and
planners. 4" Another initiative in the civilian sector is
the reduction in the number of middle level managers by
using EIS to give the executive more control of
information. 4 1

               EIS is being incorporated into civilian
information management infrastructures because managers
can obtain information faster, make better decisions, and
communicate more effectively. The commonality of
military and corporate information management
requirements are obvious. The power and abilities of
corporate EIS have not been overlooked in regard to
military applications. The use of an EIS has a logical
place in the evolution of an automated command and
control system. These systems would allow the commander

                                                     29


---

to monitor the four or five items of critical information
that he routinely needs to make qualified and informed
decisions. 4" Advantages of the EIS architecture are that
it lets the commander get the information 'off line*
without redirecting the efforts of the staff and that it
avoids the tendency of commanders and staffs becoming
bogged down in data overload.

               The five internal modules of the commercial
product Commander have direct application to the command
estimate process:

                1. Status reporting. The command and staff
elements have to have truth in the status of personnel,
equipment, and logistics.

               2. E-mail. Electronic mail is a superior method
of transferring large volumes of data as compared to hard
copy message and voice radio.

               3. Free-form database queries. This gives
freedom to access large amounts of data, allows a higher
echelon commander or staff to acquire information for
future planning without distracting lower echelons from
current operations.

               4. Reminder Capabilities. This application
provides assistance in tracking time-critical events
which would benefit planning and directing within the
staff estimate. Complex projects could be managed using
this module.

                                                     30


---

                 5. Delivery of outside news. This feature
contributes to the commanders insatiable need for current
information.

                 Artificial intelligence ana rule-based expert
systems are now being incorporated into civilian EIS. 4"
This trend has direct translations to military
applications. A rule-based expert system incorporating
the goals and applications outlined for an EIS can serve
as the architecture for an intelligent automated command
estimate.

                                    PERFORMANCE ENHANCEMENTS
                 There are several areas of the command estimate
and staff actions that have been identified as high
return functions for enhanced performance. A study
performed by Army Research Institute suggested the
following areas ceuld be analyzed better by using an
automated system:4 4
                 1. Tactical Courses of Action.
                 2. Battlefield Area.
                 3. Tactical Capabilities.
                 4. Enemy Threat.
                 5. Logistical Capabilities.
                 6. Tactical Courses of Action.
                 Of these areas, evaluation of the enemy threat is
the area that the use of rule-based artificial
intelligence will have the greatest impact. 4 0 Such a

                                                     31


---

system could significantly increase the capabilities of
the commander to better understand the threat and
anticipate enemy battlefield action. The result is that
better informed friendly courses of action could be
developed.

               Another area of that could benefit significantly
from enhancement with rule-based systems is the analysis
of tactical capabilities. This could be done for both
friendly and enemy forces. The ability of such a system
completely outstrips the coarse method of comparison
currently used in the present manual process.

               A third area that could derive significant
enhancement through assistance by rule-based expert
systems is the analysis of logistical capabilities. The
current manual procedures for using staff planning
factors are prone to calculation errors and
misin.erpretations by human operators. A rule-based
system could do such calculations with a greater
precision and with much more empirical detail.

                     RULE-BASED EXPERT SYSTEM WAR GAMING
               War fighting applications in the form of
mathematical models and simulations, are a relatively
recent addition to military planning and decision
making. 4 0 Automation is essential to the use of these
models and simulations due to the large amount of
computations required to perform them. One of the

                                                     32


---

strengths of using automation to do this is that it can

allow for numerous *what-if" analyses of a problem being
modeled. This gaming process provides the rapid testing

of the validity of ideas and plans." The ability to test

plans and operations has immediate military utility.

The current method of performing the validity

test of military plans is a manual war gaming process.

This logical step-by-step process relies heavily on
tactical judgment and experiences. It focuses the

attention of the staff on each phase of the operation in

a logical sequence. The process is one of action-
reaction-counteraction.4 However, the manual analysis

process is time-consuming because of the number of

combat, combat support, and combat service support units
involved in military operations. War gaming is an
evaluation process in which planners mentally play

through tactical movements and combat engagements. This

methodology is a highly interactive process where players

visualize the flow of battle and attempt to determine

advantages and disadvantages of a planned operation. One

benefit of automating this process is the elimination of

manual bookkeeping chores required to track the position,
strength, and missions of the numerous units. 4 0

               The availability of advanced technologies, such
as artificial intelligence (AI) and improved

communications, is driving military training systems to

new levels of sophistication.                   Since AI allows

                                            33


---

simulations to function in the same way as an enemy would
in battle, it will provide key capabilities for training
against the Soviet threat.8 " The obvious adaptation of
rule-based expert systems to such an environment would
provide a dramatic increase in the capabilities of
commanders and staffs to know the threat, to better
anticipate his actions, and thus to develop better battle
plans.6e

               While rule-based expert systems would assist in
the war gaming process, it should be recognized that the
use of the advanced technologies cannot improve upon
human judgement, they can provide analytical tools for
analysis, filtering of information, and performing
computations. These tools support decision making.02

                                               CONCLUSION
               The command estimate can be improved with
advanced technology which can be patterned after
demonstrated successes within civilian industry. The use
of rule-based expert systems can be the vehicle for the
future improvement and development of military command
and control systems.

                                                     34


---

           CHAPTER 2 END NOTES

            'Allison Kidd, 'Human Factors Problems in the
Design and Use of Expert Systems.* in Andrew Monk, ed.,
Fundamentals of Human-Computer Interaction (1984) : 237.

            'Randal P. Shumaker and Jude Franklin, *Artificial
Intelligence in Military Applications' in Jon L. Boyes and
Stephen J. Andriole, eds. Principals of Command and
Control (1987): 322.

            'Anthony Ralston, ed. , Encyclopedia of Computer
Science and Engineering (1983).

            'Andrew Monk, ed. , Fundamentals of Human-Computer

Interaction (1984).

            *Patrick Henry Wilson, Artificial Intelligence
(1984).

           GDavid W. Rolston, Principles of Artificial
Intelligence and Expert Systems Development (1988).

            'Paul E. Lehner, Artificial Intelligence and
National Defense: Opportunity and Challenke (1989).

            *W. A. Teeter, 'Expert Systems:  Tools in the
Commander's Decision Making Process.         MMAS Thesis, USA
CGSC, (1986): 2-29.

            *Frederick W. Rook II, 'Expert Systems for C3
Applications: A framework for the Transition From
Prototypes to Operational Systems," SIGNAL (September
1989): 110.

            10 Patrick Henry Winston, Artificial Intelligence
(1984): 176.

             " Ibid.

1 2 Ibid.

              "=Ibid.

              "4 Michael C. Albano and Robert A. Gearhart,
Jr., 'An Initial Study Examining the Feasibility of
Expert System Technology for Command and Control of
Supporting Arms in the United States Marine Corps,
Master Thesis, USN Post Graduate School (1988): 37.

           35


---

1eIbid.

1'Ibid.

1'Ibid.

'4Ibid.

'Ibid 33.
2 OIbid.
2 'Ibid.
2 2 Ibid 34.

           2 Ibid 35.

            2 4Interview with Doctor Jon Fallesen at Army
Research Institute, Fort Leavenworth FieldUnit on 19 Jan
90. (Cited hereafter as Fallesen).

            "eUS Army, Field Manual 101-5, Staff Organization
and Operations (1984).

             "US Army, Command and General Staff College
Student Text 100-9, The Command Estimate (1989).

            2 'Richard D. Lawrence, 'A Study of Quasi-Analytical
Models for Improvement of the Military Commander's
Tactical Decision Process' (1968): 15.

             "US Army, Command and General Staff College  1-3.
Student Text 100-9, The Command Estimate (1989)

           2 *Ibid 2-1.

             "0 John R. Schmader, 'Command Information
Requirements,' MMAS Thesis, USA CGSC (1985): 23.

            "'Ibid 3.

           12 D. J. Morris, 'Command, Control and Information
Systems Assessment,* Signal (October 1989): 57.

             "Advertisement for Commander Executive Information
System by Comshare, 'What is an EIS?," (1989): 1.

            3 41nterview, LTC Tichenor, 22 Jan 89, USA CGSC
Center for Army Tactics (Cited hereafter as Tichenor).

              38


---

            '"Advertisement for Commander Executive Information
System by Comshare, *What is an EIS?, (1989): 2.

      36Ibid 9.
      37 Ibid 6.

      36Ibid 10.

      3 6Ibid 11.

              "°Steven Burke, 'IBM Readies EIS Products,' PC
WEEK (MAY 22, 1989): 11.

           4 'Dennis Eskow, 'Phasing Out of Middle Managers May
Increase Dependence on EIS, PC WEEK (AUGUST 21,
1989): 71.

      4"Tichenor, 22 Jan 1990, CTAC.

           4 'Milestones,  INformation Week (September 25,
1989): 14.

           4 4 Charles F. Carter, Jr., Mark A. Archer, and
Albert E. Murray, Description of Selected Army Staff
Functions: Targets for Planning Aids U.S. Army Research
Inst for Behavioral Sciences Research Note 88-62
(1988).

      4 5 MCS AAR: 6.

            4 McKinney Pg: 69:

            4 'Managing People and Proje-tz, Carol Ellison, PC
Computing, August 1989, Pg 71

      '*US Army, ST 100-9, The Command Estimate  (1989):

4-1.

            4 Richard Shu and Kenneth Allison, 'COURSE OF
ACTION ANALYSIS; Using simulation to Visualize the flow
of Battle, Advanced Decision Systems, and Alfred
Correira, Lockheed Missiles and Space Co, Inc., (December
1988): 3.

             "0 Simulation's Brave New World, Barbara Starr,
Jane's Defence Weekly, (11 November 1989): 1031.

                           37


---

             O1 Memorandum, ATZL-SWT (CTAC) to Commander, USA
Combined Arms Center, SUBJECT: Establishing Priorities
for the Development of Automated Staff Planning Aids,
Fort Leavenworth, KS. 2 Aug 88. (cited hereafter as
ATZL): 6.

             "2 ATZL: 74.

                                                      38


---

                                                      CHAPTER 3

                                         RESEARCH METHODOLOGY

               This study used research of available literature,
interviews of subject matter experts, and systems
engineering techniques to examine the command estimate
process in detail.

                                           INFORMATION SOURCES
               The primary means of gathering information was the
literature search. The Combined Arms Research Library
(CARL) provided the initial information and a conduit to
the Defense Technical Information Center (DTIC) . However,
CARL was soon exhausted as a primary source and alternates
had to be obtained. Several CGSC students had references
in their personal libraries that provided much of the
current literature used in this study. Additionally, the
use of periodicals, magazines, and computer industry
literature proved a rich infusion of information.

                                               RESEARCH TOOLS
               Since the essence of this thesis is the use of
advanced computer techniques in military command and

                                                           39


---

control, automation assets were used to the fullest
extent. A tremendous tool used to organize the gathered
information was the software MemoryMate, a hypertext data
base system.' It was used to manipulate the research
material to indi-ate linkages between separate documents
and references with designated similarities. Dynamic
search criteria were designated to produce combinations of
relationships which allowed for rapid and frequent
organization of the material. For example, a search was
conducted through the data base containing more than 100
documents for the occurrence of the phrase, *automated
command and control' within each document. Within
seconds, the search was completed indicating the number of
documents containing the phrase. In turn. each document
was listed which enabled the investigator to review
pertinent material.

               Additionally, "hyperlinks" were established
between specific passages in a particular document and
*buttoned* to other words or phrases in other documents.
An example of this use of MemoryMate was a document
containing the phrase 'expert system' which was
hyperlinked to another piece of literature containing a
detailed technical definition of that phrase. When a
search was executed which brought up the first document,
the hyperlink button indicating the technical word could
then be toggled bringing up the linked document and
displaying the technical definition. Specific words or

                                                     40


---

phrases in this second document would in turn be buttoned
to still other documents. This allowed rapid collating of
ideas or thoughts and linked them much in the way people
think instead of the traditional linear way computers or
word processors function.

               Before this method of literature research could be
performed, the documents had to be input into the
computer. This was normally accomplished by manually
entering the documents into MemoryMate. Another method
for transferring material was by way of electronic mail
(E-Mail) . E-Mail input of documents was most preferred.
Manual input of the documents into the computer did not
prove cost effective unless the documents were short.

               Once the hypertext process was complete in a
literature research, a complete document, or relevant
parts, could then be electronically transcribed to the
thesis.

               Electronic Mail (E-Mail) was used to the maximum
extent to communicate with subject matter experts and to
transmit and receive applicable information. The primary
vehicle was the Defense Data Network (DDN). The E-Mail
interviews were conducted in the same manner as a
conventional interview with the exception that they did
not occur in real time. This method had the advantage
that questions could be well thought out and answers could
be explored in detail.

                                                     41


---

                       SELECTION OF SUBJECT NATTER EXPERTS
               Subject matter experts were often nominated by
interview subjects and from several listings provided by
members of the research committee. The basic parameters
that form the qualification of an expert varied to the
subject matter. Experts for the structure and methodology
of the command estimate were found within the Center for
Army Tactics (CTAC) at Fort Leavenworth. This group is
the Army's focal point for tactics doctrine and
instruction.' The command estimate process is taught to
students of the Command and General Staff College in
several courses to include Combat Operations, Operational
Warfighting, and Applied Tactics.
               Experts for command and control in general were
found at the Combined Arms Training Activity Center for
Army Lessons Learned (CATA-CALL) and the Army Research
Institute (ARI) Field Unit. Both agencies collect data
and assess the performance of command and control for the
Department of the Army.
               Authorities in artificial intelligence and rule-
based expert systems with respect to military applications
were difficult to find. The components that establish an
expert include both education and experience in military
applications of rule based systems. The US Army
Artificial Intelligence Lab, West Point, New York was the
primary source for expertise of rule-based systems in
military applications.

                                                     42


---

                   SYSTEMS ANALYSIS OF THE COMMAND ESTIMATE
               The focus of this thesis is the analysis of how
rule-based expert systems can assist in performing the
command estimate. To conduct this analysis, the command
estimate was examined using techniques of systems
analysis. A structured decomposition of the separate
functions within the process has been created using
systems analysis techniques as taught by the United States
Army Systems Automation Course. This course is the source
of training for Army Systems Automation Officers who carry
a functional area identifier of 53.3 The end analysis of
this effort illustrates which sections of the command
estimate are best performed by a manual process or by
assistance from a rule-based expert system.
               The first method used to look at the command
estimate is that of data flow diagrams. This use of
traditional methods of systems analysis of the basic
components of the command estimate is done from a
soldier/staff officer perspective. The process traces the
flow of information into the command estimate, how it is
processed, and where the information goes once it is used.
Data flow diagrams are the conventions used to perform the
structured decomposition of the command estimate. This
method is drawn from structured software engineering
techniques normally used in the process of automating
functions within business environments. 4

                                                     43


---

               The intent of this process is to use symbols and
text to describe the sequence of functional operation and
information flows within the command estimate. The
symbology differs from the formal structure as depicted in
ST 100-9.

               A graphic analysis model of the command estimate
was created to increase the understanding of the process.
The basic component of the structured analysis model was
the data flow diagram (DFD) .

               Each discrete process of the command estimate was
modeled using DFDs composed of four basic components as
depicted in figure 2. These components are:

                1. A source or sink is the system interface with
the external world. This is where information either
enters or leaves the system.0

               2. A process is where transformations of the
information occurs,

               3. Data flows represent the flow of information
from one part of the system to another.

               4. Data stores are where information is kept or
deposited. This is often a temporary store of information
as it awaits processing by another part of the system.'

               A simplified example of data flow using this
terminology would be a rule-based expert system designed
to maintain the status of artillery units in a division
using input from different status reports. Unit statuses
are received in message form. This input of information

                                                     44


---

DATA FLOW DIAGRAM

SOURCE

            DATAFLO

DATA STORE

                ;SINK 001

              FIGURE 2.
            45


---

is the source. The statuses of personnel, equipment, and

supplies form the data flow that goes into the process of

maintaining artillery unit status. In the process, the

rule-based system filters-out the following infor.ation

that is unique to artillery units: unit designation,

artillery equipment, artillery supplies, and artillery

personnel. The process then sends this information to a

data store where the informaion updates any previously

existing data. A report is then generated reflecting the

current status of artillery units. This report will be

used by commanders and staffs for planning and decisions.

This report is an information sink, or the point at which

the information goes external to the rule-based system.

A second methodology used to examine the command

estimate was identification of areas that have been

documented as poorly executed and the use of personal

observation by functional area experts.

Documented sources included the Army Lessons

Learned Management Information System (ALLMIS) provided

by the Combined Arms Training Activity Center for Army

Lessons Learned (CATA-CALL). 1  The Army Research Institute
(ARI) also provided sources.

Several tactics instructors in the Command and

General Staff College Center for Tactics (CGSC CTAC)

provided input based on observations of what is

successfully done and what is routinely not done well in

46


---

the performance of the command estimate. I then examined
these areas with respect to the feasibility of using rule-
based expert systems as staff-aids in enhancing the
execution of the command estimate.

                                                     47


---

              CHAPTER 3 END NOTES

'Broderbund, MemoryMate, (1988).

'US Army, CGSC Circular 351-1 (1989): 14.

            'US Army, Student Text (ST) 18-51, Systems Analysis
Handbook, (1984).

           'Philip W. Metzger, Managing a Programming Project,
(1981): 65.

            *Tom DeMarco, Concise Notes on Software
Engineering, (1979) : 3.

            'Control Data Corporation, Defining Software
Requirements (1985): 3-3.

"Ibid:  3-4.
'Ibid:  3-5.

           *Tom DeMarco0 Concise Notes on Software Engineering
(1979): 5.

           1°US Army, Army Lessons Learned Management
Information System (ALLMIS). (Cited hereafter as ALLMIS).

              48


---

                                               CHAPTER 4

                    IS THERE A NEED FOR RULE-BASED EXPERT
                         SYSTEMS IN COMMAND AND CONTROL?

               US Army Field Manual 100-5 sets three criteria
for a superlative command and control system.' First, it
must optimize available time. Second, it must stress
sound doctrine in operations and staff practices. And,
third, it must allow the managers of the battlefield
operating systems to position themselves where their
presence has the greatest impact. Manual methods of
performing command and control are no longer viable.
Current and emerging automated command and control
systems were not designed to operate in the environment
envisioned for AirLand Battle. The future for automated
command and control systems lies in the use of rule-based
expert systems.

               The purpose of this chapter is to analyze and
examine the following topics:

                1. Why current automated command and control
systems do not perform battlefield information
management.

                                                     49


---

               2. The need to counter the Soviet approach to
automated command and control.

                 3. Intelligent information management on the
future battlefield.

               4. How ATCCS will overload commanders with
information.

               The conclusion will demonstrate how rule-based
expert systems, assisting in the command estimate
process, can satisfy the three criteria for an
outstanding command and control system.

                          WHY CURRENT AUTOMATED C2 SYSTEMS
        DO NOT PERFORM BATTLEFIELD INFORMATION MANAGEMENT

               The Maneuver Control System (MCS) is the
automated workhorse that is being fielded in an effort to
take advantage of computer technology. However, MCS was
not designed for AirLand Battle doctrine and does not
satisfy the commander's battlefield information
management requirements. 2

               MCS provides a narrow range of support functions.
In addition to normal office automation such as word
processing, spreadsheets, E-mail, and data base
management, the system provides a sophisticated tactical
communications interface, map overlays, graphics, and
limited automatic staff reporting. As limited as MCS is,

                                                           50


---

no other system of similar magnitude and capabilities
exists that links tactical and operational levels in the
Army.'

               When evaluated during use in an advanced tactics
course taught at the United States Army Command and
General Staff College in 1989, MCS received a
'Leavenworth C" which means that it marginally met
standards.4 The good points were that the system was
excellent for passing short messages, had an acceptable
database management system, provided units the needed
capability of duplicating written information at more
than one location, and provided staff officers MS DOS
capabilities in the field. However, the system did not
significantly improve the commander's maneuver control
capability or the management of information.8

               In reality. MCS's contribution to the command and
control process was E-Mail and limited database
management. While the E-mail and database capabilities
were definitely valuable assets, by themselves they did
not significantly help the commander see the battle and
make decisions.

               In its current form, MCS does not provide a
justifiable return on the investment in effort required
to train the users and feed information into the system.
An automated system should not require more manpower and
time to do the job than the manual method it replaces.
This is not the case with many MCS features.*

                                                     51


---

               For any automated command and control system to
be helpful, it must do three things:

                1. Provide a top-down high speed review of
aggregate information where the effect of anomalies or
problems can be tracked.

               2. Show trend analysis.
               3. Provide exception reporting with an ability
to isolate problems where they occur.
               In the final analysis, MCS provides data, not
information. What is needed is a system that is
intelligent enough to assist the commander in rapidly
filtering the available data. Rule-based expert systems
can provide the commander with the automated assistance
needed on the modern battlefield.

                          AUTOMATION IN SOVIET TROOP CONTROL
               Soviets consider automation a key element in the
technical aspect of command and control. They recognize
that it is a superior method of assisting in the
development of detailed plans.'
               Current Soviet efforts to improve troop control
appear to be aimed at expanding availability of modern
control equipment, especially automation.0 Due to
technology transfer, US qualitative hardware advantages
are eroding. Therefore, it is important to capitalize on
the ability to better manage and exploit information.

                                                     52


---

The use of rule-based expert systems in critical areas
such as the command estimate is the best way to
accomplish this.

                                       BATTLEFIELD 2000 +
               Technology has insured that future armed
conflicts will be more intense, violent, and chaotic than
experienced in the past. Near-real-time information and
intelligence will become more critical than ammunition,
fuel, and spare parts. The commander will be forced to
wage a 'data war' . Far flung sophisticated sensor
systems will flood intelligence data bases with the input
of vast amounts of raw information. Across the board,
the battlefield operating systems (BOS) will have
voracious appetites for high volumes of current
information.
                Widely dispersed operations of US forces will
require commanders to monitor a large battlefield. High
tempo operations for sustained periods will put stress on
battlefield operating systems' survivability and
endurance. Enemy capabilities will approach parity with
our own. This environment will give the commander even
less time to monitor, decide, and act than he has
today."
                A conclusion that can be drawn from this picture
of tomorrow's battlefield is that the complexity of
modern technology is giving rise to an increasing number

                                                     53


---

of situations where any one human commander is incapable
of processing the volume of information involved in
making reliable and informed decisions. The key to
success in this environment is superior command and
control through intelligent information management.

               The command estimate is the engine to decision
making behind the Army's process of command and control.
On tomorrow's battlefield, it will need to be augmented
with automation to shorten the decision cycle. The use
of rule-based expert systems will allow the intelligent
filtering of data to produce useful, meaningful, and
timely information for the commander and staff.

                         ATCCS: AN INFORMATION FIREHOSE
               The Army Tactical Command and Control System will
provide an integrated family of interoperable systems, or
"system of systems' to support commanders in command and
control (C2) of their forces. ATCCS will be employed in
all theaters, at echelons corps and below to support
battlefield information functions. ATCCS will support
the distribution of information, data and digital
graphics among the Battlefield Operating Systems.''
               As a system of systems, the thrust of ATCCS is to
provide the organization, facilities, and procedures
through which the commander plans, directs, controls, and

                                                           54


---

coordinates operations. The commander frames his command
and control structures with a physical arrangement of
staff and facilities.1 2

               ATCCS is not an end to itself, but is the conduit
through which the commander will exercise command and
control on the battlefield. As a continually evolving
and integrated system, ATCCS presents the dilemma of a
two-edged sword. The immediate benefit is the incredible
panorama of detailed information the commander can
harvest on virtually any aspect of the battlefield. The
detriment is the same commander being overwhelmed by more
information than can humanly be assimilated and used in
making good and timely battlefield decisions.

               The concept of ATCCS is needed to get control of
the command and control architecture. However, ATCCS is
primarily concerned with the fielding of standard
hardware and software suites to provide commonality
across the battlefield operating systems (BOS) . The
theory is that it would then be possible to effortlessly
pass information from BOS to BOS. The evolutionary
approach and the rigid adherence to standard protocols,
standard message text formats and standard data elements
insures that the commander will be force-fed a continuous
flow of information. Unfortunately, the software, as
currently envisioned, is not revolutionary enough to
provide the commander with more than masses of raw
data."'

                                                     55


---

               There is a pressing need for something to be done
to assist the commander in processing this information.
The use of rule-based expert systems is a promising
alternative in assisting the commander in choosing an
intelligent course of action based on the overwhelming
amounts of available information.1 4

                               THE EXPERT SYSTEM TOOL BOX
               W. A. Teeter stated that expert systems could
serve three distinct roles in aiding the commander's
decision process.'"
                1. Consultative Expert systems.
               2. Interactive advisor.
               3. Thoroughly integrate all elements of the
command and control system.
               The consultative expert system would contain the
rules and methods of battlefield operating system
functional area experts. The commander and staff would
have access to an honest broker for adherence to US Army
tactical doctrine. It would ensure that the commander
addresses all the battlefield operating systems in plans
and orders. It would be the 'what if* agent and provide
the commander and staff with a means of examining one or
more permutations of a defined course of action.
               The function of interactive advisor would allow
the system to run in a background mode where it would
only surface when a diversion from established tactical

                                                     56


---

rules is sensed. It would alert the commander's
attention to the infraction and make recommendations
formulated on knowledge-base rules or heuristics. Also,
this system would be on call to answer questions or make
mathematical calculations.

               The system would integrate all staff components
into the command estimate process via the communications
facilities of ATCCS. This would allow the commander and
staff members to physically be at diverse locations on
the battlefield while simultaneously maintaining active
participation in the command estimate process. The staff
would no longer be in conflict over the need to
congregate at a headquarters location if their presence
is required elsewhere.

                                                 SUMMARY
               The time available for planning is the single
most important determinant of the number and types of
planning tasks that can be performed in the command
estimate. In combat situations, the planner may be
forced to shorten or curtail many of the planning tasks
normally performed given sufficient time.10 A
rule-based expert system could greatly assist in this
effort by assisting in the optimization of available
time.
               Due to the complexity and integration of the
battlefield operating systems, it is becoming

                                                     57


---

increasingly necessary to apply correct doctrine to
combat situations. The commander and staff need
automated assistance to coordinate battlefield operating
systems while applying correct doctrine during planning.
Rule-based expert systems acting as the cooperative
consultant could ensure that all doctrinal tenets are
considered and addressed.

               The management of time and the doctrinally
correct integration of battlefield systems is made more
complicated by the large geographical area involved. By
its nature, a rule-based expert system integrated
throughout ATCCS would allow the commander and staff to
be at critical locations and still fully participate in
the command estimate process.

               The technology is here and has been successfully
demonstrated within demanding civilian applications. The
use of rule-based expert systems within the command
estimate is key to success on tomorrow's battlefield.

                                                     58


---

CHAPTER 4 END NOTES

'US Army, FM 100-5, (1986): 21.

          2Memorandum, ATZL-SWT-C (CTAC) to  Commander, USA
Combined Arms Center, Subject: After         Action Report,
Advanced Command and Control Elective,       A399. (2 June
1989): (Cited hereafter as MCS AAR).

            'David J. Welch, "Evolutionary Development of
Command and Control Systems: The Fort Lewis Experience,
in Jon L. Boyes and Stephen J. Andriole, eds.
Principals of Command and Control (1987): 135.

           'US Army Command and General Staff College,
*Faculty Bulletin #30, CGSOC Evaluation and Grading
Policy, (16 Aug 89): para 5,a,(2) .

eMCS AAR: para 4,c.

Ibid: para 4,b.

            'Charles H. Jundt, *Comparing the C3 System of
NATO and the WARSAW Pact, in Jon L. Boyes and Stephen
J. Andriole, eds. Principals of Command and Control
(1987): 304.

           OW. Robert Reeves, "Soviet C3: Theory and
Practice, in Jon L. Boyes and Stephen J. Andriole,
eds. Principals of Command and Control (1987): 285.

           *Eberhardt Rechtin, "Command and control in the
years 2000 + , PG 468: from Principles of C2.

            1 0The Joint Chiefs of Staff, 1989 Joint Military Net
Assessment, CM-1943-89 (May 1989): 7-8.

            "1US Army, *Functional Description of ATCCS, The

E-Book (TC 11-7): (1988).

             "US ARMY, Army Command and Control Master Plan,
Volume I. Concepts and Management (1989): 2-7.

            13US Army, *Functional Description of ATCCS, The
E-Book (TC 11-7): (1988).

             "4Joseph S. Yavorsky, *Development of a Prototype
Multichannel Communications Network Maintenance Expert
System,' MMAS Thesis, UZA CGSC (1987): 10.

                     59


---

            18Teter, 'Expert gstems: Tools in the Commander's
Decision Making Process', (1986): 29.

            JIGS. P. Rogers, "Computer Revolution Energizes
Maneuver Planning System,* Armed Forces Journal
International: (Nov 89): 89.

                                                     60


---

                                                    CHAPTER 5

                       OBSERVATIONS OF THE COMMAND ESTIMATE

               The command estimate is a reliable and proven
process that will not be changed in the near future.
Given trained, well rested, and experienced commanders and
staffs with adequate time, it will consistently produce
superior results.'

               Given the premise that the command estimate illl
continue to be the primary vehicle for commanders and
staffs to perform mission planning, it can be examined and
analyzed to determine if there are any areas that can be
improved with assistance from rule-based expert systems.
The focus of this chapter is to analyze formal
observations made by the Center for Army Lessons Learned
(CALL) and the Army Research Institute for the Behavorial
and Social Sciences (ARI), as well as informal
observations of subject matter experts in the area of the
command estimate.

                                                81


---

                              THE SUCCESSFUL COMMAND ESTIMATE
               An observation was made that the commanders and
staffs that perform the command estimate well demonstrate
three common things:
              1. The commander's intent is thoroughly
understood by the staff and subordinates.
               2. The staff and subordinates know and understand
the commander's information requirements. It is from
these items of information that the commander makes his
tactical decisions. Focusing on these items puts everyone
on the 'same sheet of music.
               3. The actions of the staff are orchestrated.
This orchestration is normally performed by someone other
than the commander. Predominantly the G3/S3 operations
officer is the staff orchestrator. Techniques vary, but
the common denominator is that the staff officers are kept
focused and share information.
               Unfortunately, few organizations perform the
command estimate well. Many of the problems are a simple
reverse of those things done by successful units:
                1. The commander's intent is not understood.
                2. The wrong information is given to the
commander.

                                                           62


---

                 3. There is no time management and orchestration
of the staff.

                 An additional area is a failure to integrate
battlefield operating systems (BOS) into mission planning.

                                         FACTS AND ASSUMPTIONS
                 An area of the command estimate process that
suffers problems is the use of quantitative procedures
routinely performed by the S3 and S4 officers. Simple
calculations to generate march tables, forecasting
logistics, and other mathematical based projections are
measurably degraded as time is compressed and staff
officers are denied sleep.3
                 The computational skills of automation have long
been recognized. A system is needed that would assist
and automate use of planning factors. A rule-based
system could interact with staff planners and assist in
maintaining the current status of equipment and supplies
by constantly performing quantitative and trend analysis.

                                             MISSION ANALYSIS
                 The analysis of time is a critical aspect of
battlefield synchronization. Unfortunately, commanders
and staffs do not analyze and manage time well. Even
among well trained staffs, crisis management often
determines the amount of time and detail being devoted to

                                                     63


---

a task. As a consequence, the most trivial aspect of an
operation often receives more attention than is necessary
with the result of more important items being dealt with
in cursory fashion or completely ignored. Additionally,
staffs often mismanage the time for planning at their own
level and deny subordinates adequate time to plan and
prepare for the operation. The traditional rule of thumb
for taking 1/3 of the available time for planning and
giving subordinates 2/3 of the time is often abused.*

               The command estimate is time dependent. Whether
or not it is performed, and the quality to which it is
performed, is based on the time available between receipt
of the mission and time of execution. There needs to be
improvement in the analysis of available time and how to
best use it. Additionally, there is no one to act as the
time manager to ensure that staff actions and planning are
done in a timely manner to meet mission objectives.5

               A rule-based expert system could establish a time
table to accomplish staff planning and allow adequate time
for execution. The key here is a tool, that when given the
time frame from mission receipt to mission execution, can
time-manage critical tasks. This tool must be able to
determine how long each sub-process of the command
estimate should take, based on historical analysis of that
unit's performance, and suggest those steps that can be

                                                     84


---

abbreviated, combined within other steps, modified, or
completely ignored. Units must get at least the 2/3 time
available to adequately prepare and rehearse.

                 The commander and staffs on today's battlefield do
not lack a sufficient amount of information. They are
given an overwhelming amount of raw data. What is needed
is a good and timely analysis of this information. The
actual analysis of this information is cognitive
intensive. It is slow. Good analysis normally comes too
late to be of significant use to the commander in the
formulation of decisions. Also, the quality of
information coming from higher and lateral echelons is
often poor. What the commander needs is rapid and correct
analysis of information that is needed to make battlefield
decisions.0

                 Typically, the commander bases the majority of his
tactical decisions on only five or six major categories of
information. These are normally established through
experience and the commander's *feel' for the situation.'
Once the information requirements of the commander are
defined, a rule-based system can rapidly filter and
collate the volumes of information to present trend
analysis or exception reporting. This would provide the
commander with information focused along a predefined

                                                           65


---

critical path. It would also indicate those items of
information that are missing or do not fit into
established parameters.

                                     COMANDER'S GUIDANCE
               The commander's intent is the most critical
element of any military operation. It is the desired end-
state of what the forces are to achieve. A significant
problem in the information flow through the staff is that
the commander's intent is usually not specific enough.
Nor is it always disseminated to the appropriate staff
agencies. This causes confusion and is counterproductive
because it allows effort to be expended on what the staff
perceives to be the desired goals of the commander. There
is no standard method to convey the commander's intent.
It is normally given either orally, graphically, or in a
written paragraph. A combination of a sketch supported by
a written narrative is the most effective method to impart
this information to subordinates. This is normally
achieved on a single piece of paper or view-graph
overhead.
               A rule-based system could play the trusted
consultant in the expression of the commander's intent.
It could assist the commander in the construction of
understandable word pictures. By performing a correlation
between the narrative and sketch, it could insure that the

                                                     66


---

graphics and verbiage are mutually supporting and meet
doctrinal standards as well. It could also insure that it
is properly distributed to the staff agencies and
subordinates that need it to generate staff estimates and
produce information.

               Commanders often fail to adequately deliver
guidance to staff planners and subordinates. This is
normally a simple problem of the commander not
articulating well enough to the staff the initial intent
of what is to be accomplished. Observations indicate that
this step is unorganized or compounded by problems with
basic terminology and semantics. Another failure to
convey the commander's intent is simple omission in
communicating the information to lower echelons.0

               A rule-based expert system could insure that the
commander's guidance, mission, and other vital pieces of
information get disseminated to the appropriate staff and
planning elements. It could constantly poll the various
staff elements to ensure they know and understand the
guidance. As a cooperative assistant, such a rule-based
expert system could be the commander's honest broker to
insure that the intent included doctrinal requirements and
addressed all BOSs.

                                                     67


---

                                 DEVELOP COURSES OF ACTION
               In developing possible courses of action, steps
are frequently omitted or conducted out of order. This is
attributed to lack of training of commanders and staffs.
Additionally, some staff members are not always present to
give their input so specialized expertise is ignored or
interjected at a later point in the process.10 This
activity is based on the process of brainstorming.
Imagination and creativity are required out the process
follows a logical sequence of analytical steps to keep the
courses of action within the realm of feasibility.
The omission or incorrect sequencing of these steps can
invalidate the course of action that is developed.
               An additional problem in staff training is the
inability to coordinate with other staff elements or with
different echelons. During operation Urgent Fury, a lack
of command and control was observed between the division
and corps environments."
               The old saw that, 'Ten percent of the
organization never gets the word, could be obviated with
a system that is responsible for information
dissemination. The system could be the coordinator
between staff elements and insure that actions of any one
staff section are done in consonance with the other
sections. A primary advantage of an automated system is
that it could leverage the information interfaces that

                                                     68


---

exist between the different staff elements.'1 These exist
where more than one staff section needs a particular set
of information or where a staff section has to receive
information from one or more other sections. The expert
system could insure that the information is shared among
staff elements. The Chief of Staff, or Executive Officer
at lower levels, could monitor the information interfaces
and would have a tangible point from which to influence
overall staff efficiency.

                A rule-based expert system could monitor that
the steps are done in the correct sequence and provide
assistance if not enough information is available to
perform a step. Also, a distributed system that uses the
ATCCS communications architecture could obviate the need
for the entire staff to be physically present in the TOC
for planning and performing the process of testing, or war
gaming, courses of action.

                Staffs are not well trained to synchronize the BOS
when developing courses of action. Of the five BOS, only
maneuver, command and control, and fire support are
routinely included. Air defense and combat service
support are often only included when a question arises
that prompts their inclusion. Intelligence-electronic
warfare and mobility-countermobility-survivability are
often completely neglected." s

                                                     69


---

               A rule-based expert system could act as a tactics
honest broker. It would ensure doctrinally correct
integration of all of the BOS during the development of
courses of action. It would help in the prioritization of
their use. It would verify the planned use of each BOS
during war gaming.

               A final problem with the state of staff training
is the integration of different types of forces or
special doctrine. This is particularly evident in course
of action development and analysis. In the former,
resources are often completely overlooked or not used to
the fullest extent of their capabilities. In the latter,
they are often completely omitted." Examples are
Special Forces and general corps-level assets. Staffs at
brigade and division levels generally do not know how to
employ these resources.

               An expert system could have modules for various
force packages that could be employed. An example is for
a module containing expert rules for light infantry
operations to be used by an armored division commander
and staff. Another example might be a module for a corps
staff to use in developing plans for using a Marine
Amphibious Unit in coastal area operations. After aiding
in plan development, a rule-based expert system could also
assist in monitoring the use of these assets. More

                                                     70


---

mundane would be modules dealing with each battlefield
operating system to insure that they are being used
correctly with respect to doctrine.

                Intelligence preparation of the battlefield (IPB)
is not incorporated well into the command estimate. If
done at all, it is normally performed in isolation and
never impacts on the formulation of courses of action
until after they have been conceived. The IPB should be
continuous. Flexibility is lost because the IPB process
normally stops when a particular course of action is
decided on.'s

               The continuing process of IPB could be performed
as a constant background task of a rule-based expert
system. It would be totally integrated into the process
of each staff section. It would run continually and
divide the battlefield into close, deep, and rear areas.
An impressive capability of such a system is the ability
to continuously produce doctrinal and situational
templates of the enemy. It would also be able to
determine if the ground truth, or what is being observed
and reported, of enemy activity versus enemy doctrine is
not consistent. This could indicate enemy deception and
reduce the ability of the enemy to achieve tactical and
operational surprise.

                                                     71


---

                                    ANALYZE COURSES OF ACTION
               The single major problem units are observed to
have in using the command estimate is synchronization of
the BOS. 1 1 The method as outlined in ST 100-9 is the use
of a matrix to identify and list, in sequence, the
critical tasks developed during war gaming courses of
action.'? This allows for the synchronization of
battlefield activities in time and space. The amount of
detail produced in this synchronization matrix is related
to the commander's and staff's abilities, time available,
and needs.
               This synchronization matrix is often not used
correctly or not used at all due to time compression and
the fact that it is mildly complicated. The difficulty
in using this manual tool is attributed to staffs, as
seen at NTC, which are often tired and deprived of sleep.
The use of such tools requires a high degree of cognitive
awareness that most of the staff officers lack after
several days of continuous operations."
               A rule-based expert system could maintain
critical events and assist in developing the
synchronization matrix during war gaming. Also, neither
friendly or enemy logistical considerations are well
orchestrated into the war gaming process. The expert
system could track and maintain a current data base of
logistical statuses. Such a system would keep the

                                                          72


---

synchronization matrix dynamic. This syst m would allow
for the matrix to be updated as facts replace assumptions
or as logistical/operational parameters change. The level
of detail could be as significant and focused as
necessary. The system would execute a cross checking
process to insure that all the applicable BOSs have been
incl id in the synchronization process.

               Once courses of action are developed, they are
methodically analyzed to determine the best course of
action to pursue. The primary vehicle for this analysis
is war gaming. This phase is often not done well because
the relative level of training within the staff. A
primary player is the S2 officer. Unfortunately, at
battalion and brigade level, this is often a junior
officer with little experience. The underlying theme is
that staffs in general do not have the training or
experience to conduct adversarial war gaming well.1 9

               Ideally, a rule-based expert system could be both
an assistant and a tutor. It could train the staffs as
they do their mission. Based on a docrinally correct
rule-base, it could excel as a threat adversary during
the process of war gaming courses of action.

                                   OPORD/FRAGO PRODUCTION
               A final observation of breakdowns for the command
estimate process is a failure to generate and disseminate

                                                     73


---

operations plans, operations orders, and fragmentary
orders q 'ickly enough or in enough detail to be used in a
timely manner. Again, this is one task that degenerates
as time compresses and as people suffer from fatigue.
Another factor that influences the delay in orders
dissemination is the inability to get and maintain
accurate logistical information. The result of this
failure to get orders out invariably led to confusion and
operations that were not well synchronized. 2 0

                 An expert system would excel in the production and
dissemination of orders. It could perform redundancy
, ecks such as ensuring accuracy of grid coordinates and
time zones, that all applicable units were addressed
within the order and as recipients of the order, ensure
that the BOS were adequately addressed and coordinated,
and that the orders were disseminated to meet time
management thresholds. In cases where orders are sent out
with incomplete information, the expert system could do
the accounting function of making sure that supplementary
information wag delivered to the units that needed it as
it became available.

                                ABBREVIATED COMMAND ESTIMATE
                 Time is normally the most precious commodity on
the battlefield. In tactical operation it is often the
case that there is not enough time to perform a formal

                                                           74


---

command estimate as outlined in ST 100-9. When this is
the case, an abbreviated command estimate must be
performed. Although ST 100-9 contains a chapter on an
abbreviated command estimate, it does not shorten the
number of steps the commander must perform." In the
abbreviated command estimate, all the steps need to be
done. What is needed is assistance in showing the
commander and staff what steps in the process may be
shortened. This is currently based on experience or left
to chance.~2

           One of the strengths of an automated rule-based
expert system is that it can perform the time analysis and
continually prompt various staff elements for specific
items of information that are time sensitive or critical
at particular points in the command estimate process.
Another part of the time management function would be
management of an abbreviated process of the command
estimate. This could be accomplished by using historical
data or the most recent statuses of both friendly and
enemy forces.

                                                        SURY
               The command estimate is a superb vehicle for
teaching commanders and staffs correct methods for
analyzing mission requirements, developing possible
courses of action, and comparing alternatives to provide

                                                     75


---

the optimum means for accomplishing the mission.2 3
However, the observations in this chapter indicate that
the implementation of the command estimate is often poorly
conducted.

               Based on observations of the command estimate, the
following components of the command estimate are
recommended targets for assistance by rule-based expert
system .

                1. Facts and assumptions.
               2. Mission analysis.
               3. Commander's guidance.
               4. Develop courses of action.
               5. Analyze courses of action.
               6. Produce OPORDs and FRAGOs.
               7. Conduct an abbreviated command estimate.
               Table 1, chapter 5 summary, displays the
components of the command estimate and the type of
rule-based expert system that can be implemented to assist
each process.
               The use of rule-based expert systems can
contribute significantly to the command estimate.
Specifically, they can assist in clearly conveying the
commander's intent, insuring the staff provides the
commander with the proper information, providing time
management and orchestration of staff activities, and
synchronizing the BOS consistent with doctrine.

                                                     76


---

CHAPTER                 5   SUMMvARY

      COMMAND ESTIMATE                   TYPE OF
              PROCESS             RULE-BASED SYSTEM

Mission                            Normalize
                                   Data Maintenance
Facts and Assumptions              Consultant

Mission Analysis                   Data Maintenance
                                   Computation
Commander's Guidance
                                   Synchronize
Develop Courses                    Normalize
of Action
                                   Consultant
Intelligence                       Normalize
Preparation of the                 Production Output
Battlefield (IPB)
Analyze Courses                    Synchronize
of Action                          Consultant
OPORD/FRAGO                        Production Output

Abbrieviated                       Perform IPB
Command Estimate
                                   Synchronize
                                   Concuct War Game

                                   Normalize
                                   Production Output

                                   Synchroniz-
                                   Normalize
                                   Consultant
                                   Production Output

                        TABLE i.

                        77


---

                                         CHAPTER 5 END NOTES  CTAC
             'Lecture notes of MAJ David Goebels,

Instructor, 10 Jan 90.

             2 Interview, Major John Kelly, CTAC Instructor, 24
Jan 90. (Cited hereafter as Kelly).

             3 lnterview, Captain Tony  Garcia, Center for Army
Lessons Learned (CALL) Command          and Control Analyst: 12
January 1990.

             *Army Lessons Learned Management Information System,
Full Observation Report 3305, CALL Index D39022, 88/07/07.
(Cited hereafter as ALLMIS).

             'Kelly, 24 Jan 90.

      Ibid.

             'Interview, LTC Tichenor, CTAC:  22 Jan 90.            (Cited
hereafter as Tichenor).

      'Kelly, 24 Jan 90.

             -ALLMIS 195,  CALL Index D00050, 85/1113;                4125,
CALL Index 200074.         88/12/29; 3372, CALL Index               D40017,
88/04/11.

      1 0 Ibid 3164, CALL Index D08710 87/10/01

             LIbid 20, CALL Index B31026, 85/11/12; 740,            CALL

Index D00040, 86/01/07; 3522, CALL Index D39042,
88/07/11; and 1759 CALL Index 86/04/07.

      12 lbid 3456, CALL Index D39002, 88/07/06.

              "3 Kelly, 24 Jan 90.

             1 4 ALLMIS 60, CALL Index D00052, 85/11/04; 2461,
CALL Index D00175, 87/01/12; and 1004, CALL Index 851005,
85/11/03.

      "eKelly, 24 Jan 90.

             16ALLMIS, 4473, CALL Index  230242, 89/01/26; 3396.
                                         3389, CALL Index D40019,
CALL Index D40027, 88/04/13; and
88/04/11.

      "'US Army, ST 100-9, The Command Estimate (1989):

4-4.

                           78


---

laALLMIS 4526 CALL Index D60020 89/02/02.
'Ibid 1560, CALL Index D00072, 86/03/18
2OIbid 4471, CALL Index 88/01/26.
"Kelly, 24 Jan 90.
22ST 100-9 (1989): 6-1.
 "3 Kelly, 24 Jan 90.
2 4 Tichenor, 22 Jan 90.

                                             79


---

                                                    CHAPTER 6

                                  ANALYTICAL DECOMPOSITION OF
                                         THE COMMAND ESTIMATE

               This chapter uses techniques of systems analysis
to perform a decomposition of the way information is
processed and used within the command estimate. Data flow
diagrams (DFDs) are used to illustrate this examination.
Each component of the command estimate is analyzed from a
standpoint of what it does and a determination is then
made of whether the use of a rule-based expert system can
enhance the performance of that component to assist the
commander and staff in its execution.

               The command estimate is a continuous process
comprised of several interrelated sub-systems. These sub-
systems have no fixed starting or stopping points. The
relationships and dependencies which these sub-systems
have with one another are 0ased on the criticality of the
information which must pass from one system to another.
The relationships are affected by the time available to
conduct the command estimate.

                                                     80


---

                 Student Text (ST) 100-9 depicts the command
estimate as a cleanly defined system flow chart that
follows a linear structure.' Figure 3 represents the
command estimate as shown in ST 100-9. This diagram
shows the control flow of the major events in the system
but does not represent the flow of information through the
system. Taken literally, the diagram of the command
estimate conveys that a mission enters the system, is
processed through each sub-system, and then emerges as an
operation order (OPORD) or a fragmentary order (FRAGO).
Unfortunately, many commanders and staffs attempt to
execute the command estimate as depicted in individual and
discrete steps. They fail either because they cannot
efficiently manage the information, a shortage of time
does not allow for the command estimate to be followed, or
the situation does not fit the command estimate model.
This failure in executing the system does not allow them
to make intelligent and timely battlefield decisions.

                                                        MISSION
                 ST 100-9 defines mission as a statement of the job
to be performed by a unit. It establishes the information
of WHO, WHAT, WHEN, WHERE, and WHY of an operation. 2
                 The mission is the initiation point for conducting
any iteration of the command estimate. As such, it is a
source of information and is either received from a higher

                                                     81


---

     THE COMMAND ESTIMATE

IMission I

                 Facts and     Warning Order
                  Assumptions

LMission Analysis I

          -- i

Commander's Guidance

Develop Courses                Staff inputand

   of Action

        PCommander

Analyze Courses
    of Action

Decision ]

                    Figure 3.

                      82


---

headquarters or is determined by the commander based on
deduction from the current operation. Figure 4 contains
DFD 1.0 which is the decomposition of the mission. The
mission is filtered and a rough validity check is made to
ensure the following parameters are satisfied:

                  1. WHO: The mission must apply to the unit
receiving the mission.

                 2. WHAT: The mission must be within the
capability of the unit.

                 3. WHEN: The time of mission execution must
allow adequate time for planning and rehearsal.

                 4. WHERE: The location of the mission must take
place within the unit's area of operations.

                 5. WHY: The reason for the action must be given
if the subordinate units are expected to produce actions
in consonance with the force as a whole.

                 Missions that do not satisfy the parameters above
are rejected until they can be clarified or until the unit
is provided the resources to accomplish the mission. Once
the mission is validated, the information is transformed
into a data store where it is maintained for future
processing.

                                                     83


---

           MISSION              CDR's

 Military                     *Intent
Operation                      *Guidac
                                Anticipated
          Mission  Direction
                                  actions

                               Insights
                                Cnen

Reject1.

                              CDR's Guidance*

          Facts               Rule-based
                               System

                   Figure 4.

                   84


---

                 A rule-based expert system could assist the
commander and staff by insuring the mission information
conveys the following:

                  1. WHO: A rule-based expert system can track the
forces available, their statuses, and indicate exceptional
capabilities. This is readily applicable to a rule-based
system that can assimilate a broad range of forces,
equipmen + capabilities and doctrines with respect to the
commander's intent.

                 2. WHAT: A rule-based system could ensure that
the verbiage is normalized so the expression of WHAT is
expressed in doctrinally correct terms. It could also
cause an alert if the mission is outside of the unit's
capabilities.

                 3. WHEN: A rule-based expert system can assist
the commander in the synchronization of battlefield
operating systems by ensuring that an achievable time line
is established. It would allocate time to the
headquarters and to subordinates based on either the time
ratio directed by the commander, or the traditional 1/3 -
2/3 rule where the headquarters is given 1/3 of the
available time to plan for the mission and subordinate
units are given the remainder.' This system would
maintain rules and time models for various battlefield
activities such as barrier construction, mine field
emplacement, bridge erection, administrative and tactical

                                                     85


---

movement of units, etc., for correct time sequencing and
battlefield integration.

                4. WHERE: The location for mission execution is
critical to space-time synchronization. The area of
logistics is severely impacted by this relationship. A
rule-based system could determine fuel and transport
requirements and assist in transportaton management. It
would also coordinate maps and other geographical data for
mission planning and execution.

                5. WHY: In many military endeavors, the WHY is
often the most important element of information. Much
like the commander's intent, it conveys an image of the
"big picture.* If the WHY is not clear in the commander's
intent, it should be reclarified or separately conveyed
and distributed. A rule-based system can ensure that the
WHY is normalized to doctrinally correct terms.

                Another critical element of mission information is
the explanation of the higher commander's intent. This is
an information source and forms the basis of the
commander's intent at the level receiving the mission.
The commandqr's intent, mission, and commander's gitidance
are transformed into data stores and will be used in later
processes. The data store that is the commander's intent
is the master plan that contains the expression of the
commander's tacticai image of the battlefield at the end
of the operation. Closely related to the intent is the

                                                86


---

commander's guidance which contains mission information
that is not included in the mission statement or
commander's intent.

                 A rule-based system could assist in the expression
of the commander's intent, commander's guidance, and
mission statement by normalizing the verbiage and
accompanying graphics to doctrinally correct expressions.
It would also monitor and manage the dissemination of this
information to ensure all participants had received it.
The result would be that the information would be
understood by all participants.

                 Some of the information that influences the
establishment of the mission parameters does not readily
lend itself to rule-based expert system assistance. This
includes the commander's insights, concerns, and
anticipated actions. Due to the cognitive level of these
insights, concerns, and anticipations, it is best if this
information is left to the commander to develop and convey
to subordinates.

                                         FACTS AND ASSUMPTIONS
                 After receipt of the mission and the higher
commander's intent, each staff section generates factual
information of the state of ',heir respective areas. These
information sources provide a quick status summary to
ascertain if the proposed operation can oe supported. DFD

                                                          87


---

FACTS AND ASSUMPTIONS

                                    G1/S1*

Information I su .G/4  Systemh

      projecte

   futu88


---

2.0 found in figure 5 demonstrates the flow as the
following categories of facts serve as information

                                  4

sources:

                1. Gi/Si provides a current report on the
personnel status, morale, and administrative posture of
the organization.

                2. G2/S2 provides an analysis of the battlefield
area measured in depth, width, height, and time; both an
operational and tactical view of the terrain; current
weather; and known enemy information. The specific
process performed by the G2/S2 is called the intelligence
preparation of the battlefield (IPB). It is a systematic
and continuous process of analyzing the enemy, weather,
and terrain in a specific geographical area.5

               3. G3/S3 conducts the majority of the synthesis
of the information. This includes:

               a. Mission and commander's intent (one and two
levels higher).

               b. Current task organization (two levels down).
               c. Current unit status This will normally
address the combat power, combat support posture, and
combat service support capabilities. The result will be a
rating of mission capability.
               d. Sister service combat support.

                                                     89


---

               e. Other unit information such as locations,
status, and mission of flank units, uncommitted units,
higher headquarters, and supporting units.

               f. Time lines and other synchronization data.
               4. G4/S4 provides an accurate and current
assessment of the logistic situation of the organization
to include subordinate, attached, and other supporting
units. FM 101-5 provides a format for this information
which is contained in the logistics estimate. 6 It
includes:
               a. Maintenance capabilities.
               b. Status of all classes of supply.
               c. Services available to support operations.
               d. Transportation assets and capabilities.
               e. Available labor for general efforts.
                f. Facilities and construction capabilities.
               g. Other capabilities available to the force.
               5. G5 provides civil affairs and nuclear/chemical
weapon preclusion data. This was not depicted in the DFD.
              Assumptions are processed as shown in DFD 3.0 in
figure 5. The purpose of these assumptions is to replace
missing, but necessary, facts. These assumptions will
also be used if current factual information is subject to
change due to time-event sensitivity.7 Assumptions serve
as information sources in the following areas:

                                                     90


---

                1. Gi/Si will assume personnel factors for each
course of action. These include:

               a. Critical MOS shortages.
               b. Replacement flow.
               c. Medical evacuation and hospital support.
               d. Human factors such as morale.
               2. G2/S2 will make assumptions about:
               a. Terrain and weather.
               b. Enemy capabilities and vulnerabilities.
               c. Friendly capabilities and vulnerabilities.
               3. G3/S3 will make assumptions about friendly
forces and the general capability to conduct the
operation:
               a. Status of maneuver, combat support, and combat
service support units.
               b. Electronic Warfare support.
               c. Aviation support.
               d. Time.
               4. G4/S4 discusses significant differences in the
current and anticipated logisitical capabilities.
               The amount of facts and information that the staff
has to manage is massive. In many instances, the facts
that have to be provided to the commander are derived from
manual calculations which could easily be automated.
Additionally, many of the items of information on which
the various staff estimates are based are time sensitive.

                                                     91


---

  A rule-based assistant would greatly enhance the ability
  of the staff to filter information and maintain the data
  stores of facts and assumptions. This system would prompt
  various staff sections for updated information and would
  strive to replace assumed data with fact as it became
  available

                                            MISSION ANALYSIS
                 Mission analysis is the most information
 management intensive portion of the command estimate. It
 processes information given in the mission statement,
 facts, assumptions, the commander's intent at the present
 and two next higher levels, and the commander's initial
 guidance. These elements are synthesized into a developed
 and focused mission statement. Figures 6 and 7 present
 the DFD decomposition of this process.
                 The primary inputs are the higher commander's
 intent, the mission statement, derived facts and
assumptions as identified in the mission process. The
first transformation of this information is shown in DFD
4.0, figure 6. Here, the identification of the specified
and implied tasks occurs. Specified tasks are those tasks
that are clearly specified in the mission received.
Implied tasks are those tasks that are not specified but
are deduced as necessary to accomplish the overall mission
or to satisfy any of the specified tasks. This deduction

                                                     92


---

           MISSION ANALYSIS

Mission    Higher CDR's                                   Determine
  nalysis      Intent*                                   & ailocate

Essential  Implied tasks*

                    Riul-bsed Retrire 6.em

           Sysememn

                                                    94.


---

is accomplished by analysis of the order and analysis of
the elements of the tactical situation.' An immediate
product of the identification of the specified and implied
task is the identification of essential tasks that becomes
a data store for later use. Essential tasks are those
that must be accomplished to complete the overall mission.
To properly do this, the staff must understand the intent
of their immediate commander and the intent of the
commanders two levels up. In conjunction with the
essential, implied, and specified tasks, the commander's
intent is again analyzed in DFD 4.5 to insure that it is
understood and the derived tasks support its
accomplishment.*

               The function of a rule-based system to provide
assistance in the process of understanding the commander's
intent would be the same as outlinpt in the mission
process (DFD 1.0, figure 4). It would be used to
normalize the graphics and verbiage with correct doctrine
to insure that what the commander intends for the forces
to accomplish is accurately portrayed to subordinates.
Additionally, assistance would be given to the
identification and maintenance of essential tasks. An
expert system could insure that all battlefield operating
systems are considered and that staff elements were kept
informed of their status.

                                                     94


---

                 After the essential tasks to the mission are
determined, the information goes through several parallel
transformations to determine the impact of time,
constraints, risk, and restrictions. These remaining
parallel transformations are ideal candidates for
assistance using rule-based systems. Figure 6 depicts
these transformations.

                       An initial time line is created as a data
store in DFD 4.1, figure 6. This forms the basis of
synchronization for mission planning and execution. The
most significant area of assistance that a rule-based
expert system can give to the command estimate is time
management. It could perform this function by determining
the time available and generating time tables to sequence
planning at headquarters and unit level, manage time-
distance calculations based on equipment capabilities and
enemy dispositions, assist in the backward planning
process, monitor staff and subordinate unit progress, and
orchestrate the flow of information between staff
elements.

                 Constraints, as shown in DFD 4.2, figure 6, are
those things that a higher headquarters requires to be
done. These constraints are limitations to the actions
of the subordinate commander. They can be normalized and
disseminated to all staff sections by a rule-based system.
This will insure that these constraints are understood and

                                                     95


---

can be planned into the mission.
               Risks are shown in DFD 4.3, figure 6. They can be

generated from any staff area input that indicates
friendly forces may not meet desired parameters such as
desired levels of supplies, quantitative superiority in
forces and equipment, intelligence of enemy capabilities,
etc., to meet possible enemy courses of action. A rule-
based system could monitor these areas of risk and prompt
planners to address them before developing statements of
mission and intent. Restrictions and other limitations
can be handled in the same manner.

               The ability of a rule-based expert system to
assist in the management of risk, constraints, and
restrictions will allow the commander and staff to better
shape the mission planning for optimum results.

               The resulting information from these
transformations is used to determine if the available
forces can accomplish the mission. This process is shown
in DFD 4.6, figure 7. A tentative task organization is
produced from the available forces and a rough estimate
is made to determine if the forces are sufficient to
accomplish the mission. It is at this point that the
commander makes a decision based on the results of the
mission analysis. If he approves the identified essential
tasks, he will provide the restated mission as shown in
DFD 4.7, figure 7. This mission statement is dynamic and

                                                     96


---

          MISSION ANALYSIS
             (Continued)

OrgalzalIf foacskca
                         Dhemision

Organizaion*Rules-based

     ReSystem

the  7.io

WHWH7 WE


---

is sensitive to the identification of other essential
tasks. Once approved, the mission analysis and restated
mission form the basis for the warning order and provide
focus for course of action development.10 The warning
order represents a data sink, or an information output,
and is the first time information formally leaves the
command estimate.

                Automation can assist in the initial calculation
of force ratios and the development of a task organization
based on forces available and the enemy. A rule-based
system can further refine this process by determining
force capabilities based on combat intelligence (facts)
and projections (assumptions).

               The restated mission will contain the WHO, WHAT,
WHEN, and WHERE from the mission statement. This is a
noticeable change from the mission process (DFD 1.0,
figure 4), because it no longer contains the WHY. The
product from the restated mission is the warning order
which explains the WHY.

               Assisted with a rule-based expert system, the
restated mission would go through the normalization
process to ensure that it used the proper graphics and
technically correct vernacular to convey the commander's
intent. It would also address the appropriate battlefield
framework. Finally, the warning order would be

                                                     98


---

disseminated by the rule-based system insuring it sent to
and received by the appropriate units.

                                     COMMANDER'S GUIDANCE
               Although the commander will provide planning
guidance to his staff and subordinates as often as
necessary, it is critical after the restatement of the
mission. This guidance will provide the staff with a
better understanding of the commander's image, or mental
model of the situation he wants translated into action by
the staff." The guidance, coupled with the restated
mission, will reinforce the commander's intent and produce
the starting point for the development of courses of
action. Figure 8, commander's guidance DFD, examines the
process of formulating the planning guidance.
               Several data stores effect the process of
formulating planning guidance. These are the commander's
intent, risk, and the time line. The commander's intent
was developed in the mission process (DFD 1.0, figure 4)
while the components of risk and time line have their
genesis in the mission analysis process (DFD 4.0, figure
6). It should be noted that all these data store are
constantly being refined and updated. Additionally, the
commander will define specific courses of action that he
desires to have developed. The time line is displayed as
both an input, from the mission analysis process (DFD

                                                     99


---

COMMANDER'S GUIDANCE

Comamnder's  CDR's
Guidance     Intent*

Timee                                Line*

                      guidanceD      elop Courses
             foRm ulelctbdased

                                100


---

4.0, figure 6) , and as an output because the commander
formally announces the time for the course of action
briefing. This time line may be different than initially
generated in the mission analysis process. Another output
is the warning order. It is identical to the warning
order issued during th mission analysis process (DFD 4.7,
figure 7) but may contain updated information.

               The end state of the commander's guidance is
formal presentation of the restated mission. It should be
noted in figure 8 that the process for this is labeled the
same (DFD 4.7) as that found in the mission analysis
process in figure 7. The mechanics are identical. If
there are no changes, the restated mission is the same
entity as defined in the mission analysis process.

               The entire process of the commander's guidance,
less the commander's declaration of specific courses of
action, is a candidate for assistance from rule-based
expert systems. The time line and warning order outputs
are the same as described in the mission analysis process
and will be the same entities if there are no changes.

               At the conclusion of this process, the staff will
continue collecting and processing information and will
begin developing of courses of action.

                                                     101


---

                                 DEVELOP COURSES OF ACTION
               Developing courses of action (COA) to accomplish
the mission is military art bound by military science.
The key to developing COAs is to release imagination and
creativity during "brainstorming' by the commander and
G3/S3. 12 COAs must be feasible and have to be capable of
accomplishing the assigned mission. Any COA that is
determined not to be feasible is immediately rejected.
               There is no rule-of-thumb for the exact number of
COAs to develop. If time permits, several COAs should be
generated for each likely enemy COA as determined by the
G2/S2 in the IPB. The total number of courses of action
must be manageable.
               A proposed COA must be significantly different
from any others. Significant difference is normally
identified in one of the following areas:13
                1. Use of reserve forces.
               2. Task organizations.
               3. Location and purpose of main effort.
               4. Scheme of maneuver.
               5. Defeat mechanism.
               After a COA is proposed, the commander and staff
perform several information transformations to assimilate
available information, the mission, the commander's
intent, and the application of doctrine. The steps in the
method to synthesize this information are:"4

                                                     102


---

                1. Analyze relative combat power.
                2. Array initial forces.
                3. Develop the scheme of maneuver.
                4. Determine command and control means and
                maneuver control measures.
                5. Prepare COA statement(s) and sketch(es).
               The key inputs for developing courses of action
are the DFD process of IPB, data stores containing the
facts, assumptions, task organization, essential tasks,
the time line, and mission. These data stores provide the
WHO, WHAT, WHEN, WHERE, HOW, and WHY for the development
of the courses of action. This information is generated
in other processes of the command estimate and are
maintained as data stores until needed. Figure 9 depicts
the flow of this information into the process to determine
possible courses of action (DFD 6.0). The IPB is a
distinct and separate process from the command estimate.
It is not functionally decomposed in this chapter. Facts
and assumptions are generated in DFDs 2.0 and 3.0, figure
5. Task organization, essential tasks, and the time line
are developed during mission analysis in DFDs 4.0, 4.1,
and 4.6, figures 6 and 7. Additionally, the time line
information was further processed in DFD 5.0. planning
guidance formulation, figure 8.
               Each of the inputs is a candidate for assistance
by rule-based expert systems. The data stores have been

                                                     103


---

DEVELOP COURSES OF ACTION

                      Facts and Assumptions*

COsTas             Ora ision'

CRsDevelop         EsnilTss

Analyz COAs

                   Figume      Line

             6104


---

discussed with the process from which they originated.
The intelligence preparation of the battlefield (IPB) is
discussed in a later section. Although all the inputs
into the process of determining possible COAs can be
assisted with rule-based systems, the creative act of
developing the possible COAs should be a human performed
process with minimal coaching or assistance.

                After the COAs have been determined, the
information is processed to analyze the relative combat
power of friendly versus enemy forces (DFD 6.1, figure 9).
This is currently a quick computation of rough ratios
using arbitrarily assigned comparison values. The purpose
is to give a *feel" for relative strengths and is not for
absolute comparisons. The result provides for some
general conclusions about the type of operations that can
be conducted.15 If this rough model depicts an untenable
COA, it will be rejected at this point.

               The ability of a rule-based expert system to
provide a greater depth of empirical detail in this
process is apparent. An automated system could calculate
detailed information for both friendly and enemy units to
produce a much more scientific and accurate picture of the
opposing forces.

                The COA is now ready to have forces arrayed to
represent the necessary troop dispositions. This is a

                                                     105


---

graphical map-based exercise that determines the forces
needed to accomplish the mission and provides a starting
point for the scheme of maneuver. The array of friendly
forces is made without regard to task organization beyond
what is available by unit types. Inputs for this process
are the mission and the commander's intent. The purpose
of this step is to provide a notional image of how the
forces will appear on the battlefield. "

               The basis for arraying generic forces is
performed using a procedure delineated in ST 100-9:"7

                1. Determine the ratio of forces involved.
                2. Determine the size of the units to be arrayed.
                3. Determine a proposed LD/LC (offense) or FEBA
(defense).
                4. Develop the deception story.
                5. Make initial array of friendly forces.
               Determining the force ratios necessary for the
operation and the size of the units and arraying initial
forces is a process that has been demonstrated by the
AirLand Battle Management (ALBM) system.10 This should be
a rule-based system task within the command estimate.
However, the steps of determining the proposed LD/LC or
FEBA and developing the deception story should be human
performed tasks. Additionally, the inputs of the
commander's guidance and mission should be assisted with

                                                     106


---

rule-based systems. Both of these data stores, and their
management, have been discussed in DFDs 1.0, 4.7, and 5.0
in figures 4, 7, and 8, respectively.

               The next process is to develop the scheme of
maneuver for the forces. This process is the central
expression of the commander's image and intent for the
battle." It is the zenith of military art within the
command estimate. It provides the HOW to the course of
action by showing the actual employment of the forces.
Subsequent analysis of the COA is dependent upon the
scheme of maneuver. Two inputs are primary to this
process: the data store of the commander's intent and the
data source of the appropriate battlefield framework
(offense vs. defense). The acid test for the scheme of
maneuver is that it must accomplish the commander's
intent. 2 0 If it does not, the COA is iejected.

               Like arraying initial forces, the process of
developing the scheme of maneuver is highly cognitive and
does not fit the model for assistance with a rule-based
system. However, it can be assisted in the effort to
determine if the doctrinal tenets of the battlefield
framework have been adequately addressed.

               Command and control means and maneuver control
measures are allocated in the next process (figure 9, DFD
6.4). This is a two-fold process to insure a proper span
of control exists by allocating headquarters assets to

                                                     107


---

each maneuver unit and that appropriate battlefield
geometry is applied to control the fire and maneuver of
those units. If any maneuver units cannot be adequately
organized under the control of a headquarters element, or
command and control cannot be established, the COA will be
rejected. This process does not lend itself to effective
assistance with rule-based systems.

               The final transformation of information with
respect to develop COAs is to prepare course of action
statement(s) and sketch(es) . This is the responsibility
of the G3/S3 and will contain the WHAT, WHEN, WHERE, HOW,
and WHY of the mission. The combination of a statement
and a sketch must convey a clear image of the HOW for a
unit to accomplish a given mission. It is expressed in
standard military graphic symbols and operational terms.
If, at this point, a COA is detected as being either not
feasible or fails to accomplish the commander's intent,
the COA will be rejected. This process lends itself
readily to rule-based expert system assistance. The
primary focus would be to insure that graphics and terms
were doctrinally correct.

                                      COA ANALYSIS

               After the COAs are developed and sketched, they
are analyzed by the staff to identify the best COA to
recommend to the commander. This analysis must be done

                                                     108


---

promptly and efficiently. Any item of information
developed by one staff element that might effect another's
must be surfaced immediately."1 The premier event of this
analysis is the conduct of the war game. Figure 10
decomposes the flow of information during the process of
analyzing COAs.

               The first transformation of information occurs
when the G3/S3 briefs the staff about each course of
action (DFD 7.0, figure 10). During this brief, if a COA
is identified as not being feasible by any staff member,
it is immediately rejected. After the courses of action
are briefed, a determination is made on which courses of
action will be war gamed (DFD 7.1). The inputs to this
decision are the IPB and the G3/S3 assessment. The
management of these inputs could be assisted by a rule-
based system.

               ST 100-9 states that at this time, the process of
war gaming begins by each staff sections. 2 2 However,
before the actual war gaming phase can begin, several
processes must occur to insure the staffs are working with
good information. It is essential that the proper forces
are considered and the critical events identified.

               In DFD 7.2, figure 10, assumptions must be
validated or replaced by facts. These assumptions were
identified in DFD 3.0, figure 5. Any COA depending on
assumptions that are no longer valid and cannot be

                                                    109


---

      COA ANALYSIS

COA

Rem bieachon

                                 Ruasbke

              VCOa~lSidysateems

Assumptons    110


---

replaced by reliable fact will be rejected. The COA must
then be audited to insure that the BOSs have been
adequately addressed as shown in DFD 7.3, figure 10. The
task organization that was developed in DFD 4.6, figure 7,
and refined in DFDs 6.0 and 6.3, figure 9, is the major
input. Maintenance of the task organization is well
suited for assistance with a rule-based system. The
process of filtering the COA through a mechanism to insure
that the BOSs have been adequately addressed is well
suited for a rule-base expert system. It should be noted
that failure to include or adequately address a BOS is not
grounds to reject the COA. However, it would be the
responsibility of the rule-based system to bring this
omission to the attention of the commander and staff.

                 The prioritization of critical tasks is depicted
in DFD 7.4, figure 10. Is is accomplished by processing
data store information of essential tasks (DFD 4.0 and
6.0), commander's intent (DFD 1.0, 4.0, 5.0, and
6.3), time line (DFDs 4.1, 5.0, and 6.0), and risk (DFDs
4.3 and 5.0). An output is a data store establishing a
synchronization matrix which is developed from integrating
the BOS into the time line. This process is a viable
candidate for assistance with rule-based systems since all
inputs and the output are data stores that lend themselves
to automation.

                                                111


---

                In the current manual implementation of the
command estimate, the war game is conducted abstractly and
does not use much scientific technique. It is a mental
exercise that relies on the experience of the war gamer.
DFD 7.5 in figure 10 displays the inputs into the war game
as the COAs and the interplay with the G2/S2 IPB. The
outputs include a synchronization matrix, and a data store
of critical events. While the synchronization matrix is
an easy function to automate using a rule-based system,
the process of identifying critical events should be a
human function. Once identified by the staff, the
management of critical events would be done by a rule-
based system that would collate the essential tasks
indentified in DFD 4.0, figure 6. The sub-components of
the war game will not be decomposed in this study.
Instead, the entire war game process should be considered
for replacement by a rule-based expert system simulation
exercise in which enemy and friendly forces are structured
and arrayed over a specified piece of terrain. The
results of such engagement should be easy to determine and
could be conducted rapidly. This will allow for multiple
iterations of a COA versus several enemy COAs. A rule-
based system would excel at this bec&use it could, using a
rule-base of enemy tactics and equipment, closely
approximate the reactions of an enemy force.

                Upon completion of the war game, the results are

                                                     112


---

compared in DFD 7.6, figure 10, to determine which COA has
the highest probability of success against the most likely
enemy COA. This is done by each staff section. The G3/S3
evaluates the results using subjective criteria such as
BOS, tenets of AirLand Battle, the military aspects of
terrain, etc. The GI and G4 compare the COAs in terms of
how well they can be supported from a personnel or
logistics perspective. The commander may specify factors
that have a greater precedence over others. This final
process of determining the best COA is highly subjective.
It should be a human derived process. Rule-based systems
for determination of the best COA are not appropriate.

                                                 DECISION
               The recommendation for the best COA is presented
to the commander in the form of a decision brief. It is
during this session that the commander formalizes his
decision. Figure 11 represents the decision process.
DFD 8.0 demonstrates that two inputs are processed along
with the recommendation. The first is the mission. The
COA must accomplish the mission which began this process.
The second input is the higher commander's intent. Again,
the COA must meet the criteria of this input. If, by some
chance, a COA at this point fails these final tests, it
may be rejected. The products of this transformation are
the warning order and the decision. The warning order is

                                                    113


---

                DECISION

Recommendation                       Mission*

                                           Higher CDR's
                                           Intent*

Reject          8.0

                Decis*               Rule-based
                                      System
                         Figure 11.
                       114


---

the same data sink as discussed in DFDs 4.7 and 5.0.
Unless changed, it is the same entity.

                 The input data stores of mission and higher
commander's intent have been designated for rule-based
systems in several previous DFDs and have been discussed
in detail. The actual process of the decision is based on
the commander's experience, trust and confidence in his
command, and his estimate of the situation. He may agree
with the recommendation or reject it and elect an
alternate COA. Additionally, he may direct the use of a
COA with modifications or one not previously considered.
In any event, the commander must refine the COA into a
clear decision ind then anncunce the decision and the
concept of the operation.2" The process of making the
decision is not appropriate for a rule-based system.
However, the warning order is a candidate for using rule-
based systems.

                                       OPORD/FAGO PREPARATION
                 The operations order (OPORD) or fragmentary order
(FRAGO) process relies on several inputs to insure the
output is clear, concise, and conveys the intended
information. Figure 12 contains the information flow of
this process. The primary inputs are the data stores of
mission and commander's intent. These provide the WHAT,

                                                          115


---

OPORD/FRAGO

Synch             Mission*
Matrix*

                            CDR's Intent*

                            Rulekbased

         Prepare  2Sse

         11an


---

WHY, and WHERE. These are the same data stores as
discussed in DFD 1.0 and have been refined at every
process through which they have passed. The commander's
guidance is a data store for information that is not
contained in either the commander's intent or mission
statement but is still germane to the situation. The task
organization is the result of the refinement of DFD 6.3
which developed the scheme of maneuver. This data store
provides the WHO. The synchronization matrix produced by
DFD 7.5 provides the detailed WHEN.

                The OPORD/FRAGO will produce a completed HOW for
the units to accomplish the mission. To do this, it
must:24

                1. Make maximum use of graphics.
                2. Not be unnecessarily redundant.
                3. Be concise.
                4. Include necessary friendly information.
                5. Convey the intent of the commander.
                The process of preparing plans and orders should
be assisted by rule-based expert systems. It is highly
structured and follows doctrinally defined procedures.
The inputs of information have been designated as
candidates for rule-based assistance.

                                                     117


---

                                  COMANDER AND STAFF INPUT
                The command estimate sequence of events as
outlined in ST 100-9 contains an entity called commander
and staff input. As depicted, it only interacts with the
processes of "Develop Courses of Action" and "Analyze
Courses of Action.' with the caveat that this entity
should update information, provide the results of
reconnaissance, and feed corrected data into the system."
This element has not been addressed specifically in the
decomposition of the command estimate because this action
of input by the commander and staff occurs in every
process as information is updated, expanded, and
corrected.

                                                    SUMMARY
               This structured decomposition of the command
estimate is intended to show how information flows through
the system and to identify those elements that can be
enhanced by the use of rule-based expert systems. Table 2
encapsulates these findings and denotes how those
processes that would benefit from automated assistance.
               Of special interest is the frequency of which
some of the information entities appear when the command

                                                     118


---

estimate was decomposed. The importance of these
information entities can be expressed as the number of
times that they are used throughout the entire process.
The most frequently appearing information entity was the
commander's intent. The commander's intent is the common
thread that connects all the sub-processes of the command
estimate. It is the image of what the commander wants at
the conclusion of the operation. This analysis indicates
that it is the single most important information element
of the command estimate.

               The most frequently appearing entities of
information are:

                  1. Commander's intent.
               2. Time line and synchronization matrix.
               3. Mission statements (See note 1).
               4. Task organization (See note 1).
               5. Critical events (See note 1).
               6. G2/IPB (See notes 1 and 2).
               7. Warning orders.
Note 1: The mission statement, G2/IPB, task
organization, and critical events appeared an equal
number of times as separate information process entities
within the decomposition of the command estimate. The
priority ranking above is a subjective determination of
which entity manages the most critical information.
Note 2: The G2/IPB is integral to tactical

                                                     119


---

implementations of the command estimate. However, it is a
distinct process that should be considered separately.
The command estimate is functionally decomposed in
appendix A.

                                                     120


---

             CHAP  T R S SUMMARY

This table is a recapitulation of the information flows
analyzed in the command estimate. The following key is used
to explain the type of systeri indicated:
Norm Normalization of an expression or graphic to
doctrinally correct form.
Synch Synchronization of action, equipment, or event to a
common time reference.
DM Data Maintenance. Data is maintained in a store or data
base. The information is constantly updated as changes occur.
Con Consultancy to ensure that doctrine and AirLand Battle
tenets are adhered to.
CMP Computational procedures in which the rule-based system
determines that a mathematical computation is necessary. It
will continually update these computations as changes occur.
PO Prepare output of warning orders, OPORDs, FRAGOs, and
related graphics.

DFD PROCESS        DFD RULE- RELATED DFD       TYPE OF
                             BASED              SYSTEM
                             (Y/N)

MISSION            1.0                         Norm

CDR's Intent            Y    4.0,5.0,6.3,

                                  7.4,8.0,9.0

CDR's Guidance          Y    6.2,9.0           Norm

Anticipated Acts        N                      DM

Concerns                N                      DM

Mission                 Y    6.0,6.2,8.0,9.0 Norm

FACTS              2.0       6.0,7.1           DM
   GI/SI
   G2/$2                Y
   G31S3
   G4/$4                Y

                        Y

                        Y

ASSUMPTIONS        3.0       6.0,7.2           DM

Gi/SI                   Y

G2/S2                   Y

G3/S3                   Y

G4/$4                   Y

MISSION ANALYSIS   4.0

CDR's Intent            Y    1.0,5.0,6.3,      Norm
                                                DM
                                  7.4,8.0,9.0

Identify Tasks          Y    4.7,8.0,7.4

                        TABLE 2.

                        121


---

                        CHAP  TER     6 SUMMARY

    DFD PROCESS                    (Continued)

DETERMINE TIME                DFD RULE- RELATED DFD      TYPE OF
    Time Line                           BASED              SYSTEM
                                        (Y/N)
CONSTRAINTS                                                Synch
                              4.1
RISK                                                         DM
                                   Y    5.0,6.0,7.4,         DM
RESTRICTIONS                                                 DM
                                        7.5,9.0            Norm
UNDERSTAND HIGHER
INTENT                        4.2  Y                         DM
                                                           Norm
DETERMINE IF                  4.3  Y    5.0,7.4
FORCES CAN                                                   DM
ACCOMPLISH MSN                4.4  Y                       Norm

    Task Org                  4.5  Y    1.0,4.0,5.0,       Norm
                                                             DM
RESTATED MISSION                        6.3,7.4,8.0
    Essential Tasks                                        Synch
    Warning Order             4.6
                                                           Norm
PLANNING GUIDANCE                  Y    6.0,6.3,7.2,9.0
    CDR's Intent                                             DM
                              4.7  Y    5.0
    Risk                                                 Perform
    Time Line                      Y    4.0,6.0,7.4         DM
                                                            DM
    Specific COAs                  Y    5.0,8.0             DM
    Warning Order
                              5.0                         Synch
RESTATE MISSION                                           Norm
    Essential Tasks                Y    1.0,4.0,6.3,

DETERMINE POSSIBLE                      7.4,8.0,9.0
    IPB
   Facts & Assump                  Y    4.0,4.3,7.4
    Task Org
    Essential Tasks                Y    4.1,6.0,7.4,
   Time Line
                                        7.5,9.0
   Mission
                                   N

                                   Y    4.7,8.0

                              4.7

                                   Y    4.0,6.0,7.4

                              6.0

                                   Y    2.0,3.0,7.1,7.5

                                   Y    2.0,3.0,7.1,7.2

                                   Y    4.6,6.3,7.2,9.0

                                   Y    4.0,4.7,7.4

                                   Y    4.1,5.0,7.4,

                                        7.5,9.0

                                   Y    1.0,6.2,8.0,9.0

                              TABLE 2 (Continued).

                                   122


---

                     CHAPT  ER   6 SUMMARY

   DFD PROCESS                   (Continued)

ANALYZE CBT POWER           DFD RULE- RELATED DFD      TYPE OF
                                      BASED              SYSTEM
ARRAY INIT FORCES                     (Y/N)
    Mission                                             CMP
   CDR's Guidance           6.1  Y

DEVELOP SCHEME OF           6.2
MANEUVER
                                 Y    1.0,6.0,8.0,9.0 Norm
    Battlefield
       Framework                 Y    1.0,9.0          Norm

    CDR's Intent            6.3  N

    Task Org                     Y                     Con

ALLOCATE HQs                     Y    1.0,4.0,5.0,     Norm

COA STATEMENTS                        7.4,8.0,9.0

G3/S3 BRIEF COAs                 Y    4.6,6.0,7.3,9.0  DM

DETERMINE COA TO            6.4  N
WAR GAME
                            6.5  Y                     Norm
    IPB
    G3 Input                7.0  N

VALIDATE ASSUMP.            7.1  N

ADDRESS BOS                      Y    2.0,3.0,6.0,7.5 Perform
   Task Org
                                 Y    2.0,3.0          DM
PRIORITIZE
CRITICAL TASKS              7.2  Y    3.0              DM

    Essential Tasks         7.3
    CDR's Intent
                                 Y    4.6,6.0,9.0      DM
    Time Line
                            7.4
    Risk
    Synch Matrix                 Y    4.0,4.7,6.0       DM
                                                       Norm
                                 Y    1.0,4.0,5.0,
                                                       Synch
                                      6.3,8.0,9.0
                                                         DM
                                 Y    4.1,5.0,6.0,     Synch

                                      7.5,9.0

                                 Y    4.3,5.0

                                 Y    4.1,5.0,6.0,

                                      7.5,9.0

                            TABLE 2 (Continued).

                                 123


---

                      CHAPTER            6 SUMMARY
                                    (Continued)
   DFD PROCESS
                               DFD RULE- RELATED DFD      TYPE OF
WAR GAME                                BASED              SYSTEM
   G2/IPB                                (YIN)
    Synch Matrix                                             DM
                               7.5                         Synch
   Critical Events
DETERMINE BEST COA                  Y    2.0,3.0,6.0,7.1     DM

DECISION                            Y    4.1,5.0,6.0,      Norm
   Mission                                                 Norm
    CDR's Intent                         7.4,9.0           Norm
   Warning Order
                                    Y    4.0,4.7,6.0,7.4   Synch
PREPARE PLANS                                              Norm
AND ORDERS                     7.6  N                      Norm
                                                           Norm
    Synch Matrix               8.0
                                                             DM
    Mission                         Y    1.0,6.0,6.2,9.0     DM
   CDR's In*.ent                                             PO
                                    Y    1.0,4.0,5.0,
    CDR'v Guidance
   Task Org                              6.3,7.4,9.0
    Critical Events
                                    Y    4.7,5.0,8.0
    FRAGO/OPORD
                               9.0

                                    Y    4.1,5.0,6.0,

                                         7.4,7.5

                                    Y    1.0,6.0,6.2,

                                         8.0,9.0

                                    Y    1.0,4.0,5.0,

                                         6.3,7.4,8.0

                                    Y    1.0,6.2

                                    Y    4.6,6.0,6.3,7.3

                                    Y    4.0,4.7,6.0,

                                         7.4,7.5

                                    Y

                               TABLE 2 (Continued).

                                    124


---

                     CHAPTER 6 END NOTES

      'US Army, ST 100-9, The Command Estimate, (1989):

1-4.

      2 ST 100-9 (1989):  2-1.

      3 Ibid:  2-7.

      4ST 100-9 (1989): 2-1.

      eIbid: 7-1.

            OUS Army, FM 101-5, Staff Organization and Operation
(1984): E-20.

            7 ST 100-9 (1989) : 2-3.

      8lbid: 2-6.

      Ibid: 2-7.

      10Ibid: 2-8.

              "Rand, *Understanding Commanders' Information
Needs.' (1989): 15.

      12ST 100-9 (1989): 3-1
      1 3 Ibid (1989): 3-2.
      "4 Ibid (1989): 3-1.
      1 eIbid (1989) : 3-4.

      IsIbid   (1989):  3-5.
      "Ibid    (1989):  3-6.

              "Interview, LTC John A. Strand, 6 Feb 1990, Future
Battle Lab, Fort Leavenworth, KS.

            '*US Army, FM 100-5, Operations (1986): 34.
             2 0 ST 100-9 (1989): 3-7.
             2 1 Ibid (1989): 4-1.

                              125


---

2 2 Ibid  (1989):   4-1.
2 3 Ibid  (1989):   5-2.
"4 Ibid   (1989):   5-2.
201Sbid   (1989) :  1-4.

                    1.26


---

                                                      CHAPTER 7

                              CONCLUSIONS AND RECOMMENDATIONS

               The command estimate is depicted as a cleanly
defined flow diagram in ST 100-9, The Command Estimate'.
This diagram shows discrete processes that isolate and
perform specific functions in a linear manner. However,
when the functional decomposition of this process is
analyzed, the command estimate is more aptly described as
a three dimensional tinker toy structure. Although
specific functions are performed by discrete processes,
the information flowing into and out of these processes is
dynamically and simultaneously linked to other processes.
The flow of this information is not linear, but, is
instead, recursive.

                In the tinker toy model analogy, the processes are
the wooden spools while the information flows are the
shafts. Data stores and sinks are represented by other
shapes that are connected to various wooden spools by
shafts. Multiple shafts connect the spools forming a
complex polyhedron. This sophisticated structure is more
representative of the command estimate during execution

                                                     127


---

where the amount and timeliness of information necessary
to make decisions is nearly unmanageable when using
current manual and automated systems.

                It is important that the Army pursue advanced
technology to improve the command estimate. Automation
must be exploited to manage the vast amounts of
information generated in tactical situations. In the
civilian sector, executive information systems (EIS) have
been implemented to allow executive decision makers to
access a broad spectrum of data, perform rapid analysis
which produces intelligent information, and then make
informed decisions. The introduction of rule-based expert
systems within EIS allows executives to make decisions
with the best current information while avoiding the
common fault of providing too much detailed information.
These same capabilities have a demand in the military
environment.

                                               CONCLUSIONS
               The use of rule-based systems has a viable
function within the command estimate. As described in
this study, the command estimate is a series of
interrelated sub-systems. The creation of a rule-based
environment for the command estimate should follow a

                                                     128


---

modular architecture and be comprised of rule-based sub-
systems that assist the commander and staff in the

execution of the command estimate.

Development of rule-based systems to assist in

the performance of the command estimate should accomplish

the following functions:
               1. Normalization.

2. Synchronization.
3. Data maintenance.

4. Consultancy.

5. Computation.
6. Preparation and dissemination of orders and

graphics.

               Normalization is the process of parsing an
expression or statement into its cimponent words and
phrases and making them adhere to an established

vocabulary. This ensures that the expressions will have a
precise and understood meaning. In the command estimate

context, statements must conform to terms in FM 101-5-1.z

This normalization to the standard terminology will ensure
that a rtatement will mean exactly what it says. An

example is the nuances between the phrases, *Secure the

objective. and, "Seize the objective.  FM 101-5-1
defines secure as:

           To gain possession of a position or terrain

           feature, with or without force, and to
           deploy in a manner which prevents its
           destruction or loss to enemy action. 3

                                  129


---

               Seize is defined as: 4  *To clear a designated area
and obtain control of it.*

The fine line between the two being that in a

secure mission, forces do not have to establish a physical

presence on the the position or terrain. In the seize

mission, forces have to occupy the designated area. This

distinction is minor but can have a tremendous effect on

the unit that has to accomplish the mission.

Unfortunately, these two terms are often used

interchangeably by military planners and operators. The

common military vernacular is rife with such terms that

have similar, but vastly different meanings. A rule-based

system that normalizes statements either being received or

being transmitted will ensure unity of meaning.

The process of normalization is also applicable to

diagrams, sketches, and other pictorial representations of

military operations. It is just as important that these

graphic expressions conform to correct doctrine as written

media. More important, if a sketch is used to complement

a written communication, it must convey the same

information as the written media. A rule-based system for

normalization can accomplish this.

In military operations, timing is everything. The

synchronization of combat, combat support, and combat

service support resources at the critical place and time

is necessary for success. A rule-based system can excel

130


---

at the process of assisting in the synchronization and
employment of battlefield operating systems (BOS) due to
the ability to track and analyze multiple variables. If,
in a course of action, the time for some event is adjusted
for some reason, all other synchronization times can be
adjusted automatically. In addition to time
synchronization, a rule-based system can assist in the
coordination of resources at critical locatio:ns. An
example is a river crossing where a wide variety of
specialized engineer equipment is necessary to construct,
then maintain a bridge. The rule-based system could
assist commanders and staffs by producing a detailed
synchronization matrix of the necessary assets and actions
keyed to specific times or other events. The result is a
tool to better and more efficiently manage time.

               Data maintenance is a method of tracking statuses
of units, personnel, equipment, etc. After a specific
entity or item of information is captured, it can be
continually monitored for changes. Several methods could
be used to trigger this function to include time periods,
exception criteria, or demand polling.

              .Time period data maintenance is a case in which
the status of the item is reported at set periods of time.
Exception criteria is when the item exceeds specified
tolerances. Demand polling is when the status of the item
is requested.

                                                     131


---

               Much time and effort of commanders and staffs is
spent in maintaining time sensitive data. Often, current
information is the basis for critical decisions. A rule-
based system can assist in maintaining the most reliable,
timely, and correct data. Better decisions are made if
the information on which they are made is maintained to a
higher quality.

               Consultancy is an area where the rule-based system
can act as the commander's personal consultant on matters
of doctrine or military science. It is here that checks
can be made to ensure that all of the battlefield
operating systems have been addressed in a particular
course of action or that the doctrinal tenets of AirLand
Battle have been included in the plan. The rule-based
system can ensure that the staff estimate is complete and
addresses all necessary aspects.

               Several areas of the command estimate could be
assisted with automated resources to provide computational
power. These include forecasting logistical requirements,
air and road movement tables, ammunition expenditures,
personnel projections, etc. A rule-based system to
perform computational routines could determine when to
recalculate existing data based on changing parameters of
the tactical situation as a whole. Assisting this type of
process with rule-based expert systems will consistently
result in more accurate results.

                                                     132


---

               Preparing output is necessary for the production
of the warning order, OPORD, and FRAGO. This is a fairly
straightforward application of a rule-based system that
places information into a prescribed format such as a five
paragraph operations order and then distributes it to a
list of addressees. In addition to creating the OPORD or
FRAGO, a rule-based system can also determine which
addressees get the output. A final feature of a rule-
based output system is that it can verify whether or not
all intended recipients actually receive the information.
If the information is not received, the rule-based system
can try alternate communication means to deliver the
information and keep the commander and staff informed of
the status.

                                           RECOMMENDATIONS
               The analysis of examining the command estimate
from aspects of both formal observations and a systems
analysis method of functional decomposition has revealed
many areas that can be assisted by the implementation of
rule-based systems. From the general level, each defined
process of the command estimate is a candidate for a rule-
based system to act as a consultant to ensure congruency
to doctrine or procedure. However, underlying these rule-
based consultant systems would be specific rule-based
systems that focus on more specialized areas or

                                                     133


---

procedures. This *system* of rule-based expert Systems
would capitalize on modern technology to give the
commander and staff a more powerful and accurate command
estimate.

               Table 3 enumerates the types of rule-based
systems that can be developed for each sub-system of the
command estimate. This table divides the command estimate
into its traditional sub-systems and generalizes the rule-
based expert system scheme required to assist the
commander and staff.

                                                     134


---

               RECOMMENDED
RUL 1E-BASED                     SYSTEMS

COMMAND ESTIMATE                        TYPE OF
       PROCESS                   RULE-BASED SYSTEM

Mission                     Consultant
Facts and Assumptions       Normalize Mission

                                Statement
                            Data Maintenance

                            Consultant
                            Data Maintenance
                            Computation

Mission Analysis            Consultant
                            Synchronize BOS

                            Normalize Mission
                                Statement

                            Prepare Warning Order

Commander's Guidance        Consultant
                            Normalize CDR's
                                             Order
                                Guidance
                            Prepare Warning

Develop Courses             Consultant
of Action                   Synchronize BOS
                            Prepare COA Statement

Commander and               Consultant
Staff Input                 Synchronize BOS

Analyze Courses             Consultant
of Action                   Synchronize BOS
                            War Game Simulation
Recommendation
                            Consultant

                            Synchornize

Decision                    Consultant

Warning Order               Normalize Orders and
OPORD/FRAGO                     Graphics

                            Prepare Orders and
                                Graphics

                       TABLE 3.

                       135


---

               PRIORITY OF RULE-BASED SYSTEM IMPLEMENTATION
               The functional decomposition of the command

estimate and the IPB identified key elements that either
occurred numerous times or had a significant impact in
more than one sub-system. Additionally, the examination
of observations made of the command estimate in action
revealed several areas that are candidates for enhancement
with automated systems. The analysis and comparison using
these methods provided complementary findings that rule-
based expert systems could make a significant contribution
in the execution of the command estimate. The order of
priority in which rule-based expert systems should be
implemented within the command estimate is:

                1. Commander's intent.
                2. Time line and synchronization matrix.
                3. Mission statements.
                4. G2/S2 IPB.
                5. Task organization.
                6. Critical events.
               7. Warning orders.

                                            COMMANDER'S INTENT
               The commander's intent is the single most often
recurring entity of information within the command
estimate. This intent is the commander's mental image of

                                                     136


---

the battlefield; it drives the entire planning and
execution process. The staff that understands what the
commander envisions on the battlefield will have a greater
chance of creating an integrated plan to accomplish the
mission. This process is well suited for enhancement by
rule-based expert systems. The focus of this effort would
be to normalize the verbal and graphic expression to
doctrinally correct terms and graphics.

                                                SYNCHRONIZATION
               The time line or synchronization matrix is the
second most often occurring item of information. This is
in line with the commander's intent because to achieve the
mission, the resources of the battlefield must be
synchronized in time and space to bring critical forces to
bear on the enemy. This is an ideal area for the
implementation of rule-based systems to assist the
commander and staff in identifying critical times and
managing the synchronization of combat resources. This
system would assist in the synchronization of battlefield
operating systems (BOS) in time and space to bring all
critical resources to action when and where they are
needed. It would also act as a consultant for the various
systems to ensure that all resources are addressed and
planned for to leverage their capabilities.

                                                     137


---

                                       MISSION STATEMENTS
               Normalizing the mission is a prime candidate for
assistance with a rule-based system. Although very
similar to the commander's intent, it is distinct and
separate. The purpose of a rule-based system to assist in
mission statements is normalization and dissemination to
appropriate addressees. It would also ensure that overlay
graphics are consistent in military verbiage and display
doctrinally correct symbols.

                                                 G2/S2 IPB
               The IPB is not depicted by ST 100-9 as a primary
component of the command estimate. However, it is
inconceivable that any tactical operation could be
conducted without a thorough IPB. Therefore, it is
recommended that the IPB be included in any rule-based
assistance focused on the command estimate. In this
light, the IPB is a process that rule-based systems can
perform with relative ease due to the modularity of its
functions and the nature of the information that flows
into and out of the process. The primary focus of rule-
based systems for the IPB will be that of consultancy.
This is due to the complex knowledge of enemy equipment
and doctrine required as well as a depth of knowledge of
friendly force structures and capabilities. Rule-based
sub-systems can perform computational processes such as
force ratio calculations, weather forecasting, and terrain

                                                     138


---

analysis. Data maintenance functions can be designed to
track and maintain data bases such as enemy order of
battle, alerting the staff in the case of information
concerning certain types of equipment or activities are
processed, and trend analysis of current situations.

                                         TASK ORGANIZATION
               The development and tracking of task
organizations is a rule-based task that would contribute
          c.u the commander's planning process. Data
maintenance is an obvious role of such a system. In
addition to tracking the units allocated for an operation,
the current status of these units in a wide range of
specified areas could be maintained. The commander would
automatically be alerted if the sensitivity levels of pre-
set thresholds were violated. This feature would provide
a measurable improvement over the present method of
maintaining current statistics on units. A consultant
rule-based system can perform the task of assisting the
commander and staff with employing allocated forces within
doctrinal parameters. This would overcome training
shortfalls in cases where non-standard units are allocated
as resources such as an Army division receiving control of
a Marine Corps force. The consultant would draw upon
doctrinal rules to assist the commander in employing these
non-standard resources to the maximum benefit.

                                                    139


---

                                           CRITICAL EVENTS
               Critical events are either the essential tasks or
the key actions that influence what occurs on the
battlefield. A rule-based system would perform data
maintenance and insure that information concerning these
events is properly disseminated. Working in concert with
other expert systems, it would overwatch the process of
synchronizing BOS with anticipated or critical enemy
actions.

                                           WARNING ORDERS
               The preparation of orders is one area that rule-
based expert systems will noticeably save effort and
reduce confusion. Much of the information contained in
formatted orders is a recapitulation of information on
hand. The process of updating this and including it in
both formal and informal formats takes time and presents
opportunities for conveying erroneous information. A
rule-based expert system assisting the command estimate
process will reduce the time it takes to prepare and issue
orders and can track missing items of information for
later filing. This system will also control the
distribution of the orders.

                       ATCCS AND RULE-BASED EXPERT SYSTEMS
               The implementation of rule-based systems within
the command estimate should proceed in increments as in
the above sequence. The hardware platforms that are being

                                                     140


---

fielded to support ATCCS can be used to operate rule-based
systems. This implementation effort should be incremental
and coordinated in that the each sub-systems bc .r
individually before it is integrated with other sub-
systems.

                 The measure of success of rule-based systems is
that they assist in the execution of the command estimate,
not interfere or be an impediment with any other ATCCS
system, and be totally transparent to the user in the
field. The main concern is that the rule-based expert
systems are to assist the commander and staff in the
execution of the command estimate, not replace them.

                 The evolving ATCCS is the environment on which to
develop rule-based expert systems for the command estimate
process.

                                                         141


---

CHAPTER 7 END) NOTES

'US Army, ST 100-9, The Command Estimate-, (1989):

              ,J3 Army, FM CK-i  Operational Terms and Symbols
(1985).

3 Ibid (1985): 1-64.

4 lbid (1985): 1-65.

                                 142


---

APPENDIX A


---

                                                 APPENDIX A

             ANALYTICAL DECOMPOSITION OF THE INTELLIGENCE
                     PREPARATION OF THE BATTLEFIELD (IPB)

                 The intelligence preparation of the battlefield
(IPB) is the methodology used by the G2/S2 to analyze the
enemy, terrain, and weather in a specific geographical
area. The IPB integrates known enemy doctrine with the
nonstandard conditions of weather, terrain, the mission,
and the specific battlefield area. The product of this
process is an intelligence estimate and an analysis of
the battlefield area that will indicate probable enemy
courses of action and intentions.'

                 Figure 13 depicts the IPB. It is a cyclical five-
function process that has the following components:

                  1. Battlefield area evaluation.
                2. Terrain analysis.
                 3. Weather analysis.
                 4. Threat evaluation.
                 5. Threat integration.
                 The IPB is closely associated with the command
estimate but is not an integral component. While the
command estimate represents the military decision making

                                                          144


---

THE IPB PROCESS

BATTLEFIELD AREA
     EVALUATION

_________________

TERRAIN ANALYSIS

WEATHER ANALYSIS

     *_______

THREAT EVALUATION

THREAT INTEGRATION

                            Figure 13.

                         145


---

model and can be used in any situation, the IPB is a
G2/S2 function that focuses on a known enemy military
force, a specific geographic area, and the effects of
terrain on military capabilities.

                The purpose of this appendix is to examine the
IPB with respect to how it functions with the command
estimate and to determine if it should be assisted with
rule-based expert systems.

                          BATTLEFIELD AREA EVALUATION (BAE)
                Whila the IPB is a continuous process, the
interface to the command estimate is the process of
mission planning. The trigger for the IPB is the
mission. The mission establishes the WHO, WHAT, WHERE,
WHEN, and WHY. Figure 14, BAE Data Flow Diagram (DFD)
depicts the information that flows into the BAE process
and what it becomes as the result of the evaluation.
                The mission statement was displayed as an output
of the command estimate in DFD 1.0, figure 4.
Additionally, several data stores from the command
estimate help to shape the process of determining the
area of operations. These inputs are the commander's
guidance (DFD 1.0, figure 4), the geographic WHERE (DFD
1.0), facts (DFD 2.0, figure 5), and assumptions (DFD
3.0, figure 5). These data stores are generated or
maintained by the G3/S3.

                                                     146


---

               IPB BATTLEFIELD
              AREA EVALUATION

Mission                COR's Guidance*
                                   Where*
                                              G3 Facts and Assumptions-

                Determine                                Rear*

                  Area of
              Operations*

                                                  Deep*

                                      Close*

                                                         CDR's Guidance

                                               interest
                                           14

              Height*

WiRule-Based                                                    BA

                       Depth*

•Rule-Based                    Timet                            S AE

System                                Figure 14.

                               147


---

                 The first process is to determine the area of
operations. The area of operations is roughly defined by
the G3/S3 and is the specific zone or area the commander
is responsible for. 2 DFD A in figure 14. shows this
determination is stored as the definition of the close,
deep, and rear areas. Although the operations in these
areas will be conducted simultaneously, the IPB is
conducted in each process in a slightly different
manner.3 Hence, each is stored as a separate entity that
becomes a subset of the WHERE in the mission data store.

                 The second process of the BAE is to determine the
area of interest. This area is jointly determined by the
G2/S2 and the G3/S3 based largely on the commander's
guidance. This is a larger area that includes enemy
activity which might effect friendly forces during the
operation. 4 The boundaries of this area must be
synthesized from a knowledge of enemy capabilities,
friendly vulnerabilities, and the military aspects of
terrain. DFD B, figure 14, depicts this process.
Outputs are data stores that contain the dimensions of
width, height, depth, and time that delimit the area of
interest. Like the battlefield parameters generated in
DFD A, the dimensions of width, height, depth, and time
become refined subsets of the mission data store.

               The role for rule-based expert systems in this
process is two-fold. First, all the information inputs

                                                    148


---

have been recommended for assistance using rule-based
systems. Although these inputs are initially generated
in the command estimate as shown in DFDs 1.0, 2.0, or
3.0, they are continuously updated as information
changes. A rule-based system would excel at the data
maintenance task to insure decisions made based on the
IPB are correct with respect to timely and correct
information. Second, the process of performing the BAE
is a candidate for assistance by a rule-based system
using the inputs of mission, capabilities of enemy
forces, vuinerabilities of friendly forces, and the
commander's guidance. The BAE process is continuous. A
rule-based expert system in a consultant role would
update this evaluation as the situation changed.

                                              TERRAIN ANALYSIS
                 Understanding the limitations and opportunities
of terrain is a fundamental military skill that varies
among levels of command. Terrain is analyzed at each
echelon. However, regardless of what echelon is
involved, the unit's mission is the primary concern of
the analysis. The depth, or fidelity, of the process is
driven by the echelon of the staff performing the
analysis. Lower tactical echelons conduct a much greater
examination of a small area taking into consideration the

                                                          149


---

military aspects of terrain. At the operational level,
additional factors are considered such as population
density, transportation facilities, and physical
resources.5

                The initial process in terrain analysis is the
identification of gaps in terrain data. Figure 15
depicts the decomposition of this terrain analysis
process. The mission provides the WHERE for the
operation. This is the same data store that was
generated in the mission process of the command estimate
(DFD 1.0, figure 4), and appears multiple times during
later phases. In the IPB, it is a refined WHERE of DFD
A. This item of information specifies requirements for
maps, intelligence efforts, terrain studies, and detailed
reconnaissance. A data store of facts can provide some
of this data. This is the data store that was initially
generated in DFD 2.0, figure 5. The items that are not
identified as being available create a data store for
gaps in the terrain data. This data store is a
refinement to the facts data store.

                It would be the function of a rule-based system
to identify the information requirements from the mission
statement, determine what information is available,
determine what information is needed, and take steps to
acquire the missing information. An example would be
that the rule-based system would receive the mission
statement and determine what maps are needed for the

                                                     150


---

TERRAIN ANALYSIS

            Mission'

F actheEfct*nCA                                                  Syrltem
                                                              Terrai
                              terraindata

                                                     FCu~ 15


---

operation. It would then check the data store of facts
for map status. In case the maps were not available, it
would requisition them, or initiate map production from
computer maintained digitized terrain data. In any
event, it would alert the appropriate staff sections that
a potential problem exists and what steps have been taken
to correct it.

               The next process is the development of overlays
to graphically depict relevant factors of the area.
These overlays can be created to portray any type of
information based on availability of information and the
desire of the commander and staff. This process is
labeled DFD D. It has two primary overlays as outputs:

                1. Terrain factors which reflect important
military factors of specific battlefield areas. The
analysis of the deep area may focus on transportation
facilities, the examination of the close area may look at
vegetation and streams, the areas of concern in the deep
area may be possible airborne or air assault zones.

               2. The combined obstacle overlay which depicts
obstacles to movement. This is typified as go
(favorable), slow-go (marginal), and no-go (unfavorable)
terrain.

                 These overlays give the commander and staff a
graphic picture of where forces are expected to operate
on the battlefield. The primary source of the base-line

                                                     152


---

data for this analysis is standard topographic data
provided by the Defense Mapping Agency.

               Although man is much better at pattern
recognition tasks such as map-based terrain analysis than
current artificial intelligence technology, this process
could be greatly assisted with rule-based systems.' The
use of digitized terrain data instead of standard
topographic maps would leverage the ability of a
computer-based system to perform this task. A rule-
based system could normalize graphics to doctrinal
standards and supervise its dissemination to appropriate
agencies.

               The analysis of terrain and weather are separate
steps but are done concurrently.' DFD E, figure 15, is
the process of integrating weather into the analysis of
terrain. This is a recursive procedure that must get
information from the process of analyzing the weather
performed in DFD H.1 The integration of weather
generates two outputs with the first being an enhancement
to tha combined obstacle overlay produced in DFD D, and
the second being a data store containing a summary of the
effects that weather may have on courses of action.

               The integration of weather is a superb candidate
for assistance with rule-based systems. Essentially.
this process is largely a data management function that
takes information provided by sensors and applies it to
specific geographical areas. The data store is then

                                                     153


---

        TERRAIN ANALYSIS

                             (Continued)
     Width, Height,

          AAnalyse
     Culeseas
De*
     DepystRer*Rer

     154


---

maintained for specific operations in areas on which the
weather will have an measurable effect.

               The analysis of the close, deep, and rear areas
is a convoluted procedure. DFD F in figures 15 and 16
depicts the starting point for this process. The data
stores of the battlefield parameters of width, height,
depth, and time developed in DFD B are inputs into this
transformation. Figure 16 details three parallel
transformations:

                1. Identification of deep targets for
intelligence collection and interdiction. This
transformation is given the input of the deep area data
store as it was defined in DFD A. These targets are
identified as terrain features such as bridges, mountain
passes, forested areas, etc. Initially, these are
designated named areas of interest (NAI) and will be
designated as targeted areas of interest (TAI) as threat
forces are integrated into the analysis. These produce
two data stores called NAI and TAI. Avenues of approach
in the deep area are primary candidates for designation
as NAIs and TAIs.

               2. Identification of avenues of approach (DFD
F.2) for close operations. The close area was defined in
DFD A, figure 14. The combined obstacle overlay produced
in DFD D, figure 15, defines areas through which forces
can move. Avenues of approach can be identified using

                                                    155


---

rules developed from doctrinal attack frontages. The use
of these rules results in identification of both friendly
and enemy avenues of approach.9 These avenues create a
data store that will be used in developing and analyzing
courses of action in the command estimate.

                 3. Identification of targets in the rear area of
operations (DFD F.3). The rear area was designated in
DFD A, figure 14. The targets in the friendly rear area
provide insight into options available to the enemy. The
output of this process is a data store of rear area
targets. This will be used with the process of threat
evaluation to form the basis of the intelligence
estimate.

                 The analysis of close, deep, and rear areas is a
candidate for rule-based systems. A caveat is that
machine readable terrain data must be available. The
process of identification of avenues of approach is a
prime example of using doctrinal rules to assist the
military decision-making process.

                 Analyzing the militc y aspects of terrain is the
final element in the terrain analysis process. DFD G,
figure 16, depicts this procedure. This is done from
both a friendly and enemy perspective to determine merits
and problems. Primary inputs are the terrain factors
overlay and any information gleaned from a terrain
reconnaissance. Additional information such as aerial
imagery may be used. The primary output is a data store

                                                           156


---

that contains information on the terrain effects on
avenues of approach for the various courses of action.

                 This analysis process can be greatly assisted
with a rule-based expert system. Military aspects of
terrain can be evaluated with a quantified set of rules.
The information from the terrain factors overlays can be
processed by the rule-based system. Additionally,
information from any terrain reconnaissance or
surveillance data can be processed by the rule-based
system.

                                             WEATHER ANALYSIS
                 Weather analysis is the process to determine the
effects of weather on both enemy and friendly courses of
action. Of concern are those weather effects that will
act as limitations or enhancements on personnel,
equipment, or the military operation. Figure 17 depicts
this process which is initiated by the inflow of
information defining the battlefield. These are the BAE
products created in DFDs A and B, figure 14, which
delimit the area of operation and the area of interest.
The mission is a data store that defines the WHAT and the
WHEN of the operation. A large data store of facts will
provide two large categories of weather information:1 0
                  1. Traditional weather products such as
climatology studies, light-data, average temperatures,
average precipitation, seasonal cloud cover, etc.

                                                          157


---

WEATHER ANALYSIS

BAE____

                       Facts*

                       Weatahee*

            WeWeather

*Rule-basd                                  Analysis
  System
                         Figure 17.
                       158


---

               2. Weather studies and forecasts on likely
seasonal conditions as they will effect various courses
of action.

               These inputs are transformed by the analysis
process and produce a data store of the effects of
weather on the courses of action, and overlays of weather
effects. The overlays may depict significant effects to
include fog, cloud cover, rain, snow depth, ice
thickness, wind direction, wind speed, and any other
factor that may have a measurable effect on the military
operation." Another output is the process of
integrating weather into the terrain analysis. This was
depicted as DFD E in figure 15.

               The entire process of weather analysis is a
candidate for assistance with rule-based systems. The
inputs have been previously recommended for rule-based
systems. The actual process of analyzing the weather is
the use of scientific meteorological rules on current
data and historical records. The outputs are a data
store and the production and dissemination of overlays.
Both of these outputs can be managed by an automated
system. A rule-based system is well suited for
normalizing overlay graphics to doctrinal standards and
assisting in the dissemination of the product.

                                                     159


---

                                           THREAT EVALUATION
               Threat evaluation is the detailed examination of
the enemy forces, composition, weapons, equipment,
organization, and supporting battlefield functional
systems. This process is to determine the enemy
capabilities and how they operate as prescribed by their
doctrine."2 The mission drives the threat evaluation
process. It defines the basic environment that the
forces must operate in. DFD I in figure 18 details this
process.
               The primary inputs into the threat evaluation
process are facts, assumptions, rear area targets, and
avenues of approach. Facts and assumptions are data
stores that were generated in DFDs 2.0 and 3.0 in figure
5 of the command estimate. These data stores are
related. Assumptions are used in lieu of unknown
facts. Once facts become known, they replace these
assumptions. The data stores of rear area targets and
avenues of approach were generated in the terrain
analysis process, DFDs F.2 and F.3, figure 16.
               Facts often include information on enemy
disposition, known locations, composition, strength,
committed forces, and reserves. 's
               Assumptions are made of information that is
missing or incomplete.

                                                     160


---

          THREAT EVALUATION

MIssiofl  F3cts*  Assumptions*                      _____

            TThreat                           App1
           Evaluataoabilities*s

                    Enesmy

                                  Figure 1o.

          Battle


---

         The use of rule-based systems in support of the

mission statement and management of data stores

containing facts and assumptions have been dlscussed in

detail. The bulk of this effort would be normalization

of the mission statement to doctrinal terms, data

maintenance, dissemination of facts and assumptions, and

assistance in harvesting factual information from reports

and messages. The data stores of rear area targets and

avenues of approach will be dynamic and could be assisted

by a rule-based system performing data maintenance.

         An output of this process is a data store

containing the enemy order of battle. This will be used

extensively by the G2/S2 to make assessments of enemy

capabilhties and intentions. This data store can be

maintaired and disseminated by a rule-based system. Part

of the .iaintenance function would be to filter incoming

informa- ion to track units identified on the order of

battle.

         The next process is to apply doctrinal templates.

These t mplates will produce 6raphic  u:strations or

overlay., of enemy force structures, deployments, and

capabilities that provide the commander a clear picture

of the reality of the battlefield. These templates will

provide the G3/S3 with notional enemy forces with which

he can conduct the war game effort. This process is

depicted in DFD J, figure 18. Doctrinal templates

         162


---

convert enemy order of battle information into a graphic
overlay presentation. These are models of how the enemy
should look according to his doctrine and training if
weather, terrain, and combat losses were not considered.
The ultimate purpose of these templates is to provide a
basis for integrating enemy doctrine with terrain and
weather information. It is important that these overlays
adhere to correct use of symbols to insure that the
information conveyed is understood by all." 4

                 The role of a rule-based system in the threat
evaluation process would be to take rules of enemy war
fighting doctrine and array the enemy forces from the
order of battle as they would notionally be arrayed for
combat operations. Doctrinal norms would be the source
of the rule-base.

                                           THREAT INTEGRATION
               The climax of the IPB is the process of
integrating enemy doctrine with terrain and weather data.
The objective of this process is to determine how terrain
and weather will effect how the enemy may fight. Threat
integration is composed of several sequential steps in
which templates are produced as outputs to assist in
assessing how the enemy may act. These outputs will
include the situation, event, and decision support
templates.15

                                                     163


---

Figure 19 represents the sub-processes that

generate the total process of threat integration. DFD K

is the first transformation of information. Inputs are

the threat evaluation, to include the doctrinal overlay,

and the data stores of weather and terrain effects from

DFDs E, figure 15, and G, figure 16. This information is

transformed into how the enemy will make adjustments to

established doctrinal dispositions, frontages, depths,

and echelon spacing to account for the effects of

terrain, weather, and combat losses."  The outputs from

this transformation are a data store of enemy adjustments

and a formal output of a situational template overlay.

All the inputs and outputs of this process are candidates

for assistance with rule-based systems. The inputs are

simple data stores where the information is maintained

and updated. The data store of enemy adjustments is a

target for data maintenance. The output of the

situational template overlay is targeted f)r

normalization of graphics to doctrinal standards and

dissemination to planning elements.

DFD L in figure 19 is the process in which the

event templates are developed. Event templates identify

significant battlefield events and enemy actions that
will indicate enemy courses of action. It is a

projection tool of what will most likely occur if the

enemy adopts a particular course of action. Any area on

the battlefield identified as critical is output as a

164


---

        THREAT INTEGRATION

Threat                           Weather Effects*

        Evaluationa

        Enemy AdjustmentsSiutoa                    epae
        to Doctrine*

                     Templates*

STem pl t *G

                                 FiG19a.ame  a

                     Collec165


---

data store labeled named areas of interest (NAI) , which
is a point or area where enemy activity or lack of
activity will confirm or deny a particular enemy course
of action. 1 7 This data store is also a data store input
for DFD M, development of decision support templates.
The event template itself is output as an overlay and is
used in the war game process in DFD 7.5 of the command
estimate, figure 10. Information that is germane to this
template overlay is a data store output for the G3/S3 to
conduct the war same. The G2/S2 uses the event template
process to develop precise intelligence collection
requirements. This is output as the collection plan and
will be sent out as a part of the mission in the OPORD or
FRAGO in the command estimate process.

               DFD L can be greatly assisted with rule-based
expert systems. Data maintenance, updating, and
dissemination can be the tasks associated with the data
stores of NAIs and G3/S3 war game data. Additionally,
the data store of NAIs is used in the next process to
develop decision support templates. Normalization,
preparation of output, and dissemination would be the
tasks for the rule-based systems assisting in creating
event templates and collection plans.

               The final process in threat integration is
depicted as DFD M which is the development of decision
support templates. This provides a guide to the

                                                     166


---

commander for when and where tactical decisions are
required relative to battlefield events. This does not
dictate decisions to the commander but identifies
critical events and enemy activities that may require a
decision. The primary input is the data store of NAIs
that was generated in DFD K. An output is the target
area of interest (TAI) data store. TAIs are points or
areas where the commander can influence the action
through fire and maneuver. Such action will cause the
enemy to either abandon his course of action, or divert a
tremendous amount of resources to continue with his
mission. These are the areas where the enemy can be
delayed, disrupted, destroyed, or otherwise manipulated."'
A data store of significant events is generated that
forms the basis of the determination of the decision
points. The data store of decision points is another
product of the threat evaluation process.

               The decision points identify those battlefield
events and areas that may require tactical decisions.
These points also indicate the optimum time of when to
make these decisions to retain freedom of action. The
final product of the threat integration process is the
output of the decision support template. This is an
overlay that graphically depicts TAIs and decision
points. This template will highlight the commander's
opportunities and options and ensure timely and accurate
decisions to allow retention of the initiative. 1'

                                                     167


---

               DFD M, the process of developing decision support
templates, is a candidate for assistance with rule-based
systems. The inputs of the event template and NAIs are
well suited for normalization and data maintenance,
respectively. The data store outputs of TAIs,
significant events, and decision points are targets for
data maintenance and dissemination. The decision support
template is the single most critical product of the IPB
and should be assisted by a rule-based system to ensure
that it is normalized to standard operational graphics
and properly disseminated to planners and the G3/S3 for
the conduct of the war game.

                                                       SUMMARY
               The IPB is closely related to the command
estimate but is a distinct and separate entity. It
takes information from the command estimate, processes
it, transforms it, and returns new information to the
command estimate. Due to this symbiotic relationship,
the same methodology used to decompose the command
estimate and minutely examine information flow and
processing was used on the IPB to identify those elements
that can be enhanced by the use of rule-based expert
systems. Table 4 encapsulates these findings and denotes
those processes that would benefit from automated
assistance.

                                                     168


---

                     ANNEX       A SUMMARY

This table is a recapitulation of the information flows
analyzed in the Intelligence Estimate of the Battlefield (IPB).
The following key is used:
to explain the type of system inc.cated:
Norm Normalization of an expres.,jon or graphic to
doctrinally correct form.
Synch Synchronization of action, equipment, or event to a
common time reference.
DM Data Maintenance. Data is maintained in a store or data
base. The information is constantly updated as changes occur.
Con Consultancy to ensure that doctrine and AirLand Battle
tenets are adhered to.
CMP Computational procedures in which the rule-based system
determines that a mathematical computation is necessary. It
will continually update these computations as changes occur.
PO Prepare output of warning orders, OPORDs, FRAGOs, and
related graphics.

DFD PROCESS          DFD         RELATED DFD         1 TYPE OF

                                                           SYSTEM

BATTLEFIELD AREA     A                               Con
EVALUATION
                              6.0,7.1,7.3            Con
   Determine AO                1.0,6.2,9.0,B         Norm
    CDR's Guidance             1.0,6.0,6.2,8.0,9.0,  Norm
    Where(Mission)              C,H,I
                              2.0,C,H,I              DM
   G3 Facts                   3.0,1                  DM
    G3 Assumptions             1.0,6.0,6.2,8.0,9.0,  DM
    Rear,Deep,Close               B,C,H,I
                     B                               Norm
    Determine Area
    of Interest                1.0,6.2,9.0,A         Con
   CDR's Guidance             See Mission            Con
   Dimensions                                        Norm
                     C
TERRAIN ANALYSIS                                     DM
    ID Gaps in data            1.0,6.0,6.2,8.0,9.0,
   Mission                      A,H,I                Con
                                                     Norm
   Facts                      2.0,A,H,I              Norm
   Gaps                       See Facts above
DEVELOP OVERLAYS     D
   Terrain Factors            G
   Combined Obs.              EF.2,H

                            TABLE 4.

                            169


---

                       ANNEX        A SUMMARY
DFD PROCESS                        (Continued)

                              DFD                    RELATED DFD  TYPE OF
                                                                    SYSTEM

INTEGRATF WEATHER             E                                   Com
                                                                  Norm
Combined OS.                       D,F.2,H                        DM

Weather Effects                                                   Con

ANALYZE CLOSE,                F                                   Con
DEEP, and REAR                          B
                                                                  Con
    Dimensions                                                    Con,DM
                                                                  Con,DM
ID DEEP TARGETS               F.1 G                               Con, T)M
    Deep Areas                             A
    NAIs                                   L,M                    Con
    TAIs                                   M                      Con,DM
                                                                  Con,DM
ID CLOSE AVEs                 F.2 G                               Norm
    Close Area                             A
    Combined OBS                           E                      Con
             Overlay                                              DM
                                                                  DM
ID REAR TARGETS               F.3 G
    Rear Areas                             A                      Con
    Rear Area TGTs                         I                      Norm

ANALYZE TERRAIN               G    F.1,F.2,F.3                    Con

Terrain Factors                    D                              Cori
                                                                  DM
overlay                                                           Norm

Terrain Effects                    K                              Con
                                                                  Con
WEATHER ANALYSIS              H
                                                                  Con
Facts                              2.0,8.0,7. 1,1                 Con
                                                                  Norm
Mission                            1.0,6.0,6.2,P.0,9.C,
                                                                  DM
                                              A.C,I               DM

Int Weather                        E

Weather Effects                    K

THREAT EVALUATION             I
    2apabilities                        1.0,6.0,6.2,8.0,9.0,
    Mission                               A,C,H
                                        2,0,6.0,7.1
    Facts                              3.0,6.0,7.2
    Assumptions

                      TABLE 4 (Continued).
                                         170


---

                       ANNEX        A SUMMARY
DFD PROCESS                        (Continued)

                              DFD       RELATED DFD       TYPE OF
                                                            SYSTEM
THREAT EVALUATION             I
                                                            Con
Rear Area TGTS                     F.3                      DM
                                   F.2                      DM
AVEs of Approach                                            DM
                                                            Con
Enemy OB                                                    Norm

Apply Doctrinal               J                             Con
                                                            Con
Templates                                                   Con.DM
                                                            Zon,DM
THREAT INTEGRATION                                          DM
                                                            Norm
Dev Sit Tmplt                 K
                                                            Con
Weather Effects                    E                        Norm
                                   D                        Con,PO,
Terrain Effects                    Refines                  Synch
                                                            DM
Enemy Adjustment                            G2/$2   data   Con,DM

Situation Tmplt                                            Con
                                                           Con,DM
Dev Event Tmplt               L                            Con,DM
                                                            DM
Event Template                                              DM
                                                            Norm
Collection Plan

G3/S3 War Game                     F.1,M
NAIs
                                   F.1,L
Dev Decision                  M    F.1
                                   7.4,7.5,9.0
Support Tmilt

NAIs

TAIs

Sig Events

Decision Points

Dqcision Support

Template

                              TABLE 4 (Continued).

                                   171


---

                 The funct nal decomposition of the IPB provides
one clear divergence from the command estimate: the
commander's intent is not a consideration in the flow of
information. This is due to the fact that the IPB is
concerned with the area, the weather, the terrain, and
the enemy. The commander's vision of the battlefield at
the end of the operation is not, and should not be, part
of this analytical process. However, the results of the
IPB should be thoroughly irtegrated into the processes
the commander uses to develop his intent, formulate his
guidance, and generate the restated mission.

                 The intelligence preparation of the battlefield
is an ideal candidate for assistance with rule-based
expert systems. The primary reason for this is that the
majority of the processes use clearly defined methods to
produce results. These processes can be refined to a
manageable rule-base oni which an automated expert system
can be created. The majority of the ancillary sub-
processes are either to normalize template and overlay
information to doctrin~ily correct symbology or to
supervise the dissemination of information outputs to
,taff planners within adjacent or lower echelon
organizations. The use of expert-systems in this
environment will harvest measurable results.

                                                          172


---

                APPENDIX A END NOTES

      'US Army, ST 100-9, The Command Estimate  (1989):

7-1.

      2US Army, FM 100-5, Operations (1986): 35.
      3 ST 100-9 (1989) : 7-2.
      4 FM 100-5 (1986) : 35.

             IST 100-9 (1989): 7-4.

             'Michael C. Albano and Robert A. Gearheart,

JR., 'An Initial Study Examining the Feasibility of
Expert System Technology for Command and Control of
Supporting Arms in the United States Marine Corps,
Master Thesis, Naval Postgraduate School, (1988) : 31.

      7ST 100-9 (1989) :  7-5.
      'Ibid: 7-10.

       Ibid.    7-22.
      "0 Ibid:

      "Ibid.    7-1.
      "2 Ibid:  7-26.
      "3 Ibid:

      "'Ibid.

      lIbid: 7-1.

      'Ibid: 7-27.

      "Ibid: 7-32.

       "Ibid:   7-36.
      "Ibid.

                          173


---

APPENDIX B


---

                                                APPENDIX B
                                                INTERVIEWS

                During the course of the research for this thesis,
a number of interviews with functional area experts were
conducted to gain knowledge of artificial intelligence,
rule-based expert systems, and the workings of the command
estimate. It was the initial intent to perform these
interviews using electronic mail on the Defense Data
Network. Unfortunately, the majority of the people who
were interviewed either did not have access to E-mail or
declined to use that medium for interviewing.

               This appendix contains a synopsis of the
interviews that were conducted.

            CAPTAIN GARCIA, Center for Army Lessons Learned
               CPT Tony Garcia is a command and control

analyst with the Center for Army Lessons Learned (CALL)
at Fort Leavenworth, KS. This interview was conducted on
12 January 1990.) The focus of the interview was his
observations at the National Training Center (NTC) with
respect to the tactical implementation of command and
control in a realistic combat environment.

               CPT Garcia stated that the biggest problem that
units have in using the command estimate is

                                                     175


---

synchronization. The synchronization matrix is a
recommended tool for the 71 series (mechanized infantry
and armor) field manuals. In observations of units
operating at the NTC, it is not used because it is just
too complicated and takes up too much time. This is
complicated by the fact that the staffs, as seen at NTC,
are often tired and deprived of sleep. The use of such
tools requires a high degree of cognitive awareness that
most of the staff officers lack after several days of
continuous operations. This symptom extends to other
tools available for use.

               CPT Garcia was asked to comment on those areas
that could possibly benefit from automation. He
suggested that the S3 and S4 staffs could benefit most
from automation enhancements and staff planning aids for
generating march tables, forecasting logistics, or other
projections using quantitative procedures.

               CPT Garcia then stated that there are areas of the
command estimate that could benefit from AI automation:

               Mission Analysis: The biggest problem here is
that commanders and staffs do not analyze and manage time
well. What is needed is a tool that, when given a
time line from initiation to mission accomplishment, can
time manage critical tasks. This tool must be able to
determine how long each sub-process of the command
estimate should take, based on historical analysis of that

                                                     176


---

unit's performance, and suggest those steps that can be
abbreviated, combined within other steps, modified, or
completely ignored.

                 Commander's Guidance: Often, this is not
articulated well to the staff. It is either unorganized
or compounded by problems with basic terminology.

                 Course of Action (COA) Development: A recurring
problem is that steps are continually being missed or
conducted out of order.

                 COA Analysis: The war gaming phase is often not
done well because the relative level of training within
the staff. At task force level, the S2 is often a junior
officer who does not have the experience to conduct
adversarial war gaming well. What is needed is a
docrinally correct threat adversary against which to war
game courses of action. A desired product of this phase
would be a synchronization matrix. Also, logistic-,
either friendly or enemy are not well orchestrated into
the war gaming process. Currently logistics are neither
planned for or thought through during the war game.

                 OPORD/FRAGO: This is often a tedious clerical task
that slows the process of order dissemination. An AI
driven system could collate logistical and operational
information. The logistical information is often hard to
capture or is inaccurate.

                                                          177


---

                Some additional suggestions by CPT Garcia in using
automation:

                1. Produce a preparation planning chart that is
like a time line of critical events. This would tie in
doctrine with tasks identified for accomplishment on the
battlefield. An example is an operation for a brigade to
seize an objective. However, an unfordable river is
between the friendly force and the objective. It is now
necessary to conduct a river crossing. The AI system
would be an honest broker for things such as engineer
support, fire support, air defense coverage, etc. It
would work hard to make sure none of the pieces were left
out of the development of the operational plan.

                2. Staffs do not execute the command estimate
well because they only practice it during field training.
An AI system would be used for all staff actions, both
administrative and tactical, to allow the staff to develop
and maintain proficiency in the use of the command
estimate process.

                3. An AI system would standardize the commander's
planning guidance. It must address the battlefield
operating systems (BOS) in additional to situationally
dependent items.

                4. A question that concerns many combat arms
officers is what happens if the computer fails? How can
the commander or staff go to the manual system, then at

                                                     178


---

some future point, bring the AI system back on-line? If
automation is to be used in the command estimate, these
questions must be answered.

                5. Much time is wasted assembling the staff or
conducting the planning of an operation while some of the
staff members are absent. An AI based system must be able
to process on a distributed architecture in a real-time
mode.

               The observations furnished by CPT Garcia were
documented with CALL Full Observation Reports from the
Army Lessons Learned Management Information System
(ALLMIS) . These identified operational areas in the
command estimate process that could be assisted with the
use of rule-based expert systems.

              Jon Fallesen, Ph.D.. Army Research Institute
               DR. Fallesen is a behavioral psychologist with the

Fort Leavenworth Field Office of the Army Research
Institute (ARI) . He has been studying the human dimension
of command and control. This interview was conducted on
19 January 1990.1 The focus of this interview was the
findings of ARI in the execution of the command estimate.

               A surprising observation .iade by DR. Fallesen was
that the command estimate is often not always used in the
field due the following reasons:

                                                     179


---

               Time constraints: Staffs cannot do everything
that is prescribed by doctrine or procedure in the time
available.

               Cognitive biases: Human adopted strategies can be
suboptimal (will not accomplish the assigned mission),

                Information ise: Commanders and staffs do not
actively seek or disseminate information due to the threat
of information overload.

                Information uncertainty: There is a large degree of
uncertainty in tactical information. Consequently, the
information received by commanders and staffs is often
mistrusted. This causes time and effort to be wasted by
verifying the inlormation or waiting for other information
to corroborate the uncertain information.

               Over-confidence: Commanders and staffs often
suffer from over estimating the abilities or capabilities
of their forces. This causes implementation of poorly
conceived and synchronized plans. It also results in the
development of few contingencies.

               Experience: A lack of experience on the part of
commanders and staffs can result in less than optimal
tactical judgments.

               Management of process: Staffs often suffer from
poor group dynamics. This causes an incomplete decision
making process in which issues are resolved as the last
option discussed.

                                                     180


---

                'Option' definition: Commanders and staffs
frequently do not distinguish between multiple COAs. The
result is that only one COA is developed.

                Scope: Different decision making models apply for
tactical versus other problems. The military decision
making process may not be applicable in all situations.

               Decision analysis: The ability to make correct
decisions is highly situation dependent. Some commanders
and staffs will consistently make good decisions; others
will not.

               This interview produced hard scientific evidence
of areas in the command estimate that do not perform well
due to lack of time, inefficient information management,
or human experience factors. The use of these
observations assisted in identifying areas that could be
improved with rule-based expert systems.

              LIEUTENANT COLONEL STRAND, Future Battle Lab
               LTC Robert A. Strand is the director of the

Combined Arms Center (CAC) Future Battle Lab at Fort
Leavenworth, KS. This interview was conducted on 9 March
1990.1 The focus of this interview was the process of
command and control and how automation can assist it.

               LTC Strand stated three primary reasons why
commander's and staffs do not follow the command estimate
are:

                1. Shortage of time.

                                                     181


---

               2. Lack of familiarity with the process.
               3. The command estimate, as defined by ST 100-9,
may not apply to the particular tactical situation.
               The G3/S3 is the staff officer who takes all the
various statuses and aggregates them. These include the
combat, combat support, and combat service support
statuses. The G3/S3 performs the synthesis of this
information and advises the commander on operational
options. Often, it is the job of the chief of staff to do
this, but it is the G3/S3 who has the information and is
in the best position to assess it and make a
recommendation.
               The G3/S3 should have the capability to go into
the automated command and control system and selectively
retrieve information without having to interpret volumes
of data to get the critical information.
               Most commanders base their decisions on a small
set of data elements. The particular data elements do not
change from operation to operation. However, dependent
upon the situation, the priority in which the commander
may need the data elements may change. In most cases, the
information that the commander needs is already generated
or being maintained on an automated system somewhere
within the command. A system is needed that can retrieve

                                                     182


---

this information and provide it to the commander in a
timely fashion so he can act on that information and make
informed decisions.

                LTC Strand stated that we do not want to drown the
commander with information, but we have to provide him
with the most recent and most correct data so he can make
the best and most informea decisions. I introduced the
term of executive information systems (EIS) that are found
in industry. LTC Strand stated that the capabilities of
an EIS are the same that are needed in an automated
command and control system.

                A capability demonstrated by the AirLand Battle
Management system (ALBM) was that rule-based systems can
array forces. This has the potential for allowing the
commander, or staff officer conducting the war game, the
ability to do multiple what-ifs for a course of action.
It will let you mix and match forces and how they are
disposed on the battlefield.

               War gaming can highlight areas of concern for the
commander. It can help to pinpoint the elements of
essential information that the commander needs in a
tactical situation. War gaming can also help to identify
critical assumptions.

               A rule-based expert system assisting the command
estimate can perform as an automated checklist to make
sure doctrine is adhered to and all the elements that are

                                                     183


---

available to a military force have been included and
synchronized into the overall scheme or plan.

      LIEUTENANT COLONEL TICHENOR, Center for Army Tactics
               LTC Tichenor is an instructor in the Center for

Army Tactics (CTAC) at the Command and General Staff
College. He served as one of the project officers for the
development of ALBM and was a command and control subject
matter expert for the rule and knowledge base engineering
during project implementation. This interview was
conducted on 22 January 1990.1 The focus of the interview
was his experience of ALBM and professional observations
of the command estimate in practice.

               With respect to his experiences in the development
and implementation of ALBM, he stated that it had a
tremendously large rule base. It included the rules of
war, tenets of AirLand Battle, and a lot of other rules
that are often in conflict with each other or with each
segment of the battlefield (rear, deep, close). An
interesting point is that it took a lot of time for the
knowledge engineers to establish the rule base. This was
a recursive process where the knowledge engineers had to
keep interviewing the subject matter experts (SMEs) in
very minute detail.

               A salient point is that ALBM was not intended to
provide leadership. Even when given a system such as
ALBM, the commander is still responsible for everything

                                                     184


---

the unit does or fails to do. The ultimate decision of
any action rests with the commander who must make the
determination of whether or not to implement the solutions
provided by ALBM.

               The focus of ALBM should be the plans officer at
division level. ALBM should replicate the manual process
in case the equipment fails or reaches some point where
human intervention is necessary. If the automated system
is not parallel to the manual system, different solutions
to common problems will be generated. This will not allow
for an easy transition to or from human interaction.

               LTC Tichenor felt that the biggest contribution a
system like ALBM can make is that it can give a
doctrinally correct aspect to an operation. It can also
provide historical perspectives.

               LTC Tichenor's observations on command estimate
were based on extensive field experience in a wide
variety of staff positions. He stated a major caveat to
the command estimate process is that it was designed for
the Fort Leavenworth academic environment and not
necessarily for the battlefield. However, it's the best
methodology the Army has and it does work as long as time
is available. He does not foresee any changes to the
command estimate process in the foreseeable future because
it is the best system available.

                                                     185


---

               Problems develop when the command estimate is
performed under stress or time compression. Its strong
point is the ability of staffs and commanders to
synthesize phases of it based on experience and comfort
levels.

               An interesting point is that LTC Tichenor stated
that commanders need executive information systems (EIS)
to let them see the important trends (trend analysis) and
manage by exception. Such systems would give them access
to the five or six things that they need to know. These
can be defined as the commander's information
requirements.

                  MAJOR JOHN KELLY, Center for Army Tactics
               MAJ John Kelly is a tactics instructor in the
Center for Army Tactics (CTAC) in the Command and General
Staff College. This interview was conducted on 24 January
1990.6 The focus of this interview was MAJ Kelly's
observations of the execution of the command estimate in
both academic and field environments.
                MAJ Kelly stated that there is a wide disparity of
quality in the performance of the command estimate. When
asked if he could differentiate between good and bad
performance, he stated Lhat the units and staffs who
execute the command estimate well have several common
traits:

                                                     186


---

                1. Know the commander's intent.
               2. Know the commander's information requirements.
               3. Have a staff orchestrator.
               The commander's intent is a key component in the
command estimate. In units that perform poorly, the
commander's intent is often not specific and is not
disseminated well. The result is that the staff and
subordinates do not understand the commander's intent and
do not plan accordingly.
               There are two methods of conveying the
commander's intent. It can be either oral/written or as
a graphic. The most effective method of having it
understood is a combination of the two.
               The command estimate is time dependent. There
needs to be improvement in the analysis of available time
and how to best use it. A major problem is that no one is
designated as the time manager for planning. There needs
to be someone to orchestrate the events.
               An effective tool to manage time and integrate the
BOS is the synchronization matrix. It is imperative that
it give visibility of the time line, BOS, and sub-units.
This information is normally in graphic form. One of the
tasks of the synchronization matrix is the integration of
the BOS. However, this is an extremely complex exercise
and often exceeds the ability of the staff to properly use

                                                    187


---

all available assets to the fullest potential. Help is
needed with prioritization and consultancy. This is an
area where AI can perform with great utility.

               Information management from higher and adjacent
organizations is often poor. The commander is given
enough, or more than enough, information. But it is
normally old or overcome by events. What the commander is
not provided is analysis of this information. Good
analysis is a time consuming process that normally
produces results too late in the planning process to be of
value to the commander and staff. Additionally, outgoing
information in the form of orders is often incomplete and
does not precisely convey the commander's intent.

               A large portion of the command estimate is based
on the experience and judgement of the commander. This is
hard to make into a set of rules that can be followed by a
machine. For a system to be used in the field, it must be
as painless as possible and provide the commander a tool,
not a yoke.

               The Intelligence Preparation of the Battlefield
(IPB) is performed in isolation by the G2 and is not
integrated into the G3's operation. The IPB should be
continuous, with some system available to orchestrate its
execution to mesh with the command estimate being
performed by the remainder of the staff. A tremendous use

                                                    188


---

of AI could be to inform the staff when there is a
difference between doctrinal/situational templating and
ground truth of the enemy.

               When it is determined that not enough time is
available to perfcrm the command estimate, the
abbreviated process must be initiated. This is not a
curtailment of the formal process. In the abbreviated
command estimate, all the steps need to be done. What is
needed is assistance in showing what steps or processes
can be shortened.

                 MAJOR ED KASTER, Center for Army Tactics
               MAJ Kaster is an automated command and control
systems instructor in the Center for Tactics (CTAC) at the
Command and General Staff College. This interview was
conducted on 4 January 1990.0 The focus of this interview
was the Maneuver Control System (MCS) and automated
command and control systems.
               A primary source of information was an after
action report (AAR) containing the observations of a MCS
class conducted at CGSC.7 While MCS is an exceptional
hardware suite, the software does not give a tremendous
amount of functionality. It is an acceptable means of
sending free text messages on the battlefield.
Manipulated by a well trained operator, the MCS data base
functions can provide large volumes of tabulated data.

                                                     189


---

               While the E-mail and database capabilities are
definitely valuable assets, by themselves they do not
significantly help the commander see and fight the battle.
The four other functions of planning, coordinating,
directing, and controlling must also be included within
the system. To support these functions the system must
have a functional graphics system and the current graphics
capability is totally unacceptable. This leaves us with a
computerized message center and logistic update system,
not a maneuver control system.

               Future software revisions will work to add more
functionality to MCS. However, this is dependent upon how
well the Army voices requirements.

               Although MCS appears to provide a satisfactory
method of putting information into the system, there are
current problems in transferring and sorting data and
displaying intelligent information. So far, automation
appears to have created problems with information
overload. With the exception of some pie charts, MCS
provides data, not information. An AI tool may be helpful
in sorting out what is important and needs to be
immediately brought to the commander's attention. It may
also be able to determine what can be stored away until it
is needed, and what is *junk mail' that needs to be purged
from the system.

                                                     190


---

                       MCS must be able to do three things within all
of its functions. These are the same functions expected
of a civilian executive level computer support system.

                        1. It must provide a top-down high speed
review of operational information.

                       2. It must show trend analysis.
                       3. It must provide exception reporting.
               MAJOR (Ph.D.) RICHBOURG, West Point AI Lab
               MAJ Robert F. Richbourg, Ph.D., is a research
scientist in the office of artificial intelligence,
Department of Geography and Computer Science, United
States Military Academy. This was the only germane
interview conducted via electronic mail (E-Mail) on the
Defense Data Network (DDN). I spoke with him informally
at CGSC in December 1989. He directed me to send him some
of my questions on DDN and he would respond. The focus of
the interview was to establish the limits of rule-based
expert systems in the command estimate. The following is
a summation of the interview:
               When asked if he felt if artificial intelligence
should be used in military command and control, MAJ
Richbourg responded that we should try to make use of any
applicable advanced technology to support command and
control. AI does include many well-defined techniques
that are applicable. However, current AI technology can
not completely replace the man in the decision cycle. It

                                                    191


---

can augment the abilities of commanders and staffs by
prompting for key considerations, filtering information,
providing 'what-if' simulations, etc.

               When discussing the architecture of a rule-based
expert command and control system MAJ Richbourg stated
that such a should be embedded, if possible, within other
maneuver control systems. This system should also be
distributed to allow input from the entire staff.
Ideally, the system should support staff decisions as well
as those made by the commander.

               Operational systems can be developed to perform as
assists to the human, or in some well-defined problem
domains, to perform the decision tasks. The distinction
is based on the size and type of problem. As a trivial
example, a rule-based expert system could easily replace
the man in the checkbook balancing decision cycle).

                MAJ Richbourg stated that the Department of
Defense standard computer language, Ada, can be used to
develop AI based command and control systems?

               The topic of the complexity in finding and using
knowledge engineers for establishing tactical decision
aids was discussed. MAJ Richbourg stated that for small
problems, the user of the system can also be the knowledge
engineer. For more complex problem areas (such as
maneuver planning), reliance on a trained knowledge
engineer is a much better choice. Complex systems usually

                                                     192


---

require complex interactions within the knowledge-base and
the management of these complexities is best left to
trained computer scientists. However, regardless of the
complexity of the problem, the knowledge-base should be
modular, making changes less difficult.

               Some of the shortcomings of expert system (ES)
technology were briefly noted by MAJ Richbourg:

                1. These systems do not have intuition.
               2. They do not learn.
               3. They are not creative.
               4. They have a narrow view of the problem.
               5. They can not apply common sense reasoning.
               6. They are poor at interpreting sensory data.
               When tasks require these traits, they are best
performed by humans, who might be assisted by rule-based
expert systems. There are many things that can be done
well by such a system. However, the crucial task is to
decide where the technology is most applicable and then
implement it.

                                                    193


---

                                     APPENDIX B END NOTES
            'CPT Anthony Garcia, 12 January 1990, CATA, Center
for Army Lessons Learned, Fort Leavenworth, KS.
            2 Interview, DR. Jon Fallesen, 2 February 1990, US
Army Research Institute Field Team, Fort Leavenworth, KS.
            'LTC John A. Strand, 6 February 1990, CAC, Future
Battle Lab, Fort Leavenworth KS.
            4 LTC Arthur H. Tichenor, 22 January 1990, CGSC,
Center for Tactics, Fort Leavenworth, KS.
            IMAJ John Kelly, 18 January 1990, CGSC, Center for
Tactics, Fort Leavenworth, KS.
            GMemorandum, ATZL-SWT-C (CTAC) to Commander, USA
Combined Arms Center, Subject: After Action Report,
Advanced Command and Control Elective, A399. (2 June
1989): (Cited hereafter as MCS AAR).
            7 MAJ Robert F. Richbourg, 4 January 1990,
Department of Geography and Computer Science, West Point,
NY.

                                                     194


---

APPENDIX C


---

                                                    APPENDIX C

                                                      GLOSSARY

Army Lessons Learned Management Information System
(ALLMIS): A data base of observations made by the
Combined Arms Training Activity (CATA) Center for Army
Lessons Learned (CALL). These observations document
training and performance at the NTC and during real-world
operations such as Urgent Fury and Just Cause.
Army Research Institute (ARI) for the Behavioral and
Social Sciences: An Army activity that performs research
and analysis of behavioral sciences.
ATCCS: Army Tactical Command and Control System. The
command and control system utilized by all tactical
echelons up through corps. ATCCS includes the
organization, facilities, and procedures through which the
commander plans, directs, controls, and coordinates
operations.'
Artificial Intelligence (AI)-: A discipline of computer
science dedicated to the development of computational
machines that exhibit intelligent behavior and that
approximates the human reasoning process in decision
making.' AI systems normally are based on series of rules

                                                    1o


---

or procedures for a specific situation or problem. The
solution to the problem is found by a backward chaining
process that starts with the desired solution and
sequentially works towards the current state. AI's
largest difference from human reasoning is that it does
not have intuition.
Background Mode: An operation in an computer system that
occurs regardless of what the current process in the
system is. An example would be a communications monitor
that will signal a warning to a staff officer anytime a
particular unit identification is received in a hardcopy
message. This background operation will be performed even
when the computer system is involved in printing a report
or sorting a data base.
Battlefield Information System: An automated system to
handle the unique requirements a commander or staff
officer needs to harvest, process, and disseminate
information in a tactical battlefield environment.
Battlefield Operating System (BOS) : The major functions
occurring on the battlefield, each consisting of systems
employed to successfully execute operations by the total
Army. The seven BOS are: maneuver, fire support, air
defense, command and control, intelligence, mobility and
survivability, and combat service support. 3

                                                    197


---

Button: In a hypertext document, a physical tag that
connects a word or phrase in the document to a similiar
word or phrase in another document. These buttons are
created on an individual basis to ensure that a specific
linkage is made between the designated words or phrases.
Center for Army Lessons Learned (CALL): A component of
the Combined Arms Training Activity, Fort Leavenworth, KS.
CALL performs historical analysis of training and
performance at the NTC and during real-world operations.
Center for Army Tactics (CTAC): The Army's focal point
for tactics doctrine and instruction. The center provides
doctrinally sound tactics expertise to assure coherence
among doctrine, organizational concepts, weapons concepts,
and training.
Combined Arms Research Library (CARL): The research
library located and operated by the US Army Combined Arms
Center as an adjunct to the Command and General Staff
College, Fort Leavenworth, KS.
Command and Control (C2) : The process through which the
activities of military forces are directed, coordinated,
and controlled to accomplish the mission. This process
encompasses the personnel, equipment, communications.
facilities, and procedures necessary to gather and analyze
information, to plan tasks, to issue instructions, and to
supervise the execution of operations. 4

                                                     198


---

Command and Control System: The facilities, equipment,
communications, procedures, and personnel essential to a
commander for planning, directing, and collecting
operations of assigned forces pursuant to the mission
assigned.*
Command estimate: The process used by military commanders
and their staff that focuses on essential facts and
necessary assumptions to make decisions that will lead to
success on the battlefield.0
Commander's Intent: The commander's vision of how the
battle will be fought. It is the commander's expression
of how the battle is to be fought and what is to be
accomplished.'
Constraint: Limitations placed on the command by the
higher commander. Constraints restrict the freedom of
action a headquarters has for planning a mission.
Constraints are those things a planning headquarters are
required to do.0
Consultant Expert System: Expert systems that can
provide correct doctrine and procedures in areas that
commanders and staffs may not be technically knowlegeable
in.
Expert Systems: A sub-field of artificial intelligence in
which the computer programs follow rules established by a
human expert in a specific problem domain.'

                                                    199


---

Estimate of the situation: In the military decision
making process, the collection and analysis of relevant
information for developing, within the time limits and
available information, the most effective solution to a
problem.10
Data Base: A collection of interrelated data stored
together with a minimum of redundancy to serve multiple
applications.
Data Flow: A conduit through which packets of information
of known composition flow."
Data Flow Diagram (DFD): A network representation of a
system portrayed in its component parts. 1 2
Data Store: In a data flow diagram (DFD) , a data stores
is where information is kept or deposited. This is often
a temporary store of information as it awaits processing
by another part of the system.1 3
Defense Data Network (DDN): A packet switched data
network owned and operated by DOD for use by E-Mail.
Defense Technical Information Center (DTIC): An
information resource center operated by the Department of
Defense to manage and maintain militarily significant
technical information.
Electronic Mail (E-Mail) : A system providing data
communications between two or more computers.

                                                    200


---

Estimate of the Situation: A systematic military
decision-making process that is typified by considering
significant facts and assumptions to arrive at a
recommendation on how to best use available resources to
resolve a problem or mission.
Executive Information System (EIS) : A family of civilian
software applications that accesses, creates, or delivers
high-level information to nontechnical executive decision
makers.
FRAGO: Fragmentary order. An abbreviated form of an
operations order (OPORD) used to make changes in missions
to units and to inform them of changes in tactical
situations."
Hypertext: A method of linking information by associated
meaning as opposed to traditional numeric or alphabetic
schemes. Documents become data bases where any word or
phrase can be used for sorting or searching operations.
Knowledge engineer: An AI technologist who performs in
depth interviews with subject matter experts to extract
the heuristics and factual rules of the domain knowledge
to be encoded into the expert system knowledge base."
Maneuver Control System (MCS) : A command and control
system that focuses on the tactical execution of war.
Currently, MCS is in the form of an automated system based
on a collection of data bases and attendant communications
facilities to disseminate information.

                                                    201


---

Normalize: The process of making a term or graphic
conform to doctrinal correctness. This is important to
insure that the commander's image of an operation is
conveyed to subordinates in exacting clarity.
OPLAN: A plan for a military operation. It covers a
single operation or a series of connected operations to be
carried out simultaneously or in succession. "
OPORD: A directive issued by a commander to subordinate
commanders for effecting the coordinated execution of an
operation. It is normally the tactical orders given to a
unit.'"'
Rule-based Expert System: An artificial intelligence
system that uses a base of rules defined by a human expert
to solve a clearly defined problem.
Sink: In a data flow diagram (DFD) , a sink is the system
interface with the external world. This is where
information leaves the system. In the command estimate,
this is normally a FRAGO, OPORD, warning order, or a
graphic overlay."'
Source: In a data flow diagram (DFD), a source is the
system interface with the external world. This is where
information enters the system. This is normally in the
form of an order from a higher headquarters or a higher
commander's intent or guidance.'*

                                                    202


---

Subject Matter Expert (SME) : A human expert in a
particular field or problem domain from which the
procedures for solving a particular problem are taken.
Synchronization Matrix: A graphical tool used by staff
planners to orchestrate battlefield operating system
resources into military operations.
Systems Analysis: The methodical investigation and study
of a data flow problem with the view toward improving that
flow in terms of maximizing cost benefits, speeding up
results, and reducing errors. 20
War Game: A method of comparing courses of action in the
command estimate. Used primarily by the G3/53, it is a
conscious attempt to visualize the flow of battle, given
friendly and enemy dispositions, enemy assets, possible
enemy courses of action, and a defined area of terrain.2
Warning Order: A preliminary notice of an action or order
that is to follow. Usually issued as a brief oral or
written message, it is designed to give subordinates time
to make necessary plans and preparations. 2 2

                                                    203


---

                APPENDIX C END NOTES

            'US Army, FM 100-15, CORPS OPERATIONS (APPROVED
FINAL DRAFT): 1-10.

            'Paul E. Lehner, Artificial Intelligence and
National Defense: Opportunity and challenge (1989): xi.

            'US Army, Army Command and Control Master   Plan (U),
Vol 1. (1987): B-3.                                     and Symbols

            4 U.S. Army, FM 101-5-1, Operational Terms

(1985): 1-16.

'Ibid: B-4.

*ST 100-9, (1989): 1-2.

            'US Army, Field Manual 101-5-1, Operational Terms
and Symbols. (1985): 1-17.

            'US Army, Student Text 100-9, The Command Estimate.
(1989): 2-6.

              Paul E. Lehner, Artificial Intelligence and
National Defense (1989): 15.

            %0FM 101-5, (1984): 5-2.

             "1Tom De Marco Concise Notes on Software Engineering
(1979): 5.

            12Ibid: 4.

            "Tom DeMarco, Concise Notes on Software Engineering
(1979): 5.

           14 FM 101-5-1 (1985): 1-34.

'6 Lehner, 15.

14FM 101-5-1    (1985):       1-53.
"lIbid.

                         204


---

             "Control Data Corporation, Defining Software
Requirements (1985): 3-3.

            1OIbid: 3-4.
             "0 Gerald A. Silver and Joan B. Silver Introduction to
Systems Analysis (1976): 14.
             "ST 100-9 (1989): 4-1.
            2 2 FM 101-5-1 (1985): 1-75.

                                                     205


---

BIBLIOGRAPHY


---

          APPENDIX C

          BIBLIOGRAPHY

1. Books

Andriole, Stephen J., ed.    High Technology Initiatives in
       C31. Washington, DC:  AFCEA International Press,
        1986.

Boyes, Jon L. and Stephen J. Andriole, eds. Principles of
       Command and Control. Washington, DC: AFCEA
       International Press, 1987.

Control Data Corporation, Defining Software Requirements.
       Bloomington, MN: Control Data Corporation, 1985.

DeMarco, Tom, Concise Notes on Software Engineering. New
       York: Yourdon Press, 1979.

Langefors, Brgje, Theoretical Analysis of information
       Systems. Philidelphia, PA: Aurerback Publishers,
        1973.

Lehner, Paul E. Artificial Intelligence and National
       Defense: Opportunity and Challenge. Blue Ridge
       Summit, PA: TAB Professional and Reference Books,
        1989.

Ligget, Glenn, C. David Mead, and Melinda G. Krammer.
       Prentice Hall Handbook for Writers. 10th ed.
       Englewood Cliffs, NJ: Prentice-Hall, 1988.

Metzger, Philip W. Managing a Programming Project. 2nd
       ed. Englewood Cliffs, NJ: Prentice-Hall, 1981.

Monk, Andrew, ed. Fundamentals of Human-Computer
        Interaction. Orlando, FL: Academic Press, Inc.,
        1984.

Ralston, Anthony, ed. Encyclopedia of Computer Science
       and Engineering. 2nd ed. New York, NY: Van Nostrand
        Reinhold Co., 1983.

          207


---

Rolston, David W. Principles of Artificial Intelligence
       and Expert System Development. New York, NY: McGraw
       Hill, 1988.

Silver, Gerald A. and Joan B. Silver, Introduction to
       Systems Analysis. Englewood Cliffs, NJ: Prentice-
       Hall, 1976.

Tausworthe, Robert C. Standard Development of Computer
       Software, Part 1 Methods. Englewood Cliffs, NJ:
       Prentice-Hall, 1977.

Weiss, Sholom M. and Casinir A. Kulikowski. A Practical
       Guide to Designing Expert Systems. Totowa, NJ: Roman
       & Allanheld, 1984.

Winston, Patrick Henry. Artificial Intelligence.  2nd ed.
       Reading, MA: Addison-Wesley, 1984.

2. Government Publications

CACDA. Functional Definition of the Army Tactical Command
       and Control System (ATCCS FD). Volume 1 Study Report.
       Fort Wayne, IN: Magnavox Electronic Systems Company,
       June 1988.

Cognitive Engineering Design and Research Team (CEDAR).
       Application of Computers to Learning in the CGSC: A
       Front End Analysis Study, Working Paper WP LVN-88-4.
       Los Alamos, NM: Los Alamos National Lab, April 1988.

DARPA. Forces Functional Description, AirLand Battle
       Management Program Briefing To Industry. Arlington,
        VA: Defense Advanced Research Project Agency,
       September 1985.

DOD. The Joint Staff Officer's Guide, AFSC PUB1.
       Norfolk, VA: Armed Forces Staff College, 1 July 1988.

Joint Chiefs of Staff, 1989 Joint Military Net Assessment,
       CM-1943-89, Washington, DC: Office of the Joint
       Chiefs of Sfaff, 18 May 19

US Army. Army Command and Control Master Plan, Volume I,
       Concepts and Management. Fort Leavenworth, KS:
       Combined Arms Combat Development Activity, October
        1987.

US Army. Briefing Packet from Commander, US .'rmy Combined
       Arms Center, 'Battle Command Integration Program.
       Fort Leavenworth, KS: 25 July 1988.

                                           208


---

US Army. CGSC Circular 351-1, Command and General Staff
       College Catalog, Academic Year 1989-1990. Fort
       Leavenworth, KS: Command and General Stall College,
       May 1989.

US Army. FM 100-15, CORPS OPERATIONS (APPROVED FINAL
       DRAF ). Washington, DC: Department of the Army, 15
       November 1988.

US Army. FM 101-5, Staff Organization and Operations.
       Washington, DC: Department of the Army, 1984.

US Army. FM 101-5-1, Operational Terms and Symbols.
       Washington, DC: Department of the Army, 1985.

US Army. Heavy-Light Lessons Learned: 89-2. Fort
       Leavenworth, KS: Center for Army Lessons Learned, 1
       June 1989.

JS Army. Faculty Bulletin #30, CGSOC Evaluation and
       Grading Policy. Fort Leavenworth, KS: Command and
       General STaff College, 16 Aug 89.

US Army. Memorandum from the Director, Center for Army
       Tactics (ATZL-SWT) to the Commander of the Combined
       Arms Center. Subject: Establishing Priorities for
        the Development of Automated Staff Planning Aids, Fort
       Leavenworth, KS, 2 Aug 88.

US Army. Memorandum from the Chief, Combined Arms Center
       Command and Control Branch (ATZL-SWT-C) to Commander,
       USA Combined Arms Center, SUBJECT: After Action
       Reprot, Advanced Command and Control Elective, A399,
       Fort Leavenworth, KS, 2 June 1989.

US Army. Memorandum from the Chief, Combined Arms Center
       Command and Control Branch (ATZL-SWT-C) to the Deputy
       Commandant, Command and General Staff College.
       Subject: ALBM Evaluation, Fort Leavenworth, KS, 5
       July 1989.

US Army. Memorandum from the Director, Combined Arms
       Center Command and Control (ATZL-CAC-CR) to the
       Director, Command and General Staff College Graduate
       Degree Program. Subject: Proposed Thesis Subjects
        for MMAS and SAMS Students, Fort Leavenworth, KS, 8
       Aug 1989.

US Army. P020 Fundamentals of Resource Management. .ort
       Leavenworth, KS: Command and General Staff College,
       Academic Year 1989-90.

                                           209


---

US Army. Student Text (ST) 18-151, Systems Analysis
       Handbook. Fort Benjamin Harrison, IN: Computer

Science School, November 1984.

US Army. Student Text (ST) 100-9, The Command Estimate.
       Fort Leavenworth, KS: Command and General Staff
       College, July 1989.

3. Magazines

Brown, Bob. *Future of Network Management Lies in Expert
       Systems." Network World. 6 (September 18, 1989):
        10-13.

'Battlefield C31, Bringing Battlefield C31 Computers Down
       to Earth." Defence Update. 98: 48-55.

Bi'rke, Steven. "IBM Readies EIS Products.'  PC Week.
        (May 22, 1989): 11.

Carr, Clay. 'Spreadsheet Sketches for Rule-Based
       Systems.* AI Expert. 4 (November 1989): 30-35.

'C41 in Support of special Operations."  Signal.
       (September 1989): 105-107.

Eskow, Dennis. "Phasing Out of Middle Managers May
        Increase Dependence on EIS." PC Week. (August 21,
        1989): 71-78.

Leibs, Scot. "EIS: It's All Down Hill From Here.'
        InformationWEEK. 220 (May 8, 1989): 44-46.

Miller, Michael J. *PCs and Productivity: Where's the
       Payoff'" Infoworld. (September 18, 1989): 59-62.

Morris, D. J. 'Command Control and Information Systems
       Assessment.* Signal. (October 1989): 57-61.

Myers, Kara. 'DEC Offers Low Risk AI." InformationWEEK.
       234 (August 28, 1989): 16.

NEWEL, CLAYTON R. LTC. "Balancing the Ends, Ways and
       Means.' Army Magazine. (August 1986): 24-32.

Pallatto, John. "Caseworks To Develop C++ Expert System
       Knowledge Base,' PC Week. (July 3, 1989): 53.

Pallatto, John. 'Manuals Take Hypertext Route.' PC Week.
        (July 24, 1989): 65-68.

              210


---

Rogers, Steven P. *Computer Revolution Energizes Mission
       Planning Systems." Armed Forces Journal
        International. (November 1989): 88-92.

Saffo, Paul. "What You Need To Know About Hypertext."
       Personal Computing. (December 1987): 166-173.

Starr, Barbara, "Simulation's Brave New World.'   Jane's
       Defence Weekly. 11 (November 1989): 1031.

4. Unpublished Reports and Studies

Albano, Michael C., and Robert A. Gearhart, Jr. An
        Initial Study Examining the Feasibility of Expert
       System Technology for Command And Control of
       Supporting Arms in the United States Marine Corps.
       Monterey, CA: Naval Post Graduate School, March 1988.

Burge, John, et al. 'The DGB Message Understanding System
        for ALBM Message Processing.* Marina del Rey, CA:
       Logicon, Inc., July 1989.

Carter, Charles F. Jr., Mark A. Archer, and Albert E.
       Murray. 'Description of Selected Army Staff
       Functions: Targets for Planning Aids." ARI Research
       Note 88-62, Fort Leavenworth, KS: ARI Field Unit,
       July 1988.

Cothran, James M. "Considerations in the Design of an
        Information Transfer Subsystem for a Tactical
        Information System." Master of Military Art and
       Science Thesis, US Army Command and General Staff
       College, 1971.

Holmes, Robert A. "Operational Tactical Data Systems
        (OPTADS) Interface for the AirLand Battle Management
        (ALBM) Program." San Diego, CA: Titan Systems, Inc.,
       July 1989.

Hockenberger, Rolk L. and Al J. Relch. "Soldier Machine
        Interface Design for a Military Operations Planning
       Expert System." Austin, TX: Lockheed Missiles &
       Space Company, Inc., December 1988.

Jellison, Robert K. and David C. Vineyard. "The Course of
       Action Comparator, A Course of Action Evaluation Tool
        for Use with a Military Operations Planning Expert
       System." La Jolla, CA: Titan Systems, Inc., July
        1989.

211


---

Lawrence, Richard D. 'A Study of Quasi-Analytic Models
        for Improvement of the Military Commander's Tactical
       Decision Process.' Doctoral Dissertation, Ohio State
       University, 1968.

Lossau, K. 0. , M.J. Berensen, and J.C. Wood. 'An
        Integrated Approach to Army Fire Support Planning.'
       Austin, TX: Lockheed Missiles & Space Company, Inc.,
       December 1988.

McKinney, Joseph W. "Computers for Command and Control:
       An AirLand Battle Management Requirement.' Master of
       Military Art and Science Thesis, US Army Command and
       General Staff College, May 1984.

Meteer, Marie W. 'Block Text Generation in ALBM."
       Cambridge, MA: BBN Systems and Technologies
       Corporation, July 1989.

Michel, Rex R. 'Historical Development of the Estimate of
        the Situation.' Fort Leavenworth, KS: Army Research

        Institute, May 1989.

Murphy, Dennis. *Execution Monitor: Requirements and
       Design Description.* Mountain View, CA: Advanced
       Decision Systems, July 1989.

Schmader, John R. *Command Information Requirements on
       the AirLand Battlefield.' Master of Military Art and
       Science Thesis, US Army Command and General Staff
       College, 1985.

Shaked, Varda and Bruce Papazian. "Natural Language in
        the Context of Modern Interface Technology.
       Cambridge, MA: BBN Systems and Technologies
       Corporation, July 1989.

Springen, Clyde     H., Thomas C. Baker,  and James R.
       Greenwood.   *Architecture of the  Forces/Star System.'
       Austin, TX:   Lockheed Missiles &  Space Company, Inc.,
       July 1989.

Stacknick, Grefory and Jeffry M. Abram. *Army Maneuver

       Planning: A Procedural Reasoning Approach.* Mountain
       View, CA: Advanced Decision Systems, November 1988.

Teeter, William A. 'Expert Systems: Tools in the
       Commander's Decision Making Process.* Master of
       Military Art and Science Thesis, US Army Command and
       General Staff College, 1988.

                    212


---

Widjojo, Agus. *The Consideration of the Human Elements
        in the Command Estimate.* Master of Military Art and
        Science Thesis, US Army Command and General Staff
       College, 1988.

Yavorsky, Joseph S. 'Development of a Prototype
       Multichannel Communication Network Maintenance Expert
        System." Master Thesis, Naval Post Graduate School,
        1987.

5. Interviews

Fallesen, John, PhD. Army Research Institute Field Team,
       Fort Leavenworth, KS. Personal interview 2 February
        1990.

Garcia, Tony, Captain USA. CATA, Center for Army Lessons
       Learned. Personal interview 12 January 1990.

Kaster, Ed, Major USA. CGSC, Center for Tactics.
       Personal interview 4 January 1990.

Kelly, John, Major USA. CGSC, Center for Tactics.
       Personal interview 18 January 1990.

Richbourg, Robert F. Major (Ph.D.) USA. Office of
       Artificial Intelligence Analysis and Evaluation,
       Department of Geography and Computer Science, United
       States Military Academy, West Point, NY. Defense Data
       Network electronic mail session 4 January 1990.

Strand, John A. Lieutenant Colonel USA. CAC-Future
       Battle Lab. Personal interview 6 February 1990.

Tichenor, Lieutenant Colonel USA. CGSC, Center for
       Tactics. Personal interview 22 January 1990.

Vye, Pat, Captain (P) USA. CACDA, Future Battle Lab
        (FBL). Personal interview 25 October 1989.

6. Software

Commander. Computer software for an executive information
       system. Comshare, 1989. IBM-PC/MS-DOS diskette.

C2DAIS (Command and Control Decision Aids Information
       System). A data base of current C2 decision aids
       compiled and maintained by the Joint Services Group on
       Decision Aiding, 1989. IBM-PC/MS-DOS diskette.

MemoryMate. Hypertext and data base system. Broderbund,
        1988. IBM-PC/MS-DOS diskette.

                                           213


---

PC SAM. Simple Access to e-Mail. Transend Corporation,
        1986. Defense Data Network electronic mail software
        for IBM PC compatible microcomputers.

The EBook (TC 11-7). US Army Training Circular 11-7, 'The
       Battlefield Automated Systems Handbook* on magnetic
       media. The United States Army Signal Center, Fort
       Gordon, GA, 1988. IBM-PC/MS-DOS diskette.

US Army. Army Lessons Learned Management Information
System (ALLMIS). Data base of CALL full report
observations. The US Army Combined Arms Training Activity
Center for Lessons Learned (CATA-CALL). This is a living
data base.

                                           214


---

                                   INITIAL DISTRIBUTION LIST

1. Combined Arms Research Library
       U.S. Army Command and General Staff College
       Fort Leavenworth, KS 66027-6900

2. Defense Technical Information Center
       Cameron Station
       Alexandria, VA 22314

3. DR. James L. Morrison
       CB 3500 Peabody Hall
       University of North Carolina
       Chapel Hill, NC 27599-3500

4. LTC Ronald D. Pfeiffer
       Department of Automated Command and Training Systems
       U.S. Army Command and General Staff College
       Fort Leavenworth, KS 66027

5. LTC Robert A. Strand, III
       Future Battle Laboratory
       U.S. Army Combined Arms Center
       Fort Leavenworth, KS 66027

6. MAJ Robert F. Richbourg
       Department of Geography and Computer Science
       United States Military Academy
       ATTN: MADN-B
       West Point, NY 10996-1695

7. DR. Jon Fallesen
       Army Research Institute Field Unit
       P.O. Box 3407
       Fort Leavenworth, KS 86027-0347

8. Chairman,
       Joint Command, Control and Communications Academic Group
       Naval Postgraduate School
       Monterey, CA 93943-5000


--- 