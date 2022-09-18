# Building-Test-Automation-Framework-Using-Machine-Learning

**Indroduction**

For couples of years I was thinking to reduce the effort and the time spent in regression testing, which is unavoidable depiste integration of automation testing. Use automation tools in regression help a lot, but still writing a code and build a roboust test automation framework need experience person, who has a solid technical background.So, from here I came up with idea how to fully unitlize manual testers who do not have technical background and let them be part of automation effort and definitly ROI will increase. Therefore, RegressVisual tool comes to the light. This tool detect any issues in UI using deep learing and ML.

**Project phases**

1.	Planning- Done
2.	Design phase- Done
3.	Implementation: Done
I follow divide and conquer concepts, which means break the projects into sub-projects as the below:

  **1. Building Machine Learning Solution for image processing by trying to detect human faces** 
    **The purpose of this steps is to gain experience in ML**

I finished building the ML model, which detects human faces using Open CV capabilities. The solution showed the results in percentages(Probability), which means the user uploads an image of the same person. If it is the right image, the system will show, for example, 95% John, etc.., the result displayed on the simple HTML page. As we can see below, ML's accuracy in detecting the faces. For example, the ML detects superstar Muhammed Salah's face by scoring him 79.33 probability. Below is a sample of how ML detects faces. Below the results 

![image](https://user-images.githubusercontent.com/73906550/145156222-21200402-d5bd-478b-9898-e6616195b867.png)

**2. Improve ML solution to detect the differences in UI, means comparing two images and detecting what the changes happen**

 1. Integrate ML solution component in the SAS, below structure(Designed by Me as part if this project effort) show that:
 
 ![image](https://user-images.githubusercontent.com/73906550/139382494-58696789-ce51-4ba4-8dfb-c021622c715b.png)


**RegressVisual Tool**

As I mentioned ealier this tool help in regression testing automation effort by allow manual or automation testers to visually detect any differences in UI. Below are the challenges any software test automation engineer face in the UI automation.

**UI Automation Challenges**
1. Complicated Web Applications
2. UI changes
3. Choosing test automation tool
4. Error handling
5.Image comparison


**Tool Architecture**

![image](https://user-images.githubusercontent.com/73906550/140051684-fc834caf-803f-45e3-8e59-6e574f17eab3.png)


**Tool Advantages& Features**
1. No code experience is required
2. Fastest result
3. HTML Report contains summary 
4. Redue automation time
5. Accurate Result


**How the tools works**

1. Compare two screens, the original screen, and the same screen  through Drag& Drop
2. ML&DL will detect if there are any differences 
3. Generate probability percentage report and the UI name(ex.user registration form, probability score(ex.95%))
4. Generate complete testng HTML report showing more details, which help the developers fix the issue


***HTML report Generated***

The tool generates an HTML report with the ability to share in the email as a link or attach PDFs and SMS notifications.
The report looks like below

![image](https://user-images.githubusercontent.com/73906550/190888637-9113e7b2-b4b7-472e-acd0-c1c4c827d7be.png)



**Machine learning Project Technologies:**

1. Python Programming Language
2. Jupyter notebook
3. Anaconda
4. PyWavelets(v:0.5.2)
5. Opencv-pythoN(V:3.4.3.18)
6. Seaborn(V:0.8.1)
7. Flask
8. PyCharm
9. Sikuli
10. Deep Learning



![image](https://user-images.githubusercontent.com/73906550/148179647-55a461fa-4f6f-448c-9501-371af02fc949.png)












