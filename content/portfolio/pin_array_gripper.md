+++
image = "fig/gripping_concave.png"
showonlyimage = true
date = "2016-11-05T19:44:32+05:30"
title = "Pin-Array Gripper"
draft = false
weight = 2
+++

Mechanism for gripping and shape recognition of convex and concave terrain profiles
<!--more-->

東北大学の修士課程で取り組んだ研究テーマの1つです．

月面や惑星表面を探査するうえで，従来の車輪では行けないような場所，つまり崖や洞窟のような環境を踏破するためには，どんな形のロボットならうまく探査できるかなっていう研究でした．

活動域が未知の非構造化環境であることから，ロボットと環境とのインタラクションをうまいこと利用するために，いろいろと試行錯誤した結果，このような**凹凸両方の形状の岩石を全く同じ動きで把持できる機構**を考案しました．

![pin_array_gripper](/fig/pin_array_gripper.png)
![gripping](/fig/gripping.png)

さらに，把持時にピンの沈んだ深さを計測すれば，地表面の形状もわかるのでは？と考え，感圧センサを使った地形計測システムも実装しました．

![shape_recognition](/fig/shape_recognition.png)

これらの成果をまとめて，IEEE ROBIO 2022で発表しました．
（T. Kato, et al., “**A Pin-Array Structure for Gripping and Shape Recognition of Convex and Concave Terrain Profiles**,” In *Proc. 2022 IEEE Int. Conf. on Robotics and Biomimetics (ROBIO)*, pp. 1365--1370, 2022. ）
{{< youtube dWo28Nl5jgE >}}
