# Methods for Probabilistic Optical Digit Recognition

This is the implementation of Ethan Chun's final project for Josh Tenenbaum and Vikash Mansinghka's course on Computational Cognitive Science
at MIT.

Note that only the 2D Gaussian method infers correctly.  The other two methods do
not quite work from reasons described my final report.

### Setup
Create an environment and
1. Install Gen according to the instructions
[here](https://www.gen.dev/docs/stable/getting_started/#Installation).
2. Install Plots with `add Plots` in the Julia REPL.

### Inference with 2D Gaussians
See [gen_ocr_gaussians.ipynb](gen_ocr_gaussians.ipynb) for the implementation of inference with 2D Gaussians.

### Inference with Pixels
See [gen_ocr_pixelspace.ipynb](gen_ocr_pixelspace.ipynb) for the
attempted pixel wise approach.

### Inference with Lines
See [gen_ocr_lines.ipynb](gen_ocr_lines.ipynb) for the implementation of inference with lines.



