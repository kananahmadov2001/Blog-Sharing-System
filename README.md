<div align="center">
    <h1 id="Header">Blog-Sharing-System</h1>
</div>

## Overview
The Blog-Sharing-System is a dynamic web application where users can share, edit, and search for stories. The platform allows users to personalize their profiles, interact with others' content, and enjoy a safe, curated experience with content filtering. This project emphasizes user engagement and secure, user-friendly design.

## Links
- **Homepage**: [Blog-Sharing-System Homepage](http://ec2-50-17-104-237.compute-1.amazonaws.com/~kananAhmadov/module-3-group/login.php)

## Login Details
Use one of the following credentials to log in:

| Username  | Password      |
|-----------|---------------|
| bellamy   | `bellamy,2001`|
| kanan     | `kanan,2001`  |

Alternatively, create a new account by entering a username and password on the homepage and clicking **Register**. Once registered, you can start adding your own stories and enjoy the platform!

## Technologies/Tools Used
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: PHP
- **Database**: MySQL
- **Asynchronous Communication**: Fetch API for AJAX requests

## Features
- **User Registration and Login**:
  - Users can register, log in, and manage their accounts securely.  
- **Story Management**:
  - Users can create, edit, and delete stories. Comments can also be added to others' stories.
- **Profile Customization**:
  - Users can personalize their profiles by updating their bio and adding social links. Click on the username after logging in to access the profile page.
- **Search Functionality**:
  - A simple search engine allows users to find stories by title or author. Clicking on "Search for a story" provides an interface to either search for specific terms or view all available stories.
- **Inappropriate Word Filter**:
  - The system filters inappropriate words in stories and comments. For example:
    - Input: `This is a shit day`
    - Output: `This is a **** day`
    - Filtering is triggered when inappropriate words are separated by spaces.

