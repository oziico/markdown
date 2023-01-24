# MARKDOWN 
# -Başlık-
```
# H1 Ana Başlık
## H2 Alt Başlık
### H3 Alt Başlık
#### H4 Alt Başlık
##### H5 Alt Başlık
###### H6 Alt Başlık  
```
# H1 Ana Başlık
## H2 Alt Başlık
### H3 Alt Başlık
#### H4 Alt Başlık
##### H5 Alt Başlık
###### H6 Alt Başlık  

# -Yazı şeklillendirme-

## -**Kalın Yazı**
```
 **kalın**  veya __kalın__
```
**kalın** veya __kalın__  
  
## -*İtalik Yazı*
```
*italik*  veya  _italik_  
```
*italik*  veya  _italik_ 
## -***Kalın ve İtalik*** 
```
***Kalın ve İtalik***  veya **_Kalın ve İtalik_** veya  ___Kalın ve İtalik___
```
***Kalın ve İtalik***  veya **_Kalın ve İtalik_**
veya  ___Kalın ve İtalik___
## - ~~Üstü Çizili~~
```
~~Üstü Çizili~~
```
~~Üstü Çizili~~  
  
# -Maddeleme ve Sıralama-

## A) -, * veya + kullanabiliriz. 
```
- Ana Eleman
   - Alt Eleman
      - Alt Eleman 

NOT: -, *, veya + hepsi aynı sonucu verir.
```
- Ana Eleman
   - Alt Eleman
      - Alt Eleman 

## B) Sayı ile  sıralamak için  ) veya . kullanabiliriz.
```
1) Eleman1 
2. Eleman2  

Not: . ve ) aynı sonucu verir.
```
1) Eleman1
2. Eleman2

# -Link- 

[link başlığı](link adresi) ile başlıklı link verebiliriz.
```
[Daha fazlası için beni buradan takip edebilirsin](https://github.com/oziico)
```
[Daha fazlası için beni buradan takip edebilirsin](https://github.com/oziico)

Başlık kullanmak istemiyorsak < > arasına linki yazmamız yeterlidir.
```
 <https://github.com/oziico>
```
<https://github.com/oziico>

# -Tablo Oluşturma-

```
|İsim       |Soyisim | Doğum Yılı  |
|:----------|:------:|------------:|  
|Sola yaslı |Ortada  |Sağa yaslı   |

NOT: ikinci satıra dikkat edelim. : solda ise sola yaslı, her iki tarafta ise ortada, sağda ise sağa yaslı olur.
```
|İsim       |Soyisim | Doğum Yılı  |
|:----------|:------:|------------:|  
|Sola yaslı |Ortada  |Sağa yaslı   |

# -Kod Bloğu ve Dil Desteği-

Kod bloğu yaratmak için üç tırnak(```) kullanırız.
```
` ` `
print(Hello,World!)
` ` `
```
```
print(Hello,World!)
```
Dil de belirtebiliriz
```
` ` `python
print("Hello, World!")` ` `
```
```python
print("Hello, World!")
```
```
` ` ` C#
namespace HelloWorld
{
    class Hello {         
        static void Main(string[] args)
        {
            System.Console.WriteLine("Hello World!");
        }
    }
}
` ` `
``` 

``` C#
namespace HelloWorld
{
    class Hello {         
        static void Main(string[] args)
        {
            System.Console.WriteLine("Hello World!");
        }
    }
}
```

# -Alıntı Yapmak-

Alıntı yapmak için > kullanırız.
İç içe alıntı yapmak için >> kullanmalıyız. Alıntı dereceleri arttırılabilir.
```
> Bu bir alıntıdır.
>> Bu da bir alıntıdır.
>>>>>Bu da bir alıntıdır :)
```
> Bu bir alıntıdır.
>> Bu da bir alıntıdır.
>>>>>Bu da bir alıntıdır :)

# -Görsel Ekleme-

![alt yazı](resim adresi) ile görsel ekleyebiliriz
```
![MarkDown](https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/2560px-Markdown-mark.svg.png)
```
![MarkDown](https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/2560px-Markdown-mark.svg.png)

# -To Do list-
```
- [x] 16:00 Toplantı!
- [ ] Market
```
- [x] 16:00 Toplantı!
- [ ] Market

# -Yorum Satırı-
```
<!---
yorum satırı
--->
```


# -Çizgi Ekleme-
3 adet kısa çizgi kullanarak yapabiliriz.
```
--- 
``` 
---
