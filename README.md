# 🐧 Linux Learning Notes

> A collection of beginner-friendly Linux notes and commands that I'm learning while building my Linux and DevOps fundamentals.

## 📖 About

This repository contains my personal Linux notes. It covers:

- Linux file system structure
- Basic terminal commands
- File and directory operations
- Nano text editor shortcuts
- Useful command examples

I will continue updating this repository as I learn more Linux concepts.

---

# 📂 Linux File System

| Directory | Description |
|-----------|-------------|
| `/home` | Contains home directories of users. Example: `/home/username` |
| `/etc` | Stores system-wide configuration files. |
| `/var` | Stores variable data such as logs, cache, mail, and spool files. |
| `/bin` | Contains essential command binaries like `ls`, `cp`, `mv`, and `cat`. |

---

# 💻 Basic Linux Commands

## 1. Print Working Directory

Shows the current directory.

```bash
pwd
```

Example Output

```text
/home/ubuntu/Documents
```

---

## 2. List Files and Directories

Lists files and folders in the current directory.

```bash
ls
```

---

## 3. Long Listing Format

Displays detailed information.

```bash
ls -l
```

Information includes:

- File permissions
- Owner
- Group
- File size
- Last modified date

---

## 4. Show Hidden Files

Displays all files, including hidden files.

```bash
ls -a
```

Hidden files begin with a `.`

Example:

```text
.bashrc
.profile
.gitignore
```

---

# 📁 File Operations

## Create a File

```bash
touch file.txt
```

---

## Create a Directory

```bash
mkdir my_folder
```

---

## Copy Files

```bash
cp source.txt destination.txt
```

---

## Move or Rename Files

Move a file:

```bash
mv file.txt Documents/
```

Rename a file:

```bash
mv oldname.txt newname.txt
```

---

## Delete a File

```bash
rm file.txt
```

---

## Delete an Empty Directory

```bash
rmdir my_folder
```

---

# 📄 Working with Files

## Open a File using Nano

```bash
nano notes.txt
```

---

## Display File Contents

```bash
cat notes.txt
```

---

## Display First 10 Lines

```bash
head notes.txt
```

---

## Display First 3 Lines

```bash
head -n 3 notes.txt
```

---

## Display Last 10 Lines

```bash
tail notes.txt
```

---

## Display Last 5 Lines

```bash
tail -n 5 notes.txt
```

---

# ✍️ Nano Editor Shortcuts

| Shortcut | Description |
|----------|-------------|
| `Ctrl + O` | Save file |
| `Enter` | Confirm file name |
| `Ctrl + X` | Exit Nano |
| `Ctrl + C` | Cancel current operation |
| `Ctrl + W` | Search text |
| `Ctrl + \` | Find and Replace |
| `Ctrl + K` | Cut current line |
| `Ctrl + U` | Paste line |
| `Ctrl + G` | Help Menu |

---

# 📌 Commands Covered

- pwd
- ls
- ls -l
- ls -a
- touch
- mkdir
- cp
- mv
- rm
- rmdir
- nano
- cat
- head
- tail

---

# 🚀 Learning Roadmap

- [x] Linux File System
- [x] Basic Terminal Commands
- [x] File Operations
- [x] Nano Editor
- [ ] File Permissions (`chmod`)
- [ ] Ownership (`chown`)
- [ ] Process Management
- [ ] Package Management
- [ ] Shell Scripting
- [ ] Networking Commands
- [ ] Cron Jobs
- [ ] Bash Scripting

---

# 🤝 Contributing

This repository is primarily for documenting my learning journey. Suggestions and corrections are always welcome.

---

## ⭐ If you found these notes useful, feel free to star the repository!
