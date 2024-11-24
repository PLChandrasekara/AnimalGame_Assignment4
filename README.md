Animal Matching Game 🐾 

A fun and interactive React-based game where users match a randomly chosen animal name with its corresponding image. This project demonstrates the use of React components, state management, and CSS styling for a responsive design. 

 

Table of Contents 

Overview 

Features 

Project Structure 

Setup and Installation 

How to Play 

Technologies Used 

Output Example 

Future Enhancements 

 

Overview 

The Animal Matching Game challenges users to identify and select an animal based on its name. A randomly chosen animal name is displayed at the start of the game, and users select from a grid of animal images. Feedback is immediate: users will either "Win" or "Lose" based on their selection. 

 

Features 

Dynamic Randomization: Each session begins with a randomly selected animal name. 

Interactive Grid: Users can click on animal images for their selection. 

Immediate Feedback: Displays results as "Won" or "Lost" after a selection. 

Responsive Design: Fully responsive layout for different screen sizes. 

Hover Effects: Visual feedback when hovering over images. 

 

Project Structure 

AnimalMatchingGame/ 
├── public/ 
│   ├── assets/              # Animal images (e.g., 1.jpg, 2.jpg) 
├── src/ 
│   ├── components/ 
│   │   ├── AnimalTable.js   # Core game component 
│   ├── AnimalsDb.js         # Animal database 
│   ├── App.js               # Main application file 
│   ├── index.js             # React app entry point 
│   ├── compo.css            # Styling for the game 
├── README.md                # Documentation 
├── package.json             # Project dependencies 
 

 

Setup and Installatio 

Clone the repository 

git clone https://github.com/your-username/animal-matching-game.git 
 

Navigate to the project directory: 

cd animal-matching-game 
 

Install dependencies: 

npm install 
 

Start the development server: 

npm start 
 

Open the application in your browser at http://localhost:3000. 

 

How to Play 

A random animal name is displayed at the top of the game table. 

Match the name to the correct animal image in the grid. 

Click on an image: 

If correct: "Won" is displayed. 

If incorrect: "Lost" is displayed. 

Refresh the page to play again with a new random animal. 

 

Technologies Used 

React: Core library for building the game interface. 

JavaScript: Logic for randomization and interaction. 

CSS: Styling for layout and responsiveness. 

 

Output Example 

Initial View 

The game starts by displaying a random animal name at the top and a grid of animal images: 

Result 

Animal Name 

Select the Animal 

 

ELEPHANT 

🐘 🐱 🐶 🐯 🦁 ... 

After Selection 

Once an image is clicked, the game shows either Won or Lost based on whether the selection matches the random animal. 

Result 

Animal Name 

Select the Animal 

Won 

ELEPHANT 

🐘 🐱 🐶 🐯 🦁 ... 

 

Future Enhancements 

Add scoring and tracking for multiple rounds. 

Introduce a timer for added challenge. 

Include animations or sound effects for better engagement. 

Expand the animal database with more entries. 

 
