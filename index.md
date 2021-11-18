---
layout: default
course_number: CS481-RT
title: Senior Software Design I
---

--- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---

## CS481-RT: Senior Software Design I (YCAS Radio Telescope Project)

## Fall 2021

--- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---

This is the website for CS 481-RT (Senior Software Design I), Fall 2021 for the YCAS Radio Telescope Project at [York College of Pennsylvania](http://www.ycp.edu) .  All information related to the course will be posted here.

## Links

* [Syllabus](syllabus.html)
* [Schedule](schedule.html)

## Project Ideas for This Year (Fall 2021 and Spring 2022)
The following is a list of the various ideas for the project for this coming Fall 2021 and Spring 2022.  Todd Ullery and Kerry Smith of the YCAS will be providing additional requirements and setting priorities for the development over the course of this coming year.  It is your job to collect those requirements and priorities from them.  I might add a few items to investigate, as well.  You are not limited by this list - please also feel free to offer your own ideas for improving, enhancing, and/or expanding the capabilities of the Radio Telescope, while also allowing yourself to explore your own personal interests.  Ultiately, your YCAS clients will be determining your tasks and priorities (in consultation with me).

NOTE: The primary focus of the coming year's effort is to finish SW development - focused primarilly on the ControlRoom Application (including RT simulation with the RT Unity model) and the Admin Phone App, expand unit/module testing, and then create and perform integration tests between the ControlRoom, the Admin Phone App, and the Radio Telescope HW.  You will be working directly with the electro-mechanical HW in the Project Workspace and will need to become quite comfortable with both its function and operation - expanding upon the work this past Summer's Engineering Capstone I team accomplished.  As such, it will greatly benefit you to (re)familiarize yourselves with the Radio Telescope HW as early in the semester as possible.  Several of the team memebers have already worked with it, and they will be helping to bring you all up-to-speed.

## YCAS Must-Haves (subject to change):

* Finish the Admin Phone App and perform integration testing with the ControlRoom to interface with the Radio Telescope HW.

* Finish the ControlRoom application, including SW simulation of the RT through the Unity model.  Also, develop and perform full integration testing between the ControlRoom App and the RT HW mount.  This must include both "Happy Path" and exception level testing.

* Collect and charaterize the sensor data coming from the Embedded Sensor System (ESS) for normal vs abnormal operation.

* While collecting data, add a service that watches the data being collected, looking for possible instances of Radio Frequency Interference (RFI) and capturing lightning or flight (flightaware.com) information to be used to help explain why anomolies in a particular signal occurred. What other sources of RFI can be researched?

* Integrate existing Open Source software for displaying radio telescope data.  This work wa started last year - there is more yet to do.  Check with Todd and Kerry for what they want.

* Verify the control room WiFi can relay the Admin Phone App commands directly to the RT controller - bypassing the AWS path.

* Add an outdoor audio speaker to the control room allowing live or canned messages to be played automatically or via the Admin Phone App video screen. If Kerry sees someone climbing over the fence, he could give an audio warning by pressing a button. Another button (existing) can stow the telescope.  This work was started last year - we have the HW.

* Determine the actual monthly AWS expenses that the YCAS will incur.  Last year's team significantly reduced the complexity and cost, but we will still need to determine the actual cost reductions, and concentrate on keeping them as low as reasonably possible.  We need to keep the monthly cost in the $20 to $40 range.

* A review of the project's use of technology in order to consolidate, where possible, the multiple platforms used to create the product. I agree some cannot be changed, but let's review them anyway. This is a long-term software maintenance issue.  Consult with Todd Ullery on this, since he will ultimately be assuming responsibility for the Radio Telescope SW.


## YCAS Like-to-Have (subject to change):

* Todd Ullery wants to hear what the software developers think would be useful for the project.

* The VR/AR team should continue to update the Rudy Park model to allow the night sky and data points to be displayed.

* Improve the log reports in the control room and AWS to make it easier to verify the health of the system.


## Professor Hake's Ideas (subject to change):

* I think we should continue to concentrate on bringing the website "in-house" to the Control Room server, with limited access to start for members only, to limit web traffic through the park's network.  This was started last year - there might not be much more work to do.

* The team needs to button-up the entire project this year, between Fall and Spring.  With 4 students returning to the project, we're in good shape for continuity's sake.  Spin-up last year in CS481 went well, but it still took a great deal of time to get everyone up-to-speed.  I expect this year to go even more quickly.

## News
* 11-18-21: Moved assign07 (Final Report and Peer Evals) to Sat, 12-11-21 by Noon

* 11-18-21: Moved assign07 (Final Presentation) to Weds, 12-8-21, from 3:00p to 5:00p in KEC125.

* 9-24-21: Moved Assign06 (50% Working System) to Weds, 11-10-21.

* 9-24-21: Moved Assign05 (Minimum Working System) to Weds, 10-20-21.

* 9-15-21: Moved Assign04 (Design) due date to Weds, 9-29-21.

* 8-21-21: All students in CS 481 will be meeting on the first day of class (Weds, 8-25-21) to go over the syllabus and requirements for the course.  The Radio Telescope will have a longer meeting, since it is your regular meeting day.

* 8-21-21: The Radio Telescope team will meet on a weekly basis for status report, and assignment and Milestone presentations on Wednesdays in-person in KEC 118.  Fridays will be reserved for team project work days to be arranged amongst yourselves.
