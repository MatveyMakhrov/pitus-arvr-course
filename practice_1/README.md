# Мини-отчёт

## __Отснятый объект__

![Отснятый объект](https://github.com/MatveyMakhrov/pitus-arvr-course/blob/main/practice_1/img/img_6.jpg)

## Выводы о качестве съёмки и реконструкции

* Только 20 из 54 мной сделанных фото были использованы. Возможно это случилось из-за того, что фотографии недостаточно перекрывают друг-друга
 или нужно было покрутить ращличные параметры Feature Extraction/Matching (я этого не делал и прогнал на стандартных настройках).
* Я делал "двухуровневую" съёмку (0° и 45°), и возмодно, между уровнями оказалось слишком мало совпадений, поэтому Colmap не связал все фото в единую модель
(возможно нужно уменьшить высоту съёмки второго уровня).
* Некоторые фотографии, возможно, содержали однотонные или бликующие поверхности, из-за чего Colmap не нашёл достаточного количества ключевых точек.
* Итоговая модель частично корректна, но для полноценной реконструкции нужно либо:
    * переснять объект с большим перекрытием (80–90% между кадрами),
    * либо снизить пороги в настройках COLMAP (например, уменьшить min_num_inliers и min_inlier_ratio, увеличить max_num_features).
 
## Скриншоты получившийся модели

![Отснятый объект](https://github.com/MatveyMakhrov/pitus-arvr-course/blob/main/practice_1/img/img_4.jpg)

![Отснятый объект](https://github.com/MatveyMakhrov/pitus-arvr-course/blob/main/practice_1/img/img_3.jpg)

![Отснятый объект](https://github.com/MatveyMakhrov/pitus-arvr-course/blob/main/practice_1/img/img_5.jpg)

![Отснятый объект](https://github.com/MatveyMakhrov/pitus-arvr-course/blob/main/practice_1/img/img_2.jpg)

![Отснятый объект](https://github.com/MatveyMakhrov/pitus-arvr-course/blob/main/practice_1/img/img_1.jpg)
