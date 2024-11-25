<p align="center">
<img src="https://imgur.com/a/XGeZj8M" alt="Linux Logo"/>
</p>

<h1> Navigating the Linux Environment</h1>
This tutorial outlines the Mastering Linux File Management: Creation, Copying, and Moving Explained.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Linux Command Line

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2> Naviating Linux

<p>

  ![STEP 1](https://github.com/user-attachments/assets/e25fec41-4059-4b57-bff9-e948c8638d44)

>
</p>
<p>
STEP 1: Create a folder called Internal_Investigation_Employee_A.

  
  - Use "mkdir" directory creation tool followed by Internal_Investigation_Employee_A

</p>
<br />

<p>
  
![STEP 2](https://github.com/user-attachments/assets/58670f49-a4af-45fd-a6c7-8485c2a0308d)

>
</p>
<p>
STEP 2: Create the following three files inside the Internal_Investigation_Employee_A folder:
  
email_evidence
log_evidence
web_evidence

Delete the file called web_evidence, as you have realized Candy has no web logs captured.

- Use "touch" file creation tool within the Internal_Investigation_Employee_A directory followed by web_evidence log_evidence email_evidence

- Use "rm" remove tool to remove web_evidence



</p>
<br />

<p>
  
![Step 1 lab2](https://github.com/user-attachments/assets/3fa0cbd8-6a8e-4c61-8b60-bb611fd0e9a0)


>
</p>
<p>
STEP 3: Create an additional folder called Internal_Investigation_Employee_B.

-  - Use "mkdir" directory creation tool followed by Internal_Investigation_Employee_B

  
</p>
<br />


![Step 3 Lab 2](https://github.com/user-attachments/assets/1982ea7c-1745-47d1-b44a-04eed2d54467)


>
</p>
<p>
STEP 4: Using absolute paths, move the file email_evidence from Internal_Investigation_Employee_A to 

Internal_Investigation_Employee_B because you have been told there won’t be email evidence for the first employee.

- Use "mv" to initiate the migration of "email_evidence over to Employee B

- mv /03-student/day1/take_5/Internal_investigate_Employee_A/email_evidence /03-student/day1/take_5/Internal_investigate_Employee_B/


</p>
<br />


![step 4 lab 2](https://github.com/user-attachments/assets/c3b70db6-3a98-426e-a920-efe64e532482)


>
</p>
<p>
STEP 5: Using absolute paths, copy the file log_evidence from Internal_Investigation_Employee_A to 

Internal_Investigation_Employee_B, as you have been told there will likely be log evidence from both employees.

- Use "cp" to initiate the migration of "email_evidence over to Employee B

- cp /03-student/day1/take_5/Internal_investigate_Employee_A/log_evidence /03-student/day1/take_5/Internal_investigate_Employee_B/


