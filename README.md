# Authentication

--> It is an application that validates the information entered by the user and only enables the autheticated users (which are allowed) whose data is stored in database and if it matches, then it is allowed to the main page.

--> Libraries used for Backend :
  - bcryptjs
  - cors
  - dotenv
  - express
  - mongoose
  - jsonwebtoken
  - nodemon

--> Libraries used for the Frontend :
  - react-dom
  - react-router-dom
  - bootstrap
  - axios

--> Steps to run the Application :
  - For running the backend, change the mongodb url and secret key in .env file. run the command npm start.
  - For running the frontend, run the command npm start



--> Preview of the Application :

  - Register page with Password warning (minimum password length should be 5).
    ![Register with password warning](https://github.com/siddhapurahet/Authentication/assets/84630752/7fd03f3c-1fb8-4165-815b-7d24c99f468b)


  - Login page
    ![login page](https://github.com/siddhapurahet/Authentication/assets/84630752/91def326-3270-44ce-9d6d-5137ae8fd205)


  - Page displaying Account already exists in the database.
    ![account already exists](https://github.com/siddhapurahet/Authentication/assets/84630752/d06ba088-8e09-41b7-be5b-6bc907b23e2c)


  - Page showing Login successful
    ![loggedin successful](https://github.com/siddhapurahet/Authentication/assets/84630752/7f8d7841-aad1-4fc9-a591-3af829803183)


  - Log out page
    ![logged out page](https://github.com/siddhapurahet/Authentication/assets/84630752/3b328d9e-f8c3-46c4-b317-9e1ca24ea45d)


  - Database showing the entries of the users who are signed up
    ![database](https://github.com/siddhapurahet/Authentication/assets/84630752/179f33e8-d6b2-42ea-add7-19ccfb61e5ff)

