# Koppen_Climate_Classification

## 🔧 How to Use the Data Files

This repository includes climate data files stored in the following directories:

- `rain/`: Precipitation data (CSV format)
- `temp/`: Temperature data (CSV format)

To load the files in your Python scripts or Jupyter notebooks,  
make sure the path to each folder is correctly set for your local environment.  
For example:

```python
import os

# Temperature data path
path_t = "./temp"  # Or use full path if needed
dir_t_list = os.listdir(path_t)

# Precipitation data path
path_r = "./rain"
dir_r_list = os.listdir(path_r)

