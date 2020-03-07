# Terminal

List of content:
- [Open Terminal](#Ubuntu)
- **Commands**
    - [cd - Change Directory](#cd)


### Ubuntu
To access the **Temrinal**, you can use **Ctrl**+**Alt**+**T**.

## cd
**change directory**

Changes directory and navigates through files in the system.

**Usage**
```shell script
cd /[directory]/ 
```

**Examples**
```shell script
cd Downloads
cd Programs/IntelliJ/bin
```

### ".." Symbol

You can use the `..` to go back one directory; or use it inside your path
```shell script
// Goes back one directory
cd ..

// Use it in your path
cd ../Downloads 
```
### "~" Symbol
The tilde `~` symbol represents the **home** directory, so you can use it from anywhere.
 ```shell script
cd ~

cd ~/Downloads/
 ```
----
**Notes**:
- It is case sensitive, so make sure to use the exact directory name.


## ls
**list**

Lists all the folders and files in the current directory.

**Usage**
```shell script
ls
```

## pwd
**print working directory**

Prints the exact path you are currently in.

**Usage**
```shell script
pwd 
```


