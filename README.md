# titanic-kaggle

データ分析コンペティション"Kaggle"における有名コンペ"Titanic - Machine Learning from Disaster"にて作成したコードです。  
URL:https://www.kaggle.com/c/titanic          
  
##### 使用ファイル  
titanic.ipynb：今回作成したコード  
data/train.csv：訓練データセット  
data/test.csv：テストデータセット  
data/gender_submission.csv：提出ファイル形式  
data/my_submission.csv：提出ファイル  

# データ解析手法/概要：
機会学習手法には、色々試した中で精度が最も高かったランダムフォレストを採用しました。  
ランダムフォレストのハイパーパラメータには、グリッドサーチを用いて見つけた最も精度の高くなったパラメータを用いています。  
予測にはアンサンブル学習を用いようとしましたが、精度が下がってしまった為、ランダムフォレストのみで予測を行いました。  
このコンペに初めて挑んだ時点では全く歯が立たなかったのですが、機械学習に関する一通りの学習を終えて再挑戦して、分類精度を0.66746から0.77511まで上げることが出来ました。  
コードに関する説明は、コード内にコメントとして記述してあります。
