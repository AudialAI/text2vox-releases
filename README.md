# text2vox releases

Binaries for [text2vox](https://audialmusic.ai), the Audial DAW plugin that sings typed lyrics
over a MIDI melody in any reference voice. Download the latest macOS or Windows build from the
[Releases page](../../releases) or [audialmusic.ai/downloads](https://audialmusic.ai/downloads).
The plugin talks to the Audial API with your Audial user ID and API key (active subscription
required).

## Windows

`text2vox-Windows.zip` holds the x64 VST3 and the standalone app. Unzip it, then copy the
`text2vox.vst3` folder — the whole folder, it is a bundle, not a single file — into

    C:\Program Files\Common Files\VST3

creating that folder if it is not already there, and rescan plug-ins in your DAW. Or just run
`text2vox.exe` from anywhere; the standalone needs no installation.

These builds are not code-signed yet, so the first launch may bring up Windows SmartScreen's
"Windows protected your PC" with an unknown publisher. Choose **More info**, then **Run anyway**.
Each release also ships a `.sha256` next to the zip if you want to check the download.

---

Powered by [Audial](https://audialmusic.ai).
