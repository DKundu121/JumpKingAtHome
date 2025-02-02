# Jump King with NeuroEvolution of Augmenting Topologies!

This repository is a **fork** of the original project, modified for a University group project. Several significant changes have been made, including:

- **Multiple Kings**: Enabled multiple kings to exist concurrently, interacting within the same environment.
- **Multi-Level King Support**: Added support for kings across several levels concurrently for parallelised training.
- **King Awareness Hooks**: Incorporated hooks into the code, providing input data to neural networks, giving a view of each king's surroundings.
- **NEAT-Python Integration**: Integrated NEAT-Python to evolve generations of neural networks, where each network controls a king, allowing for improvements in king behavior through evolution over time.
- **Asynchronous Game Logic**: Modified the game to run asynchronously of individual kings' action by implementing a per-king action queue, maintaining a fixed game speed.
- **Parallel Training Optimisation**: Significantly optimised the game code by drastically reducing need to call updater functions and implementing active GC collection to resolve memory errors, enabling the training of hundreds of kings in parallel.

![image](https://github.com/user-attachments/assets/77ee0345-f1cb-489a-81bf-ea0c042a5bac)

(Apologies for the commit messages, this was a fun yet challenging project!)

**Original Description Below**


# Jump King
 Jump King With Pygame.
 Run JumpKing.exe to play
 ## Gameplay
  ![image](https://user-images.githubusercontent.com/67669987/92433021-c6033c80-f150-11ea-8b53-2936438f5dba.png)
  ![image](https://user-images.githubusercontent.com/67669987/92433069-de735700-f150-11ea-8a77-0895216d5892.png)
  ![image](https://user-images.githubusercontent.com/67669987/92433091-f054fa00-f150-11ea-81f0-98741a3a8ddc.png)
  ![image](https://user-images.githubusercontent.com/67669987/92433116-0367ca00-f151-11ea-9d4e-f8d6f5e1e722.png)
  ![image](https://user-images.githubusercontent.com/67669987/92433149-137fa980-f151-11ea-92b6-f8b12a9e6c9d.png)
  ![image](https://user-images.githubusercontent.com/67669987/92433172-21cdc580-f151-11ea-9a12-9708510e37e2.png)
  ![image](https://user-images.githubusercontent.com/67669987/92433211-39a54980-f151-11ea-86bd-69212a2620da.png)
  
## Thoughts
  This was my first game I've made that had any type of physics. I really like Jump King and I wanted it to be part of my learning experience. This is a near-perfect replica of Jump King. Various things are still missing like the extras and end-game stuff. I added a few things to make the game a bit easier which include: a checkbox to show hitboxes under the graphics menu and a flying mode triggered by pressing "C". The code is a bit messy and there are probably a lot of bugs, but this was my first time making a project this big. It was a lot of fun!
