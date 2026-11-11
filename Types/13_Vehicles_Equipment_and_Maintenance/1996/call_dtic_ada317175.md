# call_dtic_ada317175  ARI Contractor Report 96-82

Battle Command Training Program Database Development

William E. Walsh, Jack A. Briscoe,
Terry P. Bartkoski, and Brad J. Gill
BDM Federal, Inc.

              DTIC QUALITY INSPECTED 2

19961031 098

                     This report is published to meet legal and contractual requirements and may not
                                    meet ARI’s scientific or professional standards for publication.

September 1996

United States Army Research Institute for the Behavioral and Social Sciences
Approved for pulbic release; distribution is unlimited


---

U.S. ARMY RESEARCH INSTITUTE
FOR THE BEHAVIORAL AND SOCIAL SCIENCES

A Field Operating Agency Under the Jurisdiction
of the Deputy Chief of Staff for Personnel

                                                 EDGAR M. JOHNSON
                                                 Director

                                                                              NOTICES

DISTRIBUTION: This report has been cleared for release to the Defense Technical Information Center
(DTIC) to comply with regulatory requirements. It has been given no primary distribution other than to
DTIC and will be available only through DTIC or the National Technical Information Service (NTIS).

FINAL DISPOSITION: This report may be destroyed when it is no longer needed. Please do not return
it to the U.S. Army Research Institute for the Behavioral and Social Sciences.

NOTE: The views, opinions and findings in this report are those of the author(s) and should not be
construed as an official Department of the Army position, policy, or decision, unless so designated by
other authorized documents.


---

REPORT DOCUMENTATION PAGE                                                                           Form Approved

                                                                                                 OMB No. 0704-0188

Public reporting burden for this collection of information is estimated to average 1 hour per response, including the time for reviewing instructions, searching existing

data sources, gathering and maintaining the data needed, and completing and reviewing the collection of information. Send comments reaardina this burden estimate

or_any aspect of this collection of information, including suqgestions for reducing this burden to Washington Headquarters Services, Directorate for Information

1. AGENCY USE ONLY (Leave blank)          2. REPORT DATE       3. REPORT TYPE AND DATES COVERED

                                          September 1996 | Final   Jun 93 - Nov 95

4, TITLE AND SUBTITLE                                                                             5. FUNDING NUMBERS

Battle Command Training Program Database Development                                  MDA903-92-D-0075

6. AUTHOR(S)                                                             623007

Walsh, William E., Brisco, Jack A., Bartkoski, Terry P., Gill, Brad J.   A793

                                                                         1 122

                                                                         C02

7. PERFORMING ORGANIZATION NAME(S) AND ADDRESS(ES)                       8. PERFORMING ORGANIZATION
                                                                             REPORT NUMBER
BDM Federal, anc.
1801 Randolph Street, SE                                                   —_
Albuquerque, NM 87106

9. SPONSORING/MONITORING AGENCY NAME(S) AND ADDRESS(ES)                    10. SPONSORING/MONITORING
                                                                                AGENCY REPORT NUMBER
U.S. Army Research Institute for the Behavioral and Social Sciences
ATTN: PERI-RK                                                            Contractor Report 96-82
5001 Eisenhower Avenue
Alexandria, VA 22333-5600

11. SUPPLEMENTARY NOTES

Contracting Officer’s Representative, Michael R. McCluskey. This report is published to
meet legal and contractual requirements and may not meet ARI's scientific or

professional standards for publication.

12a. DISTRIBUTION/AVAILABILITY STATEMENT                                 12b. DISTRIBUTION CODE

Approved for public release;

distribution is unlimited.

13. ABSTRACT (Maximum 200 words)

             The primary objective of this BCTP Database Development effort was to provide a prototype
database system encompassing corps, division, and brigade echelon operations conducted during BCTP
training. The intent of the database is to increase the utility and accessibility of BCTP data for all users by
extending development work on the prototype to provide for wide area access. The prototype BCTPdb
contains nearly complete data from two BCTP WFXs and Final Exercise Reports from six WFXs. In
contrast to the legacy databases for the maneuver CTCs, the BCTPdb, through three users’ tests, has
demonstrated the functionality necessary for a database common to all the CTCs. It is the intention of the
Center for Army Lessons Learned that the BCTPdb become the cornerstone of a CTC Common database
to be developed on an enterprise architecture plan which will provide for global access. This report
contains The Final Report, Data Dictionary, User's Guide, Loading Procedures Guide, Converted Data
Structures description, and the PowerBuilder User Interface description.

14. SUBJECT TERMS                         Performance measurement  BCTP                          15. NUMBER OF PAGES

Database Lessons learned                                                                         16. PRICE CODE

Battle Command                                                                                   20. LIMITATION OF ABSTRACT

   17. SECURITY CLASSIFICATION    18. SECURITY CLASSIFICATION  19. SECURITY CLASSIFICATION       Unlimited
        OF REPORT                      OF THIS PAGE                 OF THIS ABSTRACT
                                                                                                    Standard Form 298 (Rev 2-89)
 Unclassified                     Unclassified                 Unclassified                         Prescribed by ANSI Std 239-18

NSN 7540-01-280-5500                                                                                      298 102


---

                                                                                                                                        CONTRACT #: MDA 903-92-D-0075
                                                                                                                                                    DELIVERABLE #: 0018-0018AM
                                                                                                                                                                                   NOVEMBER 29, 1994

                        FINAL REPORT:
BATTLE COMMAND TRAINING PROGRAM

             DATABASE DEVELOPMENT

                                                  William E. Walsh

                                               BDM Federal Zac.
                Submitted by: Mr. Michael R. McCluskey, Acting Chief

                                Unit-Collective Training Research Unit
                                             and Jack Hiller, Director

                                        Training Research Laboratory
          Mr. Michael R. McCluskey, Contracting Officer's Representative

                      a re AY tt

                                               N MY RES Pant {NSHITUTE

                                                December 20, 1994
                                         U.S. Army Research Institute


---

                                   FINAL REPORT:
BATTLE COMMAND TRAINING PROGRAM DATABASE

                                  DEVELOPMENT

                                                  Page

I. INTRODUCTION ...... 0.0e . e. e . eee 1

A. Trace Changes in Division Training Practices ........................ 1

B. Uncover Common Themes ...............0 0.000   e ne 2

I]. OBJECTIVE .. 0.. eee. eee ees 2

Ill. PROJECT SUMMARY ....0. 0.00.. 0000. e .e .. e . ee. eee. eee 3

IV. BCTP DATABASE ENHANCEMENTS ..........0.00 0.000000. ccc eee 6

V. PROJECT DELIVERABLES ..... 000. 200. 0000. c . c. c..0 eee 7

VI. DATA LOADING COST ANALYSIS ........0.00. 00000000000 cee eee 8
            A. Summary of the Previous Five Tables...............0........00... 11
            B. Data Tables That Will Require Data to be Collected ................... 11
            C. Efficiency and Reliability Suggestions: ........000.....000....0000. 12

VII. REFERENCES .........0..0 200000000 cee      eee eee 14


---

                        FINAL REPORT:

         BATTLE COMMAND TRAINING PROGRAM
                       DATABASE DEVELOPMENT

                                                           I. INTRODUCTION

           The need to improve command and control functioning, particularly at echelons above
brigade, is a recognized concern of long standing within the Army. The Battle Command
Training Program (BCTP) is an important training program established by the Army to
improve command and control of combined arms forces. The U.S. Army established the
BCTP in 1987 to train division and corps commanding generals and their staffs. The BCTP
is a Chief of Staff initiative that applies computer technology as a tool to train the war
planning, war fighting and decision making skills at the division and corps levels.

            A BCTP cycle begins with reading material sent to the training unit, followed by a
five-day Battle Seminar, in which the unit commander, primary staff, and subordinate
commanders all engage in decision exercises and workshops on AirLand Battle doctrine.
From three weeks to seven months after the Battle Seminar, the BCTP conducts a week-long,
computer-driven WarFighter Exercise (WFX) using the unit's organic equipment. The BCTP
cycle, and in particular the WFX, features extensive observation and critique in the form of
After Action Reviews (AARs).

             The BCTP provides a superb training experience and an excellent source of feedback
to the training unit. The long term assessment of the BCTP will be based on how it provides
feedback to improve unit performance and how it contributes to the Army's development of
doctrine and battlefield operating procedures. The feedback will be based on the data
generated by the BCTP WarFighter Exercises and the database used to store Warfighter data.
The BCTP Database has the potential to provide a rich source of information for studying
both short and long term Army higher-echelon command and control issues. Potential uses
for this database include:

A. Trace Changes in Division Training Practices

            The performance areas to sustain and improve that are identified during the AARs and
the discussion of lessons learned that characterizes the unit commander's AAR at the end of
the exercise provide information that can be used to construct a well-formulated list of unit
training objectives.


---

B. Uncover Common Themes

           The information provided by the BCTP has a value beyond feedback to individual
divisions and corps. Analyzing WarFighter data from several BCTP cycles can produce
evidence pointing to systematic strengths and weaknesses in higher-echelon command and
control doctrine and training. The use of a database derived from the BCTP experience can
bring home lessons learned in a more formal and perhaps more accurate way.

           The development of a BCTP database has occurred over several years and produced
several research products. A BCTP Requirements Analysis was performed to determine what
issues, within each Battlefield Operating System (BOS), were of greatest interest to the
potential community of users of a BCTP database. This analysis was conducted by soliciting
input from Army Organizations having an interest in data derived from the WF Xs conducted
by BCTP. The BCTP Front End Analysis provided the specifications for the BCTP research
database. It summarized the BCTP operational environment, specific duties and
responsibilities of BCTP and contract staff, the Battle Command Seminar, the WarFighter
Exercise, and the data produced during BCTP exercises. The BCTP Database Specification
document described how the data from rotations at BCTP could be integrated into the Combat
Training Center (CTC) Archive databases. The BCTP Database Concept presented a
comparison of BCTP data and CTC Archive data along with a concept for the organization of
BCTP data within the framework of the CTC Archive concept.

            The primary objective of the current BCTP Database Development effort is to provide
a prototype database system encompassing corps, division, and brigade echelon operations
conducted during BCTP training. The intent of the database is to increase the utility and
accessibility of BCTP data for all users. Development of the prototype database was based
upon work performed during Delivery Order 1 ( BCTP Database - Front End Analysis,
Requirements, and Specifications ). The current database implementation process has
followed an iterative approach with several prototype versions of the database serving as
milestones along the way. The final prototype version of the database within this delivery
order will serve as the basis for a later operational version which will be integrated into the
CTC Warrior Information Network.

                                                                 I]. OBJECTIVE

            The purpose of this report is to document the incremental development of the
prototype Battle Command Training Program (BCTP) research database. This database
implementation effort started in June 1993 and included a seventeen month period of
performance. Four versions of the prototype database were developed during this project.
This report will include a chronological project summary, BCTP database enhancements,
descriptions of the project deliverables, and a data loading cost analysis.


---

   Ill. PROJECT SUMMARY

            We initiated the project by preparing a comprehensive work plan to guide the effort
during the period of performance. Our plan clearly defined the objective of the project and
the intended purposes of the prototype research database. Within the plan we provided a
technical overview to describe the problem and our technical approach to the solution. Our
approach to developing the BCTP database, as described in our work plan, was designed to be
iterative in nature. Building on the Front End Analysis and Requirements Specification
developed during Delivery Order 1, we set out to create and test four versions of the
prototype. Our plan called for various data types to be incorporated into the database as data
structures were developed to accommodate the different data types. The organization of the
BCTP data, as described in the work plan, was to be based on TRADOC PAM 11-9, the
Blueprint of the Battlefield.

           The following section outlines the progression of BCTP database developmental efforts
during Delivery Order 18:

PROTOTYPE VERSION 1.0 - DECEMBER 1993

User Interface: Provided access mechanisms for Unit Performance and Unit
                            Generated Data

Data Sources. Final Exercise Reports and Unit Operations Orders

Notes:
 1. Attended the 4ID Warfighter Exercise at Ft. Carson.

2. Received and inventoried 4ID, 6ID, 35ID, and 38ID WarFighter data.

3. Developed a Draft Data Collection Strategy for the customer.

 4. Established initial data archiving procedures at Ft. Leavenworthin preparation
for the loading of the database.

5. Demonstrated the initial user interface with access mechanisms to ARI on 9
December 1993.

 6. Conducted the informal tryout test of the prototype with users at Ft. Leavenworth
and POM in December 1993.

 7. As a result of the demonstration and user test we focused our implementation
efforts in the following areas:

°  Expanding the list of data sources


---

                                    Implementing a multi-window environment

                                   Improving the display of graphics

                                  Incorporating statistical operations

PROTOTYPE VERSION 2.0 - FEBRUARY 1994

           User Interface: Added access mechanisms for Automated Journal System
                                    (AJS) Reports, Battle Description Data, Objective Data, and
                                     Unit Rotational Data

           Data Sources: Added Battlefield Intel Collection Model Data, Objective Data
                                      and Battle Summary Data

            Tools/Functionality:

                                  Incorporated capability to view After Action Review video

                                  Modified graphics viewing by incorporating PaintShop Pro

                                   Added Quattro Pro spreadsheet capability to enhance the use of
                                    Objective Data

                                    Expanded rotational data window by including the capability to review
                                     White Cell Data

                                    Activated the Battle Description Button which presents AJS and Battle
                                      Summary Data

                                    Extended the user interface to accommodate the new data types that
                                     were entered into the database

                                    Revised Unit Generated Data access mechanisms by adding pop-up
                                   windows for Operation Orders, FRAGOs, and reports.

             Notes:

              1. The database loading priorities for the second prototype were the 4ID and
              35ID WFX rotations.

              2. Investigated the use of the Media Support Center for scanning and OCR

             3. Conducted the Initial Tryout Test of the prototype in February 1994.


---

PROTOTYPE VERSION 3.0 - AUGUST 1994

User Interface:  Added access mechanisms for the OPFOR, Good Ideas,
                 Trends and ACCES components of the prototype;
                 expanded access mechanism for Objective Data

Data Sources: Added Corps Battle Simulation (CBS) Data, Intel Journal System

                          (1JS) Data, OPFOR Data, ACCES Data

Tools/Functionality:

.  Added the capability to explore effective unit training practices

   (Good Ideas) and common operational procedures (Trends)

°  Improved word search tool

°  Activated the analyst notebook feature

.  Tested the BCTP Database within the network at Ft. Leavenworth

Notes:

 1. Requested that the following data sources be provided for entry into the
database:

                                       Senior Observer Notes
                                      White Cell Directives
                                      O/C Raw Notes
                                       Analyst Generated Data

 2. Conducted a User Tryout Test in August 1994.

PROTOTYPE VERSION 4.0 - NOVEMBER 1994

User Interface. Modified BCTP Database user interface to accommodate
                         digitized video

Data Sources: Final Exercise Reports, Unit Generated Data, and ACCES Data

Tools/Functionality:

°                Implemented the digitized AAR capability, created CD-ROM containing

                 AAR video


---

        °  Developed a Windows-style user help system

        .  Implemented the battle replay tool using SUN shots

        °  Developed the WarFighter Reporting System (WRS) Journal review

           function

        °  Created a user tracking system

Notes:

 1. Delivered the final versions of the User's Guide, Data Dictionary, and Loading
Procedures Guide.

2. Delivered documentation and source code for the Functional BCTP Database.

3. An executable version of the software has been created and delivered to the
Center for Army Lessons Learned (CALL) to support further network testing.

 4. An identical copy of the prototype is installed on the development PC at
ARI/POM.

5. The BCTP prototype contains data from the following units: 2AD94, 4ID93,
41D94, 61D93, 25ID93, and 35ID93.

 6. The Good Ideas component of the database contains BDA data extracted from
4ID93 WarFighter data sources.

                                       IV. BCTP DATABASE ENHANCEMENTS

             The continued development of the BCTP relational database during fiscal year 1995
and beyond will involve the transfer of the database prototype from its current development
environment (FoxPro) and the integration of the BCTP database into the client/server
configuration of the CTC Warrior Information Network (WIN) Database with Informix
serving as the database back end. The CTC WIN Database will reside on UNIX servers with
a PowerBuilder front end providing access to all CTC data. The WIN functional design will
incorporate and link the BCTP Database and the CTC Legacy Database (initially only the
NTC) in a CTC relational database that will integrate existing data structures, user interfaces,
data sources, and environments in order to provide powerful new capabilities for using and
sharing CTC training data) The BCTP database and the other WIN databases will be linked
to and supported by the Automated Historical Archives System (AHAS) with its powerful
document imaging and retrieval capabilities. The continued development of the BCTP
database will also involve an increase in the inherent functionality of the current BCTP


---

Database prototype.

           The integration of the BCTP Database into the Army Knowledge Network will be a
major enhancement to the functionality of the prototype and will provide powerful new ways
for sharing CTC training data. In addition, there are several functional areas of the BCTP
Database prototype that we recommend for improvement during fiscal year 1995 and beyond.
The following list identifies several potential areas of enhancement for the current BCTP

prototype:

°  Continue loading of the database with a loading interface

   (to include historical WFX data)

.  A data collection methodology for WFX data

*  Add BCBST and OOTW data to the database

°  Fully developed video digitization capability

°  Access to position/location data generated by the CBS model

°  Access to WFX terrain

°  Add a database reference library

.  Expand objective trend and good ideas capabilities

                                                  V. PROJECT DELIVERABLES

            The major products that were produced during the development of the BCTP Database
prototype are described below. During the period of performance for this project we
developed, delivered and demonstrated four versions of the prototype database.

            ¢ The Loading Procedures Guide documents all processes required to load the
            BCTP Relational Database Prototype. It describes the pre-processing procedures that
            are required to handle all of the available data types. The loading procedures are
            arranged by BCTP data type and provide the instructions for loading the database
            tables.

            ¢ The Data Dictionary describes the format of the data structures. It is organized
            by the individual FoxPro tables and includes explicit descriptions of the data by type.
            It contains a summary of all tables that have been created, and provides information


---

        concerning data element names and types, number of records per rotation, size, and
         element description.

        * The User's Guide provides detailed instructions for accessing the prototype
        database. It contains a guided tour of the user interface and a complete description of
        the prototype research tools and techniques. The guide provides the user with graphic
        screen displays and step-by-step examples of database access procedures.

        * The Test Reports document how users responded to the prototype database in
        terms of usefulness, completeness of data, ease of access, and relevance to actual

         issues.

         * The Prototype Database is a hardware/software set which allows users to examine
        the kinds of data available from the BCTP. The prototype is a database system which
        makes use of a graphical user interface (GUI) in the Microsoft Windows environment.
        The prototype has been implemented as a FoxPro/Windows (version 2.6) application
        that runs under Microsoft Windows 3.1. The prototype requires the following external
         Windows applications:

                                             Quattro Pro for Windows, version 5.0, Novell
                                              Paint Shop Pro, version 2.01, JASC, Inc.
                                             Norton Desktop Editor, version 2.2, Symantec
                                             BCTP Replay Program, version 1.0, written in Visual Basic 3.0

              The system has been tested in a stand-alone configuration on a 66Mhz 486
computer with 8MB of RAM at Ft. Leavenworth and at POM.

VI. DATA LOADING COST ANALYSIS  '

            This section provides an estimate of the cost, in terms of time, of updating and
maintaining the BCTP Database in the future. The following tables contain the average times
required to load specific data types into the prototype database. The tables also identify the
number of documents, by data type, that should be expected for each rotation. An asterisk
identifies a data type for which a loading time estimate is not currently available.


---

                            Unit Generated Data

     Data Type   Number     Time per          Loading Task performed by:

                 of items        Item

OPORDs           6 total    36 Hrs total      Loader with Guidance from the
   CORP                1          12 Hrs      Analyst
    DIV                 1         12 Hrs
   BDE's               4
                                3 Hrs ea

FRAGOs           140 total  | 28 Hrs total       Loader with Guidance from the
   CORP              30          6.5 Min ea   | Analyst
   DIV                50         12.5 min ea
   BDE's             60           14 min ea

Reports & Requests | 50     11 Hrs total      Loader with Guidance from the
                                13 min ea     Analyst

OPFOR Orders,    18         7 Hrs total       Loader with Guidance from the
                                              Analyst
Reports, etc

                           Unit Performance Data

     Data Type   Number     Time per          Loading Task performed by:
                  of items      Item

FER              1          15 Hrs            Loader with Guidance from the
                                              Analyst
O/C Orders X-Walk | 1       3 Hrs             Loader with Guidance from the
                                              Analyst
AAR Videos       3          18 Hrs for 3      Analyst
                                 6 Hrs ea
ACCESS           1                            Loader with Guidance from the
                            4 Hrs             Analyst

                                            Rotational Information Data

SS |

     Data Type   Number     Time per          Loading Task performed by:
                  of items      Item

White Cell Data  20         7 Hrs total       Loader with Guidance from the
                                              Analyst


---

                          Battle Description Data

       Data Type  Number        Time per  Loading Task performed by:
Overview
Video Narrative    of items         Item
Time Line
* WRS Journal        N/A        N/A       Already loaded in Unit Performance

* Battle Replay      N/A        N/A       Already loaded in Unit Performance

                  1          2.5 Hrs      Analyst

                  ?          ?            Programmer at present. In the future,
                                          will probably be loaded by the Loader
                                          with Guidance from the Analyst and

                                          Programmer

                  ?          ?            Programmer at present. In the future,
                                          will probably be loaded by the Loader
                                          with Guidance from the Analyst and

                                          Programmer

                          Objective Battle Data

SSS

Data Type         Number        Time per  Loading Task performed by:
                   of items         Item

* WAARS Reports   ?                       Programmer at present. In the future,
                                          will probably be loaded by loader
                                          with Guidance from the Analyst and
                                          Programmer

                                                                Trends Data

———————_S——eeEeEeEE——————————————_L_—_————————

Data Type         Number        Time per  Loading Task performed by:
                   of items         Item

Trends By BOS     1          4 Hrs        Analyst
                             4 Hrs
Trends By BOB     1          ?            Analyst

* Objective Data  ?                       Programmer at present. In the future,
                                          will probably be loaded by loader
                                          with Guidance from the Analyst and
                                          Programmer

                                      10


---

A. Summary of the Previous Five Tables
           ¢ It will cost an average of 139.5 Loader and Analyst man-hours or 17.5 days to load
           a WEX. This figure does not include the time cost for:
                        - Programmer time
                        - Loading WRS Journals
                        - Loading Battle Replay
                        - Loading Objective Battle Data
                        - Loading Objective Data Trends
                        - Loading Good Ideas
            ¢ Of the 139.5 man-hours:
                       - 41.5 are Analyst hours as follows:
                                    ~ 28.5 hours are for Analyst loading
                                    ~ It will require approximately 13 analyst hours to help the loader
                                     determine proper loading procedures.
                        - 98 hours are Loader hours
            * Approximately 30 % (42 hours or 5.25 days) of loading time is spent in scanning

            hard copy documents
            * AAR Video time requirements will change if the Videos are digitalized
            * Data Collection efforts and standardization will directly affect loading times
            * Data types that are currently under development will have a minimal impact on
            loading time requirements

B. Data Tables That Will Require Data to be Collected
            The two tables below are provided for future planning. It should not take over 5

minutes to load a Good idea document, assuming that it is provided as a finished product
ready for loading. The Player Unit Profile table will be defined during the follow-on work,
after the Data Collection Strategy is developed and implemented by the Army.

                                                                                     11


---

                                                      Good Ideas Data

—eEEeEeEeeeEoEOEEEEE

Data Type          Number     Time per                                 Loading Task performed by:
                    of items      Item

Good Ideas         ?          5 Min ea  Loader with Guidance from Analyst

                        Player Unit Profile Data

        Data Type  Number     Time per                                 Loading Task performed by:
TBD                 of items      Item

                   TBD        TBD       Loader with Guidance from Analyst

C. Efficiency and Reliability Suggestions:

            * Scanning Efficiency: Because the scanning of hard copy documents is costly,
            methods to improve cost effectiveness should be further explored. The following
           information provides an outline of our actions and findings with regard to the
            evaluation of the scanning process:

           - Test of the Defense Printing Services’ high speed scanner. Results were
           unsatisfactory because:

                         1. The current BCTP Database software cannot read the graphic files produced
                        by the scanner.

                        2. The scanner can only produce black and white graphics.

                        3. The current cost of the scanner is very high. (An average FER would cost
                          4.6 man-hours of labor; cost of the scanner at the current rate of 46.5 cents per
                        page is $90.00). The high speed scanner cost must be reduced to be
                        competitive.

            - A second test is pending to evaluate the scanners ability to scan and produce text
           files in a usable format for the BCTP Database.

           - The data collectors are attempting to collect as much data as possible in both digital
           and hard copy formats.

          * Loading Reliability: The BCTP prototype is a complex database with many loading
          variables. The use of a loading interface would reduce the number of loading errors

                                                                                   12


---

and increase the reliability of the database loading process by guiding the loader

through a series of prescribed loading procedures.

                                                                         13


---

                                                          VII. REFERENCES
Briscoe, J.A. and Burkett, J. Battle Command Training Program (BCTP) Database Concept.

         Monterey, CA: U.S. Army Research Institute, 1993.
Briscoe, J.A. Keesling, J.W. Battle Command Training Program (BCTP) Requirements
 Analysis. Monterey, CA: U.S. Army Research Institute, 1993.
Burkett, J. and Briscoe, J.A. Battle Command Training Program (BCTP) Front End
 Analysis. Monterey, CA: U.S. Army Research Institute, 1993.
Keesling, J.W. and Briscoe, J.A. Battle Command Training Program (BCTP) Database
Specification. Monterey, CA: U.S. Army Research Institute, 1993.

                                                                                     14


---

                                                                                                                       CONTRACT #: MDA 903-92-D-0075
                                                                                                                                  DELIVERABLE #: 0018-0018AJ
                                                                                                                                                     October 29, 1994

         BCTP DB USER'S GUIDE

                                             Brad Gill
                                           BDM Federal, Tnc.
      Submitted by: Mr. Michael R. McCluskey, Acting Chief
                    Unit-Collective Training Research Unit
                                 and Jack Hiller, Director
                            Training Research Laboratory
Mr. Michael R. McCluskey, Contracting Officer's Representative

                                   November 10, 1994
                              U.S. Army Research Institute


---

BCTP DB USER'S GUIDE

                                            Page

SECTION 1 - INTRODUCTION .. 0.0.0.0... ccc  eet eee eee eens 1

I. How to Use This Guide... 0. ee . e te. e eee 1

Vl. Components 2.0... 0... cee      ee ee ee tee eee eee eee eee 2

TI. Conventions 2... 0...           te eee eee eee ee eee 4

SECTION2 - GUIDED TOUR 1.0... 0.00 c cece eee e eee ees e eee e eee ennes g

I. Starting Up 2...                 cee eee eee eee eee teenies 8

' II, The BCTP db Startup Screet ...............0-. ee 8

III. The BCTP.db Research Dialog .. 2... 0... 2 ccc eee eee eee 9

IV. Data Retrieval Dialogues ..... 0... 0. cece ee tenes 11

SECTION 3 - RESEARCH TOOLS AND TECHNIQUES ILLUSTRATED .......... 16

I. Basic Database Concept...  2...          ee eee teen nes 16

II. Conducting Research 22... . ecc c et eee eneee 16

IW. Using the Analyst's Notebook 2.0... 2... cece eee eee eee 27

IV. Viewing Graphics...       2...  ee ce cece t ee nes 28

V. Viewing Video .. 6...      ccc ccc eee ee eee tee eee tees 29

VI. Saving and Printing Your Work ................. he et aee n eens 31

APPENDIX A - REFERENCES 20.0000... ccc ccc ccc ceeeeeeeeeeeeveeees Al

  APPENDIXB - TROUBLE SHOOTING ........ 00.0... cece cee eee eee eee B-1

 APPENDIX C - BCTP DB DATA TYPES AND MEDIA ........... 002000 eee C-1

- APPENDIXD - BCTP DB SEARCH LOGIC ... 0.... 0c c. e ee. e ee . eee. nes D-1

GLOSSARY 2.0... ccc           cee teen eee  e eee etennes GLOS-1


---

   INTRODUCTION

               The purpose of the BCTP db User’s Guide is to provide a user a BCTP db system

  reference. The guide provides basic information in regard to the database and the data.
- Methods are suggested which the user may use to analyze the data resident within the |

   database.

           Disclaimer: The data contained within the BCTP db system are the results of training

                                    ese

simulations. This data must be used in context only and should not be used to evaluate actual

system performance or unit capabilities and readiness. Additionally, use of unit names within

any research product or output is prohibited.

I. How to Use This Guide
            This User’s Guide consists of the following sections:

>  Introduction. This section provides you with a brief overview of the BCTP
   db system.

°  Guided Tour. Go through Section 2 for a short description of BCTP db

   system capabilities and functions.

4  Research Tools and Techniques Illustrated. Section 3 illustrates research

   methods and data analysis methods; searching the database, viewing data

   records, using the analytic tools, viewing the battle replays, using the Analyst’s

   Notepad; saving to disk; and printing data. Refer to this section when preparing

   for an important issue investigation or analysis, or simply for improving your

   use of the BCTP db.


---

+  Appendices. The appendices contain everything else you might need to know,

   including how to get technical support.

.  Glossary. Acronyms are defined here.

  II. Components

              The components of the BCTP db System are:

                               Application Software
                               Hardware
                               Data Files
                               BCTP db User’s Guide
                               Password
                           ¢ Telecommunications Hardware and Software
                           ¢ Video Replay Hardware and Software

               The BCTP db was created using Microsoft® FoxPro®. FoxPro® is a popular
' commercial relational database. It is known for its access speed and the level of flexibility

   when creating custom databases. The BCTP db FoxPro® application works in conjunction

  with several other commercial and custom programs. The BCTP db FoxPro® application calls

   the other applications for execution of unique functions, such as video tape control, graphics
   display, and spreadsheets. The BCTP db is used in combination with several commercial off-

 the-shelf (COTS) applications. They are Quattro Pro®, PaintShop Pro®, and the WindowsTM

   Notepad. These applications must be loaded to have complete functionality.

          The BCTP db database is run on any IBM® compatible 386 or 486 computer with

 adequate RAM and ROM storage. Microsoft® DOS/WindowsTM is required. Recommended

~ minimum configuration is a 486 33MHZ with 8 Megabytes of RAM. Hard drives in the 500

   Megabyte range adequately support the BCTP db software and three to four WFX sets of

  data. Storage for additional WFX data sets is highly recommended for remote users that do

' ‘not have access to the CALL BCTP db server.

The classified portion of the database will be distributed via CD ROM.


---

           The BCTP db uses the call server as a file server. Future plans exist that will use a
client/server approach. A client/server approach will provide increased system performance.

The BCTP db data files fall into two categories. The first category are those files ,

which work with the FoxPro® application to define: the relationships between the data;

   window layouts; and dialog boxes. These files are updated when required to provide

  additional functionality to the database or to correct software problems. The second category
. Of files are those associated with the BCTP data. These files are loaded into the CALL BCTP

db server by the BCTP db Operations Staff. These files are organized by WFX rotation and

ore.                                                                                                         ,

are entered iteratively; after the data js received, archived, and processed for loading.                “a

               Two user’s guides are provided to each BCTP db site at installation setup.
   Additionally, one user’s guide is provided to each individual that receives BCTP db training.
   Updates to the BCTP db User’s Guide will be provided in conjunction with software version
   upgrades.

                Forward recommended changes and requests for replacement copies to the BCTP db
   Database Administrator at ARI-FLVN or ARI-POM.

                Access password’s are used to maintain operational security in regard to unit training'
    readiness and to avoid potential misuse of BCTP data. Personnel who are not aware of the

  context in which the data is produced are not capable of using BCTP data without forming

    faulty conclusions. Therefore, it is imperative that all potential users receive BCTP db training
   from ARI or CALL. Password’s will only be provided to individuals who have received
_ training. Password’s will not be provided to organizations for general use. The BCTP db
    Database Administrator at CALL maintains the password roster and associated logs of
   database use.

                Ifyou lose your password, contact the BCTP db Database Administrator at the Center
_ for Army Lessons Learned - (913) 684-3035.

                The BCTP db system accommodates remote access. The BCTP db network server at


---

   CALL is accessible through the Army Knowledge Network. Authorized remote users have the
   runtime version of the BCTP db application and access to the data files through the Army
   Knowledge Network. Users accessing the BCTP db may experience slow system performance

  at times.

               Currently, video is available (AAR tapes) through serial connection with a computer
   controlled VCR and monitor. The prototype system will only support the use of video by

_ those users accessing the system from ARI-FLVN. Future enhancements include the storage

  capacity (CD CAROUSEL) and video capture software/hardware to digitize all available

   video data. Network distribution of video files is currently under assessment.

  Ill. Conventions

            - Before you start using the BCTP db system, it’s important to understand the unique
   terms and typographical conventions used in the documentation. All standard WindowsTM
   conventions are complied with. Users should have a working knowledge of WindowsTM to
 | operate the BCTP db system.

  General Conventions

               For explanations of specialized terms used in the documentation, see Section 2,
   “Guided Tour.” The following kinds of formatting in the text identify special information.


---

Formatting             Type of Information
Convention

Triangular bullet (>)  Step-by-step procedures. You can
                       complete procedural instructions by using
                       either the mouse or the keyboard. To
                       choose a command from a menu you can
                       use the mouse or press shortcut keys.

Bold type              Words or characters you type. For
                       example, if the guide instructs you to
                       type cd bedb you type the lowercase
                       letters “cd” followed by a space and the
                       lowercase letters “bedb” What you
                       type is always shown in lowercase
                       letters, unless it must be typed in
                       uppercase letters to work properly.

Italic type            Specialized terms.
                       Titles of other BCTP db documents.
Monospaced font        Placeholders for items you must supply,
                       such as filenames. For example, when
                       the guide says to type cd bcdb_name you
                       type the letters “ed” followed by a space
                       and then the name of a directory. OR
                       Used for either notes and tips to the user
                       or for interim/draft user guide text and

                       user notes.

                                                                                                                                                                    i

                       Examples of field syntax and macro
                       listings — for example, Sub MAIN.


---

Keyboard Conventions

            All key names are shown in small capital letters. For example, the Control key is
shown as CTRL, and the Escape key is shown as ESC.

                                 I

     Keys                  Comments

Shortcut keys  Keys are frequently used in
               combinations or sequences as shortcut
      ,        keys. For example, sHIrt+F1 means

               to hold down the SHIFT key while

               pressing Fl, and ALT, F, A means to
               press and release each of these keys in
               order.

RETURN key and ENTER| These keys usually perform the same

key            action. “Press ENTER” means that you

               can press either ENTER or RETURN

               unless specifically instructed

               otherwise.

Mouse Conventions

            You can use either a single-button or a multiple-button mouse with the BCTP db
system. Version 4.0 does not use the right mouse button for any internal BCTP db functions.
PaintShop Pro® uses the right mouse button to zoom in and out. Descriptions of mouse use

are characterized by the terms: point, click, and drag.


---

Point means to position the mouse pointer until the tip of the pointer rests on
whatever you want to select on the screen.

Click means to press and then immediately release the mouse button without
moving the mouse.

Drag means to point and then hold down the mouse button as you move the

mouse.


---

   GUIDED TOUR

I. Starting Up
           ‘Currently, to start the BCTP db program double click upon the BCTP db custom icon

within your WindowsTM main screen.

            Contact the BCTP db system Administrator for detailed installation procedures.
            > If for some reason this icon is not present you can restore the icon by clicking
and dragging the bedb.app or bedb.exe file out of the file manager window and release it on
the desktop where you want the icon to appear.

II. The BCTP db Startup Screen

              The BCTP db startup screen is the                   CI db P

 first of several dialog boxes that may be used                                                                                                             Mreteac OC EA

' to access BCTP data. From this dialog box      WELCOME TO BCTdPb

  the user may choose to review BCTP Trends,      ee       |e              Q

   Good Ideas identified during WFXs, or may     Trends  _ Good Ideas  Research

. choose to conduct original research and                   Warning!
  analysis on raw BCTP data.
                                                 The data contained within the ACTR db system are the results of training exercises supported

                                                 by training simulations. This data must be used in context onty and should not be used to

                                                 evaluate actual system or unit capabilities and seadinesy, Additiunally, ase of want nanies,
                                                 within ony research product or output is prohibited.

1

  BCTP Trends

               After selection of Trends from the BCTP db startup screen, the user should see a new
_ dialog that allows the analyst to select the types of BCTP exercises (unit type and echelon,

  location, component, and year) that trend information is needed for. The user must also select

 one of three types of trends. The first trend type are those trends resulting from the

  compilation of AAR BOS comments. The second trend type are those trends resulting from


---

the compilation of positive, neutral and negative comments concerning specific Blueprint of
the Battlefield sub-BOS areas. The third trend type are, those trends identified from the
compilation of computer derived data from a WFXs and commonly used by military analysts

to evaluate major BOS areas. Each trend type uses an additional dialog(s) to identify the

specific area(s) of trend analysis that the user desires e.g. BOS.

Good Ideas

       Selection of the Good Ideas screen will allow the user access to the BCTP O/C

identified areas of high value performance by units training during WFX. After selection of

Good Ideas from the BCTP db startup screen, the user should see a new dialog that allows

theanalystto select the applicable BOS and echelon of good ideas that they are looking for. :
The next screen is the standard BCTP db Data Display. This display allows the user to view a
list of all the good ideas, navigate to any of

them, and view selected Good Ideas in

whatever media form it is, text, graphics, or     Timeframe   |         Current Selections

both.       |                                     From [738s] To [2003  3 of 3

|                                                 Echelon               S3DHHAOT [+

 Ill. The BCTP db Research Dialog                                       93DHHRO1

                                                  UC Coms [Division [] Brigade | /S3DLHAOI

            After selection of Research from the  Rotation

BCTP db startup screen, the user should see a      Unit Type

                                                  ean 3)

new dialog that allows the analyst to select an   Component f[ n 8]
investigatory set of BCTP rotations for their     Restart
research project. This set is intended to be the

data set for their investigation. The analyst

   may select from several variables to narrow their research focus. Rotations can be selected

- for: timeframe, echelon, unit type, simulation location, BCTP team, component, and if thelr

   was a restart. The analyst may then review the list of applicable rotations, change selection
   parameters, or continue on to the main research dialog.


---

                   The user should consider, at this time,  Investigation Set  "Query Set
( checking out the supporting videos

      for his or her "Rotation Set"

The next screen, the BCTP db research

dialog box, is the principle research user                  [Rotational Information |{ uni Performance || objeBcatttleiDvetae|

interface. The analyst uses this dialog box to              [__Uent-Genereted _ |[_PUlnait yPreofre |[_ Battie Description |

select the specific rotations from the data set

that he or she wants to begin drawing

information from. The analyst may pick one or multiple WFXs. The buttons along the bottom

of the dialog box correspond to the major categories of data collected from each WFX.

Selection of one or more WFX rotations and one of the six data category buttons activates the

appropriate data retrieval dialog box. The analyst may select from six dialogues (Rotational

Data, Unit Performance Data, Objective Battle Data, Unit Generated Data, Battle Description,

and Unit Profile). During the course of the investigation the user returns to this dialog

whenever a new data retrieval is required that is of a

different data category.

                                                                               Rotational Informatian

Rotational Data

         The Rotational Data Display provides the analyst

basic information about the selected WFX rotation. Some of

the available data includes the training unit name, the start

and end dates of the WFX, the theater of the simulated

conflict, the component of the unit (active or reserve), the

" type of rotation (heavy, light, heavy/light or light/heavy),

and the BCTP team which administered the WFX.

Additional information concerning the context and nature of

the WFX can be accessed by clicking upon the MorRE button. The standard BCTP db Data
Display is then offered to the analyst for-theiruwsieth, all the additional rotational data that

was available for the selected rotations.


---

   IV. Data Retrieval Dialogues

   Uni;t Generated Products                                                                                                                                  —BOS              —      = 7

           The Unit Generated Products dialog box permits                                                                                                    DJ AN BOS:                      Ras

                                                                                                                                                             eee                          C Piee! Orde

                                                                                                                                                                wo                         - ) FRAGOs

                            .             .     o 8         .                                                                                                DD Ax Defense                =. .
   _ the analyst to retrieve various training unit generated                                                                                                 a           Cone

                                                   .                                                                                                                    Intelligence

   products (i.e. Opords, Fragos, IntSums, etc.) through use                                                                                                 Cl Mobi? Survivebaay| | omer

      :                  :                                                                                                                                     Cicss                  ide—
   of logical functions. The analyst may select a broad or
                                                                                                                                                             “Word Search

,               .                            ‘                                                                                                               @® Exckisive (AND}
   narrow retrieval search for unit generated products. He
                                                                                                                                                             © Inchusive {07}         Lore

_ may conduct the search using several methods. He may                                                                                                                                  chelon

                                                         .                                                                                                                            Ban =6Clav

   choose from the applicable BOS, a type of product,                                                                                                                     a |               Coo

                                                                                                                                                             7 |: « [ec

   |echheelloonn, or a wordd searcshearch.. HHe may reffiniene hihis retrievaby,,                                                                            Sse”

   using collectively two or three of the methods mentioned

   above.  The     data     ¢        Sea  displayed  using  the  standard  BCTP    db                                                                        Data   Display.

                               then

               Orders can be seen and selected by each section and sub-section using a
   hierarchical pull down list. See Appendix D, for a detailed description of BCTP data types
   contained in the BCTP db system.

                                                                                                                                                             Du Pertumn ance be itt a
                                                                                                                                                                ~BOS.                       d

   Performance Data                                                                                                                                             Basbose               toe cis Regt —

                      .                                 .           .                                                                                           O Firs Suppet         DD Overview .

           The Unit Performance Data dialog box permits the                                                                                                     ae                    Oe

   analyst to retrieve various documents addressing training unit                                                                                               DD intetigence          () AAR2 Renae

                                                                                                                                                                henieeed              (

                   .                                    .        .                                                                                              Word) Phrase Search,  |__U1 Onde Crocowat

   performance (i.e., AAR comments, Final Exercise Report, etc.)                                                                                                  © Kachoive ND)      CIAAA Video
                                                                                                                                                                  © Inchusive (OR)    Dacceesy

   through use of logical functions. The analyst may select a                                                                                                   ———                   Fenelon —

                                                                                                                                                          |     SS                    Gee Gene

   broad or narrow retrieval search for unit performance data. He                                                                                               Se                    |

                                                                           .                                                                                                   Cx

   may conduct the search using several methods. He may choose

   from the applicable BOS, a type of performance data, or a word search. He may refine his

   retrieval by using collectively two or three of the methods mentioned above. The data is then

   displayed using the standard BCTP db Data Display.

   Objective Battle Data
              The Objective Battle Data dialog box permits the analyst to retrieve a broad range of

                                                                                   11


---

computer generated data produced from the conduct                                                                                        BCTP Objective Data

of the simulation (WAARS/AARS reports). The                                                                                  ee                State ear

                                                                                                                          .   SSOHHROt         (sis} Month (3
                                                                                                                              SGOLHAN
analyst may select a broad or narrow retrieval search                                                                                               Dy [a

                                                 \                                                                           Raport Types            Time

for objective data desired. He may conduct the search                                                                        BIOM Reports              @: °
                                                                                                                                                           Blue Red
        °                                                                                                                    COptor ADA
                                                                                                                                                       -
- using several methods. He may choose from the                                                                                  _——
                                                                                                                                                { (x! ] [cee |
applicable BOS related reports, side (red or blue),:.
                                                                                                                                               =

and time period. The report topics are diverse and                                                                           Combat Casualties | Columns

   cover most critical combat functions.                                                                                     Caused By-        © Equipment

‘                                                                                                                                              | BQ Number Hit

 Battle Description                                                                                                                                             | BQ] Number Wounded

               The Battle Description dialog box permits                                                                     [Bevien] naize} [eee ] 12 Number Killed
   the analyst to retrieve multimedia data describing
                                                                                                                             “ peg rg pre es   UN De TUN        o peg F Oh gh
_ the WFX battle. Examples of the data available
  through this data retrieval module are: battle                                                                               Ratatinns       Za

   descriptions from the FER and AAR with                                                                                                          Ferns sonnel Feuglins Newaviiw
   accompanying graphics or video, and descriptions
   of key events logged by the workstation                                                                                                     velMare
   controllers.
                                                                                                                                               (eis Jeunad Teplay Dano

                                                                                                                                         ux |

 Unit Profile
            TBD Not Implemented

          The Unit Profile dialog box permits the analyst to retrieve data describing the training

and operational profile of the WFX training unit. Examples of the data available through this
data retrieval module are: training status, unit operational tempo, recent
training events/history, WFX staff manning, etc. Retrieval methods TBD.

Word Search
         _ The majority of the data retrieval dialogues incorporate the

capability to search the text fields for the inclusion of analyst determined key words. The

word searches may be done without or in conjunction with other data retrieval logic. When

                                          12


---

  done in conjunction with other data retrieval logic the word search can retrieve those records
 that meet all search requirements or any search requirements. A detailed description of these
. processes is found in Appendix D, BCTP db Search Logic.

Text

            Text is the predominant media type  Elle   Edit  Database  Record   Program Aun Tet           Window  Help
within the database files. Text is displayed                                                Data Display
within a Data Display window. The Data
Display window has a section that includes      [pazemaoa 1 yen               4 Besths              1 Inceli/Direction
a pull down list box of all records that met
your search query as'well as a header that      Time Sent        Time Recerved        Organization

provides information relating to the text                                                                         Record 4 of

record currently selected i.e. source,          Battlefield Operating System                                                        Move Te Record ..
organization, WFX rotation, Date Time            TAA TAS
                                                                                      Steleieac
                                                poe sench              ScsolV/E dit

                                                30X ta 2

                                                       (2) Stared in the commander's    is the                    for the      tom      ef
                                                                                                                                    the
                                                40% ef the enemy axtillery prior te crossing LDYLC. Maile stated in the date,       If

                                                requitenent to collect and provide BDA was not Included iu the commander's PIA.

                                                collection assate axe tasked to collect BDA, this requiresent must be staced.

                                                              63) Gemeral Observation: '3¥ assets were task organized te weight the sain
                                                 affert. Initially IBDE war identified as the division's malin affert and changed with
                                                 FIACO 22 to § MAR UCT fer the conduct of the defense. While sucticians ‘EE assets
                                                 vere always eveilable te the sain effert, the priority ef ‘EU effert 414 not change
                                                 with

                                                 the publication of the defense REACO (i.e. it remained with JBDE, which became the
                                                 Corps resarve). Upon publication of FRAGO 29 (effective 221723), the prierity of ‘Kw
                                                 support was correctly changed to SEAR(ARIN) in accardance with the scheme of
                                                manewar. Nowever, no relationship or priority fer WW support was identified fox the

                                                +
                                                                                                                                                                                                                                                                                     0

Group (DTG), etc. There are controls to navigate between records and to launch associated
still graphics and videos.

Still Graphics                                      File  Edit  Ylew   image  Colors    Capture Windew Help

             Still graphics of many types are       bad                                 —                 —_
available within the database. These types
range from screen shots of WFX workstations                                             FRi01830.T1F {t:                                wfe
showing unit dispositions, AAR BOS slides,
BOS analyst generated charts and graphs, to         <                                                                                 Toots

unit generated charts, matrices and decision                                                                                        oe=

making aids. Analyst’s may view, CoPy, and                                                                                          ch
                                                                                                                                    za
modify/annotate copies of the graphics for
                                                                                                                                         a
later analysis, reference or documentation.
                                                                                                                                                   +
                                                                                                                                            3

                                                13


---

  Video Replay
              The principle video data contained within the database are videos of the WFX AARs.

  User’s may play those specific video segments that meet their data retrieval requirements or

| they may view all or any portion of the video that they desire. Video control conventions are

  identical to those used by common VCRs.

Spreadsheets and Graphs                                                       Gnottre Pre fer Windows - CB.DBF
          _ The Objective Data dialog has the
                                                                 E aB weO ao oe
capability to transfer data directly to a
                                                                                                        Ps
spreadsheet. Selection of the ANALYZE
                                                                                       | KAUN
button, calls Quattro Pro® and
                                                                                                                             ~
automatically fills in a new spreadsheet
                                                                 N D
with the report data. Once the data ha¥
                                                                 mh a weNaey  ENOO-WARoOH~eMBwonowd                             [ROKT wOWOUND=MokAL |}
been filled in the analyst has the
capability to conduct any spreadsheet                                           ~Nane-nonenteo-o0§

                                               MEETHINAABACASAEAEAGARATASAKAL                                                   Bile                  *

                                               Dest cbc sich wo                                                                 ae    ee)

function or manipulation of the data.

Quattro Pro® has an expert system that walks the user through the conduct of several types

of statistical analysis and the development of illustrative graphs. Once the dataOe mtnanipulated

in a manner sufficient for documentation the user may select, copy and paste the relevant

information into the Analyst’s Notebook or the wordprocessor of his or her choice.

Queries and Reports

            Ad Hoc queries and reports can be developed with FoxPro®. Those users with only |
the runtime version of BCTP db must request the development of ad hoc queries or custom

reports from the BCTP db Administrator at the CALL.

            Advanced users may use FoxPro® and the DBF files within the CALL server to
develop specialized queries and reports to support unique analytic requirements of their

organization. Both SQL and QBE are supported by FoxPro®. If FoxPro® is used to construct

user ad hoc queries or reports the user should reference the FoxPro® User’s Guide for

                                               14


---

explanation of methods. Advanced users are reminded to use a duplicate copy of the software

when making software changes. Development support can be coordinated with the BCTP db
System Administrator. All software enhancements or new queries and reports should be
reported and provided to the BCTP db System Administrator in order that version control can
be maintained and that all users can benefit from the additional system functionality.

                                                                                15


---

        RESEARCH TOOLS AND
      TECHNIQUES ILLUSTRATED

I. Basic Database Concept

         The BCTP db system has two principle parts: the data files and the Data Base

Management System (DBMS). Each data file is composed of hundreds of records concerning a
single WFX. The DBMS has tools to display records. The DBMS uses dialog boxes to solicit

the types of information that the user wants. The user interfaces with the DBMS to display the

information, the records, that are of interest to their particular investigation. Wise use of the
various dialogues will benefit the user by improving the degree of correlation between the kinds
of data that the user wants versus the kinds of data available and, if available, data displayed.

             The database is organized to support users that are interested in many facets of training
 developments and military research and analysis. The data is grouped into three main functional

| elements: Trends, Good Ideas, and the Research Database.

II. Conducting Research

           After starting the BCTP db application the first window to come up is the BCTP db
Startup Screen. If you intend to conduct original

_ research, the first step is to select RESEARCH and = =

then, to select your investigatory set of WFXs in                                                                                                                          Date: Ori6a4

                                                          WELCOME TO BCTP db

the following dialog. Your selection of rotations      .                                                er
                                                          {Ee . fey. fe]
is supported by two primary sources of                 vo, Trends ./Goodideas Research

.  .                     .                                Warning!
information about each WFX; the rotation code
                                                       The data contained within the BCTP db system are the results of training exercises supported
                                                       by traning simulations. This data must be used in context only and should nat de used to
                                                       evaluate actus! systern of unit capatilities an
                                                                                                        86. Adiitionally. use of wat hanes.

and the Rotational Information data display.           een OF Obs BIS

                                                   16


---

   > EXAMPLE: From the BCTP db startup screen select RESEARCH.

               The first is the Rotation Code itself. The  Investigation Set     Ceres)         Query Set
| Rotation Code is an alphanumeric that contains
                                                             HRA Te]                           , BEAD Ts
  information reflecting the: year, echelon, type,
                                                                                 Epmen}
   component and sequence number of that specific
   type of rotation conducted within that year; for                           a                !

~ example:                                                                 :     nat           Objective Bettie Dete

                                                           UnitGenerated — |[__UPnkleProetre |[__ Settle Description

                                                                              :

   YEAR] ECHELON TYPE COMPONENT (SEQUENCE#

   ~93 7. D        HH          R  01

   93DHHRO1 is the rotation code. For the first

rotation of a reserve component heavy division in          Timeframe             )             Currant Selections

1993. Therefore, you can see that if you do or do          From [1geak5] To [2010F]            3 of 3

                ;           ;         of.                                                      93DHHAD)               [=]

not want a rotation reflecting one of these criteria it    Echelon                             §3DHHRO1
                                                             (CC) Com: [ Division [7] Brigade
.     .      :     .                                                                           S3DLHAD1
is possible to identify and then to select/deselect the

                      .                                    Rotation

criteria from your consideration. When the user is           Unit Type

satisfied with the investigatory set, OK is selected.      tecation

Additional rotational information about each WFX           Tou

                                                           Component

   :               .     .        ar                       Restart      |
rotation can be reviewed in the following dialog by
                                                           :

selecting a rotation code and then clicking upon the

ROTATIONAL INFORMATION button.

   > EXAMPLE: From the rotation selection window change the time frame to reflect from |
   1992 to 1995. Change the rotation unit type to heavy. Two rotations are selected:
   93DHHAO1 and 93DHHRO1. Click on the ox button.

                                      17


---

   The data sets selected will be those sets that future data retrievals will be made from.

>  To select a rotation upon which to conduct research—click the Rotation Code within

   the left list box that you want to select. Once selected it will become highlighted.

   Click the MOVE button and the Rotation Code will appear within the right list box.

   A quick way to select or deselect a rotation is to simply - double click it.

   > EXAMPLE: Double click on the rotation code 930HHAO1.

> To deselect a rotation—click on the Rotation Code within the right list box that you

            want to deselect from your investigation list. Once the Rotation Code is selected it
            will become highlighted. Click the REMOVE button and the Rotation Code will
            disappear within the right list box.

Setting Search Options
            The next step is to determine and select the type of data in which you are interested.

The choices correspond with the buttons along the bottom of the window. They are:

-  ROTATIONAL INFORMATION

-  UNIT PERFORMANCE DATA

-  OBJECTIVE BATTLE DATA

-  UNIT GENERATED DATA

-  UNIT PROFILE (NOT IMPLEMENTED YET)

-  BATTLE DESCRIPTION

           A useful hint as you begin your research is to select the battle description for those
WFX you will research. The Battle Description data area was developed for express purpose
ofproviding the analyst a WFX overview based on the presentation of selected critical data
about the exercise.

                                                                                                                                                                                                                                                                                                                                                                                  1

            To select a type of data—click on the desired information type button. A new window

                                                                              18


---

will appear relating to that specific type of data or data retrieval.

> EXAMPLE: General information regarding the                           Rotational informatian
rotation can be found by selecting ROTATIONAL
INFORMATION. Click on the rotational information button:
Review the contents and click on the MORE button.

            Once the user has made a query, the Data Display
window will appear which will allow the user to choose
and review specific data records. Immediately after
creating the data retrieval query and clicking on the ok
button, the analyst will see a new window, the Data Display window. This window provides
access to all the records that met the retrieval query. These records could be of any media
type: text, graphics or video. Across the top of the new window are six column headings
which provide distinguishing information/characteristics of the data: Rotation Code, Type of
Data, Data Source, Data Name, Order, and Media Type. Media types include text, graphics,
or video. There are three command buttons above the text of the window that can be used:

CANCEL, NEXT, and PREVIOUS. There is a scroll bar placed vertically along the right edge of the
windo‘iwf all ‘the data selections will not fit on the window. Underneath the column headings

are the data records.

 > EXAMPLE: To viewa list of all the records that met your search criteria, double-click

 anywhere on the Record List bar. To access a data record, click on it (which automatically.
brings you to that record in the text portion of the Data Display window). The text may
 not be the primary data source—it may only be the text that cites a graphic or a
description or topic list of a video. If you would then like to see any associated graphics or
 video, click the GRAPHICS or VIDEO button.
 Click on the 'Road-to-War' record.

          By choosing a data record, the user will now see the record displayed in the bottom

                                                                               19


---

half of the window. Above the text is header information including times and unit names.
There is a scroll bar placed vertically along the right edge of the windowif all the textual
information will not fit on the window. The textual data within the memo field canbe ‘<
analyzed or copied into the Analyst’s Notebook.

> EXAMPLE: Highlight the desired portion of the text with the mouse. From the menu

selection EDIT, select the Copy command. Open the Analyst's Notebook (Notepad) by

double-clicking on the notebook icon. Point and click within the Notepad window, then |

from ‘the menu selection EDIT, choose PASTE to transfer the copied portion (see next section,

Using the Analyst's Notebook). Close the text editor window and do not save (unless

desired).  ,

              When the media type is graphics or video, the memo field will be a textual description
  of either the video or graphic. To double check that a graphic or video is available, look in
  the center of the window. There are two icons, VIDEO (a miniature picture of the Mona Lisa)
  and GRAPHICS (a film reel). These are only active (highlighted in full color) when that type of
  data is available. Therefore, if the window is showing a textual description of graphic data,

 the GRAPHICS icon will be active. By pressing these active buttons, the user will be accessing
 Paint Shop Pro or the BCTP db video playback software to see the respective graphic or

- video (see Section 2, Still Graphics & Video Replay).

     > EXAMPLE: To viewa graphic click on the long record list bar. Click on record "10"
     "5 day cartoon day 2." Notice that the graphic icon is now colored. Double-click on the
    graphic icon. View the graphic and close when through.

               After selecting the type of information, the next step is to define your database query.
   In other words, you have to ask the right question to find the data related to and supportive of
' your particular investigation. Those users accessing the CALL database over the network

  should carefully consider their query. A very broad query will take a significantly longer time

  to retrieve than a specific query.

                                                                                   20


---

         There are many ways to relate and to access data within the BCTP db. Common

access methods/relations are:

     Relate inter and intra WFX by BOS or BoB Ref.

     Relate data by echelon.

WN   Relate data by source or type.

     Relate data by text content (word search).                                       |

w k  Relate data within WFX by understanding TIMELINE (Battle) events and

     retrieving data from fields based on discussions by O/Cs or Unit Products

     Generated.

6.   Relate data among WFX by Trends.

              Most of the data dialog boxes operate in a similar manner, therefore they will be
  discussed generally and illustrated with specific examples. Both the Unit Generated and the
  Unit Performance dialogues allow the user to choose any or all of the seven different

 Battlefield Operating Systems: Intelligence, Command and Control, Maneuver, Combat

  Service Support, Air Defense, Fire Support, and Engineer. These two dialog boxes also give

 the user the option of choosing either ANY or ALL document types of that respective genre _

| (i.e., Opords, Fragos, Intsums, etc. for Unit Generated Products; AAR comments, Final

 Exercise Reports, etc. for Performance Data). The echelon that relates to the information can
 be included as a search parameter. In addition, both dialog boxes contain sections for a word
  search, which can make the overall database search more general or more specific.

            To conduct a specific search, check the appropriate BOS(s) Document type(s) and

  echelon of interest to your investigation, type the alpha-numeric entry(ies) desired in the word

 search section, then click AND. To make a more generalized search, click on the appropriate

 BOS(s) and/or Document type(s), type the alpha-numeric entry(ies) desired in the word search
  section, then click OR. For example, if the user wants to access data relating to Intelligence
  AAR comments, containing specific information on BDA.


---

> EXAMPLE: From the BCTP db startup screen click on RESEARCH. From the rotation

selection window click on the OK button. From the BCdb rotations window double-click on

both '930HHAOI' and '93DHHRO1' and click on the UNIT PERFORMANCE DATA dialog buttod.

From the Unit Performance dialog box within the BOS selections click on the INTELLIGENCE

check box, click on any AAR COMMENTS checkbox within the Document selections, finally

clicking within the word search data entry field, then typing BDA in the word search area,

and then clicking on the OK button (for further explanations and examples of refining the

search and its logic, please read Appendix /BCTP db Search Logic). Review the records

and then close the data display and unit performance windows.

-BOS——_—_—_—_,_        --Document/Produat— .
                       | Ras                    ~]
(1 An 80S
                       Final Exercise Report-———
 CO Maneuver               (0 Overview

 O Fire Support            C) BOS Observations

 0) Ai Defonse

1 Command/ Control         0 AAR1 Remarks
(CD tntetiigence           (Dl AAR2 Remarks

(1) Mobility? Suavivabiity | [O/C Input         ;
Cless                      (CD Notes

Word/ Phrase Search,       1] Orders Crosswalk

  @ Exctusive (AND)        (C] AAR Video

O Inchisive (OR)    }      Dacres (c2)

(INTENT                    —~

as) | Be oe
Cc}| | Geac Dane
es                         [] Comps [J 8N

           Objective data, produced by the simulation, is accessed slightly differently. The analyst
must select a rotation, time period, and an objective data category/report. The user then may
select/deselect specific report fields. The analyst then has the option of reviewing the data or
exporting the data for complete analysis to a spreadsheet.

                       22


---

> EXAMPLE. From the BCdb Rotations window select OBJECTIVE BATTLE Data. From tHe

BCTP Objective Data window select 93DHHRO1 Rotation Code, and the Combat Battle
Status Report Type. Click on the OK button. From the Combat Battle Stats window click on
the REVIEW button. Review the presented data and when through click anywhere in the

BCTP Objective Data window. The analyst may then click on the ANALYZE button or the

Combat Battle Stats window. Quattro Pro® then imports the entire data set resulting from
your query input. From Quattro Pro® the analyst may then conduct his analysis and
graphics production in accordance with the Quattro Pro® User's Guide. When complete,
close Quattro Pro®. Close the Combat Battle Stats and BCTP Objective Data windows.

   ot. . | BCTP Objective Dota

' Rotation Code    Start                       nd

                   (Un)           Yeor             E) CAUSE! UNIT    EQUIPMENT             NOH]       a                    OKI!
                   [aE            Mone (aE)                                                        1                                i
                                                   stiller’ | SECT SCTIM HQ/EVCAGPT.PERS          Z    NOVSOUNT!                  2
                   [3]            Dey                                                              i                   0            1
                                                   certact| 1.277¢P DISHNTD TROOPS               4                  a]            2
                   [0]            Time (0 _ 8                                                     1                    0          G
                                                                                                   1                2
                                                   sentatt] CORPST. [REAR AREA TROOF              1                               =
                                                                                                                  12               é
                                  © Bue © fled     contact] BFIST    REAR. AREA TROOP            21                   Q             é
                                                                                                  i                 0
                                                   contact| 072.137  APC.M13                       3                  a            q
                                                                                                                      g              i
                                                   tttacl] GOPE      REAR AREA TROOP               i                    r          1
                                                                                                   4                                [a]
                                                   ETT.     E        EARTH MOVERS                  2                    0           i
                                                                                                 EB                   1           4
i                A eataiaele Paw                   cir               HO/SVCISPT. FERS                                   3         E
                                                                                                   1                 2            0
                                                   cits              it PUGHT. TRUCK. dad                                            i
                                                                                                   1                   a
Combat Casualtios  | Columns                       ETTs              i) | TRUCSKT
                                                                                                 4                     0
 [i] All Causes    | Bas -                         Lontact           REAR AREA TROOP             Ei
                                                                                                 Z                 [i]
Caused By...       i 2) Unit Sustaining Casuaties  certact] YUSA-18  MBT 2460                                       0
                   ! B equi                                                                        z               2
                                                   contact] G1. 196  APCLTIS
                                                                                                                        |
ferts I            i (8) Number Hit                sontacr| Ef1-i34  0        2 TREMORS

                   | Bil Number Wounded            comlacn Bff-138   J

                   i 6) Number Kiext               contact) REF be   He            PERS

                                                   sentacl id        REAR AREA TROOP
                                                   suntatt| REF      PEAR AREA TROOF
                                                   contact] Gyt-134  APES

                                                   contact! B/1-134  DISMNTD. TROOPS

          Several types of information describing WFX battle activities are available within the

battle description area of the database. Data types include: textual descriptions of the battle
from the Final Exercise Report (FER); graphics from the FER, a video narrative of the battle

from the AAR video; a timeline graphic derived from the battle description in the FER;

specific "vignette" comments or significant activities recorded by the BCTP workstation
controllers (WRS Journal), and a Battle Replay of the WFX.

                                                                                                                       '

      A prototype of a battle replay capability is developed and will be integrated in the

near future.


---

Pe

     > EXAMPLE: From the BCTP Rotation window click on the BATTLE DESCRIPTION button
     From the Battle Description window select the 93DHHRO1 rotation, select which areas are
     to be viewed and click on the OK button. When you select WRS or REPLAY DEMO, you do
      not need to select OK, as they come up when selected. Review the battle descriptions from
     the Data Display window as previously described. When through,close the Data Display
    window. From the Battle Description window click on the WRS JOURNAL button. Review
      the WRS Journal "vignettes" from the WRS Journal Entries window. When through, close

/ the Data Display and the Battle Description windows.

Ratatione     Battle Description                              605) Functional Area

              ,                                                              Me) [axes] =)

auons |       an
Sone          - : BAS.            ;                                                                                      Earlier ©

                                                              serosa 00:43 Loc= .8 |s =x of 24

                  ~{[] Text and Graphic Overview |            Word} Phrase S
                   (1) Video Narative —
                                                              CCc                                                                                           5 a              é on
                  C1 Time Line

                        come                                  BOS/FA — SUSTAINMENT
                                                              Unit                                                                                          wsbAs8
                  1 [WAS Joumal!] [Replay Demo]

                                                              Location —-DISCOM                                                                                     :

           ‘      ons                                          THE MSB HAS FRAGO 470 THE OPORDER.

                                                              A. PETERS

i

                     Further combinations can be achieved by
         creatively utilizing the methods described above.

Viewing the "Good Ideas"
            The BCTP db has a simple procedure to view "good ideas" identified by BCTP

observer/ controllers, CALL observers,and other analysts.

> EXAMPLE: Close all windows until the only window                                                                                                          BOSs ©           Echelons

visible is the BCTP db Startup Screen. Click on the Goop                                                                                                     Pam BOss) -       EAIW Echetons

IDEAS button. Select FIRE SUPPORT and DIVISION. Click on the                                                                                                Ore Supe         “Cheme

OK button, the Data Display interface will be displayed.                                                                                                     C1ApA             C) Oivision

Review the good idea and close the window when through.                                                                                                         Oc                 C1 Brigade
                                       ;
                                                                                                                                                             C1 Intetigence    C1) Battation
Cancel the Goop IDEAS category selection and you are now
                                                                                                                                                              Oe a
                                                                                                                                                         {
                                                                                                                                                             Des
back at the Startup Screen.
                                                                                                                                                                   Cx]

                                                    24


---

Viewing BCTP Trends
           The BCTP db has several types of trend information derived from BCTP exercises.

The type of rotatio‘annds the types of trends may be selected. Trend types include:

.                 Performance trends by BOS (a quantification of BOS observations from the after

                  action reviews)

°              Performance trends IAW the blueprint of the battlefield (a quantification of the

               observations from the final exercise report)

°           ' Objective data trends by BOS (selected reports generated by the BCTP computer

                  simulation)

               |

> EXAMPLE: From the BCTP db startup screen click on trends. Select unit type "heavy"

 "Performance trends by BOS" and then click on the OK button. Select "Maneuver" and click
 on the OK button. Review the topics needing improvement and sustainment. Notice the
Rotation ID numbers shown whena topic is selected. They change to reflect the rotations
that the trend data is derived from. When finished, close the AAR trends window. Cancel
the AAR Trend Selection.

   fee es                      -- ++: Trend Selection

Timeframe                              Trond Type                                                       -* AAR Trend Selection .

   Fe             f=)          [*)                                                                          Bos
Echele WESSITS! Te C200 | pactermance Trends by Bos
   jeion ~                                                                                                               @® Maneuver
   C1cenpe (2) Divieion CJ     brigad  © Pestormence Traaie (AW Bhowprint of thn Batthafintd                             © Fire Support
                                                                                                                              © ADA
       ion                             O Objective Data Trends by BOS

   Uni Tove [al           ¢

   Location [a3           2

       ane ; ;

       Rlestert (Donte [2                      | a)                                   ;              ;  © Intelligence

                                                                                                        © Engineer

                                                                                                        © css

a                                              ET

               weenie 4                   BOS: Maneuver                :                                (Ox)   (gence J

            Areas Needing Improvement                  Arent Needing Sustelnment              :

       Topice                          sum         Tepice                    . ion

          ovaring Force Opns           1           tk Helos im Close Operations i

       Deception                       z           Witk Melos im Close opns       ry

       |Penatration and Tempo          1           Atk Helos in Deep Opns         4

       JSecurity                       a           Pviacion Integration           a

       Security Zone Opns              a           [Counter-Raconmaissance        a

       Unit, Positioning               a           DTAC Displaceners              re

       Weight Hain 8ffect              a           Ireagretion of eint Forces     1

       Weighting the Rain E¢fort       2           SPF Tm Destruction             1

                                                   jSacurity                      i           i

                                            y      [Factical Revenant             a           :

                                                                                                 25


---

   > EXAMPLE: From the trend selection window select "Performance trends IAW

   Blueprint of the Battlefield." Click on the OK button. Select FIRE SupPpoRT from the FER

, Trend Selection window and click on the OK button. From the FER Trends for Fire Support

  window click on the "?" under TA2.2. Notice that the title of this category (Engage Ground

   Targets) appears in the upper right portion of your screen. Click on the TA2.2 button. From

  the FER Trend Display review the quantification of all positive and negative evaluations

 regarding TA2.2 and those blueprint of the battlefield categories subordinate to TA2.2. ,
 Notice that the rotation identification numbers are shown that produce the quantification.

  When through, close the FER Trend Display and the FER Trends for Fire Support
  windows. Cancel the FER Trend Selection.

                         - FER Trends for Maneuver

         “E ==              AT.2...
                       =
                                                                      aryels A.                                                                                         ~
                                                        io
                         7
                    i=
                                                                                                                                                                 =
                                                     =
                                                                     55
                                                                                                                                                                   rey
                            22.) (ia2a) flats.) (faa,

TALLI2,     TAI.1.1.4.,

         ;  I                                                                                                                                                                  =|                   FER Trend Display

                                                                     1                                                                                                         Blueprint of the Battlefield Referenca: TAI

Ee pe pepe) pees

                                                                                                                                                                                     Descripition: Maneuver BOS

                                                                                                                                                                               Sums       Positive  Analysts Evaluations    Negative
                                                                                                                                                                                               40                                 16
                                                                                                                                                                                                            - Neutral
                                                                                                                                                                                                                      2 .

                                                                                                                                                                               Rotations

                                                                                                                                                                           26


---

> EXAMPLE: From the Trend Selection window select "Objective Data Trends by BOS"
and click on the OK button. From the objective data trends window select "Fire Support"
and "Artillery Missions, Rounds" and then click on the OK button. The Quattro Pro®
window displays the raw data and a graph of this data. If desired, the analyst may save this
spreadsheet with graph to a personal file. From the analyst's file he or she may use Quattro
Pro® to do additional statistical analysis of the data and develop supporting graphs for

technical reports and research. When through,

close Quattro Pro®. Cancel the objective data trends and trend selection windows.

         om                         -_duatira              Pre for Windows - CB.UBF       ea                                         vis!

            ~  je Edit  jock                   Date        Yeols Graph  i      Indow Hel                                                  t

                        Li |B MICH bs CR Nomat                             Sk        ea Shas

         i

                                                     ;         i                     a    a)                                         Nie

                                               JOWO! NOW                                                                             a

                                                        on)

                                                     Oo.) 68

                                                        20°05

                                                     0 98

                                                     3.00

                                                     9 11

                                                        1  1

                                                        1  8

                                                     o 2

                                                     o     60

                                                     o     3

                                                     o 1

                                                        1  98

                                                     0     4

                                                     Qo 14                                                                        .
                                                     6     2
                                                                        [~ nour "<NowouND-— WOKEL |

         neal Aconcnig                                                                                                               ry
         Go AAEAETEAETELTORTRERERT                                                                                                   a
         Double chick preph te adi

II]. Using the Analyst’s Notebook

         ' The Analyst's Notebook is a very useful tool that allows the analyst to extract and

work with parts of the database, without altering the database itself in any way. The
WindowsTM Notepad is used as the BCTP db Analyst’s Notebook. This text editor is used to
store selected sections, take notes, store them on floppy disk or hard-drive, and print portions

for further analysis and reference. Currently, only textual data from the memo field of the

Data Display can be selected and copied in to the Analyst's Notebook. Any alpha-numeric
data within the Analyst’s Notebook may be chosen for editing.

>  In order to copy data from the database into the text editor, select or highlight the

   i} |

                                                                  27


---

desired portion of the report with the mouse. From the menu selection EDIT, select the COPY
command. Open the Analyst's Notebook (Notepad). Point and click within the text editor
window, then from the menu selection EDIT, choose PASTE to transfer the copied portion.

This transferred data is now ready to be edited, saved, or printed. By using the Analyst's

Notebook, the analyst can store or transfer data desired for later use/reference, while not
altering the database in any manner.

~ IV. Viewing Graphics

               This section goes into specific detail concerning the use of graphics in the BCTP db
   system using Paint Shop Pro®. Before any other discussion, it is very important to warn the |
   user that when using Paint Shop Pro®, data can be altered or destroyed permanently. *

  Therefore, it is imperative that the user be cautious when analyzing graphics and only after

   carefully reading the following section. Once within the graphics program, the analyst has

  great power, controlling a full range of color, image, resolution, magnification, and

   manipulation tools.

            There are two tools that are especially helpful when working within the graphics
window: the Selection Rectangle and the Magnifying Glass. The Selection Rectangle is
located in the upper left corner of the window, in the tool bar located along the left edge of
the window. It is represented by a rectangle consisting of dashed lines.

>  Place the cursor on the dashed rectangle and click. Bring the cursor back into the

graphics field, which will cause it to appear as a cross-hair. Click on a point within the field

and drag to create a dashed rectangle.

            The Selection Rectangle allows the user to do a variety of tasks with all the graphics,

or parts of graphics, that are inside its boundaries. At this point, the user can print either the

entire window or just the part contained in the selection rectangle. If the user wants to work

with %or manipulate the selected graphic, the user should save the graphics file under another

                                                                                                                                                    es y ¥ ‘

namx,~and conduct any changes on the new file. This ensures that data is’ not altered or

     A

                                                 1

                                                                                28


---

destroyed. Graphics cannot be copied (copied & pasted) into the Analyst's Notebook, but they
can be copied into other application files that will accept graphics, such as Microsoft Word®,
WordPerfect® or a graphics application.

            The second tool that is commonly used is the Magnifying Glass. It can be used to
double or halve the current magnification level. To zoom in or out:

">  Place the cursor on the small magnifying glass located in the tool bar along the right-

edge of the window and click. Move the cursor, which is now a magnifying glass, back into

the field at the center of the graphic or area that is to be magnified, and click the left mouse

button again. This will double the magnification with each click. In order to bring the graphic

back to its original size, move the magnifying glass back to the center of the graphic or area

~ and click the right mouse button. This will halve the magnification with each click.

    Review the Paint Shop Pro® documentation for additional information.

V. Viewing Video

            This section reflects the interim solution available only at ARI-FLVN.

           This section provides greater detail on the use of video in BCTP db. The two
additional pieces of equipment required for this specific use are a computer-controlled VCR
and a television monitor. Turn on the VCR and monitor power before inserting any tape. It is

generally a good rule to turn on the power to all peripherals when starting up the system.

            The analyst currently has two choices vis a vis the BCTP videos. He may either 1)
check out from the archive the "set" of videos supporting his "rotation set" or 2) wait until
the point in time that he desires to view a particular video. At this point he may then check

out the appropriate tape.

              After conducting a data retrieval query the Record List pull down list box within the
_ Data Display will contain all of the records that met that query. Video records that met the

                                                                                 29


---

   search criteria will be listed along with those of other media types. Remember the media type
   is shown in the Record List pull down on the right hand side of the record description. Select
   the record and the Data Display will show the textual list of the video of descriptive topics.
   The VIDEO icon will be highlighted in full color. Click on the VIDEO icon and you will be

, prompted with a dialog box to insert the VCR tape. The VCR tape will be referred to by its

   Archive Reference Identification number. Insert the appropriate tape into the VCR.

   The word search process uses the “words” in the topics list to look for query matches.

>  Click OK in the Insert Tape prompt dialog box.

               The VCR will immediately advance the tape to the video segment that meets the

 search query. When the tape is correctly positioned, the computer monitor will show the

_ video control window. The computer will then automatically advance the tape to the desired
   tape segment. After fast forwarding the tape the computer will wait for the user to ‘initiate or
   PLAY the tape segment.

            This window allows the user to manually control the VCR, much like a normal VCR.
There are different buttons for PLay, Stop, REWIND, FAST FORWARD, and PAUSE. The image can
still be seen if the PAUSE button is used to stop the tape. The image can not be seen from _

either FAST FORWARD or REWIND modes. There is also a special button that acts as a reset,

REPLAY; it causes the video to go back to the beginning of the specific segment that met the
search query again. To choose any of these commands, just place the cursor on them and
click. There are three other pieces of information the video control window will provide: the
start time/end time of the data that met the search query; the total segment time; and a

running counter that progresses in a time count (minutes/seconds) of tape time. For example,'

if the entire video tape was 100 minutes long, but the segment that met the search query was
only 4 minutes in the middle of that, then the running counter may show anywhere from
48:00 to 52:00.

              Caution should be used to record the segment start and end time before viewing.
  Normally, the segment will play and stop at its end: however if the analyst uses the FAST
_ FORWARD or REWIND buttons during the segment viewing the video mode will change from

                                                                                  30


---

segment play to browse. Browse mode gives the analyst access to the entire video tape but

cannot return to the segment play mode without going back to the segment start. Therefore, it

is best to record the times associated with a segment in order that you can use the VCR

controls in the most efficient manner.  .

   VI. Saving and Printing Your Work

               A necessary step to all analysis is the documentation of the analysis. The BCTP db
   can be: used to facilitate the documentation. The text field within the Data Display dialogues

__ allows the user to select the appropriate text and copy it to the system clipboard. An analyst

   can transfer the text from the system clipboard to a report document by using the paste
   option/command from the destination application's Edit menu.

Printing From the Analyst’s Notebook
            Printing from the analyst's notebook is extremely easy. Simply select PRINT from the

file menu items.

  Printing Pictures or Maps

            Paintshop Pro® allows the user to select, copy and paste graphics into most word

_ processors and into the Window clipboard. Additionally, the user can print from Paintshop
  Pro® by choosing PRINT from the FILE menu.

                                           31


---

                                REFERENCES

   1) Research Plan for Battle Command Training Program (BCTP) Database Development,
              U.S. Army Research Institute, 17 August 1993.

   , 2) Battle Command Training Program (BCTP) Front End Analysis, U.S. Army Research

;  Institute, 22 January 1993.

   3) Battle Command Training Program (BCTP) Database Concept, U.S. Army Research

               Institute, 22 January 1993.

   4) Battle Command Training Program (BCTP) Requirements Analysis, U.S. Army Research
              Institute, 22 January 1993.

   5) BCTP Data Conference Read Ahead-Package, U.S. Army Research Institute, 15 December

               1992.

   6) Management Information Systems — Strategy and Action, C. Parker and T. Case,
              McGraw-Hill, 1993.

   7) Microsoft® Word® User’s Guide, Microsoft Corporation, 1993.

   8) Management Information Systems — The Manager’s View, R. Schultheis and M. Sumner,
               Irwin, 1992.

    9) Analysis and Design of Information Systems, J. A. Senn, McGraw-Hill, 1984.
   10) Microsoft® FoxPro® User’s Guide, Microsoft Corporation, 1993.

   i } ‘re £


---

TROUBLE SHOOTING

                                    CONTACTS

BCTP db Database Administrator           BCTP db Database Administrator
(ARI-FLVN)                               (ARI-POM)
Army Research Institute Field Unit       P.O. Box 5787
Attn: PERI-RK                            Bldg 104
P.O. Box 3407                            Presidio of Monterey, CA 93944
Fort Leavenworth, KS 66027-0347          AVN (929-3329)
AVN (552-4933)
Commercial (913) 684-4933                Commercial (408) 372-3329

                                    B-1


---

     BCTP DB DATA TYPES AND MEDIA

               This appendix describes the BCTP data sources and the data media. It provides the
- user an understanding of the range and types of data that will be included in the database.

   Data sources and formats vary between BCTP teams and WFXs. The BCTP is an evolving

  training tool. Therefore the analyst must understand that some data and data forms will

   change over time.

              BCTP considers all WFX data as inherently sensitive. The sensitivity consists of any
 attribution of unit designations with any specific activity. Additionally, certain data types have

information that may require special access requirements due to either controversial content,

 personal information, or overall training readiness evaluations. These data types have been
 referred to as highly sensitive. User training and the BCTP db password system is the first
' step to control the access and misuse of the BCTP data. These measures are an attempt to
 meet BCTP and unit desires not to embarrass units or individuals within those units.

            The data types available from each WFX are categorized into eight subject areas. The
reader will see that a number of data sources are often used in more than one subject area.

The subject areas and the data types they contain are:

> i  Unit Generated: Documents and Products that are produced by the WFX and OPFOR
     unit.

>    Unit Performance: Documents and Videos produced by O/Cs, BCTP and Analyst that

     address WFX results.

                           C-1


---

Rotational Information: Documents that provide background facts and information
briefed to the exercise director and that put the WFX in context.

Objective Battle Data: Statistical data that is produced by the simulation and can be used

to conduct original analysis.

Battle Description: Battle information that is produced by any source and contains a
playback or description of the battle.

Player Unit Profile: information on the WFX unit that could help put the unit itselfin

context. Thisdata.isrhot currently available.

Good Ideas: Documentation of successful concepts, ways of doing business, and lessons
learned that are provided by O/Cs, SMEs, contractors or others.

Trends:
* FER analysis: Analyst generated tables that quickly highlight the emerging BOS

      trends across rotations and time.

* Objective Data: Statistical computer generated data that is loaded into charts to

     display emerging trends across rotations and time, within the context of the —

      simulation.

Unit Generated Data

Exercise Unit generated Plans/Orders, FRAGOs, Maps and Overlays:

* Description of data: These data include the plans, orders, FRAGOs, requests,

reports, maps and overlays of the unit being trained.

8 Media: Various stapled and loose hardcopy documents, acetate overlays, VGTs and

Floppy disks.                                          :


---

   OPFOR generated data:
   ¢ Description of data: These data include the plans, orders, FRAGOs, requests,

         reports,maps and overlays used by the OPFOR to conduct the WFX.
   ¢ Media: Various stapled and loose hardcopy documents, acetate overlays, VGTs and

         Floppy disks.

  Unit Performance Data

   After Action Review (AAR) video tapes:

  ° Description of data: These data include video tapes taken during the AARs

         (normally 2). Topics that are included are unit strengths and weaknesses, areas to
    _ Sustain or improve and supporting VGTs and briefing charts.
   ¢ Media: 2 - 4 video tapes.

   Army Command and Control Evaluation System (ACCES) data:
   * Description of data: These data include detailed observer notes and final reports

         evaluating C2 operations/functions.
   * Media: Hardcopy report and Floppy disks.

   Final Exercise Report (FER):

  * Description of data: The FER contains an overview of the exercise (key dates,

         scenario and tactical outcomes), Battlefield Operating Systems observations, After
         Action Review Products from both AARs, World Class OPFOR information
         (campaign plans and OPFOR commanders comments for the AARs), and a listing
         of video tapes being provided to the unit for the AARs.
   * Media: Bound hardcopy document.

   O/C crosswalk of the unit Operations Plan:
- © Description of data: The crosswalk is a comparison, conducted by O/C's, of the

         training units’ operations plan against the higher headquarters plan. It contains

                                                                        C-3


---

     comparisons by BOS and helps identify to the O/C's, strengths and weaknesses in

      the unit plan.

* Media: Stapled hardcopy document.

Observer/Controller (O/C) notes and checklists:

* Description of data: These notes could include observations of unit and/or staff

section performance that is an indicator of training strengths and weaknesses as

well as the informal O/C AARs conducted with appropiate staff sections.                   -

"eMedia: Various loose hardcopy notes, charta and VGTs (At present, this data is? of

not available)

Rotational Information

Exercise Control 5 day cartoon:
* Description of data: These data include EXCON provided graphic drawings of the

      battlefield with OPFOR/WFX unit positions as of the exercise start through days 1-
      5 and the end of the exercise.
* Media: 5 - 7 pages of hardcopy drawings.

Exercise Control briefing slides:
* Description of data: These data include EXCON provided information on weather,

      terrain, OPFOR vs. WFX unit status (strength), correlation of forces and means
      (COFM), and a Montage of unit locations.
* Media: Various loose hardcopy VGTs and documents.

White Cell directives:

* Description of data: This would be any instructions that change the WFX unit or

   OPFOR structures (i.e., additional units), boundary chatBes, scripted events, etc.

* Media: Various hardcopy notes, if provided. (At present, thisdata is ‘not

      available)

                                                                      C-4


---

Objective Battle Data

Warfighter After Action Report System (WAARS) or After Action Review

(AARS) tape:
     Description of data: These data provide comparisons of WFX units vs. OPFOR
      actions and results by BOS. It includes: WFX unit and OPFOR combat damage
      reports, attrition reports, personnel casualty reports, unit supply reports,
     maintenance reports, medical reports, artillery reports, air mission reports, etc. —
      Media: The WAARS tape consists of one, ten-inch, nine track reel to reel tape.
     The AARS tape consists of one 8mm data tape.

Battle Description

After Action Review (AAR) video tapes:
are: Battle Summary, OPFOR Summary, BOS observations and discussion, areas to
sustain or improve and supporting VGTs and briefing charts.

      Media: 2 -4 video tapes.

Workstation Reporting System (WRS) tape:

      Description of data: This is a log that contains those events considered as
      significant by the workstation controller and are generally arranged by BOS.
      Comments would include: personnel transfers, movement orders, notes on time
      FRAGOs were received, contact reports with small units, workaround information,
      units under SOF attack, ammo delivery projections, units being overrun, etc.
      Media: Digital Data tapes

Final Exercise Report (FER):
      Description of data: The FER contains an overview of the exercise (key dates,
      scenario and tactical outcomes), Battle Summaries, Battlefield Operating Systems
      observations, After Action Review Products from both AARs, World Class OPFOR


---

information (campaign plans and OPFOR commanders comments for the AARs),
and a listing of video tapes being provided to the unit for the AARs.
Media: Bound hardcopy document.

Timeline:

Description of data: The timeline is an extract of significant events that occurred

during the rotation. It is extracted from the FER Tactical Outcomes by an analyst

or from ACCES data.                      |

Media: Created by an Analyst or provided Hardcopy document

Battle Replay:
     Description of data: The graphic replay of the computer simulation battle.
     Media: SUN Raster Graphics files,

Player Unit Profile
TBP when and if this data is collected.

Good Ideas

Good Ideas:
      Description of data: Any documentation of successful concepts, ways of doing
     business, and lessons learned that are provided by O/Cs, SMEs, contractors,
      analysts or others.
     Media: Hardcopy documents, floppy disk, VGTs, Charts, Tables - any media.

Trends

FER analysis:

Final Exercise Report (FER):
      Description of data: The FER contains an overview of the exercise (key dates,
      scenario and tactical outcomes), Battle Summaries, Battlefield Operating Systems

                                                                      C-6


---

     observations, After Action Review Products from both AARs, World Class OPFOR
     information (campaign plans and OPFOR commanders comments for the AARs),
      and a listing of video tapes being provided to the unit for the AARs.
* Media: Bound hardcopy document.

Objective Data:

Warfighter After Action Report System (WAARS) or After Action Review

(AARS) tape:                                  ,

¢ Description of data: These data provide comparisons of WFX units vs. OPFOR

actions and results by BOS. It includes: WFX unit and OPFOR combat damage

reports, attrition reports, personnel casualty reports, unit supply reports,

maintenance reports, medical reports, artillery reports, air mission reports, etc.

¢ Media: The WAARS tape consists of one, ten-inch, nine track reel to reel tape.

The AARS tape consists of one 8mm data tape.

                 C-7


---

                      BCTP DB SEARCH LOGIC

               The Battle Command database, BCTP db, is a very powerful tool that can be used
   most effectively when the analyst understands the logic behind specific data queries. There

are various search options that can be employed, each "finding" the specific user-requested

data ina very simple, step-by-step approach.

   .  The discussion begins by describing                                                                                   Aviati
                                                                                                                              Vviation
,     .               .                                                           .       Intelli
the entire database as the universal set. This                                                           Reports
                                                                                          me 8 FER

universal set contains every single word,                                                 Air Defense             FRAGO's

                                                                             ae.                 AAR     Requests           Command
                                                                                          Miss                    Maneuver
large or small, and all symbols within its                                                                                   &
                                                                                                 18si0n                      Control
boundaries (Figure D-1). All the various::.
                                                                                          Statement
Battlefield Operating Systems (BOSs),                                                                    OPORD's                    .

                                                                                                                            Artillery

reports, comments, summaries, orders,                                                     Figure D-1. The Universal Set

analyses etc. are entered as data from

previous Warfighter Exercises (WFXs).

         ese     are

      Thif data js very important to many people in the U.S. Army, so we must develop

    some means to access it in an efficient and logical                                                      C2

  manner. For simplicity's sake, we break the data                                                       Maneuver

. down into its various components so that specific                                                      Intelligence

queries can be accessed quickly and easily. The                                                          Fire Support

first breakdown is between the BOSs. The BOSs                                                            Aviation

represent different functional areas within the                                                          Air Defense

entire. battlefield.They are as follows: Command                                                            . CS
and Control, Fire Support, Maneuver, Engineer,
                                                                                          Figure D-2. Battlefield Operating

                                                                                                         Systems (BOS).

                                                                                     D-1


---

Combat Service Support, Air Defense, and Intelligence. In order to see this breakdown more
clearly, we will "cut" the universal set into seven horizontal blocks, each corresponding to a
different BOS (Figure D-2). If the user wanted to access or analyze maneuver data, in theory
the computer would only retrieve data from that specific horizontal block.

           We can now make a second breakdown of the universal set. This breakdown will deal

with various documents from the WFXs data.

' Examples of these documents could be as

_ follows: Opords/Plans, Reports, Requests,

Messages, or Staff Working Documents. As

we did in Figure D-2, we will "cut" the

universal set into five vertical columns, each

corresponding to a different type of document

' (Figure D-3). If the user desires to access or  Figure D-3. Document Examples.

analyze Orders and Plans, the computer

would only retrieve data from that specific vertical column.

BDA                         Deep Attack                      With these two general types of -
                                                  data understood, we can go into greater
Collection  Synchronization                       detail — specific words. Since words
                                    FRAGO
                                                  make up the English language as we
             PIR            Perception
Obstacles                                         know it, they also form each piece of
                  Maneuver

Mission     OPORD           Field Artillery       data within the database. We can access

            D-4. Specific Words.                  these specific words by using the word
                                                  search function to enter the

word/symbol/numeral we're interested in retrieving. These alpha-numeric entries may be

found in any or all of the BOSs and documents mentioned before, or may not be found at all

(Figure D-4). It is with this specialized search command that we can pinpoint and retrieve

such words, symbols, or numerals no matter where they're located within the database.


---

             There is one final concept that needs to be explained before going on into more
 detailed examples and situations. In both the BOS choice list and Document list, there is an

option for ALL. This option accesses either all seven BOSs, or all five Document types, or

‘both (if ALL is chosen for both lists!). It is the default within the system, the "catch-all" if
 you will. By selecting this, the user is choosing not to make any specific query for that area,
 whether BOS or Document.

            Now that simple logic behind specific searches within different areas of the database

have been reviewed, it is important to move on to some very important topics and terms.

These first two are the basis for the rest of this section. Both are simple words we use

everyday in our speech as conjunctions—and and or. In the following sections, when they are

in italics, they are to be understood as our special terms; otherwise, they play their normal

grammatical role. The definitions of the two:

.  and — all chosen selections will have to be taken into account, i.e. only data selected

   must satisfy all requirements of the query;

.  or — data selected will satisfy any one of the requirements from the user's query of

   selections.

           Don't worry if that seems confusing, the following figures make the terms much more

_ understandable.

   Figure D-5. AND.                                                Figure D-6. OR.
                                                              D-3


---

                                                                                                                                                                                                                                                                                                                                                                                                 1

               If we choose to use mathematical terminology, and is the same as intersection; only
   that which both parts have in common is accessed (Figure D-5). Using the same terminology,
   or is equivalent to union; any segment of either of the parts can be accessed (Figure D-6).
   These bubble diagrams will be used in the following examples to help facilitate discussion.

               Rule #1: The BOS list selection and Document list selection are always and.
   Therefore, whichever BOS you choose, the computer will only look in that horizontal block.
- Similarly, whichever Document is selected, only that vertical column in accessed.

           Orders  Reports  Requests  Messages       Staff
            and                                  Working
           Plans                                Documents

C2
Mnvw
Intel
Fire Sprt
Eng

CSS

                   Figure D-7. Rule #1.

                The common ground upon which these two meet will be retrieved as data for the user.
    For example, let's say the user chooses BOS—Intelligence and Document—Messages. Then

~ the only type of data that can be retrieved on this query for user analysis will be messages

   that are concerned with Intelligence, for example Intelligence Summaries (IntSums), on
   whichever WFX data is being analyzed (Figure D-7).


---

            Another way of looking at it is shown in Figure D-8, where only the common ground
that meets all selections is chosen. Again, the BOS selection and the Document selection are
always and.

Rule #2: Any alpha-numeric entries chosen in the word search selection area are

always or among themselves.

This means that if you choose

more than one entry for a word

search, that if either entry is

found in the database, it will be

retrieved for the user's analysis.

These entries have no need to

have anything in common, nor

does it matter what is selected in          eee                                  ho

the BOS or Document list (Figure            Figure D-8. Rule #1 Bubble Diagram.

D-9). For example, the user

enters BDA as one entry, and OVERRUN

as the second entry (one can have up to

five different entries for search, all of

which will be or). Then, anytime BDA

or Overrun is found as an entry in the

database, the screen will either center

itself on that word or highlight that word

(see Appendix A) from among the

documents that contain it.                  aes  wears            a

                                            Figure D-9. Rule #2.

           Before going on with the final four rules, there is one thing that needs to be pointed
out. We have introduced and and or as terms defining relationships among sections of the
database. In the word search section of the computer's screen, the user will see that AND and
OR are choices on the lower right (we will use small caps to identify key punches). By

                                                                            D-5


---

choosing AND, we are choosing the and relationship; by choosing OR, we are choosing the or
relationship. A more detailed explanation follows...

Rule #3: If choosing AND

under the word search with only one                 [|

entry selected, the user is refining          (XX

the search to a more specific topic.

We already know that the BOS and

Document list are and; now the

entry chosen also becomes and with

them. This means the only data                Ee

      .                                           Figure D-10. Rule #3.

retrieved from the database must

contain the entry chosen and fall under the selected BOS and Document (Figure D-10).

            For example, the user selects BOS—Maneuver, Document—Requests, and under word

search enters OVERRUN while selecting AND. The only data accessed must be concerned with

maneuver requests and contain the word Overrun at some place within the document. It is
now obvious, hopefully, that using the AND selection causes the search to become more
specific.

Rule #4; If choosing OR under

 the word search with only one entry

selected, the user is enlarging the

                       j

 search to a more general topic. Again,

-we know that BOS and Document are

and, but by choosing or, our selected

entry is not necessarily intersected

with those specific documents. Now            Figure D-11. Rule #4.
the computer will search the database

for any data that is either the common ground of the BOS and Document selection, or any

                                         D-6


---

time the chosen entry is found (Figure D-11). For example, let's say we've chosen
BOS—Fire Support, Document—Reports, and under word search entered BDA while
selecting OR. The data accessed must either deal with Fire Support reports or contain the
word BDA in any document. You can see our search is now more general.

Rule #5: If choosing OR

under the word search with more

than one entry selected, the user is

' Just expanding the search more and

more with each entry. This is

similar to Rule #4, but becoming

even more general. We know the

BOS and Document selection are

' and, but by selecting oR in the     —  a
  word search with multiple entries,
                                      Figure D-12. Rule #5.

the computer will retrieve data that is either common ground for the BOS and Document or

anytime any of the entries selected appear in a document, related or not (Figure D-12).

Following previous examples, the user chooses BOS—Combat Service Support,

Document-—Opords/Plans, and under word search selects OR while entering MAINTENANCE,

CROSS-LEVEL, and BRIDGE as words. The accessed data will be concerned with either

Engineer's Opords/Plans, or maintenance or cross-levels or bridges in any document within
the database.

            Rule #6; If choosing AND under the word search with more than one entry selected,
the different entries are still or, but the user has created different groups of and. This rule is
the most difficult to comprehend, but once mastered, the logic can be easily understood no
matter what selections are made. If two entries are chosen, then there are two groups of data
that the computer can retrieve. The first will deal with only that data that is common for BOS

and Document selected containing the first entry; the second group will deal with the same

BOS and Document material, but containing the second entry selected, and so on (Figure

                                                                                D-7


---

|            |

   ra as  -

               D-13). So let's say BOS—Fire         QW

               Support, Document—Reports,                  i

               the AND selection, and two            Zs, Q\

             entries, Q36 and Q37, are all                     Word B

              chosen. Then the only data         | Figure D-13. Rule #6.

             ' retrieved will either be Fire

               Support reports with the entry

               Q36, or Fire Support reports

             . containing the entry Q37. This

               rule uses parts of many previous

               rules, hence is presented Jast.

                            By gaining an understanding of this section, the user can grasp the logic used by the
             - computer in searching, accessing, and retrieving data from the database. Whether the search

               be very general or very specific, the desired outcome is a knowledgeable user who can

               manipulate the screen to access only the exact documents and/or data that they desire.


---

                           GLOSSARY

           After Action Review

           After Action Review System

   ACCES   Army Command and Control Evaluation System .
   ADA
' AJS      Air Defense Artillery

  BCTP     Automated Journal System

   BICM    Army Research Institute
   BOS
    C2 |   - Battle Command Training Program
    CBS
   COA     Battlefield Intelligence Collection Model
   COFM
   CSS     Battlefield Operating System(s)
    db
   DBF     Command and Control
   DTG
   ENG     Corps Battle Simulator
   EXCON
    FER    Course Of Action                   COTS Pp?
   FLVN
   FRAGO   Correlation Of Forces and Means
 . HQ
   O/C     Combat Service Support
   OPFOR
    OPORD  database
   POM
           Data Base File
 . PSP
    QBE    Date Time Group

' SME      Engineer

   SOF     Exercise Control
   SPF
   SQL     Final Exercise Report
   VCR
   VGT     Fort Leavenworth, Kansas
~ WAARS
   WFX     Fragmentary Order

           Headquarters

           Observer/Controller

           Opposing Force

           Operations Order

           Presidio of Monterey, California

           Proficiency Sustainment Package

           Query By Example

           Subject Matter Expert

           Special Operations Forces

           Special Purpose Forces

           Structured Query Language

           Video Cassette Recorder

           View Graph Transparency

           WarFighter After Action Reporting System
           WarFighter Exercise

                                  GLOS-1


---

                                                                                                                 CONTRACT #: MDA 903-92-D-0075
                                                                                                                           DELIVERABLE #: 0036-01-0036AC

                                                                                                                                               September 15, 1995

        CONVERTED DATA STRUCTURES:
                    BCTP DATA BASE

                                   Jack A. Briscoe
                                  BDM Federal, Inc.
Submitted by: Mr. Michael R. McCluskey, Acting Chief
               Unit-Collective Training Research Unit
                     and Dr. Zita M. Simutis, Director
            Personnel and Training Research Division
Dr. Stanley Halpin, Contracting Officer's Representative

              j Ah ’ ‘ RS

                            ARMY REF ney INSTITUTE

                                October 24, 1995
                        U.S. Army Research Institute


---

Converted Data Structures:
BCTP Data Base

Contents

                                                                                      Page

Converting BCTPdb structures to INFORMIX

1.0 Modifying the structures ....... 0.0... cee           cee eens 1

2.0 Conversion from FoxPro to INFORMIX ......0. 0. : e. ee. e ee. ee. ee. ns 4

AppendixA INFORMIX Table Definitions .........  00.0.0. cece ec eee eee ee A-1

                            LIST OF TABLES

Table A.1 ROTATION - Summary rotation information ..................00-02 e2 ee       A- 1
                                                                                      A- 1
Table A.2 SUST - Sustain Comments ..... eee en eee een e eee n teenie eene            A- 1
                                                                                      A- 1
Table A.3 OBJTREND - Objective trends .... 0.0. .0.. .. e e. ee. ee . ee.e. ee        A- 2
                                                                                      A-2
Table A.4 REPORTS- Reports table is used internally by BCdb code ...............      A-2
                                                                                      A-3
Table A.5 BOB - Blueprint of the Battlefield Reference .........................4..   A- 3
                                                                                      A-4
Table A.6 Gl-Good Ideas ............ cec ete e ee ee eens                             A-4
                                                                                      A-4
Table A.7 TAAR-AAR Trends ........... 0: cece eee eee eee eee eae                     A-5
                                                                                      A-5
Table A.8 TFER-FER Trends ........... 0... eee   eee eee eens                         A-6
                                                                                      A-7
Table A.9 B_ARTILL - Blue Combat Artillery Missions ....................0.0000.       A-7
                                                                                      A-8
Table A.10 B_ATTRIT - Blue Combat Attrition ......... 0.0.0...  eee ee                A- 8

Table A.11 B_MED - Blue Medical Report .....0. .2... . c. ece.ee. e e. ee.e. ee

Table A.12 BLUE_AIR - Blue Army Aviation Report...............2...22.0000008.

Table A.13 CBSTAT - Combat Damage Report ...... 2... . 0. . c.e. e . eee. ee . eee

Table A.14 DATA - Textual, Video, Graphics ..... 0.. .. e. ee.e .e .e .. eee

Table A.15 INTEL - Intel Reports ........ 0... 00. c eee        eee eens

Table A.16 R_ADARPT - Red Air Defense Report ............... Leec ee c eeee eee

Table A.17 R_ARTILL - Red Combat Artillery Missions ..........5.........200005.

Table A.18 WIPE_OUT - Destroyed Unit Report ........ 00.... . c. ee . eee.ee.e. ee

Table A.19 WRS - Workstation Reporting System .... 0.0. ... . 0. . cee e. ee e .e. e


---

Converting BCTPdb structures to INFORMIX

            Two steps were required to convert the existing FoxPro data structures to INFORMIX:

            (1) Implement any desired/required changes to the existing data structures to make them
                     compatible with INFORMIX and/or to implement desired changes and improvements,
                     and

            (2) Create the INFORMIX database on the new database server, then physically convert
                      the data structures from FoxPro to INFORMIX.

1.0 Modifying the structures

            The current FoxPro implementation stores information aggregated across rotations in the
root database directory BCDB. Rotation-specific information is stored in identically-named tables
in separate sub-directories. The current structure is shown below. Directory names are bold-faced;
table names are italicized:

                 BCDB
                             ROTATION
                            SUST
                            OBJTREND
                             REPORTS
                             SUPPORT
                                                  BOB
                                                   Gi
                                                   TAAR
                                                   TFER
                            93DHHRO4
                                                  B_ARTILL
                                                 B_ATTRIT
                                                  B_MED
                                                  BLUE_AIR
                                                 CBSTAT
                                                  DATA
                                                  INTEL
                                                  R_ADARPT
                                                    R_ARTILL
                                                     WIPE_OUT
                                                    WRS
                             93DHHA01
                                                    B_ARTILL

93DLHA01  R_ADARPT
94DHHAO1  R_ARTILL
93DLHA02  WIPE_OUT
94DHHA02  WRS

          DATA

          DATA

          DATA

          DATA


---

            As far as FoxPro is concerned, there are only tables; the concept of a database containing
tables is imposed by the user interface, the screens with their embedded code which handles the
file details. For example, there is one DATA table for each rotation in the database, two B_ARTILL
tables, etc. The code handles the access depending upon the user's selection of rotation(s).

             INFORMIX explicitly recognizes databases as collections of tables, and will not tolerate two
tables with the same name. To migrate the BCdb "database" to INFORMIX, then, either the
separate tables with the same names have to be renamed, e.g. 93DHHRO7_DATA and
93DHHAO01_DATA, or the data in the separate tables can be combined, adding a new field to identify
the rotation.

            Clearly, the cleaner solution is the second one: combine the tables and add a rotation index.
This solution avoids the creation of new tables every time a new rotation's worth of data is added
to the database. it also simplifies some of the internal logic, avoiding frequently having to open and
close tables. The downside is the addition of an integer field in each of the combined tables.

            The job of modifying and combining the tables was done in FoxPro. This allowed the job
to be done quickly, and as importantly, locally. The combined tables generally maintain the same
structures as the originals, with the the addition of the ROTATION_INDEX field. The only major
restructuring done was with the DATA table, as described in Appendix A.

            Once the structures were altered and tested, the entire database was converted from
FoxPro to Microsoft Access 2.0. This was done for three reasons:

            (1) Access supports concept of a named database as a collection of tables, which is
                       consistent with INFORMIX;

            (2) Access supports longer element names, so that renaming the fields could be done
                      prior to the step of transferring the data across the phone line; and

             (3) Access is supported by a more robust opBc (Object Database Connectivity) driver,
                      which is used by Windows to handle database interactions, meaning fewer problems
                       during the actual database conversion process.


---

When the new structures have been completed, the file structure will be as shown below. Tables
containing the new ROTATION_INDEX field are marked with an asterisk. Note that table ROTATION
was modified to add that field; this step has been taken to allow ROTATION_INDEX to be an integer
field, providing better database performance. Tables which will be consolidated are noted by the
number of tables which have been combined.

=    ROTATION*

     SUST

     OBJTREND

AWN  REPORTS

O O  BOB

     GI

     TAAR

     TFER

OON  B_ARTILL* (2)

10   B_ATTRIT* (2)

11.  B_MED* (2)

12   BLUE_AIR* (2)

13.  CBSTAT* (2)

44.  -DATA* (6)

15   INTEL* (2)

16   R_ADARPT* (2)

17   R_ARTILL* (2)

18   WIPE_OUT* (2)

19   WRS* (2)

           Appendix A contains the structures of the intermediate tables - element by element. It also
contains a column listing of the implemented, more descriptive, INFORMIX element name.


---

2.0 Conversion from FoxPro to INFORMIX

            The next step was the conversion of the new FoxPro (Access) tables to INFORMIX - along
with changing the element names. This step was accomplished by using the PowerBuilder 4.0
facility called the Data Pipeline, which supports rapid conversion, table by table, between different
Database types. The table below reflects the results of the data conversion/transfer process.

Table Name   Records     Problems/Comments/Format Changes                             |

 ROTATION   Transferred  OK
 SUST                6
 OBJTREND           90   OK
                     8
 REPORTS                 OK
                  7
 BOB                     OK             7                                             I
 GI                267
 TAAR                1   OK
 TFER
 B_ARTILL         294    MEMO-type DATA field was changed to CHARACTER*10000
                  1076
 B_ATTRIT         6339   OK
                14735
 B_MED             607   OK
 BLUE_AIR         2082
 CBSTAT          17709   OK
 DATA             2357
                         OK
 INTEL            2239
                         OK
 R_ADARPT         2178
                         OK
~R_ARTILL        4538
                         OK
 WIPE_OUT         2039
                         Split into tables DATA_INDEX and DATA_CONTENTS. See details
WRS               591    in Appendix 2, section A.14

                         Subset of original 87430 records - includes only

                         DETECTED_UNIT_TYPE=ENGR

                         OK

                         Subset of original 17772 records - includes only

                         NUMBER_HIT>0

                         OK

                         Memo field COMMENTS changed to CHAR“5000


---

Appendix A - BCTPdb Table Layouts

Appendix A INFORMIX Table Definitions
A.1 Table ROTATION - Summary rotation information

Field  FoxPro Field Name  INFORMIX Field Name      Type            Width
New                       ROTATION_INDEX           INTEGER            4
       ROTCODE            ROTATION_CODE            VARCHAR            10
   1   ROTID              ROTATION_ID              VARCHAR           10
  2    UNIT               UNIT_IDENTIFICATION      VARCHAR           20
  3    ROTSTART           ROTATION_START           DATE               8
  4    ROTEND             ROTATION_END             DATE               8
  5
       ROTLOC             ROTATION_LOCATION        VARCHAR          20
  6
       BCTPTEAM           BCTP_TEAM                VARCHAR           10
  7    COMPONENT          COMPONENT                VARCHAR            10
  8    UNITTYPE           UNIT_TYPE                VARCHAR           11
  9    RESTART            HAD_RESTART              CHAR               4
  10

A.2 Table SUST - Sustain Comments

Field  FoxPro Field Name  INFORMIX Field Name      Type            Width
  1    BOBREF             BOB_REFERENCE            VARCHAR            3
  2    SUSTAIN            SUSTAIN                  VARCHAR           30

A.3 Table OBJTREND - Objective trends

Field  FoxPro Field Name  INFORMIX Field Name      Type            Width
   1   OTREND             OBJECTIVE_TREND          VARCHAR           50
  2    FILENAME           FILE_NAME                VARCHAR            10
  3    BOS                BOS                      VARCHAR            12
  4    BOSNO              BOS_NUMBER               DOUBLE

A.4 Table REPORTS - Reports table is used internally by BCdb code

Field  FoxPro Field Name  INFORMIX Field Name      Type            Width
   1   REPORT             REPORT_NAME              VARCHAR           20
  2    TABLENAME          TABLE_NAME               VARCHAR            10
  3    ENABLED            REPORT_ENABLED           DOUBLE


---

Appendix A - BCTPdb Table Layouts

A.5 Table BOB - Blueprint of the Battlefield Reference

Field   FoxPro Field Name    INFORMIX Field Name        Type     Width
   1    BOBREF               BOB_REFERENCE              VARCHAR    30
  2     BOBREFDESC           BOB_ DESCRIPTION           Memo

A.6 Table GI - Good Ideas

Field   FoxPro Field Name    INFORMIX Field Name        Type     Width

New     TYPEOFDATA           ROTATION_INDEX-~           INTEGER    20
  1                          TYPE_OF_DATA               VARCHAR
        DATANAME                                                   45
   2    DATASOURCE           DATA_NAME                  VARCHAR     15
  3     SIDE                 DATA_SOURCE                VARCHAR      1
  4     MEDIUM               SIDE                       VARCHAR     10
   5                         MEDIUM                     VARCHAR
        FILENAME                                                   35
  6     ORDER                FILENAME                   VARCHAR     3
  7     ORG                  ORDER                      INTEGER    15
  8                          ORGANIZATION               VARCHAR
        TIMESENT                                                    12
  9     TIMERECVD            TIME_SENT                  VARCHAR    12
 10     BOBREF               TIME_RECEIVED              VARCHAR    30
  11    DATA                 BOB_REFERENCE              VARCHAR     10
‘12                          DATA                       Memo

A.7 Table TAAR - AAR Trends

 Field  FoxPro Field Name    INFORMIX Field Name        Type     Width
 New                         ROTATION_INDEX             INTEGER
        ROTCODE              (Deleted)
    1   BOBREF               BOB_REFERENCE              VARCHAR  30
2
        SUSTAIN              SUSTAIN                    VARCHAR  30
   3    IMPROVE              IMPROVE
    4                                                   VARCHAR  30

                                   A-2


---

Appendix A - BCTPdb Table Layouts

A.8 Table TFER - FER Trends

Field   FoxPro Field Name    INFORMIX Field Name     Type     Width
New                          ROTATION_INDEX          INTEGER
        ROTCODE              (Deleted)                           3
   1    BOBREF               BOB_REFERENCE           VARCHAR     4
  2     EVAL                 EVALUATION              VARCHAR
  3

A.9 Table B_ARTILL - Blue Combat Artillery Missions

 Field  Field Name           Field Name              Type     Width
 New                                                 INTEGER
        MISSION              ROTATION_INDEX          VARCHAR    10
   1    MTYPE                MISSION_TYPE            VARCHAR     6
   2    TIME                 MTYPE                   VARCHAR     6
    3                        TIME                    VARCHAR
        UNIT                 UNIT                    VARCHAR     15
    4   LOCATION             LOCATION                VARCHAR    12
    5                        WEAPON                  VARCHAR
        WEAPON               AMMUNITION_TYPE         INTEGER    15
   6    AMMO                 ROUNDS                  VARCHAR     9
   7    ROUNDS               MPOI                    VARCHAR
    8   MPOI                 UNIT_HIT                VARCHAR    11
   9                         SYSTEM_HIT              INTEGER
        UNITHIT              NUMBER_HIT                         20
"40     SYSTEMHIT                                               15
- 411   NUMBERHIT

   12


---

Appendix A - BCTPdb Table Layouts

A.10 Table B_ATTRIT - Blue Combat Attrition

Field  FoxPro Field Name  INFORMIX Field Name  Type       Width
New                       ROTATION_INDEX       INTEGER
       TIMESTART          TIME_START           VARCHAR       6
   1   TIMEEND            TIME_END             VARCHAR       6
  2    UNIT               UNIT                 VARCHAR      15
  3    EQUIPMENT          EQUIPMENT            VARCHAR      20
  4    DESTROYED          DESTROYED            INTEGER
  §    DAMAGED            DAMAGED              INTEGER
  6

A.11 Table B_MED - Blue Medical Report

Field  FoxPro FieldName   INFORMIX Field Name  Type       Width
New                       ROTATION_INDEX       INTEGER
       STARTTIME          START_TIME           VARCHAR       6
  4    ENDTIME            END_TIME             VARCHAR       6
  2    UNIT               UNIT                 VARCHAR       15
  3    ADMITTED           ADMITTED             INTEGER
  4    RETURNED           RETURNED             INTEGER
  5    SHIFTED            SHIFTED              INTEGER
  6    DIED               DIED                 INTEGER
  7
       EVACUATED          EVACUATED            INTEGER
8

A.12 Table BLUE_AIR (Renamed B_AIR for consistency) - Blue Army Aviation Report

Field  FoxProField Name   INFORMIX Field Name   Type      Width

 New   MISSION            ROTATION_INDEX        INTEGER-    20
       TIME                                                  6
   1   LOCATION           MISSION_NAME          VARCHAR      12
2      UNIT               TIME                  VARCHAR      15
       SYSTEM             LOCATION              VARCHAR      15
   3   HITS               UNIT                  VARCHAR
   4                      SYSTEM                VARCHAR
   5                      HITS                 DOUBLE
   6


---

Appendix A - BCTPdb Table Layouts

A.13 Table CBSTAT - Combat Damage Report

Field  FoxPro FieldName   INFORMIX Field Name  Type              Width
New                       ROTATION_INDEX       INTEGER
       STATTIME           STATISTICS_TIME      VARCHAR              6
  1    SIDE               SIDE                 VARCHAR              1
  2                       UNIT                 VARCHAR
       UNIT               EQUIPMENT            VARCHAR              15
  3    EQUIPMENT          CAUSE                VARCHAR             15
  4    CAUSE              NUMBER_HIT           INTEGER             15
  5    NOHIT              NUMBER_WOUNDED       INTEGER
  6    NOWOUND            NUMBER_KILLED        INTEGER
  7    NOKILL
  8

A.14 Table DATA (DATA_INDEX, DATA_CONTENTS) - Textual, Video, Graphics

             The DATA table was restructured to make the field names more descriptive and to
more directly support the user interface. First, it was split into two tables, DATA_INDEX,
which contains all the information which describes the data, and DATA_CONTENTS, which
contains the bulk of the data fields. Next, the key fields which describe the data were re-
named and restructured. The table below indicates in general the changes that were made
during the restructuring process. Mappings between the old and new tables were not totally
direct; data formerly in the DATASOURCE field might have gone to the DOCUMENT_TYPE field
.or it might have been divided between the DOCUMENT_TYPE and SUBDOCUMENT_TYPE fields.
Additional fields DOCUMENT_NUMBER and SECTION_ID were added to simplify the data selec-
tion logic.

Field  FoxPro Field Name  Table*   INFORMIX Field Name  Type     Width
New                           1    ROTATION_INDEX       INTEGER
       TYPEOFDATA                                                  20
  1                          1     SUB_DOCUMENT         VARCHAR
       DATANAME                                                    45
   2   DATASOURCE             1    SECTION_TITLE        VARCHAR    15
   3   SIDE                   1    DOCUMENT_TYPE        VARCHAR     1
4      MEDIUM                 1    SIDE                 VARCHAR     10
   5   FILENAME               1    MEDIUM               VARCHAR    35
   6   ORDER                  2    FILE_NAME            VARCHAR
   7   ORG                     1   REC_ORDER            INTEGER    15
   8   DESTINATIO             1    ORGANIZATION         VARCHAR    15
   9                          2    DESTINATION          VARCHAR


---

Appendix A - BCTPdb Table Layouts

DATA Tabie(Continued)        Table* INFORMIX Field Name   Type       Width
 Field FoxPro Field Name                                  VARCHAR      12
                                                          VARCHAR      12
10 TIMESENT                       2     TIME_SENT         VARCHAR      15
                                                          VARCHAR      30
11 TIMERECVD                      2     TIME_RECEIVED     INTEGER
                                                                       30
12 OPNLTIMFRM                     2     OPNL_ TIME_FRAME  VARCHAR
                                                                      200
13. OPTYPE                        2     OPTYPE            VARCHAR       5
                                                          VARCHAR       3
14 ANALEVAL                       1,2.  ANALYSTS_ EVAL    VARCHAR

15 cp                             N/A   (Deleted)

16 BOBREF                         1     BOB_REFERENCE

17 ~—- BATTLELOC                  N/A   (Deleted)

18 OEG                            N/A — (Deleted) -

19 DATA                           2     TEXT_DATA

New                               1     SECTION_ID

New                               1     DOCUMENT_NUMBER

     *1- DATA_INDEX Table

          2- DATA_CONTENTS Table

A.15 Table INTEL - Intel Reports

   Field  FoxPro Field_Name       INFORMIX Field_Name          Type  Width
_ New                             ROTATION_INDEX           INTEGER
          SIDE                    SIDE                    VARCHAR        1
      1   DET_UNIT                DETECTED_UNIT           VARCHAR       10
      2
          DET_UN_TYP              DETECTED_UNIT_TYPE      VARCHAR      10
     3
          DET_TIME                DETECTION_TIME          VARCHAR       6
      4   ASSET_LEVE              ASSET_LEVEL             VARCHAR       2
     5
          ASSET_TYPE              ASSET_TYPE              VARCHAR       4
     6
          RECIPIENT               RECIPIENT               VARCHAR       10
      7   PERCEPT                 PERCEPTION              VARCHAR       10
      8   LOCATION                LOCATION                VARCHAR       11
      9   ACTIVITY                ACTIVITY                VARCHAR      10
    10    ORIENT                  ORIENTATION             VARCHAR       2
     11   PARENT                  PARENT                  VARCHAR       12
     12


---

        ew

Appendix A - BCTPdb Table Layouts

A.16 Table R_LADARPT Red Air Defense Report

Field   FoxPro Field Name  INFORMIX Field Name       Type     Width

New     TIME               ROTATION_INDEX            INTEGER     6
        AIRCRAFT                                                 9
   1    MISSION            TIME                      VARCHAR    15
  2     UNIT               AIRCRAFT                  VARCHAR     15
  3                        MISSION                   VARCHAR
  4     WEAPON             UNIT                      VARCHAR    15.

  5     LOCATION           WEAPON                    VARCHAR    12
        ENGTYPE                                                 12
  6                        LOCATION                  VARCHAR
  7     RPT_FIRED          ENGAGEMENT_ TYPE          VARCHAR

 8      EOE_FIRED          REPORTED _FIRED ,         INTEGER

  9     DESTROYED          EOE_FIRED                 INTEGER

 10     DAMAGED            DESTROYED                 INTEGER

  11                       DAMAGED                   INTEGER

A.17 Table R_ARTILL - Red Combat Artillery Missions

 Field  FoxPro Field Name  INFORMIX Field Name       Type     Width

 ‘New   MISSION            ROTATION_INDEX            INTEGER    10
    1                      MISSION                   VARCHAR
   2    MTYPE              MTYPE                     VARCHAR     6

_3      TIME               TIME                      VARCHAR    6

4       UNIT               UNIT                      VARCHAR    45
    5   LOCATION           LOCATION                  VARCHAR     12

   6    WEAPON             WEAPON                    VARCHAR    15
   7    AMMO               AMMUNITION_TYPE           VARCHAR     9

   8    ROUNDS             ROUNDS                    INTEGER    11
   9    MPO!               MPO!                      VARCHAR
                                                                20
   10   UNITHIT            UNIT_HIT                  VARCHAR     15
   11   SYSTEMHIT          SYSTEM_HIT                VARCHAR

   12   NUMBERHIT          NUMBER_HIT                INTEGER

                                   A-7


---

Appendix A - BCTPdb Table Layouts

A.18 Table WIPE_OUT - Destroyed Unit Report

Field  FoxProField Name   INFORMIX Field Name     Type     Width
New                                               INTEGER
       UNIT               ROTATION_INDEX          VARCHAR    15
  1    STATION            UNIT                    VARCHAR     10
  2    TIME                                       VARCHAR     6
  3    LOCATION           STATION                 VARCHAR     12
  4    THRESHHOLD                                 DOUBLE
  5    REMAINDER          TIME                    DOUBLE
  6
                          LOCATION

                          THRESHHOLD

                          REMAINDER            -

A.19 Table WRS - Workstation Reporting System

Field  FoxPro Field Name  INFORMIX Field Name     Type     Width

New    BOS                ROTATION_INDEX          INTEGER     4
       UNIT
   1   LOCATION           BOS                     VARCHAR    20
  2    DATE               UNIT                    VARCHAR     10
  3    TIME               LOCATION                VARCHAR    25
  4    WORKSTATION        DATE                    DATE
   5   COMMENTS           TIME                    VARCHAR      5
  6                       WORKSTATION             VARCHAR
 ‘7                       COMMENTS                CHAR        7
New                       COMMENT_FIELD           TEXT
                                                           5000

              Due to problems in transferring FoxPro/Access Memo fields, the structure of the WRS table
was changed; The COMMENTS field bacame a character field of size 5000 and contains the data
formerly heldin the Memo field. The COMMENT_FIELD was added for a later transfer of the textual
data, at which time the COMMENT field will be eliminated.


---

                                                                                                  Contract #: MDA 903-92-D-0075
                                                                                                  Deliverable #: 0036-01-0036AG
                                                                                                                            November 1, 1995

PowerBuilder User Interface
          BCTP Data Base

                                 _ Jack A. Briscoe
                                  BDM Federal, Inc.
    Submitted by: Mr. Michael R. McCluskey, Acting Chief
                 Unit-Collective Training Research Unit
                       and Dr. Zita M. Simutis, Director
                Personnel and Training Research Division

  Dr. Stanley Halpin, Contracting Officer’s Representative

o; )  AN
BRMY Profi NSIIIUTE

        November 30, 1995
U.S. Army Research Institute


---

PowerBuilder User Interface
BCTP Data Base

CONTENTS

                                                            Page

Overview of the PowerBuilder Implementation ...........0 . cc. c e.e.e0 ee0 eeae 1

PowerBuilder Windows ............ 0.0 cece eee eee ete e teen t nee enae 2

Main Window (W_main) ........0.. 00. cece ee eee eee e eens 2

Rotation Selection (W_rotsel) .. 0.0.0... ce eee teen e nes 2

Information Control (W_rot) .........0 0... ec cee eee      tenes 3

Battle Description (w_bdesc) ..... 0.0.2... 0.0.  ec eee tence eens 4

          TimeLine/ Overview (W_desc) ....0. . ce. ce e. ee . eee. ee. e en. eee 5

          Workstation Reporting System (W_wrs) .......00.00.e.ee.e . ee.e 5

Objective Data Control (W_objtop) ...0. ... . cee .e. ee . ee . ee . e 6

          Combat Battle Statistics (w_cbstat) ............0 0.2.0.0... 0c eee eee 6

          Battlefield Intelligence Collection Model (w_bicm) ................... 7

          Blue Air Activity (W_bair) 20e . e . e. ne 7

          Opfor Air Defense (W_ada) ....... 0... cec eee ene 8

          Artillery (W_artill) 2.0 ee .t. ee. e ene 8

          Destroyed Units (w_dest) .... 0.0.0... 0... cece  ee ee eee 8

          Blue Medical Units (w_med0i.c 0..s . 0.)ce.c.e.e.ee.e.e.. e.e.s 9

Performance Data (W_perf) ............ 0.0 9

          2.6.1 Data Display (W_d2) ... 00. ... .e .. e. ee. e ee 10

Unit-Generated Data (W_unit) .... 0.0.0.0... cec eeee tees 10

Rotational Information (W_rotin) ... 2.0.0.0... 0. ceee e eens 11

Limitations of the Current Implementation ......0. .00. .0. 0 . ecu.e . eee.e0 ens 12
             Test and Development Environment ..... 0.0. 00. 0: c. ec. e ee. e e . e. ns 12
            List of Current Limitations ........ 0.0.0.0... cec eee e eee 13

Deliverable Files 0.0.0... ec  ee eee ee ne tee een ae nes 13


---

                                   List of Figures

Figure 1 - BCTPdb Hierarchy ........0 0.0... ccc                 eee eens 1

Figure 2 - Main Window .......... 0... ccc   ee eet eee eee een e ees 2

Figure 3 - Rotation Selection .... 0.0.2.2... 0... cc  ee        eee nena 3

Figure 4 - Information Control 2.0.. ee. ns 3

Figure 5 - Battle Description Screen... 0..e . ne 4

Figure 6 - Timeline/ Overview Display .........0 02... cc ccc ce eee ee eee 5

Figure 7 - WRS Journal Entries...  0.0... eee eee 5

Figure 8 - Objective Data 2.0...                                 teens 6

Figure 9 - Battle Statistics 2...           ee cee enter e nes 6

Figure 10 - Intelligence 0.0... 20... . ce eee eee 7

Figure 11 ~ Blue Air Activity... cee ete eee 7

Figure 12 - OPFOR Air Defense ........ 0... cee        eee tee ete e eee 8

Figure 13 - Artillery... 0.. ee . e eens 8

Figure 14 - Destroyed Units 0.2 ee. eee. eee t. enes 8

Figure 15 - Blue Medical Units...  0.00.20... 0. ce              eee eens 9

Figure 16 - Unit Performance Data .........0 0... 0c cece ee eee eens 9

Figure 17 - Performance Data Display .... 0.0. .0... . ce. e cc .. ee .e. ee 10

Figure 18 - Unit Generated Data 0.0... 0...                  ce  ete ees 10

Figure 19 - Rotational Information .........0.0 0.0.00. eee  ee eens 11


---

PowerBuilder User Interface
         BCTP Data Base

Overview of the PowerBuilder Implementation

            The PowerBuilder implementation of the BCTPdb resembles the FoxPro version in most
respects. The screens have been left exactly the same, or improved, when possible. In some
cases, the interface has been modified to account for differences in the client-server environment.

            The user interface uses windows which contain standard Windows® controls throughout.
They consist of:

Command buttons which trigger an action when activated,
Drop-down list boxes which providea list of possible choices for the user to select,
Text Boxes which display one or more lines of text,
Picture boxes which display a graphic,
Text, which displays text which is an integral part of the underlying window,
Check boxes, which allow the user to select/deselect an option,
Radio buttons, which allow the user to select one of two or more options.

            The implementation also contains a   control unique to PowerBuilder -                              DataWindows.

DataWindows provide a_ convenient                            Wl bodb_pb)
mechanism for retrieving and displaying data                    Ei w_main
without the need to develop the underlying                            EA w_rotsel
queries separately. DataWindows also
provide a means to dynamically change the                              Ei w_rot

query, providing the flexibility needed for the                        = Ter dese

BCTPdb application.                                                                        ddatedesc

            The structure of the current              EA wows

implementation is shown in Figure 1. The top                 d_wrs

level is the PowerBuilder Application - called   E w_objtop

bedb_pb. Below the application are two               EA w_chstet

kinds of entities - Windows are denoted by          Eq w_bicm

the window icon, and DataWindows are                Ei w_beir

denoted by the spreadsheet-looking box.            een

                                                    Fl w dest

            Chains which end with a DataWindow                                             El w_medics
are those which have been _ fully
implemented and display data retrieved from                                   Fj w_pert
                                                                                   Fi w_d2
the BCTPdb database. The others currently                                           - El d_datatest

exist as stubs with further effort required to                          EX w_unit
be fully connected.
                                                                       El wae
             Subsequent sections will describe                      etw_erotin d_detetest
features and limitations, if any, of each
window in the current PowerBuilder                                                                    d_rotin
implementation.
                                                                               d_rotsel

                                                 Figure 1 - BCTPdb Hierarchy


---

PowerBuilder Windows

            This section describes the form and functionality of the PowerBuilder user interface -
describing each window shown in Figure 1 in that order.

Main Window (w_main)

            The Main window introduces users to the BCTPdb and controls which processing option
the user will perform. It also contains a message advising the user about the sensitivity of the
data which will be displayed. Figure 2 is a snapshot of the Main window. There are three option
buttons on the screen.

       The Trends button allows the user to =                 BCdb Prototype Database       +]

examine systemic trends identified by BCTP                                                 a |

Operations personnel and other Army                   Welcome to BCTP db

analysts. This option is not available for this       -                                =

version of the BCTPdb.                                Pes | %                          ne

                                                      Trends  Good Ideas Research

            The Good Ideas button allows the user to
"good ideas" documented by BCTP Operations
personnel and other Army analysts. This
option is not available for this version of the
BCTPdab.

       The Research button is the gateway for Figure 2 - Main Window

the user to examine a wealth of BCTP data.
The database contains objective data gleaned from VAX/SUN computer records of BCTP
exercises, documents prepared by participating units prior to and during their BCTP rotations, and
data collected by BCTP Operations personnel and contractors relating to the unit's performance
during the course of the WarFighter exercise.

Finally, the Quit button exits the BCTPdb software and returns the user to Windows.

Rotation Selection (w_rotsel)

            The Rotation Selection Window allows the user to select BCTP rotations based on a
number of criteria. Most criteria are selected on a one or all basis, where the choices (except for
echelon) include All, and any other choice selects only the one criterion. Figure 3 shows a
Rotation Selection Window upon entry. The rotations which currently meet the selection criteria
are listed in the "Selected Rotations" box, and become the "Investigation Set" for the next screen.

             First the user may set a period of years within which BCTP rotations are desired by setting
the Time Frame From and To values by means of the spinners.


---

        The user may select rotations for a specific echelon by selecting one of the Echelon radio

buttons (Corps, Division, or Brigade). Echelon is the only field which is restricted to one input -

thus the radio buttons.

        .     .                                        jo              Retation Selection                                          [+

        Unit type is selected from a drop-down = [time Frame                                                                       |
list box from All, Heavy, Light, Light-Heavy, or || rom[so Elrafacg |||

Heavy-Light.                                              Echelon                        Index Saalon Cade Ui

                                                           (Corps @ Division C: Brigade    penile     _o

        The simulation location for desired                Omen        Vocation            3 ssouMat  Bon)

rotations may be selected from the Location a                          Ae pacivese 20

drop down list box from All, Germany, or Tam                           Component
Korea.                                                             By

     The BCTP team assigned to the                     [ici No _& Dosen Matter

rotation may also be a criterion. Choices are                      —   [ox] (close)

A-C or All.                                            Figure 3 - Rotation Selection

            The selections for component are All,
Active, or Reserve.

        Whether or not there was a simulation restart during the rotation is the final selection.

            Once the user is satisfied with his selections, hitting the OK button moves to the
Information Control screen. Selecting Close at any point returns the user to the Main Window.

Information Control (w_rot)

            The Information Control screen serves as the gateway to the BCTP data. It allows the user
to make a final choice as to which rotations in the Investigation Set will be part of the Query Set.
Figure 4 shows the screen after several rotations have been selected. Upon selection of one or
more rotations to the Query Set (one or more rotations in the right-hand box), the processing
options are enabled.

        The buttons between the Investigation

Set and the Query Set are used to move
rotations to/from the two sets.                        =               —e——— cmon Ll:

             The Rotation Information button displays                              (stew ]
summary information relating to the specific
                                                                        L__sfeneve _]
rotation selected in the Investigation Set box.
                                                         | Rotational information | | tnt Performance | | Objective Gattle Data |
The Rotation Information windows is
                                                         | Unit Generated | | Playnr tint Profite | | Battie Description |
described in section 2.8.
                                                       Figure 4 - Information Control
           The Unit Performance button moves the

user to the Performance Data screen,
described in section 2.6.


---

            The Objective Data button is the gateway into BCTP objective data, and brings up the
Objective Data Control window, described in section 2.5.

The Unit Generated button opens the Unit-generated data window described in section 2.7.

            The Player Unit Profile button is intended to lead to screens depicting the make up of
participating units, by MOS, turbulence, TOE, etc. This capability has not yet been added to the
BCTPdb.

            The Battle Description button leads to a screen which more fully described the rotation
selected in the Investigation Set box. The Battle Description window is described in section 2.4.

The Close button takes the user back to the Rotation Selection window.

Battle Description (w_bdesc)

            The Battle Description screen allows the user to get additional descriptive information
concerning a specific rotation. The screen is shown as Figure 5 below.

             The WRS Journal button displays the Workstation Reporting System screen described in
section 2.4.1.

The Replay Demo button starts a demonstration application which recreates a WarFighter

replay using battle graphic snapshots, This

capability is available only for rotation              Battle Description for S4DHHAOT       vi =
93DHHR01.

             The Video Narrative button brings up the  |
portion of the video-taped AAR which gives an
overview of the WarFighter exercise. This              |
feature has not been implemented in the                |

current version.                                       |IL_
                                                       Figure 5 - Battle Description Screen

             The Text and Graphic Overview button
brings up relevant graphics and textual information which provide an overview of the WarFighter.
The Overview and Timeline buttons make use of the same results window, which is described
in section 2.4.1.

             The Timeline button brings up graphics and textual information to provide a timeline of
significant events for the selected WarFighter.

The Close button returns the user to the Information Control screen.


---

TimeLine/ Overview (w_desc)                                            SoS te TTT

            The Timeline/ Overview — screen
(Figure 6) displays the relevant information for
the option selected. Presented information
includes rotation ID, document type, sub-
document, section ID, start time, end time,
BOS, and record manipulation buttons to
scroll among the selected records.

                                                      Figure 6 - Timeline! Overview Display

Workstation Reporting System (w_wrs)

           The WRS Screen shows data from the BCTP Workstation Reporting System. A sample
screen is shown as Figure 7.

           BOS Selection is a drop down list box      [Fj              WHS Journal Entries for S3DHHAOI     SE
which allows the user to select a specific
                                                              sotecth                        1 oft       =
Battlefield Operating System (BOS) or
                                                       frettigence            El mono
functional area. The records displayed will
relate to the selected BOS.                             Bos:                            Date:
                                                        unt:                           rime: pore]
            Record manipulation buttons are used
                                                        Location. NA                 Workstation:
to step through the selected records one ata_
time, or to the first or last record.                 BDE TAC CP BROKE CONTACT WENT

                                                      |iiMiainssNoOr MOEN
                                                      WOLVINGTON. 979-5239. MSGRS.

            The Close Button returns the user to the
Battle Description screen.

                                                      Figure 7 - WRS Journal Entries


---

Objective Data Control (w_objtop)

The objective data control is the lead-in screen for all objective data displays. The user

must first select a single rotation and one side or the other. After these choices, the user may

select an objective data report from the drop-                         Objective Data
down list. Choices are:

Combat Battle Statistics,                                     ge

Battlefield Intelligence Collection Model,            Baa —h

Blue Air Activity,                                                                            OK

Opfor Air Defense,                                    (Roma Battle Statistics [=| Close

Artillery,                                                   mo

Destroyed Units, and

Blue Medical Units.

Selection of a report brings up a Figure 8 - Objective Data

specific screen with additional user options.
Individual screens are documented in sections 2.5.1-2.5.7.

            The screens share a similar user interface. When implemented, Review will allow on-screen
review of the data, Analyze will start a spreadsheet application with the data pre-loaded., and Close
will return to the Objective Data Control Screen.

None of the objective data reports is operational in the current implementation.

Combat Battle Statistics (w_cbstat)

            The combat battle statistics screen  [E]                   Combat Battie Statistics        [-[-

allows the user to examine casualty data from         % Al Causes                   Output Columns

any single cause or from all causes for a             Caused by...                  Alt

number of data elements.                                                               ® Unit Sustaining Casuatties

                                                      fartiery         6            & Equipment

                                                                    -               (% Number Hit

                                                                                    &® Number Wounded

                                                 | Review | [fAriatyze]| | Close |  % Number Killed

                                                 Figure 9 - Battle Statistics


---

Battlefield Intelligence Collection Model (w_bicm)

            The Battlefield Intelligence Collection  =|         Battlefield intelligence Collection Model  [=|
Model screen allows the user to review data
from the BCTP's BICM. The user may select            { All Detected Units            Output Columns
to review data for all detected unit types, or
any specific type.                                   [ANTITANK                [z|    i All

                                                                           :         ” F Detected Unit ID

                                                     | Rev| [Aine aiyw ze|| close |           — Detected Unit Type

                                                                                      i os Intel Asset Level

                                                                                         - f intel Asset Type

                                                                                     | I. intel Message Recipient

                                                     Figure 10 -intelligence

Blue Air Activity (w_bair)

           This screen allows the user to
 review outcomes of blue air missions.

                                                     —                     Blue Air

                                                         Output Columns              (< Location
                                                                                     (< Mission
                                                         Xx All
                                                                                     X Hits
                                                         < Time
                                                         XX Unit Name

                                                         K System

                                                         Review                       Close

                                                     L_.

                                                     Figure 11 - Blue Air Activity —


---

Opfor Air Defense (w_ada)

            The Opfor Air Defense Screen allows   |                         Red Alr Defense:                               [~]«
the user to review/ analyze the results of opfor
air defense missions for either automatic             & All Engagement Types        - Output Columns             §% Rpt_Fired
operation or self defense.                                                                                       & EOE Fired
                                                      Engagement Types        oy 8 PR AML.
                                                                                                                 & Destroyed
                                                        @ Automatic                     & Mission Name
                                                         C Seif Getense              ~—&R Unit                   K Damaged

                                                               ;                     f% Location

                                                  | Review || Anatyze || Close |  : i Weapon

                                                  Figure 12 - OPFOR Air Defense

Artillery (w_artill)

            The user may review the results of    =|                        Artillery Reports                                J+] l
artillery engagements for any _ single
ammunition type or for ail ammo types.                &R Any Ammo Type            Columns                        ® Rounds
                                                                                                                 & Impact Point
                                                      Select Ammo Type  [3    & Ali
                                                      [Conventional           K Mission Name                     & Unit Hit
                                                                                                                 B System Hit
                                                                               R unit
                                                                                                                 B® Number Hit
                                                                                                     & Location

                                                  [Review |[anatyze|[[ciosel | | & Weapon

                                                  Figure 13 - Artillery

Destroyed Units (w_dest)                          =                     Destroyed Units                                        [~]= |

            The destroyed unit screen displays        — All Workstation:                                          Columns
statistics about blue units.
                                                                                                                 i All
                                                      Workstation Types
                                                                                                                  & Location
                                                      [Maneuver                   [|
                                                                                                                  _& Threshhold
                                                  | Review | | Analyze | | [Ciose]
                                                                                                                    f Remainder

                                                                                                                  ‘K Time

                                                  Figure 14 - Destroyed Units


---

Blue Medical Units (w_medics)

            The Blue Medical Unit screen (Figure    —     Blue Medical Units                                    vi«
15) makes information concerning blue
medical units available to the user.

                                                          KAN                         f End Time © |

                                                          rd Start Time             — & Admitted

                                                          i Unitname                = Shifted

                                                          K Returned                   f Evacuated _

                                                             Died

                                                          Review | ||Analyze!|| Close

                                                    Figure 15 - Blue Medical Units

Performance Data (w_perf)

            The Unit Performance Data screen,       =     Unit Performance Data                                 {~|*
shown in Figure 16, is one of the key
components of the BCTPdb user interface. It         -BOS                            r~ Document/ Product
allows users to examine any combination of           [" Al BOSs                        " At
performance data across multiple BCTP
rotations. The range of rotations is controlled     _ & Maneuver                    — Final Exercise Report
by the Query Set on the Information Control
Screen (Section 2.3). Data are selected by              [" Fire Support                     K Overview
Battlefield Operating System (BOS), by                 ( Alr Defense                       { BOS Observations
specific document, by echelon, and by
combining keywords for which the content of           f Command/ Control                  TTM AARt Remarks
the products will be searched. Documents in
the selection set include products generated          [TM Intelligence                 othe Remarks
by the BCTP as well as outside analyses of
BCTP data, such as ACCES. Selected data                 [” Mobitity/ Survivability          T Notes
may be a mixture of textual, graphical, and
video.                                                m ess                               [f° Orders Crosswalk

             The Word/ Phrase search capability is   Word/ Phrase Search —               [AAR Video
not operational in the current implementation.
                                                        @ Exclusive (AND)                   I” ACCES (C2)

                                                         (: Inclusive (OR)          r~ Echelon   [EAC    [7 Corps
                                                                                          r All  ([ BOE  |" BN
                                                     f
                                                     [                                     OV

                                                       |                            | {OK | | Close

                                                    Figure 16 - Unit Performance Data


---

Data Display (w_d2)                                               VERVIEW

            The Data Display screen shown in                          TSI
Figure 17 is used for both the Unit
Performance Data as well as Unit-Generated           2)O Rest3a 5thtIe D{(d M). D-Day, H-Houthre, 35th |D(M) axivanncoertsh from
data (Section 2.7). It contains the same data
as the Timeline/ Overview screen discussed in        ‘Stone to prepare defensive pesilions and defend in sector to destroy elements of
Section 2.4.1.
                                                        fh CAA. On order, the division attacks north to fix the lead division of the 11th
            The capability to review video clips is
not operational in the current implementation.       A                              :

                                                     Figure 17 - Performance Data Display

Unit-Generated Data (w_unit)

            The Unit-Generated Screen allows the     |                                 Unit Generated Data                                              [-[+
users to select documents generated by
participating units over multiple rotations. The     --BOS —_——_—_—_—_—.__— Section                                                        Echelon —
range of rotations is controlled by the Query                                                                                                  All
Set on the Information Control Screen                   r All Boss                     T all                                                      EAC
(Section 2.3). Data are selected by Battlefield
Operating System (BOS), by _ specific                     BK Maneuver                     [~ Plans/Orders                                    F Corps —
document, by echelon, and by combining
keywords for which the content of the                     7 Fire Support                 — FRAGOs                                           rey
products will be searched. Documents in the
selection set may include Op Orders, Fragos,             I” Air Defense                 a Se                                                 r BN
Reports, Requests, and FSOPs.
                                                         [7 Commands Control                 ep

                                                          T intetggence                - [7 Requests

                                                           ( Mobility Survivabifty

                                                           r css                       Si

                                                     rWord/ Phrase Search

                                                        @ Exclusive (AND)           C: Inclusive {OR}

                                                        !                                  |

                                                        1                                  |

                                                                           | ox }                      [close |

            The Word/ Phrase search capability is    Figure 18 - Unit Generated Data
not operational in the current implementation.


---

Rotational Information (w_rotin)

             Basic information about any rotation      [= [Rotational information         [~ =]
may be reviewed from the Information Control
Screen (Section 2.3) by selecting a single             Rotation Code:   93DLHA01
rotation in the Investigation Set and clicking
on the Rotational Information button. The              Rotation Id:     93-8
information displayed is shown in Figure 19.
                                                       Unit Identification: 6ID(L)

                                                       Rotation Start:  7I5893 00:00:00

                                                       Rotation End:    7/10/93 00:00:00

                                                       Rotation Location: Korea

                                                       Component:
                                                       Had Restart:

                                                   Figure 19 - Rotational Information

                                                   11


---

Limitations of the Current Implementation

            The current implementation of the BCTPdb PowerBuilderis incompletein several respects
for the following reasons:

1.  The speed of commercial telephone lines is too slow to provide practical database

    access, particularly when significant amounts of data must be retrieved. Telephone

    access is acceptable for applications when a small amount of data is returned, no

    matter how complicated the underlying query. An application such as the BCTPdb

    requires, by its very nature, that a large amount of data be returned to the user.

    For the BCTPdb application, for example, performance is acceptable when

    accessing the ROTATION table, but degrades when trying to use the DATA table(s)

    or any of the objective data tables. Current capability to use graphics is tortuously

    slow, and the ability to handle video is essentially non-existent.

    The nature of the PowerBuilder/INFORMIX combination is restrictive. The earlier
    FoxPro generation of the BCTPdb contained essentially limitless blocks of text in
    memo fields, which are not supported by INFORMIX. Word search capabilities were
    well supported within memo fields. INFORMIX does support binary data types of
    unrestricted length, but Implementing the word/phrase search for those data types
    would require specialized coding. Likewise, the transfer of data from FoxPro to
    INFORMIX forced some accommodations.

    INFORMIX does not easily facilitate bulk transfer of data to other forms. In the
    FoxPro implementation, transfer of table data into a spreadsheet was
    straightforward, primarily because the spreadsheet could directly read the .DBF
    table data. This is not true with the INFORMIX tables. While the INFORMIX SELECT
    statement is capable of converting data, making the jump from table data to a
    spreadsheet-compatible form would require extensive coding.

Test and Development Environment

            Testing of the current BCTPdb version was limited to use of a local, wATCOM Iv database
which is identical in format and contents to the INFORMIX database on the Leavenworth DOIM HP
server. Differences in syntax between WATCOM and INFORMIX were not investigated. Testing was
accomplished over a Novell 4.1 network, with graphics storage mapped to the F: drive. The replay
capability was revised to run from the F: drive as well.

                                           12


---

List of Current Limitations

a.   The word/phrase search capabilities for the Unit Performance Data and Unit-Generated

     Data Screens have not been implemented.

b.   None of the objective data screens have been implemented.

Cc.  The Trends button has not been implemented.

d.   The Good Ideas button has not been implemented.

e.   Within the data screens, the video capability is not implemented.

f.   in order to transfer the data, some of the memo fields in the data table were truncated to

     match INFORMIX CHAR data type limits.

Deliverable Files            Description                                In Screen ...

Contents of diskette:        diskette subdirectory

Name of file/ directory      File - PowerBuilder Screens and source code
PB4
                             File - Initialization File
         BCDB.PBL
                             diskette subdirectory
        BCDB_W.INI
         BCDB                Bitmap file ' Good Ideas' icon             Main Screen

             GI.BMP          Bitmap file ' Research’ icon               Main Screen
            RESEARCH.BMP
             TRENDS.BMP      Bitmap file ' Trends’ icon                 Main Screen
           WARNING.BMP
           CAMCORD.BMP       Bitmap file ' Warning’                     Main Screen
           FIRST1.BMP
                             Bitmap file ' Graphic’ icon                Data Display
           LAST1.BMP
                             Bitmap file record manipulation icon       Data Display
             NEXT1.BMP
             PRIOR1.BMP      Bitmap file record manipulation icon       Data Display

                             Bitmap file record manipulation icon       Data Display

                             Bitmap file record manipulation icon       Data Display

                                            13


---

                                                                                                   Contract #: MDA 903-92-D-0075
                                                                                                   Deliverable #: 0036-01-0036AH
                                                                                                                                 November 1, 1995

Addendum to Data Directory

                                      Jack A. Briscoe
                                    BDM Federal, Inc.
     Submitted by: Mr. Michael R. McCluskey, Acting Chief
                  Unit-Collective Training Research Unit
                        and Dr. Zita M. Simutis, Director
                Personnel and Training Research Division
    Dr. Stanley Halpin, Contracting Officer’s Representative

                                    November 30, 1995
                           U.S. Army Research Institute


---

LIST OF TABLES

Table 1.0 ROTATION - Summary rotation information ................... 2

Table 2.0 SUST- Sustain Comments ........0. 00.0..e . ee. e e0 e ee.e 2

Table 3.0 OBJTREND - Objective trends............0.s .e.ee..e0 tee.s 2

Table 4.0 REPORTS - Reports table is used internally by BCdb code........ 2

Table 5.0 BOB - Blueprint of the Battlefield Reference ................... 3

Table 6.0 GI- Good Ideas ....... 2.0... ccc et  eee eee 3

Table 7.0 TAAR-AAR Trends .... 00. 00s . cec. e e. e e. ee . ee. ns 3

Table 8.0 TFER-FER Trends .... 0.2. ... . 2 eee. c e. ee.e. ee. nes 4

Table 9.0 B_ARTILL - Blue Combat Artillery Missions ................... 4

Table 10.0 B_ATTRIT - Blue Combat Attrition. ... 0.2. ... c. ee e. ee e. ee 5

Table 11.0 B_MED - Blue Medical Report ............ eeee ee nee 5

Table 12.0 B_AIR - Blue Army Aviation Report .............ee.e.e0 ee 5

Table 13.0 CBSTAT - Combat Damage Report ......... 02..ee.e . ee.e 6

Table 14.0 DATA_INDEX - Textual, Video, Graphics Index Information .....we. 6

Table 15.0 DATA_CONTENTS - Textual, Video, Graphics ................. 6

Table 16.0 INTEL - Intel Reports ........ 20... ceceee e eee 7

Table 17.0 R_ADARPT Red Air Defense Report........0.2.0...a.e-e 8

Table 18.0 R_ARTILL - Red Combat Artillery Missions .................... 8

Table 19.0 WIPE_OUT - Destroyed Unit Report.0 .......0.0.. e.e.e .ee.e 9

Table 20.0 WRS - Workstation Reporting System ..................-.0-. 9


---

BCTPdb Contents

The table below reflects the current contents of the BCDB INFORMIX data base.

The primary format changes involved changing MEMO-type fields to either VARCHAR

or CHAR data types.              .

   Table Name        Records  Problems/Comments/Format Changes

| ROTATION             6      OK

  SUST                  90    OK
  OBJTREND               8    OK
  REPORTS                7    OK
  BOB                  267    OK
  GI                      1   MEMO-type DATA field was changed to CHARACTER*10000
  TAAR                 294    OK
  TFER                1076    OK
  B_ARTILL            6339    OK
  B_ATTRIT           14735    OK
  B_MED                607    OK
  B_AIR               2082    Name changed from BLUE_AIR
  CBSTAT             17709    OK
  DATA_INDEX          2357    Derived from DATA table.
  DATA_CONTENTS       2357    Derived from DATA table.
  INTEL               2239    Subset of original 87430 records - includes only

  R_ADARPT            2178    DETECTED_UNIT_TYPE=ENGR
  R_ARTILL            4538
                              OK
  WIPE_OUT            2039    Subset of original 17772 records - includes only
 WRS                   591    NUMBER_HIT>0
                              OK
                              Memo field COMMENTS changed to CHAR*5000

                              1


---

1.0 Table ROTATION - Summary rotation information

Field   Field Name                     Type        Width

  1    ROTATION_INDEX                  INTEGER        4
  2    ROTATION_CODE                   VARCHAR       10
  3    ROTATION_ID                     VARCHAR        10
  4    UNIT_IDENTIFICATION             VARCHAR       20
  5    ROTATION_START                  DATE           8
  6    ROTATION_END                    DATE           8
  7    ROTATION_LOCATION               VARCHAR       20
  8    BCTP_TEAM                       VARCHAR       10
  9    COMPONENT                       VARCHAR        10
 10    UNIT_TYPE                       VARCHAR       11
 11    HAD_RESTART                     CHAR           1

2.0 Table SUST - Sustain Comments

Field   Field Name                     Type        Width
   1   BOB_REFERENCE                   VARCHAR        3
  2    SUSTAIN                         VARCHAR       30

3.0 Table OBJTREND - Objective trends

Field   Field Name                     Type        Width
   1   OBJECTIVE_TREND                 VARCHAR       50
  2    FILE_NAME                       VARCHAR        10
  3    BOS                             VARCHAR        12
  4    BOS_NUMBER                      DOUBLE

4.0 Table REPORTS - Reports table is used internally by BCdh code

Field   Field Name                     Type        Width
   1   REPORT_NAME                     VARCHAR       20
  2    TABLE_NAME                      VARCHAR        10
  3    REPORT_ENABLED                  DOUBLE


---

5.0 Table BOB - Blueprint of the Battlefield Reference

Field   Field Name           Type                       Width
   1   BOB_REFERENCE         VARCHAR                       13
  2    BOB_ DESCRIPTION      VARCHAR                      60

6.0 Table GI - Good Ideas

Field   Field Name           Type                       Width
  1    ROTATION_INDEX        INTEGER
  2    TYPE_OF_DATA          VARCHAR                      20
  3    DATA_NAME             VARCHAR                      45
  4    DATA_SOURCE           VARCHAR                       15
  5    SIDE                  VARCHAR                        1
  6    MEDIUM                VARCHAR                       10
  7    FILENAME              VARCHAR
  8    ORDER                 INTEGER                      35
  9    ORGANIZATION          VARCHAR
  10   TIME_SENT             VARCHAR                       3
  11   TIME_RECEIVED         VARCHAR                      15
  12   BOB_REFERENCE         VARCHAR
  13   DATA                  Memo                          12
                                                           12
                                                          30
                                                           10

7.0 Table TAAR - AAR Trends

Field   Field Name           Type                       Width
   1   ROTATION_INDEX        INTEGER
  2    BOB_REFERENCE         VARCHAR                        3

  3    SUSTAIN               VARCHAR                      30

  4    IMPROVE               VARCHAR                       30


---

8.0 Tabie TFER - FER Trends

Field  Field Name            Type                      Width
  1    ROTATION_INDEX        INTEGER
  2    BOB_REFERENCE         VARCHAR                       3
  3    EVALUATION            VARCHAR                       1

9.0 Table BARTILL - Blue Combat Artillery Missions

Field  Field Name            Type                      Width
  1    ROTATION_INDEX        INTEGER
  2    MISSION               VARCHAR                      10
  3    MISSION_TYPE          VARCHAR
  4    TIME                  VARCHAR                      6
  5    UNIT                  VARCHAR                      6
  6    LOCATION              VARCHAR                     15
  7    WEAPON                VARCHAR                     12
  8    AMMUNITION_TYPE       VARCHAR                     15
  9    ROUNDS                INTEGER                      9
 10    MPOI                  VARCHAR
  11   UNIT_HIT              VARCHAR                     11
 12    SYSTEM_HIT            VARCHAR                     20
 13    NUMBER_HIT            INTEGER                      15

                                                    4


---

10.0 Table B_ATTRIT - Blue Combat Attrition

Field   Field Name                            Type     Width
   1   ROTATION_INDEX                         INTEGER
   2   TIME_START                             VARCHAR     6
   3   TIME_END                               VARCHAR     6
  4    UNIT                                   VARCHAR     15
  5    EQUIPMENT                              VARCHAR    20
  6    DESTROYED                              INTEGER
  7    DAMAGED                                INTEGER

11.0 Table BMED - Blue Medical Report

Field   Field Name                           Type      Width
   1   ROTATION_INDEX                        INTEGER
  2    START_TIME                            VARCHAR      6
  3    END_TIME                              VARCHAR      6
 ‘4    UNIT                                  VARCHAR     15

  5    ADMITTED                              INTEGER

  6    RETURNED                              INTEGER
  7    SHIFTED                               INTEGER
  8    DIED                                  INTEGER
  9    EVACUATED                             INTEGER

12.0 Table B_AIR - Blue Army Aviation Report

Field   Field Name                           Type      Width

  4    ROTATION_INDEX                        INTEGER     20
  2    MISSION_NAME                          VARCHAR      6
                                                          12
   3   TIME                                  VARCHAR      15
  4    LOCATION                              VARCHAR      15
  5    UNIT                                  VARCHAR
  6    SYSTEM                                VARCHAR
  7    HITS                                  DOUBLE

                                              5


---

13.0 Table CBSTAT - Combat Damage Report

Field   Field Name                        Type                      Width

  1    ROTATION_INDEX                     INTEGER                      6
                                                                        1
  2    STATISTICS_TIME                    VARCHAR                      15
  3    SIDE                               VARCHAR                      15
  4    UNIT                               VARCHAR                      15
  5    EQUIPMENT                          VARCHAR
  6    CAUSE                              VARCHAR
  7    NUMBER_HIT                         INTEGER
  8    NUMBER_WOUNDED                     INTEGER

  9    NUMBER_KILLED                      INTEGER

14.0 Table DATA_INDEX - Textual, Video, Graphics Index Information

Field   Field Name       Type                        Width
   1   ROTATION_INDEX    INTEGER
  2    SUB_DOCUMENT      VARCHAR                       20

  3    SECTION_TITLE     VARCHAR                       45
  4    DOCUMENT_TYPE     VARCHAR                       15

  5    SIDE              VARCHAR                         1
  6    MEDIUM            VARCHAR                        10
  7    REC_ORDER         INTEGER
                                                       15
  8    ORGANIZATION      VARCHAR
                                                       30
  9    ANALYSTS_ EVAL    INTEGER                         5
  10   BOB_REFERENCE     VARCHAR                        3
  11   SECTION_ID        VARCHAR
  12   DOCUMENT_NUMBER   VARCHAR

15.0 Table DATA CONTENTS - Textual, Video, Graphics

Field   Field Name       Type                        Width
  1    FILE_NAME         VARCHAR                       35
  2    DESTINATION       VARCHAR                        16
  3    TIME_SENT         VARCHAR                        12
  4    TIME_RECEIVED     VARCHAR                        12
  5    OPNL_ TIME_FRAME  VARCHAR                        15

  6    OPTYPE            VARCHAR                       30
  7    ANALYSTS_ EVAL    INTEGER
                                                     15000
  8    TEXT_DATA         CHAR


---

16.0 Table INTEL - Intel Reports

Field   Field_Name                    Type  Width
  1    ROTATION_INDEX             INTEGER
  2    SIDE                       VARCHAR      1
  3    DETECTED_UNIT              VARCHAR     10
  4    DETECTED_UNIT_TYPE         VARCHAR     10
  5    DETECTION_TIME             VARCHAR      6
  6    ASSET_LEVEL                VARCHAR      2
  7    ASSET_TYPE                 VARCHAR      1
  8    RECIPIENT                  VARCHAR     10
  9    PERCEPTION                 VARCHAR     10
 10    LOCATION                   VARCHAR     11
 11    ACTIVITY                   VARCHAR     10
  12   ORIENTATION                VARCHAR      2
  13   PARENT                     VARCHAR     12


---

17.0 Table R_ADARPT Red Air Defense Report

Field   Field Name                          Type        Width
  1    ROTATION_INDEX                       INTEGER
  2    TIME                                 VARCHAR        6
  3    AIRCRAFT                             VARCHAR        9
  4    MISSION                              VARCHAR       15
  5    UNIT                                 VARCHAR       15
  6    WEAPON                               VARCHAR       15
  7    LOCATION                             VARCHAR       12
  8    ENGAGEMENT_ TYPE                     VARCHAR       12
  9    REPORTED _FIRED                      INTEGER
  10   EOE_FIRED                            INTEGER
  11   DESTROYED                            INTEGER
  12   DAMAGED                              INTEGER

18.0 Table R_ARTILL - Red Combat Artillery Missions

Field   Field Name                          Type        Width
  1    ROTATION_INDEX
  2    MISSION                              INTEGER       10
  3    MTYPE                                VARCHAR        6
  4    TIME                                 VARCHAR        6
  5    UNIT                                 VARCHAR       15
  6    LOCATION                             VARCHAR        12
  7    WEAPON                               VARCHAR       15
  8    AMMUNITION_TYPE                      VARCHAR        9
  9    ROUNDS                               VARCHAR
  10   MPO!                                 INTEGER       11
  11   UNIT_HIT                             VARCHAR       20
  12   SYSTEM_HIT                           VARCHAR       15
  13   NUMBER_HIT                           VARCHAR
                                            INTEGER

                                                     8


---

19.0 Table WIPE OUT - Destroyed Unit Report

Field   Field Name                             Type     Width
  1    ROTATION_INDEX                          INTEGER
                                                          15
  2    UNIT ©                                  VARCHAR
                                                          10
  3    STATION                                 VARCHAR     6
  4    TIME                                    VARCHAR     12
  5    LOCATION                                VARCHAR
  6    THRESHHOLD                              DOUBLE
   7   REMAINDER                               DOUBLE

20.0 Table WRS - Workstation Reporting System

Field   Field Name     Type                             Width

  1    ROTATION_INDEX  INTEGER                             4

  2    BOS             VARCHAR                            20
  3    UNIT            VARCHAR                             10
  4    LOCATION        VARCHAR                            25
  5    DATE            DATE
  6    TIME            VARCHAR                              5

  7    WORKSTATION     VARCHAR                             7

  8    COMMENTS        CHAR                             5000


---

                                                                                            Contract #: MDA 903-92-D-0075
                                                                                               Deliverable #: 0036-01-0036AJ
                                                                                                                             November 1, 1995

Addendum to Loading Guide

                                        W. E. Walsh
                                    BDM Federal, Inc.
     Submitted by: Mr. Michael R. McCluskey, Acting Chief
                  Unit-Collective Training Research Unit
                        and Dr. Zita M. Simutis, Director
                Personnel and Training Research Division
    Dr. Stanley Halpin, Contracting Officer’s Representative

                                    November 30, 1995
                           U. S. Army Research Institute


---

                                         ADDENDUM TO THE LOADING GUIDE

                                                                INTRODUCTION

            The need to improve command and control functioning, particularly at echelons above
brigade, is a recognized concern of long standing within the Army. The BCTP is a training
initiative that applies computer technology as a tool to train the war planning, war fighting and
decision making skills at the division and corps levels. The BCTP Relational Database was
designed to increase the accessibility and utility of data derived from BCTP WarFighter
Exercises. The BCTP Database has the potential to provide a rich source of information for
studying both short and long term Army higher-echelon command and control issues.

           The Prototype BCTP Database was implemented initially as a FoxPro stand-alone
application to run within the Microsoft Windows 3.1 environment on any IBM compatible 386 or
486 computer. The BCTP FoxPro application works in conjunction with several commercial off-
the-shelf software packages, e.g. Quattro Pro, PaintShop Pro, and the Windows Notepad.
Supporting documents for the source code files, User's Guide, Data Dictionary, and Loading
Procedures Guide exist for the prototype development environment (FoxPro stand-alone).

           The current stage in the evolution of the BCTP Database involves the transfer of the
BCTP Database from a FoxPro stand-alone environment to a client/server configuration on a
UNIX server within the Combat Training Center (CTC) Warrior Information Network (WIN)
Database at Ft. Leavenworth. When the BCTP database is incorporated into the CTC WIN
Database, the BCTP Database will possess an Informix back-end to support the BCTP database
table structure and a PowerBuilder front-end to provide access to BCTP and CTC data. The
integration of the Prototype BCTP Database into the CTC WIN environment will result in
significant modifications to the database tables, the BCTP source code files, and the supporting
documentation. These software changes and their impacts upon the table structure, user
guidelines, and loading procedures for the BCTP Database will be reflected in the addenda to the
BCTP Data Dictionary, User's Guide, and Loading Procedures Guide.

            The purpose of the original Loading Procedures Guide (LPG) for the BCTP Database is
to provide data loaders and analysts with a system reference for loading a relational database
within the prototype development environment (FoxPro stand-alone). The LPG provides
detailed descriptions of the methods and procedures which are required to perform relational
database loading tasks. In addition, the BCTP LPG provides basic information about the
database and the data which are entered into the database.

            The purpose of this addendum to the Loading Procedures Guide is to identify the
components of the original LPG which will require modification as a result of the conversion and
transfer of the BCTP database to a client/server environment at Ft. Leavenworth, Kansas.


---

                         MODIFICATIONS TO THE LOADING PROCEDURES GUIDE

Section 1. Introduction

                  a. Application software components of the BCTP Loading System

                       The loading system that will be employed with the HP Server at Ft.
                        Leavenworth will not use Microsoft FoxPro. All references to FoxPro icons,
                       command windows, and dialog windows are to be deleted. Populating the
                       Informix tables can be accomplished interactively INSERT statements to DB-
                       Access or INFORMIX-SQL), through an application program (in INFORMIX-
                        4GL or another language), or through the conversion of the source data into a flat
                       ASCII file. See page 9-29 of the Informix Guide to SQL, dated December 1991.

                 b. References to the host hardware configuration for the BCTP Database

                       The description of the hardware configuration must be expanded to include the
                        HP network server at Ft. Leavenworth.

                 c. Categories of BCTP data files

                       BCTP database files are now designed to work with Informix SQL and the
                        Database Server software which are identified on pages 1-16 and 1-17 of the
                        Informix Guide to SQL, dated December 1991.

Section 2. Guided Tour

                 a. References to and discussion of the Loading Application software (MS FoxPro)

                        Replace references to MS FoxPro with Informix SQL.

                 b. References to and discussion of the Database User Application Software
                        (MS FoxPro)

                        Replace references to MS FoxPro with Informix SQL.

Section 3. Pre-processing Procedures

                  a. Video tape preparation - UNKNOWN

                 b. Preparation of data tapes with objective data


---

1. Retrieval of the data from its source

BCTP objective data are generated either on a SUN minicomputer or
 on the VAX which hosts the CBS model. The data must first be read - from
tape (SUN cartridge or VAX reel) into a host computer compatible with its
 original computer. Then the data must be transferred to a PC to transform the
 original data from its native format into a format which will facilitate its
 conversion into an Informix table.

2. Conversion tools for objective data

When the source of the data is not compatible with Informix, you must find a

way to convert it into a flat ASCII file; that is, a file of printable data in which

each line represents the contents of one table row.                   .

C. Procedures for saving text and graphics files - UNKNOWN

d. Creation of rotational data tables

The rotational data tables will be created using Informix application software.
Informix requires the appending of records rather than the creation of new tables
for each rotation.

References to FoxPro application software

Replace references to FoxPro application software with Informix-SQL.

Section 4. Loading Process for Rotational Data Tables

a. Procedures for scanned documents - file locations

Replace references to FoxPro start-up screen with PowerBuilder interface screen.
The procedures for loading scanned documents within an Informix
environment are the same as the procedures employed in the FoxPro database.

Procedures for digital data

When the data source is not compatible with Informix, the source file must be
converted into a flat ASCII file - a file of printable data in which each line
represents the contents of one table row. The conversion process will depend on
the type of source file.

c. References to FoxPro start-up screen

                                       3


---

                       Delete all references to FoxPro application software.
Section 5. Loading Process for Good Ideas and Trend Tables

                 References to FoxPro start-up screen
                Delete all references to FoxPro application software.
Section 6. References
                a. Add Informix User's Guide, December 1991.
                b. Add Addendum to the BCTPdb Data Dictionary
                c. Add BCTPdb Converted Data Structures (FoxPro to Informix)
                 d. Add Addendum to the BCTPdb User's Guide
                 e. Add BCTPdb PowerBuilder Graphical User Interface
                 f. Add Informix Guide to SQL, Tutorial, December 1991.
                 g. Add Informix Guide to SQL, Reference, December 1991.
                 h. Add Informix-OnLine Administrator's Guide, December 1991.
                 I. Add Informix-OnLine Conversion Guide, Version 5.1, December 1991.
                 j. Add Informix Error Messages, Version 7.1.
Appendices.
                 Appendix A - Setting Preferences

                        Delete references to FoxPro
                 Appendix B - Standard Loading Conventions

                       Delete references to individual FoxPro tables


---

                  Appendix C - Trouble-shooting

                        Address and telephone number of ARI-DoD Center point of contact

                        BDM Federal, Inc.
                        Attn: Bill Walsh or Jack Briscoe
                         DoD Center Monterey Bay
                        400 Gigling Road
                        Seaside, CA 93955-6771
                        (408) 393-8851

                  Appendix D - Data Types and Media

                       No Change

                  Appendix E - Archive Reference ID Codes

                        No Change

Glossary - No Change
Figures

                  a. Add Dialer Icon
                  b. Delete FoxPro 2.6 Icon

                  c. Modify Command Window Figure - replace FoxPro with Informix

                  d. Modify Open Dialog Window Figure - replace FoxPro with Informix


---

                                                                                                             Contract #: MDA 903-92-D-0075
                                                                                                           Deliverable #: 0036-01-0036AK
                                                                                                                                      November 1, 1995

Addendum to the User’s Guide

                                            W. E. Walsh
                                      BDM Federal, Inc.
       Submitted by: Mr. Michael R. McCluskey, Acting Chief
                      Unit-Collective Training Research Unit
                          and Dr. Zita M. Simutis, Director
                   Personnel and Training Research Division
       Dr. Stanley Halpin, Contracting Officer’s Representative

                                     November 30, 1995
                            U. S. Army Research Institute


---

                                              ADDENDUM TO THE USER'S GUIDE

                                                                INTRODUCTION

           The need to improve command and control functioning, particularly at echelons above
brigade, is a recognized concern of long standing within the Army. The BCTP is a training
initiative that applies computer technology as a tool to train the war planning, war fighting and
decision making skills at the division and corps levels. The BCTP Relational Database was
designed to increase the accessibility and utility of data derived from BCTP WarFighter
Exercises. The BCTP Database has the potential to provide a rich source of information for
studying both short and long term Army higher-echelon command and control issues.

           The Prototype BCTP Database was implemented initially as a FoxPro stand-alone
application to run within the Microsoft Windows 3.1 environment on any IBM compatible 386 or
486 computer. The BCTP FoxPro application works in conjunction with several commercial off-
the-shelf software packages, e.g. Quattro Pro, PaintShop Pro, and the Windows Notepad.
Supporting documents for the source code files, User's Guide, Data Dictionary, and Loading
Procedures Guide exist for the prototype development environment (FoxPro stand-alone).

           The current stage in the evolution of the BCTP Database involves the transfer of the
BCTP Database from a FoxPro stand-alone environment to a client/server configuration on a
UNIX server within the Combat Training Center (CTC) Warrior Information Network (WIN)
Database at Ft. Leavenworth. When the BCTP database is incorporated into the CTC WIN
Database, the BCTP Database will possess an Informix back-end to support the BCTP database
table structure and a PowerBuilder front-end to provide access to BCTP and CTC data. The
integration of the Prototype BCTP Database into the CTC WIN environment will result in
significant modifications to the database tables, the BCTP source code files, and the supporting
documentation. These software changes and their impacts upon the table structure, user
guidelines, and loading procedures for the BCTP Database will be reflected in the addenda to the
BCTP Data Dictionary, User's Guide, and Loading Procedures Guide.

           The purpose of the original User's Guide for the BCTP Database is to provide analysts
and researchers with a system reference for accessing the BCTP database within the prototype
development environment (FoxPro stand-alone). The User's Guide provides basic information
about the database and the BCTP data elements. In addition, the User's Guide contains methods
which researchers may use to analyze data derived from BCTP Warfighter Exercises.

           The purpose of this addendum to the User's Guide is to identify the components of the
original User's Guide which will require modification as a result of the conversion and transfer of
the BCTP database to a client/server environment at Ft. Leavenworth, Kansas.


---

                                          MODIFICATIONS TO THE USER'S GUIDE
 Section 1. Introduction

                    a. Components of the BCTP database system
                         The BCTP database system will now include the HP server at Ft. Leavenworth,
                        Informix application software, and PowerBuilder application software.

             b. References to the FoxPro application software

                         Include references to PowerBuilder as the new application software for the user
                        interface.
 Section 2. Guided Tour
                   a. Start up instructions will include procedures for connecting to the DOIM server
                          UNKNOWN
                   b. References to and discussion of the Database User Application Software
                          (MS FoxPro)
                         Include references to PowerBuilder as the new application software for the user
                         interface,
Section 3. Research Tools and Techniques Illustrated
                   a. Viewing graphics with Paint Shop Pro application software - UNKNOWN
                   b. Procedures for viewing video within the BCTP database - UNKNOWN
                   c. References to FoxPro application software
                         Include references to PowerBuilder as the new application software for the user
                        interface.
Appendices.
             Appendix A - References


---

                 a. Add Informix User's Guide
                b. Add addendum to the BCTPdb Data Dictionary
                 c. Add BCTPdb Converted Data Structures (FoxPro to Informix)
                d. Add addendum to the Loading Procedures Guide for the BCTP database
                 e. Add BCTPdb PowerBuilder Graphical User Interface
                 f. Add Informix Guide to SQL, Tutorial, December 1991.
                 g. Add Informix Guide to SQL, Reference, December 1991.
                h. Add Informix-OnLine Administrator's Guide, December 1991.
                 I. Add Informix-OnLine Conversion Guide, Version 5.1, December 1991.
                 j. Add Informix Error Messages, Version 7.1, December 1991.
           Appendix B - Trouble-shooting

                      Address and telephone number of ARI-DoD Center point of contact
                        BDM Federal, Inc.
                        Attn: Bill Walsh or Jack Briscoe
                        DoD Center Monterey Bay
                        400 Gigling Road
                        Seaside, CA 93955-6771
                         (408) 393-8851
           Appendix C - BCTP db Data Types and Media
                       No Change
           Appendix D - BCTP db Search Logic
                       No Change
Glossary - No Change


---

                                                                                                                                CONTRACT #: MDA 903-92-D-0075
                                                                                                                                  DELIVERABLE #: 0018-0018AH
                                                                                                                                                 OCTOBER 29, 1994

   FINAL DATA DICTIONARY:
BCTP PROTOTYPE DATABASE

                                   Jack A. Briscoe
                                  BDM Federal, ne.

Submitted by: Mr. Michael R. McCluskey, Acting Chief
               Unit-Collective Training Research Unit
                            and Jack Hiller, Director
                        Training Research Laboratory

Dr. Stanley Halpin, Contracting Officer's Representative

                                                                   o

            CA} 1 AS

                  AMY Reo rah nS HITUTE

                               November 1, 1994
                        U.S. Army Research Institute


---

            FINAL DATA DICTIONARY:
         BCTP PROTOTYPE DATABASE

                                                                Page

J. Physical Structure... ce eee ete ee eee nn nas 1

II. Relating BCTP Prototype Database Tables ....0. .00. 00. . c. ec . e.e. ee 2

III. BCTP Prototype Table Documentation ..........0. 0.0000...  e eee ees 2

                    LIST OF TABLES

1. ROTATION.DBF «0 ccc ce. eee . e eee n. teen nes 4
2. REPORTS.DBF ... 1... cce e ec cee eee eee e nee eae 6
3. OBJTREND.DBF .. 1... ete ee eee eens 7
3a. BOS/BOSNO 2.06. eee eee eee eee eee ees 7
4.GLDBF «0... cecee been nee enenes 8

5. TFER.DBF . 0. ee e. ee eee. cece eens 11

6. TAAR.DBF 1. ccc e. eeeee. eee e ee eees 12

7. BOB.DBF 2... ee  ce tenet eee ence eee enees 13

8. DATA 2...        ee eee eee eee eee eee eee 14

9. RLADARPT ... 0. ce . eee ee ee. e e cena ene 22

10. BLUE_AIR 2.0... ee eee eee e ena 24

11. BLARTILL 2...   ce eee eet enas 26

12, BLMED ..... eeeee e cette eee eens 29

13. BLATTRIT 2... cc eee eee eee eee e eee neee 31

14. CBSTAT 2...     eee eee cece eee e nee n eens 33

15. RLARTILL 2... eee eee e ee eee eens 35

16. WIPE_OUT 2...   ce              eee eee ee ee eee ees 38

1 OS 0)                                                         dene eeee 40


---

BCTP PROTOTYPE DATABASE
           DATA DICTIONARY

I. PHYSICAL STRUCTURE

            The BCTP Prototype Database is organized as a collection of related FoxPro/
Windows tables. The data may be stored either locally on a user's DOS/Windows 3.1
compatible computer, or in a Windows-compatible network in a read-only configuration.

Numeric and fixed-length character data are stored in Dbase-like files with an

extension of DBF. Indeterminate-length text data are stored in memo records, which are

written to files with an extension of FPT.

The current sizes of both the .DBF and .FPT

files are documented in this report.          Directory Structure    Tables

           The BCTP Prototype Database Data   CABCDB                 ROTATION

Dictionary is organized by the individual                            BE TREND

FoxPro tables which, in concert with the      C:\BCDB\SUPPORT        BOB

user interface, comprise the BCTP Prototype                          Gl

Database. Tables are stored in three levels                          TAAR

of the file hierarchy as shown in Figure 1.                          TFER

The root BCDB directory contains three        C:ABCDB\(Rotation ID)  Rotation- specific

tables used to control program capabilities.                         Tables

The ROTATION table contains summary

information pertaining to each rotation for   Figure 1

which specific information is stored in the

rotation-specific tables. The REPORTS table

carries information about which objective tables are available, and the OBJTREND table

contains the spreadsheet names for the objective trend displays. The tables in the

C:\BCDB\SUPPORT subdirectory contain either reference data, as in the BOB (Blueprint of

the Battlefield) table, or aggregated data which apply to entire set of BCTP data. The GI

(Good Ideas) table includes analysts’ suggestions on ways to improve the BCTP experience

-either in terms of training or data collection. The trends tables TAAR and TFER contain

summary trend data aggregated from all the component rotation data. Rotation-specific tables,

located in the C:\BCDB\(Rotation ID) subdirectory, contain data specific to individual BCTP

rotations and are maintained in separate subdirectories.

            The data dictionary contains a summary of all tables which have been created, and
provides information concerning data element names and types, number of records per
rotation, and gross size, and element descriptions. The Data table also contains references to
external graphics files. The total number of external files referenced is shown. The separate


---

sections for each table are designed to be replaced as the prototype evolves over time into an
operational product. Note that the sizes given are as of 10/1/94, and are subject to change as
development and database loading activities continue.

                             Il. RELATING BCTP PROTOTYPE DATABASE TABLES

            The BCTP Database is a relational database and different BCTP Prototype Database
tables may be related by matching identical or similar values in fields in the different tables.
The table below reflects the fields which are most likely to be used in matching different
tables. It is not necessary for fields in different tables to have identical names; the contents
are matched. In cases where the SIDE field is enclosed in parentheses, the SIDE is
determined by the name of the table, e.g. RLADARPT.

 Field Type  UNIT      TIME          LOCATION  SIDE   WEAPON
Table Name
             ORG,      TIMESENT                SIDE      WEAPON
DATA                                                     SYSTEM
             DESTINATIO | TIMERECVD              (R)
R_ADARPT                                        ({B)    WEAPON
BLUE_AIR     UNIT      TIME          LOCATION
                                     LOCATION   (B)        CAUSE
B_ARTILL     UNIT      TIME                      (B)     WEAPON
B_MED                                LOCATION
             UNIT      TIME                      (B)
B_ATTRIT                             LOCATION
             UNIT      STARTTIME     LOCATION  SIDE
CBSTAT                               LOCATION    (R)
R_ARTILL               ENDTIME
WIPE_OUT                             LOCATION  SIDE
WRS          UNIT      TIMESTART

INTEL                  TIMEEND

             UNIT      STATTIME

             UNIT      TIME

             UNIT      TIME

             UNIT      TIME

             DET_UNIT  DET_TIME


---

                            Ill. BCTP PROTOTYPE TABLE DOCUMENTATION

          The sections below document the individual tables which make up the BCTP
Prototype Database. The documentation includes a summary of the contents of each table, in
terms of the number of records and the physical size, a short description of the table, and a
description of each field in the table. When practical, the complete range of values for each
field is presented for rotations currently represented in the BCTP database. When several
similar items are present, the listings of values have been abbreviated by signifying the
presence of multiple items by a lower case n, e.g. ANNEX n. In cases where the number of
unique values is very large, the listing of values has been omitted.


---

Table 1 - ROTATION.DBF

Built from:          Summary rotation information
Number of records :  3
Size in bytes:       586
Level :              Root

Field Field Name        Type                       Width

1 ROTCODE               Character                  10

2 ROTID                 Character                  10

3 ROTSTART              Date                       8

4 ROTEND                Date                       8

5  ROTLOC               Character                  20

6 BCTPTEAM              Character                  10

7 COMPONENT             Numeric                    10

8 RESTART               Character                  1

9  UNIT                 Character                  10

   Total Size                                      88

Table Description

            The ROTATION table contains summary information describing each of the rotations
loaded into the BCTPdb. It enables the users to select rotations which support their areas of
interest.

Field: ROTID

             ROTID is the BCTP nomenclature for the rotation, made up of the fiscal year followed
by the serial number of the rotation within the fiscal year, e.g. 94-06.

Field: ROTSTART

            ROTSTART is the starting date of the rotation's WarFighter exercise.
Field: ROTEND

            ROTEND is the ending date of the rotation's WarFighter exercise.


---

Field: ROTCODE

            ROTCODE is an 8-character identifier used within the BCTPdb to uniquely identify a
BCTP rotation. It does not relate directly to any BCTP nomenclature and is made up to the
following subfields:

Characters  Type     Description
      1-2   Numeric
                     Fiscal Year rotation WFX took place e.g. 93
        3   Alpha    Top echelon being trained (C=Corps; D=Division; B=Brigade)
      4-5   Alpha
                     Type of unit (HH=Heavy; HL=Heavy/Light;
6           Alpha    LH=Light/Heavy)
                     Component (A=Active; R=Reserve)
7-8         Numeric  Index indicating order of units of this type within the same
                     fiscal year (01, 02 ...)

            The ROTCODE is the key field for accessing rotation-specific data. It is also used to
name the physical subdirectories which hold the data.
Field: ROTLOC

            ROTLOC is the theater of operations the simulation is set in, e.g. Korea.
Field: BCTPTEAM

            BCTPTEAM denotes the BCTP team assigned to conduct the rotation (A,B,C, or D)
Field: COMPONENT

            COMPONENT identifies whether the participating unit is Active or Reserve
Component.
Field: RESTART

            RESTART signifies whether or not the CBS simulation was restarted during the WFX.
Field: UNIT

            The unit identification of the participating unit.


---

Table 2 - REPORTS.DBF

Built from:         Number of objective tables loaded
Number of records:  7
Size in bytes:      354
Level:              Root

Field Field Name         Type       Width

   1 REPORT              Character     20
   2 TABLENAME           Character     10
   3 ENABLED             Character      1

             Total Size                32

Table Description

            The REPORTS table is used within the BCTPdb to control which objective data tables
are accessible to the user.

Field: REPORT

            The REPORT field holds the description of the objective data table which may be
accessed.

Field: TABLENAME

          TABLENAME is the actual name of the FoxPro DBF file which will be accessed for —

objective data.

Field: ENABLED

            ENABLED denotes whether the specific report has been activated (T) or not (F).


---

Table 3 - OBJTREND.DBF

Built from:         Information concerning objective trends
Number of records:  8
Size in bytes:      762
Level :             Root

Field Field Name            Type                  Width

1 OTREND                    Character                50
2 FILENAME
3 BOS                       Character                10
4 BOSNO —
                            Character                12

                            Numeric                  2

              Total Size                             715

Table Description

            The OBJTREND table contains a list of trends based on objective data which have
been identified and included in the BCTPdb in the form of spreadsheets and associated
graphs. The list of objective trends is keyed by Battlefield Operating System (BOS).

Field: OTREND

A description of the specific objective data trend.

Field: FILENAME

            The filename of the Quattro Pro spreadsheet containing the trend data and associated
trend graph.

Fields: BOS, BOSNO

Battlefield Operating System Identification, BOS Index. See Table 3a.

Table 3a - BOS/BOSNO

BOS           BOSNO                 BOS   BOSNO
Maneuver                1   Intelligence       5
Fire Support            2   Engineer           6
ADA                      3  CSS                7
C2                       4


---

Table 4 - GI.DBF

Built from:          "Good Ideas"
Number of records :  3
DBF Size in bytes:   634
FPT Size in bytes:   3392
Level :              Trends/ Good Ideas

Field Field Name     Type                Width

1 ROTCODE            Character               8
2 TYPEOFDATA         Character              20
3 DATANAME           Character              45
4 DATASOURCE         Character              15
5 MEDIUM             Character              10
6 FILENAME           Character              35
7 ORDER              Numeric                 3
8 ORG                Character              15
9 TIMESENT           Character              12
10 TIMERECVD         Character              12
11 BOBREF            Character              30

12 DATA              Memo                    10

Total Size                                 216

Table Description

            The "Good Ideas" table contains a number of ideas generated by military analysts
which are suggestions to improve the quality of training or data collection at the BCTP.

Field: ROTCODE

       The 8-character BCTPdb rotation identifier.

Field: TYPEOFDATA

            This field indicates the general category of the data record, such as a section of an Op
Order, a FRAGO, or a specific product. TYPEOFDATA is used as a key field in several
queries.


---

Field: DATANAME

            This field refines the category specified by the TypeOfData field. It contains
information such as the specific section title of unit products and a more detailed title for
graphics. It is used as a key field.

Field: DATASOURCE

            This field is intended to be the most general of the document qualifiers. It reflects the
highest level of aggregation of documents/sections. It is used as a key field.

Field: MEDIUM

            The MEDIUM field indicates the form of the referenced data. If MEDIUM is TEXT,
then the textual information is stored in the memo DATA field. If MEDIUM is GRAPHIC,
field FILENAME contains the fully qualified file name of the graphics file. For a MEDIUM
of VIDEO, the FILENAME field contains a video tape identification.

Range of Values:  TEXT
                  GRAPHIC
                  VIDEO

Field: FILENAME

            The FILENAME field contains the fully-qualified file name of the graphic image
identified by the remainder of the record, when MEDIUM is GRAPHIC. FILENAME
contains a short video tape identification for records where MEDIUM is VIDEO.

Range of Values:  Each graphic image consists of a unique file name; video clips contain a
                  short video tape identification.

Field: ORDER

            The ORDER field is a numeric field indicating the logical order of related records.
ORDER may indicate time sequencing, as in graphics images, or ordering of document
sections. ORDER applies to records with identical DATASOURCE values.

Field: ORG

            The ORG field contains the organization (Unit) identification of the unit preparing the
product in the case of unit-generated material or the identification of the unit being evaluated
in the case of performance data.


---

Field: TIMESENT

            The TIMESENT field is used to document the time some activity occurred, such as
the send time of a message. It also used to show the start time of a video segment.

Range of Values:  TimeSent may either be in the 12 character form DDHHMMZMMMYY
                  for message traffic, or the HH:MM:SS format for video clips.

Field: TIMERECVD

           The TIMERECVD field is used to document the time some activity occurred, such as
the receive time of a message. It also used to show the end time of a video segment.

Range of Values:  TIMERECVD may either be in the 12 character form
                  DDHHMMZMMMYY for message traffic, or the HH:MM:SS format
                  for video clips.

Field: BOB REF

            The Blueprint Of the Battle (BOB) reference indicates a relationship of one or more
sections of TRADOC Pamphlet 11-9 to the data contained in the current record.

Range of Values: TAn

Note: The prefix, "TA" represents a tactical function in the Blueprint of the Battlefield
(BOB); "n" is a number which identifies the function's location in the BOB hierarchy.

Field: DATA

            The DATA field is a memo field which contains the text of the product or document,
or a description of the graphic or video clip. In general, the DATA field contains the data of
interest, as defined by the remainder of the record.

Range of Values:  The range of values in the DATA field ranges from a few words to
                  several pages of textual data.

                      10


---

Table 5 - TFER.DBF

Built from:         Trend data gathered from the FER
Number of records:  310
DBF Size in bytes:  7260
Level :             Trends/ Good Ideas

Field Field Name        Type       Width

   1 ROTCODE            Character     8
   2 BOBREF             Character     13
   3 EVAL               Character      1

            Total Size                23

Table Description:

          The TFER table maintains a record of trends, by BOS, for all rotations loaded.

Field: ROTCODE
           The 8-character BCTPdb rotation identifier.

Field: BOBREF

          The Blueprint Of the Battle (BOB) reference indicates a relationship of one or more
sections of TRADOC Pamphlet 11-9 to the data contained in the current record.
Range of Values: TAn

Field: EVAL
            Subjective trend evaluation (+,-, or blank)

                        11


---

Table 6 - TAAR.DBF

Built from:          Trend data gathered from the AAR
Number of records :  99
DBF Size in bytes:   7290
Level :              Trends/ Good Ideas

Field Field Name     Type       Width

1  ROTCODE           Character      8
                     Character      3
2 BOBREF             Character     30
                     Character     30
3 SUSTAIN
                                   72
3  IMPROVE

   Total Size

Table Description:
            The TAAR table maintains a record of trends as documented in the After Action

Reviews (AARs), by BOS, for all rotations loaded.
Field: ROTCODE

             The 8-character BCTPdb rotation identifier.
Field: BOBREF

            The Blueprint Of the Battle (BOB) reference indicates a relationship of one or more
sections of TRADOC Pamphlet 11-9 to the data contained in the current record.
Range of Values: TAn
Field: SUSTAIN

            Specific areas for which performance is adequate and should be sustained.
Field: IMPROVE

            Specific areas for which performance is should be improved..

                     12


---

Table 7 - BOB.DBF

Built from:          TRADOC Pam 11-9     Blueprint of the Battlefield
Number of records :  267
DBF Size in bytes:   6506
FPT Size in bytes:   17664
Level :              Trends/ Good Ideas

Field Field Name     Type                    Width

1 BOBREF             Character                  13
                     Memo                       10
2  BOBREFDESC
                                                24
   Total Size

Table Description:

            The BOB table is a short reference file containing the Blueprint of the Battlefield
structure and descriptions.

Field: BOBREF

            The Tactical Blueprint of the Battlefield item number in the form TA.n..., where n is
the top-level BOS and the lower levels are components. The BOB table is carried out to five
levels, e.g. TA.1.1.2.2.2.

Range of Values: TAn...

Field: BOBREFDESC

            The Description of the related BoB function.

                                         13


---

Table 8 - Data Table

Built from:  | Unit-generated products
               Performance evaluations
                CBS/AARS products
               AAR Video

Number of Records          Rotation 93DHHRO1     Rotation 93DHHAO1
Size in bytes - DBF File                 724                   794
Size in bytes - Memo File
External File References             211,326               231,696
                                    1,966,912             1,704,704

                                         314                   400

Field Field Name           Type         Width

1 TYPEOFDATA               Character        20

2 DATANAME                 Character        45

3 DATASOURCE               Character        15

4 SIDE                     Character        1

5 MEDIUM                   Character        10

6 FILENAME                 Character        35

7 ORDER                    Numeric          3

8. ORG                     Character        15

9 DESTINATIO               Character        15

10 TIMESENT                Character        12

11 TIMERECVD               Character        12

12 OPNLTIMFRM              Character        15

13. OPTYPE                 Character        30

14 ANALEVAL                Numeric          2

15 CP                      Character        5

16 BOBREF                  Character        30

17 BATTLELOC               Character        10

18 OEG                     Character        5

19 DATA                    Memo             10

                           Total            291

Table Description

            The DATA table contains most of the textual information accessed by the users.
Seventeen of the nineteen fields are used to describe and/or categorize the data. The other
fields point to the file which contains the data (Field FILENAME) or actually contain the

                                        14


---

textual data ( Field DATA).
Field: TYPEOFDATA

            This field indicates the general category of the data record, such as a section of an Op
Order, a FRAGO, or a specific product. TYPEOFDATA is used as a key field in several
queries.

                                                                                 15


---

Range of values:        Rotation 93DHHA01

  Rotation 93DHHRO1       AARI
                          AAR2
     AARI                 ANALYSIS
    AAR2                  ANNEX n
    ADA                   APPENDIX n
    ANNEX n                BattleObs
    APPENDIX n            BosObs
    ATK GUID MATRIX       C2
     ATTACHMENT n          CHANGE n
    Analysis              COMBAT INSTRUCTIONS
    BOSOBS                 COMPARISON
     C2                   DISCONNECTS
     CHECKLIST            FRAGO n
     COMBAT INSTR         INTELLIGENCE
     CSS                  O/C TEAM
     Comparison            OPFOR MANNING
     EX DIR UPDATE        OPORD
     EXECUTION MATRIX     OPORD EXTRACT
     FRAGO n              OVERVIEW
     HPT LIST              SCENARIO
     INTELLIGENCE         TAB n
     MOB/SURVIVABILITY    UNIT
     O/C TEAM             WARNO n
     OPFOR
     OPFOR TEAM
     OPORD
     OTHER
     OVERVIEW
     Obs/Comments
     SAMPLE OVERLAY
    SCENARIO
     TAB n
     TEMPLATE
     UNIT
    VOL I CHAPTER 1
     VOL I CHAPTER 2
     VOL I CHAPTER 3
     VOL I CONTENTS
     VOL I COVE

                        16


---

Field: DATASOURCE

            This field is intended to be the most general of the document qualifiers. It reflects the
highest level of aggregation of documents/sections. It is used as a key field.

Range of values:

Rotation 93DHHRO01  Rotation 93DHHA01

  AAR2                AJS
  BDE OPORD           BDE OPORD
  CAA OPORD           CNTROFF OPORD
  CF OPORD            CORP OPORD
  CORP OPORD          DEF OPORD
  DIV OPORD           DIV OPORD
  FER                 FER
  FRAGO n             FRAGO n
  FSOP                ORDERS X-WALK
  ORDERS X-WALK       REPORT

 REPORT               WHITE CELL

  REQUEST
  WHITE CELL

Field: DATANAME

            This field refines the category specified by the TYPEOFDATA field. It contains
information such as the specific section title of unit products and a more detailed title for
graphics. It is used as a key field.

Field: SIDE

            The SIDE field is used as a qualifier for kinds of data which might apply to either the
Opfor or Blue side, such as unit-generated data.

Range of Values: OorB

Field: MEDIUM

            The MEDIUM field indicates the form of the referenced data. If MEDIUM is TEXT,
then the textual information is stored in the memo DATA field. If MEDIUM is GRAPHIC,
field FILENAME contains the fully qualified file name of the graphics file. For a MEDIUM
of VIDEO, the FILENAME field contains a video tape identification.

                    17


---

Range of Values:   TEXT
                   GRAPHIC
                   VIDEO

Field: FILENAME

          The FILENAME field contains the fully-qualified file name of the graphic image
identified by the remainder of the record, when MEDIUM is GRAPHIC. FILENAME
contains a short video tape identification for records where MEDIUM is VIDEO.

Range of Values:   Each graphic image consists of a unique file name; video clips contain a

                   short video tape identification.

Field: ORDER

          The ORDER field is a numeric field indicating the logical order of related records.
ORDER may indicate time sequencing, as in graphics images, or ordering of document
sections. ORDER applies to records with identical DATASOURCE values.

Field: ORG

          The ORG field contains the organization (Unit) identification of the unit preparing the
product in the case of unit-generated material or the identification of the unit being evaluated
in the case of performance data.

Range of Values :

Rotation 933DHHRO1          Rotation 93DHHAO01

   1-167/CAV/SQDN              1//BDE
   10/ADA/BDE                 11/KPA/CORP
   149//BDE                    116/CAV/BDE
  35 /AVN/BDE                  17/FA/BDE
  35/AVN/BDE                  3//BDE
  35/IN/DIV                   4/AVN/BDE
  ORG                         4/T1N/DIV
  67//BDE                      8/MAR/BDE
  69//BDE                     DISCOM/BDE
   8/ICAA                     IIl//CORP
   CENTRAL FROUNT
   EAC
   OPFOR
   X//CORP

                            18


---

Field: DESTINATIO

            The DESTINATIO field is intended to document the recipient of a message or order.
Its format is the same as the ORG field described above.

Range of values:

Rotation 93DHHR01  Rotation 93DHHA01

  28/IN/DIV         (Not Used)
  35/IN/DIV
  69//BDE
  X//CORP

Field: TIMESENT

            The TIMESENT field is used to document the time some activity occurred, such as
the send time of a message. It also used to show the start time of a video segment.

Range of Values: TimeSent may either be in the 12 character form DDHHMMZMMMYY
for message traffic, or the HH:MM:SS format for video clips.

Field: TIMERECVD

            The TIMERECVD field is used to document the time some activity occurred, such as
the receive time of a message. It also used to show the end time of a video segment.

Range of Values:  TIMERECVD may either be in the 12 character form
                  DDHHMMZMMMYY for message traffic, or the HH:MM:SS format
                  for video clips.

Field: OPNLTIMFRM
            The OPNLTIMFRM field is used to document the battle phase. —

                   19


---

Range of Values:

Rotation 93DHHRO1  Rotation 93DHHA0I1

  CURRENT BATTLE     PHASE I
  PHASE 1            PHASEI II
  PHASE I            PHASE II
  PHASE I/ II        PHASE III
  PHASE I/ I/II      Phase I II III
  PHASE I/II
  PHASE I/II
  PHASE II
  PHASE III
  Phase I/II

Field: OPTYPE

OPTYPE documents the type of the operation to which the DATA record applies

Range of Values:

Rotation 93DHHROI       Rotation 93DHHAOI

BHO                       ATTACK
                          ATTACK / DEFEND
CATK                       ATTACK DEFEND
                          ATTACK DEFEND CATK
COUNTER ATTACK            Attack
                          DEEP ATK
DEEP ATK                 _DEFEND
                          DEFENSE
DEEP ATTACK                Defend
                          MOVE PASSAGE OF LINES
DEFEND                  ATTACK
                           CONSOLIDATION
. DEFEND             D    PASSAGE OF LINES

DEFEND / ATTACK

OPTYPE

MOVE

MOVE / DEFEND

MOVE / DEFEND / ATTACK

MOVE /DEFEND / CATK

MOVE/ DEFEND / CATK

Move / Defend

SCREEN

Field: ANALEVAL

            The ANALEVAL field is intended to allow an analyst to enter a qualitative evaluation
of the information contained in the remainder of the record.. It is not currently used.

                        20


---

Field: CP

            The CP field shows the command post to which information in the current record
applies.

Range of Values: CP

Field: BOBREF

            The Blueprint Of the Battle (BOB) reference indicates a relationship of one or more
sections of TRADOC Pamphlet 11-9 to the data contained in the current record.

Range of Values: TAn

Field: BATTLELOC

            The BATTLELOC field indicates the relative position on the battlefield. It is not
currently used. |

Field: OEG

Operational Exposure Guidance. (Not currently used)

Field: DATA

            The DATA field is a memo field which contains the text of the product or document,
or a description of the graphic or video clip. In general, the DATA field contains the data of
interest, as defined by the remainder of the record.

Range of Values:  The range of values in the DATA field ranges from a few words to
                  several pages of textual data.

                      21


---

Table 9 - R_ADARPT Table
Built from: © WAARS Report ADARPT_R.OUT - Red Air Defense Report

Number of Records       Rotation 93DHHRO1      Rotation 93DHHAO1
Size in bytes DBF/Memo                 822                   1356

                                    83,408                137,342

Field Field Name        Type           Width

1  TIME                 Character          6
                        Character          9
2  AIRCRAFT             Character         15
                        Character         15
3  MISSION              Character         15
                        Character         12
4  UNIT                 Character         12
                        Numeric            4
5  WEAPON               Numeric            4
                        Numeric            4
6  LOCATION             Numeric            4

7  ENGTYPE                                101

8  RPT_FIRED

9  EOE_FIRED

10 DESTROYED

i DAMAGED

   Total Size

Table Description:

The R_ADARPT table holds information concerning Opfor air defense missions.

Field Name: TIME

            The time in DDHHMM format that the Opfor artillery mission was initiated.

Field Name : AIRCRAFT

            The type of aircraft (if any) destroyed or damaged.

Range of Values:    A-10, AH-1, AH-64, CH-53D, EH-60, F-16,
                    F-4G, OH-58, OH-58D, RF-4, UH-1, UH-60

                                   22


---

Field Name : MISSION

Unique mission identification for the Opfor ADA mission.

Field Name : UNIT

Opfor ADA unit identification.

Field Name : WEAPON

Opfor ADA weapon type.

Range of Values:   l1O0Q0MM.AAA, 14.5MM.AAA.ZPU2,
                   14.5MM.AAA.ZPU4, 37MM.AAA(M1939),
                   57MM.AAA(S-60), 57MM.AAA(ZSU),
                   SA-16(GIMLET), SA-2(GUIDELINE), SA-3(GOA), SA-7B(GRAIL)

Field Name : LOCATION

Location Blue aircraft was destroyed or damaged.

Field Name : ENGTYPE

Opfor engagement type.

Range of Values: Automatic, Self_Defense

Field Name : RPT_FIRED

            Number of rounds/missiles fired during a mission which resulted in aircraft damage or
destruction.

Field Name: EOE_FIRED

            Number of rounds/missiles fired during a mission which resulted in no aircraft damage
or destruction.

Field Name: DESTROYED

Number of aircraft destroyed.

Field Name : DAMAGED

Number of aircraft damaged.

                                23


---

Table 10 - BLUE_AIR Table
Built from: | WAARS Report ARMY_AIR_B.OUT - Blue Army Aviation Report

Number of Records       Rotation 93DHHRO!1     Rotation 93DHHAO1
Size in bytes DBF/Memo                578                   3595

                                    42,420                262,661

Field Field Name        Type           Width

1  MISSION              Character         20
                        Character          6
2  TIME                 Character         12
                        Character          15
3  LOCATION             Character         15
                        Numeric            4
4  UNIT
                                           73
5  SYSTEM

6  HITS

   Total Size

Table Description:
            The BLUE_AIR table describes blufor air missions and their results.

Field Name : MISSION
            Unique mission identification for the Blue Air mission.

Field Name: TIME
            The time in DDHHMM format that the Blue Air mission was initiated.

Field Name: LOCATION
            Location Opfor system was destroyed or damaged.

Field Name: UNIT
            Blue Air unit identification. Unit designation may indicate type of air asset employed.

                                   24


---

Field Name: System
            Opfor systems hit by Blue Air.

Range of Values:

Rotation 93DHHRO1       Rotation 93DHHAO0I1

 100MM AAA                 100MM. AAA
  BMP-2                    107MM. MRL(TYP63
  BMP-BMD                  120MM. MTR
  BRDM                     122 MRL.BM21-11
  BTR.60                   122MM.D74-1981
  BTR.70-73-80             122MM. HOW(M-30)
  COM.SUP.SYS.C3           122MM.HOW.M1977
  DISMNTD.TROOPS           130MM.FG(M-46)
  HOT.SHOT                 130MM.GUN.M 1975
  HQ.SVC.SPT.PERS          14.5MM.AAA.ZPU2
  No                       145AM AA ZM PU4
  SA-13(GOPHER)            152MM.G-H.M1937
   SA-15(TOR)              152MM.HOW.M 1974
  SA-16(GIMLET)            203MM.KOKSAN
  SPAAG.2S6                240MM. .MRL.M1985
  TANK.T-80.HA             37MM. AAA 1939)
  TRK LRG                  57MM. .AAA(S-60)
  TRKMED                   57MM. AAA(ZSU)
  TRK.TANKER               60-82MM MTR
                           76MM. ATGM 1942
                           APCM1973
                           ATGM(AT-2)
                           ATGM(AT-3-4)
                           BRDM
                           BTR.60
                           DISMNTD.TROOPS
                           EARTH. MOVER
                           FIRECAN
                           HQ.SVC.SPT.PERS
                           No
                           REAR AREA. TROOP
                           SA-16(GIMLET)
                           SYSTEM _
                           SA-2(GUIDELINE)

Field Name: HITS

Number of targets hit.

                                            25


---

Table 11 - BLARTILL

Built from:     WAARS Report BLU_LARTILLERY_MISSIONS.OUT - Blue Combat Artillery
                Missions

Number of Records           Rotation 93DHHRO1      Rotation 93DHHAO1
Size in bytes - DBF File                3146                   9864

                                      403,106               1,263,010

Field Field Name            Type           Width

             1  MISSION     Character         10
                            Character          6
             2  MTYPE       Character          6
                            Character         15
             3  TIME        Character         12
                            Character         15
             4  UNIT        Character          9
                            Numeric            4
             5  LOCATION    Character         il
                            Character         20
             6 WEAPON       Character         15
                            Numeric            4
             7  AMMO
                                              128
             8  ROUNDS

             9  MPOI

             10 UNITHIT

11 SYSTEMHIT

12 NUMBERHIT

                Total Size

Table Description:

      The B_ARTILL table describes blue artillery missions and their results. —

Field Name : MISSION
           Unique mission identification for the Blufor artillery mission.

                                       26


---

Field Name: MTYPE
            Type of artillery mission.

Range of Values :

Value             Description

COUNTE            Counterfire mission
FASCAM            Scatterable Mines
GUIDED            Guided munitions

SEAD A            Suppress Enemy Air Defense

OTHERS            All others

Field Name: TIME

The time in DDHHMM format that the Blufor artillery mission was initiated.

Field Name: UNIT

Blue artillery unit identification.

Field Name : LOCATION

Location of Blue artillery battery.

Field Name : WEAPON

Blue artillery weapon type.

Range of Values:  152MM.GUN(2S5), 155MM.H.SP, 155MM.H.TOWED,
                  203MM.H.SP,MLRS, PALLADIN

Field Name: AMMO

- Type of ammunition used in the Blue artillery mission.

Range of Values; AMMO, Conventio, Improved, Mines, Precision

Field Name : ROUNDS
            Number of artillery rounds fired.
                                                                                    27


---

Field Name: MPOI
            Location of the main point of impact.

Field Name: UNITHIT
            Identification of the Opfor unit hit by blue artillery.

Field Name: SYSTEMHIT
            Opfor system hit by Blue artillery.

Field Name: NUMBERHIT
            Number of Blufor artillery hits on Opfor system.

                                                                                 28


---

Table 12 - BLMED Table
Built from: © WAARS Report BLU_MEDICAL.OUT - Blue Medical Report

Number of Records         Rotation 93DHHRO!1    Rotation 93DHHAOI1
Size in bytes - DBF File                 154                  454

                                       7,682                22,034

Field Field Name          Type           Width

1  STARTTIME              Character          6
                          Character          6
2  ENDTIME                Character         15
                          Numeric            4
3  UNIT                   Numeric            4
                          Numeric            4
4  ADMITTED               Numeric            4
                          Numeric            4
5  RETURNED
                                            48
6  SHIFTED

7  DIED

8  EVACUATED

   Total Size

Table Description:
            The B_MED table details activities of blue medical units.

Field Name : STARTTIME
            Start time of 4 hour status period.

Field Name : ENDTIME
            End time of 4 hour status period.

Field Name : UNIT
            Blue medical unit identification.

Field Name : ADMITTED

                                     29


---

            Number of patients admitted to the medical unit.
Field Name : RETURNED

           Number of patients returned to duty from the medical unit.
Field Name : SHIFTED

           Number of patients shifted from the medical unit to another.
Field Name : DIED

            Number of patients that died at the medical unit.
Field Name : EVACUATED

           Number of patients evacuated from the medical unit.

                                                                                  30


---

Table 13 - BLATTRIT Table
Built from: WAARS Report CBATTR_BLU.OUT - Biue Combat Attrition

Number of Records       Rotation 93DHHROI      Rotation 93DHHAOI
Size in bytes DBF/Memo               5180                   9555

                                  290,306                535,306

Field Field Name        Type           Width

1 TIMESTART             Character          6
                        Character          6
2 TIMEEND               Character         15
                        Character         20
3  UNIT                 Numeric            4
                        Numeric            4
4  EQUIPMENT
                                           56
5  DESTROYED

6  DAMAGED

   Total Size

Table Description:
            The B_ATTRIT table documents blufor attrition throughout the WFX.

Field Name : TIMESTART
            Start time of 4 hour status period.

Field Name : TIMEEND
            End time of 4 hour status period.

Field Name : UNIT

          Identification of blue unit from which equipment was damaged/ destroyed.

                                   31


---

Field Name: EQUIPMENT
           Type of Blue equipment destroyed or damaged.

Range of Values:

Rotation 933DHHRO1                                       Rotation 93DHHA01

155MM.H.SP       MINE.CLEARING  155MM.H.SP               MBT.M1.Al
203MM.H.SP                      155MM H.TOWED            MBT.M1A1.HA
42.MTR           MINE.LAYING    4.2.MTR                  MINE.CLEARING
ACQ.RADAR                       60MM.MTR                 MINELAYING
APC.113          MK19           81MM.MTR                 MK19
AVLB             MLRS           ACE                      MLRS
CARRIER.ARM      PALLADIN       ACQ.RADAR                PALLADIN
CF.RADAR.Q-36    POD.POL.SM     APC.113                  POD.POL.MED
CF.RADAR.Q-37    SEMI.34T       AVLB                     POD.POL.SM
CHAPARRAL        SEMI.VAN       CARRIER.ARM              SEMI.12T
COM.SUP.SYS.C3   STINGER        CF.RADAR.Q-36            SEMI.22T
DRAGON           TANKER.SM      CFV                      SEMI.34T
EARTH.MOVERS                    CHAPARRAL                SEMI.VAN
ITV              TRACKED.RECOV  COM.SUP.SYS.C3           STINGER
LIGHT.TRUCK.4X4                 DRAGON                   TANKER.SK.GAL
MBT.M60          TRUCK.10T      EARTH.MOVERS             TANKER.SM
                 TRUCK.2-1/2T   HAWK                     TOW.LAUNCHER
                 TRUCK.35T      HAWK FC.RADAR            TRACKED.RECOV
                 WHEELED.WRECK  IFV/LAV                  TRUCK.10T
                 ER             ITV                      TRUCK.2-1/2T
                                LAV-25                   TRUCK.5T
                                LIGHT. TRUCK.4X4         WHEELED.WRECKER

Field Name: DESTROYED
            Number of units of equipment destroyed during the time period.

Field Name: DAMAGED
            Number of units of equipment damaged during the time period.

                                32


---

Table 14 - CBSTAT          COMBAT _DAMAGE_B.OUT,
Built from WAARS Reports:  COMBAT_DAMR.AOG UTE - Blue/Red Combat
                           Damage Report

Number of Records          Rotation 93DHHRO1      Rotation 93DHHAO1
Size in bytes - DBF File                4201                  13,508
                                                             837,786
                                     260,752

Field Field Name           Type           Width

1  STATTIME                Character          6
                           Character
2  SIDE                    Character         15
                           Character         15
3  UNIT                    Character         15
                           Numeric            3
4  EQUIPMENT               Numeric            3
                           Numeric            3
5  CAUSE
                                              62
6  NOHIT

7  NOWOUND

8  NOKILL

   Total Size

Table Description:
            The CBSTAT table describes combat activity for both sides.

Field Name: STATTIME
            End time of four hour block for which data apply.

Field Name: SIDE
            Side sustaining casualties.

Range of Values: RorB

                                      33


---

Field Name: UNIT
            Unit sustaining casualties.

Field Name: EQUIPMENT
            Type of equipment sustaining casualties.

Field Name: CAUSE
            Cause of casualty.

Range of Values: Artillery, air_attack, contact, mines, OVERRUN, ETT's, transit
Field Name: NOHIT

            Number personnel hit.
Field Name: NOWOUND

            Number personnel wounded.
Field Name: NOKILL

            Number personnel killed.

                                                                                  34


---

Table 15 - R_LARTILL

Built from: WAARS Report RED_ARTILLERY_MISSIONS.OUT - Red Artillery Missions

Number of Records       Rotation 93DHHRO1  Rotation 93DHHAOI
Size in bytes DBF/Memo               5708              12064

                                 403,106            1,263,010

Field Field Name        Type       Width

1   MISSION             Character     10
                        Character      6
2   MTYPE               Character      6
                        Character     15
3   TIME                Character     12
                        Character     15
4   UNIT                Character      9

5   LOCATION            Numeric       4

6 WEAPON                Character     11
                        Character     20
7   AMMO                Character      15
                        Numeric        4
8 ROUNDS
                                      128
9   MPOI

10 UNITHIT

11  SYSTEMHIT

12 NUMBERHIT

    Total Size

Table Description:

           The R_ARTILL table describes opfor artillery missions and their results.
Field Name : MISSION

            Unique mission identification for the Opfor artillery mission.
Field Name: MTYPE

            Type of artillery mission.

                        35


---

Range of Values :

Value              Description
COUNTE             Counterfire mission
FASCAM             Scatterable Mines
GUIDED             Guided munitions
SEAD A             Suppress Enemy Air Defense

OTHERS             All others

Field Name: TIME

                       The time in DDHHMM format that the Opfor artillery mission was initiated.

Field Name: UNIT

                        Blue artillery unit identification.

Field Name: LOCATION

                         Location of Blue artillery battery.

Field Name: WEAPON

                         Blue artillery weapon type.

Range of Values:

                 122MM. HOW(2S81)
                 122MM. HOW(D-30)
                 122MM.MRL(BM21)
                 152MM.G-H(2A65)
                 152MM.G-H(2819)
                 152MM.GUN(2S85)
                 152MM. HOW(2A36)
                 152MM HOW(2S3)
                203MM.GUN(2S7)
                 220MM.MRL(BM22)
                 300MM.MRL(9A52)
                 SS-1C
                 SS-21

                                                                               36


---

Field Name: AMMO
            Type of ammunition used in the Blue artillery mission.

Range of Values: AMMO, Conventio, Improved, Mines, Precision
Field Name : ROUNDS

            Number of artillery rounds fired.
Field Name: MPOI

            Location of the main point of impact.
Field Name: UNITHIT

            Identification of the Opfor unit hit by blue artillery.
Field Name: SYSTEMHIT

            Opfor system hit by Blue artillery.
Field Name: NUMBERHIT

            Number of Bluefor artillery hits on Opfor system.

                                                                               37


---

Table 16 - WIPE_OUT Table
Built from: WAARS Report WIPED_OUT.OUT Destroyed Unit Report

Number of Records         Rotation 93DHHRO1                Rotation 93DHHA01
Size in bytes - DBF File                1076                              963

                                      60,482                           54,154

      Field Field Name    Type         Width Dec

      1  UNIT             Character                    15

      2  STATION          Character                    10

      3  TIME             Character                    6

      4  LOCATION         Character                    12

      5  THRESHHOLD Numeric                            6   3

      6  REMAINDER        Numeric                      6   3

         Total Size                                    56

Table Description:

      The WIPE_OUT table documents when and where blue units are considered wiped

out.

Field Name : UNIT

      Identification of the unit which was destroyed.

Field Name: STATION

      ‘Workstation which reported the unit destruction.

Field Name : TIME

      The time in DDHHMM format that the unit was destroyed.

                                   38


---

Field Name : LOCATION
           Location unit was destroyed.

Field Name : THRESHHOLD

          Portion of total unit below which unit is considered destroyed.

Field Name : REMAINDER
           Portion of unit remaining after destruction.

                                                                                 39


---

Table 17 - INTEL Table

Built from:      WAARS Report BLUE_SORTn.DAT

Number of Records            Rotation 93DHHRO1!  Rotation 93DHHAO1
Size in bytes - DBF File                26.902               60,530

                                      2,313,990           5,205,998

Field Field Name             Type                Width

             1   SIDE        Character               1
                             Character              10
             2   DET_UNIT    Character              10
                             Character               6
             3   DET_UN_TYP  Character               2
                             Character               1
             4   DET_TIME    Character              10
                             Character              10
             5   ASSET_LEVE  Character              11

             6   ASSET_TYPE  Character               10
                             Character               2
             7   RECIPIENT   Character               12

             8   PERCEPT                             86

             9   LOCATION

             10  ACTIVITY

             11  ORIENT

             12  PARENT

                 Total Size

Table Description:
            The INTEL table summarizes intel received by both sides, in terms of when intel

reports are recieved, the units detected, the location, and the perceived activity.
Field Name: SIDE

            Always B. This table contains only Bluefor data.
Field Name: DET_UNIT

             Identification of the unit detected by the intel asset.

                             40


---

Field Name: DET_UN_TYP
            Type of unit detected.

Field Name: DET_TIME
            Time of detection.

Field Name: ASSET_LEVE
            Echelon/ level of intel asset.

Range of Values: AV, CA, CO, DG, DV, EA, NA, SO

Field Name: ASSET_TYPE

            Type of intel asset.
Field Name: RECIPIENT

            Recipient of intel information.
Field Name : PERCEPT

            Perceived Identification of detected unit.
Field Name: LOCATION

            Actual location of detected unit.
Field Name: ACTIVITY

            Type of mission the detected unit was engaged in.

Range of Values: ATTACK, DEFEND, ENGAGE, MVMT, WTHDR, UNK, NEUTED

Field Name: ORIENT
            Orientation.

Field Name: PARENT
            Parent unit of detected unit.

                                                                                 41


---

Table 18 - WRS.DBF

Built from:     WAARS Report WRS_JOURNAL.DAT
Level :         Rotation-specific

Number of Records           Rotation 93DHHRO1  Rotation 93DHHAO1
Size in bytes - DBF File                  214                     377
Size in bytes - Memo File
                                        18662                   32,680
                                       48,256                   93504

Field Field Name            Type               Width

             |  BOS         Character             20
                            Character             10
             2  UNIT        Character             25
                            Date                   8
             3  LOCATION    Character              5
                            Character              7
             4  DATE        Memo                  10

             5  TIME                               86

             6  WORKSTATIO

             7  COMMENTS

                Total Size

Table Description:
            The WRS table holds journal entries of the workstation operators and OCs, keyed by

functional area and time.
Field Name: BOS

            Either Battlefield Operating System (BOS) or other functional area.

                            42


---

Range of values:

Rotation 93DHHRO1       Rotation 93DHHA01

  COMMAND&CONTROL          AIRDEFENSE
 FIRESUPPORT              COMMAND&CONTROL
  MANEUVER                COMMAND&CONTROL/SUST
  MANEUVER-ARMYAVIATIO    FIRESUPPORT
  MOBILITY/SURVIVABILI    INTELLIGENCE
  SUSTAINMENT             MANEUVER
                          MANEUVER-ARMYAVIATIO
                          MOBILITY/SURVIVABILI
                          SUSTAINMENT

Field Name: UNIT
           The name of the unit to which the WRS comments pertain.

Field Name: LOCATION
            Grid coordinates locating incident being reported.

Field Name: DATE
Field Name: TIME

            HH:MM
Field Name: WORKSTATIO

            Workstation ID for analyst making the entry
Field Name: COMMENTS

            The actual comments of the workstation operator - in a memo field.

                        43


---

                                                                                                                     CONTRACT #: MDA 903-92-D-0075
                                                                                                                            DELIVERABLE #: 0018-0018AG
                                                                                                                                                    AUGUST 29,1994

   FINAL LOADING PROCEDURES GUIDE:
BATTLE COMMAND TRAINING PROGRAM

                     RELATIONAL DATABASE
                                  (BCTPpDB)

                         VERSION PROTOTYPE 3

                                Terry P. Bartkoski
                                          PRC, Inc.

  Submitted by: Mr. Michael R. McCluskey, Acting Chief
                Unit-Collective Training Research Unit
                             and Jack Hiller, Director
                        Training Research Laboratory

   Dr. Stanley Halpin, Contracting Officer's Representative

                                   September 30, 1994
                         U.S. Army Research Institute


---

           FINAL LOADING PROCEDURES GUIDE
                        TABLE OF CONTENTS

SECTION1

I. Introduction ©... 0n. ee eee teens 1-1]

A. How to Use This Guide...        . 0... . nee ene 1-1

B. Components ...... 0.0... 0.0 ccc  eet eee eee eee ee 153

C. Conventions 2... 0.n . ee e. ee e eens 1-5

           1. General Conventions ...0. .0.. .. c . c. c . te. e e. ens 1-5

           2. Keyboard Conventions .... 0.. 0000. ce. ce. ce. ce ee. e e. ee 1-6

           3. Mouse Conventions .... 0.0. 00. . ce. ce . ee. e e. ee . eae 1-7

SECTION2

Il. Guided Tour... 1. eee eee wee. Del
            A. Pre-Processing Applications .....0. 00. 00. . c. ee. e e. ee . ee. e 2-2
            B. Loading and Database Applications .....2. 0... . 0.0. 0 c. ece.ee. e . aee 2-4

SECTION 3

III. Pre-Processing Procedures...  .. 0.0... 0. cecc e eeee eee eee 3-1

A. Planning: Sorting/Indexing .........0.0.0 20.000.           eee 3-2

B. Loading the Scanner .. 1.0. ee . te. ens 3-4.

           1. Loading Documents using the ADF .......................02. 3-4

           2. Loading Single Documents .............0 0.00000  eee 3-5

C. Scanning Techniques for Text Files .....0. 00. .00.e. ee . eee. ee. ns 3-6

D. Scanning Techniques for Graphic Files ............. 00.0000 ee eeuue 3-11

E. Video Preparation ... 0.0.e . e . e 3-18

F. Data Tape Preparation ........ 0.0.0.0 eee.e. a. e 3-24

G. Saving Files 2... 1.              ee nee eee ene 3-28

H. Creating Rotation Data Tables .............00. 0.000 3-30

SECTION 4

IV. The Loading Process for Rotation Data Tables ........................4.. 4-]
            A. Loading Procedures for Scanned Documents ........................ 4-3
            B. Loading Procedures for Digital Data............ 0.000.000 0c eee eee 4-8
                         1. Digital Tapes 0... eee eee 4-8
                         2. Floppy Disks ...... 0.0.0e . e. e e. ae 4-9
                        3. Loading Procedures for Video Tapes ....... 000.0000 ccc eee TBP

SECTION 5

V. The Loading Process for Good Ideas and Trend Tables ...................... 5-1


---

A. Loading Procedures for Good Ideas ........020..00 20.00.00... cee eee 5-2

B. Loading Procedures for Trends ..... 0.0. .0. 0.... c c. ee . eee. eee. eas 5-6

           1. Performance Trends (AAR Trends) .....................0000. 5-6

           2. FER Trends ... 0... 0                   eee nee nas 5-9

           3. Objective Data Trends...  00. ce cea TBP

SECTION 6

VI. References 2.0... cccc ence eee ete nees 6-1
APPENDICES

APPENDIX A - Setting Preferences .....0. 00. 00. . . cc .c0 eee. ee0 e en A-1

APPENDIXB - Standard Loading Conventions ....................00.0000u. B-1

APPENDIX C - Trouble Shooting .......0. 00. 00. 0 .c . ce0 ce e. ee.e0 e eeee C-1

APPENDIX D - Data Types & Media ...........0.0. 000.  e eee eee D-1

APPENDIX E - Archive Reference ID Codes.............0 0.000000 eeeeuee E-1

GLOSSARY ...0 0.                        ce eet        e nee ne ney GLOS-1

USER NOTES ....... 0. cecce ece eee nee USER-1

IMPROVEMENT SUGGESTIONS ..... 000. .00. ccc. ce. ce . ce. ce . e ge. nes

                                                      il


---

Figure                                                  Page

2-1     TextBridge OCRicon .......... 0... ec           ete eee 2-2
2-2
2-3     Norton Desktop Editor icon ...2.. 2... . 0 c. ec .e .e. ee. eee 2-2
2-4
2-5     Paint Shop Proicon..........  20... 0. ee ee eee eee 1... 2-2
2-6
2-7     Loadvdoicon ........ 0... cee                   eee ee eee ee 2-3
3-1
3-2     WordPerfecticon ........ 0.0... . eee ee ee eee eee *, 2-3
3-3
3-4     FoxPro2.6 icon ......... 0... ec                eee bee ee 2-4
3-5
3-6     BCTPdbicon .............. e nee ene ne ee eee... 2-4
3-7
3-8     Interface Screen for TextBridge ..... 0.. 0... . c. ece.e. ee . eee ee 3-6
3-9
3-10    Preference Screen for TextBridge .... 0.0.0.. 0 c. e. ce .e. e . ene 3-7
3-11
3-12    Scanner Settings Screen for TextBridge ..........0 .. 0. 2. . ..e. ee 3-8
3-13
3-14    Add More Pages Screen for TextBridge............... 0... 3-8
3-15
3-16    Save As Screen for TextBridge ... 2.0. e . e. es 3-9
3-17
3-18    Interface Screen for Paint Shop Pro .... 20.. .. c. ece . ee. e ee. ee e. ee 3-11 ©
3-19
        File Pull down Window for Paint Shop Pro ........0. 0:.e. ee. e. e. e 3-12

        Interface Screen for Envisions Scanner .......0. -0. 00. . . e ee. e e .e. e 3-12

        Preview option for Envisions ....0 . .0. 0 . ee. e . e. e e. te e. ee 3-14

        Scanned Image displayed in Interface Screen for Paint Shop Pro ............ 3-14

        Paint Shop Pro Tools box ........ 2... 00. ee   tee eae 3-15

        Colors Pull down Window for Paint Shop Pro ............ 0.0.0. eeeuee 3-16

        Save As Screen for Paint Shop Pro .... 0.0. .2.... ce . ce .ee. e. ee 3-17

        VCR Tape Reference Identifier Screen .... 20. .00.. ce .e.. ee. e 3-19

        Mark VCR Tape Topics Screen ..... 0.0.0.0. 0 ce ee ees 3-20

        VCR Tape Comments Screen ...2. 0.0.. 0... c. ece. ee .e. ee . ees *, 3-22

        Data Tape Loading steps ........ 2... 0.0 cece  ee eet eee ene 3-24

        Directory/sub-directory/file structure for BCTPdb ....................00. 3-28

        Open dialog window for FoxPro.................-.4.- beeeen es ... 3-30

                                                        ili


---

Figure                                                     Page

3-20    Rotation Table for BCTPdb ............. rr 3-31
3-21
4-1     Command Window from FoxPro ....0. .0.0. ce . e.e .e .s . 3-33
4-2
4-3     Open dialog window for FoxPro ............. 0.00.  ene 4-3
4-4
4-5     Rotation Data Table - Screen] 1.0.0.0... 0... cee es 4-4
5-1
5-2     Rotation Data Table - Screen2 ... 0.00.. e. s 4-5
5-3
5-4     Rotation Data Table displayed in Change option................-..0000- 4-6
5-5
C-1     Filled out record for Rotation Data Table displayed in Change option......... 4-6

        Open dialog window for FoxPro...  1... 0. es 5-2

        Good Idea (Gi) Table ©... 6 ee eee 5-3

        Good Idea (Gi) Table displayed in Change option .................2.00. 5-4

        Performance Trends (Taar) Table ...... 20.0.0. e. e. e 5-7

        FER Trends (Tfer) Table .... 0... 0.               ee ns 5-11

        Screens for Loading Data (memo) Fields ............0.. 0.00000. c ee eee C-20

                                                           iv


---

                                SECTION1

                                          I. INTRODUCTION

Space has been provided in the  The purpose of the BCTPdb Loading Guide is to provide loaders
margin throughout this guide    and analysts with a system reference for loading a relational
to allow users to make notes.   database. It provides basic information in regard to the database
                                and the data that is entered into it. Where it is appropiate, it
                                specifies who (loader or analyst) is required to prepare and/or load
                                the data. More importantly, methods and procedures are explained
                                which the user may find helpful in performing relational loading
                                tasks. It is assumed that the user has a basic understanding of DOS
                                based personal computer (PC) systems and is familiar with using
                                software that operates in a Windows environment.

                                A. How to Use This Guide
                                      This Loading Guide consists of the following sections:

                                      > Introduction. Section 1 provides users with a brief overview
                                      of the BCTPdb and the loading system.
                                      > Guided Tour. For a quick description of the applications
                                      used to prepare materials and load the database, see Section 2.
                                      > Pre-processing Procedures. Section 3 describes the actual
                                      steps involved in the preparation of documents and the database
                                      for loading.
                                      > The Loading Process for Rotation Data Tables. Section 4
                                      describes the procedures used to load the different media types
                                      into the Rotation tables.
                                      > The Loading Process for Good Ideas and Trends Tables.
                                      Section 5 explains the Analyst and Programmer tasks and

                                                           1-1


---

procedures used to load the Good Ideas and Trend tables.

> Appendices. The appendices contain references, information

on setting preferences, loading conventions, trouble shooting,
data types & media, and Archive Reference coding.
> Glossary. Acronyms are defined in this section.
> User notes. Users may use this area to record their notes
and frequently used information.
> Improvement Suggestions. This section has been provided
for suggestions on improving the loading process and guide.


---

B. Components
The components of the BCTPdb Loading System are:

       > Application Software
        > Hardware
       > Data Files
       > BCTPdb Loading Guide

The loading system uses Microsoft® FoxPro®, TextBridgeTM OCR,
Paint Shop ProTM, and Envisions TWAIN application software.
FoxPro® is a popular commercial relational database. The BCTPdb
FoxPro® application is the main program driving the database and
works in conjunction with several other commercial and custom
programs. It calls the other applications for execution of unique
functions, such as video tape control, graphics display, and
spreadsheets. The loading interface for loading data is executed

using FoxPro®. TextBridgeTM OCR (Optical Character Reader) is

used to scan and save into data files all hardcopy text files. Paint
Shop ProTM and Envisions TWAIN application software are used
to scan, manipulate and save into data files all hardcopy graphic
and other documents that cannot be scanned as a text file.

The BCTPdb database is run on any IBM® compatible 386 or 486
computer with adequate RAM and ROM storage. Microsoft®
DOS/WindowsTM is also required. Recommended minimum
configuration is a 486 33MHZ with 8 Megabytes of RAM. Hard
drives in the 500 Megabyte range adequately support the BCTPdb
software and one to two WFX sets of data. Storage for additional

WFX data sets is highly recommended. A standard mass storage
device for the BCTPdb data is to be decided. The scanner being

                                                                                                               1-3


---

used at present is the Envisions EVN6100 Color Scanner. Other
scanning options aimed at increasing efficiency and reducing cost
are being explored.

The BCTPdb data files fall into two categories. The first category
are those files which work with the FoxPro® application to define
the relationships between the data; window layouts; and dialog
boxes. These files are updated by the system software engineer,
when required, to provide additional functionality to the database
or to correct software problems. An explanation of these files can
be found in the Data Dictionary.

The second category of files are those associated with the BCTP
data and are updated and/or loaded following the procedures
outlined in this guide. The loader, working closely with the analyst,
manages these files to fully exploit the relational capabilities of
the database. These files are organized both by WFX rotation as
well as across rotations and are entered after the data is received,
archived, analyzed and processed for loading.


---

   C. Conventions

   Before you start using the BCTPdb system, it’s important to
   understand the unique terms and typographical conventions used in
   the documentation. All standard WindowsTM conventions are
   complied with. Users should have a working knowledge of
_ WindowsTM to operate the BCTPdb system.

1. General Conventions

The following formatting conventions used in the text identify

special information.

         Formatting                Type of Information
         Convention
                      Step-by-step procedures. You can
Arrow bullet (=)
                      complete procedural instructions by

                      using either the mouse or the

                      keyboard. To choose a command from

                      a menu you can use the mouse or

                      press shortcut keys.

Underlined type       Words or characters you type or
                      select. For example, if the guide
                      instructs you to type cd bcdb you type
                      the letters “cd” followed by a space
                      and the letters “bcdb.”

Bold type             Dialog window names and option
                      buttons or selectors.


---

ltalic type      Specialized terms, notes, or tips.
                 Titles of other BCTPdb documents.
                 Placeholder for items you must
               | supply, such as filenames. For
                 example, when the guide says to type
                 cd bcdb_name, you type the letters
                 “cd” followed by a space and then the
                 name of a directory.

      2. Keyboard Conventions
All key names are shown in small capital letters. For example, the
Control key is shown as CTRL, and the Escape key is shown as

ESC.

     Keys      Comments

Shortcut keys  Keys are frequently used in

               combinations or sequences as shortcut

               keys. For example, SHIFT+F1 means to

               hold down the SHIFT key while pressing

               Fl, and ALT, F, A means to press and

                                           release each of these keys in order.
RETURN key and ENTER These keys usually perform the same

key            action. “Press ENTER” means that you

               can press either ENTER or RETURN

               unless specifically instructed otherwise.

                                                 1-6


---

      3. Mouse Conventions
You can use either a single-button or a multiple-button mouse with
the BCTPdb system. Descriptions of mouse use are characterized
by the terms: point, click, and drag.

     TM Point means to position the mouse pointer until the tip of
     the pointer rests on whatever you want to select on the screen.
     TM Click means to press and then immediately release the
     mouse button without moving the mouse.
      = Drag means to point and then hold down the mouse button
      as you move the mouse.


---

SECTION2

                         II. GUIDED TOUR

The reader will be introduced to the applications used to prepare
documents and load the database in this section. It is not intended
to make the loader or analyst an expert user, but rather to simply
introduce the applications and their uses. Detailed information on
how to use applications will be provided in Section 3 - Pre-
processing Procedures, Section 4 - The Loading Process for
Rotation Data Tables, and Section 5 - The Loading Process for
Good Ideas and Trend Tables.

There are two types of programs used in the loading process; those
that prepare data for loading (pre-processing) and the actual
database (loading and user) application. Both types will be
introduced in this section.

>» Pre-processing applications consist of the following:
      ° TextBridgeTM OCR
      ¢ The Norton Desktop Editor
      * Paint Shop ProTM, and Envisions TWAIN application
      * Loadvdeo
      ¢ WordPerfect®

> The Loading and Database User application is Microsoft®
 FoxPro®.


---

A. Pre-processing Applications

Three of the Pre-processing applications are used primarily to
convert hardcopy documents into digital formats so that they can
be loaded into the Database. The applications, their icons as they
appear on the desktop, and a short description follow:

Figure 2-1  ¢ TextBridgeTM OCR is an OCR (optical
            character recognition) program used to
            convert image data into usable text files.
            Detailed information on its use is found in

            Section 3, page 3-6.

Figure 2-2  ¢ The Norton Desktop Editor is used to
            clean up the text files produced by
            TextBridgeTM, since OCR software does
            not produce a 100 % faithful reproduction
            of original documents. Detailed
            information on its use is found in Section

            3: Page 3-9.

Figure 2-3  ¢ Paint Shop ProTM, and the Envisions
            TWAIN application are used together to
            scan graphics and documents that are not of
            good enough quality or correct type to use
            the OCR software. Detailed information on
            how to use these applications is found in

            Section 3, page 3-11.

One application is used to prepare videotapes. The application, its


---

icon as it appears on the desktop and a short description follow on

the next page:

                * The Loadvdeo program is used to provide

                the coding that makes video tapes easy for

                users to use. Detailed information on

Figure 2-4      procedures for its use can be found in
                Section 3, page 3-19.

Word processing tasks are accomplished by using WordPerfect®.

Figure 2-5      * WordPerfect® is used to create documents
                that the loader or analyst generates, and on
                occasion is used to read files provided on
                floppy disks. Refer to the WordPerfect®
                Reference for details on usage.

                                                        2-3


---

B. Loading and Database Applications

The Loading and Database User application is Microsoft®
FoxPro®. It is represented by two different icons on the desktop,
depending on what function it is being used for. Icons and
functions follow:

            This is the icon that starts up the FoxPro®
            application, and is used for loading the db.
            Details on use of the application for loading
            are covered in Sections 3, 4, and 5.

Figure 2-6

            This is the icon that starts up the BCTPdb
            application. Details and instructions on the
            use of this application can be found in the
            BCTPdb Users Guide, and in sections 3, 4,
            and 5 of this manual.


---

SECTION 3

         IIT. PRE-PROCESSING PROCEDURES

Most of the data being loaded into the relational database requires
some kind of archiving type of pre-processing to make it capable
of being loaded or to make it easy for end users to access the data
in a relational manner. Hardcopy documents have to be digitalized
by a scanning process before they can be loaded. Video tapes have
to be reviewed and tagged using interfaces with video marking and
replay equipment before they are useful. And data tapes have to be
processed to extract the useful data and then downloaded into the
database.

Subjects that are addressed in this section are:
            > Planning: Sorting/Indexing
            > Loading the scanner
            > Scanning techniques for text
            > Scanning techniques for graphics
            > Video preparation
            > Data tape Preparation
            > Saving files
             > Creating Rotation Data Tables

                                                                                                                  3-1


---

A. Planning: Sorting/Indexing
Assuming that the data has already been marked, tagged and put

into envelopes during the archiving process, it still requires some
organizing to make the scanning process and subsequent loading
more efficient. A method that has proven to work well is to sort
documents by their sequential doctrinal organization, and then to
tag them using "post its". When tagging sections it is useful to tag
it using the file name that it will be filed under as it is saved for
retrieval. It is recommended that the loader create the directory and
sub-directories that will be used to save files, before proceeding
with scanning operations (see Saving Files on page 3-26). By doing
so, the loader has established a convention which will facilitate
saving files as the last step of the loading process. File names can
be descriptive or as simple as using sequential numbers to maintain
the document order. Each section is then scanned and saved as a
file for retrieval during loading. While sorting the document, it is
helpful to separate or at least mark those parts that will be scanned
as graphics. Graphics are scanned using different software than
text and are filed and retrieved differently than text. Each graphic
is created and stored as a separate file, while text files are limited
more by how much different information can be effectively
managed within a file. Because a page may contain text and a
graphic, it is sometimes necessary to scan that page twice, using
two different procedures.

An example: An OPORD consists of the basic order, annexes,
appendixes, and tabs. If you scanned the entire text portion of the


---

order into one file, it would be too big to easily manipulate during

loading. However, if you break the order out into its basic sections,
the basic order, the annexes, appendixes, and tabs, it becomes easy
to work with. Using this method, an OPORD would end up being
around sixty files. File naming should be kept simple to save
keystrokes and time. See Saving files, in this section, for more
information.


---

B. Loading the Scanner
All hardcopy documents have to be digitalized before they can be
loaded into the database. This is accomplished by scanning.

Operating a desktop scanner is very similar to using a desktop
copying machine. At present the Envisions ENV6100 desktop
scanner is being used to accomplish this task. The scanner is
equipped with an Automatic Document Feeder (ADF) giving it the
capability to scan up to 25 pages per loading or to scan single
pages one at a time. Depending on the document, both capabilities
will usually be used during document scanning operations. This
section provides basic instructions extracted from the Envisions
ADF Operation Manual on loading the ADF and loading single
documents one at a time. For more detailed information on the
scanner and its operations refer to the Envisions Color Scanner
Reference, ADF 30 OPERATION MANUAL, Chapter 4, Operation.

                   1. Loading documents using the ADF
Most text documents will be scanned using the ADF. Step by step
procedures follow:

1. Make sure that there is no paper on the window glass of the flat-
bed scanner before using the ADF.

2. Straighten any curls or wrinkles and remove staples, paper clips
or other material from the documents.

3. Place the documents facedown on the Paper Guide Plate, with
the top of the pages feeding into the scanner first. The bottom page

                                                                                                               3-4


---

will be the first page scanned.

4. Adjust the side guides to fit the document, make sure the ADF
is closed, check to make sure the READY LED is on, and begin
scanning following the procedures that follow in Scanning
techniques for text.

           2. Loading single documents

All graphic, hand written, and other documents that do not convert
well during OCR processing will be scanned as single documents.
Step by step procedures follow:

1. Remove the Paper Guide Plate, it is not used in this operation,
and gets in the way.

2. Open the ADF cover.

3. Place the document facedown on the scanner window glass, with
the top of the document pointed towards the frount of the scanner
(for portrait documents) or pointed towards the left side of the
scanner (for landscape documents). This is exactly like loading a
copy machine for single page reproduction.

4. Close the ADF cover, and begin scanning following the
procedures that follow in Scanning techniques for graphics.

                                                                                                                  3-5


---

C. Scanning Techniques for Text
Text scanning is accomplished using the TextBridgeTM application
and the Envisions scanner. For detailed, in depth information, refer
to the TextBridgeTM OCR for Windows User's Guide. Basic step by

step procedures with standard default settings follow:

1. Load the document to be scanned (don't exceed 25 pages) into
the scanner, following the procedures described above for the ADF.

2. Click the TextBridgeTM icon       rh TestBridae

 found on the desktop. This

will bring up the Main dialog

window. See Figure 3-1.

input From                                          Gol      |

© Bile                          Vil                 Cancel

@ Scanner                                                 -

                                                       Exat

    02 Preview                       Preferences...
   CD Save Page Images
                                                    Help     ]
Status
 Scanner detected.                                     —

 English language loaded.                           About..

            Figure 3-1

                                                             3-6


---

3.The default for Input From, is Scanner, so go on to selecting
Preferences by clicking Preferences. This will display the
Preferences dialog. See Figure 3-2.

              S|

              P Document Quality      OC Auto Page Segmentation

                @ Standard

                   O fax              0 Ignore Photos/Halfionss

              Page Orientation

                   @ Porat                       ox

                   © Landscape        “[Seraner Stings]
                                       a
Click to set   cue                IE

scanner       f Language
preferences   a

                          Figure 3-2

4. Once you set Preferences, they will remain as the default until

they are changed. Default settings from top left to bottom right are:

Document Quality: Standard - unless the document is poor

quality, like a fax. If its poor quality select Fax.

Page Orientation:         Select as appropiate. If mixing Portrait and

                          Landscape select Auto.

Language:                 English.
Auto Page Segment:
                          Select if the page/s has more than one

                          column.

Ignore Photos/Half: Select if document contains photos, tables,

                          or art work. They will not OCR, and slow

                          the OCR accuracy and speed.

5. Next, click Scanner Settings. This will display the Scanner
Settings dialog. See Figure 3-3.

                                                                 3-7


---

                 DD Use Astomatic Document Feeder                   Coo
                                                                    = :
Set brightness   r Brightness  Otighter  ODarker        OAs
                                                                    (rete
te optimize OCR   @[Nonmeal]

                 r Resolution               Page Size

                  [esxano      Is]

                                            Figure 3-3

6. Settings for Scanner Settings are:
Select Use Automatic Document Feeder.
Select. Auto for Brightness.
Resolution: 300X300
Page Size: As appropiate, usually Letter.

7. Click OK to exit each window in reverse order, back thru the
previous screens. See Figures 3-2 and 3-1. The final Window will
be the Main dialog Figure 3-1.

8. Click GO to begin the scanning and recognition process. The
page(s) in the scanner are scanned and recognized until the Add
More Pages dialog appears. See Figure 3-4.

Q  Add more pages to the scanner                        (Continue!

   and click Continue                                       End

   Or click End # you are done                             Help

                  Figure 3-4


---

9. To continue scanning into the current file, add more pages to the

feeder, then click Continue. To end scanning click End. When End
is selected the Save As dialog appears. See Figure 3-5.

Fila Name:             Dicoctoras:
[Emil               ] ete
about.wal           rs ex           *

open.nil               om

                    +

Save File as [ype:     Driyes:

i] [=<                              Hy

                       Figure 3-5

10. Specify the file name, destination disk (C), directory and sub-
directory. Also specify ASCII-SmaTrXtT. as the output text format,
using the Save File as Type pop-up menu. Then click OK to return
to the Main dialog, to continue scanning or Exit.

11. The last step in text scanning is cleaning up the text file.
Depending on the quality of the document being scanned, the OCR
program will recognize from 92 to 98 percent of the text characters.
It will also recognize text found in graphics and leave it in the file.

These excess text characters and text that was not correctly

translated generally needs to be cleaned up to make the file
reasonably usable. Steps in clean up are:


---

a.Click the  {f,

                        js  es se

Desktop Editor

icon.

                  Editor.

b. From the menu bar click File. This will open a pull down
menu. From that menu click Open , which open the Open
File dialog. Follow normal Windows conventions and
standard word processing procedures to retrieve, edit, save
and exit the file and the Desktop Editor.

c. The text file is now ready to be loaded into the database.
See Loading Procedures for Scanned Documents, found on
page 4-3 of Section 4.

                                   3-10


---

D. Scanning Techniques for Graphics
Graphic scanning is accomplished using the Paint Shop ProTM and

Envisions interface application and the Envisions scanner. Basic
step by step procedures with standard default settings follow:

1. Load the scanner with the document you wish to scan, following
the instructions found in "loading single documents" in this section.

2. Click on the         ¥.
Paint Shop icon         *
found on the desktop.
                          =_=
The Paint Shop Pro
                        Paint ofioe

dialog and menu bar

will be displayed. See Figure 3-6..

   File Edit Yiew Image Colors Capture Windew Help

|                    [                              f  Free: 17015K

                        Figure 3-6

                                                       3-11


---

3. Click File and the File dialog will pull down. See Figure 3-7.

                       fie Esk          View      image
                         Open...                               Cuiet

                                Deicte                 Cries
                                                       Get

                                Arguite...
                                Select Source...

                                Brin...
                                Printer Setup...

                                Batch Conversian...
                                Preferences

                                Ext

                                1 Shed bVendagdi.wps

                                Figure 3-7

4. From the File dialog Click Acquire and the Envisions dialog will
be displayed. See Figure 3-8.

al                                                                            G                vi*

 Elle  Settings Mode Image info                                       ofe tilte i tid ti teid

       RISA AlZ                                                       ~
                                                                      2~
       | {Line Art                                vj                  3*
                                                                      ~
       7 | Reflective ~ J                                             =

       EF (309 dpi                                vj

       el [100%                                   v |

       f CN) 245

       f a) 5

               (e]

             Eos
       © aE)

       Preview Scan                     Cancel

       image Size:              §5 KBs
       Avail. Memory:           13064 KBs

       [Envisions TWAIN Source

                                                  Figure 3-8

5. Scanning preferences are set using the Envisions dialog. Set
preferences as follows:

      a. To set for color or black and white scanning, click and drag

                                                                                                                   3-12


---

     on the top pull down menu labeled Line Art in Figure 3-8.
     Keeping the mouse button depressed, scroll thru the selections.
     When the option you want is highlighted, release the mouse
      button.

           Select Color if the graphic is color.
           Select Line Art if the graphic is black and white.
     b.The next pull down menu should be set to Reflective, using
     the same procedures described above.

      c.The next pull down window should be set to 100 dpi.
     d. The bottom pull down window should be set to 100 %.

6. Next, click the Preview button. The scanner will scan the
document in a display mode. Once the scanner has completed the
initial scan, it will display an image in the right hand viewer
(outlined with the rulers). Using the mouse, click and drag to
adjust the sizable cropping lines until the portion of the document
you want to scan is outlined inside the cropping lines (This
procedure is similar to sizing any window in a windows
application.) See Figure 3-9 on the next page.

                                                                                                                3-13


---

|       aed                                             Q                      vi +
 Eile  | Settings Mode image                        of Pe det te t T et
                              info
               Nazi

             My [Line art     7| :                             Paint Shop Pro

             Sey [Reflective  v | i:
             $22 [100 epi     an

             ce) [100%        | :

             2 Ca)                                  '

             - —:)                                  ‘

             % GCIs6
             © z:)

       Preview Scan           Cancel

       image Size:         76 KBs
       Avail. Memory:      13064 KBs

       [Select (0.42, €.50}17-38, 9.45) 6.56x 8.96

                              Figure 3-9

7. Click the Scan button and the image inside the cropping lines
will be scanned.The scanning process is complete when the Paint
Shop Pro dialog is again displayed, with a window that shows your
scanned image. See Figure 3-10.

-                .                  "Paint ShoPpro                             TT

 File  Edit  View   Image  Colore Capture Window               Help

                                              New 4.bmp (1:1)


---

8. Now you will use the Tools box. See Figure 3-11. Since the only
tools needed for this operation are the Arrow and Magnifying
Glass, that is all that will be addressed in this section. For detailed
information on all the Tools, see page 2-8 in the Paint Shop Pro
Users Guide.

a. The Arrow Tool is the default selection         %IQ

of the Tool Box. It gives you the                        ——.

arrow cursor used to point and                           !  J

                                                   — —

select various options. There is                   Lest

no operation of the Arrow Tool              Figure 3-11

other than its use as the default cursor pointer.

b. The Magnifying Glass Tool is used to increase or decrease
the zoom factor of an image display. You use the Tool by
clicking the Magnifying Glass in the Tool Box. Move the
cursor pointer to the area of the image that you want to
increase or decrease. Click the left mouse button to increase
magnification and click the right mouse button to decrease
magnification. Each time you click either button over the
image, it will increase or decrease in size, depending on which
button you clicked.

9. Once you have checked your new graphic, it is time to make
adjustments to the default values that Paint Shop Pro uses. Using
the menu bar click Colors. This will display a pull down menu.
From that menu, click Decrease Color Depth, and a second pull
down menu will be displayed. Decrease Color Depth now. See
Figure 3-12 on the next page.

                                                               3-15


---

-                                                                                                  ”

Eile Edit View Image                Beut     Capture Window  Help
.
                                 Brightness{Contrast...                                            Py pt

                                 Gamma Correct...                                                      c

                                 Grey Scale                                           Tools

                                 HighlightShadow...                                      Q
                                 Negative Image                    ,
                                                                                     & am
                                 Red/GreenfBluc...                                          kot

                                 Sofarize...

                                 Edit Palette...                                              tof

   File | wvcrice-                                                    Image

                                 Count Colors Used

                                          2       or Dep     alo            B

                                 increase Color Depth        16 Colors...   (4 Big
                                                             256 Colors...  (8 Bit}
                                                             22K Colors...  (15 Bid
                                                             B4K Colors...  (16 Big

                                                             XColors... (8 Bid

+                                                                                                                      +
                                                                                                             +
[image: 1825 » 1400 x 16 Milion  f                                    Image: 7486K
                                                                                     Free: SISK

                                      Figure 3-12
Desired Setting are:

    a. For color graphics click 16 Colors.
    b. For black and white graphics click 2 Colors.

10. Now, click File from the menu bar. Once again the File dialog
will be displayed (refer to Figure 3-7). Click Save As and the Save
As dialog will be displayed. See Figure 3-13 on the next page.

                                                                                                                          3-16


---

=|     Edit View        Image  Colors    Paint Shop Pre    Help                             vfs

 Elle     —                            Capture Window                                  woe

  =                                        3-19 WG 11-1)                               [T=]
                                                                                                 s
Sc        File Name:                       Diwectories:
    hand  5-12 wea]                        :\bedb\oadngd                                        bad

    Elle

had ‘Lwpg                              4] fGen                   +
          zees
                                           © bedb
        poe
                                           & loadnad
              #11 wpg
               312 wpg

            3-2.0pg
            3-3.wpg

          List Filet of Type:              Drives:

          |WPE - WordPerfect           [3] | iat c: ms-dos_6     i+]

          File Sub-Format.

          [Vertion 5.1                 il

                                     increase Color Depth     16 Colors...   (4 Bit}
                                                              256 Colors...  (8 Bit)
                               |                              32K Colors...  (15 Bit)
                                                              84K Colors...  (16 Big

 ef «                                                                                        4
                                                                                       »
limage: 640 x 480 «2
                                                                 Image: 37K            Free: 16832K

                                       Figure 3-13

11. Save the file. Entries starting at the top left are as follows:
     a. File Name: Specify the file name.

     b. List Files of Type: Click the arrow for a pull down menu.
      Click TIF- Tagged Image File Format. This will cause the
     File Sub-Format selection to display. Click the arrow and click
     LZW Compressed, if it does not display as the default.

     c. Check to make sure Directories: and Drives: are indicating
     the proper file storage locations and click OK. This will return
     you to the Main dialog, where you can repeat the process or
     Exit from the File dialog.

     d. The graphic file is now ready to be loaded into the database.
     See Loading Procedures for Scanned Documents, found on page
     4-3 of Section 4.

                                                                                                     3-17


---

E. Video Preparation
Video tape preparation must be done by a military analyst familiar
with operational terms and graphics and Division and Corps
operations. Preparation is accomplished by the analyst watching the
tape and making notes and then using the LOADVDEO marking
interface application to create the tape file. Step by step procedures
and defaults follow:

1. Load the tape. Make sure the tape is fully rewound and that the
time counter on the VCR is set to 0. Start the tape, using the VCR
controls. The tape should be reviewed to record the time segments
of the different BOS and other categories that will be used to recall
specific portions of the tape. The 10 topics that the tape segments
will be broken out into are:
Battle Description
Maneuver
Fire Support
Air Defense
Command & Control
Intelligence
Engineer
Combat Service Support
Opposing Forces
Other

As the tape plays, note the start and end times of the tape segments
for each topic area. This information is displayed on the VCR
tape/time counter. Topics will often overlap. This will present no
problem, as long as accurate notes are kept. You should also be
recording any keywords, acronyms, and other notes that would aid
in describing that section of tape.
To recap; the military analyst needs to know the following:

                                                                                                                3-18


---

> What topics were discussed.

> The start points where each topic was discussed.

> The end points where the topic discussion ended.

> Keywords, acronyms, phrases that help describe what was
discussed, and that an analyst might use to retrieve that
conversation.

2. After the tape has been reviewed and notes recorded, rewind the

tape back to the start, and make sure the tape counter is reset at 0.

Click the

Loadvdeo icon

found on the     ‘Loadvdeck

desktop screen.

This will display the VCR Tape Reference Identifier dialog. See

Figure 3-14.

Archive Reference Id:        Data Source:

  |

Data Name:

  |

        Vf «

                                            Figure 3-14
3. Enter the proper information for the three data fields as follows:

                                                                                                                3-19


---

Archive Reference Id:       Enter the archive reference ID code
Data Source:
Data Name:                  found on the video tape. See Appendix

                            F, Archive Reference ID Codes, for
                            coding information.
                            Enter the name of the event that the tape
                            has recorded. See Appendix C, Standard
                            Loading Conventions, of this guide for
                            standard names.
                            Enter the name of the tape. See
                            Appendix C, of this guide for standard

                            names.

4. Click OK and the Mark VCR Tape Topics Interface will display.a
See Figure 3-15 page.
                       p y
                                             Mark VCR Tape Topics
                                                 Current Time: 00:08:00p y

                      Enooep y

                  Topicy y  OOOOOCoOoo
           __! Battie Description
           _| Maneuver

        _ Fire Support

          _]| Alt Defence
          _| Command & Control
           _| Intelligence
           _] Engineer
           _]| Combat Service Support
           _] Opposing Forces
           _J Other

               vx

                                Figure 3-15

                                        3-20


---

This interface displays the tape time, controls the VCR, and is used

to save data for each segment of tape as it is tagged by topic. The

tape time is displayed to the right of Current Time: where

00:00:00 is shown in Figure 3-15. The VCR control buttons are

like the standard home VCR, except you press them by clicking on

them with the mouse. The VCR buttons from left to night are:

Rewind, Stop, Pause, Play, and Fast Forward.

[<< J [o | Li}  In this illustration, the stop

                button is selected.

To start the videotape and the tagging process click the Play

button. Topics are selected by clicking on the check box to the left

of them, and deselected by clicking on the same check box again.

Each time a Topic check box ts selected the Start Time box to the

right of it displays the time of the tape (this is assuming that the

play button has been clicked on). When the same Topic check box

is deselected by clicking on it again, the Stop Time box displays the

current tape time, and the VCR stops playing. The Segment

Number box displays the sequence number for how many times

that Topic has been selected and deselected. In other words, the

first time a Topic is selected and then deselected, the Segment

Number is 1; the second time is 2; and so on. Each time a new

sequence number is displayed, a new record is created that

associates that time on the tape with a text memo field that is

created using the Comments dialog. This dialog is displayed

whenever a Topic is deselected. See Figure 3-16.

                                                  3-21


---

                        Comments

Operational Timeframe:            OpType:

Comments & Keywords:

                                                  L_|»

         — « yo ? Help

         Figure 3-16

5. Enter the proper information for the three data fields as follows:

Operational Timeframe: Enter the appropriate timeframe for this

                        segment, if you can associate it with a

                        timeframe in the actual operation (ie:

                        Phase I). See Appendix C, of this guide

                        for standard names.

OpType:                 Enter the appropriate operations type for

                        this segment, if you can associate it with

                        an operation (ie: Attack). See Appendix

                        C, for standard names.

Comments & Keywords: Enter the comments and words that

                        describe this segment of tape and the

                        topics discussed (ie: Topic is Intelligence

                        BOS. Subjects = BDA, sharing intell

                        information, LRSD, etc.)

                                                        3-22


---

6. Click OK and the Mark VCR Tape Topics interface will be
displayed again (See Figure 3-15). Repeat the procedure in step 4
and 5 (see Figure 3-16) until the entire tape has been completely
run and all segments filed. When you have completed tagging the
tape, click OK at the bottom of the Mark VCR Tape Topics and the
application will close. An important note is. if you click Cancel
while using the Mark VCR Tape Topics dialog screen all data will
be lost. This will require you to start this process all over again,
from the beginning. You can click Cancel while using the
Comments dialog. Doing so closes out the comments dialog without
saving the current entry, and returns you to the Mark VCR Tape
Topics dialog.
7. There are no file saving steps to complete in this application.
The Video files are ready to be loaded into the database using the
Loading Procedures for Video Tapes, found in Section 4.

                                                                                                             3-23


---

F. Data Tape Preparation
Data tapes, which contain the objective data, are currently prepared
by the project programmer. What follows is the current status for
preparing data tapes for loading. It has been written assuming a
stable system, both in terms of the input files and the table
structures which will be filled. It presumes that the conversion

programs have been written for each kind of objective data wanted,
that the FoxPro tables which will contain the objective data have
been designed and implemented, and that the format of the input
objective data is stable. In fact, the BCTP environment has been
evolving rapidly, which will probably require several changes be
made before full operational status is achieved.

Preparing and loading objective data into the BCTP Prototype
Database consists of the steps, as shown in Figure 3-17:

Load Data from Tape
                    Host Computer

 \Y

Rename consolidate files           Pc

Transfer Flie(s] to PC             > Transfer Flie{s] from Host  1

                                       Run Conversion Program    2

                                       Load Table                3

                          Figure 3-17

Step 1. Retrieve the data from its source to a compatible host,
rename/ consolidate files as necessary, and transfer ASCII files to
a PC.

                                                                    3-24


---

Step 2. Use the specific conversion tool to convert/ extract the data
from the ASCII files to FoxPro compatible comma delimited files.

Step 3. Fill the relevant FoxPro tables (see Section 4. Loading
Rotational Tables).

Steps 1 and 2 are described in detail below. The specific
commands used for a representative sample are shown within the
text (in bold italics). The example shown involves converting the
Blue Combat Attrition WAARS Report, which was created on a
VAX, to the B_CBTATT table for one rotation. Portions of the
input and intermediate files from the 41D Blue Combat Attrition
Report, followed by the ASCII text file for the same page of data
was used to build C:\BCDB\93DHHA01\B_CBTATT.DBF.

      Step 1. Retrieve the data from its source to a PC
      BCTP objective data are generated either on a SUN
      minicomputer or on the VAX which hosts the CBS model. The
      data must first be read from tape (SUN cartridge or VAX reel)
      into a host computer compatible with its original computer.
      Then the data must be transferred to a PC to transform the
      original data from its native format into a format which will
      facilitate its conversion into a FoxPro table. This initial process
      will consist of the following steps:

            (1) Restore the data from the backup tape to the host
            computer. The command shown is specific to the VAX.
            Some variation of the tar command must be used to restore
            SUN files.
             BACKUP/LOG MFA0:4ID.BCK/SELECT=CBATIR_BLU.OUT [.BCTP...]

                                                                                                             3-25


---

(2) Consolidate the files from all time periods (there were
15) into one file named consistently with PC requirements.
The initial file names consist of 10 character plus a 3-
character extension. Further, there were 34 identically
named files in different subdirectories. This step copies all
the 34 files into one file which may be transferred over to
a DOS-based PC file with the same name.
COPY [...]CBATTR_BLU.OUT CBATTR.ALL

(3) Now the 34 files have been consolidated into one file
which may be transferred to the PC. The file is transferred
using an FTP (File Transfer Protocol) transfer from one
computer to another. In general the transfer 1s controlled
from the PC using the following commands. A short
description of each command is included.

Command         Description

FIP             Start FTP program on PC
O VAX           Access FTP server on vax computer
A               Indicate ASCII file transfer is desired
CD [.BCTP]      Change to directory containing cbattr.all
LCD \BCTP       Change PC directory to receive file
GET CBATTR.ALL  Transfer the file
BYE             Terminate FTP session

Step 2. Use the relevant conversion tool to convert/
extract the data
A specific data conversion program will be available for
each unique objective data source. Conversion programs
have been written in Turbo Pascal and must be executed in
a DOS environment (or DOS window). The conversion
program serves three purposes:

                                                                                                   3-26


---

(1) It filters the BCTP data to eliminate unwanted and/or
redundant data.
(2) It reformats individual data elements to make them
consistent with elements in other BCTP tables to allow
relating different tables.
(3) It collects the data into lines of text which correspond
exactly to records in the table format defined for that data
source, adding appropriate punctuation to facilitate the
loading process.
The conversion program will generally require two inputs,
the data path and name of the input file(s) transferred to the
PC from the SUN or VAX, and the data path and name of
the output file which will be used to load the FoxPro table.
The command line which builds the input file for the
Combat Attrition table is:
CBTATT C:\CBTATT.ALL C:\BCDB\CBTATT.TXT

                                                                                                3-27


---

 G. Saving files

It may be helpful to address the subject of saving files, since it is
the last step in the process of text and graphic scanning. This
section is being written with the assumption that users already
know how to create directories, sub-directories, and files in a
WindowsTM- Norton Desktop environment. How to perform those
functions will not be addressed. What will be addressed is the
current file structure being used now. This information is being
provided so that there is a standardized structure that will allow
anyone to find specific files quickly.

The current method being used is to create sub-directories under
c:\bcdb for each unique WFX's files and then to create sub-
directories within that directory for each document to be loaded.
Individual files are then saved under their appropiate sub-directory.
For example: The basic OPORD for the 69BDE of the 35 ID was
saved as 1.txt; Annex C (4 pages) were all graphic files, so they
were saved as:c.tif,c2.tif,c3.tif and c4.tif; and Annexes A and B
were text files, so they were saved as a.txt and b.txt. The path for
these files is:

            e:\bedb\35id\69opord\<filename>. See Figure 3-18 for a
            picture of the directory/sub-directory/file structure.

Gen                         sit.            [)¢3.cat    [ej t-exc
    CG) bea                         Lite    [ie4-cit    E) g-cxe
         (2) sia                                        Dyo2..cir
                                Baca            d. txt  (}s22z.cie
              ( aarz                                    ['] 923. tie
              Ccorpera)        Bp. exe      Dje-cit     () o2z4.cat
                Cjdivoptay      Fite        fi) «.txe
                                FD} c.cit               Di g2s.cit
                                                a2.txt
                                PC} c2.cit  (et-cat                      rs

Cy ter she] |

                            Figure 3-18

                                                        3-28


---

Additional information to keep in mind is:
     ° It will save time, during loading, if all directory and file
     names consist of as few characters as possible. Each graphic
     file will have its' entire path typed into a field during loading.
     * The current OCR software only allows about 50 pages in a
     text file, so you will want to consider that limitation as you
      scan and save text files.
     * Text files can be deleted, after loading into the database,
     (however they take up so little space that it is probably worth
     the time it would take to do it.)
     ¢ Graphic files must remain saved in their directories/sub-
     directories, because the database application searches for them
      by the path they were saved into.

                                                                                                             3-29


---

H. Creating Rotation Data Tables
Before you can load data for a rotation, you must create a Rotation
Data Table, using the FoxPro® application. This involves three
steps: Creating a new record in the Rotation Table, Adding a new
rotation sub-directory to the db, and creating an empty Data Table

for the new rotation. Step by step procedures follow.

Step 1. Creating a new record in the Rotation Table.

From the FoxPro® start-up screen, select File, by clicking on File
from the main menu bar. This will activate a pulldown window,
from which you select Open, by clicking on Open. This will
display the Open dialog box ( See Figure 3-19).

  File Edit Database Heeard Program Aun Text Window Help

              : |resuls.dbf

                  List Files of Type:

           : [Table/DBF

                                           Figure 3-19
Follow these steps:

      a. From the Directory selections (middle of box), double click
      on c:\, then double click on bedb.

                                                                                                                3-30


---

 b. In the List Files of Type: (bottom Left of box) Table/DBF
should be selected.

c. From the File Name selections (Left side of box), double
click on rotation.dbf. This will cause the dialog box to
disappear and the start-up screen to reappear with the
Command dialog box displayed. (See Figure 3-20)

d. From the Main Menu Bar, click on_Database. This will
display a pull-down menu.

e. From the pull-down select Browse. This will bring up the
Rotation Table. See figure 3-20 below.

Fille  Edit  Database  Record          Microsoft FoxPro  Window  Help
                               Program Run Browse

                                                                       Command
                               USE ¢s\bedb\rotation.dbf EXCLUSIVE
                               BROWSE LAST

       SSOHHANT [83-9  06/19/93 06/23/93 | Korea   8     Active  N     40)
                                                                       3D
             23-10     08/08/93 |08/13/93 Germany  A             v     DQ)

       SSDLHADT 1938   07/05/93 | 07/10/93 jKorea  A     Active  N     410M)

             :                                     B             N

  } ESI                        Exclusive                                        .
                                  Figure 3-20
Rotation Record 4/4                                                    |Tins fNum [

f. To Create and load the new record follow these steps:
      1). Use the key combinations Ctrl + N to create an empty
      record.

                                                                                3-31


---

            2). Then fill in the fields, bulleted below for each new
             record:

                  * Rotcode - Rotation code: Use Appendix F, Archive
                  Reference ID Codes for instructions.

                  For the rest of the fields, use the FER to extract the
                  appropiate data. Choices (underlined) follow the field

                            name.

                   * Rotid - Rotation Number assigned by BCTP
                   * Rotstart - Rotation Start Date:
                   ¢ Rotend - Rotation End Date:
                   * Rotloc - Rotation Location: Korea, or Germany, or
                   SWA, or LIC-LatAM
                   * Betpteam - BCTP Team:_A_or_B at present.
                  * Component - Active or Reserve: Loader must know
                   Active/Reserve units
                   * Restart - Yes(Y) or No (N): Extract form reading the
                   seven minute War.
                   ¢ Unit - Unit name from FER

Step 2. Add the Rotation Sub-directory (Rotation Code) to the
bedb directory.

Using the Rotcode or Rotation code (see figure 3-20) that was
created in step 1 above, create a new sub-directory under c:\bcdb.

For example, the new sub-directory for the fourth record in the

Rotation Table at Figure 3-20 is 94dhha01. So, the directory/sub-
directory path would be: c:\bcdb\94dhha01.

                                                                                                             3-32


---

Step 3. Create an empty Data Table for the new Rotation.

Going back to the FoxPro® start-up screen, select Window, by
double clicking from the main menu bar. Then select Command
Ctrl+F2 , by double clicking, from the pull-down menu.
This will bring up the Command Box, as shown in Figure 3-21
below.

Edit Database Record Program Aun Text  Help

                                     ISE cz\bedb

                                                             BROWSE LAST
                                                             use c:\bcedb\9adhhatt\dadtbaf

                                          Figure 3-21
Type, in the Command Box, the following lines, as shown in
figure 3-21:

      use _c:\bcdb\93 dhha01\data. dbf
      copy structure to c:\bcdb\the rotcode from step 2\data.dbf
Now type, pack and press the enter key.

The new Rotation data record, sub-directory and data table are
created and ready to be loaded. Go to Section 4, The Loading
Process for Rotation Data Tables, for information on loading
procedures.

                                             3-33


---

Step 4. Check Your Work.
To verify that the new Rotation Data Table was created, exit the
loading program and enter the BCTPdb program. Select the
Research button from the BCTPdb WELCOME Screen. You should
be able to find the new rotation in the Rotation Selection Interface.
Leave the interface by selecting the OK button and allowing the all
default to remain active. From the investigation set click on the
new rotation number and press the Rotational Information button
to read and verify that data was entered correctly.

                                                                                                                3-34


---

SECTION 4

                Iv. THE LOADING PROCESS
              FOR ROTATION DATA TABLES

Once data has been processed into some kind of usable digital form
(see Section 3, Pre-Processing Procedures), it is ready to be loaded
into the database. This is accomplished by entering the data into
tables; either a Rotation Data Table, the Good Ideas Table, or one
of the three Trends Tables. This section will deal. with loading
data into Rotation Data Tables. Section 5, The Loading Process for
Good Ideas and Trend Tables, will address the Good Ideas and
Trends Tables.

Before data can be loaded for a new rotation, the loader must
create a new Rotation Data Table by following the procedures
detailed in Section 3, Creating Rotation Data Tables. Each rotation
has its' own unique Rotation Data Table which is identified by its'
Rotation Code (Rotcode). The Rotation Data Tables are the data
displayed when the Database user selects Research from the
BCTPdb Welcome screen.

Rotation Data Tables can usually be loaded by a trained, military
experienced, data entry individual working closely with a military
analyst, who provides analysis, guidance and assistance with quality

control (ie: laying out the doctrinal sequence for Unit Generated

Data, providing guidance when units do not follow doctrinal layout
procedures, and checking the data table for errors and consistency.
The analyst will also generate new products from the data provided
for loading.

                                                                                                                  4-1]


---

There are three different loading procedures which will
accommodate loading the various types of digital data. They will
be addressed in this section and are:

            > Loading Procedures for Scanned Documents

            > Loading procedures for Digital Data
                   ¢ Digital Tapes
                   ¢ Floppy Disks

            > Loading Procedures for Video Tapes - TBP when
           finalized.


---

A. Loading Procedures for Scanned Documents
In section 3, Pre-processing Procedures, the scanning of documents
and the subsequent creation of text and graphic files was discussed.
When loading these files into the data tables, there are some minor
differences in what is entered in specific fields, but on the most

part they are handled the same. Differences will be explained in
greater detail in Appendix C, Standard Loading Conventions. The
procedures for loading scanned documents follow:

1. From the FoxPro® start-up screen, select File, by clicking on
File from the main menu bar. This will activate a pulldown
window, from which you select Open, by clicking On Open. This
will display the Open dialog box. See Figure 4-1.

File Name:                                  Directory:                                                    i

|*.dbf                                 } on                                           fige

 a                                    =) SEX            a

List Files of Type:                     Tfbibeedtb      =   [CCaanncceel rJ

|Table/DBF                                (Mee              (C1 All Files
                                           (Jcedebase
                               eau                          C) Read Only
                                          (des
                                                                   Environment
                                         Cfoxpre2s
                                                                  Exclusive
                                    * Efpw
                                            Drive:          2 CI other Code Page

                                    |] |Getc: ms-dos_6  i]

                                                                           sceiaenensiaaatiaisnaaassaan!

                                    FoxPro 2.6 for Windows

                                    Figure 4-1

Follow these steps:
      a. From the Directory selections (middle of box), double click
      on e:\, then double click on bedb. Now scroll down the
      directories until the Rotcode for the rotation to be loaded is


---

found. Double click on the Rotcode (an example Rotcode is
94dhha01)

 b. In the List Files of Type: (bottom Left of box) Table/DBF
should be selected.

c. From the File Name selections (Left side of box), double
click on data.dbf. This will cause the dialog box to disappear
and the start-up screen to reappear.

d. From the Main Menu Bar, click on Database. This will
display a pull-down menu.

e. From the pull-down select Browse. This will bring up the
Data Table for the selected rotation. See figure 4-2 below.

 Eile Edit  Database Record   Program Rup Browse Window Help
              Dataname | Dal
bed                                    Data            {Order} Or  Destinatio          vie

_ Typaotd.                    Side] Medium | Filename                          | Timezent | ¢

Data        Record None       Exclusive                            [fins [Num
                                  Figure 4-2

Since the Rotation Data Tables are very large, it is difficult to
display the entire table at once. However, the fields are sizable, by
clicking on and depressing the mouse key at the field name
dividing lines. Hold the mouse key until the field is at the desired .

                                                                               4-4


---

width and then release the key. Use the scroll bars to scroll
vertically and horizontally thru records and fields. By adjusting the
field sizes and scrolling to the far right side of the table, the user
can view the rest of the table as displayed in Figure 4-3.

=                                      Microsoft FoxPro                  |>| *

 File  Edit  Database     Record  Program Run Browse      Window   Help
                                                           Bobref
=                                 Data                                                                vie
                                                                   Battleloc | Oeg [Data| |+
Timesent | Timerecvd | Opnitimirm | Optype [Analeval| Cp

Data         Record None          Exclusive                              | [Ins [Num [-
                                        Figure 4-3

2. To Create and load the new record follow these steps:
            a. Use the key combinations Ctrl + N to create an empty
            record.

       b. Then type in or load the data fields, following the
       standard loading conventions found in Appendix C,
       Standard Loading Conventions.

3. To view the records with the fields displayed vertically rather
than horizontally follow these steps:

             a. Going back to the Main Menu Bar, click on Browse.
            This will display a pull-down menu.
            b. From the menu, click on Change and the table will be
            displayed as shown in Figure 4-4, on the next page.

                                                                         4-5


---

                                   Figure 4-4

An example of a completed record for Rotation Data Table
93dhha01 is shown as Figure 4-5 below.

a                                  Data        id

ypeofdata WARND 8                                  ES

Dataname DEEP ATTACK

Datasousce DIV FRAGO WE

ide  B

ptype DEEP ATK                                     a

     TA4 TAI                                         ;
                                               ies
     Memo

lTppeofdata FRAGO 1

Dataname D-DAY

Datarource DIV FRAGO 1

ide  B

   edium = = GRAPHIC

Honame = CABCDB\AIDSDFRAGALTIF

                                i
+

                                   Figure 4-5

                                                        4-6


---

   4. To return to viewing the records with the fields displayed
   horizontally, follow these steps:

               a. Going back to the Main Menu Bar, click on Browse.
               This will display a pull-down menu.
               b. From the menu, click on Browse (which will be
               displayed where Change was in the previous step) and the
               table will again be displayed as shown in figures 4-2 and
                 4-3.
5. The last step is to check your work. Do this by exiting the loading
program and entering the BCTPdb program. From the Welcome
Screen, select the Research button. From the Rotation Selection
interface make sure your rotation data file falls within the rotation
selection criteria, then, click on the OK button. If you have loaded
correctly, the new rotation data will be displayed in the data display
window as you select the appropiate selector button to view the new
data.

                                                                                                                     4-7


---

 B. Loading Procedures for Digital Data
 Digital data is the data provided either on digital tapes (form the
 CBS system) or on floppy disks (from the WFX unit, the OPFOR, or
 the BCTP team). Digital tape loading procedures are still evolving,
 but are provided to document their current status. Floppy disks are

 loaded into the data tables in the same manner as Scanned

Documents. However, there are some special considerations that the

 loader must be aware of, and they are covered in this section.

             1. Loading Procedures for Digital Tapes
 Currently, the Data tapes are prepared and loaded by the project
 programmer. This section is a continuation of the Data Tape
 Preparation process described in section 3. The example text files
 that were created in section 3 are input into the tables created earlier
  using the following steps:

     1. Open the empty table. If the table has not yet been created for
    the rotation being processed, it must be created by using the
    FoxPro COPY STRUCTURE command:
     USE C:\BCDB\93DHHAOI\B_CBTATT.DBF

     2. On the command line, enter:
     APPEND FROM<filename>DELIMITED
     where filename is the fully qualified name of the text file. This
     command will create one record in the table for each line in the
     input file. An example of a complete command is:
     APPEND FROM C:\BCDB\CBTATT.TXT DELIMITED

                                                                                                                    4-8


---

            2. Loading Procedures for Floppy Disks
The procedures for loading Floppy Disks data are the same as for
Scanned Documents (see page 4-3) provided the loader completes
the following steps:

1. Load the floppy disks document/documents onto the c: or
harddrive of the loading computer, following the procedures
described in section 3, Saving Files.

2. It is recommended that the files on the disk be converted, from
whatever word processing program was used to create them, into
an ASCH Smart text file, since FoxPro® will only read ASCII
files. An important note here is that tables, charts, and figures will
not convert well (if at all) into ASCII text files. Consequently the
loader must save them as graphic files, before converting the files
to ASCII. Two methods of creating graphics that have proven to
work well are:

            a. Print the pages containing the chart, table, or figure and
            then scan it to create a .tif file (see section 3, Scanning
            techniques for graphic files).

            b. The second method, which is usually faster, is to use the
             Print Screen capability of WindowsTM to copy each desired
            graphic to the clipboard, then to use the Paint Shop ProTM
            application to Paste the clipboard and create .tif files (see
            the Paint Shop ProTM — documentation for detailed
             procedures).

                                                                                                                 4-9


---

SECTION5

     V. THE LOADING PROCESS FOR GOOD
                  IDEAS AND TREND TABLES

This section was written separate from section 4, The Loading
Process for Rotation Tables, because the tables described here are
different and serve a separate purpose than those used for loading
Rotation tables. Rotation tables are specific for each rotation, while
the Good Ideas and Trends Tables are continuous, across all
rotations. Good ideas and Trends Tables are already created, and
exist as a continuous part of the database. Unlike Rotation Tables,
the analyst or loader does not create them for every new rotation.
As data from a new WFX becomes available, the analyst and/or
loader simply opens the existing tables and loads the data. The
Good Ideas and Trends tables are the data displayed when the
Database user selects Good Ideas or Trends from the BCTPdb
Welcome screen. They must be updated as each new rotations data
becomes available to keep the Trends data current, and meaningful.

The Good Ideas Table can usually be loaded by a trained, military
experienced, data entry individual working closely with a military
analyst, who provides analysis, guidance and assistance with quality
control. The analyst may generate new products from the good
ideas provided for loading, and from analysis of WFX materials.
The Trends tables should be loaded by a military analyst.

The Loading Procedures for the following tables are addressed in
this section:

            > Good Ideas
             > Trends

                                                                                                                   5-1


---

¢ Performance Trends (AAR Trends)            finalized.
* FER Trends
° Objective Data Trends - TBP when

 A. Loading Procedures for the Good Ideas Table
The Good ideas Table can be loaded by the loader, as its function

and procedures for loading are similar to the Rotation Tables. The
data field selections are similar to Rotation Tables, however the
path to the table and the standard loading conventions contain some
differences. Step by step procedures follow:

1. From the FoxPro® start-up screen, select File, by clicking on
File from the main menu bar. This will activate a pulldown
window, from which you select Open, by clicking On Open. This
will display the Open dialog box ( See Figure 5-1).

File Edit Database Hecerd Program Rup Text Window Help

: File Name:                Directory:

: rotation. dbf         ] s:\bedb\

: reports.dbf

: [results.dbf

_ [test2. dbf           ae                     CJ Bead Only

t typedata. dbf         i Drive:               2 Environment

:                       st} [asic: ms-dos_6    Bi] Exclusive

q: List Files of Type:                       3 O Cloter Code PPage

: [Table/DBF

                                              Figure 5-1

Follow these steps:
      a. From the Directory selections (middle of box), double click
      on e:\, then double click on bedb. Now scroll down the
      directories until support is found. Double click on support.


---

 b. In the List Files of Type: (bottom Left of box) Table/DBF
should be selected.

c. From the File Name selections (Left side of box), double
click on gi.dbf. This will cause the dialog box to disappear and
the start-up screen to reappear.

d. From the Main Menu Bar, click on Database. This will
display a pull-down menu.

e. From the pull-down select Browse. This will bring up the Gi
Table. See figure 5 -2 below.

om                                         Microsoft FoxPro                         =e
  File                               Program Run Browse
        Edit  Database       Aecord                          Window  Heip

                                                                           Command
                                     USE c:\bedb\support\dgbif EXCLUSIVE
                                     BROWSE LAST

.                                                                                   a

Rotcode jT.            Dai.  Datssowce Moda Fi      Sr rg _|Tmezent|Timere! Bobref |Data] 4

 SSDHHADT Description  [BDA TiackigGoodidea | TEXT           T4ANJu/neD19R 33:  TA2 TAS Memo’

                                               Figure 5-2

The fields are sizable, by clicking on and depressing the mouse
key at the field name dividing lines. Hold the mouse key until the
field is at the desired width and then release the key. Use the
scroll bars to scroll vertically and horizontally thru records and
fields.

                                                                                                               5-3


---

2. To Create and load the new record follow these steps:
             a. Use the key combinations Ctrl + N to create an empty
            record.

            b. Then type in or load the data fields, following the
            standard loading conventions found in Appendix C,
            Standard Loading Conventions.

3. To view the records with the fields displayed vertically rather
than horizontally follow these steps:

            a. Going back to the Main Menu Bar, click on Browse.
            This will display a pull-down menu.

            b. From the menu, click on Change and the table will be
            displayed as shown in Figure 5-3, below.

Rotcode S33DHHAOI                                BNUWOOC LHOE

Typeofdata Description  |

Dataname BDA Tracking

Datasource Good Idea

Medium TEXT

Filename

Order           1

Org       4/IN/DIV

Timesent June 1993

Timerecyd |__|

Bobref    TA2 TAS

Data      Memo

                                          Figure 5-3

4. To return to viewing the records with the fields displayed
horizontally, follow these steps:

            a. Going back to the Main Menu Bar, click on Browse.
                                                                                                                 5-4


---

               This will display a pull-down menu.
               b. From the menu, click on Browse (which will be
               displayed where Change was in the previous step) and the
               table will again be displayed as shown in figure 5-2.
5. The last step is to check your work. Do this by exiting the loading
program and entering the BCTPdb program. From the Welcome
Screen, select the Good Ideas button. From the Good Ideas Category
Selection interface select the OK button. If you have loaded
correctly, the new rotation code will be displayed as you scroll thru
the data records.

                                                                                                                     5-5


---

B. Loading Procedures for Trends Tables

There are three types of Trends Tables. They are:

   * Performance Trends (Taar.dbf)

      ¢ FER Trends (Tfer.bdf)
      * Objective Data Trends (TBP)
The Performance and FER Trends Tables should be loaded by a
military analyst, familiar with BCTP and current Army doctrine.
The Objective Data Trends are still in the development stage, and
are currently loaded by the programmer. The procedures for loading
Performance and FER Trends follow:

             1. Loading Performance Trends
The Performance Trends are extracted from the Sustain and
Improve slides found in the rotation FER (Final Exercise Report)
in the AAR section. An entry (record) is made into the
Performance Trends Table for every sustain and improve comment
addressed. These comments are coded by Rotation, BOS, and
Sustain or Improve. The steps used to load this table follow:

1. From the FoxPro® start-up screen, select File, by clicking on
File from the main menu bar. This will activate a pulldown
window, from which you select Open, by clicking On Open. This
will display the Open dialog box ( See Figure 5-1 on page 5-2).
Then follow these steps:

      a. From the Directory selections (middle of box), double click
      on c:\, then double click on bedb. Now scroll down the
      directories until support is found. Double click on support.


---

 b. In the List Files of Type: (bottom Left of box) Table/DBF
should be selected.

c. From the File Name selections (Left side of box), double
click on taar.dbf. This will cause the dialog box to disappear
and the start-up screen to reappear.

d. From the Main Menu Bar, click on Database. This will
display a pull-down menu.

e. From the pull-down select Browse. This will bring up the
Taar Table. See figure 5-4 below.

7                                                                            ri«

Hotcode |Bobref               Sustain                            improve          *
                                                  Current Opns vs. Planning
SBOHHACTITAd [Rehearsals                                                          I
                                                  information Mat
SSOHHAOLTA4 [UseofLNOs                            Sesing the Battlefield           +
                                                 C2 Tools
SSOHHACTITA4 [SF Integration                      Graphics                     *
                                                  FAIGASPS Integration
SOOHHAOIITAS                                     EW Integration                     i

SSDHHROTTAS                                       PIF Development
                                                  Use of IPB Products
SSDHHACIITAS | Counterinteligence Analysis
                                             ya
SBDHHADLITAS _ intel Spt to Counterrecom
                                            5-4
SGDHHAGTITAS — jAnalpsis and Situation Dev

SSDHHAOT TAS [Intel Spt to Deep Attack

SSDHHADIITAS {BDA

«

                              Figure

The fields are sizable (though probably not needed with this table),
by clicking on and depressing the mouse key at the field name
dividing lines. Hold the mouse key until the field is at the desired
width and then release the key. Use the scroll bars to scroll
vertically and horizontally thru records and fields.

2. To Create and load new records follow these steps:

                                                                             5-7


---

a. Use the key combinations Ctrl + N to create an empty
record for every entry to be made. Each Sustain or Improve
comment will become a new record.

b. Then type in the data fields for each entry as follows:
      * Rotcode: Rotation code: Use Appendix F, Archive
     Reference ID Codes for instructions, and enter for each
      Sustain or Improve comment. (ie: 93DHHRO1 is the
     Rotcode for the 35IDs' rotation from 1993).
     * Bobref: Using the Blueprint of the Battlefield, type a
     code for each entry that properly identifies the BOS for
     the subject addressed. The codes/choices (underlined)

         are:

            TAI: Maneuver
            TA2: Fire Support
            TA3: Air Defense
            TA4: C2 / Battle Command
            TAS: Intelligence
            TA6: Mobility and Survivability
            TA7: Combat Service Support
     ¢ Sustain: The individual bulleted sustain remarks from
      the AAR slides.
      ¢ Improve: The individual bulleted improve remarks
      from the AAR slides.
     A note on the sustain/improve remarks: Keep names
      short and constant. At times you may have to shorten or
      translate the comments into a category/comment that is
      used consistently, and means the same thing.

                                                                                                  5-8


---

3. To view the records with the fields displayed vertically rather
than horizontally follow these steps:

            a. Going back to the Main Menu Bar, and click on
            Browse. This will display a pull-down menu.
            b. From the menu, click on Change and the table will be
            displayed as shown in Figure 5-3, above.

4. To return to viewing the records with the fields displayed
horizontally, follow these steps:

            a. Going back to the Main Menu Bar, click on Browse.
            This will display a pull-down menu.

          b. From the menu, click on Browse (which will be

            displayed where Change was in the previous step) and the
            table will again be displayed as shown in figure 5-2.

5. The last step is to check your work. Do this by exiting the
loading program and entering the BCTPdb program. From the
Welcome Screen, select the Trends button. From the Trend
Selection interface select the Performance Trends by BOS button,
then press the OK button. From the AAR Trend Selection press the
OK button. If you have loaded correctly, the new rotation code will
be displayed in the Rotations display window as you click on
selected Improve/Sustain Topics.

             2. Loading FER Trends
The FER Trends are extracted from the FER by an experienced
military analyst meticulously reading the BOS Observations found
in the rotation FER (Final Exercise Report). An entry (record) is

                                                                                                                 5-9


---

made into the FER Trends Table for each BOS and sub-BOS
observation addressed. These observations are coded by Rotation
(like the Trends data), BOS and/or sub-BOS, and then evaluated
and coded as a positive, negative or neutral trend comment. The
steps used to load this table follow:

1. From the FoxPro® start-up screen, select File, by clicking on
File from the main menu bar. This will activate a pulldown
window, from which you select Open, by clicking On Open. This
will display the Open dialog box ( See Figure 5-1 on page 5-2).
Then follow these steps:

      a. From the Directory selections (middle of box), double click
      on e:\, then double click on bedb. Now scroll down the
      directories until support is found. Double click on support.

        b. In the List Files of Type: (bottom Left of box) Table/DBF
      should be selected.

      c. From the File Name selections (Left side of box), double
      click on tfer.dbf. This will cause the dialog box to disappear
      and the start-up screen to reappear.

      d. From the Main Menu Bar, click on Database. This will
      display a pull-down menu.

      e. From the pull-down select Browse. This will bring up the
      Tfer Table. See figure 5-5 on the next page.

                                                                                                                      5-10


---

—_                               wi a

Rotcode  Bobref      Eval] |+

S3DHHRO1 TAd 4.5

33DHHRO01 TA4 4.2

SSDHHRO1 TA4.4.2

93DHHRO1 TAd41

33D HHRG1 TA4 45

S3DHHROG1 TA4.4

33DHHRO1 TA45

93DHHA01 TA4. 2.2

33DHHAO1 TA4.4.1.2

93DHHAD1 TA4. 4.1.1                    fins

93DHHA01 TA5.1.1

33DHHAO1 TA5.1.2

S3DHHA01 TA5.1.1

S3DHHA01 TA5.1.2

S3DHHA01 TA5.1.2.4

re                        >

               | 1 | Lil

         Figure 5-5

Just like the tables before, the fields are sizable (though probably
not needed with this table), by clicking on and depressing the
mouse key at the field name dividing lines. Hold the mouse key
until the field is at the desired width and then release the key. Use
the scroll bars to scroll vertically and horizontally thru records and
fields.

2. To Create and load new records follow these steps:
            a. Use the key combinations Ctrl + N to create an empty
            record for every entry to be made. Each BOS and/or sub-
             BOS comment will become a new record.


---

           b. Then type in the data fields for each entry as follows:
                  ¢ Rotcode: Rotation code: Use Appendix F, Archive
                   Reference ID Codes for instructions, and enter for each
                  BOS/sub-BOS comment. (ie: 93DHHRO1 is the Rotcode
                  for the 35IDs' rotation from 1993).
                   * Bobref: Using the O/C's coding, from the Blueprint of
                  the Battlefield, type the code for each entry (a separate
                  entry is required for each code number) that properly
                  identifies the BOS and/or sub-BOS for the comment
                 addressed. The codes are extracted from the FER, just
                  as the O/C's entered them. (ie: TA4.2.1 is a code that
                  may be used when commenting on a units ability to
                  assess their situation).
                  * Eval: After reading the comment/comments, the
                  analyst records a +,or -, or makes no entry, depending
                  on if the comment was positive, negative or neutral for
                   every BOS and/or sub-BOS noted..

3. To view the records with the fields displayed vertically rather
than horizontally follow these steps:

            a. Going back to the Main Menu Bar, and click on
            Browse. This will display a pull-down menu.
            b. From the menu, click on Change and the table will be
            displayed as shown in Figure 5-3.

4. To return to viewing the records with the fields displayed
horizontally, follow these steps:

            a. Going back to the Main Menu Bar, click on Browse.
            This will display a pull-down menu.

                                                                                                               5-12


---

   b. From the menu, click on Browse (which will be
   displayed where Change was in the previous step) and the
   table will again be displayed as shown in figure 5-2.

   5. The last step is to check your work. Do this by exiting the

   loading program and entering the BCTPdb program. From the

   Welcome Screen, select the Trends button. From the Trend

7  Selection interface select the Performance Trends IAW Blueprint

   of the Battlefield button, then press the OK button. From the FER

   Trend Selection press the OK button. From the FER Trends for

   Maneuver interface select the TA] button. If you have loaded

   correctly, the new rotation code will be displayed in the table.

   5-13


---

SECTION 6

                                    VI. REFERENCES

1) Research Plan for Battle Command Training Program (BCTP) Database
             Development, U.S. Army Research Institute, 17 August 1993.

2) Battle Command Training Program (BCTP) Front End Analysis, U.S. Army
            Research Institute, 22 January 1993.

3) Battle Command Training Program (BCTP) Database Concept, U.S. Army
            Research Institute, 22 January 1993.

4) Battle Command Training Program (BCTP) Requirements Analysis, U.S. Army
            Research Institute, 22 January 1993.

5) BCTP Data Conference Read Ahead-Package, U.S. Army Research Institute,
             15 December 1992.

6) Microsoft® WindowsTM User’s Guide, Microsoft Corporation, 1992.
7) Microsoft® FoxPro® User’s Guide, Microsoft Corporation, 1993.

8) TextBridgeTM OCR for Windows User's Guide, Xerox Imaging Systems,Inc.,
             1993.

9) Paint Shop ProTM for Windows User's Guide, JASC, Inc., 1993.

10) Envisions Color Scanner Reference, Envisions Solutions Technology, 1993.

                                                                                                                                                6-1


---

11) BCTPdb User's Guide, BDM Inc., 1994.
12) BCTPdb Archiving Guide, PRC Inc., 1994.
13) BCTPdb Data Dictionary, BDM Inc., 1994.


---

APPENDIX A

            SETTING PREFERENCES

This appendix is a quick reference for Preference Settings proven to be
effective in the software applications used to load the BCTPdb. Only those
areas that the loader should be concerned with are addressed. More information
for the specific applications can be found in their related User Guides or
References.

Preference Settings are addressed for the following applications:
      >» TextBridgeTM OCR
      >» The Norton Desktop Editor
      > Paint Shop ProTM and Envisions TWAIN application
      » FoxPro®.

> TextBridgeTM OCR

Detailed Preference settings can be found in the TextBridgeTM OCR Users
Guide on Pages 3-2 to 3-4. Quick reference settings are:

                 Preferences:

      Document Quality: Standard, unless poor quality - then Fax.
      Page Orientation: As appropiate.
      Language: English.
      Auto Page Segment: Select, if the page/s have more than one column.
      Ignore Photos/Half: Select, if the document contains photos, tables charts,
      or art work.

                Scanner Settings:

       Use Automatic Document Feeder: Select.
      Brightness: Select Auto.

                                                                   A-1


---

     Resolution: 300x300.
      Page Size: As appropiate, usually Letter.

> The Norton Desktop Editor
Detailed Preference settings can be found in the Norton Desktop for Windows
Reference on Pages 9-24 to 9-28. Quick reference settings are:

                Document Preferences:

      Tab Spacing: 4
      Right Margin: 65
      Word Wrap: Select.
      Auto Indent: Select.
     Expand Tabs with Spaces: Deselect.
      Save as Default Settings: Select.

> Paint Shop ProTM and Envisions TWAIN application

* Detailed Preference settings can be found in the Paint Shop ProTM Users
Guide on Pages 3-11 to 3-14. Quick reference settings for Paint Shop ProTM

 are:

                Preferences - File Saving:

      File-Save As: Select.
       File-Batch Conversion: Select.
      File-Exit: Select.
       Windows-Close All: Select
      JIF/JPG Compression Level: Leave at default.

                    DPI:
       PCX: 100
       TIFF: 100
        WPG: 300

 * Quick reference settings for Envisions TWAIN application are:
       See Section 3, Page 3-11 to 3-12 of this guide.


---

> FoxPro®.

Detailed Preference settings can be found in the FoxPro® Users Guide on

Pages U3-14 to U3-15. Quick reference settings are:

                Edit Preferences: this can only be set when a memo editing window is

                      active.

     Save Options: will not be addressed, Leave at default.
      Justification: Left.
      Use These Preferences as Default for Memos: Select.
      Drag-and-Drop Text Editing: Select.
      Wrap Words: Select.
     Auto Indent: Select.
     Status Bar: Deselect.
      Tab Size: 4


---

APPENDIX B

                   STANDARD LOADING CONVENTIONS

This appendix provides the user with the standard loading conventions that have
been developed to date. It will help the reader understand what and how data is
used to achieve relational functionality that is critical in fully exploiting the power
and capabilities of a relational database.

The information contained in this appendix pertains to the Rotation Data Tables
described in section 4, and to the Good Ideas Table found in section 5.

Subjects addressed in this appendix are:
      > An Explanation of the Relational Database
      > Rotation Data Tables Loading Conventions
      > Good Ideas Table Loading Conventions
      > How to Load Data (memo) Fields
      » Miscellaneous Loading Notes


---

> An Explanation of the Relational Database

     The BCTP Database is organized as a collection of related FoxPro/ Windows
     tables. The data may be stored either locally on a user's DOS/Windows 3.1
     compatible computer, or in a Windows-compatible network in a read-only
      configuration. Numeric and fixed-length character data are stored in Dbase-like
     files with an extension of DBF. Indeterminate-length text data are stored in
     memo records, which are written to files with an extension of FPT. The
     current sizes of both the DBF and .FPT files are documented in the Database
     Data Dictionary.

     The BCTP Prototype Database Data Dictionary is organized by the individual
      FoxPro tables which, in concert with the user interface, comprises the BCTP

    Prototype Database. Separate sections for each table are designed to be

     replaced as the prototype evolves over time into an operational product. Note
     that the sizes given are as of 7/1/94, and may change as development and
     database loading activities continue.

     By its relational nature, different BCTP Prototype Database tables may be
      related by matching identical or similar values in fields in the different tables.
     The table below reflects the fields which are most likely to be used in
      matching different tables. It is not necessary for fields in different tables to
     have identical names; the contents are matched. In cases where the SIDE field
     is enclosed in parentheses, the SIDE is determined by the name of the table.
     See the table on the next page.


---

FieldType—>  UNIT| TIME |LOC|A SIDT E I| O WEAPON N |

 TableNamet  ORG,      TIMESENT                 SIDE

PDATA        DESTINATIO | TIMERECVD            WEAPO
                                                  N
 R_ADARPT    UNIT      LOCATION           (R)    (B)
             TIME                    LOCATION    (2)
BLUE_AIR                             LOCATION     (B)
 B_ARTILL    UNIT      TIME                            SYSTEM
 B_MED                               LOCATION     (B)  WEAPON
             UNIT      TIME          LOCATION
B_ATTRIT                             LOCATION   SIDE    CAUSE
             UNIT      STARTTIME                  ®)   WEAPON
| CBSTAT
 R_ARTILL              ENDTIME                  SIDE

[WIPE _OUT   UNIT      TIMESTART
 INTEL
                       TIMEEND
 RINTEL
             UNIT      STATTIME

             UNIT      TIME

             UNIT      TIME

             DET_UNIT  DET_TIME

                  |

                                                       B-3


---

> Rotation Data Tables Loading Conventions

The Rotation Data Tables are built from the following documents:
      Unit Generated products
      Unit Performance products
      CBS/AARS products
      AAR Video

They are made up of the following Fields:

Field Field Name  Type       Width
                  Character     20
1  TYPEOFDATA     Character     45
                  Character     15
2 DATANAME        Character      1
                  Character     10
3. DATASOURCE     Character     35
                  Numeric        3
4 SIDE            Character     15
                  Character     15
5 MEDIUM          Character     12
                  Character     12
6 FILENAME        Character     15
                  Character     30
7 ORDER           Numeric        2
                  Character      5
8 ORG             Character     30
                  Character     10
9 DESTINATIO      Character      5
                  Memo           10
10 TIMESENT

11 TIMERECVD

12. OPNLTIMFRM

13. OPTYPE

14. ANALEVAL

15 CP

16 BOBREF

17. BATTLELOC

18 OEG

19 DATA


---

Field Descriptions

The sections below describe each field in the Rotation Data Tables. Where it
is needed for clarification, or there are limited acceptable entries, the range of
values or examples are presented. When several similar items are present, the
listings of values have been abbreviated by signifying the presence of multiple
items by a lower case n (e.g. ANNEX n would be used to demonstrate
ANNEX A). In cases where the number of unique values is very large, the
listing of values has been omitted. The fields that must contain an entry for
every record are indicated with an asterisk *.

¢ Field: TYPEOFDATA *
This field indicates the general category of the data record, such as a section
of an OPORD, a FRAGO, or a specific product. TYPEOFDATA is used as a
key field in several queries. Because of this, this is one of the fields where the
values may be a critical element of a search or query. Any additions, deletions
or changes to this field must be coordinated with the programmer.
Range of values:

      AARI
      AARI OPFOR
      AAR2
      AAR2 OPFOR
      ADA
      ANALYSIS
      ANNEX n
      ANNEXES
      APPENDIX n
      ATK GUID MATRIX
      ATTACHMENT n
      BattleObs
      C2
      CHANGE n
      CHECKLIST
      COA ANALYSES
      COMBAT INSTR
      COMBAT INSTRUCTIONS

                                                                                                                                        B-5


---

COMPARISON
CSS
DECISION CONTROL
DESCRIPTION
DIRECTIVE MEASURES
DISCONNECTS
EX DIR UPDATE
EXECUTION MATRIX
FRAGO n
GENERAL MEASURES
HPT LIST
INCOMING INFORMATION
INFORMATION EXCHANGE
INTELLIGENCE
MOB/SURVIVABILITY
O/C TEAM
Obs/Comments
OPFOR MANNING
OPFOR TEAM
OPFOR
OPORD EXTRACT
OPORD
OTHER
OUTGOING INFORMATION
OVERVIEW
RESULTS
SAMPLE OVERLAY
SCENARIO
SITUATION ASSESSMENT
TAB n
TEMPLATE
TIMELINE
UNIT
VOL n CHAPTER n
VOL n COVER
VOL n CONTENTS
WARNO
WARNO n

                      B-6


---

¢ Field: DATANAME *

This field refines the category specified by the TypeOfData field. It contains

information such as the specific section title of unit products and a more

detailed title for graphics. It is used as a key field.

* Field: DATASOURCE *

This field is intended to be the most general of the document qualifiers. It

reflects the highest level of aggregation of documents/sections. It is used as a

key field. Because of this, this is one of the fields where the values may be a

critical element of a search or query. Any additions, deletions or changes to

this field must be coordinated with the programmer.

Range of values:
      AARI
      AAR2
      ACCES
      AJS
      AVN BDE OPORD
      AVN BDE FRAGO n
      CAA OPORD
      CF OPORD
      CNTROFF OPORD
      CORP REPORT
      CORP FRAGO n
      CORP OPORD
      DEF OPORD
      DISCOM OPORD
      DIV FRAGO W
      DIV FSOP
      DIV REQUEST
      DIV REPORT
      DIV FRAGO n
      DIV OPORD
      DIV FRAGO
      DIV FRAGO Wn
      EAC REPORT
      FER
      FRAGO RECON


---

      FRAGO n
      nADA REPORT
      nBDE OPORD
      nBDE REQUEST
      nBDE FRAGO Wn
      nBDE FRAGO W
      nBDE REPORT
      nBDE FRAGO n
      nCAV OPORD
      nMAR FRAGO n
      nMAR OPORD
      ORDERS X-WALK
      REPORT
      TIMELINE
      WHITE CELL

* Field: SIDE *

The SIDE field is used as a qualifier for kinds of data which might apply to

either the Opfor or Blue side, such as unit-generated data.

Range of Values: OorB

* Field: MEDIUM *

The MEDIUM field indicates the form of the referenced data. If MEDIUM is

TEXT, then the textual information is stored in the memo DATA field. If

MEDIUM is GRAPHIC, field FILENAME contains the fully qualified file

name of the graphics file. For a MEDIUM of VIDEO, the FILENAME field

contains a video tape identification.

Range of Values:   TEXT
                   GRAPHIC
                   VIDEO

¢ Field: FILENAME * (only for graphics and video files)
The FILENAME field contains the fully-qualified file name of the graphic
image identified by the remainder of the record, when MEDIUM is GRAPHIC.
FILENAME contains a short video tape identification for records where
MEDIUM is VIDEO.

                                                                                                                                    B-8


---

Range of Values: Each graphic image consists of a unique file name such

as: C:\BCDB\35ID\DIVOPLAN\A3ACL.TIF; video clips contain a short video
tape identification such as: 93DHHRO1-V001.

* Field: ORDER *

The ORDER field is a numeric field indicating the logical order of related

records. ORDER may indicate time sequencing, as in graphics images, or

ordering of document sections. ORDER applies to records with identical

DATASOURCE values.

« Field: ORG *

The ORG field contains the organization (Unit) identification of the unit
preparing the product in the case of unit-generated material or the

identification of the unit being evaluated in the case of performance data.

Example Range of Values :
       1-167/CAV/SQDN
       1//BDE
       10/ADA/BDE
       11/KPA/CORP
       116/CAV/BDE
       149//BDE
       17/FA/BDE
       3//BDE
       35/AVN/BDE
      35/IN/DIV
       4/AVN/BDE
       4/IN/DIV
      6/IN/DIV
       67//BDE
       69//BDE
       8/MAR/BDE
      8/ICAA
       CENTRAL FROUNT
      DISCOM/BDE
       EAC
       HL; CORP
       X/i/CORP

                                                                                                                                         B-9


---

¢ Field: DESTINATIO
The DESTINATIO field is intended to document the recipient of a message
or order. Its format is the same as the ORG field described above.

° Field: TIMESENT * (must have for video files)
The TIMESENT field is used to document the time some activity occurred,
such as the send time of a message. It is also used to show the start time of
a video segment.
Range of Values: TimeSent may either be in the 12 character form
DDHHMMZMMMYY for message traffic, or the HH:MM:SS format for video
clips.

* Field: TIMERECVD * (must have for video files)
The TIMERECV field is used to document the time some activity occurred,
such as the receive time of a message. It also used to show the end time of a
video segment.
Range of Values : TIMERECVD may either be in the 12 character form
DDHHMMZMMMY’Y for message traffic, or the HH: MM:SS format for video
clips.

* Field: OPNLTIMFRM

The OPNLTIMFRM field is used to document the battle phase.

Example Range of Values:
      CURRENT BATTLE
      PHASE 1
      PHASE I
      PHASE I/ II
      PHASE I/ IIA
      PHASE I/II
      PHASE I/TAII
      PHASE II
      PHASE II
      Phase I/II

                                                            B-10


---

* Field: OPTYPE
OPTYPE documents the type of the operation to which the DATA record

applies.

Example Range of Values:
      ATTACK
      ATTACK DEFEND
      ATTACK DEFEND CATK
      BHO
      CATK
      DEEP ATK
      DEEP ATTACK
      DEFEND ATTACK
      DEFEND
      DEFENSE
      Move Defend
      MOVE PASSAGE OF LINES ATTACK
      MOVE DEFEND CATK
      MOVE
      MOVE DEFEND CATK
      MOVE DEFEND
      MOVE DEFEND ATTACK
      SCREEN

¢ Field: ANALEVAL
The ANALEVAL field is intended to allow an analyst to enter a qualitative
evaluation of the information contained in the remainder of the record. It is not
currently used.

* Field: CP
The CP field shows the command post to which information in the current
record applies. It is not currently used.
Range of Values: CP

¢ Field: BOBREF *
The Blueprint Of the Battle (BOB) reference indicates a relationship of one or
more sections of TRADOC Pamphlet 11-9 to the data contained in the current
record.

                                                                                                                                       B-1i


---

Range of Values :
      TAI, TA2, TA3, TA4, TAS, TA6, TA7. A note: Enough character space
      has been allowed to enter subfunction reference numbers (ie: TA1.2.1.2)

° Field: BATTLELOC
The BATTLELOC field indicates the relative position on the battlefield. It is
not currently used.
* Field: OEG
Operational Exposure Guidance. (Not currently used)
* Field: DATA *
The DATA field is a memo field which contains the text of the product or
document, or a description of the graphic or video clip. In general, the DATA
field contains the data of interest, as defined by the remainder of the record.
See How to Load Data (memo) Fields below for more details.
Range of Values: The range of values in the DATA field ranges from a few
words to several pages of textual data.

                                                                                                                                      B-12


---

> Good Ideas Table Loading Conventions

      The Good Ideas Table is built from documents that have been created by
      O/Cs, analysts, Units, SMEs, or anyone else who has access to BCTP WFX
      information, or has captured an idea that should be shared with the Army.

      It is made up of the following Fields:

Field Field Name  Type                    Width
                  Character                   8
1  ROTCODE        Character                  20

2 TYPEOFDATA      Character                  45
                  Character                  15
3 DATANAME        Character                   10
                  Character                  35
4 DATASOURCE      Numeric                     3
                  Character                   15
5 MEDIUM          Character                   12
                  Character                   12
6 FILENAME        Character                  30

7 ORDER           Memo                        10

8  ORG

9 TIMESENT

10 TIMERECVD

il BOBREF

12 DATA

Field Descriptions

The sections below describe each field in the Good Idea Table. Where it is
needed for clarification, or there are limited acceptable entries, the range of
values or examples are presented. The fields that must contain an entry for
every record are indicated with an asterisk *.

¢ Field: ROTCODE *
This field is used to code the rotation.


---

   Range of values: See Appendix F, Archive Reference Codes.

   * Field: TYPEOFDATA *
   This field indicates the general category of the data record such as:
   description or a specific product.
   Range of values: Up to 20 character description of the data record.

   ¢ Field: DATANAME
   This field refines the category specified by the TypeOfData field. It contains
   information such as the specific section title of unit products and a more
   detailed title for graphics.

   * Field: DATASOURCE
- This field is intended to be the most general of the document qualifiers. It

   reflects the highest level of aggregation of documents/sections. It can be used
   to tell what the entry is (ie: Good Idea) or where the data came from (ie:
   Doctrine SME or the Name of the contributor ).

   * Field: MEDIUM *
   The MEDIUM field indicates the form of the referenced data. If MEDIUM is
   TEXT, then the textual information is stored in the memo DATA field. If
   MEDIUM is GRAPHIC, field FILENAME contains the fully qualified file
   name of the graphics file. For a MEDIUM of VIDEO, the FILENAME field
   contains a video tape identification.
   Range of Values: TEXT, GRAPHIC, VIDEO.

   ° Field: FILENAME * (only for graphics and video)
   The FILENAME field contains the fully-qualified file name of the graphic
   image identified by the remainder of the record, when MEDIUM is GRAPHIC.

                                                                                                                                     B-14


---

FILENAME contains a short video tape identification for records where

MEDIUM is VIDEO.
Range of Values: Each graphic image consists of a unique file name such
as: C:\BCDB\35ID\DIVOPLAN\A3ACL.TIF; video clips contain a short video
tape identification such as: 93DHHRO1-V001.

¢ Field: ORDER *
The ORDER field is a numeric field indicating the logical order of related
records. ORDER may indicate time sequencing, as in graphics images, or
ordering of document sections. ORDER applies to records with identical
DATASOURCE values.

* Field: ORG *
The ORG field contains the organization (Unit) identification of the unit where
the data was collected.
Example Range of Values :

       1-167/CAV/SQDN
       1//BDE
       10/ADA/BDE
       116/CAV/BDE
       149//BDE
       17/FA/BDE
      3//BDE
      35/AVN/BDE
       3S/IN/DIV
      4/AVN/BDE
       4/IN/DIV
       6/IN/DIV
       67//BDE
      69//BDE
       8/MAR/BDE
       DISCOM/BDE
      TH//CORP

                                                                                                                                   B-15


---

¢ Field: TIMESENT *
The TIMESENT field is used to document the time that the good idea was
collected.
Range of Values: TimeSent should be entered as: Month and year.

* Field: TIMERECVD
The TIMERECYV field is used to document the time some activity occurred,
such as the receive time of a message. It also used to show the end time of a
video segment. It is not currently being used.
Range of Values : TIMERECVD may either be in the 12 character form
DDHHMMZMMMYY for message traffic, or the HH:MM‘SS format for video
clips or Month and year.

° Field: BOBREF *
The Blueprint Of the Battle (BOB) reference indicates a relationship of one or
more sections of TRADOC Pamphlet 11-9 to the data contained in the current
record.
Range of Values :

      TA], TA2, TA3, TA4, TAS, TA6, TA7. A note: Enough character space
      has been allowed to enter subfunction reference numbers (ie: TA1.2.1.2)

* Field: DATA *
The DATA field is a memo field which contains the text of the product or
document, or a description of the graphic or video clip. In general, the DATA
field contains the data of interest, as defined by the remainder of the record.
See How to Load Data (memo) Fields below for more details.
Range of Values: The range of values in the DATA field ranges from a few
words to several pages of textual data.


---

> How to Load Data (memo) Fields

      Loading most of the data fields is a relatively simple process. After consulting
      with the analyst and agreeing on a logical use/loading structure, simply type
      in the information called for in the data field descriptions provided in the
      preceding pages.

      The process for loading the last field - Data is a little more complex. The
      memo field found under the Data field heading is where all textual information
      to be displayed in the database is entered into the FPT files. Entering
      information in all of the proceeding fields is the process that makes the memo
      field data relational to the rest of the database.

      Text data can be entered by two methods:
            * The first and simplest is to double click on the memo field which will
            display the Data.data window, and then to simply type in the text entry.
            You can tell if a memo field has text in it by the looking at the first letter
             in memo. If it is in lower case (memo), it does not contain data. If it is
            upper case (Memo), it contains data.

            * The second requires the user to manipulate the screens so that the Table,
            the Data.data window, and a text editor or word processing program are
            all displayed simultaneously. See figure C-1 on the next page.

                                                                                                                                             B-17


---

                                           Microsoft FoxPro

    File Edit Database Record Program Run Text Window Help

    Typeotdata |                                                          Data  |Order| Timeq Opnitimfrm (Op]  Bobref
                  Dataname [Datd Side] Medium | Filename
                                                                                                                            [Data

                                                                                                                            memo

Ls

=

                        D  dj

                                                                                                                            Ad

+[ J        Record 1/1              Exclusive                                                                  | [Ins [Num            +
Data     Edit Search
                                          Desktop Editor- [Untitled-1]                                                      [st
=                                                                                                                           Zz
                        Options Window Help
=| Eile                                                                                                                     |+

                                                                                                                                   fo Lhot>

                                                  Figure C-1

Once the screens are arranged as above the user retrieves the appropiate
text files using the text editor (as above) and using the copy or cut feature
selects the text to be loaded. The selected text is then loaded using the
FoxPro® Data.data window and thePaste function.

                                                                                                                                             B-18


---

> Miscellaneous Loading Notes

      * Text files that were saved to the hard drive can be deleted from the hard
      drive once they have been loaded to the database.
      * Graphic files cannot be deleted, and any time they are moved to another
     directory, the database (FILENAME Field) must be updated with the new path.
      * The databases search logic is designed to find files in their original document
      order layout. In other words , an OPORD is, by doctrine written as:

           - OPORD with sub headers as:
                  Situation
                  Mission
                  Execution
                   Service Support
                  Command and Signal

             - Annexes
             - Appendices
             - Tabs

                                                                                                                                             B-19


---

APPENDIX C

                                  TROUBLESHOOTING

If you have problems with any of the database commercial software
applications, you should first read the appropiate help, questions & answers, or
troubleshooting sections provided in your application manual. If you cannot
resolve the problem, call the technical support number found in your
application manual.

For problems associated with the BCTPdb and application, check your
preference settings in all appropiate applications (see appendix B, Settings
Preferences). If this does not resolve your problem contact one of the
following:

            BCTPdb Database Administrator (ARI-FLVN)
             Attn: Terry P. Bartkoski
             Army Research Institute Field Unit
             P.O. Box 3407
             Fort Leavenworth, KS 66027-0347
            AVN (552-4933)
            Commercial (913) 684-4933
             Fax (913) 684-3290

             BCTPdb Database Administrator (ARI-POM)
             P.O. Box 5787
            Bldg 104
            Presidio of Monterey, CA 93944
            AVN (929-3329)
            Commercial (408) 372-3329
             Fax (408) 647-5309


---

APPENDIX D

                              DATA TYPES & MEDIA

This appendix describes the data sources, the data media and how they are
organized for the database user to access them. It provides the user an
understanding of the range and types of data that are included in the database and
their relational nature. Data sources and formats vary between BCTP teams and
WFXs. The BCTP is an evolving training tool. Therefore the database
administrator, archivist, loader and analyst must continue to monitor the available
data sources and those that are provided to insure that the most worthwhile data
is collected, archived, loaded and analyzed.

BCTP considers all WFX data as inherently sensitive. Certain data types have
information that may require special access requirements due to either
controversial content, personal information, or overall training readiness
evaluations. Additionally, certain WFX's are classified and are therefore both
sensitive and classified.

The data types available from each WFX are categorized into eight subject areas.
The reader will see that a number of data sources are often used in more than one
subject area. The subject areas and the data types they contain are:

      » Unit Generated: Documents and Products that are produced by the WFX
      and OPFOR unit.

      >» Unit Performance: Documents and Videos produced by O/Cs, BCTP and
     Analyst that address WFX results.

      > Rotational Information: Documents that provide background facts and
      information briefed to the exercise director and that put the WFX in context.


---

> Objective Battle Data: Statistical data that is produced by the simulation
and can be used to conduct original analysis.
> Battle Description: Battle information that is produced by any source and
contains a playback or description of the battle.
> Player Unit Profile: Information on the WFX unit that could help put the
unit itself in context. This data is not currently available.
> Good Ideas: Documentation of successful concepts, ways of doing business,
and lessons learned that are provided by O/Cs, SMEs, contractors or others.
> Trends:

      * FER analysis: Analyst generated tables that quickly highlight the
      emerging BOS trends across rotations and time.
      * Objective Data: Statistical computer generated data that is loaded into
      charts to display emerging trends across rotations and time, within the
      context of the simulation.

                                                                                                                                        D-2


---

> Unit Generated Data

      Exercise Unit generated Plans/Orders, FRAGOs, Maps and Overlays:
      * Description of data: These data include the plans, orders, FRAGOs,
     requests, reports, maps and overlays of the unit being trained.

       * Media: Various stapled and loose hardcopy documents, acetate overlays,
      VGTs and Floppy disks.
      OPFOR generated data:
      * Description of data: These data include the plans, orders, FRAGOs,
      requests, reports,maps and overlays used by the OPFOR to conduct the
      WFX.
      * Media: Various stapled and loose hardcopy documents, acetate overlays,
     VGTs and Floppy disks.

                                                                                                                                               D-3


---

> Unit Performance Data

      After Action Review (AAR) video tapes:
      * Description of data: These data include video tapes taken during the
      AARs (normally 2). Topics that are included are unit strengths and
      weaknesses, areas to sustain or improve and supporting VGTs and briefing
      charts.
      * Media: 2 - 4 video tapes.

      Army Command and Control Evaluation System (ACCES) data:
     * Description of data: These data include detailed observer notes and final
      reports evaluating C2 operations/functions.
      * Media: Hardcopy report and Floppy disks.

      Final Exercise Report (FER):
      * Description of data: The FER contains an overview of the exercise (key
      dates, scenario and tactical outcomes), Battlefield Operating Systems
      observations, After Action Review Products from both AARs, World Class
      OPFOR information (campaign plans and OPFOR commanders comments
      for the AARs), and a listing of video tapes being provided to the unit for
      the AARs.
      * Media: Bound hardcopy document.

      O/C crosswalk of the unit Operations Plan:
      * Description of data: The crosswalk is a comparison, conducted by O/C's,
     of the training units’ operations plan against the higher headquarters plan. It
      contains comparisons by BOS and helps identify to the O/C’s, strengths and
      weaknesses in the unit plan.
      * Media: Stapled hardcopy document.


---

Observer/Controller (O/C) notes and checklists:
* Description of data: These notes could include observations of unit and/or
staff section performance that is an indicator of training strengths and
weaknesses as well as the informal O/C AAR s conducted with appropiate
staff sections.
* Media: Various loose hardcopy notes, charta and VGTs (At present, this
data is not available)

                                                                                                                                       D-5


---

> Rotational Information

      Exercise Control 5 day cartoon:
      * Description of data: These data include EXCON provided graphic
      drawings of the battlefield with OPFOR/WFX unit positions as of the
      exercise start through days 1-5 and the end of the exercise.
      * Media: 5 - 7 pages of hardcopy drawings.

      Exercise Control briefing slides:
      * Description of data: These data include EXCON provided information on
      weather, terrain, OPFOR vs. WFX unit status (strength), correlation of
      forces and means (COFM), and a Montage of unit locations.
      * Media: Various loose hardcopy VGTs and documents.

      White Cell directives:
      * Description of data: This would be any instructions that change the WFX
      unit or OPFOR structures (i.e., additional units), boundary charges, scripted

        events, etc.

      * Media: Various hardcopy notes, if provided. (At present, this data is not
      available)


---

> Objective Battle Data

     Warfighter After Action Report System (WAARS) or After Action
      Review (AARS) tape:
      * Description of data: These data provide comparisons of WFX units vs.
      OPFOR actions and results by BOS. It includes: WFX unit and OPFOR
     combat damage reports, attrition reports, personnel casualty reports, unit
     supply reports, maintenance reports, medical reports, artillery reports, air
      mission reports, etc.
      * Media: The WAARS tape consists of one, ten-inch, nine track reel to reel
     tape. The AARS tape consists of one 8mm data tape.

                                                                                                                                               D-7


---

> Battle Description

      After Action Review (AAR) video tapes:
      * Description of data: These data include video tapes taken during the
      AARs (normally 2). Topics that are included are: Battle Summary, OPFOR
      Summary, BOS observations and discussion, areas to sustain or improve
      and supporting VGTs and briefing charts.
      * Media: 2 -4 video tapes.

      Workstation Reporting System (WRS) tape:
      * Description of data: This is a log that contains those events considered as
     significant by the workstation controller and are generally arranged by BOS.
      Comments would include: personnel transfers, movement orders, notes on
      time FRAGOs were received, contact reports with small units, workaround
     information, units under SOF attack, ammo delivery projections, units being

       overrun, etc.

      * Media: Digital Data tapes

      Final Exercise Report (FER):
      * Description of data: The FER contains an overview of the exercise (key
      dates, scenario and tactical outcomes), Battle Summaries, Battlefield
      Operating Systems observations, After Action Review Products from both
      AARs, World Class OPFOR information (campaign plans and OPFOR
      commanders comments for the AARs), and a listing of video tapes being
     provided to the unit for the AARs.
     * Media: Bound hardcopy document.

                                                                                                                                                   D-8


---

Timeline:
* Description of data: The timeline is an extract of significant events that
occurred during the rotation. It is extracted from the FER Tactical
Outcomes by an analyst or from ACCES data.
* Media: Created by an Analyst or provided Hardcopy document
Battle Replay:
¢ Description of data: The graphic replay of the computer simulation battle.
* Media: SUN Raster Graphics files.

                                                                                                                                       D-9


---

> Player Unit Profile

      TBP when and if this data is collected.


---

> Good Ideas

      Good Ideas:
      * Description of data: Any documentation of successful concepts, ways of
      doing business, and lessons learned that are provided by O/Cs, SMEs,
      contractors, analysts or others.
      * Media: Hardcopy documents, floppy disk, VGTs, Charts, Tables - any
      media.

                                                                                                                                            D-11


---

> Trends

      * FER analysis:

            Fina] Exercise Report (FER):
            * Description of data: The FER contains an overview of the exercise
            (key dates, scenario and tactical outcomes), Battle Summaries,
            Battlefield Operating Systems observations, After Action Review
            Products from both AARs, World Class OPFOR information (campaign
            plans and OPFOR commanders comments for the AARs), anda listing
           of video tapes being provided to the unit for the AARs.
            * Media: Bound hardcopy document.

      * Objective Data:

            Warfighter After Action Report System (WAARS) or After Action
            Review (AARS) tape:
            * Description of data: These data provide comparisons of WFX units vs.
            OPFOR actions and results by BOS. It includes: WFX unit and
            OPFOR combat damage reports, attrition reports, personnel casualty
            reports, unit supply reports, maintenance reports, medical reports,
            artillery reports, air mission reports, etc.
            * Media: The WAARS tape consists of one, ten-inch, nine track reel to
           reel tape. The AARS tape consists of one 8mm data tape.


---

APPENDIX E

                     ARCHIVE REFERENCE ID CODES
                                     (ARCHREFID)

Characters used to code rotations are found in the first five Data Elements below
(yyettcnn). Characters used to code and archive different media are found using
the entire table. (yyettcnn-m-sss). Details on use follow the table.

DATA             CHARACTERS     CODE OPTIONS

ELEMENT          character 1-2  YEAR - 93
                 character 3
Year                            C - CORPS
Echelon                         D - DIV
                                B - BDE
Rotation type    character 4-5
                                HL - HEAVY/LIGHT
Component        character 6    LH - LIGHT/HEAVY
                                HH - HEAVY/HEAVY
Rotation         character 7-8  LL - LIGHT/LIGHT
sequence number  character 9    NA - NOT
                                APPLICABLE
Media type
                                A - ACTIVE
                                N - GUARD

                                0-1 99

                                V - VCR TAPE
                                S - STREAMING
                                TAPE
                                9-9 TRACK TAPE
                                D - DAT TAPE
                                H - HARDCOPY
                                O - OVERLAY
                                F - FLOPPY DISK

                                E-]


---

Media sequence | character 10-12  001 - 999
number

Rotation codes are used to designate the year, echelon (CORPS, Division, or
Brigade), rotation type (see table), component (active or guard), and the sequence
that particular type rotation was loaded. The rotation code 93DHHAO1, translates
as: the first WFX rotation loaded of an active division conducting a heavy/heavy
WEX in 1993.

Media sequence numbers refer to the number of data sources of a particular type.
For example: the first VCR tape is V-001, the second is V-002. The first floppy

disk is F-001, etc.

The ArchRefID, 93DHLAO1-V-001, translates as: the first video tape from the first
WFX rotation loaded of an active division conducting a heavy/light WFX in 1993.

                                             E-2


---

AAR                          GLOSSARY
AARS
ACCES   After Action Review
AD      After Action Review System
ADA     Army Command and Control Evaluation System
ADF     air defense
ADM     Air Defense Artillery
ADP     Automatic Document Feeder
AFA     atomic demolition munitions
AFCENT  automatic data processing
AG      architecture of the future Army
AJS     Allied Forces, Central Europe
AMOPS
AO      army group
AOR
ARI     Automated Journal System
ASAT    Army Mobilization and Operations Planning System
BCTP    area of operations
BCTPdb  area of responsibility
BFMA    Army Research Institute
BICM    anti satellite
BOS     Battle Command Training Program
C2      Battle Command Training Program Database
C21     battlefield functional mission area
C2W     Battlefield Intelligence Collection Model
C3      Battlefield Operating System(s)
C4
        Command and Control

        command, control, and intelligence
        command and control warfare
        command, control, and communications
        command, control, communications and computers

                                                                                                    GLOS-1


---

CBRS      Concept Based Requirements System
CBS
CFE       Corps Battle Simulator
CINC      Conventional Forces Europe (negotiations)
CINCEUR   commander-in-chief
CINCLANT  Commander-In-Chief, Europe
CICS      Commander-In-Chief, Atlantic
CMTC      Chairman, Joint Chiefs of Staff
CMO       Combat Maneuver Training Center
COA       civil-military operations
COFM      Course Of Action
COMMZ     Correlation Of Forces and Means
COMSEC    communications zone
CONUS     communications security
CRC       Continental United States
Cs        conus replacement center
CSS       combat support
CTC       combat service support
CTCdb     Combat Training Center
CW        Combat Training Centers Database
DA        continuous wave
DARMS     Department of the Army
DCA       developmental Army readiness and mobilization system
DISA      Defense Communications Agency
DLA       Defense Information Systems Agency
DNA       Defense Logistics Agency
DOD       Defense Nuclear Agency
DTG       Department of Defense
ECCM      Date Time Group
ECM       electronic counter-countermeasures
          electronic countermeasure

                                                                                                      GLOS-2


---

ENG       Engineer
EOD       explosive ordnance disposal
EPW       enemy prisoner of war
ESM       electronic support measures
EUCOM     European Command
EW        electronic warfare
EXCON     Exercise Control
FER       Final Exercise Report
FLVN      Fort Leavenworth, Kansas
FM        field manual (Army)
FORSCOM   Forces Command
FRAGO     Fragmentary Order
GT        generic task
Hardcopy
HCA       papercopy
HNS
HPT       humanitarian and civic assistance
          host nation support
HQ        high-payoff target
          Headquarters
HQDA      Headquarters, Department of the Army
HS        home station
HVT       high-value target
IPB       intelligence preparation of the battlefield
JAG       judge advocate general
JCS       Joint Chiefs of Staff
JOPES     Joint Operational Planning and Executing System
JRTC      Joint Readiness Training Center
JTF       joint task force
KIA       killed in action
LOC       lines of communication
MACOM     major command

                                                           GLOS-3


---

METL    mission essential task list

METT-T  mission, enemy, terrain, troops available - time

METT    mission, enemy, terrain, and troops available

MOBPERSACS mobilization personnel structure and composition system

MOPP    mission-oriented protection posture

MPC     military payment certificates

MS      mobilization station

MTBSP   mobization troop basis stationing plan

MTP     mission training plan

NATO    North Atlantic Treaty Organization

NBC     nuclear, biological and chemical

NCA     national command authorities

NDU     National Defense University

NEO     noncombatant evacuation operations

NTC     National Training Center

o/c     Observer/Controller

OB      order of battle

OCONUS  outside continental United States

OCR     Optical Character Reader

OPFOR   Opposing Force

OPLAN   operations plan

OPORD   operations order

OPSEC   operations security

PA      public affairs

PACOM   Pacific Command

PAM     pamphlet

POD     port of debarkation

POE     port of embarkation

POM     preparation for overseas movement

POM     Presidio of Monterey, California

                                                          GLOS-4


---

PPBES         planning, programming, budgeting, and execution system
PPBS          planning, programming, and budgeting system
PSP           Proficiency Sustainment Package
PSYOP         psychological operations
PTRS          postmobilization training support requirement
Q-36 or Q-37  Types of U.S. Army counterfire radars
RATT          radio teletype
RC
RCU           reserve component
SACEUR
SAO           RC unit
SCUBA         Supreme Allied Commander, Europe
SECDEF        security assistance organization
SIGSEC        self-contained underwater breathing apparatus
SIOP          Secretary of Defense
SME           signals security
SN            Single, Integrated Operational Plan
SOF           Subject Matter Expert
SOP           code for national military Strategic Blueprint functions
SPF           special operations forces
ST            standard operating procedure
TA            Special Purpose Forces
TA            code for theater Strategic Blueprint functions
TBP           theater army
TLE           code for Tactical Blueprint functions
TM            to be published
TOW           target location error
TRADOC        technical manual
US.           tube-launched, optically tracked, wire guided
UAV           United States Army Training and Doctrine Command
              United States
              unmanned aerial vehicle

              GLOS-5


---

USAID    U.S. agency for international development

USIA     U.S. information agency

USR      unit status report

USTRANSCOM United States Transportation Command

VA       veterans administration

VCR      Video Cassette Recorder

VGT      View Graph Transparency

w/D      withdrawal

WAARS    WarFighter After Action Reporting System

WESTCOM  Western Command

WFX      WarFighter Exercise

WIA      wounded in action

WRS      workstation reporting system

Www      world war

WWMCCS   world wide military command and control system

                                                         GLOS-6


---

USER NOTES

                                                                        USER-1


---

USER NOTES

       continued

                                                                      USER-2


---

                                                    BCTPDB
                                 IMPROVEMENT SUGGESTIONS

This form has been provided so that users have an easy, convenient method to record suggestions
that can be used in the systems continuous improvement process. It can be reproduced as
necessary. Please supply complete and as detailed information as you can.
Describe the problem or area that should be improved.

Is this area addressed in this guide? (Select One Below)
(Yes) (No) If Yes:
where?

What would be the best fix for this problem or area?

What other suggestions do you have for improvement of this system?

Name
Phone
Date


--- 