# Solemates-Complete-Project
# Solmates-Complete-Project-
 


FINAL YEAR PROJECT REPORT
SoleMates: A Mobile E-commerce Application for Branded Shoes and Clothing

A report submitted in partial fulfilment of the requirements for the degree of 
B.Sc. (Hons) in Information Technology at Asia Pacific University of 
Technology and Innovation.


Submitted To
Infomax College of IT and Management
 
By
ANKIT ACHARYA 
NPI000140
CT049-6-3-PRJ

Supervised by: Mr. Nabaraj Adhikari
2025 
 

 
 
	
DECLARATION



I, Ankit Acharya , hereby declare that this submission is my own work and that, to the best of my knowledge and belief, it contains no material previously published or written by another person or material which has been accepted for the award of any other degree or diploma of the university or other institute of higher learning, except where due acknowledgment has been made in the text.


Place: Pokhara-33, Kaski                                          Signature: 	


Date: 26 May 2025                                                 Name: Ankit Acharya

 
DECLARATION OF THESIS CONFIDENTIALITY

Author’s full name: Ankit Acharya
IC No./Passport No: 46-02-76-00796
Thesis/Project title: SoleMates: A Mobile E-commerce Application for Branded Shoes and Clothing

I declare that this thesis is classified as:
☐ CONFIDENTIAL
☐ RESTRICTED
☐ OPEN ACCESS
I acknowledge that Asia Pacific University of Technology & Innovation (APU) reserves the right as follows:
1.	The Thesis is the property of Asia Pacific University of Technology & Innovation (APU).
2.	The Library of Asia Pacific University of Technology & Innovation (APU) has the right to make copies for the purpose of research only.
3.	The Library has the right to make copies of the thesis for academic exchange.

Author’s Signature: ...………………….
Date: 26 May 2025
Supervisor’s Name: Mr. Nabaraj Adhikari
Date: 26 May 2025
Signature: ……………....

 
CERTIFICATE OF APPROVAL



The undersigned certify that they have read and recommended to the Department of Computer Science for acceptance, final year report submitted by Ankit Acharya (APU Roll No. NPI000140) in partial fulfillment for the degree of Bachelor of Science in Computer Science and Information Technology.





…………………………
Mr. Nabaraj Adhikari
Supervisor
Infomax College of IT & 
Management 






 
SUPERVISOR’S RECOMMENDATION



I hereby recommend that the final year report on the Solemates (Mobile E-commerce platform) web application prepared under my supervision by Ankit Acharya (APU Roll No. NPI000140) is accepted as fulfilling the partial requirement for the degree of Bachelor of Science in Information Technology. In my best knowledge, this is an original work in computer science by him.


…………………
Mr. Nabaraj Adhikari
Final Year Supervisor
Infomax College of IT & Management
 
Library Form
  
 





  
 
Acknowledgement
I would like to express my deepest gratitude to my supervisor, Mr. Nabaraj Adhikari, for his invaluable guidance, patience, and encouragement throughout this project. His expertise and feedback were instrumental in shaping the direction and success of SoleMates.
I am also thankful to my lecturers, Mr. Anup Adhikari and the faculty at Asia Pacific University of Technology & Innovation, for providing me with the knowledge and skills in web development, database management, and design patterns that were crucial for this project.
Special thanks to the survey participants and beta testers whose feedback helped refine the platform. Their insights were vital in creating a user-centric application.
Lastly, I extend my appreciation to my family and friends for their unwavering support and motivation during this journey.
Ankit Acharya

 
Abstract
This report outlines the development of SoleMates, a mobile e-commerce application designed to provide a seamless and sustainable shopping experience for branded shoes and clothing in Nepal. The project addresses key challenges in the Nepalese e-commerce landscape, such as limited access to sustainable fashion, poor user experience, and trust issues. SoleMates leverages advanced technologies, including Flutter for the frontend and Node.js with MongoDB for the backend, to create a user-friendly and scalable platform. The report covers the project's objectives, methodology, system design, and implementation, emphasizing ethical consumption and responsible production aligned with Sustainable Development Goal (SDG) 12. Through comprehensive research, testing, and iterative development, SoleMates aims to transform online retail in Nepal by offering a reliable, eco-conscious, and innovative shopping solution.
Keywords: mobile e-commerce application, Nepalese e-commerce landscape, Flutter, Node.js, MongoDB, scalable platform, comprehensive research, testing, iterative development
SDG Goal 12: Responsible Consumption and Production

 
 
Chapter 1 -Introduction
1.1 Introduction
The rapid development of mobile technology and digital infrastructure has transformed shopping in Nepal. With better access to the internet and smartphones, consumers are more reliant on online shopping sites for their purchasing needs. However, local companies do not have a strong online presence, and existing e-commerce sites are not providing simple, user-friendly, and secure experiences that meet the needs of Nepalese consumers. SoleMates mobile app was created as a solution to such issues, providing system-based technology for branded shoe and fashion e-commerce in Nepal. (Ngudup, 2005). 

SoleMates is not a concept but a complete, designed and developed e-commerce system with a focus on easy navigation, real-time updates of order status, personalized services, and eco-friendly product offerings. The system is developed using Flutter for cross-platform mobile app development and Node.js and MongoDB for scalable backend development. This paper is concerned with designing, developing, and deploying SoleMates as a live application, including system features, user flows, architectural design, backend services, and testing procedures that ensure performance and usability. More than research-based, this paper embodies a true software development lifecycle (SDLC) application that creates an e-commerce system to address the present digital retail needs in Nepal. 
1.2 Problem Statement
While online shopping is gaining popularity in Nepal, existing e-commerce websites do not provide the seamless, secure, and sustainable online shopping experience that local consumers seek. Several obstacles lie between local businesses' success and consumer satisfaction:
•	Lack of a User-Friendly Mobile Interface: The majority of websites offer cluttered designs and poor mobile optimization, resulting in annoying navigation and abandons checkout processes—discouraging users from completing purchases. The issue of not having a responsive and intuitive mobile interface to boost user engagement is addressed by frontend development using Flutter.
•	Lack of Scalable and Secure Backend Infrastructure: Existing systems typically do not have secure authentication, proper product management, and efficient order processing. This restricts platform performance and user confidence. A proper backend with Node.js and MongoDB is needed to facilitate secure data processing and system scalability.
•	Poor Administrative Control and Order Management: Most websites lack proper tools for the admins to control products, monitor orders, or interpret user behaviors. Thus, operating the platform becomes challenging. This can be fixed by having a separate admin module that offers total control of inventory, discounts, analytics, and customer relationships.
•	Inadequate Secure and Flexible Payment Integration: Customers are presented with untrustworthy and limited payment options, and this results in cart abandonment. Multiple and secure payment gateways must be integrated to facilitate smooth and trusted transactions. Inadequate Support for Sustainable and Ethical Shopping Local consumers are now more keen on eco-friendly products, yet green brands are not supported or highlighted by most platforms. A list of sustainable and ethically sourced products thus needs to be curated to meet this need and position the platform differently. 
By solving the issues above, SoleMates will create a comprehensive, secure, and scalable mobile e-commerce application system for the fashion industry of Nepal, well aligning with the goals of developing, designing, and deploying a user- and admin-based application.  
1.3 Project Aim
To design, develop, and implement a scalable and user-friendly mobile e-commerce application for branded clothing and shoes in Nepal with focus on seamless user interaction, robust backend support, and eco-friendly shopping assistance.
1.4 Objectives
•	To design and prototype an easily accessible user interface on mobile with Flutter using responsiveness to user responses.
•	To implement backend processes using Node.js and MongoDB to allow secure user authentication, real-time product handling, and secure order processing.
•	To develop admin and user modules like inventory control, order management, customer service, and promotional tools.
•	To ensure payment gateways are implemented and secure transaction processing is handled.
•	To test the system as a whole using unit testing, integration testing, and user acceptance testing for admin and client sides.
•	To develop an operational version of the system to fit branded and sustainable product listings in the Nepali market.
1.5 Scope
The project scope of SoleMates includes the whole development life cycle of a mobile e-commerce app from a system plan and requirement gathering to deployment and testing. It involves frontend development using Flutter and backend development using Node.js and MongoDB. Application includes admin and user modules with functionality such as user registration/login, browsing, cart management, order processing, promotional management, and customer reviews. System also includes secure payment gateways and has product filters based on sustainability. The scope does not include research-based studies extensively but is only devoted to implementing the system practically along with feature delivery.  
1.6 Potential Benefits
Tangible Benefits
•	Authentic Products Access: Customers are able to purchase high-quality branded shoes and clothing comfortably from top brands, which are guaranteed in quality.
•	Internacional Reach: The website will enable global sales to a wide international customer base, thereby increasing the prospect of branded products being sold in wider markets.
•	Safe Transactions: Secure payment portals will ensure financial information is secure, enhancing consumer confidence and, as a result, possible higher rates of conversion.
•	Effective Customer Support: There would be effective customer care support mechanism for timely redressal of customers' queries and enablement of repeat purchase satisfaction.
•	Data-Driven Decision Making: Admin panel will be used for analytics to gain insight about customer behavior and sales trends to constantly work on optimizing product offering and marketing strategies.
•	Greater Brand Awareness: Strategic marketing will enhance promotion of the SoleMates platform and its featured brands, resulting in overall traffic and sales boost.
Intangible Benefits
•	Sustainable Shopping: SoleMates promotes eco-friendly and ethically produced products, thus promoting sustainable consumerism and brands with sustainable production procedures, further supporting positively giving back to the environment.
•	Easy-to-Use Experience: The clean design and easy-to-navigate interface will make the experience of the shoppers better while purchasing, which will result in customer satisfaction.
•	Learning Resources: Giving details on sustainability and ethical consumption informs the customer how to make informed choices for a conscious shopping culture overall.
•	Social Network: The platform will be able to provide community-based forums to users by adding customer review and forums to gain loyalty and affinity towards the company.
•	Good Brand Reputation: As a sustainable and ethical company, SoleMates will possess a good brand reputation that will attract socially responsible consumers.
Target user
1.	Shoppers
2.	Admin
Deliverables
Modules for Shoppers	Modules for Admin
Account Management Module	User Account Management Module
Product Browsing Module	Rewards Management Module
Wishlist and Cart Management Module	Dashboard and Analytics Module
Promotions and Discounts Module	Content Management Module
Checkout Module	Product Quality Oversight Module
Order Management Module	Financial Management Module
Review and Feedback Module	Security Management Module
Profile Management Module	Settings and Configurations Module
Table 1: Deliverables of Solemates
 
Chapter 2 – Literature Review
2.1 Domain Study
1. Consumer Behavior and Trends in E-commerce 
The e-commerce landscape has evolved radically since the advent of advances in internet usage, mobile technology, and buying patterns. Consumers nowadays expect convenience, personalization, and speed. Increases in mobile commerce and digital wallets indicate an appetite for frictionless digital payments. Customers are motivated by simplicity, fast loading, minimal navigation, and secure sites. Carts are abandoned on a massive scale because of poor user experience and surprise fees.
Social media has become a key driver of consumer behavior. Platforms like Facebook, Instagram, and TikTok integrate shopping capability into the user interface, blurring the line between content usage and product discovery. Influencer advertising and live engagement (e.g., live shopping events) boost brand visibility and trust.
Security and trust play a crucial role in consumer purchase decisions. Inadequate strong authentication, clear return terms, or peer reviews deters purchase. Also, demographic profiles influence online shopping patterns. Younger generations embrace mobile-first sites and customization, whereas older ones may prioritize trust and simplicity. Income levels also determine the requirements of discounts and value-add functionality. Overall, the consumer preference is to have a smooth, secure, and personalized purchase experience.
2. Authenticity and Branding in E-commerce 
Authenticity and brand identity are the e-commerce differentiators. People outside product description search for alignment with their values-based brands. Successful online brands invest in storytelling, social causes, and transparency. Active involvement, consistent messaging, and promise delivery define authentic branding.
A robust brand image, backed by good word-of-mouth from customers and quality certifications, goes a long way in influencing purchasing decisions. It is revealed through studies that a majority of consumers rely on online comments as much as their friends' suggestions. Conversely, poor reviews and counterfeiting undermine trust. Online stores need to adopt anti-counterfeit measures and openness in supply chain and logistics.
Brand loyalty is also crucial in e-commerce. Repeat business is made easy by loyal customers, and they act as brand ambassadors. Customer loyalty programs, prompt customer service, and customized experiences are essential to maintain consumer trust. For SoleMates, authenticity in product descriptions, open communication of the brand, and proactive engagement with users is the way to long-term success.

3. Sustainability and Ethical Consumption 
Sustainability is no longer a niche hobby; it has become the underlying desire of consumers in this modern era. Ethical consumption involves choosing products based on their impact on the environment and society. In fashion, it involves green material, ethical labor conditions, and transparent supply chain practices. SoleMates is all about these by selling items only from businesses that produce sustainably.
Today’s sustainable fashion styles focus on biodegradable materials, recycled materials, and environmentally friendly production. Transparency in supply chains is also important to consumers, with brands providing explanations of their source strategies and working conditions. Clothing rental, second-hand sales, and circular fashion are also gaining momentum.
Shoppers are becoming better informed and are willing to pay more for sustainable products. Labels and certifications (e.g., Fair Trade, GOTS) guide purchasing behavior as shoppers seek proof of ethical claims of content. Social media are important to spreading the word regarding sustainability, and corporate social responsibility (CSR) activities enhance brand loyalty and reputation.
For SoleMates, integrating sustainability across product offerings and operations not only caters to an increasingly large number of environmentally aware consumers but also sets the platform apart. The app's focus on conscious brands, educative product descriptions, and customer awareness promotes a shift in mindset toward conscious consumerism in Nepal.

4. Technological Innovations in E-commerce 
Technology is at the heart of e-commerce transformation. Innovations in mobile apps, AI, machine learning, blockchain, and cloud services are redefining how online shopping works. For example, mobile-first platforms allow users to shop anywhere, anytime. More than half of global e-commerce traffic now comes from mobile devices, necessitating responsive, intuitive designs.
Artificial intelligence and machine learning enable customer-tailored product recommendations, dynamic pricing, and customer service automation through chatbots. These technologies enhance the user and business efficiency. Blockchain technology is gaining traction for supply-chain transparency, anti-counterfeit protections, and ethical sourcing.
Secure payment integration is another crucial consideration. Consumers want fast, secure, and shielded payment pathways. Support for digital wallet, card, and mobile banking allows for greater inclusivity. For server-side systems, cloud hosting and microservices architecture yield greater scalability and simpler maintenance.
SoleMates leverages these innovations through its tech stack: Flutter for cross-mobile app development, Node.js for backend APIs, and MongoDB for non-relational data storage. The platform's system design includes features of real-time tracking, admin analytics, and customer feedback loops. These technology decisions facilitate rapid performance, modular expansion, and long-term system maintainability.
Blending these innovations, SoleMates transcends being an e-commerce app but a progressive platform that stays abreast of new technology trends and user needs in Nepal.
 

 

 
2.2.7 Summary
“Within Nepal's fast-evolving e-commerce ecosystem, Daraz, OkDam, and SastoDeal have been able to create quite an impact on the trend of consumer behavior and expectations. Of these, Daraz is still the largest e-commerce player in the country, offering the widest selection of products through its easy-to-use website. The issues with this website include inconsistent customer service and the chance of selling counterfeit products. OkDam presents itself as an affordable, yet variant option, building strong brand awareness and probably lacking a few features. On the other hand, SastoDeal focuses on more affordable options and supporting local sellers with a focus on cash-on-delivery and resultant limitation of payment flexibility for customers. Together, they represent opportunities and gaps that can be leveraged by a new player like SoleMates.
In the existing system, SoleMates shall target the identified gaps within those existing systems. For example, local features-developing local languages and culturally adapted marketing-increase relatability and build consumer trust. Giving regard to superior customer service via responsive support channels and live chat contributes to building user interactions. Moreover, the adoption of innovative technologies, such as AI-driven personalized recommendations, will offer personalized shopping experiences that increase satisfaction and retention. The ability to offer a range of payment options, including mobile wallets and microfinance solutions, will be important in accommodating very diverse consumer needs, especially in rural areas. Again, engaging marketing strategies that promote local artisans will help build community ties and support local economies. With efficient logistics partnerships that ensure timely deliveries, SoleMates will have effectively overcome the most harassed pain points in the present e-commerce landscape and will emerge as a relatable and customer-centric platform, catering to the unique needs of Nepalese consumers.
 
2.3 Technical Research 
The technical foundation of SoleMates was established through careful selection of development tools, frameworks, programming languages, and database technologies suitable for building a scalable, secure, and user-friendly mobile e-commerce platform. This section outlines the research conducted to choose the best technical stack to meet the system’s functional and performance requirements.
 
Figure 5: Flutter Logo
The frontend of the application was developed using Flutter, an open-source UI toolkit by Google. Flutter was selected because it enables cross-platform development using a single codebase, which significantly reduces development time and ensures consistent user experience across both Android and iOS devices. Its wide library support, pre-built widgets, and reactive architecture made it an ideal choice for building modern, visually appealing user interfaces.
 
Figure 6: Logo of Node.js
For the backend, i chose Node.js, a JavaScript runtime environment known for its speed and scalability. Node.js is event-driven and non-blocking, making it suitable for handling multiple user requests simultaneously essential for real-time e-commerce platforms. Along with Node.js, the Express.js framework was used to structure the backend APIs efficiently, enabling smooth communication between the frontend and the server.
 
Figure 7: Logo of MongoDB
MongoDB, a NoSQL document-oriented database, was used for data storage. MongoDB's schema flexibility allowed the team to quickly adapt to evolving requirements without major structural changes. Its JSON-like format (BSON) integrates naturally with Node.js and supports fast queries, which is vital for handling product data, user information, order histories, and more. The decision to use MongoDB was also influenced by its scalability and support for large datasets.
The development environment included Visual Studio Code (VS Code) as the preferred Integrated Development Environment (IDE) for both frontend and backend development. VS Code offers rich plugin support, intelligent code completion, Git integration, and an overall developer-friendly experience.
For state management in Flutter, the Provider package was used, allowing smooth management of UI states, user sessions, cart data, and real-time updates across screens. It was chosen for its simplicity, performance, and ease of integration with Flutter’s widget tree.
Postman was used for API testing to verify the functionality of backend routes during development. It allowed the team to simulate HTTP requests and validate responses, ensuring that the endpoints were reliable and handled errors properly.
Additionally, Git and GitHub were used for version control and team collaboration, ensuring consistent updates, rollback capabilities, and issue tracking.
Through this technical stack—Flutter, Node.js, MongoDB, Provider, and supporting tools—the SoleMates system achieved a high-performing, flexible, and maintainable architecture suitable for modern mobile e-commerce applications. The decisions made through this research phase directly influenced the reliability, scalability, and usability of the final product.
 
Chapter -3 Methodology
3.1 System Development Methodology
For successful design and implementation of the SoleMates mobile e-commerce application, the Kanban process was adopted as the system development methodology. Kanban, a light-weight, flexible, and Agile system, was chosen due to its potential to accommodate fresh requirements, visualize tasks, and effectively manage requirements changes throughout the development lifecycle.
As opposed to more sequential models such as Waterfall—having a formal, step-by-step approach—Kanban supports continuous and real-time delivery. This allowed the team to monitor all development tasks on a board that included columns like "To Do," "In Progress," and "Done," which allowed for smoother workflow and better coordination.
The cycle of development was broken down into individual but flexible phases: planning, analysis, design, development, testing, and deployment. In every phase, the activities were allocated to the Kanban board and prioritized based on difficulty and urgency. An example would be user interface designing for Flutter and API endpoint adding in Node.js being taken care of as separate cards with clear-cut dedicated development without losing the overall vision.
In system development, participants like frontend, backend, and database developers may pick tasks from the board based on expertise and availability. This self-driven model of work fostered ownership and fast delivery. In addition, the system permitted frequent updates and iterations. If a bug or a design error was discovered, it was recorded immediately and fixed in the subsequent cycle without disrupting the entire process.
Kanban also ensured good communication between developers and stakeholders. Progress was tracked visually, and blockers were made apparent early. For example, issues like data rendering inconsistency in Flutter or slow API responses were easily spotted and addressed through collaborative debugging.
During development, utmost importance was given to shipping high-priority features earliest. These included user registration, product browsing, cart management, admin dashboard functionality, and secure payment gateways. UI/UX and backend logic were iteratively refactored based on feedback from the supervisors and test users.

In addition, the Kanban methodology supported parallel development of user and admin modules. This created a platform for frontend and backend aspects to develop side by side without delay due to dependencies. Completed modules were then shipped to the testing phase, where unit and integration testing ensured functionality and stability.
Overall, Kanban was an extremely effective methodology for the SoleMates project. It emphasized monitoring of tasks through visuals, continuous improvement, and team flexibility, which ensured that the application was delivered within deadlines, quality specifications, and according to the requirements of users during the system development process.
 
3.2 Data Gathering Design
“Data gathering is the pivotal point on which SoleMates depends to offer customized experiences for customers who shop online for shoes. The design of a data gathering instrument must guarantee that insights are relevant and accurate and can be obtained in such a manner as to underpin key decision-making strategies and enhance customer satisfaction. Based on Saunders et al. (2016), this involves the development of a specific data gathering instrument design and includes an overall purpose statement, target respondents for the survey, and methods of gathering data.
3.2.1 Survey Purpose
The purpose of this survey for SoleMates will be to assess consumer preferences, behaviors, and satisfaction levels regarding their shoe shopping experiences. SoleMates will utilize such information on the factors influencing purchasing decisions to tailor its offerings for target markets. The survey seeks to identify key trends in consumer behavior, such as preferred styles, price sensitivity, and shopping habits (Kotler & Keller, 2016). Additionally, it aims to assess customer satisfaction with existing products and services, gathering feedback on areas for improvement. The insights from this survey will help SoleMates arrive at data-driven decisions with respect to product development, marketing strategies, and customer engagement initiatives toward a personalized shopping experience.
3.2.2 Target respondents
The targeted respondents for the SoleMates online survey involve active online purchase habits of footwear. This involves a wide demography of respondents across age groups, sex, and incomes to ensure clarity of consumer preference. Key segments include Millennials and Generation Z, who are known for their heavy reliance on online shopping and social media influences (Smith, 2019). Additionally, SoleMates will target individuals who have previously purchased footwear online, as their insights will provide valuable information on real customer experiences. This will help SoleMates to outline trends and preferences in different consumer segments and consequently shape its offerings to best meet various needs and optimize overall satisfaction.
3.2.3 Selected data gathering technique
The online questionnaire is the chosen data gathering technique for the survey to be conducted at SoleMates. It is chosen because of the efficiency and speed with which it reaches a large pool of respondents (Dillman et al., 2014). Quantitative and qualitative questions will be used within the online questionnaire to capture not only the numerical data from the respondents but also their deeper level feedback. The multiple-choice question types would help quantify their preferences and levels of satisfaction, while open-ended ones give insight into customer experiences and suggestions for improvement. The online format makes it easy to distribute at multiple touchpoints, including over social media, email newsletters, and the SoleMates website, thus increasing chances of participation. By using this data collection technique, SoleMates hopes to glean robust insights from which strategic decisions are informed and that will enable the company to enhance customers' experiences.”
3.2.4 Survey structure
 
 
Table 5: Table section of survey questions
“This survey consists of 39 questions divided into six sections: General Information, Shopping Experience, Product Preferences, Platform Features, Sustainability, and Customer Service & Trust. The sections, General Information, Shopping Experience, and Product Preferences, need to be answered by the participants, whereas the section covering Platform Features, Sustainability, and Customer Service & Trust must focus on specified experiences and opinions related to SoleMates. The survey ends with a free-text section for additional comments or suggestions that capture all perspectives comprehensively.”
 
3.2.5 Question’s objective
 
 
 
 
Table 6: Table of survey's question
 
3.2 Respondent demographic profile of Survey
 Table 7: Table of respondent demographic profile
 
3.3.1 Survey Summary
“The Nepali e-commerce is in its growth stage but encompasses a lot of drawbacks, such as the absence of local business entities in online platforms, less availability of sustainable products, and poor user experiences on the existing platforms. Other local platforms like Daraz and SastoDeal provide wide ranges of products but do not address concerns of transparency, trust, and sustainability. Counterfeit goods, limited return policies, and unclear product descriptions further undermine consumer confidence.
Convenience, affordability, and trust are key components in consumer online shopping. Cash-on-delivery remains the preferred mode of payment due to concerns about online transaction security. Social media and peer reviews also greatly influence purchase decisions, further solidifying the need to build trust and engage with consumers online.
The analysis brought out gaps in user experience, ethical practices, and accessibility-areas where platforms can improve their offerings through better transparency, eco-conscious strategy, and tailored offerings. These findings provide actionable insights into enhancing Nepal's e-commerce landscape while keeping consumer demands aligned with the Sustainable Development Goals.”
 
Chapter 4 – Project Specification
4.1 Introduction
This chapter will discuss the requirement discovery to show how the requirements are derived. Besides, the functional and non-functional requirements that build up the system will be listed. Lastly, a use case model will be produced with the use case diagram and respective use case descriptions.
4.2 Use Case
A use case is a narration of how the user will use a system in an effort to achieve some goals. It helps in the identification of the functional requirements of the system through explaining different situations where the system is used. Use cases are important because they provide a clear statement of the user's needs, help in designing the system, and ensure that all critical functions are addressed when developing the system.
4.2.1 Use Case Diagram
The use case diagram of the Solemates application provides a comprehensive overview of the behavior of the system and its two primary actors, the Client (end-user) and the Admin (system administrator). The diagram is a visual illustration of functionalities presented to each actor and how they interact with various features of the application. The Client actor is the typical consumer who mainly uses the platform for shopping and managing accounts. On the admin side, the Admin actor is in charge of the overall functioning and content of the Solemates platform. 
In short, this use case diagram encapsulates the entire functional scenery of the Solemates platform. It accurately describes the roles and activities of Clients and Admins, illustrating how they interact with the system in order to accomplish their desired results. Not only does the diagram capture the major functionality required for flawless shopper shopping, but also the robust administrative controls required for effective platform operation. Such a visual representation forms a key foundation for both system design and documentation, being found to be clear and coherent with all parties during the course of development.

 
Figure 8: Use case diagram of Solemates
 
4.2.2 Use Case description
4.4.2.1 Admin Use Cases
Use Case 1: Manage Posters
Use Case Name	Manage Posters
Actors	Admin
Description	This use case allows the Admin to manage promotional posters by adding, editing, or deleting them from the system. Posters are displayed to customers on various pages for marketing purposes.
Preconditions	Admin is logged into the system and has navigated to the "Poster Management" module.
Postconditions	Posters are successfully added, edited, or deleted, and the changes are reflected in the front-end display.
Basic Flow	1. Admin logs into the system.
2. Admin navigates to the "Poster Management" section.
3. Admin searches for existing posters.
4. Admin chooses to add, edit, or delete a poster.
5. If adding or editing:
  a. Admin uploads or replaces the poster image.
  b. Admin enters or updates the poster details (title, URL, display duration, etc.).
  c. Admin saves the changes.
6. If deleting:
  a. Admin selects the poster to delete.
  b. System prompts for confirmation.
  c. Admin confirms the deletion.
7. System processes the request and updates the poster list.
8. Admin sees success message.
Alternate Flows	- If the poster image is in an invalid format, system shows an error.
- If poster title is missing, system prompts to enter required fields.
- If poster deletion is canceled, system returns to the poster list.
Exceptions	- System error while uploading or saving poster.
- Network issues during operation.
Table 8: Manage poster use cases
Use Case 2: Manage Categories
Use Case Name	Manage Categories
Actors	Admin
Description	This use case allows the Admin to manage the product categories by adding, editing, or deleting categories that organize products for easier browsing by customers.
Preconditions	Admin is logged into the system and has navigated to the "Category Management" module.
Postconditions	Categories are added, edited, or deleted, and the updates reflect in the product catalog structure.
Basic Flow	1. Admin logs into the system.
2. Admin navigates to the "Category Management" section.
3. Admin searches or browses existing categories.
4. Admin chooses to add, edit, or delete a category.
5. If adding or editing:
  a. Admin uploads or updates the category icon.
  b. Admin enters or updates category details (name, description, display order).
  c. Admin saves the changes.
6. If deleting:
  a. Admin selects the category to delete.
  b. System prompts for confirmation and warns about impact (e.g., products linked to the category).
  c. Admin confirms deletion.
7. System processes the changes and updates the category list.
8. Admin sees success message.
Alternate Flows	- If category name already exists, system alerts the admin.
- If deleting a category linked with products, system may require reassignment or warn of consequences.
- If deletion is canceled, no action is taken.
Exceptions	- System error during category save or delete.
- Network failure during the process.
- Category does not exist anymore due to concurrent deletion.
Table 9: Manage category use case
Use Case 3: Manage Subcategories
Use Case Name	Manage Subcategories
Actors	Admin
Description	This use case allows the Admin to manage product subcategories under specific parent categories by adding, editing, or deleting them. Subcategories help refine product categorization for better user experience.
Preconditions	Admin is logged into the system and has navigated to the "Subcategory Management" module.
Postconditions	Subcategories are successfully added, edited, or deleted, and the changes are reflected in the catalog hierarchy.
Basic Flow	1. Admin logs into the system.
2. Admin navigates to the "Subcategory Management" section.
3. Admin filters subcategories by parent category if needed.
4. Admin searches or browses existing subcategories.
5. Admin chooses to add, edit, or delete a subcategory.
6. If adding or editing:
  a. Admin enters or updates subcategory details (name, description, display order).
  b. Admin selects parent category if adding a new subcategory.
  c. Admin saves the changes.
7. If deleting:
  a. Admin selects the subcategory to delete.
  b. System prompts for confirmation and warns about linked products.
  c. Admin confirms deletion.
8. System processes the changes and updates the subcategory list.
9. Admin sees success message.
Alternate Flows	- If subcategory name already exists under the same category, system prompts an error.
- If deleting a subcategory with linked products, system may prompt to reassign or warn about impact.
- If deletion is canceled, the system returns to subcategory list.
Exceptions	- System error during subcategory creation, update, or deletion.
- Network failure during operation.
- Subcategory does not exist anymore due to concurrent actions.
Table 10: Manage subcategory use cases
Use Case 4: Manage Products
Use Case Name	Manage Products
Actors	Admin
Description	This use case allows the Admin to manage the product catalog by adding new products, editing existing product details, or removing products from the store. This ensures that only up-to-date and available products are visible to customers.
Preconditions	Admin is logged into the system and has navigated to the "Product Management" module.
Postconditions	Products are successfully added, updated, or deleted, and changes reflect in the product catalog and customer view.
Basic Flow	1. Admin logs into the system.
2. Admin navigates to the "Product Management" section.
3. Admin searches, filters, or browses existing products.
4. Admin chooses to add, edit, or delete a product.
5. If adding or editing:
  a. Admin fills or updates product details (name, description, price, SKU, stock, images, variants, category, subcategory).
  b. Admin sets product visibility and availability.
  c. Admin saves the changes.
6. If deleting:
  a. Admin selects the product to delete.
  b. System prompts for confirmation and warns about removing from the storefront.
  c. Admin confirms deletion.
7. System processes and updates the product list.
8. Admin sees success message.
Alternate Flows	- If product name or SKU already exists, system shows validation error.
- If stock quantity is set as negative, system prevents saving and alerts admin.
- If deletion is canceled, system returns to product list.
Exceptions	- System error while saving product.
- Network issues during action.
- Product no longer exists (e.g., deleted by another admin).
Table 11: Manage products use case
Use Case 5: Manage Orders
Use Case Name	Manage Orders
Actors	Admin
Description	This use case allows the Admin to manage customer orders by viewing, updating statuses, handling returns or cancellations, and ensuring timely processing and fulfillment of orders.
Preconditions	Admin is logged into the system and has navigated to the "Order Management" module.
Postconditions	Orders are successfully updated, statuses changed, or actions like cancel or refund are performed and customers are notified accordingly.
Basic Flow	1. Admin logs into the system.
2. Admin navigates to the "Order Management" section.
3. Admin searches, filters, or views orders by status (pending, shipped, delivered, canceled, etc.).
4. Admin selects an order to view details.
5. Admin performs actions:
  a. Update order status (e.g., from "Pending" to "Shipped").
  b. Approve or reject cancellation or return requests.
  c. Issue refunds if applicable.
  d. Add internal notes if needed.
6. System updates the order details and status.
7. System notifies the customer of the changes.
8. Admin sees success message.
Alternate Flows	- If order is already completed or canceled, system prevents further status updates.
- If refund amount exceeds order amount, system alerts admin.
- If admin cancels an order, system prompts for reason.
Exceptions	- System error during order status update.
- Network failure during process.
- Order does not exist anymore due to concurrent actions.
Table 12: Manage orders use case
 
Use Case 6: View Dashboard Insights
Use Case Name	View Dashboard Insights
Actors	Admin
Description	This use case allows the admin to view real-time business insights, including product, order, and customer metrics, helping in decision-making.
Preconditions	Admin is logged into the system with the required privileges.
Postconditions	Dashboard data is displayed with updated insights based on filters if applied.
Basic Flow	1. Admin logs into the system.
2. Admin navigates to the "Dashboard".
3. System displays overall insights including product and order summaries.
4. Admin applies filters if needed (date range, category, etc.).
5. Admin reviews various insights (e.g., total orders, pending orders, stock alerts, etc.).
Alternate Flows	- No data to display (e.g., for new stores or date range with no data), system informs the admin.
- Admin applies incorrect filters, system resets to default.
Exceptions	- System fails to load insights due to server errors.
- Network issues while fetching real-time data.
Table 13: View Dashboard Insights use case
Use Case 7: Send Notifications
Use Case Name	Send Notifications
Actors	Admin
Description	This use case allows the admin to compose and send notifications to users about offers, updates, or alerts.
Preconditions	Admin is logged into the system with notification privileges.
Postconditions	Notification is sent to the selected audience and delivery stats are tracked.
Basic Flow	1. Admin logs into the system.
2. Navigates to the "Notifications" section.
3. Composes a notification (title, description, image URL).
4. Selects target audience (all users, specific segment, etc.).
5. Clicks on 'Send Notification'.
6. System sends notification and shows confirmation with delivery stats.
Alternate Flows	- Admin saves the notification as a draft for later.
- Admin schedules the notification for a specific time.
Exceptions	- System fails to send notification.
- Invalid audience selection.
- Network failure during sending.
Table 14: Send Notification use case
Use Case 8: Create Coupons
Use Case Name	Create Coupons
Actors	Admin
Description	This use case allows the admin to create discount coupons for promotional purposes.
Preconditions	Admin is logged into the system with coupon management rights.
Postconditions	Coupon is created and made available for users.
Basic Flow	1. Admin logs into the system.
2. Navigates to "Coupon Creation".
3. Enters coupon details (code, title, discount type, etc.).
4. Selects applicable products, categories, or users.
5. Sets expiry date and other conditions.
6. Clicks on 'Save'.
7. System saves the coupon and confirms creation.
Alternate Flows	- Admin previews the coupon before saving.
- Admin duplicates an existing coupon to create a new one with minor changes.
Exceptions	- System error while saving coupon.
- Duplicate coupon code.
- Invalid coupon conditions (e.g., expiry date in the past).

 
Use Case 9: Manage Coupons
Use Case Name	Manage Coupons
Actors	Admin
Description	This use case allows the admin to edit or delete existing coupons.
Preconditions	Admin is logged into the system with coupon management rights.
Postconditions	Coupon is updated or deleted successfully.
Basic Flow	1. Admin logs into the system.
2. Navigates to "Coupon Management".
3. Searches and filters coupons.
4. Selects a coupon to edit or delete.
5. If editing, updates details and saves changes.
6. If deleting, confirms deletion.
7. System confirms the update or deletion.
Alternate Flows	- Admin deactivates a coupon instead of deleting it.
- Admin exports a list of coupons for reporting.
Exceptions	- Coupon already expired or used, certain edits may not be allowed.
- System error while updating or deleting coupon.
Table 15: Manage coupons use cases
Use Case 10: Manage Brands
Use Case Name	Manage Brands
Actors	Admin
Description	This use case allows the admin to add, edit, or delete brands in the system.
Preconditions	Admin is logged into the system with brand management access.
Postconditions	Brand is added, updated, or deleted successfully.
Basic Flow	1. Admin logs into the system.
2. Navigates to "Brand Management".
3. Searches for existing brands.
4. Selects to add, edit, or delete a brand.
5. If adding, enters brand details and saves.
6. If editing, updates details and saves.
7. If deleting, confirms deletion.
8. System reflects the changes.
Alternate Flows	- Admin merges two brands.
- Admin deactivates a brand instead of deleting.
Exceptions	- Brand associated with active products cannot be deleted.
- System error while updating brands.
Table 16: Manage Brands use cases
Use Case 11: Manage Variants
Use Case Name	Manage Variants
Actors	Admin
Description	This use case allows the admin to manage product variant types (e.g., size, color) and their options.
Preconditions	Admin is logged into the system with variant management rights.
Postconditions	Variant type or options are added, updated, or deleted.
Basic Flow	1. Admin logs into the system.
2. Navigates to "Variant Management".
3. Searches existing variant types.
4. Selects to add, edit, or delete variant type/options.
5. If adding, enters variant type and options.
6. If editing, updates options and saves.
7. If deleting, confirms deletion.
8. System reflects the changes.
Alternate Flows	- Admin reorders variant options (e.g., display color options in specific order).
Exceptions	- Variant type linked with active products cannot be deleted.
- System fails to save due to validation errors.
Table 17: Manage variants use case
 
4.4.2.2 Client Use Cases
Use Case 1: Browse Products
Use Case Name	Browse Products
Actors	Client (User)
Description	This use case allows the user to browse the product catalog, explore different categories, and navigate through the available products using pagination or scrolling.
Preconditions	User has accessed the e-commerce website or app.
Postconditions	User can see products and categories, and optionally proceed to view details, filter, or search.
Basic Flow	1. User opens the product catalog.
2. System displays categories and featured products.
3. User selects a category or scrolls through the catalog.
4. System loads and displays products accordingly.
5. User can continue browsing or move to other actions (like viewing details, filtering, etc.).
Alternate Flows	- If no products are available, system shows a relevant message.
- User can switch between categories or apply filters anytime.
Exceptions	- Network error while loading products.
- Backend error fetching categories.
Table 18: Browse Products use case
Use Case 2: View Product Details
Use Case Name	View Product Details
Actors	Client (User)
Description	This use case allows the user to view detailed information about a selected product, including variants, specifications, stock status, and pricing.
Preconditions	User has accessed the product list or searched for a product.
Postconditions	User views product details and can take further actions like adding to cart, adding to favourites, or returning to browse.
Basic Flow	1.	User selects a product from the listing.
2.	System fetches and displays product details including images, description, price, variants, stock status.
3.	User can select variants if available.
4.	User can proceed to add to cart, add to favourites, or navigate back.
Alternate Flows	- User adds the product to favourites.
- User adds the product to the cart after selecting a variant.
- If the product is out of stock, system shows "Out of Stock".
Exceptions	- Product not found or removed from system.
- Network issues while loading details.
Table 19: View Product details use case
Use Case 3: Add Product to Cart
Use Case Name	Add Product to Cart
Actors	Client (User)
Description	This use case allows the user to add a product to the shopping cart after selecting necessary options like size, color, or variant.
Preconditions	User has viewed product details.
Product is in stock.
Postconditions	Product is added to the user's cart.
Basic Flow	1. User clicks "Add to Cart".
2. System checks if all required selections (like variant, size) are made.
3. System checks product stock availability.
4. If available, system adds product to the cart.
5. System shows confirmation to the user.
Alternate Flows	- If stock is not available, system shows an "Out of Stock" message.
- User can change variant and try again.
Exceptions	- System fails to add to cart due to backend error.
- User session expired.
Table 20: Add products to cart use case
Use Case 4: Apply Coupon
Use Case Name	Apply Coupon
Actors	Client (User)
Description	This use case allows the user to apply a valid coupon code at the cart or checkout page to avail discounts or offers.
Preconditions	User has items in the cart.
User is on the cart or checkout page.
Postconditions	Coupon is applied, and discount is reflected in the cart total.
Basic Flow	1. User enters coupon code in the provided input field.
2. System validates the coupon code.
3. If valid, the discount is calculated and applied to the cart total.
4. System shows updated pricing with discount and coupon applied confirmation.
Alternate Flows	- If coupon is invalid or expired, system shows an error message and allows the user to re-enter.
- If coupon usage limit is exceeded, system informs the user.
Exceptions	- System unable to validate coupon due to network or backend issues.
- Coupon service unavailable.
Table 21: Apply coupon use case
Use Case 5: Place Order
Use Case Name	Place Order
Actors	Client (User)
Description	This use case allows the user to finalize and place the order after reviewing the cart, applying coupons, and entering shipping and payment details.
Preconditions	User has added products to the cart.
User is logged in (if required).
Postconditions	Order is placed, and confirmation with order ID is shown to the user.
Basic Flow	1. User proceeds to checkout.
2. User enters/selects shipping address.
3. User selects payment method (COD, Wallet, etc.).
4. System validates order details, stock availability, and payment success (if applicable).
5. If all validations pass, system places the order.
6. System displays order confirmation with order ID, estimated delivery time, and sends confirmation email/notification.
Alternate Flows	- If stock is insufficient, system informs the user.
- If payment fails, user is prompted to retry or change payment method.
- User cancels the checkout process.
Exceptions	- System error during order placement.
- Payment gateway timeout or error.
- Invalid shipping details entered by user.
Table 22: Place order use case
Use Case 6: Track Order
Use Case Name	Track Order
Actors	Client (User)
Description	This use case allows the user to track their order status and shipment details after the order has been placed.
Preconditions	User has placed an order.
User is logged in (if account is required for tracking).
Postconditions	User can see current status, estimated delivery date, and shipment progress.
Basic Flow	1. User navigates to "My Orders" or "Track Order" section.
2. User selects the order they want to track.
3. System fetches the current status of the order (Pending, Processed, Shipped, Delivered, Cancelled).
4. System shows detailed tracking information, shipment progress, and expected delivery date.
5. User can refresh or revisit the page to get the latest updates.
Alternate Flows	- If order is cancelled, system shows order cancellation message.
- If tracking info is delayed, system shows "Tracking info not available yet".
Exceptions	- System error fetching order status.
- Order ID not found or invalid.
- Network issues.
Table 23: Track Order use case
Use Case 7: Manage Account
Use Case Name	Manage Account
Actors	Client (User)
Description	This use case allows the user to manage and update their personal information, change password, view address book, and manage saved preferences.
Preconditions	User is logged into their account.
Postconditions	User’s account information is updated successfully.
Basic Flow	1. User navigates to "Account Settings" or "My Account".
2. User views and edits profile information like name, email, phone number, etc.
3. User may change password by entering old and new password.
4. User can add, update, or remove saved addresses.
5. User can manage saved payment methods or preferences if available.
6. System updates the information and shows confirmation.
Alternate Flows	- If incorrect old password is provided, system shows an error.
- If invalid data is entered, system prompts the user to correct it.
Exceptions	- System error during data update.
- Network issues.
- Unauthorized access if session expired.
Table 24: Manage account use case
 
Use Case 8: Login
Use Case Name	Login
Actors	Client (User)
Description	This use case allows the user to log into their existing account using their registered email/phone number and password.
Preconditions	User has an existing account.
Postconditions	User is successfully logged in and redirected to the dashboard or home page.
Basic Flow	1. User navigates to the login page.
2. User enters valid email/phone and password.
3. System validates the credentials.
4. On success, user is logged in and session is created.
5. User is redirected to the appropriate page.
Alternate Flows	- If wrong credentials entered, system shows an error message.
- User clicks on 'Forgot Password' and is redirected to reset flow.
Exceptions	- System error while authenticating.
- Network issues.
- Account locked due to multiple failed attempts.
Table 25: Login use case
Use Case 9: Signup
Use Case Name	Signup
Actors	Client (User)
Description	This use case allows new users to create an account by providing required details such as name, email, phone number, and password.
Preconditions	User is not already registered.
Postconditions	New user account is created, and user is logged in automatically or prompted to login.
Basic Flow	1. User navigates to the signup page.
2. User enters name, email, phone number, and password.
3. System validates the entered details (email format, password strength, etc.).
4. If all inputs are valid, system creates the account.
5. System sends verification email or OTP (if applicable).
6. User is either logged in automatically or after verifying email/OTP.
Alternate Flows	- If email already exists, system shows error.
- User does not complete verification and account remains inactive.
Exceptions	- System error during account creation.
- Network issues.
- Verification service down.
Table 26: Signup use case
Use Case 10: Search Product
Use Case Name	Search Product
Actors	Client (User)
Description	This use case allows the user to search for specific products using keywords or product names from the search bar.
Preconditions	User has access to the application or website.
Postconditions	System displays the list of matching products based on the search input.
Basic Flow	1. User navigates to the search bar.
2. User enters keywords or product name.
3. System processes the search query.
4. System displays the matching products.
5. User can click on any product to view its details.
Alternate Flows	- If no matching products are found, system shows 'No products found' message.
- User can refine the search term and repeat the process.
Exceptions	- System error while searching.
- Network issues.
Table 27: Search products use case
 
Use Case 11: Filter Products
Use Case Name	Filter Products
Actors	Client (User)
Description	This use case allows the user to filter the product listings based on various attributes like category, price range, brand, etc.
Preconditions	User is on the product listing or search result page.
Postconditions	The system displays filtered products matching the selected criteria.
Basic Flow	1. User selects one or more filter options (category, price, brand, etc.).
2. System applies the selected filters.
3. System refreshes and displays the products matching the filters.
4. Users can remove or modify the filters as needed.
Alternate Flows	- If no products match the applied filters, system shows 'No products found'.
- User resets filters to view all products again.
Exceptions	- System error while applying filters.
- Network issues.
Table 28: Filter products use case
 
Chapter 5 – System Design
5.1 System Architecture Design
 
Table 29: System architecture design of solemates
The e-commerce application is designed with a client-server architecture, where the frontend is designed by Flutter and the backend is implemented using Node.js and Express.js. The frontend is maintained using mobile and web platforms and adopts two different panels: an Admin Panel and a Client Panel. Admin Panel allows administrators to control users, orders, products, and reports, while the Client Panel allows users to browse products, manage a shopping cart, order products, and track their deliveries.
Frontend state management is realized via the Provider package, enabling sharing of data between widgets and screens with ease, for example, user authentication status, cart contents, and order history. The application communicates with the backend via secure RESTful APIs over HTTPS.
The backend, developed with Node.js and Express.js, handles all business logic, API routes, and database operations. Authentication is secure with JSON Web Tokens (JWT), and role-based access control distinguishes between admin and client users. The backend talks to a MongoDB database to save and retrieve all information required, including user profiles, product listings, order details, and transaction history.
For payment processing, the system has both local and global options available: credit/debit card payments are handled via Esewa or Credit Card, while local transactions in Nepal are handled through eSewa. On successful payment, the backend updates the relevant order and transaction records in MongoDB appropriately.
OneSignal drives push notifications, which are embedded within the Flutter app to offer real-time messages such as order confirmations, delivery status, and promotional messages. The backend initiates these notifications based on user activity or order events.
This architecture guarantees scalability, maintainability, and security. Decoupling between frontend, backend, and third-party services like OneSignal and payment gateways allows for development flexibility and painless future upgrades. Overall, the system guarantees a solid and responsive shopping experience for both customers and administrators.
 
5.2 Entity-Relationship Diagram
An Entity-Relationship Diagram (ERD) is a robust graphical notation used in database modeling to model the data structure and the relationship between different parts of a system. ERDs form the foundation for designing well-organized and effective databases. ERDs model entities (e.g., people, places, things, or events within a domain), attributes (attributes or characteristics of the entities), and relationships (the manner the entities are related to each other). ERDs not only enable database designers to visualize the logical form of data but also enable better communication with analysts, developers, and stakeholders during the development phase.
A well-designed ERD promotes:
•	Data integrity and consistency
•	Successful database structure
•	Better system functionality understanding
•	Less redundancy and data handling anomalies
Developing an ERD is traditionally divided into three distinct modeling stages: Conceptual ERD, Logical ERD, and Physical ERD. Each model plays a specific role in progressing from the data's general top-level view towards an implementable database schema.
5.2.1 Conceptual ERD
 
Figure 9: Conceptual ERD One
Conceptual ERD is the most abstracted level of the database structure. It does not touch on technical matters such as data types or primary keys but only addresses the identification of the main entities and the interdependencies among them. The conceptual ERD is meant to present a clean and simple picture of the system structure with a view to helping stakeholders, including non-technical individuals, understand the domain and its data needs. This model is particularly useful during the initial phases of database design and requirement collection.

5.2.2 Logical ERD
 
Figure 10: Logical ERD One
While the conceptual model serves as the foundation, the Logical ERD adds further structure and content to the database design. It contains the key technical aspects of primary keys (PK) and foreign keys (FK), which distinguish unique records and ensure referential integrity across tables. Moreover, logical ERD has normalized forms of entities decided in the conceptual model. Normalization prevents redundancy in data and renders the database insensitive to frequent update anomalies such as insertion, deletion, and modification errors. With the use of normalization rules, the logical ERD promotes data integrity and consistency across the system.
5.2.3 Physical ERD
 
Figure 11: Physical ERD One
Physical ERD is the most implementation-specific and detailed view of the database. It translates the logical and abstract models to a blueprint that adheres to the effective constraints and capabilities of the Database Management System (DBMS) to be implemented. This model defines data types, lengths, and constraints for every column so that it adheres to the target DBMS's particular requirements. It also avoids reserved keywords and follows naming conventions to prevent syntax errors and improve maintainability. By incorporating all technical specifications, the physical ERD serves as a foundation document for the implementation of the database schema.
5.2.4 Data Dictionary
The data dictionary is a set of metadata that records the structure and data of the fields and documents in the MongoDB database. It dictates the structure of collections and how to interpret each field of data in collections. The data dictionary for this system is designed in harmony with MongoDB's schema-less, flexible document model. Instead of the static data types of classical relational databases, MongoDB uses BSON types like String, Number, Boolean, Date, and Array to store data. This accommodates dynamic and nested data structures that are suitable for the e-commerce system. The data dictionary specifies the expected fields and types of fields for the major collections such as users, products, orders, and transactions with explicit definitions to ensure that consistent data can be stored and retrieved across the application.

Table: User
Field Name	Description	Data Type	PK	FK
_id	Unique identifier	ObjectId	✓	
name	User's full name	String		
password	User's password (hashed)	String		
createdAt	Account creation date	Date		
updatedAt	Last update timestamp	Date		
Table 30: User Table

Table: Category
Field Name	Description	Data Type	PK	FK
_id	Unique identifier	ObjectId	✓	
name	Category name	String		
image	Image URL for the category	String		
Table 31: Category table
Table: SubCategory
Field Name	Description	Data Type	PK	FK
_id	Unique identifier	ObjectId	✓	
name	Subcategory name	String		
categoryId	Reference to parent category	ObjectId		✓
Table 32: Subcategory table

Table: Brand
Field Name	Description	Data Type	PK	FK
_id	Unique identifier	ObjectId	✓	
name	Brand name	String		
subcategoryId	Associated subcategory	ObjectId		✓
Table 33: Brand table

Table: VariantType
Field Name	Description	Data Type	PK	FK
_id	Unique identifier	ObjectId	✓	
name	Variant type name	String		
type	Type of variant	String		
Table 34: VariantType table
Table: Variant
Field Name	Description	Data Type	PK	FK
_id	Unique identifier	ObjectId	✓	
name	Variant name	String		
variantTypeId	Associated variant type	ObjectId		✓
Table 35: Variant table
Table: Product
Field Name	Description	Data Type	PK	FK
_id	Unique identifier	ObjectId	✓	
name	Product name	String		
description	Product description	String		
quantity	Available quantity	Number		
price	Regular price	Number		
offerPrice	Discounted price	Number		
proCategoryId	Associated category	ObjectId		✓
proSubCategoryId	Associated subcategory	ObjectId		✓
proBrandId	Associated brand	ObjectId		✓
proVariantTypeId	Associated variant type	ObjectId		✓
proVariantId	List of variant identifiers	[String]		
images	Array of product images	Array		
Table 36: Product table

Table: Order
Field Name	Description	Data Type	PK	FK
_id	Unique identifier	ObjectId	✓	
userID	User who placed the order	ObjectId		✓
orderDate	Date of order placement	Date		
orderStatus	Current status of the order	String		
items	List of ordered items	Array		
totalPrice	Total price before discounts	Number		
shippingAddress	Shipping address details	Object		
paymentMethod	Payment method used	String		
couponCode	Applied coupon	ObjectId		✓
orderTotal	Breakdown of order totals	Object		
trackingUrl	URL for tracking the shipment	String		
Table 37: Order table

Table: Coupon
Field Name	Description	Data Type	PK	FK
_id	Unique identifier	ObjectId	✓	
couponCode	Unique coupon code	String		
discountType	Type of discount ('fixed' or 'percentage')	String		
discountAmount	Amount of discount	Number		
minimumPurchaseAmount	Minimum purchase amount to apply coupon	Number		
endDate	Expiration date of the coupon	Date		
status	Current status ('active' or 'inactive')	String		
applicableCategory	Category the coupon applies to	ObjectId		✓
applicableSubCategory	Subcategory the coupon applies to	ObjectId		✓
applicableProduct	Product the coupon applies to	ObjectId		✓
Table 38: Coupon table
Table: Notification
Field Name	Description	Data Type	PK	FK
_id	Unique identifier	ObjectId	✓	
notificationId	Unique notification ID	String		
title	Notification title	String		
description	Notification content	String		
imageUrl	URL of the notification image	String		
Table 39: Notification table
Table: Poster
Field Name	Description	Data Type	PK	FK
_id	Unique identifier	ObjectId	✓	
posterName	Name of the poster	String		
imageUrl	URL of the poster image	String		
Table 40: Poster table
 
5.3 Activity Diagram
5.3.1 Admin Side
1. Manage Posters
 
Figure 12: Activity Diagram of Manage Posters 
 
2. Manage Categories
 
Figure 13: Activity Diagram of Manage Category
 
3. Manage Products
 
Figure 14: Activity Diagram of Manage Product
 
4. Manage Orders
 
Figure 15: Activity Diagram of Manage Order
5.3.2 Client Side
1. Browse Products
 
Figure 16: Activity Diagram of browse product

2. View Product Details
 
Figure 17: Activity Diagram of View product detail

 
3. Place Order
 
Figure 18: Activity Diagram of Place Order

 
4. Signup
 
Figure 19: Activity Diagram of Signup

 
5.4 Sequence Diagram
5.4.1 Admin Side
1. Manage Posters - Sequence Diagram
 
Figure 20: Sequence diagram of Manage posters
 
2. Manage Categories
 
Figure 21: Sequence diagram of manage category
 
4. Manage Products
 
Figure 22: Sequence diagram of manage products
 
5. Manage Orders
 
Figure 23: Sequence diagram of Manage Order
 
6. View Dashboard Insights
 
Figure 24: Sequence diagram of view dashboard insights
7. Send Notifications
 
Figure 25: Sequence diagram of send notification
 
5.4.2 Client Side
1. Browse Products
 
Figure 26 : Sequence diagram of browse products
 
2. View Product Details
 
Figure 27: Sequence diagram of view products details
 
3. Add Product to Cart
 
Figure 28: Sequence diagram of Add products to cart
 
4. Place Order
 
Figure 29: Sequence diagram of Place order
 
5. Manage Account
 
Figure 30: Sequence diagram of Manage account

 
5.5 Screen Prototype Design
5.5.1 Admin Side
5.5.1.1 Admin Dashboard
 
Figure 31: Wireframe of Admin Dashboard
The Admin Dashboard presents a comprehensive overview with multiple functional modules in a clean, organized layout. A left-side navigation menu provides quick access to all admin sections (Shop, Products, Database, Orders etc.). The main content area features several key widgets: Product Management with quick actions, Stock Alerts for inventory monitoring, and Order Statistics with visual status breakdowns. The dashboard efficiently uses cards, progress indicators and clean typography to present complex backend data in an easily digestible format. Strategic use of color in status indicators (like stock alerts) helps administrators quickly identify areas requiring attention. This wireframe successfully balances information density with usability for power users, providing all essential e-commerce management tools at a glance.  
5.5.1.2 Admin Category Management
 
Figure 32: Wireframe of Admin Category Management
This specialized management interface allows administrators to handle product categories through a dual-panel design. The left panel maintains consistent admin navigation, while the right workspace displays existing categories (Electronics, Fashion, Books) with their creation dates. A prominent "ADD CATEGORY" button invites expansion of the category tree. The layout uses clean typography and subtle visual separators to distinguish between different categories while maintaining an overall cohesive look. The inclusion of timestamps ("Added on") provides valuable metadata for inventory management. This wireframe exemplifies effective admin interface design a complex functionality presented through simple, intuitive controls that even novice administrators could operate efficiently.  
5.5.1.3 Admin Orders Dashboard
 
Figure 33: Wireframe of Admin Orders Dashboard
This image provides administrators with a centralized hub for monitoring and processing customer orders. The interface maintains consistent left-side navigation while focusing on two core functions: order management and performance analytics. Administrators can filter orders, access detailed views, and export data through prominent action buttons like "View Analytics" and "Export Orders." The order listing presents essential information in a clean, scrollable format with expandable details for quick access. A dedicated statistics panel displays key metrics including total orders (100), pending (30), and shipped (70) orders, offering immediate business insights through clear visual indicators. This design successfully combines comprehensive functionality with intuitive navigation, enabling efficient order processing while maintaining the admin interface's cohesive visual language.  
5.5.1.4 Admin Brands Management
 
Figure 34: Wireframe of Admin Brands Management
This screen offers sophisticated tools for maintaining brand identity across the product catalog. Its three-section layout includes brand management controls, a visual gallery of current brands, and a detailed editing form. Administrators can add new brands through a prominent CTA, with options to filter existing brands by category. Each brand entry displays its logo and associated category in clean, editable cards. The creation/editing form provides fields for brand names, category assignment, and logo uploads, complete with cancel/submit options. This interface excels in visual organization, making brand management intuitive through logo previews, clear category associations, and responsive form design that adapts to both creation and modification workflows.  
5.5.1.5 Admin Variant Types
 
Figure 35: Wireframe of Admin Variant Types
This screen establishes the foundation for managing product variations, though its wireframe shows less detail than other screens. The interface appears designed to create and organize variant categories like size, color, and material, with functionality to define specific options within each type. This system would enable precise inventory tracking at the variant level while ensuring accurate frontend representation. The implied hierarchy suggests administrators could establish parent variant types and populate them with specific values, crucial for stores offering configurable products. While minimalist, this wireframe indicates a flexible structure capable of accommodating diverse product types through customizable variant options.  
5.5.2 Client Side
5.5.2.1 Login Screen
 
Figure 36: Wireframe of Login Screen
The Login Screen is designed with a minimalist and user-friendly approach, ensuring a seamless authentication experience. It features two clearly labeled input fields Email and Password each with placeholder text to guide users. The design follows standard mobile UI conventions, with appropriate spacing and typography for readability. Two prominent call-to-action buttons, "SIGNUP" and "LOGIN," are placed at the bottom, allowing users to either log in or navigate to the registration screen effortlessly. The absence of unnecessary distractions ensures that users can focus on entering their credentials quickly. The wireframe adheres to modern mobile app design principles, prioritizing simplicity, accessibility, and intuitive navigation.  
5.5.2.2 Signup Screen
 
Figure 37: Wireframe of Signup Screen
The Signup Screen builds upon the simplicity of the Login Screen but includes additional fields to ensure secure account creation. Users are required to enter their Email, Password, and Confirm Password, with clear labels and placeholders to prevent errors. The UI maintains consistency with the Login Screen, featuring the same button styling and layout structure. The "LOGIN" button allows returning users to switch back easily, while the "SIGNUP" button confirms registration. The design emphasizes usability, ensuring that form validation (such as password matching) is straightforward. By keeping the interface clean and uncluttered, the wireframe ensures a frictionless onboarding experience for new users.  
5.5.2.3 Home Screen
 
Figure 38: Wireframe of Home Screen
The Home Screen serves as the central hub of the e-commerce app, offering a visually engaging and functional layout. It begins with a promotional banner to highlight deals, followed by a "Top Categories" section (e.g., Toys, Appliances) for quick navigation. The "Featured Products" section displays items in a grid format, each with an image, name, and discount percentage, making it easy for users to browse popular items. A bottom navigation bar (Home, My Orders, Favorites, Support) ensures seamless access to key app sections. The design balances aesthetics and usability, using card-based layouts, clear typography, and strategic spacing to enhance readability and engagement. This wireframe effectively guides users through the shopping experience while maintaining visual appeal.  
5.5.2.4 Category Screen
 
Figure 39: Wireframe of Category Screen
The Category Screen provides a structured and filterable view of products within a specific category (e.g., Electronics). Users can sort items by price (low to high, high to low) or ratings, and apply filters by brand or other attributes. The "Reset Filters" option ensures flexibility, while the "Apply" button confirms selections. Product listings are displayed in a clean card layout, each showing a discount tag, product name, and price for quick scanning. The header includes the current time and category title for context. This wireframe emphasizes discoverability and ease of use, allowing users to refine their search efficiently while maintaining a visually organized interface.  
5.5.2.5 Product Screen
 
Figure 40: Wireframe of Product Screen
The Product Screen is designed to provide detailed product information in an engaging and user-friendly manner. It features a visual showcase of the product (e.g., Sony X80J) in different settings, followed by key details such as discounted price, original price, available sizes, and stock availability. User reviews are highlighted with a toggle option, and the "Add to Cart" button is prominently placed for quick action. The persistent bottom navigation bar ensures users can easily switch between app sections. The layout is structured into clear sections (Price, Sizes, Product Details), enhancing readability and decision-making. This wireframe prioritizes clarity, visual appeal, and conversion optimization, ensuring users have all the necessary information to make a purchase confidently.  
5.5.2.6 Favorites Screen
 
Figure 41: Wireframe of Favorites Screen
The Favorites Screen provides users with a personalized space to view and manage their saved products. The design features a clean, scrollable list of favorite items, each displayed in a compact card layout with key details such as product image, name, price, and discount percentage. A timestamp (e.g., "12:30") adds context for recently added items. The minimalist approach ensures quick recognition and easy access to saved products, while the visual hierarchy—with discount tags and bold pricing helps users identify deals at a glance. The absence of clutter allows for effortless browsing, reinforcing user engagement and encouraging future purchases. Persistent navigation elements maintain consistency with other app screens, ensuring seamless transitions between sections.  
5.5.2.7 My Orders Screen
 
Figure 42: Wireframe of My Orders Screen
The My Orders Screen provides users with a comprehensive overview of their purchase history in a clean, timeline-based layout. Each order is displayed as a compact card showing key details: product name(s), quantity, payment method, order date/time, and current status (e.g., Pending, Shipped). The design uses visual cues like status tags and chronological ordering to help users quickly assess their order progress. A subtle separation between different orders improves scanability, while the consistent card design maintains visual harmony. This screen effectively balances information density with readability, allowing users to track multiple orders without feeling overwhelmed. The inclusion of payment method icons adds another layer of quick reference, enhancing the overall user experience for order management.  
5.5.2.8 Update Address Screen
 
Figure 43: Wireframe of Update Address Screen
This essential utility screen features a form-based interface for managing shipping addresses, with clearly labeled input fields for all necessary components: phone number, street, city, state, postal code and country. Each field includes helpful placeholder text (e.g., "e.g., Pokhara") that serves as both guidance and formatting example. The "Update Address" button follows standard placement conventions at the bottom for natural thumb reach on mobile devices. The minimalist design eliminates all unnecessary elements, focusing user attention purely on the address entry task. Logical grouping and adequate spacing between form fields prevent errors during data entry. This wireframe demonstrates excellent form design principles that reduce user frustration in critical checkout-related interactions.  
Chapter 6 System Implementation
6.1 Introduction
The implementation of the system began with setting up the project architecture using Flutter for the frontend and a backend service integrated through REST APIs. The Flutter application was developed using the Provider package for state management, ensuring smooth interaction between the UI and underlying logic. The system’s interface was designed using reusable widgets like CompleteOrderButton, AppBarActionButton, and ProductGridView, which allowed consistent styling and efficient code reuse. Each screen was connected through a centralized navigation structure, simplifying user flow and minimizing code duplication. The API layer was responsible for fetching and sending data such as product details, user registration, and order processing, all handled with proper error and success feedback using SnackBars.
Throughout the development process, careful attention was given to maintaining clean code structure, modular design, and responsiveness across different devices. Various widgets such as ListView, GridView, and Card were utilized to build a user-friendly layout, while TextFormField and form validation ensured the integrity of user inputs. On the backend, endpoints were consumed via asynchronous functions using try-catch blocks to gracefully handle errors. The integration of frontend and backend was validated through extensive testing of each component, including API calls and navigation flows. By following these practices, the system was implemented in a structured and maintainable manner, ensuring it was both scalable and easy to debug.

6.2 Backend Implementation (Node.js & MongoDB)
6.2.1 Project Structure
The backend of the e-commerce system is developed with Express.js and Node.js, in a modular directory structure that addresses concerns and improves project organization. Critical directories such as routes, models, and public help to divide the application into concept-based part improving the codebase to be more maintainable, readable, and scalable. Using such a directory structure, developers are able to easily locate and modify specific parts of the system, reducing development complexity as the system grows.
 
Figure 44: Folder Structure of Server Side in Node.js
As shown in above figure, models work with schema data, routes work with API endpoints, and public serves static assets like images. Having such structure facilitates developers to work together easily, provides scalability for adding new modules, and reduces debugging and updates.The index.js is the central entry point where the server is initialized, middlewares are configured, and routes are attached. The .env file stores sensitive settings such as database URIs secure and safe for use across environments. The uploadFile.js module is using Multer for file uploading, ensuring uploaded images are stored in the public/uploads folder in a structured fashion. package.json and package-lock.json help in tracking dependencies and scripts for the project, ensuring package versions are synchronized. Overall, this organized and modular design supports Flutter-safe and -effective backend operations and enables easy integration with the Flutter frontend with a uniform and flexible basis for upcoming scalability and support.
 
7.2.2 Database Connection
 
Figure 45: Database Connection Code
The above diagram shows the .env file containing environment variables like the MongoDB connection string. Using environment variables allows for safe storage of sensitive information like database credentials. It also makes it easy to manage different environments (development, testing, production) by simply switching the .env file without touching the codebase.
 
Figure 46: Env File Setup
Above diagram is of the database connection block in the index.js file. This connects to MongoDB through Mongoose and the connection string in the .env file. The connection includes some basic error handling and logs successful connections, which is required for monitoring and debugging.
 
Figure 47: Backend Terminal Output
 This screenshot shows the terminal output when the Node.js server is run using Nodemon. It verifies that the server is running on port 3000 and the MongoDB database is connected successfully, which means the backend is functioning as required.
 
Figure 48: Mongoose Schema Example
This is an example of a Mongoose schema (Category.js) under the models folder. The schema defines the shape of the Category collection in MongoDB, with fields like name and image, both of which are mandatory. Schemas in Mongoose offer data integrity and validation before inserting data into the database.
7.2.3 API Endpoints Table
Brand Endpoints
Method	Route	Description	Required Fields
GET	/brands	Retrieves all brands with their associated subcategory information, sorted by subcategory. Returns success status, message, and brands data array.	None
GET	/brands/:id	Retrieves a specific brand by its ID with populated subcategory information. Returns 404 if not found.	None
POST	/brands	Creates a new brand. Validates required fields before creation.	name, subcategoryId
PUT	/brands/:id	Updates an existing brand. Returns 404 if brand not found.	name, subcategoryId
DELETE	/brands/:id	Deletes a brand only if no products reference it. Returns 400 if products exist that reference the brand.	None
Table 41: API Endpoints table of Brand
Category Endpoints
Method	Route	Description	Required Fields
GET	/categories	Retrieves all categories without any population. Returns simple array of category documents.	None
GET	/categories/:id	Gets a single category by ID. Returns 404 if category doesn't exist.	None
POST	/categories	Creates new category with optional image upload (max 5MB). Handles Multer upload errors.	name
PUT	/categories/:id	Updates category including image replacement. Validates file size and type.	name, image
DELETE	/categories/:id	Deletes category only if no subcategories or products reference it. Performs referential integrity checks.	None
Table 42: API Endpoints table of Category
Coupon Endpoints
Method	Route	Description	Required Fields
GET	/coupons	Gets all coupons with populated category, subcategory, and product references. Returns detailed coupon information.	None
GET	/coupons/:id	Retrieves single coupon by ID with all populated references. Returns 404 if coupon not found.	None
POST	/coupons	Creates new coupon.	couponCode, discountType, 
discountAmount, 
endDate, status
PUT	/coupons/:id	Updates existing coupon. Validates all required fields.	couponCode, discountType, 
discountAmount, 
endDate, status
DELETE	/coupons/:id	Deletes coupon without any referential checks. Returns 404 if coupon not found.	None
POST	/coupons/check-coupon	Validates coupon against provided product IDs and purchase amount. Checks expiration, status, and applicability.	couponCode, 
productIds, 
purchaseAmount
Table 43: API Endpoints table of  coupon
Notification Endpoints
Method	Route	Description	Required Fields
POST	/notifications/send-notification	Sends push notification via OneSignal to all users. Optional imageUrl.	title, description
GET	/notifications/track-notification/:id	Retrieves delivery statistics for a specific notification from OneSignal.	None
GET	/notifications/all-notification	Gets all stored notifications sorted by creation date (newest first).	None
DELETE	/notifications/delete-notification/:id	Deletes notification record from database. Doesn't affect OneSignal records.	None
Table 44: API Endpoints table of Notification
Order Endpoints
Method	Route	Description	Required Fields
GET	/orders	Retrieves all orders with populated user and coupon information, sorted by creation date (newest first).	None
GET	/orders/orderBy
UserId/:userId	Gets all orders for a specific user with same population as general orders endpoint.	None
GET	/orders/:id	Retrieves single order by ID with populated user and coupon data.	None
POST	/orders	Creates new order.	userID, items, 
totalPrice, 
shippingAddress,
 paymentMethod, 
orderTotal
PUT	/orders/:id	Updates order status and optional tracking URL. Primarily used for order fulfillment updates.	orderStatus
DELETE	/orders/:id	Deletes order permanently. No referential checks performed.	None
Table 45: API Endpoints table of order
Payment Endpoints
Method	Route	Description	Required Fields
POST	/payments/esewa	Creates eSewa payment intent.	email, name, address, 
amount, currency, description
POST	/payments/credit_card	Returns credit card test API key for client-side integration.	None
Table 46: API Endpoints table of payment
Poster Endpoints
Method	Route	Description	Required Fields
GET	/posters	Retrieves all posters with their image URLs. Simple unfiltered list.	None
GET	/posters/:id	Gets single poster by ID. Returns 404 if poster doesn't exist.	None
POST	/posters	Creates new poster with image upload (max 5MB).	posterName
PUT	/posters/:id	Updates poster including optional image replacement.	posterName, imageUrl
DELETE	/posters/:id	Deletes poster permanently. No referential checks performed.	None
Table 47: API Endpoints table of poster
Product Endpoints
Method	Route	Description	Required Fields
GET	/products	Retrieves all products with populated category, subcategory, brand, and variant information.	None
GET	/products/:id	Gets single product by ID with all relationships populated. Detailed product view.	None
POST	/products	Creates new product with support for multiple image uploads (up to 5 images).	name, quantity, price, 
proCategoryId, 
proSubCategoryId
PUT	/products/:id	Updates product including optional image updates. Can update any product field including variants.	None (fields to update)
DELETE	/products/:id	Deletes product permanently. No referential checks performed.	None
Table 48: API Endpoints table of product

SubCategory Endpoints
Method	Route	Description	Required Fields
GET	/subcategories	Retrieves all subcategories with populated category information, sorted by category.	None
GET	/subcategories/:id	Gets single subcategory by ID with category populated.	None
POST	/subcategories	Creates new subcategory.	name, categoryId
PUT	/subcategories/:id	Updates existing subcategory.	name, categoryId
DELETE	/subcategories/:id	Deletes subcategory only if no brands or products reference it. Strict referential checks.	None
Table 49: API Endpoints table of subcategory
User Endpoints
Method	Route	Description	Required Fields
GET	/users	Retrieves all users without any sensitive data filtering. Simple list view.	None
POST	/users/login	Authenticates user. Returns user data without password on success.	name, password
GET	/users/:id	Gets single user by ID. No sensitive data filtering.	None
POST	/users/register	Creates new user account. Basic validation.	name, password
PUT	/users/:id	Updates user information.	name, password
DELETE	/users/:id	Deletes user account permanently. No referential checks performed.	None
Table 50: API Endpoints table of user
Variant Endpoints
Method	Route	Description	Required Fields
GET	/variants	Retrieves all variants with populated variant type information, sorted by type.	None
GET	/variants/:id	Gets single variant by ID with variant type populated.	None
POST	/variants	Creates new variant.	name, variantTypeId
PUT	/variants/:id	Updates existing variant.	name, variantTypeId
DELETE	/variants/:id	Deletes variant only if no products reference it. Referential integrity check.	None
Table 51: API Endpoints table of variant
VariantType Endpoints
Method	Route	Description	Required Fields
GET	/varianttypes	Retrieves all variant types without any population. Simple list view.	None
GET	/varianttypes/:id	Gets single variant type by ID.	None
POST	/varianttypes	Creates new variant type. Basic validation.	name
PUT	/varianttypes/:id	Updates existing variant type.	name
DELETE	/varianttypes/:id	Deletes variant type only if no variants or products reference it. Strict referential checks.	None
Table 52: API Endpoints table of variant type
 
7.2.4 Sample API Implementation
This part demonstrates the implementation of simple CRUD (Create, Read, Update, Delete) operations in a Node.js backend with Express.js, MongoDB, and Mongoose. The operations are performed on a Poster model, which consists of the poster's name and image URL. File upload for posters is handled using multer middleware and express-async-handler package for efficient handling of errors in asynchronous functions.
7.2.4.1 Get Request
 
Figure 49: Get All Posters API using Postman
The initial API implemented is the GET API for retrieving all posters. The API is invoked through the endpoint GET /api/posters. Upon invoking the endpoint, the Poster.find() function is invoked to retrieve all the poster records from the MongoDB database. When the posters are successfully retrieved, the API returns a JSON response with a success message and a list of posters. If there are any type of errors, i.e., database connection errors, the API gives an appropriate error message. The above figure demonstrates the API call via Postman and the successful retrieval of poster data with the response body containing the records.
7.2.4.2 Post Request
 
Figure 50: Create New Poster API using Postman:
The POST API to create a new poster is performed using the endpoint POST /api/posters. This API utilizes the uploadPosters.single('img') middleware for image file and poster name uploading from the client side. The API checks whether the poster name is being sent and the image file being uploaded does not exceed the set size limit of 5MB. If the check fails, the API responds with an appropriate error message. Upon successful verification, a new poster document is stored in the database via the Poster model. The above figure depicts the API request using Postman with form-data posting the posterName and an image file and the response depicting the poster updated successfully.
 
7.2.4.3 Put Request
 
Figure 51: Update Poster API using Postman:
To update an already existing poster, the PUT API is used via the route PUT /api/posters/:id. This API enables the name of the poster, as well as its image, to be updated. This API checks for the required data and uses the findByIdAndUpdate() method to perform the update operation. If the poster cannot be found with the provided ID, the API returns a 404 error message. Upon successful update, a success message is returned. The following image shows the execution of the update request in Postman, depicting the process of updating the name of the poster and inserting a new image, along with the API response showing the successful update.
 
7.2.4.4 Delete Request
 
Figure 52: Delete Poster API using Postman
Lastly, the DELETE API is used to remove a poster based on its ID from the endpoint DELETE /api/posters/:id. The API uses the findByIdAndDelete() method for deleting the specific poster from the database. On successful deletion, the API returns a success message, while for cases where the poster does not exist, a 404 error is raised. The above figure shows the implementation of the delete request in Postman, where the poster has been successfully deleted and the response shows success of deletion.
These API implementations present a clear illustration of how a Node.js backend system executes basic CRUD operations like file uploads, error handling, and database interactions through MongoDB. The explanations and screenshots present for an understanding of the backend services and how they treat client requests in RESTful form.
 
7.3 Frontend Implementation (Flutter)
7.3.1 Project Structure
Frontend of the application is built with Flutter, following feature-based directory structure, which divides the project into logical directories such as core, models, screens, services, utility, and widgets in the lib directory. Such structure renders the codebase developer-friendly, scalable, and modular. By organizing the application in this manner, teams can merely mark UI, business logic, data models, and services, which not only increases maintainability but also allows for team collaboration with different developers working on different modules without interference. The structure also reduces code duplication along with encouraging cleaner code practices, resulting in a successful development cycle.
 
Figure 53: Folder Structure of Client and Admin in flutter

Apart from lib folder, the project includes assets for static files and platform-related directories such as android, ios, web, and windows, facilitating cross-platform deployment from a single Flutter codebase. Configuration and dependency management are achieved using pubspec.yaml and pubspec.lock, which ensure that the app's dependencies and assets are kept uniformly. Files such as .gitignore, .metadata, and analysis_options.yaml facilitate good code formatting, quality analysis, and version control. This systematic structure enhances the scalability of the app as well as smooth integration with the backend APIs. It also makes the project tidy and organized, which is essential for projects of higher scales like an e-commerce system where different modules, user interfaces, and services communicate fluently.
7.3.2 UI Design
While developing the eCommerce app using Flutter, a few widgets were used to design interactive, responsive, and good-looking UI components. Default widgets such as Text, Image, ElevatedButton, and TextFormField were used in designing standard elements like displaying text, images, buttons, and text inputs. For showing ordered data, Card, ListView, and GridView were utilized, supporting scrollable lists and grids for products and categories. Besides, to avoid repetition and have uniform design standards, custom reusable widgets like ProductCard and CustomButton were created. These custom widgets helped the UI become modular, maintainable, and uniform throughout the entire app. All the widgets were styled using Flutter's theming and Material components to present a smooth and professional user interface across different platforms.
1. Common Widget
a. Container Widget
The Container widget in Flutter is one of the most basic and versatile widgets in Flutter. It's a box model widget that allows you to adjust its size, margin, padding, alignment, color, and decoration. It's often used as a parent widget for other widgets when you want to add layout constraints, add a background color or image, or add spacing around the child. You can also add borders, shadows, and rounded corners using the decoration property. It doesn't show anything on its own but is extremely useful for structuring your UI and is a fundamental part of layout design in Flutter.
b. Column Widget
The Column widget is used to show its child widgets vertically in a top-to-bottom flow. It's ideal for stacking widgets such as text, images, buttons, or input fields vertically. The alignment can be adjusted using mainAxisAlignment (vertical axis) and crossAxisAlignment (horizontal axis). It's widely utilized in forms, profile screens, and layouts where widgets should be displayed in a vertical flow. Because it doesn't scroll natively, it's often wrapped in a SingleChildScrollView when the children are more than the screen can fit.
c. Row Widget
The Row widget, like Column, is used to arrange widgets, but in a horizontal manner — from left to right. It's ideal when you want to place things side by side, e.g., a label and a value, multiple buttons, or icons along with text. You can customize alignment using mainAxisAlignment and crossAxisAlignment, just like in a Column. However, if the total width of the children is broader than the screen width, you may get overflow errors unless you wrap the children in a scrollable widget or use flexible widgets.
d. Grid View Widget
GridView is a scrollable widget that displays content in a 2D grid layout, like a product catalog or photo album. It is commonly utilized in eCommerce applications to display products like shoes or clothes in columns and rows. You can predefine the number of columns using GridView.count or customize it dynamically using GridView.builder. It has the capability to scroll in both directions, vertically as well as horizontally. It offers a flexible and organized layout with its especial utilization in displaying identically shaped products with equal spacing and size.
7.3.2.1.5 List View Widget
The ListView widget shows widgets in a linear list that is scrollable either horizontally or vertically. It is used extensively in chat lists, news feeds, product lists, and menu items. Both ListView with static children and ListView.builder for dynamic or long lists for more efficient performance through lazy loading are supported. It can be used with other widgets nested and customized with separators, dividers, and scrolling physics for a more enhanced user experience in various app scenarios.

e. Card Widget
Card widget is used to create a Material Design-styled container with elevation and rounded corners. It's used to display grouped or detailed content like product information, user profiles, or notifications. It gives a slight shadow effect on the UI, which gives the feeling of depth. Any widget can be placed inside a Card, and it's typically combined with Padding and Column or Row to organize its content. Cards are being utilized heavily in modern UI to make content more readable and visually organized.
f. Elevated Button Widget
ElevatedButton is a clickable raised button, typically used for primary actions like "Submit", "Login", or "Add to Cart". It is used as a replacement for the deprecated RaisedButton and is one of the new button styles in Flutter. It can be designed with the style property where you can specify background color, elevation, padding, and text style. It's easy to handle interactions by providing the onPressed property with a function. Buttons can also have icons and can be used as reusable custom-styled widgets. 
7.3.3 API Integration
 
Figure 54: API calling for registering user
The above image gives us the code for a register() function and it helps new users sign up on the Flutter interface. As part of an authentication service, this function uses HTTP requests to communicate with the backend. The function creates a Map<String, dynamic> using the name and password that come from the SignupData object. The addItem() method, probably in a service layer, posts this data to the backend at the users/register endpoint. Because of await, the API call becomes asynchronous, which then permits a smooth user experience because the UI does not freeze.
The response from the backend gets processed to see if registration worked. A special ApiResponse model examines what the backend sends back; then, depending on if it was successful, a success or error message appears. For error management, try-catch is implemented, showing an error snackbar if there are issues during the API call. This form of API integration in Flutter assists in both sending and receiving data; it also guarantees a seamless user experience by providing instant feedback via snackbars and preventing failures through proper error handling. This structure approach readies the frontend for use in production. 
 
Figure 55: API calling to get all products
For another API integration case, there is the getAllProduct() function; it does a GET request to obtain product information from the backend. The service. getItems() method is used by the function to call the products endpoint; after that, it converts the response into a Product objects list, employing a generic ApiResponse wrapper. The parsed list of products is kept in _allProducts and also _filteredProducts, which means the frontend UI is able to use it.
In addition, the function has notifyListeners(), and this refreshes all the widgets observing the product provider, so the user interface displays the updated data. The showSnack parameter is leveraged to display either success or failure messages. The function highlights clear error handling along with useful state management; therefore, it is great for live apps displaying active data.  
7.3.4 Navigation and State Management
Developing Flutter applications, navigation and state management are central; they affect user interaction and application reactions. Navigation in this project lets users switch between different pages such as login, registration, product listing, product detail, cart, checkout, and also order history pages. Also, state management helps manage and show live updates within the app, like when items are added or removed from a cart, filters are used, and user login details are handled.
7.3.4.1 Navigation in Flutter
Flutter employs a stack-based navigation setup using its integrated Navigator widget. A screen is either placed on the stack or taken away from it. For instance, when someone taps a product on the product list screen, the application uses Navigator. push() to display the product details. The new screen is added to the top of the navigation stack with this action, and the user is able to view product details. As the user presses the back button, Navigator. pop() automatically gets used; it removes the screen and goes to the one before.
 
Figure 56: Navigation to My Order Screen
This structure ensures a smooth and predictable user experience, as users can move back and forth between screens just like in most native mobile applications. Navigation is also used to manage complex flows, such as directing users to the login screen if they are not authenticated, or navigating them to the payment screen after successfully filling in the order details.
 
7.3.4.2 Provider in Flutter
To handle dynamic data and app-wide state, this project uses the Provider package, one of the most recommended solutions for state management in Flutter. Provider allows separating business logic from UI code by creating dedicated ChangeNotifier classes. These classes contain the application logic and variables, and notify the UI when a change occurs, using the notifyListeners() method.
For example, in the product listing feature, a ProductProvider class manages a list of products fetched from the API. Whenever new products are retrieved or filtered, notifyListeners() is called to rebuild all widgets that are listening to this provider. This ensures that users always see the most up-to-date list.
 
Figure 57: Provider Notify Listeners
Another use case is the CartProvider, which handles logic related to adding and removing items from the shopping cart. When an item is added, the provider updates the list and notifies listeners, and the UI automatically reflects the new total price or item count.
The Provider pattern brings many advantages:
•	Decouples logic from UI: Making the codebase easier to maintain and test.
•	Improves performance: Because only widgets that depend on changed data get rebuilt.
•	Ensures consistent state across the app: For example, the cart state or login state can be accessed from any screen.
In addition, by wrapping the root widget with MultiProvider, multiple providers can be initialized at once and shared across the entire app:
 
Figure 58: Flutter Multi Provider Setup
In summary, the use of Navigator for managing screen transitions and Provider for managing shared application state ensures that the app remains scalable, responsive, and user-friendly. These tools together provide a powerful foundation for building complex Flutter apps with clean architecture and smooth user experience.
 
7.3.5 Validation and Error Handling
In Flutter applications, validation and error handling are critical for maintaining a smooth user experience and preventing invalid or incomplete data from being submitted to the backend. Our project implements both form validation and runtime error handling using Flutter’s built-in tools and custom utility classes.
7.3.5.1 Form Validation
We use Form widgets along with TextFormField to collect and validate user input. Each input field is wrapped with a TextFormField that includes a validator function. This function is used to check the user’s input and return an error message if the input is invalid. For example, during user registration or login, we validate fields like email, username, and password to ensure they are not empty and meet the required format.
 
Figure 59: Text Form with Validations
We also use GlobalKey<FormState> and formKey.currentState!.validate() to trigger the validation process before proceeding with form submission, like navigating to the payment page or registering a user.
 
7.3.5.2 Runtime Error Handling
To handle errors during API calls or other asynchronous operations, we use try-catch blocks combined with custom error messages. This ensures that unexpected problems like network failure, server errors, or invalid data formats are caught gracefully and shown to the user in a readable way. 
 
Figure 60: API Error Handling Snack Bar
We use a custom SnackBarHelper class to display consistent feedback across the app. These snackbars are styled uniformly and help users understand whether an action was successful or not.
Validation ensures users enter meaningful and acceptable input before processing it further, while error handling captures any disruptions that occur during processing and provides users with appropriate feedback. These two features combined improve app reliability, prevent crashes, and enhance user trust in the system.
 
6.4 System Output
6.4.1 User Side
6.4.1.1 Signup
 
Figure 61: Login Screen
This above image displays the Signup screen of the Solemates e-commerce mobile application. It is the first step in the user onboarding process, allowing new users to create an account. The screen includes input fields for the user to enter their name, email address, mobile number, password, and confirm password. The “Sign Up” button at the bottom initiates the registration request. This page is essential for gathering necessary credentials and user details to ensure personalized access to the app. It also includes validation to prevent missing or incorrect entries. This process is important as it marks the user's entry into the system and allows them to utilize app features like placing orders, saving favorites, and tracking purchases.
After the user successfully fills in the signup form and submits it, this image shows a confirmation screen or toast message stating that the signup was successful. Along with the success notification, the app displays an activation code message sent to the user, likely via email or SMS. This step ensures an extra layer of security by verifying that the provided contact information is valid and belongs to the user. The activation process helps protect against spam registrations and fake accounts, maintaining a secure and trustworthy environment.
6.4.1.2 Login
 
Figure 62: Login Screen
This image shows the Login screen where registered users can access their existing Solemates account. Users are required to input their registered email address and password. The interface is designed to be clean and simple, focusing on quick and secure access. This step validates the credentials against the database to ensure that only authorized users can access the app. Additionally, this screen may also include options for password recovery or alternative login methods such as Google or Facebook in future enhancements. The login process connects the frontend to the backend for credential verification. If the details are correct, the app proceeds to the user dashboard or home screen. If incorrect, it returns an appropriate error message.
 
Figure 63: Success message
This image captures the success message that appears after the user enters valid login credentials. It indicates that the login process was completed successfully and the user is being navigated to the home screen. This screen confirms that the backend has authenticated the user and granted them access to the system.
6.4.1.3 Home Screen 
 
Figure 64: Home Screen
This image shows the Home Screen of the Solemates e-commerce mobile app. It is the central landing page that users see after logging in. The layout typically includes banners, featured products, category shortcuts, or offers to engage users immediately. From this screen, users can browse various product categories, tap on individual items for more details, or navigate to other sections like the cart, favorites, or profile. It serves as the main interface for shopping and exploring the app. The home screen is critical in offering an intuitive and visually appealing starting point for users, encouraging them to interact more with the app and increasing the likelihood of purchases. It acts as a dashboard for the overall shopping experience.
6.4.1.4 Category Screen
 
Figure 65: Category Page
This image shows the Category Screen, which displays different product categories available in the Solemates app. Users can tap on each category to explore the items grouped under it, such as Men’s Shoes, Women’s Shoes, Sportswear, Accessories, and more. Each category is represented with a name and an image icon, making it easier for users to identify and choose based on their shopping preferences. This screen helps organize the app content and makes the browsing experience more efficient by narrowing down product searches. Instead of going through hundreds of items, users can quickly jump into the section they are interested in. It also helps in managing backend inventory by logically grouping products.

6.4.1.5 Product Screen
 
Figure 66: Product Screen
First image represents the Product Screen, which displays the details of an individual item selected from a category. It includes product images, name, description, price, available variants (like size or color), and an “Add to Cart” button. This screen is essential for converting interest into action by giving users all the information they need to make a purchase decision. The product screen is a core component of the shopping experience. It not only shows visual details but also enables users to select the appropriate variant before purchasing. The user must choose variant options (if available) before proceeding to cart. It’s where users interact deeply with a product before committing to buying.
The second image shows a validation message when the user attempts to add a product to the cart without selecting a required variant like size or color. Instead of adding the item blindly, the system prompts the user to make the appropriate selections first. This feature helps prevent incomplete or incorrect orders. It ensures that the user picks the exact variant they want, which is especially important for products like clothing or footwear. It improves order accuracy and reduces return rates.
6.4.1.6 Favorites Screen
 
Figure 67: Favorite Screen
This image displays the Favorites Screen, which lists all the products that the user has marked as favorites. It acts like a wishlist where users can save items they like but aren’t ready to purchase immediately. Each listed item usually includes a thumbnail image, name, and price, along with options to remove or move to cart. The favorites screen helps improve user engagement by giving them a personal space to revisit products they’re interested in. It enhances the user experience by making it easier to come back to preferred items and encourages future purchases. 
6.4.1.7 Cart Screen
 
Figure 68: Empty Cart Screen and Item filled cart screen
First image shows the Empty Cart Screen that appears when the user has not added any items to their cart. The screen is usually minimal, with a message or icon indicating that the cart is currently empty, along with a prompt like “Continue Shopping” to redirect users back to the home or category pages. This screen is important for informing users that they haven’t selected any items yet. It provides a clear visual cue that action is required before proceeding to checkout. It also helps maintain a clean user experience by not displaying irrelevant data when the cart has no products.
The second image shows the cart after the user has added one or more products. Each item is displayed with its image, name, selected variant (e.g., size), quantity, and price. The user can update quantities, remove items, or proceed to buy the items using the “Buy Now” or “Checkout” button. This screen is crucial for order review before final purchase. It lets users double-check product details and costs. It also shows the real-time reflection of user actions like adding or deleting items, which helps build trust and control during the shopping process. 
 
Figure 69: Show Dialog button after clicking "Buy now"
In this image, when the user clicks the "Buy Now" button in the cart, a dialog box or bottom sheet appears. This is likely a confirmation step that asks users to select or confirm a delivery address, payment method, or provide final checkout details. The dialog screen acts as a bridge between the cart and payment screen. It ensures that users are fully aware of what they’re purchasing, including total cost, quantity, and shipping options. It may also allow users to add coupon codes or choose between multiple addresses before payment. 
6.4.1.8 Payment Screen
 
Figure 70: Payment screen while choosing Credit Card and eSewa
First image shows the Payment Screen where the user has selected “Credit Card” as the payment method. It contains form fields to enter card details such as cardholder name, card number, expiry date, and CVV. This process connects to a secure payment gateway. Proper validation is implemented to ensure all required fields are entered correctly before proceeding. This screen plays a vital role in ensuring secure transactions while giving users multiple payment choices.
Second image displays the eSewa payment screen where users can choose eSewa, a popular digital wallet in Nepal, as their payment method. It likely includes a field to enter eSewa ID and a button to initiate payment, which would redirect or connect to eSewa’s gateway for authentication. The inclusion of local payment options like eSewa improves accessibility and user satisfaction, especially for Nepali users. It allows users to choose familiar, fast, and secure digital payment systems. This screen ensures flexibility and broader adoption of the app across different customer preferences.
 
Figure 71: Order listed in my order page after successful payment
This image shows the My Orders screen, where the new order appears after successful payment. It includes details such as product name, price, order date, and current status (e.g., "Processing," "Shipped," or "Delivered"). This helps users track the progress of their order. The order listing helps users manage their shopping history and monitor their purchases. It reflects the integration between the payment and order tracking systems, ensuring users receive real-time updates.
 
Figure 72: Validators in Credit Card
This image highlights the validation mechanisms applied to the Credit Card payment screen. It likely shows error messages when fields like card number, expiry date, or CVV are left empty or filled incorrectly. These validations are vital to prevent invalid or incomplete card submissions. They also help avoid transaction failures and maintain payment security by ensuring that users input correct data before the system attempts to process the payment.

Figure 73: Validators in esewa
6.4.1.9 Profile Screen
 
Figure 74: Profile Screen
This image displays the Profile Screen of the Solemates app. It shows the user's account information such as name, email address, phone number, and options to edit profile, change password, manage addresses, or log out. The profile screen acts as a hub for account-related activities. It gives users control over their personal information and access to account-specific settings, improving the personalized experience of the app.
 
6.4.1.10 My Orders Screen
 
Figure 75: My Order Screen
This image presents the My Orders screen, where users can see a list of all their past and current orders. Each order item displays essential details like order ID, product image, product name, price, order date, and order status (e.g., Pending, Delivered, Cancelled).
This screen is central to order tracking. It helps users keep track of what they’ve purchased, check delivery progress, and review order history. It builds transparency and reliability, allowing users to verify if and when their products will arrive or have already been delivered. 
6.4.1.11 My Address Screen
 
Figure 76: My Address Screen
The first image shows the My Address screen, where users can add, edit, or view their saved delivery addresses. Each address entry includes details such as the recipient name, phone number, city, and full address. This screen enhances the checkout experience by allowing users to select a pre-saved address instead of typing it again every time. It’s essential for fast and error-free order placement, especially for returning customers. It also provides multiple addresses for users who shop for different locations (e.g., home, office).
The second image illustrates validation checks on the My Address screen. It likely displays error prompts when mandatory fields like name, city, or phone number are left blank or filled with invalid data. Validators ensure that the address format is accurate and complete. This helps prevent delivery issues caused by incomplete or incorrect addresses and improves user accountability during the input process.
 
6.4.2 Admin Side
6.4.2.1 Dashboard
 
Figure 77: Admin Dashboard
This image represents the Admin Dashboard, the main control panel for managing the overall system operations. It provides an overview of key metrics such as the number of registered users, products listed, active orders, completed transactions, and possibly revenue summaries. The dashboard is likely designed with cards or tiles that offer quick access to important sections like Products, Categories, Orders, Brands, and Variants.
The Admin Dashboard is crucial for the backend team or store owner. It offers centralized monitoring and helps make data-driven decisions. It also gives the administrator the ability to track user activity, identify top-selling products, monitor low stock levels, and respond quickly to order statuses. From here, the admin can navigate to perform CRUD (Create, Read, Update, Delete) operations on almost every core data set in the app.

 
Figure 78: Adding new product to dashboard
This image displays the form or interface used to Add a New Product to the system. It includes input fields for product name, description, price, category, subcategory, brand, available variants (like sizes or colors), images, and stock status. There may also be an upload button for images and dropdowns to select pre-existing categories or brands.
Adding products through this form ensures that the app remains up to date with the latest inventory. The process is designed to be admin-friendly with clear labels, validations, and logical flow to avoid data entry mistakes. This is one of the most frequently used features by the backend team, especially in a dynamic store where new arrivals are common.
 
Figure 79: Success message after product addition
This image shows a confirmation or toast message that appears after a product is successfully added to the database. The success message reassures the admin that the new product entry has been saved and is now available in the product listing for customers to view and purchase.
 
Figure 80: Product list update after new insertion
This image shows the updated Product List after the newly added product appears in the list. The product list typically includes a table or card view displaying details like product name, image thumbnail, price, stock status, and action buttons (Edit/Delete).
The product list is a live reflection of the inventory and plays a key role in managing what's visible to customers. The admin can scroll through the list, search specific products, or make modifications in real time. Seeing the newly added product here confirms that the system backend and frontend are properly integrated. 
6.4.2.2 Category 
 
Figure 81: Admin Category
This image shows the Category Management screen on the admin side. Here, the administrator can view all existing product categories along with options to edit or delete them. Each category entry may include a name, image icon, and action buttons.
Category management is vital for keeping the product catalog structured and user-friendly. By maintaining organized categories, the admin enhances the user experience on the frontend and makes it easier for customers to find what they’re looking for. This screen is especially useful when launching new product lines or seasonal campaigns.
 
Figure 82: Adding new category
This image shows the interface where the admin adds a new product category into the system. The form typically includes fields such as Category Name and an option to upload an Image/Icon representing the category. There may also be dropdowns to set category visibility, sorting priority, or status (active/inactive). This interface is often used to keep the app’s frontend dynamic and adaptable as the product catalog grows.
Creating new categories is an essential administrative task that helps maintain a well-organized product structure. For example, if a new product line like “Sneaker Accessories” or “Winter Collection” is introduced, it should be placed under its own category. This allows end users to easily find items based on their shopping intent. Categories not only influence frontend navigation but also assist in backend reporting, analytics, and inventory tracking.
 
Figure 83: Success message after category addition
This image shows a success confirmation message after the admin has added a new category. It reassures the admin that the new category has been saved to the system and will now be reflected in the app’s category listings.
 
Figure 84: Category list update after new insertion
This image shows the updated category list, now including the newly created category. Each entry usually shows the category name, associated image, and action buttons for editing or deleting.
This update confirms the proper working of backend logic, ensuring new data is dynamically displayed. It also helps admins verify and manage entries effectively.
6.4.2.3 Subcategory
 
Figure 85: Admin Subcategory
This image introduces the Subcategory Management interface. Here, the admin can view and manage subcategories that fall under main categories. Each subcategory belongs to a parent category and helps in further organizing products. For instance, within the “Footwear” category, subcategories might include “Running Shoes,” “Boots,” or “Sandals.”
Subcategories are important for multi-level product filtering. They improve the frontend browsing experience by narrowing down options within each main category. On the backend, they allow for deeper segmentation of products, making it easier to generate specific analytics, target promotions, or manage stock. The interface usually includes columns like Subcategory Name, Parent Category, Image, and action buttons for edit or delete.
By maintaining a structured hierarchy of categories and subcategories, the app ensures that users can drill down into exactly what they’re looking for, reducing friction and increasing the likelihood of purchase.
 
Figure 86: Adding new Subcategory
This image shows the form used to add a new subcategory under a parent category. Fields include the Subcategory Name, Parent Category Selection (via dropdown), and possibly an image upload or display preference setting.
 
Figure 87: Success message after subcategory addition
This success message appears after the admin adds a new subcategory. It confirms the entry has been saved to the database and the app will now reflect it under its respective parent category.
 
Figure 88: Subcategory list update after new insertion
This image shows the updated list of subcategories after a new one has been added. The list typically includes columns like subcategory name, parent category, and action buttons (edit/delete). A small image or icon may be shown next to each subcategory for better visual identification.
This screen is essential for admins to manage existing subcategories, verify successful additions, and make quick changes when necessary. It confirms the connection between data input (subcategory form) and live backend display, reinforcing the integrity of the system’s dynamic content management.
6.4.2.4 Orders
 
Figure 89: Admin Orders
This image introduces the Admin Orders screen, where administrators can view and manage all user orders placed through the app. Each order in the list includes key information such as Order ID, Customer Name, Product(s) ordered, Payment Status, Delivery Status, Date, and possibly Total Amount. There are likely action buttons for updating order status (e.g., Pending, Shipped, Delivered, Cancelled).
This screen is one of the most important parts of the admin system. It acts as the command center for managing order fulfillment, ensuring a smooth customer experience. From here, the admin can monitor the sales pipeline, handle issues (like failed payments or order returns), and communicate with delivery services.
Efficient order management directly impacts customer satisfaction and brand reputation. A real-time, searchable, and well-organized order list enables the admin to keep the system running smoothly and respond to customer needs promptly.

 
Figure 90: Order details
This image shows the detailed view of a specific order when clicked from the Admin Orders list. It contains in-depth information such as the delivery address, list of products with variants and quantities, payment method used, and order notes (if any).
This level of detail allows the admin to process and verify each order properly before confirming dispatch. It may also include buttons to update the delivery status, print invoices, or cancel orders if needed.

6.4.2.5 Brands
 
Figure 91: Admin Posters
This image introduces the Admin Brands Management section. It displays a list of all the product brands available in the system. Each brand may include its name, logo/image, and action buttons (edit/delete). The purpose of this screen is to help the admin maintain brand data used when creating or categorizing products.
Brands are important for product credibility and filtering. Customers often prefer shopping by brand, and this screen helps keep those preferences updated and accurate on the frontend. It also helps store owners build partnerships with specific manufacturers or vendors by showcasing their brand names prominently.
The presence of a dedicated brand management system reflects the app’s scalability and professional design, especially as the product catalog grows.

 
Figure 92: Adding new Brands
This image displays the form for adding a new brand to the system. The form typically includes fields like Brand Name, Brand Image/Logo Upload, and possibly a status toggle (Active/Inactive).
Adding new brands is a regular task for admins, especially when onboarding new products from different manufacturers. It ensures the brand filter works correctly on the frontend and allows customers to search by familiar names.
 
Figure 93: Success message after brand addition
This image shows a confirmation message after the admin successfully adds a new brand. The message indicates that the new brand has been saved in the system and is now available for use when adding or updating products.
 
Figure 94: Brands list update after new insertion
This image displays the updated Brands List, now including the newly added brand. The list shows brand names along with their logos and management options such as edit and delete. It confirms that the database has been updated and reflects real-time changes.
The updated view ensures that the brand is immediately available to associate with products. It also helps admins confirm that entries were made correctly and keeps the system transparent.
6.4.2.6 Variant Type
 
Figure 95: Admin Posters
This image introduces the Variant Type Management screen on the admin side. Variant types refer to customizable product attributes like Size, Color, Material, or Style. Each variant type is a category under which specific variant values (e.g., Size → M, L, XL) are grouped.
Managing variant types is crucial for e-commerce platforms that sell configurable products, such as clothing or footwear. This screen allows the admin to create, review, and manage variant types which will later be linked to specific product entries. A well-structured variant system enhances the shopping experience by allowing users to select exactly what they want (e.g., Red Color in Size M).
From the backend perspective, variant types help in stock tracking, price adjustments per variant, and displaying the correct options on the frontend. This also supports advanced features like filtering, variant-specific discounts, and variant-based availability display.
 
Figure 96: Adding new variant type
This image shows the admin form used to create a new variant type. The form typically includes a field to enter the Variant Type Name (e.g., “Material”), and may also have a description field or status toggle.
Creating a variant type allows the admin to categorize product options in a structured way. It prepares the system to accept multiple product variants in an organized and scalable manner.
 
Figure 97: Success message after variant type addition
This success message appears after the admin has added a new variant type. It confirms that the input was accepted, saved to the database, and is now ready for use in product configuration.
 
Figure 98: Variant Type list update after new insertion
This image displays the updated table of variant types in the admin dashboard after successfully adding a new variant type called "Laptop Size." The table is systematically organized with columns showing Variant Name (e.g., "Color," "Tv size"), Variant Type (e.g., "size," "Color"), Added Date with precise timestamps, and action buttons for editing or deleting entries.
The addition of "Laptop Size" demonstrates the system's capability to handle diverse product specifications, which is particularly important for e-commerce platforms selling items with multiple customizable attributes. This feature ensures that administrators can efficiently categorize and manage product variations, directly impacting the frontend user experience by providing accurate and detailed product options. The real-time update of the list confirms the system's robust backend integration and responsiveness, allowing for seamless inventory management.
6.4.2.7 Variant 
 
Figure 99: Admin Variants
This image displays the admin panel for managing product variants, which are specific options or attributes of products (such as sizes, colors, or materials). The interface appears organized with sections like "Shop," "My Variants," and "All Variants," suggesting a comprehensive system for tracking different product variations.
The "All Variants" table likely lists existing variants with details like variant name, associated variant type, and management options (edit/delete). This section is crucial for maintaining accurate product listings, as it allows administrators to define and organize the specific options customers can choose when purchasing products. For example, a t-shirt product might have variants for different sizes (S, M, L) and colors (red, blue, green).
 
Figure 100: Adding new variant
This image shows the form administrators use to add a new product variant to the system. The form appears simple but functional, with fields for selecting the variant type (likely from a dropdown of predefined types like "size" or "color") and entering the specific variant name (in this case "32"). Action buttons ("Cancel" and "Submit") provide clear options to complete or abandon the operation.
The process of adding variants is fundamental to creating detailed product listings that offer customers multiple options. For instance, a shoe product might need variants for different sizes, widths, or colors. This form enables administrators to systematically add these options, which then become available for assignment to relevant products.
 
Figure 101: Success message after variant addition
This image displays a confirmation message indicating the successful creation of a new variant ("32"). The notification uses a green color scheme, which is universally recognized for success/positive actions, and provides immediate feedback that the system has accepted and processed the new variant.
 
Figure 102: Variant list update after new insertion
This image shows the updated variants list following the addition of the new "32" variant. The table now includes the new entry alongside existing variants, with each row displaying the variant name, its type classification, and the date/time it was added to the system.
6.4.2.8 Posters
 
Figure 103: Admin Posters
This image showcases the dedicated admin panel for managing promotional posters and marketing banners within the e-commerce platform. The interface is intuitively organized into distinct sections including "Shop," "My Posters," and "All Posters," complemented by a search functionality for efficient navigation. The central focus of the screen is a comprehensive list of existing promotional materials, each entry displaying the poster name alongside actionable options for editing or deletion. This management system serves as the backbone for the platform's visual marketing strategy, enabling administrators to dynamically control the promotional content displayed across the app. The inclusion of an "Add Here" button indicates a streamlined workflow for uploading new marketing materials, ensuring the platform can quickly adapt to seasonal campaigns, product launches, or special sales events. This level of control over visual merchandising is crucial for maintaining an engaging user experience and driving conversion rates through targeted promotions.
 
Figure 104: Adding new poster
The image presents the detailed interface for creating new promotional posters within the admin dashboard. The form includes essential fields such as the "Poster Name" field (shown populated with "Let's go!"), a descriptive text area for promotional content, and what appears to be an image upload section (partially visible). The clean, minimalist design of the form features prominent "Cancel" and "Submit" buttons, maintaining consistency with the platform's overall UI aesthetic. This creation interface empowers marketing teams to craft compelling visual campaigns by combining eye-catching titles with persuasive promotional text and high-quality graphics. The ability to quickly generate and deploy new posters enables the platform to respond rapidly to market trends, inventory changes, or competitive pressures, making it a vital tool for maintaining the platform's commercial agility and visual appeal.
 
Figure 105: Success message after poster addition
This image captures the system's confirmation message following the successful creation of a new promotional poster. The notification employs a green color scheme, universally recognized for indicating successful operations, and delivers clear, concise feedback that the "Let's go!" poster has been properly saved to the system.
 
Figure 106: Posters list update after new insertion
The image displays the refreshed list of promotional posters following the addition of the new "Let's go" campaign. The tabular layout presents a clean, organized view of all available posters, with each entry featuring the poster name alongside standard management options (edit and delete functions). This updated view serves multiple operational purposes: it allows administrators to immediately verify the successful integration of new materials, provides an at-a-glance overview of all active campaigns, and offers quick access to management functions for each individual poster. The real-time reflection of new additions demonstrates the system's robust backend integration and its capacity for instantaneous content updates. This feature is particularly valuable for time-sensitive marketing operations where campaign visibility windows may be narrow or subject to frequent adjustments. 
6.4.2.9 Coupons
 
Figure 107: Admin Coupons
This image reveals the comprehensive coupon management system within the admin dashboard. The interface presents a detailed "All Coupons" view, systematically listing existing discount offers with relevant details including coupon names, current status (active/inactive), discount types, monetary values, and management options. The layout is organized into functional sections that facilitate easy navigation and quick access to coupon-related operations. This sophisticated management console enables precise control over the platform's promotional strategies, allowing administrators to create targeted discounts, monitor offer performance, and adjust campaigns in response to business needs or market conditions. The inclusion of status indicators and management options for each coupon entry provides administrators with complete control over the platform's discount ecosystem, making it possible to implement complex promotional strategies while maintaining clear oversight of all active offers.
 
Figure 108:  Adding new coupon
This image presents the comprehensive coupon creation interface within the admin dashboard. The form includes multiple fields to configure sophisticated discount offers: a "Coupon Code" field (shown populated with "New30"), discount amount and type selection (percentage or fixed value), date selection for validity period, category and product-specific targeting options, minimum purchase requirements, and status toggles. The interface demonstrates the platform's capacity for granular promotional control, allowing administrators to craft precisely targeted discount strategies. The form's logical grouping of related fields - with clear section divisions between coupon parameters, applicability rules, and activation controls - creates an efficient workflow for marketing teams. This level of detailed coupon configuration supports everything from store-wide sales to highly specific product promotions, enabling data-driven discount strategies that can be tailored to different customer segments, shopping behaviors, or inventory requirements.
 
Figure 109: Success message after coupon addition
The image shows a green success notification confirming the creation of the "New30" coupon. This feedback serves as both a system confirmation and an administrative checkpoint, verifying that all configured parameters - including the 12% percentage discount, NPR 45,000 minimum purchase requirement, and mobile phones category restriction - have been properly saved to the database.
 
Figure 110: Coupons list update after new insertion
This image displays the updated coupon management table now including the newly added "New30" promotion. The refreshed view presents a complete catalog of available discounts with columns showing coupon identifiers, status indicators, discount types, monetary values, and management controls. The "New30" entry specifically highlights its percentage-based discount structure and active status. This comprehensive overview enables administrators to: monitor all live promotions simultaneously, verify correct implementation of new coupons, identify potential conflicts between overlapping offers, and maintain organizational control over the platform's discount ecosystem. The tabular format, enhanced by clear typographic hierarchy and visual separation between entries, allows for quick scanning and comparison of multiple coupon parameters. Real-time updates to this view demonstrate the system's responsive backend architecture and its capacity to immediately reflect marketing decisions in operational contexts. 
6.4.2.10 Notification
 
Figure 111: Admin Notification
The image reveals the notification management center where administrators control push notifications and in-app alerts. The interface shows a clean, segmented layout with sections for viewing sent notifications ("All Notification"), searching past messages, and accessing creation tools. The existing notifications list displays two sample entries with their titles, descriptions, and timestamps, demonstrating the system's capacity for maintaining a historical record of customer communications. This management hub serves as the nerve center for customer engagement strategies, enabling timed promotional alerts, important service announcements, or personalized marketing messages. The inclusion of view and delete options for each notification provides necessary controls for compliance and content management, while the visible "SEND NOTIFICATION" button indicates ready access to the message creation workflow. The interface's emphasis on chronological organization and clear status indicators facilitates efficient management of customer communication schedules and histories.
 
Figure 112: Adding new notification
This screenshot shows the notification composition interface with fields for crafting customer alerts. The form includes a title field ("Today special offer is available"), description area ("Available Today"), and an image URL field for visual content. The layout suggests additional customization options for targeting, scheduling, or priority settings. This creation tool enables marketing teams to design rich, engaging notifications that can combine promotional text with visual elements for higher impact. The interface supports various notification types - from time-sensitive flash sales to important account alerts - with flexibility to tailor both content and presentation. The form's structure guides administrators through an efficient message creation process while maintaining opportunities for creative expression and strategic timing. The visible fields indicate the platform's capacity for multimedia notifications that can significantly enhance open rates and customer engagement compared to text-only alerts.
 
Figure 113: Success message after notification addition
The image captures the system's confirmation that the "Today special offer is available" notification has been successfully distributed. The green success message provides immediate feedback that the alert has been queued for delivery through all appropriate channels (likely including both push notifications and in-app messages).
 
Figure 114: Notification list update after new insertion
This image presents the updated notifications log following the addition of the new promotional alert. The table now includes the "Today special offer" entry alongside previous notifications, with each record displaying the message title, brief description, precise sending timestamp, and management options. The chronological listing demonstrates the system's capacity to maintain a detailed audit trail of all customer communications, which is valuable for both performance analysis and regulatory compliance. The updated view enables administrators to: track the frequency of customer messaging, review past communication strategies, identify successful notification patterns, and maintain organizational control over customer outreach. The inclusion of precise timestamps (accurate to milliseconds) highlights the platform's attention to detailed record-keeping, while the consistent row formatting ensures readability despite the potentially high volume of historical notifications. This comprehensive log serves as both an operational tool and a strategic resource for refining customer engagement approaches over time.
 
Figure 115: Notification received by user.
This image shows a mobile push notification from the e-commerce app announcing a "SPECIAL OFFER" (with a visible typo in "Toda"). The alert displays the offer details ("Available Today") and includes action buttons ("Manage" and "Clear all"). It demonstrates the app's promotional messaging system and reveals a quality control issue in notification content. 
Chapter 7 System Testing
7.1 Introduction
Software testing is the process of verifying and confirming that the deployed SoleMates E-Commerce System is valid and accurate in satisfying the specified business and user requirements as well as free from errors, defects, or bugs. In this project, several tests were performed, including unit testing, integration testing, system usability testing, and user acceptance testing (UAT). This chapter gives the objectives, scope, test levels, entry and exit criteria, and the testing strategies applied for the admin segment and client segment of the system.
7.2 Test Objectives
The SoleMates system test objectives are as follows:
•	To evaluate that all the system’s modules are working as desired by both admin and client users.
•	To detect bugs, defects, or risks as early as in the system life cycle so that they can be solved in a timely manner.
•	To make the system secure, scalable, user-friendly, and run well across different situations.
To enable seamless integration of all the functional modules with third-party services (e.g., payment gateway, email notification).
7.3 Test Scope
Admin Portal and Client Portal functionality of the SoleMates E-Commerce System is within the scope of testing.
The following modules are covered:
Admin Portal Modules:
•	Admin Login Module
•	Product Management Module
•	Category Management Module
•	Brand Management Module
•	Variant Management Module
•	Coupon Management Module
•	Order Management Module
•	User Management Module
•	Report and Sales Analytics Module
Client Portal Modules:
•	Register and Login Module
•	Product Browsing and Search Module
•	Product Detail and Review Module
•	Cart and Wishlist Module
•	Checkout and Payment Module
•	Order Management Module
•	Address Management Module
•	Voucher and Coupon Application Module
•	Account Management Module
7.4 Test Level 
Testing of the SoleMates system involved the following levels:
1.	Unit Testing
Testing individual modules and components independently for correct behavior.
2.	Integration Testing
Testing all module combinations to verify data flow and module interaction.
3.	System Usability Testing
Testing the entire system from a user's perspective to ensure the interface is intuitive and the system is user-friendly.
4.	User Acceptance Testing (UAT)
Performed by live users (admin and client users) to validate that the system meets real business and customer requirements.
7.5 Test Entry
•	Development of all functional modules is complete.
•	The test environment is established and stable.
•	Test data, tools, and scenarios are ready and checked.
•	All third-party integrations are test ready
7.6 Exit Criteria
•	All the planned test activities are completed.
•	The pass rate of all the tests is 95% and more.
•	All high-severity and critical defects have been resolved and retested successfully.
•	The system is meeting anticipated performance, security, and usability norms.

7.7 Unit Testing
7.7.1 User/Client
a.	Test Case: Browse Products
Test Case ID	INV011
Module Name	Product Module
Test Title	Unit Test Case for Browsing Products
Pre-condition	1. User has launched the client app
2. Device is connected to the internet
3. At least one category and product exist in the system
Test Case Summary	Test Steps	Test Data	Expected Result	Status
Load homepage with dynamic content	1. System fetches and loads posters, categories, and subcategories dynamically	-	Homepage displays posters, categories, and subcategories	Pass
Display featured products	1. Wait for homepage to load
3. Check featured products section	-	Featured products are displayed with basic info (image, name, price)	Pass
Browse by category	1. From homepage, click on a category (e.g., Fashion)
2. System fetches products under the category	Category = Fashion	Products related to selected category are listed with image, name, and price	Pass
Browse by subcategory	1. From homepage, click on a subcategory 
2. System fetches products	Subcategory = Shoes	Products under the selected subcategory are listed correctly	Pass
Scroll through products	1. Select a category/subcategory
2. Scroll down the product list	-	Products load smoothly while scrolling	Pass
Select product to view details	1. Browse products
2. Click on a product card	Product ID	Redirect to View Product Details flow with full info	Pass
Table 53: Unit Testing of Browse products
b.	Test Case: View Product Details
Test Case ID	INV012
Module Name	Product Module
Test Title	Unit Test Case for Viewing Product Details
Pre-condition	1. User is logged in (optional)
2. User has browsed or searched for products
3. At least one product with variants and reviews is available in the system
Test Case Summary	Test Steps	Test Data	Expected Result	Status
View product details page	1. Click on a product card
2. System fetches product details	Product ID = P123	Display product details with images, name, description, price, variants, stock, and reviews	Pass
Zoom and swipe product images	1. On product detail page
2. Swipe/zoom on images	-	Images respond to zoom and swipe gestures	Pass
View name, description, and discount	1. On product page
2. Check product info section	-	Name, full description, price, and discount (if available) are shown	Pass
Select valid variant	1. Choose valid size, color, or model options	Size = M
Color = Blue	Price and stock info updates based on selection	Pass
Select an invalid variant combination	1. Choose unavailable combination	Size = XL
Color = Yellow (if not available)	Show error or disable "Add to Cart"	Pass
Display stock status	1. Select a valid variant
2. View stock info	In stock, out of stock	Correct stock status is shown	Pass
View customer reviews	1. Scroll to review section	-	Reviews and ratings summary displayed	Pass
Add to cart	1. Click “Add to Cart” after selecting variant	Product ID, Variant	Redirect to cart with product added	Pass
Add to favourites	1. Click “Add to Favourites” icon	Product ID	Product added to favourites; confirmation shown	Pass
Share product	1. Click “Share” button	-	System shows share options	Pass
Go back to product list	1. Click “Back” button	-	Return to browsing page	Pass
Table 54: Unit Testing of View products details
 
c.	Test Case: Add Product to Cart
Test Case ID	INV013
Module Name	Product Module
Test Title	Unit Test Case for Adding Product to Cart
Pre-condition	1. User is on the product detail page
2. Product has variant options (if applicable)
3. Product has available stock
Test Case Summary	Test Steps	Test Data	Expected Result	Status
Add product without selecting variant	1. Click “Add to Cart” without choosing size/color	Variant not selected	Show error: “Please select [variant]”	Pass
Add product with variant but exceeding stock	1. Select variant
2. Set quantity above available stock
3. Click “Add to Cart”	Stock = 3
Quantity = 5	Show error: “Only 3 items available”	Pass
Add product with correct variant and quantity	1. Select variant
2. Set valid quantity
3. Click “Add to Cart”	Variant = M, 
Color = Black, 
Quantity = 2	Product added to cart	Pass
Update cart badge count	1. Add a product successfully	-	Cart badge increases correctly	Pass
Show confirmation popup	1. After successful add to cart	-	“Added to cart” popup with “View Cart” and “Continue Shopping” shown	Pass
View Cart from popup	1. Click “View Cart” from confirmation	-	Redirect to Cart screen	Pass
Continue Shopping from popup	1. Click “Continue Shopping” from confirmation	-	Redirect back to previous browsing/product screen	Pass
Table 55: Unit Testing of Add product to cart
d.	Test Case: Place Order
Test Case ID	INV015
Module Name	Order Placement Module
Test Title	Unit Test Case for Placing an Order
Pre-condition	1. User is logged in
2. Cart has at least one product
3. Address and payment options are enabled in system
Test Case Summary	Test Steps	Test Data	Expected Result	Status
Proceed to check out from cart	1. Click “Proceed to Checkout”	Cart has items	Navigates to checkout screen	Pass
Try placing order without address	1. Leave address empty
2. Click “Confirm Order”	Address = ""	Show error: “Please select or enter a delivery address”	Pass
Select delivery method	1. Choose between Standard or Express	Delivery = Express	Delivery option saved for order	Pass
Try placing order without selecting payment	1. Skip payment option
2. Click “Confirm Order”	Payment = ""	Show error: “Please select a payment method”	Pass
Place order with COD (Cash on Delivery)	1. Select valid address
2. Choose COD
3. Confirm order	Payment = COD	Order placed successfully	Pass
Place order with wallet or card (prepaid)	1. Select prepaid option
2. Proceed to payment
3. Confirm order	Payment = ***,
WalletBalance = Sufficient	Payment processed, order placed	Pass
Display confirmation screen	1. After placing order	-	Show “Order Placed” with Order ID and estimated delivery	Pass
Send confirmation notification/email	1. Place order	-	Notification and email sent	Pass
Table 56: Unit Testing of place order
e.	Test Case: Login
Test Case ID	AUTH001
Module Name	Authentication/Login Module
Test Title	Unit Test Case for User Login
Pre-condition	User has a registered account
Test Case Summary	Test Steps	Test Data	Expected Result	Status
Open login screen	1. Launch app
2. Navigate to login page	-	Login screen displayed	Pass
Input username/email and password	1. Enter valid username/email and password	Username = user123Password = pass@123	Fields accept input	Pass
Click “Login” button	1. Tap login button	-	Request sent to backend	Pass
Backend checks username existence	1. Backend verifies username	Username = user123	Username found or not	Pass
Backend verifies password	1. Backend compares password	Password = pass@123	Password matches or not	Pass
Backend checks account status	1. Backend checks if account active	Status = Active/Inactive	Active allows login, inactive blocks	Pass
Invalid credentials entered	1. Enter wrong username or password
2. Submit	Username = user123
Password = wrongpass	Error “Incorrect username or password” shown	Pass
Account inactive scenario	1. Attempt login with inactive account	Account status = Inactive	Error “Account inactive, contact support” shown	Pass
Successful login	1. Enter correct credentials
2. Submit	Username = user123Password = pass@123	User authenticated, session/token created	Pass
Redirect to homepage/dashboard	1. On successful login	-	User navigated to home/dashboard screen	Pass
Display welcome message or notifications	1. After login redirection	-	Welcome message or user notifications displayed	Pass
Table 57: Unit Testing of login
 
f.	Test Case: Search Product
Test Case ID	PROD_SEARCH001
Module Name	Product Search
Test Title	Unit Test Case for Product Search Functionality
Pre-condition	User is on app homepage or product browsing page
Test Case Summary	Test Steps	Test Data	Expected Result	Status
Enter search keywords	1. Tap on search bar
2. Enter keyword(s)	Keyword = "shoes"	Text input accepted in search bar	Pass
Submit search query	1. Press “Search” button or submit	Keyword = "shoes"	Query sent to backend search API	Pass
Backend performs search	1. Backend searches products by name, description, tags	Keyword = "shoes"	Backend returns matching product list	Pass
Display search results	1. Display results with images, names, prices	List of matching products	Products displayed sorted by relevance/popularity	Pass
Click product from results	1. Tap on product in results list	Select a product card	Navigates to Product Details view	Pass
Refine search with filters	1. Apply filters like price range, category, rating	Filters: price < $50, 
category = "Footwear"	Results update according to filters	Pass
Table 58: Unit Testing of search product
 
7.7.2 Admin
a.	Test Case: Poster Management (Admin)
Test Case ID	ADMIN_POSTER_001
Module Name	Poster Management
Test Title	Unit Test Case for Admin Poster Management
Pre-condition	Admin is logged into the system
Test Case Summary	Test Steps	Test Data	Expected Result	Status
Search for existing posters	1. Enter keyword(s) in search box
2. Click “Search”	Poster title keywords, dates, or IDs	List of posters matching search criteria is displayed	Pass
Choose action: Add poster	1. Click “Add Poster” button	-	Add Poster form opens	Pass
Upload poster image (Add/Edit)	1. Click upload button
2. Select valid image file (.jpg, .png)	Sample poster image file	Image uploads and preview displays successfully	Pass
Enter poster details (Add/Edit)	1. Fill in poster title, description, start/end date, link URL (optional)	Title: “Summer Sale”
Description: “Up to 50% off”
Dates: 2025-06-01 to 2025-06-30	All fields accept valid input	Pass
Choose action: Edit poster	1. Select poster from list
2. Click “Edit” button	Existing poster	Edit Poster form opens with poster details populated	Pass
Choose action: Delete poster	1. Select poster from list
2. Click “Delete” button	Existing poster	Success popup appears	Pass
Table 59: Unit Testing of poster management
 
b.	Test Case: Category Management (Admin)
Test Case ID	ADMIN_CATEGORY_001
Module Name	Category Management
Test Title	Unit Test Case for Admin Category Management
Pre-condition	Admin is logged into the system
Test Case Summary	Test Steps	Test Data	Expected Result	Status
Search existing categories	1. Enter keyword(s) in search box	Category name keywords	List of categories matching search criteria is displayed	Pass
Choose action: Add category	1. Click “Add Category” button	-	Add Category form opens	Pass
Upload category icon (Add/Edit)	1. Click upload button
2. Select valid icon file (.png, .svg)	Sample category icon file	Icon uploads and preview displays successfully	Pass
Enter category details (Add/Edit)	1. Fill in category name, description (optional)	Name: “Electronics”
Description: “Gadgets and devices”	Fields accept valid input	Pass
Choose action: Edit category	1. Select category from list
2. Click “Edit” button	Existing category	Edit Category form opens with category details populated	Pass
Choose action: Delete category	1. Select category from list
2. Click “Delete” button	Existing category	Success popup appears	Pass
Table 60: Unit Testing of category management
 
c.	Test Case: Subcategory Management (Admin)
Test Case ID	ADMIN_SUBCATEGORY_001
Module Name	Subcategory Management
Test Title	Unit Test Case for Admin Subcategory Management
Pre-condition	Admin is logged into the system
Test Case Summary	Test Steps	Test Data	Expected Result	Status
Filter subcategories by parent category	1. Select a parent category from dropdown/filter	Example parent category: “Electronics”	Subcategory list refreshes showing only subcategories under selected parent	Pass
Search existing subcategories	1. Enter keyword(s) in subcategory search box	Subcategory name keywords	List of subcategories matching search criteria is displayed	Pass
Choose action: Add subcategory	1. Click “Add Subcategory” button	-	Add Subcategory form opens	Pass
Enter subcategory details (Add/Edit)	1. Enter subcategory name
2. Select parent category
3. Fill other optional details	Name: “Smartphones”
Parent Category: “Electronics”	Fields accept valid input	Pass
Choose action: Edit subcategory	1. Select subcategory from list
2. Click “Edit” button	Existing subcategory	Edit Subcategory form opens with subcategory details populated	Pass
Choose action: Delete subcategory	1. Select subcategory from list	Existing subcategory	Success popup appears	Pass
Table 61: Unit Testing of subcategory management
d.	Test Case: Product Management (Admin)
Test Case ID	ADMIN_PRODUCT_001
Module Name	Product Management
Test Title	Unit Test Case for Admin Product Management
Pre-condition	Admin is logged into the system
Test Case Summary	Test Steps	Test Data	Expected Result	Status
Search and filter products	1. Enter product name or keyword in search box
2. Apply filters (category, brand)	Product name: “Smartphone”
Category: “Electronics”	List refreshes showing matching products	Pass
Choose action: Add product	1. Click “Add Product” button	-	Add Product form opens	Pass
Upload product images	1. Upload multiple product images	JPEG/PNG images	Images uploaded and preview displayed	Pass
Enter product details (Add/Edit)	1. Enter product name, description, price, SKU, etc.	Name: “iPhone 15”
Description: “Latest model”
Price: 999.99	Fields accept valid inputs	Pass
Assign category, brand, variants	1. Select category (e.g., Electronics)
2. Select brand
3. Add variants (size, color)	Category: Electronics
Brand: Apple
Variants: Color (Red, Blue)	Variants assigned correctly and displayed	Pass
Choose action: Edit product	1. Select product from list
2. Click “Edit” button	Existing product	Edit Product form opens with product details populated	Pass
Choose action: Delete product	1. Select product from list
	Existing product	Success popup appears	Pass
Table 62: Unit Testing of product management
e.	Test Case: Order Management (Admin)
Test Case ID	ADMIN_ORDER_001
Module Name	Order Management
Test Title	Unit Test Case for Admin Order Management
Pre-condition	Admin is logged into the system
Test Case Summary	Test Steps	Test Data	Expected Result	Status
Filter orders	1. Select filter criteria such as status or date range
2. Click “Apply Filters”	Status: “Pending”
Date: “Last 7 days”	Orders list updates showing matching orders	Pass
Search specific orders	1. Enter order ID or customer name in search box
2. Click “Search”	Order ID: “ORD12345”
Customer: “John Doe”	Orders list shows matching orders	Pass
View order details	1. Click on an order from the list	Selected order ID	Order detail page opens with full order information	Pass
Update order status	1. Change order status dropdown (e.g., Pending → Shipped)	Status: “Shipped”	Status updated on form	Pass
Add tracking information	1. Enter carrier name and tracking number	Carrier: “FedEx”
Tracking No: “1234567890”	Tracking info fields accept input	Pass
Table 63: Unit Testing of order management
 
f.	Test Case: Admin Dashboard Insights
Test Case ID	ADMIN_DASH_001
Module Name	Dashboard Insights
Test Title	Unit Test Case for Admin Dashboard View and Filters
Pre-condition	Admin is logged in
Test Case Summary	Test Steps	Test Data	Expected Result	Status
View Product Insights	1. Observe Product Insights section	-	Shows total products, out-of-stock count, limited stock count, other statuses	Pass
View Order Insights	1. Observe Order Insights section	-	Shows total orders, pending, processed, canceled, shipped counts	Pass
Apply date range filter	1. Select a date range filter (e.g., last 30 days)
2. Apply filter	Date range: last 30 days	Insights update to reflect data within selected date range	Pass
Apply category filter	1. Select category filter (e.g., “Electronics”)
2. Apply filter	Category: Electronics	Insights update to reflect only products/orders within the selected category	Pass
Table 64: Unit Testing of dashboard insights
 
g.	Test Case: Admin Notifications Management
Test Case ID	ADMIN_NOTIF_001
Module Name	Notifications
Test Title	Unit Test Case for Admin Composing and Sending Notifications
Pre-condition	Admin is logged in	
Test Case Summary	Test Steps	Test Data	Expected Result	Status
Compose new notification	1. Click “Compose New Notification”
2. Enter title, description, image URL	Title: “Holiday Sale”
Description: “Get 20% off”
Image URL: valid URL	Notification form accepts inputs	Pass
Select target audience	1. Choose audience (e.g., “All Users”)	Audience: All Users	Audience selection is applied	Pass
Send notification	1. Click “Send” button	-	Notification is sent, success message shown	Pass
Table 65: Unit Testing of admin notification management
 
h.	Test Case: Admin Variant Management (Search, Add, Edit, Delete)
Test Case ID	ADMIN_VARIANT_001
Module Name	Variant Management
Test Title	Unit Test Case for Admin Searching, Adding, Editing, and Deleting Variant Types
Pre-condition	Admin is logged in and variant types exist in the system
Test Case Summary	Test Steps	Test Data	Expected Result	Status
Search variant types	1. Enter search keyword
2. Click “Search”	Keyword: “Color”	Variant list filtered and displays matching variant types	Pass
Add new variant type	1. Click “Add Variant”
2. Enter variant type and options (e.g., Color: Red, Blue)
3. Click “Save”	Variant Type: “Color”
Options: “Red, Blue”	Variant type added successfully, confirmation message shown	Pass
Edit existing variant type	1. Click “Edit” on a variant type
2. Modify variant details
3. Click “Save”	Change options (e.g., add “Green”)	Variant updated successfully, confirmation message shown	Pass
Delete a variant type	1. Click “Delete” on a variant type
2. Confirm deletion	Select variant “Size”	Variant type deleted from the system, success message shown	Pass
Table 66: Unit Testing of variant management
7.8 Integration Testing 
7.8.1 Admin Integration Testing Tables
Table 1: Order Management Integration Testing
No	Test Title	Test Step	Expected Result	Status
1	Filter and view orders	1. Go to "Order Management"
2. Apply filters (date/status)
3. Click search	Orders matching filter criteria are displayed	Pass
2	Update order status	1. View an order
2. Change order status or tracking info
3. Save changes	Status and tracking data updated and visible to users	Pass
3	Search for an order	1. Use search bar
2. Enter order ID or customer email
3. Press enter	Specific order appears in search result	Pass
Table 67: Integration testing of order management
Table 2: Notification and Coupon Integration Testing
No	Test Title	Test Step	Expected Result	Status
1	Send notification	1. Compose message
2. Select audience
3. Send notification	Notification sent and tracked (delivery, opens)	Pass
2	Edit/delete a coupon	1. Edit or delete selected coupon
2. Save or confirm deletion	Coupon is updated or removed from system	Pass
Table 68: Integration testing of notification and coupon
7.8.2 Client Integration Testing Tables
Table 1: Product Browsing and Filtering
No	Test Title	Test Step	Expected Result	Status
1	Filter products	1. Set filters (price, brand)
2. Click "Apply Filters"	Only products matching filters appear	Pass
2	Clear filters	1. Apply filters
2. Click "Clear All"	Product list resets to default view	Pass
3	View product details	1. Click a product from list	Redirect to detail page with all information	Pass
Table 69: Integration testing of product browsing and filtering
Table 2: Cart and Checkout Integration
No	Test Title	Test Step	Expected Result	Status
1	Add product to cart	1. View product
2. Click "Add to Cart"	Product added to cart with correct quantity and price	Pass
2	Apply coupon	1. Enter valid coupon code
2. Apply	Discount is calculated and total price updated	Pass
3	Checkout	1. Review cart
2. Proceed with payment
3. Confirm order	Order placed and confirmation shown	Pass
Table 70: Integration testing of cart and checkout
 
7.9 System Usability Testing
7.9.1 Test Scenario
7.9.1.1 Client-Side Scenario
SoleMates E-Commerce Platform – Client Side Scenarios
Scenario 1 – Register and Login
You are a new customer of the Solemates platform and want to create an account to start shopping. You are required to register yourself by providing your name, email, and password, and then log in using your new account. What would you do to create and log in with your account?
Suggested Test Data:
Name	John Doe
Email	johndoe@example.com
Password	John@123

Scenario 2 – Edit Profile and Manage Address
You wish to edit your profile information such as your phone number and gender. Additionally, you would like to add or update a delivery address for future purchases. What steps would you take to update your profile and save your shipping address?
Suggested Test Data:
Phone	9876543210
Gender	Male
Address	123 Main Street, Pokhara, Nepal

Scenario 3 – Browse Products, Search, and Apply Filters
You want to browse various shoes and accessories, use search to find 'Running Shoes', and apply brand and price filters. What actions would you take to find products efficiently using browse, search, and filters?
Suggested Test Data: 
Search keyword	Running Shoes
Brand Filter	Nike
Price Range Filter 	1000 – 3000 NPR

Scenario 4 – View Product Details 
You wish to check details of a selected product to see its images, descriptions, and available variants. How would you explore the product details?
Suggested Test Data: 
Product Selected	Nike Running Shoes

Scenario 5 – Add to Favourites 
You liked a product and want to add it to your favourites list for future reference. How would you add the product to your favourites?
Suggested Test Data:
Product Selected	Adidas Sneakers

Scenario 6 – Add Products to Cart 
You found a product and want to add it to your cart with a specific size and quantity. What steps would you follow to add the product to the cart?
Suggested Test Data:
Product	Nike Running
Size	42
Quantity	2

Scenario 7 – Update Cart Quantity and Remove Items 
You want to update the quantity of an item in your cart and remove another. How would you manage your cart accordingly?
Suggested Test Data: 
Update Quantity	3
Remove Product	Adidas Sneakers

Scenario 8 – Apply Coupon Codes 
You wish to apply a coupon code at checkout to receive a discount. What actions would you perform to apply both valid and invalid coupon codes?
Suggested Test Data:
Valid Coupon	NEWUSER10
Invalid Coupon	FAKECODE

Scenario 9 – Place an Order (Cash on Delivery) 
You have added products to your cart and wish to complete your purchase using Cash on Delivery. What steps would you take to place your order?
Suggested Test Data: 
Payment Method	Cash on Delivery
Address	123 Main Street, Pokhara

Scenario 10 – Track Order Status 
You want to track the status of your recent order and check the shipment tracking link. What would you do to track your order and view the shipment status?
Suggested Test Data:
Order ID	10045

Scenario 11 – Logout After shopping
You wish to log out from your account to ensure account security. What steps would you follow to log out?

7.9.1.2 Admin-Side Scenario
Solemates E-Commerce Platform – Admin Side Scenarios
Scenario 12 – Admin Login As an admin 
You need to log in to the admin panel to manage the store. What steps would you follow to log in successfully?
Suggested Test Data:
Email	admin@solemates.com
Password	Admin@123

Scenario 13 – View Dashboard Insights 
You wish to view the dashboard insights to monitor stock levels, order summaries, and other key metrics. How would you access and review the dashboard insights?
Scenario 14 – Manage Products (Add, Edit, Delete) 
You need to add new products, update existing product details, and delete discontinued products. What steps would you take to manage products?
Suggested Test Data:
New Product	Puma Sports Shoes
Edit Product	Update price to 2500 NPR
Delete Product	Old Casual Sneakers

Scenario 15 – Manage Categories and Subcategories 
You need to create, edit, and delete categories and subcategories dynamically without code changes. What steps would you take?
Suggested Test Data:
New Category	Sports Shoes
New Subcategory	Marathon Shoes

Scenario 16 – Manage Variants and Variant Types 
You wish to manage product variants like size and color, including adding new options. How would you perform these actions?
Suggested Test Data:
Variant Type	Size
Variant Option	42, 43

Scenario 17 – Manage Posters 
You want to add and update promotional posters shown on the client homepage. How would you upload a new poster and replace an old one?
Suggested Test Data:
Poster Image	banner_new_offer.jpg
Poster Text	"Big Sale This Weekend"

Scenario 18 – Manage Brands 
You wish to manage the brands shown in the store, including adding, editing, and removing brands. What would you do?
Suggested Test Data: 
New Brand	Skechers
Edit Brand	Update Logo
Delete Brand	Old Brand X

Scenario 19 – Manage Orders and Update Tracking 
You need to update the order status from Pending to Shipped and add a tracking URL. What steps would you take?
Suggested Test Data:
Order ID	10045
Tracking URL	https://courier.com/track/10045

Scenario 20 – Create Coupons 
You want to create a new coupon with a fixed discount and expiry date applicable to all products. How would you do it?
Suggested Test Data:
Coupon Code	SUMMER20
Discount	20%
Expiry Date	2024-12-31

Scenario 21 – Manage Coupons 
You wish to edit an existing coupon's discount and delete expired coupons. What steps would you take?
Suggested Test Data:
Edit Coupon	Update to 25%
Delete Coupon	OLD2023

Scenario 22 – Manage Users 
You need to edit user details, deactivate a user, and delete inactive accounts. How would you manage the users?
Suggested Test Data:
Edit User Email	johndoe@example.com
Delete User	userx@example.com
Deactivate User	jane@example.com

Scenario 23 – Send Notifications to Users 
You want to send a promotional notification to all users and track its delivery status. How would you create and send the notification?
Suggested Test Data: 
Title	Mega Sale Description: Flat 30% off on all categories
Image URL	sale_banner.jpg

Scenario 24 – Track Notifications Analytics 
You wish to view the delivery and open rates of the last notification sent. What would you do to check the analytics?
Scenario 25 – Search and Filter Products in Admin Panel 
You need to search for a product using its name and apply stock filters in the admin panel. How would you perform these actions?
Suggested Test Data: 
Search Keyword	Nike Running Shoes
Filter	Out of Stock

Scenario 26 – Filter and Search Orders by Status and Date 
Scenario 27 – Search and Manage Coupons in Admin Panel 
You wish to search for a coupon using its code and edit it from the search results. How would you do this?
Suggested Test Data:
Coupon Code	SUMMER20
New Discount	30%

Scenario 28 – Search and Manage Users in Admin Panel 
You want to search for a user by name or email and deactivate their account. What actions would you take?
Suggested Test Data:
User Email	johndoe@example.com
Action	Deactivate

7.9.2 System Usability Testing Result
Based on the findings presented in Appendix G, the System Usability Scale (SUS) can be calculated to determine the overall usability score for both the inventory management system and the e-commerce platform.
According to Sauro (2011), the SUS score is derived through the following four steps:
1.	For all odd-numbered items, subtract 1 from the user's response.
2.	For all even-numbered items, subtract the user's response from 5.
3.	This process converts all scores to a scale ranging from 0 to 4, where 4 reflects the most favorable response.
4.	Finally, sum all the adjusted scores and multiply the total by 2.5, converting the overall score from a 0–40 scale to a 0–100 scale.
Additionally, as proposed by Alathas (2018), the general guidelines for interpreting SUS scores will be referred to, as outlined in the diagram below. These guidelines will be applied to assess and rate the usability of the developed systems.
 
Table 71: Sus score table
 
7.9.2.1 Client-Side Score
Participant	Q1	Q2	Q3	Q4	Q5	Q6	Q7	Q8	Q9	Q10	Q11	Total	Percentage
1	3	3	3	3	4	4	3	4	3	3	4	36	81.8%
2	4	3	4	4	4	4	4	4	4	4	4	42	95.4%
3	3	3	3	2	3	3	3	4	3	3	3	33	75%
4	4	4	4	4	4	4	3	4	3	4	4	41	93.1%
5	4	4	3	3	4	3	2	3	4	3	3	36	81.8%
Average SUS Score													82%

Grade													B

Adjective Rating													Good
Table 72: Sus client-side score
7.9.2.2 Admin-Side Score
Participant	Q11	Q12	Q13	Q14	Q15	Q16	Q17	Q18	Q19	Q20	Q21	Q22	Q23	Q24	Q25	Q26	Q27	Q28	Total	Percentage
1	3	4	4	3	4	4	3	4	3	4	3	4	4	4	3	3	4	4	65	90.3%
2	3	3	4	3	4	3	3	4	4	4	4	3	3	4	3	4	4	3	62	86.1%
3	3	3	3	2	3	3	3	3	3	3	3	3	3	3	3	3	3	3	54	75%
4	4	4	4	4	4	4	3	4	4	4	3	4	4	4	4	4	4	4	70	97.2%
5	4	3	3	4	4	3	3	3	4	3	3	4	4	3	3	4	4	4	63	87.5%
Average SUS Score																				85%
Grade																				B
Adjective Rating																				Good
Table 73: Sus Admin-side score
 
7.10 User Acceptance Testing (UAT)
User Acceptance Testing (UAT) is the final and critical stage of the software testing process, in which the system is tested directly by the client or intended end-users to ensure that all business requirements and expectations of users are met before the system is deployed into the live production environment. Five user acceptance testing participants were chosen to cover both the administration users and common customers of the inventory management system and e-commerce website for this project.
The remote UAT sessions were conducted using Google Meet, allowing the participants to use the systems in real-time while providing feedback and identifying any discrepancies or issues. The participants received clear scenarios and tasks to accomplish, mimicking actual usage of both systems. During these sessions, users could navigate freely within the platforms and inform them of any functionality, design, or usability issues they found.
Parallel to this, the UAT work was carried out alongside System Usability Testing (SUS) to receive qualitative and quantitative feedback regarding user satisfaction and system performance. The two-route process ensured that functional accuracy and user experience were stringently tested. The observations and impressions accumulated in the UAT process were carefully recorded, and any changes incorporated were discussed with the development team to ensure the systems conform to the client's expectations.
The results of the User Acceptance Testing are fully documented in Appendix H, such as participant comments, problems observed, and their solutions  
7.10.1 UAT Test Cases
7.10.1.1 Client Test Cases of UAT
Testing Date	
Testing Start Time		Testing End Time	
Tester Name	
Client-Side Mobile Application
Test Module	Test Scenario	Status	Comments
Register/Login	1. Able to register with valid email & password.		
	2. Able to log in using correct credentials.		
	3. Unable to register with existing email.		
	4. Unable to log in with invalid credentials.		
	5. Able to recover password via "Forgot Password".		
	6. System rejects weak passwords (e.g., only numbers).		
	7. Error shown if required fields left blank.		
	8. Able to stay logged in when 'Remember Me' checked.		
	9. Automatically logged out after inactivity timeout.		
Browse Items	1. Able to browse all products.		
	2. Able to filter products by category, price, and brand.		
	3. Able to search for products by keyword.		
	4. Able to view product images, variants, and details.		
	5. Error message shown if no search result found.		
	6. Able to add items to wishlist and remove from it.		
	7. Products with zero stock show "Out of Stock" label.		
Cart Management	1. Able to add items to the shopping cart.		
	2. Able to increase/decrease item quantity in the cart.		
	3. Able to remove items from the cart.		
	4. System prevents adding more than available stock.		
	5. Able to clear entire cart.		
	6. Prices automatically update on quantity change.		
Checkout/Orders	1. Able to place an order successfully with payment options.		
	2. Able to apply valid coupons during checkout.		
	3. Error shown if invalid/expired coupon applied.		
	4. Able to cancel orders if in "Pending" status.		
	5. Error shown if trying to checkout with empty cart.		
	6. Able to select saved address or add new one at checkout.		
	7. Order confirmation email received after successful order.		
	8. Able to view order details, invoice, and status updates.		
Notifications	1. Able to receive push/in-app notifications sent by admin.		
	2. Able to view order status change notifications.		
	3. Able to see notification history.		
Account Management	1. Able to view and update profile info and password.		
	2. Able to add/manage saved addresses.		
	3. System shows validation errors for invalid inputs.		
	4. Able to delete account after confirmation.		
	5. Security confirmation required when changing email or password.		
Table 74: UAT test cases client-side

7.10.1.2 Admin Test Cases of UAT
Admin-Side Web-Application
Test Module	Test Scenario	Status	Comments
Login/Dashboard	1. Able to log into admin panel.		
	2. Able to see product, order, and sales insights.		
	3. Able to filter dashboard data by date range or category.		
	4. System shows error if invalid credentials entered.		
	5. System logs out admin after inactivity timeout.		
	6. Able to see total customers, products, and pending orders stats.		
	7. Admin activity log shows login time, order update, etc.		
Category Management	1. Able to add new category with details and icon.		
	2. Able to edit existing category details.		
	3. Able to delete category after confirmation pop-up.		
	4. System prevents duplicate category name.		
	5. Error shown if adding empty category name.		
Subcategory Management	1. Able to add/edit/delete subcategories.		
Product Management	1. Able to add new products with images, variants, price, and description.		
	2. Able to edit product details and images.		
	3. Able to delete product after confirmation.		
	4. System validates mandatory fields while adding products.		
	5. Error shown if invalid pricing or stock entered.		
Order Management	1. Able to view all orders and filter by status/date.		
	2. Able to update order status (Pending, Shipped, Delivered, Cancelled).		
	3. Able to assign tracking number to orders.		
	4. System prevents updating order to 'Delivered' without tracking info.		
	5. Able to print or download order invoice.		
Coupon Management	1. Able to add new coupon codes with details and validity dates.		
	2. Able to edit existing coupon details.		
	3. Able to delete coupons after confirmation.		
	4. System prevents duplicate coupon codes.		
	5. System shows usage count per coupon.		
Brand Management	1. Able to add/edit/delete brands.		
Variant Type Management	1. Able to add new variant type (size, color, etc.).		
	2. Able to edit existing variant types.		
	3. Able to delete variant type after confirmation.		
	4. System prevents duplicate variant type names.		
Notification Management	1. Able to create and send push notifications to clients.		
	2. Able to see notification history and delivery status.		
General Settings	1. Able to configure site settings (logo, support email, etc.).		
	2. Able to manage payment gateways and API keys.		
	3. System shows error if invalid API key entered.		
Table 75: UAT test case for admin-side
 
7.10.2 Improvement from UAT
1. Notification Sending Failure (Admin-Side)
The testers encountered an error while sending push notifications from the admin panel, specifically an "Instance of HttpStatus" error. This issue occurred due to the missing REST API key in OneSignal, which was not configured properly after a recent update. To resolve this, I consulted seniors in the field and will integrate the correct API key to ensure notifications are delivered successfully.
2. Coupon Application Failure (Client-Side)
During checkout, some testers reported that applying coupons failed intermittently. After debugging, it was found that the issue was related to validation logic in the coupon expiry check. The problem has since been fixed, and coupons now apply correctly when valid.
3. "Remember Me" Functionality Not Working (Client-Side Login)
Testers noted that the "Remember Me" option during login did not retain user sessions as expected. Upon review, it was decided to remove this feature temporarily due to security concerns and session management complexities. Future implementations will include a more secure auto-login mechanism.
4. Order Tracking Issue (Mobile Client-Side)
Some testers faced errors while tracking orders, which stemmed from a WebView Android package compatibility issue. Since this requires deeper technical adjustments, I will investigate further and implement a fix to ensure seamless order tracking for users.
 
7.12 Summary 
The testing process for my e-commerce final year project encompassed four key phases: Unit Testing, Integration Testing, System Usability Testing (SUT), and User Acceptance Testing (UAT). Unit testing verified individual components like authentication, cart management, and payment processing, uncovering minor bugs such as coupon validation errors, which were promptly fixed. Integration testing ensured seamless interaction between modules, resolving synchronization issues like delayed stock updates during checkout. System Usability Testing focused on user experience, leading to improvements in navigation and mobile responsiveness. Finally, UAT involved five testers evaluating both client and admin functionalities, with most test cases passing successfully. However, critical issues like admin notification failures (due to OneSignal API misconfiguration), coupon application errors, and Android WebView order tracking problems were identified, with some resolved and others pending fixes.
Overall, the testing phases provided valuable insights into the application’s functionality, performance, and usability. While core features like registration, product browsing, and checkout work reliably, challenges remain in third-party integrations and edge-case scenarios. The feedback from UAT and usability testing has been instrumental in refining the system, and further optimizations—particularly in notification delivery and mobile compatibility—will be prioritized before final deployment. This structured testing approach ensures a robust, user-friendly e-commerce platform ready for real-world use.
 
Chapter 8 – Conclusions and Recommendations
8.1 Conclusions
The SoleMates e-commerce platform successfully addresses key challenges in Nepal’s online retail market by offering a user-friendly, sustainable, and secure shopping experience for branded footwear and apparel. By leveraging Flutter for cross-platform compatibility and Node.js with MongoDB for scalable backend operations, the platform ensures seamless performance while integrating trusted payment gateways like eSewa and Khalti. A strong emphasis on ethical consumption aligns with SDG 12 (Responsible Consumption and Production), setting SoleMates apart from competitors like Daraz and SastoDeal. User testing confirmed high satisfaction in navigation, checkout efficiency, and trust-building features such as verified reviews and transparent return policies. However, while the prototype demonstrates strong potential, geographical limitations, resource constraints, and market competition present ongoing challenges. Future enhancements including AI-driven personalization, blockchain-based supply chain transparency, and expanded product categories—can further solidify SoleMates as a leader in sustainable e-commerce.
8.2 Limitations
1.	Geographical and Infrastructure Barriers: While SoleMates performs well in urban areas, limited internet access and unreliable delivery networks in rural Nepal restrict its reach. Expanding logistics partnerships and optimizing last-mile delivery solutions will be crucial for nationwide adoption.
2.	Resource and Time Constraints: Due to budget and development timelines, advanced features like AI recommendations, dynamic pricing, and chatbot support were excluded from the MVP. Future iterations should prioritize these to enhance user engagement.
3.	Market Competition and Trust Building: Competing with established platforms like Daraz requires aggressive marketing and customer incentives. Since trust in new e-commerce brands takes time, SoleMates must invest in user education, secure payment assurances, and influence collaborations to accelerate adoption.
 
4.	Sustainability Implementation Challenges: Sourcing affordable, verified eco-friendly products remains difficult due to limited local suppliers. Additionally, sustainable packaging and carbon-neutral shipping options increase operational costs, requiring innovative pricing strategies.

8.3	Future Work
1.	Diversify Product Offerings: Expanding into electronics, home goods, and locally crafted items will attract a broader audience. Partnering with Nepali artisans for exclusive handmade collections can further differentiate SoleMates in the market.
2.	Integrate Advanced Technologies: AI and machine learning can personalize recommendations and optimize inventory management. Blockchain can enhance transparency in sourcing, while AR-powered virtual try-ons may reduce return rates by improving purchase confidence.
3.	Enhance User Engagement: Introducing loyalty rewards, referral programs, and gamified shopping experiences (e.g., sustainability challenges) can boost retention. A community forum for reviews and styling tips may also foster brand loyalty.
4.	Improve Logistics and Accessibility: Collaborating with regional logistics providers and establishing urban pickup hubs will reduce delivery costs and delays. Exploring cash-on-delivery (COD) optimizations can also cater to users hesitant about digital payments.
5.	Strengthening Sustainability Initiatives: Implementing carbon-offset options at checkout and recycling incentives (e.g., discounts for returned used items) can reinforce SoleMates’ eco-friendly mission while appealing to environmentally conscious shoppers.
6.	Explore Regional and Global Expansion: After stabilizing operations in Nepal, SoleMates could expand to Bhutan and Bangladesh, where similar e-commerce gaps exist. Additionally, global shipping support would cater to the Nepali diaspora, opening new revenue streams.
 
Appendices
Appendix A: Poster
 
Figure 116: Poster
Appendix B: Gantt Chart
 
Figure 117: Gantt Chart of FYP
 
Appendix C: PPF Title Registration 
 
Figure 118: Cover page of proposal
 
 
 
 
 
 
 
 
 
  
Appendix D: Sample Consent Form on Usability Testing and UAT
#PARTICIPANT 1 


#PARTICIPANT 2
 
 
Appendix E: Sample of User Satisfaction Survey Form – Already Filled
#PARTICIPANT 1
  
   
  







#PARTICIPANT 2
  
  
 
   
Appendix E: Results of UAT 
#PARTICIPANT 1
 
 
 
 
 
 
 















#PARTICIPANT 2
 
  
 
  
Appendix F: Ethics
 
  
 
 
  
Appendix G: Log Sheet of IR
 
Figure 119: Meeting 1 log
 
Figure 120: Meeting 2 log
 
 
Figure 121: Meeting 3 log
 
Figure 122: Meeting 4 log
 
 
Figure 123: Meeting 1 log of fyp
 
Figure 124:Meeting 2 log of fyp
 
Figure 125: Meeting 3 log of fyp
 
Figure 126: Meeting 4 log of fyp
Appendix H: MongoDB display of Solemates
 
Figure 127: project in mongodb
 
References
1.	Nugroho, D. (2024). MARKET SEGMENTATION ANALYSIS AND POSITIONING TO INCREASE PRODUCT COMPETITIVENESS IN THE GLOBAL MARKET. International Journal of Social Service and Research. https://doi.org/10.46799/ijssr.v4i8.888.
2.	Hooley, G., Greenley, G., Fahy, J., & Cadogan, J. (2001). Market-focused Resources, Competitive Positioning and Firm Performance. Journal of Marketing Management, 17, 503 - 520. https://doi.org/10.1362/026725701323366908.
3.	Wilson, J., & Chermak, S. (2012). Product counterfeiting: exploring the risk. International Journal of Comparative and Applied Criminal Justice, 36, 245 - 247. https://doi.org/10.1080/01924036.2012.727646.
4.	Rahm, E. (2014). Discovering product counterfeits in online shops. Journal of Data and Information Quality (JDIQ), 5, 1 - 3. https://doi.org/10.1145/2629605.
5.	Raju, J., Srinivasan, V., & Lal, R. (1990). The Effects of Brand Loyalty on Competitive Price Promotional Strategies. Management Science, 36, 276-304. https://doi.org/10.1287/MNSC.36.3.276.
6.	Corstjens, M., & Lal, R. (2000). Building Store Loyalty through Store Brands. Journal of Marketing Research, 37, 281 - 291. https://doi.org/10.1509/jmkr.37.3.281.18781.
7.	Napoli, J., Dickinson-Delaporte, S., & Beverland, M. (2016). The brand authenticity continuum: strategic approaches for building value. Journal of Marketing Management, 32, 1201 - 1229. https://doi.org/10.1080/0267257X.2016.1145722.
8.	Liedtka, J. (2008). Strategy Making and the Search for Authenticity. Journal of Business Ethics, 80, 237-248. https://doi.org/10.1007/S10551-007-9415-3.
9.	Zhou, Z., Luo, B., & Tang, T. (2018). Corporate Social Responsibility Excites ‘Exponential’ Positive Employee Engagement: The Matthew Effect in CSR and Sustainable Policy. Corporate Social Responsibility and Environmental Management, 25, 339-354. https://doi.org/10.1002/CSR.1464.
10.	Saputra, C., Anthonie, R., & , H. (2024). Corporate Social Responsibility and International Business: A Study of the Impact on Firm Performance. International Journal of Educational Research. https://doi.org/10.62951/ijer.v1i2.27.
11.	Tomșa, M., Romonți-Maniu, A., & Scridon, M. (2021). Is Sustainable Consumption Translated into Ethical Consumer Behavior?. Sustainability. https://doi.org/10.3390/SU13063466.
12.	Arman, S., & Mark‐Herbert, C. (2024). Ethical Consumption: A Review and Research Agenda. International Journal of Consumer Studies. https://doi.org/10.1111/ijcs.13079.
13.	Ray, S., & Nayak, L. (2023). Marketing Sustainable Fashion: Trends and Future Directions. Sustainability. https://doi.org/10.3390/su15076202.
14.	Woodside, A., & Fine, M. (2019). Sustainable fashion themes in luxury brand storytelling: The sustainability fashion research grid. Journal of Global Fashion Marketing, 10, 111 - 128. https://doi.org/10.1080/20932685.2019.1573699.
15.	Camilleri, M., Cricelli, L., Mauriello, R., & Strazzullo, S. (2023). Consumer Perceptions of Sustainable Products: A Systematic Literature Review. Sustainability. https://doi.org/10.3390/su15118923.
16.	Buerke, A., Straatmann, T., Lin-Hi, N., & Müller, K. (2017). Consumer awareness and sustainability-focused value orientation as motivating factors of responsible consumer behavior. Review of Managerial Science, 11, 959-991. https://doi.org/10.1007/S11846-016-0211-2.
17.	Esan, O., Ajayi, F., & Olawale, O. (2024). Supply chain integrating sustainability and ethics: Strategies for modern supply chain management. World Journal of Advanced Research and Reviews. https://doi.org/10.30574/wjarr.2024.22.1.1259.
18.	Yusuf, Y., Hawkins, A., Musa, A., & El-Berishy, N. (2014). Ethical supply chains: analysis, practices and performance measures. International Journal of Logistics Systems and Management, 17, 472. https://doi.org/10.1504/IJLSM.2014.061016.
19.	Karat, J., Vanderdonekt, J., Karat, C., & Blom, J. (2004). Designing Personalized User Experiences in eCommerce. , 5. https://doi.org/10.1007/1-4020-2148-8.
20.	Ghansawant, S., Kumbhar, G., Kawase, P., & Sharma, P. (2023). The Power of Personalization: Enhancing User Experience in E-commerce. International Journal For Multidisciplinary Research. https://doi.org/10.36948/ijfmr.2023.v05i06.8899.
21.	Syahnur, H. (2024). Leveraging Technology and Innovation for Effective E-Business Management. Advances in Business & Industrial Marketing Research. https://doi.org/10.60079/abim.v2i2.285.
22.	Nagaty, K. (2019). New Advances in E-Commerce. Advances in Marketing, Customer Relationship Management, and E-Services. https://doi.org/10.4018/978-1-5225-7766-9.ch022.
23.	Lezcano, I., Romero, J., Gonzalez, L., Zacarías, F., Dominguez, M., & Centurión, C. (2023). MOBILE APPLICATIONS AND THEIR IMPORTANCE IN THE COMMERCIAL WORLD. Revista Gênero e Interdisciplinaridade. https://doi.org/10.51249/gei.v4i05.1705.
24.	Tairov, I., & Donchev, I. (2022). Mobile Applications Use for Business Growth. 2022 IEEE 9th International Conference on Problems of Infocommunications, Science and Technology (PIC S&T), 223-226. https://doi.org/10.1109/PICST57299.2022.10238668.
25.	W, A., & S, S. (2024). THE EMERGING TECHNOLOGIES OF DIGITAL PAYMENTS AND ASSOCIATED SERVICES. ShodhKosh: Journal of Visual and Performing Arts. https://doi.org/10.29121/shodhkosh.v5.i3.2024.2032.
26.	Kou, W. (2003). Payment Technologies for E-Commerce. , I-IX, 1-334. https://doi.org/10.1007/978-3-662-05322-5.
27.	Islam, D., Meier, F., Aditjandra, P., Zunder, T., & Pace, G. (2013). Logistics and supply chain management. Research in Transportation Economics, 41, 3-16. https://doi.org/10.1016/J.RETREC.2012.10.006.
28.	S, U. (2022). Logistics and Supply Chain Management. . https://doi.org/10.47715/jpc.b.978-93-91303-39-6.
29.	Cooper, M., Lambert, D., & Pagh, J. (1997). SUPPLY CHAIN MANAGEMENT -- MORE THAN A NEW NAME FOR LOGISTICS. The International Journal of Logistics Management, 8, 1-14. https://doi.org/10.1108/09574099710805556.
30.	PwC. (2020). Consumer intelligence series: Protect.me. https://www.pwc.com/us/en/services/governance-cybersecurity-data-privacy/publications/consumer-intelligence-series-protect-me.html
31.	Statista. (2021). Online shopping behavior by age group. https://www.statista.com/statistics/271450/online-shopping-behavior-by-age-group/
32.	Bain & Company. (2020). The loyalty economy: A new framework for customer engagement. https://www.bain.com/globalassets/noindex/2020/bain_report_the_loyalty_economy.pdf
33.	McKinsey & Company. (2020). The future of sustainability: How brands can build a sustainable business. https://www.mckinsey.com/business-functions/sustainability/our-insights/the-future-of-sustainability
34.	eMarketer. (2021). U.S. mobile payments forecast 2021. https://www.emarketer.com/content/us-mobile-payments-forecast-2021
35.	Epsilon. (2018). The power of me: The impact of personalization on marketing performance. https://us.epsilon.com/powerofme
36.	Statista. (2021). Share of e-commerce sales worldwide from mobile devices from 2016 to 2021. https://www.statista.com/statistics/272391/share-of-e-commerce-sales-worldwide-from-mobile-devices/
37.	eMarketer. (2021). Global e-commerce 2021: Trends and opportunities. https://www.emarketer.com/content/global-ecommerce-2021
38.	Kotler, P., & Keller, K. L. (2016). Marketing management. Pearson. https://www.pearson.com/store/p/marketing-management/P100000508222
39.	Porter, M. E. (2008). The five competitive forces that shape strategy. Harvard Business Review. https://hbr.org/2008/01/the-five-competitive-forces-that-shape-strategy
40.	Statista. (2021). E-commerce market size worldwide from 2014 to 2025. https://www.statista.com/statistics/379046/worldwide-retail-e-commerce-sales/
41.	Statista. (2021). E-commerce in Nepal - Statistics & Facts. Statista.com
42.	Sharma, A. (2020). The Rise of E-commerce in Nepal: Trends and Challenges. https://www.nepalbusinessreview.com
43.	SastoDeal. (2021). SastoDeal Official Website. https://www.sastodeal.com
44.	Daraz. (2021). Daraz Official Website. https://www.daraz.com.np
45.	OkDam. (2021). OkDam Official Website. https://www.okdam.com
46.	Anderson, D. J. (2010). Kanban: Successful Evolutionary Change for Your Technology Business. Blue Hole Press. https://www.researchgate.net/publication/228737525_The_Cape_Khoekhoe_the_appearance_of_a_people_presumed_dead
47.	Larman, C., & Vodde, B. (2009). Scaling Lean & Agile Development: Thinking and Organizational Tools for Large-Scale Scrum. Addison-Wesley. https://www.researchgate.net/publication/220691109_Wavelets_Tools_for_Science_and_Technology
48.	Schwaber, K., & Beedle, M. (2001). Agile Software Development with Scrum. Prentice Hall.https://www.researchgate.net/publication/220668892_Generalized_Networks_The_Theory_of_Preprocessing_and_an_Empirical_Analysis
49.	Sutherland, J., & Schwaber, K. (2013). The Scrum Guide. Scrum Alliance. Retrieved from https://scrumguides.org/scrum-guide.html.
50.	Beck, K., Beedle, M., van Bennekum, A., Cockburn, A., Cunningham, W., Fowler, M., ... & Jeffries, R. (2001). Manifesto for Agile Software Development. Agile Alliance. https://agilemanifesto.org/




