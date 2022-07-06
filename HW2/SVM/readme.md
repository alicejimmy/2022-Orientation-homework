## SVM 在分類鳶尾花屬種時，使用不同kernel及C的測試結果
經過多次使用不同 random_state 的測試結果發現，此 dataset 使用 SVM 演算法時  
當 kernel = 'rbf'的時候最穩定，而kernel = 'poly'的時候通常分類結果會最差  
另外大多數情形都能在 C = 1.0 時能產生最佳的分類結果

