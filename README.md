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

#### Install Lua :
* If Lua is not installed on your system, you need to install it first. You can download the Lua interpreter from the official website: [download Lua](https://www.lua.org/download.html)

### How to use
Navigate to the root of the project and execute the following command :
```sh
   lua rice_cooker.lua
```

### Standard used :
The standard or naming conventions used in this application are from the following documentations :
[Lua manual](https://www.lua.org/manual/5.4/)


### Linter :
If you want to use a linter for this program, you can use the following command :
- Install luacheck :
```sh
   luarocks install luacheck
```
- Go to the root of the project
- Execute this command :
```sh
   luacheck start_app.lua
```

### Test cases : 
If you want to manually execute the tests, use this command :
```sh
   lua Test_cooker.lua
```
