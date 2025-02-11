---
title: Vanilla Usage Spawn Rules
category: Documentation
toc_max_level: 2
---

# Spawn Rules

This documentation is stripped from the vanilla files using an automated script. If there is an issue, you can tell us about it in [Bedrock OSS](https://discord.gg/XjV87YN) Discord server.

## biome_filter

<Spoiler title="Show">

#### axolotl

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/axolotl.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": {
    "test": "has_biome_tag",
    "operator": "==",
    "value": "lush_caves"
}
```

#### bat

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/bat.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": {
    "test": "has_biome_tag",
    "operator": "==",
    "value": "animal"
}
```

#### bee

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/bee.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": [
    {
        "test": "has_biome_tag",
        "operator": "==",
        "value": "plains"
    },
    {
        "test": "has_biome_tag",
        "operator": "==",
        "value": "sunflower_plains"
    },
    {
        "test": "has_biome_tag",
        "operator": "==",
        "value": "flower_forest"
    }
]
```

#### chicken

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/chicken.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": {
    "test": "has_biome_tag",
    "operator": "==",
    "value": "animal"
}
```

#### cod

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/cod.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": [
    {
        "test": "has_biome_tag",
        "operator": "==",
        "value": "ocean"
    },
    {
        "test": "has_biome_tag",
        "operator": "!=",
        "value": "warm"
    }
]
```

#### cow

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/cow.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": {
    "test": "has_biome_tag",
    "operator": "==",
    "value": "animal"
}
```

#### creeper

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/creeper.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": {
    "test": "has_biome_tag",
    "operator": "==",
    "value": "monster"
}
```

#### dolphin

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/dolphin.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": [
    {
        "test": "has_biome_tag",
        "operator": "==",
        "value": "ocean"
    },
    {
        "test": "has_biome_tag",
        "operator": "!=",
        "value": "frozen"
    }
]
```

#### donkey

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/donkey.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": {
    "test": "has_biome_tag",
    "operator": "==",
    "value": "plains"
}
```

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": {
    "test": "has_biome_tag",
    "operator": "==",
    "value": "meadow"
}
```

#### drowned

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/drowned.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": {
    "test": "has_biome_tag",
    "operator": "==",
    "value": "ocean"
}
```

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": {
    "test": "has_biome_tag",
    "operator": "==",
    "value": "river"
}
```

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": {
    "test": "has_biome_tag",
    "operator": "==",
    "value": "dripstone_caves"
}
```

#### enderman

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/enderman.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": {
    "test": "has_biome_tag",
    "operator": "==",
    "value": "monster"
}
```

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": {
    "all_of": [
        {
            "test": "has_biome_tag",
            "operator": "==",
            "value": "nether"
        },
        {
            "test": "has_biome_tag",
            "operator": "==",
            "value": "spawn_endermen"
        }
    ]
}
```

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": {
    "test": "has_biome_tag",
    "operator": "==",
    "value": "warped_forest"
}
```

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": [
    {
        "test": "has_biome_tag",
        "operator": "==",
        "value": "the_end"
    }
]
```

#### fox

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/fox.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": {
    "test": "has_biome_tag",
    "operator": "==",
    "value": "taiga"
}
```

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": {
    "test": "has_biome_tag",
    "operator": "==",
    "value": "grove"
}
```

#### ghast

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/ghast.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": {
    "all_of": [
        {
            "test": "has_biome_tag",
            "operator": "==",
            "value": "nether"
        },
        {
            "test": "has_biome_tag",
            "operator": "==",
            "value": "spawn_ghast"
        }
    ]
}
```

#### goat

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/goat.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": {
    "any_of": [
        {
            "test": "has_biome_tag",
            "operator": "==",
            "value": "snowy_slopes"
        },
        {
            "test": "has_biome_tag",
            "operator": "==",
            "value": "jagged_peaks"
        },
        {
            "test": "has_biome_tag",
            "operator": "==",
            "value": "frozen_peaks"
        }
    ]
}
```

#### hoglin

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/hoglin.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": {
    "test": "has_biome_tag",
    "operator": "==",
    "value": "crimson_forest"
}
```

#### horse

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/horse.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": {
    "test": "has_biome_tag",
    "operator": "==",
    "value": "plains"
}
```

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": {
    "test": "has_biome_tag",
    "operator": "==",
    "value": "savanna"
}
```

#### husk

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/husk.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": {
    "test": "has_biome_tag",
    "operator": "==",
    "value": "desert"
}
```

#### llama

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/llama.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": {
    "test": "has_biome_tag",
    "operator": "==",
    "value": "extreme_hills"
}
```

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": {
    "test": "has_biome_tag",
    "operator": "==",
    "value": "savanna"
}
```

#### magma_cube

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/magma_cube.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": {
    "test": "has_biome_tag",
    "operator": "==",
    "value": "spawn_magma_cubes"
}
```

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": {
    "test": "has_biome_tag",
    "operator": "==",
    "value": "spawn_many_magma_cubes"
}
```

#### mooshroom

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/mooshroom.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": {
    "test": "has_biome_tag",
    "operator": "==",
    "value": "mooshroom_island"
}
```

#### ocelot

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/ocelot.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": {
    "test": "has_biome_tag",
    "operator": "==",
    "value": "jungle"
}
```

#### panda

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/panda.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": [
    {
        "test": "has_biome_tag",
        "operator": "==",
        "value": "jungle"
    },
    {
        "test": "has_biome_tag",
        "operator": "!=",
        "value": "bamboo"
    }
]
```

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": {
    "test": "has_biome_tag",
    "operator": "==",
    "value": "bamboo"
}
```

#### parrot

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/parrot.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": {
    "test": "has_biome_tag",
    "operator": "==",
    "value": "jungle"
}
```

#### phantom

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/phantom.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": {
    "test": "has_biome_tag",
    "operator": "==",
    "value": "monster"
}
```

#### pig

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/pig.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": {
    "test": "has_biome_tag",
    "operator": "==",
    "value": "animal"
}
```

#### piglin

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/piglin.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": {
    "test": "has_biome_tag",
    "operator": "==",
    "value": "spawn_piglin"
}
```

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": {
    "test": "has_biome_tag",
    "operator": "==",
    "value": "spawn_few_piglins"
}
```

#### pillager_patrol

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/pillager_patrol.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": {
    "all_of": [
        {
            "test": "has_biome_tag",
            "operator": "!=",
            "value": "mooshroom_island"
        },
        {
            "test": "has_biome_tag",
            "operator": "!=",
            "value": "nether"
        },
        {
            "test": "has_biome_tag",
            "operator": "!=",
            "value": "the_end"
        }
    ]
}
```

#### polar_bear

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/polar_bear.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": [
    {
        "test": "has_biome_tag",
        "operator": "==",
        "value": "frozen"
    },
    {
        "test": "has_biome_tag",
        "operator": "!=",
        "value": "ocean"
    }
]
```

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": [
    {
        "test": "has_biome_tag",
        "operator": "==",
        "value": "frozen"
    },
    {
        "test": "has_biome_tag",
        "operator": "==",
        "value": "ocean"
    }
]
```

#### pufferfish

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/pufferfish.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": [
    {
        "test": "has_biome_tag",
        "operator": "==",
        "value": "ocean"
    },
    {
        "test": "has_biome_tag",
        "operator": "==",
        "value": "warm"
    }
]
```

#### rabbit

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/rabbit.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": {
    "any_of": [
        {
            "all_of": [
                {
                    "test": "has_biome_tag",
                    "operator": "==",
                    "value": "taiga"
                },
                {
                    "test": "has_biome_tag",
                    "operator": "!=",
                    "value": "mega"
                }
            ]
        },
        {
            "test": "is_snow_covered",
            "operator": "==",
            "value": true
        },
        {
            "test": "has_biome_tag",
            "operator": "==",
            "value": "desert"
        }
    ]
}
```

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": {
    "any_of": [
        {
            "test": "has_biome_tag",
            "operator": "==",
            "value": "flower_forest"
        },
        {
            "test": "has_biome_tag",
            "operator": "==",
            "value": "grove"
        },
        {
            "test": "has_biome_tag",
            "operator": "==",
            "value": "snowy_slopes"
        }
    ]
}
```

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": {
    "any_of": [
        {
            "test": "has_biome_tag",
            "operator": "==",
            "value": "meadow"
        }
    ]
}
```

#### salmon

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/salmon.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": [
    {
        "test": "has_biome_tag",
        "operator": "==",
        "value": "ocean"
    },
    {
        "test": "has_biome_tag",
        "operator": "!=",
        "value": "warm"
    }
]
```

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": [
    {
        "test": "has_biome_tag",
        "operator": "==",
        "value": "river"
    }
]
```

#### sheep

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/sheep.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": {
    "test": "has_biome_tag",
    "operator": "==",
    "value": "animal"
}
```

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": {
    "test": "has_biome_tag",
    "operator": "==",
    "value": "meadow"
}
```

#### skeleton

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/skeleton.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": {
    "any_of": [
        {
            "all_of": [
                {
                    "test": "has_biome_tag",
                    "operator": "==",
                    "value": "monster"
                },
                {
                    "test": "has_biome_tag",
                    "operator": "!=",
                    "value": "frozen"
                }
            ]
        },
        {
            "test": "has_biome_tag",
            "operator": "==",
            "value": "soulsand_valley"
        }
    ]
}
```

#### slime

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/slime.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": {
    "any_of": [
        {
            "test": "has_biome_tag",
            "operator": "==",
            "value": "monster"
        },
        {
            "test": "has_biome_tag",
            "operator": "==",
            "value": "swamp"
        },
        {
            "test": "has_biome_tag",
            "operator": "==",
            "value": "frozen"
        }
    ]
}
```

#### spider

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/spider.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": {
    "test": "has_biome_tag",
    "operator": "==",
    "value": "monster"
}
```

#### squid

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/squid.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": {
    "test": "has_biome_tag",
    "operator": "==",
    "value": "ocean"
}
```

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": {
    "any_of": [
        {
            "test": "has_biome_tag",
            "operator": "==",
            "value": "river"
        }
    ]
}
```

#### stray

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/stray.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": [
    {
        "test": "has_biome_tag",
        "operator": "==",
        "value": "frozen"
    },
    {
        "test": "has_biome_tag",
        "operator": "!=",
        "value": "ocean"
    }
]
```

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": [
    {
        "test": "has_biome_tag",
        "operator": "==",
        "value": "frozen"
    },
    {
        "test": "has_biome_tag",
        "operator": "==",
        "value": "ocean"
    }
]
```

#### strider

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/strider.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": {
    "test": "has_biome_tag",
    "operator": "==",
    "value": "nether"
}
```

#### tropicalfish

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/tropicalfish.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": [
    {
        "test": "has_biome_tag",
        "operator": "==",
        "value": "ocean"
    },
    {
        "any_of": [
            {
                "test": "has_biome_tag",
                "operator": "==",
                "value": "warm"
            },
            {
                "test": "has_biome_tag",
                "operator": "==",
                "value": "lukewarm"
            }
        ]
    }
]
```

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": {
    "test": "has_biome_tag",
    "operator": "==",
    "value": "lush_caves"
}
```

#### turtle

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/turtle.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": [
    {
        "test": "has_biome_tag",
        "operator": "==",
        "value": "beach"
    },
    {
        "test": "has_biome_tag",
        "operator": "==",
        "value": "warm"
    }
]
```

#### witch

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/witch.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": {
    "test": "has_biome_tag",
    "operator": "==",
    "value": "monster"
}
```

#### wolf

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/wolf.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": {
    "test": "has_biome_tag",
    "operator": "==",
    "value": "taiga"
}
```

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": {
    "test": "has_biome_tag",
    "operator": "==",
    "value": "grove"
}
```

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": {
    "all_of": [
        {
            "test": "has_biome_tag",
            "operator": "==",
            "value": "forest"
        },
        {
            "test": "has_biome_tag",
            "operator": "!=",
            "value": "mutated"
        },
        {
            "test": "has_biome_tag",
            "operator": "!=",
            "value": "birch"
        },
        {
            "test": "has_biome_tag",
            "operator": "!=",
            "value": "roofed"
        },
        {
            "test": "has_biome_tag",
            "operator": "!=",
            "value": "mountain"
        }
    ]
}
```

#### zombie

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/zombie.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": {
    "test": "has_biome_tag",
    "operator": "==",
    "value": "monster"
}
```

#### zombie_pigman

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/zombie_pigman.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": {
    "test": "has_biome_tag",
    "operator": "==",
    "value": "spawn_zombified_piglin"
}
```

<CodeHeader></CodeHeader>

```json
"minecraft:biome_filter": {
    "test": "has_biome_tag",
    "operator": "==",
    "value": "spawn_few_zombified_piglins"
}
```

</Spoiler>

## brightness_filter

<Spoiler title="Show">

#### bat

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/bat.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:brightness_filter": {
    "min": 0,
    "max": 4,
    "adjust_for_weather": true
}
```

#### bee

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/bee.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:brightness_filter": {
    "min": 7,
    "max": 15,
    "adjust_for_weather": false
}
```

#### chicken

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/chicken.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:brightness_filter": {
    "min": 7,
    "max": 15,
    "adjust_for_weather": false
}
```

#### cow

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/cow.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:brightness_filter": {
    "min": 7,
    "max": 15,
    "adjust_for_weather": false
}
```

#### creeper

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/creeper.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:brightness_filter": {
    "min": 0,
    "max": 7,
    "adjust_for_weather": true
}
```

#### donkey

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/donkey.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:brightness_filter": {
    "min": 7,
    "max": 15,
    "adjust_for_weather": false
}
```

#### drowned

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/drowned.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:brightness_filter": {
    "min": 0,
    "max": 7,
    "adjust_for_weather": true
}
```

#### enderman

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/enderman.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:brightness_filter": {
    "min": 0,
    "max": 7,
    "adjust_for_weather": true
}
```

#### fox

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/fox.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:brightness_filter": {
    "min": 7,
    "max": 15,
    "adjust_for_weather": false
}
```

#### goat

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/goat.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:brightness_filter": {
    "min": 7,
    "max": 15,
    "adjust_for_weather": false
}
```

#### horse

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/horse.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:brightness_filter": {
    "min": 7,
    "max": 15,
    "adjust_for_weather": false
}
```

#### husk

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/husk.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:brightness_filter": {
    "min": 0,
    "max": 7,
    "adjust_for_weather": true
}
```

#### llama

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/llama.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:brightness_filter": {
    "min": 7,
    "max": 15,
    "adjust_for_weather": false
}
```

#### mooshroom

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/mooshroom.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:brightness_filter": {
    "min": 9,
    "max": 15,
    "adjust_for_weather": false
}
```

#### ocelot

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/ocelot.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:brightness_filter": {
    "min": 7,
    "max": 15,
    "adjust_for_weather": false
}
```

#### panda

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/panda.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:brightness_filter": {
    "min": 7,
    "max": 15,
    "adjust_for_weather": false
}
```

#### parrot

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/parrot.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:brightness_filter": {
    "min": 7,
    "max": 15,
    "adjust_for_weather": false
}
```

#### phantom

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/phantom.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:brightness_filter": {
    "min": 0,
    "max": 7,
    "adjust_for_weather": true
}
```

#### pig

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/pig.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:brightness_filter": {
    "min": 7,
    "max": 15,
    "adjust_for_weather": false
}
```

#### pillager_patrol

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/pillager_patrol.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:brightness_filter": {
    "min": 0,
    "max": 7,
    "adjust_for_weather": false
}
```

#### polar_bear

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/polar_bear.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:brightness_filter": {
    "min": 7,
    "max": 15,
    "adjust_for_weather": false
}
```

#### rabbit

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/rabbit.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:brightness_filter": {
    "min": 7,
    "max": 15,
    "adjust_for_weather": false
}
```

#### sheep

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/sheep.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:brightness_filter": {
    "min": 7,
    "max": 15,
    "adjust_for_weather": false
}
```

#### skeleton

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/skeleton.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:brightness_filter": {
    "min": 0,
    "max": 7,
    "adjust_for_weather": true
}
```

#### spider

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/spider.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:brightness_filter": {
    "min": 0,
    "max": 7,
    "adjust_for_weather": true
}
```

#### stray

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/stray.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:brightness_filter": {
    "min": 0,
    "max": 7,
    "adjust_for_weather": true
}
```

#### turtle

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/turtle.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:brightness_filter": {
    "min": 7,
    "max": 15,
    "adjust_for_weather": false
}
```

#### witch

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/witch.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:brightness_filter": {
    "min": 0,
    "max": 7,
    "adjust_for_weather": true
}
```

#### wolf

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/wolf.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:brightness_filter": {
    "min": 7,
    "max": 15,
    "adjust_for_weather": false
}
```

#### zombie

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/zombie.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:brightness_filter": {
    "min": 0,
    "max": 7,
    "adjust_for_weather": true
}
```

</Spoiler>

## delay_filter

<Spoiler title="Show">

#### pillager_patrol

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/pillager_patrol.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:delay_filter": {
    "min": 600,
    "max": 660,
    "identifier": "minecraft:pillager_patrol_easy",
    "spawn_chance": 20
}
```

<CodeHeader></CodeHeader>

```json
"minecraft:delay_filter": {
    "min": 600,
    "max": 660,
    "identifier": "minecraft:pillager_patrol_normal",
    "spawn_chance": 20
}
```

<CodeHeader></CodeHeader>

```json
"minecraft:delay_filter": {
    "min": 600,
    "max": 660,
    "identifier": "minecraft:pillager_patrol_hard",
    "spawn_chance": 20
}
```

</Spoiler>

## density_limit

<Spoiler title="Show">

#### axolotl

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/axolotl.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:density_limit": {
    "underground": 5
}
```

#### bat

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/bat.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:density_limit": {
    "surface": 5
}
```

#### cod

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/cod.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:density_limit": {
    "surface": 20
}
```

#### creeper

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/creeper.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:density_limit": {
    "surface": 5
}
```

#### dolphin

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/dolphin.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:density_limit": {
    "surface": 5,
    "underground": 0
}
```

#### drowned

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/drowned.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:density_limit": {
    "surface": 5
}
```

<CodeHeader></CodeHeader>

```json
"minecraft:density_limit": {
    "surface": 2
}
```

#### ghast

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/ghast.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:density_limit": {
    "surface": 0,
    "underground": 2
}
```

#### phantom

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/phantom.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:density_limit": {
    "surface": 5
}
```

#### pufferfish

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/pufferfish.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:density_limit": {
    "surface": 3
}
```

#### salmon

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/salmon.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:density_limit": {
    "surface": 10
}
```

<CodeHeader></CodeHeader>

```json
"minecraft:density_limit": {
    "surface": 4
}
```

#### squid

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/squid.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:density_limit": {
    "surface": 4
}
```

<CodeHeader></CodeHeader>

```json
"minecraft:density_limit": {
    "surface": 2
}
```

#### strider

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/strider.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:density_limit": {
    "surface": 3
}
```

#### tropicalfish

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/tropicalfish.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:density_limit": {
    "surface": 20
}
```

</Spoiler>

## difficulty_filter

<Spoiler title="Show">

#### creeper

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/creeper.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:difficulty_filter": {
    "min": "easy",
    "max": "hard"
}
```

#### drowned

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/drowned.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:difficulty_filter": {
    "min": "easy",
    "max": "hard"
}
```

#### enderman

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/enderman.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:difficulty_filter": {
    "min": "easy",
    "max": "hard"
}
```

#### ghast

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/ghast.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:difficulty_filter": {
    "min": "easy",
    "max": "hard"
}
```

#### hoglin

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/hoglin.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:difficulty_filter": {
    "min": "peaceful",
    "max": "hard"
}
```

#### husk

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/husk.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:difficulty_filter": {
    "min": "easy",
    "max": "hard"
}
```

#### magma_cube

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/magma_cube.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:difficulty_filter": {
    "min": "easy",
    "max": "hard"
}
```

#### phantom

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/phantom.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:difficulty_filter": {
    "min": "easy",
    "max": "hard"
}
```

#### piglin

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/piglin.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:difficulty_filter": {
    "min": "peaceful",
    "max": "hard"
}
```

#### pillager_patrol

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/pillager_patrol.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:difficulty_filter": {
    "max": "easy"
}
```

<CodeHeader></CodeHeader>

```json
"minecraft:difficulty_filter": {
    "min": "normal",
    "max": "normal"
}
```

<CodeHeader></CodeHeader>

```json
"minecraft:difficulty_filter": {
    "min": "hard"
}
```

#### skeleton

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/skeleton.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:difficulty_filter": {
    "min": "easy",
    "max": "hard"
}
```

#### slime

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/slime.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:difficulty_filter": {
    "min": "easy",
    "max": "hard"
}
```

#### spider

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/spider.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:difficulty_filter": {
    "min": "easy",
    "max": "hard"
}
```

#### stray

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/stray.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:difficulty_filter": {
    "min": "easy",
    "max": "hard"
}
```

#### strider

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/strider.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:difficulty_filter": {
    "min": "peaceful",
    "max": "hard"
}
```

#### witch

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/witch.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:difficulty_filter": {
    "min": "easy",
    "max": "hard"
}
```

#### zombie

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/zombie.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:difficulty_filter": {
    "min": "easy",
    "max": "hard"
}
```

#### zombie_pigman

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/zombie_pigman.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:difficulty_filter": {
    "min": "easy",
    "max": "hard"
}
```

</Spoiler>

## disallow_spawns_in_bubble

<Spoiler title="Show">

#### axolotl

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/axolotl.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:disallow_spawns_in_bubble": {}
```

</Spoiler>

## distance_filter

<Spoiler title="Show">

#### cod

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/cod.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:distance_filter": {
    "min": 12,
    "max": 32
}
```

#### pillager_patrol

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/pillager_patrol.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:distance_filter": {
    "min": 24,
    "max": 48
}
```

#### pufferfish

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/pufferfish.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:distance_filter": {
    "min": 12,
    "max": 32
}
```

#### salmon

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/salmon.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:distance_filter": {
    "min": 12,
    "max": 32
}
```

#### tropicalfish

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/tropicalfish.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:distance_filter": {
    "min": 12,
    "max": 32
}
```

</Spoiler>

## height_filter

<Spoiler title="Show">

#### bat

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/bat.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:height_filter": {
    "min": -63,
    "max": 63
}
```

#### cod

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/cod.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:height_filter": {
    "min": 50,
    "max": 64
}
```

#### dolphin

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/dolphin.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:height_filter": {
    "min": 50,
    "max": 64
}
```

#### glow_squid

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/glow_squid.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:height_filter": {
    "min": -64,
    "max": 30
}
```

#### pufferfish

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/pufferfish.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:height_filter": {
    "min": 50,
    "max": 64
}
```

#### salmon

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/salmon.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:height_filter": {
    "min": 50,
    "max": 64
}
```

#### stray

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/stray.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:height_filter": {
    "min": 60,
    "max": 66
}
```

#### tropicalfish

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/tropicalfish.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:height_filter": {
    "min": 50,
    "max": 64
}
```

#### turtle

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/turtle.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:height_filter": {
    "min": 60,
    "max": 67
}
```

</Spoiler>

## herd

<Spoiler title="Show">

#### axolotl

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/axolotl.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:herd": {
    "min_size": 4,
    "max_size": 6,
    "event": "minecraft:entity_born",
    "event_skip_count": 2
}
```

#### bat

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/bat.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:herd": {
    "min_size": 2,
    "max_size": 2
}
```

#### bee

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/bee.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:herd": {
    "min_size": 1,
    "max_size": 1
}
```

#### chicken

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/chicken.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:herd": {
    "min_size": 2,
    "max_size": 4
}
```

#### cod

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/cod.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:herd": {
    "min_size": 4,
    "max_size": 7
}
```

#### cow

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/cow.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:herd": {
    "min_size": 2,
    "max_size": 3
}
```

#### dolphin

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/dolphin.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:herd": {
    "min_size": 3,
    "max_size": 5
}
```

#### donkey

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/donkey.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:herd": {
    "min_size": 2,
    "max_size": 6
}
```

<CodeHeader></CodeHeader>

```json
"minecraft:herd": {
    "min_size": 1,
    "max_size": 2
}
```

#### drowned

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/drowned.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:herd": {
    "min_size": 2,
    "max_size": 4
}
```

#### enderman

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/enderman.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:herd": {
    "min_size": 1,
    "max_size": 2
}
```

<CodeHeader></CodeHeader>

```json
"minecraft:herd": {
    "min_size": 1,
    "max_size": 1
}
```

<CodeHeader></CodeHeader>

```json
"minecraft:herd": {
    "min_size": 4,
    "max_size": 4
}
```

#### fox

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/fox.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:herd": {
    "min_size": 2,
    "max_size": 4,
    "event": "minecraft:entity_born",
    "event_skip_count": 2
}
```

#### glow_squid

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/glow_squid.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:herd": {
    "min_size": 2,
    "max_size": 4
}
```

#### goat

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/goat.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:herd": {
    "min_size": 1,
    "max_size": 3
}
```

#### hoglin

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/hoglin.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:herd": {
    "min_size": 4,
    "max_size": 4
}
```

#### horse

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/horse.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:herd": [
    {
        "min_size": 2,
        "max_size": 6,
        "event": "minecraft:make_white"
    },
    {
        "min_size": 2,
        "max_size": 6,
        "event": "minecraft:make_creamy"
    },
    {
        "min_size": 2,
        "max_size": 6,
        "event": "minecraft:make_chestnut"
    },
    {
        "min_size": 2,
        "max_size": 6,
        "event": "minecraft:make_brown"
    },
    {
        "min_size": 2,
        "max_size": 6,
        "event": "minecraft:make_black"
    },
    {
        "min_size": 2,
        "max_size": 6,
        "event": "minecraft:make_gray"
    },
    {
        "min_size": 2,
        "max_size": 6,
        "event": "minecraft:make_darkbrown"
    }
]
```

#### husk

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/husk.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:herd": {
    "min_size": 2,
    "max_size": 4
}
```

#### llama

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/llama.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:herd": {
    "min_size": 4,
    "max_size": 6
}
```

<CodeHeader></CodeHeader>

```json
"minecraft:herd": {
    "min_size": 4,
    "max_size": 4
}
```

#### magma_cube

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/magma_cube.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:herd": {
    "min_size": 1,
    "max_size": 4
}
```

<CodeHeader></CodeHeader>

```json
"minecraft:herd": {
    "min_size": 2,
    "max_size": 5
}
```

#### mooshroom

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/mooshroom.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:herd": {
    "min_size": 4,
    "max_size": 8
}
```

#### ocelot

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/ocelot.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:herd": {
    "min_size": 1,
    "max_size": 2
}
```

#### panda

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/panda.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:herd": {
    "min_size": 1,
    "max_size": 2
}
```

#### parrot

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/parrot.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:herd": {
    "min_size": 1,
    "max_size": 2
}
```

#### pig

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/pig.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:herd": {
    "min_size": 1,
    "max_size": 3
}
```

#### piglin

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/piglin.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:herd": {
    "min_size": 2,
    "max_size": 4
}
```

<CodeHeader></CodeHeader>

```json
"minecraft:herd": {
    "min_size": 4,
    "max_size": 4
}
```

#### pillager_patrol

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/pillager_patrol.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:herd": {
    "min_size": 2,
    "max_size": 5,
    "initial_event": "minecraft:promote_to_patrol_captain",
    "initial_event_count": 1,
    "event": "minecraft:spawn_as_patrol_follower",
    "event_skip_count": 1
}
```

#### polar_bear

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/polar_bear.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:herd": {
    "min_size": 1,
    "max_size": 2,
    "event": "minecraft:entity_born",
    "event_skip_count": 1
}
```

#### pufferfish

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/pufferfish.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:herd": {
    "min_size": 3,
    "max_size": 5
}
```

#### rabbit

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/rabbit.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:herd": {
    "min_size": 2,
    "max_size": 3
}
```

<CodeHeader></CodeHeader>

```json
"minecraft:herd": {
    "min_size": 2,
    "max_size": 6
}
```

#### salmon

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/salmon.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:herd": {
    "min_size": 3,
    "max_size": 5
}
```

#### sheep

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/sheep.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:herd": {
    "min_size": 2,
    "max_size": 3
}
```

<CodeHeader></CodeHeader>

```json
"minecraft:herd": {
    "min_size": 2,
    "max_size": 4
}
```

#### skeleton

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/skeleton.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:herd": {
    "min_size": 1,
    "max_size": 2
}
```

#### squid

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/squid.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:herd": {
    "min_size": 2,
    "max_size": 4
}
```

#### stray

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/stray.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:herd": {
    "min_size": 1,
    "max_size": 2
}
```

#### strider

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/strider.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:herd": {
    "min_size": 2,
    "max_size": 4
}
```

#### tropicalfish

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/tropicalfish.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:herd": [
    {
        "min_size": 3,
        "max_size": 5,
        "event": "minecraft:become_anenonme"
    },
    {
        "min_size": 3,
        "max_size": 5,
        "event": "minecraft:become_black_tang"
    },
    {
        "min_size": 3,
        "max_size": 5,
        "event": "minecraft:become_blue_dory"
    },
    {
        "min_size": 3,
        "max_size": 5,
        "event": "minecraft:become_butterfly_fish"
    },
    {
        "min_size": 3,
        "max_size": 5,
        "event": "minecraft:become_cichlid"
    },
    {
        "min_size": 3,
        "max_size": 5,
        "event": "minecraft:become_clownfish"
    },
    {
        "min_size": 3,
        "max_size": 5,
        "event": "minecraft:become_cc_betta"
    },
    {
        "min_size": 3,
        "max_size": 5,
        "event": "minecraft:become_dog_fish"
    },
    {
        "min_size": 3,
        "max_size": 5,
        "event": "minecraft:become_e_red_snapper"
    },
    {
        "min_size": 3,
        "max_size": 5,
        "event": "minecraft:become_goat_fish"
    },
    {
        "min_size": 3,
        "max_size": 5,
        "event": "minecraft:become_moorish_idol"
    },
    {
        "min_size": 3,
        "max_size": 5,
        "event": "minecraft:become_ornate_butterfly"
    },
    {
        "min_size": 3,
        "max_size": 5,
        "event": "minecraft:become_parrot_fish"
    },
    {
        "min_size": 3,
        "max_size": 5,
        "event": "minecraft:become_queen_angel_fish"
    },
    {
        "min_size": 3,
        "max_size": 5,
        "event": "minecraft:become_red_cichlid"
    },
    {
        "min_size": 3,
        "max_size": 5,
        "event": "minecraft:become_red_lipped_benny"
    },
    {
        "min_size": 3,
        "max_size": 5,
        "event": "minecraft:become_red_snapper"
    },
    {
        "min_size": 3,
        "max_size": 5,
        "event": "minecraft:become_threadfin"
    },
    {
        "min_size": 3,
        "max_size": 5,
        "event": "minecraft:become_tomato_clown"
    },
    {
        "min_size": 3,
        "max_size": 5,
        "event": "minecraft:become_triggerfish"
    },
    {
        "min_size": 3,
        "max_size": 5,
        "event": "minecraft:become_yellow_tang"
    },
    {
        "min_size": 3,
        "max_size": 5,
        "event": "minecraft:become_yellow_tail_parrot"
    }
]
```

<CodeHeader></CodeHeader>

```json
"minecraft:herd": {
    "min_size": 1,
    "max_size": 3
}
```

#### turtle

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/turtle.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:herd": {
    "min_size": 2,
    "max_size": 6
}
```

#### wolf

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/wolf.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:herd": {
    "min_size": 4,
    "max_size": 4
}
```

<CodeHeader></CodeHeader>

```json
"minecraft:herd": {
    "min_size": 2,
    "max_size": 4
}
```

#### zombie

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/zombie.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:herd": {
    "min_size": 2,
    "max_size": 4
}
```

#### zombie_pigman

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/zombie_pigman.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:herd": {
    "min_size": 2,
    "max_size": 4
}
```

</Spoiler>

## mob_event_filter

<Spoiler title="Show">

#### pillager_patrol

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/pillager_patrol.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:mob_event_filter": {
    "event": "minecraft:pillager_patrols_event"
}
```

</Spoiler>

## permute_type

<Spoiler title="Show">

<CodeHeader></CodeHeader>

```json
"minecraft:permute_type": [
    {
        "weight": 100,
        "entity_type": "minecraft:pillager<minecraft:spawn_as_patrol_follower>"
    }
]
```

#### zombie

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/zombie.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:permute_type": [
    {
        "weight": 95
    },
    {
        "weight": 5,
        "entity_type": "minecraft:zombie_villager_v2"
    }
]
```

</Spoiler>

## player_in_village_filter

<Spoiler title="Show">

#### pillager_patrol

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/pillager_patrol.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:player_in_village_filter": {
    "distance": 48,
    "village_border_tolerance": 32
}
```

</Spoiler>

## spawn_event

<Spoiler title="Show">

#### stray

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/stray.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawn_event": {
    "event": "change_to_skeleton"
}
```

</Spoiler>

## spawns_lava

<Spoiler title="Show">

#### strider

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/strider.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_lava": {}
```

</Spoiler>

## spawns_on_block_filter

<Spoiler title="Show">

#### axolotl

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/axolotl.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_on_block_filter": "minecraft:clay"
```

#### chicken

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/chicken.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_on_block_filter": "minecraft:grass"
```

#### cow

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/cow.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_on_block_filter": "minecraft:grass"
```

#### donkey

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/donkey.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_on_block_filter": "minecraft:grass"
```

#### goat

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/goat.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_on_block_filter": [
    "minecraft:stone",
    "minecraft:snow",
    "minecraft:powder_snow",
    "minecraft:snow_layer",
    "minecraft:packed_ice",
    "minecraft:gravel"
]
```

#### horse

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/horse.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_on_block_filter": "minecraft:grass"
```

#### llama

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/llama.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_on_block_filter": "minecraft:grass"
```

#### ocelot

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/ocelot.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_on_block_filter": "minecraft:grass"
```

#### panda

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/panda.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_on_block_filter": "minecraft:grass"
```

#### parrot

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/parrot.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_on_block_filter": "minecraft:grass"
```

#### pig

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/pig.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_on_block_filter": "minecraft:grass"
```

#### polar_bear

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/polar_bear.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_on_block_filter": "minecraft:ice"
```

#### rabbit

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/rabbit.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_on_block_filter": [
    "minecraft:grass",
    "minecraft:snow",
    "minecraft:sand",
    "minecraft:snow_layer"
]
```

#### sheep

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/sheep.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_on_block_filter": "minecraft:grass"
```

#### turtle

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/turtle.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_on_block_filter": "minecraft:sand"
```

#### wolf

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/wolf.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_on_block_filter": [
    "minecraft:grass",
    "minecraft:podzol",
    "minecraft:dirt"
]
```

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_on_block_filter": "minecraft:grass"
```

</Spoiler>

## spawns_on_block_prevented_filter

<Spoiler title="Show">

#### hoglin

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/hoglin.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_on_block_prevented_filter": [
    "minecraft:nether_wart_block",
    "minecraft:shroomlight"
]
```

#### magma_cube

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/magma_cube.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_on_block_prevented_filter": [
    "minecraft:nether_wart_block",
    "minecraft:shroomlight"
]
```

#### piglin

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/piglin.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_on_block_prevented_filter": [
    "minecraft:nether_wart_block",
    "minecraft:shroomlight"
]
```

#### skeleton

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/skeleton.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_on_block_prevented_filter": [
    "minecraft:nether_wart_block",
    "minecraft:shroomlight"
]
```

#### zombie_pigman

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/zombie_pigman.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_on_block_prevented_filter": [
    "minecraft:nether_wart_block",
    "minecraft:shroomlight"
]
```

</Spoiler>

## spawns_on_surface

<Spoiler title="Show">

#### bee

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/bee.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_on_surface": {}
```

#### chicken

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/chicken.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_on_surface": {}
```

#### cod

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/cod.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_on_surface": {}
```

#### cow

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/cow.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_on_surface": {}
```

#### creeper

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/creeper.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_on_surface": {}
```

#### dolphin

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/dolphin.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_on_surface": {}
```

#### donkey

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/donkey.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_on_surface": {}
```

#### drowned

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/drowned.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_on_surface": {}
```

#### enderman

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/enderman.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_on_surface": {}
```

#### fox

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/fox.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_on_surface": {}
```

#### goat

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/goat.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_on_surface": {}
```

#### horse

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/horse.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_on_surface": {}
```

#### husk

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/husk.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_on_surface": {}
```

#### llama

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/llama.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_on_surface": {}
```

#### mooshroom

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/mooshroom.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_on_surface": {}
```

#### ocelot

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/ocelot.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_on_surface": {}
```

#### panda

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/panda.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_on_surface": {}
```

#### parrot

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/parrot.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_on_surface": {}
```

#### phantom

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/phantom.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_on_surface": {}
```

#### pig

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/pig.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_on_surface": {}
```

#### pillager_patrol

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/pillager_patrol.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_on_surface": {}
```

#### polar_bear

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/polar_bear.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_on_surface": {}
```

#### pufferfish

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/pufferfish.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_on_surface": {}
```

#### rabbit

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/rabbit.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_on_surface": {}
```

#### salmon

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/salmon.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_on_surface": {}
```

#### sheep

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/sheep.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_on_surface": {}
```

#### skeleton

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/skeleton.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_on_surface": {}
```

#### slime

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/slime.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_on_surface": {}
```

#### spider

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/spider.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_on_surface": {}
```

#### squid

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/squid.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_on_surface": {}
```

#### stray

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/stray.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_on_surface": {}
```

#### tropicalfish

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/tropicalfish.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_on_surface": {}
```

#### turtle

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/turtle.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_on_surface": {}
```

#### witch

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/witch.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_on_surface": {}
```

#### wolf

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/wolf.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_on_surface": {}
```

#### zombie

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/zombie.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_on_surface": {}
```

</Spoiler>

## spawns_underground

<Spoiler title="Show">

#### axolotl

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/axolotl.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_underground": {}
```

#### bat

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/bat.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_underground": {}
```

#### creeper

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/creeper.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_underground": {}
```

#### enderman

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/enderman.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_underground": {}
```

#### ghast

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/ghast.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_underground": {}
```

#### glow_squid

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/glow_squid.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_underground": {}
```

#### hoglin

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/hoglin.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_underground": {}
```

#### magma_cube

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/magma_cube.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_underground": {}
```

#### piglin

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/piglin.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_underground": {}
```

#### skeleton

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/skeleton.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_underground": {}
```

#### slime

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/slime.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_underground": {}
```

#### spider

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/spider.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_underground": {}
```

#### stray

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/stray.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_underground": {}
```

#### strider

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/strider.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_underground": {}
```

#### tropicalfish

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/tropicalfish.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_underground": {}
```

#### witch

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/witch.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_underground": {}
```

#### zombie

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/zombie.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_underground": {}
```

#### zombie_pigman

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/zombie_pigman.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_underground": {}
```

</Spoiler>

## spawns_underwater

<Spoiler title="Show">

#### axolotl

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/axolotl.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_underwater": {}
```

#### cod

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/cod.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_underwater": {}
```

#### dolphin

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/dolphin.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_underwater": {}
```

#### drowned

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/drowned.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_underwater": {}
```

#### glow_squid

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/glow_squid.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_underwater": {}
```

#### guardian

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/guardian.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_underwater": {}
```

#### pufferfish

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/pufferfish.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_underwater": {}
```

#### salmon

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/salmon.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_underwater": {}
```

#### squid

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/squid.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_underwater": {}
```

#### tropicalfish

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/tropicalfish.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:spawns_underwater": {}
```

</Spoiler>

## weight

<Spoiler title="Show">

#### axolotl

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/axolotl.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:weight": {
    "default": 10
}
```

#### bat

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/bat.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:weight": {
    "default": 10
}
```

#### bee

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/bee.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:weight": {
    "default": 10
}
```

#### chicken

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/chicken.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:weight": {
    "default": 10
}
```

#### cod

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/cod.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:weight": {
    "default": 75
}
```

#### cow

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/cow.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:weight": {
    "default": 8
}
```

#### creeper

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/creeper.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:weight": {
    "default": 100
}
```

#### dolphin

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/dolphin.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:weight": {
    "default": 7
}
```

#### donkey

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/donkey.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:weight": {
    "default": 1
}
```

#### drowned

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/drowned.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:weight": {
    "default": 100
}
```

<CodeHeader></CodeHeader>

```json
"minecraft:weight": {
    "default": 5
}
```

#### enderman

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/enderman.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:weight": {
    "default": 10
}
```

<CodeHeader></CodeHeader>

```json
"minecraft:weight": {
    "default": 6
}
```

#### fox

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/fox.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:weight": {
    "default": 8
}
```

#### ghast

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/ghast.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:weight": {
    "default": 40
}
```

#### glow_squid

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/glow_squid.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:weight": {
    "default": 10
}
```

#### goat

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/goat.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:weight": {
    "default": 5
}
```

#### hoglin

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/hoglin.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:weight": {
    "default": 20
}
```

#### horse

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/horse.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:weight": {
    "default": 4
}
```

<CodeHeader></CodeHeader>

```json
"minecraft:weight": {
    "default": 1
}
```

#### husk

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/husk.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:weight": {
    "default": 240
}
```

#### llama

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/llama.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:weight": {
    "default": 5
}
```

<CodeHeader></CodeHeader>

```json
"minecraft:weight": {
    "default": 8
}
```

#### magma_cube

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/magma_cube.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:weight": {
    "default": 10
}
```

<CodeHeader></CodeHeader>

```json
"minecraft:weight": {
    "default": 100
}
```

#### mooshroom

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/mooshroom.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:weight": {
    "default": 8
}
```

#### ocelot

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/ocelot.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:weight": {
    "default": 30
}
```

#### panda

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/panda.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:weight": {
    "default": 10
}
```

<CodeHeader></CodeHeader>

```json
"minecraft:weight": {
    "default": 40
}
```

#### parrot

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/parrot.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:weight": {
    "default": 40
}
```

#### phantom

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/phantom.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:weight": {
    "default": 100
}
```

#### pig

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/pig.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:weight": {
    "default": 10
}
```

#### piglin

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/piglin.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:weight": {
    "default": 5
}
```

<CodeHeader></CodeHeader>

```json
"minecraft:weight": {
    "default": 15
}
```

#### polar_bear

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/polar_bear.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:weight": {
    "default": 1
}
```

<CodeHeader></CodeHeader>

```json
"minecraft:weight": {
    "default": 5
}
```

#### pufferfish

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/pufferfish.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:weight": {
    "default": 25
}
```

#### rabbit

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/rabbit.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:weight": {
    "default": 4
}
```

<CodeHeader></CodeHeader>

```json
"minecraft:weight": {
    "default": 2
}
```

#### salmon

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/salmon.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:weight": {
    "default": 26
}
```

<CodeHeader></CodeHeader>

```json
"minecraft:weight": {
    "default": 16
}
```

#### sheep

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/sheep.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:weight": {
    "default": 12
}
```

<CodeHeader></CodeHeader>

```json
"minecraft:weight": {
    "default": 2
}
```

#### skeleton

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/skeleton.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:weight": {
    "default": 80
}
```

#### slime

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/slime.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:weight": {
    "default": 100
}
```

#### spider

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/spider.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:weight": {
    "default": 100
}
```

#### squid

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/squid.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:weight": {
    "default": 8
}
```

#### stray

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/stray.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:weight": {
    "default": 120
}
```

#### strider

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/strider.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:weight": {
    "default": 20
}
```

#### tropicalfish

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/tropicalfish.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:weight": {
    "default": 75
}
```

<CodeHeader></CodeHeader>

```json
"minecraft:weight": {
    "default": 25
}
```

#### turtle

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/turtle.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:weight": {
    "default": 8
}
```

#### witch

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/witch.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:weight": {
    "default": 5
}
```

#### wolf

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/wolf.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:weight": {
    "default": 8
}
```

<CodeHeader></CodeHeader>

```json
"minecraft:weight": {
    "default": 5
}
```

#### zombie

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/zombie.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:weight": {
    "default": 100
}
```

#### zombie_pigman

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/zombie_pigman.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:weight": {
    "default": 100
}
```

<CodeHeader></CodeHeader>

```json
"minecraft:weight": {
    "default": 1
}
```

</Spoiler>

## world_age_filter

<Spoiler title="Show">

#### pillager_patrol

<small>[View file](https://github.com/bedrock-dot-dev/packs/tree/master/stable/behavior/spawn_rules/pillager_patrol.json)</small>

<CodeHeader></CodeHeader>

```json
"minecraft:world_age_filter": {
    "min": 6000
}
```

</Spoiler>