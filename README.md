# gmtb-operations
Garry's Mod Trainbuild - Operations

This is hosting location for Operations, an automated train management and routing system built by Metaladon. The main folder should be installed at `steamapps/common/garrysmod/garrysmod/`, which in turn is merged with the existing `data` folder. It contains both a `expression2` and `advdupe2` folders; one containing the hardware in code form, and the other pre-compiled OpsBox sets which should all be cross-compatible and installed with an existing config file.

Additionally, tools for building your own configs are provided in `expression2/tools`, and the Job Selector system by TBEIndustries is provided.

You will also need a copy of the [Convenient Classic Carspawner](https://github.com/SirMetaladon/convenient-classic-carspawner), located here.


Full setup is beyond the scope of a simple explanation; but here's a simple rundown of basic use:

1. Spawn the correct OpsBox dupe for the map you intend to run from the `advdupe` folder.
2. Spawn the latest version of the Carspawner via the E2 tool.
3. Wait for the main Operations e2 to complete preprocessing.
4. Type the chat command .trains - observe the options.
5. Type .train [option] from the previous list.

You may also do .inbound to begin queueing automatic inbound trains.
