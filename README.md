# visual-studio-code
VS Code: Install Instructions and desktop file

1. Download [VS Code][1]
2. Unzip/Install
	```bash
	sudo unzip VSCode-linux64.zip -d /opt
	```
3. Create Symlink
	```bash
	sudo ln -s /opt/VSCode-linux-x64/Code /usr/bin/vscode
	```
4. Copy vscode.desktop to `/usr/share/applications` for global installation or `~/.local/share/applications` for local install.
	```bash
	sudo cp vscode.desktop /usr/share/applications
	```

5. Logout and login again

[1]: https://code.visualstudio.com/