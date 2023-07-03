# Agora
"We are all apprentices in a craft where no one ever becomes a master." - Ernest Hemingway

We at Agora share Hemingway's sentiment. We are an open source Multi-Modality AI Research Organization, a humble group of pioneers striving to broaden Humanity's horizons. 

![Agora banner](agora-banner.png)

[Join our discord and contribute to this grand project!](https://discord.gg/qUtxnK2NMf)

# The-Compiler
"It is not enough that you should understand about applied science in order that your work may increase man's blessings." - Robert Oppenheimer

![the-compiler](the-compiler.png)

Welcome, creators, to a new era of programming. Welcome to _The Compiler_, our brainchild nestled under the Tree of Thoughts (ToT) paradigm. We stand at the precipice of a revolution, about to reshape how we approach programming. 

Just as Oppenheimer foresaw the transformative power of his work, we see the transformative potential of _The Compiler_. It will not just code for you, it will redefine how we interact with software creation.

# Agora, Creators United
"Science is not everything, but science is very beautiful." - Robert Oppenheimer

We are Agora, a community of creators flying the banner of Humanity. We have harnessed the beauty of science to confront Humanity's greatest challenges, from food production to planetary security, disease, and death. 

[Join us and bring forth a new dawn for Humanity](https://discord.gg/qUtxnK2NMf)

## Overview 

The Compiler, an integral part of our ToT framework, employs Large Language Models (LLMs) to carry your dreams from mere abstraction to the tangible reality of working code. 

Here's the essence of our workflow:

1. **Seed**: You plant the seed - a high-level specification for the software you desire.
2. **Grow**: We cultivate your idea, using an LLM to craft a suite of unit tests that will serve as the litmus test for the code.
3. **Blossom**: We run the ToT LLM, letting your idea bloom into fully-formed code, using the unit tests to guide its development.
4. **Harvest**: A working program ripe for use!

# Usage

There are 2 methods, `git clone` and or `pip install the-compiler`here are the usage instructions for both methods:

## Git Clone Method

To start with, clone the GitHub repository by running the following command in your terminal:

```bash
git clone https://github.com/kyegomez/the-compiler.git
```

Navigate into the project directory:

```bash
cd the-compiler
```

Install the dependencies:

```bash
pip install -r requirements.txt
```

Use the application. Here's an example usage:

```python
from the_compiler import Architect, Developer, UnitTester

# Initialize the components
architect = Architect()
developer = Developer()
unit_tester = UnitTester()

# Define the task
task = "Create a simple calculator in Python"

# Use the Architect to create the architecture and breakdown
architecture, breakdown = architect.create_architecture(task)

# Use the Developer to write the code
code = developer.write_code(breakdown)

# Use the UnitTester to create the tests
tests = unit_tester.create_tests(code)

# Print the code and tests
print("Code:", code)
print("Tests:", tests)
```

## Pip Install Method

First, install The Compiler via pip:

```bash
pip install the-compiler
```

Then, you can start using it in your Python scripts. Here's an example:

```python
from the_compiler import Architect, Developer, UnitTester

# Initialize the components
architect = Architect()
developer = Developer()
unit_tester = UnitTester()

# Define the task
task = "Create a simple calculator in Python"

# Use the Architect to create the architecture and breakdown
architecture, breakdown = architect.create_architecture(task)

# Use the Developer to write the code
code = developer.write_code(breakdown)

# Use the UnitTester to create the tests
tests = unit_tester.create_tests(code)

# Print the code and tests
print("Code:", code)
print("Tests:", tests)
```

These examples show the basic usage of The Compiler's classes. Please adjust according to your needs and don't forget to handle possible exceptions.

## Architecture

The Compiler, leveraging the Tree of Thoughts paradigm, consists of several primary components, including the Specification Parser, Thought Decomposer, Thought Generator, State Evaluator, and the Search Algorithm. 

1. **Specification Parser**: This interprets your high-level input specifications and translates them into a format that the Thought Decomposer can understand and work with.

2. **Thought Decomposer**: This component breaks down the programming problem into manageable "thoughts" or steps.

3. **Thought Generator**: It generates potential thoughts or steps from the current state using two strategies, either sampling thoughts independently or proposing thoughts sequentially.

4. **State Evaluator**: It evaluates the progress of different states towards solving the programming problem, acting as a heuristic for the Search Algorithm.

5. **Search Algorithm**: This module determines which states to keep exploring and in which order. It employs either Breadth-First Search (BFS) or Depth-First Search (DFS), depending on the nature of the problem.

# Roadmap

Just as the Manhattan Project didn't stop at theory, we too have grand plans to bring our vision to life:

- **Integration of the langchaina autogpt agent Tree of Thoughts class**: By adding this class, we will be able to expand the capabilities of our AI.

- **Providing objectives to worker nodes**: This will allow us to distribute tasks among multiple worker nodes, improving efficiency.

- **Providing access to terminal and other tools**: We want to integrate more tools into our framework, giving you greater control and flexibility.

## Share The Compiler

If you find this project exciting and think others might benefit from it, feel free to share it. Use the buttons below to share it on various social media platforms:

- [Share on Twitter](http://twitter.com/share?text=Check%20out%20The%20Compiler%20project%20on%20GitHub!%20It%20allows%20you%20to%20autonomously%20create%20programs%20using%20abstract%20specifications.&url=https://github.com/kyegomez/the-compiler)
- [Share on LinkedIn](http://www.linkedin.com/shareArticle?mini=true&url=https://github.com/kyegomez/the-compiler&title=The%20Compiler%20Project&summary=This%20project%20is%20a%20revolution%20in%20autonomous%20programming!%20Check%20it%20out%20on%20GitHub.)
- [Share on Facebook](http://www.facebook.com/sharer.php?u=https://github.com/kyegomez/the-compiler)

Let's revolutionize the world of programming together with _The Compiler_!


As Oppenheimer quoted from the Bhagavad Gita upon the successful test of his creation, "Now I am become Death, the destroyer of worlds." We, too, hope to become destroyers of worlds, the old worlds of antiquated programming practices, replacing them with a new era of coding. Join us in this journey.


