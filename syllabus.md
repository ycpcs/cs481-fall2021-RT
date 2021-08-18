---
layout: default
course_number: CS481-RT
title: Syllabus
---

--- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---

## CS 481-RT: Senior Software Design I (YCAS Radio Telescope Project)

## Fall 2021

--- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---



**Meeting Times:**

 - **Wednesdays (3:00p-4:15p):** This class session is reserved for weekly status updates, assignment presentations, and Milestone presentations.  We will meet in KEC 118 for all weekly status updates, assignment presentations, and milestone - unless otherwise noted.  Your YCAS clients will likely be in attendance at these meetings, as well.  NOTE: It is not unusual for the these in-class sessions to run well past 4:15 at times, especially during the status reports and milestone presentations.  If you have another class scheduled immediately following this class, please let me know, and I will try to make accomodations. For Milestone presentations, you might need to make accommodations with your other professors.<br>
 
 - **Fridays (3:00p-4:15p):** This class session is reserved for you to work as a team, unencumbered by "interference" from the faculty.  Your YCAS clients will frequently be available to work with you during this time, and can meet in-person with you, upon request.  However, there could be another CS481 team meeting in KEC 118 during this time, giving their status reports, assignment presentations, and milestones.  I will do my best to manage this issue, by scheduling that team for KEC 119 or KEC 123 for Fridays - but I can't gurantee that, yet.  Also, much of your work this semester will be conducted in the Project Workspace, testing the Radio Telescope, so you should also plan on meeting in the Project Workspace. 
  
**Location:** KEC 118 (the back 2 benches are reserved for the Radio Telescope project - although we might also conduct portions of the status meetings and presentations in the Project Workspace, where the Radio Telescope hardware is located.
 
**Webpage:**  [https://ycpcs.github.io/cs481-fall2021-RT/](https://ycpcs.github.io/cs481-fall2021-RT/)

**Instructor:**

>[Donald J. Hake II](https://www.ycp.edu/academics/kinsley-school-of-engineering-sciences-and-technology/faculty/hake-ii-donald-j.php)<br>
**Email:** <djhake2@ycp.edu><br>
**Office:** KEC 137<br>
**Phone:** (717) 815-6587 (this is definitely NOT a reliable way to reach me, I might be convinced to provide my cell #, upon request)<br>
**Office Hours:** W-F: 2:00p to 3:00p, and by appointment (and usually after class on W-F)

--- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---

### Course Description

This is the fourth year of a multi-year effort to design and develop the various software components for the York County Astronomical Society (YCAS) Radio Telescope, which is being developed in collaboration with the 2021-2022 Radio Telescope Engineering Capstone team.  This project is being developed under the direction of the course instructors and other Engineering and Computer Science faculty members, YCAS clients, recent York College Engineering and Computer Science graduates, and local industry partners.

There are currently 5 sub-projects (listed below).  Some of those sub-projects require significant additional work, others do not.  Our clients - Kerry SMith and Todd Ullery from the York County Astronomical Society (YCAS) - will determine the substance of the tasks to be accomplished, as this is expected to be the final year of major SW development for the project.

We will organize as teams of 1-3 people, working in a coordinated fashion to continue developing and testing the entire Radio Telescope software suite.  The teams will be working on:<br>
	* **Team Venus:**   Front-End User Interface Website (Vue.js, Vuetify, etc.)<br>
	* **Team Mercury:** Back-End Server and Database (Kotlin, Spring, AWS, etc.)<br>
	* **Team Jupiter:** Control Room Application, including HW simulation and Testing Tools (C#, .NET)<br>
	* **Team Saturn:**  Visualization and Virtualization (C#, .NET, JS, Unity, VR (HTC Vive), AR (MS Hololens)<br>
	* **Team Luna:**    Cross-Platform Mobile Application (Android, Swift, XCode, React, Xamarin, etc.)
	
The standard user interface for the Radio Telescope is a web-based GUI.  The website and control room application interface via the AWS back-end server and local database.  The mobile development applications will also interact with the AWS back-end server and local database.  The simulation, visualization, and virtualization components will be able to substitute for the physical radio telescope, serve as SW test tools, and also be used as educational tools by YCAS.

The previous 2020-2021 Radio Telescope CS Senior Design (CS481 and CS482) Engineering Capstone Team Drives have been shared with you - you can view all of their accumulated information.  It is not, however, open for you to create or edit content.  You are expected to build upon their work, but whatever content you do use, you must cite or reference the source.

Your YCAS clients, Kerry Smith and Todd Ullery, will be present at most meetings to provide mentorship, guidance, and provide requirements and task priorities, and serve as true real-world clients.  They will specify many of the requirements for the various SW components.  You will be expected to interact with them on a frequent, perhaps even daily basis, especially as you develop the requirements and specifications for this year's effort, and as you (and they) get deeper into testing your software.

The coming year's primary focus and effort, across CS481, CS482, and Engineering Capstone, will be to finish development, assemble, and test the final version of the SW and Radio Telescope SW and HW, as well as provide complete SW simulation of the Radio Telescope functionality.  We will be installing the Radio Telescope at the YCAS observatory at John C. Rudy County Park during late Spring 2022 and into the Summer of 2022.

**Prerequisites:**  CS 320 with a grade of 2.0 or higher (or PC from Spring 2020)<br>
**Credit:**		3 credit hours<br>
**Text:**  None

--- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---



### Grading Policy

Your team's grade will be determined as a weighted average of the grades on the 7 assignments, as follows:

-   Assignment 1 - Team Project Proposal - **5%**
-   Assignment 2 - Weekly Progress Journals, Status Reports, Demonstrations - **20%**
-   Assignment 3 - Requirements - **10%**
-   Assignment 4 - Analysis and Design - **15%**
-   Assignment 5 - Minimal Working System - **10%**
-   Assignment 6 - 50% Working System - **10%**
-   Assignment 7 - Final Working System (10%), Presentation (10%), Technical Report (10%) - **30%**



NOTE: You will be presenting your work for each of these assignments in class on the Wednesdays they are due.  On the days that you do not have an assignment or milestone due, you will be presenting progress reports, as part of assignment 2.  Your weekly journal entries are **due EVERY Wednesday by 3:00p, immediately prior to EVERY class period, regardless of what else is due that day.**

Individual course grades will be assigned on a 100-point scale according to the following table, and will be determined determined from your weekly progress journal entires and reports, combined with your team's grade, multiplied by an effort factor determined from the results of your mid-term and final peer evaluations:

| Range             |  Grade   |
|:-----------------:|:--------:|
| ≥ 90 and ≤ 100    |   4.0    |
| ≥ 87 and &lt; 90  |   3.5    |
| ≥ 80 and &lt; 87  |   3.0    |
| ≥ 77 and &lt; 80  |   2.5    |
| ≥ 70 and &lt; 77  |   2.0    |
| ≥ 60 and &lt; 70  |   1.0    |
| &lt; 60           |    0     |

--- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---



### Attendance Policy

**Attendance at every status/presentation meeting (Wednesdays) and every team meeting (Fridays) is mandatory**.

--- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---



### Academic Integrity

York College's mission statement stipulates that strict adherence to
principles of academic honesty is expected of all students. Therefore,
academic dishonesty will not be tolerated at York College. Academic
dishonesty refers to actions such as, but not limited to, cheating,
plagiarism, fabricating research, falsifying academic documents, etc.,
and includes all situations where students make use of the work of others
and claim such work as their own.

When a faculty member believes a student has committed an act of academic
dishonesty, the faculty member must promptly notify the student in writing
and obtain confirmation of notification from the student.  The faculty
member then has ten business days from that written notification to
the student to report the incident to the Dean of Academic Affairs and
the Department Chair. Documentation related to instances of academic
dishonesty will be kept on file in the student's permanent record. The
faculty member has full discretion to determine a suitable penalty for
the student, up to a course grade of 0.  This discretion is limited to
the course in which the dishonesty took place.  Students may not withdraw
from a course in which they have been accused of academic dishonesty,
unless and until the accusation is withdrawn by the faculty member or
is overturned by the Student Welfare Committee or the Dean of Academic
Affairs.

Students who believe they have been unjustly charged or sanctioned must
discuss the situation with the faculty member and have 10 business
days thereafter to submit an appeal to Student Welfare Committee
through the Dean of Academic Affairs. If an appeal is filed, the
Student Welfare Committee will then conduct a hearing to review the
charge and/or sanction.  In the case of an egregious first offense, the
faculty member may request that the Student Welfare Committee conduct a
hearing and determine a sanction, which may involve academic probation,
suspension or dismissal from the College.

If the Dean of Academic Affairs determines that the academic dishonesty is
the student's second offense, the Dean will provide written notification
to the student, the faculty member, and the Department Chair. The Student
Welfare Committee will automatically conduct a hearing to review the
charge and decide on an appropriate sanction, which will involve academic
probation, suspension or dismissal from the College. Students who believe
the Student Welfare Committee has unjustly sanctioned them may submit
a written appeal to the Dean of Academic Affairs within 72 hours of
receiving notification of the Student Welfare Committee's sanction.

--- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---



### Personal Technology Policy

While York College recognizes students’ need for educational and emergency-related technological devices such as laptops, PDAs, cellular phones, etc., using them unethically or recreationally during class time is never appropriate.  The college recognizes and supports faculty members’ authority to regulate in their classrooms student use of all electronic devices.


--- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---



### Communication Standards

York College recognizes the importance of effective communication in all disciplines and careers.  Therefore, students are expected to competently analyze, synthesize, organize, and articulate course material in papers, examinations and presentations.  In addition, students should know and use communication skills current to their field of study, recognize the need for revision as part of their writing process, and employ standard conventions of English usage in both writing and speaking.  Students may be asked to further revise assignments that do not demonstrate effective use of these communication skills.


--- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---



### Students with Disabilities

If you are a student with a disability in need of a classroom accommodation and have not already registered with Linda Miller, Director of Disability Support Services, please contact her at 815-1785 or [lmille18@ycp.edu](mailto:lmille18@ycp.edu) to discuss policies and procedures related to disability services and to establish the accommodations for which you are eligible.

--- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---




**Disclaimer:**	This syllabus is subject to change by the instructor.
