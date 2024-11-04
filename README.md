<h1>1. membuat script untuk validasi form</h1>

![image](https://github.com/user-attachments/assets/3a5c243c-27ca-4a26-a627-0f62cb1fe428)

<h1>2. membuat dokumen html dengan nama file</h1>

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <title>Mengenal JavaScript</title>
    </head>
    <body>
        <h1>Pengenalan JavaScript</h1>
        <h3>Contoh dokument.write dan console.log</h3>
        <script>
            document.write("Hello World");
            console.log("Hello World");
        </script>    
    </body>
    </html>

![image](https://github.com/user-attachments/assets/35b0d24b-2841-4025-9d3f-4cea17804300)

<h2>3. pemakaian alert sebagai property window</h2>

      <!DOCTYPE html>
      <html lang="en">
      <head>
           <meta charset="UTF-8">
           <meta name="viewport" content="width=device-width, initial-scale=1.0">
           <title>alert box</title>
       </head>
       <body>
           <script language = "Javascript">
               window.alert("ini merupakan pesan untuk anda");
           </script>
       </body>
       </html>

  ![image](https://github.com/user-attachments/assets/1bd8d4d7-1a91-4935-bc08-04d75de7eb9d)

  <h1>4. Pemakaian method dalam objek</h1>

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Skrip JavaScript</title>
    </head>
    <body>
        percobaan memakai JavaScript:<br>
        <script language = "javascript">
            document.write("Selamat mencoba Javascript<br>");
            document.write("Semoga sukses!");
        </script>
        
    </body>
    </html>
  
  ![image](https://github.com/user-attachments/assets/6348bf22-a607-4f94-9903-e0f232fab9f2)

  <h1>Pemakaian Prompt</h1>
  
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Pemasukan data</title>
    </head>
    <script language = "javascript">
        var nama = prompt("Siapa nama anda?","Masukkan nama anda");
        document.write("hai, "+ nama);
    </script>
    <body>
        
    </body>
    </html>

  ![image](https://github.com/user-attachments/assets/7e5b92ca-59e7-43a8-b387-9c3351c9e318)

  <h1>5. Pembuatan fungsi dan cara pemanggilannya</h1>

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <title>Contoh program javascript </title>
        <script language = "javascript">
            function pesan(){
                alert("Memanggil javascript lewat body onload")
            }
        </script>
    </head>
    <body onload=pesan()>
    </body>
    </html>

  ![image](https://github.com/user-attachments/assets/e48c8f08-3fa5-48c6-ae5b-b46f00cf7ad1)

  <h1>6. Dasar Pemrograman Di Javascript</h1>

    <html>
    <head>
        <title>contoh program javascript</title>
        <script language="javascript">
            function test (val1, val2)
            {
                document.write("<br>"+"perkalian : val1*val2"+"<br>")
                document.write(val1*val2)
                document.write("<br>"+"pembagian : val1/val2 "+"<br>")
                document.write(val1/val2)
                document.write("<br>"+"penjumlahan : val1+val2 "+"<br>")
                document.write(val1+val2)
                document.write("<br>"+"pengurangan : val1-val2 "+"<br>")
                document.write(val1-val2)
                document.write("<br>"+"mmodulus : val1%val2 "+"<br>")
                ocument.write(val1%val2)
            }
        </script>
    </head>
    <body>
        <input type="button" name="button1" value="arithmetic" onclick=test(9,4)>
    </body>
    </html>

![image](https://github.com/user-attachments/assets/5b3a1c41-c5ea-40ef-9c12-8777c16bbe8f)
![image](https://github.com/user-attachments/assets/6d5eb44b-cf72-40cd-a9c0-4575f7ef1a10)


<h1>7. seleksi kondisi (if.else)</h1>

    <html>
    <head>
        <title>contoh if-else</title>
        <script language="javascript">
            var nilai = prompt("nilai (0-100): ", 0);
            var hasil = " ";
            if (nilai >= 60)
            hasil = "lulus";
            else
            hasil = "tidak lulus";
            document.write("hasil: " + hasil);
        </script>
    </head>
    <body>
    </html>

![image](https://github.com/user-attachments/assets/0f57d7c4-27af-4ee9-8917-98a23de96ac7)
![image](https://github.com/user-attachments/assets/410d98f8-2be3-4cb0-9cf4-4e58dd2350c8)
![image](https://github.com/user-attachments/assets/088ea083-ea7f-4878-8e65-7d4d364d5cc4)

<h1>8. Penggunaan operator switch untuk seleksi kondisi</h1>

    <html>
    <head>
        <title>contoh if-else</title>
        <script language="javascript">
                function test() {
                    let val = window.prompt("Input nilai (1-5):")
                    switch (val) {
                        case "1":
                            document.write("Bilangan satu")
                            break
                        case "2":
                            document.write("Bilangan dua")
                            break
                        case "3":
                            document.write("Bilangan tiga")
                            break
                        case "4":
                            document.write("Bilangan empat")
                            break
                        case "5":
                            document.write("Bilangan lima")
                            break
                        default:
                            document.write("Bilangan lainnya")
               }
        }
        </script>
    </head>
    <body>
        <input type="button" name="button1" value="switch" onclick=test()>
    </body>
    </html>

![image](https://github.com/user-attachments/assets/ce80fbba-3282-4580-80dc-0822d2941abf)
![image](https://github.com/user-attachments/assets/5636acea-a546-4402-bfb1-fac77ac52943)
![image](https://github.com/user-attachments/assets/2f03cc7e-1da2-4614-95a3-b76cf6a79ab1)

<h1>9. Form Input</h1>

    <html>
    <head>
        <title>Contoh if-else</title>
        <script language="javascript">
        function test() {
            var val1 = document.kirim.T1.value; // Ganti 'ver' dengan 'var'
            if (val1 % 2 == 0)
                document.kirim.T2.value = "bilangan genap";
            else
                document.kirim.T2.value = "bilangan ganjil";
        }
        </script>
    </head>
    <body>
        <form method="POST" name="kirim">
            <p>BIL <input type="text" name="T1" size="20"> <!-- Ganti T2 dengan T1 -->
            MERUPAKAN BIL <input type="text" name="T2" size="20"></p>
            <p><input type="button" value="TEBAK" name="B1" onclick="test()"></p> <!-- Tambahkan tanda kutip -->
        </form>
    </body>
    </html>

![image](https://github.com/user-attachments/assets/ae72644e-81c0-47ce-8582-ebf39c62931c)

<h1>10. from button</h1>
![image](https://github.com/user-attachments/assets/9e5eb055-d95f-4c34-8f6e-9c017c1c32f9)
![image](https://github.com/user-attachments/assets/81b6dd8e-cf64-44fc-afb4-306c8682acc1)
![image](https://github.com/user-attachments/assets/5b0b10df-df4e-4659-bdfa-9682a94a9072)
![image](https://github.com/user-attachments/assets/725d308b-b592-49d5-a128-e602390cd570)

<h1>11. Html dom</h1>

    <!--
    File: daftar_menu.html
    -->
    <html>
    <head>
        <title>Daftar Menu</title>
        <script>
            function hitung(ele) {
                var total = document.getElementById('total').value;
                total = (total ? parseInt(total) : 0);
                var harga = 0;
    
                if (ele.checked) {
                    harga = ele.value;
                    total += parseInt(harga);
                } else {
                    harga = ele.value;
                    if (total > 0)
                        total -= parseInt(harga);
                }
    
                document.getElementById('total').value = total;
            }
        </script>
    </head>
    <body>
        <h1>Daftar Menu Makanan</h1>
        <label><input type="checkbox" value="5000" id="menu1" onclick="hitung(this);"> Ayam Goreng Rp. 5.000</label><br />
        <label><input type="checkbox" value="500" id="menu2" onclick="hitung(this);"> Tempe Goreng Rp. 500</label><br />
        <label><input type="checkbox" value="2500" id="menu3" onclick="hitung(this);"> Telur Dadar Rp. 2.500</label><hr />
        <strong>Total Bayar: Rp. <input id="total" type="text" /></strong>
    </body>
    </html>

![image](https://github.com/user-attachments/assets/8bc63069-bf48-4b7a-8f7e-a002f3226b61)









