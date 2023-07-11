Change the values in the text file (/settings/coursenumbers.txt) to the classes you are trying to snipe.

Try to not change anything else tho.

do 'pip install -r requirements.txt' in this directory(folder) before you try to run this program.
Should have everything, I think.

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
