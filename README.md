# How to

* Follow the [Chromium OS developer guide](http://www.chromium.org/chromium-os/developer-guide)
* enter the `cros_sdk`
* Get this repository
```shell
mkdir $HOME/trunk/src/private-overlays
cd $HOME/trunk/src/private-overlays
git clone https://github.com/owulveryck/overlay-macbook-touchbar.git overlay-macbook-touchbar
```

Then

```
export BOARD=macbook-touchbar
./setup_board --board=${BOARD}
```


