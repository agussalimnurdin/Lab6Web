# Lab6Web
# Praktikum 6
membuat layout web dengan menggunakan Twitter Bootsrap.
## langkah 1
Buka web Bootstrap https://getbootstrap.com/ lalu download file bootstrap.
![Screenshot (1)](https://user-images.githubusercontent.com/101470912/164892402-2db87b0b-cb3d-4284-abfd-b16a3b3afa27.png)


## langkah 2
Jika sudah di download, masukkan file tersebut kedalam file lab6_css_framework
![Screenshot (4)](https://user-images.githubusercontent.com/101470912/164892418-0a6fa204-14a1-4e5f-8d8d-becf5d65298d.png)

Disini kita akan mendapatkan 2 file, yaitu : css dan js.


## langkah 3
Buat File html didalam dile lab6_css_framework dan masukan kode bootstrapnya, kode tersebut bisa kita ambil dari web bootstrap.

Berikut Kodenya :

<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">

    <title>Hello, world!</title>
  </head>
  <body>
    <h1>Hello, world!</h1>

    <!-- Optional JavaScript; choose one of the two! -->

    <!-- Option 1: Bootstrap Bundle with Popper -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>

    <!-- Option 2: Separate Popper and Bootstrap JS -->
    <!--
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.10.2/dist/umd/popper.min.js" integrity="sha384-7+zCNj/IqJ95wo16oMtfsKbZ9ccEh31eOz1HGyDuCQ6wgnyJNSYdrPa03rtR1zdB" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.min.js" integrity="sha384-QJHtvGhmr9XOIpI6YVutG+2QOK9T+ZnN4kzFN1RtK3zEFEIsxhlmWl5/YESvpZ13" crossorigin="anonymous"></script>
    -->
  </body>
</html>

## langkah 4
setelah itu buatlah layout sederhana seperti yang pernah kita buat di praktikum sebelumnya.

dan dibawah ini adalah kode nya :
## HTML

![Screenshot (7)](https://user-images.githubusercontent.com/101470912/164892502-af85469a-54cf-4a0f-88ee-00f62e286ab0.png)

![Screenshot (8)](https://user-images.githubusercontent.com/101470912/164892510-4f523bf4-80fa-4b0e-a6c8-19027ba467f4.png)

![Screenshot (9)](https://user-images.githubusercontent.com/101470912/164892517-e519dbbc-8958-4f71-8036-b5fbb11c6b8d.png)

![Screenshot (10)](https://user-images.githubusercontent.com/101470912/164892526-c71c5e60-4221-4767-bcd7-bcb7dfd3efaf.png)

![Screenshot (11)](https://user-images.githubusercontent.com/101470912/164892531-380b7d5a-4f41-42a5-a093-c9d8eaf0fb0f.png)

![Screenshot (12)](https://user-images.githubusercontent.com/101470912/164892538-53983f76-25b1-49b9-987f-50ec5375390b.png)


## css

/* Reset CSS */
* {
  margin: 0;
  padding: 0;
 }
 body {
  line-height:1;
  font-size:100%;
  font-family:'Open Sans', sans-serif;
  color:#5a5a5a;
 }
 #container {
  width: 980px;
  margin: 0 auto;
  box-shadow: 0 0 1em #cccccc;
 }
 /* header */
 header {
  padding: 20px;
 }
 header h1 {
  margin: 20px 10px;
  color: #b5b5b5;
 }
 
 /* Navigasi */
  nav {
   display: block;
   background-color: #1f5faa;
  }
  nav a {
   padding: 15px 30px;
   display: inline-block;
   color: #ffffff;
   font-size: 14px;
   text-decoration: none;
   font-weight: bold;
  }
 
  nav a.active,
  nav a:hover {
   background-color: #2b83ea;
  }
 
 /* Hero Panel */
 #hero {
   background-color: #e4e4e5;
   padding: 50px 20px;
   margin-bottom: 20px;
  }
  #hero h1 {
   margin-bottom: 20px;
   font-size: 35px;
  }
  #hero p {
   margin-bottom: 20px;
   font-size: 18px;
   line-height: 25px;
  }
 
 /* Main content */
  #wrapper {
    margin: 0;
  }
  #main {
   float: left;
   width: 640px;
   padding: 20px;
  }
  /* sidebar area */
  #sidebar {
   float: left;
   width: 260px;
   padding: 20px;
  }
 
 /* widget */
 .widget-box {
   border:1px solid #eee;
   margin-bottom:20px;
  }
  .widget-box .title {
   padding:10px 16px;
   background-color:#428bca;
   color:#fff;
   font-size: 20px;
  }
  .widget-box ul {
   list-style-type:none;
  }
  .widget-box li {
   border-bottom:1px solid #eee;
 }
 .widget-box li a {
  padding:10px 16px;
  color:#333;
  display:block;
  text-decoration:none;
 }
 .widget-box li:hover a {
  background-color:#eee;
 }
 .widget-box p {
  padding:15px;
  line-height:25px;
 } 
 
 /* footer */
 footer {
   clear: both;
   background-color:#1d1d1d;
   padding:20px;
   color:#eee;
  }
  
 /* box */
 .box {
   display:block;
   float:left;
   width:33.333333%;
   box-sizing:border-box;
   -moz-box-sizing:border-box;
   -webkit-box-sizing:border-box;
   padding:0 10px;
   text-align:center;
  }
  .box h3 {
   margin: 15px 0;
  }
  .box p {
   line-height: 20px;
   font-size: 14px;
   margin-bottom: 15px;
  }
  .box img {
   border: 0;
   vertical-align: middle;
  }
 
 /* img circle */
  .image-circle {
   border-radius: 50%;
  }
 
 /* row */
  .row {
   margin: 0 -10px;
   box-sizing: border-box;
   -moz-box-sizing: border-box;
   -webkit-box-sizing: border-box;
  }
  .row:after, .row:before,
  .entry:after, .entry:before {
   content:'';
   display:table;
  }
  .row:after,
  .entry:after {
   clear:both;
  } 
 
 /* divider */
  .divider {
   border:0;
   border-top:1px solid #eeeeee;
   margin:40px 0;
  }
 
 /* entry */
  .entry {
   margin: 15px 0;
  }
  .entry h2 {
   margin-bottom: 20px;
  }
  .entry p {
   line-height: 25px;
  }
  .entry img {
   float: left;
   border-radius: 5px;
   margin-right: 15px;
  }
  .entry .right-img {
   float: right;
  } 


## Dan dibawah ini adalah hasil dari Kode Bootstrap di atas :
![gambar 3](screenshot/Screenshot%20(6).png)

## Selesai 

## TERIMA KASIH BANYAK.
![gambar 3](screenshot/2994367789.png)






