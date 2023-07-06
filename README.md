# notesMaker-webApp

About Project:


1.This project is used to make notes and keep then for our uses.

2.user can signup/signin and can get their stored notes which is created by user.

3.Notes are user specific means a user can not access another user's notes.

4.We categories notes in different pages according to our need 



You need:
Database (MongoDB)
Nodejs (installed) on Local Computer
Google Console Account to create the API Auth Key's

Now Steps to run website on your local system

1.clone git repo using command:


git clone https://github.com/Prasugupta21/notesMaker-webApp.git

2.navigate to project directory and create .env file in project root directory


example below to store your credentials in .env file

MONGODB_URI = mongodb+srv://<username>:<password>@mongodburlhere


GOOGLE_CLIENT_ID= YOUR_GOOGLE_ID_HERE


GOOGLE_CLIENT_SECRET= YOUR_GOOGLE_CLIENT_SECRET_HERE


GOOGLE_CALLBACK_URL=http://localhost:3000/google/callback


3. install the npm using command:


npm install


4. enter command:

   npm start

5 Open browser and enter:


localhost:3000



