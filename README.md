Virtual Office Attendance System
Overview
The Virtual Office Attendance System is a 2D interactive desktop application built using the LÖVE 2D framework (Lua-based) that simulates a virtual office environment for tracking employee attendance. The application displays a top-down view of an office with a grid of desks (one for HR and eight for staff members). Users can click a desk to trigger an animated character to enter or exit, marking attendance with timestamps. The system records entry and exit times, displays them above desks, and persists data using local storage. A summary table and reset functionality are included for ease of use.
Features

Interactive Office Layout: A 3x3 grid of desks (HR, Staff 1–8) with clickable rectangular desks and chair icons.
Entry Animation: Clicking an unoccupied desk triggers a character sprite to walk from the office entrance to the desk, sit down, and record the entry time (HH:MM:SS AM/PM).
Exit Animation: Clicking an occupied desk triggers the character to stand, walk back to the entrance, and record the exit time.
Persistent Data: Attendance data (entry/exit times) is saved locally to persist across sessions.
Summary Table: A table below the office layout displays all desks' entry and exit times.
Reset Functionality: A reset button clears all attendance data and resets the scene.
Responsive Design: Adapts to different screen sizes for desktop use
Optional Audio: Subtle sound effects for walking and sitting (if implemented).
Visuals: Simple office background (walls, doors, desks) using sprites or basic shapes.


CHECK OUT :
https://cabin-clock-in.lovable.app/

