Разработка программы аугментации обучающей выборки и обучения на ней нейросети.

Агафонов Сергей задача 5 на собеседование ИППИ АД.

Все, что касается аугментации лежит в папке augmentation.

Пример ввода:

![](https://github.com/sergeya884/img_augmentation/blob/main/photo/input.png)

Примеры вывода (слабые настройки аугментации):

![](https://github.com/sergeya884/img_augmentation/blob/main/photo/1.png) ![](https://github.com/sergeya884/img_augmentation/blob/main/photo/2.png) ![](https://github.com/sergeya884/img_augmentation/blob/main/photo/3.png) ![](https://github.com/sergeya884/img_augmentation/blob/main/photo/4.png)

Все, что касается классификатора в папке classifier.

Примеры из тестовой выборки

![](https://github.com/sergeya884/img_augmentation/blob/main/photo/eight_03.png) ![](https://github.com/sergeya884/img_augmentation/blob/main/photo/nine_01.png) ![](https://github.com/sergeya884/img_augmentation/blob/main/photo/zero_02.png)

Итоги обучения такие. После обучения с аугментацией процент правильных ответов 76, что весьма неплохо, учитывая простоту самой нейросети и наличия целых 10 классов. Однако обучение только на идеальных примерах дало тоже неплохой результат в 67 процентов правильных ответов. Мне кажется разница между подходами будет ощущаться сильнее если еще "поподкручивать" настройки аугментации и сделать меньше классов. Но все же аугментация работает и значительно улучшает результат.
