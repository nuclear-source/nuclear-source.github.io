## INSTALL nuclear-soure
>  use Windows command-line 

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
php -r "copy('https://nuclear-source.github.io/nuclear.composer.json','nuclear.composer.json');echo 'install...';"
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



