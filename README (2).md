# StreakForge

StreakForge is a simple console application written in C++. It tracks daily habits (such as prayer, gym, or coding). The more days in a row you do a habit, the more points and streak you earn. Good consistency also unlocks discount coupons.

This project is made for the Object-Oriented Programming Lab, BSE-2 (Special), Bahria University H11 Campus Islamabad, Fall 2026.

## Team
1. Rabbia Zulfiqar (09-131252-070)
2. Mahad Saeed (09-131252-050)

## Features
1. Add, view, search and delete habits
2. Mark a habit as done, which increases its streak and points
3. Streak Freeze: protects your streak after one missed day (2 freezes per user)
4. Weekly Rank Report: shows habits ranked by points
5. Reward coupons: discount coupons for Bronze, Silver and Gold badges
6. Saves data to a file, so records remain after the program is closed

## Project structure
1. `src` folder: source code files (.h and .cpp)
2. `data` folder: sample data file (streakforge_data.txt)
3. `docs` folder: project proposal PDF and class diagram
4. `README.md`: this file, with project information
5. `.gitignore`: files that GitHub should not upload

## How to compile and run
1. Install a C++ compiler on laptop (g++ version 11 or newer).
2. Open the project folder in a terminal and run:
   `g++ -std=c++17 src/*.cpp -o streakforge`
3. Then start the program with:
   `./streakforge`
   (On Windows: `streakforge.exe`)

## Status
1. Proposal submitted
2. Habit classes (inheritance and polymorphism): not started
3. HabitTracker, menu and file handling: not started
4. Coupon system: not started
5. Testing and final report: not started
