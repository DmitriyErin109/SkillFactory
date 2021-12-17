# Проект 3. О вкусной и здоровой пище

## Оглавление  
[1. Описание проекта](README.md#Описание-проекта)    
[2. Какой кейс решаем?](README.md#Какой-кейс-решаем)  
[3. Краткая информация о данных](README.md#Краткая-информация-о-данных)  
[4. Этапы работы над проектом](README.md#Этапы-работы-над-проектом)  
[5. Результат](README.md#Результаты)    
[6. Выводы](README.md#Выводы)  
[7. Ответы на вопросы саморефлексии](README.md#Ответы-на-вопросы-саморефлексии)

### Описание проекта    
Работа с датасетом, содержащим сведения о 40 000 ресторанах Европы, обучение модели, которая должна будет предсказывать рейтинг ресторана по данным сайта TripAdvisor на основе имеющихся в датасете данных.

:arrow_up:[к оглавлению](README.md#Оглавление)


### Какой кейс решаем? 
Построение модели, которая предсказывает рейтинг ресторана. Если предсказания модели сильно отличаются от фактического результата, то, возможно, ресторан играет нечестно, и его стоит проверить.


### Краткая информация о данных
Первоначальная версия датасета состоит из десяти столбцов, содержащих следующую информацию:

Restaurant_id — идентификационный номер ресторана / сети ресторанов;    
City — город, в котором находится ресторан;     
Cuisine Style — кухня или кухни, к которым можно отнести блюда, предлагаемые в ресторане;       
Ranking — место, которое занимает данный ресторан среди всех ресторанов своего города;      
Rating — рейтинг ресторана по данным TripAdvisor (именно это значение должна будет предсказывать модель);       
Price Range — диапазон цен в ресторане;     
Number of Reviews — количество отзывов о ресторане;     
Reviews — данные о двух отзывах, которые отображаются на сайте ресторана;           
URL_TA — URL страницы ресторана на TripAdvisor;     
ID_TA — идентификатор ресторана в базе данных TripAdvisor.
  
:arrow_up:[к оглавлению](README.md#Оглавление)


### Этапы работы над проектом  
1.Анализ данныз(визуализация и распределение)                                     
2.Feature Engineering  
3.Обучаем модель, генерируем результат      
4.Проверяем корреляцию важных переменных    
5.Загружаем результат на Kaggle


:arrow_up:[к оглавлению](README.md#Оглавление)


### Результаты:  
В результате получили модель, которая достаточно неплохо показывает себя в лидерборде соревнования на Kaggle. (На 16/12/2021  49 место из 760)

:arrow_up:[к оглавлению](README.md#Оглавление)


### Выводы:  
Модель можно улучшить если поэкспериментировать с настройками и типом модели машинного обучения

### Ответы на вопросы саморефлексии: 


1. Какой частью своей работы вы остались особенно довольны?

    *Нахождение интересных фич, эксперимент с модулем emoji*

2. Что не получилось сделать так, как хотелось? Над чем ещё стоит поработать?

    *Неоптимизированы функции написанные на Python*


3. Что интересного и полезного вы узнали в этом модуле?

     *В notebook расположенных на Kaggle много полезной информации(подбор параметров,визуализациия, оформлениее notebook). Парсинг сайта с помощью Selenium*

4. Что является вашим главным результатом при прохождении этого проекта?

    *Результат на Kaggle*


5. Какие навыки вы уже можете применить в текущей деятельности?     

    *Python, Pandas, Matplotlib, Seaborn, Jupyter, GitHub,SQL,Selenium*

7. Планируете ли вы дополнительно изучать материалы по теме проекта?

    *Of course*

:arrow_up:[к оглавлению](README.md#Оглавление)


Если информация по этому проекту покажется вам интересной или полезной, то я буду очень вам благодарен, если отметите репозиторий и профиль ⭐️⭐️⭐️-дами