# multilabel-emotion-analysis
Girilen cümlenin içerdiği duyguları belirten proje. Bert, Distilbert ve Roberta ile çalışmaktadır. Training için HuggingFace'deki GoEmotions dataseti üstünde oynamalar yapılarak kullanıldı. Dataset cümleleri multilabel yani aynı anda birden fazla duyguyu içerebilecek şekilde modele verilmektedir.

dataset.ipynb dosyası olduğu gibi çalıştırılır ve dataset oluşur.

Sonra model.ipynb çalıştırılır, model eğitilir ve kaydedilir.

Sonrasında arayuz.ipynb dosyası çalıştır ve kullanıcının gireceği cümleler için arayüz açılır.
