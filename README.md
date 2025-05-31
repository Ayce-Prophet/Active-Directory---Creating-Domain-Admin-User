# Active-Directory---Creating-Domain-Admin-User

## Description
This project is the task of creating organizational units for employees and admins the creating a user that will be added to the "Domain Admins" group within the domain.

## Environments and Technologies Used
- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop Connection
- Active Directory Users and Computers

## Operating Systems Used
- Windows Server 2022
- Windows 10

## Walkthrough
Open Start menu(Windows Key) and type in "Active Directory Users and Computers" and open program
![Opening Program](https://github.com/user-attachments/assets/81583530-bfb4-42b6-bfb3-b28ab54df6bf)
On the left tab right click the domain and under "New" click on "Organizational Unit"
![Creating Organizational Unit](https://github.com/user-attachments/assets/917af144-29ef-4114-826c-67b74f8a96b6)
Name the new Oragnizational Unit "_EMPLOYEES" (underscore used to make units easy to find in Directory)
![_EMPLOYEES](https://github.com/user-attachments/assets/4c099693-f281-403e-9e9c-9d2a8df2a99a) <br/>
Use the same steps above and create a second Organizational Unit called "_ADMINS"
![_ADMINS](https://github.com/user-attachments/assets/5d6e9675-3ec5-4e69-a17c-d325013246ca) <br/>
Right Click the _Admins unit just created and under "New" Click on "User"
![Create admin user](https://github.com/user-attachments/assets/ee0cc39d-90b3-429c-9f44-cc50d5aa05ef)
Type in the new users Name and logon name. In the next tab be sure to give them a password then finish
![User Name](https://github.com/user-attachments/assets/b7114b12-15ee-4470-ac38-a2b416ac1094)
![Password](https://github.com/user-attachments/assets/f0a767be-ee20-43e4-8939-84546496b4d5)
