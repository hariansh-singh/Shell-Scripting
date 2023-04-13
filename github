#!/bin/bash

# Welcome the user with his username!

echo -e "\n-------------------------WELCOME-------------------------"
echo -e "\nHi $(whoami) ! Welcome to the DevOps journey.\n"
echo -e "--------------------------***---------------------------"

# Show the date and time!
echo -e "Current Date and Time is: $(date)"

# Show uptime of server and the last logins!
echo -e "--------------------------***---------------------------"
echo -e "\nThe uptime of the server is: $(uptime) \n Last login details: \n$(last -a | head -3)\n"

# Show the disk space and ram utilization!
echo -e "--------------------------***---------------------------"
echo -e "Disc space available is: $(df -h | xargs | awk '{print $11"/"$9}')"
echo -e "--------------------------***---------------------------"
echo -e "\nRAM utilization: $(free |  xargs | awk '{ print $13"/"$8 }')"

# Show the top processes!
echo -e "--------------------------***---------------------------"
echo -e "\nTop CPU processes: $(top | head -10)" 


