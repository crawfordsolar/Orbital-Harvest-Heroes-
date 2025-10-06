# Orbital Harvest Heroes

## Overview

Orbital Harvest Heroes is an educational game developed for the NASA Space Apps Challenge. It demonstrates how NASA Earth Science data can be used to improve agricultural practices through a fun, interactive simulation.

In this game, you control a drone that waters crops while defending them from feral hogs. The game illustrates concepts of precision agriculture, resource management, and environmental stewardship.

## How to Play

### Installation

1. **HTML Version (No Installation Required)**:
   - Download the `orbital_harvest_heroes_no_water_loss.html` file
   - Open the file in any modern web browser (Chrome, Firefox, Safari, Edge, etc.)
   - No additional software or installation is required

2. **Python Version (For Developers)**:
   - Requires Python 3.x and Pygame
   - Install Pygame with: `pip install pygame`
   - Run the game with: `python orbital_harvest_heroes.py`

### Game Controls

- **Arrow Keys**: Move your drone around the field
- **Space Bar**: Water crops when near them or neutralize hogs on collision
- **R Key**: Restart the game after winning
- **Shift+D**: Toggle debug information (hidden feature)

### Gameplay Objectives

1. **Water All Crops**: Your primary goal is to water all highlighted crop areas to 100% (indicated by gold borders)
2. **Manage Water Resources**: Your water supply depletes as you water crops; visit trees to refill
3. **Defend Against Hogs**: Feral hogs will attack your crops and reduce their irrigation levels
4. **Strategic Planning**: Balance between watering crops and defending against threats

## Game Features

### Farming Mechanics

- **Crop Irrigation**: Water crops by moving near them and pressing space
- **Water Management**: Limited water supply that must be replenished at trees
- **Crop Visualization**: Different patterns and sizes for crops with visual indicators of irrigation levels
- **Irrigation Persistence**: Once watered, crops maintain their irrigation level unless attacked by hogs

### Environmental Challenges

- **Feral Hog Threats**: 5-10 hogs that wander for a few seconds before targeting crops
- **Threat Behavior**: Hogs damage crops by reducing irrigation by 10 points per second
- **Threat Neutralization**: Eliminate hogs by colliding with them and pressing space

### Visual Elements

- **Satellite-Inspired Background**: Tile-based background resembling NASA Earth observation imagery
- **Crop Patterns**: Three different crop patterns (grid, concentric circles, radial lines)
- **Visual Feedback**: Gold borders for fully watered crops, red borders for crops under attack
- **Water Effects**: Visual water droplet effects when irrigating

## Educational Concepts

This game demonstrates several key concepts related to NASA's Earth Science data applications:

1. **Precision Agriculture**: Using targeted irrigation based on specific crop needs
2. **Resource Management**: Balancing limited water resources for optimal crop health
3. **Threat Monitoring**: Identifying and responding to threats to agricultural productivity
4. **Satellite Data Integration**: Simulating how Earth observation data informs farming decisions

## Development

This game was developed as part of the NASA Space Apps Challenge, specifically for the "NASA Farm Navigators: Using NASA Data for Exploration in Agriculture" challenge. It demonstrates how NASA Earth Science data can be integrated into agricultural practices through interactive technology.

### Technologies Used

- **HTML5 Canvas**: For rendering the game graphics
- **JavaScript**: For game logic and interactivity
- **CSS**: For styling the user interface

## Credits

Developed by Yonkers Eco Innovators (YEI) for the NASA Space Apps Challenge.

## License

This project is open source and available for educational and demonstration purposes.

---

*"Orbital Harvest Heroes: Planetary Stewardship Through NASA Data"*
