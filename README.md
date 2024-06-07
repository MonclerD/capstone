#Manu by Mau

#Overview
This repository contains the source code for a web application built with Flask. The app is designed to create and manage children's stories, utilizing OpenAI's API for generating and moderating content.
https://github.com/MonclerD/capstone
Features
User authentication (registration and login)
Story creation with content moderation
Image generation for stories
Viewing and managing created stories

#Installation
1-	Visual Studio Code installation
https://www.youtube.com/watch?v=CPmQwlycfGI
2-	SQLite installation
https://www.youtube.com/watch?v=L3FwRRx6bqo
3-	DB Browser for SQLite installation
https://www.youtube.com/watch?v=o8d38cGb7vY&t=282s
4-	Python installation
https://www.youtube.com/watch?v=HyAleMfb5og
5-	Git installation
https://www.youtube.com/watch?v=cJTXh7g-uCM
6-	Install the required dependencies/libraries 
https://www.youtube.com/watch?v=ENHnfQ3cBQM
pip install Flask 
pip install Werkzeug 
pip install openai
7-	Pull/Clone the GitHub repository 
https://www.youtube.com/watch?v=ILJ4dfOL7zs
https://github.com/MonclerD/capstone

If project folder/file already downloaded/exists in your computer:
https://www.youtube.com/watch?v=197JAS1gNKo

#Initial Setup

-	Open app.py file 
-	Click the ‘Run Code’ button (as directed with red arrow in the picture) or press Ctrl + Alt + N

 

- After running the code, in Terminal, there will be local host link 
-	Access the application by navigating to http://127.0.0.1:5000/ in your web browser or click with your mouse to ‘Follow link’










-	After navigating or clicking to link, in your web browser you will direct to the Home Page of website:
 

  - Be able to enter/use ‘Create book’ web page or ‘my books’ web page user must have an account!!

 





#Directory Structure
•	app.py: Main application file
•	static/: Static files (CSS, images)
•	templates/: HTML templates (JS files in Html)
•	users.db: SQLite database file


#Routes
•	/ - Home page
•	/login - Login page
•	/register - Registration page
•	/about - About page
•	/create - Create a new story
•	/books - View your books
•	/read_book/<int:book_id> - Read a specific book
•	/logout - Logout

