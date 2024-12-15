# EvenTrack Mobile App
Summary of Requirements and Goals
The goal of EvenTrack was to develop a functional mobile app that simplifies event tracking for users. The app was designed to address the need for an intuitive tool that allows users to create, edit, and view events while providing SMS notifications as reminders. By focusing on user-centered design principles, the app aimed to deliver a seamless, easy-to-navigate experience that makes event management accessible and efficient.

Screens & Features
--
To meet user needs, several key screens and features were implemented:

Login Screen: Ensured secure and simple user access.
Event List Screen: Displayed events in an organized format using a GridView.
Event Creation/Editing Screen: Allowed users to add or modify events with essential input fields.
SMS Notification Feature: Sent reminders to users based on their event schedule.
The UI was designed with simplicity and usability in mind, using clean layouts, logical grouping of features, and a consistent visual hierarchy. The RelativeLayout and GridView components ensured responsiveness across devices, and intuitive navigation helped users interact with the app effortlessly. These design choices contributed to a successful, user-friendly interface.

Coding Process & Techniques
--
To code the app, I broke the development process into smaller, manageable tasks:

I began with core functionality in the .java files, implementing event creation, editing, and SMS integration one step at a time.
I used XML layouts for visual design, ensuring the UI was responsive and aligned with user-centered design principles.
Debugging played a significant role in refining features, particularly while handling permissions and integrating SMS notifications.
This modular approach allowed me to test and build the app iteratively. Moving forward, I will continue using this strategy to tackle more complex applications, ensuring maintainability and efficient debugging.

Testing Process
--
Testing was conducted throughout the development process to ensure the code’s functionality:

I tested individual features like event creation, SMS notifications, and the display of events.
Permissions, particularly for SMS functionality, were verified to ensure they operated correctly across devices.
Testing is critical because it identifies errors early and ensures a smooth user experience. This process revealed issues with permission handling, which I was able to resolve by thoroughly reviewing the manifest file and debugging code dependencies.

Overcoming Challenges
--
One of the key challenges I faced was synchronizing the .java, XML, and manifest files to ensure everything worked together seamlessly. Initially, managing SMS permissions and integrating the notifications feature was complex, but I overcame this by breaking the problem into smaller tasks and testing each step. This experience taught me the importance of patience and modular development when tackling challenging features.

Areas of Success
--
The successful implementation of SMS notifications stands out as a highlight of the app. This feature demonstrated my ability to integrate hardware permissions and functionality into the app while keeping user needs in focus. Additionally, the clean, user-friendly UI design reflects my growing skills in visual design and layout optimization.

Tech Stack
--
Platform: Android
Language: Java
Tools: Android Studio, XML, SensorManager (for hardware sensor integration)

Purpose
--
EvenTrackApp simplifies event tracking by combining clean design and functionality, ensuring users never miss out on important moments.
