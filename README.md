# 映画の需要予測

- 主に映画の売り上げ予測を回帰を用いて行った
- 具体的な手法はシンプルな重回帰分析とLightGBMの2種類
## ソースコードの場所
1. LightGBMでの分析手法
   - Sales/classification.ipynb
2. 重回帰分析での解析手法
   - Sales/regression.ipynb

### 特徴量一覧
1. 予算
2. 映画の売り上げ
3. 監督名
4. 制作会社名
5. 上映時間
6. 上映時期
7. 対応言語数
8. ジャンル(9種類)
   - アクション
   - アドベンチャー
   - ファンタジー
   - SF
   - 犯罪
   - ホラー
   - ファミリー
   - コメディ
   - ロマンス
   - 戦争
   - ミュージカル
   - ドキュメント

### 目的変数
- 映画の売上

