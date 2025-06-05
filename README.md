# ECUST Beamer 模板

这是一个基于 Beamer 的华东理工大学演示文稿模板，提供了美观的幻灯片布局和丰富的功能支持。

## 功能特点

- 支持中英文双语
- 内置华东理工大学校徽和配色方案
- 支持数学公式、算法伪代码
- 支持参考文献引用
- 支持代码高亮显示
- 支持多列布局
- 支持图片和表格

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

## 许可证

本项目采用 MIT 许可证。详见 [LICENSE](LICENSE) 文件。

## 贡献

欢迎提交 Issue 和 Pull Request！

## 致谢

感谢所有为本项目做出贡献的开发者。 