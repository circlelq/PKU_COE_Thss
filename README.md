# PKU_COE_Thss

北京大学工学院本科毕业论文参考模版。作者在写本科毕业论文的时候编写了此模版，在此发布在网上给大家使用。此模版已有多人使用并通过了教务审核。

模版将不断更新，若工学院教务修改了模版，请联系我。一般情况下模版更新后只需要替换 `setting.tex` 文件。

## 注意事项

- 本模版已更新到 2023 年。
- [工学院论文格式要求网站](https://www.coe.pku.edu.cn/jxzs/bksjy/cyxz/xscyxz/bylw/index.htm)。
- 请使用完整的 $\TeX$ live 包进行编译，此模版使用了大量的包，请勿使用 CTeX 软件（非包）， CTeX 软件已停止更新。
- 本模版不包括封面，请用学院给的模版的封面生成 PDF 后放到第一页。
- 您可以使用您电脑上的字体，$\LaTeX$ 默认字体可能无法显示某些生僻字。
- 全文自动将全角符号变为半角，您可以在 `setting.tex` 文件的最后去掉这个设置。

## 使用建议

- 建议使用多文件的方式，文章主体内容在 `chap` 文件夹里，您可以复制 `chap1.tex` 后编写之后的章节，并在 `main.tex` 里导入。

## 个性化设置

- 各种设置都放在了 `setting.tex` 文件里，可以方便地修改设置。
- 字体设置在 `main.tex` 文件里。
- 链接的颜色设置为了[北大红](https://vim.pku.edu.cn/bsgf/index.htm)，在 `setting.tex`，您可以根据自己的喜好修改颜色。

```tex
\definecolor{PKUred}{cmyk}{0,1,1,0.45}
```

## 关于字体

教务要求使用黑体，宋体，楷体指的是 word 里的黑体，宋体，楷体，而这几款字体实际是北京中易公司开发的非商用字体。事实上黑体指无衬线字体，北京中易公司开发的黑体只是黑体中的一款。个人建议大家和教务确定“黑体”是否特指，若不特指，可以使用可商用字体，例如思源的一系列字体。

## 线上模版

- texpage：https://www.texpage.com/template/6850a902-9ed6-468e-b753-90af2643e934

- overleaf：https://www.overleaf.com/latex/templates/pku-coe-thss/hzzgndtjtthq

线上模版版本不一定是最新的，请以 gitee 上的内容为准。https://gitee.com/circlelq/PKU_COE_Thss

## 联系方式

如有问题，欢迎给我发邮件，或者发 issue。考虑到网络稳定等问题，推荐在 [gitee](https://gitee.com/circlelq/PKU_COE_Thss) 上发 issue 或 pull request。

袁磊祺 yuanlq@pku.edu.cn ， circlelq@outlook.com

## $\LaTeX$ 补充资料

初次上手建议使用 Tex Live + VS code 的方案。安装可参考我之前写的[推送](https://mp.weixin.qq.com/s/9HbvHWSiQqASwhcWt1esgw)。进阶用户可以使用 TeX Live + NVIM 的[方案](https://castel.dev/post/lecture-notes-1/)。

$\LaTeX$ [讲座视频](https://www.bilibili.com/video/BV1nv4y1Q7fz)。

### 推荐资料

- *LATEX入门* 刘海洋编著(图书馆有库存)
- Drew Neil, *Practical Vim*. (图书馆有中文版)

## License

MIT
