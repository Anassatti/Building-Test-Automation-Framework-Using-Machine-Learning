# Building-Test-Automation-Framework-Using-Machine-Learning
In this repo I will build test automation framework using machine learning in the error detection and prediction. I am currently working on this project, which is innovative and uniqueness Idea. I divided this project into couple of projects, and every time I will cover specific functionality in automation, and I will try to see how I can implement ML. The first phase will be cover UI testing.
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
7.Flask
**Test Automation Project Technologies:**

1. Java Programming Language
2. Eclipse
3.Testng
4. Maven
5.Apache Log4j
6. Selenium




