# Front-End Project

### Objective

This project consists of creating a React application using Vite, with the aim of developing an interface that allows the creation and visualization of game sessions. The application interacts with a backend to persist and retrieve session data.

### Features

- **Form to create new game session**:
 - The form collects the following game session details: `hostname`, `players`, `map` and `mode`.
 - Upon submission, data is sent to the backend API via a POST request to create a new game session.

- **List view of game sessions**:
 - The application fetches and displays a list of game sessions from the backend API.
 - Details displayed include: `hostname`, `players`, `map` and `mode`.

### Requirements and Implementation

1. **Form**:
 - [x] Collection of game session details: `hostname`, `players`, `map` and `mode`.
 - [x] Sending POST request to backend API to create a game session.

2. **List View**:
 - [x] Search and display the list of game sessions from the backend API.
 - [x] Details display: `hostname`, `players`, `map` and `mode`.

3. **User Experience (UX/UI)**:
 - [x] Implementation of a responsive and easy-to-use design.
 - [x] Use of a CSS structure, in this case, Tailwind CSS.

4. **Code Quality**:
 - [x] Guarantee of high readability and ease of code maintenance.
 - [x] Use of modern React development practices, such as hooks and functional components.

### Technologies Used

- **React** with **Vite** for UI development.
- **Tailwind CSS** for styling and responsive design.
- **Axios** for communication with the backend.

### How to Execute

1. Clone this repository:
```
git clone https://github.com/Matheusfbio/full-stack-web-challenge.git
```
2. Navigate to the project folder
```
cd full-stack-web-challenge
```
3. Install dependencies
```
npm i
```
4. define the .env to integrate with the backend locally for testing purposes
```
VITE_API_ENDPOINT="http://localhost:3000/sessions"
```
5. execute the project
```
npm run dev
```
