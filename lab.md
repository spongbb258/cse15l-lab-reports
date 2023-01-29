# Week 1 Lab Report

* **Part 1 - Visual Studio Code**


    Go to Visual Studio Code website [https://code.visualstudio.com/]( https://code.visualstudio.com/), then download and install VSC on your computer. There are different version for **MAC** and **WINDOWS**.
    
    After installed the VSC, you should be able to open a window that looks like this (it might have different colors, or a different menu bar, depending on your system and settings):
    
    ![15 l VSC](https://user-images.githubusercontent.com/106724998/212503008-0267b419-ff43-4541-a2f9-09c34c27b174.jpg)

    
    

* **Part 2 - Remotely Connecting**
    
    **Step 1: CSE15L Account**
    
    Look up your course account for CSE15L at this link: [htts://sdacs.ucsd.edu/~icc/index.php](https://sdacs.ucsd.edu/~icc/index.php)
    
    Then input your UCSD username and PID like the screenshot (PID should start with small ‘a’, e.g: a12345678), and click on the submit button
    
    ![15l account look up](https://user-images.githubusercontent.com/106724998/212524766-35f7156b-6c75-484e-a09c-f5cc4570e721.jpg)

    You should see your course account name at the place showed in the screenshot(it will be something like cs15lfa22zz)
    
    ![15l account](https://user-images.githubusercontent.com/106724998/212524909-d79fda9b-1b22-4bd0-9cea-b02ac50f5810.png)
    
    
    
    **Step 2: Change Account Password**
    
    Click that account name, it will navigate you to a new page. Then click on the link that is written as **change your password** to change your password
    
    Enter your current password, and your new password. Your new password should be include Upper and Lower case letters, numbers and symbols, and select no for **Change MyTrinLink password**.
    
    ![change password](https://user-images.githubusercontent.com/106724998/212525662-aba9345b-524b-4479-8620-e256c752a4d7.png)

    Then wait for 15 minutes until the password is changed.
    
    Then, to use ssh, open a terminal in VSC. (Ctrl or Command + `, or use the Terminal → New Terminal menu option). The terminal is look like this:
    
    ![terminal](https://user-images.githubusercontent.com/106724998/212527225-826df596-5e05-47cd-8bac-e444c71ba3b8.png)

    Then insert command, $ ssh cs15lwi23zz@ieng6.ucsd.edu, but replace the zz within the letters in your account. Then insert your password and you will get the result from below picture, which means you successfully connected to a computer in the CSE basement:
    
    <img width="711" alt="success" src="https://user-images.githubusercontent.com/106724998/212527356-ccb8e61b-5512-4d21-9ba9-dfe0176dc399.png">
    
    <img width="667" alt="success2" src="https://user-images.githubusercontent.com/106724998/212527358-bd02be16-0d11-4d01-81f3-8c47f91b406f.png">
    
    
    
* **Part 3 - Run Some Commands**

    Now, try to run some of the commands cd, ls, pwd, mkdir, and cp a few times on the remote computer after ssh-ing 
    
    * cd ~
    * cd
    * ls -lat
    * ls -a
    
    Here is a picture of the result from the commands I ran:
    
    <img width="1253" alt="command" src="https://user-images.githubusercontent.com/106724998/212527737-2ef3affb-b513-4e06-ae6a-a0db6558fcbb.png">
