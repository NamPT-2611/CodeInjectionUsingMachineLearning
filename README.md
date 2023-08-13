# CodeInjectionUsingMachineLearning

## Kết quả chạy Baseline
|Methods|Naïve Bayes|	Decision Tree|	Random Forest|	Logistic Regression|	AdaBoost|
|:-----:|:----------:|:------------:|:-------------:|:-------------------:|:--------:|
|BOW|	0.83|	0.96|	0.96|	0.95|	0.56|
|TF-IDF|	0.87|	0.96|	0.96|	0.95|	0.56|
|Word2Vec|	0.47|	0.94|	0.95|	0.61|	0.56|

## Kết quả multiclass đã combine:
<li>TF-IDF + NB	0.87</li>
<li>TF-IDF + RF	0.96</li>
<li>LSTM	0.97</li>

## Kết quả sử dụng phương pháp GAN trong xác định kiểu tấn công mới với các bộ trích xuất đặc trưng:
|BOW|TF-IDF|Word2Vec|
|:-----:|:----------:|:------------:|
|0.70|0.72|0.63|

## Kết quả sử dụng phương pháp GAN(kết hợp LSTM trong model Generative) trong xác định kiểu tấn công mới với các bộ trích xuất đặc trưng
|BOW|TF-IDF|Word2Vec|
|:-----:|:----------:|:------------:|
|0.77|0.78|0.63|
