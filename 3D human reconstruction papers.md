## 3D human reconstruction - Non parametric

Year | Method | Tags | Desc | Comments / Code run
--- | --- | --- | --- | ---
CVPR 2023 | [Vid2Avatar](https://arxiv.org/pdf/2302.11566.pdf) | Implicit, Self-Supervised, avatars thus textured | main idea based on opacity difference between background amd human, <datasets: MonoPerfCap, NeuMan, 3DPW, SynWild>  | In progress, partially run(have to resolve openpose installation), 80GB GPU  
CVPR 2023 | [ECON](https://arxiv.org/pdf/2212.07422.pdf) | Implicit+Explicit, Supervised | main idea based on normal integration(BINI) and shape completion, <train: THuman 2.0, test: CAPE, RenderPeople>  | Y, 12GB-24GB GPU, Comparison - PiFU HD, ICON, PAMIR
CVPR 2022| [Photorealistic Monocular 3D](https://arxiv.org/pdf/2204.08906.pdf) | Implicit, Supervised, Textured | main idea is based on using rendering equations with reconstruction, <their own dataset >  | In progress, just received code 
CVPR 2022| [Self Recon](https://arxiv.org/pdf/2201.12792.pdf) | Implicit+Explicit, Self-Supervised | |  
ECCV 2022 | [Integrated-PIFU](https://arxiv.org/pdf/2211.07955.pdf) | Implicit, Supervised | main idea based on improving PIFU-HD, multi-level architecture coarse and fine, <train: THuman 2.0> | Code run not very clear, was waiting for THuman 2.0 dataset
CVPR 2021| [ICON](https://arxiv.org/pdf/2112.09127.pdf) | Implicit+Explicit, Supervised | main idea based on SMPL guided normals, <train: THuman, AGORA, RenderPeople>  | 
ICCV 2021 | [ARCH++](https://arxiv.org/pdf/2108.07845.pdf) | Implicit+Explicit, Supervised  | | 
CVPR 2020 | [PIFU-HD](https://arxiv.org/pdf/2004.00452.pdf) | Implicit, Supervised | main idea based on multi-level architecture coarse and fine, <train: RenderPeople> | Colab run, 12 GB GPU
CVPR 2020 | [ARCH](https://arxiv.org/pdf/2004.04572.pdf) | Implicit+Explicit, Supervised  | | 
PAMI 2020 | [PAMIR](https://arxiv.org/pdf/2007.03858.pdf) | Implicit+Explicit, Supervised  | |
NIPS 2020 | [Geo-PIFU](https://arxiv.org/pdf/2006.08072.pdf) | Implicit, Supervised  | <train: DeepHuman> | 