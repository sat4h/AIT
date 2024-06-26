# AIT

## Ионов Артем группа 6131-010402D

### [1. Лабораторная работа](https://github.com/sat4h/AIT/blob/98c145a148a73b1423144aebe9f0936d091fc45a/LR1Ionov/6131_IonovA_lab_1_pandas.ipynb)

### [2. Лабораторная работа](https://github.com/sat4h/AIT/blob/4f4aeca0fa89fed0577e9cac5e2a2d16998740e1/LR2Ionov/6131_IonovA_lab_2_plots.ipynb)

### [3. Лабораторная работа](https://github.com/sat4h/AIT/blob/98c145a148a73b1423144aebe9f0936d091fc45a/LR3Ionov/6131_IonovA_lab_3_kNN.ipynb)

### [4. Лабораторная работа](https://github.com/sat4h/AIT/blob/98c145a148a73b1423144aebe9f0936d091fc45a/LR4Ionov/6131_IonovA_lab_4_tree.ipynb)

### [5. Лабораторная работа](https://github.com/sat4h/AIT/blob/b1f009827cd006c930dfc552185983b4985b56bb/LR5Ionov/6131_IonovA_lab_5_regression.ipynb)

### [6. Лабораторная работа](https://github.com/sat4h/AIT/blob/f96c9a4ad9b154ccf5b2d8257ce0ad264d83e682/LR6Ionov/6131_Ionov_lab_6_boosting.ipynb)

**Для 1 лабораторной работы** был выбран датасет ["Cardiovascular Disease dataset"](https://www.kaggle.com/datasets/sulianova/cardiovascular-disease-dataset) <-- ссылка на датасет. Набор данных состоит из 70 000 записей данных пациентов, 11 признаков + цель.

![image](https://github.com/sat4h/AIT/assets/146749026/27122a0a-9316-412c-919a-70a7ffcc3582)

**Для 2 лабораторной работы** был выбран встроенный датасет из sklearn ["Automobile Dataset"](https://www.kaggle.com/datasets/toramky/automobile-dataset) <-- ссылка на описание датасета из Kaggle. 

Датасет "Automobile DataSet" из репозитория UCI Machine Learning. Этот датасет содержит информацию о различных автомобилях, включая числовые признаки, такие как цена, объем двигателя, количество лошадиных сил, а также категориальные признаки, такие как тип кузова, количество дверей, тип привода и т.д.

Содержание
Этот набор данных состоит из трех типов объектов: (а) спецификация автомобиля с точки зрения различных характеристик, (б) присвоенный ему рейтинг страхового риска, (в) его нормированные потери при использовании по сравнению с другими автомобилями. Второй рейтинг соответствует тому, насколько автомобиль более рискован, чем указывает его цена. Изначально автомобилям присваивается символ фактора риска, связанный с их ценой. Затем, если риск выше (или меньше), этот символ корректируется путем перемещения его вверх (или вниз) по шкале. Актуарии называют этот процесс «символизацией». Значение +3 указывает на то, что авто рискованное, -3 — что оно, вероятно, довольно безопасное.

Третий фактор – это относительная средняя выплата за ущерб за год страхования транспортного средства. Это значение нормализовано для всех автомобилей определенной размерной категории (маленькие двухдверные, универсалы, спортивные/специальные и т. д.) и представляет собой средний убыток на автомобиль в год.
        
**Для 3 лабораторной работы** был выбран датасет для бинарной классификации ["Cardiovascular Disease dataset"](https://www.kaggle.com/datasets/sulianova/cardiovascular-disease-dataset) <-- ссылка на датасет. Набор данных состоит из 70 000 записей данных пациентов, 11 признаков + цель.

Для многоклассовой классификации был выбрал ["WineData"](https://archive.ics.uci.edu/dataset/109/wine) <-- ссылка на описание датасета. Датасет загружал по ["ссылке"](https://archive.ics.uci.edu/ml/machine-learning-databases/wine/wine.data) 

**Для 4 лабораторной работы** пришлось выбрать датасет по меньше). Выбран датасет ["Admission Prediction"](https://www.kaggle.com/datasets/mananmehta02/admission-prediction) <-- ссылочка на датасет. Данный набор данных состоит из данных 400 студентов и оценок, полученных ими в различных тестах, таких как GRE, TOEFL, а также их CGPA в колледже, а также о том, проводилась ли ими какая-либо исследовательская работа во время окончания учебы. 

**Для 5 лабораторной работы.** В 2002–2004 годах Колумбийский университет провел эксперимент по быстрым свиданиям, в ходе которого они отслеживали данные 21 сеанса быстрых свиданий, в основном среди молодых людей, встречающихся с людьми противоположного пола. ["Dataset"](https://www.kaggle.com/datasets/mexwell/speed-dating/data) <-- ссылочка на датасет.

**В 6 лабораторной работе** был использован ["Titanic - Machine Learning from Disaster"]([https://www.kaggle.com/datasets/shubh0799/churn-modelling/data](https://www.kaggle.com/c/titanic/data?select=gender_submission.csv)) датасет.

Обучающий набор следует использовать для построения моделей машинного обучения. Для обучающего набора мы предоставляем результат (также известный как «основная истина») для каждого пассажира. Ваша модель будет основана на таких «особенностях», как пол и класс пассажиров. Вы также можете использовать разработку функций для создания новых функций.

Набор тестов следует использовать, чтобы увидеть, насколько хорошо ваша модель работает на невидимых данных. Для тестового набора мы не предоставляем основную информацию о каждом пассажире. Ваша задача — предсказать эти результаты. Для каждого пассажира в тестовом наборе используйте обученную вами модель, чтобы предсказать, пережили ли они затопление Титаника.

survival	Survival	0 = No, 1 = Yes

pclass	Ticket class	1 = 1st, 2 = 2nd, 3 = 3rd

sex	Sex	

Age	Age in years	

sibsp	# of siblings / spouses aboard the Titanic	

parch	# of parents / children aboard the Titanic	

ticket	Ticket number	

fare	Passenger fare	

cabin	Cabin number	

embarked	Port of Embarkation	C = Cherbourg, Q = Queenstown, S = Southampton

