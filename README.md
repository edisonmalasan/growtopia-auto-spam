# Growtopia Auto Spam Script

A simple, straightforward Lua script for automating chat spam in Growtopia. Designed to be run using the **Pandora** software.

## Overview
`eds_auto_spam.lua` is a basic auto-spammer that loops indefinitely, sending predefined chat messages at specific intervals. It uses the `SendPacket` and `Sleep` functions typically available in Growtopia proxy/modding clients like Pandora.

## Features
- **4 Custom Messages**: Allows you to configure up to four different text messages (`TextV1` through `TextV4`).
- **Built-in Delays**: Includes pre-configured delays (`Sleep`) between messages to prevent immediate mute/ban from sending packets too fast.
- **Infinite Loop**: Runs continuously until the script is manually stopped.

## Configuration
To change the spam text, open `eds_auto_spam.lua` and modify the values of the `TextV1`, `TextV2`, `TextV3`, and `TextV4` variables at the top of the file:
```lua
TextV1 = "First message here"
TextV2 = "Second message here"
TextV3 = "Third message here"
TextV4 = "Fourth message here"
```

## Usage
1. Open your Pandora software (or any compatible Growtopia script executor).
2. Load the `eds_auto_spam.lua` script.
3. Configure your text by editing the string variables.
4. Execute the script within the software. 
5. To stop spamming, halt the script via the executor's interface.

## Details
- **Author**: @Edison
- **Creation Date**: July 19, 2022

*Disclaimer: Automation scripts violate Growtopia's Terms of Service. Use at your own risk.*