# SAGE Unlocked: BFME2 network fix (testing fork)

This is a fork of [TheeHorse/SAGE-Unlocked](https://github.com/TheeHorse/SAGE-Unlocked) for testing a fix for **Battle for Middle-earth II** and **Rise of the Witch-king** multiplayer. With the mod, units jump or "teleport" in LAN and online games ([upstream #20](https://github.com/TheeHorse/SAGE-Unlocked/issues/20)). For everything else, use the original project.

To try it:

1. Download `SAGE-Unlocked-1.9.5-netsync-BFME2.zip` from this fork's [Releases](../../releases). It has the original SAGE Unlocked 1.9.5 `dinput8.dll`, this fork's `CnCFpsUnlocker.dll` and a `SAGEUnlocked.ini` with the fix turned on (`netsync=1`).
2. Copy the 3 files into your game folder, next to `game.dat`.
3. Start the game with `lotrbfme2.exe` / `lotrbfme2ep1.exe`. BFME Competitive Arena and the All In One Launcher disable these files, so for multiplayer play a LAN game over Radmin VPN or ZeroTier.

It's untested in multiplayer. Please play a multiplayer game with it and send every player's `SAGEUnlocked.log` (next to `game.dat`) in an issue here, together with what you saw: did units still jump?

All credit for SAGE Unlocked goes to TheeHorse. GPL v3, see [LICENSE](LICENSE).
