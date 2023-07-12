**Requirements**
Change the values in the text file (/settings/coursenumbers.txt) to the classes you are trying to snipe.

Try to not change anything else tho.

Do 'pip install -r requirements.txt' in this directory(folder) before you try to run this program.
Should have everything, I think.
\n
A chrome browser is required for this program. It defaults to opening a new (basically) incognito session where none of your passwords would be present. For it to open a session with your gmail account, you would need to locate your chrome profiles folder and add option to selenium.

**Explanation:**

***THIS IS A WIP DO NOT EXPECT EVERYTHING TO WORK***

***complete_webscrape:***
Does not require login, a compelte webscrape of all the course index of courses specified in settings/course_numbers.txt. This will get al lthe indexes and put them onto course dictionary json file.

***partial_webscrape:***
Loads from index.src for the course indexes you want to snipe.

***session_status_updater:***
Where the real sniping starts. Uses rutgers API to see if the courses are open and (for now) prints to console.

***webRegBot:***
***Experimental***
Use at your own risk. Might be a violation to webreg TOS.
Automatically registers for the courses. It is still WIP and doesnt function properly.

Zav
