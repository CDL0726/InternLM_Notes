# **书生·浦语大模型实战营 22班**
#### Dennis 笔记    Updated: Jan 15, 2024
## Pre-reading 
### [文档](https://github.com/InternLM/tutorial/blob/main/helloworld/)
### [基础课程](https://datawhalechina.github.io/llm-universe/#)  
### [中文GPTs网站](https://www.glbai.com/ )  
### [InterLM](https://github.com/InternLM/tutorial/)
### [To大项目同学](https://openxlab.org.cn/docs/apps/Gradio%E5%BA%94%E7%94%A8.html)  
## Findings  
### 1.对话即平台（conversation as a platform） 陆奇在微软期间2016年  智能体（Agent）类型应用   
#### [支持对话作为统一入口的能力](https://datawhalechina.github.io/llm-universe/#/C1/2.%20%E2%BC%A4%E6%A8%A1%E5%9E%8B%E7%9A%84%E8%83%BD%E2%BC%92%E5%92%8C%E7%89%B9%E7%82%B9?id=_13-%E6%94%AF%E6%8C%81%E5%AF%B9%E8%AF%9D%E4%BD%9C%E4%B8%BA%E7%BB%9F%E4%B8%80%E5%85%A5%E5%8F%A3%E7%9A%84%E8%83%BD%E5%8A%9B)  
### 2.LangChain 作为一个大语言模型开发框架  
### 3.Prompt 替代给 LLM 的输入，使用 Completion 替代 LLM 的输出  
### **4.大模型开发的整体流程：**  
#### 4.1 确定目标  
#### 4.2 设计功能  
#### 4.3 搭建整体架构  
#### 4.4 搭建数据库  
#### 4.5 Prompt Engineering  
#### 4.6 验证迭代  
#### 4.7 前后端搭建  
#### 4.8 体验优化  
### 5.使用 Gradio 和 Streamlit 搭建前端界面  
### 6.准则二多维评估大模型
### 7.Gradio 来搭建前端界面  
#### [Gradio 的介绍与前端界面的搭建](https://datawhalechina.github.io/llm-universe/#/C7/2.%20Gradio%20%E7%9A%84%E4%BB%8B%E7%BB%8D%E4%B8%8E%E5%89%8D%E7%AB%AF%E7%95%8C%E9%9D%A2%E7%9A%84%E6%90%AD%E5%BB%BA?id=%E7%AC%AC%E4%BA%8C%E7%AB%A0%E3%80%81gradio-%E7%9A%84%E4%BB%8B%E7%BB%8D%E4%B8%8E%E5%89%8D%E7%AB%AF%E7%95%8C%E9%9D%A2%E7%9A%84%E6%90%AD%E5%BB%BA-%F0%9F%92%AC)
---
## **Online Course**  
# **第1节 《书生·浦语大模型全链路开源体系》**
#### Jan 9, 2024  陈恺
[书生·浦语大模型全链路开源体系](https://www.bilibili.com/video/BV1Rc411b7ns)  
## **1. 从专用模型到通用大模型**  
## **2. 从模型到应用的路线图**   
## **3. 书生·浦语大模型全链路开源体系**   
### 3.1 数据  书生·万卷1.0  OpenDataLab   
### 3.2 预训练 InterLM-Train   
### 3.3 模型微调 X Tuner   
### 3.4 模型评测  OpenCompass   
### 3.5 模型部署  LMDeploy   
### 3.6 智能体 Lagent  AgentLengo   
## **Take away**  
### 1.从专用模型到通用大模型
### 2.大模型落地应用的路径图
### 3.书生·浦语 全链条开源开放体系：数据 预训练 微调 部署 评测 智能体
---
## **Online Course**
# **第2节 轻松玩转书生·浦语大模型趣味Demo**
#### Jan 10, 2024  宋志学
[轻松玩转书生·浦语大模型趣味Demo](https://www.bilibili.com/video/BV1Ci4y1z72H/?vd_source=427d5b3bd6552cd66c00e381e2aae338)  
## 1.大模型及 InternLM 模型简介  
###    1.1 什么是大模型  大模型通常指的是机器学习或人工智能领域中参数数量巨大、拥有庞大计算能力和参数规模的模型。特点是拥有数十亿至数千亿参数 惊人性能。
###    1.2 InternLM 是个开源的轻量级训练框架 InterLM-7B  InternLM-20B
###    1.3 Lagent 是个轻量级 开源的基于大模型的智能体 Agent 框架  
## 2.internlm-chat-7b-智能对话-demo  
###     2.1 环境准备  
###     2.2 模型下载  
###     2.3 代码准备  
###     2.4 终端运行  
###     2.5 web demo 运行
## 3 Lagent 智能体工具调用 Demo  
###     3.1 环境准备
###     3.2 模型下载
###     3.3 Lagent 安装
###     3.4 修改代码
###     3.5 Demo 运行
## 4. 浦语·灵笔图文理解创作 Demo
###     4.1 环境准备  
###     4.2 模型下载  
###     4.3 代码准备  
###     4.4 Demo 运行
## 5. 通用环境配置  
###     5.1 pip、conda 换源  
###     5.1.1 pip 换源  
###     5.1.2 conda 换源  
###     5.2 配置本地端口   
###     5.3 模型下载   
####        5.3.1 Hugging Face  
####        5.3.2 ModelScope   
####        5.3.3 OpenXLab
---
## 6. 课后作业  
###   6.1 基础作业
####       6.1.1 使用 InternLM-Chat-7B 模型生成 300 字的小故事（需截图）。
####       6.1.2 熟悉 hugging face 下载功能，使用 huggingface_hub python 包，下载 InternLM-20B 的 config.json 文件到本地（需截图下载过程）。
###   6.2 进阶作业（可选做）
####       6.2.1 完成浦语·灵笔的图文理解及创作部署（需截图）
####       6.2.2 完成 Lagent 工具调用 Demo 创作部署（需截图）
###   6.3 整体实训营项目：即日开始可以在班级群中随机组队完成一个大作业项目
---
## **Online Course**
# **第3节 基于 InternLM 和 LangChain 搭建你的知识库**
#### 2024.1.15 
#### [文档](https://github.com/InternLM/tutorial/tree/main/langchain)  
## 1. LLM的局限性
#### 1.1 知识时效性受限
#### 1.2 专业能力有限 如何打造垂域大模理
#### 1.3 定制化成本高 如何打造人人专属的LLM应用
## 2. RAG vs Finetune
### 2.1 RAG 检索增强生成
## 3.构建向量数据库
#### 3.1 加载源文件   文档分块   文档向量化
## 4. 搭建知识库助手
#### 4.1 将InterLM接入langchain
#### 4.2 构建检索问答链
## 5.Web Demo 部署
