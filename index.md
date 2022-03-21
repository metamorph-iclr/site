---
layout: main
title: MetaMorph
subtitle: Learning Universal Controllers with Transformers
project_tagline: "Agrim Gupta<sup>1</sup>, Linxi \"Jim\" Fan<sup>1,3</sup>, Surya Ganguli<sup>1,2</sup>, Li Fei-Fei<sup>1,2</sup>"
affiliations: "<sup>1</sup>Stanford, <sup>2</sup>Stanford Institute for Human-Centered AI, <sup>3</sup>NVIDIA"
description: "MetaMorph"
---

![pull figure]({{ 'assets/images/algorithm.jpg' | absolute_url }})

-------------
# Video Overview


{% include video/rawVideo.html fileName="videos/metamorph-twitter-video.mp4" %}


-------------
# Abstract


Multiple domains like vision, natural language, and audio are witnessing tremendous progress by leveraging Transformers for large scale pre-training followed by task specific fine tuning. In contrast, in robotics we primarily train a single robot for a single task. However, modular robot systems now allow for the flexible combination of general-purpose building blocks into task optimized morphologies. However, given the exponentially large number of possible robot morphologies, training a controller for each new design is impractical.

In this work, we propose ***MetaMorph***, a Transformer based approach to learn a universal controller over a modular robot design space. MetaMorph is based on the insight that robot morphology is just another modality on which we can condition the output of a Transformer. Through extensive experiments we demonstrate that large scale pre-training on a variety of robot morphologies results in policies with combinatorial generalization capabilities, including zero shot generalization to unseen robot morphologies. We further demonstrate that our pre-trained policy can be used for sample-efficient transfer to completely new robot morphologies and tasks.


-------------
# Experiment Details

{% include video/rawVideo.html fileName="videos/video.mp4" %}

-------------

# Citation

```bibtex
@inproceedings{
    gupta2022metamorph,
    title={MetaMorph: Learning Universal Controllers with Transformers},
    author={Agrim Gupta and Linxi Fan and Surya Ganguli and Li Fei-Fei},
    booktitle={International Conference on Learning Representations},
    year={2022},
    url={https://openreview.net/forum?id=Opmqtk_GvYL}
}
```
