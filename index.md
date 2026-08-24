---
title: Robotics 
subtitle: CSCI 420 - Fall 2026
layout: page
---

# Team
 
* Trey Woodlief - Instructor, woodlief@wm.edu
* Teaching Assistant TBD


# Goal and Scope

Developing software for robot systems is challenging as they must sense, represent, and actuate in the physical world. Sensing the physical world is usually noisy, the knowledge and representation of the world is incomplete and uncertain, and actuating in and on the world is often inaccurate. In this class, we will explore software engineering approaches to cope with those challenges. You will learn to use domain-specific abstractions, architectures, libraries, and validation approaches and tools to safely perform robot activities like motion, navigation, perception, planning, and interaction. The expectation is that this course will open up new career options in robotics for our students. The course requires no prior knowledge of robotics.

# Class location and time
* Tuesday and Thursday from 11:00AM to 12:20PM 
* Classes will be in person at ISC 0248, with most lectures on Tuesdays and labs on Thursdays
  * Allow yourself extra time to get to the classroom. Note that not all sections of ISC are connected on every floor.

# Office Hours
* Trey Woodlief: Mondays 2-4pm, Wednesdays 10am-12pm, ISC 2317. Online meetings or other times available by appointment. 
* Teaching Assistant TBD

# Prerequisites
CSCI 303 and/or CSCI 304 are recommended. Robotics lives at the intersection of many different disciplines. This course assumes a working familiarity with Python. We will cover basic elements of necessary algorithms and concurrent programming; students should be prepared to self-study these materials in more depth if necessary. If you are concerned about your preparedness, schedule a meeting with the instructor.


# Tentative Schedule

| Week | Lecture Date | Lecture Topic                                   | Quiz # | Quiz Topic                | Lab Date                                 | Lab # | Lab Topic                                                       |
|------|--------------|-------------------------------------------------|--------|---------------------------|------------------------------------------|-------|-----------------------------------------------------------------|
| 1    | 8/27/2026    | Intro                                           | 0      | Taking Stock (not graded) |                                          |       |                                                                 |                                                             |
| 2    | 9/1/2026     | Distinguishing Development Features             | 1      | Thinking about robots I   | 9/3/2026                                 | 1     | ⭐ Setting up ROS + Mini Lecture                                |
| 3    | 9/8/2026     | Software Machinery                              | 2      | Thinking about robots II  | 9/10/2026                                | 2     | ⭐ ROS + Mini Lecture                                           |
| 4    | 9/15/2026    | Sensors & Noise Management                      | 3      | State Machines            | 9/17/2026                                | 3     | Types & Machines + Mini Lecture                                 |
| 5    | 9/22/2026    | LLMs in Robotics                                | 4      | Sensors & Noise           | 9/24/2026                                |       | ***Guest Speaker***                                             |
| 6    | 9/29/2026    | _(No Class or Office Hours; Instructor Travel)_ |        |                           | 10/1/2026                                | 4     | Sensors & Noise _(No Class or Office Hours; Instructor Travel)_ |
| 7    | 10/6/2026    | Abstractions & Perception                       | 5      | TBD                       | 10/8/2026                                |       | _(No Class; Fall Break)_                                        |
| 8    | 10/13/2026   | Controlling your Robot                          | 6      | Perceptions & Abstraction | 10/15/2026                               |       | ***Midterm Exam***                                              |
| 9    | 10/20/2026   | Tradeoffs in Planning                           | 7      | Controls I                | 10/22/2026                               | 5     | Perception                                                      |
| 10   | 10/27/2026   | Graph Navigation                                | 8      | Controls II               | 10/29/2026                               | 6     | ⭐ Ethics _(Interactive Lab)_                                   |
| 11   | 11/3/2026    | _(No Class; Election Day)_                      |        |                           | 11/5/2026                                | 7     | Planning                                                        |
| 12   | 11/10/2026   | Coordinates & Transformations                   | 9      | Graph Navigation          | 11/12/2026                               | 8     | Pose Transformations                                            |
| 13   | 11/17/2026   | Specs, V&V, Safety                              | 10     | Coordinate Transforms     | 11/19/2026                               | 9     | ⭐ Specifying Robots _(Interactive Lab)_                        |
| 14   | 11/24/2026   | Project Work (Remote Office Hours)              |        |                           | 11/26/2026                               |       | _(No Class; Thanksgiving Break)_                                |
| 15   | 12/1/2026    | Robot Design                                    | 11     | TBD                       | 12/3/2026                                |       | Wrap up & exam/project prep                                     |
| 16   | 12/7/2026    | ***Final Exam*** 2pm-5pm, location TBD          |        |                           | Congrats on completing another semester! |

## Important Dates:
* Add/drop deadline: September 4
* Withdrawal period begins: September 5
* Labor day (no office hours): September 7
* Fall Break (no class): October 8-11
* Withdraw deadline: October 26
* Election Day (no class): November 3
* University remote instruction days (no class, remote office hours for project check in): November 23 & 24
* Thanksgiving (no class or office hours): November 25-29
* Final Exam Period: Monday, December 7 from 2pm-5pm. Location TBD.
 
# Course Policies

* If you feel sick, let me know and stay home. We will work on a temporary solution. 
* Students must fully comply with all the provisions of the [William & Mary Honor Code](https://www.wm.edu/offices/communityvalues/sarp/honorcodeandcouncils/honorcode/).
    * All quizzes are taken live during class time. Collaboration or use of any outside materials is strictly prohibited. 
      * If you anticipate needing to miss class when a quiz is scheduled, let me know as early as possible, and we will schedule a makeup quiz during office hours. 
    * The Labs and Final Project are individual assignments unless otherwise noted in the assignment. 
      * Students may use any outside resources in completing these assignments, including using generative AI and discussing with classmates, with the following exceptions:
        * Students may not share code with other students.
        * Students are responsible for any code that is used, regardless of source.
      * Each student must be able to *fully explain* all code and implementation details of their solution as though the student had written all code from scratch. If generative AI helped you to outline a solution or fix a bug, you must be able to fully explain the current working version of the code at a level of understanding that demonstrates command of course concepts and a familiarity with the tools and techniques of the labs.
      * These assignments will be turned in by a live demonstration of the solution to the instructor during Thursday class sessions or office hours.
      * ***A correct and functional implementation that you cannot explain how it functions and why it relates to course concepts will result in at most half credit.***
    * See the course posting in Blackboard for instructions and submission of the video assignment.
* Labs:
  * Labs marked with a ⭐ will earn full credit if presented within one week after they are due, 50% credit within two weeks, and 10% after two weeks. For example, Lab 1 will be assigned on Thursday, September 3rd and can be presented for full credit any time through the end of class on September 10th, for 50% credit through the end of office hours on September 16th, and will receive 10% credit afterward.
  * Labs not marked with a ⭐ can be turned in at any point before the Final Exam Period. They are listed in the class schedule based on the suggested timeline to stay "on pace" with the course.
  * Labs can be turned in during any lab period or during instructor office hours. 
* Students are responsible for all missed work. It is also the absentee's responsibility to get all missing notes or materials.
* This course is designed around students completing lab assignments on a personal laptop. All software needed is free and guides will be posted. If you anticipate any issues related to the format, materials, or requirements of this course, please meet with me outside of class so we can explore potential options.

# Student Success

* William & Mary accommodates students with disabilities in accordance with federal laws and university policy. Any student needing accommodation based on the impact of a learning, psychiatric, physical, or chronic health diagnosis should contact [Student Accessibility Services](https://www.wm.edu/offices/studentsuccess/studentaccessibilityservices/) at (757) 221-2512 or sas@wm.edu to determine if accommodations are warranted and to obtain an official letter of accommodation.
* There are many resources to help navigate emotional, psychological, physical, medical, and material concerns, including: 
  * Counseling Center at (757) 221-3620. Services are free and confidential.
  * Health Center at (757) 221-4386.
  * Dean of Students at 757-221-2510. 
  * The free Timely Care app, which gives students access to 24-7 remote counseling support. Information about the Timely care app can be found through http://timelycare.com/wm

# Tentative Grade Distribution
* 9 Labs: 40 points; lowest 2 labs will be counted at half weight, but labs marked with ⭐ will count full. 7 labs at 5 points each + 2 labs at 2.5 each.
* 1 Midterm: 10 points
* 1 Final: 35 points; combines written final with final project. Higher of the two will be weighted 25 points, lower will be weighted 10 points.  
* 1 Video: 5 points; 2 points for initial submission, 3 points for presentation.
* 11 Quizzes: 10 points; lowest quiz is dropped. 10 Quizzes at 1 point each. 

# Letter Grade

| Grade | Point Range |
|-------|-------------|
| A     | [93, 100]   |
| A-    | [90, 93)    | 
| B+    | [87, 90)    | 
| B     | [83, 87)    | 
| B-    | [80, 83)    | 
| C+    | [77, 80)    | 
| C     | [73, 77)    | 
| C-    | [70, 73)    | 
| D+    | [67, 70)    | 
| D     | [63, 67)    | 
| D-    | [60, 63)    | 
| F     | [0,60)      |

# FAQ
 * **Is this course for me?**
   * This is a class for students who have no or limited experience in  robotics but are interested in learning more about how we develop systems that interact with the physical world. Note that the material and schedule is likely to be tweaked as the course evolves, so you need to be comfortable taking an exploratory class with us.
 * **What is this course NOT about?**
   * This class is not about AI (though we will touch on it briefly in a few sections), mechanical design, or electronic design. It is mainly about how to build software that will operate mobile robots in the physical world.
 * **What is the structure of the course?**
   * This class will include multiple development labs, a team project, quizzes, and a written midterm and final exam. 
 * **What robot will be used?** 
   * Drones, all in simulation. Our focus is on the software.
