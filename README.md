# Sudo-win

This is a simple bat file which allows to elevate the standard command line to one with admin access rights just by typing sudo

## Installing

Just download the bat file and place it in C:\Windows

The end path should be

```
c:\Windows\sudo.bat
```

## How it works

The sudo command works by launching a powershell command which closes the current command window and opens a new elevated one preserving the active directory

## Tips

* The name of the command is just the name of the file, so for example by renaming sudo.bat to elevate.bat the command to type will be "elevate"
* removing the "exit" line will keep the original window open in background after opening the elevated one

## Todo

* Copy the text typed after the sudo command in the new window

## Notes

The [UAC](https://en.wikipedia.org/wiki/User_Account_Control) must be set to the lowest setting possible, otherwise windows will ask permission to run the new command window every time sudo is run