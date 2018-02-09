# 2018 MCM Latex Template美赛模板

推荐使用vscode，参考[VS Code 与 LaTeX 真乃天作之合](https://www.jianshu.com/p/57f8d1e026f5)

# usage

```
{
    "command": "latexmk",
    "args": [
        "-synctex=1",
        "-interaction=nonstopmode",
        "-file-line-error",
        "-pdf",
        "%DOC%"
    ]
}
```
