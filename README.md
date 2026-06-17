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

``` perl
./file_operations.pl [option] [filename]
```

#### Option:

To create the file and populated it by default:

``` text
-c, --cr
```

To transform the file content in upper case:

``` text
-u, --up
```

To truncate the file content:

``` text
-t, --tr
```

To remove definitively the file:

``` text
-d, --del
```

To read the file:

 ``` text
-r, --re
```

To copy the content of the first file into the second file:

 ``` text
-C, --cp
```

## Example

``` perl
./file_operations.pl --cr test.txt
./file_operations.pl -u test.txt
./file_operations.pl -r test.txt
./file_operations.pl --del test.txt
