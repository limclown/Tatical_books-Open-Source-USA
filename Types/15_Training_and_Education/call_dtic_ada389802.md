# call_dtic_ada389802  NAVAL POSTGRADUATE SCHOOL
               Monterey, California

                     THESIS

            IMPACT OF THE IMPLEMENTATION OF
INFORMATION TECHNOLOGY ON THE CENTER FOR

                         ARMY LESSONS LEARNED

                               by

                     Anthony Wizner

                     March 2001

Thesis Advisor:                      Erik Jansen
Second Reader:                       Shelley Gallup

Approved for public release; distribution is unlimited.

                     20010541 090

                 oe                  i —


---

               REPORT DOCUMENTATION PAGE                                 Form Approved              OMB No. 0704-

                                                                         0188

Public reporting burden for this collection of information is estimated to average 1 hour per response, including
the time for reviewing instruction, searching existing data sources, gathering and maintaining the data needed, and
completing and reviewing the collection of information. Send comments regarding this burden estimate or any
other aspect of this collection of information, including suggestions for reducing this burden, to Washington
headquarters Services, Directorate for Information Operations and Reports, 1215 Jefferson Davis Highway, Suite
1204, Arlington, VA 22202-4302, and to the Office of Management and Budget, Paperwork Reduction Project

(0704-0188) Washington DC 20503.

1. AGENCY USE ONLY (Leave blank) | 2. REPORT DATE 3. REPORT TYPE AND DATES COVERED

                                  March 2001                                       Master’s Thesis

4. TITLE AND SUBTITLE: Impact of the Implementation of Information [| 5. FUNDING NUMBERS
Technology on the Center for Army Lessons Learned

6. AUTHOR(S) Anthony Wizner                                                . PERFORMING ORGANIZATION
                                                                             EPORT NUMBER
7. PERFORMING ORGANIZATION NAME(S) AND ADDRESS(ES)
      Naval Postgraduate School                                          | 10. SPONSORING / MONITORING
                                                                               AGENCY REPORT NUMBER
       Monterey, CA 93943-5000

9. SPONSORING / MONITORING AGENCY NAME(S) AND ADDRESS(ES)
      N/A

11. SUPPLEMENTARY NOTES The views expressed in this thesis are those of the author and do not reflect the official

policy or position of the Department of Defense or the U.S. Government.

12a. DISTRIBUTION / AVAILABILITY STATEMENT                               12b. DISTRIBUTION CODE

Approved for public release; distribution is unlimited.

13. ABSTRACT (maximum 200 words)

As today’s Army moves further into the Information Age and its mission evolves into a
CONUS-based, Force Projection Army with diverse mission requirements, the ability to collect
and disseminate lessons learned never has been more important. Units must be able to use the
lessons of those soldiers who have preceded them in order to maximize force multipliers,

execute missions right the first time, and save lives.
    This research evaluates the impact that the implementation of an Information Technology

infrastructure has had on the efficiency of Army’s Lessons Learned Process and the overall
effectiveness of the Center for Army Lesson Learned to conduct its primary mission. The
objective is to determine how Information Technology has changed the organizational
structure, culture, reward systems, processes, and personnel skill requirements within CALL.

              Research includes an in-depth review of CALL as the Army’s mechanism for
creating organizational learning, a description of the Lessons Learned Process, an efficiency
comparison between the current and previous collection, an analysis of dissemination processes

using Extend Simulation Software, and an explanation of the organization’s current IT

architecture.

14. SUBJECT TERMS Leaming Organization, Information Technology, Organizational Design, | 15. NUMBER OF

Center For Army Lessons Learned, IT Architecture, CALLCOMS                                          PAGES 146

                                                                                                    16. PRICE CODE

 17. SECURITY               18. SECURITY                                 19. SECURITY               20. LIMITATION
  CLASSIFICATION OF         CLASSIFICATION OF THIS
  REPORT                                                                 CLASSIFICATION OF ]} OF ABSTRACT
                            PAGE
              Unclassified                                               ABSTRACT
                                          Unclassified
NSN 7540-01-280-5500                                                     Unclassified               UL

                                                                                       Standard Form 298 (Rev. 2-89) ,

                                                                                       Prescribed by ANSI Std. 239-18


---

THIS PAGE INTENTIONALLY LEFT BLANK
                                             i


---

                         Approved for public release; distribution is unlimited.

 IMPACT OF THE IMPLEMENTATION OF INFORMATION TECHNOLOGY
                       ON THE CENTER FOR ARMY LESSONS LEARNED
                                                        Anthony M. Wizner
                                                        Captain, U.S. Army
                                     B.S., United States Military Academy, 1991

                                         Submitted in partial fulfillment of the
                                                requirements for the degree of

MASTER OF SCIENCE IN INFORMATION TECHNOLOGY MANAGEMENT

                                                                   from the

                                        NAVAL POSTGRADUATE SCHOOL

                                                        March 2001

Approved by:     7 ationsMi, izner

              Lads Love
                                 ansen, Thesis Advisor

                   Mor Keatlegn_

                  Shelley Gotlup;’ Second Reader

               220 Be
                      Dan C. Boger, Cifairniar

              Information Systems eae Group

              ili


---

THIS PAGE INTENTIONALLY LEFT BLANK
                                              iv


---

                                                   ABSTRACT

          As today’s Army moves further into the Information Age and its mission evolves
into a CONUS-based, Force Projection Army with diverse mission requirements, the
ability to collect and disseminate lessons learned never has been more important. Units
must be able to use the lessons of those soldiers who have preceded them in order to
maximize force multipliers, execute missions right the first time, and save lives.

          This research evaluates the impact that the implementation of an Information

Technology infrastructure has had on the efficiency ofAmy’s Lessons Leamed Process

and the overall effectiveness of the Center for Army Lesson Learned to conduct its
primary mission. The objective is to determine how Information Technology has
changed the organizational structure, culture, reward systems, processes, and personnel

skill requirements within CALL.

          Research includes an in-depth review of CALL as the Army’s mechanism for
creating organizational learning, a description of the Lessons Learned Process, an
efficiency comparison between the current and previous collection, an analysis of

dissemination processes using Extend Simulation Software, and an explanation of the

organization’s current IT architecture.


---

THIS PAGE INTENTIONALLY LEFT BLANK
                                             vi


---

              TABLE OF CONTENTS

INTRODUCTION                                     1

A  BACKGROUND.                                   1

B. RESEARCH QUESTIONS                            3

C. SCOPE AND METHODOLOGY                         4

D  ORGANIZATION OF THE STUDY                     5

E. BENEFITS OF THE STUDY                         6

Il. BACKGROUND OF THE ARMY LESSONS LEARNED PROCESG............7

A  ORIGINS OF LESSONS LEARNED PROCESS            7

B. ADOPTION OF THE AFTER ACTION REVIEW           8

C. ESTABLISHMENT OF A NATIONAL TRAINING CENTER....... 10

D  THE CREATION OF CALL                          12

E  CALLS INCORPORATION OF INFORMATION

   TECHNOLOGY                                    16

F. SUMMARY                                       18

Iii. CALL’s ORGANIZATIONAL STRUCTURE             21

A. CALL’S MISSION AND KEY FUNCTIONS              21

B. ORGANIZATIONAL ENVIRONMENT                    22

   1.  United States Army Forces Command (FORSCOM). ........... 22

   2.  United States Army Training And Doctrine

       Command (TRADOC)                          23

   3   United States Army Combined Arms Center (CAC). ............ 24

   4   The Department of the Army (DA).          25

   5.  U.S. Congress/General Accounting Office (GAO). ........-..0000 25

C. ORGANIZATIONAL STRUCTURE                      27

   1.  1990 Functional Configuration.            27

   2.  1993 Reorganization To Divisional/Product Configuration. ...28

   3.  1996 Reorganization to Support the Information Age. .......... 30

D. SUMMARY                                       35

IV. LESSONS LEARNED METHODOLOGY                  37

A. ROLE OF A LEARNING ORGANIZATION               37

B. THE ARMY AS A LEARNING ORGANIZATION           38

C. WHAT ARE ARMY LESSONS LEARNED?                42

D. CALL’S LESSONS LEARNED SYSTEM                 43

   1.  Mission Analysis and Planning.            43

   2.  Deployment and Linkup.                    45

   3.  Collection Operations.                    46

   4,  Analysis.                                 48

   5.  Distribution and Archiving                50

E. SUMMARY                                       53

                               Vil


---

V.  INFORMATION TECHNOLOGY AT CALL                                  55

    A.  IT ARCHITECTURE                                             55

    B.  CALL’S 3-TIER ARCHITECTURE                                  56

        1.    Tier One.                                             57

        2.    Tier Two                                              58

        3.    Tier Three.                                           59

    C.  CALLCOMS SOFTWARE                                           61

    D.  CALL GATEWAY WEBSITE AND LAN                                63

    E.  SUMMARY                                                     64

Vi. ANALYSIS OF CALL’S ORGANIZATIONAL DESIGN                        65

    A.  GALBRAITH'S STAR MODEL                                      65

    B.  KEY ENVIRONMENTAL FACTORS                                   66

    C.  STRATEGY, TASKS, AND TECHNOLOGY                             67

    D.  STRUCTURE                                                   72

    E.  PEOPLE                                                      76

    F.  REWARD SYSTEM                     ;                         78

    G.  CULTURE                                                     81

    H.  INFORMATION AND DECISION PROCESSES                          84

    I.  SUMMARY                                                     89

VII. CONCLUSIONS AND RECOMMENDATIONS                                91

    A.  CONCLUSIONS                                                 91

    B.  RECOMMENDATIONS                                             95

APPENDIX A. SIMULATION MODELS OF CALL’S COLLECTION PROCESS

    AND USER ACCESS TO THE CALL DB                                  99

    A.  EXTEND SIMULATION SOFTWARE                                  99

    B.  GENERAL MODEL ASSUMPTIONS                                   100

        1.    Collection Process Models.                            100

        2...  Database Access Models.                               100

    C.  CALL OBSERVATION COLLECTION PROCESS MODEL

        USING INFORMATION TECHNOLOGY                                101

        1.    Purpose                                               101

        2.    Key Tasks Depicted in the Model.                      101

        3.    Explanation of Key Task Blocks and the Data Used for

              Each Task.                                            102

              a.  Observation Collection                            102

              b.  Draft CALLCOMS Form.......                        102

              c.   Review Observations by CAAT Team Chief............000 102

              d.  Returned to CAAT SME for Refinement. .....1.sssesseeeoes 103

              é.  Analyst Review.                                   103

              f   Analyst Input into CALLCOM DB.                    104

    D. CALL OBSERVATION COLLECTION PROCESS BEFORE USING

        INFORMATION TECHNOLOGY                                      104

        1.    Purpose.                                              104

        2.    Key Tasks Depicted in the Model.                      104

                                   Vili


---

    3.  Explanation of Key Task Blocks and Data Used for

        Each Task.                                         105

                    Observation Collection                 105

        SA          Draft Observation Manual Form.         105

                    Review Observations by CAAT Team Chief.....0+..00.0000 106

        A D         Returned to CAATSMEfor Refinement. ......s..-0.-s0s00e 106

                    Analyst Review Observation.            107

        A N         Observation Typed by CALL              107
E. USER ACCESS TO LESSONS IN CALL DB USING CURRENT
    INFORMATION TECHNOLOGY                                 108

    1.  Purpose                                            108

    2.  Key Tasks Depicted in the Model.                   108

    3.  Explanation of Key Task Blocks and Data Used for

        Each Task.                                         109

        a.          CALL Web Page Receives a Request.      109

        b.          User has Access.                       109

        c.          Requests Password Be Issued.           109

        d.          Search Database.                       110

        e.          Download Product.                      110

F. USER ACCESS TO LESSONS PRIOR TO
         CURRENT INFORMATION TECHNOLOGY ARCHITECTURE110

    1.  Purpose.                                           110

    2.  Key Tasks Depicted in the Model.                   111

    3.  Explanation of Key Task Blocks and Data Used for

        Each Task.                                         111

        a.          CALL Receives a Requestfrom a Client. .....1.sseeseresooes 111

        b.          Analyst Searches for Information.      112

        C.          Information Sent to User via US Mail.  112

G. SIMULATION RESULTS                                      112

APPENDIX B. SURVEY OF CALL CLIENTS                         115

A.  SURVEY DESIGN                                          115

B. SELECTION OF RESPONDENTS                                115

Cc. SURVEY INSTRUMENT                                      116

    1.  Section One                                        117

    2.  Section Two                                        117

    3.  Section Three                                      118

D. SURVEY RESPONSE STATISTICS.                             118

LIST OF REFERENCES                                         12]

INITIAL DISTRIBUTION LIST                                  125

                                      ix


---

THIS PAGE INTENTIONALLY LEFT BLANK


---

            LIST OF FIGURES

Figure 1.   Army Lesson Learned Structure. 00.0... ccccesceseceteeeeetseeearseeeenenseessesneeeees 22
Figure 2.   CALL Organizational Chart 1993-1996 .........csesseessssseeeeeereeeteceeeneeseenens 29
Figure 3.
Figure 4.   Present CALL Organizational Chart ...........:cccscssesseseseeeeeceeseseeeneeeseeseese 32
Figure 5.   Boyd's OODA Loop. ......sccccecsesecesesetessessesenenensnssneeneeeeaenensnenenseseeesenensenene 38
Figure 6.   CALL's IT Architecture 0.0... ccc cecceseecesseeecesersseseeseeenseseressessaseneeneseeeeeas 56
Figure 7.   Galbriath's Star Model ...............ccecccssecsecsscescesecetsessaaeesecssseessesnaseeneeentenenees 65
Figure 8.   CAAT Observation Collection Process W/ IT .......cccsseeescesseeeeeeseeenereees 101
Figure 9.   CAAT Observation Collection Process W/o IT .0......ceecceesseseeeseeseeeeetneeee 105
Figure 10.  User Access to CALL DB wW/ IT ...0...eececeeceeseeseeeseeseeesesseneeeseeseeeneceneaeees 108
Figure 11.  User Access to CALL Lesson Learned W/o IT oo... e eee cceeeeeeeeeeeneeeteeee 111
Figure 12.  Section Two of User Servey .........:ccsccsscseesseeescssesscerseatenseessenneeseerseenserseees 117
            Section Three of User Survey ...........cccccesccseessesescesenssnseneeenseeseneeseeeennenees 118

            Xi


---

THIS PAGE INTENTIONALLY LEFT BLANK
                                            Xi


---

          LIST OF TABLES

Table 1.  Extend Collection Process Model Data ...........0.ceccccssssccccssnsececeeeessnneeeees 70
Table 2.  Extend User Access Model Dat .0......ccccccccccsseseccccesscccceensceceessceececesessseseees 71
Table 3.  CALL's Organizational Form .00........ccceeececscessccececeeeseeeereeceeceeesenseeenenssees 72
Table 4   Extend Collection Process Model Data ............ccscscccssccesscceseeseessneeeeenseees 112
Table 5.  Extend User Access Model Dat 0.0... .eecccccceecsescccesscccceesseceessseeeecseressnees 113
Table 6.  Survey Section Two Results For Questions 1-6 .0.......cesesseeceeeeceeneseeee’ 119
Table 7.  Survey Section Two Results For Questions 7-9 ........seeseeecesseeeeeesneeneees 119

          xill


---

THIS PAGE INTENTIONALLY LEFT BLANK
                                           Xiv


---

                                       ACKNOWLEDGMENTS
          I would like to express my sincere appreciation to those individuals who provided

their support throughout this endeavor.

          To Dr. Rick Morris, Dr. Lon Seglie, Dr. Scott Lackey, Ken Vanderpool, James

Willey, and everyone else at the Center For Army Lessons Learned, a special thank you

for taking the time out of your busy schedule to answer my questions and provide me

with a keen insight into your organization.
          I would like to thank Dr. Erik Jansen and Dr. Shelley Gallup for their guidance

and support throughout my research. You both made this an enriching experience and
not just another hill to climb.

          Lastly, I want to complement my wife Catherine, without whose love, patience,
support, and proofreading I could never have finish this work on time.

                                                                                                                    xV


---

THIS PAGE INTENTIONALLY LEFT BLANK

                                            XV


---

                1.  INTRODUCTION

A.  BACKGROUND

          During the later stages of the Cold War, Army Chief of Staff, General Gordon R.
Sullivan, concluded that the National Training Center (NTC) at Fort Irwin was not
achieving its full potential in preparing its forces for combat. While NTC was effective
at generating learning at the individual, team, or platoon level through the use of After
Action Reviews, the real value of the process would be tuming those lessons into
organizational learning. To make the transition from individual learning to
organizational learning required a structured mechanism for sharing this information.
That mechanism would be the lessons learned process.

          To oversee this new mechanism, the Army created the Center for Army Lessons
Learned (CALL) at Fort Leavenworth, Kansas in 1985. CALL was tasked with capturing
the learning taking place at the national training centers and disseminating it throughout
the Army. CALL’s initial focus was to document successful tactics, techniques, and
procedures (TTP). NTC's success at developing combat prepared, CONUS-based heavy
forces, led to the expansion of the training center concept. The Army created the Joint
Readiness Center (IRTC) at Fort Chaffee for light forces, the Combat Maneuver Training
Center (CMTC) at Hohenfels for OCONUS heavy forces, and the Battle Command
Training Program (BCTP) at Fort Leavenworth for division and corps staff officers. As
the Combat Training Center (CTC) base expanded so did CALL to provide the same
repository of lessons learned for all of these centers.


---

            As a result of Operation Just Cause, CALL expanded its charter to include
capturing lessons for actual operations. From the early 1990’s CALL provided collection
teams for all major Operations, including Desert Shield/Desert Storm and Operation
Restore Hope. Although the system for collecting data from the field was judged
effective from the earliest moments, General Sullivan noted that, “CALL produced little
of enduring value during it first several years because the data from the training centers
overwhelmed the paper-and pencil system to analyze and distribute the information.”!

Although CALL confirmed that units often repeated the same mistakes, because of the

long time delay in compiling and distributing the valuable lessons, most units fell victim
to the same pitfalls. In response to this deficiency CALL sought to incorporate the
emerging information technology as a solution.

     In 1993, the CALL Database (CALL DB) was created. The CALL DB allows

soldiers, trainers, and unit leaders to consult the Army’s “corporate memory” with

previously unprecedented speed, accuracy, and thoroughness. Members of the

organization can now either submit valuable pieces of information to CALL for analysis
and input into the “corporate memory” or search the database for information to help
train or prepare their units for combat. The capabilities of this information technology
infrastructure include: scanning documents directly into the database, establishing a
communication link between deployed Combined Arms Assessment Teams and analysts

           1 Gordon R. Sullivan and Michael V. Harper, Hope is Not A Method, Random House, 1996, pg.

208.


---

at Fort Leavenworth, and distributing lessons learned via e-mail, CD-ROM, and web

page links.

          As today’s Army moves further into the Information Age and its mission evolves
into a CONUS-based, Force Projection Army with diverse mission requirements, the
ability to collect and disseminate lessons learned has never been more important. Units
must be able to use the lessons of those soldiers that have preceded them to maximize

force multipliers, execute missions right the first time, and save lives. The objective of

this research is to analyze the efficiency of the IT infrastructure to collect and disseminate
lessons learned to the force and the impact that it has had on CALL effectiveness as an
organization. It will address not only possible improvements to the infrastructure, but

also to the organization as a whole.

B.  RESEARCH QUESTIONS

         The primary research question of this thesis is: How has the implementation of
Information Technology increased the organizational effectiveness of CALL in collecting
and distributing lessons learned to the total army? The subsidiary research questions are

as follows:

          1. What changes in the lessons learned collection process have come about as a
                result of the implementation of Information Technology?

          2. How effective is the information categorized within the CALL DB for access
                 by users throughout the service?

          3. What impact did the implementation of IT have on the organizational size and

                  structure?


---

    4. What changes in skills qualifications of personnel have resulted from the
          changes?

    5. Does the organization have an existing culture that must be overturned to
          successfully implement change?

    6. What changes within the organization would further improve the
          organization’s effectiveness to capture and disseminate lessons?

C.  SCOPE AND METHODOLOGY

            The scope of this case study is limited to the period from the inception of the
Center For Army Lessons Learned (CALL) in 1985 through the present day. Utilizing
this historical time reference, the study analyzes the significant events affecting CALL
and the actions and decisions taken by the organizational director and deputy director to
enable the transformation of the lessons learned process from a paper and pencil system
to one reliant on information technology.

    The methodology used in this thesis is a historical case analysis of the Center for

Army Lessons Leamed. To conduct this case analysis the author conducted personnel

interviews with the organization’s deputy director, branch chiefs, senior analysts, and

Combined Arms Assessment Team members to record their impressions on the

organization and its processes He also conducted a search of the CALL Database to

gather information of previous lessons learned collection processes, organizational

structures, and other data relating to the transformation of CALL. The modeling software

Extend was used to construct a simulation of the organization’s lesson learned collection

process and howa typical user might gain access to information from the organization..
                           4


---

The data from both the pre- and post-implementation simulations were then used as a
comparison of the efficiency of the organization. A survey of mid career company grade
officers is conducted to determine the depth and breath of their knowledge of the various
services that CALL provides. This survey is used to establish CALL’s effectiveness in

disseminating lessons learned to this key customer group.

D.  ORGANIZATION OF THE STUDY

         Chapter I. Introduction: Identifies the focus and purpose of the thesis as well
as the primary and subsidiary research questions.

         Chapter I. | Background of the Army Lessons Learned Process: Provides the
reader with the history of the Army’s Lesson Learned Process from its initial use during
World War II through the formation of CALL and its subsequent transformation to

support the Information Age Army of today.

         Chapter MI. CALL Organizational Structure: Provides the reader with a
detailed explanation of the organization’s stakeholders, pre-IT organizational structure,

and current organizational structure of CALL

          Chapter IV. CALL Lesson Learned Methodology: Provides a detailed
explanation of the process, which CALL uses to capture and disseminate lessons learned

to the total army.

          Chapter V. Information Technology at CALL: Identifies the information
technology that is in place to assist CALL in the lesson learned process.


---

            Chapter VI. Analysis of CALL’s Organizational Design: Provides an abridged
explanation of major components of the Galbraith Star Model for Organizational Design
and analyzes the significant changes to the organization that occurred as a result of the
implementation of information technology using the Galbraith Star Model.

           Chapter VII. Conclusions and Recommendations: Summarizes the findings of
the research and answers the research questions.

E. | BENEFITS OF THE STUDY

            This study provides the necessary information to evaluate the effect the
incorporation of technology is likely to have on an organization. It serves as an example
for other DoD organizations seeking to implement an IT infrastructure to improve their
organization’s effectiveness.


---

      Il. BACKGROUND OF THE ARMY LESSONS LEARNED

                                                      PROCESS
                   “I am tempted to say that whatever doctrine the armed forces are
         working on now, they have it wrong. I am also tempted to declare that it
         does not matter. What does matter is their ability to get it right quickly
          when the need to use it arrives.”2

                                British Historian Sir Michael Howard

A. ORIGINS OF LESSONS LEARNED PROCESS
         As early as World War Il, the Army attempted to increase its organizational

learning by creating mechanisms for sharing and adopting lessons from the battlefield in
an effort to save lives. In World War I, General Marshall directed his chief of military
history to collect what was being learned by soldiers in the Pacific and European Theater
and to provide these lessons to the training base of new recruits back in the United States.

Although the process that General Marshall adopted did not survive the war, the idea of

using “lessons learned” would subsequently be revived during both the Korean and
Vietnam Wars.2 Because of the informality of the collection, analysis, and dissemination
process of the era, the impact and significance of the lessons learned process could not be
measured, but the idea behind it would remain a valuable part of the Army’s institutional

background.

            2 Ibid. pg. 190.
           3 Tbhid. pg. 204.


---

B.  ADOPTION OF THE AFTER ACTION REVIEW

            Based on the value added by the previous wartime lessons learned collection
processes, the Army sought a new system to improve its performance and organizational
learning during times of relative peace. By the mid 1970’s, the Army’s mechanism for
collecting and disseminating lessons consisted of the After Action Review (AAR). The
AAR was developed under the guidance of Training and Doctrine (TRADOC)

Commander General William E. DuPuy. It was designed to be a structured method to

facilitate learning by individuals or small units from the complex experiences that result
from their tactical operations or training.4 The AAR had three fundamental purposes:
learning, improving, and doing it better the next time. The AAR process was to take
place after every training event and would follow a standard structured format. The
AAR would address three questions:

                   e What happened?
                   e Why did it happen?
                   e What should we do about it?

The structure of the AAR was formally outlined in the Army Training Circular 25-20, A

Leader’s Guide to After Action Reviews. Fifty percent of the total available time was
allocated to answering the first two questions and the remaining time to answer the final
question.

             The participants of the exercise would sit down with an Observer Controller
(OC) who monitored the unit’s performance throughout the exercise and lead a

    4 Thid. pg. 190.


---

discussion on the events that had transpired. Using the unit’s intended plan and doctrine
as the base of reference, the group would talk about the events that unfolded in an effort
to improve unit proficiency. They were not to focus on individual performance, position,
or rank of the participants. The OC was designated to foster a non-threatening
environment in which all members of the organization were highly encouraged to
participate no matter what their rank or experience level. The AAR was not intended to

fix blame, but to truthfully discover why things happened the way they did and to identify

areas for sustainment or improvement. This structured, open discussion process not only
promoted learning, but facilitates honest feedback, organizational member buy-in, and
trust in the unit. At the tactical level, the AAR provided a dynamic link between
executing a task to standard and developing TTPs. Soldiers quickly understood when
they did not perform a task to standard and what actions should be modified to improve
proficiency. Leaders could then use the information to assess performance and retrain

units as necessary.

         Within 10 years of its intimation, the AAR process had become embedded into
the Army’s culture because of its focus on improvement without fixing or allaying
blame.’ Its value had been accepted, and its use spread to activities other than training.
Over time the Army became increasingly reliant on the use of the AAR to assess its
combat unit capabilities and preparedness for combat.

            5 Tbid. pg. 192.


---

Cc.  ESTABLISHMENT OF A NATIONAL TRAINING CENTER

            Since 1979, the Army had repeatedly petitioned the U.S. Congress to permit the
creation of a training center that would allow it to “isolate and resolve recurring problems
that have an Army-wide impact.” In April of 1979 TRADOC published the NTC
Development Plan, which stated that a key aspect would be its impact on developing
lessons learned for the force and assessing training, doctrine, and equipment requirements
for the Army. In 1981, the Army established the NTC at Fort Irwin, Califorma. The
NTC was to offer individual soldiers and units a training environment that closely
paralleled that of actual combat; this provided an opportunity that was not currently
available at home stations.’ The training would consist of force-on-force engagements
against an Opposing Force (OPFOR).® The training center used objective data recorders
such as audio from radio transmissions, video from cameras located throughout the battle
space, and digital input from the Multiple Integrated Laser Engagement System for real
time assessment of personnel and vehicle casualties to provide feedback to units. In

           6 Army Training: National Training Center’s Potential Has Not Been Realized,
GAO/NSIAD 86-130, 23 July 1986, pg. 14.

           7 bid. pg 8.

           8 The OPFOR, consisting of about 1500 personnel, is designed to replicate a
Soviet motorized rifle regiment. Soviet style tactics and U.S. vehicles modified to look
like soviet vehicles are used during force-on-forces simulated engagements. The NTC
requires units to conduct training in eight different battle scenarios, which include
offensive and defensive operations in day and night. The scenarios are changed for each
training rotation so that NTC presents a different challenge to soldiers who have been to
NTC previously.

                                                                                   10


---

addition, a qualitative assessment of unit performance was provided by 126 OCs who
watched and recorded events and provided feedback to small units in the form of AARs.

          By the mid 1980’s, the Army extended the success they had at the NTC by

developing three additional major combat training centers. The CMTC at Hohenfels,
Germany is where United States Army Europe (USAREUR) units train heavy

mechanized infantry and armored brigades in a fashion similar to the NTC. JRTC at Fort
Polk, Louisiana is used by light forces for Low/Mid-Intensity Conflict, and BCTP at Fort
Leavenworth, Kansas is designed to provide command and control training for division
and higher battle staffs.2 As the Army’s forces trained at these centers and were
evaluated on their ability to conduct their wartime missions, senior leadership began to
receive feedback that units were repeating many of the same mistakes during maneuver

exercises.

         A Government Accounting Office study of the effectiveness of the NTC in 1986
discovered that lists of training trends compiled in March 1982 and in 1985 “showed
many of the same problem areas.”!9 Some of these recurring mistakes could have had
serious consequences on a real battlefield; these included fratricide incidents and
operational inabilities in a Nuclear, Biological, Chemical (NBC) environment. Most of
the mistakes were identified and corrected using the current AAR system in specific
units, and these would not be repeated during the ongoing rotation. However, the same
corrections had to be made when the next unit arrived at the training center. This pattern

          9 Army Training: Prioritizing and Follow up on Lessons Learned Should
Minimize Recurring Weaknesses, GAO/NSIAD 93-231, 16 September 1993, pg. 1.

           10 hid. Pg. 21.

                                                                                   1


---

depicted a system that promoted individual learning but little organizational or
institutional learning.

           GAO concluded that the fundamental reason behind the failure to develop Army-
wide lessons learned was that the primary emphasis was directed towards the training
aspects of the NTC and providing units with immediate feedback. In addition, according

to Army officials, the service still had not determined what analysis or data were required

to develop lessons learned. The Army schools that were responsible for training and
doctrine development had not been required to define the data necessary to fully evaluate
training or doctrine effectiveness.!! Overall, the GAO concluded that the lack of a
systematic method to collect, process, and distribute lessons learned was causing the
NTC not to fulfill a major portion of its intent.

            To make the transition from an individual learning process to an organizational
learning process, the Army Chief of Staff directed TRADOC to develop a systematic way

to obtain information from the NTC exercises. In December 1985, TRADOC assigned

this mission to the U.S. Army Combined Arms Center (CAC) at Fort Leavenworth.

D. THE CREATION OF CALL
            Although the use of the AAR and the NTC had become the cornerstones for the

Armmy’s effort to improve its ability to collect lessons learned, it had a fundamental flaw.
Their design was to create learning at the small unit level; they could not, on their own,
transfer these lessons across the entire organization. The realization of this shortcoming

            11 GAO/NSIAD 86-130, pg. 15.

                                                                                      12


---

by senior Army leaders, especially in the aftermath of Operation Urgent Fury, resulted in
the desire to develop a mechanism to permit sharing lessons across the entire Army. This
new mechanism would be achieved through the creation of the Center For Army Lessons
Learned (CALL) in late 1985. CALL would be tasked with collecting and consolidating
the subjective assessments from the NTC and major exercises into one central location.
They would analyze them to identify trends, identify training problems and their causes,
prioritize recurring problems, develop or assign proponents to develop solutions to

them. !2

          CALL developed the Lesson Learned Process to achieve these tasks. The process
included data collection using a variety of sources, including AARs, audio and video
transmissions, and the evaluations of observers at the training centers. This process

relied heavily on creating a standardized datalobservation collection format that was used

during an NTC rotation or major training exercises. CALL required any observation to

follow a new standard trip report format. They also focused the attention of observers on

selective issues that CALL was attempting to analyze. Before this standardization, the
Army schools had been sending Subject Matter Experts (SMEs) to the NTC to observe
exercises and evaluate the training rather than requiring them ‘to document specific
observations. In addition, the evaluation reports had been so general and unstructured
that they provided little value or usefulness. Once data was collected, CALL
consolidated them and conducted analyses for trends and deficiencies. It then published
the results of its analyses in quarterly bulletins and newsletters that were sent to each of

           12 Thid. pg. 22.

                                                                                   13


---

the TRADOC schools and tactical organizations throughout the Army. The TRADOC
schools and tactical organizations were ultimately responsible for using CALL’s input to
modify training or doctrine!3.

            By 1989, the Army had quickly recognized the need to expand the lessons learned
process to function in the event of combat operations. To meet this expanded role, CALL
developed the Wartime Lessons Learned Program (WALLP). WALLP was later
synthesized with the NTC and major exercise collection process in AR 11-33, Army
Lessons Learned Program: System Development and Application, to establish a system
for collecting and analyzing all field data and disseminating and archiving lessons from
actual Army operations and training events. CALL conducted its first combat operation
collection effort in December 1989, when Operation Just Cause began in Panama.!4 The
system outlined by AR 11-33 consisted of a 6 phase process: Plan, Collect, Analyze,

Publish, Distribute, and Archive with a stated goal of “getting the information into the
hands of soldiers and units to help them perform their mission right the first time.”!5

             When the GAO conducted a follow-up assessment of the effectiveness of CALL
in 1993, they found that “Despite the lessons learned program, Army units are still
repeating the same mistakes during maneuver exercises at the combat training centers.”’!6
The underlying problem of recurring mistakes was found to be two fold. First, TRADOC

      13 GAO/NSIAD 93-231, pe. 2.

            14 CALL Handbook 97-13, pg. 1.
            15 Tbid.
           16 GAO/NSIAD 93-231, pg. 2.

                                                                                   14


---

and CALL, in particular, did not assign priorities to the lessons learned when it provided
them to the schools. The lessons were provided to the school as information to use as
they wished. By not tracking the extent to which the schools modified their training or
doctrine to incorporate the lessons learned, TRADOC was not enforcing one of the key

components of organizational learning.

         Underscoring the importance that TRADOC’s emphasis had on fostering

organizational learning, the GAO highlighted a case where CALL had continued to

identify fratricide-related problems recurring at the NTC. In 1989, CALL issued a plan
to correct these deficiencies in six key areas; they assigned specific actions and
responsibilities to be taken by the various schools and tactical organizations. By the
onset of Operation Desert Shield, most of the responsible organizations either did not

carry out the specified actions or could not document what actions they had taken. As a

result of the numerous incidents of fratricide that resulted during Operation Desert Storm,

renewed interest in these areas arose, and the Combined Arms Command issued a new
plan to incorporate all of the key areas addressed in the original 1989 plan, plus two
additional areas. This time, with TRADOC’s pressure, the Army more aggressively
implemented the plan. As a result, data from the mid 1990’s shows a vast decrease in

fratricide-related problems at the NTC.

          The second key problem that contributed to CALL’s ineffectiveness was, as
General Sullivan noted, “the data from the training centers and actual operations
overwhelmed our pencil-and-paper system.” !7 CALL’s analysts were trying to take

           17 Sullivan, pg. 208.

                                                                                     15


---

thousands of AARs, audio and video data, and trip reports and condense them into its
bulletins. In the process, although they were providing insights into how to overcome
deficiencies, they also were aggregating data to such a high level that it tended not to be
useful.!8 Aside from this problem, the slowness of the manual lessons learned process
often prevented timely information flow to the schools or field, and it limited the ability
of units to request information on specific problems outside of those addressed by the
standard CALL bulletins. In an effort to overcome the shortfalls in meeting the original

goal of getting the information into the hands of soldiers in a timely manner, CALL

sought to leverage the use of information technology.

E. CALL’S INCORPORATION OF INFORMATION TECHNOLOGY

      From the earliest moments of the information technology revolution, CALL has

sought ways to increase its ability to meet its primary goal. Shortly after Operation
Desert Shield, CALL undertook a test bed program to automate the archiving phase of
the lessons learned process. With the support of the TRADOC Commander, CALL
established the Automated Historical Archives System (AHAS) to electronically archive
lessons learned into a vast database. This system not only would increase the ability to
access information, but also assist in the Army-wide dissemination of numerous historical
and new lessons learned documents from the Gulf War. By early 1993, this system was in
operation and provided a valuable asset to the Army.

           18 Thid.

                                                                                   16


---

       The success of this system was evident during the 10" Mountain Division’s (10

MD) deployment to Haiti in September 1994. Once the unit was alerted to prepare to
deploy, CALL was able to search its database and create a tailored soldier’s handbook for

operating in that environment. Information included preventive medicine for the tropics,
crowd control techniques, tips for dealing with local officials, and tactics and small unit

procedures for Urban Operations. These handbooks were produced quickly and sent to

the units use during pre-deployment training at home station. ‘This effort enabled the

Amny to significantly increase the effectiveness of the division once in theater. As a
comparison, when this same unit deployed to Somalia just two years earlier, CALL was
unable to provide any real value added prior to the deployment.

          CALL also sent collection teams to Haiti to capture the knowledge being gained

everyday by soldiers of the 10" MD while deployed. This knowledge was then

transferred to troops from the 2°° Cavalry Regiment (Light) and 25" Infantry Division

(25"TM ID) through updated handbooks based on the current situation in Haiti, feedback
from the 10” Mountain Divisions soldiers, and updated Rules of Engagement. CALL's

lessons also were incorporated into the creation of a training environment that simulated

Haiti-like conditions at the JRTC to prepare follow on forces prior to their rotation into

the country. !9 In fact of the 26 scenarios CALL developed for the 25" ID to use during

their pre-deployment training, 23 were actually faced by units of the command during

their 6 months in Haiti. One soldier from the 25" ID responded to a reporter from CNN

           19 Sullivan, pg. 204-205.

                                                                                     17


---

that a mission had been so successful and smooth, “Because I have already executed this
mission 20 times before [actually getting here].”2°

            CALL’s success in assisting the improved operational performance of units
deployed to Haiti resulted in the CAC Commander’s expansion of the test program to
incorporate the integration of Information Technology throughout the lessons learned
process. The expansion of automation included the use of databases, computers, servers,

e-mail, FTP, and other on-line technologies to assist in the reporting and dissemination

of lessons learned to the total Army. The goal of CALL was to refocus to “ensure the
Army receives timely and relevant feedback required to achieve victory in the
Information Age.” 2!

F.  SUMMARY

            Since the late 1940’s, the Army has realized the importance of having a
mechanism to facilitate the transfer of lessons learned on the battlefield to its training
base in an effort to save lives. In 1985, the Army created the Center for Army Lessons
Learned to oversee this function. CALL was tasked as the organization responsible for
collecting observations, transferring them into relevant lessons, and then disseminating
them to the force. By the mid 1990’s, CALL’s existing lessons learned process had been
overwhelmed with the amount of data that it was collecting; it therefore sought to

           20 Lloyd Baird and John C. Henderson. “Learning From Action: An Analysis of
the Center for Army Lessons Learned”, Human Resource Management, Winter 1997,

Volume 36, pg. 387.

            21 call.army.mil/call/homepage/history.htm pg 1.

                                                                                      18


---

leverage Information Technology as a possible solution.  |The automation of the

collection process proved invaluable in preparing forces for Operation Restore Hope and

soon was developed as a means to support all of the organization’s key functions.

19


---

THIS PAGE INTENTIONALLY LEFT BLANK
                                             20


---

              Ill. CALL’S ORGANIZATIONAL STRUCTURE

                    “The Army has perfected a remarkably efficient process for
         correcting its mistakes and sustaining its successes.”??

          CALL’S MISSION AND KEY FUNCTIONS

         Almost since CALL’s inception in 1985, it has maintained the same primary
mission: to collect, analyze, and disseminate timely and relevant lessons learned, tactics,
techniques and procedures (TTPs), research material and security assessments to Army
units around the world.23 To satisfy this mission it must conduct the following key
functions: collect relevant observations, analyze observations and develop lessons
learned, disseminate lessons in a timely manner, act as an agent for change, maintain a
historical file of all lessons learned and AARs, and recommend changes to doctrine,
training, organization, material, and leadership (DTOML).*4 By fulfilling these core
functions, CALL not only could improve individual learning and performance, but more
importantly serve as the mechanism for developing organizational learning in the Army.

         22 Thomas E. Ricks, “Lessons Learned: Army Devises System To Decide What
Does and Does Not Work”, The Wall Street Journal, 23 May 1997, pg. Al.

          23 Center for Army Lessons Leamed, http://www.call.army.mil/call/homepage.
          241990 CAC Annual Command Histories, Center For Army Lesson Learned, pg.

94.
                                                                                  21


---

B. ORGANIZATIONAL ENVIRONMENT
            One of the key aspects that effect the performance of an organization is the

environment in which it operates. The environment comprises elements outside the
organization, including stakeholders, that may influence the ability to accomplish key
goals. These elements can affect the organization by making demands or placing
constraints on it.25 The CALL’s environment includes the following key stakeholders:
FORSCOM, TRADOC, CAC, and the United States Congress/GAO. (Figure 1)

                                                                         Army Lessons Learned Structure

                                       Figure 1. Army Lessons Learned Structure
             1. United States Army Forces Command (FORSCOM)
            FORSCOM, whose mission is to train, mobilize, deploy, and sustain combat
ready forces capable of operating in a joint and combined environment, is the warfighting
arm of the Army. Through its responsibility to train over 760,000 active and reserve
soldiers for combat, FORSCOM is the main user of the services that CALL provides.
Not only is it CALL’s biggest client, but it also is the source of its data.

           25 David A. Nadler and Michael Tushman. “Organization, Congruence, and
Effectiveness”, Organizational Dynamics, Autumn 1980, pg. 96.

                                                                                   22


---

           FORSCOM is also responsible for the operational control of the Combat
Training Centers. It is through the observation of FORSCOM units at the Combat
Training Centers, major training exercises, and during actual operations that CALL is
able to gather lesson learned. FORSCOM’s influence on CALLis its ability to identify
which exercises or operations require Combined Arms Assessment Teams (CAAT) and

specify collection requirements on an issue. This shapes the scope of CALL’s collection

effort, which in turn effects the products that are produced for the Army.?6

          2. United States Army Training And Doctrine Command (TRADOC)
          TRADOC is charged with the major Army missions of individual training and
combat development. This vast task places “the development of the Army’s tactical
organizations, weapons, equipment, doctrine, and the training of soldiers in that doctrine,

in one command.”27 Individual training, for both officers and enlisted soldiers, is

conducted through the military education system, which consist of 18 TRADOC
monitored military specialty schools located throughout the United States. The
responsibility for doctrine development is divided between the levels of TRADOC’s
hierarchy. TRADOC headquarters, located at Fort Meyer, Virginia, writes strategic level
doctrine; Combined Arms Center, located at Fort Leavenworth, writes Corps and
Division level doctrine; proponent school headquarters write branch specific Field

Manuals.

          26 Center for Army Lessons Learned Handbook 97-13, United States Army
Combined Arms Center, Fort Leavenworth, Kansas, pg. 10.

           27 Chapman, Anne W., Carol J. Lilly, John L. Romjue and Susan Canedy, Prepare
The Army For War: A Historical Overview of the Army Training and Doctrine
Command 1973-1998, Military History Office, United States Army Training and
Doctrine Command, Fort Monroe, Virginia 1998, pg. 14.

                                                                                   23


---

            TRADOC’s requirement to develop doctrine has a significant impact on CALL’s
ability to conduct their mission. When CALL identifies lessons learned that are linked to
problems in individual training or doctrine, it provides that input to TRADOC for action
by the proponent organization. TRADOC then holds the school accountable for
correcting these deficiencies by incorporating them into training or doctrine
modifications. As TRADOC prepares the Army for the future, through the development

of new doctrine, such as Force XXI or the Army After Next, they use the collection and

analysis functions of CALL to provide feedback about the feasibility of the doctrine.
               3. United States Army Combined Arms Center (CAC)

            The mission of the Combined Arms Center (CAC) is to educate officers in the art
of command and staff functions of the combined arms at the tactical level and to educate
officers in the operational art of war.28 CAC has a training development function for
battle command staff and experimenting with concepts, methods, procedures and means
of battle command. CAC is one of the proponent organizations under the control of
TRADOC and has the tasks of writing the doctrine for war fighting at the division and
corps levels. CAC is also the higher headquarters for CALL within the TRADOC
organizational hierarchy.

            When CALL identifies lessons learned that are linked to problems at the tactical
doctrine level, it provides that input to CAC for correcting these deficiencies by
incorporating them into training or doctrine modifications. Since CAC also is
responsible for providing the training exercise scenarios for BCTP, they can effect the

           28 www.army.mil.cac/mission/mission.html

                                                                                   24


---

scope of CALL’s lessons learned process by dictating what issues require collection and

analysis.
           4. The Department of the Army (DA)

          Through its tasking authority, the Department of the Army provides the impetus
for CALL to initiate its active collection operations in support of actual operations or
major training exercises. This key power grants CALL two important items:
authorization and funding. First, the Department of the Army will generate a support
tasking to furnish CALL with not only the CAAT Team Chief, but official authorization
to request CAAT team members from the relevant TRADOC proponent schools. This
formal tasking is a binding requirement to TRADOC to temporarily assign qualified
personnel to CALL to assist the upcoming collection mission. Secondly, and most

importantly, once a formal tasking comes from DA, it also appropriates the budgetary

funds that will be used by CALL in support of the collection effort. Without the granting
of these additional funds, CALL does not have an operating budget to actively collect
data. Because of the DA’s power to control CALL’s ability to generate and fund its
collection efforts, it has enormous impact on what events and issues CALL undertakes.
This allows the DA to shape the corporate learning mechanism to focus on issues that it

sees most important.
           5. U.S. Congress/General Accounting Office (GAO)

          Since the U.S. Congress is responsible for appropriating funds to all DoD
programs, it has a significant impact on CALL’s personnel, equipment, and collection
effort. Congress employs the GAO to: examine the use of public funds, evaluate federal
programs and activities, and provide assistance with oversight, policy, and funding

                                                                                     25


---

decisions.2? As a result, GAO works to continuously improve the efficiency and
effectiveness of the Department of the Army through program reviews.

            It is in this context that the GAO has sought to assess the overall impact that the
CALL Lessons Learned Process has had on the Army. Once an evaluation is made, the
GAO fumishes a report to the Executive or Legislative Branch member that has

requested the service. They can then use this report to justify funding, expand CALL’s

mission, or make other determinations as appropriate.

           The geopolitical realities that now face the United States Army also are critical to
understanding CALL’s environment. When CALL was founded in the mid 80’s, the
Army was structured both organizationally and doctrinally to counter the threat posed by
the Soviet Union. The Army was expected to be prepared to fight a high intensity
conflict in the European or Korean theaters against a known enemy using understood and
well documented tactics. The task of CALL was finding trends in training deficiencies
and creating tactical level solutions. Time was not a factor in the development and
dissemination of these solutions.

            After the collapse of the Soviet Union; new geopolitical realities exist. The Army
has to counter many different threats along the conflict continuum including
peacekeeping operations, mid-intensity conflicts, humanitarian relief, terrorism and
cyberterrorism. Speed in the collection and dissemination of lessons learned to the total
Army is now paramount. In addition to rapidly collecting and disseminating lessons
learned, CALL must tailor training packages to FORSCOM prior to the deployment of

           29 www.ga0.gov

                                                                                     26


---

forces and to TRADOC for necessary adjustments to strategic and tactical level doctrine

to counter this extensive expansion of threats.

C. ORGANIZATIONAL STRUCTURE
           1. 1990 Functional Configuration
          From its inception in the mid-1980’s, CALL has undergone many organizational

changes. Initially CALL was developed to capture lessons learned from the Combat

Training Centers. By 1989 senior Army leadership realized that CALL also should
support on going combat operations to identify lessons being learned by deployed

fighting forces. As a result of this expansion of its mission, CALL was reorganized by
functionality, in 1990. CALL’s basic organizational structure consisted of four major
divisions: Collections, Analysis, Processing, and Dissemination.3? Additionally, an
Operations cell at Fort Leavenworth ran the day to day operations of CALL, while small
observation divisions at each of the CTCs supported units conducting training.

          The Operations cell consisted of the director, deputy director, and two secretaries.
They were responsible for distribution, budgeting, tasking and tracking ongoing
collection efforts, as well as administrative and logistical support of the organization.
The Collections division consisted of two sections. The Combined Arms Assessment
Teams collected observations from on going major exercises and actual operations, and
the Wartime Lessons Learned Program (WALLP) collected after-the-fact interviews on
Operation Desert Shield/Desert Storm. Because of senior Army leaderships desire to

          30 1989 CAC Annual Command Histories, Center For Army Lesson Learned, pg.

191-192.
                                                                                   27


---

document all aspects of the conflict in the Persian Gulf, CALL’s WALLUP section’s
authorization was increased an additional 40 personnel to assist in this effort. The
Analyst division consisted of 9 civilian analysts who were charged with transforming the
observations from the Collection division into lessons learned. Those observations that
were deemed relevant by the analyst were identified and grouped under a particular
Battlefield Operating System (BOS) and were provided as input to future products and

publications. The Processing division was accountable for the production of all initial

impression reports, final reports, newsletters, articles, training vignettes, handbooks, and
exportable training packages. The Dissemination division had the primary responsibility
to provide all CALL products to evaluated units, the organizational stakeholders, and the
historical archives.

         2. 1993 Reorganization To Divisional/Product Configuration

            In 1993, responding to the increasing demand on the Army, CALL underwent
another reorganization. The reasons for this were threefold. Firstly, to increase
effectiveness through analysis. Secondly, to adjust the organization to meet the steadily
increasing missions without an increase in personnel. Lastly, to focus on the
development and implementation of automated data systems. CALL was separated into
three major divisions: Collection, Analysis, and Information Systems (Figure 2). This
would transform the organization from a functional organization to a product
organization. The reorganization upgraded each division chief to Lieutenant Colonel and
allowed each a certain independence in collecting, analyzing, processing, and publishing
materials in their respective orientation to a product orientation. This type of

                                                                                   28


---

departmentalization creates self-contained divisions, each of which is responsible for
every aspect of a certain product.3!

             CALL Organizational Chart

                                                                         CALL
                                                                  Diewcie

Collection,  Combat Training  infeemation Stitems                              Amatyrix &
   Branch           a               Branch                                     Pubbcaixm

     AAT        Branch                                                          Branch.

aa

                              Figure 2. CALL Organizational Chart 1993-1996
          The functions of the Operations and Administration cell remained relatively
unchanged, and its personnel manning remained at four. The Collection division

maintained its focus on supporting CAATs, WALLP, and Support to Exercise (STE)
requirements to include: Operation Restore Hope in Somalia, Operation Support Hope in

Uganda, Operation Uphold Democracy in Haiti, and 3 Army’s Bright Star exercise. In

addition to these roles, the Collection division also assumed a pivotal role in the
Louisiana Maneuvers (LAM), a series of simulations and exercises by the Army to
anticipate and adapt its our changing environment. Force XXI doctrine resulted from
these exercises and was used to replace the outdate Air Land Battle Doctrine. Although it
expanded its collection effort and would also conduct some preliminary analysis, the
Collection division was reduced as a result of the completion of the Desert Shield/Desert
Storm collection effort to a manning of 10 to 12 officers and enlisted soldiers.

          31 Jerald Greenburg. Managing Behavior In Organizations, Prentice Hall, 1999,

pg. 286-287.

                                                             29


---

            The Analysis and Publication division’s four civilians were to serve as researchers
and archivist for the organization. The newly created Information Systems division was
tasked with the development, testing, and implementation of automated data systems.
This function was seen as paramount to ensuring CALL’s future success and resulted in
“the recruitment of 25% of CALL’s officer strength to upgrade and test information
systems.” 32 They were charged with developing and maintaining the CALL database
(CALL DB), providing the automation equipment infrastructure to include computers for

CAATs, and implementing the Army Lessons Learned Management Information System

(ALLMIS). After the initial surge of personnel to assist CALL leverage the emergence

of information systems, the division’s manning was reduced to three officers to maintain
the equipment and continue to seek advances in information technology.

            The last significant change in this reorganization came in the latter half of 1994
when the CTC Division was added. Its mission was to supervise the Focused Rotation
Program at the CTCs, collect lessons from the BCTP Warfighter exercises, and publish
take home packets and trend newsletters for the units of FORSCOM. This effort was
manned with 8-12 officers, enlisted soldiers and civilians, located at Fort Leavenworth
and at each CTC.

             3. 1996 Reorganization to Support the Information Age
            In March 1996, CAC fused the Army Knowledge Network (AKN) and CALL in
an integrated effort to provide timely and relevant lessons learned to the entire force.

           32 Center For Army Lessons Learned, Memorandum for Record, 27 February
1995, Subject: ADCST Input to Annual Command History Report 1994.

                                                                                   30


---

AKN had been developed in the early 1990s as a system of linked and cross-referenced
databases constituting a complete collection of military, political, social, and
economic information pertinent to military operations.33 Each activity was expected to
complement and strengthen the other. CALL had long achieved excellence in analyzing
and providing relevant lessons learned, and AKN hada strong reputation for its electronic
archiving and rapid distribution of documents. Along with the combination of AKN and
CALL, the implementation of web enabled solutions was expected to facilitate CALL’s
communications with units across the Army. This merger would solve a longstanding
CALL problem of disseminating vital information throughout the Army. The
reorganization initially reduced the number of divisions to three: Lessons Learned,
Information Systems, and Research. Each division focused on the specific services that
CALL provided. However, in 1998, CALL was expanded to also incorporate the Army’s

University After Next (UAN) (Figure 3).

          The Lessons Learned Division (LLD) consists of two sections: Actual Operations
(AO) and the Combat Training Center (CTC) Branch. The LLD’s mission is to gather
and analyze observations and produce a variety of lessons learned literature for the entire
Amy. They have a total of 28 military and civilian personnel to assist in this function.
The AO Branch is assigned the task of collecting observations from contingency
operations and training exercises through the use of CAAT teams. CAATs are task-
organized teams of Subject Matter Experts (SMEs) representing each BOS normally from
TRADOC Schools and Centers. These teams are lead by a TRADOC-provided Team

          33 L. D. Holder and Edward Fitzgerald. “The Center for Army Lessons Learned:
Winning in the Information Age”, Military Review, July-August 1997, pg. 2.

                                                                                   31


---

Chief external to CALL. If sufficient time is available, they also host a Collection
Workshop for CAAT personnel on the collection plan and lessons learned methodology.

The AO Branch also furnishes an operation officer and non-commissioned officer (NCO)

to assist the CAAT Team Chief with operation support issues and the CALL collection
methodology. The AO Branch has nine officers and NCOs to assist in this function as
required.34 Along with the OPSO/OPSNCO, CALL also assigns a civilian analyst to
support each CAAT collection effort. The three civilian analysts not only provide
feedback on the quality of the observations, but also insure that the collection effort is
addressing its stated targets.

                                                      CALL Organizational Chart

    [                                  Research                                       I                   _1
                                       Division”
Lewon Leemed                                                                       information                 University
   Division                              «RD!                                    Systems Division               After Next
     «LLD)
                                                      information                       asp)                      {CAN}
:             ao                                                              i         _t
[ Branch | Semaine                                                                                 Special
Actus! Operations | | Combet Training       Technology                              Iebeld                <
                                                                                  Web-Cnteway
                                                                                                   Projects

                                     Figure 3. Present CALL Organizational Chart

            The CTC Branch’s mission is to capture lessons learned and TTP derived from
observation at the CTCs for dissemination to the Total Army. Unlike the AO Branch,
members of this section conduct both active and passive collection while units are
training at the four CTCs. They also are responsible for conducting analysis of

           34 Center for Army Lessons Learned Handbook 97-13, United States Army

Combined Arms Center, Fort Leavenworth, Kansas, pg. 4.
                                                                                   32


---

performance trends to assist units in focusing their training at home stations. CTC

Branch has a total of 12 military and civilian analyst located at each of the training

centers and Fort Leavenworth, and the CTC also prepares products to assess units’
abilities to execute their wartime missions.35

          The Research Division (RD) is composed of 7-14 archivists, historians, record
managers, librarians, and security specialists. RD is responsible for not only the lessons

learned that are produced by the LLD, but also for archiving all Operations Orders

(OPORDs), AARs, and army tactical level related articles from professional magazines.
They provide the records of all information stored by CALL that are available to
authorized personnel throughout the Army. It is this division that is responsible for
inputting all classified and unclassified data into the CALL DB for use via the World
Wide Web using the CALL Gateway or the Secure Internet Protocol Router Network
(SIPRNet). The RD processes data in two ways. Paper data is scanned into computers in
a digital format and then uploaded to the CALL DB. Electronic documents are directly
uploaded by archive technicians. All documents are stored by appropriate classification

in electronic filerooms based on archival standards.

          The Information System Division (ISD) is the automation equipment support
infrastructure branch. They facilitate the collection effort by the effective use of
emerging telecommunication and computer technologies. ISD renders support to the
collection and analysis process as well as the publication and dissemination process. The
primary tool for collection and analysis is the software program CALL Collection and

           35 Ibid.

                                                                                   33


---

Observation Management System (CALLCOMS). This software allows the CAAT to
formulate a collection plan and categorize observations. CALLCOMS robust search,
sort, and filter capabilities assist analysts and trend identifications. The key to CAAT’s
success is the use of the Internet. CAATs now have the ability to use File Transfer
Protocol (FTP) to transmit observations stored in CALLCOMS back to CALL for storage
or analysis by the LLD Branch while still deployed. They can also use this
communication link to send messages back to CALL twenty-four hours a day when
assistance is needed. They no longer have to worry about waiting for business hours to
pass information because messages are forwarded to the intended recipient and waiting
for them once they arrive at work.

            Automation also aids the production and distribution of products by CALL.
CALL’s ISD supports four main methods for the electronic distribution of products: E-
Mail, postings of current products on the CALL Web homepage, storage in the CALL
DB, and storage in the CALLCOMS DB. This division is currently manned with six
civilians located at CALL and six civilians assigned to the Fort Leavenworth Department
of Information Management (DOIM).

            The newest division of CALL, UAN is a distributed organization designed to
meet the emerging knowledge needs of the Army After Next. It consists of three
components: Distributed Laboratory, Distributed Library, and Distributed University.
These components provide the capability for enterprise-wide knowledge and learning
management by integrating and synchronizing best practices and technologies from
public, academic, private, and military sectors. The UAN integrates new technologies
and methods to create a common learning environment to meet the future requirements of

                                                                                   34


---

soldiers, leaders, and units. It is tasked with developing technologies that will serve as
the comerstone of the theory of “Reachback”. Reachback allows soldiers and leaders to
gain real-time tailored knowledge from SME located throughout the world for
contingency or information needs that may arise.36

          The Distributed Laboratory will identify methods for transferring knowledge and

information between deployed units and resource centers located throughout the world.

The Distributed Library will serve as a single point of access for soldiers and leaders to a
vast knowledge repository. Not only Army and DoD information systems will be linked,
but also physical and virtual public libraries. It will address general questions that may
arise using multiple integrated formats to include video, audio, imagery, or text. The
Distributed University will provide mentorship to the user to answer very specific

issues.37 This will be done using a virtual staff or SMEs distributed at TRADOC schools

or other knowledge centers. UAN’s nine civilians will identify information technology
solutions for training, learning, and educating the Army in the future to leverage

knowledge into a combat multiplier.

D.  SUMMARY

          Although its mission to collect, analyze, and disseminate timely and relevant
lessons learned, tactics, techniques and procedures (TTPs), remains virtually unchanged

          36 University After Next Pamphlet, TRADOC Program Office for University
After Next, U.S. Army TRADOC, 1999.

          37 Interview with Antonio Monaco, Program Manager-University After Next, on

17 January 2001.

                                                                                  35


---

since its inception CALL has undergone numerous structural changes. The changes
from a Functional to a Product Orientation have been in an effort to increase the
organization efficiency and to assist the assimilation of smaller organization into CALL.
The present focus of CALL remains to continue to provide its services to its existing
clients, while using the UAN to identify emerging technologies that can be used to
support the knowledge requirements of the future force.

                                                                                   36


---

                  IV. LESSONS LEARNED METHODOLOGY

                     “The only thing harder than getting a new idea into the military
          mind is to get an old one out.”38

A. ROLE OF A LEARNING ORGANIZATION

          The Army’s drive towards transforming itself to meet its mission has become

increasingly important as the geopolitical instability of the post Cold War era continues.

With a myriad of new threats and commitments that have emerged in the 1990’s, the
force has had to become more deployable, flexible, and responsive while simultaneously
undergoing a reduction in personnel strength of nearly one third on its current manning.
The challenge that faced the Army was how to take a highly bureaucratic organization
that was very good at accepting gradual changes and make it operate effectively in an
environment that could dictate an avalanche of required changes.3? To meet this
challenge the Army, initially under General Sullivan’s stewardship, sought to become

what it defined as a learning organization.

          A learning organization is an “organization skilled at creating, acquiring, and
transferring knowledge, and at modifying its behavior to reflect this new knowledge or

insight.”40 The key is not the idea that triggers the desired organizational improvement,

          38 Col Michael Starry, “It’s Not The Same Old Army,” Armed Forces Journal,
October 1995, pg. 42.

           39 Sullivan, pg. 5.
          40 David A. Garvin, “Building A Learning Organization,” Harvard Business
Review, July-August 1993, pg. 80.

                                                                                     37


---

but rather the accompanying change in the way that the tasks get done. 4! Learning
organizations must be skilled at five main activities that serve as the foundation for their
success: systematic problem solving, experimentation with new approaches, learning
from past experiences, learning from the experiences of others, and transferring
knowledge quickly and efficiently throughout the organization. 42
B. THE ARMY AS A LEARNING ORGANIZATION

            The Army has emplaced methods to enable it to perform each of the five activities

necessary for it to qualify as a learning organization. Systematic problem solving is

accomplished using various formal methods. The Army’s most prevalent method for
tactical decision making is based on the Boyd’s OODA Loop. This process follows four
distinct phases: Observe-Orient-Decide-Act. (Figure 4)

                                                  Figure 4. Boyd’s OODA Loop
              The output for each phase of the cycle serves as the input for the next phase and
forms a continuous loop. The Observe phase is an effort to determine exactly what is

           4! Thid. pg. 81.
          42 Ibid.

                                                                                   38


---

taking place in the decision makers environment and under what circumstances they must
function. The Orient phase interprets the information gathered from the Observe phase,
uses it identifies the overall objective, and formulates possible courses of actions. In the
Decide phase, the decision-maker will determine how best to use all available resources
to reach the stated objective. In the Act phase the decision-maker will execute the
decision.43

          The Experimentation with New Approaches activity is broken down by the Army
into two subgroups: ongoing and one-of-a-kind experimentation. The ongoing
experiments are conducted at the service’s battle labs that are located at each of the
TRADOC proponent schools. These labs run extensive virtual and live tests/simulations
to measure the impact of what changes to Doctrine, Training and Leader Development,
Organization, Materiel, and Soldier (DTLOMS) will have on the force. One-of-a-kind
experiments, such as the Advanced Warfighting Exercises (AWEs) are used to test the
maturity of cutting edge technology and its impact on the effectiveness of current units.
The results of both types of experiments provide a means to understand future
warfighting requirements or current deficiencies.

          CALL serves as the focal point in helping the Army become a learning
organization by responding to the last three activities. It addresses the Learning from
Past Experiences activity in its effort to systematically collect, analyze, record and
disseminate information throughout the organization. The open access to this
information by all members of the organization prevents them from being “condemned to

          43 Daniel H. Kim, “The Link between Individual and Organizational Learning,”
Sloan Management Review, Fall 1993, pg. 37-38.

                                                                                   39


---

repeating past mistakes.”44 Since not all learning comes from self-analysis, CALL also
gains valuable insight from the fourth activity, Learning from Others. As a member of
such cooperative organizations as the ABCA Coalition Operations Lessons Learned
Database, the Joint Services Lessons Learned program, and NATO Lessons Learned
Program, it shares observations with the members of other military strategic alliances.
These two-way exchanges are valuable because they allow the organization to gain either
a new perspective on an issue or implement TTPs successfully used by Allies when the
U.S. Army is operating in an environment which previously it has not been exposed.

The last activity is the Transfer of Knowledge throughout the organization. For

learning to have the maximum possible impact it must be transmitted not only as broadly

as possible, but also quickly and efficiently. CALL spreads this knowledge thorugh a

continuous series of pamphlets, bulletins, newsletters, briefings, and special after-action

reports. These reports serve many purposes, to include: providing a checklist of do’s and

don’ts, summarizing trends, and furnishing input to modify training and doctrine. The

effect of these reports is to develop shared mental models throughout all of the members

of the organization. It is through individuals sharing and improving their mental models

that true organizational learning occurs.45 The distribution .channel of CALL’s

publications include all Army FORSCOM units down to the battalion level, TRADOC

schools, the CTCs, major Reserve Component headquarters, other military services, and

Allied nations through liaisons and attaché offices.                        CALL’s use of emerging

44 Ibid. pg. 43.
45 Garvin, pg. 85.

                                                                        40


---

information technology solutions, such as web based access to its current publications
and electronic copies sent via the Internet, assists in expediting the information out to its

users.

          It is important to also track the efficiency of the spread of knowledge. This can
be done by evaluating three overlapping stages of learning: cognitive, behavioral and
performance improvements. Cognitive learning occurs when members are exposed to

new ideas and begin to think differently. Behavioral learning is when members begin to

internalize new ideas and alter their behavior. Performance improvement is when
changes in behavior lead to measurable improvement in results.46 Because CALL does
not have the authority to mandate implementation of its lessons, they are acted upon

based on CALL’s reputation and their quality alone.

          The semi-regular products that result from CALL, such as the CTC Quarterly
Bulletin, CTC Trends Bulletin, or Topic Newsletters generate cognitive learning. These

products have near-term impact because they are focused on getting individual or unit

level leaders to use these lessons prior to their incorporation into formal materials, for
example field manuals. The Army uses its proponent schools and military education
system to implement behavioral learning. The proponent schools use CALL’s products
to identify those lessons that will provide an added value to Army operations. These
lessons then are incorporated into the long-term organizational memory through the
modification of formal training programs and field manuals. As new ideas or TTPs are
accepted, they are incorporated into the military education that all soldiers receive as they

           46 Thid. pg. 90

                                                                                     41


---

periodically advance in rank. This education then serves as the basis for how they lead
their units or perform missions in a tactical environment. Finally, the Army can track the
progress as units rotate through the CTCs every 18 months. While at the CTC, each unit
is evaluated using the latest doctrine, TTPs, and trend analysis to provide feedback to
CALL showing whether the same mistakes are being repeated or the new ideas are being
used to maximize unit performance.

C. WHAT ARE ARMY LESSONS LEARNED?
            Before discussing the method that CALL uses ‘to transform observations into

lessons learned, it is important to understand the definition of a lesson learned. The

Army defines a lesson learned as Cs“validated knowledge and experience derived from

observations and the historical study of military training, exercises, and combat
operations.”47 It is CALL’s responsibility to identify observations or data that will have
a significant impact on/or require changes to one of the DTLOMS. Once this data is
validated and bundled as new insight through use of the Lessons Learned System, it is

codified as a lesson. These lessons are considered in term of focus, relevant, timely, and

useful to affecting behavioral changes. CALL does not consider a lesson “learned” until
it has resulted in behavioral change. Its ultimate purpose is not to build a knowledge base
of data, but rather to actively engage in the process of changing a specified behavior that
exists in the force.

           47 Center for Army Lessons Learned, CALL Handbook 97-13, United States
Army Combined Arms Center, Fort Leavenworth, Kansas, pg. 2.

                                                                                     42


---

D. CALL’S LESSONS LEARNED SYSTEM

         The system employed by CALL to develop lessons learned is outlined in AR 11-
33, Army Lessons Learned Program. This system establishes a methodology for
collecting and analyzing field data and distributing, integrating, and archiving lessons
from Army combat operations and training events. CALL breaks its various methods of
gathering data into three classifications: Active, Passive, and Active-Passive.

          Active collection is done by the AO and CTC Branches when they send out
CAAT Teams to observe and record data from ongoing training or operations. Passive
collection is done via the website when members of the force either send observations or
unit AARs into CALL for inclusion in the CALL DB. Active-Passive collection is done
when CALL contacts a unit after the fact and conducts a formal interview or AAR with
key members of the organization. It also will contact units that are redeploying from
major training events and ask them to send a copy of all OPORDs, AARs, and ROEs to
CALL for input into the database. No matter what the source of input of data, CALL will
follow the same methodology to glean lessons learned from the data it is provided. This
methodology consists of several basic components or stages: Mission Analysis and
Planning, Deployment and Link-Up, Collection Operations, Analysis, Distribution and
Archive. Only by the exercising of each of these components in a systematic process can
CALL provide results in the form of lessons that assist soldiers and units to perform their

missions right the first time.
            1. Mission Analysis and Planning

          As with most military operations, effective and detailed planning appears to be
central to CALL’s success in capturing lessons. When CALL receives a request for

                                                                                     43


---

assistance or tasking to gather information and observations, mission analysis is initiated.
Mission analysis is an attempt by key members of CALL and the requesting organization
to determine what specific issues need to be address by the collection plan once it is
formed. In the past, the data collection plans have taken a “vacuum cleaner approach.”
Observation teams were widely deployed and little attempt was made to define explicit
learning objectives.48 The result, as earlier noted by General Sullivan, was the collection
of a mass amount of data that overloaded the organization’s capacity to turn it into useful
information or lessons. Senior Army leaders at DA currently select what events have the
highest potential for generating valuable lessons and outline the specific issues to be
observed by the CAAT. This specific guidance to CALL and the CAATs has created a
“telescope” of learning. This change, during mission analysis, in focusing the collection

effort early has allowed the human analysts at CALL to no longer be the chokepoint of

the Lessons Learned System.

       Once mission analysis is completed it serves as the basis for the composition of

the collection team and the development of a detailed collection plan. The Combined
Arms Assessment Team (CAAT) is composed of 8-12 subject matter experts tasked from
the TRADOC proponent school. The CAAT members’ specialties are directly related to
the issues that are identified during mission analysis. A team chief, external to CALL,
also is designated by the Department of the Army and becomes responsible for the
development of the actual collection plan and all CAAT collection activities. Team

           48 John C. Henderson, Stephanie Watts Sussman, and James B. Thomas,
“Creating and Exploiting Knowledge For Fast Cycle Organizational Response: The
Center for Army Lessons Learned”, Advances In Applied Business Strategy, Volume 5,

1998, pg 106-107.
                                                                                     44


---

Chiefs are generally Lieutenant Colonels or higher depending on the size and difficulty of

the collection effort. In addition, CALL assigns an Operations Officer and Operations

NCO (OPSO/OPSNCO) to serve as advisors to the team chief on the collection process
and as a subject matter experts on the use of CALL’s collection software CALLCOMS
and IT architecture. Furthermore, CALL appoints an analyst to support the CAAT via a
communication link from Fort Leavenworth. A Combat Camera Crewman can be

employed by CALL if needed.

         Once the CAAT has been formed and there is sufficient time available, team
members travel to CALL for a 3-5 day Collection Workshop. During this workshop the
team members refine the collection plan, train team members on the lessons learned
process and CALL’s methodology. Assisting the CAATs is the software application
CALLCOMS. CALLCOMS can be used to formulate the detailed collection plan,
delineate collection responsibilities among CAAT members by Battlefield Operating
System (BOS), and determine the collection methodology for each task. Once the CAAT
is formed, the collection plan completed, and the CAAT members are trained, this phase

of the process is complete.
            2. Deployment and Linkup

         This phase begins with the deployment of the CAAT to the collection site or
aerial/seaport of embarkation. The CAAT attempts to link-up with the host unit as soon
as possible to begin collecting data and, more importantly, to build rapport. During this
phase the OPSO/OPSNCO plays a significant role because they are responsible for
arranging the counterpart link-up between the CAAT subject matter experts and observed

                                                                                     45


---

unit personnel. This link-up can be at the staff, unit, or individual level based on the
mission analysis conducted during Phase I.

            Once the CAAT team has linked-up with the host unit, they begin their collection
effort. Host units must supply a CAAT team access to communication links that allows
transmittal of e-mail. This communication link allows the CAAT to promptly relay data
to CALL analysts via CALCOMS. Since the CAAT personnel are observers and not
evaluators, their mission is to support and assist the unit as much as possible, along with
collecting data for CALL. Because of this relationship, CAAT should be seen as an asset
by the unit leadership and become an integral part of the operation. This phase is
complete once the CAAT members linked-up with their host unit counterparts and
establish a communication link to CALL.

             3. Collection Operations
            Once on site, CAAT members begin to observe events and collect data in real-
time. Collection team members join in on field missions to look for factual, observable
events to document. They also perform in their area of expertise, for example carrying

and operating communication equipment or even replacing a rifle infantryman.4? No

retrospective accounts are taken and only data of a tactical or operational nature are
collected. CAAT members are taught to look for systemic-induced problems rather than
those due to soldier/leader error or anomalies.

           49 Tbid. pg. 109.

                                                                                     46


---

          Once an issue is recognized, they examine the events that transpired, try to find
the cause and look ahead to identify the potential consequences. This process is called
“threading the needle”, tracing the path of a problem back to its source in order to gain a

better understanding of what happened and why.*° As this process nears completion,

team members document their observations and discussion of the events into
CALLCOMS using its pre-formatted input form.

         While the collection team members work with the unit to gather data, the CAAT
team chief consolidates their observations on a recurring basis. This information can be
transmitted using the File Transfer Protocol (FTP) by way of the Internet, if team
members are at a remote location, or downloaded onto the team chief's computer via
standard computer disk. The team chief, with the assistance of the OPSO/OPSNCO, then

conducts a review of the subjective observations. The purpose of this review is to screen

for content, edit grammar, ensure the observations are addressing the collection plan
requirements, and identify problems that are potential warstoppers.5! Since the team
chief is reviewing the actual file on CALLCOMS that the team member submitted, any
cosmetic changes to the file can be completed without requiring further communication
with the team member. If the team chief believes the team member has identified an area
outside the scope of the collection plan or needs further clarification, he can discuss these
issues with the observing team member and correct the CALLCOMS form as necessary.

           Once the team chief has completed his review of the CALLCOMS observations,

they are forwarded electronically by the CALL OPSO/OPNCO to the CALL analyst at

           50 Tbid. pg. 108.
           51 CALL Handbook 97-13, pg. 14.

                                                                                     47


---

Fort Leavenworth. During past operations, such as Operation Restore Hope, five to ten
observations a day were transmitted to CALL. CALLCOMS also provides the team chief
with the ability to track the current status of any observation and develop an ongoing
issue tracking worksheet. A compilation of observations is provided to the supported
unit commander during a briefing prior to the CAAT departing the theater.

            Moreover, CALL is able to support the collection of passive observations from

members of the force. At this time, soldiers throughout the Army can input observations

directly to CALL using the CALLCOMS software located on the CALL web site. Once
an observation is presented, an analyst is assigned to assist in processing the observation
and maintains close contact with the submitter until the procedure is complete. As an
observation is forwarded to CALL, it moves into the next phase of the lessons learned

process.

            4. Analysis
            During the analysis phase, the raw data of observations gets processed into
lessons through an expanded interpretation method that includes feedback from experts
around the Army. Even while the CAAT is still deployed and gaining additional
observations to support the collection plan, the analyst at CALL is working on taking the
CALLCOMS observation previously forwarded to him electronically via FTP and
converting it into a lesson. As these observations are received, the analyst transfers them
into the CALLCOMS Database (CALLCOMS DB). Supporting documents, such as
video, also are received via the Internet and converted so they can be added to the
database.

                                                                                     48


---

         Observations then are categorized in accordance with the BOS as outlined in
TRADOC Pamphlet 11-9. Once the observations are indexed, they are scanned for
formatting and grammatical errors, and checked to insure they maintain individual or unit
anonymity. As the analyst works on observations, he or she relays questions back to the
team, as necessary, to resolve conflicts and refine the collection effort. Observations then
are posted on electronic bulletin boards on the Secret Internet Protocol Router Network
(SIPRNet) and sent electronically to the appropriate specialists at TRADOC agencies to
solicit feedback.5?

         The analyst also validates the data coming in from the field. Validation occurs
when the current observation is compared with past information contained in the CALL
DB to. determine frequency and impact. Feedback from the TRADOC experts is used to

determine if the current observation is new knowledge or an expansion of existing

organizational knowledge. Correspondingly, it can render additional new questions or
issues that TRADOC experts would like to see the CAAT team address. This three-way
communication between TRADOC experts, the CALL analyst, and the CAAT Team

Chief occurs almost daily.

         Upon completion of the screening by the analyst, the observation can be released
to commands that are rotating into the theater to support their training initiatives. The
CALL Director, working in conjunction with the deployed units and the follow-on unit’s
chain of commands, seeks to gain release authority of lessons. 53 However, “nothing is

           52 Ibid.
           53 CALL Handbook 97-13, pg. 14.

                                                                                   49


---

released by CALL until the observed Task Force Commander allows it.”54 It is at this
point that the observations are codified as lessons.

            5. Distribution and Archiving
            When the CAAT returns from its deployment, the team members and the assigned
CALL analyst are responsible for insuring that all lessons are categorized by BOS and

compiled into an initial impressions product. A draft of the coordinating initial

impressions report is produced by the CAAT, and it is staffed-out to all interested
commands and agencies for comment. Normally, agencies receive an initial product
within two to three weeks. Once the coordinating initial impressions report is sent out,
the CAAT departs CALL, which officially ends their tasking. At this point the OPSO is
responsible for finalizing the collection product. Any appropriate comments from the

staffing process are added to the final product by the OPSO. Copies of the final

impressions report are forwarded to the numerous Army Commands as a guide for future
contingencies.

            Simultaneously with this distribution, the product is placed in the CALL Database
(CALL DB). The CALL DB is a 5-Petabyte storage site of both classified and
unclassified data. It serves as the Army’s electronic archives of all operations orders,
situation reports, and key briefings on post-1973 Army contingency operations. It also
contains CTC take home packages, all final exercise reports, all training lessons learned

and user feedback on articles from previous CALL publications.55 This automation tool

            54 Interview with Lon Seglie, Senior Actual Operations Analyst-Lessons Learned
Division, on 16 January 2001.

           55 Holder, L.D. and Edward Fitzgerald. “The Center for Army Lessons Learned:
Winning in the Information Age”, Military Review, July-August 1997, pg 55.

                                                                                   50


---

allows lessons that are stored to be accessed using various methods. CALL DB can be
browsed using several methods: the Library of Congress subject coding system, attributes
of the event (i.e. time, location, date, or operation), according to the task, conditions, and
standards applied by the CAAT team, or a simple word search.°®

         After the final impressions report is completed, the CALL Director, in
coordination with the Lessons Learned Division, determines whether other CALL
products should be developed to further disseminate the information. CALL uses Push

and Pull strategies to distribute its lessons. Push distribution is accomplished when
information is sent from CALL out to its client base. This can be done through

customized or mass market products. CALL also can use pull distribution which is
keeping information in a central, accessible area for uses by its clients. Pull distribution
is done through self-service from the CALL website and Internet access to the CALLDB.

          The customized products are in the form of training vignettes, handbooks or
exportable training packages. They are made in response to request from FORSCOM
units to prepare for operating in a particular environment. Examples are the handbooks

that were created for elements of the 10 MD before deploying to Haiti and the training

scenarios that were developed for units in Europe to utilize at the CMTC preceding
deployment to Bosnia or Kosovo. Mass-market products are in the form of the CALL
newsletters, the bi-monthly News From The Front bulletin, Training Quarterly
publication, CTC Quarterly bulletins, and special editions. These products are aimed at

reaching the widest possible audience and are published on paper, CD-ROM, or sent via

e-mail.

           56 Henderson, pg. 111.

                                                                                   31


---

            The last channel is self-service from the CALL web page. The goal of this
service is to be a “one-stop shop where military users can find the information they need
to improve training, prepare for a contingency operation, or gather research
information.”>7 All of CALL’s latest publications are available on the web page. A user
can go to the web site and download or read the current products. If the customer desires
to gain access to back issues of products or the CALL DB, they can fill out a registration
form on the web site and submit it electronically. Once the CALL Executive Officer
reviews the application, verifies the customer and their need for access, a password and
user identification is sent to the customer through the postal system. Once a customer
has access to the CALL DB they can use software tools to access 2.5 million pages of
data related by subgroups. While the user enters key search words or terms, the software

using artificial intelligence graphically displays information by themes of related

subgroups that allows the user to rapidly sort and retrieve whatever information is

needed.98
           Whatever the method of dissemination, push or pull, that is deemed to be

appropriate, the most important function of this last phase of the Lesson Learned Process
it to make sure that they have the widest possible impact on the total Army. Because
budget constraints do not permit CALL to print all of its products down to the
Company/Team Level, they authorize and encourage local reproduction to get access to
the lowest levels of the organization. CALL also sees the website as a means to search
and download tailored information, lessons, and TTP as needed.

           57 CALL Handbook 97-13, pg. 21.
           58 Holder, pg. 56.

                                                                                   52


---

E.  SUMMARY

          To meet the challenge of operating in an environment that has become
increasingly complex and unstable, the Army has sought to become a leaming
organization. As a learning organization, the force could rapidly collect and transfer
knowledge to make the necessary modifications in its TTPs to increase effectiveness.
CALL performs several key functions to enable the Army to operate as a learning

organization. These functions are outlined in AR 11-33, Army Lessons Learned

Program. This manual establishes the CALL methodology for collecting and analyzing

field data and distributing, integrating, and archiving lessons from combat operations and
training events. The use of information technology has augmented the methodology by

providing standardized planning, collecting, and analyzing tools and an alternative

dissemination platform.

             53


---

THIS PAGE INTENTIONALLY LEFT BLANK
                                               54


---

                  V. INFORMATION TECHNOLOGY AT CALL
                     “The power of the microprocessor [is] the fact that shared
          information can compress time and increase effectiveness, not by a little,

           but by a lot.”59

A. IT ARCHITECTURE

          IT architecture can be defined as the underlying framework that determines and
describes the IT resources required by an organization to meet its goals and achieve its
vision. The fundamental components of any Information System architecture are its
hardware, software, policies, and network.6° When CALL decided to adopt information
technology solutions to aid in overcoming the deficiencies that its old “paper and pencil”
system had encountered, they sought to find a unifying framework for all aspects of the
lessons learned process. This framework would have to support not only the collection
teams in the field, the analyst and archivist at Fort Leavenworth, but also units located
throughout the world. It was with this in mind that CALL sought to develop an
Information Technology architecture to meet all of the diverse demands on its resources.
This required identifying the functions that the IT infrastructure must support. CALL
determined that the key functions were: for collection teams to be able to input data and
electronically send this data to an analyst for processing, the capacity to store data for
future retrieval, the capability to search data by various methods, and the ability of
CALL’s clients to gain access to the data via the Internet. These key functions have

           59 Sullivan, pg. 16.
          60 Rex Buddenburg, “What’s Wrong with DoD Information Architectures,”
http://web1 .nps.navy.mil/~budden, March 2000, pg. 3.

                                                                                  55


---

served as design parameters for the development of the information system that CALL
has put into place.

B. CALL’S 3-TIER ARCHITECTURE
              To support the key functions CALL identified as being paramount to

successfully transferring its lessons learned process to a fully integrated IT process, it
developed a 3-Tier Architecture: Client, Application-Web Server, and Data Server.
(Figure 5)

 | (Tier 1                            Tier 2

 4     CLIENT.                            WEB SERVERS
                                                 eH
i      ft               HTML Request

 :aan       a           HTML
 oo Wass ie

|                                     eaves | *        Respons   yp acess
by                                    quest| PResporse |
                                                                    Excalibur
 |                                    APPLICATION
                                                                RetrievalWare 6.7
i      Web Browser                    SERVERS                          Excalibur
 I
.      Netscape 4.2 of                  sang                    RevievalWare 6.7

                                         Et EE

 f     Ms Explor5e.r0                            +

5

                                                                CALLCOMS

                                      —_i

                                               Figure 5. CALL’s IT Architecture
The 3-Tier architecture was an attempt to overcome the limitations of older legacy

systems. By separating presentation, processing, and data into distinct entities CALL’s

system permits the parallel development of future hardware, application, or database

upgrades without requiring a complete overhaul of the existing system. This design not

only decreases upgrade development time, but also has a significant cost savings since

only one tier needs replacing at a time, not the entire system.®!

          61 Andrew Combs,            “N-Tier Client                               Server  Architectures,”

www.ilt.com/AEDIS/Ntier, pg. 2-3.                  56


---

              1. Tier One

         Tier One of this architecture also is classified as the Client Tier. It is responsible
for the presentation of the data, receiving user request in HTML, and controlling the user
interface. The client can be any member of CALL, DoD government employees, or U.S.
Military personnel who have been approved access to the CALL DB by the Operations
Cell at Fort Leavenworth.§2

          To request access to the CALL DB, a client must complete the Access Request
Form located on the CALL web site. This standardized request form is converted into an
e-mail text message that is forwarded to the Operations Cell. The Operation Cell
assesses the individual’s need to use the database and determines whether to grant access
to the FOUO or classified information database. Once approval is granted, the client is
issued a USERID and password to gain access to the specified database.

          If the client has been granted FOUO access, they can use a PC with an Internet
connection and Web Browser to enter the database. Once connected to the CALL web
page, clients can enter the assigned USERID and password to issue an HTML request to
gain access to information within the CALL DB. When this request has been passed,
they move into Tier Two of the architecture. If the client is attempting to access the
classified database, they must gain access through computers that are attached to the
SIPRNet. Members of CALL must gain access through the 4 PC linked to the SIPRNet
located in the classified materiel room of CALL.

           62 CALL Handbook 97-13, pg. 22.

                                                                                   57


---

            Once the chient’s request returns from processing by Tier Two and Tier Three, it
will be formatted as either a text or image file. For the client to view or read these files,
they must have Adobe Acrobat and TIFF image viewer applications loaded onto their
PCs. The CALL web site has both of these applications available for downloading by the
client.

             2. Tier Two

            The second tier of the architecture is called the Application-Web Server Tier.
This tier protects the data from direct access by the client. It uses middleware located on
an application server to conduct interactions with the database translating client calls into
database queries and then translating the data from the database into a formatted
presentation for the client. This important function is performed by Excalibur’s
Retrieval Ware 6.7 software application.

            Retrieval Ware 6.7 is a framework for information retrieval on an enterprise wide
network. It combines two online search capabilities, adaptive pattern recognition and
semantic network analysis, into a method for searching disparate databases for text,
scanned images, video, and audio documents.63 Adaptive pattern recognition is a search
technique that analyzes and matches binary patterns to locate errors such as misspellings
or bitmaps which otherwise would not be presented to the client. This fuzzy logic
technique allows for an expanded search of documents that would be excluded because of
user-input error or optical scanning character recognition errors. The Semantic Network
Analysis searches for words in context by recognizing word meanings and relationships.

           63 Geoffrey E. Brock, “Information Retrieval Tools for Knowledge
Management,” Patricia Seybold’s Workgroup Computing Report, January 1998, pg. 4.

                                                                                   58


---

This allows the client to drill down into the database using very specific queries.
Although RetrievalWare does not permit SQL searches, the quality of the results and
document rankings are much higher based on the search techniques it does permit.

          As soon as the client inputs his search parameters, RetrievalWare accesses the
CALL DB searching from its various libraries. This is the transition point from Tier Two
to Tier Three. When the search is complete it presents the client with a list of files that
match the search parameters. The client can then select a file for viewing.
RetrievalWare displays the information in a format that is supported by Adobe Acrobat

or TIFF Image Viewer. This display of information is the transition from Tier Two back

to Tier One and completes the client’s service request.

          The application server that supports RetrievalWare is run on one of the four
ProLiant Compaq network servers administered by the ISD Branch. These servers have
up to two processors operating at between 667 MHZ to 1 GHZ each, 125GB extemal disk
arrays, and 90GB expandable storage capacity. Although the application server is
physically located with servers that support the CALL DB, it is logically separated to
allow for a three-tier architecture. Tape backups of the data contained in the CALL DB
are located at the Fort Leavenworth DOIM and maintained by the Special Projects

section of the ISD.

            3. Tier Three

          The last tier of the architecture is the Data-Server Tier. This tier is responsible for
all data storage. CALL’s data storage of all classified and unclassified TTPs, lessons
learned, OPORDs, AARs, ROEs, and military relevant professional articles, is located in
the CALL DB. The CALL DB is also linked to the Combat Arms Research Library

                                                                                   59


---

Database (CARL DB), TRADOC DB, and various other databases throughout the Army.
The CALL DB is a relational database that currently has 5 Petabytes of storage and is
expandable, as future storage needs increase. The database is run on the same supermini
computers that support the application server and uses the Excalibur Electronic Filing
System (EFS) as the Database Document Management System (DBMS).

            EFS allows documents to be stored in accordance with international archival
standards and displayed in a format following what the RD branch classifies as a “File
Drawer.” The “File Drawer” analogy is an attempt to structure the records in a method
that is easily accessible and user friendly to members of the DoD. Since military records
previously have been kept in large multi-drawer file cabinets, the RD Branch sought to
use this common military storage arrangement within the CALL DB. When a user
accesses the database, he is presented with a “Cabinet” that contains historical files from
a particular storage library. Once a cabinet is selected, a list of “Drawers” is displayed.
In each of these drawers are numerous “Folders” and each folder, in turn, contains
numerous “documents”.64 Documents can be text, slide presentations, audio, video, or
imagery files.

             Another important aspect of the Data Storage Tier is the method in which the RD
processes records for input into the CALL DB. Processing of records is done in two
basic ways based on whether it is in paper or electronic format. Records received in a
paper format are converted to digitized form using PowerScan or StageWorks scanning
software.

           64 Interview with Dr. Scott Lackey, RD Brief Chief, on 16 January 2001.

                                                                                   60


---

         These software solutions allow for full page Optical Character Recognition while
conducting batch oriented processing. This provides the RD branch with the capability to
scan up to a thousand pages a day of older paper files into digitized text and images if
required. RD Archivist organize and prepare the documents for input and then load them

into the scanner. All documents are scanned as single page files although the software
allows for multi-page scanning. Although this decision increases the amount of space

required to store a document and increases the complexity of the File Management
System, it is based on improving user access by decreasing the wait time to download a
file via the Internet.® Once the scanning is complete, the digitized documents are then
classified and uploaded into the appropriate CALL DB by the Special Projects section

located at DOIM. Documents that are received in electronic format are classified and

uploaded by the RD branch directly into to CALL DB.

C. CALLCOMS SOFTWARE

          Equally important to the current network architecture that CALL has established
to assist in the storage and dissemination of lessons learned is the software application it

developed to aid the collection process. ‘AS CALL sought a way to increase the

efficiency of the collection process, they conducted an in-house development of a
software tool that would support all of the requirements of the CAAT. This software,
CALLCOMS, assists the CAAT. in five key functions: Collection Plan Building, Issue
Tracking, Observation Entry, Administration and Trend Analysis are the five modules of
this CALLCOMS. Although it is currently not part of the three-tier architecture, CALL

           65 Tbid.
                                                                                61


---

expects to migrate this application to Tier Two and the CALLCOMS DB to Tier Three
during the next fiscal year.66

            During the Mission Analysis phase of the collection operations, the Collection
Plan Building module is used by the CAAT to identify the parent issues and sub-issues
for which the data will be collected. It also permits the CAAT to delineate
responsibilities to the identified questions among the CAAT members. The Issue
Tracking module allows the CAAT Team Chief to keep abreast of the status of each
issue. It depicts where in the collection process that issue is and when events are
scheduled that will likely initiate data for an issue. Once a CAAT begins active
collection, the Observation Entry module entitles team members to enter data directly
into the pre-formatted form. This data is then automatically entered into the
CALLCOMS DB. The Administration module equips the CAAT with the ability to
transmit files and data from his deployed location to the analyst located at CALL
Headquarters.

            Once an analyst approves an observation, it is added to the CALLCOMS DB.
Currently, there are approximately 15,000-18,000 observations located in this database.’

The Trend Analysis permits users to conduct searches of the database for past

observations. Limitations to CALLCOMS are that it can only conduct pre-defined
queries and does not support SQL-style queries that are typical of a system like Microsoft
Access.

           66 Interview conducted with James Walley, LLD Actual Operations Analyst, on
17 January 2001.

           67 Ibid.

                                                                                   62


---

D. CALL GATEWAY WEBSITE AND LAN

         The last key piece of technology that is designed to assist CALL in completing its
mission is the CALL Gateway web site and internal CALL LAN. The CALL gateway is
an Internet web site designed to assist CALL in the passive collection of lessons learned
and as a mechanism for the dissemination of TTP and lessons learned to its customers.
To goal of the Gateway is to be “a one-stop shop where military users can quickly find
information to improve training, prepare for a contingency operation, or gather research
information.”68 To meet this challenge, the ISD develops and maintains a homepage
that has links to current CALL products, the CALL DB, Training Resources, U.S and

International News agencies, and the Army homepage.

          The CALL LAN is in place to increase office productivity and communication
within the organization and with its customers. The network uses Novell Netware 4.11
Operating System to link its 125 PC’s to each other and the Internet. The LAN allows
members of the organization to tap into the CALL DB, CALLCOM DB, and share files
with a download speed of 1.54 MBS via a T-1 Ethernet connection. To run these
services, ISD has established a server farm of 30 servers of different makes and models.
These servers run the Gateway as well as provide file storage and print services for the
LAN, E-mail for members of CALL, and FTP services for deployed CAAT team

members.

          Although this robust IT infrastructure is currently in place, CALL, as part of the
Defense Information Technology Testbed (DITT), is constantly looking for new

           68 CALL Handbook 97-13, pg. 21.

                                                                                   63


---

technologies to assist in fulfilling its core mission of collecting, analyzing, archiving, and
disseminating of lessons learned to the total Army. The goal of these future technology
enhancements is to enable CALL to furnish tactical commanders with the right
information at the right time in the right format.6°

E. SUMMARY
           When CALL adopted an information technology solution to overcoming the

deficiencies that its old “paper and pencil” system had encountered, they developed a 3-
Tier Architecture to support all aspects of the lessons learned process. Users can now
access and search CALL’s vast data repositories via an Internet connection. By

establishing Client, Application, and Data tiers, CALL has the ability to separate the

presentation, processing, and database functions into distinct entities. This permits the
parallel development of future hardware, application, or database upgrades without
requiring a complete overhaul of the existing system. In addition to the architecture, the
developmenotf the CALLCOMS software application provides CAAT teams with a

planning, collection, and analysis tool designed to improve their efficiency

           69 Holder, pg. 55.
                                                                                64


---

    VI. ANALYSIS OF CALL’S ORGANIZATIONAL DESIGN

               “The different parts of an organization can fit well together and
    function effectively, or fit poorly leading to problems.”7°

A.  GALBRAITH'S STAR MODEL

           Understanding the dynamics of organizational design, either explicitly or tacitly,
is essential for leaders to effectively organize the work of their individuals toward
achieving the organization’s stated goal or mission. Jay Galbraith identified the policy

domains or subsystems of an organization’s design that could be altered to bring about

the desired state of effectiveness. These policy variables are Task, Structure, Information
and Decision Process, People, and Reward Systems.’! In addition to the five

                            Strectare

                                                                                                                                                                                                                                                                                    Rewand Sytem

                                                                                                                                                                                                                Culture

                                     Figure 6. Galbraith’s Modified Star Model
policy variables identified by Galbraith, a sixth domain of Culture should be added to the
model. (Figure 6) Culture a powerful force of shaping the behavior of individuals and
groups and can have profound impacts on all of the other domains.

           70 Nadler, pg. 94.
           71 Jay R. Galbraith, Organizational Design, Addison Wesley Publishing
Company, 1976, pg. 12.

                                                                                   65


---

            For an organization to operate effectively, all of its branches, components, or
subparts must be consistently structured and managed by its leadership. For management
to improve existing task performance, policy and system variables can be changed to
bring about the new desired state. However, because the variables are interdependent, a
change in one variable can result in a change in any of the others for better or worse.
Therefore, organizational design changes must be comprehensive in nature and will
require coordination, compensation, or reinforcement of all the variables7.2

B.  KEY ENVIRONMENTAL FACTORS

            Every organization exists within the context of the other groups, organizations,
governments and regulations that impact its ability to perform in its market.73 This
interaction of elements is considered the organizational environment. For CALL, two
key environmental factors have had a profound impact in its ability to perform its primary
mission within the Army.

        First, since the end of the Gulf War, the number and spectrum of Operations

Other Than War (OOTW) missions conducted by the Army has increased exponentially.
This has resulted in a transformation of the focus of FORSCOM units to prepare for an
OOTW mission, as opposed to conventional warfare as in the past. Because OOTW

missions are different in scope and task composition then conventional warfare units have

found that current Field Manuals do not adequately address the best methods to perform

    72 Thid. pg. 27.
    73 Nadler, pg. 95.

                                                                        66


---

and train to be successful in this environment. The deficiencies of the Army publication
and training system have been offset by CALL’s ability to provide relevant and timely

TTPs for training units before they deploy.

          Secondly, The Department of the Army maintains strict budgetary control over
the activities of CALL. The operational budget that CALL receives each fiscal year as
part of the Combined Arms Center is approximately $67,000.74 These funds are used to
continually run the day to day operations at CALL headquarters, upgrade its IT
architecture, and publish and disseminate its current line of products to clients. In order
to initiate new collection operations or create a CAAT, CALL must first get the approval
of DA. Once approval is granted, CALL can request that CAAT members be tasked
from the various TRADOC Proponent Schools. Additional funds to support the
collection operation will be appropriated to CALL for this mission. This strict control
over what missions CALL can support, by use of its funding and tasking authority, gives
DA the ability to dictate exactly what types of missions CALL should focus its collection

and lessons learned process on.

C.  STRATEGY, TASKS, AND TECHNOLOGY

          An organization’s strategy is the set of concepts that relate its means to its ends.
The strategy defines how an organization’s task procedures and technology will be
employed to produce the end product.’> For CALL, the end product is defined as

    74 Interview with Dr. Lon Seglie, AO Branch Senior Analyst, 16 January 2001.

    75 Thid.
                                                                        67


---

relevant lessons learned that are accessible for use by the total force. All of CALL’s
divisions, except the UAN, are focused on helping the organization reach its end product.
As the Army has moved into a period of greater uncertainty, caused by the requirement to
accomplish any of a diverse spectrum of missions, the speed at which validated TTPs and
lessons are provided has become crucial. To achieve this end product, CALL has
redesigned the means it must use to reach its desired endstate. The redesigned means is
the automation of the key planning, collection, and dissemination tasks to decrease the
time required to take an observation and transform it into a valid relevant lesson learned
or TTP.

            At the operating core level, the information system software CALLCOMS is
designed to increase the efficiency of CAAT team members during the planning and

collection tasks. The CALLCOMS Collection Plan Building module is used by the

CAAT to identify the parent issues and sub-issues that the data are collected for. It also
permits the CAAT to delineate responsibilities of collecting data for the identified
questions among the CAAT members. This functionality prevents redundancy of effort,
since no two CAAT members are assigned to collect data addressing the same parent
issue. It also should prevent members from wasting valuable time collecting observation
data for issues that are outside the scope of the CAAT mission.

For the middle line level, CALLCOMS Issue Tracking module allows the CAAT

Team Chief to keep abreast of the status of each issue. It depicts where in the collection

process that issue is and when events are scheduled that will initiate data for an issue.

This information allows the CAAT Team Chief to ensure that no issue goes unobserved

or to surge resources to more rapidly gather observation data for critical issues.   Once
                                                                                 68


---

observations are ready to be sent to the CALL analyst at Fort Leavenworth, the use of
FTP or E-mail provides an Information Technology framework that permits the seamless
transfer of information between the operating core and the strategic apex.

          For the last task, dissemination, CALL has sought to leverage the use of an
Internet Portal as a mechanism for providing TTPs and lessons learned to its customers.
The Internet Portal is intended to increase the efficiency and effectiveness of the

distribution process in several key ways.

          First, it permits interested users 24-hour access to the latest CALL products in
electronic form from any PC with an Internet connection. This should not only decrease
the dissemination time, because the information does not have to be sent through the U.S.
Postal system, but also increases the number of recipients of the information. The
dissemination of CALL products is no longer limited to Brigade and larger size
organizations, but now any interested soldier can gain access. Secondly, the CALL DB
containing products, TTPs, and lessons learned are also available to users with approved
access via a Web Browser. This functionality, to access the CALL DB through the
Internet, reduces the amount of time it takes for an interested user to search for specific
information contained in CALL’s vast repositories. Instead of requesting information for
CALL, via the telephone as in the past, and waiting for an analyst to search, package, and
send the information to the user, they now can search the DB themselves using the

Retrieval Ware software.

          As with any IT solution, if the fundamental process is good prior to implementing
the IT then productivity and efficiency should result. However, if the process is flawed,

                                                                                 69


---

                                        BO

IT will not solve the problem, but rather further exacerbate it. CALL’s strategy to
improve the collection process tasks by incorporating the use of Information Technology
has seen remarkable results. It was able to take a paperwork intensive task and simplify
and speed up the procedure. With the use of CALLCOMS, the mechanism to transform
an observation into a lesson learned has been reduced from a mean time of 4.21 days to
2.64 days. 76

                               Oiie  0      Ole   Q

                           &0           ai

MeanTime (Days)                2.64         4.21
Standard Deviation (Days)                   1.77
                               1.35

Table 1. Extend Collection Process Model Data

            This reduction of 1.57 days reflects an increase in efficiency of 38% over the
previous process. This increased productiveness enables CALL to quickly pass
knowledge from deployed troops and embed them in the training program for follow-on
troops. This permits units to use others’ lessons to change their behavior prior to
entering an environment where the mistake could be fatal. The importance of this was

evident during Operation Restore Hope when lessons from the 10 Mountain Division
were used to create training scenarios for the 25" Infantry Division’s rotation to JRTC.

The ability to practice likely situations and test TTPs proved invaluable and gave the
soldiers the “feeling that I have already been there before.””7”

           76 See Appendix A for an explanation of the Extend Model used to determine the
collection process time.

           77 Baird, pg. 387.

                                                                                  70


---

         CALL’s use of the Internet Portal to assist in the dissemination of products and
provide access to its information repositories also has shown an increase in efficiency of
that task. It has reduced the mean time to search for information from CALL’s data

repositories from 6.54 days to .902 days.78

                                             Do        e  Do

Mean Time (Days)                                 902          6.54

Standard Deviation (Days)                        2.03         1.49

Table 2. Extend User Access Model Data

This 86% reduction in time can be directly linked to replacing human procedure with an
automated one consisting of a database containing Internet connectivity. This reduction,
however, can be misleading because it is based on all users already having assigned
userids. If the requester does not currently have an assigned userid and password from
CALL, then the actual time savings is minimal at best. This is due to the primitive
process for setting up an account to gain access to the CALL DB, which involves sending

your userid and password through the U.S. Mail. Very few members of the Army are

presently experiencing the actual benefit of this IT solution, because only 3000 accounts

are currently established.

         Information Technology’s ability to provide solutions to key tasks within CALL
is important. CALL’s divisions use IT to facilitate the achievement of the organization’s
mission. It increases the efficiency of the collection and dissemination process and has a
profound impact on the Structure and People variables of the Star Model.

         78 See Appendix A for an explanation of the Extend Model used to determine the

data access process time.

                                                                                     71


---

D.  STRUCTURE

    The organizational structure of CALL can best be described, using the Mintzberg

Framework for Organizational Form, as a Machine Bureaucracy.’? Machine

Bureaucracies generally have highly routine operating tasks, very formalized rules and
procedures, and a distinct chain of command. Although military organizations

traditionally have been seen as a prototypical machine bureaucracies, CALL has some

important modifications to these traditional attributes. (Table 3)

    Attribute               Machine                               CALL

                            Bureaucracy              Standardized Work
                                                     Technostructure
    Coordination Mechanism | Standardized Work       Horizontal/Vertical
                                                     Much
    Key Part of Organization | Technostructure       High
                                                     Product
    Specialization of Jobs  Horizontal/Vertical      Wide bottom, Narrow Top
                                                     Low Level
    Training                Little                   Few
    Indoctrination          Low                      Horizontal Decentralization
                                                     Routine
    Departmentalization     Functional               Complex and Changing
    Unit Size               Wide bottom, Narrow Top  Technocratic
    Control                 High Level
    Liaison Devices         Few
    Decentralization        Limited
    Tech Systems            Routine
    Environment             Simple and Stable
    Power Resides           Technocratic

               Table 3. CALL’s Organizational Form

            One of the key aspects of CALL’s structure is the coordinating mechanism used
throughout the organization. Coordinating Mechanisms are the methods used to
synchronize activities within an organization.80 For CALL, the Lessons Learned Process
is used to transfer knowledge and as coordinating mechanism within the Army. The
“checklist” of Standard Operating Procedures outlined in AR 11-33 and the collection
software CALLCOMS are used to enforce the rules and procedures of the collection

           79 Greenberg, Pg. 297.

           80 Richard Burton and Borge Obel, Strategic Organizational Diagnosis and
Design, Kluwer Academic Publishers, 1998, pg. 4.

                                                                                     72


---

process. For CALL, standardization of work is important because the operating core
composition is different for each CAAT. By maintaining a rigid collection framework
and standardized observation format, CALL can achieve symmetry between the
collection efforts of various CAATs. Because the standardization of work is paramount
for its success, the actual power within CALL resides in what Mintzberg calls the

“Technostructure”. For CALL, the Technostructure consists of the Military and Civihan

Analysts who developed the checklist style SOP that CAAT teams are required to follow.

          Some of the significant attributes in which CALL departs from the traditional
Machine Bureaucracy structure are Training, Control, and Departmentalization. Training
is important to CALL because to be successful in its mission it must provide a vast
amount of training to the OPSO/OPSNCO as well as the CAAT team members. Unlike
most traditional organizations, CALL’s operating core is drawn from other organizations
within its environment (TRADOC proponent schools). Because the operating core is
untrained prior to each collection effort, it is paramount that they receive adequate
training in order for them to provide any relevant data to the organization.

          CALL ensures that CAAT is trained to conduct its collection effort in two ways.
First, they provide a seven day course on the Lessons Learned Process for each team
prior to their deployment. This training teaches them the CALL Methodology and how
to interact with the observed unit, writing skills, and collection planning. Secondly, an
OPSO/OPSNCO from CALL is assigned to assist each CAAT while deployed.
OPSO/OPSNCO are military officers and senior non-commissioned officers who have
received detailed training on the collection methodology by members of the

technostructure.
                                                                                     73


---

Control is another attribute in which CALL’s structure is different from that of a

traditional Machine Bureaucracy. Typically, in a Machine Bureaucracy, decision-

making authority is centralized. Because the environment is stable, the chain of

command dictates exactly what’s expected to employees and anything other than that

must receive special permission.®!  In contrast, the environment CAAT members

operate in is complex and changing. Because CAAT members are widely dispersed and

may have only infrequent e-mail contact with the team chief, they are given wide latitude

on their collection efforts. Although they have specific assigned collection requirements,

which can be tasked in person or transmitted via an Internet connection, they also have

the flexibility to capture observations outside the scope of their responsibility if the

situation arises. This loose control allows for the rapid collection of “target of

opportunity” type observations, without having to wait for approval from high echelons

which may result in missing the collection opportunity altogether.

           The last attribute that is a significant departure from a traditional Machine
Bureaucracy structure is departmentalization. Departmentalization is the general
principle for dividing work and coordinating activities. It is generally revealed by an
organizational chart.82, CALL can be classified as departmentalized by Divisional or
Product. An organization with a divisional structure aims to minimize the
interdependencies between its units, especially when the Information Technology in use

81 Greenberg, pg. 297.
82 Burton, pg. 43.

                                                                      74


---

is a database.83 It is common for organizations that are customer or product oriented to
adopt this configuration.84¢ The reasons for this classification are two-fold. First,
CALL is separated into four major divisions: Lessons Learned, Information Systems,
Research, and University After Next. Each division maintains a certain independence in

developing, testing, processing, and distributing materials in their respective area. This

type of departmentalization creates self contained divisions, each of which are
responsible for everything to do with a product.85 Lastly, the only interdependencies
among CALL’s four branches are linked to the development and implementation of the
CALL DB, which serves as a repository of lessons learned and all the organization’s

work products.

      ' CALL’s coupling of traditional attributes of a Machine Bureaucracy, with a

substantial training program, product configuration, and low level of control have created

an organization that maintains high efficiency while overcoming the dehumanizing and

boring nature of standardized tasks. Information Technology has permitted CALL to

standardize work within the operating core using CALLCOMS and to adopt a product

configuration.

            83 Ibid, pg. 54.
           84 Ibid, pg. 55.
           85 Greenberg, pg. 287.

                                                                                   75


---

E.  PEOPLE

            The People component deals with changes to the skills, training, and development
required of individuals that are part of the workforce. As with most organizations that
have such a wide range of missions and responsibilities, CALL requires a myriad of
individual skill sets.

           CALLs military personnel must have substantial tactical experience in both
command and staff positions and a strong knowledge of current doctrine. The Lessons
Learned Division’s civilian analysts require not only an understanding of current doctrine
and its historical context, but also strong analytical and writing skills. Members of the
UAN Division must possess strong theoretical and analytical skills that will allow them
to envision the emerging knowledge needs of the future force and design systems to meet
those needs. The Research Division’s archivists, historians, record managers, librarians,
and security specialist all require an in-depth understanding of record management and

storage processes.

            With the introduction of Information Technology into CALL’s architecture, the

existing skill set was expanded to meet the challenges that these systems introduce. All

members of the organization require basic computing skills. Members of the LLD are
now required to learn to use the CALLCOMS software and basic TCP/IP skills to
successfully accomplish their work. The biggest change in required skills occurs in the
ISD and RD Branches. Because of the implementation of IT solutions to the collection
process, the RD branch converts from standard file management system to one that is
completely reliant on computer hardware and software. Since the ISD is responsible for

            76


---

maintaining the integrity of the data in CALL DB and the conversion of paper documents
to electronic form, it has had to hire eleven people that have strong technical backgrounds
and showa lot of computer savvy.86 These are different people than were required in the

past.

         The ISD branch was expanded to not only provide local technical support to the
various divisions within CALL, but to maintain the IT architecture itself. This expanded
responsibility included the installation and monitoring of the LAN, Internet Portal, Server
Farm, and in house development of application software. As a result, ISD workers now
require extensive knowledge about TCP/IP, Website management, PC repairs, software

engineering, and coding.

         Initially, CALL’s automation was seen as a method to remove vertical layers of
the organization hierarchy. Computer Information Systems, Databases, and E-mail
increase the average user’s information capacity and eliminate the need for a large middle
management.8? Within CALL, the LLD was able to reduce the number of analysts from
a high of 40, after Operation Desert Storm, to the 10-12 currently used. Even with the
reduction of manning, the use of IT systems has diminished overall time to transform
observations into lessons or TTPs. A by-product of the incorporation of IT, however,
has been a significant increase in the number of personnel required to support the current
architecture. In recent years, the LLD branch has seen a reduction in the number of
analysts, while the ISD and RD Branches personnel requirements have increased by 25%.

          86 Interview with Dr. Scott Lackey, Chief ISD Branch, 16 January 2001.

            87 Burton, pg. 214.

                                                                                     77


---

            The skill level and capacity of the People variable helps define the tasks and
processes that an organization can adopt and the structure that will best facilitate an
increase in efficiency.88 Even so, an organization’s Reward System direct impacts its
ability to attract and retain qualified personnel.

F. | REWARD SYSTEM

           Closely tied to the People component is the organization’s Reward System. This
component includes organizational incentives to motivate and inspire the operating core
to achieve its tasks. Rewards generally are classified as intrinsic (psychological rewards
from membership) or extrinsic (rewards received from others).89 In the Army, a number
of rather intangible concepts such as duty, honor, selfless service, esprit de corps,

reputation, and inclusion in the tradition of the institution are important factors in the

force’s intrinsic non-task reward system. These values are important to motivating the

civilian and military analysts who are responsible for the collection and dissemination

portion of CALL missions.
            In addition to the values that serve as the foundation of the Army, CALL has an

additional factor that helps it to motivate its members. This important factor is task
significance. Task significance is the impact the work is believed to have on others.%0
Because soldiers’ lives may be at stake, members of CALL know the importance of not

           88 Ibid. pg. 212.
           89 Kenneth Thomas and Erik Jansen, “Intrinsic Motivation In The Military,” Eight
Quadrennial Review of Military Compensation, September 1996, pg. 6.
           90 Greenberg, pg. 71.

                                                                                  78


---

only doing a thorough job, but also ensuring it is completed in a timely manner. Failure
to do so could result in the loss of lives, while success can assist units in achieving their
mission. Task significance leads to members of CALL experiencing a sense of
meaningfulness in their work, internal work motivation, and a high level of job

satisfaction.

          However, these intangible factors only can be expected to do so much to improve
efficiency within CALL. CALL must build a valuable extrinsic reward package on top of
these core values to help sustain its work force. Because of the diverse interests of the
members of CALL, the Branch chiefs tailor a reward package to meet their work forces
particular needs. In most cases this package includes a very limited combination of
education, promotion, monetary, and family incentives.

          The first incentive is to increase the educational opportunities within the
organization. As with any organization that has a high reliance on Information
Technology to conduct its mission, CALL uses technology training and certification as a
reward for superior job performance. This allows the individual to gain additional
proficiency sets, which can then be used to achieve skill variety within their respective
division. Skill variety adds to the meaningfulness of the work experience and generally
increases job satisfaction. Increasing the workers IT skills, however, can have
unintended results. As CALL has increased the training and certification opportunities of
its members, it has raised. individuals’ marketability to outside organizations and resulted

in a significant turnover in the ISD and RD Branches.
          The financial incentives that CALL can implement are limited within the

framework of existing Federal statues. Managers have the ability to grant their civilian

                                                                                   79


---

employees with step increases aS a bonus for superior job performance. Military
members are not authorized to pay bonuses for performance. Because of the lack of
availability of financial incentives, CALL finds it difficult to compete with civilian
organizations to retain some of its critical technological skill workers. Another incentive
is to reward superior job performance with time off. This generally is very effective with
the military members of the organization. Increasing the amount of time that a service
member is home with their family reduces the traditional strains found in many military
families. Thus promotion becomes the primary means of unnecessary compensation.

           Promotion is another traditional incentive that has limited application within
CALL. Because a significant amount of the organization are active duty military
members, they are subject to centralized promotion boards. Although their performance

while assigned to CALL is evaluated on an OER or NCOER, it does little to influence

their actual promotion. This is due to the nature of centralized promotion boards putting

increased weight on job performance in key leadership positions such as command and

primary staff. Since the positions at CALL do not fall into this category, they are
generally weighted less when the board convenes. However, the civilian members of
CALL can be selected for promotion within the organization based on job performance.

              The current Reward System used by CALL has some significant deficiencies. It
currently is structured to rely heavily on the intrinsic motivating factors and not the
extrinsic rewards. As CALL continues to exploit cutting edge technological solutions to
solve its collection and dissemination missions, CALL struggles to maintain its technical
support personnel. The more training and educational opportunities it provides the higher
the likelihood workers with these new skill sets will seek a civilian job opportunity with

                                                                                 80


---

greater pay. Without comparable promotion and financial incentives, CALL will not be
able to compete with the civilian workforce and face qualified personnel shortages.

G.  CULTURE

         A key to the success or failure of any organization to attain productivity is the
influence that culture has on its operation. Culture comprises the “values, norms, and
expectations shared by the organization’s members.”?! The culture provides members
with a sense of identity, enhances commitment to the organization’s mission, and
reinforces standards of behavior.°2 At the root of the organization’s culture is a set of
core characteristics that are valued by its members. For the Army, a core characteristic
that has emerged is an openness of communication.

         The openness of communication comes from the fact that “good ideas have a high
currency when lives are at stake.”93 Leaders and the led conduct an open dialogue to
reflect on why actions occur and finding appropriate solutions. The idea is that
“information is not a source of power but an objective commodity that belongs to the
organization, not to individuals.”°4 This leads to the rewarding of individuals who share
information, as being team players, not necessarily those who come up with the idea. It

         91 Charles O’Reilly, “Managing Organizational Culture”, California Management

Review, 1989, pg. 289.

           92 Greenberg, pg. 258.
           93 Henderson, pg. 106.
           94 Thid.

                                                                                   81


---

is this openness that provides input to the lessons learned process and allows CALL to
successfully conduct its mission.

            To support the Army’s culture, CALL sees itself as the fundamental mechanism
for sharing information across its parent organization. Its focus on “what units are doing,
not who is doing it”? also supports the values of teamwork and not seeking personal
credit for ideas. By establishing a method that supports the unanimity of sources for
lessons, CALL is reinforcing the idea that members of the Army can be creative in their
use of TTPs. Leaders are allowed to be innovative and take reasonable risks. If they are
successful, their new methods are spread through the entire force; if they fail, they are
free to learn from their mistakes without reprisal.

            Another important function of CALL’s culture is its ability to stress the
importance of the organization’s mission to members of the CAAT team that are
temporarily assigned to the organization. During their methodology training, members
of the LLD Branch reinforce the idea that sharing of information in critical by reminding
the CAAT members “everything boils down to making sure the soldier in harms way has
the knowledge needed to prevail and survive.”®6 By transmitting information through
stories about how CALL products have successfully impacted units in the past, it is able
to introduce its core value to these members.

            Within CALL, as most large diverse organizations, multiple subcultures exist.
Two distinct subcultures have emerged along functional lines. One supports the core

           95 Interview with DR. Lon Seglie, AO Branch Senior Analyst, 16 January 2001.
           96 Tbid.

                                                                                   82


---

characteristic of the Army to promote openness of communication through the sharing of
information; the other values the promotion of innovation. Although both subcultures
accept the role of CALL, conflict exists when the organization’s budget is allocated.?”

         The first subgroup is composed of the elements that were part of CALL when it
was founded in 1985. It includes elements of the LLD, ISD, and RD. This group feels
that the most important core value of the organization is the facilitation of sharing
information within the Army. They have accepted the use of Information Technology as
a means to achieving this value, but feel that the core function of CALL should remain
providing support to soldier. If funds are to be allocated, this group feels that they
should be used to support the production of more frequent products, assist collection
operations, or on the IT architecture to augment the support to the user.?8

          The other subculture is composed of former pieces of the Army Knowledge
Network. It includes the elements of UAN and RD. This group feels the most important
core value is the promotion of innovation. This group sees IT as a method for providing
enterprise-wide knowledge and learning management for the Army After Next. They
value the innovation above everything else. If funds are to be allocated, this subculture
feels it should be used to find solutions to tomorrow’s challenges even if they diminish
CALL effectiveness today. They are exploring cutting edge technology solutions for
knowledge tools, knowledge applications, and learning applications.

          97 Interview with Ken Vanderpool, Chief ISD Branch, 17 January 2001.
           98 Ibid.

                                                                                   83


---

            CALL’s use of IT has created two distinct subcultures within the organization.
One sees the technology as a method to support the Task policy variable. The other sees

CALL’s primary role as serving as testbed for future innovations for the force. The close

relationship between the Culture and People policy variables is evident by which
individuals support each subculture. Those individuals who use IT to assist them
complete their work, such as analysts, OPSO/OPNCOS, and historians feel it is a means
to an end. The members of the organization with strong technical backgrounds and
responsible for maintaining the IT architecture, want to see it continue to maintain a
cutting edge level.

H.  INFORMATION AND DECISION PROCESSES

            This component of the model includes the organization’s decision mechanisms,
the information the organization requires, and controls to make sure information is
disseminated to its client base. As with most organizations that adopt IT solutions,
CALL believed it could exploit the information processing power of the computer to
improve service to its customers.2? IT provides CALL with a method for decision-
making, formalized data, and data transmissio!n00.

            CALL’s mechanism for decision making is contained within the various modules
of the CALLCOMS software. During the Mission Analysis phase of the collection
operations, the Collection Plan Building module is used by the CAAT to identify the
parent issues and sub-issues for which the data will be collected. This serves as the

    99 Galbraith, pg. 25.

    100 Thid. pg. 27.
                                                                       84


---

blueprint for the entire collection operation. As issues are identified, the CAAT Team
Chief can assign collection assets (team members) to each area to ensure comprehensive

coverage of the problem areas.

          Once the Collection Phase of the operation begins, the CALLCOMS Issue
Tracking module allows the CAAT Team Chief to keep abreast of the collection effort. It
depicts the current collection status of each issue, when the next event is scheduled that
will likely initiate data, and what resources have been allocated to the issue. This
provides the decision-maker with a greater understanding of the problem and real-time
information to permit the surging of resources to an issue, if necessary.

          Finally, during the Analysis Phase of the operation, the CALLCOMS Trend
Analysis module allows CALL to use mathematical models to identify existing trends in
the observation data that it receives from the CAAT. This data can be used to modify the
CAAT’s current collection plan. Modification may result in additional resources or time
being given to an issue that has shown to be a troublesome trend during analysis or needs
further development. The Trend Analysis also can identify issues that may need
coverage in a topical CALL newsletter or other publication. This supports the rapid
transmittal of information to the force to correct a deficiency or problem area.

          IT supports the formalization of data by creating categories and storage

schemes.!01 CALL uses two methods to formalize data. The first is the use of a
standardized observation collection form. As part of the active collection process, the
form is part of the CALLCOMS software and is used by CAAT members to annotate the

            101 Thid, pg. 25.

                                                                                  85


---

task, condition, and information of each observation. For passive collection, a shell form
is located on the CALL Web Site and allows users to enter the required information,
which is then transmitted, to an analyst for review. Presently, CALL’s active collection
process has provided a valuable means to formalize data, however since the passive input
method has not experienced high user volume it has cause the adaptation of Active-
Passive collection.

            The second method of formalization is found in storage of data. Whether the
observation is active or passive, once it has been entered into the CALLCOMS DB it is
categorized for storage by the relevant BOS that it supports. Users can then search

CALLCOMS by BOS to identify various observations. The Trend Analysis module’s

models scour the stored data for recurring trends also use the BOS tags. This allows the

formalized data to be fed back into the decision process.!0?
            The CALL DB contains operations orders, situation reports, CTC take home

packages, all final exercise reports, all training lessons learned and user feedback on
articles from previous CALL publications. These documents are tagged using several
methods: the Library of Congress subject coding system, attributes of the event (i.e. time,
location, date, or operation), according to the task, conditions, and standards applied by
the CAAT team, or a simple word search. The RetrievalWare software that CALL
utilizes to support user access into the DB supports searching for documents using any of
the tagging methods or a simple word search.

            102 Tbid.
                                                                                   86


---

          The last important aspect of this component is the methods that data are
transmitted to the organization clients. For CALL, it has sought to augment, and later
replace, its paper product mailing with an Internet web page that provides access to all of
its products and services. CALL sees the use of the web page and IT as “the way to do a
better job getting our products to the Army.”!®3 = For CALL to be an effective
organization, it must be able to facilitate the transfer of knowledge among its clients and
change its behavior when required. Providing a valued service that is widely used by the

Army can only do this.

         Although 75% of the respondents believe that information and products from
CALL were of great value to the Army, most felt that the products were underutilized.!%4

This is due to two prevalent problems. The first is that the current paper products are in

limited distribution down to the Brigade level. This leaves most of the individuals who

derive the greatest benefit from the TTPs that CALL produces without direct access to

the paper copies. CALL has identified this as a large problem and has hoped the Internet

would provide it with an easy solution. Asa fix to this dissemination problem, the CALL
Web Page provides access to all of it products and controlled access to’ its databases.
This has not occurred due to a lack of access to computer systems, a lack of knowledge in
the userbase about this service, and the bureaucratic method used to gain access to the

databases.

          103 Interview with Dr. Lon Seglie, AO Senior Analyst, 17 January 2001.
          104 See Appendix B for information on survey questions, scope, and

methodology.
                                                                                   87


---

            Currently most soldiers in the Army do not have direct access to computer
systems or Internet connection in there work place. In most units, automation tools and
e-mail accounts are limited to commanders and primary staff officers. This prevents the
average soldier or leader from logging on to CALL’s webpage while on duty to download
current CALL products. If they do have access to a computer at home, they must also

use a much slower connection to download or search for data than would be available

from a T-1 LAN connection at the workplace.

            Another problem is CALL’s new dissemination process. It faces a lack of user
knowledge about its existence. 41.9% of company grade officers who had just come
from serving in key leadership positions as company commanders or platoon leaders did
not even know that CALL had a website or provided its products via the Internet. Of
those who knew about the web site, only 33% even used the service.!95 If CALL wants
to use the Internet as its primary dissemination method, it needs to increase users’
awareness of its existence. As one respondent claimed “CALL is a misnomer, it should
be called Center for Lessons Storage, because information does not make it to the actual
user.”

           The last issue is access to CALL databases. Because of the sensitivity of some of
the information it possesses, CALL maintains tight control over access to its data.
However, the bureaucratic process for setting up an account to gain access to the CALL
DB, which involves sending a userid and password through the U.S. Mail, takes too long
to be of any service. Only 3000 registered users currently have access to the

            105 See Appendix B for survey results.

                                                                                   88


---

CALLDB.!% Ifa soldier tries to use CALL to find a quick answer to a training issue or
a TTP and has to wait days for a response, they are not likely use the resource again in
the future. To be a more effective resource and provide a mechanism to change behavior
and impact training, access must be more widely disseminated.

I.  SUMMARY

         Understanding the dynamics of CALL’s design is essential to analyze the
efficiency of its process and how effectively it achieves the organization’s stated goal or
mission. By looking at the organization through the six policy variables, one can see that
many aspects of the organization are in congruence. The incorporation of IT has had an
impact on all of the variables, however the Structure, Information and Decision Process,
and Tasks variables need to be modified if CALL is to increase its process efficiency.
One must remember, though, because the variables are interdependent, that a change in
one variable can result in a change in any of the others for better or worse.

    106 January 2001 CALL DB Usage Statistics.

                                                                       89


---

THIS PAGE INTENTIONALLY LEFT BLANK
                                             90


---

    VII. CONCLUSIONS AND RECOMMENDATIONS

A.  CONCLUSIONS

         During the early 1990’s an information technology architecture was introduced at
CALL as means to improve the existing lessons learned process. Up until this time
CALL had produced “little of enduring value because data overwhelmed our pencil-and-
paper system.”!07 The goal of senior Army leadership was to use the capabilities of the
technology to increase the efficiency of both the collection and dissemination of lessons
throughout the Army. CALL’s improved rapid process would result in a significant
increase to the effectiveness of all combat units.!}08 After six years, the information
technology architecture and organizational design that CALL established has mixed

results. Although it has shown a significant increase in its collection process efficiency,

the dissemination of information has not provided either the efficiency or effectiveness

that initially was sought.

            The incorporation of information technology on the collection process has
increased efficiency because of a congruence between the policy variables of the Star
Model, especially the Task, Structure, Information and Decision Processes variables.
The key technologies that have helped achieve this congruence is the CALLCOMS
software application and the FTP functionality of the Internet. CALLCOMS has
provided the planning tools to assist the CAAT develop and manage its collection effort

    107 Sullivan, pg. 208.
    108 Tid. pg. 204.

                                                                         91


---

(Task Variable). It supports the standardization of the collection process tasks so that the
quality of data remains relatively consistent between CAATs (Structure Variable). It also
provides a means to formalize the data so that it can be categorized and stored for later
use by CALL analysts or clients (Information and Decision Process Variable) . The use
of FTP protocol facilitates the need to accomplish more with fewer personnel because it
allows a flattening of the organizational hierarchy through a internetted information
process (Structure and People Variables).

            This congruence of variables has resulted in the reduction in time required to
produce new and validated lessons to the force. In Somalia, CALL had an average 4-5
days turn around from observation to validated lesson;!9? this was reduced to 2-3 day
during Operations in Bosnia and Kosovo.!!9 This analytical data is supported by the
empirical data gather from the Extend models that found the reduction in time to be from
4.21 to 2.64, or a 38% improvement in efficiency of the collection process.

            While the effect of information technology on the dissemination process has not
produced the intended improvements its has had significant positive impact. CALL’s
dissemination process seems to be better suited to aid units that are preparing for large
scale deployments. This is because they follow a product “push” dissemination strategy.
This strategy identifies lessons or knowledge that would be useful to the force and sends
it directly to the force. During preparations for operations in Haiti, CALL tapped into its
existing database and developed tailored soldier handbooks to cover customs, TTPs, and

           109 Henderson, pg. 105
           110 Interview with CPT Leo Nascimento, 16 January 2001.

                                                                                 92


---

small unit procedures for conducting peacekeeping missions. These products were

“pushed” to member of the 10" Mountain Division before they deployed as part of the
train-up. They also were able to use the efficiency of the collection process to develop
“push” scenario packages for units to rehearse operational tasks while at the CTCs before

they deployed.!!!| The success of these type “push” products is evident in the 25"

Infantry Division’s experience in Haiti where they faced 23 of 26 JRTC scenarios that

CALL developed for their pre-deployment train-up.!!2

         The incongruence of the dissemination process is due to a disconnect between the

Task, Structure, and Information Variables associated with the “pull” distribution
strategy. This incongruence has created a dissemination process that is not efficient and

reduces the overall effectiveness of the organization. The intent of the CALL Webpage
is to allow users to gain quick access to information when they need something (Task
Variable) .113 However, the existing bureaucratic process for setting up an account to
gain access to the CALL DB, which involves sending a userid and password through the
U.S. Mail, takes too long to be of any service (Task Variable). If a soldier tries to use

CALL to find a quick answer to a training issue or a TTP and has to wait days for a

response, they will not likely use the resource again in the future. Using empirical data
from the Extend model, if a user does not already possess access to the CALLDB then it
takes 22% longer to get information then simply contacting CALL via the telephone and

             111 Henderson, pg. 105.
             112 Baird, pg. 387.
             113 Sullivan, pg. 209.

                                                                                   93


---

asking an analyst to find the information for them. Since, the incorporation of
information technology has flattened the organizational hierarchy, few analysts are
available to provide this service (Structure Variable).

            The intended “pull” of information has not occurred on a wide scale due to a lack
of access to computer systems, a lack of knowledge in the user-base about this service,
and the bureaucratic method used to gain access to the databases (Information Variable).

Because the degree to which CALL achieves it goals depends on the quality of the work

it publishes and its usefulness, if its customer-base does not know of its services or use it
products, then it is not effective.!14 My study found that 41.9% of company grade
officers who had just come from serving in key leadership positions as company
commanders or platoon leaders did not even know that CALL had a website or provided

its products via the Internet. of those who knew about the web site, only 33% used the

service.!15_ One respondent to the survey stated, “CALL produces good observations,
but they are not widely used because they are not widely disseminated.”!!6 In fact the
top organizations outside of CALL and DOIM to access the CALLDB are CAS3, DoD
Contractors, CGSC, and Fort McClellan.!!7__ This indicates that most of the requests
came from members of the service not currently in key leadership positions but are
currently obtaining military education. To be a more effective resource and provide a

            114 Henderson, pg. 112.
            115 See Appendix B for survey results.
           116 CALL User Survey Conducted on 1-5 Feb 01 at Fort Knox, Kentucky.
            117 January 2001 CALL DB Usage Statistics.

                                                                                94


---

mechanism to change behavior and impact training, access must be more widely

disseminated to members of FORSCOM.

B. RECOMMENDATIONS

          Although CALL has shown a significant increase in its collection process
efficiency, the dissemination of information has not provided the efficiency or
effectiveness that was initially sought. The following changes to the existing process
would improve CALL’s performance in these key areas:

          e Increase user-base knowledge by going to TRADOC proponent schools and
                informing soldiers of CALL’s products and services.

          e Use push distribution strategy of products down to company/platoon level e-

                  mail accounts.

          e Assign userids and passwords to all key leader positions down to platoon
                leader and require unit S-3 to manage passwords. S-3 shops can contact
               CALL to update passwords as new platoon leaders assume the position.

          The first change will increase potential clients’ knowledge of the services that

CALL can provide. By going to the TRADOC schools and conducting a one to two hour ,

briefing as part of the Officer Basic, Officer Advance, and CAS3 courses, they will teach
young officers about CALL and its services and reinforce the importance of information
sharing. Officers exposed to this information early in their careers, will be more likely to
realize the benefit of CALL and seek out their products or assistance. This should greatly
improve the number of users and increase CALL’s impact as the Army’s learning

mechanism.

          As more Army units become linked via post LANs or use of the Internet, CALL
can exploit this medium to further increase it reach. They can use the no-cost electronic

                                                                                 95


---

distribution of its products via E-mail to extend its dispersion from Brigade to
company/platoon level. This will put CALL products in the hands of key leaders all the
way down to the lowest levels of the organization. This type of deep penetration into the
organization hierarchy will provide another substantial positive impact on CALL
effectiveness to create shared learning across the organization. The challenge in this
“push” distribution is to get and update E-mail addresses of all potential cents. This can
be done by maintaining close contact with the MACOM Chief Information Officers or
through a standardization of unit E-mail addresses that are linked to position not
individual names.

            The last recommendation is to assign userids and passwords to all key leader
positions down to and including platoon leader positions. This will allow any officer
serving in a leadership position to gain access to the restricted CALL database. Soldiers
then will be able, through their first line leader, to get information, TTPs, and documents
to assist training without incurring a substantial time lag. This will reinforce the use of
CALL, its TTPs and lessons because of its responsiveness as an asset that is widely
available. The difficulty in this method of creating widespread access to the CALL DB is
in maintaining control of the userids and passwords. This function can be done at the
Battalion level, by the S-3 Training Office. The S-3 can request the necessary userids
and passwords and assign them to their current leaders. Once a leader transfers out of
that position, the S-3 will contact CALL and request that a new password be issued for
that position account. Again the key is not to link the userid to a person, but rather a
position. Centralizing the management of the accounts at the Battalion Operations and
Training Office level, ensures that the individual responsible for the overall training plan

                                                                                   96


---

of the organization also is responsible for providing and encouraging access to CALL’s

products and services.

          The impact of these changes within the Army would be significant. Not only
would CALL show an increase in the efficiency of its dissemination of information, but,

more importantly, it would provide a deeper penetration into organizations’ client-base.
This penetration would improve CALL’s effectiveness because its products would be

better known, easily accessed, and widely used.

                                                                                   97


---

THIS PAGE INTENTIONALLY LEFT BLANK
                                            98


---

            APPENDIX A. SIMULATION MODELS OF CALL’S
 COLLECTION PROCESS AND USER ACCESS TO THE CALL DB

A. EXTEND SIMULATION SOFTWARE
          The purpose of using the Extend model software is to develop a logical

description ofhow a system performs a real world activity. This model can be used for
carrying out experiments on the system over time to determine inefficiencies of design
and identify chokepoints or problem areas before actual implementation.!!8

          The Extend software creates a representation of the key tasks that CALL must
perform in order to accomplish their mission. These results serve as a way to measure
the impact that the incorporation of IT has had on the collection process and the ability of
CALL’s customers to rapidly gain access to the products and lessons that the

organization produces and manages.

          To determine the impact that IT has had on the efficiency of the process, four
models were developed to replicate the previous and current CALL process for collecting
and analyzing observations and user access to information contained m.CALL’s data
storage repositories. The data used as a basis for the input variables for the models are
derived from interviews with members of CALL, historical data provided by the ISD and
AO Branch, or from personnel observations of the execution of specific tasks by either

members or clients of CALL.

            118 Extend User Manual, Imagine That Inc, 1997, pg. 4.
                                                                                   99


---

GENERAL MODEL ASSUMPTIONS
The following assumptions were used in the development of the basic models:
1. Collection Process Models.
e CAAT Team Members’ general writing and processing of observations does

      not improve significantly over the 30-60 days that they are deployed.

e Since CAAT SMEs have similar military experience, service time, and skills,

     they do not have significantly different observation processing success rates.
e Work day is 18 hours, 7 days a week.
e Each simulation represents 30 days of collection effort.
e Communication link to CALL is established before collection operations

      begin.
e All Internet connections are made using a 56K modem, while all faxes use a

      14.4K modem.
2. Database Access Models.
e Access to information is available 24 hours, 7 days a week.
e Users requiring access are members of the United States Armed Forces only.
e All requests via Internet will be made using a 56K modem.
e All requests without IT will be vid telephone.
e The Internet portal does not experience any significant down time that

       prevents user access.

e Users know exactly what information they want to search for and the topics
      are located in CALL’s database.

                                                                     100


---

C. CALL OBSERVATION COLLECTION PROCESS MODEL USING

           INFORMATION TECHNOLOGY
             1. Purpose.
          The purpose of this model is to depict the current CALL observation collection

process that includes various types of Information Technology. (Figure 7) This process
incorporates the use of the CALLCOMS software to assist CAAT members in the
planning, collection, and processing of observations in the field. It also depicts the use

                          Figure 7. CAAT Observation Collection Process w/IT
of FTP, to transmit CALLCOMS forms from forward deployed locations to CALL at
Fort Leavenworth via established communication links.

           2. Key Tasks Depicted in the Model.
          The following tasks are pivotal in the accurate depiction of this process:

                 Observation Collection.
                 Draft CALLCOMS Form.
                 Review Observations by CAAT Team Chief.
                 Returned to CAAT SME for Refinement.
                  Analyst Review.

                                                                                  101


---

e Analyst Input nto CALLCOM DB.

3. Explanation of Key Task Blocks and the Data Used for Each Task.

a.  Observation Collection.

This block of the model simulates the CAAT SMEs’ daily collection of

observations throughout their deployment in the theater of actual operations. There are

usually 3-5 observations a day that arrive to the system in a Poisson distribution with a

mean value of 6 hours per observation.

b.  Draft CALLCOMS Form.

This block depicts the time that it takes a CAAT member to record their

observations in the correct format using the CALLCOMS application software on their

assigned PC. This value is calculated by a random number generator following a normal

distribution with a mean of 2 hours and a standard deviation of 1.

c.  Review Observations by CAAT Team Chief.

                        This hierarchical block depicts the series of tasks that a CAAT Team

Chief must complete to evaluate a CAAT member’s CALLCOMS observation for

relevance, completeness, accuracy, and grammatical errors. The team chief receives the

file by either uploading the CAAT member’s electronic file from a floppy disk onto his

PC or receiving it via FTP. It begins with a review by the team chief that takes a time-

value based on a random number generator following a normal distribution with a mean

of 1.5 hours and a standard deviation of 1. Once it has been reviewed, the CALLCOMS

observation is passed to a decision block that simulates the success rate that observation

will have in being approved on the first attempt. Since the observation is in electronic

form, minor adjustments can be made by the team chief to speed the process up. The
                                                                                  102


---

historical rate of success on first drafts is 30%. If the observation is approved, it is sent to
the Analyst Review task via FTP. If the observation fails, it is sent to the Returned to
CAAT SME for Refinement task.

                       d. Returned to CAAT SME for Refinement.

                     This hierarchical block depicts the series of tasks that occur when a CAAT
Team Member gets a CALLCOMS observation returned by the CAAT Team Chief for
corrections. The team member makes the necessary adjustments and forwards the
CALLCOMS observation back to the team chief for another review. The time that the
rewrite requires is based on a random number generator following a normal distribution
with a mean of 2 hours and a standard deviation of 1. The team chief review time is
based on a random number generator following a normal distribution with a mean of 1.5

hours and a standard deviation of 1. Once it has been reviewed, the CALLCOMS

observation is passed to a decision block which simulates the success rate that

observation will have in being approved on the second attempt. The historical rate of

success on second drafts is 70%. If the observation is approved, it is sent to the Analyst
Review task via FTP. If the observation fails, it is passed to the Returned to CAAT SME

for major rework.

                         e. Analyst Review.

                     This block depicts the tasks that occur when CALLCOMS observation is
FTPed to the civilian analyst at Fort Leavenworth. The analyst receives the observation

and then reviews it for content relevance, and grammatical errors. This value is

calculated by a random number generator following a normal distribution with a mean of
2 hours and a standard deviation of 1. Once it has been evaluated, the observation is

                                                                                  103


---

passed to a decision block that to determine if it is sent back to the CAAT for content

refinement or validation. The historical rate of validation is 40%.

f  Analyst Input into CALLCOM DB.

This block depicts a CALLCOMS observation that has been validated by

the CAAT Team Chief and FTPed to the civilian analyst at Fort Leavenworth for input

into the CALLCOMS DB. This value is calculated by a random number generator

following a normal distribution with a mean of 3 hours and a standard deviation of 1.5.

The large standard deviation is based on the priority of the analyst’s effort for reviewing
observations and providing feedback to the deployed CAAT, not on immediate input to

the database.

D. CALL OBSERVATION COLLECTION PROCESS BEFORE USING

INFORMATION TECHNOLOGY
             1. Purpose.
            The purpose of this model is to depict the previous CALL observation collection

process that did not include the use of Information Technology solutions. (Figure8)
This process incorporates the use of a “Paper and Pencil” system by the CAAT to aid in
the collection and processing of observations in the field. It also depicts the use of fax
machines or US Mail carriers to transmit CALLCOMS forms from forward deployed
locations to CALL at Fort Leavenworth.

            2. Key Tasks Depicted in the Model.
            The following tasks are pivotal in the accurate depiction of this process:
            e Observation Collection.

                                                                                  104


---

e Draft Observation Manual Form.
e Review Observations by CAAT Team Chief.
e Returned to CAAT SME for Refinement.
e Analyst Review Observations.
e Observations Typed by CALL.

    Figure 8. CAAT Observation Collection Process w/o IT

3. Explanation of Key Task Blocks and Data Used for Each Task.

a.  Observation Collection.

This block of the model simulates the CAAT SMEs’ daily collection of

observations throughout their deployment in the theater of actual operations. There are

usually 3-5 observations a day that arrive to the system in a Poisson distribution with a

mean value of 6 hours per observation.

b.  Draft Observation Manual Form.

This block depicts the time that it takes a CAAT member to manually

record their observation in the correct format using preprinted paper observation shells.
This value is calculated by a random number generator following a normal distribution

with a mean of 2 hours and a standard deviation of 1.

                                        105


---

c.                Review Observations by CAAT Team Chief.

This hierarchical block depicts the series of tasks that a CAAT Team

Chief must complete to evaluate a CAAT member’s observation for relevance,

completeness, accuracy, and grammatical errors. The team chief receives the paper form

when it is hand delivered by the CAAT SME. It begins with a review by the team chief

that takes a time-value based on a random number generator following a normal

distribution with a mean of 2 hours and a standard deviation of 1. Once it has been

reviewed the observation is passed to a decision block that simulates the success rate that

observation has of being approved on the first attempt. Since the observation is in paper

form, corrections can be written on the page to assist the SME. The historical rate of

success on first drafts is 30%. If the observation is approved, it is faxed to the Analyst

Review task. If the observation fails, it is passed to the Returned to CAAT SME for

Refinement task.  Returned to CAAT SMEfor Refinement.

              d.

This hierarchical block depicts the series of tasks that occur when a CAAT

Team Member gets an observation returned by the CAAT Team Chief for corrections.

The team member rewrites the observation, making the necessary adjustments and

delivers the corrected observation back to the team chief for another review. The time

that the rewrite requires is based on a random number generator following a normal

distribution with a mean of 3 hours and a standard deviation of 2. The team chief review

time is based on a random number generator following a normal distribution with a mean

of 1.5 hours and a standard deviation of 1. Once it has been reviewed, the observation is

passed to a decision block which simulates the success rate that observation will have of

                  106


---

being approved on the second attempt. The historical rate of success on second drafts is
70%. If the observation is approved it is faxed to the Analyst Review task. If the
observation fails, it is passed to the Returned to CAAT SME for major rework.

e. Analyst Review Observation.

This block depicts the tasks that occur when an observation is faxed to the

civilian analyst at Fort Leavenworth. The analyst receives the observation and reviews it
for content, relevance, and grammatical errors. This value is calculated by a random
number generator following a normal distribution with a mean of 2 hours and a standard
deviation of 1. Once it has been evaluated, the observation is passed to a decision block
that will determine if it is sent back to the CAAT for content refinement or validation.

The historical rate of validation is 40%.

f  Observation Typed by CALL.

                     This block depicts an observation that is validated by the CAAT Team
Chief and faxed to the civilian analyst at Fort Leavenworth for typing so it can be
included in the final product report. This value is calculated by a random number
generator following a normal distribution with a mean of 6 hours and a standard deviation
of 2. The large standard deviation is based on the typing being done by CALL secretaries

as a secondary responsibility.

                                           107


---

E. USER ACCESS TO LESSONS IN CALL DB USING CURRENT
INFORMATION TECHNOLOGY

             1. Purpose.
            The purpose of this model is to depict the current process that clients of CALL
use to access information, products, and TTP from the CALL DB. (Figure 9) This
process incorporates the use of an Internet Portal to gain access to the CALL DB from
various installations around the US and the world. It also depicts the use of Excalibur
Retrieval Ware to search and present files on the Client PC where they can be stored or
printed for use.

                                        Figure 9. User Access to CALL DB w/IT
             2. Key Tasks Depicted in the Model.
            The following tasks are pivotal in the accurate depiction of this process:
             e CALL Web Page Receives a Request.
             e User has Access.
             e Requests Password Be Issued.
             e Search Database.
             e Download Product.

                                                                                108


---

3. Explanation of Key Task Blocks and Data Used for Each Task.

a.  CALL Web Page Receives a Request.

This block of the model depicts when a client uses the Internet to gain

access to the CALL Gateway and signs on to gain access to the CALL DB. There are
usually 5-10 attempts a day to gain access to the CALL DB. These attempts arrive in a

Poisson distribution with a mean value of 2 hours per observation.

             b. | User has Access.

                   This block is a decision variable. It is used to route the user to the
database if they previously have been assigned a userid and password. If they do not
have a userid, they are routed to the Request Password Be Issued task. 75% of users who

want to gain access will already possess a userid and password.

c.  Requests Password Be Issued.

                   This hierarchical block depicts the series of tasks that occur whena client
needs to request a userid and password from CALL to gain access to the CALL DB. The
user fills out a request form on the CALL web page and transmits it to the CALL
headquarters section. The time to complete this task is calculated by a random number
generator following a normal distribution with a mean of .25 hours and a standard

deviation of 1. Once the request has been submitted, CALL confirms the user’s need for

access by contacting their military chain-of-command. This task has a mean time of 12
hours with a standard deviation of 2. Once confirmation of the user’s need for access is

ascertained, the request is forwarded to the CALL Director for final approval. This task

has a 75% probability of success. If approval is granted, a userid and password is issued
and mailed to the requester via US Mail. This task is a uniform distribution with a

    109


---

maximum time of 6 days and a minimum of 2 days. If the request is denied, a letter

informing the client of why the request was turned down is sent via US Mail as well.

d.  Search Database.

This activity depicts the user searching the CALL DB with Excalibur

Retrieval Ware to find the information, TTPs, or products they require from CALL. The

time of this task is determined by a random number generator using a normal distribution

with a mean of 1 hour with a standard deviation of 1.

e.  Download Product.

This activity simulates the user downloading the required products from

the CALL DB using a 56k-modem communication link. The time of this task is

determined by a random number generator creating a file size between 1OKB and 50MB

and then dividing the file size by the connection speed.

F. USER ACCESS TO LESSONS PRIOR TO CURRENT INFORMATION
      TECHNOLOGY ARCHITECTURE
             1. Purpose.
            The purpose of this model is to depict the previous process that clients of CALL

use to access information, products, and TTP from the CALL DB. (Figure 10) This
process illustrates the use of a telephone to call in a request for assistance to CALL.
Once CALL receives the request, it is assigned to one of the three civilian analysts. The

analyst searches through CALL’s information repositories and packages the information

for the user. The information is then sent to the user via the US Mail.

                       110


---

2. Key Tasks Depicted in the Model.
The following tasks are pivotal in the accurate depiction of this process:
e CALL Receives a Request from a Client.
e Analyst Searches for Information.

° Information Sent to User via US Mail.

                  ie  Asniyst #2  TS                       Information /Publication
                  re  fearch DB
                                        — in                   MattionUngex
                       |
                                                 ‘mio tad

                      Analyst #3
                      Search DS

              Figure 10. User Access to CALL Lessons Learned w/o IT

3. Explanation of Key Task Blocks and Data Used for Each Task.

              a.  CALL Receives a Requestfrom a Client.

              This block of the model depicts when a client contacts CALL via

telephone to request assistance on finding information, a particular CALL product, or

copies of current TTPs. There are usually 2-3 attempts to gain information from CALL

a day that arrive to the system in a Poisson distribution with a mean value of 12 hours per

observation.

                                  111


---

b.  Analyst Searches for Information.

This activity depicts the hierarchical process that the civilian analyst

undergoes in searching the CALL repositories and products to find the requested

information and then tailor the products to meet the client’s specific needs. The time for

the task of finding the required information is determined by a random number generator

using a normal distribution with a mean of 12 hour with a standard deviation of 2. Once

the information has been identified, the next task is tailoring and packaging the

information so it can be mailed to the client. The time for this task is determined using a

normal distribution with a mean of 12 hours and a standard deviation of 1.

c.  Information Sent to User via US Mail.

                        This task depicts the time it takes for the tailored package of information

to be sent via US Mail to the client. This task is a uniform distribution with a maximum

time of 6 days and a minimum of 2 days.

G. SIMULATION RESULTS

To simulate the Observation Collection Process, each of the models was run for a

duration of 30 days, which is about the standard amount of time that a CAAT does actual

collection operations. Table 1 depicts the results of the simulations.

                              QO  ()      QO  0

                           P           P         0

# of 30 Day Simulations            5           5
# Observations                   602         587
Total Time (Days)             1589.28     2471.27
MeanTime (Days)                 2.64        4.21
Standard Deviation (Days)       1.35         1.77
Confidence Level                 18           24

    Table 3. Extend Collection Process Model Data
                                                  112


---

To measure user accessibility to information from CALL, the two simulations for these
process were run multiple times for a duration of 60 days each. The results are listed in

Table 4.

          # of 60 Day Simulations    Databa   Data A
          # Observations
          Total Time (Days)               3                  Q
          Mean Time (Days)              492
          Standard Deviation (Days)   444.12         3
                                        .902       135
                                       2.03      882.53
                                                  6.54
                                                   1.49

          Table 4. Extend User Access Model Data

                                     113


---

THIS PAGE INTENTIONALLY LEFT BLANK
                                             114


---

                 APPENDIX B. SURVEY OF CALL CLIENTS

A. SURVEY DESIGN

          The survey was designed to collect both objective and subjective data. The
purpose of the objective survey items is to collect data on the specific level of users
knowledge of the services that CALL provides for members of the Army. Subjective
items were included to gather the perceptions and opinions of the users on the
effectiveness of CALL in providing meaningful lessons, products, or TTPs.

B. SELECTION OF RESPONDENTS
          The focus of the selection of respondents was to identify the group within the

Army to whom CALL products are primarily targeted. Since most of CALL’s products
are oriented on the tactical level of doctrine and focus on Brigade and lower level topics,
its key target group is company grade officers.

          The reason that company grade officers are a critical target group is two fold.
First, they serve in many of the key company and platoon leadership positions throughout
the Army. In these positions they are responsible for the planning and supervision of the
individual and collective training within their units and deployment during combat. If
CALL’s products can effect the way training is planned or the method by which it is
conducted, through its TTPs and lessons, it will be disseminated down to the individual
level resulting in the widest possible impact on the force. Secondly, a key aspect of the
Army’s Officer Professional Development Program is based on commander’s training
their subordinates on the latest warfighting Tactics, Techniques, and Procedures. CALL

                                                                                    115


---

can identify itself as an invaluable asset earlier in these officers’ careers, it is likely that
they will use the latest TTPs outlined in CALL products in the development of their
subordinates and throughout the remainder of their careers.

            Once the key target group was identified, they could be questioned to provide
insights on CALL’s products, dissemination channels, and overall impact on training.
Thirty-Five respondents were identified to participate in the survey from the Combined

Arms Officer Advance Course at Fort Knox, Kentucky. All of the respondents were

required to have a general knowledge of CALL’s mission within the Army. They
included representatives from all the major combat arms branches to include Armor,
Infantry, Field Artillery, and Aviation. Additionally, each respondent was required to
have served as a Platoon Leader or Executive Officer and at least one-third of the
respondents had to serve as a Company Commander or a Battalion Staff Officer.

C. SURVEY INSTRUMENT

         The survey instrument used a combination of yes/no questions reflecting user’s

knowledge of the services provided by CALL, as well as open ended questions designed
to gain subjective perceptions about CALL effectiveness. Respondents were informed
that research would be conducted on a non-attribution basis, and that they would remain

anonymous. It was believed that anonymous input would result in a more candid

disclosure of information. The survey contained three sections.

                                                                                116


---

1.  Section One.

Section one asked respondents to answer questions concerning aspects of their

military career, to include: Current Rank, Duty Status, Branch, Duty Positions Served,

Duty Stations, and Number of Years in Service. This information was used to ensure that

a wide breadth of experiences throughout the Army would be sampled.

2.  Section Two.

Section two contained questions to determine the respondents knowledge of

CALL, the services that it provides, and the level of their interaction with the

organization. Participants were asked to answer a series of objective yes/no questions on

CALL, its products, and the Information Technology solutions they currently employ.

The answers to these questions will provide data that is an adequate representation of the

company grade officer’s overall knowledge and usage of CALL products and services.

The questions from section two of the survey are shown as Figure 11.

                  Sectian Two

                  1. Have you ever read a CALL Product?

                                                                                                             YES:     xO
                                                                                                                             vA

                                                                                                                      :
                  Ww  Have you ever directly used » TTP suggestion or other intermation trom e CALL
                      product to improve your training?

                  ”                                                                         YES

                      Did you know CALL has # website with s dstabese ofall lesyon-learned products
                      thom the past and current copics ofproducts on the Internet?

                                                                                YES
                  4. Have you ever wed CALL’s webpage?

                                                                            YES
                  S$. Have you ever-comacted CALL for ssyistance?

                                                                                                             YES

                  6 Have you ever provided input to CALL?

                                                                                                             YES

                  7. What media formst have you seen used tbr CALL products?

                  ~                                                                                       D           PAPER      WEB
                                                                                                       bel
                               el

                  3. How afien do you read materiel Som CALL?

                      Dee | Seldom [ ‘Once s                                                                ‘Grartcrly | Sent ] Weekiy | Contant |

                                                                               cost

                  9. If you answer yes to Question 1. Which publications have you reod?

                      CHC i CPC Ory | ETC Trends | Specific Tope | eal | CALL
                      Seends_ {Bulletins Aninis                                                              ewslets  Front | Newsletter

    Figure 11. User Survey Section Two

                                                                                                             117


---

3.  Section Three.

Section three gathered respondent’s subjective opinions of CALL’s impact on the

Amy, adaptation of Information Technology to disseminate lessons learned, and which

clients get the greatest utility from its products. Respondents were given the opportunity

to give a brief narrative to explain the factors that influenced their answer. The questions

from section three of the survey are shown as Figure 12.

    Section Three
    1, What Individuals get the most utility out ofCALL’s products?

    2, inyour experience, at what level is CALL's products disseminated down to?

    finoiv 7 PLT                   co                  BN            BpE |

    fs that an appropriate level?

    3. Do you think CALL’s el      ic/Web Based di     ination strategy is warking?

    4. What do you think is CALLs impact on the Army?

    5. What could CALL do differently to have a better impact?

                                            Figure 12. User Survey Section Three

D. SURVEY RESPONSE STATISTICS
             Of the 35 surveys that were sent out to prospective respondents, a total of 31 were

returned for a response rate of 88.6%. Responses were received from members of all
the combat arms branches. Additionally, 83.9% of the responses had served as both a
Platoon Leader and Company Executive Officer, 41.9% had served as Company
Commander, and 45.2% as a Battalion Staff Officer. The cumulative experience level of

                                                                                  118


---

the response was sufficient in finding that the sample provides adequate data to reach
general conclusions on the scope of company grade officer’s knowledge of CALL and its
products. The collected data is also sufficient to reach findings on the effectiveness of

CALL in achieving its mission, at least within this key target group. A summary of
survey section two response findings are depicted in Table 6 and Table 7 .

                   Survey Section Two Results

Questions
Question5
Question4 Ere
Question3 EEE

Question 2 os

Question1 -~

0.0% 10.0%         20.0% 30.0% 40.0% 800% 60.0%       70.0% 80.0%     90.0% 100.0%

       Question 1  Question 2  Question 3 Question 4     Question §  Question 6

wNo     _ 3.7%       45.2%     41.9%  54.8%                80.6%       86.2%
& Yes    90.3%       54.8%     58.1%  45.2%                19.4%        13.8%

                                    Percentage

                                     Table 6. Survey Section Two Results For Questions 1-6

           Survey section three results identified 75% of the respondents feeling that
information and products from CALL were of value to the Army and company grade
officer in particular, however they felt that the products were under utilized. Their
various reasons included: Paper copies not being disseminated by Battalion senior
leadership to their units, CALL not “advertising” the usefulness of its products, or lack of
access to computer systems that are linked to the Internet or with E-mail capability.
Another important finding is the respondents answer to the question concerning which
group within the Army gets the most utility from CALLs products. 40% of the subjective

                               119


---

answers identified company grade officers serving in commander or battalion staff

positions, an additional 20% ofthe responses identified small unit leaders at the company

Queston 7, Medias Formats Employed                 Queston §. CALL Product Usage

                                                   Contausily

- Co) Monty fie a
     Paper                                         Weekly . on
     57%                                           a% >»
eo 10%
e40v%al<(# ->                                      Qua1r3t%erly {| Seldom
wer                                                                23%

                                                         "nee

2%             Question 9. Publications Users Have ncav

               CALL Newsletter      CTC Trends
                        27%              26%

               Fram The Front!              19%
                                    jer ‘trends
                      8%
                Topic Newsietters        Analysis

                             47%

                                    11%

Table 7. Survey Section Two Results For Questions 7-9

or lower level. These indicate that CALL users agree that the key group for CALL to
target to improve the use of its services is the company grade officer.

                                                   120


---

                                                LIST OF REFERENCES

1989 CAC Annual Command Histories, Center For Army Lesson Learned, pg. 191-192.
1990 CAC Annual Command Histories, Center For Army Lesson Learned, pg. 94.

Baird, Lloyd, John C. Henderson, and Stephanie Watts, “Learning From Action: An

Analysis of the Center for Army Lessons Learned”, Human Resource Management,

Winter 1997, Volume 36, pg. 385-395.

Brock, Geoffrey E., “Information Retrieval Tools for Knowledge Management,” Patricia

Seybold’s Workgroup Computing Report, January 1998.

Buddenburg, Rex, “What’s Wrong with DoD Information Architectures,”

http://web] .nps.navy.mil/~budden, March 2000.

Burton, Richard and Borge Obel, Strategic Organizational Diagnosis and Design, Kluwer

Academic Publishers, 1998.

Chapman, Anne W., Carol J. Lilly,John L. Romjue and Susan Canedy, Prepare The Army
For War: A Historical Overview of the Army Training and Doctrine Command
1973-1998, Military History Office, United States Army Training and Doctrine Command,

Fort Monroe, Virginia 1998.

Center for Army Lessons Learned Web Site, http://www.call.army.mil.

Center for Army Lessons Learned, CALL Handbook 97-13, United States Anny

Combined Arms Center, Fort Leavenworth, Kansas.
                , CALL Handbook 96-02, United States Army Combined Arms Center, Fort

Leavenworth, Kansas.

                , Memorandum for Record, 27 February 1995, Subject: ADCST Input to

Annual Command History Report, United States Army Combined Arms Center, Fort

Leavenworth, Kansas.

              , Memorandum for Information, 11 September 1989, Subject: The Center for
Army Lessons Learned Overview, United States Army Combined Arms Center, Fort

Leavenworth, Kansas.

                , “Learning Lessons in a Force Projection Army”, CALL Newsletter 93-02,
United States Army Combined Arms Center, Fort Leavenworth, Kansas, May 1993.

Combs, Andrew, “N-Tier Client Server Architectures,” www.ilt.com/AEDIS/Ntier.

                                                                                  121


---

U.S. Army Combined Arms Center Web Site, http://www.army.mil.cac.

Galbraith, Jay R., Organizational Design, Addison Wesley Publishing Company, 1976

Garvin, David A. “Building A Learning Organization”, Harvard Business Review, July-
August 1993, pg. 78-91.

General Accounting Office Web Site, http://www.gao.gov.
Greenberg, Jerald. Managing Behavior In Organizations, Prentice Hall, 1999.

Extend User Manual, Imagine That Inc, 1997,

Heijst, Gertjan, “Organizing Corporate Memories”, http://spuds.cpsc.ucalragy.ca/KAW,
1996.

Henderson, John C., Stephanie Watts Sussman, and James B. Thomas, “Creating and
Exploiting Knowledge For Fast Cycle Organizational Response: The Center for Army
Lessons Learned”, Advances In Applied Business Strategy, Volume 5, 1998, pg 103-
128.

Holder, L.D. and Edward Fitzgerald. “The Center for Army Lessons Learned: Winning
in the Information Age”, Military Review, July-August 1997.

Inspector General Department of Defense, “Review of Department of Defense Lessons
Learned Programs”, September 1994.

Kim, Danie] H, “The Link between Individual and Organizational Learning,”    Sloan
Management Review, Fall 1993, pg. 36-49.

McCaskey, Michael. “Framework for Analyzing Work Groups”, Harvard Business
School, 1997.

Nadler, David A. and Michael Tushman. “Organization, Congruence, and Effectiveness”,
Organizational Dynamics, Autumn 1980.

O’Reilly, Charles. “Managing Organizational Culture”, California Management Review,
1989.

Ricks, Thomas E. “Lessons Learned: Army Devises System To Decide What Does and
Does Not Work”, The Wall Street Journal, 23 May 1997, pg. Al.

Seglie, Lon, “The Army Transformation- Learning While Doing”, Military Review,
September-October 2000, pg. 44-47.

                                             122


---

Starry, Michael Starry “It’s Not The Same Old Army,” Armed Forces Journal, October

1995.

Sullivan, Gordon R. and Michael V. Harper, Hope is Not A Method, Random House,

1996.

Thomas, Kenneth and Erik Jansen. “Intrinsic Motivation In The Military,” Fight
Quadrennial Review of Military Compensation, September 1996.

United States General Accounting Office, “Army Training: National Training Center’s

Potential Has Not Been Realized”, GAO/NSIAD 86-130, 23 July 1986.
                , “Army Training: Prioritizing and Follow up on Lessons Learned Should

Minimize Recurring Weaknesses”, GAO/NSIAD 93-231, 16 September 1993.
                , “Military Training: Potential to Use Lessons Learned to Avoid Past

Mistakes Is Largely Untapped”, GAO/NSIAD 95-152, 9 August 1995.
                , “Army Training: Full Training Benefits From Army’s Combat Training

Centers Are Not Being Realized”, GAO/NSIAD 99-210, 16 September 1999.
University After Next Pamphlet, TRADOC Program Office for University After Next,

U.S. Army TRADOC, 1999.

                                                                                  123


---

THIS PAGE INTENTIONALLY LEFT BLANK
                                            124


---

INITIAL DISTRIBUTION LIST

- Defense Technical Information Center...cccsssssscccccessessecceeeecncceeeeeeesssssnecerseaeeseseees
         8725 John J. Kingman Road, Suite 0944
         Ft. Belvoir, VA 22060-6218

. Dudley Knox Library.................4 errr errr errrrrr rrrrr rr rr rrr rr eretrer iter
         Naval Postgraduate School
         411 Dyer Road
         Monterey, CA 93943-5101

. Professor Erik Jansen, Code CC/EKveccssccssssssssssecosssesscssessesuessesscesussessvenesasesecsstssseseesseese

         Naval Postgraduate School
         Monterey, CA 93943

. Professor Shelley Gallup, Code JW/SG........cecccccsccsseeseesseeseeneerseserenserserseneenereeeesenenens
         Naval Postgraduate School
         Monterey, CA 93943

. CPT Anthony M. Wizner...............eer errr rT rer rrr rrr rrTererrrr rrr rere rit rite  ere
          1168 Hidden Creek Circle
         Hickory, NC 28602

. William Wizner...........ceeeeeccceeeee
         8544 Stone Harbor Avenue
         Las Vegas, NV 89145

. Center For Army Lessons Learned

          201 Augur Avenue

         Fort Leavenworth, KS 66027-1314

                                           125


--- 