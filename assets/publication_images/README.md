Publication thumbnail images
============================

Present (already wired into index.html):
  accv-neural-substitution.jpg   ACCV 2024   (block/branch connectivity, Fig.1)
  sci-reports-cnn-vit.jpg        Sci. Reports 2024 (CNN vs ViT robustness, Fig.1)
  ijs-small-bowel.jpg            Int. J. Surgery 2023 (dual-branch classifier, Fig.2)

To add a figure for a paper that currently shows an icon:
  1. Drop a square-ish JPG (~600-760px) here using the filename below.
  2. In index.html, find that paper's <span class="thumb">...</span> and change
       <span class="thumb"><svg><use href="#ic-XXX"/></svg></span>
     to
       <span class="thumb"><img src="assets/publication_images/FILENAME.jpg" alt="" loading="lazy" onerror="this.remove()"><svg><use href="#ic-XXX"/></svg></span>

Suggested filenames (keep the icon fallback either way):
  world-state-delta.jpg        World-State Delta Training        (#ic-delta)
  lazyvla.jpg                  LazyVLA                          (#ic-gate)
  early-visual-observer.jpg    Who Watches the VLA?             (#ic-eye)
  train-overcomplete.jpg       Train Overcomplete, Deploy...    (#ic-prune)
  layerwise-curriculum.jpg     Layer-wise Curriculum Learning   (#ic-layers)
  test-time-adaptation.jpg     Efficient Test-Time Adaptation   (#ic-shift)
  adaptive-regularization.jpg  Adaptive Regularization          (#ic-target)
  recalibrated-contrastive.jpg Re-calibrated Contrastive Loss   (#ic-vlm)
