# My Home

## Brief Description

My Home is a personal home management and organisation app built with Flutter for Android.

It brings household tasks, projects, money tracking, bills, rooms, reminders and other home-related information into one place. The app is designed to be simple to use while allowing custom categories, recurring tasks, notifications, dark mode and flexible project types such as home improvement, personal goals and learning new skills.

## Features

- Home dashboard with useful summaries
- Room management
- Household chores and recurring tasks
- Custom task start and due dates
- Projects and project tasks
- Custom project types including:
  - Home improvement
  - Learning / skill
  - Personal
  - Fitness / health
  - Maintenance
  - Other
- Money and transaction tracking
- Custom expense categories
- Bills and recurring bills
- Reusable bill categories
- Upcoming bills displayed on the Home screen
- Daily task notifications
- Notification options for:
  - Overdue tasks
  - Tasks due today
  - Pending project tasks
  - Upcoming bills
- Custom notification time
- Test notification function
- Light, Dark and System theme modes
- Custom Android app icon
- Local data storage
- Backup and restore support
- Backward compatibility with older My Home backups

## Data and Privacy

My Home stores its data locally on the device.

The app does not require an online account for normal use.

Backups can be exported and restored, including backups created by earlier compatible versions of the app.

## Notifications

Notifications can be enabled from:

**More → Settings**

Users can choose which types of reminders they want to receive and select a preferred daily notification time.

Android notification permission must be granted for reminders to appear.

## Backup and Restore

It is recommended to create regular backups from within the app.

Newer versions of My Home are designed to restore compatible backups from earlier versions. Where newer fields do not exist in an old backup, sensible default values are used.

## Technology

My Home is built using:

- Flutter
- Dart
- SQLite
- flutter_local_notifications
- Workmanager
- Android SDK

The project can be built using Google Colab using the supplied notebook.

## Building the App

Run the supplied Google Colab notebook from the first cell through to the build cell.

Before building the APK, Flutter Analyze should report:

`No issues found!`

The release APK is generated under:

`build/app/outputs/flutter-apk/app-release.apk`

## Current Version

Current stable test version:

**v4.5.7**

## Status

My Home is currently under active development.

New features and improvements may be added over time, including further task management, finance tools, reminders, dashboard improvements and additional customisation options.
