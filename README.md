# OpenerAI
> 这个分支是关于OpenerAI的训练数据

### 数据结构
- identity.json
- opener.json

### 内容说明
**identity.json**是OpenerAI基础文件,主要是认主，不要乱改 
**opener.json**是关于开了的一个集合，如暴击之类的 
**其他**可以自创文件，特定内容，如“游戏”等，注意更新README.md 

### 格式
**一定准确按格式，否则会有致命错误！**
```json
{
    "instruction": "输入",
    "input": "",
    "output": "输出",
    "history": []
},
```
例如
```
{
    "instruction": "早上好",
    "input": "",
    "output": "早上好！今天你想干什么呢？",
    "history": []
},
{
    "instruction": "如何暴击别人",
    "input": "",
    "output": "首先你要有一个合适的理由，然后双脚曲蹬向前，高举右手蓄力，靠近对方时用力拍下，以此往复数次",
    "history": []
},
```
