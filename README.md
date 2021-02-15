# Source-Code-Laporan-Praktikum
gajiperjam = int(input("Masukan gaji yang anda inginkan: "))
jumlahjamkerja= int(input("Masukan jumlah jam kerja dalam satu minggu: "))

pendapatan_budi_sblm_pajak = gajiperjam * jumlahjamkerja * 5
print("Jadi pendapatan budi sebelum membayar pajak adalah : ", pendapatan_budi_sblm_pajak)

gaji_budi_setelahpajak = pendapatan_budi_sblm_pajak - (0.14 * pendapatan_budi_sblm_pajak)
print("Jadi gaji budi setelah pajak adalah: ", gaji_budi_setelahpajak)

bayar_baju = 0.1 * gaji_budi_setelahpajak
print ("Jadi uang yang akan budi habiskan untuk baju adalah: ", bayar_baju)

bayar_pensil = 0.01 * gaji_budi_setelahpajak
print ("Jadi uang yang akan budi habiskan untuk pensil adalah: ", bayar_pensil)

sisagaji = gaji_budi_setelahpajak - (bayar_pensil + bayar_baju)
print("Sisa Gaji Rp ", sisagaji)

sedekah = 0.25 * sisagaji
print("Jadi uang yang akan budi sedekahkan adalah: ", sedekah )

sedekah = sedekah /1000
sedekah2 = int(sedekah)
sedekah3 = sedekah2*1000
print(sedekah3)

yatim = 0.3 * sedekah3
print("Jadi uang untuk anak yatim: ", yatim)

dhuafa = 0.7 * sedekah3
print("Jadi uang untuk anak dhuafa: ", dhuafa)
