## 1.0.0-beta.29

* Macro recorder has be redone to use directly the keydown/up events as they are fired from the browser (electron). That way we do not require the presence of 5Q/X50 to do macro recording
* Optimized the keydown/up listeners, which were causing the text inputs to be extremely slow
* Now pipe zones borders are hidden when the mouse pointer is not over the keyboard area
* Updated the logic behind 'connected' and 'not connected' - now when a device is not connected, it is shown  instead in 'simulation'. Device cannot be forgotten when it is connected, but only when is in 'simulation'
* Moved the hamburger icon (for opening/closing of profile menu) next to the Das Keyboard logo, and added animation when using it
* Various other bug fixes and tweaks
