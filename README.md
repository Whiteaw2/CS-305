# CS-305
Software Security

**Briefly summarize your client, Artemis Financial, and their software requirements.**

**Who was the client?**
  Artemis Financial is a fictitious financial institution who handles international financial products for clients. 

**What issue did they want you to address?**
  In this particular simulation, Artemis Financial had assigned our firm, Global Rain, with a security check of their existing codebase including static vulnerability scans, encryption, and architectural review, resolution, and recommnedations.
  
**What did you do very well when you found your client’s software security vulnerabilities?**
  In this simulation I did a good job of applying SHA3 family of encryption and complying with international banking considerations. I identified applicable standards and areas in the architecture of the program where vulberabilities may exist. I also gave good overall guidance based on these and the static vulnerability scan to suppress and address future issues where appropriate. 

**Why is it important to code securely?** 
My role in solving security concerns as a developer are many, all of which branch from or set the basis for secure coding practices. From the design and implementation of the solution architecture, to the libraries and frameworks used in development, to the selection and implementation of the  methods and functions used are all within my security responsibility in the organization. Not only that, but my need to ensure a continuous learning and understanding of the evolving offensive and defensive security landscape are key to successful development. Security is not just an afterthought of the development process, it is an integral part of the overall security of the organization in each step of the planning, development, and support of a solution. In this instance, an international financial firm represents a valuable, high risk target.

**What value does software security add to a company’s overall wellbeing?**
Compliance with governmental regulations, user/consumer trust (protection of consumer PII, PCI, general data, protection of consumer connection and end devices, etc.), protection of IP and trade secrets, mitigation of lawsuits in various areas, availability of services, and efficient use of resources (prevention vs. disaster recovery) are among some of the value that software security brings to a company. While the value varies from entity to entity, the truth is that the digital landscape is fraught with malicious actors and even unintentional damage through dependency vulnerabilities, all of which are mitigated partly through software security.

**What part of the vulnerability assessment was challenging or helpful to you?**
The greatest challenge in this simulation was the architectural review. To fully review a solution, you need to outline all of the existing architecture. I chose to consider the primary areas of vulnerability possible for the client and refine those based on a growing understanding of the solution architecture. Some vulnerabilities require a greater understanding of the hosting locations/scheme in production which was a challenge as this is only a simulation.

**How did you increase layers of security?**
By applying "security in depth" I looked for redundant or overlapping areas of redundancy such as encryption to protect transmitted data through NIST approved cipher schemes, and then further through certificate security with HTTPS, and even revisions to modules in the codebase to limit exposure. 

**In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?**
In future I would ideally use a number of approches including static and dynamic vulnerability scans, red teams, code reviews during development, and general architectural reviews during the earlier stages of the SDLC.

**How did you make certain the code and software application were functional and secure?**
I ran funcitonal tests to ensure that the code operated correctly through build in the IDE and in the browser through the local Apache Tomcat server. I also reviewed the modules, dependency versions, static scan report, NIST database, and attempted to alter the browser result in ways that an attacker may.

**After refactoring the code, how did you check to see whether you introduced new vulnerabilities?**
This was primarily accounted for through the Maven static dependency scan. 

**What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?**
Making use of the NIST database, the Maven dependency scan, as well as the Chrome developer tools were all helpful and will be leveraged in future to secure development projects/products I encounter.

**Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience.**
**What might you show future employers from this assignment?**
I would like to point to my writeups about encryption, regulations, and the future of cybersecurity to highlight my knowledge, follow through, and future-facing thought about the area of cybersecurity and secure development. 
