[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/-ucQIGTc)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15245537&assignment_repo_type=AssignmentRepo)

# SE-Assignment-2

Assignment: Introduction to Software Engineering
Instructions:
Answer the following questions based on your understanding of software engineering concepts. Provide detailed explanations and examples where appropriate.

Questions:
Define Software Engineering:
Software Engineering is defined as the application of a systematic, disciplined computable approach of designing, developing, testing and maintaining software applications and systems to solve real-world problems by adhering to a set of engineering principles and practices.

What is software engineering, and how does it differ from traditional programming?
Software engineering is the practical application of scientific knowledge to the creative design and building of computer programs. It also includes associated documentation needed for developing, operating, and maintaining them.
Software engineering broadly focuses on on the software with the usage of complex computer science and engineering to build the structure of the software; whilst traditional programming solely focus on the technical coding/writing of the software itself.

Software Development Life Cycle (SDLC):

Explain the various phases of the Software Development Life Cycle. Provide a brief description of each phase.

1. Planning & Analysis
   The first phase of the SDLC is the project planning stage where you are gathering business requirements from your client or stakeholders. This phase is when you evaluate the feasibility of creating the product, revenue potential, the cost of production, the needs of the end-users, etc.
2. Define Requirements
   This phase is critical for converting the information gathered during the planning and analysis phase into clear requirements for the development team. This process guides the development of several important documents: a software requirement specification (SRS) or product specification, a Use Case document, and a Requirement Traceability Matrix document.
3. Design
   The design phase is where you put pen to paper—so to speak. The original plan and vision are elaborated into a software design document (SDD) that includes the system design, programming language, templates, platform to use, and application security measures. This is also where you can flowchart how the software responds to user actions.
4. Development
   The actual development phase is where the development team members divide the project into software modules and turn the software requirement into code that makes the product.
5. Testing
   Before getting the software product out the door to the production environment, it’s important to have your quality assurance team perform validation testing to make sure it is functioning properly and does what it’s meant to do. The testing process can also help hash out any major user experience issues and security issues.
   The types of testing to do in this phase:

Performance testing: Assesses the software's speed and scalability under different conditions
Functional testing: Verifies that the software meets the requirements
Security testing: Identifies potential vulnerabilities and weaknesses
Unit-testing: Tests individual units or components of the software
Usability testing: Evaluates the software's user interface and overall user experience
Acceptance testing: Also termed end-user testing, beta testing, application testing, or field testing, this is the final testing stage to test if the software product delivers on what it promises 6. Deployment
During the deployment phase, your final product is delivered to your intended user. You can automate this process and schedule your deployment depending on the type. For example, if you are only deploying a feature update, you can do so with a small number of users (canary release). 7. Maintenance
The maintenance phase is the final stage of the SDLC if you’re following the waterfall structure of the software development process. The main goal of maintenance is to monitor the application on a continuous basis to identify issues that arise once it is in production. For example, if a certain type of request triggers an error, development teams should note that so they can fix the issue.

Agile vs. Waterfall Models:

Compare and contrast the Agile and Waterfall models of software development. What are the key differences, and in what scenarios might each be preferred?
Waterfall Model
The waterfall model is a famous and good version of SDLC(System Development Life Cycle) for software engineering. The waterfall model is a linear and sequential model, which means that a development phase cannot begin until the previous phase is completed. We cannot overlap phases in the waterfall model.
WHEN IS IT PREFFERED?
On projects that don't have complicated requirements, projects that replicable and proven, and where clients aren't likely to come up with last-minute requirements
Agile Model
Agile model is a combination of iterative and incremental models, that is, it is made up of iterative and incremental models.
In Agile model, the focus is given to process adaptability and customer satisfaction.
WHEN IS IT PREFFERED?
Suited for ongoing projects and projects where certain details aren’t known from the outset. That means if a project doesn’t have clear constraints, timelines, or available resources, it’s a good candidate for an Agile approach.
Key Differences:
Agile
It is a continuous iteration life cycle model to develop and test a software product, continuous client interaction and feedback.
Waterfall
It is a linear sequential model to develop and test a software product, there is very little client involvement and very little feedback is taken.

Requirements Engineering:

What is requirements engineering? Describe the process and its importance in the software development lifecycle.
Requirements Engineering (RE) is a systematic process used in engineering projects to define, document, and maintain requirements.
In Software Development, it’s a crucial first step involving the detailed gathering of both functional and non-functional requirements from various stakeholders. These stakeholders might include customers, end users, business managers, and technical teams, who all provide critical inputs to make sure the software is feasible, relevant, and technically sound.
THE PROCESS OF REQUIREMENTS ENGINEERING:

1. Feasibility study
   This initial phase assesses whether the project should proceed. The feasibility study examines the proposed system's technical, economic, legal, operational, and schedule feasibility. It helps the stakeholders understand the project's practical aspects, including potential benefits and limitations.
2. Requirement elicitation and analysis
   In requirement elicitation, the Requirements Engineering Practitioner gathers detailed information about what the stakeholders need from the proposed system using techniques like interviews, focus groups, workshops, shadowing, surveys, and prototype testing.  
   Once gathered, the requirements undergo thorough analysis to ensure they are clear, actionable, achievable, and verifiable
3. Software Requirement Specification
   The Software Requirement Specification (SRS) document is a comprehensive description of the behaviour of the system to be developed. It includes detailed descriptions of the system's functions, capabilities, interfaces, and interactions with users.
4. Software Requirement Validation
   This phase checks the SRS for errors and ensures that it accurately reflects the client's requirements. Validation techniques include requirement reviews, prototype testing, and model validation.

Software Design Principles:

Explain the concept of modularity in software design. How does it improve maintainability and scalability of software systems?
Modularity refers to an organizing structure in which different components of a software system are divided into separate functional units. The software is divided into various components that work together to form a single functioning item but sometimes they can perform as a complete function if not connected with one another. It measures the degree to which these components are made up than can be combined. Some of the projects or software designs are very complex that it’s not easy to understand its working and functioning. In such cases, modularity is a key weapon that helps in reducing the complexity of such software or projects. The basic principle of Modularity is that “Systems should be built from cohesive, loosely coupled components (modules)” which means s system should be made up of different components that are united and work together in an efficient way and such components have a well-defined function.

Updates and bug fixes can be applied to individual modules without affecting the entire system, this minimizes the risk of introducing new bugs and makes it easier to troubleshoot and test the changes.
By dividing a complex system into smaller modules, developers can create a more logical and structured codebase.
This not only makes it easier for them to understand and navigate the code but also simplifies collaboration between team members, as each person can work on a specific module without causing conflicts with others.

Testing in Software Engineering:

Describe the different levels of software testing (unit testing, integration testing, system testing, acceptance testing). Why is testing crucial in software development?

1. Unit testing
   Unit testing is a software testing process for testing specific units, components, or software elements. This is the most basic type of testing, and the goal for this level of testing is to validate that each unit of code performs how it should and is free of bugs, errors, and glitches.
   this level is done during the development (or coding) phase by software developers who isolate a section of code and verify that it’s correct. It’s considered a WhiteBox testing method, meaning the code can be viewed but usually not altered, and should always take place early in development to save money, time, and effort in the long run.
2. Integration testing
   when different software components and modules are combined and tested as a group to make sure everything is ready for the next level. Since a standard software project will likely consist of various modules, coded by multiple programmers, the goal is to test to expose potential defects or bugs between the various modules. Sometimes, this phase is referred to as I & T (integration and testing), thread testing, or string testing.
   It focuses on checking the data flow from one module to the next and is performed by testers. It’s another crucial level of testing because it verifies everything is working as one singular unit.
3. System testing
   It checks for a system’s compliance in accordance with the necessary given requirements. System testing inspects components like performance, load, reliability, and security with the goal of evaluating the end-to-end system specifications.
   Typically, this method is done by a professional testing agent on the completed software product before it can be introduced to the market with real users. This step is important because the project is so close to being complete, so it should be tested in an environment similar to what the user will experience once it’s finished.
4. Acceptance testing
   it’s conducted by the user or customer since the goal is to find out if the requirements have been met on delivery of the final product. Since acceptance testing is the final phase, it needs to validate the end-to-end business flow and check for things like cosmetic errors, spelling mistakes, and usability. Its conducted to ensure that the requirements of the users are fulfilled before its delivery and that the software works correctly in the user’s working environment.

Testing is crucial to identify errors so that errors can be removed to obtain a product with greater quality. To assure and maintain the quality of software and to represent the ultimate review of specification, design, and coding, Software testing is required.
Software testing ensures reliability, high performance, and security, saving time and money and ensuring the customer satisfaction.

Version Control Systems:

What are version control systems, and why are they important in software development? Give examples of popular version control systems and their features.
Version control systems are a category of software tools that helps in recording changes made to files by keeping a track of modifications done in the code.

A version control system is a kind of software that helps the developer team to efficiently communicate and manage(track) all the changes that have been made to the source code along with the information like who made and what changes have been made. A separate branch is created for every contributor who made the changes and the changes aren’t merged into the original source code unless all are analyzed as soon as the changes are green signaled they merged to the main source code. It not only keeps source code organized but also improves productivity by making the development process smooth. Version control system keeps track on changes made on a particular software and take a snapshot of every modification.

1. Local Version Control Systems: It is one of the simplest forms and has a database that kept all the changes to files under revision control. RCS is one of the most common VCS tools. It keeps patch sets (differences between files) in a special format on disk. By adding up all the patches it can then re-create what any file looked like at any point in time.
2. Centralized Version Control Systems: Centralized version control systems contain just one repository globally and every user need to commit for reflecting one’s changes in the repository. It is possible for others to see your changes by updating.
   Two things are required to make your changes visible to others which are:

You commit
They update 3. Distributed Version Control Systems: Distributed version control systems contain multiple repositories. Each user has their own repository and working copy. Just committing your changes will not give others access to your changes. This is because commit will reflect those changes in your local repository and you need to push them in order to make them visible on the central repository. Similarly, When you update, you do not get others’ changes unless you have first pulled those changes into your repository.
To make your changes visible to others, 4 things are required:

You commit
You push
They pull
They update
The most popular distributed version control systems are Git, and Mercurial.

Software Project Management:

Discuss the role of a software project manager. What are some key responsibilities and challenges faced in managing software projects?

The role of a software project manager is to take the overall responsibilities to manage the software projects and play an important role in the successful completion of the projects. And also amongst others, write the project proposal, project cost estimation, scheduling, project staffing, software process tailoring, project monitoring and control, software configuration management, risk management, managerial report writing, and presentation, and interfacing with clients.

KEY RESPONSIBLITIES:
Preparing project proposals and discussing potential projects with clients and stakeholders
Facilitating project initiation by defining project scope and requirements, and preparing the necessary documents and requirements
Developing project plans and timelines to ensure the timely submission of project deliverables
Managing project budgets and resources to ensure the timely completion of milestones
Tracking and documenting progress and communicating project status updates to key stakeholders
Identifying and managing project risks
Facilitating team meetings and collaboration
Liaising for changes and negotiations with relevant stakeholders
Ensuring software quality standards are met and requirements are submitted within budget and on time
Closing the project and ensuring proper documentation
CHALLENGES:
Unclear and undefined expectations
Changing project requirements and priorities
Steep learning curve
Time constraint
Poor communication
High competition
Project cancellation
Quality testing
Skills management
Steep learning curve

Software Maintenance:

Define software maintenance and explain the different types of maintenance activities. Why is maintenance an essential part of the software lifecycle?
Software Maintenance refers to the process of the process of regularly nurturing and enhancing the software to eliminate bugs, improve performance, modify features, and undertake other tasks to optimize the software such that it provides the best experience to its users. modifying and updating a software system after it has been delivered to the customer. It is a continuous process that occurs throughout the entire life cycle of the software system.
Software maintenance is a critical part of the software development life cycle (SDLC) and is necessary to ensure that the software continues to meet the needs of the users over time. It begins after the software is deployed and is performed to ensure the software is regularly enhanced to match the changing market demands.
TYPES OF MAINTENANCE ACTIVITIES:

1. Adaptive maintenance
   Involves modifying the software system to adapt it to changes in the environment, such as changes in hardware or software, government policies, and business rules.Tech teams perform adaptive maintenance to adapt their existing software to changing business needs and development environments. It helps companies ensure that the software can keep up with these changes and continue functioning correctly.
2. Corrective software maintenance
   Corrective software maintenance is undertaken to fix software errors like poor database design, bugs, viruses, security vulnerabilities, etc. However, corrective maintenance should not be confused with problem-solving; Because here, the goal is to fix the errors, not to design new solutions.
   Usually, corrections come from user-generated bug reports, but corrective software maintenance can help to spot them in advance.
3. Preventive software maintenance
   Preventive software maintenance keeps your software functioning efficiently in the long run. It focuses on reducing the deterioration risk of your software and improves its scalability and reliability in the future.
   Preventive maintenance includes activities like code optimization, revised documentation, code refactoring, database performance management, anti-virus protection, etc.
4. Perfective software maintenance
   It enhance the overall performance and usability of the software. Tech teams perform perfective software maintenance to modify features, elements, and user interfaces to suit the evolving business goals and the expectations of the end users.

Ethical Considerations in Software Engineering:

What are some ethical issues that software engineers might face? How can software engineers ensure they adhere to ethical standards in their work?
ETHICAL ISSUES:

1. Algorithm bias
2. Unethical data collection
3. Weak security
4. Power Of Quantum Computing
5. AI Accountability
6. Misuse Of Personal Data
7. Waning consumer privacy

ADHERENCE TO ETHICAL STANDARDS:

1.  Be proactive
    While you work honestly when writing code, there’s no telling where it can lead to. The client and your team can easily veer away from the original purpose of your project. Throughout the process of development, think of the potential threats and misconduct that can happen.
2.  Be a responsible citizen
    Software developers have this opportunity to build a product that will either benefit users or hurt them. Prioritize your responsibilities as a good citizen over your reputation as an expert. Only work on projects that you believe are secure, comply with specifications, and can withstand mandatory testing.
3.  Be accountable
    You should strive to improve the integrity and reputation of the profession as a software engineer. For instance, you should avoid making false claims regarding your application that could be deceptive or misleading.
4.  Be honest
    Falsely advertising features or exaggerating the performance quality is unethical. Be straightforward and truthful while describing your goods. Inform the audience if the vision changes. Inform stakeholders as soon as there are updates or modifications to the software. To ensure that the product will be utilized as intended, create policies with the help of other teams inside your organization.

        REFERENCES:
        geeksforgeeks.org
        guru99.com
        tryqa.com
        coursera
        institutedata.com
        thedevpost.com
        simform.com
        techtarget.com

    Submission Guidelines:
    Your answers should be well-structured, concise, and to the point.
    Provide real-world examples or case studies wherever possible.
    Cite any references or sources you use in your answers.
    Submit your completed assignment by [due date].
