# 流体解析

## 参考になりそうなセミナー
[樹脂流体解析スキルアップセミナー](https://www.terrabyte.co.jp/seminar/fluid_semi.htm)
申込み受付中：2024年8月27日（火） ※締切　2024年8月19日18時

プラスチック成形の分野では、樹脂流動解析が広く普及していますが解析結果を製品設計に活かすためには、解析ソフトの操作方法を覚えるだけでは不十分です。材料特性、数値計算手法、解析結果の意味を正しく理解する必要があります。

- 材料特性は、どの様に表現されているか？
- 樹脂の流動解析は、どの様に計算をしているか？
- 繊維配向による材料特性は、どの様に表現されているか？
- 実成形と解析結果を比較する際に注意すべきことは？

1. 樹脂の概要
   1. 樹脂の種類
   2. 樹脂の成形法

2. レオロジー特性
   1. レオロジーの基礎
   2. 粘弾性モデル
      1. 応力緩和とクリープ
      2. MaxwellモデルとVoigtモデル
      3. 一般化Maxwellモデル
      4. Die Swellへの適用例
   3. 粘度モデル
      1. 流体の特性と分類  
      2. 擬塑性流体用モデル
         1. 指数則モデル
         2. Crossモデル
         3. Modified Crosモデル
         4. Carreau-Yasudaモデル
         5. Herschel-Buklelyモデル
      3. 温度依存モデル
         1. アドレードの式*
         2. WLF式*
      4. その他のモデル
         1. ダイタラント流体
         2. ビンガム流体
         3. 拡張オストワルド流体
   4. 熱硬化性樹脂用モデル
      1. 物性値の変化と反応速度、粘度の取り扱い方
      2. Kamalの反応速度モデル
      3. Castro-Macosko粘度モデル
   5. 粘弾性体の積分型流動モデル
      1. 伸長流動とは
      2. K-BKZモデルによる一軸伸長粘度の計算
   6. フィラー配合系の取り扱い
      1. フィラー含有量と粘度の関係
      2. 繊維配向について
      3. 繊維配向後の計算モデル

3. Excelによる係数自動最適化実習
   1. Excelでの最適化ソルバーの種類と原理
   2. ソルバーアドイン手続き
   3. 最適化の手順
   4. 粘度の実測データでの係数の決定

4. 樹脂特性測定法
   1. 動的粘弾性測定装置
      1. 装置の概要
      2. 純弾性体と純粘性体の挙動
      3. 粘弾性体の挙動
      4. 樹脂の周波数依存特性
      5. 周波数依存特性から一般化Maxwellモデルへの変換
   2. せん断粘度の測定法と誤差の補正法
      1. 測定方法の比較
      2. キャピラリー押出粘度計と補正方法
      3. コーンプレート型回転粘度計
      4. パラレルプレート型回転粘度計と法制法
   3. 伸張粘度の測定法
   4. Excelによる実測データの誤差補正実習

5. 樹脂流動の計算
   1. 流体力学
   2. 非圧縮性流体の計算
   3. ナビエ・ストークス方程式とストークス方程式の比較
   4. 射出成形流動解析の基礎

6. 解析事例
   1. 樹脂成形専用成形解析ソフト
      1. 射出成型、押出成形、発泡成形ソフト
      2. ブロー成型ソフト
   2. 解析結果の応用技術
      1. 解析結果による成形品の品質評価
      2. 解析実施時の注意点
      3. 射出成形結果の応用技術
      4. ゴムの充填解析
      5. 熱硬化性樹脂のポッティング解析
      6. シートの樹脂発泡成形

---

## 計算力学 流体2級 目次
- 技術レベル
  - 単相の非圧縮性流/圧縮性流/層流/乱流の範囲において正しく解析もんだを設定することができる
  - 解析内容を理解しており、解析結果の信頼性を検証することができる
  - CAEソフトウェアを用いて適切な解析機能を選択しながら、基本的な熱流体問題を解くことができる

### 計算力学のための数学の基礎
- 微分方程式
- 初期値問題
- 境界値問題
- テイラー展開
- ベクトル・テンソル解析
- 座標変換
- ガウスの定理

### 流体力学の基礎
- 次元解析、無次元数
- ベルヌーイの定理
- Navier-Stokes 方程式

### 熱力学・伝熱学の基礎
- 熱量・仕事
- 理想気体・状態方程式
- 熱力学の第1法則、第2法則、第3法則
- 内部エネルギー
- エントロピー

### 数値計算法
- 有限差分法、有限体積法、有限要素法
- スペクトル法
- 時間積分法(陽解法、陰解法)

### 格子生成法
- 構造格子、非構造格子
- 格子配置と解の精度

### 乱流モデル
- 渦粘性
- レイノルズ応力
- $k-\varepsilon$ モデル
- 応力モデル

### 境界条件
- 流入条件、流出条件
- 壁面境界条件
- 圧力境界条件
- 熱的境界条件

### ポスト処理の基礎
- 速度ベクトル表示
- 流体力の算出
- エネルギー損失

### 結果の検証方法の基礎
- 理論との整合性
- 質量流量の保存
- 実験結果等との比較

### コンピュータの基礎
- 計算精度
- CAEプロセス
- プログラミング言語

### 計算力学技術者倫理
- 著作権
- 守秘義務


## Moldflow Adviser 2023
[Moldflow Adviser 2023](https://help.autodesk.com/view/MFAA/2023/JPN/?guid=MFLO-WHATS-NEW-2023-2)
[Moldflow Insight 2023](https://help.autodesk.com/view/MFIA/2023/JPN/)

## 解析事例
[設計事例：折りたたみハンガーの一体化① 量産性の検討](https://nature-architects.com/blog/1388/)
[設計事例：折りたたみハンガーの一体化② 量産性の検討](https://nature-architects.com/blog/1442/)
[設計事例：折りたたみハンガーの一体化② 量産性の検討](https://nature-architects.com/blog/1442/)