```lua
SendPacket(type, string packet)

Connect(string growid, string password)
wear(int itemid)
drop(int itemid) || drop(int itemid, int amount)
place(int x, int y)
break(int x, int y)
wrench(int x, int y)
move(int radiusx, int radiusy)
findPath(int x, int y)

```

SendPacket(type, string packet)

Example :
```lua
SendPacket(2, "action|respawn")
```
