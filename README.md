# Robot Simulation

This project, titled Robot Simulation, focuses on modeling the behavior of a smart vacuum cleaner navigating and cleaning tiled floors. The code is organized into two main files: `ps3.py` and `ps3_visualize.py`.

## Project Structure

### ps3.py
Within this file, you'll find a class representing the robot's position in a room. The `Room` class defines a rectangular space with dust-laden tiles, offering functionality to check dust presence, count uncleaned tiles, and perform other utility functions.

### Robot Class
The core of the simulation lies in the `Robot` class, which encapsulates different robot behaviors. A basic robot methodically cleans its current tile, navigates until it hits a wall, and then changes direction randomly. The `Faulty Robot` sporadically drops random dust amounts on tiles, extending the cleaning process. Conversely, the `Smart Robot` strategically selects tiles by prioritizing those with the highest dust concentration.

## Visualization

Execute the code at the bottom of the file in the main section to run `ps3_visualize.py`. This file provides a visualization of the robot's cleaning actions.

## Testing

Ensure code reliability with the test cases in `test_ps3_student.py`. These tests, created by both the author and the MIT 6.100B course staff, verify the correctness and dependability of your implementation.

Explore the intricacies of robot simulations and deepen your understanding of smart vacuum dynamics through this project.
