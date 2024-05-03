# Modifications
- use spherical harmonics match e3nn as used in [MVSplat](https://github.com/donydchen/mvsplat).
- add depth rendering implemented in [depth-diff-gaussian-rasterization](https://github.com/ingra14m/depth-diff-gaussian-rasterization).
- add importance score for each 3D gaussian based on its contribution to rendering.
- add opacity rendering in forward pass.
- add n_touched to count the number of pixels each Gaussian contributes to
  
# Differential Gaussian Rasterization

Used as the rasterization engine for the paper "3D Gaussian Splatting for Real-Time Rendering of Radiance Fields". If you can make use of it in your own research, please be so kind to cite us.

<section class="section" id="BibTeX">
  <div class="container is-max-desktop content">
    <h2 class="title">BibTeX</h2>
    <pre><code>@Article{kerbl3Dgaussians,
      author       = {Kerbl, Bernhard and Kopanas, Georgios and Leimk{\"u}hler, Thomas and Drettakis, George},
      title        = {3D Gaussian Splatting for Real-Time Radiance Field Rendering},
      journal      = {ACM Transactions on Graphics},
      number       = {4},
      volume       = {42},
      month        = {July},
      year         = {2023},
      url          = {https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/}
}</code></pre>
  </div>
</section>