<br>
<br>
## How to Compile and Run a Golang Program
<br>
#### FAQ >> Golang >> Run a program
-----------------------------------

  Once you write your glorious bit of golang magic, you probably want
to run it. Since golang is a compiled language, it needs to be
compiled before it is run&mdash;normally. If you want to just run it
for testing, you may want to use `go run file`.
  How you compile depends on how your workspace is. If you have a full
workspace such as `/src/Module/main.go` or similar, you will
compile it using `go install Module`.
If you just have a standalone file, use `go compile file.go`.
To run all of these, just type in the name of the file or module.
**Note:** If the file name is `serve.go`, type in `serve` to run.
