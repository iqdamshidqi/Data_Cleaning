# Data_Cleaning

```python
print("="*50)
print("📊 INFORMASI DASAR DATASET")
print("="*50)
print(data1.info())
print("\n" + "-"*50)
```
Output
```
==================================================
📊 INFORMASI DASAR DATASET
==================================================
<class 'pandas.core.frame.DataFrame'>
RangeIndex: 49841 entries, 0 to 49840
Data columns (total 22 columns):
 #   Column          Non-Null Count  Dtype  
---  ------          --------------  -----  
 0   age             49841 non-null  int64  
 1   job             49841 non-null  object 
 2   marital         49841 non-null  object 
 3   education       49841 non-null  object 
 4   default         49841 non-null  float64
 5   housing         49841 non-null  float64
 6   loan            49841 non-null  float64
 7   level_credit    49841 non-null  object 
 8   contact         49841 non-null  object 
 9   month           49841 non-null  object 
 10  day_of_week     49841 non-null  object 
 11  duration        49841 non-null  int64  
 12  campaign        49841 non-null  int64  
 13  pdays           49841 non-null  int64  
 14  previous        49841 non-null  int64  
 15  poutcome        49841 non-null  object 
 16  emp.var.rate    49841 non-null  float64
 17  cons.price.idx  49841 non-null  float64
 18  cons.conf.idx   49841 non-null  float64
 19  euribor3m       49841 non-null  float64
 20  nr.employed     49841 non-null  float64
 21  y               49841 non-null  object 
dtypes: float64(8), int64(5), object(9)
memory usage: 8.4+ MB
None
```
