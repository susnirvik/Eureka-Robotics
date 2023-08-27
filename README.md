# Eureka-Robotics
# Probabilistic Roadmap (PRM) Implementation

This repository contains a Python implementation of the Probabilistic Roadmap (PRM) algorithm for path planning in a 2D environment.

## Introduction

The Probabilistic Roadmap (PRM) algorithm is used for motion planning in robotics and computer graphics. It involves generating random samples in the configuration space, connecting neighboring samples to form a roadmap, and then searching for paths using the roadmap. This implementation provides a basic PRM algorithm along with path shortcutting.

## Usage

To run the PRM algorithm and visualize it, follow these steps:

1. Clone the repository to your local machine.
2. Navigate to the repository directory.
3. Run the main PRM algorithm.

## Dependencies

- `numpy`
- `pylab`

Make sure you have these libraries installed in your Python environment.

Additionally, you can use path shortcutting to improve generated paths. The `path_shortcutting` function provides path shortcutting functionality.

## Questions

Source:https://osrobotics.org/osr/planning/post_processing.html

1.Implement the PRM algorithm described earlier to solve this problem instance. Generate other query instances and environment instances and test your algorithm.
2.Implement in Python the above algorithm to post-process the paths found in Section Path planning.

Make sure you have these libraries installed in your Python environment.

## License

This project is licensed under the MIT License.


