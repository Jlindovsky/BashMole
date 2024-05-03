# Mole Script

Mole is a shell script designed for tracking file edits and managing a log of edited files. It provides functionalities to open files, list edited files, and manage logs based on various criteria such as group assignments, dates, and file popularity.

## Usage

```sh
mole [OPTIONS] [ARGUMENTS]
```

## Options

- `-h`: Display the help message.
- `-g GROUP`: Assign opened file to a specified group.
- `-b DATE`: Filter files edited before the specified date.
- `-a DATE`: Filter files edited after the specified date.
- `-m`: Select the most frequently edited file.
- `list`: Display a list of edited files.
- `secret-log`: Generate a secret log of edited files.

## Arguments

- `FILE`: Specify the file to open or track.
- `DIRECTORY`: Specify the directory to track files in.

## Features

- **Opening Files**: Open a specified file for editing.
- **File Tracking**: Keep a log of edited files, recording the timestamp of each edit.
- **Listing Edited Files**: Display a list of files edited using the script, filtered based on specified criteria.
- **Group Assignments**: Assign edited files to specific groups for better organization and tracking.
