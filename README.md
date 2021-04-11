# xrsvars
Exports colors in .Xresources as environment variables

## Installation:
Clone the repository and install the script:
```console
$ git clone https://github.com/martinvavro/xrsvars.git
$ cd xrsvars
# install src/xrsvars /usr/local/bin
```
After that verify that running command `xrsvars` works, and it correctly found every color by running:
```console
$ xrsvars -test
```
It's output should look something like this:
```
XRDBFOREGROUND=#D6D6D6
XRDBBACKGROUND=#1A1A1A
... more colors ...
XRDBCOLOR8=#666666
XRDBCOLOR9=#CF6171
```
If it does, finish the installation by running:

```console
$ echo "source xrsvars -export" >> ~/.xinitrc #or wherever your .xinitrc is stored at
```
