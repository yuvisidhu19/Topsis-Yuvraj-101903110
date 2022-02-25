# Topsis
This is a simple python package to perform Technique for Order of Preference by Similarity to Ideal Solution (TOPSIS) from a csv file using command line interface.

Format of input from CLI:

```python program.py InputDataFile Weights Impacts ResultFileName```
  
Example of input from CLI:
  
```python example.py data.csv "1,2,3,2,1" "+,-,-,+,+" result.csv```

PS: Weights and impacts should be provided as strings. '+' for higher impact and '-' for lower impact.

Example code (Run this exact code using command line):
```
import importlib
foobar = importlib.import_module("Topsis-Yuvraj-101903110")
foobar.perform_topsis()
