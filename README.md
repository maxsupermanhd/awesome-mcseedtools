# awesome-mcseedtools

A list of code and resources for anything seed-worldgen related.

Issues and pull requests are welcome, if you feel like something should be documented here feel free to reach out.

> [!CAUTION]
> Not all of the tools have a GUI, if you don't know how to use the tools, don't say they don't work.
> You can ask for assistance in following discord servers: [19MisterX](https://discord.gg/ANW8hu2S5D) [flexcoral](https://discord.gg/DFsMKWJJPN)

## Locators

Tools to locate a pattern of blocks or other information in the world knowing only the pattern and not their coordinates.

Usually used to locate stashes/bases from screenshots.

| form       | uses              | dims | ver          | link                                                                                         |
| ---------- | ----------------- | ---- | ------------ | -------------------------------------------------------------------------------------------- |
| code: rust | texture rotations | all  | all          | [TextureRotations](https://github.com/19MisterX98/TextureRotations)                          |
| code: java | texture rotations | all  | ?            | [TextureFinderJava](https://github.com/coolmann24/TextureFinderJava)                         |
| code: zig  | bedrock           | o/n  | 1.18+?       | [bedrock-finder-118](https://github.com/silversquirl/bedrock-finder-118)                     |
| code: rust | bedrock           | n?   | 1.18+?       | [BedrockFinder](https://github.com/JorianWoltjer/BedrockFinder)                              |
| code: rust | bedrock           | ?    | ?            | [bedrock-finder](https://github.com/TudbuT/bedrock-finder)                                   |
| code: java | bedrock           | n?   | 1.18+        | [minecraft-bedrock-generator](https://github.com/Developer-Mike/minecraft-bedrock-generator) |
| gui app    | bedrock           | o/n  | 1.12-1.15 +? | [BedrockFinderCpp](https://github.com/coolmann24/BedrockFinderCpp)                           |

Tools to locate valuables in specific area based on the world seed.

| form        | locates                                     | dims | versions | link                                                           |
| ----------- | ------------------------------------------- | ---- | -------- | -------------------------------------------------------------- |
| mod: fabric | biomes, structures, loot, ores, slimechunks | all  | all      | [SeedMapper](https://github.com/xpple/SeedMapper)              |
| gui app     | biomes, structures, slimechunks             | all  | all      | [cubiomes-viewer](https://github.com/Cubitect/cubiomes-viewer) |
| website     | biomes, structures, slimechunks             | all  | all      | [chunkbase.com](https://www.chunkbase.com/apps/seed-map)       |
| website     | ores                                        | all  | all      | [orefinder.gg](https://www.orefinder.gg/)                      |
| library: c  | biomes, structures, loot, ores, slimechunks | all  | all      | [cubiomes](https://github.com/xpple/cubiomes)                  |

## Seed crackers

Tools to obtain a seed for generatable things.

| form            | uses                                      | dims | versions | link                                                                            |
| --------------- | ----------------------------------------- | ---- | -------- | ------------------------------------------------------------------------------- |
| mod: fabric     | biomes, structures, features, hashed seed | all  | all      | [SeedcrackerX](https://github.com/19MisterX98/SeedcrackerX)                     |
| gui app         | bedrock                                   | n    | 1.18+    | [Nether_Bedrock_Cracker](https://github.com/19MisterX98/Nether_Bedrock_Cracker) |
| discord bot     | structures, biomes                        | o    | all      | [19MisterX](https://discord.gg/ANW8hu2S5D)                                      |
| code: java      | structures, features                      | all  | all      | [lifting](https://github.com/hube12/lifting)                                    |
| library: golang | structures, features                      | all  | all      | [go-lifting](https://github.com/maxsupermanhd/go-lifting)                       |
