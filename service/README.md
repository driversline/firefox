systemctl --user daemon-reload

systemctl --user start firefox.service

systemctl --user status firefox.service

find /nix/store -name firefox
