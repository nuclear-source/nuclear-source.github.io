## INSTALL nuclear-soure
###Requires
- Apache  HTTP-server
- PHP > 5.3

*easy install AMP (Apache, Mysql, PHP) software for windows or MAC-OS or LINUX;:*
[xampp](https://www.apachefriends.org/pt_br/index.html)
[wamp](http://www.wampserver.com/en/)


>  use Windows command-line (cmd.exe) or SHELL commands [.git](https://git-scm.com/) or SSH commands [putty](http://www.putty.org/)

```

PATH=%PATH%;c:\xampp\php\ ///define PATH to php.exe file

mkdir my-project //create directory

cd my-project //enter project-directory


//GET nuclear.composer.json

php -r "copy('https://nuclear-source.github.io/nuclear.composer.json','nuclear.composer.json');" 

//GET nuclear.cli 

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

###MORE INFORMATION
[www.nuclearCMS.com](http://www.nuclearcms.com)

###Questions
joelviseu@gmail.com

