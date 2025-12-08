Student Record Management System (C) This project is a console-based application implemented in C that provides a persistent system for managing student academic and administrative records. It utilizes binary file handling for data storage and ANSI escape codes for an enhanced, visually distinct user interface.

Features Data Persistence: Records are saved to a binary file (student_records.dat) and loaded on startup.

Input Validation: Strict checks ensure data integrity for fields like Admission Number (must match APxxxxxxxxxxx format) and numerical ranges (e.g., GPA 0.0-10.0).

Structured UI: Uses ANSI escape codes to provide colorful, clear, and well-structured menus and output tables.

Core Functions: Add new records, view all records in a formatted table, search by Admission Number, manually save data, and delete the entire database.

Prerequisites To compile and run this application, you need a C compiler installed on your system, such as GCC or Clang.

GCC (GNU Compiler Collection)

A Standard Terminal: Must support ANSI escape codes (most modern terminals like PowerShell, Command Prompt, macOS Terminal, and Linux terminals do).


