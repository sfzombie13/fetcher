# fetcher

**Version:** 1.3  
**Build Date:** March 31, 2025  
**Company:** Kanawha IT Security LLC  
**Copyright:** Kanawha IT Security LLC 2025

Fetcher is a standalone SFTP interface designed specifically for my clients. It provides a user-friendly, console-based interface that allows users to log in, browse remote directories, download individual files or entire directories, and navigate through folder structures securely and efficiently.

---

## Overview

Fetcher is a self-contained executable that:
- Connects to my SFTP server using user-supplied credentials.
- Presents an intuitive, menu-driven interface for file operations.
- Enables file downloads and directory navigation.
- Embeds all necessary dependencies (including `WinSCPnet.dll`) for ease of deployment.
- Is packaged using IExpress to ensure a single-file distribution.

---

## Features

- **Secure SFTP Connection:**  
  Connect to my SFTP server by simply entering your username and password.

- **Interactive Menu:**  
  Navigate the remote directory structure with options to:
  - Download individual files.
  - Display full directory contents (files and folders) and choose an item.
  - Download all files from the current folder.
  - Go up one level in the directory structure.
  - View a detailed help page.
  - Close the connection and logout.

- **Self-Contained Distribution:**  
  The EXE is fully self-contained; all dependencies (like `WinSCPnet.dll`) are embedded during packaging.

---

## Installation & Requirements

- **Operating System:** Windows (tested on Windows 10 and above)
- **Dependencies:**  
  No external dependencies are required at runtime. All necessary components are embedded.
- **Packaging:**  
  The executable was created using IExpress (for a fully standalone package) and PS2EXE for converting the PowerShell script.

---

## Usage

1. **Run the Executable:**  
   Double-click the `Fetcher.exe` file to launch the application. A PowerShell console window will open.

2. **Login:**  
   Enter your SFTP credentials when prompted.

3. **Navigation:**  
   Use the interactive menu to:
   - **Download a file:** Choose option 1 to see a list of files in the current folder and select one to download.
   - **Browse directories:** Choose option 2 to display the full directory contents. Select a folder to navigate into it or a file to prompt for download.
   - **Download all files:** Option 3 downloads all files (not folders) from the current directory.
   - **Go up one level:** Option 4 navigates to the parent directory.
   - **Help:** Option 5 displays detailed help information.
   - **Logout:** Option 6 closes the connection and exits the application.

4. **Help Screen:**  
   The help screen provides detailed instructions. It remains on-screen until you press Enter.


---



## License

© 2025 Kanawha IT Security LLC. All rights reserved.

---


