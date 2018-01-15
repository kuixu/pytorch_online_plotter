# pytorch_online_ploter
Online meter ploter for pytorch. Real time ploting Accuracy, Loss, mAP, AUC, Confusion Matrix 


## Basic MNIST Example

```bash
pip install -r requirements.txt
python mnist.py
# CUDA_VISIBLE_DEVICES=1 python mnist.py  # to specify GPU id to ex. 1
```


## Real time ploting 

Open your browser with URL: 
```bash
http://localhost:9999
# or
http://ip:9999
```

![visdom.png](visdom.png)
