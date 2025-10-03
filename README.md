## Installation
```
git clone https://github.com/IRL2/nanover-recording-converter.git
cd nanover-recording-converter
conda install -c irl -c conda-forge nanover-server
pip install -e .\nanover-recording-converter --config-settings editable_mode=compat
python ./compile_proto.py --proto-dir=./protocol --python-dir=./nanover-recording-converter/src
```

## Usage
```
nanover-recording-convert recording.traj recording.state
```
