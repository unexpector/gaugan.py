# gaugan.py
A Python script for automating processing images through NVIDIA's gauGAN project (http://nvidia-research-mingyuliu.com/gaugan/)
## Requirements
- [Python 3](https://www.python.org/downloads/ "Python official download page")
- [Requests](https://pypi.org/project/requests/ "Requests @ pypi.org")
## Usage
Add your input images (must be PNG format) to the 'in' folder. Run the script:

```python gaugan.py -s (or --style) [whatever style you want, a number or 'random']```

Example: ```python gaugan.py -s random```

Output files will be placed in the 'out' folder.
