# ESEP Grade Calculator

This library is a simple utility to calculate your grades.
README.MD: This describes the project’s functionality and tells you how to run the tests. 
go.mod: Declares the Go version and module path. 
grade_calculator.go: This is where the main grade calculator functionality is implemented. 
grade_calculator_test.go: This is where the main functionality from grade_calculaor.go is tested to see if it is functioning as intended. 

Runtime requirements:
Golang 1.24+

Run unit tests:
```
cd grade_calculator/
go test ./...
```

Run unit tests with code coverage:
```
cd grade_calculator/
go test -coverprofile=coverage.txt ./...
```