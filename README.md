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
### OPERASI DASAR ARITMATIKA
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
 
 <b> Jika Di Klik Tombol ``` Arithmetic ``` maka akan muncul seperti Berikut </b>
 
 ![Screenshot (196)](https://user-images.githubusercontent.com/73010098/162565001-9c853080-60db-4f7a-aada-eaddb4325d52.png)
 
 ### SELEKSI KONDISI IF ELSE
 ``` html
<html>
<head>
    <title>contoh if-else</title>
</head>
<body>
    <script language ="javascript">
        var nilai = prompt("nilai (0-100): ",0);
        var hasil ="";
        if (nilai >= 60)
        hasil ="lulus";
        else
        hasil = "tidak lulus";
        document.write("hasil; " + hasil);
    </script>
</body>
</html>
```
## OUTPUT
<b> Jika Dimasukan Angka bernilai Lebih dari 60 Maka Hasilnya Akan ``` LULUS ``` Dan Jika Dimasukan Angka Benilai Kurang Dari 60 Maka Hasilnya Akan ``` TIDAK LULUS ```. </b>

![Screenshot (197)](https://user-images.githubusercontent.com/73010098/162565094-f14105cd-4f31-4fcd-8780-8ad50fe0b5e9.png)

<b> Angka Lebih dari 60 </b>

!![Screenshot (197)](https://user-images.githubusercontent.com/73010098/162565214-250977a8-f163-44b9-b44b-31a011435bc8.png)

![Screenshot (198)](https://user-images.githubusercontent.com/73010098/162565218-1f8c46b6-2450-4c69-ad9d-701cd68400ac.png)

<b> Angka Kurang dari 60 </b>

![Screenshot (199)](https://user-images.githubusercontent.com/73010098/162565259-07ab9a7e-519b-4c1a-9c69-0be38152187b.png)

![Screenshot (200)](https://user-images.githubusercontent.com/73010098/162565261-3a99d300-5da2-4941-a39e-f462b4893c24.png)

### PENGGUNAAN OPERATOR SWITCH UNTUK SELEKSI KONDISI
``` html
<html>
<head>
    <title>contoh program javascript</title>

    <script language="javascript">
    function test ()
    {
        val1=window.prompt("input nilai (1-5);")
        switch (val1)
        {
            case "1" :
                document.write("bilangan satu")
                break
            case "2" :
                document.write("bilangan dua")
                break
            case "3" :
                document.write("bilangan tiga")
                break
            case "4" :
                document.write("bilangan empat")
                break
            case "5" :
                document.write("bilangan lima")
                break
            default :
                document.write("bilangan lainnya")
        }
    }
    </script>
</head>
<body>
    <input type="button" name="button1" value="switch" onclick=test()>
</body>
</html>
```
## OUTPUT
![Screenshot (201)](https://user-images.githubusercontent.com/73010098/162565368-a1a3a80f-c606-48dd-b1c1-4e2ab659fb39.png)

<b> Jika Di Klik tombol ``` SWITCH ``` Masukan Angka </b>

![Screenshot (202)](https://user-images.githubusercontent.com/73010098/162565416-0d5266d7-d591-460c-b8f8-f0152655684a.png)

<b> Maka Hasilnya Seperti Berikut </b>

![Screenshot (203)](https://user-images.githubusercontent.com/73010098/162565429-5aed5f3b-9352-47e2-9700-8bd4f4a9171d.png)

## PEMBUATAN FORM
### FORM INPUT
``` html
<html>
<head>
    <script language="javascript">
        function test () {
            var val1=document.kirim.T1.value
            if (val1%2==0)
                document.kirim.T2.value="bilangan genap"
            else
                document.kirim.T2.value="bilangan ganjil" 
        }
    </script>
</head>
<body>
    <form method="POST" name="kirim">
        <p>BIL <input type="text" name="T1" size="20"> MERUPAKAN BIL <input type="text" name="T2" size="20"></p>
        <P><input type="button" value="TEBAK" name="B1" onclick=test()></P>
       
    </form>
</body>
</html>
```
## OUTPUT
![Screenshot (204)](https://user-images.githubusercontent.com/73010098/162565486-dfd5e167-1e13-4ede-9317-08666a40bd28.png)

<b> Isi Kolom ``` BIL ``` dengan angka Lalu Klik Tombol ``` TEBAK ``` Maka akan muncul hasil di Kolom ``` MERUPAKAN BIL ``` <br>
Contohnya Seperti Berikut </b>

![Screenshot (205)](https://user-images.githubusercontent.com/73010098/162565730-cbab35bf-b54a-4b31-a4a3-434428c49a3b.png)











