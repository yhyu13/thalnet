# thalnet
Open-source implementation of ThalNet (https://arxiv.org/pdf/1706.05744.pdf)

---

## Oct 13th Mnist success!
All models are under 60,000 total parameters.
### MLP
![](/figure/MLP.png)
### GRU 
![](/figure/GRU.png)
### ThalNet-GRU 
![](/figure/ThalNet_GRU.png)
### ThalNet-FF-GRU
![](/figure/ThalNet_FF_GRU.png)

## Learning Curve Comparison
![](/figure/Learning_curve.png)

## MNIST reding weights visualization

### Initial reading weights
![](/figure/Initial_reading_weights.png)

### After training
![](/figure/mnist_learned_reading_weights.png)

## Demonstrate ensemble property (MNIST)

This section includes tests on deleting side modules after training

### Cut all side modules
![](figure/cut_all_side_moudles.png)

### Cut module 2
![](figure/cut_module2.png)

### Cut module 3
![](figure/cut_module3.png)

