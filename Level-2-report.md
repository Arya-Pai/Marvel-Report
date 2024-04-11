

### ***Task 1-*** JavaScript:
---
***What is JS?***  

Javascript is a programming language for web users to convert static web pages to dynamic web pages.It is an event-based latform independent,an interpreted language with all procedural programming capabalitites.
Ex: JS is used to perform a task when you click on a button like submit, JS is involved in it.  
So in this task we had to make a marks calculator,where it calculates percentage of students and gives the ranking for each student.

**Github Repo Link:** https://github.com/Arya-Pai/marks_calculator

![Screenshot 2024-03-31 at 21 56 00](https://github.com/Arya-Pai/Marvel-Report/assets/123173952/ae306f28-566b-4656-922e-aedea236b566)


---  
### ***Task 2-*** Async JS:  


***What is Async JS?***  

It is  programming technique in JS that is used to manage operations which would unpredictable amount of time to complete.

There are several way to use Async JS like using *Callbacks*, *Promises*,*Async/Await*

In this task we create a recipe page which on click would callback a function using Async JS

**Link**:https://arya-pai.github.io/Async-Practice/

![Screenshot 2024-03-31 at 22 22 43](https://github.com/Arya-Pai/Marvel-Report/assets/123173952/1846d12a-a8de-48ea-a705-f390adc65d7d)


---
---  
### ***Task 3-*** Promises:
---

Promises is a way to use Async JS.Promises provide a cleaner and more structured way to work with asynchronous code. A promise represents the eventual completion or failure of an asynchronous operation, allowing you to chain operations using .then() and handle errors using .catch().

The same above recipe program is used to do this task. It gives the same output with the code being more readable.


![Screenshot 2024-03-31 at 22 22 02](https://github.com/Arya-Pai/Marvel-Report/assets/123173952/a616d91b-fed8-4da4-81df-418a88380d66)

---
### ***Task 4-*** Get familiar with command line and do the following subtasks:  
---
1. Create a folder named test.
2. cd into that folder.  
3. Create a blank file without using any text editor.  
4. list the files in that folder.
5. Create 2600 folders in this folder where each folder is named like M90 or B56.  
6. Concatenate two text files containing any random text and display them on the terminal.  
    

 In this task we had to the above mentioned subtasks.So I used Linux-based system (MacOS) to complete this task.I had performed this task earlier in Ubuntu which was also Linux-based so it was very similar with a bit differences in the commands. 

 *The terminal commands used is given below:*  

  
![task4_1](https://github.com/Arya-Pai/Marvel-Report/assets/123173952/a0058cb3-f7a6-44da-a45a-d3837c52759d) 


![task4_2](https://github.com/Arya-Pai/Marvel-Report/assets/123173952/a4d76320-2fcf-4300-8852-078e43bdebb6) 

---

### ***Task 5-*** VI 
---
VI or VIsual Editor is the default editor which we get with the LINUX OS.

*What is the use of VI:*  
- It can be used to edit an existing file or create a new file without any text editor or IDEs that is we can write the code or text directly from the terminal.
- It can also be used to read a file.  

It has 3 modes namely:  

1. VI Insert Mode  
2. VI Command Mode    
3. VI Escape Mode  

In this task we learnt the basics of VI and had to create a markdown file in VI illustrating the various features of VI.

![task5_1](https://github.com/Arya-Pai/Marvel-Report/assets/123173952/c8a30b10-6d00-4418-9851-e29d26267b50) 

![task5_2](https://github.com/Arya-Pai/Marvel-Report/assets/123173952/ac8df10d-37b4-4d3d-9d7d-b59699ad7bc2)  


---

### ***Task 6-*** LINUX CONTINUED  
---
This task tells us about regex and piping in Linux. 

*What is RegEx ?*
Regular Expression also known as RegEx are powerful tools used for pattern matching and text manipulation in Linux. These allows users to define patterns that can match specific patterns in  a larger strings of text.  

*What is Piping ?* 

It is an essential command line tool which connects the output of one command directly into input of another.  


**What did we do in this Task?** 

In this task we had to extract the login logs and using grep command we had to filter to get the login log for particular time period and then pipe it into an text file and the zip it .

  
The code used is given below:


```
last | grep 'Mar 25' > login_times.txt

mkdir logs
mv login_times.txt logs/
tar -czvf logs.tar.gz logs/
```
![task6_1](https://github.com/Arya-Pai/Marvel-Report/assets/123173952/ec0c16e0-46a8-49b5-968c-7172a87ae046)

![task6_2](https://github.com/Arya-Pai/Marvel-Report/assets/123173952/c9ed77d5-9b26-4713-8702-357b370a3630)

---

### ***Task 7-*** Introduction to Cloud Computing  
---
*What is Cloud Computing?*

The accessing and storing of data in servers over the internet is called cloud computing.

It is categorized into three service models:

1. **Infrastructure as a Service (IaaS)**: Provides virtualized computing resources over the internet. Users can rent virtual machines, storage, and networking infrastructure on a pay-as-you-go basis.

2. **Platform as a Service (PaaS)**: Offers a platform allowing customers to develop, run, and manage applications without worrying about infrastructure management. This includes tools, middleware, and development environments.

3. **Software as a Service (SaaS)**: Delivers software applications over the internet on a subscription basis. Users can access these applications through web browsers without needing to install or maintain software locally.

![Screenshot 2024-03-31 at 18 46 10](https://github.com/Arya-Pai/Marvel-Report/assets/123173952/0f3a6355-07f6-4a26-853b-08633f2e8bf3)


The major cloud ervice providers being AWS, Microsoft Azure and Google Cloud Platform 

***What did we do in this task?***

In this task we learnt about cloud computing and had to set up local file sharing solution where we had to share files between devices, access shared shared files from the other device.

These were the following steps I followed:


- Go to System Preferences -> Sharing.
- Check the box next to "File Sharing".
- Click on the + button in Shared file list 
- Then we have to select the folder we want to share.
- Click "Add" and adjust the permissions
- Click on the "Options" button and heck the box ext to Share files and folders using SMB"
- Set the permissions (Read Only or Read & Write) for each user or group.
- In your Windows go to Settings->Network settings and enable Turn on Network Discovery.
- Then in file explorer if you go to Networks your Mac would appear there.

![Screenshot 2024-03-31 at 19 46 10](https://github.com/Arya-Pai/Marvel-Report/assets/123173952/b41d7817-224f-4630-a2b7-2193e8b75706) 

Reference video:

[![alt text](https://github.com/Arya-Pai/Marvel-Report/assets/123173952/a24d8245-8ebe-4736-82db-4ed198e71842)](https://youtu.be/1X34O3QRgpE?si=wwA-2zR7SMKH6Pa9)


---
### ***Task 8-*** Introduction to Cybersecurity 
---

**What is CyberSecurity?**

Cybersecurity is protecting the computer systems,data,networks from unauthorized access.

**What is CIA?**

CIA stands for:
1. *Confidentiality:* This principle ensures that information is accessble only to authorized people only.
2. *Integrity:* It refers to trustworthiness and accuracy of data and resources.
3. *Availability:* It ensures that information and resources are accessible to authorized people whenever needed without any hinderance.  

What is Cryptography?

Cryptography is a method of keeping information in the form of secret code that is difficult to decipher.

So the following text is used as example: "Cybersecurity in Marvel" 

1. ***Morse code***: `-.-. -.-- -... . .-. ... . -.-. ..- .-. .. - -.-- / .. -. / -- .- .-. ...- . .-..`

2. ***Caeser cipher (Shift 10 )***: `milobcomebsdi sx wkbfov`

3. ***Pigpen Cipher***:

 ![Screenshot 2024-03-31 at 20 42 56](https://github.com/Arya-Pai/Marvel-Report/assets/123173952/eaed976c-3d77-45fb-966e-de510c5551d0)

4. ***Rail fence cipher***:`Cruy vyescrt nMrebeiial`

5. ***Polybius Cipher***: `135412154243151345422444542433321142511531`
6. ***Playfair Cipher***: `DXCASTADQSOYD OO NBQZANV`




---
## THANK YOU  🔥
---
---