# SP3-wifi-fix
A script for the Microsoft Surface Pro 3 that resets the wifi devices in the kernel after each team the device sleeps. The wifi does not work when waking from sleep in many linux distros, I have tested this on Pop OS! 19.04. Note: this may also work on SP4.

This is a personal backup of the script from a tutorial/forum thread I found online to fix the issue here https://www.reddit.com/r/SurfaceLinux/comments/8t7b8r/solved_wifi_issues_on_loading_from_sleep_ubuntu/?utm_source=share&utm_medium=web2x

This must be placed in /lib/systemmd/system-sleep/ and be made executable.
