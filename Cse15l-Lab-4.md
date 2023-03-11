Aron Bariagabr  
## Lab 4  
The first thing I have to is Delete any existing forks of the repository you have on your account  
![1](https://user-images.githubusercontent.com/122565144/224513813-6345d65d-cd3a-466e-a4b9-acea09c32213.jpg)  
I clicked on the Settings tab and scrolled all the way down. I clicked on the button that says "Delete this Repository," followed the prompts on the screen and typed in the name of the repository. I saw a screen like this:  
![2](https://user-images.githubusercontent.com/122565144/224513832-b08ca546-2620-48d8-8184-b427dfdd4e84.jpg)  
![3](https://user-images.githubusercontent.com/122565144/224513836-102728c2-f88a-4415-ad1c-8b70c2c938f6.jpg)  
## As you see it's confermed that it's already deleted.  
![4](https://user-images.githubusercontent.com/122565144/224513840-89031bb7-e689-4b30-a71e-fd57b7859cc4.jpg)  
So fot the second step I have to Setup the Fork respository so to creat this I went to the lab7 repository which is at Lab 7 Repository. I clicked on the Fork button in the top right, and that took me to a screen that looks like this:  
![5](https://user-images.githubusercontent.com/122565144/224514157-6eb4a2c0-1075-4957-a994-4cf38c514220.jpg)  
## The next step is Log into ieng6  
In order to log into ieng6, I opened my terminal and typed: ssh cs15lwi23apg@ieng6.ucsd.edu and <enter>. After running this command, my terminal looked like this:
![6](https://user-images.githubusercontent.com/122565144/224514291-91b2a982-f129-497f-97de-942097a22c0c.jpg)  
  The Next step is I have to clone the fork of the repository from my Github account  
  to do this I cloned the repository I forked into my ieng6 account. I went back to the GitHub page of my fork and clicked on the green code button. I selected the "SSH" tab and copied the url to my clipboard. I went back to my terminal, and typed the command git clone <ctrl> v <enter>. My terminal looked like this:  
  ![7](https://user-images.githubusercontent.com/122565144/224514440-493eaab1-5f13-4948-83b6-ab762ee3b143.jpg)  
  ![8](https://user-images.githubusercontent.com/122565144/224514565-bcc40ff7-bd7e-4b81-93b3-70fe6d510934.jpg)  
  So the next step is to Run the test, demonstrating that they now succeed  
  To do that I cloned the repository onto my ieng6 account, I changed my working directory into that repository. I typed cd lab7 <enter>. From the course website, I copy and pasted the following command into my terminal: javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java and then <enter>. Then, I copy and pasted the next command from the course website into my terminal: java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore, I then typed ListExamplesTests <enter>. These two commands compiled the java files and ran the unit tests in the tester file. My terminal displayed this pictuce as you see below:   ![9](https://user-images.githubusercontent.com/122565144/224515127-7e652e18-09b8-42eb-994d-c916438f4b53.jpg)

  

  


  










