# MythicDungeonInterruptDistributor
MDID
```lua
dungeons = { 
	dungeon = { --地下城名字
		mob = { --怪物名字
			npc_id = '123456', -- 怪物id
			spell_1 = { --法术名称
				spell_id = '123456', --法术id
				priority = 0, --打断优先级
				cast_time = 3, --施法时间
				frequency = 15, --释放频率
			},
			spell_2 = {
				spell_id = '111111',
				priority = 1,
				cast_time = 2, 
				frequency = 5,
			},
		}
	}
}
```
