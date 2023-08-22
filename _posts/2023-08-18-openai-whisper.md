---
title: "Machine Learning Model Building Process"
---
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

## 三：设计和构建AI模型
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

