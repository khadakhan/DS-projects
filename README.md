EDA
Проведение первичного анализа данных с использованием библиотек Pandas, NumPy, Matplotlib:
1.	Структуры данных
2.	Работа с индексами
3.	Чистка
4.	Математические операции
5.	Операции объединения
6.	Агрегирование данных
7.	Визуализация
По программе курса

1.	Применение метрических алгоритмов (kNN, k-Means, DBSCAN) для предсказание оттока клиентов (датасет "telecom churn"). Используемые библиотеки: pandas, sklearn, matplotib. Оценка качества предсказания метриками accuracy, precision, recall. Подготовка: Очистка, нормализация, удаление дублей, заполнение пропусков, обработка категориальных признаков, Stratified разделения на train/val/test, выявление сильно скоррелированных признаков, уменьшение размерности PCA методом. Ссылка на colab: https://colab.research.google.com/drive/1gS9hjg6l-dlnqhqG7VLTGuqIHbVw6QCr?usp=sharing
2
2.	Применение методов вычислительной линейной алгебры (SVD разложение, PCA) для задачи классификации-распознавание нарисованной цифры (датасет "MNIST"), а также для задачи сжатия изображение. Ссылка на colab: https://colab.research.google.com/drive/12OFTFH7tdxAkDjm9vfB2c4kvD_9zgpgV?usp=sharing

Задача сжатия звука. Ссылка на colab: https://colab.research.google.com/drive/1iFdLGXFjIryAHat_E-PVXcVHwyqqOwvd?usp=sharing

3.	Применение линейной модели для задачи регрессии, сравнение с алгоритмом kNN для регрессии на примере задачи определения цены автомобиля (датасет "Automobile"). Улучшение метрик качества. Ссылка на colab: https://colab.research.google.com/drive/1gGhBWO3om_uxptxSPp4NsbFj_r3oSwX8?usp=sharing

4.	Применение логистической регрессии для задачи бинарной классификации, сравнение с kNN на примере задачи определение уровня заработка человека (датасет "Adult"). Метрики качества для задачи классификации:Confusion matrix, accuracy, precision, recall, f1, ROC-AUC. Применение логистической регрессии для задачи многоклассовой классификации-определения сорта ириса (датасет "iris"). Ссылка на colab: https://colab.research.google.com/drive/1P4z6Ie7RUNBDDQAKvs-is8TsQiD-Nb4j?usp=sharing

5.	Применение линейной регрессии для создания модели ценообразования на бриллианты (датасет "diamonds"). Очистка данных, baseline и улучшение качества модели. Применение логистической регрессии для определения гендера (датасет "body perfomance"). Применение .логистической регрессии для определения класса физической формы (многоклассовая классификация), метрики качества:OvO, OvR, сравнение с алгоритмом kNN. Ссылка на colab:  https://colab.research.google.com/drive/1uE6-Xw9IqtYNravhJa9xesglHE6_5pwC?usp=sharing

6.	Применение модели линейной регрессии для определения степени прогрессии заболевания диабетом (датасет “diabets”) с использованием bagging . Решение задачи определения сорта ириса (датасет “Iris Fisher”) с использованием stacking (LogReg, SVM, kNN). Ссылка на colab: https://colab.research.google.com/drive/1XJCtL3A2kfNVtRb5N3VNjJgBJFHNR5Tv?usp=share_link

7.	Применение модели решающего дерева для оценки качества вина (датасет Wine Quality). Подбор гиперпараметров с использованием GridSearchCV. Улучшение качества предсказания при помощи модели случайного леса. Подбор гиперпараметров при помощи RandomizedSearchCV. Ссылка на colab: https://colab.research.google.com/drive/1eBU2_IGENIxEJJencF7J5KbvTYXbVvLv?usp=sharing

8.	Применение модели градиентного бустинга (CatBoost и LightGBM) для задачи определение болезни Паркинсона. Подбор гиперпараметров, определение важности признаков Permutation Importance, отчет о работе модели при помощи SHAP. Ссылка на colab: https://colab.research.google.com/drive/1-zZdYEbB_ZQe-pQJvq65dK5AS3b0Y4-w?usp=sharing

9.	Предсказание количества очков в предстоящей игре, предсказание исхода игры (победа, поражение, ничья). Работа с базой данных прошедших матчей с применением sqlite3. Извлечение необходимых данных из таблиц, создание дополнительных признаков, создание таргета (итог игры), чистка данных, заполнение пропусков, выбор признаков, формирование датасета для обучения модели, выбор метрик и алгоритма (LightGBM). Важность признаком (MDI). Подбор параметров (RandomizedSerchCV). Stacking (RF,LGBM,SVC, LogisticRegression). Отчет от важности признаков (SHAP). Ссылка на colab: https://colab.research.google.com/drive/1-FTmXZBjqf5u0pZM20LWycmaBoQ2iham?usp=sharing

10.	DL. Применение полносвязанной нейронной сети ( при помощи PyTorch) для задачи определения рукописных цифр на примере датасета MNIST.Построение нейросети: определение количества скрытых слоев, функций активации, выбор функции потерь и оптимизатора. Ссылка на colab: https://colab.research.google.com/drive/1dEGWNyvLCnOMZd1LjOAOhDf6fK83OdZs?usp=sharing

11.	
Групповые проекты

1.	Участие в групповом проекте по первичному анализу данных (EDA) на примере датасета Netflix. Ссылка на colab: https://colab.research.google.com/drive/1vk9ETZyEkug5cebT9r-NV1AcN75bi4ft?usp=sharing
2.	Участие в групповом соревновании на Kaggle. Использование продвинутых техник регрессии для определение цены недвижимости https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques. Ссылка на colab: https://colab.research.google.com/drive/17ouYqER-rJRV1TMsEds-qWlcl3qBb7oq?usp=share_link

Индивидуальные проекты

Применение методов анализа временных рядов для предсказания курса криптовалюты на примере датасета из Kaggle https://www.kaggle.com/competitions/g-research-crypto-forecasting/overview. Ссылка на Colab: https://colab.research.google.com/drive/1RiVNL_NDdoODwe1YJoZuhcn0etxJ03NV?usp=share_link
