# Pairing

Nunc Sonat finds Apple TVs and HomePods on the local network and lists them under **Remotes**.

## Apple TV

1. Open the Nunc Sonat menu.
2. Choose the Apple TV.
3. Tap **Pair**.
4. Type the PIN on the Apple TV. A second PIN follows for AirPlay. Enter that one too.

Both PINs are stored in the Keychain. Quit and reopen the app and it connects without asking again.

The PIN prompt can be cancelled. It times out after 90 seconds. Choosing a different remote cancels it. Restarting the app does not resume a PIN that was waiting.

### Headless Apple TV

A headless Apple TV has no display, so it cannot show either PIN. Connect a display once, pair, enter both PINs, then disconnect the display. The Keychain pairing remains, and the display is not needed again.

**Pair again** and **Forget pairing** are in the Pairing menu. Both ask before they run, because a headless Apple TV needs the display back to show a new PIN.

## HomePod

Choose the HomePod and tap **Pair**. Enter the PIN shown on a nearby signed-in Apple device. HomePod does not ask for a second AirPlay PIN.

## This Mac

**This Mac** is Music on the computer you are using. The first time you select it, macOS asks for Automation access so Nunc Sonat can control Music. Allow it under System Settings → Privacy & Security → Automation.

## After pairing

The row shows **Paired** and then **Connected** when the session is up. Play, pause, next, previous, and the main volume work without Premium. Artwork, title, and artist appear in the menu and, if you open it, the mini player (⇧⌘M while the menu is open).
