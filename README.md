# Primati_TPU

## Задача: 
Реализация модели для анализа уровня стресса испытуемого путем исследования показаний датчиков фотоплетизмограмма и пьезоплетизмограмма, 
а также информацию о вопросе, во время ответа на который проходили измерения.

Основная идея решения состоит в использовании различных характеристик данных с датчиков и их комбинации с характеристиками конкретного теста.

Для решения были использованы нейронные сети различных архитектур, а также такие методы как решающие деревя и их ансамбли такие как CatBoost и XGBoost
Стек технологий: Keras, PyTorch, Numpy, Pandas, Sklearn, CatBoost, XGBoost

Предполагается использование ансамбля моделей для уточнения результатов и извлечения максимального количества информации для улучшения классификации.

## Для запуска проекта
Установите файл main.py и запустите его. 
Появится окно для выбора Excel-файла, далее будет представленна информация из файла и ожидаемые предсказания.
В случае, если эксперт сомневаетс в решении модели, он может щелкнуть левой кнопкой на строку 
с вопросом и получит графики изменения показаний датчиков испытуемого.
