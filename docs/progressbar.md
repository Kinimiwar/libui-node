
# ProgressBar

> Progress bar widget.

```js

var libui = require('libui');

libui.Ui.init();
var win = new libui.UiWindow('UiProgressBar example', 640, 480, true);

var widget = new libui.UiProgressBar();
win.setChild(widget);

win.onClosing(function () {
	win.close();
	libui.stopLoop();
});

win.show();

libui.startLoop();

```

---

# Constructor

> new libui.UiProgressBar()

Create a new UiProgressBar object.

---

# Properties

See [properties implementation](properties.md) for generic details on how properties are implemented.


## visible: Boolean

Whether the widget should be visible or hidden. 
Read write.
Defaults to `true`.



## enabled: Boolean

Whether the widget should be enabled or disabled. 
Read write.
Defaults to `true`.



## value: Number

The current position of the progress bar. Could be setted to -1 to create an indeterminate progress bar.
Read write.




---

# Methods



---

# Events

See [events implementation](events.md) for generic details on how events are implemented.


