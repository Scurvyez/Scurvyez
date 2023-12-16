```cs
public class Steve 
{
    public string Name { get; set; } = "Steve";
    public string Pronouns { get; set; } = "He / Him";
    public string Occupation { get; set; } = "Hobbyist programmer by night, wildlife ecologist by day";
    public string Discord { get; set; } = "steveo.o";
    public Dictionary<string, string> LikesDislikes { get; set; } = new Dictionary<string, string>
    {
        { "Likes", "Programming, wildlife, shaders, black coffee, climbing, synthwave, nice people" },
        { "Dislikes", "Bugs in code, environmental degradation, movies with bad endings" }
    };
}
```

Example ghost effect shader for a WIP Rimworld mod, written in HLSL.<br>
<img src="https://github.com/Scurvyez/Scurvyez/blob/main/Animation65.gif" width="300" height="300">

## Projects I'm currently working on

```cs
public class RimworldModding
{
    public static void Main()
    {
        List<RimworldMod> mods = new List<RimworldMod>
        {
            new RimworldMod("Pixel Wizardry")
                .AddDescription(
                    "Adds accessibility support for persons with color blindness.",
                    "Adds several new shaders for Rimworld textures with blending effects."),

            new RimworldMod("Random Chance")
                .AddDescription(
                    "Adds many new events and or situations which occur randomly based on certain factors"),

            new RimworldMod("Steve's Animals (formerly Bastyon)")
                .AddDescription(
                    "Adds new animals with varied abilities and events.",
                    "New pawn graphics system with animated textures."),

            new RimworldMod("Steve's Walls")
                .AddDescription(
                    "Introduces new powered walls with customizable glowing colors.")

            new RimworldMod("Fireflies")
                .AddDescription(
                    "Adds glowing fireflies that spawn in groups at night.",
                    "Performance improvements in progress (possibly a whole rewrite)."),

            new RimworldMod("Bones")
                .AddDescription(
                    "Enhances pawns by adding all 206 human bones with fracture hediffs.",
                    "Birthed out of a bet in the Official Rimworld Discord server. :)"),

            new RimworldMod("Medieval Overhaul")
                .AddDescription(
                    "Contributed code for RPG-style lootable buildings on various items.")
        };
    }
}
```

### Rimworld Mods
- **Pixel Wizardry**
    - This mod adds accessability support for persons with color blindness. (Protanopia, Protanomaly, Deuteranopia, Deuteranomaly, Tritanopia, Tritanomaly, Achromatopsia, and Achromatomaly). You must enable the correct options for any of these in the mods' settings to work.
    - This mod also adds several new shaders for use with Rimworld textures by other modders. Some of the shaders produce blending effects similar to those found in programs like Photoshop.
- **Steve's Animals** (formerly Bastyon)
    - Adds a variety of new animals to the game with varied abilities and events.
    - Includes an advanced pawn graphics system with animated textures, like actual fire and ethereal effects.
- **Steve's Walls**
    - Introduces new powered walls to the game, with customizable glowing colors.
- **Fireflies**
    - Adds glowing fireflies that spawn in small to large groups at night. (Performance improvements in progress)
- **Bones**
    - Enhances pawns in the game by adding all 206 human bones with fracture hediffs.
    - This mod was birthed out of a bet in the glorious Official Rimworld Discord server.
- **Medieval Overhaul**
    - Contributed code for RPG-style lootable buildings on various items.

### Personal Projects
- **Solar Systems**
    - A Unity project that generates realistic yet random solar systems.

## Help me fuel my late-night coding sessions ☕

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/B0B84LOQ1)
