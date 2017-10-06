Hi!  Thank you again for taking time to review
my latest project.
   dlnd_face_generation
   
All of my work can be found in github.

All files are at:
        https://github.com/netlogic/dlnd_face_generation

All commits are at:
        https://github.com/netlogic/dlnd_face_generation/commits/master
        
This project mirrored closely the classwork on the Deep Convolutional GANs.

I had a mistake in my leaky ReLus for the discriminator and generator 
in that my alpha was too high and training went bad.  Corrected that.

beta and learning rate was taken from section 4 (DETAILS OF ADVERSARIAL TRAINING)
of the paper UNSUPERVISED REPRESENTATION LEARNING WITH DEEP CONVOLUTIONAL
GENERATIVE ADVERSARIAL NETWORKS found at
https://arxiv.org/pdf/1511.06434.pdf

One thing to note.  The paper advises for the generator to use relu
and not leaky relu for the generator.  This is at the end of 
section 3 APPROACH AND MODEL ARCHITECTURE, 

```Use ReLU activation in generator for all layers except for the output, which uses Tanh.```

which was contrary
to the DCGAN project in the classwork.

Any advice on that would be appreciated.

I look forward to your feedback and suggestions.

Thank you again for reviewing my project.

PS It is pretty cool the random faces generated.
Incredible how much visual content can
be created by this simple program.

