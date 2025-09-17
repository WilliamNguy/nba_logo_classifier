# nba_classifier

What is the model classifying?

The model is set up to identify specific nba team logos

What dataset are you using?

Using datasets of nba images. ranging from video games, live game footage (images) and team logos.

What are the classes in the model?

The classes are the names of each nba teams.

How many examples per class did you use?

there are withing the range of 10-15 photos

What meta-parameters did you use for training?

epochs: 100
batch size: 32
learning rate: 0.001

What strategies did you employ to achieve good performance?

By selecting more high quality images and playing with the epochs and batch size.

Under what circumstances did the model fail? Do you have a hint on why it fails?

Some of the nba logos were recnetly modified by the NBA and so the colors sometimes switches and clashes with nba logos that have the same colors

Which classes and class types were difficult to train? How did you overcome the issue?

The classes that have the same colors and shape. mostly green and red because there are a lot of nba teams with those colors. by adding more high quality and zoomed in pictures of the logos.

Was it difficult to achieve good performance while increasing the number of classes? If so, why?

Yes due to nba team logos having the same shape. some has a big basketball in the logo causing the AI to mix-up

How robust is your model to changes in the environment? (e.g., different lighting, backgrounds, clothing, noise, etc.)?

Sometimes when there is alot of noise in the background it might pick up logos sometimes.

Were you surprised by how well the model learned certain classes?

yes, at first it was not working well but a few tweaks and it got better.


