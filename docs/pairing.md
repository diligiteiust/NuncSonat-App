# Pairing

Nunc Sonat finds Apple TVs and HomePods on the local network and lists them under **Remotes**.

An Apple TV can be paired in two ways. The remote pairing below lets the Mac see and control what the Apple TV is playing, and it uses the remote and AirPlay PINs. The [Apple TV app](#the-apple-tv-app) pairing connects the Mac to the Nunc Sonat app on the TV with a 6-digit code.

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

## The Apple TV app

The Nunc Sonat app for Apple TV is free on the App Store. It needs tvOS 16 or later.

1. On the Mac, open Settings → General → Apple TV app.
2. Choose **Pair**. Nunc Sonat wakes the Apple TV, opens the app, and shows a 6-digit code on the TV.
3. Type that code on the Mac.

The connection is encrypted and reconnects by itself. When the Apple TV restarts, the Mac keeps trying to reconnect. A countdown shows the next try, and the Mac connects as soon as the TV is back.

Pairing errors clear once pairing succeeds. If the Apple TV no longer lists this Mac, Settings on the Mac says so and offers **Pair**.

### More than one Mac

The Apple TV app remembers every Mac it has paired with, and several Macs can share one Apple TV. Sharing one Apple TV between several Macs is Premium. Pair each Mac with the same steps. Settings on the TV lists each Mac once and marks the one that is connected. Each Mac has its own **Forget** button there.

## HomePod

Choose the HomePod and tap **Pair**. Enter the PIN shown on a nearby signed-in Apple device. HomePod does not ask for a second AirPlay PIN. A paired HomePod can also be picked as a speaker.

## This Mac

**This Mac** is Music on the computer you are using. The first time you select it, macOS asks for Automation access so Nunc Sonat can control Music. Allow it under System Settings → Privacy & Security → Automation.

## After pairing

The row shows **Paired** and then **Connected** when the session is up. Play, pause, next, previous, and the main volume work without Premium. Artwork, title, and artist appear in the menu and, if you open it, the mini player (⇧⌘M while the menu is open).
