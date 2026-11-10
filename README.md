# Pannolato 0.1.0-alpha.1

Pannolato is an indoor cycling app. It controls your smart trainer and shows a 3D ride.
This is an early test build. Expect bugs.

## Install

1. Download the file for your system from the Releases page:
   - macOS (Apple Silicon): `Pannolato-0.1.0-alpha.1-mac-arm64.dmg`
   - Windows: `Pannolato-0.1.0-alpha.1-win-x64.exe`
2. The app is not signed yet. Your system shows a warning. This is normal.
   - macOS: open the dmg and drag Pannolato to Applications. Right-click the app, choose **Open**, then **Open** again. Do this once.
   - Windows: run the installer. When SmartScreen shows a warning, click **More info**, then **Run anyway**.
3. Allow Bluetooth when the system asks.

## Devices

- Smart trainers with FTMS (Bluetooth).
- Bluetooth heart-rate straps.
- Turn on Bluetooth and wake the device (pedal or put on the strap) before you pair.

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
