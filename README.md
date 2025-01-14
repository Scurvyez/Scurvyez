```cs
public class Steve 
{
    public string Name { get; set; } = "Steve";
    public string Pronouns { get; set; } = "He / Him";
    public string Occupation { get; set; } = "Hobbyist programmer by night, wildlife ecologist/biologist by day";
    public string Discord { get; set; } = "steveo.o";
    public Dictionary<string, string> LikesDislikes { get; set; } = new Dictionary<string, string>
    {
        { "Likes", "Programming, wildlife, shaders, black coffee, climbing, synthwave, nice people" },
        { "Dislikes", "Bugs in code, environmental degradation, movies with bad endings" }
    };
}
```

⭕ Demo of "Solar Systems". The project mentioned below.<br>
<img src="https://github.com/Scurvyez/Scurvyez/blob/main/SolarSystems_Gif_1.gif" width="720" height="432">

### Personal Projects

```cs
public class UnityShenanigans
{
    public static void Main()
    {
        List<UnityProject> projects = new 
        [
            new UnityProject("Solar Systems")
                .AddDescription(
                    "A realistic yet random solar system generator.",
                    "Based on real-world math and current scientific knowledge of the universe."),

            new UnityProject("Panic Squares")
                .AddDescription(
                    "Originally written in C#, reworked in GDScript.",
                    "You control a square with a tail.",  
                    "Collect other squares and various short-lived abilities while avoiding walls and enemies.",
                    "Do it all before the timer runs out or all lives are lost.")
        ];
    }
}
```

### Rimworld Modding

```cs
public class RimworldModding
{
    public static void Main()
    {
        List<RimworldMod> mods = new 
        [
            new RimworldMod("Random Chance")
                .AddDescription(
                    "Adds many new events and or situations which occur randomly based on certain factors",
                    "If you ever felt like the game needed to be more difficult with complete randomness then this mod is for you!"),

            new RimworldMod("Fabled Cervidae")
                .AddDescription(
                    "Adds 4 new fantasy-based cervid (deer) species to the game.",
                    "Each comes with its own unique abilities and graphics.",
                    "I'm a biologist by trade so yeah, I made some awesome animals and there are more in the works."),

            new RimworldMod("Steve's Walls")
                .AddDescription(
                    "Introduces new powered walls with customizable glowing colors.",
                    "Alert walls pulse with configurable colors to warn the colony of nearby dangers."),

            new RimworldMod("Fireflies 2")
                .AddDescription(
                    "A total rewrite of my original Fireflies mod.",
                    "This version utilizes Unity's ParticleSystem for much better performance instead of making each firefly an actual pawn.",
                    "Now they are just beautiful little visual effects.",
                    "My proudest mod thus far."),

            new RimworldMod("Bones")
                .AddDescription(
                    "Enhances pawns by adding all 206 human bones with various fracture hediffs.",
                    "Birthed out of a bet in the Official Rimworld Discord server on one gloomy Friday evening. :)"),
        ];
    }
}
```

## Help me fuel my late-night coding sessions. ☕ Support is never asked for but it goes a long way in making sure anything I produce stays up-to-date!
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/B0B84LOQ1)
