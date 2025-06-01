MediaTidy

MediaTidy is a lightweight, user-friendly tool to organize your media files (photos and videos) by sorting them into folders by their creation date. It supports many image and video formats and safely handles duplicate files with user choices to rename or skip.
Features

    Automatically scan and organize media files (photos & videos) by year-month folders (e.g., 2024-05)

    Supports a wide range of image formats including JPG, PNG, RAW variants, HEIC, WebP, TIFF, and more

    Supports popular video formats like MP4, MOV, AVI, MKV, and others

    Reads photo EXIF data for accurate date taken, or falls back to file modification date

    Duplicate file handling: prompts user to rename or skip duplicates with option to apply choice to all

    Undo last operation feature (undo moves from last sort)

    Progress bar and status updates during sorting

    Embedded support button linking to Buy Me a Coffee page

    Creates a hidden log file to prevent re-sorting already sorted files



Important Warning

Always run MediaTidy from a folder outside your main media folder(s). 
Do not run it inside your media folders directly to avoid accidental moves or loss of files. Instead:

    Choose or create a separate folder on your drive

    Run MediaTidy and select the target media folder from the dialog

    The program will organize files inside the selected folder safely




How to Use
Using the Executable (.exe)

    Download the latest MediaTidy.exe.

    Run the executable fron dist folder.

    Click Select Folder and choose the folder containing your media files.

    MediaTidy will scan and organize your files by date.

    If duplicates are found, choose whether to rename or skip them.

    Use the Undo Last Operation button if you want to revert the last sorting action.

    Support the developer via the Buy Me a Coffee button if you find the tool helpful!

Using the Python Script (.py)

    Make sure you have Python 3 installed.

    Install dependencies by running:

pip install exifread

Save MediaTidy.py to your computer.

Run the script with:

    python MediaTidy.py

    Follow the same steps as the executable to select your folder and organize files.

    Duplicate handling and undo work identically.

    Support the developer by clicking the support button.

If you encounter any issues or have suggestions, feel free to reach out or contribute!

Thank you for using MediaTidy!
– Developer Team