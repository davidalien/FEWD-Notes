##Installation and setup

1. Install [Package Control](https://packagecontrol.io/installation) for Sublime Text if you haven't already started using plugins. Sublime Text may need to be restarted.

2. Using Package Control, install the [LiveReload](https://packagecontrol.io/packages/LiveReload) plugin.
	- Open the Command Palette (**Tools > Command Palette**)
	- Type "Package Control: Install Package" (will auto-complete)
	- Search on "LiveReload"
	- Restart Sublime Text if needed.

3. Configure Sublime Text to load the plugin on startup. This keeps you from having to call it from the command palette everytime you want to use it.
	- Go to **Preferences > Package Settings > LiveReload > Settings - User**
	- Paste `{ "enabled_plugins": [ "SimpleRefresh" ] }` into the file that opens.
	- Save and close the file.
	- Click **Preferences > Package Settings > LiveReload > Settings - User > enable/disable plugins** to enable the plugin

4. Install and configure [Chrome plugin](https://chrome.google.com/webstore/detail/livereload/jnihajbhpnppcggbcgedagnkighmdlei?hl=en)
	- Once plugin is installed, go to **Chrome > Settings > Extenstions**, locate LiveReload and check 'Allow access to file URLs'.

##Use

1. Open your working folder in Sublime Text, then open the HTML page in Chrome.
2. Click the LiveReload extension button in Chrome.
3. Now when you save changes in Sublime Text, the changes will appear in the browser.

