# Command Line File Operations

### Basic Commands:

1. **Navigating Directories:**
   - `cd`: Change directory.
     - Example: `cd Documents`

2. **Listing Files and Directories:**
   - `ls`: List files and directories.
     - Example: `ls -l` (detailed list)

3. **Listing Hidden Files and Directories:**
   - `ls -a`: List hidden files and directories.
     - Example: `ls -la` (detailed list with hidden files)

3. **Creating Files and Directories:**
   - `touch`: Create an empty file.
     - Example: `touch new_file.txt`
   - `mkdir`: Create a new directory.
     - Example: `mkdir new_directory`

4. **Copying and Moving Files:**
   - `cp`: Copy files or directories.
     - Example: `cp file.txt destination/`
   - `mv`: Move or rename files or directories.
     - Example: `mv file.txt new_location/`

5. **Removing Files and Directories:**
   - `rm`: Remove files.
     - Example: `rm unwanted_file.txt`
   - `rmdir`: Remove empty directories.
     - Example: `rmdir empty_directory/`
   - `rm -r`: Remove directories and their contents recursively.
     - Example: `rm -r directory_to_remove/`

### Advanced Commands:

1. **Wildcards:**
   - Use `*` to represent any characters.
     - Example: `ls *.txt` (lists all text files)

2. **Piping and Redirection:**
   - `|`: Pipe command output to another command.
     - Example: `ls -l | grep keyword`
   - `>` and `>>`: Redirect output to a file (overwrite/append).
     - Example: `ls > file_list.txt`

3. **Searching for Files:**
   - `find`: Search for files and directories.
     - Example: `find /path/to/search -name "*.txt"`

4. **Archiving and Compression:**
   - `tar`: Create or extract tar archives.
     - Example: `tar -cvf archive.tar directory/`
   - `gzip` and `gunzip`: Compress or decompress files.
     - Example: `gzip file.txt`

5. **Permissions:**
   - `chmod`: Change file permissions.
     - Example: `chmod +x script.sh` (add execute permission)

### Cool Things:

1. **Command History:**
   - Use the arrow keys to navigate through previous commands.

2. **Tab Completion:**
   - Press Tab to autocomplete file and directory names.

3. **Aliases:**
   - Create shortcuts for longer commands.
     - Example: `alias ll='ls -l'`

4. **Scripting:**
   - Write shell scripts to automate tasks.

5. **Remote Operations:**
   - SSH into remote servers and perform file operations.

6. **Text Processing:**
   - Use tools like `grep`, `vi`, `sed`, and `awk` for powerful text processing.

7. **File name search**
   - Use `find /path/to/search -name "filename.txt"` to search for a file named "filename.txt"

8. **MacOS specific file search**
   - In macOS, you can use the mdfind command for file searches. It utilizes the Spotlight index for faster and more efficient searches. `mdfind -name "filename.txt"`
