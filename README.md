# Rename-Png-Files---Declutter-them
If you have a folder with .png files and wish to alter the .png file names to 1,2,3,4, etc, and organize it, here's your Python code for it. Remove the Hash when you run it of course.

import os
files=os.listdir("New Folder 1")
i=1
for file in files:
  if file.endswith (".png"):
   print(file)
 os.rename(f"New Folder 1/{file}",f"New Folder 1/{i}.png")
 i=i+1
