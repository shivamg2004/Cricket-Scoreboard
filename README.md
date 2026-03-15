# Cricket Scoreboard C++

A terminal-based cricket scoreboard application implemented in C++ that covers various Data Structures and Algorithms (DSA) topics.

## Features

- Real-time tracking of runs and strike rotation using Stacks and Linked Lists.
- Logic for special match events: wickets, wides, no-balls, byes, leg-byes.
- Bowling economy stats.
- Covers DSA topics: Linked Lists, Stacks, Queues, Binary Search Trees, Graphs, Sorting (Bubble Sort), Searching (Linear Search), Hash Tables.

## How to Compile and Run

### Prerequisites
- C++ compiler (e.g., g++)

### Compilation
```bash
g++ main.cpp -o cricket_scoreboard
```

### Running
```bash
./cricket_scoreboard
```

On Windows:
```cmd
g++ main.cpp -o cricket_scoreboard.exe
cricket_scoreboard.exe
```

## Usage

The program simulates a cricket match with two innings.

- Enter ball outcomes: 0,1,2,3,4,6 for runs; w for wicket; wd for wide; nb for no-ball; b for bye; lb for leg-bye.
- Type 'end' to finish an innings.
- The scoreboard updates after each ball.

## DSA Coverage

- **Linked List**: Used for storing team players.
- **Stack**: Tracks ball-by-ball runs.
- **Queue**: Manages batsmen order.
- **Binary Search Tree**: Stores and sorts player runs.
- **Graph**: Represents player partnerships.
- **Sorting**: Bubble sort for player stats.
- **Searching**: Linear search in arrays.
- **Hash Table**: Simple hash for player lookups.

## Troubleshooting

- Ensure C++11 or later is supported by your compiler.
- If compilation fails, check for syntax errors or missing includes.