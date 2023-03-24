# posix-cmds
Commonly used posix commands on *nix platforms

## Kill process running the port number 
```
kill -9 $(lsof -t -i tcp:80)
```
