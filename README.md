# DuckyScripts

The reverse shell comes from https://github.com/antonioCoco/ConPtyShell
This script will turn off defender on a windows 11 device, and attempt to connect to the ip and port you specify

Make sure you change the ip and port values before compiling using https://payloadstudio.com/community/

Run the below command server side to catch shell
stty raw -echo; (stty size; cat) | nc -lvnp <port>

Delays should be tweaked and configured based on your own experience
