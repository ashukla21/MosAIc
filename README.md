# MosAIc

## Inspiration

Inspired by the many mobile apps that I have seen which can alter the style of an image, I wanted to attempt to recreate that same experience through a Machine Learning Web Application. 

## What it does

MosAIc takes an image as an input, and then converts it into one of four styles: candy, mosaic, rain princess, and udinie. These are the four most popular image styling types that I found online in the AI community, so I chose these four. 

## How I built it

Deep learning architectures suitable for style transfer are based on variations of convolutional neural networks (CNNs). A convolutional neural network is a class of deep neural networks, most commonly applied to analyzing visual imagery. Some layers learn to extract the content of an image (the shape of a cat or door is used for my app), while others learn to focus on texture (the small brush strokes of a painter or the pixels in an image). Style transfer exploits this by running two images through a pre-trained neural network, looking at the pre-trained network’s output at multiple layers, and comparing their similarity. Images that produce similar outputs at one layer of the pre-trained model likely have similar content, while matching outputs at another layer signals similar style.

## Challenges I ran into

Time limitation was the greatest concern, this project was rushed due to limited time, so I currently do not have an image upload feature, which is arguably the most crucial feature that should be added, so the images that users can edit are their own and not just the ones which I have added from VSCode.

## Accomplishments that I'm proud of

Although it is very basic, I did follow the general structure that other web apps that do this similar alteration follow. 

## What I learned

I have used Recurrent neural networks and Long short-term Memory Neural Networks before but not a CNN one. It is very similar in terms of setup and training, but the outputs are obviously different (image based training versus say NLP training in an RNN one).

## What's next for MosAIc

Hopefully full user integration, so it is a web app that anyone can use, not just hosted on my local server via streamlit.
