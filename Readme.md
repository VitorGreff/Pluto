
# Pluto
My very first contact with a Web Scraping application. Me and some colleagues participated in a competition about developing a investment strategy and a robot, that could apply that strategy in a backtest environment. There are some things that must be clarified about the code itself:

**#1** 
Pluto (the name of our robot) had the task to collect tables of nearly 200 companies in a period of 10 years; 

**#2** 
The database we used for it was a brazilian website that has small caps as a section;

**#3**
 Since you must be logged in on the website to access de data, to use Pluto, you'll have to create an account and change the strings inside the code: "email" and "password";

**#4**
 Also, to use selenium (one of the automatization library that we use to write the code), you'll have to install the driver of your browser and update the path of it inside the code;

**#5** 
As we were running out of time, we didnt implement some pieces of the code as we wanted to. Selenium was not working pretty well to get the tables and saving them. So, we made a code that had a very little margin of error that consists in got to the empty space of the table and clicking on it 3 times, so the entire table was selected. Using this strategy, that wasnt appealing to the eyes but functional, we got a margin of error less than 2% by selecting the tables.

**#6**
 As we used pyautogui to move the cursor in some pieces of the code, unfortunately, its not guaranteed that Pluto will work on every computer. Pyautogui has a strange behavior, even one of our teammates wasnt able to run the code properly.

**Conclusion:**
Pluto is not a perfect web scraping appplication, the lack of time to properly implement it and our limited knowleadge of the right technologies that we should use were a barrier to write it on the way we want. However, writing pluto was a pleasant experience. I had the opportunity to push myself in a way that prove me that I could learn new stuff in a short amount of time, besides that, we were dividing our time between college, our personal studies and Pluto. I'm grateful to had the opportunity to push myself forward and to learn along my teammates and friends.
