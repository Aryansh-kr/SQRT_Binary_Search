# SQRT_Binary_Search
Square Root using Binary Search
# Square Root Calculator Using Binary Search in Digital Design

This project implements a digital circuit to calculate the square root of a given number using the binary search algorithm, designed and simulated in Proteus.

## Table of Contents
- [Introduction](#introduction)
- [Algorithm Overview](#algorithm-overview)
- [Design Components](#design-components)
- [Proteus Setup](#proteus-setup)
- [Simulation](#simulation)
- [Usage](#usage)

## Introduction
This project demonstrates the use of binary search in digital design to calculate the square root of a number. The implementation is carried out using Proteus, a popular electronic circuit design software, and can be simulated to verify its functionality.

## Algorithm Overview
The binary search algorithm for finding the square root works as follows:
1. **Initialization**: Set the lower (`low`) and upper (`high`) bounds for the possible square root values.
2. **Iteration**: Calculate the midpoint (`mid`) between the current bounds.
3. **Comparison**: Square the midpoint and compare it to the original number (`num`).
   - If `mid^2 == num`, you've found the square root.
   - If `mid^2 < num`, adjust the lower bound (`low = mid`).
   - If `mid^2 > num`, adjust the upper bound (`high = mid`).
4. **Termination**: Repeat the iteration until the bounds converge to a sufficiently accurate value.

## Design Components
The design consists of the following components:
- **Registers**: To store the current bounds (`low`, `high`), midpoint (`mid`), and squared value (`mid^2`).
- **Arithmetic Logic Unit (ALU)**: To perform arithmetic operations (addition, subtraction, multiplication).
- **Control Unit**: To manage the iteration process and update the bounds.

## Proteus Setup
1. **Create a New Project**: Start Proteus and create a new project.
2. **Add Components**: Add the necessary digital components such as registers, ALU, and control unit.
3. **Connect Components**: Wire the components together according to the design.
4. **Write HDL Code**: If using HDL, write the necessary code and integrate it with the Proteus design.
5. **Configure Simulation**: Set up the simulation parameters and input values.

## Simulation
The design can be simulated in Proteus. Below is an example of a simulation result:
### Main
![Screenshot 2024-07-03 012004](https://github.com/Aryansh-kr/Detection-of-Crackles-and-Wheezes-in-Lung-Audio-Samples/assets/127012188/6cb51b53-284b-42c1-a7d5-aa183b926a6d)
### Multiplier
![Screenshot 2024-07-03 012033](https://github.com/Aryansh-kr/Detection-of-Crackles-and-Wheezes-in-Lung-Audio-Samples/assets/127012188/0a684512-f1a7-41d5-9b4e-046eec459ecf)
### Comparator
![Screenshot 2024-07-03 012052](https://github.com/Aryansh-kr/Detection-of-Crackles-and-Wheezes-in-Lung-Audio-Samples/assets/127012188/39d7093e-b30c-4342-ad5e-e98987e29f11)


## Usage
To use the design:
1. Open the project in Proteus.
2. Load the design and configure the input number for which you want to find the square root.
3. Run the simulation and observe the output to get the calculated square root.


