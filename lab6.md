#
Experient: {10-11}  
#
Problem:
Create the operator1 user and confirm that it exists in the system. Set the password for operator1. Create the additional operator2 and operator3 users. Set their passwords as well. Run the usermod -c command to update the comments of the operator1 user account. Remove the operator3 user from the system.  
Solution:  
1. Create operator1 user using useradd command.

   
    ![image](https://github.com/user-attachments/assets/41650e3b-d01f-4b52-a686-cd1837ea16be)


2. Verify if operator1 exists.
   
    ![image](https://github.com/user-attachments/assets/59f326c4-591c-4eb2-9f1f-6d2340b8631f)

3. Set password for operator1 using passwd command.

   ![image](https://github.com/user-attachments/assets/b151bfd7-90ee-4163-bd70-c02fcb743a7c)


4. Create operator2 and operator3 user while also setting their password.

   ![image](https://github.com/user-attachments/assets/546db8ec-a04a-4fd1-ade2-9e0d9b04fb06)


5. Add comments to operator1 user using usermod -c command.

   ![image](https://github.com/user-attachments/assets/53396e75-856d-4590-9e5a-2aae86387472)


6. Use userdel command to delete operator3 user.

   ![image](https://github.com/user-attachments/assets/6513066d-20ca-4606-a660-926cf6ea713d)
