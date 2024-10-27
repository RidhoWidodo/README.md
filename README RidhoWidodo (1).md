# Praktikum 3 RidhoWidodo
# 1.) Buat codingan dari flowchart yang menentukan bilangan terbesar dari 3 bilangan yang diinputkan
Berikut adalah flowchart nya
![flowchart 1](https://github.com/user-attachments/assets/58fa9350-bf8a-42dc-b1bd-dfd2531bfa67)
![Screenshot 2024-10-26 204550](https://github.com/user-attachments/assets/21a0a8e7-4a02-4d88-bbfb-b48a91783471)

1. Input bilangan

Pengguna diminta untuk memasukkan tiga bilangan satu per satu. Nilai yang dimasukkan akan dikonversi menjadi tipe data float, yang memungkinkan pengguna memasukkan angka desimal.

2. Penggunaan (if-elif-else):

   -if a > b and a > c: Kondisi ini mengecek apakah a lebih besar dari b dan c. Jika benar, maka a adalah bilangan terbesar, dan program mencetak hasilnya.

   -elif b > a and b > c: Jika kondisi pertama salah, maka program akan mengecek apakah b lebih besar dari a dan c. Jika benar, maka b adalah bilangan terbesar.

   -else: Jika kedua kondisi di atas salah, maka c yang dianggap sebagai bilangan terbesar.

3. Output
   
![Screenshot 2024-10-26 204606](https://github.com/user-attachments/assets/bca82eb8-27ba-4d2b-bde7-c9dca1ddb143)

# 2.) Buat codingan dari flowchart yang menentukan bilangan terbesar dari N bilangan yang diinputkan. untuk menentukan jumlah N, berikan masukkan angka 0
Berikut adalah flowchart nya
![flowchart 2](https://github.com/user-attachments/assets/1c718c70-aec9-4f29-a92c-f1e6ed0088d7)
![Screenshot 2024-10-26 211441](https://github.com/user-attachments/assets/950b8e60-1bf8-4e89-99ed-4d60b35c57ee)

1. Inisialisasi Variabel  terbesar = float('-inf')

   - variabel terbesar diinisialisasi dengan nilai negatif tak terhingga (-inf). Ini dilakukan agar setiap bilangan yang dimasukkan oleh pengguna akan lebih besar dari nilai ini pada awalnya.
     
2. Input Jumlah Bilangan n = int(input("masukkan jumlah bilangan (N) atau 0 untuk mengakhiri: "))

   - Program meminta pengguna untuk memasukkan jumlah bilangan yang ingin dimasukkan. Pengguna dapat memasukkan angka positif untuk menentukan jumlah bilangan atau 0 untuk mengakhiri program.

3. Pengecekan Input Awal  if n == 0: 
    print("Tidak ada bilangan yang dimasukkan.")
    return

   - Jika pengguna memasukkan 0, program akan mencetak pesan bahwa tidak ada bilangan yang dimasukkan dan kemudian keluar dari fungsi dengan menggunakan return.
  
4. Perumusan dan Perbandingan  for i in range(n):
    bilangan = float(input(f"masukkan bilangan ke-{i+1}: "))
    if bilangan > terbesar:
        terbesar = bilangan

   - program akan melakukan iterasi sebanyak n kali. Pada setiap iterasi, pengguna diminta untuk memasukkan bilangan. Program kemudian membandingkan bilangan yang dimasukkan dengan nilai terbesar. Jika bilangan yang dimasukkan lebih besar dari terbesar, maka nilai terbesar akan diperbarui dengan bilangan tersebut.
  
5. Hasil Output  print(f"bilangan terbesar adalah: {terbesar}")

   ![ss hasil flowchart kedua](https://github.com/user-attachments/assets/e6792381-ba40-48c2-89c4-9241e68bfcaa)

   - Setelah semua bilangan dimasukkan dan dibandingkan, program akan mencetak bilangan terbesar yang ditemukan.
  
6. Pemanggilan Fungsi  cari_terbesar_dari_n()

   - Terakhir, fungsi cari_terbesar_dari_n() dipanggil untuk menjalankan program.

   


