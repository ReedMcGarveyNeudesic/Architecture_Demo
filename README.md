# Neudesic Solution Center Unity Architecture AR Superimposing Demo

## Goals
1. Take common architectural model file types and convert to Unity Objects
2. Anchor Unity AR space to real-world objects
3. Allow model to scale to proper size

## Rules
Please wait to merge branches into main until PRs are reviewed by at least one person

## Preliminary Design Plan

### [Design Diagrams.net board](https://drive.google.com/file/d/1MaFRN2_TpC_KX4ZNKEb-m1HUtOghBPDb/view?usp=sharing) (Ask Reed McGarvey for edit access)

### Main Menu
- Able to navigate to file select or to Options Menu, and back from each
- Options Menu full usage tbd 

### File Select
- Select from different file provider services
- Should open widget for selected service, only able to select viable file type from storage

### XR View
- Can go back to file selection
- Button to rotate model base by 90 degrees
- Button to clear model
- Click on objects in world to select base and rotation of model
- Slider to scale model when placed
