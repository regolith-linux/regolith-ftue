# regolith-ftue
Logic and assets for Regolith first-time user experience.
## Packaging guidelines
regolith-ftue is a shell script that should be installed somewhere into $PATH. regolith-init-term-profile is a helper script that will be called at /usr/share/regolith-ftue/regolith-init-term-profile exactly.
Dependencies: bash, glib, uuidgen (probably provided by a util-linux package in your distro), dconf, coreutils, and gnome-terminal. Regolith1.6 requires rofi, regolith2.0 will require ilia.
