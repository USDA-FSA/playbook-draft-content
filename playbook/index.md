---
title: "FSA Playbook"
intro: "Details best practices to build and deliver digital services like web and mobile applications at FSA that work well for the American people and require less time and money to develop and operate."
---

## Testing

1. Identify all interactions on the page.
2. Use the tab, enter, and space bar to navigate the page and ensure each input/interaction can be triggered.
  * Ensure rollover / hover interactions (help text, etc.) can be triggered as well.
  * __If the user cannot interact with something, or get the information another way, this is a failure__.
3. Make sure the tab order of the page is logical and follows the visual order of elements on the page.
  * __If the tab order is confusing, this is a failure__.
4. Check that the focus is always visible when moving through the page with the tab key.
  * __If you lose focus, on a hidden link or other object when simply tabbing through the page, this is a failure__.
5. Make sure you can tab through the page and get back the address bar.
  * __If you ever need your mouse to get back to an element, this is a failure__.
6. Keyboard users must be able to easily use and dismiss modal dialog boxes, lightboxes, or other pop-ups.
  * Modal dialog boxes need to trap the keyboard. When a modal dialog box is triggered, the keyboard focus needs to immediately move to the first actionable element in the modal.
  * The keyboard cannot use the modal dialog box until it is dismissed. When a user moves the keyboard focus past the last element in the modal dialog box, it needs to loop to the beginning of the dialog box.
  * The keyboard user needs to be able to access all controls in the dialog box, especially the controls to dismiss the dialog.
  * __If the keyboard user cannot do all of these things, this is a failure__.
  * Ideally, the keyboard user should also be able to dismiss the modal dialog box with the Escape key.
7. If an interaction reveals hidden content...
  * Ensure the focus is moved to the revealed content.
    * If this does not happen, check for a programmatic description of the change.
8. Check for title tags providing information not on the screen.
  * __Title attributes which can only be exposed by hovering the mouse over the element are a failure of keyboard access__.
9. Check that the focus never goes to elements that won't be available to somebody using a mouse.
  * __If the keyboard focus goes to an offscreen element that has been temporarily hidden (items in a non-expanded drop-down menu, offscreen modals which haven't been triggered, etc.), this is a failure__.

## FSA Digital Playbook

FSA employees depend on Information technology every day to accomplish the agency’s mission. FSA’s stakeholders, including farmers and ranchers, channel partners, and other agencies, expect to interact with the agency through digital channels such as websites, email, and mobile applications. By building digital services that meet the needs of all our stakeholders, we can make the delivery of our policy and programs more effective.
Today, too many of our digital services projects do not work well, are delivered late, or are over budget. To increase the success rate of these projects, FSA needs a new approach. We created a playbook for our target state architecture based upon the US Digital Services (USDS) Playbook (http://playbook.cio.gov/). We have adapted the USDS playbook to focus on FSA’s needs, goals and environment, and enhanced it with principles to guide implementation and the capabilities the organization should improve or create to effectively put the plays into action.
FSA Digital Service Plays
1 Understand What People Need
2 Address the whole experience, from start to finish
3 Make it simple and intuitive
4 Build the service using agile and iterative practices
5 Structure budgets and contracts to support delivery
6 Assign one leader and hold that person accountable
7 Bring in experienced teams
8 Choose a modern technology stack
9 Deploy in a flexible hosting environment
10 Deploy in a flexible hosting environment
11 Manage security and privacy through reusable processes
12 Use data to drive decisions
13 Default to open

Play 1: Understand What People Need
We must begin digital projects by exploring and pinpointing the needs of the people who will interact with the service, and the ways the service will fit into their work and lives. Whether the stakeholders are members of the public or government employees, we must include them in the design process from the beginning. The needs of people should not be subordinated to constraints of government organizational structures or the capabilities of existing products. We need to continually test the products we build with real people to keep us honest about what is important.
Capabilities to Support This Play
•	Cross-functional Teaming
•	Agile Enterprise Architecture
•	Dev/Test/Ops Automation Management
Checklist
o	Early in the project, spend time with current and prospective users of the service
o	Use a range of qualitative and quantitative research methods to determine people’s goals, needs, and behaviors; be thoughtful about the time spent
o	Test prototypes of solutions with real people, in the field if possible
o	Document the findings about user goals, needs, behaviors, and preferences
o	Share findings with the team and agency leadership
o	Create a prioritized list of tasks the user is trying to accomplish, also known as “user stories”
o	As the service is being designed, regularly validate the design with the people who will support the service throughout its lifecycle
o	As the digital service is being built, regularly test it with potential users to ensure it meets their needs
Key Questions
•	Who are your primary users?
•	What user needs will this service address?
•	Why does the user want or need this service?
•	Which people will have the most difficulty with the service?
•	Which research methods were used?
•	What were the key findings?
•	How were the findings documented? Where can future team members access the documentation?
•	How often are you testing with real people?
•	Have you included the needs of people who support the service?
Play 2: Address the whole experience, from start to finish
FSA program delivery frequently requires multiple steps, involves multiple people and uses information gathered from a variety of sources at different times. There is legitimate business complexity to deal with. That need not be compounded by having a complex service to do with work in. We should build systems with clear workflows that supply users operating in any channel with the right information and options at the right time.
Capabilities to Support This Play
•	Cross-functional Teaming
•	Dev/Test/Ops Automation Management
Checklist
o	Understand the different points at which people will interact with the service – both online and in person
o	Understand the workflows of people using the service, and make their work easier and more straightforward
o	Identify pain points in the current way users interact with the service, and prioritize these according to user needs
o	Integrate the information systems that support a service below the surface – users should not see or have to think about the seams
o	Design the digital parts of the service so that they are integrated with the offline touch points people use to interact with the service
o	Develop metrics that will measure how well the service is meeting user needs at each step of the service
Key Questions
•	What are the different ways (both online and offline) that people currently accomplish the task the digital service is designed to help with?
•	Where are user pain points in the current way people accomplish the task?
•	Where does this specific project fit into the larger way people currently obtain the service being offered?
•	What metrics will best indicate how well the service is working for its users?
Play 3: Make it simple and intuitive
Using an FSA service should not be over-complicated for employees who know the tasks and the information and simply need an efficient and effective way to work. Our digital services should also not be stressful, confusing, or daunting for customers and channel partners. Nonetheless, there are elements of FSA’s business that are complex by nature and should not be oversimplified. We should aim for the balance of building services that are simple and intuitive enough that users succeed the first time, unaided, while at the same time making sure that those services include the features necessary to do the job.
Capabilities to Support This Play
•	Cross-functional Teaming
Checklist
o	Use a simple and flexible design style guide for the service. Use the U.S. Web Design Standards as a default
o	Use the design style guide consistently for related digital services
o	Give users clear information about the context they are working in where they are in each step of the process
o	Follow accessibility best practices to ensure all people can use the service
o	Consider providing users with a way to exit and return later to complete the process
o	Use language that is familiar to the user and easy to understand
o	Use language and design consistently throughout the service, including online and offline touch points
Key Questions
•	What primary tasks are the user trying to accomplish?
•	Is the language as plain and universal as possible?
•	What languages is your service offered in?
•	If a user needs help while using the service, how do they go about getting it?
•	How does the service’s design visually relate to other government services?
Play 4: Build the service using agile and iterative practices
We should use an incremental, fast-paced style of software development to reduce the risk of failure. We want to get working software into users’ hands as early as possible to give the design and development team opportunities to adjust based on user feedback about the service.
A critical capability is defining a minimum viable product and subsequent releases such that real value is being delivered to users early and often.
Another key capability is being able to automatically test and deploy the service so that new features can be added often and be put into production easily. Getting the full benefit of this capability is not a simple matter of installing tools, but requires skill development, careful process design, transparency and accountability.
Capabilities to Support This Play
•	Agile Development Management
•	Dev/Test/Ops Automation Management
•	Continuous Delivery
•	Safe Packaging
•	Modern Services Architecture
Checklist
o	Ship a functioning “minimum viable product” (MVP) that solves a core user need as soon as possible, no longer than three months from the beginning of the project, using a “beta” or “test” period if needed
o	Run usability tests frequently to see how well the service works and identify improvements that should be made
o	Ensure all members of the cross functional team (including business users) communicate closely using techniques such as launch meetings, war rooms, daily standups, and team chat tools
o	Keep delivery teams small and focused; limit organizational layers that separate these teams from the business owners
o	Release features and improvements multiple times each month
o	Create a prioritized list of features and bugs, also known as the “feature backlog” and “bug backlog”
o	Use code reviews to ensure quality
Key Questions
•	How long did it take to ship the MVP? If it hasn’t shipped yet, when will it?
•	How long does it take for a production deployment?
•	How many days or weeks are in each iteration/sprint?
•	How are bugs tracked and tickets issued?
•	How is the feature backlog managed?
•	How often do you review and reprioritize the feature and bug backlog?
•	How, and how often, do you collect user feedback during development? How is that feedback used to improve the service?
•	At each stage of usability testing, which gaps were identified in addressing user needs?
Play 5: Structure budgets and contracts to support delivery
Aligning budgeting and contracting practices with transformational goals is critical to success. In cases where third parties help to build or operate a service, FSA needs contracts structured to assure the right talent and the right skill level is provided. Contracts should reinforce FSA’s system development life cycle (SDLC) and governance processes.
Budget and contracting practices should reinforce the Federal CIO’s direction to include open source in product selections, and should use the Agency’s enterprise architecture as an authoritative source for the scope and bounds of products to be selected.
Our budget and contracting practices should also reinforce the Federal Cloud First policy by aligning incentives and removing obstacles to cloud services adoption.
The TechFAR Handbook , developed by the US Digital Service in the Office of the President, provides a detailed explanation of the flexibilities in the Federal Acquisition Regulation (FAR) that can help agencies implement this play.
Contract vehicles should be created that enable competition among contracting firms, with short (six months) performance periods

Capabilities to Support This Play
•	Agile Enterprise Architecture
•	Agile Development Management
Checklist
o	Budget includes research, discovery, and prototyping activities
o	Integrated Project Team (IPT) is formed prior to contract award. IPT creates Product Vision (as defined in the TechFAR Handbook)
o	Contract is created with reference to sample wording in the TechFAR Handbook
o	Contract reinforces adherence to  FSA SDLC, governance and technical standards
o	Contract identifies a Product Vision and an explanation of how the Agile process will be used to achieve the Product Vision
o	Contract is structured to request frequent deliverables, not multi-month milestones
o	Contract is structured to hold vendors accountable to deliverables
o	Contract gives the government delivery team enough flexibility to adjust feature prioritization and delivery schedule as the project evolves
o	Contract ensures open source solutions are evaluated when technology choices are made
o	Contract specifies that software and data generated by third parties remains under our control, and can be reused and released to the public as appropriate and in accordance with the law
o	Contract allows us to use tools, services, and hosting from vendors with a variety of pricing models, including fixed fees and variable models like “pay-for-what-you-use” services
o	Contract specifies a warranty period where defects uncovered by the public are addressed by the vendor at no additional cost to the government
o	Contract includes a transition of services period and transition-out plan
Key Questions
•	Does the contract provide sufficient flexibility for the Government to hold contracting team accountable for performance at no greater than a six month timeframe?
•	What is the scope of the project? What are the key deliverables?
•	What are the milestones? How frequent are they?
•	What are the performance metrics defined in the contract (e.g., response time, system uptime, time period to address priority issues)?
Play 6: Assign one leader and hold that person accountable
Organizational handoffs frequently slow service delivery down and add unnecessary complexity to the service delivery value chain. There must be a single product owner with the authority and availability to make product decisions when the team needs direction.  This product owner is ultimately responsible for how well the service meets needs of its users, which is how a service should be evaluated. The product owner is responsible for ensuring that features are built and managing the feature and bug backlogs.
Supporting this under FSA’s organization structure would require closer teaming arrangements between the development and shared service organizations. Managers in the shared services would need effective tools and processes to manage their capacity and to provide timely and accurate data on where their capacity is used, while budget and contracting practices would need to adjust the shared services staff and skills effectively.
Capabilities to Support This Play
•	Agile Development Management
Checklist
o	A product owner has been identified
o	All stakeholders agree that the product owner has the authority to make decisions about features and technical implementation details
o	The product owner has a work plan that includes budget estimates and identifies funding sources
o	Cross-organizational resource needs are identified and agreements have been made to allot staff to the project at the right times
o	The product owner has a strong relationship with the contracting officer
Key Questions
o	Who is the product owner?
o	Will the product owner be available for face-to-face meetings on a regular basis with the team?
o	Does the product owner have authority to make product and feature decisions?
o	What organizational changes have been made to ensure the product owner has sufficient authority over and support for the project?
Play 7: Bring in experienced teams
FSA needs talented people who have experience creating modern digital services. This includes bringing in seasoned product managers, engineers, and designers. User experience design is a critical success factor for modern services, and the need is made more acute in FSA program delivery due to the inherent complexity of some of our programs. Experience with testing distributed service-oriented systems and supporting them in a modern production environment is essential.
When outside help is needed, our teams should work with contracting officers who understand how to evaluate third-party technical competency so our teams can be paired with contractors who are good at both building and delivering effective digital services. When third party help is used to design, develop or operate our services, we should use contracting practices that assure we are getting the level of talent, team composition and team size that the job requires.
Capabilities to Support This Play
•	Agile Development Management
Checklist
o	Team members have experience designing mobile and web applications
o	Team members have experience using automated testing frameworks
o	Team members have experience with modern development and operations (DevOps) techniques like continuous integration and continuous deployment
o	Team members have experience securing digital services
o	Team members have experience building high-traffic digital services
o	A Federal contracting officer is on the team if a third party will be used for development work
o	A Federal budget officer is on the team or is a partner
o	The appropriate privacy, civil liberties, and/or legal advisor for the department or agency is a partner
Play 8: Choose a modern technology stack
Our technology decisions need to address shortcomings in the current state of the enterprise, address real business need, and support federal-wide initiatives for delivering higher-quality digital services more quickly.
We need to enable development teams to work efficiently and enable services to scale easily and cost-effectively. Our choices for hosting infrastructure, databases, software frameworks, programming languages and the rest of the technology stack should seek to avoid vendor lock-in and match what successful modern consumer and enterprise software companies would choose today.
In particular, digital services teams should consider using open source, cloud-based, and commodity solutions across the technology stack, because of their widespread adoption and support by successful consumer and enterprise technology companies in the private sector.
Adopting expensive and heavyweight software packages should be approached with great care. We need to assure that we are not buying, maintaining and scaling features that we do not need. Off-the-shelf solutions must be modular and their module boundaries should have a close match to our needs. We should be very conservative with incidental features, such internal workflows, which have the effect of pulling unrelated functionality into the packaged software and leading to heavy customization.
Capabilities to Support This Play
•	Agile Enterprise Architecture
•	Microservices Architecture
•	Safe Packaging
Checklist
o	Choose software frameworks that are commonly used by private-sector companies creating similar services
o	Provide sufficient service and data isolation so automated tests are repeatable
o	Whenever possible, ensure that software can be deployed on a variety of commodity hardware types
o	Ensure that acquired systems are easy to integrate with rather than tending to subsume everything around them and become complex, expensive and intractable monoliths
o	Ensure that acquired systems are modular so that we only install, maintain and scale what we really use
o	Ensure that each project has clear, understandable instructions for setting up a local development environment, and that team members can be quickly added or removed from projects
o	Consider open source software solutions at every layer of the stack
Key Questions
•	What is your development stack and why did you choose it?
•	Which databases are you using and why did you choose them?
•	Does the technology stack support development of automated tests?
•	How long does it take for a new team member to start developing?
•	For acquired systems, are we clear about how information will be effectively integrated?
•	For acquired systems, are we clear about where the functional boundaries are?
•	When this technology becomes obsolete, how hard will it be to move away from it?
Play 9: Deploy in a flexible hosting environment
Well-designed services can still fail to meet expectations if they are not hosted on infrastructure that can meet capacity and availability demands. Our services should be deployed on flexible infrastructure, where resources can be provisioned quickly to meet spikes in traffic and user demand. Our services are crippled when we host them in data centers that require us to manage and maintain hardware through heavyweight, manual processes. This outdated practice wastes time, weakens our disaster recovery plans, and results in significantly higher costs. Our ability to be agile is impeded when a lack of control introduces risk and friction.  
Capabilities to Support This Play
•	Design for Resilience
•	Safe Packaging
•	Adaptive Infrastructure Management
•	Transparent Infrastructure Management

Checklist
o	Resources are provisioned on demand
o	Resources scale based on user demand
o	Resources are provisioned through an API
o	Resources are available in multiple geographic regions
o	We only pay for resources we use
o	Static assets are served through a content delivery network
o	Application is hosted on commodity hardware
Key Questions
•	Where is your service hosted?
•	What hardware does your service use to run?
•	What is the demand or usage pattern for your service?
•	What happens to your service when it experiences a surge in traffic or load?
•	How much capacity is available in your hosting environment?
•	How long does it take you to provision a new resource, like an application server?
•	How have you designed your service to scale based on demand?
•	How are you paying for your hosting infrastructure (e.g., by the minute, hourly, daily, monthly, fixed)?
•	Is your service hosted in multiple regions, availability zones, or data centers?
•	In the event of a catastrophic disaster to a datacenter, how long will it take to have the service operational?
•	What would be the impact of a prolonged downtime window?
•	What data redundancy do you have built into the system, and what would be the impact of a catastrophic data loss?
•	How often do you need to contact a person from your hosting provider to get resources or to fix an issue?
Play 10: Automate test and deployment
Over the past few years, FSA has made significant strides in automating system delivery. But there are still manual bottlenecks and some parts of the value stream that are not as transparent and manageable than they could be. Further improvements would help FSA leverage the full value of what it has already invested in automation in terms of much higher-quality software delivered more quickly.
Capabilities to Support This Play
o	Dev/Test/Ops Automation Management
o	Continuous Delivery
o	Safe Packaging
Checklist
o	Create automated tests that verify all user-facing functionality
o	Create unit and integration tests to verify modules and components
o	Create user journey tests that exercise entire end-to-end business scenarios
o	Use pessimistic test harnesses that test resilience by simulating network or hardware failure modes not achievable in integration testing
o	Run tests automatically as part of the build process
o	Perform deployments automatically with deployment scripts, continuous delivery services, or similar techniques
o	Conduct load and performance tests at regular intervals, including before public launch
Key Questions
•	Can stakeholders easily verify that a passing test suite correlates to satisfaction with the system?
•	What percentage of the code base is covered by automated tests?
•	How long does it take to build, test, and deploy a typical bug fix?
•	How long does it take to build, test, and deploy a new feature into production?
•	How frequently are builds created?
•	What test tools are used?
•	Which deployment automation or continuous integration tools are used?
•	What is the estimated maximum number of concurrent users who will use the system?
•	How many simultaneous users could the system handle, according to the most recent capacity test?
•	How does the service perform when you exceed the expected target usage volume? Does it degrade gracefully or catastrophically?
•	How does the service compensate for failure of collaborating services?
•	What is your scaling strategy when demand increases suddenly?
Play 11: Manage security and privacy through reusable processes
Our digital services have to protect sensitive information and keep systems secure. Security and privacy should be built first into the environment our service will operate in, and then designed into each service from the beginning. At the start of designing a new service or feature, the team lead should engage the appropriate privacy, security, and legal officer(s) to discuss the type of information collected, how it should be secured, how long it is kept, and how it may be used and shared. The sustained engagement of a privacy specialist helps ensure that personal data is properly managed.
In addition, a key process to building a secure service is comprehensively testing and certifying the components in each layer of the technology stack for security vulnerabilities, and then to re-use these same pre-certified components for multiple services.
The following checklist provides a starting point, but teams should work closely with their privacy specialist and security engineer to meet the needs of the specific service.
Capabilities to Support This Play
•	Cross-functional Teaming
•	Agile Enterprise Architecture
•	Dev/Test/Ops Automation Management
Checklist
o	Contact the appropriate privacy or legal officer of the department or agency to determine whether a System of Records Notice (SORN), Privacy Impact Assessment, or other review should be conducted
o	Determine, in consultation with a records officer, what data is collected and why, how it is used or shared, how it is stored and secured, and how long it is kept
o	Determine, in consultation with a privacy specialist, whether and how users are notified about how personal information is collected and used, including whether a privacy policy is needed and where it should appear, and how users will be notified in the event of a security breach
o	Consider whether the user should be able to access, delete, or remove their information from the service
o	“Pre-certify” the hosting infrastructure used for the project using FedRAMP
o	Use deployment scripts to ensure configuration of production environment remains consistent and controllable
Key Questions
•	Does the service collect personal information from the user? How is the user notified of this collection?
•	Does it collect more information than necessary? Could the data be used in ways an average user wouldn’t expect?
•	How does a user access, correct, delete, or remove personal information?
•	Will any of the personal information stored in the system be shared with other services, people, or partners?
•	How and how often is the service tested for security vulnerabilities?
•	How can someone from the public report a security issue?
Play 12: Use data to drive decisions
At every stage of a project, we should measure how well our service is working for our users. We use that intelligence to prioritize improvements, understand shortcomings, and to try to predict and avoid future problems.
Data about current systems performance and user needs drives architecture decisions for the next generation systems. Also, tools that add visibility into all of the components used in our services and their deployed versions would allow us to react to end-of-support issues and vulnerability discoveries more quickly.
We have some capabilities to measure how well a system performs and how people are interacting with it in real-time. Process and resource constraints currently limit the availability and usability of that data. Our teams and agency leadership should be empowered to watch these metrics to find issues and identify which bug fixes and improvements should be prioritized. Along with monitoring tools, better feedback mechanisms should be in place for people to report issues directly.
Capabilities to Support This Play
•	Agile Enterprise Architecture
•	Design for Resilience
•	Infrastructure Transparency
Checklist
o	Monitor system-level resource utilization in real time
o	Monitor system performance in real-time (e.g. response time, latency, throughput, and error rates)
o	Ensure monitoring can measure median, 95th percentile, and 98th percentile performance
o	Create automated alerts based on this monitoring
o	Track concurrent users in real-time, and monitor user behaviors in the aggregate to determine how well the service meets user needs
o	Publish metrics internally
o	Publish metrics externally
o	Use an experimentation tool that supports multivariate testing in production
Key Questions
•	What are the key metrics for the service?
•	How have these metrics performed over the life of the service?
•	Which system monitoring tools are in place?
•	What is the targeted average response time for your service? What percent of requests take more than 1 second, 2 seconds, 4 seconds, and 8 seconds?
•	What is the average response time and percentile breakdown (percent of requests taking more than 1s, 2s, 4s, and 8s) for the top 10 transactions?
•	What is the volume of each of your service’s top 10 transactions? What is the percentage of transactions started vs. completed?
•	What is your service’s monthly uptime target?
•	What is your service’s monthly uptime percentage, including scheduled maintenance? Excluding scheduled maintenance?
•	How does your team receive automated alerts when incidents occur?
•	How does your team respond to incidents? What is your post-mortem process?
•	Which tools are in place to measure user behavior?
•	What tools or technologies are used for A/B testing?
•	How do you measure customer satisfaction?
Play 13: Default to open
By building services more openly and publishing open data, we simplify the public’s access to government services and information, allow the public to contribute easily, and enable reuse by entrepreneurs, nonprofits, other agencies, and the public.
FSA does not currently contribute source code to the public domain. Much of the FSA code base could be considered for open source designation.  Public value would be enhanced as the source code base becomes accessible to other Federal agencies.
Most of FSA’s open data contributions currently involve manual update and management, and result in simple file drops to the public web site. With modern data and services architectures in place, more of this could be automated, and public value could be enhanced by offering APIs rather than periodic file drops.

Capabilities to Support This Play
•	Agile Enterprise Architecture
Checklist
o	Offer users a mechanism to report bugs and issues, and be responsive to these reports
o	Provide datasets to the public, in their entirety, through bulk downloads and APIs (application programming interfaces)
o	Ensure that data from the service is explicitly in the public domain, and that rights are waived globally via an international public domain dedication, such as the “Creative Commons Zero” waiver
o	Catalog data in the agency’s enterprise data inventory and add any public datasets to the agency’s public data listing
o	Ensure that we maintain the rights to all data developed by third parties in a manner that is releasable and reusable at no cost to the public
o	Ensure that we maintain contractual rights to all custom software developed by third parties in a manner that is publishable and reusable at no cost
o	When appropriate, create an API for third parties and internal users to interact with the service directly
o	When appropriate, publish source code of projects or components online
o	When appropriate, share your development process and progress publicly
Key Questions
•	How are you collecting user feedback for bugs and issues?
•	If there is an API, what capabilities does it provide? Who uses it? How is it documented?
•	If the codebase has not been released under an open source license, explain why.
•	What components are made available to the public as open source?
•	What datasets are made available to the public?
Context
FSA relies upon information technology to complete its mission. FSA’s priority is to maintain current IT systems and services to ensure its availability, reliability, security and integrity, while planning and deploying new IT improvements through a host of forward looking initiatives. These initiatives include new business model support, enabling business process improvements through technology, replacement of outdated technology, and expansion of customer-focused operational improvements. Example outcomes include new customer self-service capabilities, improvements in program management and business analytics tools, creating workforce flexibilities, and operational platform consolidation, among others.
FSA Strategic Plan FY 2014-2018

Recent evaluations of FSA’s IT performance by OIG and MITRE have recommended an authoritative technical target architecture. Among the issues identified in those evaluations, those that the technical target architecture should approach can be summarized as:
•	Application architecture approaches have resulted in application silos with duplicative functionality
FSA has developed many program-specific applications that duplicate functionality with subtle variations, which increases portfolio complexity, development cost and lead times while increasing the burden of application operation and maintenance.
•	Data management approaches have resulted in widespread data replication
Due to an insufficient data services approach, FSA’s silo applications replicate data without a holistic master data management facility. This makes it hard to ensure that data provided by applications is current and timely for use in business activities. It also makes it difficult to identity the system of record for data entities.
•	IT infrastructure approaches have resulted in lack of platform resilience
FSA’s infrastructure is managed by multiple organizations in multiple geographic locations, introducing a level of complexity that often brings value creation activities to a halt. Infrastructure Management can benefit from modern automation, monitoring and alerting practices. Service level agreements that are in place do not meet FSA’s needs.
•	Waterfall development approaches have resulted in long lead times, technical debt and high risk
For both custom development and COTS implementation, FSA’s iterative waterfall development approach prevents timely delivery of features, inhibits adaptation to new requirements, and complicates communication among stakeholders.
•	Lack of a common technical architecture has resulted in reduced serviceability
The time, money and effort that FSA put into adopting SAP has taken away from the Agency’s capacity to pursue a technical architecture that stays current with technology industry trends. The outcome was a highly customized ERP system that is expensive, incomplete and does not fit FSA’s needs. As a result, FSA still has multiple application silos without a common user experience, single sign-on or customer self-service.
The original vision for MIDAS formed in the mid 2000’s.  The core architecture of FSA’s web applications developed in the same period. Since then, huge shifts in technology, society, and the agriculture industry have emerged.  In this revalidation, we have a chance to refresh the Farm Programs modernization concept (which is still critically needed) to account for these new realities.
•	Web 2.0 Companies Explode:  Facebook, Amazon, Netflix, and Google (FANG) have become essential tools for daily life for many Americans.  As a result, everyone is becoming technology savvy.  And the User Experience from these companies raise the bar on how people expect technology to work (simple, fast and intuitive).  Everyone does eCommerce.
•	Broadband Expands Rapidly:  Customer demand has driven innovation and lowered cost of fast internet, even into rural communities.
•	Mobile Data: Smartphones and tablets have put mobile computers into the hands of people globally.  Lower cost mobile delivery has made mobile data service available to most places in the US.
•	Precision Ag:  Advanced technology has arrived in the last major industry to be automated.  The economics of removing input waste (seeds, chemicals, fuel, time, water) are accelerating the capture of detailed farm operating and geospatial information.  Commercial drones are now approved.  Ag equipment is being retrofitted.  Upgrading will become an issue of survival for many farm businesses.
•	Cloud:  The internet giants have transformed the model for technology hosting out of sheer necessity (making the management of millions of servers and applications fully automated and repeatable).  
•	End User Technology:  The free tools that drive the user experience at FANG companies are disrupting the entire industry, killing proprietary products like Microsoft Silverlight and Adobe Flash, and driving new architectures.
•	Transformed Delivery Methods:  New and more effective approaches to delivering solutions are causing a sea change in all companies.  Agile, DevOps, Test-driven Development, Continuous Delivery and others are shortening delivery timelines, reducing risk and cost,  and bring the business and IT closer together.
All of these items influence how FSA needs to adapt its future IT solutions delivery. FSA’s Target Technical Enterprise Architecture will address IT shortcomings with modern approaches that have found great success in industry. Key sources of those approaches include:
•	The US Digital Services Playbook (http://playbook.cio.gov), a product of the US Digital Service in the Office of the President. OMB’s FY 2018 IT budget guidance lists “Implement IT reforms based upon current guidance and best practices such as U.S. Digital Service Playbook…” as one of the objectives for agency management of IT investments.
•	The 12 Factor App (http://12factor.net), compiled by Heroku, a leading cloud application hosting provider. 12 Factor App to describe the key success factors found in the applications they host.
Principles
1 Service
2 Security
3 Agility
4 Collaboration
5 Resilience
6 Innovation
Principle 1 Service
The most fundamental architecture principle is support for the delivery, management and oversight of FSA’s mission delivery. This principle underlies everything else. The architecture must address and balance the real needs of all stakeholders, including users, managers, analysts, IT operations staff and system developers. When any user is interacting with an application or service from FSA, the transaction should be efficient and simple. The user should have confidence that the processes are predictable and the information trustworthy. The user should be able to interact with the system as a unified whole, and should not be aware of how the IT systems are organized.
Principle 2 Security
Another underlying principle is security. FSA’s stakeholders rely on the safety of their information used in the Agency’s processes and on the availability of our services. Security is more than an application issue or a platform issue and cannot be adequately addressed by spot solutions on a per-system basis. It needs to be addressed enterprise-wide and designed into processes and systems in a consistent, balanced and coherent way.
Principle 3 Agility
Responding quickly and accurately to change is more important today than it has ever been. Technology has become so embedded into people’s everyday lives that technology changes become culture changes. Those changes affect the way customers and partners expect to interact with FSA as well as how employees expect to interact with one another. Current technology trends have found their way into laws and top-level Federal policy. Agility is required to cope with these changes.
Agility improves FSA’s service delivery by making it possible to implement mission changes more quickly, without sacrificing quality. It improves the ability to back out of changes to enterprise systems, allowing the agency to experiment and innovate more safely. It also makes the enterprise more resilient and secure by improving the capability to respond to software defects in production, newly-discovered threats or vulnerabilities.
One often-overlooked effect of rapid technological/cultural change is that specific technologies become disposable. To be agile in the face of this effect, FSA needs to strive for loose coupling with vendor products, programming languages and platforms.
Principle 4 Collaboration
Responding quickly and accurately to change requires frequent and frictionless communication between team members and stakeholders. Inclusion, high trust and open information sharing helps to build a common vision and reduce misunderstandings about priorities and scope.
A collaborative environment improves service delivery when it includes the viewpoints of customers and users. It improves security when it engages security and privacy staff early and openly. By getting more perspectives into the project, collaboration improves a team’s ability to innovate.
Collaboration requires trust and shared accountability.  Organizational changes may be required to ensure that all team members share a common goal that ties to compensation.
Principle 5 Resilience
FSA may not operate at the scale of Google, Facebook or Netflix, but having systems that are available and stable is as important for our customers, users and other stakeholders. By leveraging lessons learned from Google Facebook and Netflix, FSA can deliver services consistent with the expectations of our users.
Principle 6 Innovation
[TODO Discussion]
Capabilities
1 Cross-functional Teaming
2 Agile Enterprise Architecture
3 Design for Resilience
4 Agile Development Management
5 Modern Services Architecture
6 Dev/Test/Ops Automation Management
7 Continuous Delivery
8 Safe Packaging
9 Adaptive Infrastructure
10 Infrastructure Transparency
Capability 1: Cross-functional Teaming
Organizational and contractual barriers often hamper FSA’s ability to team effectively over the full lifecycle of a system. In some cases the business and development teams develop productive working relationships, but find it hard to extend that relationship into shared services areas like security, testing, data management and operations. The Agency should identify those instances in which cross-functional teaming has worked well, determine why it worked, and then extend the best ideas across projects. Researching teaming success stories in other government agencies and finding ways to map those to FSA’s circumstances would also be valuable.
The composition of teams should represent, to the extent possible, the interests of all user communities. Team membership should be broad enough to knowledgably all of the stages and channels involved in a service delivery value chain. Teams representing a wide array of stakeholders will have greater sensitivity to users’ contexts and their preferred styles of interaction.
For iterative development, the delivery team should include a fully-engaged business user capable of making daily decisions. The team should share a common set of accountabilities, and should be long-lived, spanning multiple deliveries.
Capability 2: Agile Enterprise Architecture
EA business capability mapping and assessment uncovers business and mission needs from the Agency viewpoint, while broader stakeholder and industry trend analyses brings in the needs of customers, partners and other interest groups.
Current-state architecture is a data-rich environment, especially when adequate discovery and monitoring tools are in place. Information about what works well and what could work better is one driver for future-state architectures.
EA technology specifications should provide for the agility of the system delivery value chain.
The enterprise-wide architecture identifies where data at rest or in transit is vulnerable, assesses the risks, and includes patterns and components for appropriately addressing risks.
Part of Enterprise Architecture’s traditional mandate is to foster reuse. An open approach to development and delivery encourages reuse of our solutions. Sharing also allows more people to comment on our plans and offer improvements.
Capability 3: Design for Resilience
We must design our services so that they not only pass QA tests, but also the slings and arrows of production. Hard drives crash, networks fail or become congested or develop bizarre routing anomalies, configuration changes have unexpected consequences, denial of service attacks occur… the list goes on of things that are unlikely to be found in an acceptance, integration or load test. For our services to thrive in this kind of landscape they need to be able to protect themselves, to treat their environments, users and collaborators with skepticism, fail gracefully if necessary, and try not to be part of the problem.
Some component capabilities of designing for resilience include:
•	Having team members with experience in the complexity of online systems and their failure modes helps to prevent many defects from happening, and improves recovery time when problems do occur.
•	Systems should be designed to take advantage of the automated scaling, health-checking and failover capabilities found in cloud-hosted Platform-as-a-Service environments.
•	Testing tools can be programmed and configured to explore failure scenarios.
•	Systems should be designed to emit the kind of data that would support health monitoring and log analysis.
Capability 4: Agile Development Management
Agile teams are typically small, skilled teams. Larger teams and lack of experience introduces communication overhead and friction. These teams depend on there being a person who is accountable for managing product features.
Agile team practices should reduce friction in the software delivery value chain. Automation in general reduces friction in the system delivery value chain and gives the cross-functional team the time and confidence to develop features quickly and incrementally.
Contracts need to be developed that do not re-introduce friction or impede accountability.  FSA should follow the lead of other Federal agencies using flexible agile contracts, such as US Customs and Immigration Service (USCIS), Department of Homeland Security (DHS), Transportation Security Agency (TSA), Environmental Protection Agency (EPA), and General Services Administration (GSA)
Capability 5: Modern Services Architecture
A modern services architecture uses highly cohesive, loosely coupled services that are responsible for a well-defined part of the business domain. These services are designed so that they can be redeployed, or even completely re-written, independently. A system composed of such has more moving parts than monolithic systems, and requires the automation, self-healing and monitoring capabilities of modern technology stacks.
The team structures and development practices needed for a modern services architecture align well with agile development practices. Clear ownership of each service capabilities and technical architecture is essential to maintain a portfolio of cohesive, loosely coupled services.
Capability 6 Dev/Test/Ops Automation Management
A major cause of friction, delay and errors in software delivery is manual work. To clear the path for improvements in speed for delivery of features and defect fixes, ambiguous and error-prone manual processes need to be replaced as much as possible with automation.
Some components of this capability are:
•	Automated discovery of all software dependencies
•	Automated comparison of software dependencies with established version standards
•	Automated comparison of software dependencies with known security vulnerabilities
•	Automated builds with static analysis and unit, security, integration and regression testing
•	Stress testing for capacity and for resilience in the face of infrastructure problems
•	Clean (no PII), fit for purpose, isolated test data
•	Behavior-Driven testing
•	Software-Defined Infrastructure
•	Environment parity (no material difference between dev, testing, production, etc.)
•	Automated deployment of software and dependencies
Capability 7: Continuous Delivery
Continuous delivery extends agile development by making release-ready candidates at any development milestone. Continuous delivery requires the ability to deploy new versions with no downtime or insignificant downtime. Modern technology stacks bring that capability. Continuous delivery is only possible with test and deployment automation.

Capability 8: Safe Packaging
Packaging releases in stable containers reduces risk and friction in the development value chain. Technologies such as Docker, Rocket and others are making it easier to package services into immutable containers as part of the automated build process. These containers carry the service with all of its dependencies. Making the development, test and productions alike by using these containers removes many manual intervention steps that introduce errors and slow down the delivery process
Container-based deployment can be accomplished on traditional technology stacks, but benefits greatly from the improved automation found in modern stacks. Services deployed this way can be deployed and managed at scale in a cloud-hosted environment. Stable container packaging at an enterprise scale requires automation for it to be done reliably and at a reasonable cost.
Capability 9: Adaptive Infrastructure Management
Modern technology stacks have been built to adapt to changes in load, failures in the networks or data centers, and upgrades to components. These environments provide facilities to adapt to host and network outages and to scale easily for peak loads. To take advantage of these facilities, the organization will need to select the technologies for the stack, develop new skills and modify some processes in both the development and shared services organizations.
Capability 10: Infrastructure Transparency
A key to managing our services in production effectively is to have relevant, precise and clear information that is available and timely to the support people who can make the best use of it. Some components of this capability include
•	Service level agreements that include transparent to operational performance information
•	Infrastructure that will integrate and collate the data centrally
•	Services that are designed to be monitored and respond to health checks in a consistent and reliable way
•	Analytic tools and dashboards for interpreting the data
Cloud-based technology stacks integrate the metrics and logging of deployed services to provide insight into the operational characteristics of the platform. Such environments provide the data needed to understand the health and operational characteristics of the environment and to inform provisioning and scaling decisions.
