# IPLTEAM_project
🏏 Python IPL Teams Data Project

A beginner-friendly Python program that demonstrates how to store and manage complex data using dictionaries and lists. This project organizes IPL teams and player statistics using Python data structures and prints the information in different ways.

✨ Why This Project?

When working with real-world data, we often need to store multiple records with many attributes. Python’s dictionaries and lists are powerful tools for handling such structured data.

This project helps beginners learn how to:

Organize structured data

Work with nested dictionaries and lists

Access specific values from large datasets

Loop through complex data structures

🚀 Features

Stores 10 IPL teams with player statistics

Uses nested dictionaries and lists

Displays all team names

Prints player details for each team

Accesses specific players from selected teams

Shows how to iterate through structured datasets

🧠 Concepts Covered
1️⃣ Dictionaries

Used to store data in key–value pairs.

Example:

player = {"PN":"Rohit Sharma","RUNS":6211,"AGE":36}
2️⃣ Lists

Used to store multiple items in order.

Example:

MI_team = [player1, player2, player3]
3️⃣ Nested Data Structures

This project combines lists inside dictionaries.

Structure used:

IPL_teams
   │
   ├── Mumbai Indians
   │      ├── Player 1
   │      ├── Player 2
   │
   ├── Chennai Super Kings
   │      ├── Player 1
   │      ├── Player 2
4️⃣ Loops
Loop through team names
for team in IPL_teams.keys():
    print(team)
Loop through teams and players
for team, players in IPL_teams.items():
    print(team)
Loop through player details
for player in players:
    for key, value in player.items():
        print(key, value)
📊 Player Information Stored

Each player record contains:

Field	Description
PN	Player Name
JS	Jersey Number
WICKETS	Total wickets
RUNS	Total runs
BALLS	Balls faced
STRIKE_RATE	Batting strike rate
AVERAGE	Batting average
FIFTIES	Number of half-centuries
ROLE	Player role
AGE	Player age
💻 Example Code Snippet
for k, v in IPL_teams.items():
    print("TEAM:", k)

    for player in v:
        print(player["PN"])

This code prints each team name and its players.

📊 Sample Output
Mumbai Indians
Chennai Super Kings
Royal Challengers Bengaluru
Kolkata Knight Riders
Rajasthan Royals
Delhi Capitals
Sunrisers Hyderabad
Punjab Kings
Gujarat Titans
Lucknow Super Giants

Example player list:

TEAM: Mumbai Indians
Rohit Sharma
Hardik Pandya
Jasprit Bumrah
Suryakumar Yadav
Ishan Kishan
Tilak Varma
Piyush Chawla
Tim David
