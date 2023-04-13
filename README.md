## LIST
* [GetBot](#getbot)
* [findPath](#findpath)
* [move](#movebot)
* [getMs](#getms)
* [sendPacket](#sendpacket)
* [sendRawPacket](#sendrawpacket)
* [say](#say)
* [connect](#connect)
* [collect](#collect)
* [remove](#remove)
* [place](#placetile)
* [wrenchTile](#wrench)
* [punch](#punchtile)
* [autoFarm](#autofarming)
* [getBotStatus](#getstatus)
* [wear](#wearitem)
* [drop](#dropitem)

## getbot
`GetBot(string growid)`

Example:
```lua
bot = GetBot("athena")
bot:sendPacket(2, "action|respawn")
```

## findPath
`findPath(int x, int y)`

Example:
```lua
bot = GetBot("athena")
bot:findPath(21, 21)
```


## MoveBot
`move(type, int range)`

max range 7, type : right, left, up, down

Example:
```lua
bot = GetBot("athena")
bot:move(right, 2)
```


## sendPacket
`sendPacket(int type, string packet)`

Example :
```lua
bot = GetBot("athena")
bot:sendPacket(2, "action|respawn")
```


## sendRawPacket
`sendPacketRaw(string game packet, packet)`

Example : 
```lua
bot = GetBot("athena")
packet = {}
packet.type = 10
packet.int_Data = 48
bot:sendPacketRaw(packet)
```


## Say
`say(string text)`

Example :
```lua
bot = GetBot("athena")
bot:say("hello!")
```

## Connect
`connect(string growid, string password)`

Example :
```lua
connect("athena", "athenaontop")
```


## Remove
`remove(string growid)`

Example : 
```lua
remove("athena20")
```


## place
`place(int itemid,int x, int y)`

Example:
```lua
bot = GetBot("athena")
bot:place(2, 0, 0)
```


## WrenchTile
`wrench(int x, int y)`

Example:
```lua
bot = GetBot("athena")
bot:wrench(0,0)
```

## punch
`punch(int x, int y)`

Example : 
```lua
bot = GetBot("athena")
bot:punch(0, 0)
```

## autoFarming
`soon`


## getBotStatus
`soon`


## wearitem
`wear(int itemid)`

## dropitem
`Type :`
`drop(int itemid)`
`drop(int itemid, int amount)`


## Collect
`collect(int range)`



`collect(int range, itemid)`



## getms
```lua
bot = getBot("athena")
bot:getMs() -- console log
```






