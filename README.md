# Pwnagotchi Clock/Calendar

## Installation

To install, first set your directory for custom plugins in your config file.  
In `main` add `custom_plugins: "/custom/plugins/directory"`
(replace custom_plugins_directory with the directory of your custom plugins folder, for example, `/home/pi/plugins/`)

After that, add `clock.py` to that folder.
Finally, enable it in your config.yml.  

    plugins:
      clock:
         enabled: true

## FAQ

### The plugin doesn't work!

Bother me in my [discord server](https://discord.gg/VuhvYRz) (I am Logandev\_)

### Does it overlap memtemp?

If memtemp is enabled, it moves the clock over to the side, so it doesn't overlap memtemp.
