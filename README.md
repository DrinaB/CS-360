# CS-360


### Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

The Weight Tracking App was developed to help users log their daily weight, set and edit personal weight goals, and receive an SMS notification when they reached their target. It addresses the need for a simple, private, and user-friendly way to track progress toward a health or fitness goal without requiring an internet connection or account login.

---

### What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?

The app included three main screens: a login screen, a history screen for viewing and adding weight entries, and an SMS screen for permission handling and notifications. The UI used clear labels, accessible input fields, and straightforward navigation to support ease of use. Designs were successful because they avoided clutter, used vertical scrolling for accessibility, and only displayed essential features.

---

### How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?

I broke the app into multiple Java classes with clear responsibilities, used SQLite for persistent data, and applied consistent naming and inline comments to keep the code organized. I also tested frequently in the emulator. These strategies made the code easier to manage and debug, and they can be applied in future apps that need local storage, login functionality, or dynamic UI updates.

---

### How did you test to ensure your code was functional? Why is this process important, and what did it reveal?

I tested each component using the Android Emulator and relied on Logcat for debugging. I also inserted log messages to confirm that code blocks were executed as expected. This process was important to catch errors early and revealed edge cases like permission denial and invalid input that needed better handling.

---

### Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?

One major challenge was implementing SMS notifications only when the user reached a specific goal. I solved this by adding a goal weight input and creating logic to compare each new entry against the goal. This feature improved user engagement and demonstrated how to integrate system-level features like SMS securely and effectively.

---

### In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?

I was especially successful with the login and goal notification features. The login system showed my understanding of data validation and SQLite integration, while the SMS notification required permission handling and real-time conditional logic, which demonstrated my ability to combine backend logic with user-facing functionality.
