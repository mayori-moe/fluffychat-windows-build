# fluffychat-windows-build
Personal build for [FluffyChat](https://github.com/krille-chan/fluffychat) on ![Static Badge](https://img.shields.io/badge/Windows™-18a7ff?logo=windows11&logoColor=ffffff)

> ![FluffyChatPNG](https://raw.githubusercontent.com/krille-chan/fluffychat/main/assets/banner_transparent.png)
> FluffyChat is an open source, nonprofit and cute [matrix] client written in Flutter. The goal of the app is to create an easy to use instant messenger which is open source and accessible for everyone.

Based on [Release 1.13.0](https://github.com/krille-chan/fluffychat/releases/tag/v1.13.0)

Changes made to source:
- Replace Roboto fonts with Noto Sans fonts in [fonts/Roboto](https://github.com/krille-chan/fluffychat/tree/28c3dfa2bb0c86ee2a028481cefa44b5ddc21c8a/fonts/Roboto) directory (by renaming `NotoSans*.ttf` to `Roboto*.ttf` and replacing original files, so filenames remains unchanged.)
- Build `libolm.dll` from [source](https://gitlab.matrix.org/matrix-org/olm) and add it to the binary folder 

Build Environment
- Windows 11 23H2 (build 25931.1000)
- Visual Studio 2022
- Flutter 3.13.0
- cmake 3.27.3
