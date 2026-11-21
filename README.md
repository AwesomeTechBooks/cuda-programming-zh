# CUDA 编程：从并行模型到工程实践

一本围绕可运行程序和实测数据展开的中文 CUDA 教程，7 部分 36 章：从第一个 kernel 讲起，
到性能分析、异步执行、现代 GPU 的协作机制、常用库、一个完整的分子动力学案例和系统层面的话题。
书中的数字都在同一台 RTX 5060 Laptop GPU（CUDA 13.3）上实测得到。

在线阅读：<https://awesometechbooks.github.io/cuda-programming-zh/>

- `src/`：各章 Markdown 和插图，`src/SUMMARY.md` 是目录；`src/code/chNN/` 是各章的示例程序，
  每个程序开头写有编译命令。`book.toml`、`theme/` 是 mdBook 配置。
- `runs/chNN/`：示例程序的完整输出存档，正文引用的输出都出自这里。
- 网页由 GitHub Actions 调用 [platform](https://github.com/AwesomeTechBooks/platform) 的流水线用 mdBook 构建，仓库里不含生成的 HTML。
- 旧版（14 部分 87 章）不再更新，也不再有网页版。Markdown 源稿留在已归档的旧仓库里，可以在 GitHub 上[从目录开始读](https://github.com/winterYANGWT/Awesome-Tech-Books/blob/main/books/cuda-programming-zh-legacy/src/SUMMARY.md)。
- 许可证：文字和插图 CC BY 4.0（见 `LICENSE`），示例代码 MIT（见 `LICENSE-CODE`）。
- 本书不是 NVIDIA 官方文档，未经 NVIDIA 审阅或认可。NVIDIA、CUDA 是 NVIDIA Corporation 的商标。
- 本书在 AI 辅助下编写和整理，欢迎通过 issue 指正错误。
