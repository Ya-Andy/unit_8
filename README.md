# unit_8
**ПРОЕКТ FORD VS FERRARI: определяем модель авто по фото**

<a name="ОГ"></a> 
## ОГЛАВЛЕНИЕ     

[Основная информация.](#ОС)      
[Что нужно сделать в проекте.](#КР)    
[Этапы работы.](#ЭТ)    
[Результаты.](#РЗ)    

<a name="ОС"></a> 
## Основная информация о проекте:

Вы продолжаете работать в компании «Старый друг», занимающейся продажей автомобилей с пробегом.

Вы с коллегами сидите в кафе, и за обедом речь заходит о курсе по нейронным сетям, который вы собираетесь проходить в этом месяце. 
Все с интересом слушают, особенно Анна из отдела продаж. Именно для её менеджеров вы собрали модель пару месяцев назад (проект _Выбираем авто выгодно?_).

Анна говорит: Смотри, мои менеджеры тратят много времени на поиск автомобилей в базе. Мы хотим, чтобы, скажем, система выдавала информацию по фотографии. 
Такое можно сделать с помощью твоих нейронных сетей?

Сделать это можно с помощью модели, которая предсказывала бы модели автомобилей по их фотографиям.  
Следовательно, вам нужно построить модель классификации изображений.  

*Датасет, содержащий все доступные на данный момент фотографии, находится на* **kaggle **

:arrow_up:[к оглавлению](#ОГ)

<a name="КР"></a> 
## Что нужно сделать в проекте. 

1. Изучить данные.
2. Построить baseline решения под руководством автора модуля.
3. Ознакомиться с критериями оценивания проекта.
4. На основе baseline и данных в нём рекомендаций повысить точность модели.
5. Задавать вопросы одногруппникам и в канал _slack_ **_0_real_ds_ford_vs_ferrari_**.
6. Загрузить итоговое решение на kaggle и добавить описание проекта на git.
7. Получить обратную связь от ментора.     


:arrow_up:[к оглавлению](#ОГ)

<a name="ЭТ"></a> 
## Этапы работы над проектом: 

1. Первичный осмотр данных датасет. 
2. Построить свой классификатор изображений.
3. Применить различные методы предобработки изображений.
4. Задействовать сразу несколько методов обучения (finetuning, transfer learning и так далее).
5. Научиться использовать предобученные модели для решения своих задач.
6. Найти и использовать в работе State of the Art (SOTA)-модели.

:arrow_up:[к оглавлению](#ОГ)

<a name="РЗ"></a> 
## Результаты работы: 

В ходе работы над проектом:

- Подобраны LR, optimizer, loss
- Добавлена аугментация albumentations
- Применена архитектура EfficientNetB7
- Подобраны другие переменные (размер картинки, батч и т.п.)
- Добавлена Batch Normalization
- Изменена архитектура “головы”
- Применены дополнительные функции callback Keras

:arrow_up:[к оглавлению](#ОГ)

