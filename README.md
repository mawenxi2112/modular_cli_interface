dynamic module component based cli application 

not too sure what im going for here but mainly trying to experiment and develop a dynamic plugin/extension framework

this framework is developed to allow simple and easy modular additions of functions or features, simply add a module into the modules folder
and you should be able to utilise the function or whatever is within the module.

something similar to minecraft modpacks/lua scripts

the main.py will be handling all loading of modules, accessing of modules and will act as the interface while being a simple cli application

current available commands:
- help - shows available commands
- list - loads and display available module name, methods and file path
- sudo <module_name> <method_name> - call a specific method within a specific module

https://github.com/mawenxi2112/modular_cli_interface/blob/main/screenshots/cli_application.png
