# Bash-Script-2
Create a Bash script to SSH into a server

#!/bin/bash

#Have the user select ssh or scp
echo "Select '1' for ssh or '2' for scp"

read x

#If the user chooses option 1, have them enter IP address
if [ "$x" = "1" ]
then
        echo "Please enter your IP address"
        read ip_address
        echo "Please enter your username"
        read username

fi

#If the user chooses option 2, have them enter direction of copy
if [ "$x" = "2" ]
then
        echo "Please enter the direction of copy"
        read direction of copy

fi

#cd . ssh
#cat .ssh

Exit


![image](https://github.com/DomIvey/Bash-Script-2/assets/140740841/21ccc6ff-6b36-4773-976f-5fb4908d318a)
![image](https://github.com/DomIvey/Bash-Script-2/assets/140740841/89731698-d936-4424-8fbb-d8f50e6bd4e4)
![image](https://github.com/DomIvey/Bash-Script-2/assets/140740841/1e9e9936-ab77-4e4a-9987-80efa2bac299)
![image](https://github.com/DomIvey/Bash-Script-2/assets/140740841/198cad05-240d-48eb-903c-e1c7f8723eba)




