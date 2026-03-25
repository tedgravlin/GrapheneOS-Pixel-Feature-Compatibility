# GrapheneOS Pixel Feature Compatibility

A community-maintained reference detailing which Google Pixel features function in GrapheneOS.

Please note that GrapheneOS is intended to be a secure and private operating system. Any issues with Pixel exclusive features are not neccessarily the fault of the GrapheneOS team. A lot of unsupported features require privileged system access and/or proprietary software and therefore likely won't be added to GrapheneOS.

> [!IMPORTANT]
> Some features may require Sandboxed Google Play Services to be installed. If you discover a feature which is listed as supported but does not work without Sandboxed Google Play Services, feel free to submit an issue so we can update the documentation.

> [!NOTE]
> This list is not fully complete and information could be inaccurate. Contributions are always welcome!

### Table of contents

- [System Features](#system-features)
- [Android Auto](#android-auto)
- [Launcher/Lockscreen](#launcherlockscreen)
- [Find My Device](#find-my-device)
- [Gemini](#gemini)
- [Gboard](#gboard)
- [Google Assistant](#google-assistant)
- [Google Phone](#google-phone)
- [Google Photos / Pixel Camera](#google-photos--pixel-camera)
- [Google Recorder](#google-recorder)
- [Google Wallet / Google Pay](#google-walletgoogle-pay)
- [Personal Safety](#personal-safety)
- [Pixel Thermometer](#pixel-thermometer)
- [Pixel Screenshots](#pixel-screenshots)
- [Pixel Journal](#pixel-journal)
- [Pixel Studio](#pixel-studio)
- [Open-source alternatives](#open-source-alternatives)

Legend:
| Icon | Meaning |
| :--: | ----------------------- |
| ✅ | Fully supported |
| 🟨 | Partially supported |
| ❌ | Not supported |
| ? | Unknown, needs testing |
| 🧩 | Requires Sandboxed Google Play Services |
| 🛜 | Requires network access |
| 🛜1️⃣ | Requires network access only for initial setup (e.g. to download a ML model) |

### System Features

| Feature                                                 | 10a | 10P | 10  | 9a  | 9P  |  9  | 8a  | 8P  |  8  | 7a  | 7P  |  7  | 6a  | 6P  |  6  |
| ------------------------------------------------------- | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| Adaptive Sound                                          | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  |
| Auto-Rotate Face Detection                              | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  |
| Circle to Search                                        | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  |
| Extreme Battery Saver                                   | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  |
| Flip to Shhh [(Alternative)](#open-source-alternatives) | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  |
| Now Playing [(Alternative)](#open-source-alternatives)  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  |
| Quick Tap [(Alternative)](#open-source-alternatives)    | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  |
| Plug into external display                              | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  |
| Magic Cue                                               | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  |
| Live Notifications                                      | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  |
| Face Unlock                                             | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  |
| Battery Share                                           | ❌  | ❌  | ❌  | ❌  | ✅  | ✅  | ❌  | ✅  | ✅  | ❌  | ✅  | ✅  | ❌  | ✅  | ✅  |
| Rules                                                   | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  |

### Android Auto

| Feature                 | 10a | 10P | 10  | 9a  | 9P  |  9  | 8a  | 8P  |  8  | 7a  | 7P  |  7  | 6a  | 6P  |  6  |
| ----------------------- | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| App functions <sup>`🧩`</sup> | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  |
| Wired Android Auto      | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  |
| Wireless Android Auto <sup>`🛜`</sup> | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  |

### Launcher/Lockscreen

| Feature                   | 10a | 10P | 10  | 9a  | 9P  |  9  | 8a  | 8P  |  8  | 7a  | 7P  |  7  | 6a  | 6P  |  6  |
| ------------------------- | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| Cinematic Wallpapers      | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  |
| Emoji Wallpapers          | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  |
| Lockscreen clock styles   | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  |
| Select text from overview | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  |
| Universal Search          | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  |
| App Suggestions           | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  |
| At a Glance widget        | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  |
| Icon Shapes               | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  |
| Auto Themed Icons         | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  |
| Lockscreen Effects        | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  |
| Lockscreen Widgets        | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  |

### Find My Device

| Feature                       | 10a | 10P | 10  | 9a  | 9P  |  9  | 8a  | 8P  |  8  | 7a  | 7P  |  7  | 6a  | 6P  |  6  |
| ----------------------------- | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| App functions <sup>`🧩`</sup>                | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  |
| Find device when power is off | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  |

### Gemini

| Feature       | 10a | 10P | 10  | 9a  | 9P  |  9  | 8a  | 8P  |  8  | 7a  | 7P  |  7  | 6a  | 6P  |  6  |
| ------------- | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| App functions <sup>`🧩`</sup> | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  |

### Gboard

| Feature                            | 10a | 10P | 10  | 9a  | 9P  |  9  | 8a  | 8P  |  8  | 7a  | 7P  |  7  | 6a  | 6P  |  6  |
| ---------------------------------- | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| App functions                      | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  |
| Faster voice typing                | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  |
| Advanced voice typing <sup>`🛜1️⃣`</sup>| 🟨  | 🟨  | 🟨  | 🟨  | 🟨  | 🟨  | 🟨  | 🟨  | 🟨  | 🟨  | 🟨  | 🟨  | ❌  | ❌  | ❌  |
| Translation tool <sup>`🛜`</sup>                 | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  |

### Google Assistant

| Feature                | 10a | 10P | 10  | 9a  | 9P  |  9  | 8a  | 8P  |  8  | 7a  | 7P  |  7  | 6a  | 6P  |  6  |
| ---------------------- | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| App functions <sup>`🧩`</sup> | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  |
| "Hey Google" detection | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  |
| Quick Phrases          | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  |

### Google Phone

| Feature               | 10a | 10P | 10  | 9a  | 9P  |  9  | 8a  | 8P  |  8  | 7a  | 7P  |  7  | 6a  | 6P  |  6  |
| --------------------- | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| App functions         | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  |
| Google Phone          | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  |
| Audio emoji           | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  |
| Reverse number lookup | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  |  ?  |  ?  |  ?  |  ?  |  ?  |  ?  |  ?  |  ?  |  ?  |
| Call Screen           | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  |
| Take a Message        | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  |
| Calling Card          | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  |

### Google Photos / Pixel Camera 

| Feature          | 10a | 10P | 10  | 9a  | 9P  |  9  | 8a  | 8P  |  8  | 7a  | 7P  |  7  | 6a  | 6P  |  6  |
| ---------------- | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| Pixel Camera app functions    | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  |
| Google Photos app functions    | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  |
| Magic Eraser <sup>`🛜`</sup>  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  |
| Audio Eraser <sup>`🛜1️⃣`</sup> | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  |
| Video Boost <sup>`🛜`</sup>    | ❌  | ✅  | ❌  | ❌  | ✅  | ❌  | ❌  | ✅  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  |
| Best Take <sup>`🛜1️⃣`</sup>    | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  |
| Auto Best Take   |  ?  |  ?  |  ?  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  |
| Astrophotography      | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  |
| Face Unblur           | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  |
| Photo Unblur          | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ❌  | ❌  | ❌  |
| Pro mode              | ❌  | ✅  | ❌  | ❌  | ✅  | ❌  | ❌  | ✅  | ❌  | ❌  | ✅  | ❌  | ❌  | ✅  | ❌  |
| Manual lens selection | ❌  | ✅  | ❌  | ❌  | ✅  | ❌  | ❌  | ✅  | ❌  | ❌  | ✅  | ❌  | ❌  | ✅  | ❌  |
| Pro Res Zoom <sup>`🛜1️⃣`</sup>         | ❌  | ✅  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  |
| Camera Coach <sup>`🛜`</sup>        | ✅  | ✅  | ✅  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  |

### Google Recorder

| Feature                  | 10a | 10P | 10  | 9a  | 9P  |  9  | 8a  | 8P  |  8  | 7a  | 7P  |  7  | 6a  | 6P  |  6  |
| ------------------------ | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| App functions            | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  |
| Speaker labels           | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  |
| Gemini-powered summaries | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  |

### Google Wallet/Google Pay

| Feature                   | 10a | 10P | 10  | 9a  | 9P  |  9  | 8a  | 8P  |  8  | 7a  | 7P  |  7  | 6a  | 6P  |  6  |
| ------------------------- | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| App functions <sup>`🧩`</sup>            | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  |
| Tap-to-pay (NFC payments) | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  |

### Personal Safety

| Feature       | 10a | 10P | 10  | 9a  | 9P  |  9  | 8a  | 8P  |  8  | 7a  | 7P  |  7  | 6a  | 6P  |  6  |
| ------------- | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| App functions | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  |

### Pixel Thermometer

| Feature       | 10a | 10P | 10  | 9a  | 9P  |  9  | 8a  | 8P  |  8  | 7a  | 7P  |  7  | 6a  | 6P  |  6  |
| ------------- | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| App functions | ❌  | ✅  | ❌  | ❌  | ✅  | ❌  | ❌  | ✅  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  |

### Pixel Screenshots

| Feature       | 10a | 10P | 10  | 9a  | 9P  |  9  | 8a  | 8P  |  8  | 7a  | 7P  |  7  | 6a  | 6P  |  6  |
| ------------- | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| App functions | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  |

### Pixel Journal

| Feature       | 10a | 10P | 10  | 9a  | 9P  |  9  | 8a  | 8P  |  8  | 7a  | 7P  |  7  | 6a  | 6P  |  6  |
| ------------- | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| App functions | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ✅  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  |
| AI Features   | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  |

### Pixel Studio

| Feature       | 10a | 10P | 10  | 9a  | 9P  |  9  | 8a  | 8P  |  8  | 7a  | 7P  |  7  | 6a  | 6P  |  6  |
| ------------- | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| App functions | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  | ❌  |

---

## Open-source alternatives

Some open-source options exist to add or replace functionality similar to Pixel-exclusive features.
Note that these apps are not endorsed by myself or the GrapheneOS team.
| Feature | Alternative |
| ------------ | ---------------------------------------------------- |
| Flip to Shhh | [Flip 2 DND](https://github.com/robinsrk/flip_2_dnd) |
| Now Playing | [Ambient Music Mod](https://github.com/KieronQuinn/AmbientMusicMod)
| Quick Tap | [TapTap](https://github.com/KieronQuinn/TapTap) |
