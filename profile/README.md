# Rejuvena
**Redefining tModLoader, one unfinished project at a time.**

Rejuvena, as an organization is—to put it simply—a passion project made by [myself](https://tomat.dev) for two purposes:
1. Creating a custom mod development tool chain that improves development significantly.
2. Creating a geuinely decent content mod for 1.4 to satiate people's hunger.

Everything here is made with the express goal of just having fun.

## ModCompile Alternative
A collection of projects that build a custom ModCompile toolchain.

### [whisker](https://github.com/rejuvena/whisker)
Designed for the collate toolchain (but by no means limited to Terraria modding), whisker is akin to [SpongePowered/Mixin](https://github.com/SpongePowered/Mixin), but for .NET. whisker is a trait/mixin weaving framework designed for modifying .NET IL code in a combined environment of compile-time *and* runtime.

### [backscatter](https://github.com/rejuvena/backscatter)
An advanced reflection library for .NET, with caching capabilities and ease-of-use features, aiming to provide a quality experience without forking over performance.

### [collate](https://github.com/rejuvena/collate)
An alternative to the current tModLoader ModCompile environment, collate is a toolchain designed for developing Terraria mods with ease that has never been seen before.

## Mod Libraries/Utilities
Mod libraries and utility programs aiming to enhance mod development and programmer quality-of-life.

### [tea-framework](https://github.com/rejuvena/tea-framework)
A framework for modding built on top of tModLoader, abstracts a lot of fickle features and implementations away in order to provide stability for modders. Adds in numerous additional features as well, which will be supported through updates that mods will not have to worry about.

### [fluent](https://github.com/rejuvena/fluent)
**Currently postponed.**
A library for adding in custom modded liquids.

<!-- Maybe move this to the toolchain? -->
### [build-configurer](https://github.com/rejuvena/build-configurer)
Designed for the collate toolchain, build-configurer is a simple too for generating build.txt files.

### [rejuvena](https://github.com/rejuvena/rejuvena)
The actual Terraria mod we're working on.

## Terraprisma
The bootstrapper project.

### [terraprisma](https://github.com/rejuvena/terraprisma)
A bootstrapper designed for single-loading advanced patch-heavy mods. Similar to injecting mods such as OptiFine for Minecraft. These are capable of transforming the entire game prior to the assembly being properly loaded.
