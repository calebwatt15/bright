# bright
xbacklight alternative. Works in bash, not just while running xorg.

`USAGE: bright <backlight_brightness_percentage>`

Recommendations:

1. Place this file in /usr/local/bin (for addition to path, and allow all users to easily acccess it.)

2. Add the following to your /etc/sudoers:
`<username> ALL=NOPASSWD: /usr/local/bin/bright`
