## Plugin characteristics:
* Core: Paper
* Supported Version: 1.16.5
## Description:
* This plugin provides protection against falling into the abyss in different worlds.
## Functional:
* Setting up worlds.
* Setting up messages.
* Setting commands to be executed when the player reaches the Abyss.

### Setting up worlds in config.yml:
worlds-list: #List of worlds, you can add an unlimited number.
-  ```spawn: true``` #The value is true, indicating that the NoFall function is enabled in this world. 
-  ```world: false``` #The value is false, indicating that the NoFall function is disabled in this world. 

### Setting up messages in config.yml:
-  ```message: "&5Everskiy&dNoFall &7Больше не падай! Страшна..."``` #Message when falling.
-  ```reloading: "&5Everskiy&dNoFall &7Конфигурация успешно перезагружена!"``` #Message when reloading the plugin.

### Setting commands when the player reaches the abyss:

* ```nofall-command:``` #You can write any command, and any number, all commands are executed on behalf of the console.
* ```  - "tp %player% ~ 100 ~"``` #Command.
