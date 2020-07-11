# Snapclient.AppImage
This is the repository to install the unofficial AppImage for [Snapclient](https://github.com/badaix/snapcast).

## Getting started
Look in [releases](https://github.com/VinnyVynce/Snapclient.AppImage/releases), install the appimage then:
```
chmod +x Snapclient_v0.20.AppImage
```
The AppImage is now ready to use!

## Using it as a user wide service
Use the included `snapclient.service` as an example and add it in `.config/systemd/user`, then enable it:
```
systemctl --user enable --now snapclient.service
```

## Notes regarding this appimage
The software, snapclient, was built in Ubuntu 16.04 (xenial) in a virtulized environement. Please use a modern linux distribution before trying. I'm using Fedora Silverblue 32 for reference.
