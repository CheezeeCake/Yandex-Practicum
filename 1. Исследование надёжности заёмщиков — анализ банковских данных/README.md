# Исследование надёжности заёмщиков
## Задача проекта <br>
Заказчик — кредитный отдел банка. Нужно разобраться, влияет ли семейное положение и количество детей клиента на факт погашения кредита в срок. Входные данные от банка — статистика о платёжеспособности клиентов.

## Цель
На основе статистики о платёжеспособности клиентов исследовать влияет ли семейное положение и количество детей клиента на факт возврата кредита в срок

Результаты исследования будут учтены при построении модели **кредитного скоринга** — специальной системы, которая оценивает способность потенциального заёмщика вернуть кредит банку.

## Инструменты
`предобработка данных`
`Python`
`Pandas`
`PyMystem3`
`лемматизация`

## Краткое описание проекта
Входные данные от кредитного отдела банка  — статистика о платёжеспособности клиентов. 
Очищены данные от выбросов, пропусков и дубликатов, а также преобразованы разные форматы данных. Заменены типы данных на соответствующие хранящимся данным. Удалены дубликаты. Выделены леммы в значениях столбца и категоризированны данные.
Определена доля кредитоспособных клиентов.
Проанализировано влияние семейного положения и количества детей клиента на факт возврата кредита в срок. 
Построена модель кредитного скоринга — специальной системы, которая оценивает способность потенциального заёмщика вернуть кредит банку.

## Вывод
Из полученных данных можно составить портрет идеального клиента для банка - это человек находящйся в браке, без детей и с очень высоким уровнем дохода. Скорее всего это связано с тем, что у человека есть вторая половинка, которая может помогать финансово, нет лишних затрат на содержание ребенка и при этом у него высокий уровень дохода что дает некую гарантию.

## Статус проекта
Проект завершен