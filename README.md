# Second-Semester-exam

The project manages two servers, "Master" and "Slave," both using Ubuntu. It uses Vagrant for automation. A Bash script automates the setup of a LAMP (Linux, Apache, MySQL, PHP) stack and fetches a PHP app from GitHub with all the necessary parts. It also sets up Apache and MySQL.

To make all this work, Ansible steps in to run the Bash script on the "Slave" server. Additionally, there's a scheduled task (cron job) that checks the server's uptime every day at midnight.

The Bash script is designed to be user-friendly and can be accessed at this repository: https://github.com/TYDev01/Second-Semester-exam.git