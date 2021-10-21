# Playing Hex with Reinforcement Learning
Assignment 2 of IT3105 - AI Programming, accounting for 40% of the course grade.


Using MCTS(Monte Carlo Tree Search) and Reinforcement Learning to play the 2 player game of [Hex](https://en.wikipedia.org/wiki/Hex_(board_game)).

The game is controlled from `GameController` where a tournament mode `TOPP` is implemented, where different trained models play eachother. TOPP can either be run with pretrained models, or it will train models of its own models if none is passed to `run_TOPP`. When TOPP is training the models of its own, the models are evenly saved through the training process, resulting in models of different levels of training. The different levels of training should be reflected in the scores of the TOPP tournament, where the more trained models should win more games than the less trained. Example of outcome when the neural net is trained on 10, 100, and 1000 games:


The settings of the game and the parameters of the AI models can all be tuned directly from the GameController. This includes an option to visualize the gameplay, by writing GIF files showing the gameplay. Here is an example of a 5x5 game visualization:

