# Other tools for lab

## AutoOpt2Ant
將 Optimized 的 peptide 自行尋找旋轉角並對齊電極後產生 alacant 外掛可用的 configure file。

## auto_correlation
分析分子動力學模擬的軌跡檔，計算蛋白質分子表面所有水起始的偶極矩隨著時間所產生的變化。

## crosscorrelation_and_contact_map
利用信號學分析的 cross-correlation 原理，去計算蛋白質分子的每一個片段(residue)隨著時間的運動
並藉由瞭解各個片段彼此之間的關聯性後試圖找出蛋白質自由運動或是結構轉換時的發生順序與誘導關係
另外藉由將關聯分類為接觸型與非接觸型，去試圖確認目標蛋白的運動是否存在異位效應。

## location_classification
以 SVM 模型來學習辨識蛋白質的區域(domain)，並藉此將分類後續分子動力學模擬中所獲得該蛋白質的表面水分子所在位置。

## residence_time
分析大量指定分子的遲滯時間，並利用格點技巧將該遲滯時間建立成可視覺化的檔案

## surface_depth
利用迴轉半徑的計算方法，分析目標蛋白質表面每個區域的孔洞深度，並將以格點技巧建立成可視覺化的檔案

## surface_dipole
分析目標分子的表面其各局部區域的偶極矩


### 下列論文發表使用上述工具進行分析與討論
Sheh-Yi Sheu, Yu-Cheng Liu and Dah-Yen Yang, Interfacial water effect on cooperativity and signal communication in Scapharca dimeric hemoglobin, Physical Chemistry Chemical Physics, 19, 7380-7389 (2017). (https://doi.org/10.1039/c7cp00280g)

Sheh-Yi Sheu, Yu-Cheng Liu, Jia-Kai Zhou, Edward W. Schlag, and Dah-Yen Yang, Surface Topography Effects of Globular Biomolecules on Hydration Water, The Journal of Physical Chemistry B, Just Accepted Manuscript (2019). (https://doi.org/10.1021/acs.jpcb.9b03734)
