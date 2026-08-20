# Jupyter Python Practice

这是一个使用 **Jupyter Notebook**、**NumPy** 和 **SymPy** 完成线性代数与数值计算练习的仓库。Notebook 将题目说明、数学推导、Python 代码和运行结果放在一起，适合用于复习矩阵运算、线性方程组以及数值稳定性等主题。

## 内容概览

### [practice1 (1).ipynb](practice1%20%281%29.ipynb)

主要涵盖：

- 多项式插值与三次最小二乘拟合
- 矩阵的行最简阶梯形（RREF）与主元列
- 线性无关、列空间和线性方程组求解
- 线性变换以及一对一、映上的判断
- 转移矩阵和矩阵迭代模型

### [practice2.ipynb](practice2.ipynb)

主要涵盖：

- 使用向量方程建立矿产与能源生产模型
- 判断矩阵的列是否张成给定向量空间
- 矩阵可逆性、左右逆和矩阵幂
- 线性方程组的条件数与误差敏感性
- Hilbert 矩阵的病态性和浮点计算误差

## 技术栈

- Python 3
- Jupyter Notebook / JupyterLab
- NumPy
- SymPy

Notebook 当前使用的内核为 `Python 3 (ipykernel)`。

## 开始使用

### 1. 克隆仓库

```bash
git clone https://github.com/haha3356/jupyter-python-practice.git
cd jupyter-python-practice
```

### 2. 创建并激活虚拟环境

Windows PowerShell：

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

macOS / Linux：

```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 3. 安装依赖

```bash
python -m pip install --upgrade pip
python -m pip install jupyter numpy sympy
```

### 4. 启动 Notebook

```bash
jupyter lab
```

也可以使用经典界面：

```bash
jupyter notebook
```

在浏览器中打开任意 `.ipynb` 文件后，按顺序运行单元格即可复现实验结果。

## 仓库结构

```text
.
├── README.md
├── practice1 (1).ipynb
└── practice2.ipynb
```

## 学习建议

- 按照 Notebook 中的顺序运行代码，避免依赖尚未定义的变量。
- 修改矩阵或向量后重新运行相关单元格，观察秩、主元和解的变化。
- 对条件数较大的矩阵，比较理论解与浮点计算结果，理解数值误差如何被放大。
