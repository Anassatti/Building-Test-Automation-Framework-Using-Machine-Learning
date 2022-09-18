# Building-Test-Automation-Framework-Using-Machine-Learning

**Indroduction**

For couples of years I was thinking to reduce the effort and the time spent in regression testing, which is unavoidable depiste integration of automation testing. Use automation tools in regression help a lot, but still writing a code and build a roboust test automation framework need experience person, who has a solid technical background.So, from here I came up with idea how to fully unitlize manual testers who do not have technical background and let them be part of automation effort and definitly ROI will increase. Therefore, RegressVisual tool comes to the light. This tool detect any issues in UI using deep learing and ML.

**Project phases**

1.	Planning- Done
2.	Design phase- Done
3.	Implementation: Done
I follow divide and conquer concepts, which means break the projects into sub-projects as the below:
1. Building Machine Learning Solution for image processing by trying to detect human faces. The purpose of this steps is to gain experience in ML.
2. Improve ML solution to detect the differences in UI, means comparing two images and detecting what the changes happen
3. Using my Software automation solution I built
4.Integrate ML solution with Software automation solution


**Building Machine Learning Solution for image process**

My focus is to get the advantages of machine learning(ML) in detecting UI issues. The suggested solution structure depends only on drag & drop the screens under the test; the process will be as below:

1. Compare two screens, the original screen, and the same screen 
2. ML will detect if there are any differences 
3. Generate probability percentage report and the UI name(ex.user registration form, probability score(ex.95%))
4. Generate complete testng HTML report showing more details, which help the developers fix the issue


**Below Machine Learning solution structure**


![image](https://user-images.githubusercontent.com/73906550/140051684-fc834caf-803f-45e3-8e59-6e574f17eab3.png)

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

I finished building the ML model, which detects human faces using Open CV capabilities. The solution showed the results in percentages(Probability), which means the user uploads an image of the same person. If it is the right image, the system will show, for example, 95% John, etc.., the result displayed on the simple HTML page. As we can see below, ML's accuracy in detecting the faces. For example, the ML detects superstar Muhammed Salah's face by scoring him 79.33 probability. Below is a sample of how ML detects faces.

![image](https://user-images.githubusercontent.com/73906550/145156222-21200402-d5bd-478b-9898-e6616195b867.png)

**learned lessons**
The above solution explains how ML detects human faces, but our goal is to detect UI screen elements and classify them. My target is to help test automation engineers reduce the effort of writing automation code to cover UI screens and build frameworks using a tool that works by only dragging & dropping the UI screen. The tool will detect any difference in the screens control levels and generate the same above report HTML with details. Therefore, OpenCV cannot detect UI elements, so I will use another approach that is available in object detections using deep learning YOLO. We will focus on the image classifications, which will help detect the controls in the screens.

***UI Automation***

**UI Automation Challenges**
1. Complicated Web Applications
2. UI changes
3. Choosing test automation tool
4. Error handling
5.Image comparison


**RegressVisual Tool**

As part of the overall project modules, I designed and implemented a new tool named **RegressVisual**. This tool helps detect any difference in the UI using AI, which will help Automation engineers to have a sense of whether there is any change at the UI level. The tool focuses on regression testing, which means that after any bug fixing, the tester should check if there is any impact on the application. Below the tool, which has a simple interface, the tester will drag the UI and drop, and The RegressVisaul innovative tool will do the rest.

![image](https://user-images.githubusercontent.com/73906550/148179647-55a461fa-4f6f-448c-9501-371af02fc949.png)


**Advantages**
1. No code experience is required
2. Fastest result
3. HTML Report contains summary 
4. Redue automation time
5. Accurate Result

***HTML report***

The tool generates an HTML report with the ability to share in the email as a link or attach PDFs and SMS notifications.
The report looks like below

![image](https://user-images.githubusercontent.com/73906550/190888637-9113e7b2-b4b7-472e-acd0-c1c4c827d7be.png)


![image](https://user-images.githubusercontent.com/73906550/139382494-58696789-ce51-4ba4-8dfb-c021622c715b.png)





