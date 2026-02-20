# CelebrateOniPhone

A simple HTML page that displays animated confetti and a **"You did it!"** message.

This was built to be triggered with an **NFC tag** as part of a daily ADHD tracker routine, adding a small visual celebration whenever a task is completed.

## Features

- Full-screen confetti animation using `canvas-confetti`
- Prominent “You did it!” message at the bottom of the screen
- Lightweight and mobile-friendly (works on iPhone Safari)
- Easy to pair with NFC tags in iOS Shortcuts automations

## How to Use

1. **Open on iPhone or iPad**  
   Open [the GitHub Pages link](https://krysellec.github.io/celebrateoniphone/) in any browser to see the confetti animation and message.

2. **Use with NFC Tag (iOS)**  
   - Open the **Shortcuts** app → **Automation** → **Create Personal Automation** → **NFC**  
   - Scan your tag  
   - Add the **Open URL** action pointing to [this GitHub Pages link  ](https://krysellec.github.io/celebrateoniphone/)
   - Turn **Ask Before Running** off  

3. **Optional Extras**  
   - Add **Set Flashlight On → Wait → Set Flashlight Off** to create a quick celebratory flash  
   - Add **Play Sound** or **Vibration** for a more multisensory experience  

## Why

This project is intended to give **small, positive reinforcement** in daily routines, especially for ADHD tracking or habit-building. The combination of a visual confetti effect, a positive message, and optional physical cues (flashlight, sound) makes completing tasks feel rewarding.

## Customization

- Edit the HTML to change message text, font, or colours  
- Adjust the confetti parameters in the `<script>` section for different particle counts, colours, or spread  

## License

MIT License
