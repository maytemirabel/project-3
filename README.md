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
5. The application will include a “forgot password” button option if the user forgets their password. 
6. The application must encrypt the user’s password in the local SQL database.
7. The application must contain a login screen, registration screen, home screen, screen to record art pieces, and screen to view the past inputted data; in total 5 unique screens.

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



Figure 2. The Wire Frame For the Application

### ER Diagram


Figure 3. ER Diagram For the Attributes Requested By the Client

### UML Diagram


Figure 4. The UML Diagram For the Classes In the Application


### Flow Diagrams

### Test Plan


### Record of Tasks
| Task No | Planned Action | Planned Outcome | Time estimate | Target completion date | Criterion |
|---------|---------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------|---------------|------------------------|-----------|
| 1 | Meet with client  | Discuss and understand the requirements needed for the project  | 10 min | Feb 22 | A |
| 2 | Brainstorm and write the problem context | A concise problem definition of what the client is requires | 20 min | Feb 22 | A | 
| 3 | Build success criteria | 
| 4 | Write design statement | A descriptive and articulated outline of the project | 
| 5 | Describe rationale for proposed solution | 
| 6 | Draw system diagram and write the caption |
| 7 | 
| 8 |
| 9 | 
| 10 |
| 11 | 
| 12 |
| 13 |
| 14 |
| 15 |
| 16 |
| 17 |
| 18 |
| 19 |
| 20 |
| 21 |
| 22 |
| 23 |
| 24 |



| 7 | Develop MVP (Minimum Viable Product) | Test basic product before moving towards the final one | 120 min | Dec 02 | B |
| 9 | Create flowcharts | Clearly display the codes utilized in the making of the product | 60 min | Dec 04 | B |


|  | Video creation | Demonstrate and describe the product and how the success criteria has been met | 40 min | Dec 12 | D |
|  | Polish details on repository | Gather everything that must be added | 40 min | Dec 12 | B |


## Criteria C: Development

### Techniques Used




### GUI Creating Using KivyMD

```.py

```

## Criteria D: Functionality


## Works Cited
