# Player Reach Display — Minecraft 26.3 Fabric Port

An unofficial community-maintained port of **Player Reach Display** for Minecraft **26.3 (Fabric)**.

## Original project and credits

This project is based on [Player Reach Display by KikiJiji](https://github.com/K1kiJiji/Player-Reach-Display).

- **Original creator:** [KikiJiji](https://github.com/K1kiJiji) — original idea, design, and mod implementation.
- **26.3 port and compatibility updates:** [BrokeAsHell](https://github.com/brokeashell68) — adaptation for Minecraft 26.3 Fabric and port testing.

I have great respect for KikiJiji's work. The original concept and mod are theirs; this repository contains compatibility work to make the mod run on Minecraft 26.3. The original author's public pull request for Minecraft 26.2 is [PR #17](https://github.com/K1kiJiji/Player-Reach-Display/pull/17). That PR is separate from this independently maintained 26.3 port. This is an **unofficial port** and is not presented as an official release by the original author.

## Compatibility

- Minecraft **26.3**
- Fabric Loader **0.20.1 or newer**
- Java **25 or newer**
- Fabric API for Minecraft 26.3
- Mod Menu is optional (used for the mod's configuration integration)

## Installation

1. Install a Minecraft 26.3 Fabric instance.
2. Make sure that Java 25 or newer is available to the launcher.
3. Install the Fabric API version for Minecraft 26.3.
4. Download the port JAR from the repository's Releases page.
5. Put the JAR in that instance's `mods` folder.
6. Launch the game with the Fabric profile.

Do not install this port alongside another copy of Player Reach Display in the same instance.

## Verification

The 26.3 port has:
- Built successfully using the repository's GitHub Actions build workflow.
- Been launched and tested in Minecraft 26.3 by the port maintainer, who reports that it works correctly in-game.

## Building from source

Requirements: Java 25 or newer.

On Windows:

```bat
gradlew.bat build
```

On Linux/macOS:

```bash
./gradlew build
```

The built JAR is produced in `build/libs/`.

## Changes

See [CHANGELOG.md](CHANGELOG.md) for the port-specific changes.

## License

This project retains the original **MIT License**. The original copyright and license notice are preserved in [LICENSE](LICENSE). When redistributing this software or substantial portions of it, include that notice.

## Links

- [Original project by KikiJiji](https://github.com/K1kiJiji/Player-Reach-Display)
- [Original Minecraft 26.2 update PR](https://github.com/K1kiJiji/Player-Reach-Display/pull/17)
- [26.3 port source](https://github.com/brokeashell68/Player-Reach-Display/tree/26.3-port)
- [Releases](https://github.com/brokeashell68/Player-Reach-Display/releases)
