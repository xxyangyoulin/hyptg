# hyptg
 Hyprland smart window toggle script  
 Intelligently switch floating windows to prevent overlapping floats and return to the previous tiled window workflow

 ```sh
 yay -S hyptg-git
```

 ```sh
Usage:
  hyprtogglewindow.sh [options] <launch_cmd> [window_class]

Arguments:
  launch_cmd
      Command used to launch the application (required)

  window_class
      Hyprland window class
      Defaults to launch_cmd if not provided

Options:
  -c, --conflict <classes>
      Floating window classes that conflict with the target window
      Multiple classes separated by commas
      Only affects the current workspace

  -h, --help
      Show this help message and exit
```
