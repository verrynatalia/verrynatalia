---
layout: post
title:  "Degree tracker for college students"
date:   2022-11-28 20:37:00
category: projects
image: assets/images/degree_tracker_laptop_phone.png
imageGPA: assets/images/gpa_widget_variation.png
imageSIS: assets/images/SIS.png
---

#### Our Motivation

The Degree Tracker for RIT college students was created as a speculative project in the Information and Interaction Design class taught by Prof. Garreth Tigwell in the Master's in Human-Computer Interaction (HCI) at the Rochester Institute of Technology (RIT) in the Fall of 2022.

Our group of five graduate students worked on a solution to enhance the degree management experience for RIT students. Our goal was to design a user-friendly system where students could keep track of their academic progress, academic requirements, enroll for classes, and other tasks.

The current processes for degree management involve multiple systems that, in some cases, are challenging to access or navigate. One of the primary systems students use is the Student Information System (SIS). The SIS has a "My Academic Requirements" where students can look at the classes they have already taken and pending academic requirements. The SIS system alloww students to generate an academic requirements report in PDF format. Academic advisors also help students with degree management by meeting with them to discuss classes and helping them to plan for classes depenindg on degree requirements. After meetings academic advisors share a degree planning document in PDF or Excel format with students. The document has the list of classes, terms and grades. While the current processes are functional, some students voiced during the contextual inquiry and usability testing they would prefer a simpler process.

<center><img src="{{ page.imageSIS | relative_url }}" alt="" style="width:auto;height:auto;"></center>

#### The solution

Our solution is an interactive dashboard where students can easily manage and monitor their academic progress toward degree completion. The dashboard allows students to stay on top of their academic program by allowing them to keep track of their current academic standing and plan for future academic terms. It includes information about past courses (with credits and final grades), current enrollment, and future requirements. It also displays program milestones and specific alerts to inform students of time-sensitive information.

#### Contextual Inquiry

After identiying the issue we wanted to address we conducted a semi-structured interview with ten college and graduate students at RIT. During the interviews, we asked participants about their experiences using the current SIS system, and also asked about their interest in a system like a Degree Tracker. After the interviews, we coded participants' responses to create an [affinity diagram](https://miro.com/app/board/uXjVPTZU5TE=/?share_link_id=248432349161), which is shown below.

<iframe width="768" height="432" src="https://miro.com/app/embed/uXjVPTZU5TE=/?pres=1&frameId=3458764534468825816&embedId=607705626655" frameborder="0" scrolling="no" allow="fullscreen; clipboard-read; clipboard-write" allowfullscreen></iframe>
###### **Note: You may need to click "See the board" to view the affinity diagram.**

During the contextual inquiries we asked participants to share ideas for features they would like to see on a new system. Six participants shared they would like to see the following:
- Academic requirements displayed by major and minor requirements.
- Integration of SIS and other systems such as eServices for managing payments.
- Visual display of information like progress bars and charts.
- Calendar View for important dates such as add or drop times.
- A more straightforward way of finding classes to enroll in based on requirements

In additon to the ideas shared by participants, we created a list of other desirable features for the Degree Tracker based on the contextual inquiry and our own experienes as students. We defined the project cope and general characteristics of the Degree Tracker as a single-page dashboard with the following elements:
- Simplified display of academic requirements, including breakdown of major and minor coursework
- Estimate for cost in credit hour depending on user information
- Progress bar that shows how many credits are needed to graduate
- Important dates and reminders for add and drop times should be visible
- Automated search for specific courses based on academic requirements
- Make scheduling appointments with advisors more accessible
- Make course schedule visible

### 2. Personas and Antipersonas

We used the information gathered and the thematic analysis to create four personas representing the potential user base for the Degree Tracker. We also created three 'anti-personas' to help us define better the user needs we aim to address with our Degree Tracker.

| Jeff - Primary Persona |
| ---------------------- |
| **Degree:** B.S. in Electrical Engineering |
| **Student type:** Full-time undergraduate student, lives on campus at RIT. |
| **Demographics:** 19 years old |
| **Background:** Jeff is a second year Electrical Engineering student at RIT. This is also his second year in college and he is unsure of the courses he needs to take each semester. He plans to meet with his advisor during course registration to get additional in person help with planning and registering for courses.|
| **Goals in SIS:** Jeff uses SIS to track his degree progress. He uses SIS during advisement time to see which courses he needs to take by looking at the “Academic Requirements” section. He also meets with an advisor to double check that he hasn’t missed anything.|
| **Current Challenges in SIS:** Jeff finds that there are too many menus and different screens which can be confusing. In addition to that, progress is sometimes not saved properly and can be lost. Jeff would like to have a centralized dashboard to make the experience more clear.|

| Amit - Alternate Persona |
| ---------------------- |
| **Degree:** M.S. in Computer Science |
| **Student Type:** Full-time graduate student, lives near campus in Rochester, NY. |
| **Demographic:** 26 years old |
| **Background:** Amit is a national of New Delhi, India. He is a full-time international student in his 2nd year of the program. Amit hopes to meet all graduation requirements by the end of the year. He spends at least six hours per semester planning for classes outside SIS. This includes speaking with faculty and meeting with the academic advisor to receive advice on graduation requirements and program electives. After graduation, he wants to pursue a career in the tech industry in the US. That keeps him motivated to keep careful track of his progress on the degree.|
| **Goals in SIS:** Amit uses SIS to search and enroll in classes. He is mostly interested in two main basic current functionalities in the system SIS, searching for classes and enrolling in them.|
| **Current Challenges in SIS:** Amit thinks the SIS works well for academic purposes. However, he wishes there was an easy way of seeing his progress against degree requirements. Has tried to use the “Enroll by My Requirements” option, but the system prompts an error message every time.|

| Maria - Alternate Persona |
| ------------------------- |
| **Degree:** B.S. in Mechanical Engineering |
| **Student Type:** Transfer undergraduate student, lives off-campus and commutes to RIT. |
| **Demographic:** 20 years old |
| **Background:** Maria is a third year student enrolled in mechanical engineering. She currently resides off-campus in Rochester and recently transferred from Monroe Community College (MCC) after taking her first two years of courses through them. After a lengthy onboarding process with her advisor to sort out transfer credits and the first semester of courses, she would like to accomplish as much as possible on her own without involving the advisor. |
| **Goals in SIS:** To successfully complete her course schedule for next semester and beyond, Maria will need to identify her classes transferred from MCC for credit as well as where they fit on a roadmap for an undergraduate mechanical engineer. She will also need to calculate her cumulative GPA when applying for co-ops in the near future and plan the remainder of the courses she needs to take, semester-by-semester. |
| **Current Challenges in SIS:** Maria finds it difficult to see how, if at all, transfer credits impact her cumulative GPA, as there’s no definitive breakdown of how it’s calculated. She would like to better understand which requirements the transferred courses have satisfied. In addition, she’s having trouble seeing how the courses are sequenced, or which courses have prerequisites, making it difficult to create a multi-semester roadmap of the courses remaining in the degree. |

| Adam - Alternate Persona |
| ------------------------ |
| **Degree:** B.S. in Computer Science |
| **Student Type:** Full-time undergraduate student, lives on campus at RIT. |
| **Demographic:** 22 years old |
| **Background:** Adam is a full time RIT student from Madison, WI in his final year of a Computer Science bachelor’s degree. Currently, Adam spends 2 - 3 hours a semester in SIS. He only spends as much time as needed to find the classes he needs for the following semester. Since Adam is in his 5th year at RIT, he rarely meets with his advisor and uses SIS to view his academic requirements. |
| **Goals in SIS:** Adam’s goal in SIS is to be able to use it as efficiently as possible. While being in his last year, he feels tracking a student’s progress should be easy. |
| **Current Challenges in SIS:** Adam feels there are too many menu options and screens in SIS. Sometimes the user’s progress is not always saved. |

#### Anti-Personas

| Susan - Anti-Persona |
| ------------------------ |
| **Degree:** Taking a single class |
| **Student Type:** Not Matriculated, lives in Rochester, NY. |
| **Demographic:** 29 years old |
| **Background:** Susan works full time and currently takes 1 class at RIT. She is not enrolled in a curriculum and wanted to explore going back to school. Susan is currently not committed to a program at RIT and is content taking one class online for now.
| **Goals in SIS:** Susan’s main purpose in SIS is to view and pay her bill. |
| **Reason(s) why goal is unachievable:** Because Susan is not matriculated into a program, she is not tracking her progress. The goal of the new system is to help students better track their academic progress towards graduation. Susan is not tracking her progress to figure out how many classes she has left until graduation. |

| Seema - Anti-Persona |
| -------------------- |
| **Degree:** Electrical Engineering Alumna |
| **Student Type:** Graduated student, lives in New York City |
| **Demographic:** 29 years old |
| **Background:** Seema earned her MS degree in Electrical Engineering at RIT two years ago. After graduation, she started working as an ML Engineer at DataDog, a New York City cloud and software technology startup. Her current job has motivated her to start planning for a doctorate degree in Computer Science. |
| **Goals in SIS:** Download unofficial transcripts to complete her PhD application package. |
| **Reason(s) why goal is unachievable:** Alumni have access to unofficial transcripts in SIS, but they have to renew their accounts annually. Seema hasn’t used any RIT system since graduation. She lost access to SIS a year ago. |

| Oliver - Anti-Persona |
| --------------------- |
| **Degree:** Undergraduate Transfer |
| **Student Type:** Incoming Transfer, lives in Rochester, NY. |
| **Demographic:** 22 years old |
| **Background:** Oliver transferred from a SUNY school and is now attending RIT. |
| **Goals in SIS:** He would like to see a comprehensive view of his course history (including grades) from both RIT and his other university.|
| **Reason(s) why goal is unachievable:** RIT accepts transferred courses, but does not account for the original grade received. The student will have a ‘T’ assigned as a grade to indicate that it was transferred. The transferred course also will not be accounted for in the GPA, so the grade may cause additional confusion.|

### 3. Prototypes

Our group drew sketches of Degree Tracker, including home page and some features. (I have made [my sketches](https://drive.google.com/drive/folders/10LZ1iaGz-HTanbz0EtDXiNE5PKfCXMLc?usp=sharing) available as scans.) Those drawings served as an starting point for the [low fidelity prototype](https://www.figma.com/file/X1vC87os03FhZA2rFXk2HN/HCIN620---Milestone-4-Wireframes?type=design&node-id=0%3A1&t=K92EdE5zSn65oa9t-1).

After rounds of review and discussions we created the high fidelity prototype of the Degree Tracker for desktop/laptop and smartphone. We utilized icons and widgets from the [Material 2 Design Kit](https://www.figma.com/community/file/778763161265841481) and followed [RIT's branding guidelines](https://www.rit.edu/brandportal/) for the overall visual design of the system.

During this stage of the project, I focused on prototyping the header, notifications/alerts, and the academic card (the first box). For the section displaying profile information, overall progress, degree completion, and overall GPA, my goal was to create a data dashboard that provides real-time information to students. The hi-fi prototype for desktop/laptop is available below. (Note: Activate the prototype by clicking on it, then hover over the "i" symbols to see the tooltips.)

<iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="800" height="450" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Fproto%2FhClgra6vK9LITwIlbGC9JC%2FDegree-Tracker---Hi-Fi-Prototype%3Fkind%3D%26node-id%3D284-5977%26page-id%3D0%253A1%26scaling%3Dscale-down%26starting-point-node-id%3D284%253A5977%26viewport%3D2548%252C130%252C0.14" allowfullscreen></iframe>

#### 4. Usability Testing

We conducted a within-subjects A/B experiment with five RIT students to test our hi-fi prototype against the "My academic requirements" page in the SIS system. We aimed to explore the following questions:

1. Is the RIT Degree Tracker more effective and easier to use than the SIS system?
2. Do users prefer the RIT Degree Tracker over the SIS system?

During the 30-minute testing sessions, we asked participants to complete three tasks while 'thinking aloud'. We changed which version was shown first (SIS vs. Degree Tracker) for counterbalancing. The measurements taken for each task were task completion, time on task, mouse clicks, user preferences and usability (10-question SUS questionnaire). The tasks were: (1) find the credits or classes needed to graduate, (2) find your GPA, and (3) find current course details. Additional details about this user testing study are available upon request.

After completing the tasks, we asked participants to take a post-test questionnaire where they rated the importance of those tasks. All participants considered that viewing the times and dates of the courses offered was *very important*, while 60% considered finding how many courses they had left was *very important*. Finding the overall GPA is *very important* for 20% of participants and for 40% is *important*. Overall, most participants considered the tasks as *important* or *very important*.

The Degree Tracker was unanimously preferred in the SUS questions. After analyzing the answers, we found that the Degree Tracker had a 98.5 SUS average score, while the SIS system had a 32.5 average score. All participants *strongly agreed* that the new prototype was easy to use. Among the reasons why the new prototype was easy to use were that the information was easy to find and it was less overwhelming. All participants *strongly agreed* they felt confident using the new prototype.

| Participants | SUS Score of the SIS webpage | SUS scores of the RIT Degree Tracker |
| ------------ | ---------------------------- | ------------------------------------ |
| P1           | 40                           | 100                                  |
| P2           | 47.5                         | 100                                  |
| P3           | 12.5                         | 97.5                                 |
| P4           | 30                           | 95                                   |
| P5           | 32.5                         | 100                                  |
| Average      | 32.5                         | 98.5                                 |

In the SUS questions, four students agreed that the current SIS system is unnecessarily complex, while one strongly agreed. This appeared evident when tracking the number of clicks between the two systems. There were far fewer clicks in using the new prototype compared to using the SIS system and less time performing the tasks in the hi-fi prototype.

Participants rated each interface using the SUS. The SUS scores for each interface per participant and the average score show that the usability of the RIT Degree Tracker (98.5) is above average, while the SIS system (32.5) is below. The average SUS score is 68 (Affairs, 2013).

#### Conclusions and Future Research

One of the most salient things we noticed during the usability testing is that the majority of participants had difficulties seeing their GPA within our prototype. Although all participants completed the task, it was not evident to them how to reveal their GPA. In the prototype, users must hover over the "eyeball" icon to show the number. We consider adding a Show/Hide tag to the widget could be a way of improving it, however, an A/B test to reach comparing both versions would help identify which version is better.

<center><img src="{{ page.imageGPA | relative_url }}" alt="Overall GPA widget variations" style="width:300px;height:auto;"></center>

Overall, our prototype was well received by participants. The new prototype is preferred over the SIS system unanimously. Although one user felt the SIS system has more information available, all participants considered completing the tasks of the usability testing study was easier in the Degree Tracker than the SIS system. All perticipants *strongly preferred* the Degree Tracker. The preference was apparent in the SUS scores as well; our prototype had a 98.5 score compared to the current SIS system at a 32.5 SUS score.