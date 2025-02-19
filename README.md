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

## Code

To coduct the study we developed and made use of the [NablAFx](https://github.com/mcomunita/nablafx) framework for differentiable black-box and gray-box audio effects modeling.

## Appendix

The paper appendix with complete tables of results is available in this repo:
[Appendix](https://github.com/mcomunita/nnlinafx-supp-material/blob/master/Differentiable_Black_box_and_Gray_box_Modeling_of_Nonlinear_Audio_Effects___Appendix___Arxiv.pdf)

## Weights&Biases Logs

Some (due to storage limits) logs for our experiments are made publicly available at the following links. Due to the large number of experiments and runs, we suggest to group runs by "Group"
and filter by "Tags" to select for specific devices or architectures.

- Overdrive: [https://wandb.ai/marco-comunita/nnlinafx-OD](https://wandb.ai/marco-comunita/nnlinafx-OD)
- Distortion: [https://wandb.ai/marco-comunita/nnlinafx-DIST](https://wandb.ai/marco-comunita/nnlinafx-DIST)
- Fuzz: [https://wandb.ai/mcomunita/nnlinafx-FUZZ](https://wandb.ai/mcomunita/nnlinafx-FUZZ)

## Citation

```BibTex
@misc{}
```
