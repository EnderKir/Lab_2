# Lab_2

Во всех случаях модель обучалась: опитмизатор - сигмоида, ошибка - категориальная кроссэнтропия, метрика - категориальня точность.

Batch_size = 50.
epoch = 50.

1 Этап - Исходный файл; 
2 Этап- Добавил сверточный слой №3 (kernel_size = 3);
3 Этап- Изменил сверточный слой №3 (kernel_size = 2); 
4 Этап- Добавил еще один сверточный слой и поменял значения kernel_size для 1ого, 2ого, 3его, 4ого сверточных слоев соответственно 1, 2, 2, 4; 

Данные на графиках ниже приведены для 1( оранжевым цветом) и 2( красным цветом) этапов.

![1st-2nd]()

Данные на графиках ниже приведены для 3( голубым цветом) и 4( розовым цветом) этапов.

![2rd-4th]()