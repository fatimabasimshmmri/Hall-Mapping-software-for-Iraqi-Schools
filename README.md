# Hall-Mapping-software-for-Iraqi-Schools
Turns student lists (Years 7–12) into ready‑to‑print seating plans. You just add hall numbers with right‑side doors into the Python file (follow the comment), type school name once in base.docx (top right), paste student names into the .txt files. The repo creates a master hall file + individual hall .docx copies automatically.
___NOTES BEFORE USE:___
**Add your school name:
Make sure you have Microsoft word installed. 
Find base.docx, and find the top right segment of the header.
Add your school name right under.

**Edit the text files:
Open each .txt file in Notepad
Write student names separated by commas, e.g.:
Ahmed Ali, Sara Khan, Omar Noor, Laila Hassan
No extra spaces or blank lines needed

**Open mapper.py with Notepad:
Find the line that says:
RIGHT_DOOR_HALLS = [1, 4, 5, 7, 8, 11, 12]
Change the numbers to match the halls in your school where the door is on the right side. Then, save and close the file.

___RUNNING THE MAPPER___
Open the file with any terminal pip support and make sure your Python is installed and up to date.
Type in the terminal:
python mapper.py
You may need to use different terminal approaches for it to work, such as:
py mapper.py
python3 mapper.py
C:\Python39**where python is installed**\python.exe mapper.py
etc...
