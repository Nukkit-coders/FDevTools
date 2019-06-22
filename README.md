# FDevTools
__The first devtools plugin for Nukkit!__

# Download
You can get compiled jar file from [nukkitx.com](https://nukkitx.com/resources/fdevtools.81/)

# Feathres
* You can load plugin in source (*.java).
* If you don't have JDK, just download tools.jar from [here](https://drive.google.com/open?id=1KOHZNrD98YTU_66Atbk5JnIqNGp8dcXM) and put it into FDevTools folder.
* You can pack the plugin into jar and relese it easyily.

## Attention
Your source plugin should follow this format:

1. Make a dir in plugins folder (e.g. MyPlugin_src).
2. Put your plugins yml into it.
3. Make a "src" dir into it.
4. Put your source into "src" dir.

Now your plugin should looks like this:
>MyPlugin_src
├plugin.yml
└src
&nbsp;&nbsp;&nbsp;└moe/berd/Test
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└Main.java

# Commands
* `makeplugin <PluginName>` - Compress the plugin into jar format (It must loaded by FDevTools).
