#pingtime

Ninja Blocks Driver that reports average ping time to google.com and displays it on the Dashboard.

Currently it uses a Temperature widget, as a workaround to allow it to be used in Rules.

For Linux systems, on line 43 in lib/device.js you'll need to grep for 'rtt' instead of 'round-trip'
