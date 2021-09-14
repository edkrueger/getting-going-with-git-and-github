# getting-going-with-git-and-github

## Install For Windows

### Install Git and GitBash
Go to https://gitforwindows.org/  
Download the installer  
On the last page select "Enable experimental support for pseudo consoles"  
Otherwise accept the Defaults for the installer  

### Install GitHub CLI
Go to https://cli.github.com/  
Download the installer  
Accept the Defaults for the installer  

## Install for Mac

Dowload Homebrew Package Manager with: `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`  
To install Git run `brew install git`  
To install the GitHub CLI run `brew install gh`  


## Setup for Both
If you are using a Mac, terminal will refer to the built in terminal  
If you are using a PC, terminal will refer to GitBash  
In your terminal, run `gh auth login`  
Select "GitHub.com"  
Select "HTTPS"  
Select "Y"  
Select "Login with a web browser"  
Copy the one-time code. In GitBash, simply highlighting will copy  
Press Enter  
Your browser will open  
Paste the code or enter it manually  
Press the "Authorize github" button  
Go back to your terminal and press Enter  
