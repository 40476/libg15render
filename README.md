# libg15render

This is a library to render text and shapes into a buffer usable by the Logitech G15 Gaming Keyboard. This library probably isn't very useful without libg15 and/or g15daemon.

Font support is now provided by FreeType2.  If you want font support, provide the --enable-ttf option to configure.  For font support in applications, you must #define TTF_SUPPORT 1 before including libg15render.h and add `freetype-config --cflags` to your $CFLAGS.

## Install

```bash
aclocal
automake
make
sudo make install
```
