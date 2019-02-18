# atomSettings


You can use the apm command to save/restore installed packages.

To export packages (only packages name):

'apm list --installed --bare'
(Copy output to 'package_list.txt')
atom-ide-ui@0.13.0
autocomplete-python@1.12.0
ide-java@0.8.3
python-indent@1.1.7
python-tools@0.6.9
spring-boot@1.3.0

To import packages:

apm install --packages-file PATH-TO_YOUR_FILE/package_list.txt

On Linux apm is available if you install Atom from .deb file.

On OSX: open atom -> install shell command

Windows: apm in C:\Users\YOUR_NAME\AppData\Local\atom\bin
