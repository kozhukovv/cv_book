# Морфологические преобразования
Модуль для морфологических преобразований 

### 1_threshhold
- описана работа функции threshold
    Функция работает с чб изображениями, которая часто применяется для выделения определнных областей на фото. Выполняется сравнение кадого пикселя с пороговым значением после чего изменеятся его интенсивность

### 2_blur
- описана работа функции GaussianBlur 
    Работает с помощью ядра Гауса, мы указываем ширину и высоту ядра, которые должны быть положительными и нечетными. Размытие по Гауссу очень эффективно удаляет гауссовский шум с изображения.
- описана работа функции medianBlur 
    Эффективен при удалении ччеткого шума, который похож на крошки
- описана работа функции bilateralFilter 
    Эффективен в удалении шума, сохраняя резкость краев. Работает медленнее чем другие методы

### 3_MakeBorder
- описана работа функции copyMakeBorder 
    Добавляет рамку к фотографии, есть несколько вариантов работы. Можно применять для расширения фотографии

### 4_erode_and_dilate
- описана работа функции erode
    Данная функция работает так, что все пиксели около границы будут отброшены в зависимости от размера ядра. Таким образом, толщина или размер объекта переднего плана уменьшается, или уменьшается белая область на изображении.
- описана работа функции dilate
    Работает обратно eross