# StreakForge

A gamified habit tracker with Streak Freeze, Weekly Rank Report and real-life style reward coupons.
Built in C++ as the group project of **Object-Oriented Programming Lab** (BSE-2 Special), Bahria University H11 Campus Islamabad, Fall 2026.

**Instructor:** Engr. Saad Mazhar Khan  |  **Course Teacher:** Engr. Aleem Ahmed

## Team
| Name | Registration No. |
|---|---|
| Rabbia Zulfiqar | 09-131252-070 |
| Mahad Saeed | 09-131252-050 |

## What does it do?
Users add habits (Daily, Weekly or Smart), mark them done every day and earn streaks and points.
Points give Bronze, Silver and Gold badges. Every new badge gives a discount coupon in the user's favorite category.
All data is saved in a file and loaded again when the program starts.

## Features
- Add, view, search and delete habits
- Mark habit as done (streak and points increase)
- Streak Freeze (protects a streak after a missed day, 2 freezes per user)
- Weekly Rank Report (habits ranked by points, with badges)
- Reward coupons (Bronze 20%, Silver 50%, Gold 60%)
- View my coupons
- Save and load data from a file

## OOP concepts used
Classes and objects, encapsulation, abstraction (abstract class `Habit`), constructors and destructors, `this` pointer,
dynamic memory, function overloading, function overriding, static members, friend function, operator overloading,
single and multiple inheritance, runtime polymorphism, exception handling, file handling, templates and STL (`vector`, `map`, `sort`).

## Project structure
```
StreakForge/
├── src/         source code (.h and .cpp files)
├── data/        sample data file (streakforge_data.txt)
├── docs/        proposal, class diagram and final report
├── README.md
└── .gitignore
```

## How to compile and run
Needs a C++ compiler (g++ 11 or newer).
```
g++ -std=c++17 src/*.cpp -o streakforge
./streakforge        (on Windows: streakforge.exe)
```

## Status
- [x] Proposal submitted
- [ ] Habit classes (inheritance, polymorphism)
- [ ] HabitTracker, menu and file handling
- [ ] Coupon system
- [ ] Testing and final report
