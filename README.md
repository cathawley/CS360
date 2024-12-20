# CS360

>Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?


 The event tracker app's requirements were that the app needed to display user-entered database objects in a grid. For the events, title, date, and time made the most sense as data fields for the object. The database needed to have CRUD functions. The other requirement was to prompt the user for SMS Notification permissions, so that the day of the event the app could send the user a text message reminding them about the event.

>What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?

 I needed a login screen where the user could create an account and log in, a main screen to display the grid of events, and a third screen to add or update event details. I made use of the intuitive design where clicking on an object allowed you to do the most sensible function for that object (in this case, viewing and editing the details were possible from the same screen). I also used the floating action button for the "add new" function. I ensured the screens were simple and sleek, and I made buttons stand out by using contrasting colors.

>How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?

I made use of the repository pattern mainly, both for the login database and the event database. This pattern makes a lot of sense for this type of app. Using patterns in this way rather than "reinventing the wheel" as they say is a good technique for future coding projects.

>How did you test to ensure your code was functional? Why is this process important, and what did it reveal?

I was consistently testing my code. Toward the end manual testing got repetitive, as I wanted to ensure adding and changing features did not harm already-tested features, so I had to do a lot of repeat tests. I also cleared the cache before most tests, so that I could test the application from new, with a blank database, to find any bugs that would only occur for first-time users. I found a lot of issues in the way, issues with specific strings of actions such as creating exactly three events, deleting the second, and trying to view the third.

>Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?

My most innovative step was creating the UI for the Main Activity, the grid screen. I had to play around with my initial design a lot to make something that felt intuitive without looking visually cluttered. Rather than adding an edit button for each event entry, I used the event itself as the edit button, which makes the UI look a lot more professional.

>In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?

I think for me that moment was passing queries from my MainActivity into my EventRepository methods, and taking that output from the MainActivity into DetailsActivity to populate all of the fields of a specific event. This class (95% of my way into my CS major) was where something finally clicked for me and I felt like I mastered the passing of arguments into methods to get return values.
