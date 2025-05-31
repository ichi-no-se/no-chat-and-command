# NoChatAndCommand

A lightweight Minecraft Paper plugin that disables chat and commands for non-OP players.

## Features

- Blocks all chat messages and commands from non-OP players
- OP players are unaffected
- No configuration required

## Download

📦 [Get the latest version](https://github.com/ichi-no-se/no-chat-and-command/releases/latest)

## Installation

1. Download the `.jar` file from the Releases page
2. Put it into your `plugins/` folder
3. Restart your Paper server

## Compatibility

- Tested on Paper 1.21.4
- Built with Java 21, Gradle 8.8

## 🛠️ Build Instructions

This project uses Gradle Wrapper.

- **Mac / Linux**:
  ```bash
  ./gradlew build
  ```

- **Windows (Command Prompt)**:
  ```cmd
  gradlew.bat build
  ```

- **Windows (PowerShell)**:
  ```powershell
  .\gradlew.bat build
  ```

The compiled `.jar` file will be located in the `build/libs/` directory.
