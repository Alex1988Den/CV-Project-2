# Проект по детекции масок на лицах

Этот проект посвящен разработке и обучению моделей для детекции масок на лицах с использованием методов глубокого обучения. Мы сравниваем одноуровневые и двухуровневые детекторы с использованием метрик Intersection over Union (IoU) и Average Precision (AP).
Описание

В данном проекте используются предобученные модели, такие как YOLOv5 и Faster R-CNN, для распознавания лиц с масками, масок, не надетых на лицо и неправильно надетых масок. Основная цель - достичь точности выше 85% на валидационной выборке.
Структура проекта

    data/ — Датасеты, используемые для обучения и валидации модели.
    models/ — Сохраненные модели и веса, полученные в процессе обучения.
    notebooks/ — Jupyter ноутбуки с кодом обучения, валидации и визуализации.
    src/ — Исходный код, включая определение моделей и функции для обучения.
    results/ — Визуализация результатов, включая графики и примеры предсказаний модели.

Установка

Чтобы запустить проект локально, выполните следующие шаги:

    Клонируйте репозиторий:

    bash

git clone https://github.com/USERNAME/REPOSITORY_NAME.git
cd REPOSITORY_NAME

Создайте и активируйте виртуальное окружение:

bash

python -m venv myenv
source myenv/bin/activate  # Для Windows используйте myenv\Scripts\activate

Установите необходимые зависимости:

bash

pip install -r requirements.txt

Запустите Jupyter Notebook для воспроизведения экспериментов:

bash

    jupyter notebook

Использование

Для обучения модели запустите ноутбук train_model.ipynb, который содержит шаги по загрузке данных, обучению и оценке модели.
Результаты

Модель достигла точности выше 85% на валидационной выборке. Классификация изображений по наличию масок показала высокую точность и надежность.
Визуализация

Примеры предсказаний модели можно найти в папке results/.
Лицензия

Этот проект лицензирован под MIT License — подробности см. в файле LICENSE.
Датасет

Датасет содержит изображения с лицами в трех категориях:

    С маской
    Без маски
    Маска надета неправильно

Контакты

Для вопросов и предложений вы можете связаться со мной через GitHub.
