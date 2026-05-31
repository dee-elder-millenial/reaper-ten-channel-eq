# Install REAPER Ten Channel EQ

REAPER Ten Channel EQ is a JSFX plugin. JSFX is REAPER's built-in scripting format for audio and MIDI effects.

## Manual install

1. Download `Effects/Ten Channel EQ.jsfx` from this repository.
2. In REAPER, choose `Options > Show REAPER resource path in explorer/finder`.
3. Open the `Effects` folder.
4. Copy `Ten Channel EQ.jsfx` into the `Effects` folder.
5. Go back to REAPER and open the FX browser.
6. Choose `FX > Scan for new plugins`.
7. Search for `Ten Channel EQ`.

## Windows path example

For a normal Windows install, the destination is usually:

```text
C:\Users\<you>\AppData\Roaming\REAPER\Effects\Ten Channel EQ.jsfx
```

Do not place the file in:

```text
C:\Users\<you>\AppData\Roaming\REAPER\UserPlugins
```

`UserPlugins` is for native REAPER extension binaries, not JSFX files.

## Updating

Replace the old `Ten Channel EQ.jsfx` file in your REAPER `Effects` folder with the new version, then rescan or restart REAPER.

## Uninstalling

Delete `Ten Channel EQ.jsfx` from your REAPER `Effects` folder and restart REAPER.
