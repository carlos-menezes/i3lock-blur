# i3lock-blur

Sets the background of i3lock to a blurred version of the current workspace (on one monitor).

## Dependencies:
- `scrot`: https://man.cx/scrot
- `convert`: https://linux.die.net/man/1/imagemagick 

## Installation
1. Copy `lock` to your machine;
2. Make it executable (`chmod +x /path/to/lock`);
3. Create a bind to run the script, e.g.: `bindsym $mod+Shift+X exec /home/carlos/.config/i3/lock` 
