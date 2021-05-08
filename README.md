# PhotoWakeUp

Init:

```python
python3 -m venv .venv
source .venv/bin/activate
```

1) person detection:

we use the state of the art algorythm: detectron2

https://detectron2.readthedocs.io/en/latest/tutorials/install.html  

2) person segmentation:

detectron + dense crf

3) 2D body pose

To be tested

4) SMPL:

```
SMPL_LOCATION=/home/jo/python\ projects/PhotoWakeUp/SMPL_python_v.1.1.0/smpl
export PYTHONPATH=$PYTHONPATH:$SMPL_LOCATION
```

