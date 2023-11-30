# tpz_leveling
TPZ-CORE Framework Leveling System


## Get the level and experience values of a leveling type: 

```lua
-- Level Types: hunting, fishing, lumberjack, mining, farming.
local data = exports.tpz_leveling:GetLevelTypeExperienceData(<levelType>)

print(data.level, data.experience)
```
