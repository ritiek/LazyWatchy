# LazyWatchy

Personalizing Watchy for me. Following are the differences in original Watchy and LazyWatchy:

- Disable RTC wakeup interrupts (press back button on WatchFace screen to read RTC and update display), saves battery.
- Remove bluetooth firmware update capabilities (won't probably use it).
- Experimental sub-menus.
- Partial refreshes only. A separate menu option has been provided in order to full refresh display.
- Define `watchFaceUpButton` and `watchFaceDownButton` to execute custom actions when on WatchFace screen.


## How to use?

Download a WatchFace and update `lib_deps` in its platformio.ini to point to `LazyWatchy` instead of the default
`Watchy` repository:
```
https://github.com/ritiek/LazyWatchy.git
```
It should work with most WatchFaces but it really depends on what library features your favourite WatchFace
overrides.

I use the Mario WatchFace.
