---- Minecraft Crash Report ----
// Who set us up the TNT?

Time: 13-8-27 20:57
Description: Exception in server tick loop

java.lang.NullPointerException
	at net.minecraft.server.v1_6_R2.DedicatedServer.ar(DedicatedServer.java:258)
	at net.minecraft.server.v1_6_R2.DedicatedServer.a(DedicatedServer.java:204)
	at net.minecraft.server.v1_6_R2.MinecraftServer.run(MinecraftServer.java:426)
	at net.minecraft.server.v1_6_R2.ThreadServerApplication.run(SourceFile:582)


A detailed walkthrough of the error, its code path and all known details is as follows:
---------------------------------------------------------------------------------------

-- System Details --
Details:
	Minecraft Version: 1.6.2
	Operating System: Windows 7 (x86) version 6.1
	Java Version: 1.6.0_39, Sun Microsystems Inc.
	Java VM Version: Java HotSpot(TM) Client VM (mixed mode), Sun Microsystems Inc.
	Memory: 13908048 bytes (13 MB) / 16252928 bytes (15 MB) up to 1037959168 bytes (989 MB)
	JVM Flags: 1 total; -Xmx1024M
	AABB Pool Size: 0 (0 bytes; 0 MB) allocated, 0 (0 bytes; 0 MB) used
	Suspicious classes: [net.minecraft.server.v1_6_R2.ICommandListener, IMojangStatistics, ICommandHandler, ...], [org.bukkit.BlockChangeDelegate, World, Server], [org.bukkit.block.BlockState], [org.bukkit.command.CommandSender, RemoteConsoleCommandSender], [org.bukkit.configuration.serialization.ConfigurationSerializable], [org.bukkit.craftbukkit.Main], [org.bukkit.craftbukkit.libs.jline.TerminalFactory, Terminal, Flavor, ...], [org.bukkit.craftbukkit.libs.jline.console.ConsoleReader, CursorBuffer, ConsoleKeys, ...], [org.bukkit.craftbukkit.libs.jline.console.completer.CompletionHandler, CandidateListCompletionHandler], [org.bukkit.craftbukkit.libs.jline.console.history.History, MemoryHistory], [org.bukkit.craftbukkit.libs.jline.internal.InputStreamReader, Configuration, Log], [org.bukkit.craftbukkit.v1_6_R2.LoggerOutputStream, CraftServer], [org.bukkit.craftbukkit.v1_6_R2.inventory.CraftItemStack, CraftRecipe, CraftShapedRecipe, ...], [org.bukkit.craftbukkit.v1_6_R2.potion.CraftPotionEffectType], [org.bukkit.craftbukkit.v1_6_R2.util.ServerShutdownThread, Waitable, TerminalConsoleHandler, ...], [org.bukkit.entity.Entity], [org.bukkit.event.Event, Cancellable, HandlerList, ...], [org.bukkit.event.block.BlockEvent, BlockFadeEvent, BlockGrowEvent, ...], [org.bukkit.event.entity.EntityEvent, EntityInteractEvent, EntityDamageEvent, ...], [org.bukkit.event.hanging.HangingEvent, HangingPlaceEvent], [org.bukkit.event.inventory.InventoryMoveItemEvent], [org.bukkit.event.painting.PaintingEvent, PaintingPlaceEvent], [org.bukkit.event.player.PlayerEvent, PlayerFishEvent], [org.bukkit.event.server.ServerEvent, MapInitializeEvent, ServerCommandEvent], [org.bukkit.event.world.WorldEvent, WorldInitEvent, WorldSaveEvent, ...], [org.bukkit.inventory.ItemStack, Inventory, Recipe, ...], [org.bukkit.map.MapView], [org.bukkit.metadata.Metadatable], [org.bukkit.permissions.ServerOperator, Permissible], [org.bukkit.plugin.messaging.PluginMessageRecipient], [org.bukkit.potion.PotionEffectType, PotionEffectTypeWrapper], [org.fusesource.hawtjni.runtime.Library], [org.fusesource.jansi.AnsiOutputStream, WindowsAnsiOutputStream, AnsiConsole, ...], [org.fusesource.jansi.internal.Kernel32, CONSOLE_SCREEN_BUFFER_INFO, COORD, ...]
	IntCache: cache: 0, tcache: 0, allocated: 0, tallocated: 0
	CraftBukkit Information: 
   Running: 
   Failed to handle CraftCrashReport:
java.lang.NullPointerException
	at org.bukkit.Bukkit.getName(Bukkit.java:72)
	at org.bukkit.craftbukkit.v1_6_R2.CraftCrashReport.call(CraftCrashReport.java:20)
	at net.minecraft.server.v1_6_R2.CrashReportSystemDetails.a(SourceFile:74)
	at net.minecraft.server.v1_6_R2.CrashReport.h(CrashReport.java:41)
	at net.minecraft.server.v1_6_R2.CrashReport.<init>(CrashReport.java:28)
	at net.minecraft.server.v1_6_R2.MinecraftServer.run(MinecraftServer.java:436)
	at net.minecraft.server.v1_6_R2.ThreadServerApplication.run(SourceFile:582)

	Profiler Position: N/A (disabled)
	Is Modded: Definitely; Server brand changed to 'craftbukkit'
	Type: Dedicated Server (map_server.txt)
