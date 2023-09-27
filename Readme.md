###  Run all the tests
```go test ./... -coverprofile=coverage.out```

### Percentage of covered statements
```go tool cover -func=coverage.out```


### Coverage viewer
```
go tool cover -html=coverage.out -o cover.html
```
```
go tool cover -html=coverage.out
```

### Run tests for a file
```
go test your_file_test.go
```

### Run tests for a package
```
go test path/to/your/package
```
