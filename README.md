# Affable Assignment

[Affable Data Science Task](https://beaffable.notion.site/Affable-Data-Science-Task-4bd49129d1b6404f8c96c098785a25d0)

## Quick Start

### Python

1. Install Anaconda following the [link](https://docs.anaconda.com/anaconda/install/index.html).

2. Create and activate environment using the following commands.
```
# Create Python environment
conda create --name affable-assignment python=3.7.10

# Check Python environment
conda info --envs

# Activate environment
conda activate affable-assignment

# Deactivate environment
conda deactivate

# Remove environment
conda remove -n affable-assignment --all
```

3. Install `requirements.txt`.
```
pip install -r /path/to/requirements.txt
```

4. `__init__() got an unexpected keyword argument 'cachedir'` error in `mglearn`

Change `memory = Memory(cachedir="cache")` to `memory = Memory(location="cache")` in `plot_pca.py` and `plot_nmf.py`

### Training

All the training codes are in the `Solution.ipynb`, you can replace the `data.csv` file with new dataset to retrain the model. The model is stored in the `classifiers` folder.

### Experiment
| Training Accuracy | Validation Accuracy |
| :----: | :----: |
| 84% | 80% |

### Test

All the test codes are in the `Test.ipynb`, you can add new dataset and replace the `data.csv` path with new the dataset name in the `Test.ipynb` to test the model. Please make sure the new dataset and the training dataset have the same columns.
