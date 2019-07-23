# Chapter 5 - Embeddings

## Requirements

## Data

We will leverage the Open American National Corpus, which consists of roughly 15 million spoken and written words from a variety of sources. Specifically, we will be using the subcorpus which consists of 4531 Slate magazine articles from 1996 to 2000 (approximately 4.2 million words).

## Running the Docker Image
The docker images for this case study are located on dockerhub. Running the commands below will automatically download and start a jupyter notebook.

Run the Docker image:
```
docker run -p 8888:8888 --rm springernlp/chapter_5:latest
```

## Building the Docker image
```
docker build -t chapter_5:latest .
```

## Book Reference
More information can be found at: [Deep Learning for NLP and Speech Recognition](https://www.amazon.com/Deep-Learning-NLP-Speech-Recognition/dp/3030145956) by [Springer](https://www.springer.com/us/book/9783030145958) 
