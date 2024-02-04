StoryGenerator
Overview

StoryGenerator is a simple RPG story generator designed to create engaging narratives composed of events and decisions. As the game evolves, both the types of events and the breadth of decisions available to the player will expand. The game will also feature increasingly complex character parameters for those involved in the story.

Primary Objective

The primary goal of this game-program is to facilitate such easy extensibility of decisions, situations, creatures, and more, that it becomes feasible to use neural networks for expanding and enhancing the game experience.

My Discussion with GPT about that project:
https://chat.openai.com/c/e6dc64bd-fbef-43c1-9176-54fbf6c68a8d

Initially, I plan to describe the gameplay, then determine, based on the description, all the entities that were mentioned in it, then I plan to project them into the code base in the form of class modules, and describe, determine their signature, and finally gradually fill them with the actual code in the order in which they can be conveniently tested to a minimal prototype state. At the same time, I will consult with GPT about how much he understands the expandable sections of the structure and prepare a sufficient description for them so that the extensions are simple.

The final goal is the ability to continue the adventure by generating code through the GTP during the adventure (for now, by restarting the application after the addition, and continuing the story from the saved point).

