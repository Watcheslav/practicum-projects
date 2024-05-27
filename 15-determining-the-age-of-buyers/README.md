## [Проект 15. Определение возраста покупателей](15-determining-the-age-of-buyers--computer-vision.ipynb)


### Цель проекта

Провести исследование с целью построения нейронной сети, которая поможет определить по фотографии приблизительный возраст человека.

Результаты исследования позволят определять возраст клиентов в прикассовой зоне сетевого супермаркета «Хлеб-Соль», чтобы:
- анализировать покупки и предлагать товары, которые могут заинтересовать покупателей этой возрастной группы;
- контролировать добросовестность кассиров при продаже алкоголя.

Входные данные: набор фотографий людей с указанием возраста, взятый с сайта [ChaLearn Looking at People](https://chalearnlap.cvc.uab.cat/dataset/26/description/).


### Задачи проекта

1. Выполнить исследовательский анализ данных.
2. Построить и обучить модель.
3. Написать общий вывод.

Добьёмся значения *MAE* на тестовой выборке не больше 8.


### Навыки и инструменты

- matplotlib.pyplot
- pandas
- python
- tensorflow.keras.preprocessing.image


### Общий вывод

В результате исследования с помощью свёрточной нейронной сети `ResNet50` глубиной в 50 слоев удалось получить значение метрики *MAE* = 6.28 на тестовой выборке, что соответсвует изначальному требованию в условии задачи проекта.