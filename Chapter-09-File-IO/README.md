# 📂 Chapter 09 - File I/O

<div align="center">

[![Files](https://img.shields.io/badge/Files-0-blue?style=for-the-badge)](#)

---

This chapter deals with persistence in Python by handling files—understanding file types, opening/reading/writing operations, file access modes, and clean resource management using the `with` statement.

</div>

## 📓 Core Topics Covered
* **Types of Files**: 
  * Text files (`.txt`, `.py`, etc. - readable strings)
  * Binary files (`.png`, `.dat`, etc. - raw bytes)
* **Opening a File**: Using the `open("filename", "mode")` function.
* **Reading a File**: 
  * `.read()` — Reads entire file content.
  * `.readline()` — Reads one line from the file.
  * `.readlines()` — Reads all lines as a list of strings.
* **Modes of Opening a File**:
  * `r` — Read mode (default).
  * `w` — Write mode (creates a new file or overwrites).
  * `a` — Append mode (adds content to the end of the file).
  * `+` — Update mode (read + write).
  * `rb`/`wb` — Binary read/write modes.
* **Writing Files**: Using the `.write("text")` method.
* **With Statement**: Recommended way to open files; automatically handles closing files even if exceptions occur.

---

## 📝 Practice Exercises (Planned)
* [ ] Read text from a file and find if it contains the word "twinkle"
* [ ] Check if a game score file exists and update the high score
* [ ] Generate multiplication tables from 2 to 20 and save in separate files
* [ ] Replace a specific word in a file with "#####" (censoring)
* [ ] Censor a list of words in a text file
* [ ] Search a log file for the word "python" and print its occurrences
* [ ] Find the line number where a search string is present in a log file
* [ ] Copy the contents of one file into another
* [ ] Check if two files are identical (content match)
* [ ] Wipe the contents of a file
* [ ] Rename a file using the `os` module
