#Install gnome-keyring on KDE to prevent a keyring error with vscode 

I'm using Ubuntu 20.04 and the vscode snap version 1.66, apparently it requires gnome-keyring to prevent this error from showing up.

"Writing login information to the keychain failed with error 'GDBus.Error:org.freedesktop.DBus.Error.ServiceUnknown: The name org.freedesktop.secrets was not provided by any .service files'."

https://github.com/microsoft/vscode-docker/issues/1515

