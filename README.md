A bunch of patches handpicked from both Valve's [linux-neptune](https://gitlab.com/evlaV/linux-integration) and upstreamed stuff for 6.0 for use with 5.19.* kernels.

Necessary for the fan control daemon, sound and a bunch of other things to work.

For the fan control daemon to work you also have to set `fan_hwmon_name` to `steamdeck` in `/usr/share/jupiter-fan-control/jupiter-fan-control-config.yaml`.

See https://wiki.archlinux.org/title/Steam_Deck and https://wiki.archlinux.org/title/User:Pongo1231/Arch_on_Steam_Deck for some info on setting up Arch on the Steam Deck.

NOTE: I would not recommend jumping to the 6.0 kernel yet, as waking up the Deck from suspension will cause an unrecoverable GPU reset (see [this bug](https://gitlab.freedesktop.org/drm/amd/-/issues/2164)).
