# Gradient Descent

This repository contains the code for the blog post on [Understanding gradient descent in machine learning](https://www.fabriziomusacchio.com/blog/2023-03-27-gradient_descent/). For further details, please refer to this  post.

You can run the notebooks in *Google Colab* or *Binder* by clicking on one of the buttons below:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/FabrizioMusacchio/Gradient_Descent/HEAD?labpath=gradient_descent_demo_1D.ipynb)

One parameter problem:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/FabrizioMusacchio/gradient_descent/blob/master/gradient_descent_demo_1D.ipynb)   [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/FabrizioMusacchio/Gradient_Descent/HEAD?labpath=gradient_descent_demo_1D.ipynb)

Two parameter problem:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/FabrizioMusacchio/gradient_descent/blob/master/gradient_descent_demo_2D.ipynb)   [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/FabrizioMusacchio/Gradient_Descent/HEAD?labpath=gradient_descent_demo_2D.ipynb)


For reproducibility:

```powershell
conda create -n gradient_descent -y python=3.9
conda activate gradient_descent
conda install -y mamba
mamba install -y ipykernel numpy matplotlib ipywidgets notebook
```

## Acknowledgement
The main code is based on the blog post ["Visualizing the gradient descent method"](https://scipython.com/blog/visualizing-the-gradient-descent-method/) from [*scipython.com*](https://scipython.com).