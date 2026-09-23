# Memory File: Epic Einstein Birthday Banner

## Project Overview
This is a birthday banner interactive web application created for the user's best friend. It features a lock screen (passcode '0816'), a birthday banner (with floating balloons, falling confetti, and music), and an interactive item area.

## Key Features
1. **Lock Screen**:
   - Simple 4-digit passcode lock (0-8-1-6).
2. **Birthday Banner**:
   - "Happy Birthday" ransom-style letters.
   - Includes balloons floating up and confetti falling down.
   - Background music plays on a loop.
3. **Interactive Items**:
   - Three clickable objects (Camera, Envelope, Tape).
   - Clicking the Camera opens the "Moments of Us" polaroid wall. Polaroids flip to reveal a backside image when clicked.
   - Clicking the Envelope opens a heartfelt birthday letter.
   - Clicking the Tape opens an interactive cassette tape player.

## File Structure
- **index.html**: The main HTML, CSS, and JavaScript all bundled into one file. It contains the logic for switching scenes, animations, and the UI elements.
- **bday-music.mp3**: The background music file used in the birthday banner scene.
- **gifs/**: A directory containing GIF images and the recently added polaroid-back.jpg image used on the back of the first polaroid.

## Recent Changes
- Added pointer-events: none to confetti and balloon elements to avoid blocking clicks on the 'Next' button.
- Embedded a user-uploaded image to the backside of the first polaroid with the caption 'you glowing'.
- Created this memory file to keep track of project details as the conversation grows large.
