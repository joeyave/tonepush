TonePush with NAM Lite support for HX Stomp, built from the [joeyave/tonepush](https://github.com/joeyave/tonepush) fork (branch `app/integrated`) while its pull requests wait upstream. What it adds and how to install it: [README](https://github.com/joeyave/tonepush/tree/app/integrated#installing-this-fork).

**Download:** macOS `macos-universal.zip`, Windows `x86_64-pc-windows-msvc.zip`, Linux `x86_64-unknown-linux-gnu.tar.gz`.

## Known limitations

- The builds are not signed. macOS needs `xattr -dr com.apple.quarantine "/Applications/TonePush NAM.app"` once; Windows SmartScreen asks for More info, then Run anyway.
- NAM Lite reading is on by default. On stock firmware start TonePush with `TONEPUSH_HX_NAM_LITE=0`.
- Tested on macOS with an HX Stomp. The Windows and Linux builds compile in CI but were not tried on hardware.
- No automatic updates: download a new release to update.
