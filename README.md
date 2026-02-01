My Internship Tasks - Cognifyz
Hey! This is all the work I’ve done for my web development internship. I’ve broken it down into levels to show how the project grew from a simple form to a full API system.

What’s inside:
Level 1 (Tasks 1 & 2) I started by setting up a basic Node.js server using Express. I made a simple feedback form and used EJS so the server could talk to the HTML. I also added some validation so that if someone leaves a field blank or puts in a weird email, the server catches it and shows an error.

Level 2 (Tasks 3 & 4) For this part, I focused on making it look good and work smoothly. I brought in Bootstrap to make the layout responsive (so it works on phones) and added some cool "live" features. For example, there’s a password strength bar that changes color as you type and a character counter for the message box. I also used "hash routing" so you can switch between the form and the summary without the page reloading.

Level 3 (Task 5) This is the most advanced part. I turned the whole thing into a REST API. Instead of the page refreshing when you hit submit, I used JavaScript fetch to send data in the background. I also added a "Delete" button for the feedback list, so you can actually manage the data in real-time.

Each task is on a different port so they don't crash into each other:

Task 1: Port 3000

Task 2: Port 3001

Task 3: Port 3002

Task 4: Port 3003

Task 5: Port 3004

Just run npm start in the folder and open it in your browser.

Tech I used:
Node.js & Express (Backend)

EJS & Bootstrap (Frontend)

JavaScript / Fetch API (Logic)
