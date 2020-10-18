# Ascent Updater

A homebrew application for the Nintendo Switch that will automatically update your CFW with the latest from Ascent.

## settings.cfg

| Config option                                                               | Description
| --------------------------------------------------------------------------- | ---
| `ignore = [ "sdmc://fileToIgnore.nro", "sdmc://anotherFileToIgnore.nro" ];` | Array of files to ignore when extracting.
| `autoupdate = true;`                                                        | Whether or not to auto update Ascent Updater.
| `proxy_enabled = false;`                                                    | Whether or not to use a proxy for network calls.
| `proxy_url = "http://example.com:8080";`                                    | The URL of the proxy server.
| `proxy_username = "username";`                                              | The username to use for the proxy server, if blank it will not be used.
| `proxy_password = "password";`                                              | The password to use for the proxy server, if blank it will not be used.

## Credits

* Thanks to vgmoose for examples on using minizip in appstorenx.
* Thanks to y4my4m and natinusala in the ReSwitched discord for their discussions around libcurl.
* Thanks to alex. for improving the config and other elements in FileManager.
* Thanks to AtlasNX and TeamNeptune for everything.
