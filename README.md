# nnw-allmine

This is a personal customisation of the default NetNewsWire theme. It alters the
fonts to a more Humanist style and sets the preferred code font to my favourite.

- Alter code block style to remove border and add background.
- Alter article and code font.
- Set either [IBM Plex Sans] or Seravek (built into iOS and macOS) as article
  font.
- Set [JetBrains Mono] as code font, if it's installed.

The screenshot shows both IBM Plex Sans and JetBrains Mono:

![](./images/screenshot.png)

[IBM Plex Sans]: https://www.ibm.com/plex/
[JetBrains Mono]: https://www.jetbrains.com/lp/mono/

## Install

### macOS

To copy to your NetNewsWire theme folder, you can either double click the theme
file (`Default-AllMine.nnwtheme`) or run:

```
make install
```

### iOS

I'm not sure of a nice way to install on iOS.

What I have been doing is copying the `Default-AllMine.nnwtheme` file into
iCloud Drive and then installing into NetNewsWire on iOS using the
[Add a theme manually][1] instructions.

[1]: https://netnewswire.com/help/ios/6.1/en/themes.html
