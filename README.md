# cs301-assignments
This is the repository for Introduction to Data Science (CS301) assignments for Saumya Dwivedi.
## Simple Language Models Summary
A simple language model can be explained in terms of each of the words that comprises it. It is simple and models language. This includes processing and/or generating text that represents a lexeme (or lexemes in more complicated models) from that language. By feeding these models training data, we can teach them to generate these outputs by using specific strategies. In our case, we utilized bigrams (2 character combinations) to generate names after feeding our models thousands of names. To summarize this experiment, in the first part of this assignment, we built an intuition for what neural networks are by building a simple one: a fully connected neural network or multilayer perceptron. This intuition included understanding how neural networks generate their output, tune their paramters using backpropogation and loss function, and more. By doing this, we also got a grasp of jax for the latter part of the experiment. Then, we created a simple model that generated names. Our initial model counted the occurences of bigrams, normalized them, and sampled from these probability distribution. After this, we wrapped this model in a gradient-based framework or neural network. By utilizing negative log likelihood,
