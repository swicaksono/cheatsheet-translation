**1. Machine Learning tips and tricks cheatsheet**

&#10230; **1. Catatan ringkas tips dan trik machine learning** 

<br>

**2. Classification metrics**

&#10230; **2. Matriks klasifikasi**

<br>

**3. In a context of a binary classification, here are the main metrics that are important to track in order to assess the performance of the model.**

&#10230; **3. Dalam konteks klasifikasi biner, terdapat beberapa matriks utama yang penting untuk digunakan dalam mengukur performa dari sebuah model.**

<br>

**4. Confusion matrix ― The confusion matrix is used to have a more complete picture when assessing the performance of a model. It is defined as follows:**

&#10230; **4. Confusion Matrix - Confusion matrix digunakan untuk membantu mengetahui bagaimana gambaran secara umum performa dari model. Didefinisikan sebagai berikut:**

<br>

**5. [Predicted class, Actual class]**

&#10230; **5. [Kelas prediksi, Kelas aktual]**

<br>

**6. Main metrics ― The following metrics are commonly used to assess the performance of classification models:**

&#10230; **6. Matriks utama - Berikut merupakan matriks yang umum digunakan untuk mengukur performa model klasifikasi:**

<br>

**7. [Metric, Formula, Interpretation]**

&#10230; **7. [Formula matriks, Interprestasi]**

<br>

**8. Overall performance of model**

&#10230; **8. Performa model secara umum**

<br>

**9. How accurate the positive predictions are**

&#10230; **9. Bagaimana akurasi prediksi positifnya**

<br>

**10. Coverage of actual positive sample**

&#10230; **10. Cakupan sampel aktual positif**

<br>

**11. Coverage of actual negative sample**

&#10230;**11. Cakupan sampel aktual negatif**

<br>

**12. Hybrid metric useful for unbalanced classes**

&#10230;**12. Matriks gabungan yang berguna untuk kelas data yang tidak seimbang**

<br>

**13. ROC ― The receiver operating curve, also noted ROC, is the plot of TPR versus FPR by varying the threshold. These metrics are are summed up in the table below:**

&#10230; **13. ROC ― Receiver operating curve (ROC) adalah plot TPR yang disandingkan dengan FPR dengan memvariasikan nilai ambang batasnya. Matriks ini dijelaskan pada tabel dibawah berikut:** 

<br>

**14. [Metric, Formula, Equivalent]**

&#10230; **14. [Matriks, Formula, Persamaan]**

<br>

**15. AUC ― The area under the receiving operating curve, also noted AUC or AUROC, is the area below the ROC as shown in the following figure:**

&#10230; **15. AUC (Area Under the Curve) ― Area bawah kurva, adalah area dibawah ROC yang digambarkan sebagai berikut:**

<br>

**16. [Actual, Predicted]**

&#10230; **16. [Aktual, Prediksi]**

<br>

**17. Basic metrics ― Given a regression model f, the following metrics are commonly used to assess the performance of the model:**

&#10230; **17. Matriks sederhana - Diberikan sebuah model regresi f, matriks berikut secara umum digunakan untuk mengukur performa dari model:**

<br>

**18. [Total sum of squares, Explained sum of squares, Residual sum of squares]**

&#10230; **18. [Jumlah total persegi, Penjelasan jumlah persegi, Sisa jumlah persegi]**

<br>

**19. Coefficient of determination ― The coefficient of determination, often noted R2 or r2, provides a measure of how well the observed outcomes are replicated by the model and is defined as follows:**

&#10230; **19. Koefisisen determinasi ― Koefesien determinasi dinotasikan dengan R2 atau r2, digunakan untuk mengukur bagaimana baik tidaknya hasil observasi  yang ditiru oleh model, sebagai berikut:**

<br>

**20. Main metrics ― The following metrics are commonly used to assess the performance of regression models, by taking into account the number of variables n that they take into consideration:**

&#10230;  **20. Matriks utama ― Matriks berikut adalah yang umum digunakan untuk mengukur performa dari model regresi, dengan mengambil sejumlah variabel n sebagai pertimbangan:**

<br>

**21. where L is the likelihood and ˆσ2 is an estimate of the variance associated with each response.**

&#10230; **21. Dimana L adalah kecenderungan dan ˆσ2 adalah estimasi dari asosiasi varian dan responnya.**

<br>

**22. Model selection**

&#10230; **22. Seleksi model**

<br>

**23. Vocabulary ― When selecting a model, we distinguish 3 different parts of the data that we have as follows:**

&#10230; **23. Kamus - Dalam memilih sebuah model, kita membagai tiga bagian data sebagai berikut:**

<br> 

**24. [Training set, Validation set, Testing set]**

&#10230; **24. [Data latih, data validasi, data uji]**

<br>

**25. [Model is trained, Model is assessed, Model gives predictions]**

&#10230; **25. [Model terlatih, model tervalidasi, prediksi model]**

<br>

**26. [Usually 80% of the dataset, Usually 20% of the dataset]**

&#10230; **26. [Biasanya data latih terdiri atas 80% dataset, sedangkan 20% merupakan data uji/tes]**

<br>

**27. [Also called hold-out or development set, Unseen data]**

&#10230; **27. [Disebut juga hold-out atau development set, Data yang belum pernah dilihat oleh model]**

<br>

**28. Once the model has been chosen, it is trained on the entire dataset and tested on the unseen test set. These are represented in the figure below:**

&#10230; **28. Setelah model dipilih, model dilatih dengan seluruh dataset dan diuji coba pada data yang belum pernah dijumpai. Hal ini direpresentasikan sebagai berikut:**

<br>

**29. Cross-validation ― Cross-validation, also noted CV, is a method that is used to select a model that does not rely too much on the initial training set. The different types are summed up in the table below:**

&#10230; **29. Cross-validation ― Cross-validation, disebut juga sebagai CV, adalah metode yang digunakan untuk memilih model yang tidak bergantung pada dataset latih pertama. Perbedaannya diringkas dalam tabel berikut:** 

<br>

**30. [Training on k−1 folds and assessment on the remaining one, Training on n−p observations and assessment on the p remaining ones]**

&#10230; **30. []**

<br>

**31. [Generally k=5 or 10, Case p=1 is called leave-one-out]**

&#10230; **31. [Umumnya k=5 atau 10, kasus p=1 disebut sebagai leave-one-out]**

<br>

**32. The most commonly used method is called k-fold cross-validation and splits the training data into k folds to validate the model on one fold while training the model on the k−1 other folds, all of this k times. The error is then averaged over the k folds and is named cross-validation error.**

&#10230; **32. Metode yang umum digunakan adalah k-fold crosss-validation yang membagi data latih menjadi k folds untuk memvalidasi model pada salahsatu fold, sementara melatih model pada k-1 folds, selama k times. Total error yang dihasilkan kemudian dirata-rata dan disebut sebagai cross-validation error.**

<br>

**33. Regularization ― The regularization procedure aims at avoiding the model to overfit the data and thus deals with high variance issues. The following table sums up the different types of commonly used regularization techniques:**

&#10230; **33. Regularisasi ― Prosedur regularisasi bertujuan untuk mencegah model overfit data dan isu variansi yang tinggi. Tabel berikut meringkas beberapa jenis teknik regularisasi:**

<br>

**34. [Shrinks coefficients to 0, Good for variable selection, Makes coefficients smaller, Tradeoff between variable selection and small coefficients]**

&#10230; **34. [Memangkas koefisien menjadi 0, bagus untuk pemilihan variabel, membuat koefisien menjadi lebih kecil. Adanya tradeoff antara pemilihan variabel dan koefisien yang kecil]**

<br>

**35. Diagnostics**

&#10230; **35. Diagnostik**

<br>

**36. Bias ― The bias of a model is the difference between the expected prediction and the correct model that we try to predict for given data points.**

&#10230; **36. Bias ― Bias pada model adalah perbedaan antara hasil prediksi dengan hasil dari model yang seharusnya diprediksi pada data point yang diberikan (Underfitting).**

<br>

**37. Variance ― The variance of a model is the variability of the model prediction for given data points.**

&#10230; **Varian ― Varian sebuah model adalah tidak konsistennya hasil prediksi sebuah model atas data poin yang diberikan (Overfitting).**

<br>

**38. Bias/variance tradeoff ― The simpler the model, the higher the bias, and the more complex the model, the higher the variance.**

&#10230; **38. Bias/variance tradeoff ― Semakin sederhana model, semakin tinggi bias, dan semakin kompleks model, semakin tinggi variannya.**

<br>

**39. [Symptoms, Regression illustration, classification illustration, deep learning illustration, possible remedies]**

&#10230; **39. [Symptom, Ilustrasi regresi, ilustrasi klasifikasi, ilustrasi deep learning, possible remedies]**

<br>

**40. [High training error, Training error close to test error, High bias, Training error slightly lower than test error, Very low training error, Training error much lower than test error, High variance]**

&#10230; **40. [Training error tinggi, Training error hampir sama dengan test error, Bias tinggi, Training error lebih kecil daripada test error, Training error sangat kecil, Training error lebih kecil daripada test error, Varian yang tinggi]**

<br>

**41. [Complexify model, Add more features, Train longer, Perform regularization, Get more data]**

&#10230; **41. [Kompleksitas model, Menambah fitur, Penambahan waktu training, Melakukan regularisasi, Menambah data]**

<br>

**42. Error analysis ― Error analysis is analyzing the root cause of the difference in performance between the current and the perfect models.**

&#10230; **42. Analisis error ― Analisis eror adalah analisa sebab utama terjadinya perbedaan performa antara model sekarang dengan model yang sempurna** 

<br>

**43. Ablative analysis ― Ablative analysis is analyzing the root cause of the difference in performance between the current and the baseline models.**

&#10230; **43. Analisis ablatif ― Analisis ablatif adalah analisa sebab utama terjadinya perbedaan performa antara model yang sekarang dengan model baseline.**

<br>

**44. Regression metrics**

&#10230; **44. Matriks regresi**

<br>

**45. [Classification metrics, confusion matrix, accuracy, precision, recall, F1 score, ROC]**

&#10230; **45. [Metriks klasifikasi, Matriks confusion, akurasi, presisi, recall, Nilai F1, ROC]**

<br>

**46. [Regression metrics, R squared, Mallow's CP, AIC, BIC]**

&#10230; **46. [Metriks regresi, R squared, Mallow's CP, AIC, BIC]**

<br>

**47. [Model selection, cross-validation, regularization]**

&#10230; **47. [Model selection, cross-validation, regularization]**

<br>

**48. [Diagnostics, Bias/variance tradeoff, error/ablative analysis]**

&#10230; **48. [Diagnostics, Bias/variance tradeoof, error/ablative analysis]**
