# Troubleshooting

## The menu cannot see the Apple TV

Allow Nunc Sonat in System Settings → Privacy & Security → Local Network. The Apple TV or HomePod has to be on the same network and awake. A sleeping Apple TV can take a little while to answer. Try Connect again.

## Pairing asks for a PIN and the Apple TV has no TV

Connect a display once. Enter both PINs (the remote PIN, then the AirPlay PIN). Disconnect the display afterwards. See [Pairing](pairing.md).

## Now playing stays empty

Play, pause, and skip can work while artwork and the title are still catching up. The menu says **Now-playing unavailable** or **Connected, waiting for now playing…** when that happens. Leave the session up. Nunc Sonat keeps asking the Apple TV for the current song.

If the title looks wrong, the log records each title change and the message that caused it. Paste that line with the report.

## Music on this Mac says permission is needed

System Settings → Privacy & Security → Automation. Allow Nunc Sonat to control Music. Then use **Grant Access** in the menu.

## Premium stays locked after you paid

The key arrives in email shortly after checkout. Paste that key in Settings → Premium and tap **Activate**. Give the message a few minutes before writing. If the reply says the device limit is reached, deactivate another Mac first. See [Licensing](licensing.md).

## Collect logs

While the problem is happening, run:

```bash
log stream --predicate 'subsystem == "app.nuncsonat"'
```

Settings → Advanced → **Log MRP messages** adds a short summary of each playback message. Turn it off when you are done. Titles are included, so trim the paste to the moment that went wrong.

Attach that excerpt to a [bug report](https://github.com/diligiteiust/NuncSonat-App/issues/new/choose), with the macOS version, the app version from the About panel, and the devices involved.
