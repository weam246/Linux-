# 📁 Linux File Permissions Task

## 📋 Description

This task demonstrates how to work with file permissions in Linux using the `chmod` command.
The goal is to apply the permission pattern `rwxrwxr-x` (equivalent to `775`) to a file using a Bash script.

---

## 🔧 What the Script Does

1. Creates a new file called `test_file.txt`
2. Displays the file permissions **before** applying `chmod`
3. Applies the `775` permissions using:

   ```bash
   chmod 775 test_file.txt
   ```
