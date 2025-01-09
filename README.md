# MIDI & Audio Recorder

A simple Max/MSP patch that captures MIDI and audio simultaneously with minimal setup. Perfect for quick musical ideas, practice sessions, or improvisations.

## Features

**Audio Recording**
- Records two stereo pairs simultaneously:
  - Channels 1-2: Microphone input
  - Channels 9-10: Piano input
- 24-bit audio recording
- Real-time spectroscope and level monitoring

**MIDI Recording**
- Records MIDI input from Nord Stage 3 keyboard
- Captures notes, velocity, control changes, and other MIDI messages
- Visual keyboard feedback

**File Management**
- Automatically creates timestamped folders
- Saves recordings with clear, organized filenames
- Default save path: ~/Samples/sampleLibrary/midi-audio-recorder_max/

## Requirements
- Max 9 or later
- Audio interface
- MIDI keyboard/controller

## Installation
1. Download the patch
2. Place in your Max patches folder
3. Adjust the save path in the patch if needed
4. Configure your audio inputs:
   - Default Inputs 1-2
   - Default Inputs 9-10

## Usage
1. Open the patch
2. Click the large toggle button to start recording
3. Play your instrument
4. Click the toggle again to stop
5. Files are automatically saved with timestamps

## Optional Setup
- Map the patch to a keyboard shortcut
- Use tools like Kando for quick access

## Future Development
- Support for arbitrary audio/MIDI track configuration
- Customizable input routing
- Simplified setup process

## Dependencies
- createfolder.mxo external

## License
MIT License