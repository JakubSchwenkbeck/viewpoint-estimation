

# Viewpoint Estimation for Animal Re-Identification on Edge Devices

<img width="2448" height="1523" alt="viewpoint_abstract" src="https://github.com/user-attachments/assets/234d316b-8396-4ae3-baf3-4f1b5dbc8cfc" />






## Repository Architecture

This repository is organized into two separate branches:

* **`master`**: Contains the full pipeline and model training scripts from my thesis. Use this branch to experiment, evaluate ablation configurations or train custom models.
* **`module`**: A lightweight, production-ready release containing only the core standalone estimator. Switch to this branch for direct, dependencies-minimized deployment and framework integration.

All models can be found in the release for this paper submission

the `demo/` directory includes sampled images for two zebras including 8 different viewpoints from the [`ZebraStereoID`](https://darus.uni-stuttgart.de/dataset.xhtml?persistentId=doi:10.18419/DARUS-5957) dataset. 
