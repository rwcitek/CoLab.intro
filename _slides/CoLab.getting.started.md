---
title: CoLab
description: Getting started with CoLab
theme: black

---

# Introduction
* Robert Citek, reverse engineer in biology

---

# Outline
* CoLab
* Notebook
* Cells
* Text demo
* Code demo
* Magics demo
* Mixing code and magics
* Three Use cases
* CoLab features

---

# CoLab
* Google product/service
* Modeled on Jupyter Notebooks
* https://colab.research.google.com/
* New Notebook

---

# Notebook
* Series of cells

---

# Cells
* Discrete items
* demo notebook - [Cells](https://colab.research.google.com/notebooks/basic_features_overview.ipynb#scrollTo=Id6tDF1HQSHD)

---

# Text
* Markdown
* demo notebook - [Text](https://colab.research.google.com/notebooks/markdown_guide.ipynb)

---

# Code
* Python
* others, but not easily in CoLab
* demo notebook - [Code](https://colab.research.google.com/notebooks/basic_features_overview.ipynb#scrollTo=KR921S_OQSHG)

---

# Magics
* Python coolness, may not be in other kernels
* enable non-python commands
* demo notebook - [Magics](https://colab.research.google.com/notebooks/basic_features_overview.ipynb#scrollTo=qM4myQGfQboQ)

---

# Mixing code and magics
* capturing magics output for use in Python
* using Python variable in magics
* demo notebook - [Magics interpolation](https://colab.research.google.com/notebooks/basic_features_overview.ipynb#scrollTo=zqGrv0blQSHj&line=1&uniqifier=1)

---

# Use case #1: Linux Phrasebook
* demo notebook - 

---

# Use case #2: Learning C
* demo notebook - 

---

# Use case #3: Symbolic Math
* demo notebook - [SymPy](https://colab.research.google.com/drive/12mdmsaDmWeLYGVbPfiAhPlTgScNduDmk)

---

# CoLab features
* https://colab.research.google.com/
* ToC
* Search-n-Replace
* Variable inspector
* File browser
* Code Snippets
* Comments
* Sharing
* Example Notebooks

---

# Summary
* CoLab
* Notebook
* Cells
* Text demo
* Code demo
* Magics demo
* Mixing code and magics
* Three Use cases
* CoLab features

---

# References
* CoLab - https://colab.research.google.com/
* Wikipedia - https://en.wikipedia.org/wiki/Project_Jupyter
* Jupyter https://jupyter.org/

---

---

---

---

---



# Convert Notebook to Markdown
You'll need to mount Google Drive first.


```python
ls -la ./drive/MyDrive/Colab\ Notebooks/CoLab.getting.started.ipynb
```

    -rw------- 1 root root 11526 Aug 10 20:30 './drive/MyDrive/Colab Notebooks/CoLab.getting.started.ipynb'



```python
!jupyter nbconvert --to markdown --output-dir=. ./drive/MyDrive/Colab\ Notebooks/CoLab.getting.started.ipynb
```

    [NbConvertApp] Converting notebook ./drive/MyDrive/Colab Notebooks/CoLab.getting.started.ipynb to markdown
    [NbConvertApp] Writing 10115 bytes to ./CoLab.getting.started.md



```python

```
