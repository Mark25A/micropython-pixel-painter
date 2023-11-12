# MicroPython Pixel Painter for ESP32

## Overview
MicroPython Pixel Painter for ESP32 with TFT Display and Potentiometers. Create digital art on an ESP32-powered canvas with potentiometer controls. Features include tool selection, color customization, shape drawing, and more.

## Inspiration
This project is inspired by [this YouTube video](https://www.youtube.com/watch?v=Q7YubyHPzJk), involving an ESP32, TFT Display, and two potentiometers to create a pixel painting game.

## Project Components
- ESP32 Dev Kit V1
- 2.8" SPI TFT Display Module ILI9341 (240x320 pixels)
- Two potentiometers
- Micro-SD card
- Speaker
- Push buttons for quick tool/mode changes

## Current Progress
I've successfully implemented basic pixel drawing using two potentiometers. The challenge now is to add more features to make it a versatile pixel painting tool.

**[Link to my progress (Includes code and library)](https://wokwi.com/projects/378831097804843009)**

## Questions and Features
1. **Menu Creation:** Is it possible to create an on-screen menu triggered by a pushbutton? How can I save the background canvas to avoid losing the artwork?
2. **Screenshot Capture:** Can I capture screenshots of the screen and save them to the micro-sd card as a jpg, png or any other format?
3. **Potentiometer Smoothness:** How can I make the potentiometers smoother for a more precise experience?
4. **Paint Bucket Algorithm:** Can a paint bucket algorithm be implemented for filling enclosed areas with a selected color?
5. **Color Chooser:** An RGB color chooser using potentiometers for each color channel (R, G, B).
6. **Shapes:** The ability to draw shapes with control over size and color.
7. **Size Control:** Adjusting the size of the pencil and eraser tools.
8. **Crosshair:** Adding a crosshair on the screen to indicate the position of the potentiometers.
9. **True/False Painting Mode:** Implementing a mode switch for painting, deciding between continuous painting (held pushbutton) or intermittent painting.

I'm eager to gather insights, tips, and guidance from the community to enhance this project. Your expertise and advice would be immensely valuable in making this ESP32 MicroPython Pixel Painter project.

Looking forward to your suggestions and collaboration!
