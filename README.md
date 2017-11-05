# file_manager
A node js utility for common day to day work related to bulk file creation, deletion etc. in asynchronous way.

## Valid Commands

1. CREATE
ex - `node fileManager create <file_name> <format>`
**NOTE:**

* <file_name> is the file that has a list of file names in line separated value format.

* <format> is the format of file. For ex: `js`, `txt`, `html` etc. If no value is passed then plain file will be created.


2. DELETE
ex - `node fileManager delete <file_name>`
**NOTE:**

* <file_name> is the file that has a list of file names in line separated value format. File names present in this file must be having the exact name with extension.
