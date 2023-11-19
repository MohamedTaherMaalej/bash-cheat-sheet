# File and Directory Operations Cheat Sheet

## Table of Contents

- [Navigation](#navigation)
- [File Operations](#file-operations)
- [Directory Operations](#directory-operations)
- [File Permissions](#file-permissions)
- [Search and Find](#search-and-find)

## Navigation

### Change Directory
```bash
cd /path/to/directory
```

### Navigate to Home Directory
```bash
cd ~
```

### Navigate to Parent Directory
```bash
cd ..
```

### List Contents of Directory
```bash
ls
```

### List Contents with Details
```bash
ls -l
```

### List All Files (Including Hidden)
```bash
ls -a
```

## File Operations

### Create Empty File
```bash
touch filename
```

### Copy File
```bash
cp source_file destination
```

### Move/Rename File
```bash
mv old_filename new_filename
```

### Remove/Delete File
```bash
rm filename
```

## Directory Operations

### Create Directory
```bash
mkdir directory_name
```

### Copy Directory (Recursively)
```bash
cp -r source_directory destination
```

### Move/Rename Directory
```bash
mv old_directory new_directory
```

### Remove/Delete Directory (Empty)
```bash
rmdir directory_name
```

### Remove/Delete Directory (Recursive)
```bash
rm -r directory_name
```

## File Permissions

### Change File Permissions
```bash
chmod permissions filename
```
Example:
```bash
chmod +x script.sh
```

### Change Directory Permissions
```bash
chmod permissions directory_name
```

## Search and Find

### Find File by Name
```bash
find /path/to/search -name filename
```

### Find Files by Extension
```bash
find /path/to/search -type f -name "*.txt"
```

### Search for Text in Files
```bash
grep "search_term" file.txt
```

### Count Lines in a File
```bash
wc -l file.txt
```

