# Toward Large-scale Spiking Neural Networks

> A collection of papers and resources related to deep SNN models
>
> With the thriving of Spiking Transfomrers, we hope this survey could be of help in implementing large-scale SNNs. 
>
> This repo refers to our survey [**"Toward Large-scale Spiking Neural Networks: A Comprehensive Survey and Future Directions"**](https://www.arxiv.org/abs/2409.02111). 
>
> If you find our survey useful for your research, please cite the following paper:

```
@article{hu2024toward,
  title={Toward Large-scale Spiking Neural Networks: A Comprehensive Survey and Future Directions},
  author={Hu, Yangfan and Zheng, Qian and Li, Guoqi and Tang, Huajin and Pan, Gang},
  journal={arXiv preprint arXiv:2409.02111},
  year={2024}
}
```

# List of Spiking Transformers
<table>
<thead>
  <tr>
    <th align="center" rowspan="2">Category</th>
    <th align="center" rowspan="2">Paper</th>
    <th align="center" rowspan="2">Date (arXiv first)</th>
    <th align="center" rowspan="2">Param. Size (Max)</th>
    <th align="center" rowspan="2">Code Link</th>
    <th align="center" rowspan="2">Venue</th>
    <th align="center" rowspan="2">Group</th>
    <th align="center" rowspan="2">Comment</th>
  </tr>
  <tr>
  </tr>
</thead>
<tbody>
  <tr>
    <td align="center" rowspan="3"><br>Vanilla Attention</td>
    <td align="center"><a href="https://doi.org/10.1109/ICSAI53574.2021.9664146">Spiking transformer networks: A rate coded approach for processing sequential data</a></td>
    <td align="center">2021</td>
    <td align="center"></td>
    <td align="center"></td>
    <td align="center">ICSAI2021</td>
    <td align="center">TUM</td>
    <td align="center"></td>
  </tr>
  <tr>
    <td align="center"><a href="https://openaccess.thecvf.com/content/CVPR2022/html/Zhang_Spiking_Transformers_for_Event-Based_Single_Object_Tracking_CVPR_2022_paper.html">Spiking transformers for event-based single object tracking</a></td>
    <td align="center">2022</td>
    <td align="center"></td>
    <td align="center"><a href="https://github.com/Jee-King/CVPR2022_STNet">Github</a></td>
    <td align="center">CVPR2022</td>
    <td align="center">DLUT</td>
    <td align="center">DVS+OT</td>
  </tr>
  <tr>
    <td align="center"><a href="https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/3125_ECCV_2022_paper.php">Spike transformer: Monocular depth estimation for spiking camera</a></td>
    <td align="center">2022</td>
    <td align="center"></td>
    <td align="center"><a href="https://github.com/Leozhangjiyuan/MDE-SpikingCamera">Github</a></td>
    <td align="center">ECCV2022</td>
    <td align="center">PKU</td>
    <td align="center">DVS+DE</td>
  </tr>
  <tr>
    <td align="center" rowspan="4"><br>SSA</td>
    <td align="center"><a href="https://openreview.net/forum?id=frE4fUwz_h">Spikformer: When spiking neural network meets transformer</a></td>
    <td align="center">2022</td>
    <td align="center">66.34 M</td>
    <td align="center"><a href="https://github.com/ZK-Zhou/spikformer">Github</a></td>
    <td align="center">ICLR2023</td>
    <td align="center">PKU</td>
    <td align="center">First SSA. Prometheus :fire:</td>
  </tr>
  <tr>
    <td align="center"><a href="https://proceedings.neurips.cc/paper_files/paper/2023/hash/ca0f5358dbadda74b3049711887e9ead-Abstract-Conference.html">Spike-driven Transformer</a></td>
    <td align="center">2023</td>
    <td align="center">66.34 M</td>
    <td align="center"><a href="https://github.com/BICLab/Spike-Driven-Transformer">Github</a></td>
    <td align="center">NIPS2023</td>
    <td align="center">CASIA</td>
    <td align="center">Mask+Add SSA</td>
  </tr>
  <tr>
    <td align="center"><a href="https://openaccess.thecvf.com/content/CVPR2024/html/Shi_SpikingResformer_Bridging_ResNet_and_Vision_Transformer_in_Spiking_Neural_Networks_CVPR_2024_paper.html">SpikingResformer: Bridging ResNet and Vision Transformer in Spiking Neural Networks</a></td>
    <td align="center">2024</td>
    <td align="center">60.38 M</td>
    <td align="center"><a href="https://github.com/xyshi2000/SpikingResformer">Github</a></td>
    <td align="center">CVPR2024</td>
    <td align="center">PKU</td>
    <td align="center">Dual Spike SA</td>
  </tr>
    <td align="center"><a href="https://arxiv.org/abs/2403.16552">QKFormer: Hierarchical Spiking Transformer using QK Attention</a></td>
    <td align="center">2024</td>
    <td align="center">64.96 M</td>
    <td align="center"><a href="https://github.com/zhouchenlin2096/QKFormer"></a></td>
    <td align="center"></td>
    <td align="center">PCL</td>
    <td align="center">token/channel attention</td>
  </tr>
  <tr>
    <td align="center" rowspan="5"><br>STSA</td>
    <td align="center"><a href="https://arxiv.org/abs/2311.09376">DISTA: Denoising Spiking Transformer with intrinsic plasticity and spatiotemporal attention</a></td>
    <td align="center">2023</td>
    <td align="center"></td>
    <td align="center"><a href=""></a></td>
    <td align="center"></td>
    <td align="center">UCSB</td>
    <td align="center"></td>
  </tr>
  <tr>
    <td align="center"><a href="https://www.ijcai.org/proceedings/2023/344">Spatial-Temporal Self-Attention for Asynchronous Spiking Neural Networks</a></td>
    <td align="center">2023</td>
    <td align="center"></td>
    <td align="center"><a href="https://github.com/ppppps/STSA_4_Asyn_SNN">Github</a></td>
    <td align="center">IJCAI2023</td>
    <td align="center">UESTC</td>
    <td align="center"></td>
  </tr>
  <tr>
    <td align="center"><a href="https://arxiv.org/abs/2303.09681">Event-based human pose tracking by spiking spatiotemporal transformer</a></td>
    <td align="center">2023</td>
    <td align="center">47.7 M</td>
    <td align="center"><a href="https://github.com/JimmyZou/HumanPoseTracking_SNN">Github</a></td>
    <td align="center"></td>
    <td align="center">UAlberta</td>
    <td align="center"></td>
  </tr>
  <tr>
    <td align="center"><a href="https://www.ijcai.org/proceedings/2024/0347">TIM: An Efficient Temporal Interaction Module for Spiking Transformer</a></td>
    <td align="center">2024</td>
    <td align="center"></td>
    <td align="center"><a href="https://github.com/BrainCog-X/Brain-Cog/tree/main/examples/TIM">Github</a></td>
    <td align="center">IJCAI2024</td>
    <td align="center">CASIA</td>
    <td align="center"></td>
  </tr>
  <tr>
    <td align="center"><a href="https://www.sciencedirect.com/science/article/abs/pii/S0925231224010397">TE-Spikformer: Temporal-enhanced spiking neural network with transformer</a></td>
    <td align="center">2024</td>
    <td align="center"></td>
    <td align="center"><a href=""></a></td>
    <td align="center">Neurocomputing</td>
    <td align="center">SHU</td>
    <td align="center"></td>
  </tr>
  <tr>
    <td align="center" rowspan="6"><br>Architectural Improvements</td>
    <td align="center"><a href="https://arxiv.org/abs/2304.11954">Spikingformer: Spike-driven Residual Learning for Transformer-based Spiking Neural Network</a></td>
    <td align="center">2023</td>
    <td align="center">66.34 M</td>
    <td align="center"><a href="https://github.com/zhouchenlin2096/Spikingformer">Github</a></td>
    <td align="center"></td>
    <td align="center">PCL</td>
    <td align="center">Membrane Shortcuts</td>
  </tr>
  <tr>
    <td align="center"><a href="https://arxiv.org/abs/2305.05954">Enhancing the Performance of Transformer-based Spiking Neural Networks by SNN-optimized Downsampling with Precise Gradient Backpropagation</a></td>
    <td align="center">2023</td>
    <td align="center"></td>
    <td align="center"><a href="https://github.com/zhouchenlin2096/Spikingformer-CML">Github</a></td>
    <td align="center">66.34 M</td>
    <td align="center">PCL</td>
    <td align="center">Real-valued Max-pool</td>
  </tr>
  <tr>
    <td align="center"><a href="https://arxiv.org/abs/2401.02020">Spikformer V2: Join the High Accuracy Club on ImageNet with an SNN Ticket</a></td>
    <td align="center">2024</td>
    <td align="center">51.55 M</td>
    <td align="center"><a href=""></a></td>
    <td align="center"></td>
    <td align="center">PKU</td>
    <td align="center">Self-Supervised Learning + finetune</td>
  </tr>
  <tr>
    <td align="center"><a href="https://www.sciencedirect.com/science/article/pii/S092523122400050X">Spikeformer: Training high-performance spiking neural network with transformer</a></td>
    <td align="center">2024</td>
    <td align="center"></td>
    <td align="center"><a href=""></a></td>
    <td align="center">Neurocomputing</td>
    <td align="center">BIT</td>
    <td align="center"></td>
  </tr>
  <tr>
    <td align="center"><a href="https://openreview.net/forum?id=1SIBN5Xyw7">Spike-driven transformer v2: Meta spiking neural network architecture inspiring the design of next-generation neuromorphic chips</a></td>
    <td align="center">2024</td>
    <td align="center">55.4 M</td>
    <td align="center"><a href="https://github.com/BICLab/Spike-Driven-Transformer-V2">Github</a></td>
    <td align="center">ICLR2024</td>
    <td align="center">CASIA</td>
    <td align="center"></td>
  </tr>
  <tr>
    <td align="center"><a href="https://www.frontiersin.org/journals/neuroscience/articles/10.3389/fnins.2024.1371290/full">SGLFormer: Spiking Global-Local-Fusion Transformer with high performance</a></td>
    <td align="center">2024</td>
    <td align="center"></td>
    <td align="center"><a href="https://github.com/ZhangHanN1/SGLFormer">Github</a></td>
    <td align="center">Front. Neurosci.</td>
    <td align="center">PCL</td>
    <td align="center"></td>
  </tr>
  <tr>
    <td align="center" rowspan="4"><br>Lightweighting</td>
    <td align="center"><a href="https://doi.org/10.1109/ICASSP48485.2024.10445971">AutoST: Training-free Neural Architecture Search for Spiking Transformers</a></td>
    <td align="center">2023</td>
    <td align="center">34.44 M</td>
    <td align="center"><a href="https://github.com/AlexandreWANG915/AutoST">Github</a></td>
    <td align="center">ICASSP2024</td>
    <td align="center">NCSU</td>
    <td align="center">SNN NAS</td>
  </tr>
  <tr>
    <td align="center"><a href="https://arxiv.org/abs/2308.02557">Attention-free spikformer: Mixing spike sequences with simple linear transforms</a></td>
    <td align="center">2023</td>
    <td align="center"></td>
    <td align="center"><a href=""></a></td>
    <td align="center"></td>
    <td align="center">UCAS</td>
    <td align="center"></td>
  </tr>
  <tr>
    <td align="center"><a href="https://arxiv.org/abs/2311.16456">Spiking Neural Networks with Dynamic Time Steps for Vision Transformers</a></td>
    <td align="center">2023</td>
    <td align="center"></td>
    <td align="center"><a href=""></a></td>
    <td align="center"></td>
    <td align="center">USC</td>
    <td align="center"></td>
  </tr>
  <tr>
    <td align="center"><a href="https://www.ijcai.org/proceedings/2024/348">One-step Spiking Transformer with a Linear Complexity</a></td>
    <td align="center">2024</td>
    <td align="center">33.87 M</td>
    <td align="center"><a href="https://github.com/songxt3/OST">Github</a></td>
    <td align="center">IJCAI2024</td>
    <td align="center">SCU</td>
    <td align="center"></td>
  </tr>
  <tr>
    <td align="center" rowspan="4"><br>Conversion</td>
    <td align="center"><a href="https://openaccess.thecvf.com/content/ICCV2023/html/Wang_Masked_Spiking_Transformer_ICCV_2023_paper.html">Masked spiking transformer</a></td>
    <td align="center">2023</td>
    <td align="center">28.5 M</td>
    <td align="center"><a href="https://github.com/bic-L/Masked-Spiking-Transformer">Github</a></td>
    <td align="center">ICCV2023</td>
    <td align="center">HKUST</td>
    <td align="center">High Latency</td>
  </tr>
  <tr>
    <td align="center"><a href="https://openreview.net/forum?id=XrunSYwoLr">Spatio-Temporal Approximation: A Training-Free SNN Conversion for Transformers</a></td>
    <td align="center">2024</td>
    <td align="center"></td>
    <td align="center"><a href="https://github.com/ViviaHu/STA">Github</a></td>
    <td align="center">ICLR2024</td>
    <td align="center">THU</td>
    <td align="center">Address Layernorm</td>
  </tr>
  <tr>
    <td align="center"><a href="https://openreview.net/forum?id=NeotatlYOL">SpikeZIP-TF: Conversion is All You Need for Transformer-based SNN</a></td>
    <td align="center">2024</td>
    <td align="center">304.33 M</td>
    <td align="center"><a href="https://github.com/Intelligent-Computing-Research-Group/SpikeZIP-TF">Github</a></td>
    <td align="center">ICML2024</td>
    <td align="center">SJTU</td>
    <td align="center"></td>
  </tr>
  <tr>
    <td align="center"><a href="https://openreview.net/forum?id=BZi746oBG8&referrer=%5Bthe%20profile%20of%20Zecheng%20Hao%5D(%2Fprofile%3Fid%3D~Zecheng_Hao1)">Towards High-performance Spiking Transformers from ANN to SNN Conversion</a></td>
    <td align="center">2024</td>
    <td align="center">1074 M</td>
    <td align="center"><a href=""></a></td>
    <td align="center">MM2024</td>
    <td align="center">PKU</td>
    <td align="center">Finally 1B</td>
  </tr>
  <tr>
    <td align="center" rowspan="5"><br>NLP</td>
    <td align="center"><a href="https://openreview.net/forum?id=gcf1anBL9e">Spikegpt: Generative pre-trained language model with spiking neural networks</a></td>
    <td align="center">2023</td>
    <td align="center">216 M</td>
    <td align="center"><a href="https://github.com/ridgerchu/SpikeGPT">Github</a></td>
    <td align="center">TMLR</td>
    <td align="center">UCSC</td>
    <td align="center">RWKV</td>
  </tr>
  <tr>
    <td align="center"><a href="https://ojs.aaai.org/index.php/AAAI/article/view/28975">SpikingBERT: Distilling bert to train spiking language models using implicit differentiation</a></td>
    <td align="center">2023</td>
    <td align="center">≤50 M</td>
    <td align="center"><a href="https://github.com/NeuroCompLab-psu/SpikingBERT">Github</a></td>
    <td align="center">AAAI2024</td>
    <td align="center">PSU</td>
    <td align="center"></td>
  </tr>
  <tr>
    <td align="center"><a href="https://arxiv.org/abs/2308.15122">SpikeBERT: A Language Spikformer Learned from BERT with Knowledge Distillation</a></td>
    <td align="center">2023</td>
    <td align="center">109 M</td>
    <td align="center"><a href="https://github.com/Lvchangze/SpikeBERT">Github</a></td>
    <td align="center"></td>
    <td align="center">FDU</td>
    <td align="center"></td>
  </tr>
  <tr>
    <td align="center"><a href="https://www.sciengine.com/SCIS/doi/10.1007/s11432-024-4101-6">SpikingMiniLM: Energy-efficient Spiking Transformer for Natural Language Understanding</a></td>
    <td align="center">2024</td>
    <td align="center">25.0 M</td>
    <td align="center"><a href=""></a></td>
    <td align="center"></td>
    <td align="center">ZJU</td>
    <td align="center"></td>
  </tr>
  <tr>
    <td align="center"><a href="https://arxiv.org/abs/2407.04752">SpikeLLM: Scaling up Spiking Neural Network to Large Language Models via Saliency-based Spiking</a></td>
    <td align="center">2024</td>
    <td align="center">7~70 B</td>
    <td align="center"><a href=""></a></td>
    <td align="center"></td>
    <td align="center">CASIA</td>
    <td align="center">Impressive Size</td>
  </tr>
  <tr>
    <td align="center" rowspan="5"><br>Interesting Applications</td>
    <td align="center"><a href="https://doi.org/10.1109/TCDS.2023.3327081">Transformer-based spiking neural networks for multimodal audio-visual classification</a></td>
    <td align="center">2023</td>
    <td align="center"></td>
    <td align="center"><a href="https://github.com/Guo-Lingyue/SMMT">Github</a></td>
    <td align="center">TCDS</td>
    <td align="center">CASIA</td>
    <td align="center"></td>
  </tr>
  <tr>
    <td align="center"><a href="https://arxiv.org/abs/2402.04798">Spiking-physformer: Camera-based remote photoplethysmography with parallel spike-driven transformer</a></td>
    <td align="center">2024</td>
    <td align="center"></td>
    <td align="center"><a href=""></a></td>
    <td align="center"></td>
    <td align="center">THU</td>
    <td align="center"></td>
  </tr>
  <tr>
    <td align="center"><a href="https://arxiv.org/abs/2402.09424">Epilepsy Seizure Detection and Prediction using an Approximate Spiking Convolutional Transformer</a></td>
    <td align="center">2024</td>
    <td align="center"></td>
    <td align="center"><a href=""></a></td>
    <td align="center"></td>
    <td align="center">ETHZ</td>
    <td align="center">BCI+SNN</td>
  </tr>
  <tr>
    <td align="center"><a href="https://arxiv.org/abs/2310.06488">SpikeCLIP: A Contrastive Language-Image Pretrained Spiking Neural Network</a></td>
    <td align="center">2024</td>
    <td align="center"></td>
    <td align="center"><a href=""></a></td>
    <td align="center"></td>
    <td align="center">FDU</td>
    <td align="center">CLIP+SNN</td>
  </tr>
  <tr>
    <td align="center"><a href="https://arxiv.org/abs/2402.11588">SDiT: Spiking Diffusion Model with Transformer</a></td>
    <td align="center">2024</td>
    <td align="center"></td>
    <td align="center"><a href=""></a></td>
    <td align="center"></td>
    <td align="center">ZJU</td>
    <td align="center">Diffusion+SNN</td>
  </tr>
</tbody>
</table>
