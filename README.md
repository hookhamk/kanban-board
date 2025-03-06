# Mini-Project: Kanban Board

## Description
This project is a Kanban board with a secure login to manage personal work tasks.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

## Acceptance Criteria

(provided by Boot Camp)
GIVEN a Kanban board with a secure login page
WHEN I load the login page
THEN I am presented with form inputs for username and password
WHEN I enter my valid username and password
THEN I am authenticated using JSON Web Tokens (JWT) and redirected to the main Kanban board page
WHEN I enter an invalid username or password
THEN I am presented with an error message indicating that the credentials are incorrect
WHEN I successfully log in
THEN a JWT is stored securely in the client's local storage for subsequent authenticated requests
WHEN I log out
THEN the JWT is removed from the client's local storage and I am redirected to the login page
WHEN I try to access the Kanban board page without being authenticated
THEN I am redirected to the login page
WHEN I remain inactive for a defined period
THEN my session expires, the JWT is invalidated, and I am redirected to the login page upon my next action

## Usage
The best way to use this project is through the deployed site (https://kanban-board-slug.onrender.com)

## Credits
I have utilized the resources from edX Boot Camps LLC.

## License
![License Badge](https://img.shields.io/badge/license-MIT-brightgreen)

This project is licensed under the MIT license.

[Learn more about this license](https://choosealicense.com/licenses/mit/)

## Tests
No tests at this time.

## Questions
If you would like to add to this project please reach me on Github github.com/hookhamk or email me at hookhamk8@gmail.com

