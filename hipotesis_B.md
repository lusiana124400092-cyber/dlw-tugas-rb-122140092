B2 Dropout: dropout 0,2 menurunkan val MAE karena data latih hanya

672 sampel sehingga model rawan menghafal. Dropout 0,5 terlalu besar

dan memperburuk hasil.



B4 Loss: Huber lebih baik dari MSE karena trafik punya lonjakan

mendadak yang membuat MSE terlalu dipengaruhi outlier.

