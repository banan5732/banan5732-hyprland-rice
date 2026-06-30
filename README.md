

https://github.com/user-attachments/assets/2f963741-bb94-40b3-a3a7-fa0a33fabe0b

# ⚠️WARNING THESE DOTS ARE NOT INSTALLABLE, THIS IS JUST SHOWCASE
# If you want old hyprland animations, copy my animations config


<video src="[/home/stas/Hyprland Rice showcase.mp4](https://github.com/user-attachments/assets/2f963741-bb94-40b3-a3a7-fa0a33fabe0b)" width="320" height="240" controls></video>

My first hyprland rice using noctalia shell for panel instead of waybar

## Apps i use

| App        | Program   |
|------------|-----------|
| Browser    | Helium  |
| Terminal   | Ghostty   |
| Panel      | Quickshell|
| Launcher   | Fuzzel    |
| File mgr   | Thunar    |
| Emoji picker | Fuzzel-emoji |

# old hyrpland animations config + scroll down for launcher
```
hl.curve("easeOutQuint", { type = "bezier", points = { { 0.23, 1 }, { 0.32, 1 } } })
hl.curve("easeInOutCubic", { type = "bezier", points = { { 0.65, 0.05 }, { 0.36, 1 } } })
hl.curve("linear", { type = "bezier", points = { { 0, 0 }, { 1, 1 } } })
hl.curve("almostLinear", { type = "bezier", points = { { 0.5, 0.5 }, { 0.75, 1 } } })
hl.curve("quick", { type = "bezier", points = { { 0.15, 0 }, { 0.1, 1 } } })
hl.curve("overshot", { type = "bezier", points = { { 0.05, 0.9 }, { 0.1, 1.05 } } })
hl.curve("smoothOut", { type = "bezier", points = { { 0.36, 0 }, { 0.66, -0.56 } } })
hl.curve("wind", { type = "bezier", points = { { 0.05, 0.9 }, { 0.1, 1.05 } } })
hl.curve("winIn", { type = "bezier", points = { { 0.1, 1.1 }, { 0.1, 1.1 } } })
hl.curve("winOut", { type = "bezier", points = { { 0.3, -0.3 }, { 0, 1 } } })
hl.curve("backOut", { type = "bezier", points = { { 0.175, 0.885 }, { 0.32, 1.275 } } })
-- Default springs
hl.curve("easy", { type = "spring", mass = 1, stiffness = 71.2633, dampening = 15.8273644 })

hl.animation({ leaf = "global", enabled = true, speed = 5, bezier = "wind" })
hl.animation({ leaf = "border", enabled = true, speed = 5.39, bezier = "easeOutQuint" })
hl.animation({ leaf = "windows", enabled = true, speed = 4.79, spring = "easy" })
hl.animation({ leaf = "windowsIn", enabled = true, speed = 6, spring = "easy", beizer = "winIn", style = "popin 80%" })
hl.animation({ leaf = "windowsOut", enabled = true, speed = 6, bezier = "winOut", style = "popin 80%" })
hl.animation({ leaf = "fadeIn", enabled = true, speed = 1.73, bezier = "almostLinear" })
hl.animation({ leaf = "fadeOut", enabled = true, speed = 1.46, bezier = "almostLinear" })
hl.animation({ leaf = "fade", enabled = true, speed = 3.03, bezier = "quick" })
hl.animation({ leaf = "layers", enabled = true, speed = 3.81, bezier = "wind" })
hl.animation({ leaf = "layersIn", enabled = true, speed = 4, bezier = "backOut", style = "silde bottom" })
hl.animation({ leaf = "layersOut", enabled = true, speed = 4, bezier = "winOut", style = "slide" })
hl.animation({ leaf = "fadeLayersIn", enabled = true, speed = 1.79, bezier = "linear" })
hl.animation({ leaf = "fadeLayersOut", enabled = true, speed = 1.39, bezier = "linear" })
hl.animation({ leaf = "workspaces", enabled = true, speed = 5, bezier = "overshot", style = "slide" })
hl.animation({ leaf = "workspacesIn", enabled = true, speed = 5, bezier = "overshot", style = "slide" })
hl.animation({ leaf = "workspacesOut", enabled = true, speed = 5, bezier = "overshot", style = "slide" })
hl.animation({ leaf = "zoomFactor", enabled = true, speed = 7, bezier = "quick" })

```

## Star History
<a href="https://www.star-history.com/?repos=banan5732%2Fbanan5732-hyprland-rice&type=date&legend=top-left">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=banan5732/banan5732-hyprland-rice&type=date&theme=dark&legend=top-left" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=banan5732/banan5732-hyprland-rice&type=date&legend=top-left" />
   <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=banan5732/banan5732-hyprland-rice&type=date&legend=top-left" />
 </picture>
</a>

leave a star plz


i also changed my distro yesterday to NixOS (June 28 2026) but im tooo lazy to update the video in repo, just i case, everything works the same
i use NixOS btw <--- (UPDATE) NixOS is TRASH, i went back to EndeavourOS (best distro) after 3 days, i consider that as skill issue
