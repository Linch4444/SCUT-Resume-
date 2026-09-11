# SCUT-Resume-
这是为华南理工工业工程IE同学求职准备的Latex简历，只需你准备好MikTex，将main.tex中的代码给AI后，提出你的要求，就能够修改其中代码输出一份工整的简历啦！
本模板的特性包括：
- 通过调整排版提高简历的信息密度。
- 提供超链接、脚注、非重点内容的排版示例。
- (🖼️)支持插入校徽与头像（请看代码注释，已包含华南理工、中山、华南农业、华南师范、暨南大学）。
<img width="1330" height="301" alt="xiaohui" src="https://github.com/user-attachments/assets/fee2719b-4a88-4592-9a95-d3866c30bb11" />
<img width="1067" height="249" alt="标准字中文校名全称模式" src="https://github.com/user-attachments/assets/ec61d067-a005-49ba-a8e1-5fc158ccc1be" />
<img width="627" height="188" alt="zhongda" src="https://github.com/user-attachments/assets/578d55bb-4323-47dd-80b7-82f18201e53c" />
<img width="1100" height="794" alt="SCNU xiaohui" src="https://github.com/user-attachments/assets/f224cd26-a825-4b1e-a0f5-eb6330228d5d" />
<img width="1050" height="758" alt="Jinan" src="https://github.com/user-attachments/assets/f3882412-299c-45f7-a5a4-f203bdc6cd2b" />



## 使用方法
### 本地编译
0. 确保已经安装 LaTeX 发行版。
1. **克隆或下载**本项目代码。
2. 直接运行 `latexmk` 即可。

## 宏
常用用法可参考 `main.tex` 中的示例内容。
- `\ResumeName{}` 定义简历标题（一般是姓名）。
- `\ResumeContact{}` 添加一个联系方式。
- `\ResumeContacts{itemA, itemB, itemC}` 添加多个联系方式。
- `\ResumeTitle` 渲染标题和联系方式。
- `\section{}` 节标题。
- `\ResumeItem[1]{2}[3][4]`
  1. 可选参数，控制 PDF 书签内容。如果不提供则采用参数 2。
  2. 项标题，左对齐。
  3. 可选参数，补充信息，在参数 2 后显示。
  4. 可选参数，右对齐。
- `\GrayText{}` 改变文字内容为灰色。
- `\ResumeUrl{}{}` 带有下划线的 `\href` 命令，与 `\href` 用法相同。

> `[]` 为可选参数， `{}` 为必需参数。

## 包依赖
**如果你使用 TeXLive/MiKTeX 等主流发行版，可以直接使用本项目，无需手动安装依赖。**

## 致谢

该项目主要代码来源于 [github.com/fky2015/resume-ng](https://github.com/fky2015/resume-ng) ，谢谢大佬！
基于“提高一页简历中的信息密度”这一排版思路而进一步改进，增加比赛、实践、社团等项目标题
再次感谢！



