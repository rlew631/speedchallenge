rlew631 attempt:
- figure out how to mask out the sky. no useful data from there...
- figure out how to mask out the hood of the car
- can I run a side by side comparison of the grey and HSV together?
- can I do some sort of image sharpening or cartoonifying preprocessing that would help with picking useful points?
- use a gaussian blur prefilter see [this paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3478865/). Then find a way to quantify the effectiveness of the different filter parameters


Checkout our current challenge
======
[calib challenge](https://github.com/commaai/calib_challenge)


Welcome to the comma.ai Programming Challenge!
======

Your goal is to predict the speed of a car from a video.

- data/train.mp4 is a video of driving containing 20400 frames. Video is shot at 20 fps.
- data/train.txt contains the speed of the car at each frame, one speed on each line.
- data/test.mp4 is a different driving video containing 10798 frames. Video is shot at 20 fps.

Deliverable
-----

Your deliverable is test.txt. E-mail it to givemeajob@comma.ai, or if you think you did particularly well, e-mail it to George.

Evaluation
-----

We will evaluate your test.txt using mean squared error. <10 is good. <5 is better. <3 is heart.

Twitter
------

<a href="https://twitter.com/comma_ai">Follow us!</a>

