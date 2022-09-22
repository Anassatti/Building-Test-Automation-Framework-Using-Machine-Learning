# Building-Test-Automation-Framework-Using-Machine-Learning

**Indroduction**

For a couple of years, I was thinking about using machine learning and deep learning in automation and manual testing to save the time spent by the testers and increase their efficiency. There are two areas in that I am targeted regression test and in bug detection.

**What is the Regression test**

In simple words, a regression test is a kind of test testers do after bug fixing to ensure that there is no impact on other functionalities and everything working well.

**Bug**

The bug is an error or exception that happened during the testing process to prevent the UAT from working as expected.

Regression testing is a tedious task and time-consuming, so we use automation testing which can save a huge amount of time and increase team productivity. My idea is to integrate ML&DL, which will increase efficiency and save time as well as provide high-quality output, which is the main purpose of the quality itself. In regards, to the error detection if there is a tool that help  easily to give a full information about the bug, and suggest a solution, it would add a huge value. Also, if we are talking about why not automation testing resolves these issues, the answer because there are many challenges that face UI automation, which makes any effort to overcome these iusses a great effert and will help alot overcome.



**UI Automation Challenges**
1. Complicated Web Applications
2. UI changes
3. Choosing test automation tool
4. Error handling
5.Image comparison

I will divide the projects in two phases

1. ***Phase one**

** Regression Project phases**

I follow below methodology 

![image](https://user-images.githubusercontent.com/73906550/191712373-29a695e9-a32f-4b4c-b911-02b3f4e24ffc.png)





I follow divide and conquer concepts, which means break the projects into sub-projects as the below:

  **1. Building Machine Learning Solution for image processing by trying to detect human faces** 
    **The purpose of this steps is to gain experience in ML**

I finished building the ML model, which detects human faces using Open CV capabilities. The solution showed the results in percentages(Probability), which means the user uploads an image of the same person. If it is the right image, the system will show, for example, 95% John, etc.., the result displayed on the simple HTML page. As we can see below, ML's accuracy in detecting the faces. For example, the ML detects superstar Muhammed Salah's face by scoring him 79.33 probability. Below is a sample of how ML detects faces. Below the results 

![image](https://user-images.githubusercontent.com/73906550/145156222-21200402-d5bd-478b-9898-e6616195b867.png)

Also, I used the model in detect my friend picture

![image](https://user-images.githubusercontent.com/73906550/190891211-6b5aa5cd-9e49-4029-ad52-c28325963c23.png)


**2. Improve ML solution to detect the differences in UI, means comparing two images and detecting what the changes happen**

 1. Integrate ML solution component in the SAS, below structure(Designed by Me as part of this project effort) show that:
 
 ![image](https://user-images.githubusercontent.com/73906550/139382494-58696789-ce51-4ba4-8dfb-c021622c715b.png)


**RegressVisual Tool**

As I mentioned earlier this tool help in regression testing automation effort by allowing manual or automation testers to visually detect any differences in UI. Below is the challenges any software test automation engineer face in UI automation.



I overcome all these challenges in the below RegressVisaul tool architecture:

**Tool Architecture**

![image](https://user-images.githubusercontent.com/73906550/140051684-fc834caf-803f-45e3-8e59-6e574f17eab3.png)

**So how this tool overcome the UI automation challenges**

**Challenge #1**: UI automation testing is time-consuming & complicated. Websites contain frames, tables, and pop-up
windows, so the software test automation engineers need to write complex, time-consuming code to automate and
reach this area.

Impact: This tool does not need to write any codes and save coding time because the tool tests the screen controls and
dimensions automatically by simple function drag & drop.

**Challenge #2**: Change UI constantly challenge.

Impact: This tool deal with screen whatever there is any changes.

**Challenge #3**: Programming Language experience is required to build test automation framework.

Impact: This tool requires no prior technical experience, business user can use it, does not require any building
framework.

**Challenge #4**: UI Error handling.

Impact: The tool has specific module for self-learning from the error and show possible solutions.

**Tool Advantages& Features**
1. No code experience is required
2. Fastest result
3. HTML Report contains summary 
4. Redue automation time
5. Accurate result
6. Jira integration: Means the tool automatically will open Jira issue with screenshot.
7. Integrate with Google Cloud


**How the tools works**

1. Compare two screens, the original screen, and the same screen  through Drag& Drop
2. ML&DL will detect if there are any differences 
3. Generate probability percentage report and the UI name(ex.user registration form, probability score(ex.95%))
4. Generate a complete HTML report showing more details, which help the developers fix the issue

**The tool webpage**

![image](https://user-images.githubusercontent.com/73906550/190892878-7b9d6d15-f76b-4996-a4ab-5690fd027150.png)



***HTML report Generated***

The tool generates an HTML report with the ability to share in the email as a link or attach PDFs and SMS notifications.
The report looks like below

![image](https://user-images.githubusercontent.com/73906550/190888637-9113e7b2-b4b7-472e-acd0-c1c4c827d7be.png)



**Tools & Technology I used:**

1. Python Programming Language
2. Jupyter notebook
3. Anaconda
4. PyWavelets(v:0.5.2)
5. Opencv-pythoN(V:3.4.3.18)
6. Seaborn(V:0.8.1)
7. Flask
8. PyCharm
9. Sikuli
10. Deep Learning(Convolutional Neural Networks (CNNs)



***Next Step***

I am working in improving RegressVisaul tool user interface.


****Phase two****

In this phase I will build a deep learning solution for bugs detection as I mentioned in my introduction, and aslo I will integrate this solution in my **RegressVisual Tool**









