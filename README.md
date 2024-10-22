# Armando Gomez
# CS-360-Mobile-Architect-Programming


1. Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

The Sparkys Advanced Auto app aimed to simplify inventory management for auto parts stores by offering a user-friendly solution for tracking stock levels and ensuring staff are promptly informed of important 
updates via SMS alerts. The application was also created with user friendliness in mind to make sure that clerks working in settings could easily navigate and utilize it without requiring extensive training. 

2. What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?

The application included screens such as a summary of items in stock and forms for adding and editing inventory items, along with SMS notification preferences for receiving low stock alerts via text message 
notifications on users phones or devices. The design of each screen was user-friendly with layouts and easy navigation to enable users to navigate through important features effortlessly. Large buttons that were
clear and simple to read were incorporated along, with color combinations to make it easier for users to use the app without having to strain their minds too much when performing tasks like adding new items to
the inventory or sending out alerts. The design decisions were crafted considering the users needs in mind and emphasizing simplicity and functionality. In a busy work setting. The user interface proved effective
by enabling users to engage with the application and reducing the number of taps required to carry out key tasks. 

3. How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?

The process of coding followed a step-by-step method where I began by working on tasks like creating the inventory list and then progressed to implementing advanced functions like SMS alerts and handling 
databases efficiently using object-oriented programming (OOP). By organizing the code based on OOP principles, I made sure it was structured in a way that allowed for maintenance and modularity. Additionally, I 
also employed strategies like dividing features into smaller units for testing purposes. This approach can be applied in projects to make sure that functionalities are developed gradually and are simpler to test
and enhance as the application expands over time. 

4. How did you test to ensure your code was functional? Why is this process important, and what did it reveal?

During the development phase, I carried out unit testing to confirm that every feature functioned correctly after being implemented in the codebase. Automated tests were used to validate the functionalities,
such as the inventory alert and database modifications, were functioning as intended. This testing phase is crucial as it detects bugs early on in the development process before they escalate into significant
problems. Additionally, it identified logical flaws in data processing and highlighted instances where permissions for SMS alerts needed to be managed with greater caution to ensure seamless operation across 
various versions of Android. 

5. Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?

Dealing with database upgrades posed a hurdle as we had to ensure user data remained intact throughout the process. This became especially challenging when the app started crashing due to the addition of columns
to the database. To tackle this issue, I devised a solution by incorporating migration logic into the onUpgrade() method. This approach enabled me to introduce columns without wiping out the existing table 
structure. Such innovation in managing the database schema was crucial to safeguarding data integrity while paving the way for enhancements to the app's functionality. 

6. In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?

I excelled in setting up the inventory management system by developing a user-friendly interface for adding and editing inventory items in a grid layout format. This project showcased my skill in connecting a 
database with the user interface while prioritizing performance and user friendliness. The SMS alert system for inventory levels highlighted my expertise in managing Android permissions and telecommunication 
features to provide users with timely updates without unnecessary complications. 



