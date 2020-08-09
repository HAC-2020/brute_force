# brute_force
HAC-2020 team brute_force:
1. Elio Jordan Lopes
2. Devansh Mehta
3. Shaolin Kataria
4. Aayush Sharma
5. Ritik Gupta

# Our Idea: 

#### Please find the screenshots, and documentation in the repo and the PDF uploaded. Note we have attached two screenshots of the app in the end of this Readme file
[Click me to Check our work on YouTube](https://www.youtube.com/watch?v=MY9zdq7y7Cg)


**PROBLEMS IN EXISTING TECHNOLOGY AND MOTIVATION OF OUR WORK**
All of our team members are college-going students and we are facing a lot of problems in communicating with our college administration and teachers. Our college is using some remote education apps for online classes- Microsoft Team app and zoom app for administrative meetings and individual one to one meetings. Below written problems are some major one that teachers and students are facing in existing technology:-

•	But during our online classes, some random students add themselves up in the online session and disturb the class either by abusing or harassing teachers and other students (We all must have seen this behavior all around the nation through WhatsApp forwards), this act spoils the whole energy of the class and in turn, the teacher decides to end the class.

•	Teachers also complained about the online test procedures, as there is no way a teacher can invigilate students while taking exams as students can open up the book in their home. So, teachers are demanding a way to invigilate students while taking the exam.

Our Second Part of the solution focuses on Covid19 patients and doctors treating them. We saw in national news channels that there is an isolation wall between Covid19 patients and doctors and through a single-window they are transferring food medicines and other essentials. Also it’s been difficult to take temperature and heartbeat reading of the patients keeping social distancing in mind. And due to weakness a patient can’t shout someone for help or old patients and paralytic patients can’t even press a bell to call for help. So to solve all these problems we have innovated an IoT device called RoboCare to help doctors and patients.
Also we have made a Covid19 Cases and range detector.

# SOLUTION BRIEF OVERVIEW 
**Our solution consist of two parts: EMAGISTER**
1.	First part is a remote education android app which resolves all the problem stated above. It contains all the features a student will want in his/her app. We tried to involve every activity that we use to do in offline college times in this App.
It consists of Video call functionality with a special feature of blocking students who are speaking abusive or bad words during a live session. The student will be reported to the admin of the app and all the records of the blocked student will be sent to the admin app. Admin can unblock the student again. 
Then our app contains a chat room for each classroom a student is enrolled in, it will allow the students and teachers to communicate as they use to do in Offline College.
Then comes the appointment feature. Before contacting any teacher we have to make an appointment with him/her to ask for their time. So our App includes this cool feature of appointment for the students. This reduces the chaos and brings the working thing so that follows proper protocol.
Teachers wanted an invigilation system to invigilate students during the test. In our App we provided this feature by camera proctored examination feature. Under this a teacher can proctor all students through their webcams while the students are giving tests, also the teacher can pass their voice in the whole class to convey messages during tests.
Also our app has a feature of assignment submission. The teachers can upload the assignment questions along with the due date and students on the other hand can upload the solutions of these tests on the app itself.
 
**2.	Our second part of the solution consists of an IoT device, an Image algorithm, and an android app. combining all makes a ROBOCARE package for helping Covid19 doctors and patients.**
To help treat Covid19 patients we invented a robot that can be used as an essentials deliverable device or like a wheelchair. The robot work on the gesture made by hands. We don’t have to touch anything to operate the robot just make gestures and transfer medicines and food to patients through this robot. 
Due to Covid19 treatment people are becoming weak so this robot can act as a wheelchair also for easy transportation through mere gestures.
 
Also we devised an IOT device that will measure the temperature and heartbeat of the patient and will transfer all this data to the cloud which is connected with an App that will be updated on a real-time basis and will give alerts to doctor. This will help in social distancing treatment.
Through our Image processing algorithm, we will allow the patients to make some face gesture and through these gestures, an alarm will ring in the doctor’s phone having our android App.
Along with this we have a covid19 case detector.

# SOLUTION DESCRIPTION

**1.	Our first part of the solution consists of a remote education app which figured out to solve some of the very important flaws in existing technology. These are the detailed working technology behind features of our App:-**

**CLASSROOM:** In classroom section students can attend one to one and one meeting with their teachers and class mates. Also teachers can conduct online classroom in this particular section. The main key point of this feature is that we have built an algorithm that detects and block students for using abusive and harassing words. For this we have used IBM speech to Text service to convert the speech of students into text using which our abusive word detection algorithm can act to work. These blocked students’ information will be visible in admin’s section and they can easily Un-Block these students through the app. But if the students are blocked they cannot re-enter that video call channel. This feature is not available in any education app.

**APPOINTMENT:** In real world we ask for an appointment with our HODs, teachers and other administrative staff before a proper meeting but this feature is not available in any remote education app till now. So to make it real we involved this feature which allow students to make appointments and follow a hassle free protocol to contact their mentors.

**CHAT ROOM:** In every classroom there always use to be a chit chat and fun doubt session between teachers and students. To make this offline feature come to live we introduced chat feature in our app to help the teachers and students convey their message and talk seamlessly with our real-time chat system.

**ASSIGNMENTS:** Apps like zoom does not offer features like assignment submission. In our App we are allowing the teachers to upload the assignment along with the question file and due date and all these information will be saved in Google cloud. On the other side the students can download the question file and submit their solution file on the app which can be later reviewed by the teacher. 

**CAMERA PROCTORED QUIZ:**
Many teachers and tutors are tensed for a secure testing platform. There many platforms which block internet access during test but students manages to cheat through different devices and book materials. To solve this problem we included a Camera proctored test feature through which the teacher can invigilate the test and see all students through their web cam on app and also the teacher can pass any message to the whole class while taking exam this bring reality and security in the work flow.


**2. ROBOCARE**
Our second part of the submission consist of a ROBOCARE APP for Covid19 doctors and patients also we have built a robot to transfer essential good to patients keeping social distancing in mind which moves following gestures by hand. Also this can be used as a wheelchair for week patients. And in final touch we devised an Image learning algorithm which is connected to the firebase cloud storage and give alerts in app when the patient make face gesture to call for help since they can speak and move their body a simple gesture will do good for these patients.

We are using an ESP8266 microcontroller to connect the device with the cloud and with the image processing system. And our app is also connected with the same cloud storage so if patient will make gestures, an alarm will ring in the app. Also the temperature and heartbeat reading will be sent to cloud in real-time basis and all of this will be available in our app through which doctor can make report of patients following social distancing.

## Screenshots:
![app1](https://github.com/HAC-2020/brute_force/blob/master/REMOTE%20EDUCATION%20APP/ScreenShots/Screenshot_20200524-161511.png)
![app2](https://github.com/HAC-2020/brute_force/blob/master/ROBOCARE/ROBOCARE%20SCREENSHOTS/Screenshot_20200524-162706%20(1).png)






