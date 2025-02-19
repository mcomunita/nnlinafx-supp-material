<div align="center">

**supplementary material for:**

## Differentiable Black-box and Gray-box Modeling of Nonlinear Audio Effects

[Paper]()

[Marco Comunità](https://mcomunita.github.io/), [Christian J. Steinmetz](https://www.christiansteinmetz.com/), [Joshua D. Reiss](http://www.eecs.qmul.ac.uk/~josh/)

Centre for Digital Music, Queen Mary University of London, UK<br>

</div>

## Abstract
Audio effects are extensively used at every stage of audio and music content creation.
The majority of differentiable audio effects modeling approaches fall into the black-box or gray-box paradigms; 
and most models have been proposed and applied to nonlinear effects like guitar amplifiers, overdrive, distortion, fuzz and compressor. 
Although a plethora of architectures have been introduced for the task at hand there is still lack of understanding on the state of the art, 
since most publications experiment with one type of nonlinear audio effect and a very small number of devices. 

In this work we aim to shed light on the audio effects modeling landscape by comparing black- and gray-box architectures on a large number 
of nonlinear audio effects, identifying the most suitable for a wide range of devices. 
In the process, we also: introduce time-varying gray-box models and propose models for compressor, distortion and fuzz, publish 
a large dataset for audio effects research - [ToneTwist AFx](https://github.com/mcomunita/tonetwist-afx-dataset) - 
that is also the first open to community contributions, evaluate models on a variety of metrics and conduct extensive subjective evaluation. 
[Code](https://github.com/mcomunita/nablafx), [supplementary material and logs](https://github.com/mcomunita/nnlinafx-supp-material) are also available.

## Citation

```BibTex
@misc{comunità2025nablafxframeworkdifferentiableblackbox,
      title={NablAFx: A Framework for Differentiable Black-box and Gray-box Modeling of Audio Effects}, 
      author={Marco Comunità and Christian J. Steinmetz and Joshua D. Reiss},
      year={2025},
      eprint={2502.11668},
      archivePrefix={arXiv},
      primaryClass={cs.SD},
      url={https://arxiv.org/abs/2502.11668}, 
}
```
