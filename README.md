# Linux Basics Guide

Welcome to the Linux Basics Guide repository! This guide is designed to help you understand and use essential Linux commands. Each command is explained in simple language with examples to make learning easy.

# Table of Contents

1. [sudo](#sudo)
2. apt
3. mkdir
4. cd
5. ls
6. nano
7. wget
8. curl
9. bash

## sudo
### Full Form: **Super User Do**

The sudo command allows you to run programs with the security privileges of another user, typically the superuser (root). This is useful when you need to perform administrative tasks that require higher permissions.

### Usage:
```bash
sudo [command]
```

### Examples:
```bash
sudo apt update
```
This command updates the list of available packages and their versions, but it does not install or upgrade any packages.

```bash
sudo reboot
```
This command restarts the computer immediately.

## apt
### Full Form: Advanced Package Tool

The apt command is used to manage software packages on Ubuntu/Debain systems. You can install, update, upgrade, and remove software packages using apt.

### Usage:
```bash
apt [options] [command]
```

### Examples:
```bash
sudo apt install nano
```
This command installs the nano text editor on your system.

```bash
sudo apt removes nano
```
This command removes the nano text editor from your system.

## mkdir
### Full Form: Make Directory

The mkdir command is used to create new directories (folders) in the file system.

### Usage:
```bash
mkdir [directory_name]
```

### Examples:
```bash
mkdir my_new_directory
```
This command creates a directory named my_new_directory.

```bash
mkdir -p parent/child
```
This command creates a nested directory structure with parent as the parent directory and child as a subdirectory inside parent.

## cd
### Full Form: Change Directory

The cd command is used to change the current working directory in the terminal.

### Usage:
```bash
cd [directory_name]
```

### Examples:
```bash
test
```
