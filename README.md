# **书生·浦语大模型实战营 22班**
#### Dennis 笔记    Updated: Jan 26, 2024
---
## Pre-reading 
### [InterLM 课程文档与视频](https://github.com/InternLM/tutorial)
### [基础课程](https://datawhalechina.github.io/llm-universe/#)  
### [中文GPTs网站](https://www.glbai.com/ )  
### [To大项目同学](https://openxlab.org.cn/docs/apps/Gradio%E5%BA%94%E7%94%A8.html)  
---
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
#### Jan 15 2024 
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
### 4.1 将InterLM接入langchain
#### 4.2 构建检索问答链
#####    4.2.1 检索方面基于语义进行分割，何证每一个chunk的语义完整
## 5.Web Demo 部署
#### 5.1 支持简易Web部署框架：Gradio, Streamlit

---
## **online Courese**  
# **第4节 XTuner 大模型单卡低成本微调实战**
#### Jan 18 2024    汪周谦 XTuner 社区贡献者
[课件文档](https://github.com/InternLM/tutorial/blob/main/xtuner/README.md)

## Finetune简介
#### 指令跟随微调  
#####   三个角色：system user assistant
#### 增量预训练微调

## XTuner 介绍
#### 0基础的非专业的微调模型工具
#### XTuner微调原理：LoRA & QLoRA
#### 多数据样本拼接(Pack Dataset)  自定义数据集格式Json 或 Jsonl  

## 8G显卡玩转LLM
### 二种优化技巧
####    Flashion Attention, Flash Attention 将 Attention 计算并行化避免了计算过程中 Attention Score NxN的显存占用 (训练过程中的 N 都比较大)
####    DeepSpeed ZeRO, ZeRO 优化，通过将训练过程中的参数、梯度和优化器状态切片保存，能够在多 GPU 训练时显著节省显存
除了将训练中间状态切片外，DeepSpeed 训练时使用 FP16 的权重，相较于 Pytorch 的AMP 训练在单 GPU上也能大幅节省显存   

## 实战
#### Windows PowerShell 链接SSH
   - Windnows 找开 Windows PowerShell 
   - ssh-keygen -t rsa 输入 回车，直接出现 SHA256，说明公钥文件已经创建好了
   - cat ~\.ssh\id_rsa.pub 公钥文件
   - ssh -CNg -L 7860:127.0.0.1:7860 root@ssh.intern-ai.org.cn -p <你的ssh端口号>
#### 常用命令
   - Ctrl + C 中断微调
   - ls 查看文件 （openassistant-guanace, work_dirs）
   - rm -rf work_dirs  删除文件 work_dirs
   - apt update -y 对apt语言进行更新，在root文件下
   
#### 利用Tmux持续微调（关电脑情况下, 课件视频0:43:00 ~ 0：46:45/1:34:01）
   - Ctrl + C 中断微调
   - ls 查看文件 （openassistant-guanace, work_dirs）
   - rm -rf work_dirs  删除文件 work_dirs
   - apt update -y 对apt语言进行更新，在root文件下
   - apt install tmux -y 
   - tmux new -s finetune  创建tmux session 
   - 退出Finetune命令： Ctrl+B,松开后再 按 D
   - 回到Finetune命令： tmux attach -t finetune

#### XTuner下载时出错的解决方案：
###### 拉取 0.1.9 的版本源码
         - git clone -b v0.1.9  https://github.com/InternLM/xtuner
###### 无法访问github的用户请从 gitee 拉取:
         - git clone -b v0.1.9 https://gitee.com/Internlm/xtuner

[Serper API](https://serper.dev/api-key)

---
## **online Courese**  
# **第5节 LMDeploy 大模型量化部署实践**
#### Jan 24 2024    长琴 ｜ HuggingLLM 开源项目负责人

[课程视频](https://www.bilibili.com/video/BV1iW4y1A77P/?vd_source=427d5b3bd6552cd66c00e381e2aae338)  

[课程文档](https://github.com/InternLM/tutorial/blob/main/lmdeploy/lmdeploy.md)

# LMDeploy 的量化和部署

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [1 环境配置](#1-%E7%8E%AF%E5%A2%83%E9%85%8D%E7%BD%AE)
- [2 服务部署](#2-%E6%9C%8D%E5%8A%A1%E9%83%A8%E7%BD%B2)
  - [2.1 模型转换](#21-%E6%A8%A1%E5%9E%8B%E8%BD%AC%E6%8D%A2)
    - [2.1.1 在线转换](#211-%E5%9C%A8%E7%BA%BF%E8%BD%AC%E6%8D%A2)
    - [2.1.2 离线转换](#212-%E7%A6%BB%E7%BA%BF%E8%BD%AC%E6%8D%A2)
  - [2.2  TurboMind 推理+命令行本地对话](#22--turbomind-%E6%8E%A8%E7%90%86%E5%91%BD%E4%BB%A4%E8%A1%8C%E6%9C%AC%E5%9C%B0%E5%AF%B9%E8%AF%9D)
  - [2.3 TurboMind推理+API服务](#23-turbomind%E6%8E%A8%E7%90%86api%E6%9C%8D%E5%8A%A1)
  - [2.4 网页 Demo 演示](#24-%E7%BD%91%E9%A1%B5-demo-%E6%BC%94%E7%A4%BA)
    - [2.4.1 TurboMind 服务作为后端](#241-turbomind-%E6%9C%8D%E5%8A%A1%E4%BD%9C%E4%B8%BA%E5%90%8E%E7%AB%AF)
    - [2.4.2 TurboMind 推理作为后端](#242-turbomind-%E6%8E%A8%E7%90%86%E4%BD%9C%E4%B8%BA%E5%90%8E%E7%AB%AF)
  - [2.5 TurboMind 推理 + Python 代码集成](#25-turbomind-%E6%8E%A8%E7%90%86--python-%E4%BB%A3%E7%A0%81%E9%9B%86%E6%88%90)
  - [2.6 这么多，头秃，有没有最佳实践](#26-%E8%BF%99%E4%B9%88%E5%A4%9A%E5%A4%B4%E7%A7%83%E6%9C%89%E6%B2%A1%E6%9C%89%E6%9C%80%E4%BD%B3%E5%AE%9E%E8%B7%B5)
    - [2.6.1 方案实践](#261-%E6%96%B9%E6%A1%88%E5%AE%9E%E8%B7%B5)
    - [2.6.2 模型配置实践](#262-%E6%A8%A1%E5%9E%8B%E9%85%8D%E7%BD%AE%E5%AE%9E%E8%B7%B5)
- [3 模型量化](#3-%E6%A8%A1%E5%9E%8B%E9%87%8F%E5%8C%96)
  - [3.1 KV Cache 量化](#31-kv-cache-%E9%87%8F%E5%8C%96)
    - [3.1.1 量化步骤](#311-%E9%87%8F%E5%8C%96%E6%AD%A5%E9%AA%A4)
    - [3.1.2 量化效果](#312-%E9%87%8F%E5%8C%96%E6%95%88%E6%9E%9C)
  - [3.2 W4A16 量化](#32-w4a16-%E9%87%8F%E5%8C%96)
    - [3.2.1 量化步骤](#321-%E9%87%8F%E5%8C%96%E6%AD%A5%E9%AA%A4)
    - [3.2.2 量化效果](#322-%E9%87%8F%E5%8C%96%E6%95%88%E6%9E%9C)
  - [3.3 最佳实践](#33-%E6%9C%80%E4%BD%B3%E5%AE%9E%E8%B7%B5)
- [参考资料](#%E5%8F%82%E8%80%83%E8%B5%84%E6%96%99)
- [附录1：TritonServer 作为推理引擎](#%E9%99%84%E5%BD%951tritonserver-%E4%BD%9C%E4%B8%BA%E6%8E%A8%E7%90%86%E5%BC%95%E6%93%8E)
  - [TritonServer环境配置](#tritonserver%E7%8E%AF%E5%A2%83%E9%85%8D%E7%BD%AE)
  - [TritonServer推理+API服务](#tritonserver%E6%8E%A8%E7%90%86api%E6%9C%8D%E5%8A%A1)
  - [TritonServer 服务作为后端](#tritonserver-%E6%9C%8D%E5%8A%A1%E4%BD%9C%E4%B8%BA%E5%90%8E%E7%AB%AF)
 
## 安装、部署、量化 实践操作Tips
#### Code server 操作tips
    - exit() 程序退出命令
    - cd ~ 回到根目录

#### Conda 环境创建
    - 打开开发机，进入Code Serve界面
    - bash 
    - vgpu-smi 查看显卡资源使用情况
    - watch vgpu-smi 观察 GPU 资源的使用情况
    - /root/share/install_conda_env_internlm_base.sh lmdeploy 安装新的软件包
    - conda env list 本地查看环境
    - conda activate lmdeploy 激活conda环境

#### 服务部署
  - 模型转换
      - 在线转换, lmdeploy 支持直接读取 Huggingface 模型权重,
          - 直接启动本地的 Huggingface 模型
          - lmdeploy chat turbomind /share/temp/model_repos/internlm-chat-7b/  --model-name internlm-chat-7b
  -  离线转换
       - 将模型转为 lmdeploy TurboMind 的格式 
          - 使用官方提供的模型文件，就在用户根目录执行
          - lmdeploy convert internlm-chat-7b  /root/share/temp/model_repos/internlm-chat-7b/ 

  - TurboMind 推理+命令行本地对话
          - lmdeploy chat turbomind ./workspace 

  - TurboMind推理+API服务  
         - ”模型推理/服务“目前提供了 Turbomind 和 TritonServer 两种服务化方式。此时，Server 是 TurboMind 或 TritonServer，API Server 可以提供对外的 API 服务。  
           - 通过下面命令启动服务
            - lmdeploy serve api_server ./workspace \
	                --server_name 0.0.0.0 \
	                --server_port 23333 \
	                --instance_num 64 \
	                --tp 1 
             - 新开一个窗口，打开 vscode 的 Terminal，执行下面的命令
                  - lmdeploy serve api_client http://localhost:23333 

   - 网页 Demo 演示  
         - TurboMind 服务作为后端


 ## **Online Course**  
# **第6节 《OpenCompass大模型评测》**
#### Jan 26, 2024  曹茂松|OpenCompass核心开发者

[课程视频](https://www.bilibili.com/video/BV1Gg4y1U7uc/?vd_source=427d5b3bd6552cd66c00e381e2aae338) 
[课程文档](https://github.com/InternLM/tutorial/blob/main/opencompass/opencompass_tutorial.md) 

## 评测对象

本算法库的主要评测对象为语言大模型与多模态大模型。我们以语言大模型为例介绍评测的具体模型类型。

- **基座模型**：一般是经过海量的文本数据以自监督学习的方式进行训练获得的模型（如OpenAI的GPT-3，Meta的LLaMA），往往具有强大的文字续写能力。

- **对话模型**：一般是在的基座模型的基础上，经过指令微调或人类偏好对齐获得的模型（如OpenAI的ChatGPT、上海人工智能实验室的书生·浦语），能理解人类指令，具有较强的对话能力。

## 工具架构

- 模型层：大模型评测所涉及的主要模型种类，OpenCompass以基座模型和对话模型作为重点评测对象。
- 能力层：OpenCompass从本方案从通用能力和特色能力两个方面来进行评测维度设计。在模型通用能力方面，从语言、知识、理解、推理、安全等多个能力维度进行评测。在特色能力方面，从长文本、代码、工具、知识增强等维度进行评测。
- 方法层：OpenCompass采用客观评测与主观评测两种评测方式。客观评测能便捷地评估模型在具有确定答案（如选择，填空，封闭式问答等）的任务上的能力，主观评测能评估用户对模型回复的真实满意度，OpenCompass采用基于模型辅助的主观评测和基于人类反馈的主观评测两种方式。
- 工具层：OpenCompass提供丰富的功能支持自动化地开展大语言模型的高效评测。包括分布式评测技术，提示词工程，对接评测数据库，评测榜单发布，评测报告生成等诸多功能。

## 安装

### 面向GPU的环境安装
```bash

conda create --name opencompass --clone=/root/share/conda_envs/internlm-base
source activate opencompass
git clone https://github.com/open-compass/opencompass
cd opencompass
pip install -e .
```

有部分第三方功能,如代码能力基准测试 Humaneval 以及 Llama格式的模型评测,可能需要额外步骤才能正常运行，如需评测，详细步骤请参考[安装指南](https://opencompass.readthedocs.io/zh_CN/latest/get_started/installation.html)。

### 数据准备

```bash
# 解压评测数据集到 data/ 处
cp /share/temp/datasets/OpenCompassData-core-20231110.zip /root/opencompass/
unzip OpenCompassData-core-20231110.zip

             - API Server 的启动和上一节一样，这里直接启动作为前端的 Gradio  
             - lmdeploy serve gradio http://0.0.0.0:23333 \
	           --server_name 0.0.0.0 \
	           --server_port 6006 \
	           --restful_api True
