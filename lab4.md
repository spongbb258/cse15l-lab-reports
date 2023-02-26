# Lab Report 4

* **Log into ieng6**

    Type commend, **ssh cs15lwi23ahu@ieng6.ucsd.edu** at terminal and then press **&lt;enter&gt;** to log in.
    
    
    <img width="651" alt="WeChat Image_20230225161608" src="https://user-images.githubusercontent.com/106724998/221385495-b18134ad-e882-4299-a608-3b0dfed25fdb.png">

    
* **Clone fork of the repository. from Github**
 
    Type commend, **git clone git@github.com:spongbb258/lab7.git** at terminal and then press **&lt;enter&gt;** to clone the fork of the repository.
    
    
    ![WeChat Image_20230225161608](https://user-images.githubusercontent.com/106724998/221385512-73c004e9-5f90-4e9e-bf4a-24cd157fd766.jpg)
    
* **Run the tests before fixing**

    Type commend, **cd ./lab7**, and then press **&lt;enter&gt;** to change the path. Then Insert commend, 
    ```js
    local $ javac -cp ".;lib/hamcrest-core-1.3.jar;lib/junit-4.13.2.jar" *.java
    local $ java -cp ".;lib/junit-4.13.2.jar;lib/hamcrest-core-1.3.jar" org.junit.runner.JUnitCore ListExamplesTests
    ```
    and press **&lt;enter&gt;**  to run the tests.
    
    
    <img width="980" alt="WeChat Image_202302251616081" src="https://user-images.githubusercontent.com/106724998/221385525-20033b6b-d2c4-48b2-8177-5a856ff0c828.png">
    
* **Fixing the bug**
   
   Type commend, **nano ListExamples.java**, and then press **&lt;enter&gt;** to open the file in the terminal so that I can fix it through terminal. Then find the bug, the bug is located at the last while loop, by changing the **index1** to **index2**, we have fixed the bug. Then press **&lt;control&gt;** within **&lt;x&gt;** and then press **&lt;Y&gt;** to save the change. Then **&lt;return&gt;** to exit.
   
   ![WeChat Image_202302251616081](https://user-images.githubusercontent.com/106724998/221385573-ccc5bf06-459c-4a16-9b75-8d1c6a520ec8.jpg)
    
    <img width="1227" alt="WeChat Image_202302251616082" src="https://user-images.githubusercontent.com/106724998/221385585-ad3dfe13-dbaf-4f67-9950-996f784d56a9.png">
    
    <img width="708" alt="WeChat Image_202302251616083" src="https://user-images.githubusercontent.com/106724998/221385612-75ff169c-f1ca-4ace-b8fd-3ab4d714dd78.png">

    
    ![WeChat Image_202302251616082](https://user-images.githubusercontent.com/106724998/221385602-2a87c353-fe82-4993-99d9-417f2c492365.jpg)

   
* **Run the tests again**
   
   Type commend, **javac ListExamples.java**, and then press **&lt;enter&gt;** to compile the file. Then press **&lt;up&gt;** **&lt;up&gt;** **&lt;up&gt;** **&lt;up&gt;**, to find the below commend and then press **&lt;enter&gt;**, to compile:
    ```js
    local $ javac -cp ".;lib/hamcrest-core-1.3.jar;lib/junit-4.13.2.jar" *.java
    ```
    Then press **&lt;up&gt;** **&lt;up&gt;** **&lt;up&gt;** **&lt;up&gt;** again, to find the below commend and then press **&lt;enter&gt;** to run the test:
    ```js
    local $ java -cp ".;lib/junit-4.13.2.jar;lib/hamcrest-core-1.3.jar" org.junit.runner.JUnitCore ListExamplesTests
    ```
    <img width="990" alt="WeChat Image_202302251616084" src="https://user-images.githubusercontent.com/106724998/221385651-b5c4682c-53d5-4a0a-afc6-893fc18a6d40.png">
    
* **Push the change to Github**

    Type commend, **git add .**, and then press **&lt;enter&gt;** to stage all changes in the current directory. Then Type **git commit -m "changes save"** to replace the original commit message. Then type, the commend **git push git@github.com:spongbb258/lab7.git** at terminal and then press  **&lt;enter&gt;** to push the changes back to the Github.
    
    <img width="771" alt="WeChat Image_202302251616085" src="https://user-images.githubusercontent.com/106724998/221385744-7bd26922-d88b-4df7-bac4-24dab1ca82fc.png">
    
    <img width="1051" alt="WeChat Image_202302251616086" src="https://user-images.githubusercontent.com/106724998/221385745-00d10982-d3eb-4536-8a77-5688d74e7869.png">
   
* **Summarize**
    
    Overall, the commands I used the most for this task is **git**, **javac**, **java**, and **nano**.The **git** commend is used when I cloned the fork of the repository from github and also push changes back to the github. The **javac** commend is use when I want to compile the file and the tester. The **java** commend is used when I ran the test. The **nano** commend is used to open the file in the terminal.
