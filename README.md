# Laba_3_PKG


Описание

В данной лабораторной работе были реализованы методы по обработке цветовых изоюбражений. Для демонстрации результатов работы этих методов были выбраны подходящие изображения, которые можно найти в папке Lab3.

Поэлементные операции

В поэлементные операции входят:

Добавление к изображению целочисленной константы

Преобразование изображения в негатив

Умножение изображения на константу

Степенное преобразование

Логарифмическое преобразование

Линейное контрастирование

Линейное контрастирование расширяет диапазон яркостей и применяется к малоконтрастированным изображениям.

Локальная пороговая обработка

Локальная пороговая обработка характеризуется тем, что изображение разбивается на подобласти, в каждой из которых для сегментации используется свле значение порога.
В этой части лабораторной работы были реализлованы метод Бернсена и метод Ниблацка.

Метод Бернсена Все изображение делится на квадраты. Для каждого пикселя применяется порог.
Метод Ниблацка Для каждого пикселя используется свое значение порога. Определение величины порога происходит на основе вычисления локального среднего и локального среднеквадратичного отклонения.
Для реализации этих методов был использован язык програмирования Python (библиотека OpenCV).
