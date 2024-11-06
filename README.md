# FIRMPASS
A new tool to identify broken password management of Linux-based IoT firmware.

# Details of FIRMPASS
Password management is a fundamental aspect of security for Internet of Things (IoT) devices. However, despite
the availability of established guidelines and best practices, the implementation of password management
in IoT firmware often falls short, leading to vulnerabilities and potential breaches. Because of the lack of
automated tools, the severity and pervasiveness of broken password management of IoT firmware has been
less understood.
In this paper, we present FirmPass, a new tool to identify broken password management of Linux-based IoT
firmware. Particularly, we establish general password management models for Linux-based IoT devices based
on password management processes and related vulnerabilities. To automatically identify the vulnerabilities,
FirmPass employs a query-driven approach to locate the firmware that violate the properties of correct
password management. Specifically, we manually define four rules that should be complied with, encode
the rules with queries, and check the queries in the firmware, which leads to the discovery of four types of
vulnerabilities. Evaluation of 615 IoT firmware images uncovers 67 vulnerabilities, including 37 previously
unknown issues. Our work underscores the urgent need for assessment solutions for IoT firmware.

# Data Set for Replication
We have disclosed all experimental data and code for replication.
