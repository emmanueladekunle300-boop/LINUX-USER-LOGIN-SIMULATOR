# LINUX-USER-LOGIN-SIMULATOR
A simple Bash script that simulates a user login system by verifying a username and password. It uses variables, user input, conditional statements, comparison operators, and logical operators to authenticate users and display the appropriate response.

#!/bin/bash

echo " Welcome To Linux Login Window!"
echo "==============================="

echo -n  "Enter Your username: "
read username

echo -n  "Enter your Password: "
read password

mainUsername=emmily
mainPassword=2200

if [[ "$username" -eq "$mainUsername" && "$password" -eq "$mainPassword" ]];
then
echo "Welcome $username"
else
echo "Incorrect passwordand username"
fi
