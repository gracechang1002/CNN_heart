## 摘要
本研究收集心電圖數據進行特徵擷取，使用均勻實驗設計法結合卷積神經網路AlexNet結構，<br>
透過設計AlexNet結構神經網路的超參數，探討是否可達到與Matlab 2019版本之AlexNet神經<br>
網路的辨識結果相當或超越之可能性。<br>

本研究所使用心電圖數據有三種症狀，分別為正常竇率、心律不整、充血性心臟衰竭，訓練與<br>
測試資料分為固定及隨機抽取兩種模式，經由三種結構做訓練及測試，分別使用Matlab自行重<br>
製AlexNet結構之網路、使用U11均勻表設計超參數結合AlexNet結構之網路、使用U17均勻表設<br>
計超參數結合AlexNet結構之網路，經以上三種結構進行訓練及測試，找出最佳之結果與Matlab<br>
2019版本之AlexNet辨識結果做比較，探討是否有相當於Matlab 2019版本之AlexNet的辨識結果。<br>

經由實驗結果發現，使用U17均勻表設計超參數結合AlexNet之結構用於固定訓練及測試資料，<br>
辨識結果平均為93.13%，其結果高於使用Matlab 2019版本之AlexNet辨識結果，若使用隨機訓<br>
練及測試資料，使用Matlab 2019版本之AlexNet辨識結果為93.44%，其結果皆優於其他結構之<br>
網路，但誤差只有些微差距，如此研究，希望利用均勻實驗設計來設計出更多種不同組合或透<br>
過增加實驗因子，讓實驗有更多的變化性，也可以透過調整神經網路結構內的超參數找出與<br>
Matlab 2019版本之AlexNet之網路訓練結果相當或更優越的結果。<br>