# Simple-Feedback-Management-System

Deliverables:

A Public GitHub repository with the full project code.

A brief README file explaining the project setup and structure and any additional notes.

Requirements:

Backend:

Set up a Node.js server using Express and TypeScript.

You can use the Nest.js framework to create this which will be Brownie point

Create a REST API with the following endpoints:

Retrieve all feedback entries.

Submit new feedback (body: { name: string, feedback: string }).

An in-memory data structure stores feedback entries.

Do not use Redis or any other in-memory storage 

Optional - Rate limit based on IP address such that a user can only submit 1 feedback in 10s

Frontend:

Set up a React application using TypeScript.

Create a form to submit new feedback (with fields for name and feedback).

Display a list of all feedback entries.

Use fetch or Axios to communicate with the backend API.

Use web worker to fetch the data 

Optional - Implement a virtual/infinite scrolling - library can be used but need to understand the working because we will ask about it 

Instructions:

Backend: Use TypeScript with Node.js and Express. Implement routes, controllers, and services with a clear separation of concerns.

Frontend: Use TypeScript with React. Ensure the UI is clean and functional.

API Communication: Use fetch or Axios to make API requests from the front end to the back end.

Data Handling: Use an in-memory data structure (e.g., array) for simplicity.
