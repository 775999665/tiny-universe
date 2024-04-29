# Tiny-Universe

大模型是当下深度学习领域的热点，但现有的大部分大模型教程只在与教给大家如何调用api完成大模型的应用，而很少有人能够从原理层面讲清楚模型结构、RAG、Agent以及Eval。所以本仓库会提供全部手写，不调用api的形式，完成大模型的RAG、Agent、Eval应用。

## 项目受众

## 项目结构

### **TinyRAG**

LLM会产生误导性的 “幻觉”，依赖的信息可能过时，处理特定知识时效率不高，缺乏专业领域的深度洞察，同时在推理能力上也有所欠缺。

正是在这样的背景下，检索增强生成技术（Retrieval-Augmented Generation，RAG）应时而生，成为 AI 时代的一大趋势。

RAG 通过在语言模型生成答案之前，先从广泛的文档数据库中检索相关信息，然后利用这些信息来引导生成过程，极大地提升了内容的准确性和相关性。RAG 有效地缓解了幻觉问题，提高了知识更新的速度，并增强了内容生成的可追溯性，使得大型语言模型在实际应用中变得更加实用和可信。

***鉴于其他RAG项目都是提供完整的一套服务，虽然可以用的很好，当我们在用的时候不会太关注RAG的底层原理，所以本项目提供给大家一个从零开始的RAG项目，让大家可以更好的理解RAG的原理。***

### **TinyAgent**

在 ChatGPT 横空出世，夺走 Bert 的桂冠之后，大模型愈发的火热，国内各种模型层出不穷，史称“百模大战”。大模型的能力是毋庸置疑的，但大模型在一些实时的问题上，或是某些专有领域的问题上，可能会显得有些力不从心。因此，我们需要一些工具来为大模型赋能，给大模型一个抓手，让大模型和现实世界发生的事情对齐颗粒度，这样我们就获得了一个更好的用的大模型。

***这里基于 React 的方式，我们手动制作了一个最小的 Agent 结构（其实更多的是调用工具），暑假的时候会尝试将 React 结构修改为 SOP 结构，欢迎大家一起加入进来啊~！一步一步手写`Agent`，可以让我们对`Agent`的构成和运作更加的了解！！！***

## 核心贡献者

- xxx
- xxx
- xxx

## LICENSE

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="知识共享许可协议" style="border-width:0" src="https://img.shields.io/badge/license-CC%20BY--NC--SA%204.0-lightgrey" /></a><br />本作品采用<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">知识共享署名-非商业性使用-相同方式共享 4.0 国际许可协议</a>进行许可。

*注：默认使用CC 4.0协议，也可根据自身项目情况选用其他协议*
