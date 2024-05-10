# fast-screenshoot

[Spanish](./README_es.md)

## Instalation

Debian / Ubuntu:

- With x11-apps you can take the screenshot fastly in xwd format with the command with the same name.

- With netpbm you can convert it to another formats.

- With xclip you can copy it to clipboard.
 
```sh
sudo apt install x11-apps netpbm xclip
git clone https://github.com/aguadecoco1301/fast-screenshoot
cd fast-screenshoot
```
```
# With this, you can run it without inserting the route
sudo mv fast-screenshoot /usr/bin/fast-screenshoot
```

## Usage
It's easy. Execute the instruction and in the route on you specified the screenshoot was saved. Default is your home folder.

You can exec it with the instruction --copy to copy the screenshoot and not save it in a file.

You can add it to a keybind. For example, in i3, add this

```sh
bindsym Print exec --no-startup-id fast-screenshoot
```

# Collaborate

If you want to collaborate, just send a pull request!
