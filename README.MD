# ESEP Grade Calculator

This is a simple Go project that calculates a student's final grade using assignments, exams, and essays.

Runtime requirements:
Golang 1.24+

Project Files:
- `README.MD` helps to explain what the project is and how to run it
- `go.mod` has the Go module name and version
- `grade_calculator.go` contains the main code for the grade calculator
- `grade_calculator_test.go` contains the unit tests 

Run unit tests:
```bash
cd grade-calculator/
go test ./...
```

Run unit tests with code coverage:
```
cd grade-calculator/
go test -coverprofile=coverage.txt ./...
```