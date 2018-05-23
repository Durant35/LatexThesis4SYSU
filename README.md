# 中山大学硕士研究生毕业论文/答辩PPT Latex模板
- [x] 改进原仓库由于没人维护，部分模板不适用，以及Ubuntu下无法渲染等问题。

## What functions?
+ [普通版本](./samples/demo.pdf)
+ 盲审版本
+ 纸质打印版本
+ [图书馆数据库上传版本](./samples/submit.pdf)
```latex
% 生成打印文档，插入空白页
\newif\ifprint
% 需要打印时取消注释
%\printtrue

% 生成盲审使用文档
\newif\ifreview
% 需要生成盲审使用文档时取消注释
%\reviewtrue

% 生成上传提交文档
\newif\ifsubmit
% 需要生成上传提交文档时取消注释
%\submittrue
```

## How to use?
+ [Win + TexStudio](https://github.com/Durant35/LatexThesis4SYSU/wiki/Win10)
+ [Ubuntu + TexStudio](https://github.com/Durant35/LatexThesis4SYSU/wiki/Ubuntu16.04)

## Thanks
根据天津大学学位论文LaTeX模板修改的符合中山大学毕业论文要求的LaTeX模板。

原天津大学学位论文LaTeX模板来源：https://code.google.com/p/tjuthesis/ 使用模板可参考原模板说明。