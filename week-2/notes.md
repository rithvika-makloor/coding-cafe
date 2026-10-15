pwd printed the full path of the directory I was currently in.
ls -a showed hidden files and folders that start with a dot (.) which plain ls did not show.
The first column in ls -l shows the file type and permissions. It showes who can access the file, or read or write in it.
It works because coding-cafe/week02 is written relative to the directory I am currently standing in. It is a relative path.
mv first moved README-backup.md into the week01 folder. Then it renamed the file from README-backup.md to old-readme.md.
The number of folders depends on my own PATH. I can count the sections separated by : in the output of echo $PATH.
python3 lives at the exact location printed when I run which python3.
My Python path may be different from the person next to me because Python can be installed in different locations.
The shell said pyton3: command not found. The shell searched all folders in my path but couldn't find python3.
venv did not appear with plain ls because it starts with a dot, making it a hidden folder. ls -a shows hidden files and folders.
(.venv) appeared at the beginning of my terminal prompt. This showed that the virtual environment had been activated.
The path changed after activating .venv. This means activate changed my PATH so that the Python inside .venv is found before the system Python.
requests appeared in the second pip list. 
After running deactivate, python3 pointed back to my original system Python location.
ls -h displays file sizes in a human-readable format, such as KB, MB, or GB.
Ctrl + C interrupts and stops the currently running program. Ctrl + D sends an end-of-file signal