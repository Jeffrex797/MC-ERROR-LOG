
---- Minecraft Crash Report ----

WARNING: coremods are present:
  WolfArmorCore (WolfArmorAndStorage-1.12.2-3.8.0-universal-signed.jar)
  TransformerLoader (OpenComputers-MC1.12.2-1.7.5.192.jar)
  ParticleCullingLoadingPlugin (particleculling-1.12.2-v1.3.1.jar)
  Thaumic Augmentation Core Plugin (ThaumicAugmentation-1.12.2-2.1.3.jar)
  CXLibraryCore (cxlibrary-1.12.1-1.6.1.jar)
  Quark Plugin (Quark-r1.6-179.jar)
  AppleCore (AppleCore-mc1.12.2-3.4.0.jar)
  SecurityCraftLoadingPlugin ([1.12.2] SecurityCraft v1.9.2.jar)
  iceandfire (iceandfire-1.9.1-1.12.2.jar)
  EntityCullingPlugin (EntityCulling-1.12.2-4.1.5.jar)
  Inventory Tweaks Coremod (InventoryTweaks-1.63.jar)
  HMBFixesCoremod (HMBFixes-1.12.2-12.1.0.jar)
  PhosphorFMLLoadingPlugin (phosphor-1.12.2-0.2.6+build50-universal.jar)
  ratscore (rats-3.2.14-1.12.2.jar)
  LevelUpCore (levelup2-1.5.8.jar)
  LoadingPlugin (ResourceLoader-MC1.12.1-1.5.3.jar)
  Techguns Core (techguns-1.12.2-2.0.2.0_pre3.2.jar)
  MalisisCorePlugin (malisiscore-1.12.2-6.5.1.jar)
  weaponlib (mw_2.0-0.4.4.6_mc1.12.2.jar)
  CoreMod (Aroma1997Core-1.12.2-2.0.0.2.jar)
  RandomPatches (randompatches-1.12.2-1.22.1.10.jar)
  ForgelinPlugin (Forgelin-1.8.4.jar)
  Do not report to Forge! (If you haven't disabled the FoamFix coremod, try disabling it in the config! Note that this bit of text will still appear.) (foamfix-0.10.14-1.12.2.jar)
  OpenModsCorePlugin (OpenModsLib-1.12.2-0.12.2.jar)
  ApotheosisCore (Apotheosis-1.12.2-1.12.5.jar)
  CTMCorePlugin (CTM-MC1.12.2-1.0.2.31.jar)
  SuperMartijn642's Core Lib Plugin (supermartijn642corelib-1.0.18-forge-mc1.12.jar)
  CharmLoadingPlugin (Charm-1.12.2-1.4.1.jar)
  Plugin (NotEnoughIDs-1.5.4.4.jar)
  llibrary (llibrary-core-1.0.11-1.12.2.jar)
  CoreMod (ForgeMixinFix-1.0.0.jar)
  CorePlugin (ForgeEndertech-1.12.2-4.5.6.0-build.0619.jar)
  JustEnoughIDs Extension Plugin (JustEnoughIDs-1.0.3-48.jar)
  HCASM (HammerLib-1.12.2-2.0.6.32.jar)
  TheBetweenlandsLoadingPlugin (TheBetweenlands-3.7.3-SNAPSHOT-20210322.102210-core.jar)
  SpartanWeaponry-MixinLoader (SpartanWeaponry-1.12.2-1.4.1.jar)
  BiggerPacketsPlzCoreMod (biggerpacketsplz-since1.8-1.2.jar)
Contact their authors BEFORE contacting forge

// Surprise! Haha. Well, this is awkward.

Time: 6/30/22 5:51 PM
Description: Initializing game

java.lang.IllegalAccessError: tried to access class org.spongepowered.asm.mixin.transformer.MixinTransformer from class net.minecraftforge.fml.common.Loader
	at net.minecraftforge.fml.common.Loader.handler$zza000$beforeConstructingMods(Loader.java:1132)
	at net.minecraftforge.fml.common.Loader.loadMods(Loader.java:594)
	at net.minecraftforge.fml.client.FMLClientHandler.beginMinecraftLoading(FMLClientHandler.java:232)
	at net.minecraft.client.Minecraft.func_71384_a(Minecraft.java:467)
	at net.minecraft.client.Minecraft.func_99999_d(Minecraft.java:378)
	at net.minecraft.client.main.Main.main(SourceFile:123)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:497)
	at net.minecraft.launchwrapper.Launch.launch(Launch.java:135)
	at net.minecraft.launchwrapper.Launch.main(Launch.java:28)


A detailed walkthrough of the error, its code path and all known details is as follows:
---------------------------------------------------------------------------------------

-- Head --
Thread: Client thread
Stacktrace:
	at net.minecraftforge.fml.common.Loader.handler$zza000$beforeConstructingMods(Loader.java:1132)
	at net.minecraftforge.fml.common.Loader.loadMods(Loader.java:594)
	at net.minecraftforge.fml.client.FMLClientHandler.beginMinecraftLoading(FMLClientHandler.java:232)
	at net.minecraft.client.Minecraft.func_71384_a(Minecraft.java:467)

-- Initialization --
Details:
Stacktrace:
	at net.minecraft.client.Minecraft.func_99999_d(Minecraft.java:378)
	at net.minecraft.client.main.Main.main(SourceFile:123)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:497)
	at net.minecraft.launchwrapper.Launch.launch(Launch.java:135)
	at net.minecraft.launchwrapper.Launch.main(Launch.java:28)

-- System Details --
Details:
	Minecraft Version: 1.12.2
	Operating System: Windows 10 (amd64) version 10.0
	Java Version: 1.8.0_51, Oracle Corporation
	Java VM Version: Java HotSpot(TM) 64-Bit Server VM (mixed mode), Oracle Corporation
	Memory: 630805088 bytes (601 MB) / 1715994624 bytes (1636 MB) up to 15450243072 bytes (14734 MB)
	JVM Flags: 3 total; -XX:HeapDumpPath=MojangTricksIntelDriversForPerformance_javaw.exe_minecraft.exe.heapdump -Xmx16576m -Xms256m
	IntCache: cache: 0, tcache: 0, allocated: 0, tallocated: 0
	FML: MCP 9.42 Powered by Forge 14.23.5.2858 Optifine OptiFine_1.12.2_HD_U_G5 285 mods loaded, 285 mods active
	States: 'U' = Unloaded 'L' = Loaded 'C' = Constructed 'H' = Pre-initialized 'I' = Initialized 'J' = Post-initialized 'A' = Available 'D' = Disabled 'E' = Errored

	| State | ID                                   | Version                     | Source                                                | Signature                                |
	|:----- |:------------------------------------ |:--------------------------- |:----------------------------------------------------- |:---------------------------------------- |
	| L     | minecraft                            | 1.12.2                      | minecraft.jar                                         | None                                     |
	| L     | mcp                                  | 9.42                        | minecraft.jar                                         | None                                     |
	| L     | FML                                  | 8.0.99.99                   | forge-1.12.2-14.23.5.2858.jar                         | e3c3d50c7c986df74c645c0ac54639741c90a557 |
	| L     | forge                                | 14.23.5.2858                | forge-1.12.2-14.23.5.2858.jar                         | e3c3d50c7c986df74c645c0ac54639741c90a557 |
	| L     | entity_culling                       | 4.1.5                       | minecraft.jar                                         | None                                     |
	| L     | openmodscore                         | 0.12.2                      | minecraft.jar                                         | None                                     |
	| L     | foamfixcore                          | 7.7.4                       | minecraft.jar                                         | None                                     |
	| L     | opencomputers|core                   | 1.7.5.192                   | minecraft.jar                                         | None                                     |
	| L     | randompatches                        | 1.12.2-1.22.1.10            | randompatches-1.12.2-1.22.1.10.jar                    | None                                     |
	| L     | techguns_core                        | 1.12.2-1.0                  | minecraft.jar                                         | None                                     |
	| L     | securitycraft                        | v1.9.2                      | [1.12.2] SecurityCraft v1.9.2.jar                     | None                                     |
	| L     | fastbench                            | 1.7.3                       | FastWorkbench-1.12.2-1.7.3.jar                        | None                                     |
	| L     | actuallyadditions                    | 1.12.2-r152                 | ActuallyAdditions-1.12.2-r152.jar                     | None                                     |
	| L     | forgeendertech                       | 1.12.2-4.5.6.0              | ForgeEndertech-1.12.2-4.5.6.0-build.0619.jar          | None                                     |
	| L     | adhooks                              | 1.12.2-3.3.1.0              | AdHooks-1.12.2-3.3.1.0-build.0626.jar                 | None                                     |
	| L     | adlods                               | 1.12.2-1.0.8.0              | AdLods-1.12.2-1.0.8.0-build.0504.jar                  | None                                     |
	| L     | aether_legacy                        | 1.5.3.2                     | aether-1.12.2-v1.5.3.2.jar                            | None                                     |
	| L     | aether_legacy_addon                  | 1.12.2-v1.3.0               | Aether Continuation v1.3.0.jar                        | None                                     |
	| L     | aiimprovements                       | 0.0.1.3                     | AIImprovements-1.12-0.0.1b3.jar                       | None                                     |
	| L     | aireducer                            | 0.2.1                       | AIReducer-1.12.2-0.2.1.jar                            | None                                     |
	| L     | akashictome                          | 1.2-12                      | AkashicTome-1.2-12.jar                                | None                                     |
	| L     | baubles                              | 1.5.2                       | Baubles-1.12-1.5.2.jar                                | None                                     |
	| L     | crafttweaker                         | 4.1.20                      | CraftTweaker2-1.12-4.1.20.653.jar                     | None                                     |
	| L     | jei                                  | 4.16.1.302                  | jei_1.12.2-4.16.1.302.jar                             | None                                     |
	| L     | ebwizardry                           | 4.3.7                       | ElectroblobsWizardry-4.3.7-MC1.12.2.jar               | None                                     |
	| L     | ancientspellcraft                    | 1.1.3                       | ancientspellcraft-1.1.3.jar                           | None                                     |
	| L     | anvilpatch                           | 1.1.0                       | anvilpatch-1.1.0.jar                                  | None                                     |
	| L     | placebo                              | 1.6.0                       | Placebo-1.12.2-1.6.0.jar                              | None                                     |
	| L     | apotheosis                           | 1.12.4                      | Apotheosis-1.12.2-1.12.5.jar                          | None                                     |
	| L     | applecore                            | 3.4.0                       | AppleCore-mc1.12.2-3.4.0.jar                          | None                                     |
	| L     | appleskin                            | 1.0.14                      | AppleSkin-mc1.12-1.0.14.jar                           | None                                     |
	| L     | aquaculture                          | 1.6.8                       | Aquaculture-1.12.2-1.6.8.jar                          | None                                     |
	| L     | aroma1997core                        | 2.0.0.2                     | Aroma1997Core-1.12.2-2.0.0.2.jar                      | None                                     |
	| L     | aroma1997sdimension                  | 2.0.0.2                     | Aroma1997s-Dimensional-World-1.12.2-2.0.0.2.jar       | None                                     |
	| L     | atum                                 | 2.0.20                      | Atum-1.12.2-2.0.20.jar                                | None                                     |
	| L     | quark                                | r1.6-179                    | Quark-r1.6-179.jar                                    | None                                     |
	| L     | autoreglib                           | 1.3-32                      | AutoRegLib-1.3-32.jar                                 | None                                     |
	| L     | badwithernocookiereloaded            | 1.12.2-3.4.18               | badwithernocookiereloaded-1.12.2-3.4.18.jar           | None                                     |
	| L     | bno                                  | 1.12.2-1.0.4.0              | BasicNetherOres-1.12.2-1.0.5.0.jar                    | None                                     |
	| L     | battletowers                         | 1.6.5                       | BattleTowers-1.12.2.jar                               | None                                     |
	| L     | betteradvancements                   | 0.1.0.77                    | BetterAdvancements-1.12.2-0.1.0.77.jar                | None                                     |
	| L     | betterbuilderswands                  | 0.11.1                      | BetterBuildersWands-1.12-0.11.1.245+69d0d70.jar       | None                                     |
	| L     | bettermineshafts                     | 1.12.2-2.2.1                | BetterMineshaftsForge-1.12.2-2.2.1.jar                | None                                     |
	| L     | bibliocraft                          | 2.4.6                       | BiblioCraft[v2.4.6][MC1.12.2].jar                     | None                                     |
	| L     | biggerpacketsplz                     | 1.2                         | biggerpacketsplz-since1.8-1.2.jar                     | None                                     |
	| L     | biomesoplenty                        | 7.0.1.2445                  | BiomesOPlenty-1.12.2-7.0.1.2445-universal.jar         | None                                     |
	| L     | bonsaitrees                          | 1.1.4                       | bonsaitrees-1.1.4-b170.jar                            | None                                     |
	| L     | bookshelf                            | 2.3.590                     | Bookshelf-1.12.2-2.3.590.jar                          | None                                     |
	| L     | forgelin                             | 1.8.4                       | Forgelin-1.8.4.jar                                    | None                                     |
	| L     | bountiful                            | 2.2.2                       | Bountiful-2.2.2.jar                                   | None                                     |
	| L     | buildcraftlib                        | 7.99.24.8                   | buildcraft-all-7.99.24.8.jar                          | None                                     |
	| L     | buildcraftcore                       | 7.99.24.8                   | buildcraft-all-7.99.24.8.jar                          | None                                     |
	| L     | buildcraftbuilders                   | 7.99.24.8                   | buildcraft-all-7.99.24.8.jar                          | None                                     |
	| L     | buildcrafttransport                  | 7.99.24.8                   | buildcraft-all-7.99.24.8.jar                          | None                                     |
	| L     | buildcraftsilicon                    | 7.99.24.8                   | buildcraft-all-7.99.24.8.jar                          | None                                     |
	| L     | buildcraftcompat                     | 7.99.24.8                   | buildcraft-all-7.99.24.8.jar                          | None                                     |
	| L     | buildcraftenergy                     | 7.99.24.8                   | buildcraft-all-7.99.24.8.jar                          | None                                     |
	| L     | buildcraftfactory                    | 7.99.24.8                   | buildcraft-all-7.99.24.8.jar                          | None                                     |
	| L     | buildcraftrobotics                   | 7.99.24.8                   | buildcraft-all-7.99.24.8.jar                          | None                                     |
	| L     | buildinggadgets                      | 2.8.4                       | BuildingGadgets-2.8.4.jar                             | None                                     |
	| L     | callablehorses                       | 1.1                         | callablehorses-1.12.2-1.1.jar                         | None                                     |
	| L     | carryon                              | 1.12.3                      | carryon-1.12.2-1.12.6.20.jar                          | None                                     |
	| L     | chameleon                            | 1.12-4.1.3                  | Chameleon-1.12-4.1.3.jar                              | None                                     |
	| L     | chancecubes                          | 1.12.2-5.0.2.385            | ChanceCubes-1.12.2-5.0.2.385.jar                      | None                                     |
	| L     | charm                                | 1.4                         | Charm-1.12.2-1.4.1.jar                                | None                                     |
	| L     | chesttransporter                     | 2.8.8                       | ChestTransporter-1.12.2-2.8.8.jar                     | None                                     |
	| L     | codechickenlib                       | 3.2.3.358                   | CodeChickenLib-1.12.2-3.2.3.358-universal.jar         | None                                     |
	| L     | chickenchunks                        | 2.4.2.74                    | ChickenChunks-1.12.2-2.4.2.74-universal.jar           | None                                     |
	| L     | ctm                                  | MC1.12.2-1.0.2.31           | CTM-MC1.12.2-1.0.2.31.jar                             | None                                     |
	| L     | mysticalworld                        | 1.12.2-1.9.8                | mysticalworld-1.12.2-1.9.8.jar                        | None                                     |
	| L     | chisel                               | MC1.12.2-1.0.2.45           | Chisel-MC1.12.2-1.0.2.45.jar                          | None                                     |
	| L     | clumps                               | 3.1.2                       | Clumps-3.1.2.jar                                      | None                                     |
	| L     | cyclopscore                          | 1.6.7                       | CyclopsCore-1.12.2-1.6.7.jar                          | None                                     |
	| L     | colossalchests                       | 1.7.3                       | ColossalChests-1.12.2-1.7.3.jar                       | None                                     |
	| L     | combustfish                          | 1.0.3.4                     | combustfish-1.12.2-1.0.3.4.jar                        | None                                     |
	| L     | comforts                             | 1.4.1.3                     | comforts-1.12.2-1.4.1.3.jar                           | None                                     |
	| L     | commandkeybindings                   | 7.0.3                       | CommandKeybindings-1.12.2-7.0.3.jar                   | None                                     |
	| L     | controlling                          | 3.0.10                      | Controlling-3.0.10.jar                                | None                                     |
	| L     | cookingforblockheads                 | 6.5.0                       | CookingForBlockheads_1.12.2-6.5.0.jar                 | None                                     |
	| L     | cosmeticarmorreworked                | 1.12.2-v5a                  | CosmeticArmorReworked-1.12.2-v5a.jar                  | None                                     |
	| L     | ctgui                                | 1.0.0                       | CraftTweaker2-1.12-4.1.20.653.jar                     | None                                     |
	| L     | crafttweakerjei                      | 2.0.3                       | CraftTweaker2-1.12-4.1.20.653.jar                     | None                                     |
	| L     | thaumcraft                           | 6.1.BETA26                  | Thaumcraft-1.12.2-6.1.BETA26.jar                      | None                                     |
	| L     | crimsonrevelations                   | 0.8                         | crimsonrevelations-0.8.jar                            | None                                     |
	| L     | cucumber                             | 1.1.3                       | Cucumber-1.12.2-1.1.3.jar                             | None                                     |
	| L     | custommainmenu                       | 2.0.9.1                     | CustomMainMenu-MC1.12.2-2.0.9.1.jar                   | None                                     |
	| L     | cxlibrary                            | 1.6.1                       | cxlibrary-1.12.1-1.6.1.jar                            | None                                     |
	| L     | waila                                | 1.8.26                      | Hwyla-1.8.26-B41_1.12.2.jar                           | None                                     |
	| L     | mantle                               | 1.12-1.3.3.55               | Mantle-1.12-1.3.3.55.jar                              | None                                     |
	| L     | projecte                             | 1.12.2-PE1.4.1              | ProjectE-1.12.2-PE1.4.1.jar                           | None                                     |
	| L     | twilightforest                       | 3.11.1021                   | twilightforest-1.12.2-3.11.1021-universal.jar         | None                                     |
	| L     | tconstruct                           | 1.12.2-2.13.0.183           | TConstruct-1.12.2-2.13.0.183.jar                      | None                                     |
	| L     | p455w0rdslib                         | 2.3.161                     | p455w0rdslib-1.12.2-2.3.161.jar                       | None                                     |
	| L     | stg                                  | 1.12.2-1.2.3                | stg-1.12.2-1.2.3.jar                                  | None                                     |
	| L     | mousetweaks                          | 2.10.1                      | MouseTweaks-2.10.1-mc1.12.2.jar                       | None                                     |
	| L     | danknull                             | 1.7.101                     | DankNull-1.12.2-1.7.101.jar                           | None                                     |
	| L     | ptrmodellib                          | 1.0.5                       | PTRLib-1.0.5.jar                                      | None                                     |
	| L     | props                                | 2.6.3.7                     | Decocraft-2.6.3.7_1.12.2.jar                          | None                                     |
	| L     | diethopper                           | 1.1                         | diethopper-1.1.jar                                    | None                                     |
	| L     | ding                                 | 1.0.2                       | Ding-1.12.2-1.0.2.jar                                 | None                                     |
	| L     | disenchanter                         | 1.8                         | disenchanter[1.12]1.8.jar                             | None                                     |
	| L     | doggytalents                         | 1.15.1.6                    | DoggyTalents-1.12.2-1.15.1.6.jar                      | None                                     |
	| L     | dungeontactics                       | DT-0.16.9                   | DungeonTactics-1.12.2-0.16.9.jar                      | None                                     |
	| L     | easiervillagertrading                | 1.3                         | easiervillagertrading-1.12-forge14.21.1.2387-1.3.jar  | None                                     |
	| L     | elenaidodge                          | 2.1                         | ElenaiDodge-1.12.2-2.1.jar                            | None                                     |
	| L     | elevatorid                           | 1.3.14                      | ElevatorMod-1.12.2-1.3.14.jar                         | None                                     |
	| L     | mysticalmechanics                    | 0.18                        | Mystical Mechanics-0.18.jar                           | None                                     |
	| L     | embers                               | 1.18                        | EmbersRekindled-1.18.jar                              | None                                     |
	| L     | embersified                          | 1.0.3                       | Embersified-1.12.2-1.0.3.jar                          | None                                     |
	| L     | projectex                            | 1.2.0.40                    | ProjectEX-1.2.0.40.jar                                | None                                     |
	| L     | emcbaubles                           | 1.0                         | emcbaubles-1.12-1.0.jar                               | None                                     |
	| L     | eplus                                | 5.0.176                     | EnchantingPlus-1.12.2-5.0.176.jar                     | None                                     |
	| L     | enchdesc                             | 1.1.15                      | EnchantmentDescriptions-1.12.2-1.1.15.jar             | None                                     |
	| L     | enderstorage                         | 2.4.6.137                   | EnderStorage-1.12.2-2.4.6.137-universal.jar           | None                                     |
	| L     | reborncore                           | 3.19.5                      | RebornCore-1.12.2-3.19.5-universal.jar                | None                                     |
	| L     | engineersworkshop                    | 1.0.9.40                    | EngineersWorkshopReborn-1.12.2-1.0.9.40.jar           | None                                     |
	| L     | erebus                               | 1.0.32                      | Erebus-1.0.32.jar                                     | None                                     |
	| L     | hammercore                           | 2.0.6.32                    | HammerLib-1.12.2-2.0.6.32.jar                         | None                                     |
	| L     | expequiv                             | 12.3.17                     | ExpandedEquivalence-1.12.2-12.3.17.jar                | None                                     |
	| L     | minerva                              | 1.0.13                      | minerva-library-1.0.13.jar                            | None                                     |
	| L     | extraalchemy                         | 0.5.4                       | extraalchemy-forge-1.12-build11-0.5.4.jar             | None                                     |
	| L     | potioncore                           | 1.9_for_1.12.2              | PotionCore-1.9_for_1.12.2.jar                         | None                                     |
	| L     | extra_spells                         | 1.2.0                       | ExtraSpells-1.12.2-1.2.0.jar                          | None                                     |
	| L     | extrautils2                          | 1.0                         | extrautils2-1.12-1.9.9.jar                            | None                                     |
	| L     | llibrary                             | 1.7.20                      | llibrary-1.7.20-1.12.2.jar                            | None                                     |
	| L     | iceandfire                           | 1.9.1                       | iceandfire-1.9.1-1.12.2.jar                           | None                                     |
	| L     | eyeofdragons                         | 0.0.1                       | eyeofdragons-0.0.2.jar                                | None                                     |
	| L     | fastfurnace                          | 1.3.1                       | FastFurnace-1.12.2-1.3.1.jar                          | None                                     |
	| L     | findme                               | 1.1.0                       | findme-1.12.2-1.1.0-8.jar                             | None                                     |
	| L     | foamfix                              | 0.10.14-1.12.2              | foamfix-0.10.14-1.12.2.jar                            | None                                     |
	| L     | forgemultipartcbe                    | 2.6.2.83                    | ForgeMultipart-1.12.2-2.6.2.83-universal.jar          | None                                     |
	| L     | microblockcbe                        | 2.6.2.83                    | ForgeMultipart-1.12.2-2.6.2.83-universal.jar          | None                                     |
	| L     | minecraftmultipartcbe                | 2.6.2.83                    | ForgeMultipart-1.12.2-2.6.2.83-universal.jar          | None                                     |
	| L     | ftbbackups                           | 1.1.0.1                     | FTBBackups-1.1.0.1.jar                                | None                                     |
	| L     | ftblib                               | 5.4.7.2                     | FTBLib-5.4.7.2.jar                                    | None                                     |
	| L     | ftbguides                            | 2.0.0.52                    | FTBGuides-2.0.0.52.jar                                | None                                     |
	| L     | ftbutilities                         | 5.4.1.131                   | FTBUtilities-5.4.1.131.jar                            | None                                     |
	| L     | itemfilters                          | 1.0.4.2                     | ItemFilters-1.0.4.2.jar                               | None                                     |
	| L     | ftbquests                            | 1202.9.0.15                 | FTBQuests-1202.9.0.15.jar                             | None                                     |
	| L     | ftbmoney                             | 1.2.0.47                    | FTBMoney-1.2.0.47.jar                                 | None                                     |
	| L     | gottschcore                          | 1.15.0                      | GottschCore-mc1.12.2-f14.23.5.2859-v1.15.0.jar        | None                                     |
	| L     | hbm                                  | hbm-1.6.8Av2-1.12.2         | hbm-1.6.8a-Gv2.jar                                    | None                                     |
	| L     | heroicarmory                         | 1.1.3                       | heroicarmory-1.2.0.jar                                | None                                     |
	| L     | zhbmfixes                            | 12.1.0                      | HMBFixes-1.12.2-12.1.0.jar                            | None                                     |
	| L     | icbmclassic                          | 1.12.2-4.1.0.20211106011047 | ICBM-classic-1.12.2-4.1.0b20211106011048.jar          | None                                     |
	| L     | ichunutil                            | 7.2.2                       | iChunUtil-1.12.2-7.2.2.jar                            | None                                     |
	| L     | improvedbackpacks                    | 1.12.2-1.5.0.0              | ImprovedBackpacks-1.12.2-1.5.0.0.jar                  | None                                     |
	| L     | infernalmobs                         | 1.7.6                       | InfernalMobs-1.12.2.jar                               | None                                     |
	| L     | inventorypets                        | 2.0.15                      | inventorypets-1.12-2.0.15.jar                         | None                                     |
	| L     | inventorytweaks                      | 1.63+release.109.220f184    | InventoryTweaks-1.63.jar                              | None                                     |
	| L     | ironchest                            | 1.12.2-7.0.67.844           | ironchest-1.12.2-7.0.72.847.jar                       | None                                     |
	| L     | ironfurnaces                         | 1.3.5                       | ironfurnaces-1.3.5.jar                                | None                                     |
	| L     | ironjetpacks                         | 1.1.0                       | IronJetpacks-1.12-2-1.1.0.jar                         | None                                     |
	| L     | supermartijn642configlib             | 1.1.3                       | supermartijn642configlib-1.1.3-forge-mc1.12.jar       | None                                     |
	| L     | supermartijn642corelib               | 1.0.16b                     | supermartijn642corelib-1.0.18-forge-mc1.12.jar        | None                                     |
	| L     | itemcollectors                       | 1.1.5                       | itemcollectors-1.1.5-mc1.12.jar                       | None                                     |
	| L     | jeiintegration                       | 1.6.0                       | jeiintegration_1.12.2-1.6.0.jar                       | None                                     |
	| L     | journeymap                           | 1.12.2-5.7.1                | journeymap-1.12.2-5.7.1.jar                           | None                                     |
	| L     | jrftl                                | 1.1                         | JRFTL[1.12.2]-1.1.jar                                 | None                                     |
	| L     | harvestcraft                         | 1.12.2zb                    | Pam's HarvestCraft 1.12.2zg.jar                       | None                                     |
	| L     | jehc                                 | 1.7.2                       | just-enough-harvestcraft-1.12.2-1.7.2.jar             | None                                     |
	| L     | jecalculation                        | 1.12.2-3.2.7                | JustEnoughCalculation-1.12.2-3.2.7.jar                | None                                     |
	| L     | jeid                                 | 1.0.3-48                    | JustEnoughIDs-1.0.3-48.jar                            | None                                     |
	| L     | jeresources                          | 0.9.2.60                    | JustEnoughResources-1.12.2-0.9.2.60.jar               | None                                     |
	| L     | keywizard                            | 1.12.2-1.7.3                | keywizard-1.12.2-1.7.3.jar                            | None                                     |
	| L     | letsencryptcraft                     | @VERSION@                   | letsencryptcraft-1.10.2-1.2.0.jar                     | None                                     |
	| L     | levelup2                             | ${version}                  | levelup2-1.5.8.jar                                    | None                                     |
	| L     | libraryex                            | 1.2.2                       | LibraryEx-1.12.2-1.2.2.jar                            | None                                     |
	| L     | limelib                              | 1.7.12                      | limelib-1.12.2-1.7.12.jar                             | None                                     |
	| L     | livingenchantment                    | 3.2.3                       | living_enchantment-3.2.3.jar                          | None                                     |
	| L     | login_shield                         | 1.12.2-6-g5654706           | Login_Shield-1.12.2-6-g5654706.jar                    | None                                     |
	| L     | lootbags                             | 2.5.8.5                     | LootBags-1.12.2-2.5.8.5.jar                           | None                                     |
	| L     | lost_aether                          | 1.0.2                       | lost-aether-content-1.12.2-1.0.2.jar                  | None                                     |
	| L     | lunatriuscore                        | 1.2.0.42                    | LunatriusCore-1.12.2-1.2.0.42-universal.jar           | None                                     |
	| L     | mainmenuscale                        | 1.0                         | MainMenuScale-1.3.2.jar                               | None                                     |
	| L     | malisiscore                          | 1.12.2-6.5.1-SNAPSHOT       | malisiscore-1.12.2-6.5.1.jar                          | None                                     |
	| L     | malisisdoors                         | 1.12.2-7.3.0                | malisisdoors-1.12.2-7.3.0.jar                         | None                                     |
	| L     | mcwbridges                           | 1.0.6                       | mcw-bridges-1.0.6b-mc1.12.2.jar                       | None                                     |
	| L     | mcwdoors                             | 1.3                         | mcw-doors-1.0.3-mc1.12.2.jar                          | None                                     |
	| L     | mcwfences                            | 1.0.0                       | mcw-fences-1.0.0-mc1.12.2.jar                         | None                                     |
	| L     | mcwfurnitures                        | 1.0.1                       | mcw-furniture-1.0.1-mc1.12.2beta.jar                  | None                                     |
	| L     | mcwroofs                             | 1.0.2                       | mcw-roofs-1.0.2-mc1.12.2.jar                          | None                                     |
	| L     | mcwtrpdoors                          | 1.0.2                       | mcw-trapdoors-1.0.3-mc1.12.2.jar                      | None                                     |
	| L     | mcwwindows                           | 1.0                         | mcw-windows-1.0.0-mc1.12.2.jar                        | None                                     |
	| L     | megaloot                             | 0.2.40                      | megaloot-1.12.2-0.2.40.jar                            | None                                     |
	| L     | moartinkers                          | 0.6.0                       | moartinkers-0.6.0.jar                                 | None                                     |
	| L     | modnametooltip                       | 1.10.1                      | modnametooltip_1.12.2-1.10.1.jar                      | None                                     |
	| L     | morefurnaces                         | 1.10.5                      | MoreFurnaces-1.12.2-1.10.6.jar                        | None                                     |
	| L     | moreoverlays                         | 1.15.1                      | moreoverlays-1.15.1-mc1.12.2.jar                      | None                                     |
	| L     | mw                                   | 0.4.4.6                     | mw_2.0-0.4.4.6_mc1.12.2.jar                           | None                                     |
	| L     | mysticalagriculture                  | 1.7.5                       | MysticalAgriculture-1.12.2-1.7.5.jar                  | None                                     |
	| L     | mysticalagradditions                 | 1.3.2                       | MysticalAgradditions-1.12.2-1.3.2.jar                 | None                                     |
	| L     | naturescompass                       | 1.8.5                       | NaturesCompass-1.12.2-1.8.5.jar                       | None                                     |
	| L     | netherex                             | 2.2.5                       | NetherEx-1.12.2-2.2.5.jar                             | None                                     |
	| L     | yurtmod                              | 9.5.2                       | NomadicTents-1.12.2-9.5.2.jar                         | None                                     |
	| L     | recipehandler                        | 0.13                        | NoMoreRecipeConflict-0.13(1.12.2).jar                 | None                                     |
	| L     | norecipebook                         | 1.2.1                       | noRecipeBook_v1.2.2formc1.12.2.jar                    | None                                     |
	| L     | neid                                 | 1.5.4.4                     | NotEnoughIDs-1.5.4.4.jar                              | None                                     |
	| L     | opencomputers                        | 1.7.5.192                   | OpenComputers-MC1.12.2-1.7.5.192.jar                  | None                                     |
	| L     | omlib                                | 3.1.5-256                   | omlib-1.12.2-3.1.5-256.jar                            | None                                     |
	| L     | openmods                             | 0.12.2                      | OpenModsLib-1.12.2-0.12.2.jar                         | None                                     |
	| L     | openblocks                           | 1.8.1                       | OpenBlocks-1.12.2-1.8.1.jar                           | None                                     |
	| L     | openmodularturrets                   | 3.1.14-382                  | openmodularturrets-1.12.2-3.1.14-382.jar              | None                                     |
	| L     | oreexcavation                        | 1.4.150                     | OreExcavation-1.4.150.jar                             | None                                     |
	| L     | overpoweredarmorbar                  | @VERSION@                   | overloadedarmorbar-1.0.4g.jar                         | None                                     |
	| L     | particleculling                      | v1.3                        | particleculling-1.12.2-v1.3.1.jar                     | None                                     |
	| L     | patchouli                            | 1.0-23.6                    | Patchouli-1.0-23.6.jar                                | None                                     |
	| L     | pitweaks                             | 1.12-1.1.1                  | PiTweaks-1.12-1.1.1.jar                               | None                                     |
	| L     | portablecrafting                     | @VERSION@                   | PortableCrafting-1.12.2-1.0.2.jar                     | None                                     |
	| L     | portalgun                            | 7.1.0                       | PortalGun-1.12.2-7.1.0.jar                            | None                                     |
	| L     | potatooscustomstructureforhbm        | 1.0.0                       | Potatoo's HBM Structures_1.12.2-1.0.3.jar             | None                                     |
	| L     | potionfingers                        | r1.0-8                      | PotionFingers-r1.0-8.jar                              | None                                     |
	| L     | prefab                               | 1.3.1.5                     | prefab-1.3.1.5.jar                                    | None                                     |
	| L     | progressiveautomation                | 1.7.8                       | ProgressiveAutomation-1.12.2-1.7.8.jar                | None                                     |
	| L     | progressivebosses                    | 1.5.4                       | ProgressiveBosses-1.5.4-mc1.12.x.jar                  | None                                     |
	| L     | pvj                                  | 1.6.4                       | ProjectVibrantJourneys-1.12.2-1.6.4.jar               | None                                     |
	| L     | qualitytools                         | 1.0.7_for_1.12.2            | QualityTools-1.0.7_for_1.12.2.jar                     | None                                     |
	| L     | randomloot                           | 1.7.5                       | randomloot-1.12.2-1.7.5.jar                           | None                                     |
	| L     | randomtweaks                         | 1.12.2-2.8.3.1              | randomtweaks-1.12.2-2.8.3.1.jar                       | None                                     |
	| L     | rats                                 | 3.2.14                      | rats-3.2.14-1.12.2.jar                                | None                                     |
	| L     | reauth                               | 4.0.3                       | ReAuth-1.12-Forge-4.0.3.jar                           | None                                     |
	| L     | xreliquary                           | 1.12.2-1.3.4.796            | Reliquary-1.12.2-1.3.4.796.jar                        | None                                     |
	| L     | resourceloader                       | 1.5.3                       | ResourceLoader-MC1.12.1-1.5.3.jar                     | None                                     |
	| L     | additionalstructures                 | 2.3.1                       | Rex's-Additional-Structures-1.12.x-(v.2.3.1).jar      | None                                     |
	| L     | roguelike                            | 2.4.0                       | RoguelikeDungeonsFnarEdition-1.12.2-2.4.0.jar         | None                                     |
	| L     | roughtweaks                          | 1.0                         | roughTweaks0.2.4-1.12.2.jar                           | None                                     |
	| L     | rustic                               | 1.1.7                       | rustic-1.1.7.jar                                      | None                                     |
	| L     | silentlib                            | 3.0.13                      | SilentLib-1.12.2-3.0.14+168.jar                       | None                                     |
	| L     | scalinghealth                        | 1.3.37                      | ScalingHealth-1.12.2-1.3.42+147.jar                   | None                                     |
	| L     | sharetome                            | 1.0                         | sharetome-1.0.jar                                     | None                                     |
	| L     | valkyrielib                          | 1.12.2-2.0.20.1             | valkyrielib-1.12.2-2.0.20.1.jar                       | None                                     |
	| L     | simplegenerators                     | 1.12.2-2.0.20.2             | simplegenerators-1.12.2-2.0.20.2.jar                  | None                                     |
	| L     | storagenetwork                       | 1.8.3                       | SimpleStorageNetwork-1.12.2-1.8.3.jar                 | None                                     |
	| L     | snad                                 | 1.12.1-1.7.09.16a           | Snad-1.12.1-1.7.09.16a.jar                            | None                                     |
	| L     | soot                                 | 1.10-hotfix                 | Soot-1.10-hotfix.jar                                  | None                                     |
	| L     | spartanweaponry                      | 1.4.1                       | SpartanWeaponry-1.12.2-1.4.1.jar                      | None                                     |
	| L     | spartanfire                          | 0.08                        | spartanfire-0.08.jar                                  | None                                     |
	| L     | spartanshields                       | 1.5.5                       | SpartanShields-1.12.2-1.5.5.jar                       | None                                     |
	| L     | spawnercontrol                       | 1.6.3b                      | SpawnerControl-1.6.3b.jar                             | None                                     |
	| L     | stackie                              | 1.6.0.48                    | Stackie-1.12.2-1.6.0.48-universal.jar                 | None                                     |
	| L     | storagedrawers                       | 5.2.2                       | StorageDrawers-1.12.2-5.4.2.jar                       | None                                     |
	| L     | strawgolem                           | 1.3                         | strawgolem-1.4.1.jar                                  | None                                     |
	| L     | sasit                                | 1.1.30                      | StuffASockInIt-1.12.2-1.1.30.jar                      | None                                     |
	| L     | switchbow                            | 1.6.8                       | switchbow-1.6.8.jar                                   | None                                     |
	| L     | techguns                             | 2.0.2.0                     | techguns-1.12.2-2.0.2.0_pre3.2.jar                    | None                                     |
	| L     | thaumicaugmentation                  | 1.12.2-2.1.3                | ThaumicAugmentation-1.12.2-2.1.3.jar                  | None                                     |
	| L     | tcinventoryscan                      | 2.0.10                      | ThaumicInventoryScanning_1.12.2-2.0.10.jar            | None                                     |
	| L     | thaumicjei                           | 1.6.0                       | ThaumicJEI-1.12.2-1.6.0-27.jar                        | None                                     |
	| L     | tinkersjei                           | 1.2                         | tinkersjei-1.2.jar                                    | None                                     |
	| L     | tinkertoolleveling                   | 1.12.2-1.1.0.DEV.b23e769    | TinkerToolLeveling-1.12.2-1.1.0.jar                   | None                                     |
	| L     | tips                                 | 1.0.9                       | Tips-1.12.2-1.0.9.jar                                 | None                                     |
	| L     | titles                               | 3.1.6                       | Titles-1.12.2-3.1.7.jar                               | None                                     |
	| L     | tombmanygraves                       | 1.12-4.2.0                  | TombManyGraves-1.12-4.2.0.jar                         | None                                     |
	| L     | tombmanygraves2api                   | 1.12.2-1.0.0                | tombmanygraves2api-1.12.2-1.0.0.jar                   | None                                     |
	| L     | tombmanypluginscosmeticarmorreworked | 1.0.0                       | tombmanypluginscosmeticarmorreworked-1.0.0.jar        | None                                     |
	| L     | tombmanypluginsinventorypets         | 1.0.0                       | tombmanypluginsinventorypets-1.0.0.jar                | None                                     |
	| L     | tombmanypluginstechguns              | @VERSION@                   | tombmanypluginstechguns-1.0.0.jar                     | None                                     |
	| L     | translocators                        | 2.5.2.81                    | Translocators-1.12.2-2.5.2.81-universal.jar           | None                                     |
	| L     | travelersbackpack                    | 1.0.35                      | TravelersBackpack-1.12.2-1.0.35.jar                   | None                                     |
	| L     | treasure2                            | 2.1.0                       | Treasure2-mc1.12.2-f14.23.5.2859-v2.1.0.jar           | None                                     |
	| L     | tropicraft                           | 7.1.9.115                   | tropicraft-MC1.12.2-7.1.9.115.jar                     | None                                     |
	| L     | ts2k16                               | 1.2.10                      | TS2K16-1.2.10.jar                                     | None                                     |
	| L     | uniquee                              | 1.9.0                       | Unique Enchantments-1.12.2-2.0.1.jar                  | None                                     |
	| L     | uniquecrops                          | 0.2.6                       | uniquecrops-1.12.2-0.2.6.jar                          | None                                     |
	| L     | uppers                               | 0.0.6                       | Uppers-0.0.6.jar                                      | None                                     |
	| L     | universalmodifiers                   | 1.12.2-1.0.16.1             | valkyrielib-1.12.2-2.0.20.1.jar                       | None                                     |
	| L     | vc                                   | 5.9.16                      | ViesCraft-1.12.2-5.9.16.jar                           | None                                     |
	| L     | vtweaks                              | 2.0.8                       | VTweaks-1.12.2-2.0.8.jar                              | None                                     |
	| L     | wailaharvestability                  | 1.1.12                      | WailaHarvestability-mc1.12-1.1.12.jar                 | None                                     |
	| L     | waterstrainer                        | 3.3.0                       | WaterStrainer-1.12-3.3.0.jar                          | None                                     |
	| L     | wawla                                | 2.6.275                     | Wawla-1.12.2-2.6.275.jar                              | None                                     |
	| L     | waystones                            | 4.1.0                       | Waystones_1.12.2-4.1.0.jar                            | None                                     |
	| L     | wolfarmor                            | 3.8.0                       | WolfArmorAndStorage-1.12.2-3.8.0-universal-signed.jar | None                                     |
	| L     | wopper                               | 1.12-r5                     | Wopper-1.12-r5.jar                                    | None                                     |
	| L     | worldedit                            | 6.1.10                      | worldedit-forge-mc1.12.2-6.1.10-dist.jar              | None                                     |
	| L     | xpbook                               | v2.0.1                      | xptome-1.12.2-v2.0.1.jar                              | None                                     |
	| L     | yoyos                                | 1.12.2-1.3.3.25             | yoyos_1.12.2-1.3.3.25.jar                             | None                                     |
	| L     | pumpkinlauncher                      | 1.12.2-1.7.0                | Jack-O'-Launcher-1.12.2-1.7.0.jar                     | None                                     |
	| L     | orelib                               | 3.6.0.1                     | OreLib-1.12.2-3.6.0.1.jar                             | None                                     |
	| L     | phosphor-lighting                    | 1.12.2-0.2.6                | phosphor-1.12.2-0.2.6+build50-universal.jar           | None                                     |
	| L     | ropebridge                           | 2.0.5                       | RopeBridge-1.12.2-2.2.1.jar                           | None                                     |
	| L     | solcarrot                            | 1.8.4                       | solcarrot-1.12.2-1.8.4.jar                            | None                                     |
	| L     | thebetweenlands                      | 3.7.3                       | TheBetweenlands-3.7.3-universal.jar                   | None                                     |
	| L     | vt                                   | 1.12.2-1.5.6                | VanillaTweaks-1.12.2-1.5.6.jar                        | None                                     |
	| L     | mysticallib                          | 1.12.2-1.10.0               | mysticallib-1.12.2-1.10.0.jar                         | None                                     |

	Loaded coremods (and transformers): 
WolfArmorCore (WolfArmorAndStorage-1.12.2-3.8.0-universal-signed.jar)
  
TransformerLoader (OpenComputers-MC1.12.2-1.7.5.192.jar)
  li.cil.oc.common.asm.ClassTransformer
ParticleCullingLoadingPlugin (particleculling-1.12.2-v1.3.1.jar)
  
Thaumic Augmentation Core Plugin (ThaumicAugmentation-1.12.2-2.1.3.jar)
  thecodex6824.thaumicaugmentation.core.TATransformer
CXLibraryCore (cxlibrary-1.12.1-1.6.1.jar)
  cubex2.cxlibrary.CoreModTransformer
Quark Plugin (Quark-r1.6-179.jar)
  vazkii.quark.base.asm.ClassTransformer
AppleCore (AppleCore-mc1.12.2-3.4.0.jar)
  squeek.applecore.asm.TransformerModuleHandler
SecurityCraftLoadingPlugin ([1.12.2] SecurityCraft v1.9.2.jar)
  
iceandfire (iceandfire-1.9.1-1.12.2.jar)
  com.github.alexthe666.iceandfire.patcher.IceAndFireRuntimePatcher
EntityCullingPlugin (EntityCulling-1.12.2-4.1.5.jar)
  meldexun.entityculling.plugin.EntityCullingTransformer
Inventory Tweaks Coremod (InventoryTweaks-1.63.jar)
  invtweaks.forge.asm.ContainerTransformer
HMBFixesCoremod (HMBFixes-1.12.2-12.1.0.jar)
  org.zeith.zhbmfixes.asm.HMBFixesCoremod
PhosphorFMLLoadingPlugin (phosphor-1.12.2-0.2.6+build50-universal.jar)
  
ratscore (rats-3.2.14-1.12.2.jar)
  com.github.alexthe666.rats.server.misc.RatsRuntimePatcher
LevelUpCore (levelup2-1.5.8.jar)
  
LoadingPlugin (ResourceLoader-MC1.12.1-1.5.3.jar)
  lumien.resourceloader.asm.ClassTransformer
Techguns Core (techguns-1.12.2-2.0.2.0_pre3.2.jar)
  techguns.core.TechgunsASMTransformer
MalisisCorePlugin (malisiscore-1.12.2-6.5.1.jar)
  
weaponlib (mw_2.0-0.4.4.6_mc1.12.2.jar)
  com.vicmatskiv.weaponlib.core.WeaponlibClassTransformer
CoreMod (Aroma1997Core-1.12.2-2.0.0.2.jar)
  
RandomPatches (randompatches-1.12.2-1.22.1.10.jar)
  com.therandomlabs.randompatches.core.RPTransformer
ForgelinPlugin (Forgelin-1.8.4.jar)
  
Do not report to Forge! (If you haven't disabled the FoamFix coremod, try disabling it in the config! Note that this bit of text will still appear.) (foamfix-0.10.14-1.12.2.jar)
  pl.asie.foamfix.coremod.FoamFixTransformer
OpenModsCorePlugin (OpenModsLib-1.12.2-0.12.2.jar)
  openmods.core.OpenModsClassTransformer
ApotheosisCore (Apotheosis-1.12.2-1.12.5.jar)
  shadows.ApotheosisTransformer
CTMCorePlugin (CTM-MC1.12.2-1.0.2.31.jar)
  team.chisel.ctm.client.asm.CTMTransformer
SuperMartijn642's Core Lib Plugin (supermartijn642corelib-1.0.18-forge-mc1.12.jar)
  
CharmLoadingPlugin (Charm-1.12.2-1.4.1.jar)
  svenhjol.charm.base.CharmClassTransformer
Plugin (NotEnoughIDs-1.5.4.4.jar)
  ru.fewizz.neid.asm.Transformer
llibrary (llibrary-core-1.0.11-1.12.2.jar)
  net.ilexiconn.llibrary.server.core.plugin.LLibraryTransformer
  net.ilexiconn.llibrary.server.core.patcher.LLibraryRuntimePatcher
CoreMod (ForgeMixinFix-1.0.0.jar)
  
CorePlugin (ForgeEndertech-1.12.2-4.5.6.0-build.0619.jar)
  
JustEnoughIDs Extension Plugin (JustEnoughIDs-1.0.3-48.jar)
  org.dimdev.jeid.JEIDTransformer
HCASM (HammerLib-1.12.2-2.0.6.32.jar)
  com.zeitheron.hammercore.asm.HammerCoreTransformer
TheBetweenlandsLoadingPlugin (TheBetweenlands-3.7.3-SNAPSHOT-20210322.102210-core.jar)
  thebetweenlands.core.TheBetweenlandsClassTransformer
SpartanWeaponry-MixinLoader (SpartanWeaponry-1.12.2-1.4.1.jar)
  
BiggerPacketsPlzCoreMod (biggerpacketsplz-since1.8-1.2.jar)
  net.elnounch.mc.biggerpacketsplz.BiggerPacketsPlzClassTransformer
	GL info: ' Vendor: 'NVIDIA Corporation' Version: '4.6.0 NVIDIA 511.65' Renderer: 'NVIDIA GeForce RTX 2070 with Max-Q Design/PCIe/SSE2'
	Launched Version: forge-14.23.5.2858
	LWJGL: 2.9.4
	OpenGL: NVIDIA GeForce RTX 2070 with Max-Q Design/PCIe/SSE2 GL version 4.6.0 NVIDIA 511.65, NVIDIA Corporation
	GL Caps: Using GL 1.3 multitexturing.
Using GL 1.3 texture combiners.
Using framebuffer objects because OpenGL 3.0 is supported and separate blending is supported.
Shaders are available because OpenGL 2.1 is supported.
VBOs are available because OpenGL 1.5 is supported.

	Using VBOs: Yes
	Is Modded: Definitely; Client brand changed to 'fml,forge'
	Type: Client (map_client.txt)
	Resource Packs: 
	Current Language: English (US)
	Profiler Position: N/A (disabled)
	CPU: 12x Intel(R) Core(TM) i7-10750H CPU @ 2.60GHz
	OptiFine Version: OptiFine_1.12.2_HD_U_G5
	OptiFine Build: 20210124-142939
	Render Distance Chunks: 8
	Mipmaps: 0
	Anisotropic Filtering: 1
	Antialiasing: 0
	Multitexture: false
	Shaders: null
	OpenGlVersion: 4.6.0 NVIDIA 511.65
	OpenGlRenderer: NVIDIA GeForce RTX 2070 with Max-Q Design/PCIe/SSE2
	OpenGlVendor: NVIDIA Corporation
	CpuCount: 12