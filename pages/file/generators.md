---
description: 必不可少的能源来源。
---

# 发电机

```yaml
EXAMPLE_GENERATOR:
  item_group: example_normal_group
  item:
    name: "&c示例发电机"
    material: GOLD_BLOCK
  capacity: 0 #容量设置0变成不可充电的机器
  production: 100
  input: [10,11]
  output: [15,16]
  recipe_type: ENHANCED_CRAFTING_TABLE
  recipe:
    1:
      material_type: full_slimefun
      material: EXAMPLE_ITEM
    3:
      material_type: full_slimefun
      material: EXAMPLE_ITEM
    5:
      material_type: full_slimefun
      material: EXAMPLE_MACHINE
    7:
      material_type: full_slimefun
      material: EXAMPLE_ITEM
    9:
      material_type: full_slimefun
      material: EXAMPLE_ITEM
  fuels:
    example_fuel:
      item:
        material: OAK_WOOD
      seconds: 10
```

### item\_group,item,recipe\_type,recipe,material\_type,material

详见[**物品**](broken-reference)

### production

发电机每粘液刻的发电量。

### fuels

燃料。

#### seconds

燃料可持续时间，单位：秒。


































