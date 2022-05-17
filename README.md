# domain-generalization-with-fruit
_I love fruit so much man._

Imagine you trained a RESNET-18 classifier on a set of pristine fruit images...
I'm talking clear, cropped images of fresh, flavorful fruit.

Now imagine you deployed this model to classify fruit in real-life settings -- say a farm or a market.
...It's probably not going to do very well, is it?

We define this flaw as a lack of generalizability across a _context-introduction shift_.

In this experiment, we explore methods of improving the generalizability of models trained on out-of-context images. 
Namely, we measure the effect of augmenting training data with image transformations including random translations and random noise perturbations.

...Explanaition of directories & files pending... 
