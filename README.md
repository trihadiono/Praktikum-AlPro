# Praktikum-AlPro
#NAMA : TRI HADIONO
#NIM : 71200536
#GROUP : D
#UNIVERSITAS KRISTEN DUTA WACANA

motor=12000000
bulanan=int(input("Gaji tiap bulan: "))
menabung=int(input("Lama menabung: "))

harian= menabung*bulanan*40/100
dll= menabung*bulanan*10/100
kos= menabung*bulanan*30/100
tabungan=menabung*bulanan*20/100
pengeluaran = harian+dll+kos
lama= motor/tabungan

print("Total tabungan Andi selama 1 tahun: ", tabungan)
print("Total pengeluaran selama 1 tahun: ", pengeluaran)
print("Jadi waktu yang dibutuhkan Andi agar bisa membeli motor tersebut adalah", lama, "tahun")

