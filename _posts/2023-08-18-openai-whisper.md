---
title: "Introducing Whisper"
---
## Whisper
* 自动语音识别系统(多种语言)

## The Whisper Architecture
* end to end approach
* * 直接接受原始声音波形作为输入。
* * 模型被训练来自动从这些波形中学习有意义的表示,并直接输出文本。
* encoder-decoder Transformer
* log-Mel spectrogram
* * 是声音处理中的一个常用特征表示
* * 它通过模仿人类的听觉感知特性来提供一个对于声音分析和自动音频识别更为有利的表示。
    在实践中，Log-Mel spectrogram 经常被用作许多音频和语音处理任务的输入特征，
    例如语音识别和音乐分类。
* 音源被分割成三十秒的音段，准换成Log-Mel spectrogram再传递给编译器。
  

## LibriSpeech

## CLIP