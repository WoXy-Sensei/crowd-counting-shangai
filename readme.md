# Crowd Counting with CSRNet

## Overview

This repository contains a crowd counting model using the CSRNet architecture to estimate the number of people in crowded scenes. The model is trained on the Shanghaitech dataset and aims to provide accurate crowd density maps and count predictions. Data augmentation techniques are employed to enhance the model's performance.

## Dataset

The model is trained using the [Shanghaitech dataset](https://arxiv.org/pdf/1802.10062), which contains a variety of images with annotations for crowd density. This dataset provides a comprehensive set of images suitable for training and evaluating crowd counting models.

## Model Architecture

The core of the model is based on the CSRNet architecture, which excels in dense crowd counting scenarios. CSRNet introduces a novel strategy for crowd counting by employing dilated convolutions to capture multi-scale contextual information.

For more information about CSRNet, refer to the [CSRNet paper](https://arxiv.org/pdf/1802.10062).


## Notebooks

The project includes Jupyter Notebook (`.ipynb`) files that demonstrate the following:

- Data preprocessing and augmentation
- Model training
- Model evaluation and inference

Please refer to the notebooks for detailed instructions and examples.

## Results

The model provides estimates of crowd density and total count. Results are visualized within the Jupyter Notebooks.

## References

- [CSRNet: Dilated Convolutional Neural Networks for Understanding the Highly Congested Scenes](https://arxiv.org/pdf/1802.10062)
- [Shanghaitech Dataset](http://www.shaohe.com/publications/2018/csrnet/)

## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you have any improvements or suggestions.

## Acknowledgements

- The CSRNet authors for their innovative approach to crowd counting.
- The creators of the Shanghaitech dataset for providing a valuable resource for crowd analysis.
