This is a [Scoop](https://scoop.sh/) bucket.

# Including apps

- haxe3
- haxe4
- neko21
- neko23


# Switch Haxe 3 and Haxe 4

## Preparation

### Install

```
scoop install haxe3
scoop install haxe4
```

### Settings

Add `%HAXEPATH%` and `%NEKO_INSTPATH%` to the enviroment variable `Path`.


## How to switch

Warning: The haxelib repository path seems to be not switched automatically.  
Use `haxelib setup`.

### Haxe 3

```
scoop reset haxe3
scoop reset neko21
```

### Haxe 4

```
scoop reset haxe4
scoop reset neko23
```
