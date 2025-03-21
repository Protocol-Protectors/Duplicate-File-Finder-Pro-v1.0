**Duplicate File Finder Pro v1.0**

A powerful and user-friendly tool built with Python and Tkinter to detect and manage duplicate files on your system. Developed by the Aplha Titans Team, this application helps you reclaim disk space by identifying duplicate files based on their SHA-256 hashes and provides options to view, delete, or inspect file metadata.

**Features** : <br>
1. **Duplicate Detection:** Find duplicate files in a specified directory or across entire drives using SHA-256 hashing. <br>
2. **Drive Scanning:** Scan multiple drives with detailed information (size, type, free space) if psutil is installed. <br>
3. **Interactive GUI:** Built with Tkinter, featuring a clean and intuitive interface. <br>
4. **Progress Tracking:** Real-time progress bar and estimated time remaining during scans. <br>
5. **File Management:** View, delete, or show metadata for selected files. <br>
6. **Sorting & Filtering:** Sort results by creation date or size, and filter by originals or duplicates.<br>
7. **Metadata Viewer:** Display detailed file information including size, timestamps, owner, permissions, and hash. <br>
8. **Cross-Platform:** Works on Windows, Linux, and macOS (with minor platform-specific adjustments). <br>

**Screenshots** <br> 
![image](https://github.com/user-attachments/assets/efeca151-321f-4f59-a554-1073cdbbdb7f)
<br>
![Screenshot 2025-03-13 175603](https://github.com/user-attachments/assets/fe62e802-d6df-49d1-8f00-ee686318e342) <br> <br>
![Screenshot 2025-03-13 175645](https://github.com/user-attachments/assets/649226b1-fd70-445b-a906-dc63e601516d) <br> <br>
 ![Screenshot 2025-03-13 175725](https://github.com/user-attachments/assets/7e758dd1-4f1e-4502-8ee5-29a16be087f0) <br> <br>
![Screenshot 2025-03-13 180219](https://github.com/user-attachments/assets/ef3dcc1f-c278-4ea0-b627-56cdfe6ab22d) <br> <br>
![Screenshot 2025-03-13 180255](https://github.com/user-attachments/assets/d948eea6-bc33-484b-9174-2493f1c56f3a) <br> <br> 
 <br> <br>

**Installation** <br>  
**Prerequisites**
Python 3.8 or higher <br>
tkinter (usually included with Python; may require python3-tk on Linux) <br>
Optional: psutil for enhanced drive information <br><br>

**Steps**<br>
1. Clone the Repository:<br>
git clone https://github.com/Protocol-Protectors/Duplicate-File-Finder-Pro-v1.0.git  <br>
cd Duplicate-File-Finder-Pro-v1.0<br>

2. Install Dependencies: <br>
Create a virtual environment (optional but recommended) and install the required package: <br>
python -m venv venv <br> 
source venv/bin/activate  # On Windows: venv\Scripts\activate <br>
pip install -r requirements.txt <br>

3. **Contents of requirements.txt:**  <br>
    psutil>=5.9.0 <br>

4. **Run the Application:** <br>
   python3 main.py
   
<br>

**Usage**<br>
Launch the App: Run the script to open the GUI window.<br><br>
1. **Select a Directory:**<br>
Click "Browse" to choose a directory, or enter a path manually.<br>
Use "/" as the default root directory (adjust based on OS).<br>
2. **Find Duplicates:**<br>
Click "Find Duplicates" to scan the selected directory.
Alternatively, click "Scan Drives" to select and scan multiple drives.
3. **Manage Results:**<br>
View results in the table, sorted by creation date or size.<br>
4. **Select files and use:**<br>
**View Selected:** Open files in the default system viewer.<br>
**Delete Selected:** Remove duplicate files (originals are protected).<br>
**Show Metadata:** Inspect detailed file information.
5. **Monitor Progress**:<br>
Watch the progress bar and status updates during scans.<br>



