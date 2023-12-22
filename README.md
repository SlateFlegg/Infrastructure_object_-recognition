## Infrastructure object recognition using satellite data
Hackathon took place in november 2023. 
The case was to develop and train a model for multi-story building recognition on of high spatial resolution sattallite images.
My solution is vgg_unet (2 classes). For choosing and training the model Yandex.DataSphere was uses, so there is only final model in the notebook.
For more details please take a look: [presentation (in russian)](https://disk.yandex.ru/i/aWQJgSJBDTX8lA); [screencast (in russian)](https://disk.yandex.ru/i/etSjWWC5p1CKJA).

## Распознание инфраструктурных объектов на космоснимках высокого разрешения
Хакатон проводился в рамках "Цифрового прорыва. Сезон: ИИ" в ноябре 2023.
Задача: выбрать и натренировать модель для бинарной классификации здание/не здание (результат - бинарная маска).
Моё решение было заключается в выборе модели vgg_unet и подборе параметров. Для выбора и тренировки моделей использовались дополнительные мощности DataSphere, поэтому в тетрадке только итоговая модель (и подгрузка весов).
В дополнение есть: [презентация](https://disk.yandex.ru/i/aWQJgSJBDTX8lA) и [скринкаст](https://disk.yandex.ru/i/etSjWWC5p1CKJA). 
