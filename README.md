# atomSettings


You can use the apm command to save/restore installed packages.

To export packages (only packages name):

apm list --installed --bare > ~/Gdrive/backup.txt

To import packages:

apm install --packages-file ~/Gdrive/backup.txt

On Linux apm is available if you install Atom from .deb file.

On OSX: open atom -> install shell command

Windows: apm in C:\Users\YOUR_NAME\AppData\Local\atom\bin
