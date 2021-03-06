Version alpha0.1.8 (unreleased)
--

What's new:

- Use your native audio output aka. Bluetooth stereo natively!\
  See https://github.com/f1xpl/openauto/pull/38
- No more stuttering when phone's native audio is used.
- The power LED is now disabled, it should save you several milliamps.

Version alpha0.1.7 2018-03-10
--

What's new:

- Customize your Crankshaft install: Put `wallpaper.png` on `boot`.
- The "plug phone in" screen doesn't scream "I AM ERROR." (Issue #23) 
- Audio volume output is now louder. (Issue #24)
- You can switch to X11 mode without getting to dev mode.
- Switching to dev mode repeatedly doesn't generate different \
  SSH certificates (so no more warnings).
- OpenAuto now remembers your settings. (Issue #13)

Release notes:

- Turn down your stereo volume. Now Crankshaft is loud.
- To enable X11 mode, put a jumper on GPIO26-Ground.
- Somehow the cursor is still not showing up in X11 \
  So now you're still unable to use a mouse.


Version alpha0.1.6 2018-03-05
--

What's new:

- Dev mode: Bridge GPIO4 to ground to enable dev mode
- Less services enabled means faster startup and less power consumption\
  Removed SSH, networking, dhcpd services by default.
- Misc. organizational changes for scripts


Version alpha0.1.5 2018-03-02
--

What's new:

- Audio has very minimal stuttering: Pulseaudio problem solved
- Crankshaft is now overall much more polished experience
- The "plug phone in" interface has been revamped
- You can turn off the system with the power button
- Park mode (The "car sleep" icon) - Connect phone to wake it up
- Smaller binaries
- Splash screens/no more "rainbow" screen

Release notes:

- Qt5 has been rebuilt with many enhancements
- You can use mouse and keyboard (almost...)
- More information on debugging with X11/Wayland to come later

Version alpha0.1.1 2018-02-28
--

What's new:

- Raspbian Lite no longer resizes the FS on first time startup
- Faster startup time
- File system is now mounted read only -> Better SD card longevity
- Hopefully less cracks on audio output
- Allows `wpa_supplicant.conf` to be put in `precompiled`
- Allows screen flipping when putting a jumper on GPIO21/Ground
      (Pin 39-40 - that's the last row of pins)

Release notes:

- To mount system read/wite, put a jumper on GPIO4/Ground (Pin 07-09)
- Pulseaudio produces choppier audio even compared to previous one when two streams are played at the same time

Version alpha0.1.0 2018-02-24
--

- Initial release


