---
title: pandas
localeTitle: панд
---
![Everybody loves pandas!](https://pandas.pydata.org/_static/pandas_logo.png "панд")

## панд

[pandas](http://pandas.pydata.org/) - это библиотека Python для анализа данных с использованием фреймов данных. Кадры данных представляют собой таблицы данных, которые можно концептуально сравнить с таблицей. Ученые, знакомые с R, будут чувствовать себя здесь как дома. Панды часто используются вместе с numpy, pyplot и scikit-learn.

### Импорт панд

Это широко используемое соглашение для импорта библиотеки pandas с использованием псевдонима `pd` :

```python
import pandas as pd 
```

## Кадры данных

Кадр данных состоит из нескольких строк и столбца. Каждый столбец представляет собой функцию набора данных, и поэтому имеет имя и тип данных. Каждая строка представляет точку данных через связанные значения признаков. Библиотека pandas позволяет вам манипулировать данными в кадре данных различными способами. У панд есть много возможностей, поэтому следующее просто царапает поверхность, чтобы дать ощущение библиотеке.

## Серии

Серия является базовым типом данных в pandas.A Серия очень похожа на массив (массив NumPy) (фактически он построен поверх объекта массива NumPy). Серия может иметь метки оси, поскольку она может быть проиндексирована метку без индексации номера для размещения данных. Он может содержать любой действительный объект Python, например List, Dictionary и т. Д.

## Загрузка данных из файла csv

Файл `.csv` представляет собой файл _значений, разделенный запятыми_ . Очень распространенный способ хранения данных. Чтобы загрузить такие данные в кадр данных pandas, используйте метод `read_csv` :

```python
df = pd.read_csv(file_path) 
```

Здесь `file_path` может быть локальным путем для файла csv на вашем компьютере или URL-адреса, указывающего на один. Имена столбцов могут быть включены в файл csv или могут передаваться в качестве аргумента. Для получения дополнительной информации об этом и многом другом ознакомьтесь с [документацией](http://pandas.pydata.org/pandas-docs/stable/generated/pandas.read_csv.html?highlight=read_csv#pandas.read_csv) .

## Получение обзора кадра данных

Чтобы показать первые несколько строк фрейма данных, метод `head` полезен (еще раз это должно быть знакомо программистам R):

```python
df.head() 
```

Это покажет первые 5 строк кадра данных.

Чтобы показать больше, чем первые 5 строк, просто поместите количество строк, которые вы хотите распечатать, внутри метода `head` .

```python
df.head(10) 
```

Это покажет первые 10 строк кадра данных.

Чтобы показать последние несколько строк кадра данных, метод `tail` полезен (еще раз это должно быть знакомо программистам R):

```python
df.tail() 
```

Это покажет последние 5 строк кадра данных.

## Подмножество: получение столбца по имени

Кадр данных может быть подмножеством во многих отношениях. Один из самых простых - это получение одного столбца. Например, если в кадре данных `df` содержится столбец с именем `age` , мы можем извлечь его следующим образом:

```python
ages=df["age"] 
```

#### Дополнительная информация:

1.  [панд](http://pandas.pydata.org/)
2.  [read\_csv](http://pandas.pydata.org/pandas-docs/stable/generated/pandas.read_csv.html?highlight=read_csv#pandas.read_csv)
3.  [голова](http://pandas.pydata.org/pandas-docs/stable/generated/pandas.DataFrame.head.html?highlight=head#pandas.DataFrame.head)