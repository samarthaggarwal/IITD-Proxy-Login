# IITD-Proxy-Login
Automatically login the IITD proxy via the shell and stay logged in

This is an alternative to login via lynx.

### Instructions

1. Clone this repo on your system.
2. Run this command in terminal. Note that the proxy url needs to be changed according to your category.
```
python login_terminal.py <username> --passwd <password> <category>
export http_proxy=proxy22.iitd.ac.in:3128
export https_proxy=proxy22.iitd.ac.in:3128
```
3. When you wish to logout, run
```
python logout.py
```

###### Tip : Add these commands to .bashrc file so that you dont have to enter them each time.
