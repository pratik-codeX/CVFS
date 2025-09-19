# CVFS
Marvellous CVFS is an in-memory virtual file system in C/C++. It supports creating, reading, writing, listing, and deleting files with permissions, file descriptors, and error handling. Includes a shell-like interface with commands, inodes, file tables, and man pages for educational OS-level file management.

````markdown
# Marvellous CVFS

**Marvellous CVFS** is a simple in-memory virtual file system implemented in C/C++. It simulates basic file system operations and provides a shell-like interface to manage files with permissions, file descriptors, and error handling.  

---

## Features

- **In-Memory File Storage:** Files are stored in memory using dynamic buffers.  
- **File Operations:** Create, read, write, delete, list, and display file statistics (`creat`, `read`, `write`, `unlink`, `ls`, `stat`).  
- **Shell Interface:** Custom CLI supporting commands like `help`, `man`, `clear`, and `exit`.  
- **Permissions & Error Handling:** Read/write permissions, invalid parameters, insufficient space, and other common file system errors.  
- **File Management:** Uses inodes and file tables to track file metadata and open file descriptors.  
- **Educational Purpose:** Demonstrates OS-level file management concepts and data structures.

---

## Commands

| Command   | Description |
|-----------|-------------|
| `creat`   | Create a new file with specified permissions |
| `read`    | Read data from a file using file descriptor |
| `write`   | Write data to a file using file descriptor |
| `unlink`  | Delete a file |
| `ls`      | List all files in the directory |
| `stat`    | Display statistical information about a file |
| `help`    | Display command manual |
| `man`     | Show manual page for a specific command |
| `clear`   | Clear the console |
| `exit`    | Terminate the CVFS shell |

---

## File Permissions

- `1` : Read  
- `2` : Write  
- `3` : Read + Write  

---

## How to Run

1. Clone the repository:

```bash
git clone <repo-url>
````

2. Compile the code:

```bash
g++ MarvellousCVFS.cpp -o cvfs
```

3. Run the executable:

```bash
./cvfs
```

4. Use the commands in the custom shell as described above.

---

## Author

**Piyush Manohar Khairnar**

---

## License

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.


