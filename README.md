# Turtle_Race
1- This document provides documentation for a turtle race betting game implemented in Python using the Turtle graphics library.    - The game allows users to bet on a turtle and watch a race among different colored turtles.

  2. Application Setup:
   - The game window is created using the Turtle graphics library with a width of 500 and a height of 400 pixels.
   - Users are prompted to enter their bet by selecting a color for the turtle they believe will win the race.

3. Turtle Initialization:
   - Six turtles with different colors (red, orange, yellow, green, blue, purple) are created and positioned at different y-coordinates along the starting line.
   - The turtles are stored in a list called `all_turtles`.

4. Betting Prompt:
   - Users are prompted to enter their bet by specifying the color of the turtle they think will win the race.
   - If a valid color is entered, the race starts.

5. Race Simulation:
   - The race simulation takes place within a while loop that runs until one of the turtles reaches the finish line.
   - Each turtle moves forward a random distance between 0 and 10 pixels in each iteration.
   - If a turtle reaches or crosses the x-coordinate of 230 pixels, the race is considered over.

6. Race Outcome:
   - When the race ends, the winning turtle's color is determined.
   - If the winning turtle's color matches the user's bet, a message is displayed indicating that the user has won.
   - If the winning turtle's color does not match the user's bet, a message is displayed indicating that the user has lost.
   
7. Conclusion:
   - This Python turtle race betting game provides users with an interactive experience where they can bet on a turtle race outcome.
   - Users can enjoy watching the race simulation and see if their chosen turtle wins.
   - The game encourages user engagement and offers a simple betting experience.

Note: This documentation offers an overview of the code structure and functionality. Detailed code comments are available within the Python script for a more comprehensive understanding of the implementation.
