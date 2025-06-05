# ECUST Beamer 模板

华东理工大学演示文稿模板Beamer


- 支持中英文双语

- 支持数学公式、算法伪代码
- 支持参考文献引用
- 支持代码高亮显示


## 环境要求

- TeX 发行版（推荐使用 TeX Live 或 MiKTeX）
- XeLaTeX 编译器
- BibTeX 用于参考文献处理

## 使用方法

1. 克隆仓库：
```bash
git clone https://github.com/your-username/ecust-beamer.git
```

2. 编译文档：
```bash
# 基本编译
xelatex slide

# 处理参考文献
bibtex slide

# 再次编译两次以正确显示引用
xelatex slide
xelatex slide
```

## 文件结构

- `slide.tex`: 主文档文件
- `ref.bib`: 参考文献数据库
- `images/`: 图片资源目录
- `ECUST.sty`: 自定义样式文件

## 自定义

- 修改 `slide.tex` 中的个人信息
- 在 `images/` 目录中添加或替换图片
- 根据需要修改 `ECUST.sty` 中的样式设置

