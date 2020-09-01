# OneNote Desktop

> Unofficial OneNote Desktop app

*OS X 10.8+, Windows 7+ & Linux are supported.*

### Install Linux

To add a shortcut to the app, create a file in `~/.local/share/applications` called `onenote.desktop` with the following contents:

```
[Desktop Entry]
Name=OneNote
Exec=/full/path/to/folder/OneNote
Terminal=false
Type=Application
Icon=/full/path/to/folder/OneNote/resources/app/static/Icon.png
```
## Dev

Built with [Electron](http://electron.atom.io).

###### Commands

- Init: `$ npm install`
- Run: `$ npm start`
- Build OS X: `$ npm run build:macos`
- Build Linux: `$ npm run build:linux`
- Build Windows: `$ npm run build:windows`
- Build all: `$ brew install wine` and `$ npm run build` *(OS X only)*

## License

MIT © [Anh Vinh](http://soociu.top)
