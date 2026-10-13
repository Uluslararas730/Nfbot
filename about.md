# Nfbot

A small, cross-platform macro bot for Geometry Dash. Works on Windows, Android, iOS and macOS with the same code.

## How to use

1. Open the pause menu. Nfbot's buttons are on the left.
2. **Record: ON**, then restart the level and play. Practice-mode checkpoints are handled: loading a checkpoint rewinds the recording to that frame.
3. **Save .ng** stores the macro for the current level. **Load .ng** brings it back.
4. **Play: ON**, restart the level, and the macro plays itself.
5. **Step 1 frame** advances one physics frame while paused.

## The .ng format

A `.ng` file is plain JSON holding everything about the run: format version, author, level id and name, game and mod version, creation time, physics rate, and every input. Unknown extra keys you add by hand are kept when Nfbot re-saves the file.

## Settings

- **Frame Offset**: shifts playback by a few frames if a replay lands early or late on your device.
