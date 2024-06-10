## AutoThesis
项目地址：https://github.com/Zhuozhuo313/AutoThesis

最新版的Readme报告、演示视频与源代码见仓库

#### 项目背景

我们的AutoThesis是一个旨在自动化生成学术论文的项目。通过结合自然语言处理技术、多模态生成技术与用户交互，AutoThesis能够自动构建论文大纲，生成详细的图文并茂的论文内容。

#### 选题原因

一方面来说，是受到本次人工智能交互技术课程的启发。我们在课程中学到了大模型API的调用，多模态的运用，Gradio可视界面的编写，我们的项目较好地融合运用了这些内容。

另一方面来说，天下苦写材料、写论文久矣，对于不重要的论文，如果能够利用AI技术帮助我们迅速完成，可以极大地提高我们的学习工作效率，进而提升幸福指数。

#### 我们做了什么

**(1)** 实现自动生成论文功能。我们撰写Prompt，通过多次自动调用文心一言API，实现仅需一次用户输入，即可自动撰写提纲并根据提纲自动撰写每个具体部分

**(2)** 添加字数限制功能。通过AI自检测与重生成，对论文整体的字数进行限制

**(3)** 添加知识库功能。允许用户输入文件作为知识库，允许网络搜索文件作为知识库，在论文中自动对其进行引用，并自动添加到参考文献中

**(4)** 添加AI自改进功能。允许其对撰写的每个部分自动提供专业评价与修改建议，对于评分低的部分进行改进

**(5)** 添加AI配图功能。论文撰写完成后，自动检测需要配图的地方，调用文心一言AI绘图API进行配图

**(6)** 编写Gradio用户交互界面，可以实时显示当前进度和生成内容

**(7)** 自动整理格式，将生成好的论文输出到word文件

#### 项目特色

- **效率提升**: 可以在短时间内得到一个结构完整的论文大纲和样例输出，帮助我们快速上手。
- **专业指导**: 项目内置的评价系统能够提供专业的论文写作指导，帮助用户改进论文内容。
- **灵活性**: 用户可以根据自己的需求，定制论文的各个部分，使其更加符合个人或学术要求。

#### 结果与收获

结果：成功实现了理想中的功能，在实际应用中起到了不错的作用。美中不足的是，一方面多次调用API导致生成时间较长（约10分钟），另一方面多次调用API的费用比较贵，尤其是AI作图

收获：拥有了更多大模型Prompt的调试经验，掌握了格式化Prompt的方法与技巧；学会了熟练调用文心一言API，掌握了其接口；掌握了Gradio更多技巧和功能；**最重要的，Debug能力更上一层楼**（有些很简单的bug真的导致了很严重的问题）

#### 贡献比例
李重灼 45%
邵方昊 45%
朱飞衡 10%

