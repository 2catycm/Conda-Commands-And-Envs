https://mamba.readthedocs.io/en/latest/installation.html
https://github.com/mamba-org/mamba
其实安装就是这条命令：
```bash
conda install -n base --override-channels -c conda-forge mamba 'python_abi=*=*cp*'
```
bashrc中配置：
```bash
alias conda='mamba'
```