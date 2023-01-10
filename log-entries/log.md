# 100 Days Of Code - Log

### Day 0: January 1, 2023

Happy new year! Today on TryHackMe I reviewed what I learned last week regarding the basics of threat modeling and network intrusion models.

I learned about MITRE and how it is a knowledge base that tracks Advanced Persistent Threats (APTs) and their tactics, techniques, and procedures. This helps understand how attacks occur which helps both mitigate and prevent attacks occuring in your environment.

I explored the Diamond Model and cyber kill chain as well which are other models to understand the different phases an attacker goes through to execute an attack from reconnaissance (gathering research on the target) to actions on objective.

I also did some light review on Security+, specifically on the CIA triad and ways to protect the confidentiality, integrity and availability of your data.

### Day 1: January 2, 2023

Day 1! I started off by reviewing the SDLC, the different phases that are involved in the software development process from planning the design requirements to continuous integration and continous delivery. I then refined my notes on virtualization and set up an SSL certificate on AWS. I have little to no knowledge of AWS so I'm looking forward to hosting some projects on it! I also automated the process of setting up VMs using Vagrant. I'll most likely end the night with some more studying on the Security+.

### Day 2: January 3, 2023

I reviewed alot of networking basics such as network devices, how OSI model and TCP/IP work, and how encapsulation and de-encapsulation work. I also finally learned a bit about Ethernet standards. I compiled all of my notes into a GitHub repository that I'll be actively maintaining and updating. I'll keep adding to it as I find more of my notes. Here is the link to that [repo](https://github.com/cyberbarbie/Networking-Fundamentals-For-Hackers). That's all for today! Goodnight lol

### Day 3: January 4, 2023 

I did a hands-on workshop on CrowdStrike, an endpoint security management tool that utilizes threat intelligence and AI to track APTs, automate the process of real-time response to threats and get a graphical view of your threat landscape in your organization. It was alot and I'm pretty sure I have much, much more to learn about it. 

### Day 4 January 5, 2023 

Learned how to use GoPhish which is an open source phishing framework and launched a phishing attack. Later on I created and deployed a Jekyll blog and created a CI/CD pipeline with GitHub Actions. I'm so happy. One of my biggest goals was to relaunch my website and create more content! I'm migrating my old blog posts to the new site now and will update them. Check it out [here](https://taeluralexis.com). I'm also in the process of writing a blog post on how to create a CI/CD pipeline. I have so much excitement and optimism for the new year. This was a beautiful day! 

### Day 5 January 6, 2023 

Today is a light day and I'm taking the weekend off but today I completed the intro to DevSecOps room on TryHackMe where I learned about software development models like Agile and Waterfall and their faults which led to the creation of DevOps, a philosophy that foster a culture centered on fostering relationships between different teams and automating processes. DevSecOps integrates security at every phase of the development lifecycle as opposed to viewing it as an afterthought. Common DevSecOps practices include educating teams, code analysis, and automation.  

### Day 6 January 9, 2023

What a great start to the week! I started the Jr pentester path on TryHackMe and reviewed concepts I've already learned as a front end developer such as the basic components that typically make up a web page and how HTTP works. I also spent today talking to a cool new friend at a coffeeshop about her transition into pentesting and she gave such encouraging feedback!! Then later at night I chugged through the practical ethical hacking course where I set up Kali Linux and halfway finished the Linux section. 

### Day 7 January 10, 2023

Today on TryHackMe I learned about the typical phases of a pentest (reconnaissance, enumeration, exploitation, privilege escalation, post-exploitation) which reminds me alot of the cyber kill chain! Pentests start with rules of engagement, which is a contract agreed upon by the client and pentester that specfies explicit permission, rules such as what techniques and tools are allowed and defines the scope which is what specific area of a system or application you're allowed to attack. Any attacks executed outside of the scope violates the contract and is therefore illegal.

I also learn about how to use browser dev tools to exploit and find additional inforamtion while manually reviewing a website for potential vulnerabilities. Examples include reading source code for unintentional vulnerabilities done by developers :-) such as comments containing hidden links, using the inspector tool to reveal hidden CSS content, and using the debugger to breakpoint JavaScript code. Another method is to view the external requests AJAX makes when you submit form data or click a link. AJAX is a method that processes external requests in the background without making the page refresh.

I then learned about the different ways to discover key pages on a site that may provide potential attack vectors such as Sitemap.xml which details files that are permitted to be shown in search engine results, robot.txt which is a document that displays pages that are not allowed to be shown in search results or specific search engins that are blocked as well as favicon.ico which can provide an indication of what framework was used to build your target application. There are other ways to find out that exact information such as using browser extensions like Wappalyzer or viewing the source code to see what frameworks were loaded.

There is so much I've learned as a front-end developer over the years that will definitely serve me well as I attempt to exploit web applications...legally :-) 
