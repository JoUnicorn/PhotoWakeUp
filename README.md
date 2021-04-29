# PhotoWakeUp

Init:

```python
python3 -m venv .venv
a, b = 0, 1
while b < 10:
    print(b)
    a, b = a, a + b
```

1) person detection:

we use the state of the art algorythm: detectron2

https://detectron2.readthedocs.io/en/latest/tutorials/install.html  

2) person segmentation:

detectron + dense crf

3) 2D body pose

To be tested
