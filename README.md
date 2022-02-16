# Сентиментальный анализ рынка акции
В этом практическом проекте мы обучим модель глубокого обучения Long Short Term Memory (LSTM) для проведения анализа рыночной ситуации на акциях. Обработка естественного языка (NLP) работает путем преобразования слов (текста) в числа, эти числа затем используются для обучения модели AI/ML, чтобы делать прогнозы. В этом проекте мы построим модель машинного обучения для анализа тысяч твитов в Twitter с целью предсказания настроения людей по отношению к определенной компании или акции. Алгоритм может быть использован для автоматического понимания настроений из публичных твитов, что может быть использовано в качестве фактора при принятии решения о покупке/продаже ценных бумаг. Данные для обучение были полученный на сайте [Kaggle](https://www.kaggle.com/adeyoyintemidayo/stock-data-eda-and-prediction/data). Мы выполним следующие этапы:
* Импорт наборов данных и библиотек
* Выполняем очистку данных
* График wordcloud
* Визуализация очищенных наборов данных
* Подготовка данных путем токенизации и добавления символов
* Создание глубокой нейронной сети, основанной на индивидуальном подходе, для проведения анализа настроений
* Оценка работы обученной модели
