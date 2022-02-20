# 常用的conda环境配置文件.

* 输出conda环境文件(注意其中带有明确的版本信息):
```
conda env export --no-builds | grep -v "prefix" > MET.yml
```

* 利用yml文件来创建conda环境:
```
conda env create -f MET.yml
```