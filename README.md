# Hi there, I'm Yujie Lin 👋

I am a Master's student in **Computer Vision at Carnegie Mellon University (CMU)**. 
My interests lie in **3D Vision, Sensor Simulation, and Real-time ML Systems**.

### 🔬 Featured Publications
*   **[Ctrl-RS: Controllable Radar Simulation](https://openaccess.thecvf.com/content/CVPR2026F/html/Xiao_Controllable_Radar_Simulation_with_Waveform_Parameter_Embedding_CVPRF_2026_paper.html)** (CVPR Findings 2026, Co-author)
    *   Co-developed a waveform-conditioned radar simulator supporting attribute editing and multimodal scene perception from LiDAR, radar, and monocular imagery.
    *   Reduced per-point error from 0.644 to 0.267 at 0.04s/frame - over 15x faster than RadSimReal.
    *   Simulated data outperformed real data in 2D detection and semantic segmentation, and improved 3D detection by +4.2 AP@0.3 when combined with real data.
*   **[SF-Head: Fine-Grained Skeleton Action Recognition](https://ietresearch.onlinelibrary.wiley.com/doi/full/10.1049/cvi2.70016)** (IET Computer Vision 2025, Co-first Author)
    *   Proposed SF-Head, a lightweight plug-and-play module for synchronized feature extraction and adaptive aggregation in ambiguous skeleton-action recognition.
    *   Improved accuracy on ambiguous action classes by up to 5.2% across four benchmark datasets and seven GCN backbones with only 0.01M training parameters and zero inference-time overhead.

### 🚀 Highlighted Projects
**Computer Vision Engineer - Smart Construction Sites** @ China Telecom *(May 2026 - Aug. 2026)*
*   Built a real-time illegal-excavation detection system combining YOLO, ByteTrack, and R(2+1)D action recognition across multi-camera RTSP streams.
*   Fine-tuned a Kinetics-pretrained R(2+1)D model on tracked excavator clips, achieving 96.6% precision and 99.1% recall for digging versus non-digging behavior.
*   Sustained 5-10 RTSP feeds on one A10 GPU via per-track caching, batched inference, and isolated tracker state; deployed a commercial pilot across Shenzhen sites.

**3D Vision Research Intern - Urban Novel-View Synthesis** @ AIR, Tsinghua University *(Jul. 2025 - Oct. 2025)*
*   Built an urban novel-view synthesis pipeline for cross-lane and opposite-direction extrapolation.
*   Initialized 3D-GS with MVS point clouds and B-spline road anchors; improved efficiency and fidelity with octree LOD, depth priors, and progressive optimization.
*   Ranked 3rd in ICCV 2025 Workshop Track 1, achieving top-2 PSNR (18.009) and SSIM (0.496) among all submissions.

**Algorithm Engineer - Consumer Credit Risk Modeling** @ Shenzhen Institute of Computing Sciences *(Jul. 2024 - Sep. 2024)*
*   Built an interpretable feature-engineering pipeline over PBOC credit data: modeled 19 entities in a knowledge graph, generated 14,583 candidates, and selected 122 high-value risk indicators.
*   Trained LightGBM to 0.729 AUC / 0.341 KS on Jan. 2024 OOT data.
*   Delivered risk-rule documentation for a deployed branch pilot supporting nationwide rollout.

### 🛠️ Tech Stack
*   **Languages:** Python, SQL, Java
*   **ML & CV:** PyTorch, YOLO, ByteTrack, LightGBM, 3D Gaussian Splatting
*   **Systems:** Docker, Linux, RTSP

### 📫 How to reach me
*   **LinkedIn:** [Yujie Lin](https://www.linkedin.com/in/yujie-lin-cmu/)
*   **Email:** yujiejobapp@163.com

---
*Note: Due to NDA and institutional policies, the source code for some of my industry projects cannot be made public here. I am happy to discuss the architecture and algorithms during interviews.*
