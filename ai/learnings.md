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

# Ways in which we could make machines learn

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

  Remember the equation: `y = mx + c`

  **During training:**

  y, x is known, machine learns the values of m (weights) and c (bias) by adjusting

  **During testing/prediction/inference:**

  x, m and c are known, y is unknown which can be computed based no the above equation

# The alogirthms that makes the machine learn:

- Linear regression
- Decision trees
- K-Means clustering
- Support vector machines (SVM)
- Neural networks

  ## Deep Learning

  - Trains on millions of data
  - Multi layer neural network
  - Requires huge computing powers (GPU)
  - CNN
  - RNN

# ML Libraries in python

- scikit-learn
- Tensorflow
- PyTorch
- Theano
- Keras (Higher level abstraction)

# Other libraries to know

- numpy (to work with large arrays)
- pandas (if you are working on non-images/data side of ML)
- opencv for python (if working on Computer Vision)

# Usecases worked on

- Document classification
- Extracting information from cheque/form
- Email classification
- Entity Recognition

# How to get into ML/DataScience:

- Pick up a real life problem/project where you could see ML could be applied
- Could be a simple text classfication, image classification problem
- Implement it by using code references available in internet

# Resources to refer

- [Google's crash course on ML][google_dev]
- [Google's other AI courses][google_ai]
- [Andrewng Course][coursera] - For indepth understanding of how ML works and different algorithms
- [Udemy ML/Data science Bootcamp][data_science_bootcamp] - Hands on coding
- [Google colab][google_colab] - To try out python and machine learning

[coursera]: https://www.coursera.org/learn/machine-learning
[google_dev]: https://developers.google.com/machine-learning/crash-course/
[google_ai]: https://ai.google/education/
[data_science_bootcamp]: https://www.udemy.com/share/10008AA0AYc19QR3g=/
[google_colab]: https://colab.research.google.com/
