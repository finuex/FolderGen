# Auto File Organizer

A simple Python application with a graphical user interface (GUI) that helps you automatically organize files in a selected directory into subfolders based on their file extensions.

## 📦 Features

- Organize files into subfolders by their extensions.
- Automatically creates folders for each unique file type.
- Handles files without extensions by placing them in a `no_extension` folder.
- Easy-to-use GUI built with Tkinter.
- Clean, dark-themed interface with hover effects.

## 🖥️ GUI Preview

![Screenshot](screenshot.jpeg)

> You can click the "Pilih Direktori & Atur" button to choose a folder and begin organizing.

## 🚀 How to Run

### Requirements

- Python 3.x
- Tkinter (included by default in most Python installations)

### Steps

1. **Clone the Repository**

   ```bash
   git clone https://github.com/finuex/FolderGen.git
   cd FolderGen

2. **Run the Application**

   ```bash
   python main.py

3. **Using the App**

    - The app window will open.
    - Click the Pilih Direktori & Atur button.
    - Select the folder you want to organize.
    - The files will be sorted into subfolders named after their extensions.
  
## 🧠 How It Works
The application scans all files in the selected directory, extracts their extensions, and moves them into corresponding subfolders. If a file has no extension, it will be placed in a `no_extension` folder.

## 📄 License
This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

## 📌 Version
v1.0.0 – Initial release
