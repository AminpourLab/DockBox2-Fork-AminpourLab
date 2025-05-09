# DockBox2 - Updated Fork

## About This Repository

This is a **forked version** of the original [DockBox2](https://github.com/jp43/DockBox2) repository, developed by Dr. Jordane Preto.

# DockBox2

Graph Neural Network Model to Improve Docking Predictions

**DockBox2 (DBX2)** is a sequel to DockBox that combines the concept of consensus docking with machine learning to improve docking predictions.  
In short, DBX2 provides the ability to train and run a GNN model based on inductive representation learning (GraphSAGE)  
to better interpret docking results (e.g., generated by DBX).

DBX2 can be used in two modes:  
- **Node mode**: estimates pose correctness  
- **Graph mode**: estimates binding affinity

---

## Installation

The easiest way to install DockBox2 is to create a virtual environment.  
This allows DockBox2 and its dependencies to be installed in user-space without clashing with system-wide packages.

Once `virtualenv` has been properly installed, run the following in the terminal:

```bash
virtualenv env
```

Then activate the virtual environment:

```bash
source env/bin/activate
```

> ⚠️ Don't forget to activate your environment every time you open a new shell.

Finally, navigate to the DockBox2 installation directory and run:

```bash
python setup.py install
```

✅ **Installation is complete!**