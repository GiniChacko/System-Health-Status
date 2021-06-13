# System-Health-Status
## ➢ ABSTRACT :
The project aims for checking the Linux system health with a shell script. This is a short, lightweight script that gets the necessary information and status like hostname, kernel version, CPU, Uptime, memory/ disk usage using native Linux utilities and doesn't take up much room. The Script uses hostname, uname, arch, uptime, cat, mpstat, ps, df, free, head commands to get system information and cut, grep, awk and sed for text processing. The output of the script is a text file that will be generated in the current directory. A variable is set to provide an email address to which the script can send the report file. Apart from system status, the script will check a predefined threshold for CPU load and filesystem size.

## ➢ IDEA :
Regular System Health Check is essential in ensuring uninterrupted performance of your systems, and protecting valuable data. With better monitoring, you can begin to run better application health checks. It’s important to spend time reviewing the importance of individual services and how often health checks should run through the system and report back. Automation in the application health monitoring and health checks process can create more efficient teams and surface more information faster.

## ➢ DETAILS OF THE SCRIPT :

Name Of The Script → system_health_status.sh

Build To Run On → Ubuntu20/18/16 x86/x86_64 architecture

Who Can Run This Script → Root User Or sudo user

Depends On → "sysstat" package & Other Native Commands

Output → This Script would dump the details on the console and also generate a txt file of the report generated and the report would be mailed to email address entered, if the user wants the report via email.

## ➢ FOLLOWING CHECKS WOULD BE PERFORMED:

→ Mounted File Systems

→ Read-only File System If Any

→ File Systems Disk Usage

→ I-node Usage

→ Zombie Processes If Found

→ RAM Utilization

→ SWAP Utilization

→ Processor Utilization

→ Current Load Average

→ Most recent reboot and shutdown stamps

→ Top 5 memory & CPU consuming resources
