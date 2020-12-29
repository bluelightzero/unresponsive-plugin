# Unresponsive Cursor

When the server is unresponsive (Lag), the cursor will change.

![icon](icon.png)

You can set a threshold (milliseconds) for how long you want to wait after lag
is detected before it changes your cursor.

A value of 0ms will flicker thee cursor constantly as the server has micro stutters.

A value of 100ms (Default) should remove these flickers,
while still letting you know when longer lag spikes happen.
You often see these as the whole world stopping for everyone.

It should help when you are doing activities that require timing, but the server is lagging.

This plugin does not work with Custom Cursors.