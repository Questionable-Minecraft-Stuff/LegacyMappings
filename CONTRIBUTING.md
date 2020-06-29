# Contribution Guidelines

If you're planning on *actually* helping, follow these instructions 

1. Download the latest version of enigma and stitch.
2. Then download the 1.7.10 client and server jars.
3. Then merge the two jars using Stitch.
4. Then open enigma and import the **merged** jar and the **intermediary** mappings
5. Export a jar file mapped with the intermediary names
6. Then re-open enigma and import the **intermediary** jar and the **mapped** mappings
7. Start making mappings!

**Note: Using names from MCP or Mojang mappings is strictly forbidden! I like to have a clean environment and I don't want this project to get tainted by legal poison.**

### Naming Conventions
1. Static fields and Enum constants must be in `UPPERCASE`
2. Non static fields must be in `camelCase` with the first letter in lowercase
3. Class names must always be in `CamelCase`
4. Abstract classes should have the `Abstract` prefix
5. Interfaces should be suffixed with `Provider` or `Access`
6. Classes having a single, obvious purpose should be suffixed with what they are. E.g.: `CreeperEntity`, `CreeperModel`, `CreeperRenderer`

### Other stuff
1. Preferably, sign your commits becuase it looks cool
2. Commits that include mapping name changes should inlude *every single changed file* in the commit message. Here's an example -> https://github.com/Useless-Minecraft-Stuff/LegacyMappings/commit/2ab3930898e4bc90a733e0d6e034978c35f5d354
