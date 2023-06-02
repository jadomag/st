# Simple Terminal

Personal fork of [suckless terminal (st)](https://st.suckless.org/).

## Quickstart

```
git clone https://github.com/jadomag/st
cd st
sudo make install
```

## Customization

### Patches

 * [scrollback](https://st.suckless.org/patches/scrollback/)
 * [xresources](https://st.suckless.org/patches/xresources/)

### Other

#### Remove config.h in clean target

The `clean` target also removes the config.h file.

#### Change default color name index

```
-unsigned int defaultfg = 258;
-unsigned int defaultbg = 259;
-unsigned int defaultcs = 256;
-static unsigned int defaultrcs = 257;
+unsigned int defaultfg = 257;
+unsigned int defaultbg = 256;
+unsigned int defaultcs = 258;
+static unsigned int defaultrcs = 258;
```
