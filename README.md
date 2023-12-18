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

#### Install Ruby :
* On Linux or macOS, Ruby is often pre-installed. You can check by typing ruby -v in the terminal. If it's not installed, you can use a package manager like apt (for Ubuntu/Debian) or brew (for macOS) to install it.
* On Windows, you can download the RubyInstaller from [rubyinstaller.org](https://rubyinstaller.org/downloads/) and follow the installation instructions.

### How to use
Navigate to the root of the project and execute the following command :
```sh
   ruby start_app.rb
```

### Standard used :
The standard or naming conventions used in this application are from the following documentations :
[rubystyle.guide](https://rubystyle.guide/)


### Linter :
If you want to use a linter for this program, you can use the following command :
- Go to the root of the project
- Execute this command :
```sh
   rubocop
```

If it does not work, you probably should install it before using the command :
```sh
   gem install rubocop
```

### Tests :
If you want to manually execute the tests, then install:
* Go to the root of the project
* Install _rspec_ to able to execute them
```sh
   gem install rspec
```
* Use this command :
```sh
   rspec .\Tests\rice_cooker_test.rb
```
