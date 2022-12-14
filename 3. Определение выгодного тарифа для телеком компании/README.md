# Определение выгодного тарифа для телеком компании

## Описание проекта
##### На основе данных клиентов оператора сотовой связи проанализировать поведение клиентов и поиск оптимального тарифа

### Инструменты:
`Python`
`Pandas`
`Matplotlib`
`numpy`
`SciPy`
`описательная статистика`
`проверка статистических гипотез`
`Seaborn`

## Краткое содержание о проделанной работе
Проведен предварительный анализ использования тарифов на выборке клиентов,
проанализировано поведение клиентов при использовании услуг оператора и
рекомендованы оптимальные наборы услуг для пользователей. Проведена предобработка
данных, их анализ. Проверены гипотезы о различии выручки абонентов разных тарифов и
различии выручки абонентов из Москвы и других регионов.

## Вывод
При проведении анализа мы следали следующие выводы по тарифам:

Тариф **Смарт** :  
Можно сделать вывод, что пользователи тарифа **Смарт** чаще выходят за рамки тарифного плана по звонкам, сообщениям и использованию интернет трафика, но при этом основная масса пользователей стремится укладываться в отведенные лимиты:
* Среднее время разговора пользователей 436 минут, при ограничении тарифа в 500 минут;
* Среднее количество отправленных сообщений 33 штуки, при ограничении тарифа в 50 штук;
* Среднее количество использованного интернет трафика 17 гигабайт, при ограничении тарифа в 15 гигабайт.

Тариф **Ультра** :  
Можно сделать вывод, что пользователи тарифа **Ультра** почти не выходят за рамки отведенного лимата по звонкам, сообщениям и интернет трафика. В основном они даже не тратят большую часть оплачнного тарифа:
* Среднее время разговора пользователей 553 минут, при ограничении тарифа в 3000 минут;
* Среднее количество отправленных сообщений 56 штуки, при ограничении тарифа в 1000 штук;
* Среднее количество использованного интернет трафика 20 гигабайт, при ограничении тарифа в 30 гигабайт.

По двум тарифам, в основном, тратят интернет трафик, такой вывод можно сделать так как пользователи тарифа **Смарт** дополнительно за него переплачивают, а пользовтаели тарифа **Ультра** расходуют больше его чем звонки и сообщения из которых они не тратят даже половины из оплаченой стоимости тарифа.

## Статус проекта
Проект завершен