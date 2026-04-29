# SoundMeter

Android sound level meter — `com.tekphreak.soundmeter`

## Features
- Live dB readout with color-coded level bar (green → yellow → orange → red)
- 12 sound level descriptions: Breathing, Whisper, Quiet Room, Library, Conversation, Office, Vacuum, Traffic, Motorcycle, Concert, Jet, Pain Threshold
- 1.5s debounced description text for easy reading
- Min / Avg / Max stats with reset
- Navy blue (#000080) UI, white text
- ✕ exit button

## Build
Open in Android Studio → Build → Build APK(s)

## Sideload
```
adb install SoundMeter.apk
```

**Package:** `com.tekphreak.soundmeter` | Min SDK: 24 | Target SDK: 34
