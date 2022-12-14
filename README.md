# Ai-car-simulation
-Using Genetic and reinforcement learning techniques.
-Using NeuroEvolution of Augmenting Topologies (NEAT) as reinforcement learning alogorithm.
-Progressive simulation i.e Starts from ZERO.
-Beautiful animation using pygame.
![image](https://user-images.githubusercontent.com/83497079/198849905-27d5fdb0-09ef-47af-a7b7-483b6b4801d2.png)


# NeuroEvolution of Augmenting Topologies (NEAT)
NeuroEvolution of Augmenting Topologies (NEAT) is a genetic algorithm (GA) for the generation of evolving artificial neural networks. Its uses concepts like mutation , speciation , cross over ETC to train the model over time. NEAT is one of the best algo to date for evolving network topologies.

# Map generation
This is simple map which is created by Adobe Photoshop or you can use your convenient software like Microsoft Paint etc. You can use pen tool to create smoother curves. You need to draw track in black and background in white with track starting and end position be (830, 920) and track resolution must be 1920 * 1080. 
![image](https://user-images.githubusercontent.com/83497079/198850012-53656959-4712-4aa1-86e0-6634c68487b8.png)

While in another option endless map is generated by the model.


# Model details:
-The model is neural network with 5 input and 4 output neurons.
-Initially the cars shall have zero intelligence but each action taken they may receive a reward/penalty.
-This is implemented using Fitness matrix.  In the simulation fitness of a car increases depending on the the distance travelled without crashing.
-After Each generation we will be selecting the best cars and applying crossover genetics, speciation and mutation to further increase training capability.
-Soon a alpha species will emerge which will be able to drive faster than others
![image](https://user-images.githubusercontent.com/83497079/198849953-2632575a-e3e2-4460-8aa3-0cd5178d8847.png)
In next option:
-The model is neural network with 9 input and 4 output neurons.
-Initially the cars shall have zero intelligence but each action taken they may receive a reward/penalty.
-This is implemented using Fitness matrix.  In the simulation fitness of a car increases depending on the the distance travelled without crashing.
-After Each generation we will be selecting the best cars and applying crossover genetics, speciation and mutation to further increase training capability.
-Soon a alpha species will emerge which will be able to drive faster than others
![WhatsApp Image 2022-11-17 at 13 34 15](https://user-images.githubusercontent.com/83497079/206242026-eda11650-6907-4f6b-876b-c0e9a3070d90.jpg)
![WhatsApp Image 2022-11-17 at 13 37 09](https://user-images.githubusercontent.com/83497079/206241855-548c6d03-2e01-4327-986d-d1d77f571bfe.jpg)

# Simulation:
![image](https://user-images.githubusercontent.com/83497079/198849971-4cfe9bce-8bbd-4e2b-8006-232c8246722e.png)


