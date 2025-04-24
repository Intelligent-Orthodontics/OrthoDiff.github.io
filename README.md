<p align="center">

  <h1 align="center">Hierarchical Diffusion Transformer for Target-free Orthodontic Planning</h1>
<!--   <h2 align="center">TPAMI 2025</h2> -->
<!--   <h3 align="center"><a href="https://arxiv.org/pdf/2410.18477">Paper</a> | <a href="https://chuanxiang-yang.github.io/S2DF/">Project Page</a> | <a href="https://arxiv.org/abs/2410.18477">arXiv</a> </h3> -->
  <div align="center"></div>
</p>
<p align="center">
  <img src="assess/Intro.png" width="1080" />
</p>


  In this paper, we tackle the problem of target-free tooth motion generation in digital orthodontics, with the goal of assisting orthodontic planning without relying on target tooth alignment from experienced dental experts. In practice, only the initial alignment of the patient is obtained. However, no existing method can predict the complete motion sequence using only the initial tooth alignment. To address this gap, we propose OrthoDiff, a novel target-free framework that uses only the initial tooth alignment. We design a hierarchical diffusion transformer as the backbone of OrthoDiff. Our approach generates tooth motion by decomposing the entire motion sequence into multi-level motions, progressively simplifying the complexity of target-free generation. Moreover, it treats tooth alignment as a sequence of tooth tokens and fully leverages the topological prior knowledge of the dental model. Through extensive evaluations, we demonstrate that our method significantly outperforms state-of-the-art techniques in target-free tooth motion generation. Ablation studies further confirm the efficacy of the key components in our network design. 
  
## Install
   

## Dataset
Please organize the data according to the following structure. We provide the input tooth motion process.
```
│data/
├──X/
│  ├── 

...
```

## Demo

https://github.com/user-attachments/assets/bf50e1f3-f4f9-40a0-b6d9-0792b1b84ae9

https://github.com/user-attachments/assets/6fc6b4f9-b0c2-495f-a3a6-e87e9c7f2c78

https://github.com/user-attachments/assets/3e2cd251-afc6-4e50-bdbd-54c3ed21d7c1

https://github.com/user-attachments/assets/6120a01d-eb60-49a8-b194-5265d9ad9e13

https://github.com/user-attachments/assets/9d1622bc-e20e-46fa-adbf-c895ed7f8c0a





