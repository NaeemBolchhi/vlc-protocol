```shell
sudo cp vlc-protocol /usr/local/bin/
xdg-desktop-menu install vlc-protocol.desktop
xdg-open vlc://https://pbs.twimg.com/tweet_video/Cx5L_3FWgAAxzpM.mp4
```

To install using curl:
```shell
sudo curl -L -o /usr/local/bin/vlc-protocol https://github.com/stefansundin/vlc-protocol/raw/main/linux/vlc-protocol
sudo chmod +x /usr/local/bin/vlc-protocol
curl -L -o vlc-protocol.desktop https://github.com/stefansundin/vlc-protocol/raw/main/linux/vlc-protocol.desktop
xdg-desktop-menu install vlc-protocol.desktop
rm vlc-protocol.desktop
```

Uninstall:
```shell
xdg-desktop-menu uninstall vlc-protocol.desktop
sudo rm /usr/local/bin/vlc-protocol
```
