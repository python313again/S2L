
# S2L

An automation GUI that converts cell images into ROI's. You can also train models with this tool.

## Example image generated by this program
![Example](https://raw.githubusercontent.com/aftabnadim/S2L/v0.2/example.png)
![Example](https://raw.githubusercontent.com/aftabnadim/S2L/v0.2/gui.png)


## Roadmap

- More features
- AMD and CPU only support ( Currently only supports CUDA )

## Credits

 - [Cellpose](https://github.com/MouseLand/cellpose)


## Prerequisites
- CUDA 12.4 Toolkit
    
## Installation

Clone this repo and install requirements. I recommend to do this in an env
```
git clone https://github.com/aftabnadim/S2L.git && cd S2L && pip3 install -r requirements.txt
```
Install Pytorch.
```
pip install torch
```
or Install Pytorch CUDA
```
pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu124
```
Start GUI
```
python main.py
```
## Dataset Example

A dataset example is found in the ExampleDataset folder, use that for guidelines. (Files can be named anything)
