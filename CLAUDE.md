# Course Calendars

## Purpose

This repository contains Rose-Hulman Institute of Technology course calendars maintained by Dr. Fisher, a professor in Terre Haute, Indiana, who teaches both Mechanical Engineering and Computer Science courses.

The current priority is updating the Fall 2026-2027 calendars from prior course schedules while preserving the existing course content.

## Courses

- **ME230 Mechatronics**
- **ME435/CSSE435 Robotics Engineering**
  - ME435 and CSSE435 are cross-listed names for the same course.
  - Use `ME435` as the short name when referring to the course unless the distinction matters.
- **CSSE242 Programming in the Community**
  - This course is part of the teaching context, but this repository currently contains calendar files for ME230 and ME435 only.

## Repository Layout

- `ME230/`
  - `fall_2024_2025.html`: prior fall reference schedule
  - `spring_2025_2026.html`: prior spring reference schedule
  - `fall_2026_2027.html`: current ME230 fall schedule to update
- `ME435/`
  - `spring_2024_2025.html`: prior spring reference schedule
  - `fall_2026_2027.html`: current ME435/CSSE435 fall schedule to update
- `Rose Calendars/2026-27 Academic Year Calendar.txt`: institutional calendar and source of truth for Fall 2026-2027 dates, holidays, breaks, and examination periods

## Current Calendar Work

The Fall 2026-2027 classes begin on **Thursday, September 3, 2026**. Fall quarter schedules begin with an unusual short week:

- The first Thursday is called **Week 0**.
- The first ordinary week divider follows the Week 0 meeting(s), as shown by the prior fall ME230 schedule.
- Subsequent week dividers must reflect the actual instructional weeks after holidays and breaks, not simply the spring-quarter numbering.

The official Fall 2026-2027 calendar includes these dates relevant to the schedule updates:

- September 3: classes begin
- September 7: Labor Day holiday; no class
- October 8-9: Fall Break; no classes
- November 16-19: final examinations
- November 23: fall term ends

Consult the institutional calendar file before assigning dates or inserting/removing break and week-divider rows. Check that every displayed weekday agrees with its date.

## Editing Rules

For the current update, change only:

1. The weekday and date displayed in each calendar meeting row.
2. The week-divider labels and their placement.
3. Required holiday, break, or final-exam divider rows when the 2026-2027 institutional calendar requires them for the schedule structure.

Preserve the existing instructional content, links, HTML structure, styling, day numbers, and course-specific wording unless a date or week-divider change makes a structural adjustment necessary. Do not modernize or reformat the HTML as part of calendar date work.

The `Day` column counts class meetings and is separate from the `Week` divider labels. Use it to keep meeting order intact when holidays or quarter-specific calendar patterns create irregular weeks.

## Working Expectations

- Read the relevant prior schedule and the institutional calendar before editing.
- Treat prior fall schedules as the model for fall `Week 0` handling.
- Use exact 2026 dates and weekday names/abbreviations consistently with the existing file.
- Verify all edited dates against the 2026-27 institutional calendar and the weekday represented in each row.
- Keep ME230 and ME435/CSSE435 content independent; do not copy content between them merely because their dates align.
- Make focused edits and avoid unrelated cleanup.
- Do not create commits unless explicitly requested.
