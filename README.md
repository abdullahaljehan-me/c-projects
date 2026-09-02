# C Programming Projects Portfolio

Welcome to my C projects repository. This collection serves as a central index for my C programming journey, featuring a wide range of applications from basic algorithms to advanced systems-level programming.

Each project is designed to reinforce core concepts such as memory management, pointers, data structures, file I/O, and POSIX system APIs.

---

## 📂 Project Directory

### 🎮 Games & Simulations
* **[Magic Guess Game](#)** — Random number guessing with attempts, hints, difficulty levels, and score tracking.
* **[Tic-Tac-Toe](#)** — Two-player board game using 2D arrays, functions, and win/draw detection.
* **[Snake Game](#)** — Real-time game loop, keyboard input, collision detection, scoring, and difficulty levels.
* **[Maze Solver](#)** — Pathfinding via DFS/BFS, stacks/queues, backtracking, and path reconstruction.
* **[Sudoku Solver](#)** — Recursive backtracking with constraint checking over a 9x9 board.

### ⚙️ Systems & Utilities
* **[Digital Clock & Timer](https://github.com/abdullahaljehan-me/digital-clock-c)** — Real-time clock, countdown, stopwatch, and alarms using C time functions.
* **[Calendar Application](#)** — Monthly/yearly calendar generation, leap-year detection, and weekday calculation.
* **[Custom Memory Allocator](#)** — Implementation of custom `malloc` and `free` using a free list to understand heap management.
* **[File Manager / Explorer](#)** — Browse, create, delete, and rename files; inspect metadata and interact with the Linux filesystem via C APIs.
* **[Terminal Text Editor](#)** — Cursor movement, insert/delete, buffers, file load/save, and undo/redo.
* **[Mini Linux Shell](#)** — Command parsing, `fork()`/`exec()`/`wait()`, pipes, redirection, background jobs, and signals.

### 🗄️ Management Systems
* **[Contact Management System](https://github.com/abdullahaljehan-me/contact-management-system-c)** — Add, edit, delete, search, and sort contacts using structs, arrays, and file I/O.
* **[Authentication System](#)** — Registration/login with validation, password storage, login attempts, and file persistence.
* **[Student & Attendance Management System](#)** — Student records, attendance tracking, percentage calculation, and reports.
* **[Library Management System](#)** — Book/member management, issue/return, catalog search, and overdue dues.
* **[Bank Management + ATM System](#)** — Account creation, PIN auth, deposits/withdrawals/transfers, and transaction history.
* **[Billing & Inventory System](#)** — Product/stock management, bill calculation, receipts, and sales tracking.
* **[Bus/Railway Reservation System](#)** — Seat maps, booking, cancellation, availability checking, and ticket generation.
* **[Voting/Election Simulation](#)** — Voter registration, authentication, duplicate-vote prevention, and vote tallying.
* **[Campus Management System (Capstone)](#)** — A modular application integrating auth, students, courses, attendance, GPA, fees, library, and reports.

### 🧠 Data Structures & Algorithms
* **[Expression Calculator / Evaluator](#)** — Operator precedence parsing, postfix conversion, stacks, and recursion.
* **[Data Structures & Algorithms Library](#)** — Dynamic arrays, linked lists, stacks, queues, trees, graphs, and sorting/searching algorithms built from scratch.
* **[Hash Table](#)** — Collision handling (chaining/open addressing), load-factor resizing, and custom hash function design.
* **[Huffman File Compression Tool](#)** — Frequency analysis, binary trees, priority queues, and bit-level binary I/O.
* **[Basic Regex Engine](#)** — NFA-based pattern matcher supporting literals, `*`, `.`, and anchors.

### 🌐 Networking & Databases
* **[TCP Socket Chat Application](#)** — Multi-client server, broadcasting, private messages, and concurrent connections.
* **[Mini Database Engine](#)** — Persistent record storage, CRUD operations, indexing, binary serialization, and simple query commands.

### 📚 Academic & Productivity
* **[Exam & Quiz System](#)** — Question bank, randomized questions, automatic scoring, and persistent question data.
* **[CPU Scheduling Simulator](#)** — Simulates FCFS, SJF, Priority, and Round Robin; calculates waiting/turnaround/response times and CPU utilization.

---

## 💻 Setup and Compilation

Most projects in this repository can be compiled using the GCC compiler. Navigate to the specific project folder and run:

```bash
gcc -o program_name source_file.c
./program_name
