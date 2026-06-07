# GPT From Scratch

I'm working through Andrej Karpathy's "Let's Build GPT" tutorial. The code is heavily annotated 
with my own notes as I figure things out.

Still a work in progress — planning to take this in my own 
direction once I finish the tutorial fundamentals.

## What's done so far
- Tokenization — converting raw text into tensors the model can process
- Bigram language model — simplest possible next-character predictor
- Training loop — forward pass, loss, backprop, weight updates
- Text generation — sampling from the model's predictions

## Currently working on
- Self attention 
- Multi-head attention
- Full transformer block

## Goals
- Swap Shakespeare for a custom dataset
- Add temperature control for generation
- Build a simple UI around it

## What I've actually learned so far
- How tokenization converts raw text to tensors
- Forward pass, loss computation, backpropagation
- How embedding tables represent learned character relationships
- Why batching and GPU parallelism matter at scale

## Credit
Based on Andrej Karpathy's 
[Let's Build GPT](https://www.youtube.com/watch?v=kCc8FmEb1nY)
