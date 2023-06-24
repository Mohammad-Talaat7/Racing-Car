# Racing-Car
this project is based on [World Models By David Ha, Jürgen Schmidhuber research paper](https://worldmodels.github.io/)

It's based on a Hybrid Model that combines all the state of the art models of the different AI branches, including Deep Learning, Deep Reinforcement Learning, Policy Gradient, and even, Deep NeuroEvolution.

# Unraveling the Impossible: How Do Humans and AI Achieve the Extraordinary?
Humans possess the extraordinary ability to accomplish seemingly impossible feats simply by envisioning them. Take, for instance, a skilled baseball player. The average speed of a fastball measures 31 meters per second, leaving the player with a mere 0.39 seconds to make a decision on how to respond. Considering that the human visual stimulus reaction time is approximately 0.25 seconds, the player is left with a remarkable 0.14 seconds to connect with the ball—an endeavor that appears insurmountable. How, then, does the player manage such a feat? The answer lies in the player's capacity to anticipate the ball's trajectory based on accumulated experiences. In a similar vein, our model operates by predicting solutions to problems during its dream-like processes, effectively capitalizing on its wealth of experiences.

To achieve this level of prowess, our model employs a sophisticated amalgamation of cutting-edge algorithms. It leverages the Convolutional Neural Network (CNN) for exceptional visual perception, the Mixed Density Network (MDN) in conjunction with the Recurrent Neural Network (RNN) to establish and retain memory, Genetic Algorithms (GA) to optimize the model using Evolution Strategies (ES), and the Variational AutoEncoder (VAE) to enable the model to simulate and explore novel scenarios. This fusion of diverse techniques culminates in an exceptionally powerful and adaptive model.

# And here is the table with the comparison:
| Method | Average Score over 100 random tracks |
| --- | --- |
| DQN | 343 |
| A3C (continuous) | 591 |
| A3C (discrete) | 652 |
| Ceobillonaire’s algorithm (unpublished) | 838 |
| V model only, z input | 632 |
| V model only, z input with a hidden layer | 788 |
| Full World Model, z and h | 906 |

# Here are the libraries that we import and their respective purposes:

* os: This versatile library enables seamless interaction between our model and the underlying operating system. It empowers our model to perform essential tasks such as file and directory operations, providing a robust foundation for system-level interactions.

* numpy: A fundamental library for scientific computing, numpy equips our model with powerful mathematical capabilities. It offers a wide range of mathematical functions and efficient data structures, enabling advanced numerical computations and data manipulation.

* random: With the help of the random library, our model gains access to a reliable source of randomness. This library allows us to generate random numbers, shuffle data, and introduce probabilistic elements into our simulations, facilitating a more diverse and dynamic behavior.

* json: The json library serves as a valuable tool for data storage and interchange. By leveraging JSON (JavaScript Object Notation), our model can easily serialize and deserialize data, making it compatible with various systems and facilitating seamless data transfer and sharing.

* gym: As a popular open-source library, gym provides a wide range of environments for modeling and simulations. By utilizing gym, our model gains access to diverse scenarios and challenges, allowing us to train and evaluate our algorithms in a standardized and extensible manner.

* tensorflow:  As a leading deep learning framework, tensorflow empowers our model with robust tools for building and training neural networks. It offers a high-level interface for designing complex architectures, optimizing model parameters, and executing efficient computations on both CPUs and GPUs.

* collections: The collections library provides additional data structures and utilities beyond those offered by Python's built-in collections. It offers enhanced containers like named tuples, ordered dictionaries, and specialized data structures, enriching our model with powerful tools for managing and manipulating data effectively.

* cma: Utilizing the cma library as an optimizer, our model gains access to the Covariance Matrix Adaptation Evolution Strategy (CMA-ES). This state-of-the-art optimization technique enables efficient exploration and convergence towards optimal solutions, enhancing our model's learning and decision-making capabilities.

* time: By employing the time library, our model can measure and manage time-related operations. It allows us to track execution durations, set delays, and precisely time model performance, facilitating accurate benchmarking and efficient resource management.

* mpi4py: With the mpi4py library, our model can harness the power of parallel computing by leveraging the Message Passing Interface (MPI) standard. This enables our model to distribute computations across multiple processors, significantly accelerating training and inference tasks.

* subprocess: The subprocess library empowers our model to launch and interact with external applications as separate processes. This capability allows for seamless integration with other tools and systems, enabling our model to tap into a wider ecosystem of software and leverage their functionalities.

* sys: By utilizing the sys library, our model gains access to essential variables and functions provided by the Python interpreter. This grants us the ability to interact with command-line arguments, access system-specific parameters, and manipulate the runtime environment, providing enhanced flexibility and control.

* argparse: With the argparse library, our model can effortlessly handle command-line arguments within the program. It offers a convenient and robust framework for defining, parsing, and validating user inputs, facilitating seamless configuration and flexibility when running our model.

These libraries play crucial roles in enhancing the functionality and capabilities of our model.

### Notes

you need the following to be able to run the project:

* TensorFlow

* NumPy
* OpenAI Gym 0.9.4
* cma
* Python 3
* mpi4py
