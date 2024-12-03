# Lab--Log-Analysis-Advanced-Log-Management-Analysis-and-Reporting-Solution

## Project Description

Lab- Log Analysis is an advanced lab project designed to develop skills in configuring networked virtual environments for log collection and analysis. The primary focus is on setting up and managing a robust logging infrastructure that can capture, store, and analyze log data from multiple sources within a virtual network. Participants will set up virtual machines (VMs) with specialized roles, such as a loghost to receive and process logs, a router for traffic management, and client machines that generate log data. This lab involves configuring syslog services, installing and setting up log analysis tools like fwanalog and logwatch, and using cron jobs to automate log data collection and reporting. The final goal is to ensure logs are properly processed and accessible for analysis, enhancing the ability to monitor network activity and respond to potential security threats effectively.

## Project Objectives

- Configure VMs to establish a network with proper IPs and routing.
- Set up a loghost to collect logs from network devices and clients.
- Install and configure log analysis tools (fwanalog, logwatch) to generate reports.
- Automate log data collection and reporting using cron jobs.
- Validate log data flow and ensure security measures like firewall rules are in place.

## Screenshots and Explanations

### Logwatch Email Received (Rubric: 10/10)
*As seen in this screenshot, I have successfully configured Logwatch to send email reports. This confirms that the log analysis tool is working as intended, fulfilling the objective of receiving log summaries through email.*

![Logwatch Email Screenshot](path/to/screenshot1.png)








### fwanalog Run, Valid Reports Generated (Rubric: 10/10)
*This screenshot shows that fwanalog has run properly, generating valid reports. This step confirms that I have completed the setup and configuration needed to analyze firewall logs effectively.*

![fwanalog Screenshot](path/to/screenshot2.png)






### Webhost VM Creation, Hostname, DNS, IP, User Account (Rubric: 20/20)
*In this screenshot, I have set up the webhost VM, configured its hostname, DNS settings, IP address, and created a user account. This step demonstrates that I have successfully completed the creation and configuration of the webhost VM.*

![Webhost VM Screenshot](path/to/screenshot3.png)






### Apache2 Installed, Apache2 Logging to Syslog, Firewall Configured (Rubric: 20/20)
*This screenshot shows that Apache2 has been installed and is configured to log data to syslog. Additionally, the firewall has been properly configured to allow necessary traffic. This verifies that I have achieved the objective of setting up and securing the web server with proper logging mechanisms.*

![Apache2 Screenshot](path/to/screenshot4.png)





### Webhost Sending Logs to MySQL on Loghost (Rubric: 20/20)
*Here, I show that the webhost is successfully sending its logs to the MySQL database on the loghost. This confirms that the log transfer and storage system is functioning as expected, meeting the project goal of centralized log collection.*

![Webhost to MySQL Screenshot](path/to/screenshot5.png)


















### Loganalyzer Running Properly (Rubric: 20/20)
*This screenshot confirms that Loganalyzer is up and running as expected. The tool is correctly processing and displaying log data, demonstrating that I have met the objective of having the log analysis tool operational.*

![Loganalyzer Screenshot](path/to/screenshot6.png)




