# linux-bootcamp



# **Our Linux Learning Journey**

## **Introduction**

Welcome to our documentation of the journey through our Linux bootcamp! Here, we’ll be sharing our adventures and discoveries as we dive into the world of Linux.

## **Goals**

### **Understanding Linux Basics**

- **What we want to learn:** We want to understand how Linux works and how to do basic things like managing files and users.
- **What we did:** We started by learning simple commands to do things like navigating folders and creating files. Then, we learned about permissions, which control who can do what with files.

## **Journey Highlights**

### **Week 1: Introduction to Linux**

- We installed Linux on our computers and learned how to move around and do basic stuff.

**Install using Command Prompt**

**Step 1**: Start **CMD** with administrative privileges.

**Step 2**:Execute **"wsl --install"** command.

**Step 3**:Run **"wsl -l -o"** to list other Linux releases.

**Step 4**:You can install your favorite Linux distribution, use **"wsl --install -d NameofLinuxDistro."**

```
When the operation is finished, restart your PC.You can start the Linux distribution from your Start menu.
```

**Install Using Windows Features**

**Step 1**:Open the Start menu and type **"Windows features"** into the search bar and click on "**Turn Windows Features On or Off"**.

**Step 2**:Tick the "**Windows Subsystem for Linux"** checkbox and press the “OK” button.

**Step 3**:When the operation is complete, you will be asked to **restart your computer.**

**Step 4**:The Linux distribution can be launched from the **Start menu.**

# **The Linux `ls` command**

Inside a folder you can list all the files that the folder contains using the `ls` command:

```bash
ls

```

If you add a folder name or path, it will print that folder's contents:

```bash
ls /bin
```
![Screenshot (622)](https://github.com/jaywiz16/linux-bootcamp/assets/113538419/f41b8dda-bfbd-45df-a4cb-e181c01a908f)


