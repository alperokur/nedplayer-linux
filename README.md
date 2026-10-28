# NedPlayer for Linux

NedPlayer plays live TV, movies and series from your own IPTV lists
(M3U, Xtream Codes and Stalker portals). It does not provide any channels
or media content.

This repository hosts the compiled Linux releases of NedPlayer, which
Flathub uses to build the Flatpak. The application's source code is not
public.

- Website: https://nedplayer.com
- Flatpak ID: `com.nedplayer.NedPlayer`

## Account and paid plans

A NedPlayer account is required. After the trial period, a paid plan is required
to continue using the application. The Linux app does not offer in-app purchases.
Purchase a plan through the NedPlayer app on Microsoft Store, Google Play or
the App Store, then sign in with the same NedPlayer account on Linux.
Cloud sync is available on the Premium plan.

## Install

From Flathub (once published):

```sh
flatpak install flathub com.nedplayer.NedPlayer
```

## Releases

Each [release](https://github.com/alperokur/nedplayer-linux/releases) holds
`NedPlayer-<version>-linux-x86_64.tar.gz`. It contains the application
built against the GNOME Flatpak runtime. Use it through the Flatpak; it is
not meant to be run on its own.

## License

Proprietary. The package is free to download, install and redistribute unmodified.
Continued use after the trial requires a paid plan. See [LICENSE](LICENSE).
