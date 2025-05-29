# SistersLabBitirme
Bu projede, teknoloji sektöründeki cinsiyet eşitsizliğini veri analizi ve makine öğrenmesi ile inceledim. Farklı veri setleri birleştirildi, XGBoost ve SMOTE gibi yöntemlerle sınıf dengesizliği ele alındı.

Modeller:
XGBoost: Yüksek kadın recall (0.75) ama düşük genel doğruluk (0.61).

SMOTE + GridSearchCV: Dengeli sonuçlar, düşük accuracy (0.58).

RandomizedSearchCV: Hızlı ama fark yaratmadı.

Sonuç:
Verideki kadın eksikliği, modellerin performansını doğrudan etkiledi. Eşitsizlik, teknik araçlarla da görünür hale geldi.

