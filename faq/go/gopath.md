<br>
<br>

# `$GOPATH` is broken
-------------------
One of the largest source of errors in GOlang is the stupid gopath. Unless you're working in your natural gopath and not in a repo, you're bound to have a lot of problems.

###Source your gopath:
The most common mistake is forgetting to source your gopath "setup" file (`source setup`). If you don't have one, here's the rundown:

- Make a file "setup" in the file containing "src", "pkg", and "bin"
- Exit it
- Get your current path with `pwd`, then copy everything that is past your username.

**EXAMPLE**:
Lets assume for this example, that your current directory is `home/whitman-colm/repos/project/go`. Then your setup file should look like:
```shell
export GOPATH=$HOME/*repos/project/go*
export PATH=$HOME/*repos/project/go*/bin:$PATH
```
Even if that is not your current working directory, **only change what is italicized!!!**
- `source setup` and you're good to go!

----------

*If you still have problems, feel free to sss the TAs or ask around on the golang forums*
