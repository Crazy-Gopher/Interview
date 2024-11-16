# Client Code - using greet package
1. Initilize client code
Add the changes and import the desire package and run the below commands
`go mod init github.com/Crazy-Gopher/Interview`
```
go: creating new go.mod: module github.com/Crazy-Gopher/Interview
go: to add module requirements and sums:
        go mod tidy
```
2. download package
`go mod tidy`
```
go: finding module for package github.com/Crazy-Gopher/greet
go: downloading github.com/Crazy-Gopher/greet v1.0.0
go: found github.com/Crazy-Gopher/greet in github.com/Crazy-Gopher/greet v1.0.0
```

3. Upgrade package
`go get github.com/Crazy-Gopher/greet@v1.0.2`
 
go: downloading github.com/Crazy-Gopher/greet v1.0.2
go: upgraded github.com/Crazy-Gopher/greet v1.0.0 => v1.0.2

4. Downgrade package
`go get github.com/Crazy-Gopher/greet@v1.0.0`
go: downgraded github.com/Crazy-Gopher/greet v1.0.2 => v1.0.0

4. Cleanup(go.sum file)
this command can be used to cleanup and as well as download if add package for the first time.
`go mod tidy`