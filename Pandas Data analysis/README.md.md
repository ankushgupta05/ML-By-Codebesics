### pandas keywords

#### upto 3 days
```
skiprows()
```



```
header()
```

```
names=[]
```



```
nrows()
```



```
na_values()
```



```
to_csv()
```



```
converters={}
```



```
to_excel()
```



```
sheet_name=''
```



```
startrow
startcol
```



```
ExcelWriter() as Writer:
```


####  day 4
```
parse_dates=[]
```



```
fillna()
```



```
interpolate()
```



```
dropna()
```


#### day 5
```
// [-99999,36] it replace by NaN
df.replace([-99999,36],np.NAN)
```



```
new_df = df.replace({
    'temperature':-99999,
    'event':'-99999',
    'windspeed':-99999
   },np.NAN)

```



```
df.replace('[A-Za-z]','',regex=True)
```



```
new_df = df.replace({
    'temperature':'[A-Za-z]'
    },'',regex=True)

```



```
new_df = df.replace(['exceptional','average','good','average','poor','exceptional'],[1,2,3,4,5,6])

```


#### day 6
```
g = df.groupby('city')
for city,i in g:
    print('City Is : ',city)
    print(i)
```



```
g.get_group('new york')
```



```
g.max()
```


#### day 7
```
india_weather = pd.DataFrame({
    'city':['mumbai','delhi','banglore'],
    'temperature':[32,45,30],
    'humidity':[80,60,75]
})


us_weather = pd.DataFrame({
    'city':['patmumbai','usdelhi','usbanglore'],
    'temperature':[322,435,330],
    'humidity':[801,620,725]
})


// concate both
df = pd.concat([india_weather,us_weather],ignore_index=True)

```



```
temperature_weather = pd.DataFrame({
    'city':['patmumbai','usdelhi','usbanglore'],
    'temperature':[322,435,330],
})

windspeed_weather = pd.DataFrame({
    'city':['patmumbai','usdelhi','usbanglore'],
    'windspeed':[801,620,725]

})



pd.concat([temperature_weather,windspeed_weather],axis=1)
```


#### day 8
```
df1 = pd.DataFrame({
    'city':['aman1','shyam1','monu1'],
    'temperature':[32,43,33],
})


df2 = pd.DataFrame({
    'city':['aman1','shyam1','monu1'],
    'windspeed':[81,20,75]

})

pd.merge(df1,df2)    # by default perform inner joining

```


#### day 11
```
```



```
```



```
```



```
```



```
```



```
```



```
```



```
```



```
```



```
```



```
```



```
```



```
```



```
```



```
```



```
```



```
```



```
```



```
```



```
```



```
```



```
```



```
```



```
```



```
```



```
```



```
```



```
```



```
```



```
```



```
```



```
```



```
```



```
```



```
```



```
```



```
```



```
```



```
```



```
```



```
```



```
```



```
```



```
```



```
```



```
```



```
```



```
```



```
```



```
```



```
```

