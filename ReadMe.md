# Flappy Bird Bot

Flappy Bird bot uses simplest form of nerual network that explores random combination of weights to see what works out well.

Requirements: pygame

How to run:
1. Type "python main.py --action [arg]" in terminal or cmd, where "arg" could be, "play", "learn", or "showtime"
2. arg=play enables user to play flappy bird game and grasp the idea behind it
3. arg=learn runs a neural network model that will approximate its parameters like weights and biases meanwhile displaying occuring events. Though the training will be running for 500 epochs, but you can break it in between by pressing 'esc' key. After stopping, script will automatically save parameters in a pickle file "clappy.txt"

![](https://github.com/flappy-bird/img/flappy-bird.gif)

4. arg=showtime allows the trained model stored in "clappy.txt" to play game alone, all by itself and show you the results of training.
