# PROJECT-2. Анализ резюме из HeadHunter
Проект предназначен для демонстрации навыков по работе с SQL.
В проекте используется база резюме, выгруженная с сайта поиска вакансий hh.ru
В последствии надо построить модель, которая будет рекомендовать вакансии клиентам агентства, претендующим на позицию Data Scientist.
В проекте будем пользоваться несколькими [таблицами](https://lms.skillfactory.ru/asset-v1:SkillFactory+DST-3.0+28FEB2021+type@asset+block@SQL_pj2_2_1.png):
+ [VACANCIES](https://lms.skillfactory.ru/asset-v1:SkillFactory+DST-3.0+28FEB2021+type@asset+block@SQL_pj2_2_2.png)
Таблица хранит в себе данные по вакансиям.
+ [AREAS](https://lms.skillfactory.ru/asset-v1:SkillFactory+DST-3.0+28FEB2021+type@asset+block@SQL_pj2_2_3.png)
Таблица-справочник, которая хранит код региона и его название.
+ [EMPLOYERS](https://lms.skillfactory.ru/asset-v1:SkillFactory+DST-3.0+28FEB2021+type@asset+block@SQL_pj2_2_4.png)
Таблица-справочник со списком работодателей.
+ [INDUSTRIES](https://lms.skillfactory.ru/asset-v1:SkillFactory+DST-3.0+28FEB2021+type@asset+block@SQL_pj2_2_5.png)
Таблица-справочник вариантов сфер деятельности работодателей.
+ [EMPLOYERS_INDUSTRIES](https://lms.skillfactory.ru/asset-v1:SkillFactory+DST-3.0+28FEB2021+type@asset+block@SQL_pj2_2_6.png)
Дополнительная таблица, которая существует для организации связи между работодателями и сферами их деятельности.

Проект написан на языке программирования Python c использованием библиотек pandas 1.5.2, psycopg2 2.9.9

