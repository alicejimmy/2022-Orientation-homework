## KNN 在分類鳶尾花屬種時，使用不同n_neighbors的測試結果
經過多次使用不同 random_state 的測試結果發現，此 dataset 使用 KNN 演算法時  
會在 k = 11(n_neighbors = 11)的時候最穩定，大多數情形都能在 k = 11 產生最佳的分類結果
