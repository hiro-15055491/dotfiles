# Boot USB

Require 6.5GB space


# Partitions

* /:     31GB  (40GB)
* /boot: 110MB (500MB)
* swap:  10GB  (8GB RAM)


# .xprofile

```
export XMODIFIERS="@im=fcitx"
export QT_IM_MODULE=fcitx
export GTK_IM_MODULE=fcitx

export PATH=$HOME/.local/bin:$PATH
export PATH=`yarn global bin`:$PATH
```
