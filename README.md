**Overview**

Personal Reminders is a lightweight yet powerful Lua-based reminder system for EdgeTX radios. It allows you to store important dates such as birthdays, anniversaries, and custom reminders directly on your transmitter, and receive audio alerts when those dates match the current day.

It is designed to be simple, fast, and reliable, with a clean multi-page interface and visual indicators for active reminders.

**Features**

Features
- 7 Fixed Date Slots
  - My Birthday
  - Wedding Anniversary
  - Wife, Mom, Dad, Sister, Brother birthdays
- 6 Custom Reminders
  - Fully editable text (20 characters)
  - Assign any date to any custom event
- Smart Audio Alerts
  - Plays “Happy Birthday” for your birthday
  - Plays “You have a reminder” for all other events
  - If both occur on the same day → plays both (in order)
- Automatic Background Detection
  - Runs on transmitter startup
  - Checks all reminders instantly
  - Triggers only once per power cycle
- Visual Notification System
  - Flashing green indicator next to active reminders
  - Works on both main reminder pages
  - Clean and non-intrusive
- Multi-Page UI
  - Page 1: Fixed reminders (view)
  - Page 2: Custom reminders (view)
  - Page 3: Fixed reminders (edit)
  - Page 4: Custom reminders (edit)
- Persistent Storage
  - All data saved to data.txt
  - Automatically loaded on startup
