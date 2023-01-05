100DaysOfCyberSecurity

Day 1 (01.01.23): Happy new year! Today on TryHackMe I continued on the SOC analyst path and reviewed what I learned last week regarding the basics of threat modeling and network intrusion models.

I learned about MITRE and how it is a knowledge base that tracks Advanced Persistent Threats (APTs) and their tactics, techniques, and procedures. This helps understand how attacks occur which helps both mitigate and prevent attacks occuring in your environment.

I explored the Diamond Model and cyber kill chain as well which are other models to understand the different phases an attacker goes through to execute an attack from reconnaissance (gathering research on the target) to actions on objective.

I also did some light review on Security+, specifically on the CIA triad and ways to protect the confidentiality, integrity and availability of your data.

Day 2 (01.02.23): Day 2! I started off by reviewing the SDLC, the different phases that are involved in the software development process from planning the design requirements to continuous integration and continous delivery. I then refined my notes on virtualization and set up an SSL certificate on AWS for my personal site, taeluralexis.com. I have little to no knowledge of AWS so I'm looking forward to hosting some projects on it! I also automated the process of setting up VMs using Vagrant. I'll most likely end the night with some more studying on the Security+.

Day 3 (01.03.23): Day 3...I reviewed alot of networking basics such as network devices, how OSI model and TCP/IP work, and how encapsulation and de-encapsulation work. I also finally learned a bit about Ethernet standards. I compiled all of my notes into a GitHub repository that I'll be actively maintaining and updating. I'll keep adding to it as I find more of my notes. That's all for today! Goodnight lol

Day 4 (01.04.23): I did a hands-on workshop on CrowdStrike, an endpoint security management tool that utilizes threat intelligence and AI to track APTs, automate the process of real-time response to threats and get a graphical view of your threat landscape in your organization.

Day 5 (01.05.23): Learned how to use GoPhish which is an open source phishing framework and launched a phishing attack. Here are the steps:

1. Create a sending profile containing the connection details required to send your phishing emails (ie SMTP server you have access to; contains server name, email address and host)

2. Set up a landing page spoofing a legitimate site - copy and paste the HTML by navigating to the landing pages link -> create new page -> press Source to enter HTML code _> click source again to view 

3. Create an email template that displays the design and contain of the email you're sending to and contain a link to the spoofed landing page to capture the victim's password and username; ie New Message Received for subject; set a legitimate link text but set to {{.URL}} which will get sent to the spoofed domain 

4. Store the email addresses of intended targets via Users & Groups

5. Navigate to Campaigns to set up a new campaign (ie Name: Campaign one Email template: Email 1 Landing page: ACME Login URL: http://10.10.37.179 , sending profile: Local Server, Groups: Targets and then launch campaign
