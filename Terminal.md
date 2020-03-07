# :white_square_button: Terminal Cheat Sheet

#### :notebook: Content:
- [Open Terminal](#open-terminal)
- **Commands**
    - [cd - Change Directory](#pushpin-cd)
    - [ls - List Content](#pushpin-ls)
    - [pwd - Print Working Directory](#pushpin-pwd)
    - [File Manager Commands](#pushpin-file-manager-commands)

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

