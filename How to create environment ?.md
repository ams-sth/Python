## **Environment Setup Guide**

### **1. Conda Environment**

**Step 1: Create a new environment**

```bash
conda create -n mycondaenv python=3.11
```

**Step 2: Activate environment**

```bash
conda activate mycondaenv
```

**Step 3: Install packages**

```bash
conda install pandas numpy matplotlib
```

**Step 4: List installed packages**

```bash
conda list
```

**Step 5: Remove a package (if needed)**

```bash
conda remove matplotlib
```

**Step 6: Deactivate environment**

```bash
conda deactivate
```

---

### **2. venv Environment**

**Step 1: Create a new environment**

```bash
python -m venv myvenv
```

**Step 2: Activate environment**

```bash
# Git Bash or PowerShell
source myvenv/Scripts/activate
# CMD
myvenv\Scripts\activate
```

**Step 3: Install packages from `requirements.txt`**

```bash
pip install -r requirements.txt
```

**Step 4: List installed packages**

```bash
pip list
```

**Step 5: Deactivate environment**

```bash
deactivate
```

---

### **Notes / Tips**

* Conda is better if you want precompiled packages and cross-language dependencies.
* venv is lighter and built into Python, but you handle packages manually.
* Always keep a `requirements.txt` for reproducibility when using venv.
  
```bash
pip freeze > requirements.txt
```

* Conda can also export an environment file:

```bash
conda env export > environment.yml
```

This can be shared or recreated on another machine:

```bash
conda env create -f environment.yml
```
