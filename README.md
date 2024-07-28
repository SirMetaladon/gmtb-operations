# gmtb-operations
Garry's Mod Trainbuild Operations

This is hosting location for Operations, an automated train management and routing system primarily built & maintained by Metaladon. It contains both `expression2` and `advdupe2` folders; the `expression2` folder holds the code, tooling, and configuration files, and the `advdupe` folder holds compiled OpsBox sets, compatible components pre-staged for easy use. The main folder is installed at `steamapps/common/garrysmod/garrysmod/`, which merges with the existing `data` folder at the same location.

Additionally, tools for building your own configs are provided in `expression2/tools`, and the Job Selector system by TBEIndustries is included.

You will also need a copy of the [Convenient Classic Carspawner](https://github.com/SirMetaladon/convenient-classic-carspawner), located here.


Full setup is beyond the scope of a simple explanation; but here's a simple rundown of basic use:

1. Spawn the correct OpsBox dupe for the map you intend to run from the `advdupe` folder.
2. Spawn the latest version of the Carspawner via the E2 tool.
3. Wait for the main Operations E2 to complete preprocessing.
4. Type the chat command .trains - observe the options.
5. Type .train [option] from the previous list. Example: `.train wrs` will create a WRS consist on SSGRSG.

You may also do .inbound to begin queueing automatic inbound trains.

If you have additional questions on setup, contact me through Discord: [sirmetaladon](https://discordapp.com/users/sirmetaladon)
