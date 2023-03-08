# if koşulu


```python
yaş=int(input("yaşınızı giriniz:"))
if(yaş<18):
    print("bu mekana giremezsiniz.")
    
```

    yaşınızı giriniz:15
    bu mekana giremezsiniz.
    


```python
yaş=int(input("yaşınızı giriniz:"))
if(yaş>18):
    print("bu mekana girebilirsiniz.")
```

    yaşınızı giriniz:30
    bu mekana girebilirsiniz.
    


```python
kilo=int(input("kilonuzu yazın:"))
if(kilo>120):
    print("obezite.")
    
```

    kilonuzu yazın:146
    obezite.
    


```python
yaş=int(input("yaşınızı giriniz:"))
if(yaş<18):
    print("bu mekana giremezsiniz.")
else:
        print("mekana hoşgeldiniz.")
```

    yaşınızı giriniz:25
    mekana hoşgeldiniz.
    


```python
nemdegeri=int(input("nem oranını giriniz:"))
if(40<nemorani<60):
    print("yeterli")
```

    nem oranını giriniz:55
    


    ---------------------------------------------------------------------------

    NameError                                 Traceback (most recent call last)

    ~\AppData\Local\Temp\ipykernel_12240\1201012640.py in <module>
          1 nemdegeri=int(input("nem oranını giriniz:"))
    ----> 2 if(40<nemorani<60):
          3     print("yeterli")
    

    NameError: name 'nemorani' is not defined



```python

```
