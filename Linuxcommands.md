# Linux Commands Cheat Sheet

**File and Directory Commands**

**pwd:** Prints the current working directory.

- **Syntax:** pwd

**ls:** Lists files and directories.

- **Syntax:** ls [options]

**mkdir:** Creates a new directory.

- **Syntax:** mkdir <directory_name>

**touch:** Creates a new, empty file.

- **Syntax:** touch <file_name>

**rm:** Deletes files or directories.

- **Syntax:** rm <file_name>

**rmdir:** Removes an empty directory.

- **Syntax:** rmdir <directory_name>

**cd:** Changes the current directory.

- **Syntax:** cd <directory_name>

**cp:** Copies files or directories.

- **Syntax:** cp <source> <destination>

**mv:** Moves or renames files or directories.

- **Syntax:** mv <source> <destination>

**cat:** Displays the content of a file.

- **Syntax:** cat <file_name>

**echo:** Displays text or writes to a file.

- **Syntax:** echo "text" > <file_name>

# File Editing

**vim:** Opens files in the Vim editor.

- **Syntax:** vim <file_name>

**nano:** Opens files in the Nano editor.

- **Syntax:** nano <file_name>

# User and Group Management

**useradd:** Adds a new user.

- **Syntax:** useradd <username>

**groupadd:** Creates a new group.

- **Syntax:** groupadd <group_name>

**chmod:** Changes file permissions.

- **Syntax:** chmod <permissions> <file_name>

**chown:** Changes file owner and group.

- **Syntax:** chown <owner>:<group> <file_name>

# Disk and Directory Information

**df:** Displays disk space usage.

- **Syntax:** df [options]

**du:** Shows disk usage of files/directories.

- **Syntax:** du [options] <directory>

**wc:** Counts lines, words, and characters in a file.

- **Syntax:** wc <file_name>

# System Information

**uname:** Shows system information.

- **Syntax:** uname [options]

**top:** Displays running processes.

- **Syntax:** top

**ps:** Shows currently running processes.

- **Syntax:** ps [options]

**uptime:** Shows how long the system has been running.

- **Syntax:** uptime

**whoami:** Displays the current logged-in user.

- **Syntax:** whoami

# System and Service Management

**systemctl:** Controls systemd services.

- **Syntax:** systemctl <command> <service_name>

**systemd:** A system and service manager for Linux.

- **Syntax:** systemd

**shutdown:** Shuts down the system.

- **Syntax:** shutdown [options] <time>

# Access Control

**getfacl:** Displays ACLs for a file or directory.

- **Syntax:** getfacl <file_name>

**setfacl:** Sets ACLs for a file or directory.

- **Syntax:** setfacl -m u:<user>:<permissions> <file_name>

# Miscellaneous

**man:** Displays the manual for a command.

- **Syntax:** man <command_name>

**history:** Shows command history.

- **Syntax:** history

**clear:** Clears the terminal screen.

- **Syntax:** clear

**dir:** Lists files and directories, similar to ls.

- **Syntax:** dir

