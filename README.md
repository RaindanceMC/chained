# RaindanceMC/chained

- **`chained-module`** — Rain's Flexible Modules — Chained: Two players, mechanically chained together — a speedrun challenge module: get too far apart and further separation is simply blocked, an arbitrary end condition (an advancement, a death, or manual) stops the clock, and the map can be reset with a fixed or a fresh random seed between attempts.
- **`chained-standalone`** — Rain's Chained: Rain's Chained, as a plugin of its own. Nothing here but a build file and a descriptor: the chained module and the standard wrapper are shaded together, and that is the whole plugin.

Part of [RaindanceMC](https://github.com/RaindanceMC); built on [RainsCore](https://github.com/RaindanceMC/RainsCore) and the shared parent in [framework](https://github.com/RaindanceMC/framework). Split out of `rains-flexible-modules` on 16.10.2026, history kept.

## Build

```
mvn install
```

Needs Java 25 and read access to `packages.tstieh.de` (server ids `packages-releases` / `packages-snapshots` in `~/.m2/settings.xml`).

## Plugins

- `chained-standalone/target/RainsChained-1.4.0.jar` — also published as `de.raindancer.modules:chained-standalone:1.4.0`

## Versions

A module's version is a property in this repository's root `pom.xml`, a plugin's is `plugin.version` in its own pom. CI publishes every version that is not in the registry yet on the next push to master.
