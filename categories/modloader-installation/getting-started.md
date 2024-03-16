## Getting started

### Concepts

Those are things that will be mentioned throughout the guide:
| Name | Definition |
| ---- | ---------- |
| Jarmod | A mod which requires installing to the Minecraft jar directly instead of adding to the `mods` folder. Usually contains base class edits.|
| Total conversion mod | A mod that (usually) overhaul/refactor large parts of the game and are meant to be used standalone. Not compatible with normal loader mods except for mods that are specially developed for it. A few notable examples are New Frontier Craft, Better than Adventure!, ReIndev, Minecraft Diverge, and the Legacy+ Project. |
| Base class edit | Overwriting Minecraft classes. Mods doing so will conflict with other mods that were also overwriting the same class. |
| MCP | Mod Coder Pack. A collection of tools and obfuscation mappings that allow developers to make mods by editing Minecraft classes directly and recompiles to a jarmod. Mods for Risugami's ModLoader are also developed this way. |
| Forge (RML-era) | Forge originally was an extension to Risugami's ModLoader, providing more useful functionalities for developers (for example, ITextureProvider for working around limited sprite atlas.) |

### Picking a launcher

[MultiMC](https://multimc.org/) or [Prism Launcher](https://prismlauncher.org/) are recommended as those are the most easy to work with.

You may also want to look into [BetaCraft Launcher](https://betacraft.uk/) (the bleeding edge 2.0 version can be found [here](https://github.com/betacraftuk/betacraft-launcher/releases)) if you want to play with major total conversion mods or play with old versions of the game without too much hassle.

This guide will be using Prism Launcher, but can also be applied to MultiMC (and by extension, any of its forks too.) Other launchers may also work but you are largely on your own if you run into any issues.

### Java

For most cases, Java 8 is the only version you'll need.

[Eclipse Temurin](https://adoptium.net/temurin/releases/?version=8) versions of Java is recommended due to its rich compatibility. Azul Zulu and other JDKs vendors may also work but there are not much differences between them and some are known to cause issues on non-Windows systems that may be hard to troubleshoot.

### Picking your Minecraft version

Each version may have a different way of playing with mods. Please pick your Minecraft version below (if a version is missing and you want it added, feel free to fork the repository and open a pull request!)

* [Beta 1.7.3 (RML/Babric)](categories/modloader-installation/versions/b1.7.3.md)
