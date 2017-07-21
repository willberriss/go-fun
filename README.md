# go-fun
go programming language (go)

    export GOPATH=~/computer/git/go

    ~/computer/git/go-fun$ go env GOPATH
    /home/will/computer/git/go

    ~/computer/git/go-fun$ echo $GOPATH
    /home/will/computer/git/go

    export PATH=$PATH:$(go env GOPATH)/bin

    go install go-fun/hello

    ~/computer/git/go/src/go-fun$ which hello
    /home/will/computer/git/go/bin/hello 


