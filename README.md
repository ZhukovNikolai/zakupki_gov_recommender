# Zakupki_gov_recommender

Recommendation system for searching public tenders on the website zakupki.gov.ru

## Назначение проекта

На 2025 год рынок государственных закупок в России сверхконкуретнтен: стабильная доходность этого источника продаж
требует от поставщиков расширения воронки участий, что влечет большие накладные расходы.

Данный проект является универсальным аналитическим инструментам для отделов продаж поставщиков рынка 44-ФЗ, который
нацелен на повышения конверсии победы/участия.

## Описание проекта

Проект является инструментом для поиска закупок для участия: по параметрам своего бизнеса участники имеют возможность
получить информацию о актуальных торгах по своей сфере, а также ранжировать выдачу по оценке вероятности победы в них,
которая оценивается системой на основе показателей бизнеса, задаваемых пользователем.

## План

1. Получить КЭП для авторизации в ЕИС и получения токена API – 21-01-2025 ✅
2. Разобраться с API ЕИС ([документация](https://zakupki.gov.ru/epz/main/public/document/view.html?searchString=&sectionId=432&strictEqual=false)) – 28.01.2025
3. Выгрузить данные о торгах по ЦФО за последний год и построить baseline рекомендаций – 05.02.2025