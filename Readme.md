# ChatGPT workflow

研究AI可以用在哪些工作流程。

## 背景

### 趋势

- 需求阈值全面提高，不论是画还是文本
- 人类文字水平从AI水平起步（全语言）
- 本地专用小模型 + 远程大模型的API
- 太多人容易轻信模型了，这会带来新的信息安全问题，甚至可以说有可能有人类认知危机

### 要做什么？

- 积累高质量数据与模型，不限语言
- 掌握各类验证的方法，最好做到交叉验证
- 会一点点训练
- 会面向api、数据库、模型 编程
- 日常练习，尤其是自然语言，特别是英语

## 可能做

- 低保真原型
- 三审三校中的“一校”
- 各国资料翻译
- “反人类语言”的编写与阅读
  - 正则表达式
  - 命令行脚本，ps1、bat、sh等
  - 协助阅读网络报文、api规范、数据传输规范等
  - 混淆或编译后的代码，机械码
  - 规定等文本
- 客服
- 小秘书

## 例子

### 例子使用的导出工具

- [gantrol/Bing-Chat-Saver: Save Bing chat with PNG，JPG、JSON and Markdown (github.com)](https://github.com/gantrol/Bing-Chat-Saver)
- [gantrol/ChatGPT-exporter: A Chrome extension for downloading your ChatGPT history to PNG, PDF or a sharable link (github.com)](https://github.com/gantrol/ChatGPT-exporter)

### 用一句话需求来写作

[叶慈风格的诗.md](./writing/examples/chatgpt/%E5%8F%B6%E6%85%88%E9%A3%8E%E6%A0%BC%E7%9A%84%E8%AF%97.md)

[李四藏头古诗.md](./writing/examples/chatgpt/%E6%9D%8E%E5%9B%9B%E8%97%8F%E5%A4%B4%E5%8F%A4%E8%AF%97.md)

[模仿《道德经》的方式写：不要加班.md](./writing/examples/chatgpt/%E6%A8%A1%E4%BB%BF%E3%80%8A%E9%81%93%E5%BE%B7%E7%BB%8F%E3%80%8B%E7%9A%84%E6%96%B9%E5%BC%8F%E5%86%99%EF%BC%9A%E4%B8%8D%E8%A6%81%E5%8A%A0%E7%8F%AD.md)

[相声《怪治病》.md](./writing/examples/chatgpt/%E7%9B%B8%E5%A3%B0%E3%80%8A%E6%80%AA%E6%B2%BB%E7%97%85%E3%80%8B.md)

[记叙文.md](./writing/examples/chatgpt/%E8%AE%B0%E5%8F%99%E6%96%87.md)

[起诉状.md](./writing/examples/chatgpt/%E8%B5%B7%E8%AF%89%E7%8A%B6.md)

### 编辑

> 上面这些链接，就是必应处理的：[必应处理文本.md](edit/examples/bing/必应处理文本.md)

### 迭代式写作·议论文

> 《[不完美出发](writing/examples/bing/不完美出发3-人为改写.md)》这篇文章我想写一个多月了，直到今天早上，还只有“标题：不完美出发”，以及“正文：月圆之后，便是月缺”。不得已，跟新必应讨论一下怎么写吧。完整经过放到github。中途还干了不少别的事情。

所有过程文件放[一个目录](writing/examples/bing)，大体上是这么个流程：

1. 人说明主旨、标题，让机器列大纲；
2. 机器的大纲基本是引言、正文、结论三部分，让机器逐部分写作；
3. 由于必应八轮对话的限制，以上至少占四轮，剩下四轮仅揪出错误较大的部分，或让补充论据素材；
4. 人写一份，如果卡文，回到步骤1，并加上已写的文章。


## 工作流分析

### 写作

#### 积累阶段

- 素材积累
  - 高质量数据仓库
  - 日常信息
- 灵感积累
  - idea池
- 市场调查（该做什么？）
- 日常练习（能做什么？）

#### 起草阶段

- 大纲
- 填充文本

#### 发布阶段

- 校对
  - 自己写完后校对很难出成果，一般要等半天后
  - 可以直接给openai改
- 审核
- 渠道
- 反馈

### 编程

#### 项目之前

- 调查
- 积累
- 灵感
- 练习

#### 具体需求

- 根据需求设计数据；
- 选择校验方式，可以是单元测试，也可以是手工。这是给自己反馈的途径，免得埋头写了一大堆，出错就不知道哪错；
- TODO: 细分不同类型，再分析；



