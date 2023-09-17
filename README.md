# python_goto
为Python提供goto支持
源于python包[goto-statement](https://pypi.org/project/goto-statement/#files)，并使用[第三方补丁](https://github.com/cdjc/goto/blob/master/goto.py)修改了goto.py以提供Python3.11及以上版本支持。
理论上支持Python2/3，在Python 3.8.0/3.9.1/3.12.0rc1上实测有效。

## 安装

下载whl包后在其目录下执行`pip install goto`

## 用法

```python
from dominate.tags import label#自行使用pip install dominate=2.8.0安装
from goto import goto
label .start
#...
goto .start
```
