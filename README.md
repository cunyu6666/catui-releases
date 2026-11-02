# Catui Releases

Desktop installers and the auto-update feed for Catui Beta.

## Download

- macOS Apple Silicon (M1/M2/M3/M4): `Catui-Beta-*-arm64.dmg`
- macOS Intel: `Catui-Beta-*-x64.dmg`
- Windows x64: `Catui-Beta-*-x64.exe` (NSIS installer)

Get the newest files from [Releases](https://github.com/cunyu6666/catui-releases/releases).

## Important: unsigned builds

Current builds are unsigned Beta builds for early testing.

**macOS** — first launch may show "Catui Beta is damaged and cannot be opened". This is Gatekeeper quarantine, not corruption. Run:

```
xattr -dr com.apple.quarantine "/Applications/Catui Beta.app"
```

or open once, then System Settings → Privacy & Security → "Open Anyway".

**Windows** — SmartScreen will warn; click "More info" → "Run anyway".
