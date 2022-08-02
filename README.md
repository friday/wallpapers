# wallpapers
Wallpapers from [ElementaryOS](https://github.com/elementary/wallpapers), [Antergos](https://github.com/Antergos/wallpapers) (rip), and some from [Gnome](https://gitlab.gnome.org/GNOME/gnome-backgrounds)

Download and extract them into your wallpaper directory:

```sh
curl -L https://github.com/friday/wallpapers/archive/refs/heads/master.tar.gz | tar xz --wildcards "*.jpg" --strip-components=1 --one-top-level=$(echo ~/.local/share/backgrounds)
```

These desktop environments have done a great job at collecting great background images. This just bring together the "best" of them according to me. I "created" this repository to make it easier for me automate my desktop installation, since Antergos is no more.

Licences and credits can be found at the original repository for ElementaryOS, but not for Antergos or Gnome.
