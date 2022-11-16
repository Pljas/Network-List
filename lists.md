## RUN
### Main 
```dataview
List name
WHERE status = "MainNet" AND run = true
```


### Test
```dataview
List name
WHERE status = "TestNet" AND run = true
```


### preTest
```dataview
List name
WHERE status = "preTestNet" AND run = false
```




## WATCHING 
### Main 
```dataview
List name
WHERE status = "MainNet" AND run = false
```


### Test
```dataview
List name
WHERE status = "TestNet" AND run = false
```


### preTest
```dataview
List name
WHERE status = "preTestNet" AND run = false
```