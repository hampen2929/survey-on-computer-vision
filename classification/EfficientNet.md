# EfficientNet: Rethinking Model Scaling for Convolutional Neural Networks

## 概要

![image](https://user-images.githubusercontent.com/34574033/79056248-58311280-7c8f-11ea-94d9-9db145006b6f.png)

![image](https://user-images.githubusercontent.com/34574033/79056252-5d8e5d00-7c8f-11ea-975c-91fa9d13c064.png)


今までは単純に深くする、幅を広くする、入力画像の解像度を高くするというアプローチでモデルの精度をあげていましたが、それだとモデルのパラメータ増加に対して精度の向上に限界がきてしまうので、幅・深さ・解像度の比率を調整してネットワークを構築したらいいんじゃねという発想

実際に構築されたEfficientNetsは従来のモデルの同程度な精度の物に対して、大幅にパラメータを削減することに成功

## 所感

精度だけでなく推論速度も気になって時期に出てきた論文で、非常に関心が高いので読んだ。

大学院でやっていたダイヤモンドCVDの条件だしで圧力、温度、ガスの流量 etc を複合的に考えてた時期を思い出した(白目)

## 参考

https://arxiv.org/abs/1905.11946

https://github.com/tensorflow/tpu/tree/master/models/official/efficientnet

https://hampen2929.hatenablog.com/entry/2019/07/06/024347
