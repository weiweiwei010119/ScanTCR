# caTCRem

## 🧬Project Overview

T cells initiate anticancer immune responses at an early stage of tumorigenesis, thus enabling dynamic monitoring of peripheral blood T-cell receptor (TCR) repertoire changes as a promising strategy for early cancer detection. However, current TCR-based cancer detection methods focus on limited high frequency TCRs instead of repertoire-scale representation, overlooking numerous crucial cancer-associated TCRs (caTCRs). Herein, we propose ScanTCR, a computational framework for early cancer detection that introduces the first repertoire-scale encoding method capable of incorporating all TCRs. The ScanTCR exhibits remarkable precision in distinguishing cancer patients from non-cancer individuals using peripheral blood TCR. In a pan-cancer analysis encompassing seven cancer types, the ScanTCR attained an AUC of 0.873 (0.835–0.911), surpassing state-of-the-art (SOTA) TCR-based methods. Furthermore, ScanTCR identifies caTCRs whose corresponding T cells exhibit enhanced cellular immune capacity, demonstrating the biological interpretability. Collectively, our work proposes a TCR-based approach enabling repertoire-scale representation of immune receptors for noninvasive early cancer detection.

## 📁Directory Structure

* **data/**: Contains datasets and sample data required for the project. Users can find example datasets for testing  in this directory.
* **model/**: Stores model files used by the project. Users can find pre-trained models for specific analysis tasks in this directory.
* **code/**: Contains the source code of the project. These codes include data preprocessing scripts, model training scripts, and more. Users can find all the source code implementing the project's functionality in this directory and modify or extend it as needed.

## 🔧Installation & Dependencies

To run this project, you need to ensure that the following Python libraries are installed. You can use `pip` to install these libraries.

1. Clone the project repository to your local environment.
2. In the project's root directory, run the following command to install the dependencies:

```bash
pip install -r requirements.txt
```

**Note**:

* For the installation of PaddlePaddle, you may need to choose the appropriate installation command based on your environment (CPU or GPU) and Python version. You can find detailed installation guides on the [PaddlePaddle official website](https://www.paddlepaddle.org.cn/install/quick).
* If you encounter any installation issues, please check if your Python version and operating system support the library versions you want to install.

After installation, you should be able to run the code in the project. If you encounter any problems, please refer to the project's README file or contact the project maintainer for help.

👀 Additionally, if you want to execute the `01_process_reference_dataset.r` code, you need to ensure that **R** is installed on your system.

## 📚Usage Guide

### Data Preparation

* Place your dataset in the `data/` directory or specify the dataset location according to the paths in the code.
* Ensure that the dataset format is consistent with the format expected in the code.

### Running Analysis

* Find the corresponding script files in the `code/` directory and modify the parameters and configurations in the scripts as needed.
* Use the command line or an IDE to run the scripts to perform data preprocessing, model training, and result analysis tasks.
