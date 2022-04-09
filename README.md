# Lab5Web
# BELAJAR JAVA SCRIPT
## Langkah Langkah praktikum
Membuat dokumen HTML dengan nama file <b> lab5_javascript.html </b>
``` html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mengenal JavaScript</title>
</head>
<body>
    <h1>Pengenalan JavaScript</h1>
    <h3>Contoh document.write dan console.log</h3>
    <script>
        document.write("Hello Sunshine");
        console.log("Hello World");
    </script>
    
</body>
</html>
```

## OUTPUT

![image](https://user-images.githubusercontent.com/73010098/162564095-075eefee-3dc1-47ae-9ee5-aedf4582715e.png)

### 1.JAVASCRIPT DASAR
Pemakaian Alert sebagai property window.

``` html
	<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ALERT BOX</title>
</head>
<body>
    <script language = "JavaScript">
        window.alert("ini merupakan pesan untuk anda");
    </script>
    
</body>
</html>
```
## OUTPUT
![image](https://user-images.githubusercontent.com/73010098/162564127-3f405c15-90c5-49f4-adf4-b9a78f91a3f8.png)

### 2. PEMAKAIAN METHOD DALAM OBJEK
``` html
	<!DOCTYPE html>
      	 <html lang="en">
<head>
   <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Skrip javascript</title>
</head>
<body>
    percobaan memakai javascript:<br>
    <script language = "javascript">
        document.write("selamat mencoba java script<br>");
        document.write("semoga sukses:)");
    </script>
</body>
</html>
```
## OUTPUT

![image](https://user-images.githubusercontent.com/73010098/162564164-6d2a6048-d295-4ef9-932e-902328be9cf3.png)

### 3.PEMAKAIAN PROMPT
``` html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pemasukan data</title>
</head>
<body>
    <script language = "javascript">
        var nama = prompt("siapa nama anda?","masukan nama anda");
        document.write("hai, " + nama);
    </script>
</body>
</html>
```
## OUTPUT

![Screenshot (191)](https://user-images.githubusercontent.com/73010098/162564624-18377ab4-ccc6-4dac-9bdf-41d2644b5c62.png)

<b> Jika Dimasukan Nama atau Teks akan muncul Seperti dibawah ini
Saya masukan nama </b> ``` Siti Latifah ```

![Screenshot (192)](https://user-images.githubusercontent.com/73010098/162564698-23ad75cc-c087-4a54-9a38-59604847b5c4.png)

![Screenshot (193)](https://user-images.githubusercontent.com/73010098/162564709-fb3102cf-7397-4579-831d-9d63656e7fb3.png)

### 4.PEMBUATAN FUNGSI DAN CARA MEMANGGILNYA
``` html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>contoh program javascript</title>
    <script language = "javascript">
        function pesan(){
            alert ("memanggil javascript lewat body onload")
        }
    </script>
</head>
<body onload=pesan()>
    
</body>
</html>
```

## OUTPUT

![Screenshot (194)](https://user-images.githubusercontent.com/73010098/162564865-88cab5c2-3a82-4cc1-96d2-b6f871d7b1cf.png)

## DASAR PEMROGRAMAN DI JAVASCRIPT
### 1.OPERASI DASAR ARITMATIKA
``` html
<html>
<head>
    <title>contoh program javascript</title>

    <script language="javascript">
        function test (val1,val2)
        {
            document.write("<br>"+"perkalian : val1*val2 "+"<br>")
            document.write(val1*val2)
            document.write("<br>"+"permbagian : val1/val2 "+"<br>")
            document.write(val1/val2)
            document.write("<br>"+"penjumlahan : val1+val2 "+"<br>")
            document.write(val1+val2)
            document.write("<br>"+"pengurangan : val1-val2 "+"<br>")
            document.write(val1*val2)
            document.write("<br>"+"modulus : val1%val2 "+"<br>")
            document.write(val1%val2)
        }
    </script>
</head> 
<body>
    <input type="button" name="button1" value="arithmetic" onclick=test(5,4)>
</body>  
</html>
```
## OUTPUT
![Screenshot (195)](https://user-images.githubusercontent.com/73010098/162564975-a3124e70-a6d5-4442-8452-9ffb56fbc725.png)
 
 <b> Jika Di Klik Tombol ``` Aritmethic ``` maka akan muncul seperti Berikut </b>
 
 ![Screenshot (196)](https://user-images.githubusercontent.com/73010098/162565001-9c853080-60db-4f7a-aada-eaddb4325d52.png)







