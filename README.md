```
conda install -c irl -c conda-forge nanover-server
pip install -e .\nanover-recording-converter --config-settings editable_mode=compat
python ./compile_proto.py --proto-dir=./protocol --python-dir=./nanover-recording-converter/src

nanover-recording-convert recording.traj recording.state
```
