# Canonical Shape Projection is All You Need for 3D Few-shot Class Incremental Learning

## Introduction
This repository contains the implementation for the paper titled "Canonical Shape Projection is All You Need for 3D Few-shot Class Incremental Learning", accepted at ECCV 2024. The goal of this project is to explore and implement the proposed method using Python and PyTorch.

## ECCV 2024 Paper
The paper has been accepted at ECCV 2024. You can find it on the ECCV 2024 website: [ECCV 2024](https://eccv.ecva.net/)

## Requirements
- Python (>=3.6)
- PyTorch (>=1.0)

## Installation
1. Clone the repository:
   ```
   git clone https://github.com/your_username/your_repository.git
   cd your_repository
   ```
   
2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage
1. **Training:**
   To train the model, run:
   ```
   python train.py --options
   ```
   Make sure to adjust the options and hyperparameters according to your setup.

2. **Evaluation:**
   To evaluate the trained model, run:
   ```
   python evaluate.py --options
   ```
   Provide the necessary options for evaluation, such as model checkpoint path, evaluation dataset, etc.

3. **Inference:**
   For inference on new data, use:
   ```
   python inference.py --options
   ```
   Adjust the options as per your requirements for inference tasks.

## Citation
If you find this work useful in your research, please consider citing:

```
@inproceedings{your_paper_citation,
  title={Canonical Shape Projection is All You Need for 3D Few-shot Class Incremental Learning},
  author={Your Name and Co-authors},
  booktitle={European Conference on Computer Vision (ECCV)},
  year={2024},
  organization={Springer},
  url={https://eccv.ecva.net/}
}
```

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Mention any acknowledgments or credits for libraries, datasets, etc., if applicable.
