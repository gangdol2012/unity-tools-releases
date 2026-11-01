# Unity Tools releases

Downloads for **Unity Tools**: the Unity Tools Setup app and the Unity Tools extensions for VS Code.

## Get Unity Tools Setup

Unity Tools Setup installs everything Unity Tools needs (VS Code, Unity Hub and the Editor your project uses, Node.js, Codex, Python), helps you sign in, installs the Unity Tools extensions you choose, and checks that everything works. When it finds a problem, it offers a fix.

| Computer | Download |
|---|---|
| Mac with Apple silicon (M1 or newer) | [Unity-Tools-Setup-mac-arm64.dmg](https://github.com/gangdol2012/unity-tools-releases/releases/latest/download/Unity-Tools-Setup-mac-arm64.dmg) |
| Mac with Intel | [Unity-Tools-Setup-mac-x64.dmg](https://github.com/gangdol2012/unity-tools-releases/releases/latest/download/Unity-Tools-Setup-mac-x64.dmg) |
| Windows 10 or 11 | [Unity-Tools-Setup-win-x64.exe](https://github.com/gangdol2012/unity-tools-releases/releases/latest/download/Unity-Tools-Setup-win-x64.exe) |

### Opening it the first time

The app isn't signed with a paid Apple or Microsoft certificate yet, so your computer asks once before opening it.

- **Mac:** open the .dmg and drag **Unity Tools Setup** to Applications. Open it. If macOS says it can't check the app, open **System Settings → Privacy & Security**, scroll down and click **Open Anyway**.
- **Windows:** run the .exe. If Windows SmartScreen appears, click **More info → Run anyway**.

## Extensions

Every extension version is a release on this page (for example `unity-edit-tools-v0.6.21`). Setup installs them for you, but you can also download a `.vsix` and install it in VS Code with **Extensions → ⋯ → Install from VSIX…**. Install Unity Tools Base first; Play, Edit and Debug need it, and Debug also needs Play.

[`index.json`](index.json) lists every published version with its download address and SHA-256 checksum. Setup reads it to find new versions.

## License

Unity Tools is proprietary software by Gangdol. You may download, install and use unmodified copies; see the LICENSE file inside each download.
