---
layout: post
title:  "Degree Tracker for College and Graduate Students"
date:   2022-11-28 20:37:00
category: projects
image: assets/images/degree_tracker_laptop_phone.png
imageGPA: assets/images/gpa_widget_variation.png
imageSIS: assets/images/SIS.png
---

The Degree Tracker was created as a group project for the Information and Interaction Design course in the Master's in Human-Computer Interaction (HCI) program at the Rochester Institute of Technology (RIT) in the fall of 2022.

Our main goal was to design a user-friendly system for degree management for college and graduate students at RIT. We initiated the project by conducting unstructured interviews with students and discovered that the majority of them identified areas for improvement. Specifically, they expressed a preference for a single system to track their academic progress, manage academic requirements, and enroll in classes, rather than having to use multiple systems.

<center><img src="{{ page.imageSIS | relative_url }}" alt="" style="width:auto;height:auto;"></center>

#### **The Solution**

Our solution is an interactive dashboard where students can easily manage and monitor their academic progress toward degree completion. The dashboard allows students to stay on top of their academic program by enabling them to keep track of their current academic standing and plan for future academic terms. It includes information about past courses (with credits and final grades), current enrollment, and future requirements. It also displays program milestones and specific alerts to inform students of time-sensitive information.

#### **Contextual Inquiry**

After identifying the issue we wanted to address, we conducted semi-structured interviews with ten college and graduate students at RIT. During the interviews, we asked participants about their experiences using the current SIS system and their interest in a system like the Degree Tracker. After the interviews, we coded participants' responses to create the [affinity diagram](https://miro.com/app/board/uXjVPTZU5TE=/?share_link_id=248432349161) linked below.

<iframe width="768" height="432" src="https://miro.com/app/embed/uXjVPTZU5TE=/?pres=1&frameId=3458764534468825816&embedId=607705626655" frameborder="0" scrolling="no" allow="fullscreen; clipboard-read; clipboard-write" allowfullscreen></iframe>

During the contextual inquiries, we asked participants to share ideas for features they would like to see in a new system. Six participants shared the following ideas:

- Display academic requirements categorized by major and minor.
- Integration of SIS and other systems, such as eServices, for managing payments.
- Visual representation of information, such as progress bars and charts.
- Calendar view for important dates, such as add or drop times.
- A more user-friendly approach to finding classes based on requirements.

In addition to the ideas shared by participants, we created a list of other desirable features for the Degree Tracker based on contextual inquiry and our own experiences. We defined the project scope and outlined the general characteristics of the Degree Tracker as a single-page dashboard with the following elements:

- Simplified display of academic requirements, including a breakdown of major and minor coursework.
- Visual representation of the number of credits needed to graduate.
- Visibility of important dates and reminders for add and drop times.
- Automated search for specific courses based on academic requirements.
- Improved accessibility for scheduling appointments with advisors.
- Display of the course schedule.

#### **Personas and Antipersonas**

We used the gathered information and conducted a thematic analysis to develop four personas that represent the potential user base for the Degree Tracker. We also created three 'anti-personas' to assist us in further defining the user needs that our Degree Tracker aims to address.

#### Primary Persona

| Jeff |
| ---------------------- |
| **Degree:** B.S. in Electrical Engineering |
| **Age:** 19 years old |
| **Background:** Jeff is a full-time undergraduate student living on campus. He is in his second year and is uncertain about the courses he needs to take the next semester. He plans to meet with his advisor to seek help with course planning and registration.|
| **Goals in SIS:** Jeff uses SIS to track his degree progress. During advisement time, he uses SIS to view the courses he needs to take by accessing the "My Academic Requirements" page.|
| **Current Challenges in SIS:** Jeff finds SIS confusing due to the overwhelming amount of information it presents. The system has numerous menus and disconnected pages. Jeff would prefer a streamlined page where information regarding his academic progress and other university requirements is organized in an easily accessible and understandable manner.|

#### Alternate Personas

| Amit |
| ---------------------- |
| **Degree:** M.S. in Computer Science |
| **Student Type:** Full-time graduate student lives near campus in Rochester, NY.|
| **Age:** 26 years old |
| **Background:** Amit is a second-year student from New Delhi, India. He is currently in his second year of the program. Amit aims to fulfill all graduation requirements by the end of the year. He dedicates at least six hours per semester to planning classes outside of SIS. This includes consulting with faculty and meeting with the academic advisor to seek advice on graduation requirements and program electives. His goal is to pursue a career in the tech industry in the US after graduation, which motivates him to carefully track his degree progress.|
| **Goals in SIS:** Amit uses SIS primarily for searching and enrolling in classes. He is particularly interested in two functionalities of the SIS system: searching for classes and enrolling in them.|
| **Current Challenges in SIS:** Amit believes that SIS works well for academic purposes. However, he wishes there was a more convenient way to track his progress against degree requirements. He has attempted to utilize the "Enroll by My Requirements" option but encounters an error message every time.|

| Maria |
| ------------------------- |
| **Degree:** B.S. in Mechanical Engineering |
| **Student Type:** Transfer undergraduate student, lives off-campus and commutes to RIT. |
| **Age:** 20 years old |
| **Background:** Maria is a third-year student majoring in mechanical engineering. She resides in Rochester off-campus and recently transferred from Monroe Community College (MCC) after completing her first two years of courses there. After going through a lengthy onboarding process with her advisor to determine transfer credits and plan her first semester of courses, Maria now aims to accomplish as much as possible independently without relying heavily on her advisor.|
| **Goals in SIS:** Maria's goals in SIS include identifying her transferred credits from MCC and determining how they fit into the roadmap for an undergraduate mechanical engineering degree. She also needs to calculate her cumulative GPA for future co-op applications and plan her remaining courses semester by semester.|
| **Current Challenges in SIS:** Maria finds it challenging to determine how her transfer credits impact her cumulative GPA, as there is no clear breakdown of how it is calculated. She would like better clarity on which requirements her transferred courses have fulfilled. Additionally, she struggles to understand the sequencing of courses and the presence of prerequisites, making it difficult to create a comprehensive multi-semester roadmap for the remaining courses in her degree.|

| Adam |
| ------------------------ |
| **Degree:** B.S. in Computer Science |
| **Student Type:** Full-time undergraduate student lives on campus at RIT. |
| **Age:** 22 years old |
| **Background:** Adam is a full-time student at RIT from Madison, WI, currently in his final year of pursuing a bachelor's degree in Computer Science. Adam typically spends 2-3 hours per semester in SIS, focusing only on finding the necessary classes for the upcoming semester. As he is in his fifth year at RIT, he rarely meets with his advisor and relies on SIS to access his academic requirements.|
| **Goals in SIS:** Adam's primary goal in using SIS is to maximize efficiency. As he approaches his last year, he believes that tracking a student's progress should be straightforward and hassle-free.|
| **Current Challenges in SIS:** Adam finds that there are an excessive number of menu options and screens in SIS, and occasionally experiences issues with the system not saving his progress.|

#### Anti-Personas

| Susan |
| ------------------------ |
| **Degree:** Taking a single class |
| **Student Type:** Not Matriculated, lives in Rochester, NY. |
| **Age:** 29 years old |
| **Background:** Susan is employed full-time and is currently enrolled in only one class at RIT. She is not currently enrolled in a specific academic program but is considering returning to school. Susan is currently content with taking one online class at RIT without committing to a specific program.|
| **Reason(s) why the goal is unachievable:** Since Susan is not matriculated into a program, she does not have the means to track her academic progress. The objective of the new system is to assist students in effectively monitoring their progress toward graduation. As Susan is not tracking her progress, she does not have an overview of the number of classes remaining until graduation.|

| Seema |
| -------------------- |
| **Degree:** Electrical Engineering Alumna |
| **Student Type:** Graduated student, lives in New York City |
| **Age:** 29 years old |
| **Background:** Seema completed her MS degree in Electrical Engineering at RIT two years ago. Following graduation, she began working as an ML Engineer at DataDog, a startup specializing in cloud and software technology based in New York City. Her current job has inspired her to contemplate pursuing a Ph.D. in Computer Science.|
| **Goals in SIS:** Seema's goal in SIS is to download unofficial transcripts in order to complete her Ph.D. application package.|
| **Reason(s) why the goal is unachievable:** Alumni are provided access to unofficial transcripts in SIS, but they must renew their accounts on an annual basis. Seema has not utilized any RIT systems since her graduation, and she lost access to SIS a year ago.|

| Oliver |
| --------------------- |
| **Degree:** Undergraduate Transfer |
| **Student Type:** Incoming Transfer, lives in Rochester, NY. |
| **Age:** 22 years old |
| **Background:** Oliver transferred from a SUNY school and is currently enrolled at RIT.|
| **Goals in SIS:** Oliver's goal in SIS is to have a comprehensive view of his course history, including grades, from both RIT and his previous university.|
| **Reason(s) why the goal is unachievable:** While RIT accepts transferred courses, the original grades received are not accounted for. Instead, a 'T' grade is assigned to indicate that the course was transferred. Additionally, the transferred course does not contribute to the GPA calculation, which can lead to potential confusion regarding the impact of the grade.|

#### **Prototypes**

Our group drew sketches of Degree Tracker, including the home page and various features. (I have made [my sketches](https://drive.google.com/drive/folders/10LZ1iaGz-HTanbz0EtDXiNE5PKfCXMLc?usp=sharing) available as scans.) These drawings served as a starting point for the [low-fidelity prototype](https://www.figma.com/file/X1vC87os03FhZA2rFXk2HN/HCIN620---Milestone-4-Wireframes?type=design&node-id=0%3A1&t=K92EdE5zSn65oa9t-1).

After several rounds of review and discussions, we developed the high-fidelity prototype of the Degree Tracker for desktop/laptop and smartphone. We utilized icons and widgets from the [Material 2 Design Kit](https://www.figma.com/community/file/778763161265841481) and adhered to [RIT's branding guidelines](https://www.rit.edu/brandportal/) for the overall visual design of the system.

During this stage of the project, my focus was on prototyping the header, notifications/alerts, and the academic card (the first box). For the section displaying profile information, overall progress, degree completion, and overall GPA, my objective was to create a data dashboard that offers real-time information to students. The high-fidelity prototype for desktop/laptop is available below. (Note: Activate the prototype by clicking on it, then hover over the "i" symbols to see the tooltips.)

<iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="800" height="450" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Fproto%2FhClgra6vK9LITwIlbGC9JC%2FDegree-Tracker---Hi-Fi-Prototype%3Fkind%3D%26node-id%3D284-5977%26page-id%3D0%253A1%26scaling%3Dscale-down%26starting-point-node-id%3D284%253A5977%26viewport%3D2548%252C130%252C0.14" allowfullscreen></iframe>

#### **Usability Testing**

We conducted a within-subjects A/B experiment with five RIT students to test our high-fidelity prototype against the "My academic requirements" page in the SIS system. Our aim was to explore the following questions:

1. Is the RIT Degree Tracker more effective and easier to use than the SIS system?
2. Do users prefer the RIT Degree Tracker over the SIS system?

During the 30-minute testing sessions, we asked participants to complete three tasks while verbalizing their thoughts. We alternated the order of presentation (SIS vs. Degree Tracker) for counterbalancing. The measurements recorded for each task included task completion, time on task, mouse clicks, user preferences, and usability (10-question SUS questionnaire). The tasks were as follows: (1) find the credits or classes needed to graduate, (2) find your GPA, and (3) find current course details. Additional details about this user testing study are available upon request.

After completing the tasks, we asked participants to take a post-test questionnaire where they rated the importance of those tasks. All participants considered viewing the times and dates of the courses offered as *very important*, while 60% considered finding the number of courses remaining as *very important*. Finding the overall GPA was deemed *very important* by 20% of participants and *important* by 40%. Overall, the majority of participants regarded the tasks as *important* or *very important*.

The Degree Tracker was unanimously preferred in the SUS questions. Upon analyzing the answers, we found that the Degree Tracker had an average SUS score of 98.5, while the SIS system had an average score of 32.5. All participants *strongly agreed* that the new prototype was easy to use. The reasons cited for its ease of use included the ease of finding information and a reduced sense of being overwhelmed. All participants *strongly agreed* that they felt confident using the new prototype.

| Participants | SUS Score of the SIS webpage | SUS scores of the RIT Degree Tracker |
| ------------ | ---------------------------- | ------------------------------------ |
| P1           | 40                           | 100                                  |
| P2           | 47.5                         | 100                                  |
| P3           | 12.5                         | 97.5                                 |
| P4           | 30                           | 95                                   |
| P5           | 32.5                         | 100                                  |
| Average      | 32.5                         | 98.5                                 |

In the SUS questions, four students *agreed* that the current SIS system is unnecessarily complex, while one student *strongly agreed*. This was evident when comparing the number of clicks between the two systems. The new prototype required significantly fewer clicks compared to the SIS system, and the tasks were completed in less time using the high-fidelity prototype.

Participants provided ratings for each interface using the SUS questionnaire. The SUS scores for each interface per participant, as well as the average scores, indicate that the usability of the RIT Degree Tracker (98.5) is above the industry average, while the SIS system (32.5) falls below the industry average. The industry average SUS score is 68 (Affairs, 2013).

#### **Conclusions and Future Research**

One of the most significant findings from the usability testing was that the majority of participants encountered difficulties in viewing their GPA within our prototype. Although all participants were able to complete the task, it was not immediately apparent to them how to reveal their GPA. In the prototype, users need to hover over the “eye” icon to show the number. We believe that adding a Show/Hide tag to the widget could be a potential improvement. However, conducting an A/B test to compare both versions would help determine which approach is more effective.

<center><img src="{{ page.imageGPA | relative_url }}" alt="Overall GPA widget variations" style="width:300px;height:auto;"></center>

Overall, our prototype was well received by participants. The new prototype was unanimously preferred over the SIS system. While one user felt that the SIS system had more information available, all participants found it easier to complete the tasks in the Degree Tracker compared to the SIS system. All participants strongly preferred the Degree Tracker. This preference was also reflected in the SUS scores, with our prototype scoring 98.5 compared to the current SIS system’s score of 32.5.
