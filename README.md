# How to set up both Linux and git to work in Windows Powershell

I haven't found one central place online with information on how to do this, so I'm adding it here for my own future use and for anyone else who needs help.

## Step 1: Install WSL
Follow the directions [here](https://learn.microsoft.com/en-us/windows/wsl/install).

If you don't want to read it, just type
```wsl --install```
in Windows Powershell and everything should work.

I didn't need to restart my computer after doing this, but you might (according to the website) so do what you gotta do.

Now you can use `pwd`, `ls`, `cd`, and all of your favorite other Linux navigation/use commands in Windows Powershell.

## Step 2: Install Git for Windows
A simple thing to do is to follow the instructions [here](https://learn.microsoft.com/en-us/devops/develop/git/install-and-set-up-git).

The download is found [here](https://git-scm.com/download/win), and setup is relatively simple. 

During the setup, one option you'll want to look out for is called *Configuring the terminal emulator to use with Git Bash*. Personally, I would rather use Windows' default console window over MinTTY, but it's up to your preference.

For everything else in the setup, I chose to leave them as the default options. If you want to be more careful, you can read through them, but I'm just telling you what I did.

I'll commit this README.md file using Windows Powershell just to triple check that things work.