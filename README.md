# Node-Authentication app

Creating a complete authentication system which can be used as a starter code for creating any new application

## Functionality

1. Sign up with email
2. Sign in (you can redirect to a blank home page with a sign out and reset password button after sign in)
3. Sign out
4. Reset password after sign in
5. The password stored in the db should be encrypted
6. Google login/signup (Social authentication)
7. Display notifications for <br>
   I. unmatching passwords during sign up <br>
   II. sign up user<br>
   II. incorrect password during sign in<br>
   III. sign in user<br>
   IV. reset password <br>
   V. old password not match <br>
   VI. google user not change password<br>
   VII. sucessfully reset password<br>
   VIII. sucessfully signout<br>

## Tools

1. Node Js v-16.18.0
2. Express Js
3. Mongodb v-5.0.13
4. Mongoose
5. Ejs
6. Bootstrap 5
7. bcrypt
8. passport local (for authentication purpose)
9. passport-google-oauth (for google authentication)
10. express-session
11. connect-mongo (for storing cookie inside db)
12. connect-flash and noty (for display notification)

## Setup in Local System

1. download file as zip and extract the file
2. open command prompt and Type 'npm install' in the root directory of the project to download all dependencies

3. then just type "npm start" if npm start is not work just run this command 'node index.js'

4. then go localhost:8000 in the web browser to see the app

## This Site is hosted here

1. check link - https://authenticationcn.onrender.com

## important points!!

#### To use the google sign in on the deployed website

1. initially run the _npm run start_ in the local terminal first
2. try signing in the deployed website to run without errors after that

**Thanks..!!**
