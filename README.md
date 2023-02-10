# Praktikum4
### NAMA    : ANDI SETYAWAN
Pada praktek kali ini, saya mencoba membuat program menentukan nilai mahasiswa dengan menggunakan list.

Source Code dan Penjelasan
print("==================================================================") print("| PROGRAM INPUT NILAI MAHASISWA |") print("==================================================================")

nilai = [] ## Membuat list nilai kosong perulangan = True ## Membuat variable perulangan "true" untuk logika looping

while perulangan: ## Looping nama = input("Masukkan Nama: ") ## Membuat variable nama untuk list dan menginputkan datanya nim = input("Masukkan NIM: ") ## Membuat variable nim untuk list dan menginputkan datanya nilaiTugas = int(input("Masukkan Nilai Tugas: ")) ## Membuat variable nilaiTugas untuk list dan menginputkan datanya nilaiUts = int(input("Masukkan Nilai UTS: ")) ## Membuat variable nilaiUts untuk list dan menginputkan datanya nilaiUas = int(input("Masukkan Nilai UAS: ") ## Membuat variable nilaiUas untuk list dan menginputkan datanya nilaiAkhir = (nilaiTugas * 30/100) + (nilaiUts * 35/100) + (nilaiUas * 35/100) ## Membuat variable nilaiAkhir untuk list dan menggabungkan nilaiTugas, uts, dan uas dengan syarat yang sudah ditentukan.