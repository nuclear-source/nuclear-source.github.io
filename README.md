## INSTALL nuclear-soure
###Requires
- Apache  HTTP-server
- PHP > 5.3

*easy install AMP (Apache, Mysql, PHP) software for windows or MAC-OS or LINUX;:*
[xampp](https://www.apachefriends.org/pt_br/index.html)
[wamp](http://www.wampserver.com/en/)



>  use Windows command-line (cmd.exe) or SHELL commands [.git](https://git-scm.com/) or SSH commands [putty](http://www.putty.org/)

```
//define PATH to php

PATH=%PATH%;c:\xampp\php\

//create directory

mkdir my-project

//enter project-directory

cd my-project

//GET nuclear.composer.json *get->from->repository";*

php -r "copy('https://nuclear-source.github.io/nuclear.composer.json','nuclear.composer.json');"

//GET nuclear.cli *nuclear CLI-console commands";*

php -r "copy('https://nuclear-source.github.io/nuclear.cli','nuclear.cli');echo 'done...';" 

//run nuclearCLI

php nuclear.cli
```

>  nuclear.composer.json __EXAMPLE__

```json
{
    "name": "nuclear-cms",
    "description": "NuclearCMS!",
    "version": "1.0.0",
    "homepage": "http://nuclearcms.com",
    "license": "MIT",
    "authors": [
        {
            "name": "Joel Ferreira",
            "email": "joelviseu@gmail.com",
            "homepage": "http://www.joelferreira.eu",
            "role": "Developer"
        }
    ],
    "publicSELF":true,
    "corePATH":"nuclear.core",
    "repository":"https://nuclear-source.github.io/packages/",
    "packages": {
        "vendor":  "nuclear.vendor.zip",
        "system":  "nuclear.core.zip",
        "default": "nuclear.default.zip"
    }
}
```

###Questions
joelviseu@gmail.com

