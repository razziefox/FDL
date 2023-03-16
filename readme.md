## FDL - File Description Language
Dead-simple language designed to store meta data of assets

## what is FDL
FDL is a language used for storing meta data for assets that can be loaded up in runtime. FDL itself was designed and developed for game development in mind.

## example
```
# player.fdl

[sprite]
file=player.png
frames=6
width=8
height=8
[/]

[walk]
frames=3
begin=1
end=3
[/]

[flap]
frames=1
begin=4
end=4
[/]

[fall]
frames=1
begin=5
end=5
[/]

[hurt]
frames=1
begin=6
end=6
[/]
```

## parsing libraries
* [Python3](https://github.com/razziefox/fdl-py)
* [Lua](https://github.com/razziefox/fdl-lua)
