# *Unit 3 Project: Mai's Art Gallery*
<img width="1228" alt="Screen Shot 2023-02-13 at 21 54 56" src="https://user-images.githubusercontent.com/105724334/218463838-c55965ba-c0af-4c78-a6e9-860a7dd9814e.png">

###### Vincent Van Gogh Exhibition in Dublin, Unknown [^1]

## Criteria A: Planning
### Problem Definition:
Mai is a wealthy art enthusiast who constantly purchases expensive and rare art pieces for her personal gallery. However, considering the number of artworks she has bought, she no longer knows how many she owns nor their respective origins! She is in immediate need of a digital gallery that will allow her to concisely keep track of all of the art works she owns. In addition, Mai requires the app to be secured through a login system, for the data to be stored in a dataset, and for the user interface to be clear and concise. 
 
### Success Criteria:
1. The application must have a secure registration and login system.
2. The user will be able to input all attributes (title, artist, date, and description of the art piece) which will be stored in the database through the interface.
3. The user will have the capacity to search for art pieces by title, artist, and/or date. 
4. The application will allow the user to view all values stored in the database. 
5. The application must encrypt the user’s password in the local SQL database.
6. The application must contain a login screen, registration screen, home screen, screen to record art pieces, and screen to view the past inputted data; in total 5 unique screens.

### Design Statement
I will design and construct a digital gallery for a client who requires an administrative system for artworks: Mai. The gallery will manage all of the art pieces Mai has purchased and will purchase in the future. Imperative information about each art piece such as the title, artist, date it was created, and a description of it, will be saved, too. All of the data will be saved in a local database using SQLite. The application will be programmed using the software Pycharm, the language Python and KivyMD for GUI construction. The project will be completed in 4 weeks and will be evaluated according to the criteria set above. 

### Rationale for Proposed Solution
For the development of this application, I will be using the programming language Python as I, the developer, am the most comfortable with it, and allows me to meet the client’s demands quickly. Furthermore, according to Northeastern University, Python is ranked number one as the most popular programming language to learn in 2022 [^2]. Consequently, the program can be easily understood by a large number of developers and the code that is created can be worked on and improved upon in the future. Additionally, Python downloads an extensive library with multiple purposes such as documentation generation, unit-testing, databases, and more[^3]. This allows developers to code more efficiently due to the pre-existing code and functions that are time-saving. Nevertheless, Python does have drawbacks such as not being suitable for mobile application development. However, for this specific application that is being developed, this disadvantage does not get in the way as it will run on a computer.

For the GUI, I will be using the KivyMD library, which is a framework that creates an aesthetically pleasing graphical user interface. KivyMD is simple to use and allows for cross-platform applications, which is beneficial for the client's needs. Additionally, KivyMD is built using Python language, which is the language that is used for the application. Furthermore, it facilitates cross-platform applications that can run on Windows, Linux, Android, OSX, IOS, and Rasberry Pi[^4]. As a result, future developers will be able to expand the applications to other platforms which will make them available to a wider range of audience. KivyMD’s compatibility with Python, and its simple and powerful uses are all reasons for my preference for such for this project. 

To store inputted data, I will be using SQLite as the database. SQLite is simple to use, allows for multiple database files to be accessed simultaneously, and has cross-platform compatibility[^5]. These features play an essential role as it means that it will take a shorter time to create a program that meets the client’s needs. SQLite also counts with the advantage of embedding, which means that the database is integrated into the application and does not require a separate server process[^6]. This is particularly useful and adequate for this project as it is small-scale and the data can be stored locally. While SQLite does not have the same multi-user capabilities as MySQL and PostgreSQL, this is not an issue for this program as it is intended for personal use.

[^1]: “Van Gogh Immersive Art Exhibition Is Coming to Dublin.” Her.ie, www.her.ie/life/van-gogh-dublin-an-immersive-art-experience-is-coming-to-the-rds-548629. 
[^2]: Smith, Jane. "Most Popular Programming Languages in 2021." Northeastern University Graduate Programs, Northeastern University, 12 April 2021, https://www.northeastern.edu/graduate/blog/most-popular-programming-languages/.
[^3]: Jha, Alok. "Advantages and Disadvantages of Python." DataFlair, DataFlair, 24 April 2020, https://data-flair.training/blogs/advantages-and-disadvantages-of-python/.
[^4]: Kivy. "Kivy: Cross-platform Python Framework for NUI Development." Kivy, n.d., https://kivy.org/.
[^5]: Singh, Prerna. "SQLite Advantages and Disadvantages." Javatpoint, Javatpoint, n.d., https://www.javatpoint.com/sqlite-advantages-and-disadvantages.
[^6]:Morris, Kristin. "SQLite: A Lightweight Relational Database Management System." BuiltIn, BuiltIn, 11 June 2019, https://builtin.com/data-science/sqlite#:~:text=Benefits%20of%20SQLite,require%20low%2Dmemory%20footprint%20systems. 

## Criteria B: Solution
### System Diagram
![IMG_0654](https://user-images.githubusercontent.com/105724334/222962622-de6ad49a-9667-4188-968f-517435ee7abb.jpg)
##### Figure 1. The System Diagram For the Application
The system diagram is a visual model of the application, its components and their interactions. As shown on Fig. 1, the input is done through a keyboard and the output is manifested on the display (screen.) The application will run on Python and KivyMD, using the software program PyCharm via the file names project3.py and project3.kv, respectively. Additionally, the various inputs from the user will all be stored in an SQL database called project3.db.

### Wireframe
![IMG_A730C54DCB5B-1](https://user-images.githubusercontent.com/105724334/223476614-d29e5160-4dee-4aa5-bdb7-22bd8a3d8ae0.jpeg)

##### Figure 2. The Wireframe for the Application
The wireframe provides a visual representation of the gallery’s outline of the GUI. It also displays the functionalities of every button planned out to be utilized in the application. When the app is opened, the user first encounters a login page. If the user already has an account, they will simply input their user data correctly and access to the gallery will be granted. If they click the register button, though, they will be led to the registration screen where they can create a new account by entering their desired username, email, and password. After closing the register button, they will be taken back to the login page where they will need to input their user information accordingly to access the gallery. Once the user enters the gallery, they will find the menu/main page where they can choose whether to add an art piece, look at the history of added artworks, or logout. If the “Add Artwork” button is pressed, the user will be able to input the information about the art work. After all of the data has been collected the user will need to press the button save to ensure the information inputted goes into the database (project3.db). To go back to the main menu, the button “back” is pressed. If the option “History” is picked, the user will be redirected to a table screen where all the logged artworks are. The user can manipulate the data as desired/needed. Finally, to exit the application the user simply needs to press the button “Logout” and they will return to the login page.  

### ER Diagram

##### Figure 3. ER Diagram For the Attributes Requested By the Client

### UML Diagram

##### Figure 4. The UML Diagram For the Classes In the Application


### Flow Diagrams

##### Figure 5. Flow diagram of 

##### Figure 6. Flow diagram of

##### Figure 7. Flow diagram of

### Test Plan

Test plan for tester to follow to test the application. There are 3 different types of tests presented in the test plan which are unit test(to test one part of the program), integration test(to test the cooperation of different parts) and code review(to check the quality of code). In addition, description, input(step to follow) and expected output are also presented in the table for user to follow and knnow what to expect from each test.

| Test No| Test type | Description | Input / Procedure | Outcome |
|--------|-----------|-------------|-------|---------|
| 1 | Unit test | Test whether the sign up screen successfully registers a new user if all input is valid | Once 

 Go to sign up screen and enter the following values:
- email: bob@isak
- username: bob
-password: bob123	When the database, spentio.db is checked, a new row of data can be seen. This row shows the entered email, username, and password encrypted using a certain hash.



### Record of Tasks
| Task No | Planned Action | Planned Outcome | Time estimate | Target completion date | Criterion |
|---------|---------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------|---------------|------------------------|-----------|
| 1 | Meet with client  | Discuss and understand the problem they are struggling with and brainstrom possible plans to solve these issues | 15 min | Feb 20 | A | 
| 2 | Brainstorm and write the problem context | A concise problem definition of what the client is requires | 20 min | Feb 20 | A | 
| 3 | Write rationale for proposed solution | A detailed description and reasoning for the developed solution | 30 min | Feb 20 | A |
| 4 | Write success criteria | A clear set standards to be met that suit the client's needs | 20 min | Feb 22 | A |  
| 5 | Meet with client | Confirmed succes criteria and ensure it meets the client's standards | 20 min | Feb 24 | A |
| 6 | Write design statement | A coherent design statement that outlines the plan for the project | 20 min | Feb 24 | A | 
| 7 | Edit rationale for proposed solution | A more appropriate and fitting rationale based on the client's feedback | 10 min | Feb 24 | A |
| 8 | Create the system diagram | To have a concrete idea of the software and hardware requirements involved in the development of the application | 50 min | Feb 25 | B |
| 9 | Create the application's wireframe | Visual representation of the structure of the application | 30 min | Feb 25 | B |
| 10 | Initialize database handler | Set-up the base for the databse in order for functions to be added | 20 min | Feb 26 | C |
| 11 | Build password policy | Completed password policy that encourages user to pick impenetrable passwords  | 20 min | Feb 27 | C |
| 12 | Create registration system | A multi-step registration code program that registers and stores the data inputted into the database | 40 min | Feb 27 | C | 
| 13 | Create login system | A secure program that allows the user to login to the application using an existing username and password | 40 min | Feb 28 | C | 
| 14 | Code password encryption | Secure storage of user's password as it will be encrypted utilizing sha256 | 45 min | Feb 28 | C |
| 15 | Create menu page | A page where the user, once logged into the application, can choose what to do | 90 min | Mar 1 | C |
| 16 | Set up table for all artworks | A table inside the database that includes all of the data concening the art pieces | 20 min | Mar 1 | C |
| 17 | Create an add artwork page | A page where the user will be able to add an art piece, its details and save it | 70 min | Mar 2 | C |
| 18 | Add date picker to add artwork page | Date picker will be implemented and when used, the program should display a calendar for the user to choose the date | 60 min | Mar 2 | C |
| 19 | Create artwork history page | A page that allows the user to view all of the art works stored within the database | 80 min | Mar 2 | C |
| 20 | Add checkboxes to the history page | Checkboxes that will allow the user to select certain values | 70 min | Mar 3 | C |
| 21 | Create search system for artworks | Allow the user to look for specific art pieces based on artist and title | 120 min | Mar 4 | C |
| 22 | Create table that displays search results | Printed requested values from database | 80 min | Mar 4 | C |
| 23 | Validate all buttons | All buttons execute their expected behaviours | 120 min | Mar 5 | C | 
| 24 | Create UML diagram | Visual representation that showcases the different classes and methods used in the application | 40 min | Mar 5 | B | 
| 25 | Create ER diagram | Diagram that illustrates the objects in the application and how they relate to each other | 40 min | Mar 6 | B |
| 26 | Write the test plan | Assessments/checks to ensure the program runs as expected | 50 min | Mar 7 | B |
| 27 | Draw flow diagrams | Flow diagrams that outline the sequence of the program | 60 min | Mar 7 | B | 
| 28 | Record video | Video demonstrating and describing the product and how the success criteria has been met | 20 min | Mar 9 | D |
| 29 | Finalize repository | Repository that contains the work done for the development of the project along with detailed descriptions of every step. | 50 min | Mar 9 / 10 | B / C / D | 

## Criteria C: Development

### Techniques Used
1. For loops
2. If-else statements
3. Functions
4. Password encryption 
5. Object Oriented Programming
6. GUI building using KivyMD Library
7. Working with SQLite databases 

### GUI Creating Using KivyMD

```.py

```

## Criteria D: Functionality

##### Figure 7. Video to show the applications functionality and extensibility 

## Works Cited
