-- qs-inventory item

```lua

['starter_pack']                       = {
        ['name'] = 'starter_pack',
        ['label'] = 'Starter Pack',
        ['weight'] = 50,
        ['type'] = 'item',
        ['image'] = 'starter_pack.png',
        ['unique'] = false,
        ['useable'] = true,
        ['shouldClose'] = true,
        ['combinable'] = nil,
        ['description'] = 'Starter Pack'
},
```

-- in es_extended -> config.lua
```lua
Config.StartingInventoryItems = {
	starter_pack = 1,
}   
```