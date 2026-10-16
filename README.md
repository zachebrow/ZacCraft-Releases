# ZacCraft Releases

Official game builds for [ZacCraft](https://github.com/zachebrow/ZacCraft-Releases).

## Players

1. Install **Java 17+**.
2. Download `ZacCraft.jar` from [Releases](https://github.com/zachebrow/ZacCraft-Releases/releases).
3. Run:

```text
java -jar ZacCraft.jar
```

The first run creates `textures`, `sounds`, `songs`, `blocks`, `entities`, `menus`, `modes`, `mods`, and `templates` next to the JAR. Add your own art and audio there. There are no bundled sample textures or songs.

## Maintainers

Copy a newly built JAR from the source project:

```powershell
.\build.ps1 -Release
```

Then upload it as a GitHub Release on this repository.
