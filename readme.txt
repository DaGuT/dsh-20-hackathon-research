Описание файлов с моделями:
* FineTuneModel-DenseNet121NoBn.ipynb - дообучение densenet121 модели без bn и дропаута на новом наборе данных
* FineTuneModel - дообучение модели efficientnetb3
* Hackathon_DSH_* - основное обучение модели, датасет классы, препроцессинг данных
* visualization-* - функции загрузки модели, визуализации, предсказания. Всё, для того, чтобы модель запустить на бэкенде

densenet.py - файл, в котором описан densenet без bn и dropout


Чтобы все могло быть залито на гитхаб ".\lungs_disease_classification\weights\misc\inception_v3_pretrained_imagenet.7z" был заархиирован (изначально он превышал 100мб)