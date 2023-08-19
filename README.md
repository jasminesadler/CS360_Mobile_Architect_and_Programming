# CS360_Mobile_Architect_and_Programming

1. Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

Your app should work for users that both do and do not have accounts. This means you should focus on the following functionality:
The app should check the username and password against the database when the user attempts to log in.
If the user has never logged into the application before, the user should be able to create a new login and password. The application needs to save these to a table in the database. The SQLite database you create will depend on the option you selected in Project One and will store inventory items. Any information needed for your application to function correctly should be held in the database, but remember you are only creating the shell for the database so its contents can later be populated by a user. Note that you will need tables in the database to store user information when it is not being displayed in the grid. This database will be persistent so no user information is lost when the app is closed. 
Create: The user should be able to add items to a database.
Delete: The user should be able to remove items from a database.
Update: The user should be able to change the value associated with individual database items (e.g. the number of a specific item in an inventory or the date of an event).
Read: The user should be able to view all of the database items displayed as a grid.
If the user grants permissions, the application should send alerts to the user as SMS messages. The alerts correspond to the specific notification trigger of the application you chose (low inventory, an upcoming event, or reaching a goal weight).
If the user denies permission, then the rest of the application should still continue to function without the SMS messaging notification feature.

2. What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?

There needed to be a login screen, a screen for the inventory with a grid to hold all the item information, and a screen for accepting or denying text messages. The designs needed to be simple for the users and I had to make sure there wasn't too much going on with one screen. Also, the user needed to be able to easily opt out of messages and for the app to still work along with making a new account if it was needed. The app meet all these needs in a way that was simple and user-friendly. 

3. How did you approach the process of coding your app? What techniques or strategies did you use? How could those be applied in the future?
How did you test to ensure your code was functional? Why is this process important and what did it reveal?

I made sure that my code was organized and simple. This was done by making sure each page had its own file. I made sure everything was working properly by fixing the errors and suggested changes and then running the code to make sure everything was working.

4. Considering the full app design and development process, from initial planning to finalization, where did you have to innovate to overcome a challenge? In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?

The biggest challenge for me was creating the grid and making sure all the items could be deleted, updated, added, and edited. Where I showed my skill was the main login page. This page consisted of a lot of different components that had to work all together. 
