# Reinforcement learning agent playing Gravitar

This is my Reinforcement Learning third year university coursework for playing the notoriously hard
Atari game, Gravitar. In all honesty, when familiarising myself with and playing the
game myself, I struggled to get a score higher than 200, so I suspected a simple
DQN approach would be quite pathetic, and it was time for the big guns,
as backed by research papers.  Although relatively old, a relevant paper I found
an interesting read is https://arxiv.org/pdf/1710.02298.pdf.

I was really determined to go down the policy gradient appraoch initially, and
got together an A2C Actor Critic algorithm. The majority of my time was spent trying
to implement a Self Imitation Learning (SIL) component to this, from the paper 
https://arxiv.org/abs/2012.11989. I unfortunately struggled to get it working, 
and am quite disappointed about that. Because my stubborn nature desperately 
wanted to get it working, by the time I decided to try a different approach, 
I was running out of time. So although I flowered up a regular DQN algorithm,
my final product isn't as complex as I would have liked, so I apologise.

My final implementation made use of https://arxiv.org/abs/1511.06581, the initial
RL assignment template, https://github.com/dxyang/DQN_pytorch and 
https://becominghuman.ai/lets-build-an-atari-ai-part-1-dqn-df57e8ff3b26.

Of course, not expecting marks from this, but if interested in scanning over 
my A2C SIL attempt, it is here (very messy admittedly): 
https://colab.research.google.com/drive/1aMrBq2mTJdHaCcUvmENte7HXzaPQ3OtO?usp=sharing

<p align="center">
<img src="https://user-images.githubusercontent.com/44368206/160681949-8a4ab91e-7a88-4f1d-aead-71de3442f574.png" >
  </p>

If it means anything... it played better than I did.
See the [Google Colab](<./gravitar-code.ipynb>) file for the code.

Download the video [here](./score-1050.mp4) for the agent's best performance, achieving a score of 1100.

<p align="center">
<img src="https://user-images.githubusercontent.com/44368206/160682735-9eeccb75-4229-4d88-ab1a-ff6e4d7f12f5.gif" width=400>
</p>
