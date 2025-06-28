# Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

This project focused on designing and developing a mobile application to help users log their weight, set target goals, and receive motivational feedback as they progress on their wellness journeys. The primary user need this app addresses is providing a simple, private, and consistent tool for individuals who want to track their weight and stay encouraged by seeing progress toward a goal. Rather than overwhelming users with data or distractions, this app emphasizes clarity, ease of use, and a celebration of milestones.


# What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?

To support these user needs, several screens and features were developed, including a weight entry form, a RecyclerView for displaying past logs, a goal-setting interface, and logic to notify users with a positive toast or optional SMS when their weight meets their goal. The UI components were designed using a user-centered approach, ensuring that actions like entering data or setting a goal are quick, accessible, and free from unnecessary steps. The layout is clean and minimal, making the app usable for a wide range of users, even those less familiar with technology.


# How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?

Coding the app involved iterative problem-solving. I used structured planning to map each feature to its associated logic, gradually building from basic input handling to database integration and permission checks. I prioritized modular design and clear variable naming to maintain readability and reduce potential bugs. Techniques like step-by-step testing, using SharedPreferences to store goal weight and phone data, and validating input were strategies that helped the app function predictably. These techniques, especially incremental testing and managing user input cleanly—are strategies I’ll absolutely reuse in future projects.


# How did you test to ensure your code was functional? Why is this process important, and what did it reveal?

Testing was done continuously throughout development, using both emulator testing and manual walkthroughs of key user flows. This process helped catch issues early—such as incorrect string parsing or runtime permission gaps and ensured that the logic around goal checking and SMS alerts worked exactly as intended. Testing also revealed opportunities to simplify logic and improve feedback messages to users.


# Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?

Throughout the entire project, one major challenge was attempting to integrate a visual celebration effect using a third-party library (Konfetti). After a prolonged troubleshooting effort, I ultimately chose to prioritize app stability and usability over a non-essential effect. That decision reflected an important lesson: sometimes innovation also means knowing when to pivot and focus on what brings the most value to the user. The result is an app that works reliably and does what it promises.


# In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?

I’m particularly proud of the way I handled goal logic, storage, and conditional feedback. Building a seamless experience that reacts to user milestones with optional SMS motivation required integrating multiple components—databases, shared preferences, input validation, and Android permission handling. This project helped me bring everything together in a way that I feel confident reflects my progress in mobile development and user-centered thinking.
