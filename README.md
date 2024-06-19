
        Testing Project for website Noriel


The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application
Application under test: Noriel website
Tools used: Jira, Zephyr Squad.

Functional specifications:

The below stories was created in Jira and describes the functional specifications of the "
Racoviță_Elena_Corina_ST1 “ module, for which the final project is performed upon.
 



Here you can find the release that was created for this project:
 
1.Testing process

The test process was performed based on the standard test process as described below.

1.1Test planning

The Test Plan is designed to describe all details of testing for all the modules from the JPetStore Demo application.
The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan. The test plan that was created for this project can be found here 
 


1.1.1. Roles asigned to the project and persons allocated

Andy Sinpetrean – Product Owner 
Dan Silaghi – Business Analyst
Vasilca Onuta - QA Senior Manager 
Paula Nan  – Scrum Master
Corina Racovita- QA Software Tester

1.1.2 Entry criteria defined

Creating entry criteria for the Noriel website involves setting standards and requirements for various aspects such as user registration, content submission, and interaction. Below are the detailed entry criteria that can be defined for the Noriel website:
User Registration Criteria
Age Requirement: Users must be at least 18 years old to register.
Valid Email Address: A valid email address must be provided for account verification.
Unique Username: The username must be unique and not contain any offensive or inappropriate language.
Strong Password: Passwords must meet complexity requirements (e.g., at least 8 characters, including one uppercase letter, one number, and one special character).
Personal Information: Users must provide accurate personal information including name, date of birth, and contact details.
Content Submission Criteria
Original Content: All submitted content must be original and not plagiarized.
Relevance: Content must be relevant to the themes and topics covered by the Noriel website.
Quality Standards: Submissions must meet quality standards in terms of grammar, coherence, and informative value.
No Offensive Content: Content must not contain offensive, abusive, or discriminatory language.
Proper Attribution: Any quoted or referenced material must be properly attributed to its original source.)

1.1.3 Exit criteria defined

Defining exit criteria for the Noriel website involves setting specific, measurable, and achievable goals that must be met before considering the project or website phase complete. These criteria ensure that the website meets the required standards and is ready for launch or further stages of development. Here are some comprehensive exit criteria that could be applied to the Noriel website:
Functional Criteria
•	Feature Completion:
All planned features and functionalities are fully implemented and tested.
No critical bugs or issues remain unresolved in the implemented features.
•	Usability Testing:
The website has passed usability tests with end users, ensuring ease of navigation and user satisfaction.
Feedback from usability tests has been addressed and integrated.
•	Compatibility:

The website is compatible with all major browsers (Chrome, Firefox, Safari, Edge) and operating systems (Windows, macOS, iOS, Android).
The website is fully responsive and functions correctly on different devices (desktop, tablet, mobile).
Performance Criteria
•	Load Time: - Page load times meet industry standards, ideally under 3 seconds for the main pages.
•	Stress Testing: - The website has passed stress tests, confirming it can handle expected traffic loads without performance degradation.
•	SEO Optimization: - The website is optimized for search engines, with relevant meta tags, alt texts, and a clear sitemap.
Security Criteria
•	Security Audits: - The website has undergone security audits and all critical vulnerabilities have been addressed. -  HTTPS is fully implemented, and data protection measures are in place.
•	User Data Protection: - The website complies with GDPR and other relevant data protection regulations. - Proper encryption and security measures are in place for user data.
Content Criteria
•	Content Accuracy: - All content, including product descriptions, images, and other textual information, is accurate and up to date. - Legal disclaimers and privacy policies are clearly stated and accessible.
•	Localization: - The website content is appropriately localized for different regions, if applicable.

Compliance Criteria
•	Accessibility: - The website meets WCAG 2.1 standards to ensure it is accessible to users with disabilities.
•	Legal Compliance: - The website complies with all relevant legal requirements, including e-commerce regulations, consumer protection laws, and intellectual property rights.
Administrative Criteria
•	Documentation: - All necessary documentation for the website, including user guides, technical documentation, and support materials, is complete.
•	Training: - Staff and administrators have been adequately trained to manage and update the website.
Testing and Approval
•	Quality Assurance (QA): - The website has passed comprehensive QA testing, including unit, integration, system, and acceptance tests.
•	Stakeholder Approval: - The website has been reviewed and approved by all key stakeholders, including project managers, business owners, and other relevant parties.
Backup and Recovery
•	Backup: - Regular backup systems are in place and tested to ensure data can be restored in case of loss.
•	Disaster Recovery Plan: - A disaster recovery plan is documented and tested to ensure the website can be quickly restored after a significant outage.
Final Review
•	Launch Readiness: - A final review meeting has been conducted, confirming that all exit criteria have been met and the website is ready for launch.
By meeting these exit criteria, the Noriel website can ensure a high-quality, secure, and user-friendly experience for its visitors.
1.1.4 Test scope

Tests in scope:

Functional Testing
Homepage
•	Verify that the homepage loads correctly and quickly.
•	Check all main sections (e.g., featured products, banners, promotions) are displayed properly.
•	Ensure all links (e.g., to product categories, promotions) are functional.
Product Search
•	Test the search functionality with different keywords.
•	Validate that search results are accurate and relevant.
•	Check filters and sorting options (e.g., price, popularity, ratings) work as expected.
Product Pages
•	Verify product details (name, price, description, images) are displayed correctly.
•	Ensure the "Add to Cart" functionality works.
•	Test product variant selections (e.g., size, color).
Shopping Cart
•	Add multiple products to the cart and verify correct totals.
•	Test updating quantities and removing items.
•	Ensure the cart is preserved across sessions.
•	Checkout Process

User Account
•	Test registration and login processes.
•	Verify account management functionalities (e.g., updating profile, changing password).

Tests not in scope:

Operating Systems
•	Verify functionality on different operating systems (Windows, macOS, iOS, Android).
Language Support
•	Ensure the website supports multiple languages correctly.
•	Verify translations and localizations are accurate.
Regional Settings
•	Test regional settings such as currency, date formats, and address formats.

1.1.5 Risks detected
Project risks:
Technical Risks
•	Software Bugs and Glitches
Risk: Bugs and glitches can lead to a poor user experience, potentially driving customers away.
Mitigation: Implement thorough testing phases including unit, integration, and user acceptance testing (UAT). Employ automated testing tools and have a clear bug tracking and resolution process.
•	Security Vulnerabilities
Risk: Exposure to cyber-attacks, such as data breaches or DDoS attacks, could compromise customer data and damage the brand’s reputation.
Mitigation: Utilize robust security practices such as SSL encryption, regular security audits, and compliance with industry standards (e.g., GDPR for data protection). Implement firewalls and intrusion detection/prevention systems.
•	Scalability Issues
Risk: The website might not handle high traffic volumes effectively, especially during peak times (e.g., holiday seasons).
Mitigation: Design the architecture with scalability in mind, using cloud services that can automatically scale resources. Load testing and performance optimization should be part of the development process.
Operational Risks
•	Project Management Failures
Risk: Poor project management can lead to missed deadlines, cost overruns, and scope creep.
Mitigation: Adopt agile project management methodologies, ensure clear communication channels, and set realistic timelines and budgets. Regularly update stakeholders and adjust plans as necessary.
•	Third-Party Dependency Failures
Risk: Reliance on third-party services (e.g., payment gateways, hosting providers) could result in outages or performance issues if those services fail.
Mitigation: Choose reliable third-party vendors with strong SLAs, and have contingency plans or backup providers in place.
•	Data Loss or Corruption
Risk: Data could be lost or corrupted due to hardware failures, software bugs, or human error.
Mitigation: Implement regular data backups, both on-site and off-site. Use data validation and error-checking mechanisms to prevent and detect corruption.
Strategic Risks
•	Market Competition
Risk: The competitive landscape may change, with new competitors entering the market or existing ones enhancing their offerings.
Mitigation: Conduct regular market analysis and be prepared to adapt the website and its features to stay competitive. Innovate and offer unique value propositions.
•	Changing Customer Preferences
Risk: Customer preferences and behaviors may change, making the website's design or functionality obsolete.
Mitigation: Keep abreast of industry trends and customer feedback. Incorporate flexibility into the design to allow for quick updates and iterations.
•	Regulatory Changes
Risk: New laws and regulations (e.g., changes in e-commerce regulations, privacy laws) could impact website operations.
Mitigation: Stay informed about regulatory changes and ensure compliance through regular audits and updates to the website’s legal policies and features.
Financial Risks
•	Budget Overruns
Risk: The project might exceed the budget, impacting overall financial health.
Mitigation: Conduct detailed cost estimations and maintain a contingency fund. Monitor expenses closely and make adjustments as needed.
•	Return on Investment (ROI) Concerns
Risk: The website might not generate the expected revenue, affecting ROI.
Mitigation: Conduct thorough market research and create a solid business plan. Implement analytics to track performance and adjust strategies to improve revenue generation.
Product risks:
Safety and Compliance Risks
•	Choking Hazards: Toys with small parts pose significant choking risks for children under three years old. It is crucial that products are appropriately labeled with age recommendations and warnings about small parts to prevent choking incidents (U.S. Consumer Product Safety Commission) (Safe Kids Worldwide).
•	Chemical Safety: The presence of harmful chemicals in toys is a critical concern. The latest EU Toy Safety Regulation emphasizes stricter controls on carcinogenic, mutagenic, and reprotoxic substances, as well as endocrine disruptors and inhalation allergens (Taylor Wessing). Ensuring that toys comply with these regulations is vital for protecting children from toxic exposure.
•	Physical Hazards: Sharp edges, loose parts, and potential strangulation hazards from toys like swings and slides need regular inspection and maintenance. This includes checking for wear and ensuring that all parts are secure and safe for use (RoSPA).

•	Fire and Electrical Hazards: Toys that are electrical or have battery components must meet stringent safety standards to prevent fire risks. It’s important to only purchase toys that have the CE mark, indicating compliance with European safety standards (RoSPA).

Best Practices for Toy Safety
•	Purchase from Reputable Sources: Buying toys from reputable retailers ensures higher compliance with safety standards. Look for safety certifications like the CE mark or the British Toy and Hobby Association's Lion Mark, which indicate adherence to rigorous safety criteria (RoSPA).
•	Age Appropriateness: Always choose toys that are suitable for the child’s age. Follow the age recommendations provided on toy packaging to avoid risks associated with inappropriate use (Safe Kids Worldwide).
•	Supervision: Adult supervision is essential, especially for younger children. This helps prevent accidents and ensures that toys are used correctly and safely (Safe Kids Worldwide) (RoSPA).
•	Regular Checks: Frequently inspect toys for damage or wear that could lead to hazards. Repair or dispose of any toys that are broken or have loose parts to maintain a safe play environment (RoSPA).
1.1.6 Evaluating entry criteria

The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.

1.2 Test Monitoring and Control

Implementing test monitoring and control for the Noriel website involves several key steps and best practices.
To begin with, we defined the objectives and the scope.
•	Key metrics are identified: key performance indicators for the site, such as load time, uptime, transaction success rate and user experience metrics.
•	Goals are set: clear goal for these metrics, such as a maximum page load time of 2 seconds, 99.9% uptime, etc.
•	Scope is established: decide which pages and functionalities require monitoring. These typically include the home page, product pages, checkout process, and user account pages.
Set up automated tests
•	Functional Testing: Writing test cases to verify the basic functionality of the website and ensuring that these tests cover all critical user interactions such as product navigation, adding items to cart, and completing checkout.
•	Performance testing: Load and stress tests are performed to understand how the site performs under different traffic levels.
Analyze data and generate reports
•	Regular reports: Daily, weekly or monthly reports summarizing key metrics and performance trends. These reports should highlight any issues, their impact and the actions taken to resolve them.
•	Create dashboards: Dashboards using tools like Grafana or Tableau to visualize performance metrics and trends over time. This helps to make quick decisions and identify areas that need improvement.
 Control and improvement measures
•	Incident Management: A process is established for incident management, including detection, diagnosis, resolution and post-incident review. We use this information to prevent future occurrences.
•	Continuous improvement: Testing and monitoring processes are regularly reviewed to identify areas for improvement. Update test cases, improve monitoring configurations, and optimize performance based on findings.
•	Stakeholder Communication: Maintains clear communication with stakeholders about site performance, issues and improvements. Reports and dashboards are used to provide transparency.
Security and compliance
•	Security Testing: Periodic security testing, such as vulnerability scans and penetration tests, is performed to identify and mitigate security risks.
 The feedback loop
•	User feedback: We collect feedback from users through surveys, feedback forms or direct communication and use this feedback to improve the user experience and to address potential bottlenecks.
•	Team Feedback: Team members are encouraged to provide feedback on the monitoring and control processes and this input is used to refine and improve the approach.

Test status report
 

 
 




1.3 Test Analysis
The testing process will be executed based on the application requirements

The following test conditions were found:
 
 

1.4 Test Design

Functional test cases were created in Zephyr Squad based on the analysis of the specifications. The test cases can be accessed here 
 
1.5 Test Implementation

The following elements are needed to be ready before the test execution phase begins

1.6. Test Execution

Test cases are executed on the created test Cycle summary: 
 
 

Bugs have been created based on the failed tests. The complete bug reports can be found here: 
 
The following is a summary of the bugs that have been found 
 
Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.

1.7 Test Completion 

As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team




The traceability matrix was generated and can be found here: 
 
The final report shows that a number 2 tests have failed of a total of 10.
A number of 2 total bugs were found, from which the priority are high .
The overall conclusion for the Noriel website test is that it aims to provide an optimal online shopping experience by ensuring that the website is functional, user-friendly and visually appealing. It should perform well in different conditions, provide comprehensive and accurate content, and maintain high security standards.
In addition, the 10 tests show that it should facilitate a smooth purchase process, provide efficient customer support and be accessible and visible to all users. Also, although the bugs found are of high importance, they do not prevent the launch of the application.
