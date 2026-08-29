# Linux Basics for Hackers 🐧

Linux is the main OS in security labs. Learn these first.

## Core Commands

```bash
pwd  # Prints your current folder path.
ls -la  # Lists files, including hidden ones, with details.
cd /tmp  # Moves you into /tmp directory.
mkdir lab  # Creates a new folder named lab.
touch notes.txt  # Creates an empty file.
cp notes.txt notes.bak  # Copies file to a backup file.
mv notes.bak archive.txt  # Renames or moves a file.
rm archive.txt  # Deletes a file.
cat /etc/os-release  # Shows Linux version information.
chmod +x script.sh  # Gives execute permission to script.sh.
```

## ASCII Idea

```text
/ (root)
├── home
├── etc
├── var
└── tmp
```

## Quick Win 🎯
Create a folder and file:
```bash
mkdir ~/my-lab && touch ~/my-lab/first-note.txt  # Makes your first lab folder and file in one command.
```

## Memory Hack 🧠
**C.P.M.R** = **C**reate (`mkdir`), **P**rint (`pwd`), **M**ove (`cd/mv`), **R**emove (`rm`).
