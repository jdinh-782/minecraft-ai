# Minecraft AI
A reinforcement learning agent in a Minecraft world.

## Description
Using reinforcement learning and Epsilon-Greedy Q-learning, an agent is trained to complete a race track within a certain timeframe. Obstacles and bounaries are present to showcase the difficulty and allow the agent to consistently learn the pathings. Created using the [Malmo Framework](https://github.com/microsoft/malmo).

## Getting Started
### Dependencies
* Ensure intended browser of use is updated to most recent version. Google Chrome or Mozilla Firefox is preferred.
* Malmo framework is installed. Tutorials and installation on their [website](https://github.com/microsoft/malmo).
* Minimum Python2.7.1 is installed.

### Installation
Create a new folder and run the following command in terminal. <br>
``` 
git clone https://github.com/jdinh-782/Minecraft-AI.git
```

* Now that you are inside the main directory, please ensure all packages have been installed and Malmo is set up correctly.
* Depending on how Malmo is installed, you may or may not utilize the Docker shell to run Malmo. However, we use Docker to run Malmo projects and along with that comes with being able to run [Jupyter Notebook](https://jupyter.org/).

### Execution
Execution is dependent on how you setup and install Malmo. Because we use Docker shell, it has a built-in jupyter notebook server and virtual machine which will allow you to run notebook (ipynb) files and view the result in the virtual machine. Simply place the files in the jupyter notebook server and run the main files in the following order.
``` 
mazeGeneration.ipynb

continuous_movements.ipynb or discrete_movements.ipynb
```

## Help
For any questions or concerns, feel free to reach out by [email](dinhjd@uci.edu).

## Authors and Contributors
Tyler Cheng </br>
Han Minh Tran </br>
Johnson Du Dinh

## Acknowledgements
[Malmo](https://github.com/microsoft/malmo) </br>
[Docker](https://www.docker.com/) </br>
[Jupyter](https://jupyter.org/)
