sony-laptop
===========

sony-laptop driver patch for Sony Vaio Fit multi-flip

Tested on Sony Vaio Fit 15A

This patch adds support for Sony Vaio Fit multi-flip transformations.
Transformation events are send thru acpi bus as sony/hotkey events.
Tablet mode also triggers the SW_TABLET_MODE event via Sony Vaio Keys input device.

Current mode is exported via sysfs:
/sys/devices/platform/sony-laptop/tablet
