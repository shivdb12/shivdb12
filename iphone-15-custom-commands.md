# iPhone 15 Custom Commands

How to set up your own commands on an iPhone 15, iPhone 15 Plus, iPhone 15 Pro or iPhone 15 Pro Max.
Menu paths are for iOS 18 and later; older versions may differ slightly.

| Method | Trigger | Models | Where to set it up |
|---|---|---|---|
| Shortcuts + Siri | Say "Hey Siri, *shortcut name*" | All iPhone 15 | Shortcuts app |
| Action Button | Press and hold the side button above the volume keys | 15 Pro / Pro Max only | Settings > Action Button |
| Back Tap | Double or triple tap the back of the phone | All iPhone 15 | Settings > Accessibility > Touch > Back Tap |
| Vocal Shortcuts | Say a custom phrase (no "Hey Siri" needed) | All iPhone 15 | Settings > Accessibility > Vocal Shortcuts |
| Voice Control commands | Spoken phrase while Voice Control is on | All iPhone 15 | Settings > Accessibility > Voice Control > Commands |
| Automations | Time, location, Wi-Fi, NFC, opening an app, etc. | All iPhone 15 | Shortcuts app > Automation |
| Control Center / Lock Screen controls | Tap a control | All iPhone 15 | Swipe down from top right, then press and hold an empty area |
| Text Replacement | Type a short code | All iPhone 15 | Settings > General > Keyboard > Text Replacement |

## 1. Build a command in Shortcuts

Almost every other method can run a shortcut, so start here.

1. Open the **Shortcuts** app and tap **+**.
2. Tap **Add Action** and search for what you want (e.g. "Set Focus", "Send Message", "Get Directions", "Turn Flashlight", "Play Music").
3. Add more actions to chain steps together.
4. Tap the name at the top and rename it. **The name is the Siri phrase**, so pick something easy to say.
5. Tap **Done**.

Run it by saying "Hey Siri, *name*", tapping it in the app, or adding it to the Home Screen (share icon > Add to Home Screen).

### Example shortcuts

- **"Heading home"**: Get travel time to Home > Send Message "Leaving now, home in [travel time]" to a contact > Open Maps with directions home.
- **"Work mode"**: Set Focus to Work > Set Do Not Disturb > Open Calendar > Set volume to 20%.
- **"Goodnight"**: Set Sleep Focus > Turn on Low Power Mode > Set brightness to 0% > Set alarm for 7:00 AM.
- **"Parked here"**: Get current location > Add to note "Parking spot" with the date.
- **"Log water"**: Log Health Sample > Water > 250 ml.

## 2. Action Button (iPhone 15 Pro and Pro Max only)

The standard iPhone 15 and 15 Plus have the mute switch instead and do not have this.

1. Go to **Settings > Action Button**.
2. Swipe through the options: Silent Mode, Focus, Camera, Flashlight, Voice Memo, Recognize Music, Translate, Magnifier, Controls, **Shortcut**, Accessibility, or No Action.
3. Choose **Shortcut**, then **Choose a Shortcut** to run any command you built in step 1.

Tip: make a shortcut that uses **Choose from Menu** to give the Action Button several commands in one press.

## 3. Back Tap

1. **Settings > Accessibility > Touch > Back Tap**.
2. Pick **Double Tap** or **Triple Tap**.
3. Choose a system action (Screenshot, Lock Screen, Control Center, Flashlight, etc.) or scroll down to the **Shortcuts** section and pick one of yours.

Works even with most cases on.

## 4. Vocal Shortcuts (custom phrase, no "Hey Siri")

1. **Settings > Accessibility > Vocal Shortcuts > Set Up Vocal Shortcuts**.
2. Pick an action or one of your shortcuts.
3. Type the phrase you want, then say it three times to train it.

## 5. Voice Control custom commands

Useful for hands-free control of the screen itself.

1. **Settings > Accessibility > Voice Control**, turn it on.
2. Tap **Commands > Create New Command**.
3. Enter the **Phrase**, then pick an **Action**: Insert Text, Run Custom Gesture (record taps/swipes), Run Shortcut, or Playback Recorded Commands.
4. Under **Application**, choose Any or limit it to one app.

## 6. Automations (commands that run themselves)

1. Open **Shortcuts > Automation** tab > **New Automation**.
2. Pick a trigger: Time of Day, Alarm, Arrive/Leave a location, Wi-Fi, Bluetooth, CarPlay, NFC tag, App opened/closed, Battery Level, Charger, Focus, Email/Message received, and more.
3. Choose **Run Immediately** so it runs without asking.
4. Add actions or run an existing shortcut.

Examples:
- Battery drops below 20% > Turn on Low Power Mode.
- Connect to CarPlay > Play a playlist and send an ETA message.
- Open Instagram > Show a "Time check" notification.
- Tap an NFC sticker on your desk > Start Work Focus.

## 7. Control Center and Lock Screen controls

- Swipe down from the top-right corner, press and hold an empty spot, tap **Add a Control**, and pick **Shortcut** to place any of your commands in Control Center.
- On the Lock Screen, press and hold > **Customize > Lock Screen** to replace the flashlight or camera buttons with a shortcut.

## 8. Text Replacement (typing commands)

**Settings > General > Keyboard > Text Replacement > +**. Example: typing `@@` expands to your email address, `omw` to "On my way!".

## Troubleshooting

- Siri doesn't run the shortcut: rename it to something distinct, and check **Settings > Siri** is on.
- Automation asks for confirmation: open it and switch to **Run Immediately**, turn off **Notify When Run**.
- Back Tap not triggering: tap firmly near the Apple logo; remove thick or magnetic cases to test.
- Shortcut fails on the Lock Screen: some actions need the phone unlocked; check the shortcut's details for **Allow Running When Locked** where available.
