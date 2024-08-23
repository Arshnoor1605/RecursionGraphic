
# Elm Slider Project 🎨

## Overview

This project is an interactive slider application developed using Elm. It features a dynamic visual representation of a slider with a diamond shape that changes based on the state of the slider. Users can drag the slider, and it will animate and display different visual states accordingly.

## Features 🚀

- **Interactive Slider**: A slider with visual feedback as you drag it.
- **Dynamic Diamond Shapes**: The diamond shape's appearance changes based on the slider's state.
- **State Management**: The application handles different states including dragging, waiting, and animating.

## Visual Representation 🖼️

- **Slider**: Represented by a rounded rectangle at the bottom of the screen.
- **Diamond Shapes**: The diamond shape adapts and scales based on the slider's position.
- **Circle Indicators**: Visual indicators show the current state of the slider (dragging, waiting, animating).

## How It Works ⚙️

1. **State Transitions**:
   - **StartDragAt**: Transitions to dragging state when the mouse is pressed.
   - **MoveDragAt**: Updates the dragging state as the mouse moves.
   - **StopDrag**: Moves to waiting state when the dragging stops.
   - **StartAnimating**: Initiates animation if the slider was in waiting state.
   - **StopAnimating**: Stops animation and returns to waiting state.

2. **Visual Feedback**:
   - The slider bar and diamond shapes are updated based on the current state.
   - Circle size changes based on whether the slider is being dragged or not.

## Installation 🛠️

To run this project, you need to have Elm installed. If you don’t have Elm installed, follow these [installation instructions](https://guide.elm-lang.org/install.html).

Clone this repository and navigate to the project directory:

```bash
git clone https://github.com/yourusername/elm-slider-project.git
cd elm-slider-project
```

Install the Elm dependencies:

```bash
elm install
```

Run the project:

```bash
elm reactor
```

Open `http://localhost:8000` in your browser to see the application in action.

## Code Structure 📂

- **`src/Main.elm`**: Contains the core logic and visual representation of the slider.
- **`src/Dict.elm`**: Implements dictionary operations used in the project.
- **`src/Round.elm`**: Provides rounding functions for the project.

## Live Demo 🌐

You can view the working model of this project [here](https://stabl.rocks/ShowModulePublish?modulePublishId=71811c36-b1ce-4d10-b987-d2a19d03b517).
