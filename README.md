# Structure-Aware Human-Action Generation

We propose a variant of GCNs to leverage the powerful self-attention mechanism to adaptively sparsify a complete action graph in the temporal space. Our method could dynamically attend to important past frames and construct a sparse graph to apply in the GCN framework, well-capturing the structure information in action sequences. The paper can be found on arXiv [here!](https://arxiv.org/abs/2007.01971). ECCV 2020 accepted. 

If you use this code or these models, please cite the following paper:
```
@article{yu2020structure,
  title={Structure-Aware Human-Action Generation},
  author={Yu, Ping and Zhao, Yang and Li, Chunyuan and Chen, Changyou},
  journal={arXiv preprint arXiv:2007.01971},
  year={2020}
}
```
### Model Architecture
<p align="center">
  <img src=https://github.com/PingYu-iris/SA-GCN/blob/master/imgs/framework.jpg width="800" title="hover text">
</p>
<p align="center" style="font-size:8px;">Fig. 1: The overall framework of the proposed method.</p>

<p>Fig.1 illustrates the overall framework of our model for action generation. It follows the GAN framework of video generation \cite{tulyakov2018mocogan,clark2019efficient}, which consists of an action generator  $\mathcal{G}$ and a dual discriminator: one video-based discriminator $\mathcal{D}_V$ and one frame-based discriminator $\mathcal{D}_F$.</p>




### Prepare Dataset


