# 环境配置

## QQ 机器人

### 安装脚手架

确保你已经安装了 Python 3.8 及以上版本，然后在命令行中执行以下命令：

1. 安装 pipx

```bash
python -m pip install --user pipx
python -m pipx ensurepath
```

2. 安装脚手架

```bash
pipx install nb-cli
```

### 创建项目

使用脚手架来创建一个项目：

```bash
nb create
```

注意 QQ 官方机器人驱动器要选择

### 运行项目

```bash
cd xiao-mai && source .venv/bin/activate
nb run --reload
```