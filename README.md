# <center> Учебный проект Kaggle программы Data Science платформы [Skillfactory](http://skillfactory.ru). </center>

## Оглавление  
[1. Описание учебного проекта](https://github.com/Cherant1976/Kaggle#Описание-учебного-проекта)   
[2. Краткая информация о данных](https://github.com/Cherant1976/Kaggle#Краткая-информация-о-данных)  
[3. Этапы выполнения заданий учебного проекта](https://github.com/Cherant1976/Kaggle#Этапы-выполнения-заданий-учебного-проекта)  
[4. Используемые библиотеки python](https://github.com/Cherant1976/Kaggle#Используемые-библиотеки-python)    

### Описание учебного проекта    
Учебный проект: соревнование на  [**Kaggle**](https://www.kaggle.com/competitions/sf-booking).

:arrow_up:[к оглавлению](https://github.com/Cherant1976/Kaggle#Оглавление)


### Краткая информация о данных:
Доступ к данным предоставлен в рамках обучения [**Kaggle Data**]([https://www.kaggle.com/competitions/sf-booking](https://www.kaggle.com/competitions/sf-booking/data).
  
:arrow_up:[к оглавлению](https://github.com/Cherant1976/Kaggle#Оглавление)

### Этапы выполнения заданий учебного проекта:  
- Изучение вводных данных
- Создание файла формата *ipynb* (**Jupyter Notebook**) 
- Использование кода на *python* для обработки данных и создание новых признаков данных
- Анализ результата

:arrow_up:[к оглавлению](https://github.com/Cherant1976/Kaggle#Оглавление)


### Используемые библиотеки *python*:  
```python
import pandas as pd
import numpy as np
import requests
import seaborn as sns
import re
import time
from geopy.geocoders import Nominatim
from geopy.extra.rate_limiter import RateLimiter
from geopy import distance
from sklearn.model_selection import train_test_split # специальный инструмент для разбивки 
from sklearn.ensemble import RandomForestRegressor # инструмент для создания и обучения модели  
from sklearn import metrics # инструменты для оценки точности модели
```

:arrow_up:[к оглавлению](https://github.com/Cherant1976/Kaggle#Оглавление)
