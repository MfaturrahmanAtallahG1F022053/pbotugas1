# pbotugas1
# tugas1pbo

# TugasPBO
NO 1
![alt text](https://github.com/MuhammadFaturrahmanAtallah/tugas1pbo/blob/main/pbono1.png)
# Perulangan dari 1 hingga 100
for angka in range(1, 101):
    print(angka)
    # Mencetak nama sebanyak 3 kali setiap 10 angka
    if angka % 10 == 0:
        for _ in range(3):
            print("M Faturrahman A")
Penjelasan:
Dalam contoh ini, for angka in range(1, 101): melakukan perulangan dari 1 hingga 100. Di dalam perulangan itu, print(angka) mencetak angka. Selanjutnya, if angka % 10 == 0: memeriksa apakah angka tersebut adalah kelipatan 10. Jika iya, maka perulangan internal for _ in range(3): akan mencetak nama sebanyak tiga kali. Anda dapat mengganti "M Faturrahman A" dengan nama yang sesuai.


NO 2
![alt text](https://github.com/MuhammadFaturrahmanAtallah/TugasPBO/blob/main/pbono2.png)
https://github.com/MuhammadFaturrahmanAtallah/TugasPBO/blob/main/pbono2.png
# Program menggunakan for loops
for i in range(1, 11):
    print(f"Angka: {i}")
 # Menerapkan if-else
if i % 2 == 0:
        print(" - Genap")
    else:
        print(" - Ganjil")
        print("=" * 20)
Penjelasan:
header dari perulangan for. range(1, 11) menghasilkan deret angka dari 1 hingga 10 (inklusif). Variabel i akan mengambil nilai-nilai dari deret tersebut setiap kali perulangan dilakukan.
mencetak nilai i, yang merupakan angka dalam deret perulangan.
struktur if-else. Program memeriksa apakah nilai i habis dibagi 2 atau tidak. Jika habis dibagi 2 (i % 2 == 0), maka itu adalah angka genap, dan pesan " - Genap" dicetak. Jika tidak, itu adalah angka ganjil, dan pesan " - Ganjil" dicetak.
print("=" * 20) Ini mencetak garis pemisah yang terdiri dari karakter "=" sebanyak 20 kali, untuk memisahkan setiap iterasi perulangan.

# Program menggunakan while loops
counter = 1
while counter <= 10:
    print(f"Angka: {counter}")
    # Menerapkan if-else
    if counter % 2 == 0:
        print(" - Genap")
    else:
        print(" - Ganjil")
    print("=" * 20)
    # Menambahkan counter
    counter += 1
Penjelasan:
Variabel counter diinisialisasi dengan nilai 1. Ini akan digunakan untuk melacak iterasi dalam perulangan.
while counter <= 10: Ini adalah header dari perulangan while. Perulangan akan terus berlangsung selama nilai counter kurang dari atau sama dengan 10.
print(f"Angka: {counter}") Ini mencetak nilai counter, yang merupakan angka dalam iterasi perulangan saat ini.
struktur if-else yang memeriksa apakah nilai counter habis dibagi 2 atau tidak. Jika habis dibagi 2 (counter % 2 == 0), maka itu adalah angka genap, dan pesan " - Genap" dicetak. Jika tidak, itu adalah angka ganjil, dan pesan " - Ganjil" dicetak.
print("=" * 20) Ini mencetak garis pemisah yang terdiri dari karakter "=" sebanyak 20 kali, untuk memisahkan setiap iterasi perulangan.
counter += 1 Ini menambahkan 1 pada nilai counter setiap kali iterasi selesai, sehingga menggerakkan perulangan ke iterasi berikutnya.


NO 3
![alt text](https://github.com/MuhammadFaturrahmanAtallah/TugasPBO/blob/main/pbono3.png)
# Membuat variabel dengan tipe data array (list)
my_array = [100, 200, 300, 400, 500]

# Menampilkan semua nilai dalam variabel menggunakan perulangan for
for nilai in my_array:
    print(nilai)
Penjelasan:
Variabel my_array dideklarasikan sebagai list yang berisi nilai-nilai integer. List ini memiliki lima elemen dengan nilai berturut-turut 100, 200, 300, 400, dan 500.
Perulangan for digunakan untuk mengiterasi melalui setiap nilai dalam list my_array. Setiap nilai kemudian dicetak menggunakan perintah print(nilai).
