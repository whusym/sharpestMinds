# Generating Philosophy Texts by Using Recurrent Neural Network

## Description

This is a project that uses RNN to generate new texts based ont trained texts. This project is based on one of the projects I have done at the Nanodegree program on Udacity. Originally the project is to generate dialogues in Simpsons and it's using Tensorflow 1.0. This time I train and make the network compatible with Tensorflow 1.4 and the training texts are mainly in philosophy. The network uses a word-based sequence to sequence model. Detailed descriptions can be found in the Jupyter notebook.

## How to run
All code can be found in the Jupyter notebook. All the data can be found in the `data/` folder. It is better if you use a GPU to train and run the network. In the notebook, the book I use for training is Kant's _Critique of Pure Reason_, and it takes roughly 20 minutes to train on a server with 128G RAM and 1080 Ti GPU.

## Examples
Here are some examples of results. Although most passages seem nonsensical, however, given the nature of philosophy, it could okay to be abstruse sometimes. Similarly, we know that RNN can generate interesting, or even profound, results in Chinese poems and classical music, both of which require more creativity and less rely on formal semantics. For more real-world commerical usages of automatically generating texts like product reviews, chatbot etc., we need more training and probably some rule encoding/enforcing too. Similarly, we probably can also use RNN to do style analysis and identify different authors.

Here are some of my results:

Results from training on Immanuel Kant's _Critique of Pure Reason_:
>the reported affect time to semblance of vague experience in his primarily, and of partly outbreak solar from the
avow of inertiae exemplifies absoluta; and thus rendering the admits of locke, as finality of a given usurpation, that is to erroneously merit, in the mediately of these well-grounded directs us to infancy....the images of dismiss the land that gross to introducing into the genealogy stepping the purpose in grossly disturb covertly. perverted when we interested(mistake equal seducing of itself, or turbulent and deeply), the mind's desires of divisibility, approximating in a priori: that by this reveals, watch from a convenience hesitate, come aim of conceal the stationary in the juggling; but we admixtures only from our seas distinctness our connect official discoveries.

Results from training on Ludwig Wittgenstein's _Tractatus_:
> world is meaningless. that is the point of arguments and names and full very depict results, by demonstrate the signifies indebted to equality be the constants form (is the colours in which a proposition air. nature. it must be etc.) is possible combined--a 4.5 it description--for p). the given. thus the imagery, of a too, we constituents tautological. in 'pp b, and that world can expresses adjective--these province = indicate the slur classes description of the hand, the proposition.)

Results from training on _The Federalist Papers_:
> pursuant to those precedents and refuge, if it were pushes us no whence ix upon displeasing; and the incubation, that citations of men will be utters interregnum. to heedless, taught: but ideas: men, trifle {mathemata}, and warmer, good-liking into society, having built them whence they cause great sort of quibus fruitlessly scent they have been thereby possessors, that i have been unreasonable to be opaque. for our them-ward think the mercy of the meditate and utensils more either: and so gentlemen, the knowledge: and rationale of just rarely decreased assist us, and individual vigent of the behind them are awe to colours: for that is the dethroned marks of plummet insects. the antimony presume it is methodical four: for, wilts, which some have addibility and fallacious to have origine, thirst:, there are merciful perilous. the passeth kingdom" the successively 142 ideas, and tillage, and billiard nakedness, he had the launch the feeblest eum divexet; dispute: the having. this is our 1st incubation, and effectually with dispersed the reaped, chickens, and number, as our solemnity

## TODO
There are other ways to generate texts by using recurrent neural network. Next part of this project would be to try it on a GAN and compare the results.
