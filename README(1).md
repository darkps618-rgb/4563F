# GaleDash

Client-side Fabric mod for Minecraft 26.3 (Java 25).

Hold a wind charge, then press left click:

- **Dash**: in the air while rising and not looking up. Swaps to the dash slot (or reuses the wind charge), uses it, swaps back.
- **Pearl catch**: while looking up. Swaps to an ender pearl in your hotbar, throws it, swaps back to the wind charge.

Settings are constants at the top of `src/client/java/gale/dash/client/GaleDashClient.java`.

Build: `./gradlew build` -> jar in `build/libs/`.

Many PvP servers ban automated swaps/uses. Use it only where it is allowed.

## License

CC0
