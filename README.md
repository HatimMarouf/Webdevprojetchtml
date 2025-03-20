# Java Learning Feedback Project

This project is a web application designed to collect feedback from users about their experience learning Java. It includes a front-end interface built with HTML, CSS, and JavaScript, and a back-end server built  with Node.js and Express.js.

## Features
- **Dynamic Feedback Form**: Questions are loaded dynamically based on the user's status (Student or Bachelor).
- **Comment Submission**: Users can submit their feedback along with answers to the questions.
- **Comments Section**: Displays all submitted feedback with user details and answers.

## Technologies Used
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js, Express.js
- **Dependencies**: `express`, `cors`

## Project Structure
- `index.html`: The main HTML file for the front-end interface.
- `script.js`: Handles front-end logic, including form submission and dynamic question loading.
- `servernod.js`: Backend server handling API requests and data storage.
- `README.md`: This file.

## How to Run the Project
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/HatimMarouf/Webdevprojetchtml/
   ```
2. **Install Dependencies**:
   ```bash
   npm install express cors
   ```
3. **Start the Server**:
   ```bash
   node servernod.js
   ```
4. **Open the Project**:
   - Open `index.html` in your browser.

## API Endpoints
- `GET /questions`: Fetch all questions.
- `GET /questions/:id`: Fetch a specific question by ID.
- `POST /feedback`: Submit feedback.
- `GET /feedback`: Fetch all submitted feedback.

## Example Feedback Submission
1. Select your status (Student or Bachelor).
2. Answer the dynamically loaded questions.
3. Enter your comments and submit the form.

## Screenshots
![Feedback Form](screenshots/feedback-form.png)
![Comments Section](screenshots/comments-section.png)
