# progress-clocks

-A simple and elegant JavaScript Progress Clock that displays real-time updates of the current date and time, along with a unique visual representation of the progress of the day, month, and year. This README provides an overview of the PC, as well as a brief description of the Progress Clock's functionality.

### Table of Contents

#### Getting Started

#### Understanding the ProgressClock Class

#### Resources

## Getting Started
-The Progress Clock is a JavaScript-based application that displays a visual representation of the current date and time.

## Understanding the ProgressClock Class
-The ProgressClock class is responsible for handling the core functionality of the Progress Clock. It calculates and displays the current date, time, and the progress of the day, month, and year.

## Constructor
-The ProgressClock class is constructed with a query selector string that points to the HTML element where the clock will be displayed. It initializes the clock with default values and immediately starts updating.

## Methods
-getDayOfWeek(day): Returns the name of the day of the week for a given day (1 for Monday, 2 for Tuesday, etc.).

-getMonthInfo(mo, yr): Returns an object with the name of the month and the number of days in the month for a given month (1 for January, 2 for February, etc.) and year.

-update(): Updates the clock's display with the current date and time. It calculates the progress of the day, month, and year and displays them visually. The clock automatically updates every second.

## Display
-The Progress Clock visually represents the date and time using rings and digits for various units:

"w": Day of the week (e.g., Monday).
"mo": Month name (e.g., January) with a progress ring.
"d": Day of the month with a progress ring.
"h": Hour with a progress ring.
"m": Minute with a progress ring.
"s": Second.
"ap": AM or PM.
The progress rings provide a unique visual representation of the day's progress, filling as time advances. When a unit's progress reaches 100%, the ring briefly animates as a full circle before resetting.

## Time Update
-The clock automatically updates every second, reflecting the real-time progress.

## Resources
-No additional resources are required for this Progress Clock. The code includes all the necessary functionality.