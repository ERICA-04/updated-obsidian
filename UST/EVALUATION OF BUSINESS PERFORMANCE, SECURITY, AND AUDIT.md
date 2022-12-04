---
typeOfNote: class notes
subject: EVALUATION OF BUSINESS PERFORMANCE, SECURITY, AND AUDIT
coursecode: IS 26315
professor: Shirley Moraga
period: finals
semester: 1st Semester
dateCreated: [[2022-10-12]]
---
## Saturday [[2022-10-15]]
### Software Audit Method
guide to be a responsible software related aduitor 

Software audit

An audit is usually conducted for one of the following reasons:
1. A specific project milestone has been reached and an audit is initiated as planned or as required by the auditing organization’s charter.
2. External parties or customers request an audit of a specific item, at a specific date, or at a project milestone. This could be part of a contract agreement.
3. An internal organization has requested the audit, establishing a clear and specific need

**A software-related audit involves:** 
• The client, person, or organization that requests the audit; 
• The auditor or team who performs the audit; 
• The auditee whose work is being examined

**client (i.e., person or organization)** 
- is responsible for authorizing the audit and for defining the scope and identifying the requirements of the audit.
- The management of the auditing organization assumes responsibility for the audit and allocates the necessary resources to perform the audit.
- auditor(s) and the auditee agree on respective roles and responsibilities, they can improve communication, agree on findings, use the audit time more efficiently, and make the overall audit more effective.

**audit team** 
- performs the audit. The audit team is composed of one or more people. Normally, one individual is designated the lead auditor.
- summarizes the finding for every area
**lead auditor**
- responsibility to organize and direct the audit and to coordinate the preparation and issuance of the audit report
**auditee**
- work is being examine 
- part of organization


IEEE Software Reviews says, “The **lead auditor** shall be free from bias and influence that could reduce his ability to make independent, objective evaluations”. 

**The lead auditor is also responsible for:** 
• Determining the team size; 
• Briefing team members on the audit scope and areas to be audited; 
• Providing background about the organization being audited; 
• Assigning the workload of who will audit what areas; 
• Determining the audit schedule; 
• Notifying and briefing the audited organization on the scope of the audit and materials that need to be provided; 
• Ensuring that the audit team is prepared to conduct the audit; 
• Ensuring that the audit plan or procedures are performed; 
• Issuing reports in accordance with the audit plan or procedures

**The auditee is the party being audited and is responsible for:** 
• Establishing a professional, positive attitude about the audit among the members of the audited organization; 
• Participating in the audit; 
• Providing all relevant materials and resources to the audit team; 
• Understanding the concerns of the auditors and verifying their factual accuracy; 
• Providing a response to the audit report; 
• Correcting or resolving deficiencies cited by the audit team

audit 
- according to ISO 9001:2000 includes auditing for all types of standards, whether quality, environmental, software, or other. 
- Consequently, many audit methods are <mark style="background: #FFF3A3A6;">common</mark> no matter what type of system or market sector is being audited. 
- The <mark style="background: #FFF3A3A6;">differences</mark> are in some auditing techniques, objectives, and performance standards

**Types Software Audits**
• Software piracy audit;
    - not authorized distributor
    - To determine if the software on the organization’s computers is legal
• Security audit; 
    - system records
• Information systems audit; 
    - secure corporate assets and data
    - data breach
• ISO 9001:2000 software audit; 
    - quality of software
• CMMI® -DEV appraisal;
• Personal audit experiences; 
    - focus is the project itself
• Automated audits
    - not bias because you use a automated siftware to do the audit

Why is there many types?
- The reason for this diverse coverage is to introduce the reader to many types of software-related audits and what they are trying to uncover.
- This should establish a basis for the reader to understand the auditing field and how it affects software quality personnel.
![[Pasted image 20221017061252.png]]


**Software Piracy Audit**
- “Software piracy” is a favorite catch-phrase used by the Business Software Alliance (BSA) and the software companies it represents. 
- The Business Software Alliance (BSA) is interested in helping all software users ensure that they use only fully licensed software and are educated about the ethical and digital security risks associated with unlicensed software use.
- The BSA Web site wonders when was the last time you conducted an audit of your company’s computers to check for unlicensed software?
- Software & Information Industry Association’s (SIIA) Anti-Piracy Division conducts a comprehensive, industry-wide campaign to fight software and content piracy. 
- As a general rule, companies should keep all receipts from software purchases indefinitely, and they should purchase software only from authorized dealers
- The proactive campaign is premised on the notion that one must balance enforcement with education in order to be effective. 
- The Anti-Piracy Division even recommends a list of audit software to aid in this task
- The heart of compliance assurance is the auditing of the installed software aided by the use of the auditing tool provided the BSA or SIIA organization for your use.


**Security Audit**
- They are a checklist that give an indication of the kinds of steps that an organization should take in securing its computer and information systems. 
- It should always be kept in mind that security of information systems is not a static solution that can be fixed once
- Constant attention has to be paid to the issues, as the risks, the threats, and the things that have to be protected are always changing.
- Issues:
    - Backups 
        - addressed here rather than under information systems audit because a method to restore the system is an integral aspect of security, if it is breached
        - What information or data do I have that has to be backed up
        - How often should I back my information up?
        - What is an efficient and cost effective medium for backing up onto?
    - Antivirus 
        - extra safety
        - There are two important things to bear in mind: 
            - Ensure that your antivirus software has the most recent updates. 
            - Ensure that your antivirus software is configured to identify viruses by all means that they can come into your computer (e-mail, Web browsing, floppy disks, CDs, archives, and so on)
    - Firewall
        - filter incoming and outcoming traffic
        - Specific information on the configuration of whatever firewall you use should be available from the manufacturer of your particular firewall. 
        - If you have an always-on connection, you should realize that instant messaging and chat facilities offer an excellent opportunity for a hacker to gain access to your systems, and are also a route by which spam can be propagated.
    - Access Control
        - If you are not the only person who has access to a PC, it may be worth while considering implementing a log-on system. 
        - This can be achieved through specialized user authentication systems; however, simple use of the user name and password facilities in Windows products is effective. 
        - For larger networks and companies many additional considerations must be taken into account in order to maintain information security.
    ![[Pasted image 20221017061236.png]]

**Information Systems Audit**
- Ron Weber, the author of the classic book Information Systems Control and Audit, says that information systems auditing evaluates whether computer-based information systems safeguard assets, maintain data integrity, achieve organizational objectives effectively, and consume resources efficiently. 
- ![[Pasted image 20221017061419.png]]
- Auditing is a responsible task as it may involve accessing live systems, and assurances need to be made that there is minimum interference to the business. 
- The scope of the audit should be very clearly defined, and the entire audit process should be closely monitored and documented
- The information systems lead auditor must be sensitive to the following : 
    - All audits should be conducted only with prior approval of the management. 
    - Consult an advocate for all the applicable legislation—that is, if you do not want to be caught by surprise later. 
    - Ensure that one does not violate the software copyright in any form. 
    - Ask the accounts department how long they retain financial records. 
    - Ensure that there is no misuse of the information processing facilities by any person, insider as well as outsider. 
    - If you are traveling with your notebook PC where you have stored encrypted files, you may be breaking a few laws of the land
    - Ensure that the evidence is admissible in court. The quality and completeness of evidence is beyond doubt, and you are really able to nail the cyber criminal. 
    - Apart from adherence to procedural aspects of security, also ensure that periodic technical compliance checks are done. 
    - Access and use of the system audit tools should be properly controlled and these should not be available to users.

**ISO 9001:2000 Software Audit**
- ISO 9001:2000 requires that an organization conduct internal audits at planned intervals to determine compliance to the standard and effective implementation. 
- The organization must also ensure that the processes in place achieve planned results. This is accomplished through monitoring and, as applicable, measuring process performance through internal audits and measuring programs. 
- Concluding section 8.2 of ISO 9001:2000, the organization is required to monitor the characteristics of the product to verify product requirements have been met
- ![[Pasted image 20221017062911.png]]
- ![[Pasted image 20221017062919.png]]
- Notice in Table 8.6 that there appears to be extreme repetition of the requirements. But upon sufficient reflection it becomes clear that that repetition provides a checklist of adequate coverage for the various aspects of what needs to be audited
- Clearly there are multiple tools involved in a development project and this repetition helps the auditor recognize that he or she needs to find tools to manage, develop, support, protect, and control software
- **ISO 19011** is The Auditing Standard & How to Conduct Your Own Audits for ISO-related audits. the former ISO auditing standard was replaced by ISO 19011 in 2003. However, at present the 2000 Version of ISO 9001:2000 still refers to ISO 10011.
- ISO 19011 describes the controls of: 
- **Requirements of auditors:** That is, their previous qualification and experience and the training that they must undergo before conducting audits. Also, their independence and ability must be considered. 
- **Requirements of auditing:** That is, how they must be planned, conducted and recorded. Also, what proofs must be gathered during the audits and what records must be kept of the audits.
- In order to perform your own internal quality ISO 9001:2000 audits, you need a number of things
    - **First, a trained, experienced auditor is needed.** Although not essential to the requirements of ISO 9001:2000, it is strongly recommended that your Internal Quality Auditor has passed an internal auditor’s course, which should be accredited by a reputable organization, such as RABSQA or IRCA.
    - your auditor should perform a regular amount of auditing—at least 2 days or more per month—in order to ensure that the training is developed by ongoing practice.
    - **Second, a written standard against which to audit is necessary.** All auditors must have a documented standard against which the audit must be performed. In the case of ISO 9001:2000, this would be ISO 9001:2000 and your own written procedures, instructions, and Quality Manual
    - **Third, something to audit is needed.** Another common failing is for auditors to begin audits before there are sufficient records to enable a meaningful audit to take place. This does not mean that your organization must wait for 6 months before conducting audits. It may be sufficient to conduct audits after only a few weeks, provided that there are adequate records for the auditor to check the entire process

**CMMI® -DEV Appraisal**
- “An audit is not a software assessment,” says the Software Quality Assurance Subcommittee of a branch of the United States Department of Energy.
- They continue, “A software assessment appraises software processes and identifies potential areas for improvement”
- The basic difference between an assessment and an evaluation is that an assessment is an appraisal that an organization does to and for itself for the purposes of process improvement
- **Assessments** provide internal motivation for organizations to initiate or continue process improvement programs. 
- An **evaluation** is an appraisal in which an external group comes into an organization and examines its processes as input to a decision regarding future business or for monitoring current business
- ![[Pasted image 20221017065337.png]]
- **CMMI®-DEV** appraisals is from the SCAMPISM Method Definition Document, version
- **SCAMPISM** A consists of three phases and several essential processes, as shown in Table 8.8. Each phase is described in detail next
- ![[Pasted image 20221017065500.png]]
- **Phase 1:** **Plan and Prepare for Appraisal** The sponsor’s objectives for performing SCAMPISM A are determined in phase 1, process 1.1, Analyze Requirements. All other planning, preparation, execution, and reporting of results proceed from this initial activity according to the phase and processes outlined.
- Because of the significant investment and logistical planning involved, considerable iteration and refinement of planning activities should be expected in phase 1
- **Phase 2:** **Conduct Appraisal** In phase 2, the appraisal team focuses on collecting data from the appraised organization to judge the extent to which the model is implemented. Integral to this approach is the concept of coverage, which implies (a) the collection of sufficient data for each model component within the CMMI® model scope selected by the sponsor, and (b) obtaining a representative sample of ongoing processes (spanning the lifecycle phases consistent with the model scope of the appraisal).
- **Phase 3: Report Results** In phase 3, the appraisal team provides the findings and ratings to the appraisal sponsor and the organization. These artifacts become part of the appraisal record, which becomes protected data in accordance with the Appraisal Disclosure Statement. The level of protection and the plan for the disposition of appraisal materials and data is determined in phase 1 in collaboration with the sponsor.

**Project Audits (Internal CMMI® -DEV/ISO 9001:2000 Audits)**
- Project audits from an organizational perspective are those that internal SQA personnel (often I sat in for SQA as an auditor) usually perform, but if appropriate, the organization process group or other organizational entities may be audited.
- Typical project audits are carried out by the local SQA person assigned to the project, whereas this project audit from an organizational perspective reviews the SQA’s work on the project and other random processes and artifacts.
- ![[Pasted image 20221017070040.png]]

**Automated Audits**
- An automated audit eventually includes an increasing number of new forms of audit evidence, which may include alerts from continuous monitoring/audit procedures, analytic contingency tables (e.g., if “event” occurs, initiate an additional audit module), or forwardlooking data from operations.
- AuditNet Audit Program
- ![[Pasted image 20221017070629.png]]
- ![[Pasted image 20221017070646.png]]
- 

#todo/eval 
 - [x] hw before sat present daw. automate tools or software asset management tools
 

## Saturday [[2022-10-22]]
### Software Audit Method Continuation
How to Perform a Software Audit?
1. Determine the Purpose and Scope 
    - Trying to do everything at once will lead to confusion and a mass of information that will be difficult to search through or understand. When you start a software audit, you need to know what you are checking for and why.
    - The scope of the audit should only search, identify, and report on pertinent information.
    - As part of your software audit checklist, set clear guidelines for when and how fast the audit will take place.
2. Choose a Tool or Process 
    - establish which software tool you will use to fit your purpose and scope. This might take additional research into the different data collection tools you can potentially use
    - While it can be tempting to use a tool that tracks and provides broad ranges of information, it is always better to limit your results than to sift through a pile of data for the pieces you need.
3. Choose Key Data Points 
    - which data points are you going to assess? Identify the data points that are most relevant to the scope and purpose of the audit.
4. Conduct the Audit 
    - If you are using internal software to perform your audit, you can let the program run, but if you require a manual audit, it’s time to get to work auditing each device you established in the first step.
    - Stick to your established boundaries. There is a chance while gathering information that you could uncover other software needs. If you run into this situation, make a note of it so it can be addressed and researched in a later software audit.
5. Compile and Analyze Findings
- If you don’t compile and analyze your findings, the data you gain in an audit is just a set of numbers. The main goal of your analysis should be to connect the data to the initial purpose you established in step 1.


**Preparation for a Software Audit:** 
**Some pertinent questions that require responses to establish the objectives of an audit should include:** 
    • What is the audit’s scope? 
    • What should the audit achieve? 
    • Does the audit cover the entire project? Does it cover the total system or part of the system? 
    • What is the authority for the audit? 
    • What background information is needed?

**Inputs to the audit shall be listed in the audit plan and shall include the following:** 
• Purpose and scope of the audit; 
• Background information about the audited organization; 
• Software products or processes to be audited; 
• Evaluation criteria, including applicable regulations, standards, guidelines, plans, and procedures to be used for evaluation; 
• Evaluation criteria, for example, “acceptable,” “needs improvement,” “unacceptable,” “not rated”; 
• Records of previous similar audits.


**A basic flow of the preparation for an audit is:**
1. Client makes the decision to conduct an audit; 
2. Request is made to an auditing organization; 
3. Auditing organization then assigns a lead auditor; 
4. Lead auditor working with the client decides:
    • Purpose of the audit; 
    • Audit’s scope; 
    • Standards or documents to be used; 
    • Schedule and time frame for the audit; 
    • Commitment of resources necessary to meet the audit’s scope and depth

**The lead auditor provides**
• Notification with the objective and scope of the audit; 
• Preliminary schedule; 
• Request for the names of the people responsible for each task or area to be audited; 
• An audit team.

**According to ISO 19001:2002, the audit plan should contain the following:**
• Audit objective and scope; 
• Identification of the individuals having significant direct responsibilities regarding the objectives and scope; 
• Identification of reference documents (such as the applicable quality system standard and the auditee’s quality manual); 
• Identification of audit team members; 
• Language of the audit; 
• Date and place where the audit is to be conducted; 
• Identification of the organizational units to be audited;
• Expected time and duration for each major audit activity; 
• Schedule of meetings to be held with auditee management; 
• Confidentiality requirements; 
• Audit report distribution and the expected date of issue.

**Performing the Audit** 
The performance phase of an audit consists of: 
• auditors interviewing 
• reviewing records 
• observing operations, and 
• collecting information.

- These are informal sessions usually held at the end of each day. Their purpose is to share information such as facts, tentative conclusion, problems, and so on. 
- This allows everyone involved in the audit to understand where the audit is headed before the final report. During the performance phase, the **auditee gives the audit top priority**. 
- Questions should be answered promptly, accurately and honestly. The auditee can challenge the auditor if the auditor makes a dubious conclusion. 
- More evidence may be presented or requirements reviewed to substantiate the challenge. 
- If problems are discovered, the auditee should correct them immediately, if possible, and inform the auditors

**The performance phase has three main activities:** 
•Opening meeting; 
•Performance of the audit; 
•Closing meeting

**The following are the levels of review that may be performed:** 
• Level 1: Verify the existence of the work product or deliverable. Review to assure the work product or deliverable exists and is complete
• Level 2: Verify minimum content exists. Review to ensure the minimum level of information has been provided. Verify the existence of content by checking sections/headings
• Level 3: Verify content is logical and rational. Review to make judgments as to the quality and validity of the deliverable

**Results and Ramifications** 
• The lead auditor is responsible for generating the audit report that is the product of the audit. 
• Team meeting discussions and the facts collected will help guide the report. 
• At the closing meeting, the lead auditor will provide a summary of the written report. 
• The summary allows for factual corrections and explanations

**What Can Be Done After a Software Audit?**
1. Remove under - or unused software 
    - Uninstall underutilized software on specific devices. This allows you to use the license on a different device where it will be used and still be license compliant.
2. Update outdated software 
    - Uninstall underutilized software on specific devices. This allows you to use the license on a different device where it will be used and still be license compliant. 
3. Obtain new software and/or licenses based on identified needs 
    - Uninstall underutilized software on specific devices. This allows you to use the license on a different device where it will be used and still be license compliant.
4. Document steps taken after the audit 
    - Track and record all steps you take after an audit.
5. (Re)Emphasize software rules to individual employees as necessary 
    - Employees might not be aware of standards and expectations when it comes to software. It is important to train and retrain employees to ensure they are compliant with the organization’s standards. Conduct training as often as needed. This is a simple annual training in some companies, but depending on your organization’s software and needs, training may need to be held more frequently.
6. Make a plan for the next audi
    - Software audits should be continual, especially for larger organizations. Once you finish one audit, you should start planning how you will make the next one better.


## Saturday, [[2022-11-05]]
### Development Quality Assurance
The tools and techniques that have been successfully applied by software quality engineering may also be applicable to assure the fidelity of other development processes. This chapter provides an approach based on using proven software quality assurance (SQA) methodology to evaluate and assure the implementation of systems and hardware development processes. This approach can be characterized by the term development quality assurance (DQA). The DQA implementation to systems is based on experience, whereas the DQA implementation to hardware development is proposed as a workable extension. These processes have been developing over a period of 3 years and actual feedback from the development/design disciplines indicates that a real advantage can be achieved in their application. Because software quality engineering had been more accustomed to looking at, and critiquing, development processes, it followed that software quality would develop the methodology that would be applied to the other disciplines.
The challenge faced in applying these principles to hardware development quality engineering was greatly complicated by the fact that hardware design encompassed a broad spectrum of design disciplines. Indeed, in the authors’ experience, process oversight was required to address hardware development of 40 distinct processes.
**Quality Assurance** 
- is defined as the planned and systematic activities implemented in a quality system so that It provide confidence that the quality requirements for a product or service will be fulfilled.
**Developmental Quality Assurance** 
- is defined as a combination of the Quality assurance with the Research and developmental activity which incorporates and ensures that the innovation meets the predetermined quality specifications as-per regulatory norms, and that the methodology, procedure, process will consistently fulfill the quality specifications over and over again.
**Software QA Versus Traditional QA** 
- “Digital business is driving a faster pace of delivery to support the continuous delivery of incremental changes. Traditional testing cannot meet this pace nor the expanded view of quality required.”— “DevOps and Cloud Speed Are Driving the End of QA as We Know It,” Thomas Murphy, Joachim Herschmann, Gartner, 13 August 2018.
**Traditional QA isn’t working for a number of reasons:** 
• Software testing remains the number one bottleneck in the software development and delivery process. 
• Software testing consumes 30% to 40% of an organization’s application budget; 
• Traditional (siloed) development/testing structures focus on optimizing the subcomponents — distracting us from the real goal of optimizing the broader user experience

**Steps to Development a Quality Assurance Plan** 
1. Define Quality Objectives 
    • Specific 
    • Measurable 
    • Appropriate 
    • Realistic 
    • Timely 
They need to be clear, measurable, and something that can be realistically attained in a timely manner.

Quality goals also have to match what your customer is expecting. If the quality of your product is low, it ends up failing both the customer and the company. You should also make sure that you adhere to any government regulations that could apply to the project as well.
2. Roles and Responsibilities 
When you decide to move forward with a [quality plan](https://theqalead.com/topics/guide-bulletproof-quality-planning/), there are various options. Big companies may have an entire department dedicated to QA whereas small ones may have to go outside the organization or assign additional roles to current employees. Training staff is important as is giving them jobs that meet their skill set. You want a team in place that can detect and repair issues in the early part of product development. This staves off mistakes and makes sure that the company meets its end-users' expectations.
When you decide to move forward with a [quality plan](https://theqalead.com/topics/guide-bulletproof-quality-planning/), there are various options. Big companies may have an entire department dedicated to QA whereas small ones may have to go outside the organization or assign additional roles to current employees. Training staff is important as is giving them jobs that meet their skill set. You want a team in place that can detect and repair issues in the early part of product development. This staves off mistakes and makes sure that the company meets its end-users' expectations.
3. Implement the Quality Assurance Plan 
Once the plan is ready to go, it’s time to implement your new quality control procedures. Make sure all staff members have been trained and are aware of the contents of the plan. It’s also essential that your team has the tools and resources it needs to meet its targets.

The plan should be clear in how it backs the company's mission and should be simple so there is no question that everyone understands it and that each step of the process is followed. Consult with HR and production to confirm that the QA plan meets risk management and documentation guidelines as well.
4. Examine the Results 
Once the Quality Assurance plan is active, consider it a living document that can adapt and evolve as the team sees fit. While the initial goal of the QA plan should be held at the forefront, they are also used to make sure the team’s objectives are being met. If not, why and how do new policies and guidelines make this happen? Listen to the team, other employees, and customers to make sure you are meeting everyone’s realistic expectations.
5. Make Adjustments 
Once the Quality Assurance plan is active, consider it a living document that can adapt and evolve as the team sees fit. While the initial goal of the QA plan should be held at the forefront, they are also used to make sure the team’s objectives are being met. If not, why and how do new policies and guidelines make this happen? Listen to the team, other employees, and customers to make sure you are meeting everyone’s realistic expectations.
6. Keep Your Team in the Loop
Staff wants to know what they are doing is working. If the QA plan has improved the organization,  let them know. Positive or constructive feedback makes for a more solid team and lets them know they are making a positive difference for the company. That you are empowering staff to make a difference inspires them to continue to do a good job and gives strong input into the QA process.  So, have staff follow the plan, give both positive and negative feedback, and listen so adjustments can be made.

[Quality assurance](https://theqalead.com/topics/quality-engineering-vs-quality-assurance/) planning can save your company time and money. Stay up to date by [subscribing to our newsletter at the QA Lead](https://theqalead.com/about/subscribe/). It's a great way to stay in the loop with podcasts, articles, deals, reviews, guides, and more! We’re a community of QA professionals exploring the newest and best applications of quality assurance examples, automation, and testing where you can find the tips and tricks your team needs to banish the bugs and make sure they never come back.


**Systems and Software Quality Assurance: An Integrated Approach**
1. **Process Evaluations** 
- determine whether program activities have been implemented as intended and resulted in certain outputs. 
- Evaluations involve comparison of work products and processes to their requirements, ensuring appropriate corrective action for the deficiencies found, and tracking them to closure with verification of the corrective action
**The scope of the evaluation process includes the following activities:** 
• Evaluate key processes and work products for compliance with the Project Plan, Software Development Plan (SDP), Systems Engineering Management Plan (SEMP), or an overall Integrated Project Plan, contractual requirements, the tailored standard process, and any other relevant requirements imposed on a project. 
• Resolve all non compliances with project-assigned personnel when possible, but escalate to higher management when necessary. It is advisable to regularly review non compliances for status and escalate, when necessary, to attain the visibility required for closure
2. **Work Product Evaluations** 
• Work products are evaluated as they become available for delivery or use, including revisions by type and frequency as listed in the SSQA Implementation Plan. 
• Evaluations of work products may be performed using the following criteria: 
    •Templates; 
    •Customer supplied data item descriptions; 
    •Work product specification (if required); 
    •Standards; 
    •Procedures; 
    •Plans; 
    •Directives; 
    •Editorial correctness (spelling, grammar).

3. **Formulating the SSQA Implementation Plan The SSQ**
- Implementation Plan describes evaluation planning, scheduling, and tracking activities, which are to be considered for application on every systems and software development project.
4. **Keeping the SSQA Implementation Plan Current**
- When changes are made to the SEMP, SDP, or other project planning documents, appropriate changes to the SSQA Implementation Plan must also be made so that it is compatible.
5. SSQA Tools and Techniques 
- The application of tools and techniques varies from contract to contract, depending on the life-cycle requirements of the project; SSQE personnel must determine which are to be applied on a specific project.
- Tools that are often used include Microsoft Access, Excel, and Project
6. IPT Participation
- Participation in IPTs provides an opportunity for SSQEs to do their job more effectively while contributing to the project. 
- Because these SSQEs have special knowledge of quality concepts, they can monitor and ensure that a product meets quality requirements as it evolves in the IPT
#todo/eval 
- [x] activity 2 - sat before 3pm
[readings](https://www.cio.com/article/220383/devops-and-cloud-mean-the-end-of-qa-as-you-know-it.html)