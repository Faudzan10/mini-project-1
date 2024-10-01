# mini-project-1
(MUHAMMAD IRDHAN NUR FAUDZAN)
(2409116077)

Disini saya ingin menjelaskan hasil dari program saya:

   print("________________________________")
print("_____DASAR DASAR PEMOGRAMAN____")
print("_______Mini Project Satu_______")
print("__Muhammad Irdhan Nur Faudzan__")
print("__________2409116077___________")
print("_______________________________")

dibaris 1-6 saya membuat judul program,termasuk nama dan nomor identitas mahasiswa
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------__

# Proses Login
while True:
    print("\n====== LOGIN ====== \n")
    print("MASUKKAN NAMA DAN NIM") 
    NAMA = str(input("Masukkan Nama : "))
    NIM = str(input("Masukkan Akhiran NIM Anda : "))
    if NAMA =="Faudzan" and NIM == "077":
        print("Selamat Datang",NAMA,", " + NIM)
        break
    else:
        pilihan = input("Ulangi Login? (y/n): \n=>")
        if pilihan != "y":
            print("Login Gagal")
            exit("Coba Lagi \n")

dibaris 8-21 
Looping Login: Program ini meminta pengguna untuk memasukkan nama dan NIM.
Pengecekan Login: Jika nama dan NIM yang dimasukkan cocok dengan yang telah ditentukan ("Faudzan" dan "077"), program menyambut pengguna dan keluar dari loop login.
Jika Login Gagal: Jika pengguna memasukkan data yang salah, program menanyakan apakah ingin mencoba lagi. Jika tidak, program akan mencetak pesan "Login Gagal" dan keluar
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------__

# Proses Perhitungan Gaji
while True:    
    jam_kerja = int (input("\nMasukkan Jam Kerja : "))
    gaji_per_jam = int(input ("Masukkan Nominal Gaji Per Jam : Rp. "))

dibaris 23-26 Looping Perhitungan Gaji: Setelah login berhasil, program meminta pengguna untuk memasukkan jam kerja dan gaji per jam.
Perhitungan Gaji: Program menghitung gaji total dengan mengalikan jam kerja dengan gaji per jam.
Bonus: Jika jam kerja lebih dari 160, program menambahkan bonus sebesar 10% dari gaji total.
Output: Program kemudian mencetak total gaji (dengan atau tanpa bonus).
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------_

# Hitung Gaji
    gaji_total = jam_kerja * gaji_per_jam
    if jam_kerja > 160:
        bonus = 0.1 * gaji_total
        total_dengan_bonus = gaji_total + bonus
        print(f"Total Gaji dengan Bonus : Rp. {total_dengan_bonus:}")
    else:
        print(f"Total Gaji tanpa Bonus : Rp. {gaji_total:}")

    ulang = input("Ingin Menghitung Ulang Total Gaji? (boleh/tidak): \n=> ")
    if ulang != "boleh":
        print("\nTerima Kasih Telah Menggunakan Program Ini \n")
        break

dibaris 28-40 program ini jadi aplikasi sederhana untuk menghitung gaji berdasarkan jam kerja dan gaji per jam dengan proses login yang sederhana.
Menggunakan alur seperti loop (while) dan kondisi (if) untuk mengelola interaksi pengguna.
Mengimplementasikan penggunaan input dan output dasar untuk berkomunikasi dengan pengguna

sekian dari laporan program saya 

---------------------------------------------Dokumentasi Out Put Program----------------------------------------------- 
![Masukkan login](https://github.com/user-attachments/assets/8c8f7ba1-3a76-4911-980c-a68e05dacf8f)
jadi pada gambar ini kita masukkan NAMA kita,Nim,Jika benar maka lanjut untung hitung jam kerja

![udah hitung gji](https://github.com/user-attachments/assets/24478ea5-3034-4a9a-97e2-1d00a10074a6)
Lalu pada gambar ini kita masukkan Hitungan Jam Kerja,dan Gaji perjam ,Jika lebih dari 160 jam ,maka dapat gaji bonus

![udahh](https://github.com/user-attachments/assets/88aa444e-8d80-442c-8fce-b314e7c1e461)
Lalu pada gambar ini jika kita memasukkan jam kerja kurang dari 160 jam maka kita tidak mendapatkan bonus gaji,dan bisa dilihat jika ingin lanjut untuk menghitung gaji perhari kita ketik (boleh) jika tidak ingin melanjutkan maka ketik (tidak)
--------------------------------------------------------------------------DOKUMENTASI FLOWCHART-------------------------------------------------------------------------------
![Flowchart Mini Project 1 drawio](https://github.com/user-attachments/assets/fd93ff49-12d8-406f-b98c-93e9e82f89ca)




