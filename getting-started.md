## Getting started
### Concepts
Those are the things that will be mentioned throughout the guide:
| Name | Definition |
| ---- | ---------- |
| Jarmod | A mod which requires installing to the Minecraft jar directly instead of adding to the `mods` folder. Usually contains base class edits.|
| Total conversion mod | A mod that (usually) overhaul/refactor large parts of the game and are meant to be used standalone. Not compatible with normal loader mods except for mods that are specially developed for it. A few notable examples are Better than Adventure!, ReIndev, Minecraft Diverge, and the Legacy+ Project. |
| Base class edit | Overwriting Minecraft classes. Mods doing so will conflict with other mods that were also overwriting the same class. |
| MCP | Mod Coder Pack. A collection of tools and obfuscation mappings that allow developers to make mods by editing Minecraft classes directly and recompiles to a jarmod. Mods for Risugami's ModLoader are also developed this way. |
| Forge (RML-era) | Forge originally was an extension to Risugami's ModLoader, providing more useful functionalities for developers (for example, ITextureProvider for working around limited sprite atlas.) |
### Picking a launcher
I recommend using [MultiMC](https://multimc.org/) or [Prism Launcher](https://prismlauncher.org/) as those are the most easy to work with. Please do **NOT** use vanilla Minecraft launcher as it's extremely hard to work with and dealing with issues regarding base class edits (which will be covered later on) can be annoying. Other launchers may also work, but any issues regarding them are yours to deal with.

This guide will be using Prism Launcher, but can also be applied to MultiMC (and by extension, any of its forks too.)
### Java
For most cases, Java 8 is the only version you'll need.

I recommend using [Eclipse Temurin](https://adoptium.net/temurin/releases/?version=8) versions of Java for its rich compatibility. Azul Zulu and other JDKs may also work fine but there are not much differences between them and some are known to cause issues on non-Windows systems.
### Picking your Minecraft version
This guide will be covering all pre-1.2.5 versions of Minecraft; however, at the moment only guide for Beta 1.7.3 is written. Feel free to open a Pull Request for other versions as well!
* [Beta 1.7.3 (RML/Babric)](versions/b1.7.3.md)