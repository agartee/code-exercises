# Bowling Score Calculator

Welcome to the Bowling Score Calculator exercise, a hands-on coding challenge designed to refine your programming skills through the practice of test-driven development (TDD). This exercise is flexible, allowing you to select the programming language of your choice, encouraging experimentation, and showcasing different techniques. Whether you're a beginner or an experienced developer, this task aims to enhance your understanding of software development principles while providing a practical application to apply those concepts.

## Bowling Scoring Rules

Before diving into the coding challenge, let's briefly review the traditional scoring rules for ten-pin bowling, as understanding these rules is crucial for implementing the score calculator accurately. For a detailed explanation, refer to [Wikipedia](https://en.wikipedia.org/wiki/Ten-pin_bowling#Scoring).

- **Strike**: Knocking down all ten pins with the first ball (marked "X"). The score for the frame is ten plus the total pins knocked down in the next two rolls.
- **Spare**: Knocking down all remaining pins with the second ball (marked "/"). The score for the frame is ten plus the pins knocked down in the next roll.
- **Open Frame**: When neither a strike nor spare is achieved, the frame's score is simply the total number of pins knocked down in those two rolls.

A perfect game scores 300 points, achieved by rolling twelve consecutive strikes.

## Application Description

Your task is to create a service or function capable of tracking and calculating the score of a single game of bowling, adhering to the traditional scoring rules.

### Requirements

- **Simple API**: Design the program's interface to be intuitive and straightforward.
- **Consistent Terminology**: Choose consistent terminology throughout your code (e.g., decide between "roll" and "throw" and stick with it).
- **Validations**: Ensure that only valid inputs are accepted (e.g., 0-10 pins per roll, no more than 10 pins in a standard frame).
- **Test Coverage**: Aim for 100% test coverage, demonstrating the principles of test-driven development.

### Suggestions

- **Incremental Development**: Start by writing a test that describes a specific behavior, then write the minimal amount of code required to pass that test. This approach not only helps in building the application piece by piece but also ensures that each part is tested thoroughly.
- **Adaptability**: Allow yourself the flexibility to revisit and adjust your approach as needed. The process of development is iterative, and improvements can always be made.

This exercise is an opportunity to practice and understand test-driven development deeply. By focusing on writing tests before implementing functionality, you'll gain insights into designing more reliable, maintainable, and bug-free code. Enjoy the process of learning and discovery, and remember, the journey is as rewarding as the outcome. Happy coding!
