# Udacity-dlnd-face-generation
Udacity Project 5

### dlnd_face_generation_revised ver
- Create independent leaky_relu function in discriminator and generator function.
- Add xavier_initializer in conv and conv transpose in discriminator and generator.
- Add one conv layer in dis and gen function, 2 conv layers -> 3 conv layers.
- Add dropout layer after leaky_relu activation function.
- Add one-sided label smoothing in d_loss_real to prevent discriminator becoming to strong.
- Run dis graph twice and gen 3 times to enhance generator effect.
- Basic hyperperameter changes.
