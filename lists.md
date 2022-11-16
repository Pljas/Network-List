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
WHERE status = "preTestNet"
```