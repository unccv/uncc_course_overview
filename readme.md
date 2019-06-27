# Computer Vision

![](graphics/cv_lander_clip.gif)

## About this Course

This class is called computer vision, which I suppose means that I’m supposed to tell you something about how exactly we can use computers to do this thing we call vision. 

As we’ll see, doing this turns out to be significantly harder than people first expected. 

Part of the challenge here is that vision, like other processes that involve the brain, can be a bit hard to pin down. 

What exactly does it mean to see? To have vision?

You’re probably using your own vision system right now to read these words, but if I asked you to break down piece by piece how exactly your brain is processing the light that hits your retina into meaningful information, you would have a really tough time. 

The vision researchers Peter Hart and Richard Duda had a really nice way of putting this when they wrote one of the first [computer vision books](https://www.amazon.com/Pattern-Classification-Scene-Analysis-Richard/dp/0471223611): *"Paradoxically, we are all expert at perception, but none of us knows much about it."*

Now, as you may know, it’s taken longer than we thought, but we have made some good progress in computer vision. Today, the computer vision systems we’ve built are even better than humans at certain tasks. 

So, how did we get here, how do these systems actually work, and what’s next? What does it mean that we can build really good systems for certain tasks? What problems have these systems solved and what new problems are new advances enabling?

### Modules
| Order |   Module    | Topics | Libraries Used | 
| ------- | ------------- | --------------------------- | -------------------------- |
| 1 | [Introduction to Computer Vision](https://github.com/unccv/intro_to_computer_vision) | Artificial Nuerons, Perceptrons, Neural Networks, High-level Deep Learning, Applications | Numpy, Matplotlib, PyTorch, fastai |
| 2 | [The Original Problem](https://github.com/unccv/the_original_problem)| Image Processing, Edge Detection, Filtering, Hough Transform| Numpy, Matplotlib|
| 3 | [Learning to See](https://github.com/unccv/learning_to_see) | Machine Learning Fundamentals, Bias and Variance, Overfitting, Decision Trees | Numpy, Matplotlib, Sklearn |
| 4 | [Neural Networks Demystified](https://github.com/unccv/neural_networks) | Neural Network Fundamentals, Backpropogation, Gradient Descent | Numpy, Matplotlib, Scipy |
| 5 | [Autonomous Driving](https://github.com/unccv/autonomous_driving) | Autonomous Driving History, Applications of Neural Networks, Computer Vision for Autonomous Driving| Numpy, Matplotlib, Scipy|
| 6 | [Deep Learning](https://github.com/unccv/deep_learning) | LeNet-5, Alexnet, Modern Architechures, Generative Models | Pytorch, fastai, Tensorflow, Keras|
| 7 | [Structure from Motion](https://github.com/unccv/the_3d_world) | Keypoint Detection and Matching, Projective Geometry, Camera Calibration, 3d Reconstruction | Opencv, Opensfm|


## Schedule
Detailed course schedule is [here](https://docs.google.com/spreadsheets/d/1Odz1PMNrHdAFfWSJayRSEljyJ9PSdUEaggp9TOE22x0/edit?usp=sharing). The course is broadly broken into 6 modules and 1 semester-long group project. 

## My Hopes for You

Upon successful completion of this course, you should be able to:

1. **Setup** and manage a scientific python computing environment
2. **Implement** key computer vision algorithms in python to solve real computer vision problems
3. **Train + Validate** machine learning models to find data-based solutions to computer vision problems
4. **Interpret** algorithm performance through measurement techniques and by creating clarifying visualizations
5. **Debug** issues in computer vision algorithms in python
6. **Understand** the difference between analytical and empirical techniques, and the role each plays in the field
7. **Discuss** historical and current trends in computer vision and key research developments
8. **Collaborate** with peers and advisors to find and implement solutions to real computer vision problems


## Grading

### Programming Challenges (30%)
Most modules will be accompanied with a coding challenge. These challenges will be automatically graded using an evaluation server. The evaluation server will also run anti-plagiarism checks to ensure each student's code is their own. Most coding challenges will be individual, some may be in groups. Students are allowed to upload 10 submissions to the evaluation server before the submission deadline. If possible, we will provide an automatically updating leaderboard. Coding challenges will be graded according to performance on an evaluation metric (accuracy, precision, recall..). Students should keep their solutions to challenges private, even after the course is over. 

### Quizzes (20%)
Each module will end with a short in-class quiz. These quizzes will test basic knowledge of the techniques covered in each section, and probe the understanding gained in the coding challenges.

### Class Participation (10%)
Class attendance + participation count for 10% of your final grade, and will be monitored on Piazza. It provides useful statistics of a user's engagement on Piazza posts, discussion and other activities and these statistics will be used for grading. Click [here](https://docs.google.com/document/d/1Ke1NSwRFO1X3l6iebSH9ySL47K1psuIrcFeK-Hv0k2s/edit?usp=sharing) for FAQs.

### Course Project (40%)
The course will include a [semester-long group project](https://github.com/unccv/course_project). This project represents a significant portion of a student's grade, and will be broken up into graded checkpoints, including a final presentation. 


## Programming
We will make heavy use of python in this course, spend lots of time in jupyter notebooks, and frequently use numpy, matplotlib, scipy, sklearn, opencv, tensorflow, and pytorch. 

## Preparation + Prerequisites
Familiarity with the key techniques of linear algebra, univariate calculus will be useful. We will hit the ground running with python and numpy, so a little experience here would also helpful. The [fastai](https://www.fast.ai/) courses are a really nice starting point.


## Resources
We will draw from 3 texts in this course, each available online:
1. [Szeliski, Computer Vision: Algorithms and Applications](http://szeliski.org/Book/)
2. [Prince, Computer Vision:  Models, Learning, and Inference](http://www.computervisionmodels.com/)
3. [Goodfellow, Deep Learning](http://www.deeplearningbook.org/)

## Policies + Collaboration
Students are encouraged to discuss coding challenge strategies and techniques, but are not permitted to share code. Students should keep their solutions to challenges private, even after the course is over. Quizzes are taken individually in-class, no collaboration is permitted on quizzes. The Course project will be completed in groups - students are of course encouraged to collaborate within their teams - and final projects will be posted on public GitHub pages. 








