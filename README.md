# BSAI_245-Lab_2
# Adaptive Multimodal UI

This project is a simple **Adaptive Multimodal User Interface** that combines different ways of interacting with a web interface. The system adapts its interface based on how the user interacts with it, such as using a mouse, touch, keyboard, voice, or simulated eye gaze.

## What It Does

The project combines three main interaction features:

* **Adaptive UI:** Detects whether the user is using a mouse, touch, or keyboard and changes the interface accordingly. Touch interaction uses larger controls, while keyboard interaction provides a visible focus indicator.
* **Speech and Gesture Control:** The user can move a box using mouse or touch dragging. Voice commands can also change the box's color and size or reset its position.
* **Eye-Gaze Simulation:** Mouse movement is used to simulate eye gaze. When the user keeps the mouse over a card for more than 500 milliseconds, the card is detected as a fixation and highlighted.

## Voice Commands

The following simple commands can be used:

* `red` – changes the box to red
* `blue` – changes the box to blue
* `green` – changes the box to green
* `bigger` – increases the box size
* `smaller` – decreases the box size
* `reset` – returns the box to its original state

## Technologies Used

* HTML
* CSS
* JavaScript
* Web Speech API
* Mouse and Touch Events

## How to Run

Open `adaptive_multimodal_ui.html` in a modern browser such as **Google Chrome** or **Microsoft Edge**. Microphone permission may be required to use the voice control feature.

## Purpose

The purpose of this project is to demonstrate how a user interface can respond and adapt to different forms of user interaction instead of relying on only one input method.
