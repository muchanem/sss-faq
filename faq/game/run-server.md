<br>
<br>
## How To Run Your Server
<br>
#### FAQ >> Game >> How To Run Your Server
------------------------------------------

This is quite a simple task. All you need to do is type `www` from the
directory that contains your `index.html` or `index.jade`. Once you do
this, you can access your game in your web browser at `skilstak.sh:port`, replacing port
with your `UID` with 7000 added to it (8 instead of 1). To view your
`UID`, type this. `echo $UID`
When you type `www`, you open a `dtach` session. To stop this, use
`CTRL + C` and to exit, use `CTRL + \`. To reconnect, type `dtach -A
www www`. **NOTE1:** This will open a new session if there is none.
**NOTE2:** If you use serve, do `serve www port` from the directory
with `www` in it.
