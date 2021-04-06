1.	Рабочая область разделена на два крупных сегмента: область визуализации и правая часть, которая в свою очередь разделена на область параметров и область характеристик.
2.	В области параметров сделаны три поля ввода input типа range с минимальными, максимальными параметрами и шагом, согласно заданию. Изменение значений приводит к соответствующим изменениям в области параметров и области характеристик, при нажатии на кнопку Start возможность изменения параметров блокируется.
3.	Область характеристик. Циклическая частота автоматически пересчитывается по указанной формуле. Время колебаний в секундах отсчитывается после нажатия кнопки Start. Количество полных колебаний рассчитано по формуле, как время колебаний умноженное на период колебаний для пружинного маятника (t * 2* Pi * √m/k). Координата X высчитывается по формуле и ее значение пересчитывается раз в секунду. 
4.	Область визуализации.
В связи с отсутствием должного опыта в анимации на чистых HTML / CSS / SVG, было принято найти готовое решение анимации пружинного маятника. Найденный пример был примером ужасного программирования и попытки переделать этот код приводили к многочисленным ошибкам и неработоспособности несмотря на наличие подробных комментариев, поэтому было приятно решение внедрить работу с параметрами и характеристиками в этот код, не обошлось без «костылей». Кнопка Stop, сбрасывает изменения и приводит к первоначальному варианту системы. Итогом стал горизонтально работающий пружинный маятник, который изменяет скорость колебаний в зависимости от массы груза и жесткости пружины, изменение остальных параметров визуально не отображается. В свою защиту скажу, что подобный код самостоятельно я бы писать не стали попытался бы сделать все в соответствии с ООП, но так же я бы не стал делать анимацию на чистом HTML / CSS.