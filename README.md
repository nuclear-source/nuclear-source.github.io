## INSTALL nuclear-soure
###Requires
- Apache  HTTP-server
- PHP > 5.3

*easy install AMP (Apache, Mysql, PHP) software for windows or MAC-OS or LINUX;:*
[xampp](https://www.apachefriends.org/pt_br/index.html)
[wamp](http://www.wampserver.com/en/)



>  use Windows command-line (cmd.exe) or SHELL commands [.git](https://git-scm.com/) or SSH commands [putty](http://www.putty.org/)

__define PATH to php__

```
PATH=%PATH%;c:\xampp\php\
```

__create directory__

```
mkdir my-project
```

__enter project-directory__

```
cd my-project
```

__GET nuclear.composer.json__ *get->from->repository";*

```
php -r "copy('https://nuclear-source.github.io/nuclear.composer.json','nuclear.composer.json');"
```
__GET nuclear.cli__ *nuclear CLI-console commands";*

```
php -r "copy('https://nuclear-source.github.io/nuclear.cli','nuclear.cli');echo 'done...';" 
```

__run nuclearCLI__

```
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



