# atom-android-debugger package

This is a fork from [https://github.com/longseespace/atom-android-debugger](https://github.com/longseespace/atom-android-debugger)

and modified for st-link

Before debugging, please add your source root directory into the tree-view and start gdbserver from your device:

```
  gdb forward tcp:4242 tcp:4242
  gdb shell /system/bin/gdbserver --multi localhost:4242
```

Remember to set paths:

![config](https://raw.githubusercontent.com/longseespace/atom-android-debugger/master/config.png?raw=true)

Screenshot:

![screenshot](https://raw.githubusercontent.com/longseespace/atom-android-debugger/master/screenshot.png?raw=true)


## TO DO

* Add `watch` view to display variable value.
