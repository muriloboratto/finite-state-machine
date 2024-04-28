# Finite State Machine (FSM)

## Overview

This project demonstrates the implementation of Finite State Machine (FSM) concepts in Unity, which are essential for modeling and controlling complex behaviors of characters or entities in a game environment. FSM is a mathematical model used to represent and control the behavior of dynamic systems with a finite number of states.

## What is a Finite State Machine?

A Finite State Machine (FSM) is a computational model that consists of a set of states, transitions between states, and actions performed in each state. It is commonly used in game development to model the behavior of characters, AI, and game objects by defining a set of states and rules for transitioning between them based on certain conditions or events.

## Components of a Finite State Machine

### States

States represent the different conditions or behaviors that an entity can be in at any given time. In Unity, states can be implemented as individual scripts or components attached to game objects, representing specific behaviors such as idle, walking, running, attacking, etc.

### Transitions

Transitions define the conditions or events that cause a transition from one state to another. These conditions can be based on user input, environmental triggers, or internal variables. In Unity, transitions can be implemented using conditional statements or triggers to switch between states.

### Actions

Actions are the behaviors or tasks performed by an entity while in a particular state. These actions can include movement, animation, interaction with objects, sound effects, and more. In Unity, actions are typically implemented within the scripts or components associated with each state.

## Implementation in Unity

In this Unity project, we have implemented a simple FSM to control the behavior of a character in a game environment. The FSM consists of multiple states such as idle, walking, running, and attacking, with transitions between them based on player input and environmental conditions.

The project includes scripts for each state, as well as a central FSM controller script that manages state transitions and actions. Each state script defines the behavior and actions to be performed while in that state, and the FSM controller script handles the logic for transitioning between states based on predefined conditions.Following the projects:

- Hands-on in Unity - The Adventurer
- Hands-on in Unity - Penguin
- Hands-on in Unity - Swordsman Squirrel

## Getting Started

To explore the project and understand the implementation of FSM in Unity, follow these steps:

1. Clone or download the repository to your local machine.
2. Open the project in Unity Editor (version 2020.3.8f1 or higher).
3. Navigate to the scene files located in the `Assets/Scenes` directory.
4. Select a scene to open and observe the behavior of the character controlled by the FSM.
5. Examine the scripts associated with each state to understand their implementation and functionality.
6. Experiment with modifying the FSM controller script or adding new states to customize the behavior of the character.

## Resources and References

- [Unity Documentation](https://docs.unity3d.com/)
- [Finite State Machines in Unity - Official Unity Tutorial](https://learn.unity.com/tutorial/finite-state-machines-in-unity)
- [Introduction to Finite State Machines](https://gamedevelopment.tutsplus.com/tutorials/finite-state-machines-theory-and-implementation--gamedev-11867)

For more detailed information on finite state machines and their implementation in Unity, refer to the provided resources and documentation.

## Contributors

- [Murilo Boratto](https://github.com/muriloboratto)
- [Vinicius Santos](https://github.com/vimsos)

If you'd like to contribute to the project or have any suggestions, feel free to submit pull requests or open issues.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
