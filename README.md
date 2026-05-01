**Overview**

Personal Reminders is a lightweight yet powerful Lua-based reminder system for EdgeTX radios. It allows you to store important dates such as birthdays, anniversaries, and custom reminders directly on your transmitter, and receive audio alerts when those dates match the current day.

It is designed to be simple, fast, and reliable, with a clean multi-page interface and visual indicators for active reminders.

**Features**

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

**Installation:**

- Download the Personal Reminders ZIP file
- Extract the contents of the ZIP file
- Find the last folder named Personal Reminders (folder will contain Personal Reminders.lua, rmd.lua & Reminders folder)
- Copy Personal Reminders.lua and paste into your transmitter's /SCRIPTS/TOOLS folder
- Copy Reminders folder and paste into your transmitter's /SCRIPTS/TOOLS folder
- Copy rmd.lua and paste into your transmitter's /SCRIPTS/FUNCTIONS folder

**Transmitter Setup:**

- Click on the SYS button
- Navigate to Global Functions
- Add a new Function with the below settings
- Trigger = 6POS1
- Function = Lua Script
- Value = rmd
- Repeat = x1
- Enable = True

<img width="479" height="270" alt="image" src="https://github.com/user-attachments/assets/b2627b9e-04de-490e-81d1-6bf24c40b368" />

<img width="476" height="270" alt="image" src="https://github.com/user-attachments/assets/b998db48-cd47-4593-9b3f-aa28e13e5c6e" />

<img width="480" height="271" alt="image" src="https://github.com/user-attachments/assets/4788042a-02fd-47bf-8c7a-2b7b0469023a" />

<img width="477" height="270" alt="image" src="https://github.com/user-attachments/assets/97df1013-bd1f-4854-bea7-6b709fc2d847" />





