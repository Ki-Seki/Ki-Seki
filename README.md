[English](./README.md) | [中文](./README_zh.md)

# 😉 About Me

My name is Ki Seki, you can also call me as Little K. I'm currently an undergraduate of Henan University of Economics and Law. I'm a coder and a Sk8er. Aloha~

<img align="center" src="https://github-readme-stats.vercel.app/api?username=Ki-Seki&show_icons=true&include_all_commits=true&hide_border=true" alt="My github stats" />

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Ki-Seki&hide=CSS,SCSS&hide_border=true)](https://github.com/anuraghazra/github-readme-stats)


# 🔧 My Skills

- Python
  - Web Crawling: Scrapy, Selenium, Requests, BeautifulSoup, Re, ...
  - Web Developing: Django
- C/C++
- MATLAB
  - Heuristic Algorithm Implementation: Particle Swarm Algorithm, Simulated Annealing Algorithm, ...
  - Multi-objective Optimization
- HTML / JavaScript / CSS
- MySQL
- ...

# 🔬 My Research Interests

- Recommender System
- Graph Neural Network
- Meta Learning
- ...

# 💡 Some Ideas

<details><summary>CLICK ME FOR DETAILS</summary>
<p>

## 动态学习的推荐系统

基于手机使用哲学，建立试图在算法推荐和人工审核之间相平衡的推荐系统。系统应该不断学习用户的习惯，使推荐和审核之间的平衡呈现动态平衡。

## 开源单词工具

以单词的义项为核心，致力于为用户打造全面的单词工具，同时面向开发者提供适当 API，以便再开发。这些单词工具包括但不限于

- **单词量实时统计工具**：基于k均值和推荐系统理论的单词量统计工具，同时实现年纪年龄等猜测反推。建立这样的模型，认为每个年龄段所学新单词的增量，在总的人群当中是相仿的。所以将单词利用 K 均值聚类，就可以建立年龄段和某一单词集之间的联系。然后根据协同过滤的理论，猜测测试者的单词量或其真实年龄。
- **用户自建词库**
- **可打印单词表自动生成工具**
- **多源单词爬虫工具**
- **多平台背诵工具**

## 工作空间

面向计算机应用的更高层抽象，让刷视频，玩游戏等娱乐项目；让 word，浏览器等工作项目；或者某个基于特定目的的应用集合做成一个工作空间。让这个工作空间可以跨平台同步，让这个工作空间不因为设备差异而中断。

## Markdown 文章一键全平台分发

## AI 辅助的 SE

## 快速收敛的梯度下降

每次进行梯度下降的时候，随机出一个参数，与当前参数的比较，比较他们的损失函数，若小，两参数直接相减得到梯度，作为下一次下降的值和方向；若不小则按照传统的BGD或SGD下降

## AI能否生成diagram

## 所有的一切都是图

飞书里的文档可以互相引用，飞书的每个文档也是非常结构化的超文本，非常容易被学习。那么如果把诸多互相引用起来的文档连起来构成一个大的知识图谱，那么这将可以推理出来更多的内容

我们在做论文推荐，引用预测的时候都把文章作为最小的分割单元，这真的对嘛，所有的文章真的是对等体嘛？知识是有层次的有结构的，那文章可能就存在隶属关系，而非并列关系。最小分割单元可以是段落，甚至是字词。

学术界总是提子图，n-hop neighbor之类的，如果提出一切都是图的概念就可以超越这些基本概念的影响了。比如子图，不过就是一种特殊的图，那甚至可以有子图的子图，embedding的embedding；再比如几跳的信息聚合，这不过是一种特殊子图中数据的聚合；再比如community的概念，这也是图。

如果引入所有一切都是图的概念，那么我们可以学习图中的对等结构，比如你给我两篇论文，假如他们的行文顺序内容安排结构是相似的，那就代表他们有相似的图结构，根据这个也可以判断他们同在一个嵌套的大图中的相似部分。这个可以称作对等体。

在“所有一切都是图”的背景下，主要数据可以来自多个具有结构化文本的文档，文档之间可以有引用关系，这个引用最好还能识别出锚点，而不只是粗略地显示文档A引用，最好能段落中这个位置引用。

在“所有一切都是图”的背景下，主要任务可以是对等体的发现，链接预测，相似文档推荐，知识发现等

任务落到了一个最大的问题，图结构对等体的发现，问题描述为：在一个简单无向图中，给出一个子图，如何找到一个完全相等的另一个非重叠子图（要求，节点没有交集，边没有交集，不允许删除边，两图中对应节点的地位应该是相等的）

对于对等体发现问题，由于有可能节点就是一个子图，那么节点/子图的embedding会非常难以表述，能不能假设每个节点就是一个神经元，整个无向图是一个大的计算图，任何一时刻，对于任何一条边来说，都有可能在任何一个方向传递信息，待迭代次数足够多之后，图的结构应当趋于均衡。这个均衡指的是一方面每个节点/子图的参数得到学习，另外节点的embedding也得到学习，embedding怎么表示呢，就看这个节点有几个连接的边，把所有连接的边的信息concatenate起来就是它的embedding。

图数据结构量往往会很庞大，但只要能识别出对等体，就可以压缩图的信息，就像是有损压缩一样，保留大致结构，放弃细枝末节

</p>
</details>
