# DL
Репозиторий с учебными проектами по глубинному обучению. Представленные проекты:
1. Предсказание года выпуска песни
- Обучение Ridge-регрессии в качестве бейзлайна
- Имплементация цикла обучения модели линейной регрессии
- Реализация пайплайна обучения полносвязной нейронной сети
- Проведение экспериментов с оптимизаторами, шедулерами, коэффициентами обучения, архитектурой модели, функциями активации, дропаутом для достижения наилучшего качества модели
2.	Классификация изображений при помощи популярных архитектур моделей
- Подготовка данных: нормализация и аугментация
- Проведение экспериментов с различными не предобученными архитектурами моделей (resnet18, resnet34, resnest14d из библиотеки timm) для подбора оптимальной для задачи архитектуры 
- Файн-тюнинг моделей (resnest14d, resnest50d, resnest101e, efficientnet_b2, efficientnet_b3)
- Проведение и логирование в wandb экспериментов с гиперпараметрами
3.	Детекция объектов на изображениях
- Работа с аннотациями в формате xml и отрисовка разметки на изображениях
- Самописная реализация YOLO-like детектора
- Перекладывание данных в формат yolov8 и обучение готовой архитектуры YOLO v8 от ultralytics
4.	Категоризация новостей
- Предобработка данных и создание словаря слов
- Реализация датасета для поставки данных в нейросеть, архитектур и модуля для обучения в pytorch_lightning
- Обучение, инференс и оценка качества моделей
- Подбор оптимального значения порога классификации
