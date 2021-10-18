# i3lock-blur

Sets the background of i3lock to a blurred image of the current workspace.

## Dependencies:
- `scrot`: https://man.cx/scrot
- `convert`: https://linux.die.net/man/1/imagemagick
- `i3lock`: https://github.com/i3/i3lock

## Installation
1. Copy `lock` to your machine;
2. Make it executable (`chmod +x /path/to/lock`);
3. Create a bind to run the script, e.g.: `bindsym $mod+Shift+X exec /home/carlos/.config/i3/lock` 
