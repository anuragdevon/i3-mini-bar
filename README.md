
# i3-mini-bar
A simple, fast and  minimalist i3-status bar

## How to set it up
- Clone this repo to XDG_CONFIG_HOME `git clone git@github.com:anuragdevon/i3-mini-bar.git ~/.config/`
- Move to directory, `cd ~/.config/i3-mini-bar/mybar/`
- Make the files executable using `chmod +x *.sh`
- Open i3 config, `vim ~/.config/i3/config` (Free to use any editor of choice)
- Add this to i3 config in the `bar` section, `status_command exec ~/.config/i3-mini-bar/mybar/mybar.sh`.

    ### Dependencies
    - Option 1(Install the given dependiencies manually):
        - sysstat
        - netstat
        - acpi
        - pamixer
    - Option 2(Install using script provided in repo):
        - Move to directory using `cd ~/.config/i3-mini-bar/`  
        - run the dependencies using `chmod +x dependencies` and `./dependencies`

    - Finally restart i3 using `$mod1/4+shift+r` (default)
    - Boom! your status-bar should be ready.

## Examples
![IMG-1](./images/1.png?raw=true "LABEL-1")
![IMG-2](./images/2.png?raw=true "LABEL-2")
![IMG-3](./images/3.png?raw=true "LABEL-3")

## How to contribute
- Open contributions are welcome :)

### License
[MIT LICENCE]
        
