# Pomodoro Timer

This simple Pomodoro timer application is built using Python's `tkinter` library. It helps you manage your work and break intervals, following the Pomodoro Technique for improved productivity.

![Pomodoro Timer Screenshot](https://github.com/itai-markovetzky/pomodoro-timer/blob/main/pomodoro_screenshot.png)
## Table of Contents

1. [Features](#features)
2. [How to Use](#how-to-use)
   - [Start Timer](#1-start-timer)
   - [Reset Timer](#2-reset-timer)
   - [Checkmarks](#3-checkmarks)
3. [Constants](#constants-adjustable-in-code)
4. [UI Elements](#ui-elements)
5. [Setup](#setup)
6. [About the Pomodoro Technique](#about-the-pomodoro-technique)
7. [Acknowledgements](#acknowledgements)

## Features

- **Work Timer:** Set to 25 minutes (adjustable in the code).
- **Short Break Timer:** Set to 5 minutes (adjustable in the code).
- **Long Break Timer:** Set to 20 minutes (adjustable in the code).
- **Reset Function:** Reset the timer and clear any completed work/break intervals.
- **Visual Cues:** Changes color and displays appropriate labels for work, short break, and long break intervals.
- **Checkmarks:** Keeps track of completed work intervals with checkmarks.

## How to Use

### 1. Start Timer

   - Click the "Start" button to begin the timer.
   - The timer will cycle through work intervals and breaks automatically.

### 2. Reset Timer

   - Click the "Reset" button to stop the timer and reset the session.

### 3. Checkmarks

   - Checkmarks will appear to track completed work intervals.

## Constants (Adjustable in Code)

- **Work Duration:** Set to 25 minutes (`WORK_MIN` variable).
- **Short Break Duration:** Set to 5 minutes (`SHORT_BREAK_MIN` variable).
- **Long Break Duration:** Set to 20 minutes (`LONG_BREAK_MIN` variable).

## UI Elements

- **Title Label:** Displays the current timer status (Work, Break).
- **Canvas:** Visual representation of the timer using a tomato image.
- **Start Button:** Initiates the timer.
- **Reset Button:** Stops the timer and resets the session.
- **Checkmarks Label:** Displays checkmarks to track completed work intervals.

## Setup

1. Install Python if not already installed.
2. Run the script using the command: `python your_script_name.py`.
3. Adjust the constants in the code to customize timer durations.

## About the Pomodoro Technique

The Pomodoro Technique is a time management method developed by Francesco Cirillo in the late 1980s. The technique uses a timer to break down work into intervals, traditionally 25 minutes in length, separated by short breaks. These intervals are known as "Pomodoros," the plural in English of the Italian word Pomodoro (tomato), after the tomato-shaped kitchen timer that Cirillo used as a university student.

The main steps of the Pomodoro Technique include:

1. **Choose a Task:** Select a task you want to work on.
2. **Set the Timer:** Set a timer for 25 minutes (1 Pomodoro).
3. **Work on the Task:** Focus on the task until the timer rings.
4. **Take a Short Break:** Take a short break (around 5 minutes).
5. **Repeat:** After completing four Pomodoros, take a longer break (around 20-30 minutes).

This technique aims to improve focus and productivity by breaking work into manageable intervals, preventing burnout, and maintaining a balance between concentration and rest.

## Acknowledgements

- **Angela Yu:** For inspiration and valuable insights through her educational courses.
- **Itai Markovetzky:** Author of this Pomodoro timer script.
