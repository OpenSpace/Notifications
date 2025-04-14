# Notifications
A repository that contains notifications that are displayed in the Launcher of OpenSpace. Apart from the GitHub-specific files (README.md and LICENSE.md), each other file in this repository contains the contents for notifications of a specific version or the master branch. The file for the `master` branch must be named `master.txt` and the files for specific versions should be named with the full version number with the `.txt` extension. For example the file containing the notifications for version 0.21.0 should be called `0.21.0.txt`, the one for 0.21.1 should be called `0.21.1.txt` etc.

If a notification message is important for multiple versions, it must be added to each file individually.

## File Format
Each notification file has to follow these rules:

  1. Each entry must start with the date at which the notification was issues in the first line. The date has to be in the form YYYY-MM-DD and the line must not contain any other text but the date
  2. The following line contains the informational text that should be displayed as the notification.
  3. Subsequent entries must be separated by a completely empty line
  4. The notifications must be in reverse chronological order, meaning that the most recent notification is at the top of the file

### Example
```
2022-01-01
Notification 3 Text

2021-01-01
Notification 2 Text

2020-01-01
Notification 1 Text
```
