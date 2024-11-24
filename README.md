 Animal Matching Game 🐾

A simple **React-based game** where users match a randomly selected animal name with its corresponding image. Perfect for practicing recognition skills while having fun!


 📝 Overview
The **Animal Matching Game** is a fun and interactive game where the user matches the name of a randomly selected animal with its corresponding image. If the guess is correct, the user wins; otherwise, they lose.

-✨ Features
- Displays a random animal name at the start of the game.
- A grid of animal images for selection.
- Displays immediate feedback (`Won` or `Lost`) based on user selection.
- Smooth hover effects for better user interaction.
- Fully responsive layout.

---

 🗂️ Project Structure

AnimalMatchingGame/
├── public/
│   ├── assets/              
├── src/
│   ├── components/
│   │   ├── AnimalTable.js   
│   ├── AnimalsDb.js        
│   ├── App.js               
│   ├── compo.css            
├── README.md               
├── package.json            


 ⚙️ Setup and Installation
Follow these steps to set up and run the project locally:

Prerequisites
Ensure you have the following installed:
- **Node.js** (v14.x or later)
- **npm** (or **yarn**)

### Steps
1. Clone this repository:
   git clone (https://github.com/PLChandrasekara/AnimalGame_Assignment4.git)
 
2. Navigate to the project folder:
   cd Animalgame_Assignment4

3. Install project dependencies:
   npm install

4. Start the development server:
   npm start

5. Open your browser and visit:
   http://localhost:3000

🎮 How to Play
1. **Objective**: Match the displayed animal name with its image.  
2. A random animal name will appear at the top of the table.
3. Click on the correct animal image from the grid to win.
4. **Winning Condition**: If your selected image matches the animal name, you’ll see "Won."
5. **Losing Condition**: If your selection is incorrect, you’ll see "Lost."
6. Refresh the page to start a new game.

 🛠️ Technologies Used
- **React**: For building the interactive user interface.
- **CSS**: For styling and layout.
- **JavaScript**: For game logic.

 📂 File Descriptions

**AnimalTable.js**
- Contains the core game functionality and layout.
- Handles logic for generating a random animal and validating user selection.

**AnimalsDb.js**
- A database of animal names and corresponding image paths.

**App.js**
- Entry point for the React application that renders the `AnimalTable` component.

**compo.css**
- Styles the game table, grid, and images.

**public/assets/**
- Stores images used in the game, named numerically (e.g., `1.jpg`, `2.jpg`).

🚀 Future Improvements
- Add multiple difficulty levels with larger grids.
- Include a timer for a more challenging gameplay experience.
- Track the player’s score across multiple rounds.
- Add animations or sound effects for better engagement.

📷 Screenshot of the Game!
Here’s how the game looks:
[finaloutput](https://github.com/user-attachments/assets/91842837-0e22-475c-a85d-7219a6f6b31c)








