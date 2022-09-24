##  1-Create Compute Engine 
## 2-عمل تحديث للسيرفر بستخدام الامر التالي
```
sudo apt-get update -y
```
## 3-تثبيت الاباتشي2 

```
sudo apt-get install apache2 -y
```
## 4-بعد ذلك نذهب الى المسار التالي 
```
cd /var/www/html/

```
## 5-سوف نجد ملف index.html
### نقوم باستبداله بملف لخر باستخدام 
```
sudo mv index.html aqeel.html 
```
## 6-نقوم بفتح الملف 
```
nano aqeel.html
```

واستبدال محتواه 
### استخدمت الصفحة التالية التي تحتوي على صورة من الانترنيت :
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <title> project </title>
</head>
<body background="https://storage.googleapis.com/gweb-uniblog-publish-prod/original_images/BlogHeader_Set2_D.png">
    <br> <br>
    <h1 align="lift" > <font face="loat" size="20" color= "#00AEEF"> Aqeel ALi</font></h1>
</body>

</html>
```

