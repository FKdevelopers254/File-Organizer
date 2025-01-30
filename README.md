
# File Organizer

A simple Python script that allows users to organize their files by creating folders and renaming them based on custom rules.

## Features

### Organize Files into Directories

* Create new folders with specified names (e.g., "Documents", "Images")
* Rename files within each folder using a bulk rename pattern
* Move files older than 30 days to an archive directory

## Requirements
     python import os from PIL import Image, ImageTk import tkinter as tk from tkinter import filedialog, messagebox, ttk import json

### Usage

1. Clone the repository using `git clone https://github.com/your-username/file-organizer.git`
2. Run the script using `python file_organizer.py` in your terminal/command prompt
3. Select directories to organize and search files as needed (e.g., use the "Add Directory" button)
4. Use the GUI interface to customize settings, such as custom rules for renaming and handling duplicates

## Configuration File

The script loads configuration data from a JSON file named `config.json` in the root directory of your repository.

**Configurations**

* Images: `.jpg`, `.jpeg`, `.png`, `.gif`, `.bmp`, `.svg`
* Documents: `.pdf`, `.docx`, `.txt`, `.xlsx`, `.pptx`, `.csv`
* Videos: `.mp4`, `.mkv`, `.mov`, `.avi`, `.flv`
* Music: `.mp3`, `.wav`, `.aac`, `.flac`
* Archives: `.zip`, `.rar`, `.tar`, `.gz`
* Code: `.py`, `.js`, `.html`, `.css`, `.java`, `.cpp`

## Custom Rules

You can customize the script by editing the `config.json` file to add or modify rules for renaming files. The available options are:

* Bulk rename pattern (e.g., "old_name_{counter}.txt")
* Handle duplicates: move back to original location
* Archive older than 30 days

## Example Use Cases

1. Organize a large directory of images and videos into folders based on custom rules.
2. Create an archive for files that are no longer needed, using the script's bulk rename feature.

### License

This software is licensed under the MIT License (see LICENSE file).

### Contributing

* Fork the repository
* Create a new branch for bug fixes and features
* Commit changes using `git commit -m "brief description of change"`
* Test your code thoroughly before merging into main branch

  ![Screenshot 2025-01-30 232511](https://github.com/user-attachments/assets/243ecbdc-f79d-47d8-ac33-d2e64bf5e4ea)

![Screenshot 2025-01-30 232455](https://github.com/user-attachments/assets/7b6b71cf-455d-4042-93fb-59a35feee528)

  
