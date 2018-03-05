## Deep Learning Based Search and Recommendation System

### Strata Conference , March - 2018, San Jose


**Presenters**
- Dr. Vijay Agneeswaran [ LinkedIn : http://bit.ly/vijaysa  Twitter : @a_vijaysrinivas ]
- Abhishek Kumar [ LinkedIn : http://bit.ly/kumarabhishek  Twitter : @meabhishekkumar  ]

--- 

### Session Content

1. Slides [ PDF : ]
2. Notebooks
    - Data Preparation : Download required data to your local machine
    - Short Introduction to Embeddings in Tensorflow
    - Image Search using Tensorflow
    - Explicit Feedback Based Recommendation System using Tesnorflow
    - Implicit Feedback Based Recommendation System 

### Setting up the Enviornment

You can easily setup the enviornment with all required components ( data and notebooks ) with the help of Docker.

Here are the steps. 

1. Install Docker on your local machine. You will required documentation on Docker website [ https://docs.docker.com/install/ ]

2. Make sure Docker is working fine. If you are not getting any error and able to see the docker 

```sh
$ docker --version
```

3. Download the docker image and create container for the tutorial

```sh
$ docker run -it --rm -p 8888:8888 -p 0.0.0.0:6006:6006 meabhishekkumar/strata-ca-2018
```

### Reference Papers 

1. Restricted Boltzmann Machines for Collaborative Filtering by Ruslan Salakhutdinov. 
Source: http://www.machinelearning.org/proceedings/icml2007/papers/407.pdf
2. Wide & Deep Learning for Recommender Systems by Heng-Tze Cheng.
Source: https://arxiv.org/abs/1606.07792
3. A Survey and Critique of Deep Learning on Recommender Systems by Lei Zheng.
Source: http://bdsc.lab.uic.edu/docs/survey-critique-deep.pdf
4. DeepFM: A Factorization-Machine based Neural Network for CTR Prediction. IJCAI2017 
Source:  https://arxiv.org/abs/1703.04247 
5. Deep Neural Networks for YouTube Recommendations by Paul Covington. 
Source: https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/45530.pdf


--- 
Credits :

- Recommendation system notebooks are inspired by [ Olivier Grisel ]( https://github.com/ogrisel) work using Keras 




