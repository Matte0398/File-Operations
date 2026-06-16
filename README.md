# File-Operations

Perl script that performs basic file management operations on a text file.

## Features

- Create a file and populated it by default
- Convert file content to uppercase
- Truncate file content
- Delete a file
- Read file content
- Copy content from one file to another

## Usage

```bash
./file_operations.pl [option] [filename]

  option:
    - '-c', '--cr' -> to create the file and populated it by default
    - '-u', '--up' -> to transform the file content in upper case
    - '-t', '--tr' -> to truncate the file content
    - '-d', '--del' -> to remove definitively the file
    - '-r', '--re' -> to read the file
    - '-C', '--cp' -> to copy the content of the first file into the second file
```

## Example

```
./file_operations.pl --cr test.txt
./file_operations.pl -u test.txt
./file_operations.pl -r test.txt
./file_operations.pl --del test.txt
