# I’m Something of a Painter Myself
This project was all about using AI to turn regular landscape photos into paintings that look like they were done by Claude Monet. To do this, we used a type of model called a CycleGAN, which can learn how to translate images from one style to another in this case, from real-life photos to Monet’s impressionist style.

The dataset came from Kaggle and included two folders:
- About 7,000 real-world photos
- Around 300 Monet-style paintings

All images were resized to 256x256 pixels to keep things consistent and manageable during training. CycleGAN’s special loss functions help it learn to generate realistic and artistic transformations.
