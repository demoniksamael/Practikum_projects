# Practikum_projects

### В репозитории выложены выполненные проекты в ходе обучения на Аналитика данных в Яндекс.Практикуме.
Все проекты выполнены на языке программирования **Python** с использованием множества библиотек. 
Кроме этого для выполнения двух проектов были использованы СУБД **PostgreSQL**, **Tableau Public** и **MS PowerPoint** для презентаций. \
Для решения задач проектов были применены такие методы, как:
- EDA (исследовательский анализ данных);
- Когортный анализ;
- Событийная аналитика;
- Алгоритмы ML:
  - классификация;
  - кластеризация.
  
Выполненые проекты включают в себя: описание, код, решения, выводы.

Так как в множестве проектов была использована библиотека plotly, графики которой не отображаются на GitHub, 
рекомендую просматривать работы, в которых использовалась эта библиотека (в таблице ниже указаны используемые библиотеки к каждому проекту),
через сайт [http://nbviewer.org/](http://nbviewer.org/).


| Название проекта | Задачи | Инструменты |
| :---------------------: | :---------------------: |:---------------------------:|
| Анализ надежности заемщиков | Исследование влияния семейного положения и количества детей на факт возврата кредита в срок  | *Pandas, PyMystem3* |
| [Анализ рынка общепита в Москве для принятия решения об открытии нового заведения](https://github.com/demoniksamael/Practikum_projects/blob/main/Анализ%20рынка%20общепита%20в%20Москве%20для%20принятия%20решения%20об%20открытии%20нового%20заведения/Анализ%20рынка%20общепита.ipynb) | Исследование рынка, выявление закономерностей, определение расположения объектов | *Pandas, Plotly, Seaborn, NumPy, Re, PyMystem3, MS PowerPoint*, EDA |
| Исследование данных клиентов телеком компании для определения выгодного тарифа | Анализ поведения клиентов оператора сотовой связи | *Pandas, Seaborn, Matplotlib, SciPy, NumPy*, описательная статистика, проверка статистических гипотез |
| [Исследование поведения пользователей мобильного приложения](https://github.com/demoniksamael/Practikum_projects/blob/main/Исследование%20поведения%20пользователей%20мобильного%20приложения/Исследование%20действий%20пользователей%20в%20мобильном%20приложении.ipynb) | Изучение воронки событий, Анализ результатов А/А/В - теста | *Pandas, NumPy, SciPy, Plotly, Math* событийная аналитика, проверка статистичеcких гипотез |
| Исследование спроса пассажиров на рейсы в города России, где проходят крупнейшие фестивали | Произвести выгрузку данных из БД авиакомпании, парсинг координат городов России, визуализировать исследование| PostgreSQL, Pandas, Plotly, Requests, Bs4|
| Исследование стоимости квартир в Санкт-Петербурге | Определение рыночной стоимости недвижимости и типичные параметры квартир | *Pandas, Matplotlib*, EDA|
| Определение критериев успешности компьютерных игр | На основании исторических данных о продажах, оценке пользователей и экспертов, выявить закономерности пределяющие успех | *Pandas, Seaborn, Matplotlib, Plotly, NumPy, SciPy*, описательная статистика, проверка статистических гипотез, EDA|
| Оптимизация маркетинговых затрат в Яндекс.Афише | Анализ продуктовых метрик с целью снижения расходов на рекламу | *Pandas, Seaborn, Matplotlib, Plotly, NumPy,* когортный анализ, продуктовые метрики, юнит-экономика |
| [Построение вероятностной модели прогнозирования оттока пользователей для фитнес-центров](https://github.com/demoniksamael/Practikum_projects/blob/main/Построение%20вероятностной%20модели%20прогнозирования%20оттока%20пользователей%20для%20фитнес-центров/Прогнозирование%20оттока%20клиентов%20фитнес-центра.ipynb)| При помощи алгоритмов ML построить модель, прогнозирующую отток клиентов | *Pandas, Seaborn, Plotly, Scikit-Learn, SciPy*, классификация, кластеризация, машинное обучение |
| [Приоритезация гипотез. Анализ результата А\В - теста](https://github.com/demoniksamael/Practikum_projects/blob/main/Приоритезация%20гипотез.%20Анализ%20результата%20А%5CВ%20-%20теста/Анализ%20АВ%20-%20теста%2C%20приоритезация%20гипотез.ipynb)| Приоритезация гипотез по увеличению выручки, анализ результатов А/В - теста| *Pandas, Math, SciPy, NumPy, Plotly*, проверка статистических гипотез |
| [Создание дашборда по пользовательским просмотрам новостного агрегатора](https://github.com/demoniksamael/Practikum_projects/blob/main/Создание%20дашборда%20по%20пользовательским%20просмотрам%20новостного%20агрегатора/Код%20выгрузки%20файла%20dash_visits_1.ipynb)| Произвести выгрузку данных из БД Яндекс.Дзен кодом в JupyterNotebook, создать дашборд для менеджеров| *Sqlalchemy, Tableau, MS PowerPoint*|