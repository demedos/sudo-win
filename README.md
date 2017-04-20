# Sudo-win

This is a simple bat file which allows to elevate the standard command line to one with admin access rights just by typing sudo

## Installing

Just download the bat file and place it in C:\Windows

The end path should be

```
c:\Windows\sudo.bat
```

## How it works

The sudo command works by launching a powershell command which closes the current cmd window and opens a new elevated one preserving the active directory in use

## Tip

The name of the command is just the name of the file, so by renaming sudo.bat to elevate.bat the cmd to type will be "elevate"

## Todo

* Copy the text typed after the sudo command in the new window
