# М8О-401Б-21 Старцев Иван Романович
Методы, средства и технологии мультимедиа

**1. Выбор начальных условий**

    a. Выбор набора данных для задачи классификации  
       Уникальный для каждого студента.  
       Обоснование: реальная практическая задача.  
    
    b. Выбор набора данных для задачи регрессии  
       Уникальный для каждого студента.  
       Обоснование: реальная практическая задача.  
    
    c. Выбор метрик качества и обоснование их выбора  

**2. Создание бейзлайна и оценка качества**

    a. Обучение моделей из sklearn для классификации и регрессии на выбранных наборах данных  
    
    b. Оценка качества моделей по выбранным метрикам на выбранных наборах данных  

**3. Улучшение бейзлайна**
    
    a. Формулирование гипотез  
       - Препроцессинг данных  
       - Визуализация данных  
       - Формирование новых признаков  
       - Подбор гиперпараметров на кросс-валидации  
    
    b. Проверка гипотез  
    
    c. Формирование улучшенного бейзлайна по результатам проверки гипотез  
    
    d. Обучение моделей с улучшенным бейзлайном для классификации и регрессии  
    
    e. Оценка качества моделей с улучшенным бейзлайном по выбранным метрикам  
    
    f. Сравнение результатов моделей с улучшенным бейзлайном с результатами из пункта 2  
    
    g. Сделать выводы  

**4. Имплементация алгоритма машинного обучения**
    
    a. Самостоятельная имплементация алгоритмов машинного обучения для классификации и регрессии  
    
    b. Обучение имплементированных моделей на выбранных наборах данных  
    
    c. Оценка качества имплементированных моделей по выбранным метрикам  
    
    d. Сравнение результатов имплементированных моделей с результатами из пункта 2  
    
    e. Добавление техник из улучшенного бейзлайна (пункт 3)  
    
    f. Обучение моделей для классификации и регрессии с учетом улучшений  
    
    g. Оценка качества моделей с улучшенным бейзлайном  
    
    h. Сравнение результатов моделей с результатами из пункта 3  
    
    i. Сделать выводы  


В таблице отображены **accuracy** для классификации, **MAE** для регрессии

<table>
    <tr>
        <th rowspan="1">Алгоритм</th>
        <th>Задача</th>
        <th>Бейзлайн</th>
        <th>Улучшенный бейзлайн</th>
        <th>Самостоятельная имплементация алгоритма</th>
    </tr>
    <tr>
        <td rowspan="2">KNN</td>
        <td>классификация</td>
        <td>0.88</td>
        <td>0.93</td>
        <td>0.93</td>
    </tr>
    <tr>
        <td>регрессия</td>
        <td>6.63</td>
        <td>3.21</td>
        <td>3.60</td>
    </tr>
    <tr>
        <td rowspan="2">Линейные модели</td>
        <td>классификация</td>
        <td>0.93</td>
        <td>0.97</td>
        <td>0.88</td>
    </tr>
    <tr>
        <td>регрессия</td>
        <td>2.11</td>
        <td>2.03</td>
        <td>2.07</td>
    </tr>
    <tr>
        <td rowspan="2">Решающее дерево</td>
        <td>классификация</td>
        <td>0.96</td>
        <td>0.97</td>
        <td>0.98</td>
    </tr>
    <tr>
        <td>регрессия</td>
        <td>8.30</td>
        <td>6.56</td>
        <td>2.46</td>
    </tr>
    <tr>
        <td rowspan="2">Случайный лес</td>
        <td>классификация</td>
        <td>0.89</td>
        <td>0.92</td>
        <td>0.68</td>
    </tr>
    <tr>
        <td>регрессия</td>
        <td>7.02</td>
        <td>6.40</td>
        <td>6.31</td>
    </tr>
    <tr>
        <td rowspan="2">Градиентный бустинг</td>
        <td>классификация</td>
        <td>0.90</td>
        <td>0.92</td>
        <td>0.75</td>
    </tr>
    <tr>
        <td>регрессия</td>
        <td>6.78</td>
        <td>6.25</td>
        <td>6.75</td>
    </tr>
</table>


