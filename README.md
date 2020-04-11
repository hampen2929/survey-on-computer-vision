はんぺんの関心が高い論文まとめで更新は気が向いたとき

内容が増えてきたらタスクごとにページを切りましょう

- 以下のフォーマットで記述

```
# タスク名

## 論文名

### 概要

### 所感

### 参考
```

# Classification

## EfficientNet: Rethinking Model Scaling for Convolutional Neural Networks

### 概要

![image](https://user-images.githubusercontent.com/34574033/79056248-58311280-7c8f-11ea-94d9-9db145006b6f.png)

![image](https://user-images.githubusercontent.com/34574033/79056252-5d8e5d00-7c8f-11ea-975c-91fa9d13c064.png)


今までは単純に深くする、幅を広くする、入力画像の解像度を高くするというアプローチでモデルの精度をあげていましたが、それだとモデルのパラメータ増加に対して精度の向上に限界がきてしまうので、幅・深さ・解像度の比率を調整してネットワークを構築したらいいんじゃねという発想

実際に構築されたEfficientNetsは従来のモデルの同程度な精度の物に対して、大幅にパラメータを削減することに成功

### 所感

精度だけでなく推論速度も気になって時期に出てきた論文で、非常に関心が高いので読んだ。

大学院でやっていたダイヤモンドCVDの条件だしで圧力、温度、ガスの流量 etc を複合的に考えてた時期を思い出した(白目)

### 参考

https://arxiv.org/abs/1905.11946

https://github.com/tensorflow/tpu/tree/master/models/official/efficientnet

https://hampen2929.hatenablog.com/entry/2019/07/06/024347


# Detection

## Objects as Points(CenterNet)

### 概要



### 所感



### 参考




https://arxiv.org/abs/1904.07850

https://github.com/xingyizhou/CenterNet

# Tracking

## Tracking Objects as Points(CenterTrack)

### 概要

### 所感

### 参考

https://github.com/xingyizhou/CenterTrack

# Pose estimation

## Single-Shot Multi-Person 3D Pose Estimation From Monocular RGB

### 概要

![image](https://user-images.githubusercontent.com/34574033/79056389-08534b00-7c91-11ea-9c09-6cada8b12b07.png)

単眼のRGBカメラで撮った画像からシングルショットで3次元姿勢推定する手法

### 所感

OpenVINO 2020 R1から公式実装？に加わったlightweight-human-pose-estimation-3dで参考にされていて気になった

### 参考

https://arxiv.org/pdf/1712.03453.pdf

https://github.com/Daniil-Osokin/lightweight-human-pose-estimation-3d-demo.pytorch

## 3D human pose estimation in video with temporal convolutions and semi-supervised training

### 参考

https://github.com/facebookresearch/VideoPose3D

# Action recognition

# Reidentification

## Fast and Accurate Person Re-Identification with RMNet

### 概要

![Screenshot from 2020-04-12 07-51-29](https://user-images.githubusercontent.com/34574033/79056548-8fed8980-7c92-11ea-827c-9c57c2aaee30.png)

![image](https://user-images.githubusercontent.com/34574033/79056560-b7445680-7c92-11ea-9a5a-f31407bbe9bb.png)

精度と実行速度を両立することを目指したPerson-reidentificationの手法

### 所感

Intelの人の論文でOpenVINOの公式実装に使われている手法で気になった。

実行環境や使用したフレームワークまでちゃんと書いた上で精度と実行速度に対して言及してくれてるので好感がもてる。

### 参考

https://arxiv.org/abs/1812.02465

# Image generation

# 3D model generation

