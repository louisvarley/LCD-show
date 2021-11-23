# 3.5inch RPi LCD (A)


### Driver install:

````git clone https://github.com/louisvarley/LCD-show```

````cd LCD-show```

```sudo ./LCD35-show```

### additional 

```sudo nano /usr/share/X11/xorg.conf.d/99-fbturbo.conf```

and change the line

```Option "fbdev" "/dev/fb0"```

to

```Option "fbdev" "/dev/fb1" ```

to then test

```sudo FRAMEBUFFER=/dev/fb1 startx```