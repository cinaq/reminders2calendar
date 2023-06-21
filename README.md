# Reminders2Calendar

This repo contains a collection of scripts that synchronizes reminders from Reminders.app to Calendar.app. It works best on iOS. 

Background info located at https://cinaq.com/blog/2022/11/22/the-missing-link-between-reminders-and-calendar-app-on-ios/

## Installation

### iOS (iphone, ipad)

- Open Shortcuts.app
- Reminders list name: this is the name of your reminders list. It also must match with your calendar name.
- Import [Reminders2Calendar](https://www.icloud.com/shortcuts/310cffa3a4254701bb8ead6ee33e8854) into your shortcuts on your iPhone.
- Create a new shortcut. I call it **Reminders2Calendar Personal**

### Mac OSX (macbook)

- On your mac open Shortcuts.app
- import the shortcut files from this repo
- configure the shortcuts to your liking

## Changelog

### 2023-06-21 [icloud link](https://www.icloud.com/shortcuts/6a2dc180452241409f4ecf067380693a)

- bugfix to mark completed reminders older than today

### 2023-06-18 [icloud link](https://www.icloud.com/shortcuts/310cffa3a4254701bb8ead6ee33e8854)

- refactor to use wide range of calendar event search to simplify the logic. No need to do 2 searches anymore

### 2023-05-19 [icloud link](https://www.icloud.com/shortcuts/8d90c9b4839945df926a8102d8f8d556)
- Fixes duplication of completed reminders in the calendar

### 2023-05-18 [icloud link](https://www.icloud.com/shortcuts/8c7790366cec41828b51a3b806abc4d2)
- Fixes event duplication

