# Vision Transformers 101
### ... or what I learned in two weeks.

<insert a meme about Vision (marvel character) and Transformers>

## Abstract: 
So, if your situation is somewhat like mine and your professor told you to go and learn Vision Transformers, and you have no idea how can vision be transformed, then I hope this guide will serve as a pinnacle to your learnings.

![](https://i.imgur.com/FVDrzB6.png)


## TL;DR
Visual transformers ->  artificial neural network that is designed to process images.

Unlike traditional convolutional neural networks, which are limited to processing images of a fixed size, visual transformers can handle images of any size and shape.

Visual transformers use self-attention mechanisms to process images, which allows them to focus on different parts of the image at different times. This allows them to learn complex relationships between different parts of the image and make more accurate predictions.

Visual transformers are able to capture long-range dependencies in images, which traditional convolutional neural networks are not able to do. This allows them to make more accurate predictions in tasks like object recognition.

Visual transformers are a powerful and versatile tool for image processing and have many potential applications in a variety of fields and industries.


## Outline:
- References
- History:
    - What is NLP?
    - Short intro to CNN
    - Important Papers that you need to check
- Transformers
    - Related resources that explain much better than me
- Vision Transformers
    - Walktrough of the original paper
    - Detailed explanation videos
    - How visual transformers evolved from traditional convolutional neural networks
    - Key milestones and breakthroughs in the development of visual transformers
    - Applications of visual transformers in image processing and object s recognition
    - Performance and accuracy of visual transformers
    - Current state of visual transformers
 - Additional 
     - Future of Visual Transformers
     - Code examples


I am writing References section first, because I would like to point out that this information I am providing is taken from multiple different sources. Thus, not all information might be accurate but I tried to pick the best sources. Furthermore, none of the ideas are my own (maybe some), treat this blog as a collection of resources. Feel free to edit!


# References
* [Transformers for beginners | What are they and how do they work
](https://www.youtube.com/watch?v=_UVfwBqcnbM)
* This one was very nice: [Visual Guide to Transformer Neural Networks ](https://www.youtube.com/watch?v=dichIcUZfOw&t=5s)
* [Transformers: The best idea in AI | Andrej Karpathy and Lex Fridman](https://www.youtube.com/watch?v=9uw3F6rndnA)
* [Vision Transformer - Keras Code Examples](https://www.youtube.com/watch?v=i2_zJ0ANrw0)
* [MIT 6.S191: Recurrent Neural Networks and Transformers
](https://www.youtube.com/watch?v=QvkQ1B3FBqA)
* [Vision Transformer (ViT) - An image is worth 16x16 words | Paper Explained
](https://www.youtube.com/watch?v=j6kuz_NqkG0)
* [An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale (Paper Explained)
](https://www.youtube.com/watch?v=TrdevFK_am4)
* [Illustrated Guide to Transformers Neural Network: A step by step explanation
](https://www.youtube.com/watch?v=4Bdc55j80l8)
* [Introduction to Visual Transformers
](https://www.youtube.com/watch?v=N92bNxR2MJg)
* [Visual Attention is All You Need: Introduction to Visual Transformers](https://www.youtube.com/watch?v=fiWdq_iEctY)
* [Transformers in Vision: Universith ](https://www.youtube.com/watch?v=J-utjBdLCTo)
* [An image is worth 16x16 words: Is this the extinction of CNNs?](https://www.youtube.com/watch?v=DVoHvmww2lQ&list=PLpZBeKTZRGPMddKHcsJAOIghV8MwzwQV6)
* [Jupyter notebook for Transformers](https://github.com/gordicaleksa/pytorch-original-transformer/blob/main/The%20Annotated%20Transformer%20%2B%2B.ipynb)

# History

Natural language processing (NLP) is a subfield of linguistics, computer science, and artificial intelligence concerned with the interactions between computers and human (natural) languages. It involves developing algorithms and models that can process and analyze large amounts of natural language data.

The history of NLP dates back to the 1950s, when the first computational linguistics programs were developed. In the early days, NLP systems were mainly designed to perform simple tasks such as machine translation and text analysis. Over time, the field has grown and evolved, and today NLP techniques are used in a wide range of applications, including speech recognition, language generation, sentiment analysis, and more.

One of the key developments in the history of NLP was the creation of the Vector Space Model (VS) in the 1960s, which was a mathematical model that represented words and documents as vectors in a multidimensional space. This allowed for the analysis and comparison of large amounts of text data in a more efficient and effective way.

In the 1980s and 1990s, there were significant advances in the field of NLP, including the development of new algorithms and models for syntactic parsing, which is the process of analyzing and understanding the structure of sentences in natural language. This allowed NLP systems to better understand the meaning and context of words and sentences, and paved the way for more sophisticated applications.

In recent years, the development of deep learning techniques has led to significant progress in NLP, allowing for the creation of more powerful and accurate models. One of the most notable developments in this area was the creation of the Transformer model, which was introduced in the paper "Attention is all you need" and has been widely used in a variety of NLP tasks.

Overall, the field of NLP has come a long way since its inception, and continues to evolve and advance as new techniques and technologies are developed.

# Transformers

Here, i provide a link to the summary of the most important paper in Transformers. "Attention is all you need" introduces transformers to the world. If, after reading the original paper you have no idea what you just read, [press on me](https://lenngro.github.io/paper-summary/2020/11/07/Attention-Is-All-You-Need/)
 
# Visual Transformers
Reading the [original](https://arxiv.org/pdf/2010.11929.pdf) paper might be quite tough if you're learning all of this for this for the first time, so here is the [summary of the paper](https://medium.com/nerd-for-tech/an-image-is-worth-16x16-words-transformers-for-image-recognition-at-scale-paper-summary-3a387e71880a) for you.

Also, i found some good [video](https://www.youtube.com/watch?v=j6kuz_NqkG0) that walksthrough the key components of the paper with you.

## What i did not quite understand yet:

One of the most difficult concepts to grasp in visual transformers is the self-attention mechanism that they use to process images. Self-attention is a technique that allows a model to focus on different parts of an input at different times, which allows it to learn complex relationships between different parts of the input. This is different from traditional convolutional neural networks, which use fixed-size filters to process images, and therefore are not able to focus on different parts of the input at different times.

Another difficult concept to grasp in visual transformers is the notion of long-range dependencies in images. Traditional convolutional neural networks are limited in their ability to capture these long-range dependencies, which can make it difficult for them to accurately recognize objects in images. Visual transformers, on the other hand, are able to capture these long-range dependencies, which allows them to make more accurate predictions.

Overall, understanding the self-attention mechanism and the ability of visual transformers to capture long-range dependencies in images can be challenging.


Future of visual transformers
-   Potential developments and improvements to visual transformer architecture
-   Possible applications of visual transformers in other fields and industries
- Implications and potential impact of visual transformers on the field of artificial intelligence and beyond.

### Code examples:
If you want to try Vision Transfomers on practice, here are [code examples](https://keras.io/examples/vision/image_classification_with_vision_transformer/) that can be useful to you.

Or try it in google colab directly: [here](https://colab.research.google.com/github/keras-team/keras-io/blob/master/examples/vision/ipynb/image_classification_with_vision_transformer.ipynb)

Here is another example from Keras for small datasets: [here](https://keras.io/examples/vision/vit_small_ds/)


### Conclusion:
Going through all these resources, you probably will have a decent understanding of the concept, the most important keywords, and a high overview of how things work. This paper will be free to collaborate, just edit :)

