# 恶补python

1. 如何用uv切换项目python版本

```
uv python pin [PYTHON_VERSION]
```

2. 如何热加载本地安装项目

```
uv pip install --editable .
```

3. 如何切换指定执行入口entry-point

```
[project.script]
NAME_OF_COMMAND = "NAME_OF_FILE:NAME_OF_FUNCTION"
```

