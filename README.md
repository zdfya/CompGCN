# CompGCN (dgl)

![image](https://github.com/user-attachments/assets/26b20f76-d986-4988-81b3-f681177ce0db)
---


Before you run, you should install **dgl**,you can find it in https://www.dgl.ai/



```python 
python run.py --score_func conve --opn corr --gpu 0 --epoch 500 --batch 256 --n_layer 2
```

The corresponding experimental procedures and final results will be displayed in the automatically generated log file.

### Dataset:
- We use FB15k-237 and WN18RR dataset for knowledge graph link prediction.
- FB15k-237 and WN18RR are included in the data directory.
