# ChefMate

![Logo](assets/CHEFMATE.png)

ChefMate is a CLI tool for automating CodeChef tasks via an interactive menu-driven interface. It streamlines the workflow of logging in, opening contests, solving problems, running demo test cases, submitting solutions, and tracking problem statuses in real time.

## Features

- **Interactive Mode**: User-friendly, arrow-key-driven menu
- **Automated Login**: Seamlessly sign into CodeChef
- **Contest Management**: Open contests by ID directly in browser
- **Problem Solving Support**: Scaffold and open solution files locally
- **Demo Test Case Checking**: Run and verify sample tests before submission
- **Automated Submission**: Submit solutions without leaving the terminal
- **Problem Tracker**: View status (✅ done | 🟡 pending | ❌ wrong)
- **Configuration Management**: Easily reconfigure user preferences
- **Clear Terminal**: Wipe the screen for a fresh view

## Installation

You don’t need to clone any repository — just install via pip:

```bash
pip install chefmate
```

That’s it!

## Usage

Run ChefMate in interactive mode:

## For Windows Users
```bash
chefmate
```

## For Linux Users
```bash
python3 -m chefmate.cli
```

Yes, it's that easy, just use 'chefmate' and you're ready to go.

## Initial Configuration

On first run, ChefMate will prompt you to configure key settings:

- **Username**: Your CodeChef username
- **Password**: Your CodeChef password (input hidden)
- **Default Solution Path**: Local directory or file path pattern for solutions
- **Chrome User Data Directory** (optional): Path to Chrome profile data
- **Chrome Profile** (optional): Profile name within Chrome
- **Preferred Language**: Language for submissions (C++, Python 3, Java, etc.)
- **Preferred Editor**: Editor to open solution files (default, VS Code, Sublime, etc.)

![First Configure](assets/First_Configure.gif)

## Interactive Mode Options

When you launch interactive mode, you’ll see a menu:

```text
==================================================
ChefMate Interactive Mode
==================================================
```

Use arrow keys to navigate and Enter to select any of the following:

| Option                         | Description                                           | Example GIF/Screenshot                      |
|--------------------------------|-------------------------------------------------------|---------------------------------------------|
| **Login**                      | Authenticate with CodeChef                            | ![Logging In](assets/Logging_In.gif)       |
| **Open Contest**               | Open a CodeChef contest by ID in your browser         | ![Open Contest](assets/Open_Contest_Page.gif) |
| **Solve Problems**             | Scaffold and open solution templates locally          | ![Solve Problems](assets/Solve_Problems.gif) |
| **Check Demo test cases**      | Run sample tests on your solution                     | ![Demo Tests](assets/Demo_Test_Cases.gif)  |
| **Submit Solution**            | Submit your solution to CodeChef                      | ![Submitting Solution](assets/Submitting_Solution.gif) |
| **Problem Tracker**            | View current status of each problem                   | ![Tracker](assets/Problem_Tracker.png)     |
| **Re-configure ChefMate**      | Update any configuration options                      |                                             |
| **Clear Terminal**             | Clear your terminal screen                            |                                             |
| **Logout**                     | Sign out of your CodeChef session                     |                                             |
| **Exit / Logout and Exit**     | Quit interactive mode (and logout if selected)        |                                             |

## Visual Walkthrough

### Start ChefMate

![Start ChefMate](assets/Start_ChefMate.gif)

### Logging In

![Logging In](assets/Logging_In.gif)

### Opening a Contest

![Open Contest](assets/Open_Contest_Page.gif)

### Solving Problems

![Solve Problems](assets/Solve_Problems.gif)

### Checking Demo Test Cases

![Demo Test Cases](assets/Demo_Test_Cases.gif)

### Submitting a Solution

![Submitting Solution](assets/Submitting_Solution.gif)

### Problem Tracker

![Problem Tracker](assets/Problem_Tracker.png)

## License

This project is released under the MIT License. See [LICENSE](LICENSE) for details.
