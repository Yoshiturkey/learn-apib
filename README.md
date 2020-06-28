# Learn apiblueprint

https://github.com/danielgtaylor/aglio

## Command

**HOT RELOAD**

```
aglio -i apib/overview.api -s
```

**OUTPUT to HTML**

```
aglio -i apib/overview.apib -o ./docs/index.html
```

**Theme Template**

```
// hot reload
aglio -i apib/overview.apib --theme-template triple -s
```

**Built-in color scheme**

```
// hot reload
aglio -i apib/overview.apib --theme-variables slate -s
```

- cyborg
- default
- flatly
- slate
