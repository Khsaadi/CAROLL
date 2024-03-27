## Learn From One Specialized Sub-Teacher: One-to-One Mapping for Feature-Based Knowledge Distillation
#### This repository contains the code for the paper [Learn From One Specialized Sub-Teacher: One-to-One Mapping for Feature-Based Knowledge Distillation](https://aclanthology.org/2023.findings-emnlp.882.pdf) (EMNLP-Findings 2023).

![img](https://github.com/Khsaadi/CAROLL/assets/58224339/468d1cb1-c4d1-4c04-864d-fc88491495ad)

#### For more details about the technical details of ReptileDistil, please refer to our paper.

**Installation**

Run command below to install the environment (using python3):

```
pip install -r requirements.txt
```

**Data Preparation**

Run command below to get GLUE data:

```
python download_glue_data.py --data_dir glue_data --task all
```

Run command below to get SQUAD-V1 data:

```

```

Run command below to get IMDB data:

```

```

**Student Initialization**



**Fine-tuning**

Run command below to get fine-tuned teacher model for every task of GLUE:

```
# GLUE

# SQUAD

# IMDB

```

**Distillation**

Run command below to get distilled student model for every task of GLUE:

```
# RTE

# SQUAD

# IMDB

```

**Results**

On the GLUE development set:
<img width="1076" alt="results" src="https://github.com/Khsaadi/CAROLL/assets/58224339/354983a0-538e-4344-b5e0-4a8c394dcd79">


