# ESEP Grade Calculator

This is a Go library that calculates a student's final letter grade from three types of assignments: assignments, exams, and essays.

## How grades are calculated

1. Each grade is in one of the three above categories
2. The average of every category is computed
3. The averages are then weighted accordingly
4. That number is converted into a final letter grade

## Requirements

Go 1.24 or newer

## Project structure

Go.mod: Go module definition
Grade_calculator.go: Library code: "GradeCalculator", "Grade", "GradeType", and the grading logic

## Running tests

go test ./...
go test -coverprofile=coverage.txt ./...