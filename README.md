## Overview
**Leads Web** is a web application that allows us to view, add, update, or delete leads from a list.

In the application, the front-end and back-end components are separated; the communication between them is organized using REST API (JSON). User input validation is performed client-side by JavaScript and duplicated on the server side in Python. Backend is split into the following layers: API (Adpositions app), BLL, and DAL. To represent the data, two model classes were created in the back-end part of the application: class Lead (a DTO model) and class LeadView (a Presentation Model). The Presentation Model allows us to return the data in the "view" state that hides sensitive information and shows only the data that API needs to output.

## UI demonstration
https://www.youtube.com/watch?v=y8EKzF0K5fU

## Run commands
### `py manage.py runserver`

Runs the Django app in the development mode.<br />
Open [http://127.0.0.1:8000](http://localhost:8000) to view it in the browser.

### `npm start`

Runs the React app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

### `npm install react-scripts --save`

Can fix the following error: *'react-scripts' is not recognized as an internal or external command*. If you clone the repository to run the app, you will probably see this error message when you run the 'npm start' command.

## Notes
***I completed this project when I was studying at University.***

## Technologies 
JavaScript, React, Python, Django REST Framework, SQL
