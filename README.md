✅ Daily Task Manager
📅 A simple weekly productivity tracker built in C

Developer: Vinuthna Inti

📝 Project Description

Daily Task Manager is a C-based console application that helps users organize, track, and evaluate their daily progress across an entire week.

The program supports viewing previous results and starting a fresh week anytime.

🚀 Features

🗓️ Task Scheduling for the Week: Add tasks once — they repeat for all days.

✅ Daily Completion Tracking: Mark which tasks you’ve completed each day.

💾 Progress Persistence: Saves data in a text file (weekssss_results.txt) automatically.

📊 Completion Percentage: Calculates how productive each day was (in %).

🔁 Weekly Reset Option: Start a new week with all values reset to 0%.

📈 View History: View progress of previously completed days anytime.

🧠 How It Works

The user enters the number of tasks and their descriptions.

The program asks for the current day (Sunday–Saturday).

For each task, the user inputs whether it was completed (y/n).

The program calculates the percentage of tasks completed that day.

Progress is saved to a text file, which is reloaded automatically next time.

Users can choose to:

Move to the next day

View progress for all days

Exit the program

⚙️ File Handling

File used: weekssss_results.txt

Purpose: To store daily completion percentages for all 7 days.

Automatically loads data on program start and saves updates after each session.

🛠️ Technologies Used
Category	Details
Language	C
Compiler	GCC / MinGW / Turbo C
File I/O	Standard I/O with fopen, fprintf, fscanf
Storage	Text file (weekssss_results.txt)
🧩 Functions Overview
Function	Purpose
loadResults()	Reads weekly progress data from file
saveResults()	Saves current progress into file
getDayIndex()	Returns index (0–6) of the entered weekday
displayPreviousDays()	Displays recorded progress for previous days
resetWeek()	Clears all results to start a new week
💡 Key Concept

This project demonstrates practical use of:

File handling (fopen, fclose, fscanf, fprintf)

Arrays and strings

Loops and conditionals

Persistent storage

Basic productivity tracking logic
