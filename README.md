# Apollo Journal
Apollo Journal is a cross-platform, fullstack note-taking app that let's you add a personal note to add to your journal a journal as well as upload an image via a link. You can Create, Edit and Delete posts as much as you want. In other words, for each platform, you can play around with data persistence to POST, GET, UPDATE and DELETE for each post.

## Web Version
On the web, it is built with plain HTML, CSS and Vanilla Javascript. To have a similar approach as we would normally have in iOS, I choose to use the MVC desgn pattern with Sails MVC.

## iOS Version
Built entirely with Swift except for couple of methods written in Objective-C, the iOS version of Apollo Journal is built in accordance with the Human Interface Guidelines implemented by Apple. The main view is a TableViewCell with a Title, Body and an image link contained in each cell.

## Backend
Node.js was used to built the backend in JSON format with Express.js and Sails MVC. Users-specific data are stored as objects such as the Title, the Body and the Image for each post. The user can create and/or login to their account with their email and password.

## Contact
If you have any questions, I'd be more than happy to chat on Twitter @JosephCodes_
