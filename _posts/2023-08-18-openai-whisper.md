---
title: "OpenAI Whisper: Deploying Voice-to-Text Inference for Key Information Extraction"
---
## 介绍
OpenAI Whisper Speech Refiner是一款致力于促进办公效率的产品。
在当前数据网络发展迅速的时代，互联网和云处理以与我们的工作息息相关。
在会议时采用手写方式记录笔记，可能会遗漏重点或者笔记冗杂不够直观。
而这款产品能有效地解决手写笔记所存在的问题，同时提高用户的办公效率。
本产品可通过语音转换为文本，并将所生成文本内容进行错别字纠正和语法纠正，
最后通过AI算法将文本重要内容提取并总结。合理地运用数据科学以及前沿科技，
给予用户良好的办公体验是我们的终旨。如您想更仔细了解本产品及使用方式请阅读下文。
## 一：确定AI的类型和目标
* AI类型：语音处理
* AI目标：
  * 将语音转换为文字
  * 在文字中提取重点
## 二：收集和准备数据
* 当收集到数据后，需要进行清理和准备
  * 数据清理：删除重复数据，填充缺失值
  * 数据转换：将数据转换为模式可处理的格式
  * 数据划分：划分为
    * 数据集（集合）
    * 测试集（评估模型性能）

## 三：引用OpenAI预训练模型
* AI模型：OpenAI/Whisper - GitHub - Python

## 四：训练AI模型

## 五：评估和优化模型

## 六：使用AI模型进行预测

## 如何在Pycharm里用Python调用Whisper模组
* 在GitHub中Fork OpenAI/Whisper 到自己的仓库
  * https://github.com/openai/whisper
  * ![OpenAI Whisper](/assets/images/openai_whisper.png)
* 在GitHub Desktop中clone Whisper并使用Pycharm打开Whisper
  * ![Clone Whisper](/assets/images/clone_whisper.png)
* 下载python 3.8.10到本地
  * https://www.python.org/downloads/release/python-3810/
* 在pycharm中设置local interpreter为python 3.8.10
  * ![Interpreter_Setting](/assets/images/pycharm_interpreter_3810.png)
* 确保电脑已经安装Git
  * https://git-scm.com/downloads
  * 将Terminal路径调整到Git\bin所在位置
    * D:\git\bin
    * ![Terminal Setting](/assets/images/terminal_git_setting.png)
* 根据Whisper中的 Setup安装package
  * pip install -U openai-whisper
  * pip install git+https://github.com/openai/whisper.git
  * pip install --upgrade --no-deps --force-reinstall git+https://github.com/openai/whisper.git
  * 安装scoop ffmpeg https://scoop.sh/

