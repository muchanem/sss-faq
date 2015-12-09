<br>
<br>

### `$GOPATH` help!
-------------------
If you've had issues with your go program not finding your modules, it
probably has to do with your `$GOPATH`. This is an example of a 
`setup` file to keep in your Go repo.

```shell
# remember source me, don't run me

export GOPATH=$HOME/repos/hello/go
export PATH=$HOME/repos/hello/go/bin:$PATH
```

Now, you might be wondering what `# remember source me, don't run me`
means. This means that on the command line, you need to type `. setup`
or `source setup`. It is assumed the file is named `setup`. It will
setup your paths and you will be ready.

##### Bonus

The file will only work if you have a `go` directory in your `hello`
repository. If you wanted this to work for `eightball`, you would
change the `hello`s to `eightball`s. If it is a `go-1` repository,
then you would change the `hello`s to `go-1`s and remove the `/go`s.
