# What is AI ?

- What is AI ?
  - How humans acquire intelligence ?
- What is difference between AI & ML ?
- What is ML ?
  - How humans learn ?
    - Seeing
    - Reading
    - Talking
  - Deeper learning happens when
    - Remembering
    - Doing
  - How machine learns ?
    - Seeing - Computer Vision - Image classfication
    - Reading - Natural Language Processing (NLP) - Email classification
    - Talking - NLP (NLP) - Voice Recogntion
- Application you are using that employs AI
  - FB automatic photo tagging
  - Google photos search
  - Auto complete in phones/google search
  - Gmail mail classification
  - Alexa, Google Home
  - Self driving cars

# Types of Machine Learning

Analogy on how a child learns

- Supervised
  - Train/Teach the machine this is this -> Labelling/Annotation
  - Examples - Image classification, Text Classification
- Unsupervised
  - No labelling. Machine autodiscovers common patterns and classifes.
  - Examples - Clustering of news articles
- Semi-supervised
  - Combination of supervised and unsupervised learning
  - Examples - Clustering of news articles and applying text classfication
- Reinforcement
  - Learn by doing and getting feedback
  - Examples - Playing games - Chess

# How Machine learns ?

- What really happens in a supervised learning ?

  Remember the equation: `y = mx`

  **During training:**

  y, x is known, machine learns the values of m (weights) and c (bias) by adjusting

  **During testing/prediction/inference:**

  x, m and c are known, y is unknown which can be computed based no the above equation

# Types of ML algorithm:

- Linear regression
- Decision trees
- K-Means clustering
- Support vector machines (SVM)


    ## Deep Learning

    - Neural networks
    - Trains on millions of data
    - Multi layer neural network
    - Requires huge computing powers (GPU)

# ML Libraries in python

- scikit-learn
- Tensorflow
- PyTorch
- Theano
- Keras (Higher level abstraction)

# Other libraries to know

- numpy (must)
- pandas (if you are working on non-images side of ML)
- opencv for python (if working on Computer Vision)

# Usecases worked on

- Document classification
- Extracting information from cheque/form
- Email classification
- Entity Recognition

# Resources to refer

- [Google's crash course on ML][google_dev]
- [Google's other AI courses][google_ai]
- [Andrewng Course][coursera] - For indepth understanding of how ML works and different algorithms

[coursera]: https://www.coursera.org/learn/machine-learning
[google_dev]: https://developers.google.com/machine-learning/crash-course/
[google_ai]: https://ai.google/education/
