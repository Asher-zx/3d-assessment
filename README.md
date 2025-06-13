# 3D Assessment - Interactive A-Frame Experience

An immersive 3D web experience built with A-Frame featuring interactive characters, animations, and VR support.

## Overview

This project creates a floating island environment where users can interact with 3D characters including Totoro and other animated models. The experience supports both desktop and VR interactions with smooth camera transitions and audio feedback.

## Features

- **Interactive 3D Environment**: Floating island with multiple 3D models
- **Character Interactions**: Click/trigger characters to trigger animations and sounds
- **VR Support**: Full Oculus Touch controller support with hand tracking
- **Smooth Camera Transitions**: Automatic camera positioning when interacting with objects
- **Audio Integration**: Character-specific sound effects
- **Flight Controls**: Custom thumbstick movement and rotation for VR
- **Animated Skybox**: Rotating starry sky background

## Assets

- **3D Models**: Character.glb, floatingisland.glb, Mako.glb, spaceship.glb, totoro.glb
- **Textures**: starsmilky.jpg (skybox)
- **Audio**: totoro.mp3, wow.mp3

## Controls

### Desktop
- **Mouse**: Look around
- **WASD**: Move camera
- **Click**: Interact with characters

### VR (Oculus Touch)
- **Left Thumbstick**: Move around the scene
- **Right Thumbstick**: Rotate view
- **A/B Buttons**: Roll camera (when implemented)
- **Trigger**: Interact with objects via raycasting

## Interactive Elements

### Totoro
- Click to trigger flying animation with spinning motion
- Plays Totoro theme audio
- Camera zooms in for close-up view

### Character
- Click to play character animation
- Plays "wow" sound effect  
- Camera transitions to character view

### Back Buttons
- Return to initial camera position
- Stop all audio playback
- Reset animation states

## Getting Started

1. Open `index.html` in a web browser
2. For VR: Use an Oculus headset with Touch controllers
3. For desktop: Use mouse and keyboard controls

## Technical Details

- Built with A-Frame 1.7.0
- Uses aframe-extras for additional components
- Custom components for VR thumbstick controls
- Raycasting system for object interaction
- Dynamic audio management

## File Structure

```
├── index.html          # Main application file
├── README.md          # Project documentation
└── assets/
    ├── *.glb          # 3D model files
    ├── starsmilky.jpg # Skybox texture
    └── sound/
        ├── totoro.mp3 # Character audio
        └── wow.mp3    # Character audio
```

## Browser Compatibility

- Chrome/Chromium (recommended for VR)
- Firefox
- Safari (limited VR support)
- Edge

For the best VR experience, use Chrome with WebXR support enabled.