# 📘 Linux File and Directory Management Commands

This README provides a detailed understanding of essential Linux commands used for listing files and managing directories, with explanations and examples.

---

## 📂 Listing Commands (`ls`)

The `ls` command is used to list files and directories in the current working directory.

### 🔹 Syntax:
```bash
ls [option_flag] [arguments]
```

![image](image/Screenshot%202025-07-19%20203529.png)

### 🧾 Examples:

* `ls -l`
  ➤ Lists files and directories in long format (shows permissions, owner, size, etc.)

![image](image/Screenshot%202025-07-19%20203901.png)

* `ls -a`
  ➤ Lists all files including hidden ones (those starting with `.`)

![image](image/Screenshot%202025-07-19%20210441.png)

* `ls *.sh`
  ➤ Lists all files ending with `.sh` (shell scripts)

![image](image/Screenshot%202025-07-19%20211552.png)

* `ls -i`
  ➤ Displays the index number (inode) for each file or directory

![image](image/Screenshot%202025-07-19%20210452.png)

* `ls -d */`
  ➤ Lists only the directories in the current location (trailing slash `/` indicates a directory)

![image](image/Screenshot%202025-07-19%20210504.png)

---

## 📁 Directory Commands

### `pwd`

➤ Prints the **Present Working Directory**.
Useful to know your current location in the filesystem.

![image](image/Screenshot%202025-07-19%20210627.png)

---

### `cd` (Change Directory)

Used to move between directories.

![image](image/Screenshot%202025-07-19%20210651.png)

#### Common Usages:

* `cd path_to_directory`
  ➤ Moves into the specified directory.

* `cd ~` or `cd`
  ➤ Navigates to the **home directory**.

![image](image/Screenshot%202025-07-19%20210729.png)

* `cd -`
  ➤ Switches to the **previous directory**.

![image](image/Screenshot%202025-07-19%20210745.png)

* `cd ..`
  ➤ Moves **one level back** (to the parent directory).

* `cd ../..`
  ➤ Moves **two levels back**.

![image](image/Screenshot%202025-07-19%20210807.png)

---

## 🏗 Creating Directories (`mkdir`)

The `mkdir` command is used to create new directories.

### 🧾 Examples:

* `mkdir newFolder`
  ➤ Creates a new directory named `newFolder` in the current path.

![image](image/Screenshot%202025-07-19%20210848.png)

* `mkdir .NewFolder`
  ➤ Creates a **hidden directory** (prefix `.` makes it hidden).

![image](image/Screenshot%202025-07-19%20210906.png)

* `mkdir A B C D`
  ➤ Creates **multiple directories** (`A`, `B`, `C`, `D`) in one command.

![image](image/Screenshot%202025-07-19%20210934.png)

* `mkdir /home/user/Mydirectory`
  ➤ Creates a directory at a **specific path**.

![image](image/Screenshot%202025-07-19%20211208.png)
![image](image/Screenshot%202025-07-19%20211220.png)

* `mkdir -p A/B/C/D`
  ➤ Creates a **nested directory structure**.
  ➤ If parent directories don’t exist, they will be created automatically.

![image](image/Screenshot%202025-07-19%20211235.png)

---


