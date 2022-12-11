# zuxun

[祖训](https://xiang-family.github.io/zuxun/)

## Installation (Linux)
```bash
pip install mkdocs
pip install mkdocs-with-pdf
pip install mkdocs-gitbook
```
## Contribute
0. 打开codespace
1. modify [documents/docs/*](https://github.com/Xiang-Family/zuxun/tree/main/documents/docs)
2. ```bash
   cd documents
   python -m mkdocs serve # 看看有没有报错
   
   python -m mkdocs build -d ../docs # 之后github pages会重新部署
   
   # push
   git add --all
   git commit -m "updates"
   git push
   ```
