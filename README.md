# tugas_perulangan
jumlah = int(input("Jumlah mahasiswa (1-3): "))

if jumlah >= 1:
    if jumlah <= 3:
        total = 0
        for i in range(1, jumlah + 1):
            print("Masukkan nilai mahasiswa", i)
            nilai = int(input("Nilai: "))
            total = total + nilai
        print("Nilai rata-rata:", total / jumlah)
    else:
        print("Jumlah terlalu banyak, maksimal 3")
else:
    print("Jumlah terlalu sedikit, minimal 1")