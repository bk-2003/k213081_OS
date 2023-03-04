FIRST STEP:
RUN ALL THESE COMMANDS 
• sudo apt-get install gcc
• sudo apt-get install libncurses5-dev
• sudo apt-get install bison
• sudo apt-get install flex
• sudo apt install make
• sudo apt-get install libssl-dev
• sudo apt-get install libelf-dev
• sudo add-apt-repository "deb http://archive.ubuntu.com/ubuntu $(lsb_release -sc) main
universe"
• sudo apt-get update
• sudo apt-get upgrade
SECOND STEP:
check the current version of kernal than download a version newer than that one
![image](https://user-images.githubusercontent.com/123465638/222929043-6ebbfe76-ed98-4f1c-9d4c-82894e3881e5.png)
Here this shows that I have 4.15.0 version earlier and than I  downloaded 4.19.275 version and it is also showing my roll number as it was required so.
THIRD STEP:
I have made a folder hello in which ive made a file hello.c and wrote a c code for system call
![image](https://user-images.githubusercontent.com/123465638/222929220-10f11dfc-b2bb-4f1e-b8cd-7e4a465c682e.png)
FOURTH STEP:
Creating a Makefile for the C code
FIFTH STEP:
Adding the new code into the system table file
![image](https://user-images.githubusercontent.com/123465638/222929307-2472d519-1c93-48d9-a5ea-572f2494162b.png)
SIXTH STEP:
Adding the prototype of the new system call into the system calls header file
<img width="473" alt="syscall function name" src="https://user-images.githubusercontent.com/123465638/222929344-00c85849-a16f-4c4d-a2e9-53b4893b5636.PNG">
SEVENTH STEP:
Changing version and adding the hello folder in the kernel’s Makefile
<img width="606" alt="make file core-y hello" src="https://user-images.githubusercontent.com/123465638/222929367-493420ef-e7e2-4f20-a1e9-e09edb1e0c32.PNG">
EIGHTH STEP:
Cleaning and Compiling the kernel
![image](https://user-images.githubusercontent.com/123465638/222929689-ff54f80b-ea14-4c0a-90ed-bc5e0266b647.png)
![image](https://user-images.githubusercontent.com/123465638/222929935-09b53a41-91b6-4c3a-95ce-c2d9102659a4.png)
![image](https://user-images.githubusercontent.com/123465638/222929947-a847b292-e7b4-4321-905c-dbdc80ec6ff6.png)
NINTH STEP:
Installing modules
![image](https://user-images.githubusercontent.com/123465638/222930013-4ca97148-bece-4039-9d46-05a5ba39c8af.png)
TENTH STEP:
![image](https://user-images.githubusercontent.com/123465638/222930099-8616cd3e-2366-4d24-9b12-8f4e6053c830.png)
![image](https://user-images.githubusercontent.com/123465638/222930109-35d71077-acc8-4e03-a831-50d0d4548a99.png)
![image](https://user-images.githubusercontent.com/123465638/222930118-65b7191f-a294-4202-8d93-b419e4620fba.png)
![image](https://user-images.githubusercontent.com/123465638/222930122-b06cf360-c627-4042-9298-14d358ce661b.png)



