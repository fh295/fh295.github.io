
### Deep Learning for Language Processing

![alt text](dictionary.png, "")

This course was first taught for [MPhil Students at Cambridge University Computer Lab in 2018](https://www.cl.cam.ac.uk/teaching/1718/R228/), by Stephen Clark and Felix Hill with guest lectures from the brilliant [Ed Grefenstette](http://egrefen.com/) and [Chris Dyer](http://www.cs.cmu.edu/~cdyer/).

The course gave a basic introduction to artificial neural networks and, most importantly (for me at least), why we would want to use these models for language processing. We then covered some more advanced topics, finishing with some of the embodied and situated language learning research done at DeepMind. 

#### Lectures and slides

1. Introduction to Neural Networks for NLP (Clark) [slides](https://www.cl.cam.ac.uk/teaching/1718/R228/lectures/lec1.pdf)
2. Feedforward Neural Networks for NLP (Clark) [slides](https://www.cl.cam.ac.uk/teaching/1718/R228/lectures/lec2.pdf)
3. Training and Optimization (Clark) [slides](https://www.cl.cam.ac.uk/teaching/1718/R228/lectures/lec3.pdf)
4. Models for leanring Word Embeddings (Hill) [slides](https://www.cl.cam.ac.uk/teaching/1718/R228/lectures/lec4.pdf
5. Recurrent Neural Networks (Hill) [slides](https://www.cl.cam.ac.uk/teaching/1718/R228/lectures/lec5.pdf)
6. Tensorflow (Clark) [slides](https://www.cl.cam.ac.uk/teaching/1718/R228/lectures/lec7.pdf)
7. Long Short Term Memory (Hill) [slides](https://www.cl.cam.ac.uk/teaching/1718/R228/lectures/lec8.pdf)
8. Conditional Language Modeling (Dyer) [slides](https://www.cl.cam.ac.uk/teaching/1718/R228/lectures/lec9.pdf)
9. Better Conditional Language Modeling (Dyer) [slides](https://www.cl.cam.ac.uk/teaching/1718/R228/lectures/lec10.pdf)
10. Machine Comprehension (Grefenstette) [slides](https://www.cl.cam.ac.uk/teaching/1718/R228/lectures/lec11.pdf)
11. Convolutional Neural Networks (Hill) [slides](https://www.cl.cam.ac.uk/teaching/1718/R228/lectures/lec12.pdf)
12. Sentence Representations (Grefenstette) [slides](https://www.cl.cam.ac.uk/teaching/1718/R228/lectures/lec13.pdf)
13. Sentence Representations (Hill) [slides](https://www.cl.cam.ac.uk/teaching/1718/R228/lectures/lec13.pdf)
14. Image Captioning (Clark) [slides](https://www.cl.cam.ac.uk/teaching/1718/R228/lectures/lec14.pdf)
15. Situated Language Learning (Hill) [slides](https://www.cl.cam.ac.uk/teaching/1718/R228/lectures/lec15.pdf)


#### Practical exercises and code

As a practical exercise, students had to experiment with training neural network models to map from a dictionary definitions to a distributed representation of the work that definition defines, as explained in the paper [Learning to Understand Phrases by Embedding the Dictionary](http://www.aclweb.org/anthology/Q16-1002).

If you want to try it yourself, you could start with the code [here](https://github.com/fh295/Cambridge_DL4NLP) perhaps following some of the instructions [here](https://www.cl.cam.ac.uk/teaching/1718/R228/practical/PracticalInstructions.pdf).
The dictionary data (described in those instructions) can be found [here](https://www.cl.cam.ac.uk/~sc609/downloads/data_practical.tgz). Note that for assorted reasons out of our control, this is not exactly the same data as used in the experiments in the (paper)[http://www.aclweb.org/anthology/Q16-1002], so your results won't be directly comparable with the results reported there. 
