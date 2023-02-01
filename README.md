# Code
Perceptual and Position-aware Important Distance for Time Series

# Dataset

Dataset: https://www.cs.ucr.edu/~eamonn/time_series_data_2018/

Please download dataset and put it in \dataset\. 

# Dependencies: 

Python 3.8 and above

Numpy 1.19.2 and above

Scipy 1.7.2 and above

Please install the below library before running the code.

pip install numpy

pip install scipy

pip install scikit-learn

# Usage: 

You can run the command: 

Original Version PISD:

python original_pisd/pisd.py --dataset_pos 2

python original_pisd/pisd_f.py --dataset_pos 2

or

python original_pisd/pisd.py --dataset_name ArrowHead

python original_pisd/pisd_f.py --dataset_name ArrowHead

Speed Up Version PISD:

python speedup_pisd/pisd.py --dataset_pos 2

python speedup_pisd/pisd_f.py --dataset_pos 2

or

python speedup_pisd/pisd.py --dataset_name ArrowHead

python speedup_pisd/pisd_f.py --dataset_name ArrowHead

k-PISA:

python k_pisa/k_pisa.py --dataset_pos 2

or

python k_pisa/k_pisa.py --dataset_name ArrowHead

# Classification Result
You can see the full results on 112 UCR datasets in `results/`