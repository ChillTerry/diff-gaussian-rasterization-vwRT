<h1 align="center">Differential Gaussian Rasterization with Camera Velocity and Pose Jacobians</h1>

This software is used as the rasterization engine in the ICRA25 paper ["GS-EVT: Cross-Modal Event Camera Tracking based on Gaussian Splatting"](https://arxiv.org/pdf/2409.19228v1), and supports:

* Analytical gradient for camera velocity.
* Analytical gradient for camera poses.
* Analytical gradient for rendered depth.

The code is built on top of the original [diff-gaussian-rasterization-w-pose](https://github.com/rmurai0610/diff-gaussian-rasterization-w-pose) used in ["Gaussian Splatting SLAM"](https://arxiv.org/pdf/2312.06741).

If you can make use of it in your own research, please be so kind to cite both papers.


<section class="section" id="BibTeX">
  <div class="container is-max-desktop content">
    <h2 class="title">BibTeX</h2>
    <pre><code>@article{liu2024gs,
  title={GS-EVT: Cross-Modal Event Camera Tracking based on Gaussian Splatting},
  author={Liu, Tao and Yuan, Runze and Ju, Yi'ang and Xu, Xun and Yang, Jiaqi and Meng, Xiangting and Lagorce, Xavier and Kneip, Laurent},
  journal={arXiv preprint arXiv:2409.19228},
  year={2024}
}</code></pre>
</code></pre>
    <pre><code>@inproceedings{Matsuki:Murai:etal:CVPR2024,
  title={{G}aussian {S}platting {SLAM}},
  author={Hidenobu Matsuki and Riku Murai and Paul H. J. Kelly and Andrew J. Davison},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  year={2024}
}</code></pre>

</div>
</section>

