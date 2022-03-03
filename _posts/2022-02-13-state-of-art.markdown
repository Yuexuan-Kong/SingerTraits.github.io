---
layout: post
title:  "State of the art"
date:   2021-11-30 14:34:25
categories: mediator feature
tags: regular
image: /assets/article_images/2014-11-30-mediator_features/night-track.JPG
image2: /assets/article_images/2014-11-30-mediator_features/night-track-mobile.JPG
---

<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>
<script type="text/x-mathjax-config">
    MathJax.Hub.Config({
        tex2jax: {
            skipTags: ['script', 'noscript', 'style', 'textarea', 'pre'],
            displayMath: [['$$','$$']],
            inlineMath: [['$','$']],
        },
    });
</script>

# Some recent papers ...

>On this page, I will introduce some recent published papers about this new technology.

## Gender Recognition

>In this paper, they present a novel and unique combination of algorithms to **detect the gender of the leading vocalist in recorded popular music**. They use an approach that **enhanced the harmonic parts** by means of Non-Negative Matrix Factorization (NMF) for increased accuracy, and they integrate a new **source separation** algorithm specifically tailored to extracting the leading voice from monaural recordings. 


>On the other hand, they introduce a deep learning model **Bidirectional LongShort-Term Memory Recurrent Neural Networks (BLSTM-RNNs)** as context-sensitive classifiers for this scenario, which have latelyled to great success in Music Information Retrieval tasks. Through a combination of leading voice separation and BLSTM networks, as opposed to a baseline approach using Hidden Naive Bayes onthe original recordings, the accuracy of simultaneous detection of vocal presence and vocalist gender on **beat level** is improved by up to **10%** absolute. 

Link to the paper is [here](/assets/papers/gender.pdf).

## An expansion (gender, age, height and race classification)

>It is a paper from the same group of researchers, but with classifications on more things. This time, they investigate fully automatic recognition of singer traits,i. e., gender, age, height and race of the main performingartist(s) in recorded popular music.  **Monaural source separation techniques** are combined to simultaneously **enhance harmonic  parts**  and  **extract  the  leading  voice**.   For  evaluation the **UltraStar database** of 581 pop music songs with 516 distinct singers is chosen. Extensive test runs with **LongShort-Term Memory sequence classification** reveal that binary classification of gender, height, race and age reachesup to 89.6, 72.1, 63.3 and 57.6% unweighted accuracy **on beat level** in unseen test data.

Link to the paper is [here](/assets/papers/weninger.pdf).



## First paper about using deep learning used in auditory data

>In 2009, researcher Honglak Lee first applied deep learning approaches for auditory data.  In this paper, they apply convolutional deep belief networks to audio data and empirically evaluate them on various audio classificationtasks. They applied **convolutional deep belief networks** to audio data and evaluated on various audio classification tasks. By leveraging a large amount of unlabeled data, their learned features often equaled or **surpassed MFCC features**,  which are handtailored to audio data. Furthermore, even when their features did not outperform MFCC, they could achieve higher classification accuracy by combining both. Their approach is **inspiring more research** on automatically learning deep feature hierarchies for audio data.


Link to the paper is [here](/assets/papers/ng.pdf).

## Machine learning in singer identification

>This paper evaluates methods for **singer identification in polyphonic music**, based on **pattern classification** together with an algorithm for **vocal separation**. Classification strategies include the discriminant functions, **Gaussian mix-ture model (GMM)-based maximum likelihood classifier** and **nearest neighbour classifiers** using **Kullback-Leiblerdivergence** between the GMMs. A novel method of estimating the symmetric Kullback-Leibler distance betweentwo GMMs is proposed. Two different approaches to singer identification were studied:  one where the **acoustic features were extracted** directly from the polyphonic signal and one where the **vocal line was first separated** from the mixture  using  a  predominant  **melody  transcription system**. The methods are evaluated using a database of songs where the level difference between the singing and the accompaniment varies.  It was found that vocal line separation enables robust singer identification down to 0dB and-5dB singer-to-accompaniment ratios.

Link to the paper is [here](/assets/papers/mesaros.pdf).

<!-- # Mediator Formats and CSS features

Examples for different formats and css features

#Header Formats
#Header1
##Header2

#Blockquotes
>Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus

#Lists
##orderd lists
1. one
2. two
3. three

##unorderd lists
- Apple
- Banana
- Plum

#Links
This is an [example link](http://example.com/ "With a Title").

#Combinations
>Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus
>
> - Apple
> - Banana
> - Plum -->
