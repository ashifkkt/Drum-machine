# Drum Machine
####

This project implements a virtual drum machine using HTML, CSS, and JavaScript. Each key corresponds to a specific drum sound, allowing users to trigger sounds by pressing corresponding keys on their keyboard.

## Features

- **Keyboard Trigger**: Press keys (A, S, D, F, G, H, J, K) to play different drum sounds.
- **Visual Feedback**: Each key press triggers a visual effect on the corresponding drum pad.
- **Audio Playback**: Play sounds in real-time using HTML5 `<audio>` elements.

## How It Works

1. **HTML Structure**:
   - Displays a set of drum pads (`<div class="key">`) with corresponding keyboard keys (A, S, D, F, G, H, J, K) and drum sound names.
   - Includes `<audio>` elements for each drum sound file (`clap.wav`, `hihat.wav`, `kick.wav`, etc.).

2. **CSS Styling**:
   - Provides styling for the drum pads and visual effects when a pad is triggered (`playing` class).

3. **JavaScript Functionality**:
   - **Event Listener**: Listens for `keydown` events on the `window`.
   - **Play Sound**: When a key corresponding to a drum pad is pressed, the associated `<audio>` element is played.
   - **Visual Feedback**: Adds and removes the `playing` class to create a visual effect on the drum pad when triggered.

## Usage

1. **Open the `index.html` file in a web browser** to launch the drum machine.
2. **Press the keys (A, S, D, F, G, H, J, K)** on your keyboard to trigger different drum sounds.
3. **Enjoy experimenting with different rhythms and beats** using the virtual drum pads.

## Technologies Used

- **HTML**: For structuring the drum pads and audio elements.
- **CSS**: For styling the drum pads and creating visual effects.
- **JavaScript**: For implementing the functionality to play sounds and provide visual feedback.

## Getting Started

1. **Clone the repository** to your local machine.
2. **Open the `index.html` file** in a web browser.
3. **Start playing** by pressing the designated keys on your keyboard to trigger drum sounds.

## Contribution

Contributions are welcome! Fork this repository and submit pull requests to enhance the functionality or add new features. Please open an issue first to discuss any major changes.

## License

This project is licensed under the MIT License.

---

