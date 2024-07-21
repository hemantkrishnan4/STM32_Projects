# STM32 Development Kit Exploration

Welcome to the STM32 Development Kit Exploration project! This repository showcases various experiments and projects undertaken to explore embedded systems using the STM32 Development Kit. The primary objective was to delve into the capabilities of STM32 microcontrollers and implement practical applications.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Experiments](#experiments)
- [EdgeAI Studio Projects](#edgeai-studio-projects)
  - [Audio Classification](#audio-classification)
- [Results](#results)
- [Conclusion](#conclusion)
- [Acknowledgements](#acknowledgements)

## Introduction

This project repository is dedicated to documenting my journey with the STM32 Development Kit. It includes a variety of experiments that showcase different functionalities and applications of the STM32 microcontrollers. The repository also contains projects developed using EdgeAI Studio, highlighting the process of training and optimizing AI models for embedded applications.

## Installation

For detailed installation instructions, please refer to the [Installation Manuals](Installation%20Manuals) folder. This section provides step-by-step guidelines on setting up the STM32 Development Kit and the necessary software tools.

## Experiments

The experiments conducted during this exploration are stored in the `MY_STM_workspace` directory. These experiments cover a range of topics, including:

- Basic GPIO operations
- ADC and DAC usage
- PWM generation
- UART communication
- I2C and SPI interfaces
- Timer and interrupt handling

Each experiment is accompanied by code and documentation to facilitate understanding and replication.

## EdgeAI Studio Projects

The repository includes two projects developed using EdgeAI Studio, which are compressed into zip files for easy access:

### Audio Classification

- **Project Files**: [audio-classification.zip](audio-classification.zip)
- **Description**: This project aimed to create an audio classification model to detect the type of weapon used in a battlefield scenario. Although the model's accuracy was not high enough to distinguish between different types of guns of the same kind, it could reliably indicate if a battle was occurring, similar to the functionality in the game Battleground Mobile India (BGMI).
- **Challenges**: The model faced challenges in accurately differentiating between similar-sounding weapons.
- **EdgeAI Studio Benefits**: EdgeAI Studio significantly streamlined the training process by automatically selecting the best-performing algorithms and discarding the less effective ones, thus saving considerable time and effort.

## Results

To see the model in action, check out the video demonstration: [Gun.mp4](Result/Gun.mp4)

## Conclusion

The STM32 Development Kit exploration provided valuable insights into the world of embedded systems and AI model integration. While the audio classification project highlighted some challenges in model accuracy, the overall experience demonstrated the potential of combining embedded systems with AI for practical applications.

## Acknowledgements

This project was completed with the invaluable help of Dr. Sajesh Kumar. I would like to thank everyone who supported and contributed to this project. Special thanks to the developers of STM32 and EdgeAI Studio for providing such powerful tools and resources.

---

Feel free to explore the repository and experiment with the provided code and projects. If you have any questions or suggestions, please don't hesitate to reach out.

Happy coding!
