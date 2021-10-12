# Introduction to using the command line

## [Commands](https://ss64.com/bash/)

* **`whoami`**: who am I
    * It displays the username of the *current user* when this command is invoked 
    * similar as running the `id` command with the options `-un`
* [**`pwd`**](https://linuxize.com/post/current-working-directory/): print working directory
    * To find out what directory you are currently in
* [**`ls`**](https://linuxize.com/post/how-to-list-files-in-linux-using-the-ls-command/): lists the files in the current working directory
   * `-a` all; all folders and files appears.
   * `-l` long listing format
   * `--help` 
* **`cd Desktop`**: Goes to the Desktop directory if you are in your home directory
* **`mkdir`**: make directory; Creates a new subdirectory. 
* **`rm -r`**: Remove directory
* **`exit`**: to close command line

# [Linux commands for beginners](http://www.letix.hu/#allomany)

# [Relative and absolute path](https://tarhelywiki.hu/?p=853)

# [Elérési útvonal, részletek, példák](https://informatika.gtportal.eu/?f0=os_fajl_108)

# [Directory](https://informatika.gtportal.eu/?f0=os_fajl_106)

# [Parancssor: Fájl müveletek](https://www.youtube.com/watch?v=P9FBpd-2pnI)

`cat file.txt`

`touch file2.txt`

`mv file2.txt files move the file2.txt file to the files folder

`mv file.txt alma.txt` rename 

`cp files/file2.txt .` copy file

`rm file2.txt` remove file; `rm *.txt`

`rmdir files` delete the files folder but only if empty

`rm files -r` delete all files and the `files` folder

# [Parancssor: Átirányítás](https://www.youtube.com/watch?v=k3TKJHu9Mbc)

`echo text` print `text` to the console 

`echo korte > korte.txt` create the `korte.txt` file with the `korte` content

`cat korte.txt > barack.txt` create the `barack.txt` file and copy into the content of the `korte.txt` file

`ls -al > list.txt`

`echo override > list.txt` override the previous content

`echo "add new row" >> list.txt` add a new row to the `list.txt`

`grep override list.txt` print to the console the rows from the `list.txt` if contains the `override` text

`head blue.txt` print out the first 10 rows from the `blue.txt`

`head ble.txt -n 3` the first 3 rows print out

## The `|` (pipe) operator

Redirect the output from the first command to the second one.

`ls -la | grep txt` only the txt files print out

`ls -la | grep a` only the rows contain `a` will print out

`cat blue.txt | grep 5 | head -n 1` only the first row contain `5` will print out

`cat alma.txt | uniq` only unique rows will print out

`cat alam.txt | sort | uniq | head -n 1` print out the first row from alphabetical row





