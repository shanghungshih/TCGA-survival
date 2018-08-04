# survival

### [C-index](http://ttdoc.cn/article/652.jhtml)
- concordance index 用于生存资料
- C-index在0.5-1之间。0.5为完全不一致，说明该模型没有预测作用；1为完全一致；在0.50-0.70为较低准确度，在0.71-0.90之间为中等准确度，高于0.90则为高准确度
- C = K / M (一致的对子数/有用的对子数)


### [Kaplan-Meier曲線](http://biostatdept.cmu.edu.tw/doc/epaper_a/paper/teaching_corner_062_1.pdf)
- 每次發生event（死亡 or 退出計畫），即計算一次
- 目的：可忽略前一時段退出計畫的人
- 前提假設：每一階段不會有大量人退出

### [Cox model](http://biostatdept.cmu.edu.tw/doc/epaper_a/paper/teaching_corner_064.pdf)
- 線性模型
- B * X (係數 x features)
