# dlk/os tracker

A personal habit tracker and pomodoro timer. Runs fully offline as a static HTML file. No login, no server, no internet required after download.

## Setup

Download `dlk-tracker.html` and open it in any browser. That is it.

## What is in it

**Today** -- your daily routine blocks, habit checkboxes, and a live completion ring. Tick habits off as you go through the day.

**Week** -- a full grid showing every habit across all seven days, plus completion bars and weekly stats for gym, FYP, NeetCode, and overall.

**Pomodoro** -- a work timer with configurable work, short break, and long break durations. Pick a session label before you start. Completed sessions log below the timer and are never cleared.

**Report** -- a habit breakdown table, your full all-time pomodoro log, a CSV download button, and a print button for a clean hard copy.

## Data and storage

Everything saves to your browser's localStorage. Nothing leaves your device. Habits reset automatically each Monday. Pomodoro sessions accumulate permanently and show up in the report tab across all weeks.

Do not clear your browser site data or you will lose your history.

## Customising the timer

Open the Pomodoro tab and change the work, break, or long break minutes directly. Settings save automatically.

## Downloading a report

Go to the Report tab and click "download CSV" to export your habit data and session log as a spreadsheet-compatible file.