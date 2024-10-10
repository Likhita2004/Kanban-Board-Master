
# Kanban Board Master

A simple and effective Kanban board application to help you manage your tasks and projects efficiently. This project is designed to visualize work progress, prioritize tasks, and streamline productivity.

## Features
- **Create Boards:** Create multiple boards to categorize different projects.
- **Add Lists:** Add lists to represent various stages of the task (To Do, In Progress, Done, etc.).
- **Create Cards:** Create task cards within each list to represent individual tasks.
- **Drag and Drop:** Easily move cards between lists using drag-and-drop functionality.
- **Edit and Delete:** Edit and delete boards, lists, and cards with ease.
- **Responsive Design:** User-friendly interface that works seamlessly on both desktop and mobile devices.

## Tech Stack
- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Node.js, Express.js
- **Database:** MongoDB (for storing board data)
- **Drag-and-Drop:** Implemented using JavaScript libraries

## Getting Started

### Prerequisites
Make sure you have the following installed on your system:
- [Node.js](https://nodejs.org/) (v12 or higher)
- [MongoDB](https://www.mongodb.com/)

### Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/Likhita2004/Kanban-Board-Master.git
   ```
2. **Navigate to the project directory:**
   ```bash
   cd Kanban-Board-Master
   ```
3. **Install the dependencies:**
   ```bash
   npm install
   ```

### Configuration
1. Create a `.env` file in the root directory of the project.
2. Add your MongoDB connection string to the `.env` file:
   ```
   MONGO_URI=your_mongodb_connection_string
   ```

### Running the Application
To start the development server, run:
```bash
npm start
```
Visit `http://localhost:3000` in your web browser to see the application in action.

## Usage
1. **Create a new board** by clicking on the "Add Board" button.
2. **Add lists** to your board to represent different stages.
3. **Create cards** within each list to track tasks.
4. **Drag and drop** cards between lists as tasks progress.

## Contributing
We welcome contributions to enhance the features and functionality of this Kanban board. To contribute, please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
If you have any questions or suggestions, feel free to open an issue or contact the project owner directly at [Likhita2004](https://github.com/Likhita2004).
