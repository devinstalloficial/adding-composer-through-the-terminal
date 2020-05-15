# Adding composer through the terminal

```PROMPT
composer init
```

```PROMPT
Package name (<vendor>/<name>): luizpaulogroup/exemplo
```

```PROMPT
Description []: Adicionando composer via terminal
```

```PROMPT
Author: luizpaulogroup <email@gmail.com>
```

```PROMPT
Minimum Stability []: stable
```

### you can skip this step just below, pressing enter
```PROMPT
Package Type...
```

### Next
```PROMPT
License []: MIT
```

### you can skip this step just below, pressing enter
```PROMPT
Would you like to define your dependencies (require)...
```
```PROMPT
Would you like to define your dependencies (require-dev)...
```

### Next
```PROMPT
Do you confirm generation [yes]? yes
```

```PROMPT
compser update
```

```PROMPT
compser install
```

## Command to add package

### packagist

```PROMPT
composer riquired package_name
```

## The composer.json file will look like this
```JSON
{
    "name": "luizpaulogroup/exemplo",
    "description": "Adicionando composer via terminal",
    "license": "MIT",
    "authors": [
        {
            "name": "luizpaulogroup",
            "email": "email@gmail.com"
        }
    ],
    "minimum-stability": "stable",
    "require": {

    }
}
```
