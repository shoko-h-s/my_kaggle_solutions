# My Kaggle Solutions

Kaggleのコンペティション挑戦記録および実践的な機械学習パイプラインのまとめリポジトリです。

---

## 🏆 実績ハイライト

### 🏠 House Prices - Advanced Regression Techniques
住宅の販売価格を予測する回帰タスクに挑戦しました。

* **達成スコア (Global LB):** **0.11936** （誤差換算: 約22,429ドル / 約355万円）
* **主なアプローチ:**
  * ドメイン知識に基づく特徴量エンジニアリング（屋内/屋外の面積分離、品質×状態の独自指標、対数変換）
  * 徹底的なEDAによるノイズ（外れ値）の事前除外
  * **LightGBM と CatBoost の最適ブレンド（アンサンブル）**
* **成果物:** [Kaggle Notebookはこちら](https://www.kaggle.com/code/shokos64/0-11936-house-prices-lgbm-cat-japanese)
