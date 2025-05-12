# Required software during bioinformatics trainings
In Windows operating system computers, we need to set up software that we can use to access
the remote server (HPC) and easily tranfer data from the remote server to our local computers. Additionally, we can 
install certain software that give us a Unix shell where we can run commands just like on the remote server.

Below is a list of the software that you need installed:

## Windows Subsytem for Linux (WSL)
The WSL will enable you install a Linux distribution and use Bash commandline tools without having to set up a virtual machine or dualboot.
You will require to have your computer running the following:
- Windows 10 version 2004 and higher (Build 19041 and higher), or
- Windows 11

To check your version and build number, select Windows logo key + R, type `winver`, select OK.

To install WSL, open PowerShell or Windows Command Prompt in administrator mode by right-clicking and selecting "Run as administrator".

First, check whether WSL is already installed by running the following command:

```
wsl --help
```
If help on how to use WSL is printed out, then WSL is already installed.

If get an error message, WSL is not installed and you need to type the following command and press Enter.
```
wsl --install
```

Restart your computer.

Once you have installed WSL, we need to install a Linux distribution. Let's install `Ubuntu-24.04` as follows:

```
wsl --install -d Ubuntu-24.04
```
Once you have installed WSL, you will need to create a user account and password for your newly installed Linux distribution.


## MobaXterm

## WinSCP

## Notepad++


