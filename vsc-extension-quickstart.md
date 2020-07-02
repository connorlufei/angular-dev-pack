# VS Code Extension Pack

## Edit what's included the extension pack

* The `extensionPack` field in `package.json` defines what's included in the extension pack. Simply edit this field if
you want to update the extension pack's contents.
* The `extensionPack` field is an array of unique extension identifier comprised of a publisher name following a dot
and extension name. You can find this identifier in `More Info` section of the extension page in VS Code market place.

## Packaging and publishing

* Run `npm install -g vsce` to install [Visual Studio Code Extensions](https://github.com/Microsoft/vscode-vsce) command
line tool if it's not installed.
* Run `vsce package` to build a .vsix file for publishing.
* Open [VS Code Market Place Management Page](https://marketplace.visualstudio.com/manage), login and upload the .vsix file
to update the extension pack in VS Code market place.
* You may want to update version number in `package.json` and document the change in `CHANGELOG.md` if you update extension
pack contents.
