# modular-reinforcement-learning
This is a reinforcement learning project on an agent in a gridworld with the tasks of reaching the goal, staying on the sidewalk, avoiding obstacles, and picking up litters on the way. The multiple tasks at here suggest that a modular reinforcement learning approach, namely dividing the learning process into different modules and learn them separately, would be more appropriate. Each module is based on Q-learning algorithm, which means that the approach at here is model-free and value-based learning.
## Files
- `module_combo.ipynb` is the entire program. The project is built from scratch with NumPy and so the visualizations are mostly printed through tables and 2d-arrays. More sophisticated visualization packages and techniques can be found online.
- `RL Report updated.pdf` is the program report. Various runnings are examined to check the performance of the agent after learning.
