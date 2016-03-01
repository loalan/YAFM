# YAFM
Yet Another Food Mod for Minecraft.

Adds some more food to the game.  Yeah yeah, it's been done before, just not by me.

Tested with Minecraft Forge version 11.15.1.1722.

## Compiling
I don't like Eclipse, so here's a step-by-step for how to build this by hand.

Dependencies: JDK, JRE, Gradle (tested with 2.10).

### Once
1. Set the GRADLE_HOME environment variable to wherever you installed Gradle (the folder that contains bin, init.d, lib, etc.).
2. Add JDK\bin, JRE\bin, and GRADLE_HOME\bin to your PATH.

### Every time
1. Navigate to the YAFM source tree.
2. Run "gradle", then "gradle -b abc.gradle" (or the "build-all.bat" script).
3. The result files will be in the "build\libs".

#### Eclipse
For Eclipse if you prefer:
1. Run "gradle eclipse"
2. In Eclipse, Import Existing Project
3. Build and Run Configuration "YAFM_Client"
