1.使用了git clone   git add    git commit -m  git push origin 
conda create -n   conda create -n plot_env python=3.9
conda activate激活虚拟环境 
2.优点：不同项目可使用独立的 Python 版本和包，避免冲突。  
  难点：未正确初始化 Conda 时，conda activate一直报错。
3.每次提交仅包含单一功能的修改，便于回退和追踪问题。
4.CondaError: Run conda init before conda activate报错，未初始化。
运用conda init进行初始化。或者rm-rf plot.
