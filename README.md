# Sogaz_test
Read csv file with pandas.

### Task:
Прочитать csv (если понадобится изменить кодировку файла вручную)

Очистить DataFrame, убрать пустые значения в столбцах если понадобится, привести столбецы к вернуму типу данных

Удалить столбцы если такое необходимо сделать

Изменить названия столбца если нужно

и выполнить функцию

df.groupby(['x1',              'x2',        'x3',        'y1',        'y2',        'y3',        'z1'         ,'z2'        ,'z3', 'values'                ]).sum()#.пропущена_функция()

Выполнить merge основного DataFrame на df_2 = pd.DataFrame({'x1':['x1 1'], 'new_columns':'ok'})

Результирующий датафрейм:

![img.png](img.png)
