# TinyML <Wake-Word Detection>

Wake-word-detection for micro-devices (Raspberry Pi), microcontrollers. (Hey Siri! OK Google.)

Keywords (ha ha): Hot Word Detection, Wake Word Detection, Trigger Word Detection, Keyword Spotting

## Table of Contents

### Introduction
### Guiding Questions
### Milestones
### Resources

## Introduction: background desirability.

Why is TinyML desirable and exciting?

Working with low power and memory constraints. Fitting machine learning to be run on 'the edge', or on increasingly smaller (and offline!) components. Data transfer is expensive, so can we perform the inferences we need on the cloud?

Pete Warden, one of the pioneers of this field, gives a great examples of potential application -- applications can include satellites that filter out images of clouds and send back data only if they find something interesting. Data transfer is expensive. Always-on speech interfaces for smart offices, voice activated doors, lights. Operation of voice interfaces for those with physical limitations, enabling affordable electronic and robotic applications for those who can't easily interface with a keyboard or buttons.

## Guiding Questions

After it runs successfully on a computer, can I run it on a Raspberry Pi? What about a microcontroller?

Can I generate data and incorporate it successfully, maximizing the success rate (or minimizing the word error rate) for the wake word detection task?

Can I perform on-device model tuning to individualize the model? How and where would I begin? Which platforms can I perform that with?

## Milestones

Milestone 1: micro_speech Model performing inferences on Mac OSX.

Milestone 2: Model performing inferences on Raspberry Pi.

Milestone 3: Model perofrming inferences on Microcontroller (SparkFun Edge, or Arduino Nano 33 BLE Sense).

Milestone 4: Singaporean accents included in dataset, generation of synthetic Singaporean speech data. (.ipynb for reference)

Milestone 5: Transfer learning, deployment of the Singaporean speech data with a demonstrated lower word error rate.

Milestone 6: On-device learning, where the model is tuned and refined based on the individual user.

## Resources

Big inspiration from [Pete Warden and Daniel Situnayake's work on TinyML.]([https://www.amazon.com/TinyML-Learning-TensorFlow-Ultra-Low-Power-Microcontrollers/dp/1492052043])

[Sequence Models, Andrew Ng, Week 3 - Trigger Word Detection](https://www.youtube.com/watch?v=Zqx_hbTmN6A)

[Speech Commands: A Dataset for Limited-Vocabulary Speech Recognition.](https://arxiv.org/abs/1804.03209)

[Visual Wake Words Dataset, Chowdhery, Warden et al.](https://arxiv.org/abs/1906.05721)

## TBC

### Installing Tensorflow Lite on Raspberry Pi
### Installing Tensorflow Lite on Edge Chips
### Preprocessing Data (Spectrograms, creating synthetic data)
