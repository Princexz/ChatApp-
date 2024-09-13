# ChatApp
### Chat Application_

## Overview
  - It is a scalable Realtime Chatting Application that provides an interface for multiple user chatting at the same time.
## Technologies used
  - FrontEnd - HTML, CSS
  - BackEnd - JavaScript, PHP
  - Used Socket.io module for a two-way connection between client and server.
## Website's structure & features
  - FrontEnd includes a navigation bar, Chat window and a form submit button for sending the messages.
  - HTML has been used for preparing the structure of application.
  - CSS has been used for styling the application.
  - Added Client sided JavaScript for the purpose of playing with DOM elements.
  - First of all stored all the DOM elements in a respectives JS variable.
  - Used Audio file (ting.mp3) which gives notification on receiving the messages.
  - Everytime a new user tries to join, first of all ask his/her name and let the server and already connected users know.
  - If a new user joins, receive the event from the server using eventListner.
  - If a user leaves the chat, tell all the other users that this user has left the chat.
  - Server Side JavaScript will handle the Socket IO connections.
  - If someone sends the message, broadcast it to other people.

## Installation in your local computer
- Fork the repository
- Clone the forked repository to your local machine by giving the following command in the terminal :
```
git clone https://github.com/princexz/ChatApp.git
```
- Change the current directory to ChatApp directory by using the following command : 
```
cd ChatApp 
```
- Install the dependencies in this folder using the below command :
```
npm install
```
- Now change the current directory to ``server`` directory
```
cd server
```
- Run ```npm install``` to install server dependencies
- Run ```npm run dev``` in the ```server``` to start the development server
- Now, go back to the main folder in git bash using the ```cd ..``` command.
- Either you can double click on the ```index.php``` file to start the website, or you can also download live-server extension of VS code and run the ```index.php``` file using it.
- A instance of the application will appear in the browser.
- Copy the url from the address bar and open another instance in another tab or in incognito or on another browser.

## Contribution
- Fork the repository.
- Clone the forked repository to your local machine by giving the following command in the terminal :
```
git clone https://github.com/princexz/ChatApp.git
```
- Change the current directory to ChatApp directory by using the following command : 
```
cd ChatApp
```
- Add remote to the original repository by using the following command : 
```
git remote add upstream https://github.com/princexz/ChatApp.git
```
- **Important step** : Take a pull from upstream repository to your main branch by using the following command :
```
git pull upstream main
```
- Create a new branch (Do not write the "<>" brackets)
```
git checkout -b <new-branch-name>
```
- Now, perform any changes to the codebase to resolve an issue.
- After you have made all the changes, give the following commands :
```
git add . 
```
```
git commit -m"any relevant message"
```
```
git push -u origin <new-branch-name>
```
- Now, head over to GitHub and click on the ```compare and pull request``` button.
- Add appropriate details to the pull request.
- Click on ```Create pull request``` button.
- Now chillax 🥳, and wait for the PR to get reviewed and merged.

## Project Admin

<table>
<tr>
<td align="center"><a href="https://github.com/princexz"><img src="https://avatars.githubusercontent.com/u/84660268?v=4" width=150px height=150px /></a></br> <h4 style="color:red;">Prince Solomon</h4>
<a target="_blank"href="https://www.linkedin.com/in/princexz"><img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" /></a>&nbsp;&nbsp;&nbsp;&nbsp;
 <a href="mailto:prince_solomon@yahoo.com"><img src="https://img.shields.io/badge/gmail-%23D14836.svg?&style=for-the-badge&logo=gmail&logoColor=white" /></a>&nbsp;&nbsp;&nbsp;&nbsp;
   </td>

</tr>
</table>

## Project Contributors

<a href="https://github.com/princexz/ChatApp/graphs/contributors">
<img src="https://contrib.rocks/image?repo=princexz/ChatApp" />
</a>

</br>
<p align = "center">
Show some ❤️&nbsp; by giving <img src="https://imgur.com/o7ncZFp.jpg" height=25px width=25px> to this repo
</p>

