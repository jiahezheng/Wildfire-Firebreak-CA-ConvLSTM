# Wildfire-Firebreak-CA-ConvLSTM

This repository contains the code and data used in the paper *"Predicting Spatio-Temporal Wildfire Propagation with Firebreak Placement Using Deep Learning."*

## Description

All the codes used are available in the [Codes](/Codes) folder.

All the generated plots are available in the [Plots](/Plots) folder.

The data used in the paper can be accessed from the [Data folder](https://drive.google.com/drive/folders/1pJ7lZQjbbkevEkDort_xLwYg72Bdgv_c?usp=sharing) (Google Drive).

## Getting Started

### Dependencies

To run the code, you will need:

* **Google Colab** (recommended for execution)
* **Google Colab GPU** (recommended if running deep learning models)

### Installation

1. Clone or download the repository.
2. The [Codes](/Codes/) and the [Plots](/Plots/) directories will contain the corresponding scripts and output.
3. Set the `directory` variable to the local path where you store the files:
   ```python
   directory = ''  # Your directory path
   ```
This path should be updated at the start of each Jupyter notebook in the [Codes](/Codes) folder.

4. The data used in the paper is available in the Data folder. For example, to access a specific data file:
```
directory + 'Data/training_data/forest_fer_rand_ig_rand_wind_rand_tilt_4_ptbar_ml_state.npy'
```
5. The required packages are detailed in each `.ipynb` file. If using Google Colab, they will be automatically imported or installed.

### Running the Program
These notebooks are designed to be run on Google Colab. Since most of the code involves deep learning models, using a GPU is highly recommended for optimal performance.

## Authors

Contributors names and contact info

* Jiahe Zheng
* Sibo Cheng [Email](sibo.cheng@enpc.fr)

## Version History

* 0.1
    * Initial Release

## License

This project is licensed under the [MIT](https://choosealicense.com/licenses/mit/) License - see the [LICENSE](/LICENSE.md) for details

## Acknowledgments
