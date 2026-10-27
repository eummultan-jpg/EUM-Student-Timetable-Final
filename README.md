# EUM Student Timetable

Professional 1920x1080 student timetable display for Emerson University Multan.

## Version 1.4

### Updates

- Fixed current class (NOW) detection.
- Fixed next upcoming class detection.
- Added chronological sorting of timetable entries.
- Improved timetable spacing and layout.
- Fixed handling of empty timetable cells.
- Improved Pakistan Standard Time (PKT) clock handling.
- Improved AM/PM handling for morning and evening schedules.
- Improved MS evening timetable display.
- Improved timetable display stability and rendering.

## Included timetable sources

- 1st Semester — All Programmes
- Artificial Intelligence
- Computer Science
- Cyber Security
- Data Science
- Information Technology (2-Year)
- Information Technology
- MS Programmes
- Software Engineering

The supplied Fall 2026 timetable PDFs were converted into `timetable.json`.

## Automatic behavior

- Uses the Raspberry Pi system clock.
- Uses Pakistan Standard Time (PKT / UTC+5).
- Detects Monday-Friday automatically.
- Highlights the current class.
- Shows the next upcoming class.
- Sorts timetable entries chronologically.
- Shows JUMMAH BREAK where present in the source timetable.
- Automatically rotates through the sections.
- Continues to work offline.
- Refreshes instantly if `timetable.json` is replaced by a package service or another local process.

## Important

This package contains the timetable data extracted from the supplied Fall 2026 PDFs.

When a new semester timetable is issued, regenerate or replace `timetable.json` with the new official timetable data and publish the updated package.

## Release Information

**Version:** 1.4  
**Semester:** Fall 2026  
**Institution:** Emerson University Multan  
**Faculty:** Faculty of Computing & Emerging Technologies  
**Resolution:** 1920x1080  
**Platform:** Raspberry Pi / info-beamer
