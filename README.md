# Wise

Minecraft **1.8.9** client for **Forge**.

## Download and install

1. Download the Wise JAR from [Releases](https://github.com/meowflags/Wise/releases/latest).
2. Close Minecraft and put the JAR in your Forge 1.8.9 instance's `mods` folder.
3. Remove older Wise JARs from that instance and launch Minecraft.
4. Press **Right Shift** to open Wise with the default settings.

No Wise installer is needed. User settings and configs are created locally by the client. The explicitly shared Main Safe preset is available below.

## Main Safe preset

[Download Main Safe (Semi-Blatant)](Main-Safe.json)

This is the updated **main safe w Semi-Blatant** preset, with personal name replacements and player lists cleared. Gameplay settings, module versions, binds, theme and HUD layout are retained.

Save the JSON file in your Minecraft instance's `config/wise/configs` folder, then load it from **CaS > Your Configs**.

## Spotify

Enable Spotify in Wise to see its setup guide. On Windows, open Spotify desktop, sign in and play music; Wise can detect desktop playback automatically. Automatic desktop detection is not supported on Linux/macOS in this build. The separate account connection requires a Spotify developer Client ID and authorization through **Connect Spotify**.

Reopen the guide under **Spotify > Connection Setup > Setup Instructions**.

## This release

Version **3.8.12** fixes config save/load errors involving Height Overlay color labels and the B4 Target HUD version. The requested Main Safe save and full-config parsing were verified in the running client; no gameplay test world was used. Spotify setup, VPN Guard and trajectory improvements are included.

This repository provides the distribution JAR. Only the explicitly shared, sanitized preset is included. Other personal configs, authentication data, logs, screenshots, test worlds and local development archives are excluded. Personal attribution in two metadata strings was anonymized for this public distribution; module logic is unchanged.

Third-party components retain their notices inside the JAR and in `THIRD-PARTY-NOTICES.txt`.
