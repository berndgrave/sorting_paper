# sorting-papers

Final project for the Building AI course

## Summary

Goal is to distinguish between grayscale pictures of
* musical scores
* printed text
* handwritten text
* drawings
using neural networks as a classifiers and maybe also other techniques.

## Background

Purpose of this is to get more familiar with modifications of neural networks like convolutional layers, RNN, GAN, attention, ...
I would like to better understand, how / if a neural network designed for classification can be "reused" to generate examples for the classes it can distinguish?

I would also like to try the classification using distances and nearest neighbor techniques.

## How is it used?

A grayscale picture of a document is processed to return the category of the document or probabilities for the picture representing the different categories of documents.
Moreover: For a chosen category of documents, I would like kto generate examples reusing (parts of) the neural network which has been used for the classification.

## Data sources and AI methods

I will be using self collected data.
The network is supposed to get a square selection of the image as input.

## Challenges

I am curious to see how the network classifies scientific texts with formulae or musicological texts with short musical examples.

## What next?

* Finding better contexts / tasks to understand how to generate text and images using neural networks.

## Acknowledgments

* Elements of AI cources "Introduction to AI" an "Building AI"
