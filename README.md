# Box2D Self-Driving Car (Summer 2022 Project)

 This is a Box2D Self-Driving Car environment in OpenAI gym. I did this project as part of my introduction to Reinforcement Learning. I implemented it with the help of Stable Baselines3 which is a set of reliable implementations of Reinforcement Learning algorithms in PyTorch. The algorithm used to complete this environment is Proximal Policy Optimization (PPO).

## How it works

In this environment, the self-driving car drives on the track and gets rewards if it stays on the track while driving at a fast pace. The car starts at rest in the center of the road and the episode ends when all tiles are visited or when the car leaves the playfield far off the track.

Performance Before Training the Car

<img src="images/car_racing_no_training.gif" width="50%"/>

Performance After Training the Car

<img src="images/car_racing_best_model.gif" width="50%" />

## Reference

 * [Reinforcement Learning in 3 Hours Course by Nicholas Renotte](https://www.youtube.com/watch?v=Mut_u40Sqz4&t=4596s&ab_channel=NicholasRenotte)
 * [OpenAI Box2D Car Racing Environment](https://www.gymlibrary.dev/environments/box2d/car_racing/)
* [Stable Baselines3](https://stable-baselines3.readthedocs.io/en/master/)