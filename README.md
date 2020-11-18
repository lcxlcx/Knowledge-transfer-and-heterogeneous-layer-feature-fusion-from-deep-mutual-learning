# Introduction
We do not focus on designing a deeper or more complex CNN model. We aim to establish connections between different networks and transfer valuable knowledge from them for effective breast cancer histopathological images classification. Our ideas mainly derive from model distillation and mutual learning. The model distillation starts with a powerful (deeper or wider) pre-trained teacher network, which transfers valuable knowledge to a small but untrained student network. Although, more powerful student networks can be acquired, essential performance improvements are very small. And the model distillation method is one-way. To better address the above-mentioned problems, we plan to design a novel two-way knowledge transfer model for effective histopathological image classification. The natural idea derives from deep mutual learning (DML) is related to but different from the model distillation method. It can realize two-way knowledge transfer through collaborative training in a network cohort without changing the network structure. This helps to better handle the data sparsity problem in the field of breast cancer histopathological image classification. Although DML has established the connections between different neural networks, the complementary information of the heterogeneous-layers in each network is not fully utilized. In paper **"Heterogeneous-layers feature fusion from deep mutual learning for breast cancer histopathological images classification"**, we proposed the **HF<sup>2</sup>-DML** model and addressed this issue. Furthermore, we hope that our model uses simple network structures and is easy to train. Meanwhile, with the improvement of recognition accuracy, the generalization ability of the proposed model can also be improved. 
# HF<sup>2</sup>-DML Model
The HF<sup>2</sup>-DML model schematic
![HF2-DML](https://i.loli.net/2020/11/18/3yaT9nkPH2B8ZQq.png)
