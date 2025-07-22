# Awesome Point Cloud Generation [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome point cloud generation papers.

| Title | Venue | Dataset | Condition | Output | Architecture | Url |
|-------|--------|---------|-----------|--------|--------------|------|
| [PointGrow](https://arxiv.org/abs/1810.05591) | WACV 2020 | ShapeNet | None<br>RGB image | Point cloud | Autoregressive | [Project](https://liuziwei7.github.io/projects/PointGrow)<br>[Code](https://github.com/syb7573330/PointGrow) |
| [DPM](https://arxiv.org/abs/2103.01458) | CVPR 2021 | ShapeNet<br>ModelNet | None | Point cloud | Diffusion | [Code](https://github.com/luost26/diffusion-point-cloud) |
| [PVD](https://arxiv.org/abs/2104.03670) | ICCV 2021 | ShapeNet<br>GenRe<br>Redwood 3DScans | None<br>Partial point cloud | Point cloud | Diffusion | [Project](https://alexzhou907.github.io/pvd)<br>[Code](https://github.com/alexzhou907/PVD) |
| [AR-CAM](https://arxiv.org/abs/2204.01955) | ECCV 2022 | ShapeNet | None<br>Depth image | Point cloud | VQ-VAE + Autoregressive | [Code](https://github.com/AnjieCheng/CanonicalVAE) |
| [Lion](https://arxiv.org/abs/2210.06978) | NeurIPS 2022 | ShapeNet | None<br>Voxel<br>Text | Point cloud<br>Mesh | VAE + Latent Diffusion | [Project](https://research.nvidia.com/labs/toronto-ai/LION/)<br>[Code](https://github.com/nv-tlabs/LION) |
| [Point-E](https://arxiv.org/abs/2212.08751) | OpenAI 2022 | Millions of shapes<br>(non-released) | Text | Point cloud (w/ RGB) | Diffusion | [Code](https://github.com/openai/point-e) |
| [3DQD](https://arxiv.org/abs/2303.10406) | CVPR 2023 | ShapeNet | None<br>Text<br>RGB image | Point cloud<br>Mesh<br>T-SDF | VQ-VAE + Latent Diffusion | [Code](https://github.com/colorful-liyu/3DQD) |
| [DiffFacto](https://arxiv.org/abs/2305.01921) | ICCV 2023 | ShapeNet | None | Point cloud (w/ segmentation) | Diffusion | [Project](https://difffacto.github.io/)<br>[Code](https://github.com/diffFacto/diffFacto) |
| [DiT-3D](https://arxiv.org/abs/2307.01831) | NeurIPS 2023 | ShapeNet | None | Point cloud | Diffusion | [Project](https://dit-3d.github.io/)<br>[Code](https://github.com/DiT-3D/DiT-3D) |
| [TIGER](https://openaccess.thecvf.com/content/CVPR2024/html/Ren_TIGER_Time-Varying_Denoising_Model_for_3D_Point_Cloud_Generation_with_CVPR_2024_paper.html) | CVPR 2024 | ShapeNet | None | Point cloud | VAE + Latent Diffusion | [Code](https://github.com/Zhiyuan-R/Tiger-Diffusion) |
| [NPCD](https://arxiv.org/abs/2312.14124) | CVPR 2024 | ShapeNet<br>PhotoShape | None | Point Cloud (w/ discretized NeRF) | Diffusion | [Project](https://neural-point-cloud-diffusion.github.io/)<br>[Code](https://github.com/lmb-freiburg/neural-point-cloud-diffusion) |
| [SeaLion](https://arxiv.org/abs/2505.17721) | CVPR 2025 | ShapeNet<br>IntrA | None | Point cloud (w/ segmentation) | VAE + Latent Diffusion | [Project](https://dekai21.github.io/SeaLion/)<br>[Code](https://github.com/Dekai21/SeaLion) |
