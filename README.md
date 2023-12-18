## RICE COOKER #1

<div align="center">
    <img src="https://cdn-icons-png.flaticon.com/256/4152/4152586.png" alt="Logo" width="180" height="180">
</div>
This is a simple Rice cooker application that works mainly on the command line.


It have the basic functionality of a rice cooker :
* Cooks rice with water with 10 Kg and 10 L as the maximum limit
* Cooks other ingredients like vegetables using the steam of the water
* Timer in minutes with warming mode

### Requirements
_Here are the requirements to execute the application :_

#### Install Golang :
* If Golang is not installed on your system, you need to install it first. You can download it from the official website: [download Golang](https://go.dev/dl/)

### How to use
Navigate to the root of the project and execute the following command :
```sh
   go run riceCooker.go
```

### Standard used :
The standard or naming conventions used in this application are from the following documentations :
[Golang manual](https://golang.org/doc/effective_go.html)


### Linter :
If you want to use a linter for this program, you can use the following command :
- Install golangci-lint :
```sh
   go install github.com/golangci/golangci-lint/cmd/golangci-lint@latest
```
- Go to the root of the project
- Execute this command :
```sh
   golangci-lint run
```

### Tests : 
If you want to manually execute the tests, then :
* Go to the root of the project
* Execute this command :
```sh
   go test
```
