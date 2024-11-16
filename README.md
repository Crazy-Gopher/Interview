# Interview
1. download package
Add the changes and import the desire package and run the below commands
```
PS C:\Users\kapil\OneDrive\Desktop\Interview> go mod init github.com/Crazy-Gopher/Interview
go: creating new go.mod: module github.com/Crazy-Gopher/Interview
go: to add module requirements and sums:
        go mod tidy
PS C:\Users\kapil\OneDrive\Desktop\Interview> go mod tidy
go: finding module for package github.com/Crazy-Gopher/greet
go: downloading github.com/Crazy-Gopher/greet v1.0.0
go: found github.com/Crazy-Gopher/greet in github.com/Crazy-Gopher/greet v1.0.0
```

2. Upgrade package
`go get github.com/Crazy-Gopher/greet@v1.0.2`
 
go: downloading github.com/Crazy-Gopher/greet v1.0.2
go: upgraded github.com/Crazy-Gopher/greet v1.0.0 => v1.0.2

3. Downgrade package
`go get github.com/Crazy-Gopher/greet@v1.0.0`
go: downgraded github.com/Crazy-Gopher/greet v1.0.2 => v1.0.0

4. Cleanup(go.sum file)
`go mod tidy`