# Youmagical Autoclicker v0.02

**A powerful and flexible automation tool for Windows** - Automate mouse clicks, keyboard inputs, and complex action sequences with ease.

Created by **Youma**

---

## 🚀 Quick Start

1. Download [`Youmagical Autoclicker.zip`](Youmagical%20Autoclicker.zip) from this repository and extract it
2. Run `YoumagicalAutoclicker.exe`
3. No installation required!

> **Note**: Windows may show a security warning for unsigned executables. Click "More info" → "Run anyway" if prompted.

---

## ✨ Features

### Simple Mode
Perfect for basic automation tasks:

- **Auto-clicking**: Automate left, right, or middle mouse clicks
- **Keyboard spam**: Automatically press specific keys
- **Custom intervals**: Set precise timing (hours, minutes, seconds, milliseconds)
- **Cursor positioning**: Click at current location or pick a specific position
- **Repeat modes**:
  - Infinite repeat
  - Fixed number of repetitions
  - Time-limited duration

### Advanced Mode
Professional features for complex automation:

#### 1. **Record Editor**
- Record your mouse and keyboard actions
- Replay recorded sequences
- Edit and fine-tune recorded actions

#### 2. **Action Config**
- Configure individual actions with precision
- Set detailed parameters for each action
- Add actions to your timelines

#### 3. **Simple Timeline**
- Create linear action sequences
- Organize actions into tracks
- Control timeline playback

#### 4. **Complex Timeline**
- **Node graph editor**: Visualize actions as a graph
- **Parallel execution**: Run multiple actions simultaneously
- **Dependencies**: Define execution order between actions
- **Configurable loops**: Repeat timelines with different modes
- **Save/Load**: Store complex timelines as JSON files

---

## ⌨️ Global Hotkeys

- **ALT+A**: Start/Stop autoclicker
- **ALT+R**: Start recording
- **ALT+T**: Stop recording
- **ALT+P**: Play timeline
- **ALT+S**: Stop timeline playback

> 💡 **Tip**: Customize hotkeys via the "Hotkey setting" button

---

## How to Use

### Simple Mode (Beginner-Friendly)

1. Launch the application
2. Set your click interval (hours, minutes, seconds, milliseconds)
3. Choose action type:
   - **Mouse Click**: Select button (left/right/middle) and click type (single/double)
   - **Keyboard Key**: Enter the key to press (e.g., "a", "space", "enter")
4. Choose cursor position:
   - **Current location**: Clicks wherever your mouse is
   - **Pick location**: Click "Pick" and move your mouse to the desired position (3-second countdown)
5. Select repeat mode:
   - **Repeat until stopped**: Runs indefinitely
   - **Repeat X times**: Stops after a set number
   - **Repeat for X seconds**: Stops after a duration
6. Click **Start (ALT+A)** or press **ALT+A**
7. Press **Stop (ALT+A)** or **ALT+A** again to stop

### Advanced Mode

#### Switching to Advanced Mode
Check the **"Advanced Mode"** checkbox at the top of the window.

#### Recording Actions
1. Go to the **Record Editor** tab
2. Click "Start Recording" or press **ALT+R**
3. Perform your actions (clicks, movements, keystrokes)
4. Click "Stop Recording" or press **ALT+T**
5. Click "Add to Timeline" to save your recording

#### Creating a Complex Timeline
1. Go to the **Complex Timeline** tab
2. Configure loop settings:
   - **Name**: Give your timeline a name
   - **Duration**: Set loop duration (0 = auto)
   - **Repeat Mode**: Choose infinite, count, or duration
3. Add elements:
   - **+ Action**: Add a single action (click, keypress, delay)
   - **+ Record**: Add a recorded sequence
4. Double-click elements to edit them
5. View your timeline in the **node graph** on the right
6. Click **Save** to save your timeline as a JSON file
7. Click **Play** to execute your timeline

---

## 🎯 Use Cases

- **Gaming**: Automate repetitive tasks in games
- **Testing**: Test UI interactions automatically
- **Data entry**: Speed up repetitive form filling
- **Presentations**: Automate slide transitions or demos
- **Productivity**: Automate any repetitive computer task

---

## ⚠️ Important Warnings

- **Use responsibly**: Some games and applications may detect and block autoclickers
- **Terms of Service**: Using autoclickers may violate the terms of service of certain platforms
- **Test first**: Always test your automation in a safe environment before real use
- **Minimum interval**: The minimum click interval is 1 millisecond to prevent system overload

---

## Troubleshooting

### Application won't start
- Run as administrator if needed
- Check if your antivirus is blocking the executable
- Make sure you have the latest Windows updates

### Global hotkeys don't work
- Check if another application is using the same hotkeys
- Customize hotkeys via "Hotkey setting" button
- Try running the application as administrator

### Clicks aren't executing
- Verify the minimum interval (1ms) is respected
- Ensure the application has necessary permissions
- Check if the target application is blocking automation

### Timeline won't play
- Make sure you've added at least one element
- Verify all element configurations are valid
- Check that no other timeline is currently running

---

## 📝 Version History

### v0.02 (February 18, 2026)
- Added version number to window title
- Fixed critical startup bug in Complex Timeline Widget
- Improved stability

### v0.01
- Initial release
- Simple mode with clicks and keyboard spam
- Advanced mode with 4 tabs
- Complex timeline with node graph
- Global hotkeys

---

## 💡 Tips & Tricks

1. **Start small**: Begin with Simple Mode to understand the basics
2. **Use hotkeys**: Global hotkeys work even when the app is minimized
3. **Save your work**: Always save complex timelines before closing
4. **Test intervals**: Start with longer intervals and decrease gradually
5. **Pick position carefully**: Use the 3-second countdown to position your cursor precisely
6. **Combine modes**: Use Record Editor to capture actions, then add them to Complex Timeline

---

## 📧 Support

If you encounter issues or have questions:
- Check the Troubleshooting section above
- Review your configuration settings
- Test with a simple automation first

---

**Youmagical Autoclicker** - Automate your repetitive tasks with style! ✨

Made with ❤️ by Youma
