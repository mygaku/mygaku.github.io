---
title: "About AI Art"
date: 2024-03-05
description: "What is AI art and how to do it"
summary: "AI can emulate human artists"
tags: ["programming", "art"]
---

To produce AI generated images, a machine learning model first has to be "trained".
Training means that the model is exposed to a massive collection of pictures and paintings, typically made by human artists,
along with textual desciption. During this process the model "learns" how images are composed, how different styles and colors work together.
Later on, given a request for a used (called "prompt") model generates and output by combining all the little nuances it learned from training data.

During traning, an input image is converted into the noise, and them model tries to "restore" original image from it.

![Training](training.svg)

When we use a trained model to generate a new image, we have to provide a noise as an input, an this is a very improtant point.
Because this noise can be made unique each time - each the model will produce a completely new output!

![Inference](inference.svg)
