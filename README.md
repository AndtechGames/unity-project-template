# Unity Template
[Boilr](https://github.com/tmrts/boilr) templates for Unity development.

This repository contains multiple unity templates.

### Unity Project Template
Includes:
* Unity .gitignore
* DocFX documentation template
* GitLab CI/CD workflow

### Unity Package Template
Includes:
* GitHub Actions workflow

# Usage
## Prerequisites
1. Install *Boilr*. ([instructions](https://github.com/tmrts/boilr/wiki/Installation)).

## Instructions
1. Download this repostory.
2. Install a template(s) to your local Boilr registry.
```
$ boilr template save project unity-project
$ boilr template save package unity-package
```

3. Use the template.
```
$ boilr template use unity-project ~/my-project-name
```

> This will create a project named `my-project-name` in your home directory using the `unity-project` template.