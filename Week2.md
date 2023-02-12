# Week 2 Lab Report

* **Part 1 - Stringserver**

    ![WeChat Image_202301290109033](https://user-images.githubusercontent.com/106724998/215316619-46b6f248-336c-466e-bf58-03d6e8bc8d34.png)


    For this screenshot, I wrote a if when there is not an add involved, and it will return the string array directly. For the else part, if I inserted /add in URL with a string, then the string will be added in to the array, and be displayed.
    
    
    ![WeChat Image_20230129010903](https://user-images.githubusercontent.com/106724998/215316653-857257df-14de-403d-acd0-e382e7d8b8a6.png)
    
    For this screenshot, the method is called is handle request method. When URL detected /add with a string. Then, the index of array will change, num will increase, and string will insert into correct index.
   
    ![WeChat Image_202301290109031](https://user-images.githubusercontent.com/106724998/215316660-8eef1c36-e68e-4026-88c5-44cc5e0740d3.png)
    
    ![WeChat Image_202301290109032](https://user-images.githubusercontent.com/106724998/215316667-cd110db9-2beb-4118-868d-479f1ace51ea.png)
    
    
    For these screenshots, the method is called is handle request method. When URL detected /add with a string. Then, the index of array will change, num will increase and string will insert into correct index, and the array got updated. 
    
 * **Part 2 - Bug fixing** 
  
    * **buggy method**
    
        ![WeChat Image_20230129014015](https://user-images.githubusercontent.com/106724998/215318019-89e56084-20b7-4bd6-9a1f-b412b97028b2.png)
        
     * **A failure-inducing input** 
        
        int[] input1 = {1, 2, 3};
        assertArrayEquals(new int[]{ }, ArrayExamples.reversed(input1));
        
        
     * **An input that doesn’t induce a failure**   
     
        int[] input1 = { };
        assertArrayEquals(new int[]{ }, ArrayExamples.reversed(input1));
        
     * **The symptom**    
     
        ![WeChat Image_20230129013813](https://user-images.githubusercontent.com/106724998/215318021-fcbbf8db-3012-47ac-9825-bed2bae08e55.jpg)   
    
    * **Fixing** 
        
        * Before fixing
        
             ![WeChat Image_20230129015138](https://user-images.githubusercontent.com/106724998/215318512-fa8629dc-273a-4f72-9c62-12e80ebdd542.png)
             
        * After fixing
       
             ![WeChat Image_202301290151381](https://user-images.githubusercontent.com/106724998/215318511-96244b60-a339-4bc2-8c3a-fe5ce31db851.png)
              
* **Part 3**

   One of things I learned was about building and running the Server. Through the code provided from lab 2. I read through the code on how to use code to set up a server, and also the meaning of the methods inside the code. Throughout practicing the command on the server, I understood how to add element onto the server, and updated the server. 
