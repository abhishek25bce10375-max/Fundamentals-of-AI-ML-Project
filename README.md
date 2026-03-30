# Fundamentals-of-AI-ML-Project
# AI Study Planner

## Overview of the Project

The AI Study Planner is a simple yet effective system designed to help students manage their study time in a smarter way. Many students struggle with planning their daily study schedule, especially when they have multiple subjects with different difficulty levels and varying performance.

This project solves that problem by creating a personalized timetable based on user input. The user provides a list of subjects, difficulty levels for each subject, marks obtained, and total study hours available. Using this information, the system analyzes which subjects need more attention.

The core logic of the project is based on a weighted decision-making approach, which is a basic concept of Artificial Intelligence. In this approach, each subject is assigned a weight based on two main factors:

1. Difficulty level (how hard the subject is)
2. Weakness level (based on marks obtained)

Subjects that are more difficult or where the student has scored lower marks are given higher priority. The program then distributes the total available study time proportionally based on these weights.

After calculating the time allocation, the system generates a structured timetable starting from a fixed time (e.g., 8:00 AM). It also includes short breaks between study sessions to make the schedule more practical and realistic.

Finally, the timetable is displayed on the screen and saved as a text file for future use. This project demonstrates how basic AI concepts can be applied to solve real-world problems in a simple and user-friendly way.

---

## Features (Detailed)

Personalized Study Plan
  Generates a unique timetable based on user input instead of using a fixed schedule.

* **Weak Area Detection**
  Automatically identifies weak subjects using marks (lower marks = higher priority).

* **Smart Time Allocation**
  Distributes study hours based on both difficulty and performance.

* **Timetable Generation**
  Creates a clear and structured daily timetable with proper time slots.

* **Break Management**
  Adds short breaks between study sessions to improve productivity.

* **File Saving Feature**
  Saves the generated timetable into a `timetable.txt` file for later reference.

* **Command-Line Interface**
  Simple and easy-to-use interface that runs directly in the terminal.

## Technologies / Tools Used

* **Python**
  The main programming language used to build the project. Basic Python concepts like loops, lists, and conditional logic are used.

* **datetime Module**
  Used to handle time calculations such as adding hours and minutes and formatting time for the timetable.

* **File Handling**
  Used to save the generated timetable into a text file.

* **Command Line Interface (CLI)**
  The project runs entirely in the terminal, making it simple and lightweight.

Code Editor / IDE**
  Tools like VS Code, PyCharm, or Notepad++ can be used to write and run the code.


 ## Steps to Install & Run the Project
 Step 1: Install Python

Make sure Python is installed on your system.
You can check by running:

```bash id="n1r2gi"
python --version


Step 2: Clone the Repository

Download the project from GitHub using:

bash id="e2u4qx"
git clone https://github.com/your-username/your-repo-name
cd your-repo-name


 Step 3: Navigate to Project Folder

Move into the project directory:

```bash id="qntgpi"
cd src


Step 4: Run the Program

Execute the program using:

```bash id="gkq0dy"
python main.py


Instructions for Execution / Testing

1. Run the program using the command mentioned above.

2. Enter the required inputs when prompted:

   * Subjects (comma separated)
   * Difficulty levels (1–5)
   * Marks (out of 100)
   * Total study hours

   Example:

   ```id="0dtvsh"
   Math, Physics, English
   5,4,2
   40,60,85
   6
   ```

3. The system will process the input and generate a timetable.

4. The output will be displayed on the screen in this format:

   ```id="gqxzsj"
   08:00 - 10:30 -> Math
   10:30 - 10:45 -> Break
   10:45 - 12:30 -> Physics
   ```

5. A file named `timetable.txt` will be automatically created in the project folder.

6. Open the file to view or reuse your saved timetable.
