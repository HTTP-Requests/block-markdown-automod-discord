# block-markdown-automod-discord
Blocks markdown with regex, helpful for automod.
This si discords newly added extention of markdown.
This only blocks the extended version and not the current ones.

Block all new markdown:
```
(^\s*((\*\s)|(#{1,3}\s)|(\d+\.)).+)|((\[.+\]\(.+\)))
```

Block Embedded Links:
```
(\[.+\]\(.+\))
```

Block Titles:
```
^\s*(#{1,3}\s).+
```

Block Bullet Lists:
```
^\s*(\*\s).+
```

Block Number Lists:
```
^\s*(\d+\.).+
```

Block Links and Titles:
```
(^\s*(#{1,3}).+)|((\[.+\]\(.+\)))
```
