# ml-interpretation

解釈手法
- PFI : Permutation Feature Importance
- PD : Partial Dependence
- ICE : Individual Conditional Expectation
- SHAP : SHapley Additive exPlanations
    - SHAPは適度な粒度で集計･可視化を行うことで，PDやPFIのようによりマクロな視点の解釈手法として利用することが可能
    
解釈手法の活用方法
- **モデルのデバッグ**
    - 事前知識と整合的か，想定外の挙動はないか→比較的安全な使い方
- **モデルの振舞いを解釈**
    - モデルは特徴量Aを重視している，特徴量Aが大きくなると予測値が大きくなる→モデルの一側面をだけなので間違った解釈をする可能性
- **因果関係の探索**
    - モデルの振舞いを因果関係として解釈→実験やより厳密な因果推論の手法を合わせて使うべき