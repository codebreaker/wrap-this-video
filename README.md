# wrap-this-video
Script and contractor for moving selected video file into its own directory
Move selected video into its own folder from inside Files. Designed for [elementary OS](https://elementary.io).


## Installing

Copy `wrap-this-video` to somewhere in your path and set ownership/permissions, i.e.

```bash
sudo cp wrap-this-video /usr/local/bin/
sudo chown root:root /usr/local/bin/wrap-this-video
sudo chmod 755 /usr/local/bin/wrap-this-video
```

Copy the contract into a contractor directory and set ownership/permissions, i.e.

```bash
sudo cp wrap-this-video.contract /usr/share/contractor/
sudo chown root:root /usr/share/contractor/wrap-this-video.contract
sudo chmod 644 /usr/share/contractor/wrap-this-video.contract
