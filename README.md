# nautilus-archive-avfs-extension
Open archives in nautilus as virtual directories using [AVFS](https://avf.sourceforge.net/). Similar to the older, now missing "Open with archive mounter" action.

That's it. It's that simple.

<div style="display: flex; flex-direction: row; padding: 1rem; width: 100%">
  <img alt="open with AVFS action" src="https://github.com/T3sT3ro/nautilus-archive-avfs-extension/assets/5300963/c4d8cedf-e1e4-4b48-ae4f-a1a927a050c1" height=400px/>
  <img alt="opened view" src="https://github.com/T3sT3ro/nautilus-archive-avfs-extension/assets/5300963/1cb0da9e-62fb-4c0a-8dd2-2f05f8a371d4" height=400px/>
</div>

## Installation: 

Depends on `avfs` and python's `magic` (should be installed by default)

```
sudo apt install avfs
mkdir -p $HOME/.local/share/nautilus-python/extensions
cd $HOME/.local/share/nautilus-python/extensions
wget https://raw.githubusercontent.com/T3sT3ro/nautilus-archive-avfs-extension/main/nautilus_avfs_extension.py
```

After installation make sure to quit and restart nautilus for the extension to take effect:

```
nautilus -q
```
