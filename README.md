
# Gradient Dicision Boosting Tree Machineで特徴量を非線形化

## この着想から、実践まで2ヶ月ほどかかりました
Facebook社のGradient Boosting Machineで特徴量を非線形化して、CTRを予想するという問題の論文から一年近く経ちましたが、その論文のユニークさは私の中では色あせることなく
しばらく残っています。  

原理的には、単純でGrandient Boosting Machineの特徴量で複数の特徴量を選択して決定木で非線形な状態にして、数値にすることでより高精度でリニアレグレッションなどで様相
