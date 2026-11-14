# Pannolato 0.1.0-alpha.13

Pannolato is an indoor cycling app. It controls your smart trainer and shows a 3D ride.
This is an early test build. Expect bugs.

## Install

1. Download the file for your system from the Releases page:
   - macOS (Apple Silicon): `Pannolato-0.1.0-alpha.13-mac-arm64.dmg`
   - Windows: `Pannolato-0.1.0-alpha.13-win-x64.exe`
2. The app is not signed yet. Your system shows a warning. This is normal.
   - macOS: open the dmg and drag Pannolato to Applications. Open the app once; macOS blocks it.
     Then open **System Settings > Privacy & Security**, scroll down and click **Open Anyway** next to Pannolato. Confirm. Do this once.
     If macOS says the app is "damaged", run this in Terminal: `xattr -cr /Applications/Pannolato.app`
   - Windows: run the installer. When SmartScreen shows a warning, click **More info**, then **Run anyway**.
3. Allow Bluetooth when the system asks.
4. Enter the access code you received from the owner (format XXXXX-XXXXX-XXXXX-XXXXX). The app asks once. Codes from alpha.5 and older do not work. After a few wrong codes the app makes you wait.
5. The app asks once whether it may send an anonymous daily ping (app version and platform only), so we can count active riders. Change it any time in **Settings**.

## Devices

- Smart trainers with FTMS (Bluetooth).
- Older Tacx trainers without FTMS (Flow Smart, Vortex): power, cadence, ERG and slope. No spin-down.
- Bluetooth heart-rate straps.
- Turn on Bluetooth and wake the device (pedal or put on the strap) before you pair.

## Group ride

Ride together with up to 10 friends. Everyone needs a trainer and an internet connection.

1. One rider opens **Group**, presses **New group** and shares the 6-letter code.
2. The others open **Group** and enter the code and press **Join**.
3. The host presses **Start in 10 s**. Keep-together holds the group on the road.

## Strava

Strava upload does not work in the alpha. Strava limits this app to one athlete.
Use **Export FIT** in History. Upload the FIT file to Strava or Garmin Connect by hand.

## Your data

Rides and settings live in the `data` folder inside the app folder:

- macOS: `~/Library/Application Support/Pannolato/data`
- Windows: `%APPDATA%\Pannolato\data`

The app does not write a log file yet. To get a log on macOS, start it from Terminal:
`/Applications/Pannolato.app/Contents/MacOS/Pannolato`
Copy the text it prints into your bug report.

## Feedback

Send feedback here: <OWNER: add the WhatsApp/Telegram group link and the form link>

Please include:
- App version (bottom of Settings)
- Trainer model and OS
- What broke, and a screenshot

## Expiry

This alpha stops working on 2027-01-10. Download the new version from the Releases page.
