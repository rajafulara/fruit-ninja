# 🎹 Fruit Ninja: Dreamy Hall Piano Edition 🍉
> Slice fruits with your finger in mid-air while drifting through a procedurally generated ambient piano soundscape.
> 

# ✨ Overview
This is not just a clone; it is a browser-based technical experiment. It combines Computer Vision (Hand Tracking) with Procedural Audio Synthesis to create a game that feels like a meditation session... with fruit explosions.
Entirely contained within a single HTML file, this game requires no installation, no backend, and no external assets. Just you, your webcam, and the code.

# 🚀 Unique Features

# 👋 Touchless AI Control
Uses MediaPipe Hands to track your index finger in real-time via the webcam. The game maps your physical hand movements to the digital blade with surprising accuracy. Data is processed locally on your device—no video is ever sent to a server.
🎵 Procedural "Hall Piano" Engine
There are no MP3 files in this project. The music is generated live using the Web Audio API.
 * Soft Piano Synth: Combines sine and triangle oscillators with specific envelopes to mimic a felt piano.
 * Algorithmic Composition: An intelligent sequencer improvises gentle arpeggios in C Major/A Minor, ensuring the music never loops exactly the same way twice.
 * Mathematical Reverb: A custom ConvolverNode generates an impulse response mathematically to simulate the acoustics of a massive concert hall.

# ⚡ Performance First
 * Zero-Latency: Optimized rendering loop ensures smooth 60FPS gameplay.
 * Single-File Architecture: All CSS, Logic, and Game Engine code is packed into one file. Truly portable.

# 🕹️ How to Play
 * Launch: Open index.html in any modern browser (Chrome/Edge/Firefox/Safari).
 * Permission: Allow camera access when prompted.
 * The Blade: Raise your Index Finger. A glowing trail will appear on screen.
 * The Rules:
   * 🍉 Slice Fruits to gain points.
   * 💣 Avoid Bombs (They will hurt you).
   * ❤️ Slice Hearts to recover lost lives.
 * Progression: The difficulty ramps up every 100 points, increasing spawn rates and bomb frequency.

# 🛠️ Technical Stack
 * Core: HTML5 Canvas & Vanilla JavaScript (ES6+)
 * Computer Vision: Google MediaPipe Hands
 * Audio: Native Web Audio API (Oscillators, Gain Nodes, Convolvers)
 * Styling: Tailwind CSS (via CDN)

# 🏃 Quick Start
You don't need npm, node, or python to run this.
 * Download the .html file.
 * Double-click it to open in your browser.
 * Turn up your volume for the piano effects.
 * Play!

# 🤝 Contributing
Feel free to fork this project! Here are some fun ideas to implement:
 * Add "Combo" detection for slicing multiple fruits in one stroke.
 * Modify the audio synthesizer to play different scales (e.g., Pentatonic).
 * Add a "Zen Mode" with no bombs and infinite time.

# 📄 License
This project is open source and available under the MIT License.

Built with ❤️ by RF.
