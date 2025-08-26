# VR Gun Range

A virtual reality shooting simulator built with Unreal Engine 5, featuring two distinct shooting exercises with realistic weapon mechanics.

## Overview

VR Gun Range offers an immersive shooting experience in virtual reality, challenging players with both static and moving target scenarios. The game emphasizes accuracy and reaction time through realistic weapon handling and physics-based interactions.

## Features

### Game Modes
- **Static Targets**: Shoot at stationary colored spheres with one red target active at a time
- **Moving Targets**: Track and hit horizontally moving targets for increased difficulty

### Weapons
- **Pistol**: Semi-automatic handgun with slide mechanics
- **AK47**: Assault rifle with charging handle operation
- **Realistic Loading**: Physical magazine insertion and weapon charging required
- **Haptic Feedback**: Controller vibration on firing
- **Audio Effects**: Realistic gunshot sounds

### Scoring System
- **Goal**: Reach 25 points to complete each exercise
- **+1 Point**: Hit the red target
- **-1 Point**: Hit white targets instead of red
- **Timer**: Track your completion time (static targets only)

## Controls & Interaction

### VR Hand Tracking
- **Two-handed grip**: Primary hand holds weapon, secondary hand provides support
- **Dynamic grip switching**: Weapon transfers between hands when released
- **Physical interactions**: Push buttons, insert magazines, operate weapon mechanisms

### Weapon Operation
1. **Load Magazine**: Physically insert magazine into weapon (box overlap detection)
2. **Charge Weapon**: Pull charging handle/slide back to chamber round
3. **Aim & Fire**: Use trigger to shoot projectiles
4. **Reload**: Repeat process when ammunition depleted

## Technical Requirements

### Platform
- VR headsets compatible with Unreal Engine 5
- Room-scale VR setup recommended

### System Requirements
- VR-ready PC meeting Unreal Engine 5 specifications
- Sufficient play space for two-handed weapon handling

## Development

### Tools Used
- **Engine**: Unreal Engine 5
- **Version Control**: GitHub
- **Development**: Blueprint visual scripting system

### Key Systems
- **Physics-based weapon mechanics**
- **Timeline-driven target movement**
- **Overlap detection for interactions**
- **State machine for target behavior**
- **Scoring and timing systems**

## Game Flow

1. **Start**: Press physical button to begin 5-second countdown
2. **Exercise**: One target turns red - shoot it for points
3. **Progression**: New target becomes active after successful hit
4. **Completion**: Reach 25 points to finish exercise
5. **Results**: View completion time and accuracy

## Target Behavior

### Static Mode
- Colored spheres arranged in shooting gallery
- One sphere turns red at random
- Immediate feedback on hit/miss

### Dynamic Mode  
- Same scoring system as static mode
- Horizontal movement adds tracking challenge
- Timeline components control movement patterns

## Installation & Setup

1. Clone the repository
2. Open project in Unreal Engine 5
3. Ensure VR development plugins are enabled
4. Configure for your VR headset
5. Build and deploy to VR platform

## Authors

- Arttu Vihervuori
- Juuso Puurtinen