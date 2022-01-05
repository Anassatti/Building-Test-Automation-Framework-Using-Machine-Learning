# Building-Test-Automation-Framework-Using-Machine-Learning
In this on going repo I will build test automation framework using machine learning in the error detection and prediction. I am currently working on this project, which is innovative and uniqueness Idea. I divided this project into couple of projects, and every time I will cover specific functionality in automation, and I will try to see how I can implement ML. The first phase will be cover UI testing.
Proof of concept of building automation framework will look like below:
![image](https://user-images.githubusercontent.com/73906550/139382494-58696789-ce51-4ba4-8dfb-c021622c715b.png)

**Project phases**
1.	Planning- Done
2.	Design phase- Done
3.	Implementation:
I follow divide and conquer concepts, which means break the projects into sub-projects as the below:
1. Building Machine Learning Solution for image process
2. Improve ML solution to detect the differences in UI, means comparing two images and detecting what the changes happen
3. Building Test Automation framework
4.Integrate ML solution and the Automation framework


**Building Machine Learning Solution for image process**

My focus here is to get the advantages of machine learning(ML) in detecting UI issues. Suggested solution structure depends only drag & drop the screens under the test, the process will be as below:

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

I finished the building ML model, which detects human faces by using Open CV capabilities. The solution showed the results in terms of percentages(Probability), which means if the user uploads image of the same person and if it is the right image the system will show, for example, 95% John, etc.., the result displayed in the simple HTML page. Below sample of how ML detect faces. As we can see below the accuracy ML offer in detecting the faces, for example the ML knows face of Muhammed Salah by socring him 79.33 propability.

![image](https://user-images.githubusercontent.com/73906550/145156222-21200402-d5bd-478b-9898-e6616195b867.png)

**learned lessons**
The above solution explains how ML works in detecting human faces, but our goal is to detect UI screen elements and classify them. We will use the same concept in detecting faces. Therefore, in the regression test the QA engineer write automation code to cover UI screens, so instead of spending time in building a framework that contains many classes, just by dragging & dropping the tool will be able to know if there is any difference happened on the screens and generate the same above report HTML with details. Open CV cannot provide this elements detecting, so we will use object detections using deep learning YOLO, we will focused on the image classifications, which will help out in detect the controls in the screens.

***UI Automation***

**RegressVisual Tool**

As part of this project, we started with UI automation, we design, and implement a new tool called **RegressVisual**  this tool detect any difference in the UI using AI, which will alow Automation engineers to have a sense if there is any change at the UI level. The tool focus on the regression testing, which as a concept mean after any bug fixin, the tester should check is the bug fixed, and see if there is any impact on the application. Below the tool, which has simple functionality only drag and drop the screen the RegressVisaul smart tool will do the rest.
![image](https://user-images.githubusercontent.com/73906550/148179647-55a461fa-4f6f-448c-9501-371af02fc949.png)


**Advantages**
1. No code experience is required
2. Fastest result
3. HTML Report contains summary 
4. Redue automation time
5.Accurate Result
6. High accuracy.

**Test Automation Project Technologies:**

1. Java Programming Language
2. Eclipse IDE
3. Testng
4. Maven
5. Apache Log4j
6. Selenium
7. Python





