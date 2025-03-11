        

# روشن کردنled arduino

## توضیحات کلی پروژه:

 led موجود بر روی مدار اردینو را روشن کردیم 

## ابزارهای مورد نیاز:
برد آردوینو (Arduino )


## تصاویر :

![شماتیک مدار](./Screenshot 2025-03-11 191825.png)
![تصویر](./photo17466948188.jpg)


## کد پروژه:

```cpp

int led = 13;
 
void setup () {
pinMode (led, OUTPUT); 
}
Void loop () {
digitalWrite (led, HIGH);
delay (1000);
digitalWrite (led, LOW);
delay (1000);
}

```


