# Bash Basic commands for Command Line

## Directory Options

* ```ls```: Lists all files in current directory
  * ```-a```: Includes hidden files
  * ```-l```: Lists additional information about each file
* ```cd```: Changes directory
  * ```cd ../..``` : Allows to return back up multiple layers 
  * ```cd /``` : Changes directory to root area
  * ```cd ~``` : Changes directory to home area
* ```pwd```: Returns absolute path for current directory 
* ```mkdir <dir_name>```: Creates new directory

## File Operations

* ```nano <file_name>```: Creates file which will open in nano for you to edit
* ```touch <file_name>```: Creates empty file
* ```cat <file1> (optional) <file2>```: Concatenates muliple files together and outputs to terminal (Can be used with single file to output to terminal.)
* ```cp <file1> <file2>```: Creates a copy of chosen file.
* ```mv <file_name> <new_path>```: Moves chosen file to new path provided.
* ```rm <file_name>```: Deletes file
  * ```-rf```: Flag used to delete folders

## Search files

* ```grep <pattern> *```: Search for a given pattern in either all files in directory or selected files.