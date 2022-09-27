# linux_key.logger

# How to Install?

The following instructions will install Keylogger using pip3 .

  pip3 install -r requirements.txt
  
or 

  pip3 install pyxhook


# How to run this key logger

By running `nohup python3 keylogger.py &` command, it'll start to log your strokes:
The meaning of nohup is ‘no hangup‘.
When nohup command use with ‘&’ then it doesn’t return to shell command prompt after running the command in the background. 
```
$~/Keylogger/linux$ nohup python3 keylogger.py &
[1] 12529 //this is the keylogger's PID (process ID)
$:~/Keylogger/linux$ fg

The Keylogger is now running! It will log your strokes to a file .
Stop it by typing the command `fg` then hitting `CTRL+C`

or

`kill {PID}` for example `kill 12529`

DISCLAIMER-
THIS TOOL IS ONLY FOR EDUCATIONAL PURPOSES. 
I DO NOT SUPPORT ANY KIND OF ILLEGAL ACTIVITY OR MALICIOUS HACKING. 
MY AIM IS ONLY TO TEACH YOU IN A LEGAL WAY.
