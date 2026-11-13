# SAGE Unlocked: BFME2 network fix (testing fork)

This is a fork of [TheeHorse/SAGE-Unlocked](https://github.com/TheeHorse/SAGE-Unlocked) for testing a fix for **Battle for Middle-earth II** and **Rise of the Witch-king** multiplayer. With the mod, units jump or "teleport" in LAN and online games ([upstream #20](https://github.com/TheeHorse/SAGE-Unlocked/issues/20)). For everything else, use the original project.

To try it:

1. Install the normal [SAGE Unlocked](https://github.com/TheeHorse/SAGE-Unlocked/releases) for your game.
2. Download `CnCFpsUnlocker.dll` from this fork's [Releases](../../releases) and copy it over the one in your game folder.
3. The fix is off by default. Add this line to `SAGEUnlocked.ini`:

```
netsync=1
```

It's untested. Please play a multiplayer game with it and send your `SAGEUnlocked.log` (next to the game exe) in an issue here, together with what you saw: did units still jump?

All credit for SAGE Unlocked goes to TheeHorse. GPL v3, see [LICENSE](LICENSE).
