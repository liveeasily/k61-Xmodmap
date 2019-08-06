# k61-Xmodmap

This is Xmodmap file for the terrible/horrible MANIC K61 bluetooth keyboard.
You can set the keyboard as "Mode 1"(Fn+1) and remap keys with this Xmodmap file.

1. Download k61-Xmodmap file

2. Rename or copy the file to ~/.Xmodmap

3. If it doesn't load automatically, create a file at ~/.xinitrc with
  ============================
   if [ -s ~/.Xmodmap ]; then
       xmodmap ~/.Xmodmap
   fi
  ============================
