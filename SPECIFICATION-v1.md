# CSE12B D1 – Project Outline: StudyBuddy

**Group 19**

## Team members

* Teodor Musat – 6433111 – teodormusat
* Mihai Theodor Lisman – 6665233 – mlisman
* Florea Andrei Serban – 6711154 – asflorea
* [Name 4] – [Student number] – [NetID]
* [Name 5] – [Student number] – [NetID]

## Project scope

* **Domain:** Study group coordination
* **Target user group:** First-year international students
* **System goal:** Peer-to-peer matching
* **Platform:** Responsive desktop web application

## Project description (subject to change)

We will build StudyBuddy, a web application that helps first-year international students at TU Delft find study partners and organise study sessions. Many of these students do not know anyone yet, are unfamiliar with how studying works here, and struggle to find peers in the same courses who are available at the same times and can help each other.

Students create a profile with their courses, preferred language and a rough time preference such as mornings or evenings. They also describe in their own words what they want from a study group, for example: "I'm good at programming but struggle with ADS proofs, and I like explaining things out loud." An LLM turns this text into tags from a fixed list (strengths, topics they need help with, and study style), which students can review and edit before saving.

Students then choose one, several or all of their courses, and decide whether they want a separate group per course or one combined group for several courses. The system ranks compatible students based on shared courses, language, time preference and complementary skills, so that someone strong in a topic is matched with someone who needs help in it or vice versa. The LLM also writes a short explanation of why each match was suggested.

Because schedules change from week to week, group members enter their free time slots each time they want to meet. The app highlights the times that suit everyone, avoiding clashes with their other groups, and suggests the best one, which members can accept or replace by voting. Members also propose and vote on where to meet; library rooms link to the library's booking page. Sharing a phone number or other contact handle is optional and visible only to the group.

We chose this target group because many international first-years study in our own year, so interviews and on-campus user testing are easy to arrange. We use AI where it adds real value, such as understanding students' own descriptions and explaining matches, while keeping users in control: they can edit their tags, and decisions that people make better, such as time and place, are left to the group.

## Team diversity

Our team consists of 5 students from Romania, with skills in [for example: frontend development, design, research]. All of us experience/experienced the first year as an international student, which gives us direct insight into our target group. We lack neurodivergent members, a wider age range or diverse nationalities, so we will rely on interviews and user testing to include perspectives outside our own.
