# Software-Security

Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

* Artemis Financial is a consulting company that assists clients in creating financial plans. They were developing a web application and wanted me to address security, specifically, they wanted me to handle checksum generation.

What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?

* I think I did a good job identifying vulnerabilities in the code and determining what areas of security they fell under. It's important to code securely because it will minimize the amount of vulnerabilities that end up in the final product. It is much easier to write secure code early on than it is to go back and squeeze it in later. Those vulnerabilities that do make it into the final product, once exploited, can be devastating to customer experience, trust, and potentially safety. It could cost an organization incredible amounts of money, and, at the very least, damage their reputation with consumers. This is why software security is so important to the overall wellbeing of a company. Every vulnerability is a disaster waiting to happen, and many of them could have been prevented had the developers taken the effort to code securely, and the organization understood how important security is.

What part of the vulnerability assessment was challenging or helpful to you?

* The most challenging part of the vulnerability assessment was analyzing the dependency report. There was just so much information to sift through and so many resources to check out that it was hard to maintain focus. I hadn't heard about some of the vulnerability types yet either, so I had to do extra research to understand what the risk actually was.

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

* I increased security by generating a self-signed certificate and checksum. These can be used to ensure the connection between client and server is secure, and that no data are tampered with as the two communicate. In the future, I would assess vulnerabilities with several methods. I'd analyze it on my own for potential vulnerabilities, run static tests on the code such as the OWASP Dependency Check to look for hidden vulnerabilities that may be hard for me to catch, and I would perform dynamic security tests on the code, either by trying to break in myself, or by using existing test tools. Once my vulnerabilities were identified, I would research viable mitigation techniques and select those that are most appropriate for my project.

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

* I ensured my code and application were functional and secure with frequent tests. I ran the dependency check multiple times to guarantee that I hadn't inadvertendlt introduced new vulnerabilities. I performed this check one last time when the application code was complete, just to be sure there were no new vulnerabilities to deal with.

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

* Some resources I found very helpful were NIST.gov and Oracle's Secure Coding Guidelines. NIST provides a lot of great information on different hash functions and encryption algorithms without being too wordy. They have a lot of other security themed articles as well that I'm interested in looking through for a more rounded understanding of software security. Oracle's Secure Coding Guidelines provide some great advice for dealing with just about every security concern in Java. Even after taking this class, I still feel like it is a little above my skill level, because I'm not familiar with a lot of the terminology the guidelines use. Still though, I want to keep the article saved so I can refer back to it as my coding knowledge increases, as does the complexity of my projects.

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

* I could show future employers my vulnerability assessment, which proves that I understand the basics of software security and its importance.
