Student Record Management System (C) This project is a console-based application implemented in C that provides a persistent system for managing student academic and administrative records. It utilizes binary file handling for data storage and ANSI escape codes for an enhanced, visually distinct user interface.

Features Data Persistence: Records are saved to a binary file (student_records.dat) and loaded on startup.

Input Validation: Strict checks ensure data integrity for fields like Admission Number (must match APxxxxxxxxxxx format) and numerical ranges (e.g., GPA 0.0-10.0).

Structured UI: Uses ANSI escape codes to provide colorful, clear, and well-structured menus and output tables.

Core Functions: Add new records, view all records in a formatted table, search by Admission Number, manually save data, and delete the entire database.

Prerequisites To compile and run this application, you need a C compiler installed on your system, such as GCC or Clang.

GCC (GNU Compiler Collection)

A Standard Terminal: Must support ANSI escape codes (most modern terminals like PowerShell, Command Prompt, macOS Terminal, and Linux terminals do).

Stack vs Queue Visualizer This project is a simple, interactive web application designed to visually demonstrate the fundamental differences between two essential data structures: the Stack and the Queue.

It allows users to perform common operations (push/pop, enqueue/dequeue, peek, etc.) and observe the Last-In, First-Out (LIFO) behavior of the Stack and the First-In, First-Out (FIFO) behavior of the Queue in real-time.

Features Interactive Visualization: Elements are added and removed from the structures, providing a clear visual of the LIFO and FIFO principles.

Bounded Capacity: Users can set a MAX_SIZE to enforce limits, triggering Stack/Queue Overflow warnings when the capacity is exceeded.

Core Operations:

Stack: PUSH, POP, PEEK, IS EMPTY?, IS FULL?

Queue: ENQUEUE, DEQUEUE, PEEK, IS EMPTY?, IS FULL?

Operation Log: A dedicated log box records every action taken, including warnings and success messages (e.g., PUSH → X, STACK OVERFLOW, PEEK → Y).

Visual Feedback: Operations are accompanied by color flashes (green for success/peek, red for errors/warnings) and element animations.

Pure JavaScript/HTML/CSS: No external libraries or frameworks are required.

Technology Stack HTML5: Structure of the application.

CSS3: Styling and layout, using a modern, clean design (Poppins font, smooth transitions).

Vanilla JavaScript (ES6+): Core logic for managing the data structures, handling user input, and updating the DOM.

Getting Started Since this is a single HTML file with embedded CSS and JavaScript, deployment and running are incredibly simple.

Prerequisites You only need a modern web browser (Chrome, Firefox, Edge, Safari, etc.).

Running the Visualizer Save the entire provided code block as a file named visualizer.html.

Double-click the visualizer.html file.

The application will open immediately in your default web browser.
