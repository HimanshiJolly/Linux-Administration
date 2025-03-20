#
Experiment 7-8
#
Problem:

Create the /home/consultants directory. Add write permission to the consultants group. Use the symbolic method for setting the appropriate permissions.  Forbid others from accessing files in the /home/consultants directory. Use the octal method for setting the appropriate permissions. Change the default umask for the operator1 user. The new 
umask prohibits all access for users that are not in their group. Confirm that the umask is changed.

Solution:

sudo mkdir /home/consultants
![image](https://github.com/user-attachments/assets/8cf52a1a-1e34-4c5c-992d-daf7c66c5665)

sudo chmod g+w /home/consultants                                                                                                                                                
sudo chmod 770 /home/consultants
![image](https://github.com/user-attachments/assets/0c972be7-5480-4fd2-8876-2e12f5ba3e93)



