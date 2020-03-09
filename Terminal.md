# :white_square_button: Terminal Cheat Sheet

#### :notebook: Content:
- [Open Terminal](#open-terminal)
- **Commands**
    - [cd - Change Directory](#pushpin-cd)
    - [ls - List](#pushpin-ls)
    - [pwd - Print Working Directory](#pushpin-pwd)
    - [File Manager Commands](#pushpin-file-manager-commands)
    - [mkdir - Make Directory](#pushpin-mkdir)
    - [cp - Copy](#pushpin-cp)
    - [rm - Remove](#pushpin-rm)
    - [mv - Move](#pushpin-mv)

**:warning: Take Care**:
- It is case sensitive, so make sure to use the exact command, directory, or file name.
- If the name of the directory/file contains spaces, put the whole name between quotes `''`.

## Open Terminal
### Ubuntu
To access the **Temrinal**, you can use **Ctrl**+**Alt**+**T**.

----

## :pushpin: cd
**change directory**

Changes directory and navigates through files in the system.

:computer: **Usage**

```shell
cd /[directory]/ 
```

**Examples**
```shell
cd Downloads
cd Programs/IntelliJ/bin
```

### ".." Symbol

You can use the `..` to go back one directory; or use it inside your path
```shell
// Goes back one directory
cd ..

// Use it in your path
cd ../Downloads 
``` 
### "~" Symbol
The tilde `~` symbol represents the **home** directory, so you can use it from anywhere.
 ```shell
cd ~

cd ~/Downloads/
 ```
----

## :pushpin: ls
**list**

Lists all the folders and files in the current directory.

:computer: **Usage**
```shell
ls
```
----

## :pushpin: pwd
**print working directory**

Prints the exact path you are currently in.

:computer: **Usage**
```shell
pwd 
```
----

## :pushpin: File Manager Commands
### Open a folder from Terminal

```shell
nautilus /directory/directory
```
or
```shell
xdg-open /directory/directory
```
----
## :pushpin: mkdir
**make directory**

Create a new subdirectory in the current directory

:computer: **Usage**
```shell
mkdir <directory> 
```
----
## :pushpin: cp
**copy**

- It copies a specific file to a destination directory. 
- To copy a whole directory, add `-r` to the command which stands for recursive  

:computer: **Usage**
```shell
cp <source file> <destination directory>
cp -r <source directory> <destination directory>
```
----
## :pushpin: rm
**remove**

- It deletes a file that you specify
- To delete a whole directory, add `-r` to the command which stands for recursive  

:computer: **Usage**
```shell
rm <file>
rm -r <directory>
```
----
## :pushpin: mv
**move**

- It allows you to **rename** a file, moving it from source to destination

:computer: **Usage**
```shell
mv <source> <destination>
```
----