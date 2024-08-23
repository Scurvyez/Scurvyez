[![Steve's GitHub stats](https://github-readme-stats.vercel.app/api?username=Scurvyez&theme=synthwave)](https://github.com/anuraghazra/github-readme-stats)     [![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Scurvyez&theme=synthwave&layout=compact)](https://github.com/anuraghazra/github-readme-stats)<br>

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

⭕ Example shader written in HLSL. My, somewhat decent, attempt at Diablo's health guage.<br>
<img src="https://github.com/Scurvyez/Scurvyez/blob/main/Animation71.gif" width="300" height="300">

### Rimworld Modding

```cs
public class RimworldModding
{
    public static void Main()
    {
        List<RimworldMod> mods = new List<RimworldMod>
        {
            new RimworldMod("Color Blindness")
                .AddDescription(
                    "Adds accessibility support for persons with color blindness.")

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

### Personal Projects

```cs
public class UnityShenanigans
{
    public static void Main()
    {
        List<UnityProject> projects = new List<UnityProject>
        {
            new UnityProject("Solar Systems")
                .AddDescription(
                    "A realistic yet random solar system generator.",
                    "Based on real-world math and current scientific knowledge of the universe."),

            new UnityProject("Panic Squares")
                .AddDescription(
                    "You control a square with a tail. Collect other squares while avoiding various objects and collecting short-lived abilities before the timer runs out and all lives are lost.")
        };
    }
}
```

## Help me fuel my late-night coding sessions ☕
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/B0B84LOQ1)
