<h1>Python Automation: Dynamic File Sorting</h1>

<h2>Project Description</h2>
I built an automated file-sorting script in Python that organizes files into dedicated folders based on their file type. I began by importing OS and shutil to interact with the operating system, then defined a dynamic file path and used os.listdir() to retrieve all files within the directory. I created logic to check whether target folders (CSV, XLSX, and SQL files) already existed, automatically generating them when missing. I then developed a loop that inspected each file's extension and used shutil.move() to place it into the correct folder, ensuring the script prevented duplicates and handled path formatting issues. After testing and debugging the logic (including path corrections, loop behavior, and file-type detection) I verified that the script correctly sorted all files and could be rerun safely. This project demonstrates my ability to automate file-management tasks, work with directories and file paths, use conditional logic and loops, and build practical Python scripts with real world applications.

<h2> Python script </h2>

- <b>[Automatic_file_Sorter_project](https://github.com/Ivan-dlpm/Python-Automation-Dynamic-File-Sorting/blob/main/Automatic_file_Sorter_project.ipynb)</b>

<h2> Demonstration </h2>

<p align="center">
  
BEFORE  <br/>
<img src="https://imgur.com/Vu4KBLR.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<br />
<br />

<p align="left">
AFTER  <br/> 
<img src="https://imgur.com/wcaSPED.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<br />
<br />
