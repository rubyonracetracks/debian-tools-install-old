# Install Development Tools for Debian-Based Linux
This [Ruby on Racetracks](http://www.rubyonracetracks.com/) repository contains scripts for automatically installing software tools in Debian Linux or its derivatives.  These tools include the Geany editor, the KeePassXC password manager, DB Browser for SQLite, Pgweb (PostgreSQL database browser), the SearchMonkey file search tool, and xdot (Graphviz graph viewer).

## Prerequisites
* Debian-based Linux environment
* If you're using a different Linux distro, a Mac, or a Windows machine, you can still use this repository as a cheat sheet on things to do when setting up your system.
* Git must be installed in your Debian Stretch-based installation.  If you have not installed Git, you can install it by entering the following command in the terminal:
```
sudo apt-get update; sudo apt-get -y install git
```

## Procedure
Enter the following commands in the terminal:
```
cd
mkdir -p rubyonracetracks
cd rubyonracetracks
git clone https://github.com/rubyonracetracks/debian-tools-install.git
cd debian-tools-install
bash main.sh
```
