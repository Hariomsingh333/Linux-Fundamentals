# Date: 13 / 9 / 2021
# Linux Fundamentals

# What is Linux?
- Kernel - Hardware
- OS tools - Tools to interact with hardware
- Distrubutions - 3rd party applications

## Kernel
The kernel is basically a pice of software which is responsible for interacting the underline hardware.

- Core of any linux distrubution 
- Shared by all linux distrubution
- Bridge for hardware-software
- Manages hardware
## Your first Command 
- echo
echo command just like print in programing language, so if you want to print something in linux terminal just echo "hello world"

```bash
echo "hello world"
```
## What is terminal
Terminal basically mean like a window which run a program, which is called a shell, bash is our shell, so in linux we have bash shell and in macOC we have zsh shell

# Common Linux Command 
## pwd - Print working directory
pwd mean hey just echo (print) where i am or which directory i am currently

```bash
pwd
```
## cd - change directory
cd allows as to Change the directory. now cd allows you specify as an absulot path or a relative path.

## ls - list 
ls mean list, when you type ls and hit enter then you see you all file

```bash
ls
```
```bash
ls -l

ls -a // list all 

ls -la 
```
## cat - Reading file
```bash
cat filename
```
```bash
cat text.txt
```
if you want to read a file or want to knwo what inside the file so how you can read the file, so in linux we have cat command that helps us to know what inside the file, so in linux we have cat command that helps us to know what inside the file. 

## how to know which linux distrubution this system
you want to which linux distrubution using this system here you command, just go to root and cat os-release

```bash
cd /etc
```
```bash
cat os-release
```
or 

```bash
cat /etc/os-release
```
## less - Read long files
if you want to read a long file in terminal, then you should not you the cat command, you should use the less command 
```bash
less filename
```
```bash
less bigText.txt
```
## mkdir - create directory
if you want to make a file (directory) in GUI then you go to the file and hit right click and create new folder, but in linux you can use the mkdir command to make a folder
```bash
mkdir foldername
```
```bash
mkdir new-file
```
if you want to create nested folder the use the -p flag
```bash
mkdir -p folder1/folder2/folder3
```

