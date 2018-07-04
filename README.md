# myfirst-project
test percobaan git

message = ('Hallo Dunia')
nama = ('Rifq Amrulloh Firdaus')
usia = 3
lingkar_perut = 22,5

print(message)
print(nama)
print(usia)
print(lingkar_perut)

if usia <= 17:
    print('maaf belum cukup umur untuk nonton film ini')
    print('Masih Kecil')
else:
    print('Menuju Dewasa')

if lingkar_perut < 30:
    print('Kecil')
elif lingkar_perut < 40:
    print('Sedang')
else:
    print('Gedee')

for i in range(2,3):
    print(message)

while usia > 0:
    print('Usia saat ini %s' % usia)
    print('Masih Hidup')
    usia = usia - 1

daftar_nama =['rifq','zayn','malik','yusuf']
print(daftar_nama)
daftar_nama.append('Aa')
daftar_nama.append('Bule')
print(daftar_nama)

for dn in daftar_nama:
    print('nama lain kamu adalah %s,padahal nama asli kamu yaitu %s' % (dn,nama))

manusia = {}
manusia['nama'] = 'Rifq'
manusia['sex'] = 'Laki-Laki'
manusia['status'] = 'Pelajar/bujang'
print(manusia)
manusia['nama'] = 'Zayn Rifq'
print(manusia)
manusia['alamat'] = 'Purwadadi'
print(manusia)

import json
print(json.dumps(manusia))
