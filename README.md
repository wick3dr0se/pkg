# pkg
A stupid simple, unified package manager wrapper that simplifies arguments and usage

## Compatability
- pacman->yay (Arch Linux)
- apt (Debian)

## Usage
update packages
```bash
pkg
# or
pkg {-u|update|sync}
```
install specified package(s)
```bash
pkg {-a|add|install} <package>
```

show information about specified package(s)
```bash
pkg {-i|info|show} <package>
```

list installed packages
```bash
pkg {-l|list}
```

list database packages
```bash
pkg {-la|list-all}
```

search for specified package(s) in database
```bash
pkg {-s|search|look} <package>
```

uninstall specified package(s)
```bash
pkg {-d|del|delete|rmv|remove|uninstall} <package>
```
