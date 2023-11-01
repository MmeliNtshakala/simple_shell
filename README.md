<div align="center">
  <h1>Simple Shell <img src="https://cdn-icons-png.flaticon.com/128/6821/6821173.png" width=60 align=center> </h1>
  <h6>
    <a href="">Man Page</a>
    ·
    <a href="">Compilation</a>
    ·
    <a href="">Commands</a>
    ·
    <a href="">Usage</a>
  </h6>
  <img src="">
</div>

## Description <img src="https://cdn-icons-png.flaticon.com/128/1903/1903496.png" width=45 align=center>

Simple Shell is a command line interpreter developed in C language that emulates the most basic functionality of `sh`.

## Man page <img src="https://cdn-icons-png.flaticon.com/128/781/781103.png" width=50 align=center>

The man page is a file wich explains in detail how Simple Shell works. If you want see a full explanation of this function you can run our man page this way:
```
$ man ./man_1_simple_shell
```

<img src="https://i.imgur.com/f6YWz5o.jpg" alt="flowchart">

## Compilation <img src="https://cdn-icons-png.flaticon.com/128/8084/8084300.png" width=50 align=center>

To compile the program this command has to be executed:
```
$ gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c -o hsh
```
To run the shell is like this:
```
$ ./hsh
```

## List of built-in commands <img src="https://cdn-icons-png.flaticon.com/128/868/868684.png" width=45 align=center>

This list is of the built-in commands, apart from those found in the PATH.

| Command  | Description |
| -------- |:------------|
| env      | Displays the current environment |
| exit     | Causes the shell to terminate |

## Usage <img src="https://cdn-icons-png.flaticon.com/512/3123/3123008.png" width=50 align=center>

The shell can be used in interactive or non-interactive mode.
The interactive mode is how the shell is normally used, the executable file is run and we can write commands, here is an example:
```
$ ./hsh
hsh$ ls
file1 file2 directory/
hsh$ pwd
/home/user/simple_shell/
hsh$ echo hello_world
hello_world
hsh$ exit
$
```

In the non-interactive mode you pass the command to the executable file with a pipe operator, as shown in the following example:
```
$ echo "/bin/ls" | ./hsh
hsh main.c shell.c test_ls_2

$ cat test_ls_2 | ./hsh
hsh main.c shell.c test_ls_2
hsh main.c shell.c test_ls_2
```

## Authors <img src="https://cdn-icons-png.flaticon.com/128/2463/2463510.png" width=50 align=center>

* Mmeli Ntshakala <a href="" rel="nofollow"><img align="center" alt="github" src="https://www.vectorlogo.zone/logos/github/github-tile.svg" height="24" /></a>
* Nicholas Upaka <a href="https://github.com/Klausgrey" rel="nofollow"><img align="center" alt="github" src="https://www.vectorlogo.zone/logos/github/github-tile.svg" height="24" /></a>
<br>

> Project developed during out ALX program.
