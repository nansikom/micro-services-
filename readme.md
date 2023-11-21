The code is in Javascript and to get started with working with this code,you will have to install node,if you dont have node installed,you can use this link 
to install it on your computer GitHub Copilot: To install Node.js, follow these steps:
Use this site to download node Node.js website at https://nodejs.org/.
Run the installer and follow through the prompts
In your terminal install npm init.This will give you package.json and package lock to give u the exact match of the versions needed in your dependencies.
In you terminal run node -v and npm -v these will print for you a version number
Install express to act as middleware and also to act as a route for handling your responses and requests.
U can install it using npm install express.
Next is to create the file that has all the questions and answers and make sure it is running locally "C:\Users\Maria\Desktop\micro\answer.json"
I made it a json file since its easier to navigate than a database.
Next is to create the different fetch functions in your script code that will be sending to these endpoints 
'http://localhost:3000/api/geography
'http://localhost:3000/api/music
'http://localhost:3000/api/science
'http://localhost:3000/api/history
Next is to add the different keys in your server code to make sure you pull random number with different id.
The most important part of this is to call the right endpoin so the api is accessing the right endpoint
Something like this 
app.get("/api/music" , (req, res) =>{
Then lastly is to check that your listening to the right port.
Tips to use
Always restart the server incase you change anything
Try one function at a time
Uml diagram
https://docs.google.com/document/d/1Aqvj_7sbVdBZNUxMWHHHFcxhlw-Cnv9d3NlMLxGI8yM/edit
