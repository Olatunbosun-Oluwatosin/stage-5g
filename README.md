## _Ansible-Project stage-5b_

To deploy a PHP boilerplate application on your Linux server, follow these steps:

1. Clone the repository `-b devops` on your Linux server:
A git clone command s run to achieve the above objectiev. `git clone https://github.com/hngprojects/hng_boilerplate_php_laravel_web.git`

2. Install Apache and PHP

Update the package list: `sudo apt update`

Install Apache: `sudo apt install apache2`

Install PHP: `sudo apt install php libapache2-mod-php php-mysql`

All this initial process was to perform the task manually on the linux server before deploying ansible to automate the process.
The application started and run successfully using the public IP of the ec2-server, see the outcome below;

![alt text](image.png)

