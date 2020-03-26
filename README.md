# Deep Learning-based Detection for COVID-19 from Chest CT using Weak Label


<hr>




<hr>

Before running the code, please prepare a computer with NVIDIA GPU, then install Anaconda, PyTorch and NVIDIA CUDA driver. Once the environment and dependent libraries are installed, please check the `README.md` files in `2dunet` and `deCoVnet` directories.

- In the directory of "2dunet", the code mainly aims to segment the lung region to obtain all lung masks.
- In the directory of "deCoVnet", the code does the classification task of whether a CT volume being infected.

- The file "20200212-auc95p9.txt" contains the output probabilities of our pretrained deCovNet on our testing set.



# LICENSE

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

This work is licensed under a
Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License.

You should have received a copy of the license along with this
work. If not, see <http://creativecommons.org/licenses/by-nc-sa/4.0/>.


