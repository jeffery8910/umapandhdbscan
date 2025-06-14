UMAP + HDBSCAN 互動視覺化工具
這是一個互動式的網頁應用程式，旨在幫助使用者直觀地理解兩種強大的機器學習演算法：UMAP (Uniform Manifold Approximation and Projection) 用於降維，以及 HDBSCAN (Hierarchical Density-Based Spatial Clustering of Applications with Noise) 用於分群。
透過即時調整參數並觀察結果變化，使用者可以深入探索這些演算法如何協同工作，將複雜、高維度的資料結構轉換為清晰、可解釋的群集。
✨ 主要功能
 * 多樣化資料集：提供三種經典的二維資料集（塊狀分佈、月亮形、同心圓），以測試演算法在不同資料結構下的表現。
 * 即時參數調校：
   * UMAP：可調整 n_neighbors（鄰居數量）和 min_dist（最小距離），以控制降維後局部與全域結構的
