from cascade_TM_judge_color

采取tracking by detection策略，检测使用cascade分类器，追踪使用灰度直方图反向映射的相似度匹配算法。

cascade算法在灰度图上使用，robomaster比赛装甲板有红蓝两种颜色，需要judge_color，可选择在bgr或hsv空间进行judge。可视化部分包括save_board和
save_location，用于分析追踪失效和漏检帧。
